
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.00x faster
- HPT reliability: 98.29%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                       |
| tornado_http   | 87.7 ms                                                     | 88.4 ms: 1.01x slower                                        |
| Geometric mean | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 72.6 ms                                                     | 70.3 ms: 1.03x faster                                        |
| float          | 55.1 ms                                                     | 53.8 ms: 1.02x faster                                        |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                       | 1.03x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 116 ms: 1.07x faster                                         |
| regex_v8       | 13.9 ms                                                     | 13.1 ms: 1.06x faster                                        |
| regex_effbot   | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                        |
| regex_compile  | 88.3 ms                                                     | 87.5 ms: 1.01x faster                                        |
| Geometric mean | (ref)                                                       | 1.04x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.4 us: 1.04x faster                                        |
| pickle_list          | 2.86 us                                                     | 2.81 us: 1.02x faster                                        |
| xml_etree_process    | 38.4 ms                                                     | 37.8 ms: 1.02x faster                                        |
| tomli_loads          | 1.37 sec                                                    | 1.36 sec: 1.01x faster                                       |
| pickle_pure_python   | 196 us                                                      | 195 us: 1.00x faster                                         |
| xml_etree_generate   | 55.6 ms                                                     | 55.8 ms: 1.00x slower                                        |
| unpickle_pure_python | 133 us                                                      | 135 us: 1.01x slower                                         |
| xml_etree_iterparse  | 62.5 ms                                                     | 63.5 ms: 1.02x slower                                        |
| xml_etree_parse      | 89.2 ms                                                     | 91.0 ms: 1.02x slower                                        |
| json_loads           | 13.4 us                                                     | 13.7 us: 1.02x slower                                        |
| json_dumps           | 5.60 ms                                                     | 5.72 ms: 1.02x slower                                        |
| unpickle             | 8.16 us                                                     | 8.40 us: 1.03x slower                                        |
| unpickle_list        | 2.78 us                                                     | 2.90 us: 1.04x slower                                        |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                 |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.7 ms: 1.04x slower                                        |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                 |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-pythonperf1-amd64-python-3.12-3.12.0rc1+-3e20303 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna                | 124 ms                                                      | 116 ms: 1.07x faster                                         |
| regex_v8                 | 13.9 ms                                                     | 13.1 ms: 1.06x faster                                        |
| richards_super           | 30.5 ms                                                     | 29.0 ms: 1.05x faster                                        |
| pickle_dict              | 19.3 us                                                     | 18.4 us: 1.04x faster                                        |
| richards                 | 26.9 ms                                                     | 25.8 ms: 1.04x faster                                        |
| dulwich_log              | 42.4 ms                                                     | 40.8 ms: 1.04x faster                                        |
| nbody                    | 72.6 ms                                                     | 70.3 ms: 1.03x faster                                        |
| sqlglot_parse            | 820 us                                                      | 797 us: 1.03x faster                                         |
| scimark_monte_carlo      | 43.7 ms                                                     | 42.5 ms: 1.03x faster                                        |
| regex_effbot             | 1.62 ms                                                     | 1.58 ms: 1.03x faster                                        |
| async_tree_none          | 294 ms                                                      | 287 ms: 1.03x faster                                         |
| float                    | 55.1 ms                                                     | 53.8 ms: 1.02x faster                                        |
| coverage                 | 51.5 ms                                                     | 50.3 ms: 1.02x faster                                        |
| deepcopy_memo            | 23.8 us                                                     | 23.3 us: 1.02x faster                                        |
| crypto_pyaes             | 47.4 ms                                                     | 46.4 ms: 1.02x faster                                        |
| pidigits                 | 150 ms                                                      | 147 ms: 1.02x faster                                         |
| sqlglot_transpile        | 1.04 ms                                                     | 1.01 ms: 1.02x faster                                        |
| chaos                    | 42.8 ms                                                     | 41.9 ms: 1.02x faster                                        |
| scimark_sor              | 79.6 ms                                                     | 78.2 ms: 1.02x faster                                        |
| pickle_list              | 2.86 us                                                     | 2.81 us: 1.02x faster                                        |
| docutils                 | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                       |
| xml_etree_process        | 38.4 ms                                                     | 37.8 ms: 1.02x faster                                        |
| deepcopy                 | 240 us                                                      | 237 us: 1.02x faster                                         |
| generators               | 22.7 ms                                                     | 22.4 ms: 1.01x faster                                        |
| raytrace                 | 191 ms                                                      | 189 ms: 1.01x faster                                         |
| create_gc_cycles         | 727 us                                                      | 717 us: 1.01x faster                                         |
| meteor_contest           | 73.1 ms                                                     | 72.2 ms: 1.01x faster                                        |
| async_generators         | 235 ms                                                      | 233 ms: 1.01x faster                                         |
| pyflate                  | 297 ms                                                      | 294 ms: 1.01x faster                                         |
| regex_compile            | 88.3 ms                                                     | 87.5 ms: 1.01x faster                                        |
| go                       | 88.5 ms                                                     | 87.7 ms: 1.01x faster                                        |
| tomli_loads              | 1.37 sec                                                    | 1.36 sec: 1.01x faster                                       |
| gc_traversal             | 1.48 ms                                                     | 1.47 ms: 1.01x faster                                        |
| mdp                      | 1.44 sec                                                    | 1.43 sec: 1.01x faster                                       |
| nqueens                  | 61.2 ms                                                     | 60.8 ms: 1.01x faster                                        |
| sqlite_synth             | 1.76 us                                                     | 1.74 us: 1.01x faster                                        |
| telco                    | 4.09 ms                                                     | 4.07 ms: 1.01x faster                                        |
| sqlglot_normalize        | 185 ms                                                      | 184 ms: 1.01x faster                                         |
| pickle_pure_python       | 196 us                                                      | 195 us: 1.00x faster                                         |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.49 ms: 1.00x slower                                        |
| pprint_safe_repr         | 512 ms                                                      | 514 ms: 1.00x slower                                         |
| fannkuch                 | 237 ms                                                      | 238 ms: 1.00x slower                                         |
| xml_etree_generate       | 55.6 ms                                                     | 55.8 ms: 1.00x slower                                        |
| spectral_norm            | 63.2 ms                                                     | 63.5 ms: 1.01x slower                                        |
| bench_mp_pool            | 66.4 ms                                                     | 66.8 ms: 1.01x slower                                        |
| logging_simple           | 6.21 us                                                     | 6.25 us: 1.01x slower                                        |
| hexiom                   | 4.03 ms                                                     | 4.06 ms: 1.01x slower                                        |
| scimark_fft              | 180 ms                                                      | 181 ms: 1.01x slower                                         |
| pprint_pformat           | 1.04 sec                                                    | 1.05 sec: 1.01x slower                                       |
| tornado_http             | 87.7 ms                                                     | 88.4 ms: 1.01x slower                                        |
| deltablue                | 2.14 ms                                                     | 2.15 ms: 1.01x slower                                        |
| mypy2                    | 207 ms                                                      | 209 ms: 1.01x slower                                         |
| scimark_lu               | 58.1 ms                                                     | 58.7 ms: 1.01x slower                                        |
| unpickle_pure_python     | 133 us                                                      | 135 us: 1.01x slower                                         |
| pathlib                  | 77.1 ms                                                     | 78.2 ms: 1.01x slower                                        |
| xml_etree_iterparse      | 62.5 ms                                                     | 63.5 ms: 1.02x slower                                        |
| xml_etree_parse          | 89.2 ms                                                     | 91.0 ms: 1.02x slower                                        |
| json_loads               | 13.4 us                                                     | 13.7 us: 1.02x slower                                        |
| json_dumps               | 5.60 ms                                                     | 5.72 ms: 1.02x slower                                        |
| comprehensions           | 14.1 us                                                     | 14.5 us: 1.02x slower                                        |
| pycparser                | 673 ms                                                      | 691 ms: 1.03x slower                                         |
| unpack_sequence          | 37.5 ns                                                     | 38.5 ns: 1.03x slower                                        |
| typing_runtime_protocols | 95.2 us                                                     | 97.9 us: 1.03x slower                                        |
| unpickle                 | 8.16 us                                                     | 8.40 us: 1.03x slower                                        |
| json                     | 2.86 ms                                                     | 2.95 ms: 1.03x slower                                        |
| python_startup_no_site   | 16.1 ms                                                     | 16.7 ms: 1.04x slower                                        |
| unpickle_list            | 2.78 us                                                     | 2.90 us: 1.04x slower                                        |
| dask                     | 259 ms                                                      | 361 ms: 1.39x slower                                         |
| Geometric mean           | (ref)                                                       | 1.00x faster                                                 |

Benchmark hidden because not significant (16): asyncio_tcp_ssl, bench_thread_pool, aiohttp, mako, python_startup, async_tree_cpu_io_mixed, async_tree_memoization, deepcopy_reduce, 2to3, sqlglot_optimize, async_tree_io, logging_format, coroutines, logging_silent, asyncio_tcp, pickle


# HPT report

- Reliability score: 98.29% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
