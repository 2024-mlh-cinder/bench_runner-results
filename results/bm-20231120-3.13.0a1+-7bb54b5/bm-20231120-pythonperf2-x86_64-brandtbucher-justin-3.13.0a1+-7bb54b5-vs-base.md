
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 291 ms                                                                       | 302 ms: 1.04x slower                                                 |
| chameleon      | 7.33 ms                                                                      | 7.53 ms: 1.03x slower                                                |
| docutils       | 2.82 sec                                                                     | 2.87 sec: 1.02x slower                                               |
| tornado_http   | 118 ms                                                                       | 122 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                                        | 1.03x slower                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 712 ms                                                                       | 720 ms: 1.01x slower                                                 |
| async_tree_cpu_io_mixed    | 696 ms                                                                       | 708 ms: 1.02x slower                                                 |
| async_tree_io              | 1.07 sec                                                                     | 1.09 sec: 1.02x slower                                               |
| async_tree_io_tg           | 1.08 sec                                                                     | 1.10 sec: 1.02x slower                                               |
| async_tree_memoization     | 540 ms                                                                       | 554 ms: 1.03x slower                                                 |
| async_tree_none_tg         | 434 ms                                                                       | 447 ms: 1.03x slower                                                 |
| async_tree_none            | 427 ms                                                                       | 441 ms: 1.03x slower                                                 |
| async_tree_memoization_tg  | 553 ms                                                                       | 578 ms: 1.05x slower                                                 |
| Geometric mean             | (ref)                                                                        | 1.03x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 78.8 ms                                                                      | 81.0 ms: 1.03x slower                                                |
| nbody          | 85.0 ms                                                                      | 94.4 ms: 1.11x slower                                                |
| Geometric mean | (ref)                                                                        | 1.04x slower                                                         |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_dna      | 240 ms                                                                       | 240 ms: 1.00x faster                                                 |
| regex_v8       | 24.9 ms                                                                      | 25.5 ms: 1.02x slower                                                |
| regex_effbot   | 3.47 ms                                                                      | 3.57 ms: 1.03x slower                                                |
| regex_compile  | 142 ms                                                                       | 150 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                                        | 1.03x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_list          | 4.40 us                                                                      | 4.24 us: 1.04x faster                                                |
| unpickle_pure_python | 225 us                                                                       | 227 us: 1.01x slower                                                 |
| json_loads           | 25.5 us                                                                      | 25.7 us: 1.01x slower                                                |
| xml_etree_parse      | 146 ms                                                                       | 148 ms: 1.01x slower                                                 |
| xml_etree_iterparse  | 105 ms                                                                       | 106 ms: 1.01x slower                                                 |
| unpickle_list        | 4.60 us                                                                      | 4.69 us: 1.02x slower                                                |
| json_dumps           | 10.5 ms                                                                      | 10.8 ms: 1.02x slower                                                |
| pickle_dict          | 32.4 us                                                                      | 33.3 us: 1.03x slower                                                |
| pickle_pure_python   | 307 us                                                                       | 316 us: 1.03x slower                                                 |
| unpickle             | 14.4 us                                                                      | 14.9 us: 1.03x slower                                                |
| xml_etree_generate   | 83.6 ms                                                                      | 86.8 ms: 1.04x slower                                                |
| xml_etree_process    | 57.4 ms                                                                      | 59.7 ms: 1.04x slower                                                |
| tomli_loads          | 2.14 sec                                                                     | 2.29 sec: 1.07x slower                                               |
| Geometric mean       | (ref)                                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 12.8 ms                                                                      | 12.9 ms: 1.01x slower                                                |
| python_startup_no_site | 11.2 ms                                                                      | 11.4 ms: 1.01x slower                                                |
| Geometric mean         | (ref)                                                                        | 1.01x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.3 ms                                                                      | 11.0 ms: 1.07x slower                                                |

All benchmarks:
===============

| Benchmark                  | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpack_sequence            | 52.6 ns                                                                      | 48.0 ns: 1.10x faster                                                |
| richards                   | 52.9 ms                                                                      | 49.9 ms: 1.06x faster                                                |
| richards_super             | 58.6 ms                                                                      | 56.1 ms: 1.05x faster                                                |
| pickle_list                | 4.40 us                                                                      | 4.24 us: 1.04x faster                                                |
| coverage                   | 82.2 ms                                                                      | 79.9 ms: 1.03x faster                                                |
| create_gc_cycles           | 1.61 ms                                                                      | 1.59 ms: 1.02x faster                                                |
| asyncio_tcp                | 370 ms                                                                       | 366 ms: 1.01x faster                                                 |
| logging_format             | 7.26 us                                                                      | 7.20 us: 1.01x faster                                                |
| dulwich_log                | 67.9 ms                                                                      | 67.7 ms: 1.00x faster                                                |
| regex_dna                  | 240 ms                                                                       | 240 ms: 1.00x faster                                                 |
| asyncio_tcp_ssl            | 1.57 sec                                                                     | 1.57 sec: 1.00x slower                                               |
| go                         | 167 ms                                                                       | 168 ms: 1.00x slower                                                 |
| pathlib                    | 19.0 ms                                                                      | 19.1 ms: 1.01x slower                                                |
| scimark_sparse_mat_mult    | 4.32 ms                                                                      | 4.35 ms: 1.01x slower                                                |
| unpickle_pure_python       | 225 us                                                                       | 227 us: 1.01x slower                                                 |
| json_loads                 | 25.5 us                                                                      | 25.7 us: 1.01x slower                                                |
| python_startup             | 12.8 ms                                                                      | 12.9 ms: 1.01x slower                                                |
| xml_etree_parse            | 146 ms                                                                       | 148 ms: 1.01x slower                                                 |
| python_startup_no_site     | 11.2 ms                                                                      | 11.4 ms: 1.01x slower                                                |
| xml_etree_iterparse        | 105 ms                                                                       | 106 ms: 1.01x slower                                                 |
| logging_simple             | 6.54 us                                                                      | 6.62 us: 1.01x slower                                                |
| async_tree_cpu_io_mixed_tg | 712 ms                                                                       | 720 ms: 1.01x slower                                                 |
| coroutines                 | 22.2 ms                                                                      | 22.6 ms: 1.02x slower                                                |
| pyflate                    | 506 ms                                                                       | 515 ms: 1.02x slower                                                 |
| async_tree_cpu_io_mixed    | 696 ms                                                                       | 708 ms: 1.02x slower                                                 |
| async_tree_io              | 1.07 sec                                                                     | 1.09 sec: 1.02x slower                                               |
| async_tree_io_tg           | 1.08 sec                                                                     | 1.10 sec: 1.02x slower                                               |
| unpickle_list              | 4.60 us                                                                      | 4.69 us: 1.02x slower                                                |
| generators                 | 35.3 ms                                                                      | 36.0 ms: 1.02x slower                                                |
| docutils                   | 2.82 sec                                                                     | 2.87 sec: 1.02x slower                                               |
| regex_v8                   | 24.9 ms                                                                      | 25.5 ms: 1.02x slower                                                |
| json_dumps                 | 10.5 ms                                                                      | 10.8 ms: 1.02x slower                                                |
| sqlglot_parse              | 1.40 ms                                                                      | 1.43 ms: 1.02x slower                                                |
| deepcopy                   | 358 us                                                                       | 366 us: 1.02x slower                                                 |
| async_tree_memoization     | 540 ms                                                                       | 554 ms: 1.03x slower                                                 |
| pickle_dict                | 32.4 us                                                                      | 33.3 us: 1.03x slower                                                |
| chameleon                  | 7.33 ms                                                                      | 7.53 ms: 1.03x slower                                                |
| float                      | 78.8 ms                                                                      | 81.0 ms: 1.03x slower                                                |
| logging_silent             | 96.2 ns                                                                      | 99.0 ns: 1.03x slower                                                |
| sqlglot_transpile          | 1.80 ms                                                                      | 1.86 ms: 1.03x slower                                                |
| regex_effbot               | 3.47 ms                                                                      | 3.57 ms: 1.03x slower                                                |
| deepcopy_memo              | 36.0 us                                                                      | 37.1 us: 1.03x slower                                                |
| async_tree_none_tg         | 434 ms                                                                       | 447 ms: 1.03x slower                                                 |
| deepcopy_reduce            | 3.21 us                                                                      | 3.31 us: 1.03x slower                                                |
| telco                      | 8.11 ms                                                                      | 8.36 ms: 1.03x slower                                                |
| pickle_pure_python         | 307 us                                                                       | 316 us: 1.03x slower                                                 |
| tornado_http               | 118 ms                                                                       | 122 ms: 1.03x slower                                                 |
| dask                       | 392 ms                                                                       | 404 ms: 1.03x slower                                                 |
| unpickle                   | 14.4 us                                                                      | 14.9 us: 1.03x slower                                                |
| async_tree_none            | 427 ms                                                                       | 441 ms: 1.03x slower                                                 |
| sympy_expand               | 488 ms                                                                       | 506 ms: 1.04x slower                                                 |
| json                       | 5.13 ms                                                                      | 5.32 ms: 1.04x slower                                                |
| scimark_lu                 | 99.9 ms                                                                      | 104 ms: 1.04x slower                                                 |
| deltablue                  | 3.57 ms                                                                      | 3.71 ms: 1.04x slower                                                |
| meteor_contest             | 127 ms                                                                       | 132 ms: 1.04x slower                                                 |
| xml_etree_generate         | 83.6 ms                                                                      | 86.8 ms: 1.04x slower                                                |
| 2to3                       | 291 ms                                                                       | 302 ms: 1.04x slower                                                 |
| xml_etree_process          | 57.4 ms                                                                      | 59.7 ms: 1.04x slower                                                |
| typing_runtime_protocols   | 124 us                                                                       | 129 us: 1.04x slower                                                 |
| mypy2                      | 364 ms                                                                       | 380 ms: 1.04x slower                                                 |
| mdp                        | 2.50 sec                                                                     | 2.61 sec: 1.04x slower                                               |
| async_tree_memoization_tg  | 553 ms                                                                       | 578 ms: 1.05x slower                                                 |
| gc_traversal               | 3.74 ms                                                                      | 3.93 ms: 1.05x slower                                                |
| sympy_str                  | 287 ms                                                                       | 302 ms: 1.05x slower                                                 |
| regex_compile              | 142 ms                                                                       | 150 ms: 1.05x slower                                                 |
| raytrace                   | 272 ms                                                                       | 288 ms: 1.06x slower                                                 |
| bench_mp_pool              | 4.52 ms                                                                      | 4.80 ms: 1.06x slower                                                |
| sympy_integrate            | 22.9 ms                                                                      | 24.4 ms: 1.06x slower                                                |
| sqlglot_optimize           | 57.9 ms                                                                      | 61.7 ms: 1.07x slower                                                |
| sqlglot_normalize          | 114 ms                                                                       | 122 ms: 1.07x slower                                                 |
| sympy_sum                  | 149 ms                                                                       | 160 ms: 1.07x slower                                                 |
| mako                       | 10.3 ms                                                                      | 11.0 ms: 1.07x slower                                                |
| tomli_loads                | 2.14 sec                                                                     | 2.29 sec: 1.07x slower                                               |
| pprint_safe_repr           | 786 ms                                                                       | 850 ms: 1.08x slower                                                 |
| pprint_pformat             | 1.61 sec                                                                     | 1.74 sec: 1.08x slower                                               |
| async_generators           | 358 ms                                                                       | 395 ms: 1.10x slower                                                 |
| fannkuch                   | 374 ms                                                                       | 414 ms: 1.11x slower                                                 |
| nbody                      | 85.0 ms                                                                      | 94.4 ms: 1.11x slower                                                |
| spectral_norm              | 90.4 ms                                                                      | 101 ms: 1.12x slower                                                 |
| crypto_pyaes               | 71.6 ms                                                                      | 81.3 ms: 1.14x slower                                                |
| scimark_monte_carlo        | 68.0 ms                                                                      | 78.4 ms: 1.15x slower                                                |
| chaos                      | 60.8 ms                                                                      | 70.3 ms: 1.16x slower                                                |
| nqueens                    | 88.0 ms                                                                      | 103 ms: 1.17x slower                                                 |
| scimark_fft                | 308 ms                                                                       | 375 ms: 1.22x slower                                                 |
| comprehensions             | 16.6 us                                                                      | 20.3 us: 1.22x slower                                                |
| hexiom                     | 6.35 ms                                                                      | 7.82 ms: 1.23x slower                                                |
| Geometric mean             | (ref)                                                                        | 1.04x slower                                                         |

Benchmark hidden because not significant (7): asyncio_websockets, pycparser, pidigits, pickle, sqlite_synth, scimark_sor, bench_thread_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
