
# Results vs. 3.10.4

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 30e5f4b
- commit date: 2023-11-04
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 292 ms: 1.20x faster                                                                   |
| chameleon      | 9.88 ms                                                      | 7.41 ms: 1.33x faster                                                                  |
| docutils       | 3.42 sec                                                     | 2.82 sec: 1.21x faster                                                                 |
| tornado_http   | 157 ms                                                       | 120 ms: 1.31x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.26x faster                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|-------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 430 ms: 1.63x faster                                                                   |
| async_tree_memoization  | 827 ms                                                       | 547 ms: 1.51x faster                                                                   |
| async_tree_io           | 1.61 sec                                                     | 1.07 sec: 1.50x faster                                                                 |
| async_tree_cpu_io_mixed | 946 ms                                                       | 698 ms: 1.36x faster                                                                   |
| Geometric mean          | (ref)                                                        | 1.50x faster                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| nbody          | 134 ms                                                       | 83.7 ms: 1.60x faster                                                                  |
| float          | 109 ms                                                       | 80.0 ms: 1.36x faster                                                                  |
| pidigits       | 270 ms                                                       | 264 ms: 1.03x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.31x faster                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 145 ms: 1.33x faster                                                                   |
| regex_v8       | 27.1 ms                                                      | 24.4 ms: 1.11x faster                                                                  |
| regex_dna      | 260 ms                                                       | 241 ms: 1.08x faster                                                                   |
| regex_effbot   | 3.10 ms                                                      | 3.47 ms: 1.12x slower                                                                  |
| Geometric mean | (ref)                                                        | 1.09x faster                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 307 us: 1.47x faster                                                                   |
| unpickle_pure_python | 315 us                                                       | 221 us: 1.43x faster                                                                   |
| json_dumps           | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                                                  |
| xml_etree_process    | 76.4 ms                                                      | 57.8 ms: 1.32x faster                                                                  |
| tomli_loads          | 2.96 sec                                                     | 2.29 sec: 1.29x faster                                                                 |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.23x faster                                                                  |
| xml_etree_generate   | 93.1 ms                                                      | 85.0 ms: 1.10x faster                                                                  |
| xml_etree_parse      | 159 ms                                                       | 151 ms: 1.06x faster                                                                   |
| xml_etree_iterparse  | 110 ms                                                       | 108 ms: 1.02x faster                                                                   |
| pickle               | 10.1 us                                                      | 10.1 us: 1.01x slower                                                                  |
| unpickle             | 13.9 us                                                      | 14.3 us: 1.03x slower                                                                  |
| unpickle_list        | 4.45 us                                                      | 4.63 us: 1.04x slower                                                                  |
| pickle_list          | 4.23 us                                                      | 4.46 us: 1.05x slower                                                                  |
| pickle_dict          | 30.4 us                                                      | 33.0 us: 1.08x slower                                                                  |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                                  |
| python_startup_no_site | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.31x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.2 ms: 1.45x faster                                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 122 us: 4.36x faster                                                                   |
| asyncio_tcp              | 785 ms                                                       | 369 ms: 2.13x faster                                                                   |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.58 sec: 1.98x faster                                                                 |
| deltablue                | 7.43 ms                                                      | 3.76 ms: 1.97x faster                                                                  |
| raytrace                 | 497 ms                                                       | 271 ms: 1.84x faster                                                                   |
| logging_silent           | 168 ns                                                       | 95.1 ns: 1.76x faster                                                                  |
| chaos                    | 106 ms                                                       | 61.0 ms: 1.74x faster                                                                  |
| generators               | 57.7 ms                                                      | 34.3 ms: 1.68x faster                                                                  |
| crypto_pyaes             | 118 ms                                                       | 70.7 ms: 1.67x faster                                                                  |
| comprehensions           | 27.0 us                                                      | 16.4 us: 1.65x faster                                                                  |
| scimark_monte_carlo      | 109 ms                                                       | 66.8 ms: 1.64x faster                                                                  |
| async_tree_none          | 700 ms                                                       | 430 ms: 1.63x faster                                                                   |
| scimark_lu               | 165 ms                                                       | 102 ms: 1.61x faster                                                                   |
| nbody                    | 134 ms                                                       | 83.7 ms: 1.60x faster                                                                  |
| sqlglot_parse            | 2.27 ms                                                      | 1.42 ms: 1.60x faster                                                                  |
| richards_super           | 93.0 ms                                                      | 59.4 ms: 1.56x faster                                                                  |
| spectral_norm            | 141 ms                                                       | 90.6 ms: 1.56x faster                                                                  |
| async_tree_memoization   | 827 ms                                                       | 547 ms: 1.51x faster                                                                   |
| async_tree_io            | 1.61 sec                                                     | 1.07 sec: 1.50x faster                                                                 |
| go                       | 258 ms                                                       | 172 ms: 1.50x faster                                                                   |
| sqlglot_transpile        | 2.73 ms                                                      | 1.83 ms: 1.49x faster                                                                  |
| hexiom                   | 9.46 ms                                                      | 6.41 ms: 1.48x faster                                                                  |
| pickle_pure_python       | 453 us                                                       | 307 us: 1.47x faster                                                                   |
| mako                     | 14.7 ms                                                      | 10.2 ms: 1.45x faster                                                                  |
| unpickle_pure_python     | 315 us                                                       | 221 us: 1.43x faster                                                                   |
| bench_mp_pool            | 6.82 ms                                                      | 4.78 ms: 1.43x faster                                                                  |
| richards                 | 76.3 ms                                                      | 53.7 ms: 1.42x faster                                                                  |
| pyflate                  | 698 ms                                                       | 501 ms: 1.39x faster                                                                   |
| json_dumps               | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                                                  |
| logging_simple           | 9.06 us                                                      | 6.60 us: 1.37x faster                                                                  |
| coroutines               | 30.9 ms                                                      | 22.6 ms: 1.36x faster                                                                  |
| float                    | 109 ms                                                       | 80.0 ms: 1.36x faster                                                                  |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 698 ms: 1.36x faster                                                                   |
| deepcopy_memo            | 50.5 us                                                      | 37.3 us: 1.36x faster                                                                  |
| logging_format           | 9.82 us                                                      | 7.30 us: 1.34x faster                                                                  |
| chameleon                | 9.88 ms                                                      | 7.41 ms: 1.33x faster                                                                  |
| regex_compile            | 192 ms                                                       | 145 ms: 1.33x faster                                                                   |
| xml_etree_process        | 76.4 ms                                                      | 57.8 ms: 1.32x faster                                                                  |
| pprint_pformat           | 2.15 sec                                                     | 1.63 sec: 1.32x faster                                                                 |
| tornado_http             | 157 ms                                                       | 120 ms: 1.31x faster                                                                   |
| pprint_safe_repr         | 1.04 sec                                                     | 798 ms: 1.30x faster                                                                   |
| tomli_loads              | 2.96 sec                                                     | 2.29 sec: 1.29x faster                                                                 |
| sympy_sum                | 194 ms                                                       | 151 ms: 1.28x faster                                                                   |
| nqueens                  | 112 ms                                                       | 88.0 ms: 1.27x faster                                                                  |
| fannkuch                 | 488 ms                                                       | 384 ms: 1.27x faster                                                                   |
| mypy2                    | 467 ms                                                       | 368 ms: 1.27x faster                                                                   |
| deepcopy                 | 459 us                                                       | 362 us: 1.27x faster                                                                   |
| sqlglot_normalize        | 146 ms                                                       | 116 ms: 1.26x faster                                                                   |
| pycparser                | 1.65 sec                                                     | 1.30 sec: 1.26x faster                                                                 |
| scimark_sor              | 183 ms                                                       | 147 ms: 1.25x faster                                                                   |
| sympy_str                | 359 ms                                                       | 289 ms: 1.24x faster                                                                   |
| sympy_integrate          | 28.3 ms                                                      | 22.9 ms: 1.24x faster                                                                  |
| json_loads               | 30.0 us                                                      | 24.3 us: 1.23x faster                                                                  |
| deepcopy_reduce          | 4.00 us                                                      | 3.27 us: 1.22x faster                                                                  |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.29 ms: 1.22x faster                                                                  |
| docutils                 | 3.42 sec                                                     | 2.82 sec: 1.21x faster                                                                 |
| sympy_expand             | 599 ms                                                       | 494 ms: 1.21x faster                                                                   |
| 2to3                     | 349 ms                                                       | 292 ms: 1.20x faster                                                                   |
| scimark_fft              | 363 ms                                                       | 304 ms: 1.19x faster                                                                   |
| sqlglot_optimize         | 69.9 ms                                                      | 58.5 ms: 1.19x faster                                                                  |
| bench_thread_pool        | 1.13 ms                                                      | 964 us: 1.18x faster                                                                   |
| dulwich_log              | 80.0 ms                                                      | 68.0 ms: 1.18x faster                                                                  |
| mdp                      | 2.94 sec                                                     | 2.50 sec: 1.18x faster                                                                 |
| unpack_sequence          | 60.3 ns                                                      | 51.5 ns: 1.17x faster                                                                  |
| async_generators         | 418 ms                                                       | 363 ms: 1.15x faster                                                                   |
| json                     | 5.91 ms                                                      | 5.13 ms: 1.15x faster                                                                  |
| create_gc_cycles         | 1.79 ms                                                      | 1.58 ms: 1.13x faster                                                                  |
| sqlite_synth             | 2.97 us                                                      | 2.64 us: 1.12x faster                                                                  |
| regex_v8                 | 27.1 ms                                                      | 24.4 ms: 1.11x faster                                                                  |
| xml_etree_generate       | 93.1 ms                                                      | 85.0 ms: 1.10x faster                                                                  |
| pathlib                  | 21.2 ms                                                      | 19.5 ms: 1.09x faster                                                                  |
| regex_dna                | 260 ms                                                       | 241 ms: 1.08x faster                                                                   |
| meteor_contest           | 138 ms                                                       | 128 ms: 1.07x faster                                                                   |
| xml_etree_parse          | 159 ms                                                       | 151 ms: 1.06x faster                                                                   |
| gc_traversal             | 3.63 ms                                                      | 3.52 ms: 1.03x faster                                                                  |
| pidigits                 | 270 ms                                                       | 264 ms: 1.03x faster                                                                   |
| asyncio_websockets       | 394 ms                                                       | 386 ms: 1.02x faster                                                                   |
| xml_etree_iterparse      | 110 ms                                                       | 108 ms: 1.02x faster                                                                   |
| pickle                   | 10.1 us                                                      | 10.1 us: 1.01x slower                                                                  |
| unpickle                 | 13.9 us                                                      | 14.3 us: 1.03x slower                                                                  |
| unpickle_list            | 4.45 us                                                      | 4.63 us: 1.04x slower                                                                  |
| pickle_list              | 4.23 us                                                      | 4.46 us: 1.05x slower                                                                  |
| pickle_dict              | 30.4 us                                                      | 33.0 us: 1.08x slower                                                                  |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                                  |
| telco                    | 7.21 ms                                                      | 8.06 ms: 1.12x slower                                                                  |
| regex_effbot             | 3.10 ms                                                      | 3.47 ms: 1.12x slower                                                                  |
| coverage                 | 65.9 ms                                                      | 81.4 ms: 1.23x slower                                                                  |
| python_startup_no_site   | 7.35 ms                                                      | 11.3 ms: 1.54x slower                                                                  |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                                           |
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231104-3.13.0a1+-30e5f4b/bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
