
# Results vs. 3.11.0

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: linux-x86_64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.03x faster \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| chameleon      | 7.42 ms                                                      | 7.31 ms: 1.02x faster                                                       |
| docutils       | 2.87 sec                                                     | 2.78 sec: 1.03x faster                                                      |
| html5lib       | 70.7 ms                                                      | 66.8 ms: 1.06x faster                                                       |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 608 ms: 1.07x faster                                                        |
| async_tree_none         | 529 ms                                                       | 505 ms: 1.05x faster                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.15 sec: 1.03x faster                                                      |
| async_tree_cpu_io_mixed | 762 ms                                                       | 742 ms: 1.03x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.04x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 76.0 ms                                                      | 72.4 ms: 1.05x faster                                                       |
| pidigits       | 251 ms                                                       | 252 ms: 1.00x slower                                                        |
| nbody          | 95.8 ms                                                      | 98.1 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 149 ms: 1.05x faster                                                        |
| regex_v8       | 23.7 ms                                                      | 23.0 ms: 1.03x faster                                                       |
| regex_effbot   | 3.42 ms                                                      | 3.43 ms: 1.00x slower                                                       |
| regex_dna      | 226 ms                                                       | 229 ms: 1.01x slower                                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.1 ms: 1.33x faster                                                       |
| json_loads           | 29.0 us                                                      | 24.0 us: 1.21x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 144 ms: 1.11x faster                                                        |
| unpickle_pure_python | 236 us                                                       | 214 us: 1.10x faster                                                        |
| pickle_list          | 3.89 us                                                      | 3.70 us: 1.05x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 31.1 us: 1.02x faster                                                       |
| pickle_pure_python   | 318 us                                                       | 313 us: 1.02x faster                                                        |
| xml_etree_iterparse  | 106 ms                                                       | 104 ms: 1.02x faster                                                        |
| xml_etree_process    | 56.1 ms                                                      | 55.4 ms: 1.01x faster                                                       |
| pickle               | 9.77 us                                                      | 9.71 us: 1.01x faster                                                       |
| unpickle             | 13.2 us                                                      | 13.3 us: 1.01x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.06x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_generate, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.8 ms: 1.00x faster                                                       |
| python_startup_no_site | 7.78 ms                                                      | 7.87 ms: 1.01x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.00x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 11.0 ms                                                      | 10.2 ms: 1.07x faster                                                       |
| genshi_xml      | 57.2 ms                                                      | 53.7 ms: 1.06x faster                                                       |
| genshi_text     | 26.1 ms                                                      | 24.8 ms: 1.05x faster                                                       |
| django_template | 40.4 ms                                                      | 39.2 ms: 1.03x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.06x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| asyncio_tcp             | 752 ms                                                       | 386 ms: 1.95x faster                                                        |
| json_dumps              | 13.5 ms                                                      | 10.1 ms: 1.33x faster                                                       |
| json_loads              | 29.0 us                                                      | 24.0 us: 1.21x faster                                                       |
| fannkuch                | 457 ms                                                       | 380 ms: 1.20x faster                                                        |
| mypy2                   | 449 ms                                                       | 380 ms: 1.18x faster                                                        |
| gc_traversal            | 4.06 ms                                                      | 3.54 ms: 1.15x faster                                                       |
| scimark_lu              | 115 ms                                                       | 101 ms: 1.14x faster                                                        |
| xml_etree_parse         | 159 ms                                                       | 144 ms: 1.11x faster                                                        |
| unpickle_pure_python    | 236 us                                                       | 214 us: 1.10x faster                                                        |
| deltablue               | 4.03 ms                                                      | 3.69 ms: 1.09x faster                                                       |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 3.70 ms: 1.09x faster                                                       |
| go                      | 166 ms                                                       | 153 ms: 1.08x faster                                                        |
| mako                    | 11.0 ms                                                      | 10.2 ms: 1.07x faster                                                       |
| json                    | 5.59 ms                                                      | 5.24 ms: 1.07x faster                                                       |
| async_tree_memoization  | 648 ms                                                       | 608 ms: 1.07x faster                                                        |
| genshi_xml              | 57.2 ms                                                      | 53.7 ms: 1.06x faster                                                       |
| richards                | 49.9 ms                                                      | 46.9 ms: 1.06x faster                                                       |
| scimark_monte_carlo     | 70.6 ms                                                      | 66.6 ms: 1.06x faster                                                       |
| html5lib                | 70.7 ms                                                      | 66.8 ms: 1.06x faster                                                       |
| nqueens                 | 99.2 ms                                                      | 94.0 ms: 1.05x faster                                                       |
| regex_compile           | 157 ms                                                       | 149 ms: 1.05x faster                                                        |
| pickle_list             | 3.89 us                                                      | 3.70 us: 1.05x faster                                                       |
| genshi_text             | 26.1 ms                                                      | 24.8 ms: 1.05x faster                                                       |
| float                   | 76.0 ms                                                      | 72.4 ms: 1.05x faster                                                       |
| async_tree_none         | 529 ms                                                       | 505 ms: 1.05x faster                                                        |
| pyflate                 | 453 ms                                                       | 433 ms: 1.04x faster                                                        |
| logging_simple          | 7.21 us                                                      | 6.95 us: 1.04x faster                                                       |
| thrift                  | 941 us                                                       | 908 us: 1.04x faster                                                        |
| bench_thread_pool       | 1.02 ms                                                      | 987 us: 1.03x faster                                                        |
| docutils                | 2.87 sec                                                     | 2.78 sec: 1.03x faster                                                      |
| telco                   | 6.91 ms                                                      | 6.70 ms: 1.03x faster                                                       |
| async_tree_io           | 1.19 sec                                                     | 1.15 sec: 1.03x faster                                                      |
| django_template         | 40.4 ms                                                      | 39.2 ms: 1.03x faster                                                       |
| raytrace                | 308 ms                                                       | 299 ms: 1.03x faster                                                        |
| regex_v8                | 23.7 ms                                                      | 23.0 ms: 1.03x faster                                                       |
| hexiom                  | 6.97 ms                                                      | 6.77 ms: 1.03x faster                                                       |
| deepcopy                | 389 us                                                       | 379 us: 1.03x faster                                                        |
| async_tree_cpu_io_mixed | 762 ms                                                       | 742 ms: 1.03x faster                                                        |
| sympy_expand            | 550 ms                                                       | 537 ms: 1.03x faster                                                        |
| logging_format          | 7.83 us                                                      | 7.66 us: 1.02x faster                                                       |
| unpack_sequence         | 44.9 ns                                                      | 44.0 ns: 1.02x faster                                                       |
| pickle_dict             | 31.8 us                                                      | 31.1 us: 1.02x faster                                                       |
| dask                    | 417 ms                                                       | 408 ms: 1.02x faster                                                        |
| pycparser               | 1.28 sec                                                     | 1.26 sec: 1.02x faster                                                      |
| deepcopy_memo           | 37.3 us                                                      | 36.7 us: 1.02x faster                                                       |
| pickle_pure_python      | 318 us                                                       | 313 us: 1.02x faster                                                        |
| chameleon               | 7.42 ms                                                      | 7.31 ms: 1.02x faster                                                       |
| xml_etree_iterparse     | 106 ms                                                       | 104 ms: 1.02x faster                                                        |
| xml_etree_process       | 56.1 ms                                                      | 55.4 ms: 1.01x faster                                                       |
| scimark_sor             | 109 ms                                                       | 108 ms: 1.01x faster                                                        |
| dulwich_log             | 68.3 ms                                                      | 67.5 ms: 1.01x faster                                                       |
| deepcopy_reduce         | 3.37 us                                                      | 3.33 us: 1.01x faster                                                       |
| crypto_pyaes            | 81.8 ms                                                      | 81.1 ms: 1.01x faster                                                       |
| pickle                  | 9.77 us                                                      | 9.71 us: 1.01x faster                                                       |
| python_startup          | 10.8 ms                                                      | 10.8 ms: 1.00x faster                                                       |
| regex_effbot            | 3.42 ms                                                      | 3.43 ms: 1.00x slower                                                       |
| pidigits                | 251 ms                                                       | 252 ms: 1.00x slower                                                        |
| scimark_fft             | 281 ms                                                       | 283 ms: 1.00x slower                                                        |
| meteor_contest          | 130 ms                                                       | 131 ms: 1.01x slower                                                        |
| sqlglot_transpile       | 1.94 ms                                                      | 1.95 ms: 1.01x slower                                                       |
| sqlglot_normalize       | 122 ms                                                       | 123 ms: 1.01x slower                                                        |
| sympy_sum               | 184 ms                                                       | 186 ms: 1.01x slower                                                        |
| unpickle                | 13.2 us                                                      | 13.3 us: 1.01x slower                                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.87 ms: 1.01x slower                                                       |
| mdp                     | 2.72 sec                                                     | 2.75 sec: 1.01x slower                                                      |
| regex_dna               | 226 ms                                                       | 229 ms: 1.01x slower                                                        |
| pathlib                 | 19.1 ms                                                      | 19.4 ms: 1.01x slower                                                       |
| pprint_safe_repr        | 780 ms                                                       | 794 ms: 1.02x slower                                                        |
| sqlglot_parse           | 1.55 ms                                                      | 1.59 ms: 1.02x slower                                                       |
| nbody                   | 95.8 ms                                                      | 98.1 ms: 1.02x slower                                                       |
| sqlite_synth            | 2.49 us                                                      | 2.56 us: 1.03x slower                                                       |
| bench_mp_pool           | 4.63 ms                                                      | 4.94 ms: 1.07x slower                                                       |
| generators              | 56.4 ms                                                      | 60.5 ms: 1.07x slower                                                       |
| spectral_norm           | 94.0 ms                                                      | 101 ms: 1.08x slower                                                        |
| comprehensions          | 24.8 us                                                      | 27.1 us: 1.09x slower                                                       |
| coverage                | 66.6 ms                                                      | 89.3 ms: 1.34x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.03x faster                                                                |

Benchmark hidden because not significant (12): chaos, create_gc_cycles, pprint_pformat, sympy_str, xml_etree_generate, logging_silent, sympy_integrate, 2to3, sqlglot_optimize, coroutines, async_generators, unpickle_list
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
