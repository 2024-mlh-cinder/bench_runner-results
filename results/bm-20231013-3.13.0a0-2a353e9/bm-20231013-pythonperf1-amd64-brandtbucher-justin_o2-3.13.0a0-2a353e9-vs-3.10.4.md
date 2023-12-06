
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_o2
- machine: windows-amd64
- commit hash: 2a353e9
- commit date: 2023-10-13
- overall geometric mean: 1.06x faster
- HPT reliability: 98.28%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.71 sec: 1.11x faster                                                |
| tornado_http   | 109 ms                                                      | 92.4 ms: 1.18x faster                                                 |
| Geometric mean | (ref)                                                       | 1.14x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.9 ms: 1.08x faster                                                 |
| pidigits       | 145 ms                                                      | 150 ms: 1.04x slower                                                  |
| nbody          | 69.3 ms                                                     | 88.2 ms: 1.27x slower                                                 |
| Geometric mean | (ref)                                                       | 1.07x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 123 ms: 1.07x faster                                                  |
| regex_compile  | 103 ms                                                      | 100 ms: 1.03x faster                                                  |
| regex_effbot   | 1.66 ms                                                     | 1.63 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                       | 1.02x faster                                                          |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|---------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps          | 8.50 ms                                                     | 6.11 ms: 1.39x faster                                                 |
| pickle_pure_python  | 257 us                                                      | 224 us: 1.14x faster                                                  |
| unpickle            | 9.17 us                                                     | 8.08 us: 1.14x faster                                                 |
| xml_etree_parse     | 102 ms                                                      | 92.2 ms: 1.10x faster                                                 |
| tomli_loads         | 1.62 sec                                                    | 1.50 sec: 1.08x faster                                                |
| json_loads          | 14.2 us                                                     | 13.5 us: 1.05x faster                                                 |
| unpickle_list       | 2.81 us                                                     | 2.71 us: 1.04x faster                                                 |
| xml_etree_process   | 43.4 ms                                                     | 44.9 ms: 1.03x slower                                                 |
| xml_etree_iterparse | 63.5 ms                                                     | 68.0 ms: 1.07x slower                                                 |
| pickle_dict         | 16.9 us                                                     | 18.2 us: 1.08x slower                                                 |
| pickle              | 6.80 us                                                     | 7.44 us: 1.09x slower                                                 |
| pickle_list         | 2.59 us                                                     | 2.86 us: 1.11x slower                                                 |
| xml_etree_generate  | 54.5 ms                                                     | 62.7 ms: 1.15x slower                                                 |
| Geometric mean      | (ref)                                                       | 1.03x faster                                                          |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.5 ms: 1.02x faster                                                 |
| python_startup_no_site | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                                 |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.86 ms: 1.28x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 104 us: 3.12x faster                                                  |
| mypy2                    | 352 ms                                                      | 231 ms: 1.52x faster                                                  |
| asyncio_tcp              | 712 ms                                                      | 484 ms: 1.47x faster                                                  |
| async_tree_none          | 420 ms                                                      | 287 ms: 1.46x faster                                                  |
| deltablue                | 4.17 ms                                                     | 2.90 ms: 1.44x faster                                                 |
| async_tree_io            | 1.07 sec                                                    | 765 ms: 1.39x faster                                                  |
| json_dumps               | 8.50 ms                                                     | 6.11 ms: 1.39x faster                                                 |
| async_tree_memoization   | 497 ms                                                      | 367 ms: 1.36x faster                                                  |
| richards_super           | 51.7 ms                                                     | 39.0 ms: 1.32x faster                                                 |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 473 ms: 1.29x faster                                                  |
| mako                     | 8.80 ms                                                     | 6.86 ms: 1.28x faster                                                 |
| raytrace                 | 271 ms                                                      | 213 ms: 1.27x faster                                                  |
| crypto_pyaes             | 62.3 ms                                                     | 50.7 ms: 1.23x faster                                                 |
| sqlglot_parse            | 1.22 ms                                                     | 999 us: 1.22x faster                                                  |
| go                       | 136 ms                                                      | 114 ms: 1.20x faster                                                  |
| sqlglot_transpile        | 1.46 ms                                                     | 1.23 ms: 1.19x faster                                                 |
| tornado_http             | 109 ms                                                      | 92.4 ms: 1.18x faster                                                 |
| chaos                    | 58.9 ms                                                     | 50.4 ms: 1.17x faster                                                 |
| richards                 | 41.2 ms                                                     | 35.5 ms: 1.16x faster                                                 |
| mdp                      | 1.71 sec                                                    | 1.48 sec: 1.16x faster                                                |
| pickle_pure_python       | 257 us                                                      | 224 us: 1.14x faster                                                  |
| scimark_lu               | 85.4 ms                                                     | 74.9 ms: 1.14x faster                                                 |
| unpickle                 | 9.17 us                                                     | 8.08 us: 1.14x faster                                                 |
| pyflate                  | 387 ms                                                      | 348 ms: 1.11x faster                                                  |
| pycparser                | 868 ms                                                      | 781 ms: 1.11x faster                                                  |
| docutils                 | 1.89 sec                                                    | 1.71 sec: 1.11x faster                                                |
| xml_etree_parse          | 102 ms                                                      | 92.2 ms: 1.10x faster                                                 |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.85 sec: 1.10x faster                                                |
| create_gc_cycles         | 782 us                                                      | 714 us: 1.10x faster                                                  |
| scimark_monte_carlo      | 55.9 ms                                                     | 51.6 ms: 1.08x faster                                                 |
| tomli_loads              | 1.62 sec                                                    | 1.50 sec: 1.08x faster                                                |
| float                    | 60.2 ms                                                     | 55.9 ms: 1.08x faster                                                 |
| bench_thread_pool        | 946 us                                                      | 883 us: 1.07x faster                                                  |
| regex_dna                | 132 ms                                                      | 123 ms: 1.07x faster                                                  |
| sqlite_synth             | 1.84 us                                                     | 1.72 us: 1.07x faster                                                 |
| hexiom                   | 5.52 ms                                                     | 5.18 ms: 1.07x faster                                                 |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.52 ms: 1.06x faster                                                 |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                                 |
| json                     | 3.05 ms                                                     | 2.92 ms: 1.04x faster                                                 |
| dulwich_log              | 47.6 ms                                                     | 45.9 ms: 1.04x faster                                                 |
| unpickle_list            | 2.81 us                                                     | 2.71 us: 1.04x faster                                                 |
| logging_silent           | 96.4 ns                                                     | 93.0 ns: 1.04x faster                                                 |
| regex_compile            | 103 ms                                                      | 100 ms: 1.03x faster                                                  |
| regex_effbot             | 1.66 ms                                                     | 1.63 ms: 1.02x faster                                                 |
| python_startup           | 20.0 ms                                                     | 19.5 ms: 1.02x faster                                                 |
| sqlglot_optimize         | 39.0 ms                                                     | 39.2 ms: 1.01x slower                                                 |
| nqueens                  | 67.0 ms                                                     | 67.8 ms: 1.01x slower                                                 |
| pprint_safe_repr         | 589 ms                                                      | 596 ms: 1.01x slower                                                  |
| pprint_pformat           | 1.21 sec                                                    | 1.22 sec: 1.01x slower                                                |
| pathlib                  | 77.4 ms                                                     | 79.0 ms: 1.02x slower                                                 |
| xml_etree_process        | 43.4 ms                                                     | 44.9 ms: 1.03x slower                                                 |
| spectral_norm            | 78.0 ms                                                     | 80.6 ms: 1.03x slower                                                 |
| pidigits                 | 145 ms                                                      | 150 ms: 1.04x slower                                                  |
| sqlglot_normalize        | 202 ms                                                      | 209 ms: 1.04x slower                                                  |
| python_startup_no_site   | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                                 |
| scimark_fft              | 193 ms                                                      | 203 ms: 1.05x slower                                                  |
| comprehensions           | 16.0 us                                                     | 16.9 us: 1.06x slower                                                 |
| deepcopy                 | 255 us                                                      | 273 us: 1.07x slower                                                  |
| xml_etree_iterparse      | 63.5 ms                                                     | 68.0 ms: 1.07x slower                                                 |
| fannkuch                 | 258 ms                                                      | 277 ms: 1.08x slower                                                  |
| pickle_dict              | 16.9 us                                                     | 18.2 us: 1.08x slower                                                 |
| generators               | 31.6 ms                                                     | 34.0 ms: 1.08x slower                                                 |
| bench_mp_pool            | 60.7 ms                                                     | 66.0 ms: 1.09x slower                                                 |
| pickle                   | 6.80 us                                                     | 7.44 us: 1.09x slower                                                 |
| pickle_list              | 2.59 us                                                     | 2.86 us: 1.11x slower                                                 |
| meteor_contest           | 72.5 ms                                                     | 80.4 ms: 1.11x slower                                                 |
| gc_traversal             | 1.34 ms                                                     | 1.49 ms: 1.11x slower                                                 |
| deepcopy_memo            | 28.5 us                                                     | 31.8 us: 1.11x slower                                                 |
| deepcopy_reduce          | 2.16 us                                                     | 2.41 us: 1.12x slower                                                 |
| logging_format           | 6.66 us                                                     | 7.56 us: 1.14x slower                                                 |
| logging_simple           | 6.20 us                                                     | 7.10 us: 1.15x slower                                                 |
| xml_etree_generate       | 54.5 ms                                                     | 62.7 ms: 1.15x slower                                                 |
| coroutines               | 15.9 ms                                                     | 18.9 ms: 1.18x slower                                                 |
| async_generators         | 224 ms                                                      | 273 ms: 1.22x slower                                                  |
| nbody                    | 69.3 ms                                                     | 88.2 ms: 1.27x slower                                                 |
| unpack_sequence          | 37.8 ns                                                     | 48.2 ns: 1.27x slower                                                 |
| telco                    | 3.78 ms                                                     | 4.86 ms: 1.28x slower                                                 |
| coverage                 | 40.0 ms                                                     | 58.7 ms: 1.47x slower                                                 |
| Geometric mean           | (ref)                                                       | 1.06x faster                                                          |

Benchmark hidden because not significant (3): unpickle_pure_python, scimark_sor, regex_v8
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 98.28% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
