
# Results vs. 3.12.0

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: windows-amd64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 222 ms: 1.05x slower                                                        |
| chameleon      | 4.95 ms                                                     | 5.27 ms: 1.07x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.65 sec: 1.03x slower                                                      |
| tornado_http   | 87.2 ms                                                     | 90.3 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 494 ms: 1.02x slower                                                        |
| async_tree_none_tg         | 277 ms                                                      | 295 ms: 1.06x slower                                                        |
| async_tree_io_tg           | 742 ms                                                      | 791 ms: 1.07x slower                                                        |
| async_tree_io              | 712 ms                                                      | 767 ms: 1.08x slower                                                        |
| async_tree_memoization     | 333 ms                                                      | 362 ms: 1.09x slower                                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 383 ms: 1.11x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (2): async_tree_none, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 148 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 74.3 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.60 ms: 1.01x slower                                                       |
| regex_dna      | 119 ms                                                      | 121 ms: 1.02x slower                                                        |
| regex_compile  | 87.2 ms                                                     | 92.8 ms: 1.06x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 15.2 ms: 1.12x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.98 us: 1.06x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.64 us: 1.02x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.73 ms: 1.02x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.84 us: 1.02x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.31 us: 1.01x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.8 us: 1.01x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 56.7 ms: 1.02x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 93.0 ms: 1.03x slower                                                       |
| pickle_pure_python   | 195 us                                                      | 200 us: 1.03x slower                                                        |
| unpickle_pure_python | 134 us                                                      | 139 us: 1.03x slower                                                        |
| xml_etree_iterparse  | 63.1 ms                                                     | 65.4 ms: 1.04x slower                                                       |
| xml_etree_process    | 37.6 ms                                                     | 39.9 ms: 1.06x slower                                                       |
| tomli_loads          | 1.38 sec                                                    | 1.56 sec: 1.13x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.6 ms: 1.09x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.1 ms: 1.13x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions             | 14.0 us                                                     | 11.3 us: 1.24x faster                                                       |
| sqlite_synth               | 1.75 us                                                     | 1.56 us: 1.12x faster                                                       |
| raytrace                   | 192 ms                                                      | 180 ms: 1.07x faster                                                        |
| bench_mp_pool              | 67.2 ms                                                     | 63.1 ms: 1.07x faster                                                       |
| pickle                     | 7.38 us                                                     | 6.98 us: 1.06x faster                                                       |
| crypto_pyaes               | 46.4 ms                                                     | 44.2 ms: 1.05x faster                                                       |
| sympy_sum                  | 90.1 ms                                                     | 88.1 ms: 1.02x faster                                                       |
| unpickle_list              | 2.69 us                                                     | 2.64 us: 1.02x faster                                                       |
| json                       | 2.94 ms                                                     | 2.89 ms: 1.02x faster                                                       |
| json_dumps                 | 5.83 ms                                                     | 5.73 ms: 1.02x faster                                                       |
| pidigits                   | 150 ms                                                      | 148 ms: 1.02x faster                                                        |
| pickle_list                | 2.88 us                                                     | 2.84 us: 1.02x faster                                                       |
| scimark_monte_carlo        | 43.0 ms                                                     | 42.3 ms: 1.02x faster                                                       |
| unpickle                   | 8.44 us                                                     | 8.31 us: 1.01x faster                                                       |
| pickle_dict                | 18.9 us                                                     | 18.8 us: 1.01x faster                                                       |
| scimark_lu                 | 57.5 ms                                                     | 58.0 ms: 1.01x slower                                                       |
| gc_traversal               | 1.49 ms                                                     | 1.50 ms: 1.01x slower                                                       |
| sympy_integrate            | 13.0 ms                                                     | 13.1 ms: 1.01x slower                                                       |
| scimark_sor                | 79.8 ms                                                     | 80.6 ms: 1.01x slower                                                       |
| regex_effbot               | 1.58 ms                                                     | 1.60 ms: 1.01x slower                                                       |
| regex_dna                  | 119 ms                                                      | 121 ms: 1.02x slower                                                        |
| xml_etree_generate         | 55.8 ms                                                     | 56.7 ms: 1.02x slower                                                       |
| bench_thread_pool          | 830 us                                                      | 844 us: 1.02x slower                                                        |
| sympy_str                  | 171 ms                                                      | 175 ms: 1.02x slower                                                        |
| nqueens                    | 61.7 ms                                                     | 63.0 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 494 ms: 1.02x slower                                                        |
| unpack_sequence            | 36.9 ns                                                     | 37.8 ns: 1.03x slower                                                       |
| xml_etree_parse            | 90.5 ms                                                     | 93.0 ms: 1.03x slower                                                       |
| docutils                   | 1.61 sec                                                    | 1.65 sec: 1.03x slower                                                      |
| scimark_fft                | 181 ms                                                      | 186 ms: 1.03x slower                                                        |
| pickle_pure_python         | 195 us                                                      | 200 us: 1.03x slower                                                        |
| chaos                      | 42.1 ms                                                     | 43.3 ms: 1.03x slower                                                       |
| unpickle_pure_python       | 134 us                                                      | 139 us: 1.03x slower                                                        |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.60 ms: 1.03x slower                                                       |
| xml_etree_iterparse        | 63.1 ms                                                     | 65.4 ms: 1.04x slower                                                       |
| logging_silent             | 60.5 ns                                                     | 62.7 ns: 1.04x slower                                                       |
| async_generators           | 230 ms                                                      | 238 ms: 1.04x slower                                                        |
| tornado_http               | 87.2 ms                                                     | 90.3 ms: 1.04x slower                                                       |
| generators                 | 22.6 ms                                                     | 23.5 ms: 1.04x slower                                                       |
| typing_runtime_protocols   | 96.7 us                                                     | 101 us: 1.04x slower                                                        |
| coroutines                 | 14.1 ms                                                     | 14.7 ms: 1.04x slower                                                       |
| mypy2                      | 209 ms                                                      | 218 ms: 1.04x slower                                                        |
| pyflate                    | 294 ms                                                      | 307 ms: 1.05x slower                                                        |
| 2to3                       | 213 ms                                                      | 222 ms: 1.05x slower                                                        |
| mdp                        | 1.42 sec                                                    | 1.49 sec: 1.05x slower                                                      |
| meteor_contest             | 72.1 ms                                                     | 75.6 ms: 1.05x slower                                                       |
| asyncio_tcp_ssl            | 1.89 sec                                                    | 1.98 sec: 1.05x slower                                                      |
| deltablue                  | 2.12 ms                                                     | 2.25 ms: 1.06x slower                                                       |
| xml_etree_process          | 37.6 ms                                                     | 39.9 ms: 1.06x slower                                                       |
| pprint_pformat             | 1.04 sec                                                    | 1.10 sec: 1.06x slower                                                      |
| pprint_safe_repr           | 508 ms                                                      | 540 ms: 1.06x slower                                                        |
| regex_compile              | 87.2 ms                                                     | 92.8 ms: 1.06x slower                                                       |
| async_tree_none_tg         | 277 ms                                                      | 295 ms: 1.06x slower                                                        |
| chameleon                  | 4.95 ms                                                     | 5.27 ms: 1.07x slower                                                       |
| async_tree_io_tg           | 742 ms                                                      | 791 ms: 1.07x slower                                                        |
| sqlglot_transpile          | 1.02 ms                                                     | 1.08 ms: 1.07x slower                                                       |
| fannkuch                   | 244 ms                                                      | 261 ms: 1.07x slower                                                        |
| dulwich_log                | 42.7 ms                                                     | 45.6 ms: 1.07x slower                                                       |
| hexiom                     | 4.00 ms                                                     | 4.28 ms: 1.07x slower                                                       |
| sqlglot_normalize          | 183 ms                                                      | 197 ms: 1.07x slower                                                        |
| sqlglot_parse              | 802 us                                                      | 862 us: 1.07x slower                                                        |
| deepcopy                   | 233 us                                                      | 250 us: 1.08x slower                                                        |
| deepcopy_memo              | 23.4 us                                                     | 25.2 us: 1.08x slower                                                       |
| async_tree_io              | 712 ms                                                      | 767 ms: 1.08x slower                                                        |
| go                         | 89.0 ms                                                     | 95.9 ms: 1.08x slower                                                       |
| sqlglot_optimize           | 34.0 ms                                                     | 36.7 ms: 1.08x slower                                                       |
| deepcopy_reduce            | 2.08 us                                                     | 2.25 us: 1.08x slower                                                       |
| nbody                      | 68.8 ms                                                     | 74.3 ms: 1.08x slower                                                       |
| richards_super             | 31.2 ms                                                     | 33.8 ms: 1.08x slower                                                       |
| logging_simple             | 6.21 us                                                     | 6.75 us: 1.09x slower                                                       |
| async_tree_memoization     | 333 ms                                                      | 362 ms: 1.09x slower                                                        |
| logging_format             | 6.72 us                                                     | 7.31 us: 1.09x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.6 ms: 1.09x slower                                                       |
| sympy_expand               | 278 ms                                                      | 305 ms: 1.10x slower                                                        |
| richards                   | 27.6 ms                                                     | 30.3 ms: 1.10x slower                                                       |
| async_tree_memoization_tg  | 345 ms                                                      | 383 ms: 1.11x slower                                                        |
| regex_v8                   | 13.5 ms                                                     | 15.2 ms: 1.12x slower                                                       |
| tomli_loads                | 1.38 sec                                                    | 1.56 sec: 1.13x slower                                                      |
| python_startup_no_site     | 15.9 ms                                                     | 18.1 ms: 1.13x slower                                                       |
| coverage                   | 39.8 ms                                                     | 46.1 ms: 1.16x slower                                                       |
| telco                      | 4.08 ms                                                     | 4.79 ms: 1.17x slower                                                       |
| pycparser                  | 673 ms                                                      | 818 ms: 1.22x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.04x slower                                                                |

Benchmark hidden because not significant (9): async_tree_none, async_tree_cpu_io_mixed, float, pathlib, spectral_norm, json_loads, create_gc_cycles, mako, asyncio_tcp
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
