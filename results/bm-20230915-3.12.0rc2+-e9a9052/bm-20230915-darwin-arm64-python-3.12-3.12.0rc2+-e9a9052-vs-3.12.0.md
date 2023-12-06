
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.00x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 170 ms: 1.00x faster                                    |
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| nbody          | 68.6 ms                                                | 68.4 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 16.0 ms                                                | 15.8 ms: 1.01x faster                                   |
| regex_compile  | 75.8 ms                                                | 75.5 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (2): regex_effbot, regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.89 us: 1.01x faster                                   |
| tomli_loads          | 1.39 sec                                               | 1.38 sec: 1.01x faster                                  |
| pickle               | 7.45 us                                                | 7.40 us: 1.01x faster                                   |
| xml_etree_iterparse  | 74.3 ms                                                | 73.9 ms: 1.01x faster                                   |
| unpickle             | 9.26 us                                                | 9.22 us: 1.00x faster                                   |
| unpickle_list        | 3.22 us                                                | 3.21 us: 1.00x faster                                   |
| unpickle_pure_python | 145 us                                                 | 144 us: 1.00x faster                                    |
| pickle_dict          | 18.0 us                                                | 18.0 us: 1.00x faster                                   |
| xml_etree_process    | 38.5 ms                                                | 38.5 ms: 1.00x faster                                   |
| json_dumps           | 6.43 ms                                                | 6.45 ms: 1.00x slower                                   |
| Geometric mean       | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (4): xml_etree_parse, pickle_pure_python, json_loads, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.73 ms: 1.03x slower                                   |
| python_startup         | 11.5 ms                                                | 11.9 ms: 1.03x slower                                   |
| Geometric mean         | (ref)                                                  | 1.03x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.53 ms: 1.00x faster                                   |

All benchmarks:
===============

| Benchmark               | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-darwin-arm64-python-3.12-3.12.0rc2+-e9a9052 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| telco                   | 3.82 ms                                                | 3.72 ms: 1.03x faster                                   |
| mdp                     | 1.68 sec                                               | 1.65 sec: 1.02x faster                                  |
| sqlalchemy_declarative  | 65.9 ms                                                | 65.0 ms: 1.01x faster                                   |
| asyncio_tcp_ssl         | 1.26 sec                                               | 1.24 sec: 1.01x faster                                  |
| regex_v8                | 16.0 ms                                                | 15.8 ms: 1.01x faster                                   |
| async_tree_io           | 669 ms                                                 | 661 ms: 1.01x faster                                    |
| async_tree_none         | 262 ms                                                 | 259 ms: 1.01x faster                                    |
| async_tree_memoization  | 309 ms                                                 | 306 ms: 1.01x faster                                    |
| pickle_list             | 2.92 us                                                | 2.89 us: 1.01x faster                                   |
| tomli_loads             | 1.39 sec                                               | 1.38 sec: 1.01x faster                                  |
| sqlalchemy_imperative   | 7.02 ms                                                | 6.97 ms: 1.01x faster                                   |
| docutils                | 1.54 sec                                               | 1.53 sec: 1.01x faster                                  |
| generators              | 28.5 ms                                                | 28.3 ms: 1.01x faster                                   |
| pickle                  | 7.45 us                                                | 7.40 us: 1.01x faster                                   |
| pycparser               | 670 ms                                                 | 666 ms: 1.01x faster                                    |
| pyflate                 | 329 ms                                                 | 327 ms: 1.01x faster                                    |
| scimark_sparse_mat_mult | 3.16 ms                                                | 3.14 ms: 1.01x faster                                   |
| xml_etree_iterparse     | 74.3 ms                                                | 73.9 ms: 1.01x faster                                   |
| bench_thread_pool       | 489 us                                                 | 487 us: 1.01x faster                                    |
| mako                    | 7.57 ms                                                | 7.53 ms: 1.00x faster                                   |
| 2to3                    | 171 ms                                                 | 170 ms: 1.00x faster                                    |
| regex_compile           | 75.8 ms                                                | 75.5 ms: 1.00x faster                                   |
| sqlglot_parse           | 898 us                                                 | 894 us: 1.00x faster                                    |
| deltablue               | 2.59 ms                                                | 2.58 ms: 1.00x faster                                   |
| unpickle                | 9.26 us                                                | 9.22 us: 1.00x faster                                   |
| logging_simple          | 3.69 us                                                | 3.68 us: 1.00x faster                                   |
| sqlite_synth            | 1.58 us                                                | 1.58 us: 1.00x faster                                   |
| unpickle_list           | 3.22 us                                                | 3.21 us: 1.00x faster                                   |
| spectral_norm           | 75.0 ms                                                | 74.7 ms: 1.00x faster                                   |
| pidigits                | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| logging_format          | 3.97 us                                                | 3.96 us: 1.00x faster                                   |
| raytrace                | 246 ms                                                 | 246 ms: 1.00x faster                                    |
| pprint_pformat          | 1.00 sec                                               | 1.00 sec: 1.00x faster                                  |
| crypto_pyaes            | 52.3 ms                                                | 52.1 ms: 1.00x faster                                   |
| fannkuch                | 267 ms                                                 | 266 ms: 1.00x faster                                    |
| pprint_safe_repr        | 493 ms                                                 | 492 ms: 1.00x faster                                    |
| nbody                   | 68.6 ms                                                | 68.4 ms: 1.00x faster                                   |
| unpickle_pure_python    | 145 us                                                 | 144 us: 1.00x faster                                    |
| sqlglot_optimize        | 34.3 ms                                                | 34.2 ms: 1.00x faster                                   |
| pickle_dict             | 18.0 us                                                | 18.0 us: 1.00x faster                                   |
| chaos                   | 45.2 ms                                                | 45.1 ms: 1.00x faster                                   |
| scimark_monte_carlo     | 50.1 ms                                                | 50.0 ms: 1.00x faster                                   |
| richards_super          | 34.9 ms                                                | 34.8 ms: 1.00x faster                                   |
| xml_etree_process       | 38.5 ms                                                | 38.5 ms: 1.00x faster                                   |
| gc_traversal            | 2.40 ms                                                | 2.40 ms: 1.00x faster                                   |
| hexiom                  | 4.24 ms                                                | 4.23 ms: 1.00x faster                                   |
| create_gc_cycles        | 702 us                                                 | 704 us: 1.00x slower                                    |
| json_dumps              | 6.43 ms                                                | 6.45 ms: 1.00x slower                                   |
| scimark_sor             | 94.1 ms                                                | 94.4 ms: 1.00x slower                                   |
| async_generators        | 303 ms                                                 | 304 ms: 1.00x slower                                    |
| coverage                | 51.0 ms                                                | 51.3 ms: 1.01x slower                                   |
| deepcopy_memo           | 24.5 us                                                | 24.6 us: 1.01x slower                                   |
| deepcopy_reduce         | 2.02 us                                                | 2.03 us: 1.01x slower                                   |
| deepcopy                | 224 us                                                 | 225 us: 1.01x slower                                    |
| bench_mp_pool           | 45.9 ms                                                | 46.5 ms: 1.01x slower                                   |
| python_startup_no_site  | 9.43 ms                                                | 9.73 ms: 1.03x slower                                   |
| python_startup          | 11.5 ms                                                | 11.9 ms: 1.03x slower                                   |
| coroutines              | 18.2 ms                                                | 19.0 ms: 1.05x slower                                   |
| pathlib                 | 28.8 ms                                                | 32.7 ms: 1.13x slower                                   |
| dask                    | 228 ms                                                 | 329 ms: 1.44x slower                                    |
| Geometric mean          | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (25): asyncio_tcp, mypy2, async_tree_cpu_io_mixed, unpack_sequence, xml_etree_parse, json, pickle_pure_python, nqueens, json_loads, float, sqlglot_transpile, typing_runtime_protocols, comprehensions, go, meteor_contest, sqlglot_normalize, scimark_fft, scimark_lu, richards, regex_effbot, dulwich_log, regex_dna, logging_silent, xml_etree_generate, tornado_http


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
