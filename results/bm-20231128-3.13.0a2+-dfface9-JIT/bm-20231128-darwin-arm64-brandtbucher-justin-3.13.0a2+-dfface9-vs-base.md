
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.01x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 175 ms                                                                 | 181 ms: 1.04x slower                                           |
| chameleon      | 5.09 ms                                                                | 5.15 ms: 1.01x slower                                          |
| docutils       | 1.51 sec                                                               | 1.52 sec: 1.01x slower                                         |
| tornado_http   | 71.3 ms                                                                | 73.7 ms: 1.03x slower                                          |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|--------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none_tg | 267 ms                                                                 | 268 ms: 1.01x slower                                           |
| Geometric mean     | (ref)                                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (7): async_tree_io_tg, async_tree_memoization, async_tree_io, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_memoization_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 84.5 ms                                                                | 80.5 ms: 1.05x faster                                          |
| pidigits       | 294 ms                                                                 | 283 ms: 1.04x faster                                           |
| float          | 58.5 ms                                                                | 58.7 ms: 1.00x slower                                          |
| Geometric mean | (ref)                                                                  | 1.03x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 150 ms                                                                 | 149 ms: 1.01x faster                                           |
| regex_effbot   | 2.57 ms                                                                | 2.57 ms: 1.00x faster                                          |
| regex_v8       | 16.9 ms                                                                | 17.0 ms: 1.01x slower                                          |
| regex_compile  | 80.0 ms                                                                | 83.9 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 1.61 sec                                                               | 1.53 sec: 1.05x faster                                         |
| pickle_dict          | 18.6 us                                                                | 18.0 us: 1.03x faster                                          |
| pickle               | 7.53 us                                                                | 7.39 us: 1.02x faster                                          |
| pickle_list          | 2.94 us                                                                | 2.89 us: 1.02x faster                                          |
| json_dumps           | 6.62 ms                                                                | 6.57 ms: 1.01x faster                                          |
| xml_etree_process    | 41.2 ms                                                                | 41.3 ms: 1.00x slower                                          |
| unpickle             | 9.04 us                                                                | 9.11 us: 1.01x slower                                          |
| xml_etree_generate   | 58.4 ms                                                                | 59.2 ms: 1.01x slower                                          |
| unpickle_pure_python | 165 us                                                                 | 171 us: 1.04x slower                                           |
| Geometric mean       | (ref)                                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (5): xml_etree_parse, json_loads, pickle_pure_python, unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.75 ms                                                                | 7.96 ms: 1.03x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|--------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads              | 1.61 sec                                                               | 1.53 sec: 1.05x faster                                         |
| nbody                    | 84.5 ms                                                                | 80.5 ms: 1.05x faster                                          |
| richards                 | 34.8 ms                                                                | 33.4 ms: 1.04x faster                                          |
| richards_super           | 39.0 ms                                                                | 37.3 ms: 1.04x faster                                          |
| pidigits                 | 294 ms                                                                 | 283 ms: 1.04x faster                                           |
| pprint_safe_repr         | 562 ms                                                                 | 542 ms: 1.04x faster                                           |
| pickle_dict              | 18.6 us                                                                | 18.0 us: 1.03x faster                                          |
| create_gc_cycles         | 724 us                                                                 | 701 us: 1.03x faster                                           |
| pickle                   | 7.53 us                                                                | 7.39 us: 1.02x faster                                          |
| pickle_list              | 2.94 us                                                                | 2.89 us: 1.02x faster                                          |
| telco                    | 4.71 ms                                                                | 4.64 ms: 1.01x faster                                          |
| pathlib                  | 25.2 ms                                                                | 24.9 ms: 1.01x faster                                          |
| gc_traversal             | 2.42 ms                                                                | 2.40 ms: 1.01x faster                                          |
| json_dumps               | 6.62 ms                                                                | 6.57 ms: 1.01x faster                                          |
| regex_dna                | 150 ms                                                                 | 149 ms: 1.01x faster                                           |
| regex_effbot             | 2.57 ms                                                                | 2.57 ms: 1.00x faster                                          |
| logging_format           | 3.91 us                                                                | 3.92 us: 1.00x slower                                          |
| xml_etree_process        | 41.2 ms                                                                | 41.3 ms: 1.00x slower                                          |
| float                    | 58.5 ms                                                                | 58.7 ms: 1.00x slower                                          |
| sqlite_synth             | 1.66 us                                                                | 1.66 us: 1.00x slower                                          |
| logging_simple           | 3.62 us                                                                | 3.64 us: 1.00x slower                                          |
| scimark_sor              | 108 ms                                                                 | 108 ms: 1.01x slower                                           |
| async_tree_none_tg       | 267 ms                                                                 | 268 ms: 1.01x slower                                           |
| pprint_pformat           | 1.10 sec                                                               | 1.11 sec: 1.01x slower                                         |
| unpickle                 | 9.04 us                                                                | 9.11 us: 1.01x slower                                          |
| regex_v8                 | 16.9 ms                                                                | 17.0 ms: 1.01x slower                                          |
| chameleon                | 5.09 ms                                                                | 5.15 ms: 1.01x slower                                          |
| dask                     | 229 ms                                                                 | 231 ms: 1.01x slower                                           |
| docutils                 | 1.51 sec                                                               | 1.52 sec: 1.01x slower                                         |
| coverage                 | 47.9 ms                                                                | 48.5 ms: 1.01x slower                                          |
| nqueens                  | 64.9 ms                                                                | 65.7 ms: 1.01x slower                                          |
| xml_etree_generate       | 58.4 ms                                                                | 59.2 ms: 1.01x slower                                          |
| typing_runtime_protocols | 78.0 us                                                                | 79.1 us: 1.01x slower                                          |
| pycparser                | 709 ms                                                                 | 719 ms: 1.01x slower                                           |
| pyflate                  | 344 ms                                                                 | 349 ms: 1.01x slower                                           |
| deepcopy_reduce          | 2.09 us                                                                | 2.12 us: 1.01x slower                                          |
| dulwich_log              | 30.0 ms                                                                | 30.5 ms: 1.02x slower                                          |
| sympy_expand             | 255 ms                                                                 | 260 ms: 1.02x slower                                           |
| fannkuch                 | 296 ms                                                                 | 301 ms: 1.02x slower                                           |
| deepcopy                 | 233 us                                                                 | 238 us: 1.02x slower                                           |
| sqlglot_parse            | 831 us                                                                 | 849 us: 1.02x slower                                           |
| logging_silent           | 70.3 ns                                                                | 71.9 ns: 1.02x slower                                          |
| sqlglot_normalize        | 192 ms                                                                 | 197 ms: 1.03x slower                                           |
| mako                     | 7.75 ms                                                                | 7.96 ms: 1.03x slower                                          |
| crypto_pyaes             | 49.0 ms                                                                | 50.3 ms: 1.03x slower                                          |
| sqlglot_transpile        | 1.01 ms                                                                | 1.04 ms: 1.03x slower                                          |
| raytrace                 | 183 ms                                                                 | 189 ms: 1.03x slower                                           |
| bench_thread_pool        | 514 us                                                                 | 531 us: 1.03x slower                                           |
| mdp                      | 1.67 sec                                                               | 1.72 sec: 1.03x slower                                         |
| deepcopy_memo            | 26.0 us                                                                | 26.9 us: 1.03x slower                                          |
| tornado_http             | 71.3 ms                                                                | 73.7 ms: 1.03x slower                                          |
| unpickle_pure_python     | 165 us                                                                 | 171 us: 1.04x slower                                           |
| sqlglot_optimize         | 35.7 ms                                                                | 37.1 ms: 1.04x slower                                          |
| 2to3                     | 175 ms                                                                 | 181 ms: 1.04x slower                                           |
| bench_mp_pool            | 44.5 ms                                                                | 46.3 ms: 1.04x slower                                          |
| sympy_str                | 148 ms                                                                 | 154 ms: 1.04x slower                                           |
| meteor_contest           | 75.3 ms                                                                | 78.5 ms: 1.04x slower                                          |
| chaos                    | 43.0 ms                                                                | 44.9 ms: 1.04x slower                                          |
| scimark_sparse_mat_mult  | 3.18 ms                                                                | 3.31 ms: 1.04x slower                                          |
| scimark_fft              | 212 ms                                                                 | 222 ms: 1.04x slower                                           |
| scimark_monte_carlo      | 48.6 ms                                                                | 50.8 ms: 1.04x slower                                          |
| scimark_lu               | 75.1 ms                                                                | 78.6 ms: 1.05x slower                                          |
| regex_compile            | 80.0 ms                                                                | 83.9 ms: 1.05x slower                                          |
| deltablue                | 2.44 ms                                                                | 2.57 ms: 1.05x slower                                          |
| async_generators         | 305 ms                                                                 | 321 ms: 1.05x slower                                           |
| sympy_sum                | 76.2 ms                                                                | 81.0 ms: 1.06x slower                                          |
| go                       | 106 ms                                                                 | 114 ms: 1.07x slower                                           |
| sympy_integrate          | 11.2 ms                                                                | 12.0 ms: 1.07x slower                                          |
| comprehensions           | 12.7 us                                                                | 13.8 us: 1.09x slower                                          |
| spectral_norm            | 74.9 ms                                                                | 82.1 ms: 1.10x slower                                          |
| hexiom                   | 5.04 ms                                                                | 5.82 ms: 1.15x slower                                          |
| Geometric mean           | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (22): mypy2, python_startup_no_site, asyncio_tcp, async_tree_io_tg, xml_etree_parse, generators, json_loads, coroutines, async_tree_memoization, pickle_pure_python, json, async_tree_io, unpickle_list, async_tree_cpu_io_mixed_tg, xml_etree_iterparse, asyncio_websockets, async_tree_cpu_io_mixed, unpack_sequence, asyncio_tcp_ssl, async_tree_memoization_tg, async_tree_none, python_startup


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
