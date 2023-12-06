
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 07fb485
- commit date: 2023-10-11
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.93 sec: 1.01x slower                                              |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                        | 1.02x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 265 ms: 1.01x slower                                                |
| nbody          | 94.1 ms                                                      | 100 ms: 1.06x slower                                                |
| float          | 78.5 ms                                                      | 88.8 ms: 1.13x slower                                               |
| Geometric mean | (ref)                                                        | 1.07x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 247 ms: 1.02x slower                                                |
| regex_effbot   | 3.47 ms                                                      | 3.62 ms: 1.04x slower                                               |
| regex_v8       | 25.0 ms                                                      | 26.6 ms: 1.07x slower                                               |
| regex_compile  | 146 ms                                                       | 159 ms: 1.09x slower                                                |
| Geometric mean | (ref)                                                        | 1.06x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.3 us: 1.03x faster                                               |
| unpickle_list        | 4.77 us                                                      | 4.68 us: 1.02x faster                                               |
| pickle_pure_python   | 323 us                                                       | 317 us: 1.02x faster                                                |
| pickle_list          | 4.39 us                                                      | 4.33 us: 1.01x faster                                               |
| pickle               | 10.1 us                                                      | 10.0 us: 1.01x faster                                               |
| xml_etree_process    | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                               |
| json_loads           | 24.3 us                                                      | 24.6 us: 1.02x slower                                               |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                                |
| pickle_dict          | 31.7 us                                                      | 32.8 us: 1.03x slower                                               |
| xml_etree_iterparse  | 103 ms                                                       | 107 ms: 1.04x slower                                                |
| json_dumps           | 10.2 ms                                                      | 10.8 ms: 1.05x slower                                               |
| tomli_loads          | 2.20 sec                                                     | 2.48 sec: 1.13x slower                                              |
| unpickle_pure_python | 207 us                                                       | 237 us: 1.14x slower                                                |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                        |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.69 ms: 1.00x faster                                               |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                               |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 12.1 ms: 1.22x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.74 ms: 1.13x faster                                               |
| coverage                 | 89.6 ms                                                      | 82.6 ms: 1.08x faster                                               |
| unpack_sequence          | 53.3 ns                                                      | 49.9 ns: 1.07x faster                                               |
| create_gc_cycles         | 1.67 ms                                                      | 1.60 ms: 1.05x faster                                               |
| raytrace                 | 302 ms                                                       | 291 ms: 1.04x faster                                                |
| unpickle                 | 14.8 us                                                      | 14.3 us: 1.03x faster                                               |
| async_tree_none          | 459 ms                                                       | 444 ms: 1.03x faster                                                |
| asyncio_tcp              | 381 ms                                                       | 371 ms: 1.03x faster                                                |
| deepcopy_reduce          | 3.46 us                                                      | 3.38 us: 1.02x faster                                               |
| unpickle_list            | 4.77 us                                                      | 4.68 us: 1.02x faster                                               |
| pickle_pure_python       | 323 us                                                       | 317 us: 1.02x faster                                                |
| pickle_list              | 4.39 us                                                      | 4.33 us: 1.01x faster                                               |
| generators               | 36.7 ms                                                      | 36.2 ms: 1.01x faster                                               |
| pickle                   | 10.1 us                                                      | 10.0 us: 1.01x faster                                               |
| python_startup_no_site   | 8.70 ms                                                      | 8.69 ms: 1.00x faster                                               |
| pidigits                 | 264 ms                                                       | 265 ms: 1.01x slower                                                |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.59 sec: 1.01x slower                                              |
| xml_etree_process        | 58.3 ms                                                      | 58.8 ms: 1.01x slower                                               |
| scimark_monte_carlo      | 72.4 ms                                                      | 73.3 ms: 1.01x slower                                               |
| docutils                 | 2.89 sec                                                     | 2.93 sec: 1.01x slower                                              |
| json_loads               | 24.3 us                                                      | 24.6 us: 1.02x slower                                               |
| spectral_norm            | 91.6 ms                                                      | 93.2 ms: 1.02x slower                                               |
| coroutines               | 23.0 ms                                                      | 23.4 ms: 1.02x slower                                               |
| pathlib                  | 19.8 ms                                                      | 20.2 ms: 1.02x slower                                               |
| xml_etree_parse          | 146 ms                                                       | 149 ms: 1.02x slower                                                |
| tornado_http             | 122 ms                                                       | 124 ms: 1.02x slower                                                |
| regex_dna                | 241 ms                                                       | 247 ms: 1.02x slower                                                |
| sqlglot_parse            | 1.40 ms                                                      | 1.44 ms: 1.03x slower                                               |
| sqlglot_transpile        | 1.80 ms                                                      | 1.86 ms: 1.03x slower                                               |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                              |
| typing_runtime_protocols | 151 us                                                       | 156 us: 1.03x slower                                                |
| sqlglot_optimize         | 57.8 ms                                                      | 59.6 ms: 1.03x slower                                               |
| logging_silent           | 95.6 ns                                                      | 98.8 ns: 1.03x slower                                               |
| pickle_dict              | 31.7 us                                                      | 32.8 us: 1.03x slower                                               |
| mdp                      | 2.53 sec                                                     | 2.62 sec: 1.03x slower                                              |
| scimark_lu               | 101 ms                                                       | 104 ms: 1.04x slower                                                |
| logging_simple           | 6.73 us                                                      | 6.97 us: 1.04x slower                                               |
| crypto_pyaes             | 80.9 ms                                                      | 83.9 ms: 1.04x slower                                               |
| mypy2                    | 368 ms                                                       | 382 ms: 1.04x slower                                                |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.59 ms: 1.04x slower                                               |
| xml_etree_iterparse      | 103 ms                                                       | 107 ms: 1.04x slower                                                |
| regex_effbot             | 3.47 ms                                                      | 3.62 ms: 1.04x slower                                               |
| logging_format           | 7.37 us                                                      | 7.73 us: 1.05x slower                                               |
| pycparser                | 1.27 sec                                                     | 1.34 sec: 1.05x slower                                              |
| json_dumps               | 10.2 ms                                                      | 10.8 ms: 1.05x slower                                               |
| deepcopy_memo            | 37.4 us                                                      | 39.5 us: 1.06x slower                                               |
| nbody                    | 94.1 ms                                                      | 100 ms: 1.06x slower                                                |
| dulwich_log              | 65.3 ms                                                      | 69.5 ms: 1.06x slower                                               |
| regex_v8                 | 25.0 ms                                                      | 26.6 ms: 1.07x slower                                               |
| meteor_contest           | 128 ms                                                       | 137 ms: 1.07x slower                                                |
| pprint_safe_repr         | 823 ms                                                       | 885 ms: 1.07x slower                                                |
| python_startup           | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                               |
| pprint_pformat           | 1.67 sec                                                     | 1.81 sec: 1.08x slower                                              |
| regex_compile            | 146 ms                                                       | 159 ms: 1.09x slower                                                |
| async_generators         | 385 ms                                                       | 422 ms: 1.09x slower                                                |
| chaos                    | 62.9 ms                                                      | 69.8 ms: 1.11x slower                                               |
| richards_super           | 51.7 ms                                                      | 57.6 ms: 1.11x slower                                               |
| tomli_loads              | 2.20 sec                                                     | 2.48 sec: 1.13x slower                                              |
| float                    | 78.5 ms                                                      | 88.8 ms: 1.13x slower                                               |
| nqueens                  | 90.1 ms                                                      | 102 ms: 1.13x slower                                                |
| unpickle_pure_python     | 207 us                                                       | 237 us: 1.14x slower                                                |
| richards                 | 45.0 ms                                                      | 51.6 ms: 1.15x slower                                               |
| go                       | 150 ms                                                       | 175 ms: 1.16x slower                                                |
| scimark_fft              | 304 ms                                                       | 361 ms: 1.19x slower                                                |
| pyflate                  | 447 ms                                                       | 534 ms: 1.19x slower                                                |
| telco                    | 6.96 ms                                                      | 8.32 ms: 1.19x slower                                               |
| mako                     | 9.94 ms                                                      | 12.1 ms: 1.22x slower                                               |
| fannkuch                 | 350 ms                                                       | 429 ms: 1.23x slower                                                |
| comprehensions           | 21.9 us                                                      | 28.5 us: 1.30x slower                                               |
| scimark_sor              | 110 ms                                                       | 148 ms: 1.34x slower                                                |
| deltablue                | 3.29 ms                                                      | 4.80 ms: 1.46x slower                                               |
| hexiom                   | 5.96 ms                                                      | 9.00 ms: 1.51x slower                                               |
| Geometric mean           | (ref)                                                        | 1.05x slower                                                        |

Benchmark hidden because not significant (9): gc_traversal, xml_etree_generate, sqlglot_normalize, deepcopy, sqlite_synth, bench_thread_pool, json, async_tree_memoization, async_tree_cpu_io_mixed
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
