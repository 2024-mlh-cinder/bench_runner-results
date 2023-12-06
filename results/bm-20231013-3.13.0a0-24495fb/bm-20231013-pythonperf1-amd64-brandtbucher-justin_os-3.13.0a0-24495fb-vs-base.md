
# Results vs. base

- fork: brandtbucher
- ref: justin_os
- machine: windows-amd64
- commit hash: 24495fb
- commit date: 2023-10-13
- overall geometric mean: 1.10x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.62 sec                                                                   | 1.70 sec: 1.05x slower                                                |
| tornado_http   | 89.3 ms                                                                    | 92.9 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                                      | 1.05x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 150 ms                                                                     | 151 ms: 1.00x slower                                                  |
| float          | 54.3 ms                                                                    | 55.6 ms: 1.02x slower                                                 |
| nbody          | 75.3 ms                                                                    | 87.3 ms: 1.16x slower                                                 |
| Geometric mean | (ref)                                                                      | 1.06x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 123 ms                                                                     | 124 ms: 1.01x slower                                                  |
| regex_effbot   | 1.61 ms                                                                    | 1.67 ms: 1.04x slower                                                 |
| regex_compile  | 91.4 ms                                                                    | 99.7 ms: 1.09x slower                                                 |
| regex_v8       | 14.9 ms                                                                    | 18.8 ms: 1.26x slower                                                 |
| Geometric mean | (ref)                                                                      | 1.10x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_list          | 2.93 us                                                                    | 2.88 us: 1.02x faster                                                 |
| tomli_loads          | 1.51 sec                                                                   | 1.50 sec: 1.01x faster                                                |
| pickle_dict          | 18.7 us                                                                    | 18.8 us: 1.01x slower                                                 |
| json_loads           | 13.6 us                                                                    | 13.7 us: 1.01x slower                                                 |
| xml_etree_parse      | 91.8 ms                                                                    | 92.6 ms: 1.01x slower                                                 |
| pickle               | 6.95 us                                                                    | 7.08 us: 1.02x slower                                                 |
| xml_etree_iterparse  | 64.2 ms                                                                    | 67.8 ms: 1.06x slower                                                 |
| json_dumps           | 5.67 ms                                                                    | 6.11 ms: 1.08x slower                                                 |
| xml_etree_generate   | 56.7 ms                                                                    | 62.3 ms: 1.10x slower                                                 |
| xml_etree_process    | 39.1 ms                                                                    | 44.7 ms: 1.14x slower                                                 |
| pickle_pure_python   | 197 us                                                                     | 227 us: 1.15x slower                                                  |
| unpickle_pure_python | 141 us                                                                     | 173 us: 1.23x slower                                                  |
| Geometric mean       | (ref)                                                                      | 1.05x slower                                                          |

Benchmark hidden because not significant (2): unpickle, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|------------------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 19.2 ms                                                                    | 19.5 ms: 1.02x slower                                                 |
| python_startup_no_site | 15.8 ms                                                                    | 16.0 ms: 1.02x slower                                                 |
| Geometric mean         | (ref)                                                                      | 1.02x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|-----------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 7.17 ms                                                                    | 6.74 ms: 1.06x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|--------------------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako                     | 7.17 ms                                                                    | 6.74 ms: 1.06x faster                                                 |
| coverage                 | 46.5 ms                                                                    | 45.5 ms: 1.02x faster                                                 |
| pickle_list              | 2.93 us                                                                    | 2.88 us: 1.02x faster                                                 |
| tomli_loads              | 1.51 sec                                                                   | 1.50 sec: 1.01x faster                                                |
| gc_traversal             | 1.51 ms                                                                    | 1.50 ms: 1.01x faster                                                 |
| pidigits                 | 150 ms                                                                     | 151 ms: 1.00x slower                                                  |
| sqlite_synth             | 1.70 us                                                                    | 1.71 us: 1.01x slower                                                 |
| pickle_dict              | 18.7 us                                                                    | 18.8 us: 1.01x slower                                                 |
| json_loads               | 13.6 us                                                                    | 13.7 us: 1.01x slower                                                 |
| regex_dna                | 123 ms                                                                     | 124 ms: 1.01x slower                                                  |
| xml_etree_parse          | 91.8 ms                                                                    | 92.6 ms: 1.01x slower                                                 |
| pathlib                  | 78.2 ms                                                                    | 79.1 ms: 1.01x slower                                                 |
| python_startup           | 19.2 ms                                                                    | 19.5 ms: 1.02x slower                                                 |
| dulwich_log              | 45.3 ms                                                                    | 46.1 ms: 1.02x slower                                                 |
| python_startup_no_site   | 15.8 ms                                                                    | 16.0 ms: 1.02x slower                                                 |
| scimark_sparse_mat_mult  | 2.48 ms                                                                    | 2.52 ms: 1.02x slower                                                 |
| pickle                   | 6.95 us                                                                    | 7.08 us: 1.02x slower                                                 |
| float                    | 54.3 ms                                                                    | 55.6 ms: 1.02x slower                                                 |
| json                     | 2.90 ms                                                                    | 2.97 ms: 1.02x slower                                                 |
| bench_thread_pool        | 849 us                                                                     | 879 us: 1.04x slower                                                  |
| asyncio_tcp              | 471 ms                                                                     | 488 ms: 1.04x slower                                                  |
| fannkuch                 | 261 ms                                                                     | 272 ms: 1.04x slower                                                  |
| tornado_http             | 89.3 ms                                                                    | 92.9 ms: 1.04x slower                                                 |
| bench_mp_pool            | 63.4 ms                                                                    | 66.0 ms: 1.04x slower                                                 |
| regex_effbot             | 1.61 ms                                                                    | 1.67 ms: 1.04x slower                                                 |
| docutils                 | 1.62 sec                                                                   | 1.70 sec: 1.05x slower                                                |
| async_tree_cpu_io_mixed  | 452 ms                                                                     | 477 ms: 1.06x slower                                                  |
| xml_etree_iterparse      | 64.2 ms                                                                    | 67.8 ms: 1.06x slower                                                 |
| async_tree_none          | 271 ms                                                                     | 287 ms: 1.06x slower                                                  |
| async_tree_memoization   | 345 ms                                                                     | 368 ms: 1.07x slower                                                  |
| async_tree_io            | 724 ms                                                                     | 773 ms: 1.07x slower                                                  |
| typing_runtime_protocols | 96.0 us                                                                    | 103 us: 1.07x slower                                                  |
| mypy2                    | 215 ms                                                                     | 230 ms: 1.07x slower                                                  |
| unpack_sequence          | 45.3 ns                                                                    | 48.8 ns: 1.08x slower                                                 |
| json_dumps               | 5.67 ms                                                                    | 6.11 ms: 1.08x slower                                                 |
| meteor_contest           | 74.4 ms                                                                    | 80.3 ms: 1.08x slower                                                 |
| logging_format           | 6.97 us                                                                    | 7.53 us: 1.08x slower                                                 |
| logging_simple           | 6.52 us                                                                    | 7.09 us: 1.09x slower                                                 |
| regex_compile            | 91.4 ms                                                                    | 99.7 ms: 1.09x slower                                                 |
| mdp                      | 1.39 sec                                                                   | 1.53 sec: 1.09x slower                                                |
| nqueens                  | 61.2 ms                                                                    | 67.0 ms: 1.09x slower                                                 |
| xml_etree_generate       | 56.7 ms                                                                    | 62.3 ms: 1.10x slower                                                 |
| scimark_fft              | 186 ms                                                                     | 205 ms: 1.10x slower                                                  |
| deepcopy_reduce          | 2.13 us                                                                    | 2.36 us: 1.11x slower                                                 |
| sqlglot_optimize         | 35.1 ms                                                                    | 39.0 ms: 1.11x slower                                                 |
| crypto_pyaes             | 45.6 ms                                                                    | 50.9 ms: 1.12x slower                                                 |
| async_generators         | 242 ms                                                                     | 270 ms: 1.12x slower                                                  |
| sqlglot_normalize        | 186 ms                                                                     | 209 ms: 1.12x slower                                                  |
| pprint_pformat           | 1.07 sec                                                                   | 1.21 sec: 1.12x slower                                                |
| pyflate                  | 305 ms                                                                     | 343 ms: 1.12x slower                                                  |
| pprint_safe_repr         | 526 ms                                                                     | 594 ms: 1.13x slower                                                  |
| comprehensions           | 14.7 us                                                                    | 16.7 us: 1.14x slower                                                 |
| xml_etree_process        | 39.1 ms                                                                    | 44.7 ms: 1.14x slower                                                 |
| pickle_pure_python       | 197 us                                                                     | 227 us: 1.15x slower                                                  |
| deepcopy                 | 238 us                                                                     | 275 us: 1.16x slower                                                  |
| nbody                    | 75.3 ms                                                                    | 87.3 ms: 1.16x slower                                                 |
| sqlglot_transpile        | 1.05 ms                                                                    | 1.23 ms: 1.17x slower                                                 |
| chaos                    | 42.4 ms                                                                    | 49.7 ms: 1.17x slower                                                 |
| sqlglot_parse            | 827 us                                                                     | 990 us: 1.20x slower                                                  |
| raytrace                 | 178 ms                                                                     | 213 ms: 1.20x slower                                                  |
| richards_super           | 32.7 ms                                                                    | 39.2 ms: 1.20x slower                                                 |
| go                       | 92.6 ms                                                                    | 113 ms: 1.22x slower                                                  |
| hexiom                   | 4.20 ms                                                                    | 5.13 ms: 1.22x slower                                                 |
| scimark_monte_carlo      | 42.5 ms                                                                    | 52.0 ms: 1.22x slower                                                 |
| richards                 | 29.1 ms                                                                    | 35.7 ms: 1.23x slower                                                 |
| unpickle_pure_python     | 141 us                                                                     | 173 us: 1.23x slower                                                  |
| scimark_lu               | 60.4 ms                                                                    | 75.0 ms: 1.24x slower                                                 |
| scimark_sor              | 83.2 ms                                                                    | 103 ms: 1.24x slower                                                  |
| spectral_norm            | 64.3 ms                                                                    | 80.2 ms: 1.25x slower                                                 |
| regex_v8                 | 14.9 ms                                                                    | 18.8 ms: 1.26x slower                                                 |
| coroutines               | 14.7 ms                                                                    | 18.8 ms: 1.28x slower                                                 |
| deepcopy_memo            | 24.2 us                                                                    | 31.4 us: 1.29x slower                                                 |
| deltablue                | 2.21 ms                                                                    | 2.86 ms: 1.30x slower                                                 |
| logging_silent           | 63.7 ns                                                                    | 92.7 ns: 1.45x slower                                                 |
| generators               | 22.6 ms                                                                    | 34.0 ms: 1.50x slower                                                 |
| Geometric mean           | (ref)                                                                      | 1.10x slower                                                          |

Benchmark hidden because not significant (6): pycparser, unpickle, telco, asyncio_tcp_ssl, create_gc_cycles, unpickle_list


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.07x
- 95% likely to have a slowdown of 1.06x
- 99% likely to have a slowdown of 1.06x
