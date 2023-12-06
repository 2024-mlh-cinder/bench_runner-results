
# Results vs. base

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: 7736e18
- commit date: 2023-11-02
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1+-7810b69 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 262 ms                                                                 | 279 ms: 1.07x slower                                                             |
| chameleon      | 6.95 ms                                                                | 7.09 ms: 1.02x slower                                                            |
| docutils       | 2.59 sec                                                               | 2.71 sec: 1.05x slower                                                           |
| tornado_http   | 94.9 ms                                                                | 98.0 ms: 1.03x slower                                                            |
| Geometric mean | (ref)                                                                  | 1.04x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1+-7810b69 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|---------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_io_tg          | 1.23 sec                                                               | 1.25 sec: 1.02x slower                                                           |
| async_tree_memoization_tg | 600 ms                                                                 | 612 ms: 1.02x slower                                                             |
| async_tree_io             | 1.19 sec                                                               | 1.21 sec: 1.02x slower                                                           |
| async_tree_memoization    | 566 ms                                                                 | 579 ms: 1.02x slower                                                             |
| async_tree_none_tg        | 458 ms                                                                 | 469 ms: 1.02x slower                                                             |
| async_tree_none           | 438 ms                                                                 | 452 ms: 1.03x slower                                                             |
| Geometric mean            | (ref)                                                                  | 1.02x slower                                                                     |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1+-7810b69 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 196 ms: 1.01x slower                                                             |
| float          | 80.6 ms                                                                | 96.2 ms: 1.19x slower                                                            |
| nbody          | 88.0 ms                                                                | 110 ms: 1.25x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.14x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1+-7810b69 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_dna      | 216 ms                                                                 | 211 ms: 1.02x faster                                                             |
| regex_v8       | 24.4 ms                                                                | 25.7 ms: 1.05x slower                                                            |
| regex_effbot   | 3.43 ms                                                                | 3.73 ms: 1.09x slower                                                            |
| regex_compile  | 134 ms                                                                 | 157 ms: 1.17x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.07x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1+-7810b69 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpickle_list        | 5.23 us                                                                | 5.09 us: 1.03x faster                                                            |
| pickle_dict          | 33.4 us                                                                | 32.7 us: 1.02x faster                                                            |
| xml_etree_parse      | 162 ms                                                                 | 159 ms: 1.02x faster                                                             |
| json_loads           | 27.9 us                                                                | 27.7 us: 1.01x faster                                                            |
| xml_etree_generate   | 85.6 ms                                                                | 87.0 ms: 1.02x slower                                                            |
| json_dumps           | 10.5 ms                                                                | 10.7 ms: 1.02x slower                                                            |
| xml_etree_process    | 58.7 ms                                                                | 59.9 ms: 1.02x slower                                                            |
| pickle_pure_python   | 298 us                                                                 | 310 us: 1.04x slower                                                             |
| pickle_list          | 4.87 us                                                                | 5.10 us: 1.05x slower                                                            |
| xml_etree_iterparse  | 106 ms                                                                 | 111 ms: 1.05x slower                                                             |
| unpickle_pure_python | 216 us                                                                 | 239 us: 1.10x slower                                                             |
| tomli_loads          | 2.14 sec                                                               | 2.49 sec: 1.16x slower                                                           |
| Geometric mean       | (ref)                                                                  | 1.03x slower                                                                     |

Benchmark hidden because not significant (2): pickle, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1+-7810b69 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                                            |
| python_startup_no_site | 8.96 ms                                                                | 9.00 ms: 1.00x slower                                                            |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1+-7810b69 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 11.3 ms                                                                | 14.0 ms: 1.24x slower                                                            |

All benchmarks:
===============

| Benchmark                 | bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1+-7810b69 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|---------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| gc_traversal              | 3.87 ms                                                                | 3.57 ms: 1.08x faster                                                            |
| unpickle_list             | 5.23 us                                                                | 5.09 us: 1.03x faster                                                            |
| pickle_dict               | 33.4 us                                                                | 32.7 us: 1.02x faster                                                            |
| regex_dna                 | 216 ms                                                                 | 211 ms: 1.02x faster                                                             |
| xml_etree_parse           | 162 ms                                                                 | 159 ms: 1.02x faster                                                             |
| coverage                  | 94.8 ms                                                                | 93.5 ms: 1.01x faster                                                            |
| unpack_sequence           | 49.9 ns                                                                | 49.4 ns: 1.01x faster                                                            |
| create_gc_cycles          | 1.48 ms                                                                | 1.47 ms: 1.01x faster                                                            |
| json_loads                | 27.9 us                                                                | 27.7 us: 1.01x faster                                                            |
| generators                | 29.8 ms                                                                | 29.6 ms: 1.01x faster                                                            |
| coroutines                | 22.4 ms                                                                | 22.3 ms: 1.00x faster                                                            |
| python_startup            | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                                            |
| python_startup_no_site    | 8.96 ms                                                                | 9.00 ms: 1.00x slower                                                            |
| pidigits                  | 195 ms                                                                 | 196 ms: 1.01x slower                                                             |
| asyncio_tcp_ssl           | 1.79 sec                                                               | 1.80 sec: 1.01x slower                                                           |
| deepcopy_reduce           | 3.03 us                                                                | 3.05 us: 1.01x slower                                                            |
| scimark_sor               | 130 ms                                                                 | 132 ms: 1.01x slower                                                             |
| logging_simple            | 5.88 us                                                                | 5.94 us: 1.01x slower                                                            |
| logging_format            | 6.37 us                                                                | 6.45 us: 1.01x slower                                                            |
| xml_etree_generate        | 85.6 ms                                                                | 87.0 ms: 1.02x slower                                                            |
| async_tree_io_tg          | 1.23 sec                                                               | 1.25 sec: 1.02x slower                                                           |
| json_dumps                | 10.5 ms                                                                | 10.7 ms: 1.02x slower                                                            |
| sqlite_synth              | 2.82 us                                                                | 2.88 us: 1.02x slower                                                            |
| async_tree_memoization_tg | 600 ms                                                                 | 612 ms: 1.02x slower                                                             |
| xml_etree_process         | 58.7 ms                                                                | 59.9 ms: 1.02x slower                                                            |
| chameleon                 | 6.95 ms                                                                | 7.09 ms: 1.02x slower                                                            |
| sqlglot_normalize         | 105 ms                                                                 | 107 ms: 1.02x slower                                                             |
| pathlib                   | 19.3 ms                                                                | 19.7 ms: 1.02x slower                                                            |
| async_tree_io             | 1.19 sec                                                               | 1.21 sec: 1.02x slower                                                           |
| asyncio_tcp               | 482 ms                                                                 | 493 ms: 1.02x slower                                                             |
| async_tree_memoization    | 566 ms                                                                 | 579 ms: 1.02x slower                                                             |
| async_tree_none_tg        | 458 ms                                                                 | 469 ms: 1.02x slower                                                             |
| spectral_norm             | 109 ms                                                                 | 112 ms: 1.03x slower                                                             |
| sqlglot_optimize          | 53.0 ms                                                                | 54.5 ms: 1.03x slower                                                            |
| dulwich_log               | 65.2 ms                                                                | 67.2 ms: 1.03x slower                                                            |
| deepcopy                  | 343 us                                                                 | 353 us: 1.03x slower                                                             |
| async_generators          | 442 ms                                                                 | 455 ms: 1.03x slower                                                             |
| async_tree_none           | 438 ms                                                                 | 452 ms: 1.03x slower                                                             |
| tornado_http              | 94.9 ms                                                                | 98.0 ms: 1.03x slower                                                            |
| bench_thread_pool         | 809 us                                                                 | 835 us: 1.03x slower                                                             |
| logging_silent            | 104 ns                                                                 | 108 ns: 1.03x slower                                                             |
| mdp                       | 2.73 sec                                                               | 2.84 sec: 1.04x slower                                                           |
| pickle_pure_python        | 298 us                                                                 | 310 us: 1.04x slower                                                             |
| mypy2                     | 340 ms                                                                 | 354 ms: 1.04x slower                                                             |
| scimark_lu                | 114 ms                                                                 | 119 ms: 1.04x slower                                                             |
| meteor_contest            | 110 ms                                                                 | 115 ms: 1.05x slower                                                             |
| docutils                  | 2.59 sec                                                               | 2.71 sec: 1.05x slower                                                           |
| pickle_list               | 4.87 us                                                                | 5.10 us: 1.05x slower                                                            |
| xml_etree_iterparse       | 106 ms                                                                 | 111 ms: 1.05x slower                                                             |
| fannkuch                  | 401 ms                                                                 | 420 ms: 1.05x slower                                                             |
| sympy_sum                 | 146 ms                                                                 | 153 ms: 1.05x slower                                                             |
| richards                  | 48.0 ms                                                                | 50.4 ms: 1.05x slower                                                            |
| regex_v8                  | 24.4 ms                                                                | 25.7 ms: 1.05x slower                                                            |
| pycparser                 | 1.16 sec                                                               | 1.22 sec: 1.05x slower                                                           |
| richards_super            | 54.3 ms                                                                | 57.6 ms: 1.06x slower                                                            |
| sympy_str                 | 265 ms                                                                 | 281 ms: 1.06x slower                                                             |
| sympy_expand              | 448 ms                                                                 | 476 ms: 1.06x slower                                                             |
| sqlglot_transpile         | 1.58 ms                                                                | 1.67 ms: 1.06x slower                                                            |
| sqlglot_parse             | 1.26 ms                                                                | 1.34 ms: 1.06x slower                                                            |
| raytrace                  | 271 ms                                                                 | 289 ms: 1.07x slower                                                             |
| 2to3                      | 262 ms                                                                 | 279 ms: 1.07x slower                                                             |
| crypto_pyaes              | 70.7 ms                                                                | 75.5 ms: 1.07x slower                                                            |
| pyflate                   | 476 ms                                                                 | 514 ms: 1.08x slower                                                             |
| sympy_integrate           | 19.3 ms                                                                | 21.0 ms: 1.09x slower                                                            |
| regex_effbot              | 3.43 ms                                                                | 3.73 ms: 1.09x slower                                                            |
| scimark_monte_carlo       | 66.9 ms                                                                | 72.9 ms: 1.09x slower                                                            |
| typing_runtime_protocols  | 113 us                                                                 | 125 us: 1.10x slower                                                             |
| unpickle_pure_python      | 216 us                                                                 | 239 us: 1.10x slower                                                             |
| pprint_safe_repr          | 727 ms                                                                 | 804 ms: 1.11x slower                                                             |
| scimark_fft               | 359 ms                                                                 | 398 ms: 1.11x slower                                                             |
| go                        | 143 ms                                                                 | 159 ms: 1.11x slower                                                             |
| deepcopy_memo             | 37.1 us                                                                | 41.4 us: 1.12x slower                                                            |
| pprint_pformat            | 1.50 sec                                                               | 1.67 sec: 1.12x slower                                                           |
| chaos                     | 60.5 ms                                                                | 68.2 ms: 1.13x slower                                                            |
| scimark_sparse_mat_mult   | 4.85 ms                                                                | 5.51 ms: 1.14x slower                                                            |
| tomli_loads               | 2.14 sec                                                               | 2.49 sec: 1.16x slower                                                           |
| regex_compile             | 134 ms                                                                 | 157 ms: 1.17x slower                                                             |
| float                     | 80.6 ms                                                                | 96.2 ms: 1.19x slower                                                            |
| nqueens                   | 79.2 ms                                                                | 95.9 ms: 1.21x slower                                                            |
| mako                      | 11.3 ms                                                                | 14.0 ms: 1.24x slower                                                            |
| nbody                     | 88.0 ms                                                                | 110 ms: 1.25x slower                                                             |
| comprehensions            | 16.4 us                                                                | 22.2 us: 1.35x slower                                                            |
| deltablue                 | 3.31 ms                                                                | 4.58 ms: 1.38x slower                                                            |
| hexiom                    | 6.10 ms                                                                | 8.74 ms: 1.43x slower                                                            |
| Geometric mean            | (ref)                                                                  | 1.05x slower                                                                     |

Benchmark hidden because not significant (8): telco, pickle, bench_mp_pool, asyncio_websockets, async_tree_cpu_io_mixed_tg, unpickle, json, async_tree_cpu_io_mixed


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
