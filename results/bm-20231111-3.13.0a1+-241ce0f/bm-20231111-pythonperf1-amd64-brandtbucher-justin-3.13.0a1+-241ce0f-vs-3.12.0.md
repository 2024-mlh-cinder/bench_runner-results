
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.00x faster \*
- HPT reliability: 51.11%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 217 ms: 1.02x slower                                                |
| chameleon      | 4.95 ms                                                     | 4.89 ms: 1.01x faster                                               |
| docutils       | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                              |
| tornado_http   | 87.2 ms                                                     | 88.0 ms: 1.01x slower                                               |
| Geometric mean | (ref)                                                       | 1.00x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|---------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 270 ms: 1.06x faster                                                |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 453 ms: 1.05x faster                                                |
| async_tree_io             | 712 ms                                                      | 730 ms: 1.03x slower                                                |
| async_tree_memoization    | 333 ms                                                      | 343 ms: 1.03x slower                                                |
| async_tree_none_tg        | 277 ms                                                      | 285 ms: 1.03x slower                                                |
| async_tree_io_tg          | 742 ms                                                      | 770 ms: 1.04x slower                                                |
| async_tree_memoization_tg | 345 ms                                                      | 366 ms: 1.06x slower                                                |
| Geometric mean            | (ref)                                                       | 1.01x slower                                                        |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 52.8 ms: 1.04x faster                                               |
| pidigits       | 150 ms                                                      | 150 ms: 1.00x slower                                                |
| nbody          | 68.8 ms                                                     | 73.1 ms: 1.06x slower                                               |
| Geometric mean | (ref)                                                       | 1.01x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 82.2 ms: 1.06x faster                                               |
| regex_effbot   | 1.58 ms                                                     | 1.56 ms: 1.02x faster                                               |
| regex_v8       | 13.5 ms                                                     | 14.7 ms: 1.09x slower                                               |
| Geometric mean | (ref)                                                       | 1.00x slower                                                        |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 183 us: 1.06x faster                                                |
| unpickle             | 8.44 us                                                     | 8.15 us: 1.03x faster                                               |
| pickle_dict          | 18.9 us                                                     | 18.3 us: 1.03x faster                                               |
| tomli_loads          | 1.38 sec                                                    | 1.34 sec: 1.03x faster                                              |
| pickle               | 7.38 us                                                     | 7.22 us: 1.02x faster                                               |
| xml_etree_generate   | 55.8 ms                                                     | 54.6 ms: 1.02x faster                                               |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.02x faster                                               |
| json_dumps           | 5.83 ms                                                     | 5.72 ms: 1.02x faster                                               |
| xml_etree_process    | 37.6 ms                                                     | 37.0 ms: 1.02x faster                                               |
| unpickle_pure_python | 134 us                                                      | 136 us: 1.01x slower                                                |
| xml_etree_parse      | 90.5 ms                                                     | 92.8 ms: 1.03x slower                                               |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.8 ms: 1.03x slower                                               |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                        |

Benchmark hidden because not significant (2): unpickle_list, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| python_startup_no_site | 15.9 ms                                                     | 18.9 ms: 1.19x slower                                               |
| Geometric mean         | (ref)                                                       | 1.14x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.59 ms: 1.07x faster                                               |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|---------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols  | 96.7 us                                                     | 76.5 us: 1.26x faster                                               |
| comprehensions            | 14.0 us                                                     | 11.8 us: 1.19x faster                                               |
| raytrace                  | 192 ms                                                      | 168 ms: 1.14x faster                                                |
| sqlite_synth              | 1.75 us                                                     | 1.56 us: 1.12x faster                                               |
| logging_silent            | 60.5 ns                                                     | 55.2 ns: 1.10x faster                                               |
| generators                | 22.6 ms                                                     | 20.7 ms: 1.09x faster                                               |
| mako                      | 7.05 ms                                                     | 6.59 ms: 1.07x faster                                               |
| sympy_sum                 | 90.1 ms                                                     | 84.4 ms: 1.07x faster                                               |
| pickle_pure_python        | 195 us                                                      | 183 us: 1.06x faster                                                |
| richards_super            | 31.2 ms                                                     | 29.3 ms: 1.06x faster                                               |
| sympy_str                 | 171 ms                                                      | 162 ms: 1.06x faster                                                |
| regex_compile             | 87.2 ms                                                     | 82.2 ms: 1.06x faster                                               |
| async_tree_none           | 286 ms                                                      | 270 ms: 1.06x faster                                                |
| deepcopy_reduce           | 2.08 us                                                     | 1.98 us: 1.05x faster                                               |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 453 ms: 1.05x faster                                                |
| richards                  | 27.6 ms                                                     | 26.2 ms: 1.05x faster                                               |
| deepcopy                  | 233 us                                                      | 222 us: 1.05x faster                                                |
| coroutines                | 14.1 ms                                                     | 13.5 ms: 1.04x faster                                               |
| sqlglot_parse             | 802 us                                                      | 771 us: 1.04x faster                                                |
| bench_mp_pool             | 67.2 ms                                                     | 64.7 ms: 1.04x faster                                               |
| float                     | 54.7 ms                                                     | 52.8 ms: 1.04x faster                                               |
| dulwich_log               | 42.7 ms                                                     | 41.3 ms: 1.03x faster                                               |
| unpickle                  | 8.44 us                                                     | 8.15 us: 1.03x faster                                               |
| pickle_dict               | 18.9 us                                                     | 18.3 us: 1.03x faster                                               |
| sqlglot_normalize         | 183 ms                                                      | 178 ms: 1.03x faster                                                |
| tomli_loads               | 1.38 sec                                                    | 1.34 sec: 1.03x faster                                              |
| docutils                  | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                              |
| sqlglot_transpile         | 1.02 ms                                                     | 990 us: 1.03x faster                                                |
| pickle                    | 7.38 us                                                     | 7.22 us: 1.02x faster                                               |
| xml_etree_generate        | 55.8 ms                                                     | 54.6 ms: 1.02x faster                                               |
| json_loads                | 13.6 us                                                     | 13.4 us: 1.02x faster                                               |
| spectral_norm             | 63.9 ms                                                     | 62.6 ms: 1.02x faster                                               |
| json_dumps                | 5.83 ms                                                     | 5.72 ms: 1.02x faster                                               |
| crypto_pyaes              | 46.4 ms                                                     | 45.6 ms: 1.02x faster                                               |
| xml_etree_process         | 37.6 ms                                                     | 37.0 ms: 1.02x faster                                               |
| regex_effbot              | 1.58 ms                                                     | 1.56 ms: 1.02x faster                                               |
| sympy_expand              | 278 ms                                                      | 274 ms: 1.01x faster                                                |
| pprint_pformat            | 1.04 sec                                                    | 1.02 sec: 1.01x faster                                              |
| chameleon                 | 4.95 ms                                                     | 4.89 ms: 1.01x faster                                               |
| logging_format            | 6.72 us                                                     | 6.63 us: 1.01x faster                                               |
| sqlglot_optimize          | 34.0 ms                                                     | 33.7 ms: 1.01x faster                                               |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.49 ms: 1.01x faster                                               |
| pathlib                   | 79.6 ms                                                     | 79.0 ms: 1.01x faster                                               |
| deepcopy_memo             | 23.4 us                                                     | 23.2 us: 1.01x faster                                               |
| sympy_integrate           | 13.0 ms                                                     | 12.9 ms: 1.00x faster                                               |
| mdp                       | 1.42 sec                                                    | 1.41 sec: 1.00x faster                                              |
| pidigits                  | 150 ms                                                      | 150 ms: 1.00x slower                                                |
| chaos                     | 42.1 ms                                                     | 42.3 ms: 1.00x slower                                               |
| tornado_http              | 87.2 ms                                                     | 88.0 ms: 1.01x slower                                               |
| gc_traversal              | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                               |
| unpickle_pure_python      | 134 us                                                      | 136 us: 1.01x slower                                                |
| bench_thread_pool         | 830 us                                                      | 847 us: 1.02x slower                                                |
| scimark_sor               | 79.8 ms                                                     | 81.4 ms: 1.02x slower                                               |
| 2to3                      | 213 ms                                                      | 217 ms: 1.02x slower                                                |
| deltablue                 | 2.12 ms                                                     | 2.17 ms: 1.02x slower                                               |
| async_generators          | 230 ms                                                      | 235 ms: 1.02x slower                                                |
| pyflate                   | 294 ms                                                      | 301 ms: 1.02x slower                                                |
| xml_etree_parse           | 90.5 ms                                                     | 92.8 ms: 1.03x slower                                               |
| async_tree_io             | 712 ms                                                      | 730 ms: 1.03x slower                                                |
| go                        | 89.0 ms                                                     | 91.3 ms: 1.03x slower                                               |
| xml_etree_iterparse       | 63.1 ms                                                     | 64.8 ms: 1.03x slower                                               |
| scimark_monte_carlo       | 43.0 ms                                                     | 44.1 ms: 1.03x slower                                               |
| scimark_lu                | 57.5 ms                                                     | 59.2 ms: 1.03x slower                                               |
| async_tree_memoization    | 333 ms                                                      | 343 ms: 1.03x slower                                                |
| async_tree_none_tg        | 277 ms                                                      | 285 ms: 1.03x slower                                                |
| fannkuch                  | 244 ms                                                      | 253 ms: 1.03x slower                                                |
| scimark_fft               | 181 ms                                                      | 188 ms: 1.04x slower                                                |
| async_tree_io_tg          | 742 ms                                                      | 770 ms: 1.04x slower                                                |
| nqueens                   | 61.7 ms                                                     | 64.1 ms: 1.04x slower                                               |
| meteor_contest            | 72.1 ms                                                     | 76.0 ms: 1.05x slower                                               |
| pycparser                 | 673 ms                                                      | 712 ms: 1.06x slower                                                |
| async_tree_memoization_tg | 345 ms                                                      | 366 ms: 1.06x slower                                                |
| nbody                     | 68.8 ms                                                     | 73.1 ms: 1.06x slower                                               |
| regex_v8                  | 13.5 ms                                                     | 14.7 ms: 1.09x slower                                               |
| python_startup            | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| telco                     | 4.08 ms                                                     | 4.59 ms: 1.12x slower                                               |
| hexiom                    | 4.00 ms                                                     | 4.56 ms: 1.14x slower                                               |
| coverage                  | 39.8 ms                                                     | 46.7 ms: 1.17x slower                                               |
| python_startup_no_site    | 15.9 ms                                                     | 18.9 ms: 1.19x slower                                               |
| unpack_sequence           | 36.9 ns                                                     | 44.4 ns: 1.20x slower                                               |
| mypy2                     | 209 ms                                                      | 292 ms: 1.40x slower                                                |
| Geometric mean            | (ref)                                                       | 1.00x faster                                                        |

Benchmark hidden because not significant (10): asyncio_tcp_ssl, unpickle_list, create_gc_cycles, async_tree_cpu_io_mixed_tg, regex_dna, pickle_list, pprint_safe_repr, json, logging_simple, asyncio_tcp
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 51.11% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
