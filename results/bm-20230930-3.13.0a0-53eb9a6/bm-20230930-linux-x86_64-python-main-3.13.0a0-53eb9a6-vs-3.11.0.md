
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.05x faster
- HPT reliability: 99.26%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.60 sec: 1.01x faster                                |
| tornado_http   | 96.3 ms                                                | 95.0 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 93.1 ms                                                | 89.1 ms: 1.04x faster                                 |
| pidigits       | 198 ms                                                 | 194 ms: 1.02x faster                                  |
| float          | 77.2 ms                                                | 79.9 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.50 ms: 1.14x faster                                 |
| regex_compile  | 138 ms                                                 | 134 ms: 1.03x faster                                  |
| regex_v8       | 22.0 ms                                                | 23.4 ms: 1.06x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.88 ms: 1.27x faster                                 |
| unpickle_pure_python | 228 us                                                 | 211 us: 1.08x faster                                  |
| tomli_loads          | 2.22 sec                                               | 2.11 sec: 1.05x faster                                |
| pickle_pure_python   | 306 us                                                 | 294 us: 1.04x faster                                  |
| xml_etree_parse      | 158 ms                                                 | 153 ms: 1.04x faster                                  |
| json_loads           | 26.5 us                                                | 25.8 us: 1.03x faster                                 |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                  |
| pickle_dict          | 31.1 us                                                | 31.5 us: 1.01x slower                                 |
| unpickle_list        | 4.91 us                                                | 5.01 us: 1.02x slower                                 |
| pickle               | 10.1 us                                                | 10.5 us: 1.04x slower                                 |
| xml_etree_process    | 53.9 ms                                                | 56.8 ms: 1.06x slower                                 |
| xml_etree_generate   | 76.2 ms                                                | 83.3 ms: 1.09x slower                                 |
| unpickle             | 13.7 us                                                | 15.0 us: 1.10x slower                                 |
| pickle_list          | 4.11 us                                                | 4.72 us: 1.15x slower                                 |
| Geometric mean       | (ref)                                                  | 1.00x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.84 ms: 1.14x slower                                 |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                 |
| Geometric mean         | (ref)                                                  | 1.16x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.5 ms: 1.04x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 142 us: 3.43x faster                                  |
| generators               | 73.5 ms                                                | 28.4 ms: 2.59x faster                                 |
| asyncio_tcp              | 922 ms                                                 | 500 ms: 1.84x faster                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                |
| json_dumps               | 12.6 ms                                                | 9.88 ms: 1.27x faster                                 |
| async_tree_none          | 526 ms                                                 | 433 ms: 1.21x faster                                  |
| coroutines               | 25.5 ms                                                | 21.7 ms: 1.18x faster                                 |
| coverage                 | 100 ms                                                 | 85.3 ms: 1.17x faster                                 |
| chaos                    | 69.2 ms                                                | 59.5 ms: 1.16x faster                                 |
| regex_effbot             | 3.99 ms                                                | 3.50 ms: 1.14x faster                                 |
| async_tree_memoization   | 627 ms                                                 | 559 ms: 1.12x faster                                  |
| raytrace                 | 297 ms                                                 | 265 ms: 1.12x faster                                  |
| comprehensions           | 22.4 us                                                | 20.1 us: 1.12x faster                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.25 ms: 1.12x faster                                 |
| deltablue                | 3.67 ms                                                | 3.31 ms: 1.11x faster                                 |
| async_tree_io            | 1.30 sec                                               | 1.18 sec: 1.10x faster                                |
| crypto_pyaes             | 74.7 ms                                                | 68.4 ms: 1.09x faster                                 |
| sqlglot_transpile        | 1.70 ms                                                | 1.56 ms: 1.09x faster                                 |
| unpickle_pure_python     | 228 us                                                 | 211 us: 1.08x faster                                  |
| hexiom                   | 6.37 ms                                                | 5.97 ms: 1.07x faster                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 695 ms: 1.06x faster                                  |
| tomli_loads              | 2.22 sec                                               | 2.11 sec: 1.05x faster                                |
| richards_super           | 56.8 ms                                                | 53.9 ms: 1.05x faster                                 |
| nbody                    | 93.1 ms                                                | 89.1 ms: 1.04x faster                                 |
| sqlglot_normalize        | 108 ms                                                 | 103 ms: 1.04x faster                                  |
| pickle_pure_python       | 306 us                                                 | 294 us: 1.04x faster                                  |
| xml_etree_parse          | 158 ms                                                 | 153 ms: 1.04x faster                                  |
| pycparser                | 1.18 sec                                               | 1.14 sec: 1.04x faster                                |
| nqueens                  | 83.4 ms                                                | 80.5 ms: 1.04x faster                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 65.8 ms: 1.03x faster                                 |
| logging_format           | 6.68 us                                                | 6.47 us: 1.03x faster                                 |
| regex_compile            | 138 ms                                                 | 134 ms: 1.03x faster                                  |
| logging_simple           | 6.03 us                                                | 5.87 us: 1.03x faster                                 |
| json_loads               | 26.5 us                                                | 25.8 us: 1.03x faster                                 |
| json                     | 4.94 ms                                                | 4.83 ms: 1.02x faster                                 |
| gc_traversal             | 4.02 ms                                                | 3.93 ms: 1.02x faster                                 |
| pidigits                 | 198 ms                                                 | 194 ms: 1.02x faster                                  |
| deepcopy_memo            | 37.0 us                                                | 36.4 us: 1.02x faster                                 |
| sqlglot_optimize         | 53.1 ms                                                | 52.2 ms: 1.02x faster                                 |
| bench_thread_pool        | 819 us                                                 | 806 us: 1.02x faster                                  |
| tornado_http             | 96.3 ms                                                | 95.0 ms: 1.01x faster                                 |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                  |
| go                       | 140 ms                                                 | 138 ms: 1.01x faster                                  |
| fannkuch                 | 388 ms                                                 | 384 ms: 1.01x faster                                  |
| docutils                 | 2.63 sec                                               | 2.60 sec: 1.01x faster                                |
| logging_silent           | 101 ns                                                 | 100 ns: 1.01x faster                                  |
| pprint_pformat           | 1.46 sec                                               | 1.45 sec: 1.01x faster                                |
| pickle_dict              | 31.1 us                                                | 31.5 us: 1.01x slower                                 |
| pprint_safe_repr         | 701 ms                                                 | 710 ms: 1.01x slower                                  |
| scimark_sor              | 118 ms                                                 | 120 ms: 1.02x slower                                  |
| scimark_lu               | 110 ms                                                 | 112 ms: 1.02x slower                                  |
| unpickle_list            | 4.91 us                                                | 5.01 us: 1.02x slower                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.04 us: 1.03x slower                                 |
| create_gc_cycles         | 1.49 ms                                                | 1.54 ms: 1.03x slower                                 |
| float                    | 77.2 ms                                                | 79.9 ms: 1.03x slower                                 |
| mako                     | 10.1 ms                                                | 10.5 ms: 1.04x slower                                 |
| mdp                      | 2.62 sec                                               | 2.71 sec: 1.04x slower                                |
| richards                 | 45.7 ms                                                | 47.4 ms: 1.04x slower                                 |
| dulwich_log              | 63.7 ms                                                | 66.1 ms: 1.04x slower                                 |
| pickle                   | 10.1 us                                                | 10.5 us: 1.04x slower                                 |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                 |
| unpack_sequence          | 43.1 ns                                                | 45.1 ns: 1.05x slower                                 |
| spectral_norm            | 100 ms                                                 | 105 ms: 1.05x slower                                  |
| xml_etree_process        | 53.9 ms                                                | 56.8 ms: 1.06x slower                                 |
| regex_v8                 | 22.0 ms                                                | 23.4 ms: 1.06x slower                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.85 ms: 1.08x slower                                 |
| xml_etree_generate       | 76.2 ms                                                | 83.3 ms: 1.09x slower                                 |
| scimark_fft              | 328 ms                                                 | 359 ms: 1.09x slower                                  |
| pyflate                  | 418 ms                                                 | 460 ms: 1.10x slower                                  |
| unpickle                 | 13.7 us                                                | 15.0 us: 1.10x slower                                 |
| sqlite_synth             | 2.52 us                                                | 2.78 us: 1.10x slower                                 |
| python_startup_no_site   | 6.01 ms                                                | 6.84 ms: 1.14x slower                                 |
| pickle_list              | 4.11 us                                                | 4.72 us: 1.15x slower                                 |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                 |
| async_generators         | 368 ms                                                 | 438 ms: 1.19x slower                                  |
| telco                    | 6.58 ms                                                | 7.97 ms: 1.21x slower                                 |
| Geometric mean           | (ref)                                                  | 1.05x faster                                          |

Benchmark hidden because not significant (5): meteor_contest, deepcopy, regex_dna, bench_mp_pool, mypy2
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.26% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
