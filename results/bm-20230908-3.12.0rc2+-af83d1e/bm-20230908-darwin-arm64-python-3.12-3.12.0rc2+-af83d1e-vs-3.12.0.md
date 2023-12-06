
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.00x slower
- HPT reliability: 99.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 170 ms: 1.00x faster                                    |
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 58.2 ms                                                | 57.9 ms: 1.00x faster                                   |
| nbody          | 68.6 ms                                                | 68.4 ms: 1.00x faster                                   |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| Geometric mean | (ref)                                                  | 1.00x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 16.0 ms                                                | 15.6 ms: 1.03x faster                                   |
| regex_effbot   | 2.58 ms                                                | 2.55 ms: 1.01x faster                                   |
| regex_dna      | 151 ms                                                 | 150 ms: 1.01x faster                                    |
| regex_compile  | 75.8 ms                                                | 75.7 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.87 us: 1.02x faster                                   |
| unpickle_pure_python | 145 us                                                 | 144 us: 1.01x faster                                    |
| tomli_loads          | 1.39 sec                                               | 1.39 sec: 1.00x faster                                  |
| json_dumps           | 6.43 ms                                                | 6.44 ms: 1.00x slower                                   |
| unpickle             | 9.26 us                                                | 9.30 us: 1.00x slower                                   |
| pickle_pure_python   | 188 us                                                 | 190 us: 1.01x slower                                    |
| unpickle_list        | 3.22 us                                                | 3.29 us: 1.02x slower                                   |
| Geometric mean       | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (7): xml_etree_iterparse, pickle, json_loads, xml_etree_generate, pickle_dict, xml_etree_process, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 11.5 ms                                                | 11.8 ms: 1.03x slower                                   |
| python_startup_no_site | 9.43 ms                                                | 9.69 ms: 1.03x slower                                   |
| Geometric mean         | (ref)                                                  | 1.03x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.53 ms: 1.01x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230908-darwin-arm64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| telco                    | 3.82 ms                                                | 3.71 ms: 1.03x faster                                   |
| regex_v8                 | 16.0 ms                                                | 15.6 ms: 1.03x faster                                   |
| pickle_list              | 2.92 us                                                | 2.87 us: 1.02x faster                                   |
| typing_runtime_protocols | 90.7 us                                                | 89.1 us: 1.02x faster                                   |
| sqlalchemy_declarative   | 65.9 ms                                                | 65.0 ms: 1.01x faster                                   |
| async_tree_none          | 262 ms                                                 | 259 ms: 1.01x faster                                    |
| regex_effbot             | 2.58 ms                                                | 2.55 ms: 1.01x faster                                   |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.24 sec: 1.01x faster                                  |
| async_tree_memoization   | 309 ms                                                 | 306 ms: 1.01x faster                                    |
| regex_dna                | 151 ms                                                 | 150 ms: 1.01x faster                                    |
| pycparser                | 670 ms                                                 | 665 ms: 1.01x faster                                    |
| pyflate                  | 329 ms                                                 | 327 ms: 1.01x faster                                    |
| generators               | 28.5 ms                                                | 28.3 ms: 1.01x faster                                   |
| bench_thread_pool        | 489 us                                                 | 486 us: 1.01x faster                                    |
| unpickle_pure_python     | 145 us                                                 | 144 us: 1.01x faster                                    |
| docutils                 | 1.54 sec                                               | 1.53 sec: 1.01x faster                                  |
| logging_simple           | 3.69 us                                                | 3.67 us: 1.01x faster                                   |
| raytrace                 | 246 ms                                                 | 245 ms: 1.01x faster                                    |
| pprint_pformat           | 1.00 sec                                               | 998 ms: 1.01x faster                                    |
| crypto_pyaes             | 52.3 ms                                                | 52.0 ms: 1.01x faster                                   |
| scimark_lu               | 71.7 ms                                                | 71.3 ms: 1.01x faster                                   |
| mako                     | 7.57 ms                                                | 7.53 ms: 1.01x faster                                   |
| fannkuch                 | 267 ms                                                 | 266 ms: 1.00x faster                                    |
| scimark_monte_carlo      | 50.1 ms                                                | 49.8 ms: 1.00x faster                                   |
| pprint_safe_repr         | 493 ms                                                 | 491 ms: 1.00x faster                                    |
| float                    | 58.2 ms                                                | 57.9 ms: 1.00x faster                                   |
| go                       | 107 ms                                                 | 107 ms: 1.00x faster                                    |
| tomli_loads              | 1.39 sec                                               | 1.39 sec: 1.00x faster                                  |
| sqlglot_optimize         | 34.3 ms                                                | 34.2 ms: 1.00x faster                                   |
| 2to3                     | 171 ms                                                 | 170 ms: 1.00x faster                                    |
| nqueens                  | 60.6 ms                                                | 60.4 ms: 1.00x faster                                   |
| create_gc_cycles         | 702 us                                                 | 700 us: 1.00x faster                                    |
| nbody                    | 68.6 ms                                                | 68.4 ms: 1.00x faster                                   |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x faster                                   |
| coroutines               | 18.2 ms                                                | 18.2 ms: 1.00x faster                                   |
| regex_compile            | 75.8 ms                                                | 75.7 ms: 1.00x faster                                   |
| meteor_contest           | 72.9 ms                                                | 72.8 ms: 1.00x faster                                   |
| sqlglot_normalize        | 186 ms                                                 | 186 ms: 1.00x slower                                    |
| dulwich_log              | 30.3 ms                                                | 30.4 ms: 1.00x slower                                   |
| logging_silent           | 67.7 ns                                                | 67.8 ns: 1.00x slower                                   |
| json_dumps               | 6.43 ms                                                | 6.44 ms: 1.00x slower                                   |
| scimark_fft              | 198 ms                                                 | 198 ms: 1.00x slower                                    |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.17 ms: 1.00x slower                                   |
| richards_super           | 34.9 ms                                                | 35.0 ms: 1.00x slower                                   |
| deepcopy_reduce          | 2.02 us                                                | 2.03 us: 1.00x slower                                   |
| unpickle                 | 9.26 us                                                | 9.30 us: 1.00x slower                                   |
| comprehensions           | 15.7 us                                                | 15.8 us: 1.00x slower                                   |
| deepcopy                 | 224 us                                                 | 225 us: 1.00x slower                                    |
| sqlite_synth             | 1.58 us                                                | 1.59 us: 1.01x slower                                   |
| deepcopy_memo            | 24.5 us                                                | 24.6 us: 1.01x slower                                   |
| async_generators         | 303 ms                                                 | 305 ms: 1.01x slower                                    |
| pickle_pure_python       | 188 us                                                 | 190 us: 1.01x slower                                    |
| bench_mp_pool            | 45.9 ms                                                | 46.3 ms: 1.01x slower                                   |
| richards                 | 31.1 ms                                                | 31.4 ms: 1.01x slower                                   |
| unpickle_list            | 3.22 us                                                | 3.29 us: 1.02x slower                                   |
| python_startup           | 11.5 ms                                                | 11.8 ms: 1.03x slower                                   |
| python_startup_no_site   | 9.43 ms                                                | 9.69 ms: 1.03x slower                                   |
| pathlib                  | 28.8 ms                                                | 32.3 ms: 1.12x slower                                   |
| dask                     | 228 ms                                                 | 323 ms: 1.42x slower                                    |
| Geometric mean           | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (25): asyncio_tcp, mypy2, async_tree_cpu_io_mixed, mdp, xml_etree_iterparse, coverage, pickle, json, logging_format, json_loads, chaos, xml_etree_generate, spectral_norm, sqlalchemy_imperative, async_tree_io, pickle_dict, scimark_sor, xml_etree_process, sqlglot_parse, deltablue, unpack_sequence, sqlglot_transpile, tornado_http, hexiom, xml_etree_parse


# HPT report

- Reliability score: 99.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
