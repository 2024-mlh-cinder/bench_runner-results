
# Results vs. base

- fork: brandtbucher
- ref: justin_no_stubs
- machine: linux-x86_64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| 2to3           | 292 ms                                                                       | 301 ms: 1.03x slower                                                          |
| chameleon      | 7.59 ms                                                                      | 7.50 ms: 1.01x faster                                                         |
| docutils       | 2.83 sec                                                                     | 2.87 sec: 1.01x slower                                                        |
| Geometric mean | (ref)                                                                        | 1.01x slower                                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|--------------------|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| async_tree_none_tg | 439 ms                                                                       | 444 ms: 1.01x slower                                                          |
| Geometric mean     | (ref)                                                                        | 1.01x slower                                                                  |

Benchmark hidden because not significant (7): async_tree_cpu_io_mixed, async_tree_io, async_tree_io_tg, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| pidigits       | 266 ms                                                                       | 265 ms: 1.00x faster                                                          |
| nbody          | 85.1 ms                                                                      | 95.7 ms: 1.12x slower                                                         |
| Geometric mean | (ref)                                                                        | 1.04x slower                                                                  |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| regex_effbot   | 3.54 ms                                                                      | 3.49 ms: 1.02x faster                                                         |
| regex_dna      | 247 ms                                                                       | 244 ms: 1.01x faster                                                          |
| regex_v8       | 25.1 ms                                                                      | 25.4 ms: 1.01x slower                                                         |
| regex_compile  | 144 ms                                                                       | 149 ms: 1.04x slower                                                          |
| Geometric mean | (ref)                                                                        | 1.01x slower                                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| pickle_dict          | 32.1 us                                                                      | 32.3 us: 1.01x slower                                                         |
| unpickle_pure_python | 220 us                                                                       | 222 us: 1.01x slower                                                          |
| xml_etree_process    | 58.4 ms                                                                      | 58.9 ms: 1.01x slower                                                         |
| xml_etree_iterparse  | 104 ms                                                                       | 105 ms: 1.01x slower                                                          |
| pickle_pure_python   | 308 us                                                                       | 311 us: 1.01x slower                                                          |
| unpickle_list        | 4.60 us                                                                      | 4.65 us: 1.01x slower                                                         |
| pickle               | 9.92 us                                                                      | 10.0 us: 1.01x slower                                                         |
| xml_etree_generate   | 84.6 ms                                                                      | 85.6 ms: 1.01x slower                                                         |
| json_loads           | 25.3 us                                                                      | 25.6 us: 1.01x slower                                                         |
| xml_etree_parse      | 144 ms                                                                       | 147 ms: 1.02x slower                                                          |
| unpickle             | 14.8 us                                                                      | 15.1 us: 1.02x slower                                                         |
| tomli_loads          | 2.19 sec                                                                     | 2.27 sec: 1.04x slower                                                        |
| pickle_list          | 4.19 us                                                                      | 4.40 us: 1.05x slower                                                         |
| Geometric mean       | (ref)                                                                        | 1.02x slower                                                                  |

Benchmark hidden because not significant (1): json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| python_startup         | 12.8 ms                                                                      | 12.9 ms: 1.00x slower                                                         |
| python_startup_no_site | 11.2 ms                                                                      | 11.3 ms: 1.01x slower                                                         |
| Geometric mean         | (ref)                                                                        | 1.01x slower                                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| mako      | 10.2 ms                                                                      | 11.0 ms: 1.07x slower                                                         |

All benchmarks:
===============

| Benchmark                | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|--------------------------|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| richards                 | 54.5 ms                                                                      | 50.9 ms: 1.07x faster                                                         |
| richards_super           | 60.6 ms                                                                      | 57.4 ms: 1.06x faster                                                         |
| gc_traversal             | 3.54 ms                                                                      | 3.45 ms: 1.03x faster                                                         |
| create_gc_cycles         | 1.61 ms                                                                      | 1.58 ms: 1.02x faster                                                         |
| deepcopy_reduce          | 3.34 us                                                                      | 3.28 us: 1.02x faster                                                         |
| regex_effbot             | 3.54 ms                                                                      | 3.49 ms: 1.02x faster                                                         |
| chameleon                | 7.59 ms                                                                      | 7.50 ms: 1.01x faster                                                         |
| regex_dna                | 247 ms                                                                       | 244 ms: 1.01x faster                                                          |
| pyflate                  | 524 ms                                                                       | 522 ms: 1.00x faster                                                          |
| pidigits                 | 266 ms                                                                       | 265 ms: 1.00x faster                                                          |
| asyncio_tcp              | 369 ms                                                                       | 368 ms: 1.00x faster                                                          |
| deepcopy                 | 369 us                                                                       | 367 us: 1.00x faster                                                          |
| go                       | 173 ms                                                                       | 172 ms: 1.00x faster                                                          |
| asyncio_tcp_ssl          | 1.57 sec                                                                     | 1.57 sec: 1.00x slower                                                        |
| python_startup           | 12.8 ms                                                                      | 12.9 ms: 1.00x slower                                                         |
| scimark_sor              | 146 ms                                                                       | 147 ms: 1.01x slower                                                          |
| pickle_dict              | 32.1 us                                                                      | 32.3 us: 1.01x slower                                                         |
| unpickle_pure_python     | 220 us                                                                       | 222 us: 1.01x slower                                                          |
| python_startup_no_site   | 11.2 ms                                                                      | 11.3 ms: 1.01x slower                                                         |
| deepcopy_memo            | 36.5 us                                                                      | 36.8 us: 1.01x slower                                                         |
| pathlib                  | 19.1 ms                                                                      | 19.3 ms: 1.01x slower                                                         |
| xml_etree_process        | 58.4 ms                                                                      | 58.9 ms: 1.01x slower                                                         |
| xml_etree_iterparse      | 104 ms                                                                       | 105 ms: 1.01x slower                                                          |
| pickle_pure_python       | 308 us                                                                       | 311 us: 1.01x slower                                                          |
| unpickle_list            | 4.60 us                                                                      | 4.65 us: 1.01x slower                                                         |
| async_tree_none_tg       | 439 ms                                                                       | 444 ms: 1.01x slower                                                          |
| pickle                   | 9.92 us                                                                      | 10.0 us: 1.01x slower                                                         |
| xml_etree_generate       | 84.6 ms                                                                      | 85.6 ms: 1.01x slower                                                         |
| regex_v8                 | 25.1 ms                                                                      | 25.4 ms: 1.01x slower                                                         |
| json                     | 5.18 ms                                                                      | 5.24 ms: 1.01x slower                                                         |
| json_loads               | 25.3 us                                                                      | 25.6 us: 1.01x slower                                                         |
| sympy_expand             | 494 ms                                                                       | 500 ms: 1.01x slower                                                          |
| docutils                 | 2.83 sec                                                                     | 2.87 sec: 1.01x slower                                                        |
| xml_etree_parse          | 144 ms                                                                       | 147 ms: 1.02x slower                                                          |
| coroutines               | 22.3 ms                                                                      | 22.7 ms: 1.02x slower                                                         |
| logging_silent           | 97.6 ns                                                                      | 99.3 ns: 1.02x slower                                                         |
| coverage                 | 79.0 ms                                                                      | 80.8 ms: 1.02x slower                                                         |
| unpickle                 | 14.8 us                                                                      | 15.1 us: 1.02x slower                                                         |
| sqlglot_parse            | 1.38 ms                                                                      | 1.42 ms: 1.02x slower                                                         |
| unpack_sequence          | 46.7 ns                                                                      | 47.9 ns: 1.02x slower                                                         |
| logging_simple           | 6.40 us                                                                      | 6.57 us: 1.03x slower                                                         |
| sqlglot_transpile        | 1.79 ms                                                                      | 1.84 ms: 1.03x slower                                                         |
| mypy2                    | 368 ms                                                                       | 378 ms: 1.03x slower                                                          |
| sympy_str                | 290 ms                                                                       | 300 ms: 1.03x slower                                                          |
| 2to3                     | 292 ms                                                                       | 301 ms: 1.03x slower                                                          |
| logging_format           | 7.05 us                                                                      | 7.30 us: 1.03x slower                                                         |
| scimark_lu               | 99.7 ms                                                                      | 103 ms: 1.03x slower                                                          |
| bench_thread_pool        | 946 us                                                                       | 980 us: 1.04x slower                                                          |
| regex_compile            | 144 ms                                                                       | 149 ms: 1.04x slower                                                          |
| tomli_loads              | 2.19 sec                                                                     | 2.27 sec: 1.04x slower                                                        |
| meteor_contest           | 127 ms                                                                       | 132 ms: 1.04x slower                                                          |
| deltablue                | 3.58 ms                                                                      | 3.74 ms: 1.05x slower                                                         |
| async_generators         | 366 ms                                                                       | 383 ms: 1.05x slower                                                          |
| scimark_sparse_mat_mult  | 4.27 ms                                                                      | 4.48 ms: 1.05x slower                                                         |
| pickle_list              | 4.19 us                                                                      | 4.40 us: 1.05x slower                                                         |
| sympy_sum                | 151 ms                                                                       | 159 ms: 1.05x slower                                                          |
| sympy_integrate          | 23.0 ms                                                                      | 24.2 ms: 1.05x slower                                                         |
| pprint_safe_repr         | 817 ms                                                                       | 860 ms: 1.05x slower                                                          |
| mdp                      | 2.54 sec                                                                     | 2.67 sec: 1.05x slower                                                        |
| raytrace                 | 268 ms                                                                       | 285 ms: 1.06x slower                                                          |
| pprint_pformat           | 1.65 sec                                                                     | 1.76 sec: 1.06x slower                                                        |
| sqlglot_normalize        | 113 ms                                                                       | 120 ms: 1.06x slower                                                          |
| sqlglot_optimize         | 57.6 ms                                                                      | 61.4 ms: 1.07x slower                                                         |
| typing_runtime_protocols | 122 us                                                                       | 130 us: 1.07x slower                                                          |
| generators               | 34.1 ms                                                                      | 36.4 ms: 1.07x slower                                                         |
| mako                     | 10.2 ms                                                                      | 11.0 ms: 1.07x slower                                                         |
| fannkuch                 | 380 ms                                                                       | 411 ms: 1.08x slower                                                          |
| nbody                    | 85.1 ms                                                                      | 95.7 ms: 1.12x slower                                                         |
| chaos                    | 61.4 ms                                                                      | 70.4 ms: 1.15x slower                                                         |
| crypto_pyaes             | 71.6 ms                                                                      | 82.4 ms: 1.15x slower                                                         |
| spectral_norm            | 91.4 ms                                                                      | 106 ms: 1.16x slower                                                          |
| scimark_monte_carlo      | 69.7 ms                                                                      | 80.9 ms: 1.16x slower                                                         |
| nqueens                  | 88.4 ms                                                                      | 104 ms: 1.17x slower                                                          |
| scimark_fft              | 304 ms                                                                       | 364 ms: 1.19x slower                                                          |
| hexiom                   | 6.40 ms                                                                      | 7.78 ms: 1.22x slower                                                         |
| comprehensions           | 16.3 us                                                                      | 20.2 us: 1.24x slower                                                         |
| Geometric mean           | (ref)                                                                        | 1.03x slower                                                                  |

Benchmark hidden because not significant (17): asyncio_websockets, telco, float, sqlite_synth, json_dumps, dulwich_log, async_tree_cpu_io_mixed, async_tree_io, async_tree_io_tg, pycparser, async_tree_cpu_io_mixed_tg, dask, async_tree_memoization, async_tree_memoization_tg, tornado_http, async_tree_none, bench_mp_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
