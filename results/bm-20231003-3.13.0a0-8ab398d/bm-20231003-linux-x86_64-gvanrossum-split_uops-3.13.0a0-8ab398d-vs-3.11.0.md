
# Results vs. 3.11.0

- fork: gvanrossum
- ref: split_uops
- machine: linux-x86_64
- commit hash: 8ab398d
- commit date: 2023-10-03
- overall geometric mean: 1.06x faster
- HPT reliability: 99.79%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.58 sec: 1.02x faster                                          |
| tornado_http   | 96.3 ms                                                | 95.7 ms: 1.01x faster                                           |
| Geometric mean | (ref)                                                  | 1.01x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.06x faster                                            |
| nbody          | 93.1 ms                                                | 91.8 ms: 1.01x faster                                           |
| float          | 77.2 ms                                                | 79.3 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                  | 1.01x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.39 ms: 1.18x faster                                           |
| regex_compile  | 138 ms                                                 | 134 ms: 1.03x faster                                            |
| regex_dna      | 204 ms                                                 | 205 ms: 1.00x slower                                            |
| regex_v8       | 22.0 ms                                                | 23.9 ms: 1.09x slower                                           |
| Geometric mean | (ref)                                                  | 1.03x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.75 ms: 1.29x faster                                           |
| unpickle_pure_python | 228 us                                                 | 214 us: 1.06x faster                                            |
| xml_etree_parse      | 158 ms                                                 | 153 ms: 1.04x faster                                            |
| tomli_loads          | 2.22 sec                                               | 2.15 sec: 1.03x faster                                          |
| pickle_pure_python   | 306 us                                                 | 297 us: 1.03x faster                                            |
| json_loads           | 26.5 us                                                | 25.9 us: 1.02x faster                                           |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                            |
| unpickle_list        | 4.91 us                                                | 4.81 us: 1.02x faster                                           |
| pickle               | 10.1 us                                                | 10.4 us: 1.03x slower                                           |
| pickle_dict          | 31.1 us                                                | 32.2 us: 1.04x slower                                           |
| unpickle             | 13.7 us                                                | 14.6 us: 1.07x slower                                           |
| xml_etree_process    | 53.9 ms                                                | 58.0 ms: 1.08x slower                                           |
| xml_etree_generate   | 76.2 ms                                                | 83.2 ms: 1.09x slower                                           |
| pickle_list          | 4.11 us                                                | 4.68 us: 1.14x slower                                           |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.86 ms: 1.14x slower                                           |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                           |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.4 ms: 1.03x slower                                           |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 142 us: 3.41x faster                                            |
| generators               | 73.5 ms                                                | 28.5 ms: 2.58x faster                                           |
| asyncio_tcp              | 922 ms                                                 | 500 ms: 1.84x faster                                            |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.75x faster                                          |
| json_dumps               | 12.6 ms                                                | 9.75 ms: 1.29x faster                                           |
| mypy2                    | 420 ms                                                 | 336 ms: 1.25x faster                                            |
| async_tree_none          | 526 ms                                                 | 439 ms: 1.20x faster                                            |
| regex_effbot             | 3.99 ms                                                | 3.39 ms: 1.18x faster                                           |
| coverage                 | 100 ms                                                 | 86.2 ms: 1.16x faster                                           |
| chaos                    | 69.2 ms                                                | 60.0 ms: 1.15x faster                                           |
| deltablue                | 3.67 ms                                                | 3.25 ms: 1.13x faster                                           |
| coroutines               | 25.5 ms                                                | 22.7 ms: 1.12x faster                                           |
| async_tree_memoization   | 627 ms                                                 | 562 ms: 1.12x faster                                            |
| sqlglot_parse            | 1.40 ms                                                | 1.26 ms: 1.11x faster                                           |
| raytrace                 | 297 ms                                                 | 267 ms: 1.11x faster                                            |
| comprehensions           | 22.4 us                                                | 20.5 us: 1.10x faster                                           |
| sqlglot_transpile        | 1.70 ms                                                | 1.56 ms: 1.09x faster                                           |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                          |
| gc_traversal             | 4.02 ms                                                | 3.70 ms: 1.09x faster                                           |
| richards_super           | 56.8 ms                                                | 52.5 ms: 1.08x faster                                           |
| crypto_pyaes             | 74.7 ms                                                | 69.2 ms: 1.08x faster                                           |
| hexiom                   | 6.37 ms                                                | 5.92 ms: 1.08x faster                                           |
| nqueens                  | 83.4 ms                                                | 77.9 ms: 1.07x faster                                           |
| unpickle_pure_python     | 228 us                                                 | 214 us: 1.06x faster                                            |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 699 ms: 1.06x faster                                            |
| pidigits                 | 198 ms                                                 | 188 ms: 1.06x faster                                            |
| sqlglot_normalize        | 108 ms                                                 | 103 ms: 1.04x faster                                            |
| logging_simple           | 6.03 us                                                | 5.81 us: 1.04x faster                                           |
| mdp                      | 2.62 sec                                               | 2.52 sec: 1.04x faster                                          |
| xml_etree_parse          | 158 ms                                                 | 153 ms: 1.04x faster                                            |
| tomli_loads              | 2.22 sec                                               | 2.15 sec: 1.03x faster                                          |
| logging_format           | 6.68 us                                                | 6.48 us: 1.03x faster                                           |
| scimark_monte_carlo      | 68.1 ms                                                | 66.1 ms: 1.03x faster                                           |
| regex_compile            | 138 ms                                                 | 134 ms: 1.03x faster                                            |
| unpack_sequence          | 43.1 ns                                                | 41.9 ns: 1.03x faster                                           |
| pickle_pure_python       | 306 us                                                 | 297 us: 1.03x faster                                            |
| json_loads               | 26.5 us                                                | 25.9 us: 1.02x faster                                           |
| pycparser                | 1.18 sec                                               | 1.15 sec: 1.02x faster                                          |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                            |
| fannkuch                 | 388 ms                                                 | 380 ms: 1.02x faster                                            |
| unpickle_list            | 4.91 us                                                | 4.81 us: 1.02x faster                                           |
| sqlglot_optimize         | 53.1 ms                                                | 52.1 ms: 1.02x faster                                           |
| docutils                 | 2.63 sec                                               | 2.58 sec: 1.02x faster                                          |
| logging_silent           | 101 ns                                                 | 99.5 ns: 1.02x faster                                           |
| nbody                    | 93.1 ms                                                | 91.8 ms: 1.01x faster                                           |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.01x faster                                            |
| json                     | 4.94 ms                                                | 4.88 ms: 1.01x faster                                           |
| go                       | 140 ms                                                 | 138 ms: 1.01x faster                                            |
| bench_thread_pool        | 819 us                                                 | 810 us: 1.01x faster                                            |
| deepcopy_memo            | 37.0 us                                                | 36.8 us: 1.01x faster                                           |
| tornado_http             | 96.3 ms                                                | 95.7 ms: 1.01x faster                                           |
| regex_dna                | 204 ms                                                 | 205 ms: 1.00x slower                                            |
| deepcopy                 | 342 us                                                 | 344 us: 1.00x slower                                            |
| pprint_safe_repr         | 701 ms                                                 | 711 ms: 1.01x slower                                            |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                           |
| pathlib                  | 18.2 ms                                                | 18.7 ms: 1.03x slower                                           |
| float                    | 77.2 ms                                                | 79.3 ms: 1.03x slower                                           |
| richards                 | 45.7 ms                                                | 47.1 ms: 1.03x slower                                           |
| pickle                   | 10.1 us                                                | 10.4 us: 1.03x slower                                           |
| deepcopy_reduce          | 2.94 us                                                | 3.03 us: 1.03x slower                                           |
| mako                     | 10.1 ms                                                | 10.4 ms: 1.03x slower                                           |
| pickle_dict              | 31.1 us                                                | 32.2 us: 1.04x slower                                           |
| dulwich_log              | 63.7 ms                                                | 66.3 ms: 1.04x slower                                           |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.74 ms: 1.05x slower                                           |
| unpickle                 | 13.7 us                                                | 14.6 us: 1.07x slower                                           |
| spectral_norm            | 100 ms                                                 | 107 ms: 1.07x slower                                            |
| xml_etree_process        | 53.9 ms                                                | 58.0 ms: 1.08x slower                                           |
| sqlite_synth             | 2.52 us                                                | 2.73 us: 1.08x slower                                           |
| pyflate                  | 418 ms                                                 | 454 ms: 1.09x slower                                            |
| regex_v8                 | 22.0 ms                                                | 23.9 ms: 1.09x slower                                           |
| xml_etree_generate       | 76.2 ms                                                | 83.2 ms: 1.09x slower                                           |
| scimark_fft              | 328 ms                                                 | 359 ms: 1.09x slower                                            |
| pickle_list              | 4.11 us                                                | 4.68 us: 1.14x slower                                           |
| python_startup_no_site   | 6.01 ms                                                | 6.86 ms: 1.14x slower                                           |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                           |
| async_generators         | 368 ms                                                 | 445 ms: 1.21x slower                                            |
| telco                    | 6.58 ms                                                | 8.05 ms: 1.22x slower                                           |
| Geometric mean           | (ref)                                                  | 1.06x faster                                                    |

Benchmark hidden because not significant (4): pprint_pformat, scimark_sor, bench_mp_pool, scimark_lu
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.79% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
