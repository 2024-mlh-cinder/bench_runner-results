
# Results vs. 3.10.4

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: darwin-arm64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.14x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 166 ms: 1.14x faster                                                  |
| chameleon      | 6.00 ms                                                             | 4.68 ms: 1.28x faster                                                 |
| docutils       | 1.71 sec                                                            | 1.48 sec: 1.15x faster                                                |
| html5lib       | 41.2 ms                                                             | 34.7 ms: 1.19x faster                                                 |
| Geometric mean | (ref)                                                               | 1.19x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization  | 466 ms                                                              | 333 ms: 1.40x faster                                                  |
| async_tree_none         | 381 ms                                                              | 295 ms: 1.29x faster                                                  |
| async_tree_io           | 972 ms                                                              | 758 ms: 1.28x faster                                                  |
| async_tree_cpu_io_mixed | 640 ms                                                              | 539 ms: 1.19x faster                                                  |
| Geometric mean          | (ref)                                                               | 1.29x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 68.4 ms: 1.29x faster                                                 |
| float          | 66.8 ms                                                             | 57.6 ms: 1.16x faster                                                 |
| pidigits       | 281 ms                                                              | 280 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.15x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 78.1 ms: 1.19x faster                                                 |
| regex_dna      | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| regex_v8       | 17.2 ms                                                             | 15.1 ms: 1.14x faster                                                 |
| regex_effbot   | 2.46 ms                                                             | 2.45 ms: 1.00x faster                                                 |
| Geometric mean | (ref)                                                               | 1.12x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.95 ms                                                             | 6.15 ms: 1.29x faster                                                 |
| pickle_pure_python   | 272 us                                                              | 213 us: 1.28x faster                                                  |
| xml_etree_process    | 45.8 ms                                                             | 36.4 ms: 1.26x faster                                                 |
| unpickle_pure_python | 190 us                                                              | 160 us: 1.19x faster                                                  |
| xml_etree_parse      | 108 ms                                                              | 96.5 ms: 1.12x faster                                                 |
| xml_etree_generate   | 52.4 ms                                                             | 47.5 ms: 1.10x faster                                                 |
| tomli_loads          | 1.66 sec                                                            | 1.51 sec: 1.10x faster                                                |
| unpickle             | 8.88 us                                                             | 8.45 us: 1.05x faster                                                 |
| unpickle_list        | 2.86 us                                                             | 2.75 us: 1.04x faster                                                 |
| json_loads           | 16.3 us                                                             | 15.8 us: 1.03x faster                                                 |
| xml_etree_iterparse  | 71.9 ms                                                             | 70.3 ms: 1.02x faster                                                 |
| pickle_list          | 2.70 us                                                             | 2.67 us: 1.01x faster                                                 |
| pickle_dict          | 16.9 us                                                             | 17.0 us: 1.01x slower                                                 |
| pickle               | 7.01 us                                                             | 7.13 us: 1.02x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.10x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 11.4 ms: 1.03x faster                                                 |
| python_startup_no_site | 8.83 ms                                                             | 9.48 ms: 1.07x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.02x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 9.78 ms                                                             | 7.45 ms: 1.31x faster                                                 |
| django_template | 25.5 ms                                                             | 21.9 ms: 1.16x faster                                                 |
| genshi_xml      | 33.6 ms                                                             | 30.7 ms: 1.09x faster                                                 |
| genshi_text     | 17.0 ms                                                             | 15.9 ms: 1.07x faster                                                 |
| Geometric mean  | (ref)                                                               | 1.16x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|--------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.93 ms                                                             | 2.83 ms: 1.74x faster                                                 |
| logging_silent           | 114 ns                                                              | 79.3 ns: 1.44x faster                                                 |
| async_tree_memoization   | 466 ms                                                              | 333 ms: 1.40x faster                                                  |
| richards_super           | 57.4 ms                                                             | 41.5 ms: 1.38x faster                                                 |
| richards                 | 47.7 ms                                                             | 34.7 ms: 1.38x faster                                                 |
| crypto_pyaes             | 70.7 ms                                                             | 51.5 ms: 1.37x faster                                                 |
| raytrace                 | 293 ms                                                              | 218 ms: 1.34x faster                                                  |
| mako                     | 9.78 ms                                                             | 7.45 ms: 1.31x faster                                                 |
| nbody                    | 88.4 ms                                                             | 68.4 ms: 1.29x faster                                                 |
| json_dumps               | 7.95 ms                                                             | 6.15 ms: 1.29x faster                                                 |
| async_tree_none          | 381 ms                                                              | 295 ms: 1.29x faster                                                  |
| chameleon                | 6.00 ms                                                             | 4.68 ms: 1.28x faster                                                 |
| scimark_sor              | 134 ms                                                              | 105 ms: 1.28x faster                                                  |
| async_tree_io            | 972 ms                                                              | 758 ms: 1.28x faster                                                  |
| pickle_pure_python       | 272 us                                                              | 213 us: 1.28x faster                                                  |
| create_gc_cycles         | 870 us                                                              | 682 us: 1.28x faster                                                  |
| spectral_norm            | 101 ms                                                              | 79.6 ms: 1.27x faster                                                 |
| thrift                   | 565 us                                                              | 445 us: 1.27x faster                                                  |
| pycparser                | 863 ms                                                              | 686 ms: 1.26x faster                                                  |
| xml_etree_process        | 45.8 ms                                                             | 36.4 ms: 1.26x faster                                                 |
| go                       | 148 ms                                                              | 118 ms: 1.26x faster                                                  |
| scimark_lu               | 102 ms                                                              | 81.7 ms: 1.25x faster                                                 |
| chaos                    | 64.0 ms                                                             | 51.4 ms: 1.24x faster                                                 |
| pyflate                  | 420 ms                                                              | 340 ms: 1.24x faster                                                  |
| pprint_pformat           | 1.28 sec                                                            | 1.03 sec: 1.24x faster                                                |
| pprint_safe_repr         | 625 ms                                                              | 507 ms: 1.23x faster                                                  |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 2.65 ms: 1.22x faster                                                 |
| hexiom                   | 6.05 ms                                                             | 4.97 ms: 1.22x faster                                                 |
| unpack_sequence          | 38.7 ns                                                             | 32.3 ns: 1.20x faster                                                 |
| regex_compile            | 92.8 ms                                                             | 78.1 ms: 1.19x faster                                                 |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 539 ms: 1.19x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 29.4 ms: 1.19x faster                                                 |
| unpickle_pure_python     | 190 us                                                              | 160 us: 1.19x faster                                                  |
| html5lib                 | 41.2 ms                                                             | 34.7 ms: 1.19x faster                                                 |
| sqlglot_parse            | 1.20 ms                                                             | 1.02 ms: 1.18x faster                                                 |
| scimark_monte_carlo      | 63.2 ms                                                             | 53.6 ms: 1.18x faster                                                 |
| regex_dna                | 173 ms                                                              | 147 ms: 1.18x faster                                                  |
| sqlglot_transpile        | 1.40 ms                                                             | 1.19 ms: 1.17x faster                                                 |
| django_template          | 25.5 ms                                                             | 21.9 ms: 1.16x faster                                                 |
| scimark_fft              | 216 ms                                                              | 186 ms: 1.16x faster                                                  |
| float                    | 66.8 ms                                                             | 57.6 ms: 1.16x faster                                                 |
| deepcopy_memo            | 33.2 us                                                             | 28.7 us: 1.16x faster                                                 |
| docutils                 | 1.71 sec                                                            | 1.48 sec: 1.15x faster                                                |
| 2to3                     | 189 ms                                                              | 166 ms: 1.14x faster                                                  |
| regex_v8                 | 17.2 ms                                                             | 15.1 ms: 1.14x faster                                                 |
| deepcopy                 | 269 us                                                              | 240 us: 1.12x faster                                                  |
| xml_etree_parse          | 108 ms                                                              | 96.5 ms: 1.12x faster                                                 |
| logging_format           | 4.59 us                                                             | 4.10 us: 1.12x faster                                                 |
| logging_simple           | 4.25 us                                                             | 3.81 us: 1.12x faster                                                 |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.46 sec: 1.11x faster                                                |
| async_generators         | 230 ms                                                              | 208 ms: 1.11x faster                                                  |
| fannkuch                 | 295 ms                                                              | 267 ms: 1.10x faster                                                  |
| xml_etree_generate       | 52.4 ms                                                             | 47.5 ms: 1.10x faster                                                 |
| telco                    | 3.41 ms                                                             | 3.09 ms: 1.10x faster                                                 |
| bench_thread_pool        | 534 us                                                              | 485 us: 1.10x faster                                                  |
| tomli_loads              | 1.66 sec                                                            | 1.51 sec: 1.10x faster                                                |
| sqlglot_optimize         | 36.3 ms                                                             | 33.1 ms: 1.10x faster                                                 |
| genshi_xml               | 33.6 ms                                                             | 30.7 ms: 1.09x faster                                                 |
| deepcopy_reduce          | 2.27 us                                                             | 2.09 us: 1.09x faster                                                 |
| sympy_expand             | 268 ms                                                              | 246 ms: 1.09x faster                                                  |
| sympy_integrate          | 12.9 ms                                                             | 11.9 ms: 1.08x faster                                                 |
| sympy_str                | 165 ms                                                              | 153 ms: 1.08x faster                                                  |
| sympy_sum                | 91.1 ms                                                             | 85.0 ms: 1.07x faster                                                 |
| genshi_text              | 17.0 ms                                                             | 15.9 ms: 1.07x faster                                                 |
| json                     | 3.04 ms                                                             | 2.85 ms: 1.06x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.77 sec: 1.06x faster                                                |
| unpickle                 | 8.88 us                                                             | 8.45 us: 1.05x faster                                                 |
| nqueens                  | 62.5 ms                                                             | 60.0 ms: 1.04x faster                                                 |
| sqlglot_normalize        | 187 ms                                                              | 180 ms: 1.04x faster                                                  |
| unpickle_list            | 2.86 us                                                             | 2.75 us: 1.04x faster                                                 |
| json_loads               | 16.3 us                                                             | 15.8 us: 1.03x faster                                                 |
| asyncio_tcp              | 682 ms                                                              | 661 ms: 1.03x faster                                                  |
| python_startup           | 11.8 ms                                                             | 11.4 ms: 1.03x faster                                                 |
| pathlib                  | 24.0 ms                                                             | 23.3 ms: 1.03x faster                                                 |
| meteor_contest           | 77.6 ms                                                             | 75.9 ms: 1.02x faster                                                 |
| xml_etree_iterparse      | 71.9 ms                                                             | 70.3 ms: 1.02x faster                                                 |
| typing_runtime_protocols | 335 us                                                              | 329 us: 1.02x faster                                                  |
| sqlite_synth             | 1.45 us                                                             | 1.43 us: 1.01x faster                                                 |
| pickle_list              | 2.70 us                                                             | 2.67 us: 1.01x faster                                                 |
| pidigits                 | 281 ms                                                              | 280 ms: 1.01x faster                                                  |
| regex_effbot             | 2.46 ms                                                             | 2.45 ms: 1.00x faster                                                 |
| gc_traversal             | 2.38 ms                                                             | 2.38 ms: 1.00x faster                                                 |
| asyncio_websockets       | 408 ms                                                              | 408 ms: 1.00x slower                                                  |
| pickle_dict              | 16.9 us                                                             | 17.0 us: 1.01x slower                                                 |
| pickle                   | 7.01 us                                                             | 7.13 us: 1.02x slower                                                 |
| comprehensions           | 16.8 us                                                             | 17.3 us: 1.02x slower                                                 |
| coroutines               | 19.7 ms                                                             | 20.5 ms: 1.04x slower                                                 |
| bench_mp_pool            | 40.0 ms                                                             | 42.6 ms: 1.07x slower                                                 |
| python_startup_no_site   | 8.83 ms                                                             | 9.48 ms: 1.07x slower                                                 |
| generators               | 32.1 ms                                                             | 37.2 ms: 1.16x slower                                                 |
| dask                     | 251 ms                                                              | 331 ms: 1.32x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.14x faster                                                          |
Ignored benchmarks (9) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, coverage, flaskblogging, gunicorn, mypy2, pylint, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
Ignored benchmarks (4) of results/bm-20221206-3.12.0a3-b6bd7ff/bm-20221206-darwin-arm64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.10x
