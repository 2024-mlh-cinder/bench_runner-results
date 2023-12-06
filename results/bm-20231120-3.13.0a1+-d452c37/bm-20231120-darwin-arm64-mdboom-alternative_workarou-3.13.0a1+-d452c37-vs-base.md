
# Results vs. base

- fork: mdboom
- ref: alternative_workarou
- machine: darwin-arm64
- commit hash: d452c37
- commit date: 2023-11-20
- overall geometric mean: 1.00x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 174 ms                                                                 | 174 ms: 1.00x slower                                                   |
| chameleon      | 4.83 ms                                                                | 4.86 ms: 1.01x slower                                                  |
| docutils       | 1.49 sec                                                               | 1.51 sec: 1.01x slower                                                 |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

Benchmark hidden because not significant (8): async_tree_none, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_io, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 79.0 ms                                                                | 79.2 ms: 1.00x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (2): pidigits, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                                 | 149 ms: 1.00x slower                                                   |
| regex_compile  | 78.7 ms                                                                | 78.9 ms: 1.00x slower                                                  |
| regex_v8       | 16.9 ms                                                                | 16.9 ms: 1.00x slower                                                  |
| regex_effbot   | 2.57 ms                                                                | 2.58 ms: 1.01x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|----------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_dict          | 18.0 us                                                                | 17.9 us: 1.01x faster                                                  |
| xml_etree_generate   | 58.4 ms                                                                | 58.2 ms: 1.00x faster                                                  |
| pickle               | 7.35 us                                                                | 7.37 us: 1.00x slower                                                  |
| unpickle_pure_python | 161 us                                                                 | 161 us: 1.00x slower                                                   |
| json_dumps           | 6.56 ms                                                                | 6.59 ms: 1.00x slower                                                  |
| xml_etree_process    | 40.2 ms                                                                | 40.4 ms: 1.01x slower                                                  |
| pickle_pure_python   | 203 us                                                                 | 205 us: 1.01x slower                                                   |
| xml_etree_iterparse  | 76.2 ms                                                                | 76.8 ms: 1.01x slower                                                  |
| xml_etree_parse      | 107 ms                                                                 | 108 ms: 1.01x slower                                                   |
| pickle_list          | 2.90 us                                                                | 2.94 us: 1.01x slower                                                  |
| Geometric mean       | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (4): unpickle, json_loads, unpickle_list, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.6 ms                                                                | 12.3 ms: 1.05x slower                                                  |
| python_startup_no_site | 10.3 ms                                                                | 10.8 ms: 1.05x slower                                                  |
| Geometric mean         | (ref)                                                                  | 1.05x slower                                                           |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1+-d452c37 |
|--------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| coverage                 | 48.4 ms                                                                | 47.5 ms: 1.02x faster                                                  |
| scimark_lu               | 75.9 ms                                                                | 74.8 ms: 1.01x faster                                                  |
| pickle_dict              | 18.0 us                                                                | 17.9 us: 1.01x faster                                                  |
| typing_runtime_protocols | 76.4 us                                                                | 75.9 us: 1.01x faster                                                  |
| sympy_expand             | 255 ms                                                                 | 254 ms: 1.01x faster                                                   |
| crypto_pyaes             | 49.7 ms                                                                | 49.4 ms: 1.01x faster                                                  |
| xml_etree_generate       | 58.4 ms                                                                | 58.2 ms: 1.00x faster                                                  |
| chaos                    | 43.7 ms                                                                | 43.5 ms: 1.00x faster                                                  |
| logging_format           | 3.94 us                                                                | 3.93 us: 1.00x faster                                                  |
| regex_dna                | 149 ms                                                                 | 149 ms: 1.00x slower                                                   |
| scimark_monte_carlo      | 48.4 ms                                                                | 48.5 ms: 1.00x slower                                                  |
| sqlglot_normalize        | 191 ms                                                                 | 191 ms: 1.00x slower                                                   |
| nbody                    | 79.0 ms                                                                | 79.2 ms: 1.00x slower                                                  |
| pickle                   | 7.35 us                                                                | 7.37 us: 1.00x slower                                                  |
| regex_compile            | 78.7 ms                                                                | 78.9 ms: 1.00x slower                                                  |
| generators               | 25.6 ms                                                                | 25.6 ms: 1.00x slower                                                  |
| unpickle_pure_python     | 161 us                                                                 | 161 us: 1.00x slower                                                   |
| comprehensions           | 12.6 us                                                                | 12.6 us: 1.00x slower                                                  |
| hexiom                   | 4.96 ms                                                                | 4.97 ms: 1.00x slower                                                  |
| sqlglot_optimize         | 35.4 ms                                                                | 35.5 ms: 1.00x slower                                                  |
| 2to3                     | 174 ms                                                                 | 174 ms: 1.00x slower                                                   |
| async_generators         | 304 ms                                                                 | 306 ms: 1.00x slower                                                   |
| deepcopy_memo            | 25.2 us                                                                | 25.3 us: 1.00x slower                                                  |
| regex_v8                 | 16.9 ms                                                                | 16.9 ms: 1.00x slower                                                  |
| json_dumps               | 6.56 ms                                                                | 6.59 ms: 1.00x slower                                                  |
| raytrace                 | 189 ms                                                                 | 189 ms: 1.00x slower                                                   |
| sympy_integrate          | 11.1 ms                                                                | 11.2 ms: 1.00x slower                                                  |
| bench_thread_pool        | 514 us                                                                 | 516 us: 1.00x slower                                                   |
| deepcopy                 | 230 us                                                                 | 232 us: 1.00x slower                                                   |
| fannkuch                 | 287 ms                                                                 | 288 ms: 1.01x slower                                                   |
| xml_etree_process        | 40.2 ms                                                                | 40.4 ms: 1.01x slower                                                  |
| deltablue                | 2.48 ms                                                                | 2.49 ms: 1.01x slower                                                  |
| meteor_contest           | 74.9 ms                                                                | 75.4 ms: 1.01x slower                                                  |
| chameleon                | 4.83 ms                                                                | 4.86 ms: 1.01x slower                                                  |
| regex_effbot             | 2.57 ms                                                                | 2.58 ms: 1.01x slower                                                  |
| pprint_pformat           | 1.06 sec                                                               | 1.07 sec: 1.01x slower                                                 |
| pickle_pure_python       | 203 us                                                                 | 205 us: 1.01x slower                                                   |
| scimark_fft              | 208 ms                                                                 | 210 ms: 1.01x slower                                                   |
| xml_etree_iterparse      | 76.2 ms                                                                | 76.8 ms: 1.01x slower                                                  |
| richards                 | 34.5 ms                                                                | 34.8 ms: 1.01x slower                                                  |
| docutils                 | 1.49 sec                                                               | 1.51 sec: 1.01x slower                                                 |
| deepcopy_reduce          | 2.05 us                                                                | 2.08 us: 1.01x slower                                                  |
| xml_etree_parse          | 107 ms                                                                 | 108 ms: 1.01x slower                                                   |
| pickle_list              | 2.90 us                                                                | 2.94 us: 1.01x slower                                                  |
| sqlite_synth             | 1.65 us                                                                | 1.67 us: 1.01x slower                                                  |
| bench_mp_pool            | 43.6 ms                                                                | 44.5 ms: 1.02x slower                                                  |
| telco                    | 4.64 ms                                                                | 4.76 ms: 1.02x slower                                                  |
| pathlib                  | 23.6 ms                                                                | 24.3 ms: 1.03x slower                                                  |
| python_startup           | 11.6 ms                                                                | 12.3 ms: 1.05x slower                                                  |
| python_startup_no_site   | 10.3 ms                                                                | 10.8 ms: 1.05x slower                                                  |
| Geometric mean           | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (43): async_tree_none, unpickle, json, unpack_sequence, asyncio_tcp_ssl, sqlglot_transpile, coroutines, async_tree_memoization_tg, json_loads, create_gc_cycles, unpickle_list, tomli_loads, dulwich_log, sqlglot_parse, mypy2, logging_silent, async_tree_cpu_io_mixed_tg, sympy_sum, gc_traversal, richards_super, async_tree_io_tg, pycparser, async_tree_cpu_io_mixed, pidigits, asyncio_websockets, sympy_str, float, scimark_sparse_mat_mult, go, scimark_sor, pprint_safe_repr, logging_simple, mako, pyflate, async_tree_memoization, async_tree_io, nqueens, async_tree_none_tg, mdp, spectral_norm, dask, tornado_http, asyncio_tcp


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
