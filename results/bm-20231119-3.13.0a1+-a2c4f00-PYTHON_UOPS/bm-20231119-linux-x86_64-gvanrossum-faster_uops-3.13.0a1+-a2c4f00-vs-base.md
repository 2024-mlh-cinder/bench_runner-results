
# Results vs. base

- fork: gvanrossum
- ref: faster_uops
- machine: linux-x86_64
- commit hash: a2c4f00
- commit date: 2023-11-19
- overall geometric mean: 1.01x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 289 ms                                                                 | 290 ms: 1.00x slower                                              |
| docutils       | 2.70 sec                                                               | 2.73 sec: 1.01x slower                                            |
| tornado_http   | 99.6 ms                                                                | 103 ms: 1.03x slower                                              |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| async_tree_io    | 1.23 sec                                                               | 1.22 sec: 1.00x faster                                            |
| async_tree_io_tg | 1.26 sec                                                               | 1.26 sec: 1.00x slower                                            |
| Geometric mean   | (ref)                                                                  | 1.00x faster                                                      |

Benchmark hidden because not significant (6): async_tree_memoization, async_tree_none, async_tree_memoization_tg, async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 196 ms                                                                 | 190 ms: 1.03x faster                                              |
| nbody          | 131 ms                                                                 | 138 ms: 1.06x slower                                              |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.59 ms                                                                | 3.52 ms: 1.02x faster                                             |
| regex_compile  | 160 ms                                                                 | 161 ms: 1.00x slower                                              |
| regex_dna      | 221 ms                                                                 | 222 ms: 1.01x slower                                              |
| regex_v8       | 24.3 ms                                                                | 24.9 ms: 1.02x slower                                             |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| unpickle_list        | 5.10 us                                                                | 5.03 us: 1.01x faster                                             |
| pickle_pure_python   | 307 us                                                                 | 308 us: 1.00x slower                                              |
| xml_etree_parse      | 158 ms                                                                 | 159 ms: 1.00x slower                                              |
| pickle_list          | 5.05 us                                                                | 5.11 us: 1.01x slower                                             |
| unpickle_pure_python | 242 us                                                                 | 245 us: 1.01x slower                                              |
| xml_etree_iterparse  | 111 ms                                                                 | 114 ms: 1.03x slower                                              |
| pickle               | 11.3 us                                                                | 11.6 us: 1.03x slower                                             |
| xml_etree_generate   | 88.7 ms                                                                | 91.3 ms: 1.03x slower                                             |
| xml_etree_process    | 60.5 ms                                                                | 62.9 ms: 1.04x slower                                             |
| Geometric mean       | (ref)                                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (5): json_loads, json_dumps, tomli_loads, pickle_dict, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                             |
| python_startup_no_site | 9.01 ms                                                                | 9.10 ms: 1.01x slower                                             |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|-----------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 15.6 ms                                                                | 15.1 ms: 1.04x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|--------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| gc_traversal             | 4.16 ms                                                                | 3.65 ms: 1.14x faster                                             |
| unpack_sequence          | 56.4 ns                                                                | 52.6 ns: 1.07x faster                                             |
| mako                     | 15.6 ms                                                                | 15.1 ms: 1.04x faster                                             |
| nqueens                  | 102 ms                                                                 | 98.3 ms: 1.03x faster                                             |
| pidigits                 | 196 ms                                                                 | 190 ms: 1.03x faster                                              |
| hexiom                   | 9.38 ms                                                                | 9.16 ms: 1.02x faster                                             |
| fannkuch                 | 473 ms                                                                 | 463 ms: 1.02x faster                                              |
| generators               | 30.4 ms                                                                | 29.8 ms: 1.02x faster                                             |
| typing_runtime_protocols | 128 us                                                                 | 126 us: 1.02x faster                                              |
| regex_effbot             | 3.59 ms                                                                | 3.52 ms: 1.02x faster                                             |
| comprehensions           | 23.7 us                                                                | 23.3 us: 1.02x faster                                             |
| telco                    | 8.83 ms                                                                | 8.70 ms: 1.02x faster                                             |
| unpickle_list            | 5.10 us                                                                | 5.03 us: 1.01x faster                                             |
| go                       | 166 ms                                                                 | 164 ms: 1.01x faster                                              |
| deepcopy_reduce          | 3.17 us                                                                | 3.14 us: 1.01x faster                                             |
| chaos                    | 78.6 ms                                                                | 78.0 ms: 1.01x faster                                             |
| coroutines               | 22.4 ms                                                                | 22.3 ms: 1.01x faster                                             |
| async_tree_io            | 1.23 sec                                                               | 1.22 sec: 1.00x faster                                            |
| meteor_contest           | 117 ms                                                                 | 117 ms: 1.00x slower                                              |
| async_tree_io_tg         | 1.26 sec                                                               | 1.26 sec: 1.00x slower                                            |
| create_gc_cycles         | 1.46 ms                                                                | 1.46 ms: 1.00x slower                                             |
| 2to3                     | 289 ms                                                                 | 290 ms: 1.00x slower                                              |
| pickle_pure_python       | 307 us                                                                 | 308 us: 1.00x slower                                              |
| regex_compile            | 160 ms                                                                 | 161 ms: 1.00x slower                                              |
| xml_etree_parse          | 158 ms                                                                 | 159 ms: 1.00x slower                                              |
| asyncio_tcp              | 496 ms                                                                 | 499 ms: 1.01x slower                                              |
| regex_dna                | 221 ms                                                                 | 222 ms: 1.01x slower                                              |
| scimark_lu               | 120 ms                                                                 | 121 ms: 1.01x slower                                              |
| mypy2                    | 354 ms                                                                 | 358 ms: 1.01x slower                                              |
| richards                 | 50.5 ms                                                                | 51.0 ms: 1.01x slower                                             |
| dask                     | 367 ms                                                                 | 371 ms: 1.01x slower                                              |
| python_startup           | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                             |
| docutils                 | 2.70 sec                                                               | 2.73 sec: 1.01x slower                                            |
| python_startup_no_site   | 9.01 ms                                                                | 9.10 ms: 1.01x slower                                             |
| crypto_pyaes             | 86.9 ms                                                                | 87.8 ms: 1.01x slower                                             |
| bench_thread_pool        | 852 us                                                                 | 861 us: 1.01x slower                                              |
| pickle_list              | 5.05 us                                                                | 5.11 us: 1.01x slower                                             |
| logging_silent           | 110 ns                                                                 | 111 ns: 1.01x slower                                              |
| sqlite_synth             | 2.88 us                                                                | 2.92 us: 1.01x slower                                             |
| unpickle_pure_python     | 242 us                                                                 | 245 us: 1.01x slower                                              |
| pyflate                  | 538 ms                                                                 | 546 ms: 1.02x slower                                              |
| coverage                 | 93.7 ms                                                                | 95.2 ms: 1.02x slower                                             |
| pycparser                | 1.20 sec                                                               | 1.22 sec: 1.02x slower                                            |
| deepcopy                 | 357 us                                                                 | 363 us: 1.02x slower                                              |
| raytrace                 | 311 ms                                                                 | 317 ms: 1.02x slower                                              |
| logging_simple           | 6.10 us                                                                | 6.21 us: 1.02x slower                                             |
| dulwich_log              | 68.5 ms                                                                | 69.9 ms: 1.02x slower                                             |
| sympy_integrate          | 21.3 ms                                                                | 21.7 ms: 1.02x slower                                             |
| richards_super           | 57.0 ms                                                                | 58.3 ms: 1.02x slower                                             |
| logging_format           | 6.82 us                                                                | 6.98 us: 1.02x slower                                             |
| regex_v8                 | 24.3 ms                                                                | 24.9 ms: 1.02x slower                                             |
| scimark_fft              | 476 ms                                                                 | 488 ms: 1.03x slower                                              |
| xml_etree_iterparse      | 111 ms                                                                 | 114 ms: 1.03x slower                                              |
| pickle                   | 11.3 us                                                                | 11.6 us: 1.03x slower                                             |
| xml_etree_generate       | 88.7 ms                                                                | 91.3 ms: 1.03x slower                                             |
| pprint_pformat           | 1.73 sec                                                               | 1.78 sec: 1.03x slower                                            |
| tornado_http             | 99.6 ms                                                                | 103 ms: 1.03x slower                                              |
| pprint_safe_repr         | 825 ms                                                                 | 853 ms: 1.03x slower                                              |
| sqlglot_transpile        | 1.67 ms                                                                | 1.72 ms: 1.03x slower                                             |
| sqlglot_parse            | 1.34 ms                                                                | 1.39 ms: 1.04x slower                                             |
| xml_etree_process        | 60.5 ms                                                                | 62.9 ms: 1.04x slower                                             |
| sympy_expand             | 476 ms                                                                 | 496 ms: 1.04x slower                                              |
| scimark_monte_carlo      | 84.7 ms                                                                | 88.6 ms: 1.05x slower                                             |
| mdp                      | 2.69 sec                                                               | 2.82 sec: 1.05x slower                                            |
| sympy_sum                | 154 ms                                                                 | 163 ms: 1.06x slower                                              |
| sympy_str                | 283 ms                                                                 | 300 ms: 1.06x slower                                              |
| nbody                    | 131 ms                                                                 | 138 ms: 1.06x slower                                              |
| sqlglot_optimize         | 54.7 ms                                                                | 59.5 ms: 1.09x slower                                             |
| sqlglot_normalize        | 108 ms                                                                 | 117 ms: 1.09x slower                                              |
| spectral_norm            | 114 ms                                                                 | 149 ms: 1.31x slower                                              |
| Geometric mean           | (ref)                                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (23): async_tree_memoization, json_loads, async_tree_none, scimark_sor, json_dumps, float, tomli_loads, deltablue, pathlib, async_tree_memoization_tg, deepcopy_memo, async_generators, pickle_dict, async_tree_none_tg, bench_mp_pool, asyncio_tcp_ssl, async_tree_cpu_io_mixed, asyncio_websockets, async_tree_cpu_io_mixed_tg, chameleon, json, scimark_sparse_mat_mult, unpickle


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
