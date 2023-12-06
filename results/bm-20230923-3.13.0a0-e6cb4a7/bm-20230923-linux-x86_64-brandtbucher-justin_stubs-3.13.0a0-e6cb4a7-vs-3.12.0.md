
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_stubs
- machine: linux-x86_64
- commit hash: e6cb4a7
- commit date: 2023-09-23
- overall geometric mean: 1.01x slower
- HPT reliability: 97.35%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.69 sec: 1.00x faster                                              |
| tornado_http   | 99.6 ms                                                | 97.0 ms: 1.03x faster                                               |
| Geometric mean | (ref)                                                  | 1.02x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                |
| float          | 80.7 ms                                                | 82.5 ms: 1.02x slower                                               |
| nbody          | 88.8 ms                                                | 90.9 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                  | 1.02x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 210 ms: 1.00x slower                                                |
| regex_effbot   | 3.55 ms                                                | 3.65 ms: 1.03x slower                                               |
| regex_v8       | 22.3 ms                                                | 23.3 ms: 1.04x slower                                               |
| Geometric mean | (ref)                                                  | 1.02x slower                                                        |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.07 sec: 1.07x faster                                              |
| pickle_pure_python   | 309 us                                                 | 296 us: 1.04x faster                                                |
| pickle               | 10.6 us                                                | 10.3 us: 1.03x faster                                               |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                |
| xml_etree_process    | 58.6 ms                                                | 58.1 ms: 1.01x faster                                               |
| pickle_list          | 4.62 us                                                | 4.58 us: 1.01x faster                                               |
| unpickle             | 15.0 us                                                | 14.9 us: 1.01x faster                                               |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                |
| unpickle_list        | 4.95 us                                                | 5.02 us: 1.01x slower                                               |
| unpickle_pure_python | 218 us                                                 | 223 us: 1.02x slower                                                |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                        |

Benchmark hidden because not significant (4): xml_etree_generate, json_loads, pickle_dict, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.88 ms: 1.00x faster                                               |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                               |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.0 ms: 1.03x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| generators               | 31.1 ms                                                | 28.4 ms: 1.09x faster                                               |
| coverage                 | 94.2 ms                                                | 86.7 ms: 1.09x faster                                               |
| raytrace                 | 294 ms                                                 | 271 ms: 1.09x faster                                                |
| crypto_pyaes             | 77.2 ms                                                | 71.3 ms: 1.08x faster                                               |
| scimark_monte_carlo      | 71.0 ms                                                | 66.2 ms: 1.07x faster                                               |
| tomli_loads              | 2.22 sec                                               | 2.07 sec: 1.07x faster                                              |
| async_tree_none          | 469 ms                                                 | 444 ms: 1.06x faster                                                |
| scimark_fft              | 358 ms                                                 | 341 ms: 1.05x faster                                                |
| asyncio_tcp              | 526 ms                                                 | 503 ms: 1.05x faster                                                |
| pickle_pure_python       | 309 us                                                 | 296 us: 1.04x faster                                                |
| scimark_sor              | 125 ms                                                 | 120 ms: 1.04x faster                                                |
| deltablue                | 3.52 ms                                                | 3.38 ms: 1.04x faster                                               |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                               |
| tornado_http             | 99.6 ms                                                | 97.0 ms: 1.03x faster                                               |
| pickle                   | 10.6 us                                                | 10.3 us: 1.03x faster                                               |
| coroutines               | 22.4 ms                                                | 21.9 ms: 1.03x faster                                               |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                                |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                               |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                |
| xml_etree_process        | 58.6 ms                                                | 58.1 ms: 1.01x faster                                               |
| pickle_list              | 4.62 us                                                | 4.58 us: 1.01x faster                                               |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                |
| unpickle                 | 15.0 us                                                | 14.9 us: 1.01x faster                                               |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                |
| docutils                 | 2.70 sec                                               | 2.69 sec: 1.00x faster                                              |
| python_startup_no_site   | 6.90 ms                                                | 6.88 ms: 1.00x faster                                               |
| create_gc_cycles         | 1.52 ms                                                | 1.53 ms: 1.00x slower                                               |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                              |
| regex_dna                | 209 ms                                                 | 210 ms: 1.00x slower                                                |
| dulwich_log              | 67.9 ms                                                | 68.3 ms: 1.01x slower                                               |
| bench_thread_pool        | 827 us                                                 | 832 us: 1.01x slower                                                |
| sqlglot_optimize         | 53.3 ms                                                | 53.6 ms: 1.01x slower                                               |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                               |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                               |
| logging_simple           | 6.18 us                                                | 6.24 us: 1.01x slower                                               |
| unpickle_list            | 4.95 us                                                | 5.02 us: 1.01x slower                                               |
| pprint_pformat           | 1.50 sec                                               | 1.52 sec: 1.02x slower                                              |
| typing_runtime_protocols | 146 us                                                 | 148 us: 1.02x slower                                                |
| pprint_safe_repr         | 735 ms                                                 | 748 ms: 1.02x slower                                                |
| pyflate                  | 450 ms                                                 | 459 ms: 1.02x slower                                                |
| json                     | 4.77 ms                                                | 4.86 ms: 1.02x slower                                               |
| mypy2                    | 344 ms                                                 | 350 ms: 1.02x slower                                                |
| mdp                      | 2.57 sec                                               | 2.62 sec: 1.02x slower                                              |
| chaos                    | 63.5 ms                                                | 64.8 ms: 1.02x slower                                               |
| unpickle_pure_python     | 218 us                                                 | 223 us: 1.02x slower                                                |
| float                    | 80.7 ms                                                | 82.5 ms: 1.02x slower                                               |
| nbody                    | 88.8 ms                                                | 90.9 ms: 1.02x slower                                               |
| mako                     | 10.7 ms                                                | 11.0 ms: 1.03x slower                                               |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                              |
| spectral_norm            | 106 ms                                                 | 109 ms: 1.03x slower                                                |
| regex_effbot             | 3.55 ms                                                | 3.65 ms: 1.03x slower                                               |
| fannkuch                 | 387 ms                                                 | 401 ms: 1.04x slower                                                |
| pycparser                | 1.15 sec                                               | 1.19 sec: 1.04x slower                                              |
| regex_v8                 | 22.3 ms                                                | 23.3 ms: 1.04x slower                                               |
| deepcopy_memo            | 37.4 us                                                | 39.1 us: 1.05x slower                                               |
| meteor_contest           | 105 ms                                                 | 110 ms: 1.05x slower                                                |
| async_generators         | 440 ms                                                 | 464 ms: 1.05x slower                                                |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                                |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                               |
| go                       | 136 ms                                                 | 145 ms: 1.07x slower                                                |
| nqueens                  | 81.1 ms                                                | 87.1 ms: 1.07x slower                                               |
| richards_super           | 49.0 ms                                                | 54.1 ms: 1.11x slower                                               |
| unpack_sequence          | 44.8 ns                                                | 49.9 ns: 1.11x slower                                               |
| richards                 | 43.2 ms                                                | 48.2 ms: 1.12x slower                                               |
| hexiom                   | 6.12 ms                                                | 6.86 ms: 1.12x slower                                               |
| comprehensions           | 20.4 us                                                | 23.0 us: 1.12x slower                                               |
| gc_traversal             | 3.84 ms                                                | 4.37 ms: 1.14x slower                                               |
| telco                    | 6.87 ms                                                | 8.07 ms: 1.17x slower                                               |
| dask                     | 365 ms                                                 | 529 ms: 1.45x slower                                                |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                        |

Benchmark hidden because not significant (12): async_tree_cpu_io_mixed, async_tree_memoization, regex_compile, xml_etree_generate, scimark_sparse_mat_mult, json_loads, bench_mp_pool, pickle_dict, sqlite_synth, json_dumps, logging_format, deepcopy
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 97.35% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
