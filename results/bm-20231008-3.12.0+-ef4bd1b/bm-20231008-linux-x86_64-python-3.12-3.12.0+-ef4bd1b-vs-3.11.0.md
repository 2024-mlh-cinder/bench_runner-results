
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: ef4bd1b
- commit date: 2023-10-08
- overall geometric mean: 1.01x slower
- HPT reliability: 99.97%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 259 ms                                                 | 275 ms: 1.06x slower                                 |
| docutils       | 2.63 sec                                               | 2.75 sec: 1.05x slower                               |
| tornado_http   | 96.3 ms                                                | 103 ms: 1.07x slower                                 |
| Geometric mean | (ref)                                                  | 1.06x slower                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                 |
| nbody          | 93.1 ms                                                | 95.1 ms: 1.02x slower                                |
| float          | 77.2 ms                                                | 83.5 ms: 1.08x slower                                |
| Geometric mean | (ref)                                                  | 1.01x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.68 ms: 1.08x faster                                |
| regex_v8       | 22.0 ms                                                | 22.3 ms: 1.01x slower                                |
| regex_dna      | 204 ms                                                 | 209 ms: 1.03x slower                                 |
| regex_compile  | 138 ms                                                 | 149 ms: 1.08x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.6 ms: 1.19x faster                                |
| unpickle_pure_python | 228 us                                                 | 231 us: 1.01x slower                                 |
| xml_etree_parse      | 158 ms                                                 | 161 ms: 1.01x slower                                 |
| xml_etree_iterparse  | 104 ms                                                 | 107 ms: 1.03x slower                                 |
| tomli_loads          | 2.22 sec                                               | 2.32 sec: 1.05x slower                               |
| pickle_dict          | 31.1 us                                                | 32.7 us: 1.05x slower                                |
| pickle_pure_python   | 306 us                                                 | 325 us: 1.06x slower                                 |
| json_loads           | 26.5 us                                                | 28.5 us: 1.08x slower                                |
| pickle               | 10.1 us                                                | 11.4 us: 1.13x slower                                |
| xml_etree_process    | 53.9 ms                                                | 62.0 ms: 1.15x slower                                |
| unpickle             | 13.7 us                                                | 15.8 us: 1.15x slower                                |
| unpickle_list        | 4.91 us                                                | 5.68 us: 1.16x slower                                |
| xml_etree_generate   | 76.2 ms                                                | 89.1 ms: 1.17x slower                                |
| pickle_list          | 4.11 us                                                | 4.86 us: 1.18x slower                                |
| Geometric mean       | (ref)                                                  | 1.07x slower                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.54 ms: 1.12x slower                                |
| python_startup_no_site | 6.01 ms                                                | 6.92 ms: 1.15x slower                                |
| Geometric mean         | (ref)                                                  | 1.14x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.7 ms: 1.16x slower                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 156 us: 3.12x faster                                 |
| generators               | 73.5 ms                                                | 31.4 ms: 2.34x faster                                |
| asyncio_tcp              | 922 ms                                                 | 501 ms: 1.84x faster                                 |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.78 sec: 1.77x faster                               |
| json_dumps               | 12.6 ms                                                | 10.6 ms: 1.19x faster                                |
| richards_super           | 56.8 ms                                                | 51.1 ms: 1.11x faster                                |
| async_tree_io            | 1.30 sec                                               | 1.17 sec: 1.11x faster                               |
| async_tree_none          | 526 ms                                                 | 478 ms: 1.10x faster                                 |
| coroutines               | 25.5 ms                                                | 23.3 ms: 1.10x faster                                |
| regex_effbot             | 3.99 ms                                                | 3.68 ms: 1.08x faster                                |
| async_tree_memoization   | 627 ms                                                 | 583 ms: 1.08x faster                                 |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                 |
| gc_traversal             | 4.02 ms                                                | 3.83 ms: 1.05x faster                                |
| chaos                    | 69.2 ms                                                | 66.8 ms: 1.04x faster                                |
| sqlglot_parse            | 1.40 ms                                                | 1.36 ms: 1.03x faster                                |
| comprehensions           | 22.4 us                                                | 21.9 us: 1.03x faster                                |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 727 ms: 1.02x faster                                 |
| coverage                 | 100 ms                                                 | 98.4 ms: 1.02x faster                                |
| richards                 | 45.7 ms                                                | 45.0 ms: 1.02x faster                                |
| mdp                      | 2.62 sec                                               | 2.61 sec: 1.00x faster                               |
| go                       | 140 ms                                                 | 140 ms: 1.00x slower                                 |
| nqueens                  | 83.4 ms                                                | 83.7 ms: 1.00x slower                                |
| deltablue                | 3.67 ms                                                | 3.70 ms: 1.01x slower                                |
| regex_v8                 | 22.0 ms                                                | 22.3 ms: 1.01x slower                                |
| unpickle_pure_python     | 228 us                                                 | 231 us: 1.01x slower                                 |
| pathlib                  | 18.2 ms                                                | 18.5 ms: 1.01x slower                                |
| xml_etree_parse          | 158 ms                                                 | 161 ms: 1.01x slower                                 |
| nbody                    | 93.1 ms                                                | 95.1 ms: 1.02x slower                                |
| create_gc_cycles         | 1.49 ms                                                | 1.52 ms: 1.02x slower                                |
| bench_thread_pool        | 819 us                                                 | 838 us: 1.02x slower                                 |
| sqlglot_normalize        | 108 ms                                                 | 110 ms: 1.02x slower                                 |
| hexiom                   | 6.37 ms                                                | 6.54 ms: 1.03x slower                                |
| regex_dna                | 204 ms                                                 | 209 ms: 1.03x slower                                 |
| xml_etree_iterparse      | 104 ms                                                 | 107 ms: 1.03x slower                                 |
| sqlglot_optimize         | 53.1 ms                                                | 54.9 ms: 1.03x slower                                |
| pycparser                | 1.18 sec                                               | 1.22 sec: 1.03x slower                               |
| dask                     | 360 ms                                                 | 373 ms: 1.04x slower                                 |
| meteor_contest           | 107 ms                                                 | 111 ms: 1.04x slower                                 |
| raytrace                 | 297 ms                                                 | 310 ms: 1.05x slower                                 |
| tomli_loads              | 2.22 sec                                               | 2.32 sec: 1.05x slower                               |
| docutils                 | 2.63 sec                                               | 2.75 sec: 1.05x slower                               |
| pickle_dict              | 31.1 us                                                | 32.7 us: 1.05x slower                                |
| sqlalchemy_imperative    | 17.9 ms                                                | 18.8 ms: 1.05x slower                                |
| logging_silent           | 101 ns                                                 | 107 ns: 1.06x slower                                 |
| sqlalchemy_declarative   | 138 ms                                                 | 146 ms: 1.06x slower                                 |
| pickle_pure_python       | 306 us                                                 | 325 us: 1.06x slower                                 |
| pprint_pformat           | 1.46 sec                                               | 1.55 sec: 1.06x slower                               |
| logging_simple           | 6.03 us                                                | 6.41 us: 1.06x slower                                |
| 2to3                     | 259 ms                                                 | 275 ms: 1.06x slower                                 |
| json                     | 4.94 ms                                                | 5.28 ms: 1.07x slower                                |
| tornado_http             | 96.3 ms                                                | 103 ms: 1.07x slower                                 |
| logging_format           | 6.68 us                                                | 7.18 us: 1.07x slower                                |
| json_loads               | 26.5 us                                                | 28.5 us: 1.08x slower                                |
| regex_compile            | 138 ms                                                 | 149 ms: 1.08x slower                                 |
| pprint_safe_repr         | 701 ms                                                 | 758 ms: 1.08x slower                                 |
| float                    | 77.2 ms                                                | 83.5 ms: 1.08x slower                                |
| telco                    | 6.58 ms                                                | 7.15 ms: 1.09x slower                                |
| deepcopy                 | 342 us                                                 | 372 us: 1.09x slower                                 |
| dulwich_log              | 63.7 ms                                                | 69.2 ms: 1.09x slower                                |
| fannkuch                 | 388 ms                                                 | 423 ms: 1.09x slower                                 |
| crypto_pyaes             | 74.7 ms                                                | 81.7 ms: 1.09x slower                                |
| deepcopy_memo            | 37.0 us                                                | 40.7 us: 1.10x slower                                |
| scimark_lu               | 110 ms                                                 | 121 ms: 1.11x slower                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 75.5 ms: 1.11x slower                                |
| scimark_sor              | 118 ms                                                 | 132 ms: 1.12x slower                                 |
| python_startup           | 8.52 ms                                                | 9.54 ms: 1.12x slower                                |
| unpack_sequence          | 43.1 ns                                                | 48.6 ns: 1.13x slower                                |
| deepcopy_reduce          | 2.94 us                                                | 3.32 us: 1.13x slower                                |
| spectral_norm            | 100 ms                                                 | 113 ms: 1.13x slower                                 |
| pickle                   | 10.1 us                                                | 11.4 us: 1.13x slower                                |
| sqlite_synth             | 2.52 us                                                | 2.87 us: 1.14x slower                                |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.15 ms: 1.15x slower                                |
| xml_etree_process        | 53.9 ms                                                | 62.0 ms: 1.15x slower                                |
| python_startup_no_site   | 6.01 ms                                                | 6.92 ms: 1.15x slower                                |
| scimark_fft              | 328 ms                                                 | 378 ms: 1.15x slower                                 |
| unpickle                 | 13.7 us                                                | 15.8 us: 1.15x slower                                |
| unpickle_list            | 4.91 us                                                | 5.68 us: 1.16x slower                                |
| mako                     | 10.1 ms                                                | 11.7 ms: 1.16x slower                                |
| xml_etree_generate       | 76.2 ms                                                | 89.1 ms: 1.17x slower                                |
| pyflate                  | 418 ms                                                 | 489 ms: 1.17x slower                                 |
| pickle_list              | 4.11 us                                                | 4.86 us: 1.18x slower                                |
| async_generators         | 368 ms                                                 | 468 ms: 1.27x slower                                 |
| Geometric mean           | (ref)                                                  | 1.01x slower                                         |

Benchmark hidden because not significant (3): sqlglot_transpile, bench_mp_pool, mypy2
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.97% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
