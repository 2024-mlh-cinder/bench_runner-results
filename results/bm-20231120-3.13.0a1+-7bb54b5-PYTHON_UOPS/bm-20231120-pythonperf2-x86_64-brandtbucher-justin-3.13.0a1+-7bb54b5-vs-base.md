
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.10x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| 2to3           | 323 ms                                                                       | 300 ms: 1.07x faster                                                 |
| chameleon      | 7.96 ms                                                                      | 7.58 ms: 1.05x faster                                                |
| docutils       | 2.97 sec                                                                     | 2.88 sec: 1.03x faster                                               |
| tornado_http   | 126 ms                                                                       | 121 ms: 1.04x faster                                                 |
| Geometric mean | (ref)                                                                        | 1.05x faster                                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| async_tree_none            | 461 ms                                                                       | 439 ms: 1.05x faster                                                 |
| async_tree_none_tg         | 467 ms                                                                       | 446 ms: 1.05x faster                                                 |
| async_tree_memoization     | 576 ms                                                                       | 550 ms: 1.05x faster                                                 |
| async_tree_cpu_io_mixed    | 726 ms                                                                       | 701 ms: 1.04x faster                                                 |
| async_tree_cpu_io_mixed_tg | 743 ms                                                                       | 719 ms: 1.03x faster                                                 |
| async_tree_io              | 1.12 sec                                                                     | 1.08 sec: 1.03x faster                                               |
| async_tree_io_tg           | 1.14 sec                                                                     | 1.10 sec: 1.03x faster                                               |
| Geometric mean             | (ref)                                                                        | 1.03x faster                                                         |

Benchmark hidden because not significant (1): async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 140 ms                                                                       | 96.3 ms: 1.46x faster                                                |
| float          | 109 ms                                                                       | 79.1 ms: 1.38x faster                                                |
| pidigits       | 268 ms                                                                       | 265 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                                        | 1.27x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 182 ms                                                                       | 150 ms: 1.22x faster                                                 |
| regex_v8       | 25.2 ms                                                                      | 25.7 ms: 1.02x slower                                                |
| regex_effbot   | 3.45 ms                                                                      | 3.53 ms: 1.02x slower                                                |
| regex_dna      | 238 ms                                                                       | 244 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                                        | 1.03x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| tomli_loads          | 2.97 sec                                                                     | 2.28 sec: 1.30x faster                                               |
| xml_etree_iterparse  | 122 ms                                                                       | 105 ms: 1.16x faster                                                 |
| unpickle_pure_python | 257 us                                                                       | 221 us: 1.16x faster                                                 |
| xml_etree_generate   | 94.1 ms                                                                      | 86.1 ms: 1.09x faster                                                |
| xml_etree_process    | 64.4 ms                                                                      | 59.1 ms: 1.09x faster                                                |
| xml_etree_parse      | 153 ms                                                                       | 143 ms: 1.07x faster                                                 |
| pickle_dict          | 32.6 us                                                                      | 31.6 us: 1.03x faster                                                |
| pickle_pure_python   | 315 us                                                                       | 308 us: 1.02x faster                                                 |
| unpickle_list        | 4.63 us                                                                      | 4.54 us: 1.02x faster                                                |
| json_dumps           | 10.9 ms                                                                      | 10.8 ms: 1.01x faster                                                |
| unpickle             | 14.5 us                                                                      | 14.7 us: 1.01x slower                                                |
| pickle               | 9.99 us                                                                      | 10.2 us: 1.02x slower                                                |
| pickle_list          | 4.19 us                                                                      | 4.48 us: 1.07x slower                                                |
| Geometric mean       | (ref)                                                                        | 1.06x faster                                                         |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 12.9 ms                                                                      | 12.9 ms: 1.00x faster                                                |
| python_startup_no_site | 11.3 ms                                                                      | 11.3 ms: 1.00x slower                                                |
| Geometric mean         | (ref)                                                                        | 1.00x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 17.8 ms                                                                      | 11.0 ms: 1.61x faster                                                |

All benchmarks:
===============

| Benchmark                  | bm-20231120-pythonperf2-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| spectral_norm              | 179 ms                                                                       | 102 ms: 1.75x faster                                                 |
| mako                       | 17.8 ms                                                                      | 11.0 ms: 1.61x faster                                                |
| deltablue                  | 5.93 ms                                                                      | 3.69 ms: 1.61x faster                                                |
| hexiom                     | 11.4 ms                                                                      | 7.80 ms: 1.46x faster                                                |
| nbody                      | 140 ms                                                                       | 96.3 ms: 1.46x faster                                                |
| scimark_sparse_mat_mult    | 6.61 ms                                                                      | 4.59 ms: 1.44x faster                                                |
| comprehensions             | 28.8 us                                                                      | 20.2 us: 1.42x faster                                                |
| float                      | 109 ms                                                                       | 79.1 ms: 1.38x faster                                                |
| tomli_loads                | 2.97 sec                                                                     | 2.28 sec: 1.30x faster                                               |
| fannkuch                   | 523 ms                                                                       | 413 ms: 1.26x faster                                                 |
| scimark_fft                | 452 ms                                                                       | 364 ms: 1.24x faster                                                 |
| chaos                      | 84.7 ms                                                                      | 69.6 ms: 1.22x faster                                                |
| regex_compile              | 182 ms                                                                       | 150 ms: 1.22x faster                                                 |
| unpack_sequence            | 52.8 ns                                                                      | 43.9 ns: 1.20x faster                                                |
| crypto_pyaes               | 97.9 ms                                                                      | 81.7 ms: 1.20x faster                                                |
| nqueens                    | 121 ms                                                                       | 101 ms: 1.20x faster                                                 |
| pyflate                    | 613 ms                                                                       | 520 ms: 1.18x faster                                                 |
| go                         | 197 ms                                                                       | 168 ms: 1.17x faster                                                 |
| gc_traversal               | 3.99 ms                                                                      | 3.42 ms: 1.17x faster                                                |
| xml_etree_iterparse        | 122 ms                                                                       | 105 ms: 1.16x faster                                                 |
| unpickle_pure_python       | 257 us                                                                       | 221 us: 1.16x faster                                                 |
| scimark_monte_carlo        | 91.8 ms                                                                      | 79.0 ms: 1.16x faster                                                |
| deepcopy_memo              | 42.1 us                                                                      | 36.9 us: 1.14x faster                                                |
| richards                   | 56.8 ms                                                                      | 50.2 ms: 1.13x faster                                                |
| pprint_pformat             | 1.95 sec                                                                     | 1.74 sec: 1.12x faster                                               |
| sympy_str                  | 337 ms                                                                       | 301 ms: 1.12x faster                                                 |
| raytrace                   | 322 ms                                                                       | 288 ms: 1.12x faster                                                 |
| pprint_safe_repr           | 945 ms                                                                       | 852 ms: 1.11x faster                                                 |
| xml_etree_generate         | 94.1 ms                                                                      | 86.1 ms: 1.09x faster                                                |
| richards_super             | 62.3 ms                                                                      | 57.0 ms: 1.09x faster                                                |
| sympy_sum                  | 174 ms                                                                       | 159 ms: 1.09x faster                                                 |
| xml_etree_process          | 64.4 ms                                                                      | 59.1 ms: 1.09x faster                                                |
| sympy_expand               | 547 ms                                                                       | 504 ms: 1.09x faster                                                 |
| meteor_contest             | 143 ms                                                                       | 132 ms: 1.09x faster                                                 |
| sqlglot_parse              | 1.54 ms                                                                      | 1.42 ms: 1.08x faster                                                |
| sqlglot_transpile          | 1.98 ms                                                                      | 1.84 ms: 1.08x faster                                                |
| 2to3                       | 323 ms                                                                       | 300 ms: 1.07x faster                                                 |
| mdp                        | 2.79 sec                                                                     | 2.61 sec: 1.07x faster                                               |
| sympy_integrate            | 26.0 ms                                                                      | 24.3 ms: 1.07x faster                                                |
| dulwich_log                | 72.9 ms                                                                      | 68.2 ms: 1.07x faster                                                |
| sqlglot_optimize           | 65.7 ms                                                                      | 61.6 ms: 1.07x faster                                                |
| xml_etree_parse            | 153 ms                                                                       | 143 ms: 1.07x faster                                                 |
| create_gc_cycles           | 1.63 ms                                                                      | 1.54 ms: 1.06x faster                                                |
| sqlglot_normalize          | 127 ms                                                                       | 120 ms: 1.06x faster                                                 |
| scimark_lu                 | 109 ms                                                                       | 103 ms: 1.05x faster                                                 |
| pathlib                    | 19.9 ms                                                                      | 18.9 ms: 1.05x faster                                                |
| async_tree_none            | 461 ms                                                                       | 439 ms: 1.05x faster                                                 |
| chameleon                  | 7.96 ms                                                                      | 7.58 ms: 1.05x faster                                                |
| pycparser                  | 1.38 sec                                                                     | 1.32 sec: 1.05x faster                                               |
| logging_simple             | 6.93 us                                                                      | 6.61 us: 1.05x faster                                                |
| async_tree_none_tg         | 467 ms                                                                       | 446 ms: 1.05x faster                                                 |
| async_tree_memoization     | 576 ms                                                                       | 550 ms: 1.05x faster                                                 |
| deepcopy                   | 386 us                                                                       | 369 us: 1.05x faster                                                 |
| telco                      | 8.62 ms                                                                      | 8.29 ms: 1.04x faster                                                |
| tornado_http               | 126 ms                                                                       | 121 ms: 1.04x faster                                                 |
| typing_runtime_protocols   | 135 us                                                                       | 130 us: 1.04x faster                                                 |
| async_tree_cpu_io_mixed    | 726 ms                                                                       | 701 ms: 1.04x faster                                                 |
| docutils                   | 2.97 sec                                                                     | 2.88 sec: 1.03x faster                                               |
| async_tree_cpu_io_mixed_tg | 743 ms                                                                       | 719 ms: 1.03x faster                                                 |
| sqlite_synth               | 2.83 us                                                                      | 2.74 us: 1.03x faster                                                |
| async_tree_io              | 1.12 sec                                                                     | 1.08 sec: 1.03x faster                                               |
| pickle_dict                | 32.6 us                                                                      | 31.6 us: 1.03x faster                                                |
| async_tree_io_tg           | 1.14 sec                                                                     | 1.10 sec: 1.03x faster                                               |
| logging_silent             | 100 ns                                                                       | 97.7 ns: 1.03x faster                                                |
| deepcopy_reduce            | 3.41 us                                                                      | 3.32 us: 1.03x faster                                                |
| bench_thread_pool          | 988 us                                                                       | 966 us: 1.02x faster                                                 |
| pickle_pure_python         | 315 us                                                                       | 308 us: 1.02x faster                                                 |
| scimark_sor                | 151 ms                                                                       | 148 ms: 1.02x faster                                                 |
| dask                       | 411 ms                                                                       | 403 ms: 1.02x faster                                                 |
| unpickle_list              | 4.63 us                                                                      | 4.54 us: 1.02x faster                                                |
| mypy2                      | 387 ms                                                                       | 381 ms: 1.02x faster                                                 |
| logging_format             | 7.57 us                                                                      | 7.46 us: 1.02x faster                                                |
| asyncio_tcp_ssl            | 1.59 sec                                                                     | 1.57 sec: 1.01x faster                                               |
| pidigits                   | 268 ms                                                                       | 265 ms: 1.01x faster                                                 |
| asyncio_tcp                | 372 ms                                                                       | 369 ms: 1.01x faster                                                 |
| async_generators           | 391 ms                                                                       | 388 ms: 1.01x faster                                                 |
| json_dumps                 | 10.9 ms                                                                      | 10.8 ms: 1.01x faster                                                |
| json                       | 5.25 ms                                                                      | 5.23 ms: 1.00x faster                                                |
| python_startup             | 12.9 ms                                                                      | 12.9 ms: 1.00x faster                                                |
| python_startup_no_site     | 11.3 ms                                                                      | 11.3 ms: 1.00x slower                                                |
| unpickle                   | 14.5 us                                                                      | 14.7 us: 1.01x slower                                                |
| coverage                   | 80.7 ms                                                                      | 81.8 ms: 1.01x slower                                                |
| regex_v8                   | 25.2 ms                                                                      | 25.7 ms: 1.02x slower                                                |
| pickle                     | 9.99 us                                                                      | 10.2 us: 1.02x slower                                                |
| regex_effbot               | 3.45 ms                                                                      | 3.53 ms: 1.02x slower                                                |
| regex_dna                  | 238 ms                                                                       | 244 ms: 1.03x slower                                                 |
| coroutines                 | 22.1 ms                                                                      | 22.8 ms: 1.03x slower                                                |
| generators                 | 34.1 ms                                                                      | 35.7 ms: 1.05x slower                                                |
| pickle_list                | 4.19 us                                                                      | 4.48 us: 1.07x slower                                                |
| Geometric mean             | (ref)                                                                        | 1.10x faster                                                         |

Benchmark hidden because not significant (4): bench_mp_pool, async_tree_memoization_tg, asyncio_websockets, json_loads


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.05x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.04x
