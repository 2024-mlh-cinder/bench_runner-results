
# Results vs. 3.10.4

- fork: mdboom
- ref: test_branch3
- machine: linux-x86_64
- commit hash: dbd826e
- commit date: 2023-11-20
- overall geometric mean: 1.24x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 288 ms: 1.20x faster                                           |
| chameleon      | 9.84 ms                                                | 7.46 ms: 1.32x faster                                          |
| docutils       | 3.26 sec                                               | 2.72 sec: 1.20x faster                                         |
| tornado_http   | 131 ms                                                 | 99.1 ms: 1.32x faster                                          |
| Geometric mean | (ref)                                                  | 1.26x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 452 ms: 1.62x faster                                           |
| async_tree_memoization  | 867 ms                                                 | 581 ms: 1.49x faster                                           |
| async_tree_io           | 1.79 sec                                               | 1.21 sec: 1.48x faster                                         |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 725 ms: 1.39x faster                                           |
| Geometric mean          | (ref)                                                  | 1.49x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 112 ms: 1.33x faster                                           |
| float          | 116 ms                                                 | 94.4 ms: 1.23x faster                                          |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                  | 1.17x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 160 ms: 1.16x faster                                           |
| regex_v8       | 26.2 ms                                                | 24.5 ms: 1.07x faster                                          |
| regex_dna      | 215 ms                                                 | 217 ms: 1.01x slower                                           |
| regex_effbot   | 3.41 ms                                                | 3.57 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 313 us: 1.54x faster                                           |
| unpickle_pure_python | 327 us                                                 | 241 us: 1.35x faster                                           |
| json_dumps           | 14.3 ms                                                | 10.7 ms: 1.34x faster                                          |
| xml_etree_process    | 79.8 ms                                                | 63.1 ms: 1.26x faster                                          |
| tomli_loads          | 3.06 sec                                               | 2.51 sec: 1.22x faster                                         |
| json_loads           | 31.4 us                                                | 28.5 us: 1.10x faster                                          |
| xml_etree_generate   | 100.0 ms                                               | 92.6 ms: 1.08x faster                                          |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.07x faster                                           |
| xml_etree_iterparse  | 116 ms                                                 | 114 ms: 1.01x faster                                           |
| unpickle_list        | 5.10 us                                                | 5.16 us: 1.01x slower                                          |
| pickle_list          | 5.05 us                                                | 5.20 us: 1.03x slower                                          |
| pickle               | 10.7 us                                                | 11.7 us: 1.09x slower                                          |
| pickle_dict          | 30.0 us                                                | 35.5 us: 1.19x slower                                          |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                   |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                          |
| python_startup_no_site | 5.87 ms                                                | 9.05 ms: 1.54x slower                                          |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 14.5 ms: 1.12x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 124 us: 4.50x faster                                           |
| generators               | 78.9 ms                                                | 29.7 ms: 2.65x faster                                          |
| asyncio_tcp              | 918 ms                                                 | 491 ms: 1.87x faster                                           |
| logging_silent           | 189 ns                                                 | 108 ns: 1.75x faster                                           |
| scimark_sor              | 214 ms                                                 | 127 ms: 1.68x faster                                           |
| richards_super           | 95.6 ms                                                | 57.2 ms: 1.67x faster                                          |
| async_tree_none          | 732 ms                                                 | 452 ms: 1.62x faster                                           |
| raytrace                 | 498 ms                                                 | 309 ms: 1.61x faster                                           |
| deltablue                | 7.81 ms                                                | 4.87 ms: 1.60x faster                                          |
| richards                 | 79.4 ms                                                | 50.8 ms: 1.56x faster                                          |
| sqlglot_parse            | 2.15 ms                                                | 1.38 ms: 1.55x faster                                          |
| pickle_pure_python       | 482 us                                                 | 313 us: 1.54x faster                                           |
| coroutines               | 34.5 ms                                                | 22.7 ms: 1.52x faster                                          |
| chaos                    | 114 ms                                                 | 75.6 ms: 1.51x faster                                          |
| async_tree_memoization   | 867 ms                                                 | 581 ms: 1.49x faster                                           |
| sqlglot_transpile        | 2.55 ms                                                | 1.71 ms: 1.49x faster                                          |
| async_tree_io            | 1.79 sec                                               | 1.21 sec: 1.48x faster                                         |
| scimark_monte_carlo      | 118 ms                                                 | 80.1 ms: 1.47x faster                                          |
| crypto_pyaes             | 127 ms                                                 | 86.6 ms: 1.46x faster                                          |
| go                       | 238 ms                                                 | 163 ms: 1.46x faster                                           |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.46x faster                                           |
| deepcopy_memo            | 58.8 us                                                | 41.1 us: 1.43x faster                                          |
| unpack_sequence          | 65.7 ns                                                | 46.0 ns: 1.43x faster                                          |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                         |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 725 ms: 1.39x faster                                           |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                          |
| unpickle_pure_python     | 327 us                                                 | 241 us: 1.35x faster                                           |
| logging_simple           | 8.27 us                                                | 6.15 us: 1.34x faster                                          |
| json_dumps               | 14.3 ms                                                | 10.7 ms: 1.34x faster                                          |
| deepcopy                 | 481 us                                                 | 361 us: 1.33x faster                                           |
| nbody                    | 148 ms                                                 | 112 ms: 1.33x faster                                           |
| deepcopy_reduce          | 4.17 us                                                | 3.15 us: 1.32x faster                                          |
| chameleon                | 9.84 ms                                                | 7.46 ms: 1.32x faster                                          |
| tornado_http             | 131 ms                                                 | 99.1 ms: 1.32x faster                                          |
| pyflate                  | 708 ms                                                 | 543 ms: 1.30x faster                                           |
| pycparser                | 1.57 sec                                               | 1.20 sec: 1.30x faster                                         |
| logging_format           | 9.07 us                                                | 6.98 us: 1.30x faster                                          |
| comprehensions           | 28.5 us                                                | 22.2 us: 1.29x faster                                          |
| xml_etree_process        | 79.8 ms                                                | 63.1 ms: 1.26x faster                                          |
| pprint_safe_repr         | 1.01 sec                                               | 812 ms: 1.25x faster                                           |
| pprint_pformat           | 2.10 sec                                               | 1.69 sec: 1.24x faster                                         |
| mypy2                    | 442 ms                                                 | 357 ms: 1.24x faster                                           |
| float                    | 116 ms                                                 | 94.4 ms: 1.23x faster                                          |
| sqlglot_normalize        | 141 ms                                                 | 115 ms: 1.23x faster                                           |
| tomli_loads              | 3.06 sec                                               | 2.51 sec: 1.22x faster                                         |
| docutils                 | 3.26 sec                                               | 2.72 sec: 1.20x faster                                         |
| 2to3                     | 346 ms                                                 | 288 ms: 1.20x faster                                           |
| sympy_integrate          | 25.4 ms                                                | 21.4 ms: 1.18x faster                                          |
| sympy_sum                | 190 ms                                                 | 161 ms: 1.18x faster                                           |
| dask                     | 432 ms                                                 | 368 ms: 1.17x faster                                           |
| sqlglot_optimize         | 68.7 ms                                                | 58.6 ms: 1.17x faster                                          |
| regex_compile            | 186 ms                                                 | 160 ms: 1.16x faster                                           |
| hexiom                   | 10.3 ms                                                | 8.90 ms: 1.16x faster                                          |
| sympy_str                | 337 ms                                                 | 296 ms: 1.14x faster                                           |
| sympy_expand             | 558 ms                                                 | 491 ms: 1.14x faster                                           |
| fannkuch                 | 527 ms                                                 | 464 ms: 1.14x faster                                           |
| bench_thread_pool        | 966 us                                                 | 858 us: 1.13x faster                                           |
| mako                     | 16.3 ms                                                | 14.5 ms: 1.12x faster                                          |
| dulwich_log              | 77.0 ms                                                | 69.6 ms: 1.11x faster                                          |
| json_loads               | 31.4 us                                                | 28.5 us: 1.10x faster                                          |
| nqueens                  | 107 ms                                                 | 97.0 ms: 1.10x faster                                          |
| json                     | 5.67 ms                                                | 5.18 ms: 1.09x faster                                          |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.09x faster                                          |
| pathlib                  | 20.3 ms                                                | 18.7 ms: 1.08x faster                                          |
| xml_etree_generate       | 100.0 ms                                               | 92.6 ms: 1.08x faster                                          |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.07x faster                                           |
| regex_v8                 | 26.2 ms                                                | 24.5 ms: 1.07x faster                                          |
| sqlite_synth             | 3.02 us                                                | 2.89 us: 1.04x faster                                          |
| spectral_norm            | 163 ms                                                 | 156 ms: 1.04x faster                                           |
| mdp                      | 2.93 sec                                               | 2.82 sec: 1.04x faster                                         |
| meteor_contest           | 119 ms                                                 | 118 ms: 1.01x faster                                           |
| xml_etree_iterparse      | 116 ms                                                 | 114 ms: 1.01x faster                                           |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                           |
| regex_dna                | 215 ms                                                 | 217 ms: 1.01x slower                                           |
| unpickle_list            | 5.10 us                                                | 5.16 us: 1.01x slower                                          |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.23 ms: 1.02x slower                                          |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| pickle_list              | 5.05 us                                                | 5.20 us: 1.03x slower                                          |
| async_generators         | 442 ms                                                 | 460 ms: 1.04x slower                                           |
| regex_effbot             | 3.41 ms                                                | 3.57 ms: 1.05x slower                                          |
| pickle                   | 10.7 us                                                | 11.7 us: 1.09x slower                                          |
| gc_traversal             | 3.43 ms                                                | 3.83 ms: 1.12x slower                                          |
| coverage                 | 82.0 ms                                                | 94.8 ms: 1.16x slower                                          |
| pickle_dict              | 30.0 us                                                | 35.5 us: 1.19x slower                                          |
| telco                    | 7.01 ms                                                | 8.64 ms: 1.23x slower                                          |
| python_startup_no_site   | 5.87 ms                                                | 9.05 ms: 1.54x slower                                          |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                   |

Benchmark hidden because not significant (3): bench_mp_pool, unpickle, scimark_fft
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-dbd826e-PYTHON_UOPS/bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1+-dbd826e.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
