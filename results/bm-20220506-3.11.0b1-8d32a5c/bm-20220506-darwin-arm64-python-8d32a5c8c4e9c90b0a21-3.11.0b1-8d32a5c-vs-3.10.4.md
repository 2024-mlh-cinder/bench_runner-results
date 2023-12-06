
# Results vs. 3.10.4

- fork: python
- ref: 8d32a5c8c4e9c90b0a21
- machine: darwin-arm64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 152 ms: 1.24x faster                                                  |
| chameleon      | 6.00 ms                                                             | 4.32 ms: 1.39x faster                                                 |
| docutils       | 1.71 sec                                                            | 1.39 sec: 1.23x faster                                                |
| html5lib       | 41.2 ms                                                             | 31.0 ms: 1.33x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 69.4 ms: 1.28x faster                                                 |
| Geometric mean | (ref)                                                               | 1.29x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_io           | 972 ms                                                              | 690 ms: 1.41x faster                                                  |
| async_tree_none         | 381 ms                                                              | 277 ms: 1.37x faster                                                  |
| async_tree_memoization  | 466 ms                                                              | 353 ms: 1.32x faster                                                  |
| async_tree_cpu_io_mixed | 640 ms                                                              | 514 ms: 1.24x faster                                                  |
| Geometric mean          | (ref)                                                               | 1.34x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 65.6 ms: 1.35x faster                                                 |
| float          | 66.8 ms                                                             | 53.3 ms: 1.25x faster                                                 |
| pidigits       | 281 ms                                                              | 281 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                               | 1.19x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 73.1 ms: 1.27x faster                                                 |
| regex_dna      | 173 ms                                                              | 144 ms: 1.20x faster                                                  |
| regex_v8       | 17.2 ms                                                             | 15.8 ms: 1.09x faster                                                 |
| regex_effbot   | 2.46 ms                                                             | 2.26 ms: 1.09x faster                                                 |
| Geometric mean | (ref)                                                               | 1.16x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 196 us: 1.39x faster                                                  |
| xml_etree_process    | 45.8 ms                                                             | 34.2 ms: 1.34x faster                                                 |
| tomli_loads          | 1.66 sec                                                            | 1.31 sec: 1.27x faster                                                |
| unpickle_pure_python | 190 us                                                              | 152 us: 1.25x faster                                                  |
| xml_etree_generate   | 52.4 ms                                                             | 46.9 ms: 1.12x faster                                                 |
| xml_etree_parse      | 108 ms                                                              | 97.3 ms: 1.11x faster                                                 |
| xml_etree_iterparse  | 71.9 ms                                                             | 67.2 ms: 1.07x faster                                                 |
| unpickle             | 8.88 us                                                             | 8.32 us: 1.07x faster                                                 |
| pickle_list          | 2.70 us                                                             | 2.55 us: 1.06x faster                                                 |
| json_loads           | 16.3 us                                                             | 15.5 us: 1.05x faster                                                 |
| json_dumps           | 7.95 ms                                                             | 7.57 ms: 1.05x faster                                                 |
| pickle_dict          | 16.9 us                                                             | 16.2 us: 1.04x faster                                                 |
| unpickle_list        | 2.86 us                                                             | 2.77 us: 1.03x faster                                                 |
| pickle               | 7.01 us                                                             | 6.98 us: 1.00x faster                                                 |
| Geometric mean       | (ref)                                                               | 1.13x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 11.4 ms: 1.03x faster                                                 |
| python_startup_no_site | 8.83 ms                                                             | 9.27 ms: 1.05x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.01x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 25.5 ms                                                             | 19.6 ms: 1.30x faster                                                 |
| mako            | 9.78 ms                                                             | 8.18 ms: 1.19x faster                                                 |
| genshi_text     | 17.0 ms                                                             | 14.5 ms: 1.18x faster                                                 |
| genshi_xml      | 33.6 ms                                                             | 28.7 ms: 1.17x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.21x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|--------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.71 ms: 1.82x faster                                                 |
| logging_silent           | 114 ns                                                              | 65.8 ns: 1.74x faster                                                 |
| scimark_sor              | 134 ms                                                              | 78.2 ms: 1.72x faster                                                 |
| mypy2                    | 294 ms                                                              | 187 ms: 1.58x faster                                                  |
| richards                 | 47.7 ms                                                             | 31.1 ms: 1.53x faster                                                 |
| richards_super           | 57.4 ms                                                             | 37.4 ms: 1.53x faster                                                 |
| scimark_lu               | 102 ms                                                              | 68.4 ms: 1.49x faster                                                 |
| spectral_norm            | 101 ms                                                              | 68.2 ms: 1.48x faster                                                 |
| crypto_pyaes             | 70.7 ms                                                             | 47.8 ms: 1.48x faster                                                 |
| pyflate                  | 420 ms                                                              | 286 ms: 1.47x faster                                                  |
| raytrace                 | 293 ms                                                              | 203 ms: 1.44x faster                                                  |
| scimark_monte_carlo      | 63.2 ms                                                             | 44.1 ms: 1.43x faster                                                 |
| go                       | 148 ms                                                              | 104 ms: 1.42x faster                                                  |
| async_tree_io            | 972 ms                                                              | 690 ms: 1.41x faster                                                  |
| chameleon                | 6.00 ms                                                             | 4.32 ms: 1.39x faster                                                 |
| pickle_pure_python       | 272 us                                                              | 196 us: 1.39x faster                                                  |
| thrift                   | 565 us                                                              | 411 us: 1.38x faster                                                  |
| async_tree_none          | 381 ms                                                              | 277 ms: 1.37x faster                                                  |
| nbody                    | 88.4 ms                                                             | 65.6 ms: 1.35x faster                                                 |
| xml_etree_process        | 45.8 ms                                                             | 34.2 ms: 1.34x faster                                                 |
| chaos                    | 64.0 ms                                                             | 48.2 ms: 1.33x faster                                                 |
| html5lib                 | 41.2 ms                                                             | 31.0 ms: 1.33x faster                                                 |
| async_tree_memoization   | 466 ms                                                              | 353 ms: 1.32x faster                                                  |
| hexiom                   | 6.05 ms                                                             | 4.59 ms: 1.32x faster                                                 |
| pycparser                | 863 ms                                                              | 659 ms: 1.31x faster                                                  |
| django_template          | 25.5 ms                                                             | 19.6 ms: 1.30x faster                                                 |
| pprint_pformat           | 1.28 sec                                                            | 985 ms: 1.30x faster                                                  |
| pprint_safe_repr         | 625 ms                                                              | 482 ms: 1.30x faster                                                  |
| tornado_http             | 89.1 ms                                                             | 69.4 ms: 1.28x faster                                                 |
| regex_compile            | 92.8 ms                                                             | 73.1 ms: 1.27x faster                                                 |
| tomli_loads              | 1.66 sec                                                            | 1.31 sec: 1.27x faster                                                |
| float                    | 66.8 ms                                                             | 53.3 ms: 1.25x faster                                                 |
| unpickle_pure_python     | 190 us                                                              | 152 us: 1.25x faster                                                  |
| logging_format           | 4.59 us                                                             | 3.68 us: 1.25x faster                                                 |
| logging_simple           | 4.25 us                                                             | 3.41 us: 1.25x faster                                                 |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 514 ms: 1.24x faster                                                  |
| 2to3                     | 189 ms                                                              | 152 ms: 1.24x faster                                                  |
| sqlalchemy_imperative    | 8.79 ms                                                             | 7.14 ms: 1.23x faster                                                 |
| docutils                 | 1.71 sec                                                            | 1.39 sec: 1.23x faster                                                |
| create_gc_cycles         | 870 us                                                              | 715 us: 1.22x faster                                                  |
| sqlalchemy_declarative   | 72.4 ms                                                             | 59.7 ms: 1.21x faster                                                 |
| async_generators         | 230 ms                                                              | 190 ms: 1.21x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 28.9 ms: 1.21x faster                                                 |
| regex_dna                | 173 ms                                                              | 144 ms: 1.20x faster                                                  |
| deepcopy_memo            | 33.2 us                                                             | 27.8 us: 1.20x faster                                                 |
| mako                     | 9.78 ms                                                             | 8.18 ms: 1.19x faster                                                 |
| fannkuch                 | 295 ms                                                              | 247 ms: 1.19x faster                                                  |
| sqlglot_optimize         | 36.3 ms                                                             | 30.5 ms: 1.19x faster                                                 |
| scimark_fft              | 216 ms                                                              | 182 ms: 1.19x faster                                                  |
| deepcopy                 | 269 us                                                              | 228 us: 1.18x faster                                                  |
| unpack_sequence          | 38.7 ns                                                             | 32.9 ns: 1.18x faster                                                 |
| deepcopy_reduce          | 2.27 us                                                             | 1.93 us: 1.18x faster                                                 |
| genshi_text              | 17.0 ms                                                             | 14.5 ms: 1.18x faster                                                 |
| genshi_xml               | 33.6 ms                                                             | 28.7 ms: 1.17x faster                                                 |
| sympy_sum                | 91.1 ms                                                             | 78.1 ms: 1.17x faster                                                 |
| coroutines               | 19.7 ms                                                             | 16.9 ms: 1.17x faster                                                 |
| sympy_integrate          | 12.9 ms                                                             | 11.1 ms: 1.16x faster                                                 |
| sympy_expand             | 268 ms                                                              | 232 ms: 1.15x faster                                                  |
| sympy_str                | 165 ms                                                              | 143 ms: 1.15x faster                                                  |
| aiohttp                  | 1.27 ms                                                             | 1.11 ms: 1.15x faster                                                 |
| nqueens                  | 62.5 ms                                                             | 54.5 ms: 1.15x faster                                                 |
| dask                     | 251 ms                                                              | 220 ms: 1.14x faster                                                  |
| gunicorn                 | 1.34 ms                                                             | 1.18 ms: 1.14x faster                                                 |
| sqlglot_normalize        | 187 ms                                                              | 164 ms: 1.14x faster                                                  |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.43 sec: 1.13x faster                                                |
| flaskblogging            | 2.66 ms                                                             | 2.38 ms: 1.12x faster                                                 |
| xml_etree_generate       | 52.4 ms                                                             | 46.9 ms: 1.12x faster                                                 |
| bench_thread_pool        | 534 us                                                              | 480 us: 1.11x faster                                                  |
| xml_etree_parse          | 108 ms                                                              | 97.3 ms: 1.11x faster                                                 |
| pylint                   | 279 ms                                                              | 253 ms: 1.10x faster                                                  |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 2.95 ms: 1.10x faster                                                 |
| json                     | 3.04 ms                                                             | 2.77 ms: 1.10x faster                                                 |
| regex_v8                 | 17.2 ms                                                             | 15.8 ms: 1.09x faster                                                 |
| sqlglot_transpile        | 1.40 ms                                                             | 1.29 ms: 1.09x faster                                                 |
| regex_effbot             | 2.46 ms                                                             | 2.26 ms: 1.09x faster                                                 |
| sqlite_synth             | 1.45 us                                                             | 1.33 us: 1.09x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.73 sec: 1.08x faster                                                |
| generators               | 32.1 ms                                                             | 29.9 ms: 1.07x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.18 ms: 1.07x faster                                                 |
| meteor_contest           | 77.6 ms                                                             | 72.5 ms: 1.07x faster                                                 |
| sqlglot_parse            | 1.20 ms                                                             | 1.12 ms: 1.07x faster                                                 |
| xml_etree_iterparse      | 71.9 ms                                                             | 67.2 ms: 1.07x faster                                                 |
| unpickle                 | 8.88 us                                                             | 8.32 us: 1.07x faster                                                 |
| pickle_list              | 2.70 us                                                             | 2.55 us: 1.06x faster                                                 |
| json_loads               | 16.3 us                                                             | 15.5 us: 1.05x faster                                                 |
| json_dumps               | 7.95 ms                                                             | 7.57 ms: 1.05x faster                                                 |
| pickle_dict              | 16.9 us                                                             | 16.2 us: 1.04x faster                                                 |
| pathlib                  | 24.0 ms                                                             | 23.1 ms: 1.04x faster                                                 |
| python_startup           | 11.8 ms                                                             | 11.4 ms: 1.03x faster                                                 |
| asyncio_tcp              | 682 ms                                                              | 660 ms: 1.03x faster                                                  |
| unpickle_list            | 2.86 us                                                             | 2.77 us: 1.03x faster                                                 |
| typing_runtime_protocols | 335 us                                                              | 327 us: 1.03x faster                                                  |
| pickle                   | 7.01 us                                                             | 6.98 us: 1.00x faster                                                 |
| pidigits                 | 281 ms                                                              | 281 ms: 1.00x faster                                                  |
| asyncio_websockets       | 408 ms                                                              | 407 ms: 1.00x faster                                                  |
| comprehensions           | 16.8 us                                                             | 17.1 us: 1.01x slower                                                 |
| bench_mp_pool            | 40.0 ms                                                             | 41.7 ms: 1.04x slower                                                 |
| python_startup_no_site   | 8.83 ms                                                             | 9.27 ms: 1.05x slower                                                 |
| coverage                 | 41.0 ms                                                             | 73.6 ms: 1.80x slower                                                 |
| Geometric mean           | (ref)                                                               | 1.20x faster                                                          |

Benchmark hidden because not significant (1): gc_traversal
Ignored benchmarks (4) of results/bm-20220506-3.11.0b1-8d32a5c/bm-20220506-darwin-arm64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
