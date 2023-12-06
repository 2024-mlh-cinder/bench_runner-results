
# Results vs. 3.10.4

- fork: python
- ref: a9574c68f04695eecd19
- machine: windows-amd64
- commit hash: a9574c6
- commit date: 2023-12-02
- overall geometric mean: 1.12x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 227 ms: 1.05x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.24 ms: 1.15x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.65 sec: 1.14x faster                                                      |
| tornado_http   | 106 ms                                                      | 90.6 ms: 1.17x faster                                                       |
| Geometric mean | (ref)                                                       | 1.13x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 276 ms: 1.53x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 752 ms: 1.42x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 356 ms: 1.42x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 467 ms: 1.32x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.42x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 57.6 ms: 1.07x faster                                                       |
| pidigits       | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| nbody          | 71.0 ms                                                     | 81.7 ms: 1.15x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 92.1 ms: 1.11x faster                                                       |
| regex_dna      | 129 ms                                                      | 119 ms: 1.08x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 19.5 ms: 1.30x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.86 ms: 1.50x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 192 us: 1.35x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 146 us: 1.21x faster                                                        |
| unpickle             | 9.11 us                                                     | 8.13 us: 1.12x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.49 sec: 1.10x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 39.8 ms: 1.08x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| unpickle_list        | 2.68 us                                                     | 2.57 us: 1.04x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 93.1 ms: 1.04x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 67.6 ms: 1.05x slower                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 57.3 ms: 1.05x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.3 us: 1.07x slower                                                       |
| pickle_list          | 2.69 us                                                     | 3.10 us: 1.15x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.5 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.5 ms: 1.20x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.37 ms: 1.22x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 83.4 us: 4.04x faster                                                       |
| async_tree_none          | 424 ms                                                      | 276 ms: 1.53x faster                                                        |
| logging_silent           | 93.4 ns                                                     | 62.2 ns: 1.50x faster                                                       |
| richards_super           | 50.3 ms                                                     | 33.6 ms: 1.50x faster                                                       |
| json_dumps               | 8.77 ms                                                     | 5.86 ms: 1.50x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.76 ms: 1.50x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 484 ms: 1.48x faster                                                        |
| raytrace                 | 266 ms                                                      | 184 ms: 1.45x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 752 ms: 1.42x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 356 ms: 1.42x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 849 us: 1.42x faster                                                        |
| generators               | 31.8 ms                                                     | 22.4 ms: 1.42x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 59.5 ms: 1.41x faster                                                       |
| go                       | 135 ms                                                      | 96.3 ms: 1.40x faster                                                       |
| richards                 | 40.6 ms                                                     | 30.0 ms: 1.35x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 192 us: 1.35x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.08 ms: 1.34x faster                                                       |
| scimark_sor              | 105 ms                                                      | 79.5 ms: 1.32x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 467 ms: 1.32x faster                                                        |
| chaos                    | 59.5 ms                                                     | 45.0 ms: 1.32x faster                                                       |
| pycparser                | 905 ms                                                      | 701 ms: 1.29x faster                                                        |
| crypto_pyaes             | 63.1 ms                                                     | 49.0 ms: 1.29x faster                                                       |
| comprehensions           | 16.6 us                                                     | 13.2 us: 1.26x faster                                                       |
| pyflate                  | 402 ms                                                      | 325 ms: 1.24x faster                                                        |
| mako                     | 8.98 ms                                                     | 7.37 ms: 1.22x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 23.8 us: 1.22x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 146 us: 1.21x faster                                                        |
| mdp                      | 1.71 sec                                                    | 1.43 sec: 1.20x faster                                                      |
| sqlite_synth             | 1.90 us                                                     | 1.59 us: 1.20x faster                                                       |
| sympy_sum                | 105 ms                                                      | 89.8 ms: 1.17x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 49.8 ms: 1.17x faster                                                       |
| tornado_http             | 106 ms                                                      | 90.6 ms: 1.17x faster                                                       |
| chameleon                | 6.02 ms                                                     | 5.24 ms: 1.15x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.83 sec: 1.15x faster                                                      |
| docutils                 | 1.88 sec                                                    | 1.65 sec: 1.14x faster                                                      |
| dask                     | 305 ms                                                      | 268 ms: 1.14x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 43.0 ms: 1.13x faster                                                       |
| unpickle                 | 9.11 us                                                     | 8.13 us: 1.12x faster                                                       |
| sympy_str                | 193 ms                                                      | 173 ms: 1.11x faster                                                        |
| regex_compile            | 102 ms                                                      | 92.1 ms: 1.11x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.49 sec: 1.10x faster                                                      |
| sympy_expand             | 320 ms                                                      | 290 ms: 1.10x faster                                                        |
| hexiom                   | 5.59 ms                                                     | 5.08 ms: 1.10x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.6 ms: 1.10x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.12 sec: 1.09x faster                                                      |
| deepcopy                 | 259 us                                                      | 239 us: 1.09x faster                                                        |
| regex_dna                | 129 ms                                                      | 119 ms: 1.08x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 39.8 ms: 1.08x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 549 ms: 1.08x faster                                                        |
| coroutines               | 15.5 ms                                                     | 14.4 ms: 1.08x faster                                                       |
| float                    | 61.7 ms                                                     | 57.6 ms: 1.07x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 37.1 ms: 1.06x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 753 us: 1.06x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 195 ms: 1.06x faster                                                        |
| 2to3                     | 239 ms                                                      | 227 ms: 1.05x faster                                                        |
| json                     | 3.10 ms                                                     | 2.96 ms: 1.05x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 2.12 us: 1.05x faster                                                       |
| unpickle_list            | 2.68 us                                                     | 2.57 us: 1.04x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 93.1 ms: 1.04x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 882 us: 1.03x faster                                                        |
| nqueens                  | 68.3 ms                                                     | 66.3 ms: 1.03x faster                                                       |
| unpack_sequence          | 40.0 ns                                                     | 38.9 ns: 1.03x faster                                                       |
| pidigits                 | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| regex_effbot             | 1.56 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| spectral_norm            | 78.9 ms                                                     | 81.5 ms: 1.03x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.5 ms: 1.04x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.57 us: 1.05x slower                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 67.6 ms: 1.05x slower                                                       |
| logging_format           | 6.73 us                                                     | 7.05 us: 1.05x slower                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 57.3 ms: 1.05x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 77.6 ms: 1.05x slower                                                       |
| fannkuch                 | 258 ms                                                      | 273 ms: 1.06x slower                                                        |
| pickle_dict              | 17.1 us                                                     | 18.3 us: 1.07x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.53 ms: 1.09x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 79.9 ms: 1.10x slower                                                       |
| scimark_fft              | 187 ms                                                      | 207 ms: 1.11x slower                                                        |
| async_generators         | 219 ms                                                      | 245 ms: 1.12x slower                                                        |
| bench_mp_pool            | 59.9 ms                                                     | 68.5 ms: 1.14x slower                                                       |
| pickle_list              | 2.69 us                                                     | 3.10 us: 1.15x slower                                                       |
| nbody                    | 71.0 ms                                                     | 81.7 ms: 1.15x slower                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 3.08 ms: 1.15x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.5 ms: 1.20x slower                                                       |
| coverage                 | 38.4 ms                                                     | 47.3 ms: 1.23x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.73 ms: 1.24x slower                                                       |
| mypy2                    | 347 ms                                                      | 439 ms: 1.27x slower                                                        |
| regex_v8                 | 15.0 ms                                                     | 19.5 ms: 1.30x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.12x faster                                                                |

Benchmark hidden because not significant (1): pickle
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231202-3.13.0a2+-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2+-a9574c6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.08x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.07x
