
# Results vs. 3.10.4

- fork: python
- ref: f3909b8bc83675b7ab09
- machine: windows-amd64
- commit hash: f3909b8
- commit date: 2023-04-04
- overall geometric mean: 1.12x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 206 ms: 1.16x faster                                                     |
| chameleon      | 6.02 ms                                                     | 5.27 ms: 1.14x faster                                                    |
| docutils       | 1.88 sec                                                    | 1.58 sec: 1.19x faster                                                   |
| html5lib       | 47.5 ms                                                     | 39.8 ms: 1.20x faster                                                    |
| tornado_http   | 106 ms                                                      | 90.1 ms: 1.17x faster                                                    |
| Geometric mean | (ref)                                                       | 1.17x faster                                                             |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|-------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 739 ms: 1.45x faster                                                     |
| async_tree_memoization  | 505 ms                                                      | 368 ms: 1.37x faster                                                     |
| async_tree_none         | 424 ms                                                      | 314 ms: 1.35x faster                                                     |
| async_tree_cpu_io_mixed | 617 ms                                                      | 500 ms: 1.24x faster                                                     |
| Geometric mean          | (ref)                                                       | 1.35x faster                                                             |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 52.6 ms: 1.17x faster                                                    |
| nbody          | 71.0 ms                                                     | 69.8 ms: 1.02x faster                                                    |
| pidigits       | 146 ms                                                      | 147 ms: 1.00x slower                                                     |
| Geometric mean | (ref)                                                       | 1.06x faster                                                             |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 89.7 ms: 1.14x faster                                                    |
| regex_dna      | 129 ms                                                      | 120 ms: 1.08x faster                                                     |
| regex_v8       | 15.0 ms                                                     | 14.3 ms: 1.05x faster                                                    |
| regex_effbot   | 1.56 ms                                                     | 1.57 ms: 1.00x slower                                                    |
| Geometric mean | (ref)                                                       | 1.07x faster                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| pickle_pure_python   | 259 us                                                      | 198 us: 1.31x faster                                                     |
| xml_etree_process    | 43.1 ms                                                     | 36.3 ms: 1.19x faster                                                    |
| unpickle_pure_python | 177 us                                                      | 150 us: 1.18x faster                                                     |
| json_dumps           | 8.77 ms                                                     | 7.60 ms: 1.15x faster                                                    |
| unpickle             | 9.11 us                                                     | 7.97 us: 1.14x faster                                                    |
| json_loads           | 14.2 us                                                     | 13.0 us: 1.10x faster                                                    |
| xml_etree_parse      | 96.8 ms                                                     | 91.3 ms: 1.06x faster                                                    |
| xml_etree_generate   | 54.5 ms                                                     | 51.8 ms: 1.05x faster                                                    |
| xml_etree_iterparse  | 64.5 ms                                                     | 61.4 ms: 1.05x faster                                                    |
| pickle               | 6.87 us                                                     | 6.73 us: 1.02x faster                                                    |
| pickle_list          | 2.69 us                                                     | 2.78 us: 1.03x slower                                                    |
| pickle_dict          | 17.1 us                                                     | 18.6 us: 1.09x slower                                                    |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                             |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| python_startup | 19.7 ms                                                     | 18.4 ms: 1.07x faster                                                    |
| Geometric mean | (ref)                                                       | 1.03x faster                                                             |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|-----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 7.22 ms: 1.24x faster                                                    |
| django_template | 28.8 ms                                                     | 23.8 ms: 1.21x faster                                                    |
| genshi_text     | 18.8 ms                                                     | 17.3 ms: 1.09x faster                                                    |
| genshi_xml      | 39.4 ms                                                     | 37.6 ms: 1.05x faster                                                    |
| Geometric mean  | (ref)                                                       | 1.14x faster                                                             |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|-------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.65 ms: 1.55x faster                                                    |
| async_tree_io           | 1.07 sec                                                    | 739 ms: 1.45x faster                                                     |
| scimark_sor             | 105 ms                                                      | 75.2 ms: 1.40x faster                                                    |
| async_tree_memoization  | 505 ms                                                      | 368 ms: 1.37x faster                                                     |
| go                      | 135 ms                                                      | 99.2 ms: 1.36x faster                                                    |
| async_tree_none         | 424 ms                                                      | 314 ms: 1.35x faster                                                     |
| richards                | 40.6 ms                                                     | 30.4 ms: 1.34x faster                                                    |
| pyflate                 | 402 ms                                                      | 301 ms: 1.33x faster                                                     |
| logging_silent          | 93.4 ns                                                     | 70.1 ns: 1.33x faster                                                    |
| scimark_lu              | 84.0 ms                                                     | 63.3 ms: 1.33x faster                                                    |
| raytrace                | 266 ms                                                      | 203 ms: 1.31x faster                                                     |
| pickle_pure_python      | 259 us                                                      | 198 us: 1.31x faster                                                     |
| crypto_pyaes            | 63.1 ms                                                     | 48.2 ms: 1.31x faster                                                    |
| sqlglot_parse           | 1.20 ms                                                     | 931 us: 1.29x faster                                                     |
| thrift                  | 623 us                                                      | 482 us: 1.29x faster                                                     |
| pycparser               | 905 ms                                                      | 703 ms: 1.29x faster                                                     |
| scimark_monte_carlo     | 58.0 ms                                                     | 45.1 ms: 1.29x faster                                                    |
| sqlglot_transpile       | 1.45 ms                                                     | 1.13 ms: 1.28x faster                                                    |
| async_generators        | 219 ms                                                      | 176 ms: 1.25x faster                                                     |
| mako                    | 8.98 ms                                                     | 7.22 ms: 1.24x faster                                                    |
| mypy2                   | 347 ms                                                      | 280 ms: 1.24x faster                                                     |
| async_tree_cpu_io_mixed | 617 ms                                                      | 500 ms: 1.24x faster                                                     |
| hexiom                  | 5.59 ms                                                     | 4.56 ms: 1.23x faster                                                    |
| chaos                   | 59.5 ms                                                     | 48.9 ms: 1.22x faster                                                    |
| sqlalchemy_declarative  | 98.6 ms                                                     | 81.1 ms: 1.22x faster                                                    |
| django_template         | 28.8 ms                                                     | 23.8 ms: 1.21x faster                                                    |
| create_gc_cycles        | 800 us                                                      | 664 us: 1.20x faster                                                     |
| html5lib                | 47.5 ms                                                     | 39.8 ms: 1.20x faster                                                    |
| xml_etree_process       | 43.1 ms                                                     | 36.3 ms: 1.19x faster                                                    |
| docutils                | 1.88 sec                                                    | 1.58 sec: 1.19x faster                                                   |
| unpickle_pure_python    | 177 us                                                      | 150 us: 1.18x faster                                                     |
| float                   | 61.7 ms                                                     | 52.6 ms: 1.17x faster                                                    |
| tornado_http            | 106 ms                                                      | 90.1 ms: 1.17x faster                                                    |
| spectral_norm           | 78.9 ms                                                     | 67.6 ms: 1.17x faster                                                    |
| dask                    | 305 ms                                                      | 261 ms: 1.17x faster                                                     |
| deepcopy_memo           | 29.0 us                                                     | 24.8 us: 1.17x faster                                                    |
| 2to3                    | 239 ms                                                      | 206 ms: 1.16x faster                                                     |
| json_dumps              | 8.77 ms                                                     | 7.60 ms: 1.15x faster                                                    |
| pprint_pformat          | 1.22 sec                                                    | 1.06 sec: 1.15x faster                                                   |
| chameleon               | 6.02 ms                                                     | 5.27 ms: 1.14x faster                                                    |
| unpickle                | 9.11 us                                                     | 7.97 us: 1.14x faster                                                    |
| dulwich_log             | 48.6 ms                                                     | 42.5 ms: 1.14x faster                                                    |
| regex_compile           | 102 ms                                                      | 89.7 ms: 1.14x faster                                                    |
| sqlglot_optimize        | 39.4 ms                                                     | 34.7 ms: 1.14x faster                                                    |
| pprint_safe_repr        | 594 ms                                                      | 526 ms: 1.13x faster                                                     |
| aiohttp                 | 961 us                                                      | 857 us: 1.12x faster                                                     |
| sqlite_synth            | 1.90 us                                                     | 1.69 us: 1.12x faster                                                    |
| sqlalchemy_imperative   | 11.2 ms                                                     | 10.0 ms: 1.12x faster                                                    |
| sympy_expand            | 320 ms                                                      | 290 ms: 1.11x faster                                                     |
| sympy_integrate         | 15.0 ms                                                     | 13.6 ms: 1.10x faster                                                    |
| json_loads              | 14.2 us                                                     | 13.0 us: 1.10x faster                                                    |
| deepcopy_reduce         | 2.22 us                                                     | 2.04 us: 1.09x faster                                                    |
| genshi_text             | 18.8 ms                                                     | 17.3 ms: 1.09x faster                                                    |
| sqlglot_normalize       | 207 ms                                                      | 191 ms: 1.08x faster                                                     |
| comprehensions          | 16.6 us                                                     | 15.4 us: 1.08x faster                                                    |
| bench_thread_pool       | 913 us                                                      | 848 us: 1.08x faster                                                     |
| regex_dna               | 129 ms                                                      | 120 ms: 1.08x faster                                                     |
| sympy_sum               | 105 ms                                                      | 98.4 ms: 1.07x faster                                                    |
| python_startup          | 19.7 ms                                                     | 18.4 ms: 1.07x faster                                                    |
| deepcopy                | 259 us                                                      | 243 us: 1.07x faster                                                     |
| sympy_str               | 193 ms                                                      | 182 ms: 1.06x faster                                                     |
| xml_etree_parse         | 96.8 ms                                                     | 91.3 ms: 1.06x faster                                                    |
| pylint                  | 341 ms                                                      | 321 ms: 1.06x faster                                                     |
| regex_v8                | 15.0 ms                                                     | 14.3 ms: 1.05x faster                                                    |
| xml_etree_generate      | 54.5 ms                                                     | 51.8 ms: 1.05x faster                                                    |
| xml_etree_iterparse     | 64.5 ms                                                     | 61.4 ms: 1.05x faster                                                    |
| genshi_xml              | 39.4 ms                                                     | 37.6 ms: 1.05x faster                                                    |
| nqueens                 | 68.3 ms                                                     | 65.6 ms: 1.04x faster                                                    |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.58 ms: 1.03x faster                                                    |
| coroutines              | 15.5 ms                                                     | 15.1 ms: 1.02x faster                                                    |
| pickle                  | 6.87 us                                                     | 6.73 us: 1.02x faster                                                    |
| nbody                   | 71.0 ms                                                     | 69.8 ms: 1.02x faster                                                    |
| scimark_fft             | 187 ms                                                      | 185 ms: 1.02x faster                                                     |
| fannkuch                | 258 ms                                                      | 256 ms: 1.01x faster                                                     |
| regex_effbot            | 1.56 ms                                                     | 1.57 ms: 1.00x slower                                                    |
| pidigits                | 146 ms                                                      | 147 ms: 1.00x slower                                                     |
| flaskblogging           | 2.04 sec                                                    | 2.05 sec: 1.01x slower                                                   |
| meteor_contest          | 73.8 ms                                                     | 74.7 ms: 1.01x slower                                                    |
| mdp                     | 1.71 sec                                                    | 1.74 sec: 1.02x slower                                                   |
| gc_traversal            | 1.40 ms                                                     | 1.43 ms: 1.02x slower                                                    |
| pickle_list             | 2.69 us                                                     | 2.78 us: 1.03x slower                                                    |
| bench_mp_pool           | 59.9 ms                                                     | 62.0 ms: 1.04x slower                                                    |
| logging_format          | 6.73 us                                                     | 6.99 us: 1.04x slower                                                    |
| telco                   | 3.82 ms                                                     | 4.02 ms: 1.05x slower                                                    |
| logging_simple          | 6.28 us                                                     | 6.67 us: 1.06x slower                                                    |
| generators              | 31.8 ms                                                     | 34.0 ms: 1.07x slower                                                    |
| pickle_dict             | 17.1 us                                                     | 18.6 us: 1.09x slower                                                    |
| unpack_sequence         | 40.0 ns                                                     | 46.0 ns: 1.15x slower                                                    |
| coverage                | 38.4 ms                                                     | 53.2 ms: 1.39x slower                                                    |
| Geometric mean          | (ref)                                                       | 1.12x faster                                                             |

Benchmark hidden because not significant (5): unpickle_list, python_startup_no_site, asyncio_tcp, pathlib, json
Ignored benchmarks (4) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
