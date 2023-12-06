
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.02x faster
- HPT reliability: 88.12%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 259 ms                                                 | 269 ms: 1.04x slower                                    |
| docutils       | 2.63 sec                                               | 2.71 sec: 1.03x slower                                  |
| tornado_http   | 96.3 ms                                                | 99.6 ms: 1.03x slower                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                    |
| nbody          | 93.1 ms                                                | 89.8 ms: 1.04x faster                                   |
| float          | 77.2 ms                                                | 80.0 ms: 1.04x slower                                   |
| Geometric mean | (ref)                                                  | 1.02x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.72 ms: 1.07x faster                                   |
| regex_compile  | 138 ms                                                 | 143 ms: 1.04x slower                                    |
| regex_v8       | 22.0 ms                                                | 22.9 ms: 1.04x slower                                   |
| regex_dna      | 204 ms                                                 | 214 ms: 1.05x slower                                    |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.82 ms: 1.28x faster                                   |
| json_loads           | 26.5 us                                                | 25.0 us: 1.06x faster                                   |
| unpickle_pure_python | 228 us                                                 | 218 us: 1.05x faster                                    |
| xml_etree_parse      | 158 ms                                                 | 154 ms: 1.03x faster                                    |
| tomli_loads          | 2.22 sec                                               | 2.19 sec: 1.02x faster                                  |
| pickle_dict          | 31.1 us                                                | 31.4 us: 1.01x slower                                   |
| pickle_pure_python   | 306 us                                                 | 314 us: 1.03x slower                                    |
| pickle               | 10.1 us                                                | 10.6 us: 1.05x slower                                   |
| xml_etree_process    | 53.9 ms                                                | 58.7 ms: 1.09x slower                                   |
| pickle_list          | 4.11 us                                                | 4.52 us: 1.10x slower                                   |
| unpickle_list        | 4.91 us                                                | 5.40 us: 1.10x slower                                   |
| xml_etree_generate   | 76.2 ms                                                | 84.4 ms: 1.11x slower                                   |
| unpickle             | 13.7 us                                                | 15.3 us: 1.12x slower                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.46 ms: 1.11x slower                                   |
| python_startup_no_site | 6.01 ms                                                | 6.88 ms: 1.15x slower                                   |
| Geometric mean         | (ref)                                                  | 1.13x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.9 ms: 1.08x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 148 us: 3.29x faster                                    |
| generators               | 73.5 ms                                                | 32.3 ms: 2.28x faster                                   |
| asyncio_tcp              | 922 ms                                                 | 524 ms: 1.76x faster                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                  |
| json_dumps               | 12.6 ms                                                | 9.82 ms: 1.28x faster                                   |
| mypy2                    | 420 ms                                                 | 345 ms: 1.22x faster                                    |
| coroutines               | 25.5 ms                                                | 22.0 ms: 1.16x faster                                   |
| richards_super           | 56.8 ms                                                | 50.3 ms: 1.13x faster                                   |
| async_tree_io            | 1.30 sec                                               | 1.15 sec: 1.13x faster                                  |
| async_tree_none          | 526 ms                                                 | 469 ms: 1.12x faster                                    |
| async_tree_memoization   | 627 ms                                                 | 572 ms: 1.10x faster                                    |
| chaos                    | 69.2 ms                                                | 63.5 ms: 1.09x faster                                   |
| comprehensions           | 22.4 us                                                | 20.9 us: 1.08x faster                                   |
| regex_effbot             | 3.99 ms                                                | 3.72 ms: 1.07x faster                                   |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                    |
| json_loads               | 26.5 us                                                | 25.0 us: 1.06x faster                                   |
| coverage                 | 100 ms                                                 | 94.6 ms: 1.06x faster                                   |
| sqlglot_parse            | 1.40 ms                                                | 1.33 ms: 1.06x faster                                   |
| unpickle_pure_python     | 228 us                                                 | 218 us: 1.05x faster                                    |
| hexiom                   | 6.37 ms                                                | 6.11 ms: 1.04x faster                                   |
| nqueens                  | 83.4 ms                                                | 80.2 ms: 1.04x faster                                   |
| richards                 | 45.7 ms                                                | 44.1 ms: 1.04x faster                                   |
| nbody                    | 93.1 ms                                                | 89.8 ms: 1.04x faster                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.64 ms: 1.04x faster                                   |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 714 ms: 1.03x faster                                    |
| go                       | 140 ms                                                 | 136 ms: 1.03x faster                                    |
| json                     | 4.94 ms                                                | 4.81 ms: 1.03x faster                                   |
| xml_etree_parse          | 158 ms                                                 | 154 ms: 1.03x faster                                    |
| deltablue                | 3.67 ms                                                | 3.57 ms: 1.03x faster                                   |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                  |
| gc_traversal             | 4.02 ms                                                | 3.96 ms: 1.02x faster                                   |
| tomli_loads              | 2.22 sec                                               | 2.19 sec: 1.02x faster                                  |
| sqlglot_normalize        | 108 ms                                                 | 108 ms: 1.00x slower                                    |
| raytrace                 | 297 ms                                                 | 299 ms: 1.01x slower                                    |
| pickle_dict              | 31.1 us                                                | 31.4 us: 1.01x slower                                   |
| logging_silent           | 101 ns                                                 | 103 ns: 1.02x slower                                    |
| bench_thread_pool        | 819 us                                                 | 833 us: 1.02x slower                                    |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                   |
| fannkuch                 | 388 ms                                                 | 395 ms: 1.02x slower                                    |
| mdp                      | 2.62 sec                                               | 2.68 sec: 1.02x slower                                  |
| scimark_lu               | 110 ms                                                 | 112 ms: 1.02x slower                                    |
| deepcopy_memo            | 37.0 us                                                | 37.9 us: 1.02x slower                                   |
| pickle_pure_python       | 306 us                                                 | 314 us: 1.03x slower                                    |
| pathlib                  | 18.2 ms                                                | 18.8 ms: 1.03x slower                                   |
| docutils                 | 2.63 sec                                               | 2.71 sec: 1.03x slower                                  |
| sqlalchemy_imperative    | 17.9 ms                                                | 18.5 ms: 1.03x slower                                   |
| tornado_http             | 96.3 ms                                                | 99.6 ms: 1.03x slower                                   |
| pprint_pformat           | 1.46 sec                                               | 1.51 sec: 1.04x slower                                  |
| float                    | 77.2 ms                                                | 80.0 ms: 1.04x slower                                   |
| telco                    | 6.58 ms                                                | 6.82 ms: 1.04x slower                                   |
| scimark_sor              | 118 ms                                                 | 122 ms: 1.04x slower                                    |
| crypto_pyaes             | 74.7 ms                                                | 77.4 ms: 1.04x slower                                   |
| deepcopy                 | 342 us                                                 | 355 us: 1.04x slower                                    |
| regex_compile            | 138 ms                                                 | 143 ms: 1.04x slower                                    |
| spectral_norm            | 100 ms                                                 | 104 ms: 1.04x slower                                    |
| regex_v8                 | 22.0 ms                                                | 22.9 ms: 1.04x slower                                   |
| 2to3                     | 259 ms                                                 | 269 ms: 1.04x slower                                    |
| scimark_monte_carlo      | 68.1 ms                                                | 70.9 ms: 1.04x slower                                   |
| sqlalchemy_declarative   | 138 ms                                                 | 145 ms: 1.05x slower                                    |
| pickle                   | 10.1 us                                                | 10.6 us: 1.05x slower                                   |
| regex_dna                | 204 ms                                                 | 214 ms: 1.05x slower                                    |
| pprint_safe_repr         | 701 ms                                                 | 737 ms: 1.05x slower                                    |
| logging_simple           | 6.03 us                                                | 6.38 us: 1.06x slower                                   |
| logging_format           | 6.68 us                                                | 7.11 us: 1.06x slower                                   |
| dulwich_log              | 63.7 ms                                                | 67.8 ms: 1.07x slower                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.84 ms: 1.08x slower                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.17 us: 1.08x slower                                   |
| mako                     | 10.1 ms                                                | 10.9 ms: 1.08x slower                                   |
| xml_etree_process        | 53.9 ms                                                | 58.7 ms: 1.09x slower                                   |
| scimark_fft              | 328 ms                                                 | 360 ms: 1.10x slower                                    |
| pickle_list              | 4.11 us                                                | 4.52 us: 1.10x slower                                   |
| unpickle_list            | 4.91 us                                                | 5.40 us: 1.10x slower                                   |
| sqlite_synth             | 2.52 us                                                | 2.79 us: 1.11x slower                                   |
| xml_etree_generate       | 76.2 ms                                                | 84.4 ms: 1.11x slower                                   |
| python_startup           | 8.52 ms                                                | 9.46 ms: 1.11x slower                                   |
| pyflate                  | 418 ms                                                 | 466 ms: 1.11x slower                                    |
| unpickle                 | 13.7 us                                                | 15.3 us: 1.12x slower                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.88 ms: 1.15x slower                                   |
| unpack_sequence          | 43.1 ns                                                | 50.3 ns: 1.17x slower                                   |
| async_generators         | 368 ms                                                 | 445 ms: 1.21x slower                                    |
| dask                     | 360 ms                                                 | 535 ms: 1.49x slower                                    |
| Geometric mean           | (ref)                                                  | 1.02x faster                                            |

Benchmark hidden because not significant (4): xml_etree_iterparse, bench_mp_pool, sqlglot_optimize, meteor_contest
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 88.12% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
