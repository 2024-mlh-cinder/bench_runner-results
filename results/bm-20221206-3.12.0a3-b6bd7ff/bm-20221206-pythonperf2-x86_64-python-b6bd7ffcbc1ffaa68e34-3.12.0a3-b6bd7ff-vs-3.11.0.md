
# Results vs. 3.11.0

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: linux-x86_64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.02x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 281 ms: 1.02x faster                                                        |
| chameleon      | 7.42 ms                                                      | 7.51 ms: 1.01x slower                                                       |
| docutils       | 2.87 sec                                                     | 2.76 sec: 1.04x faster                                                      |
| html5lib       | 70.7 ms                                                      | 66.2 ms: 1.07x faster                                                       |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_memoization | 648 ms                                                       | 623 ms: 1.04x faster                                                        |
| async_tree_io          | 1.19 sec                                                     | 1.18 sec: 1.01x faster                                                      |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                                |

Benchmark hidden because not significant (2): async_tree_none, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 76.0 ms                                                      | 73.2 ms: 1.04x faster                                                       |
| nbody          | 95.8 ms                                                      | 94.3 ms: 1.02x faster                                                       |
| pidigits       | 251 ms                                                       | 250 ms: 1.00x faster                                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 23.7 ms                                                      | 22.3 ms: 1.06x faster                                                       |
| regex_compile  | 157 ms                                                       | 150 ms: 1.05x faster                                                        |
| regex_effbot   | 3.42 ms                                                      | 3.44 ms: 1.01x slower                                                       |
| regex_dna      | 226 ms                                                       | 233 ms: 1.03x slower                                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.3 ms: 1.30x faster                                                       |
| json_loads           | 29.0 us                                                      | 24.2 us: 1.20x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 141 ms: 1.13x faster                                                        |
| unpickle_pure_python | 236 us                                                       | 212 us: 1.11x faster                                                        |
| xml_etree_generate   | 80.5 ms                                                      | 78.9 ms: 1.02x faster                                                       |
| xml_etree_process    | 56.1 ms                                                      | 55.6 ms: 1.01x faster                                                       |
| pickle_pure_python   | 318 us                                                       | 316 us: 1.01x faster                                                        |
| unpickle             | 13.2 us                                                      | 13.1 us: 1.01x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 31.9 us: 1.00x slower                                                       |
| pickle               | 9.77 us                                                      | 9.84 us: 1.01x slower                                                       |
| xml_etree_iterparse  | 106 ms                                                       | 108 ms: 1.02x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.05x faster                                                                |

Benchmark hidden because not significant (2): unpickle_list, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.8 ms: 1.00x faster                                                       |
| python_startup_no_site | 7.78 ms                                                      | 7.86 ms: 1.01x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.00x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| genshi_xml      | 57.2 ms                                                      | 53.5 ms: 1.07x faster                                                       |
| mako            | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                                       |
| django_template | 40.4 ms                                                      | 39.6 ms: 1.02x faster                                                       |
| genshi_text     | 26.1 ms                                                      | 25.8 ms: 1.01x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.04x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf2-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps              | 13.5 ms                                                      | 10.3 ms: 1.30x faster                                                       |
| mypy2                   | 449 ms                                                       | 375 ms: 1.20x faster                                                        |
| json_loads              | 29.0 us                                                      | 24.2 us: 1.20x faster                                                       |
| scimark_lu              | 115 ms                                                       | 100 ms: 1.15x faster                                                        |
| fannkuch                | 457 ms                                                       | 398 ms: 1.15x faster                                                        |
| xml_etree_parse         | 159 ms                                                       | 141 ms: 1.13x faster                                                        |
| unpickle_pure_python    | 236 us                                                       | 212 us: 1.11x faster                                                        |
| deltablue               | 4.03 ms                                                      | 3.67 ms: 1.10x faster                                                       |
| json                    | 5.59 ms                                                      | 5.11 ms: 1.10x faster                                                       |
| richards                | 49.9 ms                                                      | 46.1 ms: 1.08x faster                                                       |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 3.73 ms: 1.08x faster                                                       |
| gc_traversal            | 4.06 ms                                                      | 3.79 ms: 1.07x faster                                                       |
| genshi_xml              | 57.2 ms                                                      | 53.5 ms: 1.07x faster                                                       |
| html5lib                | 70.7 ms                                                      | 66.2 ms: 1.07x faster                                                       |
| mako                    | 11.0 ms                                                      | 10.4 ms: 1.06x faster                                                       |
| regex_v8                | 23.7 ms                                                      | 22.3 ms: 1.06x faster                                                       |
| thrift                  | 941 us                                                       | 894 us: 1.05x faster                                                        |
| regex_compile           | 157 ms                                                       | 150 ms: 1.05x faster                                                        |
| telco                   | 6.91 ms                                                      | 6.60 ms: 1.05x faster                                                       |
| pprint_pformat          | 1.63 sec                                                     | 1.56 sec: 1.05x faster                                                      |
| go                      | 166 ms                                                       | 159 ms: 1.04x faster                                                        |
| docutils                | 2.87 sec                                                     | 2.76 sec: 1.04x faster                                                      |
| async_tree_memoization  | 648 ms                                                       | 623 ms: 1.04x faster                                                        |
| float                   | 76.0 ms                                                      | 73.2 ms: 1.04x faster                                                       |
| bench_mp_pool           | 4.63 ms                                                      | 4.46 ms: 1.04x faster                                                       |
| hexiom                  | 6.97 ms                                                      | 6.73 ms: 1.04x faster                                                       |
| sqlglot_transpile       | 1.94 ms                                                      | 1.87 ms: 1.03x faster                                                       |
| deepcopy_memo           | 37.3 us                                                      | 36.2 us: 1.03x faster                                                       |
| pprint_safe_repr        | 780 ms                                                       | 758 ms: 1.03x faster                                                        |
| pyflate                 | 453 ms                                                       | 440 ms: 1.03x faster                                                        |
| logging_simple          | 7.21 us                                                      | 7.03 us: 1.03x faster                                                       |
| bench_thread_pool       | 1.02 ms                                                      | 994 us: 1.03x faster                                                        |
| deepcopy                | 389 us                                                       | 380 us: 1.03x faster                                                        |
| sqlglot_parse           | 1.55 ms                                                      | 1.52 ms: 1.02x faster                                                       |
| dulwich_log             | 68.3 ms                                                      | 66.7 ms: 1.02x faster                                                       |
| logging_silent          | 102 ns                                                       | 99.7 ns: 1.02x faster                                                       |
| sympy_expand            | 550 ms                                                       | 539 ms: 1.02x faster                                                        |
| pycparser               | 1.28 sec                                                     | 1.26 sec: 1.02x faster                                                      |
| django_template         | 40.4 ms                                                      | 39.6 ms: 1.02x faster                                                       |
| xml_etree_generate      | 80.5 ms                                                      | 78.9 ms: 1.02x faster                                                       |
| dask                    | 417 ms                                                       | 409 ms: 1.02x faster                                                        |
| 2to3                    | 286 ms                                                       | 281 ms: 1.02x faster                                                        |
| nbody                   | 95.8 ms                                                      | 94.3 ms: 1.02x faster                                                       |
| logging_format          | 7.83 us                                                      | 7.72 us: 1.01x faster                                                       |
| sympy_str               | 336 ms                                                       | 331 ms: 1.01x faster                                                        |
| sqlglot_optimize        | 59.2 ms                                                      | 58.5 ms: 1.01x faster                                                       |
| asyncio_tcp             | 752 ms                                                       | 743 ms: 1.01x faster                                                        |
| meteor_contest          | 130 ms                                                       | 129 ms: 1.01x faster                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.18 sec: 1.01x faster                                                      |
| genshi_text             | 26.1 ms                                                      | 25.8 ms: 1.01x faster                                                       |
| xml_etree_process       | 56.1 ms                                                      | 55.6 ms: 1.01x faster                                                       |
| pickle_pure_python      | 318 us                                                       | 316 us: 1.01x faster                                                        |
| pathlib                 | 19.1 ms                                                      | 19.0 ms: 1.01x faster                                                       |
| sqlglot_normalize       | 122 ms                                                       | 121 ms: 1.01x faster                                                        |
| unpickle                | 13.2 us                                                      | 13.1 us: 1.01x faster                                                       |
| sympy_sum               | 184 ms                                                       | 183 ms: 1.01x faster                                                        |
| pidigits                | 251 ms                                                       | 250 ms: 1.00x faster                                                        |
| python_startup          | 10.8 ms                                                      | 10.8 ms: 1.00x faster                                                       |
| sympy_integrate         | 25.6 ms                                                      | 25.6 ms: 1.00x faster                                                       |
| scimark_fft             | 281 ms                                                       | 282 ms: 1.00x slower                                                        |
| pickle_dict             | 31.8 us                                                      | 31.9 us: 1.00x slower                                                       |
| mdp                     | 2.72 sec                                                     | 2.73 sec: 1.00x slower                                                      |
| regex_effbot            | 3.42 ms                                                      | 3.44 ms: 1.01x slower                                                       |
| pickle                  | 9.77 us                                                      | 9.84 us: 1.01x slower                                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.86 ms: 1.01x slower                                                       |
| chameleon               | 7.42 ms                                                      | 7.51 ms: 1.01x slower                                                       |
| unpack_sequence         | 44.9 ns                                                      | 45.5 ns: 1.01x slower                                                       |
| xml_etree_iterparse     | 106 ms                                                       | 108 ms: 1.02x slower                                                        |
| spectral_norm           | 94.0 ms                                                      | 96.2 ms: 1.02x slower                                                       |
| nqueens                 | 99.2 ms                                                      | 102 ms: 1.03x slower                                                        |
| regex_dna               | 226 ms                                                       | 233 ms: 1.03x slower                                                        |
| scimark_monte_carlo     | 70.6 ms                                                      | 72.7 ms: 1.03x slower                                                       |
| async_generators        | 322 ms                                                       | 335 ms: 1.04x slower                                                        |
| sqlite_synth            | 2.49 us                                                      | 2.60 us: 1.05x slower                                                       |
| raytrace                | 308 ms                                                       | 327 ms: 1.06x slower                                                        |
| generators              | 56.4 ms                                                      | 60.8 ms: 1.08x slower                                                       |
| chaos                   | 71.6 ms                                                      | 78.3 ms: 1.09x slower                                                       |
| comprehensions          | 24.8 us                                                      | 27.3 us: 1.10x slower                                                       |
| coverage                | 66.6 ms                                                      | 85.0 ms: 1.28x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.02x faster                                                                |

Benchmark hidden because not significant (9): unpickle_list, deepcopy_reduce, scimark_sor, crypto_pyaes, pickle_list, create_gc_cycles, coroutines, async_tree_none, async_tree_cpu_io_mixed
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
