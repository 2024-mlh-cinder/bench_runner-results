
# Results vs. 3.11.0

- fork: python
- ref: v3.11.4
- machine: linux-x86_64
- commit hash: d2340ef
- commit date: 2023-06-06
- overall geometric mean: 1.00x faster \*
- HPT reliability: 99.69%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 285 ms: 1.00x faster                                         |
| chameleon      | 7.42 ms                                                      | 7.63 ms: 1.03x slower                                        |
| docutils       | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                       |
| tornado_http   | 125 ms                                                       | 121 ms: 1.03x faster                                         |
| Geometric mean | (ref)                                                        | 1.00x faster                                                 |

Benchmark hidden because not significant (1): html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_memoization | 648 ms                                                       | 630 ms: 1.03x faster                                         |
| async_tree_io          | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                       |
| async_tree_none        | 529 ms                                                       | 522 ms: 1.01x faster                                         |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                 |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 76.0 ms                                                      | 73.8 ms: 1.03x faster                                        |
| pidigits       | 251 ms                                                       | 252 ms: 1.00x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 155 ms: 1.01x faster                                         |
| regex_effbot   | 3.42 ms                                                      | 3.46 ms: 1.01x slower                                        |
| regex_dna      | 226 ms                                                       | 231 ms: 1.02x slower                                         |
| regex_v8       | 23.7 ms                                                      | 24.5 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_dict          | 31.8 us                                                      | 29.7 us: 1.07x faster                                        |
| pickle_list          | 3.89 us                                                      | 3.70 us: 1.05x faster                                        |
| json_loads           | 29.0 us                                                      | 28.4 us: 1.02x faster                                        |
| unpickle             | 13.2 us                                                      | 13.0 us: 1.02x faster                                        |
| xml_etree_iterparse  | 106 ms                                                       | 105 ms: 1.01x faster                                         |
| json_dumps           | 13.5 ms                                                      | 13.4 ms: 1.00x faster                                        |
| xml_etree_generate   | 80.5 ms                                                      | 81.0 ms: 1.01x slower                                        |
| pickle_pure_python   | 318 us                                                       | 321 us: 1.01x slower                                         |
| pickle               | 9.77 us                                                      | 9.96 us: 1.02x slower                                        |
| unpickle_pure_python | 236 us                                                       | 243 us: 1.03x slower                                         |
| unpickle_list        | 4.47 us                                                      | 4.69 us: 1.05x slower                                        |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                 |

Benchmark hidden because not significant (3): tomli_loads, xml_etree_parse, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.7 ms: 1.01x faster                                        |
| python_startup_no_site | 7.78 ms                                                      | 7.72 ms: 1.01x faster                                        |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako            | 11.0 ms                                                      | 10.8 ms: 1.02x faster                                        |
| genshi_text     | 26.1 ms                                                      | 25.6 ms: 1.02x faster                                        |
| django_template | 40.4 ms                                                      | 39.7 ms: 1.02x faster                                        |
| genshi_xml      | 57.2 ms                                                      | 57.9 ms: 1.01x slower                                        |
| Geometric mean  | (ref)                                                        | 1.01x faster                                                 |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| gc_traversal            | 4.06 ms                                                      | 3.70 ms: 1.10x faster                                        |
| pickle_dict             | 31.8 us                                                      | 29.7 us: 1.07x faster                                        |
| pickle_list             | 3.89 us                                                      | 3.70 us: 1.05x faster                                        |
| fannkuch                | 457 ms                                                       | 441 ms: 1.04x faster                                         |
| dask                    | 417 ms                                                       | 402 ms: 1.04x faster                                         |
| tornado_http            | 125 ms                                                       | 121 ms: 1.03x faster                                         |
| logging_format          | 7.83 us                                                      | 7.58 us: 1.03x faster                                        |
| thrift                  | 941 us                                                       | 912 us: 1.03x faster                                         |
| generators              | 56.4 ms                                                      | 54.7 ms: 1.03x faster                                        |
| float                   | 76.0 ms                                                      | 73.8 ms: 1.03x faster                                        |
| async_tree_memoization  | 648 ms                                                       | 630 ms: 1.03x faster                                         |
| bench_thread_pool       | 1.02 ms                                                      | 995 us: 1.02x faster                                         |
| telco                   | 6.91 ms                                                      | 6.75 ms: 1.02x faster                                        |
| logging_simple          | 7.21 us                                                      | 7.05 us: 1.02x faster                                        |
| pylint                  | 521 ms                                                       | 510 ms: 1.02x faster                                         |
| mako                    | 11.0 ms                                                      | 10.8 ms: 1.02x faster                                        |
| json                    | 5.59 ms                                                      | 5.48 ms: 1.02x faster                                        |
| json_loads              | 29.0 us                                                      | 28.4 us: 1.02x faster                                        |
| genshi_text             | 26.1 ms                                                      | 25.6 ms: 1.02x faster                                        |
| django_template         | 40.4 ms                                                      | 39.7 ms: 1.02x faster                                        |
| scimark_lu              | 115 ms                                                       | 113 ms: 1.02x faster                                         |
| unpickle                | 13.2 us                                                      | 13.0 us: 1.02x faster                                        |
| sqlalchemy_imperative   | 19.9 ms                                                      | 19.6 ms: 1.02x faster                                        |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                       |
| scimark_monte_carlo     | 70.6 ms                                                      | 69.5 ms: 1.01x faster                                        |
| python_startup          | 10.8 ms                                                      | 10.7 ms: 1.01x faster                                        |
| sqlglot_transpile       | 1.94 ms                                                      | 1.91 ms: 1.01x faster                                        |
| docutils                | 2.87 sec                                                     | 2.83 sec: 1.01x faster                                       |
| regex_compile           | 157 ms                                                       | 155 ms: 1.01x faster                                         |
| async_tree_none         | 529 ms                                                       | 522 ms: 1.01x faster                                         |
| xml_etree_iterparse     | 106 ms                                                       | 105 ms: 1.01x faster                                         |
| flaskblogging           | 3.92 ms                                                      | 3.87 ms: 1.01x faster                                        |
| pathlib                 | 19.1 ms                                                      | 18.9 ms: 1.01x faster                                        |
| dulwich_log             | 68.3 ms                                                      | 67.6 ms: 1.01x faster                                        |
| logging_silent          | 102 ns                                                       | 101 ns: 1.01x faster                                         |
| pprint_pformat          | 1.63 sec                                                     | 1.62 sec: 1.01x faster                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.72 ms: 1.01x faster                                        |
| sqlglot_optimize        | 59.2 ms                                                      | 58.7 ms: 1.01x faster                                        |
| nqueens                 | 99.2 ms                                                      | 98.5 ms: 1.01x faster                                        |
| sympy_sum               | 184 ms                                                       | 183 ms: 1.01x faster                                         |
| sympy_str               | 336 ms                                                       | 334 ms: 1.01x faster                                         |
| asyncio_tcp_ssl         | 3.09 sec                                                     | 3.07 sec: 1.01x faster                                       |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 4.01 ms: 1.01x faster                                        |
| sqlglot_parse           | 1.55 ms                                                      | 1.55 ms: 1.01x faster                                        |
| json_dumps              | 13.5 ms                                                      | 13.4 ms: 1.00x faster                                        |
| sqlglot_normalize       | 122 ms                                                       | 122 ms: 1.00x faster                                         |
| meteor_contest          | 130 ms                                                       | 130 ms: 1.00x faster                                         |
| 2to3                    | 286 ms                                                       | 285 ms: 1.00x faster                                         |
| pidigits                | 251 ms                                                       | 252 ms: 1.00x slower                                         |
| pprint_safe_repr        | 780 ms                                                       | 784 ms: 1.01x slower                                         |
| xml_etree_generate      | 80.5 ms                                                      | 81.0 ms: 1.01x slower                                        |
| pickle_pure_python      | 318 us                                                       | 321 us: 1.01x slower                                         |
| deltablue               | 4.03 ms                                                      | 4.06 ms: 1.01x slower                                        |
| raytrace                | 308 ms                                                       | 311 ms: 1.01x slower                                         |
| genshi_xml              | 57.2 ms                                                      | 57.9 ms: 1.01x slower                                        |
| hexiom                  | 6.97 ms                                                      | 7.06 ms: 1.01x slower                                        |
| regex_effbot            | 3.42 ms                                                      | 3.46 ms: 1.01x slower                                        |
| unpack_sequence         | 44.9 ns                                                      | 45.6 ns: 1.01x slower                                        |
| crypto_pyaes            | 81.8 ms                                                      | 83.1 ms: 1.02x slower                                        |
| regex_dna               | 226 ms                                                       | 231 ms: 1.02x slower                                         |
| pickle                  | 9.77 us                                                      | 9.96 us: 1.02x slower                                        |
| deepcopy_memo           | 37.3 us                                                      | 38.1 us: 1.02x slower                                        |
| create_gc_cycles        | 1.59 ms                                                      | 1.63 ms: 1.02x slower                                        |
| go                      | 166 ms                                                       | 170 ms: 1.03x slower                                         |
| chameleon               | 7.42 ms                                                      | 7.63 ms: 1.03x slower                                        |
| unpickle_pure_python    | 236 us                                                       | 243 us: 1.03x slower                                         |
| regex_v8                | 23.7 ms                                                      | 24.5 ms: 1.03x slower                                        |
| richards                | 49.9 ms                                                      | 52.2 ms: 1.05x slower                                        |
| chaos                   | 71.6 ms                                                      | 75.0 ms: 1.05x slower                                        |
| scimark_sor             | 109 ms                                                       | 115 ms: 1.05x slower                                         |
| unpickle_list           | 4.47 us                                                      | 4.69 us: 1.05x slower                                        |
| mdp                     | 2.72 sec                                                     | 2.86 sec: 1.05x slower                                       |
| mypy2                   | 449 ms                                                       | 535 ms: 1.19x slower                                         |
| Geometric mean          | (ref)                                                        | 1.00x faster                                                 |

Benchmark hidden because not significant (25): bench_mp_pool, deepcopy, async_tree_cpu_io_mixed, gunicorn, aiohttp, sqlite_synth, typing_runtime_protocols, sqlalchemy_declarative, nbody, coroutines, tomli_loads, asyncio_tcp, scimark_fft, sympy_expand, richards_super, pycparser, sympy_integrate, async_generators, spectral_norm, xml_etree_parse, xml_etree_process, comprehensions, deepcopy_reduce, html5lib, pyflate
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage


# HPT report

- Reliability score: 99.69% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
