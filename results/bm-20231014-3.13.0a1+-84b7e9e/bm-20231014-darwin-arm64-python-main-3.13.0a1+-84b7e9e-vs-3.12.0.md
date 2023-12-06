
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.01x faster
- HPT reliability: 62.83%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.48 sec: 1.04x faster                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 58.2 ms                                                | 54.7 ms: 1.06x faster                                  |
| nbody          | 68.6 ms                                                | 71.3 ms: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 149 ms: 1.01x faster                                   |
| regex_compile  | 75.8 ms                                                | 75.6 ms: 1.00x faster                                  |
| regex_v8       | 16.0 ms                                                | 16.8 ms: 1.05x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 3.15 us: 1.02x faster                                  |
| unpickle             | 9.26 us                                                | 9.05 us: 1.02x faster                                  |
| pickle_list          | 2.92 us                                                | 2.89 us: 1.01x faster                                  |
| json_loads           | 17.6 us                                                | 17.4 us: 1.01x faster                                  |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                  |
| pickle               | 7.45 us                                                | 7.40 us: 1.01x faster                                  |
| json_dumps           | 6.43 ms                                                | 6.44 ms: 1.00x slower                                  |
| xml_etree_process    | 38.5 ms                                                | 39.0 ms: 1.01x slower                                  |
| xml_etree_iterparse  | 74.3 ms                                                | 75.3 ms: 1.01x slower                                  |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                   |
| xml_etree_generate   | 55.8 ms                                                | 57.2 ms: 1.03x slower                                  |
| pickle_pure_python   | 188 us                                                 | 193 us: 1.03x slower                                   |
| unpickle_pure_python | 145 us                                                 | 157 us: 1.08x slower                                   |
| tomli_loads          | 1.39 sec                                               | 1.54 sec: 1.10x slower                                 |
| Geometric mean       | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 10.3 ms: 1.09x slower                                  |
| python_startup         | 11.5 ms                                                | 12.7 ms: 1.10x slower                                  |
| Geometric mean         | (ref)                                                  | 1.09x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.34 ms: 1.03x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 173 ms: 1.42x faster                                   |
| generators               | 28.5 ms                                                | 24.1 ms: 1.18x faster                                  |
| chaos                    | 45.2 ms                                                | 40.1 ms: 1.13x faster                                  |
| sqlglot_parse            | 898 us                                                 | 797 us: 1.13x faster                                   |
| scimark_monte_carlo      | 50.1 ms                                                | 44.8 ms: 1.12x faster                                  |
| crypto_pyaes             | 52.3 ms                                                | 47.1 ms: 1.11x faster                                  |
| deltablue                | 2.59 ms                                                | 2.34 ms: 1.11x faster                                  |
| sqlglot_transpile        | 1.07 ms                                                | 970 us: 1.11x faster                                   |
| asyncio_tcp              | 460 ms                                                 | 420 ms: 1.10x faster                                   |
| unpack_sequence          | 28.8 ns                                                | 26.4 ns: 1.09x faster                                  |
| coverage                 | 51.0 ms                                                | 47.0 ms: 1.09x faster                                  |
| comprehensions           | 15.7 us                                                | 14.6 us: 1.08x faster                                  |
| spectral_norm            | 75.0 ms                                                | 70.5 ms: 1.06x faster                                  |
| float                    | 58.2 ms                                                | 54.7 ms: 1.06x faster                                  |
| nqueens                  | 60.6 ms                                                | 57.4 ms: 1.05x faster                                  |
| async_tree_none          | 262 ms                                                 | 250 ms: 1.05x faster                                   |
| logging_simple           | 3.69 us                                                | 3.55 us: 1.04x faster                                  |
| mdp                      | 1.68 sec                                               | 1.62 sec: 1.04x faster                                 |
| docutils                 | 1.54 sec                                               | 1.48 sec: 1.04x faster                                 |
| logging_format           | 3.97 us                                                | 3.84 us: 1.04x faster                                  |
| go                       | 107 ms                                                 | 104 ms: 1.03x faster                                   |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.06 ms: 1.03x faster                                  |
| mako                     | 7.57 ms                                                | 7.34 ms: 1.03x faster                                  |
| coroutines               | 18.2 ms                                                | 17.7 ms: 1.03x faster                                  |
| scimark_lu               | 71.7 ms                                                | 70.0 ms: 1.02x faster                                  |
| unpickle_list            | 3.22 us                                                | 3.15 us: 1.02x faster                                  |
| unpickle                 | 9.26 us                                                | 9.05 us: 1.02x faster                                  |
| deepcopy_reduce          | 2.02 us                                                | 1.97 us: 1.02x faster                                  |
| bench_thread_pool        | 489 us                                                 | 479 us: 1.02x faster                                   |
| deepcopy_memo            | 24.5 us                                                | 24.0 us: 1.02x faster                                  |
| sqlglot_normalize        | 186 ms                                                 | 182 ms: 1.02x faster                                   |
| regex_dna                | 151 ms                                                 | 149 ms: 1.01x faster                                   |
| deepcopy                 | 224 us                                                 | 221 us: 1.01x faster                                   |
| pickle_list              | 2.92 us                                                | 2.89 us: 1.01x faster                                  |
| sqlglot_optimize         | 34.3 ms                                                | 34.0 ms: 1.01x faster                                  |
| async_generators         | 303 ms                                                 | 300 ms: 1.01x faster                                   |
| json_loads               | 17.6 us                                                | 17.4 us: 1.01x faster                                  |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                  |
| pickle                   | 7.45 us                                                | 7.40 us: 1.01x faster                                  |
| regex_compile            | 75.8 ms                                                | 75.6 ms: 1.00x faster                                  |
| create_gc_cycles         | 702 us                                                 | 701 us: 1.00x faster                                   |
| scimark_fft              | 198 ms                                                 | 197 ms: 1.00x faster                                   |
| logging_silent           | 67.7 ns                                                | 67.7 ns: 1.00x slower                                  |
| json_dumps               | 6.43 ms                                                | 6.44 ms: 1.00x slower                                  |
| dulwich_log              | 30.3 ms                                                | 30.4 ms: 1.00x slower                                  |
| meteor_contest           | 72.9 ms                                                | 73.7 ms: 1.01x slower                                  |
| xml_etree_process        | 38.5 ms                                                | 39.0 ms: 1.01x slower                                  |
| xml_etree_iterparse      | 74.3 ms                                                | 75.3 ms: 1.01x slower                                  |
| pyflate                  | 329 ms                                                 | 334 ms: 1.02x slower                                   |
| pprint_pformat           | 1.00 sec                                               | 1.02 sec: 1.02x slower                                 |
| pprint_safe_repr         | 493 ms                                                 | 502 ms: 1.02x slower                                   |
| xml_etree_parse          | 109 ms                                                 | 111 ms: 1.02x slower                                   |
| pathlib                  | 28.8 ms                                                | 29.6 ms: 1.02x slower                                  |
| xml_etree_generate       | 55.8 ms                                                | 57.2 ms: 1.03x slower                                  |
| pickle_pure_python       | 188 us                                                 | 193 us: 1.03x slower                                   |
| sqlite_synth             | 1.58 us                                                | 1.63 us: 1.03x slower                                  |
| pycparser                | 670 ms                                                 | 690 ms: 1.03x slower                                   |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.30 sec: 1.04x slower                                 |
| richards_super           | 34.9 ms                                                | 36.2 ms: 1.04x slower                                  |
| typing_runtime_protocols | 90.7 us                                                | 94.4 us: 1.04x slower                                  |
| nbody                    | 68.6 ms                                                | 71.3 ms: 1.04x slower                                  |
| async_tree_io            | 669 ms                                                 | 698 ms: 1.04x slower                                   |
| regex_v8                 | 16.0 ms                                                | 16.8 ms: 1.05x slower                                  |
| fannkuch                 | 267 ms                                                 | 282 ms: 1.06x slower                                   |
| richards                 | 31.1 ms                                                | 32.8 ms: 1.06x slower                                  |
| async_tree_memoization   | 309 ms                                                 | 328 ms: 1.06x slower                                   |
| hexiom                   | 4.24 ms                                                | 4.58 ms: 1.08x slower                                  |
| unpickle_pure_python     | 145 us                                                 | 157 us: 1.08x slower                                   |
| python_startup_no_site   | 9.43 ms                                                | 10.3 ms: 1.09x slower                                  |
| scimark_sor              | 94.1 ms                                                | 103 ms: 1.10x slower                                   |
| python_startup           | 11.5 ms                                                | 12.7 ms: 1.10x slower                                  |
| tomli_loads              | 1.39 sec                                               | 1.54 sec: 1.10x slower                                 |
| telco                    | 3.82 ms                                                | 4.63 ms: 1.21x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (8): tornado_http, async_tree_cpu_io_mixed, regex_effbot, json, mypy2, gc_traversal, pidigits, bench_mp_pool
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 62.83% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
