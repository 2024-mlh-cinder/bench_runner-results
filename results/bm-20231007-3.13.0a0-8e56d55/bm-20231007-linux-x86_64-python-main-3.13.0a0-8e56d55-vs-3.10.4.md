
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 8e56d55
- commit date: 2023-10-07
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.63 sec: 1.20x faster                                |
| tornado_http   | 127 ms                                                 | 96.5 ms: 1.32x faster                                 |
| Geometric mean | (ref)                                                  | 1.26x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.4 ms: 1.55x faster                                 |
| float          | 111 ms                                                 | 82.7 ms: 1.34x faster                                 |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.28x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 139 ms: 1.28x faster                                  |
| regex_dna      | 222 ms                                                 | 211 ms: 1.05x faster                                  |
| regex_v8       | 25.0 ms                                                | 25.5 ms: 1.02x slower                                 |
| regex_effbot   | 3.23 ms                                                | 3.65 ms: 1.13x slower                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 307 us: 1.49x faster                                  |
| tomli_loads          | 2.92 sec                                               | 2.17 sec: 1.34x faster                                |
| unpickle_pure_python | 300 us                                                 | 225 us: 1.33x faster                                  |
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.29x faster                                 |
| xml_etree_process    | 74.9 ms                                                | 59.6 ms: 1.26x faster                                 |
| xml_etree_generate   | 94.2 ms                                                | 86.7 ms: 1.09x faster                                 |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.06x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                  |
| json_loads           | 28.8 us                                                | 28.4 us: 1.01x faster                                 |
| unpickle             | 14.1 us                                                | 14.9 us: 1.05x slower                                 |
| unpickle_list        | 4.82 us                                                | 5.08 us: 1.05x slower                                 |
| pickle               | 10.3 us                                                | 11.6 us: 1.12x slower                                 |
| pickle_list          | 4.56 us                                                | 5.18 us: 1.14x slower                                 |
| pickle_dict          | 27.3 us                                                | 34.2 us: 1.25x slower                                 |
| Geometric mean       | (ref)                                                  | 1.08x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.41x faster                                 |
| python_startup_no_site | 5.82 ms                                                | 6.85 ms: 1.18x slower                                 |
| Geometric mean         | (ref)                                                  | 1.09x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.8 ms: 1.25x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 154 us: 3.32x faster                                  |
| generators               | 76.8 ms                                                | 29.0 ms: 2.65x faster                                 |
| deltablue                | 7.42 ms                                                | 3.32 ms: 2.23x faster                                 |
| asyncio_tcp              | 925 ms                                                 | 474 ms: 1.95x faster                                  |
| chaos                    | 106 ms                                                 | 61.8 ms: 1.72x faster                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.77 sec: 1.69x faster                                |
| richards_super           | 90.7 ms                                                | 54.2 ms: 1.67x faster                                 |
| raytrace                 | 464 ms                                                 | 278 ms: 1.67x faster                                  |
| logging_silent           | 175 ns                                                 | 107 ns: 1.63x faster                                  |
| crypto_pyaes             | 118 ms                                                 | 72.8 ms: 1.63x faster                                 |
| async_tree_none          | 717 ms                                                 | 440 ms: 1.63x faster                                  |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.60x faster                                 |
| go                       | 229 ms                                                 | 146 ms: 1.57x faster                                  |
| richards                 | 74.9 ms                                                | 47.8 ms: 1.57x faster                                 |
| scimark_sor              | 197 ms                                                 | 126 ms: 1.57x faster                                  |
| scimark_monte_carlo      | 108 ms                                                 | 69.2 ms: 1.56x faster                                 |
| nbody                    | 142 ms                                                 | 91.4 ms: 1.55x faster                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.61 ms: 1.52x faster                                 |
| hexiom                   | 9.53 ms                                                | 6.31 ms: 1.51x faster                                 |
| async_tree_memoization   | 854 ms                                                 | 567 ms: 1.51x faster                                  |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                |
| pickle_pure_python       | 455 us                                                 | 307 us: 1.49x faster                                  |
| pyflate                  | 673 ms                                                 | 465 ms: 1.45x faster                                  |
| scimark_lu               | 163 ms                                                 | 115 ms: 1.42x faster                                  |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.41x faster                                 |
| logging_simple           | 8.07 us                                                | 5.86 us: 1.38x faster                                 |
| logging_format           | 8.91 us                                                | 6.48 us: 1.38x faster                                 |
| coroutines               | 31.8 ms                                                | 23.3 ms: 1.37x faster                                 |
| tomli_loads              | 2.92 sec                                               | 2.17 sec: 1.34x faster                                |
| deepcopy_memo            | 52.3 us                                                | 38.9 us: 1.34x faster                                 |
| float                    | 111 ms                                                 | 82.7 ms: 1.34x faster                                 |
| unpickle_pure_python     | 300 us                                                 | 225 us: 1.33x faster                                  |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 714 ms: 1.33x faster                                  |
| spectral_norm            | 150 ms                                                 | 114 ms: 1.32x faster                                  |
| tornado_http             | 127 ms                                                 | 96.5 ms: 1.32x faster                                 |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                |
| json_dumps               | 13.5 ms                                                | 10.5 ms: 1.29x faster                                 |
| pprint_safe_repr         | 955 ms                                                 | 744 ms: 1.28x faster                                  |
| regex_compile            | 177 ms                                                 | 139 ms: 1.28x faster                                  |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                  |
| comprehensions           | 26.8 us                                                | 21.1 us: 1.27x faster                                 |
| xml_etree_process        | 74.9 ms                                                | 59.6 ms: 1.26x faster                                 |
| nqueens                  | 100 ms                                                 | 79.8 ms: 1.25x faster                                 |
| mako                     | 14.8 ms                                                | 11.8 ms: 1.25x faster                                 |
| mypy2                    | 428 ms                                                 | 344 ms: 1.25x faster                                  |
| deepcopy                 | 442 us                                                 | 355 us: 1.24x faster                                  |
| pycparser                | 1.50 sec                                               | 1.21 sec: 1.24x faster                                |
| sqlglot_optimize         | 65.3 ms                                                | 53.6 ms: 1.22x faster                                 |
| docutils                 | 3.17 sec                                               | 2.63 sec: 1.20x faster                                |
| deepcopy_reduce          | 3.82 us                                                | 3.19 us: 1.20x faster                                 |
| fannkuch                 | 486 ms                                                 | 412 ms: 1.18x faster                                  |
| unpack_sequence          | 64.7 ns                                                | 55.1 ns: 1.17x faster                                 |
| bench_thread_pool        | 947 us                                                 | 813 us: 1.16x faster                                  |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.70 ms: 1.16x faster                                 |
| scimark_fft              | 424 ms                                                 | 370 ms: 1.15x faster                                  |
| dulwich_log              | 75.9 ms                                                | 67.4 ms: 1.13x faster                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                 |
| xml_etree_generate       | 94.2 ms                                                | 86.7 ms: 1.09x faster                                 |
| mdp                      | 2.82 sec                                               | 2.60 sec: 1.08x faster                                |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.06x faster                                  |
| json                     | 5.42 ms                                                | 5.14 ms: 1.05x faster                                 |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.05x faster                                 |
| meteor_contest           | 115 ms                                                 | 109 ms: 1.05x faster                                  |
| regex_dna                | 222 ms                                                 | 211 ms: 1.05x faster                                  |
| xml_etree_parse          | 163 ms                                                 | 158 ms: 1.03x faster                                  |
| sqlite_synth             | 2.93 us                                                | 2.85 us: 1.03x faster                                 |
| json_loads               | 28.8 us                                                | 28.4 us: 1.01x faster                                 |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                  |
| gc_traversal             | 3.84 ms                                                | 3.85 ms: 1.00x slower                                 |
| regex_v8                 | 25.0 ms                                                | 25.5 ms: 1.02x slower                                 |
| unpickle                 | 14.1 us                                                | 14.9 us: 1.05x slower                                 |
| unpickle_list            | 4.82 us                                                | 5.08 us: 1.05x slower                                 |
| async_generators         | 425 ms                                                 | 471 ms: 1.11x slower                                  |
| pickle                   | 10.3 us                                                | 11.6 us: 1.12x slower                                 |
| regex_effbot             | 3.23 ms                                                | 3.65 ms: 1.13x slower                                 |
| pickle_list              | 4.56 us                                                | 5.18 us: 1.14x slower                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.85 ms: 1.18x slower                                 |
| coverage                 | 72.8 ms                                                | 90.4 ms: 1.24x slower                                 |
| pickle_dict              | 27.3 us                                                | 34.2 us: 1.25x slower                                 |
| telco                    | 6.54 ms                                                | 8.23 ms: 1.26x slower                                 |
| Geometric mean           | (ref)                                                  | 1.27x faster                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
