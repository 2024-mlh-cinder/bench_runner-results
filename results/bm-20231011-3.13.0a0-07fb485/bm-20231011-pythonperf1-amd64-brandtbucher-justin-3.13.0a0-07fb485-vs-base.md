
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 07fb485
- commit date: 2023-10-11
- overall geometric mean: 1.09x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                                   | 1.71 sec: 1.05x slower                                             |
| tornado_http   | 89.2 ms                                                                    | 91.9 ms: 1.03x slower                                              |
| Geometric mean | (ref)                                                                      | 1.04x slower                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| float          | 55.2 ms                                                                    | 54.7 ms: 1.01x faster                                              |
| pidigits       | 150 ms                                                                     | 150 ms: 1.00x slower                                               |
| nbody          | 75.1 ms                                                                    | 86.4 ms: 1.15x slower                                              |
| Geometric mean | (ref)                                                                      | 1.05x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 123 ms                                                                     | 121 ms: 1.02x faster                                               |
| regex_compile  | 92.4 ms                                                                    | 99.0 ms: 1.07x slower                                              |
| regex_v8       | 15.1 ms                                                                    | 16.9 ms: 1.12x slower                                              |
| Geometric mean | (ref)                                                                      | 1.04x slower                                                       |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_list          | 2.87 us                                                                    | 2.82 us: 1.02x faster                                              |
| tomli_loads          | 1.50 sec                                                                   | 1.49 sec: 1.01x faster                                             |
| pickle               | 7.26 us                                                                    | 7.34 us: 1.01x slower                                              |
| xml_etree_parse      | 91.8 ms                                                                    | 92.9 ms: 1.01x slower                                              |
| unpickle             | 8.13 us                                                                    | 8.23 us: 1.01x slower                                              |
| json_loads           | 13.6 us                                                                    | 13.9 us: 1.02x slower                                              |
| json_dumps           | 5.81 ms                                                                    | 6.00 ms: 1.03x slower                                              |
| pickle_dict          | 18.3 us                                                                    | 18.9 us: 1.03x slower                                              |
| xml_etree_iterparse  | 64.4 ms                                                                    | 67.4 ms: 1.05x slower                                              |
| xml_etree_generate   | 56.9 ms                                                                    | 62.8 ms: 1.10x slower                                              |
| xml_etree_process    | 39.6 ms                                                                    | 45.2 ms: 1.14x slower                                              |
| pickle_pure_python   | 197 us                                                                     | 227 us: 1.15x slower                                               |
| unpickle_pure_python | 141 us                                                                     | 172 us: 1.21x slower                                               |
| Geometric mean       | (ref)                                                                      | 1.05x slower                                                       |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|------------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                                    | 15.9 ms: 1.01x faster                                              |
| Geometric mean         | (ref)                                                                      | 1.00x faster                                                       |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|-----------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 7.19 ms                                                                    | 6.91 ms: 1.04x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|--------------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pycparser                | 901 ms                                                                     | 771 ms: 1.17x faster                                               |
| mako                     | 7.19 ms                                                                    | 6.91 ms: 1.04x faster                                              |
| pickle_list              | 2.87 us                                                                    | 2.82 us: 1.02x faster                                              |
| regex_dna                | 123 ms                                                                     | 121 ms: 1.02x faster                                               |
| typing_runtime_protocols | 103 us                                                                     | 101 us: 1.01x faster                                               |
| python_startup_no_site   | 16.1 ms                                                                    | 15.9 ms: 1.01x faster                                              |
| float                    | 55.2 ms                                                                    | 54.7 ms: 1.01x faster                                              |
| tomli_loads              | 1.50 sec                                                                   | 1.49 sec: 1.01x faster                                             |
| pidigits                 | 150 ms                                                                     | 150 ms: 1.00x slower                                               |
| json                     | 2.92 ms                                                                    | 2.94 ms: 1.01x slower                                              |
| pickle                   | 7.26 us                                                                    | 7.34 us: 1.01x slower                                              |
| xml_etree_parse          | 91.8 ms                                                                    | 92.9 ms: 1.01x slower                                              |
| unpickle                 | 8.13 us                                                                    | 8.23 us: 1.01x slower                                              |
| gc_traversal             | 1.48 ms                                                                    | 1.50 ms: 1.01x slower                                              |
| pathlib                  | 77.8 ms                                                                    | 78.9 ms: 1.01x slower                                              |
| sqlite_synth             | 1.70 us                                                                    | 1.73 us: 1.01x slower                                              |
| dulwich_log              | 45.4 ms                                                                    | 46.1 ms: 1.02x slower                                              |
| json_loads               | 13.6 us                                                                    | 13.9 us: 1.02x slower                                              |
| telco                    | 4.72 ms                                                                    | 4.83 ms: 1.02x slower                                              |
| asyncio_tcp              | 474 ms                                                                     | 488 ms: 1.03x slower                                               |
| tornado_http             | 89.2 ms                                                                    | 91.9 ms: 1.03x slower                                              |
| json_dumps               | 5.81 ms                                                                    | 6.00 ms: 1.03x slower                                              |
| coverage                 | 46.2 ms                                                                    | 47.7 ms: 1.03x slower                                              |
| bench_mp_pool            | 63.7 ms                                                                    | 65.8 ms: 1.03x slower                                              |
| fannkuch                 | 260 ms                                                                     | 269 ms: 1.03x slower                                               |
| pickle_dict              | 18.3 us                                                                    | 18.9 us: 1.03x slower                                              |
| scimark_sparse_mat_mult  | 2.48 ms                                                                    | 2.58 ms: 1.04x slower                                              |
| xml_etree_iterparse      | 64.4 ms                                                                    | 67.4 ms: 1.05x slower                                              |
| async_tree_cpu_io_mixed  | 455 ms                                                                     | 477 ms: 1.05x slower                                               |
| docutils                 | 1.63 sec                                                                   | 1.71 sec: 1.05x slower                                             |
| bench_thread_pool        | 835 us                                                                     | 881 us: 1.05x slower                                               |
| meteor_contest           | 75.9 ms                                                                    | 80.1 ms: 1.06x slower                                              |
| async_tree_io            | 729 ms                                                                     | 773 ms: 1.06x slower                                               |
| mypy2                    | 217 ms                                                                     | 230 ms: 1.06x slower                                               |
| async_tree_memoization   | 346 ms                                                                     | 368 ms: 1.06x slower                                               |
| mdp                      | 1.43 sec                                                                   | 1.53 sec: 1.07x slower                                             |
| async_tree_none          | 271 ms                                                                     | 289 ms: 1.07x slower                                               |
| regex_compile            | 92.4 ms                                                                    | 99.0 ms: 1.07x slower                                              |
| logging_simple           | 6.55 us                                                                    | 7.09 us: 1.08x slower                                              |
| logging_format           | 6.96 us                                                                    | 7.55 us: 1.08x slower                                              |
| deepcopy_reduce          | 2.20 us                                                                    | 2.39 us: 1.09x slower                                              |
| async_generators         | 245 ms                                                                     | 269 ms: 1.10x slower                                               |
| xml_etree_generate       | 56.9 ms                                                                    | 62.8 ms: 1.10x slower                                              |
| nqueens                  | 61.2 ms                                                                    | 67.8 ms: 1.11x slower                                              |
| sqlglot_optimize         | 35.2 ms                                                                    | 39.0 ms: 1.11x slower                                              |
| pprint_pformat           | 1.10 sec                                                                   | 1.22 sec: 1.11x slower                                             |
| pprint_safe_repr         | 536 ms                                                                     | 599 ms: 1.12x slower                                               |
| regex_v8                 | 15.1 ms                                                                    | 16.9 ms: 1.12x slower                                              |
| scimark_fft              | 183 ms                                                                     | 205 ms: 1.12x slower                                               |
| sqlglot_normalize        | 186 ms                                                                     | 210 ms: 1.13x slower                                               |
| crypto_pyaes             | 44.7 ms                                                                    | 50.9 ms: 1.14x slower                                              |
| deepcopy                 | 242 us                                                                     | 276 us: 1.14x slower                                               |
| xml_etree_process        | 39.6 ms                                                                    | 45.2 ms: 1.14x slower                                              |
| nbody                    | 75.1 ms                                                                    | 86.4 ms: 1.15x slower                                              |
| pickle_pure_python       | 197 us                                                                     | 227 us: 1.15x slower                                               |
| comprehensions           | 14.5 us                                                                    | 16.8 us: 1.16x slower                                              |
| pyflate                  | 304 ms                                                                     | 352 ms: 1.16x slower                                               |
| sqlglot_transpile        | 1.06 ms                                                                    | 1.23 ms: 1.16x slower                                              |
| unpack_sequence          | 41.2 ns                                                                    | 48.6 ns: 1.18x slower                                              |
| raytrace                 | 178 ms                                                                     | 211 ms: 1.19x slower                                               |
| richards_super           | 32.5 ms                                                                    | 38.6 ms: 1.19x slower                                              |
| sqlglot_parse            | 828 us                                                                     | 984 us: 1.19x slower                                               |
| chaos                    | 42.4 ms                                                                    | 50.4 ms: 1.19x slower                                              |
| scimark_monte_carlo      | 43.1 ms                                                                    | 51.5 ms: 1.19x slower                                              |
| richards                 | 28.9 ms                                                                    | 35.0 ms: 1.21x slower                                              |
| unpickle_pure_python     | 141 us                                                                     | 172 us: 1.21x slower                                               |
| go                       | 91.8 ms                                                                    | 113 ms: 1.23x slower                                               |
| scimark_sor              | 85.0 ms                                                                    | 105 ms: 1.23x slower                                               |
| spectral_norm            | 65.6 ms                                                                    | 80.9 ms: 1.23x slower                                              |
| hexiom                   | 4.22 ms                                                                    | 5.21 ms: 1.23x slower                                              |
| scimark_lu               | 60.4 ms                                                                    | 76.7 ms: 1.27x slower                                              |
| deepcopy_memo            | 24.9 us                                                                    | 31.9 us: 1.28x slower                                              |
| coroutines               | 14.8 ms                                                                    | 19.1 ms: 1.29x slower                                              |
| deltablue                | 2.20 ms                                                                    | 2.87 ms: 1.30x slower                                              |
| logging_silent           | 63.6 ns                                                                    | 91.1 ns: 1.43x slower                                              |
| generators               | 22.4 ms                                                                    | 34.2 ms: 1.53x slower                                              |
| Geometric mean           | (ref)                                                                      | 1.09x slower                                                       |

Benchmark hidden because not significant (5): regex_effbot, unpickle_list, create_gc_cycles, python_startup, asyncio_tcp_ssl


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
