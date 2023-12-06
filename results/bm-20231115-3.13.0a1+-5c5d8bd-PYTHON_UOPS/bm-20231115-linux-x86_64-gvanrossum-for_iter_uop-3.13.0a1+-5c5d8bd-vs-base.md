
# Results vs. base

- fork: gvanrossum
- ref: for_iter_uop
- machine: linux-x86_64
- commit hash: 5c5d8bd
- commit date: 2023-11-15
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1+-a646560 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 284 ms                                                                 | 291 ms: 1.03x slower                                               |
| chameleon      | 7.44 ms                                                                | 7.65 ms: 1.03x slower                                              |
| docutils       | 2.71 sec                                                               | 2.75 sec: 1.02x slower                                             |
| tornado_http   | 98.9 ms                                                                | 100 ms: 1.01x slower                                               |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1+-a646560 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 728 ms                                                                 | 742 ms: 1.02x slower                                               |
| async_tree_cpu_io_mixed_tg | 753 ms                                                                 | 770 ms: 1.02x slower                                               |
| async_tree_none_tg         | 470 ms                                                                 | 481 ms: 1.02x slower                                               |
| async_tree_memoization     | 581 ms                                                                 | 596 ms: 1.03x slower                                               |
| async_tree_io              | 1.20 sec                                                               | 1.24 sec: 1.03x slower                                             |
| async_tree_io_tg           | 1.23 sec                                                               | 1.26 sec: 1.03x slower                                             |
| Geometric mean             | (ref)                                                                  | 1.02x slower                                                       |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1+-a646560 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 188 ms                                                                 | 189 ms: 1.01x slower                                               |
| nbody          | 110 ms                                                                 | 121 ms: 1.10x slower                                               |
| float          | 97.8 ms                                                                | 109 ms: 1.11x slower                                               |
| Geometric mean | (ref)                                                                  | 1.07x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1+-a646560 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 223 ms                                                                 | 219 ms: 1.02x faster                                               |
| regex_effbot   | 3.71 ms                                                                | 3.65 ms: 1.02x faster                                              |
| regex_compile  | 157 ms                                                                 | 167 ms: 1.06x slower                                               |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                       |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1+-a646560 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_dict          | 36.5 us                                                                | 33.2 us: 1.10x faster                                              |
| pickle_list          | 5.18 us                                                                | 5.01 us: 1.03x faster                                              |
| unpickle             | 14.9 us                                                                | 14.7 us: 1.01x faster                                              |
| json_dumps           | 10.6 ms                                                                | 10.7 ms: 1.01x slower                                              |
| unpickle_list        | 5.13 us                                                                | 5.22 us: 1.02x slower                                              |
| json_loads           | 28.1 us                                                                | 28.8 us: 1.03x slower                                              |
| unpickle_pure_python | 242 us                                                                 | 255 us: 1.05x slower                                               |
| xml_etree_iterparse  | 111 ms                                                                 | 120 ms: 1.08x slower                                               |
| tomli_loads          | 2.73 sec                                                               | 2.99 sec: 1.09x slower                                             |
| xml_etree_generate   | 87.3 ms                                                                | 96.8 ms: 1.11x slower                                              |
| xml_etree_process    | 59.0 ms                                                                | 65.6 ms: 1.11x slower                                              |
| Geometric mean       | (ref)                                                                  | 1.03x slower                                                       |

Benchmark hidden because not significant (3): pickle, xml_etree_parse, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1+-a646560 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|------------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 10.4 ms                                                                | 10.4 ms: 1.00x slower                                              |
| python_startup_no_site | 9.03 ms                                                                | 9.07 ms: 1.00x slower                                              |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1+-a646560 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|-----------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 14.6 ms                                                                | 16.2 ms: 1.11x slower                                              |

All benchmarks:
===============

| Benchmark                  | bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1+-a646560 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_dict                | 36.5 us                                                                | 33.2 us: 1.10x faster                                              |
| pickle_list                | 5.18 us                                                                | 5.01 us: 1.03x faster                                              |
| regex_dna                  | 223 ms                                                                 | 219 ms: 1.02x faster                                               |
| gc_traversal               | 3.87 ms                                                                | 3.80 ms: 1.02x faster                                              |
| regex_effbot               | 3.71 ms                                                                | 3.65 ms: 1.02x faster                                              |
| generators                 | 29.6 ms                                                                | 29.2 ms: 1.01x faster                                              |
| pathlib                    | 19.1 ms                                                                | 18.8 ms: 1.01x faster                                              |
| unpickle                   | 14.9 us                                                                | 14.7 us: 1.01x faster                                              |
| coverage                   | 94.9 ms                                                                | 94.4 ms: 1.01x faster                                              |
| asyncio_tcp_ssl            | 1.80 sec                                                               | 1.80 sec: 1.00x faster                                             |
| python_startup             | 10.4 ms                                                                | 10.4 ms: 1.00x slower                                              |
| python_startup_no_site     | 9.03 ms                                                                | 9.07 ms: 1.00x slower                                              |
| pidigits                   | 188 ms                                                                 | 189 ms: 1.01x slower                                               |
| scimark_sor                | 128 ms                                                                 | 129 ms: 1.01x slower                                               |
| asyncio_tcp                | 497 ms                                                                 | 501 ms: 1.01x slower                                               |
| deepcopy_reduce            | 3.09 us                                                                | 3.12 us: 1.01x slower                                              |
| json_dumps                 | 10.6 ms                                                                | 10.7 ms: 1.01x slower                                              |
| tornado_http               | 98.9 ms                                                                | 100 ms: 1.01x slower                                               |
| mypy2                      | 353 ms                                                                 | 358 ms: 1.01x slower                                               |
| dask                       | 367 ms                                                                 | 372 ms: 1.01x slower                                               |
| dulwich_log                | 68.9 ms                                                                | 69.9 ms: 1.01x slower                                              |
| logging_silent             | 111 ns                                                                 | 112 ns: 1.02x slower                                               |
| docutils                   | 2.71 sec                                                               | 2.75 sec: 1.02x slower                                             |
| coroutines                 | 22.1 ms                                                                | 22.4 ms: 1.02x slower                                              |
| pycparser                  | 1.25 sec                                                               | 1.27 sec: 1.02x slower                                             |
| unpickle_list              | 5.13 us                                                                | 5.22 us: 1.02x slower                                              |
| async_tree_cpu_io_mixed    | 728 ms                                                                 | 742 ms: 1.02x slower                                               |
| json                       | 5.18 ms                                                                | 5.30 ms: 1.02x slower                                              |
| async_tree_cpu_io_mixed_tg | 753 ms                                                                 | 770 ms: 1.02x slower                                               |
| bench_thread_pool          | 854 us                                                                 | 873 us: 1.02x slower                                               |
| async_tree_none_tg         | 470 ms                                                                 | 481 ms: 1.02x slower                                               |
| typing_runtime_protocols   | 124 us                                                                 | 127 us: 1.02x slower                                               |
| async_tree_memoization     | 581 ms                                                                 | 596 ms: 1.03x slower                                               |
| 2to3                       | 284 ms                                                                 | 291 ms: 1.03x slower                                               |
| async_tree_io              | 1.20 sec                                                               | 1.24 sec: 1.03x slower                                             |
| json_loads                 | 28.1 us                                                                | 28.8 us: 1.03x slower                                              |
| async_tree_io_tg           | 1.23 sec                                                               | 1.26 sec: 1.03x slower                                             |
| sqlite_synth               | 2.87 us                                                                | 2.96 us: 1.03x slower                                              |
| chameleon                  | 7.44 ms                                                                | 7.65 ms: 1.03x slower                                              |
| logging_simple             | 6.10 us                                                                | 6.28 us: 1.03x slower                                              |
| raytrace                   | 302 ms                                                                 | 312 ms: 1.03x slower                                               |
| logging_format             | 6.78 us                                                                | 7.02 us: 1.04x slower                                              |
| deepcopy                   | 352 us                                                                 | 365 us: 1.04x slower                                               |
| go                         | 165 ms                                                                 | 172 ms: 1.04x slower                                               |
| mdp                        | 2.67 sec                                                               | 2.79 sec: 1.04x slower                                             |
| pprint_safe_repr           | 805 ms                                                                 | 841 ms: 1.04x slower                                               |
| sympy_expand               | 475 ms                                                                 | 497 ms: 1.05x slower                                               |
| deepcopy_memo              | 41.4 us                                                                | 43.4 us: 1.05x slower                                              |
| pprint_pformat             | 1.66 sec                                                               | 1.74 sec: 1.05x slower                                             |
| richards                   | 50.0 ms                                                                | 52.6 ms: 1.05x slower                                              |
| scimark_lu                 | 120 ms                                                                 | 126 ms: 1.05x slower                                               |
| sqlglot_transpile          | 1.66 ms                                                                | 1.74 ms: 1.05x slower                                              |
| sympy_integrate            | 21.2 ms                                                                | 22.3 ms: 1.05x slower                                              |
| unpickle_pure_python       | 242 us                                                                 | 255 us: 1.05x slower                                               |
| sqlglot_parse              | 1.34 ms                                                                | 1.42 ms: 1.06x slower                                              |
| scimark_fft                | 429 ms                                                                 | 453 ms: 1.06x slower                                               |
| regex_compile              | 157 ms                                                                 | 167 ms: 1.06x slower                                               |
| chaos                      | 72.6 ms                                                                | 77.2 ms: 1.06x slower                                              |
| meteor_contest             | 116 ms                                                                 | 124 ms: 1.07x slower                                               |
| richards_super             | 56.1 ms                                                                | 59.9 ms: 1.07x slower                                              |
| scimark_monte_carlo        | 80.6 ms                                                                | 86.4 ms: 1.07x slower                                              |
| xml_etree_iterparse        | 111 ms                                                                 | 120 ms: 1.08x slower                                               |
| sympy_str                  | 282 ms                                                                 | 306 ms: 1.08x slower                                               |
| sympy_sum                  | 153 ms                                                                 | 166 ms: 1.09x slower                                               |
| fannkuch                   | 478 ms                                                                 | 522 ms: 1.09x slower                                               |
| tomli_loads                | 2.73 sec                                                               | 2.99 sec: 1.09x slower                                             |
| crypto_pyaes               | 82.9 ms                                                                | 90.8 ms: 1.10x slower                                              |
| unpack_sequence            | 41.9 ns                                                                | 46.0 ns: 1.10x slower                                              |
| nbody                      | 110 ms                                                                 | 121 ms: 1.10x slower                                               |
| mako                       | 14.6 ms                                                                | 16.2 ms: 1.11x slower                                              |
| xml_etree_generate         | 87.3 ms                                                                | 96.8 ms: 1.11x slower                                              |
| nqueens                    | 102 ms                                                                 | 113 ms: 1.11x slower                                               |
| float                      | 97.8 ms                                                                | 109 ms: 1.11x slower                                               |
| xml_etree_process          | 59.0 ms                                                                | 65.6 ms: 1.11x slower                                              |
| sqlglot_normalize          | 107 ms                                                                 | 119 ms: 1.12x slower                                               |
| pyflate                    | 536 ms                                                                 | 599 ms: 1.12x slower                                               |
| sqlglot_optimize           | 54.4 ms                                                                | 60.9 ms: 1.12x slower                                              |
| deltablue                  | 4.89 ms                                                                | 5.64 ms: 1.15x slower                                              |
| comprehensions             | 23.3 us                                                                | 27.2 us: 1.17x slower                                              |
| scimark_sparse_mat_mult    | 6.30 ms                                                                | 7.36 ms: 1.17x slower                                              |
| hexiom                     | 9.27 ms                                                                | 10.9 ms: 1.18x slower                                              |
| spectral_norm              | 108 ms                                                                 | 186 ms: 1.71x slower                                               |
| Geometric mean             | (ref)                                                                  | 1.05x slower                                                       |

Benchmark hidden because not significant (11): telco, pickle, asyncio_websockets, bench_mp_pool, async_generators, regex_v8, create_gc_cycles, async_tree_memoization_tg, xml_etree_parse, pickle_pure_python, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
