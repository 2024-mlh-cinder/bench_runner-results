
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.01x faster
- HPT reliability: 81.01%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.65 sec: 1.03x slower                                      |
| tornado_http   | 91.8 ms                                                     | 90.8 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 147 ms: 1.01x faster                                        |
| float          | 54.6 ms                                                     | 58.9 ms: 1.08x slower                                       |
| nbody          | 70.0 ms                                                     | 83.4 ms: 1.19x slower                                       |
| Geometric mean | (ref)                                                       | 1.08x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 119 ms: 1.03x slower                                        |
| regex_compile  | 90.6 ms                                                     | 93.4 ms: 1.03x slower                                       |
| regex_effbot   | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                       |
| regex_v8       | 13.8 ms                                                     | 15.0 ms: 1.08x slower                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.69 ms: 1.33x faster                                       |
| unpickle_pure_python | 152 us                                                      | 144 us: 1.06x faster                                        |
| xml_etree_parse      | 95.9 ms                                                     | 92.3 ms: 1.04x faster                                       |
| pickle_dict          | 18.5 us                                                     | 18.1 us: 1.02x faster                                       |
| xml_etree_iterparse  | 62.6 ms                                                     | 65.2 ms: 1.04x slower                                       |
| pickle_list          | 2.68 us                                                     | 2.81 us: 1.05x slower                                       |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                       |
| pickle               | 6.61 us                                                     | 7.00 us: 1.06x slower                                       |
| unpickle_list        | 2.55 us                                                     | 2.73 us: 1.07x slower                                       |
| xml_etree_process    | 37.1 ms                                                     | 40.1 ms: 1.08x slower                                       |
| xml_etree_generate   | 52.2 ms                                                     | 57.2 ms: 1.10x slower                                       |
| tomli_loads          | 1.41 sec                                                    | 1.57 sec: 1.11x slower                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (2): pickle_pure_python, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.3 ms: 1.02x slower                                       |
| python_startup         | 18.7 ms                                                     | 19.4 ms: 1.04x slower                                       |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.70 ms: 1.06x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 96.2 us: 3.34x faster                                       |
| asyncio_tcp              | 699 ms                                                      | 481 ms: 1.45x faster                                        |
| json_dumps               | 7.56 ms                                                     | 5.69 ms: 1.33x faster                                       |
| generators               | 33.8 ms                                                     | 26.1 ms: 1.30x faster                                       |
| coverage                 | 55.9 ms                                                     | 45.7 ms: 1.22x faster                                       |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.75 sec: 1.21x faster                                      |
| unpack_sequence          | 46.1 ns                                                     | 39.8 ns: 1.16x faster                                       |
| json                     | 3.25 ms                                                     | 2.86 ms: 1.14x faster                                       |
| async_tree_none          | 320 ms                                                      | 282 ms: 1.14x faster                                        |
| richards_super           | 37.5 ms                                                     | 34.1 ms: 1.10x faster                                       |
| raytrace                 | 211 ms                                                      | 192 ms: 1.10x faster                                        |
| mdp                      | 1.67 sec                                                    | 1.53 sec: 1.09x faster                                      |
| deltablue                | 2.61 ms                                                     | 2.40 ms: 1.09x faster                                       |
| sqlglot_parse            | 952 us                                                      | 888 us: 1.07x faster                                        |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 472 ms: 1.06x faster                                        |
| unpickle_pure_python     | 152 us                                                      | 144 us: 1.06x faster                                        |
| scimark_lu               | 63.5 ms                                                     | 60.6 ms: 1.05x faster                                       |
| chaos                    | 47.1 ms                                                     | 45.1 ms: 1.04x faster                                       |
| sqlglot_transpile        | 1.16 ms                                                     | 1.12 ms: 1.04x faster                                       |
| crypto_pyaes             | 47.6 ms                                                     | 45.7 ms: 1.04x faster                                       |
| xml_etree_parse          | 95.9 ms                                                     | 92.3 ms: 1.04x faster                                       |
| spectral_norm            | 67.9 ms                                                     | 65.4 ms: 1.04x faster                                       |
| mypy2                    | 229 ms                                                      | 220 ms: 1.04x faster                                        |
| comprehensions           | 15.9 us                                                     | 15.4 us: 1.03x faster                                       |
| async_tree_io            | 779 ms                                                      | 756 ms: 1.03x faster                                        |
| async_tree_memoization   | 371 ms                                                      | 360 ms: 1.03x faster                                        |
| scimark_monte_carlo      | 44.6 ms                                                     | 43.5 ms: 1.03x faster                                       |
| pickle_dict              | 18.5 us                                                     | 18.1 us: 1.02x faster                                       |
| tornado_http             | 91.8 ms                                                     | 90.8 ms: 1.01x faster                                       |
| pidigits                 | 148 ms                                                      | 147 ms: 1.01x faster                                        |
| richards                 | 30.6 ms                                                     | 30.4 ms: 1.01x faster                                       |
| hexiom                   | 4.55 ms                                                     | 4.53 ms: 1.01x faster                                       |
| sqlite_synth             | 1.68 us                                                     | 1.67 us: 1.00x faster                                       |
| meteor_contest           | 74.7 ms                                                     | 75.4 ms: 1.01x slower                                       |
| go                       | 97.3 ms                                                     | 98.4 ms: 1.01x slower                                       |
| deepcopy                 | 246 us                                                      | 249 us: 1.01x slower                                        |
| gc_traversal             | 1.46 ms                                                     | 1.48 ms: 1.02x slower                                       |
| bench_mp_pool            | 62.5 ms                                                     | 63.8 ms: 1.02x slower                                       |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.62 ms: 1.02x slower                                       |
| sqlglot_normalize        | 190 ms                                                      | 195 ms: 1.02x slower                                        |
| python_startup_no_site   | 15.9 ms                                                     | 16.3 ms: 1.02x slower                                       |
| regex_dna                | 115 ms                                                      | 119 ms: 1.03x slower                                        |
| regex_compile            | 90.6 ms                                                     | 93.4 ms: 1.03x slower                                       |
| docutils                 | 1.60 sec                                                    | 1.65 sec: 1.03x slower                                      |
| dulwich_log              | 44.5 ms                                                     | 46.0 ms: 1.03x slower                                       |
| python_startup           | 18.7 ms                                                     | 19.4 ms: 1.04x slower                                       |
| pyflate                  | 304 ms                                                      | 316 ms: 1.04x slower                                        |
| xml_etree_iterparse      | 62.6 ms                                                     | 65.2 ms: 1.04x slower                                       |
| deepcopy_memo            | 25.2 us                                                     | 26.3 us: 1.04x slower                                       |
| logging_simple           | 6.61 us                                                     | 6.91 us: 1.04x slower                                       |
| pprint_safe_repr         | 512 ms                                                      | 536 ms: 1.05x slower                                        |
| create_gc_cycles         | 693 us                                                      | 726 us: 1.05x slower                                        |
| pickle_list              | 2.68 us                                                     | 2.81 us: 1.05x slower                                       |
| coroutines               | 14.6 ms                                                     | 15.4 ms: 1.05x slower                                       |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                       |
| sqlglot_optimize         | 34.9 ms                                                     | 36.8 ms: 1.05x slower                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.10 sec: 1.06x slower                                      |
| regex_effbot             | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                       |
| mako                     | 7.26 ms                                                     | 7.70 ms: 1.06x slower                                       |
| pickle                   | 6.61 us                                                     | 7.00 us: 1.06x slower                                       |
| logging_format           | 7.01 us                                                     | 7.45 us: 1.06x slower                                       |
| deepcopy_reduce          | 2.07 us                                                     | 2.20 us: 1.06x slower                                       |
| fannkuch                 | 252 ms                                                      | 269 ms: 1.07x slower                                        |
| scimark_fft              | 178 ms                                                      | 191 ms: 1.07x slower                                        |
| unpickle_list            | 2.55 us                                                     | 2.73 us: 1.07x slower                                       |
| float                    | 54.6 ms                                                     | 58.9 ms: 1.08x slower                                       |
| regex_v8                 | 13.8 ms                                                     | 15.0 ms: 1.08x slower                                       |
| xml_etree_process        | 37.1 ms                                                     | 40.1 ms: 1.08x slower                                       |
| xml_etree_generate       | 52.2 ms                                                     | 57.2 ms: 1.10x slower                                       |
| scimark_sor              | 75.6 ms                                                     | 82.9 ms: 1.10x slower                                       |
| tomli_loads              | 1.41 sec                                                    | 1.57 sec: 1.11x slower                                      |
| pathlib                  | 71.4 ms                                                     | 79.1 ms: 1.11x slower                                       |
| pycparser                | 691 ms                                                      | 805 ms: 1.16x slower                                        |
| nbody                    | 70.0 ms                                                     | 83.4 ms: 1.19x slower                                       |
| telco                    | 3.90 ms                                                     | 4.77 ms: 1.22x slower                                       |
| async_generators         | 178 ms                                                      | 245 ms: 1.38x slower                                        |
| Geometric mean           | (ref)                                                       | 1.01x faster                                                |

Benchmark hidden because not significant (5): pickle_pure_python, nqueens, logging_silent, unpickle, bench_thread_pool
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 81.01% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
