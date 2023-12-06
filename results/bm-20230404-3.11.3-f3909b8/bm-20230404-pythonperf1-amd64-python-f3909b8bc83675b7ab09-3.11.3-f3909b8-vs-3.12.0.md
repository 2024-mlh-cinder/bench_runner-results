
# Results vs. 3.12.0

- fork: python
- ref: f3909b8bc83675b7ab09
- machine: windows-amd64
- commit hash: f3909b8
- commit date: 2023-04-04
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 206 ms: 1.03x faster                                                     |
| chameleon      | 4.95 ms                                                     | 5.27 ms: 1.06x slower                                                    |
| docutils       | 1.61 sec                                                    | 1.58 sec: 1.02x faster                                                   |
| tornado_http   | 87.2 ms                                                     | 90.1 ms: 1.03x slower                                                    |
| Geometric mean | (ref)                                                       | 1.01x slower                                                             |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|-------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| async_tree_io           | 712 ms                                                      | 739 ms: 1.04x slower                                                     |
| async_tree_cpu_io_mixed | 477 ms                                                      | 500 ms: 1.05x slower                                                     |
| async_tree_none         | 286 ms                                                      | 314 ms: 1.10x slower                                                     |
| async_tree_memoization  | 333 ms                                                      | 368 ms: 1.11x slower                                                     |
| Geometric mean          | (ref)                                                       | 1.07x slower                                                             |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 52.6 ms: 1.04x faster                                                    |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                     |
| nbody          | 68.8 ms                                                     | 69.8 ms: 1.01x slower                                                    |
| Geometric mean | (ref)                                                       | 1.02x faster                                                             |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.57 ms: 1.01x faster                                                    |
| regex_dna      | 119 ms                                                      | 120 ms: 1.01x slower                                                     |
| regex_compile  | 87.2 ms                                                     | 89.7 ms: 1.03x slower                                                    |
| regex_v8       | 13.5 ms                                                     | 14.3 ms: 1.06x slower                                                    |
| Geometric mean | (ref)                                                       | 1.02x slower                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.73 us: 1.10x faster                                                    |
| xml_etree_generate   | 55.8 ms                                                     | 51.8 ms: 1.08x faster                                                    |
| unpickle             | 8.44 us                                                     | 7.97 us: 1.06x faster                                                    |
| json_loads           | 13.6 us                                                     | 13.0 us: 1.05x faster                                                    |
| pickle_list          | 2.88 us                                                     | 2.78 us: 1.04x faster                                                    |
| xml_etree_process    | 37.6 ms                                                     | 36.3 ms: 1.04x faster                                                    |
| xml_etree_iterparse  | 63.1 ms                                                     | 61.4 ms: 1.03x faster                                                    |
| pickle_dict          | 18.9 us                                                     | 18.6 us: 1.02x faster                                                    |
| xml_etree_parse      | 90.5 ms                                                     | 91.3 ms: 1.01x slower                                                    |
| pickle_pure_python   | 195 us                                                      | 198 us: 1.02x slower                                                     |
| unpickle_pure_python | 134 us                                                      | 150 us: 1.12x slower                                                     |
| json_dumps           | 5.83 ms                                                     | 7.60 ms: 1.30x slower                                                    |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                             |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.3 ms: 1.04x faster                                                    |
| python_startup         | 18.8 ms                                                     | 18.4 ms: 1.02x faster                                                    |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                             |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|-----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 7.22 ms: 1.02x slower                                                    |
| django_template | 22.8 ms                                                     | 23.8 ms: 1.05x slower                                                    |
| Geometric mean  | (ref)                                                       | 1.03x slower                                                             |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|-------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| async_generators        | 230 ms                                                      | 176 ms: 1.31x faster                                                     |
| pickle                  | 7.38 us                                                     | 6.73 us: 1.10x faster                                                    |
| create_gc_cycles        | 726 us                                                      | 664 us: 1.09x faster                                                     |
| pathlib                 | 79.6 ms                                                     | 73.2 ms: 1.09x faster                                                    |
| bench_mp_pool           | 67.2 ms                                                     | 62.0 ms: 1.08x faster                                                    |
| xml_etree_generate      | 55.8 ms                                                     | 51.8 ms: 1.08x faster                                                    |
| scimark_sor             | 79.8 ms                                                     | 75.2 ms: 1.06x faster                                                    |
| unpickle                | 8.44 us                                                     | 7.97 us: 1.06x faster                                                    |
| json_loads              | 13.6 us                                                     | 13.0 us: 1.05x faster                                                    |
| gc_traversal            | 1.49 ms                                                     | 1.43 ms: 1.04x faster                                                    |
| sqlalchemy_declarative  | 84.5 ms                                                     | 81.1 ms: 1.04x faster                                                    |
| float                   | 54.7 ms                                                     | 52.6 ms: 1.04x faster                                                    |
| python_startup_no_site  | 15.9 ms                                                     | 15.3 ms: 1.04x faster                                                    |
| pickle_list             | 2.88 us                                                     | 2.78 us: 1.04x faster                                                    |
| xml_etree_process       | 37.6 ms                                                     | 36.3 ms: 1.04x faster                                                    |
| sqlite_synth            | 1.75 us                                                     | 1.69 us: 1.03x faster                                                    |
| 2to3                    | 213 ms                                                      | 206 ms: 1.03x faster                                                     |
| xml_etree_iterparse     | 63.1 ms                                                     | 61.4 ms: 1.03x faster                                                    |
| python_startup          | 18.8 ms                                                     | 18.4 ms: 1.02x faster                                                    |
| deepcopy_reduce         | 2.08 us                                                     | 2.04 us: 1.02x faster                                                    |
| pidigits                | 150 ms                                                      | 147 ms: 1.02x faster                                                     |
| pickle_dict             | 18.9 us                                                     | 18.6 us: 1.02x faster                                                    |
| docutils                | 1.61 sec                                                    | 1.58 sec: 1.02x faster                                                   |
| telco                   | 4.08 ms                                                     | 4.02 ms: 1.02x faster                                                    |
| regex_effbot            | 1.58 ms                                                     | 1.57 ms: 1.01x faster                                                    |
| regex_dna               | 119 ms                                                      | 120 ms: 1.01x slower                                                     |
| xml_etree_parse         | 90.5 ms                                                     | 91.3 ms: 1.01x slower                                                    |
| aiohttp                 | 848 us                                                      | 857 us: 1.01x slower                                                     |
| nbody                   | 68.8 ms                                                     | 69.8 ms: 1.01x slower                                                    |
| pickle_pure_python      | 195 us                                                      | 198 us: 1.02x slower                                                     |
| sqlglot_optimize        | 34.0 ms                                                     | 34.7 ms: 1.02x slower                                                    |
| scimark_fft             | 181 ms                                                      | 185 ms: 1.02x slower                                                     |
| bench_thread_pool       | 830 us                                                      | 848 us: 1.02x slower                                                     |
| mako                    | 7.05 ms                                                     | 7.22 ms: 1.02x slower                                                    |
| pprint_pformat          | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                                   |
| dask                    | 255 ms                                                      | 261 ms: 1.03x slower                                                     |
| pyflate                 | 294 ms                                                      | 301 ms: 1.03x slower                                                     |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.58 ms: 1.03x slower                                                    |
| regex_compile           | 87.2 ms                                                     | 89.7 ms: 1.03x slower                                                    |
| tornado_http            | 87.2 ms                                                     | 90.1 ms: 1.03x slower                                                    |
| pprint_safe_repr        | 508 ms                                                      | 526 ms: 1.04x slower                                                     |
| meteor_contest          | 72.1 ms                                                     | 74.7 ms: 1.04x slower                                                    |
| crypto_pyaes            | 46.4 ms                                                     | 48.2 ms: 1.04x slower                                                    |
| async_tree_io           | 712 ms                                                      | 739 ms: 1.04x slower                                                     |
| logging_format          | 6.72 us                                                     | 6.99 us: 1.04x slower                                                    |
| sqlglot_normalize       | 183 ms                                                      | 191 ms: 1.04x slower                                                     |
| sympy_expand            | 278 ms                                                      | 290 ms: 1.04x slower                                                     |
| pycparser               | 673 ms                                                      | 703 ms: 1.04x slower                                                     |
| deepcopy                | 233 us                                                      | 243 us: 1.04x slower                                                     |
| django_template         | 22.8 ms                                                     | 23.8 ms: 1.05x slower                                                    |
| fannkuch                | 244 ms                                                      | 256 ms: 1.05x slower                                                     |
| async_tree_cpu_io_mixed | 477 ms                                                      | 500 ms: 1.05x slower                                                     |
| scimark_monte_carlo     | 43.0 ms                                                     | 45.1 ms: 1.05x slower                                                    |
| sympy_integrate         | 13.0 ms                                                     | 13.6 ms: 1.05x slower                                                    |
| raytrace                | 192 ms                                                      | 203 ms: 1.05x slower                                                     |
| regex_v8                | 13.5 ms                                                     | 14.3 ms: 1.06x slower                                                    |
| spectral_norm           | 63.9 ms                                                     | 67.6 ms: 1.06x slower                                                    |
| sympy_str               | 171 ms                                                      | 182 ms: 1.06x slower                                                     |
| deepcopy_memo           | 23.4 us                                                     | 24.8 us: 1.06x slower                                                    |
| nqueens                 | 61.7 ms                                                     | 65.6 ms: 1.06x slower                                                    |
| chameleon               | 4.95 ms                                                     | 5.27 ms: 1.06x slower                                                    |
| coroutines              | 14.1 ms                                                     | 15.1 ms: 1.07x slower                                                    |
| logging_simple          | 6.21 us                                                     | 6.67 us: 1.07x slower                                                    |
| sqlalchemy_imperative   | 9.20 ms                                                     | 10.0 ms: 1.09x slower                                                    |
| sympy_sum               | 90.1 ms                                                     | 98.4 ms: 1.09x slower                                                    |
| comprehensions          | 14.0 us                                                     | 15.4 us: 1.10x slower                                                    |
| async_tree_none         | 286 ms                                                      | 314 ms: 1.10x slower                                                     |
| richards                | 27.6 ms                                                     | 30.4 ms: 1.10x slower                                                    |
| scimark_lu              | 57.5 ms                                                     | 63.3 ms: 1.10x slower                                                    |
| json                    | 2.94 ms                                                     | 3.25 ms: 1.10x slower                                                    |
| async_tree_memoization  | 333 ms                                                      | 368 ms: 1.11x slower                                                     |
| go                      | 89.0 ms                                                     | 99.2 ms: 1.11x slower                                                    |
| sqlglot_transpile       | 1.02 ms                                                     | 1.13 ms: 1.12x slower                                                    |
| unpickle_pure_python    | 134 us                                                      | 150 us: 1.12x slower                                                     |
| hexiom                  | 4.00 ms                                                     | 4.56 ms: 1.14x slower                                                    |
| logging_silent          | 60.5 ns                                                     | 70.1 ns: 1.16x slower                                                    |
| sqlglot_parse           | 802 us                                                      | 931 us: 1.16x slower                                                     |
| chaos                   | 42.1 ms                                                     | 48.9 ms: 1.16x slower                                                    |
| mdp                     | 1.42 sec                                                    | 1.74 sec: 1.23x slower                                                   |
| unpack_sequence         | 36.9 ns                                                     | 46.0 ns: 1.25x slower                                                    |
| deltablue               | 2.12 ms                                                     | 2.65 ms: 1.25x slower                                                    |
| json_dumps              | 5.83 ms                                                     | 7.60 ms: 1.30x slower                                                    |
| coverage                | 39.8 ms                                                     | 53.2 ms: 1.34x slower                                                    |
| mypy2                   | 209 ms                                                      | 280 ms: 1.34x slower                                                     |
| generators              | 22.6 ms                                                     | 34.0 ms: 1.50x slower                                                    |
| asyncio_tcp             | 471 ms                                                      | 718 ms: 1.52x slower                                                     |
| Geometric mean          | (ref)                                                       | 1.05x slower                                                             |

Benchmark hidden because not significant (2): unpickle_list, dulwich_log
Ignored benchmarks (8) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20230404-3.11.3-f3909b8/bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
