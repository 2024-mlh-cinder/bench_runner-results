
# Results vs. 3.10.4

- fork: python
- ref: deea7c82682848b2a0db
- machine: linux-x86_64
- commit hash: deea7c8
- commit date: 2023-09-05
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                                      |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                                        |
| Geometric mean | (ref)                                                        | 1.22x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 87.5 ms: 1.57x faster                                                       |
| float          | 110 ms                                                       | 80.2 ms: 1.38x faster                                                       |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                                        |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 147 ms: 1.32x faster                                                        |
| regex_dna      | 259 ms                                                       | 238 ms: 1.09x faster                                                        |
| regex_v8       | 26.6 ms                                                      | 25.6 ms: 1.04x faster                                                       |
| regex_effbot   | 2.99 ms                                                      | 3.48 ms: 1.16x slower                                                       |
| Geometric mean | (ref)                                                        | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 313 us: 1.46x faster                                                        |
| unpickle_pure_python | 321 us                                                       | 230 us: 1.39x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                                       |
| tomli_loads          | 2.97 sec                                                     | 2.20 sec: 1.35x faster                                                      |
| xml_etree_process    | 76.0 ms                                                      | 58.7 ms: 1.29x faster                                                       |
| json_loads           | 30.0 us                                                      | 24.9 us: 1.20x faster                                                       |
| xml_etree_generate   | 94.6 ms                                                      | 85.7 ms: 1.10x faster                                                       |
| xml_etree_parse      | 162 ms                                                       | 147 ms: 1.10x faster                                                        |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.05x faster                                                        |
| unpickle             | 14.2 us                                                      | 14.4 us: 1.01x slower                                                       |
| pickle               | 9.94 us                                                      | 10.1 us: 1.01x slower                                                       |
| unpickle_list        | 4.49 us                                                      | 4.56 us: 1.01x slower                                                       |
| pickle_list          | 4.11 us                                                      | 4.31 us: 1.05x slower                                                       |
| pickle_dict          | 30.0 us                                                      | 32.1 us: 1.07x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.9 ms: 1.03x slower                                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.84 ms: 1.21x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.2 ms: 1.43x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 148 us: 3.54x faster                                                        |
| asyncio_tcp              | 782 ms                                                       | 369 ms: 2.12x faster                                                        |
| deltablue                | 7.47 ms                                                      | 3.72 ms: 2.01x faster                                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                                      |
| chaos                    | 107 ms                                                       | 61.5 ms: 1.74x faster                                                       |
| raytrace                 | 488 ms                                                       | 282 ms: 1.73x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 71.3 ms: 1.66x faster                                                       |
| logging_silent           | 166 ns                                                       | 100 ns: 1.66x faster                                                        |
| generators               | 58.0 ms                                                      | 35.0 ms: 1.66x faster                                                       |
| scimark_lu               | 164 ms                                                       | 100 ms: 1.63x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 67.6 ms: 1.62x faster                                                       |
| sqlglot_parse            | 2.26 ms                                                      | 1.41 ms: 1.60x faster                                                       |
| async_tree_none          | 700 ms                                                       | 438 ms: 1.60x faster                                                        |
| nbody                    | 137 ms                                                       | 87.5 ms: 1.57x faster                                                       |
| go                       | 259 ms                                                       | 172 ms: 1.50x faster                                                        |
| sqlglot_transpile        | 2.71 ms                                                      | 1.81 ms: 1.50x faster                                                       |
| spectral_norm            | 136 ms                                                       | 91.1 ms: 1.50x faster                                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.81 ms: 1.49x faster                                                       |
| async_tree_memoization   | 824 ms                                                       | 552 ms: 1.49x faster                                                        |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.48x faster                                                      |
| hexiom                   | 9.52 ms                                                      | 6.45 ms: 1.48x faster                                                       |
| richards_super           | 90.8 ms                                                      | 61.7 ms: 1.47x faster                                                       |
| pickle_pure_python       | 457 us                                                       | 313 us: 1.46x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.2 ms: 1.43x faster                                                       |
| unpickle_pure_python     | 321 us                                                       | 230 us: 1.39x faster                                                        |
| float                    | 110 ms                                                       | 80.2 ms: 1.38x faster                                                       |
| pyflate                  | 697 ms                                                       | 515 ms: 1.35x faster                                                        |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 704 ms: 1.35x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                                       |
| tomli_loads              | 2.97 sec                                                     | 2.20 sec: 1.35x faster                                                      |
| richards                 | 74.1 ms                                                      | 55.4 ms: 1.34x faster                                                       |
| deepcopy_memo            | 48.9 us                                                      | 36.9 us: 1.32x faster                                                       |
| regex_compile            | 194 ms                                                       | 147 ms: 1.32x faster                                                        |
| coroutines               | 30.4 ms                                                      | 23.2 ms: 1.31x faster                                                       |
| xml_etree_process        | 76.0 ms                                                      | 58.7 ms: 1.29x faster                                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.02 ms: 1.29x faster                                                       |
| logging_simple           | 8.90 us                                                      | 6.90 us: 1.29x faster                                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.68 sec: 1.28x faster                                                      |
| unpack_sequence          | 59.5 ns                                                      | 46.6 ns: 1.28x faster                                                       |
| fannkuch                 | 496 ms                                                       | 389 ms: 1.27x faster                                                        |
| pycparser                | 1.66 sec                                                     | 1.31 sec: 1.27x faster                                                      |
| pprint_safe_repr         | 1.05 sec                                                     | 826 ms: 1.27x faster                                                        |
| nqueens                  | 112 ms                                                       | 89.5 ms: 1.26x faster                                                       |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                                        |
| logging_format           | 9.57 us                                                      | 7.64 us: 1.25x faster                                                       |
| mypy2                    | 466 ms                                                       | 373 ms: 1.25x faster                                                        |
| sqlglot_normalize        | 144 ms                                                       | 116 ms: 1.24x faster                                                        |
| comprehensions           | 26.9 us                                                      | 21.9 us: 1.23x faster                                                       |
| deepcopy                 | 454 us                                                       | 374 us: 1.21x faster                                                        |
| scimark_fft              | 359 ms                                                       | 298 ms: 1.21x faster                                                        |
| json_loads               | 30.0 us                                                      | 24.9 us: 1.20x faster                                                       |
| scimark_sor              | 177 ms                                                       | 148 ms: 1.20x faster                                                        |
| sqlglot_optimize         | 70.3 ms                                                      | 59.1 ms: 1.19x faster                                                       |
| deepcopy_reduce          | 4.03 us                                                      | 3.39 us: 1.19x faster                                                       |
| docutils                 | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                                      |
| mdp                      | 3.03 sec                                                     | 2.57 sec: 1.18x faster                                                      |
| bench_thread_pool        | 1.14 ms                                                      | 974 us: 1.17x faster                                                        |
| json                     | 5.96 ms                                                      | 5.13 ms: 1.16x faster                                                       |
| dulwich_log              | 80.1 ms                                                      | 69.4 ms: 1.15x faster                                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.61 ms: 1.13x faster                                                       |
| xml_etree_generate       | 94.6 ms                                                      | 85.7 ms: 1.10x faster                                                       |
| xml_etree_parse          | 162 ms                                                       | 147 ms: 1.10x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                                       |
| regex_dna                | 259 ms                                                       | 238 ms: 1.09x faster                                                        |
| pathlib                  | 21.7 ms                                                      | 20.2 ms: 1.07x faster                                                       |
| meteor_contest           | 137 ms                                                       | 128 ms: 1.07x faster                                                        |
| async_generators         | 422 ms                                                       | 399 ms: 1.06x faster                                                        |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.05x faster                                                        |
| regex_v8                 | 26.6 ms                                                      | 25.6 ms: 1.04x faster                                                       |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                                        |
| unpickle                 | 14.2 us                                                      | 14.4 us: 1.01x slower                                                       |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.01x slower                                                       |
| unpickle_list            | 4.49 us                                                      | 4.56 us: 1.01x slower                                                       |
| gc_traversal             | 3.45 ms                                                      | 3.53 ms: 1.02x slower                                                       |
| python_startup           | 11.5 ms                                                      | 11.9 ms: 1.03x slower                                                       |
| pickle_list              | 4.11 us                                                      | 4.31 us: 1.05x slower                                                       |
| pickle_dict              | 30.0 us                                                      | 32.1 us: 1.07x slower                                                       |
| telco                    | 7.14 ms                                                      | 8.05 ms: 1.13x slower                                                       |
| regex_effbot             | 2.99 ms                                                      | 3.48 ms: 1.16x slower                                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.84 ms: 1.21x slower                                                       |
| dask                     | 463 ms                                                       | 591 ms: 1.28x slower                                                        |
| coverage                 | 64.0 ms                                                      | 83.9 ms: 1.31x slower                                                       |
| Geometric mean           | (ref)                                                        | 1.28x faster                                                                |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
