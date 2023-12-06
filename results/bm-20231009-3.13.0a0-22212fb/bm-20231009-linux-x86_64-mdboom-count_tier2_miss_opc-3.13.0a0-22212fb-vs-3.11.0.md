
# Results vs. 3.11.0

- fork: mdboom
- ref: count_tier2_miss_opc
- machine: linux-x86_64
- commit hash: 22212fb
- commit date: 2023-10-09
- overall geometric mean: 1.02x faster
- HPT reliability: 89.18%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.65 sec: 1.01x slower                                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.05x faster                                                  |
| nbody          | 93.1 ms                                                | 95.8 ms: 1.03x slower                                                 |
| float          | 77.2 ms                                                | 82.8 ms: 1.07x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.58 ms: 1.12x faster                                                 |
| regex_dna      | 204 ms                                                 | 208 ms: 1.02x slower                                                  |
| regex_v8       | 22.0 ms                                                | 25.5 ms: 1.16x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                                          |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.4 ms: 1.22x faster                                                 |
| tomli_loads          | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                |
| unpickle_pure_python | 228 us                                                 | 223 us: 1.02x faster                                                  |
| pickle_pure_python   | 306 us                                                 | 307 us: 1.00x slower                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                  |
| json_loads           | 26.5 us                                                | 28.4 us: 1.07x slower                                                 |
| unpickle_list        | 4.91 us                                                | 5.30 us: 1.08x slower                                                 |
| unpickle             | 13.7 us                                                | 15.1 us: 1.10x slower                                                 |
| xml_etree_process    | 53.9 ms                                                | 60.1 ms: 1.12x slower                                                 |
| pickle_dict          | 31.1 us                                                | 34.8 us: 1.12x slower                                                 |
| pickle               | 10.1 us                                                | 11.3 us: 1.12x slower                                                 |
| xml_etree_generate   | 76.2 ms                                                | 88.1 ms: 1.16x slower                                                 |
| pickle_list          | 4.11 us                                                | 4.96 us: 1.21x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.05x slower                                                          |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.87 ms: 1.14x slower                                                 |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.3 ms: 1.12x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 152 us: 3.19x faster                                                  |
| generators               | 73.5 ms                                                | 29.3 ms: 2.51x faster                                                 |
| asyncio_tcp              | 922 ms                                                 | 468 ms: 1.97x faster                                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.78 sec: 1.76x faster                                                |
| mypy2                    | 420 ms                                                 | 345 ms: 1.22x faster                                                  |
| json_dumps               | 12.6 ms                                                | 10.4 ms: 1.22x faster                                                 |
| async_tree_none          | 526 ms                                                 | 442 ms: 1.19x faster                                                  |
| coroutines               | 25.5 ms                                                | 22.4 ms: 1.14x faster                                                 |
| chaos                    | 69.2 ms                                                | 61.7 ms: 1.12x faster                                                 |
| regex_effbot             | 3.99 ms                                                | 3.58 ms: 1.12x faster                                                 |
| coverage                 | 100 ms                                                 | 90.3 ms: 1.11x faster                                                 |
| async_tree_memoization   | 627 ms                                                 | 572 ms: 1.10x faster                                                  |
| deltablue                | 3.67 ms                                                | 3.36 ms: 1.09x faster                                                 |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                |
| sqlglot_parse            | 1.40 ms                                                | 1.29 ms: 1.08x faster                                                 |
| raytrace                 | 297 ms                                                 | 277 ms: 1.07x faster                                                  |
| sqlglot_transpile        | 1.70 ms                                                | 1.61 ms: 1.06x faster                                                 |
| pidigits                 | 198 ms                                                 | 188 ms: 1.05x faster                                                  |
| comprehensions           | 22.4 us                                                | 21.4 us: 1.05x faster                                                 |
| crypto_pyaes             | 74.7 ms                                                | 71.8 ms: 1.04x faster                                                 |
| richards_super           | 56.8 ms                                                | 54.9 ms: 1.03x faster                                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 717 ms: 1.03x faster                                                  |
| tomli_loads              | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                |
| sqlglot_normalize        | 108 ms                                                 | 105 ms: 1.02x faster                                                  |
| unpickle_pure_python     | 228 us                                                 | 223 us: 1.02x faster                                                  |
| logging_format           | 6.68 us                                                | 6.55 us: 1.02x faster                                                 |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                                |
| hexiom                   | 6.37 ms                                                | 6.27 ms: 1.02x faster                                                 |
| unpack_sequence          | 43.1 ns                                                | 42.5 ns: 1.01x faster                                                 |
| nqueens                  | 83.4 ms                                                | 82.4 ms: 1.01x faster                                                 |
| pickle_pure_python       | 306 us                                                 | 307 us: 1.00x slower                                                  |
| sqlglot_optimize         | 53.1 ms                                                | 53.5 ms: 1.01x slower                                                 |
| docutils                 | 2.63 sec                                               | 2.65 sec: 1.01x slower                                                |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                  |
| regex_dna                | 204 ms                                                 | 208 ms: 1.02x slower                                                  |
| scimark_monte_carlo      | 68.1 ms                                                | 69.8 ms: 1.03x slower                                                 |
| meteor_contest           | 107 ms                                                 | 110 ms: 1.03x slower                                                  |
| nbody                    | 93.1 ms                                                | 95.8 ms: 1.03x slower                                                 |
| go                       | 140 ms                                                 | 145 ms: 1.04x slower                                                  |
| json                     | 4.94 ms                                                | 5.14 ms: 1.04x slower                                                 |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                                 |
| create_gc_cycles         | 1.49 ms                                                | 1.55 ms: 1.04x slower                                                 |
| richards                 | 45.7 ms                                                | 47.7 ms: 1.04x slower                                                 |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.04x slower                                                |
| fannkuch                 | 388 ms                                                 | 406 ms: 1.05x slower                                                  |
| deepcopy                 | 342 us                                                 | 358 us: 1.05x slower                                                  |
| scimark_lu               | 110 ms                                                 | 115 ms: 1.05x slower                                                  |
| logging_silent           | 101 ns                                                 | 107 ns: 1.06x slower                                                  |
| scimark_sor              | 118 ms                                                 | 125 ms: 1.06x slower                                                  |
| dulwich_log              | 63.7 ms                                                | 67.5 ms: 1.06x slower                                                 |
| pprint_safe_repr         | 701 ms                                                 | 748 ms: 1.07x slower                                                  |
| deepcopy_memo            | 37.0 us                                                | 39.5 us: 1.07x slower                                                 |
| float                    | 77.2 ms                                                | 82.8 ms: 1.07x slower                                                 |
| json_loads               | 26.5 us                                                | 28.4 us: 1.07x slower                                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.17 us: 1.08x slower                                                 |
| unpickle_list            | 4.91 us                                                | 5.30 us: 1.08x slower                                                 |
| gc_traversal             | 4.02 ms                                                | 4.36 ms: 1.08x slower                                                 |
| unpickle                 | 13.7 us                                                | 15.1 us: 1.10x slower                                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.96 ms: 1.10x slower                                                 |
| xml_etree_process        | 53.9 ms                                                | 60.1 ms: 1.12x slower                                                 |
| pickle_dict              | 31.1 us                                                | 34.8 us: 1.12x slower                                                 |
| pickle                   | 10.1 us                                                | 11.3 us: 1.12x slower                                                 |
| mako                     | 10.1 ms                                                | 11.3 ms: 1.12x slower                                                 |
| sqlite_synth             | 2.52 us                                                | 2.84 us: 1.13x slower                                                 |
| pyflate                  | 418 ms                                                 | 472 ms: 1.13x slower                                                  |
| scimark_fft              | 328 ms                                                 | 373 ms: 1.14x slower                                                  |
| spectral_norm            | 100 ms                                                 | 114 ms: 1.14x slower                                                  |
| python_startup_no_site   | 6.01 ms                                                | 6.87 ms: 1.14x slower                                                 |
| xml_etree_generate       | 76.2 ms                                                | 88.1 ms: 1.16x slower                                                 |
| regex_v8                 | 22.0 ms                                                | 25.5 ms: 1.16x slower                                                 |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                 |
| pickle_list              | 4.11 us                                                | 4.96 us: 1.21x slower                                                 |
| async_generators         | 368 ms                                                 | 459 ms: 1.24x slower                                                  |
| telco                    | 6.58 ms                                                | 8.33 ms: 1.26x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.02x faster                                                          |

Benchmark hidden because not significant (7): tornado_http, bench_thread_pool, regex_compile, bench_mp_pool, mdp, logging_simple, xml_etree_parse
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 89.18% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
