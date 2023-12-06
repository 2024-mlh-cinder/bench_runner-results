
# Results vs. 3.10.4

- fork: brandtbucher
- ref: break_up_float_reuse
- machine: linux-x86_64
- commit hash: 2dde229
- commit date: 2023-10-19
- overall geometric mean: 1.26x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.65 sec: 1.19x faster                                                       |
| tornado_http   | 127 ms                                                 | 95.7 ms: 1.33x faster                                                        |
| Geometric mean | (ref)                                                  | 1.26x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 95.9 ms: 1.48x faster                                                        |
| float          | 111 ms                                                 | 82.0 ms: 1.35x faster                                                        |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                         |
| Geometric mean | (ref)                                                  | 1.26x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 138 ms: 1.28x faster                                                         |
| regex_v8       | 25.0 ms                                                | 24.3 ms: 1.03x faster                                                        |
| regex_dna      | 222 ms                                                 | 218 ms: 1.02x faster                                                         |
| regex_effbot   | 3.23 ms                                                | 4.13 ms: 1.28x slower                                                        |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 311 us: 1.46x faster                                                         |
| unpickle_pure_python | 300 us                                                 | 223 us: 1.35x faster                                                         |
| tomli_loads          | 2.92 sec                                               | 2.18 sec: 1.34x faster                                                       |
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.30x faster                                                        |
| xml_etree_process    | 74.9 ms                                                | 59.9 ms: 1.25x faster                                                        |
| xml_etree_generate   | 94.2 ms                                                | 86.5 ms: 1.09x faster                                                        |
| xml_etree_iterparse  | 111 ms                                                 | 106 ms: 1.05x faster                                                         |
| json_loads           | 28.8 us                                                | 27.8 us: 1.04x faster                                                        |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                                         |
| unpickle             | 14.1 us                                                | 14.5 us: 1.03x slower                                                        |
| unpickle_list        | 4.82 us                                                | 5.25 us: 1.09x slower                                                        |
| pickle               | 10.3 us                                                | 11.5 us: 1.12x slower                                                        |
| pickle_list          | 4.56 us                                                | 5.22 us: 1.15x slower                                                        |
| pickle_dict          | 27.3 us                                                | 34.9 us: 1.28x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.08x faster                                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.41x faster                                                        |
| python_startup_no_site | 5.82 ms                                                | 6.86 ms: 1.18x slower                                                        |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.8 ms: 1.25x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-2dde229 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 153 us: 3.33x faster                                                         |
| generators               | 76.8 ms                                                | 29.8 ms: 2.58x faster                                                        |
| deltablue                | 7.42 ms                                                | 3.37 ms: 2.20x faster                                                        |
| asyncio_tcp              | 925 ms                                                 | 481 ms: 1.93x faster                                                         |
| chaos                    | 106 ms                                                 | 62.1 ms: 1.71x faster                                                        |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                                       |
| raytrace                 | 464 ms                                                 | 279 ms: 1.66x faster                                                         |
| logging_silent           | 175 ns                                                 | 107 ns: 1.64x faster                                                         |
| richards_super           | 90.7 ms                                                | 55.5 ms: 1.64x faster                                                        |
| async_tree_none          | 717 ms                                                 | 440 ms: 1.63x faster                                                         |
| crypto_pyaes             | 118 ms                                                 | 73.8 ms: 1.60x faster                                                        |
| go                       | 229 ms                                                 | 143 ms: 1.60x faster                                                         |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.60x faster                                                        |
| richards                 | 74.9 ms                                                | 48.8 ms: 1.53x faster                                                        |
| scimark_monte_carlo      | 108 ms                                                 | 70.7 ms: 1.53x faster                                                        |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.52x faster                                                        |
| hexiom                   | 9.53 ms                                                | 6.26 ms: 1.52x faster                                                        |
| async_tree_memoization   | 854 ms                                                 | 564 ms: 1.51x faster                                                         |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                       |
| scimark_sor              | 197 ms                                                 | 132 ms: 1.49x faster                                                         |
| nbody                    | 142 ms                                                 | 95.9 ms: 1.48x faster                                                        |
| pickle_pure_python       | 455 us                                                 | 311 us: 1.46x faster                                                         |
| pyflate                  | 673 ms                                                 | 476 ms: 1.41x faster                                                         |
| scimark_lu               | 163 ms                                                 | 116 ms: 1.41x faster                                                         |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.41x faster                                                        |
| logging_format           | 8.91 us                                                | 6.53 us: 1.36x faster                                                        |
| logging_simple           | 8.07 us                                                | 5.96 us: 1.35x faster                                                        |
| float                    | 111 ms                                                 | 82.0 ms: 1.35x faster                                                        |
| unpickle_pure_python     | 300 us                                                 | 223 us: 1.35x faster                                                         |
| coroutines               | 31.8 ms                                                | 23.7 ms: 1.34x faster                                                        |
| tomli_loads              | 2.92 sec                                               | 2.18 sec: 1.34x faster                                                       |
| deepcopy_memo            | 52.3 us                                                | 39.2 us: 1.34x faster                                                        |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 714 ms: 1.33x faster                                                         |
| tornado_http             | 127 ms                                                 | 95.7 ms: 1.33x faster                                                        |
| spectral_norm            | 150 ms                                                 | 114 ms: 1.31x faster                                                         |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.30x faster                                                       |
| json_dumps               | 13.5 ms                                                | 10.4 ms: 1.30x faster                                                        |
| comprehensions           | 26.8 us                                                | 20.8 us: 1.29x faster                                                        |
| regex_compile            | 177 ms                                                 | 138 ms: 1.28x faster                                                         |
| pprint_safe_repr         | 955 ms                                                 | 748 ms: 1.28x faster                                                         |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.26x faster                                                         |
| xml_etree_process        | 74.9 ms                                                | 59.9 ms: 1.25x faster                                                        |
| mako                     | 14.8 ms                                                | 11.8 ms: 1.25x faster                                                        |
| mypy2                    | 428 ms                                                 | 344 ms: 1.25x faster                                                         |
| deepcopy                 | 442 us                                                 | 355 us: 1.24x faster                                                         |
| nqueens                  | 100 ms                                                 | 80.9 ms: 1.24x faster                                                        |
| pycparser                | 1.50 sec                                               | 1.22 sec: 1.23x faster                                                       |
| sqlglot_optimize         | 65.3 ms                                                | 53.7 ms: 1.22x faster                                                        |
| deepcopy_reduce          | 3.82 us                                                | 3.16 us: 1.21x faster                                                        |
| docutils                 | 3.17 sec                                               | 2.65 sec: 1.19x faster                                                       |
| bench_thread_pool        | 947 us                                                 | 815 us: 1.16x faster                                                         |
| fannkuch                 | 486 ms                                                 | 420 ms: 1.16x faster                                                         |
| create_gc_cycles         | 1.67 ms                                                | 1.46 ms: 1.14x faster                                                        |
| dulwich_log              | 75.9 ms                                                | 67.0 ms: 1.13x faster                                                        |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.82 ms: 1.13x faster                                                        |
| scimark_fft              | 424 ms                                                 | 376 ms: 1.13x faster                                                         |
| unpack_sequence          | 64.7 ns                                                | 58.1 ns: 1.11x faster                                                        |
| xml_etree_generate       | 94.2 ms                                                | 86.5 ms: 1.09x faster                                                        |
| json                     | 5.42 ms                                                | 5.12 ms: 1.06x faster                                                        |
| meteor_contest           | 115 ms                                                 | 109 ms: 1.06x faster                                                         |
| mdp                      | 2.82 sec                                               | 2.67 sec: 1.06x faster                                                       |
| xml_etree_iterparse      | 111 ms                                                 | 106 ms: 1.05x faster                                                         |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.05x faster                                                        |
| json_loads               | 28.8 us                                                | 27.8 us: 1.04x faster                                                        |
| regex_v8                 | 25.0 ms                                                | 24.3 ms: 1.03x faster                                                        |
| xml_etree_parse          | 163 ms                                                 | 159 ms: 1.03x faster                                                         |
| sqlite_synth             | 2.93 us                                                | 2.87 us: 1.02x faster                                                        |
| regex_dna                | 222 ms                                                 | 218 ms: 1.02x faster                                                         |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                         |
| unpickle                 | 14.1 us                                                | 14.5 us: 1.03x slower                                                        |
| gc_traversal             | 3.84 ms                                                | 4.04 ms: 1.05x slower                                                        |
| async_generators         | 425 ms                                                 | 459 ms: 1.08x slower                                                         |
| unpickle_list            | 4.82 us                                                | 5.25 us: 1.09x slower                                                        |
| pickle                   | 10.3 us                                                | 11.5 us: 1.12x slower                                                        |
| pickle_list              | 4.56 us                                                | 5.22 us: 1.15x slower                                                        |
| python_startup_no_site   | 5.82 ms                                                | 6.86 ms: 1.18x slower                                                        |
| coverage                 | 72.8 ms                                                | 90.6 ms: 1.24x slower                                                        |
| telco                    | 6.54 ms                                                | 8.37 ms: 1.28x slower                                                        |
| pickle_dict              | 27.3 us                                                | 34.9 us: 1.28x slower                                                        |
| regex_effbot             | 3.23 ms                                                | 4.13 ms: 1.28x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.26x faster                                                                 |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.20x
