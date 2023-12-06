
# Results vs. 3.12.0

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: linux-x86_64
- commit hash: 1ad9bed
- commit date: 2023-08-27
- overall geometric mean: 1.01x faster
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.61 sec: 1.04x faster                                                      |
| tornado_http   | 99.6 ms                                                | 95.3 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                  | 1.04x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 80.4 ms: 1.00x faster                                                       |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                        |
| nbody          | 88.8 ms                                                | 91.3 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                  | 1.01x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 135 ms: 1.06x faster                                                        |
| regex_effbot   | 3.55 ms                                                | 3.45 ms: 1.03x faster                                                       |
| regex_dna      | 209 ms                                                 | 204 ms: 1.02x faster                                                        |
| regex_v8       | 22.3 ms                                                | 23.1 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                  | 1.02x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.11 sec: 1.05x faster                                                      |
| pickle               | 10.6 us                                                | 10.1 us: 1.04x faster                                                       |
| pickle_dict          | 31.6 us                                                | 30.4 us: 1.04x faster                                                       |
| unpickle             | 15.0 us                                                | 14.4 us: 1.04x faster                                                       |
| unpickle_pure_python | 218 us                                                 | 212 us: 1.03x faster                                                        |
| pickle_pure_python   | 309 us                                                 | 301 us: 1.03x faster                                                        |
| xml_etree_process    | 58.6 ms                                                | 57.5 ms: 1.02x faster                                                       |
| xml_etree_parse      | 154 ms                                                 | 151 ms: 1.02x faster                                                        |
| xml_etree_generate   | 84.8 ms                                                | 83.4 ms: 1.02x faster                                                       |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                        |
| json_dumps           | 9.85 ms                                                | 9.75 ms: 1.01x faster                                                       |
| unpickle_list        | 4.95 us                                                | 5.04 us: 1.02x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                                |

Benchmark hidden because not significant (2): json_loads, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                       |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence          | 44.8 ns                                                | 40.5 ns: 1.11x faster                                                       |
| crypto_pyaes             | 77.2 ms                                                | 69.8 ms: 1.11x faster                                                       |
| coverage                 | 94.2 ms                                                | 85.6 ms: 1.10x faster                                                       |
| generators               | 31.1 ms                                                | 28.5 ms: 1.09x faster                                                       |
| asyncio_tcp              | 526 ms                                                 | 486 ms: 1.08x faster                                                        |
| async_tree_none          | 469 ms                                                 | 437 ms: 1.08x faster                                                        |
| logging_format           | 6.90 us                                                | 6.43 us: 1.07x faster                                                       |
| raytrace                 | 294 ms                                                 | 275 ms: 1.07x faster                                                        |
| scimark_monte_carlo      | 71.0 ms                                                | 66.7 ms: 1.06x faster                                                       |
| regex_compile            | 144 ms                                                 | 135 ms: 1.06x faster                                                        |
| deltablue                | 3.52 ms                                                | 3.33 ms: 1.06x faster                                                       |
| logging_simple           | 6.18 us                                                | 5.86 us: 1.05x faster                                                       |
| chaos                    | 63.5 ms                                                | 60.3 ms: 1.05x faster                                                       |
| tomli_loads              | 2.22 sec                                               | 2.11 sec: 1.05x faster                                                      |
| pickle                   | 10.6 us                                                | 10.1 us: 1.04x faster                                                       |
| tornado_http             | 99.6 ms                                                | 95.3 ms: 1.04x faster                                                       |
| scimark_lu               | 114 ms                                                 | 109 ms: 1.04x faster                                                        |
| sqlglot_parse            | 1.32 ms                                                | 1.27 ms: 1.04x faster                                                       |
| pickle_dict              | 31.6 us                                                | 30.4 us: 1.04x faster                                                       |
| sqlglot_transpile        | 1.64 ms                                                | 1.58 ms: 1.04x faster                                                       |
| unpickle                 | 15.0 us                                                | 14.4 us: 1.04x faster                                                       |
| docutils                 | 2.70 sec                                               | 2.61 sec: 1.04x faster                                                      |
| deepcopy                 | 355 us                                                 | 343 us: 1.04x faster                                                        |
| sqlglot_normalize        | 107 ms                                                 | 104 ms: 1.03x faster                                                        |
| dulwich_log              | 67.9 ms                                                | 66.0 ms: 1.03x faster                                                       |
| regex_effbot             | 3.55 ms                                                | 3.45 ms: 1.03x faster                                                       |
| unpickle_pure_python     | 218 us                                                 | 212 us: 1.03x faster                                                        |
| pickle_pure_python       | 309 us                                                 | 301 us: 1.03x faster                                                        |
| deepcopy_reduce          | 3.14 us                                                | 3.05 us: 1.03x faster                                                       |
| pprint_safe_repr         | 735 ms                                                 | 716 ms: 1.03x faster                                                        |
| pprint_pformat           | 1.50 sec                                               | 1.46 sec: 1.03x faster                                                      |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 698 ms: 1.02x faster                                                        |
| regex_dna                | 209 ms                                                 | 204 ms: 1.02x faster                                                        |
| async_tree_memoization   | 573 ms                                                 | 562 ms: 1.02x faster                                                        |
| sqlglot_optimize         | 53.3 ms                                                | 52.3 ms: 1.02x faster                                                       |
| xml_etree_process        | 58.6 ms                                                | 57.5 ms: 1.02x faster                                                       |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.02x faster                                                        |
| xml_etree_generate       | 84.8 ms                                                | 83.4 ms: 1.02x faster                                                       |
| mypy2                    | 344 ms                                                 | 338 ms: 1.02x faster                                                        |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.02x faster                                                        |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.67 ms: 1.02x faster                                                       |
| scimark_fft              | 358 ms                                                 | 354 ms: 1.01x faster                                                        |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                        |
| bench_thread_pool        | 827 us                                                 | 816 us: 1.01x faster                                                        |
| nqueens                  | 81.1 ms                                                | 80.2 ms: 1.01x faster                                                       |
| typing_runtime_protocols | 146 us                                                 | 144 us: 1.01x faster                                                        |
| json_dumps               | 9.85 ms                                                | 9.75 ms: 1.01x faster                                                       |
| deepcopy_memo            | 37.4 us                                                | 37.1 us: 1.01x faster                                                       |
| python_startup_no_site   | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                       |
| mdp                      | 2.57 sec                                               | 2.55 sec: 1.01x faster                                                      |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                                       |
| meteor_contest           | 105 ms                                                 | 104 ms: 1.01x faster                                                        |
| float                    | 80.7 ms                                                | 80.4 ms: 1.00x faster                                                       |
| spectral_norm            | 106 ms                                                 | 106 ms: 1.00x faster                                                        |
| pyflate                  | 450 ms                                                 | 449 ms: 1.00x faster                                                        |
| hexiom                   | 6.12 ms                                                | 6.10 ms: 1.00x faster                                                       |
| comprehensions           | 20.4 us                                                | 20.6 us: 1.01x slower                                                       |
| create_gc_cycles         | 1.52 ms                                                | 1.53 ms: 1.01x slower                                                       |
| fannkuch                 | 387 ms                                                 | 391 ms: 1.01x slower                                                        |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                       |
| async_generators         | 440 ms                                                 | 446 ms: 1.01x slower                                                        |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                        |
| json                     | 4.77 ms                                                | 4.85 ms: 1.02x slower                                                       |
| unpickle_list            | 4.95 us                                                | 5.04 us: 1.02x slower                                                       |
| nbody                    | 88.8 ms                                                | 91.3 ms: 1.03x slower                                                       |
| pycparser                | 1.15 sec                                               | 1.18 sec: 1.03x slower                                                      |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                      |
| logging_silent           | 99.1 ns                                                | 102 ns: 1.03x slower                                                        |
| regex_v8                 | 22.3 ms                                                | 23.1 ms: 1.04x slower                                                       |
| go                       | 136 ms                                                 | 141 ms: 1.04x slower                                                        |
| gc_traversal             | 3.84 ms                                                | 4.01 ms: 1.04x slower                                                       |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                       |
| coroutines               | 22.4 ms                                                | 24.0 ms: 1.07x slower                                                       |
| richards_super           | 49.0 ms                                                | 53.7 ms: 1.10x slower                                                       |
| richards                 | 43.2 ms                                                | 47.8 ms: 1.11x slower                                                       |
| telco                    | 6.87 ms                                                | 8.16 ms: 1.19x slower                                                       |
| dask                     | 365 ms                                                 | 522 ms: 1.43x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                                |

Benchmark hidden because not significant (5): json_loads, asyncio_tcp_ssl, bench_mp_pool, pickle_list, pathlib
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
