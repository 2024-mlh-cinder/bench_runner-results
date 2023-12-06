
# Results vs. 3.10.4

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: windows-amd64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.13x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 227 ms: 1.05x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.36 ms: 1.12x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.64 sec: 1.14x faster                                                      |
| tornado_http   | 106 ms                                                      | 93.5 ms: 1.13x faster                                                       |
| Geometric mean | (ref)                                                       | 1.11x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 281 ms: 1.51x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 363 ms: 1.39x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 779 ms: 1.37x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 516 ms: 1.20x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.36x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 55.0 ms: 1.12x faster                                                       |
| pidigits       | 146 ms                                                      | 155 ms: 1.06x slower                                                        |
| nbody          | 71.0 ms                                                     | 75.8 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 87.7 ms: 1.17x faster                                                       |
| regex_dna      | 129 ms                                                      | 125 ms: 1.03x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 15.5 ms: 1.03x slower                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.90 ms: 1.21x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 6.43 ms: 1.36x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 194 us: 1.33x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 143 us: 1.24x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 40.3 ms: 1.07x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.55 sec: 1.06x faster                                                      |
| unpickle             | 9.11 us                                                     | 8.75 us: 1.04x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 95.5 ms: 1.01x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 66.2 ms: 1.03x slower                                                       |
| pickle               | 6.87 us                                                     | 7.27 us: 1.06x slower                                                       |
| json_loads           | 14.2 us                                                     | 15.1 us: 1.06x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.88 us: 1.07x slower                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 59.0 ms: 1.08x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.9 us: 1.10x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.6 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.3 ms: 1.19x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.74 ms: 1.16x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 81.4 us: 4.14x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.31 ms: 1.78x faster                                                       |
| raytrace                 | 266 ms                                                      | 175 ms: 1.52x faster                                                        |
| async_tree_none          | 424 ms                                                      | 281 ms: 1.51x faster                                                        |
| logging_silent           | 93.4 ns                                                     | 63.3 ns: 1.48x faster                                                       |
| go                       | 135 ms                                                      | 91.7 ms: 1.48x faster                                                       |
| comprehensions           | 16.6 us                                                     | 11.3 us: 1.46x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 493 ms: 1.46x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 831 us: 1.45x faster                                                        |
| richards_super           | 50.3 ms                                                     | 35.1 ms: 1.44x faster                                                       |
| chaos                    | 59.5 ms                                                     | 41.7 ms: 1.43x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 363 ms: 1.39x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 60.5 ms: 1.39x faster                                                       |
| async_tree_io            | 1.07 sec                                                    | 779 ms: 1.37x faster                                                        |
| crypto_pyaes             | 63.1 ms                                                     | 46.2 ms: 1.36x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.6 ms: 1.36x faster                                                       |
| json_dumps               | 8.77 ms                                                     | 6.43 ms: 1.36x faster                                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 1.07 ms: 1.35x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 194 us: 1.33x faster                                                        |
| generators               | 31.8 ms                                                     | 23.8 ms: 1.33x faster                                                       |
| richards                 | 40.6 ms                                                     | 30.7 ms: 1.32x faster                                                       |
| pyflate                  | 402 ms                                                      | 311 ms: 1.29x faster                                                        |
| hexiom                   | 5.59 ms                                                     | 4.36 ms: 1.28x faster                                                       |
| scimark_sor              | 105 ms                                                      | 82.9 ms: 1.27x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 143 us: 1.24x faster                                                        |
| sympy_sum                | 105 ms                                                      | 86.7 ms: 1.21x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 516 ms: 1.20x faster                                                        |
| sqlite_synth             | 1.90 us                                                     | 1.59 us: 1.19x faster                                                       |
| regex_compile            | 102 ms                                                      | 87.7 ms: 1.17x faster                                                       |
| pycparser                | 905 ms                                                      | 777 ms: 1.17x faster                                                        |
| mako                     | 8.98 ms                                                     | 7.74 ms: 1.16x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.64 sec: 1.14x faster                                                      |
| sympy_str                | 193 ms                                                      | 170 ms: 1.14x faster                                                        |
| sympy_integrate          | 15.0 ms                                                     | 13.2 ms: 1.14x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.51 sec: 1.13x faster                                                      |
| tornado_http             | 106 ms                                                      | 93.5 ms: 1.13x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 25.7 us: 1.13x faster                                                       |
| dask                     | 305 ms                                                      | 270 ms: 1.13x faster                                                        |
| float                    | 61.7 ms                                                     | 55.0 ms: 1.12x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.09 sec: 1.12x faster                                                      |
| chameleon                | 6.02 ms                                                     | 5.36 ms: 1.12x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 534 ms: 1.11x faster                                                        |
| sympy_expand             | 320 ms                                                      | 289 ms: 1.11x faster                                                        |
| spectral_norm            | 78.9 ms                                                     | 71.2 ms: 1.11x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 35.7 ms: 1.10x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 190 ms: 1.09x faster                                                        |
| nqueens                  | 68.3 ms                                                     | 63.6 ms: 1.07x faster                                                       |
| xml_etree_process        | 43.1 ms                                                     | 40.3 ms: 1.07x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 45.4 ms: 1.07x faster                                                       |
| deepcopy                 | 259 us                                                      | 244 us: 1.06x faster                                                        |
| tomli_loads              | 1.65 sec                                                    | 1.55 sec: 1.06x faster                                                      |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.98 sec: 1.06x faster                                                      |
| 2to3                     | 239 ms                                                      | 227 ms: 1.05x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 762 us: 1.05x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.75 us: 1.04x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 2.14 us: 1.04x faster                                                       |
| regex_dna                | 129 ms                                                      | 125 ms: 1.03x faster                                                        |
| xml_etree_parse          | 96.8 ms                                                     | 95.5 ms: 1.01x faster                                                       |
| coroutines               | 15.5 ms                                                     | 15.3 ms: 1.01x faster                                                       |
| fannkuch                 | 258 ms                                                      | 256 ms: 1.01x faster                                                        |
| logging_simple           | 6.28 us                                                     | 6.37 us: 1.01x slower                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 66.2 ms: 1.03x slower                                                       |
| logging_format           | 6.73 us                                                     | 6.92 us: 1.03x slower                                                       |
| regex_v8                 | 15.0 ms                                                     | 15.5 ms: 1.03x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 77.0 ms: 1.04x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.6 ms: 1.05x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.27 us: 1.06x slower                                                       |
| json_loads               | 14.2 us                                                     | 15.1 us: 1.06x slower                                                       |
| pidigits                 | 146 ms                                                      | 155 ms: 1.06x slower                                                        |
| nbody                    | 71.0 ms                                                     | 75.8 ms: 1.07x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.88 us: 1.07x slower                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.87 ms: 1.08x slower                                                       |
| scimark_fft              | 187 ms                                                      | 202 ms: 1.08x slower                                                        |
| xml_etree_generate       | 54.5 ms                                                     | 59.0 ms: 1.08x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.9 us: 1.10x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.55 ms: 1.11x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 66.4 ms: 1.11x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 82.1 ms: 1.13x slower                                                       |
| async_generators         | 219 ms                                                      | 252 ms: 1.15x slower                                                        |
| python_startup_no_site   | 15.3 ms                                                     | 18.3 ms: 1.19x slower                                                       |
| coverage                 | 38.4 ms                                                     | 46.2 ms: 1.20x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.90 ms: 1.21x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.91 ms: 1.29x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.13x faster                                                                |

Benchmark hidden because not significant (5): mypy2, bench_thread_pool, unpack_sequence, unpickle_list, json
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.06x
