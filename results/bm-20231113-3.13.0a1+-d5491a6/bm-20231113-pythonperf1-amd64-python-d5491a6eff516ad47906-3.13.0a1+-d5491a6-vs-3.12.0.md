
# Results vs. 3.12.0

- fork: python
- ref: d5491a6eff516ad47906
- machine: windows-amd64
- commit hash: d5491a6
- commit date: 2023-11-13
- overall geometric mean: 1.01x faster \*
- HPT reliability: 99.91%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 210 ms: 1.01x faster                                                        |
| chameleon      | 4.95 ms                                                     | 4.82 ms: 1.03x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.54 sec: 1.05x faster                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 265 ms: 1.08x faster                                                        |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 449 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 474 ms: 1.02x faster                                                        |
| async_tree_io              | 712 ms                                                      | 722 ms: 1.01x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 340 ms: 1.02x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 761 ms: 1.03x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 360 ms: 1.04x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 53.0 ms: 1.03x faster                                                       |
| pidigits       | 150 ms                                                      | 146 ms: 1.03x faster                                                        |
| nbody          | 68.8 ms                                                     | 73.8 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 79.4 ms: 1.10x faster                                                       |
| regex_dna      | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 15.1 ms: 1.12x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 180 us: 1.08x faster                                                        |
| unpickle_pure_python | 134 us                                                      | 127 us: 1.05x faster                                                        |
| unpickle             | 8.44 us                                                     | 8.13 us: 1.04x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.61 us: 1.03x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.1 ms: 1.03x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.66 ms: 1.03x faster                                                       |
| pickle               | 7.38 us                                                     | 7.21 us: 1.02x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 36.9 ms: 1.02x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 19.4 us: 1.02x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.45 sec: 1.05x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (4): xml_etree_iterparse, json_loads, xml_etree_parse, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.9 ms: 1.12x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.49 ms: 1.09x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions             | 14.0 us                                                     | 10.8 us: 1.30x faster                                                       |
| typing_runtime_protocols   | 96.7 us                                                     | 74.5 us: 1.30x faster                                                       |
| raytrace                   | 192 ms                                                      | 166 ms: 1.16x faster                                                        |
| sqlite_synth               | 1.75 us                                                     | 1.58 us: 1.11x faster                                                       |
| regex_compile              | 87.2 ms                                                     | 79.4 ms: 1.10x faster                                                       |
| mako                       | 7.05 ms                                                     | 6.49 ms: 1.09x faster                                                       |
| logging_silent             | 60.5 ns                                                     | 55.9 ns: 1.08x faster                                                       |
| pickle_pure_python         | 195 us                                                      | 180 us: 1.08x faster                                                        |
| async_tree_none            | 286 ms                                                      | 265 ms: 1.08x faster                                                        |
| generators                 | 22.6 ms                                                     | 20.9 ms: 1.08x faster                                                       |
| sympy_sum                  | 90.1 ms                                                     | 83.5 ms: 1.08x faster                                                       |
| sympy_str                  | 171 ms                                                      | 159 ms: 1.08x faster                                                        |
| bench_mp_pool              | 67.2 ms                                                     | 62.7 ms: 1.07x faster                                                       |
| deepcopy_reduce            | 2.08 us                                                     | 1.95 us: 1.07x faster                                                       |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 449 ms: 1.06x faster                                                        |
| deepcopy                   | 233 us                                                      | 219 us: 1.06x faster                                                        |
| unpickle_pure_python       | 134 us                                                      | 127 us: 1.05x faster                                                        |
| asyncio_tcp_ssl            | 1.89 sec                                                    | 1.79 sec: 1.05x faster                                                      |
| nqueens                    | 61.7 ms                                                     | 58.6 ms: 1.05x faster                                                       |
| dulwich_log                | 42.7 ms                                                     | 40.6 ms: 1.05x faster                                                       |
| chaos                      | 42.1 ms                                                     | 40.1 ms: 1.05x faster                                                       |
| crypto_pyaes               | 46.4 ms                                                     | 44.3 ms: 1.05x faster                                                       |
| sqlglot_parse              | 802 us                                                      | 766 us: 1.05x faster                                                        |
| sympy_integrate            | 13.0 ms                                                     | 12.4 ms: 1.05x faster                                                       |
| docutils                   | 1.61 sec                                                    | 1.54 sec: 1.05x faster                                                      |
| sqlglot_normalize          | 183 ms                                                      | 176 ms: 1.04x faster                                                        |
| hexiom                     | 4.00 ms                                                     | 3.85 ms: 1.04x faster                                                       |
| deltablue                  | 2.12 ms                                                     | 2.04 ms: 1.04x faster                                                       |
| coroutines                 | 14.1 ms                                                     | 13.6 ms: 1.04x faster                                                       |
| unpickle                   | 8.44 us                                                     | 8.13 us: 1.04x faster                                                       |
| sqlglot_transpile          | 1.02 ms                                                     | 981 us: 1.04x faster                                                        |
| go                         | 89.0 ms                                                     | 86.0 ms: 1.04x faster                                                       |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.43 ms: 1.03x faster                                                       |
| float                      | 54.7 ms                                                     | 53.0 ms: 1.03x faster                                                       |
| unpickle_list              | 2.69 us                                                     | 2.61 us: 1.03x faster                                                       |
| xml_etree_generate         | 55.8 ms                                                     | 54.1 ms: 1.03x faster                                                       |
| json_dumps                 | 5.83 ms                                                     | 5.66 ms: 1.03x faster                                                       |
| spectral_norm              | 63.9 ms                                                     | 62.0 ms: 1.03x faster                                                       |
| chameleon                  | 4.95 ms                                                     | 4.82 ms: 1.03x faster                                                       |
| pidigits                   | 150 ms                                                      | 146 ms: 1.03x faster                                                        |
| pprint_pformat             | 1.04 sec                                                    | 1.01 sec: 1.02x faster                                                      |
| pprint_safe_repr           | 508 ms                                                      | 496 ms: 1.02x faster                                                        |
| pickle                     | 7.38 us                                                     | 7.21 us: 1.02x faster                                                       |
| sympy_expand               | 278 ms                                                      | 272 ms: 1.02x faster                                                        |
| xml_etree_process          | 37.6 ms                                                     | 36.9 ms: 1.02x faster                                                       |
| richards_super             | 31.2 ms                                                     | 30.6 ms: 1.02x faster                                                       |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 474 ms: 1.02x faster                                                        |
| logging_format             | 6.72 us                                                     | 6.62 us: 1.02x faster                                                       |
| sqlglot_optimize           | 34.0 ms                                                     | 33.6 ms: 1.01x faster                                                       |
| pathlib                    | 79.6 ms                                                     | 78.6 ms: 1.01x faster                                                       |
| 2to3                       | 213 ms                                                      | 210 ms: 1.01x faster                                                        |
| async_generators           | 230 ms                                                      | 228 ms: 1.01x faster                                                        |
| pyflate                    | 294 ms                                                      | 291 ms: 1.01x faster                                                        |
| scimark_lu                 | 57.5 ms                                                     | 57.1 ms: 1.01x faster                                                       |
| scimark_monte_carlo        | 43.0 ms                                                     | 42.8 ms: 1.01x faster                                                       |
| gc_traversal               | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                                       |
| mdp                        | 1.42 sec                                                    | 1.44 sec: 1.01x slower                                                      |
| scimark_sor                | 79.8 ms                                                     | 80.7 ms: 1.01x slower                                                       |
| regex_dna                  | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| async_tree_io              | 712 ms                                                      | 722 ms: 1.01x slower                                                        |
| fannkuch                   | 244 ms                                                      | 248 ms: 1.01x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 340 ms: 1.02x slower                                                        |
| pickle_dict                | 18.9 us                                                     | 19.4 us: 1.02x slower                                                       |
| async_tree_io_tg           | 742 ms                                                      | 761 ms: 1.03x slower                                                        |
| meteor_contest             | 72.1 ms                                                     | 74.4 ms: 1.03x slower                                                       |
| async_tree_memoization_tg  | 345 ms                                                      | 360 ms: 1.04x slower                                                        |
| python_startup             | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                                       |
| json                       | 2.94 ms                                                     | 3.09 ms: 1.05x slower                                                       |
| tomli_loads                | 1.38 sec                                                    | 1.45 sec: 1.05x slower                                                      |
| nbody                      | 68.8 ms                                                     | 73.8 ms: 1.07x slower                                                       |
| regex_v8                   | 13.5 ms                                                     | 15.1 ms: 1.12x slower                                                       |
| python_startup_no_site     | 15.9 ms                                                     | 17.9 ms: 1.12x slower                                                       |
| coverage                   | 39.8 ms                                                     | 45.0 ms: 1.13x slower                                                       |
| telco                      | 4.08 ms                                                     | 4.68 ms: 1.15x slower                                                       |
| pycparser                  | 673 ms                                                      | 784 ms: 1.17x slower                                                        |
| unpack_sequence            | 36.9 ns                                                     | 44.0 ns: 1.19x slower                                                       |
| mypy2                      | 209 ms                                                      | 287 ms: 1.38x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (14): tornado_http, xml_etree_iterparse, create_gc_cycles, richards, regex_effbot, deepcopy_memo, json_loads, xml_etree_parse, pickle_list, asyncio_tcp, scimark_fft, logging_simple, async_tree_none_tg, bench_thread_pool
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.91% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
