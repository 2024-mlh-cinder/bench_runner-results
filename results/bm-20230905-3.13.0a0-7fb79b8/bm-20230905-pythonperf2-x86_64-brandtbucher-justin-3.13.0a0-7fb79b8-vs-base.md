
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.88 sec                                                                    | 2.97 sec: 1.03x slower                                              |
| tornado_http   | 121 ms                                                                      | 123 ms: 1.01x slower                                                |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 264 ms                                                                      | 265 ms: 1.00x slower                                                |
| float          | 80.2 ms                                                                     | 83.2 ms: 1.04x slower                                               |
| nbody          | 87.5 ms                                                                     | 96.0 ms: 1.10x slower                                               |
| Geometric mean | (ref)                                                                       | 1.05x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 238 ms                                                                      | 241 ms: 1.01x slower                                                |
| regex_v8       | 25.6 ms                                                                     | 25.9 ms: 1.01x slower                                               |
| regex_effbot   | 3.48 ms                                                                     | 3.64 ms: 1.05x slower                                               |
| regex_compile  | 147 ms                                                                      | 157 ms: 1.07x slower                                                |
| Geometric mean | (ref)                                                                       | 1.04x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| xml_etree_process    | 58.7 ms                                                                     | 59.4 ms: 1.01x slower                                               |
| xml_etree_generate   | 85.7 ms                                                                     | 87.0 ms: 1.02x slower                                               |
| pickle               | 10.1 us                                                                     | 10.2 us: 1.02x slower                                               |
| json_loads           | 24.9 us                                                                     | 25.4 us: 1.02x slower                                               |
| pickle_pure_python   | 313 us                                                                      | 319 us: 1.02x slower                                                |
| xml_etree_iterparse  | 105 ms                                                                      | 108 ms: 1.03x slower                                                |
| unpickle             | 14.4 us                                                                     | 15.0 us: 1.05x slower                                               |
| pickle_dict          | 32.1 us                                                                     | 33.7 us: 1.05x slower                                               |
| pickle_list          | 4.31 us                                                                     | 4.52 us: 1.05x slower                                               |
| unpickle_pure_python | 230 us                                                                      | 246 us: 1.07x slower                                                |
| tomli_loads          | 2.20 sec                                                                    | 2.42 sec: 1.10x slower                                              |
| Geometric mean       | (ref)                                                                       | 1.03x slower                                                        |

Benchmark hidden because not significant (3): json_dumps, xml_etree_parse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                                     | 11.9 ms: 1.00x slower                                               |
| python_startup_no_site | 8.84 ms                                                                     | 8.86 ms: 1.00x slower                                               |
| Geometric mean         | (ref)                                                                       | 1.00x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.2 ms                                                                     | 10.9 ms: 1.06x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| logging_format           | 7.64 us                                                                     | 7.43 us: 1.03x faster                                               |
| coroutines               | 23.2 ms                                                                     | 22.7 ms: 1.02x faster                                               |
| pathlib                  | 20.2 ms                                                                     | 20.0 ms: 1.01x faster                                               |
| coverage                 | 83.9 ms                                                                     | 83.0 ms: 1.01x faster                                               |
| raytrace                 | 282 ms                                                                      | 279 ms: 1.01x faster                                                |
| pyflate                  | 515 ms                                                                      | 511 ms: 1.01x faster                                                |
| scimark_sor              | 148 ms                                                                      | 147 ms: 1.01x faster                                                |
| logging_simple           | 6.90 us                                                                     | 6.86 us: 1.01x faster                                               |
| python_startup           | 11.9 ms                                                                     | 11.9 ms: 1.00x slower                                               |
| asyncio_tcp_ssl          | 1.58 sec                                                                    | 1.58 sec: 1.00x slower                                              |
| pidigits                 | 264 ms                                                                      | 265 ms: 1.00x slower                                                |
| python_startup_no_site   | 8.84 ms                                                                     | 8.86 ms: 1.00x slower                                               |
| dask                     | 591 ms                                                                      | 596 ms: 1.01x slower                                                |
| asyncio_tcp              | 369 ms                                                                      | 372 ms: 1.01x slower                                                |
| richards                 | 55.4 ms                                                                     | 56.0 ms: 1.01x slower                                               |
| regex_dna                | 238 ms                                                                      | 241 ms: 1.01x slower                                                |
| xml_etree_process        | 58.7 ms                                                                     | 59.4 ms: 1.01x slower                                               |
| json                     | 5.13 ms                                                                     | 5.19 ms: 1.01x slower                                               |
| regex_v8                 | 25.6 ms                                                                     | 25.9 ms: 1.01x slower                                               |
| tornado_http             | 121 ms                                                                      | 123 ms: 1.01x slower                                                |
| async_tree_io            | 1.08 sec                                                                    | 1.10 sec: 1.02x slower                                              |
| xml_etree_generate       | 85.7 ms                                                                     | 87.0 ms: 1.02x slower                                               |
| pickle                   | 10.1 us                                                                     | 10.2 us: 1.02x slower                                               |
| async_tree_memoization   | 552 ms                                                                      | 562 ms: 1.02x slower                                                |
| async_tree_cpu_io_mixed  | 704 ms                                                                      | 716 ms: 1.02x slower                                                |
| deltablue                | 3.72 ms                                                                     | 3.79 ms: 1.02x slower                                               |
| sqlite_synth             | 2.72 us                                                                     | 2.77 us: 1.02x slower                                               |
| json_loads               | 24.9 us                                                                     | 25.4 us: 1.02x slower                                               |
| pickle_pure_python       | 313 us                                                                      | 319 us: 1.02x slower                                                |
| async_tree_none          | 438 ms                                                                      | 449 ms: 1.02x slower                                                |
| deepcopy_reduce          | 3.39 us                                                                     | 3.48 us: 1.03x slower                                               |
| sqlglot_parse            | 1.41 ms                                                                     | 1.45 ms: 1.03x slower                                               |
| telco                    | 8.05 ms                                                                     | 8.29 ms: 1.03x slower                                               |
| xml_etree_iterparse      | 105 ms                                                                      | 108 ms: 1.03x slower                                                |
| docutils                 | 2.88 sec                                                                    | 2.97 sec: 1.03x slower                                              |
| mypy2                    | 373 ms                                                                      | 386 ms: 1.03x slower                                                |
| sqlglot_transpile        | 1.81 ms                                                                     | 1.87 ms: 1.04x slower                                               |
| float                    | 80.2 ms                                                                     | 83.2 ms: 1.04x slower                                               |
| mdp                      | 2.57 sec                                                                    | 2.67 sec: 1.04x slower                                              |
| sqlglot_optimize         | 59.1 ms                                                                     | 61.5 ms: 1.04x slower                                               |
| async_generators         | 399 ms                                                                      | 416 ms: 1.04x slower                                                |
| sqlglot_normalize        | 116 ms                                                                      | 121 ms: 1.04x slower                                                |
| generators               | 35.0 ms                                                                     | 36.6 ms: 1.04x slower                                               |
| bench_thread_pool        | 974 us                                                                      | 1.02 ms: 1.05x slower                                               |
| regex_effbot             | 3.48 ms                                                                     | 3.64 ms: 1.05x slower                                               |
| spectral_norm            | 91.1 ms                                                                     | 95.3 ms: 1.05x slower                                               |
| unpickle                 | 14.4 us                                                                     | 15.0 us: 1.05x slower                                               |
| pickle_dict              | 32.1 us                                                                     | 33.7 us: 1.05x slower                                               |
| pickle_list              | 4.31 us                                                                     | 4.52 us: 1.05x slower                                               |
| deepcopy                 | 374 us                                                                      | 396 us: 1.06x slower                                                |
| go                       | 172 ms                                                                      | 182 ms: 1.06x slower                                                |
| scimark_monte_carlo      | 67.6 ms                                                                     | 71.7 ms: 1.06x slower                                               |
| mako                     | 10.2 ms                                                                     | 10.9 ms: 1.06x slower                                               |
| scimark_lu               | 100 ms                                                                      | 107 ms: 1.06x slower                                                |
| regex_compile            | 147 ms                                                                      | 157 ms: 1.07x slower                                                |
| unpickle_pure_python     | 230 us                                                                      | 246 us: 1.07x slower                                                |
| crypto_pyaes             | 71.3 ms                                                                     | 76.9 ms: 1.08x slower                                               |
| deepcopy_memo            | 36.9 us                                                                     | 40.0 us: 1.08x slower                                               |
| typing_runtime_protocols | 148 us                                                                      | 160 us: 1.09x slower                                                |
| meteor_contest           | 128 ms                                                                      | 140 ms: 1.09x slower                                                |
| nbody                    | 87.5 ms                                                                     | 96.0 ms: 1.10x slower                                               |
| unpack_sequence          | 46.6 ns                                                                     | 51.1 ns: 1.10x slower                                               |
| tomli_loads              | 2.20 sec                                                                    | 2.42 sec: 1.10x slower                                              |
| chaos                    | 61.5 ms                                                                     | 68.4 ms: 1.11x slower                                               |
| scimark_fft              | 298 ms                                                                      | 333 ms: 1.12x slower                                                |
| fannkuch                 | 389 ms                                                                      | 438 ms: 1.12x slower                                                |
| hexiom                   | 6.45 ms                                                                     | 7.51 ms: 1.16x slower                                               |
| nqueens                  | 89.5 ms                                                                     | 104 ms: 1.16x slower                                                |
| gc_traversal             | 3.53 ms                                                                     | 4.16 ms: 1.18x slower                                               |
| comprehensions           | 21.9 us                                                                     | 26.2 us: 1.20x slower                                               |
| scimark_sparse_mat_mult  | 4.02 ms                                                                     | 5.23 ms: 1.30x slower                                               |
| Geometric mean           | (ref)                                                                       | 1.04x slower                                                        |

Benchmark hidden because not significant (11): create_gc_cycles, pycparser, bench_mp_pool, json_dumps, logging_silent, pprint_safe_repr, pprint_pformat, richards_super, dulwich_log, xml_etree_parse, unpickle_list


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
