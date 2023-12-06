
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.02x faster
- HPT reliability: 79.17%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.64 sec: 1.01x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                   |
| nbody          | 93.1 ms                                                | 93.7 ms: 1.01x slower                                  |
| float          | 77.2 ms                                                | 82.4 ms: 1.07x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.60 ms: 1.11x faster                                  |
| regex_compile  | 138 ms                                                 | 137 ms: 1.01x faster                                   |
| regex_dna      | 204 ms                                                 | 220 ms: 1.08x slower                                   |
| regex_v8       | 22.0 ms                                                | 25.7 ms: 1.16x slower                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.5 ms: 1.20x faster                                  |
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                 |
| unpickle_pure_python | 228 us                                                 | 224 us: 1.02x faster                                   |
| pickle_pure_python   | 306 us                                                 | 304 us: 1.01x faster                                   |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                   |
| unpickle_list        | 4.91 us                                                | 5.13 us: 1.04x slower                                  |
| json_loads           | 26.5 us                                                | 27.9 us: 1.05x slower                                  |
| xml_etree_process    | 53.9 ms                                                | 59.2 ms: 1.10x slower                                  |
| pickle_dict          | 31.1 us                                                | 34.7 us: 1.11x slower                                  |
| xml_etree_generate   | 76.2 ms                                                | 86.4 ms: 1.13x slower                                  |
| pickle               | 10.1 us                                                | 11.5 us: 1.14x slower                                  |
| unpickle             | 13.7 us                                                | 15.7 us: 1.15x slower                                  |
| pickle_list          | 4.11 us                                                | 5.11 us: 1.24x slower                                  |
| Geometric mean       | (ref)                                                  | 1.05x slower                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.85 ms: 1.14x slower                                  |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                  |
| Geometric mean         | (ref)                                                  | 1.16x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.1 ms                                                | 12.0 ms: 1.19x slower                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 149 us: 3.26x faster                                   |
| generators               | 73.5 ms                                                | 29.4 ms: 2.50x faster                                  |
| asyncio_tcp              | 922 ms                                                 | 473 ms: 1.95x faster                                   |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.77 sec: 1.77x faster                                 |
| mypy2                    | 420 ms                                                 | 342 ms: 1.23x faster                                   |
| async_tree_none          | 526 ms                                                 | 436 ms: 1.21x faster                                   |
| json_dumps               | 12.6 ms                                                | 10.5 ms: 1.20x faster                                  |
| chaos                    | 69.2 ms                                                | 61.8 ms: 1.12x faster                                  |
| async_tree_memoization   | 627 ms                                                 | 561 ms: 1.12x faster                                   |
| regex_effbot             | 3.99 ms                                                | 3.60 ms: 1.11x faster                                  |
| deltablue                | 3.67 ms                                                | 3.31 ms: 1.11x faster                                  |
| coverage                 | 100 ms                                                 | 90.5 ms: 1.11x faster                                  |
| async_tree_io            | 1.30 sec                                               | 1.18 sec: 1.10x faster                                 |
| coroutines               | 25.5 ms                                                | 23.2 ms: 1.10x faster                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.09x faster                                  |
| gc_traversal             | 4.02 ms                                                | 3.69 ms: 1.09x faster                                  |
| raytrace                 | 297 ms                                                 | 278 ms: 1.07x faster                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.60 ms: 1.06x faster                                  |
| richards_super           | 56.8 ms                                                | 53.7 ms: 1.06x faster                                  |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                   |
| comprehensions           | 22.4 us                                                | 21.4 us: 1.05x faster                                  |
| nqueens                  | 83.4 ms                                                | 79.9 ms: 1.04x faster                                  |
| logging_format           | 6.68 us                                                | 6.44 us: 1.04x faster                                  |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 713 ms: 1.04x faster                                   |
| logging_simple           | 6.03 us                                                | 5.91 us: 1.02x faster                                  |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                 |
| unpickle_pure_python     | 228 us                                                 | 224 us: 1.02x faster                                   |
| hexiom                   | 6.37 ms                                                | 6.26 ms: 1.02x faster                                  |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                   |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.01x faster                                 |
| bench_thread_pool        | 819 us                                                 | 808 us: 1.01x faster                                   |
| mdp                      | 2.62 sec                                               | 2.60 sec: 1.01x faster                                 |
| regex_compile            | 138 ms                                                 | 137 ms: 1.01x faster                                   |
| pickle_pure_python       | 306 us                                                 | 304 us: 1.01x faster                                   |
| docutils                 | 2.63 sec                                               | 2.64 sec: 1.01x slower                                 |
| nbody                    | 93.1 ms                                                | 93.7 ms: 1.01x slower                                  |
| crypto_pyaes             | 74.7 ms                                                | 75.3 ms: 1.01x slower                                  |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                   |
| sqlglot_optimize         | 53.1 ms                                                | 53.8 ms: 1.01x slower                                  |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.01x slower                                  |
| go                       | 140 ms                                                 | 143 ms: 1.02x slower                                   |
| scimark_monte_carlo      | 68.1 ms                                                | 69.8 ms: 1.03x slower                                  |
| json                     | 4.94 ms                                                | 5.10 ms: 1.03x slower                                  |
| deepcopy                 | 342 us                                                 | 354 us: 1.03x slower                                   |
| pprint_pformat           | 1.46 sec                                               | 1.51 sec: 1.04x slower                                 |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                  |
| unpickle_list            | 4.91 us                                                | 5.13 us: 1.04x slower                                  |
| deepcopy_memo            | 37.0 us                                                | 38.9 us: 1.05x slower                                  |
| json_loads               | 26.5 us                                                | 27.9 us: 1.05x slower                                  |
| dulwich_log              | 63.7 ms                                                | 67.1 ms: 1.05x slower                                  |
| unpack_sequence          | 43.1 ns                                                | 45.5 ns: 1.06x slower                                  |
| richards                 | 45.7 ms                                                | 48.3 ms: 1.06x slower                                  |
| pprint_safe_repr         | 701 ms                                                 | 743 ms: 1.06x slower                                   |
| scimark_lu               | 110 ms                                                 | 117 ms: 1.06x slower                                   |
| float                    | 77.2 ms                                                | 82.4 ms: 1.07x slower                                  |
| deepcopy_reduce          | 2.94 us                                                | 3.15 us: 1.07x slower                                  |
| fannkuch                 | 388 ms                                                 | 417 ms: 1.07x slower                                   |
| scimark_sor              | 118 ms                                                 | 127 ms: 1.08x slower                                   |
| regex_dna                | 204 ms                                                 | 220 ms: 1.08x slower                                   |
| logging_silent           | 101 ns                                                 | 110 ns: 1.08x slower                                   |
| xml_etree_process        | 53.9 ms                                                | 59.2 ms: 1.10x slower                                  |
| pickle_dict              | 31.1 us                                                | 34.7 us: 1.11x slower                                  |
| sqlite_synth             | 2.52 us                                                | 2.82 us: 1.12x slower                                  |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.05 ms: 1.12x slower                                  |
| xml_etree_generate       | 76.2 ms                                                | 86.4 ms: 1.13x slower                                  |
| python_startup_no_site   | 6.01 ms                                                | 6.85 ms: 1.14x slower                                  |
| pickle                   | 10.1 us                                                | 11.5 us: 1.14x slower                                  |
| scimark_fft              | 328 ms                                                 | 377 ms: 1.15x slower                                   |
| pyflate                  | 418 ms                                                 | 481 ms: 1.15x slower                                   |
| unpickle                 | 13.7 us                                                | 15.7 us: 1.15x slower                                  |
| regex_v8                 | 22.0 ms                                                | 25.7 ms: 1.16x slower                                  |
| spectral_norm            | 100 ms                                                 | 117 ms: 1.17x slower                                   |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                  |
| mako                     | 10.1 ms                                                | 12.0 ms: 1.19x slower                                  |
| pickle_list              | 4.11 us                                                | 5.11 us: 1.24x slower                                  |
| telco                    | 6.58 ms                                                | 8.22 ms: 1.25x slower                                  |
| async_generators         | 368 ms                                                 | 462 ms: 1.25x slower                                   |
| Geometric mean           | (ref)                                                  | 1.02x faster                                           |

Benchmark hidden because not significant (4): xml_etree_parse, tornado_http, bench_mp_pool, meteor_contest
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 79.17% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
