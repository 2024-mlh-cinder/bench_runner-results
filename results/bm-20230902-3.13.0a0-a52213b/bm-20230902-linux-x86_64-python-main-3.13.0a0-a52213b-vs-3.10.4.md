
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.62 sec: 1.21x faster                                |
| tornado_http   | 127 ms                                                 | 95.0 ms: 1.34x faster                                 |
| Geometric mean | (ref)                                                  | 1.27x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 142 ms                                                 | 89.3 ms: 1.59x faster                                 |
| float          | 111 ms                                                 | 78.7 ms: 1.41x faster                                 |
| pidigits       | 190 ms                                                 | 203 ms: 1.07x slower                                  |
| Geometric mean | (ref)                                                  | 1.28x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 135 ms: 1.31x faster                                  |
| regex_v8       | 25.0 ms                                                | 24.6 ms: 1.02x faster                                 |
| regex_dna      | 222 ms                                                 | 221 ms: 1.01x faster                                  |
| regex_effbot   | 3.23 ms                                                | 3.68 ms: 1.14x slower                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 297 us: 1.53x faster                                  |
| unpickle_pure_python | 300 us                                                 | 213 us: 1.41x faster                                  |
| tomli_loads          | 2.92 sec                                               | 2.12 sec: 1.38x faster                                |
| json_dumps           | 13.5 ms                                                | 9.91 ms: 1.37x faster                                 |
| xml_etree_process    | 74.9 ms                                                | 56.6 ms: 1.32x faster                                 |
| xml_etree_generate   | 94.2 ms                                                | 82.0 ms: 1.15x faster                                 |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                 |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 150 ms: 1.09x faster                                  |
| unpickle             | 14.1 us                                                | 13.8 us: 1.02x faster                                 |
| unpickle_list        | 4.82 us                                                | 4.84 us: 1.01x slower                                 |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                 |
| pickle_list          | 4.56 us                                                | 4.74 us: 1.04x slower                                 |
| pickle_dict          | 27.3 us                                                | 32.6 us: 1.20x slower                                 |
| Geometric mean       | (ref)                                                  | 1.15x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.43 ms: 1.50x faster                                 |
| python_startup_no_site | 5.82 ms                                                | 6.93 ms: 1.19x slower                                 |
| Geometric mean         | (ref)                                                  | 1.12x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.0 ms: 1.34x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 146 us: 3.50x faster                                  |
| generators               | 76.8 ms                                                | 28.9 ms: 2.66x faster                                 |
| deltablue                | 7.42 ms                                                | 3.25 ms: 2.28x faster                                 |
| asyncio_tcp              | 925 ms                                                 | 485 ms: 1.91x faster                                  |
| chaos                    | 106 ms                                                 | 59.7 ms: 1.78x faster                                 |
| richards_super           | 90.7 ms                                                | 53.3 ms: 1.70x faster                                 |
| logging_silent           | 175 ns                                                 | 103 ns: 1.70x faster                                  |
| crypto_pyaes             | 118 ms                                                 | 70.3 ms: 1.69x faster                                 |
| raytrace                 | 464 ms                                                 | 276 ms: 1.68x faster                                  |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.67x faster                                |
| scimark_sor              | 197 ms                                                 | 118 ms: 1.66x faster                                  |
| go                       | 229 ms                                                 | 138 ms: 1.66x faster                                  |
| async_tree_none          | 717 ms                                                 | 438 ms: 1.64x faster                                  |
| scimark_monte_carlo      | 108 ms                                                 | 66.4 ms: 1.63x faster                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.27 ms: 1.63x faster                                 |
| richards                 | 74.9 ms                                                | 47.0 ms: 1.59x faster                                 |
| nbody                    | 142 ms                                                 | 89.3 ms: 1.59x faster                                 |
| hexiom                   | 9.53 ms                                                | 6.01 ms: 1.59x faster                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.57 ms: 1.56x faster                                 |
| pickle_pure_python       | 455 us                                                 | 297 us: 1.53x faster                                  |
| pyflate                  | 673 ms                                                 | 442 ms: 1.52x faster                                  |
| async_tree_memoization   | 854 ms                                                 | 567 ms: 1.51x faster                                  |
| scimark_lu               | 163 ms                                                 | 109 ms: 1.50x faster                                  |
| python_startup           | 14.2 ms                                                | 9.43 ms: 1.50x faster                                 |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                |
| coroutines               | 31.8 ms                                                | 22.2 ms: 1.43x faster                                 |
| deepcopy_memo            | 52.3 us                                                | 36.9 us: 1.42x faster                                 |
| unpack_sequence          | 64.7 ns                                                | 45.7 ns: 1.42x faster                                 |
| unpickle_pure_python     | 300 us                                                 | 213 us: 1.41x faster                                  |
| float                    | 111 ms                                                 | 78.7 ms: 1.41x faster                                 |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.38x faster                                  |
| tomli_loads              | 2.92 sec                                               | 2.12 sec: 1.38x faster                                |
| logging_format           | 8.91 us                                                | 6.48 us: 1.38x faster                                 |
| logging_simple           | 8.07 us                                                | 5.87 us: 1.38x faster                                 |
| json_dumps               | 13.5 ms                                                | 9.91 ms: 1.37x faster                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 705 ms: 1.35x faster                                  |
| tornado_http             | 127 ms                                                 | 95.0 ms: 1.34x faster                                 |
| mako                     | 14.8 ms                                                | 11.0 ms: 1.34x faster                                 |
| pprint_pformat           | 1.99 sec                                               | 1.49 sec: 1.34x faster                                |
| xml_etree_process        | 74.9 ms                                                | 56.6 ms: 1.32x faster                                 |
| pprint_safe_repr         | 955 ms                                                 | 730 ms: 1.31x faster                                  |
| regex_compile            | 177 ms                                                 | 135 ms: 1.31x faster                                  |
| sqlglot_normalize        | 135 ms                                                 | 104 ms: 1.30x faster                                  |
| comprehensions           | 26.8 us                                                | 20.7 us: 1.30x faster                                 |
| deepcopy                 | 442 us                                                 | 345 us: 1.28x faster                                  |
| fannkuch                 | 486 ms                                                 | 382 ms: 1.27x faster                                  |
| mypy2                    | 428 ms                                                 | 339 ms: 1.27x faster                                  |
| nqueens                  | 100 ms                                                 | 79.6 ms: 1.26x faster                                 |
| pycparser                | 1.50 sec                                               | 1.20 sec: 1.25x faster                                |
| sqlglot_optimize         | 65.3 ms                                                | 52.4 ms: 1.25x faster                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.09 us: 1.24x faster                                 |
| docutils                 | 3.17 sec                                               | 2.62 sec: 1.21x faster                                |
| scimark_fft              | 424 ms                                                 | 355 ms: 1.19x faster                                  |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.64 ms: 1.18x faster                                 |
| bench_thread_pool        | 947 us                                                 | 819 us: 1.16x faster                                  |
| xml_etree_generate       | 94.2 ms                                                | 82.0 ms: 1.15x faster                                 |
| dulwich_log              | 75.9 ms                                                | 66.7 ms: 1.14x faster                                 |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.49 ms: 1.12x faster                                 |
| json                     | 5.42 ms                                                | 4.94 ms: 1.10x faster                                 |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                  |
| xml_etree_parse          | 163 ms                                                 | 150 ms: 1.09x faster                                  |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.08x faster                                  |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.06x faster                                 |
| sqlite_synth             | 2.93 us                                                | 2.77 us: 1.06x faster                                 |
| mdp                      | 2.82 sec                                               | 2.73 sec: 1.03x faster                                |
| unpickle                 | 14.1 us                                                | 13.8 us: 1.02x faster                                 |
| regex_v8                 | 25.0 ms                                                | 24.6 ms: 1.02x faster                                 |
| regex_dna                | 222 ms                                                 | 221 ms: 1.01x faster                                  |
| unpickle_list            | 4.82 us                                                | 4.84 us: 1.01x slower                                 |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                 |
| pickle_list              | 4.56 us                                                | 4.74 us: 1.04x slower                                 |
| async_generators         | 425 ms                                                 | 448 ms: 1.05x slower                                  |
| pidigits                 | 190 ms                                                 | 203 ms: 1.07x slower                                  |
| gc_traversal             | 3.84 ms                                                | 4.18 ms: 1.09x slower                                 |
| regex_effbot             | 3.23 ms                                                | 3.68 ms: 1.14x slower                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.93 ms: 1.19x slower                                 |
| coverage                 | 72.8 ms                                                | 86.9 ms: 1.19x slower                                 |
| pickle_dict              | 27.3 us                                                | 32.6 us: 1.20x slower                                 |
| telco                    | 6.54 ms                                                | 8.00 ms: 1.22x slower                                 |
| dask                     | 423 ms                                                 | 523 ms: 1.24x slower                                  |
| Geometric mean           | (ref)                                                  | 1.30x faster                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.24x
