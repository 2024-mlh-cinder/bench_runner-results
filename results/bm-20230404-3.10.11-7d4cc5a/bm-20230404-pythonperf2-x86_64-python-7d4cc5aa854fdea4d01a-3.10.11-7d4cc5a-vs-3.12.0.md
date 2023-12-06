
# Results vs. 3.12.0

- fork: python
- ref: 7d4cc5aa854fdea4d01a
- machine: linux-x86_64
- commit hash: 7d4cc5a
- commit date: 2023-04-04
- overall geometric mean: 1.27x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf2-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 350 ms: 1.22x slower                                                       |
| docutils       | 2.89 sec                                                     | 3.42 sec: 1.19x slower                                                     |
| tornado_http   | 122 ms                                                       | 150 ms: 1.24x slower                                                       |
| Geometric mean | (ref)                                                        | 1.21x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf2-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 271 ms: 1.03x slower                                                       |
| float          | 78.5 ms                                                      | 110 ms: 1.40x slower                                                       |
| nbody          | 94.1 ms                                                      | 137 ms: 1.46x slower                                                       |
| Geometric mean | (ref)                                                        | 1.28x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf2-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.47 ms                                                      | 3.25 ms: 1.07x faster                                                      |
| regex_dna      | 241 ms                                                       | 259 ms: 1.07x slower                                                       |
| regex_v8       | 25.0 ms                                                      | 27.1 ms: 1.08x slower                                                      |
| regex_compile  | 146 ms                                                       | 191 ms: 1.31x slower                                                       |
| Geometric mean | (ref)                                                        | 1.09x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf2-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.04 us: 1.09x faster                                                      |
| unpickle             | 14.8 us                                                      | 14.1 us: 1.05x faster                                                      |
| unpickle_list        | 4.77 us                                                      | 4.61 us: 1.03x faster                                                      |
| pickle_dict          | 31.7 us                                                      | 31.1 us: 1.02x faster                                                      |
| pickle               | 10.1 us                                                      | 10.1 us: 1.00x slower                                                      |
| xml_etree_iterparse  | 103 ms                                                       | 109 ms: 1.06x slower                                                       |
| xml_etree_generate   | 86.1 ms                                                      | 92.8 ms: 1.08x slower                                                      |
| xml_etree_parse      | 146 ms                                                       | 160 ms: 1.09x slower                                                       |
| json_loads           | 24.3 us                                                      | 30.2 us: 1.24x slower                                                      |
| xml_etree_process    | 58.3 ms                                                      | 76.5 ms: 1.31x slower                                                      |
| pickle_pure_python   | 323 us                                                       | 454 us: 1.41x slower                                                       |
| json_dumps           | 10.2 ms                                                      | 14.4 ms: 1.41x slower                                                      |
| unpickle_pure_python | 207 us                                                       | 313 us: 1.52x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.13x slower                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf2-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 7.35 ms: 1.18x faster                                                      |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.01x faster                                                      |
| Geometric mean         | (ref)                                                        | 1.10x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf2-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 14.9 ms: 1.50x slower                                                      |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230404-pythonperf2-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a |
|-------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| coverage                | 89.6 ms                                                      | 63.5 ms: 1.41x faster                                                      |
| python_startup_no_site  | 8.70 ms                                                      | 7.35 ms: 1.18x faster                                                      |
| pickle_list             | 4.39 us                                                      | 4.04 us: 1.09x faster                                                      |
| regex_effbot            | 3.47 ms                                                      | 3.25 ms: 1.07x faster                                                      |
| unpickle                | 14.8 us                                                      | 14.1 us: 1.05x faster                                                      |
| unpickle_list           | 4.77 us                                                      | 4.61 us: 1.03x faster                                                      |
| pickle_dict             | 31.7 us                                                      | 31.1 us: 1.02x faster                                                      |
| python_startup          | 11.7 ms                                                      | 11.5 ms: 1.01x faster                                                      |
| pickle                  | 10.1 us                                                      | 10.1 us: 1.00x slower                                                      |
| telco                   | 6.96 ms                                                      | 7.16 ms: 1.03x slower                                                      |
| pidigits                | 264 ms                                                       | 271 ms: 1.03x slower                                                       |
| gc_traversal            | 3.54 ms                                                      | 3.68 ms: 1.04x slower                                                      |
| xml_etree_iterparse     | 103 ms                                                       | 109 ms: 1.06x slower                                                       |
| pathlib                 | 19.8 ms                                                      | 21.0 ms: 1.06x slower                                                      |
| regex_dna               | 241 ms                                                       | 259 ms: 1.07x slower                                                       |
| xml_etree_generate      | 86.1 ms                                                      | 92.8 ms: 1.08x slower                                                      |
| meteor_contest          | 128 ms                                                       | 139 ms: 1.08x slower                                                       |
| async_generators        | 385 ms                                                       | 418 ms: 1.08x slower                                                       |
| regex_v8                | 25.0 ms                                                      | 27.1 ms: 1.08x slower                                                      |
| create_gc_cycles        | 1.67 ms                                                      | 1.82 ms: 1.09x slower                                                      |
| xml_etree_parse         | 146 ms                                                       | 160 ms: 1.09x slower                                                       |
| sqlite_synth            | 2.70 us                                                      | 2.97 us: 1.10x slower                                                      |
| unpack_sequence         | 53.3 ns                                                      | 59.4 ns: 1.12x slower                                                      |
| bench_thread_pool       | 980 us                                                       | 1.10 ms: 1.13x slower                                                      |
| deepcopy_reduce         | 3.46 us                                                      | 3.99 us: 1.15x slower                                                      |
| dask                    | 397 ms                                                       | 459 ms: 1.16x slower                                                       |
| json                    | 5.14 ms                                                      | 5.97 ms: 1.16x slower                                                      |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 5.22 ms: 1.18x slower                                                      |
| scimark_fft             | 304 ms                                                       | 360 ms: 1.18x slower                                                       |
| docutils                | 2.89 sec                                                     | 3.42 sec: 1.19x slower                                                     |
| sqlglot_optimize        | 57.8 ms                                                      | 69.1 ms: 1.19x slower                                                      |
| 2to3                    | 287 ms                                                       | 350 ms: 1.22x slower                                                       |
| dulwich_log             | 65.3 ms                                                      | 80.1 ms: 1.23x slower                                                      |
| mdp                     | 2.53 sec                                                     | 3.12 sec: 1.23x slower                                                     |
| sqlglot_normalize       | 117 ms                                                       | 144 ms: 1.23x slower                                                       |
| tornado_http            | 122 ms                                                       | 150 ms: 1.24x slower                                                       |
| comprehensions          | 21.9 us                                                      | 27.1 us: 1.24x slower                                                      |
| deepcopy                | 376 us                                                       | 465 us: 1.24x slower                                                       |
| json_loads              | 24.3 us                                                      | 30.2 us: 1.24x slower                                                      |
| nqueens                 | 90.1 ms                                                      | 112 ms: 1.25x slower                                                       |
| pprint_safe_repr        | 823 ms                                                       | 1.03 sec: 1.26x slower                                                     |
| pycparser               | 1.27 sec                                                     | 1.61 sec: 1.26x slower                                                     |
| mypy2                   | 368 ms                                                       | 470 ms: 1.28x slower                                                       |
| bench_mp_pool           | 5.34 ms                                                      | 6.82 ms: 1.28x slower                                                      |
| pprint_pformat          | 1.67 sec                                                     | 2.14 sec: 1.28x slower                                                     |
| logging_format          | 7.37 us                                                      | 9.57 us: 1.30x slower                                                      |
| xml_etree_process       | 58.3 ms                                                      | 76.5 ms: 1.31x slower                                                      |
| coroutines              | 23.0 ms                                                      | 30.2 ms: 1.31x slower                                                      |
| regex_compile           | 146 ms                                                       | 191 ms: 1.31x slower                                                       |
| logging_simple          | 6.73 us                                                      | 8.94 us: 1.33x slower                                                      |
| async_tree_cpu_io_mixed | 706 ms                                                       | 952 ms: 1.35x slower                                                       |
| fannkuch                | 350 ms                                                       | 477 ms: 1.36x slower                                                       |
| deepcopy_memo           | 37.4 us                                                      | 51.1 us: 1.37x slower                                                      |
| float                   | 78.5 ms                                                      | 110 ms: 1.40x slower                                                       |
| pickle_pure_python      | 323 us                                                       | 454 us: 1.41x slower                                                       |
| json_dumps              | 10.2 ms                                                      | 14.4 ms: 1.41x slower                                                      |
| crypto_pyaes            | 80.9 ms                                                      | 115 ms: 1.42x slower                                                       |
| nbody                   | 94.1 ms                                                      | 137 ms: 1.46x slower                                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 2.69 ms: 1.49x slower                                                      |
| spectral_norm           | 91.6 ms                                                      | 137 ms: 1.49x slower                                                       |
| async_tree_memoization  | 553 ms                                                       | 827 ms: 1.49x slower                                                       |
| mako                    | 9.94 ms                                                      | 14.9 ms: 1.50x slower                                                      |
| async_tree_none         | 459 ms                                                       | 695 ms: 1.52x slower                                                       |
| unpickle_pure_python    | 207 us                                                       | 313 us: 1.52x slower                                                       |
| async_tree_io           | 1.06 sec                                                     | 1.61 sec: 1.52x slower                                                     |
| scimark_monte_carlo     | 72.4 ms                                                      | 110 ms: 1.53x slower                                                       |
| pyflate                 | 447 ms                                                       | 693 ms: 1.55x slower                                                       |
| generators              | 36.7 ms                                                      | 57.8 ms: 1.58x slower                                                      |
| hexiom                  | 5.96 ms                                                      | 9.43 ms: 1.58x slower                                                      |
| scimark_lu              | 101 ms                                                       | 161 ms: 1.60x slower                                                       |
| scimark_sor             | 110 ms                                                       | 176 ms: 1.60x slower                                                       |
| sqlglot_parse           | 1.40 ms                                                      | 2.26 ms: 1.61x slower                                                      |
| raytrace                | 302 ms                                                       | 491 ms: 1.63x slower                                                       |
| richards                | 45.0 ms                                                      | 74.5 ms: 1.66x slower                                                      |
| chaos                   | 62.9 ms                                                      | 105 ms: 1.67x slower                                                       |
| logging_silent          | 95.6 ns                                                      | 166 ns: 1.73x slower                                                       |
| go                      | 150 ms                                                       | 264 ms: 1.76x slower                                                       |
| asyncio_tcp             | 381 ms                                                       | 781 ms: 2.05x slower                                                       |
| deltablue               | 3.29 ms                                                      | 7.44 ms: 2.26x slower                                                      |
| Geometric mean          | (ref)                                                        | 1.27x slower                                                               |
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (16) of results/bm-20230404-3.10.11-7d4cc5a/bm-20230404-pythonperf2-x86_64-python-7d4cc5aa854fdea4d01a-3.10.11-7d4cc5a.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.23x
- 95% likely to have a slowdown of 1.23x
- 99% likely to have a slowdown of 1.22x
