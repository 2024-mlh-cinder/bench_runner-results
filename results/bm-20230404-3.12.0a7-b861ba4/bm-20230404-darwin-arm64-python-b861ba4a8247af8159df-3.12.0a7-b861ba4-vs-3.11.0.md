
# Results vs. 3.11.0

- fork: python
- ref: b861ba4a8247af8159df
- machine: darwin-arm64
- commit hash: b861ba4
- commit date: 2023-04-04
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 154 ms                                                              | 170 ms: 1.11x slower                                                  |
| chameleon      | 4.21 ms                                                             | 4.73 ms: 1.12x slower                                                 |
| docutils       | 1.43 sec                                                            | 1.51 sec: 1.05x slower                                                |
| html5lib       | 33.3 ms                                                             | 35.6 ms: 1.07x slower                                                 |
| Geometric mean | (ref)                                                               | 1.07x slower                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|---------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization    | 353 ms                                                              | 325 ms: 1.09x faster                                                  |
| async_tree_memoization_tg | 351 ms                                                              | 343 ms: 1.02x faster                                                  |
| async_tree_none_tg        | 277 ms                                                              | 271 ms: 1.02x faster                                                  |
| async_tree_io_tg          | 723 ms                                                              | 721 ms: 1.00x faster                                                  |
| async_tree_none           | 277 ms                                                              | 288 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed   | 516 ms                                                              | 537 ms: 1.04x slower                                                  |
| async_tree_io             | 691 ms                                                              | 740 ms: 1.07x slower                                                  |
| Geometric mean            | (ref)                                                               | 1.00x slower                                                          |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 68.5 ms                                                             | 64.0 ms: 1.07x faster                                                 |
| float          | 55.1 ms                                                             | 54.3 ms: 1.02x faster                                                 |
| pidigits       | 280 ms                                                              | 282 ms: 1.01x slower                                                  |
| Geometric mean | (ref)                                                               | 1.03x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_v8       | 15.4 ms                                                             | 15.2 ms: 1.02x faster                                                 |
| regex_dna      | 149 ms                                                              | 148 ms: 1.01x faster                                                  |
| regex_effbot   | 2.45 ms                                                             | 2.46 ms: 1.00x slower                                                 |
| regex_compile  | 73.5 ms                                                             | 78.7 ms: 1.07x slower                                                 |
| Geometric mean | (ref)                                                               | 1.01x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|----------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.58 ms                                                             | 6.01 ms: 1.26x faster                                                 |
| unpickle_pure_python | 162 us                                                              | 158 us: 1.03x faster                                                  |
| unpickle_list        | 2.76 us                                                             | 2.70 us: 1.02x faster                                                 |
| pickle_pure_python   | 210 us                                                              | 206 us: 1.02x faster                                                  |
| unpickle             | 8.35 us                                                             | 8.39 us: 1.00x slower                                                 |
| xml_etree_parse      | 97.6 ms                                                             | 98.6 ms: 1.01x slower                                                 |
| json_loads           | 15.5 us                                                             | 15.8 us: 1.02x slower                                                 |
| pickle_dict          | 17.0 us                                                             | 17.3 us: 1.02x slower                                                 |
| pickle_list          | 2.68 us                                                             | 2.76 us: 1.03x slower                                                 |
| xml_etree_generate   | 47.1 ms                                                             | 49.6 ms: 1.05x slower                                                 |
| tomli_loads          | 1.32 sec                                                            | 1.43 sec: 1.09x slower                                                |
| xml_etree_iterparse  | 67.5 ms                                                             | 73.5 ms: 1.09x slower                                                 |
| xml_etree_process    | 34.1 ms                                                             | 39.0 ms: 1.14x slower                                                 |
| Geometric mean       | (ref)                                                               | 1.01x slower                                                          |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.37 ms                                                             | 9.57 ms: 1.02x slower                                                 |
| python_startup         | 11.5 ms                                                             | 11.8 ms: 1.02x slower                                                 |
| Geometric mean         | (ref)                                                               | 1.02x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|-----------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.25 ms                                                             | 7.17 ms: 1.15x faster                                                 |
| genshi_xml      | 28.3 ms                                                             | 31.5 ms: 1.11x slower                                                 |
| genshi_text     | 14.5 ms                                                             | 16.2 ms: 1.12x slower                                                 |
| django_template | 19.6 ms                                                             | 22.2 ms: 1.13x slower                                                 |
| Geometric mean  | (ref)                                                               | 1.05x slower                                                          |

All benchmarks:
===============

| Benchmark                 | bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509 | bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4 |
|---------------------------|:-------------------------------------------------------------------:|:---------------------------------------------------------------------:|
| asyncio_tcp               | 664 ms                                                              | 434 ms: 1.53x faster                                                  |
| json_dumps                | 7.58 ms                                                             | 6.01 ms: 1.26x faster                                                 |
| mako                      | 8.25 ms                                                             | 7.17 ms: 1.15x faster                                                 |
| mdp                       | 1.84 sec                                                            | 1.62 sec: 1.14x faster                                                |
| scimark_sparse_mat_mult   | 3.00 ms                                                             | 2.72 ms: 1.10x faster                                                 |
| asyncio_tcp_ssl           | 1.43 sec                                                            | 1.31 sec: 1.09x faster                                                |
| async_tree_memoization    | 353 ms                                                              | 325 ms: 1.09x faster                                                  |
| nbody                     | 68.5 ms                                                             | 64.0 ms: 1.07x faster                                                 |
| gc_traversal              | 2.53 ms                                                             | 2.40 ms: 1.05x faster                                                 |
| scimark_fft               | 186 ms                                                              | 177 ms: 1.05x faster                                                  |
| meteor_contest            | 75.3 ms                                                             | 72.3 ms: 1.04x faster                                                 |
| sqlalchemy_imperative     | 7.33 ms                                                             | 7.13 ms: 1.03x faster                                                 |
| unpickle_pure_python      | 162 us                                                              | 158 us: 1.03x faster                                                  |
| deepcopy_memo             | 28.7 us                                                             | 27.9 us: 1.03x faster                                                 |
| async_tree_memoization_tg | 351 ms                                                              | 343 ms: 1.02x faster                                                  |
| create_gc_cycles          | 714 us                                                              | 698 us: 1.02x faster                                                  |
| unpickle_list             | 2.76 us                                                             | 2.70 us: 1.02x faster                                                 |
| pickle_pure_python        | 210 us                                                              | 206 us: 1.02x faster                                                  |
| async_tree_none_tg        | 277 ms                                                              | 271 ms: 1.02x faster                                                  |
| regex_v8                  | 15.4 ms                                                             | 15.2 ms: 1.02x faster                                                 |
| float                     | 55.1 ms                                                             | 54.3 ms: 1.02x faster                                                 |
| sqlite_synth              | 1.36 us                                                             | 1.34 us: 1.01x faster                                                 |
| regex_dna                 | 149 ms                                                              | 148 ms: 1.01x faster                                                  |
| async_tree_io_tg          | 723 ms                                                              | 721 ms: 1.00x faster                                                  |
| asyncio_websockets        | 408 ms                                                              | 408 ms: 1.00x slower                                                  |
| regex_effbot              | 2.45 ms                                                             | 2.46 ms: 1.00x slower                                                 |
| unpickle                  | 8.35 us                                                             | 8.39 us: 1.00x slower                                                 |
| dulwich_log               | 29.2 ms                                                             | 29.3 ms: 1.00x slower                                                 |
| pidigits                  | 280 ms                                                              | 282 ms: 1.01x slower                                                  |
| xml_etree_parse           | 97.6 ms                                                             | 98.6 ms: 1.01x slower                                                 |
| hexiom                    | 4.55 ms                                                             | 4.60 ms: 1.01x slower                                                 |
| json                      | 2.77 ms                                                             | 2.80 ms: 1.01x slower                                                 |
| json_loads                | 15.5 us                                                             | 15.8 us: 1.02x slower                                                 |
| deepcopy                  | 232 us                                                              | 236 us: 1.02x slower                                                  |
| python_startup_no_site    | 9.37 ms                                                             | 9.57 ms: 1.02x slower                                                 |
| dask                      | 219 ms                                                              | 224 ms: 1.02x slower                                                  |
| pickle_dict               | 17.0 us                                                             | 17.3 us: 1.02x slower                                                 |
| python_startup            | 11.5 ms                                                             | 11.8 ms: 1.02x slower                                                 |
| pycparser                 | 658 ms                                                              | 676 ms: 1.03x slower                                                  |
| pickle_list               | 2.68 us                                                             | 2.76 us: 1.03x slower                                                 |
| deltablue                 | 2.69 ms                                                             | 2.77 ms: 1.03x slower                                                 |
| telco                     | 3.17 ms                                                             | 3.27 ms: 1.03x slower                                                 |
| sqlalchemy_declarative    | 60.4 ms                                                             | 62.6 ms: 1.04x slower                                                 |
| async_tree_none           | 277 ms                                                              | 288 ms: 1.04x slower                                                  |
| deepcopy_reduce           | 1.96 us                                                             | 2.04 us: 1.04x slower                                                 |
| unpack_sequence           | 32.3 ns                                                             | 33.6 ns: 1.04x slower                                                 |
| async_tree_cpu_io_mixed   | 516 ms                                                              | 537 ms: 1.04x slower                                                  |
| sympy_expand              | 236 ms                                                              | 246 ms: 1.04x slower                                                  |
| pprint_pformat            | 986 ms                                                              | 1.03 sec: 1.05x slower                                                |
| fannkuch                  | 247 ms                                                              | 260 ms: 1.05x slower                                                  |
| pprint_safe_repr          | 480 ms                                                              | 505 ms: 1.05x slower                                                  |
| sympy_integrate           | 11.2 ms                                                             | 11.8 ms: 1.05x slower                                                 |
| xml_etree_generate        | 47.1 ms                                                             | 49.6 ms: 1.05x slower                                                 |
| docutils                  | 1.43 sec                                                            | 1.51 sec: 1.05x slower                                                |
| sympy_str                 | 144 ms                                                              | 152 ms: 1.05x slower                                                  |
| pathlib                   | 23.0 ms                                                             | 24.4 ms: 1.06x slower                                                 |
| sympy_sum                 | 80.8 ms                                                             | 85.9 ms: 1.06x slower                                                 |
| bench_thread_pool         | 467 us                                                              | 498 us: 1.07x slower                                                  |
| html5lib                  | 33.3 ms                                                             | 35.6 ms: 1.07x slower                                                 |
| async_tree_io             | 691 ms                                                              | 740 ms: 1.07x slower                                                  |
| regex_compile             | 73.5 ms                                                             | 78.7 ms: 1.07x slower                                                 |
| bench_mp_pool             | 42.1 ms                                                             | 45.4 ms: 1.08x slower                                                 |
| raytrace                  | 205 ms                                                              | 223 ms: 1.09x slower                                                  |
| tomli_loads               | 1.32 sec                                                            | 1.43 sec: 1.09x slower                                                |
| xml_etree_iterparse       | 67.5 ms                                                             | 73.5 ms: 1.09x slower                                                 |
| thrift                    | 420 us                                                              | 459 us: 1.09x slower                                                  |
| crypto_pyaes              | 47.9 ms                                                             | 52.4 ms: 1.09x slower                                                 |
| 2to3                      | 154 ms                                                              | 170 ms: 1.11x slower                                                  |
| genshi_xml                | 28.3 ms                                                             | 31.5 ms: 1.11x slower                                                 |
| sqlglot_optimize          | 29.6 ms                                                             | 33.0 ms: 1.12x slower                                                 |
| genshi_text               | 14.5 ms                                                             | 16.2 ms: 1.12x slower                                                 |
| scimark_monte_carlo       | 45.7 ms                                                             | 51.1 ms: 1.12x slower                                                 |
| pyflate                   | 295 ms                                                              | 332 ms: 1.12x slower                                                  |
| chameleon                 | 4.21 ms                                                             | 4.73 ms: 1.12x slower                                                 |
| nqueens                   | 54.3 ms                                                             | 61.1 ms: 1.13x slower                                                 |
| sqlglot_normalize         | 160 ms                                                              | 181 ms: 1.13x slower                                                  |
| logging_format            | 3.73 us                                                             | 4.21 us: 1.13x slower                                                 |
| django_template           | 19.6 ms                                                             | 22.2 ms: 1.13x slower                                                 |
| logging_simple            | 3.45 us                                                             | 3.93 us: 1.14x slower                                                 |
| go                        | 102 ms                                                              | 117 ms: 1.14x slower                                                  |
| xml_etree_process         | 34.1 ms                                                             | 39.0 ms: 1.14x slower                                                 |
| richards                  | 30.7 ms                                                             | 35.3 ms: 1.15x slower                                                 |
| richards_super            | 36.7 ms                                                             | 42.3 ms: 1.15x slower                                                 |
| spectral_norm             | 69.4 ms                                                             | 80.5 ms: 1.16x slower                                                 |
| comprehensions            | 14.6 us                                                             | 17.0 us: 1.16x slower                                                 |
| sqlglot_transpile         | 1.04 ms                                                             | 1.24 ms: 1.19x slower                                                 |
| logging_silent            | 64.3 ns                                                             | 77.7 ns: 1.21x slower                                                 |
| generators                | 29.0 ms                                                             | 35.4 ms: 1.22x slower                                                 |
| sqlglot_parse             | 874 us                                                              | 1.07 ms: 1.22x slower                                                 |
| scimark_sor               | 74.4 ms                                                             | 90.7 ms: 1.22x slower                                                 |
| typing_runtime_protocols  | 322 us                                                              | 392 us: 1.22x slower                                                  |
| scimark_lu                | 67.9 ms                                                             | 84.7 ms: 1.25x slower                                                 |
| coroutines                | 16.4 ms                                                             | 21.4 ms: 1.30x slower                                                 |
| async_generators          | 191 ms                                                              | 260 ms: 1.36x slower                                                  |
| mypy2                     | 187 ms                                                              | 265 ms: 1.42x slower                                                  |
| Geometric mean            | (ref)                                                               | 1.05x slower                                                          |

Benchmark hidden because not significant (4): chaos, pickle, async_tree_cpu_io_mixed_tg, tornado_http
Ignored benchmarks (5) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509.json: aiohttp, coverage, flaskblogging, gunicorn, pylint


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
