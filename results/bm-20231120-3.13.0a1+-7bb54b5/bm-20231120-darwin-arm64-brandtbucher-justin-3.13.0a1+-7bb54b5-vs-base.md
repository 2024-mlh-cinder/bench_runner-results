
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 174 ms                                                                 | 181 ms: 1.04x slower                                           |
| chameleon      | 4.86 ms                                                                | 4.89 ms: 1.01x slower                                          |
| docutils       | 1.50 sec                                                               | 1.53 sec: 1.02x slower                                         |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|--------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none_tg | 269 ms                                                                 | 270 ms: 1.01x slower                                           |
| Geometric mean     | (ref)                                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (7): async_tree_io_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 281 ms                                                                 | 282 ms: 1.00x slower                                           |
| nbody          | 79.1 ms                                                                | 81.4 ms: 1.03x slower                                          |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_v8       | 16.9 ms                                                                | 17.0 ms: 1.01x slower                                          |
| regex_compile  | 78.4 ms                                                                | 83.7 ms: 1.07x slower                                          |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (2): regex_effbot, regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 1.58 sec                                                               | 1.52 sec: 1.04x faster                                         |
| pickle_list          | 2.91 us                                                                | 2.88 us: 1.01x faster                                          |
| json_loads           | 17.3 us                                                                | 17.2 us: 1.00x faster                                          |
| pickle_dict          | 18.0 us                                                                | 17.9 us: 1.00x faster                                          |
| pickle_pure_python   | 204 us                                                                 | 204 us: 1.00x slower                                           |
| xml_etree_process    | 40.5 ms                                                                | 40.8 ms: 1.01x slower                                          |
| pickle               | 7.35 us                                                                | 7.43 us: 1.01x slower                                          |
| xml_etree_generate   | 57.9 ms                                                                | 58.9 ms: 1.02x slower                                          |
| json_dumps           | 6.55 ms                                                                | 6.67 ms: 1.02x slower                                          |
| unpickle_pure_python | 161 us                                                                 | 166 us: 1.04x slower                                           |
| Geometric mean       | (ref)                                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (4): xml_etree_parse, unpickle_list, unpickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 10.7 ms                                                                | 10.2 ms: 1.05x faster                                          |
| python_startup         | 12.0 ms                                                                | 11.6 ms: 1.03x faster                                          |
| Geometric mean         | (ref)                                                                  | 1.04x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.76 ms                                                                | 7.92 ms: 1.02x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|--------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site   | 10.7 ms                                                                | 10.2 ms: 1.05x faster                                          |
| richards_super           | 38.6 ms                                                                | 36.9 ms: 1.05x faster                                          |
| tomli_loads              | 1.58 sec                                                               | 1.52 sec: 1.04x faster                                         |
| richards                 | 34.7 ms                                                                | 33.2 ms: 1.04x faster                                          |
| python_startup           | 12.0 ms                                                                | 11.6 ms: 1.03x faster                                          |
| create_gc_cycles         | 711 us                                                                 | 699 us: 1.02x faster                                           |
| pickle_list              | 2.91 us                                                                | 2.88 us: 1.01x faster                                          |
| logging_format           | 3.93 us                                                                | 3.90 us: 1.01x faster                                          |
| logging_simple           | 3.61 us                                                                | 3.60 us: 1.01x faster                                          |
| json_loads               | 17.3 us                                                                | 17.2 us: 1.00x faster                                          |
| gc_traversal             | 2.40 ms                                                                | 2.39 ms: 1.00x faster                                          |
| pickle_dict              | 18.0 us                                                                | 17.9 us: 1.00x faster                                          |
| pidigits                 | 281 ms                                                                 | 282 ms: 1.00x slower                                           |
| deepcopy                 | 231 us                                                                 | 232 us: 1.00x slower                                           |
| pickle_pure_python       | 204 us                                                                 | 204 us: 1.00x slower                                           |
| coroutines               | 18.6 ms                                                                | 18.6 ms: 1.00x slower                                          |
| async_tree_none_tg       | 269 ms                                                                 | 270 ms: 1.01x slower                                           |
| regex_v8                 | 16.9 ms                                                                | 17.0 ms: 1.01x slower                                          |
| xml_etree_process        | 40.5 ms                                                                | 40.8 ms: 1.01x slower                                          |
| chameleon                | 4.86 ms                                                                | 4.89 ms: 1.01x slower                                          |
| pycparser                | 710 ms                                                                 | 715 ms: 1.01x slower                                           |
| scimark_sor              | 107 ms                                                                 | 108 ms: 1.01x slower                                           |
| pickle                   | 7.35 us                                                                | 7.43 us: 1.01x slower                                          |
| dulwich_log              | 30.0 ms                                                                | 30.3 ms: 1.01x slower                                          |
| pyflate                  | 346 ms                                                                 | 350 ms: 1.01x slower                                           |
| dask                     | 227 ms                                                                 | 230 ms: 1.01x slower                                           |
| sqlite_synth             | 1.64 us                                                                | 1.66 us: 1.01x slower                                          |
| crypto_pyaes             | 49.4 ms                                                                | 50.1 ms: 1.01x slower                                          |
| xml_etree_generate       | 57.9 ms                                                                | 58.9 ms: 1.02x slower                                          |
| json_dumps               | 6.55 ms                                                                | 6.67 ms: 1.02x slower                                          |
| unpack_sequence          | 27.9 ns                                                                | 28.4 ns: 1.02x slower                                          |
| docutils                 | 1.50 sec                                                               | 1.53 sec: 1.02x slower                                         |
| sqlglot_parse            | 852 us                                                                 | 868 us: 1.02x slower                                           |
| coverage                 | 47.4 ms                                                                | 48.3 ms: 1.02x slower                                          |
| sqlglot_transpile        | 1.03 ms                                                                | 1.05 ms: 1.02x slower                                          |
| telco                    | 4.66 ms                                                                | 4.76 ms: 1.02x slower                                          |
| sympy_expand             | 254 ms                                                                 | 259 ms: 1.02x slower                                           |
| mako                     | 7.76 ms                                                                | 7.92 ms: 1.02x slower                                          |
| typing_runtime_protocols | 75.9 us                                                                | 77.5 us: 1.02x slower                                          |
| raytrace                 | 189 ms                                                                 | 194 ms: 1.02x slower                                           |
| mdp                      | 1.65 sec                                                               | 1.69 sec: 1.03x slower                                         |
| pprint_safe_repr         | 522 ms                                                                 | 538 ms: 1.03x slower                                           |
| nbody                    | 79.1 ms                                                                | 81.4 ms: 1.03x slower                                          |
| bench_thread_pool        | 514 us                                                                 | 530 us: 1.03x slower                                           |
| bench_mp_pool            | 44.0 ms                                                                | 45.4 ms: 1.03x slower                                          |
| scimark_monte_carlo      | 48.4 ms                                                                | 50.0 ms: 1.03x slower                                          |
| deepcopy_memo            | 25.3 us                                                                | 26.1 us: 1.03x slower                                          |
| fannkuch                 | 289 ms                                                                 | 299 ms: 1.03x slower                                           |
| unpickle_pure_python     | 161 us                                                                 | 166 us: 1.04x slower                                           |
| sqlglot_normalize        | 190 ms                                                                 | 197 ms: 1.04x slower                                           |
| async_generators         | 306 ms                                                                 | 317 ms: 1.04x slower                                           |
| scimark_lu               | 74.8 ms                                                                | 77.5 ms: 1.04x slower                                          |
| chaos                    | 43.5 ms                                                                | 45.1 ms: 1.04x slower                                          |
| deltablue                | 2.48 ms                                                                | 2.57 ms: 1.04x slower                                          |
| 2to3                     | 174 ms                                                                 | 181 ms: 1.04x slower                                           |
| sympy_str                | 146 ms                                                                 | 152 ms: 1.04x slower                                           |
| sqlglot_optimize         | 35.3 ms                                                                | 36.8 ms: 1.04x slower                                          |
| scimark_sparse_mat_mult  | 3.16 ms                                                                | 3.30 ms: 1.04x slower                                          |
| pprint_pformat           | 1.06 sec                                                               | 1.11 sec: 1.05x slower                                         |
| meteor_contest           | 75.0 ms                                                                | 78.8 ms: 1.05x slower                                          |
| sympy_sum                | 75.8 ms                                                                | 80.4 ms: 1.06x slower                                          |
| go                       | 107 ms                                                                 | 114 ms: 1.07x slower                                           |
| regex_compile            | 78.4 ms                                                                | 83.7 ms: 1.07x slower                                          |
| scimark_fft              | 208 ms                                                                 | 224 ms: 1.07x slower                                           |
| sympy_integrate          | 11.1 ms                                                                | 11.9 ms: 1.07x slower                                          |
| spectral_norm            | 75.4 ms                                                                | 81.4 ms: 1.08x slower                                          |
| nqueens                  | 60.2 ms                                                                | 65.6 ms: 1.09x slower                                          |
| comprehensions           | 12.5 us                                                                | 13.9 us: 1.11x slower                                          |
| hexiom                   | 4.95 ms                                                                | 5.79 ms: 1.17x slower                                          |
| Geometric mean           | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (24): asyncio_tcp, pathlib, xml_etree_parse, unpickle_list, unpickle, async_tree_io_tg, float, xml_etree_iterparse, regex_effbot, generators, logging_silent, regex_dna, async_tree_memoization, async_tree_cpu_io_mixed_tg, asyncio_websockets, async_tree_none, deepcopy_reduce, async_tree_io, async_tree_cpu_io_mixed, json, asyncio_tcp_ssl, async_tree_memoization_tg, tornado_http, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
