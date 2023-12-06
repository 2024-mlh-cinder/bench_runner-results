
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 56976b3
- commit date: 2023-09-15
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 2.60 sec                                                              | 2.70 sec: 1.04x slower                                        |
| tornado_http   | 95.0 ms                                                               | 97.6 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 189 ms: 1.01x slower                                          |
| float          | 78.7 ms                                                               | 83.4 ms: 1.06x slower                                         |
| nbody          | 87.9 ms                                                               | 118 ms: 1.34x slower                                          |
| Geometric mean | (ref)                                                                 | 1.13x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.63 ms                                                               | 3.51 ms: 1.04x faster                                         |
| regex_dna      | 209 ms                                                                | 208 ms: 1.01x faster                                          |
| regex_v8       | 23.0 ms                                                               | 24.2 ms: 1.05x slower                                         |
| regex_compile  | 134 ms                                                                | 150 ms: 1.12x slower                                          |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle             | 14.9 us                                                               | 14.0 us: 1.07x faster                                         |
| unpickle_list        | 4.90 us                                                               | 4.73 us: 1.04x faster                                         |
| pickle_dict          | 32.4 us                                                               | 31.7 us: 1.02x faster                                         |
| xml_etree_parse      | 154 ms                                                                | 152 ms: 1.01x faster                                          |
| pickle               | 10.8 us                                                               | 10.7 us: 1.01x faster                                         |
| json_loads           | 25.4 us                                                               | 25.3 us: 1.00x faster                                         |
| xml_etree_generate   | 83.9 ms                                                               | 84.4 ms: 1.01x slower                                         |
| xml_etree_iterparse  | 102 ms                                                                | 103 ms: 1.01x slower                                          |
| pickle_list          | 4.67 us                                                               | 4.70 us: 1.01x slower                                         |
| json_dumps           | 9.81 ms                                                               | 9.97 ms: 1.02x slower                                         |
| pickle_pure_python   | 297 us                                                                | 309 us: 1.04x slower                                          |
| unpickle_pure_python | 211 us                                                                | 233 us: 1.10x slower                                          |
| tomli_loads          | 2.04 sec                                                              | 2.34 sec: 1.15x slower                                        |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                  |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 6.86 ms                                                               | 6.87 ms: 1.00x slower                                         |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                  |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.5 ms                                                               | 11.3 ms: 1.07x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| gc_traversal             | 4.11 ms                                                               | 3.57 ms: 1.15x faster                                         |
| unpickle                 | 14.9 us                                                               | 14.0 us: 1.07x faster                                         |
| scimark_sor              | 130 ms                                                                | 125 ms: 1.04x faster                                          |
| regex_effbot             | 3.63 ms                                                               | 3.51 ms: 1.04x faster                                         |
| unpickle_list            | 4.90 us                                                               | 4.73 us: 1.04x faster                                         |
| pickle_dict              | 32.4 us                                                               | 31.7 us: 1.02x faster                                         |
| xml_etree_parse          | 154 ms                                                                | 152 ms: 1.01x faster                                          |
| sqlite_synth             | 2.76 us                                                               | 2.74 us: 1.01x faster                                         |
| regex_dna                | 209 ms                                                                | 208 ms: 1.01x faster                                          |
| scimark_monte_carlo      | 67.9 ms                                                               | 67.4 ms: 1.01x faster                                         |
| pickle                   | 10.8 us                                                               | 10.7 us: 1.01x faster                                         |
| json_loads               | 25.4 us                                                               | 25.3 us: 1.00x faster                                         |
| create_gc_cycles         | 1.52 ms                                                               | 1.52 ms: 1.00x faster                                         |
| python_startup_no_site   | 6.86 ms                                                               | 6.87 ms: 1.00x slower                                         |
| generators               | 28.3 ms                                                               | 28.4 ms: 1.00x slower                                         |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.80 sec: 1.00x slower                                        |
| xml_etree_generate       | 83.9 ms                                                               | 84.4 ms: 1.01x slower                                         |
| xml_etree_iterparse      | 102 ms                                                                | 103 ms: 1.01x slower                                          |
| pickle_list              | 4.67 us                                                               | 4.70 us: 1.01x slower                                         |
| pidigits                 | 187 ms                                                                | 189 ms: 1.01x slower                                          |
| pycparser                | 1.18 sec                                                              | 1.20 sec: 1.01x slower                                        |
| async_tree_cpu_io_mixed  | 708 ms                                                                | 718 ms: 1.02x slower                                          |
| dask                     | 529 ms                                                                | 538 ms: 1.02x slower                                          |
| json_dumps               | 9.81 ms                                                               | 9.97 ms: 1.02x slower                                         |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.02x slower                                        |
| sqlglot_parse            | 1.27 ms                                                               | 1.30 ms: 1.02x slower                                         |
| sqlglot_transpile        | 1.58 ms                                                               | 1.62 ms: 1.02x slower                                         |
| asyncio_tcp              | 480 ms                                                                | 491 ms: 1.02x slower                                          |
| async_tree_none          | 438 ms                                                                | 449 ms: 1.02x slower                                          |
| richards                 | 48.1 ms                                                               | 49.3 ms: 1.02x slower                                         |
| tornado_http             | 95.0 ms                                                               | 97.6 ms: 1.03x slower                                         |
| async_tree_memoization   | 563 ms                                                                | 579 ms: 1.03x slower                                          |
| sqlglot_optimize         | 52.5 ms                                                               | 54.0 ms: 1.03x slower                                         |
| logging_simple           | 6.05 us                                                               | 6.22 us: 1.03x slower                                         |
| spectral_norm            | 106 ms                                                                | 110 ms: 1.03x slower                                          |
| coroutines               | 21.8 ms                                                               | 22.6 ms: 1.04x slower                                         |
| sqlglot_normalize        | 104 ms                                                                | 108 ms: 1.04x slower                                          |
| pathlib                  | 18.3 ms                                                               | 19.0 ms: 1.04x slower                                         |
| pickle_pure_python       | 297 us                                                                | 309 us: 1.04x slower                                          |
| docutils                 | 2.60 sec                                                              | 2.70 sec: 1.04x slower                                        |
| richards_super           | 53.8 ms                                                               | 55.9 ms: 1.04x slower                                         |
| dulwich_log              | 66.8 ms                                                               | 69.5 ms: 1.04x slower                                         |
| async_generators         | 447 ms                                                                | 468 ms: 1.05x slower                                          |
| regex_v8                 | 23.0 ms                                                               | 24.2 ms: 1.05x slower                                         |
| bench_thread_pool        | 809 us                                                                | 854 us: 1.06x slower                                          |
| deepcopy_reduce          | 3.12 us                                                               | 3.30 us: 1.06x slower                                         |
| raytrace                 | 268 ms                                                                | 284 ms: 1.06x slower                                          |
| mypy2                    | 336 ms                                                                | 356 ms: 1.06x slower                                          |
| float                    | 78.7 ms                                                               | 83.4 ms: 1.06x slower                                         |
| scimark_lu               | 110 ms                                                                | 117 ms: 1.06x slower                                          |
| logging_silent           | 100 ns                                                                | 107 ns: 1.07x slower                                          |
| meteor_contest           | 105 ms                                                                | 113 ms: 1.07x slower                                          |
| mako                     | 10.5 ms                                                               | 11.3 ms: 1.07x slower                                         |
| deltablue                | 3.28 ms                                                               | 3.53 ms: 1.07x slower                                         |
| mdp                      | 2.63 sec                                                              | 2.83 sec: 1.08x slower                                        |
| scimark_fft              | 352 ms                                                                | 381 ms: 1.08x slower                                          |
| crypto_pyaes             | 69.2 ms                                                               | 75.6 ms: 1.09x slower                                         |
| pprint_safe_repr         | 727 ms                                                                | 797 ms: 1.10x slower                                          |
| go                       | 140 ms                                                                | 154 ms: 1.10x slower                                          |
| scimark_sparse_mat_mult  | 4.56 ms                                                               | 5.02 ms: 1.10x slower                                         |
| pyflate                  | 454 ms                                                                | 500 ms: 1.10x slower                                          |
| unpickle_pure_python     | 211 us                                                                | 233 us: 1.10x slower                                          |
| deepcopy                 | 344 us                                                                | 382 us: 1.11x slower                                          |
| pprint_pformat           | 1.47 sec                                                              | 1.64 sec: 1.11x slower                                        |
| regex_compile            | 134 ms                                                                | 150 ms: 1.12x slower                                          |
| typing_runtime_protocols | 142 us                                                                | 159 us: 1.12x slower                                          |
| unpack_sequence          | 48.2 ns                                                               | 54.7 ns: 1.14x slower                                         |
| tomli_loads              | 2.04 sec                                                              | 2.34 sec: 1.15x slower                                        |
| fannkuch                 | 389 ms                                                                | 455 ms: 1.17x slower                                          |
| comprehensions           | 20.4 us                                                               | 24.3 us: 1.19x slower                                         |
| deepcopy_memo            | 36.1 us                                                               | 45.1 us: 1.25x slower                                         |
| hexiom                   | 5.86 ms                                                               | 7.53 ms: 1.28x slower                                         |
| nqueens                  | 78.8 ms                                                               | 104 ms: 1.32x slower                                          |
| nbody                    | 87.9 ms                                                               | 118 ms: 1.34x slower                                          |
| chaos                    | 59.3 ms                                                               | 80.0 ms: 1.35x slower                                         |
| Geometric mean           | (ref)                                                                 | 1.05x slower                                                  |

Benchmark hidden because not significant (7): coverage, python_startup, bench_mp_pool, telco, xml_etree_process, json, logging_format


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
