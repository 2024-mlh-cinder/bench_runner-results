
# Results vs. 3.11.0

- fork: iritkatriel
- ref: gen_close
- machine: linux-x86_64
- commit hash: 03335e6
- commit date: 2023-10-26
- overall geometric mean: 1.06x faster
- HPT reliability: 99.98%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 264 ms: 1.01x faster                                             |
| chameleon      | 6.86 ms                                                | 6.97 ms: 1.02x slower                                            |
| docutils       | 2.69 sec                                               | 2.65 sec: 1.02x faster                                           |
| tornado_http   | 97.7 ms                                                | 95.7 ms: 1.02x faster                                            |
| Geometric mean | (ref)                                                  | 1.01x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 437 ms: 1.22x faster                                             |
| async_tree_memoization     | 640 ms                                                 | 563 ms: 1.14x faster                                             |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                           |
| async_tree_none_tg         | 490 ms                                                 | 455 ms: 1.08x faster                                             |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                           |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 712 ms: 1.05x faster                                             |
| async_tree_memoization_tg  | 627 ms                                                 | 596 ms: 1.05x faster                                             |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 743 ms: 1.03x faster                                             |
| Geometric mean             | (ref)                                                  | 1.09x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                             |
| float          | 78.9 ms                                                | 81.4 ms: 1.03x slower                                            |
| Geometric mean | (ref)                                                  | 1.00x slower                                                     |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 138 ms: 1.03x faster                                             |
| regex_dna      | 204 ms                                                 | 212 ms: 1.04x slower                                             |
| regex_effbot   | 3.45 ms                                                | 3.65 ms: 1.06x slower                                            |
| regex_v8       | 22.9 ms                                                | 25.5 ms: 1.11x slower                                            |
| Geometric mean | (ref)                                                  | 1.05x slower                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.29x faster                                            |
| unpickle_pure_python | 241 us                                                 | 220 us: 1.10x faster                                             |
| tomli_loads          | 2.31 sec                                               | 2.14 sec: 1.08x faster                                           |
| pickle_dict          | 34.8 us                                                | 32.8 us: 1.06x faster                                            |
| pickle_pure_python   | 319 us                                                 | 300 us: 1.06x faster                                             |
| json_loads           | 29.4 us                                                | 28.0 us: 1.05x faster                                            |
| xml_etree_iterparse  | 109 ms                                                 | 105 ms: 1.03x faster                                             |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                             |
| unpickle_list        | 5.22 us                                                | 5.08 us: 1.03x faster                                            |
| xml_etree_process    | 56.5 ms                                                | 58.8 ms: 1.04x slower                                            |
| pickle_list          | 4.65 us                                                | 4.95 us: 1.07x slower                                            |
| unpickle             | 13.9 us                                                | 14.8 us: 1.07x slower                                            |
| xml_etree_generate   | 80.4 ms                                                | 86.1 ms: 1.07x slower                                            |
| Geometric mean       | (ref)                                                  | 1.03x faster                                                     |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.3 ms: 1.18x slower                                            |
| python_startup_no_site | 6.09 ms                                                | 8.94 ms: 1.47x slower                                            |
| Geometric mean         | (ref)                                                  | 1.32x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.5 ms: 1.06x slower                                            |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 152 us: 3.44x faster                                             |
| generators                 | 76.5 ms                                                | 29.6 ms: 2.58x faster                                            |
| asyncio_tcp                | 887 ms                                                 | 479 ms: 1.85x faster                                             |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.78 sec: 1.76x faster                                           |
| comprehensions             | 23.6 us                                                | 16.7 us: 1.41x faster                                            |
| json_dumps                 | 13.5 ms                                                | 10.4 ms: 1.29x faster                                            |
| mypy2                      | 427 ms                                                 | 343 ms: 1.25x faster                                             |
| async_tree_none            | 532 ms                                                 | 437 ms: 1.22x faster                                             |
| chaos                      | 71.4 ms                                                | 61.4 ms: 1.16x faster                                            |
| coroutines                 | 26.1 ms                                                | 22.5 ms: 1.16x faster                                            |
| sympy_sum                  | 170 ms                                                 | 148 ms: 1.15x faster                                             |
| async_tree_memoization     | 640 ms                                                 | 563 ms: 1.14x faster                                             |
| deltablue                  | 3.80 ms                                                | 3.38 ms: 1.12x faster                                            |
| sympy_str                  | 299 ms                                                 | 266 ms: 1.12x faster                                             |
| richards_super             | 61.2 ms                                                | 55.0 ms: 1.11x faster                                            |
| raytrace                   | 306 ms                                                 | 276 ms: 1.11x faster                                             |
| async_tree_io              | 1.31 sec                                               | 1.19 sec: 1.10x faster                                           |
| mdp                        | 2.79 sec                                               | 2.54 sec: 1.10x faster                                           |
| sqlglot_parse              | 1.43 ms                                                | 1.31 ms: 1.10x faster                                            |
| unpickle_pure_python       | 241 us                                                 | 220 us: 1.10x faster                                             |
| hexiom                     | 6.74 ms                                                | 6.20 ms: 1.09x faster                                            |
| sympy_integrate            | 21.4 ms                                                | 19.7 ms: 1.09x faster                                            |
| sqlglot_transpile          | 1.75 ms                                                | 1.62 ms: 1.08x faster                                            |
| sympy_expand               | 490 ms                                                 | 452 ms: 1.08x faster                                             |
| crypto_pyaes               | 77.5 ms                                                | 71.5 ms: 1.08x faster                                            |
| tomli_loads                | 2.31 sec                                               | 2.14 sec: 1.08x faster                                           |
| nqueens                    | 86.8 ms                                                | 80.4 ms: 1.08x faster                                            |
| async_tree_none_tg         | 490 ms                                                 | 455 ms: 1.08x faster                                             |
| sqlglot_normalize          | 112 ms                                                 | 105 ms: 1.07x faster                                             |
| pickle_dict                | 34.8 us                                                | 32.8 us: 1.06x faster                                            |
| pickle_pure_python         | 319 us                                                 | 300 us: 1.06x faster                                             |
| logging_format             | 6.83 us                                                | 6.43 us: 1.06x faster                                            |
| async_tree_io_tg           | 1.30 sec                                               | 1.23 sec: 1.06x faster                                           |
| logging_simple             | 6.24 us                                                | 5.91 us: 1.06x faster                                            |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 712 ms: 1.05x faster                                             |
| async_tree_memoization_tg  | 627 ms                                                 | 596 ms: 1.05x faster                                             |
| json_loads                 | 29.4 us                                                | 28.0 us: 1.05x faster                                            |
| scimark_monte_carlo        | 71.8 ms                                                | 69.1 ms: 1.04x faster                                            |
| logging_silent             | 108 ns                                                 | 105 ns: 1.04x faster                                             |
| sqlglot_optimize           | 55.2 ms                                                | 53.2 ms: 1.04x faster                                            |
| xml_etree_iterparse        | 109 ms                                                 | 105 ms: 1.03x faster                                             |
| pycparser                  | 1.20 sec                                               | 1.16 sec: 1.03x faster                                           |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 743 ms: 1.03x faster                                             |
| xml_etree_parse            | 163 ms                                                 | 158 ms: 1.03x faster                                             |
| deepcopy                   | 360 us                                                 | 350 us: 1.03x faster                                             |
| unpickle_list              | 5.22 us                                                | 5.08 us: 1.03x faster                                            |
| regex_compile              | 141 ms                                                 | 138 ms: 1.03x faster                                             |
| fannkuch                   | 410 ms                                                 | 401 ms: 1.02x faster                                             |
| bench_thread_pool          | 833 us                                                 | 815 us: 1.02x faster                                             |
| tornado_http               | 97.7 ms                                                | 95.7 ms: 1.02x faster                                            |
| meteor_contest             | 109 ms                                                 | 107 ms: 1.02x faster                                             |
| pprint_pformat             | 1.53 sec                                               | 1.50 sec: 1.02x faster                                           |
| docutils                   | 2.69 sec                                               | 2.65 sec: 1.02x faster                                           |
| pidigits                   | 190 ms                                                 | 187 ms: 1.02x faster                                             |
| create_gc_cycles           | 1.48 ms                                                | 1.45 ms: 1.01x faster                                            |
| json                       | 5.24 ms                                                | 5.17 ms: 1.01x faster                                            |
| deepcopy_memo              | 38.9 us                                                | 38.5 us: 1.01x faster                                            |
| pprint_safe_repr           | 743 ms                                                 | 737 ms: 1.01x faster                                             |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                             |
| 2to3                       | 266 ms                                                 | 264 ms: 1.01x faster                                             |
| go                         | 143 ms                                                 | 145 ms: 1.01x slower                                             |
| chameleon                  | 6.86 ms                                                | 6.97 ms: 1.02x slower                                            |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 4.90 ms: 1.02x slower                                            |
| pathlib                    | 18.5 ms                                                | 18.9 ms: 1.02x slower                                            |
| dulwich_log                | 64.9 ms                                                | 66.4 ms: 1.02x slower                                            |
| scimark_lu                 | 112 ms                                                 | 116 ms: 1.03x slower                                             |
| scimark_sor                | 121 ms                                                 | 125 ms: 1.03x slower                                             |
| float                      | 78.9 ms                                                | 81.4 ms: 1.03x slower                                            |
| unpack_sequence            | 43.3 ns                                                | 44.7 ns: 1.03x slower                                            |
| regex_dna                  | 204 ms                                                 | 212 ms: 1.04x slower                                             |
| xml_etree_process          | 56.5 ms                                                | 58.8 ms: 1.04x slower                                            |
| gc_traversal               | 3.90 ms                                                | 4.08 ms: 1.04x slower                                            |
| spectral_norm              | 105 ms                                                 | 110 ms: 1.05x slower                                             |
| mako                       | 10.8 ms                                                | 11.5 ms: 1.06x slower                                            |
| regex_effbot               | 3.45 ms                                                | 3.65 ms: 1.06x slower                                            |
| pickle_list                | 4.65 us                                                | 4.95 us: 1.07x slower                                            |
| unpickle                   | 13.9 us                                                | 14.8 us: 1.07x slower                                            |
| xml_etree_generate         | 80.4 ms                                                | 86.1 ms: 1.07x slower                                            |
| sqlite_synth               | 2.58 us                                                | 2.78 us: 1.08x slower                                            |
| scimark_fft                | 342 ms                                                 | 377 ms: 1.10x slower                                             |
| pyflate                    | 426 ms                                                 | 470 ms: 1.10x slower                                             |
| regex_v8                   | 22.9 ms                                                | 25.5 ms: 1.11x slower                                            |
| coverage                   | 81.2 ms                                                | 94.3 ms: 1.16x slower                                            |
| python_startup             | 8.69 ms                                                | 10.3 ms: 1.18x slower                                            |
| async_generators           | 375 ms                                                 | 458 ms: 1.22x slower                                             |
| telco                      | 6.72 ms                                                | 8.32 ms: 1.24x slower                                            |
| python_startup_no_site     | 6.09 ms                                                | 8.94 ms: 1.47x slower                                            |
| Geometric mean             | (ref)                                                  | 1.06x faster                                                     |

Benchmark hidden because not significant (5): deepcopy_reduce, nbody, richards, bench_mp_pool, pickle
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
