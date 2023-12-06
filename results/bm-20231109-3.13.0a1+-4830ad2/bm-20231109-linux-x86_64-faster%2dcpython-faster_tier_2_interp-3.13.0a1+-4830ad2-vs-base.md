
# Results vs. base

- fork: faster-cpython
- ref: faster_tier_2_interp
- machine: linux-x86_64
- commit hash: 4830ad2
- commit date: 2023-11-09
- overall geometric mean: 1.07x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1+-97c4c06 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 263 ms                                                                 | 287 ms: 1.09x slower                                                             |
| chameleon      | 6.97 ms                                                                | 7.53 ms: 1.08x slower                                                            |
| docutils       | 2.60 sec                                                               | 2.71 sec: 1.04x slower                                                           |
| tornado_http   | 95.6 ms                                                                | 99.3 ms: 1.04x slower                                                            |
| Geometric mean | (ref)                                                                  | 1.06x slower                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1+-97c4c06 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_io              | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                                           |
| async_tree_io_tg           | 1.23 sec                                                               | 1.24 sec: 1.01x slower                                                           |
| async_tree_memoization_tg  | 599 ms                                                                 | 609 ms: 1.02x slower                                                             |
| async_tree_none_tg         | 458 ms                                                                 | 467 ms: 1.02x slower                                                             |
| async_tree_memoization     | 568 ms                                                                 | 581 ms: 1.02x slower                                                             |
| async_tree_cpu_io_mixed_tg | 740 ms                                                                 | 759 ms: 1.03x slower                                                             |
| async_tree_cpu_io_mixed    | 713 ms                                                                 | 733 ms: 1.03x slower                                                             |
| async_tree_none            | 440 ms                                                                 | 454 ms: 1.03x slower                                                             |
| Geometric mean             | (ref)                                                                  | 1.02x slower                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1+-97c4c06 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 188 ms: 1.04x faster                                                             |
| float          | 81.4 ms                                                                | 101 ms: 1.24x slower                                                             |
| nbody          | 88.9 ms                                                                | 127 ms: 1.43x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.20x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1+-97c4c06 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_v8       | 25.1 ms                                                                | 24.2 ms: 1.04x faster                                                            |
| regex_dna      | 221 ms                                                                 | 219 ms: 1.01x faster                                                             |
| regex_effbot   | 3.56 ms                                                                | 3.59 ms: 1.01x slower                                                            |
| regex_compile  | 134 ms                                                                 | 158 ms: 1.18x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1+-97c4c06 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpickle_list        | 5.52 us                                                                | 5.34 us: 1.03x faster                                                            |
| xml_etree_parse      | 159 ms                                                                 | 157 ms: 1.01x faster                                                             |
| unpickle             | 14.9 us                                                                | 14.8 us: 1.01x faster                                                            |
| xml_etree_generate   | 87.5 ms                                                                | 87.9 ms: 1.00x slower                                                            |
| xml_etree_process    | 59.8 ms                                                                | 60.2 ms: 1.01x slower                                                            |
| pickle_pure_python   | 303 us                                                                 | 310 us: 1.02x slower                                                             |
| pickle               | 11.4 us                                                                | 11.7 us: 1.03x slower                                                            |
| json_dumps           | 10.4 ms                                                                | 10.8 ms: 1.04x slower                                                            |
| xml_etree_iterparse  | 105 ms                                                                 | 110 ms: 1.05x slower                                                             |
| pickle_list          | 4.78 us                                                                | 5.03 us: 1.05x slower                                                            |
| unpickle_pure_python | 217 us                                                                 | 242 us: 1.11x slower                                                             |
| tomli_loads          | 2.14 sec                                                               | 2.66 sec: 1.24x slower                                                           |
| Geometric mean       | (ref)                                                                  | 1.03x slower                                                                     |

Benchmark hidden because not significant (2): json_loads, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1+-97c4c06 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.3 ms: 1.01x slower                                                            |
| python_startup_no_site | 8.95 ms                                                                | 9.03 ms: 1.01x slower                                                            |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1+-97c4c06 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 11.5 ms                                                                | 14.2 ms: 1.24x slower                                                            |

All benchmarks:
===============

| Benchmark                  | bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1+-97c4c06 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| unpack_sequence            | 48.8 ns                                                                | 45.0 ns: 1.08x faster                                                            |
| regex_v8                   | 25.1 ms                                                                | 24.2 ms: 1.04x faster                                                            |
| pidigits                   | 195 ms                                                                 | 188 ms: 1.04x faster                                                             |
| unpickle_list              | 5.52 us                                                                | 5.34 us: 1.03x faster                                                            |
| coverage                   | 95.4 ms                                                                | 93.7 ms: 1.02x faster                                                            |
| regex_dna                  | 221 ms                                                                 | 219 ms: 1.01x faster                                                             |
| xml_etree_parse            | 159 ms                                                                 | 157 ms: 1.01x faster                                                             |
| unpickle                   | 14.9 us                                                                | 14.8 us: 1.01x faster                                                            |
| gc_traversal               | 3.76 ms                                                                | 3.77 ms: 1.00x slower                                                            |
| create_gc_cycles           | 1.46 ms                                                                | 1.46 ms: 1.00x slower                                                            |
| xml_etree_generate         | 87.5 ms                                                                | 87.9 ms: 1.00x slower                                                            |
| xml_etree_process          | 59.8 ms                                                                | 60.2 ms: 1.01x slower                                                            |
| python_startup             | 10.3 ms                                                                | 10.3 ms: 1.01x slower                                                            |
| async_tree_io              | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                                           |
| regex_effbot               | 3.56 ms                                                                | 3.59 ms: 1.01x slower                                                            |
| python_startup_no_site     | 8.95 ms                                                                | 9.03 ms: 1.01x slower                                                            |
| async_tree_io_tg           | 1.23 sec                                                               | 1.24 sec: 1.01x slower                                                           |
| asyncio_tcp_ssl            | 1.79 sec                                                               | 1.81 sec: 1.01x slower                                                           |
| spectral_norm              | 113 ms                                                                 | 114 ms: 1.01x slower                                                             |
| async_tree_memoization_tg  | 599 ms                                                                 | 609 ms: 1.02x slower                                                             |
| asyncio_tcp                | 485 ms                                                                 | 494 ms: 1.02x slower                                                             |
| async_tree_none_tg         | 458 ms                                                                 | 467 ms: 1.02x slower                                                             |
| logging_silent             | 106 ns                                                                 | 109 ns: 1.02x slower                                                             |
| json                       | 5.11 ms                                                                | 5.22 ms: 1.02x slower                                                            |
| async_tree_memoization     | 568 ms                                                                 | 581 ms: 1.02x slower                                                             |
| pickle_pure_python         | 303 us                                                                 | 310 us: 1.02x slower                                                             |
| async_tree_cpu_io_mixed_tg | 740 ms                                                                 | 759 ms: 1.03x slower                                                             |
| async_generators           | 444 ms                                                                 | 456 ms: 1.03x slower                                                             |
| async_tree_cpu_io_mixed    | 713 ms                                                                 | 733 ms: 1.03x slower                                                             |
| pathlib                    | 19.1 ms                                                                | 19.7 ms: 1.03x slower                                                            |
| async_tree_none            | 440 ms                                                                 | 454 ms: 1.03x slower                                                             |
| deepcopy_reduce            | 3.10 us                                                                | 3.20 us: 1.03x slower                                                            |
| scimark_sor                | 124 ms                                                                 | 128 ms: 1.03x slower                                                             |
| pickle                     | 11.4 us                                                                | 11.7 us: 1.03x slower                                                            |
| sqlglot_optimize           | 53.4 ms                                                                | 55.2 ms: 1.03x slower                                                            |
| json_dumps                 | 10.4 ms                                                                | 10.8 ms: 1.04x slower                                                            |
| mypy2                      | 343 ms                                                                 | 356 ms: 1.04x slower                                                             |
| tornado_http               | 95.6 ms                                                                | 99.3 ms: 1.04x slower                                                            |
| docutils                   | 2.60 sec                                                               | 2.71 sec: 1.04x slower                                                           |
| bench_thread_pool          | 826 us                                                                 | 859 us: 1.04x slower                                                             |
| generators                 | 29.7 ms                                                                | 30.9 ms: 1.04x slower                                                            |
| sqlglot_normalize          | 105 ms                                                                 | 109 ms: 1.04x slower                                                             |
| sqlite_synth               | 2.81 us                                                                | 2.93 us: 1.04x slower                                                            |
| dulwich_log                | 65.8 ms                                                                | 68.8 ms: 1.05x slower                                                            |
| scimark_lu                 | 114 ms                                                                 | 120 ms: 1.05x slower                                                             |
| deepcopy                   | 344 us                                                                 | 360 us: 1.05x slower                                                             |
| mdp                        | 2.74 sec                                                               | 2.87 sec: 1.05x slower                                                           |
| xml_etree_iterparse        | 105 ms                                                                 | 110 ms: 1.05x slower                                                             |
| sympy_sum                  | 147 ms                                                                 | 155 ms: 1.05x slower                                                             |
| pickle_list                | 4.78 us                                                                | 5.03 us: 1.05x slower                                                            |
| sqlglot_transpile          | 1.59 ms                                                                | 1.67 ms: 1.05x slower                                                            |
| telco                      | 8.27 ms                                                                | 8.73 ms: 1.06x slower                                                            |
| sqlglot_parse              | 1.27 ms                                                                | 1.35 ms: 1.06x slower                                                            |
| pycparser                  | 1.17 sec                                                               | 1.25 sec: 1.06x slower                                                           |
| richards_super             | 54.8 ms                                                                | 58.2 ms: 1.06x slower                                                            |
| sympy_expand               | 450 ms                                                                 | 480 ms: 1.07x slower                                                             |
| sympy_str                  | 265 ms                                                                 | 283 ms: 1.07x slower                                                             |
| richards                   | 47.9 ms                                                                | 51.5 ms: 1.07x slower                                                            |
| chameleon                  | 6.97 ms                                                                | 7.53 ms: 1.08x slower                                                            |
| meteor_contest             | 108 ms                                                                 | 117 ms: 1.09x slower                                                             |
| logging_simple             | 5.76 us                                                                | 6.28 us: 1.09x slower                                                            |
| sympy_integrate            | 19.4 ms                                                                | 21.2 ms: 1.09x slower                                                            |
| typing_runtime_protocols   | 115 us                                                                 | 126 us: 1.09x slower                                                             |
| raytrace                   | 278 ms                                                                 | 304 ms: 1.09x slower                                                             |
| 2to3                       | 263 ms                                                                 | 287 ms: 1.09x slower                                                             |
| logging_format             | 6.30 us                                                                | 6.94 us: 1.10x slower                                                            |
| deepcopy_memo              | 38.2 us                                                                | 42.3 us: 1.11x slower                                                            |
| unpickle_pure_python       | 217 us                                                                 | 242 us: 1.11x slower                                                             |
| pprint_safe_repr           | 735 ms                                                                 | 826 ms: 1.12x slower                                                             |
| pprint_pformat             | 1.49 sec                                                               | 1.70 sec: 1.14x slower                                                           |
| go                         | 142 ms                                                                 | 163 ms: 1.14x slower                                                             |
| pyflate                    | 480 ms                                                                 | 549 ms: 1.15x slower                                                             |
| scimark_monte_carlo        | 69.0 ms                                                                | 80.6 ms: 1.17x slower                                                            |
| regex_compile              | 134 ms                                                                 | 158 ms: 1.18x slower                                                             |
| fannkuch                   | 403 ms                                                                 | 477 ms: 1.18x slower                                                             |
| scimark_fft                | 367 ms                                                                 | 447 ms: 1.22x slower                                                             |
| crypto_pyaes               | 71.4 ms                                                                | 87.1 ms: 1.22x slower                                                            |
| chaos                      | 60.6 ms                                                                | 74.0 ms: 1.22x slower                                                            |
| scimark_sparse_mat_mult    | 4.92 ms                                                                | 6.03 ms: 1.22x slower                                                            |
| mako                       | 11.5 ms                                                                | 14.2 ms: 1.24x slower                                                            |
| float                      | 81.4 ms                                                                | 101 ms: 1.24x slower                                                             |
| tomli_loads                | 2.14 sec                                                               | 2.66 sec: 1.24x slower                                                           |
| nqueens                    | 81.0 ms                                                                | 102 ms: 1.25x slower                                                             |
| comprehensions             | 16.1 us                                                                | 22.6 us: 1.40x slower                                                            |
| nbody                      | 88.9 ms                                                                | 127 ms: 1.43x slower                                                             |
| deltablue                  | 3.35 ms                                                                | 4.83 ms: 1.44x slower                                                            |
| hexiom                     | 6.10 ms                                                                | 9.19 ms: 1.51x slower                                                            |
| Geometric mean             | (ref)                                                                  | 1.07x slower                                                                     |

Benchmark hidden because not significant (5): json_loads, bench_mp_pool, asyncio_websockets, pickle_dict, coroutines


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
