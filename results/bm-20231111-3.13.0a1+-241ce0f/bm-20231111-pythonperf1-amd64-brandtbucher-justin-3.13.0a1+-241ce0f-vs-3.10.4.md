
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.20x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 217 ms: 1.10x faster                                                |
| chameleon      | 6.02 ms                                                     | 4.89 ms: 1.23x faster                                               |
| docutils       | 1.88 sec                                                    | 1.56 sec: 1.20x faster                                              |
| tornado_http   | 106 ms                                                      | 88.0 ms: 1.20x faster                                               |
| Geometric mean | (ref)                                                       | 1.18x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 270 ms: 1.57x faster                                                |
| async_tree_memoization  | 505 ms                                                      | 343 ms: 1.47x faster                                                |
| async_tree_io           | 1.07 sec                                                    | 730 ms: 1.47x faster                                                |
| async_tree_cpu_io_mixed | 617 ms                                                      | 453 ms: 1.36x faster                                                |
| Geometric mean          | (ref)                                                       | 1.47x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 52.8 ms: 1.17x faster                                               |
| pidigits       | 146 ms                                                      | 150 ms: 1.03x slower                                                |
| nbody          | 71.0 ms                                                     | 73.1 ms: 1.03x slower                                               |
| Geometric mean | (ref)                                                       | 1.03x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 82.2 ms: 1.24x faster                                               |
| regex_dna      | 129 ms                                                      | 119 ms: 1.08x faster                                                |
| regex_v8       | 15.0 ms                                                     | 14.7 ms: 1.02x faster                                               |
| regex_effbot   | 1.56 ms                                                     | 1.56 ms: 1.00x faster                                               |
| Geometric mean | (ref)                                                       | 1.08x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.72 ms: 1.53x faster                                               |
| pickle_pure_python   | 259 us                                                      | 183 us: 1.42x faster                                                |
| unpickle_pure_python | 177 us                                                      | 136 us: 1.30x faster                                                |
| tomli_loads          | 1.65 sec                                                    | 1.34 sec: 1.23x faster                                              |
| xml_etree_process    | 43.1 ms                                                     | 37.0 ms: 1.16x faster                                               |
| unpickle             | 9.11 us                                                     | 8.15 us: 1.12x faster                                               |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                               |
| xml_etree_parse      | 96.8 ms                                                     | 92.8 ms: 1.04x faster                                               |
| pickle               | 6.87 us                                                     | 7.22 us: 1.05x slower                                               |
| pickle_dict          | 17.1 us                                                     | 18.3 us: 1.07x slower                                               |
| pickle_list          | 2.69 us                                                     | 2.88 us: 1.07x slower                                               |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                        |

Benchmark hidden because not significant (3): unpickle_list, xml_etree_generate, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.7 ms: 1.05x slower                                               |
| python_startup_no_site | 15.3 ms                                                     | 18.9 ms: 1.23x slower                                               |
| Geometric mean         | (ref)                                                       | 1.14x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.59 ms: 1.36x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 76.5 us: 4.40x faster                                               |
| deltablue                | 4.12 ms                                                     | 2.17 ms: 1.90x faster                                               |
| richards_super           | 50.3 ms                                                     | 29.3 ms: 1.72x faster                                               |
| logging_silent           | 93.4 ns                                                     | 55.2 ns: 1.69x faster                                               |
| raytrace                 | 266 ms                                                      | 168 ms: 1.58x faster                                                |
| async_tree_none          | 424 ms                                                      | 270 ms: 1.57x faster                                                |
| sqlglot_parse            | 1.20 ms                                                     | 771 us: 1.56x faster                                                |
| richards                 | 40.6 ms                                                     | 26.2 ms: 1.55x faster                                               |
| generators               | 31.8 ms                                                     | 20.7 ms: 1.54x faster                                               |
| json_dumps               | 8.77 ms                                                     | 5.72 ms: 1.53x faster                                               |
| asyncio_tcp              | 717 ms                                                      | 476 ms: 1.51x faster                                                |
| go                       | 135 ms                                                      | 91.3 ms: 1.48x faster                                               |
| async_tree_memoization   | 505 ms                                                      | 343 ms: 1.47x faster                                                |
| async_tree_io            | 1.07 sec                                                    | 730 ms: 1.47x faster                                                |
| sqlglot_transpile        | 1.45 ms                                                     | 990 us: 1.46x faster                                                |
| scimark_lu               | 84.0 ms                                                     | 59.2 ms: 1.42x faster                                               |
| pickle_pure_python       | 259 us                                                      | 183 us: 1.42x faster                                                |
| comprehensions           | 16.6 us                                                     | 11.8 us: 1.41x faster                                               |
| chaos                    | 59.5 ms                                                     | 42.3 ms: 1.41x faster                                               |
| crypto_pyaes             | 63.1 ms                                                     | 45.6 ms: 1.38x faster                                               |
| mako                     | 8.98 ms                                                     | 6.59 ms: 1.36x faster                                               |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 453 ms: 1.36x faster                                                |
| pyflate                  | 402 ms                                                      | 301 ms: 1.34x faster                                                |
| scimark_monte_carlo      | 58.0 ms                                                     | 44.1 ms: 1.32x faster                                               |
| unpickle_pure_python     | 177 us                                                      | 136 us: 1.30x faster                                                |
| scimark_sor              | 105 ms                                                      | 81.4 ms: 1.29x faster                                               |
| pycparser                | 905 ms                                                      | 712 ms: 1.27x faster                                                |
| spectral_norm            | 78.9 ms                                                     | 62.6 ms: 1.26x faster                                               |
| sympy_sum                | 105 ms                                                      | 84.4 ms: 1.25x faster                                               |
| deepcopy_memo            | 29.0 us                                                     | 23.2 us: 1.25x faster                                               |
| regex_compile            | 102 ms                                                      | 82.2 ms: 1.24x faster                                               |
| tomli_loads              | 1.65 sec                                                    | 1.34 sec: 1.23x faster                                              |
| chameleon                | 6.02 ms                                                     | 4.89 ms: 1.23x faster                                               |
| hexiom                   | 5.59 ms                                                     | 4.56 ms: 1.23x faster                                               |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.21x faster                                               |
| mdp                      | 1.71 sec                                                    | 1.41 sec: 1.21x faster                                              |
| docutils                 | 1.88 sec                                                    | 1.56 sec: 1.20x faster                                              |
| tornado_http             | 106 ms                                                      | 88.0 ms: 1.20x faster                                               |
| sympy_str                | 193 ms                                                      | 162 ms: 1.20x faster                                                |
| pprint_pformat           | 1.22 sec                                                    | 1.02 sec: 1.20x faster                                              |
| mypy2                    | 347 ms                                                      | 292 ms: 1.19x faster                                                |
| dulwich_log              | 48.6 ms                                                     | 41.3 ms: 1.18x faster                                               |
| sqlglot_optimize         | 39.4 ms                                                     | 33.7 ms: 1.17x faster                                               |
| float                    | 61.7 ms                                                     | 52.8 ms: 1.17x faster                                               |
| sympy_expand             | 320 ms                                                      | 274 ms: 1.17x faster                                                |
| pprint_safe_repr         | 594 ms                                                      | 508 ms: 1.17x faster                                                |
| deepcopy                 | 259 us                                                      | 222 us: 1.17x faster                                                |
| xml_etree_process        | 43.1 ms                                                     | 37.0 ms: 1.16x faster                                               |
| sqlglot_normalize        | 207 ms                                                      | 178 ms: 1.16x faster                                                |
| sympy_integrate          | 15.0 ms                                                     | 12.9 ms: 1.16x faster                                               |
| coroutines               | 15.5 ms                                                     | 13.5 ms: 1.14x faster                                               |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.86 sec: 1.13x faster                                              |
| deepcopy_reduce          | 2.22 us                                                     | 1.98 us: 1.12x faster                                               |
| unpickle                 | 9.11 us                                                     | 8.15 us: 1.12x faster                                               |
| create_gc_cycles         | 800 us                                                      | 724 us: 1.10x faster                                                |
| 2to3                     | 239 ms                                                      | 217 ms: 1.10x faster                                                |
| regex_dna                | 129 ms                                                      | 119 ms: 1.08x faster                                                |
| bench_thread_pool        | 913 us                                                      | 847 us: 1.08x faster                                                |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.49 ms: 1.07x faster                                               |
| nqueens                  | 68.3 ms                                                     | 64.1 ms: 1.07x faster                                               |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                               |
| json                     | 3.10 ms                                                     | 2.95 ms: 1.05x faster                                               |
| xml_etree_parse          | 96.8 ms                                                     | 92.8 ms: 1.04x faster                                               |
| regex_v8                 | 15.0 ms                                                     | 14.7 ms: 1.02x faster                                               |
| fannkuch                 | 258 ms                                                      | 253 ms: 1.02x faster                                                |
| logging_format           | 6.73 us                                                     | 6.63 us: 1.01x faster                                               |
| logging_simple           | 6.28 us                                                     | 6.23 us: 1.01x faster                                               |
| regex_effbot             | 1.56 ms                                                     | 1.56 ms: 1.00x faster                                               |
| pidigits                 | 146 ms                                                      | 150 ms: 1.03x slower                                                |
| nbody                    | 71.0 ms                                                     | 73.1 ms: 1.03x slower                                               |
| meteor_contest           | 73.8 ms                                                     | 76.0 ms: 1.03x slower                                               |
| pickle                   | 6.87 us                                                     | 7.22 us: 1.05x slower                                               |
| python_startup           | 19.7 ms                                                     | 20.7 ms: 1.05x slower                                               |
| pickle_dict              | 17.1 us                                                     | 18.3 us: 1.07x slower                                               |
| pickle_list              | 2.69 us                                                     | 2.88 us: 1.07x slower                                               |
| async_generators         | 219 ms                                                      | 235 ms: 1.08x slower                                                |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.08x slower                                               |
| bench_mp_pool            | 59.9 ms                                                     | 64.7 ms: 1.08x slower                                               |
| pathlib                  | 72.8 ms                                                     | 79.0 ms: 1.08x slower                                               |
| unpack_sequence          | 40.0 ns                                                     | 44.4 ns: 1.11x slower                                               |
| telco                    | 3.82 ms                                                     | 4.59 ms: 1.20x slower                                               |
| coverage                 | 38.4 ms                                                     | 46.7 ms: 1.22x slower                                               |
| python_startup_no_site   | 15.3 ms                                                     | 18.9 ms: 1.23x slower                                               |
| Geometric mean           | (ref)                                                       | 1.20x faster                                                        |

Benchmark hidden because not significant (4): unpickle_list, xml_etree_generate, scimark_fft, xml_etree_iterparse
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-241ce0f/bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.14x
