
# Results vs. 3.12.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: linux-x86_64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.03x faster \*
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| chameleon      | 7.41 ms                                                | 6.90 ms: 1.07x faster                                                  |
| docutils       | 2.75 sec                                               | 2.60 sec: 1.06x faster                                                 |
| tornado_http   | 101 ms                                                 | 95.4 ms: 1.05x faster                                                  |
| Geometric mean | (ref)                                                  | 1.06x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 438 ms: 1.09x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 566 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 709 ms: 1.02x faster                                                   |
| async_tree_none_tg         | 447 ms                                                 | 454 ms: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 740 ms: 1.02x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 598 ms: 1.04x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.00x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 83.3 ms                                                | 82.5 ms: 1.01x faster                                                  |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                                   |
| nbody          | 92.2 ms                                                | 97.7 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 133 ms: 1.11x faster                                                   |
| regex_effbot   | 3.57 ms                                                | 3.62 ms: 1.01x slower                                                  |
| regex_dna      | 209 ms                                                 | 221 ms: 1.06x slower                                                   |
| regex_v8       | 22.7 ms                                                | 25.5 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                                   |
| tomli_loads          | 2.30 sec                                               | 2.16 sec: 1.06x faster                                                 |
| unpickle             | 15.8 us                                                | 15.0 us: 1.05x faster                                                  |
| unpickle_pure_python | 230 us                                                 | 221 us: 1.04x faster                                                   |
| xml_etree_process    | 61.2 ms                                                | 59.4 ms: 1.03x faster                                                  |
| pickle_dict          | 33.5 us                                                | 32.5 us: 1.03x faster                                                  |
| xml_etree_generate   | 88.7 ms                                                | 87.1 ms: 1.02x faster                                                  |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| unpickle_list        | 5.04 us                                                | 5.24 us: 1.04x slower                                                  |
| pickle_list          | 4.67 us                                                | 4.88 us: 1.04x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (4): xml_etree_parse, pickle, json_loads, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 9.04 ms: 1.31x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.0 ms: 1.04x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 115 us: 1.33x faster                                                   |
| comprehensions             | 20.9 us                                                | 16.4 us: 1.28x faster                                                  |
| unpack_sequence            | 54.2 ns                                                | 46.1 ns: 1.18x faster                                                  |
| sympy_sum                  | 167 ms                                                 | 147 ms: 1.14x faster                                                   |
| crypto_pyaes               | 83.6 ms                                                | 73.6 ms: 1.14x faster                                                  |
| deltablue                  | 3.71 ms                                                | 3.28 ms: 1.13x faster                                                  |
| logging_format             | 7.10 us                                                | 6.30 us: 1.13x faster                                                  |
| logging_simple             | 6.38 us                                                | 5.72 us: 1.12x faster                                                  |
| raytrace                   | 308 ms                                                 | 277 ms: 1.11x faster                                                   |
| sympy_str                  | 296 ms                                                 | 266 ms: 1.11x faster                                                   |
| gc_traversal               | 4.28 ms                                                | 3.85 ms: 1.11x faster                                                  |
| regex_compile              | 148 ms                                                 | 133 ms: 1.11x faster                                                   |
| chaos                      | 67.5 ms                                                | 61.4 ms: 1.10x faster                                                  |
| sympy_integrate            | 21.2 ms                                                | 19.4 ms: 1.09x faster                                                  |
| coroutines                 | 23.5 ms                                                | 21.6 ms: 1.09x faster                                                  |
| generators                 | 32.5 ms                                                | 29.8 ms: 1.09x faster                                                  |
| async_tree_none            | 475 ms                                                 | 438 ms: 1.09x faster                                                   |
| chameleon                  | 7.41 ms                                                | 6.90 ms: 1.07x faster                                                  |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.98 ms: 1.07x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 305 us: 1.07x faster                                                   |
| nqueens                    | 86.2 ms                                                | 80.9 ms: 1.07x faster                                                  |
| tomli_loads                | 2.30 sec                                               | 2.16 sec: 1.06x faster                                                 |
| scimark_monte_carlo        | 74.6 ms                                                | 70.2 ms: 1.06x faster                                                  |
| docutils                   | 2.75 sec                                               | 2.60 sec: 1.06x faster                                                 |
| sqlglot_parse              | 1.35 ms                                                | 1.28 ms: 1.06x faster                                                  |
| sympy_expand               | 476 ms                                                 | 450 ms: 1.06x faster                                                   |
| sqlglot_normalize          | 112 ms                                                 | 106 ms: 1.06x faster                                                   |
| hexiom                     | 6.54 ms                                                | 6.20 ms: 1.06x faster                                                  |
| tornado_http               | 101 ms                                                 | 95.4 ms: 1.05x faster                                                  |
| asyncio_tcp                | 506 ms                                                 | 481 ms: 1.05x faster                                                   |
| sqlglot_transpile          | 1.68 ms                                                | 1.59 ms: 1.05x faster                                                  |
| deepcopy                   | 363 us                                                 | 346 us: 1.05x faster                                                   |
| unpickle                   | 15.8 us                                                | 15.0 us: 1.05x faster                                                  |
| scimark_sor                | 129 ms                                                 | 124 ms: 1.05x faster                                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.09 us: 1.04x faster                                                  |
| dulwich_log                | 68.7 ms                                                | 65.9 ms: 1.04x faster                                                  |
| mako                       | 11.5 ms                                                | 11.0 ms: 1.04x faster                                                  |
| unpickle_pure_python       | 230 us                                                 | 221 us: 1.04x faster                                                   |
| 2to3                       | 274 ms                                                 | 264 ms: 1.04x faster                                                   |
| deepcopy_memo              | 39.7 us                                                | 38.3 us: 1.04x faster                                                  |
| async_generators           | 459 ms                                                 | 444 ms: 1.03x faster                                                   |
| scimark_fft                | 381 ms                                                 | 369 ms: 1.03x faster                                                   |
| xml_etree_process          | 61.2 ms                                                | 59.4 ms: 1.03x faster                                                  |
| spectral_norm              | 115 ms                                                 | 111 ms: 1.03x faster                                                   |
| pickle_dict                | 33.5 us                                                | 32.5 us: 1.03x faster                                                  |
| scimark_lu                 | 120 ms                                                 | 117 ms: 1.03x faster                                                   |
| pathlib                    | 18.9 ms                                                | 18.4 ms: 1.03x faster                                                  |
| pprint_safe_repr           | 765 ms                                                 | 744 ms: 1.03x faster                                                   |
| dask                       | 369 ms                                                 | 359 ms: 1.03x faster                                                   |
| mypy2                      | 351 ms                                                 | 342 ms: 1.03x faster                                                   |
| sqlglot_optimize           | 54.8 ms                                                | 53.5 ms: 1.03x faster                                                  |
| async_tree_memoization     | 580 ms                                                 | 566 ms: 1.02x faster                                                   |
| meteor_contest             | 110 ms                                                 | 107 ms: 1.02x faster                                                   |
| pprint_pformat             | 1.55 sec                                               | 1.52 sec: 1.02x faster                                                 |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 709 ms: 1.02x faster                                                   |
| fannkuch                   | 410 ms                                                 | 402 ms: 1.02x faster                                                   |
| xml_etree_generate         | 88.7 ms                                                | 87.1 ms: 1.02x faster                                                  |
| pyflate                    | 471 ms                                                 | 465 ms: 1.01x faster                                                   |
| bench_thread_pool          | 845 us                                                 | 835 us: 1.01x faster                                                   |
| sqlite_synth               | 2.83 us                                                | 2.81 us: 1.01x faster                                                  |
| float                      | 83.3 ms                                                | 82.5 ms: 1.01x faster                                                  |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                  |
| json                       | 5.22 ms                                                | 5.19 ms: 1.01x faster                                                  |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.78 sec: 1.00x slower                                                 |
| bench_mp_pool              | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                  |
| go                         | 140 ms                                                 | 141 ms: 1.01x slower                                                   |
| regex_effbot               | 3.57 ms                                                | 3.62 ms: 1.01x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 454 ms: 1.02x slower                                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.02x slower                                                  |
| logging_silent             | 108 ns                                                 | 109 ns: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.19 sec: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 740 ms: 1.02x slower                                                   |
| pycparser                  | 1.17 sec                                               | 1.21 sec: 1.03x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.23 sec: 1.03x slower                                                 |
| richards_super             | 51.9 ms                                                | 53.7 ms: 1.03x slower                                                  |
| unpickle_list              | 5.04 us                                                | 5.24 us: 1.04x slower                                                  |
| richards                   | 46.0 ms                                                | 47.9 ms: 1.04x slower                                                  |
| async_tree_memoization_tg  | 574 ms                                                 | 598 ms: 1.04x slower                                                   |
| pidigits                   | 187 ms                                                 | 195 ms: 1.04x slower                                                   |
| pickle_list                | 4.67 us                                                | 4.88 us: 1.04x slower                                                  |
| regex_dna                  | 209 ms                                                 | 221 ms: 1.06x slower                                                   |
| nbody                      | 92.2 ms                                                | 97.7 ms: 1.06x slower                                                  |
| mdp                        | 2.57 sec                                               | 2.76 sec: 1.07x slower                                                 |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 25.5 ms: 1.13x slower                                                  |
| telco                      | 7.18 ms                                                | 8.27 ms: 1.15x slower                                                  |
| coverage                   | 75.1 ms                                                | 94.3 ms: 1.25x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 9.04 ms: 1.31x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                           |

Benchmark hidden because not significant (5): xml_etree_parse, asyncio_websockets, pickle, json_loads, xml_etree_iterparse
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
