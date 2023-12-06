
# Results vs. 3.12.0

- fork: python
- ref: eb3c94ea669561a0dfac
- machine: linux-x86_64
- commit hash: eb3c94e
- commit date: 2023-11-17
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 289 ms: 1.05x slower                                                   |
| chameleon      | 7.41 ms                                                | 7.34 ms: 1.01x faster                                                  |
| docutils       | 2.75 sec                                               | 2.70 sec: 1.02x faster                                                 |
| tornado_http   | 101 ms                                                 | 99.6 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 462 ms: 1.03x faster                                                   |
| async_tree_memoization     | 580 ms                                                 | 590 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 759 ms: 1.05x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.05x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                 |
| async_tree_none_tg         | 447 ms                                                 | 477 ms: 1.07x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 614 ms: 1.07x slower                                                   |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 196 ms: 1.05x slower                                                   |
| float          | 83.3 ms                                                | 103 ms: 1.24x slower                                                   |
| nbody          | 92.2 ms                                                | 131 ms: 1.42x slower                                                   |
| Geometric mean | (ref)                                                  | 1.22x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.59 ms: 1.01x slower                                                  |
| regex_dna      | 209 ms                                                 | 221 ms: 1.06x slower                                                   |
| regex_v8       | 22.7 ms                                                | 24.3 ms: 1.07x slower                                                  |
| regex_compile  | 148 ms                                                 | 160 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.8 us: 1.06x faster                                                  |
| pickle_pure_python   | 326 us                                                 | 307 us: 1.06x faster                                                   |
| xml_etree_process    | 61.2 ms                                                | 60.5 ms: 1.01x faster                                                  |
| xml_etree_parse      | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| pickle               | 11.2 us                                                | 11.3 us: 1.01x slower                                                  |
| unpickle_list        | 5.04 us                                                | 5.10 us: 1.01x slower                                                  |
| pickle_dict          | 33.5 us                                                | 34.5 us: 1.03x slower                                                  |
| xml_etree_iterparse  | 106 ms                                                 | 111 ms: 1.05x slower                                                   |
| unpickle_pure_python | 230 us                                                 | 242 us: 1.05x slower                                                   |
| pickle_list          | 4.67 us                                                | 5.05 us: 1.08x slower                                                  |
| tomli_loads          | 2.30 sec                                               | 2.77 sec: 1.20x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (3): json_loads, xml_etree_generate, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| python_startup_no_site | 6.92 ms                                                | 9.01 ms: 1.30x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 15.6 ms: 1.36x slower                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 128 us: 1.19x faster                                                   |
| sympy_sum                  | 167 ms                                                 | 154 ms: 1.08x faster                                                   |
| generators                 | 32.5 ms                                                | 30.4 ms: 1.07x faster                                                  |
| unpickle                   | 15.8 us                                                | 14.8 us: 1.06x faster                                                  |
| pickle_pure_python         | 326 us                                                 | 307 us: 1.06x faster                                                   |
| sympy_str                  | 296 ms                                                 | 283 ms: 1.05x faster                                                   |
| logging_simple             | 6.38 us                                                | 6.10 us: 1.05x faster                                                  |
| coroutines                 | 23.5 ms                                                | 22.4 ms: 1.05x faster                                                  |
| logging_format             | 7.10 us                                                | 6.82 us: 1.04x faster                                                  |
| sqlglot_normalize          | 112 ms                                                 | 108 ms: 1.04x faster                                                   |
| async_tree_none            | 475 ms                                                 | 462 ms: 1.03x faster                                                   |
| gc_traversal               | 4.28 ms                                                | 4.16 ms: 1.03x faster                                                  |
| asyncio_tcp                | 506 ms                                                 | 496 ms: 1.02x faster                                                   |
| deepcopy_reduce            | 3.23 us                                                | 3.17 us: 1.02x faster                                                  |
| scimark_sor                | 129 ms                                                 | 127 ms: 1.02x faster                                                   |
| docutils                   | 2.75 sec                                               | 2.70 sec: 1.02x faster                                                 |
| deepcopy                   | 363 us                                                 | 357 us: 1.02x faster                                                   |
| xml_etree_process          | 61.2 ms                                                | 60.5 ms: 1.01x faster                                                  |
| pathlib                    | 18.9 ms                                                | 18.7 ms: 1.01x faster                                                  |
| spectral_norm              | 115 ms                                                 | 114 ms: 1.01x faster                                                   |
| tornado_http               | 101 ms                                                 | 99.6 ms: 1.01x faster                                                  |
| xml_etree_parse            | 159 ms                                                 | 158 ms: 1.01x faster                                                   |
| chameleon                  | 7.41 ms                                                | 7.34 ms: 1.01x faster                                                  |
| json                       | 5.22 ms                                                | 5.19 ms: 1.01x faster                                                  |
| sqlglot_transpile          | 1.68 ms                                                | 1.67 ms: 1.01x faster                                                  |
| sqlglot_parse              | 1.35 ms                                                | 1.34 ms: 1.00x faster                                                  |
| dulwich_log                | 68.7 ms                                                | 68.5 ms: 1.00x faster                                                  |
| sqlglot_optimize           | 54.8 ms                                                | 54.7 ms: 1.00x faster                                                  |
| sympy_integrate            | 21.2 ms                                                | 21.3 ms: 1.00x slower                                                  |
| regex_effbot               | 3.57 ms                                                | 3.59 ms: 1.01x slower                                                  |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                                  |
| pickle                     | 11.2 us                                                | 11.3 us: 1.01x slower                                                  |
| bench_thread_pool          | 845 us                                                 | 852 us: 1.01x slower                                                   |
| mypy2                      | 351 ms                                                 | 354 ms: 1.01x slower                                                   |
| unpickle_list              | 5.04 us                                                | 5.10 us: 1.01x slower                                                  |
| raytrace                   | 308 ms                                                 | 311 ms: 1.01x slower                                                   |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.01x slower                                                 |
| sqlite_synth               | 2.83 us                                                | 2.88 us: 1.02x slower                                                  |
| async_tree_memoization     | 580 ms                                                 | 590 ms: 1.02x slower                                                   |
| logging_silent             | 108 ns                                                 | 110 ns: 1.02x slower                                                   |
| pycparser                  | 1.17 sec                                               | 1.20 sec: 1.02x slower                                                 |
| pickle_dict                | 33.5 us                                                | 34.5 us: 1.03x slower                                                  |
| crypto_pyaes               | 83.6 ms                                                | 86.9 ms: 1.04x slower                                                  |
| unpack_sequence            | 54.2 ns                                                | 56.4 ns: 1.04x slower                                                  |
| deepcopy_memo              | 39.7 us                                                | 41.6 us: 1.05x slower                                                  |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 759 ms: 1.05x slower                                                   |
| mdp                        | 2.57 sec                                               | 2.69 sec: 1.05x slower                                                 |
| pidigits                   | 187 ms                                                 | 196 ms: 1.05x slower                                                   |
| xml_etree_iterparse        | 106 ms                                                 | 111 ms: 1.05x slower                                                   |
| 2to3                       | 274 ms                                                 | 289 ms: 1.05x slower                                                   |
| unpickle_pure_python       | 230 us                                                 | 242 us: 1.05x slower                                                   |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.05x slower                                                 |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                 |
| regex_dna                  | 209 ms                                                 | 221 ms: 1.06x slower                                                   |
| meteor_contest             | 110 ms                                                 | 117 ms: 1.06x slower                                                   |
| async_tree_none_tg         | 447 ms                                                 | 477 ms: 1.07x slower                                                   |
| async_tree_memoization_tg  | 574 ms                                                 | 614 ms: 1.07x slower                                                   |
| regex_v8                   | 22.7 ms                                                | 24.3 ms: 1.07x slower                                                  |
| pprint_safe_repr           | 765 ms                                                 | 825 ms: 1.08x slower                                                   |
| regex_compile              | 148 ms                                                 | 160 ms: 1.08x slower                                                   |
| pickle_list                | 4.67 us                                                | 5.05 us: 1.08x slower                                                  |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                  |
| richards                   | 46.0 ms                                                | 50.5 ms: 1.10x slower                                                  |
| richards_super             | 51.9 ms                                                | 57.0 ms: 1.10x slower                                                  |
| pprint_pformat             | 1.55 sec                                               | 1.73 sec: 1.11x slower                                                 |
| comprehensions             | 20.9 us                                                | 23.7 us: 1.13x slower                                                  |
| scimark_monte_carlo        | 74.6 ms                                                | 84.7 ms: 1.14x slower                                                  |
| pyflate                    | 471 ms                                                 | 538 ms: 1.14x slower                                                   |
| fannkuch                   | 410 ms                                                 | 473 ms: 1.15x slower                                                   |
| chaos                      | 67.5 ms                                                | 78.6 ms: 1.17x slower                                                  |
| nqueens                    | 86.2 ms                                                | 102 ms: 1.18x slower                                                   |
| go                         | 140 ms                                                 | 166 ms: 1.18x slower                                                   |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.32 ms: 1.19x slower                                                  |
| tomli_loads                | 2.30 sec                                               | 2.77 sec: 1.20x slower                                                 |
| telco                      | 7.18 ms                                                | 8.83 ms: 1.23x slower                                                  |
| float                      | 83.3 ms                                                | 103 ms: 1.24x slower                                                   |
| coverage                   | 75.1 ms                                                | 93.7 ms: 1.25x slower                                                  |
| scimark_fft                | 381 ms                                                 | 476 ms: 1.25x slower                                                   |
| python_startup_no_site     | 6.92 ms                                                | 9.01 ms: 1.30x slower                                                  |
| mako                       | 11.5 ms                                                | 15.6 ms: 1.36x slower                                                  |
| deltablue                  | 3.71 ms                                                | 5.11 ms: 1.38x slower                                                  |
| nbody                      | 92.2 ms                                                | 131 ms: 1.42x slower                                                   |
| hexiom                     | 6.54 ms                                                | 9.38 ms: 1.43x slower                                                  |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                           |

Benchmark hidden because not significant (10): dask, async_generators, json_loads, scimark_lu, xml_etree_generate, asyncio_websockets, bench_mp_pool, sympy_expand, json_dumps, async_tree_cpu_io_mixed
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
