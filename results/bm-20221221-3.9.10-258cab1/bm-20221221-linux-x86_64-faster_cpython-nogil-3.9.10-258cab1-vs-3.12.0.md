
# Results vs. 3.12.0

- fork: faster_cpython
- ref: nogil
- machine: linux-x86_64
- commit hash: 258cab1
- commit date: 2022-12-21
- overall geometric mean: 1.23x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221221-linux-x86_64-faster_cpython-nogil-3.9.10-258cab1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 382 ms: 1.43x slower                                         |
| docutils       | 2.70 sec                                               | 5.20 sec: 1.92x slower                                       |
| tornado_http   | 99.6 ms                                                | 124 ms: 1.25x slower                                         |
| Geometric mean | (ref)                                                  | 1.51x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221221-linux-x86_64-faster_cpython-nogil-3.9.10-258cab1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 186 ms: 1.00x faster                                         |
| float          | 80.7 ms                                                | 104 ms: 1.29x slower                                         |
| nbody          | 88.8 ms                                                | 172 ms: 1.94x slower                                         |
| Geometric mean | (ref)                                                  | 1.36x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221221-linux-x86_64-faster_cpython-nogil-3.9.10-258cab1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.35 ms: 1.06x faster                                        |
| regex_dna      | 209 ms                                                 | 218 ms: 1.04x slower                                         |
| regex_v8       | 22.3 ms                                                | 24.1 ms: 1.08x slower                                        |
| regex_compile  | 144 ms                                                 | 186 ms: 1.30x slower                                         |
| Geometric mean | (ref)                                                  | 1.08x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221221-linux-x86_64-faster_cpython-nogil-3.9.10-258cab1 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_dict          | 31.6 us                                                | 25.3 us: 1.25x faster                                        |
| pickle_list          | 4.62 us                                                | 4.17 us: 1.11x faster                                        |
| xml_etree_iterparse  | 104 ms                                                 | 95.5 ms: 1.09x faster                                        |
| pickle               | 10.6 us                                                | 10.0 us: 1.06x faster                                        |
| xml_etree_parse      | 154 ms                                                 | 149 ms: 1.03x faster                                         |
| xml_etree_generate   | 84.8 ms                                                | 87.8 ms: 1.04x slower                                        |
| pickle_pure_python   | 309 us                                                 | 346 us: 1.12x slower                                         |
| unpickle_list        | 4.95 us                                                | 5.80 us: 1.17x slower                                        |
| unpickle_pure_python | 218 us                                                 | 262 us: 1.20x slower                                         |
| xml_etree_process    | 58.6 ms                                                | 71.4 ms: 1.22x slower                                        |
| unpickle             | 15.0 us                                                | 18.6 us: 1.24x slower                                        |
| json_loads           | 25.2 us                                                | 32.5 us: 1.29x slower                                        |
| json_dumps           | 9.85 ms                                                | 13.4 ms: 1.36x slower                                        |
| Geometric mean       | (ref)                                                  | 1.08x slower                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221221-linux-x86_64-faster_cpython-nogil-3.9.10-258cab1 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 5.91 ms: 1.17x faster                                        |
| python_startup         | 9.47 ms                                                | 9.41 ms: 1.01x faster                                        |
| Geometric mean         | (ref)                                                  | 1.08x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221221-linux-x86_64-faster_cpython-nogil-3.9.10-258cab1 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 16.4 ms: 1.53x slower                                        |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221221-linux-x86_64-faster_cpython-nogil-3.9.10-258cab1 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_io           | 1.16 sec                                               | 829 ms: 1.40x faster                                         |
| async_tree_none         | 469 ms                                                 | 372 ms: 1.26x faster                                         |
| pickle_dict             | 31.6 us                                                | 25.3 us: 1.25x faster                                        |
| async_tree_memoization  | 573 ms                                                 | 460 ms: 1.25x faster                                         |
| python_startup_no_site  | 6.90 ms                                                | 5.91 ms: 1.17x faster                                        |
| async_tree_cpu_io_mixed | 714 ms                                                 | 614 ms: 1.16x faster                                         |
| pickle_list             | 4.62 us                                                | 4.17 us: 1.11x faster                                        |
| richards                | 43.2 ms                                                | 39.3 ms: 1.10x faster                                        |
| xml_etree_iterparse     | 104 ms                                                 | 95.5 ms: 1.09x faster                                        |
| pprint_pformat          | 1.50 sec                                               | 1.40 sec: 1.07x faster                                       |
| regex_effbot            | 3.55 ms                                                | 3.35 ms: 1.06x faster                                        |
| pickle                  | 10.6 us                                                | 10.0 us: 1.06x faster                                        |
| logging_silent          | 99.1 ns                                                | 96.0 ns: 1.03x faster                                        |
| xml_etree_parse         | 154 ms                                                 | 149 ms: 1.03x faster                                         |
| python_startup          | 9.47 ms                                                | 9.41 ms: 1.01x faster                                        |
| bench_mp_pool           | 24.0 ms                                                | 23.8 ms: 1.01x faster                                        |
| pidigits                | 187 ms                                                 | 186 ms: 1.00x faster                                         |
| xml_etree_generate      | 84.8 ms                                                | 87.8 ms: 1.04x slower                                        |
| telco                   | 6.87 ms                                                | 7.15 ms: 1.04x slower                                        |
| regex_dna               | 209 ms                                                 | 218 ms: 1.04x slower                                         |
| deepcopy_memo           | 37.4 us                                                | 40.1 us: 1.07x slower                                        |
| regex_v8                | 22.3 ms                                                | 24.1 ms: 1.08x slower                                        |
| deepcopy                | 355 us                                                 | 393 us: 1.11x slower                                         |
| pathlib                 | 18.5 ms                                                | 20.6 ms: 1.11x slower                                        |
| logging_format          | 6.90 us                                                | 7.69 us: 1.11x slower                                        |
| pickle_pure_python      | 309 us                                                 | 346 us: 1.12x slower                                         |
| logging_simple          | 6.18 us                                                | 6.95 us: 1.13x slower                                        |
| json                    | 4.77 ms                                                | 5.37 ms: 1.13x slower                                        |
| dulwich_log             | 67.9 ms                                                | 77.0 ms: 1.13x slower                                        |
| deepcopy_reduce         | 3.14 us                                                | 3.63 us: 1.16x slower                                        |
| scimark_sor             | 125 ms                                                 | 144 ms: 1.16x slower                                         |
| unpack_sequence         | 44.8 ns                                                | 52.4 ns: 1.17x slower                                        |
| unpickle_list           | 4.95 us                                                | 5.80 us: 1.17x slower                                        |
| sqlite_synth            | 2.76 us                                                | 3.24 us: 1.17x slower                                        |
| go                      | 136 ms                                                 | 159 ms: 1.18x slower                                         |
| pycparser               | 1.15 sec                                               | 1.35 sec: 1.18x slower                                       |
| scimark_fft             | 358 ms                                                 | 430 ms: 1.20x slower                                         |
| unpickle_pure_python    | 218 us                                                 | 262 us: 1.20x slower                                         |
| mdp                     | 2.57 sec                                               | 3.10 sec: 1.21x slower                                       |
| meteor_contest          | 105 ms                                                 | 127 ms: 1.21x slower                                         |
| xml_etree_process       | 58.6 ms                                                | 71.4 ms: 1.22x slower                                        |
| unpickle                | 15.0 us                                                | 18.6 us: 1.24x slower                                        |
| tornado_http            | 99.6 ms                                                | 124 ms: 1.25x slower                                         |
| hexiom                  | 6.12 ms                                                | 7.74 ms: 1.26x slower                                        |
| fannkuch                | 387 ms                                                 | 490 ms: 1.26x slower                                         |
| scimark_sparse_mat_mult | 4.74 ms                                                | 6.09 ms: 1.28x slower                                        |
| json_loads              | 25.2 us                                                | 32.5 us: 1.29x slower                                        |
| float                   | 80.7 ms                                                | 104 ms: 1.29x slower                                         |
| regex_compile           | 144 ms                                                 | 186 ms: 1.30x slower                                         |
| sqlglot_optimize        | 53.3 ms                                                | 69.3 ms: 1.30x slower                                        |
| scimark_lu              | 114 ms                                                 | 149 ms: 1.31x slower                                         |
| nqueens                 | 81.1 ms                                                | 109 ms: 1.34x slower                                         |
| spectral_norm           | 106 ms                                                 | 143 ms: 1.34x slower                                         |
| sqlglot_normalize       | 107 ms                                                 | 144 ms: 1.35x slower                                         |
| json_dumps              | 9.85 ms                                                | 13.4 ms: 1.36x slower                                        |
| pyflate                 | 450 ms                                                 | 636 ms: 1.41x slower                                         |
| raytrace                | 294 ms                                                 | 416 ms: 1.41x slower                                         |
| scimark_monte_carlo     | 71.0 ms                                                | 101 ms: 1.42x slower                                         |
| async_generators        | 440 ms                                                 | 626 ms: 1.42x slower                                         |
| 2to3                    | 268 ms                                                 | 382 ms: 1.43x slower                                         |
| bench_thread_pool       | 827 us                                                 | 1.19 ms: 1.43x slower                                        |
| mako                    | 10.7 ms                                                | 16.4 ms: 1.53x slower                                        |
| deltablue               | 3.52 ms                                                | 5.41 ms: 1.54x slower                                        |
| sqlglot_transpile       | 1.64 ms                                                | 2.55 ms: 1.56x slower                                        |
| crypto_pyaes            | 77.2 ms                                                | 122 ms: 1.58x slower                                         |
| chaos                   | 63.5 ms                                                | 102 ms: 1.60x slower                                         |
| sqlglot_parse           | 1.32 ms                                                | 2.18 ms: 1.65x slower                                        |
| docutils                | 2.70 sec                                               | 5.20 sec: 1.92x slower                                       |
| nbody                   | 88.8 ms                                                | 172 ms: 1.94x slower                                         |
| generators              | 31.1 ms                                                | 81.6 ms: 2.62x slower                                        |
| coroutines              | 22.4 ms                                                | 72.5 ms: 3.23x slower                                        |
| coverage                | 94.2 ms                                                | 553 ms: 5.87x slower                                         |
| Geometric mean          | (ref)                                                  | 1.23x slower                                                 |
Ignored benchmarks (13) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp, asyncio_tcp_ssl, comprehensions, create_gc_cycles, dask, gc_traversal, mypy2, pprint_safe_repr, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (16) of results/bm-20221221-3.9.10-258cab1/bm-20221221-linux-x86_64-faster_cpython-nogil-3.9.10-258cab1.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, mypy, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.18x
- 95% likely to have a slowdown of 1.16x
- 99% likely to have a slowdown of 1.13x
