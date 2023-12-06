
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 2.60 sec                                                              | 2.71 sec: 1.04x slower                                        |
| tornado_http   | 95.2 ms                                                               | 97.4 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 212 ms                                                                | 189 ms: 1.12x faster                                          |
| float          | 79.5 ms                                                               | 83.2 ms: 1.05x slower                                         |
| nbody          | 88.1 ms                                                               | 120 ms: 1.36x slower                                          |
| Geometric mean | (ref)                                                                 | 1.08x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 23.6 ms                                                               | 24.0 ms: 1.02x slower                                         |
| regex_dna      | 205 ms                                                                | 210 ms: 1.02x slower                                          |
| regex_effbot   | 3.42 ms                                                               | 3.62 ms: 1.06x slower                                         |
| regex_compile  | 134 ms                                                                | 148 ms: 1.11x slower                                          |
| Geometric mean | (ref)                                                                 | 1.05x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle             | 15.0 us                                                               | 14.2 us: 1.05x faster                                         |
| pickle_dict          | 32.7 us                                                               | 31.6 us: 1.03x faster                                         |
| pickle               | 10.9 us                                                               | 10.5 us: 1.03x faster                                         |
| unpickle_list        | 4.90 us                                                               | 4.83 us: 1.02x faster                                         |
| xml_etree_parse      | 154 ms                                                                | 152 ms: 1.01x faster                                          |
| xml_etree_generate   | 83.8 ms                                                               | 83.4 ms: 1.01x faster                                         |
| json_dumps           | 9.85 ms                                                               | 9.81 ms: 1.00x faster                                         |
| xml_etree_iterparse  | 101 ms                                                                | 102 ms: 1.01x slower                                          |
| xml_etree_process    | 57.7 ms                                                               | 58.1 ms: 1.01x slower                                         |
| pickle_list          | 4.74 us                                                               | 4.81 us: 1.02x slower                                         |
| pickle_pure_python   | 297 us                                                                | 309 us: 1.04x slower                                          |
| unpickle_pure_python | 212 us                                                                | 234 us: 1.11x slower                                          |
| tomli_loads          | 1.99 sec                                                              | 2.35 sec: 1.18x slower                                        |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                  |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                         |
| python_startup_no_site | 6.87 ms                                                               | 6.84 ms: 1.00x faster                                         |
| Geometric mean         | (ref)                                                                 | 1.00x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.6 ms                                                               | 11.3 ms: 1.06x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-linux-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits                 | 212 ms                                                                | 189 ms: 1.12x faster                                          |
| scimark_sor              | 130 ms                                                                | 122 ms: 1.07x faster                                          |
| unpickle                 | 15.0 us                                                               | 14.2 us: 1.05x faster                                         |
| gc_traversal             | 3.86 ms                                                               | 3.69 ms: 1.04x faster                                         |
| pickle_dict              | 32.7 us                                                               | 31.6 us: 1.03x faster                                         |
| pickle                   | 10.9 us                                                               | 10.5 us: 1.03x faster                                         |
| create_gc_cycles         | 1.54 ms                                                               | 1.50 ms: 1.02x faster                                         |
| coverage                 | 86.7 ms                                                               | 85.3 ms: 1.02x faster                                         |
| unpickle_list            | 4.90 us                                                               | 4.83 us: 1.02x faster                                         |
| xml_etree_parse          | 154 ms                                                                | 152 ms: 1.01x faster                                          |
| xml_etree_generate       | 83.8 ms                                                               | 83.4 ms: 1.01x faster                                         |
| coroutines               | 21.9 ms                                                               | 21.8 ms: 1.00x faster                                         |
| json_dumps               | 9.85 ms                                                               | 9.81 ms: 1.00x faster                                         |
| python_startup           | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                         |
| python_startup_no_site   | 6.87 ms                                                               | 6.84 ms: 1.00x faster                                         |
| generators               | 28.0 ms                                                               | 28.1 ms: 1.00x slower                                         |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.81 sec: 1.01x slower                                        |
| xml_etree_iterparse      | 101 ms                                                                | 102 ms: 1.01x slower                                          |
| async_tree_io            | 1.20 sec                                                              | 1.20 sec: 1.01x slower                                        |
| dask                     | 529 ms                                                                | 533 ms: 1.01x slower                                          |
| xml_etree_process        | 57.7 ms                                                               | 58.1 ms: 1.01x slower                                         |
| sqlglot_parse            | 1.28 ms                                                               | 1.29 ms: 1.01x slower                                         |
| json                     | 4.77 ms                                                               | 4.82 ms: 1.01x slower                                         |
| sqlglot_transpile        | 1.58 ms                                                               | 1.60 ms: 1.01x slower                                         |
| asyncio_tcp              | 488 ms                                                                | 496 ms: 1.02x slower                                          |
| pickle_list              | 4.74 us                                                               | 4.81 us: 1.02x slower                                         |
| regex_v8                 | 23.6 ms                                                               | 24.0 ms: 1.02x slower                                         |
| sqlglot_normalize        | 104 ms                                                                | 106 ms: 1.02x slower                                          |
| telco                    | 8.03 ms                                                               | 8.19 ms: 1.02x slower                                         |
| regex_dna                | 205 ms                                                                | 210 ms: 1.02x slower                                          |
| tornado_http             | 95.2 ms                                                               | 97.4 ms: 1.02x slower                                         |
| richards_super           | 53.5 ms                                                               | 54.7 ms: 1.02x slower                                         |
| deepcopy_reduce          | 3.13 us                                                               | 3.21 us: 1.03x slower                                         |
| scimark_lu               | 111 ms                                                                | 114 ms: 1.03x slower                                          |
| sqlglot_optimize         | 52.2 ms                                                               | 53.6 ms: 1.03x slower                                         |
| scimark_monte_carlo      | 66.4 ms                                                               | 68.3 ms: 1.03x slower                                         |
| pickle_pure_python       | 297 us                                                                | 309 us: 1.04x slower                                          |
| raytrace                 | 268 ms                                                                | 279 ms: 1.04x slower                                          |
| async_generators         | 444 ms                                                                | 463 ms: 1.04x slower                                          |
| docutils                 | 2.60 sec                                                              | 2.71 sec: 1.04x slower                                        |
| scimark_fft              | 361 ms                                                                | 378 ms: 1.05x slower                                          |
| spectral_norm            | 104 ms                                                                | 109 ms: 1.05x slower                                          |
| pathlib                  | 18.4 ms                                                               | 19.2 ms: 1.05x slower                                         |
| float                    | 79.5 ms                                                               | 83.2 ms: 1.05x slower                                         |
| dulwich_log              | 66.2 ms                                                               | 69.5 ms: 1.05x slower                                         |
| mypy2                    | 337 ms                                                                | 354 ms: 1.05x slower                                          |
| pycparser                | 1.15 sec                                                              | 1.21 sec: 1.05x slower                                        |
| regex_effbot             | 3.42 ms                                                               | 3.62 ms: 1.06x slower                                         |
| deltablue                | 3.32 ms                                                               | 3.52 ms: 1.06x slower                                         |
| mako                     | 10.6 ms                                                               | 11.3 ms: 1.06x slower                                         |
| pyflate                  | 456 ms                                                                | 486 ms: 1.07x slower                                          |
| scimark_sparse_mat_mult  | 4.62 ms                                                               | 4.93 ms: 1.07x slower                                         |
| meteor_contest           | 106 ms                                                                | 113 ms: 1.07x slower                                          |
| deepcopy                 | 348 us                                                                | 374 us: 1.07x slower                                          |
| go                       | 141 ms                                                                | 151 ms: 1.07x slower                                          |
| logging_simple           | 5.83 us                                                               | 6.28 us: 1.08x slower                                         |
| typing_runtime_protocols | 144 us                                                                | 155 us: 1.08x slower                                          |
| logging_format           | 6.42 us                                                               | 6.92 us: 1.08x slower                                         |
| bench_thread_pool        | 807 us                                                                | 871 us: 1.08x slower                                          |
| pprint_safe_repr         | 715 ms                                                                | 773 ms: 1.08x slower                                          |
| logging_silent           | 98.7 ns                                                               | 107 ns: 1.09x slower                                          |
| crypto_pyaes             | 68.5 ms                                                               | 75.5 ms: 1.10x slower                                         |
| unpickle_pure_python     | 212 us                                                                | 234 us: 1.11x slower                                          |
| regex_compile            | 134 ms                                                                | 148 ms: 1.11x slower                                          |
| pprint_pformat           | 1.45 sec                                                              | 1.61 sec: 1.11x slower                                        |
| mdp                      | 2.53 sec                                                              | 2.82 sec: 1.12x slower                                        |
| tomli_loads              | 1.99 sec                                                              | 2.35 sec: 1.18x slower                                        |
| fannkuch                 | 383 ms                                                                | 460 ms: 1.20x slower                                          |
| comprehensions           | 20.2 us                                                               | 24.7 us: 1.22x slower                                         |
| hexiom                   | 5.91 ms                                                               | 7.48 ms: 1.26x slower                                         |
| chaos                    | 59.9 ms                                                               | 78.1 ms: 1.30x slower                                         |
| deepcopy_memo            | 35.6 us                                                               | 46.7 us: 1.31x slower                                         |
| nqueens                  | 78.3 ms                                                               | 103 ms: 1.32x slower                                          |
| nbody                    | 88.1 ms                                                               | 120 ms: 1.36x slower                                          |
| unpack_sequence          | 41.1 ns                                                               | 58.4 ns: 1.42x slower                                         |
| Geometric mean           | (ref)                                                                 | 1.05x slower                                                  |

Benchmark hidden because not significant (7): sqlite_synth, json_loads, bench_mp_pool, richards, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
