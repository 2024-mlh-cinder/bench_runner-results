
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_opargs
- machine: windows-amd64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.70 sec: 1.04x slower                                                    |
| tornado_http   | 87.7 ms                                                     | 91.7 ms: 1.05x slower                                                     |
| Geometric mean | (ref)                                                       | 1.04x slower                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.01x slower                                                      |
| float          | 55.1 ms                                                     | 56.9 ms: 1.03x slower                                                     |
| nbody          | 72.6 ms                                                     | 76.3 ms: 1.05x slower                                                     |
| Geometric mean | (ref)                                                       | 1.03x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 118 ms: 1.05x faster                                                      |
| regex_effbot   | 1.62 ms                                                     | 1.56 ms: 1.04x faster                                                     |
| regex_v8       | 13.9 ms                                                     | 15.1 ms: 1.09x slower                                                     |
| regex_compile  | 88.3 ms                                                     | 96.1 ms: 1.09x slower                                                     |
| Geometric mean | (ref)                                                       | 1.02x slower                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.1 us: 1.06x faster                                                     |
| unpickle_list        | 2.78 us                                                     | 2.76 us: 1.01x faster                                                     |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                                     |
| pickle_list          | 2.86 us                                                     | 2.91 us: 1.02x slower                                                     |
| pickle_pure_python   | 196 us                                                      | 199 us: 1.02x slower                                                      |
| xml_etree_parse      | 89.2 ms                                                     | 91.6 ms: 1.03x slower                                                     |
| xml_etree_generate   | 55.6 ms                                                     | 57.6 ms: 1.04x slower                                                     |
| xml_etree_process    | 38.4 ms                                                     | 40.0 ms: 1.04x slower                                                     |
| json_dumps           | 5.60 ms                                                     | 5.84 ms: 1.04x slower                                                     |
| unpickle             | 8.16 us                                                     | 8.53 us: 1.05x slower                                                     |
| xml_etree_iterparse  | 62.5 ms                                                     | 65.6 ms: 1.05x slower                                                     |
| tomli_loads          | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                                    |
| unpickle_pure_python | 133 us                                                      | 146 us: 1.10x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.03x slower                                                              |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                     |
| python_startup_no_site | 16.1 ms                                                     | 16.7 ms: 1.04x slower                                                     |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.81 ms: 1.02x faster                                                     |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 46.4 ms: 1.11x faster                                                     |
| pickle_dict              | 19.3 us                                                     | 18.1 us: 1.06x faster                                                     |
| regex_dna                | 124 ms                                                      | 118 ms: 1.05x faster                                                      |
| regex_effbot             | 1.62 ms                                                     | 1.56 ms: 1.04x faster                                                     |
| async_tree_none          | 294 ms                                                      | 283 ms: 1.04x faster                                                      |
| mako                     | 6.93 ms                                                     | 6.81 ms: 1.02x faster                                                     |
| unpickle_list            | 2.78 us                                                     | 2.76 us: 1.01x faster                                                     |
| pidigits                 | 150 ms                                                      | 151 ms: 1.01x slower                                                      |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                                     |
| gc_traversal             | 1.48 ms                                                     | 1.51 ms: 1.01x slower                                                     |
| pickle_list              | 2.86 us                                                     | 2.91 us: 1.02x slower                                                     |
| python_startup           | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                     |
| pickle_pure_python       | 196 us                                                      | 199 us: 1.02x slower                                                      |
| json                     | 2.86 ms                                                     | 2.92 ms: 1.02x slower                                                     |
| bench_thread_pool        | 844 us                                                      | 860 us: 1.02x slower                                                      |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 490 ms: 1.02x slower                                                      |
| crypto_pyaes             | 47.4 ms                                                     | 48.5 ms: 1.02x slower                                                     |
| scimark_monte_carlo      | 43.7 ms                                                     | 44.7 ms: 1.02x slower                                                     |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.55 ms: 1.03x slower                                                     |
| xml_etree_parse          | 89.2 ms                                                     | 91.6 ms: 1.03x slower                                                     |
| pathlib                  | 77.1 ms                                                     | 79.3 ms: 1.03x slower                                                     |
| float                    | 55.1 ms                                                     | 56.9 ms: 1.03x slower                                                     |
| xml_etree_generate       | 55.6 ms                                                     | 57.6 ms: 1.04x slower                                                     |
| python_startup_no_site   | 16.1 ms                                                     | 16.7 ms: 1.04x slower                                                     |
| async_tree_io            | 720 ms                                                      | 749 ms: 1.04x slower                                                      |
| docutils                 | 1.63 sec                                                    | 1.70 sec: 1.04x slower                                                    |
| xml_etree_process        | 38.4 ms                                                     | 40.0 ms: 1.04x slower                                                     |
| json_dumps               | 5.60 ms                                                     | 5.84 ms: 1.04x slower                                                     |
| deepcopy_reduce          | 2.13 us                                                     | 2.23 us: 1.04x slower                                                     |
| unpickle                 | 8.16 us                                                     | 8.53 us: 1.05x slower                                                     |
| tornado_http             | 87.7 ms                                                     | 91.7 ms: 1.05x slower                                                     |
| xml_etree_iterparse      | 62.5 ms                                                     | 65.6 ms: 1.05x slower                                                     |
| nbody                    | 72.6 ms                                                     | 76.3 ms: 1.05x slower                                                     |
| typing_runtime_protocols | 95.2 us                                                     | 99.9 us: 1.05x slower                                                     |
| deepcopy                 | 240 us                                                      | 253 us: 1.05x slower                                                      |
| deepcopy_memo            | 23.8 us                                                     | 25.1 us: 1.05x slower                                                     |
| pprint_safe_repr         | 512 ms                                                      | 542 ms: 1.06x slower                                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.12 sec: 1.07x slower                                                    |
| bench_mp_pool            | 66.4 ms                                                     | 71.1 ms: 1.07x slower                                                     |
| pyflate                  | 297 ms                                                      | 318 ms: 1.07x slower                                                      |
| fannkuch                 | 237 ms                                                      | 254 ms: 1.07x slower                                                      |
| async_generators         | 235 ms                                                      | 253 ms: 1.07x slower                                                      |
| mdp                      | 1.44 sec                                                    | 1.55 sec: 1.07x slower                                                    |
| chaos                    | 42.8 ms                                                     | 46.1 ms: 1.08x slower                                                     |
| scimark_fft              | 180 ms                                                      | 194 ms: 1.08x slower                                                      |
| logging_silent           | 60.6 ns                                                     | 65.4 ns: 1.08x slower                                                     |
| async_tree_memoization   | 336 ms                                                      | 363 ms: 1.08x slower                                                      |
| scimark_sor              | 79.6 ms                                                     | 86.1 ms: 1.08x slower                                                     |
| coroutines               | 14.0 ms                                                     | 15.1 ms: 1.08x slower                                                     |
| tomli_loads              | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                                    |
| regex_v8                 | 13.9 ms                                                     | 15.1 ms: 1.09x slower                                                     |
| spectral_norm            | 63.2 ms                                                     | 68.7 ms: 1.09x slower                                                     |
| regex_compile            | 88.3 ms                                                     | 96.1 ms: 1.09x slower                                                     |
| sqlglot_transpile        | 1.04 ms                                                     | 1.13 ms: 1.09x slower                                                     |
| meteor_contest           | 73.1 ms                                                     | 79.7 ms: 1.09x slower                                                     |
| sqlglot_parse            | 820 us                                                      | 896 us: 1.09x slower                                                      |
| deltablue                | 2.14 ms                                                     | 2.34 ms: 1.09x slower                                                     |
| nqueens                  | 61.2 ms                                                     | 67.0 ms: 1.09x slower                                                     |
| scimark_lu               | 58.1 ms                                                     | 63.6 ms: 1.09x slower                                                     |
| unpickle_pure_python     | 133 us                                                      | 146 us: 1.10x slower                                                      |
| logging_format           | 6.67 us                                                     | 7.35 us: 1.10x slower                                                     |
| generators               | 22.7 ms                                                     | 25.1 ms: 1.10x slower                                                     |
| logging_simple           | 6.21 us                                                     | 6.87 us: 1.10x slower                                                     |
| sqlglot_normalize        | 185 ms                                                      | 205 ms: 1.11x slower                                                      |
| dulwich_log              | 42.4 ms                                                     | 47.0 ms: 1.11x slower                                                     |
| sqlglot_optimize         | 34.4 ms                                                     | 38.1 ms: 1.11x slower                                                     |
| comprehensions           | 14.1 us                                                     | 15.7 us: 1.11x slower                                                     |
| mypy2                    | 207 ms                                                      | 230 ms: 1.11x slower                                                      |
| pycparser                | 673 ms                                                      | 752 ms: 1.12x slower                                                      |
| telco                    | 4.09 ms                                                     | 4.63 ms: 1.13x slower                                                     |
| richards                 | 26.9 ms                                                     | 30.5 ms: 1.13x slower                                                     |
| richards_super           | 30.5 ms                                                     | 35.1 ms: 1.15x slower                                                     |
| go                       | 88.5 ms                                                     | 104 ms: 1.18x slower                                                      |
| hexiom                   | 4.03 ms                                                     | 4.77 ms: 1.18x slower                                                     |
| unpack_sequence          | 37.5 ns                                                     | 48.8 ns: 1.30x slower                                                     |
| dask                     | 259 ms                                                      | 396 ms: 1.53x slower                                                      |
| Geometric mean           | (ref)                                                       | 1.06x slower                                                              |

Benchmark hidden because not significant (6): create_gc_cycles, pickle, raytrace, asyncio_tcp_ssl, sqlite_synth, asyncio_tcp
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.04x
