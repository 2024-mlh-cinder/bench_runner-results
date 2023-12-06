
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 209 ms                                                                      | 217 ms: 1.04x slower                                                |
| chameleon      | 4.80 ms                                                                     | 4.89 ms: 1.02x slower                                               |
| docutils       | 1.54 sec                                                                    | 1.56 sec: 1.01x slower                                              |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 447 ms                                                                      | 453 ms: 1.01x slower                                                |
| async_tree_none_tg         | 280 ms                                                                      | 285 ms: 1.02x slower                                                |
| async_tree_cpu_io_mixed_tg | 473 ms                                                                      | 482 ms: 1.02x slower                                                |
| async_tree_io_tg           | 755 ms                                                                      | 770 ms: 1.02x slower                                                |
| async_tree_io              | 714 ms                                                                      | 730 ms: 1.02x slower                                                |
| async_tree_memoization_tg  | 357 ms                                                                      | 366 ms: 1.03x slower                                                |
| Geometric mean             | (ref)                                                                       | 1.02x slower                                                        |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 74.3 ms                                                                     | 73.1 ms: 1.02x faster                                               |
| float          | 52.3 ms                                                                     | 52.8 ms: 1.01x slower                                               |
| pidigits       | 146 ms                                                                      | 150 ms: 1.03x slower                                                |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_v8       | 15.3 ms                                                                     | 14.7 ms: 1.04x faster                                               |
| regex_effbot   | 1.59 ms                                                                     | 1.56 ms: 1.02x faster                                               |
| regex_dna      | 121 ms                                                                      | 119 ms: 1.01x faster                                                |
| regex_compile  | 79.2 ms                                                                     | 82.2 ms: 1.04x slower                                               |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads          | 1.42 sec                                                                    | 1.34 sec: 1.06x faster                                              |
| json_loads           | 13.5 us                                                                     | 13.4 us: 1.01x faster                                               |
| xml_etree_process    | 37.2 ms                                                                     | 37.0 ms: 1.00x faster                                               |
| json_dumps           | 5.69 ms                                                                     | 5.72 ms: 1.00x slower                                               |
| pickle_dict          | 18.2 us                                                                     | 18.3 us: 1.01x slower                                               |
| xml_etree_generate   | 54.2 ms                                                                     | 54.6 ms: 1.01x slower                                               |
| unpickle_list        | 2.65 us                                                                     | 2.67 us: 1.01x slower                                               |
| xml_etree_parse      | 91.0 ms                                                                     | 92.8 ms: 1.02x slower                                               |
| pickle_pure_python   | 179 us                                                                      | 183 us: 1.02x slower                                                |
| xml_etree_iterparse  | 63.0 ms                                                                     | 64.8 ms: 1.03x slower                                               |
| pickle               | 6.96 us                                                                     | 7.22 us: 1.04x slower                                               |
| unpickle_pure_python | 130 us                                                                      | 136 us: 1.05x slower                                                |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                        |

Benchmark hidden because not significant (2): unpickle, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 20.3 ms                                                                     | 20.7 ms: 1.02x slower                                               |
| python_startup_no_site | 18.3 ms                                                                     | 18.9 ms: 1.04x slower                                               |
| Geometric mean         | (ref)                                                                       | 1.03x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 6.46 ms                                                                     | 6.59 ms: 1.02x slower                                               |

All benchmarks:
===============

| Benchmark                  | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pycparser                  | 802 ms                                                                      | 712 ms: 1.13x faster                                                |
| unpack_sequence            | 47.3 ns                                                                     | 44.4 ns: 1.06x faster                                               |
| tomli_loads                | 1.42 sec                                                                    | 1.34 sec: 1.06x faster                                              |
| richards                   | 27.7 ms                                                                     | 26.2 ms: 1.06x faster                                               |
| richards_super             | 30.9 ms                                                                     | 29.3 ms: 1.05x faster                                               |
| logging_silent             | 57.6 ns                                                                     | 55.2 ns: 1.04x faster                                               |
| regex_v8                   | 15.3 ms                                                                     | 14.7 ms: 1.04x faster                                               |
| telco                      | 4.76 ms                                                                     | 4.59 ms: 1.04x faster                                               |
| generators                 | 21.3 ms                                                                     | 20.7 ms: 1.03x faster                                               |
| deepcopy_memo              | 23.8 us                                                                     | 23.2 us: 1.02x faster                                               |
| regex_effbot               | 1.59 ms                                                                     | 1.56 ms: 1.02x faster                                               |
| nbody                      | 74.3 ms                                                                     | 73.1 ms: 1.02x faster                                               |
| json_loads                 | 13.5 us                                                                     | 13.4 us: 1.01x faster                                               |
| regex_dna                  | 121 ms                                                                      | 119 ms: 1.01x faster                                                |
| xml_etree_process          | 37.2 ms                                                                     | 37.0 ms: 1.00x faster                                               |
| spectral_norm              | 62.8 ms                                                                     | 62.6 ms: 1.00x faster                                               |
| json_dumps                 | 5.69 ms                                                                     | 5.72 ms: 1.00x slower                                               |
| pickle_dict                | 18.2 us                                                                     | 18.3 us: 1.01x slower                                               |
| xml_etree_generate         | 54.2 ms                                                                     | 54.6 ms: 1.01x slower                                               |
| unpickle_list              | 2.65 us                                                                     | 2.67 us: 1.01x slower                                               |
| sqlite_synth               | 1.55 us                                                                     | 1.56 us: 1.01x slower                                               |
| typing_runtime_protocols   | 75.9 us                                                                     | 76.5 us: 1.01x slower                                               |
| scimark_sor                | 80.7 ms                                                                     | 81.4 ms: 1.01x slower                                               |
| float                      | 52.3 ms                                                                     | 52.8 ms: 1.01x slower                                               |
| pprint_pformat             | 1.01 sec                                                                    | 1.02 sec: 1.01x slower                                              |
| sympy_expand               | 271 ms                                                                      | 274 ms: 1.01x slower                                                |
| deepcopy_reduce            | 1.95 us                                                                     | 1.98 us: 1.01x slower                                               |
| deepcopy                   | 219 us                                                                      | 222 us: 1.01x slower                                                |
| async_tree_cpu_io_mixed    | 447 ms                                                                      | 453 ms: 1.01x slower                                                |
| coverage                   | 46.1 ms                                                                     | 46.7 ms: 1.01x slower                                               |
| docutils                   | 1.54 sec                                                                    | 1.56 sec: 1.01x slower                                              |
| sqlglot_optimize           | 33.2 ms                                                                     | 33.7 ms: 1.02x slower                                               |
| sqlglot_normalize          | 175 ms                                                                      | 178 ms: 1.02x slower                                                |
| sqlglot_parse              | 759 us                                                                      | 771 us: 1.02x slower                                                |
| sqlglot_transpile          | 974 us                                                                      | 990 us: 1.02x slower                                                |
| async_tree_none_tg         | 280 ms                                                                      | 285 ms: 1.02x slower                                                |
| coroutines                 | 13.3 ms                                                                     | 13.5 ms: 1.02x slower                                               |
| chameleon                  | 4.80 ms                                                                     | 4.89 ms: 1.02x slower                                               |
| python_startup             | 20.3 ms                                                                     | 20.7 ms: 1.02x slower                                               |
| sympy_sum                  | 82.8 ms                                                                     | 84.4 ms: 1.02x slower                                               |
| async_tree_cpu_io_mixed_tg | 473 ms                                                                      | 482 ms: 1.02x slower                                                |
| bench_thread_pool          | 830 us                                                                      | 847 us: 1.02x slower                                                |
| mako                       | 6.46 ms                                                                     | 6.59 ms: 1.02x slower                                               |
| xml_etree_parse            | 91.0 ms                                                                     | 92.8 ms: 1.02x slower                                               |
| dulwich_log                | 40.5 ms                                                                     | 41.3 ms: 1.02x slower                                               |
| async_tree_io_tg           | 755 ms                                                                      | 770 ms: 1.02x slower                                                |
| sympy_str                  | 158 ms                                                                      | 162 ms: 1.02x slower                                                |
| pickle_pure_python         | 179 us                                                                      | 183 us: 1.02x slower                                                |
| async_tree_io              | 714 ms                                                                      | 730 ms: 1.02x slower                                                |
| logging_format             | 6.48 us                                                                     | 6.63 us: 1.02x slower                                               |
| crypto_pyaes               | 44.6 ms                                                                     | 45.6 ms: 1.02x slower                                               |
| pprint_safe_repr           | 496 ms                                                                      | 508 ms: 1.02x slower                                                |
| meteor_contest             | 74.1 ms                                                                     | 76.0 ms: 1.03x slower                                               |
| logging_simple             | 6.07 us                                                                     | 6.23 us: 1.03x slower                                               |
| async_tree_memoization_tg  | 357 ms                                                                      | 366 ms: 1.03x slower                                                |
| fannkuch                   | 246 ms                                                                      | 253 ms: 1.03x slower                                                |
| pidigits                   | 146 ms                                                                      | 150 ms: 1.03x slower                                                |
| xml_etree_iterparse        | 63.0 ms                                                                     | 64.8 ms: 1.03x slower                                               |
| pyflate                    | 291 ms                                                                      | 301 ms: 1.03x slower                                                |
| python_startup_no_site     | 18.3 ms                                                                     | 18.9 ms: 1.04x slower                                               |
| 2to3                       | 209 ms                                                                      | 217 ms: 1.04x slower                                                |
| bench_mp_pool              | 62.4 ms                                                                     | 64.7 ms: 1.04x slower                                               |
| pickle                     | 6.96 us                                                                     | 7.22 us: 1.04x slower                                               |
| regex_compile              | 79.2 ms                                                                     | 82.2 ms: 1.04x slower                                               |
| raytrace                   | 162 ms                                                                      | 168 ms: 1.04x slower                                                |
| chaos                      | 40.6 ms                                                                     | 42.3 ms: 1.04x slower                                               |
| async_generators           | 226 ms                                                                      | 235 ms: 1.04x slower                                                |
| scimark_sparse_mat_mult    | 2.38 ms                                                                     | 2.49 ms: 1.04x slower                                               |
| mdp                        | 1.35 sec                                                                    | 1.41 sec: 1.05x slower                                              |
| unpickle_pure_python       | 130 us                                                                      | 136 us: 1.05x slower                                                |
| sympy_integrate            | 12.3 ms                                                                     | 12.9 ms: 1.05x slower                                               |
| go                         | 86.5 ms                                                                     | 91.3 ms: 1.06x slower                                               |
| deltablue                  | 2.06 ms                                                                     | 2.17 ms: 1.06x slower                                               |
| scimark_fft                | 174 ms                                                                      | 188 ms: 1.08x slower                                                |
| scimark_lu                 | 54.4 ms                                                                     | 59.2 ms: 1.09x slower                                               |
| scimark_monte_carlo        | 40.3 ms                                                                     | 44.1 ms: 1.10x slower                                               |
| comprehensions             | 10.6 us                                                                     | 11.8 us: 1.11x slower                                               |
| nqueens                    | 57.4 ms                                                                     | 64.1 ms: 1.12x slower                                               |
| hexiom                     | 3.85 ms                                                                     | 4.56 ms: 1.18x slower                                               |
| Geometric mean             | (ref)                                                                       | 1.02x slower                                                        |

Benchmark hidden because not significant (12): asyncio_tcp_ssl, json, unpickle, gc_traversal, pathlib, tornado_http, pickle_list, create_gc_cycles, async_tree_memoization, asyncio_tcp, async_tree_none, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
