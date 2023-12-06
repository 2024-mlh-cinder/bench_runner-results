
# Results vs. 3.11.0

- fork: python
- ref: 8d32a5c8c4e9c90b0a21
- machine: linux-x86_64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.01x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 281 ms: 1.02x faster                                                        |
| chameleon      | 7.42 ms                                                      | 7.53 ms: 1.01x slower                                                       |
| docutils       | 2.87 sec                                                     | 2.82 sec: 1.02x faster                                                      |
| html5lib       | 70.7 ms                                                      | 69.0 ms: 1.02x faster                                                       |
| tornado_http   | 125 ms                                                       | 121 ms: 1.03x faster                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 624 ms: 1.04x faster                                                        |
| async_tree_none         | 529 ms                                                       | 516 ms: 1.02x faster                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                                      |
| async_tree_cpu_io_mixed | 762 ms                                                       | 748 ms: 1.02x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 76.0 ms                                                      | 74.7 ms: 1.02x faster                                                       |
| pidigits       | 251 ms                                                       | 251 ms: 1.00x slower                                                        |
| nbody          | 95.8 ms                                                      | 100 ms: 1.04x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 2.97 ms: 1.15x faster                                                       |
| regex_v8       | 23.7 ms                                                      | 22.8 ms: 1.04x faster                                                       |
| regex_compile  | 157 ms                                                       | 153 ms: 1.03x faster                                                        |
| regex_dna      | 226 ms                                                       | 232 ms: 1.02x slower                                                        |
| Geometric mean | (ref)                                                        | 1.05x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads           | 29.0 us                                                      | 24.6 us: 1.18x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 29.9 us: 1.06x faster                                                       |
| pickle_list          | 3.89 us                                                      | 3.81 us: 1.02x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 155 ms: 1.02x faster                                                        |
| pickle               | 9.77 us                                                      | 9.62 us: 1.02x faster                                                       |
| unpickle_pure_python | 236 us                                                       | 233 us: 1.01x faster                                                        |
| xml_etree_iterparse  | 106 ms                                                       | 105 ms: 1.01x faster                                                        |
| pickle_pure_python   | 318 us                                                       | 320 us: 1.01x slower                                                        |
| unpickle_list        | 4.47 us                                                      | 4.56 us: 1.02x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.02x faster                                                                |

Benchmark hidden because not significant (4): xml_etree_generate, xml_etree_process, json_dumps, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.5 ms: 1.03x faster                                                       |
| python_startup_no_site | 7.78 ms                                                      | 7.68 ms: 1.01x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| genshi_text     | 26.1 ms                                                      | 25.4 ms: 1.03x faster                                                       |
| mako            | 11.0 ms                                                      | 10.9 ms: 1.01x faster                                                       |
| django_template | 40.4 ms                                                      | 41.3 ms: 1.02x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.01x faster                                                                |

Benchmark hidden because not significant (1): genshi_xml

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-pythonperf2-x86_64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads              | 29.0 us                                                      | 24.6 us: 1.18x faster                                                       |
| regex_effbot            | 3.42 ms                                                      | 2.97 ms: 1.15x faster                                                       |
| fannkuch                | 457 ms                                                       | 418 ms: 1.09x faster                                                        |
| json                    | 5.59 ms                                                      | 5.14 ms: 1.09x faster                                                       |
| pickle_dict             | 31.8 us                                                      | 29.9 us: 1.06x faster                                                       |
| gunicorn                | 986 us                                                       | 928 us: 1.06x faster                                                        |
| go                      | 166 ms                                                       | 156 ms: 1.06x faster                                                        |
| gc_traversal            | 4.06 ms                                                      | 3.85 ms: 1.06x faster                                                       |
| pyflate                 | 453 ms                                                       | 433 ms: 1.05x faster                                                        |
| logging_simple          | 7.21 us                                                      | 6.90 us: 1.05x faster                                                       |
| aiohttp                 | 984 us                                                       | 945 us: 1.04x faster                                                        |
| pprint_pformat          | 1.63 sec                                                     | 1.57 sec: 1.04x faster                                                      |
| regex_v8                | 23.7 ms                                                      | 22.8 ms: 1.04x faster                                                       |
| async_tree_memoization  | 648 ms                                                       | 624 ms: 1.04x faster                                                        |
| nqueens                 | 99.2 ms                                                      | 95.8 ms: 1.03x faster                                                       |
| sympy_sum               | 184 ms                                                       | 178 ms: 1.03x faster                                                        |
| pprint_safe_repr        | 780 ms                                                       | 755 ms: 1.03x faster                                                        |
| tornado_http            | 125 ms                                                       | 121 ms: 1.03x faster                                                        |
| thrift                  | 941 us                                                       | 913 us: 1.03x faster                                                        |
| pylint                  | 521 ms                                                       | 505 ms: 1.03x faster                                                        |
| regex_compile           | 157 ms                                                       | 153 ms: 1.03x faster                                                        |
| genshi_text             | 26.1 ms                                                      | 25.4 ms: 1.03x faster                                                       |
| python_startup          | 10.8 ms                                                      | 10.5 ms: 1.03x faster                                                       |
| sqlglot_normalize       | 122 ms                                                       | 119 ms: 1.03x faster                                                        |
| flaskblogging           | 3.92 ms                                                      | 3.82 ms: 1.03x faster                                                       |
| async_tree_none         | 529 ms                                                       | 516 ms: 1.02x faster                                                        |
| deltablue               | 4.03 ms                                                      | 3.93 ms: 1.02x faster                                                       |
| html5lib                | 70.7 ms                                                      | 69.0 ms: 1.02x faster                                                       |
| pickle_list             | 3.89 us                                                      | 3.81 us: 1.02x faster                                                       |
| sqlalchemy_imperative   | 19.9 ms                                                      | 19.5 ms: 1.02x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 155 ms: 1.02x faster                                                        |
| logging_silent          | 102 ns                                                       | 99.8 ns: 1.02x faster                                                       |
| logging_format          | 7.83 us                                                      | 7.67 us: 1.02x faster                                                       |
| sympy_str               | 336 ms                                                       | 329 ms: 1.02x faster                                                        |
| scimark_monte_carlo     | 70.6 ms                                                      | 69.2 ms: 1.02x faster                                                       |
| sympy_expand            | 550 ms                                                       | 540 ms: 1.02x faster                                                        |
| pycparser               | 1.28 sec                                                     | 1.26 sec: 1.02x faster                                                      |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                                      |
| async_tree_cpu_io_mixed | 762 ms                                                       | 748 ms: 1.02x faster                                                        |
| sympy_integrate         | 25.6 ms                                                      | 25.2 ms: 1.02x faster                                                       |
| pathlib                 | 19.1 ms                                                      | 18.8 ms: 1.02x faster                                                       |
| float                   | 76.0 ms                                                      | 74.7 ms: 1.02x faster                                                       |
| 2to3                    | 286 ms                                                       | 281 ms: 1.02x faster                                                        |
| generators              | 56.4 ms                                                      | 55.5 ms: 1.02x faster                                                       |
| docutils                | 2.87 sec                                                     | 2.82 sec: 1.02x faster                                                      |
| pickle                  | 9.77 us                                                      | 9.62 us: 1.02x faster                                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.68 ms: 1.01x faster                                                       |
| unpickle_pure_python    | 236 us                                                       | 233 us: 1.01x faster                                                        |
| xml_etree_iterparse     | 106 ms                                                       | 105 ms: 1.01x faster                                                        |
| scimark_lu              | 115 ms                                                       | 114 ms: 1.01x faster                                                        |
| async_generators        | 322 ms                                                       | 318 ms: 1.01x faster                                                        |
| spectral_norm           | 94.0 ms                                                      | 93.1 ms: 1.01x faster                                                       |
| sqlalchemy_declarative  | 155 ms                                                       | 153 ms: 1.01x faster                                                        |
| hexiom                  | 6.97 ms                                                      | 6.91 ms: 1.01x faster                                                       |
| mako                    | 11.0 ms                                                      | 10.9 ms: 1.01x faster                                                       |
| sqlglot_optimize        | 59.2 ms                                                      | 58.9 ms: 1.01x faster                                                       |
| asyncio_tcp             | 752 ms                                                       | 749 ms: 1.00x faster                                                        |
| pidigits                | 251 ms                                                       | 251 ms: 1.00x slower                                                        |
| raytrace                | 308 ms                                                       | 309 ms: 1.00x slower                                                        |
| scimark_sor             | 109 ms                                                       | 110 ms: 1.01x slower                                                        |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 4.06 ms: 1.01x slower                                                       |
| pickle_pure_python      | 318 us                                                       | 320 us: 1.01x slower                                                        |
| coroutines              | 27.9 ms                                                      | 28.0 ms: 1.01x slower                                                       |
| crypto_pyaes            | 81.8 ms                                                      | 82.3 ms: 1.01x slower                                                       |
| meteor_contest          | 130 ms                                                       | 131 ms: 1.01x slower                                                        |
| deepcopy_memo           | 37.3 us                                                      | 37.6 us: 1.01x slower                                                       |
| sqlite_synth            | 2.49 us                                                      | 2.51 us: 1.01x slower                                                       |
| telco                   | 6.91 ms                                                      | 6.99 ms: 1.01x slower                                                       |
| chaos                   | 71.6 ms                                                      | 72.4 ms: 1.01x slower                                                       |
| deepcopy                | 389 us                                                       | 394 us: 1.01x slower                                                        |
| chameleon               | 7.42 ms                                                      | 7.53 ms: 1.01x slower                                                       |
| deepcopy_reduce         | 3.37 us                                                      | 3.42 us: 1.02x slower                                                       |
| django_template         | 40.4 ms                                                      | 41.3 ms: 1.02x slower                                                       |
| unpickle_list           | 4.47 us                                                      | 4.56 us: 1.02x slower                                                       |
| regex_dna               | 226 ms                                                       | 232 ms: 1.02x slower                                                        |
| mdp                     | 2.72 sec                                                     | 2.78 sec: 1.02x slower                                                      |
| unpack_sequence         | 44.9 ns                                                      | 46.2 ns: 1.03x slower                                                       |
| create_gc_cycles        | 1.59 ms                                                      | 1.64 ms: 1.03x slower                                                       |
| nbody                   | 95.8 ms                                                      | 100 ms: 1.04x slower                                                        |
| scimark_fft             | 281 ms                                                       | 294 ms: 1.04x slower                                                        |
| comprehensions          | 24.8 us                                                      | 28.2 us: 1.14x slower                                                       |
| sqlglot_transpile       | 1.94 ms                                                      | 2.30 ms: 1.19x slower                                                       |
| sqlglot_parse           | 1.55 ms                                                      | 1.95 ms: 1.25x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.01x faster                                                                |

Benchmark hidden because not significant (11): mypy2, bench_mp_pool, genshi_xml, dulwich_log, xml_etree_generate, xml_etree_process, bench_thread_pool, json_dumps, dask, richards, unpickle
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
