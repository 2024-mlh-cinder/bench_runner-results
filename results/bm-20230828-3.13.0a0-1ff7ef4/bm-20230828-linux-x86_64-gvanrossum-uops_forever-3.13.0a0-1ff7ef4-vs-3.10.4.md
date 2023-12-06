
# Results vs. 3.10.4

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: 1ff7ef4
- commit date: 2023-08-28
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.73 sec: 1.16x faster                                            |
| tornado_http   | 127 ms                                                 | 98.5 ms: 1.29x faster                                             |
| Geometric mean | (ref)                                                  | 1.23x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 102 ms: 1.38x faster                                              |
| float          | 111 ms                                                 | 84.1 ms: 1.31x faster                                             |
| pidigits       | 190 ms                                                 | 189 ms: 1.00x faster                                              |
| Geometric mean | (ref)                                                  | 1.22x faster                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 150 ms: 1.18x faster                                              |
| regex_dna      | 222 ms                                                 | 216 ms: 1.03x faster                                              |
| regex_effbot   | 3.23 ms                                                | 3.47 ms: 1.07x slower                                             |
| Geometric mean | (ref)                                                  | 1.03x faster                                                      |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 307 us: 1.48x faster                                              |
| json_dumps           | 13.5 ms                                                | 9.93 ms: 1.36x faster                                             |
| xml_etree_process    | 74.9 ms                                                | 58.8 ms: 1.27x faster                                             |
| unpickle_pure_python | 300 us                                                 | 236 us: 1.27x faster                                              |
| tomli_loads          | 2.92 sec                                               | 2.36 sec: 1.24x faster                                            |
| json_loads           | 28.8 us                                                | 25.4 us: 1.13x faster                                             |
| xml_etree_generate   | 94.2 ms                                                | 85.4 ms: 1.10x faster                                             |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                              |
| xml_etree_iterparse  | 111 ms                                                 | 106 ms: 1.05x faster                                              |
| pickle_list          | 4.56 us                                                | 4.52 us: 1.01x faster                                             |
| unpickle             | 14.1 us                                                | 14.3 us: 1.01x slower                                             |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                             |
| unpickle_list        | 4.82 us                                                | 5.08 us: 1.05x slower                                             |
| pickle_dict          | 27.3 us                                                | 31.6 us: 1.16x slower                                             |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.37 ms: 1.51x faster                                             |
| python_startup_no_site | 5.82 ms                                                | 6.86 ms: 1.18x slower                                             |
| Geometric mean         | (ref)                                                  | 1.13x faster                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.8 ms: 1.25x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 149 us: 3.43x faster                                              |
| generators               | 76.8 ms                                                | 28.9 ms: 2.66x faster                                             |
| deltablue                | 7.42 ms                                                | 3.59 ms: 2.07x faster                                             |
| asyncio_tcp              | 925 ms                                                 | 510 ms: 1.81x faster                                              |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                            |
| logging_silent           | 175 ns                                                 | 106 ns: 1.65x faster                                              |
| raytrace                 | 464 ms                                                 | 288 ms: 1.61x faster                                              |
| crypto_pyaes             | 118 ms                                                 | 73.6 ms: 1.61x faster                                             |
| richards_super           | 90.7 ms                                                | 56.5 ms: 1.61x faster                                             |
| async_tree_none          | 717 ms                                                 | 449 ms: 1.60x faster                                              |
| scimark_sor              | 197 ms                                                 | 124 ms: 1.59x faster                                              |
| scimark_monte_carlo      | 108 ms                                                 | 68.1 ms: 1.59x faster                                             |
| chaos                    | 106 ms                                                 | 67.2 ms: 1.58x faster                                             |
| sqlglot_parse            | 2.06 ms                                                | 1.32 ms: 1.56x faster                                             |
| go                       | 229 ms                                                 | 150 ms: 1.53x faster                                              |
| python_startup           | 14.2 ms                                                | 9.37 ms: 1.51x faster                                             |
| richards                 | 74.9 ms                                                | 49.8 ms: 1.51x faster                                             |
| sqlglot_transpile        | 2.45 ms                                                | 1.64 ms: 1.49x faster                                             |
| pickle_pure_python       | 455 us                                                 | 307 us: 1.48x faster                                              |
| async_tree_memoization   | 854 ms                                                 | 576 ms: 1.48x faster                                              |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.48x faster                                            |
| scimark_lu               | 163 ms                                                 | 115 ms: 1.41x faster                                              |
| nbody                    | 142 ms                                                 | 102 ms: 1.38x faster                                              |
| coroutines               | 31.8 ms                                                | 23.1 ms: 1.38x faster                                             |
| spectral_norm            | 150 ms                                                 | 109 ms: 1.37x faster                                              |
| json_dumps               | 13.5 ms                                                | 9.93 ms: 1.36x faster                                             |
| logging_simple           | 8.07 us                                                | 5.95 us: 1.36x faster                                             |
| logging_format           | 8.91 us                                                | 6.64 us: 1.34x faster                                             |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 713 ms: 1.33x faster                                              |
| unpack_sequence          | 64.7 ns                                                | 48.7 ns: 1.33x faster                                             |
| float                    | 111 ms                                                 | 84.1 ms: 1.31x faster                                             |
| pyflate                  | 673 ms                                                 | 516 ms: 1.31x faster                                              |
| pprint_pformat           | 1.99 sec                                               | 1.53 sec: 1.30x faster                                            |
| deepcopy_memo            | 52.3 us                                                | 40.4 us: 1.30x faster                                             |
| tornado_http             | 127 ms                                                 | 98.5 ms: 1.29x faster                                             |
| pprint_safe_repr         | 955 ms                                                 | 746 ms: 1.28x faster                                              |
| xml_etree_process        | 74.9 ms                                                | 58.8 ms: 1.27x faster                                             |
| unpickle_pure_python     | 300 us                                                 | 236 us: 1.27x faster                                              |
| pycparser                | 1.50 sec                                               | 1.19 sec: 1.26x faster                                            |
| hexiom                   | 9.53 ms                                                | 7.57 ms: 1.26x faster                                             |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.26x faster                                              |
| mako                     | 14.8 ms                                                | 11.8 ms: 1.25x faster                                             |
| tomli_loads              | 2.92 sec                                               | 2.36 sec: 1.24x faster                                            |
| deepcopy                 | 442 us                                                 | 359 us: 1.23x faster                                              |
| mypy2                    | 428 ms                                                 | 352 ms: 1.22x faster                                              |
| sqlglot_optimize         | 65.3 ms                                                | 54.7 ms: 1.19x faster                                             |
| deepcopy_reduce          | 3.82 us                                                | 3.22 us: 1.19x faster                                             |
| regex_compile            | 177 ms                                                 | 150 ms: 1.18x faster                                              |
| docutils                 | 3.17 sec                                               | 2.73 sec: 1.16x faster                                            |
| json_loads               | 28.8 us                                                | 25.4 us: 1.13x faster                                             |
| scimark_fft              | 424 ms                                                 | 375 ms: 1.13x faster                                              |
| create_gc_cycles         | 1.67 ms                                                | 1.48 ms: 1.13x faster                                             |
| json                     | 5.42 ms                                                | 4.88 ms: 1.11x faster                                             |
| dulwich_log              | 75.9 ms                                                | 68.7 ms: 1.11x faster                                             |
| xml_etree_generate       | 94.2 ms                                                | 85.4 ms: 1.10x faster                                             |
| fannkuch                 | 486 ms                                                 | 441 ms: 1.10x faster                                              |
| bench_thread_pool        | 947 us                                                 | 859 us: 1.10x faster                                              |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                              |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                             |
| comprehensions           | 26.8 us                                                | 25.1 us: 1.07x faster                                             |
| xml_etree_iterparse      | 111 ms                                                 | 106 ms: 1.05x faster                                              |
| pathlib                  | 20.0 ms                                                | 19.1 ms: 1.05x faster                                             |
| nqueens                  | 100 ms                                                 | 96.8 ms: 1.03x faster                                             |
| regex_dna                | 222 ms                                                 | 216 ms: 1.03x faster                                              |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.37 ms: 1.02x faster                                             |
| pickle_list              | 4.56 us                                                | 4.52 us: 1.01x faster                                             |
| mdp                      | 2.82 sec                                               | 2.81 sec: 1.00x faster                                            |
| pidigits                 | 190 ms                                                 | 189 ms: 1.00x faster                                              |
| meteor_contest           | 115 ms                                                 | 116 ms: 1.01x slower                                              |
| unpickle                 | 14.1 us                                                | 14.3 us: 1.01x slower                                             |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                             |
| unpickle_list            | 4.82 us                                                | 5.08 us: 1.05x slower                                             |
| regex_effbot             | 3.23 ms                                                | 3.47 ms: 1.07x slower                                             |
| gc_traversal             | 3.84 ms                                                | 4.19 ms: 1.09x slower                                             |
| async_generators         | 425 ms                                                 | 473 ms: 1.11x slower                                              |
| pickle_dict              | 27.3 us                                                | 31.6 us: 1.16x slower                                             |
| coverage                 | 72.8 ms                                                | 85.4 ms: 1.17x slower                                             |
| python_startup_no_site   | 5.82 ms                                                | 6.86 ms: 1.18x slower                                             |
| telco                    | 6.54 ms                                                | 8.23 ms: 1.26x slower                                             |
| dask                     | 423 ms                                                 | 536 ms: 1.27x slower                                              |
| Geometric mean           | (ref)                                                  | 1.25x faster                                                      |

Benchmark hidden because not significant (2): regex_v8, bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.22x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.16x
