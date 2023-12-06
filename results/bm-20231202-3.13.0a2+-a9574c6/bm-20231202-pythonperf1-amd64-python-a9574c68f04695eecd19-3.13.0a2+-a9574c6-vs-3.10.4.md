
# Results vs. 3.10.4

- fork: python
- ref: a9574c68f04695eecd19
- machine: windows-amd64
- commit hash: a9574c6
- commit date: 2023-12-02
- overall geometric mean: 1.16x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 217 ms: 1.10x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.17 ms: 1.17x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                                      |
| tornado_http   | 106 ms                                                      | 88.0 ms: 1.20x faster                                                       |
| Geometric mean | (ref)                                                       | 1.16x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 270 ms: 1.57x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 346 ms: 1.46x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 738 ms: 1.45x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 459 ms: 1.34x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.45x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.5 ms: 1.13x faster                                                       |
| pidigits       | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| nbody          | 71.0 ms                                                     | 74.2 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 86.5 ms: 1.18x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.59 ms: 1.02x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 15.4 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.74 ms: 1.53x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 194 us: 1.33x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 135 us: 1.31x faster                                                        |
| unpickle             | 9.11 us                                                     | 8.23 us: 1.11x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 39.0 ms: 1.10x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.54 sec: 1.07x faster                                                      |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| unpickle_list        | 2.68 us                                                     | 2.60 us: 1.03x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 93.8 ms: 1.03x faster                                                       |
| pickle               | 6.87 us                                                     | 7.03 us: 1.02x slower                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 57.0 ms: 1.05x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.88 us: 1.07x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.5 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.09x faster                                                                |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.1 ms: 1.02x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.0 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.93 ms: 1.30x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 79.2 us: 4.25x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.21 ms: 1.86x faster                                                       |
| async_tree_none          | 424 ms                                                      | 270 ms: 1.57x faster                                                        |
| asyncio_tcp              | 717 ms                                                      | 460 ms: 1.56x faster                                                        |
| raytrace                 | 266 ms                                                      | 172 ms: 1.55x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.74 ms: 1.53x faster                                                       |
| comprehensions           | 16.6 us                                                     | 11.1 us: 1.50x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 62.5 ns: 1.49x faster                                                       |
| richards_super           | 50.3 ms                                                     | 33.9 ms: 1.49x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 346 ms: 1.46x faster                                                        |
| go                       | 135 ms                                                      | 92.8 ms: 1.46x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 829 us: 1.45x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 738 ms: 1.45x faster                                                        |
| chaos                    | 59.5 ms                                                     | 41.3 ms: 1.44x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 45.3 ms: 1.39x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 60.3 ms: 1.39x faster                                                       |
| generators               | 31.8 ms                                                     | 23.1 ms: 1.38x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.3 ms: 1.37x faster                                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 1.06 ms: 1.36x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 459 ms: 1.34x faster                                                        |
| richards                 | 40.6 ms                                                     | 30.3 ms: 1.34x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 194 us: 1.33x faster                                                        |
| pyflate                  | 402 ms                                                      | 304 ms: 1.32x faster                                                        |
| hexiom                   | 5.59 ms                                                     | 4.24 ms: 1.32x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 135 us: 1.31x faster                                                        |
| mako                     | 8.98 ms                                                     | 6.93 ms: 1.30x faster                                                       |
| scimark_sor              | 105 ms                                                      | 82.5 ms: 1.28x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 63.2 ms: 1.25x faster                                                       |
| sympy_sum                | 105 ms                                                      | 85.2 ms: 1.24x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.58 us: 1.20x faster                                                       |
| tornado_http             | 106 ms                                                      | 88.0 ms: 1.20x faster                                                       |
| regex_compile            | 102 ms                                                      | 86.5 ms: 1.18x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                                      |
| sympy_str                | 193 ms                                                      | 164 ms: 1.18x faster                                                        |
| deepcopy_memo            | 29.0 us                                                     | 24.7 us: 1.17x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 12.8 ms: 1.17x faster                                                       |
| dask                     | 305 ms                                                      | 261 ms: 1.17x faster                                                        |
| chameleon                | 6.02 ms                                                     | 5.17 ms: 1.17x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.06 sec: 1.15x faster                                                      |
| dulwich_log              | 48.6 ms                                                     | 42.4 ms: 1.14x faster                                                       |
| sympy_expand             | 320 ms                                                      | 281 ms: 1.14x faster                                                        |
| pprint_safe_repr         | 594 ms                                                      | 523 ms: 1.14x faster                                                        |
| float                    | 61.7 ms                                                     | 54.5 ms: 1.13x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.87 sec: 1.12x faster                                                      |
| mdp                      | 1.71 sec                                                    | 1.53 sec: 1.12x faster                                                      |
| unpickle                 | 9.11 us                                                     | 8.23 us: 1.11x faster                                                       |
| xml_etree_process        | 43.1 ms                                                     | 39.0 ms: 1.10x faster                                                       |
| 2to3                     | 239 ms                                                      | 217 ms: 1.10x faster                                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 36.0 ms: 1.09x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 190 ms: 1.09x faster                                                        |
| deepcopy                 | 259 us                                                      | 239 us: 1.09x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 744 us: 1.07x faster                                                        |
| tomli_loads              | 1.65 sec                                                    | 1.54 sec: 1.07x faster                                                      |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| coroutines               | 15.5 ms                                                     | 14.5 ms: 1.07x faster                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.50 ms: 1.06x faster                                                       |
| nqueens                  | 68.3 ms                                                     | 64.2 ms: 1.06x faster                                                       |
| pycparser                | 905 ms                                                      | 851 ms: 1.06x faster                                                        |
| deepcopy_reduce          | 2.22 us                                                     | 2.09 us: 1.06x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 870 us: 1.05x faster                                                        |
| unpickle_list            | 2.68 us                                                     | 2.60 us: 1.03x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 93.8 ms: 1.03x faster                                                       |
| fannkuch                 | 258 ms                                                      | 251 ms: 1.03x faster                                                        |
| scimark_fft              | 187 ms                                                      | 186 ms: 1.01x faster                                                        |
| pidigits                 | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| meteor_contest           | 73.8 ms                                                     | 75.1 ms: 1.02x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.59 ms: 1.02x slower                                                       |
| regex_v8                 | 15.0 ms                                                     | 15.4 ms: 1.02x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.03 us: 1.02x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.1 ms: 1.02x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.53 us: 1.04x slower                                                       |
| logging_format           | 6.73 us                                                     | 7.02 us: 1.04x slower                                                       |
| nbody                    | 71.0 ms                                                     | 74.2 ms: 1.04x slower                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 57.0 ms: 1.05x slower                                                       |
| unpack_sequence          | 40.0 ns                                                     | 42.4 ns: 1.06x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.49 ms: 1.07x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.88 us: 1.07x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 64.6 ms: 1.08x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.5 us: 1.08x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 79.6 ms: 1.09x slower                                                       |
| async_generators         | 219 ms                                                      | 240 ms: 1.10x slower                                                        |
| python_startup_no_site   | 15.3 ms                                                     | 18.0 ms: 1.17x slower                                                       |
| mypy2                    | 347 ms                                                      | 426 ms: 1.23x slower                                                        |
| coverage                 | 38.4 ms                                                     | 47.3 ms: 1.23x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.81 ms: 1.26x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.16x faster                                                                |

Benchmark hidden because not significant (2): json, xml_etree_iterparse
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231202-3.13.0a2+-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
