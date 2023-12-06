
# Results vs. base

- fork: brandtbucher
- ref: justin_os
- machine: linux-x86_64
- commit hash: 24495fb
- commit date: 2023-10-13
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.87 sec                                                                    | 2.94 sec: 1.02x slower                                                 |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 264 ms                                                                      | 265 ms: 1.00x slower                                                   |
| float          | 79.8 ms                                                                     | 88.0 ms: 1.10x slower                                                  |
| nbody          | 88.7 ms                                                                     | 100 ms: 1.13x slower                                                   |
| Geometric mean | (ref)                                                                       | 1.08x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 239 ms                                                                      | 248 ms: 1.04x slower                                                   |
| regex_compile  | 151 ms                                                                      | 159 ms: 1.05x slower                                                   |
| regex_effbot   | 3.40 ms                                                                     | 3.59 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                                       | 1.04x slower                                                           |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| xml_etree_parse      | 149 ms                                                                      | 147 ms: 1.02x faster                                                   |
| pickle_list          | 4.44 us                                                                     | 4.40 us: 1.01x faster                                                  |
| unpickle             | 14.8 us                                                                     | 14.7 us: 1.01x faster                                                  |
| unpickle_list        | 4.82 us                                                                     | 4.79 us: 1.01x faster                                                  |
| pickle_dict          | 32.1 us                                                                     | 32.2 us: 1.00x slower                                                  |
| json_loads           | 24.9 us                                                                     | 25.0 us: 1.00x slower                                                  |
| xml_etree_generate   | 85.6 ms                                                                     | 86.2 ms: 1.01x slower                                                  |
| json_dumps           | 10.6 ms                                                                     | 10.7 ms: 1.01x slower                                                  |
| xml_etree_process    | 58.7 ms                                                                     | 59.6 ms: 1.02x slower                                                  |
| pickle_pure_python   | 315 us                                                                      | 322 us: 1.02x slower                                                   |
| tomli_loads          | 2.31 sec                                                                    | 2.49 sec: 1.08x slower                                                 |
| unpickle_pure_python | 217 us                                                                      | 241 us: 1.11x slower                                                   |
| Geometric mean       | (ref)                                                                       | 1.02x slower                                                           |

Benchmark hidden because not significant (2): pickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 8.69 ms                                                                     | 8.71 ms: 1.00x slower                                                  |
| python_startup         | 12.6 ms                                                                     | 12.8 ms: 1.01x slower                                                  |
| Geometric mean         | (ref)                                                                       | 1.01x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|-----------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.2 ms                                                                     | 12.0 ms: 1.17x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231010-pythonperf2-x86_64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|--------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpack_sequence          | 53.5 ns                                                                     | 47.1 ns: 1.13x faster                                                  |
| richards                 | 55.7 ms                                                                     | 52.6 ms: 1.06x faster                                                  |
| richards_super           | 61.5 ms                                                                     | 58.8 ms: 1.05x faster                                                  |
| create_gc_cycles         | 1.67 ms                                                                     | 1.60 ms: 1.04x faster                                                  |
| json                     | 5.23 ms                                                                     | 5.13 ms: 1.02x faster                                                  |
| xml_etree_parse          | 149 ms                                                                      | 147 ms: 1.02x faster                                                   |
| dulwich_log              | 70.4 ms                                                                     | 69.5 ms: 1.01x faster                                                  |
| pickle_list              | 4.44 us                                                                     | 4.40 us: 1.01x faster                                                  |
| unpickle                 | 14.8 us                                                                     | 14.7 us: 1.01x faster                                                  |
| unpickle_list            | 4.82 us                                                                     | 4.79 us: 1.01x faster                                                  |
| sqlite_synth             | 2.68 us                                                                     | 2.67 us: 1.01x faster                                                  |
| scimark_sor              | 148 ms                                                                      | 147 ms: 1.01x faster                                                   |
| python_startup_no_site   | 8.69 ms                                                                     | 8.71 ms: 1.00x slower                                                  |
| asyncio_tcp_ssl          | 1.58 sec                                                                    | 1.59 sec: 1.00x slower                                                 |
| pickle_dict              | 32.1 us                                                                     | 32.2 us: 1.00x slower                                                  |
| pidigits                 | 264 ms                                                                      | 265 ms: 1.00x slower                                                   |
| json_loads               | 24.9 us                                                                     | 25.0 us: 1.00x slower                                                  |
| pyflate                  | 526 ms                                                                      | 528 ms: 1.01x slower                                                   |
| coroutines               | 23.3 ms                                                                     | 23.4 ms: 1.01x slower                                                  |
| asyncio_tcp              | 372 ms                                                                      | 374 ms: 1.01x slower                                                   |
| xml_etree_generate       | 85.6 ms                                                                     | 86.2 ms: 1.01x slower                                                  |
| python_startup           | 12.6 ms                                                                     | 12.8 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed  | 707 ms                                                                      | 716 ms: 1.01x slower                                                   |
| json_dumps               | 10.6 ms                                                                     | 10.7 ms: 1.01x slower                                                  |
| async_tree_memoization   | 555 ms                                                                      | 563 ms: 1.01x slower                                                   |
| sqlglot_transpile        | 1.83 ms                                                                     | 1.85 ms: 1.01x slower                                                  |
| deepcopy_reduce          | 3.38 us                                                                     | 3.43 us: 1.01x slower                                                  |
| async_tree_io            | 1.09 sec                                                                    | 1.10 sec: 1.02x slower                                                 |
| xml_etree_process        | 58.7 ms                                                                     | 59.6 ms: 1.02x slower                                                  |
| pathlib                  | 19.6 ms                                                                     | 20.0 ms: 1.02x slower                                                  |
| sqlglot_parse            | 1.41 ms                                                                     | 1.44 ms: 1.02x slower                                                  |
| deepcopy                 | 381 us                                                                      | 388 us: 1.02x slower                                                   |
| async_tree_none          | 440 ms                                                                      | 448 ms: 1.02x slower                                                   |
| raytrace                 | 280 ms                                                                      | 285 ms: 1.02x slower                                                   |
| spectral_norm            | 92.4 ms                                                                     | 94.1 ms: 1.02x slower                                                  |
| pickle_pure_python       | 315 us                                                                      | 322 us: 1.02x slower                                                   |
| docutils                 | 2.87 sec                                                                    | 2.94 sec: 1.02x slower                                                 |
| go                       | 174 ms                                                                      | 179 ms: 1.03x slower                                                   |
| logging_silent           | 97.5 ns                                                                     | 100 ns: 1.03x slower                                                   |
| telco                    | 8.11 ms                                                                     | 8.34 ms: 1.03x slower                                                  |
| logging_format           | 7.52 us                                                                     | 7.75 us: 1.03x slower                                                  |
| typing_runtime_protocols | 153 us                                                                      | 158 us: 1.03x slower                                                   |
| logging_simple           | 6.88 us                                                                     | 7.09 us: 1.03x slower                                                  |
| async_generators         | 398 ms                                                                      | 410 ms: 1.03x slower                                                   |
| mypy2                    | 373 ms                                                                      | 385 ms: 1.03x slower                                                   |
| coverage                 | 79.7 ms                                                                     | 82.4 ms: 1.03x slower                                                  |
| regex_dna                | 239 ms                                                                      | 248 ms: 1.04x slower                                                   |
| sqlglot_normalize        | 116 ms                                                                      | 121 ms: 1.04x slower                                                   |
| gc_traversal             | 3.82 ms                                                                     | 3.97 ms: 1.04x slower                                                  |
| sqlglot_optimize         | 58.7 ms                                                                     | 61.2 ms: 1.04x slower                                                  |
| scimark_lu               | 100 ms                                                                      | 105 ms: 1.04x slower                                                   |
| pycparser                | 1.29 sec                                                                    | 1.35 sec: 1.04x slower                                                 |
| generators               | 35.1 ms                                                                     | 36.7 ms: 1.05x slower                                                  |
| meteor_contest           | 130 ms                                                                      | 137 ms: 1.05x slower                                                   |
| regex_compile            | 151 ms                                                                      | 159 ms: 1.05x slower                                                   |
| mdp                      | 2.54 sec                                                                    | 2.68 sec: 1.06x slower                                                 |
| regex_effbot             | 3.40 ms                                                                     | 3.59 ms: 1.06x slower                                                  |
| deepcopy_memo            | 37.3 us                                                                     | 39.8 us: 1.07x slower                                                  |
| tomli_loads              | 2.31 sec                                                                    | 2.49 sec: 1.08x slower                                                 |
| pprint_safe_repr         | 811 ms                                                                      | 882 ms: 1.09x slower                                                   |
| pprint_pformat           | 1.66 sec                                                                    | 1.80 sec: 1.09x slower                                                 |
| scimark_monte_carlo      | 66.9 ms                                                                     | 73.5 ms: 1.10x slower                                                  |
| float                    | 79.8 ms                                                                     | 88.0 ms: 1.10x slower                                                  |
| unpickle_pure_python     | 217 us                                                                      | 241 us: 1.11x slower                                                   |
| scimark_sparse_mat_mult  | 4.23 ms                                                                     | 4.71 ms: 1.12x slower                                                  |
| fannkuch                 | 391 ms                                                                      | 437 ms: 1.12x slower                                                   |
| nbody                    | 88.7 ms                                                                     | 100 ms: 1.13x slower                                                   |
| chaos                    | 61.8 ms                                                                     | 70.2 ms: 1.14x slower                                                  |
| crypto_pyaes             | 73.2 ms                                                                     | 83.6 ms: 1.14x slower                                                  |
| nqueens                  | 88.2 ms                                                                     | 102 ms: 1.16x slower                                                   |
| mako                     | 10.2 ms                                                                     | 12.0 ms: 1.17x slower                                                  |
| scimark_fft              | 306 ms                                                                      | 362 ms: 1.18x slower                                                   |
| comprehensions           | 22.3 us                                                                     | 28.4 us: 1.28x slower                                                  |
| deltablue                | 3.61 ms                                                                     | 4.81 ms: 1.33x slower                                                  |
| hexiom                   | 6.45 ms                                                                     | 8.90 ms: 1.38x slower                                                  |
| Geometric mean           | (ref)                                                                       | 1.04x slower                                                           |

Benchmark hidden because not significant (6): regex_v8, pickle, xml_etree_iterparse, tornado_http, bench_thread_pool, bench_mp_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
