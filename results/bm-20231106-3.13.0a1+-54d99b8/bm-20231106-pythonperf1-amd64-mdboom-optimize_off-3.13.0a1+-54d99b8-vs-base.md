
# Results vs. base

- fork: mdboom
- ref: optimize_off
- machine: windows-amd64
- commit hash: 54d99b8
- commit date: 2023-11-06
- overall geometric mean: 1.06x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 222 ms                                                                      | 208 ms: 1.07x faster                                                |
| chameleon      | 5.37 ms                                                                     | 4.90 ms: 1.10x faster                                               |
| docutils       | 1.65 sec                                                                    | 1.55 sec: 1.06x faster                                              |
| tornado_http   | 89.9 ms                                                                     | 86.8 ms: 1.04x faster                                               |
| Geometric mean | (ref)                                                                       | 1.07x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_memoization     | 360 ms                                                                      | 339 ms: 1.06x faster                                                |
| async_tree_none            | 281 ms                                                                      | 265 ms: 1.06x faster                                                |
| async_tree_cpu_io_mixed    | 474 ms                                                                      | 451 ms: 1.05x faster                                                |
| async_tree_io              | 755 ms                                                                      | 723 ms: 1.04x faster                                                |
| async_tree_memoization_tg  | 378 ms                                                                      | 363 ms: 1.04x faster                                                |
| async_tree_none_tg         | 293 ms                                                                      | 282 ms: 1.04x faster                                                |
| async_tree_cpu_io_mixed_tg | 493 ms                                                                      | 479 ms: 1.03x faster                                                |
| async_tree_io_tg           | 781 ms                                                                      | 762 ms: 1.03x faster                                                |
| Geometric mean             | (ref)                                                                       | 1.04x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 54.4 ms                                                                     | 52.2 ms: 1.04x faster                                               |
| nbody          | 74.6 ms                                                                     | 72.6 ms: 1.03x faster                                               |
| Geometric mean | (ref)                                                                       | 1.02x faster                                                        |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 92.6 ms                                                                     | 79.2 ms: 1.17x faster                                               |
| regex_v8       | 15.5 ms                                                                     | 14.9 ms: 1.04x faster                                               |
| regex_effbot   | 1.61 ms                                                                     | 1.57 ms: 1.03x faster                                               |
| regex_dna      | 121 ms                                                                      | 119 ms: 1.02x faster                                                |
| Geometric mean | (ref)                                                                       | 1.06x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 200 us                                                                      | 181 us: 1.10x faster                                                |
| tomli_loads          | 1.55 sec                                                                    | 1.41 sec: 1.10x faster                                              |
| unpickle_pure_python | 139 us                                                                      | 130 us: 1.07x faster                                                |
| xml_etree_process    | 39.4 ms                                                                     | 37.6 ms: 1.05x faster                                               |
| json_dumps           | 5.84 ms                                                                     | 5.63 ms: 1.04x faster                                               |
| xml_etree_generate   | 56.4 ms                                                                     | 55.3 ms: 1.02x faster                                               |
| unpickle             | 8.17 us                                                                     | 8.02 us: 1.02x faster                                               |
| xml_etree_iterparse  | 64.3 ms                                                                     | 63.3 ms: 1.02x faster                                               |
| json_loads           | 13.8 us                                                                     | 13.6 us: 1.01x faster                                               |
| unpickle_list        | 2.68 us                                                                     | 2.70 us: 1.01x slower                                               |
| pickle_list          | 2.80 us                                                                     | 2.88 us: 1.03x slower                                               |
| pickle               | 6.91 us                                                                     | 7.18 us: 1.04x slower                                               |
| pickle_dict          | 18.1 us                                                                     | 19.8 us: 1.09x slower                                               |
| Geometric mean       | (ref)                                                                       | 1.02x faster                                                        |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 18.0 ms                                                                     | 17.6 ms: 1.03x faster                                               |
| python_startup         | 20.0 ms                                                                     | 19.6 ms: 1.02x faster                                               |
| Geometric mean         | (ref)                                                                       | 1.02x faster                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|-----------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.14 ms                                                                     | 6.56 ms: 1.09x faster                                               |

All benchmarks:
===============

| Benchmark                  | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1+-54d99b8 |
|----------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 97.6 us                                                                     | 76.3 us: 1.28x faster                                               |
| regex_compile              | 92.6 ms                                                                     | 79.2 ms: 1.17x faster                                               |
| deepcopy                   | 255 us                                                                      | 220 us: 1.16x faster                                                |
| deepcopy_reduce            | 2.24 us                                                                     | 1.96 us: 1.14x faster                                               |
| chaos                      | 45.0 ms                                                                     | 39.5 ms: 1.14x faster                                               |
| sqlglot_parse              | 861 us                                                                      | 758 us: 1.14x faster                                                |
| go                         | 98.2 ms                                                                     | 86.5 ms: 1.13x faster                                               |
| logging_silent             | 62.6 ns                                                                     | 55.5 ns: 1.13x faster                                               |
| hexiom                     | 4.27 ms                                                                     | 3.79 ms: 1.13x faster                                               |
| logging_simple             | 6.89 us                                                                     | 6.13 us: 1.12x faster                                               |
| raytrace                   | 182 ms                                                                      | 162 ms: 1.12x faster                                                |
| dulwich_log                | 45.2 ms                                                                     | 40.4 ms: 1.12x faster                                               |
| logging_format             | 7.38 us                                                                     | 6.61 us: 1.12x faster                                               |
| sqlglot_normalize          | 194 ms                                                                      | 174 ms: 1.11x faster                                                |
| pprint_safe_repr           | 546 ms                                                                      | 490 ms: 1.11x faster                                                |
| sqlglot_transpile          | 1.09 ms                                                                     | 977 us: 1.11x faster                                                |
| pycparser                  | 852 ms                                                                      | 769 ms: 1.11x faster                                                |
| pprint_pformat             | 1.12 sec                                                                    | 1.01 sec: 1.11x faster                                              |
| pickle_pure_python         | 200 us                                                                      | 181 us: 1.10x faster                                                |
| tomli_loads                | 1.55 sec                                                                    | 1.41 sec: 1.10x faster                                              |
| sqlglot_optimize           | 36.3 ms                                                                     | 33.1 ms: 1.10x faster                                               |
| deltablue                  | 2.23 ms                                                                     | 2.03 ms: 1.10x faster                                               |
| chameleon                  | 5.37 ms                                                                     | 4.90 ms: 1.10x faster                                               |
| sympy_expand               | 296 ms                                                                      | 270 ms: 1.10x faster                                                |
| richards_super             | 33.4 ms                                                                     | 30.5 ms: 1.10x faster                                               |
| sympy_str                  | 173 ms                                                                      | 158 ms: 1.09x faster                                                |
| mako                       | 7.14 ms                                                                     | 6.56 ms: 1.09x faster                                               |
| nqueens                    | 62.5 ms                                                                     | 57.5 ms: 1.09x faster                                               |
| richards                   | 29.8 ms                                                                     | 27.5 ms: 1.08x faster                                               |
| mypy2                      | 218 ms                                                                      | 203 ms: 1.07x faster                                                |
| sympy_sum                  | 88.3 ms                                                                     | 82.5 ms: 1.07x faster                                               |
| deepcopy_memo              | 25.4 us                                                                     | 23.7 us: 1.07x faster                                               |
| unpack_sequence            | 39.9 ns                                                                     | 37.3 ns: 1.07x faster                                               |
| unpickle_pure_python       | 139 us                                                                      | 130 us: 1.07x faster                                                |
| 2to3                       | 222 ms                                                                      | 208 ms: 1.07x faster                                                |
| coroutines                 | 14.6 ms                                                                     | 13.7 ms: 1.06x faster                                               |
| sympy_integrate            | 13.1 ms                                                                     | 12.3 ms: 1.06x faster                                               |
| async_tree_memoization     | 360 ms                                                                      | 339 ms: 1.06x faster                                                |
| scimark_fft                | 188 ms                                                                      | 177 ms: 1.06x faster                                                |
| docutils                   | 1.65 sec                                                                    | 1.55 sec: 1.06x faster                                              |
| async_tree_none            | 281 ms                                                                      | 265 ms: 1.06x faster                                                |
| scimark_sparse_mat_mult    | 2.50 ms                                                                     | 2.37 ms: 1.05x faster                                               |
| pyflate                    | 306 ms                                                                      | 290 ms: 1.05x faster                                                |
| async_tree_cpu_io_mixed    | 474 ms                                                                      | 451 ms: 1.05x faster                                                |
| generators                 | 22.7 ms                                                                     | 21.7 ms: 1.05x faster                                               |
| xml_etree_process          | 39.4 ms                                                                     | 37.6 ms: 1.05x faster                                               |
| asyncio_tcp_ssl            | 1.96 sec                                                                    | 1.87 sec: 1.05x faster                                              |
| async_generators           | 237 ms                                                                      | 226 ms: 1.05x faster                                                |
| comprehensions             | 11.2 us                                                                     | 10.7 us: 1.04x faster                                               |
| async_tree_io              | 755 ms                                                                      | 723 ms: 1.04x faster                                                |
| float                      | 54.4 ms                                                                     | 52.2 ms: 1.04x faster                                               |
| async_tree_memoization_tg  | 378 ms                                                                      | 363 ms: 1.04x faster                                                |
| meteor_contest             | 75.9 ms                                                                     | 72.9 ms: 1.04x faster                                               |
| async_tree_none_tg         | 293 ms                                                                      | 282 ms: 1.04x faster                                                |
| regex_v8                   | 15.5 ms                                                                     | 14.9 ms: 1.04x faster                                               |
| json_dumps                 | 5.84 ms                                                                     | 5.63 ms: 1.04x faster                                               |
| crypto_pyaes               | 45.3 ms                                                                     | 43.7 ms: 1.04x faster                                               |
| tornado_http               | 89.9 ms                                                                     | 86.8 ms: 1.04x faster                                               |
| async_tree_cpu_io_mixed_tg | 493 ms                                                                      | 479 ms: 1.03x faster                                                |
| nbody                      | 74.6 ms                                                                     | 72.6 ms: 1.03x faster                                               |
| regex_effbot               | 1.61 ms                                                                     | 1.57 ms: 1.03x faster                                               |
| scimark_lu                 | 60.3 ms                                                                     | 58.8 ms: 1.03x faster                                               |
| python_startup_no_site     | 18.0 ms                                                                     | 17.6 ms: 1.03x faster                                               |
| async_tree_io_tg           | 781 ms                                                                      | 762 ms: 1.03x faster                                                |
| xml_etree_generate         | 56.4 ms                                                                     | 55.3 ms: 1.02x faster                                               |
| regex_dna                  | 121 ms                                                                      | 119 ms: 1.02x faster                                                |
| telco                      | 4.85 ms                                                                     | 4.76 ms: 1.02x faster                                               |
| scimark_sor                | 81.9 ms                                                                     | 80.3 ms: 1.02x faster                                               |
| unpickle                   | 8.17 us                                                                     | 8.02 us: 1.02x faster                                               |
| python_startup             | 20.0 ms                                                                     | 19.6 ms: 1.02x faster                                               |
| xml_etree_iterparse        | 64.3 ms                                                                     | 63.3 ms: 1.02x faster                                               |
| spectral_norm              | 63.7 ms                                                                     | 62.7 ms: 1.02x faster                                               |
| scimark_monte_carlo        | 42.8 ms                                                                     | 42.2 ms: 1.01x faster                                               |
| json_loads                 | 13.8 us                                                                     | 13.6 us: 1.01x faster                                               |
| pathlib                    | 79.7 ms                                                                     | 78.9 ms: 1.01x faster                                               |
| bench_mp_pool              | 62.9 ms                                                                     | 62.6 ms: 1.01x faster                                               |
| sqlite_synth               | 1.56 us                                                                     | 1.56 us: 1.00x slower                                               |
| unpickle_list              | 2.68 us                                                                     | 2.70 us: 1.01x slower                                               |
| fannkuch                   | 249 ms                                                                      | 252 ms: 1.01x slower                                                |
| mdp                        | 1.42 sec                                                                    | 1.44 sec: 1.01x slower                                              |
| pickle_list                | 2.80 us                                                                     | 2.88 us: 1.03x slower                                               |
| pickle                     | 6.91 us                                                                     | 7.18 us: 1.04x slower                                               |
| pickle_dict                | 18.1 us                                                                     | 19.8 us: 1.09x slower                                               |
| Geometric mean             | (ref)                                                                       | 1.06x faster                                                        |

Benchmark hidden because not significant (8): bench_thread_pool, create_gc_cycles, json, xml_etree_parse, asyncio_tcp, coverage, gc_traversal, pidigits


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
