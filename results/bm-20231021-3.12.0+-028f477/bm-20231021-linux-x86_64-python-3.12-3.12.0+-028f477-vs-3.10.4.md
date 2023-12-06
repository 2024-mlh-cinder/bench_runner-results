
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 336 ms                                                 | 275 ms: 1.22x faster                                 |
| docutils       | 3.17 sec                                               | 2.73 sec: 1.16x faster                               |
| tornado_http   | 127 ms                                                 | 100.0 ms: 1.27x faster                               |
| Geometric mean | (ref)                                                  | 1.22x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| nbody          | 142 ms                                                 | 95.1 ms: 1.49x faster                                |
| float          | 111 ms                                                 | 83.7 ms: 1.32x faster                                |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.26x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 147 ms: 1.20x faster                                 |
| regex_v8       | 25.0 ms                                                | 23.0 ms: 1.09x faster                                |
| regex_dna      | 222 ms                                                 | 209 ms: 1.06x faster                                 |
| regex_effbot   | 3.23 ms                                                | 3.63 ms: 1.12x slower                                |
| Geometric mean | (ref)                                                  | 1.05x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 324 us: 1.41x faster                                 |
| unpickle_pure_python | 300 us                                                 | 228 us: 1.32x faster                                 |
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.29x faster                                |
| tomli_loads          | 2.92 sec                                               | 2.30 sec: 1.27x faster                               |
| xml_etree_process    | 74.9 ms                                                | 62.2 ms: 1.20x faster                                |
| xml_etree_generate   | 94.2 ms                                                | 88.7 ms: 1.06x faster                                |
| xml_etree_iterparse  | 111 ms                                                 | 107 ms: 1.04x faster                                 |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                 |
| unpickle_list        | 4.82 us                                                | 5.20 us: 1.08x slower                                |
| pickle               | 10.3 us                                                | 11.6 us: 1.13x slower                                |
| unpickle             | 14.1 us                                                | 16.0 us: 1.13x slower                                |
| pickle_list          | 4.56 us                                                | 5.16 us: 1.13x slower                                |
| pickle_dict          | 27.3 us                                                | 35.4 us: 1.30x slower                                |
| Geometric mean       | (ref)                                                  | 1.05x faster                                         |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.57 ms: 1.48x faster                                |
| python_startup_no_site | 5.82 ms                                                | 6.93 ms: 1.19x slower                                |
| Geometric mean         | (ref)                                                  | 1.11x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.3 ms: 1.31x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 156 us: 3.28x faster                                 |
| generators               | 76.8 ms                                                | 30.9 ms: 2.48x faster                                |
| deltablue                | 7.42 ms                                                | 3.64 ms: 2.04x faster                                |
| richards_super           | 90.7 ms                                                | 50.1 ms: 1.81x faster                                |
| asyncio_tcp              | 925 ms                                                 | 512 ms: 1.81x faster                                 |
| richards                 | 74.9 ms                                                | 44.2 ms: 1.69x faster                                |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.78 sec: 1.69x faster                               |
| logging_silent           | 175 ns                                                 | 105 ns: 1.66x faster                                 |
| go                       | 229 ms                                                 | 140 ms: 1.64x faster                                 |
| chaos                    | 106 ms                                                 | 65.9 ms: 1.61x faster                                |
| scimark_sor              | 197 ms                                                 | 129 ms: 1.52x faster                                 |
| async_tree_io            | 1.77 sec                                               | 1.16 sec: 1.52x faster                               |
| async_tree_none          | 717 ms                                                 | 472 ms: 1.52x faster                                 |
| raytrace                 | 464 ms                                                 | 306 ms: 1.51x faster                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.36 ms: 1.51x faster                                |
| nbody                    | 142 ms                                                 | 95.1 ms: 1.49x faster                                |
| async_tree_memoization   | 854 ms                                                 | 576 ms: 1.48x faster                                 |
| crypto_pyaes             | 118 ms                                                 | 80.1 ms: 1.48x faster                                |
| python_startup           | 14.2 ms                                                | 9.57 ms: 1.48x faster                                |
| pyflate                  | 673 ms                                                 | 456 ms: 1.48x faster                                 |
| hexiom                   | 9.53 ms                                                | 6.48 ms: 1.47x faster                                |
| scimark_monte_carlo      | 108 ms                                                 | 74.3 ms: 1.46x faster                                |
| sqlglot_transpile        | 2.45 ms                                                | 1.69 ms: 1.45x faster                                |
| unpack_sequence          | 64.7 ns                                                | 46.0 ns: 1.41x faster                                |
| pickle_pure_python       | 455 us                                                 | 324 us: 1.41x faster                                 |
| scimark_lu               | 163 ms                                                 | 118 ms: 1.39x faster                                 |
| coroutines               | 31.8 ms                                                | 23.4 ms: 1.36x faster                                |
| float                    | 111 ms                                                 | 83.7 ms: 1.32x faster                                |
| spectral_norm            | 150 ms                                                 | 114 ms: 1.32x faster                                 |
| unpickle_pure_python     | 300 us                                                 | 228 us: 1.32x faster                                 |
| deepcopy_memo            | 52.3 us                                                | 39.9 us: 1.31x faster                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 725 ms: 1.31x faster                                 |
| mako                     | 14.8 ms                                                | 11.3 ms: 1.31x faster                                |
| json_dumps               | 13.5 ms                                                | 10.5 ms: 1.29x faster                                |
| pprint_pformat           | 1.99 sec                                               | 1.56 sec: 1.28x faster                               |
| tornado_http             | 127 ms                                                 | 100.0 ms: 1.27x faster                               |
| tomli_loads              | 2.92 sec                                               | 2.30 sec: 1.27x faster                               |
| logging_format           | 8.91 us                                                | 7.11 us: 1.25x faster                                |
| pprint_safe_repr         | 955 ms                                                 | 763 ms: 1.25x faster                                 |
| logging_simple           | 8.07 us                                                | 6.46 us: 1.25x faster                                |
| pycparser                | 1.50 sec                                               | 1.21 sec: 1.24x faster                               |
| comprehensions           | 26.8 us                                                | 21.6 us: 1.24x faster                                |
| 2to3                     | 336 ms                                                 | 275 ms: 1.22x faster                                 |
| sqlglot_normalize        | 135 ms                                                 | 111 ms: 1.22x faster                                 |
| xml_etree_process        | 74.9 ms                                                | 62.2 ms: 1.20x faster                                |
| deepcopy                 | 442 us                                                 | 368 us: 1.20x faster                                 |
| regex_compile            | 177 ms                                                 | 147 ms: 1.20x faster                                 |
| fannkuch                 | 486 ms                                                 | 409 ms: 1.19x faster                                 |
| nqueens                  | 100 ms                                                 | 84.2 ms: 1.19x faster                                |
| sqlglot_optimize         | 65.3 ms                                                | 55.1 ms: 1.18x faster                                |
| deepcopy_reduce          | 3.82 us                                                | 3.24 us: 1.18x faster                                |
| docutils                 | 3.17 sec                                               | 2.73 sec: 1.16x faster                               |
| create_gc_cycles         | 1.67 ms                                                | 1.46 ms: 1.15x faster                                |
| dask                     | 423 ms                                                 | 368 ms: 1.15x faster                                 |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.6 ms: 1.14x faster                                |
| sqlalchemy_declarative   | 165 ms                                                 | 146 ms: 1.13x faster                                 |
| bench_thread_pool        | 947 us                                                 | 837 us: 1.13x faster                                 |
| dulwich_log              | 75.9 ms                                                | 68.5 ms: 1.11x faster                                |
| scimark_fft              | 424 ms                                                 | 384 ms: 1.10x faster                                 |
| regex_v8                 | 25.0 ms                                                | 23.0 ms: 1.09x faster                                |
| gc_traversal             | 3.84 ms                                                | 3.55 ms: 1.08x faster                                |
| pathlib                  | 20.0 ms                                                | 18.6 ms: 1.08x faster                                |
| xml_etree_generate       | 94.2 ms                                                | 88.7 ms: 1.06x faster                                |
| regex_dna                | 222 ms                                                 | 209 ms: 1.06x faster                                 |
| xml_etree_iterparse      | 111 ms                                                 | 107 ms: 1.04x faster                                 |
| meteor_contest           | 115 ms                                                 | 110 ms: 1.04x faster                                 |
| json                     | 5.42 ms                                                | 5.23 ms: 1.04x faster                                |
| sqlite_synth             | 2.93 us                                                | 2.85 us: 1.03x faster                                |
| mdp                      | 2.82 sec                                               | 2.75 sec: 1.02x faster                               |
| xml_etree_parse          | 163 ms                                                 | 159 ms: 1.02x faster                                 |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.40 ms: 1.01x faster                                |
| unpickle_list            | 4.82 us                                                | 5.20 us: 1.08x slower                                |
| async_generators         | 425 ms                                                 | 465 ms: 1.09x slower                                 |
| telco                    | 6.54 ms                                                | 7.23 ms: 1.11x slower                                |
| regex_effbot             | 3.23 ms                                                | 3.63 ms: 1.12x slower                                |
| pickle                   | 10.3 us                                                | 11.6 us: 1.13x slower                                |
| unpickle                 | 14.1 us                                                | 16.0 us: 1.13x slower                                |
| pickle_list              | 4.56 us                                                | 5.16 us: 1.13x slower                                |
| python_startup_no_site   | 5.82 ms                                                | 6.93 ms: 1.19x slower                                |
| pickle_dict              | 27.3 us                                                | 35.4 us: 1.30x slower                                |
| coverage                 | 72.8 ms                                                | 97.8 ms: 1.34x slower                                |
| Geometric mean           | (ref)                                                  | 1.24x faster                                         |

Benchmark hidden because not significant (3): json_loads, bench_mp_pool, mypy2
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.18x
