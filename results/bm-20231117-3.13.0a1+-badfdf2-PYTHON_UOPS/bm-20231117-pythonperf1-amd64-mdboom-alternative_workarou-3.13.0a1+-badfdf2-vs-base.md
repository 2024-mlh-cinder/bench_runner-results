
# Results vs. base

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: badfdf2
- commit date: 2023-11-17
- overall geometric mean: 1.01x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 218 ms                                                                      | 223 ms: 1.02x slower                                                        |
| chameleon      | 4.95 ms                                                                     | 5.13 ms: 1.04x slower                                                       |
| docutils       | 1.59 sec                                                                    | 1.62 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

Benchmark hidden because not significant (8): async_tree_none, async_tree_cpu_io_mixed, async_tree_io, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_memoization, async_tree_io_tg, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 59.8 ms                                                                     | 61.0 ms: 1.02x slower                                                       |
| nbody          | 78.6 ms                                                                     | 81.7 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 15.4 ms                                                                     | 14.9 ms: 1.03x faster                                                       |
| regex_dna      | 120 ms                                                                      | 119 ms: 1.01x faster                                                        |
| regex_effbot   | 1.58 ms                                                                     | 1.59 ms: 1.01x slower                                                       |
| regex_compile  | 91.4 ms                                                                     | 96.9 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|----------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_dict          | 18.7 us                                                                     | 18.3 us: 1.02x faster                                                       |
| json_dumps           | 5.75 ms                                                                     | 5.65 ms: 1.02x faster                                                       |
| pickle               | 7.13 us                                                                     | 7.03 us: 1.01x faster                                                       |
| json_loads           | 13.6 us                                                                     | 13.5 us: 1.01x faster                                                       |
| xml_etree_parse      | 92.5 ms                                                                     | 91.8 ms: 1.01x faster                                                       |
| xml_etree_process    | 37.3 ms                                                                     | 37.5 ms: 1.00x slower                                                       |
| xml_etree_generate   | 54.6 ms                                                                     | 54.9 ms: 1.01x slower                                                       |
| tomli_loads          | 1.59 sec                                                                    | 1.62 sec: 1.02x slower                                                      |
| xml_etree_iterparse  | 65.7 ms                                                                     | 67.2 ms: 1.02x slower                                                       |
| unpickle_pure_python | 142 us                                                                      | 146 us: 1.03x slower                                                        |
| unpickle             | 8.17 us                                                                     | 8.41 us: 1.03x slower                                                       |
| pickle_pure_python   | 180 us                                                                      | 187 us: 1.04x slower                                                        |
| pickle_list          | 3.04 us                                                                     | 3.27 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|-----------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.30 ms                                                                     | 7.99 ms: 1.04x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-badfdf2 |
|--------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| scimark_sparse_mat_mult  | 3.88 ms                                                                     | 3.69 ms: 1.05x faster                                                       |
| asyncio_tcp              | 480 ms                                                                      | 459 ms: 1.05x faster                                                        |
| mako                     | 8.30 ms                                                                     | 7.99 ms: 1.04x faster                                                       |
| regex_v8                 | 15.4 ms                                                                     | 14.9 ms: 1.03x faster                                                       |
| pickle_dict              | 18.7 us                                                                     | 18.3 us: 1.02x faster                                                       |
| json_dumps               | 5.75 ms                                                                     | 5.65 ms: 1.02x faster                                                       |
| create_gc_cycles         | 744 us                                                                      | 733 us: 1.01x faster                                                        |
| pickle                   | 7.13 us                                                                     | 7.03 us: 1.01x faster                                                       |
| deltablue                | 2.96 ms                                                                     | 2.92 ms: 1.01x faster                                                       |
| deepcopy_reduce          | 1.99 us                                                                     | 1.96 us: 1.01x faster                                                       |
| scimark_monte_carlo      | 49.0 ms                                                                     | 48.5 ms: 1.01x faster                                                       |
| typing_runtime_protocols | 80.2 us                                                                     | 79.4 us: 1.01x faster                                                       |
| regex_dna                | 120 ms                                                                      | 119 ms: 1.01x faster                                                        |
| json_loads               | 13.6 us                                                                     | 13.5 us: 1.01x faster                                                       |
| pprint_pformat           | 1.11 sec                                                                    | 1.10 sec: 1.01x faster                                                      |
| xml_etree_parse          | 92.5 ms                                                                     | 91.8 ms: 1.01x faster                                                       |
| scimark_fft              | 213 ms                                                                      | 212 ms: 1.01x faster                                                        |
| unpack_sequence          | 38.0 ns                                                                     | 37.7 ns: 1.01x faster                                                       |
| gc_traversal             | 1.51 ms                                                                     | 1.50 ms: 1.01x faster                                                       |
| telco                    | 4.87 ms                                                                     | 4.85 ms: 1.00x faster                                                       |
| pprint_safe_repr         | 538 ms                                                                      | 536 ms: 1.00x faster                                                        |
| meteor_contest           | 79.0 ms                                                                     | 79.2 ms: 1.00x slower                                                       |
| xml_etree_process        | 37.3 ms                                                                     | 37.5 ms: 1.00x slower                                                       |
| regex_effbot             | 1.58 ms                                                                     | 1.59 ms: 1.01x slower                                                       |
| xml_etree_generate       | 54.6 ms                                                                     | 54.9 ms: 1.01x slower                                                       |
| sympy_integrate          | 13.4 ms                                                                     | 13.5 ms: 1.01x slower                                                       |
| sqlglot_normalize        | 177 ms                                                                      | 178 ms: 1.01x slower                                                        |
| sqlite_synth             | 1.58 us                                                                     | 1.59 us: 1.01x slower                                                       |
| deepcopy                 | 222 us                                                                      | 224 us: 1.01x slower                                                        |
| sqlglot_optimize         | 33.6 ms                                                                     | 33.9 ms: 1.01x slower                                                       |
| richards_super           | 31.4 ms                                                                     | 31.7 ms: 1.01x slower                                                       |
| fannkuch                 | 294 ms                                                                      | 298 ms: 1.01x slower                                                        |
| richards                 | 27.9 ms                                                                     | 28.3 ms: 1.01x slower                                                       |
| docutils                 | 1.59 sec                                                                    | 1.62 sec: 1.01x slower                                                      |
| async_generators         | 233 ms                                                                      | 237 ms: 1.02x slower                                                        |
| logging_simple           | 6.43 us                                                                     | 6.53 us: 1.02x slower                                                       |
| dask                     | 256 ms                                                                      | 260 ms: 1.02x slower                                                        |
| pyflate                  | 333 ms                                                                      | 339 ms: 1.02x slower                                                        |
| logging_format           | 6.89 us                                                                     | 7.02 us: 1.02x slower                                                       |
| sqlglot_transpile        | 1.00 ms                                                                     | 1.02 ms: 1.02x slower                                                       |
| float                    | 59.8 ms                                                                     | 61.0 ms: 1.02x slower                                                       |
| crypto_pyaes             | 51.2 ms                                                                     | 52.2 ms: 1.02x slower                                                       |
| tomli_loads              | 1.59 sec                                                                    | 1.62 sec: 1.02x slower                                                      |
| 2to3                     | 218 ms                                                                      | 223 ms: 1.02x slower                                                        |
| coverage                 | 45.3 ms                                                                     | 46.3 ms: 1.02x slower                                                       |
| coroutines               | 13.1 ms                                                                     | 13.4 ms: 1.02x slower                                                       |
| xml_etree_iterparse      | 65.7 ms                                                                     | 67.2 ms: 1.02x slower                                                       |
| logging_silent           | 58.7 ns                                                                     | 60.2 ns: 1.02x slower                                                       |
| nqueens                  | 70.4 ms                                                                     | 72.2 ms: 1.03x slower                                                       |
| hexiom                   | 5.96 ms                                                                     | 6.11 ms: 1.03x slower                                                       |
| unpickle_pure_python     | 142 us                                                                      | 146 us: 1.03x slower                                                        |
| unpickle                 | 8.17 us                                                                     | 8.41 us: 1.03x slower                                                       |
| sympy_sum                | 84.6 ms                                                                     | 87.1 ms: 1.03x slower                                                       |
| sqlglot_parse            | 787 us                                                                      | 812 us: 1.03x slower                                                        |
| generators               | 20.6 ms                                                                     | 21.3 ms: 1.03x slower                                                       |
| chameleon                | 4.95 ms                                                                     | 5.13 ms: 1.04x slower                                                       |
| mdp                      | 1.52 sec                                                                    | 1.57 sec: 1.04x slower                                                      |
| nbody                    | 78.6 ms                                                                     | 81.7 ms: 1.04x slower                                                       |
| deepcopy_memo            | 23.7 us                                                                     | 24.7 us: 1.04x slower                                                       |
| sympy_str                | 165 ms                                                                      | 172 ms: 1.04x slower                                                        |
| go                       | 99.2 ms                                                                     | 103 ms: 1.04x slower                                                        |
| chaos                    | 45.0 ms                                                                     | 46.9 ms: 1.04x slower                                                       |
| pickle_pure_python       | 180 us                                                                      | 187 us: 1.04x slower                                                        |
| sympy_expand             | 280 ms                                                                      | 294 ms: 1.05x slower                                                        |
| scimark_lu               | 58.6 ms                                                                     | 61.9 ms: 1.06x slower                                                       |
| raytrace                 | 177 ms                                                                      | 187 ms: 1.06x slower                                                        |
| spectral_norm            | 59.7 ms                                                                     | 63.3 ms: 1.06x slower                                                       |
| regex_compile            | 91.4 ms                                                                     | 96.9 ms: 1.06x slower                                                       |
| dulwich_log              | 42.3 ms                                                                     | 44.9 ms: 1.06x slower                                                       |
| pickle_list              | 3.04 us                                                                     | 3.27 us: 1.08x slower                                                       |
| scimark_sor              | 77.6 ms                                                                     | 83.6 ms: 1.08x slower                                                       |
| Geometric mean           | (ref)                                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (21): tornado_http, json, async_tree_none, pidigits, pathlib, python_startup, bench_mp_pool, async_tree_cpu_io_mixed, async_tree_io, python_startup_no_site, bench_thread_pool, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_memoization, async_tree_io_tg, async_tree_none_tg, comprehensions, unpickle_list, asyncio_tcp_ssl, mypy2, pycparser


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
