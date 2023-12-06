
# Results vs. base

- fork: brandtbucher
- ref: justin_no_pic
- machine: windows-amd64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 1.64 sec                                                                   | 1.67 sec: 1.02x slower                                                    |
| tornado_http   | 90.5 ms                                                                    | 89.3 ms: 1.01x faster                                                     |
| Geometric mean | (ref)                                                                      | 1.00x slower                                                              |

Benchmarks with tag 'math':
===========================

Benchmark hidden because not significant (3): float, nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_effbot   | 1.62 ms                                                                    | 1.64 ms: 1.01x slower                                                     |
| regex_compile  | 93.2 ms                                                                    | 94.7 ms: 1.02x slower                                                     |
| regex_v8       | 14.9 ms                                                                    | 15.2 ms: 1.02x slower                                                     |
| regex_dna      | 121 ms                                                                     | 123 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                                      | 1.02x slower                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| tomli_loads          | 1.54 sec                                                                   | 1.49 sec: 1.03x faster                                                    |
| json_loads           | 13.8 us                                                                    | 13.5 us: 1.02x faster                                                     |
| json_dumps           | 5.76 ms                                                                    | 5.82 ms: 1.01x slower                                                     |
| unpickle             | 8.34 us                                                                    | 8.46 us: 1.01x slower                                                     |
| xml_etree_iterparse  | 64.0 ms                                                                    | 65.3 ms: 1.02x slower                                                     |
| pickle_list          | 2.87 us                                                                    | 2.93 us: 1.02x slower                                                     |
| xml_etree_generate   | 56.9 ms                                                                    | 58.2 ms: 1.02x slower                                                     |
| xml_etree_process    | 38.9 ms                                                                    | 39.9 ms: 1.03x slower                                                     |
| pickle_dict          | 18.4 us                                                                    | 18.9 us: 1.03x slower                                                     |
| pickle               | 7.18 us                                                                    | 7.38 us: 1.03x slower                                                     |
| pickle_pure_python   | 197 us                                                                     | 203 us: 1.03x slower                                                      |
| unpickle_pure_python | 140 us                                                                     | 152 us: 1.08x slower                                                      |
| Geometric mean       | (ref)                                                                      | 1.02x slower                                                              |

Benchmark hidden because not significant (2): xml_etree_parse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 18.7 ms                                                                    | 19.1 ms: 1.02x slower                                                     |
| python_startup_no_site | 15.7 ms                                                                    | 16.1 ms: 1.03x slower                                                     |
| Geometric mean         | (ref)                                                                      | 1.02x slower                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 7.46 ms                                                                    | 6.74 ms: 1.11x faster                                                     |

All benchmarks:
===============

| Benchmark                | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako                     | 7.46 ms                                                                    | 6.74 ms: 1.11x faster                                                     |
| logging_format           | 7.24 us                                                                    | 6.80 us: 1.06x faster                                                     |
| logging_simple           | 6.67 us                                                                    | 6.37 us: 1.05x faster                                                     |
| pycparser                | 758 ms                                                                     | 726 ms: 1.04x faster                                                      |
| tomli_loads              | 1.54 sec                                                                   | 1.49 sec: 1.03x faster                                                    |
| json                     | 3.00 ms                                                                    | 2.92 ms: 1.03x faster                                                     |
| json_loads               | 13.8 us                                                                    | 13.5 us: 1.02x faster                                                     |
| async_tree_io            | 745 ms                                                                     | 731 ms: 1.02x faster                                                      |
| telco                    | 4.85 ms                                                                    | 4.76 ms: 1.02x faster                                                     |
| tornado_http             | 90.5 ms                                                                    | 89.3 ms: 1.01x faster                                                     |
| generators               | 24.3 ms                                                                    | 24.1 ms: 1.01x faster                                                     |
| fannkuch                 | 255 ms                                                                     | 255 ms: 1.00x faster                                                      |
| raytrace                 | 182 ms                                                                     | 183 ms: 1.00x slower                                                      |
| sqlite_synth             | 1.76 us                                                                    | 1.77 us: 1.00x slower                                                     |
| mypy2                    | 221 ms                                                                     | 222 ms: 1.01x slower                                                      |
| dulwich_log              | 45.4 ms                                                                    | 45.7 ms: 1.01x slower                                                     |
| typing_runtime_protocols | 98.2 us                                                                    | 98.9 us: 1.01x slower                                                     |
| gc_traversal             | 1.49 ms                                                                    | 1.51 ms: 1.01x slower                                                     |
| json_dumps               | 5.76 ms                                                                    | 5.82 ms: 1.01x slower                                                     |
| regex_effbot             | 1.62 ms                                                                    | 1.64 ms: 1.01x slower                                                     |
| deepcopy_reduce          | 2.22 us                                                                    | 2.25 us: 1.01x slower                                                     |
| unpickle                 | 8.34 us                                                                    | 8.46 us: 1.01x slower                                                     |
| dask                     | 385 ms                                                                     | 391 ms: 1.02x slower                                                      |
| regex_compile            | 93.2 ms                                                                    | 94.7 ms: 1.02x slower                                                     |
| docutils                 | 1.64 sec                                                                   | 1.67 sec: 1.02x slower                                                    |
| regex_v8                 | 14.9 ms                                                                    | 15.2 ms: 1.02x slower                                                     |
| python_startup           | 18.7 ms                                                                    | 19.1 ms: 1.02x slower                                                     |
| pyflate                  | 310 ms                                                                     | 316 ms: 1.02x slower                                                      |
| xml_etree_iterparse      | 64.0 ms                                                                    | 65.3 ms: 1.02x slower                                                     |
| pickle_list              | 2.87 us                                                                    | 2.93 us: 1.02x slower                                                     |
| xml_etree_generate       | 56.9 ms                                                                    | 58.2 ms: 1.02x slower                                                     |
| regex_dna                | 121 ms                                                                     | 123 ms: 1.02x slower                                                      |
| xml_etree_process        | 38.9 ms                                                                    | 39.9 ms: 1.03x slower                                                     |
| python_startup_no_site   | 15.7 ms                                                                    | 16.1 ms: 1.03x slower                                                     |
| pickle_dict              | 18.4 us                                                                    | 18.9 us: 1.03x slower                                                     |
| sqlglot_optimize         | 35.7 ms                                                                    | 36.7 ms: 1.03x slower                                                     |
| pickle                   | 7.18 us                                                                    | 7.38 us: 1.03x slower                                                     |
| deepcopy                 | 247 us                                                                     | 254 us: 1.03x slower                                                      |
| deltablue                | 2.24 ms                                                                    | 2.31 ms: 1.03x slower                                                     |
| pickle_pure_python       | 197 us                                                                     | 203 us: 1.03x slower                                                      |
| sqlglot_normalize        | 191 ms                                                                     | 197 ms: 1.03x slower                                                      |
| spectral_norm            | 66.4 ms                                                                    | 68.7 ms: 1.03x slower                                                     |
| bench_mp_pool            | 67.2 ms                                                                    | 69.6 ms: 1.04x slower                                                     |
| scimark_monte_carlo      | 44.8 ms                                                                    | 46.5 ms: 1.04x slower                                                     |
| richards                 | 29.2 ms                                                                    | 30.3 ms: 1.04x slower                                                     |
| chaos                    | 43.2 ms                                                                    | 45.1 ms: 1.04x slower                                                     |
| pprint_pformat           | 1.08 sec                                                                   | 1.13 sec: 1.04x slower                                                    |
| scimark_fft              | 187 ms                                                                     | 196 ms: 1.05x slower                                                      |
| pprint_safe_repr         | 529 ms                                                                     | 555 ms: 1.05x slower                                                      |
| async_generators         | 239 ms                                                                     | 252 ms: 1.05x slower                                                      |
| coroutines               | 14.5 ms                                                                    | 15.3 ms: 1.05x slower                                                     |
| comprehensions           | 14.8 us                                                                    | 15.6 us: 1.06x slower                                                     |
| meteor_contest           | 74.4 ms                                                                    | 78.7 ms: 1.06x slower                                                     |
| mdp                      | 1.43 sec                                                                   | 1.51 sec: 1.06x slower                                                    |
| crypto_pyaes             | 45.2 ms                                                                    | 48.0 ms: 1.06x slower                                                     |
| nqueens                  | 61.5 ms                                                                    | 65.3 ms: 1.06x slower                                                     |
| richards_super           | 32.7 ms                                                                    | 34.9 ms: 1.07x slower                                                     |
| scimark_sor              | 84.1 ms                                                                    | 90.4 ms: 1.07x slower                                                     |
| deepcopy_memo            | 24.6 us                                                                    | 26.5 us: 1.08x slower                                                     |
| scimark_lu               | 59.8 ms                                                                    | 64.5 ms: 1.08x slower                                                     |
| go                       | 96.9 ms                                                                    | 105 ms: 1.08x slower                                                      |
| unpickle_pure_python     | 140 us                                                                     | 152 us: 1.08x slower                                                      |
| scimark_sparse_mat_mult  | 2.47 ms                                                                    | 2.70 ms: 1.09x slower                                                     |
| hexiom                   | 4.25 ms                                                                    | 4.80 ms: 1.13x slower                                                     |
| unpack_sequence          | 39.8 ns                                                                    | 45.2 ns: 1.14x slower                                                     |
| Geometric mean           | (ref)                                                                      | 1.02x slower                                                              |

Benchmark hidden because not significant (17): async_tree_none, async_tree_memoization, async_tree_cpu_io_mixed, float, nbody, xml_etree_parse, logging_silent, sqlglot_parse, pidigits, coverage, create_gc_cycles, pathlib, asyncio_tcp, sqlglot_transpile, unpickle_list, bench_thread_pool, asyncio_tcp_ssl


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
