
# Results vs. 3.12.0

- fork: brandtbucher
- ref: ff1d6a73a64e73cbbfee
- machine: linux-x86_64
- commit hash: ff1d6a7
- commit date: 2023-09-24
- overall geometric mean: 1.01x slower
- HPT reliability: 85.25%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tornado_http   | 99.6 ms                                                | 96.5 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                  | 1.02x faster                                                                |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                        |
| float          | 80.7 ms                                                | 82.5 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                  | 1.02x slower                                                                |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 140 ms: 1.03x faster                                                        |
| regex_effbot   | 3.55 ms                                                | 3.49 ms: 1.02x faster                                                       |
| regex_dna      | 209 ms                                                 | 206 ms: 1.01x faster                                                        |
| regex_v8       | 22.3 ms                                                | 23.8 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                  | 1.00x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.00 sec: 1.11x faster                                                      |
| unpickle             | 15.0 us                                                | 14.2 us: 1.05x faster                                                       |
| pickle_pure_python   | 309 us                                                 | 300 us: 1.03x faster                                                        |
| pickle_dict          | 31.6 us                                                | 31.1 us: 1.02x faster                                                       |
| unpickle_list        | 4.95 us                                                | 4.89 us: 1.01x faster                                                       |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                        |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                        |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                                       |
| xml_etree_generate   | 84.8 ms                                                | 84.5 ms: 1.00x faster                                                       |
| json_dumps           | 9.85 ms                                                | 9.90 ms: 1.01x slower                                                       |
| json_loads           | 25.2 us                                                | 25.5 us: 1.01x slower                                                       |
| pickle_list          | 4.62 us                                                | 4.72 us: 1.02x slower                                                       |
| unpickle_pure_python | 218 us                                                 | 224 us: 1.03x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                                |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                                       |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads              | 2.22 sec                                               | 2.00 sec: 1.11x faster                                                      |
| coverage                 | 94.2 ms                                                | 85.4 ms: 1.10x faster                                                       |
| crypto_pyaes             | 77.2 ms                                                | 70.0 ms: 1.10x faster                                                       |
| generators               | 31.1 ms                                                | 28.6 ms: 1.09x faster                                                       |
| asyncio_tcp              | 526 ms                                                 | 485 ms: 1.08x faster                                                        |
| scimark_fft              | 358 ms                                                 | 334 ms: 1.07x faster                                                        |
| raytrace                 | 294 ms                                                 | 275 ms: 1.07x faster                                                        |
| logging_format           | 6.90 us                                                | 6.48 us: 1.06x faster                                                       |
| async_tree_none          | 469 ms                                                 | 446 ms: 1.05x faster                                                        |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.51 ms: 1.05x faster                                                       |
| unpickle                 | 15.0 us                                                | 14.2 us: 1.05x faster                                                       |
| scimark_monte_carlo      | 71.0 ms                                                | 67.5 ms: 1.05x faster                                                       |
| logging_simple           | 6.18 us                                                | 5.91 us: 1.04x faster                                                       |
| deltablue                | 3.52 ms                                                | 3.39 ms: 1.04x faster                                                       |
| tornado_http             | 99.6 ms                                                | 96.5 ms: 1.03x faster                                                       |
| pickle_pure_python       | 309 us                                                 | 300 us: 1.03x faster                                                        |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.03x faster                                                       |
| regex_compile            | 144 ms                                                 | 140 ms: 1.03x faster                                                        |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.02x faster                                                       |
| pickle_dict              | 31.6 us                                                | 31.1 us: 1.02x faster                                                       |
| regex_effbot             | 3.55 ms                                                | 3.49 ms: 1.02x faster                                                       |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                                       |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                                        |
| regex_dna                | 209 ms                                                 | 206 ms: 1.01x faster                                                        |
| coroutines               | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                       |
| unpickle_list            | 4.95 us                                                | 4.89 us: 1.01x faster                                                       |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                        |
| async_tree_memoization   | 573 ms                                                 | 568 ms: 1.01x faster                                                        |
| dulwich_log              | 67.9 ms                                                | 67.3 ms: 1.01x faster                                                       |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                        |
| chaos                    | 63.5 ms                                                | 63.1 ms: 1.01x faster                                                       |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                                       |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                                       |
| xml_etree_generate       | 84.8 ms                                                | 84.5 ms: 1.00x faster                                                       |
| sqlglot_normalize        | 107 ms                                                 | 107 ms: 1.00x slower                                                        |
| bench_thread_pool        | 827 us                                                 | 832 us: 1.01x slower                                                        |
| json_dumps               | 9.85 ms                                                | 9.90 ms: 1.01x slower                                                       |
| deepcopy                 | 355 us                                                 | 358 us: 1.01x slower                                                        |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                                      |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                        |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                       |
| mypy2                    | 344 ms                                                 | 347 ms: 1.01x slower                                                        |
| sqlglot_optimize         | 53.3 ms                                                | 53.9 ms: 1.01x slower                                                       |
| json_loads               | 25.2 us                                                | 25.5 us: 1.01x slower                                                       |
| pyflate                  | 450 ms                                                 | 457 ms: 1.02x slower                                                        |
| scimark_lu               | 114 ms                                                 | 116 ms: 1.02x slower                                                        |
| pprint_pformat           | 1.50 sec                                               | 1.53 sec: 1.02x slower                                                      |
| pprint_safe_repr         | 735 ms                                                 | 749 ms: 1.02x slower                                                        |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                       |
| pickle_list              | 4.62 us                                                | 4.72 us: 1.02x slower                                                       |
| float                    | 80.7 ms                                                | 82.5 ms: 1.02x slower                                                       |
| fannkuch                 | 387 ms                                                 | 397 ms: 1.02x slower                                                        |
| typing_runtime_protocols | 146 us                                                 | 150 us: 1.03x slower                                                        |
| json                     | 4.77 ms                                                | 4.89 ms: 1.03x slower                                                       |
| unpickle_pure_python     | 218 us                                                 | 224 us: 1.03x slower                                                        |
| spectral_norm            | 106 ms                                                 | 109 ms: 1.03x slower                                                        |
| deepcopy_memo            | 37.4 us                                                | 38.7 us: 1.03x slower                                                       |
| deepcopy_reduce          | 3.14 us                                                | 3.25 us: 1.04x slower                                                       |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                      |
| meteor_contest           | 105 ms                                                 | 109 ms: 1.04x slower                                                        |
| unpack_sequence          | 44.8 ns                                                | 46.9 ns: 1.05x slower                                                       |
| async_generators         | 440 ms                                                 | 463 ms: 1.05x slower                                                        |
| mdp                      | 2.57 sec                                               | 2.71 sec: 1.06x slower                                                      |
| go                       | 136 ms                                                 | 144 ms: 1.06x slower                                                        |
| regex_v8                 | 22.3 ms                                                | 23.8 ms: 1.06x slower                                                       |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                                       |
| hexiom                   | 6.12 ms                                                | 6.57 ms: 1.07x slower                                                       |
| nqueens                  | 81.1 ms                                                | 87.7 ms: 1.08x slower                                                       |
| logging_silent           | 99.1 ns                                                | 108 ns: 1.09x slower                                                        |
| gc_traversal             | 3.84 ms                                                | 4.20 ms: 1.09x slower                                                       |
| richards_super           | 49.0 ms                                                | 54.6 ms: 1.11x slower                                                       |
| comprehensions           | 20.4 us                                                | 22.9 us: 1.12x slower                                                       |
| richards                 | 43.2 ms                                                | 48.5 ms: 1.12x slower                                                       |
| telco                    | 6.87 ms                                                | 8.03 ms: 1.17x slower                                                       |
| dask                     | 365 ms                                                 | 530 ms: 1.46x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                                |

Benchmark hidden because not significant (7): docutils, xml_etree_process, sqlite_synth, async_tree_cpu_io_mixed, bench_mp_pool, asyncio_tcp_ssl, nbody
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 85.25% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
