
# Results vs. 3.12.0

- fork: python
- ref: ce6a533c4bf1afa3775d
- machine: windows-amd64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 223 ms: 1.05x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.00 ms: 1.01x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.60 sec: 1.01x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 90.0 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed   | 477 ms                                                      | 458 ms: 1.04x faster                                                        |
| async_tree_none           | 286 ms                                                      | 275 ms: 1.04x faster                                                        |
| async_tree_io_tg          | 742 ms                                                      | 776 ms: 1.05x slower                                                        |
| async_tree_io             | 712 ms                                                      | 745 ms: 1.05x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 291 ms: 1.05x slower                                                        |
| async_tree_memoization    | 333 ms                                                      | 353 ms: 1.06x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 372 ms: 1.08x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| float          | 54.7 ms                                                     | 61.9 ms: 1.13x slower                                                       |
| nbody          | 68.8 ms                                                     | 85.1 ms: 1.24x slower                                                       |
| Geometric mean | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.62 ms: 1.02x slower                                                       |
| regex_dna      | 119 ms                                                      | 123 ms: 1.03x slower                                                        |
| regex_compile  | 87.2 ms                                                     | 93.6 ms: 1.07x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 15.7 ms: 1.16x slower                                                       |
| Geometric mean | (ref)                                                       | 1.07x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 181 us: 1.08x faster                                                        |
| pickle               | 7.38 us                                                     | 7.03 us: 1.05x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.4 us: 1.03x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.68 ms: 1.03x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.4 ms: 1.02x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.25 us: 1.02x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.3 us: 1.02x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.0 ms: 1.02x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.87 us: 1.01x faster                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 95.9 ms: 1.06x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 144 us: 1.07x slower                                                        |
| xml_etree_iterparse  | 63.1 ms                                                     | 69.0 ms: 1.09x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.72 sec: 1.25x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.9 ms: 1.12x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 8.46 ms: 1.20x slower                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols  | 96.7 us                                                     | 78.2 us: 1.24x faster                                                       |
| sqlite_synth              | 1.75 us                                                     | 1.58 us: 1.11x faster                                                       |
| raytrace                  | 192 ms                                                      | 176 ms: 1.09x faster                                                        |
| spectral_norm             | 63.9 ms                                                     | 58.5 ms: 1.09x faster                                                       |
| generators                | 22.6 ms                                                     | 20.8 ms: 1.09x faster                                                       |
| pickle_pure_python        | 195 us                                                      | 181 us: 1.08x faster                                                        |
| bench_mp_pool             | 67.2 ms                                                     | 63.3 ms: 1.06x faster                                                       |
| logging_silent            | 60.5 ns                                                     | 57.4 ns: 1.05x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 85.5 ms: 1.05x faster                                                       |
| deepcopy_reduce           | 2.08 us                                                     | 1.98 us: 1.05x faster                                                       |
| coroutines                | 14.1 ms                                                     | 13.4 ms: 1.05x faster                                                       |
| pickle                    | 7.38 us                                                     | 7.03 us: 1.05x faster                                                       |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 458 ms: 1.04x faster                                                        |
| async_tree_none           | 286 ms                                                      | 275 ms: 1.04x faster                                                        |
| deepcopy                  | 233 us                                                      | 224 us: 1.04x faster                                                        |
| pickle_dict               | 18.9 us                                                     | 18.4 us: 1.03x faster                                                       |
| sqlglot_normalize         | 183 ms                                                      | 178 ms: 1.03x faster                                                        |
| json_dumps                | 5.83 ms                                                     | 5.68 ms: 1.03x faster                                                       |
| xml_etree_generate        | 55.8 ms                                                     | 54.4 ms: 1.02x faster                                                       |
| unpickle                  | 8.44 us                                                     | 8.25 us: 1.02x faster                                                       |
| json_loads                | 13.6 us                                                     | 13.3 us: 1.02x faster                                                       |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| sympy_str                 | 171 ms                                                      | 168 ms: 1.02x faster                                                        |
| sqlglot_parse             | 802 us                                                      | 788 us: 1.02x faster                                                        |
| xml_etree_process         | 37.6 ms                                                     | 37.0 ms: 1.02x faster                                                       |
| sqlglot_optimize          | 34.0 ms                                                     | 33.7 ms: 1.01x faster                                                       |
| sqlglot_transpile         | 1.02 ms                                                     | 1.01 ms: 1.01x faster                                                       |
| pickle_list               | 2.88 us                                                     | 2.87 us: 1.01x faster                                                       |
| docutils                  | 1.61 sec                                                    | 1.60 sec: 1.01x faster                                                      |
| scimark_sor               | 79.8 ms                                                     | 80.2 ms: 1.01x slower                                                       |
| dulwich_log               | 42.7 ms                                                     | 42.9 ms: 1.01x slower                                                       |
| scimark_lu                | 57.5 ms                                                     | 57.9 ms: 1.01x slower                                                       |
| chameleon                 | 4.95 ms                                                     | 5.00 ms: 1.01x slower                                                       |
| gc_traversal              | 1.49 ms                                                     | 1.51 ms: 1.01x slower                                                       |
| create_gc_cycles          | 726 us                                                      | 737 us: 1.02x slower                                                        |
| richards_super            | 31.2 ms                                                     | 31.9 ms: 1.02x slower                                                       |
| regex_effbot              | 1.58 ms                                                     | 1.62 ms: 1.02x slower                                                       |
| bench_thread_pool         | 830 us                                                      | 850 us: 1.02x slower                                                        |
| sympy_expand              | 278 ms                                                      | 286 ms: 1.03x slower                                                        |
| deepcopy_memo             | 23.4 us                                                     | 24.1 us: 1.03x slower                                                       |
| regex_dna                 | 119 ms                                                      | 123 ms: 1.03x slower                                                        |
| async_generators          | 230 ms                                                      | 237 ms: 1.03x slower                                                        |
| tornado_http              | 87.2 ms                                                     | 90.0 ms: 1.03x slower                                                       |
| richards                  | 27.6 ms                                                     | 28.5 ms: 1.03x slower                                                       |
| logging_format            | 6.72 us                                                     | 6.98 us: 1.04x slower                                                       |
| python_startup            | 18.8 ms                                                     | 19.6 ms: 1.04x slower                                                       |
| sympy_integrate           | 13.0 ms                                                     | 13.5 ms: 1.04x slower                                                       |
| async_tree_io_tg          | 742 ms                                                      | 776 ms: 1.05x slower                                                        |
| async_tree_io             | 712 ms                                                      | 745 ms: 1.05x slower                                                        |
| async_tree_none_tg        | 277 ms                                                      | 291 ms: 1.05x slower                                                        |
| logging_simple            | 6.21 us                                                     | 6.53 us: 1.05x slower                                                       |
| 2to3                      | 213 ms                                                      | 223 ms: 1.05x slower                                                        |
| mdp                       | 1.42 sec                                                    | 1.50 sec: 1.05x slower                                                      |
| async_tree_memoization    | 333 ms                                                      | 353 ms: 1.06x slower                                                        |
| xml_etree_parse           | 90.5 ms                                                     | 95.9 ms: 1.06x slower                                                       |
| pprint_safe_repr          | 508 ms                                                      | 543 ms: 1.07x slower                                                        |
| unpickle_pure_python      | 134 us                                                      | 144 us: 1.07x slower                                                        |
| regex_compile             | 87.2 ms                                                     | 93.6 ms: 1.07x slower                                                       |
| chaos                     | 42.1 ms                                                     | 45.3 ms: 1.08x slower                                                       |
| pprint_pformat            | 1.04 sec                                                    | 1.12 sec: 1.08x slower                                                      |
| async_tree_memoization_tg | 345 ms                                                      | 372 ms: 1.08x slower                                                        |
| unpack_sequence           | 36.9 ns                                                     | 40.1 ns: 1.09x slower                                                       |
| crypto_pyaes              | 46.4 ms                                                     | 50.6 ms: 1.09x slower                                                       |
| xml_etree_iterparse       | 63.1 ms                                                     | 69.0 ms: 1.09x slower                                                       |
| meteor_contest            | 72.1 ms                                                     | 79.5 ms: 1.10x slower                                                       |
| scimark_monte_carlo       | 43.0 ms                                                     | 48.0 ms: 1.12x slower                                                       |
| go                        | 89.0 ms                                                     | 99.8 ms: 1.12x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 17.9 ms: 1.12x slower                                                       |
| float                     | 54.7 ms                                                     | 61.9 ms: 1.13x slower                                                       |
| comprehensions            | 14.0 us                                                     | 16.0 us: 1.15x slower                                                       |
| pycparser                 | 673 ms                                                      | 776 ms: 1.15x slower                                                        |
| regex_v8                  | 13.5 ms                                                     | 15.7 ms: 1.16x slower                                                       |
| pyflate                   | 294 ms                                                      | 344 ms: 1.17x slower                                                        |
| nqueens                   | 61.7 ms                                                     | 72.6 ms: 1.18x slower                                                       |
| telco                     | 4.08 ms                                                     | 4.82 ms: 1.18x slower                                                       |
| coverage                  | 39.8 ms                                                     | 47.0 ms: 1.18x slower                                                       |
| mako                      | 7.05 ms                                                     | 8.46 ms: 1.20x slower                                                       |
| scimark_fft               | 181 ms                                                      | 217 ms: 1.20x slower                                                        |
| nbody                     | 68.8 ms                                                     | 85.1 ms: 1.24x slower                                                       |
| tomli_loads               | 1.38 sec                                                    | 1.72 sec: 1.25x slower                                                      |
| fannkuch                  | 244 ms                                                      | 307 ms: 1.26x slower                                                        |
| mypy2                     | 209 ms                                                      | 295 ms: 1.41x slower                                                        |
| deltablue                 | 2.12 ms                                                     | 3.00 ms: 1.42x slower                                                       |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 3.64 ms: 1.45x slower                                                       |
| hexiom                    | 4.00 ms                                                     | 6.15 ms: 1.54x slower                                                       |
| Geometric mean            | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (6): json, pathlib, unpickle_list, async_tree_cpu_io_mixed_tg, asyncio_tcp_ssl, asyncio_tcp
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
