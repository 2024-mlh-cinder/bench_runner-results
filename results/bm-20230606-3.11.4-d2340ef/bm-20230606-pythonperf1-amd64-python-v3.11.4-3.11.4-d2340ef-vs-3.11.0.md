
# Results vs. 3.11.0

- fork: python
- ref: v3.11.4
- machine: windows-amd64
- commit hash: d2340ef
- commit date: 2023-06-06
- overall geometric mean: 1.04x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 221 ms: 1.07x slower                                        |
| chameleon      | 5.35 ms                                                     | 5.44 ms: 1.02x slower                                       |
| docutils       | 1.59 sec                                                    | 1.66 sec: 1.05x slower                                      |
| html5lib       | 38.6 ms                                                     | 39.4 ms: 1.02x slower                                       |
| tornado_http   | 89.9 ms                                                     | 103 ms: 1.15x slower                                        |
| Geometric mean | (ref)                                                       | 1.06x slower                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|-------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 495 ms                                                      | 522 ms: 1.06x slower                                        |
| async_tree_none         | 314 ms                                                      | 334 ms: 1.07x slower                                        |
| async_tree_memoization  | 367 ms                                                      | 392 ms: 1.07x slower                                        |
| async_tree_io           | 753 ms                                                      | 813 ms: 1.08x slower                                        |
| Geometric mean          | (ref)                                                       | 1.07x slower                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 70.4 ms: 1.02x slower                                       |
| pidigits       | 149 ms                                                      | 151 ms: 1.02x slower                                        |
| float          | 54.4 ms                                                     | 56.7 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                        |
| regex_v8       | 13.7 ms                                                     | 13.9 ms: 1.02x slower                                       |
| regex_compile  | 90.8 ms                                                     | 92.8 ms: 1.02x slower                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|---------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python  | 207 us                                                      | 201 us: 1.03x faster                                        |
| tomli_loads         | 1.42 sec                                                    | 1.43 sec: 1.01x slower                                      |
| xml_etree_parse     | 94.5 ms                                                     | 96.4 ms: 1.02x slower                                       |
| xml_etree_process   | 37.0 ms                                                     | 37.9 ms: 1.02x slower                                       |
| json_loads          | 12.9 us                                                     | 13.3 us: 1.03x slower                                       |
| xml_etree_iterparse | 63.0 ms                                                     | 64.8 ms: 1.03x slower                                       |
| xml_etree_generate  | 52.2 ms                                                     | 53.8 ms: 1.03x slower                                       |
| pickle              | 6.53 us                                                     | 6.74 us: 1.03x slower                                       |
| pickle_list         | 2.68 us                                                     | 2.78 us: 1.04x slower                                       |
| unpickle            | 7.82 us                                                     | 8.15 us: 1.04x slower                                       |
| pickle_dict         | 17.8 us                                                     | 18.8 us: 1.06x slower                                       |
| unpickle_list       | 2.57 us                                                     | 2.73 us: 1.06x slower                                       |
| Geometric mean      | (ref)                                                       | 1.02x slower                                                |

Benchmark hidden because not significant (2): unpickle_pure_python, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.6 ms: 1.10x slower                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.5 ms: 1.13x slower                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| genshi_xml      | 40.5 ms                                                     | 38.6 ms: 1.05x faster                                       |
| mako            | 7.55 ms                                                     | 7.67 ms: 1.02x slower                                       |
| django_template | 24.0 ms                                                     | 24.5 ms: 1.02x slower                                       |
| Geometric mean  | (ref)                                                       | 1.00x faster                                                |

Benchmark hidden because not significant (1): genshi_text

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| genshi_xml               | 40.5 ms                                                     | 38.6 ms: 1.05x faster                                       |
| thrift                   | 501 us                                                      | 486 us: 1.03x faster                                        |
| pickle_pure_python       | 207 us                                                      | 201 us: 1.03x faster                                        |
| sqlite_synth             | 1.79 us                                                     | 1.76 us: 1.02x faster                                       |
| raytrace                 | 211 ms                                                      | 208 ms: 1.02x faster                                        |
| nqueens                  | 66.1 ms                                                     | 65.1 ms: 1.02x faster                                       |
| sqlalchemy_declarative   | 83.9 ms                                                     | 82.7 ms: 1.01x faster                                       |
| regex_dna                | 121 ms                                                      | 120 ms: 1.01x faster                                        |
| pprint_safe_repr         | 519 ms                                                      | 513 ms: 1.01x faster                                        |
| pprint_pformat           | 1.06 sec                                                    | 1.05 sec: 1.01x faster                                      |
| sqlalchemy_imperative    | 10.5 ms                                                     | 10.4 ms: 1.01x faster                                       |
| sqlglot_optimize         | 35.1 ms                                                     | 35.2 ms: 1.01x slower                                       |
| flaskblogging            | 2.03 sec                                                    | 2.05 sec: 1.01x slower                                      |
| scimark_sparse_mat_mult  | 2.59 ms                                                     | 2.60 ms: 1.01x slower                                       |
| richards                 | 30.8 ms                                                     | 31.0 ms: 1.01x slower                                       |
| scimark_sor              | 76.4 ms                                                     | 76.9 ms: 1.01x slower                                       |
| sqlglot_normalize        | 191 ms                                                      | 193 ms: 1.01x slower                                        |
| hexiom                   | 4.51 ms                                                     | 4.55 ms: 1.01x slower                                       |
| deepcopy_reduce          | 2.07 us                                                     | 2.09 us: 1.01x slower                                       |
| tomli_loads              | 1.42 sec                                                    | 1.43 sec: 1.01x slower                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 45.1 ms: 1.01x slower                                       |
| coroutines               | 14.7 ms                                                     | 14.8 ms: 1.01x slower                                       |
| scimark_fft              | 181 ms                                                      | 184 ms: 1.01x slower                                        |
| deepcopy                 | 242 us                                                      | 246 us: 1.01x slower                                        |
| generators               | 34.0 ms                                                     | 34.5 ms: 1.02x slower                                       |
| chameleon                | 5.35 ms                                                     | 5.44 ms: 1.02x slower                                       |
| sympy_str                | 184 ms                                                      | 187 ms: 1.02x slower                                        |
| regex_v8                 | 13.7 ms                                                     | 13.9 ms: 1.02x slower                                       |
| mako                     | 7.55 ms                                                     | 7.67 ms: 1.02x slower                                       |
| sympy_integrate          | 13.7 ms                                                     | 13.9 ms: 1.02x slower                                       |
| go                       | 98.8 ms                                                     | 100 ms: 1.02x slower                                        |
| logging_simple           | 6.60 us                                                     | 6.71 us: 1.02x slower                                       |
| nbody                    | 69.3 ms                                                     | 70.4 ms: 1.02x slower                                       |
| pidigits                 | 149 ms                                                      | 151 ms: 1.02x slower                                        |
| scimark_lu               | 62.3 ms                                                     | 63.4 ms: 1.02x slower                                       |
| pyflate                  | 305 ms                                                      | 310 ms: 1.02x slower                                        |
| mdp                      | 1.73 sec                                                    | 1.76 sec: 1.02x slower                                      |
| telco                    | 3.93 ms                                                     | 4.00 ms: 1.02x slower                                       |
| django_template          | 24.0 ms                                                     | 24.5 ms: 1.02x slower                                       |
| richards_super           | 37.9 ms                                                     | 38.6 ms: 1.02x slower                                       |
| typing_runtime_protocols | 320 us                                                      | 326 us: 1.02x slower                                        |
| xml_etree_parse          | 94.5 ms                                                     | 96.4 ms: 1.02x slower                                       |
| logging_silent           | 70.7 ns                                                     | 72.1 ns: 1.02x slower                                       |
| async_generators         | 181 ms                                                      | 184 ms: 1.02x slower                                        |
| regex_compile            | 90.8 ms                                                     | 92.8 ms: 1.02x slower                                       |
| html5lib                 | 38.6 ms                                                     | 39.4 ms: 1.02x slower                                       |
| xml_etree_process        | 37.0 ms                                                     | 37.9 ms: 1.02x slower                                       |
| unpack_sequence          | 47.0 ns                                                     | 48.1 ns: 1.02x slower                                       |
| logging_format           | 7.06 us                                                     | 7.26 us: 1.03x slower                                       |
| sympy_sum                | 100.0 ms                                                    | 103 ms: 1.03x slower                                        |
| json_loads               | 12.9 us                                                     | 13.3 us: 1.03x slower                                       |
| xml_etree_iterparse      | 63.0 ms                                                     | 64.8 ms: 1.03x slower                                       |
| pycparser                | 705 ms                                                      | 726 ms: 1.03x slower                                        |
| crypto_pyaes             | 48.2 ms                                                     | 49.7 ms: 1.03x slower                                       |
| xml_etree_generate       | 52.2 ms                                                     | 53.8 ms: 1.03x slower                                       |
| meteor_contest           | 75.0 ms                                                     | 77.4 ms: 1.03x slower                                       |
| pickle                   | 6.53 us                                                     | 6.74 us: 1.03x slower                                       |
| deltablue                | 2.63 ms                                                     | 2.71 ms: 1.03x slower                                       |
| pickle_list              | 2.68 us                                                     | 2.78 us: 1.04x slower                                       |
| float                    | 54.4 ms                                                     | 56.7 ms: 1.04x slower                                       |
| unpickle                 | 7.82 us                                                     | 8.15 us: 1.04x slower                                       |
| gc_traversal             | 1.46 ms                                                     | 1.52 ms: 1.04x slower                                       |
| chaos                    | 46.8 ms                                                     | 48.8 ms: 1.04x slower                                       |
| pylint                   | 317 ms                                                      | 331 ms: 1.04x slower                                        |
| docutils                 | 1.59 sec                                                    | 1.66 sec: 1.05x slower                                      |
| create_gc_cycles         | 706 us                                                      | 740 us: 1.05x slower                                        |
| dulwich_log              | 44.1 ms                                                     | 46.4 ms: 1.05x slower                                       |
| async_tree_cpu_io_mixed  | 495 ms                                                      | 522 ms: 1.06x slower                                        |
| pickle_dict              | 17.8 us                                                     | 18.8 us: 1.06x slower                                       |
| fannkuch                 | 248 ms                                                      | 263 ms: 1.06x slower                                        |
| unpickle_list            | 2.57 us                                                     | 2.73 us: 1.06x slower                                       |
| 2to3                     | 207 ms                                                      | 221 ms: 1.07x slower                                        |
| async_tree_none          | 314 ms                                                      | 334 ms: 1.07x slower                                        |
| async_tree_memoization   | 367 ms                                                      | 392 ms: 1.07x slower                                        |
| spectral_norm            | 69.9 ms                                                     | 74.7 ms: 1.07x slower                                       |
| async_tree_io            | 753 ms                                                      | 813 ms: 1.08x slower                                        |
| bench_mp_pool            | 61.1 ms                                                     | 66.1 ms: 1.08x slower                                       |
| dask                     | 262 ms                                                      | 287 ms: 1.09x slower                                        |
| python_startup           | 18.8 ms                                                     | 20.6 ms: 1.10x slower                                       |
| aiohttp                  | 854 us                                                      | 936 us: 1.10x slower                                        |
| bench_thread_pool        | 847 us                                                      | 941 us: 1.11x slower                                        |
| pathlib                  | 69.4 ms                                                     | 77.5 ms: 1.12x slower                                       |
| python_startup_no_site   | 15.5 ms                                                     | 17.5 ms: 1.13x slower                                       |
| tornado_http             | 89.9 ms                                                     | 103 ms: 1.15x slower                                        |
| json                     | 2.99 ms                                                     | 3.51 ms: 1.17x slower                                       |
| asyncio_tcp_ssl          | 2.02 sec                                                    | 2.41 sec: 1.19x slower                                      |
| mypy2                    | 226 ms                                                      | 290 ms: 1.28x slower                                        |
| coverage                 | 43.0 ms                                                     | 55.6 ms: 1.29x slower                                       |
| asyncio_tcp              | 614 ms                                                      | 932 ms: 1.52x slower                                        |
| Geometric mean           | (ref)                                                       | 1.04x slower                                                |

Benchmark hidden because not significant (9): sqlglot_parse, regex_effbot, sqlglot_transpile, unpickle_pure_python, sympy_expand, json_dumps, comprehensions, genshi_text, deepcopy_memo
Ignored benchmarks (4) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
