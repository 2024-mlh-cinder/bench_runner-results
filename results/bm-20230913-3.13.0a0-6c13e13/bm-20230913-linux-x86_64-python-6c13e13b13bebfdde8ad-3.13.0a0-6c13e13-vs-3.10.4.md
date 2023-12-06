
# Results vs. 3.10.4

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: linux-x86_64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.31x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.60 sec: 1.22x faster                                                |
| tornado_http   | 127 ms                                                 | 95.2 ms: 1.34x faster                                                 |
| Geometric mean | (ref)                                                  | 1.28x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 88.1 ms: 1.61x faster                                                 |
| float          | 111 ms                                                 | 79.5 ms: 1.39x faster                                                 |
| pidigits       | 190 ms                                                 | 212 ms: 1.12x slower                                                  |
| Geometric mean | (ref)                                                  | 1.26x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 134 ms: 1.32x faster                                                  |
| regex_dna      | 222 ms                                                 | 205 ms: 1.08x faster                                                  |
| regex_v8       | 25.0 ms                                                | 23.6 ms: 1.06x faster                                                 |
| regex_effbot   | 3.23 ms                                                | 3.42 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                  | 1.09x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 297 us: 1.53x faster                                                  |
| tomli_loads          | 2.92 sec                                               | 1.99 sec: 1.46x faster                                                |
| unpickle_pure_python | 300 us                                                 | 212 us: 1.42x faster                                                  |
| json_dumps           | 13.5 ms                                                | 9.85 ms: 1.37x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 57.7 ms: 1.30x faster                                                 |
| json_loads           | 28.8 us                                                | 25.1 us: 1.15x faster                                                 |
| xml_etree_generate   | 94.2 ms                                                | 83.8 ms: 1.12x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 101 ms: 1.10x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                                  |
| unpickle_list        | 4.82 us                                                | 4.90 us: 1.02x slower                                                 |
| pickle_list          | 4.56 us                                                | 4.74 us: 1.04x slower                                                 |
| pickle               | 10.3 us                                                | 10.9 us: 1.05x slower                                                 |
| unpickle             | 14.1 us                                                | 15.0 us: 1.06x slower                                                 |
| pickle_dict          | 27.3 us                                                | 32.7 us: 1.20x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                 |
| python_startup_no_site | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.6 ms: 1.39x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 144 us: 3.55x faster                                                  |
| generators               | 76.8 ms                                                | 28.0 ms: 2.74x faster                                                 |
| deltablue                | 7.42 ms                                                | 3.32 ms: 2.23x faster                                                 |
| asyncio_tcp              | 925 ms                                                 | 488 ms: 1.89x faster                                                  |
| chaos                    | 106 ms                                                 | 59.9 ms: 1.78x faster                                                 |
| logging_silent           | 175 ns                                                 | 98.7 ns: 1.77x faster                                                 |
| raytrace                 | 464 ms                                                 | 268 ms: 1.73x faster                                                  |
| crypto_pyaes             | 118 ms                                                 | 68.5 ms: 1.73x faster                                                 |
| richards_super           | 90.7 ms                                                | 53.5 ms: 1.70x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                                |
| go                       | 229 ms                                                 | 141 ms: 1.63x faster                                                  |
| async_tree_none          | 717 ms                                                 | 439 ms: 1.63x faster                                                  |
| scimark_monte_carlo      | 108 ms                                                 | 66.4 ms: 1.63x faster                                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                                 |
| hexiom                   | 9.53 ms                                                | 5.91 ms: 1.61x faster                                                 |
| nbody                    | 142 ms                                                 | 88.1 ms: 1.61x faster                                                 |
| unpack_sequence          | 64.7 ns                                                | 41.1 ns: 1.58x faster                                                 |
| richards                 | 74.9 ms                                                | 47.7 ms: 1.57x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.58 ms: 1.55x faster                                                 |
| pickle_pure_python       | 455 us                                                 | 297 us: 1.53x faster                                                  |
| scimark_sor              | 197 ms                                                 | 130 ms: 1.51x faster                                                  |
| async_tree_memoization   | 854 ms                                                 | 568 ms: 1.50x faster                                                  |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.48x faster                                                |
| pyflate                  | 673 ms                                                 | 456 ms: 1.48x faster                                                  |
| scimark_lu               | 163 ms                                                 | 111 ms: 1.48x faster                                                  |
| deepcopy_memo            | 52.3 us                                                | 35.6 us: 1.47x faster                                                 |
| tomli_loads              | 2.92 sec                                               | 1.99 sec: 1.46x faster                                                |
| coroutines               | 31.8 ms                                                | 21.9 ms: 1.45x faster                                                 |
| spectral_norm            | 150 ms                                                 | 104 ms: 1.44x faster                                                  |
| unpickle_pure_python     | 300 us                                                 | 212 us: 1.42x faster                                                  |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                 |
| float                    | 111 ms                                                 | 79.5 ms: 1.39x faster                                                 |
| mako                     | 14.8 ms                                                | 10.6 ms: 1.39x faster                                                 |
| logging_format           | 8.91 us                                                | 6.42 us: 1.39x faster                                                 |
| logging_simple           | 8.07 us                                                | 5.83 us: 1.38x faster                                                 |
| json_dumps               | 13.5 ms                                                | 9.85 ms: 1.37x faster                                                 |
| pprint_pformat           | 1.99 sec                                               | 1.45 sec: 1.37x faster                                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 710 ms: 1.34x faster                                                  |
| tornado_http             | 127 ms                                                 | 95.2 ms: 1.34x faster                                                 |
| pprint_safe_repr         | 955 ms                                                 | 715 ms: 1.34x faster                                                  |
| comprehensions           | 26.8 us                                                | 20.2 us: 1.33x faster                                                 |
| regex_compile            | 177 ms                                                 | 134 ms: 1.32x faster                                                  |
| pycparser                | 1.50 sec                                               | 1.15 sec: 1.30x faster                                                |
| sqlglot_normalize        | 135 ms                                                 | 104 ms: 1.30x faster                                                  |
| xml_etree_process        | 74.9 ms                                                | 57.7 ms: 1.30x faster                                                 |
| nqueens                  | 100 ms                                                 | 78.3 ms: 1.28x faster                                                 |
| mypy2                    | 428 ms                                                 | 337 ms: 1.27x faster                                                  |
| deepcopy                 | 442 us                                                 | 348 us: 1.27x faster                                                  |
| fannkuch                 | 486 ms                                                 | 383 ms: 1.27x faster                                                  |
| sqlglot_optimize         | 65.3 ms                                                | 52.2 ms: 1.25x faster                                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.13 us: 1.22x faster                                                 |
| docutils                 | 3.17 sec                                               | 2.60 sec: 1.22x faster                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.62 ms: 1.18x faster                                                 |
| bench_thread_pool        | 947 us                                                 | 807 us: 1.17x faster                                                  |
| scimark_fft              | 424 ms                                                 | 361 ms: 1.17x faster                                                  |
| json_loads               | 28.8 us                                                | 25.1 us: 1.15x faster                                                 |
| dulwich_log              | 75.9 ms                                                | 66.2 ms: 1.15x faster                                                 |
| json                     | 5.42 ms                                                | 4.77 ms: 1.13x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 83.8 ms: 1.12x faster                                                 |
| mdp                      | 2.82 sec                                               | 2.53 sec: 1.12x faster                                                |
| xml_etree_iterparse      | 111 ms                                                 | 101 ms: 1.10x faster                                                  |
| pathlib                  | 20.0 ms                                                | 18.4 ms: 1.09x faster                                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.54 ms: 1.08x faster                                                 |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.08x faster                                                  |
| regex_dna                | 222 ms                                                 | 205 ms: 1.08x faster                                                  |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                                 |
| regex_v8                 | 25.0 ms                                                | 23.6 ms: 1.06x faster                                                 |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                                  |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                 |
| unpickle_list            | 4.82 us                                                | 4.90 us: 1.02x slower                                                 |
| pickle_list              | 4.56 us                                                | 4.74 us: 1.04x slower                                                 |
| async_generators         | 425 ms                                                 | 444 ms: 1.04x slower                                                  |
| pickle                   | 10.3 us                                                | 10.9 us: 1.05x slower                                                 |
| regex_effbot             | 3.23 ms                                                | 3.42 ms: 1.06x slower                                                 |
| unpickle                 | 14.1 us                                                | 15.0 us: 1.06x slower                                                 |
| pidigits                 | 190 ms                                                 | 212 ms: 1.12x slower                                                  |
| python_startup_no_site   | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                 |
| coverage                 | 72.8 ms                                                | 86.7 ms: 1.19x slower                                                 |
| pickle_dict              | 27.3 us                                                | 32.7 us: 1.20x slower                                                 |
| telco                    | 6.54 ms                                                | 8.03 ms: 1.23x slower                                                 |
| dask                     | 423 ms                                                 | 529 ms: 1.25x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.31x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.25x
