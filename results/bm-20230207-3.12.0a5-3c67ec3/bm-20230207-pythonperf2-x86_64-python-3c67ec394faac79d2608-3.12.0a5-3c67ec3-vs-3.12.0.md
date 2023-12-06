
# Results vs. 3.12.0

- fork: python
- ref: 3c67ec394faac79d2608
- machine: linux-x86_64
- commit hash: 3c67ec3
- commit date: 2023-02-07
- overall geometric mean: 1.01x slower \*
- HPT reliability: 89.05%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 282 ms: 1.01x faster                                                        |
| chameleon      | 7.27 ms                                                      | 7.46 ms: 1.03x slower                                                       |
| docutils       | 2.89 sec                                                     | 2.78 sec: 1.04x faster                                                      |
| tornado_http   | 122 ms                                                       | 117 ms: 1.04x faster                                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 737 ms: 1.05x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 601 ms: 1.09x slower                                                        |
| async_tree_none         | 459 ms                                                       | 503 ms: 1.10x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.10x slower                                                      |
| Geometric mean          | (ref)                                                        | 1.08x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 71.9 ms: 1.14x faster                                                       |
| pidigits       | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| nbody          | 88.2 ms                                                      | 101 ms: 1.15x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 24.4 ms                                                      | 22.7 ms: 1.08x faster                                                       |
| regex_effbot   | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                |

Benchmark hidden because not significant (2): regex_dna, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 12.8 us: 1.20x faster                                                       |
| pickle_list          | 4.22 us                                                      | 3.84 us: 1.10x faster                                                       |
| xml_etree_generate   | 85.3 ms                                                      | 80.6 ms: 1.06x faster                                                       |
| xml_etree_process    | 58.3 ms                                                      | 55.6 ms: 1.05x faster                                                       |
| xml_etree_parse      | 147 ms                                                       | 142 ms: 1.03x faster                                                        |
| unpickle_list        | 4.65 us                                                      | 4.50 us: 1.03x faster                                                       |
| unpickle_pure_python | 210 us                                                       | 204 us: 1.03x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 312 us: 1.02x faster                                                        |
| json_dumps           | 10.3 ms                                                      | 10.0 ms: 1.02x faster                                                       |
| json_loads           | 24.3 us                                                      | 23.8 us: 1.02x faster                                                       |
| pickle               | 10.0 us                                                      | 9.88 us: 1.02x faster                                                       |
| pickle_dict          | 32.0 us                                                      | 31.6 us: 1.01x faster                                                       |
| xml_etree_iterparse  | 104 ms                                                       | 103 ms: 1.01x faster                                                        |
| Geometric mean       | (ref)                                                        | 1.05x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 8.25 ms: 1.05x faster                                                       |
| python_startup         | 11.7 ms                                                      | 11.2 ms: 1.04x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.05x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 10.1 ms                                                      | 10.3 ms: 1.02x slower                                                       |
| django_template | 38.7 ms                                                      | 40.5 ms: 1.05x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.03x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence         | 54.5 ns                                                      | 43.3 ns: 1.26x faster                                                       |
| scimark_sparse_mat_mult | 4.49 ms                                                      | 3.61 ms: 1.24x faster                                                       |
| unpickle                | 15.3 us                                                      | 12.8 us: 1.20x faster                                                       |
| async_generators        | 385 ms                                                       | 325 ms: 1.19x faster                                                        |
| float                   | 81.6 ms                                                      | 71.9 ms: 1.14x faster                                                       |
| pickle_list             | 4.22 us                                                      | 3.84 us: 1.10x faster                                                       |
| scimark_fft             | 303 ms                                                       | 278 ms: 1.09x faster                                                        |
| telco                   | 7.16 ms                                                      | 6.59 ms: 1.09x faster                                                       |
| pprint_safe_repr        | 808 ms                                                       | 744 ms: 1.09x faster                                                        |
| regex_v8                | 24.4 ms                                                      | 22.7 ms: 1.08x faster                                                       |
| pprint_pformat          | 1.64 sec                                                     | 1.53 sec: 1.07x faster                                                      |
| xml_etree_generate      | 85.3 ms                                                      | 80.6 ms: 1.06x faster                                                       |
| sqlite_synth            | 2.72 us                                                      | 2.58 us: 1.06x faster                                                       |
| pidigits                | 264 ms                                                       | 251 ms: 1.05x faster                                                        |
| bench_mp_pool           | 4.96 ms                                                      | 4.71 ms: 1.05x faster                                                       |
| python_startup_no_site  | 8.67 ms                                                      | 8.25 ms: 1.05x faster                                                       |
| xml_etree_process       | 58.3 ms                                                      | 55.6 ms: 1.05x faster                                                       |
| json                    | 5.17 ms                                                      | 4.94 ms: 1.05x faster                                                       |
| tornado_http            | 122 ms                                                       | 117 ms: 1.04x faster                                                        |
| gc_traversal            | 3.70 ms                                                      | 3.55 ms: 1.04x faster                                                       |
| python_startup          | 11.7 ms                                                      | 11.2 ms: 1.04x faster                                                       |
| docutils                | 2.89 sec                                                     | 2.78 sec: 1.04x faster                                                      |
| xml_etree_parse         | 147 ms                                                       | 142 ms: 1.03x faster                                                        |
| deepcopy_reduce         | 3.41 us                                                      | 3.30 us: 1.03x faster                                                       |
| unpickle_list           | 4.65 us                                                      | 4.50 us: 1.03x faster                                                       |
| pyflate                 | 442 ms                                                       | 428 ms: 1.03x faster                                                        |
| regex_effbot            | 3.61 ms                                                      | 3.50 ms: 1.03x faster                                                       |
| unpickle_pure_python    | 210 us                                                       | 204 us: 1.03x faster                                                        |
| pickle_pure_python      | 319 us                                                       | 312 us: 1.02x faster                                                        |
| comprehensions          | 21.8 us                                                      | 21.3 us: 1.02x faster                                                       |
| json_dumps              | 10.3 ms                                                      | 10.0 ms: 1.02x faster                                                       |
| deepcopy_memo           | 36.6 us                                                      | 35.8 us: 1.02x faster                                                       |
| json_loads              | 24.3 us                                                      | 23.8 us: 1.02x faster                                                       |
| scimark_sor             | 107 ms                                                       | 105 ms: 1.02x faster                                                        |
| pickle                  | 10.0 us                                                      | 9.88 us: 1.02x faster                                                       |
| pycparser               | 1.29 sec                                                     | 1.28 sec: 1.02x faster                                                      |
| pickle_dict             | 32.0 us                                                      | 31.6 us: 1.01x faster                                                       |
| sqlglot_optimize        | 58.4 ms                                                      | 57.7 ms: 1.01x faster                                                       |
| 2to3                    | 285 ms                                                       | 282 ms: 1.01x faster                                                        |
| xml_etree_iterparse     | 104 ms                                                       | 103 ms: 1.01x faster                                                        |
| crypto_pyaes            | 82.4 ms                                                      | 81.8 ms: 1.01x faster                                                       |
| sqlglot_normalize       | 119 ms                                                       | 120 ms: 1.01x slower                                                        |
| scimark_monte_carlo     | 69.5 ms                                                      | 70.2 ms: 1.01x slower                                                       |
| sympy_integrate         | 24.0 ms                                                      | 24.3 ms: 1.01x slower                                                       |
| meteor_contest          | 126 ms                                                       | 128 ms: 1.01x slower                                                        |
| spectral_norm           | 93.9 ms                                                      | 95.4 ms: 1.02x slower                                                       |
| mako                    | 10.1 ms                                                      | 10.3 ms: 1.02x slower                                                       |
| logging_format          | 7.29 us                                                      | 7.43 us: 1.02x slower                                                       |
| pathlib                 | 18.7 ms                                                      | 19.1 ms: 1.02x slower                                                       |
| go                      | 149 ms                                                       | 152 ms: 1.02x slower                                                        |
| asyncio_tcp             | 380 ms                                                       | 388 ms: 1.02x slower                                                        |
| richards                | 45.1 ms                                                      | 46.1 ms: 1.02x slower                                                       |
| dulwich_log             | 64.9 ms                                                      | 66.6 ms: 1.03x slower                                                       |
| sympy_str               | 305 ms                                                       | 313 ms: 1.03x slower                                                        |
| chameleon               | 7.27 ms                                                      | 7.46 ms: 1.03x slower                                                       |
| deepcopy                | 371 us                                                       | 383 us: 1.03x slower                                                        |
| logging_silent          | 93.3 ns                                                      | 96.5 ns: 1.04x slower                                                       |
| mypy2                   | 365 ms                                                       | 379 ms: 1.04x slower                                                        |
| create_gc_cycles        | 1.58 ms                                                      | 1.64 ms: 1.04x slower                                                       |
| mdp                     | 2.56 sec                                                     | 2.66 sec: 1.04x slower                                                      |
| django_template         | 38.7 ms                                                      | 40.5 ms: 1.05x slower                                                       |
| nqueens                 | 90.1 ms                                                      | 94.2 ms: 1.05x slower                                                       |
| async_tree_cpu_io_mixed | 704 ms                                                       | 737 ms: 1.05x slower                                                        |
| scimark_lu              | 98.6 ms                                                      | 104 ms: 1.05x slower                                                        |
| sympy_sum               | 163 ms                                                       | 172 ms: 1.06x slower                                                        |
| sqlglot_transpile       | 1.80 ms                                                      | 1.93 ms: 1.07x slower                                                       |
| sympy_expand            | 492 ms                                                       | 526 ms: 1.07x slower                                                        |
| async_tree_memoization  | 554 ms                                                       | 601 ms: 1.09x slower                                                        |
| chaos                   | 64.1 ms                                                      | 69.6 ms: 1.09x slower                                                       |
| hexiom                  | 5.97 ms                                                      | 6.49 ms: 1.09x slower                                                       |
| async_tree_none         | 459 ms                                                       | 503 ms: 1.10x slower                                                        |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.10x slower                                                      |
| sqlglot_parse           | 1.41 ms                                                      | 1.56 ms: 1.11x slower                                                       |
| deltablue               | 3.24 ms                                                      | 3.60 ms: 1.11x slower                                                       |
| fannkuch                | 362 ms                                                       | 409 ms: 1.13x slower                                                        |
| nbody                   | 88.2 ms                                                      | 101 ms: 1.15x slower                                                        |
| coroutines              | 23.1 ms                                                      | 29.1 ms: 1.26x slower                                                       |
| coverage                | 66.3 ms                                                      | 86.0 ms: 1.30x slower                                                       |
| dask                    | 394 ms                                                       | 562 ms: 1.43x slower                                                        |
| generators              | 37.3 ms                                                      | 60.4 ms: 1.62x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.01x slower                                                                |

Benchmark hidden because not significant (5): raytrace, regex_dna, regex_compile, logging_simple, bench_thread_pool
Ignored benchmarks (13) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, gunicorn, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (4) of results/bm-20230207-3.12.0a5-3c67ec3/bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 89.05% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
