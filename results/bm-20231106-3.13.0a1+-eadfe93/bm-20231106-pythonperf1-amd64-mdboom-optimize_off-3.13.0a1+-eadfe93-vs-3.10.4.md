
# Results vs. 3.10.4

- fork: mdboom
- ref: optimize_off
- machine: windows-amd64
- commit hash: eadfe93
- commit date: 2023-11-06
- overall geometric mean: 1.26x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 305 ms: 1.28x slower                                                |
| chameleon      | 6.02 ms                                                     | 8.28 ms: 1.38x slower                                               |
| docutils       | 1.88 sec                                                    | 2.09 sec: 1.12x slower                                              |
| Geometric mean | (ref)                                                       | 1.19x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|-------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 363 ms: 1.17x faster                                                |
| async_tree_io           | 1.07 sec                                                    | 919 ms: 1.16x faster                                                |
| async_tree_memoization  | 505 ms                                                      | 456 ms: 1.11x faster                                                |
| async_tree_cpu_io_mixed | 617 ms                                                      | 591 ms: 1.04x faster                                                |
| Geometric mean          | (ref)                                                       | 1.12x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 146 ms                                                      | 153 ms: 1.04x slower                                                |
| float          | 61.7 ms                                                     | 92.6 ms: 1.50x slower                                               |
| nbody          | 71.0 ms                                                     | 129 ms: 1.82x slower                                                |
| Geometric mean | (ref)                                                       | 1.42x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 129 ms                                                      | 119 ms: 1.09x faster                                                |
| regex_v8       | 15.0 ms                                                     | 18.7 ms: 1.24x slower                                               |
| regex_compile  | 102 ms                                                      | 132 ms: 1.29x slower                                                |
| regex_effbot   | 1.56 ms                                                     | 2.04 ms: 1.31x slower                                               |
| Geometric mean | (ref)                                                       | 1.18x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 8.58 ms: 1.02x faster                                               |
| unpickle_list        | 2.68 us                                                     | 2.85 us: 1.06x slower                                               |
| xml_etree_parse      | 96.8 ms                                                     | 109 ms: 1.13x slower                                                |
| pickle_dict          | 17.1 us                                                     | 20.1 us: 1.17x slower                                               |
| unpickle             | 9.11 us                                                     | 10.7 us: 1.18x slower                                               |
| pickle               | 6.87 us                                                     | 8.11 us: 1.18x slower                                               |
| pickle_list          | 2.69 us                                                     | 3.28 us: 1.22x slower                                               |
| xml_etree_iterparse  | 64.5 ms                                                     | 91.0 ms: 1.41x slower                                               |
| tomli_loads          | 1.65 sec                                                    | 2.33 sec: 1.41x slower                                              |
| pickle_pure_python   | 259 us                                                      | 385 us: 1.49x slower                                                |
| json_loads           | 14.2 us                                                     | 21.3 us: 1.50x slower                                               |
| xml_etree_process    | 43.1 ms                                                     | 68.0 ms: 1.58x slower                                               |
| xml_etree_generate   | 54.5 ms                                                     | 92.6 ms: 1.70x slower                                               |
| unpickle_pure_python | 177 us                                                      | 301 us: 1.70x slower                                                |
| Geometric mean       | (ref)                                                       | 1.32x slower                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 21.6 ms: 1.10x slower                                               |
| python_startup_no_site | 15.3 ms                                                     | 19.5 ms: 1.27x slower                                               |
| Geometric mean         | (ref)                                                       | 1.18x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 12.1 ms: 1.35x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93 |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 116 us: 2.91x faster                                                |
| sqlglot_normalize        | 207 ms                                                      | 113 ms: 1.82x faster                                                |
| asyncio_tcp              | 717 ms                                                      | 508 ms: 1.41x faster                                                |
| mypy2                    | 347 ms                                                      | 287 ms: 1.21x faster                                                |
| async_tree_none          | 424 ms                                                      | 363 ms: 1.17x faster                                                |
| async_tree_io            | 1.07 sec                                                    | 919 ms: 1.16x faster                                                |
| async_tree_memoization   | 505 ms                                                      | 456 ms: 1.11x faster                                                |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.92 sec: 1.09x faster                                              |
| regex_dna                | 129 ms                                                      | 119 ms: 1.09x faster                                                |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 591 ms: 1.04x faster                                                |
| dulwich_log              | 48.6 ms                                                     | 46.9 ms: 1.04x faster                                               |
| json_dumps               | 8.77 ms                                                     | 8.58 ms: 1.02x faster                                               |
| sqlite_synth             | 1.90 us                                                     | 1.89 us: 1.00x faster                                               |
| pidigits                 | 146 ms                                                      | 153 ms: 1.04x slower                                                |
| mdp                      | 1.71 sec                                                    | 1.81 sec: 1.06x slower                                              |
| unpickle_list            | 2.68 us                                                     | 2.85 us: 1.06x slower                                               |
| sympy_sum                | 105 ms                                                      | 114 ms: 1.08x slower                                                |
| python_startup           | 19.7 ms                                                     | 21.6 ms: 1.10x slower                                               |
| docutils                 | 1.88 sec                                                    | 2.09 sec: 1.12x slower                                              |
| sympy_str                | 193 ms                                                      | 217 ms: 1.12x slower                                                |
| xml_etree_parse          | 96.8 ms                                                     | 109 ms: 1.13x slower                                                |
| pathlib                  | 72.8 ms                                                     | 83.4 ms: 1.14x slower                                               |
| bench_thread_pool        | 913 us                                                      | 1.05 ms: 1.15x slower                                               |
| sympy_expand             | 320 ms                                                      | 370 ms: 1.16x slower                                                |
| pickle_dict              | 17.1 us                                                     | 20.1 us: 1.17x slower                                               |
| unpickle                 | 9.11 us                                                     | 10.7 us: 1.18x slower                                               |
| pickle                   | 6.87 us                                                     | 8.11 us: 1.18x slower                                               |
| sympy_integrate          | 15.0 ms                                                     | 17.8 ms: 1.19x slower                                               |
| sqlglot_parse            | 1.20 ms                                                     | 1.45 ms: 1.21x slower                                               |
| pickle_list              | 2.69 us                                                     | 3.28 us: 1.22x slower                                               |
| crypto_pyaes             | 63.1 ms                                                     | 76.9 ms: 1.22x slower                                               |
| bench_mp_pool            | 59.9 ms                                                     | 73.7 ms: 1.23x slower                                               |
| sqlglot_transpile        | 1.45 ms                                                     | 1.79 ms: 1.24x slower                                               |
| regex_v8                 | 15.0 ms                                                     | 18.7 ms: 1.24x slower                                               |
| python_startup_no_site   | 15.3 ms                                                     | 19.5 ms: 1.27x slower                                               |
| deltablue                | 4.12 ms                                                     | 5.23 ms: 1.27x slower                                               |
| comprehensions           | 16.6 us                                                     | 21.2 us: 1.28x slower                                               |
| 2to3                     | 239 ms                                                      | 305 ms: 1.28x slower                                                |
| pyflate                  | 402 ms                                                      | 515 ms: 1.28x slower                                                |
| pycparser                | 905 ms                                                      | 1.16 sec: 1.29x slower                                              |
| chaos                    | 59.5 ms                                                     | 76.6 ms: 1.29x slower                                               |
| regex_compile            | 102 ms                                                      | 132 ms: 1.29x slower                                                |
| regex_effbot             | 1.56 ms                                                     | 2.04 ms: 1.31x slower                                               |
| raytrace                 | 266 ms                                                      | 349 ms: 1.31x slower                                                |
| meteor_contest           | 73.8 ms                                                     | 97.9 ms: 1.33x slower                                               |
| json                     | 3.10 ms                                                     | 4.12 ms: 1.33x slower                                               |
| mako                     | 8.98 ms                                                     | 12.1 ms: 1.35x slower                                               |
| richards_super           | 50.3 ms                                                     | 68.5 ms: 1.36x slower                                               |
| sqlglot_optimize         | 39.4 ms                                                     | 54.2 ms: 1.37x slower                                               |
| chameleon                | 6.02 ms                                                     | 8.28 ms: 1.38x slower                                               |
| go                       | 135 ms                                                      | 190 ms: 1.40x slower                                                |
| xml_etree_iterparse      | 64.5 ms                                                     | 91.0 ms: 1.41x slower                                               |
| tomli_loads              | 1.65 sec                                                    | 2.33 sec: 1.41x slower                                              |
| generators               | 31.8 ms                                                     | 45.2 ms: 1.42x slower                                               |
| nqueens                  | 68.3 ms                                                     | 98.7 ms: 1.45x slower                                               |
| pickle_pure_python       | 259 us                                                      | 385 us: 1.49x slower                                                |
| json_loads               | 14.2 us                                                     | 21.3 us: 1.50x slower                                               |
| scimark_monte_carlo      | 58.0 ms                                                     | 86.9 ms: 1.50x slower                                               |
| pprint_pformat           | 1.22 sec                                                    | 1.83 sec: 1.50x slower                                              |
| float                    | 61.7 ms                                                     | 92.6 ms: 1.50x slower                                               |
| deepcopy                 | 259 us                                                      | 390 us: 1.50x slower                                                |
| pprint_safe_repr         | 594 ms                                                      | 898 ms: 1.51x slower                                                |
| richards                 | 40.6 ms                                                     | 61.7 ms: 1.52x slower                                               |
| gc_traversal             | 1.40 ms                                                     | 2.13 ms: 1.53x slower                                               |
| logging_format           | 6.73 us                                                     | 10.3 us: 1.54x slower                                               |
| hexiom                   | 5.59 ms                                                     | 8.61 ms: 1.54x slower                                               |
| scimark_lu               | 84.0 ms                                                     | 130 ms: 1.55x slower                                                |
| spectral_norm            | 78.9 ms                                                     | 123 ms: 1.56x slower                                                |
| deepcopy_reduce          | 2.22 us                                                     | 3.48 us: 1.57x slower                                               |
| logging_simple           | 6.28 us                                                     | 9.87 us: 1.57x slower                                               |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 4.20 ms: 1.57x slower                                               |
| xml_etree_process        | 43.1 ms                                                     | 68.0 ms: 1.58x slower                                               |
| unpack_sequence          | 40.0 ns                                                     | 63.4 ns: 1.58x slower                                               |
| scimark_sor              | 105 ms                                                      | 168 ms: 1.60x slower                                                |
| logging_silent           | 93.4 ns                                                     | 151 ns: 1.62x slower                                                |
| deepcopy_memo            | 29.0 us                                                     | 47.6 us: 1.64x slower                                               |
| scimark_fft              | 187 ms                                                      | 308 ms: 1.64x slower                                                |
| fannkuch                 | 258 ms                                                      | 426 ms: 1.65x slower                                                |
| coverage                 | 38.4 ms                                                     | 64.3 ms: 1.68x slower                                               |
| xml_etree_generate       | 54.5 ms                                                     | 92.6 ms: 1.70x slower                                               |
| unpickle_pure_python     | 177 us                                                      | 301 us: 1.70x slower                                                |
| async_generators         | 219 ms                                                      | 375 ms: 1.71x slower                                                |
| telco                    | 3.82 ms                                                     | 6.55 ms: 1.72x slower                                               |
| coroutines               | 15.5 ms                                                     | 27.5 ms: 1.78x slower                                               |
| nbody                    | 71.0 ms                                                     | 129 ms: 1.82x slower                                                |
| Geometric mean           | (ref)                                                       | 1.26x slower                                                        |

Benchmark hidden because not significant (2): tornado_http, create_gc_cycles
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231106-3.13.0a1+-eadfe93/bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-eadfe93.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.22x
- 95% likely to have a slowdown of 1.19x
- 99% likely to have a slowdown of 1.16x
