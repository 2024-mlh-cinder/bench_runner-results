
# Results vs. 3.11.0

- fork: python
- ref: 3c67ec394faac79d2608
- machine: linux-x86_64
- commit hash: 3c67ec3
- commit date: 2023-02-07
- overall geometric mean: 1.04x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 282 ms: 1.01x faster                                                        |
| chameleon      | 7.42 ms                                                      | 7.46 ms: 1.00x slower                                                       |
| docutils       | 2.87 sec                                                     | 2.78 sec: 1.03x faster                                                      |
| html5lib       | 70.7 ms                                                      | 65.3 ms: 1.08x faster                                                       |
| tornado_http   | 125 ms                                                       | 117 ms: 1.07x faster                                                        |
| Geometric mean | (ref)                                                        | 1.04x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 601 ms: 1.08x faster                                                        |
| async_tree_none         | 529 ms                                                       | 503 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed | 762 ms                                                       | 737 ms: 1.03x faster                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                                      |
| Geometric mean          | (ref)                                                        | 1.05x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 76.0 ms                                                      | 71.9 ms: 1.06x faster                                                       |
| nbody          | 95.8 ms                                                      | 101 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 145 ms: 1.08x faster                                                        |
| regex_v8       | 23.7 ms                                                      | 22.7 ms: 1.04x faster                                                       |
| regex_effbot   | 3.42 ms                                                      | 3.50 ms: 1.03x slower                                                       |
| regex_dna      | 226 ms                                                       | 240 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.0 ms: 1.34x faster                                                       |
| json_loads           | 29.0 us                                                      | 23.8 us: 1.22x faster                                                       |
| unpickle_pure_python | 236 us                                                       | 204 us: 1.16x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 142 ms: 1.12x faster                                                        |
| xml_etree_iterparse  | 106 ms                                                       | 103 ms: 1.03x faster                                                        |
| unpickle             | 13.2 us                                                      | 12.8 us: 1.03x faster                                                       |
| pickle_pure_python   | 318 us                                                       | 312 us: 1.02x faster                                                        |
| pickle_list          | 3.89 us                                                      | 3.84 us: 1.02x faster                                                       |
| xml_etree_process    | 56.1 ms                                                      | 55.6 ms: 1.01x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 31.6 us: 1.01x faster                                                       |
| unpickle_list        | 4.47 us                                                      | 4.50 us: 1.01x slower                                                       |
| pickle               | 9.77 us                                                      | 9.88 us: 1.01x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.07x faster                                                                |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.2 ms: 1.03x slower                                                       |
| python_startup_no_site | 7.78 ms                                                      | 8.25 ms: 1.06x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.05x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako           | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                                       |
| genshi_xml     | 57.2 ms                                                      | 53.4 ms: 1.07x faster                                                       |
| genshi_text    | 26.1 ms                                                      | 24.6 ms: 1.06x faster                                                       |
| Geometric mean | (ref)                                                        | 1.05x faster                                                                |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| asyncio_tcp             | 752 ms                                                       | 388 ms: 1.94x faster                                                        |
| json_dumps              | 13.5 ms                                                      | 10.0 ms: 1.34x faster                                                       |
| json_loads              | 29.0 us                                                      | 23.8 us: 1.22x faster                                                       |
| mypy2                   | 449 ms                                                       | 379 ms: 1.18x faster                                                        |
| comprehensions          | 24.8 us                                                      | 21.3 us: 1.16x faster                                                       |
| unpickle_pure_python    | 236 us                                                       | 204 us: 1.16x faster                                                        |
| gc_traversal            | 4.06 ms                                                      | 3.55 ms: 1.15x faster                                                       |
| json                    | 5.59 ms                                                      | 4.94 ms: 1.13x faster                                                       |
| deltablue               | 4.03 ms                                                      | 3.60 ms: 1.12x faster                                                       |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 3.61 ms: 1.12x faster                                                       |
| fannkuch                | 457 ms                                                       | 409 ms: 1.12x faster                                                        |
| xml_etree_parse         | 159 ms                                                       | 142 ms: 1.12x faster                                                        |
| scimark_lu              | 115 ms                                                       | 104 ms: 1.11x faster                                                        |
| go                      | 166 ms                                                       | 152 ms: 1.09x faster                                                        |
| regex_compile           | 157 ms                                                       | 145 ms: 1.08x faster                                                        |
| html5lib                | 70.7 ms                                                      | 65.3 ms: 1.08x faster                                                       |
| richards                | 49.9 ms                                                      | 46.1 ms: 1.08x faster                                                       |
| logging_simple          | 7.21 us                                                      | 6.67 us: 1.08x faster                                                       |
| async_tree_memoization  | 648 ms                                                       | 601 ms: 1.08x faster                                                        |
| hexiom                  | 6.97 ms                                                      | 6.49 ms: 1.07x faster                                                       |
| sympy_str               | 336 ms                                                       | 313 ms: 1.07x faster                                                        |
| mako                    | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                                       |
| tornado_http            | 125 ms                                                       | 117 ms: 1.07x faster                                                        |
| genshi_xml              | 57.2 ms                                                      | 53.4 ms: 1.07x faster                                                       |
| sympy_sum               | 184 ms                                                       | 172 ms: 1.07x faster                                                        |
| pprint_pformat          | 1.63 sec                                                     | 1.53 sec: 1.07x faster                                                      |
| genshi_text             | 26.1 ms                                                      | 24.6 ms: 1.06x faster                                                       |
| float                   | 76.0 ms                                                      | 71.9 ms: 1.06x faster                                                       |
| pyflate                 | 453 ms                                                       | 428 ms: 1.06x faster                                                        |
| logging_silent          | 102 ns                                                       | 96.5 ns: 1.06x faster                                                       |
| sympy_integrate         | 25.6 ms                                                      | 24.3 ms: 1.05x faster                                                       |
| logging_format          | 7.83 us                                                      | 7.43 us: 1.05x faster                                                       |
| nqueens                 | 99.2 ms                                                      | 94.2 ms: 1.05x faster                                                       |
| async_tree_none         | 529 ms                                                       | 503 ms: 1.05x faster                                                        |
| bench_thread_pool       | 1.02 ms                                                      | 971 us: 1.05x faster                                                        |
| telco                   | 6.91 ms                                                      | 6.59 ms: 1.05x faster                                                       |
| pprint_safe_repr        | 780 ms                                                       | 744 ms: 1.05x faster                                                        |
| sympy_expand            | 550 ms                                                       | 526 ms: 1.05x faster                                                        |
| scimark_sor             | 109 ms                                                       | 105 ms: 1.04x faster                                                        |
| regex_v8                | 23.7 ms                                                      | 22.7 ms: 1.04x faster                                                       |
| deepcopy_memo           | 37.3 us                                                      | 35.8 us: 1.04x faster                                                       |
| unpack_sequence         | 44.9 ns                                                      | 43.3 ns: 1.04x faster                                                       |
| async_tree_cpu_io_mixed | 762 ms                                                       | 737 ms: 1.03x faster                                                        |
| xml_etree_iterparse     | 106 ms                                                       | 103 ms: 1.03x faster                                                        |
| docutils                | 2.87 sec                                                     | 2.78 sec: 1.03x faster                                                      |
| unpickle                | 13.2 us                                                      | 12.8 us: 1.03x faster                                                       |
| chaos                   | 71.6 ms                                                      | 69.6 ms: 1.03x faster                                                       |
| sqlglot_optimize        | 59.2 ms                                                      | 57.7 ms: 1.03x faster                                                       |
| dulwich_log             | 68.3 ms                                                      | 66.6 ms: 1.03x faster                                                       |
| raytrace                | 308 ms                                                       | 301 ms: 1.02x faster                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.17 sec: 1.02x faster                                                      |
| mdp                     | 2.72 sec                                                     | 2.66 sec: 1.02x faster                                                      |
| deepcopy_reduce         | 3.37 us                                                      | 3.30 us: 1.02x faster                                                       |
| pickle_pure_python      | 318 us                                                       | 312 us: 1.02x faster                                                        |
| deepcopy                | 389 us                                                       | 383 us: 1.02x faster                                                        |
| meteor_contest          | 130 ms                                                       | 128 ms: 1.02x faster                                                        |
| pickle_list             | 3.89 us                                                      | 3.84 us: 1.02x faster                                                       |
| 2to3                    | 286 ms                                                       | 282 ms: 1.01x faster                                                        |
| sqlglot_normalize       | 122 ms                                                       | 120 ms: 1.01x faster                                                        |
| xml_etree_process       | 56.1 ms                                                      | 55.6 ms: 1.01x faster                                                       |
| sqlglot_transpile       | 1.94 ms                                                      | 1.93 ms: 1.01x faster                                                       |
| pickle_dict             | 31.8 us                                                      | 31.6 us: 1.01x faster                                                       |
| scimark_monte_carlo     | 70.6 ms                                                      | 70.2 ms: 1.01x faster                                                       |
| chameleon               | 7.42 ms                                                      | 7.46 ms: 1.00x slower                                                       |
| unpickle_list           | 4.47 us                                                      | 4.50 us: 1.01x slower                                                       |
| async_generators        | 322 ms                                                       | 325 ms: 1.01x slower                                                        |
| pickle                  | 9.77 us                                                      | 9.88 us: 1.01x slower                                                       |
| spectral_norm           | 94.0 ms                                                      | 95.4 ms: 1.02x slower                                                       |
| regex_effbot            | 3.42 ms                                                      | 3.50 ms: 1.03x slower                                                       |
| create_gc_cycles        | 1.59 ms                                                      | 1.64 ms: 1.03x slower                                                       |
| python_startup          | 10.8 ms                                                      | 11.2 ms: 1.03x slower                                                       |
| sqlite_synth            | 2.49 us                                                      | 2.58 us: 1.03x slower                                                       |
| coroutines              | 27.9 ms                                                      | 29.1 ms: 1.04x slower                                                       |
| nbody                   | 95.8 ms                                                      | 101 ms: 1.06x slower                                                        |
| python_startup_no_site  | 7.78 ms                                                      | 8.25 ms: 1.06x slower                                                       |
| regex_dna               | 226 ms                                                       | 240 ms: 1.06x slower                                                        |
| generators              | 56.4 ms                                                      | 60.4 ms: 1.07x slower                                                       |
| coverage                | 66.6 ms                                                      | 86.0 ms: 1.29x slower                                                       |
| dask                    | 417 ms                                                       | 562 ms: 1.35x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.04x faster                                                                |

Benchmark hidden because not significant (10): scimark_fft, thrift, pycparser, pidigits, pathlib, crypto_pyaes, django_template, xml_etree_generate, sqlglot_parse, bench_mp_pool
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
