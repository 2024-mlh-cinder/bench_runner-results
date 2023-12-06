
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.65 sec: 1.01x slower                                     |
| tornado_http   | 87.7 ms                                                     | 89.7 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.01x slower                                       |
| float          | 55.1 ms                                                     | 56.0 ms: 1.02x slower                                      |
| nbody          | 72.6 ms                                                     | 78.1 ms: 1.07x slower                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 119 ms: 1.05x faster                                       |
| regex_effbot   | 1.62 ms                                                     | 1.59 ms: 1.02x faster                                      |
| regex_compile  | 88.3 ms                                                     | 93.0 ms: 1.05x slower                                      |
| regex_v8       | 13.9 ms                                                     | 14.9 ms: 1.07x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.7 us: 1.03x faster                                      |
| pickle_list          | 2.86 us                                                     | 2.79 us: 1.02x faster                                      |
| unpickle_list        | 2.78 us                                                     | 2.72 us: 1.02x faster                                      |
| json_loads           | 13.4 us                                                     | 13.4 us: 1.00x faster                                      |
| xml_etree_generate   | 55.6 ms                                                     | 55.8 ms: 1.00x slower                                      |
| pickle               | 7.13 us                                                     | 7.20 us: 1.01x slower                                      |
| pickle_pure_python   | 196 us                                                      | 198 us: 1.01x slower                                       |
| xml_etree_process    | 38.4 ms                                                     | 39.0 ms: 1.02x slower                                      |
| xml_etree_parse      | 89.2 ms                                                     | 92.0 ms: 1.03x slower                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 65.6 ms: 1.05x slower                                      |
| json_dumps           | 5.60 ms                                                     | 5.88 ms: 1.05x slower                                      |
| unpickle_pure_python | 133 us                                                      | 143 us: 1.07x slower                                       |
| tomli_loads          | 1.37 sec                                                    | 1.54 sec: 1.13x slower                                     |
| Geometric mean       | (ref)                                                       | 1.02x slower                                               |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 19.9 ms: 1.02x slower                                      |
| python_startup_no_site | 16.1 ms                                                     | 16.7 ms: 1.03x slower                                      |
| Geometric mean         | (ref)                                                       | 1.03x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.60 ms: 1.10x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 47.0 ms: 1.10x faster                                      |
| raytrace                 | 191 ms                                                      | 183 ms: 1.05x faster                                       |
| async_tree_none          | 294 ms                                                      | 280 ms: 1.05x faster                                       |
| regex_dna                | 124 ms                                                      | 119 ms: 1.05x faster                                       |
| pickle_dict              | 19.3 us                                                     | 18.7 us: 1.03x faster                                      |
| crypto_pyaes             | 47.4 ms                                                     | 46.1 ms: 1.03x faster                                      |
| pickle_list              | 2.86 us                                                     | 2.79 us: 1.02x faster                                      |
| unpickle_list            | 2.78 us                                                     | 2.72 us: 1.02x faster                                      |
| regex_effbot             | 1.62 ms                                                     | 1.59 ms: 1.02x faster                                      |
| gc_traversal             | 1.48 ms                                                     | 1.47 ms: 1.01x faster                                      |
| json_loads               | 13.4 us                                                     | 13.4 us: 1.00x faster                                      |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.48 ms: 1.00x slower                                      |
| xml_etree_generate       | 55.6 ms                                                     | 55.8 ms: 1.00x slower                                      |
| sqlite_synth             | 1.76 us                                                     | 1.77 us: 1.01x slower                                      |
| pidigits                 | 150 ms                                                      | 151 ms: 1.01x slower                                       |
| pickle                   | 7.13 us                                                     | 7.20 us: 1.01x slower                                      |
| docutils                 | 1.63 sec                                                    | 1.65 sec: 1.01x slower                                     |
| scimark_monte_carlo      | 43.7 ms                                                     | 44.1 ms: 1.01x slower                                      |
| pickle_pure_python       | 196 us                                                      | 198 us: 1.01x slower                                       |
| mdp                      | 1.44 sec                                                    | 1.46 sec: 1.01x slower                                     |
| chaos                    | 42.8 ms                                                     | 43.3 ms: 1.01x slower                                      |
| bench_mp_pool            | 66.4 ms                                                     | 67.3 ms: 1.01x slower                                      |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 486 ms: 1.01x slower                                       |
| float                    | 55.1 ms                                                     | 56.0 ms: 1.02x slower                                      |
| xml_etree_process        | 38.4 ms                                                     | 39.0 ms: 1.02x slower                                      |
| scimark_fft              | 180 ms                                                      | 184 ms: 1.02x slower                                       |
| python_startup           | 19.5 ms                                                     | 19.9 ms: 1.02x slower                                      |
| tornado_http             | 87.7 ms                                                     | 89.7 ms: 1.02x slower                                      |
| meteor_contest           | 73.1 ms                                                     | 75.0 ms: 1.03x slower                                      |
| typing_runtime_protocols | 95.2 us                                                     | 97.8 us: 1.03x slower                                      |
| scimark_sor              | 79.6 ms                                                     | 82.1 ms: 1.03x slower                                      |
| xml_etree_parse          | 89.2 ms                                                     | 92.0 ms: 1.03x slower                                      |
| nqueens                  | 61.2 ms                                                     | 63.2 ms: 1.03x slower                                      |
| pathlib                  | 77.1 ms                                                     | 79.7 ms: 1.03x slower                                      |
| python_startup_no_site   | 16.1 ms                                                     | 16.7 ms: 1.03x slower                                      |
| deepcopy                 | 240 us                                                      | 249 us: 1.03x slower                                       |
| async_generators         | 235 ms                                                      | 244 ms: 1.04x slower                                       |
| spectral_norm            | 63.2 ms                                                     | 65.7 ms: 1.04x slower                                      |
| pprint_safe_repr         | 512 ms                                                      | 533 ms: 1.04x slower                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.09 sec: 1.04x slower                                     |
| scimark_lu               | 58.1 ms                                                     | 60.8 ms: 1.05x slower                                      |
| sqlglot_transpile        | 1.04 ms                                                     | 1.09 ms: 1.05x slower                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 65.6 ms: 1.05x slower                                      |
| sqlglot_normalize        | 185 ms                                                      | 195 ms: 1.05x slower                                       |
| json                     | 2.86 ms                                                     | 3.01 ms: 1.05x slower                                      |
| json_dumps               | 5.60 ms                                                     | 5.88 ms: 1.05x slower                                      |
| deepcopy_memo            | 23.8 us                                                     | 25.0 us: 1.05x slower                                      |
| sqlglot_optimize         | 34.4 ms                                                     | 36.2 ms: 1.05x slower                                      |
| regex_compile            | 88.3 ms                                                     | 93.0 ms: 1.05x slower                                      |
| async_tree_io            | 720 ms                                                      | 759 ms: 1.05x slower                                       |
| sqlglot_parse            | 820 us                                                      | 864 us: 1.05x slower                                       |
| pyflate                  | 297 ms                                                      | 313 ms: 1.06x slower                                       |
| mypy2                    | 207 ms                                                      | 220 ms: 1.06x slower                                       |
| deepcopy_reduce          | 2.13 us                                                     | 2.27 us: 1.06x slower                                      |
| async_tree_memoization   | 336 ms                                                      | 358 ms: 1.07x slower                                       |
| coroutines               | 14.0 ms                                                     | 15.0 ms: 1.07x slower                                      |
| logging_format           | 6.67 us                                                     | 7.15 us: 1.07x slower                                      |
| generators               | 22.7 ms                                                     | 24.4 ms: 1.07x slower                                      |
| logging_simple           | 6.21 us                                                     | 6.66 us: 1.07x slower                                      |
| unpack_sequence          | 37.5 ns                                                     | 40.2 ns: 1.07x slower                                      |
| unpickle_pure_python     | 133 us                                                      | 143 us: 1.07x slower                                       |
| deltablue                | 2.14 ms                                                     | 2.29 ms: 1.07x slower                                      |
| regex_v8                 | 13.9 ms                                                     | 14.9 ms: 1.07x slower                                      |
| nbody                    | 72.6 ms                                                     | 78.1 ms: 1.07x slower                                      |
| logging_silent           | 60.6 ns                                                     | 65.2 ns: 1.08x slower                                      |
| dulwich_log              | 42.4 ms                                                     | 45.7 ms: 1.08x slower                                      |
| fannkuch                 | 237 ms                                                      | 257 ms: 1.08x slower                                       |
| mako                     | 6.93 ms                                                     | 7.60 ms: 1.10x slower                                      |
| hexiom                   | 4.03 ms                                                     | 4.45 ms: 1.10x slower                                      |
| go                       | 88.5 ms                                                     | 98.4 ms: 1.11x slower                                      |
| richards                 | 26.9 ms                                                     | 30.0 ms: 1.11x slower                                      |
| pycparser                | 673 ms                                                      | 755 ms: 1.12x slower                                       |
| tomli_loads              | 1.37 sec                                                    | 1.54 sec: 1.13x slower                                     |
| telco                    | 4.09 ms                                                     | 4.61 ms: 1.13x slower                                      |
| comprehensions           | 14.1 us                                                     | 16.0 us: 1.13x slower                                      |
| richards_super           | 30.5 ms                                                     | 34.6 ms: 1.14x slower                                      |
| dask                     | 259 ms                                                      | 389 ms: 1.50x slower                                       |
| Geometric mean           | (ref)                                                       | 1.04x slower                                               |

Benchmark hidden because not significant (5): asyncio_tcp_ssl, create_gc_cycles, unpickle, bench_thread_pool, asyncio_tcp
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
