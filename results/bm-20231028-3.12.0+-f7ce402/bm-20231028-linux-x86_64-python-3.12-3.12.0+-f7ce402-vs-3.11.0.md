
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.02x faster
- HPT reliability: 59.86%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 266 ms                                                 | 275 ms: 1.03x slower                                 |
| chameleon      | 6.86 ms                                                | 7.47 ms: 1.09x slower                                |
| docutils       | 2.69 sec                                               | 2.73 sec: 1.01x slower                               |
| tornado_http   | 97.7 ms                                                | 100 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.04x slower                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 474 ms: 1.12x faster                                 |
| async_tree_io              | 1.31 sec                                               | 1.17 sec: 1.12x faster                               |
| async_tree_memoization     | 640 ms                                                 | 579 ms: 1.10x faster                                 |
| async_tree_none_tg         | 490 ms                                                 | 448 ms: 1.09x faster                                 |
| async_tree_io_tg           | 1.30 sec                                               | 1.19 sec: 1.09x faster                               |
| async_tree_memoization_tg  | 627 ms                                                 | 574 ms: 1.09x faster                                 |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 725 ms: 1.05x faster                                 |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 726 ms: 1.03x faster                                 |
| Geometric mean             | (ref)                                                  | 1.09x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                 |
| nbody          | 91.6 ms                                                | 97.8 ms: 1.07x slower                                |
| float          | 78.9 ms                                                | 84.6 ms: 1.07x slower                                |
| Geometric mean | (ref)                                                  | 1.04x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_v8       | 22.9 ms                                                | 23.2 ms: 1.01x slower                                |
| regex_dna      | 204 ms                                                 | 209 ms: 1.02x slower                                 |
| regex_compile  | 141 ms                                                 | 147 ms: 1.04x slower                                 |
| regex_effbot   | 3.45 ms                                                | 3.58 ms: 1.04x slower                                |
| Geometric mean | (ref)                                                  | 1.03x slower                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                |
| unpickle_pure_python | 241 us                                                 | 229 us: 1.05x faster                                 |
| json_loads           | 29.4 us                                                | 28.2 us: 1.04x faster                                |
| pickle_dict          | 34.8 us                                                | 33.5 us: 1.04x faster                                |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.02x faster                                 |
| unpickle_list        | 5.22 us                                                | 5.12 us: 1.02x faster                                |
| pickle_pure_python   | 319 us                                                 | 323 us: 1.01x slower                                 |
| tomli_loads          | 2.31 sec                                               | 2.35 sec: 1.02x slower                               |
| pickle               | 11.1 us                                                | 11.4 us: 1.03x slower                                |
| pickle_list          | 4.65 us                                                | 4.94 us: 1.06x slower                                |
| xml_etree_process    | 56.5 ms                                                | 61.0 ms: 1.08x slower                                |
| xml_etree_generate   | 80.4 ms                                                | 88.5 ms: 1.10x slower                                |
| unpickle             | 13.9 us                                                | 16.3 us: 1.18x slower                                |
| Geometric mean       | (ref)                                                  | 1.00x slower                                         |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 9.62 ms: 1.11x slower                                |
| python_startup_no_site | 6.09 ms                                                | 6.97 ms: 1.14x slower                                |
| Geometric mean         | (ref)                                                  | 1.13x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| django_template | 33.8 ms                                                | 34.7 ms: 1.03x slower                                |
| mako            | 10.8 ms                                                | 11.4 ms: 1.05x slower                                |
| Geometric mean  | (ref)                                                  | 1.04x slower                                         |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 156 us: 3.34x faster                                 |
| generators                 | 76.5 ms                                                | 31.1 ms: 2.46x faster                                |
| asyncio_tcp                | 887 ms                                                 | 503 ms: 1.76x faster                                 |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.79 sec: 1.75x faster                               |
| json_dumps                 | 13.5 ms                                                | 10.5 ms: 1.28x faster                                |
| richards_super             | 61.2 ms                                                | 51.3 ms: 1.19x faster                                |
| async_tree_none            | 532 ms                                                 | 474 ms: 1.12x faster                                 |
| async_tree_io              | 1.31 sec                                               | 1.17 sec: 1.12x faster                               |
| coroutines                 | 26.1 ms                                                | 23.6 ms: 1.11x faster                                |
| coverage                   | 81.2 ms                                                | 73.3 ms: 1.11x faster                                |
| async_tree_memoization     | 640 ms                                                 | 579 ms: 1.10x faster                                 |
| async_tree_none_tg         | 490 ms                                                 | 448 ms: 1.09x faster                                 |
| async_tree_io_tg           | 1.30 sec                                               | 1.19 sec: 1.09x faster                               |
| async_tree_memoization_tg  | 627 ms                                                 | 574 ms: 1.09x faster                                 |
| comprehensions             | 23.6 us                                                | 21.6 us: 1.09x faster                                |
| richards                   | 48.9 ms                                                | 45.4 ms: 1.08x faster                                |
| chaos                      | 71.4 ms                                                | 66.8 ms: 1.07x faster                                |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 725 ms: 1.05x faster                                 |
| unpickle_pure_python       | 241 us                                                 | 229 us: 1.05x faster                                 |
| sqlglot_parse              | 1.43 ms                                                | 1.37 ms: 1.05x faster                                |
| deltablue                  | 3.80 ms                                                | 3.64 ms: 1.04x faster                                |
| hexiom                     | 6.74 ms                                                | 6.46 ms: 1.04x faster                                |
| json_loads                 | 29.4 us                                                | 28.2 us: 1.04x faster                                |
| pickle_dict                | 34.8 us                                                | 33.5 us: 1.04x faster                                |
| nqueens                    | 86.8 ms                                                | 83.8 ms: 1.04x faster                                |
| sqlglot_transpile          | 1.75 ms                                                | 1.70 ms: 1.03x faster                                |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 726 ms: 1.03x faster                                 |
| mdp                        | 2.79 sec                                               | 2.72 sec: 1.02x faster                               |
| xml_etree_iterparse        | 109 ms                                                 | 106 ms: 1.02x faster                                 |
| unpickle_list              | 5.22 us                                                | 5.12 us: 1.02x faster                                |
| go                         | 143 ms                                                 | 140 ms: 1.02x faster                                 |
| sympy_expand               | 490 ms                                                 | 481 ms: 1.02x faster                                 |
| logging_silent             | 108 ns                                                 | 106 ns: 1.02x faster                                 |
| sympy_sum                  | 170 ms                                                 | 167 ms: 1.02x faster                                 |
| sqlglot_normalize          | 112 ms                                                 | 110 ms: 1.02x faster                                 |
| pidigits                   | 190 ms                                                 | 187 ms: 1.02x faster                                 |
| create_gc_cycles           | 1.48 ms                                                | 1.46 ms: 1.01x faster                                |
| pycparser                  | 1.20 sec                                               | 1.18 sec: 1.01x faster                               |
| sqlglot_optimize           | 55.2 ms                                                | 54.7 ms: 1.01x faster                                |
| asyncio_websockets         | 556 ms                                                 | 551 ms: 1.01x faster                                 |
| sympy_integrate            | 21.4 ms                                                | 21.2 ms: 1.01x faster                                |
| fannkuch                   | 410 ms                                                 | 409 ms: 1.00x faster                                 |
| raytrace                   | 306 ms                                                 | 307 ms: 1.00x slower                                 |
| bench_thread_pool          | 833 us                                                 | 841 us: 1.01x slower                                 |
| dask                       | 365 ms                                                 | 368 ms: 1.01x slower                                 |
| regex_v8                   | 22.9 ms                                                | 23.2 ms: 1.01x slower                                |
| docutils                   | 2.69 sec                                               | 2.73 sec: 1.01x slower                               |
| pickle_pure_python         | 319 us                                                 | 323 us: 1.01x slower                                 |
| tomli_loads                | 2.31 sec                                               | 2.35 sec: 1.02x slower                               |
| pathlib                    | 18.5 ms                                                | 18.8 ms: 1.02x slower                                |
| pprint_pformat             | 1.53 sec                                               | 1.56 sec: 1.02x slower                               |
| regex_dna                  | 204 ms                                                 | 209 ms: 1.02x slower                                 |
| tornado_http               | 97.7 ms                                                | 100 ms: 1.02x slower                                 |
| pickle                     | 11.1 us                                                | 11.4 us: 1.03x slower                                |
| django_template            | 33.8 ms                                                | 34.7 ms: 1.03x slower                                |
| deepcopy                   | 360 us                                                 | 370 us: 1.03x slower                                 |
| aiohttp                    | 1.12 ms                                                | 1.15 ms: 1.03x slower                                |
| sqlalchemy_imperative      | 18.2 ms                                                | 18.8 ms: 1.03x slower                                |
| deepcopy_memo              | 38.9 us                                                | 40.2 us: 1.03x slower                                |
| scimark_monte_carlo        | 71.8 ms                                                | 74.1 ms: 1.03x slower                                |
| 2to3                       | 266 ms                                                 | 275 ms: 1.03x slower                                 |
| gunicorn                   | 1.20 ms                                                | 1.24 ms: 1.03x slower                                |
| pprint_safe_repr           | 743 ms                                                 | 769 ms: 1.04x slower                                 |
| regex_compile              | 141 ms                                                 | 147 ms: 1.04x slower                                 |
| regex_effbot               | 3.45 ms                                                | 3.58 ms: 1.04x slower                                |
| logging_simple             | 6.24 us                                                | 6.49 us: 1.04x slower                                |
| deepcopy_reduce            | 3.14 us                                                | 3.26 us: 1.04x slower                                |
| sqlalchemy_declarative     | 141 ms                                                 | 147 ms: 1.05x slower                                 |
| dulwich_log                | 64.9 ms                                                | 68.4 ms: 1.05x slower                                |
| mako                       | 10.8 ms                                                | 11.4 ms: 1.05x slower                                |
| crypto_pyaes               | 77.5 ms                                                | 81.7 ms: 1.05x slower                                |
| logging_format             | 6.83 us                                                | 7.21 us: 1.06x slower                                |
| pickle_list                | 4.65 us                                                | 4.94 us: 1.06x slower                                |
| pyflate                    | 426 ms                                                 | 453 ms: 1.06x slower                                 |
| nbody                      | 91.6 ms                                                | 97.8 ms: 1.07x slower                                |
| telco                      | 6.72 ms                                                | 7.19 ms: 1.07x slower                                |
| float                      | 78.9 ms                                                | 84.6 ms: 1.07x slower                                |
| scimark_sor                | 121 ms                                                 | 131 ms: 1.08x slower                                 |
| xml_etree_process          | 56.5 ms                                                | 61.0 ms: 1.08x slower                                |
| scimark_lu                 | 112 ms                                                 | 122 ms: 1.09x slower                                 |
| chameleon                  | 6.86 ms                                                | 7.47 ms: 1.09x slower                                |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.27 ms: 1.10x slower                                |
| gc_traversal               | 3.90 ms                                                | 4.28 ms: 1.10x slower                                |
| xml_etree_generate         | 80.4 ms                                                | 88.5 ms: 1.10x slower                                |
| python_startup             | 8.69 ms                                                | 9.62 ms: 1.11x slower                                |
| sqlite_synth               | 2.58 us                                                | 2.86 us: 1.11x slower                                |
| spectral_norm              | 105 ms                                                 | 117 ms: 1.12x slower                                 |
| unpack_sequence            | 43.3 ns                                                | 48.5 ns: 1.12x slower                                |
| scimark_fft                | 342 ms                                                 | 384 ms: 1.12x slower                                 |
| python_startup_no_site     | 6.09 ms                                                | 6.97 ms: 1.14x slower                                |
| unpickle                   | 13.9 us                                                | 16.3 us: 1.18x slower                                |
| async_generators           | 375 ms                                                 | 461 ms: 1.23x slower                                 |
| Geometric mean             | (ref)                                                  | 1.02x faster                                         |

Benchmark hidden because not significant (6): xml_etree_parse, bench_mp_pool, meteor_contest, sympy_str, json, mypy2
Ignored benchmarks (7) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 59.86% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
