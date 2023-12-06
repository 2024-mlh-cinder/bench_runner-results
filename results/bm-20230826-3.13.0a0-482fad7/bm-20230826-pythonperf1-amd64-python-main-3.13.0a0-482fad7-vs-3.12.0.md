
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 482fad7
- commit date: 2023-08-26
- overall geometric mean: 1.03x slower
- HPT reliability: 99.81%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.62 sec: 1.01x faster                                     |
| Geometric mean | (ref)                                                       | 1.01x faster                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                       |
| nbody          | 72.6 ms                                                     | 75.4 ms: 1.04x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 120 ms: 1.04x faster                                       |
| regex_effbot   | 1.62 ms                                                     | 1.60 ms: 1.02x faster                                      |
| regex_compile  | 88.3 ms                                                     | 90.7 ms: 1.03x slower                                      |
| regex_v8       | 13.9 ms                                                     | 14.7 ms: 1.06x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.4 us: 1.05x faster                                      |
| pickle_pure_python   | 196 us                                                      | 197 us: 1.00x slower                                       |
| xml_etree_process    | 38.4 ms                                                     | 39.0 ms: 1.02x slower                                      |
| json_dumps           | 5.60 ms                                                     | 5.71 ms: 1.02x slower                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.1 ms: 1.03x slower                                      |
| xml_etree_generate   | 55.6 ms                                                     | 57.0 ms: 1.03x slower                                      |
| xml_etree_parse      | 89.2 ms                                                     | 93.4 ms: 1.05x slower                                      |
| unpickle_list        | 2.78 us                                                     | 2.92 us: 1.05x slower                                      |
| unpickle_pure_python | 133 us                                                      | 144 us: 1.08x slower                                       |
| tomli_loads          | 1.37 sec                                                    | 1.48 sec: 1.08x slower                                     |
| unpickle             | 8.16 us                                                     | 9.16 us: 1.12x slower                                      |
| Geometric mean       | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (3): pickle_list, pickle, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup | 19.5 ms                                                     | 19.0 ms: 1.02x faster                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.47 ms: 1.08x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 46.9 ms: 1.10x faster                                      |
| async_tree_none          | 294 ms                                                      | 268 ms: 1.10x faster                                       |
| raytrace                 | 191 ms                                                      | 175 ms: 1.09x faster                                       |
| pickle_dict              | 19.3 us                                                     | 18.4 us: 1.05x faster                                      |
| crypto_pyaes             | 47.4 ms                                                     | 45.3 ms: 1.05x faster                                      |
| regex_dna                | 124 ms                                                      | 120 ms: 1.04x faster                                       |
| mdp                      | 1.44 sec                                                    | 1.40 sec: 1.03x faster                                     |
| python_startup           | 19.5 ms                                                     | 19.0 ms: 1.02x faster                                      |
| pidigits                 | 150 ms                                                      | 147 ms: 1.02x faster                                       |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 470 ms: 1.02x faster                                       |
| regex_effbot             | 1.62 ms                                                     | 1.60 ms: 1.02x faster                                      |
| sqlite_synth             | 1.76 us                                                     | 1.74 us: 1.01x faster                                      |
| docutils                 | 1.63 sec                                                    | 1.62 sec: 1.01x faster                                     |
| typing_runtime_protocols | 95.2 us                                                     | 94.5 us: 1.01x faster                                      |
| deepcopy                 | 240 us                                                      | 239 us: 1.01x faster                                       |
| chaos                    | 42.8 ms                                                     | 42.9 ms: 1.00x slower                                      |
| pickle_pure_python       | 196 us                                                      | 197 us: 1.00x slower                                       |
| sqlglot_normalize        | 185 ms                                                      | 187 ms: 1.01x slower                                       |
| deepcopy_reduce          | 2.13 us                                                     | 2.16 us: 1.01x slower                                      |
| sqlglot_parse            | 820 us                                                      | 831 us: 1.01x slower                                       |
| xml_etree_process        | 38.4 ms                                                     | 39.0 ms: 1.02x slower                                      |
| sqlglot_optimize         | 34.4 ms                                                     | 34.9 ms: 1.02x slower                                      |
| sqlglot_transpile        | 1.04 ms                                                     | 1.05 ms: 1.02x slower                                      |
| pathlib                  | 77.1 ms                                                     | 78.4 ms: 1.02x slower                                      |
| json_dumps               | 5.60 ms                                                     | 5.71 ms: 1.02x slower                                      |
| deepcopy_memo            | 23.8 us                                                     | 24.3 us: 1.02x slower                                      |
| async_tree_memoization   | 336 ms                                                      | 344 ms: 1.02x slower                                       |
| meteor_contest           | 73.1 ms                                                     | 74.9 ms: 1.02x slower                                      |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.54 ms: 1.02x slower                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 64.1 ms: 1.03x slower                                      |
| xml_etree_generate       | 55.6 ms                                                     | 57.0 ms: 1.03x slower                                      |
| async_generators         | 235 ms                                                      | 241 ms: 1.03x slower                                       |
| regex_compile            | 88.3 ms                                                     | 90.7 ms: 1.03x slower                                      |
| mypy2                    | 207 ms                                                      | 213 ms: 1.03x slower                                       |
| logging_format           | 6.67 us                                                     | 6.89 us: 1.03x slower                                      |
| spectral_norm            | 63.2 ms                                                     | 65.4 ms: 1.03x slower                                      |
| scimark_fft              | 180 ms                                                      | 186 ms: 1.04x slower                                       |
| pprint_safe_repr         | 512 ms                                                      | 531 ms: 1.04x slower                                       |
| nbody                    | 72.6 ms                                                     | 75.4 ms: 1.04x slower                                      |
| pyflate                  | 297 ms                                                      | 309 ms: 1.04x slower                                       |
| logging_simple           | 6.21 us                                                     | 6.48 us: 1.04x slower                                      |
| deltablue                | 2.14 ms                                                     | 2.23 ms: 1.04x slower                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.09 sec: 1.05x slower                                     |
| xml_etree_parse          | 89.2 ms                                                     | 93.4 ms: 1.05x slower                                      |
| unpickle_list            | 2.78 us                                                     | 2.92 us: 1.05x slower                                      |
| comprehensions           | 14.1 us                                                     | 14.8 us: 1.05x slower                                      |
| dulwich_log              | 42.4 ms                                                     | 44.6 ms: 1.05x slower                                      |
| scimark_monte_carlo      | 43.7 ms                                                     | 46.0 ms: 1.05x slower                                      |
| regex_v8                 | 13.9 ms                                                     | 14.7 ms: 1.06x slower                                      |
| logging_silent           | 60.6 ns                                                     | 64.0 ns: 1.06x slower                                      |
| scimark_lu               | 58.1 ms                                                     | 61.4 ms: 1.06x slower                                      |
| go                       | 88.5 ms                                                     | 93.7 ms: 1.06x slower                                      |
| unpack_sequence          | 37.5 ns                                                     | 39.7 ns: 1.06x slower                                      |
| generators               | 22.7 ms                                                     | 24.1 ms: 1.06x slower                                      |
| pycparser                | 673 ms                                                      | 716 ms: 1.06x slower                                       |
| hexiom                   | 4.03 ms                                                     | 4.32 ms: 1.07x slower                                      |
| mako                     | 6.93 ms                                                     | 7.47 ms: 1.08x slower                                      |
| coroutines               | 14.0 ms                                                     | 15.1 ms: 1.08x slower                                      |
| unpickle_pure_python     | 133 us                                                      | 144 us: 1.08x slower                                       |
| tomli_loads              | 1.37 sec                                                    | 1.48 sec: 1.08x slower                                     |
| richards                 | 26.9 ms                                                     | 29.4 ms: 1.09x slower                                      |
| richards_super           | 30.5 ms                                                     | 33.3 ms: 1.09x slower                                      |
| scimark_sor              | 79.6 ms                                                     | 87.9 ms: 1.10x slower                                      |
| unpickle                 | 8.16 us                                                     | 9.16 us: 1.12x slower                                      |
| telco                    | 4.09 ms                                                     | 4.67 ms: 1.14x slower                                      |
| fannkuch                 | 237 ms                                                      | 272 ms: 1.15x slower                                       |
| dask                     | 259 ms                                                      | 373 ms: 1.44x slower                                       |
| Geometric mean           | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (15): asyncio_tcp, create_gc_cycles, asyncio_tcp_ssl, json, bench_mp_pool, tornado_http, nqueens, pickle_list, pickle, python_startup_no_site, json_loads, float, async_tree_io, gc_traversal, bench_thread_pool
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 99.81% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
