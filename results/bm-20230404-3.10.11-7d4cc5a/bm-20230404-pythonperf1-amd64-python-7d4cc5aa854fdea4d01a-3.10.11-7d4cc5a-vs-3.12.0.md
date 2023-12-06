
# Results vs. 3.12.0

- fork: python
- ref: 7d4cc5aa854fdea4d01a
- machine: windows-amd64
- commit hash: 7d4cc5a
- commit date: 2023-04-04
- overall geometric mean: 1.17x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 233 ms: 1.09x slower                                                      |
| docutils       | 1.63 sec                                                    | 1.82 sec: 1.12x slower                                                    |
| tornado_http   | 87.7 ms                                                     | 108 ms: 1.23x slower                                                      |
| Geometric mean | (ref)                                                       | 1.14x slower                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                      |
| nbody          | 72.6 ms                                                     | 75.5 ms: 1.04x slower                                                     |
| float          | 55.1 ms                                                     | 60.7 ms: 1.10x slower                                                     |
| Geometric mean | (ref)                                                       | 1.04x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_effbot   | 1.62 ms                                                     | 1.60 ms: 1.01x faster                                                     |
| regex_dna      | 124 ms                                                      | 129 ms: 1.04x slower                                                      |
| regex_v8       | 13.9 ms                                                     | 14.6 ms: 1.05x slower                                                     |
| regex_compile  | 88.3 ms                                                     | 102 ms: 1.16x slower                                                      |
| Geometric mean | (ref)                                                       | 1.06x slower                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.66 us: 1.05x faster                                                     |
| pickle_dict          | 19.3 us                                                     | 18.7 us: 1.03x faster                                                     |
| xml_etree_generate   | 55.6 ms                                                     | 54.3 ms: 1.02x faster                                                     |
| xml_etree_iterparse  | 62.5 ms                                                     | 63.4 ms: 1.01x slower                                                     |
| json_loads           | 13.4 us                                                     | 13.7 us: 1.02x slower                                                     |
| pickle               | 7.13 us                                                     | 7.34 us: 1.03x slower                                                     |
| xml_etree_parse      | 89.2 ms                                                     | 96.4 ms: 1.08x slower                                                     |
| xml_etree_process    | 38.4 ms                                                     | 43.5 ms: 1.13x slower                                                     |
| unpickle             | 8.16 us                                                     | 9.30 us: 1.14x slower                                                     |
| unpickle_pure_python | 133 us                                                      | 177 us: 1.33x slower                                                      |
| pickle_pure_python   | 196 us                                                      | 266 us: 1.36x slower                                                      |
| json_dumps           | 5.60 ms                                                     | 8.90 ms: 1.59x slower                                                     |
| Geometric mean       | (ref)                                                       | 1.11x slower                                                              |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 15.6 ms: 1.03x faster                                                     |
| python_startup         | 19.5 ms                                                     | 21.1 ms: 1.08x slower                                                     |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 8.76 ms: 1.26x slower                                                     |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|-------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| coverage                | 51.5 ms                                                     | 39.2 ms: 1.31x faster                                                     |
| bench_mp_pool           | 66.4 ms                                                     | 60.4 ms: 1.10x faster                                                     |
| async_generators        | 235 ms                                                      | 218 ms: 1.08x faster                                                      |
| gc_traversal            | 1.48 ms                                                     | 1.42 ms: 1.05x faster                                                     |
| unpickle_list           | 2.78 us                                                     | 2.66 us: 1.05x faster                                                     |
| telco                   | 4.09 ms                                                     | 3.93 ms: 1.04x faster                                                     |
| pathlib                 | 77.1 ms                                                     | 74.4 ms: 1.04x faster                                                     |
| python_startup_no_site  | 16.1 ms                                                     | 15.6 ms: 1.03x faster                                                     |
| pickle_dict             | 19.3 us                                                     | 18.7 us: 1.03x faster                                                     |
| pidigits                | 150 ms                                                      | 147 ms: 1.02x faster                                                      |
| xml_etree_generate      | 55.6 ms                                                     | 54.3 ms: 1.02x faster                                                     |
| meteor_contest          | 73.1 ms                                                     | 72.1 ms: 1.01x faster                                                     |
| regex_effbot            | 1.62 ms                                                     | 1.60 ms: 1.01x faster                                                     |
| logging_simple          | 6.21 us                                                     | 6.28 us: 1.01x slower                                                     |
| logging_format          | 6.67 us                                                     | 6.76 us: 1.01x slower                                                     |
| xml_etree_iterparse     | 62.5 ms                                                     | 63.4 ms: 1.01x slower                                                     |
| json_loads              | 13.4 us                                                     | 13.7 us: 1.02x slower                                                     |
| pickle                  | 7.13 us                                                     | 7.34 us: 1.03x slower                                                     |
| nbody                   | 72.6 ms                                                     | 75.5 ms: 1.04x slower                                                     |
| regex_dna               | 124 ms                                                      | 129 ms: 1.04x slower                                                      |
| sqlite_synth            | 1.76 us                                                     | 1.84 us: 1.05x slower                                                     |
| regex_v8                | 13.9 ms                                                     | 14.6 ms: 1.05x slower                                                     |
| json                    | 2.86 ms                                                     | 3.02 ms: 1.06x slower                                                     |
| create_gc_cycles        | 727 us                                                      | 777 us: 1.07x slower                                                      |
| xml_etree_parse         | 89.2 ms                                                     | 96.4 ms: 1.08x slower                                                     |
| python_startup          | 19.5 ms                                                     | 21.1 ms: 1.08x slower                                                     |
| deepcopy                | 240 us                                                      | 260 us: 1.08x slower                                                      |
| sqlglot_normalize       | 185 ms                                                      | 202 ms: 1.09x slower                                                      |
| 2to3                    | 214 ms                                                      | 233 ms: 1.09x slower                                                      |
| bench_thread_pool       | 844 us                                                      | 928 us: 1.10x slower                                                      |
| float                   | 55.1 ms                                                     | 60.7 ms: 1.10x slower                                                     |
| comprehensions          | 14.1 us                                                     | 15.6 us: 1.10x slower                                                     |
| nqueens                 | 61.2 ms                                                     | 67.5 ms: 1.10x slower                                                     |
| aiohttp                 | 865 us                                                      | 962 us: 1.11x slower                                                      |
| docutils                | 1.63 sec                                                    | 1.82 sec: 1.12x slower                                                    |
| coroutines              | 14.0 ms                                                     | 15.7 ms: 1.12x slower                                                     |
| sqlglot_optimize        | 34.4 ms                                                     | 38.5 ms: 1.12x slower                                                     |
| dulwich_log             | 42.4 ms                                                     | 47.6 ms: 1.12x slower                                                     |
| unpack_sequence         | 37.5 ns                                                     | 42.1 ns: 1.12x slower                                                     |
| scimark_fft             | 180 ms                                                      | 203 ms: 1.13x slower                                                      |
| xml_etree_process       | 38.4 ms                                                     | 43.5 ms: 1.13x slower                                                     |
| unpickle                | 8.16 us                                                     | 9.30 us: 1.14x slower                                                     |
| pprint_safe_repr        | 512 ms                                                      | 584 ms: 1.14x slower                                                      |
| scimark_sparse_mat_mult | 2.48 ms                                                     | 2.83 ms: 1.14x slower                                                     |
| pprint_pformat          | 1.04 sec                                                    | 1.19 sec: 1.14x slower                                                    |
| regex_compile           | 88.3 ms                                                     | 102 ms: 1.16x slower                                                      |
| fannkuch                | 237 ms                                                      | 276 ms: 1.17x slower                                                      |
| dask                    | 259 ms                                                      | 303 ms: 1.17x slower                                                      |
| mdp                     | 1.44 sec                                                    | 1.71 sec: 1.19x slower                                                    |
| deepcopy_memo           | 23.8 us                                                     | 28.6 us: 1.20x slower                                                     |
| tornado_http            | 87.7 ms                                                     | 108 ms: 1.23x slower                                                      |
| pycparser               | 673 ms                                                      | 839 ms: 1.25x slower                                                      |
| async_tree_cpu_io_mixed | 479 ms                                                      | 598 ms: 1.25x slower                                                      |
| mako                    | 6.93 ms                                                     | 8.76 ms: 1.26x slower                                                     |
| spectral_norm           | 63.2 ms                                                     | 81.4 ms: 1.29x slower                                                     |
| pyflate                 | 297 ms                                                      | 391 ms: 1.32x slower                                                      |
| unpickle_pure_python    | 133 us                                                      | 177 us: 1.33x slower                                                      |
| crypto_pyaes            | 47.4 ms                                                     | 63.2 ms: 1.33x slower                                                     |
| hexiom                  | 4.03 ms                                                     | 5.40 ms: 1.34x slower                                                     |
| scimark_sor             | 79.6 ms                                                     | 107 ms: 1.35x slower                                                      |
| scimark_monte_carlo     | 43.7 ms                                                     | 58.9 ms: 1.35x slower                                                     |
| pickle_pure_python      | 196 us                                                      | 266 us: 1.36x slower                                                      |
| sqlglot_transpile       | 1.04 ms                                                     | 1.42 ms: 1.37x slower                                                     |
| chaos                   | 42.8 ms                                                     | 59.2 ms: 1.39x slower                                                     |
| async_tree_none         | 294 ms                                                      | 414 ms: 1.41x slower                                                      |
| generators              | 22.7 ms                                                     | 32.1 ms: 1.41x slower                                                     |
| raytrace                | 191 ms                                                      | 271 ms: 1.41x slower                                                      |
| async_tree_memoization  | 336 ms                                                      | 481 ms: 1.43x slower                                                      |
| async_tree_io           | 720 ms                                                      | 1.04 sec: 1.44x slower                                                    |
| sqlglot_parse           | 820 us                                                      | 1.19 ms: 1.45x slower                                                     |
| scimark_lu              | 58.1 ms                                                     | 84.5 ms: 1.45x slower                                                     |
| richards                | 26.9 ms                                                     | 40.9 ms: 1.52x slower                                                     |
| go                      | 88.5 ms                                                     | 137 ms: 1.55x slower                                                      |
| json_dumps              | 5.60 ms                                                     | 8.90 ms: 1.59x slower                                                     |
| asyncio_tcp             | 472 ms                                                      | 755 ms: 1.60x slower                                                      |
| logging_silent          | 60.6 ns                                                     | 97.2 ns: 1.61x slower                                                     |
| mypy2                   | 207 ms                                                      | 343 ms: 1.66x slower                                                      |
| deltablue               | 2.14 ms                                                     | 4.11 ms: 1.92x slower                                                     |
| Geometric mean          | (ref)                                                       | 1.17x slower                                                              |

Benchmark hidden because not significant (2): pickle_list, deepcopy_reduce
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (14) of results/bm-20230404-3.10.11-7d4cc5a/bm-20230404-pythonperf1-amd64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.12x
- 95% likely to have a slowdown of 1.12x
- 99% likely to have a slowdown of 1.11x
