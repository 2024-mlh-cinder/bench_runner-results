
# Results vs. 3.11.0

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 53917a5
- commit date: 2023-09-07
- overall geometric mean: 1.05x faster
- HPT reliability: 97.40%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.60 sec: 1.01x faster                                         |
| tornado_http   | 96.3 ms                                                | 94.7 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                  | 1.01x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                           |
| nbody          | 93.1 ms                                                | 88.7 ms: 1.05x faster                                          |
| float          | 77.2 ms                                                | 78.9 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                  | 1.03x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.47 ms: 1.15x faster                                          |
| regex_compile  | 138 ms                                                 | 134 ms: 1.03x faster                                           |
| regex_dna      | 204 ms                                                 | 208 ms: 1.02x slower                                           |
| regex_v8       | 22.0 ms                                                | 23.6 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.90 ms: 1.27x faster                                          |
| tomli_loads          | 2.22 sec                                               | 2.06 sec: 1.08x faster                                         |
| unpickle_pure_python | 228 us                                                 | 216 us: 1.06x faster                                           |
| json_loads           | 26.5 us                                                | 25.2 us: 1.05x faster                                          |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.05x faster                                           |
| pickle_pure_python   | 306 us                                                 | 300 us: 1.02x faster                                           |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                           |
| unpickle             | 13.7 us                                                | 14.6 us: 1.07x slower                                          |
| xml_etree_process    | 53.9 ms                                                | 57.7 ms: 1.07x slower                                          |
| pickle               | 10.1 us                                                | 10.8 us: 1.07x slower                                          |
| xml_etree_generate   | 76.2 ms                                                | 83.2 ms: 1.09x slower                                          |
| pickle_list          | 4.11 us                                                | 4.75 us: 1.15x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (2): unpickle_list, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.81 ms: 1.13x slower                                          |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                          |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.5 ms: 1.04x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 141 us: 3.44x faster                                           |
| generators               | 73.5 ms                                                | 29.3 ms: 2.51x faster                                          |
| asyncio_tcp              | 922 ms                                                 | 481 ms: 1.92x faster                                           |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.75x faster                                         |
| json_dumps               | 12.6 ms                                                | 9.90 ms: 1.27x faster                                          |
| mypy2                    | 420 ms                                                 | 337 ms: 1.25x faster                                           |
| async_tree_none          | 526 ms                                                 | 438 ms: 1.20x faster                                           |
| coroutines               | 25.5 ms                                                | 21.6 ms: 1.18x faster                                          |
| coverage                 | 100 ms                                                 | 85.6 ms: 1.17x faster                                          |
| regex_effbot             | 3.99 ms                                                | 3.47 ms: 1.15x faster                                          |
| chaos                    | 69.2 ms                                                | 60.4 ms: 1.15x faster                                          |
| deltablue                | 3.67 ms                                                | 3.28 ms: 1.12x faster                                          |
| async_tree_memoization   | 627 ms                                                 | 562 ms: 1.12x faster                                           |
| raytrace                 | 297 ms                                                 | 268 ms: 1.11x faster                                           |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.10x faster                                          |
| crypto_pyaes             | 74.7 ms                                                | 68.3 ms: 1.09x faster                                          |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                         |
| comprehensions           | 22.4 us                                                | 20.7 us: 1.09x faster                                          |
| tomli_loads              | 2.22 sec                                               | 2.06 sec: 1.08x faster                                         |
| sqlglot_transpile        | 1.70 ms                                                | 1.60 ms: 1.07x faster                                          |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                           |
| hexiom                   | 6.37 ms                                                | 6.02 ms: 1.06x faster                                          |
| nqueens                  | 83.4 ms                                                | 78.8 ms: 1.06x faster                                          |
| unpickle_pure_python     | 228 us                                                 | 216 us: 1.06x faster                                           |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 701 ms: 1.05x faster                                           |
| nbody                    | 93.1 ms                                                | 88.7 ms: 1.05x faster                                          |
| json_loads               | 26.5 us                                                | 25.2 us: 1.05x faster                                          |
| richards_super           | 56.8 ms                                                | 54.2 ms: 1.05x faster                                          |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.05x faster                                           |
| scimark_monte_carlo      | 68.1 ms                                                | 65.3 ms: 1.04x faster                                          |
| mdp                      | 2.62 sec                                               | 2.53 sec: 1.04x faster                                         |
| json                     | 4.94 ms                                                | 4.78 ms: 1.03x faster                                          |
| sqlglot_normalize        | 108 ms                                                 | 105 ms: 1.03x faster                                           |
| pycparser                | 1.18 sec                                               | 1.15 sec: 1.03x faster                                         |
| logging_simple           | 6.03 us                                                | 5.86 us: 1.03x faster                                          |
| regex_compile            | 138 ms                                                 | 134 ms: 1.03x faster                                           |
| fannkuch                 | 388 ms                                                 | 378 ms: 1.02x faster                                           |
| logging_format           | 6.68 us                                                | 6.53 us: 1.02x faster                                          |
| pickle_pure_python       | 306 us                                                 | 300 us: 1.02x faster                                           |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                           |
| tornado_http             | 96.3 ms                                                | 94.7 ms: 1.02x faster                                          |
| go                       | 140 ms                                                 | 138 ms: 1.02x faster                                           |
| bench_thread_pool        | 819 us                                                 | 806 us: 1.02x faster                                           |
| sqlglot_optimize         | 53.1 ms                                                | 52.3 ms: 1.01x faster                                          |
| deepcopy_memo            | 37.0 us                                                | 36.5 us: 1.01x faster                                          |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.01x faster                                           |
| docutils                 | 2.63 sec                                               | 2.60 sec: 1.01x faster                                         |
| deepcopy                 | 342 us                                                 | 344 us: 1.00x slower                                           |
| scimark_lu               | 110 ms                                                 | 111 ms: 1.01x slower                                           |
| pprint_pformat           | 1.46 sec                                               | 1.48 sec: 1.02x slower                                         |
| gc_traversal             | 4.02 ms                                                | 4.10 ms: 1.02x slower                                          |
| regex_dna                | 204 ms                                                 | 208 ms: 1.02x slower                                           |
| scimark_sor              | 118 ms                                                 | 121 ms: 1.02x slower                                           |
| create_gc_cycles         | 1.49 ms                                                | 1.52 ms: 1.02x slower                                          |
| float                    | 77.2 ms                                                | 78.9 ms: 1.02x slower                                          |
| pathlib                  | 18.2 ms                                                | 18.6 ms: 1.02x slower                                          |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.63 ms: 1.03x slower                                          |
| dulwich_log              | 63.7 ms                                                | 66.1 ms: 1.04x slower                                          |
| mako                     | 10.1 ms                                                | 10.5 ms: 1.04x slower                                          |
| pprint_safe_repr         | 701 ms                                                 | 730 ms: 1.04x slower                                           |
| spectral_norm            | 100 ms                                                 | 105 ms: 1.05x slower                                           |
| deepcopy_reduce          | 2.94 us                                                | 3.10 us: 1.05x slower                                          |
| richards                 | 45.7 ms                                                | 48.6 ms: 1.06x slower                                          |
| pyflate                  | 418 ms                                                 | 447 ms: 1.07x slower                                           |
| unpickle                 | 13.7 us                                                | 14.6 us: 1.07x slower                                          |
| regex_v8                 | 22.0 ms                                                | 23.6 ms: 1.07x slower                                          |
| xml_etree_process        | 53.9 ms                                                | 57.7 ms: 1.07x slower                                          |
| pickle                   | 10.1 us                                                | 10.8 us: 1.07x slower                                          |
| scimark_fft              | 328 ms                                                 | 354 ms: 1.08x slower                                           |
| xml_etree_generate       | 76.2 ms                                                | 83.2 ms: 1.09x slower                                          |
| sqlite_synth             | 2.52 us                                                | 2.76 us: 1.10x slower                                          |
| python_startup_no_site   | 6.01 ms                                                | 6.81 ms: 1.13x slower                                          |
| pickle_list              | 4.11 us                                                | 4.75 us: 1.15x slower                                          |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                          |
| async_generators         | 368 ms                                                 | 446 ms: 1.21x slower                                           |
| telco                    | 6.58 ms                                                | 8.00 ms: 1.22x slower                                          |
| dask                     | 360 ms                                                 | 523 ms: 1.45x slower                                           |
| Geometric mean           | (ref)                                                  | 1.05x faster                                                   |

Benchmark hidden because not significant (5): unpickle_list, logging_silent, bench_mp_pool, pickle_dict, unpack_sequence
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.40% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
