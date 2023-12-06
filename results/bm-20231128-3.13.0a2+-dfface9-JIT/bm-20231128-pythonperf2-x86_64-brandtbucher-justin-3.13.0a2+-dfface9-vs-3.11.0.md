
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.02x faster \*
- HPT reliability: 79.33%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 301 ms: 1.05x slower                                                 |
| chameleon      | 7.42 ms                                                      | 7.71 ms: 1.04x slower                                                |
| tornado_http   | 125 ms                                                       | 120 ms: 1.04x faster                                                 |
| Geometric mean | (ref)                                                        | 1.01x slower                                                         |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 443 ms: 1.19x faster                                                 |
| async_tree_memoization     | 648 ms                                                       | 557 ms: 1.16x faster                                                 |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.09x faster                                               |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 708 ms: 1.08x faster                                                 |
| async_tree_none_tg         | 482 ms                                                       | 450 ms: 1.07x faster                                                 |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                               |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 722 ms: 1.05x faster                                                 |
| async_tree_memoization_tg  | 605 ms                                                       | 580 ms: 1.04x faster                                                 |
| Geometric mean             | (ref)                                                        | 1.09x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                 |
| float          | 76.0 ms                                                      | 80.9 ms: 1.06x slower                                                |
| nbody          | 95.8 ms                                                      | 104 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                        | 1.07x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 149 ms: 1.06x faster                                                 |
| regex_effbot   | 3.42 ms                                                      | 3.51 ms: 1.03x slower                                                |
| regex_v8       | 23.7 ms                                                      | 24.7 ms: 1.04x slower                                                |
| regex_dna      | 226 ms                                                       | 246 ms: 1.09x slower                                                 |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|--------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps         | 13.5 ms                                                      | 10.8 ms: 1.24x faster                                                |
| json_loads         | 29.0 us                                                      | 25.6 us: 1.13x faster                                                |
| xml_etree_parse    | 159 ms                                                       | 151 ms: 1.05x faster                                                 |
| pickle_pure_python | 318 us                                                       | 306 us: 1.04x faster                                                 |
| tomli_loads        | 2.27 sec                                                     | 2.25 sec: 1.01x faster                                               |
| pickle             | 9.77 us                                                      | 9.95 us: 1.02x slower                                                |
| pickle_dict        | 31.8 us                                                      | 33.1 us: 1.04x slower                                                |
| xml_etree_process  | 56.1 ms                                                      | 58.8 ms: 1.05x slower                                                |
| xml_etree_generate | 80.5 ms                                                      | 86.3 ms: 1.07x slower                                                |
| unpickle_list      | 4.47 us                                                      | 4.82 us: 1.08x slower                                                |
| pickle_list        | 3.89 us                                                      | 4.26 us: 1.09x slower                                                |
| unpickle           | 13.2 us                                                      | 15.4 us: 1.16x slower                                                |
| Geometric mean     | (ref)                                                        | 1.00x slower                                                         |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 11.1 ms: 1.01x slower                                                |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 132 us: 4.00x faster                                                 |
| asyncio_tcp                | 752 ms                                                       | 366 ms: 2.06x faster                                                 |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                               |
| generators                 | 56.4 ms                                                      | 34.7 ms: 1.62x faster                                                |
| json_dumps                 | 13.5 ms                                                      | 10.8 ms: 1.24x faster                                                |
| comprehensions             | 24.8 us                                                      | 20.2 us: 1.23x faster                                                |
| coroutines                 | 27.9 ms                                                      | 22.8 ms: 1.22x faster                                                |
| async_tree_none            | 529 ms                                                       | 443 ms: 1.19x faster                                                 |
| sympy_sum                  | 184 ms                                                       | 158 ms: 1.17x faster                                                 |
| async_tree_memoization     | 648 ms                                                       | 557 ms: 1.16x faster                                                 |
| richards_super             | 65.2 ms                                                      | 56.3 ms: 1.16x faster                                                |
| json_loads                 | 29.0 us                                                      | 25.6 us: 1.13x faster                                                |
| sympy_str                  | 336 ms                                                       | 300 ms: 1.12x faster                                                 |
| scimark_lu                 | 115 ms                                                       | 103 ms: 1.12x faster                                                 |
| sqlglot_parse              | 1.55 ms                                                      | 1.40 ms: 1.11x faster                                                |
| logging_simple             | 7.21 us                                                      | 6.56 us: 1.10x faster                                                |
| sympy_expand               | 550 ms                                                       | 502 ms: 1.10x faster                                                 |
| fannkuch                   | 457 ms                                                       | 420 ms: 1.09x faster                                                 |
| async_tree_io              | 1.19 sec                                                     | 1.09 sec: 1.09x faster                                               |
| deltablue                  | 4.03 ms                                                      | 3.73 ms: 1.08x faster                                                |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 708 ms: 1.08x faster                                                 |
| async_tree_none_tg         | 482 ms                                                       | 450 ms: 1.07x faster                                                 |
| json                       | 5.59 ms                                                      | 5.22 ms: 1.07x faster                                                |
| sqlglot_transpile          | 1.94 ms                                                      | 1.83 ms: 1.06x faster                                                |
| async_tree_io_tg           | 1.17 sec                                                     | 1.11 sec: 1.06x faster                                               |
| sympy_integrate            | 25.6 ms                                                      | 24.2 ms: 1.06x faster                                                |
| logging_format             | 7.83 us                                                      | 7.40 us: 1.06x faster                                                |
| regex_compile              | 157 ms                                                       | 149 ms: 1.06x faster                                                 |
| raytrace                   | 308 ms                                                       | 292 ms: 1.05x faster                                                 |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 722 ms: 1.05x faster                                                 |
| bench_thread_pool          | 1.02 ms                                                      | 970 us: 1.05x faster                                                 |
| mdp                        | 2.72 sec                                                     | 2.59 sec: 1.05x faster                                               |
| xml_etree_parse            | 159 ms                                                       | 151 ms: 1.05x faster                                                 |
| tornado_http               | 125 ms                                                       | 120 ms: 1.04x faster                                                 |
| async_tree_memoization_tg  | 605 ms                                                       | 580 ms: 1.04x faster                                                 |
| pickle_pure_python         | 318 us                                                       | 306 us: 1.04x faster                                                 |
| dask                       | 417 ms                                                       | 400 ms: 1.04x faster                                                 |
| gc_traversal               | 4.06 ms                                                      | 3.92 ms: 1.04x faster                                                |
| logging_silent             | 102 ns                                                       | 98.6 ns: 1.03x faster                                                |
| deepcopy                   | 389 us                                                       | 380 us: 1.02x faster                                                 |
| dulwich_log                | 68.3 ms                                                      | 67.1 ms: 1.02x faster                                                |
| pathlib                    | 19.1 ms                                                      | 18.9 ms: 1.01x faster                                                |
| sqlglot_normalize          | 122 ms                                                       | 121 ms: 1.01x faster                                                 |
| tomli_loads                | 2.27 sec                                                     | 2.25 sec: 1.01x faster                                               |
| crypto_pyaes               | 81.8 ms                                                      | 81.3 ms: 1.01x faster                                                |
| chaos                      | 71.6 ms                                                      | 72.1 ms: 1.01x slower                                                |
| mako                       | 11.0 ms                                                      | 11.1 ms: 1.01x slower                                                |
| deepcopy_memo              | 37.3 us                                                      | 37.8 us: 1.01x slower                                                |
| pickle                     | 9.77 us                                                      | 9.95 us: 1.02x slower                                                |
| regex_effbot               | 3.42 ms                                                      | 3.51 ms: 1.03x slower                                                |
| meteor_contest             | 130 ms                                                       | 134 ms: 1.03x slower                                                 |
| pycparser                  | 1.28 sec                                                     | 1.32 sec: 1.03x slower                                               |
| chameleon                  | 7.42 ms                                                      | 7.71 ms: 1.04x slower                                                |
| pickle_dict                | 31.8 us                                                      | 33.1 us: 1.04x slower                                                |
| go                         | 166 ms                                                       | 173 ms: 1.04x slower                                                 |
| sqlglot_optimize           | 59.2 ms                                                      | 61.8 ms: 1.04x slower                                                |
| regex_v8                   | 23.7 ms                                                      | 24.7 ms: 1.04x slower                                                |
| nqueens                    | 99.2 ms                                                      | 104 ms: 1.05x slower                                                 |
| xml_etree_process          | 56.1 ms                                                      | 58.8 ms: 1.05x slower                                                |
| 2to3                       | 286 ms                                                       | 301 ms: 1.05x slower                                                 |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                                 |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.29 ms: 1.06x slower                                                |
| float                      | 76.0 ms                                                      | 80.9 ms: 1.06x slower                                                |
| xml_etree_generate         | 80.5 ms                                                      | 86.3 ms: 1.07x slower                                                |
| bench_mp_pool              | 4.63 ms                                                      | 4.98 ms: 1.08x slower                                                |
| unpickle_list              | 4.47 us                                                      | 4.82 us: 1.08x slower                                                |
| spectral_norm              | 94.0 ms                                                      | 102 ms: 1.08x slower                                                 |
| nbody                      | 95.8 ms                                                      | 104 ms: 1.08x slower                                                 |
| regex_dna                  | 226 ms                                                       | 246 ms: 1.09x slower                                                 |
| pprint_pformat             | 1.63 sec                                                     | 1.78 sec: 1.09x slower                                               |
| pickle_list                | 3.89 us                                                      | 4.26 us: 1.09x slower                                                |
| sqlite_synth               | 2.49 us                                                      | 2.74 us: 1.10x slower                                                |
| hexiom                     | 6.97 ms                                                      | 7.72 ms: 1.11x slower                                                |
| pprint_safe_repr           | 780 ms                                                       | 864 ms: 1.11x slower                                                 |
| pyflate                    | 453 ms                                                       | 517 ms: 1.14x slower                                                 |
| scimark_monte_carlo        | 70.6 ms                                                      | 82.1 ms: 1.16x slower                                                |
| unpickle                   | 13.2 us                                                      | 15.4 us: 1.16x slower                                                |
| async_generators           | 322 ms                                                       | 381 ms: 1.18x slower                                                 |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                |
| telco                      | 6.91 ms                                                      | 8.33 ms: 1.21x slower                                                |
| coverage                   | 66.6 ms                                                      | 81.3 ms: 1.22x slower                                                |
| scimark_fft                | 281 ms                                                       | 364 ms: 1.30x slower                                                 |
| scimark_sor                | 109 ms                                                       | 152 ms: 1.39x slower                                                 |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                |
| mypy2                      | 449 ms                                                       | 885 ms: 1.97x slower                                                 |
| Geometric mean             | (ref)                                                        | 1.02x faster                                                         |

Benchmark hidden because not significant (8): create_gc_cycles, docutils, xml_etree_iterparse, unpack_sequence, unpickle_pure_python, asyncio_websockets, deepcopy_reduce, richards
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 79.33% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
