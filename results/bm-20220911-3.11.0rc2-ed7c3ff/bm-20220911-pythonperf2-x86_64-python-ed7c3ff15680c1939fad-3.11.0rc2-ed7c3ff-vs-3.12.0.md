
# Results vs. 3.12.0

- fork: python
- ref: ed7c3ff15680c1939fad
- machine: linux-x86_64
- commit hash: ed7c3ff
- commit date: 2022-09-11
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 287 ms: 1.01x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.50 ms: 1.03x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.86 sec: 1.01x faster                                                       |
| tornado_http   | 122 ms                                                       | 125 ms: 1.03x slower                                                         |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 746 ms: 1.06x slower                                                         |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                                       |
| async_tree_none         | 459 ms                                                       | 517 ms: 1.13x slower                                                         |
| async_tree_memoization  | 554 ms                                                       | 636 ms: 1.15x slower                                                         |
| Geometric mean          | (ref)                                                        | 1.11x slower                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 75.1 ms: 1.09x faster                                                        |
| pidigits       | 264 ms                                                       | 251 ms: 1.05x faster                                                         |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                 |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.29 ms: 1.10x faster                                                        |
| regex_dna      | 240 ms                                                       | 225 ms: 1.07x faster                                                         |
| regex_v8       | 24.4 ms                                                      | 24.3 ms: 1.00x faster                                                        |
| regex_compile  | 145 ms                                                       | 157 ms: 1.09x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.0 us: 1.18x faster                                                        |
| pickle_list          | 4.22 us                                                      | 3.77 us: 1.12x faster                                                        |
| xml_etree_generate   | 85.3 ms                                                      | 80.8 ms: 1.06x faster                                                        |
| pickle               | 10.0 us                                                      | 9.61 us: 1.05x faster                                                        |
| pickle_dict          | 32.0 us                                                      | 30.7 us: 1.04x faster                                                        |
| xml_etree_process    | 58.3 ms                                                      | 57.0 ms: 1.02x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 324 us: 1.01x slower                                                         |
| xml_etree_parse      | 147 ms                                                       | 160 ms: 1.09x slower                                                         |
| json_loads           | 24.3 us                                                      | 28.4 us: 1.17x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 250 us: 1.19x slower                                                         |
| json_dumps           | 10.3 ms                                                      | 13.5 ms: 1.31x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.72 ms: 1.12x faster                                                        |
| python_startup         | 11.7 ms                                                      | 10.7 ms: 1.09x faster                                                        |
| Geometric mean         | (ref)                                                        | 1.11x faster                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 39.7 ms: 1.03x slower                                                        |
| mako            | 10.1 ms                                                      | 10.9 ms: 1.08x slower                                                        |
| Geometric mean  | (ref)                                                        | 1.05x slower                                                                 |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpack_sequence         | 54.5 ns                                                      | 45.7 ns: 1.19x faster                                                        |
| unpickle                | 15.3 us                                                      | 13.0 us: 1.18x faster                                                        |
| async_generators        | 385 ms                                                       | 328 ms: 1.17x faster                                                         |
| python_startup_no_site  | 8.67 ms                                                      | 7.72 ms: 1.12x faster                                                        |
| pickle_list             | 4.22 us                                                      | 3.77 us: 1.12x faster                                                        |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 4.01 ms: 1.12x faster                                                        |
| regex_effbot            | 3.61 ms                                                      | 3.29 ms: 1.10x faster                                                        |
| sqlite_synth            | 2.72 us                                                      | 2.48 us: 1.09x faster                                                        |
| scimark_fft             | 303 ms                                                       | 277 ms: 1.09x faster                                                         |
| bench_mp_pool           | 4.96 ms                                                      | 4.54 ms: 1.09x faster                                                        |
| python_startup          | 11.7 ms                                                      | 10.7 ms: 1.09x faster                                                        |
| float                   | 81.6 ms                                                      | 75.1 ms: 1.09x faster                                                        |
| gunicorn                | 1.01 ms                                                      | 941 us: 1.07x faster                                                         |
| regex_dna               | 240 ms                                                       | 225 ms: 1.07x faster                                                         |
| xml_etree_generate      | 85.3 ms                                                      | 80.8 ms: 1.06x faster                                                        |
| pidigits                | 264 ms                                                       | 251 ms: 1.05x faster                                                         |
| aiohttp                 | 1.02 ms                                                      | 966 us: 1.05x faster                                                         |
| pickle                  | 10.0 us                                                      | 9.61 us: 1.05x faster                                                        |
| pickle_dict             | 32.0 us                                                      | 30.7 us: 1.04x faster                                                        |
| telco                   | 7.16 ms                                                      | 6.88 ms: 1.04x faster                                                        |
| sqlalchemy_declarative  | 161 ms                                                       | 155 ms: 1.04x faster                                                         |
| xml_etree_process       | 58.3 ms                                                      | 57.0 ms: 1.02x faster                                                        |
| gc_traversal            | 3.70 ms                                                      | 3.63 ms: 1.02x faster                                                        |
| pprint_safe_repr        | 808 ms                                                       | 791 ms: 1.02x faster                                                         |
| docutils                | 2.89 sec                                                     | 2.86 sec: 1.01x faster                                                       |
| scimark_monte_carlo     | 69.5 ms                                                      | 68.7 ms: 1.01x faster                                                        |
| regex_v8                | 24.4 ms                                                      | 24.3 ms: 1.00x faster                                                        |
| sqlglot_optimize        | 58.4 ms                                                      | 58.8 ms: 1.01x slower                                                        |
| 2to3                    | 285 ms                                                       | 287 ms: 1.01x slower                                                         |
| pickle_pure_python      | 319 us                                                       | 324 us: 1.01x slower                                                         |
| sqlglot_normalize       | 119 ms                                                       | 121 ms: 1.02x slower                                                         |
| spectral_norm           | 93.9 ms                                                      | 95.5 ms: 1.02x slower                                                        |
| pyflate                 | 442 ms                                                       | 450 ms: 1.02x slower                                                         |
| pathlib                 | 18.7 ms                                                      | 19.1 ms: 1.02x slower                                                        |
| raytrace                | 301 ms                                                       | 307 ms: 1.02x slower                                                         |
| crypto_pyaes            | 82.4 ms                                                      | 84.3 ms: 1.02x slower                                                        |
| django_template         | 38.7 ms                                                      | 39.7 ms: 1.03x slower                                                        |
| scimark_sor             | 107 ms                                                       | 110 ms: 1.03x slower                                                         |
| tornado_http            | 122 ms                                                       | 125 ms: 1.03x slower                                                         |
| deepcopy_reduce         | 3.41 us                                                      | 3.51 us: 1.03x slower                                                        |
| chameleon               | 7.27 ms                                                      | 7.50 ms: 1.03x slower                                                        |
| pycparser               | 1.29 sec                                                     | 1.34 sec: 1.03x slower                                                       |
| meteor_contest          | 126 ms                                                       | 132 ms: 1.05x slower                                                         |
| bench_thread_pool       | 956 us                                                       | 1.00 ms: 1.05x slower                                                        |
| create_gc_cycles        | 1.58 ms                                                      | 1.66 ms: 1.05x slower                                                        |
| async_tree_cpu_io_mixed | 704 ms                                                       | 746 ms: 1.06x slower                                                         |
| mdp                     | 2.56 sec                                                     | 2.72 sec: 1.06x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 1.92 ms: 1.06x slower                                                        |
| dask                    | 394 ms                                                       | 420 ms: 1.07x slower                                                         |
| dulwich_log             | 64.9 ms                                                      | 69.6 ms: 1.07x slower                                                        |
| sqlalchemy_imperative   | 18.6 ms                                                      | 19.9 ms: 1.07x slower                                                        |
| json                    | 5.17 ms                                                      | 5.57 ms: 1.08x slower                                                        |
| sympy_integrate         | 24.0 ms                                                      | 25.9 ms: 1.08x slower                                                        |
| mako                    | 10.1 ms                                                      | 10.9 ms: 1.08x slower                                                        |
| logging_silent          | 93.3 ns                                                      | 101 ns: 1.08x slower                                                         |
| regex_compile           | 145 ms                                                       | 157 ms: 1.09x slower                                                         |
| xml_etree_parse         | 147 ms                                                       | 160 ms: 1.09x slower                                                         |
| deepcopy                | 371 us                                                       | 407 us: 1.10x slower                                                         |
| logging_format          | 7.29 us                                                      | 8.03 us: 1.10x slower                                                        |
| sympy_str               | 305 ms                                                       | 337 ms: 1.10x slower                                                         |
| sqlglot_parse           | 1.41 ms                                                      | 1.56 ms: 1.11x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                                       |
| logging_simple          | 6.64 us                                                      | 7.43 us: 1.12x slower                                                        |
| deepcopy_memo           | 36.6 us                                                      | 41.0 us: 1.12x slower                                                        |
| nqueens                 | 90.1 ms                                                      | 101 ms: 1.12x slower                                                         |
| sympy_expand            | 492 ms                                                       | 553 ms: 1.12x slower                                                         |
| sympy_sum               | 163 ms                                                       | 183 ms: 1.13x slower                                                         |
| async_tree_none         | 459 ms                                                       | 517 ms: 1.13x slower                                                         |
| async_tree_memoization  | 554 ms                                                       | 636 ms: 1.15x slower                                                         |
| go                      | 149 ms                                                       | 172 ms: 1.15x slower                                                         |
| scimark_lu              | 98.6 ms                                                      | 114 ms: 1.15x slower                                                         |
| json_loads              | 24.3 us                                                      | 28.4 us: 1.17x slower                                                        |
| comprehensions          | 21.8 us                                                      | 25.5 us: 1.17x slower                                                        |
| richards                | 45.1 ms                                                      | 53.5 ms: 1.19x slower                                                        |
| unpickle_pure_python    | 210 us                                                       | 250 us: 1.19x slower                                                         |
| hexiom                  | 5.97 ms                                                      | 7.12 ms: 1.19x slower                                                        |
| coroutines              | 23.1 ms                                                      | 27.9 ms: 1.21x slower                                                        |
| fannkuch                | 362 ms                                                       | 441 ms: 1.22x slower                                                         |
| mypy2                   | 365 ms                                                       | 451 ms: 1.23x slower                                                         |
| deltablue               | 3.24 ms                                                      | 4.09 ms: 1.26x slower                                                        |
| chaos                   | 64.1 ms                                                      | 81.4 ms: 1.27x slower                                                        |
| json_dumps              | 10.3 ms                                                      | 13.5 ms: 1.31x slower                                                        |
| generators              | 37.3 ms                                                      | 54.2 ms: 1.45x slower                                                        |
| asyncio_tcp             | 380 ms                                                       | 752 ms: 1.98x slower                                                         |
| Geometric mean          | (ref)                                                        | 1.05x slower                                                                 |

Benchmark hidden because not significant (4): xml_etree_iterparse, pprint_pformat, unpickle_list, nbody
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20220911-3.11.0rc2-ed7c3ff/bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
