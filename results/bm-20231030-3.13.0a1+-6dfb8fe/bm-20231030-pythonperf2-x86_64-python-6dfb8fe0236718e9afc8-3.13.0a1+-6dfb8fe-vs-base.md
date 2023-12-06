
# Results vs. base

- fork: python
- ref: 6dfb8fe0236718e9afc8
- machine: linux-x86_64
- commit hash: 6dfb8fe
- commit date: 2023-10-30
- overall geometric mean: 1.00x faster
- HPT reliability: 99.16%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 298 ms                                                                       | 297 ms: 1.00x faster                                                         |
| chameleon      | 7.36 ms                                                                      | 7.54 ms: 1.03x slower                                                        |
| docutils       | 2.88 sec                                                                     | 2.88 sec: 1.00x faster                                                       |
| tornado_http   | 122 ms                                                                       | 120 ms: 1.01x faster                                                         |
| Geometric mean | (ref)                                                                        | 1.00x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|---------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_memoization_tg | 556 ms                                                                       | 574 ms: 1.03x slower                                                         |
| Geometric mean            | (ref)                                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (7): async_tree_memoization, async_tree_cpu_io_mixed, async_tree_io_tg, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_none_tg, async_tree_none

Benchmarks with tag 'math':
===========================

Benchmark hidden because not significant (3): float, pidigits, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_dna      | 241 ms                                                                       | 249 ms: 1.03x slower                                                         |
| Geometric mean | (ref)                                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (3): regex_v8, regex_effbot, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle_pure_python | 229 us                                                                       | 223 us: 1.03x faster                                                         |
| unpickle_list        | 4.59 us                                                                      | 4.51 us: 1.02x faster                                                        |
| pickle_dict          | 32.2 us                                                                      | 31.8 us: 1.01x faster                                                        |
| xml_etree_generate   | 86.1 ms                                                                      | 85.7 ms: 1.00x faster                                                        |
| json_loads           | 24.5 us                                                                      | 24.8 us: 1.01x slower                                                        |
| xml_etree_iterparse  | 106 ms                                                                       | 107 ms: 1.01x slower                                                         |
| pickle               | 10.2 us                                                                      | 10.4 us: 1.01x slower                                                        |
| pickle_list          | 4.34 us                                                                      | 4.41 us: 1.02x slower                                                        |
| json_dumps           | 10.6 ms                                                                      | 10.8 ms: 1.02x slower                                                        |
| unpickle             | 14.1 us                                                                      | 14.5 us: 1.03x slower                                                        |
| xml_etree_parse      | 143 ms                                                                       | 148 ms: 1.03x slower                                                         |
| pickle_pure_python   | 314 us                                                                       | 325 us: 1.04x slower                                                         |
| Geometric mean       | (ref)                                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (2): tomli_loads, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup_no_site | 11.4 ms                                                                      | 11.3 ms: 1.01x faster                                                        |
| python_startup         | 12.9 ms                                                                      | 12.8 ms: 1.00x faster                                                        |
| Geometric mean         | (ref)                                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|---------------------------|:----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| coverage                  | 87.3 ms                                                                      | 82.9 ms: 1.05x faster                                                        |
| unpack_sequence           | 51.7 ns                                                                      | 49.3 ns: 1.05x faster                                                        |
| nqueens                   | 90.7 ms                                                                      | 87.6 ms: 1.03x faster                                                        |
| scimark_lu                | 103 ms                                                                       | 99.8 ms: 1.03x faster                                                        |
| unpickle_pure_python      | 229 us                                                                       | 223 us: 1.03x faster                                                         |
| logging_simple            | 6.88 us                                                                      | 6.73 us: 1.02x faster                                                        |
| unpickle_list             | 4.59 us                                                                      | 4.51 us: 1.02x faster                                                        |
| sqlglot_parse             | 1.43 ms                                                                      | 1.41 ms: 1.02x faster                                                        |
| tornado_http              | 122 ms                                                                       | 120 ms: 1.01x faster                                                         |
| dulwich_log               | 70.1 ms                                                                      | 69.1 ms: 1.01x faster                                                        |
| sqlglot_normalize         | 117 ms                                                                       | 116 ms: 1.01x faster                                                         |
| async_generators          | 400 ms                                                                       | 395 ms: 1.01x faster                                                         |
| sympy_str                 | 294 ms                                                                       | 290 ms: 1.01x faster                                                         |
| pickle_dict               | 32.2 us                                                                      | 31.8 us: 1.01x faster                                                        |
| hexiom                    | 6.53 ms                                                                      | 6.45 ms: 1.01x faster                                                        |
| sympy_expand              | 494 ms                                                                       | 488 ms: 1.01x faster                                                         |
| logging_format            | 7.53 us                                                                      | 7.45 us: 1.01x faster                                                        |
| sqlglot_transpile         | 1.83 ms                                                                      | 1.82 ms: 1.01x faster                                                        |
| go                        | 172 ms                                                                       | 170 ms: 1.01x faster                                                         |
| coroutines                | 22.8 ms                                                                      | 22.6 ms: 1.01x faster                                                        |
| meteor_contest            | 130 ms                                                                       | 129 ms: 1.01x faster                                                         |
| mypy2                     | 369 ms                                                                       | 366 ms: 1.01x faster                                                         |
| sympy_integrate           | 23.6 ms                                                                      | 23.4 ms: 1.01x faster                                                        |
| scimark_fft               | 303 ms                                                                       | 301 ms: 1.01x faster                                                         |
| python_startup_no_site    | 11.4 ms                                                                      | 11.3 ms: 1.01x faster                                                        |
| chaos                     | 62.2 ms                                                                      | 61.9 ms: 1.01x faster                                                        |
| python_startup            | 12.9 ms                                                                      | 12.8 ms: 1.00x faster                                                        |
| sqlglot_optimize          | 59.0 ms                                                                      | 58.8 ms: 1.00x faster                                                        |
| pyflate                   | 512 ms                                                                       | 510 ms: 1.00x faster                                                         |
| xml_etree_generate        | 86.1 ms                                                                      | 85.7 ms: 1.00x faster                                                        |
| 2to3                      | 298 ms                                                                       | 297 ms: 1.00x faster                                                         |
| docutils                  | 2.88 sec                                                                     | 2.88 sec: 1.00x faster                                                       |
| pathlib                   | 19.5 ms                                                                      | 19.7 ms: 1.01x slower                                                        |
| spectral_norm             | 92.3 ms                                                                      | 93.0 ms: 1.01x slower                                                        |
| deltablue                 | 3.68 ms                                                                      | 3.71 ms: 1.01x slower                                                        |
| json_loads                | 24.5 us                                                                      | 24.8 us: 1.01x slower                                                        |
| xml_etree_iterparse       | 106 ms                                                                       | 107 ms: 1.01x slower                                                         |
| pickle                    | 10.2 us                                                                      | 10.4 us: 1.01x slower                                                        |
| json                      | 5.15 ms                                                                      | 5.23 ms: 1.01x slower                                                        |
| pickle_list               | 4.34 us                                                                      | 4.41 us: 1.02x slower                                                        |
| raytrace                  | 275 ms                                                                       | 280 ms: 1.02x slower                                                         |
| deepcopy                  | 369 us                                                                       | 376 us: 1.02x slower                                                         |
| scimark_sparse_mat_mult   | 4.12 ms                                                                      | 4.19 ms: 1.02x slower                                                        |
| json_dumps                | 10.6 ms                                                                      | 10.8 ms: 1.02x slower                                                        |
| deepcopy_reduce           | 3.32 us                                                                      | 3.39 us: 1.02x slower                                                        |
| chameleon                 | 7.36 ms                                                                      | 7.54 ms: 1.03x slower                                                        |
| deepcopy_memo             | 36.7 us                                                                      | 37.8 us: 1.03x slower                                                        |
| unpickle                  | 14.1 us                                                                      | 14.5 us: 1.03x slower                                                        |
| async_tree_memoization_tg | 556 ms                                                                       | 574 ms: 1.03x slower                                                         |
| regex_dna                 | 241 ms                                                                       | 249 ms: 1.03x slower                                                         |
| xml_etree_parse           | 143 ms                                                                       | 148 ms: 1.03x slower                                                         |
| pickle_pure_python        | 314 us                                                                       | 325 us: 1.04x slower                                                         |
| gc_traversal              | 3.52 ms                                                                      | 3.68 ms: 1.05x slower                                                        |
| Geometric mean            | (ref)                                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (39): bench_mp_pool, pycparser, richards, async_tree_memoization, float, tomli_loads, scimark_monte_carlo, sympy_sum, scimark_sor, async_tree_cpu_io_mixed, async_tree_io_tg, pidigits, async_tree_cpu_io_mixed_tg, xml_etree_process, richards_super, regex_v8, pprint_safe_repr, sqlite_synth, async_tree_io, nbody, comprehensions, asyncio_websockets, telco, asyncio_tcp_ssl, async_tree_none_tg, crypto_pyaes, async_tree_none, mdp, regex_effbot, generators, typing_runtime_protocols, pprint_pformat, regex_compile, fannkuch, logging_silent, asyncio_tcp, create_gc_cycles, bench_thread_pool, mako


# HPT report

- Reliability score: 99.16% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
