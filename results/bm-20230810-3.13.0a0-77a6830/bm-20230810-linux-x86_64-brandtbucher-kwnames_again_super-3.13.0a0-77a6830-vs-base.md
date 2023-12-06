
# Results vs. base

- fork: brandtbucher
- ref: kwnames_again_super
- machine: linux-x86_64
- commit hash: 77a6830
- commit date: 2023-08-10
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.65 sec                                                              | 2.74 sec: 1.04x slower                                                     |
| tornado_http   | 95.6 ms                                                               | 104 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                                 | 1.06x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 197 ms                                                                | 189 ms: 1.04x faster                                                       |
| nbody          | 89.2 ms                                                               | 91.3 ms: 1.02x slower                                                      |
| float          | 78.9 ms                                                               | 84.5 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 222 ms                                                                | 211 ms: 1.05x faster                                                       |
| regex_v8       | 26.1 ms                                                               | 25.0 ms: 1.04x faster                                                      |
| regex_effbot   | 3.73 ms                                                               | 3.61 ms: 1.03x faster                                                      |
| regex_compile  | 136 ms                                                                | 149 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                                 | 1.01x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| xml_etree_parse      | 150 ms                                                                | 152 ms: 1.02x slower                                                       |
| pickle               | 10.6 us                                                               | 10.8 us: 1.02x slower                                                      |
| xml_etree_iterparse  | 102 ms                                                                | 105 ms: 1.02x slower                                                       |
| json_loads           | 25.1 us                                                               | 25.6 us: 1.02x slower                                                      |
| xml_etree_generate   | 82.7 ms                                                               | 85.0 ms: 1.03x slower                                                      |
| pickle_list          | 4.57 us                                                               | 4.72 us: 1.03x slower                                                      |
| unpickle             | 14.1 us                                                               | 14.6 us: 1.03x slower                                                      |
| tomli_loads          | 2.15 sec                                                              | 2.25 sec: 1.05x slower                                                     |
| xml_etree_process    | 57.3 ms                                                               | 60.0 ms: 1.05x slower                                                      |
| pickle_pure_python   | 303 us                                                                | 321 us: 1.06x slower                                                       |
| unpickle_pure_python | 215 us                                                                | 228 us: 1.06x slower                                                       |
| pickle_dict          | 30.6 us                                                               | 33.3 us: 1.09x slower                                                      |
| Geometric mean       | (ref)                                                                 | 1.03x slower                                                               |

Benchmark hidden because not significant (2): json_dumps, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 6.85 ms                                                               | 6.90 ms: 1.01x slower                                                      |
| python_startup         | 9.36 ms                                                               | 9.46 ms: 1.01x slower                                                      |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 10.8 ms                                                               | 11.4 ms: 1.05x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20230828-linux-x86_64-python-47d7eba889bc03884744-3.13.0a0-47d7eba | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|--------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna                | 222 ms                                                                | 211 ms: 1.05x faster                                                       |
| regex_v8                 | 26.1 ms                                                               | 25.0 ms: 1.04x faster                                                      |
| pidigits                 | 197 ms                                                                | 189 ms: 1.04x faster                                                       |
| regex_effbot             | 3.73 ms                                                               | 3.61 ms: 1.03x faster                                                      |
| scimark_sparse_mat_mult  | 4.99 ms                                                               | 4.92 ms: 1.01x faster                                                      |
| mdp                      | 2.70 sec                                                              | 2.69 sec: 1.01x faster                                                     |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.80 sec: 1.01x slower                                                     |
| python_startup_no_site   | 6.85 ms                                                               | 6.90 ms: 1.01x slower                                                      |
| python_startup           | 9.36 ms                                                               | 9.46 ms: 1.01x slower                                                      |
| coverage                 | 85.7 ms                                                               | 86.9 ms: 1.01x slower                                                      |
| scimark_lu               | 113 ms                                                                | 114 ms: 1.01x slower                                                       |
| asyncio_tcp              | 489 ms                                                                | 496 ms: 1.02x slower                                                       |
| xml_etree_parse          | 150 ms                                                                | 152 ms: 1.02x slower                                                       |
| pickle                   | 10.6 us                                                               | 10.8 us: 1.02x slower                                                      |
| create_gc_cycles         | 1.48 ms                                                               | 1.51 ms: 1.02x slower                                                      |
| scimark_fft              | 366 ms                                                                | 372 ms: 1.02x slower                                                       |
| meteor_contest           | 105 ms                                                                | 107 ms: 1.02x slower                                                       |
| json                     | 4.80 ms                                                               | 4.90 ms: 1.02x slower                                                      |
| xml_etree_iterparse      | 102 ms                                                                | 105 ms: 1.02x slower                                                       |
| json_loads               | 25.1 us                                                               | 25.6 us: 1.02x slower                                                      |
| nbody                    | 89.2 ms                                                               | 91.3 ms: 1.02x slower                                                      |
| pycparser                | 1.21 sec                                                              | 1.24 sec: 1.02x slower                                                     |
| sqlite_synth             | 2.73 us                                                               | 2.80 us: 1.03x slower                                                      |
| async_tree_io            | 1.17 sec                                                              | 1.20 sec: 1.03x slower                                                     |
| telco                    | 8.14 ms                                                               | 8.36 ms: 1.03x slower                                                      |
| xml_etree_generate       | 82.7 ms                                                               | 85.0 ms: 1.03x slower                                                      |
| bench_thread_pool        | 820 us                                                                | 844 us: 1.03x slower                                                       |
| pickle_list              | 4.57 us                                                               | 4.72 us: 1.03x slower                                                      |
| unpickle                 | 14.1 us                                                               | 14.6 us: 1.03x slower                                                      |
| nqueens                  | 81.6 ms                                                               | 84.3 ms: 1.03x slower                                                      |
| async_tree_cpu_io_mixed  | 690 ms                                                                | 714 ms: 1.03x slower                                                       |
| comprehensions           | 20.9 us                                                               | 21.6 us: 1.03x slower                                                      |
| docutils                 | 2.65 sec                                                              | 2.74 sec: 1.04x slower                                                     |
| async_tree_memoization   | 558 ms                                                                | 579 ms: 1.04x slower                                                       |
| async_tree_none          | 431 ms                                                                | 449 ms: 1.04x slower                                                       |
| pprint_safe_repr         | 725 ms                                                                | 756 ms: 1.04x slower                                                       |
| pprint_pformat           | 1.48 sec                                                              | 1.54 sec: 1.04x slower                                                     |
| tomli_loads              | 2.15 sec                                                              | 2.25 sec: 1.05x slower                                                     |
| scimark_monte_carlo      | 66.7 ms                                                               | 69.8 ms: 1.05x slower                                                      |
| mako                     | 10.8 ms                                                               | 11.4 ms: 1.05x slower                                                      |
| gc_traversal             | 3.66 ms                                                               | 3.84 ms: 1.05x slower                                                      |
| fannkuch                 | 391 ms                                                                | 410 ms: 1.05x slower                                                       |
| xml_etree_process        | 57.3 ms                                                               | 60.0 ms: 1.05x slower                                                      |
| pyflate                  | 446 ms                                                                | 468 ms: 1.05x slower                                                       |
| mypy2                    | 338 ms                                                                | 356 ms: 1.05x slower                                                       |
| go                       | 139 ms                                                                | 147 ms: 1.06x slower                                                       |
| pickle_pure_python       | 303 us                                                                | 321 us: 1.06x slower                                                       |
| dask                     | 523 ms                                                                | 554 ms: 1.06x slower                                                       |
| richards_super           | 53.5 ms                                                               | 56.7 ms: 1.06x slower                                                      |
| typing_runtime_protocols | 143 us                                                                | 152 us: 1.06x slower                                                       |
| richards                 | 47.8 ms                                                               | 50.7 ms: 1.06x slower                                                      |
| unpickle_pure_python     | 215 us                                                                | 228 us: 1.06x slower                                                       |
| crypto_pyaes             | 69.0 ms                                                               | 73.2 ms: 1.06x slower                                                      |
| logging_silent           | 103 ns                                                                | 109 ns: 1.06x slower                                                       |
| scimark_sor              | 122 ms                                                                | 130 ms: 1.07x slower                                                       |
| deepcopy_reduce          | 3.17 us                                                               | 3.38 us: 1.07x slower                                                      |
| float                    | 78.9 ms                                                               | 84.5 ms: 1.07x slower                                                      |
| raytrace                 | 272 ms                                                                | 291 ms: 1.07x slower                                                       |
| sqlglot_optimize         | 52.7 ms                                                               | 56.5 ms: 1.07x slower                                                      |
| sqlglot_transpile        | 1.59 ms                                                               | 1.70 ms: 1.07x slower                                                      |
| deepcopy                 | 349 us                                                                | 375 us: 1.07x slower                                                       |
| sqlglot_parse            | 1.27 ms                                                               | 1.37 ms: 1.08x slower                                                      |
| coroutines               | 22.0 ms                                                               | 23.7 ms: 1.08x slower                                                      |
| sqlglot_normalize        | 105 ms                                                                | 113 ms: 1.08x slower                                                       |
| chaos                    | 60.1 ms                                                               | 64.9 ms: 1.08x slower                                                      |
| deepcopy_memo            | 37.0 us                                                               | 40.0 us: 1.08x slower                                                      |
| tornado_http             | 95.6 ms                                                               | 104 ms: 1.08x slower                                                       |
| hexiom                   | 6.07 ms                                                               | 6.60 ms: 1.09x slower                                                      |
| pickle_dict              | 30.6 us                                                               | 33.3 us: 1.09x slower                                                      |
| dulwich_log              | 66.2 ms                                                               | 72.2 ms: 1.09x slower                                                      |
| regex_compile            | 136 ms                                                                | 149 ms: 1.09x slower                                                       |
| spectral_norm            | 105 ms                                                                | 115 ms: 1.10x slower                                                       |
| generators               | 28.7 ms                                                               | 32.1 ms: 1.12x slower                                                      |
| deltablue                | 3.33 ms                                                               | 3.77 ms: 1.13x slower                                                      |
| logging_simple           | 5.86 us                                                               | 6.94 us: 1.18x slower                                                      |
| logging_format           | 6.48 us                                                               | 7.82 us: 1.21x slower                                                      |
| unpack_sequence          | 40.3 ns                                                               | 51.0 ns: 1.27x slower                                                      |
| Geometric mean           | (ref)                                                                 | 1.05x slower                                                               |

Benchmark hidden because not significant (5): pathlib, json_dumps, bench_mp_pool, unpickle_list, async_generators


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
