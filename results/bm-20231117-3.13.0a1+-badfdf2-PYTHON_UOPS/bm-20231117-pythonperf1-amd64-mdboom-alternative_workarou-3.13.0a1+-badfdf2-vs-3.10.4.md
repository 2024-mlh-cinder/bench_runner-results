
# Results vs. 3.10.4

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: badfdf2
- commit date: 2023-11-17
- overall geometric mean: 1.13x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 223 ms: 1.07x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.13 ms: 1.17x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.62 sec: 1.16x faster                                                      |
| tornado_http   | 106 ms                                                      | 88.9 ms: 1.19x faster                                                       |
| Geometric mean | (ref)                                                       | 1.15x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 273 ms: 1.55x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 739 ms: 1.45x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 349 ms: 1.45x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 461 ms: 1.34x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.44x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 61.0 ms: 1.01x faster                                                       |
| pidigits       | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| nbody          | 71.0 ms                                                     | 81.7 ms: 1.15x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 129 ms                                                      | 119 ms: 1.08x faster                                                        |
| regex_compile  | 102 ms                                                      | 96.9 ms: 1.06x faster                                                       |
| regex_v8       | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.59 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.65 ms: 1.55x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 187 us: 1.38x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 146 us: 1.22x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 37.5 ms: 1.15x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.41 us: 1.08x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.06x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 91.8 ms: 1.05x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.62 sec: 1.02x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 54.9 ms: 1.01x slower                                                       |
| pickle               | 6.87 us                                                     | 7.03 us: 1.02x slower                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 67.2 ms: 1.04x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.3 us: 1.07x slower                                                       |
| pickle_list          | 2.69 us                                                     | 3.27 us: 1.21x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.07x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.7 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.99 ms: 1.12x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 79.4 us: 4.24x faster                                                       |
| richards_super           | 50.3 ms                                                     | 31.7 ms: 1.59x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 459 ms: 1.56x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.65 ms: 1.55x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 60.2 ns: 1.55x faster                                                       |
| async_tree_none          | 424 ms                                                      | 273 ms: 1.55x faster                                                        |
| generators               | 31.8 ms                                                     | 21.3 ms: 1.49x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 812 us: 1.48x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 739 ms: 1.45x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 349 ms: 1.45x faster                                                        |
| richards                 | 40.6 ms                                                     | 28.3 ms: 1.43x faster                                                       |
| raytrace                 | 266 ms                                                      | 187 ms: 1.42x faster                                                        |
| deltablue                | 4.12 ms                                                     | 2.92 ms: 1.41x faster                                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 1.02 ms: 1.41x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 187 us: 1.38x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 61.9 ms: 1.36x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 461 ms: 1.34x faster                                                        |
| go                       | 135 ms                                                      | 103 ms: 1.31x faster                                                        |
| chaos                    | 59.5 ms                                                     | 46.9 ms: 1.27x faster                                                       |
| scimark_sor              | 105 ms                                                      | 83.6 ms: 1.26x faster                                                       |
| pycparser                | 905 ms                                                      | 724 ms: 1.25x faster                                                        |
| spectral_norm            | 78.9 ms                                                     | 63.3 ms: 1.25x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 146 us: 1.22x faster                                                        |
| sympy_sum                | 105 ms                                                      | 87.1 ms: 1.21x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 52.2 ms: 1.21x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 48.5 ms: 1.20x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.59 us: 1.19x faster                                                       |
| tornado_http             | 106 ms                                                      | 88.9 ms: 1.19x faster                                                       |
| pyflate                  | 402 ms                                                      | 339 ms: 1.19x faster                                                        |
| deepcopy_memo            | 29.0 us                                                     | 24.7 us: 1.17x faster                                                       |
| chameleon                | 6.02 ms                                                     | 5.13 ms: 1.17x faster                                                       |
| dask                     | 305 ms                                                      | 260 ms: 1.17x faster                                                        |
| mypy2                    | 347 ms                                                      | 296 ms: 1.17x faster                                                        |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.80 sec: 1.17x faster                                                      |
| sqlglot_optimize         | 39.4 ms                                                     | 33.9 ms: 1.16x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.62 sec: 1.16x faster                                                      |
| sqlglot_normalize        | 207 ms                                                      | 178 ms: 1.16x faster                                                        |
| deepcopy                 | 259 us                                                      | 224 us: 1.16x faster                                                        |
| coroutines               | 15.5 ms                                                     | 13.4 ms: 1.15x faster                                                       |
| xml_etree_process        | 43.1 ms                                                     | 37.5 ms: 1.15x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 1.96 us: 1.13x faster                                                       |
| mako                     | 8.98 ms                                                     | 7.99 ms: 1.12x faster                                                       |
| sympy_str                | 193 ms                                                      | 172 ms: 1.12x faster                                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.10 sec: 1.11x faster                                                      |
| sympy_integrate          | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 536 ms: 1.11x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 733 us: 1.09x faster                                                        |
| mdp                      | 1.71 sec                                                    | 1.57 sec: 1.09x faster                                                      |
| sympy_expand             | 320 ms                                                      | 294 ms: 1.09x faster                                                        |
| regex_dna                | 129 ms                                                      | 119 ms: 1.08x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.41 us: 1.08x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 44.9 ms: 1.08x faster                                                       |
| 2to3                     | 239 ms                                                      | 223 ms: 1.07x faster                                                        |
| bench_thread_pool        | 913 us                                                      | 854 us: 1.07x faster                                                        |
| comprehensions           | 16.6 us                                                     | 15.6 us: 1.06x faster                                                       |
| unpack_sequence          | 40.0 ns                                                     | 37.7 ns: 1.06x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.06x faster                                                       |
| regex_compile            | 102 ms                                                      | 96.9 ms: 1.06x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 91.8 ms: 1.05x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.62 sec: 1.02x faster                                                      |
| float                    | 61.7 ms                                                     | 61.0 ms: 1.01x faster                                                       |
| regex_v8                 | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 54.9 ms: 1.01x slower                                                       |
| pidigits                 | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| regex_effbot             | 1.56 ms                                                     | 1.59 ms: 1.02x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.03 us: 1.02x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 75.0 ms: 1.03x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.53 us: 1.04x slower                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 67.2 ms: 1.04x slower                                                       |
| logging_format           | 6.73 us                                                     | 7.02 us: 1.04x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 63.2 ms: 1.06x slower                                                       |
| nqueens                  | 68.3 ms                                                     | 72.2 ms: 1.06x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.3 us: 1.07x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 79.2 ms: 1.07x slower                                                       |
| async_generators         | 219 ms                                                      | 237 ms: 1.08x slower                                                        |
| hexiom                   | 5.59 ms                                                     | 6.11 ms: 1.09x slower                                                       |
| scimark_fft              | 187 ms                                                      | 212 ms: 1.13x slower                                                        |
| nbody                    | 71.0 ms                                                     | 81.7 ms: 1.15x slower                                                       |
| fannkuch                 | 258 ms                                                      | 298 ms: 1.15x slower                                                        |
| python_startup_no_site   | 15.3 ms                                                     | 17.7 ms: 1.16x slower                                                       |
| coverage                 | 38.4 ms                                                     | 46.3 ms: 1.21x slower                                                       |
| pickle_list              | 2.69 us                                                     | 3.27 us: 1.21x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.85 ms: 1.27x slower                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 3.69 ms: 1.38x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.13x faster                                                                |

Benchmark hidden because not significant (3): json, unpickle_list, python_startup
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-badfdf2-PYTHON_UOPS/bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
