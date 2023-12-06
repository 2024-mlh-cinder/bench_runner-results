
# Results vs. 3.12.0

- fork: python
- ref: v3.11.0b2
- machine: linux-x86_64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.49%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 282 ms: 1.01x faster                                             |
| chameleon      | 7.27 ms                                                      | 7.52 ms: 1.03x slower                                            |
| docutils       | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                           |
| tornado_http   | 122 ms                                                       | 117 ms: 1.04x faster                                             |
| Geometric mean | (ref)                                                        | 1.01x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 740 ms: 1.05x slower                                             |
| async_tree_memoization  | 554 ms                                                       | 609 ms: 1.10x slower                                             |
| async_tree_io           | 1.06 sec                                                     | 1.16 sec: 1.10x slower                                           |
| async_tree_none         | 459 ms                                                       | 511 ms: 1.11x slower                                             |
| Geometric mean          | (ref)                                                        | 1.09x slower                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 73.8 ms: 1.11x faster                                            |
| pidigits       | 264 ms                                                       | 251 ms: 1.05x faster                                             |
| nbody          | 88.2 ms                                                      | 96.9 ms: 1.10x slower                                            |
| Geometric mean | (ref)                                                        | 1.02x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.11 ms: 1.16x faster                                            |
| regex_dna      | 240 ms                                                       | 227 ms: 1.06x faster                                             |
| regex_v8       | 24.4 ms                                                      | 24.1 ms: 1.01x faster                                            |
| regex_compile  | 145 ms                                                       | 157 ms: 1.08x slower                                             |
| Geometric mean | (ref)                                                        | 1.03x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.3 us: 1.16x faster                                            |
| pickle_list          | 4.22 us                                                      | 3.86 us: 1.09x faster                                            |
| xml_etree_generate   | 85.3 ms                                                      | 79.0 ms: 1.08x faster                                            |
| pickle_dict          | 32.0 us                                                      | 30.4 us: 1.05x faster                                            |
| xml_etree_process    | 58.3 ms                                                      | 55.8 ms: 1.04x faster                                            |
| pickle               | 10.0 us                                                      | 9.77 us: 1.03x faster                                            |
| unpickle_list        | 4.65 us                                                      | 4.57 us: 1.02x faster                                            |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                             |
| json_loads           | 24.3 us                                                      | 25.1 us: 1.03x slower                                            |
| xml_etree_parse      | 147 ms                                                       | 153 ms: 1.04x slower                                             |
| unpickle_pure_python | 210 us                                                       | 234 us: 1.12x slower                                             |
| json_dumps           | 10.3 ms                                                      | 13.3 ms: 1.30x slower                                            |
| Geometric mean       | (ref)                                                        | 1.00x slower                                                     |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.70 ms: 1.13x faster                                            |
| python_startup         | 11.7 ms                                                      | 10.7 ms: 1.10x faster                                            |
| Geometric mean         | (ref)                                                        | 1.11x faster                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 39.5 ms: 1.02x slower                                            |
| mako            | 10.1 ms                                                      | 10.9 ms: 1.09x slower                                            |
| Geometric mean  | (ref)                                                        | 1.05x slower                                                     |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------:|
| async_generators        | 385 ms                                                       | 313 ms: 1.23x faster                                             |
| unpack_sequence         | 54.5 ns                                                      | 45.1 ns: 1.21x faster                                            |
| regex_effbot            | 3.61 ms                                                      | 3.11 ms: 1.16x faster                                            |
| unpickle                | 15.3 us                                                      | 13.3 us: 1.16x faster                                            |
| python_startup_no_site  | 8.67 ms                                                      | 7.70 ms: 1.13x faster                                            |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 4.05 ms: 1.11x faster                                            |
| float                   | 81.6 ms                                                      | 73.8 ms: 1.11x faster                                            |
| python_startup          | 11.7 ms                                                      | 10.7 ms: 1.10x faster                                            |
| pickle_list             | 4.22 us                                                      | 3.86 us: 1.09x faster                                            |
| bench_mp_pool           | 4.96 ms                                                      | 4.55 ms: 1.09x faster                                            |
| gunicorn                | 1.01 ms                                                      | 929 us: 1.08x faster                                             |
| xml_etree_generate      | 85.3 ms                                                      | 79.0 ms: 1.08x faster                                            |
| aiohttp                 | 1.02 ms                                                      | 944 us: 1.08x faster                                             |
| sqlite_synth            | 2.72 us                                                      | 2.54 us: 1.07x faster                                            |
| scimark_fft             | 303 ms                                                       | 284 ms: 1.07x faster                                             |
| pprint_safe_repr        | 808 ms                                                       | 759 ms: 1.06x faster                                             |
| regex_dna               | 240 ms                                                       | 227 ms: 1.06x faster                                             |
| pidigits                | 264 ms                                                       | 251 ms: 1.05x faster                                             |
| pickle_dict             | 32.0 us                                                      | 30.4 us: 1.05x faster                                            |
| sqlalchemy_declarative  | 161 ms                                                       | 153 ms: 1.05x faster                                             |
| pprint_pformat          | 1.64 sec                                                     | 1.57 sec: 1.05x faster                                           |
| xml_etree_process       | 58.3 ms                                                      | 55.8 ms: 1.04x faster                                            |
| tornado_http            | 122 ms                                                       | 117 ms: 1.04x faster                                             |
| scimark_monte_carlo     | 69.5 ms                                                      | 67.5 ms: 1.03x faster                                            |
| pickle                  | 10.0 us                                                      | 9.77 us: 1.03x faster                                            |
| pyflate                 | 442 ms                                                       | 431 ms: 1.03x faster                                             |
| docutils                | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                           |
| telco                   | 7.16 ms                                                      | 6.99 ms: 1.02x faster                                            |
| unpickle_list           | 4.65 us                                                      | 4.57 us: 1.02x faster                                            |
| regex_v8                | 24.4 ms                                                      | 24.1 ms: 1.01x faster                                            |
| 2to3                    | 285 ms                                                       | 282 ms: 1.01x faster                                             |
| spectral_norm           | 93.9 ms                                                      | 93.4 ms: 1.00x faster                                            |
| scimark_sor             | 107 ms                                                       | 108 ms: 1.01x slower                                             |
| deepcopy_memo           | 36.6 us                                                      | 36.9 us: 1.01x slower                                            |
| crypto_pyaes            | 82.4 ms                                                      | 83.5 ms: 1.01x slower                                            |
| raytrace                | 301 ms                                                       | 305 ms: 1.01x slower                                             |
| deepcopy_reduce         | 3.41 us                                                      | 3.47 us: 1.02x slower                                            |
| pathlib                 | 18.7 ms                                                      | 19.1 ms: 1.02x slower                                            |
| django_template         | 38.7 ms                                                      | 39.5 ms: 1.02x slower                                            |
| meteor_contest          | 126 ms                                                       | 129 ms: 1.02x slower                                             |
| xml_etree_iterparse     | 104 ms                                                       | 106 ms: 1.02x slower                                             |
| sqlglot_optimize        | 58.4 ms                                                      | 59.7 ms: 1.02x slower                                            |
| json_loads              | 24.3 us                                                      | 25.1 us: 1.03x slower                                            |
| chameleon               | 7.27 ms                                                      | 7.52 ms: 1.03x slower                                            |
| dulwich_log             | 64.9 ms                                                      | 67.2 ms: 1.04x slower                                            |
| go                      | 149 ms                                                       | 154 ms: 1.04x slower                                             |
| deepcopy                | 371 us                                                       | 385 us: 1.04x slower                                             |
| sqlglot_normalize       | 119 ms                                                       | 124 ms: 1.04x slower                                             |
| dask                    | 394 ms                                                       | 410 ms: 1.04x slower                                             |
| sympy_integrate         | 24.0 ms                                                      | 25.0 ms: 1.04x slower                                            |
| create_gc_cycles        | 1.58 ms                                                      | 1.64 ms: 1.04x slower                                            |
| xml_etree_parse         | 147 ms                                                       | 153 ms: 1.04x slower                                             |
| sqlalchemy_imperative   | 18.6 ms                                                      | 19.4 ms: 1.04x slower                                            |
| bench_thread_pool       | 956 us                                                       | 1.00 ms: 1.05x slower                                            |
| async_tree_cpu_io_mixed | 704 ms                                                       | 740 ms: 1.05x slower                                             |
| logging_silent          | 93.3 ns                                                      | 98.9 ns: 1.06x slower                                            |
| gc_traversal            | 3.70 ms                                                      | 3.94 ms: 1.06x slower                                            |
| sympy_str               | 305 ms                                                       | 327 ms: 1.07x slower                                             |
| logging_format          | 7.29 us                                                      | 7.81 us: 1.07x slower                                            |
| richards                | 45.1 ms                                                      | 48.5 ms: 1.08x slower                                            |
| regex_compile           | 145 ms                                                       | 157 ms: 1.08x slower                                             |
| sympy_expand            | 492 ms                                                       | 533 ms: 1.08x slower                                             |
| nqueens                 | 90.1 ms                                                      | 97.7 ms: 1.09x slower                                            |
| logging_simple          | 6.64 us                                                      | 7.21 us: 1.09x slower                                            |
| mako                    | 10.1 ms                                                      | 10.9 ms: 1.09x slower                                            |
| sympy_sum               | 163 ms                                                       | 177 ms: 1.09x slower                                             |
| nbody                   | 88.2 ms                                                      | 96.9 ms: 1.10x slower                                            |
| async_tree_memoization  | 554 ms                                                       | 609 ms: 1.10x slower                                             |
| async_tree_io           | 1.06 sec                                                     | 1.16 sec: 1.10x slower                                           |
| async_tree_none         | 459 ms                                                       | 511 ms: 1.11x slower                                             |
| mdp                     | 2.56 sec                                                     | 2.85 sec: 1.11x slower                                           |
| unpickle_pure_python    | 210 us                                                       | 234 us: 1.12x slower                                             |
| chaos                   | 64.1 ms                                                      | 72.1 ms: 1.13x slower                                            |
| scimark_lu              | 98.6 ms                                                      | 111 ms: 1.13x slower                                             |
| hexiom                  | 5.97 ms                                                      | 6.99 ms: 1.17x slower                                            |
| mypy2                   | 365 ms                                                       | 439 ms: 1.20x slower                                             |
| coroutines              | 23.1 ms                                                      | 27.9 ms: 1.21x slower                                            |
| deltablue               | 3.24 ms                                                      | 3.98 ms: 1.23x slower                                            |
| fannkuch                | 362 ms                                                       | 447 ms: 1.24x slower                                             |
| sqlglot_transpile       | 1.80 ms                                                      | 2.29 ms: 1.27x slower                                            |
| comprehensions          | 21.8 us                                                      | 27.9 us: 1.28x slower                                            |
| json_dumps              | 10.3 ms                                                      | 13.3 ms: 1.30x slower                                            |
| sqlglot_parse           | 1.41 ms                                                      | 1.95 ms: 1.38x slower                                            |
| generators              | 37.3 ms                                                      | 55.2 ms: 1.48x slower                                            |
| asyncio_tcp             | 380 ms                                                       | 746 ms: 1.97x slower                                             |
| Geometric mean          | (ref)                                                        | 1.04x slower                                                     |

Benchmark hidden because not significant (3): json, pickle_pure_python, pycparser
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20220530-3.11.0b2-72f00f4/bm-20220530-pythonperf2-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4.json: genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.49% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
