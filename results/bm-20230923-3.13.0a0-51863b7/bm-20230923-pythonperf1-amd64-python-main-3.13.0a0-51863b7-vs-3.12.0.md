
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.02x slower
- HPT reliability: 99.70%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                     |
| Geometric mean | (ref)                                                       | 1.01x faster                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 55.1 ms                                                     | 54.8 ms: 1.01x faster                                      |
| pidigits       | 150 ms                                                      | 150 ms: 1.00x faster                                       |
| nbody          | 72.6 ms                                                     | 76.0 ms: 1.05x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 122 ms: 1.02x faster                                       |
| regex_effbot   | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                      |
| regex_compile  | 88.3 ms                                                     | 90.1 ms: 1.02x slower                                      |
| regex_v8       | 13.9 ms                                                     | 14.8 ms: 1.07x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.65 us: 1.05x faster                                      |
| pickle_dict          | 19.3 us                                                     | 18.7 us: 1.03x faster                                      |
| pickle_pure_python   | 196 us                                                      | 192 us: 1.02x faster                                       |
| unpickle             | 8.16 us                                                     | 8.29 us: 1.02x slower                                      |
| xml_etree_generate   | 55.6 ms                                                     | 56.7 ms: 1.02x slower                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 63.8 ms: 1.02x slower                                      |
| unpickle_pure_python | 133 us                                                      | 136 us: 1.02x slower                                       |
| json_dumps           | 5.60 ms                                                     | 5.74 ms: 1.03x slower                                      |
| xml_etree_parse      | 89.2 ms                                                     | 93.1 ms: 1.04x slower                                      |
| tomli_loads          | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                     |
| pickle_list          | 2.86 us                                                     | 3.38 us: 1.18x slower                                      |
| Geometric mean       | (ref)                                                       | 1.02x slower                                               |

Benchmark hidden because not significant (3): json_loads, pickle, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                      |
| python_startup         | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                      |
| Geometric mean         | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.39 ms: 1.07x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 45.9 ms: 1.12x faster                                      |
| async_tree_none          | 294 ms                                                      | 262 ms: 1.12x faster                                       |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.79 sec: 1.10x faster                                     |
| raytrace                 | 191 ms                                                      | 177 ms: 1.08x faster                                       |
| unpickle_list            | 2.78 us                                                     | 2.65 us: 1.05x faster                                      |
| scimark_monte_carlo      | 43.7 ms                                                     | 41.7 ms: 1.05x faster                                      |
| crypto_pyaes             | 47.4 ms                                                     | 45.7 ms: 1.04x faster                                      |
| chaos                    | 42.8 ms                                                     | 41.4 ms: 1.03x faster                                      |
| pickle_dict              | 19.3 us                                                     | 18.7 us: 1.03x faster                                      |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 466 ms: 1.03x faster                                       |
| deepcopy                 | 240 us                                                      | 234 us: 1.03x faster                                       |
| regex_dna                | 124 ms                                                      | 122 ms: 1.02x faster                                       |
| sqlglot_parse            | 820 us                                                      | 805 us: 1.02x faster                                       |
| pickle_pure_python       | 196 us                                                      | 192 us: 1.02x faster                                       |
| docutils                 | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                     |
| sqlglot_transpile        | 1.04 ms                                                     | 1.02 ms: 1.01x faster                                      |
| sqlglot_normalize        | 185 ms                                                      | 184 ms: 1.01x faster                                       |
| deepcopy_reduce          | 2.13 us                                                     | 2.11 us: 1.01x faster                                      |
| nqueens                  | 61.2 ms                                                     | 60.8 ms: 1.01x faster                                      |
| regex_effbot             | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                      |
| float                    | 55.1 ms                                                     | 54.8 ms: 1.01x faster                                      |
| meteor_contest           | 73.1 ms                                                     | 72.8 ms: 1.00x faster                                      |
| spectral_norm            | 63.2 ms                                                     | 63.0 ms: 1.00x faster                                      |
| pidigits                 | 150 ms                                                      | 150 ms: 1.00x faster                                       |
| logging_format           | 6.67 us                                                     | 6.73 us: 1.01x slower                                      |
| gc_traversal             | 1.48 ms                                                     | 1.50 ms: 1.01x slower                                      |
| sqlglot_optimize         | 34.4 ms                                                     | 34.7 ms: 1.01x slower                                      |
| typing_runtime_protocols | 95.2 us                                                     | 96.0 us: 1.01x slower                                      |
| pyflate                  | 297 ms                                                      | 300 ms: 1.01x slower                                       |
| logging_simple           | 6.21 us                                                     | 6.28 us: 1.01x slower                                      |
| comprehensions           | 14.1 us                                                     | 14.3 us: 1.01x slower                                      |
| scimark_fft              | 180 ms                                                      | 183 ms: 1.01x slower                                       |
| deepcopy_memo            | 23.8 us                                                     | 24.1 us: 1.01x slower                                      |
| scimark_sor              | 79.6 ms                                                     | 80.8 ms: 1.02x slower                                      |
| python_startup_no_site   | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                      |
| create_gc_cycles         | 727 us                                                      | 739 us: 1.02x slower                                       |
| unpickle                 | 8.16 us                                                     | 8.29 us: 1.02x slower                                      |
| pprint_safe_repr         | 512 ms                                                      | 521 ms: 1.02x slower                                       |
| mdp                      | 1.44 sec                                                    | 1.47 sec: 1.02x slower                                     |
| python_startup           | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                      |
| async_generators         | 235 ms                                                      | 240 ms: 1.02x slower                                       |
| xml_etree_generate       | 55.6 ms                                                     | 56.7 ms: 1.02x slower                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 63.8 ms: 1.02x slower                                      |
| pathlib                  | 77.1 ms                                                     | 78.7 ms: 1.02x slower                                      |
| sqlite_synth             | 1.76 us                                                     | 1.79 us: 1.02x slower                                      |
| regex_compile            | 88.3 ms                                                     | 90.1 ms: 1.02x slower                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.07 sec: 1.02x slower                                     |
| deltablue                | 2.14 ms                                                     | 2.18 ms: 1.02x slower                                      |
| unpickle_pure_python     | 133 us                                                      | 136 us: 1.02x slower                                       |
| async_tree_memoization   | 336 ms                                                      | 344 ms: 1.02x slower                                       |
| json_dumps               | 5.60 ms                                                     | 5.74 ms: 1.03x slower                                      |
| scimark_lu               | 58.1 ms                                                     | 59.8 ms: 1.03x slower                                      |
| mypy2                    | 207 ms                                                      | 214 ms: 1.03x slower                                       |
| go                       | 88.5 ms                                                     | 91.6 ms: 1.04x slower                                      |
| hexiom                   | 4.03 ms                                                     | 4.21 ms: 1.04x slower                                      |
| xml_etree_parse          | 89.2 ms                                                     | 93.1 ms: 1.04x slower                                      |
| coroutines               | 14.0 ms                                                     | 14.6 ms: 1.04x slower                                      |
| unpack_sequence          | 37.5 ns                                                     | 39.2 ns: 1.05x slower                                      |
| nbody                    | 72.6 ms                                                     | 76.0 ms: 1.05x slower                                      |
| richards_super           | 30.5 ms                                                     | 32.0 ms: 1.05x slower                                      |
| logging_silent           | 60.6 ns                                                     | 63.7 ns: 1.05x slower                                      |
| bench_mp_pool            | 66.4 ms                                                     | 70.6 ms: 1.06x slower                                      |
| dulwich_log              | 42.4 ms                                                     | 45.2 ms: 1.06x slower                                      |
| mako                     | 6.93 ms                                                     | 7.39 ms: 1.07x slower                                      |
| regex_v8                 | 13.9 ms                                                     | 14.8 ms: 1.07x slower                                      |
| richards                 | 26.9 ms                                                     | 28.8 ms: 1.07x slower                                      |
| fannkuch                 | 237 ms                                                      | 257 ms: 1.09x slower                                       |
| tomli_loads              | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                     |
| telco                    | 4.09 ms                                                     | 4.77 ms: 1.16x slower                                      |
| pickle_list              | 2.86 us                                                     | 3.38 us: 1.18x slower                                      |
| pycparser                | 673 ms                                                      | 796 ms: 1.18x slower                                       |
| dask                     | 259 ms                                                      | 368 ms: 1.42x slower                                       |
| Geometric mean           | (ref)                                                       | 1.02x slower                                               |

Benchmark hidden because not significant (10): bench_thread_pool, scimark_sparse_mat_mult, json_loads, pickle, xml_etree_process, async_tree_io, tornado_http, generators, asyncio_tcp, json
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 99.70% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
