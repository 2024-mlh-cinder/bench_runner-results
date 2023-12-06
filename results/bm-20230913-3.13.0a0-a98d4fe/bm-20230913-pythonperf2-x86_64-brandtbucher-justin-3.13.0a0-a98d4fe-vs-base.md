
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.87 sec                                                                    | 2.95 sec: 1.03x slower                                              |
| tornado_http   | 121 ms                                                                      | 122 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 264 ms                                                                      | 266 ms: 1.01x slower                                                |
| float          | 81.1 ms                                                                     | 84.9 ms: 1.05x slower                                               |
| nbody          | 87.0 ms                                                                     | 127 ms: 1.46x slower                                                |
| Geometric mean | (ref)                                                                       | 1.15x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                                     | 3.50 ms: 1.02x slower                                               |
| regex_dna      | 239 ms                                                                      | 245 ms: 1.03x slower                                                |
| regex_v8       | 24.8 ms                                                                     | 26.3 ms: 1.06x slower                                               |
| regex_compile  | 149 ms                                                                      | 159 ms: 1.07x slower                                                |
| Geometric mean | (ref)                                                                       | 1.05x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle_list        | 4.72 us                                                                     | 4.57 us: 1.03x faster                                               |
| xml_etree_parse      | 149 ms                                                                      | 147 ms: 1.01x faster                                                |
| pickle_dict          | 32.3 us                                                                     | 32.2 us: 1.00x faster                                               |
| json_dumps           | 10.7 ms                                                                     | 10.7 ms: 1.00x faster                                               |
| xml_etree_generate   | 85.9 ms                                                                     | 85.7 ms: 1.00x faster                                               |
| pickle_pure_python   | 313 us                                                                      | 317 us: 1.01x slower                                                |
| xml_etree_process    | 58.6 ms                                                                     | 59.5 ms: 1.02x slower                                               |
| pickle               | 9.94 us                                                                     | 10.1 us: 1.02x slower                                               |
| pickle_list          | 4.15 us                                                                     | 4.30 us: 1.04x slower                                               |
| unpickle_pure_python | 222 us                                                                      | 232 us: 1.04x slower                                                |
| unpickle             | 14.3 us                                                                     | 14.9 us: 1.04x slower                                               |
| tomli_loads          | 2.22 sec                                                                    | 2.44 sec: 1.10x slower                                              |
| Geometric mean       | (ref)                                                                       | 1.02x slower                                                        |

Benchmark hidden because not significant (2): xml_etree_iterparse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 12.6 ms                                                                     | 12.7 ms: 1.01x slower                                               |
| python_startup_no_site | 8.65 ms                                                                     | 8.70 ms: 1.01x slower                                               |
| Geometric mean         | (ref)                                                                       | 1.01x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.5 ms                                                                     | 10.9 ms: 1.04x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle_list            | 4.72 us                                                                     | 4.57 us: 1.03x faster                                               |
| pycparser                | 1.33 sec                                                                    | 1.30 sec: 1.02x faster                                              |
| create_gc_cycles         | 1.64 ms                                                                     | 1.61 ms: 1.02x faster                                               |
| sqlite_synth             | 2.75 us                                                                     | 2.71 us: 1.01x faster                                               |
| pyflate                  | 516 ms                                                                      | 509 ms: 1.01x faster                                                |
| xml_etree_parse          | 149 ms                                                                      | 147 ms: 1.01x faster                                                |
| coverage                 | 81.3 ms                                                                     | 80.6 ms: 1.01x faster                                               |
| deepcopy_reduce          | 3.39 us                                                                     | 3.37 us: 1.01x faster                                               |
| pickle_dict              | 32.3 us                                                                     | 32.2 us: 1.00x faster                                               |
| json_dumps               | 10.7 ms                                                                     | 10.7 ms: 1.00x faster                                               |
| xml_etree_generate       | 85.9 ms                                                                     | 85.7 ms: 1.00x faster                                               |
| spectral_norm            | 92.6 ms                                                                     | 92.5 ms: 1.00x faster                                               |
| asyncio_tcp_ssl          | 1.58 sec                                                                    | 1.58 sec: 1.00x slower                                              |
| python_startup           | 12.6 ms                                                                     | 12.7 ms: 1.01x slower                                               |
| pidigits                 | 264 ms                                                                      | 266 ms: 1.01x slower                                                |
| python_startup_no_site   | 8.65 ms                                                                     | 8.70 ms: 1.01x slower                                               |
| logging_simple           | 6.83 us                                                                     | 6.87 us: 1.01x slower                                               |
| logging_format           | 7.49 us                                                                     | 7.54 us: 1.01x slower                                               |
| richards_super           | 60.7 ms                                                                     | 61.2 ms: 1.01x slower                                               |
| dulwich_log              | 69.3 ms                                                                     | 69.9 ms: 1.01x slower                                               |
| deepcopy                 | 382 us                                                                      | 386 us: 1.01x slower                                                |
| pprint_pformat           | 1.65 sec                                                                    | 1.67 sec: 1.01x slower                                              |
| dask                     | 588 ms                                                                      | 595 ms: 1.01x slower                                                |
| pickle_pure_python       | 313 us                                                                      | 317 us: 1.01x slower                                                |
| raytrace                 | 267 ms                                                                      | 271 ms: 1.01x slower                                                |
| xml_etree_process        | 58.6 ms                                                                     | 59.5 ms: 1.02x slower                                               |
| pathlib                  | 19.7 ms                                                                     | 20.0 ms: 1.02x slower                                               |
| pprint_safe_repr         | 806 ms                                                                      | 819 ms: 1.02x slower                                                |
| pickle                   | 9.94 us                                                                     | 10.1 us: 1.02x slower                                               |
| tornado_http             | 121 ms                                                                      | 122 ms: 1.02x slower                                                |
| coroutines               | 23.1 ms                                                                     | 23.5 ms: 1.02x slower                                               |
| logging_silent           | 97.7 ns                                                                     | 99.4 ns: 1.02x slower                                               |
| sqlglot_parse            | 1.42 ms                                                                     | 1.44 ms: 1.02x slower                                               |
| deltablue                | 3.69 ms                                                                     | 3.77 ms: 1.02x slower                                               |
| richards                 | 54.0 ms                                                                     | 55.1 ms: 1.02x slower                                               |
| regex_effbot             | 3.42 ms                                                                     | 3.50 ms: 1.02x slower                                               |
| sqlglot_transpile        | 1.82 ms                                                                     | 1.86 ms: 1.03x slower                                               |
| regex_dna                | 239 ms                                                                      | 245 ms: 1.03x slower                                                |
| docutils                 | 2.87 sec                                                                    | 2.95 sec: 1.03x slower                                              |
| sqlglot_optimize         | 58.4 ms                                                                     | 60.6 ms: 1.04x slower                                               |
| pickle_list              | 4.15 us                                                                     | 4.30 us: 1.04x slower                                               |
| unpickle_pure_python     | 222 us                                                                      | 232 us: 1.04x slower                                                |
| unpickle                 | 14.3 us                                                                     | 14.9 us: 1.04x slower                                               |
| mako                     | 10.5 ms                                                                     | 10.9 ms: 1.04x slower                                               |
| sqlglot_normalize        | 115 ms                                                                      | 120 ms: 1.05x slower                                                |
| float                    | 81.1 ms                                                                     | 84.9 ms: 1.05x slower                                               |
| mypy2                    | 370 ms                                                                      | 387 ms: 1.05x slower                                                |
| deepcopy_memo            | 37.8 us                                                                     | 40.0 us: 1.06x slower                                               |
| go                       | 170 ms                                                                      | 179 ms: 1.06x slower                                                |
| async_generators         | 392 ms                                                                      | 415 ms: 1.06x slower                                                |
| mdp                      | 2.55 sec                                                                    | 2.71 sec: 1.06x slower                                              |
| regex_v8                 | 24.8 ms                                                                     | 26.3 ms: 1.06x slower                                               |
| crypto_pyaes             | 71.7 ms                                                                     | 76.6 ms: 1.07x slower                                               |
| regex_compile            | 149 ms                                                                      | 159 ms: 1.07x slower                                                |
| scimark_lu               | 101 ms                                                                      | 108 ms: 1.07x slower                                                |
| generators               | 34.7 ms                                                                     | 37.2 ms: 1.07x slower                                               |
| meteor_contest           | 129 ms                                                                      | 139 ms: 1.08x slower                                                |
| typing_runtime_protocols | 148 us                                                                      | 160 us: 1.08x slower                                                |
| fannkuch                 | 397 ms                                                                      | 437 ms: 1.10x slower                                                |
| tomli_loads              | 2.22 sec                                                                    | 2.44 sec: 1.10x slower                                              |
| scimark_monte_carlo      | 66.3 ms                                                                     | 73.4 ms: 1.11x slower                                               |
| gc_traversal             | 3.56 ms                                                                     | 3.95 ms: 1.11x slower                                               |
| chaos                    | 63.6 ms                                                                     | 72.2 ms: 1.14x slower                                               |
| comprehensions           | 22.6 us                                                                     | 26.3 us: 1.16x slower                                               |
| hexiom                   | 6.47 ms                                                                     | 7.64 ms: 1.18x slower                                               |
| unpack_sequence          | 48.7 ns                                                                     | 57.6 ns: 1.18x slower                                               |
| nqueens                  | 90.0 ms                                                                     | 111 ms: 1.23x slower                                                |
| scimark_fft              | 301 ms                                                                      | 398 ms: 1.32x slower                                                |
| scimark_sparse_mat_mult  | 4.24 ms                                                                     | 5.63 ms: 1.33x slower                                               |
| nbody                    | 87.0 ms                                                                     | 127 ms: 1.46x slower                                                |
| Geometric mean           | (ref)                                                                       | 1.04x slower                                                        |

Benchmark hidden because not significant (12): xml_etree_iterparse, json, asyncio_tcp, async_tree_cpu_io_mixed, scimark_sor, async_tree_io, bench_mp_pool, async_tree_memoization, telco, async_tree_none, json_loads, bench_thread_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
