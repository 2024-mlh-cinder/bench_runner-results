
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 8882b30
- commit date: 2023-09-29
- overall geometric mean: 1.00x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-darwin-arm64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 170 ms: 1.01x faster                                    |
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-darwin-arm64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 58.2 ms                                                | 57.9 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (2): pidigits, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-darwin-arm64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 16.0 ms                                                | 15.8 ms: 1.01x faster                                   |
| regex_compile  | 75.8 ms                                                | 75.5 ms: 1.00x faster                                   |
| regex_dna      | 151 ms                                                 | 152 ms: 1.01x slower                                    |
| Geometric mean | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-darwin-arm64-python-3.12-3.12.0rc3+-8882b30 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| unpickle             | 9.26 us                                                | 9.19 us: 1.01x faster                                   |
| tomli_loads          | 1.39 sec                                               | 1.39 sec: 1.01x faster                                  |
| xml_etree_generate   | 55.8 ms                                                | 55.5 ms: 1.01x faster                                   |
| xml_etree_process    | 38.5 ms                                                | 38.4 ms: 1.00x faster                                   |
| pickle               | 7.45 us                                                | 7.42 us: 1.00x faster                                   |
| pickle_pure_python   | 188 us                                                 | 188 us: 1.00x faster                                    |
| json_loads           | 17.6 us                                                | 17.6 us: 1.00x faster                                   |
| unpickle_pure_python | 145 us                                                 | 144 us: 1.00x faster                                    |
| Geometric mean       | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (6): xml_etree_iterparse, unpickle_list, pickle_list, pickle_dict, json_dumps, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-darwin-arm64-python-3.12-3.12.0rc3+-8882b30 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 11.5 ms                                                | 11.8 ms: 1.02x slower                                   |
| python_startup_no_site | 9.43 ms                                                | 9.61 ms: 1.02x slower                                   |
| Geometric mean         | (ref)                                                  | 1.02x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-darwin-arm64-python-3.12-3.12.0rc3+-8882b30 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.54 ms: 1.00x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230929-darwin-arm64-python-3.12-3.12.0rc3+-8882b30 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| telco                    | 3.82 ms                                                | 3.68 ms: 1.04x faster                                   |
| unpack_sequence          | 28.8 ns                                                | 28.2 ns: 1.02x faster                                   |
| sqlalchemy_declarative   | 65.9 ms                                                | 64.6 ms: 1.02x faster                                   |
| dask                     | 228 ms                                                 | 223 ms: 1.02x faster                                    |
| async_tree_io            | 669 ms                                                 | 660 ms: 1.01x faster                                    |
| regex_v8                 | 16.0 ms                                                | 15.8 ms: 1.01x faster                                   |
| async_tree_none          | 262 ms                                                 | 259 ms: 1.01x faster                                    |
| async_tree_memoization   | 309 ms                                                 | 306 ms: 1.01x faster                                    |
| async_tree_cpu_io_mixed  | 526 ms                                                 | 520 ms: 1.01x faster                                    |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.24 sec: 1.01x faster                                  |
| docutils                 | 1.54 sec                                               | 1.53 sec: 1.01x faster                                  |
| unpickle                 | 9.26 us                                                | 9.19 us: 1.01x faster                                   |
| typing_runtime_protocols | 90.7 us                                                | 90.0 us: 1.01x faster                                   |
| pprint_pformat           | 1.00 sec                                               | 997 ms: 1.01x faster                                    |
| pycparser                | 670 ms                                                 | 665 ms: 1.01x faster                                    |
| tomli_loads              | 1.39 sec                                               | 1.39 sec: 1.01x faster                                  |
| 2to3                     | 171 ms                                                 | 170 ms: 1.01x faster                                    |
| json                     | 3.05 ms                                                | 3.03 ms: 1.01x faster                                   |
| xml_etree_generate       | 55.8 ms                                                | 55.5 ms: 1.01x faster                                   |
| logging_simple           | 3.69 us                                                | 3.67 us: 1.01x faster                                   |
| pprint_safe_repr         | 493 ms                                                 | 491 ms: 1.01x faster                                    |
| sqlglot_parse            | 898 us                                                 | 893 us: 1.01x faster                                    |
| regex_compile            | 75.8 ms                                                | 75.5 ms: 1.00x faster                                   |
| logging_format           | 3.97 us                                                | 3.95 us: 1.00x faster                                   |
| generators               | 28.5 ms                                                | 28.4 ms: 1.00x faster                                   |
| float                    | 58.2 ms                                                | 57.9 ms: 1.00x faster                                   |
| xml_etree_process        | 38.5 ms                                                | 38.4 ms: 1.00x faster                                   |
| mako                     | 7.57 ms                                                | 7.54 ms: 1.00x faster                                   |
| raytrace                 | 246 ms                                                 | 245 ms: 1.00x faster                                    |
| pickle                   | 7.45 us                                                | 7.42 us: 1.00x faster                                   |
| pyflate                  | 329 ms                                                 | 328 ms: 1.00x faster                                    |
| bench_thread_pool        | 489 us                                                 | 488 us: 1.00x faster                                    |
| scimark_sor              | 94.1 ms                                                | 93.8 ms: 1.00x faster                                   |
| go                       | 107 ms                                                 | 107 ms: 1.00x faster                                    |
| pickle_pure_python       | 188 us                                                 | 188 us: 1.00x faster                                    |
| sqlglot_optimize         | 34.3 ms                                                | 34.2 ms: 1.00x faster                                   |
| json_loads               | 17.6 us                                                | 17.6 us: 1.00x faster                                   |
| unpickle_pure_python     | 145 us                                                 | 144 us: 1.00x faster                                    |
| deltablue                | 2.59 ms                                                | 2.59 ms: 1.00x faster                                   |
| sqlalchemy_imperative    | 7.02 ms                                                | 7.01 ms: 1.00x faster                                   |
| hexiom                   | 4.24 ms                                                | 4.23 ms: 1.00x faster                                   |
| coroutines               | 18.2 ms                                                | 18.2 ms: 1.00x faster                                   |
| comprehensions           | 15.7 us                                                | 15.7 us: 1.00x faster                                   |
| scimark_lu               | 71.7 ms                                                | 71.6 ms: 1.00x faster                                   |
| scimark_monte_carlo      | 50.1 ms                                                | 50.0 ms: 1.00x faster                                   |
| meteor_contest           | 72.9 ms                                                | 73.1 ms: 1.00x slower                                   |
| deepcopy                 | 224 us                                                 | 224 us: 1.00x slower                                    |
| scimark_fft              | 198 ms                                                 | 198 ms: 1.00x slower                                    |
| coverage                 | 51.0 ms                                                | 51.4 ms: 1.01x slower                                   |
| regex_dna                | 151 ms                                                 | 152 ms: 1.01x slower                                    |
| python_startup           | 11.5 ms                                                | 11.8 ms: 1.02x slower                                   |
| python_startup_no_site   | 9.43 ms                                                | 9.61 ms: 1.02x slower                                   |
| pathlib                  | 28.8 ms                                                | 32.9 ms: 1.14x slower                                   |
| Geometric mean           | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (32): asyncio_tcp, mypy2, tornado_http, xml_etree_iterparse, unpickle_list, deepcopy_reduce, pickle_list, richards, mdp, dulwich_log, pickle_dict, richards_super, pidigits, gc_traversal, logging_silent, sqlglot_transpile, chaos, spectral_norm, nbody, crypto_pyaes, async_generators, scimark_sparse_mat_mult, json_dumps, sqlglot_normalize, deepcopy_memo, create_gc_cycles, fannkuch, nqueens, sqlite_synth, regex_effbot, xml_etree_parse, bench_mp_pool


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
