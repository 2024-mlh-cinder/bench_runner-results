
# Results vs. 3.11.0

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: linux-x86_64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 261 ms: 1.02x faster                                                   |
| chameleon      | 6.86 ms                                                | 6.96 ms: 1.01x slower                                                  |
| docutils       | 2.69 sec                                               | 2.59 sec: 1.04x faster                                                 |
| tornado_http   | 97.7 ms                                                | 94.4 ms: 1.04x faster                                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 435 ms: 1.22x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 559 ms: 1.15x faster                                                   |
| async_tree_io              | 1.31 sec                                               | 1.18 sec: 1.11x faster                                                 |
| async_tree_none_tg         | 490 ms                                                 | 455 ms: 1.08x faster                                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.22 sec: 1.07x faster                                                 |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 709 ms: 1.06x faster                                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 594 ms: 1.06x faster                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 738 ms: 1.04x faster                                                   |
| Geometric mean             | (ref)                                                  | 1.09x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 91.6 ms                                                | 88.2 ms: 1.04x faster                                                  |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| float          | 78.9 ms                                                | 81.1 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 134 ms: 1.06x faster                                                   |
| regex_dna      | 204 ms                                                 | 212 ms: 1.04x slower                                                   |
| regex_effbot   | 3.45 ms                                                | 3.61 ms: 1.05x slower                                                  |
| regex_v8       | 22.9 ms                                                | 25.7 ms: 1.12x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.3 ms: 1.31x faster                                                  |
| unpickle_pure_python | 241 us                                                 | 219 us: 1.10x faster                                                   |
| tomli_loads          | 2.31 sec                                               | 2.14 sec: 1.08x faster                                                 |
| json_loads           | 29.4 us                                                | 27.9 us: 1.05x faster                                                  |
| pickle_pure_python   | 319 us                                                 | 303 us: 1.05x faster                                                   |
| xml_etree_iterparse  | 109 ms                                                 | 105 ms: 1.04x faster                                                   |
| pickle_dict          | 34.8 us                                                | 33.9 us: 1.03x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                                   |
| unpickle_list        | 5.22 us                                                | 5.30 us: 1.02x slower                                                  |
| pickle               | 11.1 us                                                | 11.3 us: 1.02x slower                                                  |
| xml_etree_process    | 56.5 ms                                                | 59.0 ms: 1.04x slower                                                  |
| unpickle             | 13.9 us                                                | 14.6 us: 1.05x slower                                                  |
| xml_etree_generate   | 80.4 ms                                                | 85.8 ms: 1.07x slower                                                  |
| pickle_list          | 4.65 us                                                | 5.03 us: 1.08x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.03x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                  |
| python_startup_no_site | 6.09 ms                                                | 9.02 ms: 1.48x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.4 ms: 1.05x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 116 us: 4.51x faster                                                   |
| generators                 | 76.5 ms                                                | 28.8 ms: 2.65x faster                                                  |
| asyncio_tcp                | 887 ms                                                 | 482 ms: 1.84x faster                                                   |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.78 sec: 1.75x faster                                                 |
| comprehensions             | 23.6 us                                                | 16.4 us: 1.44x faster                                                  |
| json_dumps                 | 13.5 ms                                                | 10.3 ms: 1.31x faster                                                  |
| mypy2                      | 427 ms                                                 | 339 ms: 1.26x faster                                                   |
| async_tree_none            | 532 ms                                                 | 435 ms: 1.22x faster                                                   |
| coroutines                 | 26.1 ms                                                | 22.0 ms: 1.19x faster                                                  |
| chaos                      | 71.4 ms                                                | 60.2 ms: 1.19x faster                                                  |
| sympy_sum                  | 170 ms                                                 | 147 ms: 1.16x faster                                                   |
| deltablue                  | 3.80 ms                                                | 3.29 ms: 1.16x faster                                                  |
| async_tree_memoization     | 640 ms                                                 | 559 ms: 1.15x faster                                                   |
| sqlglot_parse              | 1.43 ms                                                | 1.27 ms: 1.13x faster                                                  |
| richards_super             | 61.2 ms                                                | 54.3 ms: 1.13x faster                                                  |
| sympy_str                  | 299 ms                                                 | 268 ms: 1.12x faster                                                   |
| raytrace                   | 306 ms                                                 | 275 ms: 1.11x faster                                                   |
| sqlglot_transpile          | 1.75 ms                                                | 1.58 ms: 1.11x faster                                                  |
| async_tree_io              | 1.31 sec                                               | 1.18 sec: 1.11x faster                                                 |
| sympy_integrate            | 21.4 ms                                                | 19.3 ms: 1.11x faster                                                  |
| logging_format             | 6.83 us                                                | 6.21 us: 1.10x faster                                                  |
| unpickle_pure_python       | 241 us                                                 | 219 us: 1.10x faster                                                   |
| logging_simple             | 6.24 us                                                | 5.69 us: 1.10x faster                                                  |
| mdp                        | 2.79 sec                                               | 2.55 sec: 1.09x faster                                                 |
| hexiom                     | 6.74 ms                                                | 6.17 ms: 1.09x faster                                                  |
| sympy_expand               | 490 ms                                                 | 450 ms: 1.09x faster                                                   |
| crypto_pyaes               | 77.5 ms                                                | 71.3 ms: 1.09x faster                                                  |
| tomli_loads                | 2.31 sec                                               | 2.14 sec: 1.08x faster                                                 |
| async_tree_none_tg         | 490 ms                                                 | 455 ms: 1.08x faster                                                   |
| sqlglot_normalize          | 112 ms                                                 | 105 ms: 1.07x faster                                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.22 sec: 1.07x faster                                                 |
| nqueens                    | 86.8 ms                                                | 81.7 ms: 1.06x faster                                                  |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 709 ms: 1.06x faster                                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 594 ms: 1.06x faster                                                   |
| regex_compile              | 141 ms                                                 | 134 ms: 1.06x faster                                                   |
| json_loads                 | 29.4 us                                                | 27.9 us: 1.05x faster                                                  |
| pickle_pure_python         | 319 us                                                 | 303 us: 1.05x faster                                                   |
| deepcopy                   | 360 us                                                 | 343 us: 1.05x faster                                                   |
| scimark_monte_carlo        | 71.8 ms                                                | 68.5 ms: 1.05x faster                                                  |
| fannkuch                   | 410 ms                                                 | 394 ms: 1.04x faster                                                   |
| docutils                   | 2.69 sec                                               | 2.59 sec: 1.04x faster                                                 |
| logging_silent             | 108 ns                                                 | 104 ns: 1.04x faster                                                   |
| nbody                      | 91.6 ms                                                | 88.2 ms: 1.04x faster                                                  |
| xml_etree_iterparse        | 109 ms                                                 | 105 ms: 1.04x faster                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 738 ms: 1.04x faster                                                   |
| tornado_http               | 97.7 ms                                                | 94.4 ms: 1.04x faster                                                  |
| sqlglot_optimize           | 55.2 ms                                                | 53.3 ms: 1.03x faster                                                  |
| deepcopy_reduce            | 3.14 us                                                | 3.04 us: 1.03x faster                                                  |
| pycparser                  | 1.20 sec                                               | 1.16 sec: 1.03x faster                                                 |
| pickle_dict                | 34.8 us                                                | 33.9 us: 1.03x faster                                                  |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                                   |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 4.68 ms: 1.03x faster                                                  |
| richards                   | 48.9 ms                                                | 47.7 ms: 1.03x faster                                                  |
| go                         | 143 ms                                                 | 140 ms: 1.02x faster                                                   |
| pprint_pformat             | 1.53 sec                                               | 1.49 sec: 1.02x faster                                                 |
| json                       | 5.24 ms                                                | 5.13 ms: 1.02x faster                                                  |
| 2to3                       | 266 ms                                                 | 261 ms: 1.02x faster                                                   |
| pprint_safe_repr           | 743 ms                                                 | 733 ms: 1.01x faster                                                   |
| pidigits                   | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| deepcopy_memo              | 38.9 us                                                | 38.4 us: 1.01x faster                                                  |
| scimark_sor                | 121 ms                                                 | 121 ms: 1.01x faster                                                   |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                                   |
| bench_thread_pool          | 833 us                                                 | 828 us: 1.01x faster                                                   |
| meteor_contest             | 109 ms                                                 | 109 ms: 1.00x faster                                                   |
| dulwich_log                | 64.9 ms                                                | 65.5 ms: 1.01x slower                                                  |
| chameleon                  | 6.86 ms                                                | 6.96 ms: 1.01x slower                                                  |
| unpickle_list              | 5.22 us                                                | 5.30 us: 1.02x slower                                                  |
| scimark_lu                 | 112 ms                                                 | 114 ms: 1.02x slower                                                   |
| pickle                     | 11.1 us                                                | 11.3 us: 1.02x slower                                                  |
| float                      | 78.9 ms                                                | 81.1 ms: 1.03x slower                                                  |
| pathlib                    | 18.5 ms                                                | 19.0 ms: 1.03x slower                                                  |
| gc_traversal               | 3.90 ms                                                | 4.04 ms: 1.03x slower                                                  |
| regex_dna                  | 204 ms                                                 | 212 ms: 1.04x slower                                                   |
| xml_etree_process          | 56.5 ms                                                | 59.0 ms: 1.04x slower                                                  |
| regex_effbot               | 3.45 ms                                                | 3.61 ms: 1.05x slower                                                  |
| unpickle                   | 13.9 us                                                | 14.6 us: 1.05x slower                                                  |
| mako                       | 10.8 ms                                                | 11.4 ms: 1.05x slower                                                  |
| scimark_fft                | 342 ms                                                 | 364 ms: 1.06x slower                                                   |
| unpack_sequence            | 43.3 ns                                                | 46.1 ns: 1.07x slower                                                  |
| xml_etree_generate         | 80.4 ms                                                | 85.8 ms: 1.07x slower                                                  |
| spectral_norm              | 105 ms                                                 | 112 ms: 1.07x slower                                                   |
| pickle_list                | 4.65 us                                                | 5.03 us: 1.08x slower                                                  |
| sqlite_synth               | 2.58 us                                                | 2.82 us: 1.09x slower                                                  |
| pyflate                    | 426 ms                                                 | 468 ms: 1.10x slower                                                   |
| regex_v8                   | 22.9 ms                                                | 25.7 ms: 1.12x slower                                                  |
| coverage                   | 81.2 ms                                                | 96.1 ms: 1.18x slower                                                  |
| async_generators           | 375 ms                                                 | 445 ms: 1.19x slower                                                   |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.19x slower                                                  |
| telco                      | 6.72 ms                                                | 8.29 ms: 1.23x slower                                                  |
| python_startup_no_site     | 6.09 ms                                                | 9.02 ms: 1.48x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.07x faster                                                           |

Benchmark hidden because not significant (2): bench_mp_pool, create_gc_cycles
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
