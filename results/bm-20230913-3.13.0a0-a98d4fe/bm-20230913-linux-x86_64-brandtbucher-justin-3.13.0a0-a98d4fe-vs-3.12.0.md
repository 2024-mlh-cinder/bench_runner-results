
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.04x slower
- HPT reliability: 99.89%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| tornado_http   | 99.6 ms                                                | 97.4 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                  | 1.01x faster                                                  |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                          |
| float          | 80.7 ms                                                | 83.2 ms: 1.03x slower                                         |
| nbody          | 88.8 ms                                                | 120 ms: 1.35x slower                                          |
| Geometric mean | (ref)                                                  | 1.12x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 210 ms: 1.01x slower                                          |
| regex_effbot   | 3.55 ms                                                | 3.62 ms: 1.02x slower                                         |
| regex_compile  | 144 ms                                                 | 148 ms: 1.03x slower                                          |
| regex_v8       | 22.3 ms                                                | 24.0 ms: 1.08x slower                                         |
| Geometric mean | (ref)                                                  | 1.03x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.2 us: 1.05x faster                                         |
| unpickle_list        | 4.95 us                                                | 4.83 us: 1.02x faster                                         |
| xml_etree_generate   | 84.8 ms                                                | 83.4 ms: 1.02x faster                                         |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                          |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                          |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                         |
| json_loads           | 25.2 us                                                | 25.1 us: 1.01x faster                                         |
| xml_etree_process    | 58.6 ms                                                | 58.1 ms: 1.01x faster                                         |
| pickle_list          | 4.62 us                                                | 4.81 us: 1.04x slower                                         |
| tomli_loads          | 2.22 sec                                               | 2.35 sec: 1.06x slower                                        |
| unpickle_pure_python | 218 us                                                 | 234 us: 1.07x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (3): json_dumps, pickle_pure_python, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.84 ms: 1.01x faster                                         |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                         |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.3 ms: 1.05x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| generators               | 31.1 ms                                                | 28.1 ms: 1.11x faster                                         |
| coverage                 | 94.2 ms                                                | 85.3 ms: 1.10x faster                                         |
| asyncio_tcp              | 526 ms                                                 | 496 ms: 1.06x faster                                          |
| raytrace                 | 294 ms                                                 | 279 ms: 1.06x faster                                          |
| unpickle                 | 15.0 us                                                | 14.2 us: 1.05x faster                                         |
| async_tree_none          | 469 ms                                                 | 447 ms: 1.05x faster                                          |
| gc_traversal             | 3.84 ms                                                | 3.69 ms: 1.04x faster                                         |
| scimark_monte_carlo      | 71.0 ms                                                | 68.3 ms: 1.04x faster                                         |
| coroutines               | 22.4 ms                                                | 21.8 ms: 1.03x faster                                         |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.03x faster                                         |
| unpickle_list            | 4.95 us                                                | 4.83 us: 1.02x faster                                         |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.02x faster                                         |
| crypto_pyaes             | 77.2 ms                                                | 75.5 ms: 1.02x faster                                         |
| tornado_http             | 99.6 ms                                                | 97.4 ms: 1.02x faster                                         |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                          |
| xml_etree_generate       | 84.8 ms                                                | 83.4 ms: 1.02x faster                                         |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                          |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                         |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                          |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                          |
| python_startup_no_site   | 6.90 ms                                                | 6.84 ms: 1.01x faster                                         |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                         |
| json_loads               | 25.2 us                                                | 25.1 us: 1.01x faster                                         |
| xml_etree_process        | 58.6 ms                                                | 58.1 ms: 1.01x faster                                         |
| sqlglot_optimize         | 53.3 ms                                                | 53.6 ms: 1.01x slower                                         |
| regex_dna                | 209 ms                                                 | 210 ms: 1.01x slower                                          |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.81 sec: 1.01x slower                                        |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                          |
| logging_simple           | 6.18 us                                                | 6.28 us: 1.02x slower                                         |
| regex_effbot             | 3.55 ms                                                | 3.62 ms: 1.02x slower                                         |
| deepcopy_reduce          | 3.14 us                                                | 3.21 us: 1.02x slower                                         |
| spectral_norm            | 106 ms                                                 | 109 ms: 1.02x slower                                          |
| dulwich_log              | 67.9 ms                                                | 69.5 ms: 1.02x slower                                         |
| mypy2                    | 344 ms                                                 | 354 ms: 1.03x slower                                          |
| float                    | 80.7 ms                                                | 83.2 ms: 1.03x slower                                         |
| regex_compile            | 144 ms                                                 | 148 ms: 1.03x slower                                          |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.93 ms: 1.04x slower                                         |
| pathlib                  | 18.5 ms                                                | 19.2 ms: 1.04x slower                                         |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.04x slower                                        |
| pickle_list              | 4.62 us                                                | 4.81 us: 1.04x slower                                         |
| async_generators         | 440 ms                                                 | 463 ms: 1.05x slower                                          |
| pprint_safe_repr         | 735 ms                                                 | 773 ms: 1.05x slower                                          |
| deepcopy                 | 355 us                                                 | 374 us: 1.05x slower                                          |
| bench_thread_pool        | 827 us                                                 | 871 us: 1.05x slower                                          |
| scimark_fft              | 358 ms                                                 | 378 ms: 1.05x slower                                          |
| mako                     | 10.7 ms                                                | 11.3 ms: 1.05x slower                                         |
| pycparser                | 1.15 sec                                               | 1.21 sec: 1.06x slower                                        |
| typing_runtime_protocols | 146 us                                                 | 155 us: 1.06x slower                                          |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                         |
| tomli_loads              | 2.22 sec                                               | 2.35 sec: 1.06x slower                                        |
| pprint_pformat           | 1.50 sec                                               | 1.61 sec: 1.07x slower                                        |
| unpickle_pure_python     | 218 us                                                 | 234 us: 1.07x slower                                          |
| regex_v8                 | 22.3 ms                                                | 24.0 ms: 1.08x slower                                         |
| pyflate                  | 450 ms                                                 | 486 ms: 1.08x slower                                          |
| logging_silent           | 99.1 ns                                                | 107 ns: 1.08x slower                                          |
| meteor_contest           | 105 ms                                                 | 113 ms: 1.08x slower                                          |
| mdp                      | 2.57 sec                                               | 2.82 sec: 1.10x slower                                        |
| richards                 | 43.2 ms                                                | 47.9 ms: 1.11x slower                                         |
| go                       | 136 ms                                                 | 151 ms: 1.11x slower                                          |
| richards_super           | 49.0 ms                                                | 54.7 ms: 1.12x slower                                         |
| fannkuch                 | 387 ms                                                 | 460 ms: 1.19x slower                                          |
| telco                    | 6.87 ms                                                | 8.19 ms: 1.19x slower                                         |
| comprehensions           | 20.4 us                                                | 24.7 us: 1.21x slower                                         |
| hexiom                   | 6.12 ms                                                | 7.48 ms: 1.22x slower                                         |
| chaos                    | 63.5 ms                                                | 78.1 ms: 1.23x slower                                         |
| deepcopy_memo            | 37.4 us                                                | 46.7 us: 1.25x slower                                         |
| nqueens                  | 81.1 ms                                                | 103 ms: 1.27x slower                                          |
| unpack_sequence          | 44.8 ns                                                | 58.4 ns: 1.30x slower                                         |
| nbody                    | 88.8 ms                                                | 120 ms: 1.35x slower                                          |
| dask                     | 365 ms                                                 | 533 ms: 1.46x slower                                          |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                  |

Benchmark hidden because not significant (12): sqlite_synth, json_dumps, scimark_lu, async_tree_cpu_io_mixed, async_tree_memoization, pickle_pure_python, deltablue, pickle_dict, bench_mp_pool, docutils, logging_format, json
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.89% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
