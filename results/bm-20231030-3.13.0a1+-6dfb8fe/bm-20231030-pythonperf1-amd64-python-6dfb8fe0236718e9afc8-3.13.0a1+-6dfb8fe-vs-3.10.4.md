
# Results vs. 3.10.4

- fork: python
- ref: 6dfb8fe0236718e9afc8
- machine: windows-amd64
- commit hash: 6dfb8fe
- commit date: 2023-10-30
- overall geometric mean: 1.16x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 223 ms: 1.07x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.22 ms: 1.15x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.64 sec: 1.14x faster                                                      |
| tornado_http   | 106 ms                                                      | 89.4 ms: 1.18x faster                                                       |
| Geometric mean | (ref)                                                       | 1.14x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 278 ms: 1.52x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 355 ms: 1.42x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 753 ms: 1.42x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 465 ms: 1.33x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.42x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.1 ms: 1.14x faster                                                       |
| pidigits       | 146 ms                                                      | 147 ms: 1.00x slower                                                        |
| nbody          | 71.0 ms                                                     | 75.2 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 92.5 ms: 1.11x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 15.5 ms: 1.03x slower                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.77 ms: 1.52x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 200 us: 1.30x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 140 us: 1.27x faster                                                        |
| unpickle             | 9.11 us                                                     | 8.14 us: 1.12x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 39.5 ms: 1.09x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.56 sec: 1.06x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 91.9 ms: 1.05x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.8 us: 1.03x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 65.1 ms: 1.01x slower                                                       |
| pickle               | 6.87 us                                                     | 6.94 us: 1.01x slower                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 56.9 ms: 1.04x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.2 us: 1.06x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.89 us: 1.07x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 18.0 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.12 ms: 1.26x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 98.7 us: 3.41x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.22 ms: 1.86x faster                                                       |
| mypy2                    | 347 ms                                                      | 217 ms: 1.60x faster                                                        |
| async_tree_none          | 424 ms                                                      | 278 ms: 1.52x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.77 ms: 1.52x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 477 ms: 1.50x faster                                                        |
| raytrace                 | 266 ms                                                      | 178 ms: 1.50x faster                                                        |
| logging_silent           | 93.4 ns                                                     | 62.9 ns: 1.49x faster                                                       |
| richards_super           | 50.3 ms                                                     | 34.2 ms: 1.47x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 57.6 ms: 1.46x faster                                                       |
| comprehensions           | 16.6 us                                                     | 11.4 us: 1.45x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 355 ms: 1.42x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 753 ms: 1.42x faster                                                        |
| crypto_pyaes             | 63.1 ms                                                     | 44.6 ms: 1.41x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 860 us: 1.40x faster                                                        |
| go                       | 135 ms                                                      | 97.3 ms: 1.39x faster                                                       |
| chaos                    | 59.5 ms                                                     | 43.1 ms: 1.38x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.6 ms: 1.36x faster                                                       |
| generators               | 31.8 ms                                                     | 23.3 ms: 1.36x faster                                                       |
| scimark_sor              | 105 ms                                                      | 77.6 ms: 1.36x faster                                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 1.08 ms: 1.34x faster                                                       |
| richards                 | 40.6 ms                                                     | 30.3 ms: 1.34x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 465 ms: 1.33x faster                                                        |
| pyflate                  | 402 ms                                                      | 306 ms: 1.31x faster                                                        |
| hexiom                   | 5.59 ms                                                     | 4.26 ms: 1.31x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 200 us: 1.30x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 140 us: 1.27x faster                                                        |
| mako                     | 8.98 ms                                                     | 7.12 ms: 1.26x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 63.5 ms: 1.24x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.57 us: 1.21x faster                                                       |
| sympy_sum                | 105 ms                                                      | 88.3 ms: 1.19x faster                                                       |
| tornado_http             | 106 ms                                                      | 89.4 ms: 1.18x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 25.0 us: 1.16x faster                                                       |
| chameleon                | 6.02 ms                                                     | 5.22 ms: 1.15x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.1 ms: 1.15x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.64 sec: 1.14x faster                                                      |
| float                    | 61.7 ms                                                     | 54.1 ms: 1.14x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.51 sec: 1.13x faster                                                      |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.86 sec: 1.12x faster                                                      |
| sympy_str                | 193 ms                                                      | 172 ms: 1.12x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.14 us: 1.12x faster                                                       |
| pycparser                | 905 ms                                                      | 813 ms: 1.11x faster                                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.10 sec: 1.11x faster                                                      |
| pprint_safe_repr         | 594 ms                                                      | 535 ms: 1.11x faster                                                        |
| regex_compile            | 102 ms                                                      | 92.5 ms: 1.11x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 725 us: 1.10x faster                                                        |
| nqueens                  | 68.3 ms                                                     | 61.9 ms: 1.10x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 833 us: 1.10x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 39.5 ms: 1.09x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 36.4 ms: 1.08x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 45.0 ms: 1.08x faster                                                       |
| sympy_expand             | 320 ms                                                      | 297 ms: 1.08x faster                                                        |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.49 ms: 1.07x faster                                                       |
| 2to3                     | 239 ms                                                      | 223 ms: 1.07x faster                                                        |
| coroutines               | 15.5 ms                                                     | 14.5 ms: 1.07x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 195 ms: 1.06x faster                                                        |
| tomli_loads              | 1.65 sec                                                    | 1.56 sec: 1.06x faster                                                      |
| deepcopy                 | 259 us                                                      | 246 us: 1.05x faster                                                        |
| xml_etree_parse          | 96.8 ms                                                     | 91.9 ms: 1.05x faster                                                       |
| scimark_fft              | 187 ms                                                      | 178 ms: 1.05x faster                                                        |
| json_loads               | 14.2 us                                                     | 13.8 us: 1.03x faster                                                       |
| unpack_sequence          | 40.0 ns                                                     | 38.7 ns: 1.03x faster                                                       |
| pidigits                 | 146 ms                                                      | 147 ms: 1.00x slower                                                        |
| xml_etree_iterparse      | 64.5 ms                                                     | 65.1 ms: 1.01x slower                                                       |
| pickle                   | 6.87 us                                                     | 6.94 us: 1.01x slower                                                       |
| fannkuch                 | 258 ms                                                      | 263 ms: 1.02x slower                                                        |
| regex_v8                 | 15.0 ms                                                     | 15.5 ms: 1.03x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 76.6 ms: 1.04x slower                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 56.9 ms: 1.04x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 63.1 ms: 1.05x slower                                                       |
| nbody                    | 71.0 ms                                                     | 75.2 ms: 1.06x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.2 us: 1.06x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.89 us: 1.07x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.83 us: 1.09x slower                                                       |
| async_generators         | 219 ms                                                      | 238 ms: 1.09x slower                                                        |
| logging_format           | 6.73 us                                                     | 7.33 us: 1.09x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 79.7 ms: 1.09x slower                                                       |
| coverage                 | 38.4 ms                                                     | 44.9 ms: 1.17x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.0 ms: 1.18x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.77 ms: 1.25x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.16x faster                                                                |

Benchmark hidden because not significant (4): json, deepcopy_reduce, unpickle_list, python_startup
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231030-3.13.0a1+-6dfb8fe/bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
