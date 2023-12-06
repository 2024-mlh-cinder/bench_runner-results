
# Results vs. 3.11.0

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: 825ff87
- commit date: 2023-09-07
- overall geometric mean: 1.00x slower
- HPT reliability: 99.16%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.72 sec: 1.03x slower                                            |
| tornado_http   | 96.3 ms                                                | 97.8 ms: 1.02x slower                                             |
| Geometric mean | (ref)                                                  | 1.02x slower                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                              |
| float          | 77.2 ms                                                | 84.9 ms: 1.10x slower                                             |
| nbody          | 93.1 ms                                                | 106 ms: 1.13x slower                                              |
| Geometric mean | (ref)                                                  | 1.06x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.82 ms: 1.05x faster                                             |
| regex_dna      | 204 ms                                                 | 220 ms: 1.08x slower                                              |
| regex_compile  | 138 ms                                                 | 152 ms: 1.10x slower                                              |
| regex_v8       | 22.0 ms                                                | 25.0 ms: 1.13x slower                                             |
| Geometric mean | (ref)                                                  | 1.07x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.90 ms: 1.27x faster                                             |
| json_loads           | 26.5 us                                                | 25.2 us: 1.05x faster                                             |
| xml_etree_parse      | 158 ms                                                 | 153 ms: 1.03x faster                                              |
| pickle_pure_python   | 306 us                                                 | 303 us: 1.01x faster                                              |
| unpickle_list        | 4.91 us                                                | 4.87 us: 1.01x faster                                             |
| pickle_dict          | 31.1 us                                                | 31.3 us: 1.01x slower                                             |
| unpickle_pure_python | 228 us                                                 | 238 us: 1.04x slower                                              |
| xml_etree_process    | 53.9 ms                                                | 56.9 ms: 1.06x slower                                             |
| pickle               | 10.1 us                                                | 10.8 us: 1.07x slower                                             |
| tomli_loads          | 2.22 sec                                               | 2.39 sec: 1.08x slower                                            |
| xml_etree_generate   | 76.2 ms                                                | 83.3 ms: 1.09x slower                                             |
| pickle_list          | 4.11 us                                                | 4.59 us: 1.12x slower                                             |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.54 ms: 1.12x slower                                             |
| python_startup_no_site | 6.01 ms                                                | 7.01 ms: 1.17x slower                                             |
| Geometric mean         | (ref)                                                  | 1.14x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.9 ms: 1.18x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 153 us: 3.19x faster                                              |
| generators               | 73.5 ms                                                | 29.8 ms: 2.47x faster                                             |
| asyncio_tcp              | 922 ms                                                 | 492 ms: 1.87x faster                                              |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.75x faster                                            |
| json_dumps               | 12.6 ms                                                | 9.90 ms: 1.27x faster                                             |
| mypy2                    | 420 ms                                                 | 350 ms: 1.20x faster                                              |
| async_tree_none          | 526 ms                                                 | 447 ms: 1.18x faster                                              |
| coroutines               | 25.5 ms                                                | 22.7 ms: 1.12x faster                                             |
| coverage                 | 100 ms                                                 | 89.2 ms: 1.12x faster                                             |
| sqlglot_parse            | 1.40 ms                                                | 1.29 ms: 1.09x faster                                             |
| async_tree_memoization   | 627 ms                                                 | 580 ms: 1.08x faster                                              |
| async_tree_io            | 1.30 sec                                               | 1.21 sec: 1.07x faster                                            |
| sqlglot_transpile        | 1.70 ms                                                | 1.60 ms: 1.06x faster                                             |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                              |
| raytrace                 | 297 ms                                                 | 281 ms: 1.05x faster                                              |
| deltablue                | 3.67 ms                                                | 3.49 ms: 1.05x faster                                             |
| gc_traversal             | 4.02 ms                                                | 3.83 ms: 1.05x faster                                             |
| json_loads               | 26.5 us                                                | 25.2 us: 1.05x faster                                             |
| regex_effbot             | 3.99 ms                                                | 3.82 ms: 1.05x faster                                             |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 708 ms: 1.04x faster                                              |
| xml_etree_parse          | 158 ms                                                 | 153 ms: 1.03x faster                                              |
| crypto_pyaes             | 74.7 ms                                                | 72.4 ms: 1.03x faster                                             |
| richards_super           | 56.8 ms                                                | 55.4 ms: 1.03x faster                                             |
| sqlglot_normalize        | 108 ms                                                 | 105 ms: 1.02x faster                                              |
| chaos                    | 69.2 ms                                                | 68.4 ms: 1.01x faster                                             |
| pickle_pure_python       | 306 us                                                 | 303 us: 1.01x faster                                              |
| unpickle_list            | 4.91 us                                                | 4.87 us: 1.01x faster                                             |
| pickle_dict              | 31.1 us                                                | 31.3 us: 1.01x slower                                             |
| sqlglot_optimize         | 53.1 ms                                                | 53.6 ms: 1.01x slower                                             |
| scimark_monte_carlo      | 68.1 ms                                                | 68.7 ms: 1.01x slower                                             |
| logging_simple           | 6.03 us                                                | 6.10 us: 1.01x slower                                             |
| logging_silent           | 101 ns                                                 | 102 ns: 1.01x slower                                              |
| tornado_http             | 96.3 ms                                                | 97.8 ms: 1.02x slower                                             |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                             |
| logging_format           | 6.68 us                                                | 6.82 us: 1.02x slower                                             |
| docutils                 | 2.63 sec                                               | 2.72 sec: 1.03x slower                                            |
| bench_thread_pool        | 819 us                                                 | 847 us: 1.03x slower                                              |
| pathlib                  | 18.2 ms                                                | 18.9 ms: 1.04x slower                                             |
| json                     | 4.94 ms                                                | 5.15 ms: 1.04x slower                                             |
| unpickle_pure_python     | 228 us                                                 | 238 us: 1.04x slower                                              |
| scimark_sor              | 118 ms                                                 | 123 ms: 1.04x slower                                              |
| pycparser                | 1.18 sec                                               | 1.24 sec: 1.05x slower                                            |
| pprint_pformat           | 1.46 sec                                               | 1.53 sec: 1.05x slower                                            |
| deepcopy                 | 342 us                                                 | 360 us: 1.05x slower                                              |
| xml_etree_process        | 53.9 ms                                                | 56.9 ms: 1.06x slower                                             |
| go                       | 140 ms                                                 | 149 ms: 1.07x slower                                              |
| pprint_safe_repr         | 701 ms                                                 | 749 ms: 1.07x slower                                              |
| pickle                   | 10.1 us                                                | 10.8 us: 1.07x slower                                             |
| dulwich_log              | 63.7 ms                                                | 68.4 ms: 1.07x slower                                             |
| tomli_loads              | 2.22 sec                                               | 2.39 sec: 1.08x slower                                            |
| scimark_lu               | 110 ms                                                 | 118 ms: 1.08x slower                                              |
| regex_dna                | 204 ms                                                 | 220 ms: 1.08x slower                                              |
| meteor_contest           | 107 ms                                                 | 115 ms: 1.08x slower                                              |
| mdp                      | 2.62 sec                                               | 2.84 sec: 1.09x slower                                            |
| spectral_norm            | 100 ms                                                 | 109 ms: 1.09x slower                                              |
| xml_etree_generate       | 76.2 ms                                                | 83.3 ms: 1.09x slower                                             |
| richards                 | 45.7 ms                                                | 50.0 ms: 1.09x slower                                             |
| sqlite_synth             | 2.52 us                                                | 2.77 us: 1.10x slower                                             |
| float                    | 77.2 ms                                                | 84.9 ms: 1.10x slower                                             |
| regex_compile            | 138 ms                                                 | 152 ms: 1.10x slower                                              |
| deepcopy_reduce          | 2.94 us                                                | 3.25 us: 1.11x slower                                             |
| pickle_list              | 4.11 us                                                | 4.59 us: 1.12x slower                                             |
| deepcopy_memo            | 37.0 us                                                | 41.4 us: 1.12x slower                                             |
| python_startup           | 8.52 ms                                                | 9.54 ms: 1.12x slower                                             |
| comprehensions           | 22.4 us                                                | 25.2 us: 1.12x slower                                             |
| nbody                    | 93.1 ms                                                | 106 ms: 1.13x slower                                              |
| regex_v8                 | 22.0 ms                                                | 25.0 ms: 1.13x slower                                             |
| fannkuch                 | 388 ms                                                 | 444 ms: 1.14x slower                                              |
| nqueens                  | 83.4 ms                                                | 96.7 ms: 1.16x slower                                             |
| python_startup_no_site   | 6.01 ms                                                | 7.01 ms: 1.17x slower                                             |
| pyflate                  | 418 ms                                                 | 491 ms: 1.17x slower                                              |
| mako                     | 10.1 ms                                                | 11.9 ms: 1.18x slower                                             |
| scimark_fft              | 328 ms                                                 | 388 ms: 1.18x slower                                              |
| hexiom                   | 6.37 ms                                                | 7.68 ms: 1.21x slower                                             |
| async_generators         | 368 ms                                                 | 461 ms: 1.25x slower                                              |
| telco                    | 6.58 ms                                                | 8.25 ms: 1.25x slower                                             |
| unpack_sequence          | 43.1 ns                                                | 55.0 ns: 1.28x slower                                             |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.89 ms: 1.31x slower                                             |
| dask                     | 360 ms                                                 | 534 ms: 1.48x slower                                              |
| Geometric mean           | (ref)                                                  | 1.00x slower                                                      |

Benchmark hidden because not significant (3): xml_etree_iterparse, bench_mp_pool, unpickle
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.16% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
