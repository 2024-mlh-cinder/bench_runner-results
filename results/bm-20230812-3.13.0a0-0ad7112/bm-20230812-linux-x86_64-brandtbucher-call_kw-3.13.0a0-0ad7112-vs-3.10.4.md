
# Results vs. 3.10.4

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 0ad7112
- commit date: 2023-08-12
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.63 sec: 1.21x faster                                         |
| tornado_http   | 127 ms                                                 | 95.7 ms: 1.33x faster                                          |
| Geometric mean | (ref)                                                  | 1.27x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.6 ms: 1.55x faster                                          |
| float          | 111 ms                                                 | 80.2 ms: 1.38x faster                                          |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                  | 1.27x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 135 ms: 1.31x faster                                           |
| regex_v8       | 25.0 ms                                                | 25.1 ms: 1.00x slower                                          |
| regex_dna      | 222 ms                                                 | 227 ms: 1.02x slower                                           |
| regex_effbot   | 3.23 ms                                                | 3.57 ms: 1.11x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 303 us: 1.51x faster                                           |
| unpickle_pure_python | 300 us                                                 | 213 us: 1.41x faster                                           |
| tomli_loads          | 2.92 sec                                               | 2.11 sec: 1.39x faster                                         |
| json_dumps           | 13.5 ms                                                | 9.78 ms: 1.38x faster                                          |
| xml_etree_process    | 74.9 ms                                                | 56.7 ms: 1.32x faster                                          |
| json_loads           | 28.8 us                                                | 25.2 us: 1.14x faster                                          |
| xml_etree_generate   | 94.2 ms                                                | 82.5 ms: 1.14x faster                                          |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                           |
| unpickle_list        | 4.82 us                                                | 4.85 us: 1.01x slower                                          |
| pickle_list          | 4.56 us                                                | 4.75 us: 1.04x slower                                          |
| pickle               | 10.3 us                                                | 10.9 us: 1.05x slower                                          |
| unpickle             | 14.1 us                                                | 15.2 us: 1.07x slower                                          |
| pickle_dict          | 27.3 us                                                | 32.2 us: 1.18x slower                                          |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.56 ms: 1.48x faster                                          |
| python_startup_no_site | 5.82 ms                                                | 7.00 ms: 1.20x slower                                          |
| Geometric mean         | (ref)                                                  | 1.11x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.9 ms: 1.35x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 142 us: 3.59x faster                                           |
| generators               | 76.8 ms                                                | 29.0 ms: 2.64x faster                                          |
| deltablue                | 7.42 ms                                                | 3.28 ms: 2.26x faster                                          |
| asyncio_tcp              | 925 ms                                                 | 485 ms: 1.91x faster                                           |
| chaos                    | 106 ms                                                 | 59.5 ms: 1.79x faster                                          |
| crypto_pyaes             | 118 ms                                                 | 67.8 ms: 1.75x faster                                          |
| logging_silent           | 175 ns                                                 | 102 ns: 1.72x faster                                           |
| richards_super           | 90.7 ms                                                | 53.3 ms: 1.70x faster                                          |
| raytrace                 | 464 ms                                                 | 275 ms: 1.68x faster                                           |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                         |
| scimark_sor              | 197 ms                                                 | 119 ms: 1.66x faster                                           |
| go                       | 229 ms                                                 | 140 ms: 1.64x faster                                           |
| async_tree_none          | 717 ms                                                 | 437 ms: 1.64x faster                                           |
| sqlglot_parse            | 2.06 ms                                                | 1.26 ms: 1.63x faster                                          |
| scimark_monte_carlo      | 108 ms                                                 | 66.9 ms: 1.62x faster                                          |
| hexiom                   | 9.53 ms                                                | 5.90 ms: 1.61x faster                                          |
| richards                 | 74.9 ms                                                | 47.1 ms: 1.59x faster                                          |
| sqlglot_transpile        | 2.45 ms                                                | 1.57 ms: 1.56x faster                                          |
| nbody                    | 142 ms                                                 | 91.6 ms: 1.55x faster                                          |
| async_tree_memoization   | 854 ms                                                 | 566 ms: 1.51x faster                                           |
| pyflate                  | 673 ms                                                 | 446 ms: 1.51x faster                                           |
| pickle_pure_python       | 455 us                                                 | 303 us: 1.51x faster                                           |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                         |
| python_startup           | 14.2 ms                                                | 9.56 ms: 1.48x faster                                          |
| scimark_lu               | 163 ms                                                 | 110 ms: 1.48x faster                                           |
| spectral_norm            | 150 ms                                                 | 104 ms: 1.45x faster                                           |
| unpickle_pure_python     | 300 us                                                 | 213 us: 1.41x faster                                           |
| deepcopy_memo            | 52.3 us                                                | 37.4 us: 1.40x faster                                          |
| tomli_loads              | 2.92 sec                                               | 2.11 sec: 1.39x faster                                         |
| json_dumps               | 13.5 ms                                                | 9.78 ms: 1.38x faster                                          |
| logging_format           | 8.91 us                                                | 6.44 us: 1.38x faster                                          |
| float                    | 111 ms                                                 | 80.2 ms: 1.38x faster                                          |
| coroutines               | 31.8 ms                                                | 23.2 ms: 1.37x faster                                          |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 701 ms: 1.36x faster                                           |
| pprint_pformat           | 1.99 sec                                               | 1.47 sec: 1.35x faster                                         |
| mako                     | 14.8 ms                                                | 10.9 ms: 1.35x faster                                          |
| logging_simple           | 8.07 us                                                | 5.99 us: 1.35x faster                                          |
| tornado_http             | 127 ms                                                 | 95.7 ms: 1.33x faster                                          |
| unpack_sequence          | 64.7 ns                                                | 48.7 ns: 1.33x faster                                          |
| pprint_safe_repr         | 955 ms                                                 | 721 ms: 1.32x faster                                           |
| xml_etree_process        | 74.9 ms                                                | 56.7 ms: 1.32x faster                                          |
| sqlglot_normalize        | 135 ms                                                 | 103 ms: 1.32x faster                                           |
| regex_compile            | 177 ms                                                 | 135 ms: 1.31x faster                                           |
| comprehensions           | 26.8 us                                                | 20.8 us: 1.29x faster                                          |
| fannkuch                 | 486 ms                                                 | 382 ms: 1.27x faster                                           |
| deepcopy                 | 442 us                                                 | 348 us: 1.27x faster                                           |
| mypy2                    | 428 ms                                                 | 339 ms: 1.26x faster                                           |
| sqlglot_optimize         | 65.3 ms                                                | 52.0 ms: 1.26x faster                                          |
| nqueens                  | 100 ms                                                 | 79.6 ms: 1.26x faster                                          |
| pycparser                | 1.50 sec                                               | 1.20 sec: 1.25x faster                                         |
| deepcopy_reduce          | 3.82 us                                                | 3.14 us: 1.22x faster                                          |
| docutils                 | 3.17 sec                                               | 2.63 sec: 1.21x faster                                         |
| scimark_fft              | 424 ms                                                 | 355 ms: 1.19x faster                                           |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.62 ms: 1.18x faster                                          |
| bench_thread_pool        | 947 us                                                 | 814 us: 1.16x faster                                           |
| json_loads               | 28.8 us                                                | 25.2 us: 1.14x faster                                          |
| xml_etree_generate       | 94.2 ms                                                | 82.5 ms: 1.14x faster                                          |
| dulwich_log              | 75.9 ms                                                | 67.0 ms: 1.13x faster                                          |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                          |
| json                     | 5.42 ms                                                | 4.93 ms: 1.10x faster                                          |
| mdp                      | 2.82 sec                                               | 2.57 sec: 1.10x faster                                         |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                           |
| meteor_contest           | 115 ms                                                 | 107 ms: 1.08x faster                                           |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                           |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                          |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                          |
| regex_v8                 | 25.0 ms                                                | 25.1 ms: 1.00x slower                                          |
| unpickle_list            | 4.82 us                                                | 4.85 us: 1.01x slower                                          |
| regex_dna                | 222 ms                                                 | 227 ms: 1.02x slower                                           |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| pickle_list              | 4.56 us                                                | 4.75 us: 1.04x slower                                          |
| pickle                   | 10.3 us                                                | 10.9 us: 1.05x slower                                          |
| async_generators         | 425 ms                                                 | 451 ms: 1.06x slower                                           |
| unpickle                 | 14.1 us                                                | 15.2 us: 1.07x slower                                          |
| regex_effbot             | 3.23 ms                                                | 3.57 ms: 1.11x slower                                          |
| gc_traversal             | 3.84 ms                                                | 4.31 ms: 1.12x slower                                          |
| pickle_dict              | 27.3 us                                                | 32.2 us: 1.18x slower                                          |
| coverage                 | 72.8 ms                                                | 86.7 ms: 1.19x slower                                          |
| python_startup_no_site   | 5.82 ms                                                | 7.00 ms: 1.20x slower                                          |
| telco                    | 6.54 ms                                                | 7.91 ms: 1.21x slower                                          |
| dask                     | 423 ms                                                 | 525 ms: 1.24x slower                                           |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                   |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.23x
