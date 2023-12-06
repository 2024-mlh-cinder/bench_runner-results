
# Results vs. 3.10.4

- fork: python
- ref: ed7c3ff15680c1939fad
- machine: darwin-arm64
- commit hash: ed7c3ff
- commit date: 2022-09-11
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 153 ms: 1.23x faster                                                   |
| chameleon      | 6.00 ms                                                             | 4.17 ms: 1.44x faster                                                  |
| docutils       | 1.71 sec                                                            | 1.43 sec: 1.19x faster                                                 |
| html5lib       | 41.2 ms                                                             | 33.3 ms: 1.24x faster                                                  |
| tornado_http   | 89.1 ms                                                             | 70.3 ms: 1.27x faster                                                  |
| Geometric mean | (ref)                                                               | 1.27x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_io           | 972 ms                                                              | 690 ms: 1.41x faster                                                   |
| async_tree_none         | 381 ms                                                              | 277 ms: 1.37x faster                                                   |
| async_tree_memoization  | 466 ms                                                              | 347 ms: 1.34x faster                                                   |
| async_tree_cpu_io_mixed | 640 ms                                                              | 515 ms: 1.24x faster                                                   |
| Geometric mean          | (ref)                                                               | 1.34x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 68.4 ms: 1.29x faster                                                  |
| float          | 66.8 ms                                                             | 55.7 ms: 1.20x faster                                                  |
| pidigits       | 281 ms                                                              | 280 ms: 1.01x faster                                                   |
| Geometric mean | (ref)                                                               | 1.16x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 73.6 ms: 1.26x faster                                                  |
| regex_dna      | 173 ms                                                              | 150 ms: 1.15x faster                                                   |
| regex_v8       | 17.2 ms                                                             | 15.5 ms: 1.11x faster                                                  |
| Geometric mean | (ref)                                                               | 1.13x faster                                                           |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| xml_etree_process    | 45.8 ms                                                             | 34.0 ms: 1.35x faster                                                  |
| pickle_pure_python   | 272 us                                                              | 210 us: 1.30x faster                                                   |
| tomli_loads          | 1.66 sec                                                            | 1.31 sec: 1.27x faster                                                 |
| unpickle_pure_python | 190 us                                                              | 163 us: 1.17x faster                                                   |
| xml_etree_generate   | 52.4 ms                                                             | 46.7 ms: 1.12x faster                                                  |
| xml_etree_parse      | 108 ms                                                              | 96.9 ms: 1.11x faster                                                  |
| xml_etree_iterparse  | 71.9 ms                                                             | 67.1 ms: 1.07x faster                                                  |
| unpickle             | 8.88 us                                                             | 8.37 us: 1.06x faster                                                  |
| json_loads           | 16.3 us                                                             | 15.5 us: 1.05x faster                                                  |
| json_dumps           | 7.95 ms                                                             | 7.56 ms: 1.05x faster                                                  |
| unpickle_list        | 2.86 us                                                             | 2.77 us: 1.03x faster                                                  |
| pickle_list          | 2.70 us                                                             | 2.66 us: 1.01x faster                                                  |
| pickle_dict          | 16.9 us                                                             | 17.0 us: 1.01x slower                                                  |
| pickle               | 7.01 us                                                             | 7.17 us: 1.02x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.11x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 12.0 ms: 1.02x slower                                                  |
| python_startup_no_site | 8.83 ms                                                             | 9.94 ms: 1.13x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.07x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| django_template | 25.5 ms                                                             | 19.8 ms: 1.29x faster                                                  |
| genshi_xml      | 33.6 ms                                                             | 28.1 ms: 1.19x faster                                                  |
| mako            | 9.78 ms                                                             | 8.22 ms: 1.19x faster                                                  |
| genshi_text     | 17.0 ms                                                             | 14.5 ms: 1.17x faster                                                  |
| Geometric mean  | (ref)                                                               | 1.21x faster                                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|--------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.68 ms: 1.84x faster                                                  |
| scimark_sor              | 134 ms                                                              | 74.8 ms: 1.79x faster                                                  |
| logging_silent           | 114 ns                                                              | 64.4 ns: 1.77x faster                                                  |
| mypy2                    | 294 ms                                                              | 187 ms: 1.58x faster                                                   |
| richards_super           | 57.4 ms                                                             | 36.8 ms: 1.56x faster                                                  |
| richards                 | 47.7 ms                                                             | 30.8 ms: 1.55x faster                                                  |
| scimark_lu               | 102 ms                                                              | 67.9 ms: 1.50x faster                                                  |
| crypto_pyaes             | 70.7 ms                                                             | 48.1 ms: 1.47x faster                                                  |
| spectral_norm            | 101 ms                                                              | 69.2 ms: 1.46x faster                                                  |
| go                       | 148 ms                                                              | 102 ms: 1.45x faster                                                   |
| chameleon                | 6.00 ms                                                             | 4.17 ms: 1.44x faster                                                  |
| pyflate                  | 420 ms                                                              | 294 ms: 1.43x faster                                                   |
| raytrace                 | 293 ms                                                              | 206 ms: 1.42x faster                                                   |
| async_tree_io            | 972 ms                                                              | 690 ms: 1.41x faster                                                   |
| sqlglot_parse            | 1.20 ms                                                             | 874 us: 1.38x faster                                                   |
| async_tree_none          | 381 ms                                                              | 277 ms: 1.37x faster                                                   |
| sqlglot_transpile        | 1.40 ms                                                             | 1.03 ms: 1.36x faster                                                  |
| thrift                   | 565 us                                                              | 419 us: 1.35x faster                                                   |
| xml_etree_process        | 45.8 ms                                                             | 34.0 ms: 1.35x faster                                                  |
| async_tree_memoization   | 466 ms                                                              | 347 ms: 1.34x faster                                                   |
| scimark_monte_carlo      | 63.2 ms                                                             | 47.2 ms: 1.34x faster                                                  |
| hexiom                   | 6.05 ms                                                             | 4.54 ms: 1.33x faster                                                  |
| chaos                    | 64.0 ms                                                             | 48.2 ms: 1.33x faster                                                  |
| pprint_safe_repr         | 625 ms                                                              | 477 ms: 1.31x faster                                                   |
| pprint_pformat           | 1.28 sec                                                            | 977 ms: 1.31x faster                                                   |
| pycparser                | 863 ms                                                              | 663 ms: 1.30x faster                                                   |
| pickle_pure_python       | 272 us                                                              | 210 us: 1.30x faster                                                   |
| nbody                    | 88.4 ms                                                             | 68.4 ms: 1.29x faster                                                  |
| django_template          | 25.5 ms                                                             | 19.8 ms: 1.29x faster                                                  |
| tomli_loads              | 1.66 sec                                                            | 1.31 sec: 1.27x faster                                                 |
| tornado_http             | 89.1 ms                                                             | 70.3 ms: 1.27x faster                                                  |
| regex_compile            | 92.8 ms                                                             | 73.6 ms: 1.26x faster                                                  |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 515 ms: 1.24x faster                                                   |
| html5lib                 | 41.2 ms                                                             | 33.3 ms: 1.24x faster                                                  |
| logging_format           | 4.59 us                                                             | 3.72 us: 1.23x faster                                                  |
| logging_simple           | 4.25 us                                                             | 3.45 us: 1.23x faster                                                  |
| 2to3                     | 189 ms                                                              | 153 ms: 1.23x faster                                                   |
| sqlglot_optimize         | 36.3 ms                                                             | 29.5 ms: 1.23x faster                                                  |
| gunicorn                 | 1.34 ms                                                             | 1.10 ms: 1.22x faster                                                  |
| create_gc_cycles         | 870 us                                                              | 712 us: 1.22x faster                                                   |
| sqlalchemy_imperative    | 8.79 ms                                                             | 7.19 ms: 1.22x faster                                                  |
| async_generators         | 230 ms                                                              | 191 ms: 1.21x faster                                                   |
| unpack_sequence          | 38.7 ns                                                             | 32.3 ns: 1.20x faster                                                  |
| coroutines               | 19.7 ms                                                             | 16.4 ms: 1.20x faster                                                  |
| float                    | 66.8 ms                                                             | 55.7 ms: 1.20x faster                                                  |
| sqlalchemy_declarative   | 72.4 ms                                                             | 60.5 ms: 1.20x faster                                                  |
| genshi_xml               | 33.6 ms                                                             | 28.1 ms: 1.19x faster                                                  |
| docutils                 | 1.71 sec                                                            | 1.43 sec: 1.19x faster                                                 |
| fannkuch                 | 295 ms                                                              | 247 ms: 1.19x faster                                                   |
| mako                     | 9.78 ms                                                             | 8.22 ms: 1.19x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 29.5 ms: 1.18x faster                                                  |
| genshi_text              | 17.0 ms                                                             | 14.5 ms: 1.17x faster                                                  |
| unpickle_pure_python     | 190 us                                                              | 163 us: 1.17x faster                                                   |
| bench_thread_pool        | 534 us                                                              | 457 us: 1.17x faster                                                   |
| sqlglot_normalize        | 187 ms                                                              | 160 ms: 1.17x faster                                                   |
| scimark_fft              | 216 ms                                                              | 186 ms: 1.17x faster                                                   |
| deepcopy_memo            | 33.2 us                                                             | 28.7 us: 1.16x faster                                                  |
| deepcopy_reduce          | 2.27 us                                                             | 1.97 us: 1.16x faster                                                  |
| sympy_integrate          | 12.9 ms                                                             | 11.2 ms: 1.15x faster                                                  |
| deepcopy                 | 269 us                                                              | 233 us: 1.15x faster                                                   |
| regex_dna                | 173 ms                                                              | 150 ms: 1.15x faster                                                   |
| comprehensions           | 16.8 us                                                             | 14.6 us: 1.15x faster                                                  |
| nqueens                  | 62.5 ms                                                             | 54.3 ms: 1.15x faster                                                  |
| sympy_str                | 165 ms                                                              | 144 ms: 1.15x faster                                                   |
| sympy_expand             | 268 ms                                                              | 235 ms: 1.14x faster                                                   |
| aiohttp                  | 1.27 ms                                                             | 1.12 ms: 1.14x faster                                                  |
| dask                     | 251 ms                                                              | 220 ms: 1.14x faster                                                   |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.44 sec: 1.12x faster                                                 |
| sympy_sum                | 91.1 ms                                                             | 81.0 ms: 1.12x faster                                                  |
| xml_etree_generate       | 52.4 ms                                                             | 46.7 ms: 1.12x faster                                                  |
| xml_etree_parse          | 108 ms                                                              | 96.9 ms: 1.11x faster                                                  |
| pylint                   | 279 ms                                                              | 251 ms: 1.11x faster                                                   |
| regex_v8                 | 17.2 ms                                                             | 15.5 ms: 1.11x faster                                                  |
| generators               | 32.1 ms                                                             | 29.0 ms: 1.10x faster                                                  |
| json                     | 3.04 ms                                                             | 2.75 ms: 1.10x faster                                                  |
| flaskblogging            | 2.66 ms                                                             | 2.45 ms: 1.09x faster                                                  |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 3.00 ms: 1.08x faster                                                  |
| mdp                      | 1.87 sec                                                            | 1.74 sec: 1.08x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.18 ms: 1.07x faster                                                  |
| xml_etree_iterparse      | 71.9 ms                                                             | 67.1 ms: 1.07x faster                                                  |
| sqlite_synth             | 1.45 us                                                             | 1.36 us: 1.06x faster                                                  |
| unpickle                 | 8.88 us                                                             | 8.37 us: 1.06x faster                                                  |
| json_loads               | 16.3 us                                                             | 15.5 us: 1.05x faster                                                  |
| json_dumps               | 7.95 ms                                                             | 7.56 ms: 1.05x faster                                                  |
| typing_runtime_protocols | 335 us                                                              | 322 us: 1.04x faster                                                   |
| meteor_contest           | 77.6 ms                                                             | 75.0 ms: 1.04x faster                                                  |
| asyncio_tcp              | 682 ms                                                              | 661 ms: 1.03x faster                                                   |
| unpickle_list            | 2.86 us                                                             | 2.77 us: 1.03x faster                                                  |
| pathlib                  | 24.0 ms                                                             | 23.4 ms: 1.03x faster                                                  |
| pickle_list              | 2.70 us                                                             | 2.66 us: 1.01x faster                                                  |
| pidigits                 | 281 ms                                                              | 280 ms: 1.01x faster                                                   |
| asyncio_websockets       | 408 ms                                                              | 407 ms: 1.00x faster                                                   |
| pickle_dict              | 16.9 us                                                             | 17.0 us: 1.01x slower                                                  |
| coverage                 | 41.0 ms                                                             | 41.3 ms: 1.01x slower                                                  |
| python_startup           | 11.8 ms                                                             | 12.0 ms: 1.02x slower                                                  |
| pickle                   | 7.01 us                                                             | 7.17 us: 1.02x slower                                                  |
| bench_mp_pool            | 40.0 ms                                                             | 41.8 ms: 1.04x slower                                                  |
| python_startup_no_site   | 8.83 ms                                                             | 9.94 ms: 1.13x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.20x faster                                                           |

Benchmark hidden because not significant (2): regex_effbot, gc_traversal
Ignored benchmarks (4) of results/bm-20220911-3.11.0rc2-ed7c3ff/bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.16x
