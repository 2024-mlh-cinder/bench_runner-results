
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.02x slower
- HPT reliability: 97.13%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.64 sec: 1.02x faster                                 |
| tornado_http   | 99.6 ms                                                | 96.1 ms: 1.04x faster                                  |
| Geometric mean | (ref)                                                  | 1.03x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.01x slower                                   |
| float          | 80.7 ms                                                | 82.4 ms: 1.02x slower                                  |
| nbody          | 88.8 ms                                                | 93.7 ms: 1.06x slower                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                   |
| regex_effbot   | 3.55 ms                                                | 3.60 ms: 1.01x slower                                  |
| regex_dna      | 209 ms                                                 | 220 ms: 1.05x slower                                   |
| regex_v8       | 22.3 ms                                                | 25.7 ms: 1.15x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                 |
| pickle_pure_python   | 309 us                                                 | 304 us: 1.02x faster                                   |
| xml_etree_process    | 58.6 ms                                                | 59.2 ms: 1.01x slower                                  |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                   |
| xml_etree_generate   | 84.8 ms                                                | 86.4 ms: 1.02x slower                                  |
| unpickle_pure_python | 218 us                                                 | 224 us: 1.03x slower                                   |
| xml_etree_parse      | 154 ms                                                 | 158 ms: 1.03x slower                                   |
| unpickle_list        | 4.95 us                                                | 5.13 us: 1.04x slower                                  |
| unpickle             | 15.0 us                                                | 15.7 us: 1.05x slower                                  |
| json_dumps           | 9.85 ms                                                | 10.5 ms: 1.06x slower                                  |
| pickle               | 10.6 us                                                | 11.5 us: 1.08x slower                                  |
| pickle_dict          | 31.6 us                                                | 34.7 us: 1.10x slower                                  |
| json_loads           | 25.2 us                                                | 27.9 us: 1.11x slower                                  |
| pickle_list          | 4.62 us                                                | 5.11 us: 1.11x slower                                  |
| Geometric mean       | (ref)                                                  | 1.04x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.85 ms: 1.01x faster                                  |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                  |
| Geometric mean         | (ref)                                                  | 1.03x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.7 ms                                                | 12.0 ms: 1.12x slower                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 473 ms: 1.11x faster                                   |
| async_tree_none          | 469 ms                                                 | 436 ms: 1.08x faster                                   |
| logging_format           | 6.90 us                                                | 6.44 us: 1.07x faster                                  |
| deltablue                | 3.52 ms                                                | 3.31 ms: 1.06x faster                                  |
| raytrace                 | 294 ms                                                 | 278 ms: 1.06x faster                                   |
| generators               | 31.1 ms                                                | 29.4 ms: 1.06x faster                                  |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                   |
| logging_simple           | 6.18 us                                                | 5.91 us: 1.04x faster                                  |
| gc_traversal             | 3.84 ms                                                | 3.69 ms: 1.04x faster                                  |
| coverage                 | 94.2 ms                                                | 90.5 ms: 1.04x faster                                  |
| tornado_http             | 99.6 ms                                                | 96.1 ms: 1.04x faster                                  |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                  |
| chaos                    | 63.5 ms                                                | 61.8 ms: 1.03x faster                                  |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.03x faster                                  |
| crypto_pyaes             | 77.2 ms                                                | 75.3 ms: 1.02x faster                                  |
| bench_thread_pool        | 827 us                                                 | 808 us: 1.02x faster                                   |
| docutils                 | 2.70 sec                                               | 2.64 sec: 1.02x faster                                 |
| async_tree_memoization   | 573 ms                                                 | 561 ms: 1.02x faster                                   |
| scimark_monte_carlo      | 71.0 ms                                                | 69.8 ms: 1.02x faster                                  |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                 |
| pickle_pure_python       | 309 us                                                 | 304 us: 1.02x faster                                   |
| nqueens                  | 81.1 ms                                                | 79.9 ms: 1.02x faster                                  |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.77 sec: 1.01x faster                                 |
| dulwich_log              | 67.9 ms                                                | 67.1 ms: 1.01x faster                                  |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                  |
| python_startup_no_site   | 6.90 ms                                                | 6.85 ms: 1.01x faster                                  |
| deepcopy                 | 355 us                                                 | 354 us: 1.00x faster                                   |
| mypy2                    | 344 ms                                                 | 342 ms: 1.00x faster                                   |
| pidigits                 | 187 ms                                                 | 187 ms: 1.01x slower                                   |
| sqlglot_optimize         | 53.3 ms                                                | 53.8 ms: 1.01x slower                                  |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.01x slower                                 |
| xml_etree_process        | 58.6 ms                                                | 59.2 ms: 1.01x slower                                  |
| pprint_safe_repr         | 735 ms                                                 | 743 ms: 1.01x slower                                   |
| mdp                      | 2.57 sec                                               | 2.60 sec: 1.01x slower                                 |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                   |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                 |
| regex_effbot             | 3.55 ms                                                | 3.60 ms: 1.01x slower                                  |
| unpack_sequence          | 44.8 ns                                                | 45.5 ns: 1.02x slower                                  |
| async_tree_io            | 1.16 sec                                               | 1.18 sec: 1.02x slower                                 |
| xml_etree_generate       | 84.8 ms                                                | 86.4 ms: 1.02x slower                                  |
| float                    | 80.7 ms                                                | 82.4 ms: 1.02x slower                                  |
| scimark_sor              | 125 ms                                                 | 127 ms: 1.02x slower                                   |
| hexiom                   | 6.12 ms                                                | 6.26 ms: 1.02x slower                                  |
| typing_runtime_protocols | 146 us                                                 | 149 us: 1.02x slower                                   |
| sqlite_synth             | 2.76 us                                                | 2.82 us: 1.02x slower                                  |
| meteor_contest           | 105 ms                                                 | 107 ms: 1.02x slower                                   |
| scimark_lu               | 114 ms                                                 | 117 ms: 1.03x slower                                   |
| unpickle_pure_python     | 218 us                                                 | 224 us: 1.03x slower                                   |
| xml_etree_parse          | 154 ms                                                 | 158 ms: 1.03x slower                                   |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.03x slower                                  |
| coroutines               | 22.4 ms                                                | 23.2 ms: 1.04x slower                                  |
| unpickle_list            | 4.95 us                                                | 5.13 us: 1.04x slower                                  |
| deepcopy_memo            | 37.4 us                                                | 38.9 us: 1.04x slower                                  |
| comprehensions           | 20.4 us                                                | 21.4 us: 1.05x slower                                  |
| async_generators         | 440 ms                                                 | 462 ms: 1.05x slower                                   |
| unpickle                 | 15.0 us                                                | 15.7 us: 1.05x slower                                  |
| scimark_fft              | 358 ms                                                 | 377 ms: 1.05x slower                                   |
| go                       | 136 ms                                                 | 143 ms: 1.05x slower                                   |
| regex_dna                | 209 ms                                                 | 220 ms: 1.05x slower                                   |
| nbody                    | 88.8 ms                                                | 93.7 ms: 1.06x slower                                  |
| json_dumps               | 9.85 ms                                                | 10.5 ms: 1.06x slower                                  |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.05 ms: 1.07x slower                                  |
| pyflate                  | 450 ms                                                 | 481 ms: 1.07x slower                                   |
| json                     | 4.77 ms                                                | 5.10 ms: 1.07x slower                                  |
| fannkuch                 | 387 ms                                                 | 417 ms: 1.08x slower                                   |
| pickle                   | 10.6 us                                                | 11.5 us: 1.08x slower                                  |
| richards_super           | 49.0 ms                                                | 53.7 ms: 1.10x slower                                  |
| pickle_dict              | 31.6 us                                                | 34.7 us: 1.10x slower                                  |
| spectral_norm            | 106 ms                                                 | 117 ms: 1.10x slower                                   |
| json_loads               | 25.2 us                                                | 27.9 us: 1.11x slower                                  |
| logging_silent           | 99.1 ns                                                | 110 ns: 1.11x slower                                   |
| pickle_list              | 4.62 us                                                | 5.11 us: 1.11x slower                                  |
| mako                     | 10.7 ms                                                | 12.0 ms: 1.12x slower                                  |
| richards                 | 43.2 ms                                                | 48.3 ms: 1.12x slower                                  |
| regex_v8                 | 22.3 ms                                                | 25.7 ms: 1.15x slower                                  |
| telco                    | 6.87 ms                                                | 8.22 ms: 1.20x slower                                  |
| Geometric mean           | (ref)                                                  | 1.02x slower                                           |

Benchmark hidden because not significant (3): async_tree_cpu_io_mixed, bench_mp_pool, deepcopy_reduce
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 97.13% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
