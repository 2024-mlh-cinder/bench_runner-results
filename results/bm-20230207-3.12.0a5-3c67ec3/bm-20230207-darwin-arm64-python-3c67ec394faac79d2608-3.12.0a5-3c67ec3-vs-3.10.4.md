
# Results vs. 3.10.4

- fork: python
- ref: 3c67ec394faac79d2608
- machine: darwin-arm64
- commit hash: 3c67ec3
- commit date: 2023-02-07
- overall geometric mean: 1.15x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 166 ms: 1.14x faster                                                  |
| chameleon      | 6.00 ms                                                             | 4.69 ms: 1.28x faster                                                 |
| docutils       | 1.71 sec                                                            | 1.48 sec: 1.15x faster                                                |
| html5lib       | 41.2 ms                                                             | 34.6 ms: 1.19x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 72.3 ms: 1.23x faster                                                 |
| Geometric mean | (ref)                                                               | 1.20x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization  | 466 ms                                                              | 336 ms: 1.39x faster                                                  |
| async_tree_none         | 381 ms                                                              | 290 ms: 1.31x faster                                                  |
| async_tree_io           | 972 ms                                                              | 753 ms: 1.29x faster                                                  |
| async_tree_cpu_io_mixed | 640 ms                                                              | 533 ms: 1.20x faster                                                  |
| Geometric mean          | (ref)                                                               | 1.30x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 68.5 ms: 1.29x faster                                                 |
| float          | 66.8 ms                                                             | 57.5 ms: 1.16x faster                                                 |
| pidigits       | 281 ms                                                              | 281 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                               | 1.15x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 76.0 ms: 1.22x faster                                                 |
| regex_dna      | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| regex_v8       | 17.2 ms                                                             | 15.3 ms: 1.12x faster                                                 |
| regex_effbot   | 2.46 ms                                                             | 2.45 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                               | 1.13x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.95 ms                                                             | 6.08 ms: 1.31x faster                                                 |
| pickle_pure_python   | 272 us                                                              | 214 us: 1.27x faster                                                  |
| xml_etree_process    | 45.8 ms                                                             | 37.1 ms: 1.24x faster                                                 |
| tomli_loads          | 1.66 sec                                                            | 1.38 sec: 1.20x faster                                                |
| unpickle_pure_python | 190 us                                                              | 161 us: 1.18x faster                                                  |
| xml_etree_parse      | 108 ms                                                              | 95.0 ms: 1.14x faster                                                 |
| xml_etree_generate   | 52.4 ms                                                             | 48.7 ms: 1.08x faster                                                 |
| unpickle             | 8.88 us                                                             | 8.50 us: 1.05x faster                                                 |
| json_loads           | 16.3 us                                                             | 15.7 us: 1.04x faster                                                 |
| pickle_dict          | 16.9 us                                                             | 16.8 us: 1.00x faster                                                 |
| pickle_list          | 2.70 us                                                             | 2.72 us: 1.01x slower                                                 |
| pickle               | 7.01 us                                                             | 7.09 us: 1.01x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.10x faster                                                          |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 8.83 ms                                                             | 9.55 ms: 1.08x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.04x slower                                                          |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 9.78 ms                                                             | 6.94 ms: 1.41x faster                                                 |
| django_template | 25.5 ms                                                             | 22.5 ms: 1.13x faster                                                 |
| genshi_xml      | 33.6 ms                                                             | 30.7 ms: 1.09x faster                                                 |
| genshi_text     | 17.0 ms                                                             | 16.3 ms: 1.05x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.16x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|--------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.81 ms: 1.76x faster                                                 |
| asyncio_tcp              | 682 ms                                                              | 437 ms: 1.56x faster                                                  |
| scimark_sor              | 134 ms                                                              | 90.7 ms: 1.48x faster                                                 |
| richards                 | 47.7 ms                                                             | 33.5 ms: 1.43x faster                                                 |
| richards_super           | 57.4 ms                                                             | 40.4 ms: 1.42x faster                                                 |
| mako                     | 9.78 ms                                                             | 6.94 ms: 1.41x faster                                                 |
| async_tree_memoization   | 466 ms                                                              | 336 ms: 1.39x faster                                                  |
| logging_silent           | 114 ns                                                              | 83.0 ns: 1.38x faster                                                 |
| crypto_pyaes             | 70.7 ms                                                             | 51.6 ms: 1.37x faster                                                 |
| chaos                    | 64.0 ms                                                             | 48.4 ms: 1.32x faster                                                 |
| hexiom                   | 6.05 ms                                                             | 4.61 ms: 1.31x faster                                                 |
| async_tree_none          | 381 ms                                                              | 290 ms: 1.31x faster                                                  |
| json_dumps               | 7.95 ms                                                             | 6.08 ms: 1.31x faster                                                 |
| go                       | 148 ms                                                              | 113 ms: 1.30x faster                                                  |
| pyflate                  | 420 ms                                                              | 324 ms: 1.30x faster                                                  |
| nbody                    | 88.4 ms                                                             | 68.5 ms: 1.29x faster                                                 |
| async_tree_io            | 972 ms                                                              | 753 ms: 1.29x faster                                                  |
| pycparser                | 863 ms                                                              | 670 ms: 1.29x faster                                                  |
| raytrace                 | 293 ms                                                              | 229 ms: 1.28x faster                                                  |
| chameleon                | 6.00 ms                                                             | 4.69 ms: 1.28x faster                                                 |
| thrift                   | 565 us                                                              | 443 us: 1.28x faster                                                  |
| pickle_pure_python       | 272 us                                                              | 214 us: 1.27x faster                                                  |
| create_gc_cycles         | 870 us                                                              | 687 us: 1.27x faster                                                  |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.28 sec: 1.26x faster                                                |
| spectral_norm            | 101 ms                                                              | 81.8 ms: 1.24x faster                                                 |
| xml_etree_process        | 45.8 ms                                                             | 37.1 ms: 1.24x faster                                                 |
| tornado_http             | 89.1 ms                                                             | 72.3 ms: 1.23x faster                                                 |
| scimark_lu               | 102 ms                                                              | 83.3 ms: 1.22x faster                                                 |
| regex_compile            | 92.8 ms                                                             | 76.0 ms: 1.22x faster                                                 |
| tomli_loads              | 1.66 sec                                                            | 1.38 sec: 1.20x faster                                                |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 533 ms: 1.20x faster                                                  |
| sqlalchemy_imperative    | 8.79 ms                                                             | 7.32 ms: 1.20x faster                                                 |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 2.70 ms: 1.20x faster                                                 |
| scimark_monte_carlo      | 63.2 ms                                                             | 52.9 ms: 1.20x faster                                                 |
| fannkuch                 | 295 ms                                                              | 246 ms: 1.20x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 29.2 ms: 1.19x faster                                                 |
| pprint_safe_repr         | 625 ms                                                              | 524 ms: 1.19x faster                                                  |
| pprint_pformat           | 1.28 sec                                                            | 1.07 sec: 1.19x faster                                                |
| html5lib                 | 41.2 ms                                                             | 34.6 ms: 1.19x faster                                                 |
| unpickle_pure_python     | 190 us                                                              | 161 us: 1.18x faster                                                  |
| scimark_fft              | 216 ms                                                              | 183 ms: 1.18x faster                                                  |
| regex_dna                | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| comprehensions           | 16.8 us                                                             | 14.5 us: 1.17x faster                                                 |
| float                    | 66.8 ms                                                             | 57.5 ms: 1.16x faster                                                 |
| deepcopy_memo            | 33.2 us                                                             | 28.6 us: 1.16x faster                                                 |
| unpack_sequence          | 38.7 ns                                                             | 33.4 ns: 1.16x faster                                                 |
| sqlalchemy_declarative   | 72.4 ms                                                             | 62.6 ms: 1.16x faster                                                 |
| docutils                 | 1.71 sec                                                            | 1.48 sec: 1.15x faster                                                |
| sqlglot_parse            | 1.20 ms                                                             | 1.05 ms: 1.14x faster                                                 |
| sqlglot_transpile        | 1.40 ms                                                             | 1.23 ms: 1.14x faster                                                 |
| xml_etree_parse          | 108 ms                                                              | 95.0 ms: 1.14x faster                                                 |
| 2to3                     | 189 ms                                                              | 166 ms: 1.14x faster                                                  |
| django_template          | 25.5 ms                                                             | 22.5 ms: 1.13x faster                                                 |
| regex_v8                 | 17.2 ms                                                             | 15.3 ms: 1.12x faster                                                 |
| sympy_integrate          | 12.9 ms                                                             | 11.5 ms: 1.12x faster                                                 |
| sympy_str                | 165 ms                                                              | 148 ms: 1.12x faster                                                  |
| sympy_sum                | 91.1 ms                                                             | 82.4 ms: 1.11x faster                                                 |
| async_generators         | 230 ms                                                              | 209 ms: 1.10x faster                                                  |
| deepcopy                 | 269 us                                                              | 246 us: 1.10x faster                                                  |
| sqlglot_optimize         | 36.3 ms                                                             | 33.1 ms: 1.10x faster                                                 |
| sympy_expand             | 268 ms                                                              | 245 ms: 1.09x faster                                                  |
| genshi_xml               | 33.6 ms                                                             | 30.7 ms: 1.09x faster                                                 |
| logging_simple           | 4.25 us                                                             | 3.89 us: 1.09x faster                                                 |
| logging_format           | 4.59 us                                                             | 4.21 us: 1.09x faster                                                 |
| json                     | 3.04 ms                                                             | 2.79 ms: 1.09x faster                                                 |
| bench_thread_pool        | 534 us                                                              | 495 us: 1.08x faster                                                  |
| xml_etree_generate       | 52.4 ms                                                             | 48.7 ms: 1.08x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.18 ms: 1.07x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.76 sec: 1.07x faster                                                |
| deepcopy_reduce          | 2.27 us                                                             | 2.15 us: 1.06x faster                                                 |
| typing_runtime_protocols | 335 us                                                              | 319 us: 1.05x faster                                                  |
| genshi_text              | 17.0 ms                                                             | 16.3 ms: 1.05x faster                                                 |
| unpickle                 | 8.88 us                                                             | 8.50 us: 1.05x faster                                                 |
| nqueens                  | 62.5 ms                                                             | 59.9 ms: 1.04x faster                                                 |
| json_loads               | 16.3 us                                                             | 15.7 us: 1.04x faster                                                 |
| pathlib                  | 24.0 ms                                                             | 23.2 ms: 1.04x faster                                                 |
| sqlite_synth             | 1.45 us                                                             | 1.40 us: 1.03x faster                                                 |
| sqlglot_normalize        | 187 ms                                                              | 181 ms: 1.03x faster                                                  |
| regex_effbot             | 2.46 ms                                                             | 2.45 ms: 1.01x faster                                                 |
| meteor_contest           | 77.6 ms                                                             | 77.2 ms: 1.01x faster                                                 |
| pickle_dict              | 16.9 us                                                             | 16.8 us: 1.00x faster                                                 |
| pidigits                 | 281 ms                                                              | 281 ms: 1.00x faster                                                  |
| gc_traversal             | 2.38 ms                                                             | 2.39 ms: 1.00x slower                                                 |
| asyncio_websockets       | 408 ms                                                              | 409 ms: 1.00x slower                                                  |
| pickle_list              | 2.70 us                                                             | 2.72 us: 1.01x slower                                                 |
| pickle                   | 7.01 us                                                             | 7.09 us: 1.01x slower                                                 |
| coroutines               | 19.7 ms                                                             | 20.6 ms: 1.05x slower                                                 |
| python_startup_no_site   | 8.83 ms                                                             | 9.55 ms: 1.08x slower                                                 |
| bench_mp_pool            | 40.0 ms                                                             | 43.7 ms: 1.09x slower                                                 |
| generators               | 32.1 ms                                                             | 38.6 ms: 1.20x slower                                                 |
| dask                     | 251 ms                                                              | 327 ms: 1.30x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.15x faster                                                          |

Benchmark hidden because not significant (3): python_startup, unpickle_list, xml_etree_iterparse
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, pylint
Ignored benchmarks (4) of results/bm-20230207-3.12.0a5-3c67ec3/bm-20230207-darwin-arm64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.12x
