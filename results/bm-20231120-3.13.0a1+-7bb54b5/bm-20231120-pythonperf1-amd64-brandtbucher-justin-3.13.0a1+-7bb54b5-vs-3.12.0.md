
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.01x faster \*
- HPT reliability: 91.66%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 219 ms: 1.03x slower                                                |
| chameleon      | 4.95 ms                                                     | 4.93 ms: 1.00x faster                                               |
| docutils       | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                              |
| tornado_http   | 87.2 ms                                                     | 97.4 ms: 1.12x slower                                               |
| Geometric mean | (ref)                                                       | 1.03x slower                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|---------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 269 ms: 1.06x faster                                                |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 458 ms: 1.04x faster                                                |
| async_tree_io             | 712 ms                                                      | 725 ms: 1.02x slower                                                |
| async_tree_none_tg        | 277 ms                                                      | 284 ms: 1.03x slower                                                |
| async_tree_memoization    | 333 ms                                                      | 342 ms: 1.03x slower                                                |
| async_tree_io_tg          | 742 ms                                                      | 768 ms: 1.03x slower                                                |
| async_tree_memoization_tg | 345 ms                                                      | 365 ms: 1.06x slower                                                |
| Geometric mean            | (ref)                                                       | 1.01x slower                                                        |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 50.5 ms: 1.08x faster                                               |
| nbody          | 68.8 ms                                                     | 65.2 ms: 1.06x faster                                               |
| pidigits       | 150 ms                                                      | 151 ms: 1.00x slower                                                |
| Geometric mean | (ref)                                                       | 1.04x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 80.2 ms: 1.09x faster                                               |
| regex_dna      | 119 ms                                                      | 116 ms: 1.03x faster                                                |
| regex_effbot   | 1.58 ms                                                     | 1.56 ms: 1.01x faster                                               |
| regex_v8       | 13.5 ms                                                     | 17.9 ms: 1.32x slower                                               |
| Geometric mean | (ref)                                                       | 1.04x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 181 us: 1.08x faster                                                |
| tomli_loads          | 1.38 sec                                                    | 1.29 sec: 1.07x faster                                              |
| pickle               | 7.38 us                                                     | 7.11 us: 1.04x faster                                               |
| json_dumps           | 5.83 ms                                                     | 5.68 ms: 1.03x faster                                               |
| xml_etree_generate   | 55.8 ms                                                     | 54.7 ms: 1.02x faster                                               |
| xml_etree_iterparse  | 63.1 ms                                                     | 62.5 ms: 1.01x faster                                               |
| xml_etree_process    | 37.6 ms                                                     | 37.3 ms: 1.01x faster                                               |
| unpickle             | 8.44 us                                                     | 8.38 us: 1.01x faster                                               |
| unpickle_pure_python | 134 us                                                      | 133 us: 1.01x faster                                                |
| xml_etree_parse      | 90.5 ms                                                     | 91.4 ms: 1.01x slower                                               |
| json_loads           | 13.6 us                                                     | 13.9 us: 1.02x slower                                               |
| pickle_list          | 2.88 us                                                     | 3.07 us: 1.07x slower                                               |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                        |

Benchmark hidden because not significant (2): unpickle_list, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| python_startup_no_site | 15.9 ms                                                     | 18.6 ms: 1.17x slower                                               |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.21 ms: 1.14x faster                                               |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|---------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols  | 96.7 us                                                     | 77.3 us: 1.25x faster                                               |
| comprehensions            | 14.0 us                                                     | 11.3 us: 1.24x faster                                               |
| mako                      | 7.05 ms                                                     | 6.21 ms: 1.14x faster                                               |
| raytrace                  | 192 ms                                                      | 170 ms: 1.13x faster                                                |
| sqlite_synth              | 1.75 us                                                     | 1.55 us: 1.13x faster                                               |
| regex_compile             | 87.2 ms                                                     | 80.2 ms: 1.09x faster                                               |
| float                     | 54.7 ms                                                     | 50.5 ms: 1.08x faster                                               |
| coroutines                | 14.1 ms                                                     | 13.1 ms: 1.08x faster                                               |
| pickle_pure_python        | 195 us                                                      | 181 us: 1.08x faster                                                |
| sympy_str                 | 171 ms                                                      | 159 ms: 1.08x faster                                                |
| sympy_sum                 | 90.1 ms                                                     | 84.1 ms: 1.07x faster                                               |
| logging_silent            | 60.5 ns                                                     | 56.5 ns: 1.07x faster                                               |
| tomli_loads               | 1.38 sec                                                    | 1.29 sec: 1.07x faster                                              |
| generators                | 22.6 ms                                                     | 21.1 ms: 1.07x faster                                               |
| deltablue                 | 2.12 ms                                                     | 1.99 ms: 1.07x faster                                               |
| deepcopy_reduce           | 2.08 us                                                     | 1.95 us: 1.07x faster                                               |
| spectral_norm             | 63.9 ms                                                     | 59.8 ms: 1.07x faster                                               |
| async_tree_none           | 286 ms                                                      | 269 ms: 1.06x faster                                                |
| deepcopy_memo             | 23.4 us                                                     | 22.0 us: 1.06x faster                                               |
| richards_super            | 31.2 ms                                                     | 29.5 ms: 1.06x faster                                               |
| nbody                     | 68.8 ms                                                     | 65.2 ms: 1.06x faster                                               |
| richards                  | 27.6 ms                                                     | 26.2 ms: 1.05x faster                                               |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.39 ms: 1.05x faster                                               |
| sqlglot_parse             | 802 us                                                      | 764 us: 1.05x faster                                                |
| deepcopy                  | 233 us                                                      | 222 us: 1.05x faster                                                |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 458 ms: 1.04x faster                                                |
| pickle                    | 7.38 us                                                     | 7.11 us: 1.04x faster                                               |
| crypto_pyaes              | 46.4 ms                                                     | 44.9 ms: 1.03x faster                                               |
| sympy_expand              | 278 ms                                                      | 269 ms: 1.03x faster                                                |
| dulwich_log               | 42.7 ms                                                     | 41.4 ms: 1.03x faster                                               |
| mdp                       | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                              |
| regex_dna                 | 119 ms                                                      | 116 ms: 1.03x faster                                                |
| nqueens                   | 61.7 ms                                                     | 59.8 ms: 1.03x faster                                               |
| docutils                  | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                              |
| sqlglot_transpile         | 1.02 ms                                                     | 988 us: 1.03x faster                                                |
| json_dumps                | 5.83 ms                                                     | 5.68 ms: 1.03x faster                                               |
| bench_mp_pool             | 67.2 ms                                                     | 65.7 ms: 1.02x faster                                               |
| sqlglot_normalize         | 183 ms                                                      | 179 ms: 1.02x faster                                                |
| xml_etree_generate        | 55.8 ms                                                     | 54.7 ms: 1.02x faster                                               |
| scimark_sor               | 79.8 ms                                                     | 78.3 ms: 1.02x faster                                               |
| logging_format            | 6.72 us                                                     | 6.59 us: 1.02x faster                                               |
| regex_effbot              | 1.58 ms                                                     | 1.56 ms: 1.01x faster                                               |
| fannkuch                  | 244 ms                                                      | 241 ms: 1.01x faster                                                |
| pprint_pformat            | 1.04 sec                                                    | 1.03 sec: 1.01x faster                                              |
| xml_etree_iterparse       | 63.1 ms                                                     | 62.5 ms: 1.01x faster                                               |
| pprint_safe_repr          | 508 ms                                                      | 503 ms: 1.01x faster                                                |
| xml_etree_process         | 37.6 ms                                                     | 37.3 ms: 1.01x faster                                               |
| unpickle                  | 8.44 us                                                     | 8.38 us: 1.01x faster                                               |
| logging_simple            | 6.21 us                                                     | 6.17 us: 1.01x faster                                               |
| unpickle_pure_python      | 134 us                                                      | 133 us: 1.01x faster                                                |
| chaos                     | 42.1 ms                                                     | 41.9 ms: 1.01x faster                                               |
| chameleon                 | 4.95 ms                                                     | 4.93 ms: 1.00x faster                                               |
| pyflate                   | 294 ms                                                      | 293 ms: 1.00x faster                                                |
| sqlglot_optimize          | 34.0 ms                                                     | 34.1 ms: 1.00x slower                                               |
| pidigits                  | 150 ms                                                      | 151 ms: 1.00x slower                                                |
| gc_traversal              | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                               |
| xml_etree_parse           | 90.5 ms                                                     | 91.4 ms: 1.01x slower                                               |
| scimark_lu                | 57.5 ms                                                     | 58.1 ms: 1.01x slower                                               |
| go                        | 89.0 ms                                                     | 90.3 ms: 1.01x slower                                               |
| async_tree_io             | 712 ms                                                      | 725 ms: 1.02x slower                                                |
| json_loads                | 13.6 us                                                     | 13.9 us: 1.02x slower                                               |
| async_generators          | 230 ms                                                      | 235 ms: 1.02x slower                                                |
| async_tree_none_tg        | 277 ms                                                      | 284 ms: 1.03x slower                                                |
| async_tree_memoization    | 333 ms                                                      | 342 ms: 1.03x slower                                                |
| 2to3                      | 213 ms                                                      | 219 ms: 1.03x slower                                                |
| scimark_fft               | 181 ms                                                      | 187 ms: 1.03x slower                                                |
| async_tree_io_tg          | 742 ms                                                      | 768 ms: 1.03x slower                                                |
| bench_thread_pool         | 830 us                                                      | 859 us: 1.03x slower                                                |
| scimark_monte_carlo       | 43.0 ms                                                     | 44.9 ms: 1.04x slower                                               |
| meteor_contest            | 72.1 ms                                                     | 75.4 ms: 1.05x slower                                               |
| async_tree_memoization_tg | 345 ms                                                      | 365 ms: 1.06x slower                                                |
| hexiom                    | 4.00 ms                                                     | 4.24 ms: 1.06x slower                                               |
| dask                      | 255 ms                                                      | 271 ms: 1.06x slower                                                |
| pickle_list               | 2.88 us                                                     | 3.07 us: 1.07x slower                                               |
| unpack_sequence           | 36.9 ns                                                     | 39.6 ns: 1.07x slower                                               |
| python_startup            | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| tornado_http              | 87.2 ms                                                     | 97.4 ms: 1.12x slower                                               |
| coverage                  | 39.8 ms                                                     | 45.2 ms: 1.14x slower                                               |
| asyncio_tcp               | 471 ms                                                      | 539 ms: 1.14x slower                                                |
| telco                     | 4.08 ms                                                     | 4.68 ms: 1.15x slower                                               |
| python_startup_no_site    | 15.9 ms                                                     | 18.6 ms: 1.17x slower                                               |
| regex_v8                  | 13.5 ms                                                     | 17.9 ms: 1.32x slower                                               |
| mypy2                     | 209 ms                                                      | 295 ms: 1.41x slower                                                |
| Geometric mean            | (ref)                                                       | 1.01x faster                                                        |

Benchmark hidden because not significant (9): unpickle_list, asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, pickle_dict, sympy_integrate, pycparser, pathlib, create_gc_cycles, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 91.66% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
