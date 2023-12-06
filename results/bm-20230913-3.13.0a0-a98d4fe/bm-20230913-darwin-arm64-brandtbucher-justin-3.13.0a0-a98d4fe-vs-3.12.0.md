
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.01x slower
- HPT reliability: 99.63%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                        |
| Geometric mean | (ref)                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| float          | 58.2 ms                                                | 56.8 ms: 1.02x faster                                         |
| nbody          | 68.6 ms                                                | 82.4 ms: 1.20x slower                                         |
| Geometric mean | (ref)                                                  | 1.05x slower                                                  |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 140 ms: 1.08x faster                                          |
| regex_effbot   | 2.58 ms                                                | 2.50 ms: 1.03x faster                                         |
| regex_v8       | 16.0 ms                                                | 16.4 ms: 1.03x slower                                         |
| regex_compile  | 75.8 ms                                                | 82.1 ms: 1.08x slower                                         |
| Geometric mean | (ref)                                                  | 1.00x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.87 us: 1.02x faster                                         |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                         |
| json_loads           | 17.6 us                                                | 17.5 us: 1.01x faster                                         |
| unpickle             | 9.26 us                                                | 9.21 us: 1.01x faster                                         |
| json_dumps           | 6.43 ms                                                | 6.47 ms: 1.01x slower                                         |
| tomli_loads          | 1.39 sec                                               | 1.41 sec: 1.01x slower                                        |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                          |
| xml_etree_process    | 38.5 ms                                                | 39.4 ms: 1.02x slower                                         |
| xml_etree_iterparse  | 74.3 ms                                                | 76.8 ms: 1.03x slower                                         |
| xml_etree_generate   | 55.8 ms                                                | 57.7 ms: 1.04x slower                                         |
| pickle_pure_python   | 188 us                                                 | 196 us: 1.04x slower                                          |
| unpickle_pure_python | 145 us                                                 | 165 us: 1.14x slower                                          |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                  |

Benchmark hidden because not significant (2): pickle, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.45 ms: 1.00x slower                                         |
| python_startup         | 11.5 ms                                                | 12.1 ms: 1.05x slower                                         |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.67 ms: 1.01x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 179 ms: 1.37x faster                                          |
| mypy2                    | 259 ms                                                 | 196 ms: 1.32x faster                                          |
| generators               | 28.5 ms                                                | 24.9 ms: 1.14x faster                                         |
| sqlglot_parse            | 898 us                                                 | 808 us: 1.11x faster                                          |
| scimark_monte_carlo      | 50.1 ms                                                | 46.0 ms: 1.09x faster                                         |
| sqlglot_transpile        | 1.07 ms                                                | 987 us: 1.09x faster                                          |
| coverage                 | 51.0 ms                                                | 47.0 ms: 1.09x faster                                         |
| regex_dna                | 151 ms                                                 | 140 ms: 1.08x faster                                          |
| unpack_sequence          | 28.8 ns                                                | 27.0 ns: 1.07x faster                                         |
| chaos                    | 45.2 ms                                                | 42.5 ms: 1.06x faster                                         |
| crypto_pyaes             | 52.3 ms                                                | 49.1 ms: 1.06x faster                                         |
| async_tree_none          | 262 ms                                                 | 252 ms: 1.04x faster                                          |
| deltablue                | 2.59 ms                                                | 2.51 ms: 1.03x faster                                         |
| regex_effbot             | 2.58 ms                                                | 2.50 ms: 1.03x faster                                         |
| logging_simple           | 3.69 us                                                | 3.59 us: 1.03x faster                                         |
| spectral_norm            | 75.0 ms                                                | 73.1 ms: 1.03x faster                                         |
| logging_format           | 3.97 us                                                | 3.87 us: 1.03x faster                                         |
| float                    | 58.2 ms                                                | 56.8 ms: 1.02x faster                                         |
| pickle_list              | 2.92 us                                                | 2.87 us: 1.02x faster                                         |
| json                     | 3.05 ms                                                | 3.00 ms: 1.02x faster                                         |
| coroutines               | 18.2 ms                                                | 17.9 ms: 1.02x faster                                         |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                         |
| docutils                 | 1.54 sec                                               | 1.53 sec: 1.01x faster                                        |
| json_loads               | 17.6 us                                                | 17.5 us: 1.01x faster                                         |
| unpickle                 | 9.26 us                                                | 9.21 us: 1.01x faster                                         |
| gc_traversal             | 2.40 ms                                                | 2.41 ms: 1.00x slower                                         |
| python_startup_no_site   | 9.43 ms                                                | 9.45 ms: 1.00x slower                                         |
| bench_thread_pool        | 489 us                                                 | 492 us: 1.01x slower                                          |
| create_gc_cycles         | 702 us                                                 | 707 us: 1.01x slower                                          |
| json_dumps               | 6.43 ms                                                | 6.47 ms: 1.01x slower                                         |
| sqlite_synth             | 1.58 us                                                | 1.60 us: 1.01x slower                                         |
| tomli_loads              | 1.39 sec                                               | 1.41 sec: 1.01x slower                                        |
| sqlglot_optimize         | 34.3 ms                                                | 34.6 ms: 1.01x slower                                         |
| deepcopy                 | 224 us                                                 | 226 us: 1.01x slower                                          |
| mako                     | 7.57 ms                                                | 7.67 ms: 1.01x slower                                         |
| go                       | 107 ms                                                 | 109 ms: 1.01x slower                                          |
| scimark_lu               | 71.7 ms                                                | 72.7 ms: 1.01x slower                                         |
| dulwich_log              | 30.3 ms                                                | 30.8 ms: 1.02x slower                                         |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.28 sec: 1.02x slower                                        |
| xml_etree_parse          | 109 ms                                                 | 111 ms: 1.02x slower                                          |
| xml_etree_process        | 38.5 ms                                                | 39.4 ms: 1.02x slower                                         |
| pprint_safe_repr         | 493 ms                                                 | 504 ms: 1.02x slower                                          |
| pprint_pformat           | 1.00 sec                                               | 1.03 sec: 1.02x slower                                        |
| async_generators         | 303 ms                                                 | 311 ms: 1.03x slower                                          |
| regex_v8                 | 16.0 ms                                                | 16.4 ms: 1.03x slower                                         |
| pyflate                  | 329 ms                                                 | 338 ms: 1.03x slower                                          |
| pycparser                | 670 ms                                                 | 692 ms: 1.03x slower                                          |
| xml_etree_iterparse      | 74.3 ms                                                | 76.8 ms: 1.03x slower                                         |
| xml_etree_generate       | 55.8 ms                                                | 57.7 ms: 1.04x slower                                         |
| typing_runtime_protocols | 90.7 us                                                | 94.0 us: 1.04x slower                                         |
| bench_mp_pool            | 45.9 ms                                                | 47.6 ms: 1.04x slower                                         |
| async_tree_io            | 669 ms                                                 | 697 ms: 1.04x slower                                          |
| pickle_pure_python       | 188 us                                                 | 196 us: 1.04x slower                                          |
| python_startup           | 11.5 ms                                                | 12.1 ms: 1.05x slower                                         |
| logging_silent           | 67.7 ns                                                | 71.1 ns: 1.05x slower                                         |
| deepcopy_memo            | 24.5 us                                                | 25.9 us: 1.06x slower                                         |
| meteor_contest           | 72.9 ms                                                | 77.2 ms: 1.06x slower                                         |
| async_tree_memoization   | 309 ms                                                 | 328 ms: 1.06x slower                                          |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.35 ms: 1.06x slower                                         |
| nqueens                  | 60.6 ms                                                | 64.4 ms: 1.06x slower                                         |
| comprehensions           | 15.7 us                                                | 16.8 us: 1.07x slower                                         |
| richards_super           | 34.9 ms                                                | 37.7 ms: 1.08x slower                                         |
| regex_compile            | 75.8 ms                                                | 82.1 ms: 1.08x slower                                         |
| fannkuch                 | 267 ms                                                 | 291 ms: 1.09x slower                                          |
| richards                 | 31.1 ms                                                | 34.0 ms: 1.09x slower                                         |
| scimark_fft              | 198 ms                                                 | 221 ms: 1.12x slower                                          |
| pathlib                  | 28.8 ms                                                | 32.5 ms: 1.13x slower                                         |
| scimark_sor              | 94.1 ms                                                | 106 ms: 1.13x slower                                          |
| unpickle_pure_python     | 145 us                                                 | 165 us: 1.14x slower                                          |
| nbody                    | 68.6 ms                                                | 82.4 ms: 1.20x slower                                         |
| hexiom                   | 4.24 ms                                                | 5.15 ms: 1.22x slower                                         |
| telco                    | 3.82 ms                                                | 4.71 ms: 1.23x slower                                         |
| dask                     | 228 ms                                                 | 333 ms: 1.46x slower                                          |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (9): asyncio_tcp, async_tree_cpu_io_mixed, mdp, sqlglot_normalize, pickle, pidigits, deepcopy_reduce, unpickle_list, tornado_http
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.63% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
