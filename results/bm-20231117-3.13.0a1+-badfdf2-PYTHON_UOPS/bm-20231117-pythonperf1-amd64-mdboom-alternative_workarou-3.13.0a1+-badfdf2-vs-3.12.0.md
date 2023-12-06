
# Results vs. 3.12.0

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: badfdf2
- commit date: 2023-11-17
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 223 ms: 1.05x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.13 ms: 1.04x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.62 sec: 1.00x slower                                                      |
| tornado_http   | 87.2 ms                                                     | 88.9 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 273 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 461 ms: 1.04x faster                                                        |
| async_tree_io             | 712 ms                                                      | 739 ms: 1.04x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 289 ms: 1.04x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 777 ms: 1.05x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 349 ms: 1.05x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 370 ms: 1.07x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| float          | 54.7 ms                                                     | 61.0 ms: 1.12x slower                                                       |
| nbody          | 68.8 ms                                                     | 81.7 ms: 1.19x slower                                                       |
| Geometric mean | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 14.9 ms: 1.11x slower                                                       |
| regex_compile  | 87.2 ms                                                     | 96.9 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 7.03 us: 1.05x faster                                                       |
| pickle_pure_python   | 195 us                                                      | 187 us: 1.04x faster                                                        |
| pickle_dict          | 18.9 us                                                     | 18.3 us: 1.03x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.65 ms: 1.03x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.65 us: 1.02x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.9 ms: 1.02x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.5 ms: 1.00x faster                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 91.8 ms: 1.01x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 67.2 ms: 1.06x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 146 us: 1.09x slower                                                        |
| pickle_list          | 2.88 us                                                     | 3.27 us: 1.13x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.62 sec: 1.18x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.7 ms: 1.11x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 7.99 ms: 1.13x slower                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols  | 96.7 us                                                     | 79.4 us: 1.22x faster                                                       |
| sqlite_synth              | 1.75 us                                                     | 1.59 us: 1.09x faster                                                       |
| bench_mp_pool             | 67.2 ms                                                     | 63.2 ms: 1.06x faster                                                       |
| generators                | 22.6 ms                                                     | 21.3 ms: 1.06x faster                                                       |
| pathlib                   | 79.6 ms                                                     | 75.0 ms: 1.06x faster                                                       |
| deepcopy_reduce           | 2.08 us                                                     | 1.96 us: 1.06x faster                                                       |
| coroutines                | 14.1 ms                                                     | 13.4 ms: 1.05x faster                                                       |
| asyncio_tcp_ssl           | 1.89 sec                                                    | 1.80 sec: 1.05x faster                                                      |
| pickle                    | 7.38 us                                                     | 7.03 us: 1.05x faster                                                       |
| async_tree_none           | 286 ms                                                      | 273 ms: 1.05x faster                                                        |
| deepcopy                  | 233 us                                                      | 224 us: 1.04x faster                                                        |
| pickle_pure_python        | 195 us                                                      | 187 us: 1.04x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 461 ms: 1.04x faster                                                        |
| pickle_dict               | 18.9 us                                                     | 18.3 us: 1.03x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 87.1 ms: 1.03x faster                                                       |
| json_dumps                | 5.83 ms                                                     | 5.65 ms: 1.03x faster                                                       |
| sqlglot_normalize         | 183 ms                                                      | 178 ms: 1.03x faster                                                        |
| raytrace                  | 192 ms                                                      | 187 ms: 1.03x faster                                                        |
| asyncio_tcp               | 471 ms                                                      | 459 ms: 1.03x faster                                                        |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| unpickle_list             | 2.69 us                                                     | 2.65 us: 1.02x faster                                                       |
| xml_etree_generate        | 55.8 ms                                                     | 54.9 ms: 1.02x faster                                                       |
| json_loads                | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| spectral_norm             | 63.9 ms                                                     | 63.3 ms: 1.01x faster                                                       |
| logging_silent            | 60.5 ns                                                     | 60.2 ns: 1.01x faster                                                       |
| xml_etree_process         | 37.6 ms                                                     | 37.5 ms: 1.00x faster                                                       |
| sympy_str                 | 171 ms                                                      | 172 ms: 1.00x slower                                                        |
| docutils                  | 1.61 sec                                                    | 1.62 sec: 1.00x slower                                                      |
| regex_effbot              | 1.58 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 1.02 ms: 1.01x slower                                                       |
| sqlglot_parse             | 802 us                                                      | 812 us: 1.01x slower                                                        |
| xml_etree_parse           | 90.5 ms                                                     | 91.8 ms: 1.01x slower                                                       |
| richards_super            | 31.2 ms                                                     | 31.7 ms: 1.02x slower                                                       |
| tornado_http              | 87.2 ms                                                     | 88.9 ms: 1.02x slower                                                       |
| dask                      | 255 ms                                                      | 260 ms: 1.02x slower                                                        |
| unpack_sequence           | 36.9 ns                                                     | 37.7 ns: 1.02x slower                                                       |
| richards                  | 27.6 ms                                                     | 28.3 ms: 1.03x slower                                                       |
| bench_thread_pool         | 830 us                                                      | 854 us: 1.03x slower                                                        |
| async_generators          | 230 ms                                                      | 237 ms: 1.03x slower                                                        |
| chameleon                 | 4.95 ms                                                     | 5.13 ms: 1.04x slower                                                       |
| async_tree_io             | 712 ms                                                      | 739 ms: 1.04x slower                                                        |
| sympy_integrate           | 13.0 ms                                                     | 13.5 ms: 1.04x slower                                                       |
| python_startup            | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| async_tree_none_tg        | 277 ms                                                      | 289 ms: 1.04x slower                                                        |
| logging_format            | 6.72 us                                                     | 7.02 us: 1.05x slower                                                       |
| async_tree_io_tg          | 742 ms                                                      | 777 ms: 1.05x slower                                                        |
| scimark_sor               | 79.8 ms                                                     | 83.6 ms: 1.05x slower                                                       |
| async_tree_memoization    | 333 ms                                                      | 349 ms: 1.05x slower                                                        |
| 2to3                      | 213 ms                                                      | 223 ms: 1.05x slower                                                        |
| logging_simple            | 6.21 us                                                     | 6.53 us: 1.05x slower                                                       |
| dulwich_log               | 42.7 ms                                                     | 44.9 ms: 1.05x slower                                                       |
| deepcopy_memo             | 23.4 us                                                     | 24.7 us: 1.05x slower                                                       |
| pprint_safe_repr          | 508 ms                                                      | 536 ms: 1.06x slower                                                        |
| pprint_pformat            | 1.04 sec                                                    | 1.10 sec: 1.06x slower                                                      |
| sympy_expand              | 278 ms                                                      | 294 ms: 1.06x slower                                                        |
| xml_etree_iterparse       | 63.1 ms                                                     | 67.2 ms: 1.06x slower                                                       |
| async_tree_memoization_tg | 345 ms                                                      | 370 ms: 1.07x slower                                                        |
| pycparser                 | 673 ms                                                      | 724 ms: 1.07x slower                                                        |
| scimark_lu                | 57.5 ms                                                     | 61.9 ms: 1.08x slower                                                       |
| unpickle_pure_python      | 134 us                                                      | 146 us: 1.09x slower                                                        |
| meteor_contest            | 72.1 ms                                                     | 79.2 ms: 1.10x slower                                                       |
| regex_v8                  | 13.5 ms                                                     | 14.9 ms: 1.11x slower                                                       |
| mdp                       | 1.42 sec                                                    | 1.57 sec: 1.11x slower                                                      |
| regex_compile             | 87.2 ms                                                     | 96.9 ms: 1.11x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 17.7 ms: 1.11x slower                                                       |
| comprehensions            | 14.0 us                                                     | 15.6 us: 1.11x slower                                                       |
| chaos                     | 42.1 ms                                                     | 46.9 ms: 1.12x slower                                                       |
| float                     | 54.7 ms                                                     | 61.0 ms: 1.12x slower                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 52.2 ms: 1.12x slower                                                       |
| scimark_monte_carlo       | 43.0 ms                                                     | 48.5 ms: 1.13x slower                                                       |
| mako                      | 7.05 ms                                                     | 7.99 ms: 1.13x slower                                                       |
| pickle_list               | 2.88 us                                                     | 3.27 us: 1.13x slower                                                       |
| pyflate                   | 294 ms                                                      | 339 ms: 1.15x slower                                                        |
| go                        | 89.0 ms                                                     | 103 ms: 1.16x slower                                                        |
| coverage                  | 39.8 ms                                                     | 46.3 ms: 1.16x slower                                                       |
| scimark_fft               | 181 ms                                                      | 212 ms: 1.17x slower                                                        |
| nqueens                   | 61.7 ms                                                     | 72.2 ms: 1.17x slower                                                       |
| tomli_loads               | 1.38 sec                                                    | 1.62 sec: 1.18x slower                                                      |
| telco                     | 4.08 ms                                                     | 4.85 ms: 1.19x slower                                                       |
| nbody                     | 68.8 ms                                                     | 81.7 ms: 1.19x slower                                                       |
| fannkuch                  | 244 ms                                                      | 298 ms: 1.22x slower                                                        |
| deltablue                 | 2.12 ms                                                     | 2.92 ms: 1.37x slower                                                       |
| mypy2                     | 209 ms                                                      | 296 ms: 1.42x slower                                                        |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 3.69 ms: 1.47x slower                                                       |
| hexiom                    | 4.00 ms                                                     | 6.11 ms: 1.53x slower                                                       |
| Geometric mean            | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (7): unpickle, sqlglot_optimize, regex_dna, gc_traversal, create_gc_cycles, async_tree_cpu_io_mixed_tg, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
