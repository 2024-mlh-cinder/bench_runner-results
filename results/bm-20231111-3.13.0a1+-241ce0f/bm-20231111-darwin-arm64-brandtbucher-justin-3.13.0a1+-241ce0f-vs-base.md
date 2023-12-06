
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.01x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 171 ms                                                                 | 178 ms: 1.04x slower                                           |
| chameleon      | 4.66 ms                                                                | 4.74 ms: 1.02x slower                                          |
| docutils       | 1.48 sec                                                               | 1.51 sec: 1.02x slower                                         |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|--------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none_tg | 267 ms                                                                 | 268 ms: 1.01x slower                                           |
| async_tree_io_tg   | 686 ms                                                                 | 689 ms: 1.01x slower                                           |
| async_tree_io      | 702 ms                                                                 | 706 ms: 1.01x slower                                           |
| Geometric mean     | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 57.0 ms                                                                | 58.3 ms: 1.02x slower                                          |
| nbody          | 77.4 ms                                                                | 82.2 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_v8       | 16.9 ms                                                                | 16.9 ms: 1.00x slower                                          |
| regex_dna      | 149 ms                                                                 | 149 ms: 1.00x slower                                           |
| regex_compile  | 76.3 ms                                                                | 79.0 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 1.56 sec                                                               | 1.39 sec: 1.12x faster                                         |
| pickle_list          | 2.88 us                                                                | 2.85 us: 1.01x faster                                          |
| unpickle             | 9.14 us                                                                | 9.11 us: 1.00x faster                                          |
| xml_etree_iterparse  | 75.9 ms                                                                | 76.3 ms: 1.00x slower                                          |
| xml_etree_generate   | 57.7 ms                                                                | 58.1 ms: 1.01x slower                                          |
| xml_etree_process    | 39.7 ms                                                                | 40.0 ms: 1.01x slower                                          |
| xml_etree_parse      | 110 ms                                                                 | 111 ms: 1.01x slower                                           |
| pickle               | 7.37 us                                                                | 7.45 us: 1.01x slower                                          |
| pickle_pure_python   | 197 us                                                                 | 200 us: 1.02x slower                                           |
| json_dumps           | 6.45 ms                                                                | 6.67 ms: 1.03x slower                                          |
| unpickle_pure_python | 156 us                                                                 | 162 us: 1.04x slower                                           |
| Geometric mean       | (ref)                                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (3): pickle_dict, unpickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 10.5 ms                                                                | 10.3 ms: 1.02x faster                                          |
| python_startup         | 11.8 ms                                                                | 11.7 ms: 1.01x faster                                          |
| Geometric mean         | (ref)                                                                  | 1.02x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.49 ms                                                                | 7.63 ms: 1.02x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin-3.13.0a1+-241ce0f |
|--------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads              | 1.56 sec                                                               | 1.39 sec: 1.12x faster                                         |
| richards                 | 33.6 ms                                                                | 32.9 ms: 1.02x faster                                          |
| pyflate                  | 341 ms                                                                 | 335 ms: 1.02x faster                                           |
| coroutines               | 18.3 ms                                                                | 18.0 ms: 1.02x faster                                          |
| python_startup_no_site   | 10.5 ms                                                                | 10.3 ms: 1.02x faster                                          |
| generators               | 24.8 ms                                                                | 24.4 ms: 1.01x faster                                          |
| telco                    | 4.69 ms                                                                | 4.63 ms: 1.01x faster                                          |
| python_startup           | 11.8 ms                                                                | 11.7 ms: 1.01x faster                                          |
| pickle_list              | 2.88 us                                                                | 2.85 us: 1.01x faster                                          |
| coverage                 | 48.4 ms                                                                | 48.0 ms: 1.01x faster                                          |
| unpickle                 | 9.14 us                                                                | 9.11 us: 1.00x faster                                          |
| richards_super           | 36.8 ms                                                                | 36.7 ms: 1.00x faster                                          |
| gc_traversal             | 2.40 ms                                                                | 2.40 ms: 1.00x slower                                          |
| spectral_norm            | 72.6 ms                                                                | 72.8 ms: 1.00x slower                                          |
| regex_v8                 | 16.9 ms                                                                | 16.9 ms: 1.00x slower                                          |
| regex_dna                | 149 ms                                                                 | 149 ms: 1.00x slower                                           |
| logging_silent           | 70.2 ns                                                                | 70.5 ns: 1.00x slower                                          |
| deepcopy_reduce          | 1.96 us                                                                | 1.97 us: 1.00x slower                                          |
| xml_etree_iterparse      | 75.9 ms                                                                | 76.3 ms: 1.00x slower                                          |
| async_tree_none_tg       | 267 ms                                                                 | 268 ms: 1.01x slower                                           |
| async_tree_io_tg         | 686 ms                                                                 | 689 ms: 1.01x slower                                           |
| async_tree_io            | 702 ms                                                                 | 706 ms: 1.01x slower                                           |
| xml_etree_generate       | 57.7 ms                                                                | 58.1 ms: 1.01x slower                                          |
| sqlglot_parse            | 827 us                                                                 | 832 us: 1.01x slower                                           |
| sqlglot_transpile        | 1.01 ms                                                                | 1.01 ms: 1.01x slower                                          |
| xml_etree_process        | 39.7 ms                                                                | 40.0 ms: 1.01x slower                                          |
| sqlite_synth             | 1.62 us                                                                | 1.63 us: 1.01x slower                                          |
| pycparser                | 696 ms                                                                 | 702 ms: 1.01x slower                                           |
| xml_etree_parse          | 110 ms                                                                 | 111 ms: 1.01x slower                                           |
| scimark_sor              | 105 ms                                                                 | 106 ms: 1.01x slower                                           |
| pickle                   | 7.37 us                                                                | 7.45 us: 1.01x slower                                          |
| dulwich_log              | 30.1 ms                                                                | 30.5 ms: 1.01x slower                                          |
| typing_runtime_protocols | 75.2 us                                                                | 76.0 us: 1.01x slower                                          |
| fannkuch                 | 289 ms                                                                 | 293 ms: 1.01x slower                                           |
| go                       | 105 ms                                                                 | 106 ms: 1.01x slower                                           |
| unpack_sequence          | 26.5 ns                                                                | 26.9 ns: 1.01x slower                                          |
| bench_mp_pool            | 44.0 ms                                                                | 44.7 ms: 1.02x slower                                          |
| logging_simple           | 3.49 us                                                                | 3.55 us: 1.02x slower                                          |
| chameleon                | 4.66 ms                                                                | 4.74 ms: 1.02x slower                                          |
| logging_format           | 3.77 us                                                                | 3.83 us: 1.02x slower                                          |
| raytrace                 | 180 ms                                                                 | 183 ms: 1.02x slower                                           |
| pickle_pure_python       | 197 us                                                                 | 200 us: 1.02x slower                                           |
| mako                     | 7.49 ms                                                                | 7.63 ms: 1.02x slower                                          |
| docutils                 | 1.48 sec                                                               | 1.51 sec: 1.02x slower                                         |
| sqlglot_normalize        | 184 ms                                                                 | 188 ms: 1.02x slower                                           |
| sqlglot_optimize         | 34.3 ms                                                                | 35.0 ms: 1.02x slower                                          |
| float                    | 57.0 ms                                                                | 58.3 ms: 1.02x slower                                          |
| crypto_pyaes             | 47.8 ms                                                                | 49.0 ms: 1.02x slower                                          |
| bench_thread_pool        | 490 us                                                                 | 502 us: 1.03x slower                                           |
| mdp                      | 1.63 sec                                                               | 1.67 sec: 1.03x slower                                         |
| scimark_monte_carlo      | 47.3 ms                                                                | 48.8 ms: 1.03x slower                                          |
| json_dumps               | 6.45 ms                                                                | 6.67 ms: 1.03x slower                                          |
| regex_compile            | 76.3 ms                                                                | 79.0 ms: 1.04x slower                                          |
| meteor_contest           | 74.2 ms                                                                | 76.9 ms: 1.04x slower                                          |
| deepcopy_memo            | 24.4 us                                                                | 25.3 us: 1.04x slower                                          |
| unpickle_pure_python     | 156 us                                                                 | 162 us: 1.04x slower                                           |
| 2to3                     | 171 ms                                                                 | 178 ms: 1.04x slower                                           |
| scimark_sparse_mat_mult  | 3.11 ms                                                                | 3.23 ms: 1.04x slower                                          |
| scimark_lu               | 72.2 ms                                                                | 75.1 ms: 1.04x slower                                          |
| async_generators         | 300 ms                                                                 | 313 ms: 1.04x slower                                           |
| deltablue                | 2.42 ms                                                                | 2.53 ms: 1.04x slower                                          |
| scimark_fft              | 204 ms                                                                 | 213 ms: 1.05x slower                                           |
| chaos                    | 41.5 ms                                                                | 43.5 ms: 1.05x slower                                          |
| nbody                    | 77.4 ms                                                                | 82.2 ms: 1.06x slower                                          |
| nqueens                  | 58.3 ms                                                                | 62.7 ms: 1.07x slower                                          |
| hexiom                   | 4.71 ms                                                                | 5.11 ms: 1.09x slower                                          |
| comprehensions           | 11.7 us                                                                | 13.2 us: 1.13x slower                                          |
| Geometric mean           | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (19): pickle_dict, asyncio_websockets, pidigits, regex_effbot, asyncio_tcp_ssl, create_gc_cycles, unpickle_list, json_loads, deepcopy, async_tree_cpu_io_mixed_tg, json, async_tree_memoization_tg, pathlib, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization, asyncio_tcp, mypy2, tornado_http
Ignored benchmarks (6) of results/bm-20231111-3.13.0a1+-fa84e5f/bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f.json: pprint_pformat, pprint_safe_repr, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
