
# Results vs. 3.12.0

- fork: python
- ref: 2cd268a3a9340346dd86
- machine: windows-amd64
- commit hash: 2cd268a
- commit date: 2021-12-06
- overall geometric mean: 1.17x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211206-pythonperf1-amd64-python-2cd268a3a9340346dd86-3.10.1-2cd268a |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 232 ms: 1.08x slower                                                     |
| docutils       | 1.63 sec                                                    | 1.88 sec: 1.15x slower                                                   |
| tornado_http   | 87.7 ms                                                     | 109 ms: 1.25x slower                                                     |
| Geometric mean | (ref)                                                       | 1.16x slower                                                             |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211206-pythonperf1-amd64-python-2cd268a3a9340346dd86-3.10.1-2cd268a |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 149 ms: 1.01x faster                                                     |
| nbody          | 72.6 ms                                                     | 77.2 ms: 1.06x slower                                                    |
| float          | 55.1 ms                                                     | 61.8 ms: 1.12x slower                                                    |
| Geometric mean | (ref)                                                       | 1.06x slower                                                             |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211206-pythonperf1-amd64-python-2cd268a3a9340346dd86-3.10.1-2cd268a |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 129 ms: 1.04x slower                                                     |
| regex_effbot   | 1.62 ms                                                     | 1.74 ms: 1.07x slower                                                    |
| regex_v8       | 13.9 ms                                                     | 15.0 ms: 1.08x slower                                                    |
| regex_compile  | 88.3 ms                                                     | 103 ms: 1.17x slower                                                     |
| Geometric mean | (ref)                                                       | 1.09x slower                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211206-pythonperf1-amd64-python-2cd268a3a9340346dd86-3.10.1-2cd268a |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 17.0 us: 1.13x faster                                                    |
| pickle_list          | 2.86 us                                                     | 2.70 us: 1.06x faster                                                    |
| unpickle_list        | 2.78 us                                                     | 2.64 us: 1.05x faster                                                    |
| pickle               | 7.13 us                                                     | 6.84 us: 1.04x faster                                                    |
| xml_etree_generate   | 55.6 ms                                                     | 55.0 ms: 1.01x faster                                                    |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.6 ms: 1.03x slower                                                    |
| xml_etree_parse      | 89.2 ms                                                     | 98.0 ms: 1.10x slower                                                    |
| json_loads           | 13.4 us                                                     | 15.0 us: 1.12x slower                                                    |
| xml_etree_process    | 38.4 ms                                                     | 44.0 ms: 1.15x slower                                                    |
| unpickle_pure_python | 133 us                                                      | 177 us: 1.33x slower                                                     |
| pickle_pure_python   | 196 us                                                      | 267 us: 1.36x slower                                                     |
| json_dumps           | 5.60 ms                                                     | 8.45 ms: 1.51x slower                                                    |
| Geometric mean       | (ref)                                                       | 1.09x slower                                                             |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211206-pythonperf1-amd64-python-2cd268a3a9340346dd86-3.10.1-2cd268a |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 15.1 ms: 1.07x faster                                                    |
| python_startup         | 19.5 ms                                                     | 19.7 ms: 1.01x slower                                                    |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                             |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211206-pythonperf1-amd64-python-2cd268a3a9340346dd86-3.10.1-2cd268a |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 8.56 ms: 1.23x slower                                                    |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211206-pythonperf1-amd64-python-2cd268a3a9340346dd86-3.10.1-2cd268a |
|-------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| coverage                | 51.5 ms                                                     | 38.8 ms: 1.33x faster                                                    |
| pickle_dict             | 19.3 us                                                     | 17.0 us: 1.13x faster                                                    |
| bench_mp_pool           | 66.4 ms                                                     | 60.4 ms: 1.10x faster                                                    |
| gc_traversal            | 1.48 ms                                                     | 1.37 ms: 1.08x faster                                                    |
| python_startup_no_site  | 16.1 ms                                                     | 15.1 ms: 1.07x faster                                                    |
| pickle_list             | 2.86 us                                                     | 2.70 us: 1.06x faster                                                    |
| telco                   | 4.09 ms                                                     | 3.86 ms: 1.06x faster                                                    |
| unpickle_list           | 2.78 us                                                     | 2.64 us: 1.05x faster                                                    |
| async_generators        | 235 ms                                                      | 224 ms: 1.05x faster                                                     |
| pickle                  | 7.13 us                                                     | 6.84 us: 1.04x faster                                                    |
| pathlib                 | 77.1 ms                                                     | 75.9 ms: 1.02x faster                                                    |
| xml_etree_generate      | 55.6 ms                                                     | 55.0 ms: 1.01x faster                                                    |
| pidigits                | 150 ms                                                      | 149 ms: 1.01x faster                                                     |
| logging_format          | 6.67 us                                                     | 6.72 us: 1.01x slower                                                    |
| deepcopy_reduce         | 2.13 us                                                     | 2.15 us: 1.01x slower                                                    |
| python_startup          | 19.5 ms                                                     | 19.7 ms: 1.01x slower                                                    |
| xml_etree_iterparse     | 62.5 ms                                                     | 64.6 ms: 1.03x slower                                                    |
| regex_dna               | 124 ms                                                      | 129 ms: 1.04x slower                                                     |
| sqlite_synth            | 1.76 us                                                     | 1.85 us: 1.05x slower                                                    |
| create_gc_cycles        | 727 us                                                      | 770 us: 1.06x slower                                                     |
| deepcopy                | 240 us                                                      | 254 us: 1.06x slower                                                     |
| nbody                   | 72.6 ms                                                     | 77.2 ms: 1.06x slower                                                    |
| nqueens                 | 61.2 ms                                                     | 65.5 ms: 1.07x slower                                                    |
| regex_effbot            | 1.62 ms                                                     | 1.74 ms: 1.07x slower                                                    |
| regex_v8                | 13.9 ms                                                     | 15.0 ms: 1.08x slower                                                    |
| unpack_sequence         | 37.5 ns                                                     | 40.5 ns: 1.08x slower                                                    |
| scimark_fft             | 180 ms                                                      | 195 ms: 1.08x slower                                                     |
| 2to3                    | 214 ms                                                      | 232 ms: 1.08x slower                                                     |
| json                    | 2.86 ms                                                     | 3.13 ms: 1.09x slower                                                    |
| sqlglot_normalize       | 185 ms                                                      | 203 ms: 1.09x slower                                                     |
| xml_etree_parse         | 89.2 ms                                                     | 98.0 ms: 1.10x slower                                                    |
| json_loads              | 13.4 us                                                     | 15.0 us: 1.12x slower                                                    |
| fannkuch                | 237 ms                                                      | 266 ms: 1.12x slower                                                     |
| comprehensions          | 14.1 us                                                     | 15.8 us: 1.12x slower                                                    |
| float                   | 55.1 ms                                                     | 61.8 ms: 1.12x slower                                                    |
| scimark_sparse_mat_mult | 2.48 ms                                                     | 2.80 ms: 1.13x slower                                                    |
| coroutines              | 14.0 ms                                                     | 15.9 ms: 1.14x slower                                                    |
| sqlglot_optimize        | 34.4 ms                                                     | 39.2 ms: 1.14x slower                                                    |
| bench_thread_pool       | 844 us                                                      | 965 us: 1.14x slower                                                     |
| aiohttp                 | 865 us                                                      | 990 us: 1.14x slower                                                     |
| dulwich_log             | 42.4 ms                                                     | 48.7 ms: 1.15x slower                                                    |
| xml_etree_process       | 38.4 ms                                                     | 44.0 ms: 1.15x slower                                                    |
| docutils                | 1.63 sec                                                    | 1.88 sec: 1.15x slower                                                   |
| regex_compile           | 88.3 ms                                                     | 103 ms: 1.17x slower                                                     |
| pprint_safe_repr        | 512 ms                                                      | 601 ms: 1.17x slower                                                     |
| pprint_pformat          | 1.04 sec                                                    | 1.24 sec: 1.19x slower                                                   |
| mdp                     | 1.44 sec                                                    | 1.72 sec: 1.19x slower                                                   |
| deepcopy_memo           | 23.8 us                                                     | 28.7 us: 1.21x slower                                                    |
| dask                    | 259 ms                                                      | 319 ms: 1.23x slower                                                     |
| mako                    | 6.93 ms                                                     | 8.56 ms: 1.23x slower                                                    |
| tornado_http            | 87.7 ms                                                     | 109 ms: 1.25x slower                                                     |
| spectral_norm           | 63.2 ms                                                     | 79.4 ms: 1.26x slower                                                    |
| pycparser               | 673 ms                                                      | 861 ms: 1.28x slower                                                     |
| async_tree_cpu_io_mixed | 479 ms                                                      | 615 ms: 1.29x slower                                                     |
| scimark_monte_carlo     | 43.7 ms                                                     | 56.9 ms: 1.30x slower                                                    |
| pyflate                 | 297 ms                                                      | 394 ms: 1.33x slower                                                     |
| unpickle_pure_python    | 133 us                                                      | 177 us: 1.33x slower                                                     |
| scimark_sor             | 79.6 ms                                                     | 106 ms: 1.33x slower                                                     |
| hexiom                  | 4.03 ms                                                     | 5.42 ms: 1.35x slower                                                    |
| generators              | 22.7 ms                                                     | 30.7 ms: 1.35x slower                                                    |
| pickle_pure_python      | 196 us                                                      | 267 us: 1.36x slower                                                     |
| crypto_pyaes            | 47.4 ms                                                     | 65.5 ms: 1.38x slower                                                    |
| chaos                   | 42.8 ms                                                     | 59.4 ms: 1.39x slower                                                    |
| sqlglot_transpile       | 1.04 ms                                                     | 1.45 ms: 1.40x slower                                                    |
| async_tree_none         | 294 ms                                                      | 417 ms: 1.42x slower                                                     |
| raytrace                | 191 ms                                                      | 273 ms: 1.43x slower                                                     |
| async_tree_io           | 720 ms                                                      | 1.03 sec: 1.43x slower                                                   |
| scimark_lu              | 58.1 ms                                                     | 83.4 ms: 1.43x slower                                                    |
| async_tree_memoization  | 336 ms                                                      | 484 ms: 1.44x slower                                                     |
| sqlglot_parse           | 820 us                                                      | 1.21 ms: 1.47x slower                                                    |
| json_dumps              | 5.60 ms                                                     | 8.45 ms: 1.51x slower                                                    |
| asyncio_tcp             | 472 ms                                                      | 713 ms: 1.51x slower                                                     |
| richards                | 26.9 ms                                                     | 40.9 ms: 1.52x slower                                                    |
| go                      | 88.5 ms                                                     | 137 ms: 1.55x slower                                                     |
| logging_silent          | 60.6 ns                                                     | 98.0 ns: 1.62x slower                                                    |
| mypy2                   | 207 ms                                                      | 340 ms: 1.64x slower                                                     |
| deltablue               | 2.14 ms                                                     | 4.13 ms: 1.93x slower                                                    |
| Geometric mean          | (ref)                                                       | 1.17x slower                                                             |

Benchmark hidden because not significant (3): meteor_contest, unpickle, logging_simple
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (14) of results/bm-20211206-3.10.1-2cd268a/bm-20211206-pythonperf1-amd64-python-2cd268a3a9340346dd86-3.10.1-2cd268a.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.14x
- 95% likely to have a slowdown of 1.13x
- 99% likely to have a slowdown of 1.11x
