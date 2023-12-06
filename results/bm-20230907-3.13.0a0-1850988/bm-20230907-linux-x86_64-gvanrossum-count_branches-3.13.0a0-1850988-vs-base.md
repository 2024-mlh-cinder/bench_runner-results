
# Results vs. base

- fork: gvanrossum
- ref: count_branches
- machine: linux-x86_64
- commit hash: 1850988
- commit date: 2023-09-07
- overall geometric mean: 1.00x faster
- HPT reliability: 56.52%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.63 sec: 1.00x slower                                              |
| Geometric mean | (ref)                                                                 | 1.00x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 212 ms                                                                | 187 ms: 1.13x faster                                                |
| nbody          | 91.7 ms                                                               | 88.1 ms: 1.04x faster                                               |
| float          | 78.4 ms                                                               | 79.3 ms: 1.01x slower                                               |
| Geometric mean | (ref)                                                                 | 1.05x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 135 ms                                                                | 134 ms: 1.00x faster                                                |
| regex_v8       | 25.0 ms                                                               | 25.5 ms: 1.02x slower                                               |
| regex_dna      | 212 ms                                                                | 224 ms: 1.06x slower                                                |
| regex_effbot   | 3.61 ms                                                               | 3.85 ms: 1.07x slower                                               |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_dict          | 32.8 us                                                               | 32.0 us: 1.03x faster                                               |
| tomli_loads          | 2.06 sec                                                              | 2.02 sec: 1.02x faster                                              |
| pickle_pure_python   | 296 us                                                                | 292 us: 1.01x faster                                                |
| xml_etree_process    | 56.6 ms                                                               | 56.2 ms: 1.01x faster                                               |
| xml_etree_generate   | 81.5 ms                                                               | 81.8 ms: 1.00x slower                                               |
| json_dumps           | 9.75 ms                                                               | 9.82 ms: 1.01x slower                                               |
| json_loads           | 25.2 us                                                               | 25.3 us: 1.01x slower                                               |
| xml_etree_iterparse  | 102 ms                                                                | 102 ms: 1.01x slower                                                |
| xml_etree_parse      | 151 ms                                                                | 152 ms: 1.01x slower                                                |
| unpickle_pure_python | 212 us                                                                | 218 us: 1.03x slower                                                |
| Geometric mean       | (ref)                                                                 | 1.00x faster                                                        |

Benchmark hidden because not significant (4): unpickle, pickle_list, pickle, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 9.50 ms                                                               | 9.57 ms: 1.01x slower                                               |
| python_startup_no_site | 6.97 ms                                                               | 7.04 ms: 1.01x slower                                               |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.8 ms                                                               | 10.7 ms: 1.01x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988 |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpack_sequence          | 58.5 ns                                                               | 39.8 ns: 1.47x faster                                               |
| pidigits                 | 212 ms                                                                | 187 ms: 1.13x faster                                                |
| nbody                    | 91.7 ms                                                               | 88.1 ms: 1.04x faster                                               |
| generators               | 30.1 ms                                                               | 29.1 ms: 1.03x faster                                               |
| spectral_norm            | 107 ms                                                                | 104 ms: 1.03x faster                                                |
| logging_simple           | 5.97 us                                                               | 5.80 us: 1.03x faster                                               |
| chaos                    | 60.2 ms                                                               | 58.6 ms: 1.03x faster                                               |
| pickle_dict              | 32.8 us                                                               | 32.0 us: 1.03x faster                                               |
| logging_silent           | 103 ns                                                                | 101 ns: 1.02x faster                                                |
| hexiom                   | 6.03 ms                                                               | 5.89 ms: 1.02x faster                                               |
| tomli_loads              | 2.06 sec                                                              | 2.02 sec: 1.02x faster                                              |
| logging_format           | 6.50 us                                                               | 6.37 us: 1.02x faster                                               |
| pprint_pformat           | 1.50 sec                                                              | 1.47 sec: 1.02x faster                                              |
| pprint_safe_repr         | 734 ms                                                                | 719 ms: 1.02x faster                                                |
| fannkuch                 | 390 ms                                                                | 383 ms: 1.02x faster                                                |
| crypto_pyaes             | 70.9 ms                                                               | 70.0 ms: 1.01x faster                                               |
| pathlib                  | 18.7 ms                                                               | 18.4 ms: 1.01x faster                                               |
| pickle_pure_python       | 296 us                                                                | 292 us: 1.01x faster                                                |
| nqueens                  | 79.4 ms                                                               | 78.4 ms: 1.01x faster                                               |
| sqlglot_optimize         | 52.9 ms                                                               | 52.2 ms: 1.01x faster                                               |
| deepcopy_reduce          | 3.12 us                                                               | 3.08 us: 1.01x faster                                               |
| deepcopy                 | 350 us                                                                | 346 us: 1.01x faster                                                |
| sqlglot_normalize        | 105 ms                                                                | 104 ms: 1.01x faster                                                |
| mako                     | 10.8 ms                                                               | 10.7 ms: 1.01x faster                                               |
| pyflate                  | 452 ms                                                                | 449 ms: 1.01x faster                                                |
| xml_etree_process        | 56.6 ms                                                               | 56.2 ms: 1.01x faster                                               |
| regex_compile            | 135 ms                                                                | 134 ms: 1.00x faster                                                |
| mypy2                    | 338 ms                                                                | 336 ms: 1.00x faster                                                |
| bench_thread_pool        | 814 us                                                                | 812 us: 1.00x faster                                                |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.79 sec: 1.00x faster                                              |
| docutils                 | 2.62 sec                                                              | 2.63 sec: 1.00x slower                                              |
| xml_etree_generate       | 81.5 ms                                                               | 81.8 ms: 1.00x slower                                               |
| go                       | 138 ms                                                                | 139 ms: 1.00x slower                                                |
| async_generators         | 440 ms                                                                | 443 ms: 1.01x slower                                                |
| python_startup           | 9.50 ms                                                               | 9.57 ms: 1.01x slower                                               |
| scimark_sor              | 121 ms                                                                | 121 ms: 1.01x slower                                                |
| json_dumps               | 9.75 ms                                                               | 9.82 ms: 1.01x slower                                               |
| json_loads               | 25.2 us                                                               | 25.3 us: 1.01x slower                                               |
| python_startup_no_site   | 6.97 ms                                                               | 7.04 ms: 1.01x slower                                               |
| xml_etree_iterparse      | 102 ms                                                                | 102 ms: 1.01x slower                                                |
| asyncio_tcp              | 485 ms                                                                | 490 ms: 1.01x slower                                                |
| telco                    | 7.86 ms                                                               | 7.94 ms: 1.01x slower                                               |
| xml_etree_parse          | 151 ms                                                                | 152 ms: 1.01x slower                                                |
| richards                 | 46.2 ms                                                               | 46.7 ms: 1.01x slower                                               |
| float                    | 78.4 ms                                                               | 79.3 ms: 1.01x slower                                               |
| create_gc_cycles         | 1.49 ms                                                               | 1.51 ms: 1.01x slower                                               |
| deltablue                | 3.25 ms                                                               | 3.29 ms: 1.01x slower                                               |
| scimark_monte_carlo      | 65.7 ms                                                               | 66.5 ms: 1.01x slower                                               |
| async_tree_io            | 1.18 sec                                                              | 1.19 sec: 1.01x slower                                              |
| deepcopy_memo            | 37.2 us                                                               | 37.7 us: 1.01x slower                                               |
| async_tree_memoization   | 561 ms                                                                | 569 ms: 1.01x slower                                                |
| richards_super           | 53.1 ms                                                               | 53.9 ms: 1.02x slower                                               |
| regex_v8                 | 25.0 ms                                                               | 25.5 ms: 1.02x slower                                               |
| scimark_lu               | 109 ms                                                                | 112 ms: 1.02x slower                                                |
| json                     | 4.89 ms                                                               | 5.01 ms: 1.02x slower                                               |
| unpickle_pure_python     | 212 us                                                                | 218 us: 1.03x slower                                                |
| pycparser                | 1.17 sec                                                              | 1.20 sec: 1.03x slower                                              |
| gc_traversal             | 3.68 ms                                                               | 3.83 ms: 1.04x slower                                               |
| regex_dna                | 212 ms                                                                | 224 ms: 1.06x slower                                                |
| mdp                      | 2.57 sec                                                              | 2.73 sec: 1.06x slower                                              |
| regex_effbot             | 3.61 ms                                                               | 3.85 ms: 1.07x slower                                               |
| typing_runtime_protocols | 139 us                                                                | 149 us: 1.07x slower                                                |
| Geometric mean           | (ref)                                                                 | 1.00x faster                                                        |

Benchmark hidden because not significant (20): raytrace, dask, sqlglot_transpile, unpickle, coroutines, sqlglot_parse, pickle_list, dulwich_log, tornado_http, sqlite_synth, comprehensions, pickle, scimark_sparse_mat_mult, meteor_contest, bench_mp_pool, scimark_fft, unpickle_list, coverage, async_tree_cpu_io_mixed, async_tree_none


# HPT report

- Reliability score: 56.52% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
