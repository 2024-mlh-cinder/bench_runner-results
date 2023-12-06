
# Results vs. 3.10.4

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: darwin-arm64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.18x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 160 ms: 1.18x faster                                                  |
| chameleon      | 6.00 ms                                                             | 4.29 ms: 1.40x faster                                                 |
| docutils       | 1.71 sec                                                            | 1.43 sec: 1.19x faster                                                |
| html5lib       | 41.2 ms                                                             | 33.4 ms: 1.23x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 70.7 ms: 1.26x faster                                                 |
| Geometric mean | (ref)                                                               | 1.25x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization  | 466 ms                                                              | 329 ms: 1.41x faster                                                  |
| async_tree_none         | 381 ms                                                              | 281 ms: 1.35x faster                                                  |
| async_tree_io           | 972 ms                                                              | 725 ms: 1.34x faster                                                  |
| async_tree_cpu_io_mixed | 640 ms                                                              | 522 ms: 1.23x faster                                                  |
| Geometric mean          | (ref)                                                               | 1.33x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 68.8 ms: 1.29x faster                                                 |
| float          | 66.8 ms                                                             | 56.0 ms: 1.19x faster                                                 |
| pidigits       | 281 ms                                                              | 280 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                               | 1.15x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 72.7 ms: 1.28x faster                                                 |
| regex_dna      | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| regex_v8       | 17.2 ms                                                             | 15.0 ms: 1.15x faster                                                 |
| regex_effbot   | 2.46 ms                                                             | 2.44 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                               | 1.15x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 200 us: 1.36x faster                                                  |
| xml_etree_process    | 45.8 ms                                                             | 34.2 ms: 1.34x faster                                                 |
| json_dumps           | 7.95 ms                                                             | 5.97 ms: 1.33x faster                                                 |
| unpickle_pure_python | 190 us                                                              | 149 us: 1.27x faster                                                  |
| tomli_loads          | 1.66 sec                                                            | 1.40 sec: 1.19x faster                                                |
| xml_etree_generate   | 52.4 ms                                                             | 46.0 ms: 1.14x faster                                                 |
| xml_etree_parse      | 108 ms                                                              | 95.4 ms: 1.13x faster                                                 |
| unpickle             | 8.88 us                                                             | 8.39 us: 1.06x faster                                                 |
| unpickle_list        | 2.86 us                                                             | 2.73 us: 1.05x faster                                                 |
| json_loads           | 16.3 us                                                             | 15.6 us: 1.04x faster                                                 |
| xml_etree_iterparse  | 71.9 ms                                                             | 69.2 ms: 1.04x faster                                                 |
| pickle_list          | 2.70 us                                                             | 2.64 us: 1.02x faster                                                 |
| pickle_dict          | 16.9 us                                                             | 17.1 us: 1.02x slower                                                 |
| pickle               | 7.01 us                                                             | 7.14 us: 1.02x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.13x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 11.4 ms: 1.04x faster                                                 |
| python_startup_no_site | 8.83 ms                                                             | 9.43 ms: 1.07x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.01x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 9.78 ms                                                             | 7.55 ms: 1.30x faster                                                 |
| django_template | 25.5 ms                                                             | 19.7 ms: 1.29x faster                                                 |
| genshi_xml      | 33.6 ms                                                             | 28.3 ms: 1.19x faster                                                 |
| genshi_text     | 17.0 ms                                                             | 14.9 ms: 1.15x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.23x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|--------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.67 ms: 1.85x faster                                                 |
| logging_silent           | 114 ns                                                              | 65.2 ns: 1.75x faster                                                 |
| richards                 | 47.7 ms                                                             | 30.2 ms: 1.58x faster                                                 |
| richards_super           | 57.4 ms                                                             | 36.7 ms: 1.56x faster                                                 |
| scimark_lu               | 102 ms                                                              | 67.0 ms: 1.52x faster                                                 |
| crypto_pyaes             | 70.7 ms                                                             | 49.0 ms: 1.44x faster                                                 |
| spectral_norm            | 101 ms                                                              | 70.9 ms: 1.43x faster                                                 |
| async_tree_memoization   | 466 ms                                                              | 329 ms: 1.41x faster                                                  |
| chameleon                | 6.00 ms                                                             | 4.29 ms: 1.40x faster                                                 |
| pickle_pure_python       | 272 us                                                              | 200 us: 1.36x faster                                                  |
| async_tree_none          | 381 ms                                                              | 281 ms: 1.35x faster                                                  |
| xml_etree_process        | 45.8 ms                                                             | 34.2 ms: 1.34x faster                                                 |
| async_tree_io            | 972 ms                                                              | 725 ms: 1.34x faster                                                  |
| raytrace                 | 293 ms                                                              | 220 ms: 1.34x faster                                                  |
| thrift                   | 565 us                                                              | 424 us: 1.33x faster                                                  |
| json_dumps               | 7.95 ms                                                             | 5.97 ms: 1.33x faster                                                 |
| pycparser                | 863 ms                                                              | 660 ms: 1.31x faster                                                  |
| scimark_sor              | 134 ms                                                              | 103 ms: 1.30x faster                                                  |
| mako                     | 9.78 ms                                                             | 7.55 ms: 1.30x faster                                                 |
| pprint_safe_repr         | 625 ms                                                              | 483 ms: 1.29x faster                                                  |
| django_template          | 25.5 ms                                                             | 19.7 ms: 1.29x faster                                                 |
| chaos                    | 64.0 ms                                                             | 49.7 ms: 1.29x faster                                                 |
| go                       | 148 ms                                                              | 115 ms: 1.29x faster                                                  |
| nbody                    | 88.4 ms                                                             | 68.8 ms: 1.29x faster                                                 |
| pprint_pformat           | 1.28 sec                                                            | 998 ms: 1.28x faster                                                  |
| regex_compile            | 92.8 ms                                                             | 72.7 ms: 1.28x faster                                                 |
| pyflate                  | 420 ms                                                              | 329 ms: 1.28x faster                                                  |
| unpickle_pure_python     | 190 us                                                              | 149 us: 1.27x faster                                                  |
| create_gc_cycles         | 870 us                                                              | 683 us: 1.27x faster                                                  |
| sqlglot_parse            | 1.20 ms                                                             | 954 us: 1.26x faster                                                  |
| tornado_http             | 89.1 ms                                                             | 70.7 ms: 1.26x faster                                                 |
| sqlglot_transpile        | 1.40 ms                                                             | 1.12 ms: 1.26x faster                                                 |
| hexiom                   | 6.05 ms                                                             | 4.83 ms: 1.25x faster                                                 |
| html5lib                 | 41.2 ms                                                             | 33.4 ms: 1.23x faster                                                 |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 2.64 ms: 1.23x faster                                                 |
| deepcopy_memo            | 33.2 us                                                             | 27.1 us: 1.23x faster                                                 |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 522 ms: 1.23x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 28.7 ms: 1.22x faster                                                 |
| logging_simple           | 4.25 us                                                             | 3.53 us: 1.21x faster                                                 |
| scimark_monte_carlo      | 63.2 ms                                                             | 52.5 ms: 1.20x faster                                                 |
| logging_format           | 4.59 us                                                             | 3.82 us: 1.20x faster                                                 |
| deepcopy                 | 269 us                                                              | 225 us: 1.19x faster                                                  |
| float                    | 66.8 ms                                                             | 56.0 ms: 1.19x faster                                                 |
| docutils                 | 1.71 sec                                                            | 1.43 sec: 1.19x faster                                                |
| tomli_loads              | 1.66 sec                                                            | 1.40 sec: 1.19x faster                                                |
| genshi_xml               | 33.6 ms                                                             | 28.3 ms: 1.19x faster                                                 |
| deepcopy_reduce          | 2.27 us                                                             | 1.92 us: 1.18x faster                                                 |
| regex_dna                | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| sqlglot_optimize         | 36.3 ms                                                             | 30.7 ms: 1.18x faster                                                 |
| 2to3                     | 189 ms                                                              | 160 ms: 1.18x faster                                                  |
| scimark_fft              | 216 ms                                                              | 186 ms: 1.16x faster                                                  |
| bench_thread_pool        | 534 us                                                              | 463 us: 1.15x faster                                                  |
| regex_v8                 | 17.2 ms                                                             | 15.0 ms: 1.15x faster                                                 |
| sympy_integrate          | 12.9 ms                                                             | 11.2 ms: 1.15x faster                                                 |
| genshi_text              | 17.0 ms                                                             | 14.9 ms: 1.15x faster                                                 |
| unpack_sequence          | 38.7 ns                                                             | 33.8 ns: 1.15x faster                                                 |
| xml_etree_generate       | 52.4 ms                                                             | 46.0 ms: 1.14x faster                                                 |
| async_generators         | 230 ms                                                              | 203 ms: 1.14x faster                                                  |
| xml_etree_parse          | 108 ms                                                              | 95.4 ms: 1.13x faster                                                 |
| fannkuch                 | 295 ms                                                              | 260 ms: 1.13x faster                                                  |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.43 sec: 1.13x faster                                                |
| sympy_str                | 165 ms                                                              | 146 ms: 1.13x faster                                                  |
| sympy_expand             | 268 ms                                                              | 238 ms: 1.12x faster                                                  |
| sqlglot_normalize        | 187 ms                                                              | 167 ms: 1.12x faster                                                  |
| sympy_sum                | 91.1 ms                                                             | 82.6 ms: 1.10x faster                                                 |
| json                     | 3.04 ms                                                             | 2.79 ms: 1.09x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.15 ms: 1.08x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.74 sec: 1.07x faster                                                |
| nqueens                  | 62.5 ms                                                             | 58.8 ms: 1.06x faster                                                 |
| unpickle                 | 8.88 us                                                             | 8.39 us: 1.06x faster                                                 |
| comprehensions           | 16.8 us                                                             | 15.9 us: 1.06x faster                                                 |
| unpickle_list            | 2.86 us                                                             | 2.73 us: 1.05x faster                                                 |
| json_loads               | 16.3 us                                                             | 15.6 us: 1.04x faster                                                 |
| pathlib                  | 24.0 ms                                                             | 23.1 ms: 1.04x faster                                                 |
| xml_etree_iterparse      | 71.9 ms                                                             | 69.2 ms: 1.04x faster                                                 |
| python_startup           | 11.8 ms                                                             | 11.4 ms: 1.04x faster                                                 |
| asyncio_tcp              | 682 ms                                                              | 658 ms: 1.04x faster                                                  |
| typing_runtime_protocols | 335 us                                                              | 325 us: 1.03x faster                                                  |
| meteor_contest           | 77.6 ms                                                             | 75.6 ms: 1.03x faster                                                 |
| sqlite_synth             | 1.45 us                                                             | 1.42 us: 1.02x faster                                                 |
| pickle_list              | 2.70 us                                                             | 2.64 us: 1.02x faster                                                 |
| coroutines               | 19.7 ms                                                             | 19.3 ms: 1.02x faster                                                 |
| regex_effbot             | 2.46 ms                                                             | 2.44 ms: 1.01x faster                                                 |
| pidigits                 | 281 ms                                                              | 280 ms: 1.00x faster                                                  |
| gc_traversal             | 2.38 ms                                                             | 2.39 ms: 1.00x slower                                                 |
| pickle_dict              | 16.9 us                                                             | 17.1 us: 1.02x slower                                                 |
| pickle                   | 7.01 us                                                             | 7.14 us: 1.02x slower                                                 |
| bench_mp_pool            | 40.0 ms                                                             | 42.2 ms: 1.05x slower                                                 |
| python_startup_no_site   | 8.83 ms                                                             | 9.43 ms: 1.07x slower                                                 |
| generators               | 32.1 ms                                                             | 36.6 ms: 1.14x slower                                                 |
| dask                     | 251 ms                                                              | 320 ms: 1.27x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.18x faster                                                          |

Benchmark hidden because not significant (1): asyncio_websockets
Ignored benchmarks (8) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, pylint, sqlalchemy_declarative, sqlalchemy_imperative
Ignored benchmarks (4) of results/bm-20221114-3.12.0a2-3b9d793/bm-20221114-darwin-arm64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.14x
