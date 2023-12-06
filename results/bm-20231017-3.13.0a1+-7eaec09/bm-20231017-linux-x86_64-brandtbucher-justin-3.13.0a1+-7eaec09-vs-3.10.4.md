
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.70 sec: 1.17x faster                                         |
| tornado_http   | 127 ms                                                 | 98.0 ms: 1.30x faster                                          |
| Geometric mean | (ref)                                                  | 1.23x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.9 ms: 1.54x faster                                          |
| float          | 111 ms                                                 | 82.4 ms: 1.34x faster                                          |
| pidigits       | 190 ms                                                 | 195 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                  | 1.26x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 143 ms: 1.24x faster                                           |
| regex_dna      | 222 ms                                                 | 215 ms: 1.03x faster                                           |
| regex_v8       | 25.0 ms                                                | 25.2 ms: 1.00x slower                                          |
| regex_effbot   | 3.23 ms                                                | 3.51 ms: 1.09x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 310 us: 1.47x faster                                           |
| tomli_loads          | 2.92 sec                                               | 2.06 sec: 1.41x faster                                         |
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.28x faster                                          |
| unpickle_pure_python | 300 us                                                 | 235 us: 1.28x faster                                           |
| xml_etree_process    | 74.9 ms                                                | 61.0 ms: 1.23x faster                                          |
| xml_etree_generate   | 94.2 ms                                                | 88.3 ms: 1.07x faster                                          |
| json_loads           | 28.8 us                                                | 28.0 us: 1.03x faster                                          |
| xml_etree_iterparse  | 111 ms                                                 | 109 ms: 1.02x faster                                           |
| xml_etree_parse      | 163 ms                                                 | 161 ms: 1.01x faster                                           |
| unpickle_list        | 4.82 us                                                | 5.17 us: 1.07x slower                                          |
| unpickle             | 14.1 us                                                | 15.2 us: 1.08x slower                                          |
| pickle_list          | 4.56 us                                                | 5.00 us: 1.10x slower                                          |
| pickle               | 10.3 us                                                | 11.3 us: 1.10x slower                                          |
| pickle_dict          | 27.3 us                                                | 34.0 us: 1.25x slower                                          |
| Geometric mean       | (ref)                                                  | 1.07x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.2 ms: 1.39x faster                                          |
| python_startup_no_site | 5.82 ms                                                | 6.94 ms: 1.19x slower                                          |
| Geometric mean         | (ref)                                                  | 1.08x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.5 ms: 1.28x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 161 us: 3.16x faster                                           |
| generators               | 76.8 ms                                                | 31.4 ms: 2.45x faster                                          |
| deltablue                | 7.42 ms                                                | 3.86 ms: 1.92x faster                                          |
| asyncio_tcp              | 925 ms                                                 | 492 ms: 1.88x faster                                           |
| richards_super           | 90.7 ms                                                | 53.9 ms: 1.68x faster                                          |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                         |
| chaos                    | 106 ms                                                 | 65.0 ms: 1.63x faster                                          |
| async_tree_none          | 717 ms                                                 | 444 ms: 1.61x faster                                           |
| crypto_pyaes             | 118 ms                                                 | 74.2 ms: 1.60x faster                                          |
| raytrace                 | 464 ms                                                 | 293 ms: 1.58x faster                                           |
| richards                 | 74.9 ms                                                | 47.6 ms: 1.57x faster                                          |
| sqlglot_parse            | 2.06 ms                                                | 1.31 ms: 1.57x faster                                          |
| logging_silent           | 175 ns                                                 | 112 ns: 1.56x faster                                           |
| nbody                    | 142 ms                                                 | 91.9 ms: 1.54x faster                                          |
| go                       | 229 ms                                                 | 151 ms: 1.52x faster                                           |
| scimark_sor              | 197 ms                                                 | 131 ms: 1.50x faster                                           |
| async_tree_memoization   | 854 ms                                                 | 571 ms: 1.50x faster                                           |
| sqlglot_transpile        | 2.45 ms                                                | 1.64 ms: 1.49x faster                                          |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                         |
| scimark_monte_carlo      | 108 ms                                                 | 73.4 ms: 1.47x faster                                          |
| pickle_pure_python       | 455 us                                                 | 310 us: 1.47x faster                                           |
| tomli_loads              | 2.92 sec                                               | 2.06 sec: 1.41x faster                                         |
| python_startup           | 14.2 ms                                                | 10.2 ms: 1.39x faster                                          |
| coroutines               | 31.8 ms                                                | 23.0 ms: 1.39x faster                                          |
| pyflate                  | 673 ms                                                 | 497 ms: 1.36x faster                                           |
| hexiom                   | 9.53 ms                                                | 7.09 ms: 1.34x faster                                          |
| scimark_lu               | 163 ms                                                 | 122 ms: 1.34x faster                                           |
| float                    | 111 ms                                                 | 82.4 ms: 1.34x faster                                          |
| logging_simple           | 8.07 us                                                | 6.10 us: 1.32x faster                                          |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 720 ms: 1.32x faster                                           |
| logging_format           | 8.91 us                                                | 6.85 us: 1.30x faster                                          |
| tornado_http             | 127 ms                                                 | 98.0 ms: 1.30x faster                                          |
| spectral_norm            | 150 ms                                                 | 117 ms: 1.28x faster                                           |
| json_dumps               | 13.5 ms                                                | 10.5 ms: 1.28x faster                                          |
| mako                     | 14.8 ms                                                | 11.5 ms: 1.28x faster                                          |
| unpickle_pure_python     | 300 us                                                 | 235 us: 1.28x faster                                           |
| pycparser                | 1.50 sec                                               | 1.18 sec: 1.28x faster                                         |
| sqlglot_normalize        | 135 ms                                                 | 109 ms: 1.25x faster                                           |
| regex_compile            | 177 ms                                                 | 143 ms: 1.24x faster                                           |
| deepcopy_memo            | 52.3 us                                                | 42.5 us: 1.23x faster                                          |
| pprint_pformat           | 1.99 sec                                               | 1.62 sec: 1.23x faster                                         |
| xml_etree_process        | 74.9 ms                                                | 61.0 ms: 1.23x faster                                          |
| deepcopy                 | 442 us                                                 | 362 us: 1.22x faster                                           |
| deepcopy_reduce          | 3.82 us                                                | 3.16 us: 1.21x faster                                          |
| mypy2                    | 428 ms                                                 | 356 ms: 1.20x faster                                           |
| sqlglot_optimize         | 65.3 ms                                                | 54.7 ms: 1.19x faster                                          |
| pprint_safe_repr         | 955 ms                                                 | 801 ms: 1.19x faster                                           |
| fannkuch                 | 486 ms                                                 | 412 ms: 1.18x faster                                           |
| docutils                 | 3.17 sec                                               | 2.70 sec: 1.17x faster                                         |
| comprehensions           | 26.8 us                                                | 22.9 us: 1.17x faster                                          |
| scimark_fft              | 424 ms                                                 | 365 ms: 1.16x faster                                           |
| nqueens                  | 100 ms                                                 | 87.6 ms: 1.14x faster                                          |
| create_gc_cycles         | 1.67 ms                                                | 1.46 ms: 1.14x faster                                          |
| bench_thread_pool        | 947 us                                                 | 844 us: 1.12x faster                                           |
| unpack_sequence          | 64.7 ns                                                | 58.0 ns: 1.12x faster                                          |
| dulwich_log              | 75.9 ms                                                | 68.3 ms: 1.11x faster                                          |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.00 ms: 1.09x faster                                          |
| mdp                      | 2.82 sec                                               | 2.61 sec: 1.08x faster                                         |
| xml_etree_generate       | 94.2 ms                                                | 88.3 ms: 1.07x faster                                          |
| json                     | 5.42 ms                                                | 5.18 ms: 1.05x faster                                          |
| pathlib                  | 20.0 ms                                                | 19.2 ms: 1.04x faster                                          |
| sqlite_synth             | 2.93 us                                                | 2.82 us: 1.04x faster                                          |
| meteor_contest           | 115 ms                                                 | 111 ms: 1.03x faster                                           |
| regex_dna                | 222 ms                                                 | 215 ms: 1.03x faster                                           |
| json_loads               | 28.8 us                                                | 28.0 us: 1.03x faster                                          |
| xml_etree_iterparse      | 111 ms                                                 | 109 ms: 1.02x faster                                           |
| xml_etree_parse          | 163 ms                                                 | 161 ms: 1.01x faster                                           |
| regex_v8                 | 25.0 ms                                                | 25.2 ms: 1.00x slower                                          |
| pidigits                 | 190 ms                                                 | 195 ms: 1.03x slower                                           |
| gc_traversal             | 3.84 ms                                                | 3.95 ms: 1.03x slower                                          |
| unpickle_list            | 4.82 us                                                | 5.17 us: 1.07x slower                                          |
| unpickle                 | 14.1 us                                                | 15.2 us: 1.08x slower                                          |
| regex_effbot             | 3.23 ms                                                | 3.51 ms: 1.09x slower                                          |
| pickle_list              | 4.56 us                                                | 5.00 us: 1.10x slower                                          |
| pickle                   | 10.3 us                                                | 11.3 us: 1.10x slower                                          |
| async_generators         | 425 ms                                                 | 482 ms: 1.13x slower                                           |
| python_startup_no_site   | 5.82 ms                                                | 6.94 ms: 1.19x slower                                          |
| coverage                 | 72.8 ms                                                | 89.9 ms: 1.24x slower                                          |
| pickle_dict              | 27.3 us                                                | 34.0 us: 1.25x slower                                          |
| telco                    | 6.54 ms                                                | 8.56 ms: 1.31x slower                                          |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                   |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.18x
