
# Results vs. base

- fork: python
- ref: 6dfb8fe0236718e9afc8
- machine: windows-amd64
- commit hash: 6dfb8fe
- commit date: 2023-10-30
- overall geometric mean: 1.01x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| chameleon      | 5.27 ms                                                                     | 5.22 ms: 1.01x faster                                                       |
| docutils       | 1.65 sec                                                                    | 1.64 sec: 1.01x faster                                                      |
| tornado_http   | 90.3 ms                                                                     | 89.4 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_memoization     | 362 ms                                                                      | 355 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed_tg | 494 ms                                                                      | 485 ms: 1.02x faster                                                        |
| async_tree_io              | 767 ms                                                                      | 753 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed    | 473 ms                                                                      | 465 ms: 1.02x faster                                                        |
| async_tree_io_tg           | 791 ms                                                                      | 780 ms: 1.01x faster                                                        |
| async_tree_none_tg         | 295 ms                                                                      | 291 ms: 1.01x faster                                                        |
| Geometric mean             | (ref)                                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (2): async_tree_none, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 148 ms                                                                      | 147 ms: 1.00x faster                                                        |
| nbody          | 74.3 ms                                                                     | 75.2 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                                      | 121 ms: 1.00x faster                                                        |
| regex_compile  | 92.8 ms                                                                     | 92.5 ms: 1.00x faster                                                       |
| regex_effbot   | 1.60 ms                                                                     | 1.61 ms: 1.01x slower                                                       |
| regex_v8       | 15.2 ms                                                                     | 15.5 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_dict          | 18.8 us                                                                     | 18.2 us: 1.03x faster                                                       |
| unpickle             | 8.31 us                                                                     | 8.14 us: 1.02x faster                                                       |
| xml_etree_parse      | 93.0 ms                                                                     | 91.9 ms: 1.01x faster                                                       |
| xml_etree_process    | 39.9 ms                                                                     | 39.5 ms: 1.01x faster                                                       |
| pickle               | 6.98 us                                                                     | 6.94 us: 1.01x faster                                                       |
| unpickle_pure_python | 139 us                                                                      | 140 us: 1.01x slower                                                        |
| json_dumps           | 5.73 ms                                                                     | 5.77 ms: 1.01x slower                                                       |
| unpickle_list        | 2.64 us                                                                     | 2.67 us: 1.01x slower                                                       |
| json_loads           | 13.6 us                                                                     | 13.8 us: 1.01x slower                                                       |
| pickle_list          | 2.84 us                                                                     | 2.89 us: 1.02x slower                                                       |
| Geometric mean       | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (4): xml_etree_iterparse, pickle_pure_python, tomli_loads, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup | 20.6 ms                                                                     | 19.8 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| asyncio_tcp_ssl            | 1.98 sec                                                                    | 1.86 sec: 1.06x faster                                                      |
| scimark_fft                | 186 ms                                                                      | 178 ms: 1.04x faster                                                        |
| scimark_sparse_mat_mult    | 2.60 ms                                                                     | 2.49 ms: 1.04x faster                                                       |
| scimark_sor                | 80.6 ms                                                                     | 77.6 ms: 1.04x faster                                                       |
| python_startup             | 20.6 ms                                                                     | 19.8 ms: 1.04x faster                                                       |
| pickle_dict                | 18.8 us                                                                     | 18.2 us: 1.03x faster                                                       |
| coverage                   | 46.1 ms                                                                     | 44.9 ms: 1.03x faster                                                       |
| sympy_expand               | 305 ms                                                                      | 297 ms: 1.02x faster                                                        |
| async_tree_memoization     | 362 ms                                                                      | 355 ms: 1.02x faster                                                        |
| unpickle                   | 8.31 us                                                                     | 8.14 us: 1.02x faster                                                       |
| deepcopy_reduce            | 2.25 us                                                                     | 2.21 us: 1.02x faster                                                       |
| typing_runtime_protocols   | 101 us                                                                      | 98.7 us: 1.02x faster                                                       |
| async_tree_cpu_io_mixed_tg | 494 ms                                                                      | 485 ms: 1.02x faster                                                        |
| nqueens                    | 63.0 ms                                                                     | 61.9 ms: 1.02x faster                                                       |
| async_tree_io              | 767 ms                                                                      | 753 ms: 1.02x faster                                                        |
| sympy_str                  | 175 ms                                                                      | 172 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed    | 473 ms                                                                      | 465 ms: 1.02x faster                                                        |
| deepcopy                   | 250 us                                                                      | 246 us: 1.02x faster                                                        |
| deltablue                  | 2.25 ms                                                                     | 2.22 ms: 1.01x faster                                                       |
| dulwich_log                | 45.6 ms                                                                     | 45.0 ms: 1.01x faster                                                       |
| async_tree_io_tg           | 791 ms                                                                      | 780 ms: 1.01x faster                                                        |
| coroutines                 | 14.7 ms                                                                     | 14.5 ms: 1.01x faster                                                       |
| async_tree_none_tg         | 295 ms                                                                      | 291 ms: 1.01x faster                                                        |
| raytrace                   | 180 ms                                                                      | 178 ms: 1.01x faster                                                        |
| xml_etree_parse            | 93.0 ms                                                                     | 91.9 ms: 1.01x faster                                                       |
| chameleon                  | 5.27 ms                                                                     | 5.22 ms: 1.01x faster                                                       |
| xml_etree_process          | 39.9 ms                                                                     | 39.5 ms: 1.01x faster                                                       |
| tornado_http               | 90.3 ms                                                                     | 89.4 ms: 1.01x faster                                                       |
| pprint_safe_repr           | 540 ms                                                                      | 535 ms: 1.01x faster                                                        |
| sqlglot_normalize          | 197 ms                                                                      | 195 ms: 1.01x faster                                                        |
| docutils                   | 1.65 sec                                                                    | 1.64 sec: 1.01x faster                                                      |
| sqlglot_optimize           | 36.7 ms                                                                     | 36.4 ms: 1.01x faster                                                       |
| generators                 | 23.5 ms                                                                     | 23.3 ms: 1.01x faster                                                       |
| scimark_lu                 | 58.0 ms                                                                     | 57.6 ms: 1.01x faster                                                       |
| sqlglot_transpile          | 1.08 ms                                                                     | 1.08 ms: 1.01x faster                                                       |
| spectral_norm              | 63.9 ms                                                                     | 63.5 ms: 1.01x faster                                                       |
| mypy2                      | 218 ms                                                                      | 217 ms: 1.01x faster                                                        |
| pickle                     | 6.98 us                                                                     | 6.94 us: 1.01x faster                                                       |
| chaos                      | 43.3 ms                                                                     | 43.1 ms: 1.00x faster                                                       |
| regex_dna                  | 121 ms                                                                      | 121 ms: 1.00x faster                                                        |
| pidigits                   | 148 ms                                                                      | 147 ms: 1.00x faster                                                        |
| telco                      | 4.79 ms                                                                     | 4.77 ms: 1.00x faster                                                       |
| regex_compile              | 92.8 ms                                                                     | 92.5 ms: 1.00x faster                                                       |
| logging_silent             | 62.7 ns                                                                     | 62.9 ns: 1.00x slower                                                       |
| sqlite_synth               | 1.56 us                                                                     | 1.57 us: 1.00x slower                                                       |
| scimark_monte_carlo        | 42.3 ms                                                                     | 42.6 ms: 1.01x slower                                                       |
| unpickle_pure_python       | 139 us                                                                      | 140 us: 1.01x slower                                                        |
| regex_effbot               | 1.60 ms                                                                     | 1.61 ms: 1.01x slower                                                       |
| fannkuch                   | 261 ms                                                                      | 263 ms: 1.01x slower                                                        |
| json_dumps                 | 5.73 ms                                                                     | 5.77 ms: 1.01x slower                                                       |
| crypto_pyaes               | 44.2 ms                                                                     | 44.6 ms: 1.01x slower                                                       |
| unpickle_list              | 2.64 us                                                                     | 2.67 us: 1.01x slower                                                       |
| json_loads                 | 13.6 us                                                                     | 13.8 us: 1.01x slower                                                       |
| comprehensions             | 11.3 us                                                                     | 11.4 us: 1.01x slower                                                       |
| richards_super             | 33.8 ms                                                                     | 34.2 ms: 1.01x slower                                                       |
| logging_simple             | 6.75 us                                                                     | 6.83 us: 1.01x slower                                                       |
| nbody                      | 74.3 ms                                                                     | 75.2 ms: 1.01x slower                                                       |
| meteor_contest             | 75.6 ms                                                                     | 76.6 ms: 1.01x slower                                                       |
| go                         | 95.9 ms                                                                     | 97.3 ms: 1.01x slower                                                       |
| mdp                        | 1.49 sec                                                                    | 1.51 sec: 1.02x slower                                                      |
| pickle_list                | 2.84 us                                                                     | 2.89 us: 1.02x slower                                                       |
| regex_v8                   | 15.2 ms                                                                     | 15.5 ms: 1.02x slower                                                       |
| unpack_sequence            | 37.8 ns                                                                     | 38.7 ns: 1.02x slower                                                       |
| json                       | 2.89 ms                                                                     | 3.03 ms: 1.05x slower                                                       |
| Geometric mean             | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (27): async_tree_none, bench_thread_pool, async_tree_memoization_tg, deepcopy_memo, pycparser, create_gc_cycles, float, xml_etree_iterparse, hexiom, pickle_pure_python, sqlglot_parse, python_startup_no_site, pyflate, pprint_pformat, gc_traversal, async_generators, sympy_integrate, bench_mp_pool, tomli_loads, pathlib, richards, sympy_sum, logging_format, 2to3, xml_etree_generate, mako, asyncio_tcp


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
