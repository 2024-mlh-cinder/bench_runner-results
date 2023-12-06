
# Results vs. 3.12.0

- fork: mdboom
- ref: nogil_d595911
- machine: linux-x86_64
- commit hash: d595911
- commit date: 2023-04-27
- overall geometric mean: 1.09x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 303 ms: 1.06x slower                                                 |
| docutils       | 2.89 sec                                                     | 2.99 sec: 1.04x slower                                               |
| Geometric mean | (ref)                                                        | 1.05x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 78.5 ms                                                      | 65.5 ms: 1.20x faster                                                |
| pidigits       | 264 ms                                                       | 246 ms: 1.07x faster                                                 |
| nbody          | 94.1 ms                                                      | 102 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                        | 1.06x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 23.1 ms: 1.08x faster                                                |
| regex_effbot   | 3.47 ms                                                      | 3.30 ms: 1.05x faster                                                |
| regex_dna      | 241 ms                                                       | 233 ms: 1.03x faster                                                 |
| regex_compile  | 146 ms                                                       | 157 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                        | 1.02x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| xml_etree_parse      | 146 ms                                                       | 137 ms: 1.07x faster                                                 |
| pickle               | 10.1 us                                                      | 9.64 us: 1.05x faster                                                |
| xml_etree_generate   | 86.1 ms                                                      | 85.4 ms: 1.01x faster                                                |
| pickle_list          | 4.39 us                                                      | 4.46 us: 1.02x slower                                                |
| pickle_pure_python   | 323 us                                                       | 329 us: 1.02x slower                                                 |
| pickle_dict          | 31.7 us                                                      | 32.7 us: 1.03x slower                                                |
| unpickle_list        | 4.77 us                                                      | 5.01 us: 1.05x slower                                                |
| unpickle             | 14.8 us                                                      | 15.8 us: 1.07x slower                                                |
| xml_etree_process    | 58.3 ms                                                      | 62.8 ms: 1.08x slower                                                |
| json_dumps           | 10.2 ms                                                      | 11.4 ms: 1.12x slower                                                |
| unpickle_pure_python | 207 us                                                       | 233 us: 1.13x slower                                                 |
| tomli_loads          | 2.20 sec                                                     | 2.49 sec: 1.13x slower                                               |
| xml_etree_iterparse  | 103 ms                                                       | 126 ms: 1.22x slower                                                 |
| json_loads           | 24.3 us                                                      | 32.3 us: 1.33x slower                                                |
| Geometric mean       | (ref)                                                        | 1.07x slower                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.45 ms: 1.03x faster                                                |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                                |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 14.9 ms: 1.50x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_io            | 1.06 sec                                                     | 595 ms: 1.78x faster                                                 |
| async_tree_memoization   | 553 ms                                                       | 361 ms: 1.53x faster                                                 |
| async_tree_none          | 459 ms                                                       | 304 ms: 1.51x faster                                                 |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 529 ms: 1.33x faster                                                 |
| float                    | 78.5 ms                                                      | 65.5 ms: 1.20x faster                                                |
| async_generators         | 385 ms                                                       | 335 ms: 1.15x faster                                                 |
| gc_traversal             | 3.54 ms                                                      | 3.08 ms: 1.15x faster                                                |
| regex_v8                 | 25.0 ms                                                      | 23.1 ms: 1.08x faster                                                |
| pidigits                 | 264 ms                                                       | 246 ms: 1.07x faster                                                 |
| xml_etree_parse          | 146 ms                                                       | 137 ms: 1.07x faster                                                 |
| regex_effbot             | 3.47 ms                                                      | 3.30 ms: 1.05x faster                                                |
| pickle                   | 10.1 us                                                      | 9.64 us: 1.05x faster                                                |
| pycparser                | 1.27 sec                                                     | 1.22 sec: 1.04x faster                                               |
| regex_dna                | 241 ms                                                       | 233 ms: 1.03x faster                                                 |
| python_startup_no_site   | 8.70 ms                                                      | 8.45 ms: 1.03x faster                                                |
| python_startup           | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                                |
| unpack_sequence          | 53.3 ns                                                      | 52.4 ns: 1.02x faster                                                |
| xml_etree_generate       | 86.1 ms                                                      | 85.4 ms: 1.01x faster                                                |
| pickle_list              | 4.39 us                                                      | 4.46 us: 1.02x slower                                                |
| pickle_pure_python       | 323 us                                                       | 329 us: 1.02x slower                                                 |
| dulwich_log              | 65.3 ms                                                      | 67.2 ms: 1.03x slower                                                |
| pickle_dict              | 31.7 us                                                      | 32.7 us: 1.03x slower                                                |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.58 ms: 1.03x slower                                                |
| logging_silent           | 95.6 ns                                                      | 99.0 ns: 1.03x slower                                                |
| docutils                 | 2.89 sec                                                     | 2.99 sec: 1.04x slower                                               |
| sqlglot_optimize         | 57.8 ms                                                      | 59.9 ms: 1.04x slower                                                |
| telco                    | 6.96 ms                                                      | 7.29 ms: 1.05x slower                                                |
| asyncio_tcp              | 381 ms                                                       | 399 ms: 1.05x slower                                                 |
| unpickle_list            | 4.77 us                                                      | 5.01 us: 1.05x slower                                                |
| sqlglot_normalize        | 117 ms                                                       | 123 ms: 1.05x slower                                                 |
| 2to3                     | 287 ms                                                       | 303 ms: 1.06x slower                                                 |
| pprint_safe_repr         | 823 ms                                                       | 871 ms: 1.06x slower                                                 |
| scimark_sor              | 110 ms                                                       | 117 ms: 1.06x slower                                                 |
| sqlite_synth             | 2.70 us                                                      | 2.88 us: 1.07x slower                                                |
| unpickle                 | 14.8 us                                                      | 15.8 us: 1.07x slower                                                |
| deepcopy                 | 376 us                                                       | 403 us: 1.07x slower                                                 |
| scimark_lu               | 101 ms                                                       | 108 ms: 1.07x slower                                                 |
| scimark_fft              | 304 ms                                                       | 327 ms: 1.08x slower                                                 |
| regex_compile            | 146 ms                                                       | 157 ms: 1.08x slower                                                 |
| xml_etree_process        | 58.3 ms                                                      | 62.8 ms: 1.08x slower                                                |
| pyflate                  | 447 ms                                                       | 482 ms: 1.08x slower                                                 |
| pprint_pformat           | 1.67 sec                                                     | 1.81 sec: 1.08x slower                                               |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.70 sec: 1.08x slower                                               |
| nbody                    | 94.1 ms                                                      | 102 ms: 1.08x slower                                                 |
| deepcopy_reduce          | 3.46 us                                                      | 3.74 us: 1.08x slower                                                |
| logging_simple           | 6.73 us                                                      | 7.32 us: 1.09x slower                                                |
| coverage                 | 89.6 ms                                                      | 97.6 ms: 1.09x slower                                                |
| deepcopy_memo            | 37.4 us                                                      | 41.0 us: 1.09x slower                                                |
| crypto_pyaes             | 80.9 ms                                                      | 88.9 ms: 1.10x slower                                                |
| logging_format           | 7.37 us                                                      | 8.16 us: 1.11x slower                                                |
| nqueens                  | 90.1 ms                                                      | 99.8 ms: 1.11x slower                                                |
| mdp                      | 2.53 sec                                                     | 2.82 sec: 1.11x slower                                               |
| json_dumps               | 10.2 ms                                                      | 11.4 ms: 1.12x slower                                                |
| go                       | 150 ms                                                       | 169 ms: 1.12x slower                                                 |
| unpickle_pure_python     | 207 us                                                       | 233 us: 1.13x slower                                                 |
| tomli_loads              | 2.20 sec                                                     | 2.49 sec: 1.13x slower                                               |
| spectral_norm            | 91.6 ms                                                      | 105 ms: 1.14x slower                                                 |
| scimark_monte_carlo      | 72.4 ms                                                      | 82.9 ms: 1.15x slower                                                |
| sqlglot_transpile        | 1.80 ms                                                      | 2.08 ms: 1.15x slower                                                |
| create_gc_cycles         | 1.67 ms                                                      | 1.93 ms: 1.15x slower                                                |
| hexiom                   | 5.96 ms                                                      | 7.01 ms: 1.18x slower                                                |
| richards                 | 45.0 ms                                                      | 53.5 ms: 1.19x slower                                                |
| meteor_contest           | 128 ms                                                       | 153 ms: 1.20x slower                                                 |
| deltablue                | 3.29 ms                                                      | 4.00 ms: 1.22x slower                                                |
| mypy2                    | 368 ms                                                       | 449 ms: 1.22x slower                                                 |
| xml_etree_iterparse      | 103 ms                                                       | 126 ms: 1.22x slower                                                 |
| coroutines               | 23.0 ms                                                      | 28.1 ms: 1.22x slower                                                |
| json                     | 5.14 ms                                                      | 6.28 ms: 1.22x slower                                                |
| sqlglot_parse            | 1.40 ms                                                      | 1.73 ms: 1.23x slower                                                |
| chaos                    | 62.9 ms                                                      | 77.8 ms: 1.24x slower                                                |
| raytrace                 | 302 ms                                                       | 376 ms: 1.25x slower                                                 |
| fannkuch                 | 350 ms                                                       | 447 ms: 1.28x slower                                                 |
| richards_super           | 51.7 ms                                                      | 66.5 ms: 1.29x slower                                                |
| json_loads               | 24.3 us                                                      | 32.3 us: 1.33x slower                                                |
| comprehensions           | 21.9 us                                                      | 29.6 us: 1.35x slower                                                |
| bench_mp_pool            | 5.34 ms                                                      | 7.77 ms: 1.45x slower                                                |
| mako                     | 9.94 ms                                                      | 14.9 ms: 1.50x slower                                                |
| generators               | 36.7 ms                                                      | 62.3 ms: 1.70x slower                                                |
| bench_thread_pool        | 980 us                                                       | 2.03 ms: 2.07x slower                                                |
| typing_runtime_protocols | 151 us                                                       | 575 us: 3.80x slower                                                 |
| Geometric mean           | (ref)                                                        | 1.09x slower                                                         |

Benchmark hidden because not significant (1): pathlib
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: dask, tornado_http
Ignored benchmarks (10) of results/bm-20230427-3.12.0a4-d595911/bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911.json: chameleon, django_template, genshi_text, genshi_xml, html5lib, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
