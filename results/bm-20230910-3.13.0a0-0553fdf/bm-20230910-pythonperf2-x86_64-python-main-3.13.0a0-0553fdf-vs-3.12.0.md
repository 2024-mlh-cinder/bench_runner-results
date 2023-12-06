
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.02x slower
- HPT reliability: 99.59%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.90 sec: 1.00x slower                                      |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 87.7 ms: 1.07x faster                                       |
| float          | 78.5 ms                                                      | 81.1 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 242 ms: 1.00x slower                                        |
| regex_compile  | 146 ms                                                       | 148 ms: 1.01x slower                                        |
| regex_v8       | 25.0 ms                                                      | 25.6 ms: 1.03x slower                                       |
| regex_effbot   | 3.47 ms                                                      | 3.61 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 323 us                                                       | 312 us: 1.03x faster                                        |
| unpickle_list        | 4.77 us                                                      | 4.65 us: 1.03x faster                                       |
| tomli_loads          | 2.20 sec                                                     | 2.18 sec: 1.01x faster                                      |
| unpickle             | 14.8 us                                                      | 14.9 us: 1.01x slower                                       |
| xml_etree_process    | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                       |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                       |
| pickle_dict          | 31.7 us                                                      | 32.3 us: 1.02x slower                                       |
| json_loads           | 24.3 us                                                      | 24.8 us: 1.02x slower                                       |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.03x slower                                        |
| pickle_list          | 4.39 us                                                      | 4.58 us: 1.04x slower                                       |
| unpickle_pure_python | 207 us                                                       | 227 us: 1.10x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                |

Benchmark hidden because not significant (3): xml_etree_generate, pickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                       |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                       |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                       |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|-------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| coverage                | 89.6 ms                                                      | 79.8 ms: 1.12x faster                                       |
| raytrace                | 302 ms                                                       | 271 ms: 1.11x faster                                        |
| crypto_pyaes            | 80.9 ms                                                      | 72.8 ms: 1.11x faster                                       |
| bench_mp_pool           | 5.34 ms                                                      | 4.89 ms: 1.09x faster                                       |
| nbody                   | 94.1 ms                                                      | 87.7 ms: 1.07x faster                                       |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.16 ms: 1.06x faster                                       |
| async_tree_none         | 459 ms                                                       | 439 ms: 1.05x faster                                        |
| scimark_monte_carlo     | 72.4 ms                                                      | 69.3 ms: 1.04x faster                                       |
| generators              | 36.7 ms                                                      | 35.4 ms: 1.03x faster                                       |
| pickle_pure_python      | 323 us                                                       | 312 us: 1.03x faster                                        |
| asyncio_tcp             | 381 ms                                                       | 370 ms: 1.03x faster                                        |
| unpickle_list           | 4.77 us                                                      | 4.65 us: 1.03x faster                                       |
| deepcopy_reduce         | 3.46 us                                                      | 3.37 us: 1.02x faster                                       |
| nqueens                 | 90.1 ms                                                      | 88.9 ms: 1.01x faster                                       |
| chaos                   | 62.9 ms                                                      | 62.0 ms: 1.01x faster                                       |
| tornado_http            | 122 ms                                                       | 120 ms: 1.01x faster                                        |
| tomli_loads             | 2.20 sec                                                     | 2.18 sec: 1.01x faster                                      |
| json                    | 5.14 ms                                                      | 5.11 ms: 1.01x faster                                       |
| sqlglot_normalize       | 117 ms                                                       | 116 ms: 1.01x faster                                        |
| pprint_pformat          | 1.67 sec                                                     | 1.66 sec: 1.01x faster                                      |
| pprint_safe_repr        | 823 ms                                                       | 819 ms: 1.01x faster                                        |
| pathlib                 | 19.8 ms                                                      | 19.7 ms: 1.00x faster                                       |
| python_startup_no_site  | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                       |
| asyncio_tcp_ssl         | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                      |
| regex_dna               | 241 ms                                                       | 242 ms: 1.00x slower                                        |
| docutils                | 2.89 sec                                                     | 2.90 sec: 1.00x slower                                      |
| unpickle                | 14.8 us                                                      | 14.9 us: 1.01x slower                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                       |
| sqlite_synth            | 2.70 us                                                      | 2.72 us: 1.01x slower                                       |
| mypy2                   | 368 ms                                                       | 372 ms: 1.01x slower                                        |
| meteor_contest          | 128 ms                                                       | 129 ms: 1.01x slower                                        |
| sqlglot_optimize        | 57.8 ms                                                      | 58.4 ms: 1.01x slower                                       |
| xml_etree_process       | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                       |
| logging_simple          | 6.73 us                                                      | 6.81 us: 1.01x slower                                       |
| json_dumps              | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                       |
| regex_compile           | 146 ms                                                       | 148 ms: 1.01x slower                                        |
| mdp                     | 2.53 sec                                                     | 2.57 sec: 1.01x slower                                      |
| scimark_fft             | 304 ms                                                       | 308 ms: 1.01x slower                                        |
| pickle_dict             | 31.7 us                                                      | 32.3 us: 1.02x slower                                       |
| logging_format          | 7.37 us                                                      | 7.51 us: 1.02x slower                                       |
| comprehensions          | 21.9 us                                                      | 22.3 us: 1.02x slower                                       |
| deepcopy_memo           | 37.4 us                                                      | 38.1 us: 1.02x slower                                       |
| scimark_lu              | 101 ms                                                       | 103 ms: 1.02x slower                                        |
| async_generators        | 385 ms                                                       | 393 ms: 1.02x slower                                        |
| async_tree_io           | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                      |
| json_loads              | 24.3 us                                                      | 24.8 us: 1.02x slower                                       |
| regex_v8                | 25.0 ms                                                      | 25.6 ms: 1.03x slower                                       |
| xml_etree_iterparse     | 103 ms                                                       | 106 ms: 1.03x slower                                        |
| spectral_norm           | 91.6 ms                                                      | 94.6 ms: 1.03x slower                                       |
| float                   | 78.5 ms                                                      | 81.1 ms: 1.03x slower                                       |
| mako                    | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                       |
| unpack_sequence         | 53.3 ns                                                      | 55.4 ns: 1.04x slower                                       |
| regex_effbot            | 3.47 ms                                                      | 3.61 ms: 1.04x slower                                       |
| pickle_list             | 4.39 us                                                      | 4.58 us: 1.04x slower                                       |
| pycparser               | 1.27 sec                                                     | 1.34 sec: 1.05x slower                                      |
| dulwich_log             | 65.3 ms                                                      | 69.0 ms: 1.06x slower                                       |
| logging_silent          | 95.6 ns                                                      | 102 ns: 1.06x slower                                        |
| gc_traversal            | 3.54 ms                                                      | 3.79 ms: 1.07x slower                                       |
| python_startup          | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                       |
| hexiom                  | 5.96 ms                                                      | 6.46 ms: 1.08x slower                                       |
| unpickle_pure_python    | 207 us                                                       | 227 us: 1.10x slower                                        |
| deltablue               | 3.29 ms                                                      | 3.70 ms: 1.12x slower                                       |
| fannkuch                | 350 ms                                                       | 400 ms: 1.14x slower                                        |
| pyflate                 | 447 ms                                                       | 515 ms: 1.15x slower                                        |
| go                      | 150 ms                                                       | 174 ms: 1.16x slower                                        |
| richards_super          | 51.7 ms                                                      | 60.5 ms: 1.17x slower                                       |
| telco                   | 6.96 ms                                                      | 8.15 ms: 1.17x slower                                       |
| richards                | 45.0 ms                                                      | 53.5 ms: 1.19x slower                                       |
| scimark_sor             | 110 ms                                                       | 146 ms: 1.33x slower                                        |
| dask                    | 397 ms                                                       | 588 ms: 1.48x slower                                        |
| Geometric mean          | (ref)                                                        | 1.02x slower                                                |

Benchmark hidden because not significant (12): async_tree_cpu_io_mixed, typing_runtime_protocols, bench_thread_pool, async_tree_memoization, sqlglot_parse, xml_etree_generate, pidigits, coroutines, deepcopy, pickle, create_gc_cycles, xml_etree_parse
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 99.59% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
