
# Results vs. 3.10.4

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: windows-amd64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 209 ms: 1.14x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.92 ms: 1.22x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.54 sec: 1.22x faster                                                      |
| tornado_http   | 106 ms                                                      | 86.1 ms: 1.23x faster                                                       |
| Geometric mean | (ref)                                                       | 1.20x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 265 ms: 1.60x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 339 ms: 1.49x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 724 ms: 1.48x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 451 ms: 1.37x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 53.1 ms: 1.16x faster                                                       |
| pidigits       | 146 ms                                                      | 147 ms: 1.00x slower                                                        |
| nbody          | 71.0 ms                                                     | 84.3 ms: 1.19x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 80.2 ms: 1.27x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 16.2 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.64 ms: 1.55x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 185 us: 1.40x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 132 us: 1.34x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 36.8 ms: 1.17x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.43 sec: 1.15x faster                                                      |
| unpickle             | 9.11 us                                                     | 8.21 us: 1.11x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 92.6 ms: 1.05x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.8 ms: 1.01x faster                                                       |
| pickle               | 6.87 us                                                     | 7.12 us: 1.04x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.3 us: 1.07x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.91 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_generate, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.5 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.45 ms: 1.39x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 74.3 us: 4.53x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.09 ms: 1.98x faster                                                       |
| richards_super           | 50.3 ms                                                     | 31.1 ms: 1.62x faster                                                       |
| async_tree_none          | 424 ms                                                      | 265 ms: 1.60x faster                                                        |
| logging_silent           | 93.4 ns                                                     | 58.5 ns: 1.60x faster                                                       |
| raytrace                 | 266 ms                                                      | 168 ms: 1.58x faster                                                        |
| comprehensions           | 16.6 us                                                     | 10.6 us: 1.57x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 767 us: 1.57x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.64 ms: 1.55x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 465 ms: 1.54x faster                                                        |
| go                       | 135 ms                                                      | 88.0 ms: 1.54x faster                                                       |
| generators               | 31.8 ms                                                     | 21.3 ms: 1.49x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 339 ms: 1.49x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 724 ms: 1.48x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 988 us: 1.46x faster                                                        |
| chaos                    | 59.5 ms                                                     | 41.1 ms: 1.45x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 58.3 ms: 1.44x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 44.4 ms: 1.42x faster                                                       |
| hexiom                   | 5.59 ms                                                     | 3.94 ms: 1.42x faster                                                       |
| richards                 | 40.6 ms                                                     | 28.8 ms: 1.41x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 185 us: 1.40x faster                                                        |
| mako                     | 8.98 ms                                                     | 6.45 ms: 1.39x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.3 ms: 1.37x faster                                                       |
| pyflate                  | 402 ms                                                      | 293 ms: 1.37x faster                                                        |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 451 ms: 1.37x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 132 us: 1.34x faster                                                        |
| scimark_sor              | 105 ms                                                      | 82.2 ms: 1.28x faster                                                       |
| regex_compile            | 102 ms                                                      | 80.2 ms: 1.27x faster                                                       |
| sympy_sum                | 105 ms                                                      | 82.8 ms: 1.27x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.35 sec: 1.27x faster                                                      |
| spectral_norm            | 78.9 ms                                                     | 63.8 ms: 1.24x faster                                                       |
| tornado_http             | 106 ms                                                      | 86.1 ms: 1.23x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.92 ms: 1.22x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.54 sec: 1.22x faster                                                      |
| sympy_str                | 193 ms                                                      | 158 ms: 1.22x faster                                                        |
| sympy_integrate          | 15.0 ms                                                     | 12.3 ms: 1.22x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.21x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 23.9 us: 1.21x faster                                                       |
| mypy2                    | 347 ms                                                      | 286 ms: 1.21x faster                                                        |
| dask                     | 305 ms                                                      | 253 ms: 1.21x faster                                                        |
| deepcopy                 | 259 us                                                      | 218 us: 1.19x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 40.8 ms: 1.19x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.03 sec: 1.19x faster                                                      |
| sympy_expand             | 320 ms                                                      | 271 ms: 1.18x faster                                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 33.5 ms: 1.18x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 506 ms: 1.17x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 176 ms: 1.17x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 36.8 ms: 1.17x faster                                                       |
| pycparser                | 905 ms                                                      | 773 ms: 1.17x faster                                                        |
| float                    | 61.7 ms                                                     | 53.1 ms: 1.16x faster                                                       |
| nqueens                  | 68.3 ms                                                     | 59.0 ms: 1.16x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.43 sec: 1.15x faster                                                      |
| 2to3                     | 239 ms                                                      | 209 ms: 1.14x faster                                                        |
| deepcopy_reduce          | 2.22 us                                                     | 1.98 us: 1.12x faster                                                       |
| unpickle                 | 9.11 us                                                     | 8.21 us: 1.11x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.90 sec: 1.10x faster                                                      |
| coroutines               | 15.5 ms                                                     | 14.1 ms: 1.10x faster                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.44 ms: 1.09x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 734 us: 1.09x faster                                                        |
| bench_thread_pool        | 913 us                                                      | 839 us: 1.09x faster                                                        |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| unpack_sequence          | 40.0 ns                                                     | 37.6 ns: 1.07x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| scimark_fft              | 187 ms                                                      | 177 ms: 1.06x faster                                                        |
| xml_etree_parse          | 96.8 ms                                                     | 92.6 ms: 1.05x faster                                                       |
| logging_simple           | 6.28 us                                                     | 6.18 us: 1.01x faster                                                       |
| logging_format           | 6.73 us                                                     | 6.64 us: 1.01x faster                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.8 ms: 1.01x faster                                                       |
| fannkuch                 | 258 ms                                                      | 256 ms: 1.01x faster                                                        |
| meteor_contest           | 73.8 ms                                                     | 73.5 ms: 1.01x faster                                                       |
| pidigits                 | 146 ms                                                      | 147 ms: 1.00x slower                                                        |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| async_generators         | 219 ms                                                      | 224 ms: 1.02x slower                                                        |
| pathlib                  | 72.8 ms                                                     | 75.2 ms: 1.03x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.12 us: 1.04x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 62.9 ms: 1.05x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.48 ms: 1.06x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.3 us: 1.07x slower                                                       |
| regex_v8                 | 15.0 ms                                                     | 16.2 ms: 1.08x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.91 us: 1.08x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 17.5 ms: 1.14x slower                                                       |
| coverage                 | 38.4 ms                                                     | 43.9 ms: 1.14x slower                                                       |
| nbody                    | 71.0 ms                                                     | 84.3 ms: 1.19x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.64 ms: 1.22x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.21x faster                                                                |

Benchmark hidden because not significant (4): json, xml_etree_generate, python_startup, unpickle_list
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231119-3.13.0a1+-1a969b4/bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.15x
