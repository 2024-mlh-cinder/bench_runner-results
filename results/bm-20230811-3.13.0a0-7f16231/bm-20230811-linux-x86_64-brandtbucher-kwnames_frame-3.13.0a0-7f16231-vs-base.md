
# Results vs. base

- fork: brandtbucher
- ref: kwnames_frame
- machine: linux-x86_64
- commit hash: 7f16231
- commit date: 2023-08-11
- overall geometric mean: 1.01x slower
- HPT reliability: 99.91%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.65 sec                                                              | 2.63 sec: 1.00x faster                                               |
| tornado_http   | 95.6 ms                                                               | 96.2 ms: 1.01x slower                                                |
| Geometric mean | (ref)                                                                 | 1.00x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 197 ms                                                                | 189 ms: 1.04x faster                                                 |
| float          | 78.9 ms                                                               | 80.2 ms: 1.02x slower                                                |
| nbody          | 89.2 ms                                                               | 93.9 ms: 1.05x slower                                                |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.73 ms                                                               | 3.55 ms: 1.05x faster                                                |
| regex_v8       | 26.1 ms                                                               | 25.1 ms: 1.04x faster                                                |
| regex_dna      | 222 ms                                                                | 213 ms: 1.04x faster                                                 |
| regex_compile  | 136 ms                                                                | 137 ms: 1.00x slower                                                 |
| Geometric mean | (ref)                                                                 | 1.03x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|---------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_list         | 4.57 us                                                               | 4.38 us: 1.04x faster                                                |
| unpickle_list       | 4.98 us                                                               | 4.89 us: 1.02x faster                                                |
| tomli_loads         | 2.15 sec                                                              | 2.12 sec: 1.02x faster                                               |
| pickle              | 10.6 us                                                               | 10.4 us: 1.01x faster                                                |
| xml_etree_iterparse | 102 ms                                                                | 104 ms: 1.01x slower                                                 |
| xml_etree_process   | 57.3 ms                                                               | 57.9 ms: 1.01x slower                                                |
| pickle_dict         | 30.6 us                                                               | 31.1 us: 1.02x slower                                                |
| json_loads          | 25.1 us                                                               | 25.5 us: 1.02x slower                                                |
| xml_etree_parse     | 150 ms                                                                | 153 ms: 1.02x slower                                                 |
| xml_etree_generate  | 82.7 ms                                                               | 84.6 ms: 1.02x slower                                                |
| unpickle            | 14.1 us                                                               | 15.0 us: 1.06x slower                                                |
| Geometric mean      | (ref)                                                                 | 1.00x slower                                                         |

Benchmark hidden because not significant (3): json_dumps, pickle_pure_python, unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 6.85 ms                                                               | 6.90 ms: 1.01x slower                                                |
| python_startup         | 9.36 ms                                                               | 9.42 ms: 1.01x slower                                                |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                         |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|-------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| scimark_sparse_mat_mult | 4.99 ms                                                               | 4.58 ms: 1.09x faster                                                |
| mdp                     | 2.70 sec                                                              | 2.55 sec: 1.06x faster                                               |
| regex_effbot            | 3.73 ms                                                               | 3.55 ms: 1.05x faster                                                |
| pickle_list             | 4.57 us                                                               | 4.38 us: 1.04x faster                                                |
| regex_v8                | 26.1 ms                                                               | 25.1 ms: 1.04x faster                                                |
| pidigits                | 197 ms                                                                | 189 ms: 1.04x faster                                                 |
| pycparser               | 1.21 sec                                                              | 1.17 sec: 1.04x faster                                               |
| regex_dna               | 222 ms                                                                | 213 ms: 1.04x faster                                                 |
| scimark_fft             | 366 ms                                                                | 354 ms: 1.04x faster                                                 |
| scimark_lu              | 113 ms                                                                | 110 ms: 1.03x faster                                                 |
| unpickle_list           | 4.98 us                                                               | 4.89 us: 1.02x faster                                                |
| tomli_loads             | 2.15 sec                                                              | 2.12 sec: 1.02x faster                                               |
| telco                   | 8.14 ms                                                               | 8.01 ms: 1.02x faster                                                |
| pickle                  | 10.6 us                                                               | 10.4 us: 1.01x faster                                                |
| async_generators        | 447 ms                                                                | 443 ms: 1.01x faster                                                 |
| docutils                | 2.65 sec                                                              | 2.63 sec: 1.00x faster                                               |
| nqueens                 | 81.6 ms                                                               | 81.9 ms: 1.00x slower                                                |
| regex_compile           | 136 ms                                                                | 137 ms: 1.00x slower                                                 |
| sqlglot_parse           | 1.27 ms                                                               | 1.28 ms: 1.00x slower                                                |
| dulwich_log             | 66.2 ms                                                               | 66.5 ms: 1.00x slower                                                |
| create_gc_cycles        | 1.48 ms                                                               | 1.49 ms: 1.00x slower                                                |
| pprint_safe_repr        | 725 ms                                                                | 729 ms: 1.00x slower                                                 |
| sqlglot_normalize       | 105 ms                                                                | 105 ms: 1.01x slower                                                 |
| bench_thread_pool       | 820 us                                                                | 825 us: 1.01x slower                                                 |
| mypy2                   | 338 ms                                                                | 340 ms: 1.01x slower                                                 |
| go                      | 139 ms                                                                | 140 ms: 1.01x slower                                                 |
| tornado_http            | 95.6 ms                                                               | 96.2 ms: 1.01x slower                                                |
| pprint_pformat          | 1.48 sec                                                              | 1.49 sec: 1.01x slower                                               |
| python_startup_no_site  | 6.85 ms                                                               | 6.90 ms: 1.01x slower                                                |
| python_startup          | 9.36 ms                                                               | 9.42 ms: 1.01x slower                                                |
| fannkuch                | 391 ms                                                                | 394 ms: 1.01x slower                                                 |
| unpack_sequence         | 40.3 ns                                                               | 40.6 ns: 1.01x slower                                                |
| pathlib                 | 18.8 ms                                                               | 19.0 ms: 1.01x slower                                                |
| comprehensions          | 20.9 us                                                               | 21.1 us: 1.01x slower                                                |
| xml_etree_iterparse     | 102 ms                                                                | 104 ms: 1.01x slower                                                 |
| meteor_contest          | 105 ms                                                                | 106 ms: 1.01x slower                                                 |
| logging_format          | 6.48 us                                                               | 6.56 us: 1.01x slower                                                |
| xml_etree_process       | 57.3 ms                                                               | 57.9 ms: 1.01x slower                                                |
| raytrace                | 272 ms                                                                | 276 ms: 1.01x slower                                                 |
| chaos                   | 60.1 ms                                                               | 61.0 ms: 1.01x slower                                                |
| deepcopy                | 349 us                                                                | 354 us: 1.02x slower                                                 |
| deepcopy_memo           | 37.0 us                                                               | 37.6 us: 1.02x slower                                                |
| float                   | 78.9 ms                                                               | 80.2 ms: 1.02x slower                                                |
| pickle_dict             | 30.6 us                                                               | 31.1 us: 1.02x slower                                                |
| crypto_pyaes            | 69.0 ms                                                               | 70.2 ms: 1.02x slower                                                |
| logging_silent          | 103 ns                                                                | 105 ns: 1.02x slower                                                 |
| json_loads              | 25.1 us                                                               | 25.5 us: 1.02x slower                                                |
| xml_etree_parse         | 150 ms                                                                | 153 ms: 1.02x slower                                                 |
| generators              | 28.7 ms                                                               | 29.3 ms: 1.02x slower                                                |
| logging_simple          | 5.86 us                                                               | 5.98 us: 1.02x slower                                                |
| xml_etree_generate      | 82.7 ms                                                               | 84.6 ms: 1.02x slower                                                |
| richards_super          | 53.5 ms                                                               | 54.8 ms: 1.02x slower                                                |
| json                    | 4.80 ms                                                               | 4.91 ms: 1.02x slower                                                |
| async_tree_none         | 431 ms                                                                | 448 ms: 1.04x slower                                                 |
| async_tree_cpu_io_mixed | 690 ms                                                                | 717 ms: 1.04x slower                                                 |
| async_tree_memoization  | 558 ms                                                                | 580 ms: 1.04x slower                                                 |
| spectral_norm           | 105 ms                                                                | 110 ms: 1.05x slower                                                 |
| coroutines              | 22.0 ms                                                               | 23.1 ms: 1.05x slower                                                |
| nbody                   | 89.2 ms                                                               | 93.9 ms: 1.05x slower                                                |
| async_tree_io           | 1.17 sec                                                              | 1.23 sec: 1.05x slower                                               |
| unpickle                | 14.1 us                                                               | 15.0 us: 1.06x slower                                                |
| gc_traversal            | 3.66 ms                                                               | 4.33 ms: 1.18x slower                                                |
| Geometric mean          | (ref)                                                                 | 1.01x slower                                                         |

Benchmark hidden because not significant (20): json_dumps, deltablue, richards, scimark_monte_carlo, deepcopy_reduce, scimark_sor, pickle_pure_python, mako, typing_runtime_protocols, hexiom, bench_mp_pool, asyncio_tcp_ssl, asyncio_tcp, pyflate, sqlglot_optimize, unpickle_pure_python, dask, coverage, sqlite_synth, sqlglot_transpile


# HPT report

- Reliability score: 99.91% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
