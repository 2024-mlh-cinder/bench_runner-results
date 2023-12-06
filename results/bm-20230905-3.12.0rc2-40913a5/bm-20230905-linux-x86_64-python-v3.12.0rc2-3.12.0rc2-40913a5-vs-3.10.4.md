
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0rc2
- machine: linux-x86_64
- commit hash: 40913a5
- commit date: 2023-09-05
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 268 ms: 1.25x faster                                         |
| docutils       | 3.17 sec                                               | 2.71 sec: 1.17x faster                                       |
| tornado_http   | 127 ms                                                 | 102 ms: 1.25x faster                                         |
| Geometric mean | (ref)                                                  | 1.22x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 93.4 ms: 1.52x faster                                        |
| float          | 111 ms                                                 | 80.1 ms: 1.38x faster                                        |
| pidigits       | 190 ms                                                 | 212 ms: 1.11x slower                                         |
| Geometric mean | (ref)                                                  | 1.23x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 144 ms: 1.23x faster                                         |
| regex_v8       | 25.0 ms                                                | 22.3 ms: 1.12x faster                                        |
| regex_dna      | 222 ms                                                 | 213 ms: 1.04x faster                                         |
| regex_effbot   | 3.23 ms                                                | 3.59 ms: 1.11x slower                                        |
| Geometric mean | (ref)                                                  | 1.07x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 314 us: 1.45x faster                                         |
| unpickle_pure_python | 300 us                                                 | 219 us: 1.37x faster                                         |
| json_dumps           | 13.5 ms                                                | 9.89 ms: 1.37x faster                                        |
| tomli_loads          | 2.92 sec                                               | 2.20 sec: 1.33x faster                                       |
| xml_etree_process    | 74.9 ms                                                | 58.7 ms: 1.28x faster                                        |
| json_loads           | 28.8 us                                                | 25.1 us: 1.15x faster                                        |
| xml_etree_generate   | 94.2 ms                                                | 84.3 ms: 1.12x faster                                        |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                         |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                         |
| pickle_list          | 4.56 us                                                | 4.67 us: 1.02x slower                                        |
| pickle               | 10.3 us                                                | 10.6 us: 1.03x slower                                        |
| unpickle             | 14.1 us                                                | 15.1 us: 1.07x slower                                        |
| unpickle_list        | 4.82 us                                                | 5.38 us: 1.12x slower                                        |
| pickle_dict          | 27.3 us                                                | 31.8 us: 1.17x slower                                        |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.46 ms: 1.50x faster                                        |
| python_startup_no_site | 5.82 ms                                                | 6.88 ms: 1.18x slower                                        |
| Geometric mean         | (ref)                                                  | 1.12x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.9 ms: 1.35x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-linux-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 144 us: 3.53x faster                                         |
| generators               | 76.8 ms                                                | 30.8 ms: 2.49x faster                                        |
| deltablue                | 7.42 ms                                                | 3.49 ms: 2.13x faster                                        |
| richards_super           | 90.7 ms                                                | 48.9 ms: 1.86x faster                                        |
| asyncio_tcp              | 925 ms                                                 | 505 ms: 1.83x faster                                         |
| logging_silent           | 175 ns                                                 | 98.5 ns: 1.78x faster                                        |
| richards                 | 74.9 ms                                                | 43.3 ms: 1.73x faster                                        |
| go                       | 229 ms                                                 | 135 ms: 1.69x faster                                         |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                       |
| chaos                    | 106 ms                                                 | 63.8 ms: 1.66x faster                                        |
| scimark_sor              | 197 ms                                                 | 124 ms: 1.58x faster                                         |
| raytrace                 | 464 ms                                                 | 293 ms: 1.58x faster                                         |
| async_tree_io            | 1.77 sec                                               | 1.14 sec: 1.56x faster                                       |
| sqlglot_parse            | 2.06 ms                                                | 1.33 ms: 1.54x faster                                        |
| hexiom                   | 9.53 ms                                                | 6.17 ms: 1.54x faster                                        |
| async_tree_none          | 717 ms                                                 | 465 ms: 1.54x faster                                         |
| scimark_monte_carlo      | 108 ms                                                 | 71.4 ms: 1.52x faster                                        |
| nbody                    | 142 ms                                                 | 93.4 ms: 1.52x faster                                        |
| async_tree_memoization   | 854 ms                                                 | 571 ms: 1.50x faster                                         |
| python_startup           | 14.2 ms                                                | 9.46 ms: 1.50x faster                                        |
| crypto_pyaes             | 118 ms                                                 | 79.6 ms: 1.49x faster                                        |
| sqlglot_transpile        | 2.45 ms                                                | 1.65 ms: 1.48x faster                                        |
| pickle_pure_python       | 455 us                                                 | 314 us: 1.45x faster                                         |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                        |
| pyflate                  | 673 ms                                                 | 467 ms: 1.44x faster                                         |
| scimark_lu               | 163 ms                                                 | 113 ms: 1.44x faster                                         |
| unpack_sequence          | 64.7 ns                                                | 45.6 ns: 1.42x faster                                        |
| spectral_norm            | 150 ms                                                 | 106 ms: 1.41x faster                                         |
| deepcopy_memo            | 52.3 us                                                | 37.5 us: 1.40x faster                                        |
| float                    | 111 ms                                                 | 80.1 ms: 1.38x faster                                        |
| unpickle_pure_python     | 300 us                                                 | 219 us: 1.37x faster                                         |
| json_dumps               | 13.5 ms                                                | 9.89 ms: 1.37x faster                                        |
| mako                     | 14.8 ms                                                | 10.9 ms: 1.35x faster                                        |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 708 ms: 1.34x faster                                         |
| tomli_loads              | 2.92 sec                                               | 2.20 sec: 1.33x faster                                       |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.32x faster                                       |
| pprint_safe_repr         | 955 ms                                                 | 736 ms: 1.30x faster                                         |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.30x faster                                       |
| comprehensions           | 26.8 us                                                | 20.7 us: 1.29x faster                                        |
| logging_simple           | 8.07 us                                                | 6.28 us: 1.28x faster                                        |
| xml_etree_process        | 74.9 ms                                                | 58.7 ms: 1.28x faster                                        |
| deepcopy                 | 442 us                                                 | 351 us: 1.26x faster                                         |
| logging_format           | 8.91 us                                                | 7.08 us: 1.26x faster                                        |
| 2to3                     | 336 ms                                                 | 268 ms: 1.25x faster                                         |
| tornado_http             | 127 ms                                                 | 102 ms: 1.25x faster                                         |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.25x faster                                         |
| mypy2                    | 428 ms                                                 | 344 ms: 1.25x faster                                         |
| nqueens                  | 100 ms                                                 | 81.4 ms: 1.23x faster                                        |
| regex_compile            | 177 ms                                                 | 144 ms: 1.23x faster                                         |
| deepcopy_reduce          | 3.82 us                                                | 3.12 us: 1.23x faster                                        |
| sqlglot_optimize         | 65.3 ms                                                | 53.5 ms: 1.22x faster                                        |
| fannkuch                 | 486 ms                                                 | 400 ms: 1.21x faster                                         |
| docutils                 | 3.17 sec                                               | 2.71 sec: 1.17x faster                                       |
| scimark_fft              | 424 ms                                                 | 364 ms: 1.16x faster                                         |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.4 ms: 1.15x faster                                        |
| json_loads               | 28.8 us                                                | 25.1 us: 1.15x faster                                        |
| bench_thread_pool        | 947 us                                                 | 829 us: 1.14x faster                                         |
| sqlalchemy_declarative   | 165 ms                                                 | 145 ms: 1.14x faster                                         |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.81 ms: 1.13x faster                                        |
| json                     | 5.42 ms                                                | 4.80 ms: 1.13x faster                                        |
| regex_v8                 | 25.0 ms                                                | 22.3 ms: 1.12x faster                                        |
| xml_etree_generate       | 94.2 ms                                                | 84.3 ms: 1.12x faster                                        |
| dulwich_log              | 75.9 ms                                                | 68.2 ms: 1.11x faster                                        |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.10x faster                                        |
| mdp                      | 2.82 sec                                               | 2.58 sec: 1.10x faster                                       |
| pathlib                  | 20.0 ms                                                | 18.4 ms: 1.09x faster                                        |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.08x faster                                         |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                         |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                        |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                         |
| regex_dna                | 222 ms                                                 | 213 ms: 1.04x faster                                         |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                        |
| pickle_list              | 4.56 us                                                | 4.67 us: 1.02x slower                                        |
| pickle                   | 10.3 us                                                | 10.6 us: 1.03x slower                                        |
| telco                    | 6.54 ms                                                | 6.83 ms: 1.04x slower                                        |
| async_generators         | 425 ms                                                 | 445 ms: 1.05x slower                                         |
| unpickle                 | 14.1 us                                                | 15.1 us: 1.07x slower                                        |
| regex_effbot             | 3.23 ms                                                | 3.59 ms: 1.11x slower                                        |
| pidigits                 | 190 ms                                                 | 212 ms: 1.11x slower                                         |
| unpickle_list            | 4.82 us                                                | 5.38 us: 1.12x slower                                        |
| pickle_dict              | 27.3 us                                                | 31.8 us: 1.17x slower                                        |
| python_startup_no_site   | 5.82 ms                                                | 6.88 ms: 1.18x slower                                        |
| dask                     | 423 ms                                                 | 537 ms: 1.27x slower                                         |
| coverage                 | 72.8 ms                                                | 94.7 ms: 1.30x slower                                        |
| Geometric mean           | (ref)                                                  | 1.28x faster                                                 |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
