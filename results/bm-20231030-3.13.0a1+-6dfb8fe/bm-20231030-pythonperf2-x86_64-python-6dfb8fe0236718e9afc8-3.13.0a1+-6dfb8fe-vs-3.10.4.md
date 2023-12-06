
# Results vs. 3.10.4

- fork: python
- ref: 6dfb8fe0236718e9afc8
- machine: linux-x86_64
- commit hash: 6dfb8fe
- commit date: 2023-10-30
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 297 ms: 1.18x faster                                                         |
| chameleon      | 9.88 ms                                                      | 7.54 ms: 1.31x faster                                                        |
| docutils       | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                                       |
| tornado_http   | 157 ms                                                       | 120 ms: 1.30x faster                                                         |
| Geometric mean | (ref)                                                        | 1.24x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 435 ms: 1.61x faster                                                         |
| async_tree_memoization  | 827 ms                                                       | 548 ms: 1.51x faster                                                         |
| async_tree_io           | 1.61 sec                                                     | 1.08 sec: 1.48x faster                                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 699 ms: 1.35x faster                                                         |
| Geometric mean          | (ref)                                                        | 1.49x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 91.3 ms: 1.47x faster                                                        |
| float          | 109 ms                                                       | 78.4 ms: 1.38x faster                                                        |
| pidigits       | 270 ms                                                       | 264 ms: 1.02x faster                                                         |
| Geometric mean | (ref)                                                        | 1.28x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 148 ms: 1.30x faster                                                         |
| regex_v8       | 27.1 ms                                                      | 25.5 ms: 1.06x faster                                                        |
| regex_dna      | 260 ms                                                       | 249 ms: 1.04x faster                                                         |
| regex_effbot   | 3.10 ms                                                      | 3.53 ms: 1.14x slower                                                        |
| Geometric mean | (ref)                                                        | 1.06x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 223 us: 1.41x faster                                                         |
| pickle_pure_python   | 453 us                                                       | 325 us: 1.39x faster                                                         |
| tomli_loads          | 2.96 sec                                                     | 2.21 sec: 1.34x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                        |
| xml_etree_process    | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                                        |
| json_loads           | 30.0 us                                                      | 24.8 us: 1.21x faster                                                        |
| xml_etree_generate   | 93.1 ms                                                      | 85.7 ms: 1.09x faster                                                        |
| xml_etree_parse      | 159 ms                                                       | 148 ms: 1.08x faster                                                         |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.02x faster                                                         |
| unpickle_list        | 4.45 us                                                      | 4.51 us: 1.01x slower                                                        |
| pickle               | 10.1 us                                                      | 10.4 us: 1.03x slower                                                        |
| pickle_list          | 4.23 us                                                      | 4.41 us: 1.04x slower                                                        |
| unpickle             | 13.9 us                                                      | 14.5 us: 1.04x slower                                                        |
| pickle_dict          | 30.4 us                                                      | 31.8 us: 1.05x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 154 us: 3.47x faster                                                         |
| asyncio_tcp              | 785 ms                                                       | 372 ms: 2.11x faster                                                         |
| deltablue                | 7.43 ms                                                      | 3.71 ms: 2.00x faster                                                        |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                                       |
| raytrace                 | 497 ms                                                       | 280 ms: 1.78x faster                                                         |
| logging_silent           | 168 ns                                                       | 97.4 ns: 1.72x faster                                                        |
| chaos                    | 106 ms                                                       | 61.9 ms: 1.71x faster                                                        |
| scimark_lu               | 165 ms                                                       | 99.8 ms: 1.65x faster                                                        |
| crypto_pyaes             | 118 ms                                                       | 72.5 ms: 1.63x faster                                                        |
| comprehensions           | 27.0 us                                                      | 16.7 us: 1.62x faster                                                        |
| sqlglot_parse            | 2.27 ms                                                      | 1.41 ms: 1.62x faster                                                        |
| async_tree_none          | 700 ms                                                       | 435 ms: 1.61x faster                                                         |
| generators               | 57.7 ms                                                      | 36.0 ms: 1.60x faster                                                        |
| scimark_monte_carlo      | 109 ms                                                       | 68.7 ms: 1.59x faster                                                        |
| richards_super           | 93.0 ms                                                      | 60.2 ms: 1.54x faster                                                        |
| spectral_norm            | 141 ms                                                       | 93.0 ms: 1.52x faster                                                        |
| go                       | 258 ms                                                       | 170 ms: 1.52x faster                                                         |
| async_tree_memoization   | 827 ms                                                       | 548 ms: 1.51x faster                                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.82 ms: 1.50x faster                                                        |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.48x faster                                                       |
| bench_mp_pool            | 6.82 ms                                                      | 4.63 ms: 1.47x faster                                                        |
| nbody                    | 134 ms                                                       | 91.3 ms: 1.47x faster                                                        |
| hexiom                   | 9.46 ms                                                      | 6.45 ms: 1.47x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                                        |
| unpickle_pure_python     | 315 us                                                       | 223 us: 1.41x faster                                                         |
| richards                 | 76.3 ms                                                      | 54.4 ms: 1.40x faster                                                        |
| pickle_pure_python       | 453 us                                                       | 325 us: 1.39x faster                                                         |
| float                    | 109 ms                                                       | 78.4 ms: 1.38x faster                                                        |
| pyflate                  | 698 ms                                                       | 510 ms: 1.37x faster                                                         |
| coroutines               | 30.9 ms                                                      | 22.6 ms: 1.36x faster                                                        |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 699 ms: 1.35x faster                                                         |
| logging_simple           | 9.06 us                                                      | 6.73 us: 1.35x faster                                                        |
| tomli_loads              | 2.96 sec                                                     | 2.21 sec: 1.34x faster                                                       |
| deepcopy_memo            | 50.5 us                                                      | 37.8 us: 1.34x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.8 ms: 1.32x faster                                                        |
| logging_format           | 9.82 us                                                      | 7.45 us: 1.32x faster                                                        |
| xml_etree_process        | 76.4 ms                                                      | 58.3 ms: 1.31x faster                                                        |
| chameleon                | 9.88 ms                                                      | 7.54 ms: 1.31x faster                                                        |
| regex_compile            | 192 ms                                                       | 148 ms: 1.30x faster                                                         |
| tornado_http             | 157 ms                                                       | 120 ms: 1.30x faster                                                         |
| nqueens                  | 112 ms                                                       | 87.6 ms: 1.28x faster                                                        |
| mypy2                    | 467 ms                                                       | 366 ms: 1.28x faster                                                         |
| pycparser                | 1.65 sec                                                     | 1.30 sec: 1.27x faster                                                       |
| sympy_sum                | 194 ms                                                       | 153 ms: 1.27x faster                                                         |
| scimark_sor              | 183 ms                                                       | 145 ms: 1.27x faster                                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.70 sec: 1.27x faster                                                       |
| sqlglot_normalize        | 146 ms                                                       | 116 ms: 1.26x faster                                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 828 ms: 1.26x faster                                                         |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.19 ms: 1.24x faster                                                        |
| sympy_str                | 359 ms                                                       | 290 ms: 1.24x faster                                                         |
| fannkuch                 | 488 ms                                                       | 397 ms: 1.23x faster                                                         |
| sympy_expand             | 599 ms                                                       | 488 ms: 1.23x faster                                                         |
| deepcopy                 | 459 us                                                       | 376 us: 1.22x faster                                                         |
| unpack_sequence          | 60.3 ns                                                      | 49.3 ns: 1.22x faster                                                        |
| json_loads               | 30.0 us                                                      | 24.8 us: 1.21x faster                                                        |
| sympy_integrate          | 28.3 ms                                                      | 23.4 ms: 1.21x faster                                                        |
| scimark_fft              | 363 ms                                                       | 301 ms: 1.20x faster                                                         |
| sqlglot_optimize         | 69.9 ms                                                      | 58.8 ms: 1.19x faster                                                        |
| docutils                 | 3.42 sec                                                     | 2.88 sec: 1.19x faster                                                       |
| deepcopy_reduce          | 4.00 us                                                      | 3.39 us: 1.18x faster                                                        |
| 2to3                     | 349 ms                                                       | 297 ms: 1.18x faster                                                         |
| bench_thread_pool        | 1.13 ms                                                      | 974 us: 1.16x faster                                                         |
| mdp                      | 2.94 sec                                                     | 2.53 sec: 1.16x faster                                                       |
| dulwich_log              | 80.0 ms                                                      | 69.1 ms: 1.16x faster                                                        |
| create_gc_cycles         | 1.79 ms                                                      | 1.57 ms: 1.14x faster                                                        |
| json                     | 5.91 ms                                                      | 5.23 ms: 1.13x faster                                                        |
| sqlite_synth             | 2.97 us                                                      | 2.66 us: 1.11x faster                                                        |
| xml_etree_generate       | 93.1 ms                                                      | 85.7 ms: 1.09x faster                                                        |
| xml_etree_parse          | 159 ms                                                       | 148 ms: 1.08x faster                                                         |
| pathlib                  | 21.2 ms                                                      | 19.7 ms: 1.08x faster                                                        |
| meteor_contest           | 138 ms                                                       | 129 ms: 1.07x faster                                                         |
| regex_v8                 | 27.1 ms                                                      | 25.5 ms: 1.06x faster                                                        |
| async_generators         | 418 ms                                                       | 395 ms: 1.06x faster                                                         |
| regex_dna                | 260 ms                                                       | 249 ms: 1.04x faster                                                         |
| pidigits                 | 270 ms                                                       | 264 ms: 1.02x faster                                                         |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.02x faster                                                         |
| asyncio_websockets       | 394 ms                                                       | 387 ms: 1.02x faster                                                         |
| gc_traversal             | 3.63 ms                                                      | 3.68 ms: 1.01x slower                                                        |
| unpickle_list            | 4.45 us                                                      | 4.51 us: 1.01x slower                                                        |
| pickle                   | 10.1 us                                                      | 10.4 us: 1.03x slower                                                        |
| pickle_list              | 4.23 us                                                      | 4.41 us: 1.04x slower                                                        |
| unpickle                 | 13.9 us                                                      | 14.5 us: 1.04x slower                                                        |
| pickle_dict              | 30.4 us                                                      | 31.8 us: 1.05x slower                                                        |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                        |
| telco                    | 7.21 ms                                                      | 8.08 ms: 1.12x slower                                                        |
| regex_effbot             | 3.10 ms                                                      | 3.53 ms: 1.14x slower                                                        |
| coverage                 | 65.9 ms                                                      | 82.9 ms: 1.26x slower                                                        |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.28x faster                                                                 |
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231030-3.13.0a1+-6dfb8fe/bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
