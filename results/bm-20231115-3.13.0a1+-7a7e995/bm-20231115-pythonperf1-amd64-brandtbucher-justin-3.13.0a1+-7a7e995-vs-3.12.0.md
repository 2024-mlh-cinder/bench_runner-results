
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.89%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| chameleon      | 4.95 ms                                                     | 4.74 ms: 1.04x faster                                               |
| docutils       | 1.61 sec                                                    | 1.57 sec: 1.02x faster                                              |
| Geometric mean | (ref)                                                       | 1.02x faster                                                        |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 268 ms: 1.07x faster                                                |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 451 ms: 1.06x faster                                                |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 477 ms: 1.01x faster                                                |
| async_tree_memoization     | 333 ms                                                      | 337 ms: 1.01x slower                                                |
| async_tree_io              | 712 ms                                                      | 724 ms: 1.02x slower                                                |
| async_tree_none_tg         | 277 ms                                                      | 283 ms: 1.02x slower                                                |
| async_tree_io_tg           | 742 ms                                                      | 761 ms: 1.03x slower                                                |
| async_tree_memoization_tg  | 345 ms                                                      | 361 ms: 1.05x slower                                                |
| Geometric mean             | (ref)                                                       | 1.00x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 50.2 ms: 1.09x faster                                               |
| nbody          | 68.8 ms                                                     | 66.6 ms: 1.03x faster                                               |
| Geometric mean | (ref)                                                       | 1.04x faster                                                        |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 79.5 ms: 1.10x faster                                               |
| regex_effbot   | 1.58 ms                                                     | 1.61 ms: 1.02x slower                                               |
| regex_dna      | 119 ms                                                      | 122 ms: 1.02x slower                                                |
| regex_v8       | 13.5 ms                                                     | 15.4 ms: 1.14x slower                                               |
| Geometric mean | (ref)                                                       | 1.02x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads          | 1.38 sec                                                    | 1.27 sec: 1.09x faster                                              |
| pickle_pure_python   | 195 us                                                      | 180 us: 1.08x faster                                                |
| xml_etree_generate   | 55.8 ms                                                     | 53.3 ms: 1.05x faster                                               |
| xml_etree_process    | 37.6 ms                                                     | 36.2 ms: 1.04x faster                                               |
| unpickle_pure_python | 134 us                                                      | 130 us: 1.03x faster                                                |
| unpickle             | 8.44 us                                                     | 8.18 us: 1.03x faster                                               |
| json_dumps           | 5.83 ms                                                     | 5.67 ms: 1.03x faster                                               |
| pickle               | 7.38 us                                                     | 7.22 us: 1.02x faster                                               |
| pickle_dict          | 18.9 us                                                     | 18.6 us: 1.02x faster                                               |
| xml_etree_iterparse  | 63.1 ms                                                     | 62.1 ms: 1.02x faster                                               |
| xml_etree_parse      | 90.5 ms                                                     | 91.8 ms: 1.01x slower                                               |
| json_loads           | 13.6 us                                                     | 13.9 us: 1.02x slower                                               |
| pickle_list          | 2.88 us                                                     | 3.32 us: 1.15x slower                                               |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                        |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.4 ms: 1.08x slower                                               |
| python_startup_no_site | 15.9 ms                                                     | 18.2 ms: 1.14x slower                                               |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.21 ms: 1.14x faster                                               |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 96.7 us                                                     | 75.2 us: 1.29x faster                                               |
| comprehensions             | 14.0 us                                                     | 11.0 us: 1.28x faster                                               |
| mako                       | 7.05 ms                                                     | 6.21 ms: 1.14x faster                                               |
| sqlite_synth               | 1.75 us                                                     | 1.55 us: 1.13x faster                                               |
| raytrace                   | 192 ms                                                      | 173 ms: 1.11x faster                                                |
| regex_compile              | 87.2 ms                                                     | 79.5 ms: 1.10x faster                                               |
| spectral_norm              | 63.9 ms                                                     | 58.3 ms: 1.10x faster                                               |
| float                      | 54.7 ms                                                     | 50.2 ms: 1.09x faster                                               |
| sympy_str                  | 171 ms                                                      | 158 ms: 1.09x faster                                                |
| sympy_sum                  | 90.1 ms                                                     | 82.9 ms: 1.09x faster                                               |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.31 ms: 1.09x faster                                               |
| tomli_loads                | 1.38 sec                                                    | 1.27 sec: 1.09x faster                                              |
| generators                 | 22.6 ms                                                     | 20.8 ms: 1.08x faster                                               |
| coroutines                 | 14.1 ms                                                     | 13.0 ms: 1.08x faster                                               |
| logging_silent             | 60.5 ns                                                     | 55.9 ns: 1.08x faster                                               |
| deepcopy_memo              | 23.4 us                                                     | 21.6 us: 1.08x faster                                               |
| pickle_pure_python         | 195 us                                                      | 180 us: 1.08x faster                                                |
| deepcopy_reduce            | 2.08 us                                                     | 1.94 us: 1.07x faster                                               |
| richards_super             | 31.2 ms                                                     | 29.1 ms: 1.07x faster                                               |
| deltablue                  | 2.12 ms                                                     | 1.98 ms: 1.07x faster                                               |
| deepcopy                   | 233 us                                                      | 218 us: 1.07x faster                                                |
| async_tree_none            | 286 ms                                                      | 268 ms: 1.07x faster                                                |
| richards                   | 27.6 ms                                                     | 25.9 ms: 1.06x faster                                               |
| sqlglot_parse              | 802 us                                                      | 754 us: 1.06x faster                                                |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 451 ms: 1.06x faster                                                |
| pathlib                    | 79.6 ms                                                     | 75.4 ms: 1.06x faster                                               |
| scimark_lu                 | 57.5 ms                                                     | 54.4 ms: 1.06x faster                                               |
| sqlglot_transpile          | 1.02 ms                                                     | 967 us: 1.05x faster                                                |
| dulwich_log                | 42.7 ms                                                     | 40.7 ms: 1.05x faster                                               |
| xml_etree_generate         | 55.8 ms                                                     | 53.3 ms: 1.05x faster                                               |
| bench_mp_pool              | 67.2 ms                                                     | 64.4 ms: 1.04x faster                                               |
| chameleon                  | 4.95 ms                                                     | 4.74 ms: 1.04x faster                                               |
| xml_etree_process          | 37.6 ms                                                     | 36.2 ms: 1.04x faster                                               |
| sympy_expand               | 278 ms                                                      | 268 ms: 1.04x faster                                                |
| sqlglot_normalize          | 183 ms                                                      | 177 ms: 1.04x faster                                                |
| nqueens                    | 61.7 ms                                                     | 59.5 ms: 1.04x faster                                               |
| chaos                      | 42.1 ms                                                     | 40.7 ms: 1.03x faster                                               |
| nbody                      | 68.8 ms                                                     | 66.6 ms: 1.03x faster                                               |
| unpickle_pure_python       | 134 us                                                      | 130 us: 1.03x faster                                                |
| unpickle                   | 8.44 us                                                     | 8.18 us: 1.03x faster                                               |
| json_dumps                 | 5.83 ms                                                     | 5.67 ms: 1.03x faster                                               |
| docutils                   | 1.61 sec                                                    | 1.57 sec: 1.02x faster                                              |
| fannkuch                   | 244 ms                                                      | 239 ms: 1.02x faster                                                |
| sympy_integrate            | 13.0 ms                                                     | 12.7 ms: 1.02x faster                                               |
| pickle                     | 7.38 us                                                     | 7.22 us: 1.02x faster                                               |
| pickle_dict                | 18.9 us                                                     | 18.6 us: 1.02x faster                                               |
| logging_format             | 6.72 us                                                     | 6.58 us: 1.02x faster                                               |
| sqlglot_optimize           | 34.0 ms                                                     | 33.3 ms: 1.02x faster                                               |
| scimark_sor                | 79.8 ms                                                     | 78.3 ms: 1.02x faster                                               |
| xml_etree_iterparse        | 63.1 ms                                                     | 62.1 ms: 1.02x faster                                               |
| pprint_safe_repr           | 508 ms                                                      | 500 ms: 1.02x faster                                                |
| pprint_pformat             | 1.04 sec                                                    | 1.02 sec: 1.02x faster                                              |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 477 ms: 1.01x faster                                                |
| logging_simple             | 6.21 us                                                     | 6.13 us: 1.01x faster                                               |
| scimark_fft                | 181 ms                                                      | 179 ms: 1.01x faster                                                |
| crypto_pyaes               | 46.4 ms                                                     | 46.1 ms: 1.01x faster                                               |
| pyflate                    | 294 ms                                                      | 293 ms: 1.00x faster                                                |
| bench_thread_pool          | 830 us                                                      | 839 us: 1.01x slower                                                |
| async_tree_memoization     | 333 ms                                                      | 337 ms: 1.01x slower                                                |
| xml_etree_parse            | 90.5 ms                                                     | 91.8 ms: 1.01x slower                                               |
| regex_effbot               | 1.58 ms                                                     | 1.61 ms: 1.02x slower                                               |
| async_tree_io              | 712 ms                                                      | 724 ms: 1.02x slower                                                |
| regex_dna                  | 119 ms                                                      | 122 ms: 1.02x slower                                                |
| mdp                        | 1.42 sec                                                    | 1.45 sec: 1.02x slower                                              |
| json_loads                 | 13.6 us                                                     | 13.9 us: 1.02x slower                                               |
| async_tree_none_tg         | 277 ms                                                      | 283 ms: 1.02x slower                                                |
| async_tree_io_tg           | 742 ms                                                      | 761 ms: 1.03x slower                                                |
| pycparser                  | 673 ms                                                      | 694 ms: 1.03x slower                                                |
| scimark_monte_carlo        | 43.0 ms                                                     | 44.4 ms: 1.03x slower                                               |
| meteor_contest             | 72.1 ms                                                     | 74.7 ms: 1.04x slower                                               |
| hexiom                     | 4.00 ms                                                     | 4.15 ms: 1.04x slower                                               |
| async_tree_memoization_tg  | 345 ms                                                      | 361 ms: 1.05x slower                                                |
| python_startup             | 18.8 ms                                                     | 20.4 ms: 1.08x slower                                               |
| unpack_sequence            | 36.9 ns                                                     | 40.4 ns: 1.09x slower                                               |
| coverage                   | 39.8 ms                                                     | 44.3 ms: 1.11x slower                                               |
| telco                      | 4.08 ms                                                     | 4.59 ms: 1.12x slower                                               |
| regex_v8                   | 13.5 ms                                                     | 15.4 ms: 1.14x slower                                               |
| python_startup_no_site     | 15.9 ms                                                     | 18.2 ms: 1.14x slower                                               |
| pickle_list                | 2.88 us                                                     | 3.32 us: 1.15x slower                                               |
| mypy2                      | 209 ms                                                      | 289 ms: 1.38x slower                                                |
| Geometric mean             | (ref)                                                       | 1.02x faster                                                        |

Benchmark hidden because not significant (12): asyncio_tcp_ssl, unpickle_list, tornado_http, asyncio_tcp, go, dask, pidigits, 2to3, async_generators, create_gc_cycles, gc_traversal, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.89% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
