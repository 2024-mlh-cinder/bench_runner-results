
# Results vs. 3.11.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: linux-x86_64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.03x slower \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 290 ms: 1.09x slower                                                   |
| chameleon      | 6.86 ms                                                | 7.51 ms: 1.09x slower                                                  |
| docutils       | 2.69 sec                                               | 2.72 sec: 1.01x slower                                                 |
| tornado_http   | 97.7 ms                                                | 99.6 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|---------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 459 ms: 1.16x faster                                                   |
| async_tree_memoization    | 640 ms                                                 | 584 ms: 1.10x faster                                                   |
| async_tree_io             | 1.31 sec                                               | 1.22 sec: 1.07x faster                                                 |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.04x faster                                                 |
| async_tree_none_tg        | 490 ms                                                 | 474 ms: 1.03x faster                                                   |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 737 ms: 1.02x faster                                                   |
| async_tree_memoization_tg | 627 ms                                                 | 619 ms: 1.01x faster                                                   |
| Geometric mean            | (ref)                                                  | 1.05x faster                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 197 ms: 1.03x slower                                                   |
| float          | 78.9 ms                                                | 101 ms: 1.28x slower                                                   |
| nbody          | 91.6 ms                                                | 135 ms: 1.47x slower                                                   |
| Geometric mean | (ref)                                                  | 1.25x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.47 ms: 1.01x slower                                                  |
| regex_v8       | 22.9 ms                                                | 24.0 ms: 1.05x slower                                                  |
| regex_dna      | 204 ms                                                 | 215 ms: 1.05x slower                                                   |
| regex_compile  | 141 ms                                                 | 162 ms: 1.15x slower                                                   |
| Geometric mean | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.8 ms: 1.25x faster                                                  |
| json_loads           | 29.4 us                                                | 27.9 us: 1.06x faster                                                  |
| pickle_pure_python   | 319 us                                                 | 305 us: 1.05x faster                                                   |
| pickle_dict          | 34.8 us                                                | 34.1 us: 1.02x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.02x faster                                                   |
| unpickle_list        | 5.22 us                                                | 5.18 us: 1.01x faster                                                  |
| unpickle_pure_python | 241 us                                                 | 242 us: 1.00x slower                                                   |
| pickle               | 11.1 us                                                | 11.5 us: 1.03x slower                                                  |
| xml_etree_iterparse  | 109 ms                                                 | 116 ms: 1.06x slower                                                   |
| unpickle             | 13.9 us                                                | 15.1 us: 1.09x slower                                                  |
| pickle_list          | 4.65 us                                                | 5.16 us: 1.11x slower                                                  |
| tomli_loads          | 2.31 sec                                               | 2.58 sec: 1.11x slower                                                 |
| xml_etree_process    | 56.5 ms                                                | 63.1 ms: 1.12x slower                                                  |
| xml_etree_generate   | 80.4 ms                                                | 92.3 ms: 1.15x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                  |
| python_startup_no_site | 6.09 ms                                                | 9.02 ms: 1.48x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 15.4 ms: 1.42x slower                                                  |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|---------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 122 us: 4.26x faster                                                   |
| generators                | 76.5 ms                                                | 29.8 ms: 2.56x faster                                                  |
| asyncio_tcp               | 887 ms                                                 | 487 ms: 1.82x faster                                                   |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.80 sec: 1.73x faster                                                 |
| json_dumps                | 13.5 ms                                                | 10.8 ms: 1.25x faster                                                  |
| mypy2                     | 427 ms                                                 | 356 ms: 1.20x faster                                                   |
| coroutines                | 26.1 ms                                                | 21.9 ms: 1.19x faster                                                  |
| async_tree_none           | 532 ms                                                 | 459 ms: 1.16x faster                                                   |
| richards_super            | 61.2 ms                                                | 55.7 ms: 1.10x faster                                                  |
| async_tree_memoization    | 640 ms                                                 | 584 ms: 1.10x faster                                                   |
| async_tree_io             | 1.31 sec                                               | 1.22 sec: 1.07x faster                                                 |
| json_loads                | 29.4 us                                                | 27.9 us: 1.06x faster                                                  |
| pickle_pure_python        | 319 us                                                 | 305 us: 1.05x faster                                                   |
| sqlglot_parse             | 1.43 ms                                                | 1.37 ms: 1.04x faster                                                  |
| sympy_sum                 | 170 ms                                                 | 163 ms: 1.04x faster                                                   |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.04x faster                                                 |
| async_tree_none_tg        | 490 ms                                                 | 474 ms: 1.03x faster                                                   |
| sqlglot_transpile         | 1.75 ms                                                | 1.70 ms: 1.03x faster                                                  |
| pickle_dict               | 34.8 us                                                | 34.1 us: 1.02x faster                                                  |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 737 ms: 1.02x faster                                                   |
| xml_etree_parse           | 163 ms                                                 | 160 ms: 1.02x faster                                                   |
| json                      | 5.24 ms                                                | 5.16 ms: 1.01x faster                                                  |
| async_tree_memoization_tg | 627 ms                                                 | 619 ms: 1.01x faster                                                   |
| logging_simple            | 6.24 us                                                | 6.19 us: 1.01x faster                                                  |
| asyncio_websockets        | 556 ms                                                 | 551 ms: 1.01x faster                                                   |
| unpickle_list             | 5.22 us                                                | 5.18 us: 1.01x faster                                                  |
| unpickle_pure_python      | 241 us                                                 | 242 us: 1.00x slower                                                   |
| deepcopy                  | 360 us                                                 | 362 us: 1.00x slower                                                   |
| create_gc_cycles          | 1.48 ms                                                | 1.48 ms: 1.01x slower                                                  |
| regex_effbot              | 3.45 ms                                                | 3.47 ms: 1.01x slower                                                  |
| gc_traversal              | 3.90 ms                                                | 3.94 ms: 1.01x slower                                                  |
| docutils                  | 2.69 sec                                               | 2.72 sec: 1.01x slower                                                 |
| sympy_integrate           | 21.4 ms                                                | 21.6 ms: 1.01x slower                                                  |
| dask                      | 365 ms                                                 | 369 ms: 1.01x slower                                                   |
| richards                  | 48.9 ms                                                | 49.5 ms: 1.01x slower                                                  |
| logging_silent            | 108 ns                                                 | 110 ns: 1.02x slower                                                   |
| tornado_http              | 97.7 ms                                                | 99.6 ms: 1.02x slower                                                  |
| logging_format            | 6.83 us                                                | 7.01 us: 1.03x slower                                                  |
| sympy_expand              | 490 ms                                                 | 504 ms: 1.03x slower                                                   |
| deepcopy_reduce           | 3.14 us                                                | 3.23 us: 1.03x slower                                                  |
| sqlglot_normalize         | 112 ms                                                 | 116 ms: 1.03x slower                                                   |
| pathlib                   | 18.5 ms                                                | 19.1 ms: 1.03x slower                                                  |
| pidigits                  | 190 ms                                                 | 197 ms: 1.03x slower                                                   |
| bench_thread_pool         | 833 us                                                 | 862 us: 1.03x slower                                                   |
| pickle                    | 11.1 us                                                | 11.5 us: 1.03x slower                                                  |
| scimark_sor               | 121 ms                                                 | 126 ms: 1.04x slower                                                   |
| mdp                       | 2.79 sec                                               | 2.90 sec: 1.04x slower                                                 |
| pycparser                 | 1.20 sec                                               | 1.24 sec: 1.04x slower                                                 |
| raytrace                  | 306 ms                                                 | 320 ms: 1.04x slower                                                   |
| regex_v8                  | 22.9 ms                                                | 24.0 ms: 1.05x slower                                                  |
| regex_dna                 | 204 ms                                                 | 215 ms: 1.05x slower                                                   |
| unpack_sequence           | 43.3 ns                                                | 45.9 ns: 1.06x slower                                                  |
| dulwich_log               | 64.9 ms                                                | 69.0 ms: 1.06x slower                                                  |
| scimark_lu                | 112 ms                                                 | 119 ms: 1.06x slower                                                   |
| xml_etree_iterparse       | 109 ms                                                 | 116 ms: 1.06x slower                                                   |
| deepcopy_memo             | 38.9 us                                                | 41.7 us: 1.07x slower                                                  |
| sqlglot_optimize          | 55.2 ms                                                | 59.4 ms: 1.08x slower                                                  |
| meteor_contest            | 109 ms                                                 | 118 ms: 1.08x slower                                                   |
| 2to3                      | 266 ms                                                 | 290 ms: 1.09x slower                                                   |
| unpickle                  | 13.9 us                                                | 15.1 us: 1.09x slower                                                  |
| chameleon                 | 6.86 ms                                                | 7.51 ms: 1.09x slower                                                  |
| chaos                     | 71.4 ms                                                | 78.3 ms: 1.10x slower                                                  |
| pickle_list               | 4.65 us                                                | 5.16 us: 1.11x slower                                                  |
| tomli_loads               | 2.31 sec                                               | 2.58 sec: 1.11x slower                                                 |
| xml_etree_process         | 56.5 ms                                                | 63.1 ms: 1.12x slower                                                  |
| pprint_safe_repr          | 743 ms                                                 | 835 ms: 1.12x slower                                                   |
| sqlite_synth              | 2.58 us                                                | 2.92 us: 1.13x slower                                                  |
| go                        | 143 ms                                                 | 163 ms: 1.14x slower                                                   |
| pprint_pformat            | 1.53 sec                                               | 1.74 sec: 1.14x slower                                                 |
| regex_compile             | 141 ms                                                 | 162 ms: 1.15x slower                                                   |
| xml_etree_generate        | 80.4 ms                                                | 92.3 ms: 1.15x slower                                                  |
| crypto_pyaes              | 77.5 ms                                                | 89.3 ms: 1.15x slower                                                  |
| fannkuch                  | 410 ms                                                 | 476 ms: 1.16x slower                                                   |
| nqueens                   | 86.8 ms                                                | 101 ms: 1.16x slower                                                   |
| coverage                  | 81.2 ms                                                | 95.3 ms: 1.17x slower                                                  |
| python_startup            | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                  |
| scimark_monte_carlo       | 71.8 ms                                                | 86.4 ms: 1.20x slower                                                  |
| async_generators          | 375 ms                                                 | 458 ms: 1.22x slower                                                   |
| telco                     | 6.72 ms                                                | 8.57 ms: 1.28x slower                                                  |
| float                     | 78.9 ms                                                | 101 ms: 1.28x slower                                                   |
| pyflate                   | 426 ms                                                 | 550 ms: 1.29x slower                                                   |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 6.30 ms: 1.31x slower                                                  |
| hexiom                    | 6.74 ms                                                | 9.33 ms: 1.38x slower                                                  |
| deltablue                 | 3.80 ms                                                | 5.31 ms: 1.40x slower                                                  |
| mako                      | 10.8 ms                                                | 15.4 ms: 1.42x slower                                                  |
| scimark_fft               | 342 ms                                                 | 489 ms: 1.43x slower                                                   |
| nbody                     | 91.6 ms                                                | 135 ms: 1.47x slower                                                   |
| python_startup_no_site    | 6.09 ms                                                | 9.02 ms: 1.48x slower                                                  |
| spectral_norm             | 105 ms                                                 | 161 ms: 1.53x slower                                                   |
| Geometric mean            | (ref)                                                  | 1.03x slower                                                           |

Benchmark hidden because not significant (4): bench_mp_pool, async_tree_cpu_io_mixed_tg, comprehensions, sympy_str
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
