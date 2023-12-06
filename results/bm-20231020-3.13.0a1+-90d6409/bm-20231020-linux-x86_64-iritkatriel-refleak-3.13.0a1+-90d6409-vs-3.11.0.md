
# Results vs. 3.11.0

- fork: iritkatriel
- ref: refleak
- machine: linux-x86_64
- commit hash: 90d6409
- commit date: 2023-10-20
- overall geometric mean: 1.03x faster
- HPT reliability: 61.21%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.65 sec: 1.01x slower                                         |
| tornado_http   | 96.3 ms                                                | 95.5 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.00x slower                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                           |
| nbody          | 93.1 ms                                                | 91.0 ms: 1.02x faster                                          |
| float          | 77.2 ms                                                | 80.2 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                  | 1.01x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.52 ms: 1.14x faster                                          |
| regex_compile  | 138 ms                                                 | 137 ms: 1.00x faster                                           |
| regex_dna      | 204 ms                                                 | 214 ms: 1.05x slower                                           |
| regex_v8       | 22.0 ms                                                | 25.4 ms: 1.15x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.4 ms: 1.22x faster                                          |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                         |
| unpickle_pure_python | 228 us                                                 | 220 us: 1.03x faster                                           |
| pickle_pure_python   | 306 us                                                 | 309 us: 1.01x slower                                           |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.02x slower                                           |
| json_loads           | 26.5 us                                                | 27.8 us: 1.05x slower                                          |
| unpickle_list        | 4.91 us                                                | 5.18 us: 1.06x slower                                          |
| unpickle             | 13.7 us                                                | 14.6 us: 1.07x slower                                          |
| xml_etree_process    | 53.9 ms                                                | 59.1 ms: 1.10x slower                                          |
| pickle               | 10.1 us                                                | 11.3 us: 1.12x slower                                          |
| xml_etree_generate   | 76.2 ms                                                | 86.4 ms: 1.13x slower                                          |
| pickle_dict          | 31.1 us                                                | 35.3 us: 1.14x slower                                          |
| pickle_list          | 4.11 us                                                | 5.16 us: 1.26x slower                                          |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                   |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.85 ms: 1.14x slower                                          |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                          |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.6 ms: 1.15x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 151 us: 3.22x faster                                           |
| generators               | 73.5 ms                                                | 29.7 ms: 2.48x faster                                          |
| asyncio_tcp              | 922 ms                                                 | 480 ms: 1.92x faster                                           |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.78 sec: 1.76x faster                                         |
| comprehensions           | 22.4 us                                                | 16.6 us: 1.35x faster                                          |
| mypy2                    | 420 ms                                                 | 342 ms: 1.23x faster                                           |
| json_dumps               | 12.6 ms                                                | 10.4 ms: 1.22x faster                                          |
| async_tree_none          | 526 ms                                                 | 439 ms: 1.20x faster                                           |
| regex_effbot             | 3.99 ms                                                | 3.52 ms: 1.14x faster                                          |
| chaos                    | 69.2 ms                                                | 61.3 ms: 1.13x faster                                          |
| coroutines               | 25.5 ms                                                | 22.9 ms: 1.12x faster                                          |
| async_tree_memoization   | 627 ms                                                 | 566 ms: 1.11x faster                                           |
| coverage                 | 100 ms                                                 | 90.5 ms: 1.11x faster                                          |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.09x faster                                          |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                         |
| deltablue                | 3.67 ms                                                | 3.36 ms: 1.09x faster                                          |
| raytrace                 | 297 ms                                                 | 273 ms: 1.09x faster                                           |
| sqlglot_transpile        | 1.70 ms                                                | 1.60 ms: 1.06x faster                                          |
| nqueens                  | 83.4 ms                                                | 78.6 ms: 1.06x faster                                          |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                           |
| richards_super           | 56.8 ms                                                | 53.7 ms: 1.06x faster                                          |
| hexiom                   | 6.37 ms                                                | 6.08 ms: 1.05x faster                                          |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                         |
| logging_format           | 6.68 us                                                | 6.41 us: 1.04x faster                                          |
| crypto_pyaes             | 74.7 ms                                                | 71.8 ms: 1.04x faster                                          |
| gc_traversal             | 4.02 ms                                                | 3.87 ms: 1.04x faster                                          |
| unpickle_pure_python     | 228 us                                                 | 220 us: 1.03x faster                                           |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 714 ms: 1.03x faster                                           |
| mdp                      | 2.62 sec                                               | 2.54 sec: 1.03x faster                                         |
| logging_simple           | 6.03 us                                                | 5.87 us: 1.03x faster                                          |
| nbody                    | 93.1 ms                                                | 91.0 ms: 1.02x faster                                          |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                           |
| create_gc_cycles         | 1.49 ms                                                | 1.47 ms: 1.01x faster                                          |
| bench_thread_pool        | 819 us                                                 | 812 us: 1.01x faster                                           |
| tornado_http             | 96.3 ms                                                | 95.5 ms: 1.01x faster                                          |
| regex_compile            | 138 ms                                                 | 137 ms: 1.00x faster                                           |
| scimark_monte_carlo      | 68.1 ms                                                | 68.5 ms: 1.01x slower                                          |
| sqlglot_optimize         | 53.1 ms                                                | 53.5 ms: 1.01x slower                                          |
| docutils                 | 2.63 sec                                               | 2.65 sec: 1.01x slower                                         |
| pickle_pure_python       | 306 us                                                 | 309 us: 1.01x slower                                           |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.02x slower                                           |
| pycparser                | 1.18 sec                                               | 1.21 sec: 1.02x slower                                         |
| unpack_sequence          | 43.1 ns                                                | 44.3 ns: 1.03x slower                                          |
| go                       | 140 ms                                                 | 144 ms: 1.03x slower                                           |
| pprint_pformat           | 1.46 sec                                               | 1.50 sec: 1.03x slower                                         |
| json                     | 4.94 ms                                                | 5.11 ms: 1.03x slower                                          |
| pathlib                  | 18.2 ms                                                | 18.9 ms: 1.04x slower                                          |
| float                    | 77.2 ms                                                | 80.2 ms: 1.04x slower                                          |
| richards                 | 45.7 ms                                                | 47.5 ms: 1.04x slower                                          |
| deepcopy                 | 342 us                                                 | 357 us: 1.05x slower                                           |
| pprint_safe_repr         | 701 ms                                                 | 734 ms: 1.05x slower                                           |
| fannkuch                 | 388 ms                                                 | 406 ms: 1.05x slower                                           |
| json_loads               | 26.5 us                                                | 27.8 us: 1.05x slower                                          |
| scimark_lu               | 110 ms                                                 | 115 ms: 1.05x slower                                           |
| regex_dna                | 204 ms                                                 | 214 ms: 1.05x slower                                           |
| dulwich_log              | 63.7 ms                                                | 67.1 ms: 1.05x slower                                          |
| unpickle_list            | 4.91 us                                                | 5.18 us: 1.06x slower                                          |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.76 ms: 1.06x slower                                          |
| unpickle                 | 13.7 us                                                | 14.6 us: 1.07x slower                                          |
| deepcopy_reduce          | 2.94 us                                                | 3.14 us: 1.07x slower                                          |
| scimark_sor              | 118 ms                                                 | 126 ms: 1.07x slower                                           |
| logging_silent           | 101 ns                                                 | 108 ns: 1.07x slower                                           |
| pyflate                  | 418 ms                                                 | 451 ms: 1.08x slower                                           |
| deepcopy_memo            | 37.0 us                                                | 39.9 us: 1.08x slower                                          |
| spectral_norm            | 100 ms                                                 | 110 ms: 1.10x slower                                           |
| xml_etree_process        | 53.9 ms                                                | 59.1 ms: 1.10x slower                                          |
| scimark_fft              | 328 ms                                                 | 366 ms: 1.11x slower                                           |
| sqlite_synth             | 2.52 us                                                | 2.81 us: 1.12x slower                                          |
| pickle                   | 10.1 us                                                | 11.3 us: 1.12x slower                                          |
| xml_etree_generate       | 76.2 ms                                                | 86.4 ms: 1.13x slower                                          |
| pickle_dict              | 31.1 us                                                | 35.3 us: 1.14x slower                                          |
| python_startup_no_site   | 6.01 ms                                                | 6.85 ms: 1.14x slower                                          |
| mako                     | 10.1 ms                                                | 11.6 ms: 1.15x slower                                          |
| regex_v8                 | 22.0 ms                                                | 25.4 ms: 1.15x slower                                          |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                          |
| async_generators         | 368 ms                                                 | 454 ms: 1.23x slower                                           |
| pickle_list              | 4.11 us                                                | 5.16 us: 1.26x slower                                          |
| telco                    | 6.58 ms                                                | 8.35 ms: 1.27x slower                                          |
| Geometric mean           | (ref)                                                  | 1.03x faster                                                   |

Benchmark hidden because not significant (3): meteor_contest, xml_etree_parse, bench_mp_pool
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 61.21% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
