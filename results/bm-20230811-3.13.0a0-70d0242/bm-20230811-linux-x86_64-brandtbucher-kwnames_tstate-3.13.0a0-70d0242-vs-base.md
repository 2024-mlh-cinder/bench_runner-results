
# Results vs. base

- fork: brandtbucher
- ref: kwnames_tstate
- machine: linux-x86_64
- commit hash: 70d0242
- commit date: 2023-08-11
- overall geometric mean: 1.01x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.65 sec                                                              | 2.63 sec: 1.01x faster                                                |
| tornado_http   | 95.6 ms                                                               | 96.5 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                                 | 1.00x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 197 ms                                                                | 189 ms: 1.04x faster                                                  |
| float          | 78.9 ms                                                               | 81.4 ms: 1.03x slower                                                 |
| nbody          | 89.2 ms                                                               | 96.1 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 222 ms                                                                | 219 ms: 1.01x faster                                                  |
| regex_v8       | 26.1 ms                                                               | 25.9 ms: 1.01x faster                                                 |
| regex_compile  | 136 ms                                                                | 137 ms: 1.00x slower                                                  |
| regex_effbot   | 3.73 ms                                                               | 3.76 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_iterparse  | 102 ms                                                                | 103 ms: 1.01x slower                                                  |
| xml_etree_process    | 57.3 ms                                                               | 57.7 ms: 1.01x slower                                                 |
| xml_etree_generate   | 82.7 ms                                                               | 83.7 ms: 1.01x slower                                                 |
| json_loads           | 25.1 us                                                               | 25.4 us: 1.01x slower                                                 |
| unpickle_pure_python | 215 us                                                                | 218 us: 1.01x slower                                                  |
| xml_etree_parse      | 150 ms                                                                | 152 ms: 1.01x slower                                                  |
| tomli_loads          | 2.15 sec                                                              | 2.19 sec: 1.02x slower                                                |
| pickle               | 10.6 us                                                               | 10.9 us: 1.03x slower                                                 |
| pickle_dict          | 30.6 us                                                               | 31.9 us: 1.04x slower                                                 |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                          |

Benchmark hidden because not significant (5): pickle_list, pickle_pure_python, unpickle_list, json_dumps, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.85 ms                                                               | 6.88 ms: 1.00x slower                                                 |
| python_startup         | 9.36 ms                                                               | 9.41 ms: 1.01x slower                                                 |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|-----------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.8 ms                                                               | 11.2 ms: 1.03x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|--------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mdp                      | 2.70 sec                                                              | 2.59 sec: 1.04x faster                                                |
| pidigits                 | 197 ms                                                                | 189 ms: 1.04x faster                                                  |
| scimark_lu               | 113 ms                                                                | 109 ms: 1.03x faster                                                  |
| pycparser                | 1.21 sec                                                              | 1.18 sec: 1.03x faster                                                |
| richards                 | 47.8 ms                                                               | 46.7 ms: 1.02x faster                                                 |
| scimark_sparse_mat_mult  | 4.99 ms                                                               | 4.88 ms: 1.02x faster                                                 |
| nqueens                  | 81.6 ms                                                               | 80.5 ms: 1.01x faster                                                 |
| regex_dna                | 222 ms                                                                | 219 ms: 1.01x faster                                                  |
| pathlib                  | 18.8 ms                                                               | 18.6 ms: 1.01x faster                                                 |
| regex_v8                 | 26.1 ms                                                               | 25.9 ms: 1.01x faster                                                 |
| docutils                 | 2.65 sec                                                              | 2.63 sec: 1.01x faster                                                |
| pprint_safe_repr         | 725 ms                                                                | 722 ms: 1.00x faster                                                  |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.80 sec: 1.00x slower                                                |
| regex_compile            | 136 ms                                                                | 137 ms: 1.00x slower                                                  |
| mypy2                    | 338 ms                                                                | 339 ms: 1.00x slower                                                  |
| python_startup_no_site   | 6.85 ms                                                               | 6.88 ms: 1.00x slower                                                 |
| python_startup           | 9.36 ms                                                               | 9.41 ms: 1.01x slower                                                 |
| sqlglot_parse            | 1.27 ms                                                               | 1.28 ms: 1.01x slower                                                 |
| chaos                    | 60.1 ms                                                               | 60.5 ms: 1.01x slower                                                 |
| sqlglot_transpile        | 1.59 ms                                                               | 1.60 ms: 1.01x slower                                                 |
| xml_etree_iterparse      | 102 ms                                                                | 103 ms: 1.01x slower                                                  |
| crypto_pyaes             | 69.0 ms                                                               | 69.5 ms: 1.01x slower                                                 |
| fannkuch                 | 391 ms                                                                | 394 ms: 1.01x slower                                                  |
| xml_etree_process        | 57.3 ms                                                               | 57.7 ms: 1.01x slower                                                 |
| hexiom                   | 6.07 ms                                                               | 6.12 ms: 1.01x slower                                                 |
| meteor_contest           | 105 ms                                                                | 106 ms: 1.01x slower                                                  |
| tornado_http             | 95.6 ms                                                               | 96.5 ms: 1.01x slower                                                 |
| sqlglot_optimize         | 52.7 ms                                                               | 53.2 ms: 1.01x slower                                                 |
| regex_effbot             | 3.73 ms                                                               | 3.76 ms: 1.01x slower                                                 |
| dulwich_log              | 66.2 ms                                                               | 66.9 ms: 1.01x slower                                                 |
| xml_etree_generate       | 82.7 ms                                                               | 83.7 ms: 1.01x slower                                                 |
| async_generators         | 447 ms                                                                | 453 ms: 1.01x slower                                                  |
| scimark_monte_carlo      | 66.7 ms                                                               | 67.5 ms: 1.01x slower                                                 |
| json_loads               | 25.1 us                                                               | 25.4 us: 1.01x slower                                                 |
| sqlglot_normalize        | 105 ms                                                                | 106 ms: 1.01x slower                                                  |
| deepcopy                 | 349 us                                                                | 354 us: 1.01x slower                                                  |
| unpickle_pure_python     | 215 us                                                                | 218 us: 1.01x slower                                                  |
| deepcopy_memo            | 37.0 us                                                               | 37.5 us: 1.01x slower                                                 |
| xml_etree_parse          | 150 ms                                                                | 152 ms: 1.01x slower                                                  |
| go                       | 139 ms                                                                | 141 ms: 1.01x slower                                                  |
| tomli_loads              | 2.15 sec                                                              | 2.19 sec: 1.02x slower                                                |
| scimark_sor              | 122 ms                                                                | 124 ms: 1.02x slower                                                  |
| create_gc_cycles         | 1.48 ms                                                               | 1.51 ms: 1.02x slower                                                 |
| json                     | 4.80 ms                                                               | 4.89 ms: 1.02x slower                                                 |
| raytrace                 | 272 ms                                                                | 277 ms: 1.02x slower                                                  |
| async_tree_cpu_io_mixed  | 690 ms                                                                | 704 ms: 1.02x slower                                                  |
| logging_simple           | 5.86 us                                                               | 5.98 us: 1.02x slower                                                 |
| async_tree_memoization   | 558 ms                                                                | 570 ms: 1.02x slower                                                  |
| logging_format           | 6.48 us                                                               | 6.62 us: 1.02x slower                                                 |
| asyncio_tcp              | 489 ms                                                                | 499 ms: 1.02x slower                                                  |
| logging_silent           | 103 ns                                                                | 105 ns: 1.02x slower                                                  |
| async_tree_none          | 431 ms                                                                | 442 ms: 1.03x slower                                                  |
| coroutines               | 22.0 ms                                                               | 22.6 ms: 1.03x slower                                                 |
| pickle                   | 10.6 us                                                               | 10.9 us: 1.03x slower                                                 |
| pyflate                  | 446 ms                                                                | 458 ms: 1.03x slower                                                  |
| async_tree_io            | 1.17 sec                                                              | 1.20 sec: 1.03x slower                                                |
| typing_runtime_protocols | 143 us                                                                | 147 us: 1.03x slower                                                  |
| mako                     | 10.8 ms                                                               | 11.2 ms: 1.03x slower                                                 |
| float                    | 78.9 ms                                                               | 81.4 ms: 1.03x slower                                                 |
| pickle_dict              | 30.6 us                                                               | 31.9 us: 1.04x slower                                                 |
| spectral_norm            | 105 ms                                                                | 110 ms: 1.05x slower                                                  |
| generators               | 28.7 ms                                                               | 30.2 ms: 1.05x slower                                                 |
| nbody                    | 89.2 ms                                                               | 96.1 ms: 1.08x slower                                                 |
| unpack_sequence          | 40.3 ns                                                               | 45.5 ns: 1.13x slower                                                 |
| gc_traversal             | 3.66 ms                                                               | 4.25 ms: 1.16x slower                                                 |
| Geometric mean           | (ref)                                                                 | 1.01x slower                                                          |

Benchmark hidden because not significant (17): scimark_fft, sqlite_synth, pickle_list, deltablue, pprint_pformat, comprehensions, pickle_pure_python, coverage, unpickle_list, bench_mp_pool, telco, deepcopy_reduce, bench_thread_pool, richards_super, json_dumps, dask, unpickle


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
