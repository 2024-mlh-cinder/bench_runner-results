
# Results vs. 3.12.0

- fork: python
- ref: 7c12e4835ebe52287acd
- machine: windows-amd64
- commit hash: 7c12e48
- commit date: 2021-10-05
- overall geometric mean: 1.14x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf1-amd64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 222 ms: 1.04x slower                                                       |
| docutils       | 1.63 sec                                                    | 1.73 sec: 1.06x slower                                                     |
| tornado_http   | 87.7 ms                                                     | 97.6 ms: 1.11x slower                                                      |
| Geometric mean | (ref)                                                       | 1.07x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf1-amd64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 57.2 ms: 1.04x slower                                                      |
| nbody          | 72.6 ms                                                     | 86.8 ms: 1.20x slower                                                      |
| Geometric mean | (ref)                                                       | 1.08x slower                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf1-amd64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 1.62 ms                                                     | 1.66 ms: 1.02x slower                                                      |
| regex_v8       | 13.9 ms                                                     | 14.4 ms: 1.04x slower                                                      |
| regex_dna      | 124 ms                                                      | 129 ms: 1.04x slower                                                       |
| regex_compile  | 88.3 ms                                                     | 92.3 ms: 1.05x slower                                                      |
| Geometric mean | (ref)                                                       | 1.04x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf1-amd64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 16.8 us: 1.15x faster                                                      |
| unpickle_list        | 2.78 us                                                     | 2.56 us: 1.08x faster                                                      |
| pickle               | 7.13 us                                                     | 6.58 us: 1.08x faster                                                      |
| pickle_list          | 2.86 us                                                     | 2.66 us: 1.08x faster                                                      |
| xml_etree_generate   | 55.6 ms                                                     | 54.8 ms: 1.01x faster                                                      |
| unpickle             | 8.16 us                                                     | 8.48 us: 1.04x slower                                                      |
| xml_etree_process    | 38.4 ms                                                     | 40.3 ms: 1.05x slower                                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 65.6 ms: 1.05x slower                                                      |
| json_loads           | 13.4 us                                                     | 14.4 us: 1.07x slower                                                      |
| xml_etree_parse      | 89.2 ms                                                     | 98.4 ms: 1.10x slower                                                      |
| pickle_pure_python   | 196 us                                                      | 240 us: 1.23x slower                                                       |
| unpickle_pure_python | 133 us                                                      | 172 us: 1.29x slower                                                       |
| json_dumps           | 5.60 ms                                                     | 8.03 ms: 1.44x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.06x slower                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf1-amd64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 15.6 ms: 1.04x faster                                                      |
| python_startup         | 19.5 ms                                                     | 20.7 ms: 1.06x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf1-amd64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 8.12 ms: 1.17x slower                                                      |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211005-pythonperf1-amd64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_generators        | 235 ms                                                      | 198 ms: 1.19x faster                                                       |
| logging_simple          | 6.21 us                                                     | 5.24 us: 1.19x faster                                                      |
| logging_format          | 6.67 us                                                     | 5.64 us: 1.18x faster                                                      |
| pickle_dict             | 19.3 us                                                     | 16.8 us: 1.15x faster                                                      |
| unpickle_list           | 2.78 us                                                     | 2.56 us: 1.08x faster                                                      |
| pickle                  | 7.13 us                                                     | 6.58 us: 1.08x faster                                                      |
| gc_traversal            | 1.48 ms                                                     | 1.37 ms: 1.08x faster                                                      |
| pickle_list             | 2.86 us                                                     | 2.66 us: 1.08x faster                                                      |
| bench_mp_pool           | 66.4 ms                                                     | 63.0 ms: 1.05x faster                                                      |
| pathlib                 | 77.1 ms                                                     | 73.4 ms: 1.05x faster                                                      |
| python_startup_no_site  | 16.1 ms                                                     | 15.6 ms: 1.04x faster                                                      |
| telco                   | 4.09 ms                                                     | 3.98 ms: 1.03x faster                                                      |
| xml_etree_generate      | 55.6 ms                                                     | 54.8 ms: 1.01x faster                                                      |
| deepcopy_reduce         | 2.13 us                                                     | 2.16 us: 1.01x slower                                                      |
| regex_effbot            | 1.62 ms                                                     | 1.66 ms: 1.02x slower                                                      |
| sqlite_synth            | 1.76 us                                                     | 1.80 us: 1.03x slower                                                      |
| meteor_contest          | 73.1 ms                                                     | 75.3 ms: 1.03x slower                                                      |
| regex_v8                | 13.9 ms                                                     | 14.4 ms: 1.04x slower                                                      |
| 2to3                    | 214 ms                                                      | 222 ms: 1.04x slower                                                       |
| regex_dna               | 124 ms                                                      | 129 ms: 1.04x slower                                                       |
| float                   | 55.1 ms                                                     | 57.2 ms: 1.04x slower                                                      |
| unpickle                | 8.16 us                                                     | 8.48 us: 1.04x slower                                                      |
| regex_compile           | 88.3 ms                                                     | 92.3 ms: 1.05x slower                                                      |
| xml_etree_process       | 38.4 ms                                                     | 40.3 ms: 1.05x slower                                                      |
| xml_etree_iterparse     | 62.5 ms                                                     | 65.6 ms: 1.05x slower                                                      |
| json                    | 2.86 ms                                                     | 3.01 ms: 1.05x slower                                                      |
| docutils                | 1.63 sec                                                    | 1.73 sec: 1.06x slower                                                     |
| python_startup          | 19.5 ms                                                     | 20.7 ms: 1.06x slower                                                      |
| deepcopy                | 240 us                                                      | 256 us: 1.07x slower                                                       |
| json_loads              | 13.4 us                                                     | 14.4 us: 1.07x slower                                                      |
| async_tree_io           | 720 ms                                                      | 777 ms: 1.08x slower                                                       |
| sqlglot_normalize       | 185 ms                                                      | 201 ms: 1.08x slower                                                       |
| bench_thread_pool       | 844 us                                                      | 915 us: 1.08x slower                                                       |
| dulwich_log             | 42.4 ms                                                     | 46.1 ms: 1.09x slower                                                      |
| mdp                     | 1.44 sec                                                    | 1.58 sec: 1.09x slower                                                     |
| sqlglot_optimize        | 34.4 ms                                                     | 37.8 ms: 1.10x slower                                                      |
| xml_etree_parse         | 89.2 ms                                                     | 98.4 ms: 1.10x slower                                                      |
| nqueens                 | 61.2 ms                                                     | 67.7 ms: 1.11x slower                                                      |
| create_gc_cycles        | 727 us                                                      | 807 us: 1.11x slower                                                       |
| pprint_pformat          | 1.04 sec                                                    | 1.16 sec: 1.11x slower                                                     |
| unpack_sequence         | 37.5 ns                                                     | 41.7 ns: 1.11x slower                                                      |
| pprint_safe_repr        | 512 ms                                                      | 570 ms: 1.11x slower                                                       |
| tornado_http            | 87.7 ms                                                     | 97.6 ms: 1.11x slower                                                      |
| async_tree_cpu_io_mixed | 479 ms                                                      | 541 ms: 1.13x slower                                                       |
| dask                    | 259 ms                                                      | 295 ms: 1.14x slower                                                       |
| async_tree_memoization  | 336 ms                                                      | 384 ms: 1.14x slower                                                       |
| pycparser               | 673 ms                                                      | 777 ms: 1.15x slower                                                       |
| mako                    | 6.93 ms                                                     | 8.12 ms: 1.17x slower                                                      |
| raytrace                | 191 ms                                                      | 224 ms: 1.17x slower                                                       |
| fannkuch                | 237 ms                                                      | 279 ms: 1.18x slower                                                       |
| nbody                   | 72.6 ms                                                     | 86.8 ms: 1.20x slower                                                      |
| scimark_fft             | 180 ms                                                      | 216 ms: 1.20x slower                                                       |
| deepcopy_memo           | 23.8 us                                                     | 28.6 us: 1.20x slower                                                      |
| scimark_monte_carlo     | 43.7 ms                                                     | 52.6 ms: 1.20x slower                                                      |
| crypto_pyaes            | 47.4 ms                                                     | 57.7 ms: 1.22x slower                                                      |
| go                      | 88.5 ms                                                     | 108 ms: 1.22x slower                                                       |
| pickle_pure_python      | 196 us                                                      | 240 us: 1.23x slower                                                       |
| pyflate                 | 297 ms                                                      | 365 ms: 1.23x slower                                                       |
| generators              | 22.7 ms                                                     | 28.9 ms: 1.27x slower                                                      |
| coroutines              | 14.0 ms                                                     | 17.9 ms: 1.28x slower                                                      |
| hexiom                  | 4.03 ms                                                     | 5.17 ms: 1.28x slower                                                      |
| scimark_sparse_mat_mult | 2.48 ms                                                     | 3.18 ms: 1.28x slower                                                      |
| chaos                   | 42.8 ms                                                     | 55.0 ms: 1.29x slower                                                      |
| richards                | 26.9 ms                                                     | 34.7 ms: 1.29x slower                                                      |
| unpickle_pure_python    | 133 us                                                      | 172 us: 1.29x slower                                                       |
| scimark_sor             | 79.6 ms                                                     | 105 ms: 1.32x slower                                                       |
| asyncio_tcp             | 472 ms                                                      | 628 ms: 1.33x slower                                                       |
| spectral_norm           | 63.2 ms                                                     | 84.7 ms: 1.34x slower                                                      |
| comprehensions          | 14.1 us                                                     | 19.1 us: 1.35x slower                                                      |
| logging_silent          | 60.6 ns                                                     | 83.4 ns: 1.38x slower                                                      |
| json_dumps              | 5.60 ms                                                     | 8.03 ms: 1.44x slower                                                      |
| scimark_lu              | 58.1 ms                                                     | 83.6 ms: 1.44x slower                                                      |
| deltablue               | 2.14 ms                                                     | 3.12 ms: 1.46x slower                                                      |
| sqlglot_transpile       | 1.04 ms                                                     | 1.53 ms: 1.48x slower                                                      |
| sqlglot_parse           | 820 us                                                      | 1.32 ms: 1.60x slower                                                      |
| coverage                | 51.5 ms                                                     | 261 ms: 5.08x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.14x slower                                                               |

Benchmark hidden because not significant (2): pidigits, async_tree_none
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, asyncio_tcp_ssl, mypy2, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (14) of results/bm-20211005-3.11.0a1-7c12e48/bm-20211005-pythonperf1-amd64-python-7c12e4835ebe52287acd-3.11.0a1-7c12e48.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.09x
- 95% likely to have a slowdown of 1.09x
- 99% likely to have a slowdown of 1.08x
