
# Results vs. 3.12.0

- fork: gvanrossum
- ref: load_attr_uops
- machine: linux-x86_64
- commit hash: b54eee3
- commit date: 2023-09-26
- overall geometric mean: 1.01x faster
- HPT reliability: 98.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.62 sec: 1.03x faster                                              |
| tornado_http   | 99.6 ms                                                | 95.1 ms: 1.05x faster                                               |
| Geometric mean | (ref)                                                  | 1.04x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 78.4 ms: 1.03x faster                                               |
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                |
| nbody          | 88.8 ms                                                | 90.9 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                  | 1.00x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 133 ms: 1.08x faster                                                |
| regex_effbot   | 3.55 ms                                                | 3.52 ms: 1.01x faster                                               |
| regex_dna      | 209 ms                                                 | 212 ms: 1.02x slower                                                |
| regex_v8       | 22.3 ms                                                | 24.0 ms: 1.08x slower                                               |
| Geometric mean | (ref)                                                  | 1.00x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.09 sec: 1.06x faster                                              |
| pickle_pure_python   | 309 us                                                 | 296 us: 1.05x faster                                                |
| unpickle             | 15.0 us                                                | 14.3 us: 1.04x faster                                               |
| unpickle_pure_python | 218 us                                                 | 211 us: 1.04x faster                                                |
| xml_etree_process    | 58.6 ms                                                | 57.7 ms: 1.01x faster                                               |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                |
| json_dumps           | 9.85 ms                                                | 9.76 ms: 1.01x faster                                               |
| xml_etree_generate   | 84.8 ms                                                | 84.3 ms: 1.01x faster                                               |
| pickle_dict          | 31.6 us                                                | 31.9 us: 1.01x slower                                               |
| pickle_list          | 4.62 us                                                | 4.78 us: 1.04x slower                                               |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                        |

Benchmark hidden because not significant (3): pickle, unpickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                               |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                               |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.6 ms: 1.01x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 68.6 ms: 1.12x faster                                               |
| coverage                 | 94.2 ms                                                | 84.8 ms: 1.11x faster                                               |
| raytrace                 | 294 ms                                                 | 268 ms: 1.10x faster                                                |
| generators               | 31.1 ms                                                | 28.8 ms: 1.08x faster                                               |
| regex_compile            | 144 ms                                                 | 133 ms: 1.08x faster                                                |
| gc_traversal             | 3.84 ms                                                | 3.56 ms: 1.08x faster                                               |
| scimark_monte_carlo      | 71.0 ms                                                | 66.2 ms: 1.07x faster                                               |
| deltablue                | 3.52 ms                                                | 3.29 ms: 1.07x faster                                               |
| async_tree_none          | 469 ms                                                 | 440 ms: 1.07x faster                                                |
| logging_format           | 6.90 us                                                | 6.52 us: 1.06x faster                                               |
| tomli_loads              | 2.22 sec                                               | 2.09 sec: 1.06x faster                                              |
| chaos                    | 63.5 ms                                                | 60.6 ms: 1.05x faster                                               |
| tornado_http             | 99.6 ms                                                | 95.1 ms: 1.05x faster                                               |
| sqlglot_parse            | 1.32 ms                                                | 1.26 ms: 1.05x faster                                               |
| scimark_lu               | 114 ms                                                 | 109 ms: 1.05x faster                                                |
| pickle_pure_python       | 309 us                                                 | 296 us: 1.05x faster                                                |
| unpickle                 | 15.0 us                                                | 14.3 us: 1.04x faster                                               |
| asyncio_tcp              | 526 ms                                                 | 505 ms: 1.04x faster                                                |
| sqlglot_transpile        | 1.64 ms                                                | 1.58 ms: 1.04x faster                                               |
| logging_simple           | 6.18 us                                                | 5.96 us: 1.04x faster                                               |
| unpickle_pure_python     | 218 us                                                 | 211 us: 1.04x faster                                                |
| docutils                 | 2.70 sec                                               | 2.62 sec: 1.03x faster                                              |
| float                    | 80.7 ms                                                | 78.4 ms: 1.03x faster                                               |
| typing_runtime_protocols | 146 us                                                 | 142 us: 1.03x faster                                                |
| nqueens                  | 81.1 ms                                                | 78.9 ms: 1.03x faster                                               |
| deepcopy_memo            | 37.4 us                                                | 36.4 us: 1.03x faster                                               |
| dulwich_log              | 67.9 ms                                                | 66.2 ms: 1.03x faster                                               |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                                |
| mypy2                    | 344 ms                                                 | 336 ms: 1.02x faster                                                |
| bench_thread_pool        | 827 us                                                 | 810 us: 1.02x faster                                                |
| coroutines               | 22.4 ms                                                | 22.0 ms: 1.02x faster                                               |
| hexiom                   | 6.12 ms                                                | 6.02 ms: 1.02x faster                                               |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 703 ms: 1.02x faster                                                |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.67 ms: 1.02x faster                                               |
| xml_etree_process        | 58.6 ms                                                | 57.7 ms: 1.01x faster                                               |
| sqlglot_optimize         | 53.3 ms                                                | 52.6 ms: 1.01x faster                                               |
| async_tree_memoization   | 573 ms                                                 | 565 ms: 1.01x faster                                                |
| deepcopy                 | 355 us                                                 | 351 us: 1.01x faster                                                |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                |
| pprint_pformat           | 1.50 sec                                               | 1.48 sec: 1.01x faster                                              |
| pprint_safe_repr         | 735 ms                                                 | 727 ms: 1.01x faster                                                |
| spectral_norm            | 106 ms                                                 | 105 ms: 1.01x faster                                                |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                               |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                |
| json_dumps               | 9.85 ms                                                | 9.76 ms: 1.01x faster                                               |
| mako                     | 10.7 ms                                                | 10.6 ms: 1.01x faster                                               |
| regex_effbot             | 3.55 ms                                                | 3.52 ms: 1.01x faster                                               |
| xml_etree_generate       | 84.8 ms                                                | 84.3 ms: 1.01x faster                                               |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                               |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.01x slower                                              |
| pathlib                  | 18.5 ms                                                | 18.6 ms: 1.01x slower                                               |
| async_generators         | 440 ms                                                 | 444 ms: 1.01x slower                                                |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                               |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                |
| pickle_dict              | 31.6 us                                                | 31.9 us: 1.01x slower                                               |
| comprehensions           | 20.4 us                                                | 20.7 us: 1.01x slower                                               |
| pyflate                  | 450 ms                                                 | 457 ms: 1.02x slower                                                |
| json                     | 4.77 ms                                                | 4.85 ms: 1.02x slower                                               |
| regex_dna                | 209 ms                                                 | 212 ms: 1.02x slower                                                |
| logging_silent           | 99.1 ns                                                | 101 ns: 1.02x slower                                                |
| nbody                    | 88.8 ms                                                | 90.9 ms: 1.02x slower                                               |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                              |
| pickle_list              | 4.62 us                                                | 4.78 us: 1.04x slower                                               |
| scimark_sor              | 125 ms                                                 | 129 ms: 1.04x slower                                                |
| mdp                      | 2.57 sec                                               | 2.67 sec: 1.04x slower                                              |
| go                       | 136 ms                                                 | 141 ms: 1.04x slower                                                |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                               |
| unpack_sequence          | 44.8 ns                                                | 48.2 ns: 1.07x slower                                               |
| regex_v8                 | 22.3 ms                                                | 24.0 ms: 1.08x slower                                               |
| richards                 | 43.2 ms                                                | 48.6 ms: 1.12x slower                                               |
| richards_super           | 49.0 ms                                                | 55.4 ms: 1.13x slower                                               |
| telco                    | 6.87 ms                                                | 8.06 ms: 1.17x slower                                               |
| dask                     | 365 ms                                                 | 524 ms: 1.44x slower                                                |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                        |

Benchmark hidden because not significant (8): sqlite_synth, pickle, fannkuch, pycparser, bench_mp_pool, scimark_fft, unpickle_list, json_loads
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
