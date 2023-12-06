
# Results vs. 3.10.4

- fork: python
- ref: ed7c3ff15680c1939fad
- machine: windows-amd64
- commit hash: ed7c3ff
- commit date: 2022-09-11
- overall geometric mean: 1.13x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 202 ms: 1.18x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.09 ms: 1.18x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.57 sec: 1.19x faster                                                      |
| html5lib       | 47.5 ms                                                     | 37.2 ms: 1.28x faster                                                       |
| tornado_http   | 106 ms                                                      | 92.1 ms: 1.15x faster                                                       |
| Geometric mean | (ref)                                                       | 1.20x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 740 ms: 1.45x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 368 ms: 1.37x faster                                                        |
| async_tree_none         | 424 ms                                                      | 310 ms: 1.37x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 488 ms: 1.26x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.36x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 53.9 ms: 1.15x faster                                                       |
| nbody          | 71.0 ms                                                     | 68.6 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 89.5 ms: 1.14x faster                                                       |
| regex_dna      | 129 ms                                                      | 115 ms: 1.13x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 13.4 ms: 1.13x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.09x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 259 us                                                      | 197 us: 1.32x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 35.9 ms: 1.20x faster                                                       |
| unpickle_pure_python | 177 us                                                      | 149 us: 1.19x faster                                                        |
| unpickle             | 9.11 us                                                     | 7.70 us: 1.18x faster                                                       |
| json_dumps           | 8.77 ms                                                     | 7.66 ms: 1.14x faster                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 51.2 ms: 1.07x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 91.6 ms: 1.06x faster                                                       |
| unpickle_list        | 2.68 us                                                     | 2.55 us: 1.05x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 61.9 ms: 1.04x faster                                                       |
| pickle               | 6.87 us                                                     | 6.60 us: 1.04x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.7 us: 1.04x faster                                                       |
| pickle_list          | 2.69 us                                                     | 2.65 us: 1.01x faster                                                       |
| pickle_dict          | 17.1 us                                                     | 18.2 us: 1.06x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup | 19.7 ms                                                     | 18.5 ms: 1.06x faster                                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                                |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 7.22 ms: 1.24x faster                                                       |
| django_template | 28.8 ms                                                     | 23.8 ms: 1.21x faster                                                       |
| genshi_text     | 18.8 ms                                                     | 16.7 ms: 1.13x faster                                                       |
| genshi_xml      | 39.4 ms                                                     | 38.3 ms: 1.03x faster                                                       |
| Geometric mean  | (ref)                                                       | 1.15x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.61 ms: 1.58x faster                                                       |
| async_tree_io           | 1.07 sec                                                    | 740 ms: 1.45x faster                                                        |
| go                      | 135 ms                                                      | 97.5 ms: 1.39x faster                                                       |
| async_tree_memoization  | 505 ms                                                      | 368 ms: 1.37x faster                                                        |
| async_tree_none         | 424 ms                                                      | 310 ms: 1.37x faster                                                        |
| scimark_sor             | 105 ms                                                      | 77.3 ms: 1.36x faster                                                       |
| pyflate                 | 402 ms                                                      | 303 ms: 1.33x faster                                                        |
| richards                | 40.6 ms                                                     | 30.6 ms: 1.33x faster                                                       |
| scimark_lu              | 84.0 ms                                                     | 63.4 ms: 1.33x faster                                                       |
| pycparser               | 905 ms                                                      | 683 ms: 1.32x faster                                                        |
| logging_silent          | 93.4 ns                                                     | 70.9 ns: 1.32x faster                                                       |
| pickle_pure_python      | 259 us                                                      | 197 us: 1.32x faster                                                        |
| sqlglot_parse           | 1.20 ms                                                     | 920 us: 1.31x faster                                                        |
| scimark_monte_carlo     | 58.0 ms                                                     | 44.6 ms: 1.30x faster                                                       |
| crypto_pyaes            | 63.1 ms                                                     | 48.5 ms: 1.30x faster                                                       |
| sqlglot_transpile       | 1.45 ms                                                     | 1.12 ms: 1.29x faster                                                       |
| html5lib                | 47.5 ms                                                     | 37.2 ms: 1.28x faster                                                       |
| thrift                  | 623 us                                                      | 491 us: 1.27x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 488 ms: 1.26x faster                                                        |
| raytrace                | 266 ms                                                      | 211 ms: 1.26x faster                                                        |
| mypy2                   | 347 ms                                                      | 276 ms: 1.25x faster                                                        |
| hexiom                  | 5.59 ms                                                     | 4.48 ms: 1.25x faster                                                       |
| async_generators        | 219 ms                                                      | 176 ms: 1.25x faster                                                        |
| mako                    | 8.98 ms                                                     | 7.22 ms: 1.24x faster                                                       |
| chaos                   | 59.5 ms                                                     | 48.0 ms: 1.24x faster                                                       |
| django_template         | 28.8 ms                                                     | 23.8 ms: 1.21x faster                                                       |
| sqlalchemy_declarative  | 98.6 ms                                                     | 81.7 ms: 1.21x faster                                                       |
| xml_etree_process       | 43.1 ms                                                     | 35.9 ms: 1.20x faster                                                       |
| create_gc_cycles        | 800 us                                                      | 667 us: 1.20x faster                                                        |
| docutils                | 1.88 sec                                                    | 1.57 sec: 1.19x faster                                                      |
| unpickle_pure_python    | 177 us                                                      | 149 us: 1.19x faster                                                        |
| chameleon               | 6.02 ms                                                     | 5.09 ms: 1.18x faster                                                       |
| unpickle                | 9.11 us                                                     | 7.70 us: 1.18x faster                                                       |
| 2to3                    | 239 ms                                                      | 202 ms: 1.18x faster                                                        |
| pprint_pformat          | 1.22 sec                                                    | 1.05 sec: 1.16x faster                                                      |
| pprint_safe_repr        | 594 ms                                                      | 512 ms: 1.16x faster                                                        |
| sqlglot_optimize        | 39.4 ms                                                     | 34.0 ms: 1.16x faster                                                       |
| tornado_http            | 106 ms                                                      | 92.1 ms: 1.15x faster                                                       |
| float                   | 61.7 ms                                                     | 53.9 ms: 1.15x faster                                                       |
| json_dumps              | 8.77 ms                                                     | 7.66 ms: 1.14x faster                                                       |
| regex_compile           | 102 ms                                                      | 89.5 ms: 1.14x faster                                                       |
| dask                    | 305 ms                                                      | 267 ms: 1.14x faster                                                        |
| deepcopy_memo           | 29.0 us                                                     | 25.4 us: 1.14x faster                                                       |
| sqlite_synth            | 1.90 us                                                     | 1.67 us: 1.13x faster                                                       |
| genshi_text             | 18.8 ms                                                     | 16.7 ms: 1.13x faster                                                       |
| regex_dna               | 129 ms                                                      | 115 ms: 1.13x faster                                                        |
| regex_v8                | 15.0 ms                                                     | 13.4 ms: 1.13x faster                                                       |
| aiohttp                 | 961 us                                                      | 857 us: 1.12x faster                                                        |
| dulwich_log             | 48.6 ms                                                     | 43.6 ms: 1.11x faster                                                       |
| sqlglot_normalize       | 207 ms                                                      | 186 ms: 1.11x faster                                                        |
| deepcopy_reduce         | 2.22 us                                                     | 2.00 us: 1.11x faster                                                       |
| sympy_integrate         | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                                       |
| comprehensions          | 16.6 us                                                     | 15.2 us: 1.09x faster                                                       |
| sympy_expand            | 320 ms                                                      | 294 ms: 1.09x faster                                                        |
| sqlalchemy_imperative   | 11.2 ms                                                     | 10.3 ms: 1.09x faster                                                       |
| deepcopy                | 259 us                                                      | 239 us: 1.09x faster                                                        |
| pylint                  | 341 ms                                                      | 316 ms: 1.08x faster                                                        |
| spectral_norm           | 78.9 ms                                                     | 73.2 ms: 1.08x faster                                                       |
| mdp                     | 1.71 sec                                                    | 1.59 sec: 1.08x faster                                                      |
| bench_thread_pool       | 913 us                                                      | 849 us: 1.07x faster                                                        |
| sympy_sum               | 105 ms                                                      | 98.2 ms: 1.07x faster                                                       |
| xml_etree_generate      | 54.5 ms                                                     | 51.2 ms: 1.07x faster                                                       |
| python_startup          | 19.7 ms                                                     | 18.5 ms: 1.06x faster                                                       |
| sympy_str               | 193 ms                                                      | 182 ms: 1.06x faster                                                        |
| xml_etree_parse         | 96.8 ms                                                     | 91.6 ms: 1.06x faster                                                       |
| nqueens                 | 68.3 ms                                                     | 64.6 ms: 1.06x faster                                                       |
| unpickle_list           | 2.68 us                                                     | 2.55 us: 1.05x faster                                                       |
| xml_etree_iterparse     | 64.5 ms                                                     | 61.9 ms: 1.04x faster                                                       |
| pickle                  | 6.87 us                                                     | 6.60 us: 1.04x faster                                                       |
| json_loads              | 14.2 us                                                     | 13.7 us: 1.04x faster                                                       |
| coroutines              | 15.5 ms                                                     | 14.9 ms: 1.04x faster                                                       |
| nbody                   | 71.0 ms                                                     | 68.6 ms: 1.03x faster                                                       |
| genshi_xml              | 39.4 ms                                                     | 38.3 ms: 1.03x faster                                                       |
| pickle_list             | 2.69 us                                                     | 2.65 us: 1.01x faster                                                       |
| pathlib                 | 72.8 ms                                                     | 72.1 ms: 1.01x faster                                                       |
| flaskblogging           | 2.04 sec                                                    | 2.04 sec: 1.00x slower                                                      |
| meteor_contest          | 73.8 ms                                                     | 74.3 ms: 1.01x slower                                                       |
| gc_traversal            | 1.40 ms                                                     | 1.41 ms: 1.01x slower                                                       |
| scimark_fft             | 187 ms                                                      | 189 ms: 1.01x slower                                                        |
| regex_effbot            | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                                       |
| bench_mp_pool           | 59.9 ms                                                     | 61.2 ms: 1.02x slower                                                       |
| telco                   | 3.82 ms                                                     | 3.91 ms: 1.02x slower                                                       |
| logging_format          | 6.73 us                                                     | 6.97 us: 1.04x slower                                                       |
| logging_simple          | 6.28 us                                                     | 6.57 us: 1.05x slower                                                       |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.81 ms: 1.05x slower                                                       |
| generators              | 31.8 ms                                                     | 33.5 ms: 1.06x slower                                                       |
| pickle_dict             | 17.1 us                                                     | 18.2 us: 1.06x slower                                                       |
| unpack_sequence         | 40.0 ns                                                     | 42.7 ns: 1.07x slower                                                       |
| coverage                | 38.4 ms                                                     | 53.2 ms: 1.39x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.13x faster                                                                |

Benchmark hidden because not significant (5): asyncio_tcp, json, fannkuch, python_startup_no_site, pidigits
Ignored benchmarks (4) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
