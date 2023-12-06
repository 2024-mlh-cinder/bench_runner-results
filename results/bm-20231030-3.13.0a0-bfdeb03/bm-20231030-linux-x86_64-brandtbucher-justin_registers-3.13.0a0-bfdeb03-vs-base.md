
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: bfdeb03
- commit date: 2023-10-30
- overall geometric mean: 1.09x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.76 sec: 1.05x slower                                                  |
| tornado_http   | 95.5 ms                                                               | 99.7 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.05x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 189 ms: 1.01x slower                                                    |
| float          | 79.3 ms                                                               | 97.8 ms: 1.23x slower                                                   |
| nbody          | 89.7 ms                                                               | 112 ms: 1.25x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.16x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 210 ms                                                                | 208 ms: 1.01x faster                                                    |
| regex_v8       | 24.3 ms                                                               | 25.0 ms: 1.03x slower                                                   |
| regex_compile  | 136 ms                                                                | 156 ms: 1.15x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.04x slower                                                            |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpickle_list        | 4.87 us                                                               | 4.95 us: 1.02x slower                                                   |
| pickle_pure_python   | 298 us                                                                | 307 us: 1.03x slower                                                    |
| xml_etree_process    | 58.1 ms                                                               | 60.6 ms: 1.04x slower                                                   |
| xml_etree_parse      | 153 ms                                                                | 160 ms: 1.04x slower                                                    |
| unpickle             | 14.7 us                                                               | 15.5 us: 1.05x slower                                                   |
| xml_etree_generate   | 84.1 ms                                                               | 88.7 ms: 1.06x slower                                                   |
| json_dumps           | 9.80 ms                                                               | 10.6 ms: 1.08x slower                                                   |
| pickle               | 10.7 us                                                               | 11.6 us: 1.08x slower                                                   |
| pickle_dict          | 32.0 us                                                               | 35.4 us: 1.11x slower                                                   |
| json_loads           | 25.3 us                                                               | 28.2 us: 1.11x slower                                                   |
| xml_etree_iterparse  | 102 ms                                                                | 114 ms: 1.11x slower                                                    |
| tomli_loads          | 2.07 sec                                                              | 2.35 sec: 1.13x slower                                                  |
| pickle_list          | 4.60 us                                                               | 5.22 us: 1.13x slower                                                   |
| unpickle_pure_python | 213 us                                                                | 244 us: 1.14x slower                                                    |
| Geometric mean       | (ref)                                                                 | 1.08x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.4 ms: 1.03x slower                                                   |
| python_startup_no_site | 6.85 ms                                                               | 7.10 ms: 1.04x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.03x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                               | 12.4 ms: 1.16x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| asyncio_tcp              | 502 ms                                                                | 485 ms: 1.04x faster                                                    |
| gc_traversal             | 4.10 ms                                                               | 3.96 ms: 1.04x faster                                                   |
| create_gc_cycles         | 1.53 ms                                                               | 1.50 ms: 1.02x faster                                                   |
| regex_dna                | 210 ms                                                                | 208 ms: 1.01x faster                                                    |
| pycparser                | 1.20 sec                                                              | 1.20 sec: 1.01x faster                                                  |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.80 sec: 1.00x faster                                                  |
| pidigits                 | 187 ms                                                                | 189 ms: 1.01x slower                                                    |
| sqlite_synth             | 2.77 us                                                               | 2.81 us: 1.02x slower                                                   |
| unpickle_list            | 4.87 us                                                               | 4.95 us: 1.02x slower                                                   |
| deepcopy_reduce          | 3.13 us                                                               | 3.20 us: 1.02x slower                                                   |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.02x slower                                                  |
| scimark_sor              | 127 ms                                                                | 130 ms: 1.03x slower                                                    |
| async_tree_cpu_io_mixed  | 705 ms                                                                | 725 ms: 1.03x slower                                                    |
| pickle_pure_python       | 298 us                                                                | 307 us: 1.03x slower                                                    |
| pathlib                  | 18.6 ms                                                               | 19.1 ms: 1.03x slower                                                   |
| regex_v8                 | 24.3 ms                                                               | 25.0 ms: 1.03x slower                                                   |
| python_startup           | 10.0 ms                                                               | 10.4 ms: 1.03x slower                                                   |
| async_tree_memoization   | 564 ms                                                                | 583 ms: 1.03x slower                                                    |
| coroutines               | 22.2 ms                                                               | 23.0 ms: 1.04x slower                                                   |
| python_startup_no_site   | 6.85 ms                                                               | 7.10 ms: 1.04x slower                                                   |
| xml_etree_process        | 58.1 ms                                                               | 60.6 ms: 1.04x slower                                                   |
| generators               | 28.2 ms                                                               | 29.4 ms: 1.04x slower                                                   |
| richards_super           | 53.3 ms                                                               | 55.5 ms: 1.04x slower                                                   |
| xml_etree_parse          | 153 ms                                                                | 160 ms: 1.04x slower                                                    |
| logging_format           | 6.54 us                                                               | 6.82 us: 1.04x slower                                                   |
| tornado_http             | 95.5 ms                                                               | 99.7 ms: 1.04x slower                                                   |
| async_tree_none          | 437 ms                                                                | 457 ms: 1.04x slower                                                    |
| bench_thread_pool        | 814 us                                                                | 850 us: 1.04x slower                                                    |
| logging_simple           | 5.93 us                                                               | 6.21 us: 1.05x slower                                                   |
| deepcopy                 | 349 us                                                                | 365 us: 1.05x slower                                                    |
| dulwich_log              | 66.1 ms                                                               | 69.4 ms: 1.05x slower                                                   |
| sqlglot_optimize         | 52.7 ms                                                               | 55.4 ms: 1.05x slower                                                   |
| docutils                 | 2.62 sec                                                              | 2.76 sec: 1.05x slower                                                  |
| unpickle                 | 14.7 us                                                               | 15.5 us: 1.05x slower                                                   |
| xml_etree_generate       | 84.1 ms                                                               | 88.7 ms: 1.06x slower                                                   |
| sqlglot_normalize        | 104 ms                                                                | 110 ms: 1.06x slower                                                    |
| telco                    | 8.03 ms                                                               | 8.50 ms: 1.06x slower                                                   |
| richards                 | 46.9 ms                                                               | 49.8 ms: 1.06x slower                                                   |
| sqlglot_parse            | 1.26 ms                                                               | 1.34 ms: 1.06x slower                                                   |
| sqlglot_transpile        | 1.57 ms                                                               | 1.68 ms: 1.07x slower                                                   |
| scimark_fft              | 360 ms                                                                | 384 ms: 1.07x slower                                                    |
| meteor_contest           | 107 ms                                                                | 114 ms: 1.07x slower                                                    |
| scimark_lu               | 111 ms                                                                | 119 ms: 1.07x slower                                                    |
| mdp                      | 2.66 sec                                                              | 2.85 sec: 1.07x slower                                                  |
| json_dumps               | 9.80 ms                                                               | 10.6 ms: 1.08x slower                                                   |
| pickle                   | 10.7 us                                                               | 11.6 us: 1.08x slower                                                   |
| mypy2                    | 336 ms                                                                | 364 ms: 1.08x slower                                                    |
| json                     | 4.77 ms                                                               | 5.18 ms: 1.09x slower                                                   |
| async_generators         | 440 ms                                                                | 478 ms: 1.09x slower                                                    |
| coverage                 | 87.1 ms                                                               | 95.9 ms: 1.10x slower                                                   |
| crypto_pyaes             | 69.7 ms                                                               | 76.8 ms: 1.10x slower                                                   |
| pickle_dict              | 32.0 us                                                               | 35.4 us: 1.11x slower                                                   |
| typing_runtime_protocols | 144 us                                                                | 159 us: 1.11x slower                                                    |
| spectral_norm            | 107 ms                                                                | 119 ms: 1.11x slower                                                    |
| json_loads               | 25.3 us                                                               | 28.2 us: 1.11x slower                                                   |
| xml_etree_iterparse      | 102 ms                                                                | 114 ms: 1.11x slower                                                    |
| unpack_sequence          | 44.0 ns                                                               | 49.0 ns: 1.11x slower                                                   |
| go                       | 138 ms                                                                | 155 ms: 1.12x slower                                                    |
| tomli_loads              | 2.07 sec                                                              | 2.35 sec: 1.13x slower                                                  |
| scimark_sparse_mat_mult  | 4.73 ms                                                               | 5.36 ms: 1.13x slower                                                   |
| pickle_list              | 4.60 us                                                               | 5.22 us: 1.13x slower                                                   |
| raytrace                 | 269 ms                                                                | 306 ms: 1.14x slower                                                    |
| unpickle_pure_python     | 213 us                                                                | 244 us: 1.14x slower                                                    |
| logging_silent           | 98.2 ns                                                               | 113 ns: 1.15x slower                                                    |
| regex_compile            | 136 ms                                                                | 156 ms: 1.15x slower                                                    |
| mako                     | 10.7 ms                                                               | 12.4 ms: 1.16x slower                                                   |
| fannkuch                 | 395 ms                                                                | 463 ms: 1.17x slower                                                    |
| scimark_monte_carlo      | 65.7 ms                                                               | 77.0 ms: 1.17x slower                                                   |
| deepcopy_memo            | 36.4 us                                                               | 43.2 us: 1.19x slower                                                   |
| deltablue                | 3.45 ms                                                               | 4.14 ms: 1.20x slower                                                   |
| pprint_safe_repr         | 716 ms                                                                | 860 ms: 1.20x slower                                                    |
| pyflate                  | 447 ms                                                                | 537 ms: 1.20x slower                                                    |
| float                    | 79.3 ms                                                               | 97.8 ms: 1.23x slower                                                   |
| chaos                    | 60.8 ms                                                               | 75.3 ms: 1.24x slower                                                   |
| nqueens                  | 78.4 ms                                                               | 97.2 ms: 1.24x slower                                                   |
| pprint_pformat           | 1.47 sec                                                              | 1.82 sec: 1.24x slower                                                  |
| nbody                    | 89.7 ms                                                               | 112 ms: 1.25x slower                                                    |
| comprehensions           | 20.5 us                                                               | 26.9 us: 1.32x slower                                                   |
| hexiom                   | 5.99 ms                                                               | 9.49 ms: 1.58x slower                                                   |
| Geometric mean           | (ref)                                                                 | 1.09x slower                                                            |

Benchmark hidden because not significant (2): regex_effbot, bench_mp_pool
Ignored benchmarks (11) of results/bm-20231030-3.13.0a0-bfdeb03/bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03.json: 2to3, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
