
# Results vs. 3.12.0

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: linux-x86_64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.02x slower
- HPT reliability: 97.35%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                                      |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 87.0 ms: 1.08x faster                                                       |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                                        |
| float          | 78.5 ms                                                      | 81.1 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.47 ms                                                      | 3.42 ms: 1.02x faster                                                       |
| regex_dna      | 241 ms                                                       | 239 ms: 1.01x faster                                                        |
| regex_v8       | 25.0 ms                                                      | 24.8 ms: 1.01x faster                                                       |
| regex_compile  | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.15 us: 1.06x faster                                                       |
| unpickle             | 14.8 us                                                      | 14.3 us: 1.04x faster                                                       |
| pickle_pure_python   | 323 us                                                       | 313 us: 1.03x faster                                                        |
| pickle               | 10.1 us                                                      | 9.94 us: 1.02x faster                                                       |
| unpickle_list        | 4.77 us                                                      | 4.72 us: 1.01x faster                                                       |
| xml_etree_process    | 58.3 ms                                                      | 58.6 ms: 1.00x slower                                                       |
| tomli_loads          | 2.20 sec                                                     | 2.22 sec: 1.01x slower                                                      |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| pickle_dict          | 31.7 us                                                      | 32.3 us: 1.02x slower                                                       |
| xml_etree_iterparse  | 103 ms                                                       | 107 ms: 1.03x slower                                                        |
| json_loads           | 24.3 us                                                      | 25.1 us: 1.03x slower                                                       |
| json_dumps           | 10.2 ms                                                      | 10.7 ms: 1.04x slower                                                       |
| unpickle_pure_python | 207 us                                                       | 222 us: 1.08x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.65 ms: 1.01x faster                                                       |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.03x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.5 ms: 1.05x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.66 ms: 1.15x faster                                                       |
| raytrace                 | 302 ms                                                       | 267 ms: 1.13x faster                                                        |
| crypto_pyaes             | 80.9 ms                                                      | 71.7 ms: 1.13x faster                                                       |
| coverage                 | 89.6 ms                                                      | 81.3 ms: 1.10x faster                                                       |
| unpack_sequence          | 53.3 ns                                                      | 48.7 ns: 1.09x faster                                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 66.3 ms: 1.09x faster                                                       |
| nbody                    | 94.1 ms                                                      | 87.0 ms: 1.08x faster                                                       |
| generators               | 36.7 ms                                                      | 34.7 ms: 1.06x faster                                                       |
| pickle_list              | 4.39 us                                                      | 4.15 us: 1.06x faster                                                       |
| async_tree_none          | 459 ms                                                       | 437 ms: 1.05x faster                                                        |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.24 ms: 1.04x faster                                                       |
| unpickle                 | 14.8 us                                                      | 14.3 us: 1.04x faster                                                       |
| pickle_pure_python       | 323 us                                                       | 313 us: 1.03x faster                                                        |
| asyncio_tcp              | 381 ms                                                       | 372 ms: 1.03x faster                                                        |
| pprint_safe_repr         | 823 ms                                                       | 806 ms: 1.02x faster                                                        |
| create_gc_cycles         | 1.67 ms                                                      | 1.64 ms: 1.02x faster                                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.39 us: 1.02x faster                                                       |
| typing_runtime_protocols | 151 us                                                       | 148 us: 1.02x faster                                                        |
| sqlglot_normalize        | 117 ms                                                       | 115 ms: 1.02x faster                                                        |
| pickle                   | 10.1 us                                                      | 9.94 us: 1.02x faster                                                       |
| regex_effbot             | 3.47 ms                                                      | 3.42 ms: 1.02x faster                                                       |
| pprint_pformat           | 1.67 sec                                                     | 1.65 sec: 1.01x faster                                                      |
| unpickle_list            | 4.77 us                                                      | 4.72 us: 1.01x faster                                                       |
| scimark_fft              | 304 ms                                                       | 301 ms: 1.01x faster                                                        |
| regex_dna                | 241 ms                                                       | 239 ms: 1.01x faster                                                        |
| regex_v8                 | 25.0 ms                                                      | 24.8 ms: 1.01x faster                                                       |
| docutils                 | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                                      |
| pathlib                  | 19.8 ms                                                      | 19.7 ms: 1.01x faster                                                       |
| python_startup_no_site   | 8.70 ms                                                      | 8.65 ms: 1.01x faster                                                       |
| pidigits                 | 264 ms                                                       | 264 ms: 1.00x slower                                                        |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                      |
| mypy2                    | 368 ms                                                       | 370 ms: 1.00x slower                                                        |
| xml_etree_process        | 58.3 ms                                                      | 58.6 ms: 1.00x slower                                                       |
| scimark_lu               | 101 ms                                                       | 101 ms: 1.01x slower                                                        |
| sqlglot_transpile        | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                                       |
| mdp                      | 2.53 sec                                                     | 2.55 sec: 1.01x slower                                                      |
| sqlglot_parse            | 1.40 ms                                                      | 1.42 ms: 1.01x slower                                                       |
| meteor_contest           | 128 ms                                                       | 129 ms: 1.01x slower                                                        |
| tomli_loads              | 2.20 sec                                                     | 2.22 sec: 1.01x slower                                                      |
| sqlglot_optimize         | 57.8 ms                                                      | 58.4 ms: 1.01x slower                                                       |
| spectral_norm            | 91.6 ms                                                      | 92.6 ms: 1.01x slower                                                       |
| chaos                    | 62.9 ms                                                      | 63.6 ms: 1.01x slower                                                       |
| deepcopy_memo            | 37.4 us                                                      | 37.8 us: 1.01x slower                                                       |
| logging_simple           | 6.73 us                                                      | 6.83 us: 1.01x slower                                                       |
| xml_etree_parse          | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| logging_format           | 7.37 us                                                      | 7.49 us: 1.02x slower                                                       |
| deepcopy                 | 376 us                                                       | 382 us: 1.02x slower                                                        |
| async_generators         | 385 ms                                                       | 392 ms: 1.02x slower                                                        |
| sqlite_synth             | 2.70 us                                                      | 2.75 us: 1.02x slower                                                       |
| pickle_dict              | 31.7 us                                                      | 32.3 us: 1.02x slower                                                       |
| regex_compile            | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| logging_silent           | 95.6 ns                                                      | 97.7 ns: 1.02x slower                                                       |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                                      |
| comprehensions           | 21.9 us                                                      | 22.6 us: 1.03x slower                                                       |
| xml_etree_iterparse      | 103 ms                                                       | 107 ms: 1.03x slower                                                        |
| float                    | 78.5 ms                                                      | 81.1 ms: 1.03x slower                                                       |
| json_loads               | 24.3 us                                                      | 25.1 us: 1.03x slower                                                       |
| json_dumps               | 10.2 ms                                                      | 10.7 ms: 1.04x slower                                                       |
| pycparser                | 1.27 sec                                                     | 1.33 sec: 1.04x slower                                                      |
| mako                     | 9.94 ms                                                      | 10.5 ms: 1.05x slower                                                       |
| dulwich_log              | 65.3 ms                                                      | 69.3 ms: 1.06x slower                                                       |
| unpickle_pure_python     | 207 us                                                       | 222 us: 1.08x slower                                                        |
| python_startup           | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                       |
| hexiom                   | 5.96 ms                                                      | 6.47 ms: 1.09x slower                                                       |
| deltablue                | 3.29 ms                                                      | 3.69 ms: 1.12x slower                                                       |
| go                       | 150 ms                                                       | 170 ms: 1.13x slower                                                        |
| fannkuch                 | 350 ms                                                       | 397 ms: 1.13x slower                                                        |
| pyflate                  | 447 ms                                                       | 516 ms: 1.15x slower                                                        |
| richards_super           | 51.7 ms                                                      | 60.7 ms: 1.17x slower                                                       |
| telco                    | 6.96 ms                                                      | 8.20 ms: 1.18x slower                                                       |
| richards                 | 45.0 ms                                                      | 54.0 ms: 1.20x slower                                                       |
| scimark_sor              | 110 ms                                                       | 148 ms: 1.35x slower                                                        |
| dask                     | 397 ms                                                       | 588 ms: 1.48x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.02x slower                                                                |

Benchmark hidden because not significant (9): bench_thread_pool, tornado_http, async_tree_memoization, xml_etree_generate, nqueens, async_tree_cpu_io_mixed, json, gc_traversal, coroutines
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 97.35% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
