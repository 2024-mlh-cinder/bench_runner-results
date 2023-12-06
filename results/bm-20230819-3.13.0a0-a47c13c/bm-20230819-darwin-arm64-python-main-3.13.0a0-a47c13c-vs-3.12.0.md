
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: a47c13c
- commit date: 2023-08-19
- overall geometric mean: 1.02x slower
- HPT reliability: 98.45%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-darwin-arm64-python-main-3.13.0a0-a47c13c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-darwin-arm64-python-main-3.13.0a0-a47c13c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 58.2 ms                                                | 56.4 ms: 1.03x faster                                 |
| pidigits       | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| nbody          | 68.6 ms                                                | 72.3 ms: 1.05x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-darwin-arm64-python-main-3.13.0a0-a47c13c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 149 ms: 1.02x faster                                  |
| regex_effbot   | 2.58 ms                                                | 2.57 ms: 1.01x faster                                 |
| regex_compile  | 75.8 ms                                                | 79.1 ms: 1.04x slower                                 |
| regex_v8       | 16.0 ms                                                | 17.0 ms: 1.06x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-darwin-arm64-python-main-3.13.0a0-a47c13c |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 3.14 us: 1.02x faster                                 |
| json_loads           | 17.6 us                                                | 17.4 us: 1.01x faster                                 |
| unpickle             | 9.26 us                                                | 9.17 us: 1.01x faster                                 |
| pickle_list          | 2.92 us                                                | 2.90 us: 1.01x faster                                 |
| pickle               | 7.45 us                                                | 7.41 us: 1.01x faster                                 |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                 |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                  |
| json_dumps           | 6.43 ms                                                | 6.58 ms: 1.02x slower                                 |
| xml_etree_iterparse  | 74.3 ms                                                | 76.5 ms: 1.03x slower                                 |
| pickle_pure_python   | 188 us                                                 | 198 us: 1.05x slower                                  |
| xml_etree_process    | 38.5 ms                                                | 40.7 ms: 1.06x slower                                 |
| xml_etree_generate   | 55.8 ms                                                | 59.0 ms: 1.06x slower                                 |
| tomli_loads          | 1.39 sec                                               | 1.57 sec: 1.13x slower                                |
| unpickle_pure_python | 145 us                                                 | 163 us: 1.13x slower                                  |
| Geometric mean       | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-darwin-arm64-python-main-3.13.0a0-a47c13c |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.18 ms: 1.03x faster                                 |
| python_startup         | 11.5 ms                                                | 11.3 ms: 1.02x faster                                 |
| Geometric mean         | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-darwin-arm64-python-main-3.13.0a0-a47c13c |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.54 ms: 1.00x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-darwin-arm64-python-main-3.13.0a0-a47c13c |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 189 ms: 1.30x faster                                  |
| asyncio_tcp              | 460 ms                                                 | 405 ms: 1.14x faster                                  |
| crypto_pyaes             | 52.3 ms                                                | 47.9 ms: 1.09x faster                                 |
| sqlglot_parse            | 898 us                                                 | 827 us: 1.09x faster                                  |
| scimark_monte_carlo      | 50.1 ms                                                | 46.4 ms: 1.08x faster                                 |
| coverage                 | 51.0 ms                                                | 47.5 ms: 1.07x faster                                 |
| chaos                    | 45.2 ms                                                | 42.2 ms: 1.07x faster                                 |
| sqlglot_transpile        | 1.07 ms                                                | 1.01 ms: 1.07x faster                                 |
| unpack_sequence          | 28.8 ns                                                | 27.5 ns: 1.05x faster                                 |
| comprehensions           | 15.7 us                                                | 15.0 us: 1.04x faster                                 |
| float                    | 58.2 ms                                                | 56.4 ms: 1.03x faster                                 |
| python_startup_no_site   | 9.43 ms                                                | 9.18 ms: 1.03x faster                                 |
| nqueens                  | 60.6 ms                                                | 59.0 ms: 1.03x faster                                 |
| unpickle_list            | 3.22 us                                                | 3.14 us: 1.02x faster                                 |
| pathlib                  | 28.8 ms                                                | 28.2 ms: 1.02x faster                                 |
| mdp                      | 1.68 sec                                               | 1.64 sec: 1.02x faster                                |
| async_tree_none          | 262 ms                                                 | 257 ms: 1.02x faster                                  |
| deltablue                | 2.59 ms                                                | 2.54 ms: 1.02x faster                                 |
| python_startup           | 11.5 ms                                                | 11.3 ms: 1.02x faster                                 |
| regex_dna                | 151 ms                                                 | 149 ms: 1.02x faster                                  |
| json                     | 3.05 ms                                                | 3.01 ms: 1.01x faster                                 |
| generators               | 28.5 ms                                                | 28.2 ms: 1.01x faster                                 |
| spectral_norm            | 75.0 ms                                                | 74.2 ms: 1.01x faster                                 |
| bench_mp_pool            | 45.9 ms                                                | 45.4 ms: 1.01x faster                                 |
| json_loads               | 17.6 us                                                | 17.4 us: 1.01x faster                                 |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.13 ms: 1.01x faster                                 |
| unpickle                 | 9.26 us                                                | 9.17 us: 1.01x faster                                 |
| pickle_list              | 2.92 us                                                | 2.90 us: 1.01x faster                                 |
| pickle                   | 7.45 us                                                | 7.41 us: 1.01x faster                                 |
| regex_effbot             | 2.58 ms                                                | 2.57 ms: 1.01x faster                                 |
| docutils                 | 1.54 sec                                               | 1.53 sec: 1.01x faster                                |
| create_gc_cycles         | 702 us                                                 | 698 us: 1.01x faster                                  |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.00x faster                                 |
| pidigits                 | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| mako                     | 7.57 ms                                                | 7.54 ms: 1.00x faster                                 |
| gc_traversal             | 2.40 ms                                                | 2.39 ms: 1.00x faster                                 |
| bench_thread_pool        | 489 us                                                 | 491 us: 1.00x slower                                  |
| go                       | 107 ms                                                 | 108 ms: 1.01x slower                                  |
| xml_etree_parse          | 109 ms                                                 | 110 ms: 1.01x slower                                  |
| async_generators         | 303 ms                                                 | 308 ms: 1.02x slower                                  |
| deepcopy_memo            | 24.5 us                                                | 24.9 us: 1.02x slower                                 |
| deepcopy_reduce          | 2.02 us                                                | 2.06 us: 1.02x slower                                 |
| meteor_contest           | 72.9 ms                                                | 74.5 ms: 1.02x slower                                 |
| scimark_fft              | 198 ms                                                 | 202 ms: 1.02x slower                                  |
| sqlite_synth             | 1.58 us                                                | 1.62 us: 1.02x slower                                 |
| json_dumps               | 6.43 ms                                                | 6.58 ms: 1.02x slower                                 |
| sqlglot_optimize         | 34.3 ms                                                | 35.2 ms: 1.03x slower                                 |
| dulwich_log              | 30.3 ms                                                | 31.1 ms: 1.03x slower                                 |
| deepcopy                 | 224 us                                                 | 230 us: 1.03x slower                                  |
| sqlglot_normalize        | 186 ms                                                 | 191 ms: 1.03x slower                                  |
| logging_simple           | 3.69 us                                                | 3.80 us: 1.03x slower                                 |
| xml_etree_iterparse      | 74.3 ms                                                | 76.5 ms: 1.03x slower                                 |
| logging_format           | 3.97 us                                                | 4.12 us: 1.04x slower                                 |
| typing_runtime_protocols | 90.7 us                                                | 94.1 us: 1.04x slower                                 |
| pprint_pformat           | 1.00 sec                                               | 1.04 sec: 1.04x slower                                |
| pprint_safe_repr         | 493 ms                                                 | 514 ms: 1.04x slower                                  |
| regex_compile            | 75.8 ms                                                | 79.1 ms: 1.04x slower                                 |
| pycparser                | 670 ms                                                 | 703 ms: 1.05x slower                                  |
| pickle_pure_python       | 188 us                                                 | 198 us: 1.05x slower                                  |
| nbody                    | 68.6 ms                                                | 72.3 ms: 1.05x slower                                 |
| xml_etree_process        | 38.5 ms                                                | 40.7 ms: 1.06x slower                                 |
| pyflate                  | 329 ms                                                 | 348 ms: 1.06x slower                                  |
| xml_etree_generate       | 55.8 ms                                                | 59.0 ms: 1.06x slower                                 |
| async_tree_io            | 669 ms                                                 | 709 ms: 1.06x slower                                  |
| regex_v8                 | 16.0 ms                                                | 17.0 ms: 1.06x slower                                 |
| scimark_lu               | 71.7 ms                                                | 76.2 ms: 1.06x slower                                 |
| coroutines               | 18.2 ms                                                | 19.4 ms: 1.07x slower                                 |
| fannkuch                 | 267 ms                                                 | 286 ms: 1.07x slower                                  |
| async_tree_memoization   | 309 ms                                                 | 332 ms: 1.07x slower                                  |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.36 sec: 1.08x slower                                |
| logging_silent           | 67.7 ns                                                | 73.6 ns: 1.09x slower                                 |
| tomli_loads              | 1.39 sec                                               | 1.57 sec: 1.13x slower                                |
| unpickle_pure_python     | 145 us                                                 | 163 us: 1.13x slower                                  |
| richards_super           | 34.9 ms                                                | 39.5 ms: 1.13x slower                                 |
| scimark_sor              | 94.1 ms                                                | 108 ms: 1.15x slower                                  |
| hexiom                   | 4.24 ms                                                | 4.87 ms: 1.15x slower                                 |
| richards                 | 31.1 ms                                                | 36.1 ms: 1.16x slower                                 |
| telco                    | 3.82 ms                                                | 4.57 ms: 1.20x slower                                 |
| dask                     | 228 ms                                                 | 337 ms: 1.48x slower                                  |
| Geometric mean           | (ref)                                                  | 1.02x slower                                          |

Benchmark hidden because not significant (3): async_tree_cpu_io_mixed, mypy2, tornado_http
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.45% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
