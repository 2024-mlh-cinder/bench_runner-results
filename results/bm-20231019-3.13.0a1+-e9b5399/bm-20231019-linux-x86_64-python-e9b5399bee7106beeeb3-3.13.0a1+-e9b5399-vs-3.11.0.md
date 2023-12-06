
# Results vs. 3.11.0

- fork: python
- ref: e9b5399bee7106beeeb3
- machine: linux-x86_64
- commit hash: e9b5399
- commit date: 2023-10-19
- overall geometric mean: 1.02x faster
- HPT reliability: 71.48%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.67 sec: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 93.1 ms                                                | 91.5 ms: 1.02x faster                                                  |
| pidigits       | 198 ms                                                 | 195 ms: 1.02x faster                                                   |
| float          | 77.2 ms                                                | 81.7 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.63 ms: 1.10x faster                                                  |
| regex_compile  | 138 ms                                                 | 137 ms: 1.01x faster                                                   |
| regex_dna      | 204 ms                                                 | 221 ms: 1.08x slower                                                   |
| regex_v8       | 22.0 ms                                                | 24.5 ms: 1.11x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.5 ms: 1.20x faster                                                  |
| tomli_loads          | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                 |
| unpickle_pure_python | 228 us                                                 | 223 us: 1.02x faster                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                                   |
| unpickle_list        | 4.91 us                                                | 5.08 us: 1.04x slower                                                  |
| json_loads           | 26.5 us                                                | 27.8 us: 1.05x slower                                                  |
| unpickle             | 13.7 us                                                | 15.0 us: 1.10x slower                                                  |
| xml_etree_process    | 53.9 ms                                                | 59.7 ms: 1.11x slower                                                  |
| xml_etree_generate   | 76.2 ms                                                | 86.4 ms: 1.13x slower                                                  |
| pickle               | 10.1 us                                                | 11.5 us: 1.14x slower                                                  |
| pickle_dict          | 31.1 us                                                | 36.1 us: 1.16x slower                                                  |
| pickle_list          | 4.11 us                                                | 5.14 us: 1.25x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.05x slower                                                           |

Benchmark hidden because not significant (2): pickle_pure_python, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.90 ms: 1.15x slower                                                  |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.17x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.7 ms: 1.16x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 155 us: 3.14x faster                                                   |
| generators               | 73.5 ms                                                | 29.8 ms: 2.47x faster                                                  |
| asyncio_tcp              | 922 ms                                                 | 477 ms: 1.93x faster                                                   |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.78 sec: 1.76x faster                                                 |
| mypy2                    | 420 ms                                                 | 344 ms: 1.22x faster                                                   |
| json_dumps               | 12.6 ms                                                | 10.5 ms: 1.20x faster                                                  |
| async_tree_none          | 526 ms                                                 | 438 ms: 1.20x faster                                                   |
| coroutines               | 25.5 ms                                                | 22.3 ms: 1.14x faster                                                  |
| async_tree_memoization   | 627 ms                                                 | 561 ms: 1.12x faster                                                   |
| chaos                    | 69.2 ms                                                | 62.3 ms: 1.11x faster                                                  |
| deltablue                | 3.67 ms                                                | 3.32 ms: 1.11x faster                                                  |
| coverage                 | 100 ms                                                 | 90.5 ms: 1.11x faster                                                  |
| async_tree_io            | 1.30 sec                                               | 1.18 sec: 1.10x faster                                                 |
| regex_effbot             | 3.99 ms                                                | 3.63 ms: 1.10x faster                                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.29 ms: 1.09x faster                                                  |
| comprehensions           | 22.4 us                                                | 20.7 us: 1.08x faster                                                  |
| raytrace                 | 297 ms                                                 | 278 ms: 1.07x faster                                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.61 ms: 1.06x faster                                                  |
| nqueens                  | 83.4 ms                                                | 79.4 ms: 1.05x faster                                                  |
| richards_super           | 56.8 ms                                                | 54.3 ms: 1.05x faster                                                  |
| gc_traversal             | 4.02 ms                                                | 3.87 ms: 1.04x faster                                                  |
| logging_simple           | 6.03 us                                                | 5.80 us: 1.04x faster                                                  |
| logging_format           | 6.68 us                                                | 6.43 us: 1.04x faster                                                  |
| hexiom                   | 6.37 ms                                                | 6.15 ms: 1.04x faster                                                  |
| crypto_pyaes             | 74.7 ms                                                | 72.2 ms: 1.04x faster                                                  |
| tomli_loads              | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 716 ms: 1.03x faster                                                   |
| mdp                      | 2.62 sec                                               | 2.55 sec: 1.02x faster                                                 |
| unpickle_pure_python     | 228 us                                                 | 223 us: 1.02x faster                                                   |
| nbody                    | 93.1 ms                                                | 91.5 ms: 1.02x faster                                                  |
| pidigits                 | 198 ms                                                 | 195 ms: 1.02x faster                                                   |
| pycparser                | 1.18 sec                                               | 1.17 sec: 1.01x faster                                                 |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.01x faster                                                   |
| create_gc_cycles         | 1.49 ms                                                | 1.47 ms: 1.01x faster                                                  |
| bench_thread_pool        | 819 us                                                 | 813 us: 1.01x faster                                                   |
| regex_compile            | 138 ms                                                 | 137 ms: 1.01x faster                                                   |
| sqlglot_optimize         | 53.1 ms                                                | 53.7 ms: 1.01x slower                                                  |
| docutils                 | 2.63 sec                                               | 2.67 sec: 1.02x slower                                                 |
| go                       | 140 ms                                                 | 143 ms: 1.02x slower                                                   |
| scimark_monte_carlo      | 68.1 ms                                                | 69.5 ms: 1.02x slower                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                                   |
| meteor_contest           | 107 ms                                                 | 110 ms: 1.03x slower                                                   |
| json                     | 4.94 ms                                                | 5.08 ms: 1.03x slower                                                  |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.63 ms: 1.03x slower                                                  |
| unpickle_list            | 4.91 us                                                | 5.08 us: 1.04x slower                                                  |
| deepcopy                 | 342 us                                                 | 356 us: 1.04x slower                                                   |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.04x slower                                                 |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                                  |
| scimark_lu               | 110 ms                                                 | 115 ms: 1.04x slower                                                   |
| json_loads               | 26.5 us                                                | 27.8 us: 1.05x slower                                                  |
| fannkuch                 | 388 ms                                                 | 410 ms: 1.06x slower                                                   |
| richards                 | 45.7 ms                                                | 48.4 ms: 1.06x slower                                                  |
| float                    | 77.2 ms                                                | 81.7 ms: 1.06x slower                                                  |
| dulwich_log              | 63.7 ms                                                | 67.4 ms: 1.06x slower                                                  |
| scimark_sor              | 118 ms                                                 | 126 ms: 1.06x slower                                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.14 us: 1.07x slower                                                  |
| pprint_safe_repr         | 701 ms                                                 | 749 ms: 1.07x slower                                                   |
| deepcopy_memo            | 37.0 us                                                | 40.0 us: 1.08x slower                                                  |
| logging_silent           | 101 ns                                                 | 109 ns: 1.08x slower                                                   |
| regex_dna                | 204 ms                                                 | 221 ms: 1.08x slower                                                   |
| unpickle                 | 13.7 us                                                | 15.0 us: 1.10x slower                                                  |
| xml_etree_process        | 53.9 ms                                                | 59.7 ms: 1.11x slower                                                  |
| regex_v8                 | 22.0 ms                                                | 24.5 ms: 1.11x slower                                                  |
| scimark_fft              | 328 ms                                                 | 365 ms: 1.11x slower                                                   |
| pyflate                  | 418 ms                                                 | 470 ms: 1.12x slower                                                   |
| sqlite_synth             | 2.52 us                                                | 2.85 us: 1.13x slower                                                  |
| spectral_norm            | 100 ms                                                 | 113 ms: 1.13x slower                                                   |
| xml_etree_generate       | 76.2 ms                                                | 86.4 ms: 1.13x slower                                                  |
| pickle                   | 10.1 us                                                | 11.5 us: 1.14x slower                                                  |
| python_startup_no_site   | 6.01 ms                                                | 6.90 ms: 1.15x slower                                                  |
| mako                     | 10.1 ms                                                | 11.7 ms: 1.16x slower                                                  |
| pickle_dict              | 31.1 us                                                | 36.1 us: 1.16x slower                                                  |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                  |
| unpack_sequence          | 43.1 ns                                                | 51.3 ns: 1.19x slower                                                  |
| async_generators         | 368 ms                                                 | 452 ms: 1.23x slower                                                   |
| pickle_list              | 4.11 us                                                | 5.14 us: 1.25x slower                                                  |
| telco                    | 6.58 ms                                                | 8.39 ms: 1.27x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (4): tornado_http, bench_mp_pool, pickle_pure_python, xml_etree_parse
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 71.48% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
