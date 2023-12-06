
# Results vs. 3.12.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: linux-x86_64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 290 ms: 1.06x slower                                                   |
| chameleon      | 7.41 ms                                                | 7.51 ms: 1.01x slower                                                  |
| docutils       | 2.75 sec                                               | 2.72 sec: 1.01x faster                                                 |
| tornado_http   | 101 ms                                                 | 99.6 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 459 ms: 1.04x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 737 ms: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.22 sec: 1.05x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 765 ms: 1.06x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 474 ms: 1.06x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 619 ms: 1.08x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                           |

Benchmark hidden because not significant (1): async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 197 ms: 1.05x slower                                                   |
| float          | 83.3 ms                                                | 101 ms: 1.21x slower                                                   |
| nbody          | 92.2 ms                                                | 135 ms: 1.46x slower                                                   |
| Geometric mean | (ref)                                                  | 1.23x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.47 ms: 1.03x faster                                                  |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                                   |
| regex_v8       | 22.7 ms                                                | 24.0 ms: 1.06x slower                                                  |
| regex_compile  | 148 ms                                                 | 162 ms: 1.10x slower                                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                                   |
| unpickle             | 15.8 us                                                | 15.1 us: 1.04x faster                                                  |
| json_loads           | 28.4 us                                                | 27.9 us: 1.02x faster                                                  |
| pickle_dict          | 33.5 us                                                | 34.1 us: 1.02x slower                                                  |
| json_dumps           | 10.6 ms                                                | 10.8 ms: 1.02x slower                                                  |
| pickle               | 11.2 us                                                | 11.5 us: 1.02x slower                                                  |
| unpickle_list        | 5.04 us                                                | 5.18 us: 1.03x slower                                                  |
| xml_etree_process    | 61.2 ms                                                | 63.1 ms: 1.03x slower                                                  |
| xml_etree_generate   | 88.7 ms                                                | 92.3 ms: 1.04x slower                                                  |
| unpickle_pure_python | 230 us                                                 | 242 us: 1.05x slower                                                   |
| xml_etree_iterparse  | 106 ms                                                 | 116 ms: 1.09x slower                                                   |
| pickle_list          | 4.67 us                                                | 5.16 us: 1.10x slower                                                  |
| tomli_loads          | 2.30 sec                                               | 2.58 sec: 1.12x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 9.02 ms: 1.30x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 15.4 ms: 1.34x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 122 us: 1.25x faster                                                   |
| unpack_sequence            | 54.2 ns                                                | 45.9 ns: 1.18x faster                                                  |
| generators                 | 32.5 ms                                                | 29.8 ms: 1.09x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 3.94 ms: 1.08x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 305 us: 1.07x faster                                                   |
| coroutines                 | 23.5 ms                                                | 21.9 ms: 1.07x faster                                                  |
| unpickle                   | 15.8 us                                                | 15.1 us: 1.04x faster                                                  |
| asyncio_tcp                | 506 ms                                                 | 487 ms: 1.04x faster                                                   |
| async_tree_none            | 475 ms                                                 | 459 ms: 1.04x faster                                                   |
| logging_simple             | 6.38 us                                                | 6.19 us: 1.03x faster                                                  |
| regex_effbot               | 3.57 ms                                                | 3.47 ms: 1.03x faster                                                  |
| scimark_sor                | 129 ms                                                 | 126 ms: 1.02x faster                                                   |
| sympy_sum                  | 167 ms                                                 | 163 ms: 1.02x faster                                                   |
| json_loads                 | 28.4 us                                                | 27.9 us: 1.02x faster                                                  |
| logging_format             | 7.10 us                                                | 7.01 us: 1.01x faster                                                  |
| json                       | 5.22 ms                                                | 5.16 ms: 1.01x faster                                                  |
| docutils                   | 2.75 sec                                               | 2.72 sec: 1.01x faster                                                 |
| tornado_http               | 101 ms                                                 | 99.6 ms: 1.01x faster                                                  |
| scimark_lu                 | 120 ms                                                 | 119 ms: 1.01x faster                                                   |
| dulwich_log                | 68.7 ms                                                | 69.0 ms: 1.00x slower                                                  |
| pathlib                    | 18.9 ms                                                | 19.1 ms: 1.01x slower                                                  |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                                 |
| chameleon                  | 7.41 ms                                                | 7.51 ms: 1.01x slower                                                  |
| mypy2                      | 351 ms                                                 | 356 ms: 1.02x slower                                                   |
| sympy_str                  | 296 ms                                                 | 301 ms: 1.02x slower                                                   |
| sqlglot_transpile          | 1.68 ms                                                | 1.70 ms: 1.02x slower                                                  |
| pickle_dict                | 33.5 us                                                | 34.1 us: 1.02x slower                                                  |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 737 ms: 1.02x slower                                                   |
| sqlglot_parse              | 1.35 ms                                                | 1.37 ms: 1.02x slower                                                  |
| json_dumps                 | 10.6 ms                                                | 10.8 ms: 1.02x slower                                                  |
| bench_thread_pool          | 845 us                                                 | 862 us: 1.02x slower                                                   |
| sympy_integrate            | 21.2 ms                                                | 21.6 ms: 1.02x slower                                                  |
| pickle                     | 11.2 us                                                | 11.5 us: 1.02x slower                                                  |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                                  |
| logging_silent             | 108 ns                                                 | 110 ns: 1.03x slower                                                   |
| unpickle_list              | 5.04 us                                                | 5.18 us: 1.03x slower                                                  |
| regex_dna                  | 209 ms                                                 | 215 ms: 1.03x slower                                                   |
| xml_etree_process          | 61.2 ms                                                | 63.1 ms: 1.03x slower                                                  |
| sqlite_synth               | 2.83 us                                                | 2.92 us: 1.03x slower                                                  |
| raytrace                   | 308 ms                                                 | 320 ms: 1.04x slower                                                   |
| sqlglot_normalize          | 112 ms                                                 | 116 ms: 1.04x slower                                                   |
| xml_etree_generate         | 88.7 ms                                                | 92.3 ms: 1.04x slower                                                  |
| deepcopy_memo              | 39.7 us                                                | 41.7 us: 1.05x slower                                                  |
| pidigits                   | 187 ms                                                 | 197 ms: 1.05x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.22 sec: 1.05x slower                                                 |
| unpickle_pure_python       | 230 us                                                 | 242 us: 1.05x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 765 ms: 1.06x slower                                                   |
| 2to3                       | 274 ms                                                 | 290 ms: 1.06x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                 |
| sympy_expand               | 476 ms                                                 | 504 ms: 1.06x slower                                                   |
| regex_v8                   | 22.7 ms                                                | 24.0 ms: 1.06x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 474 ms: 1.06x slower                                                   |
| pycparser                  | 1.17 sec                                               | 1.24 sec: 1.06x slower                                                 |
| crypto_pyaes               | 83.6 ms                                                | 89.3 ms: 1.07x slower                                                  |
| richards_super             | 51.9 ms                                                | 55.7 ms: 1.07x slower                                                  |
| meteor_contest             | 110 ms                                                 | 118 ms: 1.07x slower                                                   |
| richards                   | 46.0 ms                                                | 49.5 ms: 1.08x slower                                                  |
| async_tree_memoization_tg  | 574 ms                                                 | 619 ms: 1.08x slower                                                   |
| sqlglot_optimize           | 54.8 ms                                                | 59.4 ms: 1.08x slower                                                  |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| pprint_safe_repr           | 765 ms                                                 | 835 ms: 1.09x slower                                                   |
| xml_etree_iterparse        | 106 ms                                                 | 116 ms: 1.09x slower                                                   |
| regex_compile              | 148 ms                                                 | 162 ms: 1.10x slower                                                   |
| pickle_list                | 4.67 us                                                | 5.16 us: 1.10x slower                                                  |
| tomli_loads                | 2.30 sec                                               | 2.58 sec: 1.12x slower                                                 |
| pprint_pformat             | 1.55 sec                                               | 1.74 sec: 1.12x slower                                                 |
| mdp                        | 2.57 sec                                               | 2.90 sec: 1.13x slower                                                 |
| comprehensions             | 20.9 us                                                | 23.6 us: 1.13x slower                                                  |
| scimark_monte_carlo        | 74.6 ms                                                | 86.4 ms: 1.16x slower                                                  |
| chaos                      | 67.5 ms                                                | 78.3 ms: 1.16x slower                                                  |
| fannkuch                   | 410 ms                                                 | 476 ms: 1.16x slower                                                   |
| go                         | 140 ms                                                 | 163 ms: 1.16x slower                                                   |
| pyflate                    | 471 ms                                                 | 550 ms: 1.17x slower                                                   |
| nqueens                    | 86.2 ms                                                | 101 ms: 1.17x slower                                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.30 ms: 1.18x slower                                                  |
| telco                      | 7.18 ms                                                | 8.57 ms: 1.19x slower                                                  |
| float                      | 83.3 ms                                                | 101 ms: 1.21x slower                                                   |
| coverage                   | 75.1 ms                                                | 95.3 ms: 1.27x slower                                                  |
| scimark_fft                | 381 ms                                                 | 489 ms: 1.28x slower                                                   |
| python_startup_no_site     | 6.92 ms                                                | 9.02 ms: 1.30x slower                                                  |
| mako                       | 11.5 ms                                                | 15.4 ms: 1.34x slower                                                  |
| spectral_norm              | 115 ms                                                 | 161 ms: 1.40x slower                                                   |
| hexiom                     | 6.54 ms                                                | 9.33 ms: 1.43x slower                                                  |
| deltablue                  | 3.71 ms                                                | 5.31 ms: 1.43x slower                                                  |
| nbody                      | 92.2 ms                                                | 135 ms: 1.46x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.06x slower                                                           |

Benchmark hidden because not significant (8): deepcopy, async_generators, asyncio_websockets, deepcopy_reduce, bench_mp_pool, dask, xml_etree_parse, async_tree_memoization
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
