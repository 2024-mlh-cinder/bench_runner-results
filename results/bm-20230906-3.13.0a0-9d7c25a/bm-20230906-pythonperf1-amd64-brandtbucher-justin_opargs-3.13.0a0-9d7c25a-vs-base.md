
# Results vs. base

- fork: brandtbucher
- ref: justin_opargs
- machine: windows-amd64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 1.65 sec                                                                   | 1.70 sec: 1.03x slower                                                    |
| tornado_http   | 89.7 ms                                                                    | 91.7 ms: 1.02x slower                                                     |
| Geometric mean | (ref)                                                                      | 1.03x slower                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| nbody          | 76.8 ms                                                                    | 76.3 ms: 1.01x faster                                                     |
| pidigits       | 150 ms                                                                     | 151 ms: 1.00x slower                                                      |
| float          | 55.8 ms                                                                    | 56.9 ms: 1.02x slower                                                     |
| Geometric mean | (ref)                                                                      | 1.00x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                                    | 1.56 ms: 1.01x faster                                                     |
| regex_dna      | 118 ms                                                                     | 118 ms: 1.00x faster                                                      |
| regex_v8       | 14.8 ms                                                                    | 15.1 ms: 1.02x slower                                                     |
| regex_compile  | 92.4 ms                                                                    | 96.1 ms: 1.04x slower                                                     |
| Geometric mean | (ref)                                                                      | 1.01x slower                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| tomli_loads          | 1.54 sec                                                                   | 1.49 sec: 1.04x faster                                                    |
| pickle               | 7.20 us                                                                    | 7.12 us: 1.01x faster                                                     |
| pickle_dict          | 18.2 us                                                                    | 18.1 us: 1.01x faster                                                     |
| json_dumps           | 5.79 ms                                                                    | 5.84 ms: 1.01x slower                                                     |
| json_loads           | 13.4 us                                                                    | 13.6 us: 1.01x slower                                                     |
| pickle_pure_python   | 197 us                                                                     | 199 us: 1.01x slower                                                      |
| xml_etree_process    | 39.4 ms                                                                    | 40.0 ms: 1.02x slower                                                     |
| xml_etree_iterparse  | 64.4 ms                                                                    | 65.6 ms: 1.02x slower                                                     |
| xml_etree_generate   | 56.3 ms                                                                    | 57.6 ms: 1.02x slower                                                     |
| unpickle_list        | 2.69 us                                                                    | 2.76 us: 1.02x slower                                                     |
| unpickle_pure_python | 141 us                                                                     | 146 us: 1.04x slower                                                      |
| Geometric mean       | (ref)                                                                      | 1.01x slower                                                              |

Benchmark hidden because not significant (3): xml_etree_parse, unpickle, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 16.4 ms                                                                    | 16.7 ms: 1.02x slower                                                     |
| Geometric mean         | (ref)                                                                      | 1.01x slower                                                              |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 7.60 ms                                                                    | 6.81 ms: 1.12x faster                                                     |

All benchmarks:
===============

| Benchmark                | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako                     | 7.60 ms                                                                    | 6.81 ms: 1.12x faster                                                     |
| tomli_loads              | 1.54 sec                                                                   | 1.49 sec: 1.04x faster                                                    |
| regex_effbot             | 1.58 ms                                                                    | 1.56 ms: 1.01x faster                                                     |
| pickle                   | 7.20 us                                                                    | 7.12 us: 1.01x faster                                                     |
| json                     | 2.94 ms                                                                    | 2.92 ms: 1.01x faster                                                     |
| nbody                    | 76.8 ms                                                                    | 76.3 ms: 1.01x faster                                                     |
| pickle_dict              | 18.2 us                                                                    | 18.1 us: 1.01x faster                                                     |
| regex_dna                | 118 ms                                                                     | 118 ms: 1.00x faster                                                      |
| pidigits                 | 150 ms                                                                     | 151 ms: 1.00x slower                                                      |
| telco                    | 4.61 ms                                                                    | 4.63 ms: 1.01x slower                                                     |
| pathlib                  | 78.8 ms                                                                    | 79.3 ms: 1.01x slower                                                     |
| scimark_sor              | 85.5 ms                                                                    | 86.1 ms: 1.01x slower                                                     |
| json_dumps               | 5.79 ms                                                                    | 5.84 ms: 1.01x slower                                                     |
| fannkuch                 | 252 ms                                                                     | 254 ms: 1.01x slower                                                      |
| pprint_safe_repr         | 537 ms                                                                     | 542 ms: 1.01x slower                                                      |
| json_loads               | 13.4 us                                                                    | 13.6 us: 1.01x slower                                                     |
| async_tree_cpu_io_mixed  | 484 ms                                                                     | 490 ms: 1.01x slower                                                      |
| deepcopy_memo            | 24.8 us                                                                    | 25.1 us: 1.01x slower                                                     |
| logging_simple           | 6.78 us                                                                    | 6.87 us: 1.01x slower                                                     |
| logging_format           | 7.26 us                                                                    | 7.35 us: 1.01x slower                                                     |
| scimark_monte_carlo      | 44.2 ms                                                                    | 44.7 ms: 1.01x slower                                                     |
| deepcopy_reduce          | 2.20 us                                                                    | 2.23 us: 1.01x slower                                                     |
| pickle_pure_python       | 197 us                                                                     | 199 us: 1.01x slower                                                      |
| deltablue                | 2.30 ms                                                                    | 2.34 ms: 1.01x slower                                                     |
| xml_etree_process        | 39.4 ms                                                                    | 40.0 ms: 1.02x slower                                                     |
| pprint_pformat           | 1.10 sec                                                                   | 1.12 sec: 1.02x slower                                                    |
| dask                     | 389 ms                                                                     | 396 ms: 1.02x slower                                                      |
| xml_etree_iterparse      | 64.4 ms                                                                    | 65.6 ms: 1.02x slower                                                     |
| python_startup_no_site   | 16.4 ms                                                                    | 16.7 ms: 1.02x slower                                                     |
| float                    | 55.8 ms                                                                    | 56.9 ms: 1.02x slower                                                     |
| bench_thread_pool        | 842 us                                                                     | 860 us: 1.02x slower                                                      |
| regex_v8                 | 14.8 ms                                                                    | 15.1 ms: 1.02x slower                                                     |
| tornado_http             | 89.7 ms                                                                    | 91.7 ms: 1.02x slower                                                     |
| xml_etree_generate       | 56.3 ms                                                                    | 57.6 ms: 1.02x slower                                                     |
| logging_silent           | 63.9 ns                                                                    | 65.4 ns: 1.02x slower                                                     |
| unpickle_list            | 2.69 us                                                                    | 2.76 us: 1.02x slower                                                     |
| pyflate                  | 310 ms                                                                     | 318 ms: 1.03x slower                                                      |
| docutils                 | 1.65 sec                                                                   | 1.70 sec: 1.03x slower                                                    |
| sqlglot_parse            | 871 us                                                                     | 896 us: 1.03x slower                                                      |
| richards                 | 29.7 ms                                                                    | 30.5 ms: 1.03x slower                                                     |
| scimark_sparse_mat_mult  | 2.47 ms                                                                    | 2.55 ms: 1.03x slower                                                     |
| sqlglot_transpile        | 1.09 ms                                                                    | 1.13 ms: 1.03x slower                                                     |
| coroutines               | 14.6 ms                                                                    | 15.1 ms: 1.03x slower                                                     |
| dulwich_log              | 45.4 ms                                                                    | 47.0 ms: 1.03x slower                                                     |
| deepcopy                 | 244 us                                                                     | 253 us: 1.04x slower                                                      |
| unpickle_pure_python     | 141 us                                                                     | 146 us: 1.04x slower                                                      |
| raytrace                 | 184 ms                                                                     | 191 ms: 1.04x slower                                                      |
| regex_compile            | 92.4 ms                                                                    | 96.1 ms: 1.04x slower                                                     |
| mypy2                    | 219 ms                                                                     | 230 ms: 1.05x slower                                                      |
| typing_runtime_protocols | 95.3 us                                                                    | 99.9 us: 1.05x slower                                                     |
| scimark_fft              | 185 ms                                                                     | 194 ms: 1.05x slower                                                      |
| spectral_norm            | 65.3 ms                                                                    | 68.7 ms: 1.05x slower                                                     |
| bench_mp_pool            | 67.4 ms                                                                    | 71.1 ms: 1.05x slower                                                     |
| generators               | 23.7 ms                                                                    | 25.1 ms: 1.06x slower                                                     |
| comprehensions           | 14.8 us                                                                    | 15.7 us: 1.06x slower                                                     |
| crypto_pyaes             | 45.9 ms                                                                    | 48.5 ms: 1.06x slower                                                     |
| async_generators         | 239 ms                                                                     | 253 ms: 1.06x slower                                                      |
| richards_super           | 33.1 ms                                                                    | 35.1 ms: 1.06x slower                                                     |
| meteor_contest           | 74.9 ms                                                                    | 79.7 ms: 1.06x slower                                                     |
| sqlglot_optimize         | 35.7 ms                                                                    | 38.1 ms: 1.07x slower                                                     |
| chaos                    | 43.2 ms                                                                    | 46.1 ms: 1.07x slower                                                     |
| sqlglot_normalize        | 192 ms                                                                     | 205 ms: 1.07x slower                                                      |
| nqueens                  | 62.5 ms                                                                    | 67.0 ms: 1.07x slower                                                     |
| scimark_lu               | 59.2 ms                                                                    | 63.6 ms: 1.07x slower                                                     |
| mdp                      | 1.44 sec                                                                   | 1.55 sec: 1.07x slower                                                    |
| go                       | 95.7 ms                                                                    | 104 ms: 1.09x slower                                                      |
| hexiom                   | 4.31 ms                                                                    | 4.77 ms: 1.11x slower                                                     |
| unpack_sequence          | 40.4 ns                                                                    | 48.8 ns: 1.21x slower                                                     |
| Geometric mean           | (ref)                                                                      | 1.03x slower                                                              |

Benchmark hidden because not significant (14): create_gc_cycles, xml_etree_parse, sqlite_synth, async_tree_io, unpickle, pickle_list, coverage, gc_traversal, python_startup, pycparser, async_tree_none, async_tree_memoization, asyncio_tcp, asyncio_tcp_ssl


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
