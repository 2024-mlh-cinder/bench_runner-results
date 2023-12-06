
# Results vs. 3.10.4

- fork: python
- ref: v3.11.0b2
- machine: windows-amd64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 211 ms: 1.13x faster                                            |
| chameleon      | 6.02 ms                                                     | 5.59 ms: 1.08x faster                                           |
| docutils       | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                          |
| html5lib       | 47.5 ms                                                     | 41.4 ms: 1.15x faster                                           |
| tornado_http   | 106 ms                                                      | 95.3 ms: 1.11x faster                                           |
| Geometric mean | (ref)                                                       | 1.12x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 794 ms: 1.35x faster                                            |
| async_tree_memoization  | 505 ms                                                      | 400 ms: 1.26x faster                                            |
| async_tree_none         | 424 ms                                                      | 336 ms: 1.26x faster                                            |
| async_tree_cpu_io_mixed | 617 ms                                                      | 520 ms: 1.19x faster                                            |
| Geometric mean          | (ref)                                                       | 1.26x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.5 ms: 1.13x faster                                           |
| nbody          | 71.0 ms                                                     | 70.1 ms: 1.01x faster                                           |
| pidigits       | 146 ms                                                      | 153 ms: 1.05x slower                                            |
| Geometric mean | (ref)                                                       | 1.03x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_effbot   | 1.56 ms                                                     | 1.39 ms: 1.13x faster                                           |
| regex_dna      | 129 ms                                                      | 120 ms: 1.08x faster                                            |
| regex_compile  | 102 ms                                                      | 97.0 ms: 1.05x faster                                           |
| regex_v8       | 15.0 ms                                                     | 14.4 ms: 1.04x faster                                           |
| Geometric mean | (ref)                                                       | 1.08x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_pure_python   | 259 us                                                      | 216 us: 1.20x faster                                            |
| unpickle             | 9.11 us                                                     | 8.07 us: 1.13x faster                                           |
| xml_etree_process    | 43.1 ms                                                     | 39.1 ms: 1.10x faster                                           |
| unpickle_pure_python | 177 us                                                      | 164 us: 1.08x faster                                            |
| json_dumps           | 8.77 ms                                                     | 8.21 ms: 1.07x faster                                           |
| xml_etree_iterparse  | 64.5 ms                                                     | 62.0 ms: 1.04x faster                                           |
| pickle               | 6.87 us                                                     | 6.74 us: 1.02x faster                                           |
| pickle_list          | 2.69 us                                                     | 2.64 us: 1.02x faster                                           |
| json_loads           | 14.2 us                                                     | 14.1 us: 1.01x faster                                           |
| xml_etree_generate   | 54.5 ms                                                     | 54.1 ms: 1.01x faster                                           |
| pickle_dict          | 17.1 us                                                     | 17.4 us: 1.01x slower                                           |
| unpickle_list        | 2.68 us                                                     | 2.76 us: 1.03x slower                                           |
| Geometric mean       | (ref)                                                       | 1.05x faster                                                    |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 19.0 ms: 1.03x faster                                           |
| python_startup_no_site | 15.3 ms                                                     | 15.8 ms: 1.03x slower                                           |
| Geometric mean         | (ref)                                                       | 1.00x faster                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 7.62 ms: 1.18x faster                                           |
| django_template | 28.8 ms                                                     | 25.1 ms: 1.15x faster                                           |
| genshi_text     | 18.8 ms                                                     | 17.9 ms: 1.05x faster                                           |
| genshi_xml      | 39.4 ms                                                     | 40.2 ms: 1.02x slower                                           |
| Geometric mean  | (ref)                                                       | 1.09x faster                                                    |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.72 ms: 1.51x faster                                           |
| go                      | 135 ms                                                      | 100 ms: 1.35x faster                                            |
| async_tree_io           | 1.07 sec                                                    | 794 ms: 1.35x faster                                            |
| scimark_sor             | 105 ms                                                      | 80.0 ms: 1.32x faster                                           |
| scimark_lu              | 84.0 ms                                                     | 64.6 ms: 1.30x faster                                           |
| logging_silent          | 93.4 ns                                                     | 72.2 ns: 1.29x faster                                           |
| richards                | 40.6 ms                                                     | 31.6 ms: 1.28x faster                                           |
| pyflate                 | 402 ms                                                      | 314 ms: 1.28x faster                                            |
| async_tree_memoization  | 505 ms                                                      | 400 ms: 1.26x faster                                            |
| async_tree_none         | 424 ms                                                      | 336 ms: 1.26x faster                                            |
| scimark_monte_carlo     | 58.0 ms                                                     | 46.0 ms: 1.26x faster                                           |
| raytrace                | 266 ms                                                      | 213 ms: 1.25x faster                                            |
| crypto_pyaes            | 63.1 ms                                                     | 51.8 ms: 1.22x faster                                           |
| thrift                  | 623 us                                                      | 516 us: 1.21x faster                                            |
| pycparser               | 905 ms                                                      | 750 ms: 1.21x faster                                            |
| pickle_pure_python      | 259 us                                                      | 216 us: 1.20x faster                                            |
| async_tree_cpu_io_mixed | 617 ms                                                      | 520 ms: 1.19x faster                                            |
| create_gc_cycles        | 800 us                                                      | 675 us: 1.19x faster                                            |
| sqlalchemy_declarative  | 98.6 ms                                                     | 83.2 ms: 1.18x faster                                           |
| mako                    | 8.98 ms                                                     | 7.62 ms: 1.18x faster                                           |
| mypy2                   | 347 ms                                                      | 295 ms: 1.18x faster                                            |
| async_generators        | 219 ms                                                      | 187 ms: 1.17x faster                                            |
| hexiom                  | 5.59 ms                                                     | 4.84 ms: 1.16x faster                                           |
| chaos                   | 59.5 ms                                                     | 51.8 ms: 1.15x faster                                           |
| django_template         | 28.8 ms                                                     | 25.1 ms: 1.15x faster                                           |
| html5lib                | 47.5 ms                                                     | 41.4 ms: 1.15x faster                                           |
| docutils                | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                          |
| float                   | 61.7 ms                                                     | 54.5 ms: 1.13x faster                                           |
| 2to3                    | 239 ms                                                      | 211 ms: 1.13x faster                                            |
| unpickle                | 9.11 us                                                     | 8.07 us: 1.13x faster                                           |
| regex_effbot            | 1.56 ms                                                     | 1.39 ms: 1.13x faster                                           |
| spectral_norm           | 78.9 ms                                                     | 70.6 ms: 1.12x faster                                           |
| deepcopy_memo           | 29.0 us                                                     | 26.1 us: 1.11x faster                                           |
| sqlite_synth            | 1.90 us                                                     | 1.71 us: 1.11x faster                                           |
| tornado_http            | 106 ms                                                      | 95.3 ms: 1.11x faster                                           |
| xml_etree_process       | 43.1 ms                                                     | 39.1 ms: 1.10x faster                                           |
| pprint_pformat          | 1.22 sec                                                    | 1.11 sec: 1.10x faster                                          |
| dask                    | 305 ms                                                      | 280 ms: 1.09x faster                                            |
| pprint_safe_repr        | 594 ms                                                      | 548 ms: 1.09x faster                                            |
| regex_dna               | 129 ms                                                      | 120 ms: 1.08x faster                                            |
| unpickle_pure_python    | 177 us                                                      | 164 us: 1.08x faster                                            |
| chameleon               | 6.02 ms                                                     | 5.59 ms: 1.08x faster                                           |
| json_dumps              | 8.77 ms                                                     | 8.21 ms: 1.07x faster                                           |
| sqlalchemy_imperative   | 11.2 ms                                                     | 10.5 ms: 1.07x faster                                           |
| logging_simple          | 6.28 us                                                     | 5.94 us: 1.06x faster                                           |
| dulwich_log             | 48.6 ms                                                     | 46.1 ms: 1.05x faster                                           |
| regex_compile           | 102 ms                                                      | 97.0 ms: 1.05x faster                                           |
| sympy_integrate         | 15.0 ms                                                     | 14.2 ms: 1.05x faster                                           |
| genshi_text             | 18.8 ms                                                     | 17.9 ms: 1.05x faster                                           |
| logging_format          | 6.73 us                                                     | 6.39 us: 1.05x faster                                           |
| sqlglot_optimize        | 39.4 ms                                                     | 37.5 ms: 1.05x faster                                           |
| aiohttp                 | 961 us                                                      | 921 us: 1.04x faster                                            |
| regex_v8                | 15.0 ms                                                     | 14.4 ms: 1.04x faster                                           |
| xml_etree_iterparse     | 64.5 ms                                                     | 62.0 ms: 1.04x faster                                           |
| python_startup          | 19.7 ms                                                     | 19.0 ms: 1.03x faster                                           |
| pylint                  | 341 ms                                                      | 331 ms: 1.03x faster                                            |
| bench_thread_pool       | 913 us                                                      | 889 us: 1.03x faster                                            |
| sympy_expand            | 320 ms                                                      | 312 ms: 1.03x faster                                            |
| sympy_sum               | 105 ms                                                      | 103 ms: 1.02x faster                                            |
| sqlglot_normalize       | 207 ms                                                      | 203 ms: 1.02x faster                                            |
| pickle                  | 6.87 us                                                     | 6.74 us: 1.02x faster                                           |
| pickle_list             | 2.69 us                                                     | 2.64 us: 1.02x faster                                           |
| sqlglot_transpile       | 1.45 ms                                                     | 1.42 ms: 1.02x faster                                           |
| sympy_str               | 193 ms                                                      | 190 ms: 1.02x faster                                            |
| nbody                   | 71.0 ms                                                     | 70.1 ms: 1.01x faster                                           |
| deepcopy_reduce         | 2.22 us                                                     | 2.19 us: 1.01x faster                                           |
| json_loads              | 14.2 us                                                     | 14.1 us: 1.01x faster                                           |
| xml_etree_generate      | 54.5 ms                                                     | 54.1 ms: 1.01x faster                                           |
| coroutines              | 15.5 ms                                                     | 15.6 ms: 1.01x slower                                           |
| nqueens                 | 68.3 ms                                                     | 68.9 ms: 1.01x slower                                           |
| pickle_dict             | 17.1 us                                                     | 17.4 us: 1.01x slower                                           |
| scimark_fft             | 187 ms                                                      | 191 ms: 1.02x slower                                            |
| genshi_xml              | 39.4 ms                                                     | 40.2 ms: 1.02x slower                                           |
| mdp                     | 1.71 sec                                                    | 1.75 sec: 1.02x slower                                          |
| pathlib                 | 72.8 ms                                                     | 74.8 ms: 1.03x slower                                           |
| unpickle_list           | 2.68 us                                                     | 2.76 us: 1.03x slower                                           |
| fannkuch                | 258 ms                                                      | 266 ms: 1.03x slower                                            |
| python_startup_no_site  | 15.3 ms                                                     | 15.8 ms: 1.03x slower                                           |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.77 ms: 1.04x slower                                           |
| gc_traversal            | 1.40 ms                                                     | 1.46 ms: 1.04x slower                                           |
| pidigits                | 146 ms                                                      | 153 ms: 1.05x slower                                            |
| bench_mp_pool           | 59.9 ms                                                     | 63.3 ms: 1.06x slower                                           |
| telco                   | 3.82 ms                                                     | 4.05 ms: 1.06x slower                                           |
| meteor_contest          | 73.8 ms                                                     | 78.7 ms: 1.07x slower                                           |
| comprehensions          | 16.6 us                                                     | 18.2 us: 1.09x slower                                           |
| unpack_sequence         | 40.0 ns                                                     | 44.3 ns: 1.11x slower                                           |
| generators              | 31.8 ms                                                     | 35.7 ms: 1.12x slower                                           |
| coverage                | 38.4 ms                                                     | 106 ms: 2.76x slower                                            |
| Geometric mean          | (ref)                                                       | 1.07x faster                                                    |

Benchmark hidden because not significant (5): xml_etree_parse, sqlglot_parse, deepcopy, asyncio_tcp, json
Ignored benchmarks (5) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, flaskblogging, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
