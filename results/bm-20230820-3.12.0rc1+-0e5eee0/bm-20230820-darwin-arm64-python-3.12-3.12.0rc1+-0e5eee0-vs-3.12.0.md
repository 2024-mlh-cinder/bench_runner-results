
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 0e5eee0
- commit date: 2023-08-20
- overall geometric mean: 1.01x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-darwin-arm64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 168 ms: 1.02x faster                                    |
| docutils       | 1.54 sec                                               | 1.49 sec: 1.03x faster                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-darwin-arm64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 58.2 ms                                                | 56.5 ms: 1.03x faster                                   |
| pidigits       | 282 ms                                                 | 281 ms: 1.00x faster                                    |
| nbody          | 68.6 ms                                                | 69.0 ms: 1.01x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-darwin-arm64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 16.0 ms                                                | 15.6 ms: 1.02x faster                                   |
| regex_effbot   | 2.58 ms                                                | 2.55 ms: 1.01x faster                                   |
| regex_dna      | 151 ms                                                 | 149 ms: 1.01x faster                                    |
| regex_compile  | 75.8 ms                                                | 75.6 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-darwin-arm64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle               | 7.45 us                                                | 7.28 us: 1.02x faster                                   |
| pickle_list          | 2.92 us                                                | 2.86 us: 1.02x faster                                   |
| json_dumps           | 6.43 ms                                                | 6.31 ms: 1.02x faster                                   |
| unpickle_list        | 3.22 us                                                | 3.19 us: 1.01x faster                                   |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                   |
| tomli_loads          | 1.39 sec                                               | 1.39 sec: 1.00x faster                                  |
| unpickle             | 9.26 us                                                | 9.22 us: 1.00x faster                                   |
| xml_etree_process    | 38.5 ms                                                | 38.7 ms: 1.00x slower                                   |
| xml_etree_iterparse  | 74.3 ms                                                | 74.7 ms: 1.01x slower                                   |
| unpickle_pure_python | 145 us                                                 | 145 us: 1.01x slower                                    |
| pickle_pure_python   | 188 us                                                 | 189 us: 1.01x slower                                    |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                    |
| Geometric mean       | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (2): json_loads, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-darwin-arm64-python-3.12-3.12.0rc1+-0e5eee0 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.19 ms: 1.03x faster                                   |
| python_startup         | 11.5 ms                                                | 11.3 ms: 1.02x faster                                   |
| Geometric mean         | (ref)                                                  | 1.02x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-darwin-arm64-python-3.12-3.12.0rc1+-0e5eee0 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.62 ms: 1.01x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-darwin-arm64-python-3.12-3.12.0rc1+-0e5eee0 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 208 ms: 1.18x faster                                    |
| scimark_monte_carlo      | 50.1 ms                                                | 43.3 ms: 1.16x faster                                   |
| go                       | 107 ms                                                 | 94.0 ms: 1.14x faster                                   |
| scimark_sor              | 94.1 ms                                                | 85.5 ms: 1.10x faster                                   |
| generators               | 28.5 ms                                                | 26.0 ms: 1.10x faster                                   |
| sqlglot_parse            | 898 us                                                 | 829 us: 1.08x faster                                    |
| chaos                    | 45.2 ms                                                | 41.9 ms: 1.08x faster                                   |
| deltablue                | 2.59 ms                                                | 2.41 ms: 1.08x faster                                   |
| pyflate                  | 329 ms                                                 | 307 ms: 1.07x faster                                    |
| sqlglot_transpile        | 1.07 ms                                                | 1.00 ms: 1.07x faster                                   |
| comprehensions           | 15.7 us                                                | 14.9 us: 1.05x faster                                   |
| coroutines               | 18.2 ms                                                | 17.4 ms: 1.05x faster                                   |
| logging_simple           | 3.69 us                                                | 3.58 us: 1.03x faster                                   |
| mdp                      | 1.68 sec                                               | 1.63 sec: 1.03x faster                                  |
| float                    | 58.2 ms                                                | 56.5 ms: 1.03x faster                                   |
| docutils                 | 1.54 sec                                               | 1.49 sec: 1.03x faster                                  |
| logging_format           | 3.97 us                                                | 3.87 us: 1.03x faster                                   |
| python_startup_no_site   | 9.43 ms                                                | 9.19 ms: 1.03x faster                                   |
| richards_super           | 34.9 ms                                                | 34.0 ms: 1.03x faster                                   |
| telco                    | 3.82 ms                                                | 3.73 ms: 1.02x faster                                   |
| regex_v8                 | 16.0 ms                                                | 15.6 ms: 1.02x faster                                   |
| async_tree_io            | 669 ms                                                 | 653 ms: 1.02x faster                                    |
| pickle                   | 7.45 us                                                | 7.28 us: 1.02x faster                                   |
| sqlalchemy_imperative    | 7.02 ms                                                | 6.87 ms: 1.02x faster                                   |
| richards                 | 31.1 ms                                                | 30.4 ms: 1.02x faster                                   |
| pickle_list              | 2.92 us                                                | 2.86 us: 1.02x faster                                   |
| nqueens                  | 60.6 ms                                                | 59.4 ms: 1.02x faster                                   |
| 2to3                     | 171 ms                                                 | 168 ms: 1.02x faster                                    |
| python_startup           | 11.5 ms                                                | 11.3 ms: 1.02x faster                                   |
| sqlalchemy_declarative   | 65.9 ms                                                | 64.7 ms: 1.02x faster                                   |
| json_dumps               | 6.43 ms                                                | 6.31 ms: 1.02x faster                                   |
| sqlglot_normalize        | 186 ms                                                 | 183 ms: 1.01x faster                                    |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.24 sec: 1.01x faster                                  |
| async_tree_cpu_io_mixed  | 526 ms                                                 | 520 ms: 1.01x faster                                    |
| regex_effbot             | 2.58 ms                                                | 2.55 ms: 1.01x faster                                   |
| coverage                 | 51.0 ms                                                | 50.5 ms: 1.01x faster                                   |
| unpickle_list            | 3.22 us                                                | 3.19 us: 1.01x faster                                   |
| regex_dna                | 151 ms                                                 | 149 ms: 1.01x faster                                    |
| sqlglot_optimize         | 34.3 ms                                                | 34.0 ms: 1.01x faster                                   |
| hexiom                   | 4.24 ms                                                | 4.20 ms: 1.01x faster                                   |
| crypto_pyaes             | 52.3 ms                                                | 51.8 ms: 1.01x faster                                   |
| async_tree_none          | 262 ms                                                 | 260 ms: 1.01x faster                                    |
| json                     | 3.05 ms                                                | 3.03 ms: 1.01x faster                                   |
| async_tree_memoization   | 309 ms                                                 | 307 ms: 1.01x faster                                    |
| dulwich_log              | 30.3 ms                                                | 30.1 ms: 1.01x faster                                   |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                   |
| pprint_safe_repr         | 493 ms                                                 | 490 ms: 1.01x faster                                    |
| pprint_pformat           | 1.00 sec                                               | 998 ms: 1.01x faster                                    |
| fannkuch                 | 267 ms                                                 | 265 ms: 1.01x faster                                    |
| spectral_norm            | 75.0 ms                                                | 74.6 ms: 1.01x faster                                   |
| tomli_loads              | 1.39 sec                                               | 1.39 sec: 1.00x faster                                  |
| typing_runtime_protocols | 90.7 us                                                | 90.3 us: 1.00x faster                                   |
| bench_thread_pool        | 489 us                                                 | 487 us: 1.00x faster                                    |
| gc_traversal             | 2.40 ms                                                | 2.39 ms: 1.00x faster                                   |
| create_gc_cycles         | 702 us                                                 | 699 us: 1.00x faster                                    |
| pidigits                 | 282 ms                                                 | 281 ms: 1.00x faster                                    |
| unpickle                 | 9.26 us                                                | 9.22 us: 1.00x faster                                   |
| regex_compile            | 75.8 ms                                                | 75.6 ms: 1.00x faster                                   |
| xml_etree_process        | 38.5 ms                                                | 38.7 ms: 1.00x slower                                   |
| deepcopy                 | 224 us                                                 | 224 us: 1.00x slower                                    |
| xml_etree_iterparse      | 74.3 ms                                                | 74.7 ms: 1.01x slower                                   |
| nbody                    | 68.6 ms                                                | 69.0 ms: 1.01x slower                                   |
| unpickle_pure_python     | 145 us                                                 | 145 us: 1.01x slower                                    |
| pickle_pure_python       | 188 us                                                 | 189 us: 1.01x slower                                    |
| mako                     | 7.57 ms                                                | 7.62 ms: 1.01x slower                                   |
| scimark_fft              | 198 ms                                                 | 199 ms: 1.01x slower                                    |
| logging_silent           | 67.7 ns                                                | 68.2 ns: 1.01x slower                                   |
| scimark_lu               | 71.7 ms                                                | 72.5 ms: 1.01x slower                                   |
| meteor_contest           | 72.9 ms                                                | 74.0 ms: 1.01x slower                                   |
| deepcopy_memo            | 24.5 us                                                | 24.8 us: 1.01x slower                                   |
| async_generators         | 303 ms                                                 | 307 ms: 1.02x slower                                    |
| deepcopy_reduce          | 2.02 us                                                | 2.05 us: 1.02x slower                                   |
| sqlite_synth             | 1.58 us                                                | 1.61 us: 1.02x slower                                   |
| xml_etree_parse          | 109 ms                                                 | 111 ms: 1.02x slower                                    |
| pathlib                  | 28.8 ms                                                | 29.9 ms: 1.04x slower                                   |
| dask                     | 228 ms                                                 | 316 ms: 1.39x slower                                    |
| Geometric mean           | (ref)                                                  | 1.01x faster                                            |

Benchmark hidden because not significant (9): mypy2, bench_mp_pool, pycparser, tornado_http, json_loads, xml_etree_generate, scimark_sparse_mat_mult, unpack_sequence, asyncio_tcp


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
