
# Results vs. 3.12.0

- fork: python
- ref: 2dbb2e035b968811ddc0
- machine: windows-amd64
- commit hash: 2dbb2e0
- commit date: 2023-11-17
- overall geometric mean: 1.01x faster \*
- HPT reliability: 98.44%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 209 ms: 1.02x faster                                                        |
| chameleon      | 4.95 ms                                                     | 4.78 ms: 1.04x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.54 sec: 1.05x faster                                                      |
| Geometric mean | (ref)                                                       | 1.03x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 265 ms: 1.08x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 453 ms: 1.05x faster                                                        |
| async_tree_none_tg        | 277 ms                                                      | 280 ms: 1.01x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 338 ms: 1.01x slower                                                        |
| async_tree_io             | 712 ms                                                      | 728 ms: 1.02x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 762 ms: 1.03x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 358 ms: 1.04x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 51.8 ms: 1.05x faster                                                       |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 74.6 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 80.5 ms: 1.08x faster                                                       |
| regex_dna      | 119 ms                                                      | 118 ms: 1.01x faster                                                        |
| regex_effbot   | 1.58 ms                                                     | 1.58 ms: 1.00x faster                                                       |
| regex_v8       | 13.5 ms                                                     | 14.9 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 184 us: 1.06x faster                                                        |
| unpickle             | 8.44 us                                                     | 7.99 us: 1.06x faster                                                       |
| pickle               | 7.38 us                                                     | 7.02 us: 1.05x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.64 ms: 1.03x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.3 us: 1.02x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.64 us: 1.02x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.8 ms: 1.02x faster                                                       |
| unpickle_pure_python | 134 us                                                      | 133 us: 1.01x faster                                                        |
| pickle_list          | 2.88 us                                                     | 2.87 us: 1.00x faster                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 63.6 ms: 1.01x slower                                                       |
| pickle_dict          | 18.9 us                                                     | 19.2 us: 1.01x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 92.2 ms: 1.02x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.43 sec: 1.03x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.5 ms: 1.03x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.7 ms: 1.11x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.49 ms: 1.09x faster                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions            | 14.0 us                                                     | 10.6 us: 1.32x faster                                                       |
| typing_runtime_protocols  | 96.7 us                                                     | 74.8 us: 1.29x faster                                                       |
| raytrace                  | 192 ms                                                      | 167 ms: 1.15x faster                                                        |
| sqlite_synth              | 1.75 us                                                     | 1.56 us: 1.12x faster                                                       |
| generators                | 22.6 ms                                                     | 20.7 ms: 1.09x faster                                                       |
| mako                      | 7.05 ms                                                     | 6.49 ms: 1.09x faster                                                       |
| logging_silent            | 60.5 ns                                                     | 55.7 ns: 1.09x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 83.1 ms: 1.08x faster                                                       |
| regex_compile             | 87.2 ms                                                     | 80.5 ms: 1.08x faster                                                       |
| sympy_str                 | 171 ms                                                      | 159 ms: 1.08x faster                                                        |
| nqueens                   | 61.7 ms                                                     | 57.3 ms: 1.08x faster                                                       |
| async_tree_none           | 286 ms                                                      | 265 ms: 1.08x faster                                                        |
| bench_mp_pool             | 67.2 ms                                                     | 62.6 ms: 1.07x faster                                                       |
| pickle_pure_python        | 195 us                                                      | 184 us: 1.06x faster                                                        |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.37 ms: 1.06x faster                                                       |
| unpickle                  | 8.44 us                                                     | 7.99 us: 1.06x faster                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 44.0 ms: 1.05x faster                                                       |
| float                     | 54.7 ms                                                     | 51.8 ms: 1.05x faster                                                       |
| pathlib                   | 79.6 ms                                                     | 75.5 ms: 1.05x faster                                                       |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 453 ms: 1.05x faster                                                        |
| deepcopy                  | 233 us                                                      | 221 us: 1.05x faster                                                        |
| pickle                    | 7.38 us                                                     | 7.02 us: 1.05x faster                                                       |
| deepcopy_reduce           | 2.08 us                                                     | 1.98 us: 1.05x faster                                                       |
| chaos                     | 42.1 ms                                                     | 40.1 ms: 1.05x faster                                                       |
| json                      | 2.94 ms                                                     | 2.81 ms: 1.05x faster                                                       |
| dulwich_log               | 42.7 ms                                                     | 40.8 ms: 1.05x faster                                                       |
| sqlglot_parse             | 802 us                                                      | 766 us: 1.05x faster                                                        |
| docutils                  | 1.61 sec                                                    | 1.54 sec: 1.05x faster                                                      |
| sympy_integrate           | 13.0 ms                                                     | 12.4 ms: 1.05x faster                                                       |
| mdp                       | 1.42 sec                                                    | 1.37 sec: 1.04x faster                                                      |
| sqlglot_normalize         | 183 ms                                                      | 177 ms: 1.04x faster                                                        |
| chameleon                 | 4.95 ms                                                     | 4.78 ms: 1.04x faster                                                       |
| json_dumps                | 5.83 ms                                                     | 5.64 ms: 1.03x faster                                                       |
| hexiom                    | 4.00 ms                                                     | 3.88 ms: 1.03x faster                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 986 us: 1.03x faster                                                        |
| scimark_monte_carlo       | 43.0 ms                                                     | 41.8 ms: 1.03x faster                                                       |
| coroutines                | 14.1 ms                                                     | 13.8 ms: 1.03x faster                                                       |
| asyncio_tcp               | 471 ms                                                      | 459 ms: 1.03x faster                                                        |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| json_loads                | 13.6 us                                                     | 13.3 us: 1.02x faster                                                       |
| unpickle_list             | 2.69 us                                                     | 2.64 us: 1.02x faster                                                       |
| scimark_fft               | 181 ms                                                      | 178 ms: 1.02x faster                                                        |
| xml_etree_generate        | 55.8 ms                                                     | 54.8 ms: 1.02x faster                                                       |
| 2to3                      | 213 ms                                                      | 209 ms: 1.02x faster                                                        |
| sqlglot_optimize          | 34.0 ms                                                     | 33.6 ms: 1.01x faster                                                       |
| sympy_expand              | 278 ms                                                      | 274 ms: 1.01x faster                                                        |
| go                        | 89.0 ms                                                     | 88.0 ms: 1.01x faster                                                       |
| scimark_lu                | 57.5 ms                                                     | 56.9 ms: 1.01x faster                                                       |
| regex_dna                 | 119 ms                                                      | 118 ms: 1.01x faster                                                        |
| spectral_norm             | 63.9 ms                                                     | 63.4 ms: 1.01x faster                                                       |
| unpickle_pure_python      | 134 us                                                      | 133 us: 1.01x faster                                                        |
| logging_format            | 6.72 us                                                     | 6.68 us: 1.01x faster                                                       |
| pickle_list               | 2.88 us                                                     | 2.87 us: 1.00x faster                                                       |
| regex_effbot              | 1.58 ms                                                     | 1.58 ms: 1.00x faster                                                       |
| pprint_safe_repr          | 508 ms                                                      | 510 ms: 1.00x slower                                                        |
| deltablue                 | 2.12 ms                                                     | 2.13 ms: 1.00x slower                                                       |
| richards_super            | 31.2 ms                                                     | 31.3 ms: 1.01x slower                                                       |
| gc_traversal              | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                                       |
| xml_etree_iterparse       | 63.1 ms                                                     | 63.6 ms: 1.01x slower                                                       |
| async_tree_none_tg        | 277 ms                                                      | 280 ms: 1.01x slower                                                        |
| pickle_dict               | 18.9 us                                                     | 19.2 us: 1.01x slower                                                       |
| pyflate                   | 294 ms                                                      | 298 ms: 1.01x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 338 ms: 1.01x slower                                                        |
| xml_etree_parse           | 90.5 ms                                                     | 92.2 ms: 1.02x slower                                                       |
| deepcopy_memo             | 23.4 us                                                     | 23.9 us: 1.02x slower                                                       |
| create_gc_cycles          | 726 us                                                      | 741 us: 1.02x slower                                                        |
| async_tree_io             | 712 ms                                                      | 728 ms: 1.02x slower                                                        |
| scimark_sor               | 79.8 ms                                                     | 81.8 ms: 1.03x slower                                                       |
| async_tree_io_tg          | 742 ms                                                      | 762 ms: 1.03x slower                                                        |
| fannkuch                  | 244 ms                                                      | 251 ms: 1.03x slower                                                        |
| meteor_contest            | 72.1 ms                                                     | 74.2 ms: 1.03x slower                                                       |
| python_startup            | 18.8 ms                                                     | 19.5 ms: 1.03x slower                                                       |
| tomli_loads               | 1.38 sec                                                    | 1.43 sec: 1.03x slower                                                      |
| async_tree_memoization_tg | 345 ms                                                      | 358 ms: 1.04x slower                                                        |
| richards                  | 27.6 ms                                                     | 28.7 ms: 1.04x slower                                                       |
| nbody                     | 68.8 ms                                                     | 74.6 ms: 1.08x slower                                                       |
| regex_v8                  | 13.5 ms                                                     | 14.9 ms: 1.10x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 17.7 ms: 1.11x slower                                                       |
| pycparser                 | 673 ms                                                      | 751 ms: 1.12x slower                                                        |
| telco                     | 4.08 ms                                                     | 4.57 ms: 1.12x slower                                                       |
| coverage                  | 39.8 ms                                                     | 46.6 ms: 1.17x slower                                                       |
| mypy2                     | 209 ms                                                      | 287 ms: 1.37x slower                                                        |
| unpack_sequence           | 36.9 ns                                                     | 50.7 ns: 1.37x slower                                                       |
| Geometric mean            | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (9): asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, tornado_http, async_generators, dask, pprint_pformat, logging_simple, xml_etree_process, bench_thread_pool
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.44% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
