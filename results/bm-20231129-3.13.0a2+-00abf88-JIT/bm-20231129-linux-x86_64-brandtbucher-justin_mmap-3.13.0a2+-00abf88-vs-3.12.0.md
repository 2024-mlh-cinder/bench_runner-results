
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_mmap
- machine: linux-x86_64
- commit hash: 00abf88
- commit date: 2023-11-29
- overall geometric mean: 1.03x slower \*
- HPT reliability: 99.82%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 277 ms: 1.01x slower                                                |
| chameleon      | 7.41 ms                                                | 7.08 ms: 1.05x faster                                               |
| docutils       | 2.75 sec                                               | 2.69 sec: 1.02x faster                                              |
| tornado_http   | 101 ms                                                 | 97.4 ms: 1.03x faster                                               |
| Geometric mean | (ref)                                                  | 1.02x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 442 ms: 1.07x faster                                                |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 713 ms: 1.02x faster                                                |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 741 ms: 1.02x slower                                                |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                              |
| async_tree_none_tg         | 447 ms                                                 | 458 ms: 1.02x slower                                                |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                              |
| async_tree_memoization_tg  | 574 ms                                                 | 606 ms: 1.06x slower                                                |
| Geometric mean             | (ref)                                                  | 1.01x slower                                                        |

Benchmark hidden because not significant (1): async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.00x slower                                                |
| float          | 83.3 ms                                                | 85.5 ms: 1.03x slower                                               |
| nbody          | 92.2 ms                                                | 101 ms: 1.10x slower                                                |
| Geometric mean | (ref)                                                  | 1.04x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 146 ms: 1.02x faster                                                |
| regex_effbot   | 3.57 ms                                                | 3.73 ms: 1.04x slower                                               |
| regex_dna      | 209 ms                                                 | 222 ms: 1.07x slower                                                |
| regex_v8       | 22.7 ms                                                | 26.0 ms: 1.15x slower                                               |
| Geometric mean | (ref)                                                  | 1.06x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 307 us: 1.06x faster                                                |
| tomli_loads          | 2.30 sec                                               | 2.22 sec: 1.04x faster                                              |
| unpickle             | 15.8 us                                                | 15.5 us: 1.02x faster                                               |
| json_loads           | 28.4 us                                                | 28.1 us: 1.01x faster                                               |
| xml_etree_generate   | 88.7 ms                                                | 89.4 ms: 1.01x slower                                               |
| unpickle_list        | 5.04 us                                                | 5.11 us: 1.01x slower                                               |
| unpickle_pure_python | 230 us                                                 | 233 us: 1.02x slower                                                |
| pickle               | 11.2 us                                                | 11.7 us: 1.04x slower                                               |
| xml_etree_iterparse  | 106 ms                                                 | 111 ms: 1.05x slower                                                |
| pickle_dict          | 33.5 us                                                | 35.6 us: 1.06x slower                                               |
| pickle_list          | 4.67 us                                                | 5.05 us: 1.08x slower                                               |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                        |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_process, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.5 ms: 1.10x slower                                               |
| python_startup_no_site | 6.92 ms                                                | 9.13 ms: 1.32x slower                                               |
| Geometric mean         | (ref)                                                  | 1.20x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 12.3 ms: 1.07x slower                                               |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 119 us: 1.28x faster                                                |
| generators                 | 32.5 ms                                                | 28.8 ms: 1.13x faster                                               |
| logging_format             | 7.10 us                                                | 6.45 us: 1.10x faster                                               |
| logging_simple             | 6.38 us                                                | 5.82 us: 1.10x faster                                               |
| async_tree_none            | 475 ms                                                 | 442 ms: 1.07x faster                                                |
| comprehensions             | 20.9 us                                                | 19.5 us: 1.07x faster                                               |
| raytrace                   | 308 ms                                                 | 289 ms: 1.06x faster                                                |
| pickle_pure_python         | 326 us                                                 | 307 us: 1.06x faster                                                |
| crypto_pyaes               | 83.6 ms                                                | 79.0 ms: 1.06x faster                                               |
| chameleon                  | 7.41 ms                                                | 7.08 ms: 1.05x faster                                               |
| sympy_sum                  | 167 ms                                                 | 160 ms: 1.04x faster                                                |
| coroutines                 | 23.5 ms                                                | 22.6 ms: 1.04x faster                                               |
| tomli_loads                | 2.30 sec                                               | 2.22 sec: 1.04x faster                                              |
| scimark_lu                 | 120 ms                                                 | 116 ms: 1.04x faster                                                |
| asyncio_tcp                | 506 ms                                                 | 489 ms: 1.03x faster                                                |
| tornado_http               | 101 ms                                                 | 97.4 ms: 1.03x faster                                               |
| scimark_sor                | 129 ms                                                 | 125 ms: 1.03x faster                                                |
| deepcopy_reduce            | 3.23 us                                                | 3.14 us: 1.03x faster                                               |
| sympy_str                  | 296 ms                                                 | 288 ms: 1.03x faster                                                |
| gc_traversal               | 4.28 ms                                                | 4.16 ms: 1.03x faster                                               |
| deepcopy                   | 363 us                                                 | 353 us: 1.03x faster                                                |
| docutils                   | 2.75 sec                                               | 2.69 sec: 1.02x faster                                              |
| sqlglot_parse              | 1.35 ms                                                | 1.32 ms: 1.02x faster                                               |
| deepcopy_memo              | 39.7 us                                                | 39.0 us: 1.02x faster                                               |
| dulwich_log                | 68.7 ms                                                | 67.5 ms: 1.02x faster                                               |
| sqlglot_transpile          | 1.68 ms                                                | 1.65 ms: 1.02x faster                                               |
| regex_compile              | 148 ms                                                 | 146 ms: 1.02x faster                                                |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 713 ms: 1.02x faster                                                |
| unpickle                   | 15.8 us                                                | 15.5 us: 1.02x faster                                               |
| pathlib                    | 18.9 ms                                                | 18.7 ms: 1.01x faster                                               |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.28 ms: 1.01x faster                                               |
| json_loads                 | 28.4 us                                                | 28.1 us: 1.01x faster                                               |
| sqlglot_normalize          | 112 ms                                                 | 111 ms: 1.00x faster                                                |
| pidigits                   | 187 ms                                                 | 188 ms: 1.00x slower                                                |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.79 sec: 1.01x slower                                              |
| xml_etree_generate         | 88.7 ms                                                | 89.4 ms: 1.01x slower                                               |
| sympy_expand               | 476 ms                                                 | 479 ms: 1.01x slower                                                |
| async_generators           | 459 ms                                                 | 463 ms: 1.01x slower                                                |
| bench_thread_pool          | 845 us                                                 | 852 us: 1.01x slower                                                |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                               |
| scimark_fft                | 381 ms                                                 | 384 ms: 1.01x slower                                                |
| 2to3                       | 274 ms                                                 | 277 ms: 1.01x slower                                                |
| unpickle_list              | 5.04 us                                                | 5.11 us: 1.01x slower                                               |
| unpickle_pure_python       | 230 us                                                 | 233 us: 1.02x slower                                                |
| logging_silent             | 108 ns                                                 | 109 ns: 1.02x slower                                                |
| richards                   | 46.0 ms                                                | 46.9 ms: 1.02x slower                                               |
| meteor_contest             | 110 ms                                                 | 112 ms: 1.02x slower                                                |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 741 ms: 1.02x slower                                                |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                              |
| async_tree_none_tg         | 447 ms                                                 | 458 ms: 1.02x slower                                                |
| float                      | 83.3 ms                                                | 85.5 ms: 1.03x slower                                               |
| pprint_safe_repr           | 765 ms                                                 | 785 ms: 1.03x slower                                                |
| richards_super             | 51.9 ms                                                | 53.3 ms: 1.03x slower                                               |
| scimark_monte_carlo        | 74.6 ms                                                | 76.9 ms: 1.03x slower                                               |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                              |
| sqlglot_optimize           | 54.8 ms                                                | 56.7 ms: 1.04x slower                                               |
| chaos                      | 67.5 ms                                                | 70.1 ms: 1.04x slower                                               |
| pprint_pformat             | 1.55 sec                                               | 1.62 sec: 1.04x slower                                              |
| pickle                     | 11.2 us                                                | 11.7 us: 1.04x slower                                               |
| regex_effbot               | 3.57 ms                                                | 3.73 ms: 1.04x slower                                               |
| pycparser                  | 1.17 sec                                               | 1.22 sec: 1.04x slower                                              |
| xml_etree_iterparse        | 106 ms                                                 | 111 ms: 1.05x slower                                                |
| async_tree_memoization_tg  | 574 ms                                                 | 606 ms: 1.06x slower                                                |
| pickle_dict                | 33.5 us                                                | 35.6 us: 1.06x slower                                               |
| pyflate                    | 471 ms                                                 | 501 ms: 1.06x slower                                                |
| regex_dna                  | 209 ms                                                 | 222 ms: 1.07x slower                                                |
| fannkuch                   | 410 ms                                                 | 438 ms: 1.07x slower                                                |
| unpack_sequence            | 54.2 ns                                                | 58.1 ns: 1.07x slower                                               |
| mako                       | 11.5 ms                                                | 12.3 ms: 1.07x slower                                               |
| go                         | 140 ms                                                 | 151 ms: 1.08x slower                                                |
| pickle_list                | 4.67 us                                                | 5.05 us: 1.08x slower                                               |
| nqueens                    | 86.2 ms                                                | 94.4 ms: 1.09x slower                                               |
| python_startup             | 9.53 ms                                                | 10.5 ms: 1.10x slower                                               |
| mdp                        | 2.57 sec                                               | 2.82 sec: 1.10x slower                                              |
| nbody                      | 92.2 ms                                                | 101 ms: 1.10x slower                                                |
| deltablue                  | 3.71 ms                                                | 4.10 ms: 1.11x slower                                               |
| regex_v8                   | 22.7 ms                                                | 26.0 ms: 1.15x slower                                               |
| telco                      | 7.18 ms                                                | 8.51 ms: 1.19x slower                                               |
| hexiom                     | 6.54 ms                                                | 7.94 ms: 1.21x slower                                               |
| spectral_norm              | 115 ms                                                 | 141 ms: 1.23x slower                                                |
| coverage                   | 75.1 ms                                                | 96.2 ms: 1.28x slower                                               |
| python_startup_no_site     | 6.92 ms                                                | 9.13 ms: 1.32x slower                                               |
| mypy2                      | 351 ms                                                 | 870 ms: 2.48x slower                                                |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                        |

Benchmark hidden because not significant (10): async_tree_memoization, dask, sympy_integrate, asyncio_websockets, xml_etree_parse, json, sqlite_synth, bench_mp_pool, xml_etree_process, json_dumps
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.82% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
