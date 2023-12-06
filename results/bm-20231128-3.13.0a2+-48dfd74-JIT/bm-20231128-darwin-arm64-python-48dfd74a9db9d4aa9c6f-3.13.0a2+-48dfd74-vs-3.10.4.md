
# Results vs. 3.10.4

- fork: python
- ref: 48dfd74a9db9d4aa9c6f
- machine: darwin-arm64
- commit hash: 48dfd74
- commit date: 2023-11-28
- overall geometric mean: 1.14x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 175 ms: 1.08x faster                                                   |
| chameleon      | 6.00 ms                                                             | 5.09 ms: 1.18x faster                                                  |
| docutils       | 1.71 sec                                                            | 1.51 sec: 1.13x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 71.3 ms: 1.25x faster                                                  |
| Geometric mean | (ref)                                                               | 1.16x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 381 ms                                                              | 255 ms: 1.49x faster                                                   |
| async_tree_memoization  | 466 ms                                                              | 333 ms: 1.40x faster                                                   |
| async_tree_io           | 972 ms                                                              | 707 ms: 1.38x faster                                                   |
| async_tree_cpu_io_mixed | 640 ms                                                              | 527 ms: 1.21x faster                                                   |
| Geometric mean          | (ref)                                                               | 1.37x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 66.8 ms                                                             | 58.5 ms: 1.14x faster                                                  |
| nbody          | 88.4 ms                                                             | 84.5 ms: 1.05x faster                                                  |
| pidigits       | 281 ms                                                              | 294 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                               | 1.05x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 80.0 ms: 1.16x faster                                                  |
| regex_dna      | 173 ms                                                              | 150 ms: 1.16x faster                                                   |
| regex_v8       | 17.2 ms                                                             | 16.9 ms: 1.02x faster                                                  |
| regex_effbot   | 2.46 ms                                                             | 2.57 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                               | 1.07x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 209 us: 1.30x faster                                                   |
| json_dumps           | 7.95 ms                                                             | 6.62 ms: 1.20x faster                                                  |
| unpickle_pure_python | 190 us                                                              | 165 us: 1.15x faster                                                   |
| xml_etree_process    | 45.8 ms                                                             | 41.2 ms: 1.11x faster                                                  |
| tomli_loads          | 1.66 sec                                                            | 1.61 sec: 1.03x faster                                                 |
| unpickle             | 8.88 us                                                             | 9.04 us: 1.02x slower                                                  |
| json_loads           | 16.3 us                                                             | 17.3 us: 1.06x slower                                                  |
| xml_etree_iterparse  | 71.9 ms                                                             | 76.8 ms: 1.07x slower                                                  |
| pickle               | 7.01 us                                                             | 7.53 us: 1.07x slower                                                  |
| pickle_list          | 2.70 us                                                             | 2.94 us: 1.09x slower                                                  |
| unpickle_list        | 2.86 us                                                             | 3.12 us: 1.09x slower                                                  |
| pickle_dict          | 16.9 us                                                             | 18.6 us: 1.10x slower                                                  |
| xml_etree_generate   | 52.4 ms                                                             | 58.4 ms: 1.11x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.01x faster                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 12.2 ms: 1.03x slower                                                  |
| python_startup_no_site | 8.83 ms                                                             | 10.9 ms: 1.24x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.13x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-----------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.78 ms                                                             | 7.75 ms: 1.26x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|--------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 335 us                                                              | 78.0 us: 4.29x faster                                                  |
| deltablue                | 4.93 ms                                                             | 2.44 ms: 2.02x faster                                                  |
| logging_silent           | 114 ns                                                              | 70.3 ns: 1.63x faster                                                  |
| raytrace                 | 293 ms                                                              | 183 ms: 1.60x faster                                                   |
| asyncio_tcp              | 682 ms                                                              | 428 ms: 1.59x faster                                                   |
| async_tree_none          | 381 ms                                                              | 255 ms: 1.49x faster                                                   |
| chaos                    | 64.0 ms                                                             | 43.0 ms: 1.49x faster                                                  |
| richards_super           | 57.4 ms                                                             | 39.0 ms: 1.47x faster                                                  |
| sqlglot_parse            | 1.20 ms                                                             | 831 us: 1.45x faster                                                   |
| crypto_pyaes             | 70.7 ms                                                             | 49.0 ms: 1.44x faster                                                  |
| async_tree_memoization   | 466 ms                                                              | 333 ms: 1.40x faster                                                   |
| go                       | 148 ms                                                              | 106 ms: 1.39x faster                                                   |
| sqlglot_transpile        | 1.40 ms                                                             | 1.01 ms: 1.39x faster                                                  |
| async_tree_io            | 972 ms                                                              | 707 ms: 1.38x faster                                                   |
| richards                 | 47.7 ms                                                             | 34.8 ms: 1.37x faster                                                  |
| scimark_lu               | 102 ms                                                              | 75.1 ms: 1.36x faster                                                  |
| spectral_norm            | 101 ms                                                              | 74.9 ms: 1.35x faster                                                  |
| unpack_sequence          | 38.7 ns                                                             | 28.8 ns: 1.34x faster                                                  |
| comprehensions           | 16.8 us                                                             | 12.7 us: 1.33x faster                                                  |
| pickle_pure_python       | 272 us                                                              | 209 us: 1.30x faster                                                   |
| scimark_monte_carlo      | 63.2 ms                                                             | 48.6 ms: 1.30x faster                                                  |
| deepcopy_memo            | 33.2 us                                                             | 26.0 us: 1.28x faster                                                  |
| mako                     | 9.78 ms                                                             | 7.75 ms: 1.26x faster                                                  |
| tornado_http             | 89.1 ms                                                             | 71.3 ms: 1.25x faster                                                  |
| scimark_sor              | 134 ms                                                              | 108 ms: 1.25x faster                                                   |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.30 sec: 1.24x faster                                                 |
| generators               | 32.1 ms                                                             | 26.1 ms: 1.23x faster                                                  |
| pyflate                  | 420 ms                                                              | 344 ms: 1.22x faster                                                   |
| pycparser                | 863 ms                                                              | 709 ms: 1.22x faster                                                   |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 527 ms: 1.21x faster                                                   |
| create_gc_cycles         | 870 us                                                              | 724 us: 1.20x faster                                                   |
| hexiom                   | 6.05 ms                                                             | 5.04 ms: 1.20x faster                                                  |
| json_dumps               | 7.95 ms                                                             | 6.62 ms: 1.20x faster                                                  |
| sympy_sum                | 91.1 ms                                                             | 76.2 ms: 1.20x faster                                                  |
| chameleon                | 6.00 ms                                                             | 5.09 ms: 1.18x faster                                                  |
| logging_simple           | 4.25 us                                                             | 3.62 us: 1.17x faster                                                  |
| logging_format           | 4.59 us                                                             | 3.91 us: 1.17x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 30.0 ms: 1.16x faster                                                  |
| pprint_pformat           | 1.28 sec                                                            | 1.10 sec: 1.16x faster                                                 |
| regex_compile            | 92.8 ms                                                             | 80.0 ms: 1.16x faster                                                  |
| regex_dna                | 173 ms                                                              | 150 ms: 1.16x faster                                                   |
| deepcopy                 | 269 us                                                              | 233 us: 1.16x faster                                                   |
| unpickle_pure_python     | 190 us                                                              | 165 us: 1.15x faster                                                   |
| sympy_integrate          | 12.9 ms                                                             | 11.2 ms: 1.15x faster                                                  |
| float                    | 66.8 ms                                                             | 58.5 ms: 1.14x faster                                                  |
| docutils                 | 1.71 sec                                                            | 1.51 sec: 1.13x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.67 sec: 1.12x faster                                                 |
| sympy_str                | 165 ms                                                              | 148 ms: 1.11x faster                                                   |
| pprint_safe_repr         | 625 ms                                                              | 562 ms: 1.11x faster                                                   |
| xml_etree_process        | 45.8 ms                                                             | 41.2 ms: 1.11x faster                                                  |
| dask                     | 251 ms                                                              | 229 ms: 1.10x faster                                                   |
| deepcopy_reduce          | 2.27 us                                                             | 2.09 us: 1.09x faster                                                  |
| 2to3                     | 189 ms                                                              | 175 ms: 1.08x faster                                                   |
| sympy_expand             | 268 ms                                                              | 255 ms: 1.05x faster                                                   |
| nbody                    | 88.4 ms                                                             | 84.5 ms: 1.05x faster                                                  |
| bench_thread_pool        | 534 us                                                              | 514 us: 1.04x faster                                                   |
| tomli_loads              | 1.66 sec                                                            | 1.61 sec: 1.03x faster                                                 |
| meteor_contest           | 77.6 ms                                                             | 75.3 ms: 1.03x faster                                                  |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 3.18 ms: 1.02x faster                                                  |
| coroutines               | 19.7 ms                                                             | 19.3 ms: 1.02x faster                                                  |
| scimark_fft              | 216 ms                                                              | 212 ms: 1.02x faster                                                   |
| regex_v8                 | 17.2 ms                                                             | 16.9 ms: 1.02x faster                                                  |
| sqlglot_optimize         | 36.3 ms                                                             | 35.7 ms: 1.01x faster                                                  |
| asyncio_websockets       | 408 ms                                                              | 408 ms: 1.00x slower                                                   |
| fannkuch                 | 295 ms                                                              | 296 ms: 1.00x slower                                                   |
| gc_traversal             | 2.38 ms                                                             | 2.42 ms: 1.02x slower                                                  |
| unpickle                 | 8.88 us                                                             | 9.04 us: 1.02x slower                                                  |
| sqlglot_normalize        | 187 ms                                                              | 192 ms: 1.03x slower                                                   |
| python_startup           | 11.8 ms                                                             | 12.2 ms: 1.03x slower                                                  |
| nqueens                  | 62.5 ms                                                             | 64.9 ms: 1.04x slower                                                  |
| pidigits                 | 281 ms                                                              | 294 ms: 1.04x slower                                                   |
| regex_effbot             | 2.46 ms                                                             | 2.57 ms: 1.05x slower                                                  |
| pathlib                  | 24.0 ms                                                             | 25.2 ms: 1.05x slower                                                  |
| json_loads               | 16.3 us                                                             | 17.3 us: 1.06x slower                                                  |
| xml_etree_iterparse      | 71.9 ms                                                             | 76.8 ms: 1.07x slower                                                  |
| pickle                   | 7.01 us                                                             | 7.53 us: 1.07x slower                                                  |
| pickle_list              | 2.70 us                                                             | 2.94 us: 1.09x slower                                                  |
| unpickle_list            | 2.86 us                                                             | 3.12 us: 1.09x slower                                                  |
| pickle_dict              | 16.9 us                                                             | 18.6 us: 1.10x slower                                                  |
| bench_mp_pool            | 40.0 ms                                                             | 44.5 ms: 1.11x slower                                                  |
| xml_etree_generate       | 52.4 ms                                                             | 58.4 ms: 1.11x slower                                                  |
| sqlite_synth             | 1.45 us                                                             | 1.66 us: 1.15x slower                                                  |
| coverage                 | 41.0 ms                                                             | 47.9 ms: 1.17x slower                                                  |
| python_startup_no_site   | 8.83 ms                                                             | 10.9 ms: 1.24x slower                                                  |
| async_generators         | 230 ms                                                              | 305 ms: 1.32x slower                                                   |
| telco                    | 3.41 ms                                                             | 4.71 ms: 1.38x slower                                                  |
| mypy2                    | 294 ms                                                              | 560 ms: 1.90x slower                                                   |
| Geometric mean           | (ref)                                                               | 1.14x faster                                                           |

Benchmark hidden because not significant (2): xml_etree_parse, json
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231128-3.13.0a2+-48dfd74-JIT/bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.06x
