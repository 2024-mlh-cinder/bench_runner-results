
# Results vs. 3.11.0

- fork: brandtbucher
- ref: break_up_float_reuse
- machine: linux-x86_64
- commit hash: 2dde229
- commit date: 2023-10-19
- overall geometric mean: 1.01x faster
- HPT reliability: 95.95%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.65 sec: 1.01x slower                                                       |
| tornado_http   | 96.3 ms                                                | 95.7 ms: 1.01x faster                                                        |
| Geometric mean | (ref)                                                  | 1.00x slower                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.05x faster                                                         |
| nbody          | 93.1 ms                                                | 95.9 ms: 1.03x slower                                                        |
| float          | 77.2 ms                                                | 82.0 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                  | 1.01x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 4.13 ms: 1.03x slower                                                        |
| regex_dna      | 204 ms                                                 | 218 ms: 1.07x slower                                                         |
| regex_v8       | 22.0 ms                                                | 24.3 ms: 1.10x slower                                                        |
| Geometric mean | (ref)                                                  | 1.05x slower                                                                 |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.4 ms: 1.21x faster                                                        |
| unpickle_pure_python | 228 us                                                 | 223 us: 1.02x faster                                                         |
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                                       |
| pickle_pure_python   | 306 us                                                 | 311 us: 1.02x slower                                                         |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                                         |
| json_loads           | 26.5 us                                                | 27.8 us: 1.05x slower                                                        |
| unpickle             | 13.7 us                                                | 14.5 us: 1.06x slower                                                        |
| unpickle_list        | 4.91 us                                                | 5.25 us: 1.07x slower                                                        |
| xml_etree_process    | 53.9 ms                                                | 59.9 ms: 1.11x slower                                                        |
| pickle_dict          | 31.1 us                                                | 34.9 us: 1.12x slower                                                        |
| xml_etree_generate   | 76.2 ms                                                | 86.5 ms: 1.14x slower                                                        |
| pickle               | 10.1 us                                                | 11.5 us: 1.14x slower                                                        |
| pickle_list          | 4.11 us                                                | 5.22 us: 1.27x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.05x slower                                                                 |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.86 ms: 1.14x slower                                                        |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                        |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.8 ms: 1.17x slower                                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 153 us: 3.18x faster                                                         |
| generators               | 73.5 ms                                                | 29.8 ms: 2.47x faster                                                        |
| asyncio_tcp              | 922 ms                                                 | 481 ms: 1.92x faster                                                         |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.76x faster                                                       |
| mypy2                    | 420 ms                                                 | 344 ms: 1.22x faster                                                         |
| json_dumps               | 12.6 ms                                                | 10.4 ms: 1.21x faster                                                        |
| async_tree_none          | 526 ms                                                 | 440 ms: 1.20x faster                                                         |
| chaos                    | 69.2 ms                                                | 62.1 ms: 1.11x faster                                                        |
| async_tree_memoization   | 627 ms                                                 | 564 ms: 1.11x faster                                                         |
| coverage                 | 100 ms                                                 | 90.6 ms: 1.10x faster                                                        |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                       |
| deltablue                | 3.67 ms                                                | 3.37 ms: 1.09x faster                                                        |
| sqlglot_parse            | 1.40 ms                                                | 1.29 ms: 1.09x faster                                                        |
| comprehensions           | 22.4 us                                                | 20.8 us: 1.08x faster                                                        |
| coroutines               | 25.5 ms                                                | 23.7 ms: 1.08x faster                                                        |
| raytrace                 | 297 ms                                                 | 279 ms: 1.06x faster                                                         |
| sqlglot_transpile        | 1.70 ms                                                | 1.60 ms: 1.06x faster                                                        |
| pidigits                 | 198 ms                                                 | 188 ms: 1.05x faster                                                         |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 714 ms: 1.03x faster                                                         |
| nqueens                  | 83.4 ms                                                | 80.9 ms: 1.03x faster                                                        |
| logging_format           | 6.68 us                                                | 6.53 us: 1.02x faster                                                        |
| richards_super           | 56.8 ms                                                | 55.5 ms: 1.02x faster                                                        |
| unpickle_pure_python     | 228 us                                                 | 223 us: 1.02x faster                                                         |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                                       |
| hexiom                   | 6.37 ms                                                | 6.26 ms: 1.02x faster                                                        |
| create_gc_cycles         | 1.49 ms                                                | 1.46 ms: 1.02x faster                                                        |
| logging_simple           | 6.03 us                                                | 5.96 us: 1.01x faster                                                        |
| crypto_pyaes             | 74.7 ms                                                | 73.8 ms: 1.01x faster                                                        |
| tornado_http             | 96.3 ms                                                | 95.7 ms: 1.01x faster                                                        |
| bench_thread_pool        | 819 us                                                 | 815 us: 1.00x faster                                                         |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.00x faster                                                         |
| gc_traversal             | 4.02 ms                                                | 4.04 ms: 1.00x slower                                                        |
| docutils                 | 2.63 sec                                               | 2.65 sec: 1.01x slower                                                       |
| sqlglot_optimize         | 53.1 ms                                                | 53.7 ms: 1.01x slower                                                        |
| pickle_pure_python       | 306 us                                                 | 311 us: 1.02x slower                                                         |
| meteor_contest           | 107 ms                                                 | 109 ms: 1.02x slower                                                         |
| mdp                      | 2.62 sec                                               | 2.67 sec: 1.02x slower                                                       |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                                         |
| go                       | 140 ms                                                 | 143 ms: 1.02x slower                                                         |
| pycparser                | 1.18 sec                                               | 1.22 sec: 1.03x slower                                                       |
| nbody                    | 93.1 ms                                                | 95.9 ms: 1.03x slower                                                        |
| regex_effbot             | 3.99 ms                                                | 4.13 ms: 1.03x slower                                                        |
| json                     | 4.94 ms                                                | 5.12 ms: 1.04x slower                                                        |
| deepcopy                 | 342 us                                                 | 355 us: 1.04x slower                                                         |
| scimark_monte_carlo      | 68.1 ms                                                | 70.7 ms: 1.04x slower                                                        |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                                        |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.05x slower                                                       |
| json_loads               | 26.5 us                                                | 27.8 us: 1.05x slower                                                        |
| dulwich_log              | 63.7 ms                                                | 67.0 ms: 1.05x slower                                                        |
| scimark_lu               | 110 ms                                                 | 116 ms: 1.06x slower                                                         |
| logging_silent           | 101 ns                                                 | 107 ns: 1.06x slower                                                         |
| deepcopy_memo            | 37.0 us                                                | 39.2 us: 1.06x slower                                                        |
| unpickle                 | 13.7 us                                                | 14.5 us: 1.06x slower                                                        |
| float                    | 77.2 ms                                                | 82.0 ms: 1.06x slower                                                        |
| pprint_safe_repr         | 701 ms                                                 | 748 ms: 1.07x slower                                                         |
| richards                 | 45.7 ms                                                | 48.8 ms: 1.07x slower                                                        |
| regex_dna                | 204 ms                                                 | 218 ms: 1.07x slower                                                         |
| unpickle_list            | 4.91 us                                                | 5.25 us: 1.07x slower                                                        |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.82 ms: 1.07x slower                                                        |
| deepcopy_reduce          | 2.94 us                                                | 3.16 us: 1.08x slower                                                        |
| fannkuch                 | 388 ms                                                 | 420 ms: 1.08x slower                                                         |
| regex_v8                 | 22.0 ms                                                | 24.3 ms: 1.10x slower                                                        |
| xml_etree_process        | 53.9 ms                                                | 59.9 ms: 1.11x slower                                                        |
| scimark_sor              | 118 ms                                                 | 132 ms: 1.12x slower                                                         |
| pickle_dict              | 31.1 us                                                | 34.9 us: 1.12x slower                                                        |
| xml_etree_generate       | 76.2 ms                                                | 86.5 ms: 1.14x slower                                                        |
| pyflate                  | 418 ms                                                 | 476 ms: 1.14x slower                                                         |
| sqlite_synth             | 2.52 us                                                | 2.87 us: 1.14x slower                                                        |
| pickle                   | 10.1 us                                                | 11.5 us: 1.14x slower                                                        |
| spectral_norm            | 100 ms                                                 | 114 ms: 1.14x slower                                                         |
| python_startup_no_site   | 6.01 ms                                                | 6.86 ms: 1.14x slower                                                        |
| scimark_fft              | 328 ms                                                 | 376 ms: 1.15x slower                                                         |
| mako                     | 10.1 ms                                                | 11.8 ms: 1.17x slower                                                        |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                        |
| async_generators         | 368 ms                                                 | 459 ms: 1.25x slower                                                         |
| pickle_list              | 4.11 us                                                | 5.22 us: 1.27x slower                                                        |
| telco                    | 6.58 ms                                                | 8.37 ms: 1.27x slower                                                        |
| unpack_sequence          | 43.1 ns                                                | 58.1 ns: 1.35x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                                 |

Benchmark hidden because not significant (3): bench_mp_pool, regex_compile, xml_etree_parse
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 95.95% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
