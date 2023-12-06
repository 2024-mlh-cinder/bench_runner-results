
# Results vs. 3.12.0

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: linux-x86_64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.02x slower
- HPT reliability: 99.81%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 298 ms: 1.05x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.36 ms: 1.01x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                       |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 459 ms                                                       | 434 ms: 1.06x faster                                                         |
| async_tree_none_tg         | 440 ms                                                       | 443 ms: 1.01x slower                                                         |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 717 ms: 1.01x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                                       |
| Geometric mean             | (ref)                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (3): async_tree_memoization, async_tree_cpu_io_mixed, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 78.7 ms: 1.04x faster                                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                 |

Benchmark hidden because not significant (2): pidigits, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                                        |
| regex_dna      | 240 ms                                                       | 241 ms: 1.00x slower                                                         |
| regex_compile  | 145 ms                                                       | 147 ms: 1.02x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 25.5 ms: 1.05x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 14.1 us: 1.09x faster                                                        |
| xml_etree_parse      | 147 ms                                                       | 143 ms: 1.03x faster                                                         |
| pickle_pure_python   | 319 us                                                       | 314 us: 1.02x faster                                                         |
| unpickle_list        | 4.65 us                                                      | 4.59 us: 1.01x faster                                                        |
| pickle_dict          | 32.0 us                                                      | 32.2 us: 1.01x slower                                                        |
| xml_etree_generate   | 85.3 ms                                                      | 86.1 ms: 1.01x slower                                                        |
| json_loads           | 24.3 us                                                      | 24.5 us: 1.01x slower                                                        |
| pickle               | 10.0 us                                                      | 10.2 us: 1.02x slower                                                        |
| tomli_loads          | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                                         |
| pickle_list          | 4.22 us                                                      | 4.34 us: 1.03x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 229 us: 1.09x slower                                                         |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                 |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.20x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                      | 10.3 ms: 1.02x slower                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231030-pythonperf2-x86_64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions             | 21.8 us                                                      | 16.7 us: 1.31x faster                                                        |
| crypto_pyaes               | 82.4 ms                                                      | 72.4 ms: 1.14x faster                                                        |
| raytrace                   | 301 ms                                                       | 275 ms: 1.09x faster                                                         |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.12 ms: 1.09x faster                                                        |
| unpickle                   | 15.3 us                                                      | 14.1 us: 1.09x faster                                                        |
| bench_mp_pool              | 4.96 ms                                                      | 4.66 ms: 1.06x faster                                                        |
| sympy_sum                  | 163 ms                                                       | 153 ms: 1.06x faster                                                         |
| async_tree_none            | 459 ms                                                       | 434 ms: 1.06x faster                                                         |
| unpack_sequence            | 54.5 ns                                                      | 51.7 ns: 1.05x faster                                                        |
| gc_traversal               | 3.70 ms                                                      | 3.52 ms: 1.05x faster                                                        |
| sympy_str                  | 305 ms                                                       | 294 ms: 1.04x faster                                                         |
| float                      | 81.6 ms                                                      | 78.7 ms: 1.04x faster                                                        |
| generators                 | 37.3 ms                                                      | 36.0 ms: 1.04x faster                                                        |
| chaos                      | 64.1 ms                                                      | 62.2 ms: 1.03x faster                                                        |
| xml_etree_parse            | 147 ms                                                       | 143 ms: 1.03x faster                                                         |
| deepcopy_reduce            | 3.41 us                                                      | 3.32 us: 1.03x faster                                                        |
| asyncio_tcp                | 380 ms                                                       | 370 ms: 1.03x faster                                                         |
| regex_effbot               | 3.61 ms                                                      | 3.53 ms: 1.02x faster                                                        |
| sqlite_synth               | 2.72 us                                                      | 2.66 us: 1.02x faster                                                        |
| sympy_integrate            | 24.0 ms                                                      | 23.6 ms: 1.02x faster                                                        |
| spectral_norm              | 93.9 ms                                                      | 92.3 ms: 1.02x faster                                                        |
| pickle_pure_python         | 319 us                                                       | 314 us: 1.02x faster                                                         |
| sqlglot_normalize          | 119 ms                                                       | 117 ms: 1.02x faster                                                         |
| unpickle_list              | 4.65 us                                                      | 4.59 us: 1.01x faster                                                        |
| mdp                        | 2.56 sec                                                     | 2.53 sec: 1.01x faster                                                       |
| coroutines                 | 23.1 ms                                                      | 22.8 ms: 1.01x faster                                                        |
| scimark_monte_carlo        | 69.5 ms                                                      | 68.9 ms: 1.01x faster                                                        |
| deepcopy                   | 371 us                                                       | 369 us: 1.01x faster                                                         |
| docutils                   | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                       |
| regex_dna                  | 240 ms                                                       | 241 ms: 1.00x slower                                                         |
| sympy_expand               | 492 ms                                                       | 494 ms: 1.00x slower                                                         |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 1.58 sec: 1.01x slower                                                       |
| async_tree_none_tg         | 440 ms                                                       | 443 ms: 1.01x slower                                                         |
| nqueens                    | 90.1 ms                                                      | 90.7 ms: 1.01x slower                                                        |
| pickle_dict                | 32.0 us                                                      | 32.2 us: 1.01x slower                                                        |
| xml_etree_generate         | 85.3 ms                                                      | 86.1 ms: 1.01x slower                                                        |
| json_loads                 | 24.3 us                                                      | 24.5 us: 1.01x slower                                                        |
| mypy2                      | 365 ms                                                       | 369 ms: 1.01x slower                                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 59.0 ms: 1.01x slower                                                        |
| chameleon                  | 7.27 ms                                                      | 7.36 ms: 1.01x slower                                                        |
| sqlglot_parse              | 1.41 ms                                                      | 1.43 ms: 1.01x slower                                                        |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 717 ms: 1.01x slower                                                         |
| sqlglot_transpile          | 1.80 ms                                                      | 1.83 ms: 1.02x slower                                                        |
| pickle                     | 10.0 us                                                      | 10.2 us: 1.02x slower                                                        |
| regex_compile              | 145 ms                                                       | 147 ms: 1.02x slower                                                         |
| tomli_loads                | 2.17 sec                                                     | 2.21 sec: 1.02x slower                                                       |
| typing_runtime_protocols   | 150 us                                                       | 154 us: 1.02x slower                                                         |
| mako                       | 10.1 ms                                                      | 10.3 ms: 1.02x slower                                                        |
| xml_etree_iterparse        | 104 ms                                                       | 106 ms: 1.02x slower                                                         |
| async_tree_io              | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                       |
| pprint_safe_repr           | 808 ms                                                       | 829 ms: 1.03x slower                                                         |
| meteor_contest             | 126 ms                                                       | 130 ms: 1.03x slower                                                         |
| async_tree_io_tg           | 1.07 sec                                                     | 1.10 sec: 1.03x slower                                                       |
| pickle_list                | 4.22 us                                                      | 4.34 us: 1.03x slower                                                        |
| pprint_pformat             | 1.64 sec                                                     | 1.70 sec: 1.03x slower                                                       |
| json_dumps                 | 10.3 ms                                                      | 10.6 ms: 1.03x slower                                                        |
| logging_format             | 7.29 us                                                      | 7.53 us: 1.03x slower                                                        |
| logging_simple             | 6.64 us                                                      | 6.88 us: 1.04x slower                                                        |
| async_generators           | 385 ms                                                       | 400 ms: 1.04x slower                                                         |
| pathlib                    | 18.7 ms                                                      | 19.5 ms: 1.04x slower                                                        |
| scimark_lu                 | 98.6 ms                                                      | 103 ms: 1.04x slower                                                         |
| logging_silent             | 93.3 ns                                                      | 97.2 ns: 1.04x slower                                                        |
| 2to3                       | 285 ms                                                       | 298 ms: 1.05x slower                                                         |
| regex_v8                   | 24.4 ms                                                      | 25.5 ms: 1.05x slower                                                        |
| dulwich_log                | 64.9 ms                                                      | 70.1 ms: 1.08x slower                                                        |
| unpickle_pure_python       | 210 us                                                       | 229 us: 1.09x slower                                                         |
| fannkuch                   | 362 ms                                                       | 396 ms: 1.09x slower                                                         |
| hexiom                     | 5.97 ms                                                      | 6.53 ms: 1.09x slower                                                        |
| python_startup             | 11.7 ms                                                      | 12.9 ms: 1.10x slower                                                        |
| telco                      | 7.16 ms                                                      | 8.08 ms: 1.13x slower                                                        |
| deltablue                  | 3.24 ms                                                      | 3.68 ms: 1.14x slower                                                        |
| go                         | 149 ms                                                       | 172 ms: 1.15x slower                                                         |
| pyflate                    | 442 ms                                                       | 512 ms: 1.16x slower                                                         |
| richards_super             | 50.8 ms                                                      | 60.2 ms: 1.19x slower                                                        |
| richards                   | 45.1 ms                                                      | 54.6 ms: 1.21x slower                                                        |
| python_startup_no_site     | 8.67 ms                                                      | 11.4 ms: 1.31x slower                                                        |
| coverage                   | 66.3 ms                                                      | 87.3 ms: 1.32x slower                                                        |
| scimark_sor                | 107 ms                                                       | 145 ms: 1.36x slower                                                         |
| Geometric mean             | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (14): async_tree_memoization, async_tree_cpu_io_mixed, create_gc_cycles, json, scimark_fft, tornado_http, xml_etree_process, pidigits, asyncio_websockets, deepcopy_memo, async_tree_memoization_tg, pycparser, bench_thread_pool, nbody
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.81% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
