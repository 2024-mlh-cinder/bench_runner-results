
# Results vs. base

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 48b46e7
- commit date: 2023-11-17
- overall geometric mean: 1.00x slower
- HPT reliability: 72.30%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| chameleon      | 4.95 ms                                                                     | 5.02 ms: 1.01x slower                                                       |
| docutils       | 1.59 sec                                                                    | 1.58 sec: 1.01x faster                                                      |
| Geometric mean | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io    | 739 ms                                                                      | 727 ms: 1.02x faster                                                        |
| async_tree_io_tg | 775 ms                                                                      | 765 ms: 1.01x faster                                                        |
| Geometric mean   | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (6): async_tree_none, async_tree_memoization, async_tree_none_tg, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 59.8 ms                                                                     | 61.7 ms: 1.03x slower                                                       |
| nbody          | 78.6 ms                                                                     | 83.9 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.03x slower                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 15.4 ms                                                                     | 15.3 ms: 1.01x faster                                                       |
| regex_dna      | 120 ms                                                                      | 122 ms: 1.01x slower                                                        |
| regex_compile  | 91.4 ms                                                                     | 92.7 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.13 us                                                                     | 6.93 us: 1.03x faster                                                       |
| xml_etree_process    | 37.3 ms                                                                     | 36.4 ms: 1.02x faster                                                       |
| xml_etree_generate   | 54.6 ms                                                                     | 54.0 ms: 1.01x faster                                                       |
| json_loads           | 13.6 us                                                                     | 13.4 us: 1.01x faster                                                       |
| json_dumps           | 5.75 ms                                                                     | 5.70 ms: 1.01x faster                                                       |
| pickle_dict          | 18.7 us                                                                     | 18.6 us: 1.00x faster                                                       |
| unpickle_pure_python | 142 us                                                                      | 143 us: 1.01x slower                                                        |
| xml_etree_iterparse  | 65.7 ms                                                                     | 67.1 ms: 1.02x slower                                                       |
| unpickle_list        | 2.64 us                                                                     | 2.72 us: 1.03x slower                                                       |
| Geometric mean       | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (5): pickle_pure_python, unpickle, tomli_loads, xml_etree_parse, pickle_list

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-----------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.30 ms                                                                     | 8.20 ms: 1.01x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|--------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| scimark_sparse_mat_mult  | 3.88 ms                                                                     | 3.68 ms: 1.05x faster                                                       |
| logging_silent           | 58.7 ns                                                                     | 56.5 ns: 1.04x faster                                                       |
| pickle                   | 7.13 us                                                                     | 6.93 us: 1.03x faster                                                       |
| meteor_contest           | 79.0 ms                                                                     | 77.0 ms: 1.03x faster                                                       |
| telco                    | 4.87 ms                                                                     | 4.75 ms: 1.02x faster                                                       |
| xml_etree_process        | 37.3 ms                                                                     | 36.4 ms: 1.02x faster                                                       |
| richards_super           | 31.4 ms                                                                     | 30.8 ms: 1.02x faster                                                       |
| go                       | 99.2 ms                                                                     | 97.5 ms: 1.02x faster                                                       |
| async_tree_io            | 739 ms                                                                      | 727 ms: 1.02x faster                                                        |
| deepcopy_reduce          | 1.99 us                                                                     | 1.96 us: 1.01x faster                                                       |
| richards                 | 27.9 ms                                                                     | 27.6 ms: 1.01x faster                                                       |
| async_tree_io_tg         | 775 ms                                                                      | 765 ms: 1.01x faster                                                        |
| mako                     | 8.30 ms                                                                     | 8.20 ms: 1.01x faster                                                       |
| xml_etree_generate       | 54.6 ms                                                                     | 54.0 ms: 1.01x faster                                                       |
| docutils                 | 1.59 sec                                                                    | 1.58 sec: 1.01x faster                                                      |
| generators               | 20.6 ms                                                                     | 20.4 ms: 1.01x faster                                                       |
| json_loads               | 13.6 us                                                                     | 13.4 us: 1.01x faster                                                       |
| typing_runtime_protocols | 80.2 us                                                                     | 79.5 us: 1.01x faster                                                       |
| pprint_safe_repr         | 538 ms                                                                      | 533 ms: 1.01x faster                                                        |
| scimark_monte_carlo      | 49.0 ms                                                                     | 48.6 ms: 1.01x faster                                                       |
| coverage                 | 45.3 ms                                                                     | 44.9 ms: 1.01x faster                                                       |
| pprint_pformat           | 1.11 sec                                                                    | 1.10 sec: 1.01x faster                                                      |
| json_dumps               | 5.75 ms                                                                     | 5.70 ms: 1.01x faster                                                       |
| sqlglot_normalize        | 177 ms                                                                      | 176 ms: 1.01x faster                                                        |
| deepcopy                 | 222 us                                                                      | 221 us: 1.01x faster                                                        |
| regex_v8                 | 15.4 ms                                                                     | 15.3 ms: 1.01x faster                                                       |
| sqlglot_optimize         | 33.6 ms                                                                     | 33.4 ms: 1.01x faster                                                       |
| pickle_dict              | 18.7 us                                                                     | 18.6 us: 1.00x faster                                                       |
| sympy_integrate          | 13.4 ms                                                                     | 13.3 ms: 1.00x faster                                                       |
| logging_format           | 6.89 us                                                                     | 6.93 us: 1.01x slower                                                       |
| chaos                    | 45.0 ms                                                                     | 45.2 ms: 1.01x slower                                                       |
| unpickle_pure_python     | 142 us                                                                      | 143 us: 1.01x slower                                                        |
| sympy_str                | 165 ms                                                                      | 166 ms: 1.01x slower                                                        |
| sqlite_synth             | 1.58 us                                                                     | 1.59 us: 1.01x slower                                                       |
| deepcopy_memo            | 23.7 us                                                                     | 23.9 us: 1.01x slower                                                       |
| logging_simple           | 6.43 us                                                                     | 6.48 us: 1.01x slower                                                       |
| regex_dna                | 120 ms                                                                      | 122 ms: 1.01x slower                                                        |
| deltablue                | 2.96 ms                                                                     | 2.98 ms: 1.01x slower                                                       |
| sympy_expand             | 280 ms                                                                      | 283 ms: 1.01x slower                                                        |
| sympy_sum                | 84.6 ms                                                                     | 85.5 ms: 1.01x slower                                                       |
| coroutines               | 13.1 ms                                                                     | 13.3 ms: 1.01x slower                                                       |
| mdp                      | 1.52 sec                                                                    | 1.53 sec: 1.01x slower                                                      |
| comprehensions           | 15.5 us                                                                     | 15.7 us: 1.01x slower                                                       |
| chameleon                | 4.95 ms                                                                     | 5.02 ms: 1.01x slower                                                       |
| hexiom                   | 5.96 ms                                                                     | 6.04 ms: 1.01x slower                                                       |
| fannkuch                 | 294 ms                                                                      | 298 ms: 1.01x slower                                                        |
| regex_compile            | 91.4 ms                                                                     | 92.7 ms: 1.01x slower                                                       |
| crypto_pyaes             | 51.2 ms                                                                     | 52.1 ms: 1.02x slower                                                       |
| pyflate                  | 333 ms                                                                      | 340 ms: 1.02x slower                                                        |
| xml_etree_iterparse      | 65.7 ms                                                                     | 67.1 ms: 1.02x slower                                                       |
| scimark_fft              | 213 ms                                                                      | 218 ms: 1.02x slower                                                        |
| async_generators         | 233 ms                                                                      | 240 ms: 1.03x slower                                                        |
| unpickle_list            | 2.64 us                                                                     | 2.72 us: 1.03x slower                                                       |
| float                    | 59.8 ms                                                                     | 61.7 ms: 1.03x slower                                                       |
| scimark_lu               | 58.6 ms                                                                     | 60.9 ms: 1.04x slower                                                       |
| scimark_sor              | 77.6 ms                                                                     | 82.8 ms: 1.07x slower                                                       |
| nbody                    | 78.6 ms                                                                     | 83.9 ms: 1.07x slower                                                       |
| spectral_norm            | 59.7 ms                                                                     | 64.3 ms: 1.08x slower                                                       |
| unpack_sequence          | 38.0 ns                                                                     | 48.1 ns: 1.27x slower                                                       |
| Geometric mean           | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (33): pycparser, asyncio_tcp, async_tree_none, create_gc_cycles, async_tree_memoization, python_startup_no_site, tornado_http, async_tree_none_tg, dask, async_tree_memoization_tg, gc_traversal, bench_thread_pool, pathlib, pidigits, json, async_tree_cpu_io_mixed, mypy2, 2to3, async_tree_cpu_io_mixed_tg, regex_effbot, python_startup, bench_mp_pool, raytrace, pickle_pure_python, sqlglot_parse, dulwich_log, nqueens, unpickle, tomli_loads, sqlglot_transpile, xml_etree_parse, asyncio_tcp_ssl, pickle_list


# HPT report

- Reliability score: 72.30% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
