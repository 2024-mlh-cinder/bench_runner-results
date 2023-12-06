
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_small
- machine: linux-x86_64
- commit hash: 1710e5b
- commit date: 2023-09-17
- overall geometric mean: 1.04x faster
- HPT reliability: 60.48%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.64 sec: 1.01x slower                                              |
| Geometric mean | (ref)                                                  | 1.00x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 93.1 ms                                                | 83.7 ms: 1.11x faster                                               |
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                |
| float          | 77.2 ms                                                | 81.5 ms: 1.05x slower                                               |
| Geometric mean | (ref)                                                  | 1.04x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.34 ms: 1.20x faster                                               |
| regex_v8       | 22.0 ms                                                | 23.3 ms: 1.06x slower                                               |
| Geometric mean | (ref)                                                  | 1.03x faster                                                        |

Benchmark hidden because not significant (2): regex_compile, regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.91 ms: 1.27x faster                                               |
| tomli_loads          | 2.22 sec                                               | 1.98 sec: 1.12x faster                                              |
| json_loads           | 26.5 us                                                | 25.1 us: 1.05x faster                                               |
| unpickle_pure_python | 228 us                                                 | 221 us: 1.03x faster                                                |
| xml_etree_parse      | 158 ms                                                 | 154 ms: 1.03x faster                                                |
| pickle_pure_python   | 306 us                                                 | 298 us: 1.02x faster                                                |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                |
| pickle_dict          | 31.1 us                                                | 31.6 us: 1.01x slower                                               |
| pickle               | 10.1 us                                                | 10.6 us: 1.05x slower                                               |
| xml_etree_process    | 53.9 ms                                                | 57.6 ms: 1.07x slower                                               |
| unpickle             | 13.7 us                                                | 14.8 us: 1.08x slower                                               |
| pickle_list          | 4.11 us                                                | 4.49 us: 1.09x slower                                               |
| xml_etree_generate   | 76.2 ms                                                | 83.4 ms: 1.09x slower                                               |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                        |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.88 ms: 1.14x slower                                               |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                               |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.8 ms: 1.07x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 146 us: 3.33x faster                                                |
| generators               | 73.5 ms                                                | 29.5 ms: 2.49x faster                                               |
| asyncio_tcp              | 922 ms                                                 | 501 ms: 1.84x faster                                                |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.81 sec: 1.73x faster                                              |
| json_dumps               | 12.6 ms                                                | 9.91 ms: 1.27x faster                                               |
| mypy2                    | 420 ms                                                 | 345 ms: 1.22x faster                                                |
| regex_effbot             | 3.99 ms                                                | 3.34 ms: 1.20x faster                                               |
| async_tree_none          | 526 ms                                                 | 443 ms: 1.19x faster                                                |
| coverage                 | 100 ms                                                 | 86.4 ms: 1.16x faster                                               |
| coroutines               | 25.5 ms                                                | 22.2 ms: 1.15x faster                                               |
| chaos                    | 69.2 ms                                                | 61.7 ms: 1.12x faster                                               |
| tomli_loads              | 2.22 sec                                               | 1.98 sec: 1.12x faster                                              |
| nbody                    | 93.1 ms                                                | 83.7 ms: 1.11x faster                                               |
| async_tree_memoization   | 627 ms                                                 | 565 ms: 1.11x faster                                                |
| raytrace                 | 297 ms                                                 | 268 ms: 1.11x faster                                                |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.09x faster                                               |
| deltablue                | 3.67 ms                                                | 3.36 ms: 1.09x faster                                               |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                              |
| sqlglot_transpile        | 1.70 ms                                                | 1.59 ms: 1.07x faster                                               |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                |
| json_loads               | 26.5 us                                                | 25.1 us: 1.05x faster                                               |
| richards_super           | 56.8 ms                                                | 54.0 ms: 1.05x faster                                               |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 712 ms: 1.04x faster                                                |
| logging_format           | 6.68 us                                                | 6.45 us: 1.04x faster                                               |
| json                     | 4.94 ms                                                | 4.77 ms: 1.04x faster                                               |
| crypto_pyaes             | 74.7 ms                                                | 72.4 ms: 1.03x faster                                               |
| unpickle_pure_python     | 228 us                                                 | 221 us: 1.03x faster                                                |
| xml_etree_parse          | 158 ms                                                 | 154 ms: 1.03x faster                                                |
| pickle_pure_python       | 306 us                                                 | 298 us: 1.02x faster                                                |
| scimark_monte_carlo      | 68.1 ms                                                | 66.6 ms: 1.02x faster                                               |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                              |
| logging_simple           | 6.03 us                                                | 5.92 us: 1.02x faster                                               |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                                |
| unpack_sequence          | 43.1 ns                                                | 42.4 ns: 1.02x faster                                               |
| mdp                      | 2.62 sec                                               | 2.58 sec: 1.02x faster                                              |
| comprehensions           | 22.4 us                                                | 22.2 us: 1.01x faster                                               |
| gc_traversal             | 4.02 ms                                                | 3.98 ms: 1.01x faster                                               |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                |
| docutils                 | 2.63 sec                                               | 2.64 sec: 1.01x slower                                              |
| scimark_fft              | 328 ms                                                 | 331 ms: 1.01x slower                                                |
| pickle_dict              | 31.1 us                                                | 31.6 us: 1.01x slower                                               |
| scimark_sor              | 118 ms                                                 | 120 ms: 1.02x slower                                                |
| bench_thread_pool        | 819 us                                                 | 835 us: 1.02x slower                                                |
| deepcopy_memo            | 37.0 us                                                | 37.8 us: 1.02x slower                                               |
| logging_silent           | 101 ns                                                 | 103 ns: 1.02x slower                                                |
| hexiom                   | 6.37 ms                                                | 6.53 ms: 1.02x slower                                               |
| pprint_pformat           | 1.46 sec                                               | 1.49 sec: 1.02x slower                                              |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.61 ms: 1.02x slower                                               |
| richards                 | 45.7 ms                                                | 46.9 ms: 1.03x slower                                               |
| scimark_lu               | 110 ms                                                 | 113 ms: 1.03x slower                                                |
| create_gc_cycles         | 1.49 ms                                                | 1.53 ms: 1.03x slower                                               |
| nqueens                  | 83.4 ms                                                | 85.7 ms: 1.03x slower                                               |
| pathlib                  | 18.2 ms                                                | 18.8 ms: 1.03x slower                                               |
| deepcopy                 | 342 us                                                 | 352 us: 1.03x slower                                                |
| pprint_safe_repr         | 701 ms                                                 | 725 ms: 1.03x slower                                                |
| go                       | 140 ms                                                 | 145 ms: 1.03x slower                                                |
| fannkuch                 | 388 ms                                                 | 406 ms: 1.05x slower                                                |
| pickle                   | 10.1 us                                                | 10.6 us: 1.05x slower                                               |
| float                    | 77.2 ms                                                | 81.5 ms: 1.05x slower                                               |
| regex_v8                 | 22.0 ms                                                | 23.3 ms: 1.06x slower                                               |
| dulwich_log              | 63.7 ms                                                | 67.4 ms: 1.06x slower                                               |
| xml_etree_process        | 53.9 ms                                                | 57.6 ms: 1.07x slower                                               |
| deepcopy_reduce          | 2.94 us                                                | 3.15 us: 1.07x slower                                               |
| mako                     | 10.1 ms                                                | 10.8 ms: 1.07x slower                                               |
| unpickle                 | 13.7 us                                                | 14.8 us: 1.08x slower                                               |
| spectral_norm            | 100 ms                                                 | 108 ms: 1.08x slower                                                |
| pickle_list              | 4.11 us                                                | 4.49 us: 1.09x slower                                               |
| sqlite_synth             | 2.52 us                                                | 2.76 us: 1.09x slower                                               |
| xml_etree_generate       | 76.2 ms                                                | 83.4 ms: 1.09x slower                                               |
| pyflate                  | 418 ms                                                 | 459 ms: 1.10x slower                                                |
| python_startup_no_site   | 6.01 ms                                                | 6.88 ms: 1.14x slower                                               |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                               |
| telco                    | 6.58 ms                                                | 8.05 ms: 1.22x slower                                               |
| async_generators         | 368 ms                                                 | 459 ms: 1.25x slower                                                |
| dask                     | 360 ms                                                 | 532 ms: 1.48x slower                                                |
| Geometric mean           | (ref)                                                  | 1.04x faster                                                        |

Benchmark hidden because not significant (7): tornado_http, unpickle_list, bench_mp_pool, regex_compile, regex_dna, sqlglot_optimize, meteor_contest
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 60.48% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
