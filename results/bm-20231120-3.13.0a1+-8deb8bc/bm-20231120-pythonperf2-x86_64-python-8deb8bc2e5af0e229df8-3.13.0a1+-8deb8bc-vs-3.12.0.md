
# Results vs. 3.12.0

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: linux-x86_64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.00x slower \*
- HPT reliability: 86.55%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 291 ms: 1.02x slower                                                         |
| chameleon      | 7.27 ms                                                      | 7.39 ms: 1.02x slower                                                        |
| docutils       | 2.89 sec                                                     | 2.81 sec: 1.03x faster                                                       |
| tornado_http   | 122 ms                                                       | 119 ms: 1.03x faster                                                         |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 459 ms                                                       | 425 ms: 1.08x faster                                                         |
| async_tree_memoization  | 554 ms                                                       | 536 ms: 1.03x faster                                                         |
| async_tree_cpu_io_mixed | 704 ms                                                       | 685 ms: 1.03x faster                                                         |
| async_tree_none_tg      | 440 ms                                                       | 436 ms: 1.01x faster                                                         |
| async_tree_io           | 1.06 sec                                                     | 1.07 sec: 1.01x slower                                                       |
| async_tree_io_tg        | 1.07 sec                                                     | 1.08 sec: 1.01x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.02x faster                                                                 |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 78.5 ms: 1.04x faster                                                        |
| pidigits       | 264 ms                                                       | 266 ms: 1.01x slower                                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                                 |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.51 ms: 1.03x faster                                                        |
| regex_compile  | 145 ms                                                       | 141 ms: 1.02x faster                                                         |
| regex_dna      | 240 ms                                                       | 242 ms: 1.01x slower                                                         |
| regex_v8       | 24.4 ms                                                      | 24.8 ms: 1.02x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 319 us                                                       | 302 us: 1.06x faster                                                         |
| unpickle             | 15.3 us                                                      | 15.0 us: 1.02x faster                                                        |
| pickle               | 10.0 us                                                      | 10.2 us: 1.01x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| pickle_dict          | 32.0 us                                                      | 33.1 us: 1.03x slower                                                        |
| json_dumps           | 10.3 ms                                                      | 10.7 ms: 1.04x slower                                                        |
| json_loads           | 24.3 us                                                      | 25.5 us: 1.05x slower                                                        |
| unpickle_pure_python | 210 us                                                       | 222 us: 1.06x slower                                                         |
| pickle_list          | 4.22 us                                                      | 4.47 us: 1.06x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                 |

Benchmark hidden because not significant (5): xml_etree_generate, unpickle_list, xml_etree_process, tomli_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| python_startup_no_site | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.19x slower                                                                 |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| comprehensions           | 21.8 us                                                      | 16.3 us: 1.34x faster                                                        |
| typing_runtime_protocols | 150 us                                                       | 123 us: 1.22x faster                                                         |
| crypto_pyaes             | 82.4 ms                                                      | 69.7 ms: 1.18x faster                                                        |
| unpack_sequence          | 54.5 ns                                                      | 46.4 ns: 1.18x faster                                                        |
| raytrace                 | 301 ms                                                       | 264 ms: 1.14x faster                                                         |
| generators               | 37.3 ms                                                      | 34.4 ms: 1.08x faster                                                        |
| scimark_sparse_mat_mult  | 4.49 ms                                                      | 4.15 ms: 1.08x faster                                                        |
| async_tree_none          | 459 ms                                                       | 425 ms: 1.08x faster                                                         |
| sympy_sum                | 163 ms                                                       | 151 ms: 1.08x faster                                                         |
| bench_mp_pool            | 4.96 ms                                                      | 4.64 ms: 1.07x faster                                                        |
| chaos                    | 64.1 ms                                                      | 60.1 ms: 1.07x faster                                                        |
| async_generators         | 385 ms                                                       | 363 ms: 1.06x faster                                                         |
| sympy_str                | 305 ms                                                       | 289 ms: 1.06x faster                                                         |
| pickle_pure_python       | 319 us                                                       | 302 us: 1.06x faster                                                         |
| sympy_integrate          | 24.0 ms                                                      | 22.8 ms: 1.05x faster                                                        |
| deepcopy_reduce          | 3.41 us                                                      | 3.24 us: 1.05x faster                                                        |
| sqlglot_normalize        | 119 ms                                                       | 114 ms: 1.05x faster                                                         |
| float                    | 81.6 ms                                                      | 78.5 ms: 1.04x faster                                                        |
| deepcopy                 | 371 us                                                       | 357 us: 1.04x faster                                                         |
| coroutines               | 23.1 ms                                                      | 22.2 ms: 1.04x faster                                                        |
| scimark_monte_carlo      | 69.5 ms                                                      | 67.2 ms: 1.04x faster                                                        |
| spectral_norm            | 93.9 ms                                                      | 90.8 ms: 1.03x faster                                                        |
| asyncio_tcp              | 380 ms                                                       | 368 ms: 1.03x faster                                                         |
| async_tree_memoization   | 554 ms                                                       | 536 ms: 1.03x faster                                                         |
| docutils                 | 2.89 sec                                                     | 2.81 sec: 1.03x faster                                                       |
| regex_effbot             | 3.61 ms                                                      | 3.51 ms: 1.03x faster                                                        |
| async_tree_cpu_io_mixed  | 704 ms                                                       | 685 ms: 1.03x faster                                                         |
| tornado_http             | 122 ms                                                       | 119 ms: 1.03x faster                                                         |
| mdp                      | 2.56 sec                                                     | 2.49 sec: 1.03x faster                                                       |
| logging_format           | 7.29 us                                                      | 7.11 us: 1.03x faster                                                        |
| sqlglot_parse            | 1.41 ms                                                      | 1.37 ms: 1.02x faster                                                        |
| unpickle                 | 15.3 us                                                      | 15.0 us: 1.02x faster                                                        |
| nqueens                  | 90.1 ms                                                      | 88.1 ms: 1.02x faster                                                        |
| regex_compile            | 145 ms                                                       | 141 ms: 1.02x faster                                                         |
| pprint_safe_repr         | 808 ms                                                       | 791 ms: 1.02x faster                                                         |
| pprint_pformat           | 1.64 sec                                                     | 1.61 sec: 1.02x faster                                                       |
| sqlglot_transpile        | 1.80 ms                                                      | 1.78 ms: 1.02x faster                                                        |
| logging_simple           | 6.64 us                                                      | 6.55 us: 1.01x faster                                                        |
| sqlglot_optimize         | 58.4 ms                                                      | 57.8 ms: 1.01x faster                                                        |
| async_tree_none_tg       | 440 ms                                                       | 436 ms: 1.01x faster                                                         |
| mypy2                    | 365 ms                                                       | 363 ms: 1.01x faster                                                         |
| sympy_expand             | 492 ms                                                       | 490 ms: 1.00x faster                                                         |
| asyncio_tcp_ssl          | 1.57 sec                                                     | 1.57 sec: 1.00x faster                                                       |
| pidigits                 | 264 ms                                                       | 266 ms: 1.01x slower                                                         |
| regex_dna                | 240 ms                                                       | 242 ms: 1.01x slower                                                         |
| json                     | 5.17 ms                                                      | 5.21 ms: 1.01x slower                                                        |
| async_tree_io            | 1.06 sec                                                     | 1.07 sec: 1.01x slower                                                       |
| meteor_contest           | 126 ms                                                       | 128 ms: 1.01x slower                                                         |
| asyncio_websockets       | 386 ms                                                       | 389 ms: 1.01x slower                                                         |
| async_tree_io_tg         | 1.07 sec                                                     | 1.08 sec: 1.01x slower                                                       |
| pickle                   | 10.0 us                                                      | 10.2 us: 1.01x slower                                                        |
| gc_traversal             | 3.70 ms                                                      | 3.75 ms: 1.01x slower                                                        |
| regex_v8                 | 24.4 ms                                                      | 24.8 ms: 1.02x slower                                                        |
| chameleon                | 7.27 ms                                                      | 7.39 ms: 1.02x slower                                                        |
| pycparser                | 1.29 sec                                                     | 1.32 sec: 1.02x slower                                                       |
| 2to3                     | 285 ms                                                       | 291 ms: 1.02x slower                                                         |
| logging_silent           | 93.3 ns                                                      | 95.6 ns: 1.03x slower                                                        |
| create_gc_cycles         | 1.58 ms                                                      | 1.62 ms: 1.03x slower                                                        |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.03x slower                                                         |
| pickle_dict              | 32.0 us                                                      | 33.1 us: 1.03x slower                                                        |
| scimark_lu               | 98.6 ms                                                      | 102 ms: 1.04x slower                                                         |
| dulwich_log              | 64.9 ms                                                      | 67.6 ms: 1.04x slower                                                        |
| json_dumps               | 10.3 ms                                                      | 10.7 ms: 1.04x slower                                                        |
| fannkuch                 | 362 ms                                                       | 378 ms: 1.04x slower                                                         |
| json_loads               | 24.3 us                                                      | 25.5 us: 1.05x slower                                                        |
| unpickle_pure_python     | 210 us                                                       | 222 us: 1.06x slower                                                         |
| pickle_list              | 4.22 us                                                      | 4.47 us: 1.06x slower                                                        |
| hexiom                   | 5.97 ms                                                      | 6.39 ms: 1.07x slower                                                        |
| python_startup           | 11.7 ms                                                      | 12.8 ms: 1.10x slower                                                        |
| deltablue                | 3.24 ms                                                      | 3.59 ms: 1.11x slower                                                        |
| go                       | 149 ms                                                       | 168 ms: 1.13x slower                                                         |
| telco                    | 7.16 ms                                                      | 8.08 ms: 1.13x slower                                                        |
| richards_super           | 50.8 ms                                                      | 57.5 ms: 1.13x slower                                                        |
| richards                 | 45.1 ms                                                      | 52.2 ms: 1.16x slower                                                        |
| coverage                 | 66.3 ms                                                      | 79.7 ms: 1.20x slower                                                        |
| pyflate                  | 442 ms                                                       | 532 ms: 1.20x slower                                                         |
| python_startup_no_site   | 8.67 ms                                                      | 11.3 ms: 1.30x slower                                                        |
| scimark_sor              | 107 ms                                                       | 147 ms: 1.38x slower                                                         |
| Geometric mean           | (ref)                                                        | 1.00x slower                                                                 |

Benchmark hidden because not significant (15): nbody, async_tree_cpu_io_mixed_tg, sqlite_synth, scimark_fft, async_tree_memoization_tg, xml_etree_generate, pathlib, deepcopy_memo, unpickle_list, xml_etree_process, tomli_loads, xml_etree_parse, dask, bench_thread_pool, mako
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 86.55% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
