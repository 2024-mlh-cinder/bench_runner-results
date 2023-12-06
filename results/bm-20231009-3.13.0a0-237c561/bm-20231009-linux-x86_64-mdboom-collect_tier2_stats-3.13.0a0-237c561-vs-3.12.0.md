
# Results vs. 3.12.0

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 237c561
- commit date: 2023-10-09
- overall geometric mean: 1.08x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.77 sec: 1.02x slower                                               |
| tornado_http   | 99.6 ms                                                | 102 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                 |
| float          | 80.7 ms                                                | 95.1 ms: 1.18x slower                                                |
| nbody          | 88.8 ms                                                | 114 ms: 1.28x slower                                                 |
| Geometric mean | (ref)                                                  | 1.15x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.58 ms: 1.01x slower                                                |
| regex_v8       | 22.3 ms                                                | 24.9 ms: 1.11x slower                                                |
| regex_compile  | 144 ms                                                 | 162 ms: 1.13x slower                                                 |
| Geometric mean | (ref)                                                  | 1.06x slower                                                         |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 15.2 us: 1.01x slower                                                |
| pickle               | 10.6 us                                                | 10.9 us: 1.03x slower                                                |
| xml_etree_parse      | 154 ms                                                 | 159 ms: 1.03x slower                                                 |
| xml_etree_process    | 58.6 ms                                                | 60.6 ms: 1.03x slower                                                |
| xml_etree_generate   | 84.8 ms                                                | 88.6 ms: 1.04x slower                                                |
| unpickle_list        | 4.95 us                                                | 5.21 us: 1.05x slower                                                |
| json_dumps           | 9.85 ms                                                | 10.5 ms: 1.06x slower                                                |
| xml_etree_iterparse  | 104 ms                                                 | 110 ms: 1.06x slower                                                 |
| pickle_list          | 4.62 us                                                | 4.97 us: 1.08x slower                                                |
| tomli_loads          | 2.22 sec                                               | 2.41 sec: 1.09x slower                                               |
| pickle_dict          | 31.6 us                                                | 34.4 us: 1.09x slower                                                |
| unpickle_pure_python | 218 us                                                 | 240 us: 1.10x slower                                                 |
| json_loads           | 25.2 us                                                | 28.2 us: 1.12x slower                                                |
| Geometric mean       | (ref)                                                  | 1.06x slower                                                         |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 13.4 ms: 1.25x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 472 ms: 1.11x faster                                                 |
| async_tree_none          | 469 ms                                                 | 451 ms: 1.04x faster                                                 |
| coverage                 | 94.2 ms                                                | 90.8 ms: 1.04x faster                                                |
| generators               | 31.1 ms                                                | 30.7 ms: 1.01x faster                                                |
| python_startup_no_site   | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                               |
| create_gc_cycles         | 1.52 ms                                                | 1.53 ms: 1.00x slower                                                |
| regex_effbot             | 3.55 ms                                                | 3.58 ms: 1.01x slower                                                |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                 |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                                 |
| async_tree_memoization   | 573 ms                                                 | 580 ms: 1.01x slower                                                 |
| unpickle                 | 15.0 us                                                | 15.2 us: 1.01x slower                                                |
| deepcopy_reduce          | 3.14 us                                                | 3.19 us: 1.02x slower                                                |
| deepcopy                 | 355 us                                                 | 361 us: 1.02x slower                                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.67 ms: 1.02x slower                                                |
| sqlglot_parse            | 1.32 ms                                                | 1.35 ms: 1.02x slower                                                |
| bench_thread_pool        | 827 us                                                 | 845 us: 1.02x slower                                                 |
| docutils                 | 2.70 sec                                               | 2.77 sec: 1.02x slower                                               |
| sqlite_synth             | 2.76 us                                                | 2.83 us: 1.03x slower                                                |
| tornado_http             | 99.6 ms                                                | 102 ms: 1.03x slower                                                 |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 737 ms: 1.03x slower                                                 |
| pickle                   | 10.6 us                                                | 10.9 us: 1.03x slower                                                |
| sqlglot_optimize         | 53.3 ms                                                | 55.1 ms: 1.03x slower                                                |
| xml_etree_parse          | 154 ms                                                 | 159 ms: 1.03x slower                                                 |
| xml_etree_process        | 58.6 ms                                                | 60.6 ms: 1.03x slower                                                |
| dulwich_log              | 67.9 ms                                                | 70.3 ms: 1.04x slower                                                |
| scimark_sor              | 125 ms                                                 | 129 ms: 1.04x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.04x slower                                               |
| coroutines               | 22.4 ms                                                | 23.4 ms: 1.04x slower                                                |
| mypy2                    | 344 ms                                                 | 358 ms: 1.04x slower                                                 |
| logging_simple           | 6.18 us                                                | 6.45 us: 1.04x slower                                                |
| xml_etree_generate       | 84.8 ms                                                | 88.6 ms: 1.04x slower                                                |
| pycparser                | 1.15 sec                                               | 1.20 sec: 1.05x slower                                               |
| raytrace                 | 294 ms                                                 | 310 ms: 1.05x slower                                                 |
| unpickle_list            | 4.95 us                                                | 5.21 us: 1.05x slower                                                |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                |
| logging_format           | 6.90 us                                                | 7.33 us: 1.06x slower                                                |
| json_dumps               | 9.85 ms                                                | 10.5 ms: 1.06x slower                                                |
| xml_etree_iterparse      | 104 ms                                                 | 110 ms: 1.06x slower                                                 |
| mdp                      | 2.57 sec                                               | 2.74 sec: 1.07x slower                                               |
| scimark_lu               | 114 ms                                                 | 122 ms: 1.07x slower                                                 |
| pathlib                  | 18.5 ms                                                | 19.8 ms: 1.07x slower                                                |
| pickle_list              | 4.62 us                                                | 4.97 us: 1.08x slower                                                |
| json                     | 4.77 ms                                                | 5.14 ms: 1.08x slower                                                |
| scimark_monte_carlo      | 71.0 ms                                                | 76.7 ms: 1.08x slower                                                |
| spectral_norm            | 106 ms                                                 | 115 ms: 1.08x slower                                                 |
| tomli_loads              | 2.22 sec                                               | 2.41 sec: 1.09x slower                                               |
| crypto_pyaes             | 77.2 ms                                                | 84.0 ms: 1.09x slower                                                |
| pickle_dict              | 31.6 us                                                | 34.4 us: 1.09x slower                                                |
| typing_runtime_protocols | 146 us                                                 | 159 us: 1.09x slower                                                 |
| async_generators         | 440 ms                                                 | 484 ms: 1.10x slower                                                 |
| unpickle_pure_python     | 218 us                                                 | 240 us: 1.10x slower                                                 |
| pprint_safe_repr         | 735 ms                                                 | 809 ms: 1.10x slower                                                 |
| logging_silent           | 99.1 ns                                                | 109 ns: 1.10x slower                                                 |
| meteor_contest           | 105 ms                                                 | 116 ms: 1.11x slower                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.67 sec: 1.11x slower                                               |
| regex_v8                 | 22.3 ms                                                | 24.9 ms: 1.11x slower                                                |
| json_loads               | 25.2 us                                                | 28.2 us: 1.12x slower                                                |
| regex_compile            | 144 ms                                                 | 162 ms: 1.13x slower                                                 |
| deepcopy_memo            | 37.4 us                                                | 42.2 us: 1.13x slower                                                |
| unpack_sequence          | 44.8 ns                                                | 50.6 ns: 1.13x slower                                                |
| gc_traversal             | 3.84 ms                                                | 4.35 ms: 1.13x slower                                                |
| richards                 | 43.2 ms                                                | 49.9 ms: 1.16x slower                                                |
| richards_super           | 49.0 ms                                                | 56.7 ms: 1.16x slower                                                |
| fannkuch                 | 387 ms                                                 | 449 ms: 1.16x slower                                                 |
| pyflate                  | 450 ms                                                 | 526 ms: 1.17x slower                                                 |
| chaos                    | 63.5 ms                                                | 74.2 ms: 1.17x slower                                                |
| float                    | 80.7 ms                                                | 95.1 ms: 1.18x slower                                                |
| scimark_fft              | 358 ms                                                 | 427 ms: 1.19x slower                                                 |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.81 ms: 1.23x slower                                                |
| nqueens                  | 81.1 ms                                                | 100 ms: 1.23x slower                                                 |
| go                       | 136 ms                                                 | 169 ms: 1.24x slower                                                 |
| mako                     | 10.7 ms                                                | 13.4 ms: 1.25x slower                                                |
| telco                    | 6.87 ms                                                | 8.69 ms: 1.26x slower                                                |
| nbody                    | 88.8 ms                                                | 114 ms: 1.28x slower                                                 |
| comprehensions           | 20.4 us                                                | 26.9 us: 1.31x slower                                                |
| deltablue                | 3.52 ms                                                | 4.80 ms: 1.36x slower                                                |
| hexiom                   | 6.12 ms                                                | 9.04 ms: 1.48x slower                                                |
| Geometric mean           | (ref)                                                  | 1.08x slower                                                         |

Benchmark hidden because not significant (3): regex_dna, bench_mp_pool, pickle_pure_python
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.04x
