
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.02x faster
- HPT reliability: 99.81%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 171 ms                                                 | 168 ms: 1.01x faster                                 |
| docutils       | 1.54 sec                                               | 1.50 sec: 1.02x faster                               |
| Geometric mean | (ref)                                                  | 1.02x faster                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| float          | 58.2 ms                                                | 56.5 ms: 1.03x faster                                |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| nbody          | 68.6 ms                                                | 69.3 ms: 1.01x slower                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_v8       | 16.0 ms                                                | 15.6 ms: 1.02x faster                                |
| regex_dna      | 151 ms                                                 | 149 ms: 1.01x faster                                 |
| regex_compile  | 75.8 ms                                                | 75.1 ms: 1.01x faster                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 6.43 ms                                                | 6.31 ms: 1.02x faster                                |
| pickle               | 7.45 us                                                | 7.34 us: 1.01x faster                                |
| pickle_list          | 2.92 us                                                | 2.88 us: 1.01x faster                                |
| unpickle_pure_python | 145 us                                                 | 144 us: 1.01x faster                                 |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                |
| xml_etree_generate   | 55.8 ms                                                | 55.9 ms: 1.00x slower                                |
| json_loads           | 17.6 us                                                | 17.7 us: 1.00x slower                                |
| unpickle_list        | 3.22 us                                                | 3.23 us: 1.00x slower                                |
| xml_etree_process    | 38.5 ms                                                | 38.7 ms: 1.01x slower                                |
| unpickle             | 9.26 us                                                | 9.31 us: 1.01x slower                                |
| xml_etree_iterparse  | 74.3 ms                                                | 75.0 ms: 1.01x slower                                |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                 |
| Geometric mean       | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (2): pickle_pure_python, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.01 ms: 1.05x faster                                |
| python_startup         | 11.5 ms                                                | 11.2 ms: 1.04x faster                                |
| Geometric mean         | (ref)                                                  | 1.04x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.52 ms: 1.01x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mypy2                    | 259 ms                                                 | 190 ms: 1.36x faster                                 |
| raytrace                 | 246 ms                                                 | 207 ms: 1.19x faster                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 43.2 ms: 1.16x faster                                |
| go                       | 107 ms                                                 | 94.7 ms: 1.13x faster                                |
| scimark_sor              | 94.1 ms                                                | 85.9 ms: 1.10x faster                                |
| generators               | 28.5 ms                                                | 26.2 ms: 1.09x faster                                |
| sqlglot_parse            | 898 us                                                 | 830 us: 1.08x faster                                 |
| deltablue                | 2.59 ms                                                | 2.40 ms: 1.08x faster                                |
| chaos                    | 45.2 ms                                                | 42.1 ms: 1.07x faster                                |
| sqlglot_transpile        | 1.07 ms                                                | 1.01 ms: 1.06x faster                                |
| coroutines               | 18.2 ms                                                | 17.3 ms: 1.05x faster                                |
| python_startup_no_site   | 9.43 ms                                                | 9.01 ms: 1.05x faster                                |
| pyflate                  | 329 ms                                                 | 316 ms: 1.04x faster                                 |
| bench_mp_pool            | 45.9 ms                                                | 44.2 ms: 1.04x faster                                |
| python_startup           | 11.5 ms                                                | 11.2 ms: 1.04x faster                                |
| comprehensions           | 15.7 us                                                | 15.2 us: 1.03x faster                                |
| richards_super           | 34.9 ms                                                | 33.8 ms: 1.03x faster                                |
| float                    | 58.2 ms                                                | 56.5 ms: 1.03x faster                                |
| mdp                      | 1.68 sec                                               | 1.63 sec: 1.03x faster                               |
| richards                 | 31.1 ms                                                | 30.3 ms: 1.03x faster                                |
| logging_simple           | 3.69 us                                                | 3.60 us: 1.03x faster                                |
| json                     | 3.05 ms                                                | 2.98 ms: 1.02x faster                                |
| logging_format           | 3.97 us                                                | 3.88 us: 1.02x faster                                |
| regex_v8                 | 16.0 ms                                                | 15.6 ms: 1.02x faster                                |
| docutils                 | 1.54 sec                                               | 1.50 sec: 1.02x faster                               |
| sqlalchemy_imperative    | 7.02 ms                                                | 6.88 ms: 1.02x faster                                |
| sqlalchemy_declarative   | 65.9 ms                                                | 64.7 ms: 1.02x faster                                |
| json_dumps               | 6.43 ms                                                | 6.31 ms: 1.02x faster                                |
| unpack_sequence          | 28.8 ns                                                | 28.4 ns: 1.01x faster                                |
| pickle                   | 7.45 us                                                | 7.34 us: 1.01x faster                                |
| regex_dna                | 151 ms                                                 | 149 ms: 1.01x faster                                 |
| pickle_list              | 2.92 us                                                | 2.88 us: 1.01x faster                                |
| 2to3                     | 171 ms                                                 | 168 ms: 1.01x faster                                 |
| nqueens                  | 60.6 ms                                                | 59.8 ms: 1.01x faster                                |
| create_gc_cycles         | 702 us                                                 | 695 us: 1.01x faster                                 |
| async_tree_io            | 669 ms                                                 | 662 ms: 1.01x faster                                 |
| regex_compile            | 75.8 ms                                                | 75.1 ms: 1.01x faster                                |
| pprint_pformat           | 1.00 sec                                               | 997 ms: 1.01x faster                                 |
| mako                     | 7.57 ms                                                | 7.52 ms: 1.01x faster                                |
| bench_thread_pool        | 489 us                                                 | 486 us: 1.01x faster                                 |
| coverage                 | 51.0 ms                                                | 50.7 ms: 1.01x faster                                |
| unpickle_pure_python     | 145 us                                                 | 144 us: 1.01x faster                                 |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                |
| crypto_pyaes             | 52.3 ms                                                | 52.0 ms: 1.01x faster                                |
| typing_runtime_protocols | 90.7 us                                                | 90.3 us: 1.00x faster                                |
| dulwich_log              | 30.3 ms                                                | 30.2 ms: 1.00x faster                                |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x faster                                |
| meteor_contest           | 72.9 ms                                                | 72.8 ms: 1.00x faster                                |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| xml_etree_generate       | 55.8 ms                                                | 55.9 ms: 1.00x slower                                |
| scimark_lu               | 71.7 ms                                                | 71.9 ms: 1.00x slower                                |
| json_loads               | 17.6 us                                                | 17.7 us: 1.00x slower                                |
| sqlite_synth             | 1.58 us                                                | 1.59 us: 1.00x slower                                |
| unpickle_list            | 3.22 us                                                | 3.23 us: 1.00x slower                                |
| hexiom                   | 4.24 ms                                                | 4.26 ms: 1.00x slower                                |
| xml_etree_process        | 38.5 ms                                                | 38.7 ms: 1.01x slower                                |
| unpickle                 | 9.26 us                                                | 9.31 us: 1.01x slower                                |
| telco                    | 3.82 ms                                                | 3.84 ms: 1.01x slower                                |
| async_generators         | 303 ms                                                 | 306 ms: 1.01x slower                                 |
| xml_etree_iterparse      | 74.3 ms                                                | 75.0 ms: 1.01x slower                                |
| logging_silent           | 67.7 ns                                                | 68.3 ns: 1.01x slower                                |
| nbody                    | 68.6 ms                                                | 69.3 ms: 1.01x slower                                |
| pprint_safe_repr         | 493 ms                                                 | 499 ms: 1.01x slower                                 |
| scimark_fft              | 198 ms                                                 | 200 ms: 1.01x slower                                 |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.20 ms: 1.01x slower                                |
| deepcopy                 | 224 us                                                 | 227 us: 1.01x slower                                 |
| deepcopy_memo            | 24.5 us                                                | 24.9 us: 1.02x slower                                |
| deepcopy_reduce          | 2.02 us                                                | 2.05 us: 1.02x slower                                |
| xml_etree_parse          | 109 ms                                                 | 111 ms: 1.02x slower                                 |
| Geometric mean           | (ref)                                                  | 1.02x faster                                         |

Benchmark hidden because not significant (16): asyncio_tcp, tornado_http, dask, asyncio_tcp_ssl, spectral_norm, pickle_pure_python, fannkuch, sqlglot_optimize, sqlglot_normalize, tomli_loads, async_tree_cpu_io_mixed, regex_effbot, async_tree_none, pycparser, async_tree_memoization, pathlib


# HPT report

- Reliability score: 99.81% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
