
# Results vs. 3.12.0

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: linux-x86_64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.01x slower \*
- HPT reliability: 88.86%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 278 ms: 1.03x faster                                                        |
| chameleon      | 7.27 ms                                                      | 7.62 ms: 1.05x slower                                                       |
| docutils       | 2.89 sec                                                     | 2.79 sec: 1.04x faster                                                      |
| tornado_http   | 122 ms                                                       | 114 ms: 1.07x faster                                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 756 ms: 1.07x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.16 sec: 1.10x slower                                                      |
| async_tree_memoization  | 554 ms                                                       | 618 ms: 1.12x slower                                                        |
| async_tree_none         | 459 ms                                                       | 516 ms: 1.12x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.10x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 73.2 ms: 1.12x faster                                                       |
| pidigits       | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| nbody          | 88.2 ms                                                      | 98.1 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.34 ms: 1.08x faster                                                       |
| regex_v8       | 24.4 ms                                                      | 22.9 ms: 1.07x faster                                                       |
| regex_dna      | 240 ms                                                       | 232 ms: 1.04x faster                                                        |
| regex_compile  | 145 ms                                                       | 146 ms: 1.01x slower                                                        |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.3 us: 1.15x faster                                                       |
| xml_etree_generate   | 85.3 ms                                                      | 77.6 ms: 1.10x faster                                                       |
| pickle_list          | 4.22 us                                                      | 3.84 us: 1.10x faster                                                       |
| xml_etree_process    | 58.3 ms                                                      | 54.1 ms: 1.08x faster                                                       |
| xml_etree_parse      | 147 ms                                                       | 138 ms: 1.06x faster                                                        |
| unpickle_list        | 4.65 us                                                      | 4.47 us: 1.04x faster                                                       |
| pickle_pure_python   | 319 us                                                       | 313 us: 1.02x faster                                                        |
| unpickle_pure_python | 210 us                                                       | 208 us: 1.01x faster                                                        |
| pickle_dict          | 32.0 us                                                      | 31.9 us: 1.00x faster                                                       |
| pickle               | 10.0 us                                                      | 10.1 us: 1.01x slower                                                       |
| json_dumps           | 10.3 ms                                                      | 10.4 ms: 1.01x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.04x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_iterparse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.62 ms: 1.14x faster                                                       |
| python_startup         | 11.7 ms                                                      | 10.6 ms: 1.10x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.12x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 10.1 ms                                                      | 10.4 ms: 1.04x slower                                                       |
| django_template | 38.7 ms                                                      | 40.6 ms: 1.05x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.04x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| scimark_sparse_mat_mult | 4.49 ms                                                      | 3.58 ms: 1.25x faster                                                       |
| unpack_sequence         | 54.5 ns                                                      | 45.0 ns: 1.21x faster                                                       |
| async_generators        | 385 ms                                                       | 321 ms: 1.20x faster                                                        |
| unpickle                | 15.3 us                                                      | 13.3 us: 1.15x faster                                                       |
| python_startup_no_site  | 8.67 ms                                                      | 7.62 ms: 1.14x faster                                                       |
| aiohttp                 | 1.02 ms                                                      | 894 us: 1.14x faster                                                        |
| gunicorn                | 1.01 ms                                                      | 888 us: 1.13x faster                                                        |
| float                   | 81.6 ms                                                      | 73.2 ms: 1.12x faster                                                       |
| python_startup          | 11.7 ms                                                      | 10.6 ms: 1.10x faster                                                       |
| xml_etree_generate      | 85.3 ms                                                      | 77.6 ms: 1.10x faster                                                       |
| pickle_list             | 4.22 us                                                      | 3.84 us: 1.10x faster                                                       |
| bench_mp_pool           | 4.96 ms                                                      | 4.56 ms: 1.09x faster                                                       |
| regex_effbot            | 3.61 ms                                                      | 3.34 ms: 1.08x faster                                                       |
| telco                   | 7.16 ms                                                      | 6.64 ms: 1.08x faster                                                       |
| xml_etree_process       | 58.3 ms                                                      | 54.1 ms: 1.08x faster                                                       |
| sqlite_synth            | 2.72 us                                                      | 2.54 us: 1.07x faster                                                       |
| tornado_http            | 122 ms                                                       | 114 ms: 1.07x faster                                                        |
| regex_v8                | 24.4 ms                                                      | 22.9 ms: 1.07x faster                                                       |
| pprint_safe_repr        | 808 ms                                                       | 761 ms: 1.06x faster                                                        |
| xml_etree_parse         | 147 ms                                                       | 138 ms: 1.06x faster                                                        |
| scimark_fft             | 303 ms                                                       | 288 ms: 1.05x faster                                                        |
| pidigits                | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| pprint_pformat          | 1.64 sec                                                     | 1.57 sec: 1.05x faster                                                      |
| gc_traversal            | 3.70 ms                                                      | 3.54 ms: 1.05x faster                                                       |
| unpickle_list           | 4.65 us                                                      | 4.47 us: 1.04x faster                                                       |
| docutils                | 2.89 sec                                                     | 2.79 sec: 1.04x faster                                                      |
| regex_dna               | 240 ms                                                       | 232 ms: 1.04x faster                                                        |
| pycparser               | 1.29 sec                                                     | 1.25 sec: 1.03x faster                                                      |
| scimark_monte_carlo     | 69.5 ms                                                      | 67.8 ms: 1.03x faster                                                       |
| pyflate                 | 442 ms                                                       | 431 ms: 1.03x faster                                                        |
| 2to3                    | 285 ms                                                       | 278 ms: 1.03x faster                                                        |
| json                    | 5.17 ms                                                      | 5.05 ms: 1.03x faster                                                       |
| pickle_pure_python      | 319 us                                                       | 313 us: 1.02x faster                                                        |
| deepcopy_reduce         | 3.41 us                                                      | 3.35 us: 1.02x faster                                                       |
| raytrace                | 301 ms                                                       | 298 ms: 1.01x faster                                                        |
| unpickle_pure_python    | 210 us                                                       | 208 us: 1.01x faster                                                        |
| deepcopy_memo           | 36.6 us                                                      | 36.4 us: 1.01x faster                                                       |
| meteor_contest          | 126 ms                                                       | 126 ms: 1.01x faster                                                        |
| sqlglot_optimize        | 58.4 ms                                                      | 58.2 ms: 1.00x faster                                                       |
| pickle_dict             | 32.0 us                                                      | 31.9 us: 1.00x faster                                                       |
| sqlglot_normalize       | 119 ms                                                       | 120 ms: 1.01x slower                                                        |
| regex_compile           | 145 ms                                                       | 146 ms: 1.01x slower                                                        |
| pickle                  | 10.0 us                                                      | 10.1 us: 1.01x slower                                                       |
| crypto_pyaes            | 82.4 ms                                                      | 83.2 ms: 1.01x slower                                                       |
| pathlib                 | 18.7 ms                                                      | 19.0 ms: 1.01x slower                                                       |
| json_dumps              | 10.3 ms                                                      | 10.4 ms: 1.01x slower                                                       |
| scimark_sor             | 107 ms                                                       | 108 ms: 1.01x slower                                                        |
| dulwich_log             | 64.9 ms                                                      | 65.9 ms: 1.01x slower                                                       |
| mypy2                   | 365 ms                                                       | 372 ms: 1.02x slower                                                        |
| create_gc_cycles        | 1.58 ms                                                      | 1.61 ms: 1.02x slower                                                       |
| spectral_norm           | 93.9 ms                                                      | 96.1 ms: 1.02x slower                                                       |
| logging_silent          | 93.3 ns                                                      | 95.5 ns: 1.02x slower                                                       |
| mako                    | 10.1 ms                                                      | 10.4 ms: 1.04x slower                                                       |
| go                      | 149 ms                                                       | 155 ms: 1.04x slower                                                        |
| dask                    | 394 ms                                                       | 409 ms: 1.04x slower                                                        |
| chameleon               | 7.27 ms                                                      | 7.62 ms: 1.05x slower                                                       |
| django_template         | 38.7 ms                                                      | 40.6 ms: 1.05x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 1.90 ms: 1.05x slower                                                       |
| richards                | 45.1 ms                                                      | 47.6 ms: 1.06x slower                                                       |
| sympy_integrate         | 24.0 ms                                                      | 25.4 ms: 1.06x slower                                                       |
| mdp                     | 2.56 sec                                                     | 2.71 sec: 1.06x slower                                                      |
| deepcopy                | 371 us                                                       | 394 us: 1.06x slower                                                        |
| logging_simple          | 6.64 us                                                      | 7.06 us: 1.06x slower                                                       |
| logging_format          | 7.29 us                                                      | 7.77 us: 1.07x slower                                                       |
| sympy_str               | 305 ms                                                       | 326 ms: 1.07x slower                                                        |
| sympy_expand            | 492 ms                                                       | 527 ms: 1.07x slower                                                        |
| sqlglot_parse           | 1.41 ms                                                      | 1.51 ms: 1.07x slower                                                       |
| async_tree_cpu_io_mixed | 704 ms                                                       | 756 ms: 1.07x slower                                                        |
| nqueens                 | 90.1 ms                                                      | 97.1 ms: 1.08x slower                                                       |
| async_tree_io           | 1.06 sec                                                     | 1.16 sec: 1.10x slower                                                      |
| hexiom                  | 5.97 ms                                                      | 6.61 ms: 1.11x slower                                                       |
| comprehensions          | 21.8 us                                                      | 24.2 us: 1.11x slower                                                       |
| nbody                   | 88.2 ms                                                      | 98.1 ms: 1.11x slower                                                       |
| sympy_sum               | 163 ms                                                       | 181 ms: 1.11x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 618 ms: 1.12x slower                                                        |
| fannkuch                | 362 ms                                                       | 405 ms: 1.12x slower                                                        |
| scimark_lu              | 98.6 ms                                                      | 111 ms: 1.12x slower                                                        |
| async_tree_none         | 459 ms                                                       | 516 ms: 1.12x slower                                                        |
| deltablue               | 3.24 ms                                                      | 3.65 ms: 1.13x slower                                                       |
| chaos                   | 64.1 ms                                                      | 73.4 ms: 1.15x slower                                                       |
| coroutines              | 23.1 ms                                                      | 27.4 ms: 1.19x slower                                                       |
| coverage                | 66.3 ms                                                      | 81.5 ms: 1.23x slower                                                       |
| generators              | 37.3 ms                                                      | 54.6 ms: 1.46x slower                                                       |
| asyncio_tcp             | 380 ms                                                       | 747 ms: 1.97x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.01x slower                                                                |

Benchmark hidden because not significant (3): xml_etree_iterparse, json_loads, bench_thread_pool
Ignored benchmarks (11) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20221025-3.12.0a1-4ae1a0e/bm-20221025-pythonperf2-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e.json: genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 88.86% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
