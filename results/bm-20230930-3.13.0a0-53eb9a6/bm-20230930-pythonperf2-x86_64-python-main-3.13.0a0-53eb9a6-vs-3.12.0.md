
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.02x slower
- HPT reliability: 97.61%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.85 sec: 1.01x faster                                      |
| tornado_http   | 122 ms                                                       | 119 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 88.7 ms: 1.06x faster                                       |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                        |
| float          | 78.5 ms                                                      | 82.3 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                        | 1.00x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_effbot   | 3.47 ms                                                      | 3.45 ms: 1.01x faster                                       |
| regex_v8       | 25.0 ms                                                      | 25.0 ms: 1.00x slower                                       |
| regex_compile  | 146 ms                                                       | 149 ms: 1.03x slower                                        |
| regex_dna      | 241 ms                                                       | 247 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.2 us: 1.04x faster                                       |
| pickle_list          | 4.39 us                                                      | 4.30 us: 1.02x faster                                       |
| unpickle_list        | 4.77 us                                                      | 4.70 us: 1.02x faster                                       |
| pickle               | 10.1 us                                                      | 10.0 us: 1.01x faster                                       |
| pickle_pure_python   | 323 us                                                       | 321 us: 1.01x faster                                        |
| xml_etree_process    | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                       |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| xml_etree_iterparse  | 103 ms                                                       | 105 ms: 1.02x slower                                        |
| pickle_dict          | 31.7 us                                                      | 32.6 us: 1.03x slower                                       |
| json_loads           | 24.3 us                                                      | 24.9 us: 1.03x slower                                       |
| json_dumps           | 10.2 ms                                                      | 10.6 ms: 1.03x slower                                       |
| tomli_loads          | 2.20 sec                                                     | 2.31 sec: 1.05x slower                                      |
| unpickle_pure_python | 207 us                                                       | 218 us: 1.05x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                       |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                       |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.3 ms: 1.03x slower                                       |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6 |
|-------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| crypto_pyaes            | 80.9 ms                                                      | 71.4 ms: 1.13x faster                                       |
| bench_mp_pool           | 5.34 ms                                                      | 4.75 ms: 1.12x faster                                       |
| scimark_monte_carlo     | 72.4 ms                                                      | 66.6 ms: 1.09x faster                                       |
| coverage                | 89.6 ms                                                      | 82.8 ms: 1.08x faster                                       |
| raytrace                | 302 ms                                                       | 279 ms: 1.08x faster                                        |
| nbody                   | 94.1 ms                                                      | 88.7 ms: 1.06x faster                                       |
| async_tree_none         | 459 ms                                                       | 438 ms: 1.05x faster                                        |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.23 ms: 1.05x faster                                       |
| unpickle                | 14.8 us                                                      | 14.2 us: 1.04x faster                                       |
| generators              | 36.7 ms                                                      | 35.3 ms: 1.04x faster                                       |
| asyncio_tcp             | 381 ms                                                       | 369 ms: 1.03x faster                                        |
| bench_thread_pool       | 980 us                                                       | 951 us: 1.03x faster                                        |
| tornado_http            | 122 ms                                                       | 119 ms: 1.02x faster                                        |
| pickle_list             | 4.39 us                                                      | 4.30 us: 1.02x faster                                       |
| pprint_safe_repr        | 823 ms                                                       | 810 ms: 1.02x faster                                        |
| scimark_fft             | 304 ms                                                       | 299 ms: 1.02x faster                                        |
| unpickle_list           | 4.77 us                                                      | 4.70 us: 1.02x faster                                       |
| sqlglot_normalize       | 117 ms                                                       | 115 ms: 1.01x faster                                        |
| scimark_lu              | 101 ms                                                       | 99.3 ms: 1.01x faster                                       |
| sqlite_synth            | 2.70 us                                                      | 2.66 us: 1.01x faster                                       |
| docutils                | 2.89 sec                                                     | 2.85 sec: 1.01x faster                                      |
| mdp                     | 2.53 sec                                                     | 2.51 sec: 1.01x faster                                      |
| deepcopy_reduce         | 3.46 us                                                      | 3.42 us: 1.01x faster                                       |
| nqueens                 | 90.1 ms                                                      | 89.4 ms: 1.01x faster                                       |
| regex_effbot            | 3.47 ms                                                      | 3.45 ms: 1.01x faster                                       |
| pickle                  | 10.1 us                                                      | 10.0 us: 1.01x faster                                       |
| pprint_pformat          | 1.67 sec                                                     | 1.66 sec: 1.01x faster                                      |
| pickle_pure_python      | 323 us                                                       | 321 us: 1.01x faster                                        |
| python_startup_no_site  | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                       |
| regex_v8                | 25.0 ms                                                      | 25.0 ms: 1.00x slower                                       |
| pidigits                | 264 ms                                                       | 264 ms: 1.00x slower                                        |
| logging_silent          | 95.6 ns                                                      | 95.9 ns: 1.00x slower                                       |
| asyncio_tcp_ssl         | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                      |
| sqlglot_parse           | 1.40 ms                                                      | 1.41 ms: 1.00x slower                                       |
| comprehensions          | 21.9 us                                                      | 22.0 us: 1.01x slower                                       |
| sqlglot_optimize        | 57.8 ms                                                      | 58.2 ms: 1.01x slower                                       |
| sqlglot_transpile       | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                       |
| async_generators        | 385 ms                                                       | 388 ms: 1.01x slower                                        |
| spectral_norm           | 91.6 ms                                                      | 92.4 ms: 1.01x slower                                       |
| pathlib                 | 19.8 ms                                                      | 20.0 ms: 1.01x slower                                       |
| xml_etree_process       | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                       |
| coroutines              | 23.0 ms                                                      | 23.3 ms: 1.01x slower                                       |
| meteor_contest          | 128 ms                                                       | 130 ms: 1.01x slower                                        |
| chaos                   | 62.9 ms                                                      | 63.8 ms: 1.02x slower                                       |
| deepcopy_memo           | 37.4 us                                                      | 38.0 us: 1.02x slower                                       |
| xml_etree_parse         | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| create_gc_cycles        | 1.67 ms                                                      | 1.71 ms: 1.02x slower                                       |
| xml_etree_iterparse     | 103 ms                                                       | 105 ms: 1.02x slower                                        |
| regex_compile           | 146 ms                                                       | 149 ms: 1.03x slower                                        |
| pickle_dict             | 31.7 us                                                      | 32.6 us: 1.03x slower                                       |
| json_loads              | 24.3 us                                                      | 24.9 us: 1.03x slower                                       |
| regex_dna               | 241 ms                                                       | 247 ms: 1.03x slower                                        |
| json_dumps              | 10.2 ms                                                      | 10.6 ms: 1.03x slower                                       |
| mako                    | 9.94 ms                                                      | 10.3 ms: 1.03x slower                                       |
| async_tree_io           | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                      |
| logging_simple          | 6.73 us                                                      | 6.97 us: 1.04x slower                                       |
| deepcopy                | 376 us                                                       | 392 us: 1.04x slower                                        |
| pycparser               | 1.27 sec                                                     | 1.33 sec: 1.05x slower                                      |
| float                   | 78.5 ms                                                      | 82.3 ms: 1.05x slower                                       |
| tomli_loads             | 2.20 sec                                                     | 2.31 sec: 1.05x slower                                      |
| logging_format          | 7.37 us                                                      | 7.75 us: 1.05x slower                                       |
| unpickle_pure_python    | 207 us                                                       | 218 us: 1.05x slower                                        |
| dulwich_log             | 65.3 ms                                                      | 68.9 ms: 1.05x slower                                       |
| python_startup          | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                       |
| hexiom                  | 5.96 ms                                                      | 6.49 ms: 1.09x slower                                       |
| deltablue               | 3.29 ms                                                      | 3.65 ms: 1.11x slower                                       |
| go                      | 150 ms                                                       | 167 ms: 1.11x slower                                        |
| fannkuch                | 350 ms                                                       | 396 ms: 1.13x slower                                        |
| pyflate                 | 447 ms                                                       | 511 ms: 1.14x slower                                        |
| telco                   | 6.96 ms                                                      | 8.03 ms: 1.15x slower                                       |
| richards_super          | 51.7 ms                                                      | 60.9 ms: 1.18x slower                                       |
| gc_traversal            | 3.54 ms                                                      | 4.19 ms: 1.18x slower                                       |
| richards                | 45.0 ms                                                      | 54.3 ms: 1.21x slower                                       |
| mypy2                   | 368 ms                                                       | 461 ms: 1.25x slower                                        |
| scimark_sor             | 110 ms                                                       | 150 ms: 1.36x slower                                        |
| Geometric mean          | (ref)                                                        | 1.02x slower                                                |

Benchmark hidden because not significant (6): xml_etree_generate, unpack_sequence, json, async_tree_cpu_io_mixed, async_tree_memoization, typing_runtime_protocols
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 97.61% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
