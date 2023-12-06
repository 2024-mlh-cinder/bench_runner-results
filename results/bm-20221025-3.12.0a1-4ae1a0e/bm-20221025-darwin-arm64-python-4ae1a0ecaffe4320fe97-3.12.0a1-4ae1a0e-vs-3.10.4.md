
# Results vs. 3.10.4

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: darwin-arm64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.19x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 159 ms: 1.19x faster                                                  |
| chameleon      | 6.00 ms                                                             | 4.35 ms: 1.38x faster                                                 |
| docutils       | 1.71 sec                                                            | 1.45 sec: 1.17x faster                                                |
| html5lib       | 41.2 ms                                                             | 33.9 ms: 1.21x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 69.3 ms: 1.29x faster                                                 |
| Geometric mean | (ref)                                                               | 1.25x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization  | 466 ms                                                              | 322 ms: 1.45x faster                                                  |
| async_tree_none         | 381 ms                                                              | 281 ms: 1.35x faster                                                  |
| async_tree_io           | 972 ms                                                              | 723 ms: 1.34x faster                                                  |
| async_tree_cpu_io_mixed | 640 ms                                                              | 523 ms: 1.22x faster                                                  |
| Geometric mean          | (ref)                                                               | 1.34x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 69.0 ms: 1.28x faster                                                 |
| float          | 66.8 ms                                                             | 55.9 ms: 1.20x faster                                                 |
| pidigits       | 281 ms                                                              | 280 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                               | 1.15x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 73.0 ms: 1.27x faster                                                 |
| regex_dna      | 173 ms                                                              | 148 ms: 1.17x faster                                                  |
| regex_v8       | 17.2 ms                                                             | 15.0 ms: 1.14x faster                                                 |
| regex_effbot   | 2.46 ms                                                             | 2.44 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                               | 1.14x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_process    | 45.8 ms                                                             | 33.8 ms: 1.36x faster                                                 |
| pickle_pure_python   | 272 us                                                              | 201 us: 1.35x faster                                                  |
| json_dumps           | 7.95 ms                                                             | 6.04 ms: 1.31x faster                                                 |
| unpickle_pure_python | 190 us                                                              | 154 us: 1.24x faster                                                  |
| xml_etree_parse      | 108 ms                                                              | 90.9 ms: 1.19x faster                                                 |
| tomli_loads          | 1.66 sec                                                            | 1.42 sec: 1.17x faster                                                |
| xml_etree_generate   | 52.4 ms                                                             | 46.0 ms: 1.14x faster                                                 |
| unpickle_list        | 2.86 us                                                             | 2.52 us: 1.13x faster                                                 |
| unpickle             | 8.88 us                                                             | 8.27 us: 1.07x faster                                                 |
| xml_etree_iterparse  | 71.9 ms                                                             | 67.9 ms: 1.06x faster                                                 |
| json_loads           | 16.3 us                                                             | 15.6 us: 1.04x faster                                                 |
| pickle_dict          | 16.9 us                                                             | 16.9 us: 1.00x slower                                                 |
| pickle               | 7.01 us                                                             | 7.13 us: 1.02x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.14x faster                                                          |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 11.3 ms: 1.04x faster                                                 |
| python_startup_no_site | 8.83 ms                                                             | 9.36 ms: 1.06x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.01x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 9.78 ms                                                             | 7.66 ms: 1.28x faster                                                 |
| django_template | 25.5 ms                                                             | 20.0 ms: 1.28x faster                                                 |
| genshi_xml      | 33.6 ms                                                             | 28.4 ms: 1.18x faster                                                 |
| genshi_text     | 17.0 ms                                                             | 14.6 ms: 1.17x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.23x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|--------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| logging_silent           | 114 ns                                                              | 63.1 ns: 1.81x faster                                                 |
| deltablue                | 4.93 ms                                                             | 2.75 ms: 1.79x faster                                                 |
| scimark_lu               | 102 ms                                                              | 67.4 ms: 1.51x faster                                                 |
| richards_super           | 57.4 ms                                                             | 38.6 ms: 1.49x faster                                                 |
| richards                 | 47.7 ms                                                             | 32.5 ms: 1.47x faster                                                 |
| crypto_pyaes             | 70.7 ms                                                             | 48.4 ms: 1.46x faster                                                 |
| spectral_norm            | 101 ms                                                              | 69.5 ms: 1.45x faster                                                 |
| async_tree_memoization   | 466 ms                                                              | 322 ms: 1.45x faster                                                  |
| raytrace                 | 293 ms                                                              | 207 ms: 1.42x faster                                                  |
| chameleon                | 6.00 ms                                                             | 4.35 ms: 1.38x faster                                                 |
| thrift                   | 565 us                                                              | 415 us: 1.36x faster                                                  |
| xml_etree_process        | 45.8 ms                                                             | 33.8 ms: 1.36x faster                                                 |
| async_tree_none          | 381 ms                                                              | 281 ms: 1.35x faster                                                  |
| pickle_pure_python       | 272 us                                                              | 201 us: 1.35x faster                                                  |
| async_tree_io            | 972 ms                                                              | 723 ms: 1.34x faster                                                  |
| scimark_sor              | 134 ms                                                              | 100 ms: 1.34x faster                                                  |
| chaos                    | 64.0 ms                                                             | 48.6 ms: 1.32x faster                                                 |
| json_dumps               | 7.95 ms                                                             | 6.04 ms: 1.31x faster                                                 |
| pycparser                | 863 ms                                                              | 668 ms: 1.29x faster                                                  |
| go                       | 148 ms                                                              | 114 ms: 1.29x faster                                                  |
| hexiom                   | 6.05 ms                                                             | 4.68 ms: 1.29x faster                                                 |
| pprint_safe_repr         | 625 ms                                                              | 484 ms: 1.29x faster                                                  |
| pprint_pformat           | 1.28 sec                                                            | 990 ms: 1.29x faster                                                  |
| tornado_http             | 89.1 ms                                                             | 69.3 ms: 1.29x faster                                                 |
| nbody                    | 88.4 ms                                                             | 69.0 ms: 1.28x faster                                                 |
| sqlglot_parse            | 1.20 ms                                                             | 940 us: 1.28x faster                                                  |
| mako                     | 9.78 ms                                                             | 7.66 ms: 1.28x faster                                                 |
| django_template          | 25.5 ms                                                             | 20.0 ms: 1.28x faster                                                 |
| sqlglot_transpile        | 1.40 ms                                                             | 1.10 ms: 1.27x faster                                                 |
| regex_compile            | 92.8 ms                                                             | 73.0 ms: 1.27x faster                                                 |
| pyflate                  | 420 ms                                                              | 331 ms: 1.27x faster                                                  |
| create_gc_cycles         | 870 us                                                              | 687 us: 1.27x faster                                                  |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 2.61 ms: 1.24x faster                                                 |
| unpickle_pure_python     | 190 us                                                              | 154 us: 1.24x faster                                                  |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 523 ms: 1.22x faster                                                  |
| deepcopy_memo            | 33.2 us                                                             | 27.3 us: 1.22x faster                                                 |
| html5lib                 | 41.2 ms                                                             | 33.9 ms: 1.21x faster                                                 |
| dulwich_log              | 34.9 ms                                                             | 28.8 ms: 1.21x faster                                                 |
| float                    | 66.8 ms                                                             | 55.9 ms: 1.20x faster                                                 |
| scimark_monte_carlo      | 63.2 ms                                                             | 52.9 ms: 1.19x faster                                                 |
| logging_format           | 4.59 us                                                             | 3.85 us: 1.19x faster                                                 |
| 2to3                     | 189 ms                                                              | 159 ms: 1.19x faster                                                  |
| deepcopy                 | 269 us                                                              | 227 us: 1.19x faster                                                  |
| logging_simple           | 4.25 us                                                             | 3.58 us: 1.19x faster                                                 |
| xml_etree_parse          | 108 ms                                                              | 90.9 ms: 1.19x faster                                                 |
| sqlglot_optimize         | 36.3 ms                                                             | 30.5 ms: 1.19x faster                                                 |
| deepcopy_reduce          | 2.27 us                                                             | 1.92 us: 1.19x faster                                                 |
| genshi_xml               | 33.6 ms                                                             | 28.4 ms: 1.18x faster                                                 |
| async_generators         | 230 ms                                                              | 195 ms: 1.18x faster                                                  |
| docutils                 | 1.71 sec                                                            | 1.45 sec: 1.17x faster                                                |
| scimark_fft              | 216 ms                                                              | 185 ms: 1.17x faster                                                  |
| tomli_loads              | 1.66 sec                                                            | 1.42 sec: 1.17x faster                                                |
| genshi_text              | 17.0 ms                                                             | 14.6 ms: 1.17x faster                                                 |
| regex_dna                | 173 ms                                                              | 148 ms: 1.17x faster                                                  |
| bench_thread_pool        | 534 us                                                              | 457 us: 1.17x faster                                                  |
| sympy_integrate          | 12.9 ms                                                             | 11.1 ms: 1.16x faster                                                 |
| regex_v8                 | 17.2 ms                                                             | 15.0 ms: 1.14x faster                                                 |
| sympy_str                | 165 ms                                                              | 144 ms: 1.14x faster                                                  |
| sympy_expand             | 268 ms                                                              | 235 ms: 1.14x faster                                                  |
| xml_etree_generate       | 52.4 ms                                                             | 46.0 ms: 1.14x faster                                                 |
| unpack_sequence          | 38.7 ns                                                             | 34.1 ns: 1.14x faster                                                 |
| comprehensions           | 16.8 us                                                             | 14.8 us: 1.14x faster                                                 |
| unpickle_list            | 2.86 us                                                             | 2.52 us: 1.13x faster                                                 |
| fannkuch                 | 295 ms                                                              | 260 ms: 1.13x faster                                                  |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.43 sec: 1.13x faster                                                |
| nqueens                  | 62.5 ms                                                             | 55.6 ms: 1.12x faster                                                 |
| sqlglot_normalize        | 187 ms                                                              | 167 ms: 1.12x faster                                                  |
| sympy_sum                | 91.1 ms                                                             | 81.5 ms: 1.12x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.71 sec: 1.10x faster                                                |
| coroutines               | 19.7 ms                                                             | 18.0 ms: 1.09x faster                                                 |
| pylint                   | 279 ms                                                              | 255 ms: 1.09x faster                                                  |
| json                     | 3.04 ms                                                             | 2.82 ms: 1.08x faster                                                 |
| unpickle                 | 8.88 us                                                             | 8.27 us: 1.07x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.20 ms: 1.06x faster                                                 |
| generators               | 32.1 ms                                                             | 30.2 ms: 1.06x faster                                                 |
| xml_etree_iterparse      | 71.9 ms                                                             | 67.9 ms: 1.06x faster                                                 |
| json_loads               | 16.3 us                                                             | 15.6 us: 1.04x faster                                                 |
| typing_runtime_protocols | 335 us                                                              | 321 us: 1.04x faster                                                  |
| python_startup           | 11.8 ms                                                             | 11.3 ms: 1.04x faster                                                 |
| pathlib                  | 24.0 ms                                                             | 23.1 ms: 1.04x faster                                                 |
| asyncio_tcp              | 682 ms                                                              | 659 ms: 1.03x faster                                                  |
| sqlite_synth             | 1.45 us                                                             | 1.42 us: 1.02x faster                                                 |
| meteor_contest           | 77.6 ms                                                             | 76.4 ms: 1.02x faster                                                 |
| regex_effbot             | 2.46 ms                                                             | 2.44 ms: 1.01x faster                                                 |
| pidigits                 | 281 ms                                                              | 280 ms: 1.00x faster                                                  |
| asyncio_websockets       | 408 ms                                                              | 408 ms: 1.00x slower                                                  |
| pickle_dict              | 16.9 us                                                             | 16.9 us: 1.00x slower                                                 |
| gc_traversal             | 2.38 ms                                                             | 2.40 ms: 1.01x slower                                                 |
| pickle                   | 7.01 us                                                             | 7.13 us: 1.02x slower                                                 |
| bench_mp_pool            | 40.0 ms                                                             | 41.7 ms: 1.04x slower                                                 |
| python_startup_no_site   | 8.83 ms                                                             | 9.36 ms: 1.06x slower                                                 |
| dask                     | 251 ms                                                              | 322 ms: 1.28x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.19x faster                                                          |

Benchmark hidden because not significant (1): pickle_list
Ignored benchmarks (7) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, sqlalchemy_declarative, sqlalchemy_imperative
Ignored benchmarks (4) of results/bm-20221025-3.12.0a1-4ae1a0e/bm-20221025-darwin-arm64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.15x
