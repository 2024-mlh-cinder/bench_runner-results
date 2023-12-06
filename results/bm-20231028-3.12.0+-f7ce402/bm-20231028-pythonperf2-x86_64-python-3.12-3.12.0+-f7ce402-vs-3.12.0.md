
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.01x slower
- HPT reliability: 90.66%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 286 ms: 1.00x slower                                       |
| chameleon      | 7.27 ms                                                      | 7.22 ms: 1.01x faster                                      |
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                     |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_io   | 1.06 sec                                                     | 1.06 sec: 1.00x slower                                     |
| async_tree_none | 459 ms                                                       | 461 ms: 1.01x slower                                       |
| Geometric mean  | (ref)                                                        | 1.00x slower                                               |

Benchmark hidden because not significant (6): async_tree_memoization_tg, async_tree_io_tg, async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 81.6 ms                                                      | 78.9 ms: 1.03x faster                                      |
| Geometric mean | (ref)                                                        | 1.02x faster                                               |

Benchmark hidden because not significant (2): nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.49 ms: 1.04x faster                                      |
| regex_compile  | 145 ms                                                       | 143 ms: 1.01x faster                                       |
| regex_dna      | 240 ms                                                       | 247 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.6 us: 1.05x faster                                      |
| json_loads           | 24.3 us                                                      | 24.2 us: 1.01x faster                                      |
| json_dumps           | 10.3 ms                                                      | 10.2 ms: 1.00x faster                                      |
| xml_etree_process    | 58.3 ms                                                      | 58.6 ms: 1.00x slower                                      |
| xml_etree_generate   | 85.3 ms                                                      | 85.8 ms: 1.01x slower                                      |
| tomli_loads          | 2.17 sec                                                     | 2.19 sec: 1.01x slower                                     |
| unpickle_pure_python | 210 us                                                       | 211 us: 1.01x slower                                       |
| pickle_dict          | 32.0 us                                                      | 32.4 us: 1.01x slower                                      |
| pickle               | 10.0 us                                                      | 10.2 us: 1.02x slower                                      |
| xml_etree_parse      | 147 ms                                                       | 149 ms: 1.02x slower                                       |
| unpickle_list        | 4.65 us                                                      | 4.78 us: 1.03x slower                                      |
| pickle_list          | 4.22 us                                                      | 4.50 us: 1.07x slower                                      |
| Geometric mean       | (ref)                                                        | 1.01x slower                                               |

Benchmark hidden because not significant (2): xml_etree_iterparse, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 8.66 ms: 1.00x faster                                      |
| python_startup         | 11.7 ms                                                      | 11.7 ms: 1.00x slower                                      |
| Geometric mean         | (ref)                                                        | 1.00x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 39.3 ms: 1.02x slower                                      |
| Geometric mean  | (ref)                                                        | 1.01x slower                                               |

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| scimark_sparse_mat_mult  | 4.49 ms                                                      | 4.26 ms: 1.05x faster                                      |
| unpickle                 | 15.3 us                                                      | 14.6 us: 1.05x faster                                      |
| pycparser                | 1.29 sec                                                     | 1.24 sec: 1.04x faster                                     |
| regex_effbot             | 3.61 ms                                                      | 3.49 ms: 1.04x faster                                      |
| float                    | 81.6 ms                                                      | 78.9 ms: 1.03x faster                                      |
| coverage                 | 66.3 ms                                                      | 64.2 ms: 1.03x faster                                      |
| scimark_fft              | 303 ms                                                       | 295 ms: 1.03x faster                                       |
| spectral_norm            | 93.9 ms                                                      | 91.5 ms: 1.03x faster                                      |
| fannkuch                 | 362 ms                                                       | 353 ms: 1.03x faster                                       |
| crypto_pyaes             | 82.4 ms                                                      | 80.9 ms: 1.02x faster                                      |
| generators               | 37.3 ms                                                      | 36.7 ms: 1.02x faster                                      |
| regex_compile            | 145 ms                                                       | 143 ms: 1.01x faster                                       |
| scimark_monte_carlo      | 69.5 ms                                                      | 68.8 ms: 1.01x faster                                      |
| json                     | 5.17 ms                                                      | 5.12 ms: 1.01x faster                                      |
| docutils                 | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                     |
| sqlglot_parse            | 1.41 ms                                                      | 1.40 ms: 1.01x faster                                      |
| chameleon                | 7.27 ms                                                      | 7.22 ms: 1.01x faster                                      |
| pprint_pformat           | 1.64 sec                                                     | 1.63 sec: 1.01x faster                                     |
| json_loads               | 24.3 us                                                      | 24.2 us: 1.01x faster                                      |
| sympy_expand             | 492 ms                                                       | 490 ms: 1.00x faster                                       |
| coroutines               | 23.1 ms                                                      | 23.0 ms: 1.00x faster                                      |
| sympy_str                | 305 ms                                                       | 304 ms: 1.00x faster                                       |
| hexiom                   | 5.97 ms                                                      | 5.95 ms: 1.00x faster                                      |
| json_dumps               | 10.3 ms                                                      | 10.2 ms: 1.00x faster                                      |
| sympy_integrate          | 24.0 ms                                                      | 24.0 ms: 1.00x faster                                      |
| python_startup_no_site   | 8.67 ms                                                      | 8.66 ms: 1.00x faster                                      |
| python_startup           | 11.7 ms                                                      | 11.7 ms: 1.00x slower                                      |
| chaos                    | 64.1 ms                                                      | 64.3 ms: 1.00x slower                                      |
| xml_etree_process        | 58.3 ms                                                      | 58.6 ms: 1.00x slower                                      |
| 2to3                     | 285 ms                                                       | 286 ms: 1.00x slower                                       |
| mdp                      | 2.56 sec                                                     | 2.57 sec: 1.00x slower                                     |
| async_tree_io            | 1.06 sec                                                     | 1.06 sec: 1.00x slower                                     |
| logging_silent           | 93.3 ns                                                      | 93.7 ns: 1.00x slower                                      |
| asyncio_tcp              | 380 ms                                                       | 381 ms: 1.01x slower                                       |
| async_tree_none          | 459 ms                                                       | 461 ms: 1.01x slower                                       |
| xml_etree_generate       | 85.3 ms                                                      | 85.8 ms: 1.01x slower                                      |
| deepcopy                 | 371 us                                                       | 374 us: 1.01x slower                                       |
| aiohttp                  | 1.02 ms                                                      | 1.02 ms: 1.01x slower                                      |
| deepcopy_memo            | 36.6 us                                                      | 36.8 us: 1.01x slower                                      |
| tomli_loads              | 2.17 sec                                                     | 2.19 sec: 1.01x slower                                     |
| unpickle_pure_python     | 210 us                                                       | 211 us: 1.01x slower                                       |
| raytrace                 | 301 ms                                                       | 304 ms: 1.01x slower                                       |
| scimark_sor              | 107 ms                                                       | 108 ms: 1.01x slower                                       |
| dulwich_log              | 64.9 ms                                                      | 65.6 ms: 1.01x slower                                      |
| pickle_dict              | 32.0 us                                                      | 32.4 us: 1.01x slower                                      |
| sqlglot_normalize        | 119 ms                                                       | 121 ms: 1.01x slower                                       |
| nqueens                  | 90.1 ms                                                      | 91.3 ms: 1.01x slower                                      |
| async_generators         | 385 ms                                                       | 391 ms: 1.02x slower                                       |
| pickle                   | 10.0 us                                                      | 10.2 us: 1.02x slower                                      |
| django_template          | 38.7 ms                                                      | 39.3 ms: 1.02x slower                                      |
| xml_etree_parse          | 147 ms                                                       | 149 ms: 1.02x slower                                       |
| deltablue                | 3.24 ms                                                      | 3.30 ms: 1.02x slower                                      |
| deepcopy_reduce          | 3.41 us                                                      | 3.48 us: 1.02x slower                                      |
| sqlglot_optimize         | 58.4 ms                                                      | 59.6 ms: 1.02x slower                                      |
| pathlib                  | 18.7 ms                                                      | 19.2 ms: 1.02x slower                                      |
| scimark_lu               | 98.6 ms                                                      | 101 ms: 1.03x slower                                       |
| regex_dna                | 240 ms                                                       | 247 ms: 1.03x slower                                       |
| typing_runtime_protocols | 150 us                                                       | 154 us: 1.03x slower                                       |
| unpickle_list            | 4.65 us                                                      | 4.78 us: 1.03x slower                                      |
| logging_format           | 7.29 us                                                      | 7.51 us: 1.03x slower                                      |
| telco                    | 7.16 ms                                                      | 7.39 ms: 1.03x slower                                      |
| logging_simple           | 6.64 us                                                      | 6.86 us: 1.03x slower                                      |
| meteor_contest           | 126 ms                                                       | 131 ms: 1.04x slower                                       |
| unpack_sequence          | 54.5 ns                                                      | 57.2 ns: 1.05x slower                                      |
| pickle_list              | 4.22 us                                                      | 4.50 us: 1.07x slower                                      |
| mypy2                    | 365 ms                                                       | 458 ms: 1.26x slower                                       |
| bench_mp_pool            | 4.96 ms                                                      | 6.23 ms: 1.26x slower                                      |
| Geometric mean           | (ref)                                                        | 1.01x slower                                               |

Benchmark hidden because not significant (31): nbody, tornado_http, xml_etree_iterparse, richards, gunicorn, async_tree_memoization_tg, gc_traversal, mako, pprint_safe_repr, dask, sqlalchemy_declarative, sqlglot_transpile, async_tree_io_tg, async_tree_none_tg, regex_v8, sqlalchemy_imperative, sympy_sum, pyflate, sqlite_synth, comprehensions, async_tree_cpu_io_mixed_tg, asyncio_tcp_ssl, async_tree_memoization, pidigits, async_tree_cpu_io_mixed, go, asyncio_websockets, create_gc_cycles, pickle_pure_python, richards_super, bench_thread_pool


# HPT report

- Reliability score: 90.66% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
