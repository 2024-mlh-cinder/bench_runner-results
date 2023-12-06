
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.02x slower
- HPT reliability: 99.69%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.86 sec: 1.01x faster                                      |
| Geometric mean | (ref)                                                        | 1.01x faster                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 89.7 ms: 1.05x faster                                       |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                        |
| float          | 78.5 ms                                                      | 80.9 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 24.5 ms: 1.02x faster                                       |
| regex_dna      | 241 ms                                                       | 238 ms: 1.01x faster                                        |
| regex_compile  | 146 ms                                                       | 148 ms: 1.02x slower                                        |
| regex_effbot   | 3.47 ms                                                      | 3.55 ms: 1.02x slower                                       |
| Geometric mean | (ref)                                                        | 1.00x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.5 us: 1.02x faster                                       |
| unpickle_list        | 4.77 us                                                      | 4.68 us: 1.02x faster                                       |
| pickle_pure_python   | 323 us                                                       | 317 us: 1.02x faster                                        |
| pickle               | 10.1 us                                                      | 9.95 us: 1.01x faster                                       |
| pickle_dict          | 31.7 us                                                      | 31.9 us: 1.01x slower                                       |
| xml_etree_parse      | 146 ms                                                       | 148 ms: 1.01x slower                                        |
| pickle_list          | 4.39 us                                                      | 4.43 us: 1.01x slower                                       |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                       |
| xml_etree_process    | 58.3 ms                                                      | 59.4 ms: 1.02x slower                                       |
| xml_etree_iterparse  | 103 ms                                                       | 105 ms: 1.02x slower                                        |
| json_loads           | 24.3 us                                                      | 25.0 us: 1.03x slower                                       |
| tomli_loads          | 2.20 sec                                                     | 2.30 sec: 1.05x slower                                      |
| unpickle_pure_python | 207 us                                                       | 231 us: 1.12x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                       |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                       |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.4 ms: 1.04x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf2-x86_64-python-main-3.13.0a0-51863b7 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| crypto_pyaes             | 80.9 ms                                                      | 72.0 ms: 1.12x faster                                       |
| raytrace                 | 302 ms                                                       | 269 ms: 1.12x faster                                        |
| coverage                 | 89.6 ms                                                      | 80.6 ms: 1.11x faster                                       |
| bench_mp_pool            | 5.34 ms                                                      | 4.84 ms: 1.10x faster                                       |
| async_tree_none          | 459 ms                                                       | 433 ms: 1.06x faster                                        |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.18 ms: 1.06x faster                                       |
| nbody                    | 94.1 ms                                                      | 89.7 ms: 1.05x faster                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 69.6 ms: 1.04x faster                                       |
| bench_thread_pool        | 980 us                                                       | 944 us: 1.04x faster                                        |
| generators               | 36.7 ms                                                      | 35.3 ms: 1.04x faster                                       |
| asyncio_tcp              | 381 ms                                                       | 370 ms: 1.03x faster                                        |
| unpack_sequence          | 53.3 ns                                                      | 52.1 ns: 1.02x faster                                       |
| unpickle                 | 14.8 us                                                      | 14.5 us: 1.02x faster                                       |
| unpickle_list            | 4.77 us                                                      | 4.68 us: 1.02x faster                                       |
| pickle_pure_python       | 323 us                                                       | 317 us: 1.02x faster                                        |
| sqlglot_normalize        | 117 ms                                                       | 115 ms: 1.02x faster                                        |
| regex_v8                 | 25.0 ms                                                      | 24.5 ms: 1.02x faster                                       |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 696 ms: 1.02x faster                                        |
| pickle                   | 10.1 us                                                      | 9.95 us: 1.01x faster                                       |
| nqueens                  | 90.1 ms                                                      | 88.8 ms: 1.01x faster                                       |
| regex_dna                | 241 ms                                                       | 238 ms: 1.01x faster                                        |
| async_tree_memoization   | 553 ms                                                       | 547 ms: 1.01x faster                                        |
| deepcopy_memo            | 37.4 us                                                      | 37.1 us: 1.01x faster                                       |
| docutils                 | 2.89 sec                                                     | 2.86 sec: 1.01x faster                                      |
| deepcopy_reduce          | 3.46 us                                                      | 3.43 us: 1.01x faster                                       |
| typing_runtime_protocols | 151 us                                                       | 150 us: 1.01x faster                                        |
| python_startup_no_site   | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                       |
| pidigits                 | 264 ms                                                       | 264 ms: 1.00x slower                                        |
| scimark_fft              | 304 ms                                                       | 305 ms: 1.00x slower                                        |
| deepcopy                 | 376 us                                                       | 377 us: 1.00x slower                                        |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.01x slower                                      |
| mypy2                    | 368 ms                                                       | 370 ms: 1.01x slower                                        |
| mdp                      | 2.53 sec                                                     | 2.55 sec: 1.01x slower                                      |
| pickle_dict              | 31.7 us                                                      | 31.9 us: 1.01x slower                                       |
| sqlite_synth             | 2.70 us                                                      | 2.72 us: 1.01x slower                                       |
| pprint_pformat           | 1.67 sec                                                     | 1.69 sec: 1.01x slower                                      |
| pprint_safe_repr         | 823 ms                                                       | 830 ms: 1.01x slower                                        |
| sqlglot_optimize         | 57.8 ms                                                      | 58.3 ms: 1.01x slower                                       |
| xml_etree_parse          | 146 ms                                                       | 148 ms: 1.01x slower                                        |
| pathlib                  | 19.8 ms                                                      | 20.0 ms: 1.01x slower                                       |
| pickle_list              | 4.39 us                                                      | 4.43 us: 1.01x slower                                       |
| logging_silent           | 95.6 ns                                                      | 96.8 ns: 1.01x slower                                       |
| scimark_lu               | 101 ms                                                       | 102 ms: 1.01x slower                                        |
| create_gc_cycles         | 1.67 ms                                                      | 1.70 ms: 1.01x slower                                       |
| regex_compile            | 146 ms                                                       | 148 ms: 1.02x slower                                        |
| chaos                    | 62.9 ms                                                      | 63.8 ms: 1.02x slower                                       |
| gc_traversal             | 3.54 ms                                                      | 3.60 ms: 1.02x slower                                       |
| pycparser                | 1.27 sec                                                     | 1.30 sec: 1.02x slower                                      |
| coroutines               | 23.0 ms                                                      | 23.4 ms: 1.02x slower                                       |
| async_tree_io            | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                      |
| json_dumps               | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                       |
| xml_etree_process        | 58.3 ms                                                      | 59.4 ms: 1.02x slower                                       |
| xml_etree_iterparse      | 103 ms                                                       | 105 ms: 1.02x slower                                        |
| regex_effbot             | 3.47 ms                                                      | 3.55 ms: 1.02x slower                                       |
| logging_format           | 7.37 us                                                      | 7.55 us: 1.02x slower                                       |
| meteor_contest           | 128 ms                                                       | 131 ms: 1.03x slower                                        |
| spectral_norm            | 91.6 ms                                                      | 94.2 ms: 1.03x slower                                       |
| float                    | 78.5 ms                                                      | 80.9 ms: 1.03x slower                                       |
| json_loads               | 24.3 us                                                      | 25.0 us: 1.03x slower                                       |
| logging_simple           | 6.73 us                                                      | 6.95 us: 1.03x slower                                       |
| mako                     | 9.94 ms                                                      | 10.4 ms: 1.04x slower                                       |
| async_generators         | 385 ms                                                       | 402 ms: 1.04x slower                                        |
| tomli_loads              | 2.20 sec                                                     | 2.30 sec: 1.05x slower                                      |
| dulwich_log              | 65.3 ms                                                      | 68.4 ms: 1.05x slower                                       |
| hexiom                   | 5.96 ms                                                      | 6.40 ms: 1.07x slower                                       |
| python_startup           | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                       |
| go                       | 150 ms                                                       | 167 ms: 1.11x slower                                        |
| unpickle_pure_python     | 207 us                                                       | 231 us: 1.12x slower                                        |
| deltablue                | 3.29 ms                                                      | 3.69 ms: 1.12x slower                                       |
| fannkuch                 | 350 ms                                                       | 395 ms: 1.13x slower                                        |
| pyflate                  | 447 ms                                                       | 510 ms: 1.14x slower                                        |
| richards_super           | 51.7 ms                                                      | 59.2 ms: 1.15x slower                                       |
| telco                    | 6.96 ms                                                      | 8.01 ms: 1.15x slower                                       |
| richards                 | 45.0 ms                                                      | 53.5 ms: 1.19x slower                                       |
| scimark_sor              | 110 ms                                                       | 150 ms: 1.37x slower                                        |
| dask                     | 397 ms                                                       | 587 ms: 1.48x slower                                        |
| Geometric mean           | (ref)                                                        | 1.02x slower                                                |

Benchmark hidden because not significant (6): tornado_http, json, sqlglot_parse, comprehensions, sqlglot_transpile, xml_etree_generate
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 99.69% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
