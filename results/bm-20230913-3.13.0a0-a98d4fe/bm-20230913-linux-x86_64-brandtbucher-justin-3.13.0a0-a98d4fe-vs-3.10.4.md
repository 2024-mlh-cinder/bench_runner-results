
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.71 sec: 1.17x faster                                        |
| tornado_http   | 127 ms                                                 | 97.4 ms: 1.31x faster                                         |
| Geometric mean | (ref)                                                  | 1.24x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| float          | 111 ms                                                 | 83.2 ms: 1.33x faster                                         |
| nbody          | 142 ms                                                 | 120 ms: 1.18x faster                                          |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.16x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 148 ms: 1.19x faster                                          |
| regex_dna      | 222 ms                                                 | 210 ms: 1.06x faster                                          |
| regex_v8       | 25.0 ms                                                | 24.0 ms: 1.04x faster                                         |
| regex_effbot   | 3.23 ms                                                | 3.62 ms: 1.12x slower                                         |
| Geometric mean | (ref)                                                  | 1.04x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 309 us: 1.48x faster                                          |
| json_dumps           | 13.5 ms                                                | 9.81 ms: 1.38x faster                                         |
| xml_etree_process    | 74.9 ms                                                | 58.1 ms: 1.29x faster                                         |
| unpickle_pure_python | 300 us                                                 | 234 us: 1.28x faster                                          |
| tomli_loads          | 2.92 sec                                               | 2.35 sec: 1.24x faster                                        |
| json_loads           | 28.8 us                                                | 25.1 us: 1.15x faster                                         |
| xml_etree_generate   | 94.2 ms                                                | 83.4 ms: 1.13x faster                                         |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                          |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                          |
| unpickle             | 14.1 us                                                | 14.2 us: 1.01x slower                                         |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                         |
| pickle_list          | 4.56 us                                                | 4.81 us: 1.06x slower                                         |
| pickle_dict          | 27.3 us                                                | 31.6 us: 1.16x slower                                         |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                  |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.41x faster                                         |
| python_startup_no_site | 5.82 ms                                                | 6.84 ms: 1.18x slower                                         |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.3 ms: 1.31x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 155 us: 3.30x faster                                          |
| generators               | 76.8 ms                                                | 28.1 ms: 2.73x faster                                         |
| deltablue                | 7.42 ms                                                | 3.52 ms: 2.11x faster                                         |
| asyncio_tcp              | 925 ms                                                 | 496 ms: 1.87x faster                                          |
| raytrace                 | 464 ms                                                 | 279 ms: 1.66x faster                                          |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                        |
| richards_super           | 90.7 ms                                                | 54.7 ms: 1.66x faster                                         |
| logging_silent           | 175 ns                                                 | 107 ns: 1.63x faster                                          |
| scimark_sor              | 197 ms                                                 | 122 ms: 1.61x faster                                          |
| async_tree_none          | 717 ms                                                 | 447 ms: 1.60x faster                                          |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.60x faster                                         |
| scimark_monte_carlo      | 108 ms                                                 | 68.3 ms: 1.58x faster                                         |
| crypto_pyaes             | 118 ms                                                 | 75.5 ms: 1.57x faster                                         |
| richards                 | 74.9 ms                                                | 47.9 ms: 1.56x faster                                         |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                         |
| go                       | 229 ms                                                 | 151 ms: 1.52x faster                                          |
| async_tree_memoization   | 854 ms                                                 | 572 ms: 1.49x faster                                          |
| pickle_pure_python       | 455 us                                                 | 309 us: 1.48x faster                                          |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.47x faster                                        |
| coroutines               | 31.8 ms                                                | 21.8 ms: 1.46x faster                                         |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.44x faster                                          |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.41x faster                                         |
| pyflate                  | 673 ms                                                 | 486 ms: 1.39x faster                                          |
| spectral_norm            | 150 ms                                                 | 109 ms: 1.38x faster                                          |
| json_dumps               | 13.5 ms                                                | 9.81 ms: 1.38x faster                                         |
| chaos                    | 106 ms                                                 | 78.1 ms: 1.36x faster                                         |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 713 ms: 1.33x faster                                          |
| float                    | 111 ms                                                 | 83.2 ms: 1.33x faster                                         |
| tornado_http             | 127 ms                                                 | 97.4 ms: 1.31x faster                                         |
| mako                     | 14.8 ms                                                | 11.3 ms: 1.31x faster                                         |
| xml_etree_process        | 74.9 ms                                                | 58.1 ms: 1.29x faster                                         |
| logging_format           | 8.91 us                                                | 6.92 us: 1.29x faster                                         |
| logging_simple           | 8.07 us                                                | 6.28 us: 1.28x faster                                         |
| unpickle_pure_python     | 300 us                                                 | 234 us: 1.28x faster                                          |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                          |
| hexiom                   | 9.53 ms                                                | 7.48 ms: 1.27x faster                                         |
| tomli_loads              | 2.92 sec                                               | 2.35 sec: 1.24x faster                                        |
| pycparser                | 1.50 sec                                               | 1.21 sec: 1.24x faster                                        |
| pprint_safe_repr         | 955 ms                                                 | 773 ms: 1.24x faster                                          |
| pprint_pformat           | 1.99 sec                                               | 1.61 sec: 1.23x faster                                        |
| sqlglot_optimize         | 65.3 ms                                                | 53.6 ms: 1.22x faster                                         |
| mypy2                    | 428 ms                                                 | 354 ms: 1.21x faster                                          |
| regex_compile            | 177 ms                                                 | 148 ms: 1.19x faster                                          |
| deepcopy_reduce          | 3.82 us                                                | 3.21 us: 1.19x faster                                         |
| deepcopy                 | 442 us                                                 | 374 us: 1.18x faster                                          |
| nbody                    | 142 ms                                                 | 120 ms: 1.18x faster                                          |
| docutils                 | 3.17 sec                                               | 2.71 sec: 1.17x faster                                        |
| json_loads               | 28.8 us                                                | 25.1 us: 1.15x faster                                         |
| xml_etree_generate       | 94.2 ms                                                | 83.4 ms: 1.13x faster                                         |
| json                     | 5.42 ms                                                | 4.82 ms: 1.12x faster                                         |
| scimark_fft              | 424 ms                                                 | 378 ms: 1.12x faster                                          |
| deepcopy_memo            | 52.3 us                                                | 46.7 us: 1.12x faster                                         |
| create_gc_cycles         | 1.67 ms                                                | 1.50 ms: 1.11x faster                                         |
| unpack_sequence          | 64.7 ns                                                | 58.4 ns: 1.11x faster                                         |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.93 ms: 1.11x faster                                         |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                          |
| dulwich_log              | 75.9 ms                                                | 69.5 ms: 1.09x faster                                         |
| bench_thread_pool        | 947 us                                                 | 871 us: 1.09x faster                                          |
| comprehensions           | 26.8 us                                                | 24.7 us: 1.09x faster                                         |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                          |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                         |
| fannkuch                 | 486 ms                                                 | 460 ms: 1.06x faster                                          |
| regex_dna                | 222 ms                                                 | 210 ms: 1.06x faster                                          |
| regex_v8                 | 25.0 ms                                                | 24.0 ms: 1.04x faster                                         |
| pathlib                  | 20.0 ms                                                | 19.2 ms: 1.04x faster                                         |
| gc_traversal             | 3.84 ms                                                | 3.69 ms: 1.04x faster                                         |
| meteor_contest           | 115 ms                                                 | 113 ms: 1.01x faster                                          |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                          |
| unpickle                 | 14.1 us                                                | 14.2 us: 1.01x slower                                         |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                         |
| nqueens                  | 100 ms                                                 | 103 ms: 1.03x slower                                          |
| pickle_list              | 4.56 us                                                | 4.81 us: 1.06x slower                                         |
| async_generators         | 425 ms                                                 | 463 ms: 1.09x slower                                          |
| regex_effbot             | 3.23 ms                                                | 3.62 ms: 1.12x slower                                         |
| pickle_dict              | 27.3 us                                                | 31.6 us: 1.16x slower                                         |
| coverage                 | 72.8 ms                                                | 85.3 ms: 1.17x slower                                         |
| python_startup_no_site   | 5.82 ms                                                | 6.84 ms: 1.18x slower                                         |
| telco                    | 6.54 ms                                                | 8.19 ms: 1.25x slower                                         |
| dask                     | 423 ms                                                 | 533 ms: 1.26x slower                                          |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                  |

Benchmark hidden because not significant (3): mdp, bench_mp_pool, unpickle_list
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.16x
