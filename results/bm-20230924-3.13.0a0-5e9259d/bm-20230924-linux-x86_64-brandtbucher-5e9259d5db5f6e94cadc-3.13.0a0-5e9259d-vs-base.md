
# Results vs. base

- fork: brandtbucher
- ref: 5e9259d5db5f6e94cadc
- machine: linux-x86_64
- commit hash: 5e9259d
- commit date: 2023-09-24
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.59 sec                                                              | 2.67 sec: 1.03x slower                                                      |
| tornado_http   | 95.3 ms                                                               | 95.9 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 187 ms: 1.00x slower                                                        |
| float          | 78.5 ms                                                               | 81.0 ms: 1.03x slower                                                       |
| nbody          | 88.0 ms                                                               | 91.7 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                                | 210 ms: 1.00x slower                                                        |
| regex_compile  | 134 ms                                                                | 140 ms: 1.04x slower                                                        |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                                |

Benchmark hidden because not significant (2): regex_effbot, regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle_list        | 4.99 us                                                               | 4.76 us: 1.05x faster                                                       |
| pickle_dict          | 31.9 us                                                               | 30.8 us: 1.04x faster                                                       |
| unpickle             | 14.7 us                                                               | 14.3 us: 1.03x faster                                                       |
| xml_etree_parse      | 153 ms                                                                | 150 ms: 1.02x faster                                                        |
| pickle               | 10.5 us                                                               | 10.3 us: 1.02x faster                                                       |
| pickle_list          | 4.70 us                                                               | 4.63 us: 1.02x faster                                                       |
| tomli_loads          | 2.04 sec                                                              | 2.01 sec: 1.01x faster                                                      |
| json_dumps           | 9.88 ms                                                               | 9.80 ms: 1.01x faster                                                       |
| xml_etree_iterparse  | 102 ms                                                                | 102 ms: 1.00x slower                                                        |
| pickle_pure_python   | 296 us                                                                | 300 us: 1.02x slower                                                        |
| unpickle_pure_python | 214 us                                                                | 227 us: 1.06x slower                                                        |
| Geometric mean       | (ref)                                                                 | 1.01x faster                                                                |

Benchmark hidden because not significant (3): xml_etree_process, xml_etree_generate, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 6.82 ms                                                               | 6.87 ms: 1.01x slower                                                       |
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                       |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|-----------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 10.6 ms                                                               | 10.8 ms: 1.01x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|--------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| scimark_fft              | 362 ms                                                                | 340 ms: 1.06x faster                                                        |
| scimark_sparse_mat_mult  | 4.64 ms                                                               | 4.37 ms: 1.06x faster                                                       |
| unpickle_list            | 4.99 us                                                               | 4.76 us: 1.05x faster                                                       |
| unpack_sequence          | 43.6 ns                                                               | 42.0 ns: 1.04x faster                                                       |
| pickle_dict              | 31.9 us                                                               | 30.8 us: 1.04x faster                                                       |
| unpickle                 | 14.7 us                                                               | 14.3 us: 1.03x faster                                                       |
| xml_etree_parse          | 153 ms                                                                | 150 ms: 1.02x faster                                                        |
| pickle                   | 10.5 us                                                               | 10.3 us: 1.02x faster                                                       |
| pickle_list              | 4.70 us                                                               | 4.63 us: 1.02x faster                                                       |
| tomli_loads              | 2.04 sec                                                              | 2.01 sec: 1.01x faster                                                      |
| coverage                 | 85.2 ms                                                               | 84.5 ms: 1.01x faster                                                       |
| json_dumps               | 9.88 ms                                                               | 9.80 ms: 1.01x faster                                                       |
| create_gc_cycles         | 1.51 ms                                                               | 1.51 ms: 1.01x faster                                                       |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.79 sec: 1.01x faster                                                      |
| regex_dna                | 209 ms                                                                | 210 ms: 1.00x slower                                                        |
| pidigits                 | 187 ms                                                                | 187 ms: 1.00x slower                                                        |
| xml_etree_iterparse      | 102 ms                                                                | 102 ms: 1.00x slower                                                        |
| generators               | 28.3 ms                                                               | 28.5 ms: 1.01x slower                                                       |
| scimark_sor              | 120 ms                                                                | 121 ms: 1.01x slower                                                        |
| tornado_http             | 95.3 ms                                                               | 95.9 ms: 1.01x slower                                                       |
| python_startup_no_site   | 6.82 ms                                                               | 6.87 ms: 1.01x slower                                                       |
| pathlib                  | 18.6 ms                                                               | 18.7 ms: 1.01x slower                                                       |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                       |
| spectral_norm            | 107 ms                                                                | 108 ms: 1.01x slower                                                        |
| mako                     | 10.6 ms                                                               | 10.8 ms: 1.01x slower                                                       |
| sqlite_synth             | 2.75 us                                                               | 2.79 us: 1.01x slower                                                       |
| async_tree_cpu_io_mixed  | 702 ms                                                                | 712 ms: 1.01x slower                                                        |
| richards                 | 47.7 ms                                                               | 48.4 ms: 1.01x slower                                                       |
| json                     | 4.85 ms                                                               | 4.92 ms: 1.02x slower                                                       |
| sqlglot_parse            | 1.27 ms                                                               | 1.29 ms: 1.02x slower                                                       |
| pickle_pure_python       | 296 us                                                                | 300 us: 1.02x slower                                                        |
| asyncio_tcp              | 489 ms                                                                | 497 ms: 1.02x slower                                                        |
| deepcopy_reduce          | 3.13 us                                                               | 3.19 us: 1.02x slower                                                       |
| deepcopy                 | 349 us                                                                | 355 us: 1.02x slower                                                        |
| dulwich_log              | 66.2 ms                                                               | 67.5 ms: 1.02x slower                                                       |
| bench_thread_pool        | 813 us                                                                | 829 us: 1.02x slower                                                        |
| sqlglot_normalize        | 105 ms                                                                | 107 ms: 1.02x slower                                                        |
| meteor_contest           | 106 ms                                                                | 108 ms: 1.02x slower                                                        |
| pyflate                  | 450 ms                                                                | 459 ms: 1.02x slower                                                        |
| pprint_safe_repr         | 723 ms                                                                | 738 ms: 1.02x slower                                                        |
| scimark_monte_carlo      | 66.2 ms                                                               | 67.6 ms: 1.02x slower                                                       |
| sqlglot_transpile        | 1.58 ms                                                               | 1.61 ms: 1.02x slower                                                       |
| deltablue                | 3.31 ms                                                               | 3.40 ms: 1.03x slower                                                       |
| raytrace                 | 267 ms                                                                | 274 ms: 1.03x slower                                                        |
| scimark_lu               | 110 ms                                                                | 113 ms: 1.03x slower                                                        |
| sqlglot_optimize         | 52.3 ms                                                               | 53.8 ms: 1.03x slower                                                       |
| logging_format           | 6.53 us                                                               | 6.72 us: 1.03x slower                                                       |
| docutils                 | 2.59 sec                                                              | 2.67 sec: 1.03x slower                                                      |
| float                    | 78.5 ms                                                               | 81.0 ms: 1.03x slower                                                       |
| mypy2                    | 337 ms                                                                | 348 ms: 1.03x slower                                                        |
| pprint_pformat           | 1.47 sec                                                              | 1.52 sec: 1.03x slower                                                      |
| logging_simple           | 5.92 us                                                               | 6.13 us: 1.04x slower                                                       |
| fannkuch                 | 382 ms                                                                | 395 ms: 1.04x slower                                                        |
| regex_compile            | 134 ms                                                                | 140 ms: 1.04x slower                                                        |
| nbody                    | 88.0 ms                                                               | 91.7 ms: 1.04x slower                                                       |
| typing_runtime_protocols | 139 us                                                                | 145 us: 1.04x slower                                                        |
| crypto_pyaes             | 67.8 ms                                                               | 70.9 ms: 1.04x slower                                                       |
| async_generators         | 443 ms                                                                | 464 ms: 1.05x slower                                                        |
| go                       | 139 ms                                                                | 147 ms: 1.06x slower                                                        |
| deepcopy_memo            | 36.3 us                                                               | 38.4 us: 1.06x slower                                                       |
| unpickle_pure_python     | 214 us                                                                | 227 us: 1.06x slower                                                        |
| nqueens                  | 79.3 ms                                                               | 85.3 ms: 1.08x slower                                                       |
| chaos                    | 59.8 ms                                                               | 64.7 ms: 1.08x slower                                                       |
| mdp                      | 2.53 sec                                                              | 2.75 sec: 1.09x slower                                                      |
| gc_traversal             | 3.87 ms                                                               | 4.21 ms: 1.09x slower                                                       |
| hexiom                   | 5.99 ms                                                               | 6.64 ms: 1.11x slower                                                       |
| comprehensions           | 20.3 us                                                               | 22.8 us: 1.12x slower                                                       |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                                |

Benchmark hidden because not significant (15): xml_etree_process, xml_etree_generate, regex_effbot, bench_mp_pool, async_tree_io, regex_v8, pycparser, coroutines, dask, json_loads, richards_super, telco, async_tree_memoization, logging_silent, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
