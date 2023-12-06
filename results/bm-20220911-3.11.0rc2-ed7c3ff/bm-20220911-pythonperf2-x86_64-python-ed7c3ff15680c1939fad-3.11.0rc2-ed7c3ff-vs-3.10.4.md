
# Results vs. 3.10.4

- fork: python
- ref: ed7c3ff15680c1939fad
- machine: linux-x86_64
- commit hash: ed7c3ff
- commit date: 2022-09-11
- overall geometric mean: 1.22x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 287 ms: 1.22x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.50 ms: 1.32x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.86 sec: 1.20x faster                                                       |
| html5lib       | 94.7 ms                                                      | 73.2 ms: 1.29x faster                                                        |
| tornado_http   | 157 ms                                                       | 125 ms: 1.25x faster                                                         |
| Geometric mean | (ref)                                                        | 1.25x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.37x faster                                                       |
| async_tree_none         | 700 ms                                                       | 517 ms: 1.35x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 636 ms: 1.30x faster                                                         |
| async_tree_cpu_io_mixed | 946 ms                                                       | 746 ms: 1.27x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.32x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 89.6 ms: 1.50x faster                                                        |
| float          | 109 ms                                                       | 75.1 ms: 1.45x faster                                                        |
| pidigits       | 270 ms                                                       | 251 ms: 1.08x faster                                                         |
| Geometric mean | (ref)                                                        | 1.33x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 157 ms: 1.22x faster                                                         |
| regex_dna      | 260 ms                                                       | 225 ms: 1.16x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 24.3 ms: 1.11x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.29 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                        | 1.10x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 324 us: 1.40x faster                                                         |
| xml_etree_process    | 76.4 ms                                                      | 57.0 ms: 1.34x faster                                                        |
| unpickle_pure_python | 315 us                                                       | 250 us: 1.26x faster                                                         |
| xml_etree_generate   | 93.1 ms                                                      | 80.8 ms: 1.15x faster                                                        |
| pickle_list          | 4.23 us                                                      | 3.77 us: 1.12x faster                                                        |
| unpickle             | 13.9 us                                                      | 13.0 us: 1.07x faster                                                        |
| json_loads           | 30.0 us                                                      | 28.4 us: 1.06x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 13.5 ms: 1.06x faster                                                        |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.06x faster                                                         |
| pickle               | 10.1 us                                                      | 9.61 us: 1.05x faster                                                        |
| pickle_dict          | 30.4 us                                                      | 30.7 us: 1.01x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.72 us: 1.06x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.11x faster                                                                 |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.7 ms: 1.08x faster                                                        |
| python_startup_no_site | 7.35 ms                                                      | 7.72 ms: 1.05x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                                        |
| django_template | 51.8 ms                                                      | 39.7 ms: 1.30x faster                                                        |
| genshi_text     | 32.3 ms                                                      | 26.1 ms: 1.24x faster                                                        |
| genshi_xml      | 64.1 ms                                                      | 59.2 ms: 1.08x faster                                                        |
| Geometric mean  | (ref)                                                        | 1.24x faster                                                                 |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf2-x86_64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 4.09 ms: 1.81x faster                                                        |
| scimark_sor             | 183 ms                                                       | 110 ms: 1.67x faster                                                         |
| logging_silent          | 168 ns                                                       | 101 ns: 1.66x faster                                                         |
| raytrace                | 497 ms                                                       | 307 ms: 1.62x faster                                                         |
| scimark_monte_carlo     | 109 ms                                                       | 68.7 ms: 1.59x faster                                                        |
| pyflate                 | 698 ms                                                       | 450 ms: 1.55x faster                                                         |
| bench_mp_pool           | 6.82 ms                                                      | 4.54 ms: 1.50x faster                                                        |
| go                      | 258 ms                                                       | 172 ms: 1.50x faster                                                         |
| nbody                   | 134 ms                                                       | 89.6 ms: 1.50x faster                                                        |
| spectral_norm           | 141 ms                                                       | 95.5 ms: 1.48x faster                                                        |
| sqlglot_parse           | 2.27 ms                                                      | 1.56 ms: 1.45x faster                                                        |
| float                   | 109 ms                                                       | 75.1 ms: 1.45x faster                                                        |
| scimark_lu              | 165 ms                                                       | 114 ms: 1.45x faster                                                         |
| richards                | 76.3 ms                                                      | 53.5 ms: 1.43x faster                                                        |
| sqlglot_transpile       | 2.73 ms                                                      | 1.92 ms: 1.42x faster                                                        |
| crypto_pyaes            | 118 ms                                                       | 84.3 ms: 1.40x faster                                                        |
| pickle_pure_python      | 453 us                                                       | 324 us: 1.40x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.37x faster                                                       |
| async_tree_none         | 700 ms                                                       | 517 ms: 1.35x faster                                                         |
| mako                    | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                                        |
| xml_etree_process       | 76.4 ms                                                      | 57.0 ms: 1.34x faster                                                        |
| hexiom                  | 9.46 ms                                                      | 7.12 ms: 1.33x faster                                                        |
| thrift                  | 1.20 ms                                                      | 906 us: 1.32x faster                                                         |
| unpack_sequence         | 60.3 ns                                                      | 45.7 ns: 1.32x faster                                                        |
| chameleon               | 9.88 ms                                                      | 7.50 ms: 1.32x faster                                                        |
| pprint_safe_repr        | 1.04 sec                                                     | 791 ms: 1.31x faster                                                         |
| scimark_fft             | 363 ms                                                       | 277 ms: 1.31x faster                                                         |
| pprint_pformat          | 2.15 sec                                                     | 1.65 sec: 1.31x faster                                                       |
| django_template         | 51.8 ms                                                      | 39.7 ms: 1.30x faster                                                        |
| chaos                   | 106 ms                                                       | 81.4 ms: 1.30x faster                                                        |
| async_tree_memoization  | 827 ms                                                       | 636 ms: 1.30x faster                                                         |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 4.01 ms: 1.30x faster                                                        |
| html5lib                | 94.7 ms                                                      | 73.2 ms: 1.29x faster                                                        |
| gunicorn                | 1.20 ms                                                      | 941 us: 1.28x faster                                                         |
| async_generators        | 418 ms                                                       | 328 ms: 1.28x faster                                                         |
| async_tree_cpu_io_mixed | 946 ms                                                       | 746 ms: 1.27x faster                                                         |
| unpickle_pure_python    | 315 us                                                       | 250 us: 1.26x faster                                                         |
| aiohttp                 | 1.21 ms                                                      | 966 us: 1.25x faster                                                         |
| tornado_http            | 157 ms                                                       | 125 ms: 1.25x faster                                                         |
| genshi_text             | 32.3 ms                                                      | 26.1 ms: 1.24x faster                                                        |
| pycparser               | 1.65 sec                                                     | 1.34 sec: 1.23x faster                                                       |
| deepcopy_memo           | 50.5 us                                                      | 41.0 us: 1.23x faster                                                        |
| logging_format          | 9.82 us                                                      | 8.03 us: 1.22x faster                                                        |
| regex_compile           | 192 ms                                                       | 157 ms: 1.22x faster                                                         |
| logging_simple          | 9.06 us                                                      | 7.43 us: 1.22x faster                                                        |
| sqlalchemy_declarative  | 189 ms                                                       | 155 ms: 1.22x faster                                                         |
| 2to3                    | 349 ms                                                       | 287 ms: 1.22x faster                                                         |
| sqlglot_normalize       | 146 ms                                                       | 121 ms: 1.21x faster                                                         |
| docutils                | 3.42 sec                                                     | 2.86 sec: 1.20x faster                                                       |
| sqlite_synth            | 2.97 us                                                      | 2.48 us: 1.20x faster                                                        |
| sqlglot_optimize        | 69.9 ms                                                      | 58.8 ms: 1.19x faster                                                        |
| flaskblogging           | 4.44 ms                                                      | 3.80 ms: 1.17x faster                                                        |
| regex_dna               | 260 ms                                                       | 225 ms: 1.16x faster                                                         |
| sqlalchemy_imperative   | 23.0 ms                                                      | 19.9 ms: 1.15x faster                                                        |
| xml_etree_generate      | 93.1 ms                                                      | 80.8 ms: 1.15x faster                                                        |
| dulwich_log             | 80.0 ms                                                      | 69.6 ms: 1.15x faster                                                        |
| deepcopy_reduce         | 4.00 us                                                      | 3.51 us: 1.14x faster                                                        |
| bench_thread_pool       | 1.13 ms                                                      | 1.00 ms: 1.13x faster                                                        |
| deepcopy                | 459 us                                                       | 407 us: 1.13x faster                                                         |
| pickle_list             | 4.23 us                                                      | 3.77 us: 1.12x faster                                                        |
| dask                    | 469 ms                                                       | 420 ms: 1.12x faster                                                         |
| regex_v8                | 27.1 ms                                                      | 24.3 ms: 1.11x faster                                                        |
| fannkuch                | 488 ms                                                       | 441 ms: 1.11x faster                                                         |
| coroutines              | 30.9 ms                                                      | 27.9 ms: 1.11x faster                                                        |
| nqueens                 | 112 ms                                                       | 101 ms: 1.11x faster                                                         |
| pathlib                 | 21.2 ms                                                      | 19.1 ms: 1.11x faster                                                        |
| sympy_integrate         | 28.3 ms                                                      | 25.9 ms: 1.09x faster                                                        |
| pylint                  | 564 ms                                                       | 520 ms: 1.08x faster                                                         |
| sympy_expand            | 599 ms                                                       | 553 ms: 1.08x faster                                                         |
| genshi_xml              | 64.1 ms                                                      | 59.2 ms: 1.08x faster                                                        |
| mdp                     | 2.94 sec                                                     | 2.72 sec: 1.08x faster                                                       |
| python_startup          | 11.5 ms                                                      | 10.7 ms: 1.08x faster                                                        |
| create_gc_cycles        | 1.79 ms                                                      | 1.66 ms: 1.08x faster                                                        |
| pidigits                | 270 ms                                                       | 251 ms: 1.08x faster                                                         |
| unpickle                | 13.9 us                                                      | 13.0 us: 1.07x faster                                                        |
| sympy_str               | 359 ms                                                       | 337 ms: 1.06x faster                                                         |
| generators              | 57.7 ms                                                      | 54.2 ms: 1.06x faster                                                        |
| comprehensions          | 27.0 us                                                      | 25.5 us: 1.06x faster                                                        |
| json                    | 5.91 ms                                                      | 5.57 ms: 1.06x faster                                                        |
| sympy_sum               | 194 ms                                                       | 183 ms: 1.06x faster                                                         |
| json_loads              | 30.0 us                                                      | 28.4 us: 1.06x faster                                                        |
| json_dumps              | 14.2 ms                                                      | 13.5 ms: 1.06x faster                                                        |
| xml_etree_iterparse     | 110 ms                                                       | 104 ms: 1.06x faster                                                         |
| pickle                  | 10.1 us                                                      | 9.61 us: 1.05x faster                                                        |
| telco                   | 7.21 ms                                                      | 6.88 ms: 1.05x faster                                                        |
| asyncio_tcp             | 785 ms                                                       | 752 ms: 1.04x faster                                                         |
| meteor_contest          | 138 ms                                                       | 132 ms: 1.04x faster                                                         |
| pickle_dict             | 30.4 us                                                      | 30.7 us: 1.01x slower                                                        |
| python_startup_no_site  | 7.35 ms                                                      | 7.72 ms: 1.05x slower                                                        |
| unpickle_list           | 4.45 us                                                      | 4.72 us: 1.06x slower                                                        |
| regex_effbot            | 3.10 ms                                                      | 3.29 ms: 1.06x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.22x faster                                                                 |

Benchmark hidden because not significant (3): mypy2, gc_traversal, xml_etree_parse
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.15x
