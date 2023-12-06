
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 744f752
- commit date: 2023-10-14
- overall geometric mean: 1.05x faster
- HPT reliability: 98.94%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 214 ms: 1.02x slower                                      |
| docutils       | 1.60 sec                                                    | 1.63 sec: 1.02x slower                                    |
| Geometric mean | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| float          | 54.6 ms                                                     | 53.4 ms: 1.02x faster                                     |
| nbody          | 70.0 ms                                                     | 70.6 ms: 1.01x slower                                     |
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x faster                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 87.6 ms: 1.03x faster                                     |
| regex_v8       | 13.8 ms                                                     | 13.7 ms: 1.01x faster                                     |
| regex_dna      | 115 ms                                                      | 122 ms: 1.06x slower                                      |
| regex_effbot   | 1.50 ms                                                     | 1.64 ms: 1.09x slower                                     |
| Geometric mean | (ref)                                                       | 1.02x slower                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.68 ms: 1.33x faster                                     |
| unpickle_pure_python | 152 us                                                      | 138 us: 1.10x faster                                      |
| xml_etree_parse      | 95.9 ms                                                     | 92.3 ms: 1.04x faster                                     |
| pickle_pure_python   | 200 us                                                      | 198 us: 1.01x faster                                      |
| tomli_loads          | 1.41 sec                                                    | 1.43 sec: 1.01x slower                                    |
| xml_etree_iterparse  | 62.6 ms                                                     | 63.3 ms: 1.01x slower                                     |
| unpickle             | 8.09 us                                                     | 8.26 us: 1.02x slower                                     |
| xml_etree_process    | 37.1 ms                                                     | 38.1 ms: 1.03x slower                                     |
| json_loads           | 12.9 us                                                     | 13.7 us: 1.06x slower                                     |
| xml_etree_generate   | 52.2 ms                                                     | 55.6 ms: 1.06x slower                                     |
| pickle               | 6.61 us                                                     | 7.10 us: 1.07x slower                                     |
| pickle_list          | 2.68 us                                                     | 2.88 us: 1.07x slower                                     |
| unpickle_list        | 2.55 us                                                     | 2.74 us: 1.08x slower                                     |
| Geometric mean       | (ref)                                                       | 1.00x faster                                              |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup | 18.7 ms                                                     | 18.8 ms: 1.01x slower                                     |
| Geometric mean | (ref)                                                       | 1.00x slower                                              |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.96 ms: 1.04x faster                                     |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-3.12-3.12.0+-744f752 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 103 us: 3.12x faster                                      |
| asyncio_tcp              | 699 ms                                                      | 471 ms: 1.48x faster                                      |
| generators               | 33.8 ms                                                     | 23.0 ms: 1.47x faster                                     |
| json_dumps               | 7.56 ms                                                     | 5.68 ms: 1.33x faster                                     |
| deltablue                | 2.61 ms                                                     | 2.15 ms: 1.22x faster                                     |
| richards_super           | 37.5 ms                                                     | 31.0 ms: 1.21x faster                                     |
| sqlglot_parse            | 952 us                                                      | 818 us: 1.16x faster                                      |
| logging_silent           | 69.8 ns                                                     | 60.6 ns: 1.15x faster                                     |
| sqlglot_transpile        | 1.16 ms                                                     | 1.04 ms: 1.12x faster                                     |
| richards                 | 30.6 ms                                                     | 27.3 ms: 1.12x faster                                     |
| json                     | 3.25 ms                                                     | 2.92 ms: 1.12x faster                                     |
| coverage                 | 55.9 ms                                                     | 50.5 ms: 1.11x faster                                     |
| async_tree_none          | 320 ms                                                      | 290 ms: 1.10x faster                                      |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.91 sec: 1.10x faster                                    |
| async_tree_memoization   | 371 ms                                                      | 336 ms: 1.10x faster                                      |
| unpickle_pure_python     | 152 us                                                      | 138 us: 1.10x faster                                      |
| hexiom                   | 4.55 ms                                                     | 4.14 ms: 1.10x faster                                     |
| async_tree_io            | 779 ms                                                      | 709 ms: 1.10x faster                                      |
| mdp                      | 1.67 sec                                                    | 1.52 sec: 1.10x faster                                    |
| comprehensions           | 15.9 us                                                     | 14.5 us: 1.10x faster                                     |
| mypy2                    | 229 ms                                                      | 209 ms: 1.10x faster                                      |
| chaos                    | 47.1 ms                                                     | 43.4 ms: 1.09x faster                                     |
| raytrace                 | 211 ms                                                      | 195 ms: 1.08x faster                                      |
| scimark_lu               | 63.5 ms                                                     | 59.4 ms: 1.07x faster                                     |
| aiohttp                  | 899 us                                                      | 846 us: 1.06x faster                                      |
| logging_simple           | 6.61 us                                                     | 6.25 us: 1.06x faster                                     |
| spectral_norm            | 67.9 ms                                                     | 64.6 ms: 1.05x faster                                     |
| dulwich_log              | 44.5 ms                                                     | 42.4 ms: 1.05x faster                                     |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 479 ms: 1.05x faster                                      |
| mako                     | 7.26 ms                                                     | 6.96 ms: 1.04x faster                                     |
| xml_etree_parse          | 95.9 ms                                                     | 92.3 ms: 1.04x faster                                     |
| dask                     | 264 ms                                                      | 254 ms: 1.04x faster                                      |
| nqueens                  | 64.9 ms                                                     | 62.5 ms: 1.04x faster                                     |
| logging_format           | 7.01 us                                                     | 6.76 us: 1.04x faster                                     |
| regex_compile            | 90.6 ms                                                     | 87.6 ms: 1.03x faster                                     |
| go                       | 97.3 ms                                                     | 94.1 ms: 1.03x faster                                     |
| bench_thread_pool        | 852 us                                                      | 828 us: 1.03x faster                                      |
| sqlglot_normalize        | 190 ms                                                      | 185 ms: 1.03x faster                                      |
| pyflate                  | 304 ms                                                      | 295 ms: 1.03x faster                                      |
| deepcopy_memo            | 25.2 us                                                     | 24.5 us: 1.03x faster                                     |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.51 ms: 1.02x faster                                     |
| float                    | 54.6 ms                                                     | 53.4 ms: 1.02x faster                                     |
| meteor_contest           | 74.7 ms                                                     | 73.1 ms: 1.02x faster                                     |
| sqlglot_optimize         | 34.9 ms                                                     | 34.2 ms: 1.02x faster                                     |
| deepcopy                 | 246 us                                                      | 242 us: 1.01x faster                                      |
| regex_v8                 | 13.8 ms                                                     | 13.7 ms: 1.01x faster                                     |
| pickle_pure_python       | 200 us                                                      | 198 us: 1.01x faster                                      |
| crypto_pyaes             | 47.6 ms                                                     | 47.2 ms: 1.01x faster                                     |
| bench_mp_pool            | 62.5 ms                                                     | 62.8 ms: 1.00x slower                                     |
| gc_traversal             | 1.46 ms                                                     | 1.47 ms: 1.01x slower                                     |
| python_startup           | 18.7 ms                                                     | 18.8 ms: 1.01x slower                                     |
| pprint_safe_repr         | 512 ms                                                      | 516 ms: 1.01x slower                                      |
| nbody                    | 70.0 ms                                                     | 70.6 ms: 1.01x slower                                     |
| pprint_pformat           | 1.04 sec                                                    | 1.05 sec: 1.01x slower                                    |
| tomli_loads              | 1.41 sec                                                    | 1.43 sec: 1.01x slower                                    |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.3 ms: 1.01x slower                                     |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                      |
| pycparser                | 691 ms                                                      | 701 ms: 1.01x slower                                      |
| create_gc_cycles         | 693 us                                                      | 705 us: 1.02x slower                                      |
| docutils                 | 1.60 sec                                                    | 1.63 sec: 1.02x slower                                    |
| unpickle                 | 8.09 us                                                     | 8.26 us: 1.02x slower                                     |
| 2to3                     | 209 ms                                                      | 214 ms: 1.02x slower                                      |
| deepcopy_reduce          | 2.07 us                                                     | 2.12 us: 1.02x slower                                     |
| scimark_fft              | 178 ms                                                      | 183 ms: 1.02x slower                                      |
| xml_etree_process        | 37.1 ms                                                     | 38.1 ms: 1.03x slower                                     |
| unpack_sequence          | 46.1 ns                                                     | 47.7 ns: 1.04x slower                                     |
| sqlite_synth             | 1.68 us                                                     | 1.74 us: 1.04x slower                                     |
| telco                    | 3.90 ms                                                     | 4.05 ms: 1.04x slower                                     |
| regex_dna                | 115 ms                                                      | 122 ms: 1.06x slower                                      |
| json_loads               | 12.9 us                                                     | 13.7 us: 1.06x slower                                     |
| xml_etree_generate       | 52.2 ms                                                     | 55.6 ms: 1.06x slower                                     |
| pickle                   | 6.61 us                                                     | 7.10 us: 1.07x slower                                     |
| pickle_list              | 2.68 us                                                     | 2.88 us: 1.07x slower                                     |
| unpickle_list            | 2.55 us                                                     | 2.74 us: 1.08x slower                                     |
| pathlib                  | 71.4 ms                                                     | 77.7 ms: 1.09x slower                                     |
| scimark_sor              | 75.6 ms                                                     | 82.4 ms: 1.09x slower                                     |
| regex_effbot             | 1.50 ms                                                     | 1.64 ms: 1.09x slower                                     |
| async_generators         | 178 ms                                                      | 236 ms: 1.33x slower                                      |
| Geometric mean           | (ref)                                                       | 1.05x faster                                              |

Benchmark hidden because not significant (6): pickle_dict, coroutines, tornado_http, scimark_monte_carlo, python_startup_no_site, fannkuch
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 98.94% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
