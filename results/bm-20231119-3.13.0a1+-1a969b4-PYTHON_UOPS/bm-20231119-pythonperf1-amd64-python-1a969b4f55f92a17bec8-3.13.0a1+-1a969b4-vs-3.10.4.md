
# Results vs. 3.10.4

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: windows-amd64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.13x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 226 ms: 1.06x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.10 ms: 1.18x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.60 sec: 1.17x faster                                                      |
| tornado_http   | 106 ms                                                      | 90.3 ms: 1.17x faster                                                       |
| Geometric mean | (ref)                                                       | 1.14x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 280 ms: 1.52x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 746 ms: 1.43x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 354 ms: 1.43x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 466 ms: 1.32x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.42x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| float          | 61.7 ms                                                     | 62.2 ms: 1.01x slower                                                       |
| nbody          | 71.0 ms                                                     | 85.7 ms: 1.21x slower                                                       |
| Geometric mean | (ref)                                                       | 1.07x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 94.4 ms: 1.08x faster                                                       |
| regex_dna      | 129 ms                                                      | 120 ms: 1.07x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.59 ms: 1.02x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 18.9 ms: 1.25x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.76 ms: 1.52x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 187 us: 1.39x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 147 us: 1.21x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 38.4 ms: 1.12x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.42 us: 1.08x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.53 sec: 1.08x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 91.3 ms: 1.06x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.06x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 65.4 ms: 1.01x slower                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.4 us: 1.07x slower                                                       |
| pickle_list          | 2.69 us                                                     | 3.12 us: 1.16x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (2): unpickle_list, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.1 ms: 1.02x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.5 ms: 1.21x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 8.46 ms: 1.06x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 82.7 us: 4.07x faster                                                       |
| richards_super           | 50.3 ms                                                     | 31.4 ms: 1.60x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 58.4 ns: 1.60x faster                                                       |
| json_dumps               | 8.77 ms                                                     | 5.76 ms: 1.52x faster                                                       |
| async_tree_none          | 424 ms                                                      | 280 ms: 1.52x faster                                                        |
| asyncio_tcp              | 717 ms                                                      | 473 ms: 1.52x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 805 us: 1.50x faster                                                        |
| generators               | 31.8 ms                                                     | 21.7 ms: 1.46x faster                                                       |
| richards                 | 40.6 ms                                                     | 28.2 ms: 1.44x faster                                                       |
| async_tree_io            | 1.07 sec                                                    | 746 ms: 1.43x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 354 ms: 1.43x faster                                                        |
| raytrace                 | 266 ms                                                      | 187 ms: 1.42x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.03 ms: 1.40x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.96 ms: 1.39x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 187 us: 1.39x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 60.9 ms: 1.38x faster                                                       |
| go                       | 135 ms                                                      | 99.8 ms: 1.36x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 466 ms: 1.32x faster                                                        |
| pycparser                | 905 ms                                                      | 696 ms: 1.30x faster                                                        |
| chaos                    | 59.5 ms                                                     | 47.7 ms: 1.25x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 63.3 ms: 1.25x faster                                                       |
| scimark_sor              | 105 ms                                                      | 85.0 ms: 1.24x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 51.6 ms: 1.22x faster                                                       |
| sympy_sum                | 105 ms                                                      | 86.7 ms: 1.21x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 147 us: 1.21x faster                                                        |
| pyflate                  | 402 ms                                                      | 336 ms: 1.20x faster                                                        |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.76 sec: 1.19x faster                                                      |
| sqlite_synth             | 1.90 us                                                     | 1.60 us: 1.19x faster                                                       |
| dask                     | 305 ms                                                      | 258 ms: 1.18x faster                                                        |
| chameleon                | 6.02 ms                                                     | 5.10 ms: 1.18x faster                                                       |
| mypy2                    | 347 ms                                                      | 294 ms: 1.18x faster                                                        |
| deepcopy_memo            | 29.0 us                                                     | 24.6 us: 1.18x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.60 sec: 1.17x faster                                                      |
| tornado_http             | 106 ms                                                      | 90.3 ms: 1.17x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 50.3 ms: 1.15x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 34.3 ms: 1.15x faster                                                       |
| deepcopy                 | 259 us                                                      | 226 us: 1.15x faster                                                        |
| sympy_str                | 193 ms                                                      | 169 ms: 1.14x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 181 ms: 1.14x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 42.8 ms: 1.13x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.52 sec: 1.13x faster                                                      |
| xml_etree_process        | 43.1 ms                                                     | 38.4 ms: 1.12x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 1.99 us: 1.11x faster                                                       |
| sympy_expand             | 320 ms                                                      | 288 ms: 1.11x faster                                                        |
| coroutines               | 15.5 ms                                                     | 13.9 ms: 1.11x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                                       |
| comprehensions           | 16.6 us                                                     | 15.0 us: 1.11x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 733 us: 1.09x faster                                                        |
| pprint_safe_repr         | 594 ms                                                      | 545 ms: 1.09x faster                                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.13 sec: 1.09x faster                                                      |
| regex_compile            | 102 ms                                                      | 94.4 ms: 1.08x faster                                                       |
| unpickle                 | 9.11 us                                                     | 8.42 us: 1.08x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.53 sec: 1.08x faster                                                      |
| regex_dna                | 129 ms                                                      | 120 ms: 1.07x faster                                                        |
| mako                     | 8.98 ms                                                     | 8.46 ms: 1.06x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 91.3 ms: 1.06x faster                                                       |
| 2to3                     | 239 ms                                                      | 226 ms: 1.06x faster                                                        |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.06x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 869 us: 1.05x faster                                                        |
| unpack_sequence          | 40.0 ns                                                     | 39.1 ns: 1.02x faster                                                       |
| pidigits                 | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| hexiom                   | 5.59 ms                                                     | 5.63 ms: 1.01x slower                                                       |
| float                    | 61.7 ms                                                     | 62.2 ms: 1.01x slower                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 65.4 ms: 1.01x slower                                                       |
| logging_format           | 6.73 us                                                     | 6.83 us: 1.01x slower                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.59 ms: 1.02x slower                                                       |
| nqueens                  | 68.3 ms                                                     | 69.7 ms: 1.02x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.1 ms: 1.02x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 75.4 ms: 1.03x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.50 us: 1.04x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 79.0 ms: 1.07x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.4 us: 1.07x slower                                                       |
| async_generators         | 219 ms                                                      | 236 ms: 1.08x slower                                                        |
| gc_traversal             | 1.40 ms                                                     | 1.51 ms: 1.08x slower                                                       |
| fannkuch                 | 258 ms                                                      | 284 ms: 1.10x slower                                                        |
| bench_mp_pool            | 59.9 ms                                                     | 66.7 ms: 1.11x slower                                                       |
| pickle_list              | 2.69 us                                                     | 3.12 us: 1.16x slower                                                       |
| coverage                 | 38.4 ms                                                     | 44.6 ms: 1.16x slower                                                       |
| nbody                    | 71.0 ms                                                     | 85.7 ms: 1.21x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.5 ms: 1.21x slower                                                       |
| scimark_fft              | 187 ms                                                      | 228 ms: 1.22x slower                                                        |
| regex_v8                 | 15.0 ms                                                     | 18.9 ms: 1.25x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.94 ms: 1.29x slower                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 3.47 ms: 1.30x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.13x faster                                                                |

Benchmark hidden because not significant (3): json, unpickle_list, pickle
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231119-3.13.0a1+-1a969b4-PYTHON_UOPS/bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
