
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.03x faster
- HPT reliability: 89.21%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 259 ms                                                 | 270 ms: 1.04x slower                                    |
| docutils       | 2.63 sec                                               | 2.72 sec: 1.04x slower                                  |
| tornado_http   | 96.3 ms                                                | 99.5 ms: 1.03x slower                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| nbody          | 93.1 ms                                                | 88.7 ms: 1.05x faster                                   |
| float          | 77.2 ms                                                | 79.0 ms: 1.02x slower                                   |
| pidigits       | 198 ms                                                 | 212 ms: 1.07x slower                                    |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.73 ms: 1.07x faster                                   |
| regex_dna      | 204 ms                                                 | 211 ms: 1.03x slower                                    |
| regex_v8       | 22.0 ms                                                | 22.9 ms: 1.04x slower                                   |
| regex_compile  | 138 ms                                                 | 144 ms: 1.05x slower                                    |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.72 ms: 1.29x faster                                   |
| json_loads           | 26.5 us                                                | 25.0 us: 1.06x faster                                   |
| unpickle_pure_python | 228 us                                                 | 220 us: 1.04x faster                                    |
| xml_etree_parse      | 158 ms                                                 | 153 ms: 1.04x faster                                    |
| pickle_pure_python   | 306 us                                                 | 313 us: 1.02x slower                                    |
| pickle_dict          | 31.1 us                                                | 32.2 us: 1.03x slower                                   |
| unpickle_list        | 4.91 us                                                | 5.11 us: 1.04x slower                                   |
| pickle               | 10.1 us                                                | 10.9 us: 1.08x slower                                   |
| xml_etree_process    | 53.9 ms                                                | 59.1 ms: 1.10x slower                                   |
| xml_etree_generate   | 76.2 ms                                                | 84.7 ms: 1.11x slower                                   |
| pickle_list          | 4.11 us                                                | 4.69 us: 1.14x slower                                   |
| unpickle             | 13.7 us                                                | 15.6 us: 1.14x slower                                   |
| Geometric mean       | (ref)                                                  | 1.02x slower                                            |

Benchmark hidden because not significant (2): xml_etree_iterparse, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.43 ms: 1.11x slower                                   |
| python_startup_no_site | 6.01 ms                                                | 6.86 ms: 1.14x slower                                   |
| Geometric mean         | (ref)                                                  | 1.12x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.0 ms: 1.09x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 145 us: 3.36x faster                                    |
| generators               | 73.5 ms                                                | 30.4 ms: 2.42x faster                                   |
| asyncio_tcp              | 922 ms                                                 | 505 ms: 1.82x faster                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                  |
| json_dumps               | 12.6 ms                                                | 9.72 ms: 1.29x faster                                   |
| mypy2                    | 420 ms                                                 | 344 ms: 1.22x faster                                    |
| richards_super           | 56.8 ms                                                | 49.5 ms: 1.15x faster                                   |
| coroutines               | 25.5 ms                                                | 22.3 ms: 1.14x faster                                   |
| async_tree_none          | 526 ms                                                 | 468 ms: 1.12x faster                                    |
| async_tree_io            | 1.30 sec                                               | 1.16 sec: 1.12x faster                                  |
| async_tree_memoization   | 627 ms                                                 | 571 ms: 1.10x faster                                    |
| gc_traversal             | 4.02 ms                                                | 3.67 ms: 1.10x faster                                   |
| comprehensions           | 22.4 us                                                | 20.6 us: 1.09x faster                                   |
| chaos                    | 69.2 ms                                                | 63.8 ms: 1.08x faster                                   |
| regex_effbot             | 3.99 ms                                                | 3.73 ms: 1.07x faster                                   |
| json_loads               | 26.5 us                                                | 25.0 us: 1.06x faster                                   |
| coverage                 | 100 ms                                                 | 94.7 ms: 1.06x faster                                   |
| deltablue                | 3.67 ms                                                | 3.48 ms: 1.05x faster                                   |
| hexiom                   | 6.37 ms                                                | 6.06 ms: 1.05x faster                                   |
| sqlglot_parse            | 1.40 ms                                                | 1.33 ms: 1.05x faster                                   |
| nbody                    | 93.1 ms                                                | 88.7 ms: 1.05x faster                                   |
| richards                 | 45.7 ms                                                | 43.8 ms: 1.04x faster                                   |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 711 ms: 1.04x faster                                    |
| go                       | 140 ms                                                 | 135 ms: 1.04x faster                                    |
| unpickle_pure_python     | 228 us                                                 | 220 us: 1.04x faster                                    |
| xml_etree_parse          | 158 ms                                                 | 153 ms: 1.04x faster                                    |
| sqlglot_transpile        | 1.70 ms                                                | 1.65 ms: 1.03x faster                                   |
| nqueens                  | 83.4 ms                                                | 80.8 ms: 1.03x faster                                   |
| json                     | 4.94 ms                                                | 4.80 ms: 1.03x faster                                   |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.01x faster                                  |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.01x faster                                    |
| logging_silent           | 101 ns                                                 | 99.7 ns: 1.01x faster                                   |
| raytrace                 | 297 ms                                                 | 293 ms: 1.01x faster                                    |
| mdp                      | 2.62 sec                                               | 2.59 sec: 1.01x faster                                  |
| bench_thread_pool        | 819 us                                                 | 825 us: 1.01x slower                                    |
| pathlib                  | 18.2 ms                                                | 18.5 ms: 1.01x slower                                   |
| sqlglot_optimize         | 53.1 ms                                                | 54.0 ms: 1.02x slower                                   |
| fannkuch                 | 388 ms                                                 | 396 ms: 1.02x slower                                    |
| float                    | 77.2 ms                                                | 79.0 ms: 1.02x slower                                   |
| pickle_pure_python       | 306 us                                                 | 313 us: 1.02x slower                                    |
| sqlglot_normalize        | 108 ms                                                 | 110 ms: 1.02x slower                                    |
| sqlalchemy_imperative    | 17.9 ms                                                | 18.3 ms: 1.02x slower                                   |
| scimark_lu               | 110 ms                                                 | 112 ms: 1.02x slower                                    |
| deepcopy_memo            | 37.0 us                                                | 37.9 us: 1.02x slower                                   |
| telco                    | 6.58 ms                                                | 6.80 ms: 1.03x slower                                   |
| scimark_sor              | 118 ms                                                 | 122 ms: 1.03x slower                                    |
| pickle_dict              | 31.1 us                                                | 32.2 us: 1.03x slower                                   |
| tornado_http             | 96.3 ms                                                | 99.5 ms: 1.03x slower                                   |
| regex_dna                | 204 ms                                                 | 211 ms: 1.03x slower                                    |
| pprint_pformat           | 1.46 sec                                               | 1.51 sec: 1.04x slower                                  |
| docutils                 | 2.63 sec                                               | 2.72 sec: 1.04x slower                                  |
| deepcopy                 | 342 us                                                 | 355 us: 1.04x slower                                    |
| regex_v8                 | 22.0 ms                                                | 22.9 ms: 1.04x slower                                   |
| spectral_norm            | 100 ms                                                 | 104 ms: 1.04x slower                                    |
| crypto_pyaes             | 74.7 ms                                                | 77.7 ms: 1.04x slower                                   |
| unpickle_list            | 4.91 us                                                | 5.11 us: 1.04x slower                                   |
| 2to3                     | 259 ms                                                 | 270 ms: 1.04x slower                                    |
| sqlalchemy_declarative   | 138 ms                                                 | 144 ms: 1.04x slower                                    |
| regex_compile            | 138 ms                                                 | 144 ms: 1.05x slower                                    |
| logging_simple           | 6.03 us                                                | 6.33 us: 1.05x slower                                   |
| logging_format           | 6.68 us                                                | 7.02 us: 1.05x slower                                   |
| pprint_safe_repr         | 701 ms                                                 | 739 ms: 1.05x slower                                    |
| scimark_monte_carlo      | 68.1 ms                                                | 71.9 ms: 1.06x slower                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.77 ms: 1.06x slower                                   |
| scimark_fft              | 328 ms                                                 | 350 ms: 1.07x slower                                    |
| pidigits                 | 198 ms                                                 | 212 ms: 1.07x slower                                    |
| pickle                   | 10.1 us                                                | 10.9 us: 1.08x slower                                   |
| dulwich_log              | 63.7 ms                                                | 68.9 ms: 1.08x slower                                   |
| mako                     | 10.1 ms                                                | 11.0 ms: 1.09x slower                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.20 us: 1.09x slower                                   |
| sqlite_synth             | 2.52 us                                                | 2.75 us: 1.09x slower                                   |
| xml_etree_process        | 53.9 ms                                                | 59.1 ms: 1.10x slower                                   |
| python_startup           | 8.52 ms                                                | 9.43 ms: 1.11x slower                                   |
| pyflate                  | 418 ms                                                 | 463 ms: 1.11x slower                                    |
| xml_etree_generate       | 76.2 ms                                                | 84.7 ms: 1.11x slower                                   |
| pickle_list              | 4.11 us                                                | 4.69 us: 1.14x slower                                   |
| unpickle                 | 13.7 us                                                | 15.6 us: 1.14x slower                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.86 ms: 1.14x slower                                   |
| unpack_sequence          | 43.1 ns                                                | 50.0 ns: 1.16x slower                                   |
| async_generators         | 368 ms                                                 | 442 ms: 1.20x slower                                    |
| dask                     | 360 ms                                                 | 537 ms: 1.49x slower                                    |
| Geometric mean           | (ref)                                                  | 1.03x faster                                            |

Benchmark hidden because not significant (4): xml_etree_iterparse, bench_mp_pool, create_gc_cycles, tomli_loads
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 89.21% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
