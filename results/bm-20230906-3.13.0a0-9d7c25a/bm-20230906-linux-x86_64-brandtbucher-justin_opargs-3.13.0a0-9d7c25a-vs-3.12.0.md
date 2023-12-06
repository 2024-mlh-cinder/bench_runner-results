
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_opargs
- machine: linux-x86_64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.03x slower
- HPT reliability: 99.97%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| tornado_http   | 99.6 ms                                                | 97.9 ms: 1.02x faster                                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                                         |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                 |
| float          | 80.7 ms                                                | 83.3 ms: 1.03x slower                                                |
| nbody          | 88.8 ms                                                | 99.8 ms: 1.12x slower                                                |
| Geometric mean | (ref)                                                  | 1.05x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.63 ms: 1.02x slower                                                |
| regex_compile  | 144 ms                                                 | 147 ms: 1.02x slower                                                 |
| regex_dna      | 209 ms                                                 | 222 ms: 1.07x slower                                                 |
| regex_v8       | 22.3 ms                                                | 25.4 ms: 1.14x slower                                                |
| Geometric mean | (ref)                                                  | 1.06x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 13.9 us: 1.08x faster                                                |
| xml_etree_generate   | 84.8 ms                                                | 83.3 ms: 1.02x faster                                                |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                 |
| json_loads           | 25.2 us                                                | 25.0 us: 1.01x faster                                                |
| pickle_dict          | 31.6 us                                                | 31.7 us: 1.00x slower                                                |
| unpickle_list        | 4.95 us                                                | 4.99 us: 1.01x slower                                                |
| pickle               | 10.6 us                                                | 10.7 us: 1.01x slower                                                |
| json_dumps           | 9.85 ms                                                | 9.96 ms: 1.01x slower                                                |
| unpickle_pure_python | 218 us                                                 | 228 us: 1.05x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                         |

Benchmark hidden because not significant (5): pickle_pure_python, xml_etree_process, tomli_loads, pickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.84 ms: 1.04x slower                                                |
| python_startup_no_site | 6.90 ms                                                | 7.32 ms: 1.06x slower                                                |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.7 ms: 1.09x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 87.0 ms: 1.08x faster                                                |
| unpickle                 | 15.0 us                                                | 13.9 us: 1.08x faster                                                |
| crypto_pyaes             | 77.2 ms                                                | 72.0 ms: 1.07x faster                                                |
| asyncio_tcp              | 526 ms                                                 | 491 ms: 1.07x faster                                                 |
| logging_format           | 6.90 us                                                | 6.53 us: 1.06x faster                                                |
| async_tree_none          | 469 ms                                                 | 445 ms: 1.06x faster                                                 |
| raytrace                 | 294 ms                                                 | 282 ms: 1.04x faster                                                 |
| logging_simple           | 6.18 us                                                | 5.91 us: 1.04x faster                                                |
| generators               | 31.1 ms                                                | 29.8 ms: 1.04x faster                                                |
| scimark_monte_carlo      | 71.0 ms                                                | 68.8 ms: 1.03x faster                                                |
| sqlglot_parse            | 1.32 ms                                                | 1.30 ms: 1.02x faster                                                |
| xml_etree_generate       | 84.8 ms                                                | 83.3 ms: 1.02x faster                                                |
| deltablue                | 3.52 ms                                                | 3.46 ms: 1.02x faster                                                |
| tornado_http             | 99.6 ms                                                | 97.9 ms: 1.02x faster                                                |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                                |
| sqlglot_transpile        | 1.64 ms                                                | 1.62 ms: 1.01x faster                                                |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                                 |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                                |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                 |
| deepcopy_reduce          | 3.14 us                                                | 3.10 us: 1.01x faster                                                |
| json_loads               | 25.2 us                                                | 25.0 us: 1.01x faster                                                |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                                |
| sqlglot_normalize        | 107 ms                                                 | 107 ms: 1.00x faster                                                 |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                 |
| pickle_dict              | 31.6 us                                                | 31.7 us: 1.00x slower                                                |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                               |
| deepcopy                 | 355 us                                                 | 358 us: 1.01x slower                                                 |
| unpickle_list            | 4.95 us                                                | 4.99 us: 1.01x slower                                                |
| pickle                   | 10.6 us                                                | 10.7 us: 1.01x slower                                                |
| dulwich_log              | 67.9 ms                                                | 68.7 ms: 1.01x slower                                                |
| json_dumps               | 9.85 ms                                                | 9.96 ms: 1.01x slower                                                |
| bench_thread_pool        | 827 us                                                 | 839 us: 1.01x slower                                                 |
| sqlglot_optimize         | 53.3 ms                                                | 54.1 ms: 1.02x slower                                                |
| pprint_safe_repr         | 735 ms                                                 | 748 ms: 1.02x slower                                                 |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.02x slower                                                |
| json                     | 4.77 ms                                                | 4.86 ms: 1.02x slower                                                |
| regex_effbot             | 3.55 ms                                                | 3.63 ms: 1.02x slower                                                |
| pprint_pformat           | 1.50 sec                                               | 1.54 sec: 1.02x slower                                               |
| regex_compile            | 144 ms                                                 | 147 ms: 1.02x slower                                                 |
| mdp                      | 2.57 sec                                               | 2.63 sec: 1.02x slower                                               |
| chaos                    | 63.5 ms                                                | 65.4 ms: 1.03x slower                                                |
| float                    | 80.7 ms                                                | 83.3 ms: 1.03x slower                                                |
| mypy2                    | 344 ms                                                 | 355 ms: 1.03x slower                                                 |
| deepcopy_memo            | 37.4 us                                                | 38.6 us: 1.03x slower                                                |
| python_startup           | 9.47 ms                                                | 9.84 ms: 1.04x slower                                                |
| scimark_fft              | 358 ms                                                 | 373 ms: 1.04x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.04x slower                                               |
| unpack_sequence          | 44.8 ns                                                | 46.9 ns: 1.05x slower                                                |
| unpickle_pure_python     | 218 us                                                 | 228 us: 1.05x slower                                                 |
| typing_runtime_protocols | 146 us                                                 | 153 us: 1.05x slower                                                 |
| spectral_norm            | 106 ms                                                 | 113 ms: 1.06x slower                                                 |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                                 |
| python_startup_no_site   | 6.90 ms                                                | 7.32 ms: 1.06x slower                                                |
| pyflate                  | 450 ms                                                 | 479 ms: 1.06x slower                                                 |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.05 ms: 1.06x slower                                                |
| regex_dna                | 209 ms                                                 | 222 ms: 1.07x slower                                                 |
| pycparser                | 1.15 sec                                               | 1.22 sec: 1.07x slower                                               |
| async_generators         | 440 ms                                                 | 475 ms: 1.08x slower                                                 |
| meteor_contest           | 105 ms                                                 | 113 ms: 1.08x slower                                                 |
| mako                     | 10.7 ms                                                | 11.7 ms: 1.09x slower                                                |
| go                       | 136 ms                                                 | 148 ms: 1.09x slower                                                 |
| fannkuch                 | 387 ms                                                 | 430 ms: 1.11x slower                                                 |
| richards_super           | 49.0 ms                                                | 54.7 ms: 1.12x slower                                                |
| richards                 | 43.2 ms                                                | 48.5 ms: 1.12x slower                                                |
| nbody                    | 88.8 ms                                                | 99.8 ms: 1.12x slower                                                |
| regex_v8                 | 22.3 ms                                                | 25.4 ms: 1.14x slower                                                |
| nqueens                  | 81.1 ms                                                | 93.7 ms: 1.15x slower                                                |
| hexiom                   | 6.12 ms                                                | 7.13 ms: 1.16x slower                                                |
| comprehensions           | 20.4 us                                                | 23.9 us: 1.17x slower                                                |
| telco                    | 6.87 ms                                                | 8.25 ms: 1.20x slower                                                |
| dask                     | 365 ms                                                 | 532 ms: 1.46x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.03x slower                                                         |

Benchmark hidden because not significant (11): pickle_pure_python, xml_etree_process, async_tree_cpu_io_mixed, bench_mp_pool, tomli_loads, gc_traversal, pickle_list, docutils, xml_etree_iterparse, scimark_lu, async_tree_memoization
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.97% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
