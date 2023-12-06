
# Results vs. 3.12.0

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 3f2d583
- commit date: 2023-10-04
- overall geometric mean: 1.08x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 3.01 sec: 1.04x slower                                                     |
| tornado_http   | 122 ms                                                       | 125 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.01x slower                                                       |
| nbody          | 94.1 ms                                                      | 114 ms: 1.21x slower                                                       |
| float          | 78.5 ms                                                      | 104 ms: 1.32x slower                                                       |
| Geometric mean | (ref)                                                        | 1.17x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.47 ms                                                      | 3.35 ms: 1.04x faster                                                      |
| regex_dna      | 241 ms                                                       | 234 ms: 1.03x faster                                                       |
| regex_v8       | 25.0 ms                                                      | 25.1 ms: 1.00x slower                                                      |
| regex_compile  | 146 ms                                                       | 178 ms: 1.22x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.27 us: 1.03x faster                                                      |
| unpickle             | 14.8 us                                                      | 14.6 us: 1.01x faster                                                      |
| unpickle_list        | 4.77 us                                                      | 4.73 us: 1.01x faster                                                      |
| pickle_dict          | 31.7 us                                                      | 32.0 us: 1.01x slower                                                      |
| xml_etree_generate   | 86.1 ms                                                      | 87.0 ms: 1.01x slower                                                      |
| xml_etree_process    | 58.3 ms                                                      | 59.2 ms: 1.02x slower                                                      |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                                       |
| json_loads           | 24.3 us                                                      | 24.9 us: 1.02x slower                                                      |
| json_dumps           | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                                      |
| xml_etree_iterparse  | 103 ms                                                       | 112 ms: 1.08x slower                                                       |
| unpickle_pure_python | 207 us                                                       | 239 us: 1.15x slower                                                       |
| tomli_loads          | 2.20 sec                                                     | 2.65 sec: 1.21x slower                                                     |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                               |

Benchmark hidden because not significant (2): pickle_pure_python, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                                      |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 13.7 ms: 1.38x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpack_sequence          | 53.3 ns                                                      | 41.0 ns: 1.30x faster                                                      |
| bench_mp_pool            | 5.34 ms                                                      | 4.80 ms: 1.11x faster                                                      |
| coverage                 | 89.6 ms                                                      | 80.6 ms: 1.11x faster                                                      |
| regex_effbot             | 3.47 ms                                                      | 3.35 ms: 1.04x faster                                                      |
| regex_dna                | 241 ms                                                       | 234 ms: 1.03x faster                                                       |
| pickle_list              | 4.39 us                                                      | 4.27 us: 1.03x faster                                                      |
| deepcopy_reduce          | 3.46 us                                                      | 3.37 us: 1.03x faster                                                      |
| asyncio_tcp              | 381 ms                                                       | 374 ms: 1.02x faster                                                       |
| raytrace                 | 302 ms                                                       | 297 ms: 1.02x faster                                                       |
| unpickle                 | 14.8 us                                                      | 14.6 us: 1.01x faster                                                      |
| unpickle_list            | 4.77 us                                                      | 4.73 us: 1.01x faster                                                      |
| generators               | 36.7 ms                                                      | 36.6 ms: 1.00x faster                                                      |
| python_startup_no_site   | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                                      |
| regex_v8                 | 25.0 ms                                                      | 25.1 ms: 1.00x slower                                                      |
| pidigits                 | 264 ms                                                       | 265 ms: 1.01x slower                                                       |
| sqlite_synth             | 2.70 us                                                      | 2.72 us: 1.01x slower                                                      |
| spectral_norm            | 91.6 ms                                                      | 92.2 ms: 1.01x slower                                                      |
| pickle_dict              | 31.7 us                                                      | 32.0 us: 1.01x slower                                                      |
| xml_etree_generate       | 86.1 ms                                                      | 87.0 ms: 1.01x slower                                                      |
| sqlglot_normalize        | 117 ms                                                       | 119 ms: 1.01x slower                                                       |
| create_gc_cycles         | 1.67 ms                                                      | 1.70 ms: 1.01x slower                                                      |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.60 sec: 1.01x slower                                                     |
| xml_etree_process        | 58.3 ms                                                      | 59.2 ms: 1.02x slower                                                      |
| xml_etree_parse          | 146 ms                                                       | 149 ms: 1.02x slower                                                       |
| json_loads               | 24.3 us                                                      | 24.9 us: 1.02x slower                                                      |
| async_generators         | 385 ms                                                       | 395 ms: 1.02x slower                                                       |
| deepcopy                 | 376 us                                                       | 385 us: 1.03x slower                                                       |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 726 ms: 1.03x slower                                                       |
| async_tree_memoization   | 553 ms                                                       | 570 ms: 1.03x slower                                                       |
| tornado_http             | 122 ms                                                       | 125 ms: 1.03x slower                                                       |
| json_dumps               | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                                      |
| crypto_pyaes             | 80.9 ms                                                      | 84.0 ms: 1.04x slower                                                      |
| pathlib                  | 19.8 ms                                                      | 20.6 ms: 1.04x slower                                                      |
| sqlglot_parse            | 1.40 ms                                                      | 1.46 ms: 1.04x slower                                                      |
| logging_format           | 7.37 us                                                      | 7.67 us: 1.04x slower                                                      |
| sqlglot_transpile        | 1.80 ms                                                      | 1.88 ms: 1.04x slower                                                      |
| docutils                 | 2.89 sec                                                     | 3.01 sec: 1.04x slower                                                     |
| sqlglot_optimize         | 57.8 ms                                                      | 60.3 ms: 1.04x slower                                                      |
| pycparser                | 1.27 sec                                                     | 1.33 sec: 1.04x slower                                                     |
| logging_simple           | 6.73 us                                                      | 7.07 us: 1.05x slower                                                      |
| mypy2                    | 368 ms                                                       | 388 ms: 1.05x slower                                                       |
| async_tree_io            | 1.06 sec                                                     | 1.12 sec: 1.06x slower                                                     |
| logging_silent           | 95.6 ns                                                      | 101 ns: 1.06x slower                                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 76.9 ms: 1.06x slower                                                      |
| mdp                      | 2.53 sec                                                     | 2.71 sec: 1.07x slower                                                     |
| scimark_lu               | 101 ms                                                       | 108 ms: 1.07x slower                                                       |
| typing_runtime_protocols | 151 us                                                       | 162 us: 1.07x slower                                                       |
| pprint_safe_repr         | 823 ms                                                       | 883 ms: 1.07x slower                                                       |
| pprint_pformat           | 1.67 sec                                                     | 1.80 sec: 1.08x slower                                                     |
| python_startup           | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                      |
| meteor_contest           | 128 ms                                                       | 138 ms: 1.08x slower                                                       |
| xml_etree_iterparse      | 103 ms                                                       | 112 ms: 1.08x slower                                                       |
| dulwich_log              | 65.3 ms                                                      | 73.4 ms: 1.12x slower                                                      |
| gc_traversal             | 3.54 ms                                                      | 4.04 ms: 1.14x slower                                                      |
| unpickle_pure_python     | 207 us                                                       | 239 us: 1.15x slower                                                       |
| chaos                    | 62.9 ms                                                      | 73.2 ms: 1.16x slower                                                      |
| deepcopy_memo            | 37.4 us                                                      | 43.6 us: 1.17x slower                                                      |
| telco                    | 6.96 ms                                                      | 8.36 ms: 1.20x slower                                                      |
| richards_super           | 51.7 ms                                                      | 62.1 ms: 1.20x slower                                                      |
| tomli_loads              | 2.20 sec                                                     | 2.65 sec: 1.21x slower                                                     |
| nbody                    | 94.1 ms                                                      | 114 ms: 1.21x slower                                                       |
| nqueens                  | 90.1 ms                                                      | 110 ms: 1.22x slower                                                       |
| regex_compile            | 146 ms                                                       | 178 ms: 1.22x slower                                                       |
| richards                 | 45.0 ms                                                      | 55.3 ms: 1.23x slower                                                      |
| go                       | 150 ms                                                       | 186 ms: 1.24x slower                                                       |
| scimark_fft              | 304 ms                                                       | 382 ms: 1.26x slower                                                       |
| pyflate                  | 447 ms                                                       | 567 ms: 1.27x slower                                                       |
| float                    | 78.5 ms                                                      | 104 ms: 1.32x slower                                                       |
| scimark_sor              | 110 ms                                                       | 148 ms: 1.34x slower                                                       |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 5.95 ms: 1.34x slower                                                      |
| fannkuch                 | 350 ms                                                       | 473 ms: 1.35x slower                                                       |
| mako                     | 9.94 ms                                                      | 13.7 ms: 1.38x slower                                                      |
| comprehensions           | 21.9 us                                                      | 30.4 us: 1.39x slower                                                      |
| deltablue                | 3.29 ms                                                      | 5.15 ms: 1.57x slower                                                      |
| hexiom                   | 5.96 ms                                                      | 9.72 ms: 1.63x slower                                                      |
| Geometric mean           | (ref)                                                        | 1.08x slower                                                               |

Benchmark hidden because not significant (6): async_tree_none, pickle_pure_python, pickle, coroutines, bench_thread_pool, json
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
