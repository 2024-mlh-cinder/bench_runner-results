
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 8882b30
- commit date: 2023-09-29
- overall geometric mean: 1.01x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 269 ms: 1.01x slower                                    |
| docutils       | 2.70 sec                                               | 2.72 sec: 1.01x slower                                  |
| tornado_http   | 99.6 ms                                                | 100 ms: 1.01x slower                                    |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 80.7 ms                                                | 80.1 ms: 1.01x faster                                   |
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                    |
| nbody          | 88.8 ms                                                | 92.8 ms: 1.05x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 22.3 ms                                                | 22.1 ms: 1.01x faster                                   |
| regex_effbot   | 3.55 ms                                                | 3.58 ms: 1.01x slower                                   |
| Geometric mean | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (2): regex_compile, regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|--------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps         | 9.85 ms                                                | 9.78 ms: 1.01x faster                                   |
| xml_etree_process  | 58.6 ms                                                | 59.0 ms: 1.01x slower                                   |
| pickle_list        | 4.62 us                                                | 4.70 us: 1.02x slower                                   |
| unpickle_list      | 4.95 us                                                | 5.05 us: 1.02x slower                                   |
| pickle_pure_python | 309 us                                                 | 316 us: 1.02x slower                                    |
| pickle_dict        | 31.6 us                                                | 32.7 us: 1.04x slower                                   |
| Geometric mean     | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (8): unpickle, json_loads, pickle, xml_etree_generate, unpickle_pure_python, tomli_loads, xml_etree_iterparse, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup | 9.47 ms                                                | 9.48 ms: 1.00x slower                                   |
| Geometric mean | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| coroutines              | 22.4 ms                                                | 22.1 ms: 1.02x faster                                   |
| deepcopy                | 355 us                                                 | 352 us: 1.01x faster                                    |
| regex_v8                | 22.3 ms                                                | 22.1 ms: 1.01x faster                                   |
| pyflate                 | 450 ms                                                 | 446 ms: 1.01x faster                                    |
| deepcopy_reduce         | 3.14 us                                                | 3.11 us: 1.01x faster                                   |
| float                   | 80.7 ms                                                | 80.1 ms: 1.01x faster                                   |
| json_dumps              | 9.85 ms                                                | 9.78 ms: 1.01x faster                                   |
| pycparser               | 1.15 sec                                               | 1.14 sec: 1.01x faster                                  |
| python_startup          | 9.47 ms                                                | 9.48 ms: 1.00x slower                                   |
| sqlglot_normalize       | 107 ms                                                 | 107 ms: 1.00x slower                                    |
| async_tree_io           | 1.16 sec                                               | 1.16 sec: 1.00x slower                                  |
| asyncio_tcp_ssl         | 1.79 sec                                               | 1.80 sec: 1.00x slower                                  |
| sqlglot_optimize        | 53.3 ms                                                | 53.4 ms: 1.00x slower                                   |
| deepcopy_memo           | 37.4 us                                                | 37.5 us: 1.00x slower                                   |
| dulwich_log             | 67.9 ms                                                | 68.1 ms: 1.00x slower                                   |
| mypy2                   | 344 ms                                                 | 345 ms: 1.00x slower                                    |
| bench_thread_pool       | 827 us                                                 | 831 us: 1.00x slower                                    |
| nqueens                 | 81.1 ms                                                | 81.5 ms: 1.00x slower                                   |
| pidigits                | 187 ms                                                 | 188 ms: 1.01x slower                                    |
| 2to3                    | 268 ms                                                 | 269 ms: 1.01x slower                                    |
| asyncio_tcp             | 526 ms                                                 | 529 ms: 1.01x slower                                    |
| docutils                | 2.70 sec                                               | 2.72 sec: 1.01x slower                                  |
| xml_etree_process       | 58.6 ms                                                | 59.0 ms: 1.01x slower                                   |
| scimark_lu              | 114 ms                                                 | 115 ms: 1.01x slower                                    |
| tornado_http            | 99.6 ms                                                | 100 ms: 1.01x slower                                    |
| comprehensions          | 20.4 us                                                | 20.6 us: 1.01x slower                                   |
| sqlglot_transpile       | 1.64 ms                                                | 1.65 ms: 1.01x slower                                   |
| regex_effbot            | 3.55 ms                                                | 3.58 ms: 1.01x slower                                   |
| pprint_safe_repr        | 735 ms                                                 | 742 ms: 1.01x slower                                    |
| fannkuch                | 387 ms                                                 | 391 ms: 1.01x slower                                    |
| pprint_pformat          | 1.50 sec                                               | 1.52 sec: 1.01x slower                                  |
| sqlglot_parse           | 1.32 ms                                                | 1.34 ms: 1.01x slower                                   |
| go                      | 136 ms                                                 | 138 ms: 1.01x slower                                    |
| pathlib                 | 18.5 ms                                                | 18.8 ms: 1.02x slower                                   |
| pickle_list             | 4.62 us                                                | 4.70 us: 1.02x slower                                   |
| async_generators        | 440 ms                                                 | 449 ms: 1.02x slower                                    |
| unpickle_list           | 4.95 us                                                | 5.05 us: 1.02x slower                                   |
| deltablue               | 3.52 ms                                                | 3.60 ms: 1.02x slower                                   |
| pickle_pure_python      | 309 us                                                 | 316 us: 1.02x slower                                    |
| hexiom                  | 6.12 ms                                                | 6.26 ms: 1.02x slower                                   |
| crypto_pyaes            | 77.2 ms                                                | 79.1 ms: 1.03x slower                                   |
| logging_silent          | 99.1 ns                                                | 102 ns: 1.03x slower                                    |
| gc_traversal            | 3.84 ms                                                | 3.95 ms: 1.03x slower                                   |
| richards_super          | 49.0 ms                                                | 50.6 ms: 1.03x slower                                   |
| pickle_dict             | 31.6 us                                                | 32.7 us: 1.04x slower                                   |
| logging_simple          | 6.18 us                                                | 6.40 us: 1.04x slower                                   |
| logging_format          | 6.90 us                                                | 7.16 us: 1.04x slower                                   |
| nbody                   | 88.8 ms                                                | 92.8 ms: 1.05x slower                                   |
| generators              | 31.1 ms                                                | 32.6 ms: 1.05x slower                                   |
| scimark_sparse_mat_mult | 4.74 ms                                                | 5.12 ms: 1.08x slower                                   |
| unpack_sequence         | 44.8 ns                                                | 53.7 ns: 1.20x slower                                   |
| Geometric mean          | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (34): unpickle, json_loads, typing_runtime_protocols, async_tree_none, pickle, sqlalchemy_imperative, spectral_norm, xml_etree_generate, create_gc_cycles, mdp, sqlite_synth, raytrace, chaos, unpickle_pure_python, meteor_contest, python_startup_no_site, bench_mp_pool, tomli_loads, async_tree_memoization, mako, telco, scimark_monte_carlo, json, scimark_fft, xml_etree_iterparse, regex_compile, xml_etree_parse, scimark_sor, sqlalchemy_declarative, coverage, regex_dna, async_tree_cpu_io_mixed, dask, richards


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
