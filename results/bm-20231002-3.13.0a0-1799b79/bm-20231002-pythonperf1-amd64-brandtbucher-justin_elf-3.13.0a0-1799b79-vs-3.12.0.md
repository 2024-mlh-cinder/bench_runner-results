
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_elf
- machine: windows-amd64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.12x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.70 sec: 1.04x slower                                                 |
| tornado_http   | 87.7 ms                                                     | 91.4 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                       | 1.04x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 54.8 ms: 1.01x faster                                                  |
| pidigits       | 150 ms                                                      | 150 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                       | 1.00x slower                                                           |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 121 ms: 1.02x faster                                                   |
| regex_effbot   | 1.62 ms                                                     | 1.62 ms: 1.00x faster                                                  |
| regex_compile  | 88.3 ms                                                     | 100 ms: 1.13x slower                                                   |
| regex_v8       | 13.9 ms                                                     | 17.2 ms: 1.24x slower                                                  |
| Geometric mean | (ref)                                                       | 1.08x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.2 us: 1.06x faster                                                  |
| unpickle_list        | 2.78 us                                                     | 2.73 us: 1.02x faster                                                  |
| pickle               | 7.13 us                                                     | 7.09 us: 1.01x faster                                                  |
| json_loads           | 13.4 us                                                     | 13.9 us: 1.03x slower                                                  |
| tomli_loads          | 1.37 sec                                                    | 1.43 sec: 1.05x slower                                                 |
| xml_etree_parse      | 89.2 ms                                                     | 93.9 ms: 1.05x slower                                                  |
| unpickle             | 8.16 us                                                     | 8.62 us: 1.06x slower                                                  |
| json_dumps           | 5.60 ms                                                     | 6.01 ms: 1.07x slower                                                  |
| xml_etree_iterparse  | 62.5 ms                                                     | 68.3 ms: 1.09x slower                                                  |
| xml_etree_generate   | 55.6 ms                                                     | 62.7 ms: 1.13x slower                                                  |
| pickle_pure_python   | 196 us                                                      | 225 us: 1.15x slower                                                   |
| xml_etree_process    | 38.4 ms                                                     | 45.1 ms: 1.17x slower                                                  |
| unpickle_pure_python | 133 us                                                      | 174 us: 1.30x slower                                                   |
| Geometric mean       | (ref)                                                       | 1.07x slower                                                           |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.3 ms: 1.01x slower                                                  |
| python_startup         | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                  |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.99 ms: 1.15x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.73 sec: 1.13x faster                                                 |
| coverage                 | 51.5 ms                                                     | 47.2 ms: 1.09x faster                                                  |
| pickle_dict              | 19.3 us                                                     | 18.2 us: 1.06x faster                                                  |
| regex_dna                | 124 ms                                                      | 121 ms: 1.02x faster                                                   |
| unpickle_list            | 2.78 us                                                     | 2.73 us: 1.02x faster                                                  |
| float                    | 55.1 ms                                                     | 54.8 ms: 1.01x faster                                                  |
| pickle                   | 7.13 us                                                     | 7.09 us: 1.01x faster                                                  |
| regex_effbot             | 1.62 ms                                                     | 1.62 ms: 1.00x faster                                                  |
| pidigits                 | 150 ms                                                      | 150 ms: 1.00x slower                                                   |
| pathlib                  | 77.1 ms                                                     | 78.2 ms: 1.01x slower                                                  |
| python_startup_no_site   | 16.1 ms                                                     | 16.3 ms: 1.01x slower                                                  |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.51 ms: 1.01x slower                                                  |
| gc_traversal             | 1.48 ms                                                     | 1.51 ms: 1.01x slower                                                  |
| sqlite_synth             | 1.76 us                                                     | 1.79 us: 1.02x slower                                                  |
| python_startup           | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                  |
| bench_mp_pool            | 66.4 ms                                                     | 68.0 ms: 1.02x slower                                                  |
| json                     | 2.86 ms                                                     | 2.95 ms: 1.03x slower                                                  |
| json_loads               | 13.4 us                                                     | 13.9 us: 1.03x slower                                                  |
| asyncio_tcp              | 472 ms                                                      | 488 ms: 1.04x slower                                                   |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 497 ms: 1.04x slower                                                   |
| crypto_pyaes             | 47.4 ms                                                     | 49.2 ms: 1.04x slower                                                  |
| bench_thread_pool        | 844 us                                                      | 878 us: 1.04x slower                                                   |
| tornado_http             | 87.7 ms                                                     | 91.4 ms: 1.04x slower                                                  |
| docutils                 | 1.63 sec                                                    | 1.70 sec: 1.04x slower                                                 |
| tomli_loads              | 1.37 sec                                                    | 1.43 sec: 1.05x slower                                                 |
| xml_etree_parse          | 89.2 ms                                                     | 93.9 ms: 1.05x slower                                                  |
| unpickle                 | 8.16 us                                                     | 8.62 us: 1.06x slower                                                  |
| mdp                      | 1.44 sec                                                    | 1.54 sec: 1.06x slower                                                 |
| json_dumps               | 5.60 ms                                                     | 6.01 ms: 1.07x slower                                                  |
| dulwich_log              | 42.4 ms                                                     | 45.8 ms: 1.08x slower                                                  |
| async_tree_io            | 720 ms                                                      | 782 ms: 1.09x slower                                                   |
| typing_runtime_protocols | 95.2 us                                                     | 104 us: 1.09x slower                                                   |
| xml_etree_iterparse      | 62.5 ms                                                     | 68.3 ms: 1.09x slower                                                  |
| meteor_contest           | 73.1 ms                                                     | 80.5 ms: 1.10x slower                                                  |
| async_tree_memoization   | 336 ms                                                      | 370 ms: 1.10x slower                                                   |
| mypy2                    | 207 ms                                                      | 230 ms: 1.11x slower                                                   |
| sqlglot_normalize        | 185 ms                                                      | 207 ms: 1.12x slower                                                   |
| deepcopy_reduce          | 2.13 us                                                     | 2.39 us: 1.12x slower                                                  |
| raytrace                 | 191 ms                                                      | 216 ms: 1.13x slower                                                   |
| xml_etree_generate       | 55.6 ms                                                     | 62.7 ms: 1.13x slower                                                  |
| sqlglot_optimize         | 34.4 ms                                                     | 38.9 ms: 1.13x slower                                                  |
| deepcopy                 | 240 us                                                      | 272 us: 1.13x slower                                                   |
| regex_compile            | 88.3 ms                                                     | 100 ms: 1.13x slower                                                   |
| async_generators         | 235 ms                                                      | 267 ms: 1.14x slower                                                   |
| nqueens                  | 61.2 ms                                                     | 69.9 ms: 1.14x slower                                                  |
| logging_format           | 6.67 us                                                     | 7.64 us: 1.14x slower                                                  |
| logging_simple           | 6.21 us                                                     | 7.14 us: 1.15x slower                                                  |
| pickle_pure_python       | 196 us                                                      | 225 us: 1.15x slower                                                   |
| fannkuch                 | 237 ms                                                      | 273 ms: 1.15x slower                                                   |
| mako                     | 6.93 ms                                                     | 7.99 ms: 1.15x slower                                                  |
| scimark_fft              | 180 ms                                                      | 208 ms: 1.16x slower                                                   |
| comprehensions           | 14.1 us                                                     | 16.4 us: 1.16x slower                                                  |
| chaos                    | 42.8 ms                                                     | 50.0 ms: 1.17x slower                                                  |
| sqlglot_transpile        | 1.04 ms                                                     | 1.21 ms: 1.17x slower                                                  |
| pprint_safe_repr         | 512 ms                                                      | 600 ms: 1.17x slower                                                   |
| xml_etree_process        | 38.4 ms                                                     | 45.1 ms: 1.17x slower                                                  |
| pprint_pformat           | 1.04 sec                                                    | 1.24 sec: 1.18x slower                                                 |
| pyflate                  | 297 ms                                                      | 356 ms: 1.20x slower                                                   |
| sqlglot_parse            | 820 us                                                      | 983 us: 1.20x slower                                                   |
| scimark_monte_carlo      | 43.7 ms                                                     | 52.9 ms: 1.21x slower                                                  |
| telco                    | 4.09 ms                                                     | 5.07 ms: 1.24x slower                                                  |
| regex_v8                 | 13.9 ms                                                     | 17.2 ms: 1.24x slower                                                  |
| go                       | 88.5 ms                                                     | 112 ms: 1.27x slower                                                   |
| scimark_lu               | 58.1 ms                                                     | 74.0 ms: 1.27x slower                                                  |
| spectral_norm            | 63.2 ms                                                     | 80.7 ms: 1.28x slower                                                  |
| hexiom                   | 4.03 ms                                                     | 5.16 ms: 1.28x slower                                                  |
| unpack_sequence          | 37.5 ns                                                     | 48.0 ns: 1.28x slower                                                  |
| richards_super           | 30.5 ms                                                     | 39.2 ms: 1.29x slower                                                  |
| pycparser                | 673 ms                                                      | 873 ms: 1.30x slower                                                   |
| unpickle_pure_python     | 133 us                                                      | 174 us: 1.30x slower                                                   |
| scimark_sor              | 79.6 ms                                                     | 104 ms: 1.30x slower                                                   |
| deepcopy_memo            | 23.8 us                                                     | 31.1 us: 1.30x slower                                                  |
| deltablue                | 2.14 ms                                                     | 2.81 ms: 1.31x slower                                                  |
| richards                 | 26.9 ms                                                     | 35.7 ms: 1.33x slower                                                  |
| coroutines               | 14.0 ms                                                     | 18.8 ms: 1.34x slower                                                  |
| generators               | 22.7 ms                                                     | 33.5 ms: 1.47x slower                                                  |
| logging_silent           | 60.6 ns                                                     | 92.1 ns: 1.52x slower                                                  |
| Geometric mean           | (ref)                                                       | 1.12x slower                                                           |

Benchmark hidden because not significant (4): pickle_list, async_tree_none, create_gc_cycles, nbody
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.08x
- 95% likely to have a slowdown of 1.07x
- 99% likely to have a slowdown of 1.06x
