
# Results vs. 3.11.0

- fork: python
- ref: eb3c94ea669561a0dfac
- machine: linux-x86_64
- commit hash: eb3c94e
- commit date: 2023-11-17
- overall geometric mean: 1.02x slower \*
- HPT reliability: 98.67%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 289 ms: 1.09x slower                                                   |
| chameleon      | 6.86 ms                                                | 7.34 ms: 1.07x slower                                                  |
| docutils       | 2.69 sec                                               | 2.70 sec: 1.00x slower                                                 |
| tornado_http   | 97.7 ms                                                | 99.6 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|---------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 462 ms: 1.15x faster                                                   |
| async_tree_memoization    | 640 ms                                                 | 590 ms: 1.09x faster                                                   |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.07x faster                                                 |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.04x faster                                                 |
| async_tree_none_tg        | 490 ms                                                 | 477 ms: 1.03x faster                                                   |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 730 ms: 1.03x faster                                                   |
| async_tree_memoization_tg | 627 ms                                                 | 614 ms: 1.02x faster                                                   |
| Geometric mean            | (ref)                                                  | 1.05x faster                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                                   |
| float          | 78.9 ms                                                | 103 ms: 1.30x slower                                                   |
| nbody          | 91.6 ms                                                | 131 ms: 1.43x slower                                                   |
| Geometric mean | (ref)                                                  | 1.24x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.59 ms: 1.04x slower                                                  |
| regex_v8       | 22.9 ms                                                | 24.3 ms: 1.06x slower                                                  |
| regex_dna      | 204 ms                                                 | 221 ms: 1.08x slower                                                   |
| regex_compile  | 141 ms                                                 | 160 ms: 1.13x slower                                                   |
| Geometric mean | (ref)                                                  | 1.08x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                  |
| json_loads           | 29.4 us                                                | 28.3 us: 1.04x faster                                                  |
| pickle_pure_python   | 319 us                                                 | 307 us: 1.04x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                                   |
| unpickle_list        | 5.22 us                                                | 5.10 us: 1.02x faster                                                  |
| pickle_dict          | 34.8 us                                                | 34.5 us: 1.01x faster                                                  |
| unpickle_pure_python | 241 us                                                 | 242 us: 1.00x slower                                                   |
| pickle               | 11.1 us                                                | 11.3 us: 1.02x slower                                                  |
| xml_etree_iterparse  | 109 ms                                                 | 111 ms: 1.02x slower                                                   |
| xml_etree_process    | 56.5 ms                                                | 60.5 ms: 1.07x slower                                                  |
| unpickle             | 13.9 us                                                | 14.8 us: 1.07x slower                                                  |
| pickle_list          | 4.65 us                                                | 5.05 us: 1.09x slower                                                  |
| xml_etree_generate   | 80.4 ms                                                | 88.7 ms: 1.10x slower                                                  |
| tomli_loads          | 2.31 sec                                               | 2.77 sec: 1.20x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                  |
| python_startup_no_site | 6.09 ms                                                | 9.01 ms: 1.48x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 15.6 ms: 1.44x slower                                                  |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|---------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 128 us: 4.06x faster                                                   |
| generators                | 76.5 ms                                                | 30.4 ms: 2.51x faster                                                  |
| asyncio_tcp               | 887 ms                                                 | 496 ms: 1.79x faster                                                   |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.81 sec: 1.73x faster                                                 |
| json_dumps                | 13.5 ms                                                | 10.6 ms: 1.27x faster                                                  |
| mypy2                     | 427 ms                                                 | 354 ms: 1.21x faster                                                   |
| coroutines                | 26.1 ms                                                | 22.4 ms: 1.17x faster                                                  |
| async_tree_none           | 532 ms                                                 | 462 ms: 1.15x faster                                                   |
| sympy_sum                 | 170 ms                                                 | 154 ms: 1.10x faster                                                   |
| async_tree_memoization    | 640 ms                                                 | 590 ms: 1.09x faster                                                   |
| richards_super            | 61.2 ms                                                | 57.0 ms: 1.07x faster                                                  |
| sqlglot_parse             | 1.43 ms                                                | 1.34 ms: 1.07x faster                                                  |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.07x faster                                                 |
| sympy_str                 | 299 ms                                                 | 283 ms: 1.06x faster                                                   |
| sqlglot_transpile         | 1.75 ms                                                | 1.67 ms: 1.05x faster                                                  |
| sqlglot_normalize         | 112 ms                                                 | 108 ms: 1.04x faster                                                   |
| json_loads                | 29.4 us                                                | 28.3 us: 1.04x faster                                                  |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.04x faster                                                 |
| pickle_pure_python        | 319 us                                                 | 307 us: 1.04x faster                                                   |
| mdp                       | 2.79 sec                                               | 2.69 sec: 1.04x faster                                                 |
| sympy_expand              | 490 ms                                                 | 476 ms: 1.03x faster                                                   |
| xml_etree_parse           | 163 ms                                                 | 158 ms: 1.03x faster                                                   |
| async_tree_none_tg        | 490 ms                                                 | 477 ms: 1.03x faster                                                   |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 730 ms: 1.03x faster                                                   |
| unpickle_list             | 5.22 us                                                | 5.10 us: 1.02x faster                                                  |
| logging_simple            | 6.24 us                                                | 6.10 us: 1.02x faster                                                  |
| async_tree_memoization_tg | 627 ms                                                 | 614 ms: 1.02x faster                                                   |
| create_gc_cycles          | 1.48 ms                                                | 1.46 ms: 1.01x faster                                                  |
| deepcopy                  | 360 us                                                 | 357 us: 1.01x faster                                                   |
| json                      | 5.24 ms                                                | 5.19 ms: 1.01x faster                                                  |
| sqlglot_optimize          | 55.2 ms                                                | 54.7 ms: 1.01x faster                                                  |
| pickle_dict               | 34.8 us                                                | 34.5 us: 1.01x faster                                                  |
| asyncio_websockets        | 556 ms                                                 | 552 ms: 1.01x faster                                                   |
| sympy_integrate           | 21.4 ms                                                | 21.3 ms: 1.00x faster                                                  |
| unpickle_pure_python      | 241 us                                                 | 242 us: 1.00x slower                                                   |
| docutils                  | 2.69 sec                                               | 2.70 sec: 1.00x slower                                                 |
| comprehensions            | 23.6 us                                                | 23.7 us: 1.01x slower                                                  |
| deepcopy_reduce           | 3.14 us                                                | 3.17 us: 1.01x slower                                                  |
| logging_silent            | 108 ns                                                 | 110 ns: 1.01x slower                                                   |
| pathlib                   | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                  |
| raytrace                  | 306 ms                                                 | 311 ms: 1.02x slower                                                   |
| tornado_http              | 97.7 ms                                                | 99.6 ms: 1.02x slower                                                  |
| pickle                    | 11.1 us                                                | 11.3 us: 1.02x slower                                                  |
| xml_etree_iterparse       | 109 ms                                                 | 111 ms: 1.02x slower                                                   |
| bench_thread_pool         | 833 us                                                 | 852 us: 1.02x slower                                                   |
| pidigits                  | 190 ms                                                 | 196 ms: 1.03x slower                                                   |
| richards                  | 48.9 ms                                                | 50.5 ms: 1.03x slower                                                  |
| regex_effbot              | 3.45 ms                                                | 3.59 ms: 1.04x slower                                                  |
| scimark_sor               | 121 ms                                                 | 127 ms: 1.04x slower                                                   |
| dulwich_log               | 64.9 ms                                                | 68.5 ms: 1.06x slower                                                  |
| regex_v8                  | 22.9 ms                                                | 24.3 ms: 1.06x slower                                                  |
| gc_traversal              | 3.90 ms                                                | 4.16 ms: 1.07x slower                                                  |
| deepcopy_memo             | 38.9 us                                                | 41.6 us: 1.07x slower                                                  |
| xml_etree_process         | 56.5 ms                                                | 60.5 ms: 1.07x slower                                                  |
| scimark_lu                | 112 ms                                                 | 120 ms: 1.07x slower                                                   |
| meteor_contest            | 109 ms                                                 | 117 ms: 1.07x slower                                                   |
| chameleon                 | 6.86 ms                                                | 7.34 ms: 1.07x slower                                                  |
| unpickle                  | 13.9 us                                                | 14.8 us: 1.07x slower                                                  |
| spectral_norm             | 105 ms                                                 | 114 ms: 1.08x slower                                                   |
| regex_dna                 | 204 ms                                                 | 221 ms: 1.08x slower                                                   |
| 2to3                      | 266 ms                                                 | 289 ms: 1.09x slower                                                   |
| pickle_list               | 4.65 us                                                | 5.05 us: 1.09x slower                                                  |
| chaos                     | 71.4 ms                                                | 78.6 ms: 1.10x slower                                                  |
| xml_etree_generate        | 80.4 ms                                                | 88.7 ms: 1.10x slower                                                  |
| pprint_safe_repr          | 743 ms                                                 | 825 ms: 1.11x slower                                                   |
| sqlite_synth              | 2.58 us                                                | 2.88 us: 1.12x slower                                                  |
| crypto_pyaes              | 77.5 ms                                                | 86.9 ms: 1.12x slower                                                  |
| pprint_pformat            | 1.53 sec                                               | 1.73 sec: 1.13x slower                                                 |
| regex_compile             | 141 ms                                                 | 160 ms: 1.13x slower                                                   |
| coverage                  | 81.2 ms                                                | 93.7 ms: 1.15x slower                                                  |
| fannkuch                  | 410 ms                                                 | 473 ms: 1.15x slower                                                   |
| go                        | 143 ms                                                 | 166 ms: 1.16x slower                                                   |
| nqueens                   | 86.8 ms                                                | 102 ms: 1.17x slower                                                   |
| scimark_monte_carlo       | 71.8 ms                                                | 84.7 ms: 1.18x slower                                                  |
| python_startup            | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                  |
| tomli_loads               | 2.31 sec                                               | 2.77 sec: 1.20x slower                                                 |
| async_generators          | 375 ms                                                 | 458 ms: 1.22x slower                                                   |
| pyflate                   | 426 ms                                                 | 538 ms: 1.26x slower                                                   |
| unpack_sequence           | 43.3 ns                                                | 56.4 ns: 1.30x slower                                                  |
| float                     | 78.9 ms                                                | 103 ms: 1.30x slower                                                   |
| telco                     | 6.72 ms                                                | 8.83 ms: 1.32x slower                                                  |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 6.32 ms: 1.32x slower                                                  |
| deltablue                 | 3.80 ms                                                | 5.11 ms: 1.34x slower                                                  |
| scimark_fft               | 342 ms                                                 | 476 ms: 1.39x slower                                                   |
| hexiom                    | 6.74 ms                                                | 9.38 ms: 1.39x slower                                                  |
| nbody                     | 91.6 ms                                                | 131 ms: 1.43x slower                                                   |
| mako                      | 10.8 ms                                                | 15.6 ms: 1.44x slower                                                  |
| python_startup_no_site    | 6.09 ms                                                | 9.01 ms: 1.48x slower                                                  |
| Geometric mean            | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed_tg, logging_format, bench_mp_pool, pycparser, dask
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 98.67% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
