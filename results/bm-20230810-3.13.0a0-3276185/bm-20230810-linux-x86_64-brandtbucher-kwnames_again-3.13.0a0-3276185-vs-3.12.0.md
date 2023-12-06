
# Results vs. 3.12.0

- fork: brandtbucher
- ref: kwnames_again
- machine: linux-x86_64
- commit hash: 3276185
- commit date: 2023-08-10
- overall geometric mean: 1.02x slower
- HPT reliability: 82.54%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.66 sec: 1.01x faster                                               |
| tornado_http   | 99.6 ms                                                | 97.7 ms: 1.02x faster                                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.3 ms: 1.02x faster                                                |
| nbody          | 88.8 ms                                                | 92.5 ms: 1.04x slower                                                |
| pidigits       | 187 ms                                                 | 201 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 140 ms: 1.03x faster                                                 |
| regex_effbot   | 3.55 ms                                                | 3.76 ms: 1.06x slower                                                |
| regex_dna      | 209 ms                                                 | 224 ms: 1.07x slower                                                 |
| regex_v8       | 22.3 ms                                                | 29.2 ms: 1.31x slower                                                |
| Geometric mean | (ref)                                                  | 1.10x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| xml_etree_generate   | 84.8 ms                                                | 83.4 ms: 1.02x faster                                                |
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                               |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                 |
| xml_etree_process    | 58.6 ms                                                | 57.9 ms: 1.01x faster                                                |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                 |
| pickle               | 10.6 us                                                | 10.6 us: 1.00x slower                                                |
| unpickle_pure_python | 218 us                                                 | 220 us: 1.01x slower                                                 |
| pickle_dict          | 31.6 us                                                | 32.1 us: 1.01x slower                                                |
| unpickle_list        | 4.95 us                                                | 5.13 us: 1.04x slower                                                |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                         |

Benchmark hidden because not significant (5): pickle_pure_python, json_dumps, json_loads, pickle_list, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.38 ms: 1.01x faster                                                |
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                                |
| Geometric mean         | (ref)                                                  | 1.01x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.3 ms: 1.05x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 70.2 ms: 1.10x faster                                                |
| asyncio_tcp              | 526 ms                                                 | 484 ms: 1.09x faster                                                 |
| coverage                 | 94.2 ms                                                | 87.5 ms: 1.08x faster                                                |
| raytrace                 | 294 ms                                                 | 279 ms: 1.06x faster                                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 67.3 ms: 1.05x faster                                                |
| async_tree_none          | 469 ms                                                 | 446 ms: 1.05x faster                                                 |
| deltablue                | 3.52 ms                                                | 3.38 ms: 1.04x faster                                                |
| create_gc_cycles         | 1.52 ms                                                | 1.46 ms: 1.04x faster                                                |
| generators               | 31.1 ms                                                | 29.9 ms: 1.04x faster                                                |
| chaos                    | 63.5 ms                                                | 61.6 ms: 1.03x faster                                                |
| regex_compile            | 144 ms                                                 | 140 ms: 1.03x faster                                                 |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                                 |
| tornado_http             | 99.6 ms                                                | 97.7 ms: 1.02x faster                                                |
| float                    | 80.7 ms                                                | 79.3 ms: 1.02x faster                                                |
| xml_etree_generate       | 84.8 ms                                                | 83.4 ms: 1.02x faster                                                |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                               |
| docutils                 | 2.70 sec                                               | 2.66 sec: 1.01x faster                                               |
| sqlglot_parse            | 1.32 ms                                                | 1.30 ms: 1.01x faster                                                |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.62 ms: 1.01x faster                                                |
| xml_etree_process        | 58.6 ms                                                | 57.9 ms: 1.01x faster                                                |
| python_startup           | 9.47 ms                                                | 9.38 ms: 1.01x faster                                                |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                                |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                                 |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                                |
| mdp                      | 2.57 sec                                               | 2.56 sec: 1.00x faster                                               |
| bench_thread_pool        | 827 us                                                 | 825 us: 1.00x faster                                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                               |
| dulwich_log              | 67.9 ms                                                | 68.1 ms: 1.00x slower                                                |
| pickle                   | 10.6 us                                                | 10.6 us: 1.00x slower                                                |
| meteor_contest           | 105 ms                                                 | 105 ms: 1.01x slower                                                 |
| sqlglot_optimize         | 53.3 ms                                                | 53.7 ms: 1.01x slower                                                |
| fannkuch                 | 387 ms                                                 | 391 ms: 1.01x slower                                                 |
| unpickle_pure_python     | 218 us                                                 | 220 us: 1.01x slower                                                 |
| coroutines               | 22.4 ms                                                | 22.7 ms: 1.01x slower                                                |
| json                     | 4.77 ms                                                | 4.83 ms: 1.01x slower                                                |
| pprint_pformat           | 1.50 sec                                               | 1.52 sec: 1.01x slower                                               |
| pprint_safe_repr         | 735 ms                                                 | 745 ms: 1.01x slower                                                 |
| pyflate                  | 450 ms                                                 | 457 ms: 1.01x slower                                                 |
| nqueens                  | 81.1 ms                                                | 82.3 ms: 1.01x slower                                                |
| pickle_dict              | 31.6 us                                                | 32.1 us: 1.01x slower                                                |
| deepcopy_reduce          | 3.14 us                                                | 3.19 us: 1.02x slower                                                |
| deepcopy                 | 355 us                                                 | 361 us: 1.02x slower                                                 |
| logging_format           | 6.90 us                                                | 7.02 us: 1.02x slower                                                |
| logging_simple           | 6.18 us                                                | 6.29 us: 1.02x slower                                                |
| async_generators         | 440 ms                                                 | 448 ms: 1.02x slower                                                 |
| spectral_norm            | 106 ms                                                 | 109 ms: 1.02x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                               |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.03x slower                                                |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.87 ms: 1.03x slower                                                |
| typing_runtime_protocols | 146 us                                                 | 151 us: 1.03x slower                                                 |
| deepcopy_memo            | 37.4 us                                                | 38.7 us: 1.04x slower                                                |
| unpickle_list            | 4.95 us                                                | 5.13 us: 1.04x slower                                                |
| nbody                    | 88.8 ms                                                | 92.5 ms: 1.04x slower                                                |
| hexiom                   | 6.12 ms                                                | 6.39 ms: 1.04x slower                                                |
| logging_silent           | 99.1 ns                                                | 104 ns: 1.05x slower                                                 |
| go                       | 136 ms                                                 | 143 ms: 1.05x slower                                                 |
| mako                     | 10.7 ms                                                | 11.3 ms: 1.05x slower                                                |
| comprehensions           | 20.4 us                                                | 21.5 us: 1.05x slower                                                |
| regex_effbot             | 3.55 ms                                                | 3.76 ms: 1.06x slower                                                |
| pycparser                | 1.15 sec                                               | 1.22 sec: 1.07x slower                                               |
| regex_dna                | 209 ms                                                 | 224 ms: 1.07x slower                                                 |
| pidigits                 | 187 ms                                                 | 201 ms: 1.08x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 4.14 ms: 1.08x slower                                                |
| richards_super           | 49.0 ms                                                | 55.1 ms: 1.13x slower                                                |
| richards                 | 43.2 ms                                                | 49.0 ms: 1.14x slower                                                |
| telco                    | 6.87 ms                                                | 7.95 ms: 1.16x slower                                                |
| unpack_sequence          | 44.8 ns                                                | 53.6 ns: 1.20x slower                                                |
| regex_v8                 | 22.3 ms                                                | 29.2 ms: 1.31x slower                                                |
| dask                     | 365 ms                                                 | 535 ms: 1.47x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                         |

Benchmark hidden because not significant (11): async_tree_cpu_io_mixed, async_tree_memoization, pickle_pure_python, sqlglot_normalize, json_dumps, mypy2, scimark_fft, bench_mp_pool, json_loads, pickle_list, unpickle
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 82.54% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
