
# Results vs. 3.10.4

- fork: brandtbucher
- ref: uops_enabled
- machine: linux-x86_64
- commit hash: 2ff320c
- commit date: 2023-09-15
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.71 sec: 1.17x faster                                              |
| tornado_http   | 127 ms                                                 | 97.2 ms: 1.31x faster                                               |
| Geometric mean | (ref)                                                  | 1.24x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 108 ms: 1.31x faster                                                |
| float          | 111 ms                                                 | 85.1 ms: 1.30x faster                                               |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| Geometric mean | (ref)                                                  | 1.20x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 152 ms: 1.17x faster                                                |
| regex_dna      | 222 ms                                                 | 208 ms: 1.07x faster                                                |
| regex_v8       | 25.0 ms                                                | 23.6 ms: 1.06x faster                                               |
| regex_effbot   | 3.23 ms                                                | 3.61 ms: 1.12x slower                                               |
| Geometric mean | (ref)                                                  | 1.04x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 299 us: 1.52x faster                                                |
| json_dumps           | 13.5 ms                                                | 9.84 ms: 1.38x faster                                               |
| xml_etree_process    | 74.9 ms                                                | 57.4 ms: 1.31x faster                                               |
| unpickle_pure_python | 300 us                                                 | 237 us: 1.26x faster                                                |
| tomli_loads          | 2.92 sec                                               | 2.41 sec: 1.21x faster                                              |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                               |
| xml_etree_generate   | 94.2 ms                                                | 84.0 ms: 1.12x faster                                               |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.09x faster                                                |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                                |
| pickle_list          | 4.56 us                                                | 4.71 us: 1.03x slower                                               |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                               |
| unpickle             | 14.1 us                                                | 14.8 us: 1.05x slower                                               |
| pickle_dict          | 27.3 us                                                | 32.7 us: 1.20x slower                                               |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                        |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.41x faster                                               |
| python_startup_no_site | 5.82 ms                                                | 6.85 ms: 1.18x slower                                               |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.6 ms: 1.28x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 151 us: 3.39x faster                                                |
| generators               | 76.8 ms                                                | 28.6 ms: 2.69x faster                                               |
| deltablue                | 7.42 ms                                                | 3.55 ms: 2.09x faster                                               |
| asyncio_tcp              | 925 ms                                                 | 481 ms: 1.92x faster                                                |
| logging_silent           | 175 ns                                                 | 105 ns: 1.67x faster                                                |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                              |
| raytrace                 | 464 ms                                                 | 281 ms: 1.65x faster                                                |
| richards_super           | 90.7 ms                                                | 56.2 ms: 1.61x faster                                               |
| crypto_pyaes             | 118 ms                                                 | 73.7 ms: 1.61x faster                                               |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.60x faster                                               |
| async_tree_none          | 717 ms                                                 | 448 ms: 1.60x faster                                                |
| scimark_monte_carlo      | 108 ms                                                 | 67.7 ms: 1.60x faster                                               |
| scimark_sor              | 197 ms                                                 | 124 ms: 1.59x faster                                                |
| go                       | 229 ms                                                 | 149 ms: 1.54x faster                                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                               |
| pickle_pure_python       | 455 us                                                 | 299 us: 1.52x faster                                                |
| richards                 | 74.9 ms                                                | 49.8 ms: 1.50x faster                                               |
| chaos                    | 106 ms                                                 | 70.7 ms: 1.50x faster                                               |
| async_tree_memoization   | 854 ms                                                 | 575 ms: 1.49x faster                                                |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.47x faster                                              |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                               |
| scimark_lu               | 163 ms                                                 | 115 ms: 1.41x faster                                                |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.41x faster                                               |
| pyflate                  | 673 ms                                                 | 483 ms: 1.39x faster                                                |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.39x faster                                                |
| json_dumps               | 13.5 ms                                                | 9.84 ms: 1.38x faster                                               |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 714 ms: 1.33x faster                                                |
| pprint_pformat           | 1.99 sec                                               | 1.50 sec: 1.32x faster                                              |
| tornado_http             | 127 ms                                                 | 97.2 ms: 1.31x faster                                               |
| nbody                    | 142 ms                                                 | 108 ms: 1.31x faster                                                |
| pprint_safe_repr         | 955 ms                                                 | 730 ms: 1.31x faster                                                |
| xml_etree_process        | 74.9 ms                                                | 57.4 ms: 1.31x faster                                               |
| float                    | 111 ms                                                 | 85.1 ms: 1.30x faster                                               |
| logging_simple           | 8.07 us                                                | 6.25 us: 1.29x faster                                               |
| unpack_sequence          | 64.7 ns                                                | 50.4 ns: 1.28x faster                                               |
| deepcopy_memo            | 52.3 us                                                | 40.9 us: 1.28x faster                                               |
| mako                     | 14.8 ms                                                | 11.6 ms: 1.28x faster                                               |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                                |
| logging_format           | 8.91 us                                                | 7.04 us: 1.27x faster                                               |
| unpickle_pure_python     | 300 us                                                 | 237 us: 1.26x faster                                                |
| deepcopy                 | 442 us                                                 | 356 us: 1.24x faster                                                |
| hexiom                   | 9.53 ms                                                | 7.73 ms: 1.23x faster                                               |
| mypy2                    | 428 ms                                                 | 348 ms: 1.23x faster                                                |
| pycparser                | 1.50 sec                                               | 1.23 sec: 1.23x faster                                              |
| sqlglot_optimize         | 65.3 ms                                                | 53.5 ms: 1.22x faster                                               |
| tomli_loads              | 2.92 sec                                               | 2.41 sec: 1.21x faster                                              |
| deepcopy_reduce          | 3.82 us                                                | 3.17 us: 1.21x faster                                               |
| docutils                 | 3.17 sec                                               | 2.71 sec: 1.17x faster                                              |
| regex_compile            | 177 ms                                                 | 152 ms: 1.17x faster                                                |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                               |
| bench_thread_pool        | 947 us                                                 | 837 us: 1.13x faster                                                |
| json                     | 5.42 ms                                                | 4.81 ms: 1.13x faster                                               |
| xml_etree_generate       | 94.2 ms                                                | 84.0 ms: 1.12x faster                                               |
| dulwich_log              | 75.9 ms                                                | 68.4 ms: 1.11x faster                                               |
| scimark_fft              | 424 ms                                                 | 383 ms: 1.11x faster                                                |
| fannkuch                 | 486 ms                                                 | 441 ms: 1.10x faster                                                |
| create_gc_cycles         | 1.67 ms                                                | 1.54 ms: 1.09x faster                                               |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.09x faster                                                |
| sqlite_synth             | 2.93 us                                                | 2.73 us: 1.07x faster                                               |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.07x faster                                                |
| regex_dna                | 222 ms                                                 | 208 ms: 1.07x faster                                                |
| mdp                      | 2.82 sec                                               | 2.65 sec: 1.06x faster                                              |
| regex_v8                 | 25.0 ms                                                | 23.6 ms: 1.06x faster                                               |
| comprehensions           | 26.8 us                                                | 25.3 us: 1.06x faster                                               |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.06x faster                                               |
| nqueens                  | 100 ms                                                 | 97.4 ms: 1.03x faster                                               |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| meteor_contest           | 115 ms                                                 | 114 ms: 1.01x faster                                                |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                               |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.01x slower                                               |
| pickle_list              | 4.56 us                                                | 4.71 us: 1.03x slower                                               |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                               |
| unpickle                 | 14.1 us                                                | 14.8 us: 1.05x slower                                               |
| async_generators         | 425 ms                                                 | 451 ms: 1.06x slower                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.79 ms: 1.06x slower                                               |
| regex_effbot             | 3.23 ms                                                | 3.61 ms: 1.12x slower                                               |
| python_startup_no_site   | 5.82 ms                                                | 6.85 ms: 1.18x slower                                               |
| coverage                 | 72.8 ms                                                | 85.9 ms: 1.18x slower                                               |
| pickle_dict              | 27.3 us                                                | 32.7 us: 1.20x slower                                               |
| telco                    | 6.54 ms                                                | 8.12 ms: 1.24x slower                                               |
| dask                     | 423 ms                                                 | 533 ms: 1.26x slower                                                |
| Geometric mean           | (ref)                                                  | 1.25x faster                                                        |

Benchmark hidden because not significant (1): unpickle_list
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.16x
