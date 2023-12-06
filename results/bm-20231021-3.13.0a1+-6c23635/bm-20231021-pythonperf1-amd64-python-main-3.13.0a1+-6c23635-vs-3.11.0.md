
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.02x faster
- HPT reliability: 53.47%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.66 sec: 1.03x slower                                      |
| tornado_http   | 91.8 ms                                                     | 90.6 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 147 ms: 1.01x faster                                        |
| float          | 54.6 ms                                                     | 58.0 ms: 1.06x slower                                       |
| nbody          | 70.0 ms                                                     | 83.3 ms: 1.19x slower                                       |
| Geometric mean | (ref)                                                       | 1.08x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 93.6 ms: 1.03x slower                                       |
| regex_dna      | 115 ms                                                      | 121 ms: 1.05x slower                                        |
| regex_effbot   | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                       |
| regex_v8       | 13.8 ms                                                     | 15.0 ms: 1.08x slower                                       |
| Geometric mean | (ref)                                                       | 1.06x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.70 ms: 1.33x faster                                       |
| unpickle_pure_python | 152 us                                                      | 141 us: 1.08x faster                                        |
| xml_etree_parse      | 95.9 ms                                                     | 92.7 ms: 1.04x faster                                       |
| pickle_pure_python   | 200 us                                                      | 193 us: 1.03x faster                                        |
| pickle_dict          | 18.5 us                                                     | 18.1 us: 1.02x faster                                       |
| unpickle_list        | 2.55 us                                                     | 2.60 us: 1.02x slower                                       |
| pickle_list          | 2.68 us                                                     | 2.80 us: 1.04x slower                                       |
| pickle               | 6.61 us                                                     | 6.92 us: 1.05x slower                                       |
| xml_etree_iterparse  | 62.6 ms                                                     | 65.7 ms: 1.05x slower                                       |
| xml_etree_process    | 37.1 ms                                                     | 39.8 ms: 1.07x slower                                       |
| xml_etree_generate   | 52.2 ms                                                     | 56.3 ms: 1.08x slower                                       |
| json_loads           | 12.9 us                                                     | 13.9 us: 1.08x slower                                       |
| tomli_loads          | 1.41 sec                                                    | 1.56 sec: 1.10x slower                                      |
| Geometric mean       | (ref)                                                       | 1.00x slower                                                |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.2 ms: 1.02x slower                                       |
| python_startup         | 18.7 ms                                                     | 19.6 ms: 1.05x slower                                       |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.69 ms: 1.06x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 96.8 us: 3.32x faster                                       |
| asyncio_tcp              | 699 ms                                                      | 490 ms: 1.43x faster                                        |
| generators               | 33.8 ms                                                     | 25.4 ms: 1.33x faster                                       |
| json_dumps               | 7.56 ms                                                     | 5.70 ms: 1.33x faster                                       |
| unpack_sequence          | 46.1 ns                                                     | 36.7 ns: 1.26x faster                                       |
| coverage                 | 55.9 ms                                                     | 44.6 ms: 1.25x faster                                       |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.84 sec: 1.15x faster                                      |
| async_tree_none          | 320 ms                                                      | 281 ms: 1.14x faster                                        |
| mdp                      | 1.67 sec                                                    | 1.48 sec: 1.12x faster                                      |
| raytrace                 | 211 ms                                                      | 188 ms: 1.12x faster                                        |
| richards_super           | 37.5 ms                                                     | 33.8 ms: 1.11x faster                                       |
| json                     | 3.25 ms                                                     | 2.94 ms: 1.11x faster                                       |
| sqlglot_parse            | 952 us                                                      | 863 us: 1.10x faster                                        |
| deltablue                | 2.61 ms                                                     | 2.37 ms: 1.10x faster                                       |
| chaos                    | 47.1 ms                                                     | 43.6 ms: 1.08x faster                                       |
| unpickle_pure_python     | 152 us                                                      | 141 us: 1.08x faster                                        |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 468 ms: 1.07x faster                                        |
| sqlite_synth             | 1.68 us                                                     | 1.58 us: 1.07x faster                                       |
| sqlglot_transpile        | 1.16 ms                                                     | 1.09 ms: 1.06x faster                                       |
| crypto_pyaes             | 47.6 ms                                                     | 44.7 ms: 1.06x faster                                       |
| scimark_lu               | 63.5 ms                                                     | 60.3 ms: 1.05x faster                                       |
| comprehensions           | 15.9 us                                                     | 15.1 us: 1.05x faster                                       |
| spectral_norm            | 67.9 ms                                                     | 65.1 ms: 1.04x faster                                       |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.9 ms: 1.04x faster                                       |
| async_tree_memoization   | 371 ms                                                      | 357 ms: 1.04x faster                                        |
| mypy2                    | 229 ms                                                      | 221 ms: 1.04x faster                                        |
| xml_etree_parse          | 95.9 ms                                                     | 92.7 ms: 1.04x faster                                       |
| pickle_pure_python       | 200 us                                                      | 193 us: 1.03x faster                                        |
| hexiom                   | 4.55 ms                                                     | 4.42 ms: 1.03x faster                                       |
| async_tree_io            | 779 ms                                                      | 759 ms: 1.03x faster                                        |
| pickle_dict              | 18.5 us                                                     | 18.1 us: 1.02x faster                                       |
| nqueens                  | 64.9 ms                                                     | 63.8 ms: 1.02x faster                                       |
| tornado_http             | 91.8 ms                                                     | 90.6 ms: 1.01x faster                                       |
| richards                 | 30.6 ms                                                     | 30.2 ms: 1.01x faster                                       |
| pidigits                 | 148 ms                                                      | 147 ms: 1.01x faster                                        |
| meteor_contest           | 74.7 ms                                                     | 74.2 ms: 1.01x faster                                       |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.55 ms: 1.01x faster                                       |
| go                       | 97.3 ms                                                     | 96.8 ms: 1.01x faster                                       |
| pprint_safe_repr         | 512 ms                                                      | 517 ms: 1.01x slower                                        |
| sqlglot_normalize        | 190 ms                                                      | 192 ms: 1.01x slower                                        |
| logging_format           | 7.01 us                                                     | 7.10 us: 1.01x slower                                       |
| python_startup_no_site   | 15.9 ms                                                     | 16.2 ms: 1.02x slower                                       |
| unpickle_list            | 2.55 us                                                     | 2.60 us: 1.02x slower                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                      |
| deepcopy                 | 246 us                                                      | 251 us: 1.02x slower                                        |
| pyflate                  | 304 ms                                                      | 312 ms: 1.02x slower                                        |
| scimark_fft              | 178 ms                                                      | 183 ms: 1.03x slower                                        |
| bench_mp_pool            | 62.5 ms                                                     | 64.3 ms: 1.03x slower                                       |
| regex_compile            | 90.6 ms                                                     | 93.6 ms: 1.03x slower                                       |
| dulwich_log              | 44.5 ms                                                     | 46.0 ms: 1.03x slower                                       |
| docutils                 | 1.60 sec                                                    | 1.66 sec: 1.03x slower                                      |
| gc_traversal             | 1.46 ms                                                     | 1.51 ms: 1.04x slower                                       |
| create_gc_cycles         | 693 us                                                      | 721 us: 1.04x slower                                        |
| pickle_list              | 2.68 us                                                     | 2.80 us: 1.04x slower                                       |
| deepcopy_memo            | 25.2 us                                                     | 26.3 us: 1.05x slower                                       |
| regex_dna                | 115 ms                                                      | 121 ms: 1.05x slower                                        |
| pickle                   | 6.61 us                                                     | 6.92 us: 1.05x slower                                       |
| sqlglot_optimize         | 34.9 ms                                                     | 36.5 ms: 1.05x slower                                       |
| python_startup           | 18.7 ms                                                     | 19.6 ms: 1.05x slower                                       |
| xml_etree_iterparse      | 62.6 ms                                                     | 65.7 ms: 1.05x slower                                       |
| mako                     | 7.26 ms                                                     | 7.69 ms: 1.06x slower                                       |
| float                    | 54.6 ms                                                     | 58.0 ms: 1.06x slower                                       |
| regex_effbot             | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                       |
| coroutines               | 14.6 ms                                                     | 15.6 ms: 1.07x slower                                       |
| xml_etree_process        | 37.1 ms                                                     | 39.8 ms: 1.07x slower                                       |
| xml_etree_generate       | 52.2 ms                                                     | 56.3 ms: 1.08x slower                                       |
| json_loads               | 12.9 us                                                     | 13.9 us: 1.08x slower                                       |
| deepcopy_reduce          | 2.07 us                                                     | 2.24 us: 1.08x slower                                       |
| regex_v8                 | 13.8 ms                                                     | 15.0 ms: 1.08x slower                                       |
| scimark_sor              | 75.6 ms                                                     | 82.9 ms: 1.10x slower                                       |
| tomli_loads              | 1.41 sec                                                    | 1.56 sec: 1.10x slower                                      |
| pathlib                  | 71.4 ms                                                     | 79.6 ms: 1.12x slower                                       |
| nbody                    | 70.0 ms                                                     | 83.3 ms: 1.19x slower                                       |
| telco                    | 3.90 ms                                                     | 4.84 ms: 1.24x slower                                       |
| pycparser                | 691 ms                                                      | 864 ms: 1.25x slower                                        |
| async_generators         | 178 ms                                                      | 248 ms: 1.40x slower                                        |
| Geometric mean           | (ref)                                                       | 1.02x faster                                                |

Benchmark hidden because not significant (5): logging_silent, unpickle, bench_thread_pool, logging_simple, fannkuch
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 53.47% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
