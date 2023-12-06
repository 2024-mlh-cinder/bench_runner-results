
# Results vs. 3.12.0

- fork: faster-cpython
- ref: faster_tier_2_interp
- machine: linux-x86_64
- commit hash: 4830ad2
- commit date: 2023-11-09
- overall geometric mean: 1.04x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 287 ms: 1.05x slower                                                             |
| chameleon      | 7.41 ms                                                | 7.53 ms: 1.02x slower                                                            |
| docutils       | 2.75 sec                                               | 2.71 sec: 1.02x faster                                                           |
| tornado_http   | 101 ms                                                 | 99.3 ms: 1.01x faster                                                            |
| Geometric mean | (ref)                                                  | 1.01x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 454 ms: 1.05x faster                                                             |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 733 ms: 1.01x slower                                                             |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                           |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                                           |
| async_tree_none_tg         | 447 ms                                                 | 467 ms: 1.04x slower                                                             |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 759 ms: 1.05x slower                                                             |
| async_tree_memoization_tg  | 574 ms                                                 | 609 ms: 1.06x slower                                                             |
| Geometric mean             | (ref)                                                  | 1.02x slower                                                                     |

Benchmark hidden because not significant (1): async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                             |
| float          | 83.3 ms                                                | 101 ms: 1.21x slower                                                             |
| nbody          | 92.2 ms                                                | 127 ms: 1.38x slower                                                             |
| Geometric mean | (ref)                                                  | 1.19x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.59 ms: 1.01x slower                                                            |
| regex_dna      | 209 ms                                                 | 219 ms: 1.05x slower                                                             |
| regex_v8       | 22.7 ms                                                | 24.2 ms: 1.07x slower                                                            |
| regex_compile  | 148 ms                                                 | 158 ms: 1.07x slower                                                             |
| Geometric mean | (ref)                                                  | 1.05x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 14.8 us: 1.06x faster                                                            |
| pickle_pure_python   | 326 us                                                 | 310 us: 1.05x faster                                                             |
| json_loads           | 28.4 us                                                | 27.6 us: 1.03x faster                                                            |
| xml_etree_process    | 61.2 ms                                                | 60.2 ms: 1.02x faster                                                            |
| xml_etree_parse      | 159 ms                                                 | 157 ms: 1.01x faster                                                             |
| xml_etree_generate   | 88.7 ms                                                | 87.9 ms: 1.01x faster                                                            |
| json_dumps           | 10.6 ms                                                | 10.8 ms: 1.02x slower                                                            |
| pickle_dict          | 33.5 us                                                | 34.5 us: 1.03x slower                                                            |
| xml_etree_iterparse  | 106 ms                                                 | 110 ms: 1.05x slower                                                             |
| pickle               | 11.2 us                                                | 11.7 us: 1.05x slower                                                            |
| unpickle_pure_python | 230 us                                                 | 242 us: 1.05x slower                                                             |
| unpickle_list        | 5.04 us                                                | 5.34 us: 1.06x slower                                                            |
| pickle_list          | 4.67 us                                                | 5.03 us: 1.08x slower                                                            |
| tomli_loads          | 2.30 sec                                               | 2.66 sec: 1.16x slower                                                           |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| python_startup_no_site | 6.92 ms                                                | 9.03 ms: 1.31x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 14.2 ms: 1.23x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 126 us: 1.22x faster                                                             |
| unpack_sequence            | 54.2 ns                                                | 45.0 ns: 1.20x faster                                                            |
| gc_traversal               | 4.28 ms                                                | 3.77 ms: 1.13x faster                                                            |
| sympy_sum                  | 167 ms                                                 | 155 ms: 1.08x faster                                                             |
| unpickle                   | 15.8 us                                                | 14.8 us: 1.06x faster                                                            |
| coroutines                 | 23.5 ms                                                | 22.1 ms: 1.06x faster                                                            |
| pickle_pure_python         | 326 us                                                 | 310 us: 1.05x faster                                                             |
| generators                 | 32.5 ms                                                | 30.9 ms: 1.05x faster                                                            |
| async_tree_none            | 475 ms                                                 | 454 ms: 1.05x faster                                                             |
| sympy_str                  | 296 ms                                                 | 283 ms: 1.05x faster                                                             |
| json_loads                 | 28.4 us                                                | 27.6 us: 1.03x faster                                                            |
| logging_format             | 7.10 us                                                | 6.94 us: 1.02x faster                                                            |
| asyncio_tcp                | 506 ms                                                 | 494 ms: 1.02x faster                                                             |
| sqlglot_normalize          | 112 ms                                                 | 109 ms: 1.02x faster                                                             |
| xml_etree_process          | 61.2 ms                                                | 60.2 ms: 1.02x faster                                                            |
| docutils                   | 2.75 sec                                               | 2.71 sec: 1.02x faster                                                           |
| logging_simple             | 6.38 us                                                | 6.28 us: 1.02x faster                                                            |
| xml_etree_parse            | 159 ms                                                 | 157 ms: 1.01x faster                                                             |
| tornado_http               | 101 ms                                                 | 99.3 ms: 1.01x faster                                                            |
| raytrace                   | 308 ms                                                 | 304 ms: 1.01x faster                                                             |
| scimark_sor                | 129 ms                                                 | 128 ms: 1.01x faster                                                             |
| deepcopy_reduce            | 3.23 us                                                | 3.20 us: 1.01x faster                                                            |
| xml_etree_generate         | 88.7 ms                                                | 87.9 ms: 1.01x faster                                                            |
| scimark_lu                 | 120 ms                                                 | 120 ms: 1.01x faster                                                             |
| async_generators           | 459 ms                                                 | 456 ms: 1.01x faster                                                             |
| deepcopy                   | 363 us                                                 | 360 us: 1.01x faster                                                             |
| pidigits                   | 187 ms                                                 | 188 ms: 1.01x slower                                                             |
| regex_effbot               | 3.57 ms                                                | 3.59 ms: 1.01x slower                                                            |
| sqlglot_optimize           | 54.8 ms                                                | 55.2 ms: 1.01x slower                                                            |
| create_gc_cycles           | 1.45 ms                                                | 1.46 ms: 1.01x slower                                                            |
| sympy_expand               | 476 ms                                                 | 480 ms: 1.01x slower                                                             |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 733 ms: 1.01x slower                                                             |
| mypy2                      | 351 ms                                                 | 356 ms: 1.01x slower                                                             |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.01x slower                                                           |
| bench_thread_pool          | 845 us                                                 | 859 us: 1.02x slower                                                             |
| chameleon                  | 7.41 ms                                                | 7.53 ms: 1.02x slower                                                            |
| json_dumps                 | 10.6 ms                                                | 10.8 ms: 1.02x slower                                                            |
| pickle_dict                | 33.5 us                                                | 34.5 us: 1.03x slower                                                            |
| async_tree_io              | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                           |
| sqlite_synth               | 2.83 us                                                | 2.93 us: 1.03x slower                                                            |
| pathlib                    | 18.9 ms                                                | 19.7 ms: 1.04x slower                                                            |
| async_tree_io_tg           | 1.19 sec                                               | 1.24 sec: 1.04x slower                                                           |
| crypto_pyaes               | 83.6 ms                                                | 87.1 ms: 1.04x slower                                                            |
| async_tree_none_tg         | 447 ms                                                 | 467 ms: 1.04x slower                                                             |
| xml_etree_iterparse        | 106 ms                                                 | 110 ms: 1.05x slower                                                             |
| pickle                     | 11.2 us                                                | 11.7 us: 1.05x slower                                                            |
| 2to3                       | 274 ms                                                 | 287 ms: 1.05x slower                                                             |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 759 ms: 1.05x slower                                                             |
| regex_dna                  | 209 ms                                                 | 219 ms: 1.05x slower                                                             |
| unpickle_pure_python       | 230 us                                                 | 242 us: 1.05x slower                                                             |
| unpickle_list              | 5.04 us                                                | 5.34 us: 1.06x slower                                                            |
| async_tree_memoization_tg  | 574 ms                                                 | 609 ms: 1.06x slower                                                             |
| pycparser                  | 1.17 sec                                               | 1.25 sec: 1.06x slower                                                           |
| deepcopy_memo              | 39.7 us                                                | 42.3 us: 1.07x slower                                                            |
| regex_v8                   | 22.7 ms                                                | 24.2 ms: 1.07x slower                                                            |
| meteor_contest             | 110 ms                                                 | 117 ms: 1.07x slower                                                             |
| regex_compile              | 148 ms                                                 | 158 ms: 1.07x slower                                                             |
| pickle_list                | 4.67 us                                                | 5.03 us: 1.08x slower                                                            |
| scimark_monte_carlo        | 74.6 ms                                                | 80.6 ms: 1.08x slower                                                            |
| pprint_safe_repr           | 765 ms                                                 | 826 ms: 1.08x slower                                                             |
| comprehensions             | 20.9 us                                                | 22.6 us: 1.08x slower                                                            |
| python_startup             | 9.53 ms                                                | 10.3 ms: 1.08x slower                                                            |
| chaos                      | 67.5 ms                                                | 74.0 ms: 1.10x slower                                                            |
| pprint_pformat             | 1.55 sec                                               | 1.70 sec: 1.10x slower                                                           |
| mdp                        | 2.57 sec                                               | 2.87 sec: 1.12x slower                                                           |
| richards                   | 46.0 ms                                                | 51.5 ms: 1.12x slower                                                            |
| richards_super             | 51.9 ms                                                | 58.2 ms: 1.12x slower                                                            |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.03 ms: 1.13x slower                                                            |
| tomli_loads                | 2.30 sec                                               | 2.66 sec: 1.16x slower                                                           |
| go                         | 140 ms                                                 | 163 ms: 1.16x slower                                                             |
| fannkuch                   | 410 ms                                                 | 477 ms: 1.16x slower                                                             |
| pyflate                    | 471 ms                                                 | 549 ms: 1.17x slower                                                             |
| scimark_fft                | 381 ms                                                 | 447 ms: 1.17x slower                                                             |
| nqueens                    | 86.2 ms                                                | 102 ms: 1.18x slower                                                             |
| float                      | 83.3 ms                                                | 101 ms: 1.21x slower                                                             |
| telco                      | 7.18 ms                                                | 8.73 ms: 1.22x slower                                                            |
| mako                       | 11.5 ms                                                | 14.2 ms: 1.23x slower                                                            |
| coverage                   | 75.1 ms                                                | 93.7 ms: 1.25x slower                                                            |
| deltablue                  | 3.71 ms                                                | 4.83 ms: 1.30x slower                                                            |
| python_startup_no_site     | 6.92 ms                                                | 9.03 ms: 1.31x slower                                                            |
| nbody                      | 92.2 ms                                                | 127 ms: 1.38x slower                                                             |
| hexiom                     | 6.54 ms                                                | 9.19 ms: 1.40x slower                                                            |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                                     |

Benchmark hidden because not significant (10): spectral_norm, sqlglot_parse, sqlglot_transpile, sympy_integrate, asyncio_websockets, json, bench_mp_pool, dulwich_log, async_tree_memoization, logging_silent
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
