
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 2.63 sec                                                              | 2.70 sec: 1.03x slower                                        |
| tornado_http   | 95.0 ms                                                               | 97.4 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.00x slower                                          |
| float          | 80.1 ms                                                               | 83.9 ms: 1.05x slower                                         |
| nbody          | 90.0 ms                                                               | 100 ms: 1.11x slower                                          |
| Geometric mean | (ref)                                                                 | 1.05x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.83 ms                                                               | 3.67 ms: 1.04x faster                                         |
| regex_dna      | 223 ms                                                                | 225 ms: 1.01x slower                                          |
| regex_v8       | 24.4 ms                                                               | 24.8 ms: 1.02x slower                                         |
| regex_compile  | 135 ms                                                                | 146 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle_list        | 5.11 us                                                               | 4.89 us: 1.04x faster                                         |
| unpickle             | 14.7 us                                                               | 14.3 us: 1.03x faster                                         |
| pickle_dict          | 31.3 us                                                               | 31.2 us: 1.01x faster                                         |
| xml_etree_process    | 56.8 ms                                                               | 57.4 ms: 1.01x slower                                         |
| pickle_pure_python   | 298 us                                                                | 301 us: 1.01x slower                                          |
| json_loads           | 25.1 us                                                               | 25.4 us: 1.01x slower                                         |
| xml_etree_generate   | 82.1 ms                                                               | 83.3 ms: 1.01x slower                                         |
| xml_etree_parse      | 152 ms                                                                | 154 ms: 1.01x slower                                          |
| json_dumps           | 9.74 ms                                                               | 9.94 ms: 1.02x slower                                         |
| xml_etree_iterparse  | 102 ms                                                                | 105 ms: 1.02x slower                                          |
| pickle               | 10.6 us                                                               | 10.9 us: 1.03x slower                                         |
| unpickle_pure_python | 213 us                                                                | 231 us: 1.08x slower                                          |
| tomli_loads          | 2.03 sec                                                              | 2.29 sec: 1.13x slower                                        |
| Geometric mean       | (ref)                                                                 | 1.02x slower                                                  |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 6.97 ms                                                               | 6.99 ms: 1.00x slower                                         |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                  |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 11.0 ms                                                               | 11.3 ms: 1.03x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpack_sequence          | 53.3 ns                                                               | 45.8 ns: 1.16x faster                                         |
| regex_effbot             | 3.83 ms                                                               | 3.67 ms: 1.04x faster                                         |
| unpickle_list            | 5.11 us                                                               | 4.89 us: 1.04x faster                                         |
| unpickle                 | 14.7 us                                                               | 14.3 us: 1.03x faster                                         |
| json                     | 4.93 ms                                                               | 4.84 ms: 1.02x faster                                         |
| logging_simple           | 5.98 us                                                               | 5.93 us: 1.01x faster                                         |
| pickle_dict              | 31.3 us                                                               | 31.2 us: 1.01x faster                                         |
| python_startup_no_site   | 6.97 ms                                                               | 6.99 ms: 1.00x slower                                         |
| pidigits                 | 187 ms                                                                | 188 ms: 1.00x slower                                          |
| regex_dna                | 223 ms                                                                | 225 ms: 1.01x slower                                          |
| create_gc_cycles         | 1.50 ms                                                               | 1.52 ms: 1.01x slower                                         |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.81 sec: 1.01x slower                                        |
| gc_traversal             | 3.83 ms                                                               | 3.86 ms: 1.01x slower                                         |
| xml_etree_process        | 56.8 ms                                                               | 57.4 ms: 1.01x slower                                         |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.01x slower                                        |
| pickle_pure_python       | 298 us                                                                | 301 us: 1.01x slower                                          |
| json_loads               | 25.1 us                                                               | 25.4 us: 1.01x slower                                         |
| async_tree_cpu_io_mixed  | 705 ms                                                                | 714 ms: 1.01x slower                                          |
| asyncio_tcp              | 486 ms                                                                | 493 ms: 1.01x slower                                          |
| pprint_safe_repr         | 742 ms                                                                | 752 ms: 1.01x slower                                          |
| xml_etree_generate       | 82.1 ms                                                               | 83.3 ms: 1.01x slower                                         |
| xml_etree_parse          | 152 ms                                                                | 154 ms: 1.01x slower                                          |
| mdp                      | 2.72 sec                                                              | 2.76 sec: 1.02x slower                                        |
| sqlite_synth             | 2.72 us                                                               | 2.76 us: 1.02x slower                                         |
| regex_v8                 | 24.4 ms                                                               | 24.8 ms: 1.02x slower                                         |
| deepcopy_reduce          | 3.07 us                                                               | 3.12 us: 1.02x slower                                         |
| async_tree_memoization   | 567 ms                                                                | 576 ms: 1.02x slower                                          |
| richards_super           | 54.6 ms                                                               | 55.6 ms: 1.02x slower                                         |
| pycparser                | 1.21 sec                                                              | 1.23 sec: 1.02x slower                                        |
| json_dumps               | 9.74 ms                                                               | 9.94 ms: 1.02x slower                                         |
| async_tree_none          | 438 ms                                                                | 447 ms: 1.02x slower                                          |
| telco                    | 8.03 ms                                                               | 8.20 ms: 1.02x slower                                         |
| xml_etree_iterparse      | 102 ms                                                                | 105 ms: 1.02x slower                                          |
| pprint_pformat           | 1.50 sec                                                              | 1.54 sec: 1.02x slower                                        |
| tornado_http             | 95.0 ms                                                               | 97.4 ms: 1.02x slower                                         |
| pickle                   | 10.6 us                                                               | 10.9 us: 1.03x slower                                         |
| dask                     | 520 ms                                                                | 534 ms: 1.03x slower                                          |
| scimark_lu               | 111 ms                                                                | 114 ms: 1.03x slower                                          |
| sqlglot_parse            | 1.27 ms                                                               | 1.31 ms: 1.03x slower                                         |
| docutils                 | 2.63 sec                                                              | 2.70 sec: 1.03x slower                                        |
| mako                     | 11.0 ms                                                               | 11.3 ms: 1.03x slower                                         |
| dulwich_log              | 66.6 ms                                                               | 68.6 ms: 1.03x slower                                         |
| sqlglot_transpile        | 1.58 ms                                                               | 1.63 ms: 1.03x slower                                         |
| deepcopy                 | 343 us                                                                | 354 us: 1.03x slower                                          |
| pathlib                  | 18.3 ms                                                               | 18.9 ms: 1.03x slower                                         |
| bench_thread_pool        | 814 us                                                                | 841 us: 1.03x slower                                          |
| sqlglot_optimize         | 52.6 ms                                                               | 54.4 ms: 1.03x slower                                         |
| generators               | 28.9 ms                                                               | 30.0 ms: 1.04x slower                                         |
| logging_silent           | 103 ns                                                                | 107 ns: 1.04x slower                                          |
| scimark_monte_carlo      | 65.5 ms                                                               | 68.1 ms: 1.04x slower                                         |
| crypto_pyaes             | 69.4 ms                                                               | 72.2 ms: 1.04x slower                                         |
| sqlglot_normalize        | 104 ms                                                                | 108 ms: 1.04x slower                                          |
| richards                 | 47.6 ms                                                               | 49.6 ms: 1.04x slower                                         |
| scimark_sor              | 118 ms                                                                | 123 ms: 1.04x slower                                          |
| typing_runtime_protocols | 146 us                                                                | 152 us: 1.05x slower                                          |
| mypy2                    | 338 ms                                                                | 354 ms: 1.05x slower                                          |
| float                    | 80.1 ms                                                               | 83.9 ms: 1.05x slower                                         |
| scimark_sparse_mat_mult  | 4.66 ms                                                               | 4.88 ms: 1.05x slower                                         |
| async_generators         | 447 ms                                                                | 469 ms: 1.05x slower                                          |
| raytrace                 | 271 ms                                                                | 285 ms: 1.05x slower                                          |
| deltablue                | 3.30 ms                                                               | 3.48 ms: 1.05x slower                                         |
| spectral_norm            | 106 ms                                                                | 112 ms: 1.05x slower                                          |
| go                       | 141 ms                                                                | 150 ms: 1.06x slower                                          |
| meteor_contest           | 105 ms                                                                | 113 ms: 1.07x slower                                          |
| pyflate                  | 450 ms                                                                | 481 ms: 1.07x slower                                          |
| scimark_fft              | 350 ms                                                                | 377 ms: 1.08x slower                                          |
| regex_compile            | 135 ms                                                                | 146 ms: 1.08x slower                                          |
| unpickle_pure_python     | 213 us                                                                | 231 us: 1.08x slower                                          |
| deepcopy_memo            | 36.5 us                                                               | 40.0 us: 1.10x slower                                         |
| nbody                    | 90.0 ms                                                               | 100 ms: 1.11x slower                                          |
| chaos                    | 59.2 ms                                                               | 66.0 ms: 1.12x slower                                         |
| fannkuch                 | 382 ms                                                                | 429 ms: 1.12x slower                                          |
| tomli_loads              | 2.03 sec                                                              | 2.29 sec: 1.13x slower                                        |
| comprehensions           | 20.9 us                                                               | 24.1 us: 1.15x slower                                         |
| nqueens                  | 80.0 ms                                                               | 94.2 ms: 1.18x slower                                         |
| hexiom                   | 6.05 ms                                                               | 7.15 ms: 1.18x slower                                         |
| Geometric mean           | (ref)                                                                 | 1.03x slower                                                  |

Benchmark hidden because not significant (6): coroutines, logging_format, coverage, python_startup, bench_mp_pool, pickle_list


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
