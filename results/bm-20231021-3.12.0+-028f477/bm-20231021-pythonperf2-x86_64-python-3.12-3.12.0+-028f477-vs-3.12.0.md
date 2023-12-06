
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.00x slower
- HPT reliability: 69.60%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.00x faster                                     |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 83.4 ms: 1.13x faster                                      |
| float          | 78.5 ms                                                      | 79.1 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                        | 1.04x faster                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 24.1 ms: 1.04x faster                                      |
| regex_compile  | 146 ms                                                       | 143 ms: 1.02x faster                                       |
| regex_dna      | 241 ms                                                       | 244 ms: 1.01x slower                                       |
| regex_effbot   | 3.47 ms                                                      | 3.53 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.5 us: 1.02x faster                                      |
| xml_etree_generate   | 86.1 ms                                                      | 85.5 ms: 1.01x faster                                      |
| unpickle_pure_python | 207 us                                                       | 206 us: 1.00x faster                                       |
| pickle_pure_python   | 323 us                                                       | 325 us: 1.01x slower                                       |
| xml_etree_parse      | 146 ms                                                       | 147 ms: 1.01x slower                                       |
| pickle_list          | 4.39 us                                                      | 4.43 us: 1.01x slower                                      |
| unpickle_list        | 4.77 us                                                      | 4.82 us: 1.01x slower                                      |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                      |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                      |
| pickle_dict          | 31.7 us                                                      | 32.6 us: 1.03x slower                                      |
| Geometric mean       | (ref)                                                        | 1.00x slower                                               |

Benchmark hidden because not significant (4): xml_etree_iterparse, xml_etree_process, tomli_loads, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                      |
| python_startup         | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                      |
| Geometric mean         | (ref)                                                        | 1.00x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.1 ms: 1.02x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody                    | 94.1 ms                                                      | 83.4 ms: 1.13x faster                                      |
| create_gc_cycles         | 1.67 ms                                                      | 1.58 ms: 1.06x faster                                      |
| scimark_monte_carlo      | 72.4 ms                                                      | 69.6 ms: 1.04x faster                                      |
| regex_v8                 | 25.0 ms                                                      | 24.1 ms: 1.04x faster                                      |
| pathlib                  | 19.8 ms                                                      | 19.2 ms: 1.03x faster                                      |
| pyflate                  | 447 ms                                                       | 436 ms: 1.03x faster                                       |
| pycparser                | 1.27 sec                                                     | 1.25 sec: 1.02x faster                                     |
| logging_silent           | 95.6 ns                                                      | 93.6 ns: 1.02x faster                                      |
| regex_compile            | 146 ms                                                       | 143 ms: 1.02x faster                                       |
| go                       | 150 ms                                                       | 147 ms: 1.02x faster                                       |
| unpickle                 | 14.8 us                                                      | 14.5 us: 1.02x faster                                      |
| fannkuch                 | 350 ms                                                       | 344 ms: 1.02x faster                                       |
| tornado_http             | 122 ms                                                       | 120 ms: 1.02x faster                                       |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.36 ms: 1.01x faster                                      |
| crypto_pyaes             | 80.9 ms                                                      | 79.8 ms: 1.01x faster                                      |
| coroutines               | 23.0 ms                                                      | 22.7 ms: 1.01x faster                                      |
| nqueens                  | 90.1 ms                                                      | 89.1 ms: 1.01x faster                                      |
| richards_super           | 51.7 ms                                                      | 51.2 ms: 1.01x faster                                      |
| sqlglot_parse            | 1.40 ms                                                      | 1.39 ms: 1.01x faster                                      |
| pprint_safe_repr         | 823 ms                                                       | 817 ms: 1.01x faster                                       |
| xml_etree_generate       | 86.1 ms                                                      | 85.5 ms: 1.01x faster                                      |
| deltablue                | 3.29 ms                                                      | 3.26 ms: 1.01x faster                                      |
| asyncio_tcp              | 381 ms                                                       | 379 ms: 1.01x faster                                       |
| pprint_pformat           | 1.67 sec                                                     | 1.66 sec: 1.01x faster                                     |
| deepcopy_memo            | 37.4 us                                                      | 37.2 us: 1.00x faster                                      |
| unpickle_pure_python     | 207 us                                                       | 206 us: 1.00x faster                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.44 us: 1.00x faster                                      |
| docutils                 | 2.89 sec                                                     | 2.87 sec: 1.00x faster                                     |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.57 sec: 1.00x faster                                     |
| python_startup_no_site   | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                      |
| python_startup           | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                      |
| mdp                      | 2.53 sec                                                     | 2.54 sec: 1.00x slower                                     |
| async_tree_io            | 1.06 sec                                                     | 1.06 sec: 1.00x slower                                     |
| generators               | 36.7 ms                                                      | 36.8 ms: 1.00x slower                                      |
| dulwich_log              | 65.3 ms                                                      | 65.7 ms: 1.01x slower                                      |
| async_tree_memoization   | 553 ms                                                       | 557 ms: 1.01x slower                                       |
| pickle_pure_python       | 323 us                                                       | 325 us: 1.01x slower                                       |
| sqlite_synth             | 2.70 us                                                      | 2.72 us: 1.01x slower                                      |
| scimark_fft              | 304 ms                                                       | 306 ms: 1.01x slower                                       |
| float                    | 78.5 ms                                                      | 79.1 ms: 1.01x slower                                      |
| xml_etree_parse          | 146 ms                                                       | 147 ms: 1.01x slower                                       |
| async_tree_none          | 459 ms                                                       | 463 ms: 1.01x slower                                       |
| typing_runtime_protocols | 151 us                                                       | 153 us: 1.01x slower                                       |
| pickle_list              | 4.39 us                                                      | 4.43 us: 1.01x slower                                      |
| unpickle_list            | 4.77 us                                                      | 4.82 us: 1.01x slower                                      |
| regex_dna                | 241 ms                                                       | 244 ms: 1.01x slower                                       |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                      |
| deepcopy                 | 376 us                                                       | 381 us: 1.01x slower                                       |
| json_dumps               | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                      |
| regex_effbot             | 3.47 ms                                                      | 3.53 ms: 1.02x slower                                      |
| sqlglot_normalize        | 117 ms                                                       | 119 ms: 1.02x slower                                       |
| mako                     | 9.94 ms                                                      | 10.1 ms: 1.02x slower                                      |
| meteor_contest           | 128 ms                                                       | 130 ms: 1.02x slower                                       |
| chaos                    | 62.9 ms                                                      | 64.2 ms: 1.02x slower                                      |
| sqlglot_optimize         | 57.8 ms                                                      | 59.2 ms: 1.02x slower                                      |
| coverage                 | 89.6 ms                                                      | 92.1 ms: 1.03x slower                                      |
| pickle_dict              | 31.7 us                                                      | 32.6 us: 1.03x slower                                      |
| logging_format           | 7.37 us                                                      | 7.65 us: 1.04x slower                                      |
| logging_simple           | 6.73 us                                                      | 7.00 us: 1.04x slower                                      |
| telco                    | 6.96 ms                                                      | 7.45 ms: 1.07x slower                                      |
| bench_mp_pool            | 5.34 ms                                                      | 5.87 ms: 1.10x slower                                      |
| gc_traversal             | 3.54 ms                                                      | 3.94 ms: 1.11x slower                                      |
| mypy2                    | 368 ms                                                       | 459 ms: 1.25x slower                                       |
| Geometric mean           | (ref)                                                        | 1.00x slower                                               |

Benchmark hidden because not significant (20): bench_thread_pool, xml_etree_iterparse, sqlglot_transpile, dask, xml_etree_process, async_tree_cpu_io_mixed, tomli_loads, async_generators, 2to3, raytrace, pidigits, hexiom, scimark_sor, comprehensions, json_loads, richards, json, scimark_lu, spectral_norm, unpack_sequence


# HPT report

- Reliability score: 69.60% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
