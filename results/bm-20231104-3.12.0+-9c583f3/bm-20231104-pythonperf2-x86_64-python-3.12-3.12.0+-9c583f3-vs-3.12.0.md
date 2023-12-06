
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.00x faster \*
- HPT reliability: 99.58%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 286 ms: 1.00x slower                                       |
| docutils       | 2.89 sec                                                     | 2.85 sec: 1.01x faster                                     |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|--------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none_tg | 440 ms                                                       | 437 ms: 1.01x faster                                       |
| async_tree_io_tg   | 1.07 sec                                                     | 1.07 sec: 1.00x faster                                     |
| Geometric mean     | (ref)                                                        | 1.00x faster                                               |

Benchmark hidden because not significant (6): async_tree_memoization_tg, async_tree_none, async_tree_io, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 88.2 ms                                                      | 83.2 ms: 1.06x faster                                      |
| float          | 81.6 ms                                                      | 77.7 ms: 1.05x faster                                      |
| Geometric mean | (ref)                                                        | 1.04x faster                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 145 ms                                                       | 139 ms: 1.04x faster                                       |
| regex_effbot   | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                      |
| regex_v8       | 24.4 ms                                                      | 24.2 ms: 1.01x faster                                      |
| regex_dna      | 240 ms                                                       | 244 ms: 1.02x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.9 us: 1.03x faster                                      |
| json_dumps           | 10.3 ms                                                      | 10.2 ms: 1.01x faster                                      |
| unpickle_pure_python | 210 us                                                       | 210 us: 1.00x slower                                       |
| xml_etree_generate   | 85.3 ms                                                      | 86.0 ms: 1.01x slower                                      |
| pickle_pure_python   | 319 us                                                       | 324 us: 1.01x slower                                       |
| pickle               | 10.0 us                                                      | 10.2 us: 1.02x slower                                      |
| pickle_dict          | 32.0 us                                                      | 32.6 us: 1.02x slower                                      |
| unpickle_list        | 4.65 us                                                      | 4.75 us: 1.02x slower                                      |
| tomli_loads          | 2.17 sec                                                     | 2.23 sec: 1.03x slower                                     |
| pickle_list          | 4.22 us                                                      | 4.57 us: 1.08x slower                                      |
| Geometric mean       | (ref)                                                        | 1.01x slower                                               |

Benchmark hidden because not significant (4): xml_etree_process, xml_etree_iterparse, json_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 8.63 ms: 1.01x faster                                      |
| python_startup         | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                      |
| Geometric mean         | (ref)                                                        | 1.00x faster                                               |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (2): mako, django_template

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0+-9c583f3 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 150 us                                                       | 122 us: 1.23x faster                                       |
| nbody                    | 88.2 ms                                                      | 83.2 ms: 1.06x faster                                      |
| float                    | 81.6 ms                                                      | 77.7 ms: 1.05x faster                                      |
| pycparser                | 1.29 sec                                                     | 1.23 sec: 1.05x faster                                     |
| gc_traversal             | 3.70 ms                                                      | 3.55 ms: 1.04x faster                                      |
| regex_compile            | 145 ms                                                       | 139 ms: 1.04x faster                                       |
| fannkuch                 | 362 ms                                                       | 348 ms: 1.04x faster                                       |
| comprehensions           | 21.8 us                                                      | 21.0 us: 1.04x faster                                      |
| scimark_fft              | 303 ms                                                       | 294 ms: 1.03x faster                                       |
| regex_effbot             | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                      |
| scimark_sparse_mat_mult  | 4.49 ms                                                      | 4.35 ms: 1.03x faster                                      |
| chaos                    | 64.1 ms                                                      | 62.1 ms: 1.03x faster                                      |
| unpickle                 | 15.3 us                                                      | 14.9 us: 1.03x faster                                      |
| spectral_norm            | 93.9 ms                                                      | 91.3 ms: 1.03x faster                                      |
| sqlglot_normalize        | 119 ms                                                       | 116 ms: 1.03x faster                                       |
| coverage                 | 66.3 ms                                                      | 64.9 ms: 1.02x faster                                      |
| generators               | 37.3 ms                                                      | 36.5 ms: 1.02x faster                                      |
| sqlglot_parse            | 1.41 ms                                                      | 1.38 ms: 1.02x faster                                      |
| sympy_integrate          | 24.0 ms                                                      | 23.6 ms: 1.02x faster                                      |
| logging_silent           | 93.3 ns                                                      | 91.8 ns: 1.02x faster                                      |
| docutils                 | 2.89 sec                                                     | 2.85 sec: 1.01x faster                                     |
| raytrace                 | 301 ms                                                       | 297 ms: 1.01x faster                                       |
| sympy_str                | 305 ms                                                       | 301 ms: 1.01x faster                                       |
| tornado_http             | 122 ms                                                       | 120 ms: 1.01x faster                                       |
| sympy_sum                | 163 ms                                                       | 161 ms: 1.01x faster                                       |
| json                     | 5.17 ms                                                      | 5.11 ms: 1.01x faster                                      |
| pprint_safe_repr         | 808 ms                                                       | 798 ms: 1.01x faster                                       |
| unpack_sequence          | 54.5 ns                                                      | 53.9 ns: 1.01x faster                                      |
| sqlglot_transpile        | 1.80 ms                                                      | 1.79 ms: 1.01x faster                                      |
| deepcopy                 | 371 us                                                       | 368 us: 1.01x faster                                       |
| pprint_pformat           | 1.64 sec                                                     | 1.63 sec: 1.01x faster                                     |
| scimark_monte_carlo      | 69.5 ms                                                      | 68.9 ms: 1.01x faster                                      |
| regex_v8                 | 24.4 ms                                                      | 24.2 ms: 1.01x faster                                      |
| sqlalchemy_declarative   | 161 ms                                                       | 159 ms: 1.01x faster                                       |
| sqlglot_optimize         | 58.4 ms                                                      | 58.0 ms: 1.01x faster                                      |
| json_dumps               | 10.3 ms                                                      | 10.2 ms: 1.01x faster                                      |
| mdp                      | 2.56 sec                                                     | 2.54 sec: 1.01x faster                                     |
| async_tree_none_tg       | 440 ms                                                       | 437 ms: 1.01x faster                                       |
| nqueens                  | 90.1 ms                                                      | 89.6 ms: 1.01x faster                                      |
| python_startup_no_site   | 8.67 ms                                                      | 8.63 ms: 1.01x faster                                      |
| crypto_pyaes             | 82.4 ms                                                      | 82.0 ms: 1.01x faster                                      |
| async_tree_io_tg         | 1.07 sec                                                     | 1.07 sec: 1.00x faster                                     |
| sympy_expand             | 492 ms                                                       | 489 ms: 1.00x faster                                       |
| python_startup           | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                      |
| asyncio_tcp_ssl          | 1.57 sec                                                     | 1.58 sec: 1.00x slower                                     |
| unpickle_pure_python     | 210 us                                                       | 210 us: 1.00x slower                                       |
| 2to3                     | 285 ms                                                       | 286 ms: 1.00x slower                                       |
| aiohttp                  | 1.02 ms                                                      | 1.02 ms: 1.01x slower                                      |
| xml_etree_generate       | 85.3 ms                                                      | 86.0 ms: 1.01x slower                                      |
| coroutines               | 23.1 ms                                                      | 23.2 ms: 1.01x slower                                      |
| richards_super           | 50.8 ms                                                      | 51.3 ms: 1.01x slower                                      |
| pickle_pure_python       | 319 us                                                       | 324 us: 1.01x slower                                       |
| async_generators         | 385 ms                                                       | 390 ms: 1.01x slower                                       |
| create_gc_cycles         | 1.58 ms                                                      | 1.60 ms: 1.01x slower                                      |
| deltablue                | 3.24 ms                                                      | 3.29 ms: 1.02x slower                                      |
| regex_dna                | 240 ms                                                       | 244 ms: 1.02x slower                                       |
| pickle                   | 10.0 us                                                      | 10.2 us: 1.02x slower                                      |
| pickle_dict              | 32.0 us                                                      | 32.6 us: 1.02x slower                                      |
| scimark_sor              | 107 ms                                                       | 109 ms: 1.02x slower                                       |
| unpickle_list            | 4.65 us                                                      | 4.75 us: 1.02x slower                                      |
| tomli_loads              | 2.17 sec                                                     | 2.23 sec: 1.03x slower                                     |
| meteor_contest           | 126 ms                                                       | 130 ms: 1.03x slower                                       |
| pathlib                  | 18.7 ms                                                      | 19.4 ms: 1.03x slower                                      |
| logging_simple           | 6.64 us                                                      | 6.91 us: 1.04x slower                                      |
| logging_format           | 7.29 us                                                      | 7.61 us: 1.04x slower                                      |
| telco                    | 7.16 ms                                                      | 7.59 ms: 1.06x slower                                      |
| pickle_list              | 4.22 us                                                      | 4.57 us: 1.08x slower                                      |
| bench_mp_pool            | 4.96 ms                                                      | 5.86 ms: 1.18x slower                                      |
| mypy2                    | 365 ms                                                       | 457 ms: 1.25x slower                                       |
| Geometric mean           | (ref)                                                        | 1.00x faster                                               |

Benchmark hidden because not significant (29): mako, richards, async_tree_memoization_tg, gunicorn, asyncio_tcp, xml_etree_process, chameleon, async_tree_none, async_tree_io, async_tree_memoization, dulwich_log, deepcopy_memo, pyflate, pidigits, xml_etree_iterparse, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, django_template, hexiom, go, dask, asyncio_websockets, json_loads, bench_thread_pool, scimark_lu, deepcopy_reduce, xml_etree_parse, sqlalchemy_imperative, sqlite_synth


# HPT report

- Reliability score: 99.58% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
