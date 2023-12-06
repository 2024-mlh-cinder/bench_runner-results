
# Results vs. 3.12.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: 7736e18
- commit date: 2023-11-02
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.55%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 279 ms: 1.02x slower                                                             |
| chameleon      | 7.41 ms                                                | 7.09 ms: 1.04x faster                                                            |
| docutils       | 2.75 sec                                               | 2.71 sec: 1.02x faster                                                           |
| tornado_http   | 101 ms                                                 | 98.0 ms: 1.03x faster                                                            |
| Geometric mean | (ref)                                                  | 1.02x faster                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 452 ms: 1.05x faster                                                             |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 753 ms: 1.04x slower                                                             |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                           |
| async_tree_none_tg         | 447 ms                                                 | 469 ms: 1.05x slower                                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                                           |
| async_tree_memoization_tg  | 574 ms                                                 | 612 ms: 1.07x slower                                                             |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                                     |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 196 ms: 1.05x slower                                                             |
| float          | 83.3 ms                                                | 96.2 ms: 1.16x slower                                                            |
| nbody          | 92.2 ms                                                | 110 ms: 1.19x slower                                                             |
| Geometric mean | (ref)                                                  | 1.13x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 211 ms: 1.01x slower                                                             |
| regex_effbot   | 3.57 ms                                                | 3.73 ms: 1.04x slower                                                            |
| regex_compile  | 148 ms                                                 | 157 ms: 1.06x slower                                                             |
| regex_v8       | 22.7 ms                                                | 25.7 ms: 1.13x slower                                                            |
| Geometric mean | (ref)                                                  | 1.06x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                                            |
| pickle_pure_python   | 326 us                                                 | 310 us: 1.05x faster                                                             |
| json_loads           | 28.4 us                                                | 27.7 us: 1.03x faster                                                            |
| pickle_dict          | 33.5 us                                                | 32.7 us: 1.03x faster                                                            |
| xml_etree_process    | 61.2 ms                                                | 59.9 ms: 1.02x faster                                                            |
| xml_etree_generate   | 88.7 ms                                                | 87.0 ms: 1.02x faster                                                            |
| pickle               | 11.2 us                                                | 11.2 us: 1.00x faster                                                            |
| json_dumps           | 10.6 ms                                                | 10.7 ms: 1.01x slower                                                            |
| unpickle_list        | 5.04 us                                                | 5.09 us: 1.01x slower                                                            |
| unpickle_pure_python | 230 us                                                 | 239 us: 1.04x slower                                                             |
| xml_etree_iterparse  | 106 ms                                                 | 111 ms: 1.05x slower                                                             |
| tomli_loads          | 2.30 sec                                               | 2.49 sec: 1.08x slower                                                           |
| pickle_list          | 4.67 us                                                | 5.10 us: 1.09x slower                                                            |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                                     |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| python_startup_no_site | 6.92 ms                                                | 9.00 ms: 1.30x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 14.0 ms: 1.22x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 125 us: 1.23x faster                                                             |
| gc_traversal               | 4.28 ms                                                | 3.57 ms: 1.20x faster                                                            |
| crypto_pyaes               | 83.6 ms                                                | 75.5 ms: 1.11x faster                                                            |
| logging_format             | 7.10 us                                                | 6.45 us: 1.10x faster                                                            |
| generators                 | 32.5 ms                                                | 29.6 ms: 1.10x faster                                                            |
| unpack_sequence            | 54.2 ns                                                | 49.4 ns: 1.10x faster                                                            |
| sympy_sum                  | 167 ms                                                 | 153 ms: 1.09x faster                                                             |
| logging_simple             | 6.38 us                                                | 5.94 us: 1.07x faster                                                            |
| raytrace                   | 308 ms                                                 | 289 ms: 1.07x faster                                                             |
| unpickle                   | 15.8 us                                                | 14.9 us: 1.06x faster                                                            |
| deepcopy_reduce            | 3.23 us                                                | 3.05 us: 1.06x faster                                                            |
| sympy_str                  | 296 ms                                                 | 281 ms: 1.05x faster                                                             |
| pickle_pure_python         | 326 us                                                 | 310 us: 1.05x faster                                                             |
| async_tree_none            | 475 ms                                                 | 452 ms: 1.05x faster                                                             |
| coroutines                 | 23.5 ms                                                | 22.3 ms: 1.05x faster                                                            |
| chameleon                  | 7.41 ms                                                | 7.09 ms: 1.04x faster                                                            |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.04x faster                                                             |
| tornado_http               | 101 ms                                                 | 98.0 ms: 1.03x faster                                                            |
| deepcopy                   | 363 us                                                 | 353 us: 1.03x faster                                                             |
| json_loads                 | 28.4 us                                                | 27.7 us: 1.03x faster                                                            |
| pickle_dict                | 33.5 us                                                | 32.7 us: 1.03x faster                                                            |
| asyncio_tcp                | 506 ms                                                 | 493 ms: 1.02x faster                                                             |
| spectral_norm              | 115 ms                                                 | 112 ms: 1.02x faster                                                             |
| dulwich_log                | 68.7 ms                                                | 67.2 ms: 1.02x faster                                                            |
| scimark_monte_carlo        | 74.6 ms                                                | 72.9 ms: 1.02x faster                                                            |
| xml_etree_process          | 61.2 ms                                                | 59.9 ms: 1.02x faster                                                            |
| xml_etree_generate         | 88.7 ms                                                | 87.0 ms: 1.02x faster                                                            |
| docutils                   | 2.75 sec                                               | 2.71 sec: 1.02x faster                                                           |
| scimark_lu                 | 120 ms                                                 | 119 ms: 1.02x faster                                                             |
| json                       | 5.22 ms                                                | 5.15 ms: 1.01x faster                                                            |
| bench_thread_pool          | 845 us                                                 | 835 us: 1.01x faster                                                             |
| sympy_integrate            | 21.2 ms                                                | 21.0 ms: 1.01x faster                                                            |
| async_generators           | 459 ms                                                 | 455 ms: 1.01x faster                                                             |
| sqlglot_optimize           | 54.8 ms                                                | 54.5 ms: 1.01x faster                                                            |
| sqlglot_parse              | 1.35 ms                                                | 1.34 ms: 1.00x faster                                                            |
| pickle                     | 11.2 us                                                | 11.2 us: 1.00x faster                                                            |
| json_dumps                 | 10.6 ms                                                | 10.7 ms: 1.01x slower                                                            |
| mypy2                      | 351 ms                                                 | 354 ms: 1.01x slower                                                             |
| unpickle_list              | 5.04 us                                                | 5.09 us: 1.01x slower                                                            |
| chaos                      | 67.5 ms                                                | 68.2 ms: 1.01x slower                                                            |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                                            |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                                           |
| regex_dna                  | 209 ms                                                 | 211 ms: 1.01x slower                                                             |
| sqlite_synth               | 2.83 us                                                | 2.88 us: 1.01x slower                                                            |
| 2to3                       | 274 ms                                                 | 279 ms: 1.02x slower                                                             |
| scimark_sor                | 129 ms                                                 | 132 ms: 1.02x slower                                                             |
| fannkuch                   | 410 ms                                                 | 420 ms: 1.02x slower                                                             |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.51 ms: 1.03x slower                                                            |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 753 ms: 1.04x slower                                                             |
| unpickle_pure_python       | 230 us                                                 | 239 us: 1.04x slower                                                             |
| pycparser                  | 1.17 sec                                               | 1.22 sec: 1.04x slower                                                           |
| pathlib                    | 18.9 ms                                                | 19.7 ms: 1.04x slower                                                            |
| deepcopy_memo              | 39.7 us                                                | 41.4 us: 1.04x slower                                                            |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                           |
| regex_effbot               | 3.57 ms                                                | 3.73 ms: 1.04x slower                                                            |
| scimark_fft                | 381 ms                                                 | 398 ms: 1.04x slower                                                             |
| pidigits                   | 187 ms                                                 | 196 ms: 1.05x slower                                                             |
| xml_etree_iterparse        | 106 ms                                                 | 111 ms: 1.05x slower                                                             |
| meteor_contest             | 110 ms                                                 | 115 ms: 1.05x slower                                                             |
| async_tree_none_tg         | 447 ms                                                 | 469 ms: 1.05x slower                                                             |
| pprint_safe_repr           | 765 ms                                                 | 804 ms: 1.05x slower                                                             |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                                           |
| comprehensions             | 20.9 us                                                | 22.2 us: 1.06x slower                                                            |
| regex_compile              | 148 ms                                                 | 157 ms: 1.06x slower                                                             |
| async_tree_memoization_tg  | 574 ms                                                 | 612 ms: 1.07x slower                                                             |
| pprint_pformat             | 1.55 sec                                               | 1.67 sec: 1.08x slower                                                           |
| tomli_loads                | 2.30 sec                                               | 2.49 sec: 1.08x slower                                                           |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| pickle_list                | 4.67 us                                                | 5.10 us: 1.09x slower                                                            |
| pyflate                    | 471 ms                                                 | 514 ms: 1.09x slower                                                             |
| richards                   | 46.0 ms                                                | 50.4 ms: 1.10x slower                                                            |
| mdp                        | 2.57 sec                                               | 2.84 sec: 1.10x slower                                                           |
| richards_super             | 51.9 ms                                                | 57.6 ms: 1.11x slower                                                            |
| nqueens                    | 86.2 ms                                                | 95.9 ms: 1.11x slower                                                            |
| regex_v8                   | 22.7 ms                                                | 25.7 ms: 1.13x slower                                                            |
| go                         | 140 ms                                                 | 159 ms: 1.13x slower                                                             |
| float                      | 83.3 ms                                                | 96.2 ms: 1.16x slower                                                            |
| telco                      | 7.18 ms                                                | 8.37 ms: 1.17x slower                                                            |
| nbody                      | 92.2 ms                                                | 110 ms: 1.19x slower                                                             |
| mako                       | 11.5 ms                                                | 14.0 ms: 1.22x slower                                                            |
| deltablue                  | 3.71 ms                                                | 4.58 ms: 1.23x slower                                                            |
| coverage                   | 75.1 ms                                                | 93.5 ms: 1.24x slower                                                            |
| python_startup_no_site     | 6.92 ms                                                | 9.00 ms: 1.30x slower                                                            |
| hexiom                     | 6.54 ms                                                | 8.74 ms: 1.34x slower                                                            |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                                     |

Benchmark hidden because not significant (8): xml_etree_parse, sqlglot_transpile, sympy_expand, async_tree_memoization, asyncio_websockets, async_tree_cpu_io_mixed, bench_mp_pool, logging_silent
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.55% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
