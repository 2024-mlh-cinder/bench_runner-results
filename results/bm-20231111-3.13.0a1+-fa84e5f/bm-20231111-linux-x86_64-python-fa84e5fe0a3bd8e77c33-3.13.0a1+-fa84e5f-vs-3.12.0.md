
# Results vs. 3.12.0

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: linux-x86_64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 261 ms: 1.05x faster                                                   |
| chameleon      | 7.41 ms                                                | 6.96 ms: 1.06x faster                                                  |
| docutils       | 2.75 sec                                               | 2.59 sec: 1.06x faster                                                 |
| tornado_http   | 101 ms                                                 | 94.4 ms: 1.07x faster                                                  |
| Geometric mean | (ref)                                                  | 1.06x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 435 ms: 1.09x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 559 ms: 1.04x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 709 ms: 1.02x faster                                                   |
| async_tree_none_tg         | 447 ms                                                 | 455 ms: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.02x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 738 ms: 1.02x slower                                                   |
| async_tree_io_tg           | 1.19 sec                                               | 1.22 sec: 1.03x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 594 ms: 1.03x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.00x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 92.2 ms                                                | 88.2 ms: 1.05x faster                                                  |
| float          | 83.3 ms                                                | 81.1 ms: 1.03x faster                                                  |
| pidigits       | 187 ms                                                 | 188 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                  | 1.02x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 134 ms: 1.11x faster                                                   |
| regex_effbot   | 3.57 ms                                                | 3.61 ms: 1.01x slower                                                  |
| regex_dna      | 209 ms                                                 | 212 ms: 1.02x slower                                                   |
| regex_v8       | 22.7 ms                                                | 25.7 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.6 us: 1.08x faster                                                  |
| pickle_pure_python   | 326 us                                                 | 303 us: 1.08x faster                                                   |
| tomli_loads          | 2.30 sec                                               | 2.14 sec: 1.07x faster                                                 |
| unpickle_pure_python | 230 us                                                 | 219 us: 1.05x faster                                                   |
| xml_etree_process    | 61.2 ms                                                | 59.0 ms: 1.04x faster                                                  |
| xml_etree_generate   | 88.7 ms                                                | 85.8 ms: 1.03x faster                                                  |
| json_dumps           | 10.6 ms                                                | 10.3 ms: 1.03x faster                                                  |
| json_loads           | 28.4 us                                                | 27.9 us: 1.02x faster                                                  |
| xml_etree_iterparse  | 106 ms                                                 | 105 ms: 1.01x faster                                                   |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| pickle               | 11.2 us                                                | 11.3 us: 1.01x slower                                                  |
| pickle_dict          | 33.5 us                                                | 33.9 us: 1.01x slower                                                  |
| unpickle_list        | 5.04 us                                                | 5.30 us: 1.05x slower                                                  |
| pickle_list          | 4.67 us                                                | 5.03 us: 1.08x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 9.02 ms: 1.30x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 11.4 ms: 1.01x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 116 us: 1.33x faster                                                   |
| comprehensions             | 20.9 us                                                | 16.4 us: 1.28x faster                                                  |
| unpack_sequence            | 54.2 ns                                                | 46.1 ns: 1.17x faster                                                  |
| crypto_pyaes               | 83.6 ms                                                | 71.3 ms: 1.17x faster                                                  |
| logging_format             | 7.10 us                                                | 6.21 us: 1.14x faster                                                  |
| sympy_sum                  | 167 ms                                                 | 147 ms: 1.14x faster                                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 4.68 ms: 1.14x faster                                                  |
| deltablue                  | 3.71 ms                                                | 3.29 ms: 1.13x faster                                                  |
| generators                 | 32.5 ms                                                | 28.8 ms: 1.13x faster                                                  |
| logging_simple             | 6.38 us                                                | 5.69 us: 1.12x faster                                                  |
| chaos                      | 67.5 ms                                                | 60.2 ms: 1.12x faster                                                  |
| raytrace                   | 308 ms                                                 | 275 ms: 1.12x faster                                                   |
| sympy_str                  | 296 ms                                                 | 268 ms: 1.11x faster                                                   |
| regex_compile              | 148 ms                                                 | 134 ms: 1.11x faster                                                   |
| sympy_integrate            | 21.2 ms                                                | 19.3 ms: 1.10x faster                                                  |
| async_tree_none            | 475 ms                                                 | 435 ms: 1.09x faster                                                   |
| scimark_monte_carlo        | 74.6 ms                                                | 68.5 ms: 1.09x faster                                                  |
| unpickle                   | 15.8 us                                                | 14.6 us: 1.08x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 303 us: 1.08x faster                                                   |
| tomli_loads                | 2.30 sec                                               | 2.14 sec: 1.07x faster                                                 |
| scimark_sor                | 129 ms                                                 | 121 ms: 1.07x faster                                                   |
| tornado_http               | 101 ms                                                 | 94.4 ms: 1.07x faster                                                  |
| coroutines                 | 23.5 ms                                                | 22.0 ms: 1.06x faster                                                  |
| chameleon                  | 7.41 ms                                                | 6.96 ms: 1.06x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 105 ms: 1.06x faster                                                   |
| docutils                   | 2.75 sec                                               | 2.59 sec: 1.06x faster                                                 |
| sqlglot_parse              | 1.35 ms                                                | 1.27 ms: 1.06x faster                                                  |
| deepcopy_reduce            | 3.23 us                                                | 3.04 us: 1.06x faster                                                  |
| hexiom                     | 6.54 ms                                                | 6.17 ms: 1.06x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 4.04 ms: 1.06x faster                                                  |
| deepcopy                   | 363 us                                                 | 343 us: 1.06x faster                                                   |
| sqlglot_transpile          | 1.68 ms                                                | 1.58 ms: 1.06x faster                                                  |
| sympy_expand               | 476 ms                                                 | 450 ms: 1.06x faster                                                   |
| nqueens                    | 86.2 ms                                                | 81.7 ms: 1.06x faster                                                  |
| scimark_lu                 | 120 ms                                                 | 114 ms: 1.05x faster                                                   |
| 2to3                       | 274 ms                                                 | 261 ms: 1.05x faster                                                   |
| dulwich_log                | 68.7 ms                                                | 65.5 ms: 1.05x faster                                                  |
| asyncio_tcp                | 506 ms                                                 | 482 ms: 1.05x faster                                                   |
| scimark_fft                | 381 ms                                                 | 364 ms: 1.05x faster                                                   |
| unpickle_pure_python       | 230 us                                                 | 219 us: 1.05x faster                                                   |
| nbody                      | 92.2 ms                                                | 88.2 ms: 1.05x faster                                                  |
| pprint_safe_repr           | 765 ms                                                 | 733 ms: 1.04x faster                                                   |
| fannkuch                   | 410 ms                                                 | 394 ms: 1.04x faster                                                   |
| xml_etree_process          | 61.2 ms                                                | 59.0 ms: 1.04x faster                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.49 sec: 1.04x faster                                                 |
| async_tree_memoization     | 580 ms                                                 | 559 ms: 1.04x faster                                                   |
| xml_etree_generate         | 88.7 ms                                                | 85.8 ms: 1.03x faster                                                  |
| mypy2                      | 351 ms                                                 | 339 ms: 1.03x faster                                                   |
| deepcopy_memo              | 39.7 us                                                | 38.4 us: 1.03x faster                                                  |
| async_generators           | 459 ms                                                 | 445 ms: 1.03x faster                                                   |
| logging_silent             | 108 ns                                                 | 104 ns: 1.03x faster                                                   |
| json_dumps                 | 10.6 ms                                                | 10.3 ms: 1.03x faster                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 53.3 ms: 1.03x faster                                                  |
| float                      | 83.3 ms                                                | 81.1 ms: 1.03x faster                                                  |
| spectral_norm              | 115 ms                                                 | 112 ms: 1.02x faster                                                   |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 709 ms: 1.02x faster                                                   |
| bench_thread_pool          | 845 us                                                 | 828 us: 1.02x faster                                                   |
| json                       | 5.22 ms                                                | 5.13 ms: 1.02x faster                                                  |
| json_loads                 | 28.4 us                                                | 27.9 us: 1.02x faster                                                  |
| meteor_contest             | 110 ms                                                 | 109 ms: 1.01x faster                                                   |
| mdp                        | 2.57 sec                                               | 2.55 sec: 1.01x faster                                                 |
| xml_etree_iterparse        | 106 ms                                                 | 105 ms: 1.01x faster                                                   |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| pyflate                    | 471 ms                                                 | 468 ms: 1.01x faster                                                   |
| sqlite_synth               | 2.83 us                                                | 2.82 us: 1.01x faster                                                  |
| pycparser                  | 1.17 sec                                               | 1.16 sec: 1.01x faster                                                 |
| mako                       | 11.5 ms                                                | 11.4 ms: 1.01x faster                                                  |
| go                         | 140 ms                                                 | 140 ms: 1.01x faster                                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.78 sec: 1.00x slower                                                 |
| pidigits                   | 187 ms                                                 | 188 ms: 1.00x slower                                                   |
| pathlib                    | 18.9 ms                                                | 19.0 ms: 1.01x slower                                                  |
| pickle                     | 11.2 us                                                | 11.3 us: 1.01x slower                                                  |
| regex_effbot               | 3.57 ms                                                | 3.61 ms: 1.01x slower                                                  |
| pickle_dict                | 33.5 us                                                | 33.9 us: 1.01x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 455 ms: 1.02x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.18 sec: 1.02x slower                                                 |
| regex_dna                  | 209 ms                                                 | 212 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 738 ms: 1.02x slower                                                   |
| create_gc_cycles           | 1.45 ms                                                | 1.48 ms: 1.02x slower                                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.22 sec: 1.03x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 594 ms: 1.03x slower                                                   |
| richards                   | 46.0 ms                                                | 47.7 ms: 1.04x slower                                                  |
| richards_super             | 51.9 ms                                                | 54.3 ms: 1.05x slower                                                  |
| unpickle_list              | 5.04 us                                                | 5.30 us: 1.05x slower                                                  |
| pickle_list                | 4.67 us                                                | 5.03 us: 1.08x slower                                                  |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                  |
| regex_v8                   | 22.7 ms                                                | 25.7 ms: 1.13x slower                                                  |
| telco                      | 7.18 ms                                                | 8.29 ms: 1.16x slower                                                  |
| coverage                   | 75.1 ms                                                | 96.1 ms: 1.28x slower                                                  |
| python_startup_no_site     | 6.92 ms                                                | 9.02 ms: 1.30x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.03x faster                                                           |

Benchmark hidden because not significant (2): asyncio_websockets, bench_mp_pool
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
