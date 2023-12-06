
# Results vs. 3.10.4

- fork: python
- ref: fbfec5642edd9d7690bb
- machine: linux-x86_64
- commit hash: fbfec56
- commit date: 2023-09-26
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.62 sec: 1.21x faster                                                |
| tornado_http   | 127 ms                                                 | 95.7 ms: 1.33x faster                                                 |
| Geometric mean | (ref)                                                  | 1.27x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 90.8 ms: 1.56x faster                                                 |
| float          | 111 ms                                                 | 79.5 ms: 1.39x faster                                                 |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                  |
| Geometric mean | (ref)                                                  | 1.30x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 134 ms: 1.32x faster                                                  |
| regex_dna      | 222 ms                                                 | 212 ms: 1.05x faster                                                  |
| regex_v8       | 25.0 ms                                                | 24.3 ms: 1.03x faster                                                 |
| regex_effbot   | 3.23 ms                                                | 3.52 ms: 1.09x slower                                                 |
| Geometric mean | (ref)                                                  | 1.07x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 295 us: 1.54x faster                                                  |
| tomli_loads          | 2.92 sec                                               | 2.06 sec: 1.42x faster                                                |
| unpickle_pure_python | 300 us                                                 | 214 us: 1.40x faster                                                  |
| json_dumps           | 13.5 ms                                                | 9.88 ms: 1.37x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 59.2 ms: 1.27x faster                                                 |
| json_loads           | 28.8 us                                                | 25.2 us: 1.15x faster                                                 |
| xml_etree_generate   | 94.2 ms                                                | 86.5 ms: 1.09x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.09x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 155 ms: 1.05x faster                                                  |
| unpickle_list        | 4.82 us                                                | 4.77 us: 1.01x faster                                                 |
| pickle_list          | 4.56 us                                                | 4.59 us: 1.01x slower                                                 |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                                 |
| unpickle             | 14.1 us                                                | 14.9 us: 1.05x slower                                                 |
| pickle_dict          | 27.3 us                                                | 33.3 us: 1.22x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                 |
| python_startup_no_site | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.9 ms: 1.35x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 142 us: 3.60x faster                                                  |
| generators               | 76.8 ms                                                | 29.9 ms: 2.57x faster                                                 |
| deltablue                | 7.42 ms                                                | 3.29 ms: 2.25x faster                                                 |
| asyncio_tcp              | 925 ms                                                 | 507 ms: 1.83x faster                                                  |
| chaos                    | 106 ms                                                 | 60.5 ms: 1.76x faster                                                 |
| raytrace                 | 464 ms                                                 | 266 ms: 1.74x faster                                                  |
| logging_silent           | 175 ns                                                 | 102 ns: 1.72x faster                                                  |
| crypto_pyaes             | 118 ms                                                 | 70.1 ms: 1.69x faster                                                 |
| scimark_sor              | 197 ms                                                 | 118 ms: 1.67x faster                                                  |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                                |
| scimark_monte_carlo      | 108 ms                                                 | 65.6 ms: 1.65x faster                                                 |
| go                       | 229 ms                                                 | 139 ms: 1.65x faster                                                  |
| richards_super           | 90.7 ms                                                | 55.3 ms: 1.64x faster                                                 |
| async_tree_none          | 717 ms                                                 | 438 ms: 1.64x faster                                                  |
| sqlglot_parse            | 2.06 ms                                                | 1.27 ms: 1.62x faster                                                 |
| hexiom                   | 9.53 ms                                                | 6.00 ms: 1.59x faster                                                 |
| nbody                    | 142 ms                                                 | 90.8 ms: 1.56x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.59 ms: 1.54x faster                                                 |
| pickle_pure_python       | 455 us                                                 | 295 us: 1.54x faster                                                  |
| richards                 | 74.9 ms                                                | 48.8 ms: 1.53x faster                                                 |
| async_tree_memoization   | 854 ms                                                 | 564 ms: 1.52x faster                                                  |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                |
| pyflate                  | 673 ms                                                 | 456 ms: 1.48x faster                                                  |
| scimark_lu               | 163 ms                                                 | 111 ms: 1.47x faster                                                  |
| unpack_sequence          | 64.7 ns                                                | 45.5 ns: 1.42x faster                                                 |
| coroutines               | 31.8 ms                                                | 22.4 ms: 1.42x faster                                                 |
| tomli_loads              | 2.92 sec                                               | 2.06 sec: 1.42x faster                                                |
| spectral_norm            | 150 ms                                                 | 106 ms: 1.41x faster                                                  |
| deepcopy_memo            | 52.3 us                                                | 37.3 us: 1.40x faster                                                 |
| unpickle_pure_python     | 300 us                                                 | 214 us: 1.40x faster                                                  |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                 |
| float                    | 111 ms                                                 | 79.5 ms: 1.39x faster                                                 |
| json_dumps               | 13.5 ms                                                | 9.88 ms: 1.37x faster                                                 |
| mako                     | 14.8 ms                                                | 10.9 ms: 1.35x faster                                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 707 ms: 1.34x faster                                                  |
| pprint_pformat           | 1.99 sec                                               | 1.48 sec: 1.34x faster                                                |
| tornado_http             | 127 ms                                                 | 95.7 ms: 1.33x faster                                                 |
| comprehensions           | 26.8 us                                                | 20.3 us: 1.32x faster                                                 |
| logging_simple           | 8.07 us                                                | 6.12 us: 1.32x faster                                                 |
| pprint_safe_repr         | 955 ms                                                 | 724 ms: 1.32x faster                                                  |
| regex_compile            | 177 ms                                                 | 134 ms: 1.32x faster                                                  |
| logging_format           | 8.91 us                                                | 6.77 us: 1.32x faster                                                 |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.28x faster                                                  |
| nqueens                  | 100 ms                                                 | 78.4 ms: 1.28x faster                                                 |
| mypy2                    | 428 ms                                                 | 338 ms: 1.27x faster                                                  |
| xml_etree_process        | 74.9 ms                                                | 59.2 ms: 1.27x faster                                                 |
| pycparser                | 1.50 sec                                               | 1.19 sec: 1.26x faster                                                |
| deepcopy                 | 442 us                                                 | 352 us: 1.26x faster                                                  |
| fannkuch                 | 486 ms                                                 | 388 ms: 1.25x faster                                                  |
| sqlglot_optimize         | 65.3 ms                                                | 53.2 ms: 1.23x faster                                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.15 us: 1.21x faster                                                 |
| docutils                 | 3.17 sec                                               | 2.62 sec: 1.21x faster                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.51 ms: 1.21x faster                                                 |
| scimark_fft              | 424 ms                                                 | 358 ms: 1.18x faster                                                  |
| bench_thread_pool        | 947 us                                                 | 808 us: 1.17x faster                                                  |
| json_loads               | 28.8 us                                                | 25.2 us: 1.15x faster                                                 |
| dulwich_log              | 75.9 ms                                                | 66.3 ms: 1.14x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 86.5 ms: 1.09x faster                                                 |
| json                     | 5.42 ms                                                | 4.98 ms: 1.09x faster                                                 |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.09x faster                                                  |
| create_gc_cycles         | 1.67 ms                                                | 1.54 ms: 1.08x faster                                                 |
| meteor_contest           | 115 ms                                                 | 107 ms: 1.08x faster                                                  |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                                 |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                                 |
| mdp                      | 2.82 sec                                               | 2.64 sec: 1.07x faster                                                |
| xml_etree_parse          | 163 ms                                                 | 155 ms: 1.05x faster                                                  |
| regex_dna                | 222 ms                                                 | 212 ms: 1.05x faster                                                  |
| regex_v8                 | 25.0 ms                                                | 24.3 ms: 1.03x faster                                                 |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                                  |
| unpickle_list            | 4.82 us                                                | 4.77 us: 1.01x faster                                                 |
| pickle_list              | 4.56 us                                                | 4.59 us: 1.01x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 3.98 ms: 1.04x slower                                                 |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                                 |
| unpickle                 | 14.1 us                                                | 14.9 us: 1.05x slower                                                 |
| async_generators         | 425 ms                                                 | 451 ms: 1.06x slower                                                  |
| regex_effbot             | 3.23 ms                                                | 3.52 ms: 1.09x slower                                                 |
| coverage                 | 72.8 ms                                                | 85.7 ms: 1.18x slower                                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                 |
| telco                    | 6.54 ms                                                | 7.99 ms: 1.22x slower                                                 |
| pickle_dict              | 27.3 us                                                | 33.3 us: 1.22x slower                                                 |
| dask                     | 423 ms                                                 | 525 ms: 1.24x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
