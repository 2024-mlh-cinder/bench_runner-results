
# Results vs. 3.10.4

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 2b8766e
- commit date: 2023-09-13
- overall geometric mean: 1.31x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.60 sec: 1.22x faster                                                          |
| tornado_http   | 127 ms                                                 | 95.1 ms: 1.34x faster                                                           |
| Geometric mean | (ref)                                                  | 1.28x faster                                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 88.7 ms: 1.60x faster                                                           |
| float          | 111 ms                                                 | 80.2 ms: 1.38x faster                                                           |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                            |
| Geometric mean | (ref)                                                  | 1.31x faster                                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 136 ms: 1.30x faster                                                            |
| regex_v8       | 25.0 ms                                                | 23.6 ms: 1.06x faster                                                           |
| regex_dna      | 222 ms                                                 | 209 ms: 1.06x faster                                                            |
| regex_effbot   | 3.23 ms                                                | 3.43 ms: 1.06x slower                                                           |
| Geometric mean | (ref)                                                  | 1.08x faster                                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 303 us: 1.50x faster                                                            |
| tomli_loads          | 2.92 sec                                               | 2.08 sec: 1.41x faster                                                          |
| json_dumps           | 13.5 ms                                                | 9.76 ms: 1.39x faster                                                           |
| unpickle_pure_python | 300 us                                                 | 218 us: 1.38x faster                                                            |
| xml_etree_process    | 74.9 ms                                                | 57.4 ms: 1.31x faster                                                           |
| json_loads           | 28.8 us                                                | 25.2 us: 1.14x faster                                                           |
| xml_etree_generate   | 94.2 ms                                                | 83.9 ms: 1.12x faster                                                           |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                            |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                                            |
| unpickle_list        | 4.82 us                                                | 4.74 us: 1.02x faster                                                           |
| unpickle             | 14.1 us                                                | 14.0 us: 1.01x faster                                                           |
| pickle               | 10.3 us                                                | 10.7 us: 1.04x slower                                                           |
| pickle_dict          | 27.3 us                                                | 31.4 us: 1.15x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                                    |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.41x faster                                                           |
| python_startup_no_site | 5.82 ms                                                | 6.84 ms: 1.18x slower                                                           |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.37x faster                                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 144 us: 3.55x faster                                                            |
| generators               | 76.8 ms                                                | 29.3 ms: 2.62x faster                                                           |
| deltablue                | 7.42 ms                                                | 3.27 ms: 2.27x faster                                                           |
| asyncio_tcp              | 925 ms                                                 | 488 ms: 1.90x faster                                                            |
| chaos                    | 106 ms                                                 | 60.4 ms: 1.76x faster                                                           |
| logging_silent           | 175 ns                                                 | 102 ns: 1.71x faster                                                            |
| raytrace                 | 464 ms                                                 | 272 ms: 1.71x faster                                                            |
| crypto_pyaes             | 118 ms                                                 | 69.4 ms: 1.71x faster                                                           |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                                          |
| async_tree_none          | 717 ms                                                 | 435 ms: 1.65x faster                                                            |
| richards_super           | 90.7 ms                                                | 55.3 ms: 1.64x faster                                                           |
| scimark_monte_carlo      | 108 ms                                                 | 66.2 ms: 1.63x faster                                                           |
| go                       | 229 ms                                                 | 141 ms: 1.62x faster                                                            |
| scimark_sor              | 197 ms                                                 | 121 ms: 1.62x faster                                                            |
| sqlglot_parse            | 2.06 ms                                                | 1.27 ms: 1.62x faster                                                           |
| nbody                    | 142 ms                                                 | 88.7 ms: 1.60x faster                                                           |
| hexiom                   | 9.53 ms                                                | 6.05 ms: 1.57x faster                                                           |
| sqlglot_transpile        | 2.45 ms                                                | 1.59 ms: 1.54x faster                                                           |
| richards                 | 74.9 ms                                                | 48.6 ms: 1.54x faster                                                           |
| unpack_sequence          | 64.7 ns                                                | 42.1 ns: 1.54x faster                                                           |
| async_tree_memoization   | 854 ms                                                 | 561 ms: 1.52x faster                                                            |
| async_tree_io            | 1.77 sec                                               | 1.18 sec: 1.50x faster                                                          |
| pickle_pure_python       | 455 us                                                 | 303 us: 1.50x faster                                                            |
| pyflate                  | 673 ms                                                 | 457 ms: 1.47x faster                                                            |
| scimark_lu               | 163 ms                                                 | 111 ms: 1.47x faster                                                            |
| coroutines               | 31.8 ms                                                | 21.9 ms: 1.45x faster                                                           |
| deepcopy_memo            | 52.3 us                                                | 37.2 us: 1.41x faster                                                           |
| spectral_norm            | 150 ms                                                 | 107 ms: 1.41x faster                                                            |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.41x faster                                                           |
| tomli_loads              | 2.92 sec                                               | 2.08 sec: 1.41x faster                                                          |
| json_dumps               | 13.5 ms                                                | 9.76 ms: 1.39x faster                                                           |
| float                    | 111 ms                                                 | 80.2 ms: 1.38x faster                                                           |
| unpickle_pure_python     | 300 us                                                 | 218 us: 1.38x faster                                                            |
| logging_format           | 8.91 us                                                | 6.49 us: 1.37x faster                                                           |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.37x faster                                                           |
| logging_simple           | 8.07 us                                                | 5.92 us: 1.36x faster                                                           |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 705 ms: 1.35x faster                                                            |
| pprint_pformat           | 1.99 sec                                               | 1.47 sec: 1.35x faster                                                          |
| tornado_http             | 127 ms                                                 | 95.1 ms: 1.34x faster                                                           |
| pprint_safe_repr         | 955 ms                                                 | 724 ms: 1.32x faster                                                            |
| comprehensions           | 26.8 us                                                | 20.5 us: 1.31x faster                                                           |
| xml_etree_process        | 74.9 ms                                                | 57.4 ms: 1.31x faster                                                           |
| regex_compile            | 177 ms                                                 | 136 ms: 1.30x faster                                                            |
| sqlglot_normalize        | 135 ms                                                 | 104 ms: 1.30x faster                                                            |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.29x faster                                                          |
| deepcopy                 | 442 us                                                 | 347 us: 1.27x faster                                                            |
| mypy2                    | 428 ms                                                 | 338 ms: 1.27x faster                                                            |
| sqlglot_optimize         | 65.3 ms                                                | 52.4 ms: 1.25x faster                                                           |
| fannkuch                 | 486 ms                                                 | 390 ms: 1.25x faster                                                            |
| nqueens                  | 100 ms                                                 | 80.4 ms: 1.24x faster                                                           |
| deepcopy_reduce          | 3.82 us                                                | 3.14 us: 1.22x faster                                                           |
| docutils                 | 3.17 sec                                               | 2.60 sec: 1.22x faster                                                          |
| scimark_fft              | 424 ms                                                 | 361 ms: 1.17x faster                                                            |
| bench_thread_pool        | 947 us                                                 | 808 us: 1.17x faster                                                            |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.69 ms: 1.16x faster                                                           |
| json                     | 5.42 ms                                                | 4.73 ms: 1.14x faster                                                           |
| json_loads               | 28.8 us                                                | 25.2 us: 1.14x faster                                                           |
| dulwich_log              | 75.9 ms                                                | 66.6 ms: 1.14x faster                                                           |
| xml_etree_generate       | 94.2 ms                                                | 83.9 ms: 1.12x faster                                                           |
| pathlib                  | 20.0 ms                                                | 18.3 ms: 1.09x faster                                                           |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                            |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.09x faster                                                            |
| create_gc_cycles         | 1.67 ms                                                | 1.54 ms: 1.08x faster                                                           |
| sqlite_synth             | 2.93 us                                                | 2.71 us: 1.08x faster                                                           |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                                            |
| regex_v8                 | 25.0 ms                                                | 23.6 ms: 1.06x faster                                                           |
| regex_dna                | 222 ms                                                 | 209 ms: 1.06x faster                                                            |
| mdp                      | 2.82 sec                                               | 2.67 sec: 1.06x faster                                                          |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                                            |
| unpickle_list            | 4.82 us                                                | 4.74 us: 1.02x faster                                                           |
| unpickle                 | 14.1 us                                                | 14.0 us: 1.01x faster                                                           |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                           |
| pickle                   | 10.3 us                                                | 10.7 us: 1.04x slower                                                           |
| async_generators         | 425 ms                                                 | 442 ms: 1.04x slower                                                            |
| regex_effbot             | 3.23 ms                                                | 3.43 ms: 1.06x slower                                                           |
| pickle_dict              | 27.3 us                                                | 31.4 us: 1.15x slower                                                           |
| coverage                 | 72.8 ms                                                | 85.0 ms: 1.17x slower                                                           |
| python_startup_no_site   | 5.82 ms                                                | 6.84 ms: 1.18x slower                                                           |
| telco                    | 6.54 ms                                                | 7.97 ms: 1.22x slower                                                           |
| dask                     | 423 ms                                                 | 525 ms: 1.24x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.31x faster                                                                    |

Benchmark hidden because not significant (2): pickle_list, bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.24x
