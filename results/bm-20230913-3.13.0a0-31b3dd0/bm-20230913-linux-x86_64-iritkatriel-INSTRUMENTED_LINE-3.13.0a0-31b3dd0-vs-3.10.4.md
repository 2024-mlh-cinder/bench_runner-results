
# Results vs. 3.10.4

- fork: iritkatriel
- ref: INSTRUMENTED_LINE
- machine: linux-x86_64
- commit hash: 31b3dd0
- commit date: 2023-09-13
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.62 sec: 1.21x faster                                                  |
| tornado_http   | 127 ms                                                 | 95.7 ms: 1.33x faster                                                   |
| Geometric mean | (ref)                                                  | 1.27x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.8 ms: 1.54x faster                                                   |
| float          | 111 ms                                                 | 79.1 ms: 1.40x faster                                                   |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                    |
| Geometric mean | (ref)                                                  | 1.30x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 135 ms: 1.31x faster                                                    |
| regex_dna      | 222 ms                                                 | 208 ms: 1.06x faster                                                    |
| regex_v8       | 25.0 ms                                                | 23.9 ms: 1.05x faster                                                   |
| regex_effbot   | 3.23 ms                                                | 3.48 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                  | 1.08x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 308 us: 1.48x faster                                                    |
| tomli_loads          | 2.92 sec                                               | 2.05 sec: 1.42x faster                                                  |
| json_dumps           | 13.5 ms                                                | 9.85 ms: 1.37x faster                                                   |
| unpickle_pure_python | 300 us                                                 | 221 us: 1.36x faster                                                    |
| xml_etree_process    | 74.9 ms                                                | 57.5 ms: 1.30x faster                                                   |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                                   |
| xml_etree_generate   | 94.2 ms                                                | 83.8 ms: 1.12x faster                                                   |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                    |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                                    |
| unpickle             | 14.1 us                                                | 14.2 us: 1.01x slower                                                   |
| unpickle_list        | 4.82 us                                                | 4.86 us: 1.01x slower                                                   |
| pickle               | 10.3 us                                                | 10.4 us: 1.01x slower                                                   |
| pickle_list          | 4.56 us                                                | 4.77 us: 1.05x slower                                                   |
| pickle_dict          | 27.3 us                                                | 31.7 us: 1.16x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                   |
| python_startup_no_site | 5.82 ms                                                | 6.85 ms: 1.18x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.37x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 142 us: 3.58x faster                                                    |
| generators               | 76.8 ms                                                | 30.0 ms: 2.56x faster                                                   |
| deltablue                | 7.42 ms                                                | 3.26 ms: 2.27x faster                                                   |
| asyncio_tcp              | 925 ms                                                 | 490 ms: 1.89x faster                                                    |
| chaos                    | 106 ms                                                 | 60.5 ms: 1.76x faster                                                   |
| raytrace                 | 464 ms                                                 | 269 ms: 1.72x faster                                                    |
| crypto_pyaes             | 118 ms                                                 | 69.0 ms: 1.72x faster                                                   |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                                  |
| logging_silent           | 175 ns                                                 | 104 ns: 1.68x faster                                                    |
| go                       | 229 ms                                                 | 139 ms: 1.66x faster                                                    |
| richards_super           | 90.7 ms                                                | 55.5 ms: 1.64x faster                                                   |
| scimark_monte_carlo      | 108 ms                                                 | 66.2 ms: 1.63x faster                                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.27 ms: 1.62x faster                                                   |
| scimark_sor              | 197 ms                                                 | 122 ms: 1.61x faster                                                    |
| async_tree_none          | 717 ms                                                 | 451 ms: 1.59x faster                                                    |
| hexiom                   | 9.53 ms                                                | 6.02 ms: 1.58x faster                                                   |
| sqlglot_transpile        | 2.45 ms                                                | 1.58 ms: 1.55x faster                                                   |
| nbody                    | 142 ms                                                 | 91.8 ms: 1.54x faster                                                   |
| richards                 | 74.9 ms                                                | 48.8 ms: 1.54x faster                                                   |
| pyflate                  | 673 ms                                                 | 449 ms: 1.50x faster                                                    |
| scimark_lu               | 163 ms                                                 | 109 ms: 1.49x faster                                                    |
| pickle_pure_python       | 455 us                                                 | 308 us: 1.48x faster                                                    |
| async_tree_memoization   | 854 ms                                                 | 581 ms: 1.47x faster                                                    |
| coroutines               | 31.8 ms                                                | 22.0 ms: 1.45x faster                                                   |
| async_tree_io            | 1.77 sec                                               | 1.23 sec: 1.45x faster                                                  |
| tomli_loads              | 2.92 sec                                               | 2.05 sec: 1.42x faster                                                  |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                   |
| deepcopy_memo            | 52.3 us                                                | 37.3 us: 1.40x faster                                                   |
| float                    | 111 ms                                                 | 79.1 ms: 1.40x faster                                                   |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.39x faster                                                    |
| json_dumps               | 13.5 ms                                                | 9.85 ms: 1.37x faster                                                   |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.37x faster                                                   |
| unpickle_pure_python     | 300 us                                                 | 221 us: 1.36x faster                                                    |
| logging_simple           | 8.07 us                                                | 5.99 us: 1.35x faster                                                   |
| logging_format           | 8.91 us                                                | 6.62 us: 1.35x faster                                                   |
| pprint_pformat           | 1.99 sec                                               | 1.49 sec: 1.34x faster                                                  |
| tornado_http             | 127 ms                                                 | 95.7 ms: 1.33x faster                                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 721 ms: 1.32x faster                                                    |
| comprehensions           | 26.8 us                                                | 20.4 us: 1.32x faster                                                   |
| pprint_safe_repr         | 955 ms                                                 | 726 ms: 1.32x faster                                                    |
| pycparser                | 1.50 sec                                               | 1.14 sec: 1.31x faster                                                  |
| regex_compile            | 177 ms                                                 | 135 ms: 1.31x faster                                                    |
| xml_etree_process        | 74.9 ms                                                | 57.5 ms: 1.30x faster                                                   |
| sqlglot_normalize        | 135 ms                                                 | 105 ms: 1.29x faster                                                    |
| fannkuch                 | 486 ms                                                 | 379 ms: 1.28x faster                                                    |
| nqueens                  | 100 ms                                                 | 78.2 ms: 1.28x faster                                                   |
| mypy2                    | 428 ms                                                 | 338 ms: 1.27x faster                                                    |
| deepcopy                 | 442 us                                                 | 351 us: 1.26x faster                                                    |
| unpack_sequence          | 64.7 ns                                                | 51.9 ns: 1.25x faster                                                   |
| sqlglot_optimize         | 65.3 ms                                                | 52.8 ms: 1.24x faster                                                   |
| docutils                 | 3.17 sec                                               | 2.62 sec: 1.21x faster                                                  |
| scimark_fft              | 424 ms                                                 | 354 ms: 1.20x faster                                                    |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.59 ms: 1.19x faster                                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.22 us: 1.19x faster                                                   |
| bench_thread_pool        | 947 us                                                 | 813 us: 1.16x faster                                                    |
| json                     | 5.42 ms                                                | 4.75 ms: 1.14x faster                                                   |
| dulwich_log              | 75.9 ms                                                | 66.8 ms: 1.14x faster                                                   |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                                   |
| xml_etree_generate       | 94.2 ms                                                | 83.8 ms: 1.12x faster                                                   |
| mdp                      | 2.82 sec                                               | 2.52 sec: 1.12x faster                                                  |
| create_gc_cycles         | 1.67 ms                                                | 1.52 ms: 1.10x faster                                                   |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                    |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.09x faster                                                    |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                                    |
| sqlite_synth             | 2.93 us                                                | 2.73 us: 1.07x faster                                                   |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.07x faster                                                   |
| regex_dna                | 222 ms                                                 | 208 ms: 1.06x faster                                                    |
| regex_v8                 | 25.0 ms                                                | 23.9 ms: 1.05x faster                                                   |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                                    |
| unpickle                 | 14.1 us                                                | 14.2 us: 1.01x slower                                                   |
| unpickle_list            | 4.82 us                                                | 4.86 us: 1.01x slower                                                   |
| pickle                   | 10.3 us                                                | 10.4 us: 1.01x slower                                                   |
| async_generators         | 425 ms                                                 | 432 ms: 1.02x slower                                                    |
| pickle_list              | 4.56 us                                                | 4.77 us: 1.05x slower                                                   |
| gc_traversal             | 3.84 ms                                                | 4.10 ms: 1.07x slower                                                   |
| regex_effbot             | 3.23 ms                                                | 3.48 ms: 1.08x slower                                                   |
| pickle_dict              | 27.3 us                                                | 31.7 us: 1.16x slower                                                   |
| coverage                 | 72.8 ms                                                | 85.5 ms: 1.17x slower                                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.85 ms: 1.18x slower                                                   |
| telco                    | 6.54 ms                                                | 8.11 ms: 1.24x slower                                                   |
| dask                     | 423 ms                                                 | 526 ms: 1.24x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                            |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.24x
