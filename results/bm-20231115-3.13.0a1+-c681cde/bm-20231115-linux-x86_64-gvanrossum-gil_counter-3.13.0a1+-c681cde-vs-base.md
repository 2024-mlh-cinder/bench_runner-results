
# Results vs. base

- fork: gvanrossum
- ref: gil_counter
- machine: linux-x86_64
- commit hash: c681cde
- commit date: 2023-11-15
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231115-linux-x86_64-python-4bbb367ba65e1df7307f-3.13.0a1+-4bbb367 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 263 ms                                                                 | 285 ms: 1.09x slower                                              |
| chameleon      | 7.02 ms                                                                | 7.77 ms: 1.11x slower                                             |
| docutils       | 2.60 sec                                                               | 2.70 sec: 1.04x slower                                            |
| tornado_http   | 95.2 ms                                                                | 98.0 ms: 1.03x slower                                             |
| Geometric mean | (ref)                                                                  | 1.06x slower                                                      |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231115-linux-x86_64-python-4bbb367ba65e1df7307f-3.13.0a1+-4bbb367 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| async_tree_io              | 1.19 sec                                                               | 1.20 sec: 1.00x slower                                            |
| async_tree_none_tg         | 456 ms                                                                 | 460 ms: 1.01x slower                                              |
| async_tree_memoization     | 563 ms                                                                 | 570 ms: 1.01x slower                                              |
| async_tree_cpu_io_mixed_tg | 738 ms                                                                 | 750 ms: 1.02x slower                                              |
| async_tree_cpu_io_mixed    | 708 ms                                                                 | 719 ms: 1.02x slower                                              |
| Geometric mean             | (ref)                                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (3): async_tree_io_tg, async_tree_memoization_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231115-linux-x86_64-python-4bbb367ba65e1df7307f-3.13.0a1+-4bbb367 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 188 ms: 1.03x faster                                              |
| float          | 80.9 ms                                                                | 83.4 ms: 1.03x slower                                             |
| nbody          | 88.5 ms                                                                | 102 ms: 1.15x slower                                              |
| Geometric mean | (ref)                                                                  | 1.05x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231115-linux-x86_64-python-4bbb367ba65e1df7307f-3.13.0a1+-4bbb367 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_v8       | 26.6 ms                                                                | 26.3 ms: 1.01x faster                                             |
| regex_dna      | 218 ms                                                                 | 216 ms: 1.01x faster                                              |
| regex_compile  | 135 ms                                                                 | 151 ms: 1.12x slower                                              |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                      |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231115-linux-x86_64-python-4bbb367ba65e1df7307f-3.13.0a1+-4bbb367 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| unpickle_list        | 5.23 us                                                                | 4.93 us: 1.06x faster                                             |
| json_loads           | 28.0 us                                                                | 28.3 us: 1.01x slower                                             |
| xml_etree_iterparse  | 105 ms                                                                 | 107 ms: 1.01x slower                                              |
| pickle_dict          | 33.6 us                                                                | 34.3 us: 1.02x slower                                             |
| json_dumps           | 10.3 ms                                                                | 10.5 ms: 1.02x slower                                             |
| pickle_list          | 5.02 us                                                                | 5.17 us: 1.03x slower                                             |
| xml_etree_generate   | 86.0 ms                                                                | 89.1 ms: 1.04x slower                                             |
| pickle               | 11.1 us                                                                | 11.6 us: 1.04x slower                                             |
| xml_etree_process    | 59.1 ms                                                                | 61.7 ms: 1.04x slower                                             |
| unpickle_pure_python | 220 us                                                                 | 246 us: 1.12x slower                                              |
| pickle_pure_python   | 302 us                                                                 | 344 us: 1.14x slower                                              |
| tomli_loads          | 2.13 sec                                                               | 2.46 sec: 1.15x slower                                            |
| Geometric mean       | (ref)                                                                  | 1.04x slower                                                      |

Benchmark hidden because not significant (2): xml_etree_parse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231115-linux-x86_64-python-4bbb367ba65e1df7307f-3.13.0a1+-4bbb367 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 8.97 ms                                                                | 9.04 ms: 1.01x slower                                             |
| python_startup         | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                             |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231115-linux-x86_64-python-4bbb367ba65e1df7307f-3.13.0a1+-4bbb367 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|-----------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 11.4 ms                                                                | 12.0 ms: 1.06x slower                                             |

All benchmarks:
===============

| Benchmark                  | bm-20231115-linux-x86_64-python-4bbb367ba65e1df7307f-3.13.0a1+-4bbb367 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| unpickle_list              | 5.23 us                                                                | 4.93 us: 1.06x faster                                             |
| pidigits                   | 195 ms                                                                 | 188 ms: 1.03x faster                                              |
| typing_runtime_protocols   | 119 us                                                                 | 117 us: 1.02x faster                                              |
| gc_traversal               | 3.69 ms                                                                | 3.64 ms: 1.01x faster                                             |
| regex_v8                   | 26.6 ms                                                                | 26.3 ms: 1.01x faster                                             |
| create_gc_cycles           | 1.48 ms                                                                | 1.46 ms: 1.01x faster                                             |
| regex_dna                  | 218 ms                                                                 | 216 ms: 1.01x faster                                              |
| asyncio_tcp                | 496 ms                                                                 | 494 ms: 1.00x faster                                              |
| asyncio_tcp_ssl            | 1.80 sec                                                               | 1.80 sec: 1.00x slower                                            |
| async_tree_io              | 1.19 sec                                                               | 1.20 sec: 1.00x slower                                            |
| python_startup_no_site     | 8.97 ms                                                                | 9.04 ms: 1.01x slower                                             |
| pathlib                    | 18.5 ms                                                                | 18.7 ms: 1.01x slower                                             |
| python_startup             | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                             |
| async_tree_none_tg         | 456 ms                                                                 | 460 ms: 1.01x slower                                              |
| json_loads                 | 28.0 us                                                                | 28.3 us: 1.01x slower                                             |
| logging_format             | 6.26 us                                                                | 6.34 us: 1.01x slower                                             |
| async_tree_memoization     | 563 ms                                                                 | 570 ms: 1.01x slower                                              |
| json                       | 5.10 ms                                                                | 5.17 ms: 1.01x slower                                             |
| xml_etree_iterparse        | 105 ms                                                                 | 107 ms: 1.01x slower                                              |
| async_tree_cpu_io_mixed_tg | 738 ms                                                                 | 750 ms: 1.02x slower                                              |
| async_tree_cpu_io_mixed    | 708 ms                                                                 | 719 ms: 1.02x slower                                              |
| async_generators           | 444 ms                                                                 | 452 ms: 1.02x slower                                              |
| mdp                        | 2.53 sec                                                               | 2.58 sec: 1.02x slower                                            |
| pickle_dict                | 33.6 us                                                                | 34.3 us: 1.02x slower                                             |
| json_dumps                 | 10.3 ms                                                                | 10.5 ms: 1.02x slower                                             |
| tornado_http               | 95.2 ms                                                                | 98.0 ms: 1.03x slower                                             |
| sympy_expand               | 453 ms                                                                 | 467 ms: 1.03x slower                                              |
| float                      | 80.9 ms                                                                | 83.4 ms: 1.03x slower                                             |
| pickle_list                | 5.02 us                                                                | 5.17 us: 1.03x slower                                             |
| sympy_sum                  | 148 ms                                                                 | 153 ms: 1.03x slower                                              |
| bench_thread_pool          | 833 us                                                                 | 862 us: 1.04x slower                                              |
| xml_etree_generate         | 86.0 ms                                                                | 89.1 ms: 1.04x slower                                             |
| docutils                   | 2.60 sec                                                               | 2.70 sec: 1.04x slower                                            |
| dulwich_log                | 65.6 ms                                                                | 68.3 ms: 1.04x slower                                             |
| deepcopy_reduce            | 3.15 us                                                                | 3.28 us: 1.04x slower                                             |
| pickle                     | 11.1 us                                                                | 11.6 us: 1.04x slower                                             |
| scimark_sparse_mat_mult    | 4.96 ms                                                                | 5.17 ms: 1.04x slower                                             |
| xml_etree_process          | 59.1 ms                                                                | 61.7 ms: 1.04x slower                                             |
| meteor_contest             | 107 ms                                                                 | 112 ms: 1.05x slower                                              |
| scimark_fft                | 369 ms                                                                 | 387 ms: 1.05x slower                                              |
| mypy2                      | 341 ms                                                                 | 357 ms: 1.05x slower                                              |
| sympy_str                  | 267 ms                                                                 | 281 ms: 1.05x slower                                              |
| sympy_integrate            | 19.5 ms                                                                | 20.6 ms: 1.05x slower                                             |
| logging_silent             | 109 ns                                                                 | 115 ns: 1.05x slower                                              |
| mako                       | 11.4 ms                                                                | 12.0 ms: 1.06x slower                                             |
| sqlglot_normalize          | 105 ms                                                                 | 111 ms: 1.06x slower                                              |
| sqlglot_optimize           | 53.4 ms                                                                | 56.9 ms: 1.06x slower                                             |
| nqueens                    | 79.5 ms                                                                | 84.6 ms: 1.06x slower                                             |
| pprint_safe_repr           | 759 ms                                                                 | 810 ms: 1.07x slower                                              |
| deepcopy_memo              | 39.4 us                                                                | 42.3 us: 1.07x slower                                             |
| scimark_lu                 | 114 ms                                                                 | 122 ms: 1.07x slower                                              |
| scimark_monte_carlo        | 68.4 ms                                                                | 73.4 ms: 1.07x slower                                             |
| pprint_pformat             | 1.54 sec                                                               | 1.65 sec: 1.08x slower                                            |
| pyflate                    | 465 ms                                                                 | 502 ms: 1.08x slower                                              |
| coroutines                 | 21.7 ms                                                                | 23.6 ms: 1.08x slower                                             |
| 2to3                       | 263 ms                                                                 | 285 ms: 1.09x slower                                              |
| spectral_norm              | 112 ms                                                                 | 123 ms: 1.09x slower                                              |
| chaos                      | 61.0 ms                                                                | 66.6 ms: 1.09x slower                                             |
| pycparser                  | 1.20 sec                                                               | 1.31 sec: 1.09x slower                                            |
| fannkuch                   | 397 ms                                                                 | 435 ms: 1.09x slower                                              |
| scimark_sor                | 123 ms                                                                 | 135 ms: 1.10x slower                                              |
| generators                 | 29.3 ms                                                                | 32.1 ms: 1.10x slower                                             |
| deepcopy                   | 351 us                                                                 | 385 us: 1.10x slower                                              |
| chameleon                  | 7.02 ms                                                                | 7.77 ms: 1.11x slower                                             |
| crypto_pyaes               | 72.5 ms                                                                | 80.3 ms: 1.11x slower                                             |
| raytrace                   | 277 ms                                                                 | 306 ms: 1.11x slower                                              |
| comprehensions             | 16.4 us                                                                | 18.2 us: 1.11x slower                                             |
| regex_compile              | 135 ms                                                                 | 151 ms: 1.12x slower                                              |
| unpickle_pure_python       | 220 us                                                                 | 246 us: 1.12x slower                                              |
| sqlglot_transpile          | 1.58 ms                                                                | 1.79 ms: 1.13x slower                                             |
| deltablue                  | 3.34 ms                                                                | 3.78 ms: 1.13x slower                                             |
| pickle_pure_python         | 302 us                                                                 | 344 us: 1.14x slower                                              |
| sqlglot_parse              | 1.27 ms                                                                | 1.46 ms: 1.15x slower                                             |
| nbody                      | 88.5 ms                                                                | 102 ms: 1.15x slower                                              |
| tomli_loads                | 2.13 sec                                                               | 2.46 sec: 1.15x slower                                            |
| go                         | 140 ms                                                                 | 163 ms: 1.17x slower                                              |
| hexiom                     | 6.12 ms                                                                | 7.27 ms: 1.19x slower                                             |
| richards                   | 47.9 ms                                                                | 57.3 ms: 1.20x slower                                             |
| richards_super             | 54.2 ms                                                                | 65.2 ms: 1.20x slower                                             |
| unpack_sequence            | 40.1 ns                                                                | 48.3 ns: 1.20x slower                                             |
| Geometric mean             | (ref)                                                                  | 1.05x slower                                                      |

Benchmark hidden because not significant (12): xml_etree_parse, unpickle, asyncio_websockets, sqlite_synth, coverage, bench_mp_pool, regex_effbot, async_tree_io_tg, logging_simple, telco, async_tree_memoization_tg, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
