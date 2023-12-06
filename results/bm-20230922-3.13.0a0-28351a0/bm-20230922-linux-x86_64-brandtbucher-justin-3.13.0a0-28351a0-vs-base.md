
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 28351a0
- commit date: 2023-09-22
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 2.59 sec                                                              | 2.69 sec: 1.04x slower                                        |
| tornado_http   | 95.3 ms                                                               | 97.0 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 189 ms: 1.01x slower                                          |
| nbody          | 88.0 ms                                                               | 90.1 ms: 1.02x slower                                         |
| float          | 78.5 ms                                                               | 83.0 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                               | 3.53 ms: 1.01x faster                                         |
| regex_dna      | 209 ms                                                                | 207 ms: 1.01x faster                                          |
| regex_v8       | 23.1 ms                                                               | 23.5 ms: 1.02x slower                                         |
| regex_compile  | 134 ms                                                                | 144 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| json_loads           | 25.4 us                                                               | 24.9 us: 1.02x faster                                         |
| unpickle_list        | 4.99 us                                                               | 4.91 us: 1.02x faster                                         |
| json_dumps           | 9.88 ms                                                               | 9.76 ms: 1.01x faster                                         |
| pickle               | 10.5 us                                                               | 10.4 us: 1.01x faster                                         |
| xml_etree_process    | 58.2 ms                                                               | 57.6 ms: 1.01x faster                                         |
| pickle_dict          | 31.9 us                                                               | 32.0 us: 1.00x slower                                         |
| tomli_loads          | 2.04 sec                                                              | 2.07 sec: 1.01x slower                                        |
| pickle_pure_python   | 296 us                                                                | 300 us: 1.01x slower                                          |
| xml_etree_iterparse  | 102 ms                                                                | 103 ms: 1.02x slower                                          |
| pickle_list          | 4.70 us                                                               | 4.82 us: 1.02x slower                                         |
| unpickle_pure_python | 214 us                                                                | 228 us: 1.07x slower                                          |
| Geometric mean       | (ref)                                                                 | 1.00x slower                                                  |

Benchmark hidden because not significant (3): unpickle, xml_etree_parse, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                         |
| python_startup_no_site | 6.82 ms                                                               | 6.89 ms: 1.01x slower                                         |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.6 ms                                                               | 11.1 ms: 1.04x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| scimark_fft              | 362 ms                                                                | 347 ms: 1.05x faster                                          |
| coroutines               | 22.3 ms                                                               | 21.7 ms: 1.03x faster                                         |
| json_loads               | 25.4 us                                                               | 24.9 us: 1.02x faster                                         |
| unpickle_list            | 4.99 us                                                               | 4.91 us: 1.02x faster                                         |
| json_dumps               | 9.88 ms                                                               | 9.76 ms: 1.01x faster                                         |
| regex_effbot             | 3.57 ms                                                               | 3.53 ms: 1.01x faster                                         |
| pickle                   | 10.5 us                                                               | 10.4 us: 1.01x faster                                         |
| regex_dna                | 209 ms                                                                | 207 ms: 1.01x faster                                          |
| xml_etree_process        | 58.2 ms                                                               | 57.6 ms: 1.01x faster                                         |
| pycparser                | 1.18 sec                                                              | 1.17 sec: 1.01x faster                                        |
| richards_super           | 54.1 ms                                                               | 53.6 ms: 1.01x faster                                         |
| pathlib                  | 18.6 ms                                                               | 18.5 ms: 1.00x faster                                         |
| coverage                 | 85.2 ms                                                               | 84.9 ms: 1.00x faster                                         |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.81 sec: 1.00x slower                                        |
| pickle_dict              | 31.9 us                                                               | 32.0 us: 1.00x slower                                         |
| generators               | 28.3 ms                                                               | 28.5 ms: 1.01x slower                                         |
| spectral_norm            | 107 ms                                                                | 108 ms: 1.01x slower                                          |
| sqlite_synth             | 2.75 us                                                               | 2.78 us: 1.01x slower                                         |
| async_tree_io            | 1.19 sec                                                              | 1.20 sec: 1.01x slower                                        |
| telco                    | 8.09 ms                                                               | 8.16 ms: 1.01x slower                                         |
| deepcopy_reduce          | 3.13 us                                                               | 3.16 us: 1.01x slower                                         |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                         |
| python_startup_no_site   | 6.82 ms                                                               | 6.89 ms: 1.01x slower                                         |
| create_gc_cycles         | 1.51 ms                                                               | 1.53 ms: 1.01x slower                                         |
| pidigits                 | 187 ms                                                                | 189 ms: 1.01x slower                                          |
| sqlglot_parse            | 1.27 ms                                                               | 1.29 ms: 1.01x slower                                         |
| tomli_loads              | 2.04 sec                                                              | 2.07 sec: 1.01x slower                                        |
| pickle_pure_python       | 296 us                                                                | 300 us: 1.01x slower                                          |
| xml_etree_iterparse      | 102 ms                                                                | 103 ms: 1.02x slower                                          |
| regex_v8                 | 23.1 ms                                                               | 23.5 ms: 1.02x slower                                         |
| tornado_http             | 95.3 ms                                                               | 97.0 ms: 1.02x slower                                         |
| pprint_safe_repr         | 723 ms                                                                | 738 ms: 1.02x slower                                          |
| deepcopy                 | 349 us                                                                | 356 us: 1.02x slower                                          |
| mdp                      | 2.53 sec                                                              | 2.58 sec: 1.02x slower                                        |
| sqlglot_transpile        | 1.58 ms                                                               | 1.61 ms: 1.02x slower                                         |
| pickle_list              | 4.70 us                                                               | 4.82 us: 1.02x slower                                         |
| nbody                    | 88.0 ms                                                               | 90.1 ms: 1.02x slower                                         |
| scimark_sor              | 120 ms                                                                | 123 ms: 1.02x slower                                          |
| sqlglot_normalize        | 105 ms                                                                | 107 ms: 1.03x slower                                          |
| asyncio_tcp              | 489 ms                                                                | 502 ms: 1.03x slower                                          |
| scimark_sparse_mat_mult  | 4.64 ms                                                               | 4.77 ms: 1.03x slower                                         |
| bench_thread_pool        | 813 us                                                                | 837 us: 1.03x slower                                          |
| pprint_pformat           | 1.47 sec                                                              | 1.52 sec: 1.03x slower                                        |
| sqlglot_optimize         | 52.3 ms                                                               | 53.9 ms: 1.03x slower                                         |
| meteor_contest           | 106 ms                                                                | 110 ms: 1.03x slower                                          |
| logging_silent           | 101 ns                                                                | 104 ns: 1.03x slower                                          |
| pyflate                  | 450 ms                                                                | 464 ms: 1.03x slower                                          |
| raytrace                 | 267 ms                                                                | 276 ms: 1.03x slower                                          |
| dulwich_log              | 66.2 ms                                                               | 68.4 ms: 1.03x slower                                         |
| deltablue                | 3.31 ms                                                               | 3.42 ms: 1.03x slower                                         |
| scimark_lu               | 110 ms                                                                | 114 ms: 1.04x slower                                          |
| async_generators         | 443 ms                                                                | 460 ms: 1.04x slower                                          |
| docutils                 | 2.59 sec                                                              | 2.69 sec: 1.04x slower                                        |
| scimark_monte_carlo      | 66.2 ms                                                               | 68.8 ms: 1.04x slower                                         |
| logging_simple           | 5.92 us                                                               | 6.16 us: 1.04x slower                                         |
| mypy2                    | 337 ms                                                                | 352 ms: 1.04x slower                                          |
| logging_format           | 6.53 us                                                               | 6.81 us: 1.04x slower                                         |
| mako                     | 10.6 ms                                                               | 11.1 ms: 1.04x slower                                         |
| crypto_pyaes             | 67.8 ms                                                               | 71.1 ms: 1.05x slower                                         |
| float                    | 78.5 ms                                                               | 83.0 ms: 1.06x slower                                         |
| go                       | 139 ms                                                                | 148 ms: 1.06x slower                                          |
| fannkuch                 | 382 ms                                                                | 405 ms: 1.06x slower                                          |
| typing_runtime_protocols | 139 us                                                                | 148 us: 1.06x slower                                          |
| unpickle_pure_python     | 214 us                                                                | 228 us: 1.07x slower                                          |
| regex_compile            | 134 ms                                                                | 144 ms: 1.07x slower                                          |
| deepcopy_memo            | 36.3 us                                                               | 39.2 us: 1.08x slower                                         |
| unpack_sequence          | 43.6 ns                                                               | 47.5 ns: 1.09x slower                                         |
| nqueens                  | 79.3 ms                                                               | 87.1 ms: 1.10x slower                                         |
| chaos                    | 59.8 ms                                                               | 65.8 ms: 1.10x slower                                         |
| gc_traversal             | 3.87 ms                                                               | 4.36 ms: 1.13x slower                                         |
| hexiom                   | 5.99 ms                                                               | 6.84 ms: 1.14x slower                                         |
| comprehensions           | 20.3 us                                                               | 23.3 us: 1.14x slower                                         |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                  |

Benchmark hidden because not significant (10): unpickle, richards, xml_etree_parse, xml_etree_generate, bench_mp_pool, dask, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_none, json


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
