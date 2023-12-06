
# Results vs. base

- fork: brandtbucher
- ref: kwnames_again
- machine: linux-x86_64
- commit hash: 3276185
- commit date: 2023-08-10
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230825-linux-x86_64-python-4eae1e53425d3a816a26-3.13.0a0-4eae1e5 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.63 sec                                                              | 2.66 sec: 1.01x slower                                               |
| tornado_http   | 95.9 ms                                                               | 97.7 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230825-linux-x86_64-python-4eae1e53425d3a816a26-3.13.0a0-4eae1e5 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 80.3 ms                                                               | 79.3 ms: 1.01x faster                                                |
| nbody          | 91.6 ms                                                               | 92.5 ms: 1.01x slower                                                |
| pidigits       | 189 ms                                                                | 201 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230825-linux-x86_64-python-4eae1e53425d3a816a26-3.13.0a0-4eae1e5 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 136 ms                                                                | 140 ms: 1.03x slower                                                 |
| regex_effbot   | 3.61 ms                                                               | 3.76 ms: 1.04x slower                                                |
| regex_dna      | 214 ms                                                                | 224 ms: 1.04x slower                                                 |
| regex_v8       | 24.4 ms                                                               | 29.2 ms: 1.20x slower                                                |
| Geometric mean | (ref)                                                                 | 1.08x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230825-linux-x86_64-python-4eae1e53425d3a816a26-3.13.0a0-4eae1e5 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| xml_etree_parse      | 153 ms                                                                | 152 ms: 1.01x faster                                                 |
| pickle               | 10.8 us                                                               | 10.6 us: 1.01x faster                                                |
| pickle_dict          | 31.9 us                                                               | 32.1 us: 1.01x slower                                                |
| json_dumps           | 9.77 ms                                                               | 9.84 ms: 1.01x slower                                                |
| xml_etree_process    | 57.3 ms                                                               | 57.9 ms: 1.01x slower                                                |
| unpickle_pure_python | 218 us                                                                | 220 us: 1.01x slower                                                 |
| pickle_pure_python   | 303 us                                                                | 308 us: 1.02x slower                                                 |
| unpickle_list        | 5.02 us                                                               | 5.13 us: 1.02x slower                                                |
| tomli_loads          | 2.13 sec                                                              | 2.18 sec: 1.02x slower                                               |
| unpickle             | 14.3 us                                                               | 15.1 us: 1.06x slower                                                |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                         |

Benchmark hidden because not significant (4): pickle_list, xml_etree_iterparse, xml_etree_generate, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230825-linux-x86_64-python-4eae1e53425d3a816a26-3.13.0a0-4eae1e5 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 6.87 ms                                                               | 6.86 ms: 1.00x faster                                                |
| python_startup         | 9.38 ms                                                               | 9.38 ms: 1.00x slower                                                |
| Geometric mean         | (ref)                                                                 | 1.00x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230825-linux-x86_64-python-4eae1e53425d3a816a26-3.13.0a0-4eae1e5 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.9 ms                                                               | 11.3 ms: 1.04x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20230825-linux-x86_64-python-4eae1e53425d3a816a26-3.13.0a0-4eae1e5 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|--------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| gc_traversal             | 4.34 ms                                                               | 4.14 ms: 1.05x faster                                                |
| create_gc_cycles         | 1.51 ms                                                               | 1.46 ms: 1.03x faster                                                |
| telco                    | 8.12 ms                                                               | 7.95 ms: 1.02x faster                                                |
| fannkuch                 | 398 ms                                                                | 391 ms: 1.02x faster                                                 |
| async_generators         | 455 ms                                                                | 448 ms: 1.02x faster                                                 |
| float                    | 80.3 ms                                                               | 79.3 ms: 1.01x faster                                                |
| xml_etree_parse          | 153 ms                                                                | 152 ms: 1.01x faster                                                 |
| pickle                   | 10.8 us                                                               | 10.6 us: 1.01x faster                                                |
| richards                 | 49.5 ms                                                               | 49.0 ms: 1.01x faster                                                |
| mdp                      | 2.57 sec                                                              | 2.56 sec: 1.00x faster                                               |
| async_tree_io            | 1.19 sec                                                              | 1.19 sec: 1.00x faster                                               |
| python_startup_no_site   | 6.87 ms                                                               | 6.86 ms: 1.00x faster                                                |
| python_startup           | 9.38 ms                                                               | 9.38 ms: 1.00x slower                                                |
| nqueens                  | 81.9 ms                                                               | 82.3 ms: 1.01x slower                                                |
| pickle_dict              | 31.9 us                                                               | 32.1 us: 1.01x slower                                                |
| logging_silent           | 104 ns                                                                | 104 ns: 1.01x slower                                                 |
| meteor_contest           | 105 ms                                                                | 105 ms: 1.01x slower                                                 |
| bench_thread_pool        | 819 us                                                                | 825 us: 1.01x slower                                                 |
| json_dumps               | 9.77 ms                                                               | 9.84 ms: 1.01x slower                                                |
| asyncio_tcp              | 480 ms                                                                | 484 ms: 1.01x slower                                                 |
| nbody                    | 91.6 ms                                                               | 92.5 ms: 1.01x slower                                                |
| xml_etree_process        | 57.3 ms                                                               | 57.9 ms: 1.01x slower                                                |
| pyflate                  | 452 ms                                                                | 457 ms: 1.01x slower                                                 |
| docutils                 | 2.63 sec                                                              | 2.66 sec: 1.01x slower                                               |
| async_tree_memoization   | 565 ms                                                                | 572 ms: 1.01x slower                                                 |
| unpickle_pure_python     | 218 us                                                                | 220 us: 1.01x slower                                                 |
| richards_super           | 54.4 ms                                                               | 55.1 ms: 1.01x slower                                                |
| dask                     | 527 ms                                                                | 535 ms: 1.01x slower                                                 |
| coroutines               | 22.4 ms                                                               | 22.7 ms: 1.02x slower                                                |
| crypto_pyaes             | 69.1 ms                                                               | 70.2 ms: 1.02x slower                                                |
| mypy2                    | 338 ms                                                                | 344 ms: 1.02x slower                                                 |
| deepcopy_reduce          | 3.13 us                                                               | 3.19 us: 1.02x slower                                                |
| pickle_pure_python       | 303 us                                                                | 308 us: 1.02x slower                                                 |
| scimark_monte_carlo      | 66.2 ms                                                               | 67.3 ms: 1.02x slower                                                |
| sqlglot_normalize        | 105 ms                                                                | 107 ms: 1.02x slower                                                 |
| tornado_http             | 95.9 ms                                                               | 97.7 ms: 1.02x slower                                                |
| spectral_norm            | 107 ms                                                                | 109 ms: 1.02x slower                                                 |
| sqlglot_optimize         | 52.6 ms                                                               | 53.7 ms: 1.02x slower                                                |
| typing_runtime_protocols | 147 us                                                                | 151 us: 1.02x slower                                                 |
| unpickle_list            | 5.02 us                                                               | 5.13 us: 1.02x slower                                                |
| deltablue                | 3.30 ms                                                               | 3.38 ms: 1.02x slower                                                |
| sqlglot_transpile        | 1.58 ms                                                               | 1.62 ms: 1.02x slower                                                |
| tomli_loads              | 2.13 sec                                                              | 2.18 sec: 1.02x slower                                               |
| dulwich_log              | 66.5 ms                                                               | 68.1 ms: 1.02x slower                                                |
| comprehensions           | 21.0 us                                                               | 21.5 us: 1.03x slower                                                |
| regex_compile            | 136 ms                                                                | 140 ms: 1.03x slower                                                 |
| sqlglot_parse            | 1.27 ms                                                               | 1.30 ms: 1.03x slower                                                |
| coverage                 | 85.1 ms                                                               | 87.5 ms: 1.03x slower                                                |
| pprint_pformat           | 1.48 sec                                                              | 1.52 sec: 1.03x slower                                               |
| pprint_safe_repr         | 724 ms                                                                | 745 ms: 1.03x slower                                                 |
| chaos                    | 59.8 ms                                                               | 61.6 ms: 1.03x slower                                                |
| scimark_fft              | 348 ms                                                                | 359 ms: 1.03x slower                                                 |
| mako                     | 10.9 ms                                                               | 11.3 ms: 1.04x slower                                                |
| scimark_lu               | 108 ms                                                                | 112 ms: 1.04x slower                                                 |
| deepcopy                 | 348 us                                                                | 361 us: 1.04x slower                                                 |
| regex_effbot             | 3.61 ms                                                               | 3.76 ms: 1.04x slower                                                |
| pycparser                | 1.18 sec                                                              | 1.22 sec: 1.04x slower                                               |
| regex_dna                | 214 ms                                                                | 224 ms: 1.04x slower                                                 |
| hexiom                   | 6.11 ms                                                               | 6.39 ms: 1.04x slower                                                |
| deepcopy_memo            | 36.9 us                                                               | 38.7 us: 1.05x slower                                                |
| unpickle                 | 14.3 us                                                               | 15.1 us: 1.06x slower                                                |
| scimark_sparse_mat_mult  | 4.60 ms                                                               | 4.87 ms: 1.06x slower                                                |
| generators               | 28.2 ms                                                               | 29.9 ms: 1.06x slower                                                |
| pidigits                 | 189 ms                                                                | 201 ms: 1.06x slower                                                 |
| logging_simple           | 5.90 us                                                               | 6.29 us: 1.07x slower                                                |
| logging_format           | 6.46 us                                                               | 7.02 us: 1.09x slower                                                |
| regex_v8                 | 24.4 ms                                                               | 29.2 ms: 1.20x slower                                                |
| unpack_sequence          | 44.6 ns                                                               | 53.6 ns: 1.20x slower                                                |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                         |

Benchmark hidden because not significant (14): sqlite_synth, raytrace, pickle_list, xml_etree_iterparse, xml_etree_generate, asyncio_tcp_ssl, json, json_loads, go, pathlib, bench_mp_pool, scimark_sor, async_tree_cpu_io_mixed, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
