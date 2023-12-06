
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: f1573ca
- commit date: 2023-09-25
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.70 sec: 1.03x slower                                                  |
| tornado_http   | 95.5 ms                                                               | 99.6 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.04x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.01x slower                                                    |
| float          | 79.3 ms                                                               | 96.1 ms: 1.21x slower                                                   |
| nbody          | 89.7 ms                                                               | 111 ms: 1.23x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.15x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.58 ms                                                               | 3.45 ms: 1.04x faster                                                   |
| regex_v8       | 24.3 ms                                                               | 23.5 ms: 1.03x faster                                                   |
| regex_dna      | 210 ms                                                                | 206 ms: 1.02x faster                                                    |
| regex_compile  | 136 ms                                                                | 154 ms: 1.13x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_loads           | 25.3 us                                                               | 24.8 us: 1.02x faster                                                   |
| pickle               | 10.7 us                                                               | 10.5 us: 1.02x faster                                                   |
| pickle_dict          | 32.0 us                                                               | 31.5 us: 1.01x faster                                                   |
| xml_etree_generate   | 84.1 ms                                                               | 83.6 ms: 1.01x faster                                                   |
| pickle_pure_python   | 298 us                                                                | 301 us: 1.01x slower                                                    |
| unpickle             | 14.7 us                                                               | 15.2 us: 1.03x slower                                                   |
| pickle_list          | 4.60 us                                                               | 4.80 us: 1.04x slower                                                   |
| xml_etree_iterparse  | 102 ms                                                                | 109 ms: 1.06x slower                                                    |
| tomli_loads          | 2.07 sec                                                              | 2.27 sec: 1.10x slower                                                  |
| unpickle_pure_python | 213 us                                                                | 238 us: 1.12x slower                                                    |
| Geometric mean       | (ref)                                                                 | 1.02x slower                                                            |

Benchmark hidden because not significant (4): unpickle_list, xml_etree_parse, xml_etree_process, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                   |
| python_startup_no_site | 6.85 ms                                                               | 6.92 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                               | 11.8 ms: 1.10x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot             | 3.58 ms                                                               | 3.45 ms: 1.04x faster                                                   |
| regex_v8                 | 24.3 ms                                                               | 23.5 ms: 1.03x faster                                                   |
| pycparser                | 1.20 sec                                                              | 1.17 sec: 1.03x faster                                                  |
| scimark_sor              | 127 ms                                                                | 123 ms: 1.03x faster                                                    |
| json_loads               | 25.3 us                                                               | 24.8 us: 1.02x faster                                                   |
| regex_dna                | 210 ms                                                                | 206 ms: 1.02x faster                                                    |
| pickle                   | 10.7 us                                                               | 10.5 us: 1.02x faster                                                   |
| pickle_dict              | 32.0 us                                                               | 31.5 us: 1.01x faster                                                   |
| sqlite_synth             | 2.77 us                                                               | 2.74 us: 1.01x faster                                                   |
| create_gc_cycles         | 1.53 ms                                                               | 1.51 ms: 1.01x faster                                                   |
| xml_etree_generate       | 84.1 ms                                                               | 83.6 ms: 1.01x faster                                                   |
| gc_traversal             | 4.10 ms                                                               | 4.11 ms: 1.00x slower                                                   |
| spectral_norm            | 107 ms                                                                | 108 ms: 1.01x slower                                                    |
| telco                    | 8.03 ms                                                               | 8.08 ms: 1.01x slower                                                   |
| pathlib                  | 18.6 ms                                                               | 18.7 ms: 1.01x slower                                                   |
| deepcopy_reduce          | 3.13 us                                                               | 3.16 us: 1.01x slower                                                   |
| pidigits                 | 187 ms                                                                | 188 ms: 1.01x slower                                                    |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                   |
| pickle_pure_python       | 298 us                                                                | 301 us: 1.01x slower                                                    |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.82 sec: 1.01x slower                                                  |
| python_startup_no_site   | 6.85 ms                                                               | 6.92 ms: 1.01x slower                                                   |
| generators               | 28.2 ms                                                               | 28.6 ms: 1.01x slower                                                   |
| async_tree_io            | 1.19 sec                                                              | 1.20 sec: 1.02x slower                                                  |
| asyncio_tcp              | 502 ms                                                                | 511 ms: 1.02x slower                                                    |
| async_tree_cpu_io_mixed  | 705 ms                                                                | 717 ms: 1.02x slower                                                    |
| sqlglot_normalize        | 104 ms                                                                | 106 ms: 1.02x slower                                                    |
| deepcopy                 | 349 us                                                                | 355 us: 1.02x slower                                                    |
| sqlglot_optimize         | 52.7 ms                                                               | 53.8 ms: 1.02x slower                                                   |
| logging_simple           | 5.93 us                                                               | 6.09 us: 1.03x slower                                                   |
| docutils                 | 2.62 sec                                                              | 2.70 sec: 1.03x slower                                                  |
| scimark_lu               | 111 ms                                                                | 114 ms: 1.03x slower                                                    |
| async_tree_none          | 437 ms                                                                | 451 ms: 1.03x slower                                                    |
| bench_thread_pool        | 814 us                                                                | 840 us: 1.03x slower                                                    |
| richards                 | 46.9 ms                                                               | 48.5 ms: 1.03x slower                                                   |
| unpickle                 | 14.7 us                                                               | 15.2 us: 1.03x slower                                                   |
| async_tree_memoization   | 564 ms                                                                | 584 ms: 1.04x slower                                                    |
| logging_format           | 6.54 us                                                               | 6.77 us: 1.04x slower                                                   |
| scimark_fft              | 360 ms                                                                | 373 ms: 1.04x slower                                                    |
| dulwich_log              | 66.1 ms                                                               | 68.5 ms: 1.04x slower                                                   |
| richards_super           | 53.3 ms                                                               | 55.3 ms: 1.04x slower                                                   |
| sqlglot_transpile        | 1.57 ms                                                               | 1.64 ms: 1.04x slower                                                   |
| sqlglot_parse            | 1.26 ms                                                               | 1.32 ms: 1.04x slower                                                   |
| pickle_list              | 4.60 us                                                               | 4.80 us: 1.04x slower                                                   |
| tornado_http             | 95.5 ms                                                               | 99.6 ms: 1.04x slower                                                   |
| meteor_contest           | 107 ms                                                                | 111 ms: 1.04x slower                                                    |
| crypto_pyaes             | 69.7 ms                                                               | 72.9 ms: 1.05x slower                                                   |
| mdp                      | 2.66 sec                                                              | 2.78 sec: 1.05x slower                                                  |
| async_generators         | 440 ms                                                                | 463 ms: 1.05x slower                                                    |
| typing_runtime_protocols | 144 us                                                                | 152 us: 1.05x slower                                                    |
| mypy2                    | 336 ms                                                                | 358 ms: 1.06x slower                                                    |
| xml_etree_iterparse      | 102 ms                                                                | 109 ms: 1.06x slower                                                    |
| logging_silent           | 98.2 ns                                                               | 105 ns: 1.07x slower                                                    |
| scimark_sparse_mat_mult  | 4.73 ms                                                               | 5.09 ms: 1.08x slower                                                   |
| tomli_loads              | 2.07 sec                                                              | 2.27 sec: 1.10x slower                                                  |
| deepcopy_memo            | 36.4 us                                                               | 40.0 us: 1.10x slower                                                   |
| mako                     | 10.7 ms                                                               | 11.8 ms: 1.10x slower                                                   |
| unpack_sequence          | 44.0 ns                                                               | 48.6 ns: 1.10x slower                                                   |
| go                       | 138 ms                                                                | 153 ms: 1.11x slower                                                    |
| unpickle_pure_python     | 213 us                                                                | 238 us: 1.12x slower                                                    |
| fannkuch                 | 395 ms                                                                | 442 ms: 1.12x slower                                                    |
| scimark_monte_carlo      | 65.7 ms                                                               | 74.1 ms: 1.13x slower                                                   |
| raytrace                 | 269 ms                                                                | 305 ms: 1.13x slower                                                    |
| regex_compile            | 136 ms                                                                | 154 ms: 1.13x slower                                                    |
| pyflate                  | 447 ms                                                                | 533 ms: 1.19x slower                                                    |
| pprint_safe_repr         | 716 ms                                                                | 865 ms: 1.21x slower                                                    |
| float                    | 79.3 ms                                                               | 96.1 ms: 1.21x slower                                                   |
| nbody                    | 89.7 ms                                                               | 111 ms: 1.23x slower                                                    |
| deltablue                | 3.45 ms                                                               | 4.26 ms: 1.23x slower                                                   |
| nqueens                  | 78.4 ms                                                               | 97.2 ms: 1.24x slower                                                   |
| pprint_pformat           | 1.47 sec                                                              | 1.82 sec: 1.24x slower                                                  |
| chaos                    | 60.8 ms                                                               | 76.5 ms: 1.26x slower                                                   |
| comprehensions           | 20.5 us                                                               | 26.8 us: 1.31x slower                                                   |
| hexiom                   | 5.99 ms                                                               | 9.45 ms: 1.58x slower                                                   |
| Geometric mean           | (ref)                                                                 | 1.06x slower                                                            |

Benchmark hidden because not significant (8): unpickle_list, coroutines, bench_mp_pool, xml_etree_parse, xml_etree_process, json_dumps, coverage, json


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
