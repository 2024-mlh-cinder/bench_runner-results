
# Results vs. 3.12.0

- fork: gvanrossum
- ref: call_uops_forever
- machine: linux-x86_64
- commit hash: f6a72ae
- commit date: 2023-08-16
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.72 sec: 1.01x slower                                                 |
| tornado_http   | 99.6 ms                                                | 97.9 ms: 1.02x faster                                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 84.8 ms: 1.05x slower                                                  |
| pidigits       | 187 ms                                                 | 201 ms: 1.08x slower                                                   |
| nbody          | 88.8 ms                                                | 115 ms: 1.30x slower                                                   |
| Geometric mean | (ref)                                                  | 1.14x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 214 ms: 1.03x slower                                                   |
| regex_effbot   | 3.55 ms                                                | 3.74 ms: 1.06x slower                                                  |
| regex_v8       | 22.3 ms                                                | 24.0 ms: 1.07x slower                                                  |
| regex_compile  | 144 ms                                                 | 155 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 301 us: 1.03x faster                                                   |
| unpickle             | 15.0 us                                                | 14.6 us: 1.02x faster                                                  |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                   |
| xml_etree_process    | 58.6 ms                                                | 58.3 ms: 1.00x faster                                                  |
| pickle_dict          | 31.6 us                                                | 31.9 us: 1.01x slower                                                  |
| xml_etree_generate   | 84.8 ms                                                | 85.5 ms: 1.01x slower                                                  |
| unpickle_list        | 4.95 us                                                | 4.99 us: 1.01x slower                                                  |
| pickle               | 10.6 us                                                | 10.7 us: 1.01x slower                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                                   |
| unpickle_pure_python | 218 us                                                 | 226 us: 1.03x slower                                                   |
| pickle_list          | 4.62 us                                                | 4.87 us: 1.06x slower                                                  |
| tomli_loads          | 2.22 sec                                               | 2.54 sec: 1.15x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (2): json_loads, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.31 ms: 1.02x faster                                                  |
| python_startup_no_site | 6.90 ms                                                | 6.82 ms: 1.01x faster                                                  |
| Geometric mean         | (ref)                                                  | 1.01x faster                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 12.8 ms: 1.20x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 86.0 ms: 1.09x faster                                                  |
| generators               | 31.1 ms                                                | 28.5 ms: 1.09x faster                                                  |
| asyncio_tcp              | 526 ms                                                 | 488 ms: 1.08x faster                                                   |
| logging_format           | 6.90 us                                                | 6.60 us: 1.05x faster                                                  |
| async_tree_none          | 469 ms                                                 | 450 ms: 1.04x faster                                                   |
| scimark_monte_carlo      | 71.0 ms                                                | 68.2 ms: 1.04x faster                                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.47 ms: 1.03x faster                                                  |
| coroutines               | 22.4 ms                                                | 21.7 ms: 1.03x faster                                                  |
| logging_simple           | 6.18 us                                                | 5.99 us: 1.03x faster                                                  |
| pickle_pure_python       | 309 us                                                 | 301 us: 1.03x faster                                                   |
| raytrace                 | 294 ms                                                 | 286 ms: 1.03x faster                                                   |
| unpickle                 | 15.0 us                                                | 14.6 us: 1.02x faster                                                  |
| crypto_pyaes             | 77.2 ms                                                | 75.5 ms: 1.02x faster                                                  |
| python_startup           | 9.47 ms                                                | 9.31 ms: 1.02x faster                                                  |
| tornado_http             | 99.6 ms                                                | 97.9 ms: 1.02x faster                                                  |
| python_startup_no_site   | 6.90 ms                                                | 6.82 ms: 1.01x faster                                                  |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                   |
| xml_etree_process        | 58.6 ms                                                | 58.3 ms: 1.00x faster                                                  |
| dulwich_log              | 67.9 ms                                                | 67.7 ms: 1.00x faster                                                  |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                                  |
| pickle_dict              | 31.6 us                                                | 31.9 us: 1.01x slower                                                  |
| docutils                 | 2.70 sec                                               | 2.72 sec: 1.01x slower                                                 |
| xml_etree_generate       | 84.8 ms                                                | 85.5 ms: 1.01x slower                                                  |
| unpickle_list            | 4.95 us                                                | 4.99 us: 1.01x slower                                                  |
| pickle                   | 10.6 us                                                | 10.7 us: 1.01x slower                                                  |
| deepcopy                 | 355 us                                                 | 359 us: 1.01x slower                                                   |
| sqlglot_normalize        | 107 ms                                                 | 109 ms: 1.01x slower                                                   |
| pprint_safe_repr         | 735 ms                                                 | 747 ms: 1.02x slower                                                   |
| json                     | 4.77 ms                                                | 4.85 ms: 1.02x slower                                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.21 us: 1.02x slower                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                                   |
| bench_thread_pool        | 827 us                                                 | 848 us: 1.02x slower                                                   |
| regex_dna                | 209 ms                                                 | 214 ms: 1.03x slower                                                   |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.54 sec: 1.03x slower                                                 |
| deltablue                | 3.52 ms                                                | 3.62 ms: 1.03x slower                                                  |
| sqlglot_optimize         | 53.3 ms                                                | 55.1 ms: 1.03x slower                                                  |
| unpickle_pure_python     | 218 us                                                 | 226 us: 1.03x slower                                                   |
| scimark_sor              | 125 ms                                                 | 129 ms: 1.03x slower                                                   |
| scimark_lu               | 114 ms                                                 | 118 ms: 1.04x slower                                                   |
| mdp                      | 2.57 sec                                               | 2.67 sec: 1.04x slower                                                 |
| pathlib                  | 18.5 ms                                                | 19.3 ms: 1.04x slower                                                  |
| float                    | 80.7 ms                                                | 84.8 ms: 1.05x slower                                                  |
| typing_runtime_protocols | 146 us                                                 | 153 us: 1.05x slower                                                   |
| pickle_list              | 4.62 us                                                | 4.87 us: 1.06x slower                                                  |
| unpack_sequence          | 44.8 ns                                                | 47.3 ns: 1.06x slower                                                  |
| regex_effbot             | 3.55 ms                                                | 3.74 ms: 1.06x slower                                                  |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                                   |
| async_generators         | 440 ms                                                 | 472 ms: 1.07x slower                                                   |
| regex_v8                 | 22.3 ms                                                | 24.0 ms: 1.07x slower                                                  |
| pidigits                 | 187 ms                                                 | 201 ms: 1.08x slower                                                   |
| regex_compile            | 144 ms                                                 | 155 ms: 1.08x slower                                                   |
| pycparser                | 1.15 sec                                               | 1.25 sec: 1.08x slower                                                 |
| chaos                    | 63.5 ms                                                | 69.2 ms: 1.09x slower                                                  |
| spectral_norm            | 106 ms                                                 | 116 ms: 1.09x slower                                                   |
| go                       | 136 ms                                                 | 150 ms: 1.11x slower                                                   |
| meteor_contest           | 105 ms                                                 | 118 ms: 1.12x slower                                                   |
| deepcopy_memo            | 37.4 us                                                | 42.5 us: 1.14x slower                                                  |
| tomli_loads              | 2.22 sec                                               | 2.54 sec: 1.15x slower                                                 |
| pyflate                  | 450 ms                                                 | 519 ms: 1.15x slower                                                   |
| richards_super           | 49.0 ms                                                | 56.7 ms: 1.16x slower                                                  |
| richards                 | 43.2 ms                                                | 50.4 ms: 1.17x slower                                                  |
| telco                    | 6.87 ms                                                | 8.12 ms: 1.18x slower                                                  |
| scimark_fft              | 358 ms                                                 | 425 ms: 1.18x slower                                                   |
| mako                     | 10.7 ms                                                | 12.8 ms: 1.20x slower                                                  |
| nqueens                  | 81.1 ms                                                | 99.4 ms: 1.22x slower                                                  |
| fannkuch                 | 387 ms                                                 | 480 ms: 1.24x slower                                                   |
| comprehensions           | 20.4 us                                                | 26.0 us: 1.27x slower                                                  |
| nbody                    | 88.8 ms                                                | 115 ms: 1.30x slower                                                   |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 6.19 ms: 1.30x slower                                                  |
| hexiom                   | 6.12 ms                                                | 8.00 ms: 1.31x slower                                                  |
| mypy2                    | 344 ms                                                 | 467 ms: 1.36x slower                                                   |
| dask                     | 365 ms                                                 | 533 ms: 1.46x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.05x slower                                                           |

Benchmark hidden because not significant (9): sqlite_synth, async_tree_cpu_io_mixed, async_tree_memoization, sqlglot_parse, json_loads, bench_mp_pool, asyncio_tcp_ssl, sqlglot_transpile, json_dumps
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
