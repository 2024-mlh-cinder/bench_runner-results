
# Results vs. 3.12.0

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 48b46e7
- commit date: 2023-11-17
- overall geometric mean: 1.04x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 207 ms: 1.02x faster                                                        |
| chameleon      | 4.95 ms                                                     | 4.67 ms: 1.06x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.53 sec: 1.05x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 85.6 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 262 ms: 1.09x faster                                                        |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 445 ms: 1.07x faster                                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 473 ms: 1.02x faster                                                        |
| async_tree_memoization     | 333 ms                                                      | 338 ms: 1.01x slower                                                        |
| async_tree_io              | 712 ms                                                      | 724 ms: 1.02x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 756 ms: 1.02x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 354 ms: 1.03x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 51.0 ms: 1.07x faster                                                       |
| nbody          | 68.8 ms                                                     | 66.3 ms: 1.04x faster                                                       |
| pidigits       | 150 ms                                                      | 146 ms: 1.02x faster                                                        |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 77.5 ms: 1.13x faster                                                       |
| regex_effbot   | 1.58 ms                                                     | 1.60 ms: 1.01x slower                                                       |
| regex_dna      | 119 ms                                                      | 121 ms: 1.02x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 15.3 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 172 us: 1.13x faster                                                        |
| unpickle_pure_python | 134 us                                                      | 123 us: 1.09x faster                                                        |
| xml_etree_generate   | 55.8 ms                                                     | 52.3 ms: 1.07x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.48 ms: 1.06x faster                                                       |
| pickle               | 7.38 us                                                     | 6.95 us: 1.06x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 35.9 ms: 1.05x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.63 us: 1.02x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.82 us: 1.02x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.5 us: 1.02x faster                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 62.5 ms: 1.01x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 91.7 ms: 1.01x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (2): tomli_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.5 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.7 ms: 1.11x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.36 ms: 1.11x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions             | 14.0 us                                                     | 9.92 us: 1.41x faster                                                       |
| typing_runtime_protocols   | 96.7 us                                                     | 73.6 us: 1.31x faster                                                       |
| raytrace                   | 192 ms                                                      | 161 ms: 1.20x faster                                                        |
| pickle_pure_python         | 195 us                                                      | 172 us: 1.13x faster                                                        |
| crypto_pyaes               | 46.4 ms                                                     | 41.3 ms: 1.13x faster                                                       |
| regex_compile              | 87.2 ms                                                     | 77.5 ms: 1.13x faster                                                       |
| sympy_sum                  | 90.1 ms                                                     | 80.2 ms: 1.12x faster                                                       |
| sqlite_synth               | 1.75 us                                                     | 1.56 us: 1.12x faster                                                       |
| logging_silent             | 60.5 ns                                                     | 54.0 ns: 1.12x faster                                                       |
| generators                 | 22.6 ms                                                     | 20.2 ms: 1.12x faster                                                       |
| sympy_str                  | 171 ms                                                      | 154 ms: 1.11x faster                                                        |
| chaos                      | 42.1 ms                                                     | 38.0 ms: 1.11x faster                                                       |
| mako                       | 7.05 ms                                                     | 6.36 ms: 1.11x faster                                                       |
| nqueens                    | 61.7 ms                                                     | 56.1 ms: 1.10x faster                                                       |
| hexiom                     | 4.00 ms                                                     | 3.64 ms: 1.10x faster                                                       |
| unpickle_pure_python       | 134 us                                                      | 123 us: 1.09x faster                                                        |
| async_tree_none            | 286 ms                                                      | 262 ms: 1.09x faster                                                        |
| deepcopy_reduce            | 2.08 us                                                     | 1.92 us: 1.09x faster                                                       |
| richards_super             | 31.2 ms                                                     | 28.8 ms: 1.08x faster                                                       |
| sqlglot_parse              | 802 us                                                      | 741 us: 1.08x faster                                                        |
| go                         | 89.0 ms                                                     | 82.4 ms: 1.08x faster                                                       |
| sqlglot_normalize          | 183 ms                                                      | 170 ms: 1.08x faster                                                        |
| scimark_lu                 | 57.5 ms                                                     | 53.5 ms: 1.07x faster                                                       |
| coroutines                 | 14.1 ms                                                     | 13.1 ms: 1.07x faster                                                       |
| pprint_pformat             | 1.04 sec                                                    | 966 ms: 1.07x faster                                                        |
| sympy_integrate            | 13.0 ms                                                     | 12.1 ms: 1.07x faster                                                       |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 445 ms: 1.07x faster                                                        |
| deltablue                  | 2.12 ms                                                     | 1.98 ms: 1.07x faster                                                       |
| richards                   | 27.6 ms                                                     | 25.7 ms: 1.07x faster                                                       |
| float                      | 54.7 ms                                                     | 51.0 ms: 1.07x faster                                                       |
| scimark_monte_carlo        | 43.0 ms                                                     | 40.2 ms: 1.07x faster                                                       |
| pprint_safe_repr           | 508 ms                                                      | 474 ms: 1.07x faster                                                        |
| bench_mp_pool              | 67.2 ms                                                     | 62.9 ms: 1.07x faster                                                       |
| deepcopy                   | 233 us                                                      | 218 us: 1.07x faster                                                        |
| dulwich_log                | 42.7 ms                                                     | 40.0 ms: 1.07x faster                                                       |
| pathlib                    | 79.6 ms                                                     | 74.6 ms: 1.07x faster                                                       |
| xml_etree_generate         | 55.8 ms                                                     | 52.3 ms: 1.07x faster                                                       |
| json_dumps                 | 5.83 ms                                                     | 5.48 ms: 1.06x faster                                                       |
| sqlglot_transpile          | 1.02 ms                                                     | 955 us: 1.06x faster                                                        |
| pickle                     | 7.38 us                                                     | 6.95 us: 1.06x faster                                                       |
| chameleon                  | 4.95 ms                                                     | 4.67 ms: 1.06x faster                                                       |
| scimark_fft                | 181 ms                                                      | 171 ms: 1.06x faster                                                        |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.38 ms: 1.05x faster                                                       |
| pyflate                    | 294 ms                                                      | 279 ms: 1.05x faster                                                        |
| docutils                   | 1.61 sec                                                    | 1.53 sec: 1.05x faster                                                      |
| sqlglot_optimize           | 34.0 ms                                                     | 32.3 ms: 1.05x faster                                                       |
| sympy_expand               | 278 ms                                                      | 265 ms: 1.05x faster                                                        |
| xml_etree_process          | 37.6 ms                                                     | 35.9 ms: 1.05x faster                                                       |
| fannkuch                   | 244 ms                                                      | 234 ms: 1.04x faster                                                        |
| logging_format             | 6.72 us                                                     | 6.48 us: 1.04x faster                                                       |
| nbody                      | 68.8 ms                                                     | 66.3 ms: 1.04x faster                                                       |
| deepcopy_memo              | 23.4 us                                                     | 22.6 us: 1.04x faster                                                       |
| spectral_norm              | 63.9 ms                                                     | 61.9 ms: 1.03x faster                                                       |
| scimark_sor                | 79.8 ms                                                     | 77.5 ms: 1.03x faster                                                       |
| logging_simple             | 6.21 us                                                     | 6.04 us: 1.03x faster                                                       |
| unpickle_list              | 2.69 us                                                     | 2.63 us: 1.02x faster                                                       |
| 2to3                       | 213 ms                                                      | 207 ms: 1.02x faster                                                        |
| pidigits                   | 150 ms                                                      | 146 ms: 1.02x faster                                                        |
| pickle_list                | 2.88 us                                                     | 2.82 us: 1.02x faster                                                       |
| pickle_dict                | 18.9 us                                                     | 18.5 us: 1.02x faster                                                       |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 473 ms: 1.02x faster                                                        |
| tornado_http               | 87.2 ms                                                     | 85.6 ms: 1.02x faster                                                       |
| meteor_contest             | 72.1 ms                                                     | 70.9 ms: 1.02x faster                                                       |
| dask                       | 255 ms                                                      | 251 ms: 1.01x faster                                                        |
| xml_etree_iterparse        | 63.1 ms                                                     | 62.5 ms: 1.01x faster                                                       |
| async_generators           | 230 ms                                                      | 228 ms: 1.01x faster                                                        |
| json_loads                 | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| mdp                        | 1.42 sec                                                    | 1.41 sec: 1.01x faster                                                      |
| regex_effbot               | 1.58 ms                                                     | 1.60 ms: 1.01x slower                                                       |
| xml_etree_parse            | 90.5 ms                                                     | 91.7 ms: 1.01x slower                                                       |
| async_tree_memoization     | 333 ms                                                      | 338 ms: 1.01x slower                                                        |
| async_tree_io              | 712 ms                                                      | 724 ms: 1.02x slower                                                        |
| regex_dna                  | 119 ms                                                      | 121 ms: 1.02x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 756 ms: 1.02x slower                                                        |
| unpack_sequence            | 36.9 ns                                                     | 37.6 ns: 1.02x slower                                                       |
| create_gc_cycles           | 726 us                                                      | 745 us: 1.03x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 354 ms: 1.03x slower                                                        |
| python_startup             | 18.8 ms                                                     | 19.5 ms: 1.04x slower                                                       |
| pycparser                  | 673 ms                                                      | 714 ms: 1.06x slower                                                        |
| python_startup_no_site     | 15.9 ms                                                     | 17.7 ms: 1.11x slower                                                       |
| telco                      | 4.08 ms                                                     | 4.57 ms: 1.12x slower                                                       |
| regex_v8                   | 13.5 ms                                                     | 15.3 ms: 1.13x slower                                                       |
| coverage                   | 39.8 ms                                                     | 45.6 ms: 1.15x slower                                                       |
| mypy2                      | 209 ms                                                      | 284 ms: 1.36x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (8): tomli_loads, asyncio_tcp, async_tree_none_tg, json, unpickle, gc_traversal, asyncio_tcp_ssl, bench_thread_pool
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
