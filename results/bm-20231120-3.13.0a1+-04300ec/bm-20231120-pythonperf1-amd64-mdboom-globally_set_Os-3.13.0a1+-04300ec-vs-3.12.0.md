
# Results vs. 3.12.0

- fork: mdboom
- ref: globally_set_Os
- machine: windows-amd64
- commit hash: 04300ec
- commit date: 2023-11-20
- overall geometric mean: 1.01x faster \*
- HPT reliability: 84.43%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 209 ms: 1.02x faster                                                   |
| chameleon      | 4.95 ms                                                     | 4.91 ms: 1.01x faster                                                  |
| docutils       | 1.61 sec                                                    | 1.55 sec: 1.04x faster                                                 |
| tornado_http   | 87.2 ms                                                     | 96.1 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                       | 1.01x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 279 ms: 1.03x faster                                                   |
| async_tree_none_tg         | 277 ms                                                      | 281 ms: 1.02x slower                                                   |
| async_tree_io              | 712 ms                                                      | 730 ms: 1.03x slower                                                   |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 496 ms: 1.03x slower                                                   |
| async_tree_io_tg           | 742 ms                                                      | 766 ms: 1.03x slower                                                   |
| async_tree_memoization     | 333 ms                                                      | 344 ms: 1.03x slower                                                   |
| async_tree_memoization_tg  | 345 ms                                                      | 367 ms: 1.06x slower                                                   |
| Geometric mean             | (ref)                                                       | 1.02x slower                                                           |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 51.2 ms: 1.07x faster                                                  |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                   |
| nbody          | 68.8 ms                                                     | 73.6 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                       | 1.01x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 78.9 ms: 1.11x faster                                                  |
| regex_dna      | 119 ms                                                      | 121 ms: 1.02x slower                                                   |
| regex_effbot   | 1.58 ms                                                     | 1.62 ms: 1.02x slower                                                  |
| regex_v8       | 13.5 ms                                                     | 15.2 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                       | 1.01x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_list          | 2.88 us                                                     | 2.63 us: 1.10x faster                                                  |
| pickle_dict          | 18.9 us                                                     | 17.4 us: 1.09x faster                                                  |
| pickle               | 7.38 us                                                     | 6.81 us: 1.08x faster                                                  |
| pickle_pure_python   | 195 us                                                      | 184 us: 1.06x faster                                                   |
| xml_etree_generate   | 55.8 ms                                                     | 53.4 ms: 1.05x faster                                                  |
| json_dumps           | 5.83 ms                                                     | 5.63 ms: 1.04x faster                                                  |
| unpickle_pure_python | 134 us                                                      | 131 us: 1.03x faster                                                   |
| unpickle_list        | 2.69 us                                                     | 2.63 us: 1.02x faster                                                  |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.02x faster                                                  |
| xml_etree_process    | 37.6 ms                                                     | 36.9 ms: 1.02x faster                                                  |
| unpickle             | 8.44 us                                                     | 8.34 us: 1.01x faster                                                  |
| xml_etree_parse      | 90.5 ms                                                     | 92.8 ms: 1.02x slower                                                  |
| tomli_loads          | 1.38 sec                                                    | 1.44 sec: 1.04x slower                                                 |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                           |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                  |
| python_startup_no_site | 15.9 ms                                                     | 17.9 ms: 1.13x slower                                                  |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.43 ms: 1.10x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| comprehensions             | 14.0 us                                                     | 10.4 us: 1.34x faster                                                  |
| typing_runtime_protocols   | 96.7 us                                                     | 75.9 us: 1.27x faster                                                  |
| raytrace                   | 192 ms                                                      | 161 ms: 1.20x faster                                                   |
| sqlite_synth               | 1.75 us                                                     | 1.56 us: 1.12x faster                                                  |
| regex_compile              | 87.2 ms                                                     | 78.9 ms: 1.11x faster                                                  |
| mako                       | 7.05 ms                                                     | 6.43 ms: 1.10x faster                                                  |
| pickle_list                | 2.88 us                                                     | 2.63 us: 1.10x faster                                                  |
| pickle_dict                | 18.9 us                                                     | 17.4 us: 1.09x faster                                                  |
| logging_silent             | 60.5 ns                                                     | 55.4 ns: 1.09x faster                                                  |
| crypto_pyaes               | 46.4 ms                                                     | 42.6 ms: 1.09x faster                                                  |
| sympy_sum                  | 90.1 ms                                                     | 82.7 ms: 1.09x faster                                                  |
| generators                 | 22.6 ms                                                     | 20.8 ms: 1.09x faster                                                  |
| pickle                     | 7.38 us                                                     | 6.81 us: 1.08x faster                                                  |
| sympy_str                  | 171 ms                                                      | 158 ms: 1.08x faster                                                   |
| chaos                      | 42.1 ms                                                     | 39.4 ms: 1.07x faster                                                  |
| float                      | 54.7 ms                                                     | 51.2 ms: 1.07x faster                                                  |
| nqueens                    | 61.7 ms                                                     | 58.2 ms: 1.06x faster                                                  |
| coroutines                 | 14.1 ms                                                     | 13.3 ms: 1.06x faster                                                  |
| pickle_pure_python         | 195 us                                                      | 184 us: 1.06x faster                                                   |
| deltablue                  | 2.12 ms                                                     | 2.01 ms: 1.06x faster                                                  |
| sqlglot_parse              | 802 us                                                      | 759 us: 1.06x faster                                                   |
| deepcopy_reduce            | 2.08 us                                                     | 1.98 us: 1.05x faster                                                  |
| sympy_integrate            | 13.0 ms                                                     | 12.4 ms: 1.05x faster                                                  |
| xml_etree_generate         | 55.8 ms                                                     | 53.4 ms: 1.05x faster                                                  |
| hexiom                     | 4.00 ms                                                     | 3.83 ms: 1.04x faster                                                  |
| bench_mp_pool              | 67.2 ms                                                     | 64.6 ms: 1.04x faster                                                  |
| sqlglot_transpile          | 1.02 ms                                                     | 980 us: 1.04x faster                                                   |
| docutils                   | 1.61 sec                                                    | 1.55 sec: 1.04x faster                                                 |
| logging_format             | 6.72 us                                                     | 6.48 us: 1.04x faster                                                  |
| json_dumps                 | 5.83 ms                                                     | 5.63 ms: 1.04x faster                                                  |
| deepcopy                   | 233 us                                                      | 226 us: 1.03x faster                                                   |
| unpickle_pure_python       | 134 us                                                      | 131 us: 1.03x faster                                                   |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.44 ms: 1.03x faster                                                  |
| scimark_monte_carlo        | 43.0 ms                                                     | 41.8 ms: 1.03x faster                                                  |
| dulwich_log                | 42.7 ms                                                     | 41.6 ms: 1.03x faster                                                  |
| async_tree_none            | 286 ms                                                      | 279 ms: 1.03x faster                                                   |
| richards_super             | 31.2 ms                                                     | 30.4 ms: 1.02x faster                                                  |
| pidigits                   | 150 ms                                                      | 147 ms: 1.02x faster                                                   |
| logging_simple             | 6.21 us                                                     | 6.06 us: 1.02x faster                                                  |
| unpickle_list              | 2.69 us                                                     | 2.63 us: 1.02x faster                                                  |
| go                         | 89.0 ms                                                     | 87.2 ms: 1.02x faster                                                  |
| sqlglot_normalize          | 183 ms                                                      | 180 ms: 1.02x faster                                                   |
| sympy_expand               | 278 ms                                                      | 273 ms: 1.02x faster                                                   |
| json_loads                 | 13.6 us                                                     | 13.4 us: 1.02x faster                                                  |
| xml_etree_process          | 37.6 ms                                                     | 36.9 ms: 1.02x faster                                                  |
| 2to3                       | 213 ms                                                      | 209 ms: 1.02x faster                                                   |
| richards                   | 27.6 ms                                                     | 27.2 ms: 1.02x faster                                                  |
| pyflate                    | 294 ms                                                      | 289 ms: 1.02x faster                                                   |
| pprint_safe_repr           | 508 ms                                                      | 502 ms: 1.01x faster                                                   |
| unpickle                   | 8.44 us                                                     | 8.34 us: 1.01x faster                                                  |
| chameleon                  | 4.95 ms                                                     | 4.91 ms: 1.01x faster                                                  |
| scimark_lu                 | 57.5 ms                                                     | 57.0 ms: 1.01x faster                                                  |
| pprint_pformat             | 1.04 sec                                                    | 1.03 sec: 1.00x faster                                                 |
| mdp                        | 1.42 sec                                                    | 1.42 sec: 1.00x faster                                                 |
| gc_traversal               | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                                  |
| async_generators           | 230 ms                                                      | 232 ms: 1.01x slower                                                   |
| regex_dna                  | 119 ms                                                      | 121 ms: 1.02x slower                                                   |
| async_tree_none_tg         | 277 ms                                                      | 281 ms: 1.02x slower                                                   |
| meteor_contest             | 72.1 ms                                                     | 73.5 ms: 1.02x slower                                                  |
| regex_effbot               | 1.58 ms                                                     | 1.62 ms: 1.02x slower                                                  |
| xml_etree_parse            | 90.5 ms                                                     | 92.8 ms: 1.02x slower                                                  |
| async_tree_io              | 712 ms                                                      | 730 ms: 1.03x slower                                                   |
| scimark_fft                | 181 ms                                                      | 186 ms: 1.03x slower                                                   |
| scimark_sor                | 79.8 ms                                                     | 81.9 ms: 1.03x slower                                                  |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 496 ms: 1.03x slower                                                   |
| spectral_norm              | 63.9 ms                                                     | 65.6 ms: 1.03x slower                                                  |
| create_gc_cycles           | 726 us                                                      | 749 us: 1.03x slower                                                   |
| async_tree_io_tg           | 742 ms                                                      | 766 ms: 1.03x slower                                                   |
| async_tree_memoization     | 333 ms                                                      | 344 ms: 1.03x slower                                                   |
| pathlib                    | 79.6 ms                                                     | 82.9 ms: 1.04x slower                                                  |
| dask                       | 255 ms                                                      | 265 ms: 1.04x slower                                                   |
| tomli_loads                | 1.38 sec                                                    | 1.44 sec: 1.04x slower                                                 |
| fannkuch                   | 244 ms                                                      | 255 ms: 1.04x slower                                                   |
| bench_thread_pool          | 830 us                                                      | 870 us: 1.05x slower                                                   |
| python_startup             | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                  |
| async_tree_memoization_tg  | 345 ms                                                      | 367 ms: 1.06x slower                                                   |
| nbody                      | 68.8 ms                                                     | 73.6 ms: 1.07x slower                                                  |
| unpack_sequence            | 36.9 ns                                                     | 40.0 ns: 1.08x slower                                                  |
| tornado_http               | 87.2 ms                                                     | 96.1 ms: 1.10x slower                                                  |
| python_startup_no_site     | 15.9 ms                                                     | 17.9 ms: 1.13x slower                                                  |
| regex_v8                   | 13.5 ms                                                     | 15.2 ms: 1.13x slower                                                  |
| asyncio_tcp                | 471 ms                                                      | 534 ms: 1.13x slower                                                   |
| telco                      | 4.08 ms                                                     | 4.64 ms: 1.14x slower                                                  |
| pycparser                  | 673 ms                                                      | 781 ms: 1.16x slower                                                   |
| coverage                   | 39.8 ms                                                     | 47.5 ms: 1.19x slower                                                  |
| mypy2                      | 209 ms                                                      | 287 ms: 1.37x slower                                                   |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                           |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed, xml_etree_iterparse, sqlglot_optimize, deepcopy_memo, json, asyncio_tcp_ssl
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 84.43% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
