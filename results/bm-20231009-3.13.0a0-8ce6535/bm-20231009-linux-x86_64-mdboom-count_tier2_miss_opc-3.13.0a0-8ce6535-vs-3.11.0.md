
# Results vs. 3.11.0

- fork: mdboom
- ref: count_tier2_miss_opc
- machine: linux-x86_64
- commit hash: 8ce6535
- commit date: 2023-10-09
- overall geometric mean: 1.02x faster
- HPT reliability: 85.15%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.65 sec: 1.01x slower                                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                  |
| nbody          | 93.1 ms                                                | 95.9 ms: 1.03x slower                                                 |
| float          | 77.2 ms                                                | 80.7 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.57 ms: 1.12x faster                                                 |
| regex_compile  | 138 ms                                                 | 139 ms: 1.01x slower                                                  |
| regex_dna      | 204 ms                                                 | 207 ms: 1.02x slower                                                  |
| regex_v8       | 22.0 ms                                                | 25.6 ms: 1.16x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.4 ms: 1.21x faster                                                 |
| tomli_loads          | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                |
| unpickle_pure_python | 228 us                                                 | 222 us: 1.03x faster                                                  |
| pickle_pure_python   | 306 us                                                 | 305 us: 1.00x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                  |
| pickle_dict          | 31.1 us                                                | 33.1 us: 1.06x slower                                                 |
| json_loads           | 26.5 us                                                | 28.6 us: 1.08x slower                                                 |
| unpickle_list        | 4.91 us                                                | 5.31 us: 1.08x slower                                                 |
| unpickle             | 13.7 us                                                | 14.9 us: 1.09x slower                                                 |
| xml_etree_process    | 53.9 ms                                                | 59.2 ms: 1.10x slower                                                 |
| pickle               | 10.1 us                                                | 11.1 us: 1.11x slower                                                 |
| xml_etree_generate   | 76.2 ms                                                | 86.5 ms: 1.14x slower                                                 |
| pickle_list          | 4.11 us                                                | 5.18 us: 1.26x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                          |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.85 ms: 1.14x slower                                                 |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.5 ms: 1.14x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 153 us: 3.18x faster                                                  |
| generators               | 73.5 ms                                                | 29.2 ms: 2.51x faster                                                 |
| asyncio_tcp              | 922 ms                                                 | 466 ms: 1.98x faster                                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.77 sec: 1.77x faster                                                |
| mypy2                    | 420 ms                                                 | 344 ms: 1.22x faster                                                  |
| json_dumps               | 12.6 ms                                                | 10.4 ms: 1.21x faster                                                 |
| async_tree_none          | 526 ms                                                 | 437 ms: 1.20x faster                                                  |
| coroutines               | 25.5 ms                                                | 22.0 ms: 1.16x faster                                                 |
| regex_effbot             | 3.99 ms                                                | 3.57 ms: 1.12x faster                                                 |
| async_tree_memoization   | 627 ms                                                 | 566 ms: 1.11x faster                                                  |
| chaos                    | 69.2 ms                                                | 62.4 ms: 1.11x faster                                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.10x faster                                                 |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                |
| coverage                 | 100 ms                                                 | 91.6 ms: 1.09x faster                                                 |
| deltablue                | 3.67 ms                                                | 3.37 ms: 1.09x faster                                                 |
| sqlglot_transpile        | 1.70 ms                                                | 1.60 ms: 1.07x faster                                                 |
| raytrace                 | 297 ms                                                 | 281 ms: 1.06x faster                                                  |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                  |
| comprehensions           | 22.4 us                                                | 21.3 us: 1.05x faster                                                 |
| nqueens                  | 83.4 ms                                                | 80.1 ms: 1.04x faster                                                 |
| crypto_pyaes             | 74.7 ms                                                | 71.8 ms: 1.04x faster                                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 711 ms: 1.04x faster                                                  |
| tomli_loads              | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                |
| unpickle_pure_python     | 228 us                                                 | 222 us: 1.03x faster                                                  |
| hexiom                   | 6.37 ms                                                | 6.22 ms: 1.02x faster                                                 |
| logging_format           | 6.68 us                                                | 6.53 us: 1.02x faster                                                 |
| richards_super           | 56.8 ms                                                | 55.6 ms: 1.02x faster                                                 |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                                  |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                                |
| gc_traversal             | 4.02 ms                                                | 3.97 ms: 1.01x faster                                                 |
| logging_simple           | 6.03 us                                                | 5.95 us: 1.01x faster                                                 |
| bench_thread_pool        | 819 us                                                 | 816 us: 1.00x faster                                                  |
| pickle_pure_python       | 306 us                                                 | 305 us: 1.00x faster                                                  |
| sqlglot_optimize         | 53.1 ms                                                | 53.3 ms: 1.00x slower                                                 |
| regex_compile            | 138 ms                                                 | 139 ms: 1.01x slower                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                  |
| docutils                 | 2.63 sec                                               | 2.65 sec: 1.01x slower                                                |
| regex_dna                | 204 ms                                                 | 207 ms: 1.02x slower                                                  |
| scimark_monte_carlo      | 68.1 ms                                                | 69.4 ms: 1.02x slower                                                 |
| fannkuch                 | 388 ms                                                 | 397 ms: 1.02x slower                                                  |
| meteor_contest           | 107 ms                                                 | 109 ms: 1.03x slower                                                  |
| mdp                      | 2.62 sec                                               | 2.69 sec: 1.03x slower                                                |
| go                       | 140 ms                                                 | 144 ms: 1.03x slower                                                  |
| nbody                    | 93.1 ms                                                | 95.9 ms: 1.03x slower                                                 |
| create_gc_cycles         | 1.49 ms                                                | 1.53 ms: 1.03x slower                                                 |
| scimark_lu               | 110 ms                                                 | 114 ms: 1.04x slower                                                  |
| pprint_pformat           | 1.46 sec                                               | 1.51 sec: 1.04x slower                                                |
| float                    | 77.2 ms                                                | 80.7 ms: 1.05x slower                                                 |
| deepcopy                 | 342 us                                                 | 358 us: 1.05x slower                                                  |
| json                     | 4.94 ms                                                | 5.17 ms: 1.05x slower                                                 |
| pathlib                  | 18.2 ms                                                | 19.1 ms: 1.05x slower                                                 |
| scimark_sor              | 118 ms                                                 | 125 ms: 1.05x slower                                                  |
| pprint_safe_repr         | 701 ms                                                 | 743 ms: 1.06x slower                                                  |
| dulwich_log              | 63.7 ms                                                | 67.5 ms: 1.06x slower                                                 |
| logging_silent           | 101 ns                                                 | 107 ns: 1.06x slower                                                  |
| pickle_dict              | 31.1 us                                                | 33.1 us: 1.06x slower                                                 |
| richards                 | 45.7 ms                                                | 48.7 ms: 1.07x slower                                                 |
| json_loads               | 26.5 us                                                | 28.6 us: 1.08x slower                                                 |
| deepcopy_memo            | 37.0 us                                                | 39.9 us: 1.08x slower                                                 |
| unpickle_list            | 4.91 us                                                | 5.31 us: 1.08x slower                                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.19 us: 1.08x slower                                                 |
| unpickle                 | 13.7 us                                                | 14.9 us: 1.09x slower                                                 |
| xml_etree_process        | 53.9 ms                                                | 59.2 ms: 1.10x slower                                                 |
| pickle                   | 10.1 us                                                | 11.1 us: 1.11x slower                                                 |
| spectral_norm            | 100 ms                                                 | 112 ms: 1.12x slower                                                  |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.02 ms: 1.12x slower                                                 |
| pyflate                  | 418 ms                                                 | 471 ms: 1.13x slower                                                  |
| sqlite_synth             | 2.52 us                                                | 2.85 us: 1.13x slower                                                 |
| xml_etree_generate       | 76.2 ms                                                | 86.5 ms: 1.14x slower                                                 |
| mako                     | 10.1 ms                                                | 11.5 ms: 1.14x slower                                                 |
| python_startup_no_site   | 6.01 ms                                                | 6.85 ms: 1.14x slower                                                 |
| scimark_fft              | 328 ms                                                 | 375 ms: 1.14x slower                                                  |
| regex_v8                 | 22.0 ms                                                | 25.6 ms: 1.16x slower                                                 |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                 |
| unpack_sequence          | 43.1 ns                                                | 52.0 ns: 1.21x slower                                                 |
| async_generators         | 368 ms                                                 | 461 ms: 1.25x slower                                                  |
| pickle_list              | 4.11 us                                                | 5.18 us: 1.26x slower                                                 |
| telco                    | 6.58 ms                                                | 8.51 ms: 1.29x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.02x faster                                                          |

Benchmark hidden because not significant (3): xml_etree_parse, tornado_http, bench_mp_pool
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 85.15% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
