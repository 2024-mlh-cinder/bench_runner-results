
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.22x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 213 ms: 1.12x faster                                                |
| chameleon      | 6.02 ms                                                     | 4.74 ms: 1.27x faster                                               |
| docutils       | 1.88 sec                                                    | 1.57 sec: 1.20x faster                                              |
| tornado_http   | 106 ms                                                      | 86.7 ms: 1.22x faster                                               |
| Geometric mean | (ref)                                                       | 1.20x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 268 ms: 1.58x faster                                                |
| async_tree_memoization  | 505 ms                                                      | 337 ms: 1.50x faster                                                |
| async_tree_io           | 1.07 sec                                                    | 724 ms: 1.48x faster                                                |
| async_tree_cpu_io_mixed | 617 ms                                                      | 451 ms: 1.37x faster                                                |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 50.2 ms: 1.23x faster                                               |
| nbody          | 71.0 ms                                                     | 66.6 ms: 1.07x faster                                               |
| pidigits       | 146 ms                                                      | 150 ms: 1.03x slower                                                |
| Geometric mean | (ref)                                                       | 1.09x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 79.5 ms: 1.29x faster                                               |
| regex_dna      | 129 ms                                                      | 122 ms: 1.06x faster                                                |
| regex_v8       | 15.0 ms                                                     | 15.4 ms: 1.02x slower                                               |
| regex_effbot   | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                               |
| Geometric mean | (ref)                                                       | 1.07x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.67 ms: 1.55x faster                                               |
| pickle_pure_python   | 259 us                                                      | 180 us: 1.44x faster                                                |
| unpickle_pure_python | 177 us                                                      | 130 us: 1.36x faster                                                |
| tomli_loads          | 1.65 sec                                                    | 1.27 sec: 1.30x faster                                              |
| xml_etree_process    | 43.1 ms                                                     | 36.2 ms: 1.19x faster                                               |
| unpickle             | 9.11 us                                                     | 8.18 us: 1.11x faster                                               |
| xml_etree_parse      | 96.8 ms                                                     | 91.8 ms: 1.05x faster                                               |
| xml_etree_iterparse  | 64.5 ms                                                     | 62.1 ms: 1.04x faster                                               |
| xml_etree_generate   | 54.5 ms                                                     | 53.3 ms: 1.02x faster                                               |
| json_loads           | 14.2 us                                                     | 13.9 us: 1.02x faster                                               |
| pickle               | 6.87 us                                                     | 7.22 us: 1.05x slower                                               |
| pickle_dict          | 17.1 us                                                     | 18.6 us: 1.08x slower                                               |
| pickle_list          | 2.69 us                                                     | 3.32 us: 1.23x slower                                               |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                        |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.4 ms: 1.04x slower                                               |
| python_startup_no_site | 15.3 ms                                                     | 18.2 ms: 1.19x slower                                               |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.21 ms: 1.45x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 75.2 us: 4.48x faster                                               |
| deltablue                | 4.12 ms                                                     | 1.98 ms: 2.08x faster                                               |
| richards_super           | 50.3 ms                                                     | 29.1 ms: 1.73x faster                                               |
| logging_silent           | 93.4 ns                                                     | 55.9 ns: 1.67x faster                                               |
| sqlglot_parse            | 1.20 ms                                                     | 754 us: 1.60x faster                                                |
| async_tree_none          | 424 ms                                                      | 268 ms: 1.58x faster                                                |
| richards                 | 40.6 ms                                                     | 25.9 ms: 1.57x faster                                               |
| json_dumps               | 8.77 ms                                                     | 5.67 ms: 1.55x faster                                               |
| scimark_lu               | 84.0 ms                                                     | 54.4 ms: 1.54x faster                                               |
| raytrace                 | 266 ms                                                      | 173 ms: 1.54x faster                                                |
| asyncio_tcp              | 717 ms                                                      | 469 ms: 1.53x faster                                                |
| generators               | 31.8 ms                                                     | 20.8 ms: 1.53x faster                                               |
| go                       | 135 ms                                                      | 88.8 ms: 1.52x faster                                               |
| comprehensions           | 16.6 us                                                     | 11.0 us: 1.51x faster                                               |
| async_tree_memoization   | 505 ms                                                      | 337 ms: 1.50x faster                                                |
| sqlglot_transpile        | 1.45 ms                                                     | 967 us: 1.49x faster                                                |
| async_tree_io            | 1.07 sec                                                    | 724 ms: 1.48x faster                                                |
| chaos                    | 59.5 ms                                                     | 40.7 ms: 1.46x faster                                               |
| mako                     | 8.98 ms                                                     | 6.21 ms: 1.45x faster                                               |
| pickle_pure_python       | 259 us                                                      | 180 us: 1.44x faster                                                |
| pyflate                  | 402 ms                                                      | 293 ms: 1.37x faster                                                |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 451 ms: 1.37x faster                                                |
| crypto_pyaes             | 63.1 ms                                                     | 46.1 ms: 1.37x faster                                               |
| unpickle_pure_python     | 177 us                                                      | 130 us: 1.36x faster                                                |
| spectral_norm            | 78.9 ms                                                     | 58.3 ms: 1.35x faster                                               |
| hexiom                   | 5.59 ms                                                     | 4.15 ms: 1.35x faster                                               |
| scimark_sor              | 105 ms                                                      | 78.3 ms: 1.34x faster                                               |
| deepcopy_memo            | 29.0 us                                                     | 21.6 us: 1.34x faster                                               |
| scimark_monte_carlo      | 58.0 ms                                                     | 44.4 ms: 1.31x faster                                               |
| pycparser                | 905 ms                                                      | 694 ms: 1.30x faster                                                |
| tomli_loads              | 1.65 sec                                                    | 1.27 sec: 1.30x faster                                              |
| regex_compile            | 102 ms                                                      | 79.5 ms: 1.29x faster                                               |
| sympy_sum                | 105 ms                                                      | 82.9 ms: 1.27x faster                                               |
| chameleon                | 6.02 ms                                                     | 4.74 ms: 1.27x faster                                               |
| float                    | 61.7 ms                                                     | 50.2 ms: 1.23x faster                                               |
| sympy_str                | 193 ms                                                      | 158 ms: 1.23x faster                                                |
| sqlite_synth             | 1.90 us                                                     | 1.55 us: 1.22x faster                                               |
| tornado_http             | 106 ms                                                      | 86.7 ms: 1.22x faster                                               |
| mypy2                    | 347 ms                                                      | 289 ms: 1.20x faster                                                |
| pprint_pformat           | 1.22 sec                                                    | 1.02 sec: 1.20x faster                                              |
| dask                     | 305 ms                                                      | 254 ms: 1.20x faster                                                |
| sympy_expand             | 320 ms                                                      | 268 ms: 1.20x faster                                                |
| docutils                 | 1.88 sec                                                    | 1.57 sec: 1.20x faster                                              |
| dulwich_log              | 48.6 ms                                                     | 40.7 ms: 1.20x faster                                               |
| xml_etree_process        | 43.1 ms                                                     | 36.2 ms: 1.19x faster                                               |
| deepcopy                 | 259 us                                                      | 218 us: 1.19x faster                                                |
| pprint_safe_repr         | 594 ms                                                      | 500 ms: 1.19x faster                                                |
| coroutines               | 15.5 ms                                                     | 13.0 ms: 1.19x faster                                               |
| sqlglot_optimize         | 39.4 ms                                                     | 33.3 ms: 1.18x faster                                               |
| sympy_integrate          | 15.0 ms                                                     | 12.7 ms: 1.18x faster                                               |
| mdp                      | 1.71 sec                                                    | 1.45 sec: 1.18x faster                                              |
| sqlglot_normalize        | 207 ms                                                      | 177 ms: 1.17x faster                                                |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.31 ms: 1.15x faster                                               |
| nqueens                  | 68.3 ms                                                     | 59.5 ms: 1.15x faster                                               |
| deepcopy_reduce          | 2.22 us                                                     | 1.94 us: 1.14x faster                                               |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.83 sec: 1.14x faster                                              |
| 2to3                     | 239 ms                                                      | 213 ms: 1.12x faster                                                |
| unpickle                 | 9.11 us                                                     | 8.18 us: 1.11x faster                                               |
| create_gc_cycles         | 800 us                                                      | 729 us: 1.10x faster                                                |
| bench_thread_pool        | 913 us                                                      | 839 us: 1.09x faster                                                |
| fannkuch                 | 258 ms                                                      | 239 ms: 1.08x faster                                                |
| nbody                    | 71.0 ms                                                     | 66.6 ms: 1.07x faster                                               |
| regex_dna                | 129 ms                                                      | 122 ms: 1.06x faster                                                |
| xml_etree_parse          | 96.8 ms                                                     | 91.8 ms: 1.05x faster                                               |
| scimark_fft              | 187 ms                                                      | 179 ms: 1.05x faster                                                |
| json                     | 3.10 ms                                                     | 2.98 ms: 1.04x faster                                               |
| xml_etree_iterparse      | 64.5 ms                                                     | 62.1 ms: 1.04x faster                                               |
| logging_simple           | 6.28 us                                                     | 6.13 us: 1.02x faster                                               |
| xml_etree_generate       | 54.5 ms                                                     | 53.3 ms: 1.02x faster                                               |
| logging_format           | 6.73 us                                                     | 6.58 us: 1.02x faster                                               |
| json_loads               | 14.2 us                                                     | 13.9 us: 1.02x faster                                               |
| meteor_contest           | 73.8 ms                                                     | 74.7 ms: 1.01x slower                                               |
| regex_v8                 | 15.0 ms                                                     | 15.4 ms: 1.02x slower                                               |
| pidigits                 | 146 ms                                                      | 150 ms: 1.03x slower                                                |
| regex_effbot             | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                               |
| pathlib                  | 72.8 ms                                                     | 75.4 ms: 1.03x slower                                               |
| python_startup           | 19.7 ms                                                     | 20.4 ms: 1.04x slower                                               |
| pickle                   | 6.87 us                                                     | 7.22 us: 1.05x slower                                               |
| async_generators         | 219 ms                                                      | 231 ms: 1.05x slower                                                |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                               |
| bench_mp_pool            | 59.9 ms                                                     | 64.4 ms: 1.08x slower                                               |
| pickle_dict              | 17.1 us                                                     | 18.6 us: 1.08x slower                                               |
| coverage                 | 38.4 ms                                                     | 44.3 ms: 1.15x slower                                               |
| python_startup_no_site   | 15.3 ms                                                     | 18.2 ms: 1.19x slower                                               |
| telco                    | 3.82 ms                                                     | 4.59 ms: 1.20x slower                                               |
| pickle_list              | 2.69 us                                                     | 3.32 us: 1.23x slower                                               |
| Geometric mean           | (ref)                                                       | 1.22x faster                                                        |

Benchmark hidden because not significant (2): unpickle_list, unpack_sequence
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231115-3.13.0a1+-7a7e995/bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.17x
