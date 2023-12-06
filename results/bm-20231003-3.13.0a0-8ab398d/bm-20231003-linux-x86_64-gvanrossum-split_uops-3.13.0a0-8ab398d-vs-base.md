
# Results vs. base

- fork: gvanrossum
- ref: split_uops
- machine: linux-x86_64
- commit hash: 8ab398d
- commit date: 2023-10-03
- overall geometric mean: 1.01x faster
- HPT reliability: 99.88%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------:|
| docutils       | 2.60 sec                                                              | 2.58 sec: 1.01x faster                                          |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                    |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------:|
| float          | 80.4 ms                                                               | 79.3 ms: 1.01x faster                                           |
| pidigits       | 187 ms                                                                | 188 ms: 1.00x slower                                            |
| nbody          | 89.6 ms                                                               | 91.8 ms: 1.02x slower                                           |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                               | 3.39 ms: 1.06x faster                                           |
| regex_dna      | 211 ms                                                                | 205 ms: 1.03x faster                                            |
| regex_v8       | 24.3 ms                                                               | 23.9 ms: 1.01x faster                                           |
| regex_compile  | 135 ms                                                                | 134 ms: 1.01x faster                                            |
| Geometric mean | (ref)                                                                 | 1.03x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|----------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle               | 10.7 us                                                               | 10.4 us: 1.03x faster                                           |
| pickle_list          | 4.81 us                                                               | 4.68 us: 1.03x faster                                           |
| pickle_dict          | 32.8 us                                                               | 32.2 us: 1.02x faster                                           |
| unpickle_pure_python | 218 us                                                                | 214 us: 1.02x faster                                            |
| json_loads           | 26.1 us                                                               | 25.9 us: 1.01x faster                                           |
| xml_etree_iterparse  | 103 ms                                                                | 102 ms: 1.01x faster                                            |
| pickle_pure_python   | 300 us                                                                | 297 us: 1.01x faster                                            |
| json_dumps           | 9.81 ms                                                               | 9.75 ms: 1.01x faster                                           |
| unpickle_list        | 4.83 us                                                               | 4.81 us: 1.00x faster                                           |
| tomli_loads          | 2.13 sec                                                              | 2.15 sec: 1.01x slower                                          |
| xml_etree_process    | 57.1 ms                                                               | 58.0 ms: 1.01x slower                                           |
| unpickle             | 14.3 us                                                               | 14.6 us: 1.02x slower                                           |
| Geometric mean       | (ref)                                                                 | 1.01x faster                                                    |

Benchmark hidden because not significant (2): xml_etree_generate, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.00x slower                                           |
| python_startup_no_site | 6.85 ms                                                               | 6.86 ms: 1.00x slower                                           |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|-----------|:---------------------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 10.8 ms                                                               | 10.4 ms: 1.04x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe | bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d |
|--------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------:|
| unpack_sequence          | 48.5 ns                                                               | 41.9 ns: 1.16x faster                                           |
| scimark_sor              | 128 ms                                                                | 118 ms: 1.08x faster                                            |
| regex_effbot             | 3.61 ms                                                               | 3.39 ms: 1.06x faster                                           |
| mdp                      | 2.66 sec                                                              | 2.52 sec: 1.06x faster                                          |
| mako                     | 10.8 ms                                                               | 10.4 ms: 1.04x faster                                           |
| gc_traversal             | 3.84 ms                                                               | 3.70 ms: 1.04x faster                                           |
| deltablue                | 3.34 ms                                                               | 3.25 ms: 1.03x faster                                           |
| pycparser                | 1.19 sec                                                              | 1.15 sec: 1.03x faster                                          |
| regex_dna                | 211 ms                                                                | 205 ms: 1.03x faster                                            |
| pickle                   | 10.7 us                                                               | 10.4 us: 1.03x faster                                           |
| pickle_list              | 4.81 us                                                               | 4.68 us: 1.03x faster                                           |
| fannkuch                 | 389 ms                                                                | 380 ms: 1.02x faster                                            |
| async_generators         | 454 ms                                                                | 445 ms: 1.02x faster                                            |
| richards_super           | 53.5 ms                                                               | 52.5 ms: 1.02x faster                                           |
| pickle_dict              | 32.8 us                                                               | 32.2 us: 1.02x faster                                           |
| unpickle_pure_python     | 218 us                                                                | 214 us: 1.02x faster                                            |
| pprint_safe_repr         | 723 ms                                                                | 711 ms: 1.02x faster                                            |
| sqlglot_transpile        | 1.58 ms                                                               | 1.56 ms: 1.02x faster                                           |
| regex_v8                 | 24.3 ms                                                               | 23.9 ms: 1.01x faster                                           |
| deepcopy_memo            | 37.3 us                                                               | 36.8 us: 1.01x faster                                           |
| float                    | 80.4 ms                                                               | 79.3 ms: 1.01x faster                                           |
| go                       | 140 ms                                                                | 138 ms: 1.01x faster                                            |
| pprint_pformat           | 1.47 sec                                                              | 1.45 sec: 1.01x faster                                          |
| json_loads               | 26.1 us                                                               | 25.9 us: 1.01x faster                                           |
| logging_silent           | 100 ns                                                                | 99.5 ns: 1.01x faster                                           |
| deepcopy_reduce          | 3.06 us                                                               | 3.03 us: 1.01x faster                                           |
| typing_runtime_protocols | 144 us                                                                | 142 us: 1.01x faster                                            |
| xml_etree_iterparse      | 103 ms                                                                | 102 ms: 1.01x faster                                            |
| raytrace                 | 270 ms                                                                | 267 ms: 1.01x faster                                            |
| sqlglot_parse            | 1.27 ms                                                               | 1.26 ms: 1.01x faster                                           |
| pickle_pure_python       | 300 us                                                                | 297 us: 1.01x faster                                            |
| crypto_pyaes             | 69.7 ms                                                               | 69.2 ms: 1.01x faster                                           |
| docutils                 | 2.60 sec                                                              | 2.58 sec: 1.01x faster                                          |
| json_dumps               | 9.81 ms                                                               | 9.75 ms: 1.01x faster                                           |
| regex_compile            | 135 ms                                                                | 134 ms: 1.01x faster                                            |
| mypy2                    | 338 ms                                                                | 336 ms: 1.00x faster                                            |
| dulwich_log              | 66.6 ms                                                               | 66.3 ms: 1.00x faster                                           |
| chaos                    | 60.2 ms                                                               | 60.0 ms: 1.00x faster                                           |
| unpickle_list            | 4.83 us                                                               | 4.81 us: 1.00x faster                                           |
| sqlglot_optimize         | 52.3 ms                                                               | 52.1 ms: 1.00x faster                                           |
| async_tree_io            | 1.19 sec                                                              | 1.19 sec: 1.00x faster                                          |
| create_gc_cycles         | 1.51 ms                                                               | 1.51 ms: 1.00x faster                                           |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.00x slower                                           |
| python_startup_no_site   | 6.85 ms                                                               | 6.86 ms: 1.00x slower                                           |
| bench_thread_pool        | 809 us                                                                | 810 us: 1.00x slower                                            |
| meteor_contest           | 105 ms                                                                | 105 ms: 1.00x slower                                            |
| pidigits                 | 187 ms                                                                | 188 ms: 1.00x slower                                            |
| scimark_monte_carlo      | 65.6 ms                                                               | 66.1 ms: 1.01x slower                                           |
| spectral_norm            | 106 ms                                                                | 107 ms: 1.01x slower                                            |
| generators               | 28.2 ms                                                               | 28.5 ms: 1.01x slower                                           |
| tomli_loads              | 2.13 sec                                                              | 2.15 sec: 1.01x slower                                          |
| telco                    | 7.96 ms                                                               | 8.05 ms: 1.01x slower                                           |
| logging_format           | 6.39 us                                                               | 6.48 us: 1.01x slower                                           |
| xml_etree_process        | 57.1 ms                                                               | 58.0 ms: 1.01x slower                                           |
| coverage                 | 84.5 ms                                                               | 86.2 ms: 1.02x slower                                           |
| unpickle                 | 14.3 us                                                               | 14.6 us: 1.02x slower                                           |
| nbody                    | 89.6 ms                                                               | 91.8 ms: 1.02x slower                                           |
| scimark_lu               | 107 ms                                                                | 110 ms: 1.03x slower                                            |
| scimark_fft              | 348 ms                                                                | 359 ms: 1.03x slower                                            |
| scimark_sparse_mat_mult  | 4.59 ms                                                               | 4.74 ms: 1.03x slower                                           |
| coroutines               | 21.8 ms                                                               | 22.7 ms: 1.04x slower                                           |
| Geometric mean           | (ref)                                                                 | 1.01x faster                                                    |

Benchmark hidden because not significant (20): richards, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization, logging_simple, pathlib, comprehensions, deepcopy, pyflate, asyncio_tcp_ssl, json, hexiom, bench_mp_pool, sqlglot_normalize, asyncio_tcp, nqueens, xml_etree_generate, sqlite_synth, tornado_http, xml_etree_parse


# HPT report

- Reliability score: 99.88% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
