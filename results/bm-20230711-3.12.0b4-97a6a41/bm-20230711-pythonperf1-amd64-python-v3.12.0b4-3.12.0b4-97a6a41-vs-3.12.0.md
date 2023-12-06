
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b4
- machine: windows-amd64
- commit hash: 97a6a41
- commit date: 2023-07-11
- overall geometric mean: 1.01x slower \*
- HPT reliability: 71.75%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 207 ms: 1.02x faster                                            |
| tornado_http   | 87.2 ms                                                     | 86.3 ms: 1.01x faster                                           |
| Geometric mean | (ref)                                                       | 1.01x faster                                                    |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

Benchmark hidden because not significant (4): async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 53.6 ms: 1.02x faster                                           |
| pidigits       | 150 ms                                                      | 150 ms: 1.00x slower                                            |
| nbody          | 68.8 ms                                                     | 74.4 ms: 1.08x slower                                           |
| Geometric mean | (ref)                                                       | 1.02x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_v8       | 13.5 ms                                                     | 13.0 ms: 1.04x faster                                           |
| regex_dna      | 119 ms                                                      | 115 ms: 1.04x faster                                            |
| regex_effbot   | 1.58 ms                                                     | 1.57 ms: 1.00x faster                                           |
| Geometric mean | (ref)                                                       | 1.02x faster                                                    |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 5.83 ms                                                     | 5.50 ms: 1.06x faster                                           |
| pickle               | 7.38 us                                                     | 7.05 us: 1.05x faster                                           |
| pickle_dict          | 18.9 us                                                     | 18.4 us: 1.03x faster                                           |
| unpickle             | 8.44 us                                                     | 8.23 us: 1.02x faster                                           |
| json_loads           | 13.6 us                                                     | 13.4 us: 1.01x faster                                           |
| xml_etree_generate   | 55.8 ms                                                     | 55.0 ms: 1.01x faster                                           |
| xml_etree_process    | 37.6 ms                                                     | 37.4 ms: 1.00x faster                                           |
| pickle_list          | 2.88 us                                                     | 2.89 us: 1.00x slower                                           |
| unpickle_pure_python | 134 us                                                      | 135 us: 1.01x slower                                            |
| xml_etree_parse      | 90.5 ms                                                     | 91.5 ms: 1.01x slower                                           |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.6 ms: 1.02x slower                                           |
| tomli_loads          | 1.38 sec                                                    | 1.41 sec: 1.02x slower                                          |
| unpickle_list        | 2.69 us                                                     | 2.90 us: 1.08x slower                                           |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                    |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.1 ms: 1.01x slower                                           |
| python_startup_no_site | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                           |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.86 ms: 1.03x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-pythonperf1-amd64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps               | 5.83 ms                                                     | 5.50 ms: 1.06x faster                                           |
| pickle                   | 7.38 us                                                     | 7.05 us: 1.05x faster                                           |
| regex_v8                 | 13.5 ms                                                     | 13.0 ms: 1.04x faster                                           |
| raytrace                 | 192 ms                                                      | 186 ms: 1.04x faster                                            |
| typing_runtime_protocols | 96.7 us                                                     | 93.3 us: 1.04x faster                                           |
| regex_dna                | 119 ms                                                      | 115 ms: 1.04x faster                                            |
| richards_super           | 31.2 ms                                                     | 30.2 ms: 1.03x faster                                           |
| richards                 | 27.6 ms                                                     | 26.8 ms: 1.03x faster                                           |
| bench_mp_pool            | 67.2 ms                                                     | 65.4 ms: 1.03x faster                                           |
| pickle_dict              | 18.9 us                                                     | 18.4 us: 1.03x faster                                           |
| mako                     | 7.05 ms                                                     | 6.86 ms: 1.03x faster                                           |
| deepcopy_reduce          | 2.08 us                                                     | 2.03 us: 1.03x faster                                           |
| unpickle                 | 8.44 us                                                     | 8.23 us: 1.02x faster                                           |
| 2to3                     | 213 ms                                                      | 207 ms: 1.02x faster                                            |
| scimark_fft              | 181 ms                                                      | 177 ms: 1.02x faster                                            |
| float                    | 54.7 ms                                                     | 53.6 ms: 1.02x faster                                           |
| pathlib                  | 79.6 ms                                                     | 78.0 ms: 1.02x faster                                           |
| generators               | 22.6 ms                                                     | 22.2 ms: 1.02x faster                                           |
| logging_silent           | 60.5 ns                                                     | 59.4 ns: 1.02x faster                                           |
| dulwich_log              | 42.7 ms                                                     | 42.1 ms: 1.01x faster                                           |
| json_loads               | 13.6 us                                                     | 13.4 us: 1.01x faster                                           |
| xml_etree_generate       | 55.8 ms                                                     | 55.0 ms: 1.01x faster                                           |
| json                     | 2.94 ms                                                     | 2.91 ms: 1.01x faster                                           |
| mypy2                    | 209 ms                                                      | 206 ms: 1.01x faster                                            |
| sqlglot_normalize        | 183 ms                                                      | 181 ms: 1.01x faster                                            |
| tornado_http             | 87.2 ms                                                     | 86.3 ms: 1.01x faster                                           |
| pycparser                | 673 ms                                                      | 667 ms: 1.01x faster                                            |
| deltablue                | 2.12 ms                                                     | 2.10 ms: 1.01x faster                                           |
| go                       | 89.0 ms                                                     | 88.2 ms: 1.01x faster                                           |
| sqlglot_optimize         | 34.0 ms                                                     | 33.7 ms: 1.01x faster                                           |
| coroutines               | 14.1 ms                                                     | 14.0 ms: 1.01x faster                                           |
| xml_etree_process        | 37.6 ms                                                     | 37.4 ms: 1.00x faster                                           |
| regex_effbot             | 1.58 ms                                                     | 1.57 ms: 1.00x faster                                           |
| pidigits                 | 150 ms                                                      | 150 ms: 1.00x slower                                            |
| scimark_lu               | 57.5 ms                                                     | 57.6 ms: 1.00x slower                                           |
| pickle_list              | 2.88 us                                                     | 2.89 us: 1.00x slower                                           |
| telco                    | 4.08 ms                                                     | 4.11 ms: 1.01x slower                                           |
| unpickle_pure_python     | 134 us                                                      | 135 us: 1.01x slower                                            |
| crypto_pyaes             | 46.4 ms                                                     | 46.8 ms: 1.01x slower                                           |
| scimark_sparse_mat_mult  | 2.51 ms                                                     | 2.53 ms: 1.01x slower                                           |
| pprint_pformat           | 1.04 sec                                                    | 1.05 sec: 1.01x slower                                          |
| xml_etree_parse          | 90.5 ms                                                     | 91.5 ms: 1.01x slower                                           |
| pprint_safe_repr         | 508 ms                                                      | 514 ms: 1.01x slower                                            |
| python_startup           | 18.8 ms                                                     | 19.1 ms: 1.01x slower                                           |
| pyflate                  | 294 ms                                                      | 298 ms: 1.02x slower                                            |
| fannkuch                 | 244 ms                                                      | 248 ms: 1.02x slower                                            |
| spectral_norm            | 63.9 ms                                                     | 65.1 ms: 1.02x slower                                           |
| xml_etree_iterparse      | 63.1 ms                                                     | 64.6 ms: 1.02x slower                                           |
| tomli_loads              | 1.38 sec                                                    | 1.41 sec: 1.02x slower                                          |
| meteor_contest           | 72.1 ms                                                     | 73.8 ms: 1.02x slower                                           |
| logging_format           | 6.72 us                                                     | 6.88 us: 1.03x slower                                           |
| python_startup_no_site   | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                           |
| chaos                    | 42.1 ms                                                     | 43.3 ms: 1.03x slower                                           |
| hexiom                   | 4.00 ms                                                     | 4.14 ms: 1.03x slower                                           |
| scimark_sor              | 79.8 ms                                                     | 82.6 ms: 1.04x slower                                           |
| logging_simple           | 6.21 us                                                     | 6.46 us: 1.04x slower                                           |
| mdp                      | 1.42 sec                                                    | 1.49 sec: 1.05x slower                                          |
| deepcopy_memo            | 23.4 us                                                     | 24.9 us: 1.06x slower                                           |
| unpickle_list            | 2.69 us                                                     | 2.90 us: 1.08x slower                                           |
| nbody                    | 68.8 ms                                                     | 74.4 ms: 1.08x slower                                           |
| asyncio_tcp_ssl          | 1.89 sec                                                    | 2.06 sec: 1.09x slower                                          |
| unpack_sequence          | 36.9 ns                                                     | 44.7 ns: 1.21x slower                                           |
| coverage                 | 39.8 ms                                                     | 52.7 ms: 1.32x slower                                           |
| dask                     | 255 ms                                                      | 359 ms: 1.41x slower                                            |
| Geometric mean           | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (20): deepcopy, async_tree_io, async_tree_cpu_io_mixed, create_gc_cycles, nqueens, async_generators, sqlglot_transpile, gc_traversal, regex_compile, async_tree_memoization, sqlglot_parse, docutils, aiohttp, scimark_monte_carlo, pickle_pure_python, comprehensions, sqlite_synth, async_tree_none, asyncio_tcp, bench_thread_pool
Ignored benchmarks (12) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 71.75% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
