
# Results vs. base

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: windows-amd64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.01x faster
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| chameleon      | 4.88 ms                                                                     | 4.75 ms: 1.03x faster                                                       |
| docutils       | 1.56 sec                                                                    | 1.55 sec: 1.01x faster                                                      |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none_tg | 284 ms                                                                      | 281 ms: 1.01x faster                                                        |
| Geometric mean     | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (7): async_tree_none, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_io_tg, async_tree_memoization_tg, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 75.5 ms                                                                     | 71.3 ms: 1.06x faster                                                       |
| float          | 52.1 ms                                                                     | 51.5 ms: 1.01x faster                                                       |
| pidigits       | 147 ms                                                                      | 146 ms: 1.01x faster                                                        |
| Geometric mean | (ref)                                                                       | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 80.4 ms                                                                     | 78.7 ms: 1.02x faster                                                       |
| regex_effbot   | 1.58 ms                                                                     | 1.55 ms: 1.02x faster                                                       |
| regex_v8       | 14.6 ms                                                                     | 14.6 ms: 1.00x faster                                                       |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads          | 1.45 sec                                                                    | 1.42 sec: 1.02x faster                                                      |
| unpickle_pure_python | 130 us                                                                      | 127 us: 1.02x faster                                                        |
| pickle_pure_python   | 181 us                                                                      | 177 us: 1.02x faster                                                        |
| json_dumps           | 5.65 ms                                                                     | 5.59 ms: 1.01x faster                                                       |
| xml_etree_process    | 37.8 ms                                                                     | 37.4 ms: 1.01x faster                                                       |
| json_loads           | 13.5 us                                                                     | 13.3 us: 1.01x faster                                                       |
| pickle_list          | 2.86 us                                                                     | 2.85 us: 1.00x faster                                                       |
| xml_etree_generate   | 54.3 ms                                                                     | 54.7 ms: 1.01x slower                                                       |
| pickle               | 7.03 us                                                                     | 7.18 us: 1.02x slower                                                       |
| xml_etree_parse      | 90.1 ms                                                                     | 92.6 ms: 1.03x slower                                                       |
| pickle_dict          | 18.4 us                                                                     | 18.9 us: 1.03x slower                                                       |
| unpickle_list        | 2.62 us                                                                     | 2.70 us: 1.03x slower                                                       |
| Geometric mean       | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (2): unpickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 6.53 ms                                                                     | 6.45 ms: 1.01x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| scimark_monte_carlo      | 44.8 ms                                                                     | 41.2 ms: 1.09x faster                                                       |
| unpack_sequence          | 41.9 ns                                                                     | 38.5 ns: 1.09x faster                                                       |
| nbody                    | 75.5 ms                                                                     | 71.3 ms: 1.06x faster                                                       |
| scimark_sor              | 80.9 ms                                                                     | 76.8 ms: 1.05x faster                                                       |
| deltablue                | 2.13 ms                                                                     | 2.04 ms: 1.05x faster                                                       |
| deepcopy_memo            | 24.5 us                                                                     | 23.4 us: 1.04x faster                                                       |
| hexiom                   | 3.87 ms                                                                     | 3.74 ms: 1.03x faster                                                       |
| asyncio_tcp              | 545 ms                                                                      | 531 ms: 1.03x faster                                                        |
| chameleon                | 4.88 ms                                                                     | 4.75 ms: 1.03x faster                                                       |
| tomli_loads              | 1.45 sec                                                                    | 1.42 sec: 1.02x faster                                                      |
| scimark_fft              | 178 ms                                                                      | 174 ms: 1.02x faster                                                        |
| telco                    | 4.66 ms                                                                     | 4.56 ms: 1.02x faster                                                       |
| unpickle_pure_python     | 130 us                                                                      | 127 us: 1.02x faster                                                        |
| regex_compile            | 80.4 ms                                                                     | 78.7 ms: 1.02x faster                                                       |
| pickle_pure_python       | 181 us                                                                      | 177 us: 1.02x faster                                                        |
| chaos                    | 40.2 ms                                                                     | 39.3 ms: 1.02x faster                                                       |
| regex_effbot             | 1.58 ms                                                                     | 1.55 ms: 1.02x faster                                                       |
| deepcopy                 | 226 us                                                                      | 222 us: 1.02x faster                                                        |
| go                       | 88.4 ms                                                                     | 86.8 ms: 1.02x faster                                                       |
| pyflate                  | 292 ms                                                                      | 287 ms: 1.02x faster                                                        |
| fannkuch                 | 256 ms                                                                      | 252 ms: 1.02x faster                                                        |
| coverage                 | 46.0 ms                                                                     | 45.3 ms: 1.02x faster                                                       |
| scimark_lu               | 57.6 ms                                                                     | 56.8 ms: 1.01x faster                                                       |
| deepcopy_reduce          | 1.98 us                                                                     | 1.96 us: 1.01x faster                                                       |
| pprint_pformat           | 1.02 sec                                                                    | 1.01 sec: 1.01x faster                                                      |
| mako                     | 6.53 ms                                                                     | 6.45 ms: 1.01x faster                                                       |
| sqlglot_transpile        | 988 us                                                                      | 976 us: 1.01x faster                                                        |
| json_dumps               | 5.65 ms                                                                     | 5.59 ms: 1.01x faster                                                       |
| logging_format           | 6.59 us                                                                     | 6.51 us: 1.01x faster                                                       |
| richards_super           | 31.3 ms                                                                     | 31.0 ms: 1.01x faster                                                       |
| crypto_pyaes             | 43.7 ms                                                                     | 43.2 ms: 1.01x faster                                                       |
| async_tree_none_tg       | 284 ms                                                                      | 281 ms: 1.01x faster                                                        |
| xml_etree_process        | 37.8 ms                                                                     | 37.4 ms: 1.01x faster                                                       |
| richards                 | 28.8 ms                                                                     | 28.5 ms: 1.01x faster                                                       |
| typing_runtime_protocols | 77.0 us                                                                     | 76.2 us: 1.01x faster                                                       |
| float                    | 52.1 ms                                                                     | 51.5 ms: 1.01x faster                                                       |
| dulwich_log              | 41.4 ms                                                                     | 41.1 ms: 1.01x faster                                                       |
| json                     | 2.87 ms                                                                     | 2.85 ms: 1.01x faster                                                       |
| json_loads               | 13.5 us                                                                     | 13.3 us: 1.01x faster                                                       |
| sympy_integrate          | 12.4 ms                                                                     | 12.3 ms: 1.01x faster                                                       |
| sqlglot_parse            | 768 us                                                                      | 762 us: 1.01x faster                                                        |
| gc_traversal             | 1.51 ms                                                                     | 1.50 ms: 1.01x faster                                                       |
| pprint_safe_repr         | 496 ms                                                                      | 493 ms: 1.01x faster                                                        |
| pidigits                 | 147 ms                                                                      | 146 ms: 1.01x faster                                                        |
| docutils                 | 1.56 sec                                                                    | 1.55 sec: 1.01x faster                                                      |
| meteor_contest           | 73.3 ms                                                                     | 72.9 ms: 1.01x faster                                                       |
| nqueens                  | 59.4 ms                                                                     | 59.1 ms: 1.00x faster                                                       |
| coroutines               | 13.2 ms                                                                     | 13.1 ms: 1.00x faster                                                       |
| regex_v8                 | 14.6 ms                                                                     | 14.6 ms: 1.00x faster                                                       |
| pickle_list              | 2.86 us                                                                     | 2.85 us: 1.00x faster                                                       |
| sqlglot_optimize         | 33.3 ms                                                                     | 33.2 ms: 1.00x faster                                                       |
| pathlib                  | 79.8 ms                                                                     | 80.2 ms: 1.00x slower                                                       |
| bench_mp_pool            | 63.9 ms                                                                     | 64.3 ms: 1.01x slower                                                       |
| xml_etree_generate       | 54.3 ms                                                                     | 54.7 ms: 1.01x slower                                                       |
| scimark_sparse_mat_mult  | 2.40 ms                                                                     | 2.42 ms: 1.01x slower                                                       |
| async_generators         | 229 ms                                                                      | 233 ms: 1.01x slower                                                        |
| comprehensions           | 10.3 us                                                                     | 10.5 us: 1.02x slower                                                       |
| pickle                   | 7.03 us                                                                     | 7.18 us: 1.02x slower                                                       |
| mdp                      | 1.34 sec                                                                    | 1.38 sec: 1.02x slower                                                      |
| xml_etree_parse          | 90.1 ms                                                                     | 92.6 ms: 1.03x slower                                                       |
| pickle_dict              | 18.4 us                                                                     | 18.9 us: 1.03x slower                                                       |
| unpickle_list            | 2.62 us                                                                     | 2.70 us: 1.03x slower                                                       |
| generators               | 21.4 ms                                                                     | 22.3 ms: 1.04x slower                                                       |
| Geometric mean           | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (29): async_tree_none, create_gc_cycles, python_startup, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_cpu_io_mixed, logging_simple, async_tree_io_tg, sqlglot_normalize, sqlite_synth, 2to3, sympy_str, unpickle, sympy_expand, tornado_http, spectral_norm, logging_silent, raytrace, bench_thread_pool, sympy_sum, mypy2, async_tree_memoization_tg, xml_etree_iterparse, python_startup_no_site, asyncio_tcp_ssl, regex_dna, async_tree_io, dask, pycparser


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
