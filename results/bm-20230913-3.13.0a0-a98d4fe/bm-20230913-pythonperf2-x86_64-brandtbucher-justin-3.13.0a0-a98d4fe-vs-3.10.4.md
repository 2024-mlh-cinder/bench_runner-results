
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.22x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.95 sec: 1.15x faster                                              |
| tornado_http   | 152 ms                                                       | 122 ms: 1.24x faster                                                |
| Geometric mean | (ref)                                                        | 1.20x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 110 ms                                                       | 84.9 ms: 1.30x faster                                               |
| nbody          | 137 ms                                                       | 127 ms: 1.08x faster                                                |
| pidigits       | 271 ms                                                       | 266 ms: 1.02x faster                                                |
| Geometric mean | (ref)                                                        | 1.13x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 159 ms: 1.22x faster                                                |
| regex_dna      | 259 ms                                                       | 245 ms: 1.06x faster                                                |
| regex_effbot   | 2.99 ms                                                      | 3.50 ms: 1.17x slower                                               |
| Geometric mean | (ref)                                                        | 1.03x faster                                                        |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 317 us: 1.44x faster                                                |
| unpickle_pure_python | 321 us                                                       | 232 us: 1.38x faster                                                |
| json_dumps           | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                               |
| xml_etree_process    | 76.0 ms                                                      | 59.5 ms: 1.28x faster                                               |
| tomli_loads          | 2.97 sec                                                     | 2.44 sec: 1.22x faster                                              |
| json_loads           | 30.0 us                                                      | 25.4 us: 1.18x faster                                               |
| xml_etree_generate   | 94.6 ms                                                      | 85.7 ms: 1.10x faster                                               |
| xml_etree_parse      | 162 ms                                                       | 147 ms: 1.10x faster                                                |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                                |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                               |
| unpickle_list        | 4.49 us                                                      | 4.57 us: 1.02x slower                                               |
| pickle_list          | 4.11 us                                                      | 4.30 us: 1.05x slower                                               |
| unpickle             | 14.2 us                                                      | 14.9 us: 1.05x slower                                               |
| pickle_dict          | 30.0 us                                                      | 32.2 us: 1.07x slower                                               |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                               |
| python_startup_no_site | 7.32 ms                                                      | 8.70 ms: 1.19x slower                                               |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 160 us: 3.26x faster                                                |
| asyncio_tcp              | 782 ms                                                       | 371 ms: 2.11x faster                                                |
| deltablue                | 7.47 ms                                                      | 3.77 ms: 1.98x faster                                               |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                              |
| raytrace                 | 488 ms                                                       | 271 ms: 1.80x faster                                                |
| logging_silent           | 166 ns                                                       | 99.4 ns: 1.67x faster                                               |
| async_tree_none          | 700 ms                                                       | 440 ms: 1.59x faster                                                |
| sqlglot_parse            | 2.26 ms                                                      | 1.44 ms: 1.56x faster                                               |
| generators               | 58.0 ms                                                      | 37.2 ms: 1.56x faster                                               |
| crypto_pyaes             | 118 ms                                                       | 76.6 ms: 1.54x faster                                               |
| bench_mp_pool            | 7.18 ms                                                      | 4.67 ms: 1.54x faster                                               |
| scimark_lu               | 164 ms                                                       | 108 ms: 1.51x faster                                                |
| scimark_monte_carlo      | 109 ms                                                       | 73.4 ms: 1.49x faster                                               |
| async_tree_memoization   | 824 ms                                                       | 555 ms: 1.49x faster                                                |
| richards_super           | 90.8 ms                                                      | 61.2 ms: 1.49x faster                                               |
| chaos                    | 107 ms                                                       | 72.2 ms: 1.48x faster                                               |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                              |
| spectral_norm            | 136 ms                                                       | 92.5 ms: 1.47x faster                                               |
| sqlglot_transpile        | 2.71 ms                                                      | 1.86 ms: 1.45x faster                                               |
| go                       | 259 ms                                                       | 179 ms: 1.44x faster                                                |
| pickle_pure_python       | 457 us                                                       | 317 us: 1.44x faster                                                |
| unpickle_pure_python     | 321 us                                                       | 232 us: 1.38x faster                                                |
| pyflate                  | 697 ms                                                       | 509 ms: 1.37x faster                                                |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 706 ms: 1.35x faster                                                |
| mako                     | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                               |
| richards                 | 74.1 ms                                                      | 55.1 ms: 1.34x faster                                               |
| json_dumps               | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                               |
| float                    | 110 ms                                                       | 84.9 ms: 1.30x faster                                               |
| logging_simple           | 8.90 us                                                      | 6.87 us: 1.30x faster                                               |
| coroutines               | 30.4 ms                                                      | 23.5 ms: 1.29x faster                                               |
| pprint_pformat           | 2.15 sec                                                     | 1.67 sec: 1.29x faster                                              |
| pprint_safe_repr         | 1.05 sec                                                     | 819 ms: 1.28x faster                                                |
| xml_etree_process        | 76.0 ms                                                      | 59.5 ms: 1.28x faster                                               |
| pycparser                | 1.66 sec                                                     | 1.30 sec: 1.28x faster                                              |
| logging_format           | 9.57 us                                                      | 7.54 us: 1.27x faster                                               |
| hexiom                   | 9.52 ms                                                      | 7.64 ms: 1.25x faster                                               |
| tornado_http             | 152 ms                                                       | 122 ms: 1.24x faster                                                |
| deepcopy_memo            | 48.9 us                                                      | 40.0 us: 1.22x faster                                               |
| regex_compile            | 194 ms                                                       | 159 ms: 1.22x faster                                                |
| tomli_loads              | 2.97 sec                                                     | 2.44 sec: 1.22x faster                                              |
| mypy2                    | 466 ms                                                       | 387 ms: 1.21x faster                                                |
| sqlglot_normalize        | 144 ms                                                       | 120 ms: 1.20x faster                                                |
| scimark_sor              | 177 ms                                                       | 148 ms: 1.20x faster                                                |
| deepcopy_reduce          | 4.03 us                                                      | 3.37 us: 1.19x faster                                               |
| json_loads               | 30.0 us                                                      | 25.4 us: 1.18x faster                                               |
| deepcopy                 | 454 us                                                       | 386 us: 1.18x faster                                                |
| bench_thread_pool        | 1.14 ms                                                      | 977 us: 1.16x faster                                                |
| sqlglot_optimize         | 70.3 ms                                                      | 60.6 ms: 1.16x faster                                               |
| json                     | 5.96 ms                                                      | 5.15 ms: 1.16x faster                                               |
| docutils                 | 3.40 sec                                                     | 2.95 sec: 1.15x faster                                              |
| dulwich_log              | 80.1 ms                                                      | 69.9 ms: 1.14x faster                                               |
| fannkuch                 | 496 ms                                                       | 437 ms: 1.14x faster                                                |
| create_gc_cycles         | 1.82 ms                                                      | 1.61 ms: 1.13x faster                                               |
| mdp                      | 3.03 sec                                                     | 2.71 sec: 1.12x faster                                              |
| xml_etree_generate       | 94.6 ms                                                      | 85.7 ms: 1.10x faster                                               |
| xml_etree_parse          | 162 ms                                                       | 147 ms: 1.10x faster                                                |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.10x faster                                               |
| pathlib                  | 21.7 ms                                                      | 20.0 ms: 1.09x faster                                               |
| nbody                    | 137 ms                                                       | 127 ms: 1.08x faster                                                |
| regex_dna                | 259 ms                                                       | 245 ms: 1.06x faster                                                |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                                |
| unpack_sequence          | 59.5 ns                                                      | 57.6 ns: 1.03x faster                                               |
| comprehensions           | 26.9 us                                                      | 26.3 us: 1.03x faster                                               |
| pidigits                 | 271 ms                                                       | 266 ms: 1.02x faster                                                |
| async_generators         | 422 ms                                                       | 415 ms: 1.02x faster                                                |
| nqueens                  | 112 ms                                                       | 111 ms: 1.01x faster                                                |
| meteor_contest           | 137 ms                                                       | 139 ms: 1.01x slower                                                |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                               |
| unpickle_list            | 4.49 us                                                      | 4.57 us: 1.02x slower                                               |
| pickle_list              | 4.11 us                                                      | 4.30 us: 1.05x slower                                               |
| unpickle                 | 14.2 us                                                      | 14.9 us: 1.05x slower                                               |
| pickle_dict              | 30.0 us                                                      | 32.2 us: 1.07x slower                                               |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 5.63 ms: 1.08x slower                                               |
| python_startup           | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                               |
| scimark_fft              | 359 ms                                                       | 398 ms: 1.11x slower                                                |
| gc_traversal             | 3.45 ms                                                      | 3.95 ms: 1.14x slower                                               |
| telco                    | 7.14 ms                                                      | 8.26 ms: 1.16x slower                                               |
| regex_effbot             | 2.99 ms                                                      | 3.50 ms: 1.17x slower                                               |
| python_startup_no_site   | 7.32 ms                                                      | 8.70 ms: 1.19x slower                                               |
| coverage                 | 64.0 ms                                                      | 80.6 ms: 1.26x slower                                               |
| dask                     | 463 ms                                                       | 595 ms: 1.28x slower                                                |
| Geometric mean           | (ref)                                                        | 1.22x faster                                                        |

Benchmark hidden because not significant (1): regex_v8
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
