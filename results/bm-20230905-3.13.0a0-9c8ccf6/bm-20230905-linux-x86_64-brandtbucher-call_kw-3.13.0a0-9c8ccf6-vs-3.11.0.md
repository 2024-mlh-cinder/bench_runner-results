
# Results vs. 3.11.0

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 9c8ccf6
- commit date: 2023-09-05
- overall geometric mean: 1.05x faster
- HPT reliability: 89.36%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tornado_http   | 96.3 ms                                                | 95.3 ms: 1.01x faster                                          |
| Geometric mean | (ref)                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.06x faster                                           |
| nbody          | 93.1 ms                                                | 92.3 ms: 1.01x faster                                          |
| float          | 77.2 ms                                                | 79.1 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                  | 1.01x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.74 ms: 1.07x faster                                          |
| regex_compile  | 138 ms                                                 | 135 ms: 1.02x faster                                           |
| regex_dna      | 204 ms                                                 | 220 ms: 1.08x slower                                           |
| regex_v8       | 22.0 ms                                                | 24.6 ms: 1.12x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.75 ms: 1.29x faster                                          |
| unpickle_pure_python | 228 us                                                 | 210 us: 1.08x faster                                           |
| xml_etree_parse      | 158 ms                                                 | 151 ms: 1.05x faster                                           |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                         |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                          |
| pickle_pure_python   | 306 us                                                 | 294 us: 1.04x faster                                           |
| xml_etree_iterparse  | 104 ms                                                 | 101 ms: 1.02x faster                                           |
| pickle_dict          | 31.1 us                                                | 31.5 us: 1.01x slower                                          |
| unpickle_list        | 4.91 us                                                | 5.06 us: 1.03x slower                                          |
| pickle               | 10.1 us                                                | 10.5 us: 1.04x slower                                          |
| xml_etree_process    | 53.9 ms                                                | 56.4 ms: 1.05x slower                                          |
| unpickle             | 13.7 us                                                | 14.5 us: 1.06x slower                                          |
| xml_etree_generate   | 76.2 ms                                                | 81.3 ms: 1.07x slower                                          |
| pickle_list          | 4.11 us                                                | 4.66 us: 1.13x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.48 ms: 1.11x slower                                          |
| python_startup_no_site | 6.01 ms                                                | 6.97 ms: 1.16x slower                                          |
| Geometric mean         | (ref)                                                  | 1.14x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.7 ms: 1.06x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 142 us: 3.43x faster                                           |
| generators               | 73.5 ms                                                | 29.0 ms: 2.53x faster                                          |
| asyncio_tcp              | 922 ms                                                 | 489 ms: 1.89x faster                                           |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                         |
| json_dumps               | 12.6 ms                                                | 9.75 ms: 1.29x faster                                          |
| mypy2                    | 420 ms                                                 | 338 ms: 1.24x faster                                           |
| async_tree_none          | 526 ms                                                 | 440 ms: 1.20x faster                                           |
| chaos                    | 69.2 ms                                                | 58.7 ms: 1.18x faster                                          |
| coroutines               | 25.5 ms                                                | 22.1 ms: 1.16x faster                                          |
| coverage                 | 100 ms                                                 | 87.0 ms: 1.15x faster                                          |
| deltablue                | 3.67 ms                                                | 3.26 ms: 1.13x faster                                          |
| sqlglot_parse            | 1.40 ms                                                | 1.25 ms: 1.12x faster                                          |
| async_tree_memoization   | 627 ms                                                 | 566 ms: 1.11x faster                                           |
| crypto_pyaes             | 74.7 ms                                                | 68.5 ms: 1.09x faster                                          |
| sqlglot_transpile        | 1.70 ms                                                | 1.56 ms: 1.09x faster                                          |
| raytrace                 | 297 ms                                                 | 273 ms: 1.09x faster                                           |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.08x faster                                         |
| unpickle_pure_python     | 228 us                                                 | 210 us: 1.08x faster                                           |
| comprehensions           | 22.4 us                                                | 21.0 us: 1.07x faster                                          |
| hexiom                   | 6.37 ms                                                | 5.97 ms: 1.07x faster                                          |
| regex_effbot             | 3.99 ms                                                | 3.74 ms: 1.07x faster                                          |
| richards_super           | 56.8 ms                                                | 53.7 ms: 1.06x faster                                          |
| pidigits                 | 198 ms                                                 | 188 ms: 1.06x faster                                           |
| xml_etree_parse          | 158 ms                                                 | 151 ms: 1.05x faster                                           |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 704 ms: 1.05x faster                                           |
| sqlglot_normalize        | 108 ms                                                 | 103 ms: 1.05x faster                                           |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                         |
| nqueens                  | 83.4 ms                                                | 79.7 ms: 1.05x faster                                          |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                          |
| pickle_pure_python       | 306 us                                                 | 294 us: 1.04x faster                                           |
| scimark_monte_carlo      | 68.1 ms                                                | 65.8 ms: 1.03x faster                                          |
| fannkuch                 | 388 ms                                                 | 375 ms: 1.03x faster                                           |
| logging_format           | 6.68 us                                                | 6.51 us: 1.03x faster                                          |
| xml_etree_iterparse      | 104 ms                                                 | 101 ms: 1.02x faster                                           |
| regex_compile            | 138 ms                                                 | 135 ms: 1.02x faster                                           |
| logging_simple           | 6.03 us                                                | 5.92 us: 1.02x faster                                          |
| sqlglot_optimize         | 53.1 ms                                                | 52.2 ms: 1.02x faster                                          |
| mdp                      | 2.62 sec                                               | 2.57 sec: 1.02x faster                                         |
| deepcopy_memo            | 37.0 us                                                | 36.6 us: 1.01x faster                                          |
| tornado_http             | 96.3 ms                                                | 95.3 ms: 1.01x faster                                          |
| bench_thread_pool        | 819 us                                                 | 811 us: 1.01x faster                                           |
| nbody                    | 93.1 ms                                                | 92.3 ms: 1.01x faster                                          |
| scimark_lu               | 110 ms                                                 | 109 ms: 1.01x faster                                           |
| go                       | 140 ms                                                 | 139 ms: 1.01x faster                                           |
| create_gc_cycles         | 1.49 ms                                                | 1.50 ms: 1.01x slower                                          |
| pickle_dict              | 31.1 us                                                | 31.5 us: 1.01x slower                                          |
| deepcopy                 | 342 us                                                 | 346 us: 1.01x slower                                           |
| pycparser                | 1.18 sec                                               | 1.20 sec: 1.01x slower                                         |
| pprint_pformat           | 1.46 sec                                               | 1.48 sec: 1.01x slower                                         |
| gc_traversal             | 4.02 ms                                                | 4.08 ms: 1.01x slower                                          |
| logging_silent           | 101 ns                                                 | 103 ns: 1.01x slower                                           |
| float                    | 77.2 ms                                                | 79.1 ms: 1.02x slower                                          |
| unpickle_list            | 4.91 us                                                | 5.06 us: 1.03x slower                                          |
| pathlib                  | 18.2 ms                                                | 18.8 ms: 1.03x slower                                          |
| pprint_safe_repr         | 701 ms                                                 | 724 ms: 1.03x slower                                           |
| richards                 | 45.7 ms                                                | 47.3 ms: 1.03x slower                                          |
| pickle                   | 10.1 us                                                | 10.5 us: 1.04x slower                                          |
| unpack_sequence          | 43.1 ns                                                | 45.0 ns: 1.04x slower                                          |
| xml_etree_process        | 53.9 ms                                                | 56.4 ms: 1.05x slower                                          |
| deepcopy_reduce          | 2.94 us                                                | 3.08 us: 1.05x slower                                          |
| dulwich_log              | 63.7 ms                                                | 67.2 ms: 1.06x slower                                          |
| spectral_norm            | 100 ms                                                 | 106 ms: 1.06x slower                                           |
| unpickle                 | 13.7 us                                                | 14.5 us: 1.06x slower                                          |
| mako                     | 10.1 ms                                                | 10.7 ms: 1.06x slower                                          |
| xml_etree_generate       | 76.2 ms                                                | 81.3 ms: 1.07x slower                                          |
| regex_dna                | 204 ms                                                 | 220 ms: 1.08x slower                                           |
| pyflate                  | 418 ms                                                 | 452 ms: 1.08x slower                                           |
| scimark_fft              | 328 ms                                                 | 356 ms: 1.08x slower                                           |
| sqlite_synth             | 2.52 us                                                | 2.73 us: 1.08x slower                                          |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.89 ms: 1.09x slower                                          |
| python_startup           | 8.52 ms                                                | 9.48 ms: 1.11x slower                                          |
| regex_v8                 | 22.0 ms                                                | 24.6 ms: 1.12x slower                                          |
| pickle_list              | 4.11 us                                                | 4.66 us: 1.13x slower                                          |
| python_startup_no_site   | 6.01 ms                                                | 6.97 ms: 1.16x slower                                          |
| telco                    | 6.58 ms                                                | 7.96 ms: 1.21x slower                                          |
| async_generators         | 368 ms                                                 | 447 ms: 1.21x slower                                           |
| dask                     | 360 ms                                                 | 519 ms: 1.44x slower                                           |
| Geometric mean           | (ref)                                                  | 1.05x faster                                                   |

Benchmark hidden because not significant (5): meteor_contest, scimark_sor, bench_mp_pool, docutils, json
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 89.36% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
