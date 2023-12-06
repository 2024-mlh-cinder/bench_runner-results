
# Results vs. base

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: fa8a0d5
- commit date: 2023-09-26
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.74 sec: 1.05x slower                                            |
| tornado_http   | 95.7 ms                                                               | 99.4 ms: 1.04x slower                                             |
| Geometric mean | (ref)                                                                 | 1.04x slower                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.01x slower                                              |
| float          | 79.5 ms                                                               | 99.0 ms: 1.25x slower                                             |
| nbody          | 90.8 ms                                                               | 120 ms: 1.32x slower                                              |
| Geometric mean | (ref)                                                                 | 1.18x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_v8       | 24.3 ms                                                               | 23.5 ms: 1.04x faster                                             |
| regex_dna      | 212 ms                                                                | 205 ms: 1.03x faster                                              |
| regex_effbot   | 3.52 ms                                                               | 3.44 ms: 1.02x faster                                             |
| regex_compile  | 134 ms                                                                | 157 ms: 1.17x slower                                              |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| xml_etree_generate   | 86.5 ms                                                               | 84.5 ms: 1.02x faster                                             |
| xml_etree_process    | 59.2 ms                                                               | 57.8 ms: 1.02x faster                                             |
| xml_etree_parse      | 155 ms                                                                | 152 ms: 1.02x faster                                              |
| pickle_dict          | 33.3 us                                                               | 32.9 us: 1.01x faster                                             |
| pickle_list          | 4.59 us                                                               | 4.64 us: 1.01x slower                                             |
| pickle_pure_python   | 295 us                                                                | 299 us: 1.01x slower                                              |
| xml_etree_iterparse  | 103 ms                                                                | 107 ms: 1.05x slower                                              |
| unpickle             | 14.9 us                                                               | 15.9 us: 1.07x slower                                             |
| unpickle_list        | 4.77 us                                                               | 5.17 us: 1.08x slower                                             |
| unpickle_pure_python | 214 us                                                                | 233 us: 1.09x slower                                              |
| tomli_loads          | 2.06 sec                                                              | 2.39 sec: 1.16x slower                                            |
| Geometric mean       | (ref)                                                                 | 1.03x slower                                                      |

Benchmark hidden because not significant (3): json_dumps, json_loads, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 6.87 ms                                                               | 6.84 ms: 1.00x faster                                             |
| python_startup         | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                             |
| Geometric mean         | (ref)                                                                 | 1.00x faster                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.9 ms                                                               | 12.0 ms: 1.10x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-fa8a0d5 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_v8                 | 24.3 ms                                                               | 23.5 ms: 1.04x faster                                             |
| regex_dna                | 212 ms                                                                | 205 ms: 1.03x faster                                              |
| gc_traversal             | 3.98 ms                                                               | 3.87 ms: 1.03x faster                                             |
| xml_etree_generate       | 86.5 ms                                                               | 84.5 ms: 1.02x faster                                             |
| xml_etree_process        | 59.2 ms                                                               | 57.8 ms: 1.02x faster                                             |
| create_gc_cycles         | 1.54 ms                                                               | 1.51 ms: 1.02x faster                                             |
| coroutines               | 22.4 ms                                                               | 21.9 ms: 1.02x faster                                             |
| regex_effbot             | 3.52 ms                                                               | 3.44 ms: 1.02x faster                                             |
| xml_etree_parse          | 155 ms                                                                | 152 ms: 1.02x faster                                              |
| sqlite_synth             | 2.75 us                                                               | 2.70 us: 1.02x faster                                             |
| json                     | 4.98 ms                                                               | 4.90 ms: 1.02x faster                                             |
| pickle_dict              | 33.3 us                                                               | 32.9 us: 1.01x faster                                             |
| python_startup_no_site   | 6.87 ms                                                               | 6.84 ms: 1.00x faster                                             |
| python_startup           | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                             |
| pidigits                 | 187 ms                                                                | 188 ms: 1.01x slower                                              |
| deepcopy_reduce          | 3.15 us                                                               | 3.18 us: 1.01x slower                                             |
| asyncio_tcp              | 507 ms                                                                | 511 ms: 1.01x slower                                              |
| logging_format           | 6.77 us                                                               | 6.83 us: 1.01x slower                                             |
| mdp                      | 2.64 sec                                                              | 2.67 sec: 1.01x slower                                            |
| pickle_list              | 4.59 us                                                               | 4.64 us: 1.01x slower                                             |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.82 sec: 1.01x slower                                            |
| pickle_pure_python       | 295 us                                                                | 299 us: 1.01x slower                                              |
| sqlglot_normalize        | 106 ms                                                                | 107 ms: 1.01x slower                                              |
| async_tree_cpu_io_mixed  | 707 ms                                                                | 717 ms: 1.01x slower                                              |
| deepcopy                 | 352 us                                                                | 357 us: 1.02x slower                                              |
| async_generators         | 451 ms                                                                | 459 ms: 1.02x slower                                              |
| pathlib                  | 18.7 ms                                                               | 19.0 ms: 1.02x slower                                             |
| async_tree_memoization   | 564 ms                                                                | 576 ms: 1.02x slower                                              |
| dask                     | 525 ms                                                                | 538 ms: 1.02x slower                                              |
| async_tree_none          | 438 ms                                                                | 450 ms: 1.03x slower                                              |
| sqlglot_optimize         | 53.2 ms                                                               | 54.6 ms: 1.03x slower                                             |
| richards_super           | 55.3 ms                                                               | 57.0 ms: 1.03x slower                                             |
| scimark_sor              | 118 ms                                                                | 122 ms: 1.03x slower                                              |
| richards                 | 48.8 ms                                                               | 50.6 ms: 1.04x slower                                             |
| spectral_norm            | 106 ms                                                                | 110 ms: 1.04x slower                                              |
| mypy2                    | 338 ms                                                                | 351 ms: 1.04x slower                                              |
| tornado_http             | 95.7 ms                                                               | 99.4 ms: 1.04x slower                                             |
| telco                    | 7.99 ms                                                               | 8.29 ms: 1.04x slower                                             |
| bench_thread_pool        | 808 us                                                                | 839 us: 1.04x slower                                              |
| sqlglot_transpile        | 1.59 ms                                                               | 1.65 ms: 1.04x slower                                             |
| dulwich_log              | 66.3 ms                                                               | 69.2 ms: 1.04x slower                                             |
| crypto_pyaes             | 70.1 ms                                                               | 73.2 ms: 1.04x slower                                             |
| docutils                 | 2.62 sec                                                              | 2.74 sec: 1.05x slower                                            |
| xml_etree_iterparse      | 103 ms                                                                | 107 ms: 1.05x slower                                              |
| sqlglot_parse            | 1.27 ms                                                               | 1.33 ms: 1.05x slower                                             |
| scimark_lu               | 111 ms                                                                | 117 ms: 1.05x slower                                              |
| typing_runtime_protocols | 142 us                                                                | 150 us: 1.06x slower                                              |
| unpickle                 | 14.9 us                                                               | 15.9 us: 1.07x slower                                             |
| meteor_contest           | 107 ms                                                                | 115 ms: 1.08x slower                                              |
| unpickle_list            | 4.77 us                                                               | 5.17 us: 1.08x slower                                             |
| unpickle_pure_python     | 214 us                                                                | 233 us: 1.09x slower                                              |
| go                       | 139 ms                                                                | 152 ms: 1.10x slower                                              |
| mako                     | 10.9 ms                                                               | 12.0 ms: 1.10x slower                                             |
| deepcopy_memo            | 37.3 us                                                               | 41.1 us: 1.10x slower                                             |
| pprint_safe_repr         | 724 ms                                                                | 799 ms: 1.10x slower                                              |
| scimark_monte_carlo      | 65.6 ms                                                               | 73.2 ms: 1.12x slower                                             |
| unpack_sequence          | 45.5 ns                                                               | 50.9 ns: 1.12x slower                                             |
| pprint_pformat           | 1.48 sec                                                              | 1.66 sec: 1.12x slower                                            |
| raytrace                 | 266 ms                                                                | 299 ms: 1.12x slower                                              |
| fannkuch                 | 388 ms                                                                | 449 ms: 1.16x slower                                              |
| tomli_loads              | 2.06 sec                                                              | 2.39 sec: 1.16x slower                                            |
| regex_compile            | 134 ms                                                                | 157 ms: 1.17x slower                                              |
| pyflate                  | 456 ms                                                                | 547 ms: 1.20x slower                                              |
| scimark_fft              | 358 ms                                                                | 431 ms: 1.20x slower                                              |
| chaos                    | 60.5 ms                                                               | 73.1 ms: 1.21x slower                                             |
| deltablue                | 3.29 ms                                                               | 4.09 ms: 1.24x slower                                             |
| float                    | 79.5 ms                                                               | 99.0 ms: 1.25x slower                                             |
| nqueens                  | 78.4 ms                                                               | 98.7 ms: 1.26x slower                                             |
| scimark_sparse_mat_mult  | 4.51 ms                                                               | 5.83 ms: 1.29x slower                                             |
| nbody                    | 90.8 ms                                                               | 120 ms: 1.32x slower                                              |
| comprehensions           | 20.3 us                                                               | 27.1 us: 1.33x slower                                             |
| hexiom                   | 6.00 ms                                                               | 9.03 ms: 1.51x slower                                             |
| Geometric mean           | (ref)                                                                 | 1.06x slower                                                      |

Benchmark hidden because not significant (10): logging_simple, coverage, pycparser, json_dumps, bench_mp_pool, generators, async_tree_io, json_loads, logging_silent, pickle


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
