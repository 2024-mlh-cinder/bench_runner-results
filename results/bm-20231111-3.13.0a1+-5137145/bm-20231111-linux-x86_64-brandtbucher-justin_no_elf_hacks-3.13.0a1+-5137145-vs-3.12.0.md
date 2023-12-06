
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: linux-x86_64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.01x slower \*
- HPT reliability: 86.39%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 274 ms: 1.00x faster                                                        |
| chameleon      | 7.41 ms                                                | 7.32 ms: 1.01x faster                                                       |
| docutils       | 2.75 sec                                               | 2.65 sec: 1.04x faster                                                      |
| tornado_http   | 101 ms                                                 | 96.4 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                  | 1.02x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 446 ms: 1.07x faster                                                        |
| async_tree_memoization     | 580 ms                                                 | 571 ms: 1.02x faster                                                        |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                      |
| async_tree_none_tg         | 447 ms                                                 | 460 ms: 1.03x slower                                                        |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 752 ms: 1.04x slower                                                        |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                                      |
| async_tree_memoization_tg  | 574 ms                                                 | 604 ms: 1.05x slower                                                        |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                                        |
| float          | 83.3 ms                                                | 88.0 ms: 1.06x slower                                                       |
| nbody          | 92.2 ms                                                | 103 ms: 1.11x slower                                                        |
| Geometric mean | (ref)                                                  | 1.07x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 142 ms: 1.04x faster                                                        |
| regex_effbot   | 3.57 ms                                                | 3.62 ms: 1.02x slower                                                       |
| regex_dna      | 209 ms                                                 | 216 ms: 1.03x slower                                                        |
| regex_v8       | 22.7 ms                                                | 25.7 ms: 1.14x slower                                                       |
| Geometric mean | (ref)                                                  | 1.03x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 304 us: 1.07x faster                                                        |
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                                       |
| json_loads           | 28.4 us                                                | 27.6 us: 1.03x faster                                                       |
| xml_etree_process    | 61.2 ms                                                | 60.0 ms: 1.02x faster                                                       |
| json_dumps           | 10.6 ms                                                | 10.4 ms: 1.01x faster                                                       |
| xml_etree_generate   | 88.7 ms                                                | 87.7 ms: 1.01x faster                                                       |
| tomli_loads          | 2.30 sec                                               | 2.28 sec: 1.01x faster                                                      |
| pickle               | 11.2 us                                                | 11.3 us: 1.01x slower                                                       |
| unpickle_pure_python | 230 us                                                 | 233 us: 1.02x slower                                                        |
| xml_etree_iterparse  | 106 ms                                                 | 108 ms: 1.02x slower                                                        |
| pickle_dict          | 33.5 us                                                | 34.7 us: 1.04x slower                                                       |
| pickle_list          | 4.67 us                                                | 5.01 us: 1.07x slower                                                       |
| unpickle_list        | 5.04 us                                                | 5.69 us: 1.13x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                       |
| python_startup_no_site | 6.92 ms                                                | 9.06 ms: 1.31x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.4 ms: 1.08x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence            | 54.2 ns                                                | 40.5 ns: 1.34x faster                                                       |
| typing_runtime_protocols   | 153 us                                                 | 122 us: 1.26x faster                                                        |
| generators                 | 32.5 ms                                                | 29.0 ms: 1.12x faster                                                       |
| sympy_sum                  | 167 ms                                                 | 152 ms: 1.10x faster                                                        |
| logging_format             | 7.10 us                                                | 6.53 us: 1.09x faster                                                       |
| raytrace                   | 308 ms                                                 | 284 ms: 1.08x faster                                                        |
| sympy_str                  | 296 ms                                                 | 274 ms: 1.08x faster                                                        |
| logging_simple             | 6.38 us                                                | 5.92 us: 1.08x faster                                                       |
| coroutines                 | 23.5 ms                                                | 21.8 ms: 1.08x faster                                                       |
| pickle_pure_python         | 326 us                                                 | 304 us: 1.07x faster                                                        |
| async_tree_none            | 475 ms                                                 | 446 ms: 1.07x faster                                                        |
| crypto_pyaes               | 83.6 ms                                                | 78.4 ms: 1.07x faster                                                       |
| unpickle                   | 15.8 us                                                | 14.9 us: 1.06x faster                                                       |
| gc_traversal               | 4.28 ms                                                | 4.08 ms: 1.05x faster                                                       |
| tornado_http               | 101 ms                                                 | 96.4 ms: 1.04x faster                                                       |
| sqlglot_parse              | 1.35 ms                                                | 1.29 ms: 1.04x faster                                                       |
| regex_compile              | 148 ms                                                 | 142 ms: 1.04x faster                                                        |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.04x faster                                                        |
| docutils                   | 2.75 sec                                               | 2.65 sec: 1.04x faster                                                      |
| scimark_sor                | 129 ms                                                 | 124 ms: 1.04x faster                                                        |
| sqlglot_transpile          | 1.68 ms                                                | 1.62 ms: 1.04x faster                                                       |
| sympy_expand               | 476 ms                                                 | 460 ms: 1.03x faster                                                        |
| deepcopy_reduce            | 3.23 us                                                | 3.13 us: 1.03x faster                                                       |
| scimark_lu                 | 120 ms                                                 | 117 ms: 1.03x faster                                                        |
| dulwich_log                | 68.7 ms                                                | 66.7 ms: 1.03x faster                                                       |
| json_loads                 | 28.4 us                                                | 27.6 us: 1.03x faster                                                       |
| chaos                      | 67.5 ms                                                | 65.6 ms: 1.03x faster                                                       |
| sympy_integrate            | 21.2 ms                                                | 20.6 ms: 1.03x faster                                                       |
| asyncio_tcp                | 506 ms                                                 | 495 ms: 1.02x faster                                                        |
| deepcopy                   | 363 us                                                 | 355 us: 1.02x faster                                                        |
| xml_etree_process          | 61.2 ms                                                | 60.0 ms: 1.02x faster                                                       |
| comprehensions             | 20.9 us                                                | 20.6 us: 1.02x faster                                                       |
| sqlglot_optimize           | 54.8 ms                                                | 53.9 ms: 1.02x faster                                                       |
| async_tree_memoization     | 580 ms                                                 | 571 ms: 1.02x faster                                                        |
| scimark_monte_carlo        | 74.6 ms                                                | 73.5 ms: 1.02x faster                                                       |
| json_dumps                 | 10.6 ms                                                | 10.4 ms: 1.01x faster                                                       |
| xml_etree_generate         | 88.7 ms                                                | 87.7 ms: 1.01x faster                                                       |
| chameleon                  | 7.41 ms                                                | 7.32 ms: 1.01x faster                                                       |
| spectral_norm              | 115 ms                                                 | 114 ms: 1.01x faster                                                        |
| tomli_loads                | 2.30 sec                                               | 2.28 sec: 1.01x faster                                                      |
| sqlite_synth               | 2.83 us                                                | 2.81 us: 1.01x faster                                                       |
| json                       | 5.22 ms                                                | 5.18 ms: 1.01x faster                                                       |
| mypy2                      | 351 ms                                                 | 348 ms: 1.01x faster                                                        |
| logging_silent             | 108 ns                                                 | 107 ns: 1.01x faster                                                        |
| 2to3                       | 274 ms                                                 | 274 ms: 1.00x faster                                                        |
| bench_thread_pool          | 845 us                                                 | 850 us: 1.01x slower                                                        |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.01x slower                                                      |
| pickle                     | 11.2 us                                                | 11.3 us: 1.01x slower                                                       |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                                       |
| async_generators           | 459 ms                                                 | 465 ms: 1.01x slower                                                        |
| regex_effbot               | 3.57 ms                                                | 3.62 ms: 1.02x slower                                                       |
| unpickle_pure_python       | 230 us                                                 | 233 us: 1.02x slower                                                        |
| pprint_safe_repr           | 765 ms                                                 | 778 ms: 1.02x slower                                                        |
| scimark_fft                | 381 ms                                                 | 388 ms: 1.02x slower                                                        |
| xml_etree_iterparse        | 106 ms                                                 | 108 ms: 1.02x slower                                                        |
| richards                   | 46.0 ms                                                | 47.0 ms: 1.02x slower                                                       |
| pprint_pformat             | 1.55 sec                                               | 1.59 sec: 1.02x slower                                                      |
| deepcopy_memo              | 39.7 us                                                | 40.7 us: 1.02x slower                                                       |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                      |
| async_tree_none_tg         | 447 ms                                                 | 460 ms: 1.03x slower                                                        |
| pathlib                    | 18.9 ms                                                | 19.5 ms: 1.03x slower                                                       |
| richards_super             | 51.9 ms                                                | 53.5 ms: 1.03x slower                                                       |
| mdp                        | 2.57 sec                                               | 2.65 sec: 1.03x slower                                                      |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.03x slower                                                      |
| regex_dna                  | 209 ms                                                 | 216 ms: 1.03x slower                                                        |
| pickle_dict                | 33.5 us                                                | 34.7 us: 1.04x slower                                                       |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 752 ms: 1.04x slower                                                        |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.53 ms: 1.04x slower                                                       |
| meteor_contest             | 110 ms                                                 | 114 ms: 1.04x slower                                                        |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                                      |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                                        |
| async_tree_memoization_tg  | 574 ms                                                 | 604 ms: 1.05x slower                                                        |
| float                      | 83.3 ms                                                | 88.0 ms: 1.06x slower                                                       |
| pickle_list                | 4.67 us                                                | 5.01 us: 1.07x slower                                                       |
| go                         | 140 ms                                                 | 151 ms: 1.08x slower                                                        |
| mako                       | 11.5 ms                                                | 12.4 ms: 1.08x slower                                                       |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                       |
| fannkuch                   | 410 ms                                                 | 453 ms: 1.10x slower                                                        |
| deltablue                  | 3.71 ms                                                | 4.13 ms: 1.11x slower                                                       |
| nbody                      | 92.2 ms                                                | 103 ms: 1.11x slower                                                        |
| pyflate                    | 471 ms                                                 | 526 ms: 1.12x slower                                                        |
| nqueens                    | 86.2 ms                                                | 96.6 ms: 1.12x slower                                                       |
| unpickle_list              | 5.04 us                                                | 5.69 us: 1.13x slower                                                       |
| regex_v8                   | 22.7 ms                                                | 25.7 ms: 1.14x slower                                                       |
| telco                      | 7.18 ms                                                | 8.50 ms: 1.18x slower                                                       |
| hexiom                     | 6.54 ms                                                | 7.84 ms: 1.20x slower                                                       |
| coverage                   | 75.1 ms                                                | 94.6 ms: 1.26x slower                                                       |
| python_startup_no_site     | 6.92 ms                                                | 9.06 ms: 1.31x slower                                                       |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                                |

Benchmark hidden because not significant (4): xml_etree_parse, asyncio_websockets, bench_mp_pool, async_tree_cpu_io_mixed
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 86.39% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
