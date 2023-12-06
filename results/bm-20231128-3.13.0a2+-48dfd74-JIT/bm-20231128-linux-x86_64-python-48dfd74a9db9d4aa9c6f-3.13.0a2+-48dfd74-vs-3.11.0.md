
# Results vs. 3.11.0

- fork: python
- ref: 48dfd74a9db9d4aa9c6f
- machine: linux-x86_64
- commit hash: 48dfd74
- commit date: 2023-11-28
- overall geometric mean: 1.05x faster \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 264 ms: 1.01x faster                                                   |
| chameleon      | 6.86 ms                                                | 7.06 ms: 1.03x slower                                                  |
| docutils       | 2.69 sec                                               | 2.60 sec: 1.04x faster                                                 |
| tornado_http   | 97.7 ms                                                | 94.9 ms: 1.03x faster                                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 436 ms: 1.22x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 558 ms: 1.15x faster                                                   |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                                 |
| async_tree_none_tg         | 490 ms                                                 | 453 ms: 1.08x faster                                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.21 sec: 1.08x faster                                                 |
| async_tree_memoization_tg  | 627 ms                                                 | 590 ms: 1.06x faster                                                   |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 706 ms: 1.06x faster                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 739 ms: 1.03x faster                                                   |
| Geometric mean             | (ref)                                                  | 1.10x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| float          | 78.9 ms                                                | 81.5 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 135 ms: 1.05x faster                                                   |
| regex_effbot   | 3.45 ms                                                | 3.62 ms: 1.05x slower                                                  |
| regex_dna      | 204 ms                                                 | 215 ms: 1.05x slower                                                   |
| regex_v8       | 22.9 ms                                                | 25.7 ms: 1.12x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                  |
| unpickle_pure_python | 241 us                                                 | 216 us: 1.11x faster                                                   |
| tomli_loads          | 2.31 sec                                               | 2.15 sec: 1.08x faster                                                 |
| pickle_pure_python   | 319 us                                                 | 302 us: 1.05x faster                                                   |
| pickle_dict          | 34.8 us                                                | 33.4 us: 1.04x faster                                                  |
| json_loads           | 29.4 us                                                | 28.5 us: 1.03x faster                                                  |
| xml_etree_iterparse  | 109 ms                                                 | 105 ms: 1.03x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                                   |
| pickle               | 11.1 us                                                | 11.1 us: 1.00x slower                                                  |
| unpickle_list        | 5.22 us                                                | 5.25 us: 1.01x slower                                                  |
| xml_etree_process    | 56.5 ms                                                | 59.7 ms: 1.06x slower                                                  |
| xml_etree_generate   | 80.4 ms                                                | 87.6 ms: 1.09x slower                                                  |
| pickle_list          | 4.65 us                                                | 5.10 us: 1.10x slower                                                  |
| unpickle             | 13.9 us                                                | 15.4 us: 1.11x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                  |
| python_startup_no_site | 6.09 ms                                                | 8.98 ms: 1.47x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.32x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.6 ms: 1.07x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 119 us: 4.37x faster                                                   |
| generators                 | 76.5 ms                                                | 29.8 ms: 2.57x faster                                                  |
| asyncio_tcp                | 887 ms                                                 | 486 ms: 1.82x faster                                                   |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.78 sec: 1.75x faster                                                 |
| comprehensions             | 23.6 us                                                | 16.4 us: 1.44x faster                                                  |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                  |
| async_tree_none            | 532 ms                                                 | 436 ms: 1.22x faster                                                   |
| coroutines                 | 26.1 ms                                                | 22.1 ms: 1.18x faster                                                  |
| sympy_sum                  | 170 ms                                                 | 147 ms: 1.16x faster                                                   |
| deltablue                  | 3.80 ms                                                | 3.29 ms: 1.16x faster                                                  |
| chaos                      | 71.4 ms                                                | 61.8 ms: 1.16x faster                                                  |
| async_tree_memoization     | 640 ms                                                 | 558 ms: 1.15x faster                                                   |
| richards_super             | 61.2 ms                                                | 54.1 ms: 1.13x faster                                                  |
| sqlglot_parse              | 1.43 ms                                                | 1.28 ms: 1.12x faster                                                  |
| hexiom                     | 6.74 ms                                                | 6.02 ms: 1.12x faster                                                  |
| sympy_str                  | 299 ms                                                 | 268 ms: 1.12x faster                                                   |
| unpickle_pure_python       | 241 us                                                 | 216 us: 1.11x faster                                                   |
| sqlglot_transpile          | 1.75 ms                                                | 1.59 ms: 1.10x faster                                                  |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                                 |
| mdp                        | 2.79 sec                                               | 2.54 sec: 1.10x faster                                                 |
| raytrace                   | 306 ms                                                 | 279 ms: 1.10x faster                                                   |
| sympy_integrate            | 21.4 ms                                                | 19.5 ms: 1.10x faster                                                  |
| crypto_pyaes               | 77.5 ms                                                | 71.4 ms: 1.08x faster                                                  |
| nqueens                    | 86.8 ms                                                | 80.1 ms: 1.08x faster                                                  |
| async_tree_none_tg         | 490 ms                                                 | 453 ms: 1.08x faster                                                   |
| logging_format             | 6.83 us                                                | 6.32 us: 1.08x faster                                                  |
| tomli_loads                | 2.31 sec                                               | 2.15 sec: 1.08x faster                                                 |
| logging_simple             | 6.24 us                                                | 5.80 us: 1.08x faster                                                  |
| async_tree_io_tg           | 1.30 sec                                               | 1.21 sec: 1.08x faster                                                 |
| gc_traversal               | 3.90 ms                                                | 3.64 ms: 1.07x faster                                                  |
| sympy_expand               | 490 ms                                                 | 457 ms: 1.07x faster                                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 590 ms: 1.06x faster                                                   |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 706 ms: 1.06x faster                                                   |
| pickle_pure_python         | 319 us                                                 | 302 us: 1.05x faster                                                   |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.05x faster                                                   |
| regex_compile              | 141 ms                                                 | 135 ms: 1.05x faster                                                   |
| scimark_monte_carlo        | 71.8 ms                                                | 68.6 ms: 1.05x faster                                                  |
| pickle_dict                | 34.8 us                                                | 33.4 us: 1.04x faster                                                  |
| docutils                   | 2.69 sec                                               | 2.60 sec: 1.04x faster                                                 |
| json_loads                 | 29.4 us                                                | 28.5 us: 1.03x faster                                                  |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 739 ms: 1.03x faster                                                   |
| deepcopy                   | 360 us                                                 | 349 us: 1.03x faster                                                   |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                                   |
| xml_etree_iterparse        | 109 ms                                                 | 105 ms: 1.03x faster                                                   |
| richards                   | 48.9 ms                                                | 47.4 ms: 1.03x faster                                                  |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                                   |
| tornado_http               | 97.7 ms                                                | 94.9 ms: 1.03x faster                                                  |
| pathlib                    | 18.5 ms                                                | 18.0 ms: 1.02x faster                                                  |
| sqlglot_optimize           | 55.2 ms                                                | 53.9 ms: 1.02x faster                                                  |
| pprint_pformat             | 1.53 sec                                               | 1.50 sec: 1.02x faster                                                 |
| pidigits                   | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| fannkuch                   | 410 ms                                                 | 404 ms: 1.02x faster                                                   |
| json                       | 5.24 ms                                                | 5.16 ms: 1.02x faster                                                  |
| dask                       | 365 ms                                                 | 360 ms: 1.01x faster                                                   |
| 2to3                       | 266 ms                                                 | 264 ms: 1.01x faster                                                   |
| go                         | 143 ms                                                 | 142 ms: 1.01x faster                                                   |
| pprint_safe_repr           | 743 ms                                                 | 737 ms: 1.01x faster                                                   |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                                  |
| deepcopy_reduce            | 3.14 us                                                | 3.12 us: 1.01x faster                                                  |
| meteor_contest             | 109 ms                                                 | 108 ms: 1.00x faster                                                   |
| bench_thread_pool          | 833 us                                                 | 832 us: 1.00x faster                                                   |
| pickle                     | 11.1 us                                                | 11.1 us: 1.00x slower                                                  |
| unpickle_list              | 5.22 us                                                | 5.25 us: 1.01x slower                                                  |
| dulwich_log                | 64.9 ms                                                | 65.5 ms: 1.01x slower                                                  |
| deepcopy_memo              | 38.9 us                                                | 39.3 us: 1.01x slower                                                  |
| pycparser                  | 1.20 sec                                               | 1.21 sec: 1.01x slower                                                 |
| scimark_sor                | 121 ms                                                 | 124 ms: 1.02x slower                                                   |
| scimark_lu                 | 112 ms                                                 | 115 ms: 1.03x slower                                                   |
| chameleon                  | 6.86 ms                                                | 7.06 ms: 1.03x slower                                                  |
| float                      | 78.9 ms                                                | 81.5 ms: 1.03x slower                                                  |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.00 ms: 1.04x slower                                                  |
| regex_effbot               | 3.45 ms                                                | 3.62 ms: 1.05x slower                                                  |
| regex_dna                  | 204 ms                                                 | 215 ms: 1.05x slower                                                   |
| spectral_norm              | 105 ms                                                 | 111 ms: 1.06x slower                                                   |
| xml_etree_process          | 56.5 ms                                                | 59.7 ms: 1.06x slower                                                  |
| unpack_sequence            | 43.3 ns                                                | 45.9 ns: 1.06x slower                                                  |
| pyflate                    | 426 ms                                                 | 456 ms: 1.07x slower                                                   |
| mako                       | 10.8 ms                                                | 11.6 ms: 1.07x slower                                                  |
| scimark_fft                | 342 ms                                                 | 369 ms: 1.08x slower                                                   |
| xml_etree_generate         | 80.4 ms                                                | 87.6 ms: 1.09x slower                                                  |
| pickle_list                | 4.65 us                                                | 5.10 us: 1.10x slower                                                  |
| sqlite_synth               | 2.58 us                                                | 2.84 us: 1.10x slower                                                  |
| unpickle                   | 13.9 us                                                | 15.4 us: 1.11x slower                                                  |
| regex_v8                   | 22.9 ms                                                | 25.7 ms: 1.12x slower                                                  |
| coverage                   | 81.2 ms                                                | 95.5 ms: 1.18x slower                                                  |
| async_generators           | 375 ms                                                 | 445 ms: 1.19x slower                                                   |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                  |
| telco                      | 6.72 ms                                                | 8.42 ms: 1.25x slower                                                  |
| python_startup_no_site     | 6.09 ms                                                | 8.98 ms: 1.47x slower                                                  |
| mypy2                      | 427 ms                                                 | 842 ms: 1.97x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.05x faster                                                           |

Benchmark hidden because not significant (3): asyncio_websockets, bench_mp_pool, nbody
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
