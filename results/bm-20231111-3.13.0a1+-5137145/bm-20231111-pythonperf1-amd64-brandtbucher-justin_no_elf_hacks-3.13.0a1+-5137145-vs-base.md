
# Results vs. base

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: windows-amd64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 208 ms                                                                      | 216 ms: 1.04x slower                                                             |
| chameleon      | 4.68 ms                                                                     | 4.98 ms: 1.06x slower                                                            |
| docutils       | 1.53 sec                                                                    | 1.56 sec: 1.02x slower                                                           |
| tornado_http   | 87.7 ms                                                                     | 89.0 ms: 1.01x slower                                                            |
| Geometric mean | (ref)                                                                       | 1.03x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|---------------------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_io_tg          | 759 ms                                                                      | 769 ms: 1.01x slower                                                             |
| async_tree_memoization_tg | 358 ms                                                                      | 364 ms: 1.02x slower                                                             |
| async_tree_none_tg        | 278 ms                                                                      | 286 ms: 1.03x slower                                                             |
| Geometric mean            | (ref)                                                                       | 1.01x slower                                                                     |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 147 ms                                                                      | 150 ms: 1.02x slower                                                             |
| nbody          | 70.2 ms                                                                     | 71.9 ms: 1.02x slower                                                            |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                                     |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_v8       | 15.3 ms                                                                     | 14.7 ms: 1.04x faster                                                            |
| regex_effbot   | 1.61 ms                                                                     | 1.57 ms: 1.03x faster                                                            |
| regex_dna      | 121 ms                                                                      | 119 ms: 1.02x faster                                                             |
| regex_compile  | 78.7 ms                                                                     | 81.7 ms: 1.04x slower                                                            |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| tomli_loads          | 1.42 sec                                                                    | 1.32 sec: 1.08x faster                                                           |
| pickle_dict          | 18.9 us                                                                     | 18.4 us: 1.03x faster                                                            |
| pickle               | 7.13 us                                                                     | 7.07 us: 1.01x faster                                                            |
| xml_etree_parse      | 92.9 ms                                                                     | 92.1 ms: 1.01x faster                                                            |
| xml_etree_process    | 36.8 ms                                                                     | 37.0 ms: 1.00x slower                                                            |
| json_loads           | 13.4 us                                                                     | 13.5 us: 1.01x slower                                                            |
| pickle_pure_python   | 178 us                                                                      | 182 us: 1.02x slower                                                             |
| unpickle_list        | 2.63 us                                                                     | 2.71 us: 1.03x slower                                                            |
| pickle_list          | 2.82 us                                                                     | 2.91 us: 1.03x slower                                                            |
| json_dumps           | 5.57 ms                                                                     | 5.79 ms: 1.04x slower                                                            |
| unpickle_pure_python | 124 us                                                                      | 136 us: 1.10x slower                                                             |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                                     |

Benchmark hidden because not significant (3): unpickle, xml_etree_iterparse, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 19.8 ms                                                                     | 20.0 ms: 1.01x slower                                                            |
| python_startup_no_site | 17.9 ms                                                                     | 18.1 ms: 1.01x slower                                                            |
| Geometric mean         | (ref)                                                                       | 1.01x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 6.39 ms                                                                     | 6.48 ms: 1.01x slower                                                            |

All benchmarks:
===============

| Benchmark                 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|---------------------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| tomli_loads               | 1.42 sec                                                                    | 1.32 sec: 1.08x faster                                                           |
| richards_super            | 30.6 ms                                                                     | 29.0 ms: 1.05x faster                                                            |
| richards                  | 27.3 ms                                                                     | 25.9 ms: 1.05x faster                                                            |
| regex_v8                  | 15.3 ms                                                                     | 14.7 ms: 1.04x faster                                                            |
| spectral_norm             | 60.2 ms                                                                     | 58.3 ms: 1.03x faster                                                            |
| pickle_dict               | 18.9 us                                                                     | 18.4 us: 1.03x faster                                                            |
| regex_effbot              | 1.61 ms                                                                     | 1.57 ms: 1.03x faster                                                            |
| deepcopy_reduce           | 2.00 us                                                                     | 1.96 us: 1.02x faster                                                            |
| regex_dna                 | 121 ms                                                                      | 119 ms: 1.02x faster                                                             |
| create_gc_cycles          | 730 us                                                                      | 721 us: 1.01x faster                                                             |
| telco                     | 4.72 ms                                                                     | 4.66 ms: 1.01x faster                                                            |
| pickle                    | 7.13 us                                                                     | 7.07 us: 1.01x faster                                                            |
| xml_etree_parse           | 92.9 ms                                                                     | 92.1 ms: 1.01x faster                                                            |
| generators                | 21.0 ms                                                                     | 20.9 ms: 1.01x faster                                                            |
| sqlite_synth              | 1.54 us                                                                     | 1.55 us: 1.00x slower                                                            |
| xml_etree_process         | 36.8 ms                                                                     | 37.0 ms: 1.00x slower                                                            |
| meteor_contest            | 74.5 ms                                                                     | 74.9 ms: 1.01x slower                                                            |
| coverage                  | 44.1 ms                                                                     | 44.5 ms: 1.01x slower                                                            |
| python_startup            | 19.8 ms                                                                     | 20.0 ms: 1.01x slower                                                            |
| json_loads                | 13.4 us                                                                     | 13.5 us: 1.01x slower                                                            |
| python_startup_no_site    | 17.9 ms                                                                     | 18.1 ms: 1.01x slower                                                            |
| mako                      | 6.39 ms                                                                     | 6.48 ms: 1.01x slower                                                            |
| async_tree_io_tg          | 759 ms                                                                      | 769 ms: 1.01x slower                                                             |
| tornado_http              | 87.7 ms                                                                     | 89.0 ms: 1.01x slower                                                            |
| coroutines                | 13.2 ms                                                                     | 13.4 ms: 1.02x slower                                                            |
| logging_format            | 6.43 us                                                                     | 6.54 us: 1.02x slower                                                            |
| async_tree_memoization_tg | 358 ms                                                                      | 364 ms: 1.02x slower                                                             |
| logging_simple            | 6.00 us                                                                     | 6.11 us: 1.02x slower                                                            |
| docutils                  | 1.53 sec                                                                    | 1.56 sec: 1.02x slower                                                           |
| pickle_pure_python        | 178 us                                                                      | 182 us: 1.02x slower                                                             |
| pidigits                  | 147 ms                                                                      | 150 ms: 1.02x slower                                                             |
| nbody                     | 70.2 ms                                                                     | 71.9 ms: 1.02x slower                                                            |
| raytrace                  | 165 ms                                                                      | 169 ms: 1.02x slower                                                             |
| dulwich_log               | 40.2 ms                                                                     | 41.3 ms: 1.03x slower                                                            |
| sympy_str                 | 156 ms                                                                      | 160 ms: 1.03x slower                                                             |
| unpickle_list             | 2.63 us                                                                     | 2.71 us: 1.03x slower                                                            |
| async_tree_none_tg        | 278 ms                                                                      | 286 ms: 1.03x slower                                                             |
| logging_silent            | 55.2 ns                                                                     | 56.9 ns: 1.03x slower                                                            |
| sympy_expand              | 265 ms                                                                      | 274 ms: 1.03x slower                                                             |
| sqlglot_parse             | 755 us                                                                      | 779 us: 1.03x slower                                                             |
| pickle_list               | 2.82 us                                                                     | 2.91 us: 1.03x slower                                                            |
| typing_runtime_protocols  | 73.8 us                                                                     | 76.5 us: 1.04x slower                                                            |
| regex_compile             | 78.7 ms                                                                     | 81.7 ms: 1.04x slower                                                            |
| bench_mp_pool             | 62.3 ms                                                                     | 64.8 ms: 1.04x slower                                                            |
| 2to3                      | 208 ms                                                                      | 216 ms: 1.04x slower                                                             |
| json_dumps                | 5.57 ms                                                                     | 5.79 ms: 1.04x slower                                                            |
| sqlglot_transpile         | 967 us                                                                      | 1.01 ms: 1.04x slower                                                            |
| deltablue                 | 2.05 ms                                                                     | 2.13 ms: 1.04x slower                                                            |
| sympy_sum                 | 81.9 ms                                                                     | 85.4 ms: 1.04x slower                                                            |
| async_generators          | 227 ms                                                                      | 238 ms: 1.05x slower                                                             |
| sqlglot_optimize          | 32.7 ms                                                                     | 34.2 ms: 1.05x slower                                                            |
| sqlglot_normalize         | 173 ms                                                                      | 181 ms: 1.05x slower                                                             |
| pyflate                   | 286 ms                                                                      | 300 ms: 1.05x slower                                                             |
| scimark_sparse_mat_mult   | 2.31 ms                                                                     | 2.43 ms: 1.05x slower                                                            |
| chaos                     | 39.3 ms                                                                     | 41.4 ms: 1.05x slower                                                            |
| sympy_integrate           | 12.2 ms                                                                     | 12.8 ms: 1.05x slower                                                            |
| pprint_safe_repr          | 489 ms                                                                      | 516 ms: 1.06x slower                                                             |
| pprint_pformat            | 998 ms                                                                      | 1.05 sec: 1.06x slower                                                           |
| chameleon                 | 4.68 ms                                                                     | 4.98 ms: 1.06x slower                                                            |
| mdp                       | 1.39 sec                                                                    | 1.49 sec: 1.07x slower                                                           |
| unpack_sequence           | 37.4 ns                                                                     | 40.2 ns: 1.07x slower                                                            |
| fannkuch                  | 232 ms                                                                      | 250 ms: 1.07x slower                                                             |
| scimark_lu                | 54.6 ms                                                                     | 58.8 ms: 1.08x slower                                                            |
| go                        | 84.1 ms                                                                     | 90.8 ms: 1.08x slower                                                            |
| crypto_pyaes              | 41.9 ms                                                                     | 45.3 ms: 1.08x slower                                                            |
| scimark_monte_carlo       | 40.4 ms                                                                     | 44.3 ms: 1.10x slower                                                            |
| unpickle_pure_python      | 124 us                                                                      | 136 us: 1.10x slower                                                             |
| json                      | 2.81 ms                                                                     | 3.09 ms: 1.10x slower                                                            |
| scimark_sor               | 76.0 ms                                                                     | 84.0 ms: 1.11x slower                                                            |
| comprehensions            | 10.2 us                                                                     | 11.5 us: 1.13x slower                                                            |
| nqueens                   | 55.3 ms                                                                     | 62.8 ms: 1.14x slower                                                            |
| scimark_fft               | 168 ms                                                                      | 191 ms: 1.14x slower                                                             |
| hexiom                    | 3.68 ms                                                                     | 4.37 ms: 1.19x slower                                                            |
| Geometric mean            | (ref)                                                                       | 1.03x slower                                                                     |

Benchmark hidden because not significant (18): asyncio_tcp, unpickle, async_tree_cpu_io_mixed_tg, xml_etree_iterparse, float, asyncio_tcp_ssl, gc_traversal, async_tree_cpu_io_mixed, pathlib, deepcopy, xml_etree_generate, deepcopy_memo, pycparser, bench_thread_pool, async_tree_io, async_tree_memoization, async_tree_none, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
