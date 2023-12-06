
# Results vs. 3.10.4

- fork: mdboom
- ref: test_branch
- machine: linux-x86_64
- commit hash: 3ce7ef8
- commit date: 2023-11-14
- overall geometric mean: 1.24x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 294 ms: 1.17x faster                                          |
| chameleon      | 9.84 ms                                                | 7.48 ms: 1.32x faster                                         |
| docutils       | 3.26 sec                                               | 2.74 sec: 1.19x faster                                        |
| tornado_http   | 131 ms                                                 | 102 ms: 1.28x faster                                          |
| Geometric mean | (ref)                                                  | 1.24x faster                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 463 ms: 1.58x faster                                          |
| async_tree_memoization  | 867 ms                                                 | 590 ms: 1.47x faster                                          |
| async_tree_io           | 1.79 sec                                               | 1.23 sec: 1.45x faster                                        |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 742 ms: 1.36x faster                                          |
| Geometric mean          | (ref)                                                  | 1.46x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 122 ms: 1.21x faster                                          |
| float          | 116 ms                                                 | 102 ms: 1.14x faster                                          |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.12x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 166 ms: 1.11x faster                                          |
| regex_v8       | 26.2 ms                                                | 24.8 ms: 1.06x faster                                         |
| regex_dna      | 215 ms                                                 | 213 ms: 1.01x faster                                          |
| regex_effbot   | 3.41 ms                                                | 3.50 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                  | 1.04x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 308 us: 1.57x faster                                          |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                         |
| unpickle_pure_python | 327 us                                                 | 242 us: 1.35x faster                                          |
| xml_etree_process    | 79.8 ms                                                | 59.9 ms: 1.33x faster                                         |
| xml_etree_generate   | 100.0 ms                                               | 87.9 ms: 1.14x faster                                         |
| json_loads           | 31.4 us                                                | 28.1 us: 1.12x faster                                         |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                          |
| pickle_list          | 5.05 us                                                | 4.92 us: 1.03x faster                                         |
| xml_etree_iterparse  | 116 ms                                                 | 114 ms: 1.02x faster                                          |
| tomli_loads          | 3.06 sec                                               | 3.07 sec: 1.00x slower                                        |
| pickle               | 10.7 us                                                | 11.0 us: 1.03x slower                                         |
| unpickle             | 14.9 us                                                | 15.4 us: 1.04x slower                                         |
| unpickle_list        | 5.10 us                                                | 5.33 us: 1.05x slower                                         |
| pickle_dict          | 30.0 us                                                | 32.4 us: 1.08x slower                                         |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                         |
| python_startup_no_site | 5.87 ms                                                | 9.05 ms: 1.54x slower                                         |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 14.5 ms: 1.12x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 127 us: 4.40x faster                                          |
| generators               | 78.9 ms                                                | 29.2 ms: 2.71x faster                                         |
| asyncio_tcp              | 918 ms                                                 | 494 ms: 1.86x faster                                          |
| logging_silent           | 189 ns                                                 | 107 ns: 1.76x faster                                          |
| scimark_sor              | 214 ms                                                 | 128 ms: 1.67x faster                                          |
| raytrace                 | 498 ms                                                 | 308 ms: 1.62x faster                                          |
| richards_super           | 95.6 ms                                                | 59.7 ms: 1.60x faster                                         |
| async_tree_none          | 732 ms                                                 | 463 ms: 1.58x faster                                          |
| sqlglot_parse            | 2.15 ms                                                | 1.36 ms: 1.58x faster                                         |
| pickle_pure_python       | 482 us                                                 | 308 us: 1.57x faster                                          |
| coroutines               | 34.5 ms                                                | 22.0 ms: 1.57x faster                                         |
| sqlglot_transpile        | 2.55 ms                                                | 1.68 ms: 1.52x faster                                         |
| richards                 | 79.4 ms                                                | 52.5 ms: 1.51x faster                                         |
| chaos                    | 114 ms                                                 | 75.6 ms: 1.51x faster                                         |
| deltablue                | 7.81 ms                                                | 5.20 ms: 1.50x faster                                         |
| crypto_pyaes             | 127 ms                                                 | 85.7 ms: 1.48x faster                                         |
| async_tree_memoization   | 867 ms                                                 | 590 ms: 1.47x faster                                          |
| scimark_monte_carlo      | 118 ms                                                 | 80.5 ms: 1.46x faster                                         |
| scimark_lu               | 175 ms                                                 | 121 ms: 1.45x faster                                          |
| async_tree_io            | 1.79 sec                                               | 1.23 sec: 1.45x faster                                        |
| spectral_norm            | 163 ms                                                 | 113 ms: 1.45x faster                                          |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                        |
| deepcopy_memo            | 58.8 us                                                | 41.8 us: 1.41x faster                                         |
| go                       | 238 ms                                                 | 171 ms: 1.39x faster                                          |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                         |
| unpack_sequence          | 65.7 ns                                                | 47.5 ns: 1.38x faster                                         |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                         |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 742 ms: 1.36x faster                                          |
| deepcopy                 | 481 us                                                 | 355 us: 1.35x faster                                          |
| unpickle_pure_python     | 327 us                                                 | 242 us: 1.35x faster                                          |
| xml_etree_process        | 79.8 ms                                                | 59.9 ms: 1.33x faster                                         |
| deepcopy_reduce          | 4.17 us                                                | 3.13 us: 1.33x faster                                         |
| logging_simple           | 8.27 us                                                | 6.29 us: 1.32x faster                                         |
| chameleon                | 9.84 ms                                                | 7.48 ms: 1.32x faster                                         |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                          |
| tornado_http             | 131 ms                                                 | 102 ms: 1.28x faster                                          |
| logging_format           | 9.07 us                                                | 7.11 us: 1.28x faster                                         |
| pyflate                  | 708 ms                                                 | 555 ms: 1.28x faster                                          |
| pycparser                | 1.57 sec                                               | 1.23 sec: 1.27x faster                                        |
| pprint_safe_repr         | 1.01 sec                                               | 808 ms: 1.26x faster                                          |
| pprint_pformat           | 2.10 sec                                               | 1.67 sec: 1.25x faster                                        |
| sqlglot_optimize         | 68.7 ms                                                | 54.9 ms: 1.25x faster                                         |
| mypy2                    | 442 ms                                                 | 358 ms: 1.23x faster                                          |
| sympy_sum                | 190 ms                                                 | 155 ms: 1.23x faster                                          |
| nbody                    | 148 ms                                                 | 122 ms: 1.21x faster                                          |
| docutils                 | 3.26 sec                                               | 2.74 sec: 1.19x faster                                        |
| sympy_integrate          | 25.4 ms                                                | 21.6 ms: 1.18x faster                                         |
| 2to3                     | 346 ms                                                 | 294 ms: 1.17x faster                                          |
| sympy_str                | 337 ms                                                 | 288 ms: 1.17x faster                                          |
| sympy_expand             | 558 ms                                                 | 489 ms: 1.14x faster                                          |
| float                    | 116 ms                                                 | 102 ms: 1.14x faster                                          |
| xml_etree_generate       | 100.0 ms                                               | 87.9 ms: 1.14x faster                                         |
| bench_thread_pool        | 966 us                                                 | 858 us: 1.13x faster                                          |
| mako                     | 16.3 ms                                                | 14.5 ms: 1.12x faster                                         |
| json_loads               | 31.4 us                                                | 28.1 us: 1.12x faster                                         |
| regex_compile            | 186 ms                                                 | 166 ms: 1.11x faster                                          |
| comprehensions           | 28.5 us                                                | 25.7 us: 1.11x faster                                         |
| dulwich_log              | 77.0 ms                                                | 69.3 ms: 1.11x faster                                         |
| json                     | 5.67 ms                                                | 5.15 ms: 1.10x faster                                         |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.09x faster                                         |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                          |
| mdp                      | 2.93 sec                                               | 2.73 sec: 1.07x faster                                        |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                         |
| fannkuch                 | 527 ms                                                 | 492 ms: 1.07x faster                                          |
| sqlite_synth             | 3.02 us                                                | 2.85 us: 1.06x faster                                         |
| regex_v8                 | 26.2 ms                                                | 24.8 ms: 1.06x faster                                         |
| scimark_fft              | 454 ms                                                 | 432 ms: 1.05x faster                                          |
| pickle_list              | 5.05 us                                                | 4.92 us: 1.03x faster                                         |
| meteor_contest           | 119 ms                                                 | 117 ms: 1.02x faster                                          |
| xml_etree_iterparse      | 116 ms                                                 | 114 ms: 1.02x faster                                          |
| nqueens                  | 107 ms                                                 | 105 ms: 1.02x faster                                          |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                          |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                          |
| regex_dna                | 215 ms                                                 | 213 ms: 1.01x faster                                          |
| hexiom                   | 10.3 ms                                                | 10.2 ms: 1.01x faster                                         |
| tomli_loads              | 3.06 sec                                               | 3.07 sec: 1.00x slower                                        |
| regex_effbot             | 3.41 ms                                                | 3.50 ms: 1.03x slower                                         |
| pickle                   | 10.7 us                                                | 11.0 us: 1.03x slower                                         |
| unpickle                 | 14.9 us                                                | 15.4 us: 1.04x slower                                         |
| async_generators         | 442 ms                                                 | 462 ms: 1.05x slower                                          |
| unpickle_list            | 5.10 us                                                | 5.33 us: 1.05x slower                                         |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.56 ms: 1.08x slower                                         |
| pickle_dict              | 30.0 us                                                | 32.4 us: 1.08x slower                                         |
| gc_traversal             | 3.43 ms                                                | 3.87 ms: 1.13x slower                                         |
| coverage                 | 82.0 ms                                                | 95.6 ms: 1.17x slower                                         |
| telco                    | 7.01 ms                                                | 8.76 ms: 1.25x slower                                         |
| python_startup_no_site   | 5.87 ms                                                | 9.05 ms: 1.54x slower                                         |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                  |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231114-3.13.0a1+-3ce7ef8-PYTHON_UOPS/bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1+-3ce7ef8.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.14x
