
# Results vs. 3.12.0

- fork: python
- ref: 2dbb2e035b968811ddc0
- machine: windows-amd64
- commit hash: 2dbb2e0
- commit date: 2023-11-17
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 218 ms: 1.03x slower                                                        |
| docutils       | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 89.9 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 276 ms: 1.04x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 461 ms: 1.04x faster                                                        |
| async_tree_io             | 712 ms                                                      | 739 ms: 1.04x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 288 ms: 1.04x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 775 ms: 1.04x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 348 ms: 1.05x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 369 ms: 1.07x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 148 ms: 1.01x faster                                                        |
| float          | 54.7 ms                                                     | 59.8 ms: 1.09x slower                                                       |
| nbody          | 68.8 ms                                                     | 78.6 ms: 1.14x slower                                                       |
| Geometric mean | (ref)                                                       | 1.07x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 119 ms                                                      | 120 ms: 1.01x slower                                                        |
| regex_compile  | 87.2 ms                                                     | 91.4 ms: 1.05x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 15.4 ms: 1.14x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 180 us: 1.08x faster                                                        |
| pickle               | 7.38 us                                                     | 7.13 us: 1.04x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.17 us: 1.03x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.6 ms: 1.02x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.64 us: 1.02x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.75 ms: 1.02x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.7 us: 1.01x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.3 ms: 1.01x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.6 us: 1.00x faster                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 92.5 ms: 1.02x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 65.7 ms: 1.04x slower                                                       |
| pickle_list          | 2.88 us                                                     | 3.04 us: 1.05x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 142 us: 1.06x slower                                                        |
| tomli_loads          | 1.38 sec                                                    | 1.59 sec: 1.15x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.7 ms: 1.11x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 8.30 ms: 1.18x slower                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols  | 96.7 us                                                     | 80.2 us: 1.21x faster                                                       |
| sqlite_synth              | 1.75 us                                                     | 1.58 us: 1.10x faster                                                       |
| generators                | 22.6 ms                                                     | 20.6 ms: 1.10x faster                                                       |
| raytrace                  | 192 ms                                                      | 177 ms: 1.09x faster                                                        |
| pickle_pure_python        | 195 us                                                      | 180 us: 1.08x faster                                                        |
| coroutines                | 14.1 ms                                                     | 13.1 ms: 1.08x faster                                                       |
| spectral_norm             | 63.9 ms                                                     | 59.7 ms: 1.07x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 84.6 ms: 1.07x faster                                                       |
| bench_mp_pool             | 67.2 ms                                                     | 63.3 ms: 1.06x faster                                                       |
| asyncio_tcp_ssl           | 1.89 sec                                                    | 1.78 sec: 1.06x faster                                                      |
| pathlib                   | 79.6 ms                                                     | 75.1 ms: 1.06x faster                                                       |
| deepcopy_reduce           | 2.08 us                                                     | 1.99 us: 1.05x faster                                                       |
| deepcopy                  | 233 us                                                      | 222 us: 1.05x faster                                                        |
| sqlglot_normalize         | 183 ms                                                      | 177 ms: 1.04x faster                                                        |
| sympy_str                 | 171 ms                                                      | 165 ms: 1.04x faster                                                        |
| async_tree_none           | 286 ms                                                      | 276 ms: 1.04x faster                                                        |
| pickle                    | 7.38 us                                                     | 7.13 us: 1.04x faster                                                       |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 461 ms: 1.04x faster                                                        |
| unpickle                  | 8.44 us                                                     | 8.17 us: 1.03x faster                                                       |
| logging_silent            | 60.5 ns                                                     | 58.7 ns: 1.03x faster                                                       |
| scimark_sor               | 79.8 ms                                                     | 77.6 ms: 1.03x faster                                                       |
| xml_etree_generate        | 55.8 ms                                                     | 54.6 ms: 1.02x faster                                                       |
| unpickle_list             | 2.69 us                                                     | 2.64 us: 1.02x faster                                                       |
| sqlglot_parse             | 802 us                                                      | 787 us: 1.02x faster                                                        |
| json_dumps                | 5.83 ms                                                     | 5.75 ms: 1.02x faster                                                       |
| pidigits                  | 150 ms                                                      | 148 ms: 1.01x faster                                                        |
| sqlglot_optimize          | 34.0 ms                                                     | 33.6 ms: 1.01x faster                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 1.00 ms: 1.01x faster                                                       |
| pickle_dict               | 18.9 us                                                     | 18.7 us: 1.01x faster                                                       |
| dulwich_log               | 42.7 ms                                                     | 42.3 ms: 1.01x faster                                                       |
| docutils                  | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                                      |
| xml_etree_process         | 37.6 ms                                                     | 37.3 ms: 1.01x faster                                                       |
| json_loads                | 13.6 us                                                     | 13.6 us: 1.00x faster                                                       |
| richards_super            | 31.2 ms                                                     | 31.4 ms: 1.01x slower                                                       |
| sympy_expand              | 278 ms                                                      | 280 ms: 1.01x slower                                                        |
| regex_dna                 | 119 ms                                                      | 120 ms: 1.01x slower                                                        |
| gc_traversal              | 1.49 ms                                                     | 1.51 ms: 1.01x slower                                                       |
| richards                  | 27.6 ms                                                     | 27.9 ms: 1.01x slower                                                       |
| deepcopy_memo             | 23.4 us                                                     | 23.7 us: 1.01x slower                                                       |
| async_generators          | 230 ms                                                      | 233 ms: 1.01x slower                                                        |
| scimark_lu                | 57.5 ms                                                     | 58.6 ms: 1.02x slower                                                       |
| xml_etree_parse           | 90.5 ms                                                     | 92.5 ms: 1.02x slower                                                       |
| create_gc_cycles          | 726 us                                                      | 744 us: 1.02x slower                                                        |
| logging_format            | 6.72 us                                                     | 6.89 us: 1.03x slower                                                       |
| 2to3                      | 213 ms                                                      | 218 ms: 1.03x slower                                                        |
| bench_thread_pool         | 830 us                                                      | 854 us: 1.03x slower                                                        |
| unpack_sequence           | 36.9 ns                                                     | 38.0 ns: 1.03x slower                                                       |
| sympy_integrate           | 13.0 ms                                                     | 13.4 ms: 1.03x slower                                                       |
| tornado_http              | 87.2 ms                                                     | 89.9 ms: 1.03x slower                                                       |
| logging_simple            | 6.21 us                                                     | 6.43 us: 1.04x slower                                                       |
| async_tree_io             | 712 ms                                                      | 739 ms: 1.04x slower                                                        |
| xml_etree_iterparse       | 63.1 ms                                                     | 65.7 ms: 1.04x slower                                                       |
| async_tree_none_tg        | 277 ms                                                      | 288 ms: 1.04x slower                                                        |
| python_startup            | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| async_tree_io_tg          | 742 ms                                                      | 775 ms: 1.04x slower                                                        |
| pycparser                 | 673 ms                                                      | 703 ms: 1.04x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 348 ms: 1.05x slower                                                        |
| regex_compile             | 87.2 ms                                                     | 91.4 ms: 1.05x slower                                                       |
| pickle_list               | 2.88 us                                                     | 3.04 us: 1.05x slower                                                       |
| unpickle_pure_python      | 134 us                                                      | 142 us: 1.06x slower                                                        |
| pprint_safe_repr          | 508 ms                                                      | 538 ms: 1.06x slower                                                        |
| pprint_pformat            | 1.04 sec                                                    | 1.11 sec: 1.07x slower                                                      |
| mdp                       | 1.42 sec                                                    | 1.52 sec: 1.07x slower                                                      |
| chaos                     | 42.1 ms                                                     | 45.0 ms: 1.07x slower                                                       |
| async_tree_memoization_tg | 345 ms                                                      | 369 ms: 1.07x slower                                                        |
| float                     | 54.7 ms                                                     | 59.8 ms: 1.09x slower                                                       |
| meteor_contest            | 72.1 ms                                                     | 79.0 ms: 1.10x slower                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 51.2 ms: 1.10x slower                                                       |
| comprehensions            | 14.0 us                                                     | 15.5 us: 1.11x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 17.7 ms: 1.11x slower                                                       |
| go                        | 89.0 ms                                                     | 99.2 ms: 1.12x slower                                                       |
| pyflate                   | 294 ms                                                      | 333 ms: 1.13x slower                                                        |
| coverage                  | 39.8 ms                                                     | 45.3 ms: 1.14x slower                                                       |
| regex_v8                  | 13.5 ms                                                     | 15.4 ms: 1.14x slower                                                       |
| scimark_monte_carlo       | 43.0 ms                                                     | 49.0 ms: 1.14x slower                                                       |
| nqueens                   | 61.7 ms                                                     | 70.4 ms: 1.14x slower                                                       |
| nbody                     | 68.8 ms                                                     | 78.6 ms: 1.14x slower                                                       |
| tomli_loads               | 1.38 sec                                                    | 1.59 sec: 1.15x slower                                                      |
| mako                      | 7.05 ms                                                     | 8.30 ms: 1.18x slower                                                       |
| scimark_fft               | 181 ms                                                      | 213 ms: 1.18x slower                                                        |
| telco                     | 4.08 ms                                                     | 4.87 ms: 1.19x slower                                                       |
| fannkuch                  | 244 ms                                                      | 294 ms: 1.21x slower                                                        |
| deltablue                 | 2.12 ms                                                     | 2.96 ms: 1.39x slower                                                       |
| mypy2                     | 209 ms                                                      | 293 ms: 1.40x slower                                                        |
| hexiom                    | 4.00 ms                                                     | 5.96 ms: 1.49x slower                                                       |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 3.88 ms: 1.55x slower                                                       |
| Geometric mean            | (ref)                                                       | 1.04x slower                                                                |

Benchmark hidden because not significant (6): regex_effbot, chameleon, dask, async_tree_cpu_io_mixed_tg, asyncio_tcp, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.96% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
