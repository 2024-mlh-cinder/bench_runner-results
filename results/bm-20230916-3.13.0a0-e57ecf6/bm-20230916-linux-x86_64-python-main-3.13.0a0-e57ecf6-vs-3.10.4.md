
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.31x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.62 sec: 1.21x faster                                |
| tornado_http   | 127 ms                                                 | 95.0 ms: 1.34x faster                                 |
| Geometric mean | (ref)                                                  | 1.27x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 142 ms                                                 | 88.0 ms: 1.61x faster                                 |
| float          | 111 ms                                                 | 78.7 ms: 1.40x faster                                 |
| pidigits       | 190 ms                                                 | 203 ms: 1.07x slower                                  |
| Geometric mean | (ref)                                                  | 1.28x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 134 ms: 1.32x faster                                  |
| regex_dna      | 222 ms                                                 | 205 ms: 1.08x faster                                  |
| regex_v8       | 25.0 ms                                                | 23.3 ms: 1.08x faster                                 |
| regex_effbot   | 3.23 ms                                                | 3.45 ms: 1.07x slower                                 |
| Geometric mean | (ref)                                                  | 1.09x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 296 us: 1.54x faster                                  |
| unpickle_pure_python | 300 us                                                 | 211 us: 1.42x faster                                  |
| json_dumps           | 13.5 ms                                                | 9.81 ms: 1.38x faster                                 |
| tomli_loads          | 2.92 sec                                               | 2.12 sec: 1.38x faster                                |
| xml_etree_process    | 74.9 ms                                                | 56.8 ms: 1.32x faster                                 |
| xml_etree_generate   | 94.2 ms                                                | 82.3 ms: 1.14x faster                                 |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                 |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.10x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.08x faster                                  |
| unpickle             | 14.1 us                                                | 14.2 us: 1.00x slower                                 |
| pickle               | 10.3 us                                                | 10.7 us: 1.04x slower                                 |
| pickle_list          | 4.56 us                                                | 4.85 us: 1.07x slower                                 |
| pickle_dict          | 27.3 us                                                | 32.4 us: 1.19x slower                                 |
| Geometric mean       | (ref)                                                  | 1.14x faster                                          |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                 |
| python_startup_no_site | 5.82 ms                                                | 6.83 ms: 1.17x slower                                 |
| Geometric mean         | (ref)                                                  | 1.10x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.5 ms: 1.41x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 141 us: 3.63x faster                                  |
| generators               | 76.8 ms                                                | 27.9 ms: 2.75x faster                                 |
| deltablue                | 7.42 ms                                                | 3.32 ms: 2.23x faster                                 |
| asyncio_tcp              | 925 ms                                                 | 490 ms: 1.89x faster                                  |
| chaos                    | 106 ms                                                 | 59.4 ms: 1.79x faster                                 |
| logging_silent           | 175 ns                                                 | 98.5 ns: 1.78x faster                                 |
| raytrace                 | 464 ms                                                 | 266 ms: 1.74x faster                                  |
| crypto_pyaes             | 118 ms                                                 | 69.8 ms: 1.70x faster                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                |
| richards_super           | 90.7 ms                                                | 54.4 ms: 1.67x faster                                 |
| async_tree_none          | 717 ms                                                 | 437 ms: 1.64x faster                                  |
| go                       | 229 ms                                                 | 140 ms: 1.64x faster                                  |
| scimark_monte_carlo      | 108 ms                                                 | 66.6 ms: 1.63x faster                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.27 ms: 1.62x faster                                 |
| nbody                    | 142 ms                                                 | 88.0 ms: 1.61x faster                                 |
| hexiom                   | 9.53 ms                                                | 5.93 ms: 1.61x faster                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.58 ms: 1.55x faster                                 |
| richards                 | 74.9 ms                                                | 48.4 ms: 1.55x faster                                 |
| unpack_sequence          | 64.7 ns                                                | 41.9 ns: 1.55x faster                                 |
| pickle_pure_python       | 455 us                                                 | 296 us: 1.54x faster                                  |
| scimark_sor              | 197 ms                                                 | 129 ms: 1.53x faster                                  |
| async_tree_memoization   | 854 ms                                                 | 562 ms: 1.52x faster                                  |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                |
| pyflate                  | 673 ms                                                 | 453 ms: 1.49x faster                                  |
| scimark_lu               | 163 ms                                                 | 110 ms: 1.48x faster                                  |
| deepcopy_memo            | 52.3 us                                                | 36.4 us: 1.44x faster                                 |
| coroutines               | 31.8 ms                                                | 22.4 ms: 1.42x faster                                 |
| unpickle_pure_python     | 300 us                                                 | 211 us: 1.42x faster                                  |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                 |
| mako                     | 14.8 ms                                                | 10.5 ms: 1.41x faster                                 |
| float                    | 111 ms                                                 | 78.7 ms: 1.40x faster                                 |
| spectral_norm            | 150 ms                                                 | 107 ms: 1.40x faster                                  |
| json_dumps               | 13.5 ms                                                | 9.81 ms: 1.38x faster                                 |
| tomli_loads              | 2.92 sec                                               | 2.12 sec: 1.38x faster                                |
| pprint_pformat           | 1.99 sec                                               | 1.46 sec: 1.36x faster                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 700 ms: 1.36x faster                                  |
| tornado_http             | 127 ms                                                 | 95.0 ms: 1.34x faster                                 |
| logging_format           | 8.91 us                                                | 6.69 us: 1.33x faster                                 |
| pprint_safe_repr         | 955 ms                                                 | 718 ms: 1.33x faster                                  |
| logging_simple           | 8.07 us                                                | 6.10 us: 1.32x faster                                 |
| xml_etree_process        | 74.9 ms                                                | 56.8 ms: 1.32x faster                                 |
| regex_compile            | 177 ms                                                 | 134 ms: 1.32x faster                                  |
| comprehensions           | 26.8 us                                                | 20.4 us: 1.31x faster                                 |
| pycparser                | 1.50 sec                                               | 1.14 sec: 1.31x faster                                |
| sqlglot_normalize        | 135 ms                                                 | 105 ms: 1.29x faster                                  |
| deepcopy                 | 442 us                                                 | 345 us: 1.28x faster                                  |
| nqueens                  | 100 ms                                                 | 78.2 ms: 1.28x faster                                 |
| mypy2                    | 428 ms                                                 | 337 ms: 1.27x faster                                  |
| fannkuch                 | 486 ms                                                 | 382 ms: 1.27x faster                                  |
| sqlglot_optimize         | 65.3 ms                                                | 52.8 ms: 1.24x faster                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.12 us: 1.23x faster                                 |
| docutils                 | 3.17 sec                                               | 2.62 sec: 1.21x faster                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.54 ms: 1.20x faster                                 |
| scimark_fft              | 424 ms                                                 | 359 ms: 1.18x faster                                  |
| bench_thread_pool        | 947 us                                                 | 806 us: 1.18x faster                                  |
| xml_etree_generate       | 94.2 ms                                                | 82.3 ms: 1.14x faster                                 |
| dulwich_log              | 75.9 ms                                                | 66.6 ms: 1.14x faster                                 |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                 |
| json                     | 5.42 ms                                                | 4.83 ms: 1.12x faster                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.52 ms: 1.10x faster                                 |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.10x faster                                  |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.09x faster                                  |
| pathlib                  | 20.0 ms                                                | 18.4 ms: 1.09x faster                                 |
| regex_dna                | 222 ms                                                 | 205 ms: 1.08x faster                                  |
| regex_v8                 | 25.0 ms                                                | 23.3 ms: 1.08x faster                                 |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.08x faster                                  |
| sqlite_synth             | 2.93 us                                                | 2.73 us: 1.08x faster                                 |
| mdp                      | 2.82 sec                                               | 2.63 sec: 1.07x faster                                |
| unpickle                 | 14.1 us                                                | 14.2 us: 1.00x slower                                 |
| pickle                   | 10.3 us                                                | 10.7 us: 1.04x slower                                 |
| async_generators         | 425 ms                                                 | 445 ms: 1.05x slower                                  |
| pickle_list              | 4.56 us                                                | 4.85 us: 1.07x slower                                 |
| regex_effbot             | 3.23 ms                                                | 3.45 ms: 1.07x slower                                 |
| pidigits                 | 190 ms                                                 | 203 ms: 1.07x slower                                  |
| gc_traversal             | 3.84 ms                                                | 4.12 ms: 1.07x slower                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.83 ms: 1.17x slower                                 |
| pickle_dict              | 27.3 us                                                | 32.4 us: 1.19x slower                                 |
| coverage                 | 72.8 ms                                                | 86.7 ms: 1.19x slower                                 |
| telco                    | 6.54 ms                                                | 7.98 ms: 1.22x slower                                 |
| dask                     | 423 ms                                                 | 529 ms: 1.25x slower                                  |
| Geometric mean           | (ref)                                                  | 1.31x faster                                          |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle_list
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.24x
