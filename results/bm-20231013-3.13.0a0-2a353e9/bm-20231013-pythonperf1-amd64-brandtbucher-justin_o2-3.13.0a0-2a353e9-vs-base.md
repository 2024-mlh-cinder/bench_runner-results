
# Results vs. base

- fork: brandtbucher
- ref: justin_o2
- machine: windows-amd64
- commit hash: 2a353e9
- commit date: 2023-10-13
- overall geometric mean: 1.10x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.62 sec                                                                   | 1.71 sec: 1.05x slower                                                |
| tornado_http   | 88.2 ms                                                                    | 92.4 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                                      | 1.05x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 54.3 ms                                                                    | 55.9 ms: 1.03x slower                                                 |
| nbody          | 75.4 ms                                                                    | 88.2 ms: 1.17x slower                                                 |
| Geometric mean | (ref)                                                                      | 1.06x slower                                                          |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                                     | 123 ms: 1.01x faster                                                  |
| regex_effbot   | 1.61 ms                                                                    | 1.63 ms: 1.01x slower                                                 |
| regex_compile  | 91.2 ms                                                                    | 100 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                                      | 1.03x slower                                                          |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_loads           | 13.7 us                                                                    | 13.5 us: 1.01x faster                                                 |
| pickle_dict          | 18.3 us                                                                    | 18.2 us: 1.00x faster                                                 |
| tomli_loads          | 1.49 sec                                                                   | 1.50 sec: 1.01x slower                                                |
| xml_etree_parse      | 90.6 ms                                                                    | 92.2 ms: 1.02x slower                                                 |
| pickle               | 7.29 us                                                                    | 7.44 us: 1.02x slower                                                 |
| xml_etree_iterparse  | 64.7 ms                                                                    | 68.0 ms: 1.05x slower                                                 |
| json_dumps           | 5.72 ms                                                                    | 6.11 ms: 1.07x slower                                                 |
| xml_etree_generate   | 56.1 ms                                                                    | 62.7 ms: 1.12x slower                                                 |
| pickle_pure_python   | 195 us                                                                     | 224 us: 1.15x slower                                                  |
| xml_etree_process    | 38.7 ms                                                                    | 44.9 ms: 1.16x slower                                                 |
| unpickle_pure_python | 141 us                                                                     | 171 us: 1.21x slower                                                  |
| Geometric mean       | (ref)                                                                      | 1.05x slower                                                          |

Benchmark hidden because not significant (3): unpickle, unpickle_list, pickle_list

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|-----------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 7.20 ms                                                                    | 6.86 ms: 1.05x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|--------------------------|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako                     | 7.20 ms                                                                    | 6.86 ms: 1.05x faster                                                 |
| create_gc_cycles         | 724 us                                                                     | 714 us: 1.01x faster                                                  |
| gc_traversal             | 1.51 ms                                                                    | 1.49 ms: 1.01x faster                                                 |
| json_loads               | 13.7 us                                                                    | 13.5 us: 1.01x faster                                                 |
| regex_dna                | 124 ms                                                                     | 123 ms: 1.01x faster                                                  |
| pickle_dict              | 18.3 us                                                                    | 18.2 us: 1.00x faster                                                 |
| tomli_loads              | 1.49 sec                                                                   | 1.50 sec: 1.01x slower                                                |
| pathlib                  | 78.4 ms                                                                    | 79.0 ms: 1.01x slower                                                 |
| sqlite_synth             | 1.70 us                                                                    | 1.72 us: 1.01x slower                                                 |
| regex_effbot             | 1.61 ms                                                                    | 1.63 ms: 1.01x slower                                                 |
| dulwich_log              | 45.3 ms                                                                    | 45.9 ms: 1.01x slower                                                 |
| xml_etree_parse          | 90.6 ms                                                                    | 92.2 ms: 1.02x slower                                                 |
| pickle                   | 7.29 us                                                                    | 7.44 us: 1.02x slower                                                 |
| scimark_sparse_mat_mult  | 2.46 ms                                                                    | 2.52 ms: 1.02x slower                                                 |
| telco                    | 4.72 ms                                                                    | 4.86 ms: 1.03x slower                                                 |
| float                    | 54.3 ms                                                                    | 55.9 ms: 1.03x slower                                                 |
| async_tree_cpu_io_mixed  | 456 ms                                                                     | 473 ms: 1.04x slower                                                  |
| bench_mp_pool            | 63.5 ms                                                                    | 66.0 ms: 1.04x slower                                                 |
| async_tree_io            | 735 ms                                                                     | 765 ms: 1.04x slower                                                  |
| tornado_http             | 88.2 ms                                                                    | 92.4 ms: 1.05x slower                                                 |
| mdp                      | 1.41 sec                                                                   | 1.48 sec: 1.05x slower                                                |
| xml_etree_iterparse      | 64.7 ms                                                                    | 68.0 ms: 1.05x slower                                                 |
| docutils                 | 1.62 sec                                                                   | 1.71 sec: 1.05x slower                                                |
| fannkuch                 | 262 ms                                                                     | 277 ms: 1.06x slower                                                  |
| async_tree_memoization   | 346 ms                                                                     | 367 ms: 1.06x slower                                                  |
| async_tree_none          | 271 ms                                                                     | 287 ms: 1.06x slower                                                  |
| bench_thread_pool        | 831 us                                                                     | 883 us: 1.06x slower                                                  |
| json_dumps               | 5.72 ms                                                                    | 6.11 ms: 1.07x slower                                                 |
| mypy2                    | 215 ms                                                                     | 231 ms: 1.08x slower                                                  |
| meteor_contest           | 74.8 ms                                                                    | 80.4 ms: 1.08x slower                                                 |
| logging_format           | 6.99 us                                                                    | 7.56 us: 1.08x slower                                                 |
| logging_simple           | 6.56 us                                                                    | 7.10 us: 1.08x slower                                                 |
| regex_compile            | 91.2 ms                                                                    | 100 ms: 1.10x slower                                                  |
| typing_runtime_protocols | 94.2 us                                                                    | 104 us: 1.10x slower                                                  |
| sqlglot_optimize         | 35.4 ms                                                                    | 39.2 ms: 1.11x slower                                                 |
| sqlglot_normalize        | 188 ms                                                                     | 209 ms: 1.12x slower                                                  |
| deepcopy_reduce          | 2.16 us                                                                    | 2.41 us: 1.12x slower                                                 |
| crypto_pyaes             | 45.5 ms                                                                    | 50.7 ms: 1.12x slower                                                 |
| scimark_fft              | 182 ms                                                                     | 203 ms: 1.12x slower                                                  |
| xml_etree_generate       | 56.1 ms                                                                    | 62.7 ms: 1.12x slower                                                 |
| async_generators         | 242 ms                                                                     | 273 ms: 1.13x slower                                                  |
| nqueens                  | 60.1 ms                                                                    | 67.8 ms: 1.13x slower                                                 |
| pprint_pformat           | 1.08 sec                                                                   | 1.22 sec: 1.14x slower                                                |
| pyflate                  | 305 ms                                                                     | 348 ms: 1.14x slower                                                  |
| pprint_safe_repr         | 522 ms                                                                     | 596 ms: 1.14x slower                                                  |
| deepcopy                 | 239 us                                                                     | 273 us: 1.14x slower                                                  |
| pickle_pure_python       | 195 us                                                                     | 224 us: 1.15x slower                                                  |
| xml_etree_process        | 38.7 ms                                                                    | 44.9 ms: 1.16x slower                                                 |
| comprehensions           | 14.5 us                                                                    | 16.9 us: 1.16x slower                                                 |
| nbody                    | 75.4 ms                                                                    | 88.2 ms: 1.17x slower                                                 |
| sqlglot_transpile        | 1.05 ms                                                                    | 1.23 ms: 1.17x slower                                                 |
| scimark_monte_carlo      | 43.4 ms                                                                    | 51.6 ms: 1.19x slower                                                 |
| chaos                    | 42.3 ms                                                                    | 50.4 ms: 1.19x slower                                                 |
| richards_super           | 32.5 ms                                                                    | 39.0 ms: 1.20x slower                                                 |
| coverage                 | 48.9 ms                                                                    | 58.7 ms: 1.20x slower                                                 |
| raytrace                 | 177 ms                                                                     | 213 ms: 1.21x slower                                                  |
| unpickle_pure_python     | 141 us                                                                     | 171 us: 1.21x slower                                                  |
| sqlglot_parse            | 819 us                                                                     | 999 us: 1.22x slower                                                  |
| unpack_sequence          | 39.2 ns                                                                    | 48.2 ns: 1.23x slower                                                 |
| hexiom                   | 4.20 ms                                                                    | 5.18 ms: 1.23x slower                                                 |
| richards                 | 28.8 ms                                                                    | 35.5 ms: 1.23x slower                                                 |
| go                       | 92.0 ms                                                                    | 114 ms: 1.24x slower                                                  |
| spectral_norm            | 63.4 ms                                                                    | 80.6 ms: 1.27x slower                                                 |
| coroutines               | 14.7 ms                                                                    | 18.9 ms: 1.28x slower                                                 |
| scimark_sor              | 81.7 ms                                                                    | 105 ms: 1.29x slower                                                  |
| scimark_lu               | 58.1 ms                                                                    | 74.9 ms: 1.29x slower                                                 |
| deepcopy_memo            | 24.4 us                                                                    | 31.8 us: 1.30x slower                                                 |
| deltablue                | 2.22 ms                                                                    | 2.90 ms: 1.31x slower                                                 |
| logging_silent           | 64.1 ns                                                                    | 93.0 ns: 1.45x slower                                                 |
| generators               | 23.1 ms                                                                    | 34.0 ms: 1.48x slower                                                 |
| Geometric mean           | (ref)                                                                      | 1.10x slower                                                          |

Benchmark hidden because not significant (11): pycparser, asyncio_tcp_ssl, unpickle, json, pidigits, unpickle_list, pickle_list, python_startup_no_site, python_startup, asyncio_tcp, regex_v8


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.05x
