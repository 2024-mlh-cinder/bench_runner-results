
# Results vs. 3.12.0

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 9e1c90d
- commit date: 2023-10-03
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.99 sec: 1.04x slower                                                     |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                        | 1.03x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                                       |
| float          | 78.5 ms                                                      | 83.3 ms: 1.06x slower                                                      |
| nbody          | 94.1 ms                                                      | 102 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                        | 1.05x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 242 ms: 1.00x slower                                                       |
| regex_v8       | 25.0 ms                                                      | 25.6 ms: 1.03x slower                                                      |
| regex_effbot   | 3.47 ms                                                      | 3.61 ms: 1.04x slower                                                      |
| regex_compile  | 146 ms                                                       | 172 ms: 1.18x slower                                                       |
| Geometric mean | (ref)                                                        | 1.06x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.5 us: 1.02x faster                                                      |
| pickle_list          | 4.39 us                                                      | 4.32 us: 1.02x faster                                                      |
| unpickle_list        | 4.77 us                                                      | 4.70 us: 1.01x faster                                                      |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                      |
| pickle_dict          | 31.7 us                                                      | 32.2 us: 1.02x slower                                                      |
| json_loads           | 24.3 us                                                      | 24.6 us: 1.02x slower                                                      |
| xml_etree_generate   | 86.1 ms                                                      | 87.7 ms: 1.02x slower                                                      |
| xml_etree_process    | 58.3 ms                                                      | 59.8 ms: 1.03x slower                                                      |
| json_dumps           | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                                      |
| xml_etree_parse      | 146 ms                                                       | 153 ms: 1.05x slower                                                       |
| xml_etree_iterparse  | 103 ms                                                       | 109 ms: 1.05x slower                                                       |
| unpickle_pure_python | 207 us                                                       | 239 us: 1.16x slower                                                       |
| tomli_loads          | 2.20 sec                                                     | 2.71 sec: 1.23x slower                                                     |
| Geometric mean       | (ref)                                                        | 1.04x slower                                                               |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.65 ms: 1.01x faster                                                      |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.07x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.03x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 11.5 ms: 1.16x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.69 ms: 1.14x faster                                                      |
| coverage                 | 89.6 ms                                                      | 82.5 ms: 1.09x faster                                                      |
| raytrace                 | 302 ms                                                       | 280 ms: 1.08x faster                                                       |
| crypto_pyaes             | 80.9 ms                                                      | 75.8 ms: 1.07x faster                                                      |
| scimark_monte_carlo      | 72.4 ms                                                      | 68.0 ms: 1.06x faster                                                      |
| async_tree_none          | 459 ms                                                       | 444 ms: 1.03x faster                                                       |
| unpickle                 | 14.8 us                                                      | 14.5 us: 1.02x faster                                                      |
| asyncio_tcp              | 381 ms                                                       | 373 ms: 1.02x faster                                                       |
| generators               | 36.7 ms                                                      | 36.0 ms: 1.02x faster                                                      |
| unpack_sequence          | 53.3 ns                                                      | 52.5 ns: 1.02x faster                                                      |
| pickle_list              | 4.39 us                                                      | 4.32 us: 1.02x faster                                                      |
| unpickle_list            | 4.77 us                                                      | 4.70 us: 1.01x faster                                                      |
| python_startup_no_site   | 8.70 ms                                                      | 8.65 ms: 1.01x faster                                                      |
| sqlite_synth             | 2.70 us                                                      | 2.68 us: 1.00x faster                                                      |
| pidigits                 | 264 ms                                                       | 264 ms: 1.00x slower                                                       |
| regex_dna                | 241 ms                                                       | 242 ms: 1.00x slower                                                       |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.59 sec: 1.01x slower                                                     |
| sqlglot_normalize        | 117 ms                                                       | 118 ms: 1.01x slower                                                       |
| gc_traversal             | 3.54 ms                                                      | 3.58 ms: 1.01x slower                                                      |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                      |
| pickle_dict              | 31.7 us                                                      | 32.2 us: 1.02x slower                                                      |
| json_loads               | 24.3 us                                                      | 24.6 us: 1.02x slower                                                      |
| tornado_http             | 122 ms                                                       | 124 ms: 1.02x slower                                                       |
| xml_etree_generate       | 86.1 ms                                                      | 87.7 ms: 1.02x slower                                                      |
| pprint_safe_repr         | 823 ms                                                       | 840 ms: 1.02x slower                                                       |
| sqlglot_parse            | 1.40 ms                                                      | 1.43 ms: 1.02x slower                                                      |
| pathlib                  | 19.8 ms                                                      | 20.2 ms: 1.02x slower                                                      |
| regex_v8                 | 25.0 ms                                                      | 25.6 ms: 1.03x slower                                                      |
| xml_etree_process        | 58.3 ms                                                      | 59.8 ms: 1.03x slower                                                      |
| pprint_pformat           | 1.67 sec                                                     | 1.72 sec: 1.03x slower                                                     |
| sqlglot_transpile        | 1.80 ms                                                      | 1.85 ms: 1.03x slower                                                      |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                                     |
| docutils                 | 2.89 sec                                                     | 2.99 sec: 1.04x slower                                                     |
| sqlglot_optimize         | 57.8 ms                                                      | 59.9 ms: 1.04x slower                                                      |
| json_dumps               | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                                      |
| regex_effbot             | 3.47 ms                                                      | 3.61 ms: 1.04x slower                                                      |
| logging_format           | 7.37 us                                                      | 7.68 us: 1.04x slower                                                      |
| logging_silent           | 95.6 ns                                                      | 99.8 ns: 1.04x slower                                                      |
| async_generators         | 385 ms                                                       | 402 ms: 1.04x slower                                                       |
| deepcopy                 | 376 us                                                       | 393 us: 1.05x slower                                                       |
| xml_etree_parse          | 146 ms                                                       | 153 ms: 1.05x slower                                                       |
| logging_simple           | 6.73 us                                                      | 7.05 us: 1.05x slower                                                      |
| mypy2                    | 368 ms                                                       | 387 ms: 1.05x slower                                                       |
| xml_etree_iterparse      | 103 ms                                                       | 109 ms: 1.05x slower                                                       |
| mdp                      | 2.53 sec                                                     | 2.68 sec: 1.06x slower                                                     |
| float                    | 78.5 ms                                                      | 83.3 ms: 1.06x slower                                                      |
| typing_runtime_protocols | 151 us                                                       | 162 us: 1.07x slower                                                       |
| pycparser                | 1.27 sec                                                     | 1.37 sec: 1.07x slower                                                     |
| python_startup           | 11.7 ms                                                      | 12.6 ms: 1.07x slower                                                      |
| meteor_contest           | 128 ms                                                       | 138 ms: 1.08x slower                                                       |
| chaos                    | 62.9 ms                                                      | 68.1 ms: 1.08x slower                                                      |
| nbody                    | 94.1 ms                                                      | 102 ms: 1.08x slower                                                       |
| dulwich_log              | 65.3 ms                                                      | 71.5 ms: 1.09x slower                                                      |
| scimark_lu               | 101 ms                                                       | 111 ms: 1.10x slower                                                       |
| deepcopy_memo            | 37.4 us                                                      | 42.6 us: 1.14x slower                                                      |
| scimark_fft              | 304 ms                                                       | 347 ms: 1.14x slower                                                       |
| unpickle_pure_python     | 207 us                                                       | 239 us: 1.16x slower                                                       |
| mako                     | 9.94 ms                                                      | 11.5 ms: 1.16x slower                                                      |
| telco                    | 6.96 ms                                                      | 8.16 ms: 1.17x slower                                                      |
| regex_compile            | 146 ms                                                       | 172 ms: 1.18x slower                                                       |
| deltablue                | 3.29 ms                                                      | 3.91 ms: 1.19x slower                                                      |
| nqueens                  | 90.1 ms                                                      | 108 ms: 1.20x slower                                                       |
| pyflate                  | 447 ms                                                       | 536 ms: 1.20x slower                                                       |
| go                       | 150 ms                                                       | 182 ms: 1.21x slower                                                       |
| richards_super           | 51.7 ms                                                      | 63.6 ms: 1.23x slower                                                      |
| tomli_loads              | 2.20 sec                                                     | 2.71 sec: 1.23x slower                                                     |
| comprehensions           | 21.9 us                                                      | 27.3 us: 1.25x slower                                                      |
| richards                 | 45.0 ms                                                      | 57.6 ms: 1.28x slower                                                      |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 5.84 ms: 1.32x slower                                                      |
| fannkuch                 | 350 ms                                                       | 465 ms: 1.33x slower                                                       |
| scimark_sor              | 110 ms                                                       | 149 ms: 1.35x slower                                                       |
| hexiom                   | 5.96 ms                                                      | 8.29 ms: 1.39x slower                                                      |
| Geometric mean           | (ref)                                                        | 1.06x slower                                                               |

Benchmark hidden because not significant (9): spectral_norm, async_tree_cpu_io_mixed, pickle_pure_python, deepcopy_reduce, create_gc_cycles, coroutines, json, async_tree_memoization, bench_thread_pool
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
