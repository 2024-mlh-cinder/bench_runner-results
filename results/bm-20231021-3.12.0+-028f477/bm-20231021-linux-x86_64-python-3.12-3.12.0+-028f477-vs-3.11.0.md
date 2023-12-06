
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.00x slower
- HPT reliability: 99.94%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 259 ms                                                 | 275 ms: 1.06x slower                                 |
| docutils       | 2.63 sec                                               | 2.73 sec: 1.04x slower                               |
| tornado_http   | 96.3 ms                                                | 100.0 ms: 1.04x slower                               |
| Geometric mean | (ref)                                                  | 1.05x slower                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                 |
| nbody          | 93.1 ms                                                | 95.1 ms: 1.02x slower                                |
| float          | 77.2 ms                                                | 83.7 ms: 1.08x slower                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.63 ms: 1.10x faster                                |
| regex_dna      | 204 ms                                                 | 209 ms: 1.03x slower                                 |
| regex_v8       | 22.0 ms                                                | 23.0 ms: 1.04x slower                                |
| regex_compile  | 138 ms                                                 | 147 ms: 1.07x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|---------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps          | 12.6 ms                                                | 10.5 ms: 1.20x faster                                |
| xml_etree_iterparse | 104 ms                                                 | 107 ms: 1.03x slower                                 |
| tomli_loads         | 2.22 sec                                               | 2.30 sec: 1.04x slower                               |
| pickle_pure_python  | 306 us                                                 | 324 us: 1.06x slower                                 |
| unpickle_list       | 4.91 us                                                | 5.20 us: 1.06x slower                                |
| json_loads          | 26.5 us                                                | 28.7 us: 1.09x slower                                |
| pickle_dict         | 31.1 us                                                | 35.4 us: 1.14x slower                                |
| pickle              | 10.1 us                                                | 11.6 us: 1.15x slower                                |
| xml_etree_process   | 53.9 ms                                                | 62.2 ms: 1.16x slower                                |
| xml_etree_generate  | 76.2 ms                                                | 88.7 ms: 1.16x slower                                |
| unpickle            | 13.7 us                                                | 16.0 us: 1.17x slower                                |
| pickle_list         | 4.11 us                                                | 5.16 us: 1.25x slower                                |
| Geometric mean      | (ref)                                                  | 1.08x slower                                         |

Benchmark hidden because not significant (2): unpickle_pure_python, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.57 ms: 1.12x slower                                |
| python_startup_no_site | 6.01 ms                                                | 6.93 ms: 1.15x slower                                |
| Geometric mean         | (ref)                                                  | 1.14x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.3 ms: 1.12x slower                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 156 us: 3.12x faster                                 |
| generators               | 73.5 ms                                                | 30.9 ms: 2.37x faster                                |
| asyncio_tcp              | 922 ms                                                 | 512 ms: 1.80x faster                                 |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.78 sec: 1.77x faster                               |
| json_dumps               | 12.6 ms                                                | 10.5 ms: 1.20x faster                                |
| gc_traversal             | 4.02 ms                                                | 3.55 ms: 1.13x faster                                |
| richards_super           | 56.8 ms                                                | 50.1 ms: 1.13x faster                                |
| async_tree_none          | 526 ms                                                 | 472 ms: 1.12x faster                                 |
| async_tree_io            | 1.30 sec                                               | 1.16 sec: 1.11x faster                               |
| regex_effbot             | 3.99 ms                                                | 3.63 ms: 1.10x faster                                |
| coroutines               | 25.5 ms                                                | 23.4 ms: 1.09x faster                                |
| async_tree_memoization   | 627 ms                                                 | 576 ms: 1.09x faster                                 |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                 |
| chaos                    | 69.2 ms                                                | 65.9 ms: 1.05x faster                                |
| comprehensions           | 22.4 us                                                | 21.6 us: 1.04x faster                                |
| richards                 | 45.7 ms                                                | 44.2 ms: 1.03x faster                                |
| sqlglot_parse            | 1.40 ms                                                | 1.36 ms: 1.03x faster                                |
| coverage                 | 100 ms                                                 | 97.8 ms: 1.02x faster                                |
| create_gc_cycles         | 1.49 ms                                                | 1.46 ms: 1.02x faster                                |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 725 ms: 1.02x faster                                 |
| sqlglot_transpile        | 1.70 ms                                                | 1.69 ms: 1.01x faster                                |
| deltablue                | 3.67 ms                                                | 3.64 ms: 1.01x faster                                |
| nqueens                  | 83.4 ms                                                | 84.2 ms: 1.01x slower                                |
| hexiom                   | 6.37 ms                                                | 6.48 ms: 1.02x slower                                |
| pathlib                  | 18.2 ms                                                | 18.6 ms: 1.02x slower                                |
| nbody                    | 93.1 ms                                                | 95.1 ms: 1.02x slower                                |
| bench_thread_pool        | 819 us                                                 | 837 us: 1.02x slower                                 |
| pycparser                | 1.18 sec                                               | 1.21 sec: 1.02x slower                               |
| dask                     | 360 ms                                                 | 368 ms: 1.02x slower                                 |
| regex_dna                | 204 ms                                                 | 209 ms: 1.03x slower                                 |
| sqlglot_normalize        | 108 ms                                                 | 111 ms: 1.03x slower                                 |
| xml_etree_iterparse      | 104 ms                                                 | 107 ms: 1.03x slower                                 |
| raytrace                 | 297 ms                                                 | 306 ms: 1.03x slower                                 |
| meteor_contest           | 107 ms                                                 | 110 ms: 1.04x slower                                 |
| tomli_loads              | 2.22 sec                                               | 2.30 sec: 1.04x slower                               |
| sqlglot_optimize         | 53.1 ms                                                | 55.1 ms: 1.04x slower                                |
| tornado_http             | 96.3 ms                                                | 100.0 ms: 1.04x slower                               |
| docutils                 | 2.63 sec                                               | 2.73 sec: 1.04x slower                               |
| sqlalchemy_imperative    | 17.9 ms                                                | 18.6 ms: 1.04x slower                                |
| logging_silent           | 101 ns                                                 | 105 ns: 1.04x slower                                 |
| regex_v8                 | 22.0 ms                                                | 23.0 ms: 1.04x slower                                |
| mdp                      | 2.62 sec                                               | 2.75 sec: 1.05x slower                               |
| fannkuch                 | 388 ms                                                 | 409 ms: 1.06x slower                                 |
| sqlalchemy_declarative   | 138 ms                                                 | 146 ms: 1.06x slower                                 |
| json                     | 4.94 ms                                                | 5.23 ms: 1.06x slower                                |
| pickle_pure_python       | 306 us                                                 | 324 us: 1.06x slower                                 |
| unpickle_list            | 4.91 us                                                | 5.20 us: 1.06x slower                                |
| 2to3                     | 259 ms                                                 | 275 ms: 1.06x slower                                 |
| logging_format           | 6.68 us                                                | 7.11 us: 1.06x slower                                |
| unpack_sequence          | 43.1 ns                                                | 46.0 ns: 1.07x slower                                |
| regex_compile            | 138 ms                                                 | 147 ms: 1.07x slower                                 |
| pprint_pformat           | 1.46 sec                                               | 1.56 sec: 1.07x slower                               |
| logging_simple           | 6.03 us                                                | 6.46 us: 1.07x slower                                |
| scimark_lu               | 110 ms                                                 | 118 ms: 1.07x slower                                 |
| crypto_pyaes             | 74.7 ms                                                | 80.1 ms: 1.07x slower                                |
| deepcopy                 | 342 us                                                 | 368 us: 1.08x slower                                 |
| dulwich_log              | 63.7 ms                                                | 68.5 ms: 1.08x slower                                |
| deepcopy_memo            | 37.0 us                                                | 39.9 us: 1.08x slower                                |
| float                    | 77.2 ms                                                | 83.7 ms: 1.08x slower                                |
| json_loads               | 26.5 us                                                | 28.7 us: 1.09x slower                                |
| pprint_safe_repr         | 701 ms                                                 | 763 ms: 1.09x slower                                 |
| pyflate                  | 418 ms                                                 | 456 ms: 1.09x slower                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 74.3 ms: 1.09x slower                                |
| scimark_sor              | 118 ms                                                 | 129 ms: 1.09x slower                                 |
| telco                    | 6.58 ms                                                | 7.23 ms: 1.10x slower                                |
| deepcopy_reduce          | 2.94 us                                                | 3.24 us: 1.10x slower                                |
| mako                     | 10.1 ms                                                | 11.3 ms: 1.12x slower                                |
| python_startup           | 8.52 ms                                                | 9.57 ms: 1.12x slower                                |
| sqlite_synth             | 2.52 us                                                | 2.85 us: 1.13x slower                                |
| spectral_norm            | 100 ms                                                 | 114 ms: 1.14x slower                                 |
| pickle_dict              | 31.1 us                                                | 35.4 us: 1.14x slower                                |
| python_startup_no_site   | 6.01 ms                                                | 6.93 ms: 1.15x slower                                |
| pickle                   | 10.1 us                                                | 11.6 us: 1.15x slower                                |
| xml_etree_process        | 53.9 ms                                                | 62.2 ms: 1.16x slower                                |
| xml_etree_generate       | 76.2 ms                                                | 88.7 ms: 1.16x slower                                |
| scimark_fft              | 328 ms                                                 | 384 ms: 1.17x slower                                 |
| unpickle                 | 13.7 us                                                | 16.0 us: 1.17x slower                                |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.40 ms: 1.20x slower                                |
| pickle_list              | 4.11 us                                                | 5.16 us: 1.25x slower                                |
| async_generators         | 368 ms                                                 | 465 ms: 1.26x slower                                 |
| Geometric mean           | (ref)                                                  | 1.00x slower                                         |

Benchmark hidden because not significant (5): go, bench_mp_pool, unpickle_pure_python, xml_etree_parse, mypy2
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.94% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
