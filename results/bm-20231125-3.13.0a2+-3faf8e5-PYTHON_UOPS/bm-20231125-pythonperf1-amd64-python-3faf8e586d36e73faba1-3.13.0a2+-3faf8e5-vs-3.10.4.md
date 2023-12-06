
# Results vs. 3.10.4

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: windows-amd64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.10x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 231 ms: 1.04x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.39 ms: 1.12x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.72 sec: 1.09x faster                                                      |
| tornado_http   | 106 ms                                                      | 94.2 ms: 1.12x faster                                                       |
| Geometric mean | (ref)                                                       | 1.09x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 287 ms: 1.48x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 778 ms: 1.37x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 370 ms: 1.37x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 495 ms: 1.25x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.36x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 57.7 ms: 1.07x faster                                                       |
| pidigits       | 146 ms                                                      | 151 ms: 1.03x slower                                                        |
| nbody          | 71.0 ms                                                     | 83.2 ms: 1.17x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 95.9 ms: 1.07x faster                                                       |
| regex_dna      | 129 ms                                                      | 123 ms: 1.06x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.74 ms: 1.12x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 19.4 ms: 1.29x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 6.08 ms: 1.44x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 199 us: 1.30x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 148 us: 1.20x faster                                                        |
| tomli_loads          | 1.65 sec                                                    | 1.50 sec: 1.10x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 41.3 ms: 1.04x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 94.2 ms: 1.03x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.87 us: 1.03x faster                                                       |
| json_loads           | 14.2 us                                                     | 14.5 us: 1.02x slower                                                       |
| pickle               | 6.87 us                                                     | 7.12 us: 1.04x slower                                                       |
| unpickle_list        | 2.68 us                                                     | 2.79 us: 1.04x slower                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 68.4 ms: 1.06x slower                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 59.6 ms: 1.09x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 19.3 us: 1.13x slower                                                       |
| pickle_list          | 2.69 us                                                     | 3.21 us: 1.19x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.5 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.3 ms: 1.19x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.70 ms: 1.17x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 85.8 us: 3.93x faster                                                       |
| async_tree_none          | 424 ms                                                      | 287 ms: 1.48x faster                                                        |
| deltablue                | 4.12 ms                                                     | 2.80 ms: 1.47x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 64.5 ns: 1.45x faster                                                       |
| json_dumps               | 8.77 ms                                                     | 6.08 ms: 1.44x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 498 ms: 1.44x faster                                                        |
| richards_super           | 50.3 ms                                                     | 35.5 ms: 1.42x faster                                                       |
| raytrace                 | 266 ms                                                      | 188 ms: 1.41x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 867 us: 1.39x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 778 ms: 1.37x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 370 ms: 1.37x faster                                                        |
| go                       | 135 ms                                                      | 99.8 ms: 1.35x faster                                                       |
| generators               | 31.8 ms                                                     | 23.9 ms: 1.33x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 63.3 ms: 1.33x faster                                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 1.10 ms: 1.31x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 48.2 ms: 1.31x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 199 us: 1.30x faster                                                        |
| richards                 | 40.6 ms                                                     | 31.3 ms: 1.30x faster                                                       |
| chaos                    | 59.5 ms                                                     | 46.5 ms: 1.28x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 495 ms: 1.25x faster                                                        |
| scimark_sor              | 105 ms                                                      | 84.5 ms: 1.25x faster                                                       |
| comprehensions           | 16.6 us                                                     | 13.5 us: 1.23x faster                                                       |
| pycparser                | 905 ms                                                      | 744 ms: 1.22x faster                                                        |
| pyflate                  | 402 ms                                                      | 334 ms: 1.20x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 148 us: 1.20x faster                                                        |
| sqlite_synth             | 1.90 us                                                     | 1.59 us: 1.19x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.45 sec: 1.18x faster                                                      |
| mako                     | 8.98 ms                                                     | 7.70 ms: 1.17x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.81 sec: 1.16x faster                                                      |
| scimark_monte_carlo      | 58.0 ms                                                     | 50.3 ms: 1.15x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 25.2 us: 1.15x faster                                                       |
| sympy_sum                | 105 ms                                                      | 93.5 ms: 1.13x faster                                                       |
| tornado_http             | 106 ms                                                      | 94.2 ms: 1.12x faster                                                       |
| chameleon                | 6.02 ms                                                     | 5.39 ms: 1.12x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.50 sec: 1.10x faster                                                      |
| hexiom                   | 5.59 ms                                                     | 5.10 ms: 1.10x faster                                                       |
| dask                     | 305 ms                                                      | 278 ms: 1.10x faster                                                        |
| docutils                 | 1.88 sec                                                    | 1.72 sec: 1.09x faster                                                      |
| sympy_str                | 193 ms                                                      | 179 ms: 1.08x faster                                                        |
| sympy_integrate          | 15.0 ms                                                     | 14.0 ms: 1.07x faster                                                       |
| float                    | 61.7 ms                                                     | 57.7 ms: 1.07x faster                                                       |
| regex_compile            | 102 ms                                                      | 95.9 ms: 1.07x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 559 ms: 1.06x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 754 us: 1.06x faster                                                        |
| regex_dna                | 129 ms                                                      | 123 ms: 1.06x faster                                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.16 sec: 1.05x faster                                                      |
| deepcopy                 | 259 us                                                      | 246 us: 1.05x faster                                                        |
| sympy_expand             | 320 ms                                                      | 305 ms: 1.05x faster                                                        |
| coroutines               | 15.5 ms                                                     | 14.8 ms: 1.05x faster                                                       |
| xml_etree_process        | 43.1 ms                                                     | 41.3 ms: 1.04x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 46.7 ms: 1.04x faster                                                       |
| 2to3                     | 239 ms                                                      | 231 ms: 1.04x faster                                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 38.2 ms: 1.03x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 94.2 ms: 1.03x faster                                                       |
| unpickle                 | 9.11 us                                                     | 8.87 us: 1.03x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 893 us: 1.02x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 202 ms: 1.02x faster                                                        |
| json_loads               | 14.2 us                                                     | 14.5 us: 1.02x slower                                                       |
| pidigits                 | 146 ms                                                      | 151 ms: 1.03x slower                                                        |
| pickle                   | 6.87 us                                                     | 7.12 us: 1.04x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.5 ms: 1.04x slower                                                       |
| unpickle_list            | 2.68 us                                                     | 2.79 us: 1.04x slower                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 68.4 ms: 1.06x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 78.7 ms: 1.07x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.69 us: 1.07x slower                                                       |
| logging_format           | 6.73 us                                                     | 7.26 us: 1.08x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.52 ms: 1.09x slower                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 59.6 ms: 1.09x slower                                                       |
| spectral_norm            | 78.9 ms                                                     | 86.2 ms: 1.09x slower                                                       |
| fannkuch                 | 258 ms                                                      | 283 ms: 1.10x slower                                                        |
| bench_mp_pool            | 59.9 ms                                                     | 66.3 ms: 1.11x slower                                                       |
| unpack_sequence          | 40.0 ns                                                     | 44.4 ns: 1.11x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 81.2 ms: 1.12x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.74 ms: 1.12x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 19.3 us: 1.13x slower                                                       |
| scimark_fft              | 187 ms                                                      | 212 ms: 1.13x slower                                                        |
| async_generators         | 219 ms                                                      | 251 ms: 1.15x slower                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 3.06 ms: 1.15x slower                                                       |
| nbody                    | 71.0 ms                                                     | 83.2 ms: 1.17x slower                                                       |
| pickle_list              | 2.69 us                                                     | 3.21 us: 1.19x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.3 ms: 1.19x slower                                                       |
| coverage                 | 38.4 ms                                                     | 45.9 ms: 1.20x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.84 ms: 1.27x slower                                                       |
| regex_v8                 | 15.0 ms                                                     | 19.4 ms: 1.29x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.10x faster                                                                |

Benchmark hidden because not significant (4): mypy2, json, deepcopy_reduce, nqueens
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.06x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.04x
