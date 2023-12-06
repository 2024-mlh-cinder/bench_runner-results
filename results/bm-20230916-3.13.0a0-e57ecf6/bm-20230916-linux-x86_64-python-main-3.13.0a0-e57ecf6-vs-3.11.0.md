
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.05x faster
- HPT reliability: 90.81%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| tornado_http   | 96.3 ms                                                | 95.0 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 93.1 ms                                                | 88.0 ms: 1.06x faster                                 |
| float          | 77.2 ms                                                | 78.7 ms: 1.02x slower                                 |
| pidigits       | 198 ms                                                 | 203 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.45 ms: 1.16x faster                                 |
| regex_compile  | 138 ms                                                 | 134 ms: 1.03x faster                                  |
| regex_dna      | 204 ms                                                 | 205 ms: 1.01x slower                                  |
| regex_v8       | 22.0 ms                                                | 23.3 ms: 1.05x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.81 ms: 1.28x faster                                 |
| unpickle_pure_python | 228 us                                                 | 211 us: 1.08x faster                                  |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.05x faster                                  |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                 |
| pickle_pure_python   | 306 us                                                 | 296 us: 1.03x faster                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| unpickle_list        | 4.91 us                                                | 4.83 us: 1.02x faster                                 |
| unpickle             | 13.7 us                                                | 14.2 us: 1.04x slower                                 |
| pickle_dict          | 31.1 us                                                | 32.4 us: 1.04x slower                                 |
| xml_etree_process    | 53.9 ms                                                | 56.8 ms: 1.05x slower                                 |
| pickle               | 10.1 us                                                | 10.7 us: 1.07x slower                                 |
| xml_etree_generate   | 76.2 ms                                                | 82.3 ms: 1.08x slower                                 |
| pickle_list          | 4.11 us                                                | 4.85 us: 1.18x slower                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.83 ms: 1.14x slower                                 |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                 |
| Geometric mean         | (ref)                                                  | 1.16x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.5 ms: 1.04x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-linux-x86_64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 141 us: 3.46x faster                                  |
| generators               | 73.5 ms                                                | 27.9 ms: 2.63x faster                                 |
| asyncio_tcp              | 922 ms                                                 | 490 ms: 1.88x faster                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                |
| json_dumps               | 12.6 ms                                                | 9.81 ms: 1.28x faster                                 |
| mypy2                    | 420 ms                                                 | 337 ms: 1.25x faster                                  |
| async_tree_none          | 526 ms                                                 | 437 ms: 1.21x faster                                  |
| chaos                    | 69.2 ms                                                | 59.4 ms: 1.16x faster                                 |
| regex_effbot             | 3.99 ms                                                | 3.45 ms: 1.16x faster                                 |
| coverage                 | 100 ms                                                 | 86.7 ms: 1.15x faster                                 |
| coroutines               | 25.5 ms                                                | 22.4 ms: 1.14x faster                                 |
| async_tree_memoization   | 627 ms                                                 | 562 ms: 1.12x faster                                  |
| raytrace                 | 297 ms                                                 | 266 ms: 1.12x faster                                  |
| deltablue                | 3.67 ms                                                | 3.32 ms: 1.11x faster                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.27 ms: 1.10x faster                                 |
| comprehensions           | 22.4 us                                                | 20.4 us: 1.10x faster                                 |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                |
| unpickle_pure_python     | 228 us                                                 | 211 us: 1.08x faster                                  |
| sqlglot_transpile        | 1.70 ms                                                | 1.58 ms: 1.08x faster                                 |
| hexiom                   | 6.37 ms                                                | 5.93 ms: 1.07x faster                                 |
| crypto_pyaes             | 74.7 ms                                                | 69.8 ms: 1.07x faster                                 |
| nqueens                  | 83.4 ms                                                | 78.2 ms: 1.07x faster                                 |
| nbody                    | 93.1 ms                                                | 88.0 ms: 1.06x faster                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 700 ms: 1.06x faster                                  |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.05x faster                                  |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                 |
| richards_super           | 56.8 ms                                                | 54.4 ms: 1.04x faster                                 |
| pickle_pure_python       | 306 us                                                 | 296 us: 1.03x faster                                  |
| pycparser                | 1.18 sec                                               | 1.14 sec: 1.03x faster                                |
| regex_compile            | 138 ms                                                 | 134 ms: 1.03x faster                                  |
| unpack_sequence          | 43.1 ns                                                | 41.9 ns: 1.03x faster                                 |
| logging_silent           | 101 ns                                                 | 98.5 ns: 1.03x faster                                 |
| sqlglot_normalize        | 108 ms                                                 | 105 ms: 1.02x faster                                  |
| json                     | 4.94 ms                                                | 4.83 ms: 1.02x faster                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 66.6 ms: 1.02x faster                                 |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| deepcopy_memo            | 37.0 us                                                | 36.4 us: 1.02x faster                                 |
| unpickle_list            | 4.91 us                                                | 4.83 us: 1.02x faster                                 |
| bench_thread_pool        | 819 us                                                 | 806 us: 1.02x faster                                  |
| fannkuch                 | 388 ms                                                 | 382 ms: 1.01x faster                                  |
| tornado_http             | 96.3 ms                                                | 95.0 ms: 1.01x faster                                 |
| sqlglot_optimize         | 53.1 ms                                                | 52.8 ms: 1.01x faster                                 |
| mdp                      | 2.62 sec                                               | 2.63 sec: 1.01x slower                                |
| regex_dna                | 204 ms                                                 | 205 ms: 1.01x slower                                  |
| deepcopy                 | 342 us                                                 | 345 us: 1.01x slower                                  |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.54 ms: 1.01x slower                                 |
| logging_simple           | 6.03 us                                                | 6.10 us: 1.01x slower                                 |
| pathlib                  | 18.2 ms                                                | 18.4 ms: 1.01x slower                                 |
| float                    | 77.2 ms                                                | 78.7 ms: 1.02x slower                                 |
| create_gc_cycles         | 1.49 ms                                                | 1.52 ms: 1.02x slower                                 |
| gc_traversal             | 4.02 ms                                                | 4.12 ms: 1.02x slower                                 |
| pprint_safe_repr         | 701 ms                                                 | 718 ms: 1.02x slower                                  |
| pidigits                 | 198 ms                                                 | 203 ms: 1.03x slower                                  |
| mako                     | 10.1 ms                                                | 10.5 ms: 1.04x slower                                 |
| unpickle                 | 13.7 us                                                | 14.2 us: 1.04x slower                                 |
| pickle_dict              | 31.1 us                                                | 32.4 us: 1.04x slower                                 |
| dulwich_log              | 63.7 ms                                                | 66.6 ms: 1.05x slower                                 |
| xml_etree_process        | 53.9 ms                                                | 56.8 ms: 1.05x slower                                 |
| regex_v8                 | 22.0 ms                                                | 23.3 ms: 1.05x slower                                 |
| richards                 | 45.7 ms                                                | 48.4 ms: 1.06x slower                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.12 us: 1.06x slower                                 |
| pickle                   | 10.1 us                                                | 10.7 us: 1.07x slower                                 |
| spectral_norm            | 100 ms                                                 | 107 ms: 1.07x slower                                  |
| xml_etree_generate       | 76.2 ms                                                | 82.3 ms: 1.08x slower                                 |
| sqlite_synth             | 2.52 us                                                | 2.73 us: 1.08x slower                                 |
| pyflate                  | 418 ms                                                 | 453 ms: 1.08x slower                                  |
| scimark_sor              | 118 ms                                                 | 129 ms: 1.09x slower                                  |
| scimark_fft              | 328 ms                                                 | 359 ms: 1.09x slower                                  |
| python_startup_no_site   | 6.01 ms                                                | 6.83 ms: 1.14x slower                                 |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                 |
| pickle_list              | 4.11 us                                                | 4.85 us: 1.18x slower                                 |
| async_generators         | 368 ms                                                 | 445 ms: 1.21x slower                                  |
| telco                    | 6.58 ms                                                | 7.98 ms: 1.21x slower                                 |
| dask                     | 360 ms                                                 | 529 ms: 1.47x slower                                  |
| Geometric mean           | (ref)                                                  | 1.05x faster                                          |

Benchmark hidden because not significant (7): meteor_contest, docutils, bench_mp_pool, logging_format, go, pprint_pformat, scimark_lu
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 90.81% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
