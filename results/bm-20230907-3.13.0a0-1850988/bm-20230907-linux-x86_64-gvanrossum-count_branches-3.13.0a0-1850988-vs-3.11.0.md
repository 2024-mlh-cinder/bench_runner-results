
# Results vs. 3.11.0

- fork: gvanrossum
- ref: count_branches
- machine: linux-x86_64
- commit hash: 1850988
- commit date: 2023-09-07
- overall geometric mean: 1.05x faster
- HPT reliability: 88.75%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| tornado_http   | 96.3 ms                                                | 95.2 ms: 1.01x faster                                               |
| Geometric mean | (ref)                                                  | 1.00x faster                                                        |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                |
| nbody          | 93.1 ms                                                | 88.1 ms: 1.06x faster                                               |
| float          | 77.2 ms                                                | 79.3 ms: 1.03x slower                                               |
| Geometric mean | (ref)                                                  | 1.03x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.85 ms: 1.04x faster                                               |
| regex_compile  | 138 ms                                                 | 134 ms: 1.03x faster                                                |
| regex_dna      | 204 ms                                                 | 224 ms: 1.10x slower                                                |
| regex_v8       | 22.0 ms                                                | 25.5 ms: 1.16x slower                                               |
| Geometric mean | (ref)                                                  | 1.04x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.82 ms: 1.28x faster                                               |
| tomli_loads          | 2.22 sec                                               | 2.02 sec: 1.10x faster                                              |
| pickle_pure_python   | 306 us                                                 | 292 us: 1.05x faster                                                |
| unpickle_pure_python | 228 us                                                 | 218 us: 1.05x faster                                                |
| json_loads           | 26.5 us                                                | 25.3 us: 1.04x faster                                               |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                                |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                |
| unpickle_list        | 4.91 us                                                | 4.86 us: 1.01x faster                                               |
| pickle_dict          | 31.1 us                                                | 32.0 us: 1.03x slower                                               |
| xml_etree_process    | 53.9 ms                                                | 56.2 ms: 1.04x slower                                               |
| unpickle             | 13.7 us                                                | 14.3 us: 1.04x slower                                               |
| pickle               | 10.1 us                                                | 10.6 us: 1.05x slower                                               |
| xml_etree_generate   | 76.2 ms                                                | 81.8 ms: 1.07x slower                                               |
| pickle_list          | 4.11 us                                                | 4.68 us: 1.14x slower                                               |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.57 ms: 1.12x slower                                               |
| python_startup_no_site | 6.01 ms                                                | 7.04 ms: 1.17x slower                                               |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.7 ms: 1.06x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 149 us: 3.26x faster                                                |
| generators               | 73.5 ms                                                | 29.1 ms: 2.52x faster                                               |
| asyncio_tcp              | 922 ms                                                 | 490 ms: 1.88x faster                                                |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                              |
| json_dumps               | 12.6 ms                                                | 9.82 ms: 1.28x faster                                               |
| mypy2                    | 420 ms                                                 | 336 ms: 1.25x faster                                                |
| async_tree_none          | 526 ms                                                 | 440 ms: 1.20x faster                                                |
| chaos                    | 69.2 ms                                                | 58.6 ms: 1.18x faster                                               |
| coverage                 | 100 ms                                                 | 85.3 ms: 1.17x faster                                               |
| coroutines               | 25.5 ms                                                | 22.0 ms: 1.16x faster                                               |
| deltablue                | 3.67 ms                                                | 3.29 ms: 1.12x faster                                               |
| sqlglot_parse            | 1.40 ms                                                | 1.26 ms: 1.11x faster                                               |
| async_tree_memoization   | 627 ms                                                 | 569 ms: 1.10x faster                                                |
| tomli_loads              | 2.22 sec                                               | 2.02 sec: 1.10x faster                                              |
| raytrace                 | 297 ms                                                 | 271 ms: 1.09x faster                                                |
| sqlglot_transpile        | 1.70 ms                                                | 1.56 ms: 1.09x faster                                               |
| comprehensions           | 22.4 us                                                | 20.6 us: 1.09x faster                                               |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.08x faster                                              |
| unpack_sequence          | 43.1 ns                                                | 39.8 ns: 1.08x faster                                               |
| hexiom                   | 6.37 ms                                                | 5.89 ms: 1.08x faster                                               |
| crypto_pyaes             | 74.7 ms                                                | 70.0 ms: 1.07x faster                                               |
| nqueens                  | 83.4 ms                                                | 78.4 ms: 1.06x faster                                               |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                |
| nbody                    | 93.1 ms                                                | 88.1 ms: 1.06x faster                                               |
| richards_super           | 56.8 ms                                                | 53.9 ms: 1.05x faster                                               |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 704 ms: 1.05x faster                                                |
| logging_format           | 6.68 us                                                | 6.37 us: 1.05x faster                                               |
| gc_traversal             | 4.02 ms                                                | 3.83 ms: 1.05x faster                                               |
| pickle_pure_python       | 306 us                                                 | 292 us: 1.05x faster                                                |
| unpickle_pure_python     | 228 us                                                 | 218 us: 1.05x faster                                                |
| json_loads               | 26.5 us                                                | 25.3 us: 1.04x faster                                               |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                |
| sqlglot_normalize        | 108 ms                                                 | 104 ms: 1.04x faster                                                |
| logging_simple           | 6.03 us                                                | 5.80 us: 1.04x faster                                               |
| regex_effbot             | 3.99 ms                                                | 3.85 ms: 1.04x faster                                               |
| regex_compile            | 138 ms                                                 | 134 ms: 1.03x faster                                                |
| scimark_monte_carlo      | 68.1 ms                                                | 66.5 ms: 1.02x faster                                               |
| sqlglot_optimize         | 53.1 ms                                                | 52.2 ms: 1.02x faster                                               |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                |
| fannkuch                 | 388 ms                                                 | 383 ms: 1.01x faster                                                |
| tornado_http             | 96.3 ms                                                | 95.2 ms: 1.01x faster                                               |
| unpickle_list            | 4.91 us                                                | 4.86 us: 1.01x faster                                               |
| bench_thread_pool        | 819 us                                                 | 812 us: 1.01x faster                                                |
| go                       | 140 ms                                                 | 139 ms: 1.01x faster                                                |
| pprint_pformat           | 1.46 sec                                               | 1.47 sec: 1.01x slower                                              |
| pathlib                  | 18.2 ms                                                | 18.4 ms: 1.01x slower                                               |
| deepcopy                 | 342 us                                                 | 346 us: 1.01x slower                                                |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                               |
| deepcopy_memo            | 37.0 us                                                | 37.7 us: 1.02x slower                                               |
| pycparser                | 1.18 sec                                               | 1.20 sec: 1.02x slower                                              |
| scimark_lu               | 110 ms                                                 | 112 ms: 1.02x slower                                                |
| richards                 | 45.7 ms                                                | 46.7 ms: 1.02x slower                                               |
| pprint_safe_repr         | 701 ms                                                 | 719 ms: 1.02x slower                                                |
| float                    | 77.2 ms                                                | 79.3 ms: 1.03x slower                                               |
| scimark_sor              | 118 ms                                                 | 121 ms: 1.03x slower                                                |
| pickle_dict              | 31.1 us                                                | 32.0 us: 1.03x slower                                               |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.63 ms: 1.03x slower                                               |
| dulwich_log              | 63.7 ms                                                | 66.2 ms: 1.04x slower                                               |
| spectral_norm            | 100 ms                                                 | 104 ms: 1.04x slower                                                |
| mdp                      | 2.62 sec                                               | 2.73 sec: 1.04x slower                                              |
| xml_etree_process        | 53.9 ms                                                | 56.2 ms: 1.04x slower                                               |
| unpickle                 | 13.7 us                                                | 14.3 us: 1.04x slower                                               |
| deepcopy_reduce          | 2.94 us                                                | 3.08 us: 1.05x slower                                               |
| pickle                   | 10.1 us                                                | 10.6 us: 1.05x slower                                               |
| mako                     | 10.1 ms                                                | 10.7 ms: 1.06x slower                                               |
| xml_etree_generate       | 76.2 ms                                                | 81.8 ms: 1.07x slower                                               |
| pyflate                  | 418 ms                                                 | 449 ms: 1.07x slower                                                |
| sqlite_synth             | 2.52 us                                                | 2.72 us: 1.08x slower                                               |
| scimark_fft              | 328 ms                                                 | 358 ms: 1.09x slower                                                |
| regex_dna                | 204 ms                                                 | 224 ms: 1.10x slower                                                |
| python_startup           | 8.52 ms                                                | 9.57 ms: 1.12x slower                                               |
| pickle_list              | 4.11 us                                                | 4.68 us: 1.14x slower                                               |
| regex_v8                 | 22.0 ms                                                | 25.5 ms: 1.16x slower                                               |
| python_startup_no_site   | 6.01 ms                                                | 7.04 ms: 1.17x slower                                               |
| async_generators         | 368 ms                                                 | 443 ms: 1.20x slower                                                |
| telco                    | 6.58 ms                                                | 7.94 ms: 1.21x slower                                               |
| dask                     | 360 ms                                                 | 521 ms: 1.45x slower                                                |
| Geometric mean           | (ref)                                                  | 1.05x faster                                                        |

Benchmark hidden because not significant (5): logging_silent, meteor_contest, bench_mp_pool, docutils, json
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 88.75% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
