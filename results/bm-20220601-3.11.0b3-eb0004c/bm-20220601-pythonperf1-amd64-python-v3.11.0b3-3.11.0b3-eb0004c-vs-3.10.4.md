
# Results vs. 3.10.4

- fork: python
- ref: v3.11.0b3
- machine: windows-amd64
- commit hash: eb0004c
- commit date: 2022-06-01
- overall geometric mean: 1.06x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 212 ms: 1.13x faster                                            |
| chameleon      | 6.02 ms                                                     | 5.63 ms: 1.07x faster                                           |
| docutils       | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                          |
| html5lib       | 47.5 ms                                                     | 41.2 ms: 1.15x faster                                           |
| tornado_http   | 106 ms                                                      | 94.8 ms: 1.11x faster                                           |
| Geometric mean | (ref)                                                       | 1.12x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 781 ms: 1.37x faster                                            |
| async_tree_memoization  | 505 ms                                                      | 402 ms: 1.25x faster                                            |
| async_tree_none         | 424 ms                                                      | 339 ms: 1.25x faster                                            |
| async_tree_cpu_io_mixed | 617 ms                                                      | 519 ms: 1.19x faster                                            |
| Geometric mean          | (ref)                                                       | 1.26x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 57.2 ms: 1.08x faster                                           |
| nbody          | 71.0 ms                                                     | 71.9 ms: 1.01x slower                                           |
| pidigits       | 146 ms                                                      | 154 ms: 1.05x slower                                            |
| Geometric mean | (ref)                                                       | 1.01x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 94.2 ms: 1.09x faster                                           |
| regex_dna      | 129 ms                                                      | 127 ms: 1.02x faster                                            |
| regex_v8       | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                           |
| regex_effbot   | 1.56 ms                                                     | 1.62 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                       | 1.01x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_pure_python   | 259 us                                                      | 212 us: 1.22x faster                                            |
| unpickle_pure_python | 177 us                                                      | 158 us: 1.12x faster                                            |
| xml_etree_process    | 43.1 ms                                                     | 38.9 ms: 1.11x faster                                           |
| json_dumps           | 8.77 ms                                                     | 7.98 ms: 1.10x faster                                           |
| unpickle             | 9.11 us                                                     | 8.33 us: 1.09x faster                                           |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.3 ms: 1.02x faster                                           |
| pickle               | 6.87 us                                                     | 6.83 us: 1.01x faster                                           |
| xml_etree_generate   | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                           |
| pickle_dict          | 17.1 us                                                     | 17.7 us: 1.04x slower                                           |
| pickle_list          | 2.69 us                                                     | 2.81 us: 1.05x slower                                           |
| Geometric mean       | (ref)                                                       | 1.04x faster                                                    |

Benchmark hidden because not significant (3): json_loads, xml_etree_parse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 19.4 ms: 1.02x faster                                           |
| python_startup_no_site | 15.3 ms                                                     | 16.4 ms: 1.07x slower                                           |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 7.38 ms: 1.22x faster                                           |
| django_template | 28.8 ms                                                     | 25.4 ms: 1.13x faster                                           |
| genshi_text     | 18.8 ms                                                     | 18.6 ms: 1.01x faster                                           |
| genshi_xml      | 39.4 ms                                                     | 41.0 ms: 1.04x slower                                           |
| Geometric mean  | (ref)                                                       | 1.08x faster                                                    |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-pythonperf1-amd64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.78 ms: 1.48x faster                                           |
| async_tree_io           | 1.07 sec                                                    | 781 ms: 1.37x faster                                            |
| scimark_sor             | 105 ms                                                      | 77.7 ms: 1.35x faster                                           |
| richards                | 40.6 ms                                                     | 30.7 ms: 1.32x faster                                           |
| scimark_lu              | 84.0 ms                                                     | 63.6 ms: 1.32x faster                                           |
| go                      | 135 ms                                                      | 104 ms: 1.30x faster                                            |
| logging_silent          | 93.4 ns                                                     | 72.7 ns: 1.28x faster                                           |
| scimark_monte_carlo     | 58.0 ms                                                     | 45.4 ms: 1.28x faster                                           |
| pyflate                 | 402 ms                                                      | 318 ms: 1.26x faster                                            |
| async_tree_memoization  | 505 ms                                                      | 402 ms: 1.25x faster                                            |
| async_tree_none         | 424 ms                                                      | 339 ms: 1.25x faster                                            |
| crypto_pyaes            | 63.1 ms                                                     | 50.9 ms: 1.24x faster                                           |
| raytrace                | 266 ms                                                      | 215 ms: 1.24x faster                                            |
| pycparser               | 905 ms                                                      | 735 ms: 1.23x faster                                            |
| pickle_pure_python      | 259 us                                                      | 212 us: 1.22x faster                                            |
| mako                    | 8.98 ms                                                     | 7.38 ms: 1.22x faster                                           |
| thrift                  | 623 us                                                      | 514 us: 1.21x faster                                            |
| async_tree_cpu_io_mixed | 617 ms                                                      | 519 ms: 1.19x faster                                            |
| mypy2                   | 347 ms                                                      | 293 ms: 1.18x faster                                            |
| create_gc_cycles        | 800 us                                                      | 686 us: 1.17x faster                                            |
| hexiom                  | 5.59 ms                                                     | 4.82 ms: 1.16x faster                                           |
| html5lib                | 47.5 ms                                                     | 41.2 ms: 1.15x faster                                           |
| chaos                   | 59.5 ms                                                     | 51.8 ms: 1.15x faster                                           |
| sqlalchemy_declarative  | 98.6 ms                                                     | 86.0 ms: 1.15x faster                                           |
| async_generators        | 219 ms                                                      | 192 ms: 1.14x faster                                            |
| django_template         | 28.8 ms                                                     | 25.4 ms: 1.13x faster                                           |
| docutils                | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                          |
| 2to3                    | 239 ms                                                      | 212 ms: 1.13x faster                                            |
| unpickle_pure_python    | 177 us                                                      | 158 us: 1.12x faster                                            |
| tornado_http            | 106 ms                                                      | 94.8 ms: 1.11x faster                                           |
| deepcopy_memo           | 29.0 us                                                     | 26.0 us: 1.11x faster                                           |
| xml_etree_process       | 43.1 ms                                                     | 38.9 ms: 1.11x faster                                           |
| spectral_norm           | 78.9 ms                                                     | 71.4 ms: 1.10x faster                                           |
| sqlglot_optimize        | 39.4 ms                                                     | 35.9 ms: 1.10x faster                                           |
| json_dumps              | 8.77 ms                                                     | 7.98 ms: 1.10x faster                                           |
| pprint_safe_repr        | 594 ms                                                      | 541 ms: 1.10x faster                                            |
| unpickle                | 9.11 us                                                     | 8.33 us: 1.09x faster                                           |
| sqlite_synth            | 1.90 us                                                     | 1.74 us: 1.09x faster                                           |
| pprint_pformat          | 1.22 sec                                                    | 1.12 sec: 1.09x faster                                          |
| unpack_sequence         | 40.0 ns                                                     | 36.8 ns: 1.09x faster                                           |
| regex_compile           | 102 ms                                                      | 94.2 ms: 1.09x faster                                           |
| dask                    | 305 ms                                                      | 281 ms: 1.08x faster                                            |
| sqlalchemy_imperative   | 11.2 ms                                                     | 10.3 ms: 1.08x faster                                           |
| float                   | 61.7 ms                                                     | 57.2 ms: 1.08x faster                                           |
| aiohttp                 | 961 us                                                      | 897 us: 1.07x faster                                            |
| chameleon               | 6.02 ms                                                     | 5.63 ms: 1.07x faster                                           |
| dulwich_log             | 48.6 ms                                                     | 45.5 ms: 1.07x faster                                           |
| logging_simple          | 6.28 us                                                     | 5.96 us: 1.05x faster                                           |
| sympy_integrate         | 15.0 ms                                                     | 14.2 ms: 1.05x faster                                           |
| sympy_sum               | 105 ms                                                      | 100 ms: 1.05x faster                                            |
| sympy_expand            | 320 ms                                                      | 306 ms: 1.05x faster                                            |
| logging_format          | 6.73 us                                                     | 6.43 us: 1.05x faster                                           |
| sqlglot_normalize       | 207 ms                                                      | 198 ms: 1.04x faster                                            |
| mdp                     | 1.71 sec                                                    | 1.66 sec: 1.03x faster                                          |
| pylint                  | 341 ms                                                      | 331 ms: 1.03x faster                                            |
| sqlglot_transpile       | 1.45 ms                                                     | 1.41 ms: 1.03x faster                                           |
| bench_thread_pool       | 913 us                                                      | 890 us: 1.03x faster                                            |
| xml_etree_iterparse     | 64.5 ms                                                     | 63.3 ms: 1.02x faster                                           |
| regex_dna               | 129 ms                                                      | 127 ms: 1.02x faster                                            |
| sympy_str               | 193 ms                                                      | 190 ms: 1.02x faster                                            |
| python_startup          | 19.7 ms                                                     | 19.4 ms: 1.02x faster                                           |
| genshi_text             | 18.8 ms                                                     | 18.6 ms: 1.01x faster                                           |
| pickle                  | 6.87 us                                                     | 6.83 us: 1.01x faster                                           |
| scimark_fft             | 187 ms                                                      | 188 ms: 1.01x slower                                            |
| flaskblogging           | 2.04 sec                                                    | 2.05 sec: 1.01x slower                                          |
| regex_v8                | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                           |
| pathlib                 | 72.8 ms                                                     | 73.6 ms: 1.01x slower                                           |
| coroutines              | 15.5 ms                                                     | 15.7 ms: 1.01x slower                                           |
| nbody                   | 71.0 ms                                                     | 71.9 ms: 1.01x slower                                           |
| deepcopy                | 259 us                                                      | 265 us: 1.02x slower                                            |
| xml_etree_generate      | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                           |
| regex_effbot            | 1.56 ms                                                     | 1.62 ms: 1.03x slower                                           |
| pickle_dict             | 17.1 us                                                     | 17.7 us: 1.04x slower                                           |
| genshi_xml              | 39.4 ms                                                     | 41.0 ms: 1.04x slower                                           |
| nqueens                 | 68.3 ms                                                     | 71.0 ms: 1.04x slower                                           |
| meteor_contest          | 73.8 ms                                                     | 77.1 ms: 1.04x slower                                           |
| pickle_list             | 2.69 us                                                     | 2.81 us: 1.05x slower                                           |
| pidigits                | 146 ms                                                      | 154 ms: 1.05x slower                                            |
| json                    | 3.10 ms                                                     | 3.26 ms: 1.05x slower                                           |
| asyncio_tcp             | 717 ms                                                      | 762 ms: 1.06x slower                                            |
| gc_traversal            | 1.40 ms                                                     | 1.49 ms: 1.06x slower                                           |
| python_startup_no_site  | 15.3 ms                                                     | 16.4 ms: 1.07x slower                                           |
| fannkuch                | 258 ms                                                      | 278 ms: 1.08x slower                                            |
| telco                   | 3.82 ms                                                     | 4.13 ms: 1.08x slower                                           |
| generators              | 31.8 ms                                                     | 35.4 ms: 1.11x slower                                           |
| bench_mp_pool           | 59.9 ms                                                     | 67.0 ms: 1.12x slower                                           |
| comprehensions          | 16.6 us                                                     | 18.7 us: 1.13x slower                                           |
| coverage                | 38.4 ms                                                     | 108 ms: 2.81x slower                                            |
| Geometric mean          | (ref)                                                       | 1.06x faster                                                    |

Benchmark hidden because not significant (6): json_loads, deepcopy_reduce, sqlglot_parse, scimark_sparse_mat_mult, xml_etree_parse, unpickle_list
Ignored benchmarks (4) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
