
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: d70e866
- commit date: 2023-09-25
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.59 sec                                                              | 2.66 sec: 1.02x slower                                                  |
| tornado_http   | 95.3 ms                                                               | 96.9 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 187 ms: 1.00x slower                                                    |
| float          | 78.5 ms                                                               | 82.3 ms: 1.05x slower                                                   |
| nbody          | 88.0 ms                                                               | 95.9 ms: 1.09x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.05x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                                | 201 ms: 1.04x faster                                                    |
| regex_effbot   | 3.57 ms                                                               | 3.45 ms: 1.04x faster                                                   |
| regex_compile  | 134 ms                                                                | 144 ms: 1.07x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                            |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle               | 10.5 us                                                               | 10.2 us: 1.03x faster                                                   |
| unpickle_list        | 4.99 us                                                               | 4.88 us: 1.02x faster                                                   |
| pickle_dict          | 31.9 us                                                               | 31.2 us: 1.02x faster                                                   |
| xml_etree_process    | 58.2 ms                                                               | 57.3 ms: 1.01x faster                                                   |
| json_loads           | 25.4 us                                                               | 25.1 us: 1.01x faster                                                   |
| xml_etree_generate   | 84.2 ms                                                               | 83.3 ms: 1.01x faster                                                   |
| tomli_loads          | 2.04 sec                                                              | 2.02 sec: 1.01x faster                                                  |
| pickle_pure_python   | 296 us                                                                | 297 us: 1.01x slower                                                    |
| xml_etree_iterparse  | 102 ms                                                                | 103 ms: 1.01x slower                                                    |
| unpickle             | 14.7 us                                                               | 15.0 us: 1.02x slower                                                   |
| unpickle_pure_python | 214 us                                                                | 227 us: 1.06x slower                                                    |
| Geometric mean       | (ref)                                                                 | 1.00x faster                                                            |

Benchmark hidden because not significant (3): pickle_list, xml_etree_parse, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                   |
| python_startup_no_site | 6.82 ms                                                               | 6.90 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.6 ms                                                               | 11.5 ms: 1.08x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| scimark_fft              | 362 ms                                                                | 334 ms: 1.08x faster                                                    |
| regex_dna                | 209 ms                                                                | 201 ms: 1.04x faster                                                    |
| regex_effbot             | 3.57 ms                                                               | 3.45 ms: 1.04x faster                                                   |
| pickle                   | 10.5 us                                                               | 10.2 us: 1.03x faster                                                   |
| unpickle_list            | 4.99 us                                                               | 4.88 us: 1.02x faster                                                   |
| pickle_dict              | 31.9 us                                                               | 31.2 us: 1.02x faster                                                   |
| xml_etree_process        | 58.2 ms                                                               | 57.3 ms: 1.01x faster                                                   |
| json_loads               | 25.4 us                                                               | 25.1 us: 1.01x faster                                                   |
| xml_etree_generate       | 84.2 ms                                                               | 83.3 ms: 1.01x faster                                                   |
| sqlite_synth             | 2.75 us                                                               | 2.73 us: 1.01x faster                                                   |
| tomli_loads              | 2.04 sec                                                              | 2.02 sec: 1.01x faster                                                  |
| coroutines               | 22.3 ms                                                               | 22.2 ms: 1.00x faster                                                   |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.81 sec: 1.00x slower                                                  |
| pidigits                 | 187 ms                                                                | 187 ms: 1.00x slower                                                    |
| pickle_pure_python       | 296 us                                                                | 297 us: 1.01x slower                                                    |
| pyflate                  | 450 ms                                                                | 453 ms: 1.01x slower                                                    |
| xml_etree_iterparse      | 102 ms                                                                | 103 ms: 1.01x slower                                                    |
| dask                     | 529 ms                                                                | 534 ms: 1.01x slower                                                    |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                   |
| scimark_monte_carlo      | 66.2 ms                                                               | 67.0 ms: 1.01x slower                                                   |
| python_startup_no_site   | 6.82 ms                                                               | 6.90 ms: 1.01x slower                                                   |
| coverage                 | 85.2 ms                                                               | 86.3 ms: 1.01x slower                                                   |
| sqlglot_normalize        | 105 ms                                                                | 106 ms: 1.01x slower                                                    |
| deepcopy_reduce          | 3.13 us                                                               | 3.17 us: 1.01x slower                                                   |
| json                     | 4.85 ms                                                               | 4.91 ms: 1.01x slower                                                   |
| pycparser                | 1.18 sec                                                              | 1.20 sec: 1.01x slower                                                  |
| scimark_sor              | 120 ms                                                                | 122 ms: 1.01x slower                                                    |
| pathlib                  | 18.6 ms                                                               | 18.8 ms: 1.01x slower                                                   |
| tornado_http             | 95.3 ms                                                               | 96.9 ms: 1.02x slower                                                   |
| mdp                      | 2.53 sec                                                              | 2.57 sec: 1.02x slower                                                  |
| async_tree_cpu_io_mixed  | 702 ms                                                                | 715 ms: 1.02x slower                                                    |
| deepcopy                 | 349 us                                                                | 355 us: 1.02x slower                                                    |
| asyncio_tcp              | 489 ms                                                                | 498 ms: 1.02x slower                                                    |
| meteor_contest           | 106 ms                                                                | 108 ms: 1.02x slower                                                    |
| raytrace                 | 267 ms                                                                | 272 ms: 1.02x slower                                                    |
| sqlglot_optimize         | 52.3 ms                                                               | 53.4 ms: 1.02x slower                                                   |
| async_tree_none          | 438 ms                                                                | 448 ms: 1.02x slower                                                    |
| unpickle                 | 14.7 us                                                               | 15.0 us: 1.02x slower                                                   |
| pprint_safe_repr         | 723 ms                                                                | 740 ms: 1.02x slower                                                    |
| docutils                 | 2.59 sec                                                              | 2.66 sec: 1.02x slower                                                  |
| sqlglot_parse            | 1.27 ms                                                               | 1.30 ms: 1.03x slower                                                   |
| pprint_pformat           | 1.47 sec                                                              | 1.51 sec: 1.03x slower                                                  |
| logging_simple           | 5.92 us                                                               | 6.08 us: 1.03x slower                                                   |
| deltablue                | 3.31 ms                                                               | 3.41 ms: 1.03x slower                                                   |
| sqlglot_transpile        | 1.58 ms                                                               | 1.63 ms: 1.03x slower                                                   |
| logging_format           | 6.53 us                                                               | 6.73 us: 1.03x slower                                                   |
| logging_silent           | 101 ns                                                                | 104 ns: 1.03x slower                                                    |
| bench_thread_pool        | 813 us                                                                | 838 us: 1.03x slower                                                    |
| scimark_lu               | 110 ms                                                                | 114 ms: 1.03x slower                                                    |
| scimark_sparse_mat_mult  | 4.64 ms                                                               | 4.79 ms: 1.03x slower                                                   |
| dulwich_log              | 66.2 ms                                                               | 68.6 ms: 1.04x slower                                                   |
| fannkuch                 | 382 ms                                                                | 396 ms: 1.04x slower                                                    |
| async_generators         | 443 ms                                                                | 460 ms: 1.04x slower                                                    |
| mypy2                    | 337 ms                                                                | 352 ms: 1.04x slower                                                    |
| float                    | 78.5 ms                                                               | 82.3 ms: 1.05x slower                                                   |
| crypto_pyaes             | 67.8 ms                                                               | 71.5 ms: 1.05x slower                                                   |
| go                       | 139 ms                                                                | 147 ms: 1.06x slower                                                    |
| gc_traversal             | 3.87 ms                                                               | 4.11 ms: 1.06x slower                                                   |
| unpickle_pure_python     | 214 us                                                                | 227 us: 1.06x slower                                                    |
| regex_compile            | 134 ms                                                                | 144 ms: 1.07x slower                                                    |
| mako                     | 10.6 ms                                                               | 11.5 ms: 1.08x slower                                                   |
| unpack_sequence          | 43.6 ns                                                               | 47.2 ns: 1.08x slower                                                   |
| typing_runtime_protocols | 139 us                                                                | 151 us: 1.09x slower                                                    |
| deepcopy_memo            | 36.3 us                                                               | 39.5 us: 1.09x slower                                                   |
| nbody                    | 88.0 ms                                                               | 95.9 ms: 1.09x slower                                                   |
| chaos                    | 59.8 ms                                                               | 65.3 ms: 1.09x slower                                                   |
| nqueens                  | 79.3 ms                                                               | 89.6 ms: 1.13x slower                                                   |
| hexiom                   | 5.99 ms                                                               | 6.95 ms: 1.16x slower                                                   |
| comprehensions           | 20.3 us                                                               | 23.8 us: 1.17x slower                                                   |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                            |

Benchmark hidden because not significant (13): pickle_list, generators, xml_etree_parse, create_gc_cycles, telco, regex_v8, bench_mp_pool, spectral_norm, async_tree_io, json_dumps, richards, richards_super, async_tree_memoization


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
