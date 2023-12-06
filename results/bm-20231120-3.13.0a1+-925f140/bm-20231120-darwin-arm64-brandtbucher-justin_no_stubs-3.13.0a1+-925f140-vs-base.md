
# Results vs. base

- fork: brandtbucher
- ref: justin_no_stubs
- machine: darwin-arm64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 174 ms                                                                 | 181 ms: 1.04x slower                                                    |
| chameleon      | 4.83 ms                                                                | 4.86 ms: 1.01x slower                                                   |
| docutils       | 1.49 sec                                                               | 1.53 sec: 1.02x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_io_tg | 685 ms                                                                 | 687 ms: 1.00x slower                                                    |
| async_tree_io    | 702 ms                                                                 | 706 ms: 1.01x slower                                                    |
| Geometric mean   | (ref)                                                                  | 1.00x slower                                                            |

Benchmark hidden because not significant (6): async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| float          | 58.3 ms                                                                | 58.6 ms: 1.01x slower                                                   |
| nbody          | 79.2 ms                                                                | 81.5 ms: 1.03x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                                 | 148 ms: 1.00x faster                                                    |
| regex_effbot   | 2.57 ms                                                                | 2.57 ms: 1.00x slower                                                   |
| regex_v8       | 16.8 ms                                                                | 17.1 ms: 1.01x slower                                                   |
| regex_compile  | 78.7 ms                                                                | 83.3 ms: 1.06x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| tomli_loads          | 1.59 sec                                                               | 1.52 sec: 1.04x faster                                                  |
| unpickle_list        | 3.13 us                                                                | 3.11 us: 1.01x faster                                                   |
| pickle_dict          | 18.0 us                                                                | 17.9 us: 1.01x faster                                                   |
| xml_etree_process    | 40.5 ms                                                                | 40.7 ms: 1.00x slower                                                   |
| json_loads           | 17.3 us                                                                | 17.4 us: 1.00x slower                                                   |
| unpickle             | 9.06 us                                                                | 9.11 us: 1.01x slower                                                   |
| pickle_list          | 2.90 us                                                                | 2.93 us: 1.01x slower                                                   |
| pickle               | 7.35 us                                                                | 7.42 us: 1.01x slower                                                   |
| pickle_pure_python   | 204 us                                                                 | 206 us: 1.01x slower                                                    |
| xml_etree_generate   | 57.7 ms                                                                | 58.8 ms: 1.02x slower                                                   |
| unpickle_pure_python | 160 us                                                                 | 167 us: 1.04x slower                                                    |
| Geometric mean       | (ref)                                                                  | 1.00x slower                                                            |

Benchmark hidden because not significant (3): json_dumps, xml_etree_parse, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 11.0 ms                                                                | 11.1 ms: 1.01x slower                                                   |
| python_startup         | 12.4 ms                                                                | 12.7 ms: 1.02x slower                                                   |
| Geometric mean         | (ref)                                                                  | 1.02x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 7.74 ms                                                                | 7.92 ms: 1.02x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|--------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| richards_super           | 38.5 ms                                                                | 36.8 ms: 1.05x faster                                                   |
| tomli_loads              | 1.59 sec                                                               | 1.52 sec: 1.04x faster                                                  |
| richards                 | 34.7 ms                                                                | 33.3 ms: 1.04x faster                                                   |
| generators               | 26.0 ms                                                                | 25.6 ms: 1.02x faster                                                   |
| unpickle_list            | 3.13 us                                                                | 3.11 us: 1.01x faster                                                   |
| pickle_dict              | 18.0 us                                                                | 17.9 us: 1.01x faster                                                   |
| deepcopy_reduce          | 2.05 us                                                                | 2.04 us: 1.00x faster                                                   |
| regex_dna                | 149 ms                                                                 | 148 ms: 1.00x faster                                                    |
| create_gc_cycles         | 701 us                                                                 | 700 us: 1.00x faster                                                    |
| logging_format           | 3.93 us                                                                | 3.92 us: 1.00x faster                                                   |
| regex_effbot             | 2.57 ms                                                                | 2.57 ms: 1.00x slower                                                   |
| async_tree_io_tg         | 685 ms                                                                 | 687 ms: 1.00x slower                                                    |
| xml_etree_process        | 40.5 ms                                                                | 40.7 ms: 1.00x slower                                                   |
| json_loads               | 17.3 us                                                                | 17.4 us: 1.00x slower                                                   |
| sqlite_synth             | 1.65 us                                                                | 1.66 us: 1.00x slower                                                   |
| unpickle                 | 9.06 us                                                                | 9.11 us: 1.01x slower                                                   |
| logging_silent           | 73.0 ns                                                                | 73.4 ns: 1.01x slower                                                   |
| float                    | 58.3 ms                                                                | 58.6 ms: 1.01x slower                                                   |
| chameleon                | 4.83 ms                                                                | 4.86 ms: 1.01x slower                                                   |
| async_tree_io            | 702 ms                                                                 | 706 ms: 1.01x slower                                                    |
| dulwich_log              | 30.0 ms                                                                | 30.2 ms: 1.01x slower                                                   |
| pickle_list              | 2.90 us                                                                | 2.93 us: 1.01x slower                                                   |
| pickle                   | 7.35 us                                                                | 7.42 us: 1.01x slower                                                   |
| pyflate                  | 346 ms                                                                 | 349 ms: 1.01x slower                                                    |
| pickle_pure_python       | 204 us                                                                 | 206 us: 1.01x slower                                                    |
| scimark_sor              | 107 ms                                                                 | 108 ms: 1.01x slower                                                    |
| regex_v8                 | 16.8 ms                                                                | 17.1 ms: 1.01x slower                                                   |
| python_startup_no_site   | 11.0 ms                                                                | 11.1 ms: 1.01x slower                                                   |
| json                     | 2.99 ms                                                                | 3.03 ms: 1.02x slower                                                   |
| sympy_expand             | 253 ms                                                                 | 258 ms: 1.02x slower                                                    |
| crypto_pyaes             | 49.4 ms                                                                | 50.3 ms: 1.02x slower                                                   |
| dask                     | 226 ms                                                                 | 230 ms: 1.02x slower                                                    |
| xml_etree_generate       | 57.7 ms                                                                | 58.8 ms: 1.02x slower                                                   |
| sqlglot_transpile        | 1.03 ms                                                                | 1.05 ms: 1.02x slower                                                   |
| python_startup           | 12.4 ms                                                                | 12.7 ms: 1.02x slower                                                   |
| pprint_safe_repr         | 522 ms                                                                 | 532 ms: 1.02x slower                                                    |
| sqlglot_parse            | 851 us                                                                 | 868 us: 1.02x slower                                                    |
| raytrace                 | 189 ms                                                                 | 193 ms: 1.02x slower                                                    |
| typing_runtime_protocols | 76.0 us                                                                | 77.7 us: 1.02x slower                                                   |
| mako                     | 7.74 ms                                                                | 7.92 ms: 1.02x slower                                                   |
| docutils                 | 1.49 sec                                                               | 1.53 sec: 1.02x slower                                                  |
| sqlglot_normalize        | 191 ms                                                                 | 196 ms: 1.03x slower                                                    |
| pprint_pformat           | 1.06 sec                                                               | 1.09 sec: 1.03x slower                                                  |
| bench_thread_pool        | 515 us                                                                 | 529 us: 1.03x slower                                                    |
| mdp                      | 1.64 sec                                                               | 1.69 sec: 1.03x slower                                                  |
| nbody                    | 79.2 ms                                                                | 81.5 ms: 1.03x slower                                                   |
| chaos                    | 43.5 ms                                                                | 44.8 ms: 1.03x slower                                                   |
| unpack_sequence          | 27.9 ns                                                                | 28.7 ns: 1.03x slower                                                   |
| deepcopy_memo            | 25.2 us                                                                | 26.0 us: 1.03x slower                                                   |
| telco                    | 4.60 ms                                                                | 4.75 ms: 1.03x slower                                                   |
| scimark_monte_carlo      | 48.4 ms                                                                | 50.1 ms: 1.03x slower                                                   |
| deltablue                | 2.49 ms                                                                | 2.57 ms: 1.03x slower                                                   |
| 2to3                     | 174 ms                                                                 | 181 ms: 1.04x slower                                                    |
| unpickle_pure_python     | 160 us                                                                 | 167 us: 1.04x slower                                                    |
| scimark_lu               | 75.0 ms                                                                | 78.0 ms: 1.04x slower                                                   |
| async_generators         | 304 ms                                                                 | 316 ms: 1.04x slower                                                    |
| coverage                 | 47.8 ms                                                                | 49.7 ms: 1.04x slower                                                   |
| scimark_sparse_mat_mult  | 3.17 ms                                                                | 3.30 ms: 1.04x slower                                                   |
| fannkuch                 | 287 ms                                                                 | 299 ms: 1.04x slower                                                    |
| sympy_str                | 146 ms                                                                 | 153 ms: 1.04x slower                                                    |
| sqlglot_optimize         | 35.3 ms                                                                | 36.9 ms: 1.04x slower                                                   |
| bench_mp_pool            | 45.3 ms                                                                | 47.3 ms: 1.04x slower                                                   |
| meteor_contest           | 75.2 ms                                                                | 78.9 ms: 1.05x slower                                                   |
| regex_compile            | 78.7 ms                                                                | 83.3 ms: 1.06x slower                                                   |
| sympy_sum                | 75.6 ms                                                                | 80.6 ms: 1.07x slower                                                   |
| go                       | 107 ms                                                                 | 114 ms: 1.07x slower                                                    |
| scimark_fft              | 209 ms                                                                 | 223 ms: 1.07x slower                                                    |
| sympy_integrate          | 11.1 ms                                                                | 12.0 ms: 1.08x slower                                                   |
| nqueens                  | 60.3 ms                                                                | 65.4 ms: 1.08x slower                                                   |
| spectral_norm            | 74.9 ms                                                                | 82.0 ms: 1.09x slower                                                   |
| comprehensions           | 12.5 us                                                                | 13.8 us: 1.10x slower                                                   |
| hexiom                   | 4.95 ms                                                                | 5.78 ms: 1.17x slower                                                   |
| Geometric mean           | (ref)                                                                  | 1.02x slower                                                            |

Benchmark hidden because not significant (21): asyncio_tcp, deepcopy, asyncio_websockets, coroutines, pidigits, asyncio_tcp_ssl, async_tree_none_tg, json_dumps, gc_traversal, xml_etree_parse, logging_simple, async_tree_cpu_io_mixed_tg, async_tree_none, xml_etree_iterparse, async_tree_cpu_io_mixed, async_tree_memoization, pycparser, async_tree_memoization_tg, pathlib, tornado_http, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
