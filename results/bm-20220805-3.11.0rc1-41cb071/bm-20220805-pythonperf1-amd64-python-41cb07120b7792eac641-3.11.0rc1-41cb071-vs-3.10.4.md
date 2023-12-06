
# Results vs. 3.10.4

- fork: python
- ref: 41cb07120b7792eac641
- machine: windows-amd64
- commit hash: 41cb071
- commit date: 2022-08-05
- overall geometric mean: 1.13x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 202 ms: 1.18x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.05 ms: 1.19x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                                      |
| html5lib       | 47.5 ms                                                     | 38.4 ms: 1.24x faster                                                       |
| tornado_http   | 106 ms                                                      | 90.9 ms: 1.16x faster                                                       |
| Geometric mean | (ref)                                                       | 1.19x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 739 ms: 1.45x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 368 ms: 1.37x faster                                                        |
| async_tree_none         | 424 ms                                                      | 310 ms: 1.37x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 491 ms: 1.26x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.36x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 52.9 ms: 1.17x faster                                                       |
| nbody          | 71.0 ms                                                     | 68.3 ms: 1.04x faster                                                       |
| pidigits       | 146 ms                                                      | 146 ms: 1.00x faster                                                        |
| Geometric mean | (ref)                                                       | 1.07x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 89.4 ms: 1.14x faster                                                       |
| regex_v8       | 15.0 ms                                                     | 14.1 ms: 1.07x faster                                                       |
| regex_dna      | 129 ms                                                      | 123 ms: 1.05x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.66 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 259 us                                                      | 202 us: 1.28x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 150 us: 1.18x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 36.7 ms: 1.17x faster                                                       |
| json_dumps           | 8.77 ms                                                     | 7.73 ms: 1.13x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.11 us: 1.12x faster                                                       |
| pickle               | 6.87 us                                                     | 6.44 us: 1.07x faster                                                       |
| pickle_list          | 2.69 us                                                     | 2.57 us: 1.05x faster                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 52.6 ms: 1.04x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 62.9 ms: 1.03x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 94.8 ms: 1.02x faster                                                       |
| json_loads           | 14.2 us                                                     | 14.0 us: 1.02x faster                                                       |
| pickle_dict          | 17.1 us                                                     | 18.4 us: 1.07x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup | 19.7 ms                                                     | 18.4 ms: 1.07x faster                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 7.26 ms: 1.24x faster                                                       |
| django_template | 28.8 ms                                                     | 23.7 ms: 1.21x faster                                                       |
| genshi_text     | 18.8 ms                                                     | 16.7 ms: 1.13x faster                                                       |
| genshi_xml      | 39.4 ms                                                     | 37.7 ms: 1.05x faster                                                       |
| Geometric mean  | (ref)                                                       | 1.15x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.63 ms: 1.57x faster                                                       |
| async_tree_io           | 1.07 sec                                                    | 739 ms: 1.45x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 368 ms: 1.37x faster                                                        |
| async_tree_none         | 424 ms                                                      | 310 ms: 1.37x faster                                                        |
| scimark_sor             | 105 ms                                                      | 77.3 ms: 1.36x faster                                                       |
| go                      | 135 ms                                                      | 101 ms: 1.34x faster                                                        |
| pyflate                 | 402 ms                                                      | 303 ms: 1.33x faster                                                        |
| scimark_lu              | 84.0 ms                                                     | 63.7 ms: 1.32x faster                                                       |
| pycparser               | 905 ms                                                      | 689 ms: 1.31x faster                                                        |
| raytrace                | 266 ms                                                      | 204 ms: 1.31x faster                                                        |
| scimark_monte_carlo     | 58.0 ms                                                     | 44.4 ms: 1.31x faster                                                       |
| sqlglot_parse           | 1.20 ms                                                     | 925 us: 1.30x faster                                                        |
| logging_silent          | 93.4 ns                                                     | 71.9 ns: 1.30x faster                                                       |
| richards                | 40.6 ms                                                     | 31.3 ms: 1.30x faster                                                       |
| crypto_pyaes            | 63.1 ms                                                     | 48.7 ms: 1.29x faster                                                       |
| thrift                  | 623 us                                                      | 482 us: 1.29x faster                                                        |
| pickle_pure_python      | 259 us                                                      | 202 us: 1.28x faster                                                        |
| sqlglot_transpile       | 1.45 ms                                                     | 1.13 ms: 1.28x faster                                                       |
| mypy2                   | 347 ms                                                      | 275 ms: 1.26x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 491 ms: 1.26x faster                                                        |
| hexiom                  | 5.59 ms                                                     | 4.46 ms: 1.25x faster                                                       |
| async_generators        | 219 ms                                                      | 176 ms: 1.24x faster                                                        |
| mako                    | 8.98 ms                                                     | 7.26 ms: 1.24x faster                                                       |
| html5lib                | 47.5 ms                                                     | 38.4 ms: 1.24x faster                                                       |
| django_template         | 28.8 ms                                                     | 23.7 ms: 1.21x faster                                                       |
| create_gc_cycles        | 800 us                                                      | 665 us: 1.20x faster                                                        |
| chaos                   | 59.5 ms                                                     | 49.6 ms: 1.20x faster                                                       |
| chameleon               | 6.02 ms                                                     | 5.05 ms: 1.19x faster                                                       |
| sqlalchemy_declarative  | 98.6 ms                                                     | 83.4 ms: 1.18x faster                                                       |
| unpickle_pure_python    | 177 us                                                      | 150 us: 1.18x faster                                                        |
| 2to3                    | 239 ms                                                      | 202 ms: 1.18x faster                                                        |
| docutils                | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                                      |
| xml_etree_process       | 43.1 ms                                                     | 36.7 ms: 1.17x faster                                                       |
| pprint_pformat          | 1.22 sec                                                    | 1.04 sec: 1.17x faster                                                      |
| float                   | 61.7 ms                                                     | 52.9 ms: 1.17x faster                                                       |
| tornado_http            | 106 ms                                                      | 90.9 ms: 1.16x faster                                                       |
| pprint_safe_repr        | 594 ms                                                      | 513 ms: 1.16x faster                                                        |
| regex_compile           | 102 ms                                                      | 89.4 ms: 1.14x faster                                                       |
| deepcopy_memo           | 29.0 us                                                     | 25.3 us: 1.14x faster                                                       |
| sqlglot_optimize        | 39.4 ms                                                     | 34.5 ms: 1.14x faster                                                       |
| dask                    | 305 ms                                                      | 267 ms: 1.14x faster                                                        |
| json_dumps              | 8.77 ms                                                     | 7.73 ms: 1.13x faster                                                       |
| sqlite_synth            | 1.90 us                                                     | 1.68 us: 1.13x faster                                                       |
| genshi_text             | 18.8 ms                                                     | 16.7 ms: 1.13x faster                                                       |
| dulwich_log             | 48.6 ms                                                     | 43.3 ms: 1.12x faster                                                       |
| unpickle                | 9.11 us                                                     | 8.11 us: 1.12x faster                                                       |
| aiohttp                 | 961 us                                                      | 861 us: 1.12x faster                                                        |
| sympy_integrate         | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                                       |
| sympy_expand            | 320 ms                                                      | 290 ms: 1.10x faster                                                        |
| spectral_norm           | 78.9 ms                                                     | 71.8 ms: 1.10x faster                                                       |
| sqlglot_normalize       | 207 ms                                                      | 189 ms: 1.09x faster                                                        |
| comprehensions          | 16.6 us                                                     | 15.2 us: 1.09x faster                                                       |
| asyncio_tcp             | 717 ms                                                      | 659 ms: 1.09x faster                                                        |
| deepcopy                | 259 us                                                      | 238 us: 1.09x faster                                                        |
| deepcopy_reduce         | 2.22 us                                                     | 2.05 us: 1.09x faster                                                       |
| sympy_sum               | 105 ms                                                      | 97.0 ms: 1.09x faster                                                       |
| sqlalchemy_imperative   | 11.2 ms                                                     | 10.4 ms: 1.07x faster                                                       |
| pylint                  | 341 ms                                                      | 318 ms: 1.07x faster                                                        |
| sympy_str               | 193 ms                                                      | 180 ms: 1.07x faster                                                        |
| mdp                     | 1.71 sec                                                    | 1.60 sec: 1.07x faster                                                      |
| python_startup          | 19.7 ms                                                     | 18.4 ms: 1.07x faster                                                       |
| pickle                  | 6.87 us                                                     | 6.44 us: 1.07x faster                                                       |
| regex_v8                | 15.0 ms                                                     | 14.1 ms: 1.07x faster                                                       |
| bench_thread_pool       | 913 us                                                      | 856 us: 1.07x faster                                                        |
| nqueens                 | 68.3 ms                                                     | 64.2 ms: 1.06x faster                                                       |
| json                    | 3.10 ms                                                     | 2.94 ms: 1.06x faster                                                       |
| regex_dna               | 129 ms                                                      | 123 ms: 1.05x faster                                                        |
| coroutines              | 15.5 ms                                                     | 14.8 ms: 1.05x faster                                                       |
| pickle_list             | 2.69 us                                                     | 2.57 us: 1.05x faster                                                       |
| genshi_xml              | 39.4 ms                                                     | 37.7 ms: 1.05x faster                                                       |
| fannkuch                | 258 ms                                                      | 247 ms: 1.04x faster                                                        |
| nbody                   | 71.0 ms                                                     | 68.3 ms: 1.04x faster                                                       |
| xml_etree_generate      | 54.5 ms                                                     | 52.6 ms: 1.04x faster                                                       |
| scimark_fft             | 187 ms                                                      | 182 ms: 1.03x faster                                                        |
| xml_etree_iterparse     | 64.5 ms                                                     | 62.9 ms: 1.03x faster                                                       |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.61 ms: 1.02x faster                                                       |
| xml_etree_parse         | 96.8 ms                                                     | 94.8 ms: 1.02x faster                                                       |
| json_loads              | 14.2 us                                                     | 14.0 us: 1.02x faster                                                       |
| meteor_contest          | 73.8 ms                                                     | 73.3 ms: 1.01x faster                                                       |
| pidigits                | 146 ms                                                      | 146 ms: 1.00x faster                                                        |
| gc_traversal            | 1.40 ms                                                     | 1.40 ms: 1.01x slower                                                       |
| flaskblogging           | 2.04 sec                                                    | 2.05 sec: 1.01x slower                                                      |
| telco                   | 3.82 ms                                                     | 3.87 ms: 1.01x slower                                                       |
| logging_simple          | 6.28 us                                                     | 6.37 us: 1.02x slower                                                       |
| bench_mp_pool           | 59.9 ms                                                     | 61.4 ms: 1.02x slower                                                       |
| logging_format          | 6.73 us                                                     | 6.90 us: 1.03x slower                                                       |
| unpack_sequence         | 40.0 ns                                                     | 41.9 ns: 1.05x slower                                                       |
| regex_effbot            | 1.56 ms                                                     | 1.66 ms: 1.06x slower                                                       |
| generators              | 31.8 ms                                                     | 33.8 ms: 1.06x slower                                                       |
| pickle_dict             | 17.1 us                                                     | 18.4 us: 1.07x slower                                                       |
| coverage                | 38.4 ms                                                     | 53.6 ms: 1.40x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.13x faster                                                                |

Benchmark hidden because not significant (3): unpickle_list, python_startup_no_site, pathlib
Ignored benchmarks (4) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
