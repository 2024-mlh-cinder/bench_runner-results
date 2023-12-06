
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: ef4bd1b
- commit date: 2023-10-08
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 268 ms                                                 | 275 ms: 1.03x slower                                 |
| docutils       | 2.70 sec                                               | 2.75 sec: 1.02x slower                               |
| tornado_http   | 99.6 ms                                                | 103 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                 |
| float          | 80.7 ms                                                | 83.5 ms: 1.03x slower                                |
| nbody          | 88.8 ms                                                | 95.1 ms: 1.07x slower                                |
| Geometric mean | (ref)                                                  | 1.04x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_v8       | 22.3 ms                                                | 22.3 ms: 1.00x faster                                |
| regex_compile  | 144 ms                                                 | 149 ms: 1.04x slower                                 |
| regex_effbot   | 3.55 ms                                                | 3.68 ms: 1.04x slower                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                         |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| xml_etree_iterparse  | 104 ms                                                 | 107 ms: 1.03x slower                                 |
| pickle_dict          | 31.6 us                                                | 32.7 us: 1.03x slower                                |
| xml_etree_parse      | 154 ms                                                 | 161 ms: 1.05x slower                                 |
| tomli_loads          | 2.22 sec                                               | 2.32 sec: 1.05x slower                               |
| pickle_pure_python   | 309 us                                                 | 325 us: 1.05x slower                                 |
| xml_etree_generate   | 84.8 ms                                                | 89.1 ms: 1.05x slower                                |
| pickle_list          | 4.62 us                                                | 4.86 us: 1.05x slower                                |
| unpickle             | 15.0 us                                                | 15.8 us: 1.05x slower                                |
| unpickle_pure_python | 218 us                                                 | 231 us: 1.06x slower                                 |
| xml_etree_process    | 58.6 ms                                                | 62.0 ms: 1.06x slower                                |
| pickle               | 10.6 us                                                | 11.4 us: 1.08x slower                                |
| json_dumps           | 9.85 ms                                                | 10.6 ms: 1.08x slower                                |
| json_loads           | 25.2 us                                                | 28.5 us: 1.13x slower                                |
| unpickle_list        | 4.95 us                                                | 5.68 us: 1.15x slower                                |
| Geometric mean       | (ref)                                                  | 1.06x slower                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.92 ms: 1.00x slower                                |
| python_startup         | 9.47 ms                                                | 9.54 ms: 1.01x slower                                |
| Geometric mean         | (ref)                                                  | 1.01x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.7 ms: 1.09x slower                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-linux-x86_64-python-3.12-3.12.0+-ef4bd1b |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 501 ms: 1.05x faster                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                               |
| regex_v8                 | 22.3 ms                                                | 22.3 ms: 1.00x faster                                |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                |
| python_startup_no_site   | 6.90 ms                                                | 6.92 ms: 1.00x slower                                |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                 |
| python_startup           | 9.47 ms                                                | 9.54 ms: 1.01x slower                                |
| async_tree_io            | 1.16 sec                                               | 1.17 sec: 1.01x slower                               |
| generators               | 31.1 ms                                                | 31.4 ms: 1.01x slower                                |
| bench_thread_pool        | 827 us                                                 | 838 us: 1.01x slower                                 |
| mdp                      | 2.57 sec                                               | 2.61 sec: 1.02x slower                               |
| sqlalchemy_declarative   | 144 ms                                                 | 146 ms: 1.02x slower                                 |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 727 ms: 1.02x slower                                 |
| async_tree_none          | 469 ms                                                 | 478 ms: 1.02x slower                                 |
| async_tree_memoization   | 573 ms                                                 | 583 ms: 1.02x slower                                 |
| docutils                 | 2.70 sec                                               | 2.75 sec: 1.02x slower                               |
| dulwich_log              | 67.9 ms                                                | 69.2 ms: 1.02x slower                                |
| sqlalchemy_imperative    | 18.4 ms                                                | 18.8 ms: 1.02x slower                                |
| dask                     | 365 ms                                                 | 373 ms: 1.02x slower                                 |
| 2to3                     | 268 ms                                                 | 275 ms: 1.03x slower                                 |
| sqlglot_optimize         | 53.3 ms                                                | 54.9 ms: 1.03x slower                                |
| pprint_pformat           | 1.50 sec                                               | 1.55 sec: 1.03x slower                               |
| sqlglot_normalize        | 107 ms                                                 | 110 ms: 1.03x slower                                 |
| pprint_safe_repr         | 735 ms                                                 | 758 ms: 1.03x slower                                 |
| nqueens                  | 81.1 ms                                                | 83.7 ms: 1.03x slower                                |
| sqlglot_parse            | 1.32 ms                                                | 1.36 ms: 1.03x slower                                |
| xml_etree_iterparse      | 104 ms                                                 | 107 ms: 1.03x slower                                 |
| pickle_dict              | 31.6 us                                                | 32.7 us: 1.03x slower                                |
| float                    | 80.7 ms                                                | 83.5 ms: 1.03x slower                                |
| tornado_http             | 99.6 ms                                                | 103 ms: 1.03x slower                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.70 ms: 1.04x slower                                |
| coroutines               | 22.4 ms                                                | 23.3 ms: 1.04x slower                                |
| go                       | 136 ms                                                 | 140 ms: 1.04x slower                                 |
| regex_compile            | 144 ms                                                 | 149 ms: 1.04x slower                                 |
| logging_simple           | 6.18 us                                                | 6.41 us: 1.04x slower                                |
| regex_effbot             | 3.55 ms                                                | 3.68 ms: 1.04x slower                                |
| logging_format           | 6.90 us                                                | 7.18 us: 1.04x slower                                |
| sqlite_synth             | 2.76 us                                                | 2.87 us: 1.04x slower                                |
| telco                    | 6.87 ms                                                | 7.15 ms: 1.04x slower                                |
| richards_super           | 49.0 ms                                                | 51.1 ms: 1.04x slower                                |
| richards                 | 43.2 ms                                                | 45.0 ms: 1.04x slower                                |
| coverage                 | 94.2 ms                                                | 98.4 ms: 1.04x slower                                |
| deepcopy                 | 355 us                                                 | 372 us: 1.05x slower                                 |
| xml_etree_parse          | 154 ms                                                 | 161 ms: 1.05x slower                                 |
| tomli_loads              | 2.22 sec                                               | 2.32 sec: 1.05x slower                               |
| pickle_pure_python       | 309 us                                                 | 325 us: 1.05x slower                                 |
| xml_etree_generate       | 84.8 ms                                                | 89.1 ms: 1.05x slower                                |
| chaos                    | 63.5 ms                                                | 66.8 ms: 1.05x slower                                |
| deltablue                | 3.52 ms                                                | 3.70 ms: 1.05x slower                                |
| pickle_list              | 4.62 us                                                | 4.86 us: 1.05x slower                                |
| unpickle                 | 15.0 us                                                | 15.8 us: 1.05x slower                                |
| raytrace                 | 294 ms                                                 | 310 ms: 1.05x slower                                 |
| scimark_fft              | 358 ms                                                 | 378 ms: 1.05x slower                                 |
| unpickle_pure_python     | 218 us                                                 | 231 us: 1.06x slower                                 |
| crypto_pyaes             | 77.2 ms                                                | 81.7 ms: 1.06x slower                                |
| scimark_sor              | 125 ms                                                 | 132 ms: 1.06x slower                                 |
| xml_etree_process        | 58.6 ms                                                | 62.0 ms: 1.06x slower                                |
| deepcopy_reduce          | 3.14 us                                                | 3.32 us: 1.06x slower                                |
| meteor_contest           | 105 ms                                                 | 111 ms: 1.06x slower                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 75.5 ms: 1.06x slower                                |
| pycparser                | 1.15 sec                                               | 1.22 sec: 1.06x slower                               |
| async_generators         | 440 ms                                                 | 468 ms: 1.06x slower                                 |
| scimark_lu               | 114 ms                                                 | 121 ms: 1.06x slower                                 |
| typing_runtime_protocols | 146 us                                                 | 156 us: 1.07x slower                                 |
| spectral_norm            | 106 ms                                                 | 113 ms: 1.07x slower                                 |
| hexiom                   | 6.12 ms                                                | 6.54 ms: 1.07x slower                                |
| nbody                    | 88.8 ms                                                | 95.1 ms: 1.07x slower                                |
| comprehensions           | 20.4 us                                                | 21.9 us: 1.07x slower                                |
| logging_silent           | 99.1 ns                                                | 107 ns: 1.08x slower                                 |
| pickle                   | 10.6 us                                                | 11.4 us: 1.08x slower                                |
| json_dumps               | 9.85 ms                                                | 10.6 ms: 1.08x slower                                |
| unpack_sequence          | 44.8 ns                                                | 48.6 ns: 1.08x slower                                |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.15 ms: 1.09x slower                                |
| pyflate                  | 450 ms                                                 | 489 ms: 1.09x slower                                 |
| deepcopy_memo            | 37.4 us                                                | 40.7 us: 1.09x slower                                |
| fannkuch                 | 387 ms                                                 | 423 ms: 1.09x slower                                 |
| mako                     | 10.7 ms                                                | 11.7 ms: 1.09x slower                                |
| json                     | 4.77 ms                                                | 5.28 ms: 1.11x slower                                |
| json_loads               | 25.2 us                                                | 28.5 us: 1.13x slower                                |
| unpickle_list            | 4.95 us                                                | 5.68 us: 1.15x slower                                |
| mypy2                    | 344 ms                                                 | 465 ms: 1.35x slower                                 |
| Geometric mean           | (ref)                                                  | 1.05x slower                                         |

Benchmark hidden because not significant (4): create_gc_cycles, pathlib, bench_mp_pool, regex_dna


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
