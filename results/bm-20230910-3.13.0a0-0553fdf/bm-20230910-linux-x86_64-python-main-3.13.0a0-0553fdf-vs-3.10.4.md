
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.31x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.60 sec: 1.22x faster                                |
| tornado_http   | 127 ms                                                 | 94.9 ms: 1.34x faster                                 |
| Geometric mean | (ref)                                                  | 1.28x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 142 ms                                                 | 90.6 ms: 1.56x faster                                 |
| float          | 111 ms                                                 | 79.8 ms: 1.39x faster                                 |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.30x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 134 ms: 1.32x faster                                  |
| regex_dna      | 222 ms                                                 | 205 ms: 1.08x faster                                  |
| regex_v8       | 25.0 ms                                                | 23.4 ms: 1.07x faster                                 |
| regex_effbot   | 3.23 ms                                                | 3.50 ms: 1.09x slower                                 |
| Geometric mean | (ref)                                                  | 1.09x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 295 us: 1.54x faster                                  |
| tomli_loads          | 2.92 sec                                               | 2.02 sec: 1.45x faster                                |
| unpickle_pure_python | 300 us                                                 | 212 us: 1.42x faster                                  |
| json_dumps           | 13.5 ms                                                | 9.99 ms: 1.36x faster                                 |
| xml_etree_process    | 74.9 ms                                                | 56.6 ms: 1.32x faster                                 |
| xml_etree_generate   | 94.2 ms                                                | 81.8 ms: 1.15x faster                                 |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                 |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.10x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                  |
| unpickle_list        | 4.82 us                                                | 4.86 us: 1.01x slower                                 |
| pickle_list          | 4.56 us                                                | 4.67 us: 1.02x slower                                 |
| pickle_dict          | 27.3 us                                                | 30.0 us: 1.10x slower                                 |
| Geometric mean       | (ref)                                                  | 1.16x faster                                          |

Benchmark hidden because not significant (2): unpickle, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                 |
| python_startup_no_site | 5.82 ms                                                | 6.81 ms: 1.17x slower                                 |
| Geometric mean         | (ref)                                                  | 1.10x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.37x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-linux-x86_64-python-main-3.13.0a0-0553fdf |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 140 us: 3.64x faster                                  |
| generators               | 76.8 ms                                                | 29.3 ms: 2.62x faster                                 |
| deltablue                | 7.42 ms                                                | 3.24 ms: 2.29x faster                                 |
| asyncio_tcp              | 925 ms                                                 | 488 ms: 1.89x faster                                  |
| chaos                    | 106 ms                                                 | 59.6 ms: 1.78x faster                                 |
| crypto_pyaes             | 118 ms                                                 | 68.2 ms: 1.74x faster                                 |
| logging_silent           | 175 ns                                                 | 103 ns: 1.70x faster                                  |
| raytrace                 | 464 ms                                                 | 273 ms: 1.70x faster                                  |
| richards_super           | 90.7 ms                                                | 53.6 ms: 1.69x faster                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                |
| go                       | 229 ms                                                 | 138 ms: 1.66x faster                                  |
| scimark_monte_carlo      | 108 ms                                                 | 65.8 ms: 1.65x faster                                 |
| scimark_sor              | 197 ms                                                 | 120 ms: 1.64x faster                                  |
| async_tree_none          | 717 ms                                                 | 436 ms: 1.64x faster                                  |
| sqlglot_parse            | 2.06 ms                                                | 1.25 ms: 1.64x faster                                 |
| hexiom                   | 9.53 ms                                                | 5.92 ms: 1.61x faster                                 |
| richards                 | 74.9 ms                                                | 46.6 ms: 1.61x faster                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.56 ms: 1.57x faster                                 |
| nbody                    | 142 ms                                                 | 90.6 ms: 1.56x faster                                 |
| pickle_pure_python       | 455 us                                                 | 295 us: 1.54x faster                                  |
| async_tree_memoization   | 854 ms                                                 | 560 ms: 1.52x faster                                  |
| pyflate                  | 673 ms                                                 | 446 ms: 1.51x faster                                  |
| async_tree_io            | 1.77 sec                                               | 1.18 sec: 1.50x faster                                |
| coroutines               | 31.8 ms                                                | 21.5 ms: 1.48x faster                                 |
| scimark_lu               | 163 ms                                                 | 113 ms: 1.45x faster                                  |
| tomli_loads              | 2.92 sec                                               | 2.02 sec: 1.45x faster                                |
| unpack_sequence          | 64.7 ns                                                | 44.9 ns: 1.44x faster                                 |
| spectral_norm            | 150 ms                                                 | 104 ms: 1.44x faster                                  |
| unpickle_pure_python     | 300 us                                                 | 212 us: 1.42x faster                                  |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                 |
| deepcopy_memo            | 52.3 us                                                | 37.1 us: 1.41x faster                                 |
| float                    | 111 ms                                                 | 79.8 ms: 1.39x faster                                 |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.37x faster                                 |
| logging_format           | 8.91 us                                                | 6.53 us: 1.36x faster                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 702 ms: 1.36x faster                                  |
| json_dumps               | 13.5 ms                                                | 9.99 ms: 1.36x faster                                 |
| logging_simple           | 8.07 us                                                | 5.98 us: 1.35x faster                                 |
| tornado_http             | 127 ms                                                 | 94.9 ms: 1.34x faster                                 |
| pprint_pformat           | 1.99 sec                                               | 1.48 sec: 1.34x faster                                |
| xml_etree_process        | 74.9 ms                                                | 56.6 ms: 1.32x faster                                 |
| pprint_safe_repr         | 955 ms                                                 | 722 ms: 1.32x faster                                  |
| regex_compile            | 177 ms                                                 | 134 ms: 1.32x faster                                  |
| sqlglot_normalize        | 135 ms                                                 | 104 ms: 1.30x faster                                  |
| fannkuch                 | 486 ms                                                 | 374 ms: 1.30x faster                                  |
| comprehensions           | 26.8 us                                                | 20.7 us: 1.30x faster                                 |
| nqueens                  | 100 ms                                                 | 78.0 ms: 1.28x faster                                 |
| deepcopy                 | 442 us                                                 | 345 us: 1.28x faster                                  |
| pycparser                | 1.50 sec                                               | 1.18 sec: 1.28x faster                                |
| mypy2                    | 428 ms                                                 | 337 ms: 1.27x faster                                  |
| sqlglot_optimize         | 65.3 ms                                                | 52.2 ms: 1.25x faster                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.11 us: 1.23x faster                                 |
| docutils                 | 3.17 sec                                               | 2.60 sec: 1.22x faster                                |
| scimark_fft              | 424 ms                                                 | 358 ms: 1.18x faster                                  |
| bench_thread_pool        | 947 us                                                 | 807 us: 1.17x faster                                  |
| xml_etree_generate       | 94.2 ms                                                | 81.8 ms: 1.15x faster                                 |
| dulwich_log              | 75.9 ms                                                | 66.4 ms: 1.14x faster                                 |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                 |
| json                     | 5.42 ms                                                | 4.81 ms: 1.12x faster                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.86 ms: 1.12x faster                                 |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.10x faster                                  |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.10x faster                                  |
| mdp                      | 2.82 sec                                               | 2.58 sec: 1.09x faster                                |
| create_gc_cycles         | 1.67 ms                                                | 1.54 ms: 1.09x faster                                 |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                  |
| regex_dna                | 222 ms                                                 | 205 ms: 1.08x faster                                  |
| regex_v8                 | 25.0 ms                                                | 23.4 ms: 1.07x faster                                 |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.07x faster                                 |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                 |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                  |
| unpickle_list            | 4.82 us                                                | 4.86 us: 1.01x slower                                 |
| gc_traversal             | 3.84 ms                                                | 3.90 ms: 1.01x slower                                 |
| pickle_list              | 4.56 us                                                | 4.67 us: 1.02x slower                                 |
| async_generators         | 425 ms                                                 | 439 ms: 1.03x slower                                  |
| regex_effbot             | 3.23 ms                                                | 3.50 ms: 1.09x slower                                 |
| pickle_dict              | 27.3 us                                                | 30.0 us: 1.10x slower                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.81 ms: 1.17x slower                                 |
| coverage                 | 72.8 ms                                                | 86.8 ms: 1.19x slower                                 |
| telco                    | 6.54 ms                                                | 7.92 ms: 1.21x slower                                 |
| dask                     | 423 ms                                                 | 522 ms: 1.23x slower                                  |
| Geometric mean           | (ref)                                                  | 1.31x faster                                          |

Benchmark hidden because not significant (3): unpickle, pickle, bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.25x
