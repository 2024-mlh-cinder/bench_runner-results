
# Results vs. 3.12.0

- fork: iritkatriel
- ref: INSTRUMENTED_LINE
- machine: linux-x86_64
- commit hash: 31b3dd0
- commit date: 2023-09-13
- overall geometric mean: 1.00x faster
- HPT reliability: 99.93%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                  |
| tornado_http   | 99.6 ms                                                | 95.7 ms: 1.04x faster                                                   |
| Geometric mean | (ref)                                                  | 1.04x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.1 ms: 1.02x faster                                                   |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                    |
| nbody          | 88.8 ms                                                | 91.8 ms: 1.03x slower                                                   |
| Geometric mean | (ref)                                                  | 1.00x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 135 ms: 1.07x faster                                                    |
| regex_effbot   | 3.55 ms                                                | 3.48 ms: 1.02x faster                                                   |
| regex_v8       | 22.3 ms                                                | 23.9 ms: 1.07x slower                                                   |
| Geometric mean | (ref)                                                  | 1.00x faster                                                            |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.05 sec: 1.08x faster                                                  |
| unpickle             | 15.0 us                                                | 14.2 us: 1.05x faster                                                   |
| pickle               | 10.6 us                                                | 10.4 us: 1.02x faster                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                                    |
| unpickle_list        | 4.95 us                                                | 4.86 us: 1.02x faster                                                   |
| xml_etree_process    | 58.6 ms                                                | 57.5 ms: 1.02x faster                                                   |
| xml_etree_parse      | 154 ms                                                 | 151 ms: 1.01x faster                                                    |
| xml_etree_generate   | 84.8 ms                                                | 83.8 ms: 1.01x faster                                                   |
| pickle_dict          | 31.6 us                                                | 31.7 us: 1.00x slower                                                   |
| unpickle_pure_python | 218 us                                                 | 221 us: 1.01x slower                                                    |
| pickle_list          | 4.62 us                                                | 4.77 us: 1.03x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                            |

Benchmark hidden because not significant (3): pickle_pure_python, json_dumps, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.85 ms: 1.01x faster                                                   |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 69.0 ms: 1.12x faster                                                   |
| coverage                 | 94.2 ms                                                | 85.5 ms: 1.10x faster                                                   |
| raytrace                 | 294 ms                                                 | 269 ms: 1.09x faster                                                    |
| tomli_loads              | 2.22 sec                                               | 2.05 sec: 1.08x faster                                                  |
| deltablue                | 3.52 ms                                                | 3.26 ms: 1.08x faster                                                   |
| asyncio_tcp              | 526 ms                                                 | 490 ms: 1.07x faster                                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 66.2 ms: 1.07x faster                                                   |
| regex_compile            | 144 ms                                                 | 135 ms: 1.07x faster                                                    |
| unpickle                 | 15.0 us                                                | 14.2 us: 1.05x faster                                                   |
| chaos                    | 63.5 ms                                                | 60.5 ms: 1.05x faster                                                   |
| logging_format           | 6.90 us                                                | 6.62 us: 1.04x faster                                                   |
| scimark_lu               | 114 ms                                                 | 109 ms: 1.04x faster                                                    |
| tornado_http             | 99.6 ms                                                | 95.7 ms: 1.04x faster                                                   |
| async_tree_none          | 469 ms                                                 | 451 ms: 1.04x faster                                                    |
| sqlglot_parse            | 1.32 ms                                                | 1.27 ms: 1.04x faster                                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.58 ms: 1.04x faster                                                   |
| nqueens                  | 81.1 ms                                                | 78.2 ms: 1.04x faster                                                   |
| generators               | 31.1 ms                                                | 30.0 ms: 1.04x faster                                                   |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.59 ms: 1.03x faster                                                   |
| docutils                 | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                  |
| logging_simple           | 6.18 us                                                | 5.99 us: 1.03x faster                                                   |
| typing_runtime_protocols | 146 us                                                 | 142 us: 1.03x faster                                                    |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                                    |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                                    |
| float                    | 80.7 ms                                                | 79.1 ms: 1.02x faster                                                   |
| pickle                   | 10.6 us                                                | 10.4 us: 1.02x faster                                                   |
| fannkuch                 | 387 ms                                                 | 379 ms: 1.02x faster                                                    |
| coroutines               | 22.4 ms                                                | 22.0 ms: 1.02x faster                                                   |
| mdp                      | 2.57 sec                                               | 2.52 sec: 1.02x faster                                                  |
| regex_effbot             | 3.55 ms                                                | 3.48 ms: 1.02x faster                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                                    |
| async_generators         | 440 ms                                                 | 432 ms: 1.02x faster                                                    |
| unpickle_list            | 4.95 us                                                | 4.86 us: 1.02x faster                                                   |
| xml_etree_process        | 58.6 ms                                                | 57.5 ms: 1.02x faster                                                   |
| bench_thread_pool        | 827 us                                                 | 813 us: 1.02x faster                                                    |
| hexiom                   | 6.12 ms                                                | 6.02 ms: 1.02x faster                                                   |
| dulwich_log              | 67.9 ms                                                | 66.8 ms: 1.02x faster                                                   |
| mypy2                    | 344 ms                                                 | 338 ms: 1.02x faster                                                    |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.01x faster                                                    |
| deepcopy                 | 355 us                                                 | 351 us: 1.01x faster                                                    |
| pprint_safe_repr         | 735 ms                                                 | 726 ms: 1.01x faster                                                    |
| xml_etree_generate       | 84.8 ms                                                | 83.8 ms: 1.01x faster                                                   |
| scimark_fft              | 358 ms                                                 | 354 ms: 1.01x faster                                                    |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                                   |
| sqlglot_optimize         | 53.3 ms                                                | 52.8 ms: 1.01x faster                                                   |
| pprint_pformat           | 1.50 sec                                               | 1.49 sec: 1.01x faster                                                  |
| python_startup_no_site   | 6.90 ms                                                | 6.85 ms: 1.01x faster                                                   |
| comprehensions           | 20.4 us                                                | 20.4 us: 1.00x faster                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                  |
| pickle_dict              | 31.6 us                                                | 31.7 us: 1.00x slower                                                   |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                    |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                    |
| unpickle_pure_python     | 218 us                                                 | 221 us: 1.01x slower                                                    |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.01x slower                                                   |
| async_tree_memoization   | 573 ms                                                 | 581 ms: 1.01x slower                                                    |
| spectral_norm            | 106 ms                                                 | 108 ms: 1.02x slower                                                    |
| go                       | 136 ms                                                 | 139 ms: 1.02x slower                                                    |
| deepcopy_reduce          | 3.14 us                                                | 3.22 us: 1.03x slower                                                   |
| pickle_list              | 4.62 us                                                | 4.77 us: 1.03x slower                                                   |
| nbody                    | 88.8 ms                                                | 91.8 ms: 1.03x slower                                                   |
| logging_silent           | 99.1 ns                                                | 104 ns: 1.05x slower                                                    |
| async_tree_io            | 1.16 sec                                               | 1.23 sec: 1.06x slower                                                  |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                   |
| gc_traversal             | 3.84 ms                                                | 4.10 ms: 1.07x slower                                                   |
| regex_v8                 | 22.3 ms                                                | 23.9 ms: 1.07x slower                                                   |
| richards                 | 43.2 ms                                                | 48.8 ms: 1.13x slower                                                   |
| richards_super           | 49.0 ms                                                | 55.5 ms: 1.13x slower                                                   |
| unpack_sequence          | 44.8 ns                                                | 51.9 ns: 1.16x slower                                                   |
| telco                    | 6.87 ms                                                | 8.11 ms: 1.18x slower                                                   |
| dask                     | 365 ms                                                 | 526 ms: 1.44x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                            |

Benchmark hidden because not significant (12): pycparser, json, pyflate, pickle_pure_python, deepcopy_memo, regex_dna, bench_mp_pool, json_dumps, create_gc_cycles, mako, json_loads, async_tree_cpu_io_mixed
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.93% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
