
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 07fb485
- commit date: 2023-10-11
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.88 sec                                                                    | 2.93 sec: 1.02x slower                                              |
| tornado_http   | 122 ms                                                                      | 124 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 265 ms                                                                      | 265 ms: 1.00x slower                                                |
| float          | 78.5 ms                                                                     | 88.8 ms: 1.13x slower                                               |
| nbody          | 87.3 ms                                                                     | 100 ms: 1.15x slower                                                |
| Geometric mean | (ref)                                                                       | 1.09x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 238 ms                                                                      | 247 ms: 1.04x slower                                                |
| regex_effbot   | 3.42 ms                                                                     | 3.62 ms: 1.06x slower                                               |
| regex_compile  | 150 ms                                                                      | 159 ms: 1.06x slower                                                |
| regex_v8       | 25.0 ms                                                                     | 26.6 ms: 1.07x slower                                               |
| Geometric mean | (ref)                                                                       | 1.05x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle             | 14.9 us                                                                     | 14.3 us: 1.04x faster                                               |
| xml_etree_generate   | 89.1 ms                                                                     | 85.9 ms: 1.04x faster                                               |
| xml_etree_process    | 59.8 ms                                                                     | 58.8 ms: 1.02x faster                                               |
| xml_etree_parse      | 151 ms                                                                      | 149 ms: 1.01x faster                                                |
| pickle               | 10.1 us                                                                     | 10.0 us: 1.01x faster                                               |
| xml_etree_iterparse  | 106 ms                                                                      | 107 ms: 1.01x slower                                                |
| pickle_pure_python   | 313 us                                                                      | 317 us: 1.01x slower                                                |
| json_dumps           | 10.5 ms                                                                     | 10.8 ms: 1.02x slower                                               |
| unpickle_list        | 4.55 us                                                                     | 4.68 us: 1.03x slower                                               |
| pickle_dict          | 31.6 us                                                                     | 32.8 us: 1.04x slower                                               |
| pickle_list          | 4.17 us                                                                     | 4.33 us: 1.04x slower                                               |
| unpickle_pure_python | 227 us                                                                      | 237 us: 1.04x slower                                                |
| tomli_loads          | 2.20 sec                                                                    | 2.48 sec: 1.13x slower                                              |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                        |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                                     | 8.69 ms: 1.00x slower                                               |
| python_startup         | 12.6 ms                                                                     | 12.6 ms: 1.00x slower                                               |
| Geometric mean         | (ref)                                                                       | 1.00x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|-----------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.2 ms                                                                     | 12.1 ms: 1.18x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|--------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| gc_traversal             | 3.95 ms                                                                     | 3.52 ms: 1.12x faster                                               |
| richards                 | 55.1 ms                                                                     | 51.6 ms: 1.07x faster                                               |
| richards_super           | 61.0 ms                                                                     | 57.6 ms: 1.06x faster                                               |
| create_gc_cycles         | 1.67 ms                                                                     | 1.60 ms: 1.04x faster                                               |
| unpickle                 | 14.9 us                                                                     | 14.3 us: 1.04x faster                                               |
| xml_etree_generate       | 89.1 ms                                                                     | 85.9 ms: 1.04x faster                                               |
| xml_etree_process        | 59.8 ms                                                                     | 58.8 ms: 1.02x faster                                               |
| unpack_sequence          | 50.7 ns                                                                     | 49.9 ns: 1.02x faster                                               |
| xml_etree_parse          | 151 ms                                                                      | 149 ms: 1.01x faster                                                |
| pickle                   | 10.1 us                                                                     | 10.0 us: 1.01x faster                                               |
| sqlglot_normalize        | 117 ms                                                                      | 117 ms: 1.00x faster                                                |
| python_startup_no_site   | 8.67 ms                                                                     | 8.69 ms: 1.00x slower                                               |
| python_startup           | 12.6 ms                                                                     | 12.6 ms: 1.00x slower                                               |
| pidigits                 | 265 ms                                                                      | 265 ms: 1.00x slower                                                |
| dulwich_log              | 69.2 ms                                                                     | 69.5 ms: 1.00x slower                                               |
| asyncio_tcp_ssl          | 1.58 sec                                                                    | 1.59 sec: 1.00x slower                                              |
| sqlite_synth             | 2.68 us                                                                     | 2.70 us: 1.01x slower                                               |
| sqlglot_optimize         | 59.1 ms                                                                     | 59.6 ms: 1.01x slower                                               |
| xml_etree_iterparse      | 106 ms                                                                      | 107 ms: 1.01x slower                                                |
| logging_format           | 7.65 us                                                                     | 7.73 us: 1.01x slower                                               |
| deepcopy                 | 372 us                                                                      | 376 us: 1.01x slower                                                |
| async_tree_memoization   | 551 ms                                                                      | 557 ms: 1.01x slower                                                |
| pickle_pure_python       | 313 us                                                                      | 317 us: 1.01x slower                                                |
| spectral_norm            | 91.8 ms                                                                     | 93.2 ms: 1.01x slower                                               |
| async_tree_cpu_io_mixed  | 701 ms                                                                      | 712 ms: 1.02x slower                                                |
| generators               | 35.6 ms                                                                     | 36.2 ms: 1.02x slower                                               |
| go                       | 172 ms                                                                      | 175 ms: 1.02x slower                                                |
| docutils                 | 2.88 sec                                                                    | 2.93 sec: 1.02x slower                                              |
| async_tree_none          | 436 ms                                                                      | 444 ms: 1.02x slower                                                |
| tornado_http             | 122 ms                                                                      | 124 ms: 1.02x slower                                                |
| coroutines               | 22.9 ms                                                                     | 23.4 ms: 1.02x slower                                               |
| deepcopy_reduce          | 3.31 us                                                                     | 3.38 us: 1.02x slower                                               |
| json_dumps               | 10.5 ms                                                                     | 10.8 ms: 1.02x slower                                               |
| pycparser                | 1.30 sec                                                                    | 1.34 sec: 1.03x slower                                              |
| pathlib                  | 19.7 ms                                                                     | 20.2 ms: 1.03x slower                                               |
| typing_runtime_protocols | 152 us                                                                      | 156 us: 1.03x slower                                                |
| unpickle_list            | 4.55 us                                                                     | 4.68 us: 1.03x slower                                               |
| mypy2                    | 371 ms                                                                      | 382 ms: 1.03x slower                                                |
| mdp                      | 2.54 sec                                                                    | 2.62 sec: 1.03x slower                                              |
| pickle_dict              | 31.6 us                                                                     | 32.8 us: 1.04x slower                                               |
| regex_dna                | 238 ms                                                                      | 247 ms: 1.04x slower                                                |
| pickle_list              | 4.17 us                                                                     | 4.33 us: 1.04x slower                                               |
| coverage                 | 79.6 ms                                                                     | 82.6 ms: 1.04x slower                                               |
| deepcopy_memo            | 38.1 us                                                                     | 39.5 us: 1.04x slower                                               |
| scimark_monte_carlo      | 70.4 ms                                                                     | 73.3 ms: 1.04x slower                                               |
| unpickle_pure_python     | 227 us                                                                      | 237 us: 1.04x slower                                                |
| pyflate                  | 509 ms                                                                      | 534 ms: 1.05x slower                                                |
| scimark_lu               | 98.8 ms                                                                     | 104 ms: 1.05x slower                                                |
| regex_effbot             | 3.42 ms                                                                     | 3.62 ms: 1.06x slower                                               |
| bench_mp_pool            | 4.47 ms                                                                     | 4.74 ms: 1.06x slower                                               |
| regex_compile            | 150 ms                                                                      | 159 ms: 1.06x slower                                                |
| raytrace                 | 274 ms                                                                      | 291 ms: 1.06x slower                                                |
| meteor_contest           | 129 ms                                                                      | 137 ms: 1.06x slower                                                |
| regex_v8                 | 25.0 ms                                                                     | 26.6 ms: 1.07x slower                                               |
| async_generators         | 394 ms                                                                      | 422 ms: 1.07x slower                                                |
| pprint_safe_repr         | 822 ms                                                                      | 885 ms: 1.08x slower                                                |
| pprint_pformat           | 1.67 sec                                                                    | 1.81 sec: 1.09x slower                                              |
| fannkuch                 | 387 ms                                                                      | 429 ms: 1.11x slower                                                |
| tomli_loads              | 2.20 sec                                                                    | 2.48 sec: 1.13x slower                                              |
| float                    | 78.5 ms                                                                     | 88.8 ms: 1.13x slower                                               |
| chaos                    | 61.6 ms                                                                     | 69.8 ms: 1.13x slower                                               |
| scimark_sparse_mat_mult  | 4.02 ms                                                                     | 4.59 ms: 1.14x slower                                               |
| nbody                    | 87.3 ms                                                                     | 100 ms: 1.15x slower                                                |
| nqueens                  | 88.9 ms                                                                     | 102 ms: 1.15x slower                                                |
| crypto_pyaes             | 72.5 ms                                                                     | 83.9 ms: 1.16x slower                                               |
| mako                     | 10.2 ms                                                                     | 12.1 ms: 1.18x slower                                               |
| scimark_fft              | 298 ms                                                                      | 361 ms: 1.21x slower                                                |
| comprehensions           | 22.3 us                                                                     | 28.5 us: 1.28x slower                                               |
| deltablue                | 3.64 ms                                                                     | 4.80 ms: 1.32x slower                                               |
| hexiom                   | 6.52 ms                                                                     | 9.00 ms: 1.38x slower                                               |
| Geometric mean           | (ref)                                                                       | 1.04x slower                                                        |

Benchmark hidden because not significant (11): json_loads, scimark_sor, sqlglot_parse, json, async_tree_io, asyncio_tcp, sqlglot_transpile, logging_silent, logging_simple, telco, bench_thread_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
