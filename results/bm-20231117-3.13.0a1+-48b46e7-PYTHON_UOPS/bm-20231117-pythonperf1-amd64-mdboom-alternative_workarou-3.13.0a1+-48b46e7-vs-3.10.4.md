
# Results vs. 3.10.4

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 48b46e7
- commit date: 2023-11-17
- overall geometric mean: 1.14x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 218 ms: 1.10x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.02 ms: 1.20x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.58 sec: 1.19x faster                                                      |
| tornado_http   | 106 ms                                                      | 89.2 ms: 1.18x faster                                                       |
| Geometric mean | (ref)                                                       | 1.17x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 271 ms: 1.56x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 727 ms: 1.47x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 345 ms: 1.46x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 460 ms: 1.34x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.46x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 146 ms                                                      | 148 ms: 1.01x slower                                                        |
| nbody          | 71.0 ms                                                     | 83.9 ms: 1.18x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 92.7 ms: 1.10x faster                                                       |
| regex_dna      | 129 ms                                                      | 122 ms: 1.06x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 15.3 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.70 ms: 1.54x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 179 us: 1.44x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 143 us: 1.24x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 36.4 ms: 1.18x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.19 us: 1.11x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 92.9 ms: 1.04x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.59 sec: 1.04x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 54.0 ms: 1.01x faster                                                       |
| pickle               | 6.87 us                                                     | 6.93 us: 1.01x slower                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 67.1 ms: 1.04x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.6 us: 1.09x slower                                                       |
| pickle_list          | 2.69 us                                                     | 3.09 us: 1.15x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.09x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.6 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 8.20 ms: 1.10x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 79.5 us: 4.24x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 56.5 ns: 1.65x faster                                                       |
| richards_super           | 50.3 ms                                                     | 30.8 ms: 1.64x faster                                                       |
| async_tree_none          | 424 ms                                                      | 271 ms: 1.56x faster                                                        |
| generators               | 31.8 ms                                                     | 20.4 ms: 1.56x faster                                                       |
| json_dumps               | 8.77 ms                                                     | 5.70 ms: 1.54x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 787 us: 1.53x faster                                                        |
| asyncio_tcp              | 717 ms                                                      | 471 ms: 1.52x faster                                                        |
| raytrace                 | 266 ms                                                      | 177 ms: 1.51x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 727 ms: 1.47x faster                                                        |
| richards                 | 40.6 ms                                                     | 27.6 ms: 1.47x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 345 ms: 1.46x faster                                                        |
| pickle_pure_python       | 259 us                                                      | 179 us: 1.44x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.01 ms: 1.44x faster                                                       |
| go                       | 135 ms                                                      | 97.5 ms: 1.39x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.98 ms: 1.38x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 60.9 ms: 1.38x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 460 ms: 1.34x faster                                                        |
| chaos                    | 59.5 ms                                                     | 45.2 ms: 1.32x faster                                                       |
| pycparser                | 905 ms                                                      | 689 ms: 1.31x faster                                                        |
| scimark_sor              | 105 ms                                                      | 82.8 ms: 1.27x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 143 us: 1.24x faster                                                        |
| sympy_sum                | 105 ms                                                      | 85.5 ms: 1.23x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 64.3 ms: 1.23x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 23.9 us: 1.21x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 52.1 ms: 1.21x faster                                                       |
| chameleon                | 6.02 ms                                                     | 5.02 ms: 1.20x faster                                                       |
| dask                     | 305 ms                                                      | 254 ms: 1.20x faster                                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 48.6 ms: 1.19x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.58 sec: 1.19x faster                                                      |
| sqlite_synth             | 1.90 us                                                     | 1.59 us: 1.19x faster                                                       |
| mypy2                    | 347 ms                                                      | 292 ms: 1.19x faster                                                        |
| tornado_http             | 106 ms                                                      | 89.2 ms: 1.18x faster                                                       |
| pyflate                  | 402 ms                                                      | 340 ms: 1.18x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 36.4 ms: 1.18x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 33.4 ms: 1.18x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 176 ms: 1.18x faster                                                        |
| deepcopy                 | 259 us                                                      | 221 us: 1.18x faster                                                        |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.79 sec: 1.17x faster                                                      |
| coroutines               | 15.5 ms                                                     | 13.3 ms: 1.17x faster                                                       |
| sympy_str                | 193 ms                                                      | 166 ms: 1.16x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 42.3 ms: 1.15x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 1.96 us: 1.13x faster                                                       |
| sympy_expand             | 320 ms                                                      | 283 ms: 1.13x faster                                                        |
| sympy_integrate          | 15.0 ms                                                     | 13.3 ms: 1.13x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.53 sec: 1.12x faster                                                      |
| pprint_pformat           | 1.22 sec                                                    | 1.10 sec: 1.11x faster                                                      |
| pprint_safe_repr         | 594 ms                                                      | 533 ms: 1.11x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.19 us: 1.11x faster                                                       |
| regex_compile            | 102 ms                                                      | 92.7 ms: 1.10x faster                                                       |
| mako                     | 8.98 ms                                                     | 8.20 ms: 1.10x faster                                                       |
| 2to3                     | 239 ms                                                      | 218 ms: 1.10x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 736 us: 1.09x faster                                                        |
| bench_thread_pool        | 913 us                                                      | 850 us: 1.07x faster                                                        |
| regex_dna                | 129 ms                                                      | 122 ms: 1.06x faster                                                        |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| comprehensions           | 16.6 us                                                     | 15.7 us: 1.06x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 92.9 ms: 1.04x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.59 sec: 1.04x faster                                                      |
| xml_etree_generate       | 54.5 ms                                                     | 54.0 ms: 1.01x faster                                                       |
| pidigits                 | 146 ms                                                      | 148 ms: 1.01x slower                                                        |
| pickle                   | 6.87 us                                                     | 6.93 us: 1.01x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| regex_v8                 | 15.0 ms                                                     | 15.3 ms: 1.02x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 74.8 ms: 1.03x slower                                                       |
| logging_format           | 6.73 us                                                     | 6.93 us: 1.03x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.48 us: 1.03x slower                                                       |
| nqueens                  | 68.3 ms                                                     | 70.6 ms: 1.03x slower                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 67.1 ms: 1.04x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 77.0 ms: 1.04x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 63.3 ms: 1.06x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                                       |
| hexiom                   | 5.59 ms                                                     | 6.04 ms: 1.08x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.6 us: 1.09x slower                                                       |
| async_generators         | 219 ms                                                      | 240 ms: 1.10x slower                                                        |
| python_startup_no_site   | 15.3 ms                                                     | 17.6 ms: 1.15x slower                                                       |
| pickle_list              | 2.69 us                                                     | 3.09 us: 1.15x slower                                                       |
| fannkuch                 | 258 ms                                                      | 298 ms: 1.16x slower                                                        |
| scimark_fft              | 187 ms                                                      | 218 ms: 1.16x slower                                                        |
| coverage                 | 38.4 ms                                                     | 44.9 ms: 1.17x slower                                                       |
| nbody                    | 71.0 ms                                                     | 83.9 ms: 1.18x slower                                                       |
| unpack_sequence          | 40.0 ns                                                     | 48.1 ns: 1.20x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.75 ms: 1.24x slower                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 3.68 ms: 1.38x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.14x faster                                                                |

Benchmark hidden because not significant (4): json, python_startup, float, unpickle_list
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-48b46e7-PYTHON_UOPS/bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.08x
