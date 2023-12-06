
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.92 sec: 1.01x slower                                               |
| Geometric mean | (ref)                                                        | 1.01x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 88.9 ms: 1.06x faster                                                |
| Geometric mean | (ref)                                                        | 1.02x faster                                                         |

Benchmark hidden because not significant (2): float, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 25.5 ms: 1.02x slower                                                |
| regex_dna      | 241 ms                                                       | 247 ms: 1.03x slower                                                 |
| regex_compile  | 146 ms                                                       | 150 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 323 us                                                       | 315 us: 1.02x faster                                                 |
| unpickle             | 14.8 us                                                      | 14.7 us: 1.01x faster                                                |
| json_loads           | 24.3 us                                                      | 24.4 us: 1.01x slower                                                |
| xml_etree_generate   | 86.1 ms                                                      | 87.1 ms: 1.01x slower                                                |
| xml_etree_iterparse  | 103 ms                                                       | 105 ms: 1.02x slower                                                 |
| pickle_list          | 4.39 us                                                      | 4.48 us: 1.02x slower                                                |
| pickle               | 10.1 us                                                      | 10.3 us: 1.02x slower                                                |
| xml_etree_parse      | 146 ms                                                       | 150 ms: 1.02x slower                                                 |
| xml_etree_process    | 58.3 ms                                                      | 59.8 ms: 1.03x slower                                                |
| tomli_loads          | 2.20 sec                                                     | 2.27 sec: 1.03x slower                                               |
| json_dumps           | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                                |
| unpickle_pure_python | 207 us                                                       | 237 us: 1.15x slower                                                 |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (2): unpickle_list, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.75 ms: 1.01x slower                                                |
| python_startup         | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                                |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.6 ms: 1.06x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| create_gc_cycles         | 1.67 ms                                                      | 1.53 ms: 1.10x faster                                                |
| coverage                 | 89.6 ms                                                      | 83.1 ms: 1.08x faster                                                |
| bench_mp_pool            | 5.34 ms                                                      | 4.97 ms: 1.07x faster                                                |
| crypto_pyaes             | 80.9 ms                                                      | 76.3 ms: 1.06x faster                                                |
| nbody                    | 94.1 ms                                                      | 88.9 ms: 1.06x faster                                                |
| raytrace                 | 302 ms                                                       | 286 ms: 1.05x faster                                                 |
| async_tree_none          | 459 ms                                                       | 438 ms: 1.05x faster                                                 |
| asyncio_tcp              | 381 ms                                                       | 369 ms: 1.03x faster                                                 |
| deepcopy_reduce          | 3.46 us                                                      | 3.35 us: 1.03x faster                                                |
| pickle_pure_python       | 323 us                                                       | 315 us: 1.02x faster                                                 |
| unpack_sequence          | 53.3 ns                                                      | 52.5 ns: 1.02x faster                                                |
| generators               | 36.7 ms                                                      | 36.3 ms: 1.01x faster                                                |
| scimark_monte_carlo      | 72.4 ms                                                      | 71.8 ms: 1.01x faster                                                |
| pathlib                  | 19.8 ms                                                      | 19.6 ms: 1.01x faster                                                |
| unpickle                 | 14.8 us                                                      | 14.7 us: 1.01x faster                                                |
| json_loads               | 24.3 us                                                      | 24.4 us: 1.01x slower                                                |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.01x slower                                               |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.45 ms: 1.01x slower                                                |
| python_startup_no_site   | 8.70 ms                                                      | 8.75 ms: 1.01x slower                                                |
| sqlglot_normalize        | 117 ms                                                       | 118 ms: 1.01x slower                                                 |
| xml_etree_generate       | 86.1 ms                                                      | 87.1 ms: 1.01x slower                                                |
| docutils                 | 2.89 sec                                                     | 2.92 sec: 1.01x slower                                               |
| spectral_norm            | 91.6 ms                                                      | 92.8 ms: 1.01x slower                                                |
| deepcopy                 | 376 us                                                       | 381 us: 1.01x slower                                                 |
| pprint_safe_repr         | 823 ms                                                       | 836 ms: 1.02x slower                                                 |
| xml_etree_iterparse      | 103 ms                                                       | 105 ms: 1.02x slower                                                 |
| sqlglot_parse            | 1.40 ms                                                      | 1.43 ms: 1.02x slower                                                |
| logging_silent           | 95.6 ns                                                      | 97.4 ns: 1.02x slower                                                |
| pickle_list              | 4.39 us                                                      | 4.48 us: 1.02x slower                                                |
| mdp                      | 2.53 sec                                                     | 2.59 sec: 1.02x slower                                               |
| deepcopy_memo            | 37.4 us                                                      | 38.2 us: 1.02x slower                                                |
| pickle                   | 10.1 us                                                      | 10.3 us: 1.02x slower                                                |
| sqlglot_transpile        | 1.80 ms                                                      | 1.84 ms: 1.02x slower                                                |
| pprint_pformat           | 1.67 sec                                                     | 1.71 sec: 1.02x slower                                               |
| async_tree_io            | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                               |
| regex_v8                 | 25.0 ms                                                      | 25.5 ms: 1.02x slower                                                |
| xml_etree_parse          | 146 ms                                                       | 150 ms: 1.02x slower                                                 |
| pycparser                | 1.27 sec                                                     | 1.31 sec: 1.02x slower                                               |
| xml_etree_process        | 58.3 ms                                                      | 59.8 ms: 1.03x slower                                                |
| regex_dna                | 241 ms                                                       | 247 ms: 1.03x slower                                                 |
| regex_compile            | 146 ms                                                       | 150 ms: 1.03x slower                                                 |
| tomli_loads              | 2.20 sec                                                     | 2.27 sec: 1.03x slower                                               |
| gc_traversal             | 3.54 ms                                                      | 3.66 ms: 1.03x slower                                                |
| meteor_contest           | 128 ms                                                       | 132 ms: 1.04x slower                                                 |
| json_dumps               | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                                |
| sqlglot_optimize         | 57.8 ms                                                      | 60.1 ms: 1.04x slower                                                |
| typing_runtime_protocols | 151 us                                                       | 157 us: 1.04x slower                                                 |
| mypy2                    | 368 ms                                                       | 384 ms: 1.04x slower                                                 |
| async_generators         | 385 ms                                                       | 403 ms: 1.05x slower                                                 |
| scimark_lu               | 101 ms                                                       | 106 ms: 1.05x slower                                                 |
| mako                     | 9.94 ms                                                      | 10.6 ms: 1.06x slower                                                |
| dulwich_log              | 65.3 ms                                                      | 69.7 ms: 1.07x slower                                                |
| chaos                    | 62.9 ms                                                      | 67.1 ms: 1.07x slower                                                |
| python_startup           | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                                |
| nqueens                  | 90.1 ms                                                      | 98.0 ms: 1.09x slower                                                |
| scimark_fft              | 304 ms                                                       | 341 ms: 1.12x slower                                                 |
| richards_super           | 51.7 ms                                                      | 58.1 ms: 1.12x slower                                                |
| go                       | 150 ms                                                       | 170 ms: 1.13x slower                                                 |
| deltablue                | 3.29 ms                                                      | 3.72 ms: 1.13x slower                                                |
| fannkuch                 | 350 ms                                                       | 400 ms: 1.14x slower                                                 |
| unpickle_pure_python     | 207 us                                                       | 237 us: 1.15x slower                                                 |
| comprehensions           | 21.9 us                                                      | 25.2 us: 1.15x slower                                                |
| richards                 | 45.0 ms                                                      | 51.9 ms: 1.15x slower                                                |
| pyflate                  | 447 ms                                                       | 523 ms: 1.17x slower                                                 |
| telco                    | 6.96 ms                                                      | 8.16 ms: 1.17x slower                                                |
| hexiom                   | 5.96 ms                                                      | 7.42 ms: 1.25x slower                                                |
| scimark_sor              | 110 ms                                                       | 146 ms: 1.33x slower                                                 |
| Geometric mean           | (ref)                                                        | 1.03x slower                                                         |

Benchmark hidden because not significant (14): async_tree_cpu_io_mixed, async_tree_memoization, json, unpickle_list, logging_simple, float, pidigits, sqlite_synth, bench_thread_pool, pickle_dict, coroutines, tornado_http, logging_format, regex_effbot
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
