
# Results vs. 3.11.0

- fork: mdboom
- ref: globally_set_Os
- machine: windows-amd64
- commit hash: 04300ec
- commit date: 2023-11-20
- overall geometric mean: 1.07x faster \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 209 ms: 1.01x slower                                                   |
| chameleon      | 5.35 ms                                                     | 4.91 ms: 1.09x faster                                                  |
| docutils       | 1.59 sec                                                    | 1.55 sec: 1.02x faster                                                 |
| tornado_http   | 89.9 ms                                                     | 96.1 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                       | 1.01x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|---------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none           | 314 ms                                                      | 279 ms: 1.12x faster                                                   |
| async_tree_memoization    | 367 ms                                                      | 344 ms: 1.07x faster                                                   |
| async_tree_none_tg        | 299 ms                                                      | 281 ms: 1.06x faster                                                   |
| async_tree_cpu_io_mixed   | 495 ms                                                      | 471 ms: 1.05x faster                                                   |
| async_tree_io_tg          | 795 ms                                                      | 766 ms: 1.04x faster                                                   |
| async_tree_memoization_tg | 380 ms                                                      | 367 ms: 1.03x faster                                                   |
| async_tree_io             | 753 ms                                                      | 730 ms: 1.03x faster                                                   |
| Geometric mean            | (ref)                                                       | 1.05x faster                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 51.2 ms: 1.06x faster                                                  |
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                   |
| nbody          | 69.3 ms                                                     | 73.6 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                       | 1.00x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 78.9 ms: 1.15x faster                                                  |
| regex_effbot   | 1.52 ms                                                     | 1.62 ms: 1.06x slower                                                  |
| regex_v8       | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                                  |
| Geometric mean | (ref)                                                       | 1.01x slower                                                           |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.63 ms: 1.40x faster                                                  |
| unpickle_pure_python | 152 us                                                      | 131 us: 1.17x faster                                                   |
| pickle_pure_python   | 207 us                                                      | 184 us: 1.13x faster                                                   |
| pickle_dict          | 17.8 us                                                     | 17.4 us: 1.02x faster                                                  |
| xml_etree_parse      | 94.5 ms                                                     | 92.8 ms: 1.02x faster                                                  |
| pickle_list          | 2.68 us                                                     | 2.63 us: 1.02x faster                                                  |
| tomli_loads          | 1.42 sec                                                    | 1.44 sec: 1.01x slower                                                 |
| xml_etree_generate   | 52.2 ms                                                     | 53.4 ms: 1.02x slower                                                  |
| unpickle_list        | 2.57 us                                                     | 2.63 us: 1.03x slower                                                  |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                                  |
| pickle               | 6.53 us                                                     | 6.81 us: 1.04x slower                                                  |
| unpickle             | 7.82 us                                                     | 8.34 us: 1.07x slower                                                  |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                           |

Benchmark hidden because not significant (2): xml_etree_process, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                  |
| python_startup_no_site | 15.5 ms                                                     | 17.9 ms: 1.16x slower                                                  |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.43 ms: 1.18x faster                                                  |

All benchmarks:
===============

| Benchmark                 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|---------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols  | 320 us                                                      | 75.9 us: 4.22x faster                                                  |
| generators                | 34.0 ms                                                     | 20.8 ms: 1.64x faster                                                  |
| comprehensions            | 15.6 us                                                     | 10.4 us: 1.49x faster                                                  |
| json_dumps                | 7.90 ms                                                     | 5.63 ms: 1.40x faster                                                  |
| raytrace                  | 211 ms                                                      | 161 ms: 1.31x faster                                                   |
| deltablue                 | 2.63 ms                                                     | 2.01 ms: 1.31x faster                                                  |
| logging_silent            | 70.7 ns                                                     | 55.4 ns: 1.27x faster                                                  |
| richards_super            | 37.9 ms                                                     | 30.4 ms: 1.25x faster                                                  |
| sqlglot_parse             | 939 us                                                      | 759 us: 1.24x faster                                                   |
| mdp                       | 1.73 sec                                                    | 1.42 sec: 1.22x faster                                                 |
| sympy_sum                 | 100.0 ms                                                    | 82.7 ms: 1.21x faster                                                  |
| chaos                     | 46.8 ms                                                     | 39.4 ms: 1.19x faster                                                  |
| hexiom                    | 4.51 ms                                                     | 3.83 ms: 1.18x faster                                                  |
| mako                      | 7.55 ms                                                     | 6.43 ms: 1.18x faster                                                  |
| unpack_sequence           | 47.0 ns                                                     | 40.0 ns: 1.17x faster                                                  |
| sqlglot_transpile         | 1.15 ms                                                     | 980 us: 1.17x faster                                                   |
| unpickle_pure_python      | 152 us                                                      | 131 us: 1.17x faster                                                   |
| sympy_str                 | 184 ms                                                      | 158 ms: 1.16x faster                                                   |
| regex_compile             | 90.8 ms                                                     | 78.9 ms: 1.15x faster                                                  |
| sqlite_synth              | 1.79 us                                                     | 1.56 us: 1.15x faster                                                  |
| asyncio_tcp               | 614 ms                                                      | 534 ms: 1.15x faster                                                   |
| nqueens                   | 66.1 ms                                                     | 58.2 ms: 1.14x faster                                                  |
| richards                  | 30.8 ms                                                     | 27.2 ms: 1.13x faster                                                  |
| go                        | 98.8 ms                                                     | 87.2 ms: 1.13x faster                                                  |
| crypto_pyaes              | 48.2 ms                                                     | 42.6 ms: 1.13x faster                                                  |
| pickle_pure_python        | 207 us                                                      | 184 us: 1.13x faster                                                   |
| async_tree_none           | 314 ms                                                      | 279 ms: 1.12x faster                                                   |
| sympy_integrate           | 13.7 ms                                                     | 12.4 ms: 1.11x faster                                                  |
| coroutines                | 14.7 ms                                                     | 13.3 ms: 1.10x faster                                                  |
| sympy_expand              | 299 ms                                                      | 273 ms: 1.10x faster                                                   |
| scimark_lu                | 62.3 ms                                                     | 57.0 ms: 1.09x faster                                                  |
| chameleon                 | 5.35 ms                                                     | 4.91 ms: 1.09x faster                                                  |
| logging_simple            | 6.60 us                                                     | 6.06 us: 1.09x faster                                                  |
| logging_format            | 7.06 us                                                     | 6.48 us: 1.09x faster                                                  |
| deepcopy_memo             | 25.5 us                                                     | 23.5 us: 1.09x faster                                                  |
| deepcopy                  | 242 us                                                      | 226 us: 1.07x faster                                                   |
| async_tree_memoization    | 367 ms                                                      | 344 ms: 1.07x faster                                                   |
| scimark_monte_carlo       | 44.6 ms                                                     | 41.8 ms: 1.07x faster                                                  |
| spectral_norm             | 69.9 ms                                                     | 65.6 ms: 1.06x faster                                                  |
| async_tree_none_tg        | 299 ms                                                      | 281 ms: 1.06x faster                                                   |
| sqlglot_normalize         | 191 ms                                                      | 180 ms: 1.06x faster                                                   |
| float                     | 54.4 ms                                                     | 51.2 ms: 1.06x faster                                                  |
| dulwich_log               | 44.1 ms                                                     | 41.6 ms: 1.06x faster                                                  |
| scimark_sparse_mat_mult   | 2.59 ms                                                     | 2.44 ms: 1.06x faster                                                  |
| pyflate                   | 305 ms                                                      | 289 ms: 1.05x faster                                                   |
| async_tree_cpu_io_mixed   | 495 ms                                                      | 471 ms: 1.05x faster                                                   |
| deepcopy_reduce           | 2.07 us                                                     | 1.98 us: 1.05x faster                                                  |
| async_tree_io_tg          | 795 ms                                                      | 766 ms: 1.04x faster                                                   |
| async_tree_memoization_tg | 380 ms                                                      | 367 ms: 1.03x faster                                                   |
| pprint_safe_repr          | 519 ms                                                      | 502 ms: 1.03x faster                                                   |
| async_tree_io             | 753 ms                                                      | 730 ms: 1.03x faster                                                   |
| sqlglot_optimize          | 35.1 ms                                                     | 34.0 ms: 1.03x faster                                                  |
| pprint_pformat            | 1.06 sec                                                    | 1.03 sec: 1.03x faster                                                 |
| docutils                  | 1.59 sec                                                    | 1.55 sec: 1.02x faster                                                 |
| pickle_dict               | 17.8 us                                                     | 17.4 us: 1.02x faster                                                  |
| meteor_contest            | 75.0 ms                                                     | 73.5 ms: 1.02x faster                                                  |
| xml_etree_parse           | 94.5 ms                                                     | 92.8 ms: 1.02x faster                                                  |
| pickle_list               | 2.68 us                                                     | 2.63 us: 1.02x faster                                                  |
| pidigits                  | 149 ms                                                      | 147 ms: 1.01x faster                                                   |
| 2to3                      | 207 ms                                                      | 209 ms: 1.01x slower                                                   |
| tomli_loads               | 1.42 sec                                                    | 1.44 sec: 1.01x slower                                                 |
| xml_etree_generate        | 52.2 ms                                                     | 53.4 ms: 1.02x slower                                                  |
| scimark_fft               | 181 ms                                                      | 186 ms: 1.02x slower                                                   |
| fannkuch                  | 248 ms                                                      | 255 ms: 1.03x slower                                                   |
| unpickle_list             | 2.57 us                                                     | 2.63 us: 1.03x slower                                                  |
| bench_thread_pool         | 847 us                                                      | 870 us: 1.03x slower                                                   |
| gc_traversal              | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                  |
| json_loads                | 12.9 us                                                     | 13.4 us: 1.04x slower                                                  |
| pickle                    | 6.53 us                                                     | 6.81 us: 1.04x slower                                                  |
| bench_mp_pool             | 61.1 ms                                                     | 64.6 ms: 1.06x slower                                                  |
| create_gc_cycles          | 706 us                                                      | 749 us: 1.06x slower                                                   |
| python_startup            | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                  |
| nbody                     | 69.3 ms                                                     | 73.6 ms: 1.06x slower                                                  |
| regex_effbot              | 1.52 ms                                                     | 1.62 ms: 1.06x slower                                                  |
| unpickle                  | 7.82 us                                                     | 8.34 us: 1.07x slower                                                  |
| tornado_http              | 89.9 ms                                                     | 96.1 ms: 1.07x slower                                                  |
| scimark_sor               | 76.4 ms                                                     | 81.9 ms: 1.07x slower                                                  |
| coverage                  | 43.0 ms                                                     | 47.5 ms: 1.11x slower                                                  |
| pycparser                 | 705 ms                                                      | 781 ms: 1.11x slower                                                   |
| regex_v8                  | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                                  |
| python_startup_no_site    | 15.5 ms                                                     | 17.9 ms: 1.16x slower                                                  |
| telco                     | 3.93 ms                                                     | 4.64 ms: 1.18x slower                                                  |
| pathlib                   | 69.4 ms                                                     | 82.9 ms: 1.19x slower                                                  |
| mypy2                     | 226 ms                                                      | 287 ms: 1.27x slower                                                   |
| async_generators          | 181 ms                                                      | 232 ms: 1.28x slower                                                   |
| Geometric mean            | (ref)                                                       | 1.07x faster                                                           |

Benchmark hidden because not significant (7): asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, json, xml_etree_process, regex_dna, xml_etree_iterparse, dask
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
