
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: ef4bd1b
- commit date: 2023-10-08
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 336 ms                                                 | 275 ms: 1.22x faster                                 |
| docutils       | 3.17 sec                                               | 2.75 sec: 1.15x faster                               |
| tornado_http   | 127 ms                                                 | 103 ms: 1.24x faster                                 |
| Geometric mean | (ref)                                                  | 1.20x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| nbody          | 142 ms                                                 | 95.1 ms: 1.49x faster                                |
| float          | 111 ms                                                 | 83.5 ms: 1.32x faster                                |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.26x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 149 ms: 1.19x faster                                 |
| regex_v8       | 25.0 ms                                                | 22.3 ms: 1.12x faster                                |
| regex_dna      | 222 ms                                                 | 209 ms: 1.06x faster                                 |
| regex_effbot   | 3.23 ms                                                | 3.68 ms: 1.14x slower                                |
| Geometric mean | (ref)                                                  | 1.06x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 325 us: 1.40x faster                                 |
| unpickle_pure_python | 300 us                                                 | 231 us: 1.30x faster                                 |
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.28x faster                                |
| tomli_loads          | 2.92 sec                                               | 2.32 sec: 1.26x faster                               |
| xml_etree_process    | 74.9 ms                                                | 62.0 ms: 1.21x faster                                |
| xml_etree_generate   | 94.2 ms                                                | 89.1 ms: 1.06x faster                                |
| xml_etree_iterparse  | 111 ms                                                 | 107 ms: 1.04x faster                                 |
| xml_etree_parse      | 163 ms                                                 | 161 ms: 1.01x faster                                 |
| json_loads           | 28.8 us                                                | 28.5 us: 1.01x faster                                |
| pickle_list          | 4.56 us                                                | 4.86 us: 1.07x slower                                |
| pickle               | 10.3 us                                                | 11.4 us: 1.11x slower                                |
| unpickle             | 14.1 us                                                | 15.8 us: 1.11x slower                                |
| unpickle_list        | 4.82 us                                                | 5.68 us: 1.18x slower                                |
| pickle_dict          | 27.3 us                                                | 32.7 us: 1.20x slower                                |
| Geometric mean       | (ref)                                                  | 1.06x faster                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.54 ms: 1.48x faster                                |
| python_startup_no_site | 5.82 ms                                                | 6.92 ms: 1.19x slower                                |
| Geometric mean         | (ref)                                                  | 1.12x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.7 ms: 1.26x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 156 us: 3.28x faster                                 |
| generators               | 76.8 ms                                                | 31.4 ms: 2.44x faster                                |
| deltablue                | 7.42 ms                                                | 3.70 ms: 2.01x faster                                |
| asyncio_tcp              | 925 ms                                                 | 501 ms: 1.85x faster                                 |
| richards_super           | 90.7 ms                                                | 51.1 ms: 1.78x faster                                |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.78 sec: 1.69x faster                               |
| richards                 | 74.9 ms                                                | 45.0 ms: 1.66x faster                                |
| logging_silent           | 175 ns                                                 | 107 ns: 1.64x faster                                 |
| go                       | 229 ms                                                 | 140 ms: 1.63x faster                                 |
| chaos                    | 106 ms                                                 | 66.8 ms: 1.59x faster                                |
| async_tree_io            | 1.77 sec                                               | 1.17 sec: 1.52x faster                               |
| sqlglot_parse            | 2.06 ms                                                | 1.36 ms: 1.51x faster                                |
| async_tree_none          | 717 ms                                                 | 478 ms: 1.50x faster                                 |
| raytrace                 | 464 ms                                                 | 310 ms: 1.49x faster                                 |
| scimark_sor              | 197 ms                                                 | 132 ms: 1.49x faster                                 |
| nbody                    | 142 ms                                                 | 95.1 ms: 1.49x faster                                |
| python_startup           | 14.2 ms                                                | 9.54 ms: 1.48x faster                                |
| async_tree_memoization   | 854 ms                                                 | 583 ms: 1.46x faster                                 |
| hexiom                   | 9.53 ms                                                | 6.54 ms: 1.46x faster                                |
| crypto_pyaes             | 118 ms                                                 | 81.7 ms: 1.45x faster                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.70 ms: 1.44x faster                                |
| scimark_monte_carlo      | 108 ms                                                 | 75.5 ms: 1.43x faster                                |
| pickle_pure_python       | 455 us                                                 | 325 us: 1.40x faster                                 |
| pyflate                  | 673 ms                                                 | 489 ms: 1.38x faster                                 |
| coroutines               | 31.8 ms                                                | 23.3 ms: 1.37x faster                                |
| scimark_lu               | 163 ms                                                 | 121 ms: 1.35x faster                                 |
| unpack_sequence          | 64.7 ns                                                | 48.6 ns: 1.33x faster                                |
| spectral_norm            | 150 ms                                                 | 113 ms: 1.32x faster                                 |
| float                    | 111 ms                                                 | 83.5 ms: 1.32x faster                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 727 ms: 1.31x faster                                 |
| unpickle_pure_python     | 300 us                                                 | 231 us: 1.30x faster                                 |
| deepcopy_memo            | 52.3 us                                                | 40.7 us: 1.29x faster                                |
| pprint_pformat           | 1.99 sec                                               | 1.55 sec: 1.28x faster                               |
| json_dumps               | 13.5 ms                                                | 10.6 ms: 1.28x faster                                |
| pprint_safe_repr         | 955 ms                                                 | 758 ms: 1.26x faster                                 |
| logging_simple           | 8.07 us                                                | 6.41 us: 1.26x faster                                |
| mako                     | 14.8 ms                                                | 11.7 ms: 1.26x faster                                |
| tomli_loads              | 2.92 sec                                               | 2.32 sec: 1.26x faster                               |
| logging_format           | 8.91 us                                                | 7.18 us: 1.24x faster                                |
| tornado_http             | 127 ms                                                 | 103 ms: 1.24x faster                                 |
| pycparser                | 1.50 sec                                               | 1.22 sec: 1.23x faster                               |
| comprehensions           | 26.8 us                                                | 21.9 us: 1.23x faster                                |
| sqlglot_normalize        | 135 ms                                                 | 110 ms: 1.23x faster                                 |
| 2to3                     | 336 ms                                                 | 275 ms: 1.22x faster                                 |
| xml_etree_process        | 74.9 ms                                                | 62.0 ms: 1.21x faster                                |
| nqueens                  | 100 ms                                                 | 83.7 ms: 1.19x faster                                |
| sqlglot_optimize         | 65.3 ms                                                | 54.9 ms: 1.19x faster                                |
| deepcopy                 | 442 us                                                 | 372 us: 1.19x faster                                 |
| regex_compile            | 177 ms                                                 | 149 ms: 1.19x faster                                 |
| docutils                 | 3.17 sec                                               | 2.75 sec: 1.15x faster                               |
| deepcopy_reduce          | 3.82 us                                                | 3.32 us: 1.15x faster                                |
| fannkuch                 | 486 ms                                                 | 423 ms: 1.15x faster                                 |
| dask                     | 423 ms                                                 | 373 ms: 1.13x faster                                 |
| bench_thread_pool        | 947 us                                                 | 838 us: 1.13x faster                                 |
| sqlalchemy_declarative   | 165 ms                                                 | 146 ms: 1.13x faster                                 |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.8 ms: 1.12x faster                                |
| regex_v8                 | 25.0 ms                                                | 22.3 ms: 1.12x faster                                |
| scimark_fft              | 424 ms                                                 | 378 ms: 1.12x faster                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.52 ms: 1.10x faster                                |
| dulwich_log              | 75.9 ms                                                | 69.2 ms: 1.10x faster                                |
| pathlib                  | 20.0 ms                                                | 18.5 ms: 1.08x faster                                |
| mdp                      | 2.82 sec                                               | 2.61 sec: 1.08x faster                               |
| regex_dna                | 222 ms                                                 | 209 ms: 1.06x faster                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.15 ms: 1.06x faster                                |
| xml_etree_generate       | 94.2 ms                                                | 89.1 ms: 1.06x faster                                |
| xml_etree_iterparse      | 111 ms                                                 | 107 ms: 1.04x faster                                 |
| meteor_contest           | 115 ms                                                 | 111 ms: 1.03x faster                                 |
| json                     | 5.42 ms                                                | 5.28 ms: 1.03x faster                                |
| sqlite_synth             | 2.93 us                                                | 2.87 us: 1.02x faster                                |
| xml_etree_parse          | 163 ms                                                 | 161 ms: 1.01x faster                                 |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                 |
| json_loads               | 28.8 us                                                | 28.5 us: 1.01x faster                                |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                |
| pickle_list              | 4.56 us                                                | 4.86 us: 1.07x slower                                |
| telco                    | 6.54 ms                                                | 7.15 ms: 1.09x slower                                |
| async_generators         | 425 ms                                                 | 468 ms: 1.10x slower                                 |
| pickle                   | 10.3 us                                                | 11.4 us: 1.11x slower                                |
| unpickle                 | 14.1 us                                                | 15.8 us: 1.11x slower                                |
| regex_effbot             | 3.23 ms                                                | 3.68 ms: 1.14x slower                                |
| unpickle_list            | 4.82 us                                                | 5.68 us: 1.18x slower                                |
| python_startup_no_site   | 5.82 ms                                                | 6.92 ms: 1.19x slower                                |
| pickle_dict              | 27.3 us                                                | 32.7 us: 1.20x slower                                |
| coverage                 | 72.8 ms                                                | 98.4 ms: 1.35x slower                                |
| Geometric mean           | (ref)                                                  | 1.23x faster                                         |

Benchmark hidden because not significant (2): bench_mp_pool, mypy2
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.17x
