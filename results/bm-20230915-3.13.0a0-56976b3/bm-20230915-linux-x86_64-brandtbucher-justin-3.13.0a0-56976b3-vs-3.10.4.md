
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 56976b3
- commit date: 2023-09-15
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.70 sec: 1.17x faster                                        |
| tornado_http   | 127 ms                                                 | 97.6 ms: 1.31x faster                                         |
| Geometric mean | (ref)                                                  | 1.24x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| float          | 111 ms                                                 | 83.4 ms: 1.33x faster                                         |
| nbody          | 142 ms                                                 | 118 ms: 1.20x faster                                          |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.17x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 150 ms: 1.18x faster                                          |
| regex_dna      | 222 ms                                                 | 208 ms: 1.07x faster                                          |
| regex_v8       | 25.0 ms                                                | 24.2 ms: 1.04x faster                                         |
| regex_effbot   | 3.23 ms                                                | 3.51 ms: 1.09x slower                                         |
| Geometric mean | (ref)                                                  | 1.05x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 309 us: 1.48x faster                                          |
| json_dumps           | 13.5 ms                                                | 9.97 ms: 1.36x faster                                         |
| xml_etree_process    | 74.9 ms                                                | 58.1 ms: 1.29x faster                                         |
| unpickle_pure_python | 300 us                                                 | 233 us: 1.29x faster                                          |
| tomli_loads          | 2.92 sec                                               | 2.34 sec: 1.24x faster                                        |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                         |
| xml_etree_generate   | 94.2 ms                                                | 84.4 ms: 1.12x faster                                         |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                          |
| unpickle_list        | 4.82 us                                                | 4.73 us: 1.02x faster                                         |
| unpickle             | 14.1 us                                                | 14.0 us: 1.01x faster                                         |
| pickle_list          | 4.56 us                                                | 4.70 us: 1.03x slower                                         |
| pickle               | 10.3 us                                                | 10.7 us: 1.04x slower                                         |
| pickle_dict          | 27.3 us                                                | 31.7 us: 1.16x slower                                         |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                         |
| python_startup_no_site | 5.82 ms                                                | 6.87 ms: 1.18x slower                                         |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.3 ms: 1.31x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 159 us: 3.22x faster                                          |
| generators               | 76.8 ms                                                | 28.4 ms: 2.70x faster                                         |
| deltablue                | 7.42 ms                                                | 3.53 ms: 2.10x faster                                         |
| asyncio_tcp              | 925 ms                                                 | 491 ms: 1.88x faster                                          |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                        |
| raytrace                 | 464 ms                                                 | 284 ms: 1.64x faster                                          |
| logging_silent           | 175 ns                                                 | 107 ns: 1.63x faster                                          |
| richards_super           | 90.7 ms                                                | 55.9 ms: 1.62x faster                                         |
| scimark_monte_carlo      | 108 ms                                                 | 67.4 ms: 1.61x faster                                         |
| async_tree_none          | 717 ms                                                 | 449 ms: 1.60x faster                                          |
| sqlglot_parse            | 2.06 ms                                                | 1.30 ms: 1.59x faster                                         |
| scimark_sor              | 197 ms                                                 | 125 ms: 1.57x faster                                          |
| crypto_pyaes             | 118 ms                                                 | 75.6 ms: 1.57x faster                                         |
| richards                 | 74.9 ms                                                | 49.3 ms: 1.52x faster                                         |
| sqlglot_transpile        | 2.45 ms                                                | 1.62 ms: 1.51x faster                                         |
| go                       | 229 ms                                                 | 154 ms: 1.49x faster                                          |
| async_tree_memoization   | 854 ms                                                 | 579 ms: 1.48x faster                                          |
| pickle_pure_python       | 455 us                                                 | 309 us: 1.48x faster                                          |
| async_tree_io            | 1.77 sec                                               | 1.21 sec: 1.46x faster                                        |
| coroutines               | 31.8 ms                                                | 22.6 ms: 1.41x faster                                         |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                         |
| scimark_lu               | 163 ms                                                 | 117 ms: 1.39x faster                                          |
| spectral_norm            | 150 ms                                                 | 110 ms: 1.37x faster                                          |
| json_dumps               | 13.5 ms                                                | 9.97 ms: 1.36x faster                                         |
| pyflate                  | 673 ms                                                 | 500 ms: 1.34x faster                                          |
| chaos                    | 106 ms                                                 | 80.0 ms: 1.33x faster                                         |
| float                    | 111 ms                                                 | 83.4 ms: 1.33x faster                                         |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 718 ms: 1.32x faster                                          |
| mako                     | 14.8 ms                                                | 11.3 ms: 1.31x faster                                         |
| tornado_http             | 127 ms                                                 | 97.6 ms: 1.31x faster                                         |
| logging_format           | 8.91 us                                                | 6.86 us: 1.30x faster                                         |
| logging_simple           | 8.07 us                                                | 6.22 us: 1.30x faster                                         |
| xml_etree_process        | 74.9 ms                                                | 58.1 ms: 1.29x faster                                         |
| unpickle_pure_python     | 300 us                                                 | 233 us: 1.29x faster                                          |
| hexiom                   | 9.53 ms                                                | 7.53 ms: 1.26x faster                                         |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.25x faster                                          |
| pycparser                | 1.50 sec                                               | 1.20 sec: 1.25x faster                                        |
| tomli_loads              | 2.92 sec                                               | 2.34 sec: 1.24x faster                                        |
| pprint_pformat           | 1.99 sec                                               | 1.64 sec: 1.21x faster                                        |
| sqlglot_optimize         | 65.3 ms                                                | 54.0 ms: 1.21x faster                                         |
| mypy2                    | 428 ms                                                 | 356 ms: 1.20x faster                                          |
| nbody                    | 142 ms                                                 | 118 ms: 1.20x faster                                          |
| pprint_safe_repr         | 955 ms                                                 | 797 ms: 1.20x faster                                          |
| regex_compile            | 177 ms                                                 | 150 ms: 1.18x faster                                          |
| unpack_sequence          | 64.7 ns                                                | 54.7 ns: 1.18x faster                                         |
| docutils                 | 3.17 sec                                               | 2.70 sec: 1.17x faster                                        |
| deepcopy_reduce          | 3.82 us                                                | 3.30 us: 1.16x faster                                         |
| deepcopy_memo            | 52.3 us                                                | 45.1 us: 1.16x faster                                         |
| deepcopy                 | 442 us                                                 | 382 us: 1.16x faster                                          |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                         |
| json                     | 5.42 ms                                                | 4.83 ms: 1.12x faster                                         |
| xml_etree_generate       | 94.2 ms                                                | 84.4 ms: 1.12x faster                                         |
| scimark_fft              | 424 ms                                                 | 381 ms: 1.11x faster                                          |
| bench_thread_pool        | 947 us                                                 | 854 us: 1.11x faster                                          |
| comprehensions           | 26.8 us                                                | 24.3 us: 1.11x faster                                         |
| create_gc_cycles         | 1.67 ms                                                | 1.52 ms: 1.10x faster                                         |
| dulwich_log              | 75.9 ms                                                | 69.5 ms: 1.09x faster                                         |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.02 ms: 1.09x faster                                         |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                          |
| gc_traversal             | 3.84 ms                                                | 3.57 ms: 1.08x faster                                         |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                         |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                          |
| fannkuch                 | 486 ms                                                 | 455 ms: 1.07x faster                                          |
| regex_dna                | 222 ms                                                 | 208 ms: 1.07x faster                                          |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.05x faster                                         |
| regex_v8                 | 25.0 ms                                                | 24.2 ms: 1.04x faster                                         |
| meteor_contest           | 115 ms                                                 | 113 ms: 1.02x faster                                          |
| unpickle_list            | 4.82 us                                                | 4.73 us: 1.02x faster                                         |
| unpickle                 | 14.1 us                                                | 14.0 us: 1.01x faster                                         |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                          |
| mdp                      | 2.82 sec                                               | 2.83 sec: 1.00x slower                                        |
| pickle_list              | 4.56 us                                                | 4.70 us: 1.03x slower                                         |
| nqueens                  | 100 ms                                                 | 104 ms: 1.04x slower                                          |
| pickle                   | 10.3 us                                                | 10.7 us: 1.04x slower                                         |
| regex_effbot             | 3.23 ms                                                | 3.51 ms: 1.09x slower                                         |
| async_generators         | 425 ms                                                 | 468 ms: 1.10x slower                                          |
| pickle_dict              | 27.3 us                                                | 31.7 us: 1.16x slower                                         |
| coverage                 | 72.8 ms                                                | 84.8 ms: 1.16x slower                                         |
| python_startup_no_site   | 5.82 ms                                                | 6.87 ms: 1.18x slower                                         |
| telco                    | 6.54 ms                                                | 8.08 ms: 1.23x slower                                         |
| dask                     | 423 ms                                                 | 538 ms: 1.27x slower                                          |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                  |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
