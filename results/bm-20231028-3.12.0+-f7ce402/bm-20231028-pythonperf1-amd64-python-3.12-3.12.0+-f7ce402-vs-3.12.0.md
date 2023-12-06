
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.01x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 215 ms: 1.01x slower                                      |
| chameleon      | 4.95 ms                                                     | 5.23 ms: 1.06x slower                                     |
| docutils       | 1.61 sec                                                    | 1.62 sec: 1.01x slower                                    |
| Geometric mean | (ref)                                                       | 1.02x slower                                              |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| async_tree_memoization     | 333 ms                                                      | 339 ms: 1.02x slower                                      |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 492 ms: 1.02x slower                                      |
| async_tree_memoization_tg  | 345 ms                                                      | 353 ms: 1.02x slower                                      |
| Geometric mean             | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (5): async_tree_none_tg, async_tree_io_tg, async_tree_none, async_tree_cpu_io_mixed, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.00x slower                                      |
| nbody          | 68.8 ms                                                     | 70.3 ms: 1.02x slower                                     |
| Geometric mean | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_dna      | 119 ms                                                      | 121 ms: 1.01x slower                                      |
| regex_compile  | 87.2 ms                                                     | 89.0 ms: 1.02x slower                                     |
| regex_effbot   | 1.58 ms                                                     | 1.62 ms: 1.02x slower                                     |
| regex_v8       | 13.5 ms                                                     | 13.9 ms: 1.03x slower                                     |
| Geometric mean | (ref)                                                       | 1.02x slower                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 5.83 ms                                                     | 5.62 ms: 1.04x faster                                     |
| pickle_dict          | 18.9 us                                                     | 18.3 us: 1.04x faster                                     |
| unpickle             | 8.44 us                                                     | 8.15 us: 1.03x faster                                     |
| pickle               | 7.38 us                                                     | 7.25 us: 1.02x faster                                     |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                     |
| pickle_list          | 2.88 us                                                     | 2.90 us: 1.00x slower                                     |
| xml_etree_iterparse  | 63.1 ms                                                     | 63.7 ms: 1.01x slower                                     |
| pickle_pure_python   | 195 us                                                      | 197 us: 1.01x slower                                      |
| unpickle_pure_python | 134 us                                                      | 136 us: 1.01x slower                                      |
| xml_etree_generate   | 55.8 ms                                                     | 56.7 ms: 1.02x slower                                     |
| xml_etree_parse      | 90.5 ms                                                     | 92.3 ms: 1.02x slower                                     |
| tomli_loads          | 1.38 sec                                                    | 1.41 sec: 1.02x slower                                    |
| xml_etree_process    | 37.6 ms                                                     | 38.7 ms: 1.03x slower                                     |
| unpickle_list        | 2.69 us                                                     | 2.78 us: 1.03x slower                                     |
| Geometric mean       | (ref)                                                       | 1.00x slower                                              |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                     |
| python_startup         | 18.8 ms                                                     | 19.9 ms: 1.05x slower                                     |
| Geometric mean         | (ref)                                                       | 1.05x slower                                              |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 6.90 ms: 1.02x faster                                     |
| django_template | 22.8 ms                                                     | 23.3 ms: 1.02x slower                                     |
| Geometric mean  | (ref)                                                       | 1.00x slower                                              |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| bench_mp_pool              | 67.2 ms                                                     | 63.2 ms: 1.06x faster                                     |
| json_dumps                 | 5.83 ms                                                     | 5.62 ms: 1.04x faster                                     |
| pickle_dict                | 18.9 us                                                     | 18.3 us: 1.04x faster                                     |
| unpickle                   | 8.44 us                                                     | 8.15 us: 1.03x faster                                     |
| sympy_sum                  | 90.1 ms                                                     | 87.9 ms: 1.03x faster                                     |
| coverage                   | 39.8 ms                                                     | 38.8 ms: 1.02x faster                                     |
| mako                       | 7.05 ms                                                     | 6.90 ms: 1.02x faster                                     |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.46 ms: 1.02x faster                                     |
| pickle                     | 7.38 us                                                     | 7.25 us: 1.02x faster                                     |
| sympy_str                  | 171 ms                                                      | 169 ms: 1.02x faster                                      |
| sympy_integrate            | 13.0 ms                                                     | 12.8 ms: 1.01x faster                                     |
| json_loads                 | 13.6 us                                                     | 13.5 us: 1.01x faster                                     |
| telco                      | 4.08 ms                                                     | 4.05 ms: 1.01x faster                                     |
| typing_runtime_protocols   | 96.7 us                                                     | 95.9 us: 1.01x faster                                     |
| mypy2                      | 209 ms                                                      | 209 ms: 1.00x slower                                      |
| pickle_list                | 2.88 us                                                     | 2.90 us: 1.00x slower                                     |
| sqlalchemy_imperative      | 9.20 ms                                                     | 9.25 ms: 1.00x slower                                     |
| pidigits                   | 150 ms                                                      | 151 ms: 1.00x slower                                      |
| richards                   | 27.6 ms                                                     | 27.8 ms: 1.01x slower                                     |
| xml_etree_iterparse        | 63.1 ms                                                     | 63.7 ms: 1.01x slower                                     |
| spectral_norm              | 63.9 ms                                                     | 64.5 ms: 1.01x slower                                     |
| go                         | 89.0 ms                                                     | 89.8 ms: 1.01x slower                                     |
| 2to3                       | 213 ms                                                      | 215 ms: 1.01x slower                                      |
| docutils                   | 1.61 sec                                                    | 1.62 sec: 1.01x slower                                    |
| sqlglot_transpile          | 1.02 ms                                                     | 1.03 ms: 1.01x slower                                     |
| richards_super             | 31.2 ms                                                     | 31.5 ms: 1.01x slower                                     |
| nqueens                    | 61.7 ms                                                     | 62.4 ms: 1.01x slower                                     |
| logging_silent             | 60.5 ns                                                     | 61.1 ns: 1.01x slower                                     |
| sqlglot_optimize           | 34.0 ms                                                     | 34.4 ms: 1.01x slower                                     |
| pickle_pure_python         | 195 us                                                      | 197 us: 1.01x slower                                      |
| regex_dna                  | 119 ms                                                      | 121 ms: 1.01x slower                                      |
| unpickle_pure_python       | 134 us                                                      | 136 us: 1.01x slower                                      |
| pycparser                  | 673 ms                                                      | 683 ms: 1.01x slower                                      |
| aiohttp                    | 848 us                                                      | 861 us: 1.01x slower                                      |
| sympy_expand               | 278 ms                                                      | 282 ms: 1.02x slower                                      |
| async_generators           | 230 ms                                                      | 234 ms: 1.02x slower                                      |
| sqlglot_parse              | 802 us                                                      | 815 us: 1.02x slower                                      |
| xml_etree_generate         | 55.8 ms                                                     | 56.7 ms: 1.02x slower                                     |
| logging_format             | 6.72 us                                                     | 6.83 us: 1.02x slower                                     |
| pyflate                    | 294 ms                                                      | 299 ms: 1.02x slower                                      |
| deltablue                  | 2.12 ms                                                     | 2.16 ms: 1.02x slower                                     |
| async_tree_memoization     | 333 ms                                                      | 339 ms: 1.02x slower                                      |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 492 ms: 1.02x slower                                      |
| xml_etree_parse            | 90.5 ms                                                     | 92.3 ms: 1.02x slower                                     |
| regex_compile              | 87.2 ms                                                     | 89.0 ms: 1.02x slower                                     |
| tomli_loads                | 1.38 sec                                                    | 1.41 sec: 1.02x slower                                    |
| pprint_pformat             | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                    |
| regex_effbot               | 1.58 ms                                                     | 1.62 ms: 1.02x slower                                     |
| nbody                      | 68.8 ms                                                     | 70.3 ms: 1.02x slower                                     |
| async_tree_memoization_tg  | 345 ms                                                      | 353 ms: 1.02x slower                                      |
| django_template            | 22.8 ms                                                     | 23.3 ms: 1.02x slower                                     |
| raytrace                   | 192 ms                                                      | 198 ms: 1.03x slower                                      |
| logging_simple             | 6.21 us                                                     | 6.37 us: 1.03x slower                                     |
| crypto_pyaes               | 46.4 ms                                                     | 47.7 ms: 1.03x slower                                     |
| mdp                        | 1.42 sec                                                    | 1.46 sec: 1.03x slower                                    |
| pprint_safe_repr           | 508 ms                                                      | 522 ms: 1.03x slower                                      |
| deepcopy_reduce            | 2.08 us                                                     | 2.14 us: 1.03x slower                                     |
| xml_etree_process          | 37.6 ms                                                     | 38.7 ms: 1.03x slower                                     |
| fannkuch                   | 244 ms                                                      | 251 ms: 1.03x slower                                      |
| regex_v8                   | 13.5 ms                                                     | 13.9 ms: 1.03x slower                                     |
| unpickle_list              | 2.69 us                                                     | 2.78 us: 1.03x slower                                     |
| deepcopy                   | 233 us                                                      | 240 us: 1.03x slower                                      |
| comprehensions             | 14.0 us                                                     | 14.5 us: 1.04x slower                                     |
| asyncio_tcp_ssl            | 1.89 sec                                                    | 1.96 sec: 1.04x slower                                    |
| python_startup_no_site     | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                     |
| meteor_contest             | 72.1 ms                                                     | 75.0 ms: 1.04x slower                                     |
| deepcopy_memo              | 23.4 us                                                     | 24.4 us: 1.04x slower                                     |
| scimark_fft                | 181 ms                                                      | 189 ms: 1.04x slower                                      |
| hexiom                     | 4.00 ms                                                     | 4.18 ms: 1.04x slower                                     |
| chaos                      | 42.1 ms                                                     | 44.3 ms: 1.05x slower                                     |
| python_startup             | 18.8 ms                                                     | 19.9 ms: 1.05x slower                                     |
| scimark_sor                | 79.8 ms                                                     | 84.2 ms: 1.06x slower                                     |
| scimark_monte_carlo        | 43.0 ms                                                     | 45.4 ms: 1.06x slower                                     |
| chameleon                  | 4.95 ms                                                     | 5.23 ms: 1.06x slower                                     |
| scimark_lu                 | 57.5 ms                                                     | 61.3 ms: 1.07x slower                                     |
| unpack_sequence            | 36.9 ns                                                     | 41.4 ns: 1.12x slower                                     |
| Geometric mean             | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (20): bench_thread_pool, generators, pathlib, float, gc_traversal, coroutines, create_gc_cycles, dulwich_log, sqlite_synth, json, sqlalchemy_declarative, sqlglot_normalize, async_tree_none_tg, tornado_http, async_tree_io_tg, asyncio_tcp, async_tree_none, dask, async_tree_cpu_io_mixed, async_tree_io


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
