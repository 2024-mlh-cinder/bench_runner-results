
# Results vs. 3.11.0

- fork: gvanrossum
- ref: for_iter_uop
- machine: linux-x86_64
- commit hash: 14aea56
- commit date: 2023-11-17
- overall geometric mean: 1.09x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 301 ms: 1.13x slower                                               |
| chameleon      | 6.86 ms                                                | 7.84 ms: 1.14x slower                                              |
| docutils       | 2.69 sec                                               | 2.79 sec: 1.04x slower                                             |
| tornado_http   | 97.7 ms                                                | 104 ms: 1.06x slower                                               |
| Geometric mean | (ref)                                                  | 1.09x slower                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|---------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 468 ms: 1.14x faster                                               |
| async_tree_memoization    | 640 ms                                                 | 596 ms: 1.07x faster                                               |
| async_tree_io             | 1.31 sec                                               | 1.24 sec: 1.06x faster                                             |
| async_tree_io_tg          | 1.30 sec                                               | 1.27 sec: 1.03x faster                                             |
| async_tree_memoization_tg | 627 ms                                                 | 613 ms: 1.02x faster                                               |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 742 ms: 1.01x faster                                               |
| async_tree_none_tg        | 490 ms                                                 | 485 ms: 1.01x faster                                               |
| Geometric mean            | (ref)                                                  | 1.04x faster                                                       |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 199 ms: 1.04x slower                                               |
| float          | 78.9 ms                                                | 123 ms: 1.56x slower                                               |
| nbody          | 91.6 ms                                                | 159 ms: 1.74x slower                                               |
| Geometric mean | (ref)                                                  | 1.41x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.63 ms: 1.05x slower                                              |
| regex_dna      | 204 ms                                                 | 220 ms: 1.08x slower                                               |
| regex_v8       | 22.9 ms                                                | 26.1 ms: 1.14x slower                                              |
| regex_compile  | 141 ms                                                 | 176 ms: 1.25x slower                                               |
| Geometric mean | (ref)                                                  | 1.13x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                              |
| pickle_dict          | 34.8 us                                                | 33.2 us: 1.05x faster                                              |
| json_loads           | 29.4 us                                                | 28.2 us: 1.04x faster                                              |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                               |
| pickle_pure_python   | 319 us                                                 | 315 us: 1.01x faster                                               |
| pickle               | 11.1 us                                                | 11.3 us: 1.02x slower                                              |
| unpickle_list        | 5.22 us                                                | 5.40 us: 1.03x slower                                              |
| pickle_list          | 4.65 us                                                | 5.03 us: 1.08x slower                                              |
| unpickle_pure_python | 241 us                                                 | 262 us: 1.09x slower                                               |
| unpickle             | 13.9 us                                                | 15.1 us: 1.09x slower                                              |
| xml_etree_iterparse  | 109 ms                                                 | 122 ms: 1.12x slower                                               |
| xml_etree_process    | 56.5 ms                                                | 67.0 ms: 1.19x slower                                              |
| xml_etree_generate   | 80.4 ms                                                | 98.2 ms: 1.22x slower                                              |
| tomli_loads          | 2.31 sec                                               | 3.30 sec: 1.43x slower                                             |
| Geometric mean       | (ref)                                                  | 1.06x slower                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                              |
| python_startup_no_site | 6.09 ms                                                | 9.07 ms: 1.49x slower                                              |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 19.1 ms: 1.77x slower                                              |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|---------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 130 us: 4.02x faster                                               |
| generators                | 76.5 ms                                                | 29.7 ms: 2.57x faster                                              |
| asyncio_tcp               | 887 ms                                                 | 493 ms: 1.80x faster                                               |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.81 sec: 1.73x faster                                             |
| json_dumps                | 13.5 ms                                                | 10.5 ms: 1.28x faster                                              |
| mypy2                     | 427 ms                                                 | 360 ms: 1.19x faster                                               |
| coroutines                | 26.1 ms                                                | 22.0 ms: 1.19x faster                                              |
| async_tree_none           | 532 ms                                                 | 468 ms: 1.14x faster                                               |
| async_tree_memoization    | 640 ms                                                 | 596 ms: 1.07x faster                                               |
| async_tree_io             | 1.31 sec                                               | 1.24 sec: 1.06x faster                                             |
| pickle_dict               | 34.8 us                                                | 33.2 us: 1.05x faster                                              |
| json_loads                | 29.4 us                                                | 28.2 us: 1.04x faster                                              |
| async_tree_io_tg          | 1.30 sec                                               | 1.27 sec: 1.03x faster                                             |
| async_tree_memoization_tg | 627 ms                                                 | 613 ms: 1.02x faster                                               |
| xml_etree_parse           | 163 ms                                                 | 159 ms: 1.02x faster                                               |
| pickle_pure_python        | 319 us                                                 | 315 us: 1.01x faster                                               |
| json                      | 5.24 ms                                                | 5.18 ms: 1.01x faster                                              |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 742 ms: 1.01x faster                                               |
| richards_super            | 61.2 ms                                                | 60.6 ms: 1.01x faster                                              |
| async_tree_none_tg        | 490 ms                                                 | 485 ms: 1.01x faster                                               |
| asyncio_websockets        | 556 ms                                                 | 553 ms: 1.00x faster                                               |
| create_gc_cycles          | 1.48 ms                                                | 1.47 ms: 1.00x faster                                              |
| mdp                       | 2.79 sec                                               | 2.80 sec: 1.00x slower                                             |
| sqlglot_transpile         | 1.75 ms                                                | 1.77 ms: 1.01x slower                                              |
| logging_simple            | 6.24 us                                                | 6.31 us: 1.01x slower                                              |
| deepcopy_reduce           | 3.14 us                                                | 3.18 us: 1.01x slower                                              |
| pickle                    | 11.1 us                                                | 11.3 us: 1.02x slower                                              |
| dask                      | 365 ms                                                 | 373 ms: 1.02x slower                                               |
| deepcopy                  | 360 us                                                 | 372 us: 1.03x slower                                               |
| unpickle_list             | 5.22 us                                                | 5.40 us: 1.03x slower                                              |
| pathlib                   | 18.5 ms                                                | 19.1 ms: 1.04x slower                                              |
| docutils                  | 2.69 sec                                               | 2.79 sec: 1.04x slower                                             |
| logging_silent            | 108 ns                                                 | 113 ns: 1.04x slower                                               |
| logging_format            | 6.83 us                                                | 7.11 us: 1.04x slower                                              |
| pidigits                  | 190 ms                                                 | 199 ms: 1.04x slower                                               |
| gc_traversal              | 3.90 ms                                                | 4.09 ms: 1.05x slower                                              |
| regex_effbot              | 3.45 ms                                                | 3.63 ms: 1.05x slower                                              |
| bench_thread_pool         | 833 us                                                 | 877 us: 1.05x slower                                               |
| tornado_http              | 97.7 ms                                                | 104 ms: 1.06x slower                                               |
| pycparser                 | 1.20 sec                                               | 1.27 sec: 1.07x slower                                             |
| sympy_str                 | 299 ms                                                 | 319 ms: 1.07x slower                                               |
| sympy_integrate           | 21.4 ms                                                | 22.9 ms: 1.07x slower                                              |
| sympy_expand              | 490 ms                                                 | 528 ms: 1.08x slower                                               |
| regex_dna                 | 204 ms                                                 | 220 ms: 1.08x slower                                               |
| sqlglot_normalize         | 112 ms                                                 | 121 ms: 1.08x slower                                               |
| pickle_list               | 4.65 us                                                | 5.03 us: 1.08x slower                                              |
| unpickle_pure_python      | 241 us                                                 | 262 us: 1.09x slower                                               |
| unpickle                  | 13.9 us                                                | 15.1 us: 1.09x slower                                              |
| dulwich_log               | 64.9 ms                                                | 70.6 ms: 1.09x slower                                              |
| richards                  | 48.9 ms                                                | 53.2 ms: 1.09x slower                                              |
| scimark_lu                | 112 ms                                                 | 124 ms: 1.10x slower                                               |
| raytrace                  | 306 ms                                                 | 339 ms: 1.11x slower                                               |
| xml_etree_iterparse       | 109 ms                                                 | 122 ms: 1.12x slower                                               |
| sqlglot_optimize          | 55.2 ms                                                | 62.1 ms: 1.13x slower                                              |
| 2to3                      | 266 ms                                                 | 301 ms: 1.13x slower                                               |
| scimark_sor               | 121 ms                                                 | 138 ms: 1.14x slower                                               |
| regex_v8                  | 22.9 ms                                                | 26.1 ms: 1.14x slower                                              |
| chameleon                 | 6.86 ms                                                | 7.84 ms: 1.14x slower                                              |
| deepcopy_memo             | 38.9 us                                                | 44.7 us: 1.15x slower                                              |
| sqlite_synth              | 2.58 us                                                | 3.00 us: 1.16x slower                                              |
| unpack_sequence           | 43.3 ns                                                | 50.9 ns: 1.18x slower                                              |
| coverage                  | 81.2 ms                                                | 95.8 ms: 1.18x slower                                              |
| meteor_contest            | 109 ms                                                 | 129 ms: 1.19x slower                                               |
| xml_etree_process         | 56.5 ms                                                | 67.0 ms: 1.19x slower                                              |
| python_startup            | 8.69 ms                                                | 10.4 ms: 1.20x slower                                              |
| comprehensions            | 23.6 us                                                | 28.6 us: 1.21x slower                                              |
| pprint_safe_repr          | 743 ms                                                 | 905 ms: 1.22x slower                                               |
| xml_etree_generate        | 80.4 ms                                                | 98.2 ms: 1.22x slower                                              |
| pprint_pformat            | 1.53 sec                                               | 1.90 sec: 1.24x slower                                             |
| regex_compile             | 141 ms                                                 | 176 ms: 1.25x slower                                               |
| chaos                     | 71.4 ms                                                | 89.5 ms: 1.25x slower                                              |
| async_generators          | 375 ms                                                 | 472 ms: 1.26x slower                                               |
| go                        | 143 ms                                                 | 181 ms: 1.26x slower                                               |
| scimark_monte_carlo       | 71.8 ms                                                | 97.1 ms: 1.35x slower                                              |
| crypto_pyaes              | 77.5 ms                                                | 105 ms: 1.36x slower                                               |
| nqueens                   | 86.8 ms                                                | 120 ms: 1.38x slower                                               |
| fannkuch                  | 410 ms                                                 | 566 ms: 1.38x slower                                               |
| telco                     | 6.72 ms                                                | 9.30 ms: 1.38x slower                                              |
| tomli_loads               | 2.31 sec                                               | 3.30 sec: 1.43x slower                                             |
| python_startup_no_site    | 6.09 ms                                                | 9.07 ms: 1.49x slower                                              |
| pyflate                   | 426 ms                                                 | 645 ms: 1.51x slower                                               |
| float                     | 78.9 ms                                                | 123 ms: 1.56x slower                                               |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 7.92 ms: 1.65x slower                                              |
| deltablue                 | 3.80 ms                                                | 6.38 ms: 1.68x slower                                              |
| scimark_fft               | 342 ms                                                 | 581 ms: 1.70x slower                                               |
| hexiom                    | 6.74 ms                                                | 11.6 ms: 1.73x slower                                              |
| nbody                     | 91.6 ms                                                | 159 ms: 1.74x slower                                               |
| mako                      | 10.8 ms                                                | 19.1 ms: 1.77x slower                                              |
| spectral_norm             | 105 ms                                                 | 209 ms: 1.98x slower                                               |
| Geometric mean            | (ref)                                                  | 1.09x slower                                                       |

Benchmark hidden because not significant (4): bench_mp_pool, sympy_sum, sqlglot_parse, async_tree_cpu_io_mixed_tg
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
