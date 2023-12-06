
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.01x faster
- HPT reliability: 52.49%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.48 sec: 1.04x faster                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 58.2 ms                                                | 55.4 ms: 1.05x faster                                 |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                  |
| nbody          | 68.6 ms                                                | 70.9 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 140 ms: 1.08x faster                                  |
| regex_effbot   | 2.58 ms                                                | 2.50 ms: 1.03x faster                                 |
| regex_compile  | 75.8 ms                                                | 77.1 ms: 1.02x slower                                 |
| regex_v8       | 16.0 ms                                                | 16.4 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.88 us: 1.02x faster                                 |
| unpickle             | 9.26 us                                                | 9.12 us: 1.01x faster                                 |
| pickle_dict          | 18.0 us                                                | 17.8 us: 1.01x faster                                 |
| json_loads           | 17.6 us                                                | 17.4 us: 1.01x faster                                 |
| pickle               | 7.45 us                                                | 7.39 us: 1.01x faster                                 |
| json_dumps           | 6.43 ms                                                | 6.48 ms: 1.01x slower                                 |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                  |
| xml_etree_process    | 38.5 ms                                                | 39.1 ms: 1.02x slower                                 |
| xml_etree_iterparse  | 74.3 ms                                                | 75.8 ms: 1.02x slower                                 |
| xml_etree_generate   | 55.8 ms                                                | 57.1 ms: 1.02x slower                                 |
| pickle_pure_python   | 188 us                                                 | 194 us: 1.03x slower                                  |
| unpickle_pure_python | 145 us                                                 | 158 us: 1.09x slower                                  |
| tomli_loads          | 1.39 sec                                               | 1.54 sec: 1.10x slower                                |
| Geometric mean       | (ref)                                                  | 1.02x slower                                          |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.56 ms: 1.01x slower                                 |
| python_startup         | 11.5 ms                                                | 12.2 ms: 1.06x slower                                 |
| Geometric mean         | (ref)                                                  | 1.04x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.28 ms: 1.04x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 178 ms: 1.39x faster                                  |
| mypy2                    | 259 ms                                                 | 190 ms: 1.37x faster                                  |
| generators               | 28.5 ms                                                | 24.5 ms: 1.16x faster                                 |
| asyncio_tcp              | 460 ms                                                 | 404 ms: 1.14x faster                                  |
| sqlglot_parse            | 898 us                                                 | 802 us: 1.12x faster                                  |
| crypto_pyaes             | 52.3 ms                                                | 46.8 ms: 1.12x faster                                 |
| chaos                    | 45.2 ms                                                | 40.6 ms: 1.11x faster                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 45.1 ms: 1.11x faster                                 |
| unpack_sequence          | 28.8 ns                                                | 26.2 ns: 1.10x faster                                 |
| sqlglot_transpile        | 1.07 ms                                                | 977 us: 1.10x faster                                  |
| coverage                 | 51.0 ms                                                | 46.6 ms: 1.09x faster                                 |
| regex_dna                | 151 ms                                                 | 140 ms: 1.08x faster                                  |
| comprehensions           | 15.7 us                                                | 14.6 us: 1.07x faster                                 |
| deltablue                | 2.59 ms                                                | 2.42 ms: 1.07x faster                                 |
| float                    | 58.2 ms                                                | 55.4 ms: 1.05x faster                                 |
| async_tree_none          | 262 ms                                                 | 250 ms: 1.05x faster                                  |
| spectral_norm            | 75.0 ms                                                | 71.7 ms: 1.05x faster                                 |
| mako                     | 7.57 ms                                                | 7.28 ms: 1.04x faster                                 |
| mdp                      | 1.68 sec                                               | 1.61 sec: 1.04x faster                                |
| docutils                 | 1.54 sec                                               | 1.48 sec: 1.04x faster                                |
| nqueens                  | 60.6 ms                                                | 58.5 ms: 1.04x faster                                 |
| regex_effbot             | 2.58 ms                                                | 2.50 ms: 1.03x faster                                 |
| logging_simple           | 3.69 us                                                | 3.59 us: 1.03x faster                                 |
| logging_format           | 3.97 us                                                | 3.88 us: 1.02x faster                                 |
| go                       | 107 ms                                                 | 105 ms: 1.02x faster                                  |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.10 ms: 1.02x faster                                 |
| bench_thread_pool        | 489 us                                                 | 481 us: 1.02x faster                                  |
| pickle_list              | 2.92 us                                                | 2.88 us: 1.02x faster                                 |
| unpickle                 | 9.26 us                                                | 9.12 us: 1.01x faster                                 |
| json                     | 3.05 ms                                                | 3.01 ms: 1.01x faster                                 |
| coroutines               | 18.2 ms                                                | 18.0 ms: 1.01x faster                                 |
| async_tree_cpu_io_mixed  | 526 ms                                                 | 521 ms: 1.01x faster                                  |
| pickle_dict              | 18.0 us                                                | 17.8 us: 1.01x faster                                 |
| json_loads               | 17.6 us                                                | 17.4 us: 1.01x faster                                 |
| pickle                   | 7.45 us                                                | 7.39 us: 1.01x faster                                 |
| sqlglot_normalize        | 186 ms                                                 | 185 ms: 1.00x faster                                  |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                  |
| deepcopy_memo            | 24.5 us                                                | 24.4 us: 1.00x faster                                 |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                 |
| async_generators         | 303 ms                                                 | 304 ms: 1.00x slower                                  |
| deepcopy_reduce          | 2.02 us                                                | 2.03 us: 1.01x slower                                 |
| deepcopy                 | 224 us                                                 | 225 us: 1.01x slower                                  |
| dulwich_log              | 30.3 ms                                                | 30.5 ms: 1.01x slower                                 |
| json_dumps               | 6.43 ms                                                | 6.48 ms: 1.01x slower                                 |
| xml_etree_parse          | 109 ms                                                 | 110 ms: 1.01x slower                                  |
| meteor_contest           | 72.9 ms                                                | 73.8 ms: 1.01x slower                                 |
| python_startup_no_site   | 9.43 ms                                                | 9.56 ms: 1.01x slower                                 |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.28 sec: 1.02x slower                                |
| xml_etree_process        | 38.5 ms                                                | 39.1 ms: 1.02x slower                                 |
| pprint_pformat           | 1.00 sec                                               | 1.02 sec: 1.02x slower                                |
| regex_compile            | 75.8 ms                                                | 77.1 ms: 1.02x slower                                 |
| bench_mp_pool            | 45.9 ms                                                | 46.7 ms: 1.02x slower                                 |
| typing_runtime_protocols | 90.7 us                                                | 92.4 us: 1.02x slower                                 |
| xml_etree_iterparse      | 74.3 ms                                                | 75.8 ms: 1.02x slower                                 |
| pprint_safe_repr         | 493 ms                                                 | 504 ms: 1.02x slower                                  |
| pycparser                | 670 ms                                                 | 686 ms: 1.02x slower                                  |
| xml_etree_generate       | 55.8 ms                                                | 57.1 ms: 1.02x slower                                 |
| regex_v8                 | 16.0 ms                                                | 16.4 ms: 1.02x slower                                 |
| pickle_pure_python       | 188 us                                                 | 194 us: 1.03x slower                                  |
| nbody                    | 68.6 ms                                                | 70.9 ms: 1.03x slower                                 |
| async_tree_io            | 669 ms                                                 | 695 ms: 1.04x slower                                  |
| logging_silent           | 67.7 ns                                                | 70.6 ns: 1.04x slower                                 |
| pyflate                  | 329 ms                                                 | 345 ms: 1.05x slower                                  |
| async_tree_memoization   | 309 ms                                                 | 326 ms: 1.05x slower                                  |
| python_startup           | 11.5 ms                                                | 12.2 ms: 1.06x slower                                 |
| richards_super           | 34.9 ms                                                | 37.5 ms: 1.08x slower                                 |
| fannkuch                 | 267 ms                                                 | 289 ms: 1.08x slower                                  |
| richards                 | 31.1 ms                                                | 33.9 ms: 1.09x slower                                 |
| unpickle_pure_python     | 145 us                                                 | 158 us: 1.09x slower                                  |
| tomli_loads              | 1.39 sec                                               | 1.54 sec: 1.10x slower                                |
| hexiom                   | 4.24 ms                                                | 4.68 ms: 1.11x slower                                 |
| scimark_sor              | 94.1 ms                                                | 106 ms: 1.13x slower                                  |
| pathlib                  | 28.8 ms                                                | 32.8 ms: 1.14x slower                                 |
| telco                    | 3.82 ms                                                | 4.68 ms: 1.23x slower                                 |
| dask                     | 228 ms                                                 | 332 ms: 1.46x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (7): sqlglot_optimize, scimark_fft, sqlite_synth, unpickle_list, create_gc_cycles, tornado_http, scimark_lu
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 52.49% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
