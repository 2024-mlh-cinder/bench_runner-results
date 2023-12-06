
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: windows-amd64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.00x faster \*
- HPT reliability: 73.15%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 216 ms: 1.02x slower                                                             |
| chameleon      | 4.95 ms                                                     | 4.98 ms: 1.01x slower                                                            |
| docutils       | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                                           |
| tornado_http   | 87.2 ms                                                     | 89.0 ms: 1.02x slower                                                            |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|---------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 271 ms: 1.05x faster                                                             |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 456 ms: 1.05x faster                                                             |
| async_tree_io             | 712 ms                                                      | 725 ms: 1.02x slower                                                             |
| async_tree_none_tg        | 277 ms                                                      | 286 ms: 1.03x slower                                                             |
| async_tree_io_tg          | 742 ms                                                      | 769 ms: 1.04x slower                                                             |
| async_tree_memoization    | 333 ms                                                      | 346 ms: 1.04x slower                                                             |
| async_tree_memoization_tg | 345 ms                                                      | 364 ms: 1.06x slower                                                             |
| Geometric mean            | (ref)                                                       | 1.01x slower                                                                     |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 51.5 ms: 1.06x faster                                                            |
| nbody          | 68.8 ms                                                     | 71.9 ms: 1.05x slower                                                            |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                     |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 81.7 ms: 1.07x faster                                                            |
| regex_effbot   | 1.58 ms                                                     | 1.57 ms: 1.01x faster                                                            |
| regex_v8       | 13.5 ms                                                     | 14.7 ms: 1.09x slower                                                            |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                     |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 182 us: 1.07x faster                                                             |
| tomli_loads          | 1.38 sec                                                    | 1.32 sec: 1.05x faster                                                           |
| pickle               | 7.38 us                                                     | 7.07 us: 1.04x faster                                                            |
| pickle_dict          | 18.9 us                                                     | 18.4 us: 1.03x faster                                                            |
| xml_etree_generate   | 55.8 ms                                                     | 54.2 ms: 1.03x faster                                                            |
| unpickle             | 8.44 us                                                     | 8.22 us: 1.03x faster                                                            |
| xml_etree_process    | 37.6 ms                                                     | 37.0 ms: 1.02x faster                                                            |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                                            |
| json_dumps           | 5.83 ms                                                     | 5.79 ms: 1.01x faster                                                            |
| pickle_list          | 2.88 us                                                     | 2.91 us: 1.01x slower                                                            |
| unpickle_pure_python | 134 us                                                      | 136 us: 1.01x slower                                                             |
| xml_etree_parse      | 90.5 ms                                                     | 92.1 ms: 1.02x slower                                                            |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                     |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                            |
| python_startup_no_site | 15.9 ms                                                     | 18.1 ms: 1.14x slower                                                            |
| Geometric mean         | (ref)                                                       | 1.10x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.48 ms: 1.09x faster                                                            |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|---------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols  | 96.7 us                                                     | 76.5 us: 1.26x faster                                                            |
| comprehensions            | 14.0 us                                                     | 11.5 us: 1.22x faster                                                            |
| raytrace                  | 192 ms                                                      | 169 ms: 1.14x faster                                                             |
| sqlite_synth              | 1.75 us                                                     | 1.55 us: 1.13x faster                                                            |
| spectral_norm             | 63.9 ms                                                     | 58.3 ms: 1.10x faster                                                            |
| mako                      | 7.05 ms                                                     | 6.48 ms: 1.09x faster                                                            |
| generators                | 22.6 ms                                                     | 20.9 ms: 1.08x faster                                                            |
| richards_super            | 31.2 ms                                                     | 29.0 ms: 1.08x faster                                                            |
| sympy_str                 | 171 ms                                                      | 160 ms: 1.07x faster                                                             |
| pickle_pure_python        | 195 us                                                      | 182 us: 1.07x faster                                                             |
| regex_compile             | 87.2 ms                                                     | 81.7 ms: 1.07x faster                                                            |
| richards                  | 27.6 ms                                                     | 25.9 ms: 1.07x faster                                                            |
| deepcopy                  | 233 us                                                      | 218 us: 1.07x faster                                                             |
| deepcopy_reduce           | 2.08 us                                                     | 1.96 us: 1.06x faster                                                            |
| logging_silent            | 60.5 ns                                                     | 56.9 ns: 1.06x faster                                                            |
| float                     | 54.7 ms                                                     | 51.5 ms: 1.06x faster                                                            |
| coroutines                | 14.1 ms                                                     | 13.4 ms: 1.06x faster                                                            |
| sympy_sum                 | 90.1 ms                                                     | 85.4 ms: 1.05x faster                                                            |
| async_tree_none           | 286 ms                                                      | 271 ms: 1.05x faster                                                             |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 456 ms: 1.05x faster                                                             |
| tomli_loads               | 1.38 sec                                                    | 1.32 sec: 1.05x faster                                                           |
| pickle                    | 7.38 us                                                     | 7.07 us: 1.04x faster                                                            |
| bench_mp_pool             | 67.2 ms                                                     | 64.8 ms: 1.04x faster                                                            |
| dulwich_log               | 42.7 ms                                                     | 41.3 ms: 1.03x faster                                                            |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.43 ms: 1.03x faster                                                            |
| pickle_dict               | 18.9 us                                                     | 18.4 us: 1.03x faster                                                            |
| sqlglot_parse             | 802 us                                                      | 779 us: 1.03x faster                                                             |
| xml_etree_generate        | 55.8 ms                                                     | 54.2 ms: 1.03x faster                                                            |
| docutils                  | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                                           |
| logging_format            | 6.72 us                                                     | 6.54 us: 1.03x faster                                                            |
| unpickle                  | 8.44 us                                                     | 8.22 us: 1.03x faster                                                            |
| crypto_pyaes              | 46.4 ms                                                     | 45.3 ms: 1.02x faster                                                            |
| chaos                     | 42.1 ms                                                     | 41.4 ms: 1.02x faster                                                            |
| xml_etree_process         | 37.6 ms                                                     | 37.0 ms: 1.02x faster                                                            |
| sympy_expand              | 278 ms                                                      | 274 ms: 1.02x faster                                                             |
| logging_simple            | 6.21 us                                                     | 6.11 us: 1.02x faster                                                            |
| sqlglot_normalize         | 183 ms                                                      | 181 ms: 1.01x faster                                                             |
| sqlglot_transpile         | 1.02 ms                                                     | 1.01 ms: 1.01x faster                                                            |
| sympy_integrate           | 13.0 ms                                                     | 12.8 ms: 1.01x faster                                                            |
| json_loads                | 13.6 us                                                     | 13.5 us: 1.01x faster                                                            |
| json_dumps                | 5.83 ms                                                     | 5.79 ms: 1.01x faster                                                            |
| regex_effbot              | 1.58 ms                                                     | 1.57 ms: 1.01x faster                                                            |
| deltablue                 | 2.12 ms                                                     | 2.13 ms: 1.00x slower                                                            |
| sqlglot_optimize          | 34.0 ms                                                     | 34.2 ms: 1.00x slower                                                            |
| chameleon                 | 4.95 ms                                                     | 4.98 ms: 1.01x slower                                                            |
| pickle_list               | 2.88 us                                                     | 2.91 us: 1.01x slower                                                            |
| unpickle_pure_python      | 134 us                                                      | 136 us: 1.01x slower                                                             |
| 2to3                      | 213 ms                                                      | 216 ms: 1.02x slower                                                             |
| nqueens                   | 61.7 ms                                                     | 62.8 ms: 1.02x slower                                                            |
| pprint_safe_repr          | 508 ms                                                      | 516 ms: 1.02x slower                                                             |
| pprint_pformat            | 1.04 sec                                                    | 1.05 sec: 1.02x slower                                                           |
| xml_etree_parse           | 90.5 ms                                                     | 92.1 ms: 1.02x slower                                                            |
| async_tree_io             | 712 ms                                                      | 725 ms: 1.02x slower                                                             |
| go                        | 89.0 ms                                                     | 90.8 ms: 1.02x slower                                                            |
| tornado_http              | 87.2 ms                                                     | 89.0 ms: 1.02x slower                                                            |
| pyflate                   | 294 ms                                                      | 300 ms: 1.02x slower                                                             |
| fannkuch                  | 244 ms                                                      | 250 ms: 1.02x slower                                                             |
| scimark_lu                | 57.5 ms                                                     | 58.8 ms: 1.02x slower                                                            |
| scimark_monte_carlo       | 43.0 ms                                                     | 44.3 ms: 1.03x slower                                                            |
| async_tree_none_tg        | 277 ms                                                      | 286 ms: 1.03x slower                                                             |
| async_generators          | 230 ms                                                      | 238 ms: 1.03x slower                                                             |
| async_tree_io_tg          | 742 ms                                                      | 769 ms: 1.04x slower                                                             |
| async_tree_memoization    | 333 ms                                                      | 346 ms: 1.04x slower                                                             |
| meteor_contest            | 72.1 ms                                                     | 74.9 ms: 1.04x slower                                                            |
| nbody                     | 68.8 ms                                                     | 71.9 ms: 1.05x slower                                                            |
| mdp                       | 1.42 sec                                                    | 1.49 sec: 1.05x slower                                                           |
| scimark_sor               | 79.8 ms                                                     | 84.0 ms: 1.05x slower                                                            |
| async_tree_memoization_tg | 345 ms                                                      | 364 ms: 1.06x slower                                                             |
| scimark_fft               | 181 ms                                                      | 191 ms: 1.06x slower                                                             |
| python_startup            | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                            |
| unpack_sequence           | 36.9 ns                                                     | 40.2 ns: 1.09x slower                                                            |
| hexiom                    | 4.00 ms                                                     | 4.37 ms: 1.09x slower                                                            |
| regex_v8                  | 13.5 ms                                                     | 14.7 ms: 1.09x slower                                                            |
| pycparser                 | 673 ms                                                      | 748 ms: 1.11x slower                                                             |
| coverage                  | 39.8 ms                                                     | 44.5 ms: 1.12x slower                                                            |
| python_startup_no_site    | 15.9 ms                                                     | 18.1 ms: 1.14x slower                                                            |
| telco                     | 4.08 ms                                                     | 4.66 ms: 1.14x slower                                                            |
| mypy2                     | 209 ms                                                      | 293 ms: 1.40x slower                                                             |
| Geometric mean            | (ref)                                                       | 1.00x faster                                                                     |

Benchmark hidden because not significant (13): create_gc_cycles, pathlib, async_tree_cpu_io_mixed_tg, deepcopy_memo, asyncio_tcp, regex_dna, pidigits, xml_etree_iterparse, gc_traversal, bench_thread_pool, unpickle_list, asyncio_tcp_ssl, json
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 73.15% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
