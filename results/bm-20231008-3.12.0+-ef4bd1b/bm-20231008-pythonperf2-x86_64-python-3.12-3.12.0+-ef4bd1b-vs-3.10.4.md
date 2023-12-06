
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: ef4bd1b
- commit date: 2023-10-08
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 288 ms: 1.22x faster                                       |
| docutils       | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                     |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                       |
| Geometric mean | (ref)                                                        | 1.22x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 85.4 ms: 1.61x faster                                      |
| float          | 110 ms                                                       | 78.1 ms: 1.41x faster                                      |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                       |
| Geometric mean | (ref)                                                        | 1.32x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 144 ms: 1.35x faster                                       |
| regex_v8       | 26.6 ms                                                      | 23.2 ms: 1.15x faster                                      |
| regex_dna      | 259 ms                                                       | 240 ms: 1.08x faster                                       |
| regex_effbot   | 2.99 ms                                                      | 3.53 ms: 1.18x slower                                      |
| Geometric mean | (ref)                                                        | 1.09x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 205 us: 1.56x faster                                       |
| pickle_pure_python   | 457 us                                                       | 319 us: 1.43x faster                                       |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                      |
| tomli_loads          | 2.97 sec                                                     | 2.25 sec: 1.32x faster                                     |
| xml_etree_process    | 76.0 ms                                                      | 58.3 ms: 1.30x faster                                      |
| json_loads           | 30.0 us                                                      | 24.4 us: 1.23x faster                                      |
| xml_etree_generate   | 94.6 ms                                                      | 86.6 ms: 1.09x faster                                      |
| xml_etree_parse      | 162 ms                                                       | 150 ms: 1.08x faster                                       |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.05x faster                                       |
| pickle               | 9.94 us                                                      | 10.0 us: 1.01x slower                                      |
| unpickle             | 14.2 us                                                      | 14.8 us: 1.04x slower                                      |
| pickle_dict          | 30.0 us                                                      | 31.5 us: 1.05x slower                                      |
| pickle_list          | 4.11 us                                                      | 4.32 us: 1.05x slower                                      |
| unpickle_list        | 4.49 us                                                      | 5.03 us: 1.12x slower                                      |
| Geometric mean       | (ref)                                                        | 1.14x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                      |
| python_startup_no_site | 7.32 ms                                                      | 8.65 ms: 1.18x slower                                      |
| Geometric mean         | (ref)                                                        | 1.10x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 152 us: 3.45x faster                                       |
| deltablue                | 7.47 ms                                                      | 3.23 ms: 2.32x faster                                      |
| asyncio_tcp              | 782 ms                                                       | 379 ms: 2.06x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.97x faster                                     |
| logging_silent           | 166 ns                                                       | 93.8 ns: 1.77x faster                                      |
| richards_super           | 90.8 ms                                                      | 51.6 ms: 1.76x faster                                      |
| go                       | 259 ms                                                       | 148 ms: 1.75x faster                                       |
| chaos                    | 107 ms                                                       | 63.9 ms: 1.68x faster                                      |
| richards                 | 74.1 ms                                                      | 45.0 ms: 1.65x faster                                      |
| scimark_lu               | 164 ms                                                       | 99.8 ms: 1.64x faster                                      |
| sqlglot_parse            | 2.26 ms                                                      | 1.38 ms: 1.63x faster                                      |
| raytrace                 | 488 ms                                                       | 303 ms: 1.61x faster                                       |
| nbody                    | 137 ms                                                       | 85.4 ms: 1.61x faster                                      |
| scimark_sor              | 177 ms                                                       | 110 ms: 1.60x faster                                       |
| hexiom                   | 9.52 ms                                                      | 5.95 ms: 1.60x faster                                      |
| unpickle_pure_python     | 321 us                                                       | 205 us: 1.56x faster                                       |
| generators               | 58.0 ms                                                      | 37.2 ms: 1.56x faster                                      |
| pyflate                  | 697 ms                                                       | 447 ms: 1.56x faster                                       |
| async_tree_none          | 700 ms                                                       | 459 ms: 1.53x faster                                       |
| sqlglot_transpile        | 2.71 ms                                                      | 1.78 ms: 1.52x faster                                      |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                     |
| scimark_monte_carlo      | 109 ms                                                       | 72.5 ms: 1.51x faster                                      |
| async_tree_memoization   | 824 ms                                                       | 551 ms: 1.50x faster                                       |
| spectral_norm            | 136 ms                                                       | 91.3 ms: 1.49x faster                                      |
| crypto_pyaes             | 118 ms                                                       | 79.9 ms: 1.48x faster                                      |
| mako                     | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                      |
| pickle_pure_python       | 457 us                                                       | 319 us: 1.43x faster                                       |
| float                    | 110 ms                                                       | 78.1 ms: 1.41x faster                                      |
| fannkuch                 | 496 ms                                                       | 354 ms: 1.40x faster                                       |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                      |
| logging_simple           | 8.90 us                                                      | 6.50 us: 1.37x faster                                      |
| regex_compile            | 194 ms                                                       | 144 ms: 1.35x faster                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 707 ms: 1.34x faster                                       |
| pycparser                | 1.66 sec                                                     | 1.24 sec: 1.34x faster                                     |
| pprint_pformat           | 2.15 sec                                                     | 1.61 sec: 1.33x faster                                     |
| pprint_safe_repr         | 1.05 sec                                                     | 791 ms: 1.33x faster                                       |
| deepcopy_memo            | 48.9 us                                                      | 36.9 us: 1.32x faster                                      |
| logging_format           | 9.57 us                                                      | 7.25 us: 1.32x faster                                      |
| tomli_loads              | 2.97 sec                                                     | 2.25 sec: 1.32x faster                                     |
| coroutines               | 30.4 ms                                                      | 23.1 ms: 1.31x faster                                      |
| xml_etree_process        | 76.0 ms                                                      | 58.3 ms: 1.30x faster                                      |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                       |
| unpack_sequence          | 59.5 ns                                                      | 47.4 ns: 1.25x faster                                      |
| dulwich_log              | 80.1 ms                                                      | 64.8 ms: 1.24x faster                                      |
| nqueens                  | 112 ms                                                       | 91.1 ms: 1.24x faster                                      |
| sqlglot_normalize        | 144 ms                                                       | 118 ms: 1.23x faster                                       |
| comprehensions           | 26.9 us                                                      | 21.9 us: 1.23x faster                                      |
| json_loads               | 30.0 us                                                      | 24.4 us: 1.23x faster                                      |
| sqlglot_optimize         | 70.3 ms                                                      | 57.7 ms: 1.22x faster                                      |
| deepcopy                 | 454 us                                                       | 373 us: 1.22x faster                                       |
| 2to3                     | 350 ms                                                       | 288 ms: 1.22x faster                                       |
| scimark_fft              | 359 ms                                                       | 299 ms: 1.20x faster                                       |
| mdp                      | 3.03 sec                                                     | 2.54 sec: 1.19x faster                                     |
| bench_thread_pool        | 1.14 ms                                                      | 956 us: 1.19x faster                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.38 ms: 1.19x faster                                      |
| docutils                 | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                     |
| deepcopy_reduce          | 4.03 us                                                      | 3.43 us: 1.17x faster                                      |
| dask                     | 463 ms                                                       | 395 ms: 1.17x faster                                       |
| json                     | 5.96 ms                                                      | 5.17 ms: 1.15x faster                                      |
| regex_v8                 | 26.6 ms                                                      | 23.2 ms: 1.15x faster                                      |
| pathlib                  | 21.7 ms                                                      | 19.3 ms: 1.13x faster                                      |
| create_gc_cycles         | 1.82 ms                                                      | 1.62 ms: 1.13x faster                                      |
| async_generators         | 422 ms                                                       | 386 ms: 1.09x faster                                       |
| xml_etree_generate       | 94.6 ms                                                      | 86.6 ms: 1.09x faster                                      |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                      |
| meteor_contest           | 137 ms                                                       | 126 ms: 1.08x faster                                       |
| xml_etree_parse          | 162 ms                                                       | 150 ms: 1.08x faster                                       |
| regex_dna                | 259 ms                                                       | 240 ms: 1.08x faster                                       |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.05x faster                                       |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                       |
| pickle                   | 9.94 us                                                      | 10.0 us: 1.01x slower                                      |
| gc_traversal             | 3.45 ms                                                      | 3.50 ms: 1.01x slower                                      |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                      |
| unpickle                 | 14.2 us                                                      | 14.8 us: 1.04x slower                                      |
| pickle_dict              | 30.0 us                                                      | 31.5 us: 1.05x slower                                      |
| pickle_list              | 4.11 us                                                      | 4.32 us: 1.05x slower                                      |
| unpickle_list            | 4.49 us                                                      | 5.03 us: 1.12x slower                                      |
| regex_effbot             | 2.99 ms                                                      | 3.53 ms: 1.18x slower                                      |
| python_startup_no_site   | 7.32 ms                                                      | 8.65 ms: 1.18x slower                                      |
| coverage                 | 64.0 ms                                                      | 86.6 ms: 1.35x slower                                      |
| Geometric mean           | (ref)                                                        | 1.30x faster                                               |

Benchmark hidden because not significant (3): bench_mp_pool, mypy2, telco
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.22x
