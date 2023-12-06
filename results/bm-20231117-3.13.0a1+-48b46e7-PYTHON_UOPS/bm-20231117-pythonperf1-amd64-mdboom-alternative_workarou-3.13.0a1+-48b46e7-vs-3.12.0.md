
# Results vs. 3.12.0

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 48b46e7
- commit date: 2023-11-17
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.95%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 218 ms: 1.03x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.02 ms: 1.01x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.58 sec: 1.02x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 89.2 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 271 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 460 ms: 1.04x faster                                                        |
| async_tree_io             | 712 ms                                                      | 727 ms: 1.02x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 765 ms: 1.03x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 286 ms: 1.03x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 345 ms: 1.04x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 366 ms: 1.06x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 148 ms: 1.02x faster                                                        |
| float          | 54.7 ms                                                     | 61.7 ms: 1.13x slower                                                       |
| nbody          | 68.8 ms                                                     | 83.9 ms: 1.22x slower                                                       |
| Geometric mean | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 119 ms                                                      | 122 ms: 1.02x slower                                                        |
| regex_compile  | 87.2 ms                                                     | 92.7 ms: 1.06x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 15.3 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 179 us: 1.08x faster                                                        |
| pickle               | 7.38 us                                                     | 6.93 us: 1.06x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.0 ms: 1.03x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 36.4 ms: 1.03x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.19 us: 1.03x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.70 ms: 1.02x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.6 us: 1.02x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.01x faster                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 92.9 ms: 1.03x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 67.1 ms: 1.06x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 143 us: 1.06x slower                                                        |
| pickle_list          | 2.88 us                                                     | 3.09 us: 1.07x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.59 sec: 1.15x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.6 ms: 1.10x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 8.20 ms: 1.16x slower                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols  | 96.7 us                                                     | 79.5 us: 1.22x faster                                                       |
| generators                | 22.6 ms                                                     | 20.4 ms: 1.11x faster                                                       |
| sqlite_synth              | 1.75 us                                                     | 1.59 us: 1.10x faster                                                       |
| raytrace                  | 192 ms                                                      | 177 ms: 1.09x faster                                                        |
| pickle_pure_python        | 195 us                                                      | 179 us: 1.08x faster                                                        |
| logging_silent            | 60.5 ns                                                     | 56.5 ns: 1.07x faster                                                       |
| pickle                    | 7.38 us                                                     | 6.93 us: 1.06x faster                                                       |
| coroutines                | 14.1 ms                                                     | 13.3 ms: 1.06x faster                                                       |
| deepcopy_reduce           | 2.08 us                                                     | 1.96 us: 1.06x faster                                                       |
| pathlib                   | 79.6 ms                                                     | 74.8 ms: 1.06x faster                                                       |
| bench_mp_pool             | 67.2 ms                                                     | 63.3 ms: 1.06x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 85.5 ms: 1.05x faster                                                       |
| deepcopy                  | 233 us                                                      | 221 us: 1.05x faster                                                        |
| async_tree_none           | 286 ms                                                      | 271 ms: 1.05x faster                                                        |
| asyncio_tcp_ssl           | 1.89 sec                                                    | 1.79 sec: 1.05x faster                                                      |
| sqlglot_normalize         | 183 ms                                                      | 176 ms: 1.04x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 460 ms: 1.04x faster                                                        |
| xml_etree_generate        | 55.8 ms                                                     | 54.0 ms: 1.03x faster                                                       |
| xml_etree_process         | 37.6 ms                                                     | 36.4 ms: 1.03x faster                                                       |
| unpickle                  | 8.44 us                                                     | 8.19 us: 1.03x faster                                                       |
| sympy_str                 | 171 ms                                                      | 166 ms: 1.03x faster                                                        |
| json_dumps                | 5.83 ms                                                     | 5.70 ms: 1.02x faster                                                       |
| docutils                  | 1.61 sec                                                    | 1.58 sec: 1.02x faster                                                      |
| sqlglot_optimize          | 34.0 ms                                                     | 33.4 ms: 1.02x faster                                                       |
| sqlglot_parse             | 802 us                                                      | 787 us: 1.02x faster                                                        |
| pidigits                  | 150 ms                                                      | 148 ms: 1.02x faster                                                        |
| pickle_dict               | 18.9 us                                                     | 18.6 us: 1.02x faster                                                       |
| json_loads                | 13.6 us                                                     | 13.4 us: 1.01x faster                                                       |
| richards_super            | 31.2 ms                                                     | 30.8 ms: 1.01x faster                                                       |
| dulwich_log               | 42.7 ms                                                     | 42.3 ms: 1.01x faster                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 1.01 ms: 1.01x faster                                                       |
| spectral_norm             | 63.9 ms                                                     | 64.3 ms: 1.01x slower                                                       |
| gc_traversal              | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                                       |
| create_gc_cycles          | 726 us                                                      | 736 us: 1.01x slower                                                        |
| chameleon                 | 4.95 ms                                                     | 5.02 ms: 1.01x slower                                                       |
| sympy_expand              | 278 ms                                                      | 283 ms: 1.02x slower                                                        |
| regex_dna                 | 119 ms                                                      | 122 ms: 1.02x slower                                                        |
| async_tree_io             | 712 ms                                                      | 727 ms: 1.02x slower                                                        |
| deepcopy_memo             | 23.4 us                                                     | 23.9 us: 1.02x slower                                                       |
| pycparser                 | 673 ms                                                      | 689 ms: 1.02x slower                                                        |
| tornado_http              | 87.2 ms                                                     | 89.2 ms: 1.02x slower                                                       |
| bench_thread_pool         | 830 us                                                      | 850 us: 1.02x slower                                                        |
| 2to3                      | 213 ms                                                      | 218 ms: 1.03x slower                                                        |
| xml_etree_parse           | 90.5 ms                                                     | 92.9 ms: 1.03x slower                                                       |
| sympy_integrate           | 13.0 ms                                                     | 13.3 ms: 1.03x slower                                                       |
| async_tree_io_tg          | 742 ms                                                      | 765 ms: 1.03x slower                                                        |
| logging_format            | 6.72 us                                                     | 6.93 us: 1.03x slower                                                       |
| async_tree_none_tg        | 277 ms                                                      | 286 ms: 1.03x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 345 ms: 1.04x slower                                                        |
| scimark_sor               | 79.8 ms                                                     | 82.8 ms: 1.04x slower                                                       |
| python_startup            | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| async_generators          | 230 ms                                                      | 240 ms: 1.04x slower                                                        |
| logging_simple            | 6.21 us                                                     | 6.48 us: 1.04x slower                                                       |
| pprint_safe_repr          | 508 ms                                                      | 533 ms: 1.05x slower                                                        |
| pprint_pformat            | 1.04 sec                                                    | 1.10 sec: 1.06x slower                                                      |
| scimark_lu                | 57.5 ms                                                     | 60.9 ms: 1.06x slower                                                       |
| xml_etree_iterparse       | 63.1 ms                                                     | 67.1 ms: 1.06x slower                                                       |
| async_tree_memoization_tg | 345 ms                                                      | 366 ms: 1.06x slower                                                        |
| regex_compile             | 87.2 ms                                                     | 92.7 ms: 1.06x slower                                                       |
| unpickle_pure_python      | 134 us                                                      | 143 us: 1.06x slower                                                        |
| meteor_contest            | 72.1 ms                                                     | 77.0 ms: 1.07x slower                                                       |
| pickle_list               | 2.88 us                                                     | 3.09 us: 1.07x slower                                                       |
| chaos                     | 42.1 ms                                                     | 45.2 ms: 1.07x slower                                                       |
| mdp                       | 1.42 sec                                                    | 1.53 sec: 1.08x slower                                                      |
| go                        | 89.0 ms                                                     | 97.5 ms: 1.10x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 17.6 ms: 1.10x slower                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 52.1 ms: 1.12x slower                                                       |
| comprehensions            | 14.0 us                                                     | 15.7 us: 1.12x slower                                                       |
| float                     | 54.7 ms                                                     | 61.7 ms: 1.13x slower                                                       |
| coverage                  | 39.8 ms                                                     | 44.9 ms: 1.13x slower                                                       |
| scimark_monte_carlo       | 43.0 ms                                                     | 48.6 ms: 1.13x slower                                                       |
| regex_v8                  | 13.5 ms                                                     | 15.3 ms: 1.13x slower                                                       |
| nqueens                   | 61.7 ms                                                     | 70.6 ms: 1.14x slower                                                       |
| tomli_loads               | 1.38 sec                                                    | 1.59 sec: 1.15x slower                                                      |
| pyflate                   | 294 ms                                                      | 340 ms: 1.16x slower                                                        |
| mako                      | 7.05 ms                                                     | 8.20 ms: 1.16x slower                                                       |
| telco                     | 4.08 ms                                                     | 4.75 ms: 1.16x slower                                                       |
| scimark_fft               | 181 ms                                                      | 218 ms: 1.20x slower                                                        |
| nbody                     | 68.8 ms                                                     | 83.9 ms: 1.22x slower                                                       |
| fannkuch                  | 244 ms                                                      | 298 ms: 1.22x slower                                                        |
| unpack_sequence           | 36.9 ns                                                     | 48.1 ns: 1.30x slower                                                       |
| mypy2                     | 209 ms                                                      | 292 ms: 1.40x slower                                                        |
| deltablue                 | 2.12 ms                                                     | 2.98 ms: 1.41x slower                                                       |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 3.68 ms: 1.47x slower                                                       |
| hexiom                    | 4.00 ms                                                     | 6.04 ms: 1.51x slower                                                       |
| Geometric mean            | (ref)                                                       | 1.04x slower                                                                |

Benchmark hidden because not significant (7): dask, richards, asyncio_tcp, regex_effbot, unpickle_list, async_tree_cpu_io_mixed_tg, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.95% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
