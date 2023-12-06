
# Results vs. 3.12.0

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 3d16eaf
- commit date: 2023-11-02
- overall geometric mean: 1.03x slower \*
- HPT reliability: 99.93%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 282 ms: 1.03x slower                                                  |
| chameleon      | 7.41 ms                                                | 7.14 ms: 1.04x faster                                                 |
| docutils       | 2.75 sec                                               | 2.71 sec: 1.02x faster                                                |
| tornado_http   | 101 ms                                                 | 98.2 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 454 ms: 1.05x faster                                                  |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 749 ms: 1.03x slower                                                  |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                |
| async_tree_none_tg         | 447 ms                                                 | 467 ms: 1.04x slower                                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                                |
| async_tree_memoization_tg  | 574 ms                                                 | 607 ms: 1.06x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                          |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 196 ms: 1.05x slower                                                  |
| float          | 83.3 ms                                                | 97.0 ms: 1.16x slower                                                 |
| nbody          | 92.2 ms                                                | 113 ms: 1.23x slower                                                  |
| Geometric mean | (ref)                                                  | 1.15x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.44 ms: 1.04x faster                                                 |
| regex_dna      | 209 ms                                                 | 212 ms: 1.02x slower                                                  |
| regex_compile  | 148 ms                                                 | 158 ms: 1.07x slower                                                  |
| regex_v8       | 22.7 ms                                                | 24.9 ms: 1.10x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 303 us: 1.08x faster                                                  |
| unpickle             | 15.8 us                                                | 15.0 us: 1.05x faster                                                 |
| xml_etree_process    | 61.2 ms                                                | 59.9 ms: 1.02x faster                                                 |
| json_loads           | 28.4 us                                                | 27.9 us: 1.02x faster                                                 |
| xml_etree_generate   | 88.7 ms                                                | 88.0 ms: 1.01x faster                                                 |
| unpickle_list        | 5.04 us                                                | 5.02 us: 1.01x faster                                                 |
| json_dumps           | 10.6 ms                                                | 10.6 ms: 1.01x slower                                                 |
| pickle_dict          | 33.5 us                                                | 34.4 us: 1.03x slower                                                 |
| pickle               | 11.2 us                                                | 11.6 us: 1.03x slower                                                 |
| unpickle_pure_python | 230 us                                                 | 237 us: 1.03x slower                                                  |
| xml_etree_iterparse  | 106 ms                                                 | 111 ms: 1.05x slower                                                  |
| tomli_loads          | 2.30 sec                                               | 2.47 sec: 1.07x slower                                                |
| pickle_list          | 4.67 us                                                | 5.07 us: 1.09x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                          |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                 |
| python_startup_no_site | 6.92 ms                                                | 9.00 ms: 1.30x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 13.7 ms: 1.19x slower                                                 |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 128 us: 1.20x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 3.91 ms: 1.09x faster                                                 |
| logging_format             | 7.10 us                                                | 6.49 us: 1.09x faster                                                 |
| generators                 | 32.5 ms                                                | 29.7 ms: 1.09x faster                                                 |
| crypto_pyaes               | 83.6 ms                                                | 77.0 ms: 1.09x faster                                                 |
| sympy_sum                  | 167 ms                                                 | 155 ms: 1.08x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 303 us: 1.08x faster                                                  |
| logging_simple             | 6.38 us                                                | 5.95 us: 1.07x faster                                                 |
| unpickle                   | 15.8 us                                                | 15.0 us: 1.05x faster                                                 |
| raytrace                   | 308 ms                                                 | 293 ms: 1.05x faster                                                  |
| async_tree_none            | 475 ms                                                 | 454 ms: 1.05x faster                                                  |
| coroutines                 | 23.5 ms                                                | 22.5 ms: 1.04x faster                                                 |
| sympy_str                  | 296 ms                                                 | 284 ms: 1.04x faster                                                  |
| regex_effbot               | 3.57 ms                                                | 3.44 ms: 1.04x faster                                                 |
| chameleon                  | 7.41 ms                                                | 7.14 ms: 1.04x faster                                                 |
| deepcopy_reduce            | 3.23 us                                                | 3.13 us: 1.03x faster                                                 |
| asyncio_tcp                | 506 ms                                                 | 490 ms: 1.03x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                                  |
| tornado_http               | 101 ms                                                 | 98.2 ms: 1.02x faster                                                 |
| xml_etree_process          | 61.2 ms                                                | 59.9 ms: 1.02x faster                                                 |
| dulwich_log                | 68.7 ms                                                | 67.3 ms: 1.02x faster                                                 |
| json                       | 5.22 ms                                                | 5.12 ms: 1.02x faster                                                 |
| deepcopy                   | 363 us                                                 | 356 us: 1.02x faster                                                  |
| json_loads                 | 28.4 us                                                | 27.9 us: 1.02x faster                                                 |
| docutils                   | 2.75 sec                                               | 2.71 sec: 1.02x faster                                                |
| spectral_norm              | 115 ms                                                 | 114 ms: 1.01x faster                                                  |
| xml_etree_generate         | 88.7 ms                                                | 88.0 ms: 1.01x faster                                                 |
| sympy_integrate            | 21.2 ms                                                | 21.0 ms: 1.01x faster                                                 |
| async_generators           | 459 ms                                                 | 456 ms: 1.01x faster                                                  |
| unpickle_list              | 5.04 us                                                | 5.02 us: 1.01x faster                                                 |
| bench_thread_pool          | 845 us                                                 | 841 us: 1.00x faster                                                  |
| sqlglot_parse              | 1.35 ms                                                | 1.36 ms: 1.00x slower                                                 |
| sqlglot_transpile          | 1.68 ms                                                | 1.69 ms: 1.01x slower                                                 |
| json_dumps                 | 10.6 ms                                                | 10.6 ms: 1.01x slower                                                 |
| sqlite_synth               | 2.83 us                                                | 2.85 us: 1.01x slower                                                 |
| sympy_expand               | 476 ms                                                 | 479 ms: 1.01x slower                                                  |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                                |
| create_gc_cycles           | 1.45 ms                                                | 1.47 ms: 1.01x slower                                                 |
| mypy2                      | 351 ms                                                 | 356 ms: 1.01x slower                                                  |
| regex_dna                  | 209 ms                                                 | 212 ms: 1.02x slower                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 55.7 ms: 1.02x slower                                                 |
| chaos                      | 67.5 ms                                                | 69.2 ms: 1.02x slower                                                 |
| pickle_dict                | 33.5 us                                                | 34.4 us: 1.03x slower                                                 |
| 2to3                       | 274 ms                                                 | 282 ms: 1.03x slower                                                  |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.03x slower                                                |
| pickle                     | 11.2 us                                                | 11.6 us: 1.03x slower                                                 |
| unpickle_pure_python       | 230 us                                                 | 237 us: 1.03x slower                                                  |
| pathlib                    | 18.9 ms                                                | 19.5 ms: 1.03x slower                                                 |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 749 ms: 1.03x slower                                                  |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                |
| pprint_safe_repr           | 765 ms                                                 | 794 ms: 1.04x slower                                                  |
| scimark_fft                | 381 ms                                                 | 395 ms: 1.04x slower                                                  |
| fannkuch                   | 410 ms                                                 | 427 ms: 1.04x slower                                                  |
| meteor_contest             | 110 ms                                                 | 114 ms: 1.04x slower                                                  |
| async_tree_none_tg         | 447 ms                                                 | 467 ms: 1.04x slower                                                  |
| deepcopy_memo              | 39.7 us                                                | 41.6 us: 1.05x slower                                                 |
| pidigits                   | 187 ms                                                 | 196 ms: 1.05x slower                                                  |
| xml_etree_iterparse        | 106 ms                                                 | 111 ms: 1.05x slower                                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.25 sec: 1.05x slower                                                |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.60 ms: 1.05x slower                                                 |
| mdp                        | 2.57 sec                                               | 2.71 sec: 1.06x slower                                                |
| async_tree_memoization_tg  | 574 ms                                                 | 607 ms: 1.06x slower                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.65 sec: 1.06x slower                                                |
| regex_compile              | 148 ms                                                 | 158 ms: 1.07x slower                                                  |
| tomli_loads                | 2.30 sec                                               | 2.47 sec: 1.07x slower                                                |
| pyflate                    | 471 ms                                                 | 506 ms: 1.08x slower                                                  |
| comprehensions             | 20.9 us                                                | 22.5 us: 1.08x slower                                                 |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                 |
| pickle_list                | 4.67 us                                                | 5.07 us: 1.09x slower                                                 |
| regex_v8                   | 22.7 ms                                                | 24.9 ms: 1.10x slower                                                 |
| unpack_sequence            | 54.2 ns                                                | 59.9 ns: 1.11x slower                                                 |
| richards_super             | 51.9 ms                                                | 57.7 ms: 1.11x slower                                                 |
| nqueens                    | 86.2 ms                                                | 96.5 ms: 1.12x slower                                                 |
| richards                   | 46.0 ms                                                | 51.7 ms: 1.12x slower                                                 |
| go                         | 140 ms                                                 | 160 ms: 1.14x slower                                                  |
| float                      | 83.3 ms                                                | 97.0 ms: 1.16x slower                                                 |
| telco                      | 7.18 ms                                                | 8.37 ms: 1.17x slower                                                 |
| mako                       | 11.5 ms                                                | 13.7 ms: 1.19x slower                                                 |
| nbody                      | 92.2 ms                                                | 113 ms: 1.23x slower                                                  |
| coverage                   | 75.1 ms                                                | 94.8 ms: 1.26x slower                                                 |
| python_startup_no_site     | 6.92 ms                                                | 9.00 ms: 1.30x slower                                                 |
| deltablue                  | 3.71 ms                                                | 4.85 ms: 1.31x slower                                                 |
| hexiom                     | 6.54 ms                                                | 8.94 ms: 1.37x slower                                                 |
| Geometric mean             | (ref)                                                  | 1.03x slower                                                          |

Benchmark hidden because not significant (9): scimark_lu, scimark_monte_carlo, xml_etree_parse, asyncio_websockets, logging_silent, bench_mp_pool, scimark_sor, async_tree_cpu_io_mixed, async_tree_memoization
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.93% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
