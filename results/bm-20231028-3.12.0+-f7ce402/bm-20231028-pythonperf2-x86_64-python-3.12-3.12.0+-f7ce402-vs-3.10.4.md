
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 286 ms: 1.22x faster                                       |
| chameleon      | 9.88 ms                                                      | 7.22 ms: 1.37x faster                                      |
| docutils       | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                     |
| tornado_http   | 157 ms                                                       | 121 ms: 1.30x faster                                       |
| Geometric mean | (ref)                                                        | 1.27x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 700 ms                                                       | 461 ms: 1.52x faster                                       |
| async_tree_io           | 1.61 sec                                                     | 1.06 sec: 1.51x faster                                     |
| async_tree_memoization  | 827 ms                                                       | 554 ms: 1.49x faster                                       |
| async_tree_cpu_io_mixed | 946 ms                                                       | 706 ms: 1.34x faster                                       |
| Geometric mean          | (ref)                                                        | 1.46x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 134 ms                                                       | 86.1 ms: 1.56x faster                                      |
| float          | 109 ms                                                       | 78.9 ms: 1.38x faster                                      |
| pidigits       | 270 ms                                                       | 265 ms: 1.02x faster                                       |
| Geometric mean | (ref)                                                        | 1.30x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 143 ms: 1.35x faster                                       |
| regex_v8       | 27.1 ms                                                      | 24.4 ms: 1.11x faster                                      |
| regex_dna      | 260 ms                                                       | 247 ms: 1.06x faster                                       |
| regex_effbot   | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                      |
| Geometric mean | (ref)                                                        | 1.09x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_pure_python | 315 us                                                       | 211 us: 1.49x faster                                       |
| pickle_pure_python   | 453 us                                                       | 321 us: 1.41x faster                                       |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                      |
| tomli_loads          | 2.96 sec                                                     | 2.19 sec: 1.35x faster                                     |
| xml_etree_process    | 76.4 ms                                                      | 58.6 ms: 1.30x faster                                      |
| json_loads           | 30.0 us                                                      | 24.2 us: 1.24x faster                                      |
| xml_etree_generate   | 93.1 ms                                                      | 85.8 ms: 1.09x faster                                      |
| xml_etree_parse      | 159 ms                                                       | 149 ms: 1.07x faster                                       |
| xml_etree_iterparse  | 110 ms                                                       | 103 ms: 1.07x faster                                       |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                      |
| unpickle             | 13.9 us                                                      | 14.6 us: 1.05x slower                                      |
| pickle_dict          | 30.4 us                                                      | 32.4 us: 1.06x slower                                      |
| pickle_list          | 4.23 us                                                      | 4.50 us: 1.06x slower                                      |
| unpickle_list        | 4.45 us                                                      | 4.78 us: 1.08x slower                                      |
| Geometric mean       | (ref)                                                        | 1.14x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.01x slower                                      |
| python_startup_no_site | 7.35 ms                                                      | 8.66 ms: 1.18x slower                                      |
| Geometric mean         | (ref)                                                        | 1.09x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.0 ms: 1.47x faster                                      |
| django_template | 51.8 ms                                                      | 39.3 ms: 1.32x faster                                      |
| Geometric mean  | (ref)                                                        | 1.39x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 533 us                                                       | 154 us: 3.46x faster                                       |
| deltablue                | 7.43 ms                                                      | 3.30 ms: 2.25x faster                                      |
| asyncio_tcp              | 785 ms                                                       | 381 ms: 2.06x faster                                       |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 1.57 sec: 1.99x faster                                     |
| richards_super           | 93.0 ms                                                      | 51.1 ms: 1.82x faster                                      |
| logging_silent           | 168 ns                                                       | 93.7 ns: 1.79x faster                                      |
| go                       | 258 ms                                                       | 149 ms: 1.73x faster                                       |
| richards                 | 76.3 ms                                                      | 44.7 ms: 1.71x faster                                      |
| scimark_sor              | 183 ms                                                       | 108 ms: 1.70x faster                                       |
| chaos                    | 106 ms                                                       | 64.3 ms: 1.65x faster                                      |
| raytrace                 | 497 ms                                                       | 304 ms: 1.64x faster                                       |
| scimark_lu               | 165 ms                                                       | 101 ms: 1.63x faster                                       |
| sqlglot_parse            | 2.27 ms                                                      | 1.40 ms: 1.62x faster                                      |
| scimark_monte_carlo      | 109 ms                                                       | 68.8 ms: 1.59x faster                                      |
| hexiom                   | 9.46 ms                                                      | 5.95 ms: 1.59x faster                                      |
| pyflate                  | 698 ms                                                       | 441 ms: 1.58x faster                                       |
| generators               | 57.7 ms                                                      | 36.7 ms: 1.57x faster                                      |
| nbody                    | 134 ms                                                       | 86.1 ms: 1.56x faster                                      |
| spectral_norm            | 141 ms                                                       | 91.5 ms: 1.54x faster                                      |
| async_tree_none          | 700 ms                                                       | 461 ms: 1.52x faster                                       |
| sqlglot_transpile        | 2.73 ms                                                      | 1.80 ms: 1.52x faster                                      |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.51x faster                                     |
| async_tree_memoization   | 827 ms                                                       | 554 ms: 1.49x faster                                       |
| unpickle_pure_python     | 315 us                                                       | 211 us: 1.49x faster                                       |
| mako                     | 14.7 ms                                                      | 10.0 ms: 1.47x faster                                      |
| crypto_pyaes             | 118 ms                                                       | 80.9 ms: 1.46x faster                                      |
| pickle_pure_python       | 453 us                                                       | 321 us: 1.41x faster                                       |
| json_dumps               | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                      |
| fannkuch                 | 488 ms                                                       | 353 ms: 1.38x faster                                       |
| float                    | 109 ms                                                       | 78.9 ms: 1.38x faster                                      |
| deepcopy_memo            | 50.5 us                                                      | 36.8 us: 1.37x faster                                      |
| chameleon                | 9.88 ms                                                      | 7.22 ms: 1.37x faster                                      |
| tomli_loads              | 2.96 sec                                                     | 2.19 sec: 1.35x faster                                     |
| regex_compile            | 192 ms                                                       | 143 ms: 1.35x faster                                       |
| coroutines               | 30.9 ms                                                      | 23.0 ms: 1.34x faster                                      |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 706 ms: 1.34x faster                                       |
| pycparser                | 1.65 sec                                                     | 1.24 sec: 1.33x faster                                     |
| logging_simple           | 9.06 us                                                      | 6.86 us: 1.32x faster                                      |
| pprint_pformat           | 2.15 sec                                                     | 1.63 sec: 1.32x faster                                     |
| django_template          | 51.8 ms                                                      | 39.3 ms: 1.32x faster                                      |
| logging_format           | 9.82 us                                                      | 7.51 us: 1.31x faster                                      |
| xml_etree_process        | 76.4 ms                                                      | 58.6 ms: 1.30x faster                                      |
| tornado_http             | 157 ms                                                       | 121 ms: 1.30x faster                                       |
| pprint_safe_repr         | 1.04 sec                                                     | 805 ms: 1.29x faster                                       |
| json_loads               | 30.0 us                                                      | 24.2 us: 1.24x faster                                      |
| comprehensions           | 27.0 us                                                      | 21.8 us: 1.24x faster                                      |
| sqlalchemy_imperative    | 23.0 ms                                                      | 18.6 ms: 1.24x faster                                      |
| deepcopy                 | 459 us                                                       | 374 us: 1.23x faster                                       |
| scimark_fft              | 363 ms                                                       | 295 ms: 1.23x faster                                       |
| nqueens                  | 112 ms                                                       | 91.3 ms: 1.22x faster                                      |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.26 ms: 1.22x faster                                      |
| 2to3                     | 349 ms                                                       | 286 ms: 1.22x faster                                       |
| sympy_expand             | 599 ms                                                       | 490 ms: 1.22x faster                                       |
| dulwich_log              | 80.0 ms                                                      | 65.6 ms: 1.22x faster                                      |
| sqlglot_normalize        | 146 ms                                                       | 121 ms: 1.21x faster                                       |
| gunicorn                 | 1.20 ms                                                      | 1.00 ms: 1.20x faster                                      |
| dask                     | 469 ms                                                       | 393 ms: 1.19x faster                                       |
| docutils                 | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                     |
| sympy_sum                | 194 ms                                                       | 162 ms: 1.19x faster                                       |
| aiohttp                  | 1.21 ms                                                      | 1.02 ms: 1.18x faster                                      |
| sympy_integrate          | 28.3 ms                                                      | 24.0 ms: 1.18x faster                                      |
| sympy_str                | 359 ms                                                       | 304 ms: 1.18x faster                                       |
| sqlalchemy_declarative   | 189 ms                                                       | 160 ms: 1.18x faster                                       |
| bench_thread_pool        | 1.13 ms                                                      | 963 us: 1.18x faster                                       |
| sqlglot_optimize         | 69.9 ms                                                      | 59.6 ms: 1.17x faster                                      |
| json                     | 5.91 ms                                                      | 5.12 ms: 1.15x faster                                      |
| deepcopy_reduce          | 4.00 us                                                      | 3.48 us: 1.15x faster                                      |
| mdp                      | 2.94 sec                                                     | 2.57 sec: 1.14x faster                                     |
| create_gc_cycles         | 1.79 ms                                                      | 1.58 ms: 1.13x faster                                      |
| regex_v8                 | 27.1 ms                                                      | 24.4 ms: 1.11x faster                                      |
| pathlib                  | 21.2 ms                                                      | 19.2 ms: 1.10x faster                                      |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                      |
| xml_etree_generate       | 93.1 ms                                                      | 85.8 ms: 1.09x faster                                      |
| async_generators         | 418 ms                                                       | 391 ms: 1.07x faster                                       |
| xml_etree_parse          | 159 ms                                                       | 149 ms: 1.07x faster                                       |
| xml_etree_iterparse      | 110 ms                                                       | 103 ms: 1.07x faster                                       |
| regex_dna                | 260 ms                                                       | 247 ms: 1.06x faster                                       |
| unpack_sequence          | 60.3 ns                                                      | 57.2 ns: 1.05x faster                                      |
| meteor_contest           | 138 ms                                                       | 131 ms: 1.05x faster                                       |
| coverage                 | 65.9 ms                                                      | 64.2 ms: 1.03x faster                                      |
| pidigits                 | 270 ms                                                       | 265 ms: 1.02x faster                                       |
| asyncio_websockets       | 394 ms                                                       | 388 ms: 1.02x faster                                       |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                      |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.01x slower                                      |
| gc_traversal             | 3.63 ms                                                      | 3.69 ms: 1.02x slower                                      |
| telco                    | 7.21 ms                                                      | 7.39 ms: 1.02x slower                                      |
| unpickle                 | 13.9 us                                                      | 14.6 us: 1.05x slower                                      |
| pickle_dict              | 30.4 us                                                      | 32.4 us: 1.06x slower                                      |
| pickle_list              | 4.23 us                                                      | 4.50 us: 1.06x slower                                      |
| unpickle_list            | 4.45 us                                                      | 4.78 us: 1.08x slower                                      |
| regex_effbot             | 3.10 ms                                                      | 3.49 ms: 1.13x slower                                      |
| python_startup_no_site   | 7.35 ms                                                      | 8.66 ms: 1.18x slower                                      |
| Geometric mean           | (ref)                                                        | 1.29x faster                                               |

Benchmark hidden because not significant (2): bench_mp_pool, mypy2
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231028-3.12.0+-f7ce402/bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.22x
