
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.00x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 170 ms: 1.00x faster                                    |
| docutils       | 1.54 sec                                               | 1.53 sec: 1.00x faster                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 58.2 ms                                                | 57.9 ms: 1.00x faster                                   |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| Geometric mean | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 16.0 ms                                                | 15.6 ms: 1.03x faster                                   |
| regex_effbot   | 2.58 ms                                                | 2.56 ms: 1.01x faster                                   |
| regex_dna      | 151 ms                                                 | 150 ms: 1.01x faster                                    |
| regex_compile  | 75.8 ms                                                | 75.6 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| tomli_loads          | 1.39 sec                                               | 1.38 sec: 1.01x faster                                  |
| unpickle             | 9.26 us                                                | 9.19 us: 1.01x faster                                   |
| xml_etree_parse      | 109 ms                                                 | 108 ms: 1.01x faster                                    |
| pickle_list          | 2.92 us                                                | 2.90 us: 1.01x faster                                   |
| xml_etree_iterparse  | 74.3 ms                                                | 73.9 ms: 1.01x faster                                   |
| unpickle_pure_python | 145 us                                                 | 144 us: 1.00x faster                                    |
| pickle_dict          | 18.0 us                                                | 18.0 us: 1.00x faster                                   |
| pickle_pure_python   | 188 us                                                 | 188 us: 1.00x faster                                    |
| json_dumps           | 6.43 ms                                                | 6.45 ms: 1.00x slower                                   |
| Geometric mean       | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (5): unpickle_list, xml_etree_process, json_loads, xml_etree_generate, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 11.5 ms                                                | 11.9 ms: 1.03x slower                                   |
| python_startup_no_site | 9.43 ms                                                | 9.73 ms: 1.03x slower                                   |
| Geometric mean         | (ref)                                                  | 1.03x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.52 ms: 1.01x faster                                   |

All benchmarks:
===============

| Benchmark               | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-darwin-arm64-python-3.12-3.12.0rc3+-f6287bd |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8                | 16.0 ms                                                | 15.6 ms: 1.03x faster                                   |
| telco                   | 3.82 ms                                                | 3.72 ms: 1.03x faster                                   |
| sqlalchemy_declarative  | 65.9 ms                                                | 64.8 ms: 1.02x faster                                   |
| dask                    | 228 ms                                                 | 224 ms: 1.02x faster                                    |
| async_tree_io           | 669 ms                                                 | 660 ms: 1.01x faster                                    |
| async_tree_none         | 262 ms                                                 | 259 ms: 1.01x faster                                    |
| async_tree_memoization  | 309 ms                                                 | 306 ms: 1.01x faster                                    |
| async_tree_cpu_io_mixed | 526 ms                                                 | 521 ms: 1.01x faster                                    |
| mdp                     | 1.68 sec                                               | 1.66 sec: 1.01x faster                                  |
| asyncio_tcp_ssl         | 1.26 sec                                               | 1.25 sec: 1.01x faster                                  |
| pycparser               | 670 ms                                                 | 664 ms: 1.01x faster                                    |
| regex_effbot            | 2.58 ms                                                | 2.56 ms: 1.01x faster                                   |
| tomli_loads             | 1.39 sec                                               | 1.38 sec: 1.01x faster                                  |
| unpickle                | 9.26 us                                                | 9.19 us: 1.01x faster                                   |
| xml_etree_parse         | 109 ms                                                 | 108 ms: 1.01x faster                                    |
| pickle_list             | 2.92 us                                                | 2.90 us: 1.01x faster                                   |
| regex_dna               | 151 ms                                                 | 150 ms: 1.01x faster                                    |
| xml_etree_iterparse     | 74.3 ms                                                | 73.9 ms: 1.01x faster                                   |
| mako                    | 7.57 ms                                                | 7.52 ms: 1.01x faster                                   |
| pyflate                 | 329 ms                                                 | 327 ms: 1.01x faster                                    |
| 2to3                    | 171 ms                                                 | 170 ms: 1.00x faster                                    |
| float                   | 58.2 ms                                                | 57.9 ms: 1.00x faster                                   |
| raytrace                | 246 ms                                                 | 245 ms: 1.00x faster                                    |
| docutils                | 1.54 sec                                               | 1.53 sec: 1.00x faster                                  |
| coroutines              | 18.2 ms                                                | 18.1 ms: 1.00x faster                                   |
| scimark_sparse_mat_mult | 3.16 ms                                                | 3.14 ms: 1.00x faster                                   |
| nqueens                 | 60.6 ms                                                | 60.3 ms: 1.00x faster                                   |
| pprint_pformat          | 1.00 sec                                               | 1.00 sec: 1.00x faster                                  |
| logging_simple          | 3.69 us                                                | 3.68 us: 1.00x faster                                   |
| unpickle_pure_python    | 145 us                                                 | 144 us: 1.00x faster                                    |
| regex_compile           | 75.8 ms                                                | 75.6 ms: 1.00x faster                                   |
| pprint_safe_repr        | 493 ms                                                 | 492 ms: 1.00x faster                                    |
| sqlglot_optimize        | 34.3 ms                                                | 34.2 ms: 1.00x faster                                   |
| pickle_dict             | 18.0 us                                                | 18.0 us: 1.00x faster                                   |
| spectral_norm           | 75.0 ms                                                | 74.8 ms: 1.00x faster                                   |
| pidigits                | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| crypto_pyaes            | 52.3 ms                                                | 52.2 ms: 1.00x faster                                   |
| logging_silent          | 67.7 ns                                                | 67.5 ns: 1.00x faster                                   |
| pickle_pure_python      | 188 us                                                 | 188 us: 1.00x faster                                    |
| scimark_monte_carlo     | 50.1 ms                                                | 50.0 ms: 1.00x faster                                   |
| bench_thread_pool       | 489 us                                                 | 488 us: 1.00x faster                                    |
| gc_traversal            | 2.40 ms                                                | 2.40 ms: 1.00x faster                                   |
| dulwich_log             | 30.3 ms                                                | 30.4 ms: 1.00x slower                                   |
| deepcopy_memo           | 24.5 us                                                | 24.5 us: 1.00x slower                                   |
| fannkuch                | 267 ms                                                 | 268 ms: 1.00x slower                                    |
| async_generators        | 303 ms                                                 | 304 ms: 1.00x slower                                    |
| sqlalchemy_imperative   | 7.02 ms                                                | 7.05 ms: 1.00x slower                                   |
| json_dumps              | 6.43 ms                                                | 6.45 ms: 1.00x slower                                   |
| meteor_contest          | 72.9 ms                                                | 73.2 ms: 1.00x slower                                   |
| json                    | 3.05 ms                                                | 3.06 ms: 1.00x slower                                   |
| create_gc_cycles        | 702 us                                                 | 706 us: 1.01x slower                                    |
| coverage                | 51.0 ms                                                | 51.4 ms: 1.01x slower                                   |
| sqlite_synth            | 1.58 us                                                | 1.60 us: 1.01x slower                                   |
| go                      | 107 ms                                                 | 108 ms: 1.01x slower                                    |
| hexiom                  | 4.24 ms                                                | 4.31 ms: 1.02x slower                                   |
| python_startup          | 11.5 ms                                                | 11.9 ms: 1.03x slower                                   |
| python_startup_no_site  | 9.43 ms                                                | 9.73 ms: 1.03x slower                                   |
| pathlib                 | 28.8 ms                                                | 32.8 ms: 1.14x slower                                   |
| Geometric mean          | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (27): mypy2, asyncio_tcp, unpack_sequence, typing_runtime_protocols, unpickle_list, generators, sqlglot_parse, nbody, logging_format, xml_etree_process, json_loads, comprehensions, xml_etree_generate, pickle, scimark_fft, chaos, richards_super, deepcopy, scimark_lu, sqlglot_normalize, richards, sqlglot_transpile, deltablue, deepcopy_reduce, scimark_sor, bench_mp_pool, tornado_http


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
