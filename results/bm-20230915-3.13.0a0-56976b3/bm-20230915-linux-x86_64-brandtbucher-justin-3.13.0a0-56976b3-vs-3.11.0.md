
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 56976b3
- commit date: 2023-09-15
- overall geometric mean: 1.00x slower
- HPT reliability: 99.56%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.70 sec: 1.03x slower                                        |
| tornado_http   | 96.3 ms                                                | 97.6 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                  | 1.02x slower                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 189 ms: 1.05x faster                                          |
| float          | 77.2 ms                                                | 83.4 ms: 1.08x slower                                         |
| nbody          | 93.1 ms                                                | 118 ms: 1.26x slower                                          |
| Geometric mean | (ref)                                                  | 1.09x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.51 ms: 1.14x faster                                         |
| regex_dna      | 204 ms                                                 | 208 ms: 1.02x slower                                          |
| regex_compile  | 138 ms                                                 | 150 ms: 1.08x slower                                          |
| regex_v8       | 22.0 ms                                                | 24.2 ms: 1.10x slower                                         |
| Geometric mean | (ref)                                                  | 1.02x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.97 ms: 1.26x faster                                         |
| json_loads           | 26.5 us                                                | 25.3 us: 1.05x faster                                         |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                          |
| unpickle_list        | 4.91 us                                                | 4.73 us: 1.04x faster                                         |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                          |
| pickle_pure_python   | 306 us                                                 | 309 us: 1.01x slower                                          |
| pickle_dict          | 31.1 us                                                | 31.7 us: 1.02x slower                                         |
| unpickle_pure_python | 228 us                                                 | 233 us: 1.02x slower                                          |
| tomli_loads          | 2.22 sec                                               | 2.34 sec: 1.06x slower                                        |
| pickle               | 10.1 us                                                | 10.7 us: 1.07x slower                                         |
| xml_etree_process    | 53.9 ms                                                | 58.1 ms: 1.08x slower                                         |
| xml_etree_generate   | 76.2 ms                                                | 84.4 ms: 1.11x slower                                         |
| pickle_list          | 4.11 us                                                | 4.70 us: 1.14x slower                                         |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.87 ms: 1.14x slower                                         |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                         |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.3 ms: 1.12x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 159 us: 3.07x faster                                          |
| generators               | 73.5 ms                                                | 28.4 ms: 2.58x faster                                         |
| asyncio_tcp              | 922 ms                                                 | 491 ms: 1.88x faster                                          |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                        |
| json_dumps               | 12.6 ms                                                | 9.97 ms: 1.26x faster                                         |
| coverage                 | 100 ms                                                 | 84.8 ms: 1.18x faster                                         |
| mypy2                    | 420 ms                                                 | 356 ms: 1.18x faster                                          |
| async_tree_none          | 526 ms                                                 | 449 ms: 1.17x faster                                          |
| regex_effbot             | 3.99 ms                                                | 3.51 ms: 1.14x faster                                         |
| coroutines               | 25.5 ms                                                | 22.6 ms: 1.13x faster                                         |
| gc_traversal             | 4.02 ms                                                | 3.57 ms: 1.13x faster                                         |
| async_tree_memoization   | 627 ms                                                 | 579 ms: 1.08x faster                                          |
| sqlglot_parse            | 1.40 ms                                                | 1.30 ms: 1.08x faster                                         |
| async_tree_io            | 1.30 sec                                               | 1.21 sec: 1.07x faster                                        |
| sqlglot_transpile        | 1.70 ms                                                | 1.62 ms: 1.05x faster                                         |
| pidigits                 | 198 ms                                                 | 189 ms: 1.05x faster                                          |
| raytrace                 | 297 ms                                                 | 284 ms: 1.05x faster                                          |
| json_loads               | 26.5 us                                                | 25.3 us: 1.05x faster                                         |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                          |
| deltablue                | 3.67 ms                                                | 3.53 ms: 1.04x faster                                         |
| unpickle_list            | 4.91 us                                                | 4.73 us: 1.04x faster                                         |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 718 ms: 1.03x faster                                          |
| json                     | 4.94 ms                                                | 4.83 ms: 1.02x faster                                         |
| richards_super           | 56.8 ms                                                | 55.9 ms: 1.02x faster                                         |
| scimark_monte_carlo      | 68.1 ms                                                | 67.4 ms: 1.01x faster                                         |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                          |
| pickle_pure_python       | 306 us                                                 | 309 us: 1.01x slower                                          |
| crypto_pyaes             | 74.7 ms                                                | 75.6 ms: 1.01x slower                                         |
| tornado_http             | 96.3 ms                                                | 97.6 ms: 1.01x slower                                         |
| pycparser                | 1.18 sec                                               | 1.20 sec: 1.02x slower                                        |
| sqlglot_optimize         | 53.1 ms                                                | 54.0 ms: 1.02x slower                                         |
| regex_dna                | 204 ms                                                 | 208 ms: 1.02x slower                                          |
| pickle_dict              | 31.1 us                                                | 31.7 us: 1.02x slower                                         |
| create_gc_cycles         | 1.49 ms                                                | 1.52 ms: 1.02x slower                                         |
| unpickle_pure_python     | 228 us                                                 | 233 us: 1.02x slower                                          |
| logging_format           | 6.68 us                                                | 6.86 us: 1.03x slower                                         |
| docutils                 | 2.63 sec                                               | 2.70 sec: 1.03x slower                                        |
| logging_simple           | 6.03 us                                                | 6.22 us: 1.03x slower                                         |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                         |
| bench_thread_pool        | 819 us                                                 | 854 us: 1.04x slower                                          |
| tomli_loads              | 2.22 sec                                               | 2.34 sec: 1.06x slower                                        |
| meteor_contest           | 107 ms                                                 | 113 ms: 1.06x slower                                          |
| scimark_sor              | 118 ms                                                 | 125 ms: 1.06x slower                                          |
| logging_silent           | 101 ns                                                 | 107 ns: 1.06x slower                                          |
| pickle                   | 10.1 us                                                | 10.7 us: 1.07x slower                                         |
| scimark_lu               | 110 ms                                                 | 117 ms: 1.07x slower                                          |
| richards                 | 45.7 ms                                                | 49.3 ms: 1.08x slower                                         |
| xml_etree_process        | 53.9 ms                                                | 58.1 ms: 1.08x slower                                         |
| float                    | 77.2 ms                                                | 83.4 ms: 1.08x slower                                         |
| comprehensions           | 22.4 us                                                | 24.3 us: 1.08x slower                                         |
| mdp                      | 2.62 sec                                               | 2.83 sec: 1.08x slower                                        |
| regex_compile            | 138 ms                                                 | 150 ms: 1.08x slower                                          |
| sqlite_synth             | 2.52 us                                                | 2.74 us: 1.09x slower                                         |
| dulwich_log              | 63.7 ms                                                | 69.5 ms: 1.09x slower                                         |
| regex_v8                 | 22.0 ms                                                | 24.2 ms: 1.10x slower                                         |
| spectral_norm            | 100 ms                                                 | 110 ms: 1.10x slower                                          |
| go                       | 140 ms                                                 | 154 ms: 1.10x slower                                          |
| xml_etree_generate       | 76.2 ms                                                | 84.4 ms: 1.11x slower                                         |
| deepcopy                 | 342 us                                                 | 382 us: 1.12x slower                                          |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.02 ms: 1.12x slower                                         |
| mako                     | 10.1 ms                                                | 11.3 ms: 1.12x slower                                         |
| deepcopy_reduce          | 2.94 us                                                | 3.30 us: 1.12x slower                                         |
| pprint_pformat           | 1.46 sec                                               | 1.64 sec: 1.12x slower                                        |
| pprint_safe_repr         | 701 ms                                                 | 797 ms: 1.14x slower                                          |
| python_startup_no_site   | 6.01 ms                                                | 6.87 ms: 1.14x slower                                         |
| pickle_list              | 4.11 us                                                | 4.70 us: 1.14x slower                                         |
| chaos                    | 69.2 ms                                                | 80.0 ms: 1.16x slower                                         |
| scimark_fft              | 328 ms                                                 | 381 ms: 1.16x slower                                          |
| fannkuch                 | 388 ms                                                 | 455 ms: 1.17x slower                                          |
| hexiom                   | 6.37 ms                                                | 7.53 ms: 1.18x slower                                         |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                         |
| pyflate                  | 418 ms                                                 | 500 ms: 1.20x slower                                          |
| deepcopy_memo            | 37.0 us                                                | 45.1 us: 1.22x slower                                         |
| telco                    | 6.58 ms                                                | 8.08 ms: 1.23x slower                                         |
| nqueens                  | 83.4 ms                                                | 104 ms: 1.25x slower                                          |
| nbody                    | 93.1 ms                                                | 118 ms: 1.26x slower                                          |
| async_generators         | 368 ms                                                 | 468 ms: 1.27x slower                                          |
| unpack_sequence          | 43.1 ns                                                | 54.7 ns: 1.27x slower                                         |
| dask                     | 360 ms                                                 | 538 ms: 1.49x slower                                          |
| Geometric mean           | (ref)                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (3): bench_mp_pool, sqlglot_normalize, unpickle
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.56% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
