
# Results vs. 3.10.4

- fork: gvanrossum
- ref: split_uops
- machine: linux-x86_64
- commit hash: 8ab398d
- commit date: 2023-10-03
- overall geometric mean: 1.32x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.27x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.58 sec: 1.23x faster                                          |
| tornado_http   | 127 ms                                                 | 95.7 ms: 1.33x faster                                           |
| Geometric mean | (ref)                                                  | 1.28x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.8 ms: 1.54x faster                                           |
| float          | 111 ms                                                 | 79.3 ms: 1.39x faster                                           |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                            |
| Geometric mean | (ref)                                                  | 1.30x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 134 ms: 1.32x faster                                            |
| regex_dna      | 222 ms                                                 | 205 ms: 1.08x faster                                            |
| regex_v8       | 25.0 ms                                                | 23.9 ms: 1.05x faster                                           |
| regex_effbot   | 3.23 ms                                                | 3.39 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                  | 1.09x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 297 us: 1.53x faster                                            |
| unpickle_pure_python | 300 us                                                 | 214 us: 1.40x faster                                            |
| json_dumps           | 13.5 ms                                                | 9.75 ms: 1.39x faster                                           |
| tomli_loads          | 2.92 sec                                               | 2.15 sec: 1.36x faster                                          |
| xml_etree_process    | 74.9 ms                                                | 58.0 ms: 1.29x faster                                           |
| xml_etree_generate   | 94.2 ms                                                | 83.2 ms: 1.13x faster                                           |
| json_loads           | 28.8 us                                                | 25.9 us: 1.11x faster                                           |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.10x faster                                            |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                            |
| pickle               | 10.3 us                                                | 10.4 us: 1.01x slower                                           |
| pickle_list          | 4.56 us                                                | 4.68 us: 1.03x slower                                           |
| unpickle             | 14.1 us                                                | 14.6 us: 1.03x slower                                           |
| pickle_dict          | 27.3 us                                                | 32.2 us: 1.18x slower                                           |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                    |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.41x faster                                           |
| python_startup_no_site | 5.82 ms                                                | 6.86 ms: 1.18x slower                                           |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.4 ms: 1.42x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 142 us: 3.58x faster                                            |
| generators               | 76.8 ms                                                | 28.5 ms: 2.69x faster                                           |
| deltablue                | 7.42 ms                                                | 3.25 ms: 2.29x faster                                           |
| asyncio_tcp              | 925 ms                                                 | 500 ms: 1.85x faster                                            |
| chaos                    | 106 ms                                                 | 60.0 ms: 1.77x faster                                           |
| logging_silent           | 175 ns                                                 | 99.5 ns: 1.76x faster                                           |
| raytrace                 | 464 ms                                                 | 267 ms: 1.73x faster                                            |
| richards_super           | 90.7 ms                                                | 52.5 ms: 1.73x faster                                           |
| crypto_pyaes             | 118 ms                                                 | 69.2 ms: 1.71x faster                                           |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                          |
| scimark_sor              | 197 ms                                                 | 118 ms: 1.67x faster                                            |
| go                       | 229 ms                                                 | 138 ms: 1.66x faster                                            |
| scimark_monte_carlo      | 108 ms                                                 | 66.1 ms: 1.64x faster                                           |
| sqlglot_parse            | 2.06 ms                                                | 1.26 ms: 1.64x faster                                           |
| async_tree_none          | 717 ms                                                 | 439 ms: 1.63x faster                                            |
| hexiom                   | 9.53 ms                                                | 5.92 ms: 1.61x faster                                           |
| richards                 | 74.9 ms                                                | 47.1 ms: 1.59x faster                                           |
| sqlglot_transpile        | 2.45 ms                                                | 1.56 ms: 1.57x faster                                           |
| unpack_sequence          | 64.7 ns                                                | 41.9 ns: 1.55x faster                                           |
| nbody                    | 142 ms                                                 | 91.8 ms: 1.54x faster                                           |
| pickle_pure_python       | 455 us                                                 | 297 us: 1.53x faster                                            |
| async_tree_memoization   | 854 ms                                                 | 562 ms: 1.52x faster                                            |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                          |
| pyflate                  | 673 ms                                                 | 454 ms: 1.48x faster                                            |
| scimark_lu               | 163 ms                                                 | 110 ms: 1.48x faster                                            |
| deepcopy_memo            | 52.3 us                                                | 36.8 us: 1.42x faster                                           |
| mako                     | 14.8 ms                                                | 10.4 ms: 1.42x faster                                           |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.41x faster                                           |
| unpickle_pure_python     | 300 us                                                 | 214 us: 1.40x faster                                            |
| spectral_norm            | 150 ms                                                 | 107 ms: 1.40x faster                                            |
| coroutines               | 31.8 ms                                                | 22.7 ms: 1.40x faster                                           |
| float                    | 111 ms                                                 | 79.3 ms: 1.39x faster                                           |
| logging_simple           | 8.07 us                                                | 5.81 us: 1.39x faster                                           |
| json_dumps               | 13.5 ms                                                | 9.75 ms: 1.39x faster                                           |
| logging_format           | 8.91 us                                                | 6.48 us: 1.38x faster                                           |
| pprint_pformat           | 1.99 sec                                               | 1.45 sec: 1.37x faster                                          |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 699 ms: 1.36x faster                                            |
| tomli_loads              | 2.92 sec                                               | 2.15 sec: 1.36x faster                                          |
| pprint_safe_repr         | 955 ms                                                 | 711 ms: 1.34x faster                                            |
| tornado_http             | 127 ms                                                 | 95.7 ms: 1.33x faster                                           |
| regex_compile            | 177 ms                                                 | 134 ms: 1.32x faster                                            |
| comprehensions           | 26.8 us                                                | 20.5 us: 1.31x faster                                           |
| sqlglot_normalize        | 135 ms                                                 | 103 ms: 1.31x faster                                            |
| pycparser                | 1.50 sec                                               | 1.15 sec: 1.30x faster                                          |
| xml_etree_process        | 74.9 ms                                                | 58.0 ms: 1.29x faster                                           |
| deepcopy                 | 442 us                                                 | 344 us: 1.29x faster                                            |
| nqueens                  | 100 ms                                                 | 77.9 ms: 1.28x faster                                           |
| fannkuch                 | 486 ms                                                 | 380 ms: 1.28x faster                                            |
| mypy2                    | 428 ms                                                 | 336 ms: 1.27x faster                                            |
| deepcopy_reduce          | 3.82 us                                                | 3.03 us: 1.26x faster                                           |
| sqlglot_optimize         | 65.3 ms                                                | 52.1 ms: 1.25x faster                                           |
| docutils                 | 3.17 sec                                               | 2.58 sec: 1.23x faster                                          |
| scimark_fft              | 424 ms                                                 | 359 ms: 1.18x faster                                            |
| bench_thread_pool        | 947 us                                                 | 810 us: 1.17x faster                                            |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.74 ms: 1.15x faster                                           |
| dulwich_log              | 75.9 ms                                                | 66.3 ms: 1.15x faster                                           |
| xml_etree_generate       | 94.2 ms                                                | 83.2 ms: 1.13x faster                                           |
| mdp                      | 2.82 sec                                               | 2.52 sec: 1.12x faster                                          |
| json_loads               | 28.8 us                                                | 25.9 us: 1.11x faster                                           |
| json                     | 5.42 ms                                                | 4.88 ms: 1.11x faster                                           |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                           |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.10x faster                                            |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.09x faster                                            |
| regex_dna                | 222 ms                                                 | 205 ms: 1.08x faster                                            |
| sqlite_synth             | 2.93 us                                                | 2.73 us: 1.07x faster                                           |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                           |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.07x faster                                            |
| regex_v8                 | 25.0 ms                                                | 23.9 ms: 1.05x faster                                           |
| gc_traversal             | 3.84 ms                                                | 3.70 ms: 1.04x faster                                           |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                            |
| pickle                   | 10.3 us                                                | 10.4 us: 1.01x slower                                           |
| pickle_list              | 4.56 us                                                | 4.68 us: 1.03x slower                                           |
| unpickle                 | 14.1 us                                                | 14.6 us: 1.03x slower                                           |
| async_generators         | 425 ms                                                 | 445 ms: 1.05x slower                                            |
| regex_effbot             | 3.23 ms                                                | 3.39 ms: 1.05x slower                                           |
| python_startup_no_site   | 5.82 ms                                                | 6.86 ms: 1.18x slower                                           |
| pickle_dict              | 27.3 us                                                | 32.2 us: 1.18x slower                                           |
| coverage                 | 72.8 ms                                                | 86.2 ms: 1.18x slower                                           |
| telco                    | 6.54 ms                                                | 8.05 ms: 1.23x slower                                           |
| Geometric mean           | (ref)                                                  | 1.32x faster                                                    |

Benchmark hidden because not significant (2): unpickle_list, bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.27x
