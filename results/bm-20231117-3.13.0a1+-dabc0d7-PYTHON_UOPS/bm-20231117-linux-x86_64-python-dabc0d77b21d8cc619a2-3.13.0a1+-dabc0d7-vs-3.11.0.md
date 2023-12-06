
# Results vs. 3.11.0

- fork: python
- ref: dabc0d77b21d8cc619a2
- machine: linux-x86_64
- commit hash: dabc0d7
- commit date: 2023-11-17
- overall geometric mean: 1.05x slower \*
- HPT reliability: 99.94%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 297 ms: 1.12x slower                                                   |
| chameleon      | 6.86 ms                                                | 7.46 ms: 1.09x slower                                                  |
| docutils       | 2.69 sec                                               | 2.72 sec: 1.01x slower                                                 |
| tornado_http   | 97.7 ms                                                | 103 ms: 1.05x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 464 ms: 1.15x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 595 ms: 1.08x faster                                                   |
| async_tree_io              | 1.31 sec                                               | 1.24 sec: 1.06x faster                                                 |
| async_tree_io_tg           | 1.30 sec                                               | 1.27 sec: 1.03x faster                                                 |
| async_tree_memoization_tg  | 627 ms                                                 | 610 ms: 1.03x faster                                                   |
| async_tree_none_tg         | 490 ms                                                 | 481 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 743 ms: 1.01x faster                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 773 ms: 1.01x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.04x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 198 ms: 1.04x slower                                                   |
| float          | 78.9 ms                                                | 119 ms: 1.51x slower                                                   |
| nbody          | 91.6 ms                                                | 142 ms: 1.55x slower                                                   |
| Geometric mean | (ref)                                                  | 1.34x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.56 ms: 1.03x slower                                                  |
| regex_dna      | 204 ms                                                 | 216 ms: 1.06x slower                                                   |
| regex_v8       | 22.9 ms                                                | 24.8 ms: 1.08x slower                                                  |
| regex_compile  | 141 ms                                                 | 171 ms: 1.21x slower                                                   |
| Geometric mean | (ref)                                                  | 1.09x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                  |
| json_loads           | 29.4 us                                                | 28.0 us: 1.05x faster                                                  |
| pickle_dict          | 34.8 us                                                | 33.5 us: 1.04x faster                                                  |
| pickle_pure_python   | 319 us                                                 | 308 us: 1.04x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                                   |
| unpickle_list        | 5.22 us                                                | 5.29 us: 1.01x slower                                                  |
| unpickle_pure_python | 241 us                                                 | 252 us: 1.05x slower                                                   |
| xml_etree_process    | 56.5 ms                                                | 59.3 ms: 1.05x slower                                                  |
| xml_etree_iterparse  | 109 ms                                                 | 114 ms: 1.05x slower                                                   |
| unpickle             | 13.9 us                                                | 14.9 us: 1.07x slower                                                  |
| pickle_list          | 4.65 us                                                | 5.05 us: 1.09x slower                                                  |
| xml_etree_generate   | 80.4 ms                                                | 87.8 ms: 1.09x slower                                                  |
| tomli_loads          | 2.31 sec                                               | 3.11 sec: 1.34x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                  |
| python_startup_no_site | 6.09 ms                                                | 9.05 ms: 1.48x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 17.7 ms: 1.64x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 127 us: 4.10x faster                                                   |
| generators                 | 76.5 ms                                                | 29.5 ms: 2.59x faster                                                  |
| asyncio_tcp                | 887 ms                                                 | 483 ms: 1.84x faster                                                   |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.81 sec: 1.73x faster                                                 |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                  |
| mypy2                      | 427 ms                                                 | 355 ms: 1.20x faster                                                   |
| coroutines                 | 26.1 ms                                                | 22.0 ms: 1.19x faster                                                  |
| async_tree_none            | 532 ms                                                 | 464 ms: 1.15x faster                                                   |
| sympy_sum                  | 170 ms                                                 | 155 ms: 1.10x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 595 ms: 1.08x faster                                                   |
| async_tree_io              | 1.31 sec                                               | 1.24 sec: 1.06x faster                                                 |
| json_loads                 | 29.4 us                                                | 28.0 us: 1.05x faster                                                  |
| sqlglot_parse              | 1.43 ms                                                | 1.38 ms: 1.04x faster                                                  |
| pickle_dict                | 34.8 us                                                | 33.5 us: 1.04x faster                                                  |
| richards_super             | 61.2 ms                                                | 59.1 ms: 1.04x faster                                                  |
| pickle_pure_python         | 319 us                                                 | 308 us: 1.04x faster                                                   |
| sympy_str                  | 299 ms                                                 | 290 ms: 1.03x faster                                                   |
| sqlglot_transpile          | 1.75 ms                                                | 1.70 ms: 1.03x faster                                                  |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.27 sec: 1.03x faster                                                 |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 610 ms: 1.03x faster                                                   |
| async_tree_none_tg         | 490 ms                                                 | 481 ms: 1.02x faster                                                   |
| mdp                        | 2.79 sec                                               | 2.75 sec: 1.01x faster                                                 |
| json                       | 5.24 ms                                                | 5.19 ms: 1.01x faster                                                  |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 743 ms: 1.01x faster                                                   |
| deepcopy                   | 360 us                                                 | 358 us: 1.01x faster                                                   |
| asyncio_websockets         | 556 ms                                                 | 553 ms: 1.00x faster                                                   |
| sqlglot_optimize           | 55.2 ms                                                | 55.3 ms: 1.00x slower                                                  |
| gc_traversal               | 3.90 ms                                                | 3.92 ms: 1.00x slower                                                  |
| create_gc_cycles           | 1.48 ms                                                | 1.49 ms: 1.01x slower                                                  |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 773 ms: 1.01x slower                                                   |
| docutils                   | 2.69 sec                                               | 2.72 sec: 1.01x slower                                                 |
| unpickle_list              | 5.22 us                                                | 5.29 us: 1.01x slower                                                  |
| dask                       | 365 ms                                                 | 370 ms: 1.01x slower                                                   |
| pycparser                  | 1.20 sec                                               | 1.22 sec: 1.02x slower                                                 |
| logging_format             | 6.83 us                                                | 6.98 us: 1.02x slower                                                  |
| sympy_integrate            | 21.4 ms                                                | 21.9 ms: 1.02x slower                                                  |
| pathlib                    | 18.5 ms                                                | 18.9 ms: 1.03x slower                                                  |
| regex_effbot               | 3.45 ms                                                | 3.56 ms: 1.03x slower                                                  |
| bench_thread_pool          | 833 us                                                 | 860 us: 1.03x slower                                                   |
| logging_silent             | 108 ns                                                 | 112 ns: 1.04x slower                                                   |
| pidigits                   | 190 ms                                                 | 198 ms: 1.04x slower                                                   |
| unpickle_pure_python       | 241 us                                                 | 252 us: 1.05x slower                                                   |
| xml_etree_process          | 56.5 ms                                                | 59.3 ms: 1.05x slower                                                  |
| tornado_http               | 97.7 ms                                                | 103 ms: 1.05x slower                                                   |
| xml_etree_iterparse        | 109 ms                                                 | 114 ms: 1.05x slower                                                   |
| dulwich_log                | 64.9 ms                                                | 68.7 ms: 1.06x slower                                                  |
| regex_dna                  | 204 ms                                                 | 216 ms: 1.06x slower                                                   |
| richards                   | 48.9 ms                                                | 52.2 ms: 1.07x slower                                                  |
| raytrace                   | 306 ms                                                 | 328 ms: 1.07x slower                                                   |
| unpickle                   | 13.9 us                                                | 14.9 us: 1.07x slower                                                  |
| unpack_sequence            | 43.3 ns                                                | 46.7 ns: 1.08x slower                                                  |
| regex_v8                   | 22.9 ms                                                | 24.8 ms: 1.08x slower                                                  |
| pickle_list                | 4.65 us                                                | 5.05 us: 1.09x slower                                                  |
| chameleon                  | 6.86 ms                                                | 7.46 ms: 1.09x slower                                                  |
| scimark_lu                 | 112 ms                                                 | 122 ms: 1.09x slower                                                   |
| spectral_norm              | 105 ms                                                 | 114 ms: 1.09x slower                                                   |
| xml_etree_generate         | 80.4 ms                                                | 87.8 ms: 1.09x slower                                                  |
| meteor_contest             | 109 ms                                                 | 121 ms: 1.11x slower                                                   |
| 2to3                       | 266 ms                                                 | 297 ms: 1.12x slower                                                   |
| deepcopy_memo              | 38.9 us                                                | 43.6 us: 1.12x slower                                                  |
| scimark_sor                | 121 ms                                                 | 137 ms: 1.13x slower                                                   |
| sqlite_synth               | 2.58 us                                                | 2.91 us: 1.13x slower                                                  |
| comprehensions             | 23.6 us                                                | 27.2 us: 1.15x slower                                                  |
| coverage                   | 81.2 ms                                                | 95.7 ms: 1.18x slower                                                  |
| pprint_safe_repr           | 743 ms                                                 | 879 ms: 1.18x slower                                                   |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                  |
| chaos                      | 71.4 ms                                                | 85.9 ms: 1.20x slower                                                  |
| pprint_pformat             | 1.53 sec                                               | 1.84 sec: 1.20x slower                                                 |
| regex_compile              | 141 ms                                                 | 171 ms: 1.21x slower                                                   |
| async_generators           | 375 ms                                                 | 457 ms: 1.22x slower                                                   |
| go                         | 143 ms                                                 | 174 ms: 1.22x slower                                                   |
| crypto_pyaes               | 77.5 ms                                                | 98.1 ms: 1.27x slower                                                  |
| fannkuch                   | 410 ms                                                 | 532 ms: 1.30x slower                                                   |
| scimark_monte_carlo        | 71.8 ms                                                | 93.5 ms: 1.30x slower                                                  |
| nqueens                    | 86.8 ms                                                | 115 ms: 1.32x slower                                                   |
| telco                      | 6.72 ms                                                | 8.96 ms: 1.33x slower                                                  |
| tomli_loads                | 2.31 sec                                               | 3.11 sec: 1.34x slower                                                 |
| pyflate                    | 426 ms                                                 | 593 ms: 1.39x slower                                                   |
| python_startup_no_site     | 6.09 ms                                                | 9.05 ms: 1.48x slower                                                  |
| float                      | 78.9 ms                                                | 119 ms: 1.51x slower                                                   |
| nbody                      | 91.6 ms                                                | 142 ms: 1.55x slower                                                   |
| deltablue                  | 3.80 ms                                                | 5.97 ms: 1.57x slower                                                  |
| scimark_fft                | 342 ms                                                 | 540 ms: 1.58x slower                                                   |
| hexiom                     | 6.74 ms                                                | 10.9 ms: 1.62x slower                                                  |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 7.82 ms: 1.63x slower                                                  |
| mako                       | 10.8 ms                                                | 17.7 ms: 1.64x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                           |

Benchmark hidden because not significant (5): sympy_expand, deepcopy_reduce, logging_simple, bench_mp_pool, pickle
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.94% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
