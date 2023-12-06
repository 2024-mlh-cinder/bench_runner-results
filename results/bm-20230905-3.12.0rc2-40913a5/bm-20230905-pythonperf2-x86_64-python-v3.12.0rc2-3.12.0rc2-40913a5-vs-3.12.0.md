
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0rc2
- machine: linux-x86_64
- commit hash: 40913a5
- commit date: 2023-09-05
- overall geometric mean: 1.00x faster
- HPT reliability: 97.61%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 287 ms: 1.00x faster                                               |
| docutils       | 2.89 sec                                                     | 2.90 sec: 1.01x slower                                             |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                               |
| Geometric mean | (ref)                                                        | 1.00x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 87.5 ms: 1.08x faster                                              |
| float          | 78.5 ms                                                      | 79.6 ms: 1.01x slower                                              |
| Geometric mean | (ref)                                                        | 1.02x faster                                                       |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 23.8 ms: 1.05x faster                                              |
| regex_dna      | 241 ms                                                       | 238 ms: 1.01x faster                                               |
| regex_compile  | 146 ms                                                       | 146 ms: 1.00x slower                                               |
| regex_effbot   | 3.47 ms                                                      | 3.52 ms: 1.01x slower                                              |
| Geometric mean | (ref)                                                        | 1.01x faster                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| tomli_loads          | 2.20 sec                                                     | 2.17 sec: 1.01x faster                                             |
| json_loads           | 24.3 us                                                      | 24.4 us: 1.01x slower                                              |
| pickle_pure_python   | 323 us                                                       | 326 us: 1.01x slower                                               |
| xml_etree_process    | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                              |
| pickle_list          | 4.39 us                                                      | 4.46 us: 1.02x slower                                              |
| pickle_dict          | 31.7 us                                                      | 32.4 us: 1.02x slower                                              |
| unpickle_pure_python | 207 us                                                       | 212 us: 1.02x slower                                               |
| pickle               | 10.1 us                                                      | 10.4 us: 1.03x slower                                              |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                       |

Benchmark hidden because not significant (6): unpickle_list, xml_etree_generate, xml_etree_parse, unpickle, json_dumps, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                              |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                       |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.79 ms: 1.11x faster                                              |
| nbody                    | 94.1 ms                                                      | 87.5 ms: 1.08x faster                                              |
| scimark_fft              | 304 ms                                                       | 288 ms: 1.06x faster                                               |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.21 ms: 1.05x faster                                              |
| regex_v8                 | 25.0 ms                                                      | 23.8 ms: 1.05x faster                                              |
| fannkuch                 | 350 ms                                                       | 335 ms: 1.05x faster                                               |
| scimark_monte_carlo      | 72.4 ms                                                      | 69.4 ms: 1.04x faster                                              |
| pycparser                | 1.27 sec                                                     | 1.23 sec: 1.04x faster                                             |
| pathlib                  | 19.8 ms                                                      | 19.1 ms: 1.03x faster                                              |
| scimark_lu               | 101 ms                                                       | 97.6 ms: 1.03x faster                                              |
| richards_super           | 51.7 ms                                                      | 50.5 ms: 1.02x faster                                              |
| coverage                 | 89.6 ms                                                      | 88.0 ms: 1.02x faster                                              |
| tornado_http             | 122 ms                                                       | 120 ms: 1.02x faster                                               |
| go                       | 150 ms                                                       | 148 ms: 1.02x faster                                               |
| meteor_contest           | 128 ms                                                       | 126 ms: 1.02x faster                                               |
| typing_runtime_protocols | 151 us                                                       | 149 us: 1.01x faster                                               |
| tomli_loads              | 2.20 sec                                                     | 2.17 sec: 1.01x faster                                             |
| regex_dna                | 241 ms                                                       | 238 ms: 1.01x faster                                               |
| pyflate                  | 447 ms                                                       | 443 ms: 1.01x faster                                               |
| async_generators         | 385 ms                                                       | 381 ms: 1.01x faster                                               |
| chaos                    | 62.9 ms                                                      | 62.3 ms: 1.01x faster                                              |
| dulwich_log              | 65.3 ms                                                      | 64.9 ms: 1.01x faster                                              |
| mdp                      | 2.53 sec                                                     | 2.52 sec: 1.01x faster                                             |
| pprint_pformat           | 1.67 sec                                                     | 1.67 sec: 1.00x faster                                             |
| pprint_safe_repr         | 823 ms                                                       | 820 ms: 1.00x faster                                               |
| spectral_norm            | 91.6 ms                                                      | 91.3 ms: 1.00x faster                                              |
| python_startup_no_site   | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                              |
| 2to3                     | 287 ms                                                       | 287 ms: 1.00x faster                                               |
| regex_compile            | 146 ms                                                       | 146 ms: 1.00x slower                                               |
| telco                    | 6.96 ms                                                      | 6.99 ms: 1.00x slower                                              |
| json_loads               | 24.3 us                                                      | 24.4 us: 1.01x slower                                              |
| docutils                 | 2.89 sec                                                     | 2.90 sec: 1.01x slower                                             |
| scimark_sor              | 110 ms                                                       | 111 ms: 1.01x slower                                               |
| sqlglot_parse            | 1.40 ms                                                      | 1.41 ms: 1.01x slower                                              |
| crypto_pyaes             | 80.9 ms                                                      | 81.5 ms: 1.01x slower                                              |
| unpack_sequence          | 53.3 ns                                                      | 53.7 ns: 1.01x slower                                              |
| deepcopy_memo            | 37.4 us                                                      | 37.7 us: 1.01x slower                                              |
| sqlite_synth             | 2.70 us                                                      | 2.72 us: 1.01x slower                                              |
| pickle_pure_python       | 323 us                                                       | 326 us: 1.01x slower                                               |
| xml_etree_process        | 58.3 ms                                                      | 58.9 ms: 1.01x slower                                              |
| asyncio_tcp              | 381 ms                                                       | 386 ms: 1.01x slower                                               |
| regex_effbot             | 3.47 ms                                                      | 3.52 ms: 1.01x slower                                              |
| float                    | 78.5 ms                                                      | 79.6 ms: 1.01x slower                                              |
| nqueens                  | 90.1 ms                                                      | 91.3 ms: 1.01x slower                                              |
| coroutines               | 23.0 ms                                                      | 23.3 ms: 1.01x slower                                              |
| sqlglot_optimize         | 57.8 ms                                                      | 58.6 ms: 1.01x slower                                              |
| logging_simple           | 6.73 us                                                      | 6.84 us: 1.02x slower                                              |
| deepcopy                 | 376 us                                                       | 382 us: 1.02x slower                                               |
| pickle_list              | 4.39 us                                                      | 4.46 us: 1.02x slower                                              |
| pickle_dict              | 31.7 us                                                      | 32.4 us: 1.02x slower                                              |
| raytrace                 | 302 ms                                                       | 308 ms: 1.02x slower                                               |
| unpickle_pure_python     | 207 us                                                       | 212 us: 1.02x slower                                               |
| sqlglot_normalize        | 117 ms                                                       | 120 ms: 1.02x slower                                               |
| pickle                   | 10.1 us                                                      | 10.4 us: 1.03x slower                                              |
| dask                     | 397 ms                                                       | 566 ms: 1.43x slower                                               |
| Geometric mean           | (ref)                                                        | 1.00x faster                                                       |

Benchmark hidden because not significant (28): richards, create_gc_cycles, bench_thread_pool, async_tree_cpu_io_mixed, unpickle_list, json, xml_etree_generate, xml_etree_parse, unpickle, comprehensions, async_tree_memoization, mako, mypy2, async_tree_none, deltablue, deepcopy_reduce, asyncio_tcp_ssl, json_dumps, python_startup, xml_etree_iterparse, async_tree_io, pidigits, generators, gc_traversal, hexiom, logging_silent, sqlglot_transpile, logging_format


# HPT report

- Reliability score: 97.61% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
