
# Results vs. 3.11.0

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 0ad7112
- commit date: 2023-08-12
- overall geometric mean: 1.04x faster
- HPT reliability: 85.88%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tornado_http   | 96.3 ms                                                | 95.7 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 93.1 ms                                                | 91.6 ms: 1.02x faster                                          |
| pidigits       | 198 ms                                                 | 196 ms: 1.01x faster                                           |
| float          | 77.2 ms                                                | 80.2 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                  | 1.00x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.57 ms: 1.12x faster                                          |
| regex_compile  | 138 ms                                                 | 135 ms: 1.02x faster                                           |
| regex_dna      | 204 ms                                                 | 227 ms: 1.11x slower                                           |
| regex_v8       | 22.0 ms                                                | 25.1 ms: 1.14x slower                                          |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.78 ms: 1.29x faster                                          |
| unpickle_pure_python | 228 us                                                 | 213 us: 1.07x faster                                           |
| tomli_loads          | 2.22 sec                                               | 2.11 sec: 1.05x faster                                         |
| json_loads           | 26.5 us                                                | 25.2 us: 1.05x faster                                          |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                           |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                           |
| unpickle_list        | 4.91 us                                                | 4.85 us: 1.01x faster                                          |
| pickle_pure_python   | 306 us                                                 | 303 us: 1.01x faster                                           |
| pickle_dict          | 31.1 us                                                | 32.2 us: 1.03x slower                                          |
| xml_etree_process    | 53.9 ms                                                | 56.7 ms: 1.05x slower                                          |
| pickle               | 10.1 us                                                | 10.9 us: 1.08x slower                                          |
| xml_etree_generate   | 76.2 ms                                                | 82.5 ms: 1.08x slower                                          |
| unpickle             | 13.7 us                                                | 15.2 us: 1.11x slower                                          |
| pickle_list          | 4.11 us                                                | 4.75 us: 1.16x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.56 ms: 1.12x slower                                          |
| python_startup_no_site | 6.01 ms                                                | 7.00 ms: 1.16x slower                                          |
| Geometric mean         | (ref)                                                  | 1.14x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.9 ms: 1.08x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 142 us: 3.42x faster                                           |
| generators               | 73.5 ms                                                | 29.0 ms: 2.53x faster                                          |
| asyncio_tcp              | 922 ms                                                 | 485 ms: 1.90x faster                                           |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                         |
| json_dumps               | 12.6 ms                                                | 9.78 ms: 1.29x faster                                          |
| mypy2                    | 420 ms                                                 | 339 ms: 1.24x faster                                           |
| async_tree_none          | 526 ms                                                 | 437 ms: 1.20x faster                                           |
| chaos                    | 69.2 ms                                                | 59.5 ms: 1.16x faster                                          |
| coverage                 | 100 ms                                                 | 86.7 ms: 1.15x faster                                          |
| deltablue                | 3.67 ms                                                | 3.28 ms: 1.12x faster                                          |
| regex_effbot             | 3.99 ms                                                | 3.57 ms: 1.12x faster                                          |
| sqlglot_parse            | 1.40 ms                                                | 1.26 ms: 1.11x faster                                          |
| async_tree_memoization   | 627 ms                                                 | 566 ms: 1.11x faster                                           |
| crypto_pyaes             | 74.7 ms                                                | 67.8 ms: 1.10x faster                                          |
| coroutines               | 25.5 ms                                                | 23.2 ms: 1.10x faster                                          |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                         |
| sqlglot_transpile        | 1.70 ms                                                | 1.57 ms: 1.09x faster                                          |
| hexiom                   | 6.37 ms                                                | 5.90 ms: 1.08x faster                                          |
| comprehensions           | 22.4 us                                                | 20.8 us: 1.08x faster                                          |
| raytrace                 | 297 ms                                                 | 275 ms: 1.08x faster                                           |
| unpickle_pure_python     | 228 us                                                 | 213 us: 1.07x faster                                           |
| richards_super           | 56.8 ms                                                | 53.3 ms: 1.07x faster                                          |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 701 ms: 1.05x faster                                           |
| tomli_loads              | 2.22 sec                                               | 2.11 sec: 1.05x faster                                         |
| sqlglot_normalize        | 108 ms                                                 | 103 ms: 1.05x faster                                           |
| json_loads               | 26.5 us                                                | 25.2 us: 1.05x faster                                          |
| nqueens                  | 83.4 ms                                                | 79.6 ms: 1.05x faster                                          |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                           |
| logging_format           | 6.68 us                                                | 6.44 us: 1.04x faster                                          |
| sqlglot_optimize         | 53.1 ms                                                | 52.0 ms: 1.02x faster                                          |
| regex_compile            | 138 ms                                                 | 135 ms: 1.02x faster                                           |
| scimark_monte_carlo      | 68.1 ms                                                | 66.9 ms: 1.02x faster                                          |
| mdp                      | 2.62 sec                                               | 2.57 sec: 1.02x faster                                         |
| nbody                    | 93.1 ms                                                | 91.6 ms: 1.02x faster                                          |
| fannkuch                 | 388 ms                                                 | 382 ms: 1.02x faster                                           |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                           |
| unpickle_list            | 4.91 us                                                | 4.85 us: 1.01x faster                                          |
| pickle_pure_python       | 306 us                                                 | 303 us: 1.01x faster                                           |
| pidigits                 | 198 ms                                                 | 196 ms: 1.01x faster                                           |
| logging_simple           | 6.03 us                                                | 5.99 us: 1.01x faster                                          |
| tornado_http             | 96.3 ms                                                | 95.7 ms: 1.01x faster                                          |
| bench_thread_pool        | 819 us                                                 | 814 us: 1.01x faster                                           |
| scimark_lu               | 110 ms                                                 | 110 ms: 1.00x slower                                           |
| pprint_pformat           | 1.46 sec                                               | 1.47 sec: 1.01x slower                                         |
| deepcopy_memo            | 37.0 us                                                | 37.4 us: 1.01x slower                                          |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.01x slower                                          |
| pycparser                | 1.18 sec                                               | 1.20 sec: 1.02x slower                                         |
| deepcopy                 | 342 us                                                 | 348 us: 1.02x slower                                           |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.62 ms: 1.03x slower                                          |
| pprint_safe_repr         | 701 ms                                                 | 721 ms: 1.03x slower                                           |
| pathlib                  | 18.2 ms                                                | 18.7 ms: 1.03x slower                                          |
| richards                 | 45.7 ms                                                | 47.1 ms: 1.03x slower                                          |
| pickle_dict              | 31.1 us                                                | 32.2 us: 1.03x slower                                          |
| spectral_norm            | 100 ms                                                 | 104 ms: 1.04x slower                                           |
| float                    | 77.2 ms                                                | 80.2 ms: 1.04x slower                                          |
| dulwich_log              | 63.7 ms                                                | 67.0 ms: 1.05x slower                                          |
| xml_etree_process        | 53.9 ms                                                | 56.7 ms: 1.05x slower                                          |
| pyflate                  | 418 ms                                                 | 446 ms: 1.07x slower                                           |
| deepcopy_reduce          | 2.94 us                                                | 3.14 us: 1.07x slower                                          |
| gc_traversal             | 4.02 ms                                                | 4.31 ms: 1.07x slower                                          |
| pickle                   | 10.1 us                                                | 10.9 us: 1.08x slower                                          |
| scimark_fft              | 328 ms                                                 | 355 ms: 1.08x slower                                           |
| xml_etree_generate       | 76.2 ms                                                | 82.5 ms: 1.08x slower                                          |
| mako                     | 10.1 ms                                                | 10.9 ms: 1.08x slower                                          |
| sqlite_synth             | 2.52 us                                                | 2.75 us: 1.09x slower                                          |
| unpickle                 | 13.7 us                                                | 15.2 us: 1.11x slower                                          |
| regex_dna                | 204 ms                                                 | 227 ms: 1.11x slower                                           |
| python_startup           | 8.52 ms                                                | 9.56 ms: 1.12x slower                                          |
| unpack_sequence          | 43.1 ns                                                | 48.7 ns: 1.13x slower                                          |
| regex_v8                 | 22.0 ms                                                | 25.1 ms: 1.14x slower                                          |
| pickle_list              | 4.11 us                                                | 4.75 us: 1.16x slower                                          |
| python_startup_no_site   | 6.01 ms                                                | 7.00 ms: 1.16x slower                                          |
| telco                    | 6.58 ms                                                | 7.91 ms: 1.20x slower                                          |
| async_generators         | 368 ms                                                 | 451 ms: 1.22x slower                                           |
| dask                     | 360 ms                                                 | 525 ms: 1.46x slower                                           |
| Geometric mean           | (ref)                                                  | 1.04x faster                                                   |

Benchmark hidden because not significant (7): json, go, meteor_contest, bench_mp_pool, docutils, scimark_sor, logging_silent
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 85.88% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
