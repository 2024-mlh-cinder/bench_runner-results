
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: b6755d8
- commit date: 2023-10-15
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 336 ms                                                 | 276 ms: 1.22x faster                                 |
| docutils       | 3.17 sec                                               | 2.78 sec: 1.14x faster                               |
| tornado_http   | 127 ms                                                 | 107 ms: 1.19x faster                                 |
| Geometric mean | (ref)                                                  | 1.18x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| nbody          | 142 ms                                                 | 93.9 ms: 1.51x faster                                |
| float          | 111 ms                                                 | 83.7 ms: 1.32x faster                                |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.26x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 148 ms: 1.20x faster                                 |
| regex_v8       | 25.0 ms                                                | 23.1 ms: 1.09x faster                                |
| regex_dna      | 222 ms                                                 | 209 ms: 1.06x faster                                 |
| regex_effbot   | 3.23 ms                                                | 3.63 ms: 1.12x slower                                |
| Geometric mean | (ref)                                                  | 1.05x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 325 us: 1.40x faster                                 |
| tomli_loads          | 2.92 sec                                               | 2.23 sec: 1.31x faster                               |
| unpickle_pure_python | 300 us                                                 | 230 us: 1.31x faster                                 |
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.29x faster                                |
| xml_etree_process    | 74.9 ms                                                | 61.0 ms: 1.23x faster                                |
| xml_etree_generate   | 94.2 ms                                                | 88.8 ms: 1.06x faster                                |
| xml_etree_iterparse  | 111 ms                                                 | 106 ms: 1.05x faster                                 |
| xml_etree_parse      | 163 ms                                                 | 162 ms: 1.01x faster                                 |
| json_loads           | 28.8 us                                                | 28.5 us: 1.01x faster                                |
| unpickle_list        | 4.82 us                                                | 5.21 us: 1.08x slower                                |
| pickle               | 10.3 us                                                | 11.4 us: 1.11x slower                                |
| pickle_list          | 4.56 us                                                | 5.09 us: 1.12x slower                                |
| unpickle             | 14.1 us                                                | 15.9 us: 1.13x slower                                |
| pickle_dict          | 27.3 us                                                | 35.1 us: 1.29x slower                                |
| Geometric mean       | (ref)                                                  | 1.06x faster                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.70 ms: 1.46x faster                                |
| python_startup_no_site | 5.82 ms                                                | 7.00 ms: 1.20x slower                                |
| Geometric mean         | (ref)                                                  | 1.10x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.3 ms: 1.31x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 157 us: 3.26x faster                                 |
| generators               | 76.8 ms                                                | 31.5 ms: 2.43x faster                                |
| deltablue                | 7.42 ms                                                | 3.68 ms: 2.02x faster                                |
| asyncio_tcp              | 925 ms                                                 | 509 ms: 1.82x faster                                 |
| richards_super           | 90.7 ms                                                | 51.0 ms: 1.78x faster                                |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.78 sec: 1.69x faster                               |
| richards                 | 74.9 ms                                                | 45.0 ms: 1.66x faster                                |
| go                       | 229 ms                                                 | 143 ms: 1.61x faster                                 |
| logging_silent           | 175 ns                                                 | 109 ns: 1.60x faster                                 |
| chaos                    | 106 ms                                                 | 66.6 ms: 1.60x faster                                |
| async_tree_io            | 1.77 sec                                               | 1.16 sec: 1.53x faster                               |
| async_tree_none          | 717 ms                                                 | 471 ms: 1.52x faster                                 |
| nbody                    | 142 ms                                                 | 93.9 ms: 1.51x faster                                |
| scimark_sor              | 197 ms                                                 | 130 ms: 1.51x faster                                 |
| raytrace                 | 464 ms                                                 | 310 ms: 1.50x faster                                 |
| async_tree_memoization   | 854 ms                                                 | 576 ms: 1.48x faster                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.39 ms: 1.48x faster                                |
| scimark_monte_carlo      | 108 ms                                                 | 73.4 ms: 1.47x faster                                |
| pyflate                  | 673 ms                                                 | 458 ms: 1.47x faster                                 |
| hexiom                   | 9.53 ms                                                | 6.49 ms: 1.47x faster                                |
| python_startup           | 14.2 ms                                                | 9.70 ms: 1.46x faster                                |
| crypto_pyaes             | 118 ms                                                 | 82.8 ms: 1.43x faster                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.72 ms: 1.42x faster                                |
| coroutines               | 31.8 ms                                                | 22.5 ms: 1.41x faster                                |
| pickle_pure_python       | 455 us                                                 | 325 us: 1.40x faster                                 |
| scimark_lu               | 163 ms                                                 | 118 ms: 1.39x faster                                 |
| spectral_norm            | 150 ms                                                 | 112 ms: 1.34x faster                                 |
| float                    | 111 ms                                                 | 83.7 ms: 1.32x faster                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 725 ms: 1.31x faster                                 |
| tomli_loads              | 2.92 sec                                               | 2.23 sec: 1.31x faster                               |
| mako                     | 14.8 ms                                                | 11.3 ms: 1.31x faster                                |
| unpickle_pure_python     | 300 us                                                 | 230 us: 1.31x faster                                 |
| json_dumps               | 13.5 ms                                                | 10.5 ms: 1.29x faster                                |
| deepcopy_memo            | 52.3 us                                                | 40.8 us: 1.28x faster                                |
| pprint_pformat           | 1.99 sec                                               | 1.55 sec: 1.28x faster                               |
| pycparser                | 1.50 sec                                               | 1.18 sec: 1.27x faster                               |
| comprehensions           | 26.8 us                                                | 21.5 us: 1.25x faster                                |
| pprint_safe_repr         | 955 ms                                                 | 765 ms: 1.25x faster                                 |
| logging_simple           | 8.07 us                                                | 6.54 us: 1.23x faster                                |
| xml_etree_process        | 74.9 ms                                                | 61.0 ms: 1.23x faster                                |
| fannkuch                 | 486 ms                                                 | 397 ms: 1.22x faster                                 |
| logging_format           | 8.91 us                                                | 7.30 us: 1.22x faster                                |
| 2to3                     | 336 ms                                                 | 276 ms: 1.22x faster                                 |
| unpack_sequence          | 64.7 ns                                                | 53.3 ns: 1.21x faster                                |
| sqlglot_normalize        | 135 ms                                                 | 112 ms: 1.21x faster                                 |
| regex_compile            | 177 ms                                                 | 148 ms: 1.20x faster                                 |
| nqueens                  | 100 ms                                                 | 83.8 ms: 1.19x faster                                |
| deepcopy                 | 442 us                                                 | 372 us: 1.19x faster                                 |
| tornado_http             | 127 ms                                                 | 107 ms: 1.19x faster                                 |
| sqlglot_optimize         | 65.3 ms                                                | 55.1 ms: 1.18x faster                                |
| deepcopy_reduce          | 3.82 us                                                | 3.32 us: 1.15x faster                                |
| scimark_fft              | 424 ms                                                 | 370 ms: 1.15x faster                                 |
| docutils                 | 3.17 sec                                               | 2.78 sec: 1.14x faster                               |
| dask                     | 423 ms                                                 | 375 ms: 1.13x faster                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.49 ms: 1.12x faster                                |
| sqlalchemy_declarative   | 165 ms                                                 | 148 ms: 1.12x faster                                 |
| bench_thread_pool        | 947 us                                                 | 852 us: 1.11x faster                                 |
| mdp                      | 2.82 sec                                               | 2.57 sec: 1.10x faster                               |
| regex_v8                 | 25.0 ms                                                | 23.1 ms: 1.09x faster                                |
| meteor_contest           | 115 ms                                                 | 108 ms: 1.06x faster                                 |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.06x faster                                |
| xml_etree_generate       | 94.2 ms                                                | 88.8 ms: 1.06x faster                                |
| regex_dna                | 222 ms                                                 | 209 ms: 1.06x faster                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.17 ms: 1.06x faster                                |
| xml_etree_iterparse      | 111 ms                                                 | 106 ms: 1.05x faster                                 |
| json                     | 5.42 ms                                                | 5.28 ms: 1.03x faster                                |
| dulwich_log              | 75.9 ms                                                | 74.4 ms: 1.02x faster                                |
| sqlite_synth             | 2.93 us                                                | 2.89 us: 1.02x faster                                |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                 |
| xml_etree_parse          | 163 ms                                                 | 162 ms: 1.01x faster                                 |
| json_loads               | 28.8 us                                                | 28.5 us: 1.01x faster                                |
| gc_traversal             | 3.84 ms                                                | 4.11 ms: 1.07x slower                                |
| telco                    | 6.54 ms                                                | 7.03 ms: 1.07x slower                                |
| unpickle_list            | 4.82 us                                                | 5.21 us: 1.08x slower                                |
| async_generators         | 425 ms                                                 | 462 ms: 1.09x slower                                 |
| pickle                   | 10.3 us                                                | 11.4 us: 1.11x slower                                |
| pickle_list              | 4.56 us                                                | 5.09 us: 1.12x slower                                |
| regex_effbot             | 3.23 ms                                                | 3.63 ms: 1.12x slower                                |
| unpickle                 | 14.1 us                                                | 15.9 us: 1.13x slower                                |
| python_startup_no_site   | 5.82 ms                                                | 7.00 ms: 1.20x slower                                |
| pickle_dict              | 27.3 us                                                | 35.1 us: 1.29x slower                                |
| coverage                 | 72.8 ms                                                | 98.5 ms: 1.35x slower                                |
| Geometric mean           | (ref)                                                  | 1.23x faster                                         |

Benchmark hidden because not significant (3): sqlalchemy_imperative, bench_mp_pool, mypy2
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.18x
