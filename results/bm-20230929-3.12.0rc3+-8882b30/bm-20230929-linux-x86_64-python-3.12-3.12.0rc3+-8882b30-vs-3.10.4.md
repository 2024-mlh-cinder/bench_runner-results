
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 8882b30
- commit date: 2023-09-29
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 269 ms: 1.25x faster                                    |
| docutils       | 3.17 sec                                               | 2.72 sec: 1.17x faster                                  |
| tornado_http   | 127 ms                                                 | 100 ms: 1.27x faster                                    |
| Geometric mean | (ref)                                                  | 1.23x faster                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| nbody          | 142 ms                                                 | 92.8 ms: 1.53x faster                                   |
| float          | 111 ms                                                 | 80.1 ms: 1.38x faster                                   |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                    |
| Geometric mean | (ref)                                                  | 1.29x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 144 ms: 1.23x faster                                    |
| regex_v8       | 25.0 ms                                                | 22.1 ms: 1.13x faster                                   |
| regex_dna      | 222 ms                                                 | 210 ms: 1.06x faster                                    |
| regex_effbot   | 3.23 ms                                                | 3.58 ms: 1.11x slower                                   |
| Geometric mean | (ref)                                                  | 1.07x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 316 us: 1.44x faster                                    |
| json_dumps           | 13.5 ms                                                | 9.78 ms: 1.38x faster                                   |
| unpickle_pure_python | 300 us                                                 | 218 us: 1.38x faster                                    |
| tomli_loads          | 2.92 sec                                               | 2.22 sec: 1.32x faster                                  |
| xml_etree_process    | 74.9 ms                                                | 59.0 ms: 1.27x faster                                   |
| json_loads           | 28.8 us                                                | 25.2 us: 1.15x faster                                   |
| xml_etree_generate   | 94.2 ms                                                | 84.6 ms: 1.11x faster                                   |
| xml_etree_iterparse  | 111 ms                                                 | 104 ms: 1.07x faster                                    |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                    |
| pickle               | 10.3 us                                                | 10.6 us: 1.03x slower                                   |
| pickle_list          | 4.56 us                                                | 4.70 us: 1.03x slower                                   |
| unpickle_list        | 4.82 us                                                | 5.05 us: 1.05x slower                                   |
| unpickle             | 14.1 us                                                | 14.9 us: 1.05x slower                                   |
| pickle_dict          | 27.3 us                                                | 32.7 us: 1.20x slower                                   |
| Geometric mean       | (ref)                                                  | 1.12x faster                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.48 ms: 1.49x faster                                   |
| python_startup_no_site | 5.82 ms                                                | 6.90 ms: 1.19x slower                                   |
| Geometric mean         | (ref)                                                  | 1.12x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.7 ms: 1.38x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230929-linux-x86_64-python-3.12-3.12.0rc3+-8882b30 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 145 us: 3.51x faster                                    |
| generators               | 76.8 ms                                                | 32.6 ms: 2.36x faster                                   |
| deltablue                | 7.42 ms                                                | 3.60 ms: 2.06x faster                                   |
| richards_super           | 90.7 ms                                                | 50.6 ms: 1.79x faster                                   |
| asyncio_tcp              | 925 ms                                                 | 529 ms: 1.75x faster                                    |
| logging_silent           | 175 ns                                                 | 102 ns: 1.72x faster                                    |
| richards                 | 74.9 ms                                                | 43.7 ms: 1.72x faster                                   |
| chaos                    | 106 ms                                                 | 63.5 ms: 1.67x faster                                   |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                  |
| go                       | 229 ms                                                 | 138 ms: 1.67x faster                                    |
| raytrace                 | 464 ms                                                 | 294 ms: 1.58x faster                                    |
| scimark_sor              | 197 ms                                                 | 125 ms: 1.57x faster                                    |
| sqlglot_parse            | 2.06 ms                                                | 1.34 ms: 1.54x faster                                   |
| async_tree_none          | 717 ms                                                 | 468 ms: 1.53x faster                                    |
| async_tree_io            | 1.77 sec                                               | 1.16 sec: 1.53x faster                                  |
| nbody                    | 142 ms                                                 | 92.8 ms: 1.53x faster                                   |
| scimark_monte_carlo      | 108 ms                                                 | 71.1 ms: 1.52x faster                                   |
| hexiom                   | 9.53 ms                                                | 6.26 ms: 1.52x faster                                   |
| pyflate                  | 673 ms                                                 | 446 ms: 1.51x faster                                    |
| crypto_pyaes             | 118 ms                                                 | 79.1 ms: 1.50x faster                                   |
| python_startup           | 14.2 ms                                                | 9.48 ms: 1.49x faster                                   |
| async_tree_memoization   | 854 ms                                                 | 573 ms: 1.49x faster                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.65 ms: 1.48x faster                                   |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                   |
| pickle_pure_python       | 455 us                                                 | 316 us: 1.44x faster                                    |
| scimark_lu               | 163 ms                                                 | 115 ms: 1.42x faster                                    |
| spectral_norm            | 150 ms                                                 | 106 ms: 1.42x faster                                    |
| deepcopy_memo            | 52.3 us                                                | 37.5 us: 1.40x faster                                   |
| json_dumps               | 13.5 ms                                                | 9.78 ms: 1.38x faster                                   |
| float                    | 111 ms                                                 | 80.1 ms: 1.38x faster                                   |
| unpickle_pure_python     | 300 us                                                 | 218 us: 1.38x faster                                    |
| mako                     | 14.8 ms                                                | 10.7 ms: 1.38x faster                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 720 ms: 1.32x faster                                    |
| tomli_loads              | 2.92 sec                                               | 2.22 sec: 1.32x faster                                  |
| pycparser                | 1.50 sec                                               | 1.14 sec: 1.31x faster                                  |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                  |
| comprehensions           | 26.8 us                                                | 20.6 us: 1.30x faster                                   |
| pprint_safe_repr         | 955 ms                                                 | 742 ms: 1.29x faster                                    |
| xml_etree_process        | 74.9 ms                                                | 59.0 ms: 1.27x faster                                   |
| tornado_http             | 127 ms                                                 | 100 ms: 1.27x faster                                    |
| logging_simple           | 8.07 us                                                | 6.40 us: 1.26x faster                                   |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.26x faster                                    |
| deepcopy                 | 442 us                                                 | 352 us: 1.26x faster                                    |
| 2to3                     | 336 ms                                                 | 269 ms: 1.25x faster                                    |
| logging_format           | 8.91 us                                                | 7.16 us: 1.24x faster                                   |
| mypy2                    | 428 ms                                                 | 345 ms: 1.24x faster                                    |
| fannkuch                 | 486 ms                                                 | 391 ms: 1.24x faster                                    |
| deepcopy_reduce          | 3.82 us                                                | 3.11 us: 1.23x faster                                   |
| regex_compile            | 177 ms                                                 | 144 ms: 1.23x faster                                    |
| nqueens                  | 100 ms                                                 | 81.5 ms: 1.23x faster                                   |
| sqlglot_optimize         | 65.3 ms                                                | 53.4 ms: 1.22x faster                                   |
| unpack_sequence          | 64.7 ns                                                | 53.7 ns: 1.21x faster                                   |
| scimark_fft              | 424 ms                                                 | 359 ms: 1.18x faster                                    |
| docutils                 | 3.17 sec                                               | 2.72 sec: 1.17x faster                                  |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.4 ms: 1.15x faster                                   |
| dask                     | 423 ms                                                 | 368 ms: 1.15x faster                                    |
| json_loads               | 28.8 us                                                | 25.2 us: 1.15x faster                                   |
| sqlalchemy_declarative   | 165 ms                                                 | 145 ms: 1.14x faster                                    |
| bench_thread_pool        | 947 us                                                 | 831 us: 1.14x faster                                    |
| json                     | 5.42 ms                                                | 4.78 ms: 1.13x faster                                   |
| regex_v8                 | 25.0 ms                                                | 22.1 ms: 1.13x faster                                   |
| dulwich_log              | 75.9 ms                                                | 68.1 ms: 1.11x faster                                   |
| xml_etree_generate       | 94.2 ms                                                | 84.6 ms: 1.11x faster                                   |
| mdp                      | 2.82 sec                                               | 2.56 sec: 1.10x faster                                  |
| create_gc_cycles         | 1.67 ms                                                | 1.52 ms: 1.10x faster                                   |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.10x faster                                    |
| xml_etree_iterparse      | 111 ms                                                 | 104 ms: 1.07x faster                                    |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.12 ms: 1.07x faster                                   |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.07x faster                                   |
| sqlite_synth             | 2.93 us                                                | 2.76 us: 1.07x faster                                   |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                    |
| regex_dna                | 222 ms                                                 | 210 ms: 1.06x faster                                    |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                    |
| pickle                   | 10.3 us                                                | 10.6 us: 1.03x slower                                   |
| gc_traversal             | 3.84 ms                                                | 3.95 ms: 1.03x slower                                   |
| pickle_list              | 4.56 us                                                | 4.70 us: 1.03x slower                                   |
| unpickle_list            | 4.82 us                                                | 5.05 us: 1.05x slower                                   |
| telco                    | 6.54 ms                                                | 6.88 ms: 1.05x slower                                   |
| unpickle                 | 14.1 us                                                | 14.9 us: 1.05x slower                                   |
| async_generators         | 425 ms                                                 | 449 ms: 1.06x slower                                    |
| regex_effbot             | 3.23 ms                                                | 3.58 ms: 1.11x slower                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.90 ms: 1.19x slower                                   |
| pickle_dict              | 27.3 us                                                | 32.7 us: 1.20x slower                                   |
| coverage                 | 72.8 ms                                                | 94.7 ms: 1.30x slower                                   |
| Geometric mean           | (ref)                                                  | 1.28x faster                                            |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
