
# Results vs. 3.12.0

- fork: gvanrossum
- ref: split_uops
- machine: linux-x86_64
- commit hash: 8ab398d
- commit date: 2023-10-03
- overall geometric mean: 1.02x faster
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.58 sec: 1.05x faster                                          |
| tornado_http   | 99.6 ms                                                | 95.7 ms: 1.04x faster                                           |
| Geometric mean | (ref)                                                  | 1.04x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.3 ms: 1.02x faster                                           |
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                            |
| nbody          | 88.8 ms                                                | 91.8 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                  | 1.01x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 134 ms: 1.07x faster                                            |
| regex_effbot   | 3.55 ms                                                | 3.39 ms: 1.05x faster                                           |
| regex_dna      | 209 ms                                                 | 205 ms: 1.02x faster                                            |
| regex_v8       | 22.3 ms                                                | 23.9 ms: 1.07x slower                                           |
| Geometric mean | (ref)                                                  | 1.02x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 297 us: 1.04x faster                                            |
| tomli_loads          | 2.22 sec                                               | 2.15 sec: 1.03x faster                                          |
| unpickle_list        | 4.95 us                                                | 4.81 us: 1.03x faster                                           |
| unpickle             | 15.0 us                                                | 14.6 us: 1.03x faster                                           |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                            |
| pickle               | 10.6 us                                                | 10.4 us: 1.02x faster                                           |
| xml_etree_generate   | 84.8 ms                                                | 83.2 ms: 1.02x faster                                           |
| unpickle_pure_python | 218 us                                                 | 214 us: 1.02x faster                                            |
| xml_etree_process    | 58.6 ms                                                | 58.0 ms: 1.01x faster                                           |
| json_dumps           | 9.85 ms                                                | 9.75 ms: 1.01x faster                                           |
| pickle_list          | 4.62 us                                                | 4.68 us: 1.01x slower                                           |
| pickle_dict          | 31.6 us                                                | 32.2 us: 1.02x slower                                           |
| json_loads           | 25.2 us                                                | 25.9 us: 1.02x slower                                           |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                    |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                           |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                           |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.4 ms: 1.03x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 69.2 ms: 1.12x faster                                           |
| raytrace                 | 294 ms                                                 | 267 ms: 1.10x faster                                            |
| coverage                 | 94.2 ms                                                | 86.2 ms: 1.09x faster                                           |
| generators               | 31.1 ms                                                | 28.5 ms: 1.09x faster                                           |
| deltablue                | 3.52 ms                                                | 3.25 ms: 1.08x faster                                           |
| scimark_monte_carlo      | 71.0 ms                                                | 66.1 ms: 1.08x faster                                           |
| regex_compile            | 144 ms                                                 | 134 ms: 1.07x faster                                            |
| unpack_sequence          | 44.8 ns                                                | 41.9 ns: 1.07x faster                                           |
| async_tree_none          | 469 ms                                                 | 439 ms: 1.07x faster                                            |
| logging_format           | 6.90 us                                                | 6.48 us: 1.07x faster                                           |
| logging_simple           | 6.18 us                                                | 5.81 us: 1.06x faster                                           |
| chaos                    | 63.5 ms                                                | 60.0 ms: 1.06x faster                                           |
| scimark_sor              | 125 ms                                                 | 118 ms: 1.06x faster                                            |
| sqlglot_transpile        | 1.64 ms                                                | 1.56 ms: 1.05x faster                                           |
| asyncio_tcp              | 526 ms                                                 | 500 ms: 1.05x faster                                            |
| sqlglot_parse            | 1.32 ms                                                | 1.26 ms: 1.05x faster                                           |
| docutils                 | 2.70 sec                                               | 2.58 sec: 1.05x faster                                          |
| regex_effbot             | 3.55 ms                                                | 3.39 ms: 1.05x faster                                           |
| nqueens                  | 81.1 ms                                                | 77.9 ms: 1.04x faster                                           |
| tornado_http             | 99.6 ms                                                | 95.7 ms: 1.04x faster                                           |
| pickle_pure_python       | 309 us                                                 | 297 us: 1.04x faster                                            |
| gc_traversal             | 3.84 ms                                                | 3.70 ms: 1.04x faster                                           |
| sqlglot_normalize        | 107 ms                                                 | 103 ms: 1.04x faster                                            |
| deepcopy                 | 355 us                                                 | 344 us: 1.03x faster                                            |
| scimark_lu               | 114 ms                                                 | 110 ms: 1.03x faster                                            |
| deepcopy_reduce          | 3.14 us                                                | 3.03 us: 1.03x faster                                           |
| hexiom                   | 6.12 ms                                                | 5.92 ms: 1.03x faster                                           |
| pprint_safe_repr         | 735 ms                                                 | 711 ms: 1.03x faster                                            |
| pprint_pformat           | 1.50 sec                                               | 1.45 sec: 1.03x faster                                          |
| tomli_loads              | 2.22 sec                                               | 2.15 sec: 1.03x faster                                          |
| mako                     | 10.7 ms                                                | 10.4 ms: 1.03x faster                                           |
| unpickle_list            | 4.95 us                                                | 4.81 us: 1.03x faster                                           |
| unpickle                 | 15.0 us                                                | 14.6 us: 1.03x faster                                           |
| typing_runtime_protocols | 146 us                                                 | 142 us: 1.02x faster                                            |
| dulwich_log              | 67.9 ms                                                | 66.3 ms: 1.02x faster                                           |
| sqlglot_optimize         | 53.3 ms                                                | 52.1 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 699 ms: 1.02x faster                                            |
| mypy2                    | 344 ms                                                 | 336 ms: 1.02x faster                                            |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                            |
| bench_thread_pool        | 827 us                                                 | 810 us: 1.02x faster                                            |
| pickle                   | 10.6 us                                                | 10.4 us: 1.02x faster                                           |
| xml_etree_generate       | 84.8 ms                                                | 83.2 ms: 1.02x faster                                           |
| async_tree_memoization   | 573 ms                                                 | 562 ms: 1.02x faster                                            |
| unpickle_pure_python     | 218 us                                                 | 214 us: 1.02x faster                                            |
| fannkuch                 | 387 ms                                                 | 380 ms: 1.02x faster                                            |
| regex_dna                | 209 ms                                                 | 205 ms: 1.02x faster                                            |
| float                    | 80.7 ms                                                | 79.3 ms: 1.02x faster                                           |
| deepcopy_memo            | 37.4 us                                                | 36.8 us: 1.02x faster                                           |
| mdp                      | 2.57 sec                                               | 2.52 sec: 1.02x faster                                          |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                           |
| xml_etree_process        | 58.6 ms                                                | 58.0 ms: 1.01x faster                                           |
| json_dumps               | 9.85 ms                                                | 9.75 ms: 1.01x faster                                           |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                           |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                           |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                          |
| meteor_contest           | 105 ms                                                 | 105 ms: 1.00x slower                                            |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                            |
| pyflate                  | 450 ms                                                 | 454 ms: 1.01x slower                                            |
| spectral_norm            | 106 ms                                                 | 107 ms: 1.01x slower                                            |
| async_generators         | 440 ms                                                 | 445 ms: 1.01x slower                                            |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                           |
| coroutines               | 22.4 ms                                                | 22.7 ms: 1.01x slower                                           |
| pickle_list              | 4.62 us                                                | 4.68 us: 1.01x slower                                           |
| pickle_dict              | 31.6 us                                                | 32.2 us: 1.02x slower                                           |
| go                       | 136 ms                                                 | 138 ms: 1.02x slower                                            |
| json                     | 4.77 ms                                                | 4.88 ms: 1.02x slower                                           |
| json_loads               | 25.2 us                                                | 25.9 us: 1.02x slower                                           |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                          |
| nbody                    | 88.8 ms                                                | 91.8 ms: 1.03x slower                                           |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                           |
| regex_v8                 | 22.3 ms                                                | 23.9 ms: 1.07x slower                                           |
| richards_super           | 49.0 ms                                                | 52.5 ms: 1.07x slower                                           |
| richards                 | 43.2 ms                                                | 47.1 ms: 1.09x slower                                           |
| telco                    | 6.87 ms                                                | 8.05 ms: 1.17x slower                                           |
| Geometric mean           | (ref)                                                  | 1.02x faster                                                    |

Benchmark hidden because not significant (7): xml_etree_parse, scimark_sparse_mat_mult, scimark_fft, bench_mp_pool, comprehensions, logging_silent, pycparser
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
