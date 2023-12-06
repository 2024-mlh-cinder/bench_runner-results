
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.97 sec: 1.03x slower                                              |
| Geometric mean | (ref)                                                        | 1.02x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                                |
| float          | 78.5 ms                                                      | 83.2 ms: 1.06x slower                                               |
| Geometric mean | (ref)                                                        | 1.03x slower                                                        |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 241 ms: 1.00x slower                                                |
| regex_v8       | 25.0 ms                                                      | 25.9 ms: 1.04x slower                                               |
| regex_effbot   | 3.47 ms                                                      | 3.64 ms: 1.05x slower                                               |
| regex_compile  | 146 ms                                                       | 157 ms: 1.08x slower                                                |
| Geometric mean | (ref)                                                        | 1.04x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                      | 4.57 us: 1.04x faster                                               |
| pickle_pure_python   | 323 us                                                       | 319 us: 1.01x faster                                                |
| xml_etree_generate   | 86.1 ms                                                      | 87.0 ms: 1.01x slower                                               |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                               |
| unpickle             | 14.8 us                                                      | 15.0 us: 1.02x slower                                               |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                               |
| xml_etree_process    | 58.3 ms                                                      | 59.4 ms: 1.02x slower                                               |
| pickle_list          | 4.39 us                                                      | 4.52 us: 1.03x slower                                               |
| xml_etree_iterparse  | 103 ms                                                       | 108 ms: 1.05x slower                                                |
| json_loads           | 24.3 us                                                      | 25.4 us: 1.05x slower                                               |
| pickle_dict          | 31.7 us                                                      | 33.7 us: 1.06x slower                                               |
| tomli_loads          | 2.20 sec                                                     | 2.42 sec: 1.10x slower                                              |
| unpickle_pure_python | 207 us                                                       | 246 us: 1.19x slower                                                |
| Geometric mean       | (ref)                                                        | 1.04x slower                                                        |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 11.9 ms: 1.02x slower                                               |
| python_startup_no_site | 8.70 ms                                                      | 8.86 ms: 1.02x slower                                               |
| Geometric mean         | (ref)                                                        | 1.02x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.9 ms: 1.09x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.77 ms: 1.12x faster                                               |
| coverage                 | 89.6 ms                                                      | 83.0 ms: 1.08x faster                                               |
| raytrace                 | 302 ms                                                       | 279 ms: 1.08x faster                                                |
| crypto_pyaes             | 80.9 ms                                                      | 76.9 ms: 1.05x faster                                               |
| create_gc_cycles         | 1.67 ms                                                      | 1.60 ms: 1.05x faster                                               |
| unpickle_list            | 4.77 us                                                      | 4.57 us: 1.04x faster                                               |
| unpack_sequence          | 53.3 ns                                                      | 51.1 ns: 1.04x faster                                               |
| asyncio_tcp              | 381 ms                                                       | 372 ms: 1.02x faster                                                |
| async_tree_none          | 459 ms                                                       | 449 ms: 1.02x faster                                                |
| coroutines               | 23.0 ms                                                      | 22.7 ms: 1.01x faster                                               |
| pickle_pure_python       | 323 us                                                       | 319 us: 1.01x faster                                                |
| scimark_monte_carlo      | 72.4 ms                                                      | 71.7 ms: 1.01x faster                                               |
| generators               | 36.7 ms                                                      | 36.6 ms: 1.00x faster                                               |
| regex_dna                | 241 ms                                                       | 241 ms: 1.00x slower                                                |
| pprint_pformat           | 1.67 sec                                                     | 1.68 sec: 1.00x slower                                              |
| pidigits                 | 264 ms                                                       | 265 ms: 1.00x slower                                                |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                              |
| deepcopy_reduce          | 3.46 us                                                      | 3.48 us: 1.01x slower                                               |
| logging_format           | 7.37 us                                                      | 7.43 us: 1.01x slower                                               |
| pathlib                  | 19.8 ms                                                      | 20.0 ms: 1.01x slower                                               |
| json                     | 5.14 ms                                                      | 5.19 ms: 1.01x slower                                               |
| xml_etree_generate       | 86.1 ms                                                      | 87.0 ms: 1.01x slower                                               |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 716 ms: 1.01x slower                                                |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                               |
| async_tree_memoization   | 553 ms                                                       | 562 ms: 1.02x slower                                                |
| python_startup           | 11.7 ms                                                      | 11.9 ms: 1.02x slower                                               |
| pycparser                | 1.27 sec                                                     | 1.30 sec: 1.02x slower                                              |
| unpickle                 | 14.8 us                                                      | 15.0 us: 1.02x slower                                               |
| python_startup_no_site   | 8.70 ms                                                      | 8.86 ms: 1.02x slower                                               |
| logging_simple           | 6.73 us                                                      | 6.86 us: 1.02x slower                                               |
| json_dumps               | 10.2 ms                                                      | 10.4 ms: 1.02x slower                                               |
| xml_etree_process        | 58.3 ms                                                      | 59.4 ms: 1.02x slower                                               |
| sqlite_synth             | 2.70 us                                                      | 2.77 us: 1.03x slower                                               |
| docutils                 | 2.89 sec                                                     | 2.97 sec: 1.03x slower                                              |
| pickle_list              | 4.39 us                                                      | 4.52 us: 1.03x slower                                               |
| sqlglot_parse            | 1.40 ms                                                      | 1.45 ms: 1.03x slower                                               |
| sqlglot_normalize        | 117 ms                                                       | 121 ms: 1.04x slower                                                |
| regex_v8                 | 25.0 ms                                                      | 25.9 ms: 1.04x slower                                               |
| sqlglot_transpile        | 1.80 ms                                                      | 1.87 ms: 1.04x slower                                               |
| bench_thread_pool        | 980 us                                                       | 1.02 ms: 1.04x slower                                               |
| async_tree_io            | 1.06 sec                                                     | 1.10 sec: 1.04x slower                                              |
| spectral_norm            | 91.6 ms                                                      | 95.3 ms: 1.04x slower                                               |
| logging_silent           | 95.6 ns                                                      | 99.7 ns: 1.04x slower                                               |
| xml_etree_iterparse      | 103 ms                                                       | 108 ms: 1.05x slower                                                |
| mypy2                    | 368 ms                                                       | 386 ms: 1.05x slower                                                |
| json_loads               | 24.3 us                                                      | 25.4 us: 1.05x slower                                               |
| regex_effbot             | 3.47 ms                                                      | 3.64 ms: 1.05x slower                                               |
| mdp                      | 2.53 sec                                                     | 2.67 sec: 1.05x slower                                              |
| deepcopy                 | 376 us                                                       | 396 us: 1.05x slower                                                |
| typing_runtime_protocols | 151 us                                                       | 160 us: 1.06x slower                                                |
| scimark_lu               | 101 ms                                                       | 107 ms: 1.06x slower                                                |
| float                    | 78.5 ms                                                      | 83.2 ms: 1.06x slower                                               |
| sqlglot_optimize         | 57.8 ms                                                      | 61.5 ms: 1.06x slower                                               |
| pickle_dict              | 31.7 us                                                      | 33.7 us: 1.06x slower                                               |
| dulwich_log              | 65.3 ms                                                      | 69.5 ms: 1.06x slower                                               |
| deepcopy_memo            | 37.4 us                                                      | 40.0 us: 1.07x slower                                               |
| async_generators         | 385 ms                                                       | 416 ms: 1.08x slower                                                |
| regex_compile            | 146 ms                                                       | 157 ms: 1.08x slower                                                |
| chaos                    | 62.9 ms                                                      | 68.4 ms: 1.09x slower                                               |
| meteor_contest           | 128 ms                                                       | 140 ms: 1.09x slower                                                |
| mako                     | 9.94 ms                                                      | 10.9 ms: 1.09x slower                                               |
| scimark_fft              | 304 ms                                                       | 333 ms: 1.10x slower                                                |
| tomli_loads              | 2.20 sec                                                     | 2.42 sec: 1.10x slower                                              |
| pyflate                  | 447 ms                                                       | 511 ms: 1.14x slower                                                |
| deltablue                | 3.29 ms                                                      | 3.79 ms: 1.15x slower                                               |
| nqueens                  | 90.1 ms                                                      | 104 ms: 1.16x slower                                                |
| gc_traversal             | 3.54 ms                                                      | 4.16 ms: 1.17x slower                                               |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 5.23 ms: 1.18x slower                                               |
| telco                    | 6.96 ms                                                      | 8.29 ms: 1.19x slower                                               |
| unpickle_pure_python     | 207 us                                                       | 246 us: 1.19x slower                                                |
| richards_super           | 51.7 ms                                                      | 61.7 ms: 1.19x slower                                               |
| comprehensions           | 21.9 us                                                      | 26.2 us: 1.20x slower                                               |
| go                       | 150 ms                                                       | 182 ms: 1.21x slower                                                |
| richards                 | 45.0 ms                                                      | 56.0 ms: 1.24x slower                                               |
| fannkuch                 | 350 ms                                                       | 438 ms: 1.25x slower                                                |
| hexiom                   | 5.96 ms                                                      | 7.51 ms: 1.26x slower                                               |
| scimark_sor              | 110 ms                                                       | 147 ms: 1.33x slower                                                |
| dask                     | 397 ms                                                       | 596 ms: 1.50x slower                                                |
| Geometric mean           | (ref)                                                        | 1.06x slower                                                        |

Benchmark hidden because not significant (4): pprint_safe_repr, xml_etree_parse, tornado_http, nbody
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
