
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: a47c13c
- commit date: 2023-08-19
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf1-amd64-python-main-3.13.0a0-a47c13c |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.62 sec: 1.00x faster                                     |
| Geometric mean | (ref)                                                       | 1.00x slower                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf1-amd64-python-main-3.13.0a0-a47c13c |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 55.1 ms                                                     | 54.6 ms: 1.01x faster                                      |
| nbody          | 72.6 ms                                                     | 79.6 ms: 1.10x slower                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf1-amd64-python-main-3.13.0a0-a47c13c |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 120 ms: 1.03x faster                                       |
| regex_compile  | 88.3 ms                                                     | 91.9 ms: 1.04x slower                                      |
| regex_v8       | 13.9 ms                                                     | 15.1 ms: 1.09x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf1-amd64-python-main-3.13.0a0-a47c13c |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_list          | 2.86 us                                                     | 2.85 us: 1.01x faster                                      |
| pickle               | 7.13 us                                                     | 7.37 us: 1.03x slower                                      |
| xml_etree_parse      | 89.2 ms                                                     | 92.3 ms: 1.04x slower                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.8 ms: 1.04x slower                                      |
| unpickle_pure_python | 133 us                                                      | 140 us: 1.05x slower                                       |
| unpickle             | 8.16 us                                                     | 8.60 us: 1.05x slower                                      |
| unpickle_list        | 2.78 us                                                     | 2.99 us: 1.07x slower                                      |
| tomli_loads          | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                     |
| pickle_dict          | 19.3 us                                                     | 21.2 us: 1.10x slower                                      |
| Geometric mean       | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (5): xml_etree_process, json_loads, xml_etree_generate, json_dumps, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf1-amd64-python-main-3.13.0a0-a47c13c |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                      |
| Geometric mean         | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf1-amd64-python-main-3.13.0a0-a47c13c |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.41 ms: 1.07x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230819-pythonperf1-amd64-python-main-3.13.0a0-a47c13c |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none          | 294 ms                                                      | 266 ms: 1.10x faster                                       |
| raytrace                 | 191 ms                                                      | 176 ms: 1.09x faster                                       |
| coverage                 | 51.5 ms                                                     | 47.2 ms: 1.09x faster                                      |
| crypto_pyaes             | 47.4 ms                                                     | 44.5 ms: 1.07x faster                                      |
| regex_dna                | 124 ms                                                      | 120 ms: 1.03x faster                                       |
| chaos                    | 42.8 ms                                                     | 41.7 ms: 1.03x faster                                      |
| unpack_sequence          | 37.5 ns                                                     | 36.5 ns: 1.03x faster                                      |
| bench_thread_pool        | 844 us                                                      | 828 us: 1.02x faster                                       |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 471 ms: 1.02x faster                                       |
| float                    | 55.1 ms                                                     | 54.6 ms: 1.01x faster                                      |
| bench_mp_pool            | 66.4 ms                                                     | 65.8 ms: 1.01x faster                                      |
| gc_traversal             | 1.48 ms                                                     | 1.47 ms: 1.01x faster                                      |
| pickle_list              | 2.86 us                                                     | 2.85 us: 1.01x faster                                      |
| sqlite_synth             | 1.76 us                                                     | 1.75 us: 1.00x faster                                      |
| docutils                 | 1.63 sec                                                    | 1.62 sec: 1.00x faster                                     |
| mdp                      | 1.44 sec                                                    | 1.44 sec: 1.00x faster                                     |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.49 ms: 1.00x slower                                      |
| meteor_contest           | 73.1 ms                                                     | 73.9 ms: 1.01x slower                                      |
| sqlglot_parse            | 820 us                                                      | 829 us: 1.01x slower                                       |
| sqlglot_transpile        | 1.04 ms                                                     | 1.05 ms: 1.01x slower                                      |
| sqlglot_normalize        | 185 ms                                                      | 188 ms: 1.01x slower                                       |
| nqueens                  | 61.2 ms                                                     | 62.2 ms: 1.02x slower                                      |
| pathlib                  | 77.1 ms                                                     | 78.5 ms: 1.02x slower                                      |
| python_startup_no_site   | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                      |
| async_tree_io            | 720 ms                                                      | 733 ms: 1.02x slower                                       |
| logging_format           | 6.67 us                                                     | 6.82 us: 1.02x slower                                      |
| async_tree_memoization   | 336 ms                                                      | 344 ms: 1.02x slower                                       |
| sqlglot_optimize         | 34.4 ms                                                     | 35.2 ms: 1.02x slower                                      |
| spectral_norm            | 63.2 ms                                                     | 64.7 ms: 1.02x slower                                      |
| deepcopy_reduce          | 2.13 us                                                     | 2.19 us: 1.03x slower                                      |
| pyflate                  | 297 ms                                                      | 305 ms: 1.03x slower                                       |
| typing_runtime_protocols | 95.2 us                                                     | 97.8 us: 1.03x slower                                      |
| scimark_monte_carlo      | 43.7 ms                                                     | 45.0 ms: 1.03x slower                                      |
| comprehensions           | 14.1 us                                                     | 14.6 us: 1.03x slower                                      |
| pickle                   | 7.13 us                                                     | 7.37 us: 1.03x slower                                      |
| pprint_safe_repr         | 512 ms                                                      | 529 ms: 1.03x slower                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.08 sec: 1.03x slower                                     |
| async_generators         | 235 ms                                                      | 244 ms: 1.04x slower                                       |
| xml_etree_parse          | 89.2 ms                                                     | 92.3 ms: 1.04x slower                                      |
| logging_simple           | 6.21 us                                                     | 6.43 us: 1.04x slower                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 64.8 ms: 1.04x slower                                      |
| go                       | 88.5 ms                                                     | 91.7 ms: 1.04x slower                                      |
| deltablue                | 2.14 ms                                                     | 2.22 ms: 1.04x slower                                      |
| regex_compile            | 88.3 ms                                                     | 91.9 ms: 1.04x slower                                      |
| deepcopy_memo            | 23.8 us                                                     | 24.8 us: 1.04x slower                                      |
| unpickle_pure_python     | 133 us                                                      | 140 us: 1.05x slower                                       |
| logging_silent           | 60.6 ns                                                     | 63.7 ns: 1.05x slower                                      |
| unpickle                 | 8.16 us                                                     | 8.60 us: 1.05x slower                                      |
| scimark_sor              | 79.6 ms                                                     | 84.0 ms: 1.06x slower                                      |
| hexiom                   | 4.03 ms                                                     | 4.27 ms: 1.06x slower                                      |
| scimark_lu               | 58.1 ms                                                     | 61.6 ms: 1.06x slower                                      |
| pycparser                | 673 ms                                                      | 714 ms: 1.06x slower                                       |
| dulwich_log              | 42.4 ms                                                     | 45.1 ms: 1.06x slower                                      |
| generators               | 22.7 ms                                                     | 24.2 ms: 1.06x slower                                      |
| scimark_fft              | 180 ms                                                      | 192 ms: 1.07x slower                                       |
| mako                     | 6.93 ms                                                     | 7.41 ms: 1.07x slower                                      |
| fannkuch                 | 237 ms                                                      | 253 ms: 1.07x slower                                       |
| unpickle_list            | 2.78 us                                                     | 2.99 us: 1.07x slower                                      |
| richards_super           | 30.5 ms                                                     | 32.7 ms: 1.07x slower                                      |
| richards                 | 26.9 ms                                                     | 29.1 ms: 1.08x slower                                      |
| coroutines               | 14.0 ms                                                     | 15.2 ms: 1.08x slower                                      |
| regex_v8                 | 13.9 ms                                                     | 15.1 ms: 1.09x slower                                      |
| tomli_loads              | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                     |
| nbody                    | 72.6 ms                                                     | 79.6 ms: 1.10x slower                                      |
| pickle_dict              | 19.3 us                                                     | 21.2 us: 1.10x slower                                      |
| telco                    | 4.09 ms                                                     | 4.77 ms: 1.17x slower                                      |
| mypy2                    | 207 ms                                                      | 295 ms: 1.42x slower                                       |
| dask                     | 259 ms                                                      | 372 ms: 1.44x slower                                       |
| Geometric mean           | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (14): xml_etree_process, deepcopy, json_loads, xml_etree_generate, json_dumps, regex_effbot, create_gc_cycles, pidigits, asyncio_tcp_ssl, pickle_pure_python, python_startup, tornado_http, asyncio_tcp, json
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
