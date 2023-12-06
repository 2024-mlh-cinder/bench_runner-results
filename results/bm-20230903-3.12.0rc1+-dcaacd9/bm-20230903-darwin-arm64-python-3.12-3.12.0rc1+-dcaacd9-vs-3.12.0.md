
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: dcaacd9
- commit date: 2023-09-03
- overall geometric mean: 1.01x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-darwin-arm64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 168 ms: 1.02x faster                                    |
| docutils       | 1.54 sec                                               | 1.49 sec: 1.03x faster                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-darwin-arm64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 58.2 ms                                                | 56.8 ms: 1.02x faster                                   |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| nbody          | 68.6 ms                                                | 69.0 ms: 1.01x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-darwin-arm64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 16.0 ms                                                | 15.8 ms: 1.01x faster                                   |
| regex_dna      | 151 ms                                                 | 150 ms: 1.01x faster                                    |
| regex_effbot   | 2.58 ms                                                | 2.57 ms: 1.01x faster                                   |
| regex_compile  | 75.8 ms                                                | 76.2 ms: 1.00x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-darwin-arm64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.87 us: 1.02x faster                                   |
| json_dumps           | 6.43 ms                                                | 6.32 ms: 1.02x faster                                   |
| unpickle_pure_python | 145 us                                                 | 143 us: 1.01x faster                                    |
| tomli_loads          | 1.39 sec                                               | 1.38 sec: 1.01x faster                                  |
| xml_etree_iterparse  | 74.3 ms                                                | 74.0 ms: 1.00x faster                                   |
| xml_etree_process    | 38.5 ms                                                | 38.6 ms: 1.00x slower                                   |
| xml_etree_generate   | 55.8 ms                                                | 56.0 ms: 1.00x slower                                   |
| unpickle             | 9.26 us                                                | 9.30 us: 1.00x slower                                   |
| pickle_pure_python   | 188 us                                                 | 190 us: 1.01x slower                                    |
| unpickle_list        | 3.22 us                                                | 3.28 us: 1.02x slower                                   |
| Geometric mean       | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (4): pickle, pickle_dict, json_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-darwin-arm64-python-3.12-3.12.0rc1+-dcaacd9 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.49 ms: 1.01x slower                                   |
| python_startup         | 11.5 ms                                                | 11.7 ms: 1.01x slower                                   |
| Geometric mean         | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-darwin-arm64-python-3.12-3.12.0rc1+-dcaacd9 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.61 ms: 1.00x slower                                   |

All benchmarks:
===============

| Benchmark               | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230903-darwin-arm64-python-3.12-3.12.0rc1+-dcaacd9 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| raytrace                | 246 ms                                                 | 208 ms: 1.19x faster                                    |
| scimark_monte_carlo     | 50.1 ms                                                | 43.2 ms: 1.16x faster                                   |
| go                      | 107 ms                                                 | 94.0 ms: 1.14x faster                                   |
| scimark_sor             | 94.1 ms                                                | 85.6 ms: 1.10x faster                                   |
| generators              | 28.5 ms                                                | 26.0 ms: 1.10x faster                                   |
| sqlglot_parse           | 898 us                                                 | 830 us: 1.08x faster                                    |
| deltablue               | 2.59 ms                                                | 2.40 ms: 1.08x faster                                   |
| chaos                   | 45.2 ms                                                | 42.1 ms: 1.08x faster                                   |
| pyflate                 | 329 ms                                                 | 307 ms: 1.07x faster                                    |
| sqlglot_transpile       | 1.07 ms                                                | 1.01 ms: 1.06x faster                                   |
| comprehensions          | 15.7 us                                                | 14.9 us: 1.06x faster                                   |
| coroutines              | 18.2 ms                                                | 17.4 ms: 1.05x faster                                   |
| logging_simple          | 3.69 us                                                | 3.58 us: 1.03x faster                                   |
| mdp                     | 1.68 sec                                               | 1.63 sec: 1.03x faster                                  |
| telco                   | 3.82 ms                                                | 3.71 ms: 1.03x faster                                   |
| docutils                | 1.54 sec                                               | 1.49 sec: 1.03x faster                                  |
| richards                | 31.1 ms                                                | 30.2 ms: 1.03x faster                                   |
| logging_format          | 3.97 us                                                | 3.87 us: 1.03x faster                                   |
| richards_super          | 34.9 ms                                                | 34.0 ms: 1.03x faster                                   |
| sqlalchemy_declarative  | 65.9 ms                                                | 64.2 ms: 1.03x faster                                   |
| float                   | 58.2 ms                                                | 56.8 ms: 1.02x faster                                   |
| async_tree_io           | 669 ms                                                 | 654 ms: 1.02x faster                                    |
| nqueens                 | 60.6 ms                                                | 59.3 ms: 1.02x faster                                   |
| pickle_list             | 2.92 us                                                | 2.87 us: 1.02x faster                                   |
| unpack_sequence         | 28.8 ns                                                | 28.3 ns: 1.02x faster                                   |
| crypto_pyaes            | 52.3 ms                                                | 51.3 ms: 1.02x faster                                   |
| json_dumps              | 6.43 ms                                                | 6.32 ms: 1.02x faster                                   |
| 2to3                    | 171 ms                                                 | 168 ms: 1.02x faster                                    |
| sqlalchemy_imperative   | 7.02 ms                                                | 6.92 ms: 1.01x faster                                   |
| asyncio_tcp_ssl         | 1.26 sec                                               | 1.24 sec: 1.01x faster                                  |
| regex_v8                | 16.0 ms                                                | 15.8 ms: 1.01x faster                                   |
| coverage                | 51.0 ms                                                | 50.6 ms: 1.01x faster                                   |
| pprint_safe_repr        | 493 ms                                                 | 489 ms: 1.01x faster                                    |
| regex_dna               | 151 ms                                                 | 150 ms: 1.01x faster                                    |
| async_tree_memoization  | 309 ms                                                 | 307 ms: 1.01x faster                                    |
| fannkuch                | 267 ms                                                 | 265 ms: 1.01x faster                                    |
| unpickle_pure_python    | 145 us                                                 | 143 us: 1.01x faster                                    |
| pprint_pformat          | 1.00 sec                                               | 997 ms: 1.01x faster                                    |
| tomli_loads             | 1.39 sec                                               | 1.38 sec: 1.01x faster                                  |
| sqlglot_optimize        | 34.3 ms                                                | 34.1 ms: 1.01x faster                                   |
| async_tree_none         | 262 ms                                                 | 261 ms: 1.01x faster                                    |
| dulwich_log             | 30.3 ms                                                | 30.2 ms: 1.01x faster                                   |
| regex_effbot            | 2.58 ms                                                | 2.57 ms: 1.01x faster                                   |
| xml_etree_iterparse     | 74.3 ms                                                | 74.0 ms: 1.00x faster                                   |
| scimark_lu              | 71.7 ms                                                | 71.4 ms: 1.00x faster                                   |
| bench_thread_pool       | 489 us                                                 | 487 us: 1.00x faster                                    |
| scimark_sparse_mat_mult | 3.16 ms                                                | 3.15 ms: 1.00x faster                                   |
| sqlglot_normalize       | 186 ms                                                 | 185 ms: 1.00x faster                                    |
| gc_traversal            | 2.40 ms                                                | 2.40 ms: 1.00x faster                                   |
| meteor_contest          | 72.9 ms                                                | 72.8 ms: 1.00x faster                                   |
| hexiom                  | 4.24 ms                                                | 4.23 ms: 1.00x faster                                   |
| pidigits                | 282 ms                                                 | 282 ms: 1.00x faster                                    |
| logging_silent          | 67.7 ns                                                | 67.7 ns: 1.00x slower                                   |
| xml_etree_process       | 38.5 ms                                                | 38.6 ms: 1.00x slower                                   |
| xml_etree_generate      | 55.8 ms                                                | 56.0 ms: 1.00x slower                                   |
| spectral_norm           | 75.0 ms                                                | 75.2 ms: 1.00x slower                                   |
| regex_compile           | 75.8 ms                                                | 76.2 ms: 1.00x slower                                   |
| unpickle                | 9.26 us                                                | 9.30 us: 1.00x slower                                   |
| mako                    | 7.57 ms                                                | 7.61 ms: 1.00x slower                                   |
| deepcopy_reduce         | 2.02 us                                                | 2.03 us: 1.01x slower                                   |
| nbody                   | 68.6 ms                                                | 69.0 ms: 1.01x slower                                   |
| python_startup_no_site  | 9.43 ms                                                | 9.49 ms: 1.01x slower                                   |
| async_generators        | 303 ms                                                 | 306 ms: 1.01x slower                                    |
| pickle_pure_python      | 188 us                                                 | 190 us: 1.01x slower                                    |
| python_startup          | 11.5 ms                                                | 11.7 ms: 1.01x slower                                   |
| deepcopy_memo           | 24.5 us                                                | 24.8 us: 1.01x slower                                   |
| unpickle_list           | 3.22 us                                                | 3.28 us: 1.02x slower                                   |
| pathlib                 | 28.8 ms                                                | 32.1 ms: 1.11x slower                                   |
| dask                    | 228 ms                                                 | 316 ms: 1.39x slower                                    |
| Geometric mean          | (ref)                                                  | 1.01x faster                                            |

Benchmark hidden because not significant (16): asyncio_tcp, mypy2, tornado_http, async_tree_cpu_io_mixed, pycparser, pickle, json, typing_runtime_protocols, scimark_fft, pickle_dict, create_gc_cycles, json_loads, deepcopy, sqlite_synth, bench_mp_pool, xml_etree_parse


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
