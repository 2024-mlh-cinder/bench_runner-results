
# Results vs. 3.11.0

- fork: faster-cpython
- ref: deopts_with_ip
- machine: linux-x86_64
- commit hash: 4d1e295
- commit date: 2023-11-12
- overall geometric mean: 1.01x slower \*
- HPT reliability: 97.45%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 286 ms: 1.07x slower                                                       |
| chameleon      | 6.86 ms                                                | 7.42 ms: 1.08x slower                                                      |
| docutils       | 2.69 sec                                               | 2.73 sec: 1.01x slower                                                     |
| tornado_http   | 97.7 ms                                                | 99.3 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                  | 1.05x slower                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_none           | 532 ms                                                 | 462 ms: 1.15x faster                                                       |
| async_tree_memoization    | 640 ms                                                 | 589 ms: 1.09x faster                                                       |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.06x faster                                                     |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.03x faster                                                     |
| async_tree_none_tg        | 490 ms                                                 | 476 ms: 1.03x faster                                                       |
| async_tree_memoization_tg | 627 ms                                                 | 609 ms: 1.03x faster                                                       |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 739 ms: 1.01x faster                                                       |
| Geometric mean            | (ref)                                                  | 1.05x faster                                                               |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                       |
| nbody          | 91.6 ms                                                | 114 ms: 1.24x slower                                                       |
| float          | 78.9 ms                                                | 98.5 ms: 1.25x slower                                                      |
| Geometric mean | (ref)                                                  | 1.15x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.73 ms: 1.08x slower                                                      |
| regex_dna      | 204 ms                                                 | 221 ms: 1.08x slower                                                       |
| regex_compile  | 141 ms                                                 | 160 ms: 1.13x slower                                                       |
| regex_v8       | 22.9 ms                                                | 26.1 ms: 1.14x slower                                                      |
| Geometric mean | (ref)                                                  | 1.11x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.29x faster                                                      |
| json_loads           | 29.4 us                                                | 28.4 us: 1.04x faster                                                      |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                                       |
| pickle_pure_python   | 319 us                                                 | 314 us: 1.02x faster                                                       |
| pickle_dict          | 34.8 us                                                | 34.3 us: 1.01x faster                                                      |
| unpickle_list        | 5.22 us                                                | 5.16 us: 1.01x faster                                                      |
| unpickle_pure_python | 241 us                                                 | 246 us: 1.02x slower                                                       |
| xml_etree_iterparse  | 109 ms                                                 | 112 ms: 1.03x slower                                                       |
| pickle               | 11.1 us                                                | 11.5 us: 1.04x slower                                                      |
| xml_etree_process    | 56.5 ms                                                | 60.0 ms: 1.06x slower                                                      |
| unpickle             | 13.9 us                                                | 15.0 us: 1.08x slower                                                      |
| xml_etree_generate   | 80.4 ms                                                | 88.2 ms: 1.10x slower                                                      |
| pickle_list          | 4.65 us                                                | 5.22 us: 1.12x slower                                                      |
| tomli_loads          | 2.31 sec                                               | 2.76 sec: 1.19x slower                                                     |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                      |
| python_startup_no_site | 6.09 ms                                                | 9.04 ms: 1.48x slower                                                      |
| Geometric mean         | (ref)                                                  | 1.33x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 14.8 ms: 1.36x slower                                                      |

All benchmarks:
===============

| Benchmark                 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|---------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols  | 521 us                                                 | 128 us: 4.07x faster                                                       |
| generators                | 76.5 ms                                                | 29.8 ms: 2.57x faster                                                      |
| asyncio_tcp               | 887 ms                                                 | 495 ms: 1.79x faster                                                       |
| asyncio_tcp_ssl           | 3.13 sec                                               | 1.81 sec: 1.73x faster                                                     |
| json_dumps                | 13.5 ms                                                | 10.4 ms: 1.29x faster                                                      |
| mypy2                     | 427 ms                                                 | 354 ms: 1.21x faster                                                       |
| coroutines                | 26.1 ms                                                | 22.2 ms: 1.18x faster                                                      |
| async_tree_none           | 532 ms                                                 | 462 ms: 1.15x faster                                                       |
| sympy_sum                 | 170 ms                                                 | 155 ms: 1.10x faster                                                       |
| async_tree_memoization    | 640 ms                                                 | 589 ms: 1.09x faster                                                       |
| richards_super            | 61.2 ms                                                | 56.9 ms: 1.08x faster                                                      |
| async_tree_io             | 1.31 sec                                               | 1.23 sec: 1.06x faster                                                     |
| sqlglot_parse             | 1.43 ms                                                | 1.36 ms: 1.05x faster                                                      |
| sympy_str                 | 299 ms                                                 | 284 ms: 1.05x faster                                                       |
| sqlglot_normalize         | 112 ms                                                 | 107 ms: 1.05x faster                                                       |
| sqlglot_transpile         | 1.75 ms                                                | 1.68 ms: 1.04x faster                                                      |
| json_loads                | 29.4 us                                                | 28.4 us: 1.04x faster                                                      |
| async_tree_io_tg          | 1.30 sec                                               | 1.26 sec: 1.03x faster                                                     |
| async_tree_none_tg        | 490 ms                                                 | 476 ms: 1.03x faster                                                       |
| async_tree_memoization_tg | 627 ms                                                 | 609 ms: 1.03x faster                                                       |
| sympy_expand              | 490 ms                                                 | 477 ms: 1.03x faster                                                       |
| xml_etree_parse           | 163 ms                                                 | 159 ms: 1.02x faster                                                       |
| gc_traversal              | 3.90 ms                                                | 3.83 ms: 1.02x faster                                                      |
| mdp                       | 2.79 sec                                               | 2.74 sec: 1.02x faster                                                     |
| pickle_pure_python        | 319 us                                                 | 314 us: 1.02x faster                                                       |
| async_tree_cpu_io_mixed   | 750 ms                                                 | 739 ms: 1.01x faster                                                       |
| pickle_dict               | 34.8 us                                                | 34.3 us: 1.01x faster                                                      |
| unpickle_list             | 5.22 us                                                | 5.16 us: 1.01x faster                                                      |
| deepcopy                  | 360 us                                                 | 356 us: 1.01x faster                                                       |
| pidigits                  | 190 ms                                                 | 188 ms: 1.01x faster                                                       |
| sqlglot_optimize          | 55.2 ms                                                | 54.6 ms: 1.01x faster                                                      |
| logging_simple            | 6.24 us                                                | 6.18 us: 1.01x faster                                                      |
| raytrace                  | 306 ms                                                 | 304 ms: 1.01x faster                                                       |
| asyncio_websockets        | 556 ms                                                 | 552 ms: 1.01x faster                                                       |
| deepcopy_reduce           | 3.14 us                                                | 3.16 us: 1.01x slower                                                      |
| create_gc_cycles          | 1.48 ms                                                | 1.49 ms: 1.01x slower                                                      |
| comprehensions            | 23.6 us                                                | 23.8 us: 1.01x slower                                                      |
| logging_format            | 6.83 us                                                | 6.92 us: 1.01x slower                                                      |
| docutils                  | 2.69 sec                                               | 2.73 sec: 1.01x slower                                                     |
| tornado_http              | 97.7 ms                                                | 99.3 ms: 1.02x slower                                                      |
| unpickle_pure_python      | 241 us                                                 | 246 us: 1.02x slower                                                       |
| richards                  | 48.9 ms                                                | 50.0 ms: 1.02x slower                                                      |
| logging_silent            | 108 ns                                                 | 111 ns: 1.02x slower                                                       |
| pathlib                   | 18.5 ms                                                | 19.0 ms: 1.03x slower                                                      |
| xml_etree_iterparse       | 109 ms                                                 | 112 ms: 1.03x slower                                                       |
| bench_thread_pool         | 833 us                                                 | 858 us: 1.03x slower                                                       |
| chaos                     | 71.4 ms                                                | 73.5 ms: 1.03x slower                                                      |
| pickle                    | 11.1 us                                                | 11.5 us: 1.04x slower                                                      |
| spectral_norm             | 105 ms                                                 | 109 ms: 1.04x slower                                                       |
| unpack_sequence           | 43.3 ns                                                | 45.3 ns: 1.05x slower                                                      |
| pycparser                 | 1.20 sec                                               | 1.25 sec: 1.05x slower                                                     |
| xml_etree_process         | 56.5 ms                                                | 60.0 ms: 1.06x slower                                                      |
| dulwich_log               | 64.9 ms                                                | 69.0 ms: 1.06x slower                                                      |
| scimark_sor               | 121 ms                                                 | 130 ms: 1.07x slower                                                       |
| meteor_contest            | 109 ms                                                 | 117 ms: 1.07x slower                                                       |
| crypto_pyaes              | 77.5 ms                                                | 83.0 ms: 1.07x slower                                                      |
| 2to3                      | 266 ms                                                 | 286 ms: 1.07x slower                                                       |
| unpickle                  | 13.9 us                                                | 15.0 us: 1.08x slower                                                      |
| scimark_lu                | 112 ms                                                 | 121 ms: 1.08x slower                                                       |
| regex_effbot              | 3.45 ms                                                | 3.73 ms: 1.08x slower                                                      |
| regex_dna                 | 204 ms                                                 | 221 ms: 1.08x slower                                                       |
| chameleon                 | 6.86 ms                                                | 7.42 ms: 1.08x slower                                                      |
| deepcopy_memo             | 38.9 us                                                | 42.5 us: 1.09x slower                                                      |
| xml_etree_generate        | 80.4 ms                                                | 88.2 ms: 1.10x slower                                                      |
| pprint_safe_repr          | 743 ms                                                 | 815 ms: 1.10x slower                                                       |
| pprint_pformat            | 1.53 sec                                               | 1.68 sec: 1.10x slower                                                     |
| pickle_list               | 4.65 us                                                | 5.22 us: 1.12x slower                                                      |
| sqlite_synth              | 2.58 us                                                | 2.92 us: 1.13x slower                                                      |
| regex_compile             | 141 ms                                                 | 160 ms: 1.13x slower                                                       |
| scimark_monte_carlo       | 71.8 ms                                                | 81.5 ms: 1.14x slower                                                      |
| regex_v8                  | 22.9 ms                                                | 26.1 ms: 1.14x slower                                                      |
| go                        | 143 ms                                                 | 164 ms: 1.15x slower                                                       |
| nqueens                   | 86.8 ms                                                | 101 ms: 1.17x slower                                                       |
| fannkuch                  | 410 ms                                                 | 479 ms: 1.17x slower                                                       |
| coverage                  | 81.2 ms                                                | 95.4 ms: 1.17x slower                                                      |
| python_startup            | 8.69 ms                                                | 10.4 ms: 1.19x slower                                                      |
| tomli_loads               | 2.31 sec                                               | 2.76 sec: 1.19x slower                                                     |
| async_generators          | 375 ms                                                 | 459 ms: 1.22x slower                                                       |
| nbody                     | 91.6 ms                                                | 114 ms: 1.24x slower                                                       |
| float                     | 78.9 ms                                                | 98.5 ms: 1.25x slower                                                      |
| scimark_fft               | 342 ms                                                 | 427 ms: 1.25x slower                                                       |
| pyflate                   | 426 ms                                                 | 548 ms: 1.29x slower                                                       |
| deltablue                 | 3.80 ms                                                | 4.90 ms: 1.29x slower                                                      |
| telco                     | 6.72 ms                                                | 8.95 ms: 1.33x slower                                                      |
| mako                      | 10.8 ms                                                | 14.8 ms: 1.36x slower                                                      |
| scimark_sparse_mat_mult   | 4.80 ms                                                | 6.58 ms: 1.37x slower                                                      |
| hexiom                    | 6.74 ms                                                | 9.40 ms: 1.40x slower                                                      |
| python_startup_no_site    | 6.09 ms                                                | 9.04 ms: 1.48x slower                                                      |
| Geometric mean            | (ref)                                                  | 1.01x slower                                                               |

Benchmark hidden because not significant (4): json, sympy_integrate, bench_mp_pool, async_tree_cpu_io_mixed_tg
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 97.45% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
