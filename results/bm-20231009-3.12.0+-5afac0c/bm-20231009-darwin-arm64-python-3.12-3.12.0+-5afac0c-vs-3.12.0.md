
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 5afac0c
- commit date: 2023-10-09
- overall geometric mean: 1.00x faster
- HPT reliability: 87.32%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (3): 2to3, docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| float          | 58.2 ms                                                | 58.0 ms: 1.00x faster                                |
| nbody          | 68.6 ms                                                | 68.7 ms: 1.00x slower                                |
| Geometric mean | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 149 ms: 1.01x faster                                 |
| regex_v8       | 16.0 ms                                                | 15.9 ms: 1.01x faster                                |
| regex_compile  | 75.8 ms                                                | 75.8 ms: 1.00x faster                                |
| Geometric mean | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle               | 7.45 us                                                | 7.35 us: 1.01x faster                                |
| pickle_list          | 2.92 us                                                | 2.91 us: 1.01x faster                                |
| unpickle_pure_python | 145 us                                                 | 144 us: 1.00x faster                                 |
| json_dumps           | 6.43 ms                                                | 6.42 ms: 1.00x faster                                |
| pickle_pure_python   | 188 us                                                 | 189 us: 1.00x slower                                 |
| xml_etree_generate   | 55.8 ms                                                | 55.9 ms: 1.00x slower                                |
| unpickle_list        | 3.22 us                                                | 3.26 us: 1.01x slower                                |
| xml_etree_iterparse  | 74.3 ms                                                | 75.5 ms: 1.02x slower                                |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                 |
| Geometric mean       | (ref)                                                  | 1.00x slower                                         |

Benchmark hidden because not significant (5): tomli_loads, pickle_dict, json_loads, xml_etree_process, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 11.5 ms                                                | 12.1 ms: 1.04x slower                                |
| python_startup_no_site | 9.43 ms                                                | 9.90 ms: 1.05x slower                                |
| Geometric mean         | (ref)                                                  | 1.05x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.55 ms: 1.00x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mypy2                    | 259 ms                                                 | 192 ms: 1.35x faster                                 |
| json                     | 3.05 ms                                                | 2.98 ms: 1.02x faster                                |
| bench_mp_pool            | 45.9 ms                                                | 45.0 ms: 1.02x faster                                |
| fannkuch                 | 267 ms                                                 | 263 ms: 1.01x faster                                 |
| pickle                   | 7.45 us                                                | 7.35 us: 1.01x faster                                |
| regex_dna                | 151 ms                                                 | 149 ms: 1.01x faster                                 |
| sqlalchemy_imperative    | 7.02 ms                                                | 6.96 ms: 1.01x faster                                |
| coroutines               | 18.2 ms                                                | 18.1 ms: 1.01x faster                                |
| create_gc_cycles         | 702 us                                                 | 697 us: 1.01x faster                                 |
| regex_v8                 | 16.0 ms                                                | 15.9 ms: 1.01x faster                                |
| nqueens                  | 60.6 ms                                                | 60.2 ms: 1.01x faster                                |
| pickle_list              | 2.92 us                                                | 2.91 us: 1.01x faster                                |
| unpickle_pure_python     | 145 us                                                 | 144 us: 1.00x faster                                 |
| float                    | 58.2 ms                                                | 58.0 ms: 1.00x faster                                |
| spectral_norm            | 75.0 ms                                                | 74.7 ms: 1.00x faster                                |
| mako                     | 7.57 ms                                                | 7.55 ms: 1.00x faster                                |
| async_tree_io            | 669 ms                                                 | 667 ms: 1.00x faster                                 |
| pprint_pformat           | 1.00 sec                                               | 1.00 sec: 1.00x faster                               |
| scimark_monte_carlo      | 50.1 ms                                                | 50.0 ms: 1.00x faster                                |
| pprint_safe_repr         | 493 ms                                                 | 492 ms: 1.00x faster                                 |
| json_dumps               | 6.43 ms                                                | 6.42 ms: 1.00x faster                                |
| regex_compile            | 75.8 ms                                                | 75.8 ms: 1.00x faster                                |
| hexiom                   | 4.24 ms                                                | 4.24 ms: 1.00x slower                                |
| sqlglot_normalize        | 186 ms                                                 | 186 ms: 1.00x slower                                 |
| pickle_pure_python       | 188 us                                                 | 189 us: 1.00x slower                                 |
| pyflate                  | 329 ms                                                 | 330 ms: 1.00x slower                                 |
| xml_etree_generate       | 55.8 ms                                                | 55.9 ms: 1.00x slower                                |
| nbody                    | 68.6 ms                                                | 68.7 ms: 1.00x slower                                |
| telco                    | 3.82 ms                                                | 3.83 ms: 1.00x slower                                |
| logging_silent           | 67.7 ns                                                | 67.9 ns: 1.00x slower                                |
| sqlglot_optimize         | 34.3 ms                                                | 34.4 ms: 1.00x slower                                |
| sqlglot_transpile        | 1.07 ms                                                | 1.08 ms: 1.00x slower                                |
| deepcopy                 | 224 us                                                 | 225 us: 1.00x slower                                 |
| typing_runtime_protocols | 90.7 us                                                | 91.2 us: 1.00x slower                                |
| async_generators         | 303 ms                                                 | 304 ms: 1.01x slower                                 |
| dulwich_log              | 30.3 ms                                                | 30.5 ms: 1.01x slower                                |
| scimark_lu               | 71.7 ms                                                | 72.1 ms: 1.01x slower                                |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.18 ms: 1.01x slower                                |
| chaos                    | 45.2 ms                                                | 45.5 ms: 1.01x slower                                |
| crypto_pyaes             | 52.3 ms                                                | 52.6 ms: 1.01x slower                                |
| richards_super           | 34.9 ms                                                | 35.2 ms: 1.01x slower                                |
| logging_format           | 3.97 us                                                | 4.00 us: 1.01x slower                                |
| deepcopy_memo            | 24.5 us                                                | 24.7 us: 1.01x slower                                |
| pycparser                | 670 ms                                                 | 677 ms: 1.01x slower                                 |
| scimark_fft              | 198 ms                                                 | 200 ms: 1.01x slower                                 |
| logging_simple           | 3.69 us                                                | 3.73 us: 1.01x slower                                |
| meteor_contest           | 72.9 ms                                                | 73.8 ms: 1.01x slower                                |
| richards                 | 31.1 ms                                                | 31.4 ms: 1.01x slower                                |
| unpickle_list            | 3.22 us                                                | 3.26 us: 1.01x slower                                |
| scimark_sor              | 94.1 ms                                                | 95.4 ms: 1.01x slower                                |
| xml_etree_iterparse      | 74.3 ms                                                | 75.5 ms: 1.02x slower                                |
| xml_etree_parse          | 109 ms                                                 | 111 ms: 1.02x slower                                 |
| pathlib                  | 28.8 ms                                                | 29.5 ms: 1.02x slower                                |
| comprehensions           | 15.7 us                                                | 16.1 us: 1.02x slower                                |
| python_startup           | 11.5 ms                                                | 12.1 ms: 1.04x slower                                |
| python_startup_no_site   | 9.43 ms                                                | 9.90 ms: 1.05x slower                                |
| Geometric mean           | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (29): tornado_http, sqlalchemy_declarative, mdp, coverage, bench_thread_pool, tomli_loads, deepcopy_reduce, pickle_dict, asyncio_tcp_ssl, gc_traversal, unpack_sequence, sqlite_synth, sqlglot_parse, pidigits, dask, json_loads, raytrace, xml_etree_process, 2to3, deltablue, docutils, async_tree_cpu_io_mixed, async_tree_none, unpickle, go, async_tree_memoization, generators, regex_effbot, asyncio_tcp


# HPT report

- Reliability score: 87.32% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
