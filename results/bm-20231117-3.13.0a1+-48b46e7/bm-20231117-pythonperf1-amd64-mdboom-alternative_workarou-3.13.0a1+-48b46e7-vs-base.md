
# Results vs. base

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 48b46e7
- commit date: 2023-11-17
- overall geometric mean: 1.03x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 209 ms                                                                      | 207 ms: 1.01x faster                                                        |
| chameleon      | 4.78 ms                                                                     | 4.67 ms: 1.02x faster                                                       |
| docutils       | 1.54 sec                                                                    | 1.53 sec: 1.01x faster                                                      |
| tornado_http   | 86.8 ms                                                                     | 85.6 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 453 ms                                                                      | 445 ms: 1.02x faster                                                        |
| Geometric mean          | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (7): async_tree_memoization_tg, async_tree_none, async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_io, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 74.6 ms                                                                     | 66.3 ms: 1.12x faster                                                       |
| float          | 51.8 ms                                                                     | 51.0 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                                       | 1.05x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 80.5 ms                                                                     | 77.5 ms: 1.04x faster                                                       |
| regex_effbot   | 1.58 ms                                                                     | 1.60 ms: 1.01x slower                                                       |
| regex_dna      | 118 ms                                                                      | 121 ms: 1.03x slower                                                        |
| regex_v8       | 14.9 ms                                                                     | 15.3 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|----------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle_pure_python | 133 us                                                                      | 123 us: 1.08x faster                                                        |
| pickle_pure_python   | 184 us                                                                      | 172 us: 1.07x faster                                                        |
| xml_etree_process    | 37.7 ms                                                                     | 35.9 ms: 1.05x faster                                                       |
| xml_etree_generate   | 54.8 ms                                                                     | 52.3 ms: 1.05x faster                                                       |
| tomli_loads          | 1.43 sec                                                                    | 1.37 sec: 1.04x faster                                                      |
| pickle_dict          | 19.2 us                                                                     | 18.5 us: 1.04x faster                                                       |
| json_dumps           | 5.64 ms                                                                     | 5.48 ms: 1.03x faster                                                       |
| pickle_list          | 2.87 us                                                                     | 2.82 us: 1.02x faster                                                       |
| xml_etree_iterparse  | 63.6 ms                                                                     | 62.5 ms: 1.02x faster                                                       |
| pickle               | 7.02 us                                                                     | 6.95 us: 1.01x faster                                                       |
| json_loads           | 13.3 us                                                                     | 13.5 us: 1.01x slower                                                       |
| unpickle             | 7.99 us                                                                     | 8.45 us: 1.06x slower                                                       |
| Geometric mean       | (ref)                                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_parse, unpickle_list

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|-----------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 6.49 ms                                                                     | 6.36 ms: 1.02x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-48b46e7 |
|--------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence          | 50.7 ns                                                                     | 37.6 ns: 1.35x faster                                                       |
| nbody                    | 74.6 ms                                                                     | 66.3 ms: 1.12x faster                                                       |
| richards                 | 28.7 ms                                                                     | 25.7 ms: 1.12x faster                                                       |
| richards_super           | 31.3 ms                                                                     | 28.8 ms: 1.09x faster                                                       |
| unpickle_pure_python     | 133 us                                                                      | 123 us: 1.08x faster                                                        |
| deltablue                | 2.13 ms                                                                     | 1.98 ms: 1.08x faster                                                       |
| pprint_safe_repr         | 510 ms                                                                      | 474 ms: 1.07x faster                                                        |
| pprint_pformat           | 1.03 sec                                                                    | 966 ms: 1.07x faster                                                        |
| fannkuch                 | 251 ms                                                                      | 234 ms: 1.07x faster                                                        |
| comprehensions           | 10.6 us                                                                     | 9.92 us: 1.07x faster                                                       |
| pyflate                  | 298 ms                                                                      | 279 ms: 1.07x faster                                                        |
| crypto_pyaes             | 44.0 ms                                                                     | 41.3 ms: 1.07x faster                                                       |
| go                       | 88.0 ms                                                                     | 82.4 ms: 1.07x faster                                                       |
| pickle_pure_python       | 184 us                                                                      | 172 us: 1.07x faster                                                        |
| hexiom                   | 3.88 ms                                                                     | 3.64 ms: 1.06x faster                                                       |
| scimark_lu               | 56.9 ms                                                                     | 53.5 ms: 1.06x faster                                                       |
| deepcopy_memo            | 23.9 us                                                                     | 22.6 us: 1.06x faster                                                       |
| chaos                    | 40.1 ms                                                                     | 38.0 ms: 1.06x faster                                                       |
| scimark_sor              | 81.8 ms                                                                     | 77.5 ms: 1.05x faster                                                       |
| xml_etree_process        | 37.7 ms                                                                     | 35.9 ms: 1.05x faster                                                       |
| coroutines               | 13.8 ms                                                                     | 13.1 ms: 1.05x faster                                                       |
| xml_etree_generate       | 54.8 ms                                                                     | 52.3 ms: 1.05x faster                                                       |
| meteor_contest           | 74.2 ms                                                                     | 70.9 ms: 1.05x faster                                                       |
| tomli_loads              | 1.43 sec                                                                    | 1.37 sec: 1.04x faster                                                      |
| scimark_fft              | 178 ms                                                                      | 171 ms: 1.04x faster                                                        |
| scimark_monte_carlo      | 41.8 ms                                                                     | 40.2 ms: 1.04x faster                                                       |
| raytrace                 | 167 ms                                                                      | 161 ms: 1.04x faster                                                        |
| sqlglot_normalize        | 177 ms                                                                      | 170 ms: 1.04x faster                                                        |
| sqlglot_optimize         | 33.6 ms                                                                     | 32.3 ms: 1.04x faster                                                       |
| regex_compile            | 80.5 ms                                                                     | 77.5 ms: 1.04x faster                                                       |
| sympy_sum                | 83.1 ms                                                                     | 80.2 ms: 1.04x faster                                                       |
| pickle_dict              | 19.2 us                                                                     | 18.5 us: 1.04x faster                                                       |
| sympy_expand             | 274 ms                                                                      | 265 ms: 1.04x faster                                                        |
| sqlglot_parse            | 766 us                                                                      | 741 us: 1.03x faster                                                        |
| deepcopy_reduce          | 1.98 us                                                                     | 1.92 us: 1.03x faster                                                       |
| sqlglot_transpile        | 986 us                                                                      | 955 us: 1.03x faster                                                        |
| sympy_str                | 159 ms                                                                      | 154 ms: 1.03x faster                                                        |
| logging_format           | 6.68 us                                                                     | 6.48 us: 1.03x faster                                                       |
| logging_silent           | 55.7 ns                                                                     | 54.0 ns: 1.03x faster                                                       |
| json_dumps               | 5.64 ms                                                                     | 5.48 ms: 1.03x faster                                                       |
| logging_simple           | 6.21 us                                                                     | 6.04 us: 1.03x faster                                                       |
| generators               | 20.7 ms                                                                     | 20.2 ms: 1.03x faster                                                       |
| sympy_integrate          | 12.4 ms                                                                     | 12.1 ms: 1.03x faster                                                       |
| chameleon                | 4.78 ms                                                                     | 4.67 ms: 1.02x faster                                                       |
| spectral_norm            | 63.4 ms                                                                     | 61.9 ms: 1.02x faster                                                       |
| coverage                 | 46.6 ms                                                                     | 45.6 ms: 1.02x faster                                                       |
| nqueens                  | 57.3 ms                                                                     | 56.1 ms: 1.02x faster                                                       |
| mako                     | 6.49 ms                                                                     | 6.36 ms: 1.02x faster                                                       |
| dulwich_log              | 40.8 ms                                                                     | 40.0 ms: 1.02x faster                                                       |
| async_tree_cpu_io_mixed  | 453 ms                                                                      | 445 ms: 1.02x faster                                                        |
| pickle_list              | 2.87 us                                                                     | 2.82 us: 1.02x faster                                                       |
| xml_etree_iterparse      | 63.6 ms                                                                     | 62.5 ms: 1.02x faster                                                       |
| typing_runtime_protocols | 74.8 us                                                                     | 73.6 us: 1.02x faster                                                       |
| float                    | 51.8 ms                                                                     | 51.0 ms: 1.02x faster                                                       |
| deepcopy                 | 221 us                                                                      | 218 us: 1.01x faster                                                        |
| tornado_http             | 86.8 ms                                                                     | 85.6 ms: 1.01x faster                                                       |
| dask                     | 254 ms                                                                      | 251 ms: 1.01x faster                                                        |
| pathlib                  | 75.5 ms                                                                     | 74.6 ms: 1.01x faster                                                       |
| pickle                   | 7.02 us                                                                     | 6.95 us: 1.01x faster                                                       |
| async_generators         | 229 ms                                                                      | 228 ms: 1.01x faster                                                        |
| 2to3                     | 209 ms                                                                      | 207 ms: 1.01x faster                                                        |
| docutils                 | 1.54 sec                                                                    | 1.53 sec: 1.01x faster                                                      |
| bench_mp_pool            | 62.6 ms                                                                     | 62.9 ms: 1.01x slower                                                       |
| scimark_sparse_mat_mult  | 2.37 ms                                                                     | 2.38 ms: 1.01x slower                                                       |
| regex_effbot             | 1.58 ms                                                                     | 1.60 ms: 1.01x slower                                                       |
| json_loads               | 13.3 us                                                                     | 13.5 us: 1.01x slower                                                       |
| asyncio_tcp              | 459 ms                                                                      | 471 ms: 1.03x slower                                                        |
| regex_dna                | 118 ms                                                                      | 121 ms: 1.03x slower                                                        |
| regex_v8                 | 14.9 ms                                                                     | 15.3 ms: 1.03x slower                                                       |
| mdp                      | 1.37 sec                                                                    | 1.41 sec: 1.03x slower                                                      |
| json                     | 2.81 ms                                                                     | 2.95 ms: 1.05x slower                                                       |
| unpickle                 | 7.99 us                                                                     | 8.45 us: 1.06x slower                                                       |
| asyncio_tcp_ssl          | 1.80 sec                                                                    | 1.91 sec: 1.06x slower                                                      |
| Geometric mean           | (ref)                                                                       | 1.03x faster                                                                |

Benchmark hidden because not significant (19): pycparser, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, async_tree_cpu_io_mixed_tg, mypy2, async_tree_io_tg, async_tree_io, xml_etree_parse, bench_thread_pool, unpickle_list, gc_traversal, python_startup_no_site, sqlite_synth, pidigits, telco, async_tree_memoization, python_startup, create_gc_cycles


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
