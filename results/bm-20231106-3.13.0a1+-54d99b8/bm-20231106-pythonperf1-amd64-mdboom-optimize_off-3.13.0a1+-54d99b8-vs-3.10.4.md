
# Results vs. 3.10.4

- fork: mdboom
- ref: optimize_off
- machine: windows-amd64
- commit hash: 54d99b8
- commit date: 2023-11-06
- overall geometric mean: 1.22x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 208 ms: 1.15x faster                                                |
| chameleon      | 6.02 ms                                                     | 4.90 ms: 1.23x faster                                               |
| docutils       | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                              |
| tornado_http   | 106 ms                                                      | 86.8 ms: 1.22x faster                                               |
| Geometric mean | (ref)                                                       | 1.20x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|-------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 265 ms: 1.60x faster                                                |
| async_tree_memoization  | 505 ms                                                      | 339 ms: 1.49x faster                                                |
| async_tree_io           | 1.07 sec                                                    | 723 ms: 1.48x faster                                                |
| async_tree_cpu_io_mixed | 617 ms                                                      | 451 ms: 1.37x faster                                                |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 52.2 ms: 1.18x faster                                               |
| pidigits       | 146 ms                                                      | 147 ms: 1.00x slower                                                |
| nbody          | 71.0 ms                                                     | 72.6 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                       | 1.05x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 79.2 ms: 1.29x faster                                               |
| regex_dna      | 129 ms                                                      | 119 ms: 1.09x faster                                                |
| regex_v8       | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                               |
| regex_effbot   | 1.56 ms                                                     | 1.57 ms: 1.00x slower                                               |
| Geometric mean | (ref)                                                       | 1.09x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.63 ms: 1.56x faster                                               |
| pickle_pure_python   | 259 us                                                      | 181 us: 1.43x faster                                                |
| unpickle_pure_python | 177 us                                                      | 130 us: 1.36x faster                                                |
| tomli_loads          | 1.65 sec                                                    | 1.41 sec: 1.17x faster                                              |
| xml_etree_process    | 43.1 ms                                                     | 37.6 ms: 1.15x faster                                               |
| unpickle             | 9.11 us                                                     | 8.02 us: 1.14x faster                                               |
| xml_etree_parse      | 96.8 ms                                                     | 92.0 ms: 1.05x faster                                               |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                               |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.3 ms: 1.02x faster                                               |
| xml_etree_generate   | 54.5 ms                                                     | 55.3 ms: 1.01x slower                                               |
| pickle               | 6.87 us                                                     | 7.18 us: 1.04x slower                                               |
| pickle_list          | 2.69 us                                                     | 2.88 us: 1.07x slower                                               |
| pickle_dict          | 17.1 us                                                     | 19.8 us: 1.15x slower                                               |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                        |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.6 ms: 1.15x slower                                               |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                        |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.56 ms: 1.37x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 76.3 us: 4.41x faster                                               |
| deltablue                | 4.12 ms                                                     | 2.03 ms: 2.03x faster                                               |
| mypy2                    | 347 ms                                                      | 203 ms: 1.70x faster                                                |
| logging_silent           | 93.4 ns                                                     | 55.5 ns: 1.68x faster                                               |
| richards_super           | 50.3 ms                                                     | 30.5 ms: 1.65x faster                                               |
| raytrace                 | 266 ms                                                      | 162 ms: 1.64x faster                                                |
| async_tree_none          | 424 ms                                                      | 265 ms: 1.60x faster                                                |
| sqlglot_parse            | 1.20 ms                                                     | 758 us: 1.59x faster                                                |
| go                       | 135 ms                                                      | 86.5 ms: 1.56x faster                                               |
| json_dumps               | 8.77 ms                                                     | 5.63 ms: 1.56x faster                                               |
| comprehensions           | 16.6 us                                                     | 10.7 us: 1.55x faster                                               |
| chaos                    | 59.5 ms                                                     | 39.5 ms: 1.51x faster                                               |
| async_tree_memoization   | 505 ms                                                      | 339 ms: 1.49x faster                                                |
| asyncio_tcp              | 717 ms                                                      | 482 ms: 1.49x faster                                                |
| sqlglot_transpile        | 1.45 ms                                                     | 977 us: 1.48x faster                                                |
| async_tree_io            | 1.07 sec                                                    | 723 ms: 1.48x faster                                                |
| richards                 | 40.6 ms                                                     | 27.5 ms: 1.48x faster                                               |
| hexiom                   | 5.59 ms                                                     | 3.79 ms: 1.48x faster                                               |
| generators               | 31.8 ms                                                     | 21.7 ms: 1.47x faster                                               |
| crypto_pyaes             | 63.1 ms                                                     | 43.7 ms: 1.44x faster                                               |
| pickle_pure_python       | 259 us                                                      | 181 us: 1.43x faster                                                |
| scimark_lu               | 84.0 ms                                                     | 58.8 ms: 1.43x faster                                               |
| pyflate                  | 402 ms                                                      | 290 ms: 1.38x faster                                                |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.2 ms: 1.38x faster                                               |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 451 ms: 1.37x faster                                                |
| mako                     | 8.98 ms                                                     | 6.56 ms: 1.37x faster                                               |
| unpickle_pure_python     | 177 us                                                      | 130 us: 1.36x faster                                                |
| scimark_sor              | 105 ms                                                      | 80.3 ms: 1.31x faster                                               |
| regex_compile            | 102 ms                                                      | 79.2 ms: 1.29x faster                                               |
| sympy_sum                | 105 ms                                                      | 82.5 ms: 1.28x faster                                               |
| spectral_norm            | 78.9 ms                                                     | 62.7 ms: 1.26x faster                                               |
| chameleon                | 6.02 ms                                                     | 4.90 ms: 1.23x faster                                               |
| sympy_str                | 193 ms                                                      | 158 ms: 1.22x faster                                                |
| deepcopy_memo            | 29.0 us                                                     | 23.7 us: 1.22x faster                                               |
| tornado_http             | 106 ms                                                      | 86.8 ms: 1.22x faster                                               |
| sympy_integrate          | 15.0 ms                                                     | 12.3 ms: 1.22x faster                                               |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.21x faster                                               |
| pprint_pformat           | 1.22 sec                                                    | 1.01 sec: 1.21x faster                                              |
| pprint_safe_repr         | 594 ms                                                      | 490 ms: 1.21x faster                                                |
| docutils                 | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                              |
| dulwich_log              | 48.6 ms                                                     | 40.4 ms: 1.20x faster                                               |
| sqlglot_optimize         | 39.4 ms                                                     | 33.1 ms: 1.19x faster                                               |
| mdp                      | 1.71 sec                                                    | 1.44 sec: 1.19x faster                                              |
| nqueens                  | 68.3 ms                                                     | 57.5 ms: 1.19x faster                                               |
| sqlglot_normalize        | 207 ms                                                      | 174 ms: 1.19x faster                                                |
| sympy_expand             | 320 ms                                                      | 270 ms: 1.19x faster                                                |
| float                    | 61.7 ms                                                     | 52.2 ms: 1.18x faster                                               |
| deepcopy                 | 259 us                                                      | 220 us: 1.18x faster                                                |
| pycparser                | 905 ms                                                      | 769 ms: 1.18x faster                                                |
| tomli_loads              | 1.65 sec                                                    | 1.41 sec: 1.17x faster                                              |
| 2to3                     | 239 ms                                                      | 208 ms: 1.15x faster                                                |
| xml_etree_process        | 43.1 ms                                                     | 37.6 ms: 1.15x faster                                               |
| deepcopy_reduce          | 2.22 us                                                     | 1.96 us: 1.14x faster                                               |
| unpickle                 | 9.11 us                                                     | 8.02 us: 1.14x faster                                               |
| coroutines               | 15.5 ms                                                     | 13.7 ms: 1.13x faster                                               |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.37 ms: 1.13x faster                                               |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.87 sec: 1.12x faster                                              |
| create_gc_cycles         | 800 us                                                      | 720 us: 1.11x faster                                                |
| bench_thread_pool        | 913 us                                                      | 833 us: 1.10x faster                                                |
| regex_dna                | 129 ms                                                      | 119 ms: 1.09x faster                                                |
| unpack_sequence          | 40.0 ns                                                     | 37.3 ns: 1.07x faster                                               |
| scimark_fft              | 187 ms                                                      | 177 ms: 1.06x faster                                                |
| xml_etree_parse          | 96.8 ms                                                     | 92.0 ms: 1.05x faster                                               |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                               |
| logging_simple           | 6.28 us                                                     | 6.13 us: 1.02x faster                                               |
| fannkuch                 | 258 ms                                                      | 252 ms: 1.02x faster                                                |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.3 ms: 1.02x faster                                               |
| logging_format           | 6.73 us                                                     | 6.61 us: 1.02x faster                                               |
| meteor_contest           | 73.8 ms                                                     | 72.9 ms: 1.01x faster                                               |
| regex_v8                 | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                               |
| pidigits                 | 146 ms                                                      | 147 ms: 1.00x slower                                                |
| regex_effbot             | 1.56 ms                                                     | 1.57 ms: 1.00x slower                                               |
| xml_etree_generate       | 54.5 ms                                                     | 55.3 ms: 1.01x slower                                               |
| nbody                    | 71.0 ms                                                     | 72.6 ms: 1.02x slower                                               |
| async_generators         | 219 ms                                                      | 226 ms: 1.04x slower                                                |
| pickle                   | 6.87 us                                                     | 7.18 us: 1.04x slower                                               |
| bench_mp_pool            | 59.9 ms                                                     | 62.6 ms: 1.04x slower                                               |
| gc_traversal             | 1.40 ms                                                     | 1.48 ms: 1.06x slower                                               |
| pickle_list              | 2.69 us                                                     | 2.88 us: 1.07x slower                                               |
| pathlib                  | 72.8 ms                                                     | 78.9 ms: 1.08x slower                                               |
| python_startup_no_site   | 15.3 ms                                                     | 17.6 ms: 1.15x slower                                               |
| pickle_dict              | 17.1 us                                                     | 19.8 us: 1.15x slower                                               |
| coverage                 | 38.4 ms                                                     | 45.4 ms: 1.18x slower                                               |
| telco                    | 3.82 ms                                                     | 4.76 ms: 1.25x slower                                               |
| Geometric mean           | (ref)                                                       | 1.22x faster                                                        |

Benchmark hidden because not significant (3): json, python_startup, unpickle_list
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231106-3.13.0a1+-54d99b8/bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
