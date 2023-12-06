
# Results vs. 3.10.4

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: 825ff87
- commit date: 2023-09-07
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.72 sec: 1.17x faster                                            |
| tornado_http   | 127 ms                                                 | 97.8 ms: 1.30x faster                                             |
| Geometric mean | (ref)                                                  | 1.23x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 106 ms: 1.34x faster                                              |
| float          | 111 ms                                                 | 84.9 ms: 1.30x faster                                             |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                              |
| Geometric mean | (ref)                                                  | 1.21x faster                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 152 ms: 1.16x faster                                              |
| regex_dna      | 222 ms                                                 | 220 ms: 1.01x faster                                              |
| regex_v8       | 25.0 ms                                                | 25.0 ms: 1.00x faster                                             |
| regex_effbot   | 3.23 ms                                                | 3.82 ms: 1.18x slower                                             |
| Geometric mean | (ref)                                                  | 1.00x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 303 us: 1.50x faster                                              |
| json_dumps           | 13.5 ms                                                | 9.90 ms: 1.37x faster                                             |
| xml_etree_process    | 74.9 ms                                                | 56.9 ms: 1.32x faster                                             |
| unpickle_pure_python | 300 us                                                 | 238 us: 1.26x faster                                              |
| tomli_loads          | 2.92 sec                                               | 2.39 sec: 1.22x faster                                            |
| json_loads           | 28.8 us                                                | 25.2 us: 1.14x faster                                             |
| xml_etree_generate   | 94.2 ms                                                | 83.3 ms: 1.13x faster                                             |
| xml_etree_iterparse  | 111 ms                                                 | 104 ms: 1.08x faster                                              |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.06x faster                                              |
| unpickle             | 14.1 us                                                | 13.8 us: 1.02x faster                                             |
| pickle_list          | 4.56 us                                                | 4.59 us: 1.01x slower                                             |
| unpickle_list        | 4.82 us                                                | 4.87 us: 1.01x slower                                             |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                             |
| pickle_dict          | 27.3 us                                                | 31.3 us: 1.15x slower                                             |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.54 ms: 1.48x faster                                             |
| python_startup_no_site | 5.82 ms                                                | 7.01 ms: 1.20x slower                                             |
| Geometric mean         | (ref)                                                  | 1.11x faster                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.9 ms: 1.24x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 153 us: 3.35x faster                                              |
| generators               | 76.8 ms                                                | 29.8 ms: 2.58x faster                                             |
| deltablue                | 7.42 ms                                                | 3.49 ms: 2.13x faster                                             |
| asyncio_tcp              | 925 ms                                                 | 492 ms: 1.88x faster                                              |
| logging_silent           | 175 ns                                                 | 102 ns: 1.71x faster                                              |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                            |
| raytrace                 | 464 ms                                                 | 281 ms: 1.65x faster                                              |
| richards_super           | 90.7 ms                                                | 55.4 ms: 1.64x faster                                             |
| crypto_pyaes             | 118 ms                                                 | 72.4 ms: 1.64x faster                                             |
| async_tree_none          | 717 ms                                                 | 447 ms: 1.60x faster                                              |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.60x faster                                             |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.60x faster                                              |
| scimark_monte_carlo      | 108 ms                                                 | 68.7 ms: 1.58x faster                                             |
| chaos                    | 106 ms                                                 | 68.4 ms: 1.55x faster                                             |
| go                       | 229 ms                                                 | 149 ms: 1.54x faster                                              |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                             |
| pickle_pure_python       | 455 us                                                 | 303 us: 1.50x faster                                              |
| richards                 | 74.9 ms                                                | 50.0 ms: 1.50x faster                                             |
| python_startup           | 14.2 ms                                                | 9.54 ms: 1.48x faster                                             |
| async_tree_memoization   | 854 ms                                                 | 580 ms: 1.47x faster                                              |
| async_tree_io            | 1.77 sec                                               | 1.21 sec: 1.46x faster                                            |
| coroutines               | 31.8 ms                                                | 22.7 ms: 1.40x faster                                             |
| scimark_lu               | 163 ms                                                 | 118 ms: 1.38x faster                                              |
| spectral_norm            | 150 ms                                                 | 109 ms: 1.38x faster                                              |
| pyflate                  | 673 ms                                                 | 491 ms: 1.37x faster                                              |
| json_dumps               | 13.5 ms                                                | 9.90 ms: 1.37x faster                                             |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 708 ms: 1.34x faster                                              |
| nbody                    | 142 ms                                                 | 106 ms: 1.34x faster                                              |
| logging_simple           | 8.07 us                                                | 6.10 us: 1.32x faster                                             |
| xml_etree_process        | 74.9 ms                                                | 56.9 ms: 1.32x faster                                             |
| logging_format           | 8.91 us                                                | 6.82 us: 1.31x faster                                             |
| tornado_http             | 127 ms                                                 | 97.8 ms: 1.30x faster                                             |
| float                    | 111 ms                                                 | 84.9 ms: 1.30x faster                                             |
| pprint_pformat           | 1.99 sec                                               | 1.53 sec: 1.30x faster                                            |
| sqlglot_normalize        | 135 ms                                                 | 105 ms: 1.28x faster                                              |
| pprint_safe_repr         | 955 ms                                                 | 749 ms: 1.27x faster                                              |
| deepcopy_memo            | 52.3 us                                                | 41.4 us: 1.27x faster                                             |
| unpickle_pure_python     | 300 us                                                 | 238 us: 1.26x faster                                              |
| mako                     | 14.8 ms                                                | 11.9 ms: 1.24x faster                                             |
| hexiom                   | 9.53 ms                                                | 7.68 ms: 1.24x faster                                             |
| deepcopy                 | 442 us                                                 | 360 us: 1.23x faster                                              |
| mypy2                    | 428 ms                                                 | 350 ms: 1.22x faster                                              |
| tomli_loads              | 2.92 sec                                               | 2.39 sec: 1.22x faster                                            |
| sqlglot_optimize         | 65.3 ms                                                | 53.6 ms: 1.22x faster                                             |
| pycparser                | 1.50 sec                                               | 1.24 sec: 1.21x faster                                            |
| deepcopy_reduce          | 3.82 us                                                | 3.25 us: 1.18x faster                                             |
| unpack_sequence          | 64.7 ns                                                | 55.0 ns: 1.18x faster                                             |
| docutils                 | 3.17 sec                                               | 2.72 sec: 1.17x faster                                            |
| regex_compile            | 177 ms                                                 | 152 ms: 1.16x faster                                              |
| json_loads               | 28.8 us                                                | 25.2 us: 1.14x faster                                             |
| xml_etree_generate       | 94.2 ms                                                | 83.3 ms: 1.13x faster                                             |
| bench_thread_pool        | 947 us                                                 | 847 us: 1.12x faster                                              |
| dulwich_log              | 75.9 ms                                                | 68.4 ms: 1.11x faster                                             |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.10x faster                                             |
| fannkuch                 | 486 ms                                                 | 444 ms: 1.10x faster                                              |
| scimark_fft              | 424 ms                                                 | 388 ms: 1.09x faster                                              |
| xml_etree_iterparse      | 111 ms                                                 | 104 ms: 1.08x faster                                              |
| comprehensions           | 26.8 us                                                | 25.2 us: 1.07x faster                                             |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.06x faster                                              |
| pathlib                  | 20.0 ms                                                | 18.9 ms: 1.06x faster                                             |
| sqlite_synth             | 2.93 us                                                | 2.77 us: 1.06x faster                                             |
| json                     | 5.42 ms                                                | 5.15 ms: 1.05x faster                                             |
| nqueens                  | 100 ms                                                 | 96.7 ms: 1.03x faster                                             |
| unpickle                 | 14.1 us                                                | 13.8 us: 1.02x faster                                             |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                              |
| regex_dna                | 222 ms                                                 | 220 ms: 1.01x faster                                              |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                             |
| regex_v8                 | 25.0 ms                                                | 25.0 ms: 1.00x faster                                             |
| mdp                      | 2.82 sec                                               | 2.84 sec: 1.01x slower                                            |
| pickle_list              | 4.56 us                                                | 4.59 us: 1.01x slower                                             |
| unpickle_list            | 4.82 us                                                | 4.87 us: 1.01x slower                                             |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                             |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.89 ms: 1.08x slower                                             |
| async_generators         | 425 ms                                                 | 461 ms: 1.09x slower                                              |
| pickle_dict              | 27.3 us                                                | 31.3 us: 1.15x slower                                             |
| regex_effbot             | 3.23 ms                                                | 3.82 ms: 1.18x slower                                             |
| python_startup_no_site   | 5.82 ms                                                | 7.01 ms: 1.20x slower                                             |
| coverage                 | 72.8 ms                                                | 89.2 ms: 1.23x slower                                             |
| telco                    | 6.54 ms                                                | 8.25 ms: 1.26x slower                                             |
| dask                     | 423 ms                                                 | 534 ms: 1.26x slower                                              |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                      |

Benchmark hidden because not significant (2): bench_mp_pool, meteor_contest
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.16x
