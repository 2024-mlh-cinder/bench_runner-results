
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 744f752
- commit date: 2023-10-14
- overall geometric mean: 1.02x faster
- HPT reliability: 99.91%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 171 ms                                                 | 169 ms: 1.01x faster                                 |
| docutils       | 1.54 sec                                               | 1.51 sec: 1.02x faster                               |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| float          | 58.2 ms                                                | 56.6 ms: 1.03x faster                                |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| nbody          | 68.6 ms                                                | 68.7 ms: 1.00x slower                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_v8       | 16.0 ms                                                | 15.6 ms: 1.02x faster                                |
| regex_dna      | 151 ms                                                 | 149 ms: 1.01x faster                                 |
| regex_effbot   | 2.58 ms                                                | 2.57 ms: 1.01x faster                                |
| regex_compile  | 75.8 ms                                                | 75.4 ms: 1.01x faster                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.87 us: 1.02x faster                                |
| json_dumps           | 6.43 ms                                                | 6.36 ms: 1.01x faster                                |
| pickle               | 7.45 us                                                | 7.38 us: 1.01x faster                                |
| unpickle_pure_python | 145 us                                                 | 144 us: 1.00x faster                                 |
| unpickle             | 9.26 us                                                | 9.29 us: 1.00x slower                                |
| xml_etree_generate   | 55.8 ms                                                | 56.0 ms: 1.00x slower                                |
| json_loads           | 17.6 us                                                | 17.7 us: 1.00x slower                                |
| xml_etree_process    | 38.5 ms                                                | 38.9 ms: 1.01x slower                                |
| pickle_pure_python   | 188 us                                                 | 190 us: 1.01x slower                                 |
| Geometric mean       | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (5): tomli_loads, unpickle_list, xml_etree_iterparse, pickle_dict, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 11.5 ms                                                | 12.6 ms: 1.09x slower                                |
| python_startup_no_site | 9.43 ms                                                | 10.3 ms: 1.10x slower                                |
| Geometric mean         | (ref)                                                  | 1.09x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.52 ms: 1.01x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-darwin-arm64-python-3.12-3.12.0+-744f752 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mypy2                    | 259 ms                                                 | 190 ms: 1.36x faster                                 |
| raytrace                 | 246 ms                                                 | 207 ms: 1.19x faster                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 43.1 ms: 1.16x faster                                |
| go                       | 107 ms                                                 | 94.5 ms: 1.13x faster                                |
| generators               | 28.5 ms                                                | 26.1 ms: 1.09x faster                                |
| scimark_sor              | 94.1 ms                                                | 86.3 ms: 1.09x faster                                |
| sqlglot_parse            | 898 us                                                 | 830 us: 1.08x faster                                 |
| deltablue                | 2.59 ms                                                | 2.41 ms: 1.08x faster                                |
| chaos                    | 45.2 ms                                                | 42.2 ms: 1.07x faster                                |
| sqlglot_transpile        | 1.07 ms                                                | 1.01 ms: 1.07x faster                                |
| coroutines               | 18.2 ms                                                | 17.3 ms: 1.05x faster                                |
| pyflate                  | 329 ms                                                 | 316 ms: 1.04x faster                                 |
| comprehensions           | 15.7 us                                                | 15.1 us: 1.04x faster                                |
| logging_simple           | 3.69 us                                                | 3.56 us: 1.04x faster                                |
| logging_format           | 3.97 us                                                | 3.84 us: 1.04x faster                                |
| richards_super           | 34.9 ms                                                | 33.9 ms: 1.03x faster                                |
| float                    | 58.2 ms                                                | 56.6 ms: 1.03x faster                                |
| richards                 | 31.1 ms                                                | 30.3 ms: 1.03x faster                                |
| regex_v8                 | 16.0 ms                                                | 15.6 ms: 1.02x faster                                |
| json                     | 3.05 ms                                                | 2.98 ms: 1.02x faster                                |
| telco                    | 3.82 ms                                                | 3.73 ms: 1.02x faster                                |
| pickle_list              | 2.92 us                                                | 2.87 us: 1.02x faster                                |
| docutils                 | 1.54 sec                                               | 1.51 sec: 1.02x faster                               |
| nqueens                  | 60.6 ms                                                | 59.5 ms: 1.02x faster                                |
| fannkuch                 | 267 ms                                                 | 263 ms: 1.02x faster                                 |
| sqlalchemy_imperative    | 7.02 ms                                                | 6.91 ms: 1.02x faster                                |
| regex_dna                | 151 ms                                                 | 149 ms: 1.01x faster                                 |
| sqlalchemy_declarative   | 65.9 ms                                                | 65.0 ms: 1.01x faster                                |
| 2to3                     | 171 ms                                                 | 169 ms: 1.01x faster                                 |
| async_tree_io            | 669 ms                                                 | 661 ms: 1.01x faster                                 |
| json_dumps               | 6.43 ms                                                | 6.36 ms: 1.01x faster                                |
| mdp                      | 1.68 sec                                               | 1.66 sec: 1.01x faster                               |
| pickle                   | 7.45 us                                                | 7.38 us: 1.01x faster                                |
| bench_thread_pool        | 489 us                                                 | 485 us: 1.01x faster                                 |
| regex_effbot             | 2.58 ms                                                | 2.57 ms: 1.01x faster                                |
| mako                     | 7.57 ms                                                | 7.52 ms: 1.01x faster                                |
| regex_compile            | 75.8 ms                                                | 75.4 ms: 1.01x faster                                |
| coverage                 | 51.0 ms                                                | 50.8 ms: 1.00x faster                                |
| unpickle_pure_python     | 145 us                                                 | 144 us: 1.00x faster                                 |
| sqlglot_normalize        | 186 ms                                                 | 185 ms: 1.00x faster                                 |
| crypto_pyaes             | 52.3 ms                                                | 52.0 ms: 1.00x faster                                |
| dulwich_log              | 30.3 ms                                                | 30.2 ms: 1.00x faster                                |
| sqlglot_optimize         | 34.3 ms                                                | 34.2 ms: 1.00x faster                                |
| create_gc_cycles         | 702 us                                                 | 699 us: 1.00x faster                                 |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x faster                                |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| nbody                    | 68.6 ms                                                | 68.7 ms: 1.00x slower                                |
| unpickle                 | 9.26 us                                                | 9.29 us: 1.00x slower                                |
| xml_etree_generate       | 55.8 ms                                                | 56.0 ms: 1.00x slower                                |
| json_loads               | 17.6 us                                                | 17.7 us: 1.00x slower                                |
| logging_silent           | 67.7 ns                                                | 68.0 ns: 1.01x slower                                |
| meteor_contest           | 72.9 ms                                                | 73.3 ms: 1.01x slower                                |
| pycparser                | 670 ms                                                 | 675 ms: 1.01x slower                                 |
| hexiom                   | 4.24 ms                                                | 4.26 ms: 1.01x slower                                |
| scimark_lu               | 71.7 ms                                                | 72.3 ms: 1.01x slower                                |
| typing_runtime_protocols | 90.7 us                                                | 91.5 us: 1.01x slower                                |
| xml_etree_process        | 38.5 ms                                                | 38.9 ms: 1.01x slower                                |
| async_generators         | 303 ms                                                 | 306 ms: 1.01x slower                                 |
| async_tree_none          | 262 ms                                                 | 265 ms: 1.01x slower                                 |
| deepcopy                 | 224 us                                                 | 226 us: 1.01x slower                                 |
| pickle_pure_python       | 188 us                                                 | 190 us: 1.01x slower                                 |
| deepcopy_reduce          | 2.02 us                                                | 2.05 us: 1.01x slower                                |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.20 ms: 1.02x slower                                |
| pathlib                  | 28.8 ms                                                | 29.3 ms: 1.02x slower                                |
| scimark_fft              | 198 ms                                                 | 201 ms: 1.02x slower                                 |
| deepcopy_memo            | 24.5 us                                                | 24.9 us: 1.02x slower                                |
| python_startup           | 11.5 ms                                                | 12.6 ms: 1.09x slower                                |
| python_startup_no_site   | 9.43 ms                                                | 10.3 ms: 1.10x slower                                |
| Geometric mean           | (ref)                                                  | 1.02x faster                                         |

Benchmark hidden because not significant (17): tornado_http, tomli_loads, bench_mp_pool, unpack_sequence, unpickle_list, dask, pprint_safe_repr, pprint_pformat, spectral_norm, sqlite_synth, xml_etree_iterparse, pickle_dict, async_tree_cpu_io_mixed, xml_etree_parse, asyncio_tcp_ssl, async_tree_memoization, asyncio_tcp


# HPT report

- Reliability score: 99.91% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
