
# Results vs. 3.11.0

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 237c561
- commit date: 2023-10-09
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.77 sec: 1.05x slower                                               |
| tornado_http   | 96.3 ms                                                | 102 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                  | 1.06x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.05x faster                                                 |
| nbody          | 93.1 ms                                                | 114 ms: 1.22x slower                                                 |
| float          | 77.2 ms                                                | 95.1 ms: 1.23x slower                                                |
| Geometric mean | (ref)                                                  | 1.13x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.58 ms: 1.12x faster                                                |
| regex_dna      | 204 ms                                                 | 208 ms: 1.02x slower                                                 |
| regex_v8       | 22.0 ms                                                | 24.9 ms: 1.13x slower                                                |
| regex_compile  | 138 ms                                                 | 162 ms: 1.17x slower                                                 |
| Geometric mean | (ref)                                                  | 1.05x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.5 ms: 1.20x faster                                                |
| pickle_pure_python   | 306 us                                                 | 310 us: 1.01x slower                                                 |
| unpickle_pure_python | 228 us                                                 | 240 us: 1.05x slower                                                 |
| unpickle_list        | 4.91 us                                                | 5.21 us: 1.06x slower                                                |
| xml_etree_iterparse  | 104 ms                                                 | 110 ms: 1.06x slower                                                 |
| json_loads           | 26.5 us                                                | 28.2 us: 1.06x slower                                                |
| tomli_loads          | 2.22 sec                                               | 2.41 sec: 1.08x slower                                               |
| pickle               | 10.1 us                                                | 10.9 us: 1.09x slower                                                |
| pickle_dict          | 31.1 us                                                | 34.4 us: 1.11x slower                                                |
| unpickle             | 13.7 us                                                | 15.2 us: 1.11x slower                                                |
| xml_etree_process    | 53.9 ms                                                | 60.6 ms: 1.12x slower                                                |
| xml_etree_generate   | 76.2 ms                                                | 88.6 ms: 1.16x slower                                                |
| pickle_list          | 4.11 us                                                | 4.97 us: 1.21x slower                                                |
| Geometric mean       | (ref)                                                  | 1.07x slower                                                         |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.84 ms: 1.14x slower                                                |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 13.4 ms: 1.33x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 159 us: 3.06x faster                                                 |
| generators               | 73.5 ms                                                | 30.7 ms: 2.39x faster                                                |
| asyncio_tcp              | 922 ms                                                 | 472 ms: 1.95x faster                                                 |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.75x faster                                               |
| json_dumps               | 12.6 ms                                                | 10.5 ms: 1.20x faster                                                |
| mypy2                    | 420 ms                                                 | 358 ms: 1.17x faster                                                 |
| async_tree_none          | 526 ms                                                 | 451 ms: 1.17x faster                                                 |
| regex_effbot             | 3.99 ms                                                | 3.58 ms: 1.12x faster                                                |
| coverage                 | 100 ms                                                 | 90.8 ms: 1.10x faster                                                |
| coroutines               | 25.5 ms                                                | 23.4 ms: 1.09x faster                                                |
| async_tree_memoization   | 627 ms                                                 | 580 ms: 1.08x faster                                                 |
| async_tree_io            | 1.30 sec                                               | 1.20 sec: 1.08x faster                                               |
| pidigits                 | 198 ms                                                 | 188 ms: 1.05x faster                                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.35 ms: 1.04x faster                                                |
| sqlglot_transpile        | 1.70 ms                                                | 1.67 ms: 1.02x faster                                                |
| sqlglot_normalize        | 108 ms                                                 | 108 ms: 1.00x slower                                                 |
| pickle_pure_python       | 306 us                                                 | 310 us: 1.01x slower                                                 |
| pycparser                | 1.18 sec                                               | 1.20 sec: 1.02x slower                                               |
| regex_dna                | 204 ms                                                 | 208 ms: 1.02x slower                                                 |
| create_gc_cycles         | 1.49 ms                                                | 1.53 ms: 1.03x slower                                                |
| bench_thread_pool        | 819 us                                                 | 845 us: 1.03x slower                                                 |
| sqlglot_optimize         | 53.1 ms                                                | 55.1 ms: 1.04x slower                                                |
| json                     | 4.94 ms                                                | 5.14 ms: 1.04x slower                                                |
| raytrace                 | 297 ms                                                 | 310 ms: 1.05x slower                                                 |
| mdp                      | 2.62 sec                                               | 2.74 sec: 1.05x slower                                               |
| docutils                 | 2.63 sec                                               | 2.77 sec: 1.05x slower                                               |
| unpickle_pure_python     | 228 us                                                 | 240 us: 1.05x slower                                                 |
| deepcopy                 | 342 us                                                 | 361 us: 1.06x slower                                                 |
| unpickle_list            | 4.91 us                                                | 5.21 us: 1.06x slower                                                |
| tornado_http             | 96.3 ms                                                | 102 ms: 1.06x slower                                                 |
| xml_etree_iterparse      | 104 ms                                                 | 110 ms: 1.06x slower                                                 |
| json_loads               | 26.5 us                                                | 28.2 us: 1.06x slower                                                |
| logging_simple           | 6.03 us                                                | 6.45 us: 1.07x slower                                                |
| chaos                    | 69.2 ms                                                | 74.2 ms: 1.07x slower                                                |
| gc_traversal             | 4.02 ms                                                | 4.35 ms: 1.08x slower                                                |
| logging_silent           | 101 ns                                                 | 109 ns: 1.08x slower                                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.19 us: 1.08x slower                                                |
| tomli_loads              | 2.22 sec                                               | 2.41 sec: 1.08x slower                                               |
| pickle                   | 10.1 us                                                | 10.9 us: 1.09x slower                                                |
| meteor_contest           | 107 ms                                                 | 116 ms: 1.09x slower                                                 |
| pathlib                  | 18.2 ms                                                | 19.8 ms: 1.09x slower                                                |
| richards                 | 45.7 ms                                                | 49.9 ms: 1.09x slower                                                |
| scimark_sor              | 118 ms                                                 | 129 ms: 1.09x slower                                                 |
| logging_format           | 6.68 us                                                | 7.33 us: 1.10x slower                                                |
| dulwich_log              | 63.7 ms                                                | 70.3 ms: 1.10x slower                                                |
| pickle_dict              | 31.1 us                                                | 34.4 us: 1.11x slower                                                |
| scimark_lu               | 110 ms                                                 | 122 ms: 1.11x slower                                                 |
| unpickle                 | 13.7 us                                                | 15.2 us: 1.11x slower                                                |
| sqlite_synth             | 2.52 us                                                | 2.83 us: 1.12x slower                                                |
| xml_etree_process        | 53.9 ms                                                | 60.6 ms: 1.12x slower                                                |
| crypto_pyaes             | 74.7 ms                                                | 84.0 ms: 1.13x slower                                                |
| scimark_monte_carlo      | 68.1 ms                                                | 76.7 ms: 1.13x slower                                                |
| regex_v8                 | 22.0 ms                                                | 24.9 ms: 1.13x slower                                                |
| python_startup_no_site   | 6.01 ms                                                | 6.84 ms: 1.14x slower                                                |
| deepcopy_memo            | 37.0 us                                                | 42.2 us: 1.14x slower                                                |
| spectral_norm            | 100 ms                                                 | 115 ms: 1.15x slower                                                 |
| pprint_pformat           | 1.46 sec                                               | 1.67 sec: 1.15x slower                                               |
| pprint_safe_repr         | 701 ms                                                 | 809 ms: 1.15x slower                                                 |
| fannkuch                 | 388 ms                                                 | 449 ms: 1.16x slower                                                 |
| xml_etree_generate       | 76.2 ms                                                | 88.6 ms: 1.16x slower                                                |
| regex_compile            | 138 ms                                                 | 162 ms: 1.17x slower                                                 |
| unpack_sequence          | 43.1 ns                                                | 50.6 ns: 1.17x slower                                                |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                |
| comprehensions           | 22.4 us                                                | 26.9 us: 1.20x slower                                                |
| nqueens                  | 83.4 ms                                                | 100 ms: 1.20x slower                                                 |
| go                       | 140 ms                                                 | 169 ms: 1.20x slower                                                 |
| pickle_list              | 4.11 us                                                | 4.97 us: 1.21x slower                                                |
| nbody                    | 93.1 ms                                                | 114 ms: 1.22x slower                                                 |
| float                    | 77.2 ms                                                | 95.1 ms: 1.23x slower                                                |
| pyflate                  | 418 ms                                                 | 526 ms: 1.26x slower                                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.81 ms: 1.29x slower                                                |
| scimark_fft              | 328 ms                                                 | 427 ms: 1.30x slower                                                 |
| deltablue                | 3.67 ms                                                | 4.80 ms: 1.31x slower                                                |
| async_generators         | 368 ms                                                 | 484 ms: 1.31x slower                                                 |
| telco                    | 6.58 ms                                                | 8.69 ms: 1.32x slower                                                |
| mako                     | 10.1 ms                                                | 13.4 ms: 1.33x slower                                                |
| hexiom                   | 6.37 ms                                                | 9.04 ms: 1.42x slower                                                |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                         |

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed, richards_super, bench_mp_pool, xml_etree_parse
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.03x
