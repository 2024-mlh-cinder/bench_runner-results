
# Results vs. 3.10.4

- fork: python
- ref: b861ba4a8247af8159df
- machine: darwin-arm64
- commit hash: b861ba4
- commit date: 2023-04-04
- overall geometric mean: 1.15x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 170 ms: 1.11x faster                                                  |
| chameleon      | 6.00 ms                                                             | 4.73 ms: 1.27x faster                                                 |
| docutils       | 1.71 sec                                                            | 1.51 sec: 1.13x faster                                                |
| html5lib       | 41.2 ms                                                             | 35.6 ms: 1.16x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 70.9 ms: 1.26x faster                                                 |
| Geometric mean | (ref)                                                               | 1.18x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|-------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization  | 466 ms                                                              | 325 ms: 1.43x faster                                                  |
| async_tree_none         | 381 ms                                                              | 288 ms: 1.32x faster                                                  |
| async_tree_io           | 972 ms                                                              | 740 ms: 1.31x faster                                                  |
| async_tree_cpu_io_mixed | 640 ms                                                              | 537 ms: 1.19x faster                                                  |
| Geometric mean          | (ref)                                                               | 1.31x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 64.0 ms: 1.38x faster                                                 |
| float          | 66.8 ms                                                             | 54.3 ms: 1.23x faster                                                 |
| Geometric mean | (ref)                                                               | 1.19x faster                                                          |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 78.7 ms: 1.18x faster                                                 |
| regex_dna      | 173 ms                                                              | 148 ms: 1.17x faster                                                  |
| regex_v8       | 17.2 ms                                                             | 15.2 ms: 1.13x faster                                                 |
| regex_effbot   | 2.46 ms                                                             | 2.46 ms: 1.00x faster                                                 |
| Geometric mean | (ref)                                                               | 1.12x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 206 us: 1.32x faster                                                  |
| json_dumps           | 7.95 ms                                                             | 6.01 ms: 1.32x faster                                                 |
| unpickle_pure_python | 190 us                                                              | 158 us: 1.21x faster                                                  |
| xml_etree_process    | 45.8 ms                                                             | 39.0 ms: 1.17x faster                                                 |
| tomli_loads          | 1.66 sec                                                            | 1.43 sec: 1.16x faster                                                |
| xml_etree_parse      | 108 ms                                                              | 98.6 ms: 1.10x faster                                                 |
| unpickle             | 8.88 us                                                             | 8.39 us: 1.06x faster                                                 |
| unpickle_list        | 2.86 us                                                             | 2.70 us: 1.06x faster                                                 |
| xml_etree_generate   | 52.4 ms                                                             | 49.6 ms: 1.06x faster                                                 |
| json_loads           | 16.3 us                                                             | 15.8 us: 1.03x faster                                                 |
| pickle               | 7.01 us                                                             | 7.16 us: 1.02x slower                                                 |
| xml_etree_iterparse  | 71.9 ms                                                             | 73.5 ms: 1.02x slower                                                 |
| pickle_list          | 2.70 us                                                             | 2.76 us: 1.02x slower                                                 |
| pickle_dict          | 16.9 us                                                             | 17.3 us: 1.03x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.09x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 8.83 ms                                                             | 9.57 ms: 1.08x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.04x slower                                                          |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 9.78 ms                                                             | 7.17 ms: 1.36x faster                                                 |
| django_template | 25.5 ms                                                             | 22.2 ms: 1.15x faster                                                 |
| genshi_xml      | 33.6 ms                                                             | 31.5 ms: 1.07x faster                                                 |
| genshi_text     | 17.0 ms                                                             | 16.2 ms: 1.05x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.15x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|--------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.77 ms: 1.78x faster                                                 |
| asyncio_tcp              | 682 ms                                                              | 434 ms: 1.57x faster                                                  |
| scimark_sor              | 134 ms                                                              | 90.7 ms: 1.48x faster                                                 |
| logging_silent           | 114 ns                                                              | 77.7 ns: 1.47x faster                                                 |
| async_tree_memoization   | 466 ms                                                              | 325 ms: 1.43x faster                                                  |
| nbody                    | 88.4 ms                                                             | 64.0 ms: 1.38x faster                                                 |
| mako                     | 9.78 ms                                                             | 7.17 ms: 1.36x faster                                                 |
| richards_super           | 57.4 ms                                                             | 42.3 ms: 1.35x faster                                                 |
| richards                 | 47.7 ms                                                             | 35.3 ms: 1.35x faster                                                 |
| crypto_pyaes             | 70.7 ms                                                             | 52.4 ms: 1.35x faster                                                 |
| chaos                    | 64.0 ms                                                             | 48.1 ms: 1.33x faster                                                 |
| pickle_pure_python       | 272 us                                                              | 206 us: 1.32x faster                                                  |
| json_dumps               | 7.95 ms                                                             | 6.01 ms: 1.32x faster                                                 |
| async_tree_none          | 381 ms                                                              | 288 ms: 1.32x faster                                                  |
| hexiom                   | 6.05 ms                                                             | 4.60 ms: 1.32x faster                                                 |
| async_tree_io            | 972 ms                                                              | 740 ms: 1.31x faster                                                  |
| raytrace                 | 293 ms                                                              | 223 ms: 1.31x faster                                                  |
| pycparser                | 863 ms                                                              | 676 ms: 1.28x faster                                                  |
| chameleon                | 6.00 ms                                                             | 4.73 ms: 1.27x faster                                                 |
| go                       | 148 ms                                                              | 117 ms: 1.27x faster                                                  |
| pyflate                  | 420 ms                                                              | 332 ms: 1.27x faster                                                  |
| tornado_http             | 89.1 ms                                                             | 70.9 ms: 1.26x faster                                                 |
| spectral_norm            | 101 ms                                                              | 80.5 ms: 1.26x faster                                                 |
| create_gc_cycles         | 870 us                                                              | 698 us: 1.25x faster                                                  |
| pprint_safe_repr         | 625 ms                                                              | 505 ms: 1.24x faster                                                  |
| pprint_pformat           | 1.28 sec                                                            | 1.03 sec: 1.24x faster                                                |
| scimark_monte_carlo      | 63.2 ms                                                             | 51.1 ms: 1.24x faster                                                 |
| thrift                   | 565 us                                                              | 459 us: 1.23x faster                                                  |
| sqlalchemy_imperative    | 8.79 ms                                                             | 7.13 ms: 1.23x faster                                                 |
| float                    | 66.8 ms                                                             | 54.3 ms: 1.23x faster                                                 |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.31 sec: 1.23x faster                                                |
| scimark_fft              | 216 ms                                                              | 177 ms: 1.22x faster                                                  |
| unpickle_pure_python     | 190 us                                                              | 158 us: 1.21x faster                                                  |
| scimark_lu               | 102 ms                                                              | 84.7 ms: 1.20x faster                                                 |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 2.72 ms: 1.19x faster                                                 |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 537 ms: 1.19x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 29.3 ms: 1.19x faster                                                 |
| deepcopy_memo            | 33.2 us                                                             | 27.9 us: 1.19x faster                                                 |
| regex_compile            | 92.8 ms                                                             | 78.7 ms: 1.18x faster                                                 |
| xml_etree_process        | 45.8 ms                                                             | 39.0 ms: 1.17x faster                                                 |
| regex_dna                | 173 ms                                                              | 148 ms: 1.17x faster                                                  |
| mdp                      | 1.87 sec                                                            | 1.62 sec: 1.16x faster                                                |
| sqlalchemy_declarative   | 72.4 ms                                                             | 62.6 ms: 1.16x faster                                                 |
| tomli_loads              | 1.66 sec                                                            | 1.43 sec: 1.16x faster                                                |
| html5lib                 | 41.2 ms                                                             | 35.6 ms: 1.16x faster                                                 |
| unpack_sequence          | 38.7 ns                                                             | 33.6 ns: 1.15x faster                                                 |
| django_template          | 25.5 ms                                                             | 22.2 ms: 1.15x faster                                                 |
| deepcopy                 | 269 us                                                              | 236 us: 1.14x faster                                                  |
| sqlglot_transpile        | 1.40 ms                                                             | 1.24 ms: 1.14x faster                                                 |
| fannkuch                 | 295 ms                                                              | 260 ms: 1.13x faster                                                  |
| regex_v8                 | 17.2 ms                                                             | 15.2 ms: 1.13x faster                                                 |
| docutils                 | 1.71 sec                                                            | 1.51 sec: 1.13x faster                                                |
| sqlglot_parse            | 1.20 ms                                                             | 1.07 ms: 1.13x faster                                                 |
| dask                     | 251 ms                                                              | 224 ms: 1.12x faster                                                  |
| deepcopy_reduce          | 2.27 us                                                             | 2.04 us: 1.12x faster                                                 |
| 2to3                     | 189 ms                                                              | 170 ms: 1.11x faster                                                  |
| sqlglot_optimize         | 36.3 ms                                                             | 33.0 ms: 1.10x faster                                                 |
| xml_etree_parse          | 108 ms                                                              | 98.6 ms: 1.10x faster                                                 |
| sympy_integrate          | 12.9 ms                                                             | 11.8 ms: 1.09x faster                                                 |
| logging_format           | 4.59 us                                                             | 4.21 us: 1.09x faster                                                 |
| sympy_expand             | 268 ms                                                              | 246 ms: 1.09x faster                                                  |
| sympy_str                | 165 ms                                                              | 152 ms: 1.08x faster                                                  |
| json                     | 3.04 ms                                                             | 2.80 ms: 1.08x faster                                                 |
| logging_simple           | 4.25 us                                                             | 3.93 us: 1.08x faster                                                 |
| sqlite_synth             | 1.45 us                                                             | 1.34 us: 1.08x faster                                                 |
| meteor_contest           | 77.6 ms                                                             | 72.3 ms: 1.07x faster                                                 |
| bench_thread_pool        | 534 us                                                              | 498 us: 1.07x faster                                                  |
| genshi_xml               | 33.6 ms                                                             | 31.5 ms: 1.07x faster                                                 |
| sympy_sum                | 91.1 ms                                                             | 85.9 ms: 1.06x faster                                                 |
| unpickle                 | 8.88 us                                                             | 8.39 us: 1.06x faster                                                 |
| unpickle_list            | 2.86 us                                                             | 2.70 us: 1.06x faster                                                 |
| xml_etree_generate       | 52.4 ms                                                             | 49.6 ms: 1.06x faster                                                 |
| genshi_text              | 17.0 ms                                                             | 16.2 ms: 1.05x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.27 ms: 1.04x faster                                                 |
| sqlglot_normalize        | 187 ms                                                              | 181 ms: 1.03x faster                                                  |
| json_loads               | 16.3 us                                                             | 15.8 us: 1.03x faster                                                 |
| nqueens                  | 62.5 ms                                                             | 61.1 ms: 1.02x faster                                                 |
| regex_effbot             | 2.46 ms                                                             | 2.46 ms: 1.00x faster                                                 |
| asyncio_websockets       | 408 ms                                                              | 408 ms: 1.00x slower                                                  |
| gc_traversal             | 2.38 ms                                                             | 2.40 ms: 1.01x slower                                                 |
| comprehensions           | 16.8 us                                                             | 17.0 us: 1.01x slower                                                 |
| pathlib                  | 24.0 ms                                                             | 24.4 ms: 1.02x slower                                                 |
| pickle                   | 7.01 us                                                             | 7.16 us: 1.02x slower                                                 |
| xml_etree_iterparse      | 71.9 ms                                                             | 73.5 ms: 1.02x slower                                                 |
| pickle_list              | 2.70 us                                                             | 2.76 us: 1.02x slower                                                 |
| pickle_dict              | 16.9 us                                                             | 17.3 us: 1.03x slower                                                 |
| python_startup_no_site   | 8.83 ms                                                             | 9.57 ms: 1.08x slower                                                 |
| coroutines               | 19.7 ms                                                             | 21.4 ms: 1.09x slower                                                 |
| generators               | 32.1 ms                                                             | 35.4 ms: 1.10x slower                                                 |
| async_generators         | 230 ms                                                              | 260 ms: 1.13x slower                                                  |
| bench_mp_pool            | 40.0 ms                                                             | 45.4 ms: 1.13x slower                                                 |
| typing_runtime_protocols | 335 us                                                              | 392 us: 1.17x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.15x faster                                                          |

Benchmark hidden because not significant (3): mypy2, python_startup, pidigits
Ignored benchmarks (5) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, coverage, flaskblogging, gunicorn, pylint
Ignored benchmarks (4) of results/bm-20230404-3.12.0a7-b861ba4/bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.13x
