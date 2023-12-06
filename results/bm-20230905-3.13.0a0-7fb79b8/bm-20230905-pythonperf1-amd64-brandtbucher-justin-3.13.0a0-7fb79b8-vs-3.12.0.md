
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.68 sec: 1.03x slower                                             |
| tornado_http   | 87.7 ms                                                     | 90.9 ms: 1.04x slower                                              |
| Geometric mean | (ref)                                                       | 1.03x slower                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 150 ms: 1.00x slower                                               |
| float          | 55.1 ms                                                     | 55.8 ms: 1.01x slower                                              |
| nbody          | 72.6 ms                                                     | 76.8 ms: 1.06x slower                                              |
| Geometric mean | (ref)                                                       | 1.02x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 119 ms: 1.04x faster                                               |
| regex_effbot   | 1.62 ms                                                     | 1.57 ms: 1.03x faster                                              |
| regex_v8       | 13.9 ms                                                     | 15.0 ms: 1.08x slower                                              |
| regex_compile  | 88.3 ms                                                     | 95.9 ms: 1.09x slower                                              |
| Geometric mean | (ref)                                                       | 1.02x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.5 us: 1.04x faster                                              |
| pickle_list          | 2.86 us                                                     | 2.83 us: 1.01x faster                                              |
| unpickle_list        | 2.78 us                                                     | 2.76 us: 1.01x faster                                              |
| pickle               | 7.13 us                                                     | 7.09 us: 1.01x faster                                              |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                              |
| unpickle             | 8.16 us                                                     | 8.31 us: 1.02x slower                                              |
| xml_etree_generate   | 55.6 ms                                                     | 57.6 ms: 1.04x slower                                              |
| xml_etree_process    | 38.4 ms                                                     | 40.1 ms: 1.05x slower                                              |
| xml_etree_parse      | 89.2 ms                                                     | 93.2 ms: 1.05x slower                                              |
| xml_etree_iterparse  | 62.5 ms                                                     | 66.5 ms: 1.06x slower                                              |
| json_dumps           | 5.60 ms                                                     | 5.97 ms: 1.07x slower                                              |
| tomli_loads          | 1.37 sec                                                    | 1.50 sec: 1.09x slower                                             |
| unpickle_pure_python | 133 us                                                      | 147 us: 1.10x slower                                               |
| Geometric mean       | (ref)                                                       | 1.03x slower                                                       |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 19.6 ms: 1.01x slower                                              |
| python_startup_no_site | 16.1 ms                                                     | 16.7 ms: 1.03x slower                                              |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.79 ms: 1.02x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 46.7 ms: 1.10x faster                                              |
| async_tree_none          | 294 ms                                                      | 279 ms: 1.05x faster                                               |
| regex_dna                | 124 ms                                                      | 119 ms: 1.04x faster                                               |
| pickle_dict              | 19.3 us                                                     | 18.5 us: 1.04x faster                                              |
| regex_effbot             | 1.62 ms                                                     | 1.57 ms: 1.03x faster                                              |
| raytrace                 | 191 ms                                                      | 187 ms: 1.02x faster                                               |
| mako                     | 6.93 ms                                                     | 6.79 ms: 1.02x faster                                              |
| crypto_pyaes             | 47.4 ms                                                     | 46.5 ms: 1.02x faster                                              |
| pickle_list              | 2.86 us                                                     | 2.83 us: 1.01x faster                                              |
| unpack_sequence          | 37.5 ns                                                     | 37.1 ns: 1.01x faster                                              |
| unpickle_list            | 2.78 us                                                     | 2.76 us: 1.01x faster                                              |
| pickle                   | 7.13 us                                                     | 7.09 us: 1.01x faster                                              |
| pidigits                 | 150 ms                                                      | 150 ms: 1.00x slower                                               |
| mdp                      | 1.44 sec                                                    | 1.45 sec: 1.01x slower                                             |
| python_startup           | 19.5 ms                                                     | 19.6 ms: 1.01x slower                                              |
| float                    | 55.1 ms                                                     | 55.8 ms: 1.01x slower                                              |
| gc_traversal             | 1.48 ms                                                     | 1.50 ms: 1.01x slower                                              |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                              |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 485 ms: 1.01x slower                                               |
| scimark_monte_carlo      | 43.7 ms                                                     | 44.3 ms: 1.01x slower                                              |
| async_tree_io            | 720 ms                                                      | 732 ms: 1.02x slower                                               |
| sqlite_synth             | 1.76 us                                                     | 1.79 us: 1.02x slower                                              |
| unpickle                 | 8.16 us                                                     | 8.31 us: 1.02x slower                                              |
| pathlib                  | 77.1 ms                                                     | 79.3 ms: 1.03x slower                                              |
| json                     | 2.86 ms                                                     | 2.94 ms: 1.03x slower                                              |
| bench_thread_pool        | 844 us                                                      | 869 us: 1.03x slower                                               |
| docutils                 | 1.63 sec                                                    | 1.68 sec: 1.03x slower                                             |
| python_startup_no_site   | 16.1 ms                                                     | 16.7 ms: 1.03x slower                                              |
| scimark_lu               | 58.1 ms                                                     | 60.1 ms: 1.03x slower                                              |
| deepcopy_reduce          | 2.13 us                                                     | 2.21 us: 1.04x slower                                              |
| xml_etree_generate       | 55.6 ms                                                     | 57.6 ms: 1.04x slower                                              |
| tornado_http             | 87.7 ms                                                     | 90.9 ms: 1.04x slower                                              |
| deepcopy_memo            | 23.8 us                                                     | 24.8 us: 1.04x slower                                              |
| deepcopy                 | 240 us                                                      | 250 us: 1.04x slower                                               |
| fannkuch                 | 237 ms                                                      | 247 ms: 1.04x slower                                               |
| xml_etree_process        | 38.4 ms                                                     | 40.1 ms: 1.05x slower                                              |
| xml_etree_parse          | 89.2 ms                                                     | 93.2 ms: 1.05x slower                                              |
| scimark_sor              | 79.6 ms                                                     | 83.6 ms: 1.05x slower                                              |
| scimark_fft              | 180 ms                                                      | 189 ms: 1.05x slower                                               |
| coroutines               | 14.0 ms                                                     | 14.7 ms: 1.05x slower                                              |
| pyflate                  | 297 ms                                                      | 313 ms: 1.06x slower                                               |
| bench_mp_pool            | 66.4 ms                                                     | 70.2 ms: 1.06x slower                                              |
| pprint_safe_repr         | 512 ms                                                      | 541 ms: 1.06x slower                                               |
| typing_runtime_protocols | 95.2 us                                                     | 101 us: 1.06x slower                                               |
| nbody                    | 72.6 ms                                                     | 76.8 ms: 1.06x slower                                              |
| chaos                    | 42.8 ms                                                     | 45.5 ms: 1.06x slower                                              |
| xml_etree_iterparse      | 62.5 ms                                                     | 66.5 ms: 1.06x slower                                              |
| nqueens                  | 61.2 ms                                                     | 65.2 ms: 1.06x slower                                              |
| logging_format           | 6.67 us                                                     | 7.11 us: 1.06x slower                                              |
| json_dumps               | 5.60 ms                                                     | 5.97 ms: 1.07x slower                                              |
| pprint_pformat           | 1.04 sec                                                    | 1.11 sec: 1.07x slower                                             |
| async_tree_memoization   | 336 ms                                                      | 359 ms: 1.07x slower                                               |
| logging_simple           | 6.21 us                                                     | 6.66 us: 1.07x slower                                              |
| logging_silent           | 60.6 ns                                                     | 65.0 ns: 1.07x slower                                              |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.66 ms: 1.07x slower                                              |
| sqlglot_normalize        | 185 ms                                                      | 199 ms: 1.07x slower                                               |
| sqlglot_optimize         | 34.4 ms                                                     | 37.0 ms: 1.08x slower                                              |
| spectral_norm            | 63.2 ms                                                     | 68.1 ms: 1.08x slower                                              |
| sqlglot_transpile        | 1.04 ms                                                     | 1.12 ms: 1.08x slower                                              |
| regex_v8                 | 13.9 ms                                                     | 15.0 ms: 1.08x slower                                              |
| meteor_contest           | 73.1 ms                                                     | 79.3 ms: 1.08x slower                                              |
| regex_compile            | 88.3 ms                                                     | 95.9 ms: 1.09x slower                                              |
| async_generators         | 235 ms                                                      | 257 ms: 1.09x slower                                               |
| tomli_loads              | 1.37 sec                                                    | 1.50 sec: 1.09x slower                                             |
| deltablue                | 2.14 ms                                                     | 2.34 ms: 1.09x slower                                              |
| mypy2                    | 207 ms                                                      | 227 ms: 1.09x slower                                               |
| generators               | 22.7 ms                                                     | 24.9 ms: 1.10x slower                                              |
| richards_super           | 30.5 ms                                                     | 33.5 ms: 1.10x slower                                              |
| dulwich_log              | 42.4 ms                                                     | 46.7 ms: 1.10x slower                                              |
| unpickle_pure_python     | 133 us                                                      | 147 us: 1.10x slower                                               |
| richards                 | 26.9 ms                                                     | 29.9 ms: 1.11x slower                                              |
| sqlglot_parse            | 820 us                                                      | 912 us: 1.11x slower                                               |
| comprehensions           | 14.1 us                                                     | 15.9 us: 1.13x slower                                              |
| pycparser                | 673 ms                                                      | 765 ms: 1.14x slower                                               |
| go                       | 88.5 ms                                                     | 103 ms: 1.17x slower                                               |
| hexiom                   | 4.03 ms                                                     | 4.77 ms: 1.18x slower                                              |
| telco                    | 4.09 ms                                                     | 4.87 ms: 1.19x slower                                              |
| dask                     | 259 ms                                                      | 391 ms: 1.51x slower                                               |
| Geometric mean           | (ref)                                                       | 1.05x slower                                                       |

Benchmark hidden because not significant (4): asyncio_tcp_ssl, create_gc_cycles, pickle_pure_python, asyncio_tcp
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.03x
