
# Results vs. base

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: 1ff7ef4
- commit date: 2023-08-28
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 2.65 sec                                                              | 2.73 sec: 1.03x slower                                            |
| tornado_http   | 95.6 ms                                                               | 98.5 ms: 1.03x slower                                             |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 197 ms                                                                | 189 ms: 1.04x faster                                              |
| float          | 78.9 ms                                                               | 84.1 ms: 1.07x slower                                             |
| nbody          | 89.2 ms                                                               | 102 ms: 1.15x slower                                              |
| Geometric mean | (ref)                                                                 | 1.06x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.73 ms                                                               | 3.47 ms: 1.07x faster                                             |
| regex_v8       | 26.1 ms                                                               | 25.0 ms: 1.04x faster                                             |
| regex_dna      | 222 ms                                                                | 216 ms: 1.03x faster                                              |
| regex_compile  | 136 ms                                                                | 150 ms: 1.10x slower                                              |
| Geometric mean | (ref)                                                                 | 1.01x faster                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_list          | 4.57 us                                                               | 4.52 us: 1.01x faster                                             |
| pickle_pure_python   | 303 us                                                                | 307 us: 1.01x slower                                              |
| json_loads           | 25.1 us                                                               | 25.4 us: 1.01x slower                                             |
| pickle               | 10.6 us                                                               | 10.8 us: 1.02x slower                                             |
| unpickle_list        | 4.98 us                                                               | 5.08 us: 1.02x slower                                             |
| xml_etree_process    | 57.3 ms                                                               | 58.8 ms: 1.03x slower                                             |
| xml_etree_generate   | 82.7 ms                                                               | 85.4 ms: 1.03x slower                                             |
| pickle_dict          | 30.6 us                                                               | 31.6 us: 1.03x slower                                             |
| xml_etree_iterparse  | 102 ms                                                                | 106 ms: 1.03x slower                                              |
| tomli_loads          | 2.15 sec                                                              | 2.36 sec: 1.10x slower                                            |
| unpickle_pure_python | 215 us                                                                | 236 us: 1.10x slower                                              |
| Geometric mean       | (ref)                                                                 | 1.03x slower                                                      |

Benchmark hidden because not significant (3): xml_etree_parse, json_dumps, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 6.85 ms                                                               | 6.86 ms: 1.00x slower                                             |
| python_startup         | 9.36 ms                                                               | 9.37 ms: 1.00x slower                                             |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.8 ms                                                               | 11.8 ms: 1.09x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot             | 3.73 ms                                                               | 3.47 ms: 1.07x faster                                             |
| regex_v8                 | 26.1 ms                                                               | 25.0 ms: 1.04x faster                                             |
| pidigits                 | 197 ms                                                                | 189 ms: 1.04x faster                                              |
| regex_dna                | 222 ms                                                                | 216 ms: 1.03x faster                                              |
| pycparser                | 1.21 sec                                                              | 1.19 sec: 1.02x faster                                            |
| pickle_list              | 4.57 us                                                               | 4.52 us: 1.01x faster                                             |
| python_startup_no_site   | 6.85 ms                                                               | 6.86 ms: 1.00x slower                                             |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.80 sec: 1.00x slower                                            |
| python_startup           | 9.36 ms                                                               | 9.37 ms: 1.00x slower                                             |
| generators               | 28.7 ms                                                               | 28.9 ms: 1.01x slower                                             |
| pickle_pure_python       | 303 us                                                                | 307 us: 1.01x slower                                              |
| telco                    | 8.14 ms                                                               | 8.23 ms: 1.01x slower                                             |
| deepcopy_reduce          | 3.17 us                                                               | 3.22 us: 1.01x slower                                             |
| json_loads               | 25.1 us                                                               | 25.4 us: 1.01x slower                                             |
| scimark_sor              | 122 ms                                                                | 124 ms: 1.01x slower                                              |
| pathlib                  | 18.8 ms                                                               | 19.1 ms: 1.02x slower                                             |
| logging_simple           | 5.86 us                                                               | 5.95 us: 1.02x slower                                             |
| json                     | 4.80 ms                                                               | 4.88 ms: 1.02x slower                                             |
| pickle                   | 10.6 us                                                               | 10.8 us: 1.02x slower                                             |
| unpickle_list            | 4.98 us                                                               | 5.08 us: 1.02x slower                                             |
| scimark_monte_carlo      | 66.7 ms                                                               | 68.1 ms: 1.02x slower                                             |
| scimark_fft              | 366 ms                                                                | 375 ms: 1.02x slower                                              |
| scimark_lu               | 113 ms                                                                | 115 ms: 1.02x slower                                              |
| dask                     | 523 ms                                                                | 536 ms: 1.02x slower                                              |
| logging_format           | 6.48 us                                                               | 6.64 us: 1.02x slower                                             |
| deepcopy                 | 349 us                                                                | 359 us: 1.03x slower                                              |
| async_tree_io            | 1.17 sec                                                              | 1.20 sec: 1.03x slower                                            |
| xml_etree_process        | 57.3 ms                                                               | 58.8 ms: 1.03x slower                                             |
| pprint_safe_repr         | 725 ms                                                                | 746 ms: 1.03x slower                                              |
| sqlglot_normalize        | 105 ms                                                                | 108 ms: 1.03x slower                                              |
| docutils                 | 2.65 sec                                                              | 2.73 sec: 1.03x slower                                            |
| tornado_http             | 95.6 ms                                                               | 98.5 ms: 1.03x slower                                             |
| logging_silent           | 103 ns                                                                | 106 ns: 1.03x slower                                              |
| async_tree_memoization   | 558 ms                                                                | 576 ms: 1.03x slower                                              |
| xml_etree_generate       | 82.7 ms                                                               | 85.4 ms: 1.03x slower                                             |
| pickle_dict              | 30.6 us                                                               | 31.6 us: 1.03x slower                                             |
| async_tree_cpu_io_mixed  | 690 ms                                                                | 713 ms: 1.03x slower                                              |
| xml_etree_iterparse      | 102 ms                                                                | 106 ms: 1.03x slower                                              |
| pprint_pformat           | 1.48 sec                                                              | 1.53 sec: 1.03x slower                                            |
| sqlglot_transpile        | 1.59 ms                                                               | 1.64 ms: 1.04x slower                                             |
| dulwich_log              | 66.2 ms                                                               | 68.7 ms: 1.04x slower                                             |
| mdp                      | 2.70 sec                                                              | 2.81 sec: 1.04x slower                                            |
| sqlglot_optimize         | 52.7 ms                                                               | 54.7 ms: 1.04x slower                                             |
| async_tree_none          | 431 ms                                                                | 449 ms: 1.04x slower                                              |
| typing_runtime_protocols | 143 us                                                                | 149 us: 1.04x slower                                              |
| richards                 | 47.8 ms                                                               | 49.8 ms: 1.04x slower                                             |
| spectral_norm            | 105 ms                                                                | 109 ms: 1.04x slower                                              |
| sqlglot_parse            | 1.27 ms                                                               | 1.32 ms: 1.04x slower                                             |
| mypy2                    | 338 ms                                                                | 352 ms: 1.04x slower                                              |
| asyncio_tcp              | 489 ms                                                                | 510 ms: 1.04x slower                                              |
| bench_thread_pool        | 820 us                                                                | 859 us: 1.05x slower                                              |
| coroutines               | 22.0 ms                                                               | 23.1 ms: 1.05x slower                                             |
| richards_super           | 53.5 ms                                                               | 56.5 ms: 1.06x slower                                             |
| raytrace                 | 272 ms                                                                | 288 ms: 1.06x slower                                              |
| async_generators         | 447 ms                                                                | 473 ms: 1.06x slower                                              |
| float                    | 78.9 ms                                                               | 84.1 ms: 1.07x slower                                             |
| crypto_pyaes             | 69.0 ms                                                               | 73.6 ms: 1.07x slower                                             |
| scimark_sparse_mat_mult  | 4.99 ms                                                               | 5.37 ms: 1.08x slower                                             |
| deltablue                | 3.33 ms                                                               | 3.59 ms: 1.08x slower                                             |
| go                       | 139 ms                                                                | 150 ms: 1.08x slower                                              |
| deepcopy_memo            | 37.0 us                                                               | 40.4 us: 1.09x slower                                             |
| mako                     | 10.8 ms                                                               | 11.8 ms: 1.09x slower                                             |
| tomli_loads              | 2.15 sec                                                              | 2.36 sec: 1.10x slower                                            |
| unpickle_pure_python     | 215 us                                                                | 236 us: 1.10x slower                                              |
| regex_compile            | 136 ms                                                                | 150 ms: 1.10x slower                                              |
| meteor_contest           | 105 ms                                                                | 116 ms: 1.10x slower                                              |
| chaos                    | 60.1 ms                                                               | 67.2 ms: 1.12x slower                                             |
| fannkuch                 | 391 ms                                                                | 441 ms: 1.13x slower                                              |
| gc_traversal             | 3.66 ms                                                               | 4.19 ms: 1.14x slower                                             |
| nbody                    | 89.2 ms                                                               | 102 ms: 1.15x slower                                              |
| pyflate                  | 446 ms                                                                | 516 ms: 1.16x slower                                              |
| nqueens                  | 81.6 ms                                                               | 96.8 ms: 1.19x slower                                             |
| comprehensions           | 20.9 us                                                               | 25.1 us: 1.20x slower                                             |
| unpack_sequence          | 40.3 ns                                                               | 48.7 ns: 1.21x slower                                             |
| hexiom                   | 6.07 ms                                                               | 7.57 ms: 1.25x slower                                             |
| Geometric mean           | (ref)                                                                 | 1.04x slower                                                      |

Benchmark hidden because not significant (7): coverage, bench_mp_pool, create_gc_cycles, sqlite_synth, xml_etree_parse, json_dumps, unpickle


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
