
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 96e42d2
- commit date: 2023-10-08
- overall geometric mean: 1.00x faster
- HPT reliability: 90.46%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-darwin-arm64-python-3.12-3.12.0+-96e42d2 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 171 ms                                                 | 171 ms: 1.00x slower                                 |
| docutils       | 1.54 sec                                               | 1.54 sec: 1.00x slower                               |
| Geometric mean | (ref)                                                  | 1.00x slower                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

Benchmark hidden because not significant (3): float, pidigits, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-darwin-arm64-python-3.12-3.12.0+-96e42d2 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_v8       | 16.0 ms                                                | 15.7 ms: 1.02x faster                                |
| regex_dna      | 151 ms                                                 | 150 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmark hidden because not significant (2): regex_effbot, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-darwin-arm64-python-3.12-3.12.0+-96e42d2 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.89 us: 1.01x faster                                |
| pickle               | 7.45 us                                                | 7.36 us: 1.01x faster                                |
| unpickle_pure_python | 145 us                                                 | 144 us: 1.00x faster                                 |
| xml_etree_generate   | 55.8 ms                                                | 55.9 ms: 1.00x slower                                |
| json_loads           | 17.6 us                                                | 17.7 us: 1.00x slower                                |
| json_dumps           | 6.43 ms                                                | 6.45 ms: 1.00x slower                                |
| xml_etree_process    | 38.5 ms                                                | 38.7 ms: 1.00x slower                                |
| pickle_pure_python   | 188 us                                                 | 189 us: 1.01x slower                                 |
| unpickle_list        | 3.22 us                                                | 3.24 us: 1.01x slower                                |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                 |
| xml_etree_iterparse  | 74.3 ms                                                | 75.2 ms: 1.01x slower                                |
| Geometric mean       | (ref)                                                  | 1.00x slower                                         |

Benchmark hidden because not significant (3): tomli_loads, pickle_dict, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-darwin-arm64-python-3.12-3.12.0+-96e42d2 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 11.5 ms                                                | 11.9 ms: 1.03x slower                                |
| python_startup_no_site | 9.43 ms                                                | 9.78 ms: 1.04x slower                                |
| Geometric mean         | (ref)                                                  | 1.04x slower                                         |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-darwin-arm64-python-3.12-3.12.0+-96e42d2 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mypy2                    | 259 ms                                                 | 192 ms: 1.35x faster                                 |
| json                     | 3.05 ms                                                | 2.97 ms: 1.03x faster                                |
| mdp                      | 1.68 sec                                               | 1.64 sec: 1.02x faster                               |
| unpack_sequence          | 28.8 ns                                                | 28.3 ns: 1.02x faster                                |
| bench_mp_pool            | 45.9 ms                                                | 45.0 ms: 1.02x faster                                |
| regex_v8                 | 16.0 ms                                                | 15.7 ms: 1.02x faster                                |
| fannkuch                 | 267 ms                                                 | 263 ms: 1.02x faster                                 |
| pickle_list              | 2.92 us                                                | 2.89 us: 1.01x faster                                |
| pickle                   | 7.45 us                                                | 7.36 us: 1.01x faster                                |
| nqueens                  | 60.6 ms                                                | 60.0 ms: 1.01x faster                                |
| regex_dna                | 151 ms                                                 | 150 ms: 1.01x faster                                 |
| create_gc_cycles         | 702 us                                                 | 698 us: 1.01x faster                                 |
| sqlalchemy_imperative    | 7.02 ms                                                | 6.98 ms: 1.01x faster                                |
| sqlalchemy_declarative   | 65.9 ms                                                | 65.6 ms: 1.00x faster                                |
| unpickle_pure_python     | 145 us                                                 | 144 us: 1.00x faster                                 |
| telco                    | 3.82 ms                                                | 3.81 ms: 1.00x faster                                |
| spectral_norm            | 75.0 ms                                                | 74.8 ms: 1.00x faster                                |
| coroutines               | 18.2 ms                                                | 18.2 ms: 1.00x faster                                |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x faster                                |
| pprint_pformat           | 1.00 sec                                               | 1.00 sec: 1.00x faster                               |
| hexiom                   | 4.24 ms                                                | 4.24 ms: 1.00x slower                                |
| 2to3                     | 171 ms                                                 | 171 ms: 1.00x slower                                 |
| xml_etree_generate       | 55.8 ms                                                | 55.9 ms: 1.00x slower                                |
| docutils                 | 1.54 sec                                               | 1.54 sec: 1.00x slower                               |
| sqlite_synth             | 1.58 us                                                | 1.59 us: 1.00x slower                                |
| json_loads               | 17.6 us                                                | 17.7 us: 1.00x slower                                |
| json_dumps               | 6.43 ms                                                | 6.45 ms: 1.00x slower                                |
| pyflate                  | 329 ms                                                 | 330 ms: 1.00x slower                                 |
| xml_etree_process        | 38.5 ms                                                | 38.7 ms: 1.00x slower                                |
| logging_silent           | 67.7 ns                                                | 68.0 ns: 1.00x slower                                |
| deepcopy_reduce          | 2.02 us                                                | 2.03 us: 1.01x slower                                |
| pickle_pure_python       | 188 us                                                 | 189 us: 1.01x slower                                 |
| typing_runtime_protocols | 90.7 us                                                | 91.2 us: 1.01x slower                                |
| raytrace                 | 246 ms                                                 | 248 ms: 1.01x slower                                 |
| unpickle_list            | 3.22 us                                                | 3.24 us: 1.01x slower                                |
| dulwich_log              | 30.3 ms                                                | 30.5 ms: 1.01x slower                                |
| pycparser                | 670 ms                                                 | 675 ms: 1.01x slower                                 |
| bench_thread_pool        | 489 us                                                 | 493 us: 1.01x slower                                 |
| async_generators         | 303 ms                                                 | 305 ms: 1.01x slower                                 |
| deepcopy_memo            | 24.5 us                                                | 24.7 us: 1.01x slower                                |
| richards_super           | 34.9 ms                                                | 35.1 ms: 1.01x slower                                |
| logging_format           | 3.97 us                                                | 4.00 us: 1.01x slower                                |
| logging_simple           | 3.69 us                                                | 3.72 us: 1.01x slower                                |
| chaos                    | 45.2 ms                                                | 45.6 ms: 1.01x slower                                |
| crypto_pyaes             | 52.3 ms                                                | 52.7 ms: 1.01x slower                                |
| meteor_contest           | 72.9 ms                                                | 73.6 ms: 1.01x slower                                |
| xml_etree_parse          | 109 ms                                                 | 110 ms: 1.01x slower                                 |
| deepcopy                 | 224 us                                                 | 226 us: 1.01x slower                                 |
| scimark_fft              | 198 ms                                                 | 200 ms: 1.01x slower                                 |
| richards                 | 31.1 ms                                                | 31.4 ms: 1.01x slower                                |
| xml_etree_iterparse      | 74.3 ms                                                | 75.2 ms: 1.01x slower                                |
| scimark_sor              | 94.1 ms                                                | 95.8 ms: 1.02x slower                                |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.22 ms: 1.02x slower                                |
| comprehensions           | 15.7 us                                                | 16.1 us: 1.02x slower                                |
| python_startup           | 11.5 ms                                                | 11.9 ms: 1.03x slower                                |
| python_startup_no_site   | 9.43 ms                                                | 9.78 ms: 1.04x slower                                |
| Geometric mean           | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (29): tornado_http, tomli_loads, mako, dask, regex_effbot, coverage, go, pickle_dict, async_tree_io, sqlglot_parse, regex_compile, float, pidigits, async_tree_none, async_tree_cpu_io_mixed, pprint_safe_repr, unpickle, scimark_monte_carlo, sqlglot_optimize, nbody, scimark_lu, sqlglot_normalize, deltablue, generators, sqlglot_transpile, async_tree_memoization, pathlib, asyncio_tcp_ssl, asyncio_tcp


# HPT report

- Reliability score: 90.46% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
