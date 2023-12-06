
# Results vs. 3.11.0

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: linux-x86_64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 282 ms: 1.01x faster                                                        |
| chameleon      | 7.42 ms                                                      | 7.19 ms: 1.03x faster                                                       |
| docutils       | 2.87 sec                                                     | 2.77 sec: 1.04x faster                                                      |
| html5lib       | 70.7 ms                                                      | 66.7 ms: 1.06x faster                                                       |
| tornado_http   | 125 ms                                                       | 115 ms: 1.08x faster                                                        |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_memoization | 648 ms                                                       | 621 ms: 1.04x faster                                                        |
| async_tree_io          | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                                      |
| async_tree_none        | 529 ms                                                       | 520 ms: 1.02x faster                                                        |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                                |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 90.9 ms: 1.05x faster                                                       |
| float          | 76.0 ms                                                      | 73.2 ms: 1.04x faster                                                       |
| pidigits       | 251 ms                                                       | 252 ms: 1.00x slower                                                        |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 147 ms: 1.07x faster                                                        |
| regex_v8       | 23.7 ms                                                      | 23.2 ms: 1.02x faster                                                       |
| regex_effbot   | 3.42 ms                                                      | 3.45 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                                       |
| json_loads           | 29.0 us                                                      | 23.7 us: 1.22x faster                                                       |
| unpickle_pure_python | 236 us                                                       | 209 us: 1.13x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 143 ms: 1.11x faster                                                        |
| pickle_list          | 3.89 us                                                      | 3.65 us: 1.07x faster                                                       |
| unpickle             | 13.2 us                                                      | 12.6 us: 1.05x faster                                                       |
| xml_etree_process    | 56.1 ms                                                      | 54.8 ms: 1.03x faster                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 79.3 ms: 1.01x faster                                                       |
| pickle_pure_python   | 318 us                                                       | 314 us: 1.01x faster                                                        |
| unpickle_list        | 4.47 us                                                      | 4.51 us: 1.01x slower                                                       |
| xml_etree_iterparse  | 106 ms                                                       | 108 ms: 1.02x slower                                                        |
| pickle               | 9.77 us                                                      | 10.1 us: 1.03x slower                                                       |
| pickle_dict          | 31.8 us                                                      | 33.4 us: 1.05x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.06x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.8 ms: 1.00x faster                                                       |
| python_startup_no_site | 7.78 ms                                                      | 7.87 ms: 1.01x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.01x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                                       |
| genshi_xml      | 57.2 ms                                                      | 54.0 ms: 1.06x faster                                                       |
| genshi_text     | 26.1 ms                                                      | 25.2 ms: 1.04x faster                                                       |
| django_template | 40.4 ms                                                      | 39.7 ms: 1.02x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.05x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf2-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps              | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                                       |
| json_loads              | 29.0 us                                                      | 23.7 us: 1.22x faster                                                       |
| mypy2                   | 449 ms                                                       | 374 ms: 1.20x faster                                                        |
| fannkuch                | 457 ms                                                       | 391 ms: 1.17x faster                                                        |
| json                    | 5.59 ms                                                      | 4.95 ms: 1.13x faster                                                       |
| unpickle_pure_python    | 236 us                                                       | 209 us: 1.13x faster                                                        |
| gunicorn                | 986 us                                                       | 886 us: 1.11x faster                                                        |
| xml_etree_parse         | 159 ms                                                       | 143 ms: 1.11x faster                                                        |
| deltablue               | 4.03 ms                                                      | 3.64 ms: 1.10x faster                                                       |
| richards                | 49.9 ms                                                      | 45.4 ms: 1.10x faster                                                       |
| aiohttp                 | 984 us                                                       | 904 us: 1.09x faster                                                        |
| tornado_http            | 125 ms                                                       | 115 ms: 1.08x faster                                                        |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 3.74 ms: 1.08x faster                                                       |
| mako                    | 11.0 ms                                                      | 10.2 ms: 1.08x faster                                                       |
| regex_compile           | 157 ms                                                       | 147 ms: 1.07x faster                                                        |
| pickle_list             | 3.89 us                                                      | 3.65 us: 1.07x faster                                                       |
| logging_simple          | 7.21 us                                                      | 6.78 us: 1.06x faster                                                       |
| scimark_monte_carlo     | 70.6 ms                                                      | 66.4 ms: 1.06x faster                                                       |
| genshi_xml              | 57.2 ms                                                      | 54.0 ms: 1.06x faster                                                       |
| html5lib                | 70.7 ms                                                      | 66.7 ms: 1.06x faster                                                       |
| nbody                   | 95.8 ms                                                      | 90.9 ms: 1.05x faster                                                       |
| pprint_pformat          | 1.63 sec                                                     | 1.55 sec: 1.05x faster                                                      |
| bench_thread_pool       | 1.02 ms                                                      | 969 us: 1.05x faster                                                        |
| telco                   | 6.91 ms                                                      | 6.58 ms: 1.05x faster                                                       |
| unpickle                | 13.2 us                                                      | 12.6 us: 1.05x faster                                                       |
| async_tree_memoization  | 648 ms                                                       | 621 ms: 1.04x faster                                                        |
| pyflate                 | 453 ms                                                       | 436 ms: 1.04x faster                                                        |
| float                   | 76.0 ms                                                      | 73.2 ms: 1.04x faster                                                       |
| genshi_text             | 26.1 ms                                                      | 25.2 ms: 1.04x faster                                                       |
| pprint_safe_repr        | 780 ms                                                       | 752 ms: 1.04x faster                                                        |
| gc_traversal            | 4.06 ms                                                      | 3.92 ms: 1.04x faster                                                       |
| docutils                | 2.87 sec                                                     | 2.77 sec: 1.04x faster                                                      |
| scimark_lu              | 115 ms                                                       | 111 ms: 1.04x faster                                                        |
| sqlglot_transpile       | 1.94 ms                                                      | 1.87 ms: 1.04x faster                                                       |
| sqlglot_parse           | 1.55 ms                                                      | 1.50 ms: 1.03x faster                                                       |
| go                      | 166 ms                                                       | 160 ms: 1.03x faster                                                        |
| pycparser               | 1.28 sec                                                     | 1.24 sec: 1.03x faster                                                      |
| chameleon               | 7.42 ms                                                      | 7.19 ms: 1.03x faster                                                       |
| thrift                  | 941 us                                                       | 913 us: 1.03x faster                                                        |
| hexiom                  | 6.97 ms                                                      | 6.76 ms: 1.03x faster                                                       |
| scimark_fft             | 281 ms                                                       | 273 ms: 1.03x faster                                                        |
| logging_format          | 7.83 us                                                      | 7.60 us: 1.03x faster                                                       |
| scimark_sor             | 109 ms                                                       | 106 ms: 1.03x faster                                                        |
| logging_silent          | 102 ns                                                       | 99.2 ns: 1.03x faster                                                       |
| xml_etree_process       | 56.1 ms                                                      | 54.8 ms: 1.03x faster                                                       |
| regex_v8                | 23.7 ms                                                      | 23.2 ms: 1.02x faster                                                       |
| sqlglot_optimize        | 59.2 ms                                                      | 58.2 ms: 1.02x faster                                                       |
| deepcopy_memo           | 37.3 us                                                      | 36.7 us: 1.02x faster                                                       |
| django_template         | 40.4 ms                                                      | 39.7 ms: 1.02x faster                                                       |
| dulwich_log             | 68.3 ms                                                      | 67.2 ms: 1.02x faster                                                       |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                                      |
| async_tree_none         | 529 ms                                                       | 520 ms: 1.02x faster                                                        |
| dask                    | 417 ms                                                       | 410 ms: 1.02x faster                                                        |
| xml_etree_generate      | 80.5 ms                                                      | 79.3 ms: 1.01x faster                                                       |
| pickle_pure_python      | 318 us                                                       | 314 us: 1.01x faster                                                        |
| meteor_contest          | 130 ms                                                       | 129 ms: 1.01x faster                                                        |
| crypto_pyaes            | 81.8 ms                                                      | 80.7 ms: 1.01x faster                                                       |
| 2to3                    | 286 ms                                                       | 282 ms: 1.01x faster                                                        |
| spectral_norm           | 94.0 ms                                                      | 93.2 ms: 1.01x faster                                                       |
| raytrace                | 308 ms                                                       | 305 ms: 1.01x faster                                                        |
| deepcopy                | 389 us                                                       | 387 us: 1.01x faster                                                        |
| asyncio_tcp             | 752 ms                                                       | 749 ms: 1.00x faster                                                        |
| sympy_integrate         | 25.6 ms                                                      | 25.5 ms: 1.00x faster                                                       |
| python_startup          | 10.8 ms                                                      | 10.8 ms: 1.00x faster                                                       |
| pidigits                | 251 ms                                                       | 252 ms: 1.00x slower                                                        |
| sympy_str               | 336 ms                                                       | 337 ms: 1.00x slower                                                        |
| mdp                     | 2.72 sec                                                     | 2.73 sec: 1.00x slower                                                      |
| pathlib                 | 19.1 ms                                                      | 19.3 ms: 1.01x slower                                                       |
| unpickle_list           | 4.47 us                                                      | 4.51 us: 1.01x slower                                                       |
| regex_effbot            | 3.42 ms                                                      | 3.45 ms: 1.01x slower                                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.87 ms: 1.01x slower                                                       |
| xml_etree_iterparse     | 106 ms                                                       | 108 ms: 1.02x slower                                                        |
| chaos                   | 71.6 ms                                                      | 72.9 ms: 1.02x slower                                                       |
| unpack_sequence         | 44.9 ns                                                      | 45.8 ns: 1.02x slower                                                       |
| pickle                  | 9.77 us                                                      | 10.1 us: 1.03x slower                                                       |
| sqlite_synth            | 2.49 us                                                      | 2.57 us: 1.03x slower                                                       |
| nqueens                 | 99.2 ms                                                      | 103 ms: 1.03x slower                                                        |
| pickle_dict             | 31.8 us                                                      | 33.4 us: 1.05x slower                                                       |
| comprehensions          | 24.8 us                                                      | 26.9 us: 1.08x slower                                                       |
| generators              | 56.4 ms                                                      | 61.2 ms: 1.09x slower                                                       |
| coverage                | 66.6 ms                                                      | 86.9 ms: 1.30x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.03x faster                                                                |

Benchmark hidden because not significant (10): bench_mp_pool, async_generators, sympy_expand, sympy_sum, coroutines, async_tree_cpu_io_mixed, regex_dna, sqlglot_normalize, create_gc_cycles, deepcopy_reduce
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
