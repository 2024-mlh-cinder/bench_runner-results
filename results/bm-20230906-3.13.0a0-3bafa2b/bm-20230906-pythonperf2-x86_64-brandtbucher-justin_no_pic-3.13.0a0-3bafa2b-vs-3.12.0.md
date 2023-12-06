
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.93 sec: 1.02x slower                                                     |
| Geometric mean | (ref)                                                        | 1.01x slower                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                                       |
| float          | 78.5 ms                                                      | 82.0 ms: 1.04x slower                                                      |
| Geometric mean | (ref)                                                        | 1.01x slower                                                               |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 25.2 ms: 1.01x slower                                                      |
| regex_dna      | 241 ms                                                       | 244 ms: 1.01x slower                                                       |
| regex_effbot   | 3.47 ms                                                      | 3.58 ms: 1.03x slower                                                      |
| regex_compile  | 146 ms                                                       | 154 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                        | 1.03x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.4 us: 1.02x faster                                                      |
| pickle_pure_python   | 323 us                                                       | 316 us: 1.02x faster                                                       |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                      |
| json_dumps           | 10.2 ms                                                      | 10.3 ms: 1.01x slower                                                      |
| json_loads           | 24.3 us                                                      | 24.6 us: 1.02x slower                                                      |
| xml_etree_process    | 58.3 ms                                                      | 59.5 ms: 1.02x slower                                                      |
| pickle_list          | 4.39 us                                                      | 4.49 us: 1.02x slower                                                      |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.03x slower                                                       |
| pickle_dict          | 31.7 us                                                      | 32.7 us: 1.03x slower                                                      |
| tomli_loads          | 2.20 sec                                                     | 2.29 sec: 1.04x slower                                                     |
| unpickle_pure_python | 207 us                                                       | 241 us: 1.16x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                               |

Benchmark hidden because not significant (3): xml_etree_generate, unpickle_list, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 11.9 ms: 1.01x slower                                                      |
| python_startup_no_site | 8.70 ms                                                      | 8.86 ms: 1.02x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.02x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.5 ms: 1.06x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| crypto_pyaes             | 80.9 ms                                                      | 74.0 ms: 1.09x faster                                                      |
| raytrace                 | 302 ms                                                       | 276 ms: 1.09x faster                                                       |
| coverage                 | 89.6 ms                                                      | 82.8 ms: 1.08x faster                                                      |
| create_gc_cycles         | 1.67 ms                                                      | 1.57 ms: 1.07x faster                                                      |
| bench_mp_pool            | 5.34 ms                                                      | 5.02 ms: 1.06x faster                                                      |
| scimark_monte_carlo      | 72.4 ms                                                      | 68.3 ms: 1.06x faster                                                      |
| unpack_sequence          | 53.3 ns                                                      | 50.6 ns: 1.05x faster                                                      |
| async_tree_none          | 459 ms                                                       | 438 ms: 1.05x faster                                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.36 us: 1.03x faster                                                      |
| unpickle                 | 14.8 us                                                      | 14.4 us: 1.02x faster                                                      |
| pprint_safe_repr         | 823 ms                                                       | 804 ms: 1.02x faster                                                       |
| pprint_pformat           | 1.67 sec                                                     | 1.64 sec: 1.02x faster                                                     |
| asyncio_tcp              | 381 ms                                                       | 374 ms: 1.02x faster                                                       |
| pickle_pure_python       | 323 us                                                       | 316 us: 1.02x faster                                                       |
| coroutines               | 23.0 ms                                                      | 22.6 ms: 1.02x faster                                                      |
| json                     | 5.14 ms                                                      | 5.07 ms: 1.01x faster                                                      |
| pidigits                 | 264 ms                                                       | 264 ms: 1.00x slower                                                       |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                     |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                      |
| regex_v8                 | 25.0 ms                                                      | 25.2 ms: 1.01x slower                                                      |
| json_dumps               | 10.2 ms                                                      | 10.3 ms: 1.01x slower                                                      |
| pathlib                  | 19.8 ms                                                      | 20.0 ms: 1.01x slower                                                      |
| regex_dna                | 241 ms                                                       | 244 ms: 1.01x slower                                                       |
| typing_runtime_protocols | 151 us                                                       | 153 us: 1.01x slower                                                       |
| python_startup           | 11.7 ms                                                      | 11.9 ms: 1.01x slower                                                      |
| sqlite_synth             | 2.70 us                                                      | 2.74 us: 1.02x slower                                                      |
| docutils                 | 2.89 sec                                                     | 2.93 sec: 1.02x slower                                                     |
| json_loads               | 24.3 us                                                      | 24.6 us: 1.02x slower                                                      |
| python_startup_no_site   | 8.70 ms                                                      | 8.86 ms: 1.02x slower                                                      |
| xml_etree_process        | 58.3 ms                                                      | 59.5 ms: 1.02x slower                                                      |
| deepcopy                 | 376 us                                                       | 384 us: 1.02x slower                                                       |
| sqlglot_normalize        | 117 ms                                                       | 120 ms: 1.02x slower                                                       |
| pickle_list              | 4.39 us                                                      | 4.49 us: 1.02x slower                                                      |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                                     |
| logging_silent           | 95.6 ns                                                      | 98.1 ns: 1.03x slower                                                      |
| regex_effbot             | 3.47 ms                                                      | 3.58 ms: 1.03x slower                                                      |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.03x slower                                                       |
| mypy2                    | 368 ms                                                       | 380 ms: 1.03x slower                                                       |
| pickle_dict              | 31.7 us                                                      | 32.7 us: 1.03x slower                                                      |
| scimark_lu               | 101 ms                                                       | 104 ms: 1.03x slower                                                       |
| deepcopy_memo            | 37.4 us                                                      | 38.7 us: 1.03x slower                                                      |
| spectral_norm            | 91.6 ms                                                      | 94.8 ms: 1.03x slower                                                      |
| mdp                      | 2.53 sec                                                     | 2.62 sec: 1.04x slower                                                     |
| sqlglot_transpile        | 1.80 ms                                                      | 1.87 ms: 1.04x slower                                                      |
| sqlglot_parse            | 1.40 ms                                                      | 1.46 ms: 1.04x slower                                                      |
| chaos                    | 62.9 ms                                                      | 65.3 ms: 1.04x slower                                                      |
| gc_traversal             | 3.54 ms                                                      | 3.68 ms: 1.04x slower                                                      |
| tomli_loads              | 2.20 sec                                                     | 2.29 sec: 1.04x slower                                                     |
| float                    | 78.5 ms                                                      | 82.0 ms: 1.04x slower                                                      |
| pycparser                | 1.27 sec                                                     | 1.34 sec: 1.05x slower                                                     |
| sqlglot_optimize         | 57.8 ms                                                      | 60.6 ms: 1.05x slower                                                      |
| regex_compile            | 146 ms                                                       | 154 ms: 1.06x slower                                                       |
| mako                     | 9.94 ms                                                      | 10.5 ms: 1.06x slower                                                      |
| dulwich_log              | 65.3 ms                                                      | 69.9 ms: 1.07x slower                                                      |
| meteor_contest           | 128 ms                                                       | 137 ms: 1.07x slower                                                       |
| async_generators         | 385 ms                                                       | 416 ms: 1.08x slower                                                       |
| scimark_fft              | 304 ms                                                       | 329 ms: 1.08x slower                                                       |
| nqueens                  | 90.1 ms                                                      | 98.5 ms: 1.09x slower                                                      |
| pyflate                  | 447 ms                                                       | 495 ms: 1.11x slower                                                       |
| comprehensions           | 21.9 us                                                      | 24.7 us: 1.13x slower                                                      |
| deltablue                | 3.29 ms                                                      | 3.75 ms: 1.14x slower                                                      |
| go                       | 150 ms                                                       | 175 ms: 1.16x slower                                                       |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 5.15 ms: 1.16x slower                                                      |
| unpickle_pure_python     | 207 us                                                       | 241 us: 1.16x slower                                                       |
| fannkuch                 | 350 ms                                                       | 410 ms: 1.17x slower                                                       |
| telco                    | 6.96 ms                                                      | 8.19 ms: 1.18x slower                                                      |
| richards_super           | 51.7 ms                                                      | 60.9 ms: 1.18x slower                                                      |
| hexiom                   | 5.96 ms                                                      | 7.03 ms: 1.18x slower                                                      |
| richards                 | 45.0 ms                                                      | 53.4 ms: 1.19x slower                                                      |
| scimark_sor              | 110 ms                                                       | 148 ms: 1.34x slower                                                       |
| dask                     | 397 ms                                                       | 593 ms: 1.49x slower                                                       |
| Geometric mean           | (ref)                                                        | 1.04x slower                                                               |

Benchmark hidden because not significant (11): nbody, async_tree_cpu_io_mixed, logging_format, tornado_http, async_tree_memoization, xml_etree_generate, generators, logging_simple, unpickle_list, xml_etree_parse, bench_thread_pool
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
