
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_opargs
- machine: linux-x86_64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                                     |
| Geometric mean | (ref)                                                        | 1.01x slower                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                                       |
| float          | 78.5 ms                                                      | 82.9 ms: 1.06x slower                                                      |
| Geometric mean | (ref)                                                        | 1.02x slower                                                               |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.47 ms                                                      | 3.56 ms: 1.03x slower                                                      |
| regex_dna      | 241 ms                                                       | 248 ms: 1.03x slower                                                       |
| regex_v8       | 25.0 ms                                                      | 25.8 ms: 1.03x slower                                                      |
| regex_compile  | 146 ms                                                       | 156 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.4 us: 1.03x faster                                                      |
| unpickle_list        | 4.77 us                                                      | 4.68 us: 1.02x faster                                                      |
| pickle_pure_python   | 323 us                                                       | 317 us: 1.02x faster                                                       |
| pickle_dict          | 31.7 us                                                      | 31.9 us: 1.00x slower                                                      |
| xml_etree_parse      | 146 ms                                                       | 148 ms: 1.01x slower                                                       |
| pickle_list          | 4.39 us                                                      | 4.51 us: 1.03x slower                                                      |
| xml_etree_process    | 58.3 ms                                                      | 60.2 ms: 1.03x slower                                                      |
| json_loads           | 24.3 us                                                      | 25.1 us: 1.03x slower                                                      |
| json_dumps           | 10.2 ms                                                      | 10.6 ms: 1.03x slower                                                      |
| xml_etree_iterparse  | 103 ms                                                       | 108 ms: 1.04x slower                                                       |
| tomli_loads          | 2.20 sec                                                     | 2.38 sec: 1.08x slower                                                     |
| unpickle_pure_python | 207 us                                                       | 242 us: 1.17x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                               |

Benchmark hidden because not significant (2): pickle, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 12.3 ms: 1.05x slower                                                      |
| python_startup_no_site | 8.70 ms                                                      | 9.26 ms: 1.07x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.06x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.6 ms: 1.07x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.90 ms: 1.09x faster                                                      |
| crypto_pyaes             | 80.9 ms                                                      | 74.2 ms: 1.09x faster                                                      |
| coverage                 | 89.6 ms                                                      | 82.5 ms: 1.09x faster                                                      |
| raytrace                 | 302 ms                                                       | 279 ms: 1.08x faster                                                       |
| create_gc_cycles         | 1.67 ms                                                      | 1.56 ms: 1.07x faster                                                      |
| async_tree_none          | 459 ms                                                       | 441 ms: 1.04x faster                                                       |
| unpickle                 | 14.8 us                                                      | 14.4 us: 1.03x faster                                                      |
| asyncio_tcp              | 381 ms                                                       | 372 ms: 1.02x faster                                                       |
| unpickle_list            | 4.77 us                                                      | 4.68 us: 1.02x faster                                                      |
| scimark_monte_carlo      | 72.4 ms                                                      | 71.1 ms: 1.02x faster                                                      |
| gc_traversal             | 3.54 ms                                                      | 3.48 ms: 1.02x faster                                                      |
| pickle_pure_python       | 323 us                                                       | 317 us: 1.02x faster                                                       |
| pprint_safe_repr         | 823 ms                                                       | 815 ms: 1.01x faster                                                       |
| pprint_pformat           | 1.67 sec                                                     | 1.66 sec: 1.01x faster                                                     |
| pathlib                  | 19.8 ms                                                      | 19.7 ms: 1.01x faster                                                      |
| pidigits                 | 264 ms                                                       | 264 ms: 1.00x slower                                                       |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                     |
| generators               | 36.7 ms                                                      | 36.9 ms: 1.00x slower                                                      |
| pickle_dict              | 31.7 us                                                      | 31.9 us: 1.00x slower                                                      |
| xml_etree_parse          | 146 ms                                                       | 148 ms: 1.01x slower                                                       |
| sqlite_synth             | 2.70 us                                                      | 2.73 us: 1.01x slower                                                      |
| logging_simple           | 6.73 us                                                      | 6.88 us: 1.02x slower                                                      |
| docutils                 | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                                     |
| regex_effbot             | 3.47 ms                                                      | 3.56 ms: 1.03x slower                                                      |
| pickle_list              | 4.39 us                                                      | 4.51 us: 1.03x slower                                                      |
| bench_thread_pool        | 980 us                                                       | 1.01 ms: 1.03x slower                                                      |
| typing_runtime_protocols | 151 us                                                       | 156 us: 1.03x slower                                                       |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                                     |
| regex_dna                | 241 ms                                                       | 248 ms: 1.03x slower                                                       |
| xml_etree_process        | 58.3 ms                                                      | 60.2 ms: 1.03x slower                                                      |
| logging_format           | 7.37 us                                                      | 7.61 us: 1.03x slower                                                      |
| json_loads               | 24.3 us                                                      | 25.1 us: 1.03x slower                                                      |
| regex_v8                 | 25.0 ms                                                      | 25.8 ms: 1.03x slower                                                      |
| json_dumps               | 10.2 ms                                                      | 10.6 ms: 1.03x slower                                                      |
| sqlglot_normalize        | 117 ms                                                       | 122 ms: 1.04x slower                                                       |
| spectral_norm            | 91.6 ms                                                      | 95.2 ms: 1.04x slower                                                      |
| sqlglot_parse            | 1.40 ms                                                      | 1.46 ms: 1.04x slower                                                      |
| sqlglot_transpile        | 1.80 ms                                                      | 1.88 ms: 1.04x slower                                                      |
| mdp                      | 2.53 sec                                                     | 2.64 sec: 1.04x slower                                                     |
| xml_etree_iterparse      | 103 ms                                                       | 108 ms: 1.04x slower                                                       |
| logging_silent           | 95.6 ns                                                      | 100.0 ns: 1.05x slower                                                     |
| python_startup           | 11.7 ms                                                      | 12.3 ms: 1.05x slower                                                      |
| pycparser                | 1.27 sec                                                     | 1.33 sec: 1.05x slower                                                     |
| mypy2                    | 368 ms                                                       | 386 ms: 1.05x slower                                                       |
| deepcopy_memo            | 37.4 us                                                      | 39.4 us: 1.05x slower                                                      |
| deepcopy                 | 376 us                                                       | 396 us: 1.05x slower                                                       |
| unpack_sequence          | 53.3 ns                                                      | 56.2 ns: 1.05x slower                                                      |
| scimark_lu               | 101 ms                                                       | 106 ms: 1.05x slower                                                       |
| float                    | 78.5 ms                                                      | 82.9 ms: 1.06x slower                                                      |
| async_generators         | 385 ms                                                       | 409 ms: 1.06x slower                                                       |
| sqlglot_optimize         | 57.8 ms                                                      | 61.4 ms: 1.06x slower                                                      |
| chaos                    | 62.9 ms                                                      | 66.9 ms: 1.06x slower                                                      |
| dulwich_log              | 65.3 ms                                                      | 69.5 ms: 1.06x slower                                                      |
| python_startup_no_site   | 8.70 ms                                                      | 9.26 ms: 1.07x slower                                                      |
| mako                     | 9.94 ms                                                      | 10.6 ms: 1.07x slower                                                      |
| regex_compile            | 146 ms                                                       | 156 ms: 1.07x slower                                                       |
| tomli_loads              | 2.20 sec                                                     | 2.38 sec: 1.08x slower                                                     |
| meteor_contest           | 128 ms                                                       | 139 ms: 1.09x slower                                                       |
| scimark_fft              | 304 ms                                                       | 334 ms: 1.10x slower                                                       |
| pyflate                  | 447 ms                                                       | 503 ms: 1.12x slower                                                       |
| nqueens                  | 90.1 ms                                                      | 104 ms: 1.15x slower                                                       |
| deltablue                | 3.29 ms                                                      | 3.78 ms: 1.15x slower                                                      |
| comprehensions           | 21.9 us                                                      | 25.2 us: 1.15x slower                                                      |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 5.12 ms: 1.16x slower                                                      |
| telco                    | 6.96 ms                                                      | 8.07 ms: 1.16x slower                                                      |
| richards_super           | 51.7 ms                                                      | 60.6 ms: 1.17x slower                                                      |
| unpickle_pure_python     | 207 us                                                       | 242 us: 1.17x slower                                                       |
| go                       | 150 ms                                                       | 179 ms: 1.19x slower                                                       |
| richards                 | 45.0 ms                                                      | 53.8 ms: 1.19x slower                                                      |
| fannkuch                 | 350 ms                                                       | 421 ms: 1.20x slower                                                       |
| hexiom                   | 5.96 ms                                                      | 7.40 ms: 1.24x slower                                                      |
| scimark_sor              | 110 ms                                                       | 150 ms: 1.36x slower                                                       |
| dask                     | 397 ms                                                       | 596 ms: 1.50x slower                                                       |
| Geometric mean           | (ref)                                                        | 1.05x slower                                                               |

Benchmark hidden because not significant (9): nbody, json, pickle, tornado_http, deepcopy_reduce, async_tree_cpu_io_mixed, xml_etree_generate, async_tree_memoization, coroutines
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
