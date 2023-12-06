
# Results vs. 3.12.0

- fork: mdboom
- ref: nogil_d595911
- machine: linux-x86_64
- commit hash: d595911
- commit date: 2023-04-27
- overall geometric mean: 1.07x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3      | 268 ms                                                 | 287 ms: 1.07x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 80.7 ms                                                | 67.0 ms: 1.21x faster                                          |
| nbody          | 88.8 ms                                                | 103 ms: 1.16x slower                                           |
| Geometric mean | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_v8       | 22.3 ms                                                | 22.0 ms: 1.02x faster                                          |
| regex_effbot   | 3.55 ms                                                | 3.52 ms: 1.01x faster                                          |
| regex_dna      | 209 ms                                                 | 219 ms: 1.05x slower                                           |
| regex_compile  | 144 ms                                                 | 151 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| xml_etree_parse      | 154 ms                                                 | 133 ms: 1.15x faster                                           |
| pickle               | 10.6 us                                                | 9.82 us: 1.08x faster                                          |
| pickle_dict          | 31.6 us                                                | 29.9 us: 1.06x faster                                          |
| pickle_list          | 4.62 us                                                | 4.47 us: 1.03x faster                                          |
| xml_etree_generate   | 84.8 ms                                                | 83.3 ms: 1.02x faster                                          |
| pickle_pure_python   | 309 us                                                 | 315 us: 1.02x slower                                           |
| unpickle             | 15.0 us                                                | 15.3 us: 1.02x slower                                          |
| xml_etree_process    | 58.6 ms                                                | 60.5 ms: 1.03x slower                                          |
| json_dumps           | 9.85 ms                                                | 10.5 ms: 1.06x slower                                          |
| tomli_loads          | 2.22 sec                                               | 2.39 sec: 1.08x slower                                         |
| unpickle_list        | 4.95 us                                                | 5.35 us: 1.08x slower                                          |
| unpickle_pure_python | 218 us                                                 | 237 us: 1.09x slower                                           |
| json_loads           | 25.2 us                                                | 28.1 us: 1.11x slower                                          |
| xml_etree_iterparse  | 104 ms                                                 | 121 ms: 1.16x slower                                           |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.70 ms: 1.03x faster                                          |
| python_startup         | 9.47 ms                                                | 9.33 ms: 1.02x faster                                          |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 13.6 ms: 1.27x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_io            | 1.16 sec                                               | 580 ms: 1.99x faster                                           |
| async_tree_none          | 469 ms                                                 | 289 ms: 1.62x faster                                           |
| async_tree_memoization   | 573 ms                                                 | 362 ms: 1.58x faster                                           |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 514 ms: 1.39x faster                                           |
| gc_traversal             | 3.84 ms                                                | 3.11 ms: 1.24x faster                                          |
| float                    | 80.7 ms                                                | 67.0 ms: 1.21x faster                                          |
| async_generators         | 440 ms                                                 | 369 ms: 1.19x faster                                           |
| xml_etree_parse          | 154 ms                                                 | 133 ms: 1.15x faster                                           |
| pickle                   | 10.6 us                                                | 9.82 us: 1.08x faster                                          |
| pickle_dict              | 31.6 us                                                | 29.9 us: 1.06x faster                                          |
| pickle_list              | 4.62 us                                                | 4.47 us: 1.03x faster                                          |
| python_startup_no_site   | 6.90 ms                                                | 6.70 ms: 1.03x faster                                          |
| xml_etree_generate       | 84.8 ms                                                | 83.3 ms: 1.02x faster                                          |
| python_startup           | 9.47 ms                                                | 9.33 ms: 1.02x faster                                          |
| regex_v8                 | 22.3 ms                                                | 22.0 ms: 1.02x faster                                          |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                          |
| telco                    | 6.87 ms                                                | 6.81 ms: 1.01x faster                                          |
| regex_effbot             | 3.55 ms                                                | 3.52 ms: 1.01x faster                                          |
| scimark_sor              | 125 ms                                                 | 125 ms: 1.01x slower                                           |
| asyncio_tcp              | 526 ms                                                 | 535 ms: 1.02x slower                                           |
| pickle_pure_python       | 309 us                                                 | 315 us: 1.02x slower                                           |
| unpickle                 | 15.0 us                                                | 15.3 us: 1.02x slower                                          |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.85 sec: 1.03x slower                                         |
| xml_etree_process        | 58.6 ms                                                | 60.5 ms: 1.03x slower                                          |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.91 ms: 1.03x slower                                          |
| sqlglot_optimize         | 53.3 ms                                                | 55.4 ms: 1.04x slower                                          |
| deltablue                | 3.52 ms                                                | 3.67 ms: 1.04x slower                                          |
| scimark_fft              | 358 ms                                                 | 374 ms: 1.04x slower                                           |
| regex_dna                | 209 ms                                                 | 219 ms: 1.05x slower                                           |
| deepcopy                 | 355 us                                                 | 373 us: 1.05x slower                                           |
| pprint_safe_repr         | 735 ms                                                 | 772 ms: 1.05x slower                                           |
| regex_compile            | 144 ms                                                 | 151 ms: 1.05x slower                                           |
| pyflate                  | 450 ms                                                 | 475 ms: 1.05x slower                                           |
| pathlib                  | 18.5 ms                                                | 19.5 ms: 1.06x slower                                          |
| spectral_norm            | 106 ms                                                 | 112 ms: 1.06x slower                                           |
| json                     | 4.77 ms                                                | 5.05 ms: 1.06x slower                                          |
| deepcopy_reduce          | 3.14 us                                                | 3.32 us: 1.06x slower                                          |
| crypto_pyaes             | 77.2 ms                                                | 81.9 ms: 1.06x slower                                          |
| sqlglot_normalize        | 107 ms                                                 | 114 ms: 1.06x slower                                           |
| json_dumps               | 9.85 ms                                                | 10.5 ms: 1.06x slower                                          |
| pprint_pformat           | 1.50 sec                                               | 1.60 sec: 1.06x slower                                         |
| nqueens                  | 81.1 ms                                                | 86.4 ms: 1.07x slower                                          |
| deepcopy_memo            | 37.4 us                                                | 40.1 us: 1.07x slower                                          |
| 2to3                     | 268 ms                                                 | 287 ms: 1.07x slower                                           |
| scimark_monte_carlo      | 71.0 ms                                                | 76.1 ms: 1.07x slower                                          |
| tomli_loads              | 2.22 sec                                               | 2.39 sec: 1.08x slower                                         |
| unpickle_list            | 4.95 us                                                | 5.35 us: 1.08x slower                                          |
| unpickle_pure_python     | 218 us                                                 | 237 us: 1.09x slower                                           |
| go                       | 136 ms                                                 | 147 ms: 1.09x slower                                           |
| scimark_lu               | 114 ms                                                 | 125 ms: 1.10x slower                                           |
| logging_silent           | 99.1 ns                                                | 109 ns: 1.10x slower                                           |
| json_loads               | 25.2 us                                                | 28.1 us: 1.11x slower                                          |
| logging_simple           | 6.18 us                                                | 6.89 us: 1.12x slower                                          |
| fannkuch                 | 387 ms                                                 | 433 ms: 1.12x slower                                           |
| coroutines               | 22.4 ms                                                | 25.1 ms: 1.12x slower                                          |
| hexiom                   | 6.12 ms                                                | 6.85 ms: 1.12x slower                                          |
| logging_format           | 6.90 us                                                | 7.75 us: 1.12x slower                                          |
| richards                 | 43.2 ms                                                | 48.8 ms: 1.13x slower                                          |
| mdp                      | 2.57 sec                                               | 2.94 sec: 1.15x slower                                         |
| unpack_sequence          | 44.8 ns                                                | 51.8 ns: 1.16x slower                                          |
| xml_etree_iterparse      | 104 ms                                                 | 121 ms: 1.16x slower                                           |
| nbody                    | 88.8 ms                                                | 103 ms: 1.16x slower                                           |
| raytrace                 | 294 ms                                                 | 346 ms: 1.18x slower                                           |
| sqlglot_transpile        | 1.64 ms                                                | 1.97 ms: 1.20x slower                                          |
| meteor_contest           | 105 ms                                                 | 126 ms: 1.20x slower                                           |
| chaos                    | 63.5 ms                                                | 76.6 ms: 1.21x slower                                          |
| sqlite_synth             | 2.76 us                                                | 3.33 us: 1.21x slower                                          |
| richards_super           | 49.0 ms                                                | 60.2 ms: 1.23x slower                                          |
| mako                     | 10.7 ms                                                | 13.6 ms: 1.27x slower                                          |
| sqlglot_parse            | 1.32 ms                                                | 1.67 ms: 1.27x slower                                          |
| mypy2                    | 344 ms                                                 | 445 ms: 1.30x slower                                           |
| comprehensions           | 20.4 us                                                | 26.8 us: 1.31x slower                                          |
| bench_thread_pool        | 827 us                                                 | 1.64 ms: 1.99x slower                                          |
| generators               | 31.1 ms                                                | 78.3 ms: 2.52x slower                                          |
| typing_runtime_protocols | 146 us                                                 | 535 us: 3.67x slower                                           |
| Geometric mean           | (ref)                                                  | 1.07x slower                                                   |

Benchmark hidden because not significant (3): pycparser, pidigits, bench_mp_pool
Ignored benchmarks (7) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: coverage, dask, docutils, dulwich_log, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
Ignored benchmarks (8) of results/bm-20230427-3.12.0a4-d595911/bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911.json: chameleon, genshi_text, genshi_xml, html5lib, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
