
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: d65308a
- commit date: 2023-11-08
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 264 ms                                                                 | 270 ms: 1.02x slower                                           |
| chameleon      | 6.94 ms                                                                | 7.18 ms: 1.03x slower                                          |
| docutils       | 2.61 sec                                                               | 2.66 sec: 1.02x slower                                         |
| tornado_http   | 95.5 ms                                                                | 96.7 ms: 1.01x slower                                          |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_io_tg           | 1.23 sec                                                               | 1.24 sec: 1.01x slower                                         |
| async_tree_memoization     | 564 ms                                                                 | 572 ms: 1.01x slower                                           |
| async_tree_none_tg         | 456 ms                                                                 | 464 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 739 ms                                                                 | 751 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed    | 708 ms                                                                 | 721 ms: 1.02x slower                                           |
| async_tree_none            | 438 ms                                                                 | 448 ms: 1.02x slower                                           |
| Geometric mean             | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (2): async_tree_io, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 195 ms: 1.00x slower                                           |
| nbody          | 89.4 ms                                                                | 94.2 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                                | 3.59 ms: 1.00x slower                                          |
| regex_v8       | 25.6 ms                                                                | 25.8 ms: 1.01x slower                                          |
| regex_compile  | 135 ms                                                                 | 140 ms: 1.04x slower                                           |
| regex_dna      | 214 ms                                                                 | 223 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.13 sec                                                               | 2.04 sec: 1.04x faster                                         |
| pickle_list          | 5.15 us                                                                | 4.97 us: 1.04x faster                                          |
| pickle_dict          | 35.3 us                                                                | 34.3 us: 1.03x faster                                          |
| unpickle_list        | 5.32 us                                                                | 5.24 us: 1.02x faster                                          |
| xml_etree_parse      | 160 ms                                                                 | 158 ms: 1.01x faster                                           |
| json_loads           | 28.0 us                                                                | 27.9 us: 1.00x faster                                          |
| json_dumps           | 10.4 ms                                                                | 10.5 ms: 1.00x slower                                          |
| xml_etree_generate   | 86.3 ms                                                                | 87.1 ms: 1.01x slower                                          |
| pickle               | 11.4 us                                                                | 11.6 us: 1.02x slower                                          |
| xml_etree_process    | 59.3 ms                                                                | 60.4 ms: 1.02x slower                                          |
| xml_etree_iterparse  | 105 ms                                                                 | 107 ms: 1.02x slower                                           |
| unpickle             | 14.8 us                                                                | 15.2 us: 1.03x slower                                          |
| unpickle_pure_python | 219 us                                                                 | 227 us: 1.04x slower                                           |
| Geometric mean       | (ref)                                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.4 ms: 1.00x slower                                          |
| python_startup_no_site | 8.99 ms                                                                | 9.07 ms: 1.01x slower                                          |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.4 ms                                                                | 11.4 ms: 1.00x faster                                          |

All benchmarks:
===============

| Benchmark                  | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| richards_super             | 55.7 ms                                                                | 52.0 ms: 1.07x faster                                          |
| richards                   | 48.7 ms                                                                | 46.6 ms: 1.04x faster                                          |
| tomli_loads                | 2.13 sec                                                               | 2.04 sec: 1.04x faster                                         |
| logging_silent             | 109 ns                                                                 | 105 ns: 1.04x faster                                           |
| pickle_list                | 5.15 us                                                                | 4.97 us: 1.04x faster                                          |
| pickle_dict                | 35.3 us                                                                | 34.3 us: 1.03x faster                                          |
| spectral_norm              | 111 ms                                                                 | 108 ms: 1.03x faster                                           |
| scimark_sparse_mat_mult    | 4.87 ms                                                                | 4.77 ms: 1.02x faster                                          |
| logging_simple             | 5.84 us                                                                | 5.74 us: 1.02x faster                                          |
| unpickle_list              | 5.32 us                                                                | 5.24 us: 1.02x faster                                          |
| coverage                   | 95.9 ms                                                                | 94.5 ms: 1.02x faster                                          |
| xml_etree_parse            | 160 ms                                                                 | 158 ms: 1.01x faster                                           |
| telco                      | 8.35 ms                                                                | 8.27 ms: 1.01x faster                                          |
| create_gc_cycles           | 1.47 ms                                                                | 1.46 ms: 1.00x faster                                          |
| json_loads                 | 28.0 us                                                                | 27.9 us: 1.00x faster                                          |
| mako                       | 11.4 ms                                                                | 11.4 ms: 1.00x faster                                          |
| pidigits                   | 195 ms                                                                 | 195 ms: 1.00x slower                                           |
| python_startup             | 10.3 ms                                                                | 10.4 ms: 1.00x slower                                          |
| regex_effbot               | 3.57 ms                                                                | 3.59 ms: 1.00x slower                                          |
| json_dumps                 | 10.4 ms                                                                | 10.5 ms: 1.00x slower                                          |
| deepcopy_reduce            | 3.09 us                                                                | 3.10 us: 1.00x slower                                          |
| sqlglot_normalize          | 105 ms                                                                 | 106 ms: 1.00x slower                                           |
| regex_v8                   | 25.6 ms                                                                | 25.8 ms: 1.01x slower                                          |
| asyncio_tcp_ssl            | 1.79 sec                                                               | 1.80 sec: 1.01x slower                                         |
| sqlite_synth               | 2.77 us                                                                | 2.79 us: 1.01x slower                                          |
| sqlglot_transpile          | 1.61 ms                                                                | 1.62 ms: 1.01x slower                                          |
| sympy_expand               | 455 ms                                                                 | 459 ms: 1.01x slower                                           |
| async_tree_io_tg           | 1.23 sec                                                               | 1.24 sec: 1.01x slower                                         |
| python_startup_no_site     | 8.99 ms                                                                | 9.07 ms: 1.01x slower                                          |
| xml_etree_generate         | 86.3 ms                                                                | 87.1 ms: 1.01x slower                                          |
| coroutines                 | 22.2 ms                                                                | 22.4 ms: 1.01x slower                                          |
| tornado_http               | 95.5 ms                                                                | 96.7 ms: 1.01x slower                                          |
| sqlglot_optimize           | 53.5 ms                                                                | 54.2 ms: 1.01x slower                                          |
| asyncio_tcp                | 482 ms                                                                 | 488 ms: 1.01x slower                                           |
| async_tree_memoization     | 564 ms                                                                 | 572 ms: 1.01x slower                                           |
| pickle                     | 11.4 us                                                                | 11.6 us: 1.02x slower                                          |
| async_tree_none_tg         | 456 ms                                                                 | 464 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed_tg | 739 ms                                                                 | 751 ms: 1.02x slower                                           |
| async_tree_cpu_io_mixed    | 708 ms                                                                 | 721 ms: 1.02x slower                                           |
| docutils                   | 2.61 sec                                                               | 2.66 sec: 1.02x slower                                         |
| xml_etree_process          | 59.3 ms                                                                | 60.4 ms: 1.02x slower                                          |
| dulwich_log                | 65.6 ms                                                                | 66.9 ms: 1.02x slower                                          |
| deepcopy                   | 344 us                                                                 | 351 us: 1.02x slower                                           |
| fannkuch                   | 402 ms                                                                 | 410 ms: 1.02x slower                                           |
| raytrace                   | 277 ms                                                                 | 283 ms: 1.02x slower                                           |
| scimark_fft                | 362 ms                                                                 | 369 ms: 1.02x slower                                           |
| xml_etree_iterparse        | 105 ms                                                                 | 107 ms: 1.02x slower                                           |
| async_tree_none            | 438 ms                                                                 | 448 ms: 1.02x slower                                           |
| pyflate                    | 479 ms                                                                 | 490 ms: 1.02x slower                                           |
| 2to3                       | 264 ms                                                                 | 270 ms: 1.02x slower                                           |
| mypy2                      | 342 ms                                                                 | 350 ms: 1.02x slower                                           |
| unpickle                   | 14.8 us                                                                | 15.2 us: 1.03x slower                                          |
| meteor_contest             | 111 ms                                                                 | 114 ms: 1.03x slower                                           |
| sympy_sum                  | 148 ms                                                                 | 153 ms: 1.03x slower                                           |
| bench_thread_pool          | 826 us                                                                 | 853 us: 1.03x slower                                           |
| deepcopy_memo              | 38.5 us                                                                | 39.8 us: 1.03x slower                                          |
| chameleon                  | 6.94 ms                                                                | 7.18 ms: 1.03x slower                                          |
| typing_runtime_protocols   | 117 us                                                                 | 121 us: 1.04x slower                                           |
| pprint_safe_repr           | 737 ms                                                                 | 764 ms: 1.04x slower                                           |
| regex_compile              | 135 ms                                                                 | 140 ms: 1.04x slower                                           |
| go                         | 142 ms                                                                 | 147 ms: 1.04x slower                                           |
| scimark_lu                 | 115 ms                                                                 | 119 ms: 1.04x slower                                           |
| regex_dna                  | 214 ms                                                                 | 223 ms: 1.04x slower                                           |
| unpickle_pure_python       | 219 us                                                                 | 227 us: 1.04x slower                                           |
| mdp                        | 2.71 sec                                                               | 2.82 sec: 1.04x slower                                         |
| crypto_pyaes               | 70.3 ms                                                                | 73.4 ms: 1.04x slower                                          |
| generators                 | 29.6 ms                                                                | 30.9 ms: 1.04x slower                                          |
| chaos                      | 60.6 ms                                                                | 63.3 ms: 1.04x slower                                          |
| async_generators           | 440 ms                                                                 | 459 ms: 1.05x slower                                           |
| sympy_integrate            | 19.5 ms                                                                | 20.4 ms: 1.05x slower                                          |
| pprint_pformat             | 1.51 sec                                                               | 1.58 sec: 1.05x slower                                         |
| scimark_monte_carlo        | 68.0 ms                                                                | 71.5 ms: 1.05x slower                                          |
| nbody                      | 89.4 ms                                                                | 94.2 ms: 1.05x slower                                          |
| gc_traversal               | 3.58 ms                                                                | 3.82 ms: 1.07x slower                                          |
| deltablue                  | 3.43 ms                                                                | 3.71 ms: 1.08x slower                                          |
| nqueens                    | 78.7 ms                                                                | 88.5 ms: 1.13x slower                                          |
| unpack_sequence            | 47.2 ns                                                                | 53.2 ns: 1.13x slower                                          |
| hexiom                     | 6.23 ms                                                                | 7.04 ms: 1.13x slower                                          |
| comprehensions             | 16.2 us                                                                | 18.5 us: 1.14x slower                                          |
| Geometric mean             | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (13): scimark_sor, pycparser, logging_format, asyncio_websockets, async_tree_io, json, bench_mp_pool, sqlglot_parse, float, pathlib, pickle_pure_python, sympy_str, async_tree_memoization_tg


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
