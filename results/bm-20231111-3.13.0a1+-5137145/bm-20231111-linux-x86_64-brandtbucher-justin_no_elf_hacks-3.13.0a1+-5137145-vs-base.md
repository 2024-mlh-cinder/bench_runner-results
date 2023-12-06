
# Results vs. base

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: linux-x86_64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 261 ms                                                                 | 274 ms: 1.05x slower                                                        |
| chameleon      | 7.01 ms                                                                | 7.32 ms: 1.04x slower                                                       |
| docutils       | 2.59 sec                                                               | 2.65 sec: 1.02x slower                                                      |
| tornado_http   | 94.7 ms                                                                | 96.4 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|---------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io_tg          | 1.23 sec                                                               | 1.24 sec: 1.01x slower                                                      |
| async_tree_io             | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                                      |
| async_tree_none_tg        | 456 ms                                                                 | 460 ms: 1.01x slower                                                        |
| async_tree_memoization_tg | 597 ms                                                                 | 604 ms: 1.01x slower                                                        |
| async_tree_memoization    | 563 ms                                                                 | 571 ms: 1.01x slower                                                        |
| async_tree_cpu_io_mixed   | 713 ms                                                                 | 724 ms: 1.02x slower                                                        |
| Geometric mean            | (ref)                                                                  | 1.01x slower                                                                |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 195 ms: 1.00x slower                                                        |
| float          | 81.1 ms                                                                | 88.0 ms: 1.08x slower                                                       |
| nbody          | 89.3 ms                                                                | 103 ms: 1.15x slower                                                        |
| Geometric mean | (ref)                                                                  | 1.08x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 222 ms                                                                 | 216 ms: 1.03x faster                                                        |
| regex_effbot   | 3.68 ms                                                                | 3.62 ms: 1.02x faster                                                       |
| regex_v8       | 24.4 ms                                                                | 25.7 ms: 1.05x slower                                                       |
| regex_compile  | 134 ms                                                                 | 142 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_list          | 5.10 us                                                                | 5.01 us: 1.02x faster                                                       |
| json_loads           | 27.8 us                                                                | 27.6 us: 1.01x faster                                                       |
| pickle_pure_python   | 302 us                                                                 | 304 us: 1.01x slower                                                        |
| unpickle             | 14.8 us                                                                | 14.9 us: 1.01x slower                                                       |
| json_dumps           | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                                       |
| pickle_dict          | 34.1 us                                                                | 34.7 us: 1.02x slower                                                       |
| pickle               | 11.1 us                                                                | 11.3 us: 1.02x slower                                                       |
| xml_etree_generate   | 85.8 ms                                                                | 87.7 ms: 1.02x slower                                                       |
| xml_etree_process    | 58.7 ms                                                                | 60.0 ms: 1.02x slower                                                       |
| xml_etree_iterparse  | 104 ms                                                                 | 108 ms: 1.04x slower                                                        |
| unpickle_list        | 5.40 us                                                                | 5.69 us: 1.05x slower                                                       |
| unpickle_pure_python | 219 us                                                                 | 233 us: 1.06x slower                                                        |
| tomli_loads          | 2.11 sec                                                               | 2.28 sec: 1.08x slower                                                      |
| Geometric mean       | (ref)                                                                  | 1.02x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                                       |
| python_startup_no_site | 8.97 ms                                                                | 9.06 ms: 1.01x slower                                                       |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 11.3 ms                                                                | 12.4 ms: 1.10x slower                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|---------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence           | 43.9 ns                                                                | 40.5 ns: 1.08x faster                                                       |
| mdp                       | 2.75 sec                                                               | 2.65 sec: 1.04x faster                                                      |
| regex_dna                 | 222 ms                                                                 | 216 ms: 1.03x faster                                                        |
| richards                  | 48.0 ms                                                                | 47.0 ms: 1.02x faster                                                       |
| pickle_list               | 5.10 us                                                                | 5.01 us: 1.02x faster                                                       |
| richards_super            | 54.4 ms                                                                | 53.5 ms: 1.02x faster                                                       |
| regex_effbot              | 3.68 ms                                                                | 3.62 ms: 1.02x faster                                                       |
| coverage                  | 95.5 ms                                                                | 94.6 ms: 1.01x faster                                                       |
| json_loads                | 27.8 us                                                                | 27.6 us: 1.01x faster                                                       |
| coroutines                | 21.9 ms                                                                | 21.8 ms: 1.01x faster                                                       |
| pidigits                  | 195 ms                                                                 | 195 ms: 1.00x slower                                                        |
| asyncio_tcp_ssl           | 1.79 sec                                                               | 1.79 sec: 1.00x slower                                                      |
| pickle_pure_python        | 302 us                                                                 | 304 us: 1.01x slower                                                        |
| unpickle                  | 14.8 us                                                                | 14.9 us: 1.01x slower                                                       |
| async_tree_io_tg          | 1.23 sec                                                               | 1.24 sec: 1.01x slower                                                      |
| async_tree_io             | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                                      |
| python_startup            | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                                       |
| scimark_lu                | 116 ms                                                                 | 117 ms: 1.01x slower                                                        |
| async_tree_none_tg        | 456 ms                                                                 | 460 ms: 1.01x slower                                                        |
| asyncio_tcp               | 491 ms                                                                 | 495 ms: 1.01x slower                                                        |
| python_startup_no_site    | 8.97 ms                                                                | 9.06 ms: 1.01x slower                                                       |
| telco                     | 8.41 ms                                                                | 8.50 ms: 1.01x slower                                                       |
| sqlglot_optimize          | 53.2 ms                                                                | 53.9 ms: 1.01x slower                                                       |
| json_dumps                | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                                       |
| async_tree_memoization_tg | 597 ms                                                                 | 604 ms: 1.01x slower                                                        |
| pathlib                   | 19.2 ms                                                                | 19.5 ms: 1.01x slower                                                       |
| async_tree_memoization    | 563 ms                                                                 | 571 ms: 1.01x slower                                                        |
| async_tree_cpu_io_mixed   | 713 ms                                                                 | 724 ms: 1.02x slower                                                        |
| tornado_http              | 94.7 ms                                                                | 96.4 ms: 1.02x slower                                                       |
| pickle_dict               | 34.1 us                                                                | 34.7 us: 1.02x slower                                                       |
| pickle                    | 11.1 us                                                                | 11.3 us: 1.02x slower                                                       |
| xml_etree_generate        | 85.8 ms                                                                | 87.7 ms: 1.02x slower                                                       |
| xml_etree_process         | 58.7 ms                                                                | 60.0 ms: 1.02x slower                                                       |
| docutils                  | 2.59 sec                                                               | 2.65 sec: 1.02x slower                                                      |
| scimark_sor               | 122 ms                                                                 | 124 ms: 1.02x slower                                                        |
| sympy_expand              | 450 ms                                                                 | 460 ms: 1.02x slower                                                        |
| deepcopy_reduce           | 3.05 us                                                                | 3.13 us: 1.02x slower                                                       |
| sqlglot_normalize         | 105 ms                                                                 | 107 ms: 1.02x slower                                                        |
| dulwich_log               | 65.1 ms                                                                | 66.7 ms: 1.02x slower                                                       |
| deepcopy                  | 347 us                                                                 | 355 us: 1.02x slower                                                        |
| bench_thread_pool         | 826 us                                                                 | 850 us: 1.03x slower                                                        |
| logging_simple            | 5.75 us                                                                | 5.92 us: 1.03x slower                                                       |
| mypy2                     | 339 ms                                                                 | 348 ms: 1.03x slower                                                        |
| sqlglot_parse             | 1.25 ms                                                                | 1.29 ms: 1.03x slower                                                       |
| sympy_str                 | 265 ms                                                                 | 274 ms: 1.03x slower                                                        |
| logging_format            | 6.32 us                                                                | 6.53 us: 1.03x slower                                                       |
| sqlglot_transpile         | 1.57 ms                                                                | 1.62 ms: 1.03x slower                                                       |
| typing_runtime_protocols  | 118 us                                                                 | 122 us: 1.03x slower                                                        |
| xml_etree_iterparse       | 104 ms                                                                 | 108 ms: 1.04x slower                                                        |
| raytrace                  | 274 ms                                                                 | 284 ms: 1.04x slower                                                        |
| sympy_sum                 | 147 ms                                                                 | 152 ms: 1.04x slower                                                        |
| logging_silent            | 103 ns                                                                 | 107 ns: 1.04x slower                                                        |
| meteor_contest            | 110 ms                                                                 | 114 ms: 1.04x slower                                                        |
| chameleon                 | 7.01 ms                                                                | 7.32 ms: 1.04x slower                                                       |
| 2to3                      | 261 ms                                                                 | 274 ms: 1.05x slower                                                        |
| async_generators          | 444 ms                                                                 | 465 ms: 1.05x slower                                                        |
| pycparser                 | 1.15 sec                                                               | 1.21 sec: 1.05x slower                                                      |
| unpickle_list             | 5.40 us                                                                | 5.69 us: 1.05x slower                                                       |
| regex_v8                  | 24.4 ms                                                                | 25.7 ms: 1.05x slower                                                       |
| deepcopy_memo             | 38.4 us                                                                | 40.7 us: 1.06x slower                                                       |
| pprint_safe_repr          | 732 ms                                                                 | 778 ms: 1.06x slower                                                        |
| pprint_pformat            | 1.49 sec                                                               | 1.59 sec: 1.06x slower                                                      |
| regex_compile             | 134 ms                                                                 | 142 ms: 1.06x slower                                                        |
| unpickle_pure_python      | 219 us                                                                 | 233 us: 1.06x slower                                                        |
| scimark_fft               | 364 ms                                                                 | 388 ms: 1.07x slower                                                        |
| spectral_norm             | 106 ms                                                                 | 114 ms: 1.07x slower                                                        |
| sympy_integrate           | 19.2 ms                                                                | 20.6 ms: 1.07x slower                                                       |
| scimark_monte_carlo       | 68.4 ms                                                                | 73.5 ms: 1.08x slower                                                       |
| go                        | 140 ms                                                                 | 151 ms: 1.08x slower                                                        |
| tomli_loads               | 2.11 sec                                                               | 2.28 sec: 1.08x slower                                                      |
| gc_traversal              | 3.77 ms                                                                | 4.08 ms: 1.08x slower                                                       |
| float                     | 81.1 ms                                                                | 88.0 ms: 1.08x slower                                                       |
| chaos                     | 60.4 ms                                                                | 65.6 ms: 1.09x slower                                                       |
| pyflate                   | 483 ms                                                                 | 526 ms: 1.09x slower                                                        |
| mako                      | 11.3 ms                                                                | 12.4 ms: 1.10x slower                                                       |
| crypto_pyaes              | 71.0 ms                                                                | 78.4 ms: 1.10x slower                                                       |
| scimark_sparse_mat_mult   | 5.01 ms                                                                | 5.53 ms: 1.10x slower                                                       |
| fannkuch                  | 403 ms                                                                 | 453 ms: 1.12x slower                                                        |
| nbody                     | 89.3 ms                                                                | 103 ms: 1.15x slower                                                        |
| nqueens                   | 80.6 ms                                                                | 96.6 ms: 1.20x slower                                                       |
| deltablue                 | 3.30 ms                                                                | 4.13 ms: 1.25x slower                                                       |
| comprehensions            | 16.2 us                                                                | 20.6 us: 1.27x slower                                                       |
| hexiom                    | 6.01 ms                                                                | 7.84 ms: 1.30x slower                                                       |
| Geometric mean            | (ref)                                                                  | 1.04x slower                                                                |

Benchmark hidden because not significant (9): generators, bench_mp_pool, asyncio_websockets, create_gc_cycles, sqlite_synth, json, xml_etree_parse, async_tree_cpu_io_mixed_tg, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
