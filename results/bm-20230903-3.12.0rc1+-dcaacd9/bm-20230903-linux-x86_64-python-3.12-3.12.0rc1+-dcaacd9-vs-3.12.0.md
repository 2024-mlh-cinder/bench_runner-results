
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: dcaacd9
- commit date: 2023-09-03
- overall geometric mean: 1.01x slower
- HPT reliability: 56.01%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.72 sec: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 80.7 ms                                                | 78.6 ms: 1.03x faster                                   |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                    |
| nbody          | 88.8 ms                                                | 89.5 ms: 1.01x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 142 ms: 1.01x faster                                    |
| regex_effbot   | 3.55 ms                                                | 3.61 ms: 1.02x slower                                   |
| regex_v8       | 22.3 ms                                                | 22.7 ms: 1.02x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.17 sec: 1.02x faster                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                    |
| unpickle_pure_python | 218 us                                                 | 216 us: 1.01x faster                                    |
| pickle_pure_python   | 309 us                                                 | 307 us: 1.01x faster                                    |
| xml_etree_generate   | 84.8 ms                                                | 84.4 ms: 1.00x faster                                   |
| pickle_list          | 4.62 us                                                | 4.74 us: 1.03x slower                                   |
| pickle_dict          | 31.6 us                                                | 32.7 us: 1.03x slower                                   |
| pickle               | 10.6 us                                                | 11.0 us: 1.03x slower                                   |
| unpickle_list        | 4.95 us                                                | 5.18 us: 1.05x slower                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (5): unpickle, json_loads, json_dumps, xml_etree_parse, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                   |
| python_startup         | 9.47 ms                                                | 9.44 ms: 1.00x faster                                   |
| Geometric mean         | (ref)                                                  | 1.00x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.7 ms: 1.01x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float                    | 80.7 ms                                                | 78.6 ms: 1.03x faster                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.48 ms: 1.03x faster                                   |
| pathlib                  | 18.5 ms                                                | 18.1 ms: 1.02x faster                                   |
| tomli_loads              | 2.22 sec                                               | 2.17 sec: 1.02x faster                                  |
| deepcopy                 | 355 us                                                 | 348 us: 1.02x faster                                    |
| asyncio_tcp              | 526 ms                                                 | 516 ms: 1.02x faster                                    |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                    |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                    |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                   |
| typing_runtime_protocols | 146 us                                                 | 144 us: 1.02x faster                                    |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                    |
| raytrace                 | 294 ms                                                 | 291 ms: 1.01x faster                                    |
| regex_compile            | 144 ms                                                 | 142 ms: 1.01x faster                                    |
| unpickle_pure_python     | 218 us                                                 | 216 us: 1.01x faster                                    |
| deepcopy_reduce          | 3.14 us                                                | 3.11 us: 1.01x faster                                   |
| pprint_pformat           | 1.50 sec                                               | 1.49 sec: 1.01x faster                                  |
| deepcopy_memo            | 37.4 us                                                | 37.1 us: 1.01x faster                                   |
| chaos                    | 63.5 ms                                                | 63.1 ms: 1.01x faster                                   |
| deltablue                | 3.52 ms                                                | 3.49 ms: 1.01x faster                                   |
| pprint_safe_repr         | 735 ms                                                 | 730 ms: 1.01x faster                                    |
| pickle_pure_python       | 309 us                                                 | 307 us: 1.01x faster                                    |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                   |
| mako                     | 10.7 ms                                                | 10.7 ms: 1.01x faster                                   |
| xml_etree_generate       | 84.8 ms                                                | 84.4 ms: 1.00x faster                                   |
| hexiom                   | 6.12 ms                                                | 6.10 ms: 1.00x faster                                   |
| python_startup           | 9.47 ms                                                | 9.44 ms: 1.00x faster                                   |
| gc_traversal             | 3.84 ms                                                | 3.85 ms: 1.00x slower                                   |
| bench_thread_pool        | 827 us                                                 | 829 us: 1.00x slower                                    |
| async_tree_io            | 1.16 sec                                               | 1.16 sec: 1.00x slower                                  |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                    |
| dulwich_log              | 67.9 ms                                                | 68.1 ms: 1.00x slower                                   |
| comprehensions           | 20.4 us                                                | 20.5 us: 1.00x slower                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                  |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                  |
| docutils                 | 2.70 sec                                               | 2.72 sec: 1.01x slower                                  |
| coverage                 | 94.2 ms                                                | 94.8 ms: 1.01x slower                                   |
| nbody                    | 88.8 ms                                                | 89.5 ms: 1.01x slower                                   |
| spectral_norm            | 106 ms                                                 | 107 ms: 1.01x slower                                    |
| logging_silent           | 99.1 ns                                                | 100 ns: 1.01x slower                                    |
| fannkuch                 | 387 ms                                                 | 393 ms: 1.01x slower                                    |
| regex_effbot             | 3.55 ms                                                | 3.61 ms: 1.02x slower                                   |
| regex_v8                 | 22.3 ms                                                | 22.7 ms: 1.02x slower                                   |
| crypto_pyaes             | 77.2 ms                                                | 78.6 ms: 1.02x slower                                   |
| richards                 | 43.2 ms                                                | 44.0 ms: 1.02x slower                                   |
| meteor_contest           | 105 ms                                                 | 107 ms: 1.02x slower                                    |
| nqueens                  | 81.1 ms                                                | 82.7 ms: 1.02x slower                                   |
| async_generators         | 440 ms                                                 | 450 ms: 1.02x slower                                    |
| richards_super           | 49.0 ms                                                | 50.1 ms: 1.02x slower                                   |
| pickle_list              | 4.62 us                                                | 4.74 us: 1.03x slower                                   |
| pyflate                  | 450 ms                                                 | 464 ms: 1.03x slower                                    |
| generators               | 31.1 ms                                                | 32.0 ms: 1.03x slower                                   |
| pickle_dict              | 31.6 us                                                | 32.7 us: 1.03x slower                                   |
| pickle                   | 10.6 us                                                | 11.0 us: 1.03x slower                                   |
| scimark_fft              | 358 ms                                                 | 372 ms: 1.04x slower                                    |
| unpickle_list            | 4.95 us                                                | 5.18 us: 1.05x slower                                   |
| unpack_sequence          | 44.8 ns                                                | 49.7 ns: 1.11x slower                                   |
| dask                     | 365 ms                                                 | 533 ms: 1.46x slower                                    |
| Geometric mean           | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (28): unpickle, async_tree_cpu_io_mixed, sqlalchemy_imperative, logging_format, json_loads, async_tree_none, sqlglot_transpile, mypy2, mdp, scimark_monte_carlo, logging_simple, async_tree_memoization, tornado_http, bench_mp_pool, sqlglot_optimize, json_dumps, xml_etree_parse, 2to3, xml_etree_process, go, sqlalchemy_declarative, sqlglot_normalize, sqlglot_parse, sqlite_synth, regex_dna, telco, scimark_sparse_mat_mult, json


# HPT report

- Reliability score: 56.01% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
