
# Results vs. 3.12.0

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: windows-amd64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 226 ms: 1.06x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.10 ms: 1.03x slower                                                       |
| tornado_http   | 87.2 ms                                                     | 90.3 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 477 ms                                                      | 466 ms: 1.02x faster                                                        |
| async_tree_none            | 286 ms                                                      | 280 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 494 ms: 1.02x slower                                                        |
| async_tree_io              | 712 ms                                                      | 746 ms: 1.05x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 778 ms: 1.05x slower                                                        |
| async_tree_none_tg         | 277 ms                                                      | 293 ms: 1.06x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 354 ms: 1.06x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 376 ms: 1.09x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.04x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| float          | 54.7 ms                                                     | 62.2 ms: 1.14x slower                                                       |
| nbody          | 68.8 ms                                                     | 85.7 ms: 1.25x slower                                                       |
| Geometric mean | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| regex_dna      | 119 ms                                                      | 120 ms: 1.01x slower                                                        |
| regex_compile  | 87.2 ms                                                     | 94.4 ms: 1.08x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 18.9 ms: 1.40x slower                                                       |
| Geometric mean | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.87 us: 1.07x faster                                                       |
| pickle_pure_python   | 195 us                                                      | 187 us: 1.04x faster                                                        |
| pickle_dict          | 18.9 us                                                     | 18.4 us: 1.03x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.62 us: 1.03x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.76 ms: 1.01x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 55.4 ms: 1.01x faster                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 91.3 ms: 1.01x slower                                                       |
| xml_etree_process    | 37.6 ms                                                     | 38.4 ms: 1.02x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 65.4 ms: 1.04x slower                                                       |
| pickle_list          | 2.88 us                                                     | 3.12 us: 1.08x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 147 us: 1.09x slower                                                        |
| tomli_loads          | 1.38 sec                                                    | 1.53 sec: 1.11x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.1 ms: 1.07x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.5 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 8.46 ms: 1.20x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 96.7 us                                                     | 82.7 us: 1.17x faster                                                       |
| sqlite_synth               | 1.75 us                                                     | 1.60 us: 1.09x faster                                                       |
| asyncio_tcp_ssl            | 1.89 sec                                                    | 1.76 sec: 1.07x faster                                                      |
| pickle                     | 7.38 us                                                     | 6.87 us: 1.07x faster                                                       |
| pathlib                    | 79.6 ms                                                     | 75.4 ms: 1.06x faster                                                       |
| deepcopy_reduce            | 2.08 us                                                     | 1.99 us: 1.05x faster                                                       |
| pickle_pure_python         | 195 us                                                      | 187 us: 1.04x faster                                                        |
| sympy_sum                  | 90.1 ms                                                     | 86.7 ms: 1.04x faster                                                       |
| generators                 | 22.6 ms                                                     | 21.7 ms: 1.04x faster                                                       |
| logging_silent             | 60.5 ns                                                     | 58.4 ns: 1.04x faster                                                       |
| pickle_dict                | 18.9 us                                                     | 18.4 us: 1.03x faster                                                       |
| deepcopy                   | 233 us                                                      | 226 us: 1.03x faster                                                        |
| raytrace                   | 192 ms                                                      | 187 ms: 1.03x faster                                                        |
| unpickle_list              | 2.69 us                                                     | 2.62 us: 1.03x faster                                                       |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 466 ms: 1.02x faster                                                        |
| async_tree_none            | 286 ms                                                      | 280 ms: 1.02x faster                                                        |
| pidigits                   | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| sympy_str                  | 171 ms                                                      | 169 ms: 1.01x faster                                                        |
| coroutines                 | 14.1 ms                                                     | 13.9 ms: 1.01x faster                                                       |
| json_dumps                 | 5.83 ms                                                     | 5.76 ms: 1.01x faster                                                       |
| sqlglot_normalize          | 183 ms                                                      | 181 ms: 1.01x faster                                                        |
| json_loads                 | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| spectral_norm              | 63.9 ms                                                     | 63.3 ms: 1.01x faster                                                       |
| bench_mp_pool              | 67.2 ms                                                     | 66.7 ms: 1.01x faster                                                       |
| xml_etree_generate         | 55.8 ms                                                     | 55.4 ms: 1.01x faster                                                       |
| dulwich_log                | 42.7 ms                                                     | 42.8 ms: 1.00x slower                                                       |
| regex_effbot               | 1.58 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| sqlglot_optimize           | 34.0 ms                                                     | 34.3 ms: 1.01x slower                                                       |
| richards_super             | 31.2 ms                                                     | 31.4 ms: 1.01x slower                                                       |
| regex_dna                  | 119 ms                                                      | 120 ms: 1.01x slower                                                        |
| xml_etree_parse            | 90.5 ms                                                     | 91.3 ms: 1.01x slower                                                       |
| gc_traversal               | 1.49 ms                                                     | 1.51 ms: 1.01x slower                                                       |
| dask                       | 255 ms                                                      | 258 ms: 1.01x slower                                                        |
| sqlglot_transpile          | 1.02 ms                                                     | 1.03 ms: 1.01x slower                                                       |
| logging_format             | 6.72 us                                                     | 6.83 us: 1.02x slower                                                       |
| xml_etree_process          | 37.6 ms                                                     | 38.4 ms: 1.02x slower                                                       |
| richards                   | 27.6 ms                                                     | 28.2 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 494 ms: 1.02x slower                                                        |
| async_generators           | 230 ms                                                      | 236 ms: 1.02x slower                                                        |
| chameleon                  | 4.95 ms                                                     | 5.10 ms: 1.03x slower                                                       |
| pycparser                  | 673 ms                                                      | 696 ms: 1.03x slower                                                        |
| sympy_expand               | 278 ms                                                      | 288 ms: 1.03x slower                                                        |
| xml_etree_iterparse        | 63.1 ms                                                     | 65.4 ms: 1.04x slower                                                       |
| tornado_http               | 87.2 ms                                                     | 90.3 ms: 1.04x slower                                                       |
| sympy_integrate            | 13.0 ms                                                     | 13.5 ms: 1.04x slower                                                       |
| bench_thread_pool          | 830 us                                                      | 869 us: 1.05x slower                                                        |
| async_tree_io              | 712 ms                                                      | 746 ms: 1.05x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 778 ms: 1.05x slower                                                        |
| logging_simple             | 6.21 us                                                     | 6.50 us: 1.05x slower                                                       |
| deepcopy_memo              | 23.4 us                                                     | 24.6 us: 1.05x slower                                                       |
| async_tree_none_tg         | 277 ms                                                      | 293 ms: 1.06x slower                                                        |
| scimark_lu                 | 57.5 ms                                                     | 60.9 ms: 1.06x slower                                                       |
| unpack_sequence            | 36.9 ns                                                     | 39.1 ns: 1.06x slower                                                       |
| 2to3                       | 213 ms                                                      | 226 ms: 1.06x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 354 ms: 1.06x slower                                                        |
| scimark_sor                | 79.8 ms                                                     | 85.0 ms: 1.07x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.1 ms: 1.07x slower                                                       |
| mdp                        | 1.42 sec                                                    | 1.52 sec: 1.07x slower                                                      |
| comprehensions             | 14.0 us                                                     | 15.0 us: 1.07x slower                                                       |
| pprint_safe_repr           | 508 ms                                                      | 545 ms: 1.07x slower                                                        |
| regex_compile              | 87.2 ms                                                     | 94.4 ms: 1.08x slower                                                       |
| pickle_list                | 2.88 us                                                     | 3.12 us: 1.08x slower                                                       |
| pprint_pformat             | 1.04 sec                                                    | 1.13 sec: 1.09x slower                                                      |
| async_tree_memoization_tg  | 345 ms                                                      | 376 ms: 1.09x slower                                                        |
| unpickle_pure_python       | 134 us                                                      | 147 us: 1.09x slower                                                        |
| meteor_contest             | 72.1 ms                                                     | 79.0 ms: 1.10x slower                                                       |
| crypto_pyaes               | 46.4 ms                                                     | 51.6 ms: 1.11x slower                                                       |
| tomli_loads                | 1.38 sec                                                    | 1.53 sec: 1.11x slower                                                      |
| coverage                   | 39.8 ms                                                     | 44.6 ms: 1.12x slower                                                       |
| go                         | 89.0 ms                                                     | 99.8 ms: 1.12x slower                                                       |
| nqueens                    | 61.7 ms                                                     | 69.7 ms: 1.13x slower                                                       |
| chaos                      | 42.1 ms                                                     | 47.7 ms: 1.13x slower                                                       |
| float                      | 54.7 ms                                                     | 62.2 ms: 1.14x slower                                                       |
| pyflate                    | 294 ms                                                      | 336 ms: 1.14x slower                                                        |
| python_startup_no_site     | 15.9 ms                                                     | 18.5 ms: 1.16x slower                                                       |
| fannkuch                   | 244 ms                                                      | 284 ms: 1.16x slower                                                        |
| scimark_monte_carlo        | 43.0 ms                                                     | 50.3 ms: 1.17x slower                                                       |
| mako                       | 7.05 ms                                                     | 8.46 ms: 1.20x slower                                                       |
| telco                      | 4.08 ms                                                     | 4.94 ms: 1.21x slower                                                       |
| nbody                      | 68.8 ms                                                     | 85.7 ms: 1.25x slower                                                       |
| scimark_fft                | 181 ms                                                      | 228 ms: 1.26x slower                                                        |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 3.47 ms: 1.38x slower                                                       |
| deltablue                  | 2.12 ms                                                     | 2.96 ms: 1.39x slower                                                       |
| regex_v8                   | 13.5 ms                                                     | 18.9 ms: 1.40x slower                                                       |
| hexiom                     | 4.00 ms                                                     | 5.63 ms: 1.41x slower                                                       |
| mypy2                      | 209 ms                                                      | 294 ms: 1.41x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (6): docutils, unpickle, sqlglot_parse, asyncio_tcp, create_gc_cycles, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
