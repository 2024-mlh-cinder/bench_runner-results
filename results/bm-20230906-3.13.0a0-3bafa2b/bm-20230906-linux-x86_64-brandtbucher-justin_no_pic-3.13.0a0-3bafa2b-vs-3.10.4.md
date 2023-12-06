
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.67 sec: 1.19x faster                                               |
| tornado_http   | 127 ms                                                 | 96.6 ms: 1.32x faster                                                |
| Geometric mean | (ref)                                                  | 1.25x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 95.5 ms: 1.48x faster                                                |
| float          | 111 ms                                                 | 81.7 ms: 1.35x faster                                                |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                  | 1.27x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 141 ms: 1.26x faster                                                 |
| regex_dna      | 222 ms                                                 | 211 ms: 1.05x faster                                                 |
| regex_v8       | 25.0 ms                                                | 25.0 ms: 1.00x faster                                                |
| regex_effbot   | 3.23 ms                                                | 3.54 ms: 1.10x slower                                                |
| Geometric mean | (ref)                                                  | 1.05x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 297 us: 1.53x faster                                                 |
| json_dumps           | 13.5 ms                                                | 9.85 ms: 1.37x faster                                                |
| tomli_loads          | 2.92 sec                                               | 2.15 sec: 1.35x faster                                               |
| unpickle_pure_python | 300 us                                                 | 228 us: 1.32x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 57.8 ms: 1.30x faster                                                |
| json_loads           | 28.8 us                                                | 25.2 us: 1.14x faster                                                |
| xml_etree_generate   | 94.2 ms                                                | 83.5 ms: 1.13x faster                                                |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.08x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.06x faster                                                 |
| pickle_list          | 4.56 us                                                | 4.46 us: 1.02x faster                                                |
| unpickle             | 14.1 us                                                | 14.1 us: 1.01x faster                                                |
| pickle               | 10.3 us                                                | 10.8 us: 1.05x slower                                                |
| pickle_dict          | 27.3 us                                                | 31.8 us: 1.17x slower                                                |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                         |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.52 ms: 1.49x faster                                                |
| python_startup_no_site | 5.82 ms                                                | 7.00 ms: 1.20x slower                                                |
| Geometric mean         | (ref)                                                  | 1.11x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.2 ms: 1.32x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 147 us: 3.48x faster                                                 |
| generators               | 76.8 ms                                                | 29.5 ms: 2.60x faster                                                |
| deltablue                | 7.42 ms                                                | 3.40 ms: 2.18x faster                                                |
| asyncio_tcp              | 925 ms                                                 | 493 ms: 1.88x faster                                                 |
| chaos                    | 106 ms                                                 | 62.6 ms: 1.70x faster                                                |
| logging_silent           | 175 ns                                                 | 104 ns: 1.69x faster                                                 |
| raytrace                 | 464 ms                                                 | 277 ms: 1.68x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                               |
| richards_super           | 90.7 ms                                                | 54.5 ms: 1.67x faster                                                |
| crypto_pyaes             | 118 ms                                                 | 71.8 ms: 1.65x faster                                                |
| async_tree_none          | 717 ms                                                 | 442 ms: 1.62x faster                                                 |
| scimark_sor              | 197 ms                                                 | 122 ms: 1.61x faster                                                 |
| scimark_monte_carlo      | 108 ms                                                 | 67.6 ms: 1.60x faster                                                |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.59x faster                                                |
| go                       | 229 ms                                                 | 145 ms: 1.58x faster                                                 |
| richards                 | 74.9 ms                                                | 47.9 ms: 1.56x faster                                                |
| pickle_pure_python       | 455 us                                                 | 297 us: 1.53x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.62 ms: 1.51x faster                                                |
| async_tree_memoization   | 854 ms                                                 | 570 ms: 1.50x faster                                                 |
| python_startup           | 14.2 ms                                                | 9.52 ms: 1.49x faster                                                |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.48x faster                                               |
| nbody                    | 142 ms                                                 | 95.5 ms: 1.48x faster                                                |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                                |
| pyflate                  | 673 ms                                                 | 469 ms: 1.44x faster                                                 |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                                 |
| hexiom                   | 9.53 ms                                                | 6.86 ms: 1.39x faster                                                |
| json_dumps               | 13.5 ms                                                | 9.85 ms: 1.37x faster                                                |
| tomli_loads              | 2.92 sec                                               | 2.15 sec: 1.35x faster                                               |
| logging_simple           | 8.07 us                                                | 5.96 us: 1.35x faster                                                |
| float                    | 111 ms                                                 | 81.7 ms: 1.35x faster                                                |
| deepcopy_memo            | 52.3 us                                                | 38.8 us: 1.35x faster                                                |
| logging_format           | 8.91 us                                                | 6.60 us: 1.35x faster                                                |
| spectral_norm            | 150 ms                                                 | 112 ms: 1.34x faster                                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 709 ms: 1.34x faster                                                 |
| tornado_http             | 127 ms                                                 | 96.6 ms: 1.32x faster                                                |
| unpickle_pure_python     | 300 us                                                 | 228 us: 1.32x faster                                                 |
| mako                     | 14.8 ms                                                | 11.2 ms: 1.32x faster                                                |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.31x faster                                               |
| xml_etree_process        | 74.9 ms                                                | 57.8 ms: 1.30x faster                                                |
| pprint_safe_repr         | 955 ms                                                 | 738 ms: 1.29x faster                                                 |
| pycparser                | 1.50 sec                                               | 1.17 sec: 1.28x faster                                               |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                                 |
| regex_compile            | 177 ms                                                 | 141 ms: 1.26x faster                                                 |
| deepcopy                 | 442 us                                                 | 353 us: 1.25x faster                                                 |
| unpack_sequence          | 64.7 ns                                                | 51.7 ns: 1.25x faster                                                |
| deepcopy_reduce          | 3.82 us                                                | 3.07 us: 1.24x faster                                                |
| mypy2                    | 428 ms                                                 | 349 ms: 1.23x faster                                                 |
| sqlglot_optimize         | 65.3 ms                                                | 53.9 ms: 1.21x faster                                                |
| fannkuch                 | 486 ms                                                 | 402 ms: 1.21x faster                                                 |
| docutils                 | 3.17 sec                                               | 2.67 sec: 1.19x faster                                               |
| scimark_fft              | 424 ms                                                 | 361 ms: 1.17x faster                                                 |
| comprehensions           | 26.8 us                                                | 23.0 us: 1.17x faster                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.71 ms: 1.16x faster                                                |
| json_loads               | 28.8 us                                                | 25.2 us: 1.14x faster                                                |
| json                     | 5.42 ms                                                | 4.75 ms: 1.14x faster                                                |
| nqueens                  | 100 ms                                                 | 87.9 ms: 1.14x faster                                                |
| create_gc_cycles         | 1.67 ms                                                | 1.48 ms: 1.13x faster                                                |
| bench_thread_pool        | 947 us                                                 | 839 us: 1.13x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 83.5 ms: 1.13x faster                                                |
| dulwich_log              | 75.9 ms                                                | 67.9 ms: 1.12x faster                                                |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.08x faster                                                 |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                                |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.06x faster                                                |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.06x faster                                                 |
| regex_dna                | 222 ms                                                 | 211 ms: 1.05x faster                                                 |
| meteor_contest           | 115 ms                                                 | 111 ms: 1.04x faster                                                 |
| pickle_list              | 4.56 us                                                | 4.46 us: 1.02x faster                                                |
| mdp                      | 2.82 sec                                               | 2.78 sec: 1.02x faster                                               |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                                 |
| unpickle                 | 14.1 us                                                | 14.1 us: 1.01x faster                                                |
| regex_v8                 | 25.0 ms                                                | 25.0 ms: 1.00x faster                                                |
| gc_traversal             | 3.84 ms                                                | 3.94 ms: 1.03x slower                                                |
| pickle                   | 10.3 us                                                | 10.8 us: 1.05x slower                                                |
| regex_effbot             | 3.23 ms                                                | 3.54 ms: 1.10x slower                                                |
| async_generators         | 425 ms                                                 | 470 ms: 1.10x slower                                                 |
| pickle_dict              | 27.3 us                                                | 31.8 us: 1.17x slower                                                |
| coverage                 | 72.8 ms                                                | 85.5 ms: 1.17x slower                                                |
| python_startup_no_site   | 5.82 ms                                                | 7.00 ms: 1.20x slower                                                |
| dask                     | 423 ms                                                 | 530 ms: 1.25x slower                                                 |
| telco                    | 6.54 ms                                                | 8.24 ms: 1.26x slower                                                |
| Geometric mean           | (ref)                                                  | 1.28x faster                                                         |

Benchmark hidden because not significant (2): unpickle_list, bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.20x
