
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.00x faster
- HPT reliability: 50.50%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.52 sec: 1.01x faster                                         |
| Geometric mean | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 58.2 ms                                                | 56.0 ms: 1.04x faster                                          |
| nbody          | 68.6 ms                                                | 75.6 ms: 1.10x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 149 ms: 1.01x faster                                           |
| regex_effbot   | 2.58 ms                                                | 2.56 ms: 1.01x faster                                          |
| regex_v8       | 16.0 ms                                                | 16.9 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 1.39 sec                                               | 1.34 sec: 1.04x faster                                         |
| unpickle_list        | 3.22 us                                                | 3.13 us: 1.03x faster                                          |
| pickle_list          | 2.92 us                                                | 2.89 us: 1.01x faster                                          |
| unpickle             | 9.26 us                                                | 9.16 us: 1.01x faster                                          |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                          |
| pickle               | 7.45 us                                                | 7.42 us: 1.00x faster                                          |
| json_loads           | 17.6 us                                                | 17.5 us: 1.00x faster                                          |
| json_dumps           | 6.43 ms                                                | 6.45 ms: 1.00x slower                                          |
| xml_etree_iterparse  | 74.3 ms                                                | 75.4 ms: 1.02x slower                                          |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                           |
| xml_etree_process    | 38.5 ms                                                | 39.5 ms: 1.03x slower                                          |
| pickle_pure_python   | 188 us                                                 | 193 us: 1.03x slower                                           |
| xml_etree_generate   | 55.8 ms                                                | 57.7 ms: 1.03x slower                                          |
| unpickle_pure_python | 145 us                                                 | 158 us: 1.09x slower                                           |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 8.64 ms: 1.09x faster                                          |
| python_startup         | 11.5 ms                                                | 11.2 ms: 1.03x faster                                          |
| Geometric mean         | (ref)                                                  | 1.06x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.55 ms: 1.00x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 179 ms: 1.38x faster                                           |
| generators               | 28.5 ms                                                | 24.7 ms: 1.15x faster                                          |
| sqlglot_parse            | 898 us                                                 | 796 us: 1.13x faster                                           |
| sqlglot_transpile        | 1.07 ms                                                | 975 us: 1.10x faster                                           |
| python_startup_no_site   | 9.43 ms                                                | 8.64 ms: 1.09x faster                                          |
| unpack_sequence          | 28.8 ns                                                | 26.4 ns: 1.09x faster                                          |
| coverage                 | 51.0 ms                                                | 47.0 ms: 1.09x faster                                          |
| chaos                    | 45.2 ms                                                | 41.7 ms: 1.08x faster                                          |
| scimark_monte_carlo      | 50.1 ms                                                | 46.3 ms: 1.08x faster                                          |
| crypto_pyaes             | 52.3 ms                                                | 48.7 ms: 1.07x faster                                          |
| deltablue                | 2.59 ms                                                | 2.43 ms: 1.07x faster                                          |
| logging_simple           | 3.69 us                                                | 3.50 us: 1.06x faster                                          |
| logging_format           | 3.97 us                                                | 3.79 us: 1.05x faster                                          |
| tomli_loads              | 1.39 sec                                               | 1.34 sec: 1.04x faster                                         |
| spectral_norm            | 75.0 ms                                                | 72.0 ms: 1.04x faster                                          |
| float                    | 58.2 ms                                                | 56.0 ms: 1.04x faster                                          |
| coroutines               | 18.2 ms                                                | 17.6 ms: 1.03x faster                                          |
| async_tree_none          | 262 ms                                                 | 254 ms: 1.03x faster                                           |
| python_startup           | 11.5 ms                                                | 11.2 ms: 1.03x faster                                          |
| unpickle_list            | 3.22 us                                                | 3.13 us: 1.03x faster                                          |
| json                     | 3.05 ms                                                | 2.97 ms: 1.03x faster                                          |
| go                       | 107 ms                                                 | 105 ms: 1.02x faster                                           |
| mdp                      | 1.68 sec                                               | 1.65 sec: 1.02x faster                                         |
| deepcopy_reduce          | 2.02 us                                                | 1.99 us: 1.02x faster                                          |
| docutils                 | 1.54 sec                                               | 1.52 sec: 1.01x faster                                         |
| bench_mp_pool            | 45.9 ms                                                | 45.2 ms: 1.01x faster                                          |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.11 ms: 1.01x faster                                          |
| pickle_list              | 2.92 us                                                | 2.89 us: 1.01x faster                                          |
| regex_dna                | 151 ms                                                 | 149 ms: 1.01x faster                                           |
| unpickle                 | 9.26 us                                                | 9.16 us: 1.01x faster                                          |
| sqlglot_normalize        | 186 ms                                                 | 184 ms: 1.01x faster                                           |
| regex_effbot             | 2.58 ms                                                | 2.56 ms: 1.01x faster                                          |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                          |
| pickle                   | 7.45 us                                                | 7.42 us: 1.00x faster                                          |
| richards_super           | 34.9 ms                                                | 34.7 ms: 1.00x faster                                          |
| pyflate                  | 329 ms                                                 | 328 ms: 1.00x faster                                           |
| json_loads               | 17.6 us                                                | 17.5 us: 1.00x faster                                          |
| mako                     | 7.57 ms                                                | 7.55 ms: 1.00x faster                                          |
| json_dumps               | 6.43 ms                                                | 6.45 ms: 1.00x slower                                          |
| richards                 | 31.1 ms                                                | 31.2 ms: 1.00x slower                                          |
| dulwich_log              | 30.3 ms                                                | 30.5 ms: 1.01x slower                                          |
| logging_silent           | 67.7 ns                                                | 68.2 ns: 1.01x slower                                          |
| scimark_lu               | 71.7 ms                                                | 72.5 ms: 1.01x slower                                          |
| xml_etree_iterparse      | 74.3 ms                                                | 75.4 ms: 1.02x slower                                          |
| xml_etree_parse          | 109 ms                                                 | 111 ms: 1.02x slower                                           |
| async_generators         | 303 ms                                                 | 309 ms: 1.02x slower                                           |
| deepcopy_memo            | 24.5 us                                                | 25.1 us: 1.02x slower                                          |
| xml_etree_process        | 38.5 ms                                                | 39.5 ms: 1.03x slower                                          |
| pickle_pure_python       | 188 us                                                 | 193 us: 1.03x slower                                           |
| typing_runtime_protocols | 90.7 us                                                | 93.2 us: 1.03x slower                                          |
| sqlite_synth             | 1.58 us                                                | 1.63 us: 1.03x slower                                          |
| pycparser                | 670 ms                                                 | 693 ms: 1.03x slower                                           |
| xml_etree_generate       | 55.8 ms                                                | 57.7 ms: 1.03x slower                                          |
| nqueens                  | 60.6 ms                                                | 62.7 ms: 1.04x slower                                          |
| comprehensions           | 15.7 us                                                | 16.3 us: 1.04x slower                                          |
| pathlib                  | 28.8 ms                                                | 29.9 ms: 1.04x slower                                          |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.31 sec: 1.04x slower                                         |
| async_tree_io            | 669 ms                                                 | 701 ms: 1.05x slower                                           |
| fannkuch                 | 267 ms                                                 | 281 ms: 1.05x slower                                           |
| meteor_contest           | 72.9 ms                                                | 76.8 ms: 1.05x slower                                          |
| regex_v8                 | 16.0 ms                                                | 16.9 ms: 1.06x slower                                          |
| scimark_fft              | 198 ms                                                 | 210 ms: 1.06x slower                                           |
| async_tree_memoization   | 309 ms                                                 | 331 ms: 1.07x slower                                           |
| unpickle_pure_python     | 145 us                                                 | 158 us: 1.09x slower                                           |
| nbody                    | 68.6 ms                                                | 75.6 ms: 1.10x slower                                          |
| scimark_sor              | 94.1 ms                                                | 104 ms: 1.11x slower                                           |
| hexiom                   | 4.24 ms                                                | 4.94 ms: 1.17x slower                                          |
| telco                    | 3.82 ms                                                | 4.76 ms: 1.25x slower                                          |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (10): asyncio_tcp, tornado_http, async_tree_cpu_io_mixed, create_gc_cycles, bench_thread_pool, pidigits, gc_traversal, sqlglot_optimize, deepcopy, mypy2
Ignored benchmarks (7) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, pprint_pformat, pprint_safe_repr, regex_compile, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 50.50% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
