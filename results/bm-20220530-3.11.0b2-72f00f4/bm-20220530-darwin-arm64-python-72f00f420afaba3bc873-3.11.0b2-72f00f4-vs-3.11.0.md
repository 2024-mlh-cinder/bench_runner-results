
# Results vs. 3.11.0

- fork: python
- ref: 72f00f420afaba3bc873
- machine: darwin-arm64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.00x slower
- HPT reliability: 98.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 153 ms: 1.00x faster                                                  |
| chameleon      | 4.21 ms                                                             | 4.32 ms: 1.03x slower                                                 |
| docutils       | 1.43 sec                                                            | 1.42 sec: 1.00x faster                                                |
| html5lib       | 33.3 ms                                                             | 32.7 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                               | 1.01x faster                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|---------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization_tg | 351 ms                                                              | 341 ms: 1.03x faster                                                  |
| async_tree_none_tg        | 277 ms                                                              | 273 ms: 1.01x faster                                                  |
| async_tree_io_tg          | 723 ms                                                              | 721 ms: 1.00x faster                                                  |
| Geometric mean            | (ref)                                                               | 1.00x faster                                                          |

Benchmark hidden because not significant (5): async_tree_io, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 68.5 ms                                                             | 65.5 ms: 1.05x faster                                                 |
| float          | 55.1 ms                                                             | 54.4 ms: 1.01x faster                                                 |
| pidigits       | 280 ms                                                              | 280 ms: 1.00x slower                                                  |
| Geometric mean | (ref)                                                               | 1.02x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.45 ms                                                             | 2.22 ms: 1.10x faster                                                 |
| regex_dna      | 149 ms                                                              | 147 ms: 1.02x faster                                                  |
| regex_v8       | 15.4 ms                                                             | 15.2 ms: 1.01x faster                                                 |
| regex_compile  | 73.5 ms                                                             | 73.8 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                               | 1.03x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 210 us                                                              | 194 us: 1.08x faster                                                  |
| unpickle_pure_python | 162 us                                                              | 151 us: 1.08x faster                                                  |
| pickle_dict          | 17.0 us                                                             | 16.1 us: 1.05x faster                                                 |
| pickle_list          | 2.68 us                                                             | 2.59 us: 1.03x faster                                                 |
| pickle               | 7.17 us                                                             | 7.03 us: 1.02x faster                                                 |
| unpickle             | 8.35 us                                                             | 8.23 us: 1.01x faster                                                 |
| tomli_loads          | 1.32 sec                                                            | 1.30 sec: 1.01x faster                                                |
| xml_etree_generate   | 47.1 ms                                                             | 46.7 ms: 1.01x faster                                                 |
| xml_etree_iterparse  | 67.5 ms                                                             | 66.9 ms: 1.01x faster                                                 |
| json_loads           | 15.5 us                                                             | 15.4 us: 1.01x faster                                                 |
| xml_etree_process    | 34.1 ms                                                             | 33.9 ms: 1.00x faster                                                 |
| xml_etree_parse      | 97.6 ms                                                             | 97.2 ms: 1.00x faster                                                 |
| unpickle_list        | 2.76 us                                                             | 2.80 us: 1.02x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.02x faster                                                          |

Benchmark hidden because not significant (1): json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| python_startup_no_site | 9.37 ms                                                             | 9.31 ms: 1.01x faster                                                 |
| Geometric mean         | (ref)                                                               | 1.01x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.25 ms                                                             | 8.11 ms: 1.02x faster                                                 |
| django_template | 19.6 ms                                                             | 19.8 ms: 1.01x slower                                                 |
| genshi_text     | 14.5 ms                                                             | 14.6 ms: 1.01x slower                                                 |
| genshi_xml      | 28.3 ms                                                             | 28.8 ms: 1.02x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.01x slower                                                          |

All benchmarks:
===============

| Benchmark                 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220530-darwin-arm64-python-72f00f420afaba3bc873-3.11.0b2-72f00f4 |
|---------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot              | 2.45 ms                                                             | 2.22 ms: 1.10x faster                                                 |
| pickle_pure_python        | 210 us                                                              | 194 us: 1.08x faster                                                  |
| unpickle_pure_python      | 162 us                                                              | 151 us: 1.08x faster                                                  |
| gc_traversal              | 2.53 ms                                                             | 2.38 ms: 1.06x faster                                                 |
| mdp                       | 1.84 sec                                                            | 1.74 sec: 1.06x faster                                                |
| pickle_dict               | 17.0 us                                                             | 16.1 us: 1.05x faster                                                 |
| sqlalchemy_imperative     | 7.33 ms                                                             | 6.97 ms: 1.05x faster                                                 |
| nbody                     | 68.5 ms                                                             | 65.5 ms: 1.05x faster                                                 |
| meteor_contest            | 75.3 ms                                                             | 72.5 ms: 1.04x faster                                                 |
| pyflate                   | 295 ms                                                              | 285 ms: 1.04x faster                                                  |
| sqlite_synth              | 1.36 us                                                             | 1.31 us: 1.04x faster                                                 |
| sympy_sum                 | 80.8 ms                                                             | 78.2 ms: 1.03x faster                                                 |
| pickle_list               | 2.68 us                                                             | 2.59 us: 1.03x faster                                                 |
| scimark_monte_carlo       | 45.7 ms                                                             | 44.3 ms: 1.03x faster                                                 |
| deepcopy_memo             | 28.7 us                                                             | 27.8 us: 1.03x faster                                                 |
| async_tree_memoization_tg | 351 ms                                                              | 341 ms: 1.03x faster                                                  |
| raytrace                  | 205 ms                                                              | 200 ms: 1.03x faster                                                  |
| logging_format            | 3.73 us                                                             | 3.63 us: 1.03x faster                                                 |
| logging_simple            | 3.45 us                                                             | 3.37 us: 1.02x faster                                                 |
| pickle                    | 7.17 us                                                             | 7.03 us: 1.02x faster                                                 |
| html5lib                  | 33.3 ms                                                             | 32.7 ms: 1.02x faster                                                 |
| regex_dna                 | 149 ms                                                              | 147 ms: 1.02x faster                                                  |
| dulwich_log               | 29.2 ms                                                             | 28.7 ms: 1.02x faster                                                 |
| scimark_fft               | 186 ms                                                              | 183 ms: 1.02x faster                                                  |
| deepcopy                  | 232 us                                                              | 228 us: 1.02x faster                                                  |
| scimark_sparse_mat_mult   | 3.00 ms                                                             | 2.95 ms: 1.02x faster                                                 |
| deepcopy_reduce           | 1.96 us                                                             | 1.93 us: 1.02x faster                                                 |
| mako                      | 8.25 ms                                                             | 8.11 ms: 1.02x faster                                                 |
| spectral_norm             | 69.4 ms                                                             | 68.4 ms: 1.02x faster                                                 |
| unpickle                  | 8.35 us                                                             | 8.23 us: 1.01x faster                                                 |
| sympy_expand              | 236 ms                                                              | 233 ms: 1.01x faster                                                  |
| sqlalchemy_declarative    | 60.4 ms                                                             | 59.5 ms: 1.01x faster                                                 |
| async_tree_none_tg        | 277 ms                                                              | 273 ms: 1.01x faster                                                  |
| float                     | 55.1 ms                                                             | 54.4 ms: 1.01x faster                                                 |
| thrift                    | 420 us                                                              | 415 us: 1.01x faster                                                  |
| tomli_loads               | 1.32 sec                                                            | 1.30 sec: 1.01x faster                                                |
| crypto_pyaes              | 47.9 ms                                                             | 47.4 ms: 1.01x faster                                                 |
| regex_v8                  | 15.4 ms                                                             | 15.2 ms: 1.01x faster                                                 |
| fannkuch                  | 247 ms                                                              | 244 ms: 1.01x faster                                                  |
| sympy_str                 | 144 ms                                                              | 143 ms: 1.01x faster                                                  |
| xml_etree_generate        | 47.1 ms                                                             | 46.7 ms: 1.01x faster                                                 |
| chaos                     | 48.2 ms                                                             | 47.8 ms: 1.01x faster                                                 |
| xml_etree_iterparse       | 67.5 ms                                                             | 66.9 ms: 1.01x faster                                                 |
| python_startup            | 11.5 ms                                                             | 11.4 ms: 1.01x faster                                                 |
| json_loads                | 15.5 us                                                             | 15.4 us: 1.01x faster                                                 |
| python_startup_no_site    | 9.37 ms                                                             | 9.31 ms: 1.01x faster                                                 |
| mypy2                     | 187 ms                                                              | 186 ms: 1.01x faster                                                  |
| xml_etree_process         | 34.1 ms                                                             | 33.9 ms: 1.00x faster                                                 |
| create_gc_cycles          | 714 us                                                              | 711 us: 1.00x faster                                                  |
| async_generators          | 191 ms                                                              | 191 ms: 1.00x faster                                                  |
| sympy_integrate           | 11.2 ms                                                             | 11.1 ms: 1.00x faster                                                 |
| xml_etree_parse           | 97.6 ms                                                             | 97.2 ms: 1.00x faster                                                 |
| docutils                  | 1.43 sec                                                            | 1.42 sec: 1.00x faster                                                |
| async_tree_io_tg          | 723 ms                                                              | 721 ms: 1.00x faster                                                  |
| 2to3                      | 154 ms                                                              | 153 ms: 1.00x faster                                                  |
| pidigits                  | 280 ms                                                              | 280 ms: 1.00x slower                                                  |
| pprint_pformat            | 986 ms                                                              | 988 ms: 1.00x slower                                                  |
| scimark_lu                | 67.9 ms                                                             | 68.2 ms: 1.00x slower                                                 |
| regex_compile             | 73.5 ms                                                             | 73.8 ms: 1.01x slower                                                 |
| nqueens                   | 54.3 ms                                                             | 54.7 ms: 1.01x slower                                                 |
| hexiom                    | 4.55 ms                                                             | 4.58 ms: 1.01x slower                                                 |
| json                      | 2.77 ms                                                             | 2.79 ms: 1.01x slower                                                 |
| pprint_safe_repr          | 480 ms                                                              | 485 ms: 1.01x slower                                                  |
| django_template           | 19.6 ms                                                             | 19.8 ms: 1.01x slower                                                 |
| genshi_text               | 14.5 ms                                                             | 14.6 ms: 1.01x slower                                                 |
| go                        | 102 ms                                                              | 103 ms: 1.01x slower                                                  |
| unpack_sequence           | 32.3 ns                                                             | 32.7 ns: 1.01x slower                                                 |
| typing_runtime_protocols  | 322 us                                                              | 326 us: 1.01x slower                                                  |
| deltablue                 | 2.69 ms                                                             | 2.72 ms: 1.01x slower                                                 |
| unpickle_list             | 2.76 us                                                             | 2.80 us: 1.02x slower                                                 |
| sqlglot_normalize         | 160 ms                                                              | 163 ms: 1.02x slower                                                  |
| richards                  | 30.7 ms                                                             | 31.3 ms: 1.02x slower                                                 |
| genshi_xml                | 28.3 ms                                                             | 28.8 ms: 1.02x slower                                                 |
| scimark_sor               | 74.4 ms                                                             | 76.1 ms: 1.02x slower                                                 |
| chameleon                 | 4.21 ms                                                             | 4.32 ms: 1.03x slower                                                 |
| richards_super            | 36.7 ms                                                             | 37.8 ms: 1.03x slower                                                 |
| sqlglot_optimize          | 29.6 ms                                                             | 30.4 ms: 1.03x slower                                                 |
| logging_silent            | 64.3 ns                                                             | 66.3 ns: 1.03x slower                                                 |
| generators                | 29.0 ms                                                             | 30.0 ms: 1.03x slower                                                 |
| coroutines                | 16.4 ms                                                             | 17.0 ms: 1.04x slower                                                 |
| comprehensions            | 14.6 us                                                             | 17.2 us: 1.17x slower                                                 |
| sqlglot_transpile         | 1.04 ms                                                             | 1.30 ms: 1.25x slower                                                 |
| sqlglot_parse             | 874 us                                                              | 1.14 ms: 1.30x slower                                                 |
| coverage                  | 41.4 ms                                                             | 72.4 ms: 1.75x slower                                                 |
| Geometric mean            | (ref)                                                               | 1.00x slower                                                          |

Benchmark hidden because not significant (19): tornado_http, bench_mp_pool, pylint, async_tree_io, aiohttp, async_tree_cpu_io_mixed, bench_thread_pool, dask, asyncio_websockets, async_tree_cpu_io_mixed_tg, json_dumps, pycparser, asyncio_tcp, telco, async_tree_none, asyncio_tcp_ssl, pathlib, gunicorn, async_tree_memoization
Ignored benchmarks (1) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: flaskblogging


# HPT report

- Reliability score: 98.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
