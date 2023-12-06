
# Results vs. base

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 01e464a
- commit date: 2023-11-04
- overall geometric mean: 1.09x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 262 ms                                                                 | 292 ms: 1.11x slower                                                             |
| chameleon      | 6.95 ms                                                                | 7.59 ms: 1.09x slower                                                            |
| docutils       | 2.59 sec                                                               | 2.73 sec: 1.05x slower                                                           |
| tornado_http   | 95.8 ms                                                                | 99.7 ms: 1.04x slower                                                            |
| Geometric mean | (ref)                                                                  | 1.07x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_io_tg           | 1.22 sec                                                               | 1.25 sec: 1.02x slower                                                           |
| async_tree_io              | 1.18 sec                                                               | 1.21 sec: 1.02x slower                                                           |
| async_tree_cpu_io_mixed_tg | 739 ms                                                                 | 757 ms: 1.03x slower                                                             |
| async_tree_memoization_tg  | 596 ms                                                                 | 612 ms: 1.03x slower                                                             |
| async_tree_cpu_io_mixed    | 708 ms                                                                 | 732 ms: 1.03x slower                                                             |
| async_tree_none_tg         | 455 ms                                                                 | 472 ms: 1.04x slower                                                             |
| async_tree_memoization     | 564 ms                                                                 | 588 ms: 1.04x slower                                                             |
| async_tree_none            | 439 ms                                                                 | 459 ms: 1.05x slower                                                             |
| Geometric mean             | (ref)                                                                  | 1.03x slower                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                 | 197 ms: 1.05x slower                                                             |
| float          | 80.3 ms                                                                | 104 ms: 1.30x slower                                                             |
| nbody          | 88.9 ms                                                                | 122 ms: 1.37x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.23x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_dna      | 216 ms                                                                 | 218 ms: 1.01x slower                                                             |
| regex_effbot   | 3.55 ms                                                                | 3.72 ms: 1.05x slower                                                            |
| regex_v8       | 24.6 ms                                                                | 25.8 ms: 1.05x slower                                                            |
| regex_compile  | 134 ms                                                                 | 164 ms: 1.22x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.08x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpickle_list        | 5.51 us                                                                | 5.40 us: 1.02x faster                                                            |
| pickle_dict          | 35.5 us                                                                | 35.6 us: 1.00x slower                                                            |
| pickle               | 11.5 us                                                                | 11.6 us: 1.01x slower                                                            |
| pickle_list          | 5.05 us                                                                | 5.11 us: 1.01x slower                                                            |
| xml_etree_generate   | 86.6 ms                                                                | 87.6 ms: 1.01x slower                                                            |
| json_dumps           | 10.5 ms                                                                | 10.7 ms: 1.01x slower                                                            |
| pickle_pure_python   | 298 us                                                                 | 303 us: 1.02x slower                                                             |
| unpickle             | 15.1 us                                                                | 15.5 us: 1.03x slower                                                            |
| xml_etree_iterparse  | 106 ms                                                                 | 112 ms: 1.06x slower                                                             |
| unpickle_pure_python | 220 us                                                                 | 243 us: 1.10x slower                                                             |
| tomli_loads          | 2.13 sec                                                               | 2.99 sec: 1.40x slower                                                           |
| Geometric mean       | (ref)                                                                  | 1.04x slower                                                                     |

Benchmark hidden because not significant (3): json_loads, xml_etree_process, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.3 ms: 1.00x faster                                                            |
| python_startup_no_site | 9.01 ms                                                                | 9.00 ms: 1.00x faster                                                            |
| Geometric mean         | (ref)                                                                  | 1.00x faster                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 11.2 ms                                                                | 15.3 ms: 1.36x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpickle_list              | 5.51 us                                                                | 5.40 us: 1.02x faster                                                            |
| create_gc_cycles           | 1.48 ms                                                                | 1.45 ms: 1.02x faster                                                            |
| logging_silent             | 105 ns                                                                 | 105 ns: 1.00x faster                                                             |
| python_startup             | 10.3 ms                                                                | 10.3 ms: 1.00x faster                                                            |
| spectral_norm              | 109 ms                                                                 | 109 ms: 1.00x faster                                                             |
| python_startup_no_site     | 9.01 ms                                                                | 9.00 ms: 1.00x faster                                                            |
| pickle_dict                | 35.5 us                                                                | 35.6 us: 1.00x slower                                                            |
| coroutines                 | 22.0 ms                                                                | 22.1 ms: 1.01x slower                                                            |
| regex_dna                  | 216 ms                                                                 | 218 ms: 1.01x slower                                                             |
| json                       | 5.10 ms                                                                | 5.14 ms: 1.01x slower                                                            |
| pickle                     | 11.5 us                                                                | 11.6 us: 1.01x slower                                                            |
| pickle_list                | 5.05 us                                                                | 5.11 us: 1.01x slower                                                            |
| xml_etree_generate         | 86.6 ms                                                                | 87.6 ms: 1.01x slower                                                            |
| json_dumps                 | 10.5 ms                                                                | 10.7 ms: 1.01x slower                                                            |
| asyncio_tcp_ssl            | 1.79 sec                                                               | 1.81 sec: 1.01x slower                                                           |
| generators                 | 29.6 ms                                                                | 30.0 ms: 1.02x slower                                                            |
| coverage                   | 94.6 ms                                                                | 96.0 ms: 1.02x slower                                                            |
| pickle_pure_python         | 298 us                                                                 | 303 us: 1.02x slower                                                             |
| sqlite_synth               | 2.81 us                                                                | 2.87 us: 1.02x slower                                                            |
| async_tree_io_tg           | 1.22 sec                                                               | 1.25 sec: 1.02x slower                                                           |
| async_tree_io              | 1.18 sec                                                               | 1.21 sec: 1.02x slower                                                           |
| async_tree_cpu_io_mixed_tg | 739 ms                                                                 | 757 ms: 1.03x slower                                                             |
| sqlglot_normalize          | 105 ms                                                                 | 107 ms: 1.03x slower                                                             |
| async_tree_memoization_tg  | 596 ms                                                                 | 612 ms: 1.03x slower                                                             |
| scimark_sor                | 122 ms                                                                 | 125 ms: 1.03x slower                                                             |
| asyncio_tcp                | 481 ms                                                                 | 495 ms: 1.03x slower                                                             |
| unpickle                   | 15.1 us                                                                | 15.5 us: 1.03x slower                                                            |
| deepcopy_reduce            | 3.06 us                                                                | 3.15 us: 1.03x slower                                                            |
| async_tree_cpu_io_mixed    | 708 ms                                                                 | 732 ms: 1.03x slower                                                             |
| bench_thread_pool          | 830 us                                                                 | 860 us: 1.04x slower                                                             |
| sqlglot_optimize           | 53.1 ms                                                                | 55.1 ms: 1.04x slower                                                            |
| async_tree_none_tg         | 455 ms                                                                 | 472 ms: 1.04x slower                                                             |
| richards                   | 48.7 ms                                                                | 50.7 ms: 1.04x slower                                                            |
| tornado_http               | 95.8 ms                                                                | 99.7 ms: 1.04x slower                                                            |
| deepcopy                   | 343 us                                                                 | 358 us: 1.04x slower                                                             |
| async_tree_memoization     | 564 ms                                                                 | 588 ms: 1.04x slower                                                             |
| pycparser                  | 1.16 sec                                                               | 1.21 sec: 1.05x slower                                                           |
| pathlib                    | 18.9 ms                                                                | 19.7 ms: 1.05x slower                                                            |
| async_tree_none            | 439 ms                                                                 | 459 ms: 1.05x slower                                                             |
| telco                      | 8.32 ms                                                                | 8.71 ms: 1.05x slower                                                            |
| regex_effbot               | 3.55 ms                                                                | 3.72 ms: 1.05x slower                                                            |
| mypy2                      | 341 ms                                                                 | 358 ms: 1.05x slower                                                             |
| regex_v8                   | 24.6 ms                                                                | 25.8 ms: 1.05x slower                                                            |
| pidigits                   | 187 ms                                                                 | 197 ms: 1.05x slower                                                             |
| docutils                   | 2.59 sec                                                               | 2.73 sec: 1.05x slower                                                           |
| dulwich_log                | 65.8 ms                                                                | 69.4 ms: 1.05x slower                                                            |
| async_generators           | 442 ms                                                                 | 467 ms: 1.05x slower                                                             |
| richards_super             | 54.8 ms                                                                | 57.8 ms: 1.05x slower                                                            |
| gc_traversal               | 3.58 ms                                                                | 3.80 ms: 1.06x slower                                                            |
| xml_etree_iterparse        | 106 ms                                                                 | 112 ms: 1.06x slower                                                             |
| sqlglot_transpile          | 1.59 ms                                                                | 1.69 ms: 1.07x slower                                                            |
| sqlglot_parse              | 1.27 ms                                                                | 1.36 ms: 1.07x slower                                                            |
| sympy_sum                  | 147 ms                                                                 | 157 ms: 1.07x slower                                                             |
| scimark_lu                 | 114 ms                                                                 | 122 ms: 1.07x slower                                                             |
| logging_simple             | 5.85 us                                                                | 6.32 us: 1.08x slower                                                            |
| typing_runtime_protocols   | 115 us                                                                 | 124 us: 1.08x slower                                                             |
| sympy_str                  | 266 ms                                                                 | 288 ms: 1.08x slower                                                             |
| sympy_expand               | 449 ms                                                                 | 488 ms: 1.09x slower                                                             |
| chameleon                  | 6.95 ms                                                                | 7.59 ms: 1.09x slower                                                            |
| meteor_contest             | 110 ms                                                                 | 121 ms: 1.09x slower                                                             |
| pprint_safe_repr           | 733 ms                                                                 | 807 ms: 1.10x slower                                                             |
| unpickle_pure_python       | 220 us                                                                 | 243 us: 1.10x slower                                                             |
| logging_format             | 6.41 us                                                                | 7.12 us: 1.11x slower                                                            |
| sympy_integrate            | 19.4 ms                                                                | 21.6 ms: 1.11x slower                                                            |
| pprint_pformat             | 1.50 sec                                                               | 1.67 sec: 1.11x slower                                                           |
| 2to3                       | 262 ms                                                                 | 292 ms: 1.11x slower                                                             |
| raytrace                   | 272 ms                                                                 | 309 ms: 1.13x slower                                                             |
| deepcopy_memo              | 37.4 us                                                                | 42.6 us: 1.14x slower                                                            |
| mdp                        | 2.51 sec                                                               | 2.94 sec: 1.17x slower                                                           |
| unpack_sequence            | 50.8 ns                                                                | 59.4 ns: 1.17x slower                                                            |
| scimark_monte_carlo        | 67.0 ms                                                                | 79.9 ms: 1.19x slower                                                            |
| go                         | 142 ms                                                                 | 170 ms: 1.20x slower                                                             |
| scimark_fft                | 358 ms                                                                 | 437 ms: 1.22x slower                                                             |
| regex_compile              | 134 ms                                                                 | 164 ms: 1.22x slower                                                             |
| pyflate                    | 473 ms                                                                 | 579 ms: 1.22x slower                                                             |
| chaos                      | 60.4 ms                                                                | 75.4 ms: 1.25x slower                                                            |
| crypto_pyaes               | 70.1 ms                                                                | 88.4 ms: 1.26x slower                                                            |
| fannkuch                   | 399 ms                                                                 | 510 ms: 1.28x slower                                                             |
| float                      | 80.3 ms                                                                | 104 ms: 1.30x slower                                                             |
| mako                       | 11.2 ms                                                                | 15.3 ms: 1.36x slower                                                            |
| nbody                      | 88.9 ms                                                                | 122 ms: 1.37x slower                                                             |
| nqueens                    | 78.6 ms                                                                | 108 ms: 1.38x slower                                                             |
| tomli_loads                | 2.13 sec                                                               | 2.99 sec: 1.40x slower                                                           |
| scimark_sparse_mat_mult    | 4.81 ms                                                                | 6.87 ms: 1.43x slower                                                            |
| comprehensions             | 16.6 us                                                                | 26.2 us: 1.58x slower                                                            |
| deltablue                  | 3.28 ms                                                                | 5.25 ms: 1.60x slower                                                            |
| hexiom                     | 6.14 ms                                                                | 10.3 ms: 1.67x slower                                                            |
| Geometric mean             | (ref)                                                                  | 1.09x slower                                                                     |

Benchmark hidden because not significant (5): json_loads, xml_etree_process, bench_mp_pool, asyncio_websockets, xml_etree_parse


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.04x
