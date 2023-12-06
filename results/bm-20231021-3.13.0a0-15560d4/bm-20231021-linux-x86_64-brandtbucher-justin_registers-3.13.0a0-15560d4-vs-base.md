
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 15560d4
- commit date: 2023-10-21
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.74 sec: 1.04x slower                                                  |
| tornado_http   | 95.5 ms                                                               | 99.7 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.04x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.01x slower                                                    |
| float          | 79.3 ms                                                               | 86.8 ms: 1.09x slower                                                   |
| nbody          | 89.7 ms                                                               | 100.0 ms: 1.11x slower                                                  |
| Geometric mean | (ref)                                                                 | 1.07x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.58 ms                                                               | 3.65 ms: 1.02x slower                                                   |
| regex_dna      | 210 ms                                                                | 217 ms: 1.03x slower                                                    |
| regex_v8       | 24.3 ms                                                               | 25.8 ms: 1.06x slower                                                   |
| regex_compile  | 136 ms                                                                | 151 ms: 1.11x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.06x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpickle_list        | 4.87 us                                                               | 5.00 us: 1.03x slower                                                   |
| pickle_pure_python   | 298 us                                                                | 308 us: 1.03x slower                                                    |
| xml_etree_parse      | 153 ms                                                                | 158 ms: 1.03x slower                                                    |
| tomli_loads          | 2.07 sec                                                              | 2.14 sec: 1.03x slower                                                  |
| xml_etree_generate   | 84.1 ms                                                               | 87.0 ms: 1.03x slower                                                   |
| xml_etree_process    | 58.1 ms                                                               | 60.2 ms: 1.04x slower                                                   |
| unpickle             | 14.7 us                                                               | 15.4 us: 1.05x slower                                                   |
| xml_etree_iterparse  | 102 ms                                                                | 109 ms: 1.07x slower                                                    |
| pickle_dict          | 32.0 us                                                               | 34.5 us: 1.08x slower                                                   |
| pickle               | 10.7 us                                                               | 11.6 us: 1.08x slower                                                   |
| json_dumps           | 9.80 ms                                                               | 10.6 ms: 1.08x slower                                                   |
| pickle_list          | 4.60 us                                                               | 5.02 us: 1.09x slower                                                   |
| unpickle_pure_python | 213 us                                                                | 234 us: 1.10x slower                                                    |
| json_loads           | 25.3 us                                                               | 28.3 us: 1.12x slower                                                   |
| Geometric mean       | (ref)                                                                 | 1.06x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.85 ms                                                               | 6.93 ms: 1.01x slower                                                   |
| python_startup         | 10.0 ms                                                               | 10.2 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                               | 12.1 ms: 1.13x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| gc_traversal             | 4.10 ms                                                               | 3.82 ms: 1.07x faster                                                   |
| create_gc_cycles         | 1.53 ms                                                               | 1.46 ms: 1.04x faster                                                   |
| asyncio_tcp              | 502 ms                                                                | 490 ms: 1.02x faster                                                    |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.80 sec: 1.00x faster                                                  |
| pidigits                 | 187 ms                                                                | 188 ms: 1.01x slower                                                    |
| pycparser                | 1.20 sec                                                              | 1.22 sec: 1.01x slower                                                  |
| python_startup_no_site   | 6.85 ms                                                               | 6.93 ms: 1.01x slower                                                   |
| coroutines               | 22.2 ms                                                               | 22.5 ms: 1.01x slower                                                   |
| python_startup           | 10.0 ms                                                               | 10.2 ms: 1.01x slower                                                   |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.02x slower                                                  |
| deepcopy_reduce          | 3.13 us                                                               | 3.19 us: 1.02x slower                                                   |
| regex_effbot             | 3.58 ms                                                               | 3.65 ms: 1.02x slower                                                   |
| richards                 | 46.9 ms                                                               | 47.9 ms: 1.02x slower                                                   |
| sqlite_synth             | 2.77 us                                                               | 2.83 us: 1.02x slower                                                   |
| pathlib                  | 18.6 ms                                                               | 19.0 ms: 1.02x slower                                                   |
| richards_super           | 53.3 ms                                                               | 54.5 ms: 1.02x slower                                                   |
| unpickle_list            | 4.87 us                                                               | 5.00 us: 1.03x slower                                                   |
| async_tree_memoization   | 564 ms                                                                | 579 ms: 1.03x slower                                                    |
| async_tree_cpu_io_mixed  | 705 ms                                                                | 724 ms: 1.03x slower                                                    |
| async_tree_none          | 437 ms                                                                | 450 ms: 1.03x slower                                                    |
| pickle_pure_python       | 298 us                                                                | 308 us: 1.03x slower                                                    |
| xml_etree_parse          | 153 ms                                                                | 158 ms: 1.03x slower                                                    |
| tomli_loads              | 2.07 sec                                                              | 2.14 sec: 1.03x slower                                                  |
| xml_etree_generate       | 84.1 ms                                                               | 87.0 ms: 1.03x slower                                                   |
| regex_dna                | 210 ms                                                                | 217 ms: 1.03x slower                                                    |
| xml_etree_process        | 58.1 ms                                                               | 60.2 ms: 1.04x slower                                                   |
| bench_thread_pool        | 814 us                                                                | 843 us: 1.04x slower                                                    |
| deepcopy                 | 349 us                                                                | 362 us: 1.04x slower                                                    |
| sqlglot_optimize         | 52.7 ms                                                               | 54.7 ms: 1.04x slower                                                   |
| sqlglot_normalize        | 104 ms                                                                | 108 ms: 1.04x slower                                                    |
| generators               | 28.2 ms                                                               | 29.4 ms: 1.04x slower                                                   |
| logging_simple           | 5.93 us                                                               | 6.17 us: 1.04x slower                                                   |
| sqlglot_parse            | 1.26 ms                                                               | 1.32 ms: 1.04x slower                                                   |
| sqlglot_transpile        | 1.57 ms                                                               | 1.64 ms: 1.04x slower                                                   |
| tornado_http             | 95.5 ms                                                               | 99.7 ms: 1.04x slower                                                   |
| docutils                 | 2.62 sec                                                              | 2.74 sec: 1.04x slower                                                  |
| coverage                 | 87.1 ms                                                               | 91.2 ms: 1.05x slower                                                   |
| meteor_contest           | 107 ms                                                                | 112 ms: 1.05x slower                                                    |
| unpickle                 | 14.7 us                                                               | 15.4 us: 1.05x slower                                                   |
| logging_format           | 6.54 us                                                               | 6.86 us: 1.05x slower                                                   |
| mdp                      | 2.66 sec                                                              | 2.81 sec: 1.06x slower                                                  |
| dulwich_log              | 66.1 ms                                                               | 69.8 ms: 1.06x slower                                                   |
| scimark_sparse_mat_mult  | 4.73 ms                                                               | 5.00 ms: 1.06x slower                                                   |
| regex_v8                 | 24.3 ms                                                               | 25.8 ms: 1.06x slower                                                   |
| telco                    | 8.03 ms                                                               | 8.52 ms: 1.06x slower                                                   |
| scimark_lu               | 111 ms                                                                | 118 ms: 1.07x slower                                                    |
| xml_etree_iterparse      | 102 ms                                                                | 109 ms: 1.07x slower                                                    |
| fannkuch                 | 395 ms                                                                | 423 ms: 1.07x slower                                                    |
| mypy2                    | 336 ms                                                                | 361 ms: 1.07x slower                                                    |
| pickle_dict              | 32.0 us                                                               | 34.5 us: 1.08x slower                                                   |
| pickle                   | 10.7 us                                                               | 11.6 us: 1.08x slower                                                   |
| json_dumps               | 9.80 ms                                                               | 10.6 ms: 1.08x slower                                                   |
| async_generators         | 440 ms                                                                | 476 ms: 1.08x slower                                                    |
| json                     | 4.77 ms                                                               | 5.20 ms: 1.09x slower                                                   |
| pickle_list              | 4.60 us                                                               | 5.02 us: 1.09x slower                                                   |
| crypto_pyaes             | 69.7 ms                                                               | 76.2 ms: 1.09x slower                                                   |
| logging_silent           | 98.2 ns                                                               | 107 ns: 1.09x slower                                                    |
| typing_runtime_protocols | 144 us                                                                | 158 us: 1.09x slower                                                    |
| float                    | 79.3 ms                                                               | 86.8 ms: 1.09x slower                                                   |
| unpickle_pure_python     | 213 us                                                                | 234 us: 1.10x slower                                                    |
| spectral_norm            | 107 ms                                                                | 118 ms: 1.10x slower                                                    |
| deltablue                | 3.45 ms                                                               | 3.81 ms: 1.10x slower                                                   |
| go                       | 138 ms                                                                | 153 ms: 1.11x slower                                                    |
| nbody                    | 89.7 ms                                                               | 100.0 ms: 1.11x slower                                                  |
| regex_compile            | 136 ms                                                                | 151 ms: 1.11x slower                                                    |
| raytrace                 | 269 ms                                                                | 301 ms: 1.12x slower                                                    |
| json_loads               | 25.3 us                                                               | 28.3 us: 1.12x slower                                                   |
| deepcopy_memo            | 36.4 us                                                               | 40.8 us: 1.12x slower                                                   |
| mako                     | 10.7 ms                                                               | 12.1 ms: 1.13x slower                                                   |
| scimark_monte_carlo      | 65.7 ms                                                               | 74.1 ms: 1.13x slower                                                   |
| pyflate                  | 447 ms                                                                | 517 ms: 1.16x slower                                                    |
| pprint_safe_repr         | 716 ms                                                                | 835 ms: 1.17x slower                                                    |
| nqueens                  | 78.4 ms                                                               | 92.6 ms: 1.18x slower                                                   |
| pprint_pformat           | 1.47 sec                                                              | 1.73 sec: 1.18x slower                                                  |
| chaos                    | 60.8 ms                                                               | 73.7 ms: 1.21x slower                                                   |
| unpack_sequence          | 44.0 ns                                                               | 53.6 ns: 1.22x slower                                                   |
| comprehensions           | 20.5 us                                                               | 25.9 us: 1.26x slower                                                   |
| hexiom                   | 5.99 ms                                                               | 8.25 ms: 1.38x slower                                                   |
| Geometric mean           | (ref)                                                                 | 1.06x slower                                                            |

Benchmark hidden because not significant (3): bench_mp_pool, scimark_sor, scimark_fft


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
