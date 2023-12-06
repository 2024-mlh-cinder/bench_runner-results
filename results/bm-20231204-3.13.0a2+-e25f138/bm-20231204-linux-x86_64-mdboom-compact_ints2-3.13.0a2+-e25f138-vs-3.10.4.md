
# Results vs. 3.10.4

- fork: mdboom
- ref: compact_ints2
- machine: linux-x86_64
- commit hash: e25f138
- commit date: 2023-12-04
- overall geometric mean: 1.33x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                            |
| chameleon      | 9.84 ms                                                | 7.01 ms: 1.40x faster                                           |
| docutils       | 3.26 sec                                               | 2.60 sec: 1.25x faster                                          |
| tornado_http   | 131 ms                                                 | 94.6 ms: 1.38x faster                                           |
| Geometric mean | (ref)                                                  | 1.34x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 438 ms: 1.67x faster                                            |
| async_tree_memoization  | 867 ms                                                 | 566 ms: 1.53x faster                                            |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.50x faster                                          |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 709 ms: 1.42x faster                                            |
| Geometric mean          | (ref)                                                  | 1.53x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 90.1 ms: 1.64x faster                                           |
| float          | 116 ms                                                 | 82.2 ms: 1.42x faster                                           |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                            |
| Geometric mean | (ref)                                                  | 1.33x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 135 ms: 1.37x faster                                            |
| regex_v8       | 26.2 ms                                                | 26.4 ms: 1.01x slower                                           |
| regex_dna      | 215 ms                                                 | 220 ms: 1.02x slower                                            |
| regex_effbot   | 3.41 ms                                                | 3.71 ms: 1.09x slower                                           |
| Geometric mean | (ref)                                                  | 1.05x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 302 us: 1.60x faster                                            |
| unpickle_pure_python | 327 us                                                 | 218 us: 1.50x faster                                            |
| tomli_loads          | 3.06 sec                                               | 2.23 sec: 1.37x faster                                          |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                           |
| xml_etree_process    | 79.8 ms                                                | 59.6 ms: 1.34x faster                                           |
| xml_etree_generate   | 100.0 ms                                               | 86.8 ms: 1.15x faster                                           |
| json_loads           | 31.4 us                                                | 28.0 us: 1.12x faster                                           |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.10x faster                                            |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                            |
| pickle_list          | 5.05 us                                                | 4.88 us: 1.03x faster                                           |
| unpickle_list        | 5.10 us                                                | 4.98 us: 1.02x faster                                           |
| unpickle             | 14.9 us                                                | 15.0 us: 1.01x slower                                           |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                           |
| pickle_dict          | 30.0 us                                                | 33.7 us: 1.12x slower                                           |
| Geometric mean       | (ref)                                                  | 1.16x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                           |
| python_startup_no_site | 5.87 ms                                                | 8.99 ms: 1.53x slower                                           |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.3 ms: 1.44x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 115 us: 4.88x faster                                            |
| generators               | 78.9 ms                                                | 29.2 ms: 2.70x faster                                           |
| deltablue                | 7.81 ms                                                | 3.33 ms: 2.35x faster                                           |
| asyncio_tcp              | 918 ms                                                 | 484 ms: 1.90x faster                                            |
| chaos                    | 114 ms                                                 | 61.4 ms: 1.86x faster                                           |
| raytrace                 | 498 ms                                                 | 277 ms: 1.80x faster                                            |
| crypto_pyaes             | 127 ms                                                 | 71.0 ms: 1.79x faster                                           |
| richards_super           | 95.6 ms                                                | 54.0 ms: 1.77x faster                                           |
| logging_silent           | 189 ns                                                 | 107 ns: 1.76x faster                                            |
| comprehensions           | 28.5 us                                                | 16.4 us: 1.74x faster                                           |
| scimark_sor              | 214 ms                                                 | 125 ms: 1.72x faster                                            |
| scimark_monte_carlo      | 118 ms                                                 | 68.8 ms: 1.71x faster                                           |
| sqlglot_parse            | 2.15 ms                                                | 1.26 ms: 1.70x faster                                           |
| go                       | 238 ms                                                 | 142 ms: 1.68x faster                                            |
| async_tree_none          | 732 ms                                                 | 438 ms: 1.67x faster                                            |
| hexiom                   | 10.3 ms                                                | 6.18 ms: 1.67x faster                                           |
| richards                 | 79.4 ms                                                | 47.8 ms: 1.66x faster                                           |
| nbody                    | 148 ms                                                 | 90.1 ms: 1.64x faster                                           |
| sqlglot_transpile        | 2.55 ms                                                | 1.58 ms: 1.61x faster                                           |
| pickle_pure_python       | 482 us                                                 | 302 us: 1.60x faster                                            |
| coroutines               | 34.5 ms                                                | 22.0 ms: 1.57x faster                                           |
| async_tree_memoization   | 867 ms                                                 | 566 ms: 1.53x faster                                            |
| scimark_lu               | 175 ms                                                 | 115 ms: 1.53x faster                                            |
| pyflate                  | 708 ms                                                 | 465 ms: 1.52x faster                                            |
| deepcopy_memo            | 58.8 us                                                | 39.0 us: 1.51x faster                                           |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.50x faster                                          |
| unpickle_pure_python     | 327 us                                                 | 218 us: 1.50x faster                                            |
| logging_simple           | 8.27 us                                                | 5.71 us: 1.45x faster                                           |
| logging_format           | 9.07 us                                                | 6.27 us: 1.45x faster                                           |
| spectral_norm            | 163 ms                                                 | 113 ms: 1.44x faster                                            |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.78 sec: 1.44x faster                                          |
| mako                     | 16.3 ms                                                | 11.3 ms: 1.44x faster                                           |
| unpack_sequence          | 65.7 ns                                                | 45.8 ns: 1.43x faster                                           |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 709 ms: 1.42x faster                                            |
| float                    | 116 ms                                                 | 82.2 ms: 1.42x faster                                           |
| chameleon                | 9.84 ms                                                | 7.01 ms: 1.40x faster                                           |
| pprint_pformat           | 2.10 sec                                               | 1.50 sec: 1.40x faster                                          |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                           |
| pprint_safe_repr         | 1.01 sec                                               | 732 ms: 1.39x faster                                            |
| deepcopy                 | 481 us                                                 | 347 us: 1.38x faster                                            |
| tornado_http             | 131 ms                                                 | 94.6 ms: 1.38x faster                                           |
| regex_compile            | 186 ms                                                 | 135 ms: 1.37x faster                                            |
| tomli_loads              | 3.06 sec                                               | 2.23 sec: 1.37x faster                                          |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                           |
| sqlglot_normalize        | 141 ms                                                 | 105 ms: 1.34x faster                                            |
| deepcopy_reduce          | 4.17 us                                                | 3.11 us: 1.34x faster                                           |
| nqueens                  | 107 ms                                                 | 79.6 ms: 1.34x faster                                           |
| xml_etree_process        | 79.8 ms                                                | 59.6 ms: 1.34x faster                                           |
| fannkuch                 | 527 ms                                                 | 395 ms: 1.33x faster                                            |
| sympy_integrate          | 25.4 ms                                                | 19.4 ms: 1.31x faster                                           |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                            |
| sympy_sum                | 190 ms                                                 | 147 ms: 1.30x faster                                            |
| pycparser                | 1.57 sec                                               | 1.22 sec: 1.29x faster                                          |
| sqlglot_optimize         | 68.7 ms                                                | 53.5 ms: 1.28x faster                                           |
| sympy_str                | 337 ms                                                 | 266 ms: 1.26x faster                                            |
| docutils                 | 3.26 sec                                               | 2.60 sec: 1.25x faster                                          |
| scimark_fft              | 454 ms                                                 | 366 ms: 1.24x faster                                            |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.92 ms: 1.24x faster                                           |
| sympy_expand             | 558 ms                                                 | 451 ms: 1.24x faster                                            |
| dulwich_log              | 77.0 ms                                                | 64.9 ms: 1.19x faster                                           |
| bench_thread_pool        | 966 us                                                 | 828 us: 1.17x faster                                            |
| xml_etree_generate       | 100.0 ms                                               | 86.8 ms: 1.15x faster                                           |
| pathlib                  | 20.3 ms                                                | 17.9 ms: 1.13x faster                                           |
| json_loads               | 31.4 us                                                | 28.0 us: 1.12x faster                                           |
| meteor_contest           | 119 ms                                                 | 107 ms: 1.11x faster                                            |
| json                     | 5.67 ms                                                | 5.17 ms: 1.10x faster                                           |
| xml_etree_iterparse      | 116 ms                                                 | 106 ms: 1.10x faster                                            |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.09x faster                                           |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                            |
| sqlite_synth             | 3.02 us                                                | 2.80 us: 1.08x faster                                           |
| mdp                      | 2.93 sec                                               | 2.81 sec: 1.04x faster                                          |
| pickle_list              | 5.05 us                                                | 4.88 us: 1.03x faster                                           |
| unpickle_list            | 5.10 us                                                | 4.98 us: 1.02x faster                                           |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                            |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                            |
| regex_v8                 | 26.2 ms                                                | 26.4 ms: 1.01x slower                                           |
| unpickle                 | 14.9 us                                                | 15.0 us: 1.01x slower                                           |
| regex_dna                | 215 ms                                                 | 220 ms: 1.02x slower                                            |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                           |
| regex_effbot             | 3.41 ms                                                | 3.71 ms: 1.09x slower                                           |
| pickle_dict              | 30.0 us                                                | 33.7 us: 1.12x slower                                           |
| coverage                 | 82.0 ms                                                | 94.7 ms: 1.16x slower                                           |
| telco                    | 7.01 ms                                                | 8.28 ms: 1.18x slower                                           |
| gc_traversal             | 3.43 ms                                                | 4.17 ms: 1.21x slower                                           |
| python_startup_no_site   | 5.87 ms                                                | 8.99 ms: 1.53x slower                                           |
| mypy2                    | 442 ms                                                 | 838 ms: 1.89x slower                                            |
| Geometric mean           | (ref)                                                  | 1.33x faster                                                    |

Benchmark hidden because not significant (2): bench_mp_pool, async_generators
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231204-3.13.0a2+-e25f138/bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.25x
