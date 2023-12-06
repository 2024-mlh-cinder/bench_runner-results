
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.02x slower
- HPT reliability: 97.62%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.62 sec: 1.01x faster                                     |
| tornado_http   | 87.7 ms                                                     | 88.5 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 55.1 ms                                                     | 54.5 ms: 1.01x faster                                      |
| nbody          | 72.6 ms                                                     | 74.9 ms: 1.03x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 118 ms: 1.05x faster                                       |
| regex_effbot   | 1.62 ms                                                     | 1.56 ms: 1.04x faster                                      |
| regex_compile  | 88.3 ms                                                     | 90.9 ms: 1.03x slower                                      |
| regex_v8       | 13.9 ms                                                     | 14.9 ms: 1.07x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.3 us: 1.05x faster                                      |
| unpickle_list        | 2.78 us                                                     | 2.73 us: 1.02x faster                                      |
| pickle_pure_python   | 196 us                                                      | 193 us: 1.01x faster                                       |
| xml_etree_process    | 38.4 ms                                                     | 37.9 ms: 1.01x faster                                      |
| xml_etree_generate   | 55.6 ms                                                     | 55.4 ms: 1.00x faster                                      |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                      |
| json_dumps           | 5.60 ms                                                     | 5.66 ms: 1.01x slower                                      |
| pickle               | 7.13 us                                                     | 7.24 us: 1.01x slower                                      |
| unpickle             | 8.16 us                                                     | 8.29 us: 1.02x slower                                      |
| unpickle_pure_python | 133 us                                                      | 136 us: 1.02x slower                                       |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.4 ms: 1.03x slower                                      |
| xml_etree_parse      | 89.2 ms                                                     | 91.9 ms: 1.03x slower                                      |
| tomli_loads          | 1.37 sec                                                    | 1.48 sec: 1.08x slower                                     |
| pickle_list          | 2.86 us                                                     | 3.35 us: 1.17x slower                                      |
| Geometric mean       | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.5 ms: 1.02x slower                                      |
| python_startup         | 19.5 ms                                                     | 20.0 ms: 1.03x slower                                      |
| Geometric mean         | (ref)                                                       | 1.03x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.43 ms: 1.07x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 45.7 ms: 1.13x faster                                      |
| async_tree_none          | 294 ms                                                      | 264 ms: 1.11x faster                                       |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.77 sec: 1.11x faster                                     |
| raytrace                 | 191 ms                                                      | 173 ms: 1.11x faster                                       |
| pickle_dict              | 19.3 us                                                     | 18.3 us: 1.05x faster                                      |
| regex_dna                | 124 ms                                                      | 118 ms: 1.05x faster                                       |
| crypto_pyaes             | 47.4 ms                                                     | 45.1 ms: 1.05x faster                                      |
| mdp                      | 1.44 sec                                                    | 1.38 sec: 1.04x faster                                     |
| regex_effbot             | 1.62 ms                                                     | 1.56 ms: 1.04x faster                                      |
| chaos                    | 42.8 ms                                                     | 41.3 ms: 1.04x faster                                      |
| deepcopy                 | 240 us                                                      | 234 us: 1.03x faster                                       |
| unpickle_list            | 2.78 us                                                     | 2.73 us: 1.02x faster                                      |
| pickle_pure_python       | 196 us                                                      | 193 us: 1.01x faster                                       |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 472 ms: 1.01x faster                                       |
| xml_etree_process        | 38.4 ms                                                     | 37.9 ms: 1.01x faster                                      |
| json                     | 2.86 ms                                                     | 2.82 ms: 1.01x faster                                      |
| sqlglot_normalize        | 185 ms                                                      | 183 ms: 1.01x faster                                       |
| float                    | 55.1 ms                                                     | 54.5 ms: 1.01x faster                                      |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.46 ms: 1.01x faster                                      |
| docutils                 | 1.63 sec                                                    | 1.62 sec: 1.01x faster                                     |
| sqlglot_parse            | 820 us                                                      | 814 us: 1.01x faster                                       |
| deepcopy_reduce          | 2.13 us                                                     | 2.12 us: 1.01x faster                                      |
| scimark_monte_carlo      | 43.7 ms                                                     | 43.4 ms: 1.01x faster                                      |
| scimark_fft              | 180 ms                                                      | 179 ms: 1.00x faster                                       |
| xml_etree_generate       | 55.6 ms                                                     | 55.4 ms: 1.00x faster                                      |
| meteor_contest           | 73.1 ms                                                     | 73.5 ms: 1.01x slower                                      |
| nqueens                  | 61.2 ms                                                     | 61.7 ms: 1.01x slower                                      |
| pprint_safe_repr         | 512 ms                                                      | 516 ms: 1.01x slower                                       |
| deepcopy_memo            | 23.8 us                                                     | 24.0 us: 1.01x slower                                      |
| gc_traversal             | 1.48 ms                                                     | 1.50 ms: 1.01x slower                                      |
| tornado_http             | 87.7 ms                                                     | 88.5 ms: 1.01x slower                                      |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                      |
| sqlglot_optimize         | 34.4 ms                                                     | 34.8 ms: 1.01x slower                                      |
| spectral_norm            | 63.2 ms                                                     | 63.9 ms: 1.01x slower                                      |
| async_generators         | 235 ms                                                      | 238 ms: 1.01x slower                                       |
| json_dumps               | 5.60 ms                                                     | 5.66 ms: 1.01x slower                                      |
| scimark_sor              | 79.6 ms                                                     | 80.6 ms: 1.01x slower                                      |
| comprehensions           | 14.1 us                                                     | 14.3 us: 1.01x slower                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.01x slower                                     |
| pathlib                  | 77.1 ms                                                     | 78.2 ms: 1.01x slower                                      |
| pickle                   | 7.13 us                                                     | 7.24 us: 1.01x slower                                      |
| unpickle                 | 8.16 us                                                     | 8.29 us: 1.02x slower                                      |
| create_gc_cycles         | 727 us                                                      | 739 us: 1.02x slower                                       |
| deltablue                | 2.14 ms                                                     | 2.18 ms: 1.02x slower                                      |
| go                       | 88.5 ms                                                     | 90.3 ms: 1.02x slower                                      |
| pyflate                  | 297 ms                                                      | 303 ms: 1.02x slower                                       |
| unpickle_pure_python     | 133 us                                                      | 136 us: 1.02x slower                                       |
| python_startup_no_site   | 16.1 ms                                                     | 16.5 ms: 1.02x slower                                      |
| logging_format           | 6.67 us                                                     | 6.84 us: 1.02x slower                                      |
| python_startup           | 19.5 ms                                                     | 20.0 ms: 1.03x slower                                      |
| logging_simple           | 6.21 us                                                     | 6.39 us: 1.03x slower                                      |
| scimark_lu               | 58.1 ms                                                     | 59.8 ms: 1.03x slower                                      |
| regex_compile            | 88.3 ms                                                     | 90.9 ms: 1.03x slower                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 64.4 ms: 1.03x slower                                      |
| xml_etree_parse          | 89.2 ms                                                     | 91.9 ms: 1.03x slower                                      |
| mypy2                    | 207 ms                                                      | 214 ms: 1.03x slower                                       |
| async_tree_memoization   | 336 ms                                                      | 346 ms: 1.03x slower                                       |
| nbody                    | 72.6 ms                                                     | 74.9 ms: 1.03x slower                                      |
| hexiom                   | 4.03 ms                                                     | 4.21 ms: 1.05x slower                                      |
| unpack_sequence          | 37.5 ns                                                     | 39.4 ns: 1.05x slower                                      |
| coroutines               | 14.0 ms                                                     | 14.7 ms: 1.05x slower                                      |
| dulwich_log              | 42.4 ms                                                     | 44.9 ms: 1.06x slower                                      |
| richards_super           | 30.5 ms                                                     | 32.3 ms: 1.06x slower                                      |
| bench_mp_pool            | 66.4 ms                                                     | 70.6 ms: 1.06x slower                                      |
| typing_runtime_protocols | 95.2 us                                                     | 101 us: 1.07x slower                                       |
| mako                     | 6.93 ms                                                     | 7.43 ms: 1.07x slower                                      |
| regex_v8                 | 13.9 ms                                                     | 14.9 ms: 1.07x slower                                      |
| logging_silent           | 60.6 ns                                                     | 65.0 ns: 1.07x slower                                      |
| richards                 | 26.9 ms                                                     | 29.0 ms: 1.08x slower                                      |
| tomli_loads              | 1.37 sec                                                    | 1.48 sec: 1.08x slower                                     |
| fannkuch                 | 237 ms                                                      | 266 ms: 1.12x slower                                       |
| pickle_list              | 2.86 us                                                     | 3.35 us: 1.17x slower                                      |
| telco                    | 4.09 ms                                                     | 4.80 ms: 1.17x slower                                      |
| pycparser                | 673 ms                                                      | 795 ms: 1.18x slower                                       |
| dask                     | 259 ms                                                      | 370 ms: 1.43x slower                                       |
| Geometric mean           | (ref)                                                       | 1.02x slower                                               |

Benchmark hidden because not significant (7): bench_thread_pool, sqlglot_transpile, sqlite_synth, asyncio_tcp, generators, pidigits, async_tree_io
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 97.62% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
