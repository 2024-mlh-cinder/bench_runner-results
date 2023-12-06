
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: f1573ca
- commit date: 2023-09-25
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                    |
| float          | 80.7 ms                                                | 96.1 ms: 1.19x slower                                                   |
| nbody          | 88.8 ms                                                | 111 ms: 1.25x slower                                                    |
| Geometric mean | (ref)                                                  | 1.14x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.45 ms: 1.03x faster                                                   |
| regex_dna      | 209 ms                                                 | 206 ms: 1.01x faster                                                    |
| regex_v8       | 22.3 ms                                                | 23.5 ms: 1.05x slower                                                   |
| regex_compile  | 144 ms                                                 | 154 ms: 1.07x slower                                                    |
| Geometric mean | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 301 us: 1.03x faster                                                    |
| json_loads           | 25.2 us                                                | 24.8 us: 1.02x faster                                                   |
| unpickle_list        | 4.95 us                                                | 4.87 us: 1.02x faster                                                   |
| xml_etree_generate   | 84.8 ms                                                | 83.6 ms: 1.01x faster                                                   |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                                   |
| xml_etree_process    | 58.6 ms                                                | 58.2 ms: 1.01x faster                                                   |
| pickle_dict          | 31.6 us                                                | 31.5 us: 1.00x faster                                                   |
| tomli_loads          | 2.22 sec                                               | 2.27 sec: 1.02x slower                                                  |
| pickle_list          | 4.62 us                                                | 4.80 us: 1.04x slower                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 109 ms: 1.05x slower                                                    |
| unpickle_pure_python | 218 us                                                 | 238 us: 1.09x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (3): json_dumps, xml_etree_parse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.92 ms: 1.00x slower                                                   |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.8 ms: 1.10x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| generators               | 31.1 ms                                                | 28.6 ms: 1.09x faster                                                   |
| coverage                 | 94.2 ms                                                | 87.6 ms: 1.08x faster                                                   |
| crypto_pyaes             | 77.2 ms                                                | 72.9 ms: 1.06x faster                                                   |
| async_tree_none          | 469 ms                                                 | 451 ms: 1.04x faster                                                    |
| asyncio_tcp              | 526 ms                                                 | 511 ms: 1.03x faster                                                    |
| regex_effbot             | 3.55 ms                                                | 3.45 ms: 1.03x faster                                                   |
| pickle_pure_python       | 309 us                                                 | 301 us: 1.03x faster                                                    |
| logging_format           | 6.90 us                                                | 6.77 us: 1.02x faster                                                   |
| json_loads               | 25.2 us                                                | 24.8 us: 1.02x faster                                                   |
| unpickle_list            | 4.95 us                                                | 4.87 us: 1.02x faster                                                   |
| xml_etree_generate       | 84.8 ms                                                | 83.6 ms: 1.01x faster                                                   |
| logging_simple           | 6.18 us                                                | 6.09 us: 1.01x faster                                                   |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                    |
| regex_dna                | 209 ms                                                 | 206 ms: 1.01x faster                                                    |
| coroutines               | 22.4 ms                                                | 22.3 ms: 1.01x faster                                                   |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                                    |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                                   |
| xml_etree_process        | 58.6 ms                                                | 58.2 ms: 1.01x faster                                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.00x faster                                                   |
| pickle_dict              | 31.6 us                                                | 31.5 us: 1.00x faster                                                   |
| python_startup_no_site   | 6.90 ms                                                | 6.92 ms: 1.00x slower                                                   |
| deepcopy_reduce          | 3.14 us                                                | 3.16 us: 1.01x slower                                                   |
| dulwich_log              | 67.9 ms                                                | 68.5 ms: 1.01x slower                                                   |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                    |
| sqlglot_optimize         | 53.3 ms                                                | 53.8 ms: 1.01x slower                                                   |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.82 sec: 1.01x slower                                                  |
| spectral_norm            | 106 ms                                                 | 108 ms: 1.02x slower                                                    |
| bench_thread_pool        | 827 us                                                 | 840 us: 1.02x slower                                                    |
| pycparser                | 1.15 sec                                               | 1.17 sec: 1.02x slower                                                  |
| async_tree_memoization   | 573 ms                                                 | 584 ms: 1.02x slower                                                    |
| tomli_loads              | 2.22 sec                                               | 2.27 sec: 1.02x slower                                                  |
| raytrace                 | 294 ms                                                 | 305 ms: 1.04x slower                                                    |
| pickle_list              | 4.62 us                                                | 4.80 us: 1.04x slower                                                   |
| scimark_fft              | 358 ms                                                 | 373 ms: 1.04x slower                                                    |
| typing_runtime_protocols | 146 us                                                 | 152 us: 1.04x slower                                                    |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.04x slower                                                  |
| mypy2                    | 344 ms                                                 | 358 ms: 1.04x slower                                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 74.1 ms: 1.04x slower                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 109 ms: 1.05x slower                                                    |
| async_generators         | 440 ms                                                 | 463 ms: 1.05x slower                                                    |
| regex_v8                 | 22.3 ms                                                | 23.5 ms: 1.05x slower                                                   |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                                    |
| meteor_contest           | 105 ms                                                 | 111 ms: 1.06x slower                                                    |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                   |
| regex_compile            | 144 ms                                                 | 154 ms: 1.07x slower                                                    |
| deepcopy_memo            | 37.4 us                                                | 40.0 us: 1.07x slower                                                   |
| gc_traversal             | 3.84 ms                                                | 4.11 ms: 1.07x slower                                                   |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.09 ms: 1.07x slower                                                   |
| unpack_sequence          | 44.8 ns                                                | 48.6 ns: 1.08x slower                                                   |
| mdp                      | 2.57 sec                                               | 2.78 sec: 1.08x slower                                                  |
| unpickle_pure_python     | 218 us                                                 | 238 us: 1.09x slower                                                    |
| mako                     | 10.7 ms                                                | 11.8 ms: 1.10x slower                                                   |
| richards                 | 43.2 ms                                                | 48.5 ms: 1.12x slower                                                   |
| richards_super           | 49.0 ms                                                | 55.3 ms: 1.13x slower                                                   |
| go                       | 136 ms                                                 | 153 ms: 1.13x slower                                                    |
| fannkuch                 | 387 ms                                                 | 442 ms: 1.14x slower                                                    |
| telco                    | 6.87 ms                                                | 8.08 ms: 1.18x slower                                                   |
| pprint_safe_repr         | 735 ms                                                 | 865 ms: 1.18x slower                                                    |
| pyflate                  | 450 ms                                                 | 533 ms: 1.18x slower                                                    |
| float                    | 80.7 ms                                                | 96.1 ms: 1.19x slower                                                   |
| nqueens                  | 81.1 ms                                                | 97.2 ms: 1.20x slower                                                   |
| chaos                    | 63.5 ms                                                | 76.5 ms: 1.20x slower                                                   |
| deltablue                | 3.52 ms                                                | 4.26 ms: 1.21x slower                                                   |
| pprint_pformat           | 1.50 sec                                               | 1.82 sec: 1.21x slower                                                  |
| nbody                    | 88.8 ms                                                | 111 ms: 1.25x slower                                                    |
| comprehensions           | 20.4 us                                                | 26.8 us: 1.31x slower                                                   |
| hexiom                   | 6.12 ms                                                | 9.45 ms: 1.54x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.05x slower                                                            |

Benchmark hidden because not significant (13): sqlite_synth, sqlglot_parse, sqlglot_transpile, deepcopy, json_dumps, xml_etree_parse, docutils, bench_mp_pool, tornado_http, scimark_lu, async_tree_cpu_io_mixed, json, unpickle
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
