
# Results vs. 3.10.4

- fork: python
- ref: 3c67ec394faac79d2608
- machine: linux-x86_64
- commit hash: 3c67ec3
- commit date: 2023-02-07
- overall geometric mean: 1.27x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 282 ms: 1.24x faster                                                        |
| chameleon      | 9.88 ms                                                      | 7.46 ms: 1.32x faster                                                       |
| docutils       | 3.42 sec                                                     | 2.78 sec: 1.23x faster                                                      |
| html5lib       | 94.7 ms                                                      | 65.3 ms: 1.45x faster                                                       |
| tornado_http   | 157 ms                                                       | 117 ms: 1.34x faster                                                        |
| Geometric mean | (ref)                                                        | 1.31x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 503 ms: 1.39x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.38x faster                                                      |
| async_tree_memoization  | 827 ms                                                       | 601 ms: 1.38x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 737 ms: 1.28x faster                                                        |
| Geometric mean          | (ref)                                                        | 1.36x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 109 ms                                                       | 71.9 ms: 1.51x faster                                                       |
| nbody          | 134 ms                                                       | 101 ms: 1.33x faster                                                        |
| pidigits       | 270 ms                                                       | 251 ms: 1.08x faster                                                        |
| Geometric mean | (ref)                                                        | 1.29x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 145 ms: 1.33x faster                                                        |
| regex_v8       | 27.1 ms                                                      | 22.7 ms: 1.19x faster                                                       |
| regex_dna      | 260 ms                                                       | 240 ms: 1.08x faster                                                        |
| regex_effbot   | 3.10 ms                                                      | 3.50 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                        | 1.11x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 204 us: 1.54x faster                                                        |
| pickle_pure_python   | 453 us                                                       | 312 us: 1.45x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 10.0 ms: 1.42x faster                                                       |
| xml_etree_process    | 76.4 ms                                                      | 55.6 ms: 1.37x faster                                                       |
| json_loads           | 30.0 us                                                      | 23.8 us: 1.26x faster                                                       |
| xml_etree_generate   | 93.1 ms                                                      | 80.6 ms: 1.16x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 142 ms: 1.12x faster                                                        |
| pickle_list          | 4.23 us                                                      | 3.84 us: 1.10x faster                                                       |
| unpickle             | 13.9 us                                                      | 12.8 us: 1.09x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 103 ms: 1.07x faster                                                        |
| pickle               | 10.1 us                                                      | 9.88 us: 1.02x faster                                                       |
| unpickle_list        | 4.45 us                                                      | 4.50 us: 1.01x slower                                                       |
| pickle_dict          | 30.4 us                                                      | 31.6 us: 1.04x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.18x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.2 ms: 1.03x faster                                                       |
| python_startup_no_site | 7.35 ms                                                      | 8.25 ms: 1.12x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.3 ms: 1.44x faster                                                       |
| genshi_text     | 32.3 ms                                                      | 24.6 ms: 1.31x faster                                                       |
| django_template | 51.8 ms                                                      | 40.5 ms: 1.28x faster                                                       |
| genshi_xml      | 64.1 ms                                                      | 53.4 ms: 1.20x faster                                                       |
| Geometric mean  | (ref)                                                        | 1.30x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf2-x86_64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| deltablue               | 7.43 ms                                                      | 3.60 ms: 2.07x faster                                                       |
| asyncio_tcp             | 785 ms                                                       | 388 ms: 2.02x faster                                                        |
| scimark_sor             | 183 ms                                                       | 105 ms: 1.75x faster                                                        |
| logging_silent          | 168 ns                                                       | 96.5 ns: 1.74x faster                                                       |
| go                      | 258 ms                                                       | 152 ms: 1.69x faster                                                        |
| raytrace                | 497 ms                                                       | 301 ms: 1.65x faster                                                        |
| richards                | 76.3 ms                                                      | 46.1 ms: 1.65x faster                                                       |
| pyflate                 | 698 ms                                                       | 428 ms: 1.63x faster                                                        |
| scimark_lu              | 165 ms                                                       | 104 ms: 1.58x faster                                                        |
| scimark_monte_carlo     | 109 ms                                                       | 70.2 ms: 1.56x faster                                                       |
| unpickle_pure_python    | 315 us                                                       | 204 us: 1.54x faster                                                        |
| chaos                   | 106 ms                                                       | 69.6 ms: 1.52x faster                                                       |
| float                   | 109 ms                                                       | 71.9 ms: 1.51x faster                                                       |
| spectral_norm           | 141 ms                                                       | 95.4 ms: 1.48x faster                                                       |
| sqlglot_parse           | 2.27 ms                                                      | 1.56 ms: 1.46x faster                                                       |
| hexiom                  | 9.46 ms                                                      | 6.49 ms: 1.46x faster                                                       |
| html5lib                | 94.7 ms                                                      | 65.3 ms: 1.45x faster                                                       |
| pickle_pure_python      | 453 us                                                       | 312 us: 1.45x faster                                                        |
| bench_mp_pool           | 6.82 ms                                                      | 4.71 ms: 1.45x faster                                                       |
| scimark_sparse_mat_mult | 5.21 ms                                                      | 3.61 ms: 1.45x faster                                                       |
| crypto_pyaes            | 118 ms                                                       | 81.8 ms: 1.44x faster                                                       |
| mako                    | 14.7 ms                                                      | 10.3 ms: 1.44x faster                                                       |
| json_dumps              | 14.2 ms                                                      | 10.0 ms: 1.42x faster                                                       |
| sqlglot_transpile       | 2.73 ms                                                      | 1.93 ms: 1.42x faster                                                       |
| deepcopy_memo           | 50.5 us                                                      | 35.8 us: 1.41x faster                                                       |
| pprint_pformat          | 2.15 sec                                                     | 1.53 sec: 1.40x faster                                                      |
| pprint_safe_repr        | 1.04 sec                                                     | 744 ms: 1.40x faster                                                        |
| unpack_sequence         | 60.3 ns                                                      | 43.3 ns: 1.39x faster                                                       |
| async_tree_none         | 700 ms                                                       | 503 ms: 1.39x faster                                                        |
| async_tree_io           | 1.61 sec                                                     | 1.17 sec: 1.38x faster                                                      |
| async_tree_memoization  | 827 ms                                                       | 601 ms: 1.38x faster                                                        |
| xml_etree_process       | 76.4 ms                                                      | 55.6 ms: 1.37x faster                                                       |
| logging_simple          | 9.06 us                                                      | 6.67 us: 1.36x faster                                                       |
| tornado_http            | 157 ms                                                       | 117 ms: 1.34x faster                                                        |
| regex_compile           | 192 ms                                                       | 145 ms: 1.33x faster                                                        |
| nbody                   | 134 ms                                                       | 101 ms: 1.33x faster                                                        |
| chameleon               | 9.88 ms                                                      | 7.46 ms: 1.32x faster                                                       |
| logging_format          | 9.82 us                                                      | 7.43 us: 1.32x faster                                                       |
| genshi_text             | 32.3 ms                                                      | 24.6 ms: 1.31x faster                                                       |
| scimark_fft             | 363 ms                                                       | 278 ms: 1.30x faster                                                        |
| pycparser               | 1.65 sec                                                     | 1.28 sec: 1.29x faster                                                      |
| async_generators        | 418 ms                                                       | 325 ms: 1.29x faster                                                        |
| async_tree_cpu_io_mixed | 946 ms                                                       | 737 ms: 1.28x faster                                                        |
| thrift                  | 1.20 ms                                                      | 935 us: 1.28x faster                                                        |
| django_template         | 51.8 ms                                                      | 40.5 ms: 1.28x faster                                                       |
| comprehensions          | 27.0 us                                                      | 21.3 us: 1.27x faster                                                       |
| json_loads              | 30.0 us                                                      | 23.8 us: 1.26x faster                                                       |
| 2to3                    | 349 ms                                                       | 282 ms: 1.24x faster                                                        |
| mypy2                   | 467 ms                                                       | 379 ms: 1.23x faster                                                        |
| docutils                | 3.42 sec                                                     | 2.78 sec: 1.23x faster                                                      |
| sqlglot_normalize       | 146 ms                                                       | 120 ms: 1.22x faster                                                        |
| deepcopy_reduce         | 4.00 us                                                      | 3.30 us: 1.21x faster                                                       |
| sqlglot_optimize        | 69.9 ms                                                      | 57.7 ms: 1.21x faster                                                       |
| dulwich_log             | 80.0 ms                                                      | 66.6 ms: 1.20x faster                                                       |
| genshi_xml              | 64.1 ms                                                      | 53.4 ms: 1.20x faster                                                       |
| deepcopy                | 459 us                                                       | 383 us: 1.20x faster                                                        |
| json                    | 5.91 ms                                                      | 4.94 ms: 1.20x faster                                                       |
| fannkuch                | 488 ms                                                       | 409 ms: 1.19x faster                                                        |
| regex_v8                | 27.1 ms                                                      | 22.7 ms: 1.19x faster                                                       |
| nqueens                 | 112 ms                                                       | 94.2 ms: 1.19x faster                                                       |
| bench_thread_pool       | 1.13 ms                                                      | 971 us: 1.17x faster                                                        |
| sympy_integrate         | 28.3 ms                                                      | 24.3 ms: 1.17x faster                                                       |
| xml_etree_generate      | 93.1 ms                                                      | 80.6 ms: 1.16x faster                                                       |
| sqlite_synth            | 2.97 us                                                      | 2.58 us: 1.15x faster                                                       |
| sympy_str               | 359 ms                                                       | 313 ms: 1.15x faster                                                        |
| sympy_expand            | 599 ms                                                       | 526 ms: 1.14x faster                                                        |
| sympy_sum               | 194 ms                                                       | 172 ms: 1.12x faster                                                        |
| xml_etree_parse         | 159 ms                                                       | 142 ms: 1.12x faster                                                        |
| pathlib                 | 21.2 ms                                                      | 19.1 ms: 1.11x faster                                                       |
| mdp                     | 2.94 sec                                                     | 2.66 sec: 1.10x faster                                                      |
| pickle_list             | 4.23 us                                                      | 3.84 us: 1.10x faster                                                       |
| telco                   | 7.21 ms                                                      | 6.59 ms: 1.10x faster                                                       |
| create_gc_cycles        | 1.79 ms                                                      | 1.64 ms: 1.09x faster                                                       |
| unpickle                | 13.9 us                                                      | 12.8 us: 1.09x faster                                                       |
| regex_dna               | 260 ms                                                       | 240 ms: 1.08x faster                                                        |
| pidigits                | 270 ms                                                       | 251 ms: 1.08x faster                                                        |
| meteor_contest          | 138 ms                                                       | 128 ms: 1.07x faster                                                        |
| xml_etree_iterparse     | 110 ms                                                       | 103 ms: 1.07x faster                                                        |
| coroutines              | 30.9 ms                                                      | 29.1 ms: 1.06x faster                                                       |
| python_startup          | 11.5 ms                                                      | 11.2 ms: 1.03x faster                                                       |
| gc_traversal            | 3.63 ms                                                      | 3.55 ms: 1.02x faster                                                       |
| pickle                  | 10.1 us                                                      | 9.88 us: 1.02x faster                                                       |
| unpickle_list           | 4.45 us                                                      | 4.50 us: 1.01x slower                                                       |
| pickle_dict             | 30.4 us                                                      | 31.6 us: 1.04x slower                                                       |
| generators              | 57.7 ms                                                      | 60.4 ms: 1.05x slower                                                       |
| python_startup_no_site  | 7.35 ms                                                      | 8.25 ms: 1.12x slower                                                       |
| regex_effbot            | 3.10 ms                                                      | 3.50 ms: 1.13x slower                                                       |
| dask                    | 469 ms                                                       | 562 ms: 1.20x slower                                                        |
| coverage                | 65.9 ms                                                      | 86.0 ms: 1.30x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.27x faster                                                                |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.20x
