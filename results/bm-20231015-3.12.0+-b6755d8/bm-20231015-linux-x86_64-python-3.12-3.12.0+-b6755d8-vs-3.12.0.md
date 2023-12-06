
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: b6755d8
- commit date: 2023-10-15
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 268 ms                                                 | 276 ms: 1.03x slower                                 |
| docutils       | 2.70 sec                                               | 2.78 sec: 1.03x slower                               |
| tornado_http   | 99.6 ms                                                | 107 ms: 1.08x slower                                 |
| Geometric mean | (ref)                                                  | 1.05x slower                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                 |
| float          | 80.7 ms                                                | 83.7 ms: 1.04x slower                                |
| nbody          | 88.8 ms                                                | 93.9 ms: 1.06x slower                                |
| Geometric mean | (ref)                                                  | 1.03x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.63 ms: 1.02x slower                                |
| regex_compile  | 144 ms                                                 | 148 ms: 1.03x slower                                 |
| regex_v8       | 22.3 ms                                                | 23.1 ms: 1.03x slower                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                         |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.23 sec: 1.00x slower                               |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.03x slower                                 |
| xml_etree_process    | 58.6 ms                                                | 61.0 ms: 1.04x slower                                |
| xml_etree_generate   | 84.8 ms                                                | 88.8 ms: 1.05x slower                                |
| xml_etree_parse      | 154 ms                                                 | 162 ms: 1.05x slower                                 |
| unpickle_pure_python | 218 us                                                 | 230 us: 1.05x slower                                 |
| pickle_pure_python   | 309 us                                                 | 325 us: 1.05x slower                                 |
| unpickle_list        | 4.95 us                                                | 5.21 us: 1.05x slower                                |
| unpickle             | 15.0 us                                                | 15.9 us: 1.06x slower                                |
| json_dumps           | 9.85 ms                                                | 10.5 ms: 1.07x slower                                |
| pickle               | 10.6 us                                                | 11.4 us: 1.07x slower                                |
| pickle_list          | 4.62 us                                                | 5.09 us: 1.10x slower                                |
| pickle_dict          | 31.6 us                                                | 35.1 us: 1.11x slower                                |
| json_loads           | 25.2 us                                                | 28.5 us: 1.13x slower                                |
| Geometric mean       | (ref)                                                  | 1.06x slower                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 7.00 ms: 1.02x slower                                |
| python_startup         | 9.47 ms                                                | 9.70 ms: 1.02x slower                                |
| Geometric mean         | (ref)                                                  | 1.02x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.3 ms: 1.05x slower                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231015-linux-x86_64-python-3.12-3.12.0+-b6755d8 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 509 ms: 1.03x faster                                 |
| create_gc_cycles         | 1.52 ms                                                | 1.49 ms: 1.02x faster                                |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                               |
| mdp                      | 2.57 sec                                               | 2.57 sec: 1.00x slower                               |
| tomli_loads              | 2.22 sec                                               | 2.23 sec: 1.00x slower                               |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                 |
| generators               | 31.1 ms                                                | 31.5 ms: 1.01x slower                                |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 725 ms: 1.01x slower                                 |
| python_startup_no_site   | 6.90 ms                                                | 7.00 ms: 1.02x slower                                |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.02x slower                                |
| pyflate                  | 450 ms                                                 | 458 ms: 1.02x slower                                 |
| telco                    | 6.87 ms                                                | 7.03 ms: 1.02x slower                                |
| regex_effbot             | 3.55 ms                                                | 3.63 ms: 1.02x slower                                |
| python_startup           | 9.47 ms                                                | 9.70 ms: 1.02x slower                                |
| fannkuch                 | 387 ms                                                 | 397 ms: 1.02x slower                                 |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.03x slower                                 |
| pycparser                | 1.15 sec                                               | 1.18 sec: 1.03x slower                               |
| regex_compile            | 144 ms                                                 | 148 ms: 1.03x slower                                 |
| docutils                 | 2.70 sec                                               | 2.78 sec: 1.03x slower                               |
| meteor_contest           | 105 ms                                                 | 108 ms: 1.03x slower                                 |
| sqlalchemy_declarative   | 144 ms                                                 | 148 ms: 1.03x slower                                 |
| dask                     | 365 ms                                                 | 375 ms: 1.03x slower                                 |
| bench_thread_pool        | 827 us                                                 | 852 us: 1.03x slower                                 |
| scimark_fft              | 358 ms                                                 | 370 ms: 1.03x slower                                 |
| regex_v8                 | 22.3 ms                                                | 23.1 ms: 1.03x slower                                |
| 2to3                     | 268 ms                                                 | 276 ms: 1.03x slower                                 |
| nqueens                  | 81.1 ms                                                | 83.8 ms: 1.03x slower                                |
| scimark_monte_carlo      | 71.0 ms                                                | 73.4 ms: 1.03x slower                                |
| scimark_lu               | 114 ms                                                 | 118 ms: 1.03x slower                                 |
| pprint_pformat           | 1.50 sec                                               | 1.55 sec: 1.03x slower                               |
| sqlglot_optimize         | 53.3 ms                                                | 55.1 ms: 1.03x slower                                |
| float                    | 80.7 ms                                                | 83.7 ms: 1.04x slower                                |
| richards_super           | 49.0 ms                                                | 51.0 ms: 1.04x slower                                |
| pprint_safe_repr         | 735 ms                                                 | 765 ms: 1.04x slower                                 |
| xml_etree_process        | 58.6 ms                                                | 61.0 ms: 1.04x slower                                |
| sqlglot_normalize        | 107 ms                                                 | 112 ms: 1.04x slower                                 |
| richards                 | 43.2 ms                                                | 45.0 ms: 1.04x slower                                |
| deltablue                | 3.52 ms                                                | 3.68 ms: 1.05x slower                                |
| coverage                 | 94.2 ms                                                | 98.5 ms: 1.05x slower                                |
| xml_etree_generate       | 84.8 ms                                                | 88.8 ms: 1.05x slower                                |
| scimark_sor              | 125 ms                                                 | 130 ms: 1.05x slower                                 |
| sqlite_synth             | 2.76 us                                                | 2.89 us: 1.05x slower                                |
| deepcopy                 | 355 us                                                 | 372 us: 1.05x slower                                 |
| chaos                    | 63.5 ms                                                | 66.6 ms: 1.05x slower                                |
| async_generators         | 440 ms                                                 | 462 ms: 1.05x slower                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.72 ms: 1.05x slower                                |
| sqlglot_parse            | 1.32 ms                                                | 1.39 ms: 1.05x slower                                |
| comprehensions           | 20.4 us                                                | 21.5 us: 1.05x slower                                |
| spectral_norm            | 106 ms                                                 | 112 ms: 1.05x slower                                 |
| xml_etree_parse          | 154 ms                                                 | 162 ms: 1.05x slower                                 |
| unpickle_pure_python     | 218 us                                                 | 230 us: 1.05x slower                                 |
| mako                     | 10.7 ms                                                | 11.3 ms: 1.05x slower                                |
| go                       | 136 ms                                                 | 143 ms: 1.05x slower                                 |
| pickle_pure_python       | 309 us                                                 | 325 us: 1.05x slower                                 |
| raytrace                 | 294 ms                                                 | 310 ms: 1.05x slower                                 |
| unpickle_list            | 4.95 us                                                | 5.21 us: 1.05x slower                                |
| nbody                    | 88.8 ms                                                | 93.9 ms: 1.06x slower                                |
| logging_format           | 6.90 us                                                | 7.30 us: 1.06x slower                                |
| deepcopy_reduce          | 3.14 us                                                | 3.32 us: 1.06x slower                                |
| logging_simple           | 6.18 us                                                | 6.54 us: 1.06x slower                                |
| hexiom                   | 6.12 ms                                                | 6.49 ms: 1.06x slower                                |
| unpickle                 | 15.0 us                                                | 15.9 us: 1.06x slower                                |
| json_dumps               | 9.85 ms                                                | 10.5 ms: 1.07x slower                                |
| gc_traversal             | 3.84 ms                                                | 4.11 ms: 1.07x slower                                |
| crypto_pyaes             | 77.2 ms                                                | 82.8 ms: 1.07x slower                                |
| typing_runtime_protocols | 146 us                                                 | 157 us: 1.07x slower                                 |
| pickle                   | 10.6 us                                                | 11.4 us: 1.07x slower                                |
| tornado_http             | 99.6 ms                                                | 107 ms: 1.08x slower                                 |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.17 ms: 1.09x slower                                |
| deepcopy_memo            | 37.4 us                                                | 40.8 us: 1.09x slower                                |
| dulwich_log              | 67.9 ms                                                | 74.4 ms: 1.10x slower                                |
| logging_silent           | 99.1 ns                                                | 109 ns: 1.10x slower                                 |
| pickle_list              | 4.62 us                                                | 5.09 us: 1.10x slower                                |
| json                     | 4.77 ms                                                | 5.28 ms: 1.11x slower                                |
| pickle_dict              | 31.6 us                                                | 35.1 us: 1.11x slower                                |
| json_loads               | 25.2 us                                                | 28.5 us: 1.13x slower                                |
| sqlalchemy_imperative    | 18.4 ms                                                | 20.9 ms: 1.13x slower                                |
| unpack_sequence          | 44.8 ns                                                | 53.3 ns: 1.19x slower                                |
| mypy2                    | 344 ms                                                 | 470 ms: 1.37x slower                                 |
| Geometric mean           | (ref)                                                  | 1.05x slower                                         |

Benchmark hidden because not significant (6): bench_mp_pool, async_tree_io, coroutines, regex_dna, async_tree_none, async_tree_memoization


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
