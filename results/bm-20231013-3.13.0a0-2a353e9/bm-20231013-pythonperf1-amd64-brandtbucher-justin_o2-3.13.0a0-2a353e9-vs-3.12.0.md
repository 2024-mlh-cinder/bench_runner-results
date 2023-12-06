
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_o2
- machine: windows-amd64
- commit hash: 2a353e9
- commit date: 2023-10-13
- overall geometric mean: 1.12x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.71 sec: 1.05x slower                                                |
| tornado_http   | 87.7 ms                                                     | 92.4 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                       | 1.05x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 55.9 ms: 1.01x slower                                                 |
| nbody          | 72.6 ms                                                     | 88.2 ms: 1.21x slower                                                 |
| Geometric mean | (ref)                                                       | 1.07x slower                                                          |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 123 ms: 1.01x faster                                                  |
| regex_compile  | 88.3 ms                                                     | 100 ms: 1.13x slower                                                  |
| regex_v8       | 13.9 ms                                                     | 15.9 ms: 1.14x slower                                                 |
| Geometric mean | (ref)                                                       | 1.07x slower                                                          |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.2 us: 1.06x faster                                                 |
| unpickle_list        | 2.78 us                                                     | 2.71 us: 1.03x faster                                                 |
| unpickle             | 8.16 us                                                     | 8.08 us: 1.01x faster                                                 |
| xml_etree_parse      | 89.2 ms                                                     | 92.2 ms: 1.03x slower                                                 |
| pickle               | 7.13 us                                                     | 7.44 us: 1.04x slower                                                 |
| xml_etree_iterparse  | 62.5 ms                                                     | 68.0 ms: 1.09x slower                                                 |
| json_dumps           | 5.60 ms                                                     | 6.11 ms: 1.09x slower                                                 |
| tomli_loads          | 1.37 sec                                                    | 1.50 sec: 1.10x slower                                                |
| xml_etree_generate   | 55.6 ms                                                     | 62.7 ms: 1.13x slower                                                 |
| pickle_pure_python   | 196 us                                                      | 224 us: 1.15x slower                                                  |
| xml_etree_process    | 38.4 ms                                                     | 44.9 ms: 1.17x slower                                                 |
| unpickle_pure_python | 133 us                                                      | 171 us: 1.28x slower                                                  |
| Geometric mean       | (ref)                                                       | 1.07x slower                                                          |

Benchmark hidden because not significant (2): pickle_list, json_loads

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.86 ms: 1.01x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.85 sec: 1.06x faster                                                |
| pickle_dict              | 19.3 us                                                     | 18.2 us: 1.06x faster                                                 |
| unpickle_list            | 2.78 us                                                     | 2.71 us: 1.03x faster                                                 |
| sqlite_synth             | 1.76 us                                                     | 1.72 us: 1.02x faster                                                 |
| create_gc_cycles         | 727 us                                                      | 714 us: 1.02x faster                                                  |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 473 ms: 1.01x faster                                                  |
| mako                     | 6.93 ms                                                     | 6.86 ms: 1.01x faster                                                 |
| unpickle                 | 8.16 us                                                     | 8.08 us: 1.01x faster                                                 |
| regex_dna                | 124 ms                                                      | 123 ms: 1.01x faster                                                  |
| float                    | 55.1 ms                                                     | 55.9 ms: 1.01x slower                                                 |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.52 ms: 1.02x slower                                                 |
| json                     | 2.86 ms                                                     | 2.92 ms: 1.02x slower                                                 |
| pathlib                  | 77.1 ms                                                     | 79.0 ms: 1.02x slower                                                 |
| mdp                      | 1.44 sec                                                    | 1.48 sec: 1.03x slower                                                |
| asyncio_tcp              | 472 ms                                                      | 484 ms: 1.03x slower                                                  |
| xml_etree_parse          | 89.2 ms                                                     | 92.2 ms: 1.03x slower                                                 |
| pickle                   | 7.13 us                                                     | 7.44 us: 1.04x slower                                                 |
| bench_thread_pool        | 844 us                                                      | 883 us: 1.05x slower                                                  |
| docutils                 | 1.63 sec                                                    | 1.71 sec: 1.05x slower                                                |
| tornado_http             | 87.7 ms                                                     | 92.4 ms: 1.05x slower                                                 |
| async_tree_io            | 720 ms                                                      | 765 ms: 1.06x slower                                                  |
| crypto_pyaes             | 47.4 ms                                                     | 50.7 ms: 1.07x slower                                                 |
| dulwich_log              | 42.4 ms                                                     | 45.9 ms: 1.08x slower                                                 |
| xml_etree_iterparse      | 62.5 ms                                                     | 68.0 ms: 1.09x slower                                                 |
| json_dumps               | 5.60 ms                                                     | 6.11 ms: 1.09x slower                                                 |
| async_tree_memoization   | 336 ms                                                      | 367 ms: 1.09x slower                                                  |
| typing_runtime_protocols | 95.2 us                                                     | 104 us: 1.09x slower                                                  |
| tomli_loads              | 1.37 sec                                                    | 1.50 sec: 1.10x slower                                                |
| meteor_contest           | 73.1 ms                                                     | 80.4 ms: 1.10x slower                                                 |
| nqueens                  | 61.2 ms                                                     | 67.8 ms: 1.11x slower                                                 |
| raytrace                 | 191 ms                                                      | 213 ms: 1.11x slower                                                  |
| mypy2                    | 207 ms                                                      | 231 ms: 1.11x slower                                                  |
| scimark_fft              | 180 ms                                                      | 203 ms: 1.13x slower                                                  |
| xml_etree_generate       | 55.6 ms                                                     | 62.7 ms: 1.13x slower                                                 |
| deepcopy_reduce          | 2.13 us                                                     | 2.41 us: 1.13x slower                                                 |
| sqlglot_normalize        | 185 ms                                                      | 209 ms: 1.13x slower                                                  |
| logging_format           | 6.67 us                                                     | 7.56 us: 1.13x slower                                                 |
| regex_compile            | 88.3 ms                                                     | 100 ms: 1.13x slower                                                  |
| deepcopy                 | 240 us                                                      | 273 us: 1.14x slower                                                  |
| sqlglot_optimize         | 34.4 ms                                                     | 39.2 ms: 1.14x slower                                                 |
| coverage                 | 51.5 ms                                                     | 58.7 ms: 1.14x slower                                                 |
| logging_simple           | 6.21 us                                                     | 7.10 us: 1.14x slower                                                 |
| regex_v8                 | 13.9 ms                                                     | 15.9 ms: 1.14x slower                                                 |
| pickle_pure_python       | 196 us                                                      | 224 us: 1.15x slower                                                  |
| async_generators         | 235 ms                                                      | 273 ms: 1.16x slower                                                  |
| pycparser                | 673 ms                                                      | 781 ms: 1.16x slower                                                  |
| pprint_safe_repr         | 512 ms                                                      | 596 ms: 1.16x slower                                                  |
| xml_etree_process        | 38.4 ms                                                     | 44.9 ms: 1.17x slower                                                 |
| fannkuch                 | 237 ms                                                      | 277 ms: 1.17x slower                                                  |
| pyflate                  | 297 ms                                                      | 348 ms: 1.17x slower                                                  |
| pprint_pformat           | 1.04 sec                                                    | 1.22 sec: 1.17x slower                                                |
| chaos                    | 42.8 ms                                                     | 50.4 ms: 1.18x slower                                                 |
| scimark_monte_carlo      | 43.7 ms                                                     | 51.6 ms: 1.18x slower                                                 |
| sqlglot_transpile        | 1.04 ms                                                     | 1.23 ms: 1.18x slower                                                 |
| telco                    | 4.09 ms                                                     | 4.86 ms: 1.19x slower                                                 |
| comprehensions           | 14.1 us                                                     | 16.9 us: 1.20x slower                                                 |
| nbody                    | 72.6 ms                                                     | 88.2 ms: 1.21x slower                                                 |
| sqlglot_parse            | 820 us                                                      | 999 us: 1.22x slower                                                  |
| spectral_norm            | 63.2 ms                                                     | 80.6 ms: 1.28x slower                                                 |
| unpickle_pure_python     | 133 us                                                      | 171 us: 1.28x slower                                                  |
| richards_super           | 30.5 ms                                                     | 39.0 ms: 1.28x slower                                                 |
| hexiom                   | 4.03 ms                                                     | 5.18 ms: 1.28x slower                                                 |
| go                       | 88.5 ms                                                     | 114 ms: 1.28x slower                                                  |
| unpack_sequence          | 37.5 ns                                                     | 48.2 ns: 1.29x slower                                                 |
| scimark_lu               | 58.1 ms                                                     | 74.9 ms: 1.29x slower                                                 |
| richards                 | 26.9 ms                                                     | 35.5 ms: 1.32x slower                                                 |
| scimark_sor              | 79.6 ms                                                     | 105 ms: 1.32x slower                                                  |
| deepcopy_memo            | 23.8 us                                                     | 31.8 us: 1.33x slower                                                 |
| coroutines               | 14.0 ms                                                     | 18.9 ms: 1.35x slower                                                 |
| deltablue                | 2.14 ms                                                     | 2.90 ms: 1.36x slower                                                 |
| generators               | 22.7 ms                                                     | 34.0 ms: 1.50x slower                                                 |
| logging_silent           | 60.6 ns                                                     | 93.0 ns: 1.54x slower                                                 |
| Geometric mean           | (ref)                                                       | 1.12x slower                                                          |

Benchmark hidden because not significant (9): async_tree_none, bench_mp_pool, python_startup_no_site, regex_effbot, pickle_list, pidigits, json_loads, python_startup, gc_traversal
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.09x
- 95% likely to have a slowdown of 1.08x
- 99% likely to have a slowdown of 1.06x
