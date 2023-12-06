
# Results vs. 3.11.0

- fork: brandtbucher
- ref: break_up_float_reuse
- machine: linux-x86_64
- commit hash: 52776df
- commit date: 2023-10-17
- overall geometric mean: 1.02x faster
- HPT reliability: 85.15%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.64 sec: 1.01x slower                                                       |
| Geometric mean | (ref)                                                  | 1.00x slower                                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.06x faster                                                         |
| nbody          | 93.1 ms                                                | 95.1 ms: 1.02x slower                                                        |
| float          | 77.2 ms                                                | 81.6 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                  | 1.01x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 138 ms                                                 | 137 ms: 1.00x faster                                                         |
| regex_effbot   | 3.99 ms                                                | 4.06 ms: 1.02x slower                                                        |
| regex_dna      | 204 ms                                                 | 214 ms: 1.05x slower                                                         |
| regex_v8       | 22.0 ms                                                | 25.6 ms: 1.16x slower                                                        |
| Geometric mean | (ref)                                                  | 1.05x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.4 ms: 1.21x faster                                                        |
| tomli_loads          | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                       |
| unpickle_pure_python | 228 us                                                 | 225 us: 1.01x faster                                                         |
| pickle_pure_python   | 306 us                                                 | 309 us: 1.01x slower                                                         |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                                         |
| unpickle_list        | 4.91 us                                                | 5.00 us: 1.02x slower                                                        |
| unpickle             | 13.7 us                                                | 14.3 us: 1.05x slower                                                        |
| json_loads           | 26.5 us                                                | 27.9 us: 1.06x slower                                                        |
| xml_etree_process    | 53.9 ms                                                | 59.5 ms: 1.11x slower                                                        |
| xml_etree_generate   | 76.2 ms                                                | 85.8 ms: 1.13x slower                                                        |
| pickle_dict          | 31.1 us                                                | 35.6 us: 1.15x slower                                                        |
| pickle               | 10.1 us                                                | 11.7 us: 1.16x slower                                                        |
| pickle_list          | 4.11 us                                                | 4.97 us: 1.21x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.05x slower                                                                 |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.82 ms: 1.14x slower                                                        |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.17x slower                                                        |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 12.0 ms: 1.19x slower                                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 154 us: 3.17x faster                                                         |
| generators               | 73.5 ms                                                | 29.8 ms: 2.46x faster                                                        |
| asyncio_tcp              | 922 ms                                                 | 478 ms: 1.93x faster                                                         |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.78 sec: 1.76x faster                                                       |
| mypy2                    | 420 ms                                                 | 342 ms: 1.23x faster                                                         |
| json_dumps               | 12.6 ms                                                | 10.4 ms: 1.21x faster                                                        |
| async_tree_none          | 526 ms                                                 | 438 ms: 1.20x faster                                                         |
| coroutines               | 25.5 ms                                                | 22.7 ms: 1.12x faster                                                        |
| chaos                    | 69.2 ms                                                | 62.0 ms: 1.12x faster                                                        |
| async_tree_memoization   | 627 ms                                                 | 562 ms: 1.12x faster                                                         |
| deltablue                | 3.67 ms                                                | 3.32 ms: 1.11x faster                                                        |
| coverage                 | 100 ms                                                 | 91.1 ms: 1.10x faster                                                        |
| async_tree_io            | 1.30 sec                                               | 1.18 sec: 1.10x faster                                                       |
| sqlglot_parse            | 1.40 ms                                                | 1.29 ms: 1.08x faster                                                        |
| comprehensions           | 22.4 us                                                | 20.8 us: 1.08x faster                                                        |
| raytrace                 | 297 ms                                                 | 280 ms: 1.06x faster                                                         |
| sqlglot_transpile        | 1.70 ms                                                | 1.61 ms: 1.06x faster                                                        |
| pidigits                 | 198 ms                                                 | 188 ms: 1.06x faster                                                         |
| logging_format           | 6.68 us                                                | 6.43 us: 1.04x faster                                                        |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 711 ms: 1.04x faster                                                         |
| richards_super           | 56.8 ms                                                | 54.8 ms: 1.04x faster                                                        |
| crypto_pyaes             | 74.7 ms                                                | 72.5 ms: 1.03x faster                                                        |
| tomli_loads              | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                       |
| nqueens                  | 83.4 ms                                                | 81.3 ms: 1.03x faster                                                        |
| create_gc_cycles         | 1.49 ms                                                | 1.46 ms: 1.02x faster                                                        |
| logging_simple           | 6.03 us                                                | 5.91 us: 1.02x faster                                                        |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                                         |
| unpickle_pure_python     | 228 us                                                 | 225 us: 1.01x faster                                                         |
| mdp                      | 2.62 sec                                               | 2.58 sec: 1.01x faster                                                       |
| bench_thread_pool        | 819 us                                                 | 811 us: 1.01x faster                                                         |
| hexiom                   | 6.37 ms                                                | 6.31 ms: 1.01x faster                                                        |
| unpack_sequence          | 43.1 ns                                                | 42.9 ns: 1.01x faster                                                        |
| regex_compile            | 138 ms                                                 | 137 ms: 1.00x faster                                                         |
| gc_traversal             | 4.02 ms                                                | 4.04 ms: 1.00x slower                                                        |
| docutils                 | 2.63 sec                                               | 2.64 sec: 1.01x slower                                                       |
| scimark_monte_carlo      | 68.1 ms                                                | 68.6 ms: 1.01x slower                                                        |
| sqlglot_optimize         | 53.1 ms                                                | 53.6 ms: 1.01x slower                                                        |
| pickle_pure_python       | 306 us                                                 | 309 us: 1.01x slower                                                         |
| regex_effbot             | 3.99 ms                                                | 4.06 ms: 1.02x slower                                                        |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                                         |
| unpickle_list            | 4.91 us                                                | 5.00 us: 1.02x slower                                                        |
| meteor_contest           | 107 ms                                                 | 109 ms: 1.02x slower                                                         |
| nbody                    | 93.1 ms                                                | 95.1 ms: 1.02x slower                                                        |
| pycparser                | 1.18 sec                                               | 1.21 sec: 1.02x slower                                                       |
| go                       | 140 ms                                                 | 143 ms: 1.02x slower                                                         |
| json                     | 4.94 ms                                                | 5.13 ms: 1.04x slower                                                        |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.04x slower                                                       |
| deepcopy                 | 342 us                                                 | 357 us: 1.04x slower                                                         |
| scimark_lu               | 110 ms                                                 | 115 ms: 1.05x slower                                                         |
| dulwich_log              | 63.7 ms                                                | 66.7 ms: 1.05x slower                                                        |
| unpickle                 | 13.7 us                                                | 14.3 us: 1.05x slower                                                        |
| regex_dna                | 204 ms                                                 | 214 ms: 1.05x slower                                                         |
| pathlib                  | 18.2 ms                                                | 19.2 ms: 1.05x slower                                                        |
| json_loads               | 26.5 us                                                | 27.9 us: 1.06x slower                                                        |
| float                    | 77.2 ms                                                | 81.6 ms: 1.06x slower                                                        |
| deepcopy_memo            | 37.0 us                                                | 39.2 us: 1.06x slower                                                        |
| richards                 | 45.7 ms                                                | 48.5 ms: 1.06x slower                                                        |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.82 ms: 1.07x slower                                                        |
| logging_silent           | 101 ns                                                 | 108 ns: 1.07x slower                                                         |
| pprint_safe_repr         | 701 ms                                                 | 753 ms: 1.07x slower                                                         |
| deepcopy_reduce          | 2.94 us                                                | 3.21 us: 1.09x slower                                                        |
| fannkuch                 | 388 ms                                                 | 424 ms: 1.09x slower                                                         |
| pyflate                  | 418 ms                                                 | 459 ms: 1.10x slower                                                         |
| xml_etree_process        | 53.9 ms                                                | 59.5 ms: 1.11x slower                                                        |
| scimark_sor              | 118 ms                                                 | 132 ms: 1.12x slower                                                         |
| scimark_fft              | 328 ms                                                 | 369 ms: 1.12x slower                                                         |
| xml_etree_generate       | 76.2 ms                                                | 85.8 ms: 1.13x slower                                                        |
| spectral_norm            | 100 ms                                                 | 113 ms: 1.13x slower                                                         |
| sqlite_synth             | 2.52 us                                                | 2.85 us: 1.13x slower                                                        |
| python_startup_no_site   | 6.01 ms                                                | 6.82 ms: 1.14x slower                                                        |
| pickle_dict              | 31.1 us                                                | 35.6 us: 1.15x slower                                                        |
| regex_v8                 | 22.0 ms                                                | 25.6 ms: 1.16x slower                                                        |
| pickle                   | 10.1 us                                                | 11.7 us: 1.16x slower                                                        |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.17x slower                                                        |
| mako                     | 10.1 ms                                                | 12.0 ms: 1.19x slower                                                        |
| pickle_list              | 4.11 us                                                | 4.97 us: 1.21x slower                                                        |
| async_generators         | 368 ms                                                 | 462 ms: 1.25x slower                                                         |
| telco                    | 6.58 ms                                                | 8.26 ms: 1.25x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.02x faster                                                                 |

Benchmark hidden because not significant (3): tornado_http, bench_mp_pool, xml_etree_parse
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 85.15% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
