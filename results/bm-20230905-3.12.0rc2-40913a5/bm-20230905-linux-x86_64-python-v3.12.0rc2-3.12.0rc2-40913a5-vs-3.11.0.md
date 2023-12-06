
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0rc2
- machine: linux-x86_64
- commit hash: 40913a5
- commit date: 2023-09-05
- overall geometric mean: 1.03x faster
- HPT reliability: 88.12%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 259 ms                                                 | 268 ms: 1.04x slower                                         |
| docutils       | 2.63 sec                                               | 2.71 sec: 1.03x slower                                       |
| tornado_http   | 96.3 ms                                                | 102 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                  | 1.04x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 77.2 ms                                                | 80.1 ms: 1.04x slower                                        |
| pidigits       | 198 ms                                                 | 212 ms: 1.07x slower                                         |
| Geometric mean | (ref)                                                  | 1.04x slower                                                 |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.59 ms: 1.11x faster                                        |
| regex_v8       | 22.0 ms                                                | 22.3 ms: 1.01x slower                                        |
| regex_compile  | 138 ms                                                 | 144 ms: 1.04x slower                                         |
| regex_dna      | 204 ms                                                 | 213 ms: 1.05x slower                                         |
| Geometric mean | (ref)                                                  | 1.00x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.89 ms: 1.27x faster                                        |
| json_loads           | 26.5 us                                                | 25.1 us: 1.05x faster                                        |
| unpickle_pure_python | 228 us                                                 | 219 us: 1.04x faster                                         |
| xml_etree_parse      | 158 ms                                                 | 154 ms: 1.03x faster                                         |
| tomli_loads          | 2.22 sec                                               | 2.20 sec: 1.01x faster                                       |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                         |
| pickle_dict          | 31.1 us                                                | 31.8 us: 1.02x slower                                        |
| pickle_pure_python   | 306 us                                                 | 314 us: 1.03x slower                                         |
| pickle               | 10.1 us                                                | 10.6 us: 1.05x slower                                        |
| xml_etree_process    | 53.9 ms                                                | 58.7 ms: 1.09x slower                                        |
| unpickle_list        | 4.91 us                                                | 5.38 us: 1.10x slower                                        |
| unpickle             | 13.7 us                                                | 15.1 us: 1.11x slower                                        |
| xml_etree_generate   | 76.2 ms                                                | 84.3 ms: 1.11x slower                                        |
| pickle_list          | 4.11 us                                                | 4.67 us: 1.13x slower                                        |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.46 ms: 1.11x slower                                        |
| python_startup_no_site | 6.01 ms                                                | 6.88 ms: 1.15x slower                                        |
| Geometric mean         | (ref)                                                  | 1.13x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.9 ms: 1.08x slower                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 144 us: 3.37x faster                                         |
| generators               | 73.5 ms                                                | 30.8 ms: 2.39x faster                                        |
| asyncio_tcp              | 922 ms                                                 | 505 ms: 1.82x faster                                         |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                       |
| json_dumps               | 12.6 ms                                                | 9.89 ms: 1.27x faster                                        |
| mypy2                    | 420 ms                                                 | 344 ms: 1.22x faster                                         |
| richards_super           | 56.8 ms                                                | 48.9 ms: 1.16x faster                                        |
| coroutines               | 25.5 ms                                                | 22.1 ms: 1.16x faster                                        |
| async_tree_io            | 1.30 sec                                               | 1.14 sec: 1.14x faster                                       |
| async_tree_none          | 526 ms                                                 | 465 ms: 1.13x faster                                         |
| regex_effbot             | 3.99 ms                                                | 3.59 ms: 1.11x faster                                        |
| async_tree_memoization   | 627 ms                                                 | 571 ms: 1.10x faster                                         |
| chaos                    | 69.2 ms                                                | 63.8 ms: 1.08x faster                                        |
| comprehensions           | 22.4 us                                                | 20.7 us: 1.08x faster                                        |
| coverage                 | 100 ms                                                 | 94.7 ms: 1.06x faster                                        |
| richards                 | 45.7 ms                                                | 43.3 ms: 1.06x faster                                        |
| json_loads               | 26.5 us                                                | 25.1 us: 1.05x faster                                        |
| deltablue                | 3.67 ms                                                | 3.49 ms: 1.05x faster                                        |
| sqlglot_parse            | 1.40 ms                                                | 1.33 ms: 1.05x faster                                        |
| gc_traversal             | 4.02 ms                                                | 3.83 ms: 1.05x faster                                        |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 708 ms: 1.04x faster                                         |
| unpickle_pure_python     | 228 us                                                 | 219 us: 1.04x faster                                         |
| go                       | 140 ms                                                 | 135 ms: 1.03x faster                                         |
| sqlglot_transpile        | 1.70 ms                                                | 1.65 ms: 1.03x faster                                        |
| hexiom                   | 6.37 ms                                                | 6.17 ms: 1.03x faster                                        |
| json                     | 4.94 ms                                                | 4.80 ms: 1.03x faster                                        |
| xml_etree_parse          | 158 ms                                                 | 154 ms: 1.03x faster                                         |
| logging_silent           | 101 ns                                                 | 98.5 ns: 1.03x faster                                        |
| nqueens                  | 83.4 ms                                                | 81.4 ms: 1.02x faster                                        |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                       |
| mdp                      | 2.62 sec                                               | 2.58 sec: 1.02x faster                                       |
| raytrace                 | 297 ms                                                 | 293 ms: 1.01x faster                                         |
| tomli_loads              | 2.22 sec                                               | 2.20 sec: 1.01x faster                                       |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                         |
| pathlib                  | 18.2 ms                                                | 18.4 ms: 1.01x slower                                        |
| sqlglot_optimize         | 53.1 ms                                                | 53.5 ms: 1.01x slower                                        |
| bench_thread_pool        | 819 us                                                 | 829 us: 1.01x slower                                         |
| regex_v8                 | 22.0 ms                                                | 22.3 ms: 1.01x slower                                        |
| deepcopy_memo            | 37.0 us                                                | 37.5 us: 1.01x slower                                        |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                        |
| pickle_dict              | 31.1 us                                                | 31.8 us: 1.02x slower                                        |
| deepcopy                 | 342 us                                                 | 351 us: 1.03x slower                                         |
| pickle_pure_python       | 306 us                                                 | 314 us: 1.03x slower                                         |
| sqlalchemy_imperative    | 17.9 ms                                                | 18.4 ms: 1.03x slower                                        |
| fannkuch                 | 388 ms                                                 | 400 ms: 1.03x slower                                         |
| docutils                 | 2.63 sec                                               | 2.71 sec: 1.03x slower                                       |
| scimark_lu               | 110 ms                                                 | 113 ms: 1.03x slower                                         |
| 2to3                     | 259 ms                                                 | 268 ms: 1.04x slower                                         |
| pprint_pformat           | 1.46 sec                                               | 1.51 sec: 1.04x slower                                       |
| float                    | 77.2 ms                                                | 80.1 ms: 1.04x slower                                        |
| telco                    | 6.58 ms                                                | 6.83 ms: 1.04x slower                                        |
| logging_simple           | 6.03 us                                                | 6.28 us: 1.04x slower                                        |
| regex_compile            | 138 ms                                                 | 144 ms: 1.04x slower                                         |
| regex_dna                | 204 ms                                                 | 213 ms: 1.05x slower                                         |
| pprint_safe_repr         | 701 ms                                                 | 736 ms: 1.05x slower                                         |
| scimark_monte_carlo      | 68.1 ms                                                | 71.4 ms: 1.05x slower                                        |
| pickle                   | 10.1 us                                                | 10.6 us: 1.05x slower                                        |
| sqlalchemy_declarative   | 138 ms                                                 | 145 ms: 1.05x slower                                         |
| scimark_sor              | 118 ms                                                 | 124 ms: 1.05x slower                                         |
| tornado_http             | 96.3 ms                                                | 102 ms: 1.06x slower                                         |
| unpack_sequence          | 43.1 ns                                                | 45.6 ns: 1.06x slower                                        |
| logging_format           | 6.68 us                                                | 7.08 us: 1.06x slower                                        |
| spectral_norm            | 100 ms                                                 | 106 ms: 1.06x slower                                         |
| deepcopy_reduce          | 2.94 us                                                | 3.12 us: 1.06x slower                                        |
| crypto_pyaes             | 74.7 ms                                                | 79.6 ms: 1.07x slower                                        |
| pidigits                 | 198 ms                                                 | 212 ms: 1.07x slower                                         |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.81 ms: 1.07x slower                                        |
| dulwich_log              | 63.7 ms                                                | 68.2 ms: 1.07x slower                                        |
| mako                     | 10.1 ms                                                | 10.9 ms: 1.08x slower                                        |
| sqlite_synth             | 2.52 us                                                | 2.74 us: 1.09x slower                                        |
| xml_etree_process        | 53.9 ms                                                | 58.7 ms: 1.09x slower                                        |
| unpickle_list            | 4.91 us                                                | 5.38 us: 1.10x slower                                        |
| unpickle                 | 13.7 us                                                | 15.1 us: 1.11x slower                                        |
| xml_etree_generate       | 76.2 ms                                                | 84.3 ms: 1.11x slower                                        |
| scimark_fft              | 328 ms                                                 | 364 ms: 1.11x slower                                         |
| python_startup           | 8.52 ms                                                | 9.46 ms: 1.11x slower                                        |
| pyflate                  | 418 ms                                                 | 467 ms: 1.12x slower                                         |
| pickle_list              | 4.11 us                                                | 4.67 us: 1.13x slower                                        |
| python_startup_no_site   | 6.01 ms                                                | 6.88 ms: 1.15x slower                                        |
| async_generators         | 368 ms                                                 | 445 ms: 1.21x slower                                         |
| dask                     | 360 ms                                                 | 537 ms: 1.49x slower                                         |
| Geometric mean           | (ref)                                                  | 1.03x faster                                                 |

Benchmark hidden because not significant (4): meteor_contest, bench_mp_pool, sqlglot_normalize, nbody
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 88.12% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
