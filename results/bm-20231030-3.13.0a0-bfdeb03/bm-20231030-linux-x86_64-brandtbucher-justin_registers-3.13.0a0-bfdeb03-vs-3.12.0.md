
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: bfdeb03
- commit date: 2023-10-30
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 293 ms: 1.07x slower                                                    |
| chameleon      | 7.41 ms                                                | 7.47 ms: 1.01x slower                                                   |
| tornado_http   | 101 ms                                                 | 99.7 ms: 1.01x faster                                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                                            |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 457 ms: 1.04x faster                                                    |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 756 ms: 1.04x slower                                                    |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 471 ms: 1.05x slower                                                    |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                  |
| async_tree_memoization_tg  | 574 ms                                                 | 612 ms: 1.07x slower                                                    |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                            |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                    |
| float          | 83.3 ms                                                | 97.8 ms: 1.17x slower                                                   |
| nbody          | 92.2 ms                                                | 112 ms: 1.22x slower                                                    |
| Geometric mean | (ref)                                                  | 1.13x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 208 ms: 1.00x faster                                                    |
| regex_effbot   | 3.57 ms                                                | 3.58 ms: 1.00x slower                                                   |
| regex_compile  | 148 ms                                                 | 156 ms: 1.06x slower                                                    |
| regex_v8       | 22.7 ms                                                | 25.0 ms: 1.11x slower                                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 307 us: 1.06x faster                                                    |
| unpickle             | 15.8 us                                                | 15.5 us: 1.02x faster                                                   |
| unpickle_list        | 5.04 us                                                | 4.95 us: 1.02x faster                                                   |
| xml_etree_process    | 61.2 ms                                                | 60.6 ms: 1.01x faster                                                   |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                                   |
| tomli_loads          | 2.30 sec                                               | 2.35 sec: 1.02x slower                                                  |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                                   |
| pickle_dict          | 33.5 us                                                | 35.4 us: 1.06x slower                                                   |
| unpickle_pure_python | 230 us                                                 | 244 us: 1.06x slower                                                    |
| xml_etree_iterparse  | 106 ms                                                 | 114 ms: 1.08x slower                                                    |
| pickle_list          | 4.67 us                                                | 5.22 us: 1.12x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                            |

Benchmark hidden because not significant (3): json_dumps, xml_etree_generate, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 7.10 ms: 1.03x slower                                                   |
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.4 ms: 1.08x slower                                                   |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpack_sequence            | 54.2 ns                                                | 49.0 ns: 1.10x faster                                                   |
| generators                 | 32.5 ms                                                | 29.4 ms: 1.10x faster                                                   |
| crypto_pyaes               | 83.6 ms                                                | 76.8 ms: 1.09x faster                                                   |
| gc_traversal               | 4.28 ms                                                | 3.96 ms: 1.08x faster                                                   |
| pickle_pure_python         | 326 us                                                 | 307 us: 1.06x faster                                                    |
| asyncio_tcp                | 506 ms                                                 | 485 ms: 1.04x faster                                                    |
| async_tree_none            | 475 ms                                                 | 457 ms: 1.04x faster                                                    |
| logging_format             | 7.10 us                                                | 6.82 us: 1.04x faster                                                   |
| logging_simple             | 6.38 us                                                | 6.21 us: 1.03x faster                                                   |
| unpickle                   | 15.8 us                                                | 15.5 us: 1.02x faster                                                   |
| unpickle_list              | 5.04 us                                                | 4.95 us: 1.02x faster                                                   |
| coroutines                 | 23.5 ms                                                | 23.0 ms: 1.02x faster                                                   |
| sqlglot_normalize          | 112 ms                                                 | 110 ms: 1.02x faster                                                    |
| scimark_lu                 | 120 ms                                                 | 119 ms: 1.01x faster                                                    |
| xml_etree_process          | 61.2 ms                                                | 60.6 ms: 1.01x faster                                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.20 us: 1.01x faster                                                   |
| tornado_http               | 101 ms                                                 | 99.7 ms: 1.01x faster                                                   |
| json_loads                 | 28.4 us                                                | 28.2 us: 1.01x faster                                                   |
| sympy_sum                  | 167 ms                                                 | 166 ms: 1.01x faster                                                    |
| sqlite_synth               | 2.83 us                                                | 2.81 us: 1.01x faster                                                   |
| json                       | 5.22 ms                                                | 5.18 ms: 1.01x faster                                                   |
| raytrace                   | 308 ms                                                 | 306 ms: 1.01x faster                                                    |
| sqlglot_parse              | 1.35 ms                                                | 1.34 ms: 1.00x faster                                                   |
| regex_dna                  | 209 ms                                                 | 208 ms: 1.00x faster                                                    |
| regex_effbot               | 3.57 ms                                                | 3.58 ms: 1.00x slower                                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.36 ms: 1.00x slower                                                   |
| bench_thread_pool          | 845 us                                                 | 850 us: 1.01x slower                                                    |
| sympy_str                  | 296 ms                                                 | 298 ms: 1.01x slower                                                    |
| deepcopy                   | 363 us                                                 | 365 us: 1.01x slower                                                    |
| scimark_sor                | 129 ms                                                 | 130 ms: 1.01x slower                                                    |
| chameleon                  | 7.41 ms                                                | 7.47 ms: 1.01x slower                                                   |
| scimark_fft                | 381 ms                                                 | 384 ms: 1.01x slower                                                    |
| pidigits                   | 187 ms                                                 | 189 ms: 1.01x slower                                                    |
| dulwich_log                | 68.7 ms                                                | 69.4 ms: 1.01x slower                                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 55.4 ms: 1.01x slower                                                   |
| pathlib                    | 18.9 ms                                                | 19.1 ms: 1.01x slower                                                   |
| sympy_expand               | 476 ms                                                 | 482 ms: 1.01x slower                                                    |
| tomli_loads                | 2.30 sec                                               | 2.35 sec: 1.02x slower                                                  |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.02x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 7.10 ms: 1.03x slower                                                   |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 77.0 ms: 1.03x slower                                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.50 ms: 1.04x slower                                                   |
| spectral_norm              | 115 ms                                                 | 119 ms: 1.04x slower                                                    |
| mypy2                      | 351 ms                                                 | 364 ms: 1.04x slower                                                    |
| meteor_contest             | 110 ms                                                 | 114 ms: 1.04x slower                                                    |
| typing_runtime_protocols   | 153 us                                                 | 159 us: 1.04x slower                                                    |
| async_generators           | 459 ms                                                 | 478 ms: 1.04x slower                                                    |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 756 ms: 1.04x slower                                                    |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                  |
| logging_silent             | 108 ns                                                 | 113 ns: 1.05x slower                                                    |
| async_tree_none_tg         | 447 ms                                                 | 471 ms: 1.05x slower                                                    |
| pickle_dict                | 33.5 us                                                | 35.4 us: 1.06x slower                                                   |
| regex_compile              | 148 ms                                                 | 156 ms: 1.06x slower                                                    |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                  |
| sympy_integrate            | 21.2 ms                                                | 22.5 ms: 1.06x slower                                                   |
| unpickle_pure_python       | 230 us                                                 | 244 us: 1.06x slower                                                    |
| async_tree_memoization_tg  | 574 ms                                                 | 612 ms: 1.07x slower                                                    |
| 2to3                       | 274 ms                                                 | 293 ms: 1.07x slower                                                    |
| richards_super             | 51.9 ms                                                | 55.5 ms: 1.07x slower                                                   |
| xml_etree_iterparse        | 106 ms                                                 | 114 ms: 1.08x slower                                                    |
| mako                       | 11.5 ms                                                | 12.4 ms: 1.08x slower                                                   |
| richards                   | 46.0 ms                                                | 49.8 ms: 1.08x slower                                                   |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                   |
| deepcopy_memo              | 39.7 us                                                | 43.2 us: 1.09x slower                                                   |
| go                         | 140 ms                                                 | 155 ms: 1.10x slower                                                    |
| regex_v8                   | 22.7 ms                                                | 25.0 ms: 1.11x slower                                                   |
| mdp                        | 2.57 sec                                               | 2.85 sec: 1.11x slower                                                  |
| chaos                      | 67.5 ms                                                | 75.3 ms: 1.11x slower                                                   |
| deltablue                  | 3.71 ms                                                | 4.14 ms: 1.12x slower                                                   |
| pickle_list                | 4.67 us                                                | 5.22 us: 1.12x slower                                                   |
| pprint_safe_repr           | 765 ms                                                 | 860 ms: 1.12x slower                                                    |
| nqueens                    | 86.2 ms                                                | 97.2 ms: 1.13x slower                                                   |
| fannkuch                   | 410 ms                                                 | 463 ms: 1.13x slower                                                    |
| pyflate                    | 471 ms                                                 | 537 ms: 1.14x slower                                                    |
| float                      | 83.3 ms                                                | 97.8 ms: 1.17x slower                                                   |
| pprint_pformat             | 1.55 sec                                               | 1.82 sec: 1.18x slower                                                  |
| telco                      | 7.18 ms                                                | 8.50 ms: 1.18x slower                                                   |
| nbody                      | 92.2 ms                                                | 112 ms: 1.22x slower                                                    |
| coverage                   | 75.1 ms                                                | 95.9 ms: 1.28x slower                                                   |
| comprehensions             | 20.9 us                                                | 26.9 us: 1.29x slower                                                   |
| hexiom                     | 6.54 ms                                                | 9.49 ms: 1.45x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                            |

Benchmark hidden because not significant (9): json_dumps, xml_etree_generate, bench_mp_pool, sqlglot_transpile, asyncio_websockets, async_tree_cpu_io_mixed, docutils, xml_etree_parse, async_tree_memoization
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
