
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.87 sec: 1.19x faster                                      |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                        |
| Geometric mean | (ref)                                                        | 1.22x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 86.2 ms: 1.59x faster                                       |
| float          | 110 ms                                                       | 80.0 ms: 1.38x faster                                       |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                        | 1.31x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 149 ms: 1.30x faster                                        |
| regex_dna      | 259 ms                                                       | 245 ms: 1.06x faster                                        |
| regex_v8       | 26.6 ms                                                      | 25.5 ms: 1.05x faster                                       |
| regex_effbot   | 2.99 ms                                                      | 3.61 ms: 1.21x slower                                       |
| Geometric mean | (ref)                                                        | 1.05x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 221 us: 1.45x faster                                        |
| pickle_pure_python   | 457 us                                                       | 317 us: 1.44x faster                                        |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                       |
| tomli_loads          | 2.97 sec                                                     | 2.22 sec: 1.34x faster                                      |
| xml_etree_process    | 76.0 ms                                                      | 58.7 ms: 1.30x faster                                       |
| json_loads           | 30.0 us                                                      | 24.9 us: 1.20x faster                                       |
| xml_etree_generate   | 94.6 ms                                                      | 86.0 ms: 1.10x faster                                       |
| xml_etree_parse      | 162 ms                                                       | 150 ms: 1.08x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                        |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                       |
| unpickle             | 14.2 us                                                      | 14.6 us: 1.03x slower                                       |
| unpickle_list        | 4.49 us                                                      | 4.67 us: 1.04x slower                                       |
| pickle_list          | 4.11 us                                                      | 4.37 us: 1.06x slower                                       |
| pickle_dict          | 30.0 us                                                      | 32.6 us: 1.09x slower                                       |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.68 ms: 1.19x slower                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.47x faster                                        |
| asyncio_tcp              | 782 ms                                                       | 371 ms: 2.11x faster                                        |
| deltablue                | 7.47 ms                                                      | 3.66 ms: 2.04x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                      |
| raytrace                 | 488 ms                                                       | 270 ms: 1.81x faster                                        |
| chaos                    | 107 ms                                                       | 62.1 ms: 1.73x faster                                       |
| logging_silent           | 166 ns                                                       | 97.7 ns: 1.70x faster                                       |
| generators               | 58.0 ms                                                      | 34.7 ms: 1.67x faster                                       |
| crypto_pyaes             | 118 ms                                                       | 73.5 ms: 1.61x faster                                       |
| async_tree_none          | 700 ms                                                       | 436 ms: 1.61x faster                                        |
| sqlglot_parse            | 2.26 ms                                                      | 1.41 ms: 1.60x faster                                       |
| scimark_lu               | 164 ms                                                       | 102 ms: 1.60x faster                                        |
| nbody                    | 137 ms                                                       | 86.2 ms: 1.59x faster                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.55 ms: 1.58x faster                                       |
| scimark_monte_carlo      | 109 ms                                                       | 70.1 ms: 1.56x faster                                       |
| go                       | 259 ms                                                       | 170 ms: 1.52x faster                                        |
| spectral_norm            | 136 ms                                                       | 91.2 ms: 1.49x faster                                       |
| async_tree_memoization   | 824 ms                                                       | 552 ms: 1.49x faster                                        |
| sqlglot_transpile        | 2.71 ms                                                      | 1.82 ms: 1.49x faster                                       |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                      |
| hexiom                   | 9.52 ms                                                      | 6.50 ms: 1.46x faster                                       |
| unpickle_pure_python     | 321 us                                                       | 221 us: 1.45x faster                                        |
| pickle_pure_python       | 457 us                                                       | 317 us: 1.44x faster                                        |
| richards_super           | 90.8 ms                                                      | 63.3 ms: 1.44x faster                                       |
| mako                     | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                       |
| float                    | 110 ms                                                       | 80.0 ms: 1.38x faster                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 702 ms: 1.36x faster                                        |
| pyflate                  | 697 ms                                                       | 516 ms: 1.35x faster                                        |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.22 sec: 1.34x faster                                      |
| coroutines               | 30.4 ms                                                      | 23.1 ms: 1.32x faster                                       |
| regex_compile            | 194 ms                                                       | 149 ms: 1.30x faster                                        |
| xml_etree_process        | 76.0 ms                                                      | 58.7 ms: 1.30x faster                                       |
| pycparser                | 1.66 sec                                                     | 1.29 sec: 1.29x faster                                      |
| unpack_sequence          | 59.5 ns                                                      | 46.2 ns: 1.29x faster                                       |
| richards                 | 74.1 ms                                                      | 57.6 ms: 1.29x faster                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.68 sec: 1.29x faster                                      |
| logging_simple           | 8.90 us                                                      | 6.95 us: 1.28x faster                                       |
| deepcopy_memo            | 48.9 us                                                      | 38.3 us: 1.28x faster                                       |
| pprint_safe_repr         | 1.05 sec                                                     | 827 ms: 1.27x faster                                        |
| mypy2                    | 466 ms                                                       | 370 ms: 1.26x faster                                        |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                        |
| nqueens                  | 112 ms                                                       | 89.5 ms: 1.26x faster                                       |
| logging_format           | 9.57 us                                                      | 7.61 us: 1.26x faster                                       |
| sqlglot_normalize        | 144 ms                                                       | 116 ms: 1.24x faster                                        |
| comprehensions           | 26.9 us                                                      | 21.9 us: 1.23x faster                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.24 ms: 1.22x faster                                       |
| fannkuch                 | 496 ms                                                       | 405 ms: 1.22x faster                                        |
| scimark_fft              | 359 ms                                                       | 298 ms: 1.21x faster                                        |
| json_loads               | 30.0 us                                                      | 24.9 us: 1.20x faster                                       |
| sqlglot_optimize         | 70.3 ms                                                      | 58.7 ms: 1.20x faster                                       |
| mdp                      | 3.03 sec                                                     | 2.55 sec: 1.19x faster                                      |
| docutils                 | 3.40 sec                                                     | 2.87 sec: 1.19x faster                                      |
| scimark_sor              | 177 ms                                                       | 150 ms: 1.18x faster                                        |
| deepcopy                 | 454 us                                                       | 384 us: 1.18x faster                                        |
| bench_thread_pool        | 1.14 ms                                                      | 970 us: 1.17x faster                                        |
| dulwich_log              | 80.1 ms                                                      | 68.7 ms: 1.16x faster                                       |
| deepcopy_reduce          | 4.03 us                                                      | 3.47 us: 1.16x faster                                       |
| json                     | 5.96 ms                                                      | 5.16 ms: 1.16x faster                                       |
| pathlib                  | 21.7 ms                                                      | 19.7 ms: 1.10x faster                                       |
| xml_etree_generate       | 94.6 ms                                                      | 86.0 ms: 1.10x faster                                       |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                       |
| xml_etree_parse          | 162 ms                                                       | 150 ms: 1.08x faster                                        |
| create_gc_cycles         | 1.82 ms                                                      | 1.69 ms: 1.08x faster                                       |
| async_generators         | 422 ms                                                       | 393 ms: 1.07x faster                                        |
| regex_dna                | 259 ms                                                       | 245 ms: 1.06x faster                                        |
| regex_v8                 | 26.6 ms                                                      | 25.5 ms: 1.05x faster                                       |
| meteor_contest           | 137 ms                                                       | 131 ms: 1.04x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                        |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                        |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                       |
| unpickle                 | 14.2 us                                                      | 14.6 us: 1.03x slower                                       |
| unpickle_list            | 4.49 us                                                      | 4.67 us: 1.04x slower                                       |
| pickle_list              | 4.11 us                                                      | 4.37 us: 1.06x slower                                       |
| pickle_dict              | 30.0 us                                                      | 32.6 us: 1.09x slower                                       |
| python_startup           | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                       |
| gc_traversal             | 3.45 ms                                                      | 3.83 ms: 1.11x slower                                       |
| telco                    | 7.14 ms                                                      | 8.11 ms: 1.14x slower                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.68 ms: 1.19x slower                                       |
| regex_effbot             | 2.99 ms                                                      | 3.61 ms: 1.21x slower                                       |
| dask                     | 463 ms                                                       | 589 ms: 1.27x slower                                        |
| coverage                 | 64.0 ms                                                      | 81.5 ms: 1.27x slower                                       |
| Geometric mean           | (ref)                                                        | 1.27x faster                                                |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.20x
