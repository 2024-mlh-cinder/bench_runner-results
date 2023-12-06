
# Results vs. 3.10.4

- fork: python
- ref: deaf509e8fc6e0363bd6
- machine: darwin-arm64
- commit hash: deaf509
- commit date: 2022-10-24
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 |
|----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 154 ms: 1.23x faster                                                |
| chameleon      | 6.00 ms                                                             | 4.21 ms: 1.43x faster                                               |
| docutils       | 1.71 sec                                                            | 1.43 sec: 1.19x faster                                              |
| html5lib       | 41.2 ms                                                             | 33.3 ms: 1.24x faster                                               |
| tornado_http   | 89.1 ms                                                             | 70.9 ms: 1.26x faster                                               |
| Geometric mean | (ref)                                                               | 1.27x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 |
|-------------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_io           | 972 ms                                                              | 691 ms: 1.41x faster                                                |
| async_tree_none         | 381 ms                                                              | 277 ms: 1.37x faster                                                |
| async_tree_memoization  | 466 ms                                                              | 353 ms: 1.32x faster                                                |
| async_tree_cpu_io_mixed | 640 ms                                                              | 516 ms: 1.24x faster                                                |
| Geometric mean          | (ref)                                                               | 1.33x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 |
|----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 68.5 ms: 1.29x faster                                               |
| float          | 66.8 ms                                                             | 55.1 ms: 1.21x faster                                               |
| pidigits       | 281 ms                                                              | 280 ms: 1.01x faster                                                |
| Geometric mean | (ref)                                                               | 1.16x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 |
|----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 73.5 ms: 1.26x faster                                               |
| regex_dna      | 173 ms                                                              | 149 ms: 1.16x faster                                                |
| regex_v8       | 17.2 ms                                                             | 15.4 ms: 1.12x faster                                               |
| regex_effbot   | 2.46 ms                                                             | 2.45 ms: 1.00x faster                                               |
| Geometric mean | (ref)                                                               | 1.13x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 |
|----------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| xml_etree_process    | 45.8 ms                                                             | 34.1 ms: 1.34x faster                                               |
| pickle_pure_python   | 272 us                                                              | 210 us: 1.30x faster                                                |
| tomli_loads          | 1.66 sec                                                            | 1.32 sec: 1.26x faster                                              |
| unpickle_pure_python | 190 us                                                              | 162 us: 1.17x faster                                                |
| xml_etree_generate   | 52.4 ms                                                             | 47.1 ms: 1.11x faster                                               |
| xml_etree_parse      | 108 ms                                                              | 97.6 ms: 1.11x faster                                               |
| xml_etree_iterparse  | 71.9 ms                                                             | 67.5 ms: 1.07x faster                                               |
| unpickle             | 8.88 us                                                             | 8.35 us: 1.06x faster                                               |
| json_loads           | 16.3 us                                                             | 15.5 us: 1.05x faster                                               |
| json_dumps           | 7.95 ms                                                             | 7.58 ms: 1.05x faster                                               |
| unpickle_list        | 2.86 us                                                             | 2.76 us: 1.04x faster                                               |
| pickle_list          | 2.70 us                                                             | 2.68 us: 1.01x faster                                               |
| pickle_dict          | 16.9 us                                                             | 17.0 us: 1.01x slower                                               |
| pickle               | 7.01 us                                                             | 7.17 us: 1.02x slower                                               |
| Geometric mean       | (ref)                                                               | 1.10x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 |
|------------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 11.5 ms: 1.02x faster                                               |
| python_startup_no_site | 8.83 ms                                                             | 9.37 ms: 1.06x slower                                               |
| Geometric mean         | (ref)                                                               | 1.02x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 |
|-----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| django_template | 25.5 ms                                                             | 19.6 ms: 1.30x faster                                               |
| genshi_xml      | 33.6 ms                                                             | 28.3 ms: 1.19x faster                                               |
| mako            | 9.78 ms                                                             | 8.25 ms: 1.19x faster                                               |
| genshi_text     | 17.0 ms                                                             | 14.5 ms: 1.18x faster                                               |
| Geometric mean  | (ref)                                                               | 1.21x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 |
|--------------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.69 ms: 1.83x faster                                               |
| scimark_sor              | 134 ms                                                              | 74.4 ms: 1.80x faster                                               |
| logging_silent           | 114 ns                                                              | 64.3 ns: 1.78x faster                                               |
| mypy2                    | 294 ms                                                              | 187 ms: 1.57x faster                                                |
| richards_super           | 57.4 ms                                                             | 36.7 ms: 1.56x faster                                               |
| richards                 | 47.7 ms                                                             | 30.7 ms: 1.56x faster                                               |
| scimark_lu               | 102 ms                                                              | 67.9 ms: 1.50x faster                                               |
| crypto_pyaes             | 70.7 ms                                                             | 47.9 ms: 1.48x faster                                               |
| spectral_norm            | 101 ms                                                              | 69.4 ms: 1.46x faster                                               |
| go                       | 148 ms                                                              | 102 ms: 1.45x faster                                                |
| chameleon                | 6.00 ms                                                             | 4.21 ms: 1.43x faster                                               |
| raytrace                 | 293 ms                                                              | 205 ms: 1.43x faster                                                |
| pyflate                  | 420 ms                                                              | 295 ms: 1.42x faster                                                |
| async_tree_io            | 972 ms                                                              | 691 ms: 1.41x faster                                                |
| scimark_monte_carlo      | 63.2 ms                                                             | 45.7 ms: 1.38x faster                                               |
| sqlglot_parse            | 1.20 ms                                                             | 874 us: 1.38x faster                                                |
| async_tree_none          | 381 ms                                                              | 277 ms: 1.37x faster                                                |
| sqlglot_transpile        | 1.40 ms                                                             | 1.04 ms: 1.35x faster                                               |
| thrift                   | 565 us                                                              | 420 us: 1.34x faster                                                |
| xml_etree_process        | 45.8 ms                                                             | 34.1 ms: 1.34x faster                                               |
| hexiom                   | 6.05 ms                                                             | 4.55 ms: 1.33x faster                                               |
| chaos                    | 64.0 ms                                                             | 48.2 ms: 1.33x faster                                               |
| async_tree_memoization   | 466 ms                                                              | 353 ms: 1.32x faster                                                |
| pycparser                | 863 ms                                                              | 658 ms: 1.31x faster                                                |
| pprint_safe_repr         | 625 ms                                                              | 480 ms: 1.30x faster                                                |
| django_template          | 25.5 ms                                                             | 19.6 ms: 1.30x faster                                               |
| pickle_pure_python       | 272 us                                                              | 210 us: 1.30x faster                                                |
| pprint_pformat           | 1.28 sec                                                            | 986 ms: 1.30x faster                                                |
| nbody                    | 88.4 ms                                                             | 68.5 ms: 1.29x faster                                               |
| regex_compile            | 92.8 ms                                                             | 73.5 ms: 1.26x faster                                               |
| tornado_http             | 89.1 ms                                                             | 70.9 ms: 1.26x faster                                               |
| tomli_loads              | 1.66 sec                                                            | 1.32 sec: 1.26x faster                                              |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 516 ms: 1.24x faster                                                |
| html5lib                 | 41.2 ms                                                             | 33.3 ms: 1.24x faster                                               |
| logging_format           | 4.59 us                                                             | 3.73 us: 1.23x faster                                               |
| logging_simple           | 4.25 us                                                             | 3.45 us: 1.23x faster                                               |
| 2to3                     | 189 ms                                                              | 154 ms: 1.23x faster                                                |
| sqlglot_optimize         | 36.3 ms                                                             | 29.6 ms: 1.23x faster                                               |
| create_gc_cycles         | 870 us                                                              | 714 us: 1.22x faster                                                |
| float                    | 66.8 ms                                                             | 55.1 ms: 1.21x faster                                               |
| async_generators         | 230 ms                                                              | 191 ms: 1.20x faster                                                |
| unpack_sequence          | 38.7 ns                                                             | 32.3 ns: 1.20x faster                                               |
| sqlalchemy_imperative    | 8.79 ms                                                             | 7.33 ms: 1.20x faster                                               |
| sqlalchemy_declarative   | 72.4 ms                                                             | 60.4 ms: 1.20x faster                                               |
| coroutines               | 19.7 ms                                                             | 16.4 ms: 1.20x faster                                               |
| dulwich_log              | 34.9 ms                                                             | 29.2 ms: 1.19x faster                                               |
| fannkuch                 | 295 ms                                                              | 247 ms: 1.19x faster                                                |
| docutils                 | 1.71 sec                                                            | 1.43 sec: 1.19x faster                                              |
| genshi_xml               | 33.6 ms                                                             | 28.3 ms: 1.19x faster                                               |
| mako                     | 9.78 ms                                                             | 8.25 ms: 1.19x faster                                               |
| genshi_text              | 17.0 ms                                                             | 14.5 ms: 1.18x faster                                               |
| unpickle_pure_python     | 190 us                                                              | 162 us: 1.17x faster                                                |
| sqlglot_normalize        | 187 ms                                                              | 160 ms: 1.17x faster                                                |
| deepcopy                 | 269 us                                                              | 232 us: 1.16x faster                                                |
| scimark_fft              | 216 ms                                                              | 186 ms: 1.16x faster                                                |
| deepcopy_reduce          | 2.27 us                                                             | 1.96 us: 1.16x faster                                               |
| deepcopy_memo            | 33.2 us                                                             | 28.7 us: 1.16x faster                                               |
| regex_dna                | 173 ms                                                              | 149 ms: 1.16x faster                                                |
| aiohttp                  | 1.27 ms                                                             | 1.10 ms: 1.15x faster                                               |
| gunicorn                 | 1.34 ms                                                             | 1.17 ms: 1.15x faster                                               |
| comprehensions           | 16.8 us                                                             | 14.6 us: 1.15x faster                                               |
| sympy_integrate          | 12.9 ms                                                             | 11.2 ms: 1.15x faster                                               |
| nqueens                  | 62.5 ms                                                             | 54.3 ms: 1.15x faster                                               |
| dask                     | 251 ms                                                              | 219 ms: 1.15x faster                                                |
| bench_thread_pool        | 534 us                                                              | 467 us: 1.14x faster                                                |
| sympy_str                | 165 ms                                                              | 144 ms: 1.14x faster                                                |
| sympy_expand             | 268 ms                                                              | 236 ms: 1.13x faster                                                |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.43 sec: 1.13x faster                                              |
| sympy_sum                | 91.1 ms                                                             | 80.8 ms: 1.13x faster                                               |
| flaskblogging            | 2.66 ms                                                             | 2.37 ms: 1.13x faster                                               |
| regex_v8                 | 17.2 ms                                                             | 15.4 ms: 1.12x faster                                               |
| xml_etree_generate       | 52.4 ms                                                             | 47.1 ms: 1.11x faster                                               |
| pylint                   | 279 ms                                                              | 252 ms: 1.11x faster                                                |
| xml_etree_parse          | 108 ms                                                              | 97.6 ms: 1.11x faster                                               |
| generators               | 32.1 ms                                                             | 29.0 ms: 1.10x faster                                               |
| json                     | 3.04 ms                                                             | 2.77 ms: 1.10x faster                                               |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 3.00 ms: 1.08x faster                                               |
| telco                    | 3.41 ms                                                             | 3.17 ms: 1.08x faster                                               |
| xml_etree_iterparse      | 71.9 ms                                                             | 67.5 ms: 1.07x faster                                               |
| sqlite_synth             | 1.45 us                                                             | 1.36 us: 1.06x faster                                               |
| unpickle                 | 8.88 us                                                             | 8.35 us: 1.06x faster                                               |
| json_loads               | 16.3 us                                                             | 15.5 us: 1.05x faster                                               |
| json_dumps               | 7.95 ms                                                             | 7.58 ms: 1.05x faster                                               |
| pathlib                  | 24.0 ms                                                             | 23.0 ms: 1.04x faster                                               |
| typing_runtime_protocols | 335 us                                                              | 322 us: 1.04x faster                                                |
| unpickle_list            | 2.86 us                                                             | 2.76 us: 1.04x faster                                               |
| meteor_contest           | 77.6 ms                                                             | 75.3 ms: 1.03x faster                                               |
| asyncio_tcp              | 682 ms                                                              | 664 ms: 1.03x faster                                                |
| python_startup           | 11.8 ms                                                             | 11.5 ms: 1.02x faster                                               |
| mdp                      | 1.87 sec                                                            | 1.84 sec: 1.02x faster                                              |
| pickle_list              | 2.70 us                                                             | 2.68 us: 1.01x faster                                               |
| pidigits                 | 281 ms                                                              | 280 ms: 1.01x faster                                                |
| regex_effbot             | 2.46 ms                                                             | 2.45 ms: 1.00x faster                                               |
| pickle_dict              | 16.9 us                                                             | 17.0 us: 1.01x slower                                               |
| coverage                 | 41.0 ms                                                             | 41.4 ms: 1.01x slower                                               |
| pickle                   | 7.01 us                                                             | 7.17 us: 1.02x slower                                               |
| bench_mp_pool            | 40.0 ms                                                             | 42.1 ms: 1.05x slower                                               |
| python_startup_no_site   | 8.83 ms                                                             | 9.37 ms: 1.06x slower                                               |
| gc_traversal             | 2.38 ms                                                             | 2.53 ms: 1.06x slower                                               |
| Geometric mean           | (ref)                                                               | 1.20x faster                                                        |

Benchmark hidden because not significant (1): asyncio_websockets
Ignored benchmarks (4) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.16x
