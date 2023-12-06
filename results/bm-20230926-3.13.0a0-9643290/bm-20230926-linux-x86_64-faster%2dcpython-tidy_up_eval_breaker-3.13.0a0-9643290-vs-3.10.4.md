
# Results vs. 3.10.4

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 9643290
- commit date: 2023-09-26
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.60 sec: 1.22x faster                                                          |
| tornado_http   | 127 ms                                                 | 95.9 ms: 1.33x faster                                                           |
| Geometric mean | (ref)                                                  | 1.27x faster                                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.7 ms: 1.54x faster                                                           |
| float          | 111 ms                                                 | 80.0 ms: 1.38x faster                                                           |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                            |
| Geometric mean | (ref)                                                  | 1.29x faster                                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 135 ms: 1.31x faster                                                            |
| regex_v8       | 25.0 ms                                                | 23.3 ms: 1.08x faster                                                           |
| regex_dna      | 222 ms                                                 | 215 ms: 1.03x faster                                                            |
| regex_effbot   | 3.23 ms                                                | 3.57 ms: 1.11x slower                                                           |
| Geometric mean | (ref)                                                  | 1.07x faster                                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 294 us: 1.55x faster                                                            |
| unpickle_pure_python | 300 us                                                 | 214 us: 1.40x faster                                                            |
| tomli_loads          | 2.92 sec                                               | 2.12 sec: 1.38x faster                                                          |
| json_dumps           | 13.5 ms                                                | 9.94 ms: 1.36x faster                                                           |
| xml_etree_process    | 74.9 ms                                                | 57.1 ms: 1.31x faster                                                           |
| xml_etree_generate   | 94.2 ms                                                | 82.1 ms: 1.15x faster                                                           |
| json_loads           | 28.8 us                                                | 25.4 us: 1.13x faster                                                           |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                            |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                                            |
| pickle_list          | 4.56 us                                                | 4.75 us: 1.04x slower                                                           |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                                           |
| unpickle             | 14.1 us                                                | 15.3 us: 1.08x slower                                                           |
| pickle_dict          | 27.3 us                                                | 32.4 us: 1.19x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                                    |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.41x faster                                                           |
| python_startup_no_site | 5.82 ms                                                | 6.83 ms: 1.17x slower                                                           |
| Geometric mean         | (ref)                                                  | 1.10x faster                                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.6 ms: 1.39x faster                                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 143 us: 3.56x faster                                                            |
| generators               | 76.8 ms                                                | 28.6 ms: 2.69x faster                                                           |
| deltablue                | 7.42 ms                                                | 3.27 ms: 2.27x faster                                                           |
| asyncio_tcp              | 925 ms                                                 | 502 ms: 1.84x faster                                                            |
| chaos                    | 106 ms                                                 | 60.4 ms: 1.76x faster                                                           |
| logging_silent           | 175 ns                                                 | 101 ns: 1.73x faster                                                            |
| raytrace                 | 464 ms                                                 | 271 ms: 1.71x faster                                                            |
| richards_super           | 90.7 ms                                                | 53.6 ms: 1.69x faster                                                           |
| crypto_pyaes             | 118 ms                                                 | 70.1 ms: 1.69x faster                                                           |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                                          |
| go                       | 229 ms                                                 | 139 ms: 1.65x faster                                                            |
| async_tree_none          | 717 ms                                                 | 436 ms: 1.64x faster                                                            |
| sqlglot_parse            | 2.06 ms                                                | 1.26 ms: 1.64x faster                                                           |
| scimark_sor              | 197 ms                                                 | 121 ms: 1.63x faster                                                            |
| scimark_monte_carlo      | 108 ms                                                 | 66.7 ms: 1.62x faster                                                           |
| hexiom                   | 9.53 ms                                                | 6.02 ms: 1.58x faster                                                           |
| richards                 | 74.9 ms                                                | 47.5 ms: 1.58x faster                                                           |
| sqlglot_transpile        | 2.45 ms                                                | 1.57 ms: 1.56x faster                                                           |
| pickle_pure_python       | 455 us                                                 | 294 us: 1.55x faster                                                            |
| nbody                    | 142 ms                                                 | 91.7 ms: 1.54x faster                                                           |
| async_tree_memoization   | 854 ms                                                 | 562 ms: 1.52x faster                                                            |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                          |
| scimark_lu               | 163 ms                                                 | 111 ms: 1.47x faster                                                            |
| pyflate                  | 673 ms                                                 | 461 ms: 1.46x faster                                                            |
| coroutines               | 31.8 ms                                                | 22.2 ms: 1.43x faster                                                           |
| deepcopy_memo            | 52.3 us                                                | 36.7 us: 1.42x faster                                                           |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.41x faster                                                           |
| unpickle_pure_python     | 300 us                                                 | 214 us: 1.40x faster                                                            |
| spectral_norm            | 150 ms                                                 | 107 ms: 1.40x faster                                                            |
| mako                     | 14.8 ms                                                | 10.6 ms: 1.39x faster                                                           |
| float                    | 111 ms                                                 | 80.0 ms: 1.38x faster                                                           |
| tomli_loads              | 2.92 sec                                               | 2.12 sec: 1.38x faster                                                          |
| logging_simple           | 8.07 us                                                | 5.86 us: 1.38x faster                                                           |
| logging_format           | 8.91 us                                                | 6.52 us: 1.37x faster                                                           |
| json_dumps               | 13.5 ms                                                | 9.94 ms: 1.36x faster                                                           |
| pprint_pformat           | 1.99 sec                                               | 1.46 sec: 1.36x faster                                                          |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 702 ms: 1.35x faster                                                            |
| pprint_safe_repr         | 955 ms                                                 | 715 ms: 1.34x faster                                                            |
| tornado_http             | 127 ms                                                 | 95.9 ms: 1.33x faster                                                           |
| comprehensions           | 26.8 us                                                | 20.4 us: 1.31x faster                                                           |
| xml_etree_process        | 74.9 ms                                                | 57.1 ms: 1.31x faster                                                           |
| regex_compile            | 177 ms                                                 | 135 ms: 1.31x faster                                                            |
| sqlglot_normalize        | 135 ms                                                 | 104 ms: 1.30x faster                                                            |
| unpack_sequence          | 64.7 ns                                                | 50.5 ns: 1.28x faster                                                           |
| deepcopy                 | 442 us                                                 | 346 us: 1.28x faster                                                            |
| pycparser                | 1.50 sec                                               | 1.18 sec: 1.27x faster                                                          |
| mypy2                    | 428 ms                                                 | 339 ms: 1.26x faster                                                            |
| fannkuch                 | 486 ms                                                 | 386 ms: 1.26x faster                                                            |
| sqlglot_optimize         | 65.3 ms                                                | 52.3 ms: 1.25x faster                                                           |
| nqueens                  | 100 ms                                                 | 80.1 ms: 1.25x faster                                                           |
| deepcopy_reduce          | 3.82 us                                                | 3.07 us: 1.25x faster                                                           |
| docutils                 | 3.17 sec                                               | 2.60 sec: 1.22x faster                                                          |
| bench_thread_pool        | 947 us                                                 | 809 us: 1.17x faster                                                            |
| scimark_fft              | 424 ms                                                 | 366 ms: 1.16x faster                                                            |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.74 ms: 1.15x faster                                                           |
| xml_etree_generate       | 94.2 ms                                                | 82.1 ms: 1.15x faster                                                           |
| dulwich_log              | 75.9 ms                                                | 66.3 ms: 1.15x faster                                                           |
| json_loads               | 28.8 us                                                | 25.4 us: 1.13x faster                                                           |
| json                     | 5.42 ms                                                | 4.78 ms: 1.13x faster                                                           |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.10x faster                                                            |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                            |
| create_gc_cycles         | 1.67 ms                                                | 1.54 ms: 1.09x faster                                                           |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                                            |
| regex_v8                 | 25.0 ms                                                | 23.3 ms: 1.08x faster                                                           |
| pathlib                  | 20.0 ms                                                | 18.6 ms: 1.08x faster                                                           |
| mdp                      | 2.82 sec                                               | 2.63 sec: 1.07x faster                                                          |
| sqlite_synth             | 2.93 us                                                | 2.73 us: 1.07x faster                                                           |
| regex_dna                | 222 ms                                                 | 215 ms: 1.03x faster                                                            |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                            |
| gc_traversal             | 3.84 ms                                                | 3.97 ms: 1.03x slower                                                           |
| pickle_list              | 4.56 us                                                | 4.75 us: 1.04x slower                                                           |
| async_generators         | 425 ms                                                 | 444 ms: 1.05x slower                                                            |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                                           |
| unpickle                 | 14.1 us                                                | 15.3 us: 1.08x slower                                                           |
| regex_effbot             | 3.23 ms                                                | 3.57 ms: 1.11x slower                                                           |
| coverage                 | 72.8 ms                                                | 84.7 ms: 1.16x slower                                                           |
| python_startup_no_site   | 5.82 ms                                                | 6.83 ms: 1.17x slower                                                           |
| pickle_dict              | 27.3 us                                                | 32.4 us: 1.19x slower                                                           |
| telco                    | 6.54 ms                                                | 8.10 ms: 1.24x slower                                                           |
| dask                     | 423 ms                                                 | 528 ms: 1.25x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                                    |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle_list
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.24x
