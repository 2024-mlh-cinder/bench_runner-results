
# Results vs. 3.10.4

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 53917a5
- commit date: 2023-09-07
- overall geometric mean: 1.31x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.60 sec: 1.22x faster                                         |
| tornado_http   | 127 ms                                                 | 94.7 ms: 1.35x faster                                          |
| Geometric mean | (ref)                                                  | 1.28x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 88.7 ms: 1.60x faster                                          |
| float          | 111 ms                                                 | 78.9 ms: 1.40x faster                                          |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                           |
| Geometric mean | (ref)                                                  | 1.31x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 134 ms: 1.32x faster                                           |
| regex_dna      | 222 ms                                                 | 208 ms: 1.07x faster                                           |
| regex_v8       | 25.0 ms                                                | 23.6 ms: 1.06x faster                                          |
| regex_effbot   | 3.23 ms                                                | 3.47 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                  | 1.09x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 300 us: 1.52x faster                                           |
| tomli_loads          | 2.92 sec                                               | 2.06 sec: 1.42x faster                                         |
| unpickle_pure_python | 300 us                                                 | 216 us: 1.39x faster                                           |
| json_dumps           | 13.5 ms                                                | 9.90 ms: 1.37x faster                                          |
| xml_etree_process    | 74.9 ms                                                | 57.7 ms: 1.30x faster                                          |
| json_loads           | 28.8 us                                                | 25.2 us: 1.14x faster                                          |
| xml_etree_generate   | 94.2 ms                                                | 83.2 ms: 1.13x faster                                          |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.08x faster                                           |
| unpickle             | 14.1 us                                                | 14.6 us: 1.03x slower                                          |
| pickle_list          | 4.56 us                                                | 4.75 us: 1.04x slower                                          |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                          |
| pickle_dict          | 27.3 us                                                | 31.1 us: 1.14x slower                                          |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                   |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                          |
| python_startup_no_site | 5.82 ms                                                | 6.81 ms: 1.17x slower                                          |
| Geometric mean         | (ref)                                                  | 1.10x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.5 ms: 1.41x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 141 us: 3.61x faster                                           |
| generators               | 76.8 ms                                                | 29.3 ms: 2.62x faster                                          |
| deltablue                | 7.42 ms                                                | 3.28 ms: 2.26x faster                                          |
| asyncio_tcp              | 925 ms                                                 | 481 ms: 1.92x faster                                           |
| chaos                    | 106 ms                                                 | 60.4 ms: 1.76x faster                                          |
| logging_silent           | 175 ns                                                 | 101 ns: 1.74x faster                                           |
| crypto_pyaes             | 118 ms                                                 | 68.3 ms: 1.73x faster                                          |
| raytrace                 | 464 ms                                                 | 268 ms: 1.73x faster                                           |
| richards_super           | 90.7 ms                                                | 54.2 ms: 1.67x faster                                          |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                         |
| go                       | 229 ms                                                 | 138 ms: 1.67x faster                                           |
| scimark_monte_carlo      | 108 ms                                                 | 65.3 ms: 1.66x faster                                          |
| async_tree_none          | 717 ms                                                 | 438 ms: 1.64x faster                                           |
| scimark_sor              | 197 ms                                                 | 121 ms: 1.63x faster                                           |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                          |
| nbody                    | 142 ms                                                 | 88.7 ms: 1.60x faster                                          |
| hexiom                   | 9.53 ms                                                | 6.02 ms: 1.58x faster                                          |
| richards                 | 74.9 ms                                                | 48.6 ms: 1.54x faster                                          |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                          |
| async_tree_memoization   | 854 ms                                                 | 562 ms: 1.52x faster                                           |
| pickle_pure_python       | 455 us                                                 | 300 us: 1.52x faster                                           |
| pyflate                  | 673 ms                                                 | 447 ms: 1.51x faster                                           |
| unpack_sequence          | 64.7 ns                                                | 43.1 ns: 1.50x faster                                          |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                         |
| scimark_lu               | 163 ms                                                 | 111 ms: 1.47x faster                                           |
| coroutines               | 31.8 ms                                                | 21.6 ms: 1.47x faster                                          |
| spectral_norm            | 150 ms                                                 | 105 ms: 1.43x faster                                           |
| deepcopy_memo            | 52.3 us                                                | 36.5 us: 1.43x faster                                          |
| tomli_loads              | 2.92 sec                                               | 2.06 sec: 1.42x faster                                         |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                          |
| mako                     | 14.8 ms                                                | 10.5 ms: 1.41x faster                                          |
| float                    | 111 ms                                                 | 78.9 ms: 1.40x faster                                          |
| unpickle_pure_python     | 300 us                                                 | 216 us: 1.39x faster                                           |
| logging_simple           | 8.07 us                                                | 5.86 us: 1.38x faster                                          |
| json_dumps               | 13.5 ms                                                | 9.90 ms: 1.37x faster                                          |
| logging_format           | 8.91 us                                                | 6.53 us: 1.36x faster                                          |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 701 ms: 1.36x faster                                           |
| tornado_http             | 127 ms                                                 | 94.7 ms: 1.35x faster                                          |
| pprint_pformat           | 1.99 sec                                               | 1.48 sec: 1.34x faster                                         |
| regex_compile            | 177 ms                                                 | 134 ms: 1.32x faster                                           |
| pycparser                | 1.50 sec                                               | 1.15 sec: 1.31x faster                                         |
| pprint_safe_repr         | 955 ms                                                 | 730 ms: 1.31x faster                                           |
| comprehensions           | 26.8 us                                                | 20.7 us: 1.30x faster                                          |
| xml_etree_process        | 74.9 ms                                                | 57.7 ms: 1.30x faster                                          |
| sqlglot_normalize        | 135 ms                                                 | 105 ms: 1.29x faster                                           |
| deepcopy                 | 442 us                                                 | 344 us: 1.29x faster                                           |
| fannkuch                 | 486 ms                                                 | 378 ms: 1.28x faster                                           |
| mypy2                    | 428 ms                                                 | 337 ms: 1.27x faster                                           |
| nqueens                  | 100 ms                                                 | 78.8 ms: 1.27x faster                                          |
| sqlglot_optimize         | 65.3 ms                                                | 52.3 ms: 1.25x faster                                          |
| deepcopy_reduce          | 3.82 us                                                | 3.10 us: 1.24x faster                                          |
| docutils                 | 3.17 sec                                               | 2.60 sec: 1.22x faster                                         |
| scimark_fft              | 424 ms                                                 | 354 ms: 1.20x faster                                           |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.63 ms: 1.18x faster                                          |
| bench_thread_pool        | 947 us                                                 | 806 us: 1.18x faster                                           |
| dulwich_log              | 75.9 ms                                                | 66.1 ms: 1.15x faster                                          |
| json_loads               | 28.8 us                                                | 25.2 us: 1.14x faster                                          |
| json                     | 5.42 ms                                                | 4.78 ms: 1.13x faster                                          |
| xml_etree_generate       | 94.2 ms                                                | 83.2 ms: 1.13x faster                                          |
| mdp                      | 2.82 sec                                               | 2.53 sec: 1.12x faster                                         |
| create_gc_cycles         | 1.67 ms                                                | 1.52 ms: 1.10x faster                                          |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                           |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.09x faster                                           |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.08x faster                                           |
| pathlib                  | 20.0 ms                                                | 18.6 ms: 1.07x faster                                          |
| regex_dna                | 222 ms                                                 | 208 ms: 1.07x faster                                           |
| sqlite_synth             | 2.93 us                                                | 2.76 us: 1.06x faster                                          |
| regex_v8                 | 25.0 ms                                                | 23.6 ms: 1.06x faster                                          |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                           |
| unpickle                 | 14.1 us                                                | 14.6 us: 1.03x slower                                          |
| pickle_list              | 4.56 us                                                | 4.75 us: 1.04x slower                                          |
| async_generators         | 425 ms                                                 | 446 ms: 1.05x slower                                           |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                          |
| gc_traversal             | 3.84 ms                                                | 4.10 ms: 1.07x slower                                          |
| regex_effbot             | 3.23 ms                                                | 3.47 ms: 1.07x slower                                          |
| pickle_dict              | 27.3 us                                                | 31.1 us: 1.14x slower                                          |
| python_startup_no_site   | 5.82 ms                                                | 6.81 ms: 1.17x slower                                          |
| coverage                 | 72.8 ms                                                | 85.6 ms: 1.18x slower                                          |
| telco                    | 6.54 ms                                                | 8.00 ms: 1.22x slower                                          |
| dask                     | 423 ms                                                 | 523 ms: 1.24x slower                                           |
| Geometric mean           | (ref)                                                  | 1.31x faster                                                   |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle_list
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.25x
