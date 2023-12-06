
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.06x faster
- HPT reliability: 99.98%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 211 ms: 1.01x slower                                         |
| docutils       | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                       |
| tornado_http   | 91.8 ms                                                     | 87.6 ms: 1.05x faster                                        |
| Geometric mean | (ref)                                                       | 1.01x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                         |
| nbody          | 70.0 ms                                                     | 71.8 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                       | 1.01x slower                                                 |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 86.9 ms: 1.04x faster                                        |
| regex_v8       | 13.8 ms                                                     | 13.5 ms: 1.02x faster                                        |
| regex_dna      | 115 ms                                                      | 118 ms: 1.02x slower                                         |
| regex_effbot   | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                        |
| Geometric mean | (ref)                                                       | 1.00x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.68 ms: 1.33x faster                                        |
| unpickle_pure_python | 152 us                                                      | 135 us: 1.13x faster                                         |
| xml_etree_parse      | 95.9 ms                                                     | 90.9 ms: 1.06x faster                                        |
| pickle_pure_python   | 200 us                                                      | 192 us: 1.04x faster                                         |
| tomli_loads          | 1.41 sec                                                    | 1.36 sec: 1.04x faster                                       |
| xml_etree_iterparse  | 62.6 ms                                                     | 63.4 ms: 1.01x slower                                        |
| xml_etree_process    | 37.1 ms                                                     | 38.2 ms: 1.03x slower                                        |
| unpickle             | 8.09 us                                                     | 8.40 us: 1.04x slower                                        |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                        |
| unpickle_list        | 2.55 us                                                     | 2.68 us: 1.05x slower                                        |
| xml_etree_generate   | 52.2 ms                                                     | 55.6 ms: 1.06x slower                                        |
| pickle               | 6.61 us                                                     | 7.09 us: 1.07x slower                                        |
| pickle_list          | 2.68 us                                                     | 2.88 us: 1.08x slower                                        |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                 |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.93 ms: 1.05x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230922-pythonperf1-amd64-python-3.12-3.12.0rc3+-f6287bd |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 96.0 us: 3.35x faster                                        |
| asyncio_tcp              | 699 ms                                                      | 464 ms: 1.51x faster                                         |
| generators               | 33.8 ms                                                     | 22.9 ms: 1.48x faster                                        |
| json_dumps               | 7.56 ms                                                     | 5.68 ms: 1.33x faster                                        |
| richards_super           | 37.5 ms                                                     | 30.4 ms: 1.23x faster                                        |
| deltablue                | 2.61 ms                                                     | 2.13 ms: 1.23x faster                                        |
| unpack_sequence          | 46.1 ns                                                     | 38.5 ns: 1.20x faster                                        |
| sqlglot_parse            | 952 us                                                      | 809 us: 1.18x faster                                         |
| logging_silent           | 69.8 ns                                                     | 60.6 ns: 1.15x faster                                        |
| richards                 | 30.6 ms                                                     | 26.6 ms: 1.15x faster                                        |
| sqlglot_transpile        | 1.16 ms                                                     | 1.02 ms: 1.14x faster                                        |
| comprehensions           | 15.9 us                                                     | 14.0 us: 1.14x faster                                        |
| hexiom                   | 4.55 ms                                                     | 4.00 ms: 1.14x faster                                        |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.87 sec: 1.13x faster                                       |
| unpickle_pure_python     | 152 us                                                      | 135 us: 1.13x faster                                         |
| json                     | 3.25 ms                                                     | 2.89 ms: 1.13x faster                                        |
| async_tree_none          | 320 ms                                                      | 288 ms: 1.11x faster                                         |
| go                       | 97.3 ms                                                     | 87.5 ms: 1.11x faster                                        |
| chaos                    | 47.1 ms                                                     | 42.4 ms: 1.11x faster                                        |
| raytrace                 | 211 ms                                                      | 190 ms: 1.11x faster                                         |
| async_tree_memoization   | 371 ms                                                      | 337 ms: 1.10x faster                                         |
| mdp                      | 1.67 sec                                                    | 1.52 sec: 1.10x faster                                       |
| mypy2                    | 229 ms                                                      | 209 ms: 1.10x faster                                         |
| scimark_lu               | 63.5 ms                                                     | 58.5 ms: 1.09x faster                                        |
| async_tree_io            | 779 ms                                                      | 718 ms: 1.08x faster                                         |
| spectral_norm            | 67.9 ms                                                     | 63.2 ms: 1.08x faster                                        |
| logging_simple           | 6.61 us                                                     | 6.17 us: 1.07x faster                                        |
| logging_format           | 7.01 us                                                     | 6.61 us: 1.06x faster                                        |
| deepcopy_memo            | 25.2 us                                                     | 23.7 us: 1.06x faster                                        |
| coverage                 | 55.9 ms                                                     | 52.7 ms: 1.06x faster                                        |
| fannkuch                 | 252 ms                                                      | 238 ms: 1.06x faster                                         |
| xml_etree_parse          | 95.9 ms                                                     | 90.9 ms: 1.06x faster                                        |
| nqueens                  | 64.9 ms                                                     | 61.5 ms: 1.06x faster                                        |
| aiohttp                  | 899 us                                                      | 854 us: 1.05x faster                                         |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 477 ms: 1.05x faster                                         |
| mako                     | 7.26 ms                                                     | 6.93 ms: 1.05x faster                                        |
| tornado_http             | 91.8 ms                                                     | 87.6 ms: 1.05x faster                                        |
| dulwich_log              | 44.5 ms                                                     | 42.5 ms: 1.05x faster                                        |
| regex_compile            | 90.6 ms                                                     | 86.9 ms: 1.04x faster                                        |
| pickle_pure_python       | 200 us                                                      | 192 us: 1.04x faster                                         |
| tomli_loads              | 1.41 sec                                                    | 1.36 sec: 1.04x faster                                       |
| deepcopy                 | 246 us                                                      | 237 us: 1.04x faster                                         |
| sqlglot_normalize        | 190 ms                                                      | 184 ms: 1.04x faster                                         |
| crypto_pyaes             | 47.6 ms                                                     | 46.0 ms: 1.03x faster                                        |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.49 ms: 1.03x faster                                        |
| bench_thread_pool        | 852 us                                                      | 825 us: 1.03x faster                                         |
| meteor_contest           | 74.7 ms                                                     | 72.4 ms: 1.03x faster                                        |
| pycparser                | 691 ms                                                      | 670 ms: 1.03x faster                                         |
| pyflate                  | 304 ms                                                      | 296 ms: 1.03x faster                                         |
| regex_v8                 | 13.8 ms                                                     | 13.5 ms: 1.02x faster                                        |
| coroutines               | 14.6 ms                                                     | 14.3 ms: 1.02x faster                                        |
| sqlglot_optimize         | 34.9 ms                                                     | 34.2 ms: 1.02x faster                                        |
| scimark_monte_carlo      | 44.6 ms                                                     | 44.1 ms: 1.01x faster                                        |
| pprint_safe_repr         | 512 ms                                                      | 508 ms: 1.01x faster                                         |
| pprint_pformat           | 1.04 sec                                                    | 1.03 sec: 1.01x faster                                       |
| 2to3                     | 209 ms                                                      | 211 ms: 1.01x slower                                         |
| docutils                 | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                       |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                         |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.4 ms: 1.01x slower                                        |
| deepcopy_reduce          | 2.07 us                                                     | 2.11 us: 1.02x slower                                        |
| gc_traversal             | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                        |
| regex_dna                | 115 ms                                                      | 118 ms: 1.02x slower                                         |
| nbody                    | 70.0 ms                                                     | 71.8 ms: 1.03x slower                                        |
| xml_etree_process        | 37.1 ms                                                     | 38.2 ms: 1.03x slower                                        |
| unpickle                 | 8.09 us                                                     | 8.40 us: 1.04x slower                                        |
| sqlite_synth             | 1.68 us                                                     | 1.75 us: 1.04x slower                                        |
| telco                    | 3.90 ms                                                     | 4.07 ms: 1.04x slower                                        |
| create_gc_cycles         | 693 us                                                      | 726 us: 1.05x slower                                         |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                        |
| unpickle_list            | 2.55 us                                                     | 2.68 us: 1.05x slower                                        |
| regex_effbot             | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                        |
| xml_etree_generate       | 52.2 ms                                                     | 55.6 ms: 1.06x slower                                        |
| bench_mp_pool            | 62.5 ms                                                     | 66.8 ms: 1.07x slower                                        |
| scimark_sor              | 75.6 ms                                                     | 80.9 ms: 1.07x slower                                        |
| pickle                   | 6.61 us                                                     | 7.09 us: 1.07x slower                                        |
| pickle_list              | 2.68 us                                                     | 2.88 us: 1.08x slower                                        |
| pathlib                  | 71.4 ms                                                     | 78.2 ms: 1.10x slower                                        |
| async_generators         | 178 ms                                                      | 233 ms: 1.31x slower                                         |
| dask                     | 264 ms                                                      | 362 ms: 1.37x slower                                         |
| Geometric mean           | (ref)                                                       | 1.06x faster                                                 |

Benchmark hidden because not significant (5): pickle_dict, float, scimark_fft, python_startup, python_startup_no_site
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
