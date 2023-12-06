
# Results vs. 3.12.0

- fork: python
- ref: c4c63211e83aa50927f3
- machine: windows-amd64
- commit hash: c4c6321
- commit date: 2023-11-20
- overall geometric mean: 1.01x faster \*
- HPT reliability: 95.84%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| chameleon      | 4.95 ms                                                     | 4.88 ms: 1.01x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 95.6 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 269 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 452 ms: 1.05x faster                                                        |
| async_tree_none_tg        | 277 ms                                                      | 284 ms: 1.03x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 342 ms: 1.03x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 764 ms: 1.03x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 363 ms: 1.05x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed_tg, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 52.1 ms: 1.05x faster                                                       |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 75.5 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 80.4 ms: 1.08x faster                                                       |
| regex_dna      | 119 ms                                                      | 117 ms: 1.02x faster                                                        |
| regex_v8       | 13.5 ms                                                     | 14.6 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 181 us: 1.07x faster                                                        |
| pickle               | 7.38 us                                                     | 7.03 us: 1.05x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.12 us: 1.04x faster                                                       |
| unpickle_pure_python | 134 us                                                      | 130 us: 1.03x faster                                                        |
| json_dumps           | 5.83 ms                                                     | 5.65 ms: 1.03x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.4 us: 1.03x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.62 us: 1.03x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.3 ms: 1.03x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.86 us: 1.01x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.8 ms: 1.00x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.45 sec: 1.06x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_parse, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.1 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.53 ms: 1.08x faster                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions            | 14.0 us                                                     | 10.3 us: 1.36x faster                                                       |
| typing_runtime_protocols  | 96.7 us                                                     | 77.0 us: 1.26x faster                                                       |
| raytrace                  | 192 ms                                                      | 165 ms: 1.16x faster                                                        |
| sqlite_synth              | 1.75 us                                                     | 1.56 us: 1.12x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 81.8 ms: 1.10x faster                                                       |
| sympy_str                 | 171 ms                                                      | 157 ms: 1.09x faster                                                        |
| regex_compile             | 87.2 ms                                                     | 80.4 ms: 1.08x faster                                                       |
| mako                      | 7.05 ms                                                     | 6.53 ms: 1.08x faster                                                       |
| logging_silent            | 60.5 ns                                                     | 56.1 ns: 1.08x faster                                                       |
| pickle_pure_python        | 195 us                                                      | 181 us: 1.07x faster                                                        |
| coroutines                | 14.1 ms                                                     | 13.2 ms: 1.07x faster                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 43.7 ms: 1.06x faster                                                       |
| async_tree_none           | 286 ms                                                      | 269 ms: 1.06x faster                                                        |
| mdp                       | 1.42 sec                                                    | 1.34 sec: 1.06x faster                                                      |
| generators                | 22.6 ms                                                     | 21.4 ms: 1.06x faster                                                       |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 452 ms: 1.05x faster                                                        |
| bench_mp_pool             | 67.2 ms                                                     | 63.9 ms: 1.05x faster                                                       |
| deepcopy_reduce           | 2.08 us                                                     | 1.98 us: 1.05x faster                                                       |
| float                     | 54.7 ms                                                     | 52.1 ms: 1.05x faster                                                       |
| pickle                    | 7.38 us                                                     | 7.03 us: 1.05x faster                                                       |
| chaos                     | 42.1 ms                                                     | 40.2 ms: 1.05x faster                                                       |
| sympy_integrate           | 13.0 ms                                                     | 12.4 ms: 1.05x faster                                                       |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.40 ms: 1.05x faster                                                       |
| sqlglot_parse             | 802 us                                                      | 768 us: 1.04x faster                                                        |
| nqueens                   | 61.7 ms                                                     | 59.4 ms: 1.04x faster                                                       |
| unpickle                  | 8.44 us                                                     | 8.12 us: 1.04x faster                                                       |
| sqlglot_normalize         | 183 ms                                                      | 177 ms: 1.04x faster                                                        |
| sympy_expand              | 278 ms                                                      | 268 ms: 1.04x faster                                                        |
| docutils                  | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                                      |
| hexiom                    | 4.00 ms                                                     | 3.87 ms: 1.03x faster                                                       |
| unpickle_pure_python      | 134 us                                                      | 130 us: 1.03x faster                                                        |
| json_dumps                | 5.83 ms                                                     | 5.65 ms: 1.03x faster                                                       |
| deepcopy                  | 233 us                                                      | 226 us: 1.03x faster                                                        |
| dulwich_log               | 42.7 ms                                                     | 41.4 ms: 1.03x faster                                                       |
| pickle_dict               | 18.9 us                                                     | 18.4 us: 1.03x faster                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 988 us: 1.03x faster                                                        |
| unpickle_list             | 2.69 us                                                     | 2.62 us: 1.03x faster                                                       |
| xml_etree_generate        | 55.8 ms                                                     | 54.3 ms: 1.03x faster                                                       |
| spectral_norm             | 63.9 ms                                                     | 62.3 ms: 1.03x faster                                                       |
| json                      | 2.94 ms                                                     | 2.87 ms: 1.02x faster                                                       |
| regex_dna                 | 119 ms                                                      | 117 ms: 1.02x faster                                                        |
| pprint_safe_repr          | 508 ms                                                      | 496 ms: 1.02x faster                                                        |
| sqlglot_optimize          | 34.0 ms                                                     | 33.3 ms: 1.02x faster                                                       |
| logging_format            | 6.72 us                                                     | 6.59 us: 1.02x faster                                                       |
| scimark_fft               | 181 ms                                                      | 178 ms: 1.02x faster                                                        |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| pprint_pformat            | 1.04 sec                                                    | 1.02 sec: 1.01x faster                                                      |
| chameleon                 | 4.95 ms                                                     | 4.88 ms: 1.01x faster                                                       |
| json_loads                | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| logging_simple            | 6.21 us                                                     | 6.13 us: 1.01x faster                                                       |
| pickle_list               | 2.88 us                                                     | 2.86 us: 1.01x faster                                                       |
| go                        | 89.0 ms                                                     | 88.4 ms: 1.01x faster                                                       |
| pyflate                   | 294 ms                                                      | 292 ms: 1.01x faster                                                        |
| async_generators          | 230 ms                                                      | 229 ms: 1.00x faster                                                        |
| xml_etree_process         | 37.6 ms                                                     | 37.8 ms: 1.00x slower                                                       |
| richards_super            | 31.2 ms                                                     | 31.3 ms: 1.00x slower                                                       |
| deltablue                 | 2.12 ms                                                     | 2.13 ms: 1.00x slower                                                       |
| gc_traversal              | 1.49 ms                                                     | 1.51 ms: 1.01x slower                                                       |
| scimark_sor               | 79.8 ms                                                     | 80.9 ms: 1.01x slower                                                       |
| meteor_contest            | 72.1 ms                                                     | 73.3 ms: 1.02x slower                                                       |
| create_gc_cycles          | 726 us                                                      | 739 us: 1.02x slower                                                        |
| bench_thread_pool         | 830 us                                                      | 847 us: 1.02x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 284 ms: 1.03x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 342 ms: 1.03x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 764 ms: 1.03x slower                                                        |
| richards                  | 27.6 ms                                                     | 28.8 ms: 1.04x slower                                                       |
| scimark_monte_carlo       | 43.0 ms                                                     | 44.8 ms: 1.04x slower                                                       |
| deepcopy_memo             | 23.4 us                                                     | 24.5 us: 1.04x slower                                                       |
| dask                      | 255 ms                                                      | 266 ms: 1.05x slower                                                        |
| asyncio_tcp_ssl           | 1.89 sec                                                    | 1.98 sec: 1.05x slower                                                      |
| fannkuch                  | 244 ms                                                      | 256 ms: 1.05x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 363 ms: 1.05x slower                                                        |
| tomli_loads               | 1.38 sec                                                    | 1.45 sec: 1.06x slower                                                      |
| python_startup            | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| regex_v8                  | 13.5 ms                                                     | 14.6 ms: 1.08x slower                                                       |
| tornado_http              | 87.2 ms                                                     | 95.6 ms: 1.10x slower                                                       |
| nbody                     | 68.8 ms                                                     | 75.5 ms: 1.10x slower                                                       |
| pycparser                 | 673 ms                                                      | 751 ms: 1.11x slower                                                        |
| unpack_sequence           | 36.9 ns                                                     | 41.9 ns: 1.14x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 18.1 ms: 1.14x slower                                                       |
| telco                     | 4.08 ms                                                     | 4.66 ms: 1.14x slower                                                       |
| coverage                  | 39.8 ms                                                     | 46.0 ms: 1.16x slower                                                       |
| asyncio_tcp               | 471 ms                                                      | 545 ms: 1.16x slower                                                        |
| mypy2                     | 209 ms                                                      | 286 ms: 1.37x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (8): async_tree_cpu_io_mixed_tg, xml_etree_parse, 2to3, regex_effbot, scimark_lu, pathlib, async_tree_io, xml_etree_iterparse
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 95.84% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
