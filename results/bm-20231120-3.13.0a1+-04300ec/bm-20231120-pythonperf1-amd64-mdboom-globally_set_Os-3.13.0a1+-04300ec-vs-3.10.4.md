
# Results vs. 3.10.4

- fork: mdboom
- ref: globally_set_Os
- machine: windows-amd64
- commit hash: 04300ec
- commit date: 2023-11-20
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 209 ms: 1.14x faster                                                   |
| chameleon      | 6.02 ms                                                     | 4.91 ms: 1.23x faster                                                  |
| docutils       | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                                 |
| tornado_http   | 106 ms                                                      | 96.1 ms: 1.10x faster                                                  |
| Geometric mean | (ref)                                                       | 1.17x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|-------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 279 ms: 1.52x faster                                                   |
| async_tree_memoization  | 505 ms                                                      | 344 ms: 1.47x faster                                                   |
| async_tree_io           | 1.07 sec                                                    | 730 ms: 1.47x faster                                                   |
| async_tree_cpu_io_mixed | 617 ms                                                      | 471 ms: 1.31x faster                                                   |
| Geometric mean          | (ref)                                                       | 1.44x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 51.2 ms: 1.21x faster                                                  |
| nbody          | 71.0 ms                                                     | 73.6 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                       | 1.05x faster                                                           |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 78.9 ms: 1.30x faster                                                  |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                   |
| regex_v8       | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                                  |
| regex_effbot   | 1.56 ms                                                     | 1.62 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                       | 1.07x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.63 ms: 1.56x faster                                                  |
| pickle_pure_python   | 259 us                                                      | 184 us: 1.41x faster                                                   |
| unpickle_pure_python | 177 us                                                      | 131 us: 1.36x faster                                                   |
| xml_etree_process    | 43.1 ms                                                     | 36.9 ms: 1.17x faster                                                  |
| tomli_loads          | 1.65 sec                                                    | 1.44 sec: 1.15x faster                                                 |
| unpickle             | 9.11 us                                                     | 8.34 us: 1.09x faster                                                  |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                                  |
| xml_etree_parse      | 96.8 ms                                                     | 92.8 ms: 1.04x faster                                                  |
| pickle_list          | 2.69 us                                                     | 2.63 us: 1.02x faster                                                  |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.0 ms: 1.02x faster                                                  |
| xml_etree_generate   | 54.5 ms                                                     | 53.4 ms: 1.02x faster                                                  |
| pickle               | 6.87 us                                                     | 6.81 us: 1.01x faster                                                  |
| pickle_dict          | 17.1 us                                                     | 17.4 us: 1.01x slower                                                  |
| Geometric mean       | (ref)                                                       | 1.13x faster                                                           |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.0 ms: 1.02x slower                                                  |
| python_startup_no_site | 15.3 ms                                                     | 17.9 ms: 1.17x slower                                                  |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.43 ms: 1.40x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 75.9 us: 4.44x faster                                                  |
| deltablue                | 4.12 ms                                                     | 2.01 ms: 2.05x faster                                                  |
| logging_silent           | 93.4 ns                                                     | 55.4 ns: 1.68x faster                                                  |
| richards_super           | 50.3 ms                                                     | 30.4 ms: 1.66x faster                                                  |
| raytrace                 | 266 ms                                                      | 161 ms: 1.66x faster                                                   |
| comprehensions           | 16.6 us                                                     | 10.4 us: 1.59x faster                                                  |
| sqlglot_parse            | 1.20 ms                                                     | 759 us: 1.59x faster                                                   |
| json_dumps               | 8.77 ms                                                     | 5.63 ms: 1.56x faster                                                  |
| go                       | 135 ms                                                      | 87.2 ms: 1.55x faster                                                  |
| generators               | 31.8 ms                                                     | 20.8 ms: 1.53x faster                                                  |
| async_tree_none          | 424 ms                                                      | 279 ms: 1.52x faster                                                   |
| chaos                    | 59.5 ms                                                     | 39.4 ms: 1.51x faster                                                  |
| richards                 | 40.6 ms                                                     | 27.2 ms: 1.49x faster                                                  |
| crypto_pyaes             | 63.1 ms                                                     | 42.6 ms: 1.48x faster                                                  |
| sqlglot_transpile        | 1.45 ms                                                     | 980 us: 1.48x faster                                                   |
| scimark_lu               | 84.0 ms                                                     | 57.0 ms: 1.47x faster                                                  |
| async_tree_memoization   | 505 ms                                                      | 344 ms: 1.47x faster                                                   |
| async_tree_io            | 1.07 sec                                                    | 730 ms: 1.47x faster                                                   |
| hexiom                   | 5.59 ms                                                     | 3.83 ms: 1.46x faster                                                  |
| pickle_pure_python       | 259 us                                                      | 184 us: 1.41x faster                                                   |
| mako                     | 8.98 ms                                                     | 6.43 ms: 1.40x faster                                                  |
| pyflate                  | 402 ms                                                      | 289 ms: 1.39x faster                                                   |
| scimark_monte_carlo      | 58.0 ms                                                     | 41.8 ms: 1.39x faster                                                  |
| unpickle_pure_python     | 177 us                                                      | 131 us: 1.36x faster                                                   |
| asyncio_tcp              | 717 ms                                                      | 534 ms: 1.34x faster                                                   |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 471 ms: 1.31x faster                                                   |
| regex_compile            | 102 ms                                                      | 78.9 ms: 1.30x faster                                                  |
| scimark_sor              | 105 ms                                                      | 81.9 ms: 1.29x faster                                                  |
| sympy_sum                | 105 ms                                                      | 82.7 ms: 1.27x faster                                                  |
| deepcopy_memo            | 29.0 us                                                     | 23.5 us: 1.23x faster                                                  |
| chameleon                | 6.02 ms                                                     | 4.91 ms: 1.23x faster                                                  |
| sympy_str                | 193 ms                                                      | 158 ms: 1.22x faster                                                   |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.22x faster                                                  |
| sympy_integrate          | 15.0 ms                                                     | 12.4 ms: 1.21x faster                                                  |
| mdp                      | 1.71 sec                                                    | 1.42 sec: 1.21x faster                                                 |
| docutils                 | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                                 |
| mypy2                    | 347 ms                                                      | 287 ms: 1.21x faster                                                   |
| float                    | 61.7 ms                                                     | 51.2 ms: 1.21x faster                                                  |
| spectral_norm            | 78.9 ms                                                     | 65.6 ms: 1.20x faster                                                  |
| pprint_pformat           | 1.22 sec                                                    | 1.03 sec: 1.18x faster                                                 |
| pprint_safe_repr         | 594 ms                                                      | 502 ms: 1.18x faster                                                   |
| nqueens                  | 68.3 ms                                                     | 58.2 ms: 1.17x faster                                                  |
| sympy_expand             | 320 ms                                                      | 273 ms: 1.17x faster                                                   |
| dulwich_log              | 48.6 ms                                                     | 41.6 ms: 1.17x faster                                                  |
| xml_etree_process        | 43.1 ms                                                     | 36.9 ms: 1.17x faster                                                  |
| coroutines               | 15.5 ms                                                     | 13.3 ms: 1.16x faster                                                  |
| sqlglot_optimize         | 39.4 ms                                                     | 34.0 ms: 1.16x faster                                                  |
| pycparser                | 905 ms                                                      | 781 ms: 1.16x faster                                                   |
| deepcopy                 | 259 us                                                      | 226 us: 1.15x faster                                                   |
| sqlglot_normalize        | 207 ms                                                      | 180 ms: 1.15x faster                                                   |
| dask                     | 305 ms                                                      | 265 ms: 1.15x faster                                                   |
| tomli_loads              | 1.65 sec                                                    | 1.44 sec: 1.15x faster                                                 |
| 2to3                     | 239 ms                                                      | 209 ms: 1.14x faster                                                   |
| deepcopy_reduce          | 2.22 us                                                     | 1.98 us: 1.12x faster                                                  |
| tornado_http             | 106 ms                                                      | 96.1 ms: 1.10x faster                                                  |
| unpickle                 | 9.11 us                                                     | 8.34 us: 1.09x faster                                                  |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.44 ms: 1.09x faster                                                  |
| create_gc_cycles         | 800 us                                                      | 749 us: 1.07x faster                                                   |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                   |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.96 sec: 1.07x faster                                                 |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                                  |
| json                     | 3.10 ms                                                     | 2.95 ms: 1.05x faster                                                  |
| bench_thread_pool        | 913 us                                                      | 870 us: 1.05x faster                                                   |
| xml_etree_parse          | 96.8 ms                                                     | 92.8 ms: 1.04x faster                                                  |
| logging_format           | 6.73 us                                                     | 6.48 us: 1.04x faster                                                  |
| logging_simple           | 6.28 us                                                     | 6.06 us: 1.04x faster                                                  |
| pickle_list              | 2.69 us                                                     | 2.63 us: 1.02x faster                                                  |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.0 ms: 1.02x faster                                                  |
| xml_etree_generate       | 54.5 ms                                                     | 53.4 ms: 1.02x faster                                                  |
| fannkuch                 | 258 ms                                                      | 255 ms: 1.01x faster                                                   |
| pickle                   | 6.87 us                                                     | 6.81 us: 1.01x faster                                                  |
| scimark_fft              | 187 ms                                                      | 186 ms: 1.01x faster                                                   |
| meteor_contest           | 73.8 ms                                                     | 73.5 ms: 1.01x faster                                                  |
| pickle_dict              | 17.1 us                                                     | 17.4 us: 1.01x slower                                                  |
| regex_v8                 | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                                  |
| python_startup           | 19.7 ms                                                     | 20.0 ms: 1.02x slower                                                  |
| regex_effbot             | 1.56 ms                                                     | 1.62 ms: 1.03x slower                                                  |
| nbody                    | 71.0 ms                                                     | 73.6 ms: 1.04x slower                                                  |
| async_generators         | 219 ms                                                      | 232 ms: 1.06x slower                                                   |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                                  |
| bench_mp_pool            | 59.9 ms                                                     | 64.6 ms: 1.08x slower                                                  |
| pathlib                  | 72.8 ms                                                     | 82.9 ms: 1.14x slower                                                  |
| python_startup_no_site   | 15.3 ms                                                     | 17.9 ms: 1.17x slower                                                  |
| telco                    | 3.82 ms                                                     | 4.64 ms: 1.22x slower                                                  |
| coverage                 | 38.4 ms                                                     | 47.5 ms: 1.24x slower                                                  |
| Geometric mean           | (ref)                                                       | 1.21x faster                                                           |

Benchmark hidden because not significant (3): unpickle_list, unpack_sequence, pidigits
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-04300ec/bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.14x
