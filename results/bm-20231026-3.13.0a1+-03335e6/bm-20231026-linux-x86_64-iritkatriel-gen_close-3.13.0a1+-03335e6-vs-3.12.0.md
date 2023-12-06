
# Results vs. 3.12.0

- fork: iritkatriel
- ref: gen_close
- machine: linux-x86_64
- commit hash: 03335e6
- commit date: 2023-10-26
- overall geometric mean: 1.02x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                             |
| chameleon      | 7.41 ms                                                | 6.97 ms: 1.06x faster                                            |
| docutils       | 2.75 sec                                               | 2.65 sec: 1.04x faster                                           |
| tornado_http   | 101 ms                                                 | 95.7 ms: 1.05x faster                                            |
| Geometric mean | (ref)                                                  | 1.05x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 437 ms: 1.09x faster                                             |
| async_tree_memoization     | 580 ms                                                 | 563 ms: 1.03x faster                                             |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 712 ms: 1.02x faster                                             |
| async_tree_none_tg         | 447 ms                                                 | 455 ms: 1.02x slower                                             |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 743 ms: 1.02x slower                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 596 ms: 1.04x slower                                             |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| float          | 83.3 ms                                                | 81.4 ms: 1.02x faster                                            |
| nbody          | 92.2 ms                                                | 91.3 ms: 1.01x faster                                            |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                             |
| Geometric mean | (ref)                                                  | 1.01x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 138 ms: 1.07x faster                                             |
| regex_dna      | 209 ms                                                 | 212 ms: 1.02x slower                                             |
| regex_effbot   | 3.57 ms                                                | 3.65 ms: 1.02x slower                                            |
| regex_v8       | 22.7 ms                                                | 25.5 ms: 1.12x slower                                            |
| Geometric mean | (ref)                                                  | 1.02x slower                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 300 us: 1.09x faster                                             |
| tomli_loads          | 2.30 sec                                               | 2.14 sec: 1.07x faster                                           |
| unpickle             | 15.8 us                                                | 14.8 us: 1.07x faster                                            |
| unpickle_pure_python | 230 us                                                 | 220 us: 1.04x faster                                             |
| xml_etree_process    | 61.2 ms                                                | 58.8 ms: 1.04x faster                                            |
| xml_etree_generate   | 88.7 ms                                                | 86.1 ms: 1.03x faster                                            |
| pickle_dict          | 33.5 us                                                | 32.8 us: 1.02x faster                                            |
| json_loads           | 28.4 us                                                | 28.0 us: 1.01x faster                                            |
| json_dumps           | 10.6 ms                                                | 10.4 ms: 1.01x faster                                            |
| pickle               | 11.2 us                                                | 11.1 us: 1.01x faster                                            |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                             |
| unpickle_list        | 5.04 us                                                | 5.08 us: 1.01x slower                                            |
| pickle_list          | 4.67 us                                                | 4.95 us: 1.06x slower                                            |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                     |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                            |
| python_startup_no_site | 6.92 ms                                                | 8.94 ms: 1.29x slower                                            |
| Geometric mean         | (ref)                                                  | 1.18x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.5 ms: 1.00x faster                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| comprehensions             | 20.9 us                                                | 16.7 us: 1.25x faster                                            |
| unpack_sequence            | 54.2 ns                                                | 44.7 ns: 1.21x faster                                            |
| crypto_pyaes               | 83.6 ms                                                | 71.5 ms: 1.17x faster                                            |
| sympy_sum                  | 167 ms                                                 | 148 ms: 1.13x faster                                             |
| raytrace                   | 308 ms                                                 | 276 ms: 1.11x faster                                             |
| sympy_str                  | 296 ms                                                 | 266 ms: 1.11x faster                                             |
| logging_format             | 7.10 us                                                | 6.43 us: 1.10x faster                                            |
| chaos                      | 67.5 ms                                                | 61.4 ms: 1.10x faster                                            |
| deltablue                  | 3.71 ms                                                | 3.38 ms: 1.10x faster                                            |
| generators                 | 32.5 ms                                                | 29.6 ms: 1.10x faster                                            |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.90 ms: 1.09x faster                                            |
| async_tree_none            | 475 ms                                                 | 437 ms: 1.09x faster                                             |
| pickle_pure_python         | 326 us                                                 | 300 us: 1.09x faster                                             |
| scimark_monte_carlo        | 74.6 ms                                                | 69.1 ms: 1.08x faster                                            |
| logging_simple             | 6.38 us                                                | 5.91 us: 1.08x faster                                            |
| sympy_integrate            | 21.2 ms                                                | 19.7 ms: 1.08x faster                                            |
| regex_compile              | 148 ms                                                 | 138 ms: 1.07x faster                                             |
| tomli_loads                | 2.30 sec                                               | 2.14 sec: 1.07x faster                                           |
| nqueens                    | 86.2 ms                                                | 80.4 ms: 1.07x faster                                            |
| unpickle                   | 15.8 us                                                | 14.8 us: 1.07x faster                                            |
| sqlglot_normalize          | 112 ms                                                 | 105 ms: 1.06x faster                                             |
| chameleon                  | 7.41 ms                                                | 6.97 ms: 1.06x faster                                            |
| hexiom                     | 6.54 ms                                                | 6.20 ms: 1.06x faster                                            |
| asyncio_tcp                | 506 ms                                                 | 479 ms: 1.05x faster                                             |
| sympy_expand               | 476 ms                                                 | 452 ms: 1.05x faster                                             |
| tornado_http               | 101 ms                                                 | 95.7 ms: 1.05x faster                                            |
| gc_traversal               | 4.28 ms                                                | 4.08 ms: 1.05x faster                                            |
| unpickle_pure_python       | 230 us                                                 | 220 us: 1.04x faster                                             |
| coroutines                 | 23.5 ms                                                | 22.5 ms: 1.04x faster                                            |
| scimark_lu                 | 120 ms                                                 | 116 ms: 1.04x faster                                             |
| xml_etree_process          | 61.2 ms                                                | 58.8 ms: 1.04x faster                                            |
| spectral_norm              | 115 ms                                                 | 110 ms: 1.04x faster                                             |
| docutils                   | 2.75 sec                                               | 2.65 sec: 1.04x faster                                           |
| pprint_safe_repr           | 765 ms                                                 | 737 ms: 1.04x faster                                             |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                             |
| bench_thread_pool          | 845 us                                                 | 815 us: 1.04x faster                                             |
| deepcopy                   | 363 us                                                 | 350 us: 1.04x faster                                             |
| sqlglot_transpile          | 1.68 ms                                                | 1.62 ms: 1.04x faster                                            |
| dulwich_log                | 68.7 ms                                                | 66.4 ms: 1.03x faster                                            |
| scimark_sor                | 129 ms                                                 | 125 ms: 1.03x faster                                             |
| deepcopy_reduce            | 3.23 us                                                | 3.13 us: 1.03x faster                                            |
| deepcopy_memo              | 39.7 us                                                | 38.5 us: 1.03x faster                                            |
| pprint_pformat             | 1.55 sec                                               | 1.50 sec: 1.03x faster                                           |
| xml_etree_generate         | 88.7 ms                                                | 86.1 ms: 1.03x faster                                            |
| sqlglot_parse              | 1.35 ms                                                | 1.31 ms: 1.03x faster                                            |
| sqlglot_optimize           | 54.8 ms                                                | 53.2 ms: 1.03x faster                                            |
| async_tree_memoization     | 580 ms                                                 | 563 ms: 1.03x faster                                             |
| logging_silent             | 108 ns                                                 | 105 ns: 1.03x faster                                             |
| meteor_contest             | 110 ms                                                 | 107 ms: 1.03x faster                                             |
| float                      | 83.3 ms                                                | 81.4 ms: 1.02x faster                                            |
| mypy2                      | 351 ms                                                 | 343 ms: 1.02x faster                                             |
| fannkuch                   | 410 ms                                                 | 401 ms: 1.02x faster                                             |
| pickle_dict                | 33.5 us                                                | 32.8 us: 1.02x faster                                            |
| sqlite_synth               | 2.83 us                                                | 2.78 us: 1.02x faster                                            |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 712 ms: 1.02x faster                                             |
| json_loads                 | 28.4 us                                                | 28.0 us: 1.01x faster                                            |
| json_dumps                 | 10.6 ms                                                | 10.4 ms: 1.01x faster                                            |
| mdp                        | 2.57 sec                                               | 2.54 sec: 1.01x faster                                           |
| typing_runtime_protocols   | 153 us                                                 | 152 us: 1.01x faster                                             |
| scimark_fft                | 381 ms                                                 | 377 ms: 1.01x faster                                             |
| nbody                      | 92.2 ms                                                | 91.3 ms: 1.01x faster                                            |
| pickle                     | 11.2 us                                                | 11.1 us: 1.01x faster                                            |
| pycparser                  | 1.17 sec                                               | 1.16 sec: 1.01x faster                                           |
| json                       | 5.22 ms                                                | 5.17 ms: 1.01x faster                                            |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                             |
| mako                       | 11.5 ms                                                | 11.5 ms: 1.00x faster                                            |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.78 sec: 1.00x faster                                           |
| pidigits                   | 187 ms                                                 | 187 ms: 1.00x slower                                             |
| create_gc_cycles           | 1.45 ms                                                | 1.45 ms: 1.00x slower                                            |
| unpickle_list              | 5.04 us                                                | 5.08 us: 1.01x slower                                            |
| async_tree_none_tg         | 447 ms                                                 | 455 ms: 1.02x slower                                             |
| regex_dna                  | 209 ms                                                 | 212 ms: 1.02x slower                                             |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                           |
| regex_effbot               | 3.57 ms                                                | 3.65 ms: 1.02x slower                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 743 ms: 1.02x slower                                             |
| go                         | 140 ms                                                 | 145 ms: 1.03x slower                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 596 ms: 1.04x slower                                             |
| richards_super             | 51.9 ms                                                | 55.0 ms: 1.06x slower                                            |
| richards                   | 46.0 ms                                                | 48.8 ms: 1.06x slower                                            |
| pickle_list                | 4.67 us                                                | 4.95 us: 1.06x slower                                            |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                            |
| regex_v8                   | 22.7 ms                                                | 25.5 ms: 1.12x slower                                            |
| telco                      | 7.18 ms                                                | 8.32 ms: 1.16x slower                                            |
| coverage                   | 75.1 ms                                                | 94.3 ms: 1.26x slower                                            |
| python_startup_no_site     | 6.92 ms                                                | 8.94 ms: 1.29x slower                                            |
| Geometric mean             | (ref)                                                  | 1.02x faster                                                     |

Benchmark hidden because not significant (6): xml_etree_iterparse, async_generators, pyflate, asyncio_websockets, pathlib, bench_mp_pool
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
