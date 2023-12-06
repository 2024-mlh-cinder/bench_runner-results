
# Results vs. 3.11.0

- fork: python
- ref: 2e91dba437fe5c56c6f8
- machine: linux-x86_64
- commit hash: 2e91dba
- commit date: 2021-12-08
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 293 ms: 1.03x slower                                                        |
| chameleon      | 7.42 ms                                                      | 8.85 ms: 1.19x slower                                                       |
| docutils       | 2.87 sec                                                     | 3.02 sec: 1.05x slower                                                      |
| html5lib       | 70.7 ms                                                      | 75.1 ms: 1.06x slower                                                       |
| tornado_http   | 125 ms                                                       | 135 ms: 1.08x slower                                                        |
| Geometric mean | (ref)                                                        | 1.08x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 529 ms                                                       | 545 ms: 1.03x slower                                                        |
| async_tree_memoization  | 648 ms                                                       | 686 ms: 1.06x slower                                                        |
| async_tree_cpu_io_mixed | 762 ms                                                       | 811 ms: 1.06x slower                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.32 sec: 1.11x slower                                                      |
| Geometric mean          | (ref)                                                        | 1.07x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 253 ms: 1.01x slower                                                        |
| float          | 76.0 ms                                                      | 80.9 ms: 1.06x slower                                                       |
| nbody          | 95.8 ms                                                      | 109 ms: 1.13x slower                                                        |
| Geometric mean | (ref)                                                        | 1.07x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.10 ms: 1.10x faster                                                       |
| regex_compile  | 157 ms                                                       | 153 ms: 1.03x faster                                                        |
| regex_v8       | 23.7 ms                                                      | 25.7 ms: 1.09x slower                                                       |
| regex_dna      | 226 ms                                                       | 261 ms: 1.15x slower                                                        |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads           | 29.0 us                                                      | 25.3 us: 1.14x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 155 ms: 1.02x faster                                                        |
| unpickle_list        | 4.47 us                                                      | 4.53 us: 1.01x slower                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 82.8 ms: 1.03x slower                                                       |
| xml_etree_iterparse  | 106 ms                                                       | 110 ms: 1.04x slower                                                        |
| pickle_dict          | 31.8 us                                                      | 33.0 us: 1.04x slower                                                       |
| json_dumps           | 13.5 ms                                                      | 14.1 ms: 1.04x slower                                                       |
| pickle               | 9.77 us                                                      | 10.2 us: 1.05x slower                                                       |
| xml_etree_process    | 56.1 ms                                                      | 60.9 ms: 1.08x slower                                                       |
| pickle_list          | 3.89 us                                                      | 4.32 us: 1.11x slower                                                       |
| unpickle_pure_python | 236 us                                                       | 265 us: 1.12x slower                                                        |
| pickle_pure_python   | 318 us                                                       | 366 us: 1.15x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.04x slower                                                                |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 7.78 ms                                                      | 7.14 ms: 1.09x faster                                                       |
| python_startup         | 10.8 ms                                                      | 10.1 ms: 1.07x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.08x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| genshi_xml      | 57.2 ms                                                      | 59.7 ms: 1.04x slower                                                       |
| genshi_text     | 26.1 ms                                                      | 28.2 ms: 1.08x slower                                                       |
| django_template | 40.4 ms                                                      | 44.9 ms: 1.11x slower                                                       |
| mako            | 11.0 ms                                                      | 12.9 ms: 1.17x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.10x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-pythonperf2-x86_64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads              | 29.0 us                                                      | 25.3 us: 1.14x faster                                                       |
| generators              | 56.4 ms                                                      | 50.1 ms: 1.13x faster                                                       |
| regex_effbot            | 3.42 ms                                                      | 3.10 ms: 1.10x faster                                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.14 ms: 1.09x faster                                                       |
| python_startup          | 10.8 ms                                                      | 10.1 ms: 1.07x faster                                                       |
| fannkuch                | 457 ms                                                       | 428 ms: 1.07x faster                                                        |
| json                    | 5.59 ms                                                      | 5.24 ms: 1.07x faster                                                       |
| scimark_lu              | 115 ms                                                       | 110 ms: 1.05x faster                                                        |
| gc_traversal            | 4.06 ms                                                      | 3.89 ms: 1.04x faster                                                       |
| coroutines              | 27.9 ms                                                      | 27.0 ms: 1.03x faster                                                       |
| regex_compile           | 157 ms                                                       | 153 ms: 1.03x faster                                                        |
| logging_simple          | 7.21 us                                                      | 7.04 us: 1.03x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 155 ms: 1.02x faster                                                        |
| logging_format          | 7.83 us                                                      | 7.70 us: 1.02x faster                                                       |
| meteor_contest          | 130 ms                                                       | 129 ms: 1.01x faster                                                        |
| async_generators        | 322 ms                                                       | 319 ms: 1.01x faster                                                        |
| pidigits                | 251 ms                                                       | 253 ms: 1.01x slower                                                        |
| unpickle_list           | 4.47 us                                                      | 4.53 us: 1.01x slower                                                       |
| gunicorn                | 986 us                                                       | 1.00 ms: 1.02x slower                                                       |
| mdp                     | 2.72 sec                                                     | 2.76 sec: 1.02x slower                                                      |
| sympy_sum               | 184 ms                                                       | 189 ms: 1.02x slower                                                        |
| 2to3                    | 286 ms                                                       | 293 ms: 1.03x slower                                                        |
| xml_etree_generate      | 80.5 ms                                                      | 82.8 ms: 1.03x slower                                                       |
| telco                   | 6.91 ms                                                      | 7.11 ms: 1.03x slower                                                       |
| async_tree_none         | 529 ms                                                       | 545 ms: 1.03x slower                                                        |
| unpack_sequence         | 44.9 ns                                                      | 46.3 ns: 1.03x slower                                                       |
| sympy_integrate         | 25.6 ms                                                      | 26.5 ms: 1.04x slower                                                       |
| bench_thread_pool       | 1.02 ms                                                      | 1.06 ms: 1.04x slower                                                       |
| xml_etree_iterparse     | 106 ms                                                       | 110 ms: 1.04x slower                                                        |
| nqueens                 | 99.2 ms                                                      | 103 ms: 1.04x slower                                                        |
| pickle_dict             | 31.8 us                                                      | 33.0 us: 1.04x slower                                                       |
| create_gc_cycles        | 1.59 ms                                                      | 1.66 ms: 1.04x slower                                                       |
| go                      | 166 ms                                                       | 173 ms: 1.04x slower                                                        |
| pathlib                 | 19.1 ms                                                      | 19.9 ms: 1.04x slower                                                       |
| sympy_str               | 336 ms                                                       | 350 ms: 1.04x slower                                                        |
| genshi_xml              | 57.2 ms                                                      | 59.7 ms: 1.04x slower                                                       |
| dask                    | 417 ms                                                       | 435 ms: 1.04x slower                                                        |
| json_dumps              | 13.5 ms                                                      | 14.1 ms: 1.04x slower                                                       |
| pickle                  | 9.77 us                                                      | 10.2 us: 1.05x slower                                                       |
| pycparser               | 1.28 sec                                                     | 1.35 sec: 1.05x slower                                                      |
| sympy_expand            | 550 ms                                                       | 579 ms: 1.05x slower                                                        |
| deepcopy_reduce         | 3.37 us                                                      | 3.55 us: 1.05x slower                                                       |
| docutils                | 2.87 sec                                                     | 3.02 sec: 1.05x slower                                                      |
| scimark_sor             | 109 ms                                                       | 115 ms: 1.05x slower                                                        |
| thrift                  | 941 us                                                       | 995 us: 1.06x slower                                                        |
| async_tree_memoization  | 648 ms                                                       | 686 ms: 1.06x slower                                                        |
| bench_mp_pool           | 4.63 ms                                                      | 4.90 ms: 1.06x slower                                                       |
| html5lib                | 70.7 ms                                                      | 75.1 ms: 1.06x slower                                                       |
| spectral_norm           | 94.0 ms                                                      | 99.9 ms: 1.06x slower                                                       |
| hexiom                  | 6.97 ms                                                      | 7.41 ms: 1.06x slower                                                       |
| pprint_pformat          | 1.63 sec                                                     | 1.74 sec: 1.06x slower                                                      |
| float                   | 76.0 ms                                                      | 80.9 ms: 1.06x slower                                                       |
| async_tree_cpu_io_mixed | 762 ms                                                       | 811 ms: 1.06x slower                                                        |
| pprint_safe_repr        | 780 ms                                                       | 832 ms: 1.07x slower                                                        |
| dulwich_log             | 68.3 ms                                                      | 73.0 ms: 1.07x slower                                                       |
| deepcopy                | 389 us                                                       | 418 us: 1.07x slower                                                        |
| tornado_http            | 125 ms                                                       | 135 ms: 1.08x slower                                                        |
| coverage                | 66.6 ms                                                      | 72.1 ms: 1.08x slower                                                       |
| genshi_text             | 26.1 ms                                                      | 28.2 ms: 1.08x slower                                                       |
| xml_etree_process       | 56.1 ms                                                      | 60.9 ms: 1.08x slower                                                       |
| sqlite_synth            | 2.49 us                                                      | 2.70 us: 1.09x slower                                                       |
| scimark_monte_carlo     | 70.6 ms                                                      | 76.7 ms: 1.09x slower                                                       |
| sqlglot_normalize       | 122 ms                                                       | 133 ms: 1.09x slower                                                        |
| regex_v8                | 23.7 ms                                                      | 25.7 ms: 1.09x slower                                                       |
| sqlglot_optimize        | 59.2 ms                                                      | 64.7 ms: 1.09x slower                                                       |
| chaos                   | 71.6 ms                                                      | 78.3 ms: 1.09x slower                                                       |
| async_tree_io           | 1.19 sec                                                     | 1.32 sec: 1.11x slower                                                      |
| pickle_list             | 3.89 us                                                      | 4.32 us: 1.11x slower                                                       |
| django_template         | 40.4 ms                                                      | 44.9 ms: 1.11x slower                                                       |
| deepcopy_memo           | 37.3 us                                                      | 41.5 us: 1.11x slower                                                       |
| scimark_fft             | 281 ms                                                       | 314 ms: 1.12x slower                                                        |
| unpickle_pure_python    | 236 us                                                       | 265 us: 1.12x slower                                                        |
| raytrace                | 308 ms                                                       | 347 ms: 1.13x slower                                                        |
| nbody                   | 95.8 ms                                                      | 109 ms: 1.13x slower                                                        |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 4.58 ms: 1.14x slower                                                       |
| richards                | 49.9 ms                                                      | 56.7 ms: 1.14x slower                                                       |
| logging_silent          | 102 ns                                                       | 116 ns: 1.14x slower                                                        |
| pickle_pure_python      | 318 us                                                       | 366 us: 1.15x slower                                                        |
| regex_dna               | 226 ms                                                       | 261 ms: 1.15x slower                                                        |
| crypto_pyaes            | 81.8 ms                                                      | 94.7 ms: 1.16x slower                                                       |
| pyflate                 | 453 ms                                                       | 525 ms: 1.16x slower                                                        |
| mako                    | 11.0 ms                                                      | 12.9 ms: 1.17x slower                                                       |
| deltablue               | 4.03 ms                                                      | 4.78 ms: 1.19x slower                                                       |
| chameleon               | 7.42 ms                                                      | 8.85 ms: 1.19x slower                                                       |
| comprehensions          | 24.8 us                                                      | 30.6 us: 1.23x slower                                                       |
| flaskblogging           | 3.92 ms                                                      | 4.95 ms: 1.26x slower                                                       |
| sqlglot_transpile       | 1.94 ms                                                      | 2.60 ms: 1.34x slower                                                       |
| sqlglot_parse           | 1.55 ms                                                      | 2.21 ms: 1.42x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.06x slower                                                                |

Benchmark hidden because not significant (1): unpickle
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.04x
