
# Results vs. 3.12.0

- fork: mdboom
- ref: match_nogil_gc
- machine: linux-x86_64
- commit hash: 0fd3163
- commit date: 2023-05-31
- overall geometric mean: 1.06x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 245 ms: 1.09x faster                                            |
| docutils       | 2.70 sec                                               | 2.15 sec: 1.26x faster                                          |
| Geometric mean | (ref)                                                  | 1.17x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 80.7 ms                                                | 60.7 ms: 1.33x faster                                           |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                            |
| nbody          | 88.8 ms                                                | 92.3 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                  | 1.08x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 131 ms: 1.09x faster                                            |
| regex_effbot   | 3.55 ms                                                | 3.46 ms: 1.03x faster                                           |
| regex_v8       | 22.3 ms                                                | 22.1 ms: 1.01x faster                                           |
| regex_dna      | 209 ms                                                 | 210 ms: 1.01x slower                                            |
| Geometric mean | (ref)                                                  | 1.03x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| xml_etree_iterparse  | 104 ms                                                 | 80.9 ms: 1.28x faster                                           |
| xml_etree_parse      | 154 ms                                                 | 122 ms: 1.26x faster                                            |
| xml_etree_generate   | 84.8 ms                                                | 73.4 ms: 1.16x faster                                           |
| unpickle             | 15.0 us                                                | 13.0 us: 1.15x faster                                           |
| pickle_list          | 4.62 us                                                | 4.05 us: 1.14x faster                                           |
| xml_etree_process    | 58.6 ms                                                | 51.6 ms: 1.13x faster                                           |
| tomli_loads          | 2.22 sec                                               | 1.98 sec: 1.12x faster                                          |
| unpickle_pure_python | 218 us                                                 | 198 us: 1.10x faster                                            |
| pickle_pure_python   | 309 us                                                 | 282 us: 1.09x faster                                            |
| json_loads           | 25.2 us                                                | 23.7 us: 1.07x faster                                           |
| pickle               | 10.6 us                                                | 10.2 us: 1.04x faster                                           |
| json_dumps           | 9.85 ms                                                | 9.55 ms: 1.03x faster                                           |
| pickle_dict          | 31.6 us                                                | 31.2 us: 1.01x faster                                           |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                    |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 5.93 ms: 1.16x faster                                           |
| python_startup         | 9.47 ms                                                | 8.24 ms: 1.15x faster                                           |
| Geometric mean         | (ref)                                                  | 1.16x faster                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 9.69 ms: 1.11x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_io            | 1.16 sec                                               | 534 ms: 2.17x faster                                            |
| async_tree_memoization   | 573 ms                                                 | 315 ms: 1.82x faster                                            |
| async_tree_none          | 469 ms                                                 | 260 ms: 1.80x faster                                            |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 469 ms: 1.52x faster                                            |
| float                    | 80.7 ms                                                | 60.7 ms: 1.33x faster                                           |
| async_generators         | 440 ms                                                 | 338 ms: 1.30x faster                                            |
| xml_etree_iterparse      | 104 ms                                                 | 80.9 ms: 1.28x faster                                           |
| xml_etree_parse          | 154 ms                                                 | 122 ms: 1.26x faster                                            |
| docutils                 | 2.70 sec                                               | 2.15 sec: 1.26x faster                                          |
| scimark_sor              | 125 ms                                                 | 106 ms: 1.17x faster                                            |
| python_startup_no_site   | 6.90 ms                                                | 5.93 ms: 1.16x faster                                           |
| scimark_fft              | 358 ms                                                 | 309 ms: 1.16x faster                                            |
| xml_etree_generate       | 84.8 ms                                                | 73.4 ms: 1.16x faster                                           |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.12 ms: 1.15x faster                                           |
| python_startup           | 9.47 ms                                                | 8.24 ms: 1.15x faster                                           |
| unpickle                 | 15.0 us                                                | 13.0 us: 1.15x faster                                           |
| dask                     | 365 ms                                                 | 317 ms: 1.15x faster                                            |
| pickle_list              | 4.62 us                                                | 4.05 us: 1.14x faster                                           |
| gc_traversal             | 3.84 ms                                                | 3.38 ms: 1.14x faster                                           |
| xml_etree_process        | 58.6 ms                                                | 51.6 ms: 1.13x faster                                           |
| deltablue                | 3.52 ms                                                | 3.11 ms: 1.13x faster                                           |
| spectral_norm            | 106 ms                                                 | 94.7 ms: 1.12x faster                                           |
| tomli_loads              | 2.22 sec                                               | 1.98 sec: 1.12x faster                                          |
| pyflate                  | 450 ms                                                 | 403 ms: 1.12x faster                                            |
| mypy2                    | 344 ms                                                 | 309 ms: 1.11x faster                                            |
| logging_silent           | 99.1 ns                                                | 89.6 ns: 1.11x faster                                           |
| mako                     | 10.7 ms                                                | 9.69 ms: 1.11x faster                                           |
| deepcopy_memo            | 37.4 us                                                | 33.8 us: 1.11x faster                                           |
| unpickle_pure_python     | 218 us                                                 | 198 us: 1.10x faster                                            |
| pickle_pure_python       | 309 us                                                 | 282 us: 1.09x faster                                            |
| regex_compile            | 144 ms                                                 | 131 ms: 1.09x faster                                            |
| 2to3                     | 268 ms                                                 | 245 ms: 1.09x faster                                            |
| scimark_monte_carlo      | 71.0 ms                                                | 65.2 ms: 1.09x faster                                           |
| pycparser                | 1.15 sec                                               | 1.06 sec: 1.09x faster                                          |
| pprint_safe_repr         | 735 ms                                                 | 676 ms: 1.09x faster                                            |
| scimark_lu               | 114 ms                                                 | 105 ms: 1.08x faster                                            |
| pprint_pformat           | 1.50 sec                                               | 1.39 sec: 1.08x faster                                          |
| logging_format           | 6.90 us                                                | 6.44 us: 1.07x faster                                           |
| deepcopy                 | 355 us                                                 | 332 us: 1.07x faster                                            |
| dulwich_log              | 67.9 ms                                                | 63.5 ms: 1.07x faster                                           |
| json_loads               | 25.2 us                                                | 23.7 us: 1.07x faster                                           |
| logging_simple           | 6.18 us                                                | 5.80 us: 1.07x faster                                           |
| deepcopy_reduce          | 3.14 us                                                | 2.97 us: 1.06x faster                                           |
| telco                    | 6.87 ms                                                | 6.52 ms: 1.05x faster                                           |
| fannkuch                 | 387 ms                                                 | 368 ms: 1.05x faster                                            |
| crypto_pyaes             | 77.2 ms                                                | 73.7 ms: 1.05x faster                                           |
| nqueens                  | 81.1 ms                                                | 77.6 ms: 1.05x faster                                           |
| bench_thread_pool        | 827 us                                                 | 792 us: 1.04x faster                                            |
| pickle                   | 10.6 us                                                | 10.2 us: 1.04x faster                                           |
| create_gc_cycles         | 1.52 ms                                                | 1.46 ms: 1.04x faster                                           |
| json                     | 4.77 ms                                                | 4.59 ms: 1.04x faster                                           |
| mdp                      | 2.57 sec                                               | 2.48 sec: 1.04x faster                                          |
| sqlglot_optimize         | 53.3 ms                                                | 51.6 ms: 1.03x faster                                           |
| sqlite_synth             | 2.76 us                                                | 2.67 us: 1.03x faster                                           |
| json_dumps               | 9.85 ms                                                | 9.55 ms: 1.03x faster                                           |
| asyncio_tcp              | 526 ms                                                 | 511 ms: 1.03x faster                                            |
| raytrace                 | 294 ms                                                 | 286 ms: 1.03x faster                                            |
| unpack_sequence          | 44.8 ns                                                | 43.6 ns: 1.03x faster                                           |
| regex_effbot             | 3.55 ms                                                | 3.46 ms: 1.03x faster                                           |
| pathlib                  | 18.5 ms                                                | 18.2 ms: 1.02x faster                                           |
| richards                 | 43.2 ms                                                | 42.5 ms: 1.02x faster                                           |
| pickle_dict              | 31.6 us                                                | 31.2 us: 1.01x faster                                           |
| regex_v8                 | 22.3 ms                                                | 22.1 ms: 1.01x faster                                           |
| hexiom                   | 6.12 ms                                                | 6.06 ms: 1.01x faster                                           |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                          |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                            |
| regex_dna                | 209 ms                                                 | 210 ms: 1.01x slower                                            |
| go                       | 136 ms                                                 | 137 ms: 1.01x slower                                            |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                            |
| sqlglot_transpile        | 1.64 ms                                                | 1.67 ms: 1.02x slower                                           |
| nbody                    | 88.8 ms                                                | 92.3 ms: 1.04x slower                                           |
| meteor_contest           | 105 ms                                                 | 109 ms: 1.04x slower                                            |
| sqlglot_parse            | 1.32 ms                                                | 1.38 ms: 1.04x slower                                           |
| coverage                 | 94.2 ms                                                | 99.2 ms: 1.05x slower                                           |
| richards_super           | 49.0 ms                                                | 52.9 ms: 1.08x slower                                           |
| chaos                    | 63.5 ms                                                | 68.8 ms: 1.08x slower                                           |
| coroutines               | 22.4 ms                                                | 26.1 ms: 1.16x slower                                           |
| comprehensions           | 20.4 us                                                | 23.9 us: 1.17x slower                                           |
| generators               | 31.1 ms                                                | 79.1 ms: 2.54x slower                                           |
| typing_runtime_protocols | 146 us                                                 | 463 us: 3.18x slower                                            |
| Geometric mean           | (ref)                                                  | 1.06x faster                                                    |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle_list
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
Ignored benchmarks (11) of results/bm-20230531-3.12.0a4-0fd3163/bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163.json: chameleon, django_template, djangocms, genshi_text, genshi_xml, html5lib, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.05x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
