
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 28351a0
- commit date: 2023-09-22
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.69 sec: 1.18x faster                                        |
| tornado_http   | 127 ms                                                 | 97.0 ms: 1.31x faster                                         |
| Geometric mean | (ref)                                                  | 1.24x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 90.1 ms: 1.57x faster                                         |
| float          | 111 ms                                                 | 83.0 ms: 1.33x faster                                         |
| pidigits       | 190 ms                                                 | 189 ms: 1.00x faster                                          |
| Geometric mean | (ref)                                                  | 1.28x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 144 ms: 1.23x faster                                          |
| regex_dna      | 222 ms                                                 | 207 ms: 1.07x faster                                          |
| regex_v8       | 25.0 ms                                                | 23.5 ms: 1.06x faster                                         |
| regex_effbot   | 3.23 ms                                                | 3.53 ms: 1.09x slower                                         |
| Geometric mean | (ref)                                                  | 1.06x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 300 us: 1.52x faster                                          |
| tomli_loads          | 2.92 sec                                               | 2.07 sec: 1.41x faster                                        |
| json_dumps           | 13.5 ms                                                | 9.76 ms: 1.39x faster                                         |
| unpickle_pure_python | 300 us                                                 | 228 us: 1.32x faster                                          |
| xml_etree_process    | 74.9 ms                                                | 57.6 ms: 1.30x faster                                         |
| json_loads           | 28.8 us                                                | 24.9 us: 1.16x faster                                         |
| xml_etree_generate   | 94.2 ms                                                | 84.2 ms: 1.12x faster                                         |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                          |
| pickle               | 10.3 us                                                | 10.4 us: 1.01x slower                                         |
| unpickle_list        | 4.82 us                                                | 4.91 us: 1.02x slower                                         |
| unpickle             | 14.1 us                                                | 14.6 us: 1.03x slower                                         |
| pickle_list          | 4.56 us                                                | 4.82 us: 1.06x slower                                         |
| pickle_dict          | 27.3 us                                                | 32.0 us: 1.18x slower                                         |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                         |
| python_startup_no_site | 5.82 ms                                                | 6.89 ms: 1.18x slower                                         |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.1 ms: 1.33x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 148 us: 3.44x faster                                          |
| generators               | 76.8 ms                                                | 28.5 ms: 2.69x faster                                         |
| deltablue                | 7.42 ms                                                | 3.42 ms: 2.17x faster                                         |
| asyncio_tcp              | 925 ms                                                 | 502 ms: 1.84x faster                                          |
| richards_super           | 90.7 ms                                                | 53.6 ms: 1.69x faster                                         |
| raytrace                 | 464 ms                                                 | 276 ms: 1.68x faster                                          |
| logging_silent           | 175 ns                                                 | 104 ns: 1.68x faster                                          |
| crypto_pyaes             | 118 ms                                                 | 71.1 ms: 1.67x faster                                         |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                        |
| async_tree_none          | 717 ms                                                 | 443 ms: 1.62x faster                                          |
| chaos                    | 106 ms                                                 | 65.8 ms: 1.62x faster                                         |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.60x faster                                          |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.60x faster                                         |
| richards                 | 74.9 ms                                                | 47.4 ms: 1.58x faster                                         |
| scimark_monte_carlo      | 108 ms                                                 | 68.8 ms: 1.57x faster                                         |
| nbody                    | 142 ms                                                 | 90.1 ms: 1.57x faster                                         |
| go                       | 229 ms                                                 | 148 ms: 1.55x faster                                          |
| pickle_pure_python       | 455 us                                                 | 300 us: 1.52x faster                                          |
| sqlglot_transpile        | 2.45 ms                                                | 1.61 ms: 1.52x faster                                         |
| async_tree_memoization   | 854 ms                                                 | 568 ms: 1.50x faster                                          |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.48x faster                                        |
| coroutines               | 31.8 ms                                                | 21.7 ms: 1.47x faster                                         |
| pyflate                  | 673 ms                                                 | 464 ms: 1.45x faster                                          |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                          |
| tomli_loads              | 2.92 sec                                               | 2.07 sec: 1.41x faster                                        |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                         |
| hexiom                   | 9.53 ms                                                | 6.84 ms: 1.39x faster                                         |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.39x faster                                          |
| json_dumps               | 13.5 ms                                                | 9.76 ms: 1.39x faster                                         |
| unpack_sequence          | 64.7 ns                                                | 47.5 ns: 1.36x faster                                         |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 709 ms: 1.34x faster                                          |
| deepcopy_memo            | 52.3 us                                                | 39.2 us: 1.34x faster                                         |
| float                    | 111 ms                                                 | 83.0 ms: 1.33x faster                                         |
| mako                     | 14.8 ms                                                | 11.1 ms: 1.33x faster                                         |
| unpickle_pure_python     | 300 us                                                 | 228 us: 1.32x faster                                          |
| tornado_http             | 127 ms                                                 | 97.0 ms: 1.31x faster                                         |
| logging_simple           | 8.07 us                                                | 6.16 us: 1.31x faster                                         |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                        |
| logging_format           | 8.91 us                                                | 6.81 us: 1.31x faster                                         |
| xml_etree_process        | 74.9 ms                                                | 57.6 ms: 1.30x faster                                         |
| pprint_safe_repr         | 955 ms                                                 | 738 ms: 1.29x faster                                          |
| pycparser                | 1.50 sec                                               | 1.17 sec: 1.28x faster                                        |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.26x faster                                          |
| deepcopy                 | 442 us                                                 | 356 us: 1.24x faster                                          |
| regex_compile            | 177 ms                                                 | 144 ms: 1.23x faster                                          |
| scimark_fft              | 424 ms                                                 | 347 ms: 1.22x faster                                          |
| mypy2                    | 428 ms                                                 | 352 ms: 1.22x faster                                          |
| sqlglot_optimize         | 65.3 ms                                                | 53.9 ms: 1.21x faster                                         |
| deepcopy_reduce          | 3.82 us                                                | 3.16 us: 1.21x faster                                         |
| fannkuch                 | 486 ms                                                 | 405 ms: 1.20x faster                                          |
| docutils                 | 3.17 sec                                               | 2.69 sec: 1.18x faster                                        |
| json_loads               | 28.8 us                                                | 24.9 us: 1.16x faster                                         |
| comprehensions           | 26.8 us                                                | 23.3 us: 1.15x faster                                         |
| nqueens                  | 100 ms                                                 | 87.1 ms: 1.15x faster                                         |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.77 ms: 1.14x faster                                         |
| bench_thread_pool        | 947 us                                                 | 837 us: 1.13x faster                                          |
| xml_etree_generate       | 94.2 ms                                                | 84.2 ms: 1.12x faster                                         |
| dulwich_log              | 75.9 ms                                                | 68.4 ms: 1.11x faster                                         |
| json                     | 5.42 ms                                                | 4.90 ms: 1.10x faster                                         |
| mdp                      | 2.82 sec                                               | 2.58 sec: 1.09x faster                                        |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                         |
| pathlib                  | 20.0 ms                                                | 18.5 ms: 1.08x faster                                         |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                          |
| regex_dna                | 222 ms                                                 | 207 ms: 1.07x faster                                          |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.07x faster                                          |
| regex_v8                 | 25.0 ms                                                | 23.5 ms: 1.06x faster                                         |
| sqlite_synth             | 2.93 us                                                | 2.78 us: 1.06x faster                                         |
| meteor_contest           | 115 ms                                                 | 110 ms: 1.05x faster                                          |
| pidigits                 | 190 ms                                                 | 189 ms: 1.00x faster                                          |
| pickle                   | 10.3 us                                                | 10.4 us: 1.01x slower                                         |
| unpickle_list            | 4.82 us                                                | 4.91 us: 1.02x slower                                         |
| unpickle                 | 14.1 us                                                | 14.6 us: 1.03x slower                                         |
| pickle_list              | 4.56 us                                                | 4.82 us: 1.06x slower                                         |
| async_generators         | 425 ms                                                 | 460 ms: 1.08x slower                                          |
| regex_effbot             | 3.23 ms                                                | 3.53 ms: 1.09x slower                                         |
| gc_traversal             | 3.84 ms                                                | 4.36 ms: 1.13x slower                                         |
| coverage                 | 72.8 ms                                                | 84.9 ms: 1.17x slower                                         |
| pickle_dict              | 27.3 us                                                | 32.0 us: 1.18x slower                                         |
| python_startup_no_site   | 5.82 ms                                                | 6.89 ms: 1.18x slower                                         |
| telco                    | 6.54 ms                                                | 8.16 ms: 1.25x slower                                         |
| dask                     | 423 ms                                                 | 533 ms: 1.26x slower                                          |
| Geometric mean           | (ref)                                                  | 1.28x faster                                                  |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
