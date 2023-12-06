
# Results vs. base

- fork: mdboom
- ref: globally_set_Os
- machine: windows-amd64
- commit hash: 04300ec
- commit date: 2023-11-20
- overall geometric mean: 1.00x slower
- HPT reliability: 89.58%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| chameleon      | 4.78 ms                                                                     | 4.91 ms: 1.03x slower                                                  |
| docutils       | 1.54 sec                                                                    | 1.55 sec: 1.01x slower                                                 |
| tornado_http   | 86.8 ms                                                                     | 96.1 ms: 1.11x slower                                                  |
| Geometric mean | (ref)                                                                       | 1.04x slower                                                           |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_memoization     | 338 ms                                                                      | 344 ms: 1.02x slower                                                   |
| async_tree_memoization_tg  | 358 ms                                                                      | 367 ms: 1.02x slower                                                   |
| async_tree_cpu_io_mixed_tg | 478 ms                                                                      | 496 ms: 1.04x slower                                                   |
| async_tree_cpu_io_mixed    | 453 ms                                                                      | 471 ms: 1.04x slower                                                   |
| async_tree_none            | 265 ms                                                                      | 279 ms: 1.05x slower                                                   |
| Geometric mean             | (ref)                                                                       | 1.02x slower                                                           |

Benchmark hidden because not significant (3): async_tree_none_tg, async_tree_io, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 51.8 ms                                                                     | 51.2 ms: 1.01x faster                                                  |
| nbody          | 74.6 ms                                                                     | 73.6 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                           |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 80.5 ms                                                                     | 78.9 ms: 1.02x faster                                                  |
| regex_v8       | 14.9 ms                                                                     | 15.2 ms: 1.02x slower                                                  |
| regex_dna      | 118 ms                                                                      | 121 ms: 1.02x slower                                                   |
| regex_effbot   | 1.58 ms                                                                     | 1.62 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_dict          | 19.2 us                                                                     | 17.4 us: 1.11x faster                                                  |
| pickle_list          | 2.87 us                                                                     | 2.63 us: 1.09x faster                                                  |
| pickle               | 7.02 us                                                                     | 6.81 us: 1.03x faster                                                  |
| xml_etree_generate   | 54.8 ms                                                                     | 53.4 ms: 1.03x faster                                                  |
| xml_etree_process    | 37.7 ms                                                                     | 36.9 ms: 1.02x faster                                                  |
| unpickle_pure_python | 133 us                                                                      | 131 us: 1.02x faster                                                   |
| xml_etree_iterparse  | 63.6 ms                                                                     | 63.0 ms: 1.01x faster                                                  |
| tomli_loads          | 1.43 sec                                                                    | 1.44 sec: 1.01x slower                                                 |
| unpickle             | 7.99 us                                                                     | 8.34 us: 1.04x slower                                                  |
| Geometric mean       | (ref)                                                                       | 1.02x faster                                                           |

Benchmark hidden because not significant (5): unpickle_list, json_dumps, pickle_pure_python, json_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 17.7 ms                                                                     | 17.9 ms: 1.01x slower                                                  |
| python_startup         | 19.5 ms                                                                     | 20.0 ms: 1.03x slower                                                  |
| Geometric mean         | (ref)                                                                       | 1.02x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|-----------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 6.49 ms                                                                     | 6.43 ms: 1.01x faster                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-globally_set_Os-3.13.0a1+-04300ec |
|----------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpack_sequence            | 50.7 ns                                                                     | 40.0 ns: 1.27x faster                                                  |
| pickle_dict                | 19.2 us                                                                     | 17.4 us: 1.11x faster                                                  |
| pickle_list                | 2.87 us                                                                     | 2.63 us: 1.09x faster                                                  |
| deltablue                  | 2.13 ms                                                                     | 2.01 ms: 1.06x faster                                                  |
| richards                   | 28.7 ms                                                                     | 27.2 ms: 1.06x faster                                                  |
| raytrace                   | 167 ms                                                                      | 161 ms: 1.04x faster                                                   |
| crypto_pyaes               | 44.0 ms                                                                     | 42.6 ms: 1.03x faster                                                  |
| coroutines                 | 13.8 ms                                                                     | 13.3 ms: 1.03x faster                                                  |
| pickle                     | 7.02 us                                                                     | 6.81 us: 1.03x faster                                                  |
| logging_format             | 6.68 us                                                                     | 6.48 us: 1.03x faster                                                  |
| richards_super             | 31.3 ms                                                                     | 30.4 ms: 1.03x faster                                                  |
| pyflate                    | 298 ms                                                                      | 289 ms: 1.03x faster                                                   |
| xml_etree_generate         | 54.8 ms                                                                     | 53.4 ms: 1.03x faster                                                  |
| logging_simple             | 6.21 us                                                                     | 6.06 us: 1.02x faster                                                  |
| xml_etree_process          | 37.7 ms                                                                     | 36.9 ms: 1.02x faster                                                  |
| unpickle_pure_python       | 133 us                                                                      | 131 us: 1.02x faster                                                   |
| regex_compile              | 80.5 ms                                                                     | 78.9 ms: 1.02x faster                                                  |
| deepcopy_memo              | 23.9 us                                                                     | 23.5 us: 1.02x faster                                                  |
| chaos                      | 40.1 ms                                                                     | 39.4 ms: 1.02x faster                                                  |
| comprehensions             | 10.6 us                                                                     | 10.4 us: 1.02x faster                                                  |
| pprint_safe_repr           | 510 ms                                                                      | 502 ms: 1.02x faster                                                   |
| float                      | 51.8 ms                                                                     | 51.2 ms: 1.01x faster                                                  |
| nbody                      | 74.6 ms                                                                     | 73.6 ms: 1.01x faster                                                  |
| hexiom                     | 3.88 ms                                                                     | 3.83 ms: 1.01x faster                                                  |
| mako                       | 6.49 ms                                                                     | 6.43 ms: 1.01x faster                                                  |
| meteor_contest             | 74.2 ms                                                                     | 73.5 ms: 1.01x faster                                                  |
| sqlglot_parse              | 766 us                                                                      | 759 us: 1.01x faster                                                   |
| go                         | 88.0 ms                                                                     | 87.2 ms: 1.01x faster                                                  |
| xml_etree_iterparse        | 63.6 ms                                                                     | 63.0 ms: 1.01x faster                                                  |
| sqlglot_transpile          | 986 us                                                                      | 980 us: 1.01x faster                                                   |
| sympy_expand               | 274 ms                                                                      | 273 ms: 1.01x faster                                                   |
| logging_silent             | 55.7 ns                                                                     | 55.4 ns: 1.00x faster                                                  |
| sympy_sum                  | 83.1 ms                                                                     | 82.7 ms: 1.00x faster                                                  |
| sympy_str                  | 159 ms                                                                      | 158 ms: 1.00x faster                                                   |
| tomli_loads                | 1.43 sec                                                                    | 1.44 sec: 1.01x slower                                                 |
| docutils                   | 1.54 sec                                                                    | 1.55 sec: 1.01x slower                                                 |
| create_gc_cycles           | 741 us                                                                      | 749 us: 1.01x slower                                                   |
| async_generators           | 229 ms                                                                      | 232 ms: 1.01x slower                                                   |
| sqlglot_optimize           | 33.6 ms                                                                     | 34.0 ms: 1.01x slower                                                  |
| python_startup_no_site     | 17.7 ms                                                                     | 17.9 ms: 1.01x slower                                                  |
| typing_runtime_protocols   | 74.8 us                                                                     | 75.9 us: 1.01x slower                                                  |
| telco                      | 4.57 ms                                                                     | 4.64 ms: 1.02x slower                                                  |
| nqueens                    | 57.3 ms                                                                     | 58.2 ms: 1.02x slower                                                  |
| fannkuch                   | 251 ms                                                                      | 255 ms: 1.02x slower                                                   |
| sqlglot_normalize          | 177 ms                                                                      | 180 ms: 1.02x slower                                                   |
| async_tree_memoization     | 338 ms                                                                      | 344 ms: 1.02x slower                                                   |
| coverage                   | 46.6 ms                                                                     | 47.5 ms: 1.02x slower                                                  |
| dulwich_log                | 40.8 ms                                                                     | 41.6 ms: 1.02x slower                                                  |
| deepcopy                   | 221 us                                                                      | 226 us: 1.02x slower                                                   |
| regex_v8                   | 14.9 ms                                                                     | 15.2 ms: 1.02x slower                                                  |
| regex_dna                  | 118 ms                                                                      | 121 ms: 1.02x slower                                                   |
| async_tree_memoization_tg  | 358 ms                                                                      | 367 ms: 1.02x slower                                                   |
| regex_effbot               | 1.58 ms                                                                     | 1.62 ms: 1.03x slower                                                  |
| chameleon                  | 4.78 ms                                                                     | 4.91 ms: 1.03x slower                                                  |
| bench_thread_pool          | 847 us                                                                      | 870 us: 1.03x slower                                                   |
| python_startup             | 19.5 ms                                                                     | 20.0 ms: 1.03x slower                                                  |
| bench_mp_pool              | 62.6 ms                                                                     | 64.6 ms: 1.03x slower                                                  |
| scimark_sparse_mat_mult    | 2.37 ms                                                                     | 2.44 ms: 1.03x slower                                                  |
| mdp                        | 1.37 sec                                                                    | 1.42 sec: 1.03x slower                                                 |
| spectral_norm              | 63.4 ms                                                                     | 65.6 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed_tg | 478 ms                                                                      | 496 ms: 1.04x slower                                                   |
| async_tree_cpu_io_mixed    | 453 ms                                                                      | 471 ms: 1.04x slower                                                   |
| dask                       | 254 ms                                                                      | 265 ms: 1.04x slower                                                   |
| unpickle                   | 7.99 us                                                                     | 8.34 us: 1.04x slower                                                  |
| scimark_fft                | 178 ms                                                                      | 186 ms: 1.05x slower                                                   |
| async_tree_none            | 265 ms                                                                      | 279 ms: 1.05x slower                                                   |
| json                       | 2.81 ms                                                                     | 2.95 ms: 1.05x slower                                                  |
| asyncio_tcp_ssl            | 1.80 sec                                                                    | 1.96 sec: 1.09x slower                                                 |
| pathlib                    | 75.5 ms                                                                     | 82.9 ms: 1.10x slower                                                  |
| tornado_http               | 86.8 ms                                                                     | 96.1 ms: 1.11x slower                                                  |
| asyncio_tcp                | 459 ms                                                                      | 534 ms: 1.16x slower                                                   |
| Geometric mean             | (ref)                                                                       | 1.00x slower                                                           |

Benchmark hidden because not significant (21): deepcopy_reduce, unpickle_list, sympy_integrate, pprint_pformat, pidigits, json_dumps, mypy2, generators, 2to3, sqlite_synth, scimark_monte_carlo, scimark_sor, gc_traversal, pickle_pure_python, scimark_lu, json_loads, async_tree_none_tg, async_tree_io, async_tree_io_tg, xml_etree_parse, pycparser


# HPT report

- Reliability score: 89.58% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
