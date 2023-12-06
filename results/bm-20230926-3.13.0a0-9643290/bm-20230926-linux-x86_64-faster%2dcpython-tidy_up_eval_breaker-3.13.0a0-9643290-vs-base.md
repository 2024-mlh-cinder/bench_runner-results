
# Results vs. base

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 9643290
- commit date: 2023-09-26
- overall geometric mean: 1.00x slower
- HPT reliability: 93.14%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| docutils       | 2.59 sec                                                              | 2.60 sec: 1.00x slower                                                          |
| Geometric mean | (ref)                                                                 | 1.00x slower                                                                    |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.00x slower                                                            |
| float          | 78.9 ms                                                               | 80.0 ms: 1.01x slower                                                           |
| nbody          | 88.6 ms                                                               | 91.7 ms: 1.04x slower                                                           |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| regex_compile  | 135 ms                                                                | 135 ms: 1.00x faster                                                            |
| regex_effbot   | 3.51 ms                                                               | 3.57 ms: 1.02x slower                                                           |
| regex_dna      | 207 ms                                                                | 215 ms: 1.04x slower                                                            |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                                    |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| unpickle_list        | 4.96 us                                                               | 4.83 us: 1.03x faster                                                           |
| pickle_pure_python   | 299 us                                                                | 294 us: 1.02x faster                                                            |
| xml_etree_parse      | 152 ms                                                                | 151 ms: 1.01x faster                                                            |
| unpickle_pure_python | 215 us                                                                | 214 us: 1.01x faster                                                            |
| xml_etree_generate   | 81.9 ms                                                               | 82.1 ms: 1.00x slower                                                           |
| pickle_list          | 4.72 us                                                               | 4.75 us: 1.01x slower                                                           |
| xml_etree_process    | 56.5 ms                                                               | 57.1 ms: 1.01x slower                                                           |
| json_dumps           | 9.84 ms                                                               | 9.94 ms: 1.01x slower                                                           |
| json_loads           | 25.1 us                                                               | 25.4 us: 1.01x slower                                                           |
| tomli_loads          | 2.06 sec                                                              | 2.12 sec: 1.03x slower                                                          |
| pickle_dict          | 30.4 us                                                               | 32.4 us: 1.07x slower                                                           |
| pickle               | 10.1 us                                                               | 10.8 us: 1.07x slower                                                           |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                                    |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| python_startup_no_site | 6.86 ms                                                               | 6.83 ms: 1.00x faster                                                           |
| python_startup         | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                                           |
| Geometric mean         | (ref)                                                                 | 1.00x faster                                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                               | 10.6 ms: 1.01x faster                                                           |

All benchmarks:
===============

| Benchmark                | bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743 | bm-20230926-linux-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-9643290 |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| scimark_sor              | 129 ms                                                                | 121 ms: 1.07x faster                                                            |
| deltablue                | 3.38 ms                                                               | 3.27 ms: 1.03x faster                                                           |
| unpickle_list            | 4.96 us                                                               | 4.83 us: 1.03x faster                                                           |
| coverage                 | 86.5 ms                                                               | 84.7 ms: 1.02x faster                                                           |
| unpack_sequence          | 51.5 ns                                                               | 50.5 ns: 1.02x faster                                                           |
| pickle_pure_python       | 299 us                                                                | 294 us: 1.02x faster                                                            |
| go                       | 141 ms                                                                | 139 ms: 1.01x faster                                                            |
| json                     | 4.84 ms                                                               | 4.78 ms: 1.01x faster                                                           |
| mako                     | 10.7 ms                                                               | 10.6 ms: 1.01x faster                                                           |
| logging_format           | 6.60 us                                                               | 6.52 us: 1.01x faster                                                           |
| logging_simple           | 5.92 us                                                               | 5.86 us: 1.01x faster                                                           |
| xml_etree_parse          | 152 ms                                                                | 151 ms: 1.01x faster                                                            |
| deepcopy_reduce          | 3.10 us                                                               | 3.07 us: 1.01x faster                                                           |
| pycparser                | 1.19 sec                                                              | 1.18 sec: 1.01x faster                                                          |
| sqlglot_parse            | 1.27 ms                                                               | 1.26 ms: 1.01x faster                                                           |
| generators               | 28.8 ms                                                               | 28.6 ms: 1.01x faster                                                           |
| hexiom                   | 6.06 ms                                                               | 6.02 ms: 1.01x faster                                                           |
| coroutines               | 22.3 ms                                                               | 22.2 ms: 1.01x faster                                                           |
| sqlglot_transpile        | 1.58 ms                                                               | 1.57 ms: 1.01x faster                                                           |
| unpickle_pure_python     | 215 us                                                                | 214 us: 1.01x faster                                                            |
| sqlglot_optimize         | 52.5 ms                                                               | 52.3 ms: 1.00x faster                                                           |
| comprehensions           | 20.5 us                                                               | 20.4 us: 1.00x faster                                                           |
| fannkuch                 | 388 ms                                                                | 386 ms: 1.00x faster                                                            |
| python_startup_no_site   | 6.86 ms                                                               | 6.83 ms: 1.00x faster                                                           |
| regex_compile            | 135 ms                                                                | 135 ms: 1.00x faster                                                            |
| python_startup           | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                                           |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.80 sec: 1.00x slower                                                          |
| xml_etree_generate       | 81.9 ms                                                               | 82.1 ms: 1.00x slower                                                           |
| docutils                 | 2.59 sec                                                              | 2.60 sec: 1.00x slower                                                          |
| pidigits                 | 187 ms                                                                | 188 ms: 1.00x slower                                                            |
| meteor_contest           | 104 ms                                                                | 105 ms: 1.01x slower                                                            |
| asyncio_tcp              | 499 ms                                                                | 502 ms: 1.01x slower                                                            |
| raytrace                 | 270 ms                                                                | 271 ms: 1.01x slower                                                            |
| mypy2                    | 337 ms                                                                | 339 ms: 1.01x slower                                                            |
| pickle_list              | 4.72 us                                                               | 4.75 us: 1.01x slower                                                           |
| scimark_lu               | 110 ms                                                                | 111 ms: 1.01x slower                                                            |
| pathlib                  | 18.5 ms                                                               | 18.6 ms: 1.01x slower                                                           |
| pyflate                  | 458 ms                                                                | 461 ms: 1.01x slower                                                            |
| xml_etree_process        | 56.5 ms                                                               | 57.1 ms: 1.01x slower                                                           |
| crypto_pyaes             | 69.4 ms                                                               | 70.1 ms: 1.01x slower                                                           |
| logging_silent           | 100 ns                                                                | 101 ns: 1.01x slower                                                            |
| json_dumps               | 9.84 ms                                                               | 9.94 ms: 1.01x slower                                                           |
| chaos                    | 59.7 ms                                                               | 60.4 ms: 1.01x slower                                                           |
| json_loads               | 25.1 us                                                               | 25.4 us: 1.01x slower                                                           |
| scimark_sparse_mat_mult  | 4.68 ms                                                               | 4.74 ms: 1.01x slower                                                           |
| typing_runtime_protocols | 141 us                                                                | 143 us: 1.01x slower                                                            |
| float                    | 78.9 ms                                                               | 80.0 ms: 1.01x slower                                                           |
| scimark_fft              | 360 ms                                                                | 366 ms: 1.02x slower                                                            |
| regex_effbot             | 3.51 ms                                                               | 3.57 ms: 1.02x slower                                                           |
| nqueens                  | 78.3 ms                                                               | 80.1 ms: 1.02x slower                                                           |
| spectral_norm            | 104 ms                                                                | 107 ms: 1.03x slower                                                            |
| tomli_loads              | 2.06 sec                                                              | 2.12 sec: 1.03x slower                                                          |
| gc_traversal             | 3.86 ms                                                               | 3.97 ms: 1.03x slower                                                           |
| nbody                    | 88.6 ms                                                               | 91.7 ms: 1.04x slower                                                           |
| regex_dna                | 207 ms                                                                | 215 ms: 1.04x slower                                                            |
| mdp                      | 2.51 sec                                                              | 2.63 sec: 1.05x slower                                                          |
| pickle_dict              | 30.4 us                                                               | 32.4 us: 1.07x slower                                                           |
| pickle                   | 10.1 us                                                               | 10.8 us: 1.07x slower                                                           |
| Geometric mean           | (ref)                                                                 | 1.00x slower                                                                    |

Benchmark hidden because not significant (24): async_generators, scimark_monte_carlo, richards_super, telco, tornado_http, deepcopy, sqlglot_normalize, dulwich_log, pprint_pformat, bench_mp_pool, regex_v8, create_gc_cycles, richards, async_tree_io, sqlite_synth, async_tree_none, xml_etree_iterparse, pprint_safe_repr, bench_thread_pool, deepcopy_memo, async_tree_memoization, async_tree_cpu_io_mixed, dask, unpickle


# HPT report

- Reliability score: 93.14% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
