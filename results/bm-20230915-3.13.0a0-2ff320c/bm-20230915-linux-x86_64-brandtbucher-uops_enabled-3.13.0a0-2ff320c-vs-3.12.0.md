
# Results vs. 3.12.0

- fork: brandtbucher
- ref: uops_enabled
- machine: linux-x86_64
- commit hash: 2ff320c
- commit date: 2023-09-15
- overall geometric mean: 1.04x slower
- HPT reliability: 99.92%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.71 sec: 1.00x slower                                              |
| tornado_http   | 99.6 ms                                                | 97.2 ms: 1.02x faster                                               |
| Geometric mean | (ref)                                                  | 1.01x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                |
| float          | 80.7 ms                                                | 85.1 ms: 1.05x slower                                               |
| nbody          | 88.8 ms                                                | 108 ms: 1.22x slower                                                |
| Geometric mean | (ref)                                                  | 1.09x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 208 ms: 1.00x faster                                                |
| regex_effbot   | 3.55 ms                                                | 3.61 ms: 1.02x slower                                               |
| regex_compile  | 144 ms                                                 | 152 ms: 1.05x slower                                                |
| regex_v8       | 22.3 ms                                                | 23.6 ms: 1.06x slower                                               |
| Geometric mean | (ref)                                                  | 1.03x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 299 us: 1.03x faster                                                |
| unpickle_list        | 4.95 us                                                | 4.82 us: 1.03x faster                                               |
| xml_etree_process    | 58.6 ms                                                | 57.4 ms: 1.02x faster                                               |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                |
| xml_etree_generate   | 84.8 ms                                                | 84.0 ms: 1.01x faster                                               |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                               |
| pickle_list          | 4.62 us                                                | 4.71 us: 1.02x slower                                               |
| pickle_dict          | 31.6 us                                                | 32.7 us: 1.04x slower                                               |
| unpickle_pure_python | 218 us                                                 | 237 us: 1.09x slower                                                |
| tomli_loads          | 2.22 sec                                               | 2.41 sec: 1.09x slower                                              |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                        |

Benchmark hidden because not significant (4): unpickle, xml_etree_parse, json_dumps, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.85 ms: 1.01x faster                                               |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                               |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.6 ms: 1.08x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 85.9 ms: 1.10x faster                                               |
| asyncio_tcp              | 526 ms                                                 | 481 ms: 1.09x faster                                                |
| generators               | 31.1 ms                                                | 28.6 ms: 1.09x faster                                               |
| scimark_monte_carlo      | 71.0 ms                                                | 67.7 ms: 1.05x faster                                               |
| async_tree_none          | 469 ms                                                 | 448 ms: 1.05x faster                                                |
| crypto_pyaes             | 77.2 ms                                                | 73.7 ms: 1.05x faster                                               |
| raytrace                 | 294 ms                                                 | 281 ms: 1.05x faster                                                |
| pickle_pure_python       | 309 us                                                 | 299 us: 1.03x faster                                                |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                               |
| unpickle_list            | 4.95 us                                                | 4.82 us: 1.03x faster                                               |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.02x faster                                               |
| tornado_http             | 99.6 ms                                                | 97.2 ms: 1.02x faster                                               |
| xml_etree_process        | 58.6 ms                                                | 57.4 ms: 1.02x faster                                               |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                               |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                               |
| xml_etree_generate       | 84.8 ms                                                | 84.0 ms: 1.01x faster                                               |
| scimark_sor              | 125 ms                                                 | 124 ms: 1.01x faster                                                |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                |
| python_startup_no_site   | 6.90 ms                                                | 6.85 ms: 1.01x faster                                               |
| pprint_safe_repr         | 735 ms                                                 | 730 ms: 1.01x faster                                                |
| regex_dna                | 209 ms                                                 | 208 ms: 1.00x faster                                                |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                              |
| docutils                 | 2.70 sec                                               | 2.71 sec: 1.00x slower                                              |
| sqlglot_optimize         | 53.3 ms                                                | 53.5 ms: 1.00x slower                                               |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.01x slower                                               |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                |
| dulwich_log              | 67.9 ms                                                | 68.4 ms: 1.01x slower                                               |
| deltablue                | 3.52 ms                                                | 3.55 ms: 1.01x slower                                               |
| create_gc_cycles         | 1.52 ms                                                | 1.54 ms: 1.01x slower                                               |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                               |
| logging_simple           | 6.18 us                                                | 6.25 us: 1.01x slower                                               |
| bench_thread_pool        | 827 us                                                 | 837 us: 1.01x slower                                                |
| mypy2                    | 344 ms                                                 | 348 ms: 1.01x slower                                                |
| scimark_lu               | 114 ms                                                 | 115 ms: 1.01x slower                                                |
| regex_effbot             | 3.55 ms                                                | 3.61 ms: 1.02x slower                                               |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                               |
| spectral_norm            | 106 ms                                                 | 108 ms: 1.02x slower                                                |
| logging_format           | 6.90 us                                                | 7.04 us: 1.02x slower                                               |
| pickle_list              | 4.62 us                                                | 4.71 us: 1.02x slower                                               |
| async_generators         | 440 ms                                                 | 451 ms: 1.02x slower                                                |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.02x slower                                               |
| typing_runtime_protocols | 146 us                                                 | 151 us: 1.03x slower                                                |
| mdp                      | 2.57 sec                                               | 2.65 sec: 1.03x slower                                              |
| pickle_dict              | 31.6 us                                                | 32.7 us: 1.04x slower                                               |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.04x slower                                              |
| float                    | 80.7 ms                                                | 85.1 ms: 1.05x slower                                               |
| regex_compile            | 144 ms                                                 | 152 ms: 1.05x slower                                                |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.05x slower                                                |
| regex_v8                 | 22.3 ms                                                | 23.6 ms: 1.06x slower                                               |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                               |
| pycparser                | 1.15 sec                                               | 1.23 sec: 1.07x slower                                              |
| scimark_fft              | 358 ms                                                 | 383 ms: 1.07x slower                                                |
| pyflate                  | 450 ms                                                 | 483 ms: 1.07x slower                                                |
| mako                     | 10.7 ms                                                | 11.6 ms: 1.08x slower                                               |
| meteor_contest           | 105 ms                                                 | 114 ms: 1.09x slower                                                |
| unpickle_pure_python     | 218 us                                                 | 237 us: 1.09x slower                                                |
| tomli_loads              | 2.22 sec                                               | 2.41 sec: 1.09x slower                                              |
| deepcopy_memo            | 37.4 us                                                | 40.9 us: 1.09x slower                                               |
| go                       | 136 ms                                                 | 149 ms: 1.10x slower                                                |
| chaos                    | 63.5 ms                                                | 70.7 ms: 1.11x slower                                               |
| unpack_sequence          | 44.8 ns                                                | 50.4 ns: 1.12x slower                                               |
| fannkuch                 | 387 ms                                                 | 441 ms: 1.14x slower                                                |
| richards_super           | 49.0 ms                                                | 56.2 ms: 1.15x slower                                               |
| richards                 | 43.2 ms                                                | 49.8 ms: 1.15x slower                                               |
| telco                    | 6.87 ms                                                | 8.12 ms: 1.18x slower                                               |
| nqueens                  | 81.1 ms                                                | 97.4 ms: 1.20x slower                                               |
| nbody                    | 88.8 ms                                                | 108 ms: 1.22x slower                                                |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.79 ms: 1.22x slower                                               |
| comprehensions           | 20.4 us                                                | 25.3 us: 1.24x slower                                               |
| hexiom                   | 6.12 ms                                                | 7.73 ms: 1.26x slower                                               |
| dask                     | 365 ms                                                 | 533 ms: 1.46x slower                                                |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                        |

Benchmark hidden because not significant (10): unpickle, xml_etree_parse, async_tree_cpu_io_mixed, json_dumps, pprint_pformat, bench_mp_pool, deepcopy, json_loads, async_tree_memoization, json
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.92% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
