
# Results vs. 3.12.0

- fork: python
- ref: 2e91dba437fe5c56c6f8
- machine: linux-x86_64
- commit hash: 2e91dba
- commit date: 2021-12-08
- overall geometric mean: 1.10x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 293 ms: 1.03x slower                                                        |
| chameleon      | 7.27 ms                                                      | 8.85 ms: 1.22x slower                                                       |
| docutils       | 2.89 sec                                                     | 3.02 sec: 1.04x slower                                                      |
| tornado_http   | 122 ms                                                       | 135 ms: 1.10x slower                                                        |
| Geometric mean | (ref)                                                        | 1.10x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 811 ms: 1.15x slower                                                        |
| async_tree_none         | 459 ms                                                       | 545 ms: 1.19x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 686 ms: 1.24x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.32 sec: 1.25x slower                                                      |
| Geometric mean          | (ref)                                                        | 1.21x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 253 ms: 1.05x faster                                                        |
| nbody          | 88.2 ms                                                      | 109 ms: 1.23x slower                                                        |
| Geometric mean | (ref)                                                        | 1.05x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.10 ms: 1.17x faster                                                       |
| regex_v8       | 24.4 ms                                                      | 25.7 ms: 1.05x slower                                                       |
| regex_compile  | 145 ms                                                       | 153 ms: 1.06x slower                                                        |
| regex_dna      | 240 ms                                                       | 261 ms: 1.09x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.2 us: 1.16x faster                                                       |
| xml_etree_generate   | 85.3 ms                                                      | 82.8 ms: 1.03x faster                                                       |
| unpickle_list        | 4.65 us                                                      | 4.53 us: 1.02x faster                                                       |
| pickle               | 10.0 us                                                      | 10.2 us: 1.02x slower                                                       |
| pickle_list          | 4.22 us                                                      | 4.32 us: 1.02x slower                                                       |
| pickle_dict          | 32.0 us                                                      | 33.0 us: 1.03x slower                                                       |
| json_loads           | 24.3 us                                                      | 25.3 us: 1.04x slower                                                       |
| xml_etree_process    | 58.3 ms                                                      | 60.9 ms: 1.04x slower                                                       |
| xml_etree_parse      | 147 ms                                                       | 155 ms: 1.06x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 110 ms: 1.06x slower                                                        |
| pickle_pure_python   | 319 us                                                       | 366 us: 1.15x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 265 us: 1.27x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 14.1 ms: 1.37x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.06x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.14 ms: 1.22x faster                                                       |
| python_startup         | 11.7 ms                                                      | 10.1 ms: 1.15x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.18x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 44.9 ms: 1.16x slower                                                       |
| mako            | 10.1 ms                                                      | 12.9 ms: 1.28x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.22x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site  | 8.67 ms                                                      | 7.14 ms: 1.22x faster                                                       |
| async_generators        | 385 ms                                                       | 319 ms: 1.21x faster                                                        |
| unpack_sequence         | 54.5 ns                                                      | 46.3 ns: 1.18x faster                                                       |
| regex_effbot            | 3.61 ms                                                      | 3.10 ms: 1.17x faster                                                       |
| unpickle                | 15.3 us                                                      | 13.2 us: 1.16x faster                                                       |
| python_startup          | 11.7 ms                                                      | 10.1 ms: 1.15x faster                                                       |
| pidigits                | 264 ms                                                       | 253 ms: 1.05x faster                                                        |
| xml_etree_generate      | 85.3 ms                                                      | 82.8 ms: 1.03x faster                                                       |
| unpickle_list           | 4.65 us                                                      | 4.53 us: 1.02x faster                                                       |
| sqlite_synth            | 2.72 us                                                      | 2.70 us: 1.01x faster                                                       |
| telco                   | 7.16 ms                                                      | 7.11 ms: 1.01x faster                                                       |
| json                    | 5.17 ms                                                      | 5.24 ms: 1.01x slower                                                       |
| pickle                  | 10.0 us                                                      | 10.2 us: 1.02x slower                                                       |
| meteor_contest          | 126 ms                                                       | 129 ms: 1.02x slower                                                        |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 4.58 ms: 1.02x slower                                                       |
| pickle_list             | 4.22 us                                                      | 4.32 us: 1.02x slower                                                       |
| pprint_safe_repr        | 808 ms                                                       | 832 ms: 1.03x slower                                                        |
| 2to3                    | 285 ms                                                       | 293 ms: 1.03x slower                                                        |
| pickle_dict             | 32.0 us                                                      | 33.0 us: 1.03x slower                                                       |
| scimark_fft             | 303 ms                                                       | 314 ms: 1.03x slower                                                        |
| deepcopy_reduce         | 3.41 us                                                      | 3.55 us: 1.04x slower                                                       |
| pycparser               | 1.29 sec                                                     | 1.35 sec: 1.04x slower                                                      |
| json_loads              | 24.3 us                                                      | 25.3 us: 1.04x slower                                                       |
| xml_etree_process       | 58.3 ms                                                      | 60.9 ms: 1.04x slower                                                       |
| docutils                | 2.89 sec                                                     | 3.02 sec: 1.04x slower                                                      |
| gc_traversal            | 3.70 ms                                                      | 3.89 ms: 1.05x slower                                                       |
| create_gc_cycles        | 1.58 ms                                                      | 1.66 ms: 1.05x slower                                                       |
| regex_v8                | 24.4 ms                                                      | 25.7 ms: 1.05x slower                                                       |
| pprint_pformat          | 1.64 sec                                                     | 1.74 sec: 1.06x slower                                                      |
| logging_format          | 7.29 us                                                      | 7.70 us: 1.06x slower                                                       |
| xml_etree_parse         | 147 ms                                                       | 155 ms: 1.06x slower                                                        |
| regex_compile           | 145 ms                                                       | 153 ms: 1.06x slower                                                        |
| logging_simple          | 6.64 us                                                      | 7.04 us: 1.06x slower                                                       |
| xml_etree_iterparse     | 104 ms                                                       | 110 ms: 1.06x slower                                                        |
| pathlib                 | 18.7 ms                                                      | 19.9 ms: 1.06x slower                                                       |
| spectral_norm           | 93.9 ms                                                      | 99.9 ms: 1.06x slower                                                       |
| scimark_sor             | 107 ms                                                       | 115 ms: 1.08x slower                                                        |
| mdp                     | 2.56 sec                                                     | 2.76 sec: 1.08x slower                                                      |
| regex_dna               | 240 ms                                                       | 261 ms: 1.09x slower                                                        |
| coverage                | 66.3 ms                                                      | 72.1 ms: 1.09x slower                                                       |
| scimark_monte_carlo     | 69.5 ms                                                      | 76.7 ms: 1.10x slower                                                       |
| tornado_http            | 122 ms                                                       | 135 ms: 1.10x slower                                                        |
| sympy_integrate         | 24.0 ms                                                      | 26.5 ms: 1.10x slower                                                       |
| dask                    | 394 ms                                                       | 435 ms: 1.11x slower                                                        |
| bench_thread_pool       | 956 us                                                       | 1.06 ms: 1.11x slower                                                       |
| sqlglot_optimize        | 58.4 ms                                                      | 64.7 ms: 1.11x slower                                                       |
| sqlglot_normalize       | 119 ms                                                       | 133 ms: 1.11x slower                                                        |
| scimark_lu              | 98.6 ms                                                      | 110 ms: 1.11x slower                                                        |
| deepcopy                | 371 us                                                       | 418 us: 1.12x slower                                                        |
| dulwich_log             | 64.9 ms                                                      | 73.0 ms: 1.12x slower                                                       |
| deepcopy_memo           | 36.6 us                                                      | 41.5 us: 1.13x slower                                                       |
| nqueens                 | 90.1 ms                                                      | 103 ms: 1.14x slower                                                        |
| pickle_pure_python      | 319 us                                                       | 366 us: 1.15x slower                                                        |
| sympy_str               | 305 ms                                                       | 350 ms: 1.15x slower                                                        |
| crypto_pyaes            | 82.4 ms                                                      | 94.7 ms: 1.15x slower                                                       |
| async_tree_cpu_io_mixed | 704 ms                                                       | 811 ms: 1.15x slower                                                        |
| raytrace                | 301 ms                                                       | 347 ms: 1.15x slower                                                        |
| go                      | 149 ms                                                       | 173 ms: 1.16x slower                                                        |
| django_template         | 38.7 ms                                                      | 44.9 ms: 1.16x slower                                                       |
| sympy_sum               | 163 ms                                                       | 189 ms: 1.16x slower                                                        |
| coroutines              | 23.1 ms                                                      | 27.0 ms: 1.17x slower                                                       |
| sympy_expand            | 492 ms                                                       | 579 ms: 1.18x slower                                                        |
| fannkuch                | 362 ms                                                       | 428 ms: 1.18x slower                                                        |
| async_tree_none         | 459 ms                                                       | 545 ms: 1.19x slower                                                        |
| pyflate                 | 442 ms                                                       | 525 ms: 1.19x slower                                                        |
| chameleon               | 7.27 ms                                                      | 8.85 ms: 1.22x slower                                                       |
| chaos                   | 64.1 ms                                                      | 78.3 ms: 1.22x slower                                                       |
| nbody                   | 88.2 ms                                                      | 109 ms: 1.23x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 686 ms: 1.24x slower                                                        |
| hexiom                  | 5.97 ms                                                      | 7.41 ms: 1.24x slower                                                       |
| logging_silent          | 93.3 ns                                                      | 116 ns: 1.24x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.32 sec: 1.25x slower                                                      |
| richards                | 45.1 ms                                                      | 56.7 ms: 1.26x slower                                                       |
| unpickle_pure_python    | 210 us                                                       | 265 us: 1.27x slower                                                        |
| mako                    | 10.1 ms                                                      | 12.9 ms: 1.28x slower                                                       |
| generators              | 37.3 ms                                                      | 50.1 ms: 1.34x slower                                                       |
| json_dumps              | 10.3 ms                                                      | 14.1 ms: 1.37x slower                                                       |
| comprehensions          | 21.8 us                                                      | 30.6 us: 1.40x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 2.60 ms: 1.44x slower                                                       |
| deltablue               | 3.24 ms                                                      | 4.78 ms: 1.48x slower                                                       |
| sqlglot_parse           | 1.41 ms                                                      | 2.21 ms: 1.57x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.10x slower                                                                |

Benchmark hidden because not significant (3): bench_mp_pool, float, gunicorn
Ignored benchmarks (14) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20211208-3.11.0a3-2e91dba/bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba.json: flaskblogging, genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.08x
- 95% likely to have a slowdown of 1.08x
- 99% likely to have a slowdown of 1.06x
