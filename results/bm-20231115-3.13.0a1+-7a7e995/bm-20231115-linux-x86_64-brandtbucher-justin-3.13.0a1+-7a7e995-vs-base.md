
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 264 ms                                                                 | 272 ms: 1.03x slower                                           |
| chameleon      | 6.98 ms                                                                | 7.34 ms: 1.05x slower                                          |
| docutils       | 2.61 sec                                                               | 2.65 sec: 1.02x slower                                         |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|---------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_io_tg          | 1.23 sec                                                               | 1.23 sec: 1.00x slower                                         |
| async_tree_io             | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                         |
| async_tree_memoization    | 563 ms                                                                 | 569 ms: 1.01x slower                                           |
| async_tree_memoization_tg | 595 ms                                                                 | 603 ms: 1.01x slower                                           |
| async_tree_none_tg        | 454 ms                                                                 | 461 ms: 1.02x slower                                           |
| Geometric mean            | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (3): async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 195 ms: 1.00x slower                                           |
| nbody          | 94.0 ms                                                                | 97.3 ms: 1.04x slower                                          |
| float          | 81.8 ms                                                                | 86.5 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 217 ms                                                                 | 214 ms: 1.01x faster                                           |
| regex_compile  | 135 ms                                                                 | 141 ms: 1.04x slower                                           |
| regex_v8       | 24.5 ms                                                                | 25.7 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle               | 11.7 us                                                                | 11.1 us: 1.05x faster                                          |
| pickle_list          | 5.09 us                                                                | 4.90 us: 1.04x faster                                          |
| xml_etree_parse      | 157 ms                                                                 | 158 ms: 1.01x slower                                           |
| xml_etree_process    | 59.4 ms                                                                | 60.0 ms: 1.01x slower                                          |
| json_dumps           | 10.5 ms                                                                | 10.6 ms: 1.01x slower                                          |
| json_loads           | 27.8 us                                                                | 28.2 us: 1.01x slower                                          |
| xml_etree_generate   | 86.4 ms                                                                | 87.8 ms: 1.02x slower                                          |
| xml_etree_iterparse  | 105 ms                                                                 | 108 ms: 1.03x slower                                           |
| tomli_loads          | 2.13 sec                                                               | 2.23 sec: 1.05x slower                                         |
| unpickle_pure_python | 219 us                                                                 | 231 us: 1.05x slower                                           |
| unpickle_list        | 5.06 us                                                                | 5.36 us: 1.06x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (3): unpickle, pickle_dict, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 10.4 ms                                                                | 10.4 ms: 1.01x slower                                          |
| python_startup_no_site | 9.02 ms                                                                | 9.10 ms: 1.01x slower                                          |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.5 ms                                                                | 12.3 ms: 1.07x slower                                          |

All benchmarks:
===============

| Benchmark                 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|---------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle                    | 11.7 us                                                                | 11.1 us: 1.05x faster                                          |
| pickle_list               | 5.09 us                                                                | 4.90 us: 1.04x faster                                          |
| spectral_norm             | 114 ms                                                                 | 110 ms: 1.03x faster                                           |
| richards_super            | 54.1 ms                                                                | 52.8 ms: 1.02x faster                                          |
| generators                | 29.7 ms                                                                | 29.2 ms: 1.02x faster                                          |
| gc_traversal              | 3.87 ms                                                                | 3.82 ms: 1.01x faster                                          |
| regex_dna                 | 217 ms                                                                 | 214 ms: 1.01x faster                                           |
| richards                  | 47.4 ms                                                                | 46.9 ms: 1.01x faster                                          |
| coroutines                | 21.9 ms                                                                | 21.9 ms: 1.00x faster                                          |
| pidigits                  | 195 ms                                                                 | 195 ms: 1.00x slower                                           |
| asyncio_tcp_ssl           | 1.79 sec                                                               | 1.80 sec: 1.00x slower                                         |
| async_tree_io_tg          | 1.23 sec                                                               | 1.23 sec: 1.00x slower                                         |
| create_gc_cycles          | 1.48 ms                                                                | 1.48 ms: 1.00x slower                                          |
| sqlglot_normalize         | 106 ms                                                                 | 107 ms: 1.00x slower                                           |
| python_startup            | 10.4 ms                                                                | 10.4 ms: 1.01x slower                                          |
| deepcopy_reduce           | 3.11 us                                                                | 3.13 us: 1.01x slower                                          |
| async_tree_io             | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                         |
| python_startup_no_site    | 9.02 ms                                                                | 9.10 ms: 1.01x slower                                          |
| unpack_sequence           | 49.4 ns                                                                | 49.9 ns: 1.01x slower                                          |
| xml_etree_parse           | 157 ms                                                                 | 158 ms: 1.01x slower                                           |
| xml_etree_process         | 59.4 ms                                                                | 60.0 ms: 1.01x slower                                          |
| dulwich_log               | 65.9 ms                                                                | 66.6 ms: 1.01x slower                                          |
| scimark_lu                | 116 ms                                                                 | 118 ms: 1.01x slower                                           |
| async_tree_memoization    | 563 ms                                                                 | 569 ms: 1.01x slower                                           |
| sqlglot_optimize          | 53.5 ms                                                                | 54.1 ms: 1.01x slower                                          |
| pycparser                 | 1.20 sec                                                               | 1.21 sec: 1.01x slower                                         |
| json                      | 5.12 ms                                                                | 5.18 ms: 1.01x slower                                          |
| json_dumps                | 10.5 ms                                                                | 10.6 ms: 1.01x slower                                          |
| deepcopy                  | 348 us                                                                 | 353 us: 1.01x slower                                           |
| json_loads                | 27.8 us                                                                | 28.2 us: 1.01x slower                                          |
| pathlib                   | 18.2 ms                                                                | 18.5 ms: 1.01x slower                                          |
| async_tree_memoization_tg | 595 ms                                                                 | 603 ms: 1.01x slower                                           |
| bench_thread_pool         | 834 us                                                                 | 845 us: 1.01x slower                                           |
| xml_etree_generate        | 86.4 ms                                                                | 87.8 ms: 1.02x slower                                          |
| sympy_sum                 | 148 ms                                                                 | 150 ms: 1.02x slower                                           |
| meteor_contest            | 108 ms                                                                 | 110 ms: 1.02x slower                                           |
| async_tree_none_tg        | 454 ms                                                                 | 461 ms: 1.02x slower                                           |
| docutils                  | 2.61 sec                                                               | 2.65 sec: 1.02x slower                                         |
| sqlglot_parse             | 1.28 ms                                                                | 1.30 ms: 1.02x slower                                          |
| sqlglot_transpile         | 1.59 ms                                                                | 1.62 ms: 1.02x slower                                          |
| sympy_expand              | 454 ms                                                                 | 463 ms: 1.02x slower                                           |
| sympy_str                 | 267 ms                                                                 | 273 ms: 1.02x slower                                           |
| mypy2                     | 342 ms                                                                 | 350 ms: 1.02x slower                                           |
| scimark_fft               | 372 ms                                                                 | 383 ms: 1.03x slower                                           |
| 2to3                      | 264 ms                                                                 | 272 ms: 1.03x slower                                           |
| xml_etree_iterparse       | 105 ms                                                                 | 108 ms: 1.03x slower                                           |
| logging_simple            | 5.68 us                                                                | 5.85 us: 1.03x slower                                          |
| async_generators          | 447 ms                                                                 | 461 ms: 1.03x slower                                           |
| mdp                       | 2.54 sec                                                               | 2.63 sec: 1.03x slower                                         |
| raytrace                  | 277 ms                                                                 | 287 ms: 1.04x slower                                           |
| logging_format            | 6.24 us                                                                | 6.46 us: 1.04x slower                                          |
| nbody                     | 94.0 ms                                                                | 97.3 ms: 1.04x slower                                          |
| deepcopy_memo             | 38.5 us                                                                | 40.1 us: 1.04x slower                                          |
| regex_compile             | 135 ms                                                                 | 141 ms: 1.04x slower                                           |
| tomli_loads               | 2.13 sec                                                               | 2.23 sec: 1.05x slower                                         |
| scimark_sparse_mat_mult   | 5.21 ms                                                                | 5.45 ms: 1.05x slower                                          |
| typing_runtime_protocols  | 116 us                                                                 | 122 us: 1.05x slower                                           |
| regex_v8                  | 24.5 ms                                                                | 25.7 ms: 1.05x slower                                          |
| sympy_integrate           | 19.5 ms                                                                | 20.5 ms: 1.05x slower                                          |
| chameleon                 | 6.98 ms                                                                | 7.34 ms: 1.05x slower                                          |
| unpickle_pure_python      | 219 us                                                                 | 231 us: 1.05x slower                                           |
| float                     | 81.8 ms                                                                | 86.5 ms: 1.06x slower                                          |
| unpickle_list             | 5.06 us                                                                | 5.36 us: 1.06x slower                                          |
| go                        | 141 ms                                                                 | 149 ms: 1.06x slower                                           |
| mako                      | 11.5 ms                                                                | 12.3 ms: 1.07x slower                                          |
| pprint_pformat            | 1.51 sec                                                               | 1.62 sec: 1.08x slower                                         |
| crypto_pyaes              | 71.6 ms                                                                | 77.1 ms: 1.08x slower                                          |
| scimark_monte_carlo       | 68.6 ms                                                                | 74.0 ms: 1.08x slower                                          |
| chaos                     | 61.0 ms                                                                | 65.8 ms: 1.08x slower                                          |
| pprint_safe_repr          | 738 ms                                                                 | 798 ms: 1.08x slower                                           |
| fannkuch                  | 393 ms                                                                 | 430 ms: 1.10x slower                                           |
| pyflate                   | 466 ms                                                                 | 513 ms: 1.10x slower                                           |
| nqueens                   | 81.4 ms                                                                | 90.9 ms: 1.12x slower                                          |
| comprehensions            | 16.8 us                                                                | 19.3 us: 1.15x slower                                          |
| deltablue                 | 3.33 ms                                                                | 4.00 ms: 1.20x slower                                          |
| hexiom                    | 6.19 ms                                                                | 7.59 ms: 1.23x slower                                          |
| Geometric mean            | (ref)                                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (17): unpickle, sqlite_synth, logging_silent, coverage, regex_effbot, async_tree_cpu_io_mixed_tg, asyncio_tcp, pickle_dict, bench_mp_pool, asyncio_websockets, scimark_sor, async_tree_cpu_io_mixed, pickle_pure_python, telco, dask, tornado_http, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
