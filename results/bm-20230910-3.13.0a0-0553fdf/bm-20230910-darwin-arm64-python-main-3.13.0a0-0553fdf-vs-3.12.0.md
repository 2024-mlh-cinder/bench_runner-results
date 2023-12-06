
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.01x faster
- HPT reliability: 68.22%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.50 sec: 1.03x faster                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 58.2 ms                                                | 55.2 ms: 1.05x faster                                 |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                  |
| nbody          | 68.6 ms                                                | 71.0 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 140 ms: 1.08x faster                                  |
| regex_effbot   | 2.58 ms                                                | 2.51 ms: 1.03x faster                                 |
| regex_compile  | 75.8 ms                                                | 77.3 ms: 1.02x slower                                 |
| regex_v8       | 16.0 ms                                                | 16.3 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.82 us: 1.04x faster                                 |
| unpickle_list        | 3.22 us                                                | 3.14 us: 1.03x faster                                 |
| unpickle             | 9.26 us                                                | 9.17 us: 1.01x faster                                 |
| json_loads           | 17.6 us                                                | 17.5 us: 1.01x faster                                 |
| pickle_dict          | 18.0 us                                                | 18.1 us: 1.00x slower                                 |
| json_dumps           | 6.43 ms                                                | 6.48 ms: 1.01x slower                                 |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                  |
| xml_etree_process    | 38.5 ms                                                | 39.0 ms: 1.01x slower                                 |
| xml_etree_iterparse  | 74.3 ms                                                | 75.4 ms: 1.01x slower                                 |
| xml_etree_generate   | 55.8 ms                                                | 57.2 ms: 1.03x slower                                 |
| pickle_pure_python   | 188 us                                                 | 194 us: 1.03x slower                                  |
| unpickle_pure_python | 145 us                                                 | 157 us: 1.09x slower                                  |
| tomli_loads          | 1.39 sec                                               | 1.54 sec: 1.11x slower                                |
| Geometric mean       | (ref)                                                  | 1.02x slower                                          |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.49 ms: 1.01x slower                                 |
| python_startup         | 11.5 ms                                                | 12.1 ms: 1.05x slower                                 |
| Geometric mean         | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.34 ms: 1.03x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-darwin-arm64-python-main-3.13.0a0-0553fdf |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 177 ms: 1.39x faster                                  |
| mypy2                    | 259 ms                                                 | 190 ms: 1.37x faster                                  |
| generators               | 28.5 ms                                                | 24.5 ms: 1.16x faster                                 |
| sqlglot_parse            | 898 us                                                 | 800 us: 1.12x faster                                  |
| crypto_pyaes             | 52.3 ms                                                | 46.8 ms: 1.12x faster                                 |
| chaos                    | 45.2 ms                                                | 40.6 ms: 1.11x faster                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 45.2 ms: 1.11x faster                                 |
| asyncio_tcp              | 460 ms                                                 | 415 ms: 1.11x faster                                  |
| sqlglot_transpile        | 1.07 ms                                                | 975 us: 1.10x faster                                  |
| unpack_sequence          | 28.8 ns                                                | 26.2 ns: 1.10x faster                                 |
| coverage                 | 51.0 ms                                                | 46.8 ms: 1.09x faster                                 |
| regex_dna                | 151 ms                                                 | 140 ms: 1.08x faster                                  |
| comprehensions           | 15.7 us                                                | 14.7 us: 1.07x faster                                 |
| deltablue                | 2.59 ms                                                | 2.45 ms: 1.06x faster                                 |
| float                    | 58.2 ms                                                | 55.2 ms: 1.05x faster                                 |
| spectral_norm            | 75.0 ms                                                | 71.4 ms: 1.05x faster                                 |
| async_tree_none          | 262 ms                                                 | 251 ms: 1.04x faster                                  |
| mdp                      | 1.68 sec                                               | 1.61 sec: 1.04x faster                                |
| pickle_list              | 2.92 us                                                | 2.82 us: 1.04x faster                                 |
| nqueens                  | 60.6 ms                                                | 58.7 ms: 1.03x faster                                 |
| mako                     | 7.57 ms                                                | 7.34 ms: 1.03x faster                                 |
| regex_effbot             | 2.58 ms                                                | 2.51 ms: 1.03x faster                                 |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.07 ms: 1.03x faster                                 |
| docutils                 | 1.54 sec                                               | 1.50 sec: 1.03x faster                                |
| unpickle_list            | 3.22 us                                                | 3.14 us: 1.03x faster                                 |
| logging_simple           | 3.69 us                                                | 3.61 us: 1.02x faster                                 |
| deepcopy_memo            | 24.5 us                                                | 24.0 us: 1.02x faster                                 |
| logging_format           | 3.97 us                                                | 3.90 us: 1.02x faster                                 |
| bench_thread_pool        | 489 us                                                 | 480 us: 1.02x faster                                  |
| go                       | 107 ms                                                 | 105 ms: 1.02x faster                                  |
| coroutines               | 18.2 ms                                                | 17.9 ms: 1.02x faster                                 |
| scimark_lu               | 71.7 ms                                                | 70.6 ms: 1.02x faster                                 |
| unpickle                 | 9.26 us                                                | 9.17 us: 1.01x faster                                 |
| sqlglot_optimize         | 34.3 ms                                                | 34.1 ms: 1.01x faster                                 |
| json_loads               | 17.6 us                                                | 17.5 us: 1.01x faster                                 |
| deepcopy_reduce          | 2.02 us                                                | 2.01 us: 1.00x faster                                 |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                  |
| scimark_fft              | 198 ms                                                 | 198 ms: 1.00x slower                                  |
| pickle_dict              | 18.0 us                                                | 18.1 us: 1.00x slower                                 |
| async_generators         | 303 ms                                                 | 304 ms: 1.00x slower                                  |
| sqlglot_normalize        | 186 ms                                                 | 187 ms: 1.00x slower                                  |
| meteor_contest           | 72.9 ms                                                | 73.3 ms: 1.01x slower                                 |
| python_startup_no_site   | 9.43 ms                                                | 9.49 ms: 1.01x slower                                 |
| sqlite_synth             | 1.58 us                                                | 1.60 us: 1.01x slower                                 |
| pprint_pformat           | 1.00 sec                                               | 1.01 sec: 1.01x slower                                |
| json_dumps               | 6.43 ms                                                | 6.48 ms: 1.01x slower                                 |
| pprint_safe_repr         | 493 ms                                                 | 498 ms: 1.01x slower                                  |
| xml_etree_parse          | 109 ms                                                 | 110 ms: 1.01x slower                                  |
| create_gc_cycles         | 702 us                                                 | 710 us: 1.01x slower                                  |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.27 sec: 1.01x slower                                |
| xml_etree_process        | 38.5 ms                                                | 39.0 ms: 1.01x slower                                 |
| xml_etree_iterparse      | 74.3 ms                                                | 75.4 ms: 1.01x slower                                 |
| bench_mp_pool            | 45.9 ms                                                | 46.6 ms: 1.02x slower                                 |
| json                     | 3.05 ms                                                | 3.10 ms: 1.02x slower                                 |
| dulwich_log              | 30.3 ms                                                | 30.8 ms: 1.02x slower                                 |
| typing_runtime_protocols | 90.7 us                                                | 92.4 us: 1.02x slower                                 |
| regex_compile            | 75.8 ms                                                | 77.3 ms: 1.02x slower                                 |
| regex_v8                 | 16.0 ms                                                | 16.3 ms: 1.02x slower                                 |
| xml_etree_generate       | 55.8 ms                                                | 57.2 ms: 1.03x slower                                 |
| pycparser                | 670 ms                                                 | 688 ms: 1.03x slower                                  |
| pickle_pure_python       | 188 us                                                 | 194 us: 1.03x slower                                  |
| nbody                    | 68.6 ms                                                | 71.0 ms: 1.03x slower                                 |
| pyflate                  | 329 ms                                                 | 341 ms: 1.04x slower                                  |
| async_tree_io            | 669 ms                                                 | 698 ms: 1.04x slower                                  |
| python_startup           | 11.5 ms                                                | 12.1 ms: 1.05x slower                                 |
| logging_silent           | 67.7 ns                                                | 71.5 ns: 1.06x slower                                 |
| async_tree_memoization   | 309 ms                                                 | 328 ms: 1.06x slower                                  |
| richards_super           | 34.9 ms                                                | 37.2 ms: 1.07x slower                                 |
| fannkuch                 | 267 ms                                                 | 285 ms: 1.07x slower                                  |
| richards                 | 31.1 ms                                                | 33.7 ms: 1.08x slower                                 |
| unpickle_pure_python     | 145 us                                                 | 157 us: 1.09x slower                                  |
| tomli_loads              | 1.39 sec                                               | 1.54 sec: 1.11x slower                                |
| hexiom                   | 4.24 ms                                                | 4.72 ms: 1.11x slower                                 |
| scimark_sor              | 94.1 ms                                                | 105 ms: 1.12x slower                                  |
| pathlib                  | 28.8 ms                                                | 33.0 ms: 1.14x slower                                 |
| telco                    | 3.82 ms                                                | 4.54 ms: 1.19x slower                                 |
| dask                     | 228 ms                                                 | 333 ms: 1.46x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed, pickle, deepcopy, gc_traversal, tornado_http
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 68.22% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
