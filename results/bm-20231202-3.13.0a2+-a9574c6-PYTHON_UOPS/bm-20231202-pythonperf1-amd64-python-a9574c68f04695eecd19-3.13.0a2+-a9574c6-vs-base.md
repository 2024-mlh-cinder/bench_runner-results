
# Results vs. base

- fork: python
- ref: a9574c68f04695eecd19
- machine: windows-amd64
- commit hash: a9574c6
- commit date: 2023-12-02
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| 2to3           | 217 ms                                                                                                                 | 227 ms: 1.04x slower                                                                                                               |
| chameleon      | 5.17 ms                                                                                                                | 5.24 ms: 1.01x slower                                                                                                              |
| docutils       | 1.59 sec                                                                                                               | 1.65 sec: 1.03x slower                                                                                                             |
| tornado_http   | 88.0 ms                                                                                                                | 90.6 ms: 1.03x slower                                                                                                              |
| Geometric mean | (ref)                                                                                                                  | 1.03x slower                                                                                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| async_tree_none_tg        | 287 ms                                                                                                                 | 290 ms: 1.01x slower                                                                                                               |
| async_tree_cpu_io_mixed   | 459 ms                                                                                                                 | 467 ms: 1.02x slower                                                                                                               |
| async_tree_io             | 738 ms                                                                                                                 | 752 ms: 1.02x slower                                                                                                               |
| async_tree_none           | 270 ms                                                                                                                 | 276 ms: 1.02x slower                                                                                                               |
| async_tree_memoization_tg | 369 ms                                                                                                                 | 379 ms: 1.03x slower                                                                                                               |
| async_tree_memoization    | 346 ms                                                                                                                 | 356 ms: 1.03x slower                                                                                                               |
| Geometric mean            | (ref)                                                                                                                  | 1.02x slower                                                                                                                       |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed_tg, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| float          | 54.5 ms                                                                                                                | 57.6 ms: 1.06x slower                                                                                                              |
| nbody          | 74.2 ms                                                                                                                | 81.7 ms: 1.10x slower                                                                                                              |
| Geometric mean | (ref)                                                                                                                  | 1.05x slower                                                                                                                       |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                                                                                 | 119 ms: 1.01x faster                                                                                                               |
| regex_compile  | 86.5 ms                                                                                                                | 92.1 ms: 1.07x slower                                                                                                              |
| regex_v8       | 15.4 ms                                                                                                                | 19.5 ms: 1.27x slower                                                                                                              |
| Geometric mean | (ref)                                                                                                                  | 1.07x slower                                                                                                                       |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| tomli_loads          | 1.54 sec                                                                                                               | 1.49 sec: 1.03x faster                                                                                                             |
| pickle               | 7.03 us                                                                                                                | 6.89 us: 1.02x faster                                                                                                              |
| unpickle_list        | 2.60 us                                                                                                                | 2.57 us: 1.01x faster                                                                                                              |
| pickle_dict          | 18.5 us                                                                                                                | 18.3 us: 1.01x faster                                                                                                              |
| pickle_pure_python   | 194 us                                                                                                                 | 192 us: 1.01x faster                                                                                                               |
| json_loads           | 13.4 us                                                                                                                | 13.4 us: 1.00x faster                                                                                                              |
| json_dumps           | 5.74 ms                                                                                                                | 5.86 ms: 1.02x slower                                                                                                              |
| xml_etree_process    | 39.0 ms                                                                                                                | 39.8 ms: 1.02x slower                                                                                                              |
| xml_etree_iterparse  | 64.8 ms                                                                                                                | 67.6 ms: 1.04x slower                                                                                                              |
| pickle_list          | 2.88 us                                                                                                                | 3.10 us: 1.07x slower                                                                                                              |
| unpickle_pure_python | 135 us                                                                                                                 | 146 us: 1.08x slower                                                                                                               |
| Geometric mean       | (ref)                                                                                                                  | 1.01x slower                                                                                                                       |

Benchmark hidden because not significant (3): unpickle, xml_etree_parse, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|------------------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| python_startup         | 20.1 ms                                                                                                                | 20.5 ms: 1.02x slower                                                                                                              |
| python_startup_no_site | 18.0 ms                                                                                                                | 18.5 ms: 1.03x slower                                                                                                              |
| Geometric mean         | (ref)                                                                                                                  | 1.02x slower                                                                                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|-----------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                                                                                | 7.37 ms: 1.06x slower                                                                                                              |

All benchmarks:
===============

| Benchmark                 | results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json | results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json |
|---------------------------|:----------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| pycparser                 | 851 ms                                                                                                                 | 701 ms: 1.21x faster                                                                                                               |
| unpack_sequence           | 42.4 ns                                                                                                                | 38.9 ns: 1.09x faster                                                                                                              |
| mdp                       | 1.53 sec                                                                                                               | 1.43 sec: 1.07x faster                                                                                                             |
| scimark_sor               | 82.5 ms                                                                                                                | 79.5 ms: 1.04x faster                                                                                                              |
| deepcopy_memo             | 24.7 us                                                                                                                | 23.8 us: 1.04x faster                                                                                                              |
| tomli_loads               | 1.54 sec                                                                                                               | 1.49 sec: 1.03x faster                                                                                                             |
| generators                | 23.1 ms                                                                                                                | 22.4 ms: 1.03x faster                                                                                                              |
| pickle                    | 7.03 us                                                                                                                | 6.89 us: 1.02x faster                                                                                                              |
| telco                     | 4.81 ms                                                                                                                | 4.73 ms: 1.02x faster                                                                                                              |
| scimark_lu                | 60.3 ms                                                                                                                | 59.5 ms: 1.01x faster                                                                                                              |
| unpickle_list             | 2.60 us                                                                                                                | 2.57 us: 1.01x faster                                                                                                              |
| regex_dna                 | 121 ms                                                                                                                 | 119 ms: 1.01x faster                                                                                                               |
| pickle_dict               | 18.5 us                                                                                                                | 18.3 us: 1.01x faster                                                                                                              |
| pickle_pure_python        | 194 us                                                                                                                 | 192 us: 1.01x faster                                                                                                               |
| richards                  | 30.3 ms                                                                                                                | 30.0 ms: 1.01x faster                                                                                                              |
| richards_super            | 33.9 ms                                                                                                                | 33.6 ms: 1.01x faster                                                                                                              |
| coroutines                | 14.5 ms                                                                                                                | 14.4 ms: 1.01x faster                                                                                                              |
| logging_silent            | 62.5 ns                                                                                                                | 62.2 ns: 1.00x faster                                                                                                              |
| json_loads                | 13.4 us                                                                                                                | 13.4 us: 1.00x faster                                                                                                              |
| logging_format            | 7.02 us                                                                                                                | 7.05 us: 1.00x slower                                                                                                              |
| logging_simple            | 6.53 us                                                                                                                | 6.57 us: 1.01x slower                                                                                                              |
| sqlite_synth              | 1.58 us                                                                                                                | 1.59 us: 1.01x slower                                                                                                              |
| async_tree_none_tg        | 287 ms                                                                                                                 | 290 ms: 1.01x slower                                                                                                               |
| deepcopy_reduce           | 2.09 us                                                                                                                | 2.12 us: 1.01x slower                                                                                                              |
| create_gc_cycles          | 744 us                                                                                                                 | 753 us: 1.01x slower                                                                                                               |
| chameleon                 | 5.17 ms                                                                                                                | 5.24 ms: 1.01x slower                                                                                                              |
| dulwich_log               | 42.4 ms                                                                                                                | 43.0 ms: 1.01x slower                                                                                                              |
| async_tree_cpu_io_mixed   | 459 ms                                                                                                                 | 467 ms: 1.02x slower                                                                                                               |
| sqlglot_transpile         | 1.06 ms                                                                                                                | 1.08 ms: 1.02x slower                                                                                                              |
| python_startup            | 20.1 ms                                                                                                                | 20.5 ms: 1.02x slower                                                                                                              |
| async_tree_io             | 738 ms                                                                                                                 | 752 ms: 1.02x slower                                                                                                               |
| json_dumps                | 5.74 ms                                                                                                                | 5.86 ms: 1.02x slower                                                                                                              |
| async_generators          | 240 ms                                                                                                                 | 245 ms: 1.02x slower                                                                                                               |
| xml_etree_process         | 39.0 ms                                                                                                                | 39.8 ms: 1.02x slower                                                                                                              |
| async_tree_none           | 270 ms                                                                                                                 | 276 ms: 1.02x slower                                                                                                               |
| gc_traversal              | 1.49 ms                                                                                                                | 1.53 ms: 1.02x slower                                                                                                              |
| sqlglot_parse             | 829 us                                                                                                                 | 849 us: 1.02x slower                                                                                                               |
| async_tree_memoization_tg | 369 ms                                                                                                                 | 379 ms: 1.03x slower                                                                                                               |
| sqlglot_normalize         | 190 ms                                                                                                                 | 195 ms: 1.03x slower                                                                                                               |
| dask                      | 261 ms                                                                                                                 | 268 ms: 1.03x slower                                                                                                               |
| python_startup_no_site    | 18.0 ms                                                                                                                | 18.5 ms: 1.03x slower                                                                                                              |
| async_tree_memoization    | 346 ms                                                                                                                 | 356 ms: 1.03x slower                                                                                                               |
| sqlglot_optimize          | 36.0 ms                                                                                                                | 37.1 ms: 1.03x slower                                                                                                              |
| tornado_http              | 88.0 ms                                                                                                                | 90.6 ms: 1.03x slower                                                                                                              |
| mypy2                     | 426 ms                                                                                                                 | 439 ms: 1.03x slower                                                                                                               |
| nqueens                   | 64.2 ms                                                                                                                | 66.3 ms: 1.03x slower                                                                                                              |
| sympy_expand              | 281 ms                                                                                                                 | 290 ms: 1.03x slower                                                                                                               |
| docutils                  | 1.59 sec                                                                                                               | 1.65 sec: 1.03x slower                                                                                                             |
| meteor_contest            | 75.1 ms                                                                                                                | 77.6 ms: 1.03x slower                                                                                                              |
| go                        | 92.8 ms                                                                                                                | 96.3 ms: 1.04x slower                                                                                                              |
| 2to3                      | 217 ms                                                                                                                 | 227 ms: 1.04x slower                                                                                                               |
| xml_etree_iterparse       | 64.8 ms                                                                                                                | 67.6 ms: 1.04x slower                                                                                                              |
| pprint_safe_repr          | 523 ms                                                                                                                 | 549 ms: 1.05x slower                                                                                                               |
| asyncio_tcp               | 460 ms                                                                                                                 | 484 ms: 1.05x slower                                                                                                               |
| typing_runtime_protocols  | 79.2 us                                                                                                                | 83.4 us: 1.05x slower                                                                                                              |
| sympy_sum                 | 85.2 ms                                                                                                                | 89.8 ms: 1.05x slower                                                                                                              |
| pprint_pformat            | 1.06 sec                                                                                                               | 1.12 sec: 1.06x slower                                                                                                             |
| float                     | 54.5 ms                                                                                                                | 57.6 ms: 1.06x slower                                                                                                              |
| sympy_str                 | 164 ms                                                                                                                 | 173 ms: 1.06x slower                                                                                                               |
| bench_mp_pool             | 64.6 ms                                                                                                                | 68.5 ms: 1.06x slower                                                                                                              |
| mako                      | 6.93 ms                                                                                                                | 7.37 ms: 1.06x slower                                                                                                              |
| sympy_integrate           | 12.8 ms                                                                                                                | 13.6 ms: 1.06x slower                                                                                                              |
| regex_compile             | 86.5 ms                                                                                                                | 92.1 ms: 1.07x slower                                                                                                              |
| pyflate                   | 304 ms                                                                                                                 | 325 ms: 1.07x slower                                                                                                               |
| raytrace                  | 172 ms                                                                                                                 | 184 ms: 1.07x slower                                                                                                               |
| pickle_list               | 2.88 us                                                                                                                | 3.10 us: 1.07x slower                                                                                                              |
| crypto_pyaes              | 45.3 ms                                                                                                                | 49.0 ms: 1.08x slower                                                                                                              |
| unpickle_pure_python      | 135 us                                                                                                                 | 146 us: 1.08x slower                                                                                                               |
| fannkuch                  | 251 ms                                                                                                                 | 273 ms: 1.09x slower                                                                                                               |
| chaos                     | 41.3 ms                                                                                                                | 45.0 ms: 1.09x slower                                                                                                              |
| nbody                     | 74.2 ms                                                                                                                | 81.7 ms: 1.10x slower                                                                                                              |
| scimark_fft               | 186 ms                                                                                                                 | 207 ms: 1.11x slower                                                                                                               |
| scimark_monte_carlo       | 42.3 ms                                                                                                                | 49.8 ms: 1.18x slower                                                                                                              |
| comprehensions            | 11.1 us                                                                                                                | 13.2 us: 1.19x slower                                                                                                              |
| hexiom                    | 4.24 ms                                                                                                                | 5.08 ms: 1.20x slower                                                                                                              |
| scimark_sparse_mat_mult   | 2.50 ms                                                                                                                | 3.08 ms: 1.23x slower                                                                                                              |
| deltablue                 | 2.21 ms                                                                                                                | 2.76 ms: 1.24x slower                                                                                                              |
| regex_v8                  | 15.4 ms                                                                                                                | 19.5 ms: 1.27x slower                                                                                                              |
| spectral_norm             | 63.2 ms                                                                                                                | 81.5 ms: 1.29x slower                                                                                                              |
| Geometric mean            | (ref)                                                                                                                  | 1.03x slower                                                                                                                       |

Benchmark hidden because not significant (13): json, asyncio_tcp_ssl, unpickle, xml_etree_parse, regex_effbot, pidigits, deepcopy, coverage, pathlib, xml_etree_generate, async_tree_cpu_io_mixed_tg, async_tree_io_tg, bench_thread_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
