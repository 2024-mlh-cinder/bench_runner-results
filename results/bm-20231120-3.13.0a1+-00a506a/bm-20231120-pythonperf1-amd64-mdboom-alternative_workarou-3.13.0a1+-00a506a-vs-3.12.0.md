
# Results vs. 3.12.0

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 00a506a
- commit date: 2023-11-20
- overall geometric mean: 1.01x faster \*
- HPT reliability: 96.92%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| chameleon      | 4.95 ms                                                     | 4.89 ms: 1.01x faster                                                       |
| docutils       | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 95.4 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none           | 286 ms                                                      | 261 ms: 1.09x faster                                                        |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 454 ms: 1.05x faster                                                        |
| async_tree_io_tg          | 742 ms                                                      | 754 ms: 1.02x slower                                                        |
| async_tree_memoization_tg | 345 ms                                                      | 356 ms: 1.03x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_none_tg, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 51.3 ms: 1.07x faster                                                       |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| nbody          | 68.8 ms                                                     | 72.4 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 82.8 ms: 1.05x faster                                                       |
| regex_dna      | 119 ms                                                      | 119 ms: 1.01x faster                                                        |
| regex_v8       | 13.5 ms                                                     | 14.7 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 183 us: 1.06x faster                                                        |
| json_dumps           | 5.83 ms                                                     | 5.52 ms: 1.06x faster                                                       |
| unpickle_pure_python | 134 us                                                      | 130 us: 1.03x faster                                                        |
| pickle_dict          | 18.9 us                                                     | 18.6 us: 1.02x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.6 ms: 1.02x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.1 ms: 1.01x faster                                                       |
| pickle               | 7.38 us                                                     | 7.28 us: 1.01x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.38 us: 1.01x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.86 us: 1.01x faster                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| unpickle_list        | 2.69 us                                                     | 2.75 us: 1.02x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 92.8 ms: 1.02x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.8 ms: 1.10x slower                                                       |
| python_startup_no_site | 15.9 ms                                                     | 18.2 ms: 1.14x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.05 ms                                                     | 6.61 ms: 1.07x faster                                                       |

All benchmarks:
===============

| Benchmark                 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|---------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| comprehensions            | 14.0 us                                                     | 10.2 us: 1.37x faster                                                       |
| typing_runtime_protocols  | 96.7 us                                                     | 75.1 us: 1.29x faster                                                       |
| raytrace                  | 192 ms                                                      | 163 ms: 1.18x faster                                                        |
| async_tree_none           | 286 ms                                                      | 261 ms: 1.09x faster                                                        |
| logging_silent            | 60.5 ns                                                     | 55.4 ns: 1.09x faster                                                       |
| chaos                     | 42.1 ms                                                     | 38.7 ms: 1.09x faster                                                       |
| deepcopy_reduce           | 2.08 us                                                     | 1.92 us: 1.09x faster                                                       |
| sympy_sum                 | 90.1 ms                                                     | 83.4 ms: 1.08x faster                                                       |
| deepcopy                  | 233 us                                                      | 216 us: 1.08x faster                                                        |
| generators                | 22.6 ms                                                     | 21.0 ms: 1.08x faster                                                       |
| nqueens                   | 61.7 ms                                                     | 57.3 ms: 1.08x faster                                                       |
| mako                      | 7.05 ms                                                     | 6.61 ms: 1.07x faster                                                       |
| float                     | 54.7 ms                                                     | 51.3 ms: 1.07x faster                                                       |
| deltablue                 | 2.12 ms                                                     | 1.99 ms: 1.06x faster                                                       |
| sympy_str                 | 171 ms                                                      | 161 ms: 1.06x faster                                                        |
| sympy_integrate           | 13.0 ms                                                     | 12.2 ms: 1.06x faster                                                       |
| sqlglot_parse             | 802 us                                                      | 754 us: 1.06x faster                                                        |
| pickle_pure_python        | 195 us                                                      | 183 us: 1.06x faster                                                        |
| sqlglot_transpile         | 1.02 ms                                                     | 962 us: 1.06x faster                                                        |
| json_dumps                | 5.83 ms                                                     | 5.52 ms: 1.06x faster                                                       |
| regex_compile             | 87.2 ms                                                     | 82.8 ms: 1.05x faster                                                       |
| async_tree_cpu_io_mixed   | 477 ms                                                      | 454 ms: 1.05x faster                                                        |
| sqlglot_normalize         | 183 ms                                                      | 175 ms: 1.05x faster                                                        |
| crypto_pyaes              | 46.4 ms                                                     | 44.3 ms: 1.05x faster                                                       |
| bench_mp_pool             | 67.2 ms                                                     | 64.4 ms: 1.04x faster                                                       |
| pprint_pformat            | 1.04 sec                                                    | 993 ms: 1.04x faster                                                        |
| go                        | 89.0 ms                                                     | 85.3 ms: 1.04x faster                                                       |
| pprint_safe_repr          | 508 ms                                                      | 487 ms: 1.04x faster                                                        |
| coroutines                | 14.1 ms                                                     | 13.6 ms: 1.04x faster                                                       |
| hexiom                    | 4.00 ms                                                     | 3.86 ms: 1.04x faster                                                       |
| docutils                  | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                                      |
| sqlglot_optimize          | 34.0 ms                                                     | 32.9 ms: 1.03x faster                                                       |
| unpickle_pure_python      | 134 us                                                      | 130 us: 1.03x faster                                                        |
| scimark_monte_carlo       | 43.0 ms                                                     | 41.8 ms: 1.03x faster                                                       |
| logging_format            | 6.72 us                                                     | 6.56 us: 1.02x faster                                                       |
| logging_simple            | 6.21 us                                                     | 6.07 us: 1.02x faster                                                       |
| pidigits                  | 150 ms                                                      | 147 ms: 1.02x faster                                                        |
| async_generators          | 230 ms                                                      | 225 ms: 1.02x faster                                                        |
| pickle_dict               | 18.9 us                                                     | 18.6 us: 1.02x faster                                                       |
| xml_etree_generate        | 55.8 ms                                                     | 54.6 ms: 1.02x faster                                                       |
| spectral_norm             | 63.9 ms                                                     | 62.7 ms: 1.02x faster                                                       |
| sqlite_synth              | 1.75 us                                                     | 1.72 us: 1.02x faster                                                       |
| scimark_sparse_mat_mult   | 2.51 ms                                                     | 2.47 ms: 1.02x faster                                                       |
| xml_etree_process         | 37.6 ms                                                     | 37.1 ms: 1.01x faster                                                       |
| pyflate                   | 294 ms                                                      | 289 ms: 1.01x faster                                                        |
| pickle                    | 7.38 us                                                     | 7.28 us: 1.01x faster                                                       |
| chameleon                 | 4.95 ms                                                     | 4.89 ms: 1.01x faster                                                       |
| json_loads                | 13.6 us                                                     | 13.5 us: 1.01x faster                                                       |
| gc_traversal              | 1.49 ms                                                     | 1.47 ms: 1.01x faster                                                       |
| sympy_expand              | 278 ms                                                      | 276 ms: 1.01x faster                                                        |
| unpickle                  | 8.44 us                                                     | 8.38 us: 1.01x faster                                                       |
| pickle_list               | 2.88 us                                                     | 2.86 us: 1.01x faster                                                       |
| richards_super            | 31.2 ms                                                     | 31.0 ms: 1.01x faster                                                       |
| regex_dna                 | 119 ms                                                      | 119 ms: 1.01x faster                                                        |
| meteor_contest            | 72.1 ms                                                     | 71.9 ms: 1.00x faster                                                       |
| scimark_sor               | 79.8 ms                                                     | 80.3 ms: 1.01x slower                                                       |
| mdp                       | 1.42 sec                                                    | 1.43 sec: 1.01x slower                                                      |
| xml_etree_iterparse       | 63.1 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| pathlib                   | 79.6 ms                                                     | 80.6 ms: 1.01x slower                                                       |
| richards                  | 27.6 ms                                                     | 27.9 ms: 1.01x slower                                                       |
| bench_thread_pool         | 830 us                                                      | 842 us: 1.01x slower                                                        |
| async_tree_io_tg          | 742 ms                                                      | 754 ms: 1.02x slower                                                        |
| unpickle_list             | 2.69 us                                                     | 2.75 us: 1.02x slower                                                       |
| xml_etree_parse           | 90.5 ms                                                     | 92.8 ms: 1.02x slower                                                       |
| async_tree_memoization_tg | 345 ms                                                      | 356 ms: 1.03x slower                                                        |
| fannkuch                  | 244 ms                                                      | 252 ms: 1.03x slower                                                        |
| dulwich_log               | 42.7 ms                                                     | 44.4 ms: 1.04x slower                                                       |
| scimark_lu                | 57.5 ms                                                     | 60.2 ms: 1.05x slower                                                       |
| nbody                     | 68.8 ms                                                     | 72.4 ms: 1.05x slower                                                       |
| scimark_fft               | 181 ms                                                      | 192 ms: 1.06x slower                                                        |
| dask                      | 255 ms                                                      | 272 ms: 1.07x slower                                                        |
| regex_v8                  | 13.5 ms                                                     | 14.7 ms: 1.09x slower                                                       |
| tornado_http              | 87.2 ms                                                     | 95.4 ms: 1.09x slower                                                       |
| python_startup            | 18.8 ms                                                     | 20.8 ms: 1.10x slower                                                       |
| pycparser                 | 673 ms                                                      | 744 ms: 1.10x slower                                                        |
| coverage                  | 39.8 ms                                                     | 44.9 ms: 1.13x slower                                                       |
| unpack_sequence           | 36.9 ns                                                     | 41.8 ns: 1.13x slower                                                       |
| python_startup_no_site    | 15.9 ms                                                     | 18.2 ms: 1.14x slower                                                       |
| asyncio_tcp               | 471 ms                                                      | 544 ms: 1.15x slower                                                        |
| telco                     | 4.08 ms                                                     | 4.73 ms: 1.16x slower                                                       |
| mypy2                     | 209 ms                                                      | 287 ms: 1.38x slower                                                        |
| Geometric mean            | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (11): 2to3, async_tree_cpu_io_mixed_tg, tomli_loads, regex_effbot, async_tree_io, async_tree_none_tg, deepcopy_memo, async_tree_memoization, create_gc_cycles, asyncio_tcp_ssl, json
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 96.92% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
