
# Results vs. 3.12.0

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: c47be17
- commit date: 2023-11-17
- overall geometric mean: 1.01x faster \*
- HPT reliability: 95.30%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 210 ms: 1.01x faster                                                        |
| chameleon      | 4.95 ms                                                     | 4.90 ms: 1.01x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.55 sec: 1.04x faster                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 265 ms: 1.08x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 454 ms: 1.05x faster                                                        |
| async_tree_none_tg        | 277 ms                                                      | 280 ms: 1.01x slower                                                        |
| async_tree_io             | 712 ms                                                      | 720 ms: 1.01x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 343 ms: 1.03x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 765 ms: 1.03x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 361 ms: 1.05x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 51.5 ms: 1.06x faster                                                       |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 73.5 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 83.7 ms: 1.04x faster                                                       |
| regex_dna      | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 15.2 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 183 us: 1.06x faster                                                        |
| unpickle             | 8.44 us                                                     | 8.04 us: 1.05x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.59 ms: 1.04x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.61 us: 1.03x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.2 ms: 1.03x faster                                                       |
| pickle               | 7.38 us                                                     | 7.17 us: 1.03x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.6 us: 1.02x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.02x faster                                                       |
| unpickle_pure_python | 134 us                                                      | 132 us: 1.02x faster                                                        |
| xml_etree_process    | 37.6 ms                                                     | 37.3 ms: 1.01x faster                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 63.7 ms: 1.01x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 93.3 ms: 1.03x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (2): tomli_loads, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.8 ms: 1.11x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.59 ms: 1.07x faster                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions            | 14.0 us                                                     | 10.3 us: 1.36x faster                                                       |
| typing_runtime_protocols  | 96.7 us                                                     | 74.1 us: 1.30x faster                                                       |
| raytrace                  | 192 ms                                                      | 171 ms: 1.12x faster                                                        |
| sqlite_synth              | 1.75 us                                                     | 1.56 us: 1.12x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 82.8 ms: 1.09x faster                                                       |
| async_tree_none           | 286 ms                                                      | 265 ms: 1.08x faster                                                        |
| generators                | 22.6 ms                                                     | 21.0 ms: 1.08x faster                                                       |
| bench_mp_pool             | 67.2 ms                                                     | 62.4 ms: 1.08x faster                                                       |
| sympy_integrate           | 13.0 ms                                                     | 12.1 ms: 1.07x faster                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 43.4 ms: 1.07x faster                                                       |
| mako                      | 7.05 ms                                                     | 6.59 ms: 1.07x faster                                                       |
| pathlib                   | 79.6 ms                                                     | 74.5 ms: 1.07x faster                                                       |
| deepcopy_reduce           | 2.08 us                                                     | 1.95 us: 1.07x faster                                                       |
| deepcopy                  | 233 us                                                      | 219 us: 1.06x faster                                                        |
| pickle_pure_python        | 195 us                                                      | 183 us: 1.06x faster                                                        |
| sympy_str                 | 171 ms                                                      | 161 ms: 1.06x faster                                                        |
| scimark_monte_carlo       | 43.0 ms                                                     | 40.5 ms: 1.06x faster                                                       |
| float                     | 54.7 ms                                                     | 51.5 ms: 1.06x faster                                                       |
| logging_silent            | 60.5 ns                                                     | 57.1 ns: 1.06x faster                                                       |
| sqlglot_normalize         | 183 ms                                                      | 173 ms: 1.06x faster                                                        |
| spectral_norm             | 63.9 ms                                                     | 60.6 ms: 1.05x faster                                                       |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 454 ms: 1.05x faster                                                        |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.39 ms: 1.05x faster                                                       |
| sqlglot_parse             | 802 us                                                      | 763 us: 1.05x faster                                                        |
| unpickle                  | 8.44 us                                                     | 8.04 us: 1.05x faster                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 969 us: 1.05x faster                                                        |
| chaos                     | 42.1 ms                                                     | 40.2 ms: 1.05x faster                                                       |
| json_dumps                | 5.83 ms                                                     | 5.59 ms: 1.04x faster                                                       |
| regex_compile             | 87.2 ms                                                     | 83.7 ms: 1.04x faster                                                       |
| pprint_pformat            | 1.04 sec                                                    | 997 ms: 1.04x faster                                                        |
| nqueens                   | 61.7 ms                                                     | 59.3 ms: 1.04x faster                                                       |
| pprint_safe_repr          | 508 ms                                                      | 490 ms: 1.04x faster                                                        |
| docutils                  | 1.61 sec                                                    | 1.55 sec: 1.04x faster                                                      |
| deltablue                 | 2.12 ms                                                     | 2.05 ms: 1.03x faster                                                       |
| unpickle_list             | 2.69 us                                                     | 2.61 us: 1.03x faster                                                       |
| sqlglot_optimize          | 34.0 ms                                                     | 32.9 ms: 1.03x faster                                                       |
| xml_etree_generate        | 55.8 ms                                                     | 54.2 ms: 1.03x faster                                                       |
| pickle                    | 7.38 us                                                     | 7.17 us: 1.03x faster                                                       |
| logging_format            | 6.72 us                                                     | 6.56 us: 1.02x faster                                                       |
| logging_simple            | 6.21 us                                                     | 6.07 us: 1.02x faster                                                       |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| go                        | 89.0 ms                                                     | 87.4 ms: 1.02x faster                                                       |
| pyflate                   | 294 ms                                                      | 288 ms: 1.02x faster                                                        |
| pickle_dict               | 18.9 us                                                     | 18.6 us: 1.02x faster                                                       |
| json_loads                | 13.6 us                                                     | 13.4 us: 1.02x faster                                                       |
| unpickle_pure_python      | 134 us                                                      | 132 us: 1.02x faster                                                        |
| 2to3                      | 213 ms                                                      | 210 ms: 1.01x faster                                                        |
| async_generators          | 230 ms                                                      | 228 ms: 1.01x faster                                                        |
| xml_etree_process         | 37.6 ms                                                     | 37.3 ms: 1.01x faster                                                       |
| chameleon                 | 4.95 ms                                                     | 4.90 ms: 1.01x faster                                                       |
| sympy_expand              | 278 ms                                                      | 276 ms: 1.01x faster                                                        |
| coroutines                | 14.1 ms                                                     | 14.0 ms: 1.01x faster                                                       |
| hexiom                    | 4.00 ms                                                     | 3.97 ms: 1.01x faster                                                       |
| gc_traversal              | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                                       |
| xml_etree_iterparse       | 63.1 ms                                                     | 63.7 ms: 1.01x slower                                                       |
| dulwich_log               | 42.7 ms                                                     | 43.1 ms: 1.01x slower                                                       |
| async_tree_none_tg        | 277 ms                                                      | 280 ms: 1.01x slower                                                        |
| mdp                       | 1.42 sec                                                    | 1.44 sec: 1.01x slower                                                      |
| async_tree_io             | 712 ms                                                      | 720 ms: 1.01x slower                                                        |
| regex_dna                 | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| deepcopy_memo             | 23.4 us                                                     | 23.8 us: 1.02x slower                                                       |
| meteor_contest            | 72.1 ms                                                     | 73.5 ms: 1.02x slower                                                       |
| unpack_sequence           | 36.9 ns                                                     | 37.6 ns: 1.02x slower                                                       |
| scimark_sor               | 79.8 ms                                                     | 81.4 ms: 1.02x slower                                                       |
| create_gc_cycles          | 726 us                                                      | 742 us: 1.02x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 343 ms: 1.03x slower                                                        |
| xml_etree_parse           | 90.5 ms                                                     | 93.3 ms: 1.03x slower                                                       |
| async_tree_io_tg          | 742 ms                                                      | 765 ms: 1.03x slower                                                        |
| richards_super            | 31.2 ms                                                     | 32.2 ms: 1.03x slower                                                       |
| python_startup            | 18.8 ms                                                     | 19.7 ms: 1.05x slower                                                       |
| async_tree_memoization_tg | 345 ms                                                      | 361 ms: 1.05x slower                                                        |
| richards                  | 27.6 ms                                                     | 29.0 ms: 1.05x slower                                                       |
| scimark_lu                | 57.5 ms                                                     | 60.9 ms: 1.06x slower                                                       |
| fannkuch                  | 244 ms                                                      | 261 ms: 1.07x slower                                                        |
| nbody                     | 68.8 ms                                                     | 73.5 ms: 1.07x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 17.8 ms: 1.11x slower                                                       |
| regex_v8                  | 13.5 ms                                                     | 15.2 ms: 1.13x slower                                                       |
| telco                     | 4.08 ms                                                     | 4.62 ms: 1.13x slower                                                       |
| coverage                  | 39.8 ms                                                     | 46.7 ms: 1.17x slower                                                       |
| pycparser                 | 673 ms                                                      | 795 ms: 1.18x slower                                                        |
| mypy2                     | 209 ms                                                      | 287 ms: 1.38x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (11): async_tree_cpu_io_mixed_tg, tomli_loads, tornado_http, scimark_fft, bench_thread_pool, regex_effbot, asyncio_tcp_ssl, pickle_list, dask, asyncio_tcp, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 95.30% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
