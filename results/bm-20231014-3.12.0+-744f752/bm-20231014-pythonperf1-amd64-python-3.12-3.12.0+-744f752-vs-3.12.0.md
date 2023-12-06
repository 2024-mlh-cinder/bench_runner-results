
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 744f752
- commit date: 2023-10-14
- overall geometric mean: 1.01x slower
- HPT reliability: 88.66%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| tornado_http   | 87.7 ms                                                     | 91.5 ms: 1.04x slower                                     |
| Geometric mean | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (2): 2to3, docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| float          | 55.1 ms                                                     | 53.4 ms: 1.03x faster                                     |
| nbody          | 72.6 ms                                                     | 70.6 ms: 1.03x faster                                     |
| Geometric mean | (ref)                                                       | 1.02x faster                                              |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 122 ms: 1.02x faster                                      |
| regex_v8       | 13.9 ms                                                     | 13.7 ms: 1.02x faster                                     |
| regex_compile  | 88.3 ms                                                     | 87.6 ms: 1.01x faster                                     |
| regex_effbot   | 1.62 ms                                                     | 1.64 ms: 1.01x slower                                     |
| Geometric mean | (ref)                                                       | 1.01x faster                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.3 us: 1.05x faster                                     |
| unpickle_list        | 2.78 us                                                     | 2.74 us: 1.02x faster                                     |
| xml_etree_process    | 38.4 ms                                                     | 38.1 ms: 1.01x faster                                     |
| pickle               | 7.13 us                                                     | 7.10 us: 1.01x faster                                     |
| pickle_list          | 2.86 us                                                     | 2.88 us: 1.01x slower                                     |
| pickle_pure_python   | 196 us                                                      | 198 us: 1.01x slower                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 63.3 ms: 1.01x slower                                     |
| unpickle             | 8.16 us                                                     | 8.26 us: 1.01x slower                                     |
| json_dumps           | 5.60 ms                                                     | 5.68 ms: 1.01x slower                                     |
| json_loads           | 13.4 us                                                     | 13.7 us: 1.02x slower                                     |
| unpickle_pure_python | 133 us                                                      | 138 us: 1.03x slower                                      |
| xml_etree_parse      | 89.2 ms                                                     | 92.3 ms: 1.04x slower                                     |
| tomli_loads          | 1.37 sec                                                    | 1.43 sec: 1.04x slower                                    |
| Geometric mean       | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 18.8 ms: 1.03x faster                                     |
| python_startup_no_site | 16.1 ms                                                     | 15.9 ms: 1.02x faster                                     |
| Geometric mean         | (ref)                                                       | 1.02x faster                                              |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| bench_mp_pool            | 66.4 ms                                                     | 62.8 ms: 1.06x faster                                     |
| pickle_dict              | 19.3 us                                                     | 18.3 us: 1.05x faster                                     |
| float                    | 55.1 ms                                                     | 53.4 ms: 1.03x faster                                     |
| python_startup           | 19.5 ms                                                     | 18.8 ms: 1.03x faster                                     |
| create_gc_cycles         | 727 us                                                      | 705 us: 1.03x faster                                      |
| nbody                    | 72.6 ms                                                     | 70.6 ms: 1.03x faster                                     |
| aiohttp                  | 865 us                                                      | 846 us: 1.02x faster                                      |
| coverage                 | 51.5 ms                                                     | 50.5 ms: 1.02x faster                                     |
| bench_thread_pool        | 844 us                                                      | 828 us: 1.02x faster                                      |
| dask                     | 259 ms                                                      | 254 ms: 1.02x faster                                      |
| python_startup_no_site   | 16.1 ms                                                     | 15.9 ms: 1.02x faster                                     |
| regex_dna                | 124 ms                                                      | 122 ms: 1.02x faster                                      |
| regex_v8                 | 13.9 ms                                                     | 13.7 ms: 1.02x faster                                     |
| async_tree_io            | 720 ms                                                      | 709 ms: 1.02x faster                                      |
| unpickle_list            | 2.78 us                                                     | 2.74 us: 1.02x faster                                     |
| gc_traversal             | 1.48 ms                                                     | 1.47 ms: 1.01x faster                                     |
| telco                    | 4.09 ms                                                     | 4.05 ms: 1.01x faster                                     |
| regex_compile            | 88.3 ms                                                     | 87.6 ms: 1.01x faster                                     |
| xml_etree_process        | 38.4 ms                                                     | 38.1 ms: 1.01x faster                                     |
| sqlite_synth             | 1.76 us                                                     | 1.74 us: 1.01x faster                                     |
| deepcopy_reduce          | 2.13 us                                                     | 2.12 us: 1.01x faster                                     |
| sqlglot_optimize         | 34.4 ms                                                     | 34.2 ms: 1.01x faster                                     |
| pyflate                  | 297 ms                                                      | 295 ms: 1.01x faster                                      |
| pickle                   | 7.13 us                                                     | 7.10 us: 1.01x faster                                     |
| crypto_pyaes             | 47.4 ms                                                     | 47.2 ms: 1.00x faster                                     |
| deltablue                | 2.14 ms                                                     | 2.15 ms: 1.00x slower                                     |
| pprint_pformat           | 1.04 sec                                                    | 1.05 sec: 1.00x slower                                    |
| async_generators         | 235 ms                                                      | 236 ms: 1.00x slower                                      |
| logging_simple           | 6.21 us                                                     | 6.25 us: 1.01x slower                                     |
| pathlib                  | 77.1 ms                                                     | 77.7 ms: 1.01x slower                                     |
| pickle_list              | 2.86 us                                                     | 2.88 us: 1.01x slower                                     |
| regex_effbot             | 1.62 ms                                                     | 1.64 ms: 1.01x slower                                     |
| pprint_safe_repr         | 512 ms                                                      | 516 ms: 1.01x slower                                      |
| deepcopy                 | 240 us                                                      | 242 us: 1.01x slower                                      |
| mypy2                    | 207 ms                                                      | 209 ms: 1.01x slower                                      |
| pickle_pure_python       | 196 us                                                      | 198 us: 1.01x slower                                      |
| generators               | 22.7 ms                                                     | 23.0 ms: 1.01x slower                                     |
| xml_etree_iterparse      | 62.5 ms                                                     | 63.3 ms: 1.01x slower                                     |
| logging_format           | 6.67 us                                                     | 6.76 us: 1.01x slower                                     |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.51 ms: 1.01x slower                                     |
| unpickle                 | 8.16 us                                                     | 8.26 us: 1.01x slower                                     |
| richards                 | 26.9 ms                                                     | 27.3 ms: 1.01x slower                                     |
| scimark_fft              | 180 ms                                                      | 183 ms: 1.01x slower                                      |
| json_dumps               | 5.60 ms                                                     | 5.68 ms: 1.01x slower                                     |
| chaos                    | 42.8 ms                                                     | 43.4 ms: 1.01x slower                                     |
| richards_super           | 30.5 ms                                                     | 31.0 ms: 1.02x slower                                     |
| json_loads               | 13.4 us                                                     | 13.7 us: 1.02x slower                                     |
| scimark_monte_carlo      | 43.7 ms                                                     | 44.5 ms: 1.02x slower                                     |
| json                     | 2.86 ms                                                     | 2.92 ms: 1.02x slower                                     |
| raytrace                 | 191 ms                                                      | 195 ms: 1.02x slower                                      |
| nqueens                  | 61.2 ms                                                     | 62.5 ms: 1.02x slower                                     |
| spectral_norm            | 63.2 ms                                                     | 64.6 ms: 1.02x slower                                     |
| scimark_lu               | 58.1 ms                                                     | 59.4 ms: 1.02x slower                                     |
| hexiom                   | 4.03 ms                                                     | 4.14 ms: 1.03x slower                                     |
| comprehensions           | 14.1 us                                                     | 14.5 us: 1.03x slower                                     |
| deepcopy_memo            | 23.8 us                                                     | 24.5 us: 1.03x slower                                     |
| unpickle_pure_python     | 133 us                                                      | 138 us: 1.03x slower                                      |
| scimark_sor              | 79.6 ms                                                     | 82.4 ms: 1.03x slower                                     |
| xml_etree_parse          | 89.2 ms                                                     | 92.3 ms: 1.04x slower                                     |
| coroutines               | 14.0 ms                                                     | 14.5 ms: 1.04x slower                                     |
| pycparser                | 673 ms                                                      | 701 ms: 1.04x slower                                      |
| tornado_http             | 87.7 ms                                                     | 91.5 ms: 1.04x slower                                     |
| tomli_loads              | 1.37 sec                                                    | 1.43 sec: 1.04x slower                                    |
| mdp                      | 1.44 sec                                                    | 1.52 sec: 1.05x slower                                    |
| go                       | 88.5 ms                                                     | 94.1 ms: 1.06x slower                                     |
| fannkuch                 | 237 ms                                                      | 254 ms: 1.07x slower                                      |
| typing_runtime_protocols | 95.2 us                                                     | 103 us: 1.08x slower                                      |
| unpack_sequence          | 37.5 ns                                                     | 47.7 ns: 1.27x slower                                     |
| Geometric mean           | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (16): asyncio_tcp_ssl, async_tree_none, 2to3, sqlglot_normalize, asyncio_tcp, sqlglot_parse, meteor_contest, pidigits, sqlglot_transpile, dulwich_log, xml_etree_generate, logging_silent, async_tree_cpu_io_mixed, docutils, async_tree_memoization, mako


# HPT report

- Reliability score: 88.66% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
