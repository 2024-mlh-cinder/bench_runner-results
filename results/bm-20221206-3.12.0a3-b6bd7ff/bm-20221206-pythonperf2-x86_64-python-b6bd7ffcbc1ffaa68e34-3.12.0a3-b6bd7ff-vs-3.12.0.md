
# Results vs. 3.12.0

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: linux-x86_64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.03x slower \*
- HPT reliability: 99.40%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 281 ms: 1.01x faster                                                        |
| chameleon      | 7.27 ms                                                      | 7.51 ms: 1.03x slower                                                       |
| docutils       | 2.89 sec                                                     | 2.76 sec: 1.05x faster                                                      |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 767 ms: 1.09x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.18 sec: 1.11x slower                                                      |
| async_tree_memoization  | 554 ms                                                       | 623 ms: 1.13x slower                                                        |
| async_tree_none         | 459 ms                                                       | 531 ms: 1.16x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.12x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 73.2 ms: 1.12x faster                                                       |
| pidigits       | 264 ms                                                       | 250 ms: 1.06x faster                                                        |
| nbody          | 88.2 ms                                                      | 94.3 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 24.4 ms                                                      | 22.3 ms: 1.09x faster                                                       |
| regex_effbot   | 3.61 ms                                                      | 3.44 ms: 1.05x faster                                                       |
| regex_dna      | 240 ms                                                       | 233 ms: 1.03x faster                                                        |
| regex_compile  | 145 ms                                                       | 150 ms: 1.04x slower                                                        |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.1 us: 1.17x faster                                                       |
| pickle_list          | 4.22 us                                                      | 3.90 us: 1.08x faster                                                       |
| xml_etree_generate   | 85.3 ms                                                      | 78.9 ms: 1.08x faster                                                       |
| xml_etree_process    | 58.3 ms                                                      | 55.6 ms: 1.05x faster                                                       |
| xml_etree_parse      | 147 ms                                                       | 141 ms: 1.04x faster                                                        |
| unpickle_list        | 4.65 us                                                      | 4.47 us: 1.04x faster                                                       |
| pickle               | 10.0 us                                                      | 9.84 us: 1.02x faster                                                       |
| pickle_pure_python   | 319 us                                                       | 316 us: 1.01x faster                                                        |
| json_loads           | 24.3 us                                                      | 24.2 us: 1.00x faster                                                       |
| pickle_dict          | 32.0 us                                                      | 31.9 us: 1.00x faster                                                       |
| json_dumps           | 10.3 ms                                                      | 10.3 ms: 1.01x slower                                                       |
| unpickle_pure_python | 210 us                                                       | 212 us: 1.01x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 108 ms: 1.04x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.86 ms: 1.10x faster                                                       |
| python_startup         | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.09x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 39.6 ms: 1.02x slower                                                       |
| mako            | 10.1 ms                                                      | 10.4 ms: 1.03x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.03x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| scimark_sparse_mat_mult | 4.49 ms                                                      | 3.73 ms: 1.20x faster                                                       |
| unpack_sequence         | 54.5 ns                                                      | 45.5 ns: 1.20x faster                                                       |
| unpickle                | 15.3 us                                                      | 13.1 us: 1.17x faster                                                       |
| async_generators        | 385 ms                                                       | 335 ms: 1.15x faster                                                        |
| float                   | 81.6 ms                                                      | 73.2 ms: 1.12x faster                                                       |
| bench_mp_pool           | 4.96 ms                                                      | 4.46 ms: 1.11x faster                                                       |
| python_startup_no_site  | 8.67 ms                                                      | 7.86 ms: 1.10x faster                                                       |
| regex_v8                | 24.4 ms                                                      | 22.3 ms: 1.09x faster                                                       |
| telco                   | 7.16 ms                                                      | 6.60 ms: 1.08x faster                                                       |
| python_startup          | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                                       |
| pickle_list             | 4.22 us                                                      | 3.90 us: 1.08x faster                                                       |
| xml_etree_generate      | 85.3 ms                                                      | 78.9 ms: 1.08x faster                                                       |
| scimark_fft             | 303 ms                                                       | 282 ms: 1.08x faster                                                        |
| pprint_safe_repr        | 808 ms                                                       | 758 ms: 1.07x faster                                                        |
| pidigits                | 264 ms                                                       | 250 ms: 1.06x faster                                                        |
| pprint_pformat          | 1.64 sec                                                     | 1.56 sec: 1.05x faster                                                      |
| regex_effbot            | 3.61 ms                                                      | 3.44 ms: 1.05x faster                                                       |
| docutils                | 2.89 sec                                                     | 2.76 sec: 1.05x faster                                                      |
| xml_etree_process       | 58.3 ms                                                      | 55.6 ms: 1.05x faster                                                       |
| sqlite_synth            | 2.72 us                                                      | 2.60 us: 1.04x faster                                                       |
| xml_etree_parse         | 147 ms                                                       | 141 ms: 1.04x faster                                                        |
| unpickle_list           | 4.65 us                                                      | 4.47 us: 1.04x faster                                                       |
| pycparser               | 1.29 sec                                                     | 1.26 sec: 1.03x faster                                                      |
| regex_dna               | 240 ms                                                       | 233 ms: 1.03x faster                                                        |
| pickle                  | 10.0 us                                                      | 9.84 us: 1.02x faster                                                       |
| 2to3                    | 285 ms                                                       | 281 ms: 1.01x faster                                                        |
| json                    | 5.17 ms                                                      | 5.11 ms: 1.01x faster                                                       |
| deepcopy_reduce         | 3.41 us                                                      | 3.37 us: 1.01x faster                                                       |
| pickle_pure_python      | 319 us                                                       | 316 us: 1.01x faster                                                        |
| deepcopy_memo           | 36.6 us                                                      | 36.2 us: 1.01x faster                                                       |
| crypto_pyaes            | 82.4 ms                                                      | 81.8 ms: 1.01x faster                                                       |
| json_loads              | 24.3 us                                                      | 24.2 us: 1.00x faster                                                       |
| pickle_dict             | 32.0 us                                                      | 31.9 us: 1.00x faster                                                       |
| json_dumps              | 10.3 ms                                                      | 10.3 ms: 1.01x slower                                                       |
| unpickle_pure_python    | 210 us                                                       | 212 us: 1.01x slower                                                        |
| pathlib                 | 18.7 ms                                                      | 19.0 ms: 1.01x slower                                                       |
| scimark_lu              | 98.6 ms                                                      | 100 ms: 1.02x slower                                                        |
| sqlglot_normalize       | 119 ms                                                       | 121 ms: 1.02x slower                                                        |
| meteor_contest          | 126 ms                                                       | 129 ms: 1.02x slower                                                        |
| gc_traversal            | 3.70 ms                                                      | 3.79 ms: 1.02x slower                                                       |
| deepcopy                | 371 us                                                       | 380 us: 1.02x slower                                                        |
| django_template         | 38.7 ms                                                      | 39.6 ms: 1.02x slower                                                       |
| richards                | 45.1 ms                                                      | 46.1 ms: 1.02x slower                                                       |
| spectral_norm           | 93.9 ms                                                      | 96.2 ms: 1.02x slower                                                       |
| scimark_sor             | 107 ms                                                       | 109 ms: 1.02x slower                                                        |
| mypy2                   | 365 ms                                                       | 375 ms: 1.03x slower                                                        |
| mako                    | 10.1 ms                                                      | 10.4 ms: 1.03x slower                                                       |
| dulwich_log             | 64.9 ms                                                      | 66.7 ms: 1.03x slower                                                       |
| chameleon               | 7.27 ms                                                      | 7.51 ms: 1.03x slower                                                       |
| regex_compile           | 145 ms                                                       | 150 ms: 1.04x slower                                                        |
| sqlglot_transpile       | 1.80 ms                                                      | 1.87 ms: 1.04x slower                                                       |
| xml_etree_iterparse     | 104 ms                                                       | 108 ms: 1.04x slower                                                        |
| bench_thread_pool       | 956 us                                                       | 994 us: 1.04x slower                                                        |
| dask                    | 394 ms                                                       | 409 ms: 1.04x slower                                                        |
| scimark_monte_carlo     | 69.5 ms                                                      | 72.7 ms: 1.05x slower                                                       |
| logging_format          | 7.29 us                                                      | 7.72 us: 1.06x slower                                                       |
| logging_simple          | 6.64 us                                                      | 7.03 us: 1.06x slower                                                       |
| sympy_integrate         | 24.0 ms                                                      | 25.6 ms: 1.06x slower                                                       |
| logging_silent          | 93.3 ns                                                      | 99.7 ns: 1.07x slower                                                       |
| mdp                     | 2.56 sec                                                     | 2.73 sec: 1.07x slower                                                      |
| nbody                   | 88.2 ms                                                      | 94.3 ms: 1.07x slower                                                       |
| go                      | 149 ms                                                       | 159 ms: 1.07x slower                                                        |
| sqlglot_parse           | 1.41 ms                                                      | 1.52 ms: 1.08x slower                                                       |
| sympy_str               | 305 ms                                                       | 331 ms: 1.09x slower                                                        |
| raytrace                | 301 ms                                                       | 327 ms: 1.09x slower                                                        |
| async_tree_cpu_io_mixed | 704 ms                                                       | 767 ms: 1.09x slower                                                        |
| sympy_expand            | 492 ms                                                       | 539 ms: 1.10x slower                                                        |
| fannkuch                | 362 ms                                                       | 398 ms: 1.10x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.18 sec: 1.11x slower                                                      |
| async_tree_memoization  | 554 ms                                                       | 623 ms: 1.13x slower                                                        |
| hexiom                  | 5.97 ms                                                      | 6.73 ms: 1.13x slower                                                       |
| sympy_sum               | 163 ms                                                       | 183 ms: 1.13x slower                                                        |
| nqueens                 | 90.1 ms                                                      | 102 ms: 1.13x slower                                                        |
| deltablue               | 3.24 ms                                                      | 3.67 ms: 1.13x slower                                                       |
| async_tree_none         | 459 ms                                                       | 531 ms: 1.16x slower                                                        |
| coroutines              | 23.1 ms                                                      | 28.0 ms: 1.21x slower                                                       |
| chaos                   | 64.1 ms                                                      | 78.3 ms: 1.22x slower                                                       |
| comprehensions          | 21.8 us                                                      | 27.3 us: 1.25x slower                                                       |
| coverage                | 66.3 ms                                                      | 85.0 ms: 1.28x slower                                                       |
| generators              | 37.3 ms                                                      | 60.8 ms: 1.63x slower                                                       |
| asyncio_tcp             | 380 ms                                                       | 743 ms: 1.96x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.03x slower                                                                |

Benchmark hidden because not significant (3): pyflate, sqlglot_optimize, create_gc_cycles
Ignored benchmarks (14) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, gunicorn, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols
Ignored benchmarks (4) of results/bm-20221206-3.12.0a3-b6bd7ff/bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 99.40% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
