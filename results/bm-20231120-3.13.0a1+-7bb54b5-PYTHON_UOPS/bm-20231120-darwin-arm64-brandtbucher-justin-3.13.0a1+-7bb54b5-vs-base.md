
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.05x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 183 ms                                                                 | 181 ms: 1.01x faster                                           |
| chameleon      | 5.06 ms                                                                | 4.88 ms: 1.04x faster                                          |
| docutils       | 1.54 sec                                                               | 1.53 sec: 1.01x faster                                         |
| Geometric mean | (ref)                                                                  | 1.02x faster                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none            | 266 ms                                                                 | 257 ms: 1.04x faster                                           |
| async_tree_none_tg         | 279 ms                                                                 | 270 ms: 1.03x faster                                           |
| async_tree_memoization     | 342 ms                                                                 | 332 ms: 1.03x faster                                           |
| async_tree_memoization_tg  | 347 ms                                                                 | 337 ms: 1.03x faster                                           |
| async_tree_io              | 721 ms                                                                 | 707 ms: 1.02x faster                                           |
| async_tree_io_tg           | 702 ms                                                                 | 689 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 554 ms                                                                 | 545 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed    | 536 ms                                                                 | 527 ms: 1.02x faster                                           |
| Geometric mean             | (ref)                                                                  | 1.02x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 73.5 ms                                                                | 58.3 ms: 1.26x faster                                          |
| nbody          | 91.5 ms                                                                | 81.7 ms: 1.12x faster                                          |
| pidigits       | 283 ms                                                                 | 282 ms: 1.00x faster                                           |
| Geometric mean | (ref)                                                                  | 1.12x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 91.1 ms                                                                | 83.5 ms: 1.09x faster                                          |
| regex_dna      | 149 ms                                                                 | 149 ms: 1.00x slower                                           |
| Geometric mean | (ref)                                                                  | 1.02x faster                                                   |

Benchmark hidden because not significant (2): regex_v8, regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 1.81 sec                                                               | 1.51 sec: 1.20x faster                                         |
| xml_etree_iterparse  | 83.5 ms                                                                | 76.8 ms: 1.09x faster                                          |
| xml_etree_generate   | 62.6 ms                                                                | 58.4 ms: 1.07x faster                                          |
| unpickle_pure_python | 176 us                                                                 | 165 us: 1.06x faster                                           |
| xml_etree_process    | 42.7 ms                                                                | 40.9 ms: 1.04x faster                                          |
| json_dumps           | 6.60 ms                                                                | 6.55 ms: 1.01x faster                                          |
| pickle_pure_python   | 205 us                                                                 | 204 us: 1.01x faster                                           |
| unpickle             | 9.07 us                                                                | 9.04 us: 1.00x faster                                          |
| pickle_dict          | 17.9 us                                                                | 17.9 us: 1.00x faster                                          |
| json_loads           | 17.2 us                                                                | 17.3 us: 1.01x slower                                          |
| pickle               | 7.41 us                                                                | 7.47 us: 1.01x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.03x faster                                                   |

Benchmark hidden because not significant (3): xml_etree_parse, unpickle_list, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 12.2 ms                                                                | 12.3 ms: 1.01x slower                                          |
| python_startup_no_site | 10.8 ms                                                                | 10.9 ms: 1.01x slower                                          |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.5 ms                                                                | 7.96 ms: 1.32x faster                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| deltablue                  | 3.80 ms                                                                | 2.57 ms: 1.48x faster                                          |
| spectral_norm              | 116 ms                                                                 | 81.4 ms: 1.42x faster                                          |
| scimark_sparse_mat_mult    | 4.54 ms                                                                | 3.31 ms: 1.37x faster                                          |
| mako                       | 10.5 ms                                                                | 7.96 ms: 1.32x faster                                          |
| float                      | 73.5 ms                                                                | 58.3 ms: 1.26x faster                                          |
| comprehensions             | 17.5 us                                                                | 13.9 us: 1.26x faster                                          |
| scimark_fft                | 274 ms                                                                 | 223 ms: 1.23x faster                                           |
| tomli_loads                | 1.81 sec                                                               | 1.51 sec: 1.20x faster                                         |
| fannkuch                   | 356 ms                                                                 | 299 ms: 1.19x faster                                           |
| crypto_pyaes               | 59.2 ms                                                                | 50.0 ms: 1.18x faster                                          |
| scimark_monte_carlo        | 59.3 ms                                                                | 50.1 ms: 1.18x faster                                          |
| hexiom                     | 6.66 ms                                                                | 5.77 ms: 1.15x faster                                          |
| nqueens                    | 74.2 ms                                                                | 65.8 ms: 1.13x faster                                          |
| chaos                      | 50.8 ms                                                                | 45.0 ms: 1.13x faster                                          |
| pyflate                    | 392 ms                                                                 | 350 ms: 1.12x faster                                           |
| nbody                      | 91.5 ms                                                                | 81.7 ms: 1.12x faster                                          |
| pprint_pformat             | 1.21 sec                                                               | 1.10 sec: 1.10x faster                                         |
| pprint_safe_repr           | 592 ms                                                                 | 537 ms: 1.10x faster                                           |
| regex_compile              | 91.1 ms                                                                | 83.5 ms: 1.09x faster                                          |
| xml_etree_iterparse        | 83.5 ms                                                                | 76.8 ms: 1.09x faster                                          |
| xml_etree_generate         | 62.6 ms                                                                | 58.4 ms: 1.07x faster                                          |
| unpickle_pure_python       | 176 us                                                                 | 165 us: 1.06x faster                                           |
| raytrace                   | 205 ms                                                                 | 194 ms: 1.06x faster                                           |
| sympy_sum                  | 85.3 ms                                                                | 80.7 ms: 1.06x faster                                          |
| typing_runtime_protocols   | 81.7 us                                                                | 77.4 us: 1.06x faster                                          |
| sympy_str                  | 162 ms                                                                 | 153 ms: 1.05x faster                                           |
| meteor_contest             | 83.3 ms                                                                | 79.1 ms: 1.05x faster                                          |
| telco                      | 4.87 ms                                                                | 4.65 ms: 1.05x faster                                          |
| xml_etree_process          | 42.7 ms                                                                | 40.9 ms: 1.04x faster                                          |
| sqlite_synth               | 1.72 us                                                                | 1.65 us: 1.04x faster                                          |
| sqlglot_normalize          | 204 ms                                                                 | 196 ms: 1.04x faster                                           |
| sqlglot_optimize           | 38.2 ms                                                                | 36.8 ms: 1.04x faster                                          |
| deepcopy_memo              | 27.1 us                                                                | 26.2 us: 1.04x faster                                          |
| chameleon                  | 5.06 ms                                                                | 4.88 ms: 1.04x faster                                          |
| async_tree_none            | 266 ms                                                                 | 257 ms: 1.04x faster                                           |
| async_tree_none_tg         | 279 ms                                                                 | 270 ms: 1.03x faster                                           |
| scimark_lu                 | 80.0 ms                                                                | 77.6 ms: 1.03x faster                                          |
| async_tree_memoization     | 342 ms                                                                 | 332 ms: 1.03x faster                                           |
| logging_simple             | 3.71 us                                                                | 3.61 us: 1.03x faster                                          |
| sqlglot_parse              | 892 us                                                                 | 867 us: 1.03x faster                                           |
| async_tree_memoization_tg  | 347 ms                                                                 | 337 ms: 1.03x faster                                           |
| logging_format             | 4.03 us                                                                | 3.92 us: 1.03x faster                                          |
| sympy_integrate            | 12.3 ms                                                                | 12.0 ms: 1.03x faster                                          |
| richards                   | 34.3 ms                                                                | 33.4 ms: 1.03x faster                                          |
| richards_super             | 38.1 ms                                                                | 37.1 ms: 1.03x faster                                          |
| sqlglot_transpile          | 1.08 ms                                                                | 1.05 ms: 1.02x faster                                          |
| go                         | 116 ms                                                                 | 113 ms: 1.02x faster                                           |
| mdp                        | 1.75 sec                                                               | 1.71 sec: 1.02x faster                                         |
| async_tree_io              | 721 ms                                                                 | 707 ms: 1.02x faster                                           |
| async_tree_io_tg           | 702 ms                                                                 | 689 ms: 1.02x faster                                           |
| sympy_expand               | 264 ms                                                                 | 260 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed_tg | 554 ms                                                                 | 545 ms: 1.02x faster                                           |
| async_tree_cpu_io_mixed    | 536 ms                                                                 | 527 ms: 1.02x faster                                           |
| scimark_sor                | 110 ms                                                                 | 108 ms: 1.02x faster                                           |
| deepcopy_reduce            | 2.09 us                                                                | 2.06 us: 1.01x faster                                          |
| logging_silent             | 74.4 ns                                                                | 73.6 ns: 1.01x faster                                          |
| pathlib                    | 24.5 ms                                                                | 24.2 ms: 1.01x faster                                          |
| 2to3                       | 183 ms                                                                 | 181 ms: 1.01x faster                                           |
| docutils                   | 1.54 sec                                                               | 1.53 sec: 1.01x faster                                         |
| deepcopy                   | 234 us                                                                 | 232 us: 1.01x faster                                           |
| json_dumps                 | 6.60 ms                                                                | 6.55 ms: 1.01x faster                                          |
| bench_thread_pool          | 533 us                                                                 | 529 us: 1.01x faster                                           |
| pickle_pure_python         | 205 us                                                                 | 204 us: 1.01x faster                                           |
| pidigits                   | 283 ms                                                                 | 282 ms: 1.00x faster                                           |
| create_gc_cycles           | 702 us                                                                 | 700 us: 1.00x faster                                           |
| unpickle                   | 9.07 us                                                                | 9.04 us: 1.00x faster                                          |
| coroutines                 | 18.7 ms                                                                | 18.6 ms: 1.00x faster                                          |
| pickle_dict                | 17.9 us                                                                | 17.9 us: 1.00x faster                                          |
| regex_dna                  | 149 ms                                                                 | 149 ms: 1.00x slower                                           |
| async_generators           | 317 ms                                                                 | 318 ms: 1.00x slower                                           |
| json_loads                 | 17.2 us                                                                | 17.3 us: 1.01x slower                                          |
| generators                 | 25.5 ms                                                                | 25.6 ms: 1.01x slower                                          |
| pickle                     | 7.41 us                                                                | 7.47 us: 1.01x slower                                          |
| python_startup             | 12.2 ms                                                                | 12.3 ms: 1.01x slower                                          |
| python_startup_no_site     | 10.8 ms                                                                | 10.9 ms: 1.01x slower                                          |
| unpack_sequence            | 28.1 ns                                                                | 28.4 ns: 1.01x slower                                          |
| coverage                   | 47.2 ms                                                                | 48.7 ms: 1.03x slower                                          |
| bench_mp_pool              | 44.7 ms                                                                | 46.3 ms: 1.04x slower                                          |
| Geometric mean             | (ref)                                                                  | 1.05x faster                                                   |

Benchmark hidden because not significant (15): asyncio_tcp, tornado_http, json, dask, dulwich_log, asyncio_websockets, xml_etree_parse, unpickle_list, regex_v8, regex_effbot, gc_traversal, asyncio_tcp_ssl, pycparser, pickle_list, mypy2


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
