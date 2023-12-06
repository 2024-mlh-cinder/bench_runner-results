
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: af83d1e
- commit date: 2023-09-08
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 270 ms: 1.25x faster                                    |
| docutils       | 3.17 sec                                               | 2.72 sec: 1.16x faster                                  |
| tornado_http   | 127 ms                                                 | 99.5 ms: 1.28x faster                                   |
| Geometric mean | (ref)                                                  | 1.23x faster                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| nbody          | 142 ms                                                 | 88.7 ms: 1.60x faster                                   |
| float          | 111 ms                                                 | 79.0 ms: 1.40x faster                                   |
| pidigits       | 190 ms                                                 | 212 ms: 1.11x slower                                    |
| Geometric mean | (ref)                                                  | 1.26x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 144 ms: 1.23x faster                                    |
| regex_v8       | 25.0 ms                                                | 22.9 ms: 1.10x faster                                   |
| regex_dna      | 222 ms                                                 | 211 ms: 1.05x faster                                    |
| regex_effbot   | 3.23 ms                                                | 3.73 ms: 1.15x slower                                   |
| Geometric mean | (ref)                                                  | 1.05x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 313 us: 1.46x faster                                    |
| json_dumps           | 13.5 ms                                                | 9.72 ms: 1.39x faster                                   |
| unpickle_pure_python | 300 us                                                 | 220 us: 1.37x faster                                    |
| tomli_loads          | 2.92 sec                                               | 2.23 sec: 1.31x faster                                  |
| xml_etree_process    | 74.9 ms                                                | 59.1 ms: 1.27x faster                                   |
| json_loads           | 28.8 us                                                | 25.0 us: 1.15x faster                                   |
| xml_etree_generate   | 94.2 ms                                                | 84.7 ms: 1.11x faster                                   |
| xml_etree_iterparse  | 111 ms                                                 | 104 ms: 1.08x faster                                    |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                    |
| pickle_list          | 4.56 us                                                | 4.69 us: 1.03x slower                                   |
| pickle               | 10.3 us                                                | 10.9 us: 1.05x slower                                   |
| unpickle_list        | 4.82 us                                                | 5.11 us: 1.06x slower                                   |
| unpickle             | 14.1 us                                                | 15.6 us: 1.10x slower                                   |
| pickle_dict          | 27.3 us                                                | 32.2 us: 1.18x slower                                   |
| Geometric mean       | (ref)                                                  | 1.11x faster                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.43 ms: 1.50x faster                                   |
| python_startup_no_site | 5.82 ms                                                | 6.86 ms: 1.18x slower                                   |
| Geometric mean         | (ref)                                                  | 1.13x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.0 ms: 1.35x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230908-linux-x86_64-python-3.12-3.12.0rc2+-af83d1e |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 145 us: 3.52x faster                                    |
| generators               | 76.8 ms                                                | 30.4 ms: 2.53x faster                                   |
| deltablue                | 7.42 ms                                                | 3.48 ms: 2.13x faster                                   |
| richards_super           | 90.7 ms                                                | 49.5 ms: 1.83x faster                                   |
| asyncio_tcp              | 925 ms                                                 | 505 ms: 1.83x faster                                    |
| logging_silent           | 175 ns                                                 | 99.7 ns: 1.76x faster                                   |
| richards                 | 74.9 ms                                                | 43.8 ms: 1.71x faster                                   |
| go                       | 229 ms                                                 | 135 ms: 1.70x faster                                    |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                  |
| chaos                    | 106 ms                                                 | 63.8 ms: 1.67x faster                                   |
| scimark_sor              | 197 ms                                                 | 122 ms: 1.61x faster                                    |
| nbody                    | 142 ms                                                 | 88.7 ms: 1.60x faster                                   |
| raytrace                 | 464 ms                                                 | 293 ms: 1.58x faster                                    |
| hexiom                   | 9.53 ms                                                | 6.06 ms: 1.57x faster                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.33 ms: 1.54x faster                                   |
| async_tree_io            | 1.77 sec                                               | 1.16 sec: 1.54x faster                                  |
| async_tree_none          | 717 ms                                                 | 468 ms: 1.53x faster                                    |
| crypto_pyaes             | 118 ms                                                 | 77.7 ms: 1.52x faster                                   |
| scimark_monte_carlo      | 108 ms                                                 | 71.9 ms: 1.51x faster                                   |
| python_startup           | 14.2 ms                                                | 9.43 ms: 1.50x faster                                   |
| async_tree_memoization   | 854 ms                                                 | 571 ms: 1.50x faster                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.65 ms: 1.49x faster                                   |
| pickle_pure_python       | 455 us                                                 | 313 us: 1.46x faster                                    |
| pyflate                  | 673 ms                                                 | 463 ms: 1.45x faster                                    |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.45x faster                                    |
| spectral_norm            | 150 ms                                                 | 104 ms: 1.44x faster                                    |
| coroutines               | 31.8 ms                                                | 22.3 ms: 1.42x faster                                   |
| float                    | 111 ms                                                 | 79.0 ms: 1.40x faster                                   |
| json_dumps               | 13.5 ms                                                | 9.72 ms: 1.39x faster                                   |
| deepcopy_memo            | 52.3 us                                                | 37.9 us: 1.38x faster                                   |
| unpickle_pure_python     | 300 us                                                 | 220 us: 1.37x faster                                    |
| mako                     | 14.8 ms                                                | 11.0 ms: 1.35x faster                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 711 ms: 1.34x faster                                    |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.32x faster                                  |
| tomli_loads              | 2.92 sec                                               | 2.23 sec: 1.31x faster                                  |
| comprehensions           | 26.8 us                                                | 20.6 us: 1.30x faster                                   |
| unpack_sequence          | 64.7 ns                                                | 50.0 ns: 1.29x faster                                   |
| pprint_safe_repr         | 955 ms                                                 | 739 ms: 1.29x faster                                    |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.29x faster                                  |
| tornado_http             | 127 ms                                                 | 99.5 ms: 1.28x faster                                   |
| logging_simple           | 8.07 us                                                | 6.33 us: 1.27x faster                                   |
| xml_etree_process        | 74.9 ms                                                | 59.1 ms: 1.27x faster                                   |
| logging_format           | 8.91 us                                                | 7.02 us: 1.27x faster                                   |
| deepcopy                 | 442 us                                                 | 355 us: 1.25x faster                                    |
| 2to3                     | 336 ms                                                 | 270 ms: 1.25x faster                                    |
| mypy2                    | 428 ms                                                 | 344 ms: 1.24x faster                                    |
| nqueens                  | 100 ms                                                 | 80.8 ms: 1.24x faster                                   |
| fannkuch                 | 486 ms                                                 | 396 ms: 1.23x faster                                    |
| sqlglot_normalize        | 135 ms                                                 | 110 ms: 1.23x faster                                    |
| regex_compile            | 177 ms                                                 | 144 ms: 1.23x faster                                    |
| scimark_fft              | 424 ms                                                 | 350 ms: 1.21x faster                                    |
| sqlglot_optimize         | 65.3 ms                                                | 54.0 ms: 1.21x faster                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.20 us: 1.20x faster                                   |
| docutils                 | 3.17 sec                                               | 2.72 sec: 1.16x faster                                  |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.3 ms: 1.16x faster                                   |
| json_loads               | 28.8 us                                                | 25.0 us: 1.15x faster                                   |
| bench_thread_pool        | 947 us                                                 | 825 us: 1.15x faster                                    |
| sqlalchemy_declarative   | 165 ms                                                 | 144 ms: 1.15x faster                                    |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.77 ms: 1.14x faster                                   |
| json                     | 5.42 ms                                                | 4.80 ms: 1.13x faster                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.49 ms: 1.12x faster                                   |
| xml_etree_generate       | 94.2 ms                                                | 84.7 ms: 1.11x faster                                   |
| dulwich_log              | 75.9 ms                                                | 68.9 ms: 1.10x faster                                   |
| regex_v8                 | 25.0 ms                                                | 22.9 ms: 1.10x faster                                   |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.09x faster                                    |
| mdp                      | 2.82 sec                                               | 2.59 sec: 1.09x faster                                  |
| pathlib                  | 20.0 ms                                                | 18.5 ms: 1.08x faster                                   |
| xml_etree_iterparse      | 111 ms                                                 | 104 ms: 1.08x faster                                    |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.07x faster                                    |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                   |
| regex_dna                | 222 ms                                                 | 211 ms: 1.05x faster                                    |
| gc_traversal             | 3.84 ms                                                | 3.67 ms: 1.05x faster                                   |
| pickle_list              | 4.56 us                                                | 4.69 us: 1.03x slower                                   |
| telco                    | 6.54 ms                                                | 6.80 ms: 1.04x slower                                   |
| async_generators         | 425 ms                                                 | 442 ms: 1.04x slower                                    |
| pickle                   | 10.3 us                                                | 10.9 us: 1.05x slower                                   |
| unpickle_list            | 4.82 us                                                | 5.11 us: 1.06x slower                                   |
| unpickle                 | 14.1 us                                                | 15.6 us: 1.10x slower                                   |
| pidigits                 | 190 ms                                                 | 212 ms: 1.11x slower                                    |
| regex_effbot             | 3.23 ms                                                | 3.73 ms: 1.15x slower                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.86 ms: 1.18x slower                                   |
| pickle_dict              | 27.3 us                                                | 32.2 us: 1.18x slower                                   |
| dask                     | 423 ms                                                 | 537 ms: 1.27x slower                                    |
| coverage                 | 72.8 ms                                                | 94.7 ms: 1.30x slower                                   |
| Geometric mean           | (ref)                                                  | 1.28x faster                                            |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
