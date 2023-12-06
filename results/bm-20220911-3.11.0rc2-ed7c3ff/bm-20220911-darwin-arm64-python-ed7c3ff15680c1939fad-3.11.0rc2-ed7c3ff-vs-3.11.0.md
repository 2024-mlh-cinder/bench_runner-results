
# Results vs. 3.11.0

- fork: python
- ref: ed7c3ff15680c1939fad
- machine: darwin-arm64
- commit hash: ed7c3ff
- commit date: 2022-09-11
- overall geometric mean: 1.00x faster
- HPT reliability: 99.86%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 153 ms: 1.00x faster                                                   |
| chameleon      | 4.21 ms                                                             | 4.17 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                               | 1.00x faster                                                           |

Benchmark hidden because not significant (3): docutils, html5lib, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|--------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none_tg | 277 ms                                                              | 275 ms: 1.01x faster                                                   |
| Geometric mean     | (ref)                                                               | 1.00x faster                                                           |

Benchmark hidden because not significant (7): async_tree_memoization, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 68.5 ms                                                             | 68.4 ms: 1.00x faster                                                  |
| float          | 55.1 ms                                                             | 55.7 ms: 1.01x slower                                                  |
| Geometric mean | (ref)                                                               | 1.00x slower                                                           |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 2.45 ms                                                             | 2.46 ms: 1.00x slower                                                  |
| regex_dna      | 149 ms                                                              | 150 ms: 1.01x slower                                                   |
| regex_v8       | 15.4 ms                                                             | 15.5 ms: 1.01x slower                                                  |
| Geometric mean | (ref)                                                               | 1.00x slower                                                           |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| tomli_loads          | 1.32 sec                                                            | 1.31 sec: 1.01x faster                                                 |
| xml_etree_generate   | 47.1 ms                                                             | 46.7 ms: 1.01x faster                                                  |
| xml_etree_parse      | 97.6 ms                                                             | 96.9 ms: 1.01x faster                                                  |
| pickle_list          | 2.68 us                                                             | 2.66 us: 1.01x faster                                                  |
| json_dumps           | 7.58 ms                                                             | 7.56 ms: 1.00x faster                                                  |
| xml_etree_process    | 34.1 ms                                                             | 34.0 ms: 1.00x faster                                                  |
| unpickle_pure_python | 162 us                                                              | 163 us: 1.00x slower                                                   |
| unpickle_list        | 2.76 us                                                             | 2.77 us: 1.00x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.00x faster                                                           |

Benchmark hidden because not significant (6): xml_etree_iterparse, json_loads, pickle_pure_python, pickle_dict, pickle, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                             | 12.0 ms: 1.04x slower                                                  |
| python_startup_no_site | 9.37 ms                                                             | 9.94 ms: 1.06x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.05x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| genshi_xml      | 28.3 ms                                                             | 28.1 ms: 1.01x faster                                                  |
| mako            | 8.25 ms                                                             | 8.22 ms: 1.00x faster                                                  |
| genshi_text     | 14.5 ms                                                             | 14.5 ms: 1.00x slower                                                  |
| django_template | 19.6 ms                                                             | 19.8 ms: 1.01x slower                                                  |
| Geometric mean  | (ref)                                                               | 1.00x slower                                                           |

All benchmarks:
===============

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20220911-darwin-arm64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| gc_traversal           | 2.53 ms                                                             | 2.38 ms: 1.06x faster                                                  |
| gunicorn               | 1.17 ms                                                             | 1.10 ms: 1.06x faster                                                  |
| mdp                    | 1.84 sec                                                            | 1.74 sec: 1.06x faster                                                 |
| bench_thread_pool      | 467 us                                                              | 457 us: 1.02x faster                                                   |
| sqlalchemy_imperative  | 7.33 ms                                                             | 7.19 ms: 1.02x faster                                                  |
| tomli_loads            | 1.32 sec                                                            | 1.31 sec: 1.01x faster                                                 |
| pprint_pformat         | 986 ms                                                              | 977 ms: 1.01x faster                                                   |
| xml_etree_generate     | 47.1 ms                                                             | 46.7 ms: 1.01x faster                                                  |
| chameleon              | 4.21 ms                                                             | 4.17 ms: 1.01x faster                                                  |
| pprint_safe_repr       | 480 ms                                                              | 477 ms: 1.01x faster                                                   |
| xml_etree_parse        | 97.6 ms                                                             | 96.9 ms: 1.01x faster                                                  |
| async_tree_none_tg     | 277 ms                                                              | 275 ms: 1.01x faster                                                   |
| pickle_list            | 2.68 us                                                             | 2.66 us: 1.01x faster                                                  |
| sympy_expand           | 236 ms                                                              | 235 ms: 1.01x faster                                                   |
| genshi_xml             | 28.3 ms                                                             | 28.1 ms: 1.01x faster                                                  |
| json                   | 2.77 ms                                                             | 2.75 ms: 1.01x faster                                                  |
| meteor_contest         | 75.3 ms                                                             | 75.0 ms: 1.00x faster                                                  |
| pyflate                | 295 ms                                                              | 294 ms: 1.00x faster                                                   |
| mypy2                  | 187 ms                                                              | 187 ms: 1.00x faster                                                   |
| mako                   | 8.25 ms                                                             | 8.22 ms: 1.00x faster                                                  |
| create_gc_cycles       | 714 us                                                              | 712 us: 1.00x faster                                                   |
| coverage               | 41.4 ms                                                             | 41.3 ms: 1.00x faster                                                  |
| thrift                 | 420 us                                                              | 419 us: 1.00x faster                                                   |
| json_dumps             | 7.58 ms                                                             | 7.56 ms: 1.00x faster                                                  |
| hexiom                 | 4.55 ms                                                             | 4.54 ms: 1.00x faster                                                  |
| spectral_norm          | 69.4 ms                                                             | 69.2 ms: 1.00x faster                                                  |
| scimark_fft            | 186 ms                                                              | 186 ms: 1.00x faster                                                   |
| sqlglot_optimize       | 29.6 ms                                                             | 29.5 ms: 1.00x faster                                                  |
| xml_etree_process      | 34.1 ms                                                             | 34.0 ms: 1.00x faster                                                  |
| nbody                  | 68.5 ms                                                             | 68.4 ms: 1.00x faster                                                  |
| chaos                  | 48.2 ms                                                             | 48.2 ms: 1.00x faster                                                  |
| 2to3                   | 154 ms                                                              | 153 ms: 1.00x faster                                                   |
| fannkuch               | 247 ms                                                              | 247 ms: 1.00x slower                                                   |
| raytrace               | 205 ms                                                              | 206 ms: 1.00x slower                                                   |
| logging_silent         | 64.3 ns                                                             | 64.4 ns: 1.00x slower                                                  |
| regex_effbot           | 2.45 ms                                                             | 2.46 ms: 1.00x slower                                                  |
| genshi_text            | 14.5 ms                                                             | 14.5 ms: 1.00x slower                                                  |
| sympy_sum              | 80.8 ms                                                             | 81.0 ms: 1.00x slower                                                  |
| unpickle_pure_python   | 162 us                                                              | 163 us: 1.00x slower                                                   |
| deepcopy_reduce        | 1.96 us                                                             | 1.97 us: 1.00x slower                                                  |
| telco                  | 3.17 ms                                                             | 3.18 ms: 1.00x slower                                                  |
| unpickle_list          | 2.76 us                                                             | 2.77 us: 1.00x slower                                                  |
| crypto_pyaes           | 47.9 ms                                                             | 48.1 ms: 1.00x slower                                                  |
| richards               | 30.7 ms                                                             | 30.8 ms: 1.00x slower                                                  |
| scimark_sor            | 74.4 ms                                                             | 74.8 ms: 1.01x slower                                                  |
| regex_dna              | 149 ms                                                              | 150 ms: 1.01x slower                                                   |
| asyncio_tcp_ssl        | 1.43 sec                                                            | 1.44 sec: 1.01x slower                                                 |
| regex_v8               | 15.4 ms                                                             | 15.5 ms: 1.01x slower                                                  |
| deepcopy               | 232 us                                                              | 233 us: 1.01x slower                                                   |
| django_template        | 19.6 ms                                                             | 19.8 ms: 1.01x slower                                                  |
| dulwich_log            | 29.2 ms                                                             | 29.5 ms: 1.01x slower                                                  |
| float                  | 55.1 ms                                                             | 55.7 ms: 1.01x slower                                                  |
| pathlib                | 23.0 ms                                                             | 23.4 ms: 1.02x slower                                                  |
| scimark_monte_carlo    | 45.7 ms                                                             | 47.2 ms: 1.03x slower                                                  |
| flaskblogging          | 2.37 ms                                                             | 2.45 ms: 1.04x slower                                                  |
| python_startup         | 11.5 ms                                                             | 12.0 ms: 1.04x slower                                                  |
| python_startup_no_site | 9.37 ms                                                             | 9.94 ms: 1.06x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.00x faster                                                           |

Benchmark hidden because not significant (47): async_tree_memoization, tornado_http, bench_mp_pool, xml_etree_iterparse, asyncio_tcp, pylint, sympy_integrate, sqlglot_transpile, json_loads, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, sqlglot_normalize, sympy_str, async_generators, async_tree_io, scimark_lu, async_tree_io_tg, asyncio_websockets, docutils, async_tree_none, logging_format, deltablue, scimark_sparse_mat_mult, coroutines, pidigits, pickle_pure_python, typing_runtime_protocols, deepcopy_memo, sqlglot_parse, pickle_dict, generators, comprehensions, logging_simple, nqueens, sqlite_synth, pickle, richards_super, html5lib, regex_compile, unpickle, sqlalchemy_declarative, unpack_sequence, go, dask, pycparser, aiohttp


# HPT report

- Reliability score: 99.86% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
