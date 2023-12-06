
# Results vs. 3.10.4

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: windows-amd64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.22x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 209 ms: 1.14x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.81 ms: 1.25x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                                      |
| tornado_http   | 106 ms                                                      | 86.4 ms: 1.22x faster                                                       |
| Geometric mean | (ref)                                                       | 1.21x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 266 ms: 1.59x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 341 ms: 1.48x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 723 ms: 1.48x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 455 ms: 1.36x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 51.7 ms: 1.19x faster                                                       |
| nbody          | 71.0 ms                                                     | 73.4 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 80.1 ms: 1.28x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.60 ms: 1.56x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 182 us: 1.42x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 128 us: 1.39x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 36.9 ms: 1.17x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.42 sec: 1.16x faster                                                      |
| unpickle             | 9.11 us                                                     | 7.91 us: 1.15x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 91.8 ms: 1.05x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                                       |
| unpickle_list        | 2.68 us                                                     | 2.61 us: 1.03x faster                                                       |
| pickle               | 6.87 us                                                     | 6.89 us: 1.00x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.1 us: 1.06x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.85 us: 1.06x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.12x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_iterparse, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.8 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.51 ms: 1.38x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 75.2 us: 4.48x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.13 ms: 1.94x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 56.1 ns: 1.66x faster                                                       |
| raytrace                 | 266 ms                                                      | 163 ms: 1.63x faster                                                        |
| async_tree_none          | 424 ms                                                      | 266 ms: 1.59x faster                                                        |
| richards_super           | 50.3 ms                                                     | 31.7 ms: 1.59x faster                                                       |
| comprehensions           | 16.6 us                                                     | 10.5 us: 1.58x faster                                                       |
| json_dumps               | 8.77 ms                                                     | 5.60 ms: 1.56x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 459 ms: 1.56x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 773 us: 1.56x faster                                                        |
| go                       | 135 ms                                                      | 87.3 ms: 1.55x faster                                                       |
| generators               | 31.8 ms                                                     | 21.0 ms: 1.52x faster                                                       |
| chaos                    | 59.5 ms                                                     | 39.6 ms: 1.50x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 56.4 ms: 1.49x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 341 ms: 1.48x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 723 ms: 1.48x faster                                                        |
| richards                 | 40.6 ms                                                     | 27.8 ms: 1.46x faster                                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 992 us: 1.46x faster                                                        |
| hexiom                   | 5.59 ms                                                     | 3.85 ms: 1.45x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 43.5 ms: 1.45x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 182 us: 1.42x faster                                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 41.8 ms: 1.39x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 128 us: 1.39x faster                                                        |
| mako                     | 8.98 ms                                                     | 6.51 ms: 1.38x faster                                                       |
| pyflate                  | 402 ms                                                      | 291 ms: 1.38x faster                                                        |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 455 ms: 1.36x faster                                                        |
| scimark_sor              | 105 ms                                                      | 80.5 ms: 1.31x faster                                                       |
| sympy_sum                | 105 ms                                                      | 82.1 ms: 1.28x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 61.7 ms: 1.28x faster                                                       |
| regex_compile            | 102 ms                                                      | 80.1 ms: 1.28x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.81 ms: 1.25x faster                                                       |
| pycparser                | 905 ms                                                      | 728 ms: 1.24x faster                                                        |
| sympy_str                | 193 ms                                                      | 157 ms: 1.23x faster                                                        |
| tornado_http             | 106 ms                                                      | 86.4 ms: 1.22x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 23.7 us: 1.22x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 12.3 ms: 1.22x faster                                                       |
| mypy2                    | 347 ms                                                      | 286 ms: 1.21x faster                                                        |
| dask                     | 305 ms                                                      | 252 ms: 1.21x faster                                                        |
| docutils                 | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                                      |
| sqlite_synth             | 1.90 us                                                     | 1.57 us: 1.21x faster                                                       |
| sympy_expand             | 320 ms                                                      | 267 ms: 1.20x faster                                                        |
| nqueens                  | 68.3 ms                                                     | 57.2 ms: 1.19x faster                                                       |
| float                    | 61.7 ms                                                     | 51.7 ms: 1.19x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 33.2 ms: 1.19x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.03 sec: 1.19x faster                                                      |
| pprint_safe_repr         | 594 ms                                                      | 502 ms: 1.18x faster                                                        |
| deepcopy                 | 259 us                                                      | 220 us: 1.18x faster                                                        |
| mdp                      | 1.71 sec                                                    | 1.45 sec: 1.18x faster                                                      |
| sqlglot_normalize        | 207 ms                                                      | 175 ms: 1.18x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 41.4 ms: 1.17x faster                                                       |
| xml_etree_process        | 43.1 ms                                                     | 36.9 ms: 1.17x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.42 sec: 1.16x faster                                                      |
| coroutines               | 15.5 ms                                                     | 13.4 ms: 1.15x faster                                                       |
| unpickle                 | 9.11 us                                                     | 7.91 us: 1.15x faster                                                       |
| 2to3                     | 239 ms                                                      | 209 ms: 1.14x faster                                                        |
| deepcopy_reduce          | 2.22 us                                                     | 1.95 us: 1.14x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.86 sec: 1.13x faster                                                      |
| create_gc_cycles         | 800 us                                                      | 727 us: 1.10x faster                                                        |
| bench_thread_pool        | 913 us                                                      | 840 us: 1.09x faster                                                        |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.51 ms: 1.06x faster                                                       |
| json                     | 3.10 ms                                                     | 2.94 ms: 1.06x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 91.8 ms: 1.05x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                                       |
| scimark_fft              | 187 ms                                                      | 180 ms: 1.04x faster                                                        |
| logging_format           | 6.73 us                                                     | 6.46 us: 1.04x faster                                                       |
| fannkuch                 | 258 ms                                                      | 248 ms: 1.04x faster                                                        |
| logging_simple           | 6.28 us                                                     | 6.04 us: 1.04x faster                                                       |
| unpickle_list            | 2.68 us                                                     | 2.61 us: 1.03x faster                                                       |
| meteor_contest           | 73.8 ms                                                     | 73.7 ms: 1.00x faster                                                       |
| pickle                   | 6.87 us                                                     | 6.89 us: 1.00x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| unpack_sequence          | 40.0 ns                                                     | 41.2 ns: 1.03x slower                                                       |
| nbody                    | 71.0 ms                                                     | 73.4 ms: 1.03x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 75.5 ms: 1.04x slower                                                       |
| async_generators         | 219 ms                                                      | 227 ms: 1.04x slower                                                        |
| bench_mp_pool            | 59.9 ms                                                     | 62.7 ms: 1.05x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.1 us: 1.06x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.85 us: 1.06x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.48 ms: 1.06x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 17.8 ms: 1.16x slower                                                       |
| coverage                 | 38.4 ms                                                     | 46.1 ms: 1.20x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.75 ms: 1.24x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.22x faster                                                                |

Benchmark hidden because not significant (5): xml_etree_iterparse, regex_v8, xml_etree_generate, pidigits, python_startup
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231115-3.13.0a1+-7e2308a/bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.16x
