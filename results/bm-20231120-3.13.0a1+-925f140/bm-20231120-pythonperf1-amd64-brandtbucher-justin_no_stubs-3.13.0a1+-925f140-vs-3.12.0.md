
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_stubs
- machine: windows-amd64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 227 ms: 1.07x slower                                                         |
| chameleon      | 4.95 ms                                                     | 5.02 ms: 1.01x slower                                                        |
| docutils       | 1.61 sec                                                    | 1.62 sec: 1.01x slower                                                       |
| tornado_http   | 87.2 ms                                                     | 92.0 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 281 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 512 ms: 1.06x slower                                                         |
| async_tree_io              | 712 ms                                                      | 757 ms: 1.06x slower                                                         |
| async_tree_memoization     | 333 ms                                                      | 357 ms: 1.07x slower                                                         |
| async_tree_io_tg           | 742 ms                                                      | 798 ms: 1.08x slower                                                         |
| async_tree_none_tg         | 277 ms                                                      | 298 ms: 1.08x slower                                                         |
| async_tree_memoization_tg  | 345 ms                                                      | 375 ms: 1.09x slower                                                         |
| Geometric mean             | (ref)                                                       | 1.05x slower                                                                 |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 68.8 ms                                                     | 66.3 ms: 1.04x faster                                                        |
| float          | 54.7 ms                                                     | 52.7 ms: 1.04x faster                                                        |
| pidigits       | 150 ms                                                      | 152 ms: 1.01x slower                                                         |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 83.4 ms: 1.05x faster                                                        |
| regex_dna      | 119 ms                                                      | 122 ms: 1.02x slower                                                         |
| regex_effbot   | 1.58 ms                                                     | 1.71 ms: 1.08x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 21.1 ms: 1.56x slower                                                        |
| Geometric mean | (ref)                                                       | 1.13x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 184 us: 1.06x faster                                                         |
| pickle               | 7.38 us                                                     | 7.03 us: 1.05x faster                                                        |
| tomli_loads          | 1.38 sec                                                    | 1.33 sec: 1.04x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 36.8 ms: 1.02x faster                                                        |
| unpickle             | 8.44 us                                                     | 8.26 us: 1.02x faster                                                        |
| xml_etree_generate   | 55.8 ms                                                     | 55.0 ms: 1.01x faster                                                        |
| unpickle_pure_python | 134 us                                                      | 135 us: 1.01x slower                                                         |
| pickle_dict          | 18.9 us                                                     | 19.2 us: 1.01x slower                                                        |
| unpickle_list        | 2.69 us                                                     | 2.74 us: 1.01x slower                                                        |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.5 ms: 1.02x slower                                                        |
| json_dumps           | 5.83 ms                                                     | 5.98 ms: 1.02x slower                                                        |
| xml_etree_parse      | 90.5 ms                                                     | 95.3 ms: 1.05x slower                                                        |
| json_loads           | 13.6 us                                                     | 14.6 us: 1.07x slower                                                        |
| pickle_list          | 2.88 us                                                     | 3.44 us: 1.19x slower                                                        |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                                        |
| python_startup_no_site | 15.9 ms                                                     | 19.1 ms: 1.20x slower                                                        |
| Geometric mean         | (ref)                                                       | 1.15x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.28 ms: 1.12x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 96.7 us                                                     | 77.0 us: 1.26x faster                                                        |
| comprehensions             | 14.0 us                                                     | 11.3 us: 1.24x faster                                                        |
| mako                       | 7.05 ms                                                     | 6.28 ms: 1.12x faster                                                        |
| raytrace                   | 192 ms                                                      | 173 ms: 1.11x faster                                                         |
| sqlite_synth               | 1.75 us                                                     | 1.57 us: 1.11x faster                                                        |
| richards_super             | 31.2 ms                                                     | 29.1 ms: 1.07x faster                                                        |
| generators                 | 22.6 ms                                                     | 21.3 ms: 1.06x faster                                                        |
| richards                   | 27.6 ms                                                     | 26.1 ms: 1.06x faster                                                        |
| pickle_pure_python         | 195 us                                                      | 184 us: 1.06x faster                                                         |
| pickle                     | 7.38 us                                                     | 7.03 us: 1.05x faster                                                        |
| deltablue                  | 2.12 ms                                                     | 2.03 ms: 1.05x faster                                                        |
| regex_compile              | 87.2 ms                                                     | 83.4 ms: 1.05x faster                                                        |
| sympy_str                  | 171 ms                                                      | 164 ms: 1.05x faster                                                         |
| logging_silent             | 60.5 ns                                                     | 58.2 ns: 1.04x faster                                                        |
| deepcopy_reduce            | 2.08 us                                                     | 2.01 us: 1.04x faster                                                        |
| nbody                      | 68.8 ms                                                     | 66.3 ms: 1.04x faster                                                        |
| float                      | 54.7 ms                                                     | 52.7 ms: 1.04x faster                                                        |
| tomli_loads                | 1.38 sec                                                    | 1.33 sec: 1.04x faster                                                       |
| sqlglot_parse              | 802 us                                                      | 775 us: 1.03x faster                                                         |
| sympy_sum                  | 90.1 ms                                                     | 87.3 ms: 1.03x faster                                                        |
| deepcopy                   | 233 us                                                      | 226 us: 1.03x faster                                                         |
| coroutines                 | 14.1 ms                                                     | 13.7 ms: 1.03x faster                                                        |
| xml_etree_process          | 37.6 ms                                                     | 36.8 ms: 1.02x faster                                                        |
| mdp                        | 1.42 sec                                                    | 1.39 sec: 1.02x faster                                                       |
| nqueens                    | 61.7 ms                                                     | 60.4 ms: 1.02x faster                                                        |
| unpickle                   | 8.44 us                                                     | 8.26 us: 1.02x faster                                                        |
| async_tree_none            | 286 ms                                                      | 281 ms: 1.02x faster                                                         |
| deepcopy_memo              | 23.4 us                                                     | 23.0 us: 1.02x faster                                                        |
| xml_etree_generate         | 55.8 ms                                                     | 55.0 ms: 1.01x faster                                                        |
| docutils                   | 1.61 sec                                                    | 1.62 sec: 1.01x slower                                                       |
| unpickle_pure_python       | 134 us                                                      | 135 us: 1.01x slower                                                         |
| chaos                      | 42.1 ms                                                     | 42.5 ms: 1.01x slower                                                        |
| sympy_integrate            | 13.0 ms                                                     | 13.1 ms: 1.01x slower                                                        |
| pprint_safe_repr           | 508 ms                                                      | 513 ms: 1.01x slower                                                         |
| sqlglot_normalize          | 183 ms                                                      | 186 ms: 1.01x slower                                                         |
| pickle_dict                | 18.9 us                                                     | 19.2 us: 1.01x slower                                                        |
| pathlib                    | 79.6 ms                                                     | 80.6 ms: 1.01x slower                                                        |
| chameleon                  | 4.95 ms                                                     | 5.02 ms: 1.01x slower                                                        |
| pidigits                   | 150 ms                                                      | 152 ms: 1.01x slower                                                         |
| logging_format             | 6.72 us                                                     | 6.82 us: 1.01x slower                                                        |
| unpickle_list              | 2.69 us                                                     | 2.74 us: 1.01x slower                                                        |
| logging_simple             | 6.21 us                                                     | 6.32 us: 1.02x slower                                                        |
| scimark_lu                 | 57.5 ms                                                     | 58.6 ms: 1.02x slower                                                        |
| fannkuch                   | 244 ms                                                      | 250 ms: 1.02x slower                                                         |
| xml_etree_iterparse        | 63.1 ms                                                     | 64.5 ms: 1.02x slower                                                        |
| regex_dna                  | 119 ms                                                      | 122 ms: 1.02x slower                                                         |
| json_dumps                 | 5.83 ms                                                     | 5.98 ms: 1.02x slower                                                        |
| pycparser                  | 673 ms                                                      | 692 ms: 1.03x slower                                                         |
| create_gc_cycles           | 726 us                                                      | 749 us: 1.03x slower                                                         |
| gc_traversal               | 1.49 ms                                                     | 1.54 ms: 1.03x slower                                                        |
| pyflate                    | 294 ms                                                      | 304 ms: 1.03x slower                                                         |
| scimark_sor                | 79.8 ms                                                     | 82.6 ms: 1.04x slower                                                        |
| dulwich_log                | 42.7 ms                                                     | 44.3 ms: 1.04x slower                                                        |
| sqlglot_optimize           | 34.0 ms                                                     | 35.4 ms: 1.04x slower                                                        |
| spectral_norm              | 63.9 ms                                                     | 66.9 ms: 1.05x slower                                                        |
| go                         | 89.0 ms                                                     | 93.1 ms: 1.05x slower                                                        |
| async_generators           | 230 ms                                                      | 241 ms: 1.05x slower                                                         |
| scimark_monte_carlo        | 43.0 ms                                                     | 45.1 ms: 1.05x slower                                                        |
| xml_etree_parse            | 90.5 ms                                                     | 95.3 ms: 1.05x slower                                                        |
| json                       | 2.94 ms                                                     | 3.10 ms: 1.05x slower                                                        |
| bench_thread_pool          | 830 us                                                      | 876 us: 1.05x slower                                                         |
| meteor_contest             | 72.1 ms                                                     | 76.1 ms: 1.06x slower                                                        |
| tornado_http               | 87.2 ms                                                     | 92.0 ms: 1.06x slower                                                        |
| dask                       | 255 ms                                                      | 269 ms: 1.06x slower                                                         |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 512 ms: 1.06x slower                                                         |
| async_tree_io              | 712 ms                                                      | 757 ms: 1.06x slower                                                         |
| 2to3                       | 213 ms                                                      | 227 ms: 1.07x slower                                                         |
| asyncio_tcp                | 471 ms                                                      | 502 ms: 1.07x slower                                                         |
| json_loads                 | 13.6 us                                                     | 14.6 us: 1.07x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 357 ms: 1.07x slower                                                         |
| scimark_fft                | 181 ms                                                      | 194 ms: 1.07x slower                                                         |
| async_tree_io_tg           | 742 ms                                                      | 798 ms: 1.08x slower                                                         |
| hexiom                     | 4.00 ms                                                     | 4.31 ms: 1.08x slower                                                        |
| async_tree_none_tg         | 277 ms                                                      | 298 ms: 1.08x slower                                                         |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.71 ms: 1.08x slower                                                        |
| unpack_sequence            | 36.9 ns                                                     | 40.0 ns: 1.08x slower                                                        |
| regex_effbot               | 1.58 ms                                                     | 1.71 ms: 1.08x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 375 ms: 1.09x slower                                                         |
| python_startup             | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                                        |
| telco                      | 4.08 ms                                                     | 4.76 ms: 1.17x slower                                                        |
| pickle_list                | 2.88 us                                                     | 3.44 us: 1.19x slower                                                        |
| python_startup_no_site     | 15.9 ms                                                     | 19.1 ms: 1.20x slower                                                        |
| coverage                   | 39.8 ms                                                     | 51.3 ms: 1.29x slower                                                        |
| mypy2                      | 209 ms                                                      | 304 ms: 1.46x slower                                                         |
| regex_v8                   | 13.5 ms                                                     | 21.1 ms: 1.56x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.02x slower                                                                 |

Benchmark hidden because not significant (7): asyncio_tcp_ssl, async_tree_cpu_io_mixed, sqlglot_transpile, sympy_expand, crypto_pyaes, pprint_pformat, bench_mp_pool
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.98% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
