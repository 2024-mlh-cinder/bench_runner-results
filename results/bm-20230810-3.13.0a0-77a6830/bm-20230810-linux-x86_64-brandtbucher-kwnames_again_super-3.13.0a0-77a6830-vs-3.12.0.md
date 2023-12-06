
# Results vs. 3.12.0

- fork: brandtbucher
- ref: kwnames_again_super
- machine: linux-x86_64
- commit hash: 77a6830
- commit date: 2023-08-10
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.74 sec: 1.01x slower                                                     |
| tornado_http   | 99.6 ms                                                | 104 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                  | 1.03x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                       |
| nbody          | 88.8 ms                                                | 91.3 ms: 1.03x slower                                                      |
| float          | 80.7 ms                                                | 84.5 ms: 1.05x slower                                                      |
| Geometric mean | (ref)                                                  | 1.03x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 211 ms: 1.01x slower                                                       |
| regex_effbot   | 3.55 ms                                                | 3.61 ms: 1.02x slower                                                      |
| regex_compile  | 144 ms                                                 | 149 ms: 1.03x slower                                                       |
| regex_v8       | 22.3 ms                                                | 25.0 ms: 1.12x slower                                                      |
| Geometric mean | (ref)                                                  | 1.04x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.6 us: 1.02x faster                                                      |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                       |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                       |
| tomli_loads          | 2.22 sec                                               | 2.25 sec: 1.01x slower                                                     |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                                      |
| json_loads           | 25.2 us                                                | 25.6 us: 1.02x slower                                                      |
| pickle_list          | 4.62 us                                                | 4.72 us: 1.02x slower                                                      |
| xml_etree_process    | 58.6 ms                                                | 60.0 ms: 1.03x slower                                                      |
| pickle_pure_python   | 309 us                                                 | 321 us: 1.04x slower                                                       |
| unpickle_pure_python | 218 us                                                 | 228 us: 1.04x slower                                                       |
| pickle_dict          | 31.6 us                                                | 33.3 us: 1.05x slower                                                      |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                               |

Benchmark hidden because not significant (3): json_dumps, xml_etree_generate, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 9.47 ms                                                | 9.46 ms: 1.00x faster                                                      |
| Geometric mean | (ref)                                                  | 1.00x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.4 ms: 1.06x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 86.9 ms: 1.08x faster                                                      |
| asyncio_tcp              | 526 ms                                                 | 496 ms: 1.06x faster                                                       |
| crypto_pyaes             | 77.2 ms                                                | 73.2 ms: 1.06x faster                                                      |
| async_tree_none          | 469 ms                                                 | 449 ms: 1.05x faster                                                       |
| unpickle                 | 15.0 us                                                | 14.6 us: 1.02x faster                                                      |
| scimark_monte_carlo      | 71.0 ms                                                | 69.8 ms: 1.02x faster                                                      |
| raytrace                 | 294 ms                                                 | 291 ms: 1.01x faster                                                       |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                                      |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                       |
| python_startup           | 9.47 ms                                                | 9.46 ms: 1.00x faster                                                      |
| gc_traversal             | 3.84 ms                                                | 3.84 ms: 1.00x faster                                                      |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.01x slower                                                     |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                       |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                      |
| regex_dna                | 209 ms                                                 | 211 ms: 1.01x slower                                                       |
| async_tree_memoization   | 573 ms                                                 | 579 ms: 1.01x slower                                                       |
| sqlite_synth             | 2.76 us                                                | 2.80 us: 1.01x slower                                                      |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                       |
| docutils                 | 2.70 sec                                               | 2.74 sec: 1.01x slower                                                     |
| tomli_loads              | 2.22 sec                                               | 2.25 sec: 1.01x slower                                                     |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                                      |
| json_loads               | 25.2 us                                                | 25.6 us: 1.02x slower                                                      |
| regex_effbot             | 3.55 ms                                                | 3.61 ms: 1.02x slower                                                      |
| async_generators         | 440 ms                                                 | 449 ms: 1.02x slower                                                       |
| bench_thread_pool        | 827 us                                                 | 844 us: 1.02x slower                                                       |
| chaos                    | 63.5 ms                                                | 64.9 ms: 1.02x slower                                                      |
| pickle_list              | 4.62 us                                                | 4.72 us: 1.02x slower                                                      |
| meteor_contest           | 105 ms                                                 | 107 ms: 1.02x slower                                                       |
| xml_etree_process        | 58.6 ms                                                | 60.0 ms: 1.03x slower                                                      |
| json                     | 4.77 ms                                                | 4.90 ms: 1.03x slower                                                      |
| nbody                    | 88.8 ms                                                | 91.3 ms: 1.03x slower                                                      |
| pprint_safe_repr         | 735 ms                                                 | 756 ms: 1.03x slower                                                       |
| pprint_pformat           | 1.50 sec                                               | 1.54 sec: 1.03x slower                                                     |
| generators               | 31.1 ms                                                | 32.1 ms: 1.03x slower                                                      |
| sqlglot_parse            | 1.32 ms                                                | 1.37 ms: 1.03x slower                                                      |
| regex_compile            | 144 ms                                                 | 149 ms: 1.03x slower                                                       |
| mypy2                    | 344 ms                                                 | 356 ms: 1.04x slower                                                       |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.92 ms: 1.04x slower                                                      |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.04x slower                                                     |
| sqlglot_transpile        | 1.64 ms                                                | 1.70 ms: 1.04x slower                                                      |
| pickle_pure_python       | 309 us                                                 | 321 us: 1.04x slower                                                       |
| scimark_fft              | 358 ms                                                 | 372 ms: 1.04x slower                                                       |
| nqueens                  | 81.1 ms                                                | 84.3 ms: 1.04x slower                                                      |
| typing_runtime_protocols | 146 us                                                 | 152 us: 1.04x slower                                                       |
| pyflate                  | 450 ms                                                 | 468 ms: 1.04x slower                                                       |
| tornado_http             | 99.6 ms                                                | 104 ms: 1.04x slower                                                       |
| scimark_sor              | 125 ms                                                 | 130 ms: 1.04x slower                                                       |
| unpickle_pure_python     | 218 us                                                 | 228 us: 1.04x slower                                                       |
| float                    | 80.7 ms                                                | 84.5 ms: 1.05x slower                                                      |
| mdp                      | 2.57 sec                                               | 2.69 sec: 1.05x slower                                                     |
| sqlglot_normalize        | 107 ms                                                 | 113 ms: 1.05x slower                                                       |
| pickle_dict              | 31.6 us                                                | 33.3 us: 1.05x slower                                                      |
| deepcopy                 | 355 us                                                 | 375 us: 1.06x slower                                                       |
| coroutines               | 22.4 ms                                                | 23.7 ms: 1.06x slower                                                      |
| fannkuch                 | 387 ms                                                 | 410 ms: 1.06x slower                                                       |
| comprehensions           | 20.4 us                                                | 21.6 us: 1.06x slower                                                      |
| mako                     | 10.7 ms                                                | 11.4 ms: 1.06x slower                                                      |
| sqlglot_optimize         | 53.3 ms                                                | 56.5 ms: 1.06x slower                                                      |
| dulwich_log              | 67.9 ms                                                | 72.2 ms: 1.06x slower                                                      |
| deepcopy_memo            | 37.4 us                                                | 40.0 us: 1.07x slower                                                      |
| deltablue                | 3.52 ms                                                | 3.77 ms: 1.07x slower                                                      |
| deepcopy_reduce          | 3.14 us                                                | 3.38 us: 1.08x slower                                                      |
| hexiom                   | 6.12 ms                                                | 6.60 ms: 1.08x slower                                                      |
| pycparser                | 1.15 sec                                               | 1.24 sec: 1.08x slower                                                     |
| go                       | 136 ms                                                 | 147 ms: 1.08x slower                                                       |
| spectral_norm            | 106 ms                                                 | 115 ms: 1.09x slower                                                       |
| logging_silent           | 99.1 ns                                                | 109 ns: 1.10x slower                                                       |
| regex_v8                 | 22.3 ms                                                | 25.0 ms: 1.12x slower                                                      |
| logging_simple           | 6.18 us                                                | 6.94 us: 1.12x slower                                                      |
| logging_format           | 6.90 us                                                | 7.82 us: 1.13x slower                                                      |
| unpack_sequence          | 44.8 ns                                                | 51.0 ns: 1.14x slower                                                      |
| richards_super           | 49.0 ms                                                | 56.7 ms: 1.16x slower                                                      |
| richards                 | 43.2 ms                                                | 50.7 ms: 1.17x slower                                                      |
| telco                    | 6.87 ms                                                | 8.36 ms: 1.22x slower                                                      |
| dask                     | 365 ms                                                 | 554 ms: 1.52x slower                                                       |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                               |

Benchmark hidden because not significant (7): async_tree_cpu_io_mixed, json_dumps, bench_mp_pool, python_startup_no_site, xml_etree_generate, scimark_lu, unpickle_list
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
