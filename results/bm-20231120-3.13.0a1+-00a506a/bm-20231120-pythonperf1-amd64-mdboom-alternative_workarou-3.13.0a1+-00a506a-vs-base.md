
# Results vs. base

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 00a506a
- commit date: 2023-11-20
- overall geometric mean: 1.00x slower
- HPT reliability: 68.26%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 209 ms                                                                      | 212 ms: 1.01x slower                                                        |
| chameleon      | 4.78 ms                                                                     | 4.89 ms: 1.02x slower                                                       |
| docutils       | 1.54 sec                                                                    | 1.56 sec: 1.01x slower                                                      |
| tornado_http   | 86.8 ms                                                                     | 95.4 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.04x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io    | 728 ms                                                                      | 712 ms: 1.02x faster                                                        |
| async_tree_io_tg | 762 ms                                                                      | 754 ms: 1.01x faster                                                        |
| Geometric mean   | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (6): async_tree_none, async_tree_none_tg, async_tree_memoization_tg, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 74.6 ms                                                                     | 72.4 ms: 1.03x faster                                                       |
| float          | 51.8 ms                                                                     | 51.3 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 14.9 ms                                                                     | 14.7 ms: 1.02x faster                                                       |
| regex_compile  | 80.5 ms                                                                     | 82.8 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (2): regex_effbot, regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads          | 1.43 sec                                                                    | 1.38 sec: 1.04x faster                                                      |
| pickle_dict          | 19.2 us                                                                     | 18.6 us: 1.03x faster                                                       |
| unpickle_pure_python | 133 us                                                                      | 130 us: 1.02x faster                                                        |
| json_dumps           | 5.64 ms                                                                     | 5.52 ms: 1.02x faster                                                       |
| xml_etree_process    | 37.7 ms                                                                     | 37.1 ms: 1.02x faster                                                       |
| json_loads           | 13.3 us                                                                     | 13.5 us: 1.01x slower                                                       |
| pickle               | 7.02 us                                                                     | 7.28 us: 1.04x slower                                                       |
| unpickle_list        | 2.64 us                                                                     | 2.75 us: 1.04x slower                                                       |
| unpickle             | 7.99 us                                                                     | 8.38 us: 1.05x slower                                                       |
| Geometric mean       | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (5): pickle_pure_python, pickle_list, xml_etree_generate, xml_etree_iterparse, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 17.7 ms                                                                     | 18.2 ms: 1.03x slower                                                       |
| python_startup         | 19.5 ms                                                                     | 20.8 ms: 1.07x slower                                                       |
| Geometric mean         | (ref)                                                                       | 1.05x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|-----------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 6.49 ms                                                                     | 6.61 ms: 1.02x slower                                                       |

All benchmarks:
===============

| Benchmark               | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|-------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence         | 50.7 ns                                                                     | 41.8 ns: 1.21x faster                                                       |
| deltablue               | 2.13 ms                                                                     | 1.99 ms: 1.07x faster                                                       |
| pprint_safe_repr        | 510 ms                                                                      | 487 ms: 1.05x faster                                                        |
| pprint_pformat          | 1.03 sec                                                                    | 993 ms: 1.04x faster                                                        |
| coverage                | 46.6 ms                                                                     | 44.9 ms: 1.04x faster                                                       |
| tomli_loads             | 1.43 sec                                                                    | 1.38 sec: 1.04x faster                                                      |
| chaos                   | 40.1 ms                                                                     | 38.7 ms: 1.04x faster                                                       |
| comprehensions          | 10.6 us                                                                     | 10.2 us: 1.04x faster                                                       |
| pickle_dict             | 19.2 us                                                                     | 18.6 us: 1.03x faster                                                       |
| deepcopy_reduce         | 1.98 us                                                                     | 1.92 us: 1.03x faster                                                       |
| go                      | 88.0 ms                                                                     | 85.3 ms: 1.03x faster                                                       |
| meteor_contest          | 74.2 ms                                                                     | 71.9 ms: 1.03x faster                                                       |
| nbody                   | 74.6 ms                                                                     | 72.4 ms: 1.03x faster                                                       |
| pyflate                 | 298 ms                                                                      | 289 ms: 1.03x faster                                                        |
| richards                | 28.7 ms                                                                     | 27.9 ms: 1.03x faster                                                       |
| raytrace                | 167 ms                                                                      | 163 ms: 1.03x faster                                                        |
| sqlglot_transpile       | 986 us                                                                      | 962 us: 1.02x faster                                                        |
| deepcopy                | 221 us                                                                      | 216 us: 1.02x faster                                                        |
| async_tree_io           | 728 ms                                                                      | 712 ms: 1.02x faster                                                        |
| logging_simple          | 6.21 us                                                                     | 6.07 us: 1.02x faster                                                       |
| unpickle_pure_python    | 133 us                                                                      | 130 us: 1.02x faster                                                        |
| json_dumps              | 5.64 ms                                                                     | 5.52 ms: 1.02x faster                                                       |
| logging_format          | 6.68 us                                                                     | 6.56 us: 1.02x faster                                                       |
| async_generators        | 229 ms                                                                      | 225 ms: 1.02x faster                                                        |
| sqlglot_optimize        | 33.6 ms                                                                     | 32.9 ms: 1.02x faster                                                       |
| scimark_sor             | 81.8 ms                                                                     | 80.3 ms: 1.02x faster                                                       |
| xml_etree_process       | 37.7 ms                                                                     | 37.1 ms: 1.02x faster                                                       |
| regex_v8                | 14.9 ms                                                                     | 14.7 ms: 1.02x faster                                                       |
| sympy_integrate         | 12.4 ms                                                                     | 12.2 ms: 1.02x faster                                                       |
| gc_traversal            | 1.50 ms                                                                     | 1.47 ms: 1.02x faster                                                       |
| sqlglot_parse           | 766 us                                                                      | 754 us: 1.02x faster                                                        |
| coroutines              | 13.8 ms                                                                     | 13.6 ms: 1.02x faster                                                       |
| deepcopy_memo           | 23.9 us                                                                     | 23.5 us: 1.01x faster                                                       |
| sqlglot_normalize       | 177 ms                                                                      | 175 ms: 1.01x faster                                                        |
| create_gc_cycles        | 741 us                                                                      | 732 us: 1.01x faster                                                        |
| spectral_norm           | 63.4 ms                                                                     | 62.7 ms: 1.01x faster                                                       |
| async_tree_io_tg        | 762 ms                                                                      | 754 ms: 1.01x faster                                                        |
| richards_super          | 31.3 ms                                                                     | 31.0 ms: 1.01x faster                                                       |
| float                   | 51.8 ms                                                                     | 51.3 ms: 1.01x faster                                                       |
| hexiom                  | 3.88 ms                                                                     | 3.86 ms: 1.01x faster                                                       |
| logging_silent          | 55.7 ns                                                                     | 55.4 ns: 1.01x faster                                                       |
| sympy_expand            | 274 ms                                                                      | 276 ms: 1.00x slower                                                        |
| crypto_pyaes            | 44.0 ms                                                                     | 44.3 ms: 1.01x slower                                                       |
| fannkuch                | 251 ms                                                                      | 252 ms: 1.01x slower                                                        |
| json_loads              | 13.3 us                                                                     | 13.5 us: 1.01x slower                                                       |
| generators              | 20.7 ms                                                                     | 21.0 ms: 1.01x slower                                                       |
| docutils                | 1.54 sec                                                                    | 1.56 sec: 1.01x slower                                                      |
| sympy_str               | 159 ms                                                                      | 161 ms: 1.01x slower                                                        |
| 2to3                    | 209 ms                                                                      | 212 ms: 1.01x slower                                                        |
| mako                    | 6.49 ms                                                                     | 6.61 ms: 1.02x slower                                                       |
| chameleon               | 4.78 ms                                                                     | 4.89 ms: 1.02x slower                                                       |
| python_startup_no_site  | 17.7 ms                                                                     | 18.2 ms: 1.03x slower                                                       |
| bench_mp_pool           | 62.6 ms                                                                     | 64.4 ms: 1.03x slower                                                       |
| regex_compile           | 80.5 ms                                                                     | 82.8 ms: 1.03x slower                                                       |
| telco                   | 4.57 ms                                                                     | 4.73 ms: 1.03x slower                                                       |
| pickle                  | 7.02 us                                                                     | 7.28 us: 1.04x slower                                                       |
| unpickle_list           | 2.64 us                                                                     | 2.75 us: 1.04x slower                                                       |
| scimark_sparse_mat_mult | 2.37 ms                                                                     | 2.47 ms: 1.04x slower                                                       |
| mdp                     | 1.37 sec                                                                    | 1.43 sec: 1.05x slower                                                      |
| unpickle                | 7.99 us                                                                     | 8.38 us: 1.05x slower                                                       |
| scimark_lu              | 56.9 ms                                                                     | 60.2 ms: 1.06x slower                                                       |
| python_startup          | 19.5 ms                                                                     | 20.8 ms: 1.07x slower                                                       |
| pathlib                 | 75.5 ms                                                                     | 80.6 ms: 1.07x slower                                                       |
| json                    | 2.81 ms                                                                     | 3.00 ms: 1.07x slower                                                       |
| dask                    | 254 ms                                                                      | 272 ms: 1.07x slower                                                        |
| scimark_fft             | 178 ms                                                                      | 192 ms: 1.08x slower                                                        |
| dulwich_log             | 40.8 ms                                                                     | 44.4 ms: 1.09x slower                                                       |
| tornado_http            | 86.8 ms                                                                     | 95.4 ms: 1.10x slower                                                       |
| sqlite_synth            | 1.56 us                                                                     | 1.72 us: 1.10x slower                                                       |
| asyncio_tcp             | 459 ms                                                                      | 544 ms: 1.18x slower                                                        |
| Geometric mean          | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (22): async_tree_none, async_tree_none_tg, pycparser, async_tree_memoization_tg, async_tree_memoization, bench_thread_pool, pickle_pure_python, pickle_list, xml_etree_generate, scimark_monte_carlo, nqueens, async_tree_cpu_io_mixed, pidigits, mypy2, regex_effbot, regex_dna, sympy_sum, xml_etree_iterparse, typing_runtime_protocols, xml_etree_parse, async_tree_cpu_io_mixed_tg, asyncio_tcp_ssl


# HPT report

- Reliability score: 68.26% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
