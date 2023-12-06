
# Results vs. 3.12.0

- fork: python
- ref: deea7c82682848b2a0db
- machine: windows-amd64
- commit hash: deea7c8
- commit date: 2023-09-05
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.64 sec: 1.01x slower                                                     |
| tornado_http   | 87.7 ms                                                     | 90.5 ms: 1.03x slower                                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.01x slower                                                       |
| float          | 55.1 ms                                                     | 56.5 ms: 1.02x slower                                                      |
| nbody          | 72.6 ms                                                     | 77.3 ms: 1.06x slower                                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 121 ms: 1.03x faster                                                       |
| regex_compile  | 88.3 ms                                                     | 93.2 ms: 1.06x slower                                                      |
| regex_v8       | 13.9 ms                                                     | 14.9 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.4 us: 1.05x faster                                                      |
| unpickle_list        | 2.78 us                                                     | 2.69 us: 1.03x faster                                                      |
| pickle_pure_python   | 196 us                                                      | 197 us: 1.00x slower                                                       |
| pickle               | 7.13 us                                                     | 7.18 us: 1.01x slower                                                      |
| xml_etree_process    | 38.4 ms                                                     | 38.9 ms: 1.01x slower                                                      |
| unpickle             | 8.16 us                                                     | 8.34 us: 1.02x slower                                                      |
| xml_etree_generate   | 55.6 ms                                                     | 56.9 ms: 1.02x slower                                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.0 ms: 1.02x slower                                                      |
| json_loads           | 13.4 us                                                     | 13.8 us: 1.03x slower                                                      |
| xml_etree_parse      | 89.2 ms                                                     | 91.7 ms: 1.03x slower                                                      |
| json_dumps           | 5.60 ms                                                     | 5.76 ms: 1.03x slower                                                      |
| unpickle_pure_python | 133 us                                                      | 140 us: 1.05x slower                                                       |
| tomli_loads          | 1.37 sec                                                    | 1.54 sec: 1.12x slower                                                     |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 18.7 ms: 1.04x faster                                                      |
| python_startup_no_site | 16.1 ms                                                     | 15.7 ms: 1.03x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.46 ms: 1.08x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 46.5 ms: 1.11x faster                                                      |
| async_tree_none          | 294 ms                                                      | 277 ms: 1.06x faster                                                       |
| raytrace                 | 191 ms                                                      | 182 ms: 1.05x faster                                                       |
| crypto_pyaes             | 47.4 ms                                                     | 45.2 ms: 1.05x faster                                                      |
| pickle_dict              | 19.3 us                                                     | 18.4 us: 1.05x faster                                                      |
| python_startup           | 19.5 ms                                                     | 18.7 ms: 1.04x faster                                                      |
| unpickle_list            | 2.78 us                                                     | 2.69 us: 1.03x faster                                                      |
| regex_dna                | 124 ms                                                      | 121 ms: 1.03x faster                                                       |
| python_startup_no_site   | 16.1 ms                                                     | 15.7 ms: 1.03x faster                                                      |
| create_gc_cycles         | 727 us                                                      | 718 us: 1.01x faster                                                       |
| mdp                      | 1.44 sec                                                    | 1.43 sec: 1.01x faster                                                     |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.47 ms: 1.00x faster                                                      |
| nqueens                  | 61.2 ms                                                     | 61.5 ms: 1.00x slower                                                      |
| pickle_pure_python       | 196 us                                                      | 197 us: 1.00x slower                                                       |
| pidigits                 | 150 ms                                                      | 151 ms: 1.01x slower                                                       |
| pickle                   | 7.13 us                                                     | 7.18 us: 1.01x slower                                                      |
| docutils                 | 1.63 sec                                                    | 1.64 sec: 1.01x slower                                                     |
| chaos                    | 42.8 ms                                                     | 43.2 ms: 1.01x slower                                                      |
| bench_mp_pool            | 66.4 ms                                                     | 67.2 ms: 1.01x slower                                                      |
| xml_etree_process        | 38.4 ms                                                     | 38.9 ms: 1.01x slower                                                      |
| async_generators         | 235 ms                                                      | 239 ms: 1.02x slower                                                       |
| meteor_contest           | 73.1 ms                                                     | 74.4 ms: 1.02x slower                                                      |
| bench_thread_pool        | 844 us                                                      | 860 us: 1.02x slower                                                       |
| unpickle                 | 8.16 us                                                     | 8.34 us: 1.02x slower                                                      |
| xml_etree_generate       | 55.6 ms                                                     | 56.9 ms: 1.02x slower                                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 64.0 ms: 1.02x slower                                                      |
| pathlib                  | 77.1 ms                                                     | 79.0 ms: 1.02x slower                                                      |
| float                    | 55.1 ms                                                     | 56.5 ms: 1.02x slower                                                      |
| scimark_monte_carlo      | 43.7 ms                                                     | 44.8 ms: 1.03x slower                                                      |
| json_loads               | 13.4 us                                                     | 13.8 us: 1.03x slower                                                      |
| xml_etree_parse          | 89.2 ms                                                     | 91.7 ms: 1.03x slower                                                      |
| json_dumps               | 5.60 ms                                                     | 5.76 ms: 1.03x slower                                                      |
| sqlglot_normalize        | 185 ms                                                      | 191 ms: 1.03x slower                                                       |
| deepcopy                 | 240 us                                                      | 247 us: 1.03x slower                                                       |
| scimark_lu               | 58.1 ms                                                     | 59.8 ms: 1.03x slower                                                      |
| typing_runtime_protocols | 95.2 us                                                     | 98.2 us: 1.03x slower                                                      |
| tornado_http             | 87.7 ms                                                     | 90.5 ms: 1.03x slower                                                      |
| deepcopy_memo            | 23.8 us                                                     | 24.6 us: 1.03x slower                                                      |
| pprint_safe_repr         | 512 ms                                                      | 529 ms: 1.03x slower                                                       |
| async_tree_io            | 720 ms                                                      | 745 ms: 1.04x slower                                                       |
| scimark_fft              | 180 ms                                                      | 187 ms: 1.04x slower                                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.08 sec: 1.04x slower                                                     |
| coroutines               | 14.0 ms                                                     | 14.5 ms: 1.04x slower                                                      |
| sqlglot_optimize         | 34.4 ms                                                     | 35.7 ms: 1.04x slower                                                      |
| deepcopy_reduce          | 2.13 us                                                     | 2.22 us: 1.04x slower                                                      |
| sqlglot_transpile        | 1.04 ms                                                     | 1.08 ms: 1.04x slower                                                      |
| pyflate                  | 297 ms                                                      | 310 ms: 1.04x slower                                                       |
| sqlglot_parse            | 820 us                                                      | 858 us: 1.05x slower                                                       |
| comprehensions           | 14.1 us                                                     | 14.8 us: 1.05x slower                                                      |
| deltablue                | 2.14 ms                                                     | 2.24 ms: 1.05x slower                                                      |
| json                     | 2.86 ms                                                     | 3.00 ms: 1.05x slower                                                      |
| spectral_norm            | 63.2 ms                                                     | 66.4 ms: 1.05x slower                                                      |
| hexiom                   | 4.03 ms                                                     | 4.25 ms: 1.05x slower                                                      |
| unpickle_pure_python     | 133 us                                                      | 140 us: 1.05x slower                                                       |
| scimark_sor              | 79.6 ms                                                     | 84.1 ms: 1.06x slower                                                      |
| regex_compile            | 88.3 ms                                                     | 93.2 ms: 1.06x slower                                                      |
| unpack_sequence          | 37.5 ns                                                     | 39.8 ns: 1.06x slower                                                      |
| async_tree_memoization   | 336 ms                                                      | 357 ms: 1.06x slower                                                       |
| nbody                    | 72.6 ms                                                     | 77.3 ms: 1.06x slower                                                      |
| logging_silent           | 60.6 ns                                                     | 64.5 ns: 1.07x slower                                                      |
| mypy2                    | 207 ms                                                      | 221 ms: 1.07x slower                                                       |
| generators               | 22.7 ms                                                     | 24.3 ms: 1.07x slower                                                      |
| dulwich_log              | 42.4 ms                                                     | 45.4 ms: 1.07x slower                                                      |
| richards_super           | 30.5 ms                                                     | 32.7 ms: 1.07x slower                                                      |
| logging_simple           | 6.21 us                                                     | 6.67 us: 1.07x slower                                                      |
| regex_v8                 | 13.9 ms                                                     | 14.9 ms: 1.07x slower                                                      |
| mako                     | 6.93 ms                                                     | 7.46 ms: 1.08x slower                                                      |
| fannkuch                 | 237 ms                                                      | 255 ms: 1.08x slower                                                       |
| richards                 | 26.9 ms                                                     | 29.2 ms: 1.08x slower                                                      |
| logging_format           | 6.67 us                                                     | 7.24 us: 1.09x slower                                                      |
| go                       | 88.5 ms                                                     | 96.9 ms: 1.10x slower                                                      |
| tomli_loads              | 1.37 sec                                                    | 1.54 sec: 1.12x slower                                                     |
| pycparser                | 673 ms                                                      | 758 ms: 1.13x slower                                                       |
| telco                    | 4.09 ms                                                     | 4.85 ms: 1.18x slower                                                      |
| dask                     | 259 ms                                                      | 385 ms: 1.49x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.03x slower                                                               |

Benchmark hidden because not significant (7): asyncio_tcp_ssl, regex_effbot, sqlite_synth, pickle_list, gc_traversal, async_tree_cpu_io_mixed, asyncio_tcp
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
