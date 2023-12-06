
# Results vs. base

- fork: mdboom
- ref: measure_biased_ref_c
- machine: linux-x86_64
- commit hash: bbb758f
- commit date: 2023-10-31
- overall geometric mean: 1.09x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                                 | 285 ms: 1.07x slower                                                   |
| chameleon      | 6.97 ms                                                                | 7.47 ms: 1.07x slower                                                  |
| docutils       | 2.63 sec                                                               | 2.83 sec: 1.07x slower                                                 |
| tornado_http   | 95.9 ms                                                                | 106 ms: 1.11x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.08x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 715 ms                                                                 | 780 ms: 1.09x slower                                                   |
| async_tree_cpu_io_mixed_tg | 745 ms                                                                 | 823 ms: 1.10x slower                                                   |
| async_tree_memoization     | 566 ms                                                                 | 634 ms: 1.12x slower                                                   |
| async_tree_none            | 438 ms                                                                 | 493 ms: 1.12x slower                                                   |
| async_tree_memoization_tg  | 598 ms                                                                 | 678 ms: 1.13x slower                                                   |
| async_tree_io              | 1.18 sec                                                               | 1.36 sec: 1.15x slower                                                 |
| async_tree_none_tg         | 457 ms                                                                 | 527 ms: 1.15x slower                                                   |
| async_tree_io_tg           | 1.22 sec                                                               | 1.42 sec: 1.16x slower                                                 |
| Geometric mean             | (ref)                                                                  | 1.13x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                 | 188 ms: 1.00x slower                                                   |
| float          | 82.3 ms                                                                | 90.6 ms: 1.10x slower                                                  |
| nbody          | 93.6 ms                                                                | 111 ms: 1.18x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.09x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 217 ms                                                                 | 209 ms: 1.04x faster                                                   |
| regex_effbot   | 3.60 ms                                                                | 3.48 ms: 1.03x faster                                                  |
| regex_v8       | 24.6 ms                                                                | 25.2 ms: 1.03x slower                                                  |
| regex_compile  | 138 ms                                                                 | 149 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_dict          | 33.3 us                                                                | 31.6 us: 1.05x faster                                                  |
| unpickle_list        | 5.24 us                                                                | 5.36 us: 1.02x slower                                                  |
| unpickle             | 15.0 us                                                                | 15.5 us: 1.03x slower                                                  |
| pickle               | 11.0 us                                                                | 11.5 us: 1.05x slower                                                  |
| tomli_loads          | 2.19 sec                                                               | 2.31 sec: 1.05x slower                                                 |
| xml_etree_iterparse  | 106 ms                                                                 | 112 ms: 1.06x slower                                                   |
| json_dumps           | 10.6 ms                                                                | 11.2 ms: 1.07x slower                                                  |
| xml_etree_generate   | 86.9 ms                                                                | 93.6 ms: 1.08x slower                                                  |
| xml_etree_parse      | 158 ms                                                                 | 170 ms: 1.08x slower                                                   |
| xml_etree_process    | 59.8 ms                                                                | 64.6 ms: 1.08x slower                                                  |
| pickle_pure_python   | 305 us                                                                 | 333 us: 1.09x slower                                                   |
| unpickle_pure_python | 221 us                                                                 | 243 us: 1.10x slower                                                   |
| json_loads           | 27.9 us                                                                | 30.8 us: 1.11x slower                                                  |
| Geometric mean       | (ref)                                                                  | 1.05x slower                                                           |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 8.99 ms                                                                | 9.31 ms: 1.04x slower                                                  |
| python_startup         | 10.3 ms                                                                | 10.8 ms: 1.05x slower                                                  |
| Geometric mean         | (ref)                                                                  | 1.04x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|-----------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.1 ms                                                                | 12.7 ms: 1.14x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| gc_traversal               | 4.30 ms                                                                | 3.62 ms: 1.19x faster                                                  |
| pickle_dict                | 33.3 us                                                                | 31.6 us: 1.05x faster                                                  |
| regex_dna                  | 217 ms                                                                 | 209 ms: 1.04x faster                                                   |
| regex_effbot               | 3.60 ms                                                                | 3.48 ms: 1.03x faster                                                  |
| create_gc_cycles           | 1.48 ms                                                                | 1.46 ms: 1.02x faster                                                  |
| pidigits                   | 187 ms                                                                 | 188 ms: 1.00x slower                                                   |
| asyncio_tcp_ssl            | 1.78 sec                                                               | 1.78 sec: 1.00x slower                                                 |
| generators                 | 29.9 ms                                                                | 30.2 ms: 1.01x slower                                                  |
| asyncio_tcp                | 479 ms                                                                 | 484 ms: 1.01x slower                                                   |
| unpack_sequence            | 50.1 ns                                                                | 50.7 ns: 1.01x slower                                                  |
| asyncio_websockets         | 551 ms                                                                 | 559 ms: 1.01x slower                                                   |
| typing_runtime_protocols   | 154 us                                                                 | 157 us: 1.02x slower                                                   |
| unpickle_list              | 5.24 us                                                                | 5.36 us: 1.02x slower                                                  |
| regex_v8                   | 24.6 ms                                                                | 25.2 ms: 1.03x slower                                                  |
| richards_super             | 55.3 ms                                                                | 57.0 ms: 1.03x slower                                                  |
| unpickle                   | 15.0 us                                                                | 15.5 us: 1.03x slower                                                  |
| scimark_sor                | 133 ms                                                                 | 137 ms: 1.04x slower                                                   |
| python_startup_no_site     | 8.99 ms                                                                | 9.31 ms: 1.04x slower                                                  |
| mdp                        | 2.62 sec                                                               | 2.72 sec: 1.04x slower                                                 |
| pathlib                    | 19.2 ms                                                                | 20.1 ms: 1.04x slower                                                  |
| pickle                     | 11.0 us                                                                | 11.5 us: 1.05x slower                                                  |
| richards                   | 48.7 ms                                                                | 51.0 ms: 1.05x slower                                                  |
| dulwich_log                | 67.0 ms                                                                | 70.2 ms: 1.05x slower                                                  |
| python_startup             | 10.3 ms                                                                | 10.8 ms: 1.05x slower                                                  |
| meteor_contest             | 108 ms                                                                 | 114 ms: 1.05x slower                                                   |
| tomli_loads                | 2.19 sec                                                               | 2.31 sec: 1.05x slower                                                 |
| deepcopy                   | 357 us                                                                 | 378 us: 1.06x slower                                                   |
| pycparser                  | 1.17 sec                                                               | 1.24 sec: 1.06x slower                                                 |
| comprehensions             | 16.7 us                                                                | 17.6 us: 1.06x slower                                                  |
| xml_etree_iterparse        | 106 ms                                                                 | 112 ms: 1.06x slower                                                   |
| json_dumps                 | 10.6 ms                                                                | 11.2 ms: 1.07x slower                                                  |
| scimark_lu                 | 116 ms                                                                 | 123 ms: 1.07x slower                                                   |
| scimark_sparse_mat_mult    | 5.02 ms                                                                | 5.35 ms: 1.07x slower                                                  |
| coroutines                 | 22.9 ms                                                                | 24.4 ms: 1.07x slower                                                  |
| logging_silent             | 106 ns                                                                 | 113 ns: 1.07x slower                                                   |
| logging_simple             | 5.91 us                                                                | 6.32 us: 1.07x slower                                                  |
| 2to3                       | 266 ms                                                                 | 285 ms: 1.07x slower                                                   |
| chameleon                  | 6.97 ms                                                                | 7.47 ms: 1.07x slower                                                  |
| pyflate                    | 469 ms                                                                 | 503 ms: 1.07x slower                                                   |
| hexiom                     | 6.34 ms                                                                | 6.80 ms: 1.07x slower                                                  |
| docutils                   | 2.63 sec                                                               | 2.83 sec: 1.07x slower                                                 |
| nqueens                    | 81.0 ms                                                                | 87.0 ms: 1.07x slower                                                  |
| regex_compile              | 138 ms                                                                 | 149 ms: 1.08x slower                                                   |
| sympy_expand               | 450 ms                                                                 | 484 ms: 1.08x slower                                                   |
| xml_etree_generate         | 86.9 ms                                                                | 93.6 ms: 1.08x slower                                                  |
| xml_etree_parse            | 158 ms                                                                 | 170 ms: 1.08x slower                                                   |
| sqlglot_transpile          | 1.61 ms                                                                | 1.73 ms: 1.08x slower                                                  |
| sympy_integrate            | 19.7 ms                                                                | 21.3 ms: 1.08x slower                                                  |
| go                         | 143 ms                                                                 | 154 ms: 1.08x slower                                                   |
| sqlglot_parse              | 1.29 ms                                                                | 1.39 ms: 1.08x slower                                                  |
| pprint_safe_repr           | 741 ms                                                                 | 800 ms: 1.08x slower                                                   |
| logging_format             | 6.41 us                                                                | 6.92 us: 1.08x slower                                                  |
| xml_etree_process          | 59.8 ms                                                                | 64.6 ms: 1.08x slower                                                  |
| pprint_pformat             | 1.51 sec                                                               | 1.63 sec: 1.08x slower                                                 |
| deltablue                  | 3.37 ms                                                                | 3.65 ms: 1.09x slower                                                  |
| sympy_str                  | 268 ms                                                                 | 291 ms: 1.09x slower                                                   |
| sympy_sum                  | 148 ms                                                                 | 161 ms: 1.09x slower                                                   |
| deepcopy_reduce            | 3.13 us                                                                | 3.39 us: 1.09x slower                                                  |
| sqlglot_optimize           | 53.4 ms                                                                | 58.0 ms: 1.09x slower                                                  |
| deepcopy_memo              | 38.5 us                                                                | 41.9 us: 1.09x slower                                                  |
| json                       | 5.17 ms                                                                | 5.64 ms: 1.09x slower                                                  |
| async_tree_cpu_io_mixed    | 715 ms                                                                 | 780 ms: 1.09x slower                                                   |
| scimark_fft                | 371 ms                                                                 | 405 ms: 1.09x slower                                                   |
| pickle_pure_python         | 305 us                                                                 | 333 us: 1.09x slower                                                   |
| async_generators           | 450 ms                                                                 | 492 ms: 1.09x slower                                                   |
| sqlglot_normalize          | 106 ms                                                                 | 115 ms: 1.09x slower                                                   |
| chaos                      | 62.5 ms                                                                | 68.3 ms: 1.09x slower                                                  |
| crypto_pyaes               | 72.5 ms                                                                | 79.3 ms: 1.09x slower                                                  |
| float                      | 82.3 ms                                                                | 90.6 ms: 1.10x slower                                                  |
| unpickle_pure_python       | 221 us                                                                 | 243 us: 1.10x slower                                                   |
| telco                      | 8.20 ms                                                                | 9.04 ms: 1.10x slower                                                  |
| async_tree_cpu_io_mixed_tg | 745 ms                                                                 | 823 ms: 1.10x slower                                                   |
| json_loads                 | 27.9 us                                                                | 30.8 us: 1.11x slower                                                  |
| sqlite_synth               | 2.81 us                                                                | 3.11 us: 1.11x slower                                                  |
| raytrace                   | 279 ms                                                                 | 309 ms: 1.11x slower                                                   |
| spectral_norm              | 114 ms                                                                 | 127 ms: 1.11x slower                                                   |
| tornado_http               | 95.9 ms                                                                | 106 ms: 1.11x slower                                                   |
| scimark_monte_carlo        | 69.3 ms                                                                | 77.5 ms: 1.12x slower                                                  |
| async_tree_memoization     | 566 ms                                                                 | 634 ms: 1.12x slower                                                   |
| async_tree_none            | 438 ms                                                                 | 493 ms: 1.12x slower                                                   |
| fannkuch                   | 404 ms                                                                 | 457 ms: 1.13x slower                                                   |
| async_tree_memoization_tg  | 598 ms                                                                 | 678 ms: 1.13x slower                                                   |
| mako                       | 11.1 ms                                                                | 12.7 ms: 1.14x slower                                                  |
| async_tree_io              | 1.18 sec                                                               | 1.36 sec: 1.15x slower                                                 |
| async_tree_none_tg         | 457 ms                                                                 | 527 ms: 1.15x slower                                                   |
| async_tree_io_tg           | 1.22 sec                                                               | 1.42 sec: 1.16x slower                                                 |
| nbody                      | 93.6 ms                                                                | 111 ms: 1.18x slower                                                   |
| bench_thread_pool          | 814 us                                                                 | 1.04 ms: 1.28x slower                                                  |
| mypy2                      | 342 ms                                                                 | 500 ms: 1.46x slower                                                   |
| coverage                   | 95.0 ms                                                                | 723 ms: 7.62x slower                                                   |
| Geometric mean             | (ref)                                                                  | 1.09x slower                                                           |

Benchmark hidden because not significant (2): pickle_list, bench_mp_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.07x
- 95% likely to have a slowdown of 1.07x
- 99% likely to have a slowdown of 1.06x
