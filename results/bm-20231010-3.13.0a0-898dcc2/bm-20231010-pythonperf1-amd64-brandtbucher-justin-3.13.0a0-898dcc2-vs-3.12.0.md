
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 898dcc2
- commit date: 2023-10-10
- overall geometric mean: 1.10x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.70 sec: 1.04x slower                                             |
| tornado_http   | 87.7 ms                                                     | 91.2 ms: 1.04x slower                                              |
| Geometric mean | (ref)                                                       | 1.04x slower                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 54.6 ms: 1.01x faster                                              |
| pidigits       | 150 ms                                                      | 151 ms: 1.00x slower                                               |
| nbody          | 72.6 ms                                                     | 84.9 ms: 1.17x slower                                              |
| Geometric mean | (ref)                                                       | 1.05x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 119 ms: 1.04x faster                                               |
| regex_effbot   | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                              |
| regex_v8       | 13.9 ms                                                     | 15.2 ms: 1.09x slower                                              |
| regex_compile  | 88.3 ms                                                     | 98.1 ms: 1.11x slower                                              |
| Geometric mean | (ref)                                                       | 1.03x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.3 us: 1.05x faster                                              |
| unpickle_list        | 2.78 us                                                     | 2.69 us: 1.03x faster                                              |
| pickle               | 7.13 us                                                     | 7.11 us: 1.00x faster                                              |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                              |
| tomli_loads          | 1.37 sec                                                    | 1.40 sec: 1.02x slower                                             |
| pickle_list          | 2.86 us                                                     | 2.94 us: 1.03x slower                                              |
| xml_etree_parse      | 89.2 ms                                                     | 93.2 ms: 1.05x slower                                              |
| json_dumps           | 5.60 ms                                                     | 6.06 ms: 1.08x slower                                              |
| xml_etree_iterparse  | 62.5 ms                                                     | 70.2 ms: 1.12x slower                                              |
| pickle_pure_python   | 196 us                                                      | 225 us: 1.15x slower                                               |
| xml_etree_generate   | 55.6 ms                                                     | 64.1 ms: 1.15x slower                                              |
| xml_etree_process    | 38.4 ms                                                     | 45.9 ms: 1.19x slower                                              |
| unpickle_pure_python | 133 us                                                      | 175 us: 1.32x slower                                               |
| Geometric mean       | (ref)                                                       | 1.07x slower                                                       |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 20.0 ms: 1.03x slower                                              |
| python_startup_no_site | 16.1 ms                                                     | 16.6 ms: 1.03x slower                                              |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.72 ms: 1.03x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 46.3 ms: 1.11x faster                                              |
| pickle_dict              | 19.3 us                                                     | 18.3 us: 1.05x faster                                              |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.88 sec: 1.05x faster                                             |
| regex_dna                | 124 ms                                                      | 119 ms: 1.04x faster                                               |
| unpickle_list            | 2.78 us                                                     | 2.69 us: 1.03x faster                                              |
| sqlite_synth             | 1.76 us                                                     | 1.70 us: 1.03x faster                                              |
| mako                     | 6.93 ms                                                     | 6.72 ms: 1.03x faster                                              |
| regex_effbot             | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                              |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.42 ms: 1.02x faster                                              |
| float                    | 55.1 ms                                                     | 54.6 ms: 1.01x faster                                              |
| pickle                   | 7.13 us                                                     | 7.11 us: 1.00x faster                                              |
| pidigits                 | 150 ms                                                      | 151 ms: 1.00x slower                                               |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                              |
| pathlib                  | 77.1 ms                                                     | 78.4 ms: 1.02x slower                                              |
| crypto_pyaes             | 47.4 ms                                                     | 48.3 ms: 1.02x slower                                              |
| tomli_loads              | 1.37 sec                                                    | 1.40 sec: 1.02x slower                                             |
| pickle_list              | 2.86 us                                                     | 2.94 us: 1.03x slower                                              |
| python_startup           | 19.5 ms                                                     | 20.0 ms: 1.03x slower                                              |
| python_startup_no_site   | 16.1 ms                                                     | 16.6 ms: 1.03x slower                                              |
| tornado_http             | 87.7 ms                                                     | 91.2 ms: 1.04x slower                                              |
| docutils                 | 1.63 sec                                                    | 1.70 sec: 1.04x slower                                             |
| bench_mp_pool            | 66.4 ms                                                     | 69.3 ms: 1.04x slower                                              |
| bench_thread_pool        | 844 us                                                      | 880 us: 1.04x slower                                               |
| xml_etree_parse          | 89.2 ms                                                     | 93.2 ms: 1.05x slower                                              |
| json                     | 2.86 ms                                                     | 3.03 ms: 1.06x slower                                              |
| typing_runtime_protocols | 95.2 us                                                     | 101 us: 1.06x slower                                               |
| async_tree_io            | 720 ms                                                      | 771 ms: 1.07x slower                                               |
| dulwich_log              | 42.4 ms                                                     | 45.7 ms: 1.08x slower                                              |
| json_dumps               | 5.60 ms                                                     | 6.06 ms: 1.08x slower                                              |
| nqueens                  | 61.2 ms                                                     | 66.4 ms: 1.08x slower                                              |
| meteor_contest           | 73.1 ms                                                     | 79.3 ms: 1.08x slower                                              |
| regex_v8                 | 13.9 ms                                                     | 15.2 ms: 1.09x slower                                              |
| async_tree_memoization   | 336 ms                                                      | 368 ms: 1.09x slower                                               |
| fannkuch                 | 237 ms                                                      | 261 ms: 1.10x slower                                               |
| raytrace                 | 191 ms                                                      | 211 ms: 1.10x slower                                               |
| mypy2                    | 207 ms                                                      | 229 ms: 1.11x slower                                               |
| scimark_fft              | 180 ms                                                      | 200 ms: 1.11x slower                                               |
| regex_compile            | 88.3 ms                                                     | 98.1 ms: 1.11x slower                                              |
| logging_format           | 6.67 us                                                     | 7.42 us: 1.11x slower                                              |
| comprehensions           | 14.1 us                                                     | 15.8 us: 1.12x slower                                              |
| deepcopy_reduce          | 2.13 us                                                     | 2.39 us: 1.12x slower                                              |
| sqlglot_normalize        | 185 ms                                                      | 208 ms: 1.12x slower                                               |
| xml_etree_iterparse      | 62.5 ms                                                     | 70.2 ms: 1.12x slower                                              |
| logging_simple           | 6.21 us                                                     | 6.98 us: 1.12x slower                                              |
| sqlglot_optimize         | 34.4 ms                                                     | 38.7 ms: 1.13x slower                                              |
| pprint_safe_repr         | 512 ms                                                      | 582 ms: 1.14x slower                                               |
| async_generators         | 235 ms                                                      | 269 ms: 1.14x slower                                               |
| chaos                    | 42.8 ms                                                     | 48.9 ms: 1.14x slower                                              |
| pprint_pformat           | 1.04 sec                                                    | 1.20 sec: 1.15x slower                                             |
| pyflate                  | 297 ms                                                      | 342 ms: 1.15x slower                                               |
| pickle_pure_python       | 196 us                                                      | 225 us: 1.15x slower                                               |
| pycparser                | 673 ms                                                      | 776 ms: 1.15x slower                                               |
| scimark_monte_carlo      | 43.7 ms                                                     | 50.4 ms: 1.15x slower                                              |
| xml_etree_generate       | 55.6 ms                                                     | 64.1 ms: 1.15x slower                                              |
| deltablue                | 2.14 ms                                                     | 2.47 ms: 1.16x slower                                              |
| deepcopy                 | 240 us                                                      | 279 us: 1.16x slower                                               |
| telco                    | 4.09 ms                                                     | 4.77 ms: 1.17x slower                                              |
| nbody                    | 72.6 ms                                                     | 84.9 ms: 1.17x slower                                              |
| sqlglot_transpile        | 1.04 ms                                                     | 1.22 ms: 1.17x slower                                              |
| sqlglot_parse            | 820 us                                                      | 976 us: 1.19x slower                                               |
| xml_etree_process        | 38.4 ms                                                     | 45.9 ms: 1.19x slower                                              |
| hexiom                   | 4.03 ms                                                     | 4.83 ms: 1.20x slower                                              |
| go                       | 88.5 ms                                                     | 110 ms: 1.24x slower                                               |
| richards_super           | 30.5 ms                                                     | 38.6 ms: 1.27x slower                                              |
| spectral_norm            | 63.2 ms                                                     | 80.9 ms: 1.28x slower                                              |
| scimark_lu               | 58.1 ms                                                     | 75.0 ms: 1.29x slower                                              |
| unpack_sequence          | 37.5 ns                                                     | 48.4 ns: 1.29x slower                                              |
| richards                 | 26.9 ms                                                     | 34.8 ms: 1.29x slower                                              |
| scimark_sor              | 79.6 ms                                                     | 103 ms: 1.30x slower                                               |
| unpickle_pure_python     | 133 us                                                      | 175 us: 1.32x slower                                               |
| deepcopy_memo            | 23.8 us                                                     | 31.8 us: 1.34x slower                                              |
| coroutines               | 14.0 ms                                                     | 18.9 ms: 1.35x slower                                              |
| generators               | 22.7 ms                                                     | 34.0 ms: 1.50x slower                                              |
| logging_silent           | 60.6 ns                                                     | 90.9 ns: 1.50x slower                                              |
| Geometric mean           | (ref)                                                       | 1.10x slower                                                       |

Benchmark hidden because not significant (7): async_tree_none, async_tree_cpu_io_mixed, asyncio_tcp, mdp, unpickle, gc_traversal, create_gc_cycles
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.07x
- 95% likely to have a slowdown of 1.06x
- 99% likely to have a slowdown of 1.04x
