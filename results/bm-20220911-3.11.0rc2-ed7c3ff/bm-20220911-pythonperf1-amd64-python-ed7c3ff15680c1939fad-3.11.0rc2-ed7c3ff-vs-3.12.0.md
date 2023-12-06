
# Results vs. 3.12.0

- fork: python
- ref: ed7c3ff15680c1939fad
- machine: windows-amd64
- commit hash: ed7c3ff
- commit date: 2022-09-11
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 202 ms: 1.05x faster                                                        |
| chameleon      | 4.95 ms                                                     | 5.09 ms: 1.03x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.57 sec: 1.02x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 92.1 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 488 ms: 1.02x slower                                                        |
| async_tree_io           | 712 ms                                                      | 740 ms: 1.04x slower                                                        |
| async_tree_none         | 286 ms                                                      | 310 ms: 1.08x slower                                                        |
| async_tree_memoization  | 333 ms                                                      | 368 ms: 1.11x slower                                                        |
| Geometric mean          | (ref)                                                       | 1.06x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| float          | 54.7 ms                                                     | 53.9 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 119 ms                                                      | 115 ms: 1.04x faster                                                        |
| regex_v8       | 13.5 ms                                                     | 13.4 ms: 1.01x faster                                                       |
| regex_effbot   | 1.58 ms                                                     | 1.60 ms: 1.01x slower                                                       |
| regex_compile  | 87.2 ms                                                     | 89.5 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.60 us: 1.12x faster                                                       |
| unpickle             | 8.44 us                                                     | 7.70 us: 1.10x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 51.2 ms: 1.09x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.65 us: 1.09x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.55 us: 1.06x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 35.9 ms: 1.05x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.2 us: 1.04x faster                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 61.9 ms: 1.02x faster                                                       |
| pickle_pure_python   | 195 us                                                      | 197 us: 1.01x slower                                                        |
| xml_etree_parse      | 90.5 ms                                                     | 91.6 ms: 1.01x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 149 us: 1.11x slower                                                        |
| json_dumps           | 5.83 ms                                                     | 7.66 ms: 1.31x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.3 ms: 1.04x faster                                                       |
| python_startup         | 18.8 ms                                                     | 18.5 ms: 1.02x faster                                                       |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 7.22 ms: 1.02x slower                                                       |
| django_template | 22.8 ms                                                     | 23.8 ms: 1.05x slower                                                       |
| Geometric mean  | (ref)                                                       | 1.04x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_generators        | 230 ms                                                      | 176 ms: 1.31x faster                                                        |
| pickle                  | 7.38 us                                                     | 6.60 us: 1.12x faster                                                       |
| pathlib                 | 79.6 ms                                                     | 72.1 ms: 1.10x faster                                                       |
| bench_mp_pool           | 67.2 ms                                                     | 61.2 ms: 1.10x faster                                                       |
| unpickle                | 8.44 us                                                     | 7.70 us: 1.10x faster                                                       |
| xml_etree_generate      | 55.8 ms                                                     | 51.2 ms: 1.09x faster                                                       |
| create_gc_cycles        | 726 us                                                      | 667 us: 1.09x faster                                                        |
| pickle_list             | 2.88 us                                                     | 2.65 us: 1.09x faster                                                       |
| gc_traversal            | 1.49 ms                                                     | 1.41 ms: 1.06x faster                                                       |
| unpickle_list           | 2.69 us                                                     | 2.55 us: 1.06x faster                                                       |
| 2to3                    | 213 ms                                                      | 202 ms: 1.05x faster                                                        |
| xml_etree_process       | 37.6 ms                                                     | 35.9 ms: 1.05x faster                                                       |
| telco                   | 4.08 ms                                                     | 3.91 ms: 1.05x faster                                                       |
| sqlite_synth            | 1.75 us                                                     | 1.67 us: 1.04x faster                                                       |
| pickle_dict             | 18.9 us                                                     | 18.2 us: 1.04x faster                                                       |
| python_startup_no_site  | 15.9 ms                                                     | 15.3 ms: 1.04x faster                                                       |
| regex_dna               | 119 ms                                                      | 115 ms: 1.04x faster                                                        |
| deepcopy_reduce         | 2.08 us                                                     | 2.00 us: 1.04x faster                                                       |
| sqlalchemy_declarative  | 84.5 ms                                                     | 81.7 ms: 1.03x faster                                                       |
| scimark_sor             | 79.8 ms                                                     | 77.3 ms: 1.03x faster                                                       |
| pidigits                | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| docutils                | 1.61 sec                                                    | 1.57 sec: 1.02x faster                                                      |
| xml_etree_iterparse     | 63.1 ms                                                     | 61.9 ms: 1.02x faster                                                       |
| python_startup          | 18.8 ms                                                     | 18.5 ms: 1.02x faster                                                       |
| float                   | 54.7 ms                                                     | 53.9 ms: 1.01x faster                                                       |
| regex_v8                | 13.5 ms                                                     | 13.4 ms: 1.01x faster                                                       |
| pprint_safe_repr        | 508 ms                                                      | 512 ms: 1.01x slower                                                        |
| regex_effbot            | 1.58 ms                                                     | 1.60 ms: 1.01x slower                                                       |
| aiohttp                 | 848 us                                                      | 857 us: 1.01x slower                                                        |
| pickle_pure_python      | 195 us                                                      | 197 us: 1.01x slower                                                        |
| xml_etree_parse         | 90.5 ms                                                     | 91.6 ms: 1.01x slower                                                       |
| sqlglot_normalize       | 183 ms                                                      | 186 ms: 1.01x slower                                                        |
| pprint_pformat          | 1.04 sec                                                    | 1.05 sec: 1.01x slower                                                      |
| pycparser               | 673 ms                                                      | 683 ms: 1.01x slower                                                        |
| dulwich_log             | 42.7 ms                                                     | 43.6 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed | 477 ms                                                      | 488 ms: 1.02x slower                                                        |
| bench_thread_pool       | 830 us                                                      | 849 us: 1.02x slower                                                        |
| mako                    | 7.05 ms                                                     | 7.22 ms: 1.02x slower                                                       |
| deepcopy                | 233 us                                                      | 239 us: 1.03x slower                                                        |
| regex_compile           | 87.2 ms                                                     | 89.5 ms: 1.03x slower                                                       |
| chameleon               | 4.95 ms                                                     | 5.09 ms: 1.03x slower                                                       |
| meteor_contest          | 72.1 ms                                                     | 74.3 ms: 1.03x slower                                                       |
| pyflate                 | 294 ms                                                      | 303 ms: 1.03x slower                                                        |
| scimark_monte_carlo     | 43.0 ms                                                     | 44.6 ms: 1.04x slower                                                       |
| logging_format          | 6.72 us                                                     | 6.97 us: 1.04x slower                                                       |
| async_tree_io           | 712 ms                                                      | 740 ms: 1.04x slower                                                        |
| crypto_pyaes            | 46.4 ms                                                     | 48.5 ms: 1.04x slower                                                       |
| sympy_integrate         | 13.0 ms                                                     | 13.5 ms: 1.05x slower                                                       |
| scimark_fft             | 181 ms                                                      | 189 ms: 1.05x slower                                                        |
| django_template         | 22.8 ms                                                     | 23.8 ms: 1.05x slower                                                       |
| dask                    | 255 ms                                                      | 267 ms: 1.05x slower                                                        |
| nqueens                 | 61.7 ms                                                     | 64.6 ms: 1.05x slower                                                       |
| fannkuch                | 244 ms                                                      | 256 ms: 1.05x slower                                                        |
| coroutines              | 14.1 ms                                                     | 14.9 ms: 1.05x slower                                                       |
| tornado_http            | 87.2 ms                                                     | 92.1 ms: 1.06x slower                                                       |
| sympy_expand            | 278 ms                                                      | 294 ms: 1.06x slower                                                        |
| logging_simple          | 6.21 us                                                     | 6.57 us: 1.06x slower                                                       |
| sympy_str               | 171 ms                                                      | 182 ms: 1.06x slower                                                        |
| comprehensions          | 14.0 us                                                     | 15.2 us: 1.08x slower                                                       |
| deepcopy_memo           | 23.4 us                                                     | 25.4 us: 1.08x slower                                                       |
| async_tree_none         | 286 ms                                                      | 310 ms: 1.08x slower                                                        |
| sympy_sum               | 90.1 ms                                                     | 98.2 ms: 1.09x slower                                                       |
| raytrace                | 192 ms                                                      | 211 ms: 1.09x slower                                                        |
| go                      | 89.0 ms                                                     | 97.5 ms: 1.10x slower                                                       |
| sqlglot_transpile       | 1.02 ms                                                     | 1.12 ms: 1.10x slower                                                       |
| scimark_lu              | 57.5 ms                                                     | 63.4 ms: 1.10x slower                                                       |
| async_tree_memoization  | 333 ms                                                      | 368 ms: 1.11x slower                                                        |
| richards                | 27.6 ms                                                     | 30.6 ms: 1.11x slower                                                       |
| unpickle_pure_python    | 134 us                                                      | 149 us: 1.11x slower                                                        |
| sqlalchemy_imperative   | 9.20 ms                                                     | 10.3 ms: 1.11x slower                                                       |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.81 ms: 1.12x slower                                                       |
| mdp                     | 1.42 sec                                                    | 1.59 sec: 1.12x slower                                                      |
| hexiom                  | 4.00 ms                                                     | 4.48 ms: 1.12x slower                                                       |
| chaos                   | 42.1 ms                                                     | 48.0 ms: 1.14x slower                                                       |
| spectral_norm           | 63.9 ms                                                     | 73.2 ms: 1.15x slower                                                       |
| sqlglot_parse           | 802 us                                                      | 920 us: 1.15x slower                                                        |
| unpack_sequence         | 36.9 ns                                                     | 42.7 ns: 1.16x slower                                                       |
| logging_silent          | 60.5 ns                                                     | 70.9 ns: 1.17x slower                                                       |
| deltablue               | 2.12 ms                                                     | 2.61 ms: 1.23x slower                                                       |
| json_dumps              | 5.83 ms                                                     | 7.66 ms: 1.31x slower                                                       |
| mypy2                   | 209 ms                                                      | 276 ms: 1.32x slower                                                        |
| coverage                | 39.8 ms                                                     | 53.2 ms: 1.34x slower                                                       |
| asyncio_tcp             | 471 ms                                                      | 688 ms: 1.46x slower                                                        |
| generators              | 22.6 ms                                                     | 33.5 ms: 1.48x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.04x slower                                                                |

Benchmark hidden because not significant (4): nbody, sqlglot_optimize, json_loads, json
Ignored benchmarks (8) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20220911-3.11.0rc2-ed7c3ff/bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
