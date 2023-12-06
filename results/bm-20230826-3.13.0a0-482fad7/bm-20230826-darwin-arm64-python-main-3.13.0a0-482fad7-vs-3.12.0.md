
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 482fad7
- commit date: 2023-08-26
- overall geometric mean: 1.02x slower
- HPT reliability: 99.42%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.52 sec: 1.01x faster                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 58.2 ms                                                | 56.7 ms: 1.03x faster                                 |
| pidigits       | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| nbody          | 68.6 ms                                                | 72.0 ms: 1.05x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 149 ms: 1.01x faster                                  |
| regex_effbot   | 2.58 ms                                                | 2.57 ms: 1.00x faster                                 |
| regex_compile  | 75.8 ms                                                | 79.3 ms: 1.05x slower                                 |
| regex_v8       | 16.0 ms                                                | 17.0 ms: 1.06x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 3.19 us: 1.01x faster                                 |
| json_loads           | 17.6 us                                                | 17.5 us: 1.01x faster                                 |
| pickle               | 7.45 us                                                | 7.43 us: 1.00x faster                                 |
| unpickle             | 9.26 us                                                | 9.29 us: 1.00x slower                                 |
| json_dumps           | 6.43 ms                                                | 6.51 ms: 1.01x slower                                 |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                  |
| xml_etree_iterparse  | 74.3 ms                                                | 76.5 ms: 1.03x slower                                 |
| xml_etree_generate   | 55.8 ms                                                | 59.0 ms: 1.06x slower                                 |
| xml_etree_process    | 38.5 ms                                                | 40.9 ms: 1.06x slower                                 |
| pickle_pure_python   | 188 us                                                 | 200 us: 1.06x slower                                  |
| unpickle_pure_python | 145 us                                                 | 162 us: 1.12x slower                                  |
| tomli_loads          | 1.39 sec                                               | 1.56 sec: 1.12x slower                                |
| Geometric mean       | (ref)                                                  | 1.03x slower                                          |

Benchmark hidden because not significant (2): pickle_list, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.27 ms: 1.02x faster                                 |
| python_startup         | 11.5 ms                                                | 11.4 ms: 1.02x faster                                 |
| Geometric mean         | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.46 ms: 1.01x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 192 ms: 1.28x faster                                  |
| crypto_pyaes             | 52.3 ms                                                | 48.0 ms: 1.09x faster                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 46.4 ms: 1.08x faster                                 |
| sqlglot_parse            | 898 us                                                 | 834 us: 1.08x faster                                  |
| asyncio_tcp              | 460 ms                                                 | 428 ms: 1.07x faster                                  |
| chaos                    | 45.2 ms                                                | 42.2 ms: 1.07x faster                                 |
| sqlglot_transpile        | 1.07 ms                                                | 1.01 ms: 1.06x faster                                 |
| coverage                 | 51.0 ms                                                | 48.2 ms: 1.06x faster                                 |
| comprehensions           | 15.7 us                                                | 15.0 us: 1.04x faster                                 |
| unpack_sequence          | 28.8 ns                                                | 27.9 ns: 1.03x faster                                 |
| mdp                      | 1.68 sec                                               | 1.63 sec: 1.03x faster                                |
| async_tree_none          | 262 ms                                                 | 255 ms: 1.03x faster                                  |
| float                    | 58.2 ms                                                | 56.7 ms: 1.03x faster                                 |
| spectral_norm            | 75.0 ms                                                | 73.7 ms: 1.02x faster                                 |
| python_startup_no_site   | 9.43 ms                                                | 9.27 ms: 1.02x faster                                 |
| python_startup           | 11.5 ms                                                | 11.4 ms: 1.02x faster                                 |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.11 ms: 1.01x faster                                 |
| json                     | 3.05 ms                                                | 3.01 ms: 1.01x faster                                 |
| mako                     | 7.57 ms                                                | 7.46 ms: 1.01x faster                                 |
| deltablue                | 2.59 ms                                                | 2.56 ms: 1.01x faster                                 |
| docutils                 | 1.54 sec                                               | 1.52 sec: 1.01x faster                                |
| regex_dna                | 151 ms                                                 | 149 ms: 1.01x faster                                  |
| unpickle_list            | 3.22 us                                                | 3.19 us: 1.01x faster                                 |
| create_gc_cycles         | 702 us                                                 | 696 us: 1.01x faster                                  |
| nqueens                  | 60.6 ms                                                | 60.0 ms: 1.01x faster                                 |
| bench_mp_pool            | 45.9 ms                                                | 45.5 ms: 1.01x faster                                 |
| json_loads               | 17.6 us                                                | 17.5 us: 1.01x faster                                 |
| regex_effbot             | 2.58 ms                                                | 2.57 ms: 1.00x faster                                 |
| pidigits                 | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| pickle                   | 7.45 us                                                | 7.43 us: 1.00x faster                                 |
| gc_traversal             | 2.40 ms                                                | 2.39 ms: 1.00x faster                                 |
| unpickle                 | 9.26 us                                                | 9.29 us: 1.00x slower                                 |
| bench_thread_pool        | 489 us                                                 | 492 us: 1.01x slower                                  |
| json_dumps               | 6.43 ms                                                | 6.51 ms: 1.01x slower                                 |
| logging_format           | 3.97 us                                                | 4.04 us: 1.02x slower                                 |
| meteor_contest           | 72.9 ms                                                | 74.3 ms: 1.02x slower                                 |
| go                       | 107 ms                                                 | 109 ms: 1.02x slower                                  |
| xml_etree_parse          | 109 ms                                                 | 111 ms: 1.02x slower                                  |
| logging_simple           | 3.69 us                                                | 3.77 us: 1.02x slower                                 |
| scimark_fft              | 198 ms                                                 | 202 ms: 1.02x slower                                  |
| sqlite_synth             | 1.58 us                                                | 1.62 us: 1.02x slower                                 |
| deepcopy_memo            | 24.5 us                                                | 25.1 us: 1.02x slower                                 |
| dulwich_log              | 30.3 ms                                                | 31.1 ms: 1.03x slower                                 |
| sqlglot_optimize         | 34.3 ms                                                | 35.3 ms: 1.03x slower                                 |
| xml_etree_iterparse      | 74.3 ms                                                | 76.5 ms: 1.03x slower                                 |
| async_generators         | 303 ms                                                 | 312 ms: 1.03x slower                                  |
| sqlglot_normalize        | 186 ms                                                 | 192 ms: 1.03x slower                                  |
| deepcopy_reduce          | 2.02 us                                                | 2.09 us: 1.04x slower                                 |
| typing_runtime_protocols | 90.7 us                                                | 94.2 us: 1.04x slower                                 |
| deepcopy                 | 224 us                                                 | 232 us: 1.04x slower                                  |
| regex_compile            | 75.8 ms                                                | 79.3 ms: 1.05x slower                                 |
| pprint_pformat           | 1.00 sec                                               | 1.05 sec: 1.05x slower                                |
| nbody                    | 68.6 ms                                                | 72.0 ms: 1.05x slower                                 |
| pycparser                | 670 ms                                                 | 704 ms: 1.05x slower                                  |
| async_tree_io            | 669 ms                                                 | 705 ms: 1.05x slower                                  |
| scimark_lu               | 71.7 ms                                                | 75.8 ms: 1.06x slower                                 |
| xml_etree_generate       | 55.8 ms                                                | 59.0 ms: 1.06x slower                                 |
| xml_etree_process        | 38.5 ms                                                | 40.9 ms: 1.06x slower                                 |
| pickle_pure_python       | 188 us                                                 | 200 us: 1.06x slower                                  |
| regex_v8                 | 16.0 ms                                                | 17.0 ms: 1.06x slower                                 |
| pyflate                  | 329 ms                                                 | 350 ms: 1.06x slower                                  |
| pprint_safe_repr         | 493 ms                                                 | 525 ms: 1.06x slower                                  |
| async_tree_memoization   | 309 ms                                                 | 330 ms: 1.07x slower                                  |
| fannkuch                 | 267 ms                                                 | 287 ms: 1.07x slower                                  |
| coroutines               | 18.2 ms                                                | 19.7 ms: 1.08x slower                                 |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.36 sec: 1.08x slower                                |
| richards_super           | 34.9 ms                                                | 38.8 ms: 1.11x slower                                 |
| unpickle_pure_python     | 145 us                                                 | 162 us: 1.12x slower                                  |
| logging_silent           | 67.7 ns                                                | 75.7 ns: 1.12x slower                                 |
| tomli_loads              | 1.39 sec                                               | 1.56 sec: 1.12x slower                                |
| pathlib                  | 28.8 ms                                                | 32.6 ms: 1.13x slower                                 |
| richards                 | 31.1 ms                                                | 35.4 ms: 1.14x slower                                 |
| hexiom                   | 4.24 ms                                                | 4.88 ms: 1.15x slower                                 |
| scimark_sor              | 94.1 ms                                                | 109 ms: 1.15x slower                                  |
| telco                    | 3.82 ms                                                | 4.57 ms: 1.20x slower                                 |
| dask                     | 228 ms                                                 | 336 ms: 1.47x slower                                  |
| Geometric mean           | (ref)                                                  | 1.02x slower                                          |

Benchmark hidden because not significant (6): pickle_list, generators, async_tree_cpu_io_mixed, pickle_dict, mypy2, tornado_http
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.42% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
