
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                      |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                        |
| Geometric mean | (ref)                                                        | 1.22x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 85.7 ms: 1.60x faster                                       |
| float          | 110 ms                                                       | 80.4 ms: 1.37x faster                                       |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                        | 1.31x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 148 ms: 1.31x faster                                        |
| regex_dna      | 259 ms                                                       | 248 ms: 1.04x faster                                        |
| regex_v8       | 26.6 ms                                                      | 25.9 ms: 1.03x faster                                       |
| regex_effbot   | 2.99 ms                                                      | 3.68 ms: 1.23x slower                                       |
| Geometric mean | (ref)                                                        | 1.03x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 309 us: 1.48x faster                                        |
| unpickle_pure_python | 321 us                                                       | 225 us: 1.42x faster                                        |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                       |
| tomli_loads          | 2.97 sec                                                     | 2.25 sec: 1.32x faster                                      |
| xml_etree_process    | 76.0 ms                                                      | 57.9 ms: 1.31x faster                                       |
| json_loads           | 30.0 us                                                      | 25.6 us: 1.17x faster                                       |
| xml_etree_generate   | 94.6 ms                                                      | 85.7 ms: 1.10x faster                                       |
| xml_etree_parse      | 162 ms                                                       | 149 ms: 1.08x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                        |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                       |
| pickle_dict          | 30.0 us                                                      | 31.8 us: 1.06x slower                                       |
| unpickle_list        | 4.49 us                                                      | 4.80 us: 1.07x slower                                       |
| unpickle             | 14.2 us                                                      | 15.2 us: 1.07x slower                                       |
| pickle_list          | 4.11 us                                                      | 4.50 us: 1.09x slower                                       |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.9 ms: 1.03x slower                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.86 ms: 1.21x slower                                       |
| Geometric mean         | (ref)                                                        | 1.12x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.2 ms: 1.43x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 149 us: 3.50x faster                                        |
| asyncio_tcp              | 782 ms                                                       | 370 ms: 2.11x faster                                        |
| deltablue                | 7.47 ms                                                      | 3.66 ms: 2.04x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                      |
| raytrace                 | 488 ms                                                       | 271 ms: 1.80x faster                                        |
| chaos                    | 107 ms                                                       | 61.2 ms: 1.75x faster                                       |
| logging_silent           | 166 ns                                                       | 98.2 ns: 1.69x faster                                       |
| scimark_lu               | 164 ms                                                       | 98.6 ms: 1.66x faster                                       |
| crypto_pyaes             | 118 ms                                                       | 71.7 ms: 1.65x faster                                       |
| generators               | 58.0 ms                                                      | 35.3 ms: 1.64x faster                                       |
| scimark_monte_carlo      | 109 ms                                                       | 66.8 ms: 1.64x faster                                       |
| async_tree_none          | 700 ms                                                       | 436 ms: 1.61x faster                                        |
| nbody                    | 137 ms                                                       | 85.7 ms: 1.60x faster                                       |
| sqlglot_parse            | 2.26 ms                                                      | 1.42 ms: 1.59x faster                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.68 ms: 1.53x faster                                       |
| go                       | 259 ms                                                       | 170 ms: 1.52x faster                                        |
| spectral_norm            | 136 ms                                                       | 90.3 ms: 1.51x faster                                       |
| async_tree_memoization   | 824 ms                                                       | 547 ms: 1.51x faster                                        |
| richards_super           | 90.8 ms                                                      | 60.3 ms: 1.51x faster                                       |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                      |
| sqlglot_transpile        | 2.71 ms                                                      | 1.82 ms: 1.49x faster                                       |
| pickle_pure_python       | 457 us                                                       | 309 us: 1.48x faster                                        |
| hexiom                   | 9.52 ms                                                      | 6.44 ms: 1.48x faster                                       |
| mako                     | 14.7 ms                                                      | 10.2 ms: 1.43x faster                                       |
| unpickle_pure_python     | 321 us                                                       | 225 us: 1.42x faster                                        |
| pyflate                  | 697 ms                                                       | 504 ms: 1.38x faster                                        |
| float                    | 110 ms                                                       | 80.4 ms: 1.37x faster                                       |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 696 ms: 1.37x faster                                        |
| richards                 | 74.1 ms                                                      | 54.2 ms: 1.37x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.25 sec: 1.32x faster                                      |
| deepcopy_memo            | 48.9 us                                                      | 37.2 us: 1.32x faster                                       |
| xml_etree_process        | 76.0 ms                                                      | 57.9 ms: 1.31x faster                                       |
| regex_compile            | 194 ms                                                       | 148 ms: 1.31x faster                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.65 sec: 1.31x faster                                      |
| pprint_safe_repr         | 1.05 sec                                                     | 805 ms: 1.30x faster                                        |
| coroutines               | 30.4 ms                                                      | 23.4 ms: 1.30x faster                                       |
| logging_simple           | 8.90 us                                                      | 6.85 us: 1.30x faster                                       |
| fannkuch                 | 496 ms                                                       | 385 ms: 1.29x faster                                        |
| logging_format           | 9.57 us                                                      | 7.43 us: 1.29x faster                                       |
| pycparser                | 1.66 sec                                                     | 1.29 sec: 1.29x faster                                      |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                        |
| mypy2                    | 466 ms                                                       | 371 ms: 1.26x faster                                        |
| nqueens                  | 112 ms                                                       | 89.7 ms: 1.25x faster                                       |
| sqlglot_normalize        | 144 ms                                                       | 115 ms: 1.25x faster                                        |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.16 ms: 1.25x faster                                       |
| scimark_sor              | 177 ms                                                       | 145 ms: 1.22x faster                                        |
| deepcopy                 | 454 us                                                       | 373 us: 1.22x faster                                        |
| comprehensions           | 26.9 us                                                      | 22.2 us: 1.22x faster                                       |
| sqlglot_optimize         | 70.3 ms                                                      | 58.6 ms: 1.20x faster                                       |
| mdp                      | 3.03 sec                                                     | 2.54 sec: 1.19x faster                                      |
| scimark_fft              | 359 ms                                                       | 301 ms: 1.19x faster                                        |
| deepcopy_reduce          | 4.03 us                                                      | 3.38 us: 1.19x faster                                       |
| docutils                 | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                      |
| json_loads               | 30.0 us                                                      | 25.6 us: 1.17x faster                                       |
| bench_thread_pool        | 1.14 ms                                                      | 978 us: 1.16x faster                                        |
| json                     | 5.96 ms                                                      | 5.17 ms: 1.15x faster                                       |
| dulwich_log              | 80.1 ms                                                      | 69.6 ms: 1.15x faster                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.62 ms: 1.13x faster                                       |
| unpack_sequence          | 59.5 ns                                                      | 53.0 ns: 1.12x faster                                       |
| xml_etree_generate       | 94.6 ms                                                      | 85.7 ms: 1.10x faster                                       |
| sqlite_synth             | 2.97 us                                                      | 2.69 us: 1.10x faster                                       |
| pathlib                  | 21.7 ms                                                      | 19.7 ms: 1.10x faster                                       |
| xml_etree_parse          | 162 ms                                                       | 149 ms: 1.08x faster                                        |
| async_generators         | 422 ms                                                       | 395 ms: 1.07x faster                                        |
| meteor_contest           | 137 ms                                                       | 129 ms: 1.06x faster                                        |
| regex_dna                | 259 ms                                                       | 248 ms: 1.04x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                        |
| regex_v8                 | 26.6 ms                                                      | 25.9 ms: 1.03x faster                                       |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                        |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                       |
| gc_traversal             | 3.45 ms                                                      | 3.53 ms: 1.02x slower                                       |
| python_startup           | 11.5 ms                                                      | 11.9 ms: 1.03x slower                                       |
| pickle_dict              | 30.0 us                                                      | 31.8 us: 1.06x slower                                       |
| unpickle_list            | 4.49 us                                                      | 4.80 us: 1.07x slower                                       |
| unpickle                 | 14.2 us                                                      | 15.2 us: 1.07x slower                                       |
| pickle_list              | 4.11 us                                                      | 4.50 us: 1.09x slower                                       |
| telco                    | 7.14 ms                                                      | 8.09 ms: 1.13x slower                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.86 ms: 1.21x slower                                       |
| regex_effbot             | 2.99 ms                                                      | 3.68 ms: 1.23x slower                                       |
| dask                     | 463 ms                                                       | 586 ms: 1.26x slower                                        |
| coverage                 | 64.0 ms                                                      | 84.3 ms: 1.32x slower                                       |
| Geometric mean           | (ref)                                                        | 1.28x faster                                                |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.21x
