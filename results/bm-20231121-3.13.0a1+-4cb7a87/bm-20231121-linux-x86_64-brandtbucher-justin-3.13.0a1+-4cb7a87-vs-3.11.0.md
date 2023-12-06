
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 4cb7a87
- commit date: 2023-11-21
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.92%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 291 ms: 1.09x slower                                           |
| chameleon      | 6.86 ms                                                | 7.48 ms: 1.09x slower                                          |
| docutils       | 2.69 sec                                               | 2.73 sec: 1.02x slower                                         |
| tornado_http   | 97.7 ms                                                | 99.8 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 532 ms                                                 | 459 ms: 1.16x faster                                           |
| async_tree_memoization  | 640 ms                                                 | 585 ms: 1.09x faster                                           |
| async_tree_io           | 1.31 sec                                               | 1.23 sec: 1.07x faster                                         |
| async_tree_io_tg        | 1.30 sec                                               | 1.26 sec: 1.04x faster                                         |
| async_tree_none_tg      | 490 ms                                                 | 472 ms: 1.04x faster                                           |
| async_tree_cpu_io_mixed | 750 ms                                                 | 737 ms: 1.02x faster                                           |
| Geometric mean          | (ref)                                                  | 1.05x faster                                                   |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                           |
| float          | 78.9 ms                                                | 98.5 ms: 1.25x slower                                          |
| nbody          | 91.6 ms                                                | 128 ms: 1.40x slower                                           |
| Geometric mean | (ref)                                                  | 1.20x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 204 ms                                                 | 217 ms: 1.06x slower                                           |
| regex_effbot   | 3.45 ms                                                | 3.72 ms: 1.08x slower                                          |
| regex_v8       | 22.9 ms                                                | 25.6 ms: 1.12x slower                                          |
| regex_compile  | 141 ms                                                 | 162 ms: 1.14x slower                                           |
| Geometric mean | (ref)                                                  | 1.10x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.8 ms: 1.25x faster                                          |
| json_loads           | 29.4 us                                                | 28.2 us: 1.04x faster                                          |
| pickle_pure_python   | 319 us                                                 | 308 us: 1.03x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                           |
| unpickle_list        | 5.22 us                                                | 5.20 us: 1.00x faster                                          |
| pickle_dict          | 34.8 us                                                | 34.9 us: 1.00x slower                                          |
| unpickle_pure_python | 241 us                                                 | 242 us: 1.01x slower                                           |
| pickle               | 11.1 us                                                | 11.6 us: 1.05x slower                                          |
| xml_etree_iterparse  | 109 ms                                                 | 115 ms: 1.06x slower                                           |
| unpickle             | 13.9 us                                                | 14.9 us: 1.07x slower                                          |
| pickle_list          | 4.65 us                                                | 5.10 us: 1.10x slower                                          |
| xml_etree_process    | 56.5 ms                                                | 63.0 ms: 1.12x slower                                          |
| xml_etree_generate   | 80.4 ms                                                | 92.3 ms: 1.15x slower                                          |
| tomli_loads          | 2.31 sec                                               | 2.73 sec: 1.18x slower                                         |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                          |
| python_startup_no_site | 6.09 ms                                                | 9.03 ms: 1.48x slower                                          |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 15.2 ms: 1.40x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 521 us                                                 | 123 us: 4.22x faster                                           |
| generators               | 76.5 ms                                                | 29.7 ms: 2.58x faster                                          |
| asyncio_tcp              | 887 ms                                                 | 494 ms: 1.80x faster                                           |
| asyncio_tcp_ssl          | 3.13 sec                                               | 1.81 sec: 1.73x faster                                         |
| json_dumps               | 13.5 ms                                                | 10.8 ms: 1.25x faster                                          |
| mypy2                    | 427 ms                                                 | 356 ms: 1.20x faster                                           |
| coroutines               | 26.1 ms                                                | 22.4 ms: 1.17x faster                                          |
| async_tree_none          | 532 ms                                                 | 459 ms: 1.16x faster                                           |
| richards_super           | 61.2 ms                                                | 55.3 ms: 1.11x faster                                          |
| async_tree_memoization   | 640 ms                                                 | 585 ms: 1.09x faster                                           |
| async_tree_io            | 1.31 sec                                               | 1.23 sec: 1.07x faster                                         |
| sympy_sum                | 170 ms                                                 | 162 ms: 1.05x faster                                           |
| json_loads               | 29.4 us                                                | 28.2 us: 1.04x faster                                          |
| async_tree_io_tg         | 1.30 sec                                               | 1.26 sec: 1.04x faster                                         |
| async_tree_none_tg       | 490 ms                                                 | 472 ms: 1.04x faster                                           |
| pickle_pure_python       | 319 us                                                 | 308 us: 1.03x faster                                           |
| sqlglot_parse            | 1.43 ms                                                | 1.39 ms: 1.03x faster                                          |
| unpack_sequence          | 43.3 ns                                                | 42.0 ns: 1.03x faster                                          |
| logging_simple           | 6.24 us                                                | 6.09 us: 1.03x faster                                          |
| xml_etree_parse          | 163 ms                                                 | 159 ms: 1.03x faster                                           |
| sqlglot_transpile        | 1.75 ms                                                | 1.71 ms: 1.03x faster                                          |
| comprehensions           | 23.6 us                                                | 23.1 us: 1.02x faster                                          |
| async_tree_cpu_io_mixed  | 750 ms                                                 | 737 ms: 1.02x faster                                           |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                           |
| gc_traversal             | 3.90 ms                                                | 3.87 ms: 1.01x faster                                          |
| sympy_str                | 299 ms                                                 | 297 ms: 1.01x faster                                           |
| asyncio_websockets       | 556 ms                                                 | 552 ms: 1.01x faster                                           |
| unpickle_list            | 5.22 us                                                | 5.20 us: 1.00x faster                                          |
| pickle_dict              | 34.8 us                                                | 34.9 us: 1.00x slower                                          |
| create_gc_cycles         | 1.48 ms                                                | 1.48 ms: 1.00x slower                                          |
| logging_silent           | 108 ns                                                 | 109 ns: 1.00x slower                                           |
| unpickle_pure_python     | 241 us                                                 | 242 us: 1.01x slower                                           |
| sympy_integrate          | 21.4 ms                                                | 21.6 ms: 1.01x slower                                          |
| deepcopy_reduce          | 3.14 us                                                | 3.18 us: 1.01x slower                                          |
| docutils                 | 2.69 sec                                               | 2.73 sec: 1.02x slower                                         |
| dask                     | 365 ms                                                 | 371 ms: 1.02x slower                                           |
| sqlglot_normalize        | 112 ms                                                 | 115 ms: 1.02x slower                                           |
| tornado_http             | 97.7 ms                                                | 99.8 ms: 1.02x slower                                          |
| pathlib                  | 18.5 ms                                                | 18.9 ms: 1.02x slower                                          |
| pycparser                | 1.20 sec                                               | 1.22 sec: 1.02x slower                                         |
| richards                 | 48.9 ms                                                | 50.1 ms: 1.03x slower                                          |
| bench_thread_pool        | 833 us                                                 | 860 us: 1.03x slower                                           |
| mdp                      | 2.79 sec                                               | 2.88 sec: 1.03x slower                                         |
| raytrace                 | 306 ms                                                 | 318 ms: 1.04x slower                                           |
| scimark_sor              | 121 ms                                                 | 127 ms: 1.04x slower                                           |
| pickle                   | 11.1 us                                                | 11.6 us: 1.05x slower                                          |
| deepcopy_memo            | 38.9 us                                                | 41.1 us: 1.06x slower                                          |
| xml_etree_iterparse      | 109 ms                                                 | 115 ms: 1.06x slower                                           |
| sqlglot_optimize         | 55.2 ms                                                | 58.5 ms: 1.06x slower                                          |
| dulwich_log              | 64.9 ms                                                | 69.1 ms: 1.06x slower                                          |
| regex_dna                | 204 ms                                                 | 217 ms: 1.06x slower                                           |
| scimark_lu               | 112 ms                                                 | 120 ms: 1.07x slower                                           |
| unpickle                 | 13.9 us                                                | 14.9 us: 1.07x slower                                          |
| regex_effbot             | 3.45 ms                                                | 3.72 ms: 1.08x slower                                          |
| meteor_contest           | 109 ms                                                 | 118 ms: 1.08x slower                                           |
| chameleon                | 6.86 ms                                                | 7.48 ms: 1.09x slower                                          |
| 2to3                     | 266 ms                                                 | 291 ms: 1.09x slower                                           |
| chaos                    | 71.4 ms                                                | 78.0 ms: 1.09x slower                                          |
| pickle_list              | 4.65 us                                                | 5.10 us: 1.10x slower                                          |
| pprint_safe_repr         | 743 ms                                                 | 824 ms: 1.11x slower                                           |
| xml_etree_process        | 56.5 ms                                                | 63.0 ms: 1.12x slower                                          |
| regex_v8                 | 22.9 ms                                                | 25.6 ms: 1.12x slower                                          |
| sqlite_synth             | 2.58 us                                                | 2.89 us: 1.12x slower                                          |
| pprint_pformat           | 1.53 sec                                               | 1.72 sec: 1.12x slower                                         |
| crypto_pyaes             | 77.5 ms                                                | 88.4 ms: 1.14x slower                                          |
| regex_compile            | 141 ms                                                 | 162 ms: 1.14x slower                                           |
| xml_etree_generate       | 80.4 ms                                                | 92.3 ms: 1.15x slower                                          |
| fannkuch                 | 410 ms                                                 | 471 ms: 1.15x slower                                           |
| go                       | 143 ms                                                 | 165 ms: 1.15x slower                                           |
| nqueens                  | 86.8 ms                                                | 100 ms: 1.16x slower                                           |
| coverage                 | 81.2 ms                                                | 95.2 ms: 1.17x slower                                          |
| tomli_loads              | 2.31 sec                                               | 2.73 sec: 1.18x slower                                         |
| python_startup           | 8.69 ms                                                | 10.4 ms: 1.19x slower                                          |
| scimark_monte_carlo      | 71.8 ms                                                | 86.1 ms: 1.20x slower                                          |
| async_generators         | 375 ms                                                 | 457 ms: 1.22x slower                                           |
| float                    | 78.9 ms                                                | 98.5 ms: 1.25x slower                                          |
| pyflate                  | 426 ms                                                 | 547 ms: 1.28x slower                                           |
| telco                    | 6.72 ms                                                | 8.66 ms: 1.29x slower                                          |
| deltablue                | 3.80 ms                                                | 5.12 ms: 1.34x slower                                          |
| hexiom                   | 6.74 ms                                                | 9.17 ms: 1.36x slower                                          |
| scimark_sparse_mat_mult  | 4.80 ms                                                | 6.55 ms: 1.36x slower                                          |
| scimark_fft              | 342 ms                                                 | 475 ms: 1.39x slower                                           |
| nbody                    | 91.6 ms                                                | 128 ms: 1.40x slower                                           |
| mako                     | 10.8 ms                                                | 15.2 ms: 1.40x slower                                          |
| python_startup_no_site   | 6.09 ms                                                | 9.03 ms: 1.48x slower                                          |
| spectral_norm            | 105 ms                                                 | 162 ms: 1.54x slower                                           |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (7): async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, bench_mp_pool, logging_format, deepcopy, json, sympy_expand
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.92% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
