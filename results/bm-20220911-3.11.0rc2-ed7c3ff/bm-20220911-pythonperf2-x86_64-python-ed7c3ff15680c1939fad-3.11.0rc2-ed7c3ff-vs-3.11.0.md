
# Results vs. 3.11.0

- fork: python
- ref: ed7c3ff15680c1939fad
- machine: linux-x86_64
- commit hash: ed7c3ff
- commit date: 2022-09-11
- overall geometric mean: 1.00x slower \*
- HPT reliability: 74.84%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 287 ms: 1.00x slower                                                         |
| chameleon      | 7.42 ms                                                      | 7.50 ms: 1.01x slower                                                        |
| html5lib       | 70.7 ms                                                      | 73.2 ms: 1.04x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 529 ms                                                       | 517 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed | 762 ms                                                       | 746 ms: 1.02x faster                                                         |
| async_tree_memoization  | 648 ms                                                       | 636 ms: 1.02x faster                                                         |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.01x faster                                                       |
| Geometric mean          | (ref)                                                        | 1.02x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 89.6 ms: 1.07x faster                                                        |
| float          | 76.0 ms                                                      | 75.1 ms: 1.01x faster                                                        |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                 |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.29 ms: 1.04x faster                                                        |
| regex_dna      | 226 ms                                                       | 225 ms: 1.01x faster                                                         |
| regex_v8       | 23.7 ms                                                      | 24.3 ms: 1.03x slower                                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_dict          | 31.8 us                                                      | 30.7 us: 1.04x faster                                                        |
| pickle_list          | 3.89 us                                                      | 3.77 us: 1.03x faster                                                        |
| xml_etree_iterparse  | 106 ms                                                       | 104 ms: 1.02x faster                                                         |
| json_loads           | 29.0 us                                                      | 28.4 us: 1.02x faster                                                        |
| pickle               | 9.77 us                                                      | 9.61 us: 1.02x faster                                                        |
| unpickle             | 13.2 us                                                      | 13.0 us: 1.01x faster                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 80.8 ms: 1.00x slower                                                        |
| xml_etree_parse      | 159 ms                                                       | 160 ms: 1.01x slower                                                         |
| xml_etree_process    | 56.1 ms                                                      | 57.0 ms: 1.02x slower                                                        |
| pickle_pure_python   | 318 us                                                       | 324 us: 1.02x slower                                                         |
| unpickle_list        | 4.47 us                                                      | 4.72 us: 1.06x slower                                                        |
| unpickle_pure_python | 236 us                                                       | 250 us: 1.06x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (1): json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.7 ms: 1.01x faster                                                        |
| python_startup_no_site | 7.78 ms                                                      | 7.72 ms: 1.01x faster                                                        |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| django_template | 40.4 ms                                                      | 39.7 ms: 1.02x faster                                                        |
| mako            | 11.0 ms                                                      | 10.9 ms: 1.01x faster                                                        |
| genshi_xml      | 57.2 ms                                                      | 59.2 ms: 1.03x slower                                                        |
| Geometric mean  | (ref)                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (1): genshi_text

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| gc_traversal            | 4.06 ms                                                      | 3.63 ms: 1.12x faster                                                        |
| nbody                   | 95.8 ms                                                      | 89.6 ms: 1.07x faster                                                        |
| gunicorn                | 986 us                                                       | 941 us: 1.05x faster                                                         |
| generators              | 56.4 ms                                                      | 54.2 ms: 1.04x faster                                                        |
| thrift                  | 941 us                                                       | 906 us: 1.04x faster                                                         |
| regex_effbot            | 3.42 ms                                                      | 3.29 ms: 1.04x faster                                                        |
| fannkuch                | 457 ms                                                       | 441 ms: 1.04x faster                                                         |
| pickle_dict             | 31.8 us                                                      | 30.7 us: 1.04x faster                                                        |
| pickle_list             | 3.89 us                                                      | 3.77 us: 1.03x faster                                                        |
| flaskblogging           | 3.92 ms                                                      | 3.80 ms: 1.03x faster                                                        |
| scimark_monte_carlo     | 70.6 ms                                                      | 68.7 ms: 1.03x faster                                                        |
| async_tree_none         | 529 ms                                                       | 517 ms: 1.02x faster                                                         |
| xml_etree_iterparse     | 106 ms                                                       | 104 ms: 1.02x faster                                                         |
| async_tree_cpu_io_mixed | 762 ms                                                       | 746 ms: 1.02x faster                                                         |
| json_loads              | 29.0 us                                                      | 28.4 us: 1.02x faster                                                        |
| async_tree_memoization  | 648 ms                                                       | 636 ms: 1.02x faster                                                         |
| django_template         | 40.4 ms                                                      | 39.7 ms: 1.02x faster                                                        |
| aiohttp                 | 984 us                                                       | 966 us: 1.02x faster                                                         |
| pickle                  | 9.77 us                                                      | 9.61 us: 1.02x faster                                                        |
| unpickle                | 13.2 us                                                      | 13.0 us: 1.01x faster                                                        |
| scimark_fft             | 281 ms                                                       | 277 ms: 1.01x faster                                                         |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.01x faster                                                       |
| scimark_lu              | 115 ms                                                       | 114 ms: 1.01x faster                                                         |
| float                   | 76.0 ms                                                      | 75.1 ms: 1.01x faster                                                        |
| logging_silent          | 102 ns                                                       | 101 ns: 1.01x faster                                                         |
| python_startup          | 10.8 ms                                                      | 10.7 ms: 1.01x faster                                                        |
| sqlglot_transpile       | 1.94 ms                                                      | 1.92 ms: 1.01x faster                                                        |
| mako                    | 11.0 ms                                                      | 10.9 ms: 1.01x faster                                                        |
| python_startup_no_site  | 7.78 ms                                                      | 7.72 ms: 1.01x faster                                                        |
| sqlglot_optimize        | 59.2 ms                                                      | 58.8 ms: 1.01x faster                                                        |
| sympy_sum               | 184 ms                                                       | 183 ms: 1.01x faster                                                         |
| sqlglot_normalize       | 122 ms                                                       | 121 ms: 1.01x faster                                                         |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 4.01 ms: 1.01x faster                                                        |
| regex_dna               | 226 ms                                                       | 225 ms: 1.01x faster                                                         |
| sympy_expand            | 550 ms                                                       | 553 ms: 1.00x slower                                                         |
| 2to3                    | 286 ms                                                       | 287 ms: 1.00x slower                                                         |
| sympy_str               | 336 ms                                                       | 337 ms: 1.00x slower                                                         |
| xml_etree_generate      | 80.5 ms                                                      | 80.8 ms: 1.00x slower                                                        |
| sqlglot_parse           | 1.55 ms                                                      | 1.56 ms: 1.01x slower                                                        |
| pprint_pformat          | 1.63 sec                                                     | 1.65 sec: 1.01x slower                                                       |
| xml_etree_parse         | 159 ms                                                       | 160 ms: 1.01x slower                                                         |
| chameleon               | 7.42 ms                                                      | 7.50 ms: 1.01x slower                                                        |
| sympy_integrate         | 25.6 ms                                                      | 25.9 ms: 1.01x slower                                                        |
| pprint_safe_repr        | 780 ms                                                       | 791 ms: 1.01x slower                                                         |
| meteor_contest          | 130 ms                                                       | 132 ms: 1.02x slower                                                         |
| spectral_norm           | 94.0 ms                                                      | 95.5 ms: 1.02x slower                                                        |
| xml_etree_process       | 56.1 ms                                                      | 57.0 ms: 1.02x slower                                                        |
| deltablue               | 4.03 ms                                                      | 4.09 ms: 1.02x slower                                                        |
| pickle_pure_python      | 318 us                                                       | 324 us: 1.02x slower                                                         |
| unpack_sequence         | 44.9 ns                                                      | 45.7 ns: 1.02x slower                                                        |
| dulwich_log             | 68.3 ms                                                      | 69.6 ms: 1.02x slower                                                        |
| async_generators        | 322 ms                                                       | 328 ms: 1.02x slower                                                         |
| nqueens                 | 99.2 ms                                                      | 101 ms: 1.02x slower                                                         |
| hexiom                  | 6.97 ms                                                      | 7.12 ms: 1.02x slower                                                        |
| logging_format          | 7.83 us                                                      | 8.03 us: 1.03x slower                                                        |
| comprehensions          | 24.8 us                                                      | 25.5 us: 1.03x slower                                                        |
| regex_v8                | 23.7 ms                                                      | 24.3 ms: 1.03x slower                                                        |
| logging_simple          | 7.21 us                                                      | 7.43 us: 1.03x slower                                                        |
| crypto_pyaes            | 81.8 ms                                                      | 84.3 ms: 1.03x slower                                                        |
| genshi_xml              | 57.2 ms                                                      | 59.2 ms: 1.03x slower                                                        |
| go                      | 166 ms                                                       | 172 ms: 1.04x slower                                                         |
| html5lib                | 70.7 ms                                                      | 73.2 ms: 1.04x slower                                                        |
| deepcopy_reduce         | 3.37 us                                                      | 3.51 us: 1.04x slower                                                        |
| create_gc_cycles        | 1.59 ms                                                      | 1.66 ms: 1.04x slower                                                        |
| pycparser               | 1.28 sec                                                     | 1.34 sec: 1.04x slower                                                       |
| deepcopy                | 389 us                                                       | 407 us: 1.05x slower                                                         |
| unpickle_list           | 4.47 us                                                      | 4.72 us: 1.06x slower                                                        |
| unpickle_pure_python    | 236 us                                                       | 250 us: 1.06x slower                                                         |
| richards                | 49.9 ms                                                      | 53.5 ms: 1.07x slower                                                        |
| deepcopy_memo           | 37.3 us                                                      | 41.0 us: 1.10x slower                                                        |
| chaos                   | 71.6 ms                                                      | 81.4 ms: 1.14x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (23): bench_mp_pool, bench_thread_pool, pyflate, telco, docutils, json, sqlite_synth, pylint, genshi_text, mdp, raytrace, sqlalchemy_imperative, pathlib, asyncio_tcp, json_dumps, pidigits, coroutines, sqlalchemy_declarative, tornado_http, regex_compile, scimark_sor, mypy2, dask
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 74.84% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
