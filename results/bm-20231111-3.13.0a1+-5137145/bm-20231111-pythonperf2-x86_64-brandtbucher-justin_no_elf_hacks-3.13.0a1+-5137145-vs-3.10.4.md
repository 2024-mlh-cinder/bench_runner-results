
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: linux-x86_64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.26x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 299 ms: 1.17x faster                                                              |
| chameleon      | 9.88 ms                                                      | 7.64 ms: 1.29x faster                                                             |
| docutils       | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                                            |
| tornado_http   | 157 ms                                                       | 121 ms: 1.30x faster                                                              |
| Geometric mean | (ref)                                                        | 1.23x faster                                                                      |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 438 ms: 1.60x faster                                                              |
| async_tree_memoization  | 827 ms                                                       | 549 ms: 1.51x faster                                                              |
| async_tree_io           | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                            |
| async_tree_cpu_io_mixed | 946 ms                                                       | 701 ms: 1.35x faster                                                              |
| Geometric mean          | (ref)                                                        | 1.48x faster                                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 96.7 ms: 1.39x faster                                                             |
| float          | 109 ms                                                       | 81.3 ms: 1.34x faster                                                             |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                                              |
| Geometric mean | (ref)                                                        | 1.24x faster                                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 150 ms: 1.28x faster                                                              |
| regex_dna      | 260 ms                                                       | 239 ms: 1.09x faster                                                              |
| regex_v8       | 27.1 ms                                                      | 25.0 ms: 1.08x faster                                                             |
| regex_effbot   | 3.10 ms                                                      | 3.46 ms: 1.12x slower                                                             |
| Geometric mean | (ref)                                                        | 1.08x faster                                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 315 us: 1.44x faster                                                              |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                                             |
| xml_etree_process    | 76.4 ms                                                      | 58.0 ms: 1.32x faster                                                             |
| unpickle_pure_python | 315 us                                                       | 248 us: 1.27x faster                                                              |
| json_loads           | 30.0 us                                                      | 24.4 us: 1.23x faster                                                             |
| tomli_loads          | 2.96 sec                                                     | 2.40 sec: 1.23x faster                                                            |
| xml_etree_parse      | 159 ms                                                       | 146 ms: 1.09x faster                                                              |
| xml_etree_generate   | 93.1 ms                                                      | 85.7 ms: 1.09x faster                                                             |
| xml_etree_iterparse  | 110 ms                                                       | 103 ms: 1.06x faster                                                              |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                             |
| unpickle             | 13.9 us                                                      | 14.2 us: 1.02x slower                                                             |
| pickle_list          | 4.23 us                                                      | 4.44 us: 1.05x slower                                                             |
| unpickle_list        | 4.45 us                                                      | 4.80 us: 1.08x slower                                                             |
| pickle_dict          | 30.4 us                                                      | 33.8 us: 1.11x slower                                                             |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                             |
| python_startup_no_site | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                             |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 11.2 ms: 1.32x faster                                                             |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 129 us: 4.15x faster                                                              |
| asyncio_tcp              | 785 ms                                                       | 366 ms: 2.14x faster                                                              |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                                            |
| deltablue                | 7.43 ms                                                      | 3.80 ms: 1.96x faster                                                             |
| raytrace                 | 497 ms                                                       | 285 ms: 1.74x faster                                                              |
| logging_silent           | 168 ns                                                       | 96.8 ns: 1.73x faster                                                             |
| generators               | 57.7 ms                                                      | 35.7 ms: 1.62x faster                                                             |
| sqlglot_parse            | 2.27 ms                                                      | 1.41 ms: 1.61x faster                                                             |
| async_tree_none          | 700 ms                                                       | 438 ms: 1.60x faster                                                              |
| richards_super           | 93.0 ms                                                      | 58.3 ms: 1.59x faster                                                             |
| chaos                    | 106 ms                                                       | 67.0 ms: 1.58x faster                                                             |
| scimark_lu               | 165 ms                                                       | 105 ms: 1.57x faster                                                              |
| spectral_norm            | 141 ms                                                       | 91.1 ms: 1.55x faster                                                             |
| crypto_pyaes             | 118 ms                                                       | 78.0 ms: 1.51x faster                                                             |
| async_tree_memoization   | 827 ms                                                       | 549 ms: 1.51x faster                                                              |
| sqlglot_transpile        | 2.73 ms                                                      | 1.82 ms: 1.50x faster                                                             |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                            |
| scimark_monte_carlo      | 109 ms                                                       | 73.9 ms: 1.48x faster                                                             |
| richards                 | 76.3 ms                                                      | 52.1 ms: 1.46x faster                                                             |
| go                       | 258 ms                                                       | 176 ms: 1.46x faster                                                              |
| pickle_pure_python       | 453 us                                                       | 315 us: 1.44x faster                                                              |
| nbody                    | 134 ms                                                       | 96.7 ms: 1.39x faster                                                             |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                                             |
| pyflate                  | 698 ms                                                       | 509 ms: 1.37x faster                                                              |
| deepcopy_memo            | 50.5 us                                                      | 37.0 us: 1.36x faster                                                             |
| coroutines               | 30.9 ms                                                      | 22.7 ms: 1.36x faster                                                             |
| logging_simple           | 9.06 us                                                      | 6.68 us: 1.36x faster                                                             |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 701 ms: 1.35x faster                                                              |
| float                    | 109 ms                                                       | 81.3 ms: 1.34x faster                                                             |
| unpack_sequence          | 60.3 ns                                                      | 45.5 ns: 1.32x faster                                                             |
| mako                     | 14.7 ms                                                      | 11.2 ms: 1.32x faster                                                             |
| logging_format           | 9.82 us                                                      | 7.44 us: 1.32x faster                                                             |
| xml_etree_process        | 76.4 ms                                                      | 58.0 ms: 1.32x faster                                                             |
| tornado_http             | 157 ms                                                       | 121 ms: 1.30x faster                                                              |
| chameleon                | 9.88 ms                                                      | 7.64 ms: 1.29x faster                                                             |
| regex_compile            | 192 ms                                                       | 150 ms: 1.28x faster                                                              |
| deepcopy                 | 459 us                                                       | 359 us: 1.28x faster                                                              |
| unpickle_pure_python     | 315 us                                                       | 248 us: 1.27x faster                                                              |
| pprint_pformat           | 2.15 sec                                                     | 1.71 sec: 1.26x faster                                                            |
| sqlglot_normalize        | 146 ms                                                       | 116 ms: 1.26x faster                                                              |
| comprehensions           | 27.0 us                                                      | 21.5 us: 1.26x faster                                                             |
| sympy_sum                | 194 ms                                                       | 155 ms: 1.25x faster                                                              |
| mypy2                    | 467 ms                                                       | 374 ms: 1.25x faster                                                              |
| pprint_safe_repr         | 1.04 sec                                                     | 836 ms: 1.24x faster                                                              |
| deepcopy_reduce          | 4.00 us                                                      | 3.23 us: 1.24x faster                                                             |
| pycparser                | 1.65 sec                                                     | 1.34 sec: 1.23x faster                                                            |
| json_loads               | 30.0 us                                                      | 24.4 us: 1.23x faster                                                             |
| tomli_loads              | 2.96 sec                                                     | 2.40 sec: 1.23x faster                                                            |
| scimark_sor              | 183 ms                                                       | 149 ms: 1.23x faster                                                              |
| sympy_str                | 359 ms                                                       | 294 ms: 1.22x faster                                                              |
| bench_mp_pool            | 6.82 ms                                                      | 5.60 ms: 1.22x faster                                                             |
| sympy_expand             | 599 ms                                                       | 494 ms: 1.21x faster                                                              |
| docutils                 | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                                            |
| sqlglot_optimize         | 69.9 ms                                                      | 59.0 ms: 1.18x faster                                                             |
| create_gc_cycles         | 1.79 ms                                                      | 1.51 ms: 1.18x faster                                                             |
| dulwich_log              | 80.0 ms                                                      | 67.8 ms: 1.18x faster                                                             |
| sympy_integrate          | 28.3 ms                                                      | 24.0 ms: 1.18x faster                                                             |
| json                     | 5.91 ms                                                      | 5.05 ms: 1.17x faster                                                             |
| 2to3                     | 349 ms                                                       | 299 ms: 1.17x faster                                                              |
| bench_thread_pool        | 1.13 ms                                                      | 976 us: 1.16x faster                                                              |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.51 ms: 1.16x faster                                                             |
| hexiom                   | 9.46 ms                                                      | 8.19 ms: 1.15x faster                                                             |
| fannkuch                 | 488 ms                                                       | 423 ms: 1.15x faster                                                              |
| mdp                      | 2.94 sec                                                     | 2.62 sec: 1.12x faster                                                            |
| sqlite_synth             | 2.97 us                                                      | 2.68 us: 1.11x faster                                                             |
| async_generators         | 418 ms                                                       | 382 ms: 1.09x faster                                                              |
| xml_etree_parse          | 159 ms                                                       | 146 ms: 1.09x faster                                                              |
| regex_dna                | 260 ms                                                       | 239 ms: 1.09x faster                                                              |
| xml_etree_generate       | 93.1 ms                                                      | 85.7 ms: 1.09x faster                                                             |
| nqueens                  | 112 ms                                                       | 103 ms: 1.08x faster                                                              |
| regex_v8                 | 27.1 ms                                                      | 25.0 ms: 1.08x faster                                                             |
| pathlib                  | 21.2 ms                                                      | 19.7 ms: 1.07x faster                                                             |
| xml_etree_iterparse      | 110 ms                                                       | 103 ms: 1.06x faster                                                              |
| scimark_fft              | 363 ms                                                       | 345 ms: 1.05x faster                                                              |
| meteor_contest           | 138 ms                                                       | 133 ms: 1.03x faster                                                              |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                                              |
| asyncio_websockets       | 394 ms                                                       | 390 ms: 1.01x faster                                                              |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                             |
| unpickle                 | 13.9 us                                                      | 14.2 us: 1.02x slower                                                             |
| pickle_list              | 4.23 us                                                      | 4.44 us: 1.05x slower                                                             |
| unpickle_list            | 4.45 us                                                      | 4.80 us: 1.08x slower                                                             |
| pickle_dict              | 30.4 us                                                      | 33.8 us: 1.11x slower                                                             |
| regex_effbot             | 3.10 ms                                                      | 3.46 ms: 1.12x slower                                                             |
| python_startup           | 11.5 ms                                                      | 12.9 ms: 1.12x slower                                                             |
| telco                    | 7.21 ms                                                      | 8.42 ms: 1.17x slower                                                             |
| coverage                 | 65.9 ms                                                      | 83.1 ms: 1.26x slower                                                             |
| python_startup_no_site   | 7.35 ms                                                      | 11.4 ms: 1.55x slower                                                             |
| Geometric mean           | (ref)                                                        | 1.26x faster                                                                      |

Benchmark hidden because not significant (1): gc_traversal
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-5137145/bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.22x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.18x
