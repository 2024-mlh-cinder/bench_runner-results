
# Results vs. 3.10.4

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 48b46e7
- commit date: 2023-11-17
- overall geometric mean: 1.24x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 207 ms: 1.15x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.67 ms: 1.29x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.53 sec: 1.23x faster                                                      |
| tornado_http   | 106 ms                                                      | 85.6 ms: 1.23x faster                                                       |
| Geometric mean | (ref)                                                       | 1.23x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 262 ms: 1.62x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 338 ms: 1.49x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 724 ms: 1.48x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 445 ms: 1.39x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.49x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 51.0 ms: 1.21x faster                                                       |
| nbody          | 71.0 ms                                                     | 66.3 ms: 1.07x faster                                                       |
| Geometric mean | (ref)                                                       | 1.09x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 77.5 ms: 1.32x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.06x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 15.3 ms: 1.02x slower                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.08x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.48 ms: 1.60x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 172 us: 1.50x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 123 us: 1.44x faster                                                        |
| tomli_loads          | 1.65 sec                                                    | 1.37 sec: 1.21x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 35.9 ms: 1.20x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.45 us: 1.08x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 91.7 ms: 1.06x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 52.3 ms: 1.04x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 62.5 ms: 1.03x faster                                                       |
| pickle               | 6.87 us                                                     | 6.95 us: 1.01x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.82 us: 1.05x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.5 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.13x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.7 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.36 ms: 1.41x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 73.6 us: 4.58x faster                                                       |
| deltablue                | 4.12 ms                                                     | 1.98 ms: 2.08x faster                                                       |
| richards_super           | 50.3 ms                                                     | 28.8 ms: 1.75x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 54.0 ns: 1.73x faster                                                       |
| comprehensions           | 16.6 us                                                     | 9.92 us: 1.67x faster                                                       |
| raytrace                 | 266 ms                                                      | 161 ms: 1.65x faster                                                        |
| go                       | 135 ms                                                      | 82.4 ms: 1.64x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 741 us: 1.63x faster                                                        |
| async_tree_none          | 424 ms                                                      | 262 ms: 1.62x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.48 ms: 1.60x faster                                                       |
| richards                 | 40.6 ms                                                     | 25.7 ms: 1.58x faster                                                       |
| generators               | 31.8 ms                                                     | 20.2 ms: 1.57x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 53.5 ms: 1.57x faster                                                       |
| chaos                    | 59.5 ms                                                     | 38.0 ms: 1.57x faster                                                       |
| hexiom                   | 5.59 ms                                                     | 3.64 ms: 1.53x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 41.3 ms: 1.53x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 471 ms: 1.52x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 955 us: 1.51x faster                                                        |
| pickle_pure_python       | 259 us                                                      | 172 us: 1.50x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 338 ms: 1.49x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 724 ms: 1.48x faster                                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 40.2 ms: 1.45x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 123 us: 1.44x faster                                                        |
| pyflate                  | 402 ms                                                      | 279 ms: 1.44x faster                                                        |
| mako                     | 8.98 ms                                                     | 6.36 ms: 1.41x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 445 ms: 1.39x faster                                                        |
| scimark_sor              | 105 ms                                                      | 77.5 ms: 1.36x faster                                                       |
| regex_compile            | 102 ms                                                      | 77.5 ms: 1.32x faster                                                       |
| sympy_sum                | 105 ms                                                      | 80.2 ms: 1.31x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.67 ms: 1.29x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 22.6 us: 1.28x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 61.9 ms: 1.28x faster                                                       |
| pycparser                | 905 ms                                                      | 714 ms: 1.27x faster                                                        |
| pprint_pformat           | 1.22 sec                                                    | 966 ms: 1.27x faster                                                        |
| sympy_str                | 193 ms                                                      | 154 ms: 1.25x faster                                                        |
| pprint_safe_repr         | 594 ms                                                      | 474 ms: 1.25x faster                                                        |
| sympy_integrate          | 15.0 ms                                                     | 12.1 ms: 1.24x faster                                                       |
| tornado_http             | 106 ms                                                      | 85.6 ms: 1.23x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.53 sec: 1.23x faster                                                      |
| mypy2                    | 347 ms                                                      | 284 ms: 1.22x faster                                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 32.3 ms: 1.22x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.22x faster                                                       |
| nqueens                  | 68.3 ms                                                     | 56.1 ms: 1.22x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.41 sec: 1.21x faster                                                      |
| dulwich_log              | 48.6 ms                                                     | 40.0 ms: 1.21x faster                                                       |
| dask                     | 305 ms                                                      | 251 ms: 1.21x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 170 ms: 1.21x faster                                                        |
| float                    | 61.7 ms                                                     | 51.0 ms: 1.21x faster                                                       |
| sympy_expand             | 320 ms                                                      | 265 ms: 1.21x faster                                                        |
| tomli_loads              | 1.65 sec                                                    | 1.37 sec: 1.21x faster                                                      |
| xml_etree_process        | 43.1 ms                                                     | 35.9 ms: 1.20x faster                                                       |
| deepcopy                 | 259 us                                                      | 218 us: 1.19x faster                                                        |
| coroutines               | 15.5 ms                                                     | 13.1 ms: 1.18x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 1.92 us: 1.16x faster                                                       |
| 2to3                     | 239 ms                                                      | 207 ms: 1.15x faster                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.38 ms: 1.12x faster                                                       |
| fannkuch                 | 258 ms                                                      | 234 ms: 1.10x faster                                                        |
| scimark_fft              | 187 ms                                                      | 171 ms: 1.10x faster                                                        |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.91 sec: 1.09x faster                                                      |
| bench_thread_pool        | 913 us                                                      | 843 us: 1.08x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.45 us: 1.08x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 745 us: 1.07x faster                                                        |
| nbody                    | 71.0 ms                                                     | 66.3 ms: 1.07x faster                                                       |
| regex_dna                | 129 ms                                                      | 121 ms: 1.06x faster                                                        |
| unpack_sequence          | 40.0 ns                                                     | 37.6 ns: 1.06x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 91.7 ms: 1.06x faster                                                       |
| json                     | 3.10 ms                                                     | 2.95 ms: 1.05x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                                       |
| meteor_contest           | 73.8 ms                                                     | 70.9 ms: 1.04x faster                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 52.3 ms: 1.04x faster                                                       |
| logging_simple           | 6.28 us                                                     | 6.04 us: 1.04x faster                                                       |
| logging_format           | 6.73 us                                                     | 6.48 us: 1.04x faster                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 62.5 ms: 1.03x faster                                                       |
| pickle                   | 6.87 us                                                     | 6.95 us: 1.01x slower                                                       |
| regex_v8                 | 15.0 ms                                                     | 15.3 ms: 1.02x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 74.6 ms: 1.02x slower                                                       |
| async_generators         | 219 ms                                                      | 228 ms: 1.04x slower                                                        |
| pickle_list              | 2.69 us                                                     | 2.82 us: 1.05x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 62.9 ms: 1.05x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.49 ms: 1.07x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.5 us: 1.08x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 17.7 ms: 1.15x slower                                                       |
| coverage                 | 38.4 ms                                                     | 45.6 ms: 1.19x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.57 ms: 1.20x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.24x faster                                                                |

Benchmark hidden because not significant (3): unpickle_list, python_startup, pidigits
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-48b46e7/bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.19x
