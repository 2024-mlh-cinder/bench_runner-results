
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: linux-x86_64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.03x faster \*
- HPT reliability: 51.40%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 274 ms: 1.03x slower                                                        |
| chameleon      | 6.86 ms                                                | 7.32 ms: 1.07x slower                                                       |
| docutils       | 2.69 sec                                               | 2.65 sec: 1.02x faster                                                      |
| tornado_http   | 97.7 ms                                                | 96.4 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                  | 1.02x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 532 ms                                                 | 446 ms: 1.19x faster                                                        |
| async_tree_memoization     | 640 ms                                                 | 571 ms: 1.12x faster                                                        |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                                      |
| async_tree_none_tg         | 490 ms                                                 | 460 ms: 1.06x faster                                                        |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                                      |
| async_tree_memoization_tg  | 627 ms                                                 | 604 ms: 1.04x faster                                                        |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 724 ms: 1.03x faster                                                        |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 752 ms: 1.02x faster                                                        |
| Geometric mean             | (ref)                                                  | 1.08x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 195 ms: 1.03x slower                                                        |
| float          | 78.9 ms                                                | 88.0 ms: 1.11x slower                                                       |
| nbody          | 91.6 ms                                                | 103 ms: 1.12x slower                                                        |
| Geometric mean | (ref)                                                  | 1.09x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 142 ms: 1.01x slower                                                        |
| regex_effbot   | 3.45 ms                                                | 3.62 ms: 1.05x slower                                                       |
| regex_dna      | 204 ms                                                 | 216 ms: 1.06x slower                                                        |
| regex_v8       | 22.9 ms                                                | 25.7 ms: 1.12x slower                                                       |
| Geometric mean | (ref)                                                  | 1.06x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.29x faster                                                       |
| json_loads           | 29.4 us                                                | 27.6 us: 1.07x faster                                                       |
| pickle_pure_python   | 319 us                                                 | 304 us: 1.05x faster                                                        |
| unpickle_pure_python | 241 us                                                 | 233 us: 1.03x faster                                                        |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                                        |
| tomli_loads          | 2.31 sec                                               | 2.28 sec: 1.02x faster                                                      |
| xml_etree_iterparse  | 109 ms                                                 | 108 ms: 1.01x faster                                                        |
| pickle_dict          | 34.8 us                                                | 34.7 us: 1.00x faster                                                       |
| pickle               | 11.1 us                                                | 11.3 us: 1.02x slower                                                       |
| xml_etree_process    | 56.5 ms                                                | 60.0 ms: 1.06x slower                                                       |
| unpickle             | 13.9 us                                                | 14.9 us: 1.07x slower                                                       |
| pickle_list          | 4.65 us                                                | 5.01 us: 1.08x slower                                                       |
| xml_etree_generate   | 80.4 ms                                                | 87.7 ms: 1.09x slower                                                       |
| unpickle_list        | 5.22 us                                                | 5.69 us: 1.09x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                       |
| python_startup_no_site | 6.09 ms                                                | 9.06 ms: 1.49x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 12.4 ms: 1.15x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 521 us                                                 | 122 us: 4.28x faster                                                        |
| generators                 | 76.5 ms                                                | 29.0 ms: 2.64x faster                                                       |
| asyncio_tcp                | 887 ms                                                 | 495 ms: 1.79x faster                                                        |
| asyncio_tcp_ssl            | 3.13 sec                                               | 1.79 sec: 1.74x faster                                                      |
| json_dumps                 | 13.5 ms                                                | 10.4 ms: 1.29x faster                                                       |
| mypy2                      | 427 ms                                                 | 348 ms: 1.23x faster                                                        |
| coroutines                 | 26.1 ms                                                | 21.8 ms: 1.20x faster                                                       |
| async_tree_none            | 532 ms                                                 | 446 ms: 1.19x faster                                                        |
| comprehensions             | 23.6 us                                                | 20.6 us: 1.15x faster                                                       |
| richards_super             | 61.2 ms                                                | 53.5 ms: 1.14x faster                                                       |
| async_tree_memoization     | 640 ms                                                 | 571 ms: 1.12x faster                                                        |
| sympy_sum                  | 170 ms                                                 | 152 ms: 1.12x faster                                                        |
| sqlglot_parse              | 1.43 ms                                                | 1.29 ms: 1.11x faster                                                       |
| async_tree_io              | 1.31 sec                                               | 1.20 sec: 1.09x faster                                                      |
| sympy_str                  | 299 ms                                                 | 274 ms: 1.09x faster                                                        |
| chaos                      | 71.4 ms                                                | 65.6 ms: 1.09x faster                                                       |
| sqlglot_transpile          | 1.75 ms                                                | 1.62 ms: 1.08x faster                                                       |
| raytrace                   | 306 ms                                                 | 284 ms: 1.08x faster                                                        |
| unpack_sequence            | 43.3 ns                                                | 40.5 ns: 1.07x faster                                                       |
| json_loads                 | 29.4 us                                                | 27.6 us: 1.07x faster                                                       |
| sympy_expand               | 490 ms                                                 | 460 ms: 1.06x faster                                                        |
| async_tree_none_tg         | 490 ms                                                 | 460 ms: 1.06x faster                                                        |
| logging_simple             | 6.24 us                                                | 5.92 us: 1.05x faster                                                       |
| async_tree_io_tg           | 1.30 sec                                               | 1.24 sec: 1.05x faster                                                      |
| mdp                        | 2.79 sec                                               | 2.65 sec: 1.05x faster                                                      |
| pickle_pure_python         | 319 us                                                 | 304 us: 1.05x faster                                                        |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.05x faster                                                        |
| logging_format             | 6.83 us                                                | 6.53 us: 1.05x faster                                                       |
| richards                   | 48.9 ms                                                | 47.0 ms: 1.04x faster                                                       |
| async_tree_memoization_tg  | 627 ms                                                 | 604 ms: 1.04x faster                                                        |
| sympy_integrate            | 21.4 ms                                                | 20.6 ms: 1.04x faster                                                       |
| async_tree_cpu_io_mixed    | 750 ms                                                 | 724 ms: 1.03x faster                                                        |
| unpickle_pure_python       | 241 us                                                 | 233 us: 1.03x faster                                                        |
| xml_etree_parse            | 163 ms                                                 | 159 ms: 1.02x faster                                                        |
| sqlglot_optimize           | 55.2 ms                                                | 53.9 ms: 1.02x faster                                                       |
| tomli_loads                | 2.31 sec                                               | 2.28 sec: 1.02x faster                                                      |
| async_tree_cpu_io_mixed_tg | 764 ms                                                 | 752 ms: 1.02x faster                                                        |
| docutils                   | 2.69 sec                                               | 2.65 sec: 1.02x faster                                                      |
| deepcopy                   | 360 us                                                 | 355 us: 1.01x faster                                                        |
| tornado_http               | 97.7 ms                                                | 96.4 ms: 1.01x faster                                                       |
| logging_silent             | 108 ns                                                 | 107 ns: 1.01x faster                                                        |
| json                       | 5.24 ms                                                | 5.18 ms: 1.01x faster                                                       |
| xml_etree_iterparse        | 109 ms                                                 | 108 ms: 1.01x faster                                                        |
| create_gc_cycles           | 1.48 ms                                                | 1.47 ms: 1.01x faster                                                       |
| asyncio_websockets         | 556 ms                                                 | 552 ms: 1.01x faster                                                        |
| pickle_dict                | 34.8 us                                                | 34.7 us: 1.00x faster                                                       |
| regex_compile              | 141 ms                                                 | 142 ms: 1.01x slower                                                        |
| crypto_pyaes               | 77.5 ms                                                | 78.4 ms: 1.01x slower                                                       |
| pycparser                  | 1.20 sec                                               | 1.21 sec: 1.01x slower                                                      |
| bench_thread_pool          | 833 us                                                 | 850 us: 1.02x slower                                                        |
| pickle                     | 11.1 us                                                | 11.3 us: 1.02x slower                                                       |
| scimark_sor                | 121 ms                                                 | 124 ms: 1.02x slower                                                        |
| scimark_monte_carlo        | 71.8 ms                                                | 73.5 ms: 1.02x slower                                                       |
| pidigits                   | 190 ms                                                 | 195 ms: 1.03x slower                                                        |
| dulwich_log                | 64.9 ms                                                | 66.7 ms: 1.03x slower                                                       |
| 2to3                       | 266 ms                                                 | 274 ms: 1.03x slower                                                        |
| scimark_lu                 | 112 ms                                                 | 117 ms: 1.04x slower                                                        |
| pprint_pformat             | 1.53 sec                                               | 1.59 sec: 1.04x slower                                                      |
| gc_traversal               | 3.90 ms                                                | 4.08 ms: 1.05x slower                                                       |
| deepcopy_memo              | 38.9 us                                                | 40.7 us: 1.05x slower                                                       |
| pprint_safe_repr           | 743 ms                                                 | 778 ms: 1.05x slower                                                        |
| meteor_contest             | 109 ms                                                 | 114 ms: 1.05x slower                                                        |
| regex_effbot               | 3.45 ms                                                | 3.62 ms: 1.05x slower                                                       |
| pathlib                    | 18.5 ms                                                | 19.5 ms: 1.05x slower                                                       |
| regex_dna                  | 204 ms                                                 | 216 ms: 1.06x slower                                                        |
| go                         | 143 ms                                                 | 151 ms: 1.06x slower                                                        |
| xml_etree_process          | 56.5 ms                                                | 60.0 ms: 1.06x slower                                                       |
| chameleon                  | 6.86 ms                                                | 7.32 ms: 1.07x slower                                                       |
| unpickle                   | 13.9 us                                                | 14.9 us: 1.07x slower                                                       |
| pickle_list                | 4.65 us                                                | 5.01 us: 1.08x slower                                                       |
| spectral_norm              | 105 ms                                                 | 114 ms: 1.08x slower                                                        |
| deltablue                  | 3.80 ms                                                | 4.13 ms: 1.09x slower                                                       |
| sqlite_synth               | 2.58 us                                                | 2.81 us: 1.09x slower                                                       |
| xml_etree_generate         | 80.4 ms                                                | 87.7 ms: 1.09x slower                                                       |
| unpickle_list              | 5.22 us                                                | 5.69 us: 1.09x slower                                                       |
| fannkuch                   | 410 ms                                                 | 453 ms: 1.10x slower                                                        |
| nqueens                    | 86.8 ms                                                | 96.6 ms: 1.11x slower                                                       |
| float                      | 78.9 ms                                                | 88.0 ms: 1.11x slower                                                       |
| nbody                      | 91.6 ms                                                | 103 ms: 1.12x slower                                                        |
| regex_v8                   | 22.9 ms                                                | 25.7 ms: 1.12x slower                                                       |
| scimark_fft                | 342 ms                                                 | 388 ms: 1.13x slower                                                        |
| mako                       | 10.8 ms                                                | 12.4 ms: 1.15x slower                                                       |
| scimark_sparse_mat_mult    | 4.80 ms                                                | 5.53 ms: 1.15x slower                                                       |
| hexiom                     | 6.74 ms                                                | 7.84 ms: 1.16x slower                                                       |
| coverage                   | 81.2 ms                                                | 94.6 ms: 1.16x slower                                                       |
| python_startup             | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                       |
| pyflate                    | 426 ms                                                 | 526 ms: 1.23x slower                                                        |
| async_generators           | 375 ms                                                 | 465 ms: 1.24x slower                                                        |
| telco                      | 6.72 ms                                                | 8.50 ms: 1.27x slower                                                       |
| python_startup_no_site     | 6.09 ms                                                | 9.06 ms: 1.49x slower                                                       |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                                |

Benchmark hidden because not significant (2): deepcopy_reduce, bench_mp_pool
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 51.40% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
