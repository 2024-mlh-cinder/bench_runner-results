
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.00x slower
- HPT reliability: 97.28%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 212 ms                                                                      | 219 ms: 1.03x slower                                                |
| chameleon      | 4.88 ms                                                                     | 4.93 ms: 1.01x slower                                               |
| docutils       | 1.56 sec                                                                    | 1.56 sec: 1.00x slower                                              |
| tornado_http   | 95.6 ms                                                                     | 97.4 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 452 ms                                                                      | 458 ms: 1.01x slower                                                |
| async_tree_io           | 715 ms                                                                      | 725 ms: 1.01x slower                                                |
| Geometric mean          | (ref)                                                                       | 1.01x slower                                                        |

Benchmark hidden because not significant (6): async_tree_memoization, async_tree_none, async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 75.5 ms                                                                     | 65.2 ms: 1.16x faster                                               |
| float          | 52.1 ms                                                                     | 50.5 ms: 1.03x faster                                               |
| pidigits       | 147 ms                                                                      | 151 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                                       | 1.05x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                                     | 1.56 ms: 1.01x faster                                               |
| regex_dna      | 117 ms                                                                      | 116 ms: 1.01x faster                                                |
| regex_v8       | 14.6 ms                                                                     | 17.9 ms: 1.22x slower                                               |
| Geometric mean | (ref)                                                                       | 1.05x slower                                                        |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads          | 1.45 sec                                                                    | 1.29 sec: 1.13x faster                                              |
| xml_etree_iterparse  | 63.6 ms                                                                     | 62.5 ms: 1.02x faster                                               |
| xml_etree_process    | 37.8 ms                                                                     | 37.3 ms: 1.01x faster                                               |
| xml_etree_generate   | 54.3 ms                                                                     | 54.7 ms: 1.01x slower                                               |
| pickle               | 7.03 us                                                                     | 7.11 us: 1.01x slower                                               |
| xml_etree_parse      | 90.1 ms                                                                     | 91.4 ms: 1.01x slower                                               |
| unpickle_list        | 2.62 us                                                                     | 2.68 us: 1.02x slower                                               |
| unpickle_pure_python | 130 us                                                                      | 133 us: 1.03x slower                                                |
| pickle_dict          | 18.4 us                                                                     | 18.9 us: 1.03x slower                                               |
| unpickle             | 8.12 us                                                                     | 8.38 us: 1.03x slower                                               |
| json_loads           | 13.5 us                                                                     | 13.9 us: 1.03x slower                                               |
| pickle_list          | 2.86 us                                                                     | 3.07 us: 1.07x slower                                               |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                        |

Benchmark hidden because not significant (2): pickle_pure_python, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 20.3 ms                                                                     | 20.7 ms: 1.02x slower                                               |
| python_startup_no_site | 18.1 ms                                                                     | 18.6 ms: 1.03x slower                                               |
| Geometric mean         | (ref)                                                                       | 1.02x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 6.53 ms                                                                     | 6.21 ms: 1.05x faster                                               |

All benchmarks:
===============

| Benchmark               | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody                   | 75.5 ms                                                                     | 65.2 ms: 1.16x faster                                               |
| tomli_loads             | 1.45 sec                                                                    | 1.29 sec: 1.13x faster                                              |
| pycparser               | 751 ms                                                                      | 674 ms: 1.11x faster                                                |
| deepcopy_memo           | 24.5 us                                                                     | 22.0 us: 1.11x faster                                               |
| richards                | 28.8 ms                                                                     | 26.2 ms: 1.10x faster                                               |
| deltablue               | 2.13 ms                                                                     | 1.99 ms: 1.07x faster                                               |
| richards_super          | 31.3 ms                                                                     | 29.5 ms: 1.06x faster                                               |
| fannkuch                | 256 ms                                                                      | 241 ms: 1.06x faster                                                |
| unpack_sequence         | 41.9 ns                                                                     | 39.6 ns: 1.06x faster                                               |
| asyncio_tcp_ssl         | 1.98 sec                                                                    | 1.87 sec: 1.06x faster                                              |
| mako                    | 6.53 ms                                                                     | 6.21 ms: 1.05x faster                                               |
| spectral_norm           | 62.3 ms                                                                     | 59.8 ms: 1.04x faster                                               |
| scimark_sor             | 80.9 ms                                                                     | 78.3 ms: 1.03x faster                                               |
| float                   | 52.1 ms                                                                     | 50.5 ms: 1.03x faster                                               |
| coverage                | 46.0 ms                                                                     | 45.2 ms: 1.02x faster                                               |
| xml_etree_iterparse     | 63.6 ms                                                                     | 62.5 ms: 1.02x faster                                               |
| deepcopy_reduce         | 1.98 us                                                                     | 1.95 us: 1.02x faster                                               |
| regex_effbot            | 1.58 ms                                                                     | 1.56 ms: 1.01x faster                                               |
| deepcopy                | 226 us                                                                      | 222 us: 1.01x faster                                                |
| generators              | 21.4 ms                                                                     | 21.1 ms: 1.01x faster                                               |
| xml_etree_process       | 37.8 ms                                                                     | 37.3 ms: 1.01x faster                                               |
| sqlite_synth            | 1.56 us                                                                     | 1.55 us: 1.01x faster                                               |
| coroutines              | 13.2 ms                                                                     | 13.1 ms: 1.01x faster                                               |
| regex_dna               | 117 ms                                                                      | 116 ms: 1.01x faster                                                |
| gc_traversal            | 1.51 ms                                                                     | 1.50 ms: 1.01x faster                                               |
| scimark_sparse_mat_mult | 2.40 ms                                                                     | 2.39 ms: 1.01x faster                                               |
| sqlglot_parse           | 768 us                                                                      | 764 us: 1.00x faster                                                |
| docutils                | 1.56 sec                                                                    | 1.56 sec: 1.00x slower                                              |
| sympy_expand            | 268 ms                                                                      | 269 ms: 1.00x slower                                                |
| pprint_pformat          | 1.02 sec                                                                    | 1.03 sec: 1.00x slower                                              |
| telco                   | 4.66 ms                                                                     | 4.68 ms: 1.00x slower                                               |
| logging_simple          | 6.13 us                                                                     | 6.17 us: 1.01x slower                                               |
| logging_silent          | 56.1 ns                                                                     | 56.5 ns: 1.01x slower                                               |
| nqueens                 | 59.4 ms                                                                     | 59.8 ms: 1.01x slower                                               |
| xml_etree_generate      | 54.3 ms                                                                     | 54.7 ms: 1.01x slower                                               |
| scimark_lu              | 57.6 ms                                                                     | 58.1 ms: 1.01x slower                                               |
| chameleon               | 4.88 ms                                                                     | 4.93 ms: 1.01x slower                                               |
| pickle                  | 7.03 us                                                                     | 7.11 us: 1.01x slower                                               |
| pprint_safe_repr        | 496 ms                                                                      | 503 ms: 1.01x slower                                                |
| async_tree_cpu_io_mixed | 452 ms                                                                      | 458 ms: 1.01x slower                                                |
| async_tree_io           | 715 ms                                                                      | 725 ms: 1.01x slower                                                |
| xml_etree_parse         | 90.1 ms                                                                     | 91.4 ms: 1.01x slower                                               |
| sqlglot_normalize       | 177 ms                                                                      | 179 ms: 1.02x slower                                                |
| sympy_str               | 157 ms                                                                      | 159 ms: 1.02x slower                                                |
| python_startup          | 20.3 ms                                                                     | 20.7 ms: 1.02x slower                                               |
| dask                    | 266 ms                                                                      | 271 ms: 1.02x slower                                                |
| tornado_http            | 95.6 ms                                                                     | 97.4 ms: 1.02x slower                                               |
| unpickle_list           | 2.62 us                                                                     | 2.68 us: 1.02x slower                                               |
| go                      | 88.4 ms                                                                     | 90.3 ms: 1.02x slower                                               |
| pidigits                | 147 ms                                                                      | 151 ms: 1.02x slower                                                |
| sqlglot_optimize        | 33.3 ms                                                                     | 34.1 ms: 1.02x slower                                               |
| mdp                     | 1.34 sec                                                                    | 1.38 sec: 1.02x slower                                              |
| async_generators        | 229 ms                                                                      | 235 ms: 1.03x slower                                                |
| raytrace                | 165 ms                                                                      | 170 ms: 1.03x slower                                                |
| unpickle_pure_python    | 130 us                                                                      | 133 us: 1.03x slower                                                |
| python_startup_no_site  | 18.1 ms                                                                     | 18.6 ms: 1.03x slower                                               |
| crypto_pyaes            | 43.7 ms                                                                     | 44.9 ms: 1.03x slower                                               |
| sympy_sum               | 81.8 ms                                                                     | 84.1 ms: 1.03x slower                                               |
| bench_mp_pool           | 63.9 ms                                                                     | 65.7 ms: 1.03x slower                                               |
| meteor_contest          | 73.3 ms                                                                     | 75.4 ms: 1.03x slower                                               |
| pickle_dict             | 18.4 us                                                                     | 18.9 us: 1.03x slower                                               |
| 2to3                    | 212 ms                                                                      | 219 ms: 1.03x slower                                                |
| unpickle                | 8.12 us                                                                     | 8.38 us: 1.03x slower                                               |
| json                    | 2.87 ms                                                                     | 2.97 ms: 1.03x slower                                               |
| json_loads              | 13.5 us                                                                     | 13.9 us: 1.03x slower                                               |
| chaos                   | 40.2 ms                                                                     | 41.9 ms: 1.04x slower                                               |
| sympy_integrate         | 12.4 ms                                                                     | 12.9 ms: 1.05x slower                                               |
| scimark_fft             | 178 ms                                                                      | 187 ms: 1.05x slower                                                |
| pickle_list             | 2.86 us                                                                     | 3.07 us: 1.07x slower                                               |
| comprehensions          | 10.3 us                                                                     | 11.3 us: 1.09x slower                                               |
| hexiom                  | 3.87 ms                                                                     | 4.24 ms: 1.10x slower                                               |
| regex_v8                | 14.6 ms                                                                     | 17.9 ms: 1.22x slower                                               |
| Geometric mean          | (ref)                                                                       | 1.00x slower                                                        |

Benchmark hidden because not significant (20): asyncio_tcp, create_gc_cycles, regex_compile, pickle_pure_python, dulwich_log, async_tree_memoization, sqlglot_transpile, pathlib, async_tree_none, async_tree_none_tg, logging_format, scimark_monte_carlo, pyflate, typing_runtime_protocols, json_dumps, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, bench_thread_pool, mypy2


# HPT report

- Reliability score: 97.28% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
