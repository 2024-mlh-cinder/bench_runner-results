
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_opargs
- machine: linux-x86_64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.01x faster
- HPT reliability: 96.66%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.71 sec: 1.03x slower                                               |
| tornado_http   | 96.3 ms                                                | 97.9 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                 |
| nbody          | 93.1 ms                                                | 99.8 ms: 1.07x slower                                                |
| float          | 77.2 ms                                                | 83.3 ms: 1.08x slower                                                |
| Geometric mean | (ref)                                                  | 1.03x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.63 ms: 1.10x faster                                                |
| regex_compile  | 138 ms                                                 | 147 ms: 1.07x slower                                                 |
| regex_dna      | 204 ms                                                 | 222 ms: 1.09x slower                                                 |
| regex_v8       | 22.0 ms                                                | 25.4 ms: 1.15x slower                                                |
| Geometric mean | (ref)                                                  | 1.05x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps         | 12.6 ms                                                | 9.96 ms: 1.26x faster                                                |
| json_loads         | 26.5 us                                                | 25.0 us: 1.06x faster                                                |
| xml_etree_parse    | 158 ms                                                 | 152 ms: 1.04x faster                                                 |
| unpickle_list      | 4.91 us                                                | 4.99 us: 1.02x slower                                                |
| pickle_dict        | 31.1 us                                                | 31.7 us: 1.02x slower                                                |
| pickle             | 10.1 us                                                | 10.7 us: 1.06x slower                                                |
| xml_etree_process  | 53.9 ms                                                | 58.3 ms: 1.08x slower                                                |
| xml_etree_generate | 76.2 ms                                                | 83.3 ms: 1.09x slower                                                |
| pickle_list        | 4.11 us                                                | 4.62 us: 1.12x slower                                                |
| Geometric mean     | (ref)                                                  | 1.00x slower                                                         |

Benchmark hidden because not significant (5): tomli_loads, pickle_pure_python, unpickle_pure_python, xml_etree_iterparse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.84 ms: 1.15x slower                                                |
| python_startup_no_site | 6.01 ms                                                | 7.32 ms: 1.22x slower                                                |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.7 ms: 1.16x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 153 us: 3.18x faster                                                 |
| generators               | 73.5 ms                                                | 29.8 ms: 2.47x faster                                                |
| asyncio_tcp              | 922 ms                                                 | 491 ms: 1.88x faster                                                 |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                               |
| json_dumps               | 12.6 ms                                                | 9.96 ms: 1.26x faster                                                |
| mypy2                    | 420 ms                                                 | 355 ms: 1.18x faster                                                 |
| async_tree_none          | 526 ms                                                 | 445 ms: 1.18x faster                                                 |
| coroutines               | 25.5 ms                                                | 22.1 ms: 1.15x faster                                                |
| coverage                 | 100 ms                                                 | 87.0 ms: 1.15x faster                                                |
| regex_effbot             | 3.99 ms                                                | 3.63 ms: 1.10x faster                                                |
| async_tree_memoization   | 627 ms                                                 | 578 ms: 1.09x faster                                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.30 ms: 1.08x faster                                                |
| async_tree_io            | 1.30 sec                                               | 1.21 sec: 1.07x faster                                               |
| deltablue                | 3.67 ms                                                | 3.46 ms: 1.06x faster                                                |
| json_loads               | 26.5 us                                                | 25.0 us: 1.06x faster                                                |
| chaos                    | 69.2 ms                                                | 65.4 ms: 1.06x faster                                                |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                 |
| sqlglot_transpile        | 1.70 ms                                                | 1.62 ms: 1.05x faster                                                |
| raytrace                 | 297 ms                                                 | 282 ms: 1.05x faster                                                 |
| gc_traversal             | 4.02 ms                                                | 3.84 ms: 1.05x faster                                                |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                 |
| richards_super           | 56.8 ms                                                | 54.7 ms: 1.04x faster                                                |
| crypto_pyaes             | 74.7 ms                                                | 72.0 ms: 1.04x faster                                                |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 714 ms: 1.03x faster                                                 |
| logging_format           | 6.68 us                                                | 6.53 us: 1.02x faster                                                |
| logging_simple           | 6.03 us                                                | 5.91 us: 1.02x faster                                                |
| json                     | 4.94 ms                                                | 4.86 ms: 1.02x faster                                                |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.01x faster                                                 |
| mdp                      | 2.62 sec                                               | 2.63 sec: 1.00x slower                                               |
| scimark_monte_carlo      | 68.1 ms                                                | 68.8 ms: 1.01x slower                                                |
| create_gc_cycles         | 1.49 ms                                                | 1.50 ms: 1.01x slower                                                |
| unpickle_list            | 4.91 us                                                | 4.99 us: 1.02x slower                                                |
| tornado_http             | 96.3 ms                                                | 97.9 ms: 1.02x slower                                                |
| sqlglot_optimize         | 53.1 ms                                                | 54.1 ms: 1.02x slower                                                |
| pickle_dict              | 31.1 us                                                | 31.7 us: 1.02x slower                                                |
| bench_thread_pool        | 819 us                                                 | 839 us: 1.02x slower                                                 |
| docutils                 | 2.63 sec                                               | 2.71 sec: 1.03x slower                                               |
| pathlib                  | 18.2 ms                                                | 18.8 ms: 1.03x slower                                                |
| pycparser                | 1.18 sec                                               | 1.22 sec: 1.04x slower                                               |
| logging_silent           | 101 ns                                                 | 105 ns: 1.04x slower                                                 |
| scimark_sor              | 118 ms                                                 | 123 ms: 1.04x slower                                                 |
| scimark_lu               | 110 ms                                                 | 114 ms: 1.04x slower                                                 |
| deepcopy_memo            | 37.0 us                                                | 38.6 us: 1.04x slower                                                |
| deepcopy                 | 342 us                                                 | 358 us: 1.05x slower                                                 |
| pprint_pformat           | 1.46 sec                                               | 1.54 sec: 1.05x slower                                               |
| deepcopy_reduce          | 2.94 us                                                | 3.10 us: 1.05x slower                                                |
| go                       | 140 ms                                                 | 148 ms: 1.06x slower                                                 |
| richards                 | 45.7 ms                                                | 48.5 ms: 1.06x slower                                                |
| pickle                   | 10.1 us                                                | 10.7 us: 1.06x slower                                                |
| meteor_contest           | 107 ms                                                 | 113 ms: 1.06x slower                                                 |
| regex_compile            | 138 ms                                                 | 147 ms: 1.07x slower                                                 |
| pprint_safe_repr         | 701 ms                                                 | 748 ms: 1.07x slower                                                 |
| comprehensions           | 22.4 us                                                | 23.9 us: 1.07x slower                                                |
| nbody                    | 93.1 ms                                                | 99.8 ms: 1.07x slower                                                |
| float                    | 77.2 ms                                                | 83.3 ms: 1.08x slower                                                |
| dulwich_log              | 63.7 ms                                                | 68.7 ms: 1.08x slower                                                |
| xml_etree_process        | 53.9 ms                                                | 58.3 ms: 1.08x slower                                                |
| sqlite_synth             | 2.52 us                                                | 2.74 us: 1.09x slower                                                |
| unpack_sequence          | 43.1 ns                                                | 46.9 ns: 1.09x slower                                                |
| regex_dna                | 204 ms                                                 | 222 ms: 1.09x slower                                                 |
| xml_etree_generate       | 76.2 ms                                                | 83.3 ms: 1.09x slower                                                |
| fannkuch                 | 388 ms                                                 | 430 ms: 1.11x slower                                                 |
| hexiom                   | 6.37 ms                                                | 7.13 ms: 1.12x slower                                                |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.05 ms: 1.12x slower                                                |
| nqueens                  | 83.4 ms                                                | 93.7 ms: 1.12x slower                                                |
| pickle_list              | 4.11 us                                                | 4.62 us: 1.12x slower                                                |
| spectral_norm            | 100 ms                                                 | 113 ms: 1.12x slower                                                 |
| scimark_fft              | 328 ms                                                 | 373 ms: 1.14x slower                                                 |
| pyflate                  | 418 ms                                                 | 479 ms: 1.14x slower                                                 |
| regex_v8                 | 22.0 ms                                                | 25.4 ms: 1.15x slower                                                |
| python_startup           | 8.52 ms                                                | 9.84 ms: 1.15x slower                                                |
| mako                     | 10.1 ms                                                | 11.7 ms: 1.16x slower                                                |
| python_startup_no_site   | 6.01 ms                                                | 7.32 ms: 1.22x slower                                                |
| telco                    | 6.58 ms                                                | 8.25 ms: 1.25x slower                                                |
| async_generators         | 368 ms                                                 | 475 ms: 1.29x slower                                                 |
| dask                     | 360 ms                                                 | 532 ms: 1.48x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                         |

Benchmark hidden because not significant (6): tomli_loads, pickle_pure_python, bench_mp_pool, unpickle_pure_python, xml_etree_iterparse, unpickle
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 96.66% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
