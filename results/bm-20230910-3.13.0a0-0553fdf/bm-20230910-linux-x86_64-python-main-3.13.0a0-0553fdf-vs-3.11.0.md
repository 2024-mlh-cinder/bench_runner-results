
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.05x faster
- HPT reliability: 97.32%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.60 sec: 1.01x faster                                |
| tornado_http   | 96.3 ms                                                | 94.9 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                  |
| nbody          | 93.1 ms                                                | 90.6 ms: 1.03x faster                                 |
| float          | 77.2 ms                                                | 79.8 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.50 ms: 1.14x faster                                 |
| regex_compile  | 138 ms                                                 | 134 ms: 1.03x faster                                  |
| regex_dna      | 204 ms                                                 | 205 ms: 1.01x slower                                  |
| regex_v8       | 22.0 ms                                                | 23.4 ms: 1.06x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.99 ms: 1.26x faster                                 |
| tomli_loads          | 2.22 sec                                               | 2.02 sec: 1.10x faster                                |
| unpickle_pure_python | 228 us                                                 | 212 us: 1.08x faster                                  |
| xml_etree_parse      | 158 ms                                                 | 151 ms: 1.05x faster                                  |
| json_loads           | 26.5 us                                                | 25.3 us: 1.05x faster                                 |
| pickle_pure_python   | 306 us                                                 | 295 us: 1.04x faster                                  |
| pickle_dict          | 31.1 us                                                | 30.0 us: 1.04x faster                                 |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| unpickle_list        | 4.91 us                                                | 4.86 us: 1.01x faster                                 |
| pickle               | 10.1 us                                                | 10.3 us: 1.02x slower                                 |
| unpickle             | 13.7 us                                                | 14.1 us: 1.03x slower                                 |
| xml_etree_process    | 53.9 ms                                                | 56.6 ms: 1.05x slower                                 |
| xml_etree_generate   | 76.2 ms                                                | 81.8 ms: 1.07x slower                                 |
| pickle_list          | 4.11 us                                                | 4.67 us: 1.14x slower                                 |
| Geometric mean       | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.81 ms: 1.13x slower                                 |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.17x slower                                 |
| Geometric mean         | (ref)                                                  | 1.15x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.8 ms: 1.07x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 140 us: 3.47x faster                                  |
| generators               | 73.5 ms                                                | 29.3 ms: 2.51x faster                                 |
| asyncio_tcp              | 922 ms                                                 | 488 ms: 1.89x faster                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                |
| json_dumps               | 12.6 ms                                                | 9.99 ms: 1.26x faster                                 |
| mypy2                    | 420 ms                                                 | 337 ms: 1.25x faster                                  |
| async_tree_none          | 526 ms                                                 | 436 ms: 1.21x faster                                  |
| coroutines               | 25.5 ms                                                | 21.5 ms: 1.19x faster                                 |
| chaos                    | 69.2 ms                                                | 59.6 ms: 1.16x faster                                 |
| coverage                 | 100 ms                                                 | 86.8 ms: 1.15x faster                                 |
| regex_effbot             | 3.99 ms                                                | 3.50 ms: 1.14x faster                                 |
| deltablue                | 3.67 ms                                                | 3.24 ms: 1.13x faster                                 |
| async_tree_memoization   | 627 ms                                                 | 560 ms: 1.12x faster                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.25 ms: 1.12x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.02 sec: 1.10x faster                                |
| async_tree_io            | 1.30 sec                                               | 1.18 sec: 1.10x faster                                |
| crypto_pyaes             | 74.7 ms                                                | 68.2 ms: 1.10x faster                                 |
| sqlglot_transpile        | 1.70 ms                                                | 1.56 ms: 1.09x faster                                 |
| raytrace                 | 297 ms                                                 | 273 ms: 1.09x faster                                  |
| comprehensions           | 22.4 us                                                | 20.7 us: 1.09x faster                                 |
| unpickle_pure_python     | 228 us                                                 | 212 us: 1.08x faster                                  |
| hexiom                   | 6.37 ms                                                | 5.92 ms: 1.08x faster                                 |
| nqueens                  | 83.4 ms                                                | 78.0 ms: 1.07x faster                                 |
| richards_super           | 56.8 ms                                                | 53.6 ms: 1.06x faster                                 |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                  |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 702 ms: 1.05x faster                                  |
| xml_etree_parse          | 158 ms                                                 | 151 ms: 1.05x faster                                  |
| json_loads               | 26.5 us                                                | 25.3 us: 1.05x faster                                 |
| pickle_pure_python       | 306 us                                                 | 295 us: 1.04x faster                                  |
| fannkuch                 | 388 ms                                                 | 374 ms: 1.04x faster                                  |
| sqlglot_normalize        | 108 ms                                                 | 104 ms: 1.04x faster                                  |
| pickle_dict              | 31.1 us                                                | 30.0 us: 1.04x faster                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 65.8 ms: 1.03x faster                                 |
| gc_traversal             | 4.02 ms                                                | 3.90 ms: 1.03x faster                                 |
| regex_compile            | 138 ms                                                 | 134 ms: 1.03x faster                                  |
| nbody                    | 93.1 ms                                                | 90.6 ms: 1.03x faster                                 |
| json                     | 4.94 ms                                                | 4.81 ms: 1.03x faster                                 |
| logging_format           | 6.68 us                                                | 6.53 us: 1.02x faster                                 |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.02x faster                                  |
| sqlglot_optimize         | 53.1 ms                                                | 52.2 ms: 1.02x faster                                 |
| bench_thread_pool        | 819 us                                                 | 807 us: 1.01x faster                                  |
| mdp                      | 2.62 sec                                               | 2.58 sec: 1.01x faster                                |
| tornado_http             | 96.3 ms                                                | 94.9 ms: 1.01x faster                                 |
| go                       | 140 ms                                                 | 138 ms: 1.01x faster                                  |
| docutils                 | 2.63 sec                                               | 2.60 sec: 1.01x faster                                |
| unpickle_list            | 4.91 us                                                | 4.86 us: 1.01x faster                                 |
| logging_simple           | 6.03 us                                                | 5.98 us: 1.01x faster                                 |
| regex_dna                | 204 ms                                                 | 205 ms: 1.01x slower                                  |
| deepcopy                 | 342 us                                                 | 345 us: 1.01x slower                                  |
| scimark_sor              | 118 ms                                                 | 120 ms: 1.01x slower                                  |
| logging_silent           | 101 ns                                                 | 103 ns: 1.02x slower                                  |
| pprint_pformat           | 1.46 sec                                               | 1.48 sec: 1.02x slower                                |
| pickle                   | 10.1 us                                                | 10.3 us: 1.02x slower                                 |
| richards                 | 45.7 ms                                                | 46.6 ms: 1.02x slower                                 |
| scimark_lu               | 110 ms                                                 | 113 ms: 1.03x slower                                  |
| unpickle                 | 13.7 us                                                | 14.1 us: 1.03x slower                                 |
| pathlib                  | 18.2 ms                                                | 18.8 ms: 1.03x slower                                 |
| pprint_safe_repr         | 701 ms                                                 | 722 ms: 1.03x slower                                  |
| create_gc_cycles         | 1.49 ms                                                | 1.54 ms: 1.03x slower                                 |
| float                    | 77.2 ms                                                | 79.8 ms: 1.03x slower                                 |
| spectral_norm            | 100 ms                                                 | 104 ms: 1.04x slower                                  |
| unpack_sequence          | 43.1 ns                                                | 44.9 ns: 1.04x slower                                 |
| dulwich_log              | 63.7 ms                                                | 66.4 ms: 1.04x slower                                 |
| xml_etree_process        | 53.9 ms                                                | 56.6 ms: 1.05x slower                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.11 us: 1.06x slower                                 |
| regex_v8                 | 22.0 ms                                                | 23.4 ms: 1.06x slower                                 |
| pyflate                  | 418 ms                                                 | 446 ms: 1.07x slower                                  |
| mako                     | 10.1 ms                                                | 10.8 ms: 1.07x slower                                 |
| xml_etree_generate       | 76.2 ms                                                | 81.8 ms: 1.07x slower                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.86 ms: 1.08x slower                                 |
| scimark_fft              | 328 ms                                                 | 358 ms: 1.09x slower                                  |
| sqlite_synth             | 2.52 us                                                | 2.75 us: 1.09x slower                                 |
| python_startup_no_site   | 6.01 ms                                                | 6.81 ms: 1.13x slower                                 |
| pickle_list              | 4.11 us                                                | 4.67 us: 1.14x slower                                 |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.17x slower                                 |
| async_generators         | 368 ms                                                 | 439 ms: 1.19x slower                                  |
| telco                    | 6.58 ms                                                | 7.92 ms: 1.20x slower                                 |
| dask                     | 360 ms                                                 | 522 ms: 1.45x slower                                  |
| Geometric mean           | (ref)                                                  | 1.05x faster                                          |

Benchmark hidden because not significant (3): pycparser, bench_mp_pool, deepcopy_memo
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.32% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
