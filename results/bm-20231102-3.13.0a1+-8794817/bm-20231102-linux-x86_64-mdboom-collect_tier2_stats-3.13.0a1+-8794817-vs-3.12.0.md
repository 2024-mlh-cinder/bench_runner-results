
# Results vs. 3.12.0

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 8794817
- commit date: 2023-11-02
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.78%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 279 ms: 1.02x slower                                                  |
| chameleon      | 7.41 ms                                                | 7.09 ms: 1.04x faster                                                 |
| docutils       | 2.75 sec                                               | 2.70 sec: 1.02x faster                                                |
| tornado_http   | 101 ms                                                 | 98.4 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 452 ms: 1.05x faster                                                  |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                |
| async_tree_none_tg         | 447 ms                                                 | 466 ms: 1.04x slower                                                  |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                                |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 757 ms: 1.04x slower                                                  |
| async_tree_memoization_tg  | 574 ms                                                 | 606 ms: 1.06x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                          |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 196 ms: 1.04x slower                                                  |
| float          | 83.3 ms                                                | 94.7 ms: 1.14x slower                                                 |
| nbody          | 92.2 ms                                                | 111 ms: 1.20x slower                                                  |
| Geometric mean | (ref)                                                  | 1.13x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.68 ms: 1.03x slower                                                 |
| regex_dna      | 209 ms                                                 | 218 ms: 1.05x slower                                                  |
| regex_compile  | 148 ms                                                 | 156 ms: 1.06x slower                                                  |
| regex_v8       | 22.7 ms                                                | 25.9 ms: 1.14x slower                                                 |
| Geometric mean | (ref)                                                  | 1.07x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 301 us: 1.08x faster                                                  |
| xml_etree_process    | 61.2 ms                                                | 59.2 ms: 1.04x faster                                                 |
| json_loads           | 28.4 us                                                | 27.5 us: 1.03x faster                                                 |
| unpickle             | 15.8 us                                                | 15.4 us: 1.02x faster                                                 |
| xml_etree_generate   | 88.7 ms                                                | 86.9 ms: 1.02x faster                                                 |
| json_dumps           | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                 |
| pickle_dict          | 33.5 us                                                | 33.4 us: 1.00x faster                                                 |
| unpickle_pure_python | 230 us                                                 | 235 us: 1.03x slower                                                  |
| tomli_loads          | 2.30 sec                                               | 2.38 sec: 1.03x slower                                                |
| xml_etree_iterparse  | 106 ms                                                 | 110 ms: 1.04x slower                                                  |
| pickle_list          | 4.67 us                                                | 4.91 us: 1.05x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                          |

Benchmark hidden because not significant (3): unpickle_list, pickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                 |
| python_startup_no_site | 6.92 ms                                                | 8.99 ms: 1.30x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 13.6 ms: 1.18x slower                                                 |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 123 us: 1.24x faster                                                  |
| gc_traversal               | 4.28 ms                                                | 3.51 ms: 1.22x faster                                                 |
| logging_format             | 7.10 us                                                | 6.44 us: 1.10x faster                                                 |
| logging_simple             | 6.38 us                                                | 5.84 us: 1.09x faster                                                 |
| crypto_pyaes               | 83.6 ms                                                | 76.7 ms: 1.09x faster                                                 |
| sympy_sum                  | 167 ms                                                 | 154 ms: 1.08x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 301 us: 1.08x faster                                                  |
| generators                 | 32.5 ms                                                | 30.3 ms: 1.07x faster                                                 |
| unpack_sequence            | 54.2 ns                                                | 50.6 ns: 1.07x faster                                                 |
| raytrace                   | 308 ms                                                 | 290 ms: 1.06x faster                                                  |
| coroutines                 | 23.5 ms                                                | 22.2 ms: 1.06x faster                                                 |
| async_tree_none            | 475 ms                                                 | 452 ms: 1.05x faster                                                  |
| sympy_str                  | 296 ms                                                 | 282 ms: 1.05x faster                                                  |
| chameleon                  | 7.41 ms                                                | 7.09 ms: 1.04x faster                                                 |
| deepcopy_reduce            | 3.23 us                                                | 3.10 us: 1.04x faster                                                 |
| xml_etree_process          | 61.2 ms                                                | 59.2 ms: 1.04x faster                                                 |
| json_loads                 | 28.4 us                                                | 27.5 us: 1.03x faster                                                 |
| asyncio_tcp                | 506 ms                                                 | 490 ms: 1.03x faster                                                  |
| dulwich_log                | 68.7 ms                                                | 66.9 ms: 1.03x faster                                                 |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.03x faster                                                  |
| tornado_http               | 101 ms                                                 | 98.4 ms: 1.02x faster                                                 |
| unpickle                   | 15.8 us                                                | 15.4 us: 1.02x faster                                                 |
| xml_etree_generate         | 88.7 ms                                                | 86.9 ms: 1.02x faster                                                 |
| docutils                   | 2.75 sec                                               | 2.70 sec: 1.02x faster                                                |
| deepcopy                   | 363 us                                                 | 356 us: 1.02x faster                                                  |
| json                       | 5.22 ms                                                | 5.13 ms: 1.02x faster                                                 |
| scimark_monte_carlo        | 74.6 ms                                                | 73.4 ms: 1.02x faster                                                 |
| logging_silent             | 108 ns                                                 | 106 ns: 1.01x faster                                                  |
| async_generators           | 459 ms                                                 | 453 ms: 1.01x faster                                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.65 ms: 1.01x faster                                                 |
| sqlglot_parse              | 1.35 ms                                                | 1.33 ms: 1.01x faster                                                 |
| sympy_integrate            | 21.2 ms                                                | 20.9 ms: 1.01x faster                                                 |
| json_dumps                 | 10.6 ms                                                | 10.5 ms: 1.01x faster                                                 |
| bench_thread_pool          | 845 us                                                 | 837 us: 1.01x faster                                                  |
| pickle_dict                | 33.5 us                                                | 33.4 us: 1.00x faster                                                 |
| create_gc_cycles           | 1.45 ms                                                | 1.45 ms: 1.00x slower                                                 |
| sqlglot_optimize           | 54.8 ms                                                | 55.1 ms: 1.01x slower                                                 |
| mypy2                      | 351 ms                                                 | 353 ms: 1.01x slower                                                  |
| scimark_sor                | 129 ms                                                 | 130 ms: 1.01x slower                                                  |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.80 sec: 1.01x slower                                                |
| 2to3                       | 274 ms                                                 | 279 ms: 1.02x slower                                                  |
| chaos                      | 67.5 ms                                                | 68.6 ms: 1.02x slower                                                 |
| unpickle_pure_python       | 230 us                                                 | 235 us: 1.03x slower                                                  |
| mdp                        | 2.57 sec                                               | 2.63 sec: 1.03x slower                                                |
| deepcopy_memo              | 39.7 us                                                | 40.9 us: 1.03x slower                                                 |
| fannkuch                   | 410 ms                                                 | 422 ms: 1.03x slower                                                  |
| regex_effbot               | 3.57 ms                                                | 3.68 ms: 1.03x slower                                                 |
| tomli_loads                | 2.30 sec                                               | 2.38 sec: 1.03x slower                                                |
| async_tree_io              | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                |
| async_tree_none_tg         | 447 ms                                                 | 466 ms: 1.04x slower                                                  |
| pathlib                    | 18.9 ms                                                | 19.7 ms: 1.04x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                                |
| xml_etree_iterparse        | 106 ms                                                 | 110 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 757 ms: 1.04x slower                                                  |
| pidigits                   | 187 ms                                                 | 196 ms: 1.04x slower                                                  |
| regex_dna                  | 209 ms                                                 | 218 ms: 1.05x slower                                                  |
| comprehensions             | 20.9 us                                                | 21.9 us: 1.05x slower                                                 |
| pickle_list                | 4.67 us                                                | 4.91 us: 1.05x slower                                                 |
| async_tree_memoization_tg  | 574 ms                                                 | 606 ms: 1.06x slower                                                  |
| regex_compile              | 148 ms                                                 | 156 ms: 1.06x slower                                                  |
| scimark_fft                | 381 ms                                                 | 402 ms: 1.06x slower                                                  |
| pprint_safe_repr           | 765 ms                                                 | 808 ms: 1.06x slower                                                  |
| meteor_contest             | 110 ms                                                 | 116 ms: 1.06x slower                                                  |
| pycparser                  | 1.17 sec                                               | 1.25 sec: 1.06x slower                                                |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 5.69 ms: 1.07x slower                                                 |
| pprint_pformat             | 1.55 sec                                               | 1.66 sec: 1.07x slower                                                |
| pyflate                    | 471 ms                                                 | 507 ms: 1.08x slower                                                  |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                 |
| richards                   | 46.0 ms                                                | 50.2 ms: 1.09x slower                                                 |
| richards_super             | 51.9 ms                                                | 56.7 ms: 1.09x slower                                                 |
| nqueens                    | 86.2 ms                                                | 96.2 ms: 1.12x slower                                                 |
| go                         | 140 ms                                                 | 159 ms: 1.13x slower                                                  |
| float                      | 83.3 ms                                                | 94.7 ms: 1.14x slower                                                 |
| regex_v8                   | 22.7 ms                                                | 25.9 ms: 1.14x slower                                                 |
| mako                       | 11.5 ms                                                | 13.6 ms: 1.18x slower                                                 |
| telco                      | 7.18 ms                                                | 8.57 ms: 1.19x slower                                                 |
| nbody                      | 92.2 ms                                                | 111 ms: 1.20x slower                                                  |
| deltablue                  | 3.71 ms                                                | 4.62 ms: 1.25x slower                                                 |
| coverage                   | 75.1 ms                                                | 95.3 ms: 1.27x slower                                                 |
| python_startup_no_site     | 6.92 ms                                                | 8.99 ms: 1.30x slower                                                 |
| hexiom                     | 6.54 ms                                                | 8.58 ms: 1.31x slower                                                 |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                          |

Benchmark hidden because not significant (11): async_tree_memoization, unpickle_list, pickle, asyncio_websockets, bench_mp_pool, xml_etree_parse, sympy_expand, scimark_lu, spectral_norm, sqlite_synth, async_tree_cpu_io_mixed
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.78% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
