
# Results vs. 3.12.0

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: linux-x86_64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.02x slower \*
- HPT reliability: 97.04%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 286 ms: 1.00x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.78 sec: 1.04x faster                                                      |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 742 ms: 1.05x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.15 sec: 1.09x slower                                                      |
| async_tree_memoization  | 554 ms                                                       | 608 ms: 1.10x slower                                                        |
| async_tree_none         | 459 ms                                                       | 505 ms: 1.10x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.09x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 72.4 ms: 1.13x faster                                                       |
| pidigits       | 264 ms                                                       | 252 ms: 1.05x faster                                                        |
| nbody          | 88.2 ms                                                      | 98.1 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 24.4 ms                                                      | 23.0 ms: 1.06x faster                                                       |
| regex_effbot   | 3.61 ms                                                      | 3.43 ms: 1.05x faster                                                       |
| regex_dna      | 240 ms                                                       | 229 ms: 1.05x faster                                                        |
| regex_compile  | 145 ms                                                       | 149 ms: 1.03x slower                                                        |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.3 us: 1.15x faster                                                       |
| pickle_list          | 4.22 us                                                      | 3.70 us: 1.14x faster                                                       |
| xml_etree_generate   | 85.3 ms                                                      | 80.3 ms: 1.06x faster                                                       |
| xml_etree_process    | 58.3 ms                                                      | 55.4 ms: 1.05x faster                                                       |
| unpickle_list        | 4.65 us                                                      | 4.48 us: 1.04x faster                                                       |
| pickle               | 10.0 us                                                      | 9.71 us: 1.03x faster                                                       |
| pickle_dict          | 32.0 us                                                      | 31.1 us: 1.03x faster                                                       |
| xml_etree_parse      | 147 ms                                                       | 144 ms: 1.02x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 313 us: 1.02x faster                                                        |
| json_dumps           | 10.3 ms                                                      | 10.1 ms: 1.01x faster                                                       |
| json_loads           | 24.3 us                                                      | 24.0 us: 1.01x faster                                                       |
| unpickle_pure_python | 210 us                                                       | 214 us: 1.02x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.04x faster                                                                |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.87 ms: 1.10x faster                                                       |
| python_startup         | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.09x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 39.2 ms: 1.01x slower                                                       |
| mako            | 10.1 ms                                                      | 10.2 ms: 1.02x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.01x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence         | 54.5 ns                                                      | 44.0 ns: 1.24x faster                                                       |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 3.70 ms: 1.21x faster                                                       |
| async_generators        | 385 ms                                                       | 322 ms: 1.20x faster                                                        |
| unpickle                | 15.3 us                                                      | 13.3 us: 1.15x faster                                                       |
| pickle_list             | 4.22 us                                                      | 3.70 us: 1.14x faster                                                       |
| float                   | 81.6 ms                                                      | 72.4 ms: 1.13x faster                                                       |
| python_startup_no_site  | 8.67 ms                                                      | 7.87 ms: 1.10x faster                                                       |
| python_startup          | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                                       |
| scimark_fft             | 303 ms                                                       | 283 ms: 1.07x faster                                                        |
| telco                   | 7.16 ms                                                      | 6.70 ms: 1.07x faster                                                       |
| xml_etree_generate      | 85.3 ms                                                      | 80.3 ms: 1.06x faster                                                       |
| regex_v8                | 24.4 ms                                                      | 23.0 ms: 1.06x faster                                                       |
| sqlite_synth            | 2.72 us                                                      | 2.56 us: 1.06x faster                                                       |
| regex_effbot            | 3.61 ms                                                      | 3.43 ms: 1.05x faster                                                       |
| xml_etree_process       | 58.3 ms                                                      | 55.4 ms: 1.05x faster                                                       |
| pidigits                | 264 ms                                                       | 252 ms: 1.05x faster                                                        |
| regex_dna               | 240 ms                                                       | 229 ms: 1.05x faster                                                        |
| gc_traversal            | 3.70 ms                                                      | 3.54 ms: 1.05x faster                                                       |
| scimark_monte_carlo     | 69.5 ms                                                      | 66.6 ms: 1.04x faster                                                       |
| docutils                | 2.89 sec                                                     | 2.78 sec: 1.04x faster                                                      |
| unpickle_list           | 4.65 us                                                      | 4.48 us: 1.04x faster                                                       |
| pickle                  | 10.0 us                                                      | 9.71 us: 1.03x faster                                                       |
| pickle_dict             | 32.0 us                                                      | 31.1 us: 1.03x faster                                                       |
| pycparser               | 1.29 sec                                                     | 1.26 sec: 1.03x faster                                                      |
| xml_etree_parse         | 147 ms                                                       | 144 ms: 1.02x faster                                                        |
| deepcopy_reduce         | 3.41 us                                                      | 3.33 us: 1.02x faster                                                       |
| pickle_pure_python      | 319 us                                                       | 313 us: 1.02x faster                                                        |
| pyflate                 | 442 ms                                                       | 433 ms: 1.02x faster                                                        |
| pprint_safe_repr        | 808 ms                                                       | 794 ms: 1.02x faster                                                        |
| crypto_pyaes            | 82.4 ms                                                      | 81.1 ms: 1.02x faster                                                       |
| json_dumps              | 10.3 ms                                                      | 10.1 ms: 1.01x faster                                                       |
| pprint_pformat          | 1.64 sec                                                     | 1.63 sec: 1.01x faster                                                      |
| json_loads              | 24.3 us                                                      | 24.0 us: 1.01x faster                                                       |
| raytrace                | 301 ms                                                       | 299 ms: 1.01x faster                                                        |
| 2to3                    | 285 ms                                                       | 286 ms: 1.00x slower                                                        |
| scimark_sor             | 107 ms                                                       | 108 ms: 1.01x slower                                                        |
| django_template         | 38.7 ms                                                      | 39.2 ms: 1.01x slower                                                       |
| sqlglot_optimize        | 58.4 ms                                                      | 59.3 ms: 1.02x slower                                                       |
| mako                    | 10.1 ms                                                      | 10.2 ms: 1.02x slower                                                       |
| asyncio_tcp             | 380 ms                                                       | 386 ms: 1.02x slower                                                        |
| deepcopy                | 371 us                                                       | 379 us: 1.02x slower                                                        |
| unpickle_pure_python    | 210 us                                                       | 214 us: 1.02x slower                                                        |
| scimark_lu              | 98.6 ms                                                      | 101 ms: 1.02x slower                                                        |
| sqlglot_normalize       | 119 ms                                                       | 123 ms: 1.03x slower                                                        |
| go                      | 149 ms                                                       | 153 ms: 1.03x slower                                                        |
| bench_thread_pool       | 956 us                                                       | 987 us: 1.03x slower                                                        |
| regex_compile           | 145 ms                                                       | 149 ms: 1.03x slower                                                        |
| pathlib                 | 18.7 ms                                                      | 19.4 ms: 1.04x slower                                                       |
| meteor_contest          | 126 ms                                                       | 131 ms: 1.04x slower                                                        |
| dask                    | 394 ms                                                       | 408 ms: 1.04x slower                                                        |
| dulwich_log             | 64.9 ms                                                      | 67.5 ms: 1.04x slower                                                       |
| richards                | 45.1 ms                                                      | 46.9 ms: 1.04x slower                                                       |
| mypy2                   | 365 ms                                                       | 380 ms: 1.04x slower                                                        |
| nqueens                 | 90.1 ms                                                      | 94.0 ms: 1.04x slower                                                       |
| logging_simple          | 6.64 us                                                      | 6.95 us: 1.05x slower                                                       |
| fannkuch                | 362 ms                                                       | 380 ms: 1.05x slower                                                        |
| logging_format          | 7.29 us                                                      | 7.66 us: 1.05x slower                                                       |
| async_tree_cpu_io_mixed | 704 ms                                                       | 742 ms: 1.05x slower                                                        |
| sympy_integrate         | 24.0 ms                                                      | 25.6 ms: 1.06x slower                                                       |
| mdp                     | 2.56 sec                                                     | 2.75 sec: 1.08x slower                                                      |
| spectral_norm           | 93.9 ms                                                      | 101 ms: 1.08x slower                                                        |
| sqlglot_transpile       | 1.80 ms                                                      | 1.95 ms: 1.08x slower                                                       |
| logging_silent          | 93.3 ns                                                      | 102 ns: 1.09x slower                                                        |
| sympy_expand            | 492 ms                                                       | 537 ms: 1.09x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.15 sec: 1.09x slower                                                      |
| sympy_str               | 305 ms                                                       | 335 ms: 1.10x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 608 ms: 1.10x slower                                                        |
| async_tree_none         | 459 ms                                                       | 505 ms: 1.10x slower                                                        |
| chaos                   | 64.1 ms                                                      | 70.9 ms: 1.11x slower                                                       |
| nbody                   | 88.2 ms                                                      | 98.1 ms: 1.11x slower                                                       |
| sqlglot_parse           | 1.41 ms                                                      | 1.59 ms: 1.13x slower                                                       |
| hexiom                  | 5.97 ms                                                      | 6.77 ms: 1.13x slower                                                       |
| deltablue               | 3.24 ms                                                      | 3.69 ms: 1.14x slower                                                       |
| sympy_sum               | 163 ms                                                       | 186 ms: 1.14x slower                                                        |
| coroutines              | 23.1 ms                                                      | 27.9 ms: 1.21x slower                                                       |
| comprehensions          | 21.8 us                                                      | 27.1 us: 1.24x slower                                                       |
| coverage                | 66.3 ms                                                      | 89.3 ms: 1.35x slower                                                       |
| generators              | 37.3 ms                                                      | 60.5 ms: 1.62x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.02x slower                                                                |

Benchmark hidden because not significant (6): bench_mp_pool, deepcopy_memo, create_gc_cycles, chameleon, xml_etree_iterparse, json
Ignored benchmarks (14) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, gunicorn, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols
Ignored benchmarks (4) of results/bm-20230110-3.12.0a4-3d5d3f7/bm-20230110-pythonperf2-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 97.04% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
