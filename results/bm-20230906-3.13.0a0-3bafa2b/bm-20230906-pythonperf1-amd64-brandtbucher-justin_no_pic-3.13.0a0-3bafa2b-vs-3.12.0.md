
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_pic
- machine: windows-amd64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.67 sec: 1.03x slower                                                    |
| tornado_http   | 87.7 ms                                                     | 89.3 ms: 1.02x slower                                                     |
| Geometric mean | (ref)                                                       | 1.02x slower                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.01x slower                                                      |
| float          | 55.1 ms                                                     | 56.2 ms: 1.02x slower                                                     |
| nbody          | 72.6 ms                                                     | 77.1 ms: 1.06x slower                                                     |
| Geometric mean | (ref)                                                       | 1.03x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 123 ms: 1.00x faster                                                      |
| regex_effbot   | 1.62 ms                                                     | 1.64 ms: 1.01x slower                                                     |
| regex_compile  | 88.3 ms                                                     | 94.7 ms: 1.07x slower                                                     |
| regex_v8       | 13.9 ms                                                     | 15.2 ms: 1.09x slower                                                     |
| Geometric mean | (ref)                                                       | 1.04x slower                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.70 us: 1.03x faster                                                     |
| pickle_dict          | 19.3 us                                                     | 18.9 us: 1.02x faster                                                     |
| json_loads           | 13.4 us                                                     | 13.5 us: 1.00x slower                                                     |
| pickle_list          | 2.86 us                                                     | 2.93 us: 1.02x slower                                                     |
| xml_etree_parse      | 89.2 ms                                                     | 91.4 ms: 1.03x slower                                                     |
| pickle               | 7.13 us                                                     | 7.38 us: 1.03x slower                                                     |
| unpickle             | 8.16 us                                                     | 8.46 us: 1.04x slower                                                     |
| pickle_pure_python   | 196 us                                                      | 203 us: 1.04x slower                                                      |
| xml_etree_process    | 38.4 ms                                                     | 39.9 ms: 1.04x slower                                                     |
| json_dumps           | 5.60 ms                                                     | 5.82 ms: 1.04x slower                                                     |
| xml_etree_iterparse  | 62.5 ms                                                     | 65.3 ms: 1.04x slower                                                     |
| xml_etree_generate   | 55.6 ms                                                     | 58.2 ms: 1.05x slower                                                     |
| tomli_loads          | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                                    |
| unpickle_pure_python | 133 us                                                      | 152 us: 1.14x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.04x slower                                                              |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup | 19.5 ms                                                     | 19.1 ms: 1.02x faster                                                     |
| Geometric mean | (ref)                                                       | 1.01x faster                                                              |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.74 ms: 1.03x faster                                                     |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 46.6 ms: 1.11x faster                                                     |
| async_tree_none          | 294 ms                                                      | 273 ms: 1.07x faster                                                      |
| raytrace                 | 191 ms                                                      | 183 ms: 1.05x faster                                                      |
| unpickle_list            | 2.78 us                                                     | 2.70 us: 1.03x faster                                                     |
| mako                     | 6.93 ms                                                     | 6.74 ms: 1.03x faster                                                     |
| pickle_dict              | 19.3 us                                                     | 18.9 us: 1.02x faster                                                     |
| python_startup           | 19.5 ms                                                     | 19.1 ms: 1.02x faster                                                     |
| regex_dna                | 124 ms                                                      | 123 ms: 1.00x faster                                                      |
| json_loads               | 13.4 us                                                     | 13.5 us: 1.00x slower                                                     |
| pidigits                 | 150 ms                                                      | 151 ms: 1.01x slower                                                      |
| sqlite_synth             | 1.76 us                                                     | 1.77 us: 1.01x slower                                                     |
| regex_effbot             | 1.62 ms                                                     | 1.64 ms: 1.01x slower                                                     |
| crypto_pyaes             | 47.4 ms                                                     | 48.0 ms: 1.01x slower                                                     |
| gc_traversal             | 1.48 ms                                                     | 1.51 ms: 1.01x slower                                                     |
| async_tree_io            | 720 ms                                                      | 731 ms: 1.02x slower                                                      |
| tornado_http             | 87.7 ms                                                     | 89.3 ms: 1.02x slower                                                     |
| json                     | 2.86 ms                                                     | 2.92 ms: 1.02x slower                                                     |
| logging_format           | 6.67 us                                                     | 6.80 us: 1.02x slower                                                     |
| float                    | 55.1 ms                                                     | 56.2 ms: 1.02x slower                                                     |
| pickle_list              | 2.86 us                                                     | 2.93 us: 1.02x slower                                                     |
| logging_simple           | 6.21 us                                                     | 6.37 us: 1.02x slower                                                     |
| xml_etree_parse          | 89.2 ms                                                     | 91.4 ms: 1.03x slower                                                     |
| docutils                 | 1.63 sec                                                    | 1.67 sec: 1.03x slower                                                    |
| pathlib                  | 77.1 ms                                                     | 79.2 ms: 1.03x slower                                                     |
| bench_thread_pool        | 844 us                                                      | 869 us: 1.03x slower                                                      |
| pickle                   | 7.13 us                                                     | 7.38 us: 1.03x slower                                                     |
| unpickle                 | 8.16 us                                                     | 8.46 us: 1.04x slower                                                     |
| pickle_pure_python       | 196 us                                                      | 203 us: 1.04x slower                                                      |
| xml_etree_process        | 38.4 ms                                                     | 39.9 ms: 1.04x slower                                                     |
| typing_runtime_protocols | 95.2 us                                                     | 98.9 us: 1.04x slower                                                     |
| json_dumps               | 5.60 ms                                                     | 5.82 ms: 1.04x slower                                                     |
| sqlglot_parse            | 820 us                                                      | 856 us: 1.04x slower                                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 65.3 ms: 1.04x slower                                                     |
| sqlglot_transpile        | 1.04 ms                                                     | 1.08 ms: 1.05x slower                                                     |
| xml_etree_generate       | 55.6 ms                                                     | 58.2 ms: 1.05x slower                                                     |
| bench_mp_pool            | 66.4 ms                                                     | 69.6 ms: 1.05x slower                                                     |
| mdp                      | 1.44 sec                                                    | 1.51 sec: 1.05x slower                                                    |
| async_tree_memoization   | 336 ms                                                      | 353 ms: 1.05x slower                                                      |
| chaos                    | 42.8 ms                                                     | 45.1 ms: 1.05x slower                                                     |
| deepcopy_reduce          | 2.13 us                                                     | 2.25 us: 1.05x slower                                                     |
| deepcopy                 | 240 us                                                      | 254 us: 1.06x slower                                                      |
| generators               | 22.7 ms                                                     | 24.1 ms: 1.06x slower                                                     |
| nbody                    | 72.6 ms                                                     | 77.1 ms: 1.06x slower                                                     |
| logging_silent           | 60.6 ns                                                     | 64.4 ns: 1.06x slower                                                     |
| sqlglot_normalize        | 185 ms                                                      | 197 ms: 1.06x slower                                                      |
| scimark_monte_carlo      | 43.7 ms                                                     | 46.5 ms: 1.06x slower                                                     |
| pyflate                  | 297 ms                                                      | 316 ms: 1.06x slower                                                      |
| nqueens                  | 61.2 ms                                                     | 65.3 ms: 1.07x slower                                                     |
| sqlglot_optimize         | 34.4 ms                                                     | 36.7 ms: 1.07x slower                                                     |
| async_generators         | 235 ms                                                      | 252 ms: 1.07x slower                                                      |
| regex_compile            | 88.3 ms                                                     | 94.7 ms: 1.07x slower                                                     |
| mypy2                    | 207 ms                                                      | 222 ms: 1.07x slower                                                      |
| fannkuch                 | 237 ms                                                      | 255 ms: 1.07x slower                                                      |
| meteor_contest           | 73.1 ms                                                     | 78.7 ms: 1.08x slower                                                     |
| dulwich_log              | 42.4 ms                                                     | 45.7 ms: 1.08x slower                                                     |
| pycparser                | 673 ms                                                      | 726 ms: 1.08x slower                                                      |
| deltablue                | 2.14 ms                                                     | 2.31 ms: 1.08x slower                                                     |
| pprint_safe_repr         | 512 ms                                                      | 555 ms: 1.08x slower                                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.13 sec: 1.09x slower                                                    |
| tomli_loads              | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                                    |
| spectral_norm            | 63.2 ms                                                     | 68.7 ms: 1.09x slower                                                     |
| scimark_fft              | 180 ms                                                      | 196 ms: 1.09x slower                                                      |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.70 ms: 1.09x slower                                                     |
| regex_v8                 | 13.9 ms                                                     | 15.2 ms: 1.09x slower                                                     |
| coroutines               | 14.0 ms                                                     | 15.3 ms: 1.10x slower                                                     |
| comprehensions           | 14.1 us                                                     | 15.6 us: 1.11x slower                                                     |
| scimark_lu               | 58.1 ms                                                     | 64.5 ms: 1.11x slower                                                     |
| deepcopy_memo            | 23.8 us                                                     | 26.5 us: 1.11x slower                                                     |
| richards                 | 26.9 ms                                                     | 30.3 ms: 1.13x slower                                                     |
| scimark_sor              | 79.6 ms                                                     | 90.4 ms: 1.14x slower                                                     |
| unpickle_pure_python     | 133 us                                                      | 152 us: 1.14x slower                                                      |
| richards_super           | 30.5 ms                                                     | 34.9 ms: 1.15x slower                                                     |
| telco                    | 4.09 ms                                                     | 4.76 ms: 1.16x slower                                                     |
| go                       | 88.5 ms                                                     | 105 ms: 1.18x slower                                                      |
| hexiom                   | 4.03 ms                                                     | 4.80 ms: 1.19x slower                                                     |
| unpack_sequence          | 37.5 ns                                                     | 45.2 ns: 1.21x slower                                                     |
| dask                     | 259 ms                                                      | 391 ms: 1.51x slower                                                      |
| Geometric mean           | (ref)                                                       | 1.05x slower                                                              |

Benchmark hidden because not significant (5): create_gc_cycles, asyncio_tcp_ssl, python_startup_no_site, async_tree_cpu_io_mixed, asyncio_tcp
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
