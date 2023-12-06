
# Results vs. 3.10.4

- fork: python
- ref: 2e49bd06c5ffab7d1540
- machine: darwin-arm64
- commit hash: 2e49bd0
- commit date: 2022-04-05
- overall geometric mean: 1.17x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 156 ms: 1.21x faster                                                  |
| chameleon      | 6.00 ms                                                             | 4.32 ms: 1.39x faster                                                 |
| docutils       | 1.71 sec                                                            | 1.40 sec: 1.22x faster                                                |
| html5lib       | 41.2 ms                                                             | 32.3 ms: 1.27x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 70.6 ms: 1.26x faster                                                 |
| Geometric mean | (ref)                                                               | 1.27x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_io           | 972 ms                                                              | 693 ms: 1.40x faster                                                  |
| async_tree_none         | 381 ms                                                              | 277 ms: 1.37x faster                                                  |
| async_tree_memoization  | 466 ms                                                              | 361 ms: 1.29x faster                                                  |
| async_tree_cpu_io_mixed | 640 ms                                                              | 516 ms: 1.24x faster                                                  |
| Geometric mean          | (ref)                                                               | 1.32x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 66.8 ms                                                             | 49.9 ms: 1.34x faster                                                 |
| nbody          | 88.4 ms                                                             | 67.4 ms: 1.31x faster                                                 |
| pidigits       | 281 ms                                                              | 280 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                               | 1.21x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 73.7 ms: 1.26x faster                                                 |
| regex_effbot   | 2.46 ms                                                             | 2.07 ms: 1.19x faster                                                 |
| regex_dna      | 173 ms                                                              | 175 ms: 1.01x slower                                                  |
| regex_v8       | 17.2 ms                                                             | 19.3 ms: 1.12x slower                                                 |
| Geometric mean | (ref)                                                               | 1.07x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 190 us: 1.43x faster                                                  |
| xml_etree_process    | 45.8 ms                                                             | 34.6 ms: 1.33x faster                                                 |
| unpickle_pure_python | 190 us                                                              | 149 us: 1.28x faster                                                  |
| tomli_loads          | 1.66 sec                                                            | 1.36 sec: 1.22x faster                                                |
| xml_etree_generate   | 52.4 ms                                                             | 47.0 ms: 1.11x faster                                                 |
| xml_etree_parse      | 108 ms                                                              | 97.0 ms: 1.11x faster                                                 |
| json_loads           | 16.3 us                                                             | 14.9 us: 1.09x faster                                                 |
| unpickle             | 8.88 us                                                             | 8.31 us: 1.07x faster                                                 |
| xml_etree_iterparse  | 71.9 ms                                                             | 67.4 ms: 1.07x faster                                                 |
| json_dumps           | 7.95 ms                                                             | 7.58 ms: 1.05x faster                                                 |
| unpickle_list        | 2.86 us                                                             | 2.80 us: 1.02x faster                                                 |
| pickle_list          | 2.70 us                                                             | 2.66 us: 1.01x faster                                                 |
| pickle               | 7.01 us                                                             | 7.19 us: 1.03x slower                                                 |
| pickle_dict          | 16.9 us                                                             | 17.4 us: 1.03x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.12x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 11.4 ms: 1.04x faster                                                 |
| python_startup_no_site | 8.83 ms                                                             | 9.19 ms: 1.04x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.00x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 9.78 ms                                                             | 7.05 ms: 1.39x faster                                                 |
| django_template | 25.5 ms                                                             | 20.0 ms: 1.27x faster                                                 |
| genshi_text     | 17.0 ms                                                             | 14.0 ms: 1.22x faster                                                 |
| genshi_xml      | 33.6 ms                                                             | 29.7 ms: 1.13x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.25x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0 |
|--------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.69 ms: 1.83x faster                                                 |
| logging_silent           | 114 ns                                                              | 70.1 ns: 1.63x faster                                                 |
| scimark_sor              | 134 ms                                                              | 82.8 ms: 1.62x faster                                                 |
| mypy2                    | 294 ms                                                              | 190 ms: 1.55x faster                                                  |
| richards                 | 47.7 ms                                                             | 31.3 ms: 1.52x faster                                                 |
| richards_super           | 57.4 ms                                                             | 37.9 ms: 1.51x faster                                                 |
| scimark_lu               | 102 ms                                                              | 71.2 ms: 1.43x faster                                                 |
| pickle_pure_python       | 272 us                                                              | 190 us: 1.43x faster                                                  |
| spectral_norm            | 101 ms                                                              | 70.9 ms: 1.43x faster                                                 |
| raytrace                 | 293 ms                                                              | 207 ms: 1.42x faster                                                  |
| scimark_monte_carlo      | 63.2 ms                                                             | 44.6 ms: 1.42x faster                                                 |
| pyflate                  | 420 ms                                                              | 297 ms: 1.41x faster                                                  |
| go                       | 148 ms                                                              | 105 ms: 1.41x faster                                                  |
| async_tree_io            | 972 ms                                                              | 693 ms: 1.40x faster                                                  |
| chameleon                | 6.00 ms                                                             | 4.32 ms: 1.39x faster                                                 |
| mako                     | 9.78 ms                                                             | 7.05 ms: 1.39x faster                                                 |
| async_tree_none          | 381 ms                                                              | 277 ms: 1.37x faster                                                  |
| thrift                   | 565 us                                                              | 421 us: 1.34x faster                                                  |
| deepcopy_memo            | 33.2 us                                                             | 24.8 us: 1.34x faster                                                 |
| float                    | 66.8 ms                                                             | 49.9 ms: 1.34x faster                                                 |
| xml_etree_process        | 45.8 ms                                                             | 34.6 ms: 1.33x faster                                                 |
| crypto_pyaes             | 70.7 ms                                                             | 53.4 ms: 1.32x faster                                                 |
| chaos                    | 64.0 ms                                                             | 48.7 ms: 1.31x faster                                                 |
| nbody                    | 88.4 ms                                                             | 67.4 ms: 1.31x faster                                                 |
| async_tree_memoization   | 466 ms                                                              | 361 ms: 1.29x faster                                                  |
| logging_format           | 4.59 us                                                             | 3.58 us: 1.28x faster                                                 |
| unpickle_pure_python     | 190 us                                                              | 149 us: 1.28x faster                                                  |
| html5lib                 | 41.2 ms                                                             | 32.3 ms: 1.27x faster                                                 |
| pprint_pformat           | 1.28 sec                                                            | 1.00 sec: 1.27x faster                                                |
| django_template          | 25.5 ms                                                             | 20.0 ms: 1.27x faster                                                 |
| deepcopy                 | 269 us                                                              | 212 us: 1.27x faster                                                  |
| pprint_safe_repr         | 625 ms                                                              | 492 ms: 1.27x faster                                                  |
| logging_simple           | 4.25 us                                                             | 3.35 us: 1.27x faster                                                 |
| tornado_http             | 89.1 ms                                                             | 70.6 ms: 1.26x faster                                                 |
| pycparser                | 863 ms                                                              | 684 ms: 1.26x faster                                                  |
| regex_compile            | 92.8 ms                                                             | 73.7 ms: 1.26x faster                                                 |
| hexiom                   | 6.05 ms                                                             | 4.85 ms: 1.25x faster                                                 |
| deepcopy_reduce          | 2.27 us                                                             | 1.83 us: 1.24x faster                                                 |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 516 ms: 1.24x faster                                                  |
| create_gc_cycles         | 870 us                                                              | 706 us: 1.23x faster                                                  |
| docutils                 | 1.71 sec                                                            | 1.40 sec: 1.22x faster                                                |
| async_generators         | 230 ms                                                              | 189 ms: 1.22x faster                                                  |
| genshi_text              | 17.0 ms                                                             | 14.0 ms: 1.22x faster                                                 |
| tomli_loads              | 1.66 sec                                                            | 1.36 sec: 1.22x faster                                                |
| 2to3                     | 189 ms                                                              | 156 ms: 1.21x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 28.9 ms: 1.21x faster                                                 |
| sqlalchemy_imperative    | 8.79 ms                                                             | 7.31 ms: 1.20x faster                                                 |
| sqlalchemy_declarative   | 72.4 ms                                                             | 60.7 ms: 1.19x faster                                                 |
| regex_effbot             | 2.46 ms                                                             | 2.07 ms: 1.19x faster                                                 |
| sqlglot_optimize         | 36.3 ms                                                             | 30.7 ms: 1.18x faster                                                 |
| sympy_sum                | 91.1 ms                                                             | 78.2 ms: 1.17x faster                                                 |
| aiohttp                  | 1.27 ms                                                             | 1.09 ms: 1.16x faster                                                 |
| scimark_fft              | 216 ms                                                              | 187 ms: 1.16x faster                                                  |
| fannkuch                 | 295 ms                                                              | 254 ms: 1.16x faster                                                  |
| sympy_integrate          | 12.9 ms                                                             | 11.2 ms: 1.15x faster                                                 |
| sympy_str                | 165 ms                                                              | 144 ms: 1.15x faster                                                  |
| unpack_sequence          | 38.7 ns                                                             | 33.7 ns: 1.15x faster                                                 |
| sqlite_synth             | 1.45 us                                                             | 1.26 us: 1.14x faster                                                 |
| sympy_expand             | 268 ms                                                              | 234 ms: 1.14x faster                                                  |
| gunicorn                 | 1.34 ms                                                             | 1.18 ms: 1.14x faster                                                 |
| genshi_xml               | 33.6 ms                                                             | 29.7 ms: 1.13x faster                                                 |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.43 sec: 1.13x faster                                                |
| sqlglot_normalize        | 187 ms                                                              | 166 ms: 1.13x faster                                                  |
| nqueens                  | 62.5 ms                                                             | 55.8 ms: 1.12x faster                                                 |
| pylint                   | 279 ms                                                              | 249 ms: 1.12x faster                                                  |
| flaskblogging            | 2.66 ms                                                             | 2.39 ms: 1.11x faster                                                 |
| xml_etree_generate       | 52.4 ms                                                             | 47.0 ms: 1.11x faster                                                 |
| xml_etree_parse          | 108 ms                                                              | 97.0 ms: 1.11x faster                                                 |
| json                     | 3.04 ms                                                             | 2.75 ms: 1.11x faster                                                 |
| coroutines               | 19.7 ms                                                             | 17.9 ms: 1.10x faster                                                 |
| bench_thread_pool        | 534 us                                                              | 487 us: 1.10x faster                                                  |
| json_loads               | 16.3 us                                                             | 14.9 us: 1.09x faster                                                 |
| sqlglot_transpile        | 1.40 ms                                                             | 1.30 ms: 1.08x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.15 ms: 1.08x faster                                                 |
| unpickle                 | 8.88 us                                                             | 8.31 us: 1.07x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.76 sec: 1.07x faster                                                |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 3.04 ms: 1.07x faster                                                 |
| xml_etree_iterparse      | 71.9 ms                                                             | 67.4 ms: 1.07x faster                                                 |
| generators               | 32.1 ms                                                             | 30.1 ms: 1.07x faster                                                 |
| meteor_contest           | 77.6 ms                                                             | 73.9 ms: 1.05x faster                                                 |
| sqlglot_parse            | 1.20 ms                                                             | 1.15 ms: 1.05x faster                                                 |
| json_dumps               | 7.95 ms                                                             | 7.58 ms: 1.05x faster                                                 |
| pathlib                  | 24.0 ms                                                             | 23.1 ms: 1.04x faster                                                 |
| typing_runtime_protocols | 335 us                                                              | 323 us: 1.04x faster                                                  |
| python_startup           | 11.8 ms                                                             | 11.4 ms: 1.04x faster                                                 |
| comprehensions           | 16.8 us                                                             | 16.3 us: 1.03x faster                                                 |
| asyncio_tcp              | 682 ms                                                              | 663 ms: 1.03x faster                                                  |
| unpickle_list            | 2.86 us                                                             | 2.80 us: 1.02x faster                                                 |
| pickle_list              | 2.70 us                                                             | 2.66 us: 1.01x faster                                                 |
| pidigits                 | 281 ms                                                              | 280 ms: 1.00x faster                                                  |
| regex_dna                | 173 ms                                                              | 175 ms: 1.01x slower                                                  |
| pickle                   | 7.01 us                                                             | 7.19 us: 1.03x slower                                                 |
| pickle_dict              | 16.9 us                                                             | 17.4 us: 1.03x slower                                                 |
| bench_mp_pool            | 40.0 ms                                                             | 41.5 ms: 1.04x slower                                                 |
| python_startup_no_site   | 8.83 ms                                                             | 9.19 ms: 1.04x slower                                                 |
| regex_v8                 | 17.2 ms                                                             | 19.3 ms: 1.12x slower                                                 |
| coverage                 | 41.0 ms                                                             | 392 ms: 9.57x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.17x faster                                                          |

Benchmark hidden because not significant (2): asyncio_websockets, gc_traversal
Ignored benchmarks (1) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: dask
Ignored benchmarks (4) of results/bm-20220405-3.11.0a7-2e49bd0/bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.15x
