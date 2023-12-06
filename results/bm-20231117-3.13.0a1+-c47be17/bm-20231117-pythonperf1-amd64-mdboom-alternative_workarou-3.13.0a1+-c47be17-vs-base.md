
# Results vs. base

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: c47be17
- commit date: 2023-11-17
- overall geometric mean: 1.00x faster
- HPT reliability: 85.70%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| chameleon      | 4.78 ms                                                                     | 4.90 ms: 1.03x slower                                                       |
| docutils       | 1.54 sec                                                                    | 1.55 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_memoization | 338 ms                                                                      | 343 ms: 1.01x slower                                                        |
| Geometric mean         | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (7): async_tree_io, async_tree_none, async_tree_none_tg, async_tree_cpu_io_mixed, async_tree_io_tg, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 74.6 ms                                                                     | 73.5 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (2): float, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                                     | 1.58 ms: 1.00x slower                                                       |
| regex_dna      | 118 ms                                                                      | 121 ms: 1.02x slower                                                        |
| regex_v8       | 14.9 ms                                                                     | 15.2 ms: 1.02x slower                                                       |
| regex_compile  | 80.5 ms                                                                     | 83.7 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads          | 1.43 sec                                                                    | 1.37 sec: 1.04x faster                                                      |
| pickle_dict          | 19.2 us                                                                     | 18.6 us: 1.03x faster                                                       |
| xml_etree_process    | 37.7 ms                                                                     | 37.3 ms: 1.01x faster                                                       |
| unpickle_list        | 2.64 us                                                                     | 2.61 us: 1.01x faster                                                       |
| xml_etree_generate   | 54.8 ms                                                                     | 54.2 ms: 1.01x faster                                                       |
| json_dumps           | 5.64 ms                                                                     | 5.59 ms: 1.01x faster                                                       |
| unpickle_pure_python | 133 us                                                                      | 132 us: 1.01x faster                                                        |
| json_loads           | 13.3 us                                                                     | 13.4 us: 1.01x slower                                                       |
| unpickle             | 7.99 us                                                                     | 8.04 us: 1.01x slower                                                       |
| xml_etree_parse      | 92.2 ms                                                                     | 93.3 ms: 1.01x slower                                                       |
| pickle               | 7.02 us                                                                     | 7.17 us: 1.02x slower                                                       |
| Geometric mean       | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (3): pickle_pure_python, xml_etree_iterparse, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup | 19.5 ms                                                                     | 19.7 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|-----------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 6.49 ms                                                                     | 6.59 ms: 1.01x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|--------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence          | 50.7 ns                                                                     | 37.6 ns: 1.35x faster                                                       |
| spectral_norm            | 63.4 ms                                                                     | 60.6 ms: 1.05x faster                                                       |
| pprint_safe_repr         | 510 ms                                                                      | 490 ms: 1.04x faster                                                        |
| deltablue                | 2.13 ms                                                                     | 2.05 ms: 1.04x faster                                                       |
| pprint_pformat           | 1.03 sec                                                                    | 997 ms: 1.04x faster                                                        |
| tomli_loads              | 1.43 sec                                                                    | 1.37 sec: 1.04x faster                                                      |
| comprehensions           | 10.6 us                                                                     | 10.3 us: 1.03x faster                                                       |
| pyflate                  | 298 ms                                                                      | 288 ms: 1.03x faster                                                        |
| scimark_monte_carlo      | 41.8 ms                                                                     | 40.5 ms: 1.03x faster                                                       |
| pickle_dict              | 19.2 us                                                                     | 18.6 us: 1.03x faster                                                       |
| sympy_integrate          | 12.4 ms                                                                     | 12.1 ms: 1.02x faster                                                       |
| sqlglot_normalize        | 177 ms                                                                      | 173 ms: 1.02x faster                                                        |
| logging_simple           | 6.21 us                                                                     | 6.07 us: 1.02x faster                                                       |
| sqlglot_optimize         | 33.6 ms                                                                     | 32.9 ms: 1.02x faster                                                       |
| sqlglot_transpile        | 986 us                                                                      | 969 us: 1.02x faster                                                        |
| logging_format           | 6.68 us                                                                     | 6.56 us: 1.02x faster                                                       |
| deepcopy_reduce          | 1.98 us                                                                     | 1.95 us: 1.02x faster                                                       |
| crypto_pyaes             | 44.0 ms                                                                     | 43.4 ms: 1.02x faster                                                       |
| nbody                    | 74.6 ms                                                                     | 73.5 ms: 1.01x faster                                                       |
| pathlib                  | 75.5 ms                                                                     | 74.5 ms: 1.01x faster                                                       |
| xml_etree_process        | 37.7 ms                                                                     | 37.3 ms: 1.01x faster                                                       |
| unpickle_list            | 2.64 us                                                                     | 2.61 us: 1.01x faster                                                       |
| deepcopy                 | 221 us                                                                      | 219 us: 1.01x faster                                                        |
| xml_etree_generate       | 54.8 ms                                                                     | 54.2 ms: 1.01x faster                                                       |
| meteor_contest           | 74.2 ms                                                                     | 73.5 ms: 1.01x faster                                                       |
| typing_runtime_protocols | 74.8 us                                                                     | 74.1 us: 1.01x faster                                                       |
| json_dumps               | 5.64 ms                                                                     | 5.59 ms: 1.01x faster                                                       |
| unpickle_pure_python     | 133 us                                                                      | 132 us: 1.01x faster                                                        |
| async_generators         | 229 ms                                                                      | 228 ms: 1.01x faster                                                        |
| go                       | 88.0 ms                                                                     | 87.4 ms: 1.01x faster                                                       |
| scimark_sor              | 81.8 ms                                                                     | 81.4 ms: 1.00x faster                                                       |
| sympy_sum                | 83.1 ms                                                                     | 82.8 ms: 1.00x faster                                                       |
| sqlglot_parse            | 766 us                                                                      | 763 us: 1.00x faster                                                        |
| regex_effbot             | 1.58 ms                                                                     | 1.58 ms: 1.00x slower                                                       |
| chaos                    | 40.1 ms                                                                     | 40.2 ms: 1.00x slower                                                       |
| sympy_expand             | 274 ms                                                                      | 276 ms: 1.01x slower                                                        |
| json_loads               | 13.3 us                                                                     | 13.4 us: 1.01x slower                                                       |
| unpickle                 | 7.99 us                                                                     | 8.04 us: 1.01x slower                                                       |
| scimark_sparse_mat_mult  | 2.37 ms                                                                     | 2.39 ms: 1.01x slower                                                       |
| docutils                 | 1.54 sec                                                                    | 1.55 sec: 1.01x slower                                                      |
| richards                 | 28.7 ms                                                                     | 29.0 ms: 1.01x slower                                                       |
| generators               | 20.7 ms                                                                     | 21.0 ms: 1.01x slower                                                       |
| telco                    | 4.57 ms                                                                     | 4.62 ms: 1.01x slower                                                       |
| xml_etree_parse          | 92.2 ms                                                                     | 93.3 ms: 1.01x slower                                                       |
| dask                     | 254 ms                                                                      | 257 ms: 1.01x slower                                                        |
| python_startup           | 19.5 ms                                                                     | 19.7 ms: 1.01x slower                                                       |
| mako                     | 6.49 ms                                                                     | 6.59 ms: 1.01x slower                                                       |
| async_tree_memoization   | 338 ms                                                                      | 343 ms: 1.01x slower                                                        |
| sympy_str                | 159 ms                                                                      | 161 ms: 1.02x slower                                                        |
| coroutines               | 13.8 ms                                                                     | 14.0 ms: 1.02x slower                                                       |
| scimark_fft              | 178 ms                                                                      | 181 ms: 1.02x slower                                                        |
| regex_dna                | 118 ms                                                                      | 121 ms: 1.02x slower                                                        |
| pickle                   | 7.02 us                                                                     | 7.17 us: 1.02x slower                                                       |
| regex_v8                 | 14.9 ms                                                                     | 15.2 ms: 1.02x slower                                                       |
| raytrace                 | 167 ms                                                                      | 171 ms: 1.02x slower                                                        |
| hexiom                   | 3.88 ms                                                                     | 3.97 ms: 1.02x slower                                                       |
| logging_silent           | 55.7 ns                                                                     | 57.1 ns: 1.02x slower                                                       |
| chameleon                | 4.78 ms                                                                     | 4.90 ms: 1.03x slower                                                       |
| richards_super           | 31.3 ms                                                                     | 32.2 ms: 1.03x slower                                                       |
| nqueens                  | 57.3 ms                                                                     | 59.3 ms: 1.04x slower                                                       |
| asyncio_tcp              | 459 ms                                                                      | 477 ms: 1.04x slower                                                        |
| fannkuch                 | 251 ms                                                                      | 261 ms: 1.04x slower                                                        |
| regex_compile            | 80.5 ms                                                                     | 83.7 ms: 1.04x slower                                                       |
| mdp                      | 1.37 sec                                                                    | 1.44 sec: 1.05x slower                                                      |
| dulwich_log              | 40.8 ms                                                                     | 43.1 ms: 1.06x slower                                                       |
| scimark_lu               | 56.9 ms                                                                     | 60.9 ms: 1.07x slower                                                       |
| json                     | 2.81 ms                                                                     | 3.06 ms: 1.09x slower                                                       |
| Geometric mean           | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (25): bench_thread_pool, async_tree_io, float, bench_mp_pool, async_tree_none, deepcopy_memo, pickle_pure_python, async_tree_none_tg, sqlite_synth, async_tree_cpu_io_mixed, xml_etree_iterparse, gc_traversal, tornado_http, mypy2, create_gc_cycles, coverage, pidigits, python_startup_no_site, async_tree_io_tg, async_tree_cpu_io_mixed_tg, 2to3, async_tree_memoization_tg, pickle_list, asyncio_tcp_ssl, pycparser


# HPT report

- Reliability score: 85.70% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
