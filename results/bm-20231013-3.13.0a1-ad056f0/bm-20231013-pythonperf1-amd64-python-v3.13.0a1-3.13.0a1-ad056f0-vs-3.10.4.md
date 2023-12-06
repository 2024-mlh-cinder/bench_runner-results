
# Results vs. 3.10.4

- fork: python
- ref: v3.13.0a1
- machine: windows-amd64
- commit hash: ad056f0
- commit date: 2023-10-13
- overall geometric mean: 1.18x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 216 ms: 1.11x faster                                            |
| chameleon      | 6.02 ms                                                     | 4.98 ms: 1.21x faster                                           |
| docutils       | 1.88 sec                                                    | 1.61 sec: 1.17x faster                                          |
| tornado_http   | 106 ms                                                      | 89.1 ms: 1.19x faster                                           |
| Geometric mean | (ref)                                                       | 1.17x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 267 ms: 1.59x faster                                            |
| async_tree_memoization  | 505 ms                                                      | 340 ms: 1.49x faster                                            |
| async_tree_io           | 1.07 sec                                                    | 723 ms: 1.48x faster                                            |
| async_tree_cpu_io_mixed | 617 ms                                                      | 455 ms: 1.36x faster                                            |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 53.6 ms: 1.15x faster                                           |
| nbody          | 71.0 ms                                                     | 72.2 ms: 1.02x slower                                           |
| pidigits       | 146 ms                                                      | 150 ms: 1.03x slower                                            |
| Geometric mean | (ref)                                                       | 1.03x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 90.8 ms: 1.13x faster                                           |
| regex_dna      | 129 ms                                                      | 119 ms: 1.09x faster                                            |
| regex_v8       | 15.0 ms                                                     | 14.8 ms: 1.01x faster                                           |
| regex_effbot   | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                           |
| Geometric mean | (ref)                                                       | 1.05x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.60 ms: 1.56x faster                                           |
| pickle_pure_python   | 259 us                                                      | 190 us: 1.37x faster                                            |
| unpickle_pure_python | 177 us                                                      | 137 us: 1.29x faster                                            |
| xml_etree_process    | 43.1 ms                                                     | 38.2 ms: 1.13x faster                                           |
| unpickle             | 9.11 us                                                     | 8.12 us: 1.12x faster                                           |
| tomli_loads          | 1.65 sec                                                    | 1.48 sec: 1.12x faster                                          |
| xml_etree_parse      | 96.8 ms                                                     | 91.6 ms: 1.06x faster                                           |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                           |
| xml_etree_iterparse  | 64.5 ms                                                     | 64.0 ms: 1.01x faster                                           |
| pickle               | 6.87 us                                                     | 6.98 us: 1.02x slower                                           |
| xml_etree_generate   | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                           |
| pickle_dict          | 17.1 us                                                     | 18.4 us: 1.07x slower                                           |
| pickle_list          | 2.69 us                                                     | 2.94 us: 1.09x slower                                           |
| Geometric mean       | (ref)                                                       | 1.09x faster                                                    |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 16.2 ms: 1.06x slower                                           |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                    |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.20 ms: 1.25x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 96.3 us: 3.50x faster                                           |
| deltablue                | 4.12 ms                                                     | 2.19 ms: 1.88x faster                                           |
| mypy2                    | 347 ms                                                      | 209 ms: 1.66x faster                                            |
| async_tree_none          | 424 ms                                                      | 267 ms: 1.59x faster                                            |
| richards_super           | 50.3 ms                                                     | 32.0 ms: 1.57x faster                                           |
| json_dumps               | 8.77 ms                                                     | 5.60 ms: 1.56x faster                                           |
| raytrace                 | 266 ms                                                      | 174 ms: 1.53x faster                                            |
| asyncio_tcp              | 717 ms                                                      | 470 ms: 1.52x faster                                            |
| go                       | 135 ms                                                      | 90.0 ms: 1.50x faster                                           |
| async_tree_memoization   | 505 ms                                                      | 340 ms: 1.49x faster                                            |
| sqlglot_parse            | 1.20 ms                                                     | 811 us: 1.48x faster                                            |
| async_tree_io            | 1.07 sec                                                    | 723 ms: 1.48x faster                                            |
| logging_silent           | 93.4 ns                                                     | 63.2 ns: 1.48x faster                                           |
| chaos                    | 59.5 ms                                                     | 40.4 ms: 1.47x faster                                           |
| crypto_pyaes             | 63.1 ms                                                     | 43.3 ms: 1.46x faster                                           |
| scimark_lu               | 84.0 ms                                                     | 58.6 ms: 1.43x faster                                           |
| generators               | 31.8 ms                                                     | 22.3 ms: 1.42x faster                                           |
| scimark_monte_carlo      | 58.0 ms                                                     | 41.0 ms: 1.42x faster                                           |
| richards                 | 40.6 ms                                                     | 28.8 ms: 1.41x faster                                           |
| sqlglot_transpile        | 1.45 ms                                                     | 1.03 ms: 1.41x faster                                           |
| scimark_sor              | 105 ms                                                      | 77.0 ms: 1.37x faster                                           |
| pickle_pure_python       | 259 us                                                      | 190 us: 1.37x faster                                            |
| hexiom                   | 5.59 ms                                                     | 4.09 ms: 1.37x faster                                           |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 455 ms: 1.36x faster                                            |
| pyflate                  | 402 ms                                                      | 298 ms: 1.35x faster                                            |
| unpickle_pure_python     | 177 us                                                      | 137 us: 1.29x faster                                            |
| spectral_norm            | 78.9 ms                                                     | 63.0 ms: 1.25x faster                                           |
| mako                     | 8.98 ms                                                     | 7.20 ms: 1.25x faster                                           |
| chameleon                | 6.02 ms                                                     | 4.98 ms: 1.21x faster                                           |
| pprint_pformat           | 1.22 sec                                                    | 1.03 sec: 1.19x faster                                          |
| tornado_http             | 106 ms                                                      | 89.1 ms: 1.19x faster                                           |
| pprint_safe_repr         | 594 ms                                                      | 507 ms: 1.17x faster                                            |
| comprehensions           | 16.6 us                                                     | 14.2 us: 1.17x faster                                           |
| deepcopy_memo            | 29.0 us                                                     | 24.8 us: 1.17x faster                                           |
| docutils                 | 1.88 sec                                                    | 1.61 sec: 1.17x faster                                          |
| nqueens                  | 68.3 ms                                                     | 59.1 ms: 1.16x faster                                           |
| sympy_sum                | 105 ms                                                      | 91.1 ms: 1.16x faster                                           |
| float                    | 61.7 ms                                                     | 53.6 ms: 1.15x faster                                           |
| sqlite_synth             | 1.90 us                                                     | 1.65 us: 1.15x faster                                           |
| mdp                      | 1.71 sec                                                    | 1.49 sec: 1.15x faster                                          |
| sympy_integrate          | 15.0 ms                                                     | 13.1 ms: 1.14x faster                                           |
| sqlglot_optimize         | 39.4 ms                                                     | 34.8 ms: 1.13x faster                                           |
| deepcopy                 | 259 us                                                      | 230 us: 1.13x faster                                            |
| xml_etree_process        | 43.1 ms                                                     | 38.2 ms: 1.13x faster                                           |
| regex_compile            | 102 ms                                                      | 90.8 ms: 1.13x faster                                           |
| sqlglot_normalize        | 207 ms                                                      | 184 ms: 1.12x faster                                            |
| unpickle                 | 9.11 us                                                     | 8.12 us: 1.12x faster                                           |
| sympy_expand             | 320 ms                                                      | 287 ms: 1.12x faster                                            |
| tomli_loads              | 1.65 sec                                                    | 1.48 sec: 1.12x faster                                          |
| 2to3                     | 239 ms                                                      | 216 ms: 1.11x faster                                            |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.89 sec: 1.11x faster                                          |
| sympy_str                | 193 ms                                                      | 175 ms: 1.11x faster                                            |
| create_gc_cycles         | 800 us                                                      | 728 us: 1.10x faster                                            |
| bench_thread_pool        | 913 us                                                      | 836 us: 1.09x faster                                            |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.45 ms: 1.09x faster                                           |
| regex_dna                | 129 ms                                                      | 119 ms: 1.09x faster                                            |
| dulwich_log              | 48.6 ms                                                     | 45.2 ms: 1.08x faster                                           |
| deepcopy_reduce          | 2.22 us                                                     | 2.07 us: 1.07x faster                                           |
| scimark_fft              | 187 ms                                                      | 176 ms: 1.07x faster                                            |
| xml_etree_parse          | 96.8 ms                                                     | 91.6 ms: 1.06x faster                                           |
| coroutines               | 15.5 ms                                                     | 14.7 ms: 1.05x faster                                           |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                           |
| unpack_sequence          | 40.0 ns                                                     | 38.5 ns: 1.04x faster                                           |
| fannkuch                 | 258 ms                                                      | 249 ms: 1.03x faster                                            |
| regex_v8                 | 15.0 ms                                                     | 14.8 ms: 1.01x faster                                           |
| xml_etree_iterparse      | 64.5 ms                                                     | 64.0 ms: 1.01x faster                                           |
| meteor_contest           | 73.8 ms                                                     | 74.5 ms: 1.01x slower                                           |
| logging_format           | 6.73 us                                                     | 6.81 us: 1.01x slower                                           |
| pickle                   | 6.87 us                                                     | 6.98 us: 1.02x slower                                           |
| nbody                    | 71.0 ms                                                     | 72.2 ms: 1.02x slower                                           |
| xml_etree_generate       | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                           |
| logging_simple           | 6.28 us                                                     | 6.40 us: 1.02x slower                                           |
| regex_effbot             | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                           |
| pidigits                 | 146 ms                                                      | 150 ms: 1.03x slower                                            |
| python_startup_no_site   | 15.3 ms                                                     | 16.2 ms: 1.06x slower                                           |
| gc_traversal             | 1.40 ms                                                     | 1.49 ms: 1.06x slower                                           |
| bench_mp_pool            | 59.9 ms                                                     | 64.0 ms: 1.07x slower                                           |
| pickle_dict              | 17.1 us                                                     | 18.4 us: 1.07x slower                                           |
| async_generators         | 219 ms                                                      | 236 ms: 1.08x slower                                            |
| pathlib                  | 72.8 ms                                                     | 78.5 ms: 1.08x slower                                           |
| pickle_list              | 2.69 us                                                     | 2.94 us: 1.09x slower                                           |
| coverage                 | 38.4 ms                                                     | 45.4 ms: 1.18x slower                                           |
| telco                    | 3.82 ms                                                     | 4.73 ms: 1.24x slower                                           |
| Geometric mean           | (ref)                                                       | 1.18x faster                                                    |

Benchmark hidden because not significant (4): pycparser, json, python_startup, unpickle_list
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231013-3.13.0a1-ad056f0/bm-20231013-pythonperf1-amd64-python-v3.13.0a1-3.13.0a1-ad056f0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.12x
- 99% likely to have a speedup of 1.11x
