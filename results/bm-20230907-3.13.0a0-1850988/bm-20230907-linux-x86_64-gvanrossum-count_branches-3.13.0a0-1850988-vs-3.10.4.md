
# Results vs. 3.10.4

- fork: gvanrossum
- ref: count_branches
- machine: linux-x86_64
- commit hash: 1850988
- commit date: 2023-09-07
- overall geometric mean: 1.31x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.63 sec: 1.21x faster                                              |
| tornado_http   | 127 ms                                                 | 95.2 ms: 1.34x faster                                               |
| Geometric mean | (ref)                                                  | 1.27x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 88.1 ms: 1.61x faster                                               |
| float          | 111 ms                                                 | 79.3 ms: 1.39x faster                                               |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                |
| Geometric mean | (ref)                                                  | 1.32x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 134 ms: 1.32x faster                                                |
| regex_dna      | 222 ms                                                 | 224 ms: 1.01x slower                                                |
| regex_v8       | 25.0 ms                                                | 25.5 ms: 1.02x slower                                               |
| regex_effbot   | 3.23 ms                                                | 3.85 ms: 1.19x slower                                               |
| Geometric mean | (ref)                                                  | 1.02x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 292 us: 1.56x faster                                                |
| tomli_loads          | 2.92 sec                                               | 2.02 sec: 1.45x faster                                              |
| unpickle_pure_python | 300 us                                                 | 218 us: 1.38x faster                                                |
| json_dumps           | 13.5 ms                                                | 9.82 ms: 1.38x faster                                               |
| xml_etree_process    | 74.9 ms                                                | 56.2 ms: 1.33x faster                                               |
| xml_etree_generate   | 94.2 ms                                                | 81.8 ms: 1.15x faster                                               |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                               |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                                |
| unpickle             | 14.1 us                                                | 14.3 us: 1.01x slower                                               |
| unpickle_list        | 4.82 us                                                | 4.86 us: 1.01x slower                                               |
| pickle_list          | 4.56 us                                                | 4.68 us: 1.03x slower                                               |
| pickle               | 10.3 us                                                | 10.6 us: 1.03x slower                                               |
| pickle_dict          | 27.3 us                                                | 32.0 us: 1.17x slower                                               |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.57 ms: 1.48x faster                                               |
| python_startup_no_site | 5.82 ms                                                | 7.04 ms: 1.21x slower                                               |
| Geometric mean         | (ref)                                                  | 1.11x faster                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.7 ms: 1.38x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 149 us: 3.42x faster                                                |
| generators               | 76.8 ms                                                | 29.1 ms: 2.64x faster                                               |
| deltablue                | 7.42 ms                                                | 3.29 ms: 2.25x faster                                               |
| asyncio_tcp              | 925 ms                                                 | 490 ms: 1.89x faster                                                |
| chaos                    | 106 ms                                                 | 58.6 ms: 1.81x faster                                               |
| logging_silent           | 175 ns                                                 | 101 ns: 1.74x faster                                                |
| raytrace                 | 464 ms                                                 | 271 ms: 1.71x faster                                                |
| crypto_pyaes             | 118 ms                                                 | 70.0 ms: 1.69x faster                                               |
| richards_super           | 90.7 ms                                                | 53.9 ms: 1.68x faster                                               |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                              |
| go                       | 229 ms                                                 | 139 ms: 1.65x faster                                                |
| sqlglot_parse            | 2.06 ms                                                | 1.26 ms: 1.63x faster                                               |
| async_tree_none          | 717 ms                                                 | 440 ms: 1.63x faster                                                |
| scimark_monte_carlo      | 108 ms                                                 | 66.5 ms: 1.63x faster                                               |
| unpack_sequence          | 64.7 ns                                                | 39.8 ns: 1.63x faster                                               |
| scimark_sor              | 197 ms                                                 | 121 ms: 1.62x faster                                                |
| hexiom                   | 9.53 ms                                                | 5.89 ms: 1.62x faster                                               |
| nbody                    | 142 ms                                                 | 88.1 ms: 1.61x faster                                               |
| richards                 | 74.9 ms                                                | 46.7 ms: 1.61x faster                                               |
| sqlglot_transpile        | 2.45 ms                                                | 1.56 ms: 1.56x faster                                               |
| pickle_pure_python       | 455 us                                                 | 292 us: 1.56x faster                                                |
| async_tree_memoization   | 854 ms                                                 | 569 ms: 1.50x faster                                                |
| pyflate                  | 673 ms                                                 | 449 ms: 1.50x faster                                                |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                              |
| python_startup           | 14.2 ms                                                | 9.57 ms: 1.48x faster                                               |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.46x faster                                                |
| tomli_loads              | 2.92 sec                                               | 2.02 sec: 1.45x faster                                              |
| coroutines               | 31.8 ms                                                | 22.0 ms: 1.44x faster                                               |
| spectral_norm            | 150 ms                                                 | 104 ms: 1.44x faster                                                |
| logging_format           | 8.91 us                                                | 6.37 us: 1.40x faster                                               |
| float                    | 111 ms                                                 | 79.3 ms: 1.39x faster                                               |
| logging_simple           | 8.07 us                                                | 5.80 us: 1.39x faster                                               |
| deepcopy_memo            | 52.3 us                                                | 37.7 us: 1.39x faster                                               |
| unpickle_pure_python     | 300 us                                                 | 218 us: 1.38x faster                                                |
| json_dumps               | 13.5 ms                                                | 9.82 ms: 1.38x faster                                               |
| mako                     | 14.8 ms                                                | 10.7 ms: 1.38x faster                                               |
| pprint_pformat           | 1.99 sec                                               | 1.47 sec: 1.35x faster                                              |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 704 ms: 1.35x faster                                                |
| tornado_http             | 127 ms                                                 | 95.2 ms: 1.34x faster                                               |
| xml_etree_process        | 74.9 ms                                                | 56.2 ms: 1.33x faster                                               |
| pprint_safe_repr         | 955 ms                                                 | 719 ms: 1.33x faster                                                |
| regex_compile            | 177 ms                                                 | 134 ms: 1.32x faster                                                |
| sqlglot_normalize        | 135 ms                                                 | 104 ms: 1.31x faster                                                |
| comprehensions           | 26.8 us                                                | 20.6 us: 1.30x faster                                               |
| deepcopy                 | 442 us                                                 | 346 us: 1.28x faster                                                |
| nqueens                  | 100 ms                                                 | 78.4 ms: 1.28x faster                                               |
| mypy2                    | 428 ms                                                 | 336 ms: 1.27x faster                                                |
| fannkuch                 | 486 ms                                                 | 383 ms: 1.27x faster                                                |
| sqlglot_optimize         | 65.3 ms                                                | 52.2 ms: 1.25x faster                                               |
| pycparser                | 1.50 sec                                               | 1.20 sec: 1.25x faster                                              |
| deepcopy_reduce          | 3.82 us                                                | 3.08 us: 1.24x faster                                               |
| docutils                 | 3.17 sec                                               | 2.63 sec: 1.21x faster                                              |
| scimark_fft              | 424 ms                                                 | 358 ms: 1.18x faster                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.63 ms: 1.18x faster                                               |
| bench_thread_pool        | 947 us                                                 | 812 us: 1.17x faster                                                |
| xml_etree_generate       | 94.2 ms                                                | 81.8 ms: 1.15x faster                                               |
| dulwich_log              | 75.9 ms                                                | 66.2 ms: 1.15x faster                                               |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                               |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                               |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                |
| pathlib                  | 20.0 ms                                                | 18.4 ms: 1.09x faster                                               |
| json                     | 5.42 ms                                                | 5.01 ms: 1.08x faster                                               |
| sqlite_synth             | 2.93 us                                                | 2.72 us: 1.08x faster                                               |
| meteor_contest           | 115 ms                                                 | 107 ms: 1.08x faster                                                |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                                |
| mdp                      | 2.82 sec                                               | 2.73 sec: 1.04x faster                                              |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                                |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                               |
| unpickle                 | 14.1 us                                                | 14.3 us: 1.01x slower                                               |
| unpickle_list            | 4.82 us                                                | 4.86 us: 1.01x slower                                               |
| regex_dna                | 222 ms                                                 | 224 ms: 1.01x slower                                                |
| regex_v8                 | 25.0 ms                                                | 25.5 ms: 1.02x slower                                               |
| pickle_list              | 4.56 us                                                | 4.68 us: 1.03x slower                                               |
| pickle                   | 10.3 us                                                | 10.6 us: 1.03x slower                                               |
| async_generators         | 425 ms                                                 | 443 ms: 1.04x slower                                                |
| coverage                 | 72.8 ms                                                | 85.3 ms: 1.17x slower                                               |
| pickle_dict              | 27.3 us                                                | 32.0 us: 1.17x slower                                               |
| regex_effbot             | 3.23 ms                                                | 3.85 ms: 1.19x slower                                               |
| python_startup_no_site   | 5.82 ms                                                | 7.04 ms: 1.21x slower                                               |
| telco                    | 6.54 ms                                                | 7.94 ms: 1.21x slower                                               |
| dask                     | 423 ms                                                 | 521 ms: 1.23x slower                                                |
| Geometric mean           | (ref)                                                  | 1.31x faster                                                        |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.23x
