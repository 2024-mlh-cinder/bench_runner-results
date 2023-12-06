
# Results vs. 3.12.0

- fork: faster-cpython
- ref: nogil_latest
- machine: linux-x86_64
- commit hash: 1d39009
- commit date: 2023-04-16
- overall geometric mean: 1.06x slower \*
- HPT reliability: 99.94%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-linux-x86_64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 290 ms: 1.08x slower                                                    |
| docutils       | 2.70 sec                                               | 3.15 sec: 1.16x slower                                                  |
| Geometric mean | (ref)                                                  | 1.12x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-linux-x86_64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 65.9 ms: 1.23x faster                                                   |
| pidigits       | 187 ms                                                 | 186 ms: 1.00x faster                                                    |
| nbody          | 88.8 ms                                                | 107 ms: 1.21x slower                                                    |
| Geometric mean | (ref)                                                  | 1.01x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-linux-x86_64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_v8       | 22.3 ms                                                | 21.1 ms: 1.06x faster                                                   |
| regex_effbot   | 3.55 ms                                                | 3.46 ms: 1.03x faster                                                   |
| regex_dna      | 209 ms                                                 | 205 ms: 1.02x faster                                                    |
| regex_compile  | 144 ms                                                 | 152 ms: 1.06x slower                                                    |
| Geometric mean | (ref)                                                  | 1.01x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-linux-x86_64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| xml_etree_parse      | 154 ms                                                 | 137 ms: 1.12x faster                                                    |
| pickle_list          | 4.62 us                                                | 4.33 us: 1.07x faster                                                   |
| pickle_dict          | 31.6 us                                                | 30.0 us: 1.05x faster                                                   |
| pickle               | 10.6 us                                                | 10.3 us: 1.03x faster                                                   |
| xml_etree_generate   | 84.8 ms                                                | 83.7 ms: 1.01x faster                                                   |
| unpickle             | 15.0 us                                                | 15.5 us: 1.03x slower                                                   |
| pickle_pure_python   | 309 us                                                 | 321 us: 1.04x slower                                                    |
| xml_etree_process    | 58.6 ms                                                | 61.3 ms: 1.05x slower                                                   |
| unpickle_pure_python | 218 us                                                 | 229 us: 1.05x slower                                                    |
| unpickle_list        | 4.95 us                                                | 5.20 us: 1.05x slower                                                   |
| json_dumps           | 9.85 ms                                                | 10.4 ms: 1.05x slower                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 114 ms: 1.09x slower                                                    |
| json_loads           | 25.2 us                                                | 28.0 us: 1.11x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-linux-x86_64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.59 ms: 1.05x faster                                                   |
| python_startup         | 9.47 ms                                                | 9.18 ms: 1.03x faster                                                   |
| Geometric mean         | (ref)                                                  | 1.04x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-linux-x86_64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 13.2 ms: 1.24x slower                                                   |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230416-linux-x86_64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_io           | 1.16 sec                                               | 616 ms: 1.88x faster                                                    |
| async_tree_none         | 469 ms                                                 | 311 ms: 1.51x faster                                                    |
| async_tree_memoization  | 573 ms                                                 | 381 ms: 1.51x faster                                                    |
| async_tree_cpu_io_mixed | 714 ms                                                 | 534 ms: 1.34x faster                                                    |
| float                   | 80.7 ms                                                | 65.9 ms: 1.23x faster                                                   |
| async_generators        | 440 ms                                                 | 377 ms: 1.17x faster                                                    |
| xml_etree_parse         | 154 ms                                                 | 137 ms: 1.12x faster                                                    |
| pickle_list             | 4.62 us                                                | 4.33 us: 1.07x faster                                                   |
| regex_v8                | 22.3 ms                                                | 21.1 ms: 1.06x faster                                                   |
| pickle_dict             | 31.6 us                                                | 30.0 us: 1.05x faster                                                   |
| sqlite_synth            | 2.76 us                                                | 2.62 us: 1.05x faster                                                   |
| gc_traversal            | 3.84 ms                                                | 3.67 ms: 1.05x faster                                                   |
| python_startup_no_site  | 6.90 ms                                                | 6.59 ms: 1.05x faster                                                   |
| python_startup          | 9.47 ms                                                | 9.18 ms: 1.03x faster                                                   |
| pickle                  | 10.6 us                                                | 10.3 us: 1.03x faster                                                   |
| regex_effbot            | 3.55 ms                                                | 3.46 ms: 1.03x faster                                                   |
| regex_dna               | 209 ms                                                 | 205 ms: 1.02x faster                                                    |
| scimark_sor             | 125 ms                                                 | 123 ms: 1.02x faster                                                    |
| pathlib                 | 18.5 ms                                                | 18.2 ms: 1.01x faster                                                   |
| xml_etree_generate      | 84.8 ms                                                | 83.7 ms: 1.01x faster                                                   |
| bench_mp_pool           | 24.0 ms                                                | 23.8 ms: 1.01x faster                                                   |
| pidigits                | 187 ms                                                 | 186 ms: 1.00x faster                                                    |
| dulwich_log             | 67.9 ms                                                | 68.1 ms: 1.00x slower                                                   |
| unpickle                | 15.0 us                                                | 15.5 us: 1.03x slower                                                   |
| pickle_pure_python      | 309 us                                                 | 321 us: 1.04x slower                                                    |
| pprint_safe_repr        | 735 ms                                                 | 765 ms: 1.04x slower                                                    |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.94 ms: 1.04x slower                                                   |
| pyflate                 | 450 ms                                                 | 470 ms: 1.04x slower                                                    |
| create_gc_cycles        | 1.52 ms                                                | 1.59 ms: 1.04x slower                                                   |
| logging_silent          | 99.1 ns                                                | 104 ns: 1.05x slower                                                    |
| xml_etree_process       | 58.6 ms                                                | 61.3 ms: 1.05x slower                                                   |
| unpickle_pure_python    | 218 us                                                 | 229 us: 1.05x slower                                                    |
| unpickle_list           | 4.95 us                                                | 5.20 us: 1.05x slower                                                   |
| pprint_pformat          | 1.50 sec                                               | 1.58 sec: 1.05x slower                                                  |
| json_dumps              | 9.85 ms                                                | 10.4 ms: 1.05x slower                                                   |
| deepcopy                | 355 us                                                 | 375 us: 1.06x slower                                                    |
| spectral_norm           | 106 ms                                                 | 112 ms: 1.06x slower                                                    |
| regex_compile           | 144 ms                                                 | 152 ms: 1.06x slower                                                    |
| nqueens                 | 81.1 ms                                                | 85.8 ms: 1.06x slower                                                   |
| crypto_pyaes            | 77.2 ms                                                | 81.8 ms: 1.06x slower                                                   |
| json                    | 4.77 ms                                                | 5.06 ms: 1.06x slower                                                   |
| scimark_fft             | 358 ms                                                 | 383 ms: 1.07x slower                                                    |
| sqlglot_normalize       | 107 ms                                                 | 115 ms: 1.07x slower                                                    |
| sqlglot_optimize        | 53.3 ms                                                | 57.1 ms: 1.07x slower                                                   |
| deepcopy_memo           | 37.4 us                                                | 40.1 us: 1.07x slower                                                   |
| scimark_monte_carlo     | 71.0 ms                                                | 76.4 ms: 1.08x slower                                                   |
| go                      | 136 ms                                                 | 146 ms: 1.08x slower                                                    |
| 2to3                    | 268 ms                                                 | 290 ms: 1.08x slower                                                    |
| mdp                     | 2.57 sec                                               | 2.79 sec: 1.09x slower                                                  |
| deepcopy_reduce         | 3.14 us                                                | 3.42 us: 1.09x slower                                                   |
| xml_etree_iterparse     | 104 ms                                                 | 114 ms: 1.09x slower                                                    |
| logging_format          | 6.90 us                                                | 7.66 us: 1.11x slower                                                   |
| json_loads              | 25.2 us                                                | 28.0 us: 1.11x slower                                                   |
| deltablue               | 3.52 ms                                                | 3.91 ms: 1.11x slower                                                   |
| richards                | 43.2 ms                                                | 48.4 ms: 1.12x slower                                                   |
| scimark_lu              | 114 ms                                                 | 128 ms: 1.12x slower                                                    |
| fannkuch                | 387 ms                                                 | 436 ms: 1.13x slower                                                    |
| hexiom                  | 6.12 ms                                                | 6.89 ms: 1.13x slower                                                   |
| logging_simple          | 6.18 us                                                | 7.00 us: 1.13x slower                                                   |
| coverage                | 94.2 ms                                                | 109 ms: 1.16x slower                                                    |
| docutils                | 2.70 sec                                               | 3.15 sec: 1.16x slower                                                  |
| chaos                   | 63.5 ms                                                | 74.6 ms: 1.17x slower                                                   |
| raytrace                | 294 ms                                                 | 346 ms: 1.17x slower                                                    |
| meteor_contest          | 105 ms                                                 | 124 ms: 1.19x slower                                                    |
| coroutines              | 22.4 ms                                                | 26.8 ms: 1.19x slower                                                   |
| nbody                   | 88.8 ms                                                | 107 ms: 1.21x slower                                                    |
| mako                    | 10.7 ms                                                | 13.2 ms: 1.24x slower                                                   |
| sqlglot_transpile       | 1.64 ms                                                | 2.10 ms: 1.28x slower                                                   |
| comprehensions          | 20.4 us                                                | 26.3 us: 1.29x slower                                                   |
| unpack_sequence         | 44.8 ns                                                | 58.1 ns: 1.30x slower                                                   |
| mypy2                   | 344 ms                                                 | 457 ms: 1.33x slower                                                    |
| sqlglot_parse           | 1.32 ms                                                | 1.79 ms: 1.35x slower                                                   |
| bench_thread_pool       | 827 us                                                 | 1.64 ms: 1.99x slower                                                   |
| generators              | 31.1 ms                                                | 78.8 ms: 2.54x slower                                                   |
| Geometric mean          | (ref)                                                  | 1.06x slower                                                            |

Benchmark hidden because not significant (3): asyncio_tcp, pycparser, telco
Ignored benchmarks (8) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: asyncio_tcp_ssl, dask, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols
Ignored benchmarks (11) of results/bm-20230416-3.12.0a4-1d39009/bm-20230416-linux-x86_64-faster%2dcpython-nogil_latest-3.12.0a4-1d39009.json: chameleon, django_template, djangocms, genshi_text, genshi_xml, html5lib, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.94% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.01x
