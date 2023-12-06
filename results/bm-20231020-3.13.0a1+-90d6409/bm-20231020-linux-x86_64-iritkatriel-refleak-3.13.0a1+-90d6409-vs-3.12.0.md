
# Results vs. 3.12.0

- fork: iritkatriel
- ref: refleak
- machine: linux-x86_64
- commit hash: 90d6409
- commit date: 2023-10-20
- overall geometric mean: 1.01x slower
- HPT reliability: 72.43%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.65 sec: 1.02x faster                                         |
| tornado_http   | 99.6 ms                                                | 95.5 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.03x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 80.7 ms                                                | 80.2 ms: 1.01x faster                                          |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                           |
| nbody          | 88.8 ms                                                | 91.0 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                           |
| regex_effbot   | 3.55 ms                                                | 3.52 ms: 1.01x faster                                          |
| regex_dna      | 209 ms                                                 | 214 ms: 1.03x slower                                           |
| regex_v8       | 22.3 ms                                                | 25.4 ms: 1.14x slower                                          |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                         |
| unpickle             | 15.0 us                                                | 14.6 us: 1.03x faster                                          |
| xml_etree_process    | 58.6 ms                                                | 59.1 ms: 1.01x slower                                          |
| unpickle_pure_python | 218 us                                                 | 220 us: 1.01x slower                                           |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.02x slower                                           |
| xml_etree_generate   | 84.8 ms                                                | 86.4 ms: 1.02x slower                                          |
| xml_etree_parse      | 154 ms                                                 | 158 ms: 1.03x slower                                           |
| unpickle_list        | 4.95 us                                                | 5.18 us: 1.05x slower                                          |
| json_dumps           | 9.85 ms                                                | 10.4 ms: 1.05x slower                                          |
| pickle               | 10.6 us                                                | 11.3 us: 1.07x slower                                          |
| json_loads           | 25.2 us                                                | 27.8 us: 1.10x slower                                          |
| pickle_dict          | 31.6 us                                                | 35.3 us: 1.12x slower                                          |
| pickle_list          | 4.62 us                                                | 5.16 us: 1.12x slower                                          |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                   |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.85 ms: 1.01x faster                                          |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                          |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.6 ms: 1.08x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| comprehensions           | 20.4 us                                                | 16.6 us: 1.23x faster                                          |
| asyncio_tcp              | 526 ms                                                 | 480 ms: 1.10x faster                                           |
| raytrace                 | 294 ms                                                 | 273 ms: 1.08x faster                                           |
| logging_format           | 6.90 us                                                | 6.41 us: 1.08x faster                                          |
| crypto_pyaes             | 77.2 ms                                                | 71.8 ms: 1.07x faster                                          |
| async_tree_none          | 469 ms                                                 | 439 ms: 1.07x faster                                           |
| logging_simple           | 6.18 us                                                | 5.87 us: 1.05x faster                                          |
| generators               | 31.1 ms                                                | 29.7 ms: 1.05x faster                                          |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                           |
| deltablue                | 3.52 ms                                                | 3.36 ms: 1.05x faster                                          |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                         |
| tornado_http             | 99.6 ms                                                | 95.5 ms: 1.04x faster                                          |
| coverage                 | 94.2 ms                                                | 90.5 ms: 1.04x faster                                          |
| scimark_monte_carlo      | 71.0 ms                                                | 68.5 ms: 1.04x faster                                          |
| chaos                    | 63.5 ms                                                | 61.3 ms: 1.04x faster                                          |
| create_gc_cycles         | 1.52 ms                                                | 1.47 ms: 1.04x faster                                          |
| nqueens                  | 81.1 ms                                                | 78.6 ms: 1.03x faster                                          |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                          |
| unpickle                 | 15.0 us                                                | 14.6 us: 1.03x faster                                          |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.02x faster                                          |
| docutils                 | 2.70 sec                                               | 2.65 sec: 1.02x faster                                         |
| bench_thread_pool        | 827 us                                                 | 812 us: 1.02x faster                                           |
| async_tree_memoization   | 573 ms                                                 | 566 ms: 1.01x faster                                           |
| unpack_sequence          | 44.8 ns                                                | 44.3 ns: 1.01x faster                                          |
| dulwich_log              | 67.9 ms                                                | 67.1 ms: 1.01x faster                                          |
| mdp                      | 2.57 sec                                               | 2.54 sec: 1.01x faster                                         |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                           |
| regex_effbot             | 3.55 ms                                                | 3.52 ms: 1.01x faster                                          |
| python_startup_no_site   | 6.90 ms                                                | 6.85 ms: 1.01x faster                                          |
| hexiom                   | 6.12 ms                                                | 6.08 ms: 1.01x faster                                          |
| float                    | 80.7 ms                                                | 80.2 ms: 1.01x faster                                          |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                                         |
| mypy2                    | 344 ms                                                 | 342 ms: 1.00x faster                                           |
| sqlglot_optimize         | 53.3 ms                                                | 53.5 ms: 1.00x slower                                          |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                           |
| deepcopy                 | 355 us                                                 | 357 us: 1.01x slower                                           |
| gc_traversal             | 3.84 ms                                                | 3.87 ms: 1.01x slower                                          |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                           |
| xml_etree_process        | 58.6 ms                                                | 59.1 ms: 1.01x slower                                          |
| unpickle_pure_python     | 218 us                                                 | 220 us: 1.01x slower                                           |
| scimark_lu               | 114 ms                                                 | 115 ms: 1.01x slower                                           |
| scimark_sor              | 125 ms                                                 | 126 ms: 1.02x slower                                           |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.02x slower                                           |
| sqlite_synth             | 2.76 us                                                | 2.81 us: 1.02x slower                                          |
| xml_etree_generate       | 84.8 ms                                                | 86.4 ms: 1.02x slower                                          |
| coroutines               | 22.4 ms                                                | 22.9 ms: 1.02x slower                                          |
| pathlib                  | 18.5 ms                                                | 18.9 ms: 1.02x slower                                          |
| scimark_fft              | 358 ms                                                 | 366 ms: 1.02x slower                                           |
| nbody                    | 88.8 ms                                                | 91.0 ms: 1.02x slower                                          |
| xml_etree_parse          | 154 ms                                                 | 158 ms: 1.03x slower                                           |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                         |
| regex_dna                | 209 ms                                                 | 214 ms: 1.03x slower                                           |
| async_generators         | 440 ms                                                 | 454 ms: 1.03x slower                                           |
| spectral_norm            | 106 ms                                                 | 110 ms: 1.03x slower                                           |
| typing_runtime_protocols | 146 us                                                 | 151 us: 1.03x slower                                           |
| unpickle_list            | 4.95 us                                                | 5.18 us: 1.05x slower                                          |
| fannkuch                 | 387 ms                                                 | 406 ms: 1.05x slower                                           |
| json_dumps               | 9.85 ms                                                | 10.4 ms: 1.05x slower                                          |
| pycparser                | 1.15 sec                                               | 1.21 sec: 1.05x slower                                         |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                          |
| go                       | 136 ms                                                 | 144 ms: 1.06x slower                                           |
| deepcopy_memo            | 37.4 us                                                | 39.9 us: 1.07x slower                                          |
| pickle                   | 10.6 us                                                | 11.3 us: 1.07x slower                                          |
| json                     | 4.77 ms                                                | 5.11 ms: 1.07x slower                                          |
| mako                     | 10.7 ms                                                | 11.6 ms: 1.08x slower                                          |
| logging_silent           | 99.1 ns                                                | 108 ns: 1.09x slower                                           |
| richards_super           | 49.0 ms                                                | 53.7 ms: 1.10x slower                                          |
| json_loads               | 25.2 us                                                | 27.8 us: 1.10x slower                                          |
| richards                 | 43.2 ms                                                | 47.5 ms: 1.10x slower                                          |
| pickle_dict              | 31.6 us                                                | 35.3 us: 1.12x slower                                          |
| pickle_list              | 4.62 us                                                | 5.16 us: 1.12x slower                                          |
| regex_v8                 | 22.3 ms                                                | 25.4 ms: 1.14x slower                                          |
| telco                    | 6.87 ms                                                | 8.35 ms: 1.21x slower                                          |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (8): pprint_pformat, pprint_safe_repr, pickle_pure_python, bench_mp_pool, async_tree_cpu_io_mixed, pyflate, deepcopy_reduce, scimark_sparse_mat_mult
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 72.43% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
