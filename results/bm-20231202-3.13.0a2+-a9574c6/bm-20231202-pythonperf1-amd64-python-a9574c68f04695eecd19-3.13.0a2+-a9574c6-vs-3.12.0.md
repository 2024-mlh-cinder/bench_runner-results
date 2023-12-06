
# Results vs. 3.12.0

- fork: python
- ref: a9574c68f04695eecd19
- machine: windows-amd64
- commit hash: a9574c6
- commit date: 2023-12-02
- overall geometric mean: 1.03x slower \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 217 ms: 1.02x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.17 ms: 1.04x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 88.0 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 270 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 459 ms: 1.04x faster                                                        |
| async_tree_io             | 712 ms                                                      | 738 ms: 1.04x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 287 ms: 1.04x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 346 ms: 1.04x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 778 ms: 1.05x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 369 ms: 1.07x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 74.2 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 86.5 ms: 1.01x faster                                                       |
| regex_effbot   | 1.58 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| regex_dna      | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 15.4 ms: 1.14x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 7.03 us: 1.05x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.60 us: 1.04x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.23 us: 1.03x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.5 us: 1.02x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.74 ms: 1.02x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.02x faster                                                       |
| unpickle_pure_python | 134 us                                                      | 135 us: 1.01x slower                                                        |
| xml_etree_generate   | 55.8 ms                                                     | 57.0 ms: 1.02x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.8 ms: 1.03x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 93.8 ms: 1.04x slower                                                       |
| xml_etree_process    | 37.6 ms                                                     | 39.0 ms: 1.04x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.54 sec: 1.12x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (2): pickle_pure_python, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.1 ms: 1.07x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.0 ms: 1.13x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.93 ms: 1.02x faster                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions            | 14.0 us                                                     | 11.1 us: 1.26x faster                                                       |
| typing_runtime_protocols  | 96.7 us                                                     | 79.2 us: 1.22x faster                                                       |
| raytrace                  | 192 ms                                                      | 172 ms: 1.12x faster                                                        |
| sqlite_synth              | 1.75 us                                                     | 1.58 us: 1.11x faster                                                       |
| async_tree_none           | 286 ms                                                      | 270 ms: 1.06x faster                                                        |
| sympy_sum                 | 90.1 ms                                                     | 85.2 ms: 1.06x faster                                                       |
| pickle                    | 7.38 us                                                     | 7.03 us: 1.05x faster                                                       |
| sympy_str                 | 171 ms                                                      | 164 ms: 1.05x faster                                                        |
| bench_mp_pool             | 67.2 ms                                                     | 64.6 ms: 1.04x faster                                                       |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 459 ms: 1.04x faster                                                        |
| unpickle_list             | 2.69 us                                                     | 2.60 us: 1.04x faster                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 45.3 ms: 1.03x faster                                                       |
| unpickle                  | 8.44 us                                                     | 8.23 us: 1.03x faster                                                       |
| pickle_dict               | 18.9 us                                                     | 18.5 us: 1.02x faster                                                       |
| chaos                     | 42.1 ms                                                     | 41.3 ms: 1.02x faster                                                       |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| mako                      | 7.05 ms                                                     | 6.93 ms: 1.02x faster                                                       |
| json_dumps                | 5.83 ms                                                     | 5.74 ms: 1.02x faster                                                       |
| scimark_monte_carlo       | 43.0 ms                                                     | 42.3 ms: 1.02x faster                                                       |
| json_loads                | 13.6 us                                                     | 13.4 us: 1.02x faster                                                       |
| sympy_integrate           | 13.0 ms                                                     | 12.8 ms: 1.01x faster                                                       |
| spectral_norm             | 63.9 ms                                                     | 63.2 ms: 1.01x faster                                                       |
| docutils                  | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                                      |
| regex_compile             | 87.2 ms                                                     | 86.5 ms: 1.01x faster                                                       |
| dulwich_log               | 42.7 ms                                                     | 42.4 ms: 1.01x faster                                                       |
| regex_effbot              | 1.58 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| unpickle_pure_python      | 134 us                                                      | 135 us: 1.01x slower                                                        |
| tornado_http              | 87.2 ms                                                     | 88.0 ms: 1.01x slower                                                       |
| regex_dna                 | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| sympy_expand              | 278 ms                                                      | 281 ms: 1.01x slower                                                        |
| generators                | 22.6 ms                                                     | 23.1 ms: 1.02x slower                                                       |
| xml_etree_generate        | 55.8 ms                                                     | 57.0 ms: 1.02x slower                                                       |
| 2to3                      | 213 ms                                                      | 217 ms: 1.02x slower                                                        |
| coroutines                | 14.1 ms                                                     | 14.5 ms: 1.02x slower                                                       |
| dask                      | 255 ms                                                      | 261 ms: 1.02x slower                                                        |
| create_gc_cycles          | 726 us                                                      | 744 us: 1.03x slower                                                        |
| deepcopy                  | 233 us                                                      | 239 us: 1.03x slower                                                        |
| xml_etree_iterparse       | 63.1 ms                                                     | 64.8 ms: 1.03x slower                                                       |
| pprint_pformat            | 1.04 sec                                                    | 1.06 sec: 1.03x slower                                                      |
| fannkuch                  | 244 ms                                                      | 251 ms: 1.03x slower                                                        |
| scimark_fft               | 181 ms                                                      | 186 ms: 1.03x slower                                                        |
| pprint_safe_repr          | 508 ms                                                      | 523 ms: 1.03x slower                                                        |
| logging_silent            | 60.5 ns                                                     | 62.5 ns: 1.03x slower                                                       |
| sqlglot_parse             | 802 us                                                      | 829 us: 1.03x slower                                                        |
| scimark_sor               | 79.8 ms                                                     | 82.5 ms: 1.03x slower                                                       |
| pyflate                   | 294 ms                                                      | 304 ms: 1.04x slower                                                        |
| sqlglot_normalize         | 183 ms                                                      | 190 ms: 1.04x slower                                                        |
| async_tree_io             | 712 ms                                                      | 738 ms: 1.04x slower                                                        |
| xml_etree_parse           | 90.5 ms                                                     | 93.8 ms: 1.04x slower                                                       |
| xml_etree_process         | 37.6 ms                                                     | 39.0 ms: 1.04x slower                                                       |
| async_tree_none_tg        | 277 ms                                                      | 287 ms: 1.04x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 346 ms: 1.04x slower                                                        |
| nqueens                   | 61.7 ms                                                     | 64.2 ms: 1.04x slower                                                       |
| meteor_contest            | 72.1 ms                                                     | 75.1 ms: 1.04x slower                                                       |
| async_generators          | 230 ms                                                      | 240 ms: 1.04x slower                                                        |
| go                        | 89.0 ms                                                     | 92.8 ms: 1.04x slower                                                       |
| deltablue                 | 2.12 ms                                                     | 2.21 ms: 1.04x slower                                                       |
| chameleon                 | 4.95 ms                                                     | 5.17 ms: 1.04x slower                                                       |
| logging_format            | 6.72 us                                                     | 7.02 us: 1.05x slower                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 1.06 ms: 1.05x slower                                                       |
| bench_thread_pool         | 830 us                                                      | 870 us: 1.05x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 778 ms: 1.05x slower                                                        |
| scimark_lu                | 57.5 ms                                                     | 60.3 ms: 1.05x slower                                                       |
| logging_simple            | 6.21 us                                                     | 6.53 us: 1.05x slower                                                       |
| deepcopy_memo             | 23.4 us                                                     | 24.7 us: 1.05x slower                                                       |
| sqlglot_optimize          | 34.0 ms                                                     | 36.0 ms: 1.06x slower                                                       |
| hexiom                    | 4.00 ms                                                     | 4.24 ms: 1.06x slower                                                       |
| python_startup            | 18.8 ms                                                     | 20.1 ms: 1.07x slower                                                       |
| async_tree_memoization_tg | 345 ms                                                      | 369 ms: 1.07x slower                                                        |
| nbody                     | 68.8 ms                                                     | 74.2 ms: 1.08x slower                                                       |
| mdp                       | 1.42 sec                                                    | 1.53 sec: 1.08x slower                                                      |
| richards_super            | 31.2 ms                                                     | 33.9 ms: 1.09x slower                                                       |
| richards                  | 27.6 ms                                                     | 30.3 ms: 1.10x slower                                                       |
| tomli_loads               | 1.38 sec                                                    | 1.54 sec: 1.12x slower                                                      |
| python_startup_no_site    | 15.9 ms                                                     | 18.0 ms: 1.13x slower                                                       |
| regex_v8                  | 13.5 ms                                                     | 15.4 ms: 1.14x slower                                                       |
| unpack_sequence           | 36.9 ns                                                     | 42.4 ns: 1.15x slower                                                       |
| telco                     | 4.08 ms                                                     | 4.81 ms: 1.18x slower                                                       |
| coverage                  | 39.8 ms                                                     | 47.3 ms: 1.19x slower                                                       |
| pycparser                 | 673 ms                                                      | 851 ms: 1.26x slower                                                        |
| mypy2                     | 209 ms                                                      | 426 ms: 2.04x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.03x slower                                                                |

Benchmark hidden because not significant (11): asyncio_tcp, asyncio_tcp_ssl, float, scimark_sparse_mat_mult, pickle_pure_python, pickle_list, pathlib, gc_traversal, deepcopy_reduce, async_tree_cpu_io_mixed_tg, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
