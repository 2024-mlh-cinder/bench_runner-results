
# Results vs. 3.11.0

- fork: python
- ref: 2e49bd06c5ffab7d1540
- machine: linux-x86_64
- commit hash: 2e49bd0
- commit date: 2022-04-05
- overall geometric mean: 1.02x slower \*
- HPT reliability: 99.72%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 293 ms: 1.02x slower                                                        |
| chameleon      | 7.42 ms                                                      | 7.97 ms: 1.07x slower                                                       |
| docutils       | 2.87 sec                                                     | 2.92 sec: 1.02x slower                                                      |
| html5lib       | 70.7 ms                                                      | 75.0 ms: 1.06x slower                                                       |
| tornado_http   | 125 ms                                                       | 123 ms: 1.01x faster                                                        |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 762 ms                                                       | 753 ms: 1.01x faster                                                        |
| async_tree_memoization  | 648 ms                                                       | 641 ms: 1.01x faster                                                        |
| async_tree_none         | 529 ms                                                       | 523 ms: 1.01x faster                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.18 sec: 1.01x faster                                                      |
| Geometric mean          | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 93.6 ms: 1.02x faster                                                       |
| float          | 76.0 ms                                                      | 78.4 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.13 ms: 1.09x faster                                                       |
| regex_compile  | 157 ms                                                       | 159 ms: 1.01x slower                                                        |
| regex_dna      | 226 ms                                                       | 253 ms: 1.12x slower                                                        |
| regex_v8       | 23.7 ms                                                      | 26.6 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads           | 29.0 us                                                      | 24.5 us: 1.18x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 31.1 us: 1.02x faster                                                       |
| unpickle             | 13.2 us                                                      | 13.0 us: 1.02x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 157 ms: 1.01x faster                                                        |
| unpickle_list        | 4.47 us                                                      | 4.52 us: 1.01x slower                                                       |
| pickle               | 9.77 us                                                      | 9.88 us: 1.01x slower                                                       |
| unpickle_pure_python | 236 us                                                       | 242 us: 1.03x slower                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 82.8 ms: 1.03x slower                                                       |
| xml_etree_process    | 56.1 ms                                                      | 58.3 ms: 1.04x slower                                                       |
| pickle_pure_python   | 318 us                                                       | 331 us: 1.04x slower                                                        |
| pickle_list          | 3.89 us                                                      | 4.12 us: 1.06x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_iterparse, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.4 ms: 1.04x faster                                                       |
| python_startup_no_site | 7.78 ms                                                      | 7.46 ms: 1.04x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.04x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako           | 11.0 ms                                                      | 11.2 ms: 1.02x slower                                                       |
| genshi_text    | 26.1 ms                                                      | 26.8 ms: 1.03x slower                                                       |
| genshi_xml     | 57.2 ms                                                      | 59.7 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads              | 29.0 us                                                      | 24.5 us: 1.18x faster                                                       |
| dask                    | 417 ms                                                       | 367 ms: 1.14x faster                                                        |
| gc_traversal            | 4.06 ms                                                      | 3.58 ms: 1.13x faster                                                       |
| regex_effbot            | 3.42 ms                                                      | 3.13 ms: 1.09x faster                                                       |
| json                    | 5.59 ms                                                      | 5.17 ms: 1.08x faster                                                       |
| logging_simple          | 7.21 us                                                      | 6.69 us: 1.08x faster                                                       |
| python_startup          | 10.8 ms                                                      | 10.4 ms: 1.04x faster                                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.46 ms: 1.04x faster                                                       |
| sympy_sum               | 184 ms                                                       | 177 ms: 1.04x faster                                                        |
| fannkuch                | 457 ms                                                       | 442 ms: 1.04x faster                                                        |
| logging_format          | 7.83 us                                                      | 7.59 us: 1.03x faster                                                       |
| generators              | 56.4 ms                                                      | 54.7 ms: 1.03x faster                                                       |
| nbody                   | 95.8 ms                                                      | 93.6 ms: 1.02x faster                                                       |
| pickle_dict             | 31.8 us                                                      | 31.1 us: 1.02x faster                                                       |
| gunicorn                | 986 us                                                       | 968 us: 1.02x faster                                                        |
| telco                   | 6.91 ms                                                      | 6.79 ms: 1.02x faster                                                       |
| sympy_str               | 336 ms                                                       | 330 ms: 1.02x faster                                                        |
| unpickle                | 13.2 us                                                      | 13.0 us: 1.02x faster                                                       |
| thrift                  | 941 us                                                       | 928 us: 1.01x faster                                                        |
| tornado_http            | 125 ms                                                       | 123 ms: 1.01x faster                                                        |
| sympy_integrate         | 25.6 ms                                                      | 25.3 ms: 1.01x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 157 ms: 1.01x faster                                                        |
| async_tree_cpu_io_mixed | 762 ms                                                       | 753 ms: 1.01x faster                                                        |
| async_tree_memoization  | 648 ms                                                       | 641 ms: 1.01x faster                                                        |
| async_tree_none         | 529 ms                                                       | 523 ms: 1.01x faster                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.18 sec: 1.01x faster                                                      |
| deepcopy                | 389 us                                                       | 385 us: 1.01x faster                                                        |
| async_generators        | 322 ms                                                       | 319 ms: 1.01x faster                                                        |
| asyncio_tcp             | 752 ms                                                       | 746 ms: 1.01x faster                                                        |
| aiohttp                 | 984 us                                                       | 978 us: 1.01x faster                                                        |
| pathlib                 | 19.1 ms                                                      | 19.3 ms: 1.01x slower                                                       |
| unpickle_list           | 4.47 us                                                      | 4.52 us: 1.01x slower                                                       |
| sqlite_synth            | 2.49 us                                                      | 2.52 us: 1.01x slower                                                       |
| pickle                  | 9.77 us                                                      | 9.88 us: 1.01x slower                                                       |
| regex_compile           | 157 ms                                                       | 159 ms: 1.01x slower                                                        |
| mdp                     | 2.72 sec                                                     | 2.76 sec: 1.01x slower                                                      |
| docutils                | 2.87 sec                                                     | 2.92 sec: 1.02x slower                                                      |
| mako                    | 11.0 ms                                                      | 11.2 ms: 1.02x slower                                                       |
| meteor_contest          | 130 ms                                                       | 133 ms: 1.02x slower                                                        |
| dulwich_log             | 68.3 ms                                                      | 69.8 ms: 1.02x slower                                                       |
| 2to3                    | 286 ms                                                       | 293 ms: 1.02x slower                                                        |
| pyflate                 | 453 ms                                                       | 464 ms: 1.02x slower                                                        |
| chaos                   | 71.6 ms                                                      | 73.4 ms: 1.02x slower                                                       |
| logging_silent          | 102 ns                                                       | 105 ns: 1.03x slower                                                        |
| unpickle_pure_python    | 236 us                                                       | 242 us: 1.03x slower                                                        |
| genshi_text             | 26.1 ms                                                      | 26.8 ms: 1.03x slower                                                       |
| scimark_sor             | 109 ms                                                       | 112 ms: 1.03x slower                                                        |
| xml_etree_generate      | 80.5 ms                                                      | 82.8 ms: 1.03x slower                                                       |
| sqlalchemy_imperative   | 19.9 ms                                                      | 20.5 ms: 1.03x slower                                                       |
| nqueens                 | 99.2 ms                                                      | 102 ms: 1.03x slower                                                        |
| float                   | 76.0 ms                                                      | 78.4 ms: 1.03x slower                                                       |
| deepcopy_reduce         | 3.37 us                                                      | 3.48 us: 1.03x slower                                                       |
| create_gc_cycles        | 1.59 ms                                                      | 1.65 ms: 1.03x slower                                                       |
| sqlalchemy_declarative  | 155 ms                                                       | 160 ms: 1.03x slower                                                        |
| pycparser               | 1.28 sec                                                     | 1.33 sec: 1.04x slower                                                      |
| pprint_pformat          | 1.63 sec                                                     | 1.69 sec: 1.04x slower                                                      |
| sqlglot_normalize       | 122 ms                                                       | 127 ms: 1.04x slower                                                        |
| xml_etree_process       | 56.1 ms                                                      | 58.3 ms: 1.04x slower                                                       |
| deepcopy_memo           | 37.3 us                                                      | 38.8 us: 1.04x slower                                                       |
| pickle_pure_python      | 318 us                                                       | 331 us: 1.04x slower                                                        |
| coroutines              | 27.9 ms                                                      | 29.0 ms: 1.04x slower                                                       |
| genshi_xml              | 57.2 ms                                                      | 59.7 ms: 1.04x slower                                                       |
| scimark_lu              | 115 ms                                                       | 120 ms: 1.04x slower                                                        |
| sqlglot_optimize        | 59.2 ms                                                      | 61.9 ms: 1.05x slower                                                       |
| raytrace                | 308 ms                                                       | 322 ms: 1.05x slower                                                        |
| pprint_safe_repr        | 780 ms                                                       | 818 ms: 1.05x slower                                                        |
| deltablue               | 4.03 ms                                                      | 4.23 ms: 1.05x slower                                                       |
| unpack_sequence         | 44.9 ns                                                      | 47.3 ns: 1.05x slower                                                       |
| scimark_fft             | 281 ms                                                       | 297 ms: 1.06x slower                                                        |
| pickle_list             | 3.89 us                                                      | 4.12 us: 1.06x slower                                                       |
| richards                | 49.9 ms                                                      | 52.8 ms: 1.06x slower                                                       |
| html5lib                | 70.7 ms                                                      | 75.0 ms: 1.06x slower                                                       |
| chameleon               | 7.42 ms                                                      | 7.97 ms: 1.07x slower                                                       |
| scimark_monte_carlo     | 70.6 ms                                                      | 77.1 ms: 1.09x slower                                                       |
| crypto_pyaes            | 81.8 ms                                                      | 89.5 ms: 1.09x slower                                                       |
| hexiom                  | 6.97 ms                                                      | 7.66 ms: 1.10x slower                                                       |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 4.51 ms: 1.12x slower                                                       |
| regex_dna               | 226 ms                                                       | 253 ms: 1.12x slower                                                        |
| comprehensions          | 24.8 us                                                      | 27.8 us: 1.12x slower                                                       |
| regex_v8                | 23.7 ms                                                      | 26.6 ms: 1.13x slower                                                       |
| spectral_norm           | 94.0 ms                                                      | 107 ms: 1.14x slower                                                        |
| sqlglot_transpile       | 1.94 ms                                                      | 2.38 ms: 1.23x slower                                                       |
| sqlglot_parse           | 1.55 ms                                                      | 2.04 ms: 1.31x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.02x slower                                                                |

Benchmark hidden because not significant (11): pylint, bench_mp_pool, xml_etree_iterparse, bench_thread_pool, sympy_expand, pidigits, flaskblogging, json_dumps, go, django_template, mypy2
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 99.72% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
