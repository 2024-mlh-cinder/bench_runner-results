
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.12x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.70 sec: 1.05x slower                                             |
| tornado_http   | 87.7 ms                                                     | 91.7 ms: 1.05x slower                                              |
| Geometric mean | (ref)                                                       | 1.05x slower                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 72.6 ms                                                     | 59.1 ms: 1.23x faster                                              |
| pidigits       | 150 ms                                                      | 152 ms: 1.01x slower                                               |
| float          | 55.1 ms                                                     | 65.9 ms: 1.19x slower                                              |
| Geometric mean | (ref)                                                       | 1.00x faster                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 118 ms: 1.05x faster                                               |
| regex_effbot   | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                              |
| regex_v8       | 13.9 ms                                                     | 15.1 ms: 1.09x slower                                              |
| regex_compile  | 88.3 ms                                                     | 102 ms: 1.15x slower                                               |
| Geometric mean | (ref)                                                       | 1.04x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.2 us: 1.06x faster                                              |
| pickle               | 7.13 us                                                     | 7.16 us: 1.00x slower                                              |
| unpickle             | 8.16 us                                                     | 8.33 us: 1.02x slower                                              |
| json_loads           | 13.4 us                                                     | 13.8 us: 1.03x slower                                              |
| tomli_loads          | 1.37 sec                                                    | 1.42 sec: 1.04x slower                                             |
| xml_etree_parse      | 89.2 ms                                                     | 93.6 ms: 1.05x slower                                              |
| json_dumps           | 5.60 ms                                                     | 6.06 ms: 1.08x slower                                              |
| xml_etree_generate   | 55.6 ms                                                     | 62.1 ms: 1.12x slower                                              |
| pickle_pure_python   | 196 us                                                      | 223 us: 1.14x slower                                               |
| xml_etree_iterparse  | 62.5 ms                                                     | 72.0 ms: 1.15x slower                                              |
| xml_etree_process    | 38.4 ms                                                     | 44.8 ms: 1.17x slower                                              |
| pickle_list          | 2.86 us                                                     | 3.40 us: 1.19x slower                                              |
| unpickle_pure_python | 133 us                                                      | 171 us: 1.29x slower                                               |
| Geometric mean       | (ref)                                                       | 1.08x slower                                                       |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                              |
| python_startup         | 19.5 ms                                                     | 20.1 ms: 1.03x slower                                              |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.80 ms: 1.13x slower                                              |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody                    | 72.6 ms                                                     | 59.1 ms: 1.23x faster                                              |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.70 sec: 1.16x faster                                             |
| pickle_dict              | 19.3 us                                                     | 18.2 us: 1.06x faster                                              |
| regex_dna                | 124 ms                                                      | 118 ms: 1.05x faster                                               |
| coverage                 | 51.5 ms                                                     | 48.9 ms: 1.05x faster                                              |
| regex_effbot             | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                              |
| pickle                   | 7.13 us                                                     | 7.16 us: 1.00x slower                                              |
| mdp                      | 1.44 sec                                                    | 1.45 sec: 1.01x slower                                             |
| pidigits                 | 150 ms                                                      | 152 ms: 1.01x slower                                               |
| sqlite_synth             | 1.76 us                                                     | 1.78 us: 1.02x slower                                              |
| gc_traversal             | 1.48 ms                                                     | 1.51 ms: 1.02x slower                                              |
| python_startup_no_site   | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                              |
| unpickle                 | 8.16 us                                                     | 8.33 us: 1.02x slower                                              |
| json_loads               | 13.4 us                                                     | 13.8 us: 1.03x slower                                              |
| pathlib                  | 77.1 ms                                                     | 79.5 ms: 1.03x slower                                              |
| python_startup           | 19.5 ms                                                     | 20.1 ms: 1.03x slower                                              |
| scimark_fft              | 180 ms                                                      | 186 ms: 1.03x slower                                               |
| json                     | 2.86 ms                                                     | 2.96 ms: 1.03x slower                                              |
| tomli_loads              | 1.37 sec                                                    | 1.42 sec: 1.04x slower                                             |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.58 ms: 1.04x slower                                              |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 498 ms: 1.04x slower                                               |
| docutils                 | 1.63 sec                                                    | 1.70 sec: 1.05x slower                                             |
| tornado_http             | 87.7 ms                                                     | 91.7 ms: 1.05x slower                                              |
| crypto_pyaes             | 47.4 ms                                                     | 49.6 ms: 1.05x slower                                              |
| xml_etree_parse          | 89.2 ms                                                     | 93.6 ms: 1.05x slower                                              |
| bench_thread_pool        | 844 us                                                      | 886 us: 1.05x slower                                               |
| bench_mp_pool            | 66.4 ms                                                     | 70.6 ms: 1.06x slower                                              |
| meteor_contest           | 73.1 ms                                                     | 78.2 ms: 1.07x slower                                              |
| async_tree_io            | 720 ms                                                      | 778 ms: 1.08x slower                                               |
| json_dumps               | 5.60 ms                                                     | 6.06 ms: 1.08x slower                                              |
| nqueens                  | 61.2 ms                                                     | 66.4 ms: 1.08x slower                                              |
| regex_v8                 | 13.9 ms                                                     | 15.1 ms: 1.09x slower                                              |
| dulwich_log              | 42.4 ms                                                     | 46.2 ms: 1.09x slower                                              |
| typing_runtime_protocols | 95.2 us                                                     | 104 us: 1.09x slower                                               |
| async_tree_memoization   | 336 ms                                                      | 371 ms: 1.10x slower                                               |
| fannkuch                 | 237 ms                                                      | 264 ms: 1.11x slower                                               |
| xml_etree_generate       | 55.6 ms                                                     | 62.1 ms: 1.12x slower                                              |
| deepcopy_reduce          | 2.13 us                                                     | 2.39 us: 1.12x slower                                              |
| mako                     | 6.93 ms                                                     | 7.80 ms: 1.13x slower                                              |
| mypy2                    | 207 ms                                                      | 233 ms: 1.13x slower                                               |
| raytrace                 | 191 ms                                                      | 216 ms: 1.13x slower                                               |
| sqlglot_normalize        | 185 ms                                                      | 210 ms: 1.13x slower                                               |
| deepcopy                 | 240 us                                                      | 273 us: 1.14x slower                                               |
| sqlglot_optimize         | 34.4 ms                                                     | 39.1 ms: 1.14x slower                                              |
| logging_format           | 6.67 us                                                     | 7.59 us: 1.14x slower                                              |
| pickle_pure_python       | 196 us                                                      | 223 us: 1.14x slower                                               |
| logging_simple           | 6.21 us                                                     | 7.10 us: 1.14x slower                                              |
| regex_compile            | 88.3 ms                                                     | 102 ms: 1.15x slower                                               |
| xml_etree_iterparse      | 62.5 ms                                                     | 72.0 ms: 1.15x slower                                              |
| chaos                    | 42.8 ms                                                     | 49.3 ms: 1.15x slower                                              |
| async_generators         | 235 ms                                                      | 274 ms: 1.16x slower                                               |
| pprint_safe_repr         | 512 ms                                                      | 597 ms: 1.17x slower                                               |
| xml_etree_process        | 38.4 ms                                                     | 44.8 ms: 1.17x slower                                              |
| pyflate                  | 297 ms                                                      | 347 ms: 1.17x slower                                               |
| pprint_pformat           | 1.04 sec                                                    | 1.23 sec: 1.17x slower                                             |
| comprehensions           | 14.1 us                                                     | 16.6 us: 1.17x slower                                              |
| pickle_list              | 2.86 us                                                     | 3.40 us: 1.19x slower                                              |
| float                    | 55.1 ms                                                     | 65.9 ms: 1.19x slower                                              |
| sqlglot_transpile        | 1.04 ms                                                     | 1.24 ms: 1.20x slower                                              |
| scimark_monte_carlo      | 43.7 ms                                                     | 52.5 ms: 1.20x slower                                              |
| sqlglot_parse            | 820 us                                                      | 996 us: 1.21x slower                                               |
| telco                    | 4.09 ms                                                     | 4.98 ms: 1.22x slower                                              |
| pycparser                | 673 ms                                                      | 825 ms: 1.22x slower                                               |
| spectral_norm            | 63.2 ms                                                     | 80.3 ms: 1.27x slower                                              |
| go                       | 88.5 ms                                                     | 113 ms: 1.27x slower                                               |
| deepcopy_memo            | 23.8 us                                                     | 30.4 us: 1.28x slower                                              |
| unpack_sequence          | 37.5 ns                                                     | 47.9 ns: 1.28x slower                                              |
| hexiom                   | 4.03 ms                                                     | 5.18 ms: 1.29x slower                                              |
| unpickle_pure_python     | 133 us                                                      | 171 us: 1.29x slower                                               |
| scimark_sor              | 79.6 ms                                                     | 103 ms: 1.29x slower                                               |
| richards_super           | 30.5 ms                                                     | 40.1 ms: 1.32x slower                                              |
| scimark_lu               | 58.1 ms                                                     | 76.9 ms: 1.32x slower                                              |
| richards                 | 26.9 ms                                                     | 35.9 ms: 1.34x slower                                              |
| coroutines               | 14.0 ms                                                     | 18.8 ms: 1.34x slower                                              |
| deltablue                | 2.14 ms                                                     | 2.92 ms: 1.37x slower                                              |
| generators               | 22.7 ms                                                     | 33.3 ms: 1.46x slower                                              |
| logging_silent           | 60.6 ns                                                     | 91.9 ns: 1.52x slower                                              |
| dask                     | 259 ms                                                      | 409 ms: 1.58x slower                                               |
| Geometric mean           | (ref)                                                       | 1.12x slower                                                       |

Benchmark hidden because not significant (4): create_gc_cycles, async_tree_none, unpickle_list, asyncio_tcp
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.08x
- 95% likely to have a slowdown of 1.07x
- 99% likely to have a slowdown of 1.06x
