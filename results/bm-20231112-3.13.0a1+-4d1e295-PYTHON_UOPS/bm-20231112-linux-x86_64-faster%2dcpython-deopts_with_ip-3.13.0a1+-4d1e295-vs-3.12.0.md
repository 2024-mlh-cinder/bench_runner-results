
# Results vs. 3.12.0

- fork: faster-cpython
- ref: deopts_with_ip
- machine: linux-x86_64
- commit hash: 4d1e295
- commit date: 2023-11-12
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 286 ms: 1.04x slower                                                       |
| docutils       | 2.75 sec                                               | 2.73 sec: 1.01x faster                                                     |
| tornado_http   | 101 ms                                                 | 99.3 ms: 1.01x faster                                                      |
| Geometric mean | (ref)                                                  | 1.01x slower                                                               |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_none            | 475 ms                                                 | 462 ms: 1.03x faster                                                       |
| async_tree_memoization     | 580 ms                                                 | 589 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 739 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 767 ms: 1.06x slower                                                       |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.06x slower                                                     |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                     |
| async_tree_memoization_tg  | 574 ms                                                 | 609 ms: 1.06x slower                                                       |
| async_tree_none_tg         | 447 ms                                                 | 476 ms: 1.06x slower                                                       |
| Geometric mean             | (ref)                                                  | 1.04x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                       |
| float          | 83.3 ms                                                | 98.5 ms: 1.18x slower                                                      |
| nbody          | 92.2 ms                                                | 114 ms: 1.23x slower                                                       |
| Geometric mean | (ref)                                                  | 1.14x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.73 ms: 1.04x slower                                                      |
| regex_dna      | 209 ms                                                 | 221 ms: 1.06x slower                                                       |
| regex_compile  | 148 ms                                                 | 160 ms: 1.08x slower                                                       |
| regex_v8       | 22.7 ms                                                | 26.1 ms: 1.15x slower                                                      |
| Geometric mean | (ref)                                                  | 1.08x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 15.0 us: 1.05x faster                                                      |
| pickle_pure_python   | 326 us                                                 | 314 us: 1.04x faster                                                       |
| xml_etree_process    | 61.2 ms                                                | 60.0 ms: 1.02x faster                                                      |
| json_dumps           | 10.6 ms                                                | 10.4 ms: 1.02x faster                                                      |
| xml_etree_generate   | 88.7 ms                                                | 88.2 ms: 1.01x faster                                                      |
| unpickle_list        | 5.04 us                                                | 5.16 us: 1.02x slower                                                      |
| pickle_dict          | 33.5 us                                                | 34.3 us: 1.03x slower                                                      |
| pickle               | 11.2 us                                                | 11.5 us: 1.03x slower                                                      |
| xml_etree_iterparse  | 106 ms                                                 | 112 ms: 1.06x slower                                                       |
| unpickle_pure_python | 230 us                                                 | 246 us: 1.07x slower                                                       |
| pickle_list          | 4.67 us                                                | 5.22 us: 1.12x slower                                                      |
| tomli_loads          | 2.30 sec                                               | 2.76 sec: 1.20x slower                                                     |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                               |

Benchmark hidden because not significant (2): xml_etree_parse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                      |
| python_startup_no_site | 6.92 ms                                                | 9.04 ms: 1.31x slower                                                      |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 11.5 ms                                                | 14.8 ms: 1.28x slower                                                      |

All benchmarks:
===============

| Benchmark                  | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols   | 153 us                                                 | 128 us: 1.20x faster                                                       |
| unpack_sequence            | 54.2 ns                                                | 45.3 ns: 1.20x faster                                                      |
| gc_traversal               | 4.28 ms                                                | 3.83 ms: 1.12x faster                                                      |
| generators                 | 32.5 ms                                                | 29.8 ms: 1.09x faster                                                      |
| sympy_sum                  | 167 ms                                                 | 155 ms: 1.08x faster                                                       |
| coroutines                 | 23.5 ms                                                | 22.2 ms: 1.06x faster                                                      |
| unpickle                   | 15.8 us                                                | 15.0 us: 1.05x faster                                                      |
| spectral_norm              | 115 ms                                                 | 109 ms: 1.05x faster                                                       |
| sympy_str                  | 296 ms                                                 | 284 ms: 1.04x faster                                                       |
| pickle_pure_python         | 326 us                                                 | 314 us: 1.04x faster                                                       |
| sqlglot_normalize          | 112 ms                                                 | 107 ms: 1.04x faster                                                       |
| logging_simple             | 6.38 us                                                | 6.18 us: 1.03x faster                                                      |
| async_tree_none            | 475 ms                                                 | 462 ms: 1.03x faster                                                       |
| logging_format             | 7.10 us                                                | 6.92 us: 1.03x faster                                                      |
| asyncio_tcp                | 506 ms                                                 | 495 ms: 1.02x faster                                                       |
| xml_etree_process          | 61.2 ms                                                | 60.0 ms: 1.02x faster                                                      |
| deepcopy_reduce            | 3.23 us                                                | 3.16 us: 1.02x faster                                                      |
| deepcopy                   | 363 us                                                 | 356 us: 1.02x faster                                                       |
| json_dumps                 | 10.6 ms                                                | 10.4 ms: 1.02x faster                                                      |
| raytrace                   | 308 ms                                                 | 304 ms: 1.01x faster                                                       |
| tornado_http               | 101 ms                                                 | 99.3 ms: 1.01x faster                                                      |
| docutils                   | 2.75 sec                                               | 2.73 sec: 1.01x faster                                                     |
| crypto_pyaes               | 83.6 ms                                                | 83.0 ms: 1.01x faster                                                      |
| xml_etree_generate         | 88.7 ms                                                | 88.2 ms: 1.01x faster                                                      |
| sqlglot_optimize           | 54.8 ms                                                | 54.6 ms: 1.00x faster                                                      |
| sympy_expand               | 476 ms                                                 | 477 ms: 1.00x slower                                                       |
| dulwich_log                | 68.7 ms                                                | 69.0 ms: 1.00x slower                                                      |
| pidigits                   | 187 ms                                                 | 188 ms: 1.01x slower                                                       |
| sympy_integrate            | 21.2 ms                                                | 21.3 ms: 1.01x slower                                                      |
| scimark_lu                 | 120 ms                                                 | 121 ms: 1.01x slower                                                       |
| sqlglot_parse              | 1.35 ms                                                | 1.36 ms: 1.01x slower                                                      |
| mypy2                      | 351 ms                                                 | 354 ms: 1.01x slower                                                       |
| asyncio_tcp_ssl            | 1.78 sec                                               | 1.81 sec: 1.01x slower                                                     |
| bench_thread_pool          | 845 us                                                 | 858 us: 1.02x slower                                                       |
| async_tree_memoization     | 580 ms                                                 | 589 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed    | 724 ms                                                 | 739 ms: 1.02x slower                                                       |
| unpickle_list              | 5.04 us                                                | 5.16 us: 1.02x slower                                                      |
| pickle_dict                | 33.5 us                                                | 34.3 us: 1.03x slower                                                      |
| pickle                     | 11.2 us                                                | 11.5 us: 1.03x slower                                                      |
| create_gc_cycles           | 1.45 ms                                                | 1.49 ms: 1.03x slower                                                      |
| sqlite_synth               | 2.83 us                                                | 2.92 us: 1.03x slower                                                      |
| logging_silent             | 108 ns                                                 | 111 ns: 1.03x slower                                                       |
| 2to3                       | 274 ms                                                 | 286 ms: 1.04x slower                                                       |
| regex_effbot               | 3.57 ms                                                | 3.73 ms: 1.04x slower                                                      |
| xml_etree_iterparse        | 106 ms                                                 | 112 ms: 1.06x slower                                                       |
| async_tree_cpu_io_mixed_tg | 725 ms                                                 | 767 ms: 1.06x slower                                                       |
| async_tree_io              | 1.16 sec                                               | 1.23 sec: 1.06x slower                                                     |
| regex_dna                  | 209 ms                                                 | 221 ms: 1.06x slower                                                       |
| async_tree_io_tg           | 1.19 sec                                               | 1.26 sec: 1.06x slower                                                     |
| async_tree_memoization_tg  | 574 ms                                                 | 609 ms: 1.06x slower                                                       |
| meteor_contest             | 110 ms                                                 | 117 ms: 1.06x slower                                                       |
| async_tree_none_tg         | 447 ms                                                 | 476 ms: 1.06x slower                                                       |
| pprint_safe_repr           | 765 ms                                                 | 815 ms: 1.07x slower                                                       |
| mdp                        | 2.57 sec                                               | 2.74 sec: 1.07x slower                                                     |
| deepcopy_memo              | 39.7 us                                                | 42.5 us: 1.07x slower                                                      |
| unpickle_pure_python       | 230 us                                                 | 246 us: 1.07x slower                                                       |
| pycparser                  | 1.17 sec                                               | 1.25 sec: 1.07x slower                                                     |
| regex_compile              | 148 ms                                                 | 160 ms: 1.08x slower                                                       |
| pprint_pformat             | 1.55 sec                                               | 1.68 sec: 1.09x slower                                                     |
| python_startup             | 9.53 ms                                                | 10.4 ms: 1.09x slower                                                      |
| richards                   | 46.0 ms                                                | 50.0 ms: 1.09x slower                                                      |
| chaos                      | 67.5 ms                                                | 73.5 ms: 1.09x slower                                                      |
| scimark_monte_carlo        | 74.6 ms                                                | 81.5 ms: 1.09x slower                                                      |
| richards_super             | 51.9 ms                                                | 56.9 ms: 1.10x slower                                                      |
| pickle_list                | 4.67 us                                                | 5.22 us: 1.12x slower                                                      |
| scimark_fft                | 381 ms                                                 | 427 ms: 1.12x slower                                                       |
| comprehensions             | 20.9 us                                                | 23.8 us: 1.14x slower                                                      |
| regex_v8                   | 22.7 ms                                                | 26.1 ms: 1.15x slower                                                      |
| pyflate                    | 471 ms                                                 | 548 ms: 1.16x slower                                                       |
| fannkuch                   | 410 ms                                                 | 479 ms: 1.17x slower                                                       |
| go                         | 140 ms                                                 | 164 ms: 1.17x slower                                                       |
| nqueens                    | 86.2 ms                                                | 101 ms: 1.18x slower                                                       |
| float                      | 83.3 ms                                                | 98.5 ms: 1.18x slower                                                      |
| tomli_loads                | 2.30 sec                                               | 2.76 sec: 1.20x slower                                                     |
| nbody                      | 92.2 ms                                                | 114 ms: 1.23x slower                                                       |
| scimark_sparse_mat_mult    | 5.33 ms                                                | 6.58 ms: 1.23x slower                                                      |
| telco                      | 7.18 ms                                                | 8.95 ms: 1.25x slower                                                      |
| coverage                   | 75.1 ms                                                | 95.4 ms: 1.27x slower                                                      |
| mako                       | 11.5 ms                                                | 14.8 ms: 1.28x slower                                                      |
| python_startup_no_site     | 6.92 ms                                                | 9.04 ms: 1.31x slower                                                      |
| deltablue                  | 3.71 ms                                                | 4.90 ms: 1.32x slower                                                      |
| hexiom                     | 6.54 ms                                                | 9.40 ms: 1.44x slower                                                      |
| Geometric mean             | (ref)                                                  | 1.05x slower                                                               |

Benchmark hidden because not significant (10): json, xml_etree_parse, async_generators, asyncio_websockets, bench_mp_pool, json_loads, chameleon, pathlib, scimark_sor, sqlglot_transpile
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
