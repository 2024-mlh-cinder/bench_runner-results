
# Results vs. 3.10.4

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: darwin-arm64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.21x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 158 ms: 1.20x faster                                                  |
| chameleon      | 6.00 ms                                                             | 4.21 ms: 1.43x faster                                                 |
| docutils       | 1.71 sec                                                            | 1.41 sec: 1.21x faster                                                |
| html5lib       | 41.2 ms                                                             | 32.3 ms: 1.27x faster                                                 |
| Geometric mean | (ref)                                                               | 1.27x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization  | 466 ms                                                              | 322 ms: 1.45x faster                                                  |
| async_tree_none         | 381 ms                                                              | 280 ms: 1.36x faster                                                  |
| async_tree_io           | 972 ms                                                              | 728 ms: 1.34x faster                                                  |
| async_tree_cpu_io_mixed | 640 ms                                                              | 521 ms: 1.23x faster                                                  |
| Geometric mean          | (ref)                                                               | 1.34x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 67.7 ms: 1.31x faster                                                 |
| float          | 66.8 ms                                                             | 55.5 ms: 1.20x faster                                                 |
| pidigits       | 281 ms                                                              | 280 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.17x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 72.1 ms: 1.29x faster                                                 |
| regex_dna      | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| regex_v8       | 17.2 ms                                                             | 15.0 ms: 1.15x faster                                                 |
| regex_effbot   | 2.46 ms                                                             | 2.44 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                               | 1.15x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 190 us: 1.43x faster                                                  |
| unpickle_pure_python | 190 us                                                              | 137 us: 1.39x faster                                                  |
| json_dumps           | 7.95 ms                                                             | 5.84 ms: 1.36x faster                                                 |
| xml_etree_process    | 45.8 ms                                                             | 33.8 ms: 1.36x faster                                                 |
| tomli_loads          | 1.66 sec                                                            | 1.28 sec: 1.29x faster                                                |
| xml_etree_parse      | 108 ms                                                              | 96.4 ms: 1.12x faster                                                 |
| xml_etree_generate   | 52.4 ms                                                             | 46.9 ms: 1.12x faster                                                 |
| unpickle             | 8.88 us                                                             | 8.43 us: 1.05x faster                                                 |
| json_loads           | 16.3 us                                                             | 15.5 us: 1.05x faster                                                 |
| xml_etree_iterparse  | 71.9 ms                                                             | 70.0 ms: 1.03x faster                                                 |
| unpickle_list        | 2.86 us                                                             | 2.81 us: 1.01x faster                                                 |
| pickle               | 7.01 us                                                             | 6.98 us: 1.00x faster                                                 |
| pickle_dict          | 16.9 us                                                             | 17.0 us: 1.01x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.15x faster                                                          |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 11.4 ms: 1.03x faster                                                 |
| python_startup_no_site | 8.83 ms                                                             | 9.54 ms: 1.08x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.02x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 9.78 ms                                                             | 7.76 ms: 1.26x faster                                                 |
| genshi_xml      | 33.6 ms                                                             | 27.3 ms: 1.23x faster                                                 |
| django_template | 25.5 ms                                                             | 20.8 ms: 1.22x faster                                                 |
| genshi_text     | 17.0 ms                                                             | 14.2 ms: 1.20x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.23x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|--------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.51 ms: 1.96x faster                                                 |
| logging_silent           | 114 ns                                                              | 63.9 ns: 1.79x faster                                                 |
| scimark_sor              | 134 ms                                                              | 83.4 ms: 1.61x faster                                                 |
| richards                 | 47.7 ms                                                             | 29.8 ms: 1.60x faster                                                 |
| richards_super           | 57.4 ms                                                             | 36.0 ms: 1.59x faster                                                 |
| asyncio_tcp              | 682 ms                                                              | 430 ms: 1.58x faster                                                  |
| scimark_lu               | 102 ms                                                              | 67.3 ms: 1.52x faster                                                 |
| async_tree_memoization   | 466 ms                                                              | 322 ms: 1.45x faster                                                  |
| pickle_pure_python       | 272 us                                                              | 190 us: 1.43x faster                                                  |
| spectral_norm            | 101 ms                                                              | 70.6 ms: 1.43x faster                                                 |
| chameleon                | 6.00 ms                                                             | 4.21 ms: 1.43x faster                                                 |
| raytrace                 | 293 ms                                                              | 208 ms: 1.41x faster                                                  |
| crypto_pyaes             | 70.7 ms                                                             | 50.4 ms: 1.40x faster                                                 |
| go                       | 148 ms                                                              | 106 ms: 1.40x faster                                                  |
| pyflate                  | 420 ms                                                              | 301 ms: 1.40x faster                                                  |
| unpickle_pure_python     | 190 us                                                              | 137 us: 1.39x faster                                                  |
| async_tree_none          | 381 ms                                                              | 280 ms: 1.36x faster                                                  |
| json_dumps               | 7.95 ms                                                             | 5.84 ms: 1.36x faster                                                 |
| xml_etree_process        | 45.8 ms                                                             | 33.8 ms: 1.36x faster                                                 |
| scimark_monte_carlo      | 63.2 ms                                                             | 46.8 ms: 1.35x faster                                                 |
| thrift                   | 565 us                                                              | 419 us: 1.35x faster                                                  |
| pycparser                | 863 ms                                                              | 643 ms: 1.34x faster                                                  |
| async_tree_io            | 972 ms                                                              | 728 ms: 1.34x faster                                                  |
| pprint_pformat           | 1.28 sec                                                            | 977 ms: 1.31x faster                                                  |
| nbody                    | 88.4 ms                                                             | 67.7 ms: 1.31x faster                                                 |
| pprint_safe_repr         | 625 ms                                                              | 480 ms: 1.30x faster                                                  |
| hexiom                   | 6.05 ms                                                             | 4.66 ms: 1.30x faster                                                 |
| tomli_loads              | 1.66 sec                                                            | 1.28 sec: 1.29x faster                                                |
| chaos                    | 64.0 ms                                                             | 49.5 ms: 1.29x faster                                                 |
| regex_compile            | 92.8 ms                                                             | 72.1 ms: 1.29x faster                                                 |
| unpack_sequence          | 38.7 ns                                                             | 30.2 ns: 1.28x faster                                                 |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.26 sec: 1.28x faster                                                |
| logging_format           | 4.59 us                                                             | 3.60 us: 1.27x faster                                                 |
| html5lib                 | 41.2 ms                                                             | 32.3 ms: 1.27x faster                                                 |
| logging_simple           | 4.25 us                                                             | 3.34 us: 1.27x faster                                                 |
| create_gc_cycles         | 870 us                                                              | 686 us: 1.27x faster                                                  |
| mako                     | 9.78 ms                                                             | 7.76 ms: 1.26x faster                                                 |
| dulwich_log              | 34.9 ms                                                             | 28.2 ms: 1.24x faster                                                 |
| genshi_xml               | 33.6 ms                                                             | 27.3 ms: 1.23x faster                                                 |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 521 ms: 1.23x faster                                                  |
| sqlglot_transpile        | 1.40 ms                                                             | 1.15 ms: 1.22x faster                                                 |
| django_template          | 25.5 ms                                                             | 20.8 ms: 1.22x faster                                                 |
| sqlglot_parse            | 1.20 ms                                                             | 985 us: 1.22x faster                                                  |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 2.66 ms: 1.22x faster                                                 |
| fannkuch                 | 295 ms                                                              | 244 ms: 1.21x faster                                                  |
| sqlglot_optimize         | 36.3 ms                                                             | 30.0 ms: 1.21x faster                                                 |
| docutils                 | 1.71 sec                                                            | 1.41 sec: 1.21x faster                                                |
| genshi_text              | 17.0 ms                                                             | 14.2 ms: 1.20x faster                                                 |
| float                    | 66.8 ms                                                             | 55.5 ms: 1.20x faster                                                 |
| deepcopy_memo            | 33.2 us                                                             | 27.7 us: 1.20x faster                                                 |
| 2to3                     | 189 ms                                                              | 158 ms: 1.20x faster                                                  |
| deepcopy                 | 269 us                                                              | 227 us: 1.19x faster                                                  |
| scimark_fft              | 216 ms                                                              | 182 ms: 1.19x faster                                                  |
| regex_dna                | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| deepcopy_reduce          | 2.27 us                                                             | 1.94 us: 1.17x faster                                                 |
| sympy_expand             | 268 ms                                                              | 230 ms: 1.16x faster                                                  |
| sympy_integrate          | 12.9 ms                                                             | 11.1 ms: 1.16x faster                                                 |
| bench_thread_pool        | 534 us                                                              | 460 us: 1.16x faster                                                  |
| async_generators         | 230 ms                                                              | 200 ms: 1.15x faster                                                  |
| sympy_str                | 165 ms                                                              | 144 ms: 1.15x faster                                                  |
| regex_v8                 | 17.2 ms                                                             | 15.0 ms: 1.15x faster                                                 |
| sqlglot_normalize        | 187 ms                                                              | 165 ms: 1.13x faster                                                  |
| coroutines               | 19.7 ms                                                             | 17.5 ms: 1.13x faster                                                 |
| xml_etree_parse          | 108 ms                                                              | 96.4 ms: 1.12x faster                                                 |
| xml_etree_generate       | 52.4 ms                                                             | 46.9 ms: 1.12x faster                                                 |
| sympy_sum                | 91.1 ms                                                             | 81.7 ms: 1.12x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.70 sec: 1.10x faster                                                |
| meteor_contest           | 77.6 ms                                                             | 71.1 ms: 1.09x faster                                                 |
| nqueens                  | 62.5 ms                                                             | 57.2 ms: 1.09x faster                                                 |
| json                     | 3.04 ms                                                             | 2.79 ms: 1.09x faster                                                 |
| sqlite_synth             | 1.45 us                                                             | 1.36 us: 1.06x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.22 ms: 1.06x faster                                                 |
| unpickle                 | 8.88 us                                                             | 8.43 us: 1.05x faster                                                 |
| json_loads               | 16.3 us                                                             | 15.5 us: 1.05x faster                                                 |
| typing_runtime_protocols | 335 us                                                              | 320 us: 1.05x faster                                                  |
| pathlib                  | 24.0 ms                                                             | 23.1 ms: 1.04x faster                                                 |
| python_startup           | 11.8 ms                                                             | 11.4 ms: 1.03x faster                                                 |
| xml_etree_iterparse      | 71.9 ms                                                             | 70.0 ms: 1.03x faster                                                 |
| unpickle_list            | 2.86 us                                                             | 2.81 us: 1.01x faster                                                 |
| comprehensions           | 16.8 us                                                             | 16.6 us: 1.01x faster                                                 |
| regex_effbot             | 2.46 ms                                                             | 2.44 ms: 1.01x faster                                                 |
| pidigits                 | 281 ms                                                              | 280 ms: 1.01x faster                                                  |
| pickle                   | 7.01 us                                                             | 6.98 us: 1.00x faster                                                 |
| asyncio_websockets       | 408 ms                                                              | 408 ms: 1.00x slower                                                  |
| pickle_dict              | 16.9 us                                                             | 17.0 us: 1.01x slower                                                 |
| bench_mp_pool            | 40.0 ms                                                             | 42.5 ms: 1.06x slower                                                 |
| python_startup_no_site   | 8.83 ms                                                             | 9.54 ms: 1.08x slower                                                 |
| generators               | 32.1 ms                                                             | 35.1 ms: 1.09x slower                                                 |
| dask                     | 251 ms                                                              | 309 ms: 1.23x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.21x faster                                                          |

Benchmark hidden because not significant (2): gc_traversal, pickle_list
Ignored benchmarks (9) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, pylint, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
Ignored benchmarks (4) of results/bm-20230110-3.12.0a4-3d5d3f7/bm-20230110-darwin-arm64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.17x
