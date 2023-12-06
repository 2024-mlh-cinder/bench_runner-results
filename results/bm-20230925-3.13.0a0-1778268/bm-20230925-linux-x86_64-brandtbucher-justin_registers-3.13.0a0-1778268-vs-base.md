
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 1778268
- commit date: 2023-09-25
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.68 sec: 1.02x slower                                                  |
| tornado_http   | 95.5 ms                                                               | 99.1 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 195 ms: 1.05x slower                                                    |
| float          | 79.3 ms                                                               | 86.8 ms: 1.09x slower                                                   |
| nbody          | 89.7 ms                                                               | 103 ms: 1.14x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.09x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.58 ms                                                               | 3.40 ms: 1.06x faster                                                   |
| regex_v8       | 24.3 ms                                                               | 23.4 ms: 1.04x faster                                                   |
| regex_dna      | 210 ms                                                                | 205 ms: 1.03x faster                                                    |
| regex_compile  | 136 ms                                                                | 149 ms: 1.10x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.01x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_dict          | 32.0 us                                                               | 31.1 us: 1.03x faster                                                   |
| xml_etree_parse      | 153 ms                                                                | 151 ms: 1.02x faster                                                    |
| unpickle_list        | 4.87 us                                                               | 4.80 us: 1.01x faster                                                   |
| json_loads           | 25.3 us                                                               | 25.0 us: 1.01x faster                                                   |
| xml_etree_process    | 58.1 ms                                                               | 57.4 ms: 1.01x faster                                                   |
| xml_etree_generate   | 84.1 ms                                                               | 83.2 ms: 1.01x faster                                                   |
| pickle               | 10.7 us                                                               | 10.6 us: 1.01x faster                                                   |
| json_dumps           | 9.80 ms                                                               | 9.87 ms: 1.01x slower                                                   |
| pickle_pure_python   | 298 us                                                                | 303 us: 1.02x slower                                                    |
| pickle_list          | 4.60 us                                                               | 4.72 us: 1.03x slower                                                   |
| unpickle             | 14.7 us                                                               | 15.1 us: 1.03x slower                                                   |
| tomli_loads          | 2.07 sec                                                              | 2.15 sec: 1.04x slower                                                  |
| xml_etree_iterparse  | 102 ms                                                                | 107 ms: 1.04x slower                                                    |
| unpickle_pure_python | 213 us                                                                | 233 us: 1.09x slower                                                    |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.0 ms: 1.00x slower                                                   |
| python_startup_no_site | 6.85 ms                                                               | 6.88 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                               | 11.5 ms: 1.07x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| gc_traversal             | 4.10 ms                                                               | 3.86 ms: 1.06x faster                                                   |
| regex_effbot             | 3.58 ms                                                               | 3.40 ms: 1.06x faster                                                   |
| pycparser                | 1.20 sec                                                              | 1.16 sec: 1.04x faster                                                  |
| regex_v8                 | 24.3 ms                                                               | 23.4 ms: 1.04x faster                                                   |
| scimark_sor              | 127 ms                                                                | 123 ms: 1.03x faster                                                    |
| pickle_dict              | 32.0 us                                                               | 31.1 us: 1.03x faster                                                   |
| regex_dna                | 210 ms                                                                | 205 ms: 1.03x faster                                                    |
| create_gc_cycles         | 1.53 ms                                                               | 1.50 ms: 1.02x faster                                                   |
| xml_etree_parse          | 153 ms                                                                | 151 ms: 1.02x faster                                                    |
| unpickle_list            | 4.87 us                                                               | 4.80 us: 1.01x faster                                                   |
| mdp                      | 2.66 sec                                                              | 2.62 sec: 1.01x faster                                                  |
| richards                 | 46.9 ms                                                               | 46.3 ms: 1.01x faster                                                   |
| json_loads               | 25.3 us                                                               | 25.0 us: 1.01x faster                                                   |
| xml_etree_process        | 58.1 ms                                                               | 57.4 ms: 1.01x faster                                                   |
| coroutines               | 22.2 ms                                                               | 22.0 ms: 1.01x faster                                                   |
| coverage                 | 87.1 ms                                                               | 86.2 ms: 1.01x faster                                                   |
| richards_super           | 53.3 ms                                                               | 52.7 ms: 1.01x faster                                                   |
| xml_etree_generate       | 84.1 ms                                                               | 83.2 ms: 1.01x faster                                                   |
| pickle                   | 10.7 us                                                               | 10.6 us: 1.01x faster                                                   |
| python_startup           | 10.0 ms                                                               | 10.0 ms: 1.00x slower                                                   |
| async_tree_io            | 1.19 sec                                                              | 1.19 sec: 1.00x slower                                                  |
| python_startup_no_site   | 6.85 ms                                                               | 6.88 ms: 1.01x slower                                                   |
| deepcopy_reduce          | 3.13 us                                                               | 3.15 us: 1.01x slower                                                   |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.81 sec: 1.01x slower                                                  |
| deepcopy                 | 349 us                                                                | 351 us: 1.01x slower                                                    |
| pathlib                  | 18.6 ms                                                               | 18.7 ms: 1.01x slower                                                   |
| json_dumps               | 9.80 ms                                                               | 9.87 ms: 1.01x slower                                                   |
| logging_simple           | 5.93 us                                                               | 6.01 us: 1.01x slower                                                   |
| pickle_pure_python       | 298 us                                                                | 303 us: 1.02x slower                                                    |
| async_tree_memoization   | 564 ms                                                                | 573 ms: 1.02x slower                                                    |
| sqlglot_normalize        | 104 ms                                                                | 106 ms: 1.02x slower                                                    |
| sqlglot_optimize         | 52.7 ms                                                               | 53.7 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed  | 705 ms                                                                | 718 ms: 1.02x slower                                                    |
| spectral_norm            | 107 ms                                                                | 109 ms: 1.02x slower                                                    |
| logging_format           | 6.54 us                                                               | 6.67 us: 1.02x slower                                                   |
| scimark_lu               | 111 ms                                                                | 113 ms: 1.02x slower                                                    |
| generators               | 28.2 ms                                                               | 28.9 ms: 1.02x slower                                                   |
| docutils                 | 2.62 sec                                                              | 2.68 sec: 1.02x slower                                                  |
| pickle_list              | 4.60 us                                                               | 4.72 us: 1.03x slower                                                   |
| unpickle                 | 14.7 us                                                               | 15.1 us: 1.03x slower                                                   |
| meteor_contest           | 107 ms                                                                | 110 ms: 1.03x slower                                                    |
| bench_thread_pool        | 814 us                                                                | 838 us: 1.03x slower                                                    |
| async_tree_none          | 437 ms                                                                | 451 ms: 1.03x slower                                                    |
| sqlglot_transpile        | 1.57 ms                                                               | 1.63 ms: 1.03x slower                                                   |
| sqlglot_parse            | 1.26 ms                                                               | 1.31 ms: 1.03x slower                                                   |
| tomli_loads              | 2.07 sec                                                              | 2.15 sec: 1.04x slower                                                  |
| tornado_http             | 95.5 ms                                                               | 99.1 ms: 1.04x slower                                                   |
| fannkuch                 | 395 ms                                                                | 410 ms: 1.04x slower                                                    |
| async_generators         | 440 ms                                                                | 458 ms: 1.04x slower                                                    |
| xml_etree_iterparse      | 102 ms                                                                | 107 ms: 1.04x slower                                                    |
| pidigits                 | 187 ms                                                                | 195 ms: 1.05x slower                                                    |
| crypto_pyaes             | 69.7 ms                                                               | 73.0 ms: 1.05x slower                                                   |
| dulwich_log              | 66.1 ms                                                               | 69.3 ms: 1.05x slower                                                   |
| deepcopy_memo            | 36.4 us                                                               | 38.7 us: 1.06x slower                                                   |
| mypy2                    | 336 ms                                                                | 358 ms: 1.06x slower                                                    |
| scimark_sparse_mat_mult  | 4.73 ms                                                               | 5.02 ms: 1.06x slower                                                   |
| typing_runtime_protocols | 144 us                                                                | 153 us: 1.07x slower                                                    |
| mako                     | 10.7 ms                                                               | 11.5 ms: 1.07x slower                                                   |
| logging_silent           | 98.2 ns                                                               | 106 ns: 1.08x slower                                                    |
| scimark_monte_carlo      | 65.7 ms                                                               | 71.0 ms: 1.08x slower                                                   |
| go                       | 138 ms                                                                | 150 ms: 1.09x slower                                                    |
| deltablue                | 3.45 ms                                                               | 3.76 ms: 1.09x slower                                                   |
| unpickle_pure_python     | 213 us                                                                | 233 us: 1.09x slower                                                    |
| float                    | 79.3 ms                                                               | 86.8 ms: 1.09x slower                                                   |
| raytrace                 | 269 ms                                                                | 295 ms: 1.10x slower                                                    |
| regex_compile            | 136 ms                                                                | 149 ms: 1.10x slower                                                    |
| unpack_sequence          | 44.0 ns                                                               | 49.0 ns: 1.11x slower                                                   |
| pyflate                  | 447 ms                                                                | 498 ms: 1.12x slower                                                    |
| nbody                    | 89.7 ms                                                               | 103 ms: 1.14x slower                                                    |
| pprint_safe_repr         | 716 ms                                                                | 834 ms: 1.16x slower                                                    |
| nqueens                  | 78.4 ms                                                               | 92.4 ms: 1.18x slower                                                   |
| pprint_pformat           | 1.47 sec                                                              | 1.75 sec: 1.20x slower                                                  |
| chaos                    | 60.8 ms                                                               | 73.5 ms: 1.21x slower                                                   |
| comprehensions           | 20.5 us                                                               | 25.9 us: 1.27x slower                                                   |
| hexiom                   | 5.99 ms                                                               | 8.53 ms: 1.42x slower                                                   |
| Geometric mean           | (ref)                                                                 | 1.04x slower                                                            |

Benchmark hidden because not significant (6): scimark_fft, asyncio_tcp, sqlite_synth, telco, bench_mp_pool, json


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
