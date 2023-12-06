
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 212 ms: 1.02x slower                                      |
| chameleon      | 5.35 ms                                                     | 5.01 ms: 1.07x faster                                     |
| tornado_http   | 89.9 ms                                                     | 87.4 ms: 1.03x faster                                     |
| Geometric mean | (ref)                                                       | 1.02x faster                                              |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| async_tree_memoization     | 367 ms                                                      | 336 ms: 1.09x faster                                      |
| async_tree_none            | 314 ms                                                      | 288 ms: 1.09x faster                                      |
| async_tree_memoization_tg  | 380 ms                                                      | 348 ms: 1.09x faster                                      |
| async_tree_io_tg           | 795 ms                                                      | 743 ms: 1.07x faster                                      |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                      |
| async_tree_io              | 753 ms                                                      | 724 ms: 1.04x faster                                      |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 477 ms: 1.04x faster                                      |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 485 ms: 1.04x faster                                      |
| Geometric mean             | (ref)                                                       | 1.06x faster                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 67.6 ms: 1.02x faster                                     |
| float          | 54.4 ms                                                     | 53.9 ms: 1.01x faster                                     |
| pidigits       | 149 ms                                                      | 152 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x faster                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 85.8 ms: 1.06x faster                                     |
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                      |
| regex_v8       | 13.7 ms                                                     | 13.8 ms: 1.01x slower                                     |
| regex_effbot   | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                     |
| Geometric mean | (ref)                                                       | 1.01x faster                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.60 ms: 1.41x faster                                     |
| unpickle_pure_python | 152 us                                                      | 132 us: 1.15x faster                                      |
| pickle_pure_python   | 207 us                                                      | 192 us: 1.08x faster                                      |
| xml_etree_parse      | 94.5 ms                                                     | 90.6 ms: 1.04x faster                                     |
| tomli_loads          | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                    |
| xml_etree_process    | 37.0 ms                                                     | 37.6 ms: 1.02x slower                                     |
| pickle_dict          | 17.8 us                                                     | 18.3 us: 1.03x slower                                     |
| unpickle             | 7.82 us                                                     | 8.12 us: 1.04x slower                                     |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                     |
| xml_etree_generate   | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                     |
| pickle               | 6.53 us                                                     | 7.07 us: 1.08x slower                                     |
| pickle_list          | 2.68 us                                                     | 2.90 us: 1.08x slower                                     |
| unpickle_list        | 2.57 us                                                     | 2.80 us: 1.09x slower                                     |
| Geometric mean       | (ref)                                                       | 1.01x faster                                              |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 16.0 ms: 1.03x slower                                     |
| Geometric mean         | (ref)                                                       | 1.02x slower                                              |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako            | 7.55 ms                                                     | 6.89 ms: 1.10x faster                                     |
| django_template | 24.0 ms                                                     | 23.3 ms: 1.03x faster                                     |
| Geometric mean  | (ref)                                                       | 1.06x faster                                              |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 77.7 us: 4.11x faster                                     |
| generators                 | 34.0 ms                                                     | 22.1 ms: 1.53x faster                                     |
| json_dumps                 | 7.90 ms                                                     | 5.60 ms: 1.41x faster                                     |
| unpack_sequence            | 47.0 ns                                                     | 36.1 ns: 1.30x faster                                     |
| asyncio_tcp                | 614 ms                                                      | 481 ms: 1.28x faster                                      |
| richards_super             | 37.9 ms                                                     | 30.1 ms: 1.26x faster                                     |
| deltablue                  | 2.63 ms                                                     | 2.16 ms: 1.22x faster                                     |
| logging_silent             | 70.7 ns                                                     | 60.8 ns: 1.16x faster                                     |
| richards                   | 30.8 ms                                                     | 26.6 ms: 1.16x faster                                     |
| unpickle_pure_python       | 152 us                                                      | 132 us: 1.15x faster                                      |
| sqlalchemy_imperative      | 10.5 ms                                                     | 9.13 ms: 1.15x faster                                     |
| go                         | 98.8 ms                                                     | 86.3 ms: 1.14x faster                                     |
| mdp                        | 1.73 sec                                                    | 1.51 sec: 1.14x faster                                    |
| sympy_sum                  | 100.0 ms                                                    | 87.7 ms: 1.14x faster                                     |
| sqlglot_parse              | 939 us                                                      | 830 us: 1.13x faster                                      |
| comprehensions             | 15.6 us                                                     | 13.9 us: 1.12x faster                                     |
| hexiom                     | 4.51 ms                                                     | 4.06 ms: 1.11x faster                                     |
| spectral_norm              | 69.9 ms                                                     | 63.1 ms: 1.11x faster                                     |
| sqlglot_transpile          | 1.15 ms                                                     | 1.04 ms: 1.10x faster                                     |
| chaos                      | 46.8 ms                                                     | 42.4 ms: 1.10x faster                                     |
| deepcopy_memo              | 25.5 us                                                     | 23.1 us: 1.10x faster                                     |
| raytrace                   | 211 ms                                                      | 192 ms: 1.10x faster                                      |
| mako                       | 7.55 ms                                                     | 6.89 ms: 1.10x faster                                     |
| nqueens                    | 66.1 ms                                                     | 60.5 ms: 1.09x faster                                     |
| async_tree_memoization     | 367 ms                                                      | 336 ms: 1.09x faster                                      |
| coverage                   | 43.0 ms                                                     | 39.4 ms: 1.09x faster                                     |
| async_tree_none            | 314 ms                                                      | 288 ms: 1.09x faster                                      |
| async_tree_memoization_tg  | 380 ms                                                      | 348 ms: 1.09x faster                                      |
| mypy2                      | 226 ms                                                      | 208 ms: 1.09x faster                                      |
| sympy_str                  | 184 ms                                                      | 170 ms: 1.08x faster                                      |
| sympy_integrate            | 13.7 ms                                                     | 12.7 ms: 1.08x faster                                     |
| pickle_pure_python         | 207 us                                                      | 192 us: 1.08x faster                                      |
| sympy_expand               | 299 ms                                                      | 277 ms: 1.08x faster                                      |
| scimark_lu                 | 62.3 ms                                                     | 58.0 ms: 1.07x faster                                     |
| async_tree_io_tg           | 795 ms                                                      | 743 ms: 1.07x faster                                      |
| chameleon                  | 5.35 ms                                                     | 5.01 ms: 1.07x faster                                     |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                      |
| deepcopy                   | 242 us                                                      | 229 us: 1.06x faster                                      |
| regex_compile              | 90.8 ms                                                     | 85.8 ms: 1.06x faster                                     |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.47 ms: 1.05x faster                                     |
| pyflate                    | 305 ms                                                      | 291 ms: 1.05x faster                                      |
| logging_format             | 7.06 us                                                     | 6.74 us: 1.05x faster                                     |
| crypto_pyaes               | 48.2 ms                                                     | 46.0 ms: 1.05x faster                                     |
| logging_simple             | 6.60 us                                                     | 6.32 us: 1.05x faster                                     |
| dulwich_log                | 44.1 ms                                                     | 42.2 ms: 1.04x faster                                     |
| xml_etree_parse            | 94.5 ms                                                     | 90.6 ms: 1.04x faster                                     |
| async_tree_io              | 753 ms                                                      | 724 ms: 1.04x faster                                      |
| coroutines                 | 14.7 ms                                                     | 14.1 ms: 1.04x faster                                     |
| fannkuch                   | 248 ms                                                      | 239 ms: 1.04x faster                                      |
| sqlglot_normalize          | 191 ms                                                      | 184 ms: 1.04x faster                                      |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 477 ms: 1.04x faster                                      |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 485 ms: 1.04x faster                                      |
| sqlite_synth               | 1.79 us                                                     | 1.73 us: 1.04x faster                                     |
| dask                       | 262 ms                                                      | 254 ms: 1.03x faster                                      |
| django_template            | 24.0 ms                                                     | 23.3 ms: 1.03x faster                                     |
| pprint_pformat             | 1.06 sec                                                    | 1.03 sec: 1.03x faster                                    |
| bench_thread_pool          | 847 us                                                      | 823 us: 1.03x faster                                      |
| tornado_http               | 89.9 ms                                                     | 87.4 ms: 1.03x faster                                     |
| sqlglot_optimize           | 35.1 ms                                                     | 34.1 ms: 1.03x faster                                     |
| tomli_loads                | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                    |
| pprint_safe_repr           | 519 ms                                                      | 505 ms: 1.03x faster                                      |
| nbody                      | 69.3 ms                                                     | 67.6 ms: 1.02x faster                                     |
| meteor_contest             | 75.0 ms                                                     | 73.9 ms: 1.02x faster                                     |
| regex_dna                  | 121 ms                                                      | 120 ms: 1.01x faster                                      |
| float                      | 54.4 ms                                                     | 53.9 ms: 1.01x faster                                     |
| scimark_fft                | 181 ms                                                      | 181 ms: 1.00x faster                                      |
| regex_v8                   | 13.7 ms                                                     | 13.8 ms: 1.01x slower                                     |
| sqlalchemy_declarative     | 83.9 ms                                                     | 84.3 ms: 1.01x slower                                     |
| scimark_sor                | 76.4 ms                                                     | 77.2 ms: 1.01x slower                                     |
| xml_etree_process          | 37.0 ms                                                     | 37.6 ms: 1.02x slower                                     |
| 2to3                       | 207 ms                                                      | 212 ms: 1.02x slower                                      |
| pidigits                   | 149 ms                                                      | 152 ms: 1.02x slower                                      |
| create_gc_cycles           | 706 us                                                      | 723 us: 1.02x slower                                      |
| telco                      | 3.93 ms                                                     | 4.03 ms: 1.03x slower                                     |
| pickle_dict                | 17.8 us                                                     | 18.3 us: 1.03x slower                                     |
| python_startup_no_site     | 15.5 ms                                                     | 16.0 ms: 1.03x slower                                     |
| bench_mp_pool              | 61.1 ms                                                     | 63.1 ms: 1.03x slower                                     |
| unpickle                   | 7.82 us                                                     | 8.12 us: 1.04x slower                                     |
| json_loads                 | 12.9 us                                                     | 13.4 us: 1.04x slower                                     |
| regex_effbot               | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                     |
| xml_etree_generate         | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                     |
| pickle                     | 6.53 us                                                     | 7.07 us: 1.08x slower                                     |
| pickle_list                | 2.68 us                                                     | 2.90 us: 1.08x slower                                     |
| unpickle_list              | 2.57 us                                                     | 2.80 us: 1.09x slower                                     |
| pathlib                    | 69.4 ms                                                     | 78.8 ms: 1.14x slower                                     |
| async_generators           | 181 ms                                                      | 227 ms: 1.25x slower                                      |
| Geometric mean             | (ref)                                                       | 1.07x faster                                              |

Benchmark hidden because not significant (10): asyncio_tcp_ssl, json, deepcopy_reduce, docutils, scimark_monte_carlo, aiohttp, xml_etree_iterparse, gc_traversal, python_startup, pycparser
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
