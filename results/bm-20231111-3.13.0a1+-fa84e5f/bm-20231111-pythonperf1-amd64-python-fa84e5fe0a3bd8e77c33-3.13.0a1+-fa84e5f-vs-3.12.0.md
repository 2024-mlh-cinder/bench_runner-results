
# Results vs. 3.12.0

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: windows-amd64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 209 ms: 1.02x faster                                                        |
| chameleon      | 4.95 ms                                                     | 4.80 ms: 1.03x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.54 sec: 1.04x faster                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 286 ms                                                      | 266 ms: 1.08x faster                                                        |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 447 ms: 1.07x faster                                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 473 ms: 1.02x faster                                                        |
| async_tree_none_tg         | 277 ms                                                      | 280 ms: 1.01x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 755 ms: 1.02x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 339 ms: 1.02x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 357 ms: 1.03x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 52.3 ms: 1.05x faster                                                       |
| pidigits       | 150 ms                                                      | 146 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 74.3 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 79.2 ms: 1.10x faster                                                       |
| regex_effbot   | 1.58 ms                                                     | 1.59 ms: 1.00x slower                                                       |
| regex_dna      | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 15.3 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 179 us: 1.09x faster                                                        |
| pickle               | 7.38 us                                                     | 6.96 us: 1.06x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.2 us: 1.04x faster                                                       |
| unpickle_pure_python | 134 us                                                      | 130 us: 1.04x faster                                                        |
| unpickle             | 8.44 us                                                     | 8.19 us: 1.03x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.2 ms: 1.03x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.69 ms: 1.02x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.65 us: 1.02x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.2 ms: 1.01x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.42 sec: 1.03x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (3): pickle_list, xml_etree_iterparse, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.3 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.46 ms: 1.09x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions             | 14.0 us                                                     | 10.6 us: 1.32x faster                                                       |
| typing_runtime_protocols   | 96.7 us                                                     | 75.9 us: 1.27x faster                                                       |
| raytrace                   | 192 ms                                                      | 162 ms: 1.19x faster                                                        |
| sqlite_synth               | 1.75 us                                                     | 1.55 us: 1.12x faster                                                       |
| regex_compile              | 87.2 ms                                                     | 79.2 ms: 1.10x faster                                                       |
| mako                       | 7.05 ms                                                     | 6.46 ms: 1.09x faster                                                       |
| pickle_pure_python         | 195 us                                                      | 179 us: 1.09x faster                                                        |
| sympy_sum                  | 90.1 ms                                                     | 82.8 ms: 1.09x faster                                                       |
| sympy_str                  | 171 ms                                                      | 158 ms: 1.08x faster                                                        |
| bench_mp_pool              | 67.2 ms                                                     | 62.4 ms: 1.08x faster                                                       |
| nqueens                    | 61.7 ms                                                     | 57.4 ms: 1.08x faster                                                       |
| async_tree_none            | 286 ms                                                      | 266 ms: 1.08x faster                                                        |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 447 ms: 1.07x faster                                                        |
| deepcopy_reduce            | 2.08 us                                                     | 1.95 us: 1.07x faster                                                       |
| scimark_monte_carlo        | 43.0 ms                                                     | 40.3 ms: 1.07x faster                                                       |
| coroutines                 | 14.1 ms                                                     | 13.3 ms: 1.06x faster                                                       |
| generators                 | 22.6 ms                                                     | 21.3 ms: 1.06x faster                                                       |
| pickle                     | 7.38 us                                                     | 6.96 us: 1.06x faster                                                       |
| deepcopy                   | 233 us                                                      | 219 us: 1.06x faster                                                        |
| scimark_lu                 | 57.5 ms                                                     | 54.4 ms: 1.06x faster                                                       |
| sqlglot_parse              | 802 us                                                      | 759 us: 1.06x faster                                                        |
| dulwich_log                | 42.7 ms                                                     | 40.5 ms: 1.06x faster                                                       |
| sympy_integrate            | 13.0 ms                                                     | 12.3 ms: 1.05x faster                                                       |
| mdp                        | 1.42 sec                                                    | 1.35 sec: 1.05x faster                                                      |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.38 ms: 1.05x faster                                                       |
| logging_silent             | 60.5 ns                                                     | 57.6 ns: 1.05x faster                                                       |
| sqlglot_normalize          | 183 ms                                                      | 175 ms: 1.05x faster                                                        |
| float                      | 54.7 ms                                                     | 52.3 ms: 1.05x faster                                                       |
| docutils                   | 1.61 sec                                                    | 1.54 sec: 1.04x faster                                                      |
| sqlglot_transpile          | 1.02 ms                                                     | 974 us: 1.04x faster                                                        |
| crypto_pyaes               | 46.4 ms                                                     | 44.6 ms: 1.04x faster                                                       |
| scimark_fft                | 181 ms                                                      | 174 ms: 1.04x faster                                                        |
| pickle_dict                | 18.9 us                                                     | 18.2 us: 1.04x faster                                                       |
| hexiom                     | 4.00 ms                                                     | 3.85 ms: 1.04x faster                                                       |
| chaos                      | 42.1 ms                                                     | 40.6 ms: 1.04x faster                                                       |
| logging_format             | 6.72 us                                                     | 6.48 us: 1.04x faster                                                       |
| unpickle_pure_python       | 134 us                                                      | 130 us: 1.04x faster                                                        |
| deltablue                  | 2.12 ms                                                     | 2.06 ms: 1.03x faster                                                       |
| chameleon                  | 4.95 ms                                                     | 4.80 ms: 1.03x faster                                                       |
| unpickle                   | 8.44 us                                                     | 8.19 us: 1.03x faster                                                       |
| xml_etree_generate         | 55.8 ms                                                     | 54.2 ms: 1.03x faster                                                       |
| go                         | 89.0 ms                                                     | 86.5 ms: 1.03x faster                                                       |
| sympy_expand               | 278 ms                                                      | 271 ms: 1.03x faster                                                        |
| sqlglot_optimize           | 34.0 ms                                                     | 33.2 ms: 1.03x faster                                                       |
| pprint_pformat             | 1.04 sec                                                    | 1.01 sec: 1.03x faster                                                      |
| pidigits                   | 150 ms                                                      | 146 ms: 1.02x faster                                                        |
| json_dumps                 | 5.83 ms                                                     | 5.69 ms: 1.02x faster                                                       |
| pprint_safe_repr           | 508 ms                                                      | 496 ms: 1.02x faster                                                        |
| logging_simple             | 6.21 us                                                     | 6.07 us: 1.02x faster                                                       |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 473 ms: 1.02x faster                                                        |
| async_generators           | 230 ms                                                      | 226 ms: 1.02x faster                                                        |
| spectral_norm              | 63.9 ms                                                     | 62.8 ms: 1.02x faster                                                       |
| unpickle_list              | 2.69 us                                                     | 2.65 us: 1.02x faster                                                       |
| 2to3                       | 213 ms                                                      | 209 ms: 1.02x faster                                                        |
| xml_etree_process          | 37.6 ms                                                     | 37.2 ms: 1.01x faster                                                       |
| pyflate                    | 294 ms                                                      | 291 ms: 1.01x faster                                                        |
| richards_super             | 31.2 ms                                                     | 30.9 ms: 1.01x faster                                                       |
| pathlib                    | 79.6 ms                                                     | 79.0 ms: 1.01x faster                                                       |
| json_loads                 | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| regex_effbot               | 1.58 ms                                                     | 1.59 ms: 1.00x slower                                                       |
| richards                   | 27.6 ms                                                     | 27.7 ms: 1.01x slower                                                       |
| fannkuch                   | 244 ms                                                      | 246 ms: 1.01x slower                                                        |
| regex_dna                  | 119 ms                                                      | 121 ms: 1.01x slower                                                        |
| scimark_sor                | 79.8 ms                                                     | 80.7 ms: 1.01x slower                                                       |
| gc_traversal               | 1.49 ms                                                     | 1.51 ms: 1.01x slower                                                       |
| async_tree_none_tg         | 277 ms                                                      | 280 ms: 1.01x slower                                                        |
| deepcopy_memo              | 23.4 us                                                     | 23.8 us: 1.02x slower                                                       |
| async_tree_io_tg           | 742 ms                                                      | 755 ms: 1.02x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 339 ms: 1.02x slower                                                        |
| meteor_contest             | 72.1 ms                                                     | 74.1 ms: 1.03x slower                                                       |
| tomli_loads                | 1.38 sec                                                    | 1.42 sec: 1.03x slower                                                      |
| async_tree_memoization_tg  | 345 ms                                                      | 357 ms: 1.03x slower                                                        |
| python_startup             | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| nbody                      | 68.8 ms                                                     | 74.3 ms: 1.08x slower                                                       |
| regex_v8                   | 13.5 ms                                                     | 15.3 ms: 1.13x slower                                                       |
| python_startup_no_site     | 15.9 ms                                                     | 18.3 ms: 1.15x slower                                                       |
| coverage                   | 39.8 ms                                                     | 46.1 ms: 1.16x slower                                                       |
| telco                      | 4.08 ms                                                     | 4.76 ms: 1.17x slower                                                       |
| pycparser                  | 673 ms                                                      | 802 ms: 1.19x slower                                                        |
| unpack_sequence            | 36.9 ns                                                     | 47.3 ns: 1.28x slower                                                       |
| mypy2                      | 209 ms                                                      | 286 ms: 1.37x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (10): create_gc_cycles, pickle_list, xml_etree_iterparse, asyncio_tcp, bench_thread_pool, async_tree_io, tornado_http, xml_etree_parse, asyncio_tcp_ssl, json
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
