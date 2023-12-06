
# Results vs. 3.11.0

- fork: python
- ref: 8d32a5c8c4e9c90b0a21
- machine: windows-amd64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.01x slower \*
- HPT reliability: 56.65%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 203 ms: 1.02x faster                                                       |
| chameleon      | 5.35 ms                                                     | 5.45 ms: 1.02x slower                                                      |
| docutils       | 1.59 sec                                                    | 1.57 sec: 1.01x faster                                                     |
| Geometric mean | (ref)                                                       | 1.00x faster                                                               |

Benchmark hidden because not significant (2): html5lib, tornado_http

Benchmarks with tag 'asyncio':
==============================

Benchmark hidden because not significant (4): async_tree_none, async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 67.9 ms: 1.02x faster                                                      |
| float          | 54.4 ms                                                     | 53.5 ms: 1.02x faster                                                      |
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 1.52 ms                                                     | 1.47 ms: 1.03x faster                                                      |
| regex_compile  | 90.8 ms                                                     | 90.5 ms: 1.00x faster                                                      |
| regex_v8       | 13.7 ms                                                     | 13.9 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|---------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_dict         | 17.8 us                                                     | 17.1 us: 1.04x faster                                                      |
| xml_etree_iterparse | 63.0 ms                                                     | 61.1 ms: 1.03x faster                                                      |
| json_dumps          | 7.90 ms                                                     | 7.72 ms: 1.02x faster                                                      |
| pickle_pure_python  | 207 us                                                      | 204 us: 1.02x faster                                                       |
| xml_etree_parse     | 94.5 ms                                                     | 93.1 ms: 1.02x faster                                                      |
| unpickle            | 7.82 us                                                     | 7.87 us: 1.01x slower                                                      |
| pickle              | 6.53 us                                                     | 6.59 us: 1.01x slower                                                      |
| xml_etree_generate  | 52.2 ms                                                     | 53.0 ms: 1.01x slower                                                      |
| xml_etree_process   | 37.0 ms                                                     | 37.6 ms: 1.02x slower                                                      |
| json_loads          | 12.9 us                                                     | 13.4 us: 1.04x slower                                                      |
| Geometric mean      | (ref)                                                       | 1.00x faster                                                               |

Benchmark hidden because not significant (3): pickle_list, unpickle_pure_python, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 18.4 ms: 1.02x faster                                                      |
| python_startup_no_site | 15.5 ms                                                     | 15.2 ms: 1.02x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako           | 7.55 ms                                                     | 7.13 ms: 1.06x faster                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                               |

Benchmark hidden because not significant (3): genshi_xml, genshi_text, django_template

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| logging_simple          | 6.60 us                                                     | 5.80 us: 1.14x faster                                                      |
| logging_format          | 7.06 us                                                     | 6.25 us: 1.13x faster                                                      |
| unpack_sequence         | 47.0 ns                                                     | 42.2 ns: 1.11x faster                                                      |
| create_gc_cycles        | 706 us                                                      | 663 us: 1.06x faster                                                       |
| sqlite_synth            | 1.79 us                                                     | 1.69 us: 1.06x faster                                                      |
| mako                    | 7.55 ms                                                     | 7.13 ms: 1.06x faster                                                      |
| mdp                     | 1.73 sec                                                    | 1.63 sec: 1.06x faster                                                     |
| pickle_dict             | 17.8 us                                                     | 17.1 us: 1.04x faster                                                      |
| raytrace                | 211 ms                                                      | 203 ms: 1.04x faster                                                       |
| dulwich_log             | 44.1 ms                                                     | 42.5 ms: 1.04x faster                                                      |
| regex_effbot            | 1.52 ms                                                     | 1.47 ms: 1.03x faster                                                      |
| sympy_sum               | 100.0 ms                                                    | 96.9 ms: 1.03x faster                                                      |
| xml_etree_iterparse     | 63.0 ms                                                     | 61.1 ms: 1.03x faster                                                      |
| gc_traversal            | 1.46 ms                                                     | 1.42 ms: 1.03x faster                                                      |
| python_startup          | 18.8 ms                                                     | 18.4 ms: 1.02x faster                                                      |
| json_dumps              | 7.90 ms                                                     | 7.72 ms: 1.02x faster                                                      |
| richards                | 30.8 ms                                                     | 30.1 ms: 1.02x faster                                                      |
| sympy_expand            | 299 ms                                                      | 293 ms: 1.02x faster                                                       |
| 2to3                    | 207 ms                                                      | 203 ms: 1.02x faster                                                       |
| nbody                   | 69.3 ms                                                     | 67.9 ms: 1.02x faster                                                      |
| python_startup_no_site  | 15.5 ms                                                     | 15.2 ms: 1.02x faster                                                      |
| float                   | 54.4 ms                                                     | 53.5 ms: 1.02x faster                                                      |
| pickle_pure_python      | 207 us                                                      | 204 us: 1.02x faster                                                       |
| xml_etree_parse         | 94.5 ms                                                     | 93.1 ms: 1.02x faster                                                      |
| deepcopy_memo           | 25.5 us                                                     | 25.1 us: 1.01x faster                                                      |
| pidigits                | 149 ms                                                      | 147 ms: 1.01x faster                                                       |
| docutils                | 1.59 sec                                                    | 1.57 sec: 1.01x faster                                                     |
| go                      | 98.8 ms                                                     | 97.9 ms: 1.01x faster                                                      |
| scimark_fft             | 181 ms                                                      | 180 ms: 1.01x faster                                                       |
| bench_mp_pool           | 61.1 ms                                                     | 60.6 ms: 1.01x faster                                                      |
| sympy_integrate         | 13.7 ms                                                     | 13.6 ms: 1.01x faster                                                      |
| logging_silent          | 70.7 ns                                                     | 70.2 ns: 1.01x faster                                                      |
| sympy_str               | 184 ms                                                      | 183 ms: 1.01x faster                                                       |
| pyflate                 | 305 ms                                                      | 303 ms: 1.01x faster                                                       |
| regex_compile           | 90.8 ms                                                     | 90.5 ms: 1.00x faster                                                      |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.60 ms: 1.01x slower                                                      |
| unpickle                | 7.82 us                                                     | 7.87 us: 1.01x slower                                                      |
| thrift                  | 501 us                                                      | 504 us: 1.01x slower                                                       |
| scimark_lu              | 62.3 ms                                                     | 62.7 ms: 1.01x slower                                                      |
| flaskblogging           | 2.03 sec                                                    | 2.05 sec: 1.01x slower                                                     |
| meteor_contest          | 75.0 ms                                                     | 75.5 ms: 1.01x slower                                                      |
| pickle                  | 6.53 us                                                     | 6.59 us: 1.01x slower                                                      |
| scimark_sor             | 76.4 ms                                                     | 77.1 ms: 1.01x slower                                                      |
| scimark_monte_carlo     | 44.6 ms                                                     | 45.0 ms: 1.01x slower                                                      |
| pprint_safe_repr        | 519 ms                                                      | 525 ms: 1.01x slower                                                       |
| deltablue               | 2.63 ms                                                     | 2.66 ms: 1.01x slower                                                      |
| xml_etree_generate      | 52.2 ms                                                     | 53.0 ms: 1.01x slower                                                      |
| xml_etree_process       | 37.0 ms                                                     | 37.6 ms: 1.02x slower                                                      |
| sqlglot_optimize        | 35.1 ms                                                     | 35.6 ms: 1.02x slower                                                      |
| pprint_pformat          | 1.06 sec                                                    | 1.08 sec: 1.02x slower                                                     |
| regex_v8                | 13.7 ms                                                     | 13.9 ms: 1.02x slower                                                      |
| hexiom                  | 4.51 ms                                                     | 4.59 ms: 1.02x slower                                                      |
| fannkuch                | 248 ms                                                      | 252 ms: 1.02x slower                                                       |
| chameleon               | 5.35 ms                                                     | 5.45 ms: 1.02x slower                                                      |
| crypto_pyaes            | 48.2 ms                                                     | 49.1 ms: 1.02x slower                                                      |
| deepcopy_reduce         | 2.07 us                                                     | 2.12 us: 1.02x slower                                                      |
| nqueens                 | 66.1 ms                                                     | 67.6 ms: 1.02x slower                                                      |
| dask                    | 262 ms                                                      | 268 ms: 1.02x slower                                                       |
| sqlglot_normalize       | 191 ms                                                      | 196 ms: 1.02x slower                                                       |
| pathlib                 | 69.4 ms                                                     | 71.4 ms: 1.03x slower                                                      |
| coroutines              | 14.7 ms                                                     | 15.2 ms: 1.04x slower                                                      |
| json_loads              | 12.9 us                                                     | 13.4 us: 1.04x slower                                                      |
| deepcopy                | 242 us                                                      | 252 us: 1.04x slower                                                       |
| chaos                   | 46.8 ms                                                     | 48.9 ms: 1.05x slower                                                      |
| bench_thread_pool       | 847 us                                                      | 888 us: 1.05x slower                                                       |
| pycparser               | 705 ms                                                      | 748 ms: 1.06x slower                                                       |
| json                    | 2.99 ms                                                     | 3.25 ms: 1.09x slower                                                      |
| asyncio_tcp             | 614 ms                                                      | 673 ms: 1.10x slower                                                       |
| comprehensions          | 15.6 us                                                     | 17.8 us: 1.14x slower                                                      |
| sqlglot_transpile       | 1.15 ms                                                     | 1.37 ms: 1.19x slower                                                      |
| mypy2                   | 226 ms                                                      | 277 ms: 1.22x slower                                                       |
| sqlglot_parse           | 939 us                                                      | 1.15 ms: 1.23x slower                                                      |
| coverage                | 43.0 ms                                                     | 103 ms: 2.39x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (19): genshi_xml, pylint, html5lib, async_tree_none, spectral_norm, async_tree_io, regex_dna, generators, tornado_http, pickle_list, genshi_text, django_template, aiohttp, unpickle_pure_python, telco, unpickle_list, async_tree_cpu_io_mixed, async_tree_memoization, async_generators
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 56.65% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
