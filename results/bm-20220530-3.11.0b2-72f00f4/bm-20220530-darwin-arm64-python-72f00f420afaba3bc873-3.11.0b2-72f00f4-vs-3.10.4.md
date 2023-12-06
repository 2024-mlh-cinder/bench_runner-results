
# Results vs. 3.10.4

- fork: python
- ref: 72f00f420afaba3bc873
- machine: darwin-arm64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 153 ms: 1.23x faster                                                  |
| chameleon      | 6.00 ms                                                             | 4.32 ms: 1.39x faster                                                 |
| docutils       | 1.71 sec                                                            | 1.42 sec: 1.20x faster                                                |
| html5lib       | 41.2 ms                                                             | 32.7 ms: 1.26x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 68.8 ms: 1.30x faster                                                 |
| Geometric mean | (ref)                                                               | 1.27x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|-------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_io           | 972 ms                                                              | 688 ms: 1.41x faster                                                  |
| async_tree_none         | 381 ms                                                              | 278 ms: 1.37x faster                                                  |
| async_tree_memoization  | 466 ms                                                              | 363 ms: 1.28x faster                                                  |
| async_tree_cpu_io_mixed | 640 ms                                                              | 514 ms: 1.25x faster                                                  |
| Geometric mean          | (ref)                                                               | 1.33x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 65.5 ms: 1.35x faster                                                 |
| float          | 66.8 ms                                                             | 54.4 ms: 1.23x faster                                                 |
| pidigits       | 281 ms                                                              | 280 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                               | 1.19x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 73.8 ms: 1.26x faster                                                 |
| regex_dna      | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| regex_v8       | 17.2 ms                                                             | 15.2 ms: 1.13x faster                                                 |
| regex_effbot   | 2.46 ms                                                             | 2.22 ms: 1.11x faster                                                 |
| Geometric mean | (ref)                                                               | 1.17x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 194 us: 1.40x faster                                                  |
| xml_etree_process    | 45.8 ms                                                             | 33.9 ms: 1.35x faster                                                 |
| tomli_loads          | 1.66 sec                                                            | 1.30 sec: 1.27x faster                                                |
| unpickle_pure_python | 190 us                                                              | 151 us: 1.26x faster                                                  |
| xml_etree_generate   | 52.4 ms                                                             | 46.7 ms: 1.12x faster                                                 |
| xml_etree_parse      | 108 ms                                                              | 97.2 ms: 1.11x faster                                                 |
| unpickle             | 8.88 us                                                             | 8.23 us: 1.08x faster                                                 |
| xml_etree_iterparse  | 71.9 ms                                                             | 66.9 ms: 1.07x faster                                                 |
| json_loads           | 16.3 us                                                             | 15.4 us: 1.06x faster                                                 |
| pickle_dict          | 16.9 us                                                             | 16.1 us: 1.05x faster                                                 |
| json_dumps           | 7.95 ms                                                             | 7.58 ms: 1.05x faster                                                 |
| pickle_list          | 2.70 us                                                             | 2.59 us: 1.04x faster                                                 |
| unpickle_list        | 2.86 us                                                             | 2.80 us: 1.02x faster                                                 |
| pickle               | 7.01 us                                                             | 7.03 us: 1.00x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.13x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 11.4 ms: 1.03x faster                                                 |
| python_startup_no_site | 8.83 ms                                                             | 9.31 ms: 1.05x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.01x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 25.5 ms                                                             | 19.8 ms: 1.28x faster                                                 |
| mako            | 9.78 ms                                                             | 8.11 ms: 1.20x faster                                                 |
| genshi_text     | 17.0 ms                                                             | 14.6 ms: 1.16x faster                                                 |
| genshi_xml      | 33.6 ms                                                             | 28.8 ms: 1.16x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.20x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|--------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.72 ms: 1.81x faster                                                 |
| scimark_sor              | 134 ms                                                              | 76.1 ms: 1.76x faster                                                 |
| logging_silent           | 114 ns                                                              | 66.3 ns: 1.72x faster                                                 |
| mypy2                    | 294 ms                                                              | 186 ms: 1.58x faster                                                  |
| richards                 | 47.7 ms                                                             | 31.3 ms: 1.52x faster                                                 |
| richards_super           | 57.4 ms                                                             | 37.8 ms: 1.52x faster                                                 |
| scimark_lu               | 102 ms                                                              | 68.2 ms: 1.49x faster                                                 |
| crypto_pyaes             | 70.7 ms                                                             | 47.4 ms: 1.49x faster                                                 |
| spectral_norm            | 101 ms                                                              | 68.4 ms: 1.48x faster                                                 |
| pyflate                  | 420 ms                                                              | 285 ms: 1.47x faster                                                  |
| raytrace                 | 293 ms                                                              | 200 ms: 1.47x faster                                                  |
| go                       | 148 ms                                                              | 103 ms: 1.43x faster                                                  |
| scimark_monte_carlo      | 63.2 ms                                                             | 44.3 ms: 1.43x faster                                                 |
| async_tree_io            | 972 ms                                                              | 688 ms: 1.41x faster                                                  |
| pickle_pure_python       | 272 us                                                              | 194 us: 1.40x faster                                                  |
| chameleon                | 6.00 ms                                                             | 4.32 ms: 1.39x faster                                                 |
| async_tree_none          | 381 ms                                                              | 278 ms: 1.37x faster                                                  |
| thrift                   | 565 us                                                              | 415 us: 1.36x faster                                                  |
| nbody                    | 88.4 ms                                                             | 65.5 ms: 1.35x faster                                                 |
| xml_etree_process        | 45.8 ms                                                             | 33.9 ms: 1.35x faster                                                 |
| chaos                    | 64.0 ms                                                             | 47.8 ms: 1.34x faster                                                 |
| hexiom                   | 6.05 ms                                                             | 4.58 ms: 1.32x faster                                                 |
| pycparser                | 863 ms                                                              | 660 ms: 1.31x faster                                                  |
| tornado_http             | 89.1 ms                                                             | 68.8 ms: 1.30x faster                                                 |
| pprint_pformat           | 1.28 sec                                                            | 988 ms: 1.29x faster                                                  |
| pprint_safe_repr         | 625 ms                                                              | 485 ms: 1.29x faster                                                  |
| async_tree_memoization   | 466 ms                                                              | 363 ms: 1.28x faster                                                  |
| django_template          | 25.5 ms                                                             | 19.8 ms: 1.28x faster                                                 |
| tomli_loads              | 1.66 sec                                                            | 1.30 sec: 1.27x faster                                                |
| logging_format           | 4.59 us                                                             | 3.63 us: 1.26x faster                                                 |
| unpickle_pure_python     | 190 us                                                              | 151 us: 1.26x faster                                                  |
| logging_simple           | 4.25 us                                                             | 3.37 us: 1.26x faster                                                 |
| sqlalchemy_imperative    | 8.79 ms                                                             | 6.97 ms: 1.26x faster                                                 |
| html5lib                 | 41.2 ms                                                             | 32.7 ms: 1.26x faster                                                 |
| regex_compile            | 92.8 ms                                                             | 73.8 ms: 1.26x faster                                                 |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 514 ms: 1.25x faster                                                  |
| 2to3                     | 189 ms                                                              | 153 ms: 1.23x faster                                                  |
| float                    | 66.8 ms                                                             | 54.4 ms: 1.23x faster                                                 |
| create_gc_cycles         | 870 us                                                              | 711 us: 1.22x faster                                                  |
| sqlalchemy_declarative   | 72.4 ms                                                             | 59.5 ms: 1.22x faster                                                 |
| dulwich_log              | 34.9 ms                                                             | 28.7 ms: 1.22x faster                                                 |
| async_generators         | 230 ms                                                              | 191 ms: 1.21x faster                                                  |
| mako                     | 9.78 ms                                                             | 8.11 ms: 1.20x faster                                                 |
| fannkuch                 | 295 ms                                                              | 244 ms: 1.20x faster                                                  |
| docutils                 | 1.71 sec                                                            | 1.42 sec: 1.20x faster                                                |
| deepcopy_memo            | 33.2 us                                                             | 27.8 us: 1.20x faster                                                 |
| sqlglot_optimize         | 36.3 ms                                                             | 30.4 ms: 1.19x faster                                                 |
| unpack_sequence          | 38.7 ns                                                             | 32.7 ns: 1.19x faster                                                 |
| deepcopy                 | 269 us                                                              | 228 us: 1.18x faster                                                  |
| scimark_fft              | 216 ms                                                              | 183 ms: 1.18x faster                                                  |
| deepcopy_reduce          | 2.27 us                                                             | 1.93 us: 1.18x faster                                                 |
| regex_dna                | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| sympy_sum                | 91.1 ms                                                             | 78.2 ms: 1.16x faster                                                 |
| genshi_text              | 17.0 ms                                                             | 14.6 ms: 1.16x faster                                                 |
| genshi_xml               | 33.6 ms                                                             | 28.8 ms: 1.16x faster                                                 |
| aiohttp                  | 1.27 ms                                                             | 1.10 ms: 1.16x faster                                                 |
| coroutines               | 19.7 ms                                                             | 17.0 ms: 1.16x faster                                                 |
| sympy_integrate          | 12.9 ms                                                             | 11.1 ms: 1.16x faster                                                 |
| sympy_str                | 165 ms                                                              | 143 ms: 1.15x faster                                                  |
| sympy_expand             | 268 ms                                                              | 233 ms: 1.15x faster                                                  |
| dask                     | 251 ms                                                              | 219 ms: 1.15x faster                                                  |
| sqlglot_normalize        | 187 ms                                                              | 163 ms: 1.15x faster                                                  |
| bench_thread_pool        | 534 us                                                              | 466 us: 1.15x faster                                                  |
| nqueens                  | 62.5 ms                                                             | 54.7 ms: 1.14x faster                                                 |
| gunicorn                 | 1.34 ms                                                             | 1.18 ms: 1.13x faster                                                 |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.43 sec: 1.13x faster                                                |
| regex_v8                 | 17.2 ms                                                             | 15.2 ms: 1.13x faster                                                 |
| xml_etree_generate       | 52.4 ms                                                             | 46.7 ms: 1.12x faster                                                 |
| pylint                   | 279 ms                                                              | 251 ms: 1.11x faster                                                  |
| xml_etree_parse          | 108 ms                                                              | 97.2 ms: 1.11x faster                                                 |
| regex_effbot             | 2.46 ms                                                             | 2.22 ms: 1.11x faster                                                 |
| sqlite_synth             | 1.45 us                                                             | 1.31 us: 1.10x faster                                                 |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 2.95 ms: 1.10x faster                                                 |
| json                     | 3.04 ms                                                             | 2.79 ms: 1.09x faster                                                 |
| sqlglot_transpile        | 1.40 ms                                                             | 1.30 ms: 1.08x faster                                                 |
| unpickle                 | 8.88 us                                                             | 8.23 us: 1.08x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.74 sec: 1.08x faster                                                |
| xml_etree_iterparse      | 71.9 ms                                                             | 66.9 ms: 1.07x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.17 ms: 1.07x faster                                                 |
| meteor_contest           | 77.6 ms                                                             | 72.5 ms: 1.07x faster                                                 |
| generators               | 32.1 ms                                                             | 30.0 ms: 1.07x faster                                                 |
| json_loads               | 16.3 us                                                             | 15.4 us: 1.06x faster                                                 |
| sqlglot_parse            | 1.20 ms                                                             | 1.14 ms: 1.06x faster                                                 |
| pickle_dict              | 16.9 us                                                             | 16.1 us: 1.05x faster                                                 |
| json_dumps               | 7.95 ms                                                             | 7.58 ms: 1.05x faster                                                 |
| pickle_list              | 2.70 us                                                             | 2.59 us: 1.04x faster                                                 |
| pathlib                  | 24.0 ms                                                             | 23.2 ms: 1.04x faster                                                 |
| python_startup           | 11.8 ms                                                             | 11.4 ms: 1.03x faster                                                 |
| typing_runtime_protocols | 335 us                                                              | 326 us: 1.03x faster                                                  |
| asyncio_tcp              | 682 ms                                                              | 665 ms: 1.03x faster                                                  |
| unpickle_list            | 2.86 us                                                             | 2.80 us: 1.02x faster                                                 |
| pidigits                 | 281 ms                                                              | 280 ms: 1.00x faster                                                  |
| asyncio_websockets       | 408 ms                                                              | 407 ms: 1.00x faster                                                  |
| pickle                   | 7.01 us                                                             | 7.03 us: 1.00x slower                                                 |
| comprehensions           | 16.8 us                                                             | 17.2 us: 1.02x slower                                                 |
| bench_mp_pool            | 40.0 ms                                                             | 41.6 ms: 1.04x slower                                                 |
| python_startup_no_site   | 8.83 ms                                                             | 9.31 ms: 1.05x slower                                                 |
| coverage                 | 41.0 ms                                                             | 72.4 ms: 1.77x slower                                                 |
| Geometric mean           | (ref)                                                               | 1.20x faster                                                          |

Benchmark hidden because not significant (1): gc_traversal
Ignored benchmarks (1) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: flaskblogging
Ignored benchmarks (4) of results/bm-20220530-3.11.0b2-72f00f4/bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
