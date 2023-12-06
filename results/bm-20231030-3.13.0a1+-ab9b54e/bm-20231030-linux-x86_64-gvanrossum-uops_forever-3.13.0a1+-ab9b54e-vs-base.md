
# Results vs. base

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: ab9b54e
- commit date: 2023-10-30
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231030-linux-x86_64-python-c19561b9ca2c8f5ed554-3.13.0a1+-c19561b | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 265 ms                                                                 | 290 ms: 1.10x slower                                               |
| chameleon      | 6.88 ms                                                                | 7.46 ms: 1.08x slower                                              |
| docutils       | 2.65 sec                                                               | 2.76 sec: 1.04x slower                                             |
| tornado_http   | 95.8 ms                                                                | 102 ms: 1.07x slower                                               |
| Geometric mean | (ref)                                                                  | 1.07x slower                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231030-linux-x86_64-python-c19561b9ca2c8f5ed554-3.13.0a1+-c19561b | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|---------------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_cpu_io_mixed   | 716 ms                                                                 | 725 ms: 1.01x slower                                               |
| async_tree_io             | 1.19 sec                                                               | 1.21 sec: 1.02x slower                                             |
| async_tree_io_tg          | 1.22 sec                                                               | 1.25 sec: 1.02x slower                                             |
| async_tree_none_tg        | 457 ms                                                                 | 471 ms: 1.03x slower                                               |
| async_tree_memoization    | 564 ms                                                                 | 585 ms: 1.04x slower                                               |
| async_tree_memoization_tg | 595 ms                                                                 | 621 ms: 1.04x slower                                               |
| async_tree_none           | 438 ms                                                                 | 457 ms: 1.04x slower                                               |
| Geometric mean            | (ref)                                                                  | 1.03x slower                                                       |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231030-linux-x86_64-python-c19561b9ca2c8f5ed554-3.13.0a1+-c19561b | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                 | 196 ms: 1.05x slower                                               |
| float          | 81.6 ms                                                                | 95.9 ms: 1.18x slower                                              |
| nbody          | 91.7 ms                                                                | 110 ms: 1.20x slower                                               |
| Geometric mean | (ref)                                                                  | 1.14x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231030-linux-x86_64-python-c19561b9ca2c8f5ed554-3.13.0a1+-c19561b | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_effbot   | 3.77 ms                                                                | 3.58 ms: 1.05x faster                                              |
| regex_dna      | 219 ms                                                                 | 215 ms: 1.02x faster                                               |
| regex_v8       | 25.5 ms                                                                | 25.9 ms: 1.02x slower                                              |
| regex_compile  | 138 ms                                                                 | 162 ms: 1.17x slower                                               |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231030-linux-x86_64-python-c19561b9ca2c8f5ed554-3.13.0a1+-c19561b | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| unpickle_list        | 5.21 us                                                                | 5.14 us: 1.01x faster                                              |
| unpickle             | 15.0 us                                                                | 14.8 us: 1.01x faster                                              |
| json_loads           | 27.8 us                                                                | 27.6 us: 1.01x faster                                              |
| pickle               | 11.2 us                                                                | 11.2 us: 1.00x faster                                              |
| xml_etree_parse      | 158 ms                                                                 | 159 ms: 1.01x slower                                               |
| xml_etree_generate   | 86.8 ms                                                                | 87.7 ms: 1.01x slower                                              |
| xml_etree_process    | 59.3 ms                                                                | 60.0 ms: 1.01x slower                                              |
| json_dumps           | 10.4 ms                                                                | 10.6 ms: 1.02x slower                                              |
| pickle_list          | 4.87 us                                                                | 5.02 us: 1.03x slower                                              |
| pickle_pure_python   | 302 us                                                                 | 312 us: 1.03x slower                                               |
| pickle_dict          | 33.8 us                                                                | 35.1 us: 1.04x slower                                              |
| xml_etree_iterparse  | 106 ms                                                                 | 111 ms: 1.05x slower                                               |
| unpickle_pure_python | 219 us                                                                 | 240 us: 1.10x slower                                               |
| tomli_loads          | 2.15 sec                                                               | 2.46 sec: 1.15x slower                                             |
| Geometric mean       | (ref)                                                                  | 1.03x slower                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231030-linux-x86_64-python-c19561b9ca2c8f5ed554-3.13.0a1+-c19561b | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|------------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                              |
| python_startup_no_site | 8.98 ms                                                                | 9.00 ms: 1.00x slower                                              |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231030-linux-x86_64-python-c19561b9ca2c8f5ed554-3.13.0a1+-c19561b | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|-----------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 11.3 ms                                                                | 13.2 ms: 1.17x slower                                              |

All benchmarks:
===============

| Benchmark                 | bm-20231030-linux-x86_64-python-c19561b9ca2c8f5ed554-3.13.0a1+-c19561b | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|---------------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| gc_traversal              | 3.80 ms                                                                | 3.50 ms: 1.09x faster                                              |
| regex_effbot              | 3.77 ms                                                                | 3.58 ms: 1.05x faster                                              |
| create_gc_cycles          | 1.48 ms                                                                | 1.45 ms: 1.02x faster                                              |
| coverage                  | 95.7 ms                                                                | 94.2 ms: 1.02x faster                                              |
| regex_dna                 | 219 ms                                                                 | 215 ms: 1.02x faster                                               |
| unpickle_list             | 5.21 us                                                                | 5.14 us: 1.01x faster                                              |
| unpickle                  | 15.0 us                                                                | 14.8 us: 1.01x faster                                              |
| json_loads                | 27.8 us                                                                | 27.6 us: 1.01x faster                                              |
| deepcopy_reduce           | 3.17 us                                                                | 3.15 us: 1.01x faster                                              |
| pickle                    | 11.2 us                                                                | 11.2 us: 1.00x faster                                              |
| python_startup            | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                              |
| unpack_sequence           | 45.0 ns                                                                | 45.0 ns: 1.00x slower                                              |
| python_startup_no_site    | 8.98 ms                                                                | 9.00 ms: 1.00x slower                                              |
| asyncio_tcp               | 475 ms                                                                 | 477 ms: 1.01x slower                                               |
| xml_etree_parse           | 158 ms                                                                 | 159 ms: 1.01x slower                                               |
| xml_etree_generate        | 86.8 ms                                                                | 87.7 ms: 1.01x slower                                              |
| asyncio_tcp_ssl           | 1.78 sec                                                               | 1.80 sec: 1.01x slower                                             |
| sqlglot_normalize         | 106 ms                                                                 | 108 ms: 1.01x slower                                               |
| async_tree_cpu_io_mixed   | 716 ms                                                                 | 725 ms: 1.01x slower                                               |
| xml_etree_process         | 59.3 ms                                                                | 60.0 ms: 1.01x slower                                              |
| json                      | 5.06 ms                                                                | 5.14 ms: 1.02x slower                                              |
| async_tree_io             | 1.19 sec                                                               | 1.21 sec: 1.02x slower                                             |
| json_dumps                | 10.4 ms                                                                | 10.6 ms: 1.02x slower                                              |
| scimark_sor               | 126 ms                                                                 | 128 ms: 1.02x slower                                               |
| regex_v8                  | 25.5 ms                                                                | 25.9 ms: 1.02x slower                                              |
| deepcopy                  | 353 us                                                                 | 360 us: 1.02x slower                                               |
| async_tree_io_tg          | 1.22 sec                                                               | 1.25 sec: 1.02x slower                                             |
| sqlite_synth              | 2.78 us                                                                | 2.86 us: 1.03x slower                                              |
| logging_silent            | 103 ns                                                                 | 106 ns: 1.03x slower                                               |
| pickle_list               | 4.87 us                                                                | 5.02 us: 1.03x slower                                              |
| async_tree_none_tg        | 457 ms                                                                 | 471 ms: 1.03x slower                                               |
| pickle_pure_python        | 302 us                                                                 | 312 us: 1.03x slower                                               |
| sqlglot_optimize          | 53.5 ms                                                                | 55.2 ms: 1.03x slower                                              |
| generators                | 29.4 ms                                                                | 30.4 ms: 1.03x slower                                              |
| telco                     | 8.24 ms                                                                | 8.53 ms: 1.04x slower                                              |
| bench_thread_pool         | 819 us                                                                 | 849 us: 1.04x slower                                               |
| async_tree_memoization    | 564 ms                                                                 | 585 ms: 1.04x slower                                               |
| sqlglot_parse             | 1.29 ms                                                                | 1.34 ms: 1.04x slower                                              |
| pickle_dict               | 33.8 us                                                                | 35.1 us: 1.04x slower                                              |
| mdp                       | 2.77 sec                                                               | 2.88 sec: 1.04x slower                                             |
| pathlib                   | 19.0 ms                                                                | 19.8 ms: 1.04x slower                                              |
| typing_runtime_protocols  | 152 us                                                                 | 159 us: 1.04x slower                                               |
| docutils                  | 2.65 sec                                                               | 2.76 sec: 1.04x slower                                             |
| async_tree_memoization_tg | 595 ms                                                                 | 621 ms: 1.04x slower                                               |
| async_tree_none           | 438 ms                                                                 | 457 ms: 1.04x slower                                               |
| mypy2                     | 342 ms                                                                 | 357 ms: 1.04x slower                                               |
| sqlglot_transpile         | 1.60 ms                                                                | 1.67 ms: 1.05x slower                                              |
| pidigits                  | 187 ms                                                                 | 196 ms: 1.05x slower                                               |
| richards_super            | 54.3 ms                                                                | 57.0 ms: 1.05x slower                                              |
| spectral_norm             | 111 ms                                                                 | 116 ms: 1.05x slower                                               |
| xml_etree_iterparse       | 106 ms                                                                 | 111 ms: 1.05x slower                                               |
| dulwich_log               | 66.0 ms                                                                | 69.7 ms: 1.06x slower                                              |
| sympy_sum                 | 149 ms                                                                 | 157 ms: 1.06x slower                                               |
| richards                  | 47.7 ms                                                                | 50.5 ms: 1.06x slower                                              |
| scimark_lu                | 114 ms                                                                 | 121 ms: 1.06x slower                                               |
| meteor_contest            | 108 ms                                                                 | 115 ms: 1.07x slower                                               |
| sympy_expand              | 454 ms                                                                 | 484 ms: 1.07x slower                                               |
| tornado_http              | 95.8 ms                                                                | 102 ms: 1.07x slower                                               |
| async_generators          | 447 ms                                                                 | 479 ms: 1.07x slower                                               |
| sympy_str                 | 268 ms                                                                 | 287 ms: 1.07x slower                                               |
| pycparser                 | 1.16 sec                                                               | 1.26 sec: 1.08x slower                                             |
| logging_simple            | 5.87 us                                                                | 6.35 us: 1.08x slower                                              |
| chameleon                 | 6.88 ms                                                                | 7.46 ms: 1.08x slower                                              |
| sympy_integrate           | 19.8 ms                                                                | 21.5 ms: 1.09x slower                                              |
| deepcopy_memo             | 39.3 us                                                                | 42.8 us: 1.09x slower                                              |
| pprint_safe_repr          | 744 ms                                                                 | 810 ms: 1.09x slower                                               |
| 2to3                      | 265 ms                                                                 | 290 ms: 1.10x slower                                               |
| unpickle_pure_python      | 219 us                                                                 | 240 us: 1.10x slower                                               |
| pprint_pformat            | 1.52 sec                                                               | 1.67 sec: 1.10x slower                                             |
| logging_format            | 6.45 us                                                                | 7.29 us: 1.13x slower                                              |
| scimark_monte_carlo       | 68.2 ms                                                                | 77.1 ms: 1.13x slower                                              |
| raytrace                  | 272 ms                                                                 | 309 ms: 1.13x slower                                               |
| tomli_loads               | 2.15 sec                                                               | 2.46 sec: 1.15x slower                                             |
| fannkuch                  | 396 ms                                                                 | 455 ms: 1.15x slower                                               |
| go                        | 145 ms                                                                 | 166 ms: 1.15x slower                                               |
| pyflate                   | 454 ms                                                                 | 528 ms: 1.16x slower                                               |
| mako                      | 11.3 ms                                                                | 13.2 ms: 1.17x slower                                              |
| crypto_pyaes              | 71.7 ms                                                                | 83.9 ms: 1.17x slower                                              |
| scimark_fft               | 375 ms                                                                 | 439 ms: 1.17x slower                                               |
| scimark_sparse_mat_mult   | 5.02 ms                                                                | 5.88 ms: 1.17x slower                                              |
| regex_compile             | 138 ms                                                                 | 162 ms: 1.17x slower                                               |
| float                     | 81.6 ms                                                                | 95.9 ms: 1.18x slower                                              |
| nbody                     | 91.7 ms                                                                | 110 ms: 1.20x slower                                               |
| chaos                     | 61.4 ms                                                                | 75.0 ms: 1.22x slower                                              |
| nqueens                   | 79.7 ms                                                                | 98.3 ms: 1.23x slower                                              |
| comprehensions            | 16.5 us                                                                | 22.2 us: 1.34x slower                                              |
| deltablue                 | 3.27 ms                                                                | 4.61 ms: 1.41x slower                                              |
| hexiom                    | 6.21 ms                                                                | 8.84 ms: 1.42x slower                                              |
| Geometric mean            | (ref)                                                                  | 1.06x slower                                                       |

Benchmark hidden because not significant (4): coroutines, bench_mp_pool, asyncio_websockets, async_tree_cpu_io_mixed_tg


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
