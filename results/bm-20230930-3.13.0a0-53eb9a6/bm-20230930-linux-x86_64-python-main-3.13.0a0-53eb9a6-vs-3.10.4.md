
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.31x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.60 sec: 1.22x faster                                |
| tornado_http   | 127 ms                                                 | 95.0 ms: 1.34x faster                                 |
| Geometric mean | (ref)                                                  | 1.28x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 142 ms                                                 | 89.1 ms: 1.59x faster                                 |
| float          | 111 ms                                                 | 79.9 ms: 1.38x faster                                 |
| pidigits       | 190 ms                                                 | 194 ms: 1.02x slower                                  |
| Geometric mean | (ref)                                                  | 1.29x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 134 ms: 1.32x faster                                  |
| regex_dna      | 222 ms                                                 | 204 ms: 1.09x faster                                  |
| regex_v8       | 25.0 ms                                                | 23.4 ms: 1.07x faster                                 |
| regex_effbot   | 3.23 ms                                                | 3.50 ms: 1.09x slower                                 |
| Geometric mean | (ref)                                                  | 1.09x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 294 us: 1.55x faster                                  |
| unpickle_pure_python | 300 us                                                 | 211 us: 1.42x faster                                  |
| tomli_loads          | 2.92 sec                                               | 2.11 sec: 1.38x faster                                |
| json_dumps           | 13.5 ms                                                | 9.88 ms: 1.37x faster                                 |
| xml_etree_process    | 74.9 ms                                                | 56.8 ms: 1.32x faster                                 |
| xml_etree_generate   | 94.2 ms                                                | 83.3 ms: 1.13x faster                                 |
| json_loads           | 28.8 us                                                | 25.8 us: 1.12x faster                                 |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.09x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                  |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                 |
| pickle_list          | 4.56 us                                                | 4.72 us: 1.04x slower                                 |
| unpickle_list        | 4.82 us                                                | 5.01 us: 1.04x slower                                 |
| unpickle             | 14.1 us                                                | 15.0 us: 1.06x slower                                 |
| pickle_dict          | 27.3 us                                                | 31.5 us: 1.16x slower                                 |
| Geometric mean       | (ref)                                                  | 1.14x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                 |
| python_startup_no_site | 5.82 ms                                                | 6.84 ms: 1.18x slower                                 |
| Geometric mean         | (ref)                                                  | 1.10x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.5 ms: 1.41x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 142 us: 3.60x faster                                  |
| generators               | 76.8 ms                                                | 28.4 ms: 2.71x faster                                 |
| deltablue                | 7.42 ms                                                | 3.31 ms: 2.24x faster                                 |
| asyncio_tcp              | 925 ms                                                 | 500 ms: 1.85x faster                                  |
| chaos                    | 106 ms                                                 | 59.5 ms: 1.79x faster                                 |
| raytrace                 | 464 ms                                                 | 265 ms: 1.75x faster                                  |
| logging_silent           | 175 ns                                                 | 100 ns: 1.74x faster                                  |
| crypto_pyaes             | 118 ms                                                 | 68.4 ms: 1.73x faster                                 |
| richards_super           | 90.7 ms                                                | 53.9 ms: 1.68x faster                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                |
| go                       | 229 ms                                                 | 138 ms: 1.66x faster                                  |
| async_tree_none          | 717 ms                                                 | 433 ms: 1.65x faster                                  |
| scimark_monte_carlo      | 108 ms                                                 | 65.8 ms: 1.65x faster                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.25 ms: 1.64x faster                                 |
| scimark_sor              | 197 ms                                                 | 120 ms: 1.64x faster                                  |
| hexiom                   | 9.53 ms                                                | 5.97 ms: 1.60x faster                                 |
| nbody                    | 142 ms                                                 | 89.1 ms: 1.59x faster                                 |
| richards                 | 74.9 ms                                                | 47.4 ms: 1.58x faster                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.56 ms: 1.57x faster                                 |
| pickle_pure_python       | 455 us                                                 | 294 us: 1.55x faster                                  |
| async_tree_memoization   | 854 ms                                                 | 559 ms: 1.53x faster                                  |
| async_tree_io            | 1.77 sec                                               | 1.18 sec: 1.50x faster                                |
| coroutines               | 31.8 ms                                                | 21.7 ms: 1.47x faster                                 |
| pyflate                  | 673 ms                                                 | 460 ms: 1.46x faster                                  |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.46x faster                                  |
| deepcopy_memo            | 52.3 us                                                | 36.4 us: 1.44x faster                                 |
| unpack_sequence          | 64.7 ns                                                | 45.1 ns: 1.44x faster                                 |
| spectral_norm            | 150 ms                                                 | 105 ms: 1.42x faster                                  |
| unpickle_pure_python     | 300 us                                                 | 211 us: 1.42x faster                                  |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                 |
| mako                     | 14.8 ms                                                | 10.5 ms: 1.41x faster                                 |
| tomli_loads              | 2.92 sec                                               | 2.11 sec: 1.38x faster                                |
| float                    | 111 ms                                                 | 79.9 ms: 1.38x faster                                 |
| logging_format           | 8.91 us                                                | 6.47 us: 1.38x faster                                 |
| logging_simple           | 8.07 us                                                | 5.87 us: 1.38x faster                                 |
| json_dumps               | 13.5 ms                                                | 9.88 ms: 1.37x faster                                 |
| pprint_pformat           | 1.99 sec                                               | 1.45 sec: 1.37x faster                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 695 ms: 1.37x faster                                  |
| pprint_safe_repr         | 955 ms                                                 | 710 ms: 1.34x faster                                  |
| tornado_http             | 127 ms                                                 | 95.0 ms: 1.34x faster                                 |
| comprehensions           | 26.8 us                                                | 20.1 us: 1.34x faster                                 |
| regex_compile            | 177 ms                                                 | 134 ms: 1.32x faster                                  |
| pycparser                | 1.50 sec                                               | 1.14 sec: 1.32x faster                                |
| xml_etree_process        | 74.9 ms                                                | 56.8 ms: 1.32x faster                                 |
| sqlglot_normalize        | 135 ms                                                 | 103 ms: 1.31x faster                                  |
| deepcopy                 | 442 us                                                 | 341 us: 1.30x faster                                  |
| fannkuch                 | 486 ms                                                 | 384 ms: 1.27x faster                                  |
| deepcopy_reduce          | 3.82 us                                                | 3.04 us: 1.26x faster                                 |
| sqlglot_optimize         | 65.3 ms                                                | 52.2 ms: 1.25x faster                                 |
| nqueens                  | 100 ms                                                 | 80.5 ms: 1.24x faster                                 |
| docutils                 | 3.17 sec                                               | 2.60 sec: 1.22x faster                                |
| scimark_fft              | 424 ms                                                 | 359 ms: 1.18x faster                                  |
| bench_thread_pool        | 947 us                                                 | 806 us: 1.18x faster                                  |
| dulwich_log              | 75.9 ms                                                | 66.1 ms: 1.15x faster                                 |
| xml_etree_generate       | 94.2 ms                                                | 83.3 ms: 1.13x faster                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.85 ms: 1.12x faster                                 |
| json                     | 5.42 ms                                                | 4.83 ms: 1.12x faster                                 |
| json_loads               | 28.8 us                                                | 25.8 us: 1.12x faster                                 |
| regex_dna                | 222 ms                                                 | 204 ms: 1.09x faster                                  |
| create_gc_cycles         | 1.67 ms                                                | 1.54 ms: 1.09x faster                                 |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.09x faster                                  |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.09x faster                                  |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.07x faster                                  |
| regex_v8                 | 25.0 ms                                                | 23.4 ms: 1.07x faster                                 |
| sqlite_synth             | 2.93 us                                                | 2.78 us: 1.06x faster                                 |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.06x faster                                 |
| mdp                      | 2.82 sec                                               | 2.71 sec: 1.04x faster                                |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                 |
| gc_traversal             | 3.84 ms                                                | 3.93 ms: 1.02x slower                                 |
| pidigits                 | 190 ms                                                 | 194 ms: 1.02x slower                                  |
| async_generators         | 425 ms                                                 | 438 ms: 1.03x slower                                  |
| pickle_list              | 4.56 us                                                | 4.72 us: 1.04x slower                                 |
| unpickle_list            | 4.82 us                                                | 5.01 us: 1.04x slower                                 |
| unpickle                 | 14.1 us                                                | 15.0 us: 1.06x slower                                 |
| regex_effbot             | 3.23 ms                                                | 3.50 ms: 1.09x slower                                 |
| pickle_dict              | 27.3 us                                                | 31.5 us: 1.16x slower                                 |
| coverage                 | 72.8 ms                                                | 85.3 ms: 1.17x slower                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.84 ms: 1.18x slower                                 |
| telco                    | 6.54 ms                                                | 7.97 ms: 1.22x slower                                 |
| Geometric mean           | (ref)                                                  | 1.31x faster                                          |

Benchmark hidden because not significant (2): bench_mp_pool, mypy2
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.30x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.25x
