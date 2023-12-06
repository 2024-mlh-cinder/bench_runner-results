
# Results vs. 3.12.0

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: linux-x86_64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.02x slower \*
- HPT reliability: 86.90%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 282 ms: 1.01x faster                                                        |
| chameleon      | 7.27 ms                                                      | 7.19 ms: 1.01x faster                                                       |
| docutils       | 2.89 sec                                                     | 2.77 sec: 1.05x faster                                                      |
| tornado_http   | 122 ms                                                       | 115 ms: 1.06x faster                                                        |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 762 ms: 1.08x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                                      |
| async_tree_memoization  | 554 ms                                                       | 621 ms: 1.12x slower                                                        |
| async_tree_none         | 459 ms                                                       | 520 ms: 1.13x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.11x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 73.2 ms: 1.12x faster                                                       |
| pidigits       | 264 ms                                                       | 252 ms: 1.05x faster                                                        |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 240 ms                                                       | 227 ms: 1.06x faster                                                        |
| regex_v8       | 24.4 ms                                                      | 23.2 ms: 1.05x faster                                                       |
| regex_effbot   | 3.61 ms                                                      | 3.45 ms: 1.05x faster                                                       |
| regex_compile  | 145 ms                                                       | 147 ms: 1.01x slower                                                        |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|---------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle            | 15.3 us                                                      | 12.6 us: 1.21x faster                                                       |
| pickle_list         | 4.22 us                                                      | 3.65 us: 1.16x faster                                                       |
| xml_etree_generate  | 85.3 ms                                                      | 79.3 ms: 1.08x faster                                                       |
| xml_etree_process   | 58.3 ms                                                      | 54.8 ms: 1.07x faster                                                       |
| xml_etree_parse     | 147 ms                                                       | 143 ms: 1.03x faster                                                        |
| unpickle_list       | 4.65 us                                                      | 4.51 us: 1.03x faster                                                       |
| json_loads          | 24.3 us                                                      | 23.7 us: 1.02x faster                                                       |
| pickle_pure_python  | 319 us                                                       | 314 us: 1.02x faster                                                        |
| xml_etree_iterparse | 104 ms                                                       | 108 ms: 1.04x slower                                                        |
| pickle_dict         | 32.0 us                                                      | 33.4 us: 1.04x slower                                                       |
| Geometric mean      | (ref)                                                        | 1.04x faster                                                                |

Benchmark hidden because not significant (3): json_dumps, unpickle_pure_python, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.87 ms: 1.10x faster                                                       |
| python_startup         | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.09x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 10.1 ms                                                      | 10.2 ms: 1.01x slower                                                       |
| django_template | 38.7 ms                                                      | 39.7 ms: 1.03x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.02x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle                | 15.3 us                                                      | 12.6 us: 1.21x faster                                                       |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 3.74 ms: 1.20x faster                                                       |
| async_generators        | 385 ms                                                       | 321 ms: 1.20x faster                                                        |
| unpack_sequence         | 54.5 ns                                                      | 45.8 ns: 1.19x faster                                                       |
| pickle_list             | 4.22 us                                                      | 3.65 us: 1.16x faster                                                       |
| gunicorn                | 1.01 ms                                                      | 886 us: 1.14x faster                                                        |
| aiohttp                 | 1.02 ms                                                      | 904 us: 1.13x faster                                                        |
| float                   | 81.6 ms                                                      | 73.2 ms: 1.12x faster                                                       |
| scimark_fft             | 303 ms                                                       | 273 ms: 1.11x faster                                                        |
| python_startup_no_site  | 8.67 ms                                                      | 7.87 ms: 1.10x faster                                                       |
| telco                   | 7.16 ms                                                      | 6.58 ms: 1.09x faster                                                       |
| python_startup          | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                                       |
| bench_mp_pool           | 4.96 ms                                                      | 4.59 ms: 1.08x faster                                                       |
| xml_etree_generate      | 85.3 ms                                                      | 79.3 ms: 1.08x faster                                                       |
| pprint_safe_repr        | 808 ms                                                       | 752 ms: 1.07x faster                                                        |
| xml_etree_process       | 58.3 ms                                                      | 54.8 ms: 1.07x faster                                                       |
| pprint_pformat          | 1.64 sec                                                     | 1.55 sec: 1.06x faster                                                      |
| regex_dna               | 240 ms                                                       | 227 ms: 1.06x faster                                                        |
| sqlite_synth            | 2.72 us                                                      | 2.57 us: 1.06x faster                                                       |
| tornado_http            | 122 ms                                                       | 115 ms: 1.06x faster                                                        |
| regex_v8                | 24.4 ms                                                      | 23.2 ms: 1.05x faster                                                       |
| pidigits                | 264 ms                                                       | 252 ms: 1.05x faster                                                        |
| scimark_monte_carlo     | 69.5 ms                                                      | 66.4 ms: 1.05x faster                                                       |
| regex_effbot            | 3.61 ms                                                      | 3.45 ms: 1.05x faster                                                       |
| docutils                | 2.89 sec                                                     | 2.77 sec: 1.05x faster                                                      |
| json                    | 5.17 ms                                                      | 4.95 ms: 1.05x faster                                                       |
| pycparser               | 1.29 sec                                                     | 1.24 sec: 1.04x faster                                                      |
| xml_etree_parse         | 147 ms                                                       | 143 ms: 1.03x faster                                                        |
| unpickle_list           | 4.65 us                                                      | 4.51 us: 1.03x faster                                                       |
| json_loads              | 24.3 us                                                      | 23.7 us: 1.02x faster                                                       |
| crypto_pyaes            | 82.4 ms                                                      | 80.7 ms: 1.02x faster                                                       |
| pickle_pure_python      | 319 us                                                       | 314 us: 1.02x faster                                                        |
| pyflate                 | 442 ms                                                       | 436 ms: 1.01x faster                                                        |
| chameleon               | 7.27 ms                                                      | 7.19 ms: 1.01x faster                                                       |
| 2to3                    | 285 ms                                                       | 282 ms: 1.01x faster                                                        |
| spectral_norm           | 93.9 ms                                                      | 93.2 ms: 1.01x faster                                                       |
| deepcopy_reduce         | 3.41 us                                                      | 3.39 us: 1.01x faster                                                       |
| scimark_sor             | 107 ms                                                       | 106 ms: 1.00x faster                                                        |
| regex_compile           | 145 ms                                                       | 147 ms: 1.01x slower                                                        |
| create_gc_cycles        | 1.58 ms                                                      | 1.60 ms: 1.01x slower                                                       |
| mako                    | 10.1 ms                                                      | 10.2 ms: 1.01x slower                                                       |
| raytrace                | 301 ms                                                       | 305 ms: 1.02x slower                                                        |
| meteor_contest          | 126 ms                                                       | 129 ms: 1.02x slower                                                        |
| logging_simple          | 6.64 us                                                      | 6.78 us: 1.02x slower                                                       |
| mypy2                   | 365 ms                                                       | 374 ms: 1.02x slower                                                        |
| sqlglot_normalize       | 119 ms                                                       | 122 ms: 1.03x slower                                                        |
| django_template         | 38.7 ms                                                      | 39.7 ms: 1.03x slower                                                       |
| pathlib                 | 18.7 ms                                                      | 19.3 ms: 1.03x slower                                                       |
| dulwich_log             | 64.9 ms                                                      | 67.2 ms: 1.03x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 1.87 ms: 1.04x slower                                                       |
| xml_etree_iterparse     | 104 ms                                                       | 108 ms: 1.04x slower                                                        |
| deepcopy                | 371 us                                                       | 387 us: 1.04x slower                                                        |
| pickle_dict             | 32.0 us                                                      | 33.4 us: 1.04x slower                                                       |
| dask                    | 394 ms                                                       | 410 ms: 1.04x slower                                                        |
| logging_format          | 7.29 us                                                      | 7.60 us: 1.04x slower                                                       |
| gc_traversal            | 3.70 ms                                                      | 3.92 ms: 1.06x slower                                                       |
| sympy_integrate         | 24.0 ms                                                      | 25.5 ms: 1.06x slower                                                       |
| logging_silent          | 93.3 ns                                                      | 99.2 ns: 1.06x slower                                                       |
| sqlglot_parse           | 1.41 ms                                                      | 1.50 ms: 1.07x slower                                                       |
| mdp                     | 2.56 sec                                                     | 2.73 sec: 1.07x slower                                                      |
| go                      | 149 ms                                                       | 160 ms: 1.08x slower                                                        |
| fannkuch                | 362 ms                                                       | 391 ms: 1.08x slower                                                        |
| async_tree_cpu_io_mixed | 704 ms                                                       | 762 ms: 1.08x slower                                                        |
| sympy_str               | 305 ms                                                       | 337 ms: 1.11x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                                      |
| sympy_expand            | 492 ms                                                       | 550 ms: 1.12x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 621 ms: 1.12x slower                                                        |
| deltablue               | 3.24 ms                                                      | 3.64 ms: 1.12x slower                                                       |
| scimark_lu              | 98.6 ms                                                      | 111 ms: 1.13x slower                                                        |
| hexiom                  | 5.97 ms                                                      | 6.76 ms: 1.13x slower                                                       |
| sympy_sum               | 163 ms                                                       | 184 ms: 1.13x slower                                                        |
| async_tree_none         | 459 ms                                                       | 520 ms: 1.13x slower                                                        |
| chaos                   | 64.1 ms                                                      | 72.9 ms: 1.14x slower                                                       |
| nqueens                 | 90.1 ms                                                      | 103 ms: 1.14x slower                                                        |
| coroutines              | 23.1 ms                                                      | 27.9 ms: 1.21x slower                                                       |
| comprehensions          | 21.8 us                                                      | 26.9 us: 1.23x slower                                                       |
| coverage                | 66.3 ms                                                      | 86.9 ms: 1.31x slower                                                       |
| generators              | 37.3 ms                                                      | 61.2 ms: 1.64x slower                                                       |
| asyncio_tcp             | 380 ms                                                       | 749 ms: 1.97x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.02x slower                                                                |

Benchmark hidden because not significant (8): sqlglot_optimize, json_dumps, unpickle_pure_python, pickle, deepcopy_memo, richards, bench_thread_pool, nbody
Ignored benchmarks (11) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (4) of results/bm-20221114-3.12.0a2-3b9d793/bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 86.90% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
