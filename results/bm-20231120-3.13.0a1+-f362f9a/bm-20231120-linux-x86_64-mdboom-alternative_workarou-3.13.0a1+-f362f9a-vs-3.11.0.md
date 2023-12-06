
# Results vs. 3.11.0

- fork: mdboom
- ref: alternative_workarou
- machine: linux-x86_64
- commit hash: f362f9a
- commit date: 2023-11-20
- overall geometric mean: 1.06x faster \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 264 ms: 1.01x faster                                                   |
| chameleon      | 6.86 ms                                                | 6.93 ms: 1.01x slower                                                  |
| docutils       | 2.69 sec                                               | 2.60 sec: 1.03x faster                                                 |
| tornado_http   | 97.7 ms                                                | 95.2 ms: 1.03x faster                                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 433 ms: 1.23x faster                                                   |
| async_tree_memoization     | 640 ms                                                 | 559 ms: 1.15x faster                                                   |
| async_tree_io              | 1.31 sec                                               | 1.18 sec: 1.11x faster                                                 |
| async_tree_none_tg         | 490 ms                                                 | 454 ms: 1.08x faster                                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.21 sec: 1.08x faster                                                 |
| async_tree_memoization_tg  | 627 ms                                                 | 591 ms: 1.06x faster                                                   |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 711 ms: 1.05x faster                                                   |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 740 ms: 1.03x faster                                                   |
| Geometric mean             | (ref)                                                  | 1.10x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 91.6 ms                                                | 89.9 ms: 1.02x faster                                                  |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| float          | 78.9 ms                                                | 81.6 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 133 ms: 1.06x faster                                                   |
| regex_dna      | 204 ms                                                 | 215 ms: 1.05x slower                                                   |
| regex_effbot   | 3.45 ms                                                | 3.64 ms: 1.06x slower                                                  |
| regex_v8       | 22.9 ms                                                | 25.6 ms: 1.12x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                  |
| unpickle_pure_python | 241 us                                                 | 221 us: 1.09x faster                                                   |
| tomli_loads          | 2.31 sec                                               | 2.15 sec: 1.08x faster                                                 |
| pickle_pure_python   | 319 us                                                 | 304 us: 1.05x faster                                                   |
| json_loads           | 29.4 us                                                | 28.1 us: 1.05x faster                                                  |
| pickle_dict          | 34.8 us                                                | 33.3 us: 1.04x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                                   |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.02x faster                                                   |
| unpickle_list        | 5.22 us                                                | 5.15 us: 1.01x faster                                                  |
| pickle               | 11.1 us                                                | 11.4 us: 1.03x slower                                                  |
| xml_etree_process    | 56.5 ms                                                | 60.1 ms: 1.06x slower                                                  |
| pickle_list          | 4.65 us                                                | 4.97 us: 1.07x slower                                                  |
| xml_etree_generate   | 80.4 ms                                                | 86.6 ms: 1.08x slower                                                  |
| unpickle             | 13.9 us                                                | 15.9 us: 1.14x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                  |
| python_startup_no_site | 6.09 ms                                                | 9.03 ms: 1.48x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 11.4 ms: 1.05x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 116 us: 4.50x faster                                                   |
| generators                 | 76.5 ms                                                | 30.0 ms: 2.55x faster                                                  |
| asyncio_tcp                | 887 ms                                                 | 486 ms: 1.82x faster                                                   |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.79 sec: 1.75x faster                                                 |
| comprehensions             | 23.6 us                                                | 16.5 us: 1.43x faster                                                  |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                                  |
| mypy2                      | 427 ms                                                 | 342 ms: 1.25x faster                                                   |
| async_tree_none            | 532 ms                                                 | 433 ms: 1.23x faster                                                   |
| coroutines                 | 26.1 ms                                                | 21.8 ms: 1.20x faster                                                  |
| chaos                      | 71.4 ms                                                | 61.1 ms: 1.17x faster                                                  |
| sympy_sum                  | 170 ms                                                 | 147 ms: 1.16x faster                                                   |
| richards_super             | 61.2 ms                                                | 53.3 ms: 1.15x faster                                                  |
| async_tree_memoization     | 640 ms                                                 | 559 ms: 1.15x faster                                                   |
| deltablue                  | 3.80 ms                                                | 3.33 ms: 1.14x faster                                                  |
| sqlglot_parse              | 1.43 ms                                                | 1.27 ms: 1.13x faster                                                  |
| sympy_str                  | 299 ms                                                 | 267 ms: 1.12x faster                                                   |
| raytrace                   | 306 ms                                                 | 275 ms: 1.11x faster                                                   |
| async_tree_io              | 1.31 sec                                               | 1.18 sec: 1.11x faster                                                 |
| sqlglot_transpile          | 1.75 ms                                                | 1.59 ms: 1.11x faster                                                  |
| logging_simple             | 6.24 us                                                | 5.68 us: 1.10x faster                                                  |
| sympy_integrate            | 21.4 ms                                                | 19.5 ms: 1.10x faster                                                  |
| logging_format             | 6.83 us                                                | 6.23 us: 1.10x faster                                                  |
| unpickle_pure_python       | 241 us                                                 | 221 us: 1.09x faster                                                   |
| hexiom                     | 6.74 ms                                                | 6.18 ms: 1.09x faster                                                  |
| sympy_expand               | 490 ms                                                 | 450 ms: 1.09x faster                                                   |
| async_tree_none_tg         | 490 ms                                                 | 454 ms: 1.08x faster                                                   |
| async_tree_io_tg           | 1.30 sec                                               | 1.21 sec: 1.08x faster                                                 |
| tomli_loads                | 2.31 sec                                               | 2.15 sec: 1.08x faster                                                 |
| nqueens                    | 86.8 ms                                                | 80.7 ms: 1.08x faster                                                  |
| gc_traversal               | 3.90 ms                                                | 3.64 ms: 1.07x faster                                                  |
| crypto_pyaes               | 77.5 ms                                                | 72.3 ms: 1.07x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 105 ms: 1.07x faster                                                   |
| regex_compile              | 141 ms                                                 | 133 ms: 1.06x faster                                                   |
| async_tree_memoization_tg  | 627 ms                                                 | 591 ms: 1.06x faster                                                   |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 711 ms: 1.05x faster                                                   |
| pickle_pure_python         | 319 us                                                 | 304 us: 1.05x faster                                                   |
| scimark_monte_carlo        | 71.8 ms                                                | 68.4 ms: 1.05x faster                                                  |
| json_loads                 | 29.4 us                                                | 28.1 us: 1.05x faster                                                  |
| pickle_dict                | 34.8 us                                                | 33.3 us: 1.04x faster                                                  |
| deepcopy                   | 360 us                                                 | 346 us: 1.04x faster                                                   |
| richards                   | 48.9 ms                                                | 47.1 ms: 1.04x faster                                                  |
| sqlglot_optimize           | 55.2 ms                                                | 53.4 ms: 1.03x faster                                                  |
| docutils                   | 2.69 sec                                               | 2.60 sec: 1.03x faster                                                 |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 740 ms: 1.03x faster                                                   |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                                   |
| json                       | 5.24 ms                                                | 5.10 ms: 1.03x faster                                                  |
| fannkuch                   | 410 ms                                                 | 399 ms: 1.03x faster                                                   |
| tornado_http               | 97.7 ms                                                | 95.2 ms: 1.03x faster                                                  |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.03x faster                                                   |
| pprint_pformat             | 1.53 sec                                               | 1.49 sec: 1.02x faster                                                 |
| xml_etree_iterparse        | 109 ms                                                 | 106 ms: 1.02x faster                                                   |
| mdp                        | 2.79 sec                                               | 2.72 sec: 1.02x faster                                                 |
| meteor_contest             | 109 ms                                                 | 107 ms: 1.02x faster                                                   |
| deepcopy_reduce            | 3.14 us                                                | 3.08 us: 1.02x faster                                                  |
| nbody                      | 91.6 ms                                                | 89.9 ms: 1.02x faster                                                  |
| deepcopy_memo              | 38.9 us                                                | 38.2 us: 1.02x faster                                                  |
| go                         | 143 ms                                                 | 141 ms: 1.02x faster                                                   |
| pathlib                    | 18.5 ms                                                | 18.2 ms: 1.02x faster                                                  |
| pprint_safe_repr           | 743 ms                                                 | 732 ms: 1.01x faster                                                   |
| unpickle_list              | 5.22 us                                                | 5.15 us: 1.01x faster                                                  |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                                  |
| dask                       | 365 ms                                                 | 361 ms: 1.01x faster                                                   |
| 2to3                       | 266 ms                                                 | 264 ms: 1.01x faster                                                   |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                                   |
| bench_thread_pool          | 833 us                                                 | 836 us: 1.00x slower                                                   |
| chameleon                  | 6.86 ms                                                | 6.93 ms: 1.01x slower                                                  |
| pycparser                  | 1.20 sec                                               | 1.21 sec: 1.01x slower                                                 |
| dulwich_log                | 64.9 ms                                                | 65.9 ms: 1.01x slower                                                  |
| scimark_sor                | 121 ms                                                 | 124 ms: 1.02x slower                                                   |
| pidigits                   | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| pickle                     | 11.1 us                                                | 11.4 us: 1.03x slower                                                  |
| scimark_lu                 | 112 ms                                                 | 116 ms: 1.03x slower                                                   |
| float                      | 78.9 ms                                                | 81.6 ms: 1.03x slower                                                  |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 4.97 ms: 1.03x slower                                                  |
| unpack_sequence            | 43.3 ns                                                | 45.3 ns: 1.05x slower                                                  |
| mako                       | 10.8 ms                                                | 11.4 ms: 1.05x slower                                                  |
| regex_dna                  | 204 ms                                                 | 215 ms: 1.05x slower                                                   |
| regex_effbot               | 3.45 ms                                                | 3.64 ms: 1.06x slower                                                  |
| xml_etree_process          | 56.5 ms                                                | 60.1 ms: 1.06x slower                                                  |
| pickle_list                | 4.65 us                                                | 4.97 us: 1.07x slower                                                  |
| spectral_norm              | 105 ms                                                 | 113 ms: 1.07x slower                                                   |
| scimark_fft                | 342 ms                                                 | 368 ms: 1.08x slower                                                   |
| xml_etree_generate         | 80.4 ms                                                | 86.6 ms: 1.08x slower                                                  |
| pyflate                    | 426 ms                                                 | 468 ms: 1.10x slower                                                   |
| sqlite_synth               | 2.58 us                                                | 2.85 us: 1.10x slower                                                  |
| regex_v8                   | 22.9 ms                                                | 25.6 ms: 1.12x slower                                                  |
| unpickle                   | 13.9 us                                                | 15.9 us: 1.14x slower                                                  |
| async_generators           | 375 ms                                                 | 443 ms: 1.18x slower                                                   |
| coverage                   | 81.2 ms                                                | 96.3 ms: 1.19x slower                                                  |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                  |
| telco                      | 6.72 ms                                                | 8.37 ms: 1.25x slower                                                  |
| python_startup_no_site     | 6.09 ms                                                | 9.03 ms: 1.48x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.06x faster                                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
