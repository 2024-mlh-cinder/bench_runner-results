
# Results vs. base

- fork: python
- ref: a9574c68f04695eecd19
- machine: windows-amd64
- commit hash: a9574c6
- commit date: 2023-12-02
- overall geometric mean: 1.03x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 227 ms                                                                                                                             | 217 ms: 1.04x faster                                                                                                   |
| chameleon      | 5.24 ms                                                                                                                            | 5.17 ms: 1.01x faster                                                                                                  |
| docutils       | 1.65 sec                                                                                                                           | 1.59 sec: 1.03x faster                                                                                                 |
| tornado_http   | 90.6 ms                                                                                                                            | 88.0 ms: 1.03x faster                                                                                                  |
| Geometric mean | (ref)                                                                                                                              | 1.03x faster                                                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| async_tree_memoization    | 356 ms                                                                                                                             | 346 ms: 1.03x faster                                                                                                   |
| async_tree_memoization_tg | 379 ms                                                                                                                             | 369 ms: 1.03x faster                                                                                                   |
| async_tree_none           | 276 ms                                                                                                                             | 270 ms: 1.02x faster                                                                                                   |
| async_tree_io             | 752 ms                                                                                                                             | 738 ms: 1.02x faster                                                                                                   |
| async_tree_cpu_io_mixed   | 467 ms                                                                                                                             | 459 ms: 1.02x faster                                                                                                   |
| async_tree_none_tg        | 290 ms                                                                                                                             | 287 ms: 1.01x faster                                                                                                   |
| Geometric mean            | (ref)                                                                                                                              | 1.02x faster                                                                                                           |

Benchmark hidden because not significant (2): async_tree_io_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| nbody          | 81.7 ms                                                                                                                            | 74.2 ms: 1.10x faster                                                                                                  |
| float          | 57.6 ms                                                                                                                            | 54.5 ms: 1.06x faster                                                                                                  |
| Geometric mean | (ref)                                                                                                                              | 1.05x faster                                                                                                           |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_v8       | 19.5 ms                                                                                                                            | 15.4 ms: 1.27x faster                                                                                                  |
| regex_compile  | 92.1 ms                                                                                                                            | 86.5 ms: 1.07x faster                                                                                                  |
| regex_dna      | 119 ms                                                                                                                             | 121 ms: 1.01x slower                                                                                                   |
| Geometric mean | (ref)                                                                                                                              | 1.07x faster                                                                                                           |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_pure_python | 146 us                                                                                                                             | 135 us: 1.08x faster                                                                                                   |
| pickle_list          | 3.10 us                                                                                                                            | 2.88 us: 1.07x faster                                                                                                  |
| xml_etree_iterparse  | 67.6 ms                                                                                                                            | 64.8 ms: 1.04x faster                                                                                                  |
| xml_etree_process    | 39.8 ms                                                                                                                            | 39.0 ms: 1.02x faster                                                                                                  |
| json_dumps           | 5.86 ms                                                                                                                            | 5.74 ms: 1.02x faster                                                                                                  |
| json_loads           | 13.4 us                                                                                                                            | 13.4 us: 1.00x slower                                                                                                  |
| pickle_pure_python   | 192 us                                                                                                                             | 194 us: 1.01x slower                                                                                                   |
| pickle_dict          | 18.3 us                                                                                                                            | 18.5 us: 1.01x slower                                                                                                  |
| unpickle_list        | 2.57 us                                                                                                                            | 2.60 us: 1.01x slower                                                                                                  |
| pickle               | 6.89 us                                                                                                                            | 7.03 us: 1.02x slower                                                                                                  |
| tomli_loads          | 1.49 sec                                                                                                                           | 1.54 sec: 1.03x slower                                                                                                 |
| Geometric mean       | (ref)                                                                                                                              | 1.01x faster                                                                                                           |

Benchmark hidden because not significant (3): xml_etree_generate, xml_etree_parse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| python_startup_no_site | 18.5 ms                                                                                                                            | 18.0 ms: 1.03x faster                                                                                                  |
| python_startup         | 20.5 ms                                                                                                                            | 20.1 ms: 1.02x faster                                                                                                  |
| Geometric mean         | (ref)                                                                                                                              | 1.02x faster                                                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|-----------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| mako      | 7.37 ms                                                                                                                            | 6.93 ms: 1.06x faster                                                                                                  |

All benchmarks:
===============

| Benchmark                 | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| spectral_norm             | 81.5 ms                                                                                                                            | 63.2 ms: 1.29x faster                                                                                                  |
| regex_v8                  | 19.5 ms                                                                                                                            | 15.4 ms: 1.27x faster                                                                                                  |
| deltablue                 | 2.76 ms                                                                                                                            | 2.21 ms: 1.24x faster                                                                                                  |
| scimark_sparse_mat_mult   | 3.08 ms                                                                                                                            | 2.50 ms: 1.23x faster                                                                                                  |
| hexiom                    | 5.08 ms                                                                                                                            | 4.24 ms: 1.20x faster                                                                                                  |
| comprehensions            | 13.2 us                                                                                                                            | 11.1 us: 1.19x faster                                                                                                  |
| scimark_monte_carlo       | 49.8 ms                                                                                                                            | 42.3 ms: 1.18x faster                                                                                                  |
| scimark_fft               | 207 ms                                                                                                                             | 186 ms: 1.11x faster                                                                                                   |
| nbody                     | 81.7 ms                                                                                                                            | 74.2 ms: 1.10x faster                                                                                                  |
| chaos                     | 45.0 ms                                                                                                                            | 41.3 ms: 1.09x faster                                                                                                  |
| fannkuch                  | 273 ms                                                                                                                             | 251 ms: 1.09x faster                                                                                                   |
| unpickle_pure_python      | 146 us                                                                                                                             | 135 us: 1.08x faster                                                                                                   |
| crypto_pyaes              | 49.0 ms                                                                                                                            | 45.3 ms: 1.08x faster                                                                                                  |
| pickle_list               | 3.10 us                                                                                                                            | 2.88 us: 1.07x faster                                                                                                  |
| raytrace                  | 184 ms                                                                                                                             | 172 ms: 1.07x faster                                                                                                   |
| pyflate                   | 325 ms                                                                                                                             | 304 ms: 1.07x faster                                                                                                   |
| regex_compile             | 92.1 ms                                                                                                                            | 86.5 ms: 1.07x faster                                                                                                  |
| sympy_integrate           | 13.6 ms                                                                                                                            | 12.8 ms: 1.06x faster                                                                                                  |
| mako                      | 7.37 ms                                                                                                                            | 6.93 ms: 1.06x faster                                                                                                  |
| bench_mp_pool             | 68.5 ms                                                                                                                            | 64.6 ms: 1.06x faster                                                                                                  |
| sympy_str                 | 173 ms                                                                                                                             | 164 ms: 1.06x faster                                                                                                   |
| float                     | 57.6 ms                                                                                                                            | 54.5 ms: 1.06x faster                                                                                                  |
| pprint_pformat            | 1.12 sec                                                                                                                           | 1.06 sec: 1.06x faster                                                                                                 |
| sympy_sum                 | 89.8 ms                                                                                                                            | 85.2 ms: 1.05x faster                                                                                                  |
| typing_runtime_protocols  | 83.4 us                                                                                                                            | 79.2 us: 1.05x faster                                                                                                  |
| asyncio_tcp               | 484 ms                                                                                                                             | 460 ms: 1.05x faster                                                                                                   |
| pprint_safe_repr          | 549 ms                                                                                                                             | 523 ms: 1.05x faster                                                                                                   |
| xml_etree_iterparse       | 67.6 ms                                                                                                                            | 64.8 ms: 1.04x faster                                                                                                  |
| 2to3                      | 227 ms                                                                                                                             | 217 ms: 1.04x faster                                                                                                   |
| go                        | 96.3 ms                                                                                                                            | 92.8 ms: 1.04x faster                                                                                                  |
| meteor_contest            | 77.6 ms                                                                                                                            | 75.1 ms: 1.03x faster                                                                                                  |
| docutils                  | 1.65 sec                                                                                                                           | 1.59 sec: 1.03x faster                                                                                                 |
| sympy_expand              | 290 ms                                                                                                                             | 281 ms: 1.03x faster                                                                                                   |
| nqueens                   | 66.3 ms                                                                                                                            | 64.2 ms: 1.03x faster                                                                                                  |
| mypy2                     | 439 ms                                                                                                                             | 426 ms: 1.03x faster                                                                                                   |
| tornado_http              | 90.6 ms                                                                                                                            | 88.0 ms: 1.03x faster                                                                                                  |
| sqlglot_optimize          | 37.1 ms                                                                                                                            | 36.0 ms: 1.03x faster                                                                                                  |
| async_tree_memoization    | 356 ms                                                                                                                             | 346 ms: 1.03x faster                                                                                                   |
| python_startup_no_site    | 18.5 ms                                                                                                                            | 18.0 ms: 1.03x faster                                                                                                  |
| dask                      | 268 ms                                                                                                                             | 261 ms: 1.03x faster                                                                                                   |
| sqlglot_normalize         | 195 ms                                                                                                                             | 190 ms: 1.03x faster                                                                                                   |
| async_tree_memoization_tg | 379 ms                                                                                                                             | 369 ms: 1.03x faster                                                                                                   |
| sqlglot_parse             | 849 us                                                                                                                             | 829 us: 1.02x faster                                                                                                   |
| gc_traversal              | 1.53 ms                                                                                                                            | 1.49 ms: 1.02x faster                                                                                                  |
| async_tree_none           | 276 ms                                                                                                                             | 270 ms: 1.02x faster                                                                                                   |
| xml_etree_process         | 39.8 ms                                                                                                                            | 39.0 ms: 1.02x faster                                                                                                  |
| async_generators          | 245 ms                                                                                                                             | 240 ms: 1.02x faster                                                                                                   |
| json_dumps                | 5.86 ms                                                                                                                            | 5.74 ms: 1.02x faster                                                                                                  |
| async_tree_io             | 752 ms                                                                                                                             | 738 ms: 1.02x faster                                                                                                   |
| python_startup            | 20.5 ms                                                                                                                            | 20.1 ms: 1.02x faster                                                                                                  |
| sqlglot_transpile         | 1.08 ms                                                                                                                            | 1.06 ms: 1.02x faster                                                                                                  |
| async_tree_cpu_io_mixed   | 467 ms                                                                                                                             | 459 ms: 1.02x faster                                                                                                   |
| dulwich_log               | 43.0 ms                                                                                                                            | 42.4 ms: 1.01x faster                                                                                                  |
| chameleon                 | 5.24 ms                                                                                                                            | 5.17 ms: 1.01x faster                                                                                                  |
| create_gc_cycles          | 753 us                                                                                                                             | 744 us: 1.01x faster                                                                                                   |
| deepcopy_reduce           | 2.12 us                                                                                                                            | 2.09 us: 1.01x faster                                                                                                  |
| async_tree_none_tg        | 290 ms                                                                                                                             | 287 ms: 1.01x faster                                                                                                   |
| sqlite_synth              | 1.59 us                                                                                                                            | 1.58 us: 1.01x faster                                                                                                  |
| logging_simple            | 6.57 us                                                                                                                            | 6.53 us: 1.01x faster                                                                                                  |
| logging_format            | 7.05 us                                                                                                                            | 7.02 us: 1.00x faster                                                                                                  |
| json_loads                | 13.4 us                                                                                                                            | 13.4 us: 1.00x slower                                                                                                  |
| logging_silent            | 62.2 ns                                                                                                                            | 62.5 ns: 1.00x slower                                                                                                  |
| coroutines                | 14.4 ms                                                                                                                            | 14.5 ms: 1.01x slower                                                                                                  |
| richards_super            | 33.6 ms                                                                                                                            | 33.9 ms: 1.01x slower                                                                                                  |
| richards                  | 30.0 ms                                                                                                                            | 30.3 ms: 1.01x slower                                                                                                  |
| pickle_pure_python        | 192 us                                                                                                                             | 194 us: 1.01x slower                                                                                                   |
| pickle_dict               | 18.3 us                                                                                                                            | 18.5 us: 1.01x slower                                                                                                  |
| regex_dna                 | 119 ms                                                                                                                             | 121 ms: 1.01x slower                                                                                                   |
| unpickle_list             | 2.57 us                                                                                                                            | 2.60 us: 1.01x slower                                                                                                  |
| scimark_lu                | 59.5 ms                                                                                                                            | 60.3 ms: 1.01x slower                                                                                                  |
| telco                     | 4.73 ms                                                                                                                            | 4.81 ms: 1.02x slower                                                                                                  |
| pickle                    | 6.89 us                                                                                                                            | 7.03 us: 1.02x slower                                                                                                  |
| generators                | 22.4 ms                                                                                                                            | 23.1 ms: 1.03x slower                                                                                                  |
| tomli_loads               | 1.49 sec                                                                                                                           | 1.54 sec: 1.03x slower                                                                                                 |
| deepcopy_memo             | 23.8 us                                                                                                                            | 24.7 us: 1.04x slower                                                                                                  |
| scimark_sor               | 79.5 ms                                                                                                                            | 82.5 ms: 1.04x slower                                                                                                  |
| mdp                       | 1.43 sec                                                                                                                           | 1.53 sec: 1.07x slower                                                                                                 |
| unpack_sequence           | 38.9 ns                                                                                                                            | 42.4 ns: 1.09x slower                                                                                                  |
| pycparser                 | 701 ms                                                                                                                             | 851 ms: 1.21x slower                                                                                                   |
| Geometric mean            | (ref)                                                                                                                              | 1.03x faster                                                                                                           |

Benchmark hidden because not significant (13): bench_thread_pool, async_tree_io_tg, async_tree_cpu_io_mixed_tg, xml_etree_generate, pathlib, coverage, deepcopy, pidigits, regex_effbot, xml_etree_parse, unpickle, asyncio_tcp_ssl, json


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
