
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0rc1
- machine: linux-x86_64
- commit hash: 63bcd91
- commit date: 2023-08-05
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 267 ms: 1.26x faster                                         |
| docutils       | 3.17 sec                                               | 2.70 sec: 1.17x faster                                       |
| tornado_http   | 127 ms                                                 | 99.1 ms: 1.29x faster                                        |
| Geometric mean | (ref)                                                  | 1.24x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 89.6 ms: 1.58x faster                                        |
| float          | 111 ms                                                 | 79.3 ms: 1.39x faster                                        |
| pidigits       | 190 ms                                                 | 201 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                  | 1.28x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 145 ms: 1.22x faster                                         |
| regex_v8       | 25.0 ms                                                | 22.5 ms: 1.11x faster                                        |
| regex_dna      | 222 ms                                                 | 210 ms: 1.06x faster                                         |
| regex_effbot   | 3.23 ms                                                | 3.52 ms: 1.09x slower                                        |
| Geometric mean | (ref)                                                  | 1.07x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 311 us: 1.46x faster                                         |
| json_dumps           | 13.5 ms                                                | 9.75 ms: 1.39x faster                                        |
| unpickle_pure_python | 300 us                                                 | 219 us: 1.37x faster                                         |
| tomli_loads          | 2.92 sec                                               | 2.21 sec: 1.32x faster                                       |
| xml_etree_process    | 74.9 ms                                                | 59.2 ms: 1.26x faster                                        |
| json_loads           | 28.8 us                                                | 25.4 us: 1.13x faster                                        |
| xml_etree_generate   | 94.2 ms                                                | 85.4 ms: 1.10x faster                                        |
| xml_etree_iterparse  | 111 ms                                                 | 104 ms: 1.07x faster                                         |
| xml_etree_parse      | 163 ms                                                 | 155 ms: 1.05x faster                                         |
| unpickle_list        | 4.82 us                                                | 4.98 us: 1.03x slower                                        |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                        |
| unpickle             | 14.1 us                                                | 14.9 us: 1.06x slower                                        |
| pickle_dict          | 27.3 us                                                | 31.4 us: 1.15x slower                                        |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                 |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.30 ms: 1.52x faster                                        |
| python_startup_no_site | 5.82 ms                                                | 6.76 ms: 1.16x slower                                        |
| Geometric mean         | (ref)                                                  | 1.14x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.7 ms: 1.38x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230805-linux-x86_64-python-v3.12.0rc1-3.12.0rc1-63bcd91 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 149 us: 3.42x faster                                         |
| generators               | 76.8 ms                                                | 30.2 ms: 2.54x faster                                        |
| deltablue                | 7.42 ms                                                | 3.55 ms: 2.09x faster                                        |
| richards_super           | 90.7 ms                                                | 50.3 ms: 1.80x faster                                        |
| asyncio_tcp              | 925 ms                                                 | 515 ms: 1.80x faster                                         |
| logging_silent           | 175 ns                                                 | 102 ns: 1.71x faster                                         |
| go                       | 229 ms                                                 | 135 ms: 1.70x faster                                         |
| richards                 | 74.9 ms                                                | 44.3 ms: 1.69x faster                                        |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                       |
| chaos                    | 106 ms                                                 | 64.0 ms: 1.66x faster                                        |
| nbody                    | 142 ms                                                 | 89.6 ms: 1.58x faster                                        |
| scimark_sor              | 197 ms                                                 | 125 ms: 1.58x faster                                         |
| raytrace                 | 464 ms                                                 | 297 ms: 1.56x faster                                         |
| hexiom                   | 9.53 ms                                                | 6.21 ms: 1.53x faster                                        |
| async_tree_io            | 1.77 sec                                               | 1.16 sec: 1.52x faster                                       |
| sqlglot_parse            | 2.06 ms                                                | 1.35 ms: 1.52x faster                                        |
| async_tree_none          | 717 ms                                                 | 471 ms: 1.52x faster                                         |
| python_startup           | 14.2 ms                                                | 9.30 ms: 1.52x faster                                        |
| pyflate                  | 673 ms                                                 | 444 ms: 1.52x faster                                         |
| crypto_pyaes             | 118 ms                                                 | 78.4 ms: 1.51x faster                                        |
| scimark_monte_carlo      | 108 ms                                                 | 71.7 ms: 1.51x faster                                        |
| async_tree_memoization   | 854 ms                                                 | 573 ms: 1.49x faster                                         |
| sqlglot_transpile        | 2.45 ms                                                | 1.67 ms: 1.47x faster                                        |
| pickle_pure_python       | 455 us                                                 | 311 us: 1.46x faster                                         |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                         |
| deepcopy_memo            | 52.3 us                                                | 37.1 us: 1.41x faster                                        |
| spectral_norm            | 150 ms                                                 | 107 ms: 1.40x faster                                         |
| coroutines               | 31.8 ms                                                | 22.7 ms: 1.40x faster                                        |
| float                    | 111 ms                                                 | 79.3 ms: 1.39x faster                                        |
| json_dumps               | 13.5 ms                                                | 9.75 ms: 1.39x faster                                        |
| mako                     | 14.8 ms                                                | 10.7 ms: 1.38x faster                                        |
| unpickle_pure_python     | 300 us                                                 | 219 us: 1.37x faster                                         |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 708 ms: 1.34x faster                                         |
| pprint_pformat           | 1.99 sec                                               | 1.50 sec: 1.33x faster                                       |
| tomli_loads              | 2.92 sec                                               | 2.21 sec: 1.32x faster                                       |
| pycparser                | 1.50 sec                                               | 1.14 sec: 1.31x faster                                       |
| logging_simple           | 8.07 us                                                | 6.20 us: 1.30x faster                                        |
| comprehensions           | 26.8 us                                                | 20.7 us: 1.30x faster                                        |
| pprint_safe_repr         | 955 ms                                                 | 737 ms: 1.30x faster                                         |
| tornado_http             | 127 ms                                                 | 99.1 ms: 1.29x faster                                        |
| logging_format           | 8.91 us                                                | 6.99 us: 1.27x faster                                        |
| xml_etree_process        | 74.9 ms                                                | 59.2 ms: 1.26x faster                                        |
| 2to3                     | 336 ms                                                 | 267 ms: 1.26x faster                                         |
| mypy2                    | 428 ms                                                 | 343 ms: 1.25x faster                                         |
| deepcopy                 | 442 us                                                 | 355 us: 1.24x faster                                         |
| fannkuch                 | 486 ms                                                 | 394 ms: 1.23x faster                                         |
| unpack_sequence          | 64.7 ns                                                | 52.6 ns: 1.23x faster                                        |
| nqueens                  | 100 ms                                                 | 81.5 ms: 1.23x faster                                        |
| sqlglot_normalize        | 135 ms                                                 | 111 ms: 1.22x faster                                         |
| regex_compile            | 177 ms                                                 | 145 ms: 1.22x faster                                         |
| deepcopy_reduce          | 3.82 us                                                | 3.14 us: 1.22x faster                                        |
| sqlglot_optimize         | 65.3 ms                                                | 54.3 ms: 1.20x faster                                        |
| scimark_fft              | 424 ms                                                 | 356 ms: 1.19x faster                                         |
| docutils                 | 3.17 sec                                               | 2.70 sec: 1.17x faster                                       |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.4 ms: 1.15x faster                                        |
| sqlalchemy_declarative   | 165 ms                                                 | 145 ms: 1.14x faster                                         |
| bench_thread_pool        | 947 us                                                 | 832 us: 1.14x faster                                         |
| json                     | 5.42 ms                                                | 4.77 ms: 1.14x faster                                        |
| json_loads               | 28.8 us                                                | 25.4 us: 1.13x faster                                        |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.89 ms: 1.11x faster                                        |
| regex_v8                 | 25.0 ms                                                | 22.5 ms: 1.11x faster                                        |
| mdp                      | 2.82 sec                                               | 2.54 sec: 1.11x faster                                       |
| dulwich_log              | 75.9 ms                                                | 68.5 ms: 1.11x faster                                        |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                        |
| xml_etree_generate       | 94.2 ms                                                | 85.4 ms: 1.10x faster                                        |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.10x faster                                         |
| pathlib                  | 20.0 ms                                                | 18.3 ms: 1.10x faster                                        |
| xml_etree_iterparse      | 111 ms                                                 | 104 ms: 1.07x faster                                         |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                        |
| regex_dna                | 222 ms                                                 | 210 ms: 1.06x faster                                         |
| xml_etree_parse          | 163 ms                                                 | 155 ms: 1.05x faster                                         |
| gc_traversal             | 3.84 ms                                                | 3.91 ms: 1.02x slower                                        |
| unpickle_list            | 4.82 us                                                | 4.98 us: 1.03x slower                                        |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                        |
| telco                    | 6.54 ms                                                | 6.86 ms: 1.05x slower                                        |
| pidigits                 | 190 ms                                                 | 201 ms: 1.06x slower                                         |
| unpickle                 | 14.1 us                                                | 14.9 us: 1.06x slower                                        |
| async_generators         | 425 ms                                                 | 450 ms: 1.06x slower                                         |
| regex_effbot             | 3.23 ms                                                | 3.52 ms: 1.09x slower                                        |
| pickle_dict              | 27.3 us                                                | 31.4 us: 1.15x slower                                        |
| python_startup_no_site   | 5.82 ms                                                | 6.76 ms: 1.16x slower                                        |
| dask                     | 423 ms                                                 | 537 ms: 1.27x slower                                         |
| coverage                 | 72.8 ms                                                | 94.3 ms: 1.30x slower                                        |
| Geometric mean           | (ref)                                                  | 1.28x faster                                                 |

Benchmark hidden because not significant (2): pickle_list, bench_mp_pool
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
