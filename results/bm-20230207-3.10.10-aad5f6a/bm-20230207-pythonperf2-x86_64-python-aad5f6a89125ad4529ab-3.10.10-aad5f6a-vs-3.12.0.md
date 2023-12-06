
# Results vs. 3.12.0

- fork: python
- ref: aad5f6a89125ad4529ab
- machine: linux-x86_64
- commit hash: aad5f6a
- commit date: 2023-02-07
- overall geometric mean: 1.28x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 351 ms: 1.22x slower                                                       |
| docutils       | 2.89 sec                                                     | 3.45 sec: 1.19x slower                                                     |
| tornado_http   | 122 ms                                                       | 159 ms: 1.31x slower                                                       |
| Geometric mean | (ref)                                                        | 1.24x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 271 ms: 1.03x slower                                                       |
| float          | 78.5 ms                                                      | 111 ms: 1.41x slower                                                       |
| nbody          | 94.1 ms                                                      | 138 ms: 1.46x slower                                                       |
| Geometric mean | (ref)                                                        | 1.28x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.47 ms                                                      | 3.49 ms: 1.01x slower                                                      |
| regex_dna      | 241 ms                                                       | 260 ms: 1.08x slower                                                       |
| regex_v8       | 25.0 ms                                                      | 27.2 ms: 1.09x slower                                                      |
| regex_compile  | 146 ms                                                       | 192 ms: 1.32x slower                                                       |
| Geometric mean | (ref)                                                        | 1.12x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 13.7 us: 1.08x faster                                                      |
| pickle_list          | 4.39 us                                                      | 4.17 us: 1.05x faster                                                      |
| unpickle_list        | 4.77 us                                                      | 4.71 us: 1.01x faster                                                      |
| pickle               | 10.1 us                                                      | 10.1 us: 1.00x slower                                                      |
| pickle_dict          | 31.7 us                                                      | 32.1 us: 1.01x slower                                                      |
| xml_etree_generate   | 86.1 ms                                                      | 94.0 ms: 1.09x slower                                                      |
| xml_etree_iterparse  | 103 ms                                                       | 113 ms: 1.10x slower                                                       |
| xml_etree_parse      | 146 ms                                                       | 164 ms: 1.12x slower                                                       |
| json_loads           | 24.3 us                                                      | 30.0 us: 1.23x slower                                                      |
| xml_etree_process    | 58.3 ms                                                      | 77.5 ms: 1.33x slower                                                      |
| json_dumps           | 10.2 ms                                                      | 14.4 ms: 1.41x slower                                                      |
| pickle_pure_python   | 323 us                                                       | 461 us: 1.43x slower                                                       |
| unpickle_pure_python | 207 us                                                       | 320 us: 1.55x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.15x slower                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 7.34 ms: 1.18x faster                                                      |
| python_startup         | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                                      |
| Geometric mean         | (ref)                                                        | 1.10x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 14.7 ms: 1.48x slower                                                      |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf2-x86_64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a |
|-------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| coverage                | 89.6 ms                                                      | 63.3 ms: 1.42x faster                                                      |
| python_startup_no_site  | 8.70 ms                                                      | 7.34 ms: 1.18x faster                                                      |
| unpickle                | 14.8 us                                                      | 13.7 us: 1.08x faster                                                      |
| pickle_list             | 4.39 us                                                      | 4.17 us: 1.05x faster                                                      |
| python_startup          | 11.7 ms                                                      | 11.5 ms: 1.02x faster                                                      |
| unpickle_list           | 4.77 us                                                      | 4.71 us: 1.01x faster                                                      |
| pickle                  | 10.1 us                                                      | 10.1 us: 1.00x slower                                                      |
| regex_effbot            | 3.47 ms                                                      | 3.49 ms: 1.01x slower                                                      |
| pickle_dict             | 31.7 us                                                      | 32.1 us: 1.01x slower                                                      |
| pidigits                | 264 ms                                                       | 271 ms: 1.03x slower                                                       |
| telco                   | 6.96 ms                                                      | 7.25 ms: 1.04x slower                                                      |
| pathlib                 | 19.8 ms                                                      | 21.3 ms: 1.08x slower                                                      |
| regex_dna               | 241 ms                                                       | 260 ms: 1.08x slower                                                       |
| async_generators        | 385 ms                                                       | 417 ms: 1.08x slower                                                       |
| create_gc_cycles        | 1.67 ms                                                      | 1.81 ms: 1.08x slower                                                      |
| meteor_contest          | 128 ms                                                       | 139 ms: 1.09x slower                                                       |
| regex_v8                | 25.0 ms                                                      | 27.2 ms: 1.09x slower                                                      |
| xml_etree_generate      | 86.1 ms                                                      | 94.0 ms: 1.09x slower                                                      |
| xml_etree_iterparse     | 103 ms                                                       | 113 ms: 1.10x slower                                                       |
| sqlite_synth            | 2.70 us                                                      | 2.98 us: 1.10x slower                                                      |
| unpack_sequence         | 53.3 ns                                                      | 59.3 ns: 1.11x slower                                                      |
| xml_etree_parse         | 146 ms                                                       | 164 ms: 1.12x slower                                                       |
| bench_thread_pool       | 980 us                                                       | 1.11 ms: 1.13x slower                                                      |
| json                    | 5.14 ms                                                      | 5.91 ms: 1.15x slower                                                      |
| gc_traversal            | 3.54 ms                                                      | 4.12 ms: 1.16x slower                                                      |
| deepcopy_reduce         | 3.46 us                                                      | 4.05 us: 1.17x slower                                                      |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 5.28 ms: 1.19x slower                                                      |
| docutils                | 2.89 sec                                                     | 3.45 sec: 1.19x slower                                                     |
| sqlglot_optimize        | 57.8 ms                                                      | 69.6 ms: 1.20x slower                                                      |
| mdp                     | 2.53 sec                                                     | 3.05 sec: 1.20x slower                                                     |
| dask                    | 397 ms                                                       | 484 ms: 1.22x slower                                                       |
| 2to3                    | 287 ms                                                       | 351 ms: 1.22x slower                                                       |
| comprehensions          | 21.9 us                                                      | 27.0 us: 1.23x slower                                                      |
| json_loads              | 24.3 us                                                      | 30.0 us: 1.23x slower                                                      |
| dulwich_log             | 65.3 ms                                                      | 81.1 ms: 1.24x slower                                                      |
| deepcopy                | 376 us                                                       | 466 us: 1.24x slower                                                       |
| sqlglot_normalize       | 117 ms                                                       | 146 ms: 1.24x slower                                                       |
| pprint_safe_repr        | 823 ms                                                       | 1.03 sec: 1.25x slower                                                     |
| nqueens                 | 90.1 ms                                                      | 113 ms: 1.25x slower                                                       |
| scimark_fft             | 304 ms                                                       | 383 ms: 1.26x slower                                                       |
| pprint_pformat          | 1.67 sec                                                     | 2.11 sec: 1.26x slower                                                     |
| mypy2                   | 368 ms                                                       | 469 ms: 1.27x slower                                                       |
| coroutines              | 23.0 ms                                                      | 29.9 ms: 1.30x slower                                                      |
| tornado_http            | 122 ms                                                       | 159 ms: 1.31x slower                                                       |
| pycparser               | 1.27 sec                                                     | 1.67 sec: 1.31x slower                                                     |
| logging_format          | 7.37 us                                                      | 9.67 us: 1.31x slower                                                      |
| regex_compile           | 146 ms                                                       | 192 ms: 1.32x slower                                                       |
| xml_etree_process       | 58.3 ms                                                      | 77.5 ms: 1.33x slower                                                      |
| logging_simple          | 6.73 us                                                      | 8.96 us: 1.33x slower                                                      |
| deepcopy_memo           | 37.4 us                                                      | 50.0 us: 1.33x slower                                                      |
| fannkuch                | 350 ms                                                       | 470 ms: 1.34x slower                                                       |
| async_tree_cpu_io_mixed | 706 ms                                                       | 955 ms: 1.35x slower                                                       |
| bench_mp_pool           | 5.34 ms                                                      | 7.26 ms: 1.36x slower                                                      |
| json_dumps              | 10.2 ms                                                      | 14.4 ms: 1.41x slower                                                      |
| float                   | 78.5 ms                                                      | 111 ms: 1.41x slower                                                       |
| pickle_pure_python      | 323 us                                                       | 461 us: 1.43x slower                                                       |
| crypto_pyaes            | 80.9 ms                                                      | 118 ms: 1.46x slower                                                       |
| nbody                   | 94.1 ms                                                      | 138 ms: 1.46x slower                                                       |
| mako                    | 9.94 ms                                                      | 14.7 ms: 1.48x slower                                                      |
| sqlglot_transpile       | 1.80 ms                                                      | 2.70 ms: 1.50x slower                                                      |
| spectral_norm           | 91.6 ms                                                      | 138 ms: 1.50x slower                                                       |
| async_tree_memoization  | 553 ms                                                       | 832 ms: 1.50x slower                                                       |
| scimark_monte_carlo     | 72.4 ms                                                      | 110 ms: 1.52x slower                                                       |
| async_tree_io           | 1.06 sec                                                     | 1.62 sec: 1.53x slower                                                     |
| unpickle_pure_python    | 207 us                                                       | 320 us: 1.55x slower                                                       |
| async_tree_none         | 459 ms                                                       | 711 ms: 1.55x slower                                                       |
| pyflate                 | 447 ms                                                       | 696 ms: 1.55x slower                                                       |
| generators              | 36.7 ms                                                      | 57.0 ms: 1.55x slower                                                      |
| hexiom                  | 5.96 ms                                                      | 9.49 ms: 1.59x slower                                                      |
| sqlglot_parse           | 1.40 ms                                                      | 2.25 ms: 1.60x slower                                                      |
| scimark_sor             | 110 ms                                                       | 177 ms: 1.61x slower                                                       |
| richards                | 45.0 ms                                                      | 72.9 ms: 1.62x slower                                                      |
| raytrace                | 302 ms                                                       | 495 ms: 1.64x slower                                                       |
| scimark_lu              | 101 ms                                                       | 170 ms: 1.69x slower                                                       |
| go                      | 150 ms                                                       | 260 ms: 1.73x slower                                                       |
| logging_silent          | 95.6 ns                                                      | 165 ns: 1.73x slower                                                       |
| chaos                   | 62.9 ms                                                      | 109 ms: 1.73x slower                                                       |
| asyncio_tcp             | 381 ms                                                       | 779 ms: 2.04x slower                                                       |
| deltablue               | 3.29 ms                                                      | 7.45 ms: 2.27x slower                                                      |
| Geometric mean          | (ref)                                                        | 1.28x slower                                                               |
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (16) of results/bm-20230207-3.10.10-aad5f6a/bm-20230207-pythonperf2-x86_64-python-aad5f6a89125ad4529ab-3.10.10-aad5f6a.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.24x
- 95% likely to have a slowdown of 1.24x
- 99% likely to have a slowdown of 1.23x
