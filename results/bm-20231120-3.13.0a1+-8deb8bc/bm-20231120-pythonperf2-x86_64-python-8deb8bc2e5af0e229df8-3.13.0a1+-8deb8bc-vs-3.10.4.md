
# Results vs. 3.10.4

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: linux-x86_64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 291 ms: 1.20x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.39 ms: 1.34x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.81 sec: 1.22x faster                                                       |
| tornado_http   | 157 ms                                                       | 119 ms: 1.32x faster                                                         |
| Geometric mean | (ref)                                                        | 1.27x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 425 ms: 1.65x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 536 ms: 1.54x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.07 sec: 1.51x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 685 ms: 1.38x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.52x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 85.1 ms: 1.58x faster                                                        |
| float          | 109 ms                                                       | 78.5 ms: 1.38x faster                                                        |
| pidigits       | 270 ms                                                       | 266 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 141 ms: 1.36x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 24.8 ms: 1.09x faster                                                        |
| regex_dna      | 260 ms                                                       | 242 ms: 1.08x faster                                                         |
| regex_effbot   | 3.10 ms                                                      | 3.51 ms: 1.13x slower                                                        |
| Geometric mean | (ref)                                                        | 1.09x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 302 us: 1.50x faster                                                         |
| unpickle_pure_python | 315 us                                                       | 222 us: 1.42x faster                                                         |
| tomli_loads          | 2.96 sec                                                     | 2.18 sec: 1.36x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 58.5 ms: 1.31x faster                                                        |
| json_loads           | 30.0 us                                                      | 25.5 us: 1.18x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.08x faster                                                         |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.03x faster                                                         |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                        |
| unpickle_list        | 4.45 us                                                      | 4.66 us: 1.05x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.47 us: 1.06x slower                                                        |
| unpickle             | 13.9 us                                                      | 15.0 us: 1.07x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 33.1 us: 1.09x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.53x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.30x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.2 ms: 1.45x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 123 us: 4.34x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 368 ms: 2.13x faster                                                         |
| deltablue                | 7.43 ms                                                      | 3.59 ms: 2.07x faster                                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 2.00x faster                                                       |
| raytrace                 | 497 ms                                                       | 264 ms: 1.88x faster                                                         |
| chaos                    | 106 ms                                                       | 60.1 ms: 1.76x faster                                                        |
| logging_silent           | 168 ns                                                       | 95.6 ns: 1.75x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 69.7 ms: 1.69x faster                                                        |
| generators               | 57.7 ms                                                      | 34.4 ms: 1.67x faster                                                        |
| comprehensions           | 27.0 us                                                      | 16.3 us: 1.66x faster                                                        |
| sqlglot_parse            | 2.27 ms                                                      | 1.37 ms: 1.65x faster                                                        |
| async_tree_none          | 700 ms                                                       | 425 ms: 1.65x faster                                                         |
| scimark_monte_carlo      | 109 ms                                                       | 67.2 ms: 1.63x faster                                                        |
| richards_super           | 93.0 ms                                                      | 57.5 ms: 1.62x faster                                                        |
| scimark_lu               | 165 ms                                                       | 102 ms: 1.61x faster                                                         |
| nbody                    | 134 ms                                                       | 85.1 ms: 1.58x faster                                                        |
| spectral_norm            | 141 ms                                                       | 90.8 ms: 1.56x faster                                                        |
| async_tree_memoization   | 827 ms                                                       | 536 ms: 1.54x faster                                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.78 ms: 1.54x faster                                                        |
| go                       | 258 ms                                                       | 168 ms: 1.54x faster                                                         |
| async_tree_io            | 1.61 sec                                                     | 1.07 sec: 1.51x faster                                                       |
| pickle_pure_python       | 453 us                                                       | 302 us: 1.50x faster                                                         |
| hexiom                   | 9.46 ms                                                      | 6.39 ms: 1.48x faster                                                        |
| bench_mp_pool            | 6.82 ms                                                      | 4.64 ms: 1.47x faster                                                        |
| richards                 | 76.3 ms                                                      | 52.2 ms: 1.46x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.2 ms: 1.45x faster                                                        |
| unpickle_pure_python     | 315 us                                                       | 222 us: 1.42x faster                                                         |
| coroutines               | 30.9 ms                                                      | 22.2 ms: 1.39x faster                                                        |
| float                    | 109 ms                                                       | 78.5 ms: 1.38x faster                                                        |
| logging_simple           | 9.06 us                                                      | 6.55 us: 1.38x faster                                                        |
| logging_format           | 9.82 us                                                      | 7.11 us: 1.38x faster                                                        |
| deepcopy_memo            | 50.5 us                                                      | 36.6 us: 1.38x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 685 ms: 1.38x faster                                                         |
| regex_compile            | 192 ms                                                       | 141 ms: 1.36x faster                                                         |
| tomli_loads              | 2.96 sec                                                     | 2.18 sec: 1.36x faster                                                       |
| chameleon                | 9.88 ms                                                      | 7.39 ms: 1.34x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.61 sec: 1.33x faster                                                       |
| tornado_http             | 157 ms                                                       | 119 ms: 1.32x faster                                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 791 ms: 1.31x faster                                                         |
| pyflate                  | 698 ms                                                       | 532 ms: 1.31x faster                                                         |
| xml_etree_process        | 76.4 ms                                                      | 58.5 ms: 1.31x faster                                                        |
| unpack_sequence          | 60.3 ns                                                      | 46.4 ns: 1.30x faster                                                        |
| fannkuch                 | 488 ms                                                       | 378 ms: 1.29x faster                                                         |
| mypy2                    | 467 ms                                                       | 363 ms: 1.29x faster                                                         |
| sqlglot_normalize        | 146 ms                                                       | 114 ms: 1.29x faster                                                         |
| deepcopy                 | 459 us                                                       | 357 us: 1.28x faster                                                         |
| sympy_sum                | 194 ms                                                       | 151 ms: 1.28x faster                                                         |
| nqueens                  | 112 ms                                                       | 88.1 ms: 1.27x faster                                                        |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.15 ms: 1.25x faster                                                        |
| pycparser                | 1.65 sec                                                     | 1.32 sec: 1.25x faster                                                       |
| scimark_sor              | 183 ms                                                       | 147 ms: 1.25x faster                                                         |
| sympy_integrate          | 28.3 ms                                                      | 22.8 ms: 1.24x faster                                                        |
| sympy_str                | 359 ms                                                       | 289 ms: 1.24x faster                                                         |
| deepcopy_reduce          | 4.00 us                                                      | 3.24 us: 1.23x faster                                                        |
| sympy_expand             | 599 ms                                                       | 490 ms: 1.22x faster                                                         |
| docutils                 | 3.42 sec                                                     | 2.81 sec: 1.22x faster                                                       |
| sqlglot_optimize         | 69.9 ms                                                      | 57.8 ms: 1.21x faster                                                        |
| 2to3                     | 349 ms                                                       | 291 ms: 1.20x faster                                                         |
| scimark_fft              | 363 ms                                                       | 303 ms: 1.20x faster                                                         |
| dask                     | 469 ms                                                       | 396 ms: 1.18x faster                                                         |
| dulwich_log              | 80.0 ms                                                      | 67.6 ms: 1.18x faster                                                        |
| mdp                      | 2.94 sec                                                     | 2.49 sec: 1.18x faster                                                       |
| json_loads               | 30.0 us                                                      | 25.5 us: 1.18x faster                                                        |
| bench_thread_pool        | 1.13 ms                                                      | 963 us: 1.18x faster                                                         |
| async_generators         | 418 ms                                                       | 363 ms: 1.15x faster                                                         |
| json                     | 5.91 ms                                                      | 5.21 ms: 1.13x faster                                                        |
| pathlib                  | 21.2 ms                                                      | 18.8 ms: 1.13x faster                                                        |
| create_gc_cycles         | 1.79 ms                                                      | 1.62 ms: 1.11x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.10x faster                                                        |
| xml_etree_generate       | 93.1 ms                                                      | 85.3 ms: 1.09x faster                                                        |
| regex_v8                 | 27.1 ms                                                      | 24.8 ms: 1.09x faster                                                        |
| xml_etree_parse          | 159 ms                                                       | 148 ms: 1.08x faster                                                         |
| meteor_contest           | 138 ms                                                       | 128 ms: 1.08x faster                                                         |
| regex_dna                | 260 ms                                                       | 242 ms: 1.08x faster                                                         |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.03x faster                                                         |
| pidigits                 | 270 ms                                                       | 266 ms: 1.02x faster                                                         |
| asyncio_websockets       | 394 ms                                                       | 389 ms: 1.01x faster                                                         |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                        |
| gc_traversal             | 3.63 ms                                                      | 3.75 ms: 1.03x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.66 us: 1.05x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.47 us: 1.06x slower                                                        |
| unpickle                 | 13.9 us                                                      | 15.0 us: 1.07x slower                                                        |
| pickle_dict              | 30.4 us                                                      | 33.1 us: 1.09x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| telco                    | 7.21 ms                                                      | 8.08 ms: 1.12x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.51 ms: 1.13x slower                                                        |
| coverage                 | 65.9 ms                                                      | 79.7 ms: 1.21x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.53x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                                 |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-8deb8bc/bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
