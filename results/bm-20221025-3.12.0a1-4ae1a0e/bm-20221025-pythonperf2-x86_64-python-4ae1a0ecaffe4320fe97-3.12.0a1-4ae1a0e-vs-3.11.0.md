
# Results vs. 3.11.0

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: linux-x86_64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 278 ms: 1.03x faster                                                        |
| chameleon      | 7.42 ms                                                      | 7.62 ms: 1.03x slower                                                       |
| docutils       | 2.87 sec                                                     | 2.79 sec: 1.03x faster                                                      |
| html5lib       | 70.7 ms                                                      | 66.2 ms: 1.07x faster                                                       |
| tornado_http   | 125 ms                                                       | 114 ms: 1.09x faster                                                        |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 618 ms: 1.05x faster                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.16 sec: 1.03x faster                                                      |
| async_tree_none         | 529 ms                                                       | 516 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed | 762 ms                                                       | 756 ms: 1.01x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 76.0 ms                                                      | 73.2 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                |

Benchmark hidden because not significant (2): pidigits, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 146 ms: 1.08x faster                                                        |
| regex_v8       | 23.7 ms                                                      | 22.9 ms: 1.03x faster                                                       |
| regex_effbot   | 3.42 ms                                                      | 3.34 ms: 1.02x faster                                                       |
| regex_dna      | 226 ms                                                       | 232 ms: 1.03x slower                                                        |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.4 ms: 1.30x faster                                                       |
| json_loads           | 29.0 us                                                      | 24.3 us: 1.19x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 138 ms: 1.15x faster                                                        |
| unpickle_pure_python | 236 us                                                       | 208 us: 1.14x faster                                                        |
| xml_etree_process    | 56.1 ms                                                      | 54.1 ms: 1.04x faster                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 77.6 ms: 1.04x faster                                                       |
| xml_etree_iterparse  | 106 ms                                                       | 103 ms: 1.03x faster                                                        |
| pickle_pure_python   | 318 us                                                       | 313 us: 1.02x faster                                                        |
| pickle_list          | 3.89 us                                                      | 3.84 us: 1.01x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 31.9 us: 1.00x slower                                                       |
| unpickle             | 13.2 us                                                      | 13.3 us: 1.01x slower                                                       |
| pickle               | 9.77 us                                                      | 10.1 us: 1.04x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.06x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.6 ms: 1.02x faster                                                       |
| python_startup_no_site | 7.78 ms                                                      | 7.62 ms: 1.02x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| genshi_text    | 26.1 ms                                                      | 24.7 ms: 1.06x faster                                                       |
| mako           | 11.0 ms                                                      | 10.4 ms: 1.05x faster                                                       |
| genshi_xml     | 57.2 ms                                                      | 55.5 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps              | 13.5 ms                                                      | 10.4 ms: 1.30x faster                                                       |
| mypy2                   | 449 ms                                                       | 372 ms: 1.21x faster                                                        |
| json_loads              | 29.0 us                                                      | 24.3 us: 1.19x faster                                                       |
| gc_traversal            | 4.06 ms                                                      | 3.54 ms: 1.15x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 138 ms: 1.15x faster                                                        |
| unpickle_pure_python    | 236 us                                                       | 208 us: 1.14x faster                                                        |
| fannkuch                | 457 ms                                                       | 405 ms: 1.13x faster                                                        |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 3.58 ms: 1.13x faster                                                       |
| gunicorn                | 986 us                                                       | 888 us: 1.11x faster                                                        |
| json                    | 5.59 ms                                                      | 5.05 ms: 1.11x faster                                                       |
| deltablue               | 4.03 ms                                                      | 3.65 ms: 1.10x faster                                                       |
| aiohttp                 | 984 us                                                       | 894 us: 1.10x faster                                                        |
| tornado_http            | 125 ms                                                       | 114 ms: 1.09x faster                                                        |
| regex_compile           | 157 ms                                                       | 146 ms: 1.08x faster                                                        |
| go                      | 166 ms                                                       | 155 ms: 1.07x faster                                                        |
| logging_silent          | 102 ns                                                       | 95.5 ns: 1.07x faster                                                       |
| html5lib                | 70.7 ms                                                      | 66.2 ms: 1.07x faster                                                       |
| bench_thread_pool       | 1.02 ms                                                      | 966 us: 1.06x faster                                                        |
| genshi_text             | 26.1 ms                                                      | 24.7 ms: 1.06x faster                                                       |
| mako                    | 11.0 ms                                                      | 10.4 ms: 1.05x faster                                                       |
| hexiom                  | 6.97 ms                                                      | 6.61 ms: 1.05x faster                                                       |
| pylint                  | 521 ms                                                       | 496 ms: 1.05x faster                                                        |
| pyflate                 | 453 ms                                                       | 431 ms: 1.05x faster                                                        |
| async_tree_memoization  | 648 ms                                                       | 618 ms: 1.05x faster                                                        |
| richards                | 49.9 ms                                                      | 47.6 ms: 1.05x faster                                                       |
| sympy_expand            | 550 ms                                                       | 527 ms: 1.04x faster                                                        |
| pprint_pformat          | 1.63 sec                                                     | 1.57 sec: 1.04x faster                                                      |
| telco                   | 6.91 ms                                                      | 6.64 ms: 1.04x faster                                                       |
| scimark_monte_carlo     | 70.6 ms                                                      | 67.8 ms: 1.04x faster                                                       |
| scimark_lu              | 115 ms                                                       | 111 ms: 1.04x faster                                                        |
| float                   | 76.0 ms                                                      | 73.2 ms: 1.04x faster                                                       |
| xml_etree_process       | 56.1 ms                                                      | 54.1 ms: 1.04x faster                                                       |
| xml_etree_generate      | 80.5 ms                                                      | 77.6 ms: 1.04x faster                                                       |
| dulwich_log             | 68.3 ms                                                      | 65.9 ms: 1.04x faster                                                       |
| meteor_contest          | 130 ms                                                       | 126 ms: 1.04x faster                                                        |
| generators              | 56.4 ms                                                      | 54.6 ms: 1.03x faster                                                       |
| regex_v8                | 23.7 ms                                                      | 22.9 ms: 1.03x faster                                                       |
| xml_etree_iterparse     | 106 ms                                                       | 103 ms: 1.03x faster                                                        |
| genshi_xml              | 57.2 ms                                                      | 55.5 ms: 1.03x faster                                                       |
| raytrace                | 308 ms                                                       | 298 ms: 1.03x faster                                                        |
| sympy_str               | 336 ms                                                       | 326 ms: 1.03x faster                                                        |
| 2to3                    | 286 ms                                                       | 278 ms: 1.03x faster                                                        |
| sqlglot_parse           | 1.55 ms                                                      | 1.51 ms: 1.03x faster                                                       |
| async_tree_io           | 1.19 sec                                                     | 1.16 sec: 1.03x faster                                                      |
| docutils                | 2.87 sec                                                     | 2.79 sec: 1.03x faster                                                      |
| deepcopy_memo           | 37.3 us                                                      | 36.4 us: 1.03x faster                                                       |
| pycparser               | 1.28 sec                                                     | 1.25 sec: 1.03x faster                                                      |
| pprint_safe_repr        | 780 ms                                                       | 761 ms: 1.02x faster                                                        |
| comprehensions          | 24.8 us                                                      | 24.2 us: 1.02x faster                                                       |
| async_tree_none         | 529 ms                                                       | 516 ms: 1.02x faster                                                        |
| sqlglot_transpile       | 1.94 ms                                                      | 1.90 ms: 1.02x faster                                                       |
| python_startup          | 10.8 ms                                                      | 10.6 ms: 1.02x faster                                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.62 ms: 1.02x faster                                                       |
| logging_simple          | 7.21 us                                                      | 7.06 us: 1.02x faster                                                       |
| regex_effbot            | 3.42 ms                                                      | 3.34 ms: 1.02x faster                                                       |
| nqueens                 | 99.2 ms                                                      | 97.1 ms: 1.02x faster                                                       |
| sqlglot_optimize        | 59.2 ms                                                      | 58.2 ms: 1.02x faster                                                       |
| dask                    | 417 ms                                                       | 409 ms: 1.02x faster                                                        |
| sympy_sum               | 184 ms                                                       | 181 ms: 1.02x faster                                                        |
| pickle_pure_python      | 318 us                                                       | 313 us: 1.02x faster                                                        |
| sqlglot_normalize       | 122 ms                                                       | 120 ms: 1.02x faster                                                        |
| coroutines              | 27.9 ms                                                      | 27.4 ms: 1.02x faster                                                       |
| pickle_list             | 3.89 us                                                      | 3.84 us: 1.01x faster                                                       |
| scimark_sor             | 109 ms                                                       | 108 ms: 1.01x faster                                                        |
| pathlib                 | 19.1 ms                                                      | 19.0 ms: 1.01x faster                                                       |
| sympy_integrate         | 25.6 ms                                                      | 25.4 ms: 1.01x faster                                                       |
| async_tree_cpu_io_mixed | 762 ms                                                       | 756 ms: 1.01x faster                                                        |
| asyncio_tcp             | 752 ms                                                       | 747 ms: 1.01x faster                                                        |
| mdp                     | 2.72 sec                                                     | 2.71 sec: 1.00x faster                                                      |
| pickle_dict             | 31.8 us                                                      | 31.9 us: 1.00x slower                                                       |
| unpickle                | 13.2 us                                                      | 13.3 us: 1.01x slower                                                       |
| deepcopy                | 389 us                                                       | 394 us: 1.01x slower                                                        |
| thrift                  | 941 us                                                       | 953 us: 1.01x slower                                                        |
| crypto_pyaes            | 81.8 ms                                                      | 83.2 ms: 1.02x slower                                                       |
| sqlite_synth            | 2.49 us                                                      | 2.54 us: 1.02x slower                                                       |
| spectral_norm           | 94.0 ms                                                      | 96.1 ms: 1.02x slower                                                       |
| scimark_fft             | 281 ms                                                       | 288 ms: 1.02x slower                                                        |
| chaos                   | 71.6 ms                                                      | 73.4 ms: 1.03x slower                                                       |
| regex_dna               | 226 ms                                                       | 232 ms: 1.03x slower                                                        |
| chameleon               | 7.42 ms                                                      | 7.62 ms: 1.03x slower                                                       |
| pickle                  | 9.77 us                                                      | 10.1 us: 1.04x slower                                                       |
| coverage                | 66.6 ms                                                      | 81.5 ms: 1.22x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.03x faster                                                                |

Benchmark hidden because not significant (10): bench_mp_pool, logging_format, deepcopy_reduce, async_generators, unpickle_list, pidigits, unpack_sequence, django_template, create_gc_cycles, nbody
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
