
# Results vs. 3.12.0

- fork: python
- ref: aad5f6a89125ad4529ab
- machine: windows-amd64
- commit hash: aad5f6a
- commit date: 2023-02-07
- overall geometric mean: 1.17x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 231 ms: 1.08x slower                                                      |
| docutils       | 1.63 sec                                                    | 1.84 sec: 1.13x slower                                                    |
| tornado_http   | 87.7 ms                                                     | 109 ms: 1.25x slower                                                      |
| Geometric mean | (ref)                                                       | 1.15x slower                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 148 ms: 1.01x faster                                                      |
| float          | 55.1 ms                                                     | 60.6 ms: 1.10x slower                                                     |
| Geometric mean | (ref)                                                       | 1.02x slower                                                              |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 132 ms: 1.06x slower                                                      |
| regex_v8       | 13.9 ms                                                     | 15.0 ms: 1.08x slower                                                     |
| regex_effbot   | 1.62 ms                                                     | 1.81 ms: 1.12x slower                                                     |
| regex_compile  | 88.3 ms                                                     | 103 ms: 1.17x slower                                                      |
| Geometric mean | (ref)                                                       | 1.11x slower                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| xml_etree_generate   | 55.6 ms                                                     | 53.3 ms: 1.04x faster                                                     |
| unpickle_list        | 2.78 us                                                     | 2.73 us: 1.02x faster                                                     |
| pickle               | 7.13 us                                                     | 7.00 us: 1.02x faster                                                     |
| pickle_dict          | 19.3 us                                                     | 19.1 us: 1.01x faster                                                     |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.4 ms: 1.03x slower                                                     |
| json_loads           | 13.4 us                                                     | 14.2 us: 1.05x slower                                                     |
| xml_etree_parse      | 89.2 ms                                                     | 96.6 ms: 1.08x slower                                                     |
| unpickle             | 8.16 us                                                     | 9.05 us: 1.11x slower                                                     |
| xml_etree_process    | 38.4 ms                                                     | 42.7 ms: 1.11x slower                                                     |
| unpickle_pure_python | 133 us                                                      | 180 us: 1.35x slower                                                      |
| pickle_pure_python   | 196 us                                                      | 267 us: 1.37x slower                                                      |
| json_dumps           | 5.60 ms                                                     | 8.93 ms: 1.59x slower                                                     |
| Geometric mean       | (ref)                                                       | 1.11x slower                                                              |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 15.0 ms: 1.07x faster                                                     |
| python_startup         | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                     |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 8.84 ms: 1.28x slower                                                     |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|-------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| coverage                | 51.5 ms                                                     | 40.0 ms: 1.29x faster                                                     |
| bench_mp_pool           | 66.4 ms                                                     | 60.0 ms: 1.11x faster                                                     |
| python_startup_no_site  | 16.1 ms                                                     | 15.0 ms: 1.07x faster                                                     |
| gc_traversal            | 1.48 ms                                                     | 1.40 ms: 1.06x faster                                                     |
| telco                   | 4.09 ms                                                     | 3.88 ms: 1.06x faster                                                     |
| xml_etree_generate      | 55.6 ms                                                     | 53.3 ms: 1.04x faster                                                     |
| async_generators        | 235 ms                                                      | 227 ms: 1.04x faster                                                      |
| pathlib                 | 77.1 ms                                                     | 75.0 ms: 1.03x faster                                                     |
| unpickle_list           | 2.78 us                                                     | 2.73 us: 1.02x faster                                                     |
| pickle                  | 7.13 us                                                     | 7.00 us: 1.02x faster                                                     |
| pidigits                | 150 ms                                                      | 148 ms: 1.01x faster                                                      |
| pickle_dict             | 19.3 us                                                     | 19.1 us: 1.01x faster                                                     |
| meteor_contest          | 73.1 ms                                                     | 72.9 ms: 1.00x faster                                                     |
| deepcopy_reduce         | 2.13 us                                                     | 2.14 us: 1.00x slower                                                     |
| python_startup          | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                     |
| logging_format          | 6.67 us                                                     | 6.81 us: 1.02x slower                                                     |
| xml_etree_iterparse     | 62.5 ms                                                     | 64.4 ms: 1.03x slower                                                     |
| logging_simple          | 6.21 us                                                     | 6.45 us: 1.04x slower                                                     |
| json_loads              | 13.4 us                                                     | 14.2 us: 1.05x slower                                                     |
| sqlite_synth            | 1.76 us                                                     | 1.86 us: 1.06x slower                                                     |
| regex_dna               | 124 ms                                                      | 132 ms: 1.06x slower                                                      |
| nqueens                 | 61.2 ms                                                     | 65.3 ms: 1.07x slower                                                     |
| create_gc_cycles        | 727 us                                                      | 776 us: 1.07x slower                                                      |
| json                    | 2.86 ms                                                     | 3.06 ms: 1.07x slower                                                     |
| deepcopy                | 240 us                                                      | 258 us: 1.07x slower                                                      |
| scimark_fft             | 180 ms                                                      | 194 ms: 1.08x slower                                                      |
| 2to3                    | 214 ms                                                      | 231 ms: 1.08x slower                                                      |
| regex_v8                | 13.9 ms                                                     | 15.0 ms: 1.08x slower                                                     |
| xml_etree_parse         | 89.2 ms                                                     | 96.6 ms: 1.08x slower                                                     |
| unpack_sequence         | 37.5 ns                                                     | 40.8 ns: 1.09x slower                                                     |
| sqlglot_normalize       | 185 ms                                                      | 202 ms: 1.09x slower                                                      |
| fannkuch                | 237 ms                                                      | 259 ms: 1.09x slower                                                      |
| float                   | 55.1 ms                                                     | 60.6 ms: 1.10x slower                                                     |
| comprehensions          | 14.1 us                                                     | 15.7 us: 1.11x slower                                                     |
| unpickle                | 8.16 us                                                     | 9.05 us: 1.11x slower                                                     |
| xml_etree_process       | 38.4 ms                                                     | 42.7 ms: 1.11x slower                                                     |
| regex_effbot            | 1.62 ms                                                     | 1.81 ms: 1.12x slower                                                     |
| sqlglot_optimize        | 34.4 ms                                                     | 38.5 ms: 1.12x slower                                                     |
| bench_thread_pool       | 844 us                                                      | 944 us: 1.12x slower                                                      |
| pprint_safe_repr        | 512 ms                                                      | 576 ms: 1.12x slower                                                      |
| pprint_pformat          | 1.04 sec                                                    | 1.18 sec: 1.13x slower                                                    |
| docutils                | 1.63 sec                                                    | 1.84 sec: 1.13x slower                                                    |
| aiohttp                 | 865 us                                                      | 980 us: 1.13x slower                                                      |
| coroutines              | 14.0 ms                                                     | 15.9 ms: 1.13x slower                                                     |
| scimark_sparse_mat_mult | 2.48 ms                                                     | 2.82 ms: 1.14x slower                                                     |
| dulwich_log             | 42.4 ms                                                     | 49.0 ms: 1.15x slower                                                     |
| regex_compile           | 88.3 ms                                                     | 103 ms: 1.17x slower                                                      |
| mdp                     | 1.44 sec                                                    | 1.71 sec: 1.18x slower                                                    |
| dask                    | 259 ms                                                      | 314 ms: 1.21x slower                                                      |
| deepcopy_memo           | 23.8 us                                                     | 29.1 us: 1.22x slower                                                     |
| tornado_http            | 87.7 ms                                                     | 109 ms: 1.25x slower                                                      |
| scimark_monte_carlo     | 43.7 ms                                                     | 55.2 ms: 1.26x slower                                                     |
| pycparser               | 673 ms                                                      | 855 ms: 1.27x slower                                                      |
| mako                    | 6.93 ms                                                     | 8.84 ms: 1.28x slower                                                     |
| async_tree_cpu_io_mixed | 479 ms                                                      | 615 ms: 1.29x slower                                                      |
| spectral_norm           | 63.2 ms                                                     | 82.5 ms: 1.31x slower                                                     |
| scimark_sor             | 79.6 ms                                                     | 104 ms: 1.31x slower                                                      |
| pyflate                 | 297 ms                                                      | 393 ms: 1.32x slower                                                      |
| crypto_pyaes            | 47.4 ms                                                     | 63.1 ms: 1.33x slower                                                     |
| hexiom                  | 4.03 ms                                                     | 5.38 ms: 1.34x slower                                                     |
| unpickle_pure_python    | 133 us                                                      | 180 us: 1.35x slower                                                      |
| chaos                   | 42.8 ms                                                     | 58.2 ms: 1.36x slower                                                     |
| pickle_pure_python      | 196 us                                                      | 267 us: 1.37x slower                                                      |
| raytrace                | 191 ms                                                      | 266 ms: 1.39x slower                                                      |
| sqlglot_transpile       | 1.04 ms                                                     | 1.45 ms: 1.40x slower                                                     |
| async_tree_none         | 294 ms                                                      | 417 ms: 1.42x slower                                                      |
| generators              | 22.7 ms                                                     | 32.5 ms: 1.43x slower                                                     |
| scimark_lu              | 58.1 ms                                                     | 83.2 ms: 1.43x slower                                                     |
| asyncio_tcp             | 472 ms                                                      | 678 ms: 1.44x slower                                                      |
| async_tree_io           | 720 ms                                                      | 1.05 sec: 1.45x slower                                                    |
| async_tree_memoization  | 336 ms                                                      | 490 ms: 1.46x slower                                                      |
| sqlglot_parse           | 820 us                                                      | 1.23 ms: 1.50x slower                                                     |
| go                      | 88.5 ms                                                     | 138 ms: 1.56x slower                                                      |
| richards                | 26.9 ms                                                     | 42.3 ms: 1.57x slower                                                     |
| json_dumps              | 5.60 ms                                                     | 8.93 ms: 1.59x slower                                                     |
| mypy2                   | 207 ms                                                      | 338 ms: 1.63x slower                                                      |
| logging_silent          | 60.6 ns                                                     | 99.1 ns: 1.64x slower                                                     |
| deltablue               | 2.14 ms                                                     | 4.16 ms: 1.95x slower                                                     |
| Geometric mean          | (ref)                                                       | 1.17x slower                                                              |

Benchmark hidden because not significant (2): nbody, pickle_list
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (14) of results/bm-20230207-3.10.10-aad5f6a/bm-20230207-pythonperf1-amd64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.12x
- 95% likely to have a slowdown of 1.12x
- 99% likely to have a slowdown of 1.10x
