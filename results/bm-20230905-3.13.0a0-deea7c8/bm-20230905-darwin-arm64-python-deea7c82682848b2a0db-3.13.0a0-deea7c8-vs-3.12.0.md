
# Results vs. 3.12.0

- fork: python
- ref: deea7c82682848b2a0db
- machine: darwin-arm64
- commit hash: deea7c8
- commit date: 2023-09-05
- overall geometric mean: 1.00x faster
- HPT reliability: 65.03%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.49 sec: 1.03x faster                                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.2 ms                                                | 55.4 ms: 1.05x faster                                                 |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                  |
| nbody          | 68.6 ms                                                | 71.4 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                  | 1.00x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 140 ms: 1.08x faster                                                  |
| regex_effbot   | 2.58 ms                                                | 2.51 ms: 1.03x faster                                                 |
| regex_v8       | 16.0 ms                                                | 16.2 ms: 1.01x slower                                                 |
| regex_compile  | 75.8 ms                                                | 77.1 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.85 us: 1.02x faster                                                 |
| unpickle_list        | 3.22 us                                                | 3.14 us: 1.02x faster                                                 |
| unpickle             | 9.26 us                                                | 9.11 us: 1.02x faster                                                 |
| json_loads           | 17.6 us                                                | 17.4 us: 1.01x faster                                                 |
| pickle_dict          | 18.0 us                                                | 18.0 us: 1.00x faster                                                 |
| xml_etree_iterparse  | 74.3 ms                                                | 75.4 ms: 1.01x slower                                                 |
| pickle_pure_python   | 188 us                                                 | 192 us: 1.02x slower                                                  |
| xml_etree_process    | 38.5 ms                                                | 39.4 ms: 1.02x slower                                                 |
| xml_etree_generate   | 55.8 ms                                                | 57.5 ms: 1.03x slower                                                 |
| unpickle_pure_python | 145 us                                                 | 158 us: 1.09x slower                                                  |
| tomli_loads          | 1.39 sec                                               | 1.54 sec: 1.11x slower                                                |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                          |

Benchmark hidden because not significant (3): xml_etree_parse, json_dumps, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.73 ms: 1.03x slower                                                 |
| python_startup         | 11.5 ms                                                | 11.9 ms: 1.03x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.37 ms: 1.03x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 178 ms: 1.39x faster                                                  |
| generators               | 28.5 ms                                                | 24.5 ms: 1.16x faster                                                 |
| sqlglot_parse            | 898 us                                                 | 803 us: 1.12x faster                                                  |
| chaos                    | 45.2 ms                                                | 40.5 ms: 1.12x faster                                                 |
| crypto_pyaes             | 52.3 ms                                                | 47.0 ms: 1.11x faster                                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 45.3 ms: 1.11x faster                                                 |
| sqlglot_transpile        | 1.07 ms                                                | 979 us: 1.10x faster                                                  |
| unpack_sequence          | 28.8 ns                                                | 26.4 ns: 1.09x faster                                                 |
| regex_dna                | 151 ms                                                 | 140 ms: 1.08x faster                                                  |
| comprehensions           | 15.7 us                                                | 14.7 us: 1.07x faster                                                 |
| coverage                 | 51.0 ms                                                | 47.8 ms: 1.07x faster                                                 |
| deltablue                | 2.59 ms                                                | 2.43 ms: 1.07x faster                                                 |
| spectral_norm            | 75.0 ms                                                | 71.4 ms: 1.05x faster                                                 |
| float                    | 58.2 ms                                                | 55.4 ms: 1.05x faster                                                 |
| async_tree_none          | 262 ms                                                 | 251 ms: 1.05x faster                                                  |
| mdp                      | 1.68 sec                                               | 1.61 sec: 1.04x faster                                                |
| nqueens                  | 60.6 ms                                                | 58.5 ms: 1.04x faster                                                 |
| regex_effbot             | 2.58 ms                                                | 2.51 ms: 1.03x faster                                                 |
| docutils                 | 1.54 sec                                               | 1.49 sec: 1.03x faster                                                |
| mako                     | 7.57 ms                                                | 7.37 ms: 1.03x faster                                                 |
| pickle_list              | 2.92 us                                                | 2.85 us: 1.02x faster                                                 |
| logging_simple           | 3.69 us                                                | 3.60 us: 1.02x faster                                                 |
| unpickle_list            | 3.22 us                                                | 3.14 us: 1.02x faster                                                 |
| logging_format           | 3.97 us                                                | 3.88 us: 1.02x faster                                                 |
| go                       | 107 ms                                                 | 105 ms: 1.02x faster                                                  |
| json                     | 3.05 ms                                                | 2.99 ms: 1.02x faster                                                 |
| coroutines               | 18.2 ms                                                | 17.9 ms: 1.02x faster                                                 |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.10 ms: 1.02x faster                                                 |
| bench_thread_pool        | 489 us                                                 | 481 us: 1.02x faster                                                  |
| unpickle                 | 9.26 us                                                | 9.11 us: 1.02x faster                                                 |
| scimark_lu               | 71.7 ms                                                | 70.7 ms: 1.01x faster                                                 |
| deepcopy_memo            | 24.5 us                                                | 24.2 us: 1.01x faster                                                 |
| create_gc_cycles         | 702 us                                                 | 694 us: 1.01x faster                                                  |
| json_loads               | 17.6 us                                                | 17.4 us: 1.01x faster                                                 |
| deepcopy_reduce          | 2.02 us                                                | 2.01 us: 1.01x faster                                                 |
| sqlglot_optimize         | 34.3 ms                                                | 34.2 ms: 1.00x faster                                                 |
| gc_traversal             | 2.40 ms                                                | 2.39 ms: 1.00x faster                                                 |
| pickle_dict              | 18.0 us                                                | 18.0 us: 1.00x faster                                                 |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                                  |
| sqlite_synth             | 1.58 us                                                | 1.59 us: 1.00x slower                                                 |
| sqlglot_normalize        | 186 ms                                                 | 187 ms: 1.01x slower                                                  |
| scimark_fft              | 198 ms                                                 | 200 ms: 1.01x slower                                                  |
| dulwich_log              | 30.3 ms                                                | 30.6 ms: 1.01x slower                                                 |
| async_generators         | 303 ms                                                 | 306 ms: 1.01x slower                                                  |
| pprint_pformat           | 1.00 sec                                               | 1.01 sec: 1.01x slower                                                |
| deepcopy                 | 224 us                                                 | 226 us: 1.01x slower                                                  |
| pprint_safe_repr         | 493 ms                                                 | 500 ms: 1.01x slower                                                  |
| regex_v8                 | 16.0 ms                                                | 16.2 ms: 1.01x slower                                                 |
| xml_etree_iterparse      | 74.3 ms                                                | 75.4 ms: 1.01x slower                                                 |
| meteor_contest           | 72.9 ms                                                | 74.1 ms: 1.02x slower                                                 |
| regex_compile            | 75.8 ms                                                | 77.1 ms: 1.02x slower                                                 |
| typing_runtime_protocols | 90.7 us                                                | 92.4 us: 1.02x slower                                                 |
| pickle_pure_python       | 188 us                                                 | 192 us: 1.02x slower                                                  |
| xml_etree_process        | 38.5 ms                                                | 39.4 ms: 1.02x slower                                                 |
| async_tree_io            | 669 ms                                                 | 684 ms: 1.02x slower                                                  |
| xml_etree_generate       | 55.8 ms                                                | 57.5 ms: 1.03x slower                                                 |
| pycparser                | 670 ms                                                 | 690 ms: 1.03x slower                                                  |
| python_startup_no_site   | 9.43 ms                                                | 9.73 ms: 1.03x slower                                                 |
| python_startup           | 11.5 ms                                                | 11.9 ms: 1.03x slower                                                 |
| nbody                    | 68.6 ms                                                | 71.4 ms: 1.04x slower                                                 |
| pyflate                  | 329 ms                                                 | 343 ms: 1.04x slower                                                  |
| logging_silent           | 67.7 ns                                                | 71.6 ns: 1.06x slower                                                 |
| async_tree_memoization   | 309 ms                                                 | 328 ms: 1.06x slower                                                  |
| fannkuch                 | 267 ms                                                 | 283 ms: 1.06x slower                                                  |
| richards_super           | 34.9 ms                                                | 37.4 ms: 1.07x slower                                                 |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.36 sec: 1.08x slower                                                |
| unpickle_pure_python     | 145 us                                                 | 158 us: 1.09x slower                                                  |
| richards                 | 31.1 ms                                                | 34.0 ms: 1.09x slower                                                 |
| tomli_loads              | 1.39 sec                                               | 1.54 sec: 1.11x slower                                                |
| pathlib                  | 28.8 ms                                                | 32.1 ms: 1.11x slower                                                 |
| hexiom                   | 4.24 ms                                                | 4.73 ms: 1.12x slower                                                 |
| scimark_sor              | 94.1 ms                                                | 106 ms: 1.12x slower                                                  |
| telco                    | 3.82 ms                                                | 4.65 ms: 1.22x slower                                                 |
| dask                     | 228 ms                                                 | 331 ms: 1.45x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                          |

Benchmark hidden because not significant (8): asyncio_tcp, mypy2, tornado_http, async_tree_cpu_io_mixed, xml_etree_parse, json_dumps, pickle, bench_mp_pool
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 65.03% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
