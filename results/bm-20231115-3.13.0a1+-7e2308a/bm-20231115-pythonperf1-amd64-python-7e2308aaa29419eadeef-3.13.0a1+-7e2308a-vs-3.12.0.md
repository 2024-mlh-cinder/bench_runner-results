
# Results vs. 3.12.0

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: windows-amd64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.65%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 209 ms: 1.01x faster                                                        |
| chameleon      | 4.95 ms                                                     | 4.81 ms: 1.03x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.55 sec: 1.04x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 86.4 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 266 ms: 1.07x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 455 ms: 1.05x faster                                                        |
| async_tree_none_tg        | 277 ms                                                      | 280 ms: 1.01x slower                                                        |
| async_tree_io             | 712 ms                                                      | 723 ms: 1.02x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 755 ms: 1.02x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 341 ms: 1.02x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 363 ms: 1.05x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 51.7 ms: 1.06x faster                                                       |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 73.4 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 80.1 ms: 1.09x faster                                                       |
| regex_dna      | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 15.0 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.89 us: 1.07x faster                                                       |
| pickle_pure_python   | 195 us                                                      | 182 us: 1.07x faster                                                        |
| unpickle             | 8.44 us                                                     | 7.91 us: 1.07x faster                                                       |
| unpickle_pure_python | 134 us                                                      | 128 us: 1.05x faster                                                        |
| pickle_dict          | 18.9 us                                                     | 18.1 us: 1.05x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.60 ms: 1.04x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.61 us: 1.03x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.5 ms: 1.02x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 36.9 ms: 1.02x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.85 us: 1.01x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 91.8 ms: 1.01x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.1 ms: 1.02x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.42 sec: 1.03x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.8 ms: 1.12x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.51 ms: 1.08x faster                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions            | 14.0 us                                                     | 10.5 us: 1.34x faster                                                       |
| typing_runtime_protocols  | 96.7 us                                                     | 75.2 us: 1.29x faster                                                       |
| raytrace                  | 192 ms                                                      | 163 ms: 1.18x faster                                                        |
| sqlite_synth              | 1.75 us                                                     | 1.57 us: 1.11x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 82.1 ms: 1.10x faster                                                       |
| sympy_str                 | 171 ms                                                      | 157 ms: 1.09x faster                                                        |
| regex_compile             | 87.2 ms                                                     | 80.1 ms: 1.09x faster                                                       |
| mako                      | 7.05 ms                                                     | 6.51 ms: 1.08x faster                                                       |
| nqueens                   | 61.7 ms                                                     | 57.2 ms: 1.08x faster                                                       |
| logging_silent            | 60.5 ns                                                     | 56.1 ns: 1.08x faster                                                       |
| generators                | 22.6 ms                                                     | 21.0 ms: 1.08x faster                                                       |
| async_tree_none           | 286 ms                                                      | 266 ms: 1.07x faster                                                        |
| bench_mp_pool             | 67.2 ms                                                     | 62.7 ms: 1.07x faster                                                       |
| pickle                    | 7.38 us                                                     | 6.89 us: 1.07x faster                                                       |
| pickle_pure_python        | 195 us                                                      | 182 us: 1.07x faster                                                        |
| deepcopy_reduce           | 2.08 us                                                     | 1.95 us: 1.07x faster                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 43.5 ms: 1.07x faster                                                       |
| unpickle                  | 8.44 us                                                     | 7.91 us: 1.07x faster                                                       |
| chaos                     | 42.1 ms                                                     | 39.6 ms: 1.06x faster                                                       |
| float                     | 54.7 ms                                                     | 51.7 ms: 1.06x faster                                                       |
| deepcopy                  | 233 us                                                      | 220 us: 1.06x faster                                                        |
| sympy_integrate           | 13.0 ms                                                     | 12.3 ms: 1.05x faster                                                       |
| pathlib                   | 79.6 ms                                                     | 75.5 ms: 1.05x faster                                                       |
| coroutines                | 14.1 ms                                                     | 13.4 ms: 1.05x faster                                                       |
| unpickle_pure_python      | 134 us                                                      | 128 us: 1.05x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 455 ms: 1.05x faster                                                        |
| pickle_dict               | 18.9 us                                                     | 18.1 us: 1.05x faster                                                       |
| sqlglot_normalize         | 183 ms                                                      | 175 ms: 1.05x faster                                                        |
| sympy_expand              | 278 ms                                                      | 267 ms: 1.04x faster                                                        |
| json_dumps                | 5.83 ms                                                     | 5.60 ms: 1.04x faster                                                       |
| logging_format            | 6.72 us                                                     | 6.46 us: 1.04x faster                                                       |
| hexiom                    | 4.00 ms                                                     | 3.85 ms: 1.04x faster                                                       |
| sqlglot_parse             | 802 us                                                      | 773 us: 1.04x faster                                                        |
| docutils                  | 1.61 sec                                                    | 1.55 sec: 1.04x faster                                                      |
| spectral_norm             | 63.9 ms                                                     | 61.7 ms: 1.03x faster                                                       |
| dulwich_log               | 42.7 ms                                                     | 41.4 ms: 1.03x faster                                                       |
| unpickle_list             | 2.69 us                                                     | 2.61 us: 1.03x faster                                                       |
| chameleon                 | 4.95 ms                                                     | 4.81 ms: 1.03x faster                                                       |
| scimark_monte_carlo       | 43.0 ms                                                     | 41.8 ms: 1.03x faster                                                       |
| logging_simple            | 6.21 us                                                     | 6.04 us: 1.03x faster                                                       |
| asyncio_tcp               | 471 ms                                                      | 459 ms: 1.03x faster                                                        |
| sqlglot_optimize          | 34.0 ms                                                     | 33.2 ms: 1.03x faster                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 992 us: 1.02x faster                                                        |
| xml_etree_generate        | 55.8 ms                                                     | 54.5 ms: 1.02x faster                                                       |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| go                        | 89.0 ms                                                     | 87.3 ms: 1.02x faster                                                       |
| scimark_lu                | 57.5 ms                                                     | 56.4 ms: 1.02x faster                                                       |
| xml_etree_process         | 37.6 ms                                                     | 36.9 ms: 1.02x faster                                                       |
| 2to3                      | 213 ms                                                      | 209 ms: 1.01x faster                                                        |
| async_generators          | 230 ms                                                      | 227 ms: 1.01x faster                                                        |
| pprint_safe_repr          | 508 ms                                                      | 502 ms: 1.01x faster                                                        |
| dask                      | 255 ms                                                      | 252 ms: 1.01x faster                                                        |
| pickle_list               | 2.88 us                                                     | 2.85 us: 1.01x faster                                                       |
| tornado_http              | 87.2 ms                                                     | 86.4 ms: 1.01x faster                                                       |
| scimark_fft               | 181 ms                                                      | 180 ms: 1.01x faster                                                        |
| pyflate                   | 294 ms                                                      | 291 ms: 1.01x faster                                                        |
| pprint_pformat            | 1.04 sec                                                    | 1.03 sec: 1.01x faster                                                      |
| json_loads                | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| deltablue                 | 2.12 ms                                                     | 2.13 ms: 1.00x slower                                                       |
| richards                  | 27.6 ms                                                     | 27.8 ms: 1.01x slower                                                       |
| scimark_sor               | 79.8 ms                                                     | 80.5 ms: 1.01x slower                                                       |
| async_tree_none_tg        | 277 ms                                                      | 280 ms: 1.01x slower                                                        |
| regex_dna                 | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| xml_etree_parse           | 90.5 ms                                                     | 91.8 ms: 1.01x slower                                                       |
| deepcopy_memo             | 23.4 us                                                     | 23.7 us: 1.01x slower                                                       |
| xml_etree_iterparse       | 63.1 ms                                                     | 64.1 ms: 1.02x slower                                                       |
| async_tree_io             | 712 ms                                                      | 723 ms: 1.02x slower                                                        |
| richards_super            | 31.2 ms                                                     | 31.7 ms: 1.02x slower                                                       |
| fannkuch                  | 244 ms                                                      | 248 ms: 1.02x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 755 ms: 1.02x slower                                                        |
| meteor_contest            | 72.1 ms                                                     | 73.7 ms: 1.02x slower                                                       |
| async_tree_memoization    | 333 ms                                                      | 341 ms: 1.02x slower                                                        |
| mdp                       | 1.42 sec                                                    | 1.45 sec: 1.02x slower                                                      |
| tomli_loads               | 1.38 sec                                                    | 1.42 sec: 1.03x slower                                                      |
| python_startup            | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| async_tree_memoization_tg | 345 ms                                                      | 363 ms: 1.05x slower                                                        |
| nbody                     | 68.8 ms                                                     | 73.4 ms: 1.07x slower                                                       |
| pycparser                 | 673 ms                                                      | 728 ms: 1.08x slower                                                        |
| regex_v8                  | 13.5 ms                                                     | 15.0 ms: 1.11x slower                                                       |
| unpack_sequence           | 36.9 ns                                                     | 41.2 ns: 1.12x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 17.8 ms: 1.12x slower                                                       |
| coverage                  | 39.8 ms                                                     | 46.1 ms: 1.16x slower                                                       |
| telco                     | 4.08 ms                                                     | 4.75 ms: 1.16x slower                                                       |
| mypy2                     | 209 ms                                                      | 286 ms: 1.37x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (8): asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, gc_traversal, regex_effbot, scimark_sparse_mat_mult, json, create_gc_cycles, bench_thread_pool
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.65% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
