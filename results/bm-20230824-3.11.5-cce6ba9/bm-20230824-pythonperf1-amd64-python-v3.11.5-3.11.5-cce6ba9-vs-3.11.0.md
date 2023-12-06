
# Results vs. 3.11.0

- fork: python
- ref: v3.11.5
- machine: windows-amd64
- commit hash: cce6ba9
- commit date: 2023-08-24
- overall geometric mean: 1.00x slower
- HPT reliability: 65.49%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| chameleon      | 5.11 ms                                                     | 5.27 ms: 1.03x slower                                       |
| html5lib       | 37.5 ms                                                     | 38.8 ms: 1.03x slower                                       |
| tornado_http   | 91.8 ms                                                     | 90.6 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (2): 2to3, docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| float          | 54.6 ms                                                     | 53.9 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                |

Benchmark hidden because not significant (2): pidigits, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_effbot   | 1.50 ms                                                     | 1.49 ms: 1.01x faster                                       |
| regex_v8       | 13.8 ms                                                     | 13.8 ms: 1.01x faster                                       |
| regex_compile  | 90.6 ms                                                     | 91.3 ms: 1.01x slower                                       |
| regex_dna      | 115 ms                                                      | 117 ms: 1.02x slower                                        |
| Geometric mean | (ref)                                                       | 1.00x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|---------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle            | 8.09 us                                                     | 7.92 us: 1.02x faster                                       |
| tomli_loads         | 1.41 sec                                                    | 1.41 sec: 1.01x faster                                      |
| xml_etree_generate  | 52.2 ms                                                     | 51.8 ms: 1.01x faster                                       |
| json_loads          | 12.9 us                                                     | 13.0 us: 1.01x slower                                       |
| pickle_pure_python  | 200 us                                                      | 202 us: 1.01x slower                                        |
| json_dumps          | 7.56 ms                                                     | 7.63 ms: 1.01x slower                                       |
| xml_etree_parse     | 95.9 ms                                                     | 97.0 ms: 1.01x slower                                       |
| xml_etree_iterparse | 62.6 ms                                                     | 63.4 ms: 1.01x slower                                       |
| unpickle_list       | 2.55 us                                                     | 2.60 us: 1.02x slower                                       |
| pickle_list         | 2.68 us                                                     | 2.75 us: 1.03x slower                                       |
| pickle              | 6.61 us                                                     | 6.86 us: 1.04x slower                                       |
| Geometric mean      | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (3): unpickle_pure_python, xml_etree_process, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                       |
| python_startup         | 18.7 ms                                                     | 19.4 ms: 1.04x slower                                       |
| Geometric mean         | (ref)                                                       | 1.04x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| django_template | 24.1 ms                                                     | 23.9 ms: 1.01x faster                                       |
| genshi_xml      | 37.3 ms                                                     | 38.0 ms: 1.02x slower                                       |
| mako            | 7.26 ms                                                     | 7.44 ms: 1.02x slower                                       |
| genshi_text     | 17.0 ms                                                     | 17.5 ms: 1.03x slower                                       |
| Geometric mean  | (ref)                                                       | 1.02x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| aiohttp                  | 899 us                                                      | 853 us: 1.05x faster                                        |
| nqueens                  | 64.9 ms                                                     | 62.3 ms: 1.04x faster                                       |
| raytrace                 | 211 ms                                                      | 203 ms: 1.04x faster                                        |
| async_tree_none          | 320 ms                                                      | 311 ms: 1.03x faster                                        |
| coverage                 | 55.9 ms                                                     | 54.3 ms: 1.03x faster                                       |
| sqlglot_transpile        | 1.16 ms                                                     | 1.13 ms: 1.03x faster                                       |
| sqlglot_parse            | 952 us                                                      | 928 us: 1.03x faster                                        |
| mdp                      | 1.67 sec                                                    | 1.63 sec: 1.03x faster                                      |
| pathlib                  | 71.4 ms                                                     | 69.7 ms: 1.02x faster                                       |
| unpickle                 | 8.09 us                                                     | 7.92 us: 1.02x faster                                       |
| dulwich_log              | 44.5 ms                                                     | 43.6 ms: 1.02x faster                                       |
| pylint                   | 326 ms                                                      | 320 ms: 1.02x faster                                        |
| deepcopy                 | 246 us                                                      | 241 us: 1.02x faster                                        |
| deepcopy_memo            | 25.2 us                                                     | 24.7 us: 1.02x faster                                       |
| bench_mp_pool            | 62.5 ms                                                     | 61.5 ms: 1.02x faster                                       |
| richards                 | 30.6 ms                                                     | 30.1 ms: 1.02x faster                                       |
| tornado_http             | 91.8 ms                                                     | 90.6 ms: 1.01x faster                                       |
| scimark_lu               | 63.5 ms                                                     | 62.7 ms: 1.01x faster                                       |
| float                    | 54.6 ms                                                     | 53.9 ms: 1.01x faster                                       |
| django_template          | 24.1 ms                                                     | 23.9 ms: 1.01x faster                                       |
| sqlglot_optimize         | 34.9 ms                                                     | 34.5 ms: 1.01x faster                                       |
| coroutines               | 14.6 ms                                                     | 14.5 ms: 1.01x faster                                       |
| logging_simple           | 6.61 us                                                     | 6.56 us: 1.01x faster                                       |
| regex_effbot             | 1.50 ms                                                     | 1.49 ms: 1.01x faster                                       |
| tomli_loads              | 1.41 sec                                                    | 1.41 sec: 1.01x faster                                      |
| xml_etree_generate       | 52.2 ms                                                     | 51.8 ms: 1.01x faster                                       |
| spectral_norm            | 67.9 ms                                                     | 67.5 ms: 1.01x faster                                       |
| regex_v8                 | 13.8 ms                                                     | 13.8 ms: 1.01x faster                                       |
| pyflate                  | 304 ms                                                      | 302 ms: 1.01x faster                                        |
| thrift                   | 491 us                                                      | 488 us: 1.01x faster                                        |
| flaskblogging            | 2.04 sec                                                    | 2.03 sec: 1.00x faster                                      |
| json_loads               | 12.9 us                                                     | 13.0 us: 1.01x slower                                       |
| logging_format           | 7.01 us                                                     | 7.06 us: 1.01x slower                                       |
| regex_compile            | 90.6 ms                                                     | 91.3 ms: 1.01x slower                                       |
| pickle_pure_python       | 200 us                                                      | 202 us: 1.01x slower                                        |
| sympy_str                | 182 ms                                                      | 183 ms: 1.01x slower                                        |
| json_dumps               | 7.56 ms                                                     | 7.63 ms: 1.01x slower                                       |
| crypto_pyaes             | 47.6 ms                                                     | 48.1 ms: 1.01x slower                                       |
| xml_etree_parse          | 95.9 ms                                                     | 97.0 ms: 1.01x slower                                       |
| sympy_expand             | 295 ms                                                      | 299 ms: 1.01x slower                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.05 sec: 1.01x slower                                      |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.4 ms: 1.01x slower                                       |
| scimark_sor              | 75.6 ms                                                     | 76.5 ms: 1.01x slower                                       |
| async_generators         | 178 ms                                                      | 180 ms: 1.01x slower                                        |
| richards_super           | 37.5 ms                                                     | 38.0 ms: 1.01x slower                                       |
| gc_traversal             | 1.46 ms                                                     | 1.48 ms: 1.01x slower                                       |
| go                       | 97.3 ms                                                     | 98.8 ms: 1.01x slower                                       |
| telco                    | 3.90 ms                                                     | 3.96 ms: 1.02x slower                                       |
| regex_dna                | 115 ms                                                      | 117 ms: 1.02x slower                                        |
| typing_runtime_protocols | 322 us                                                      | 327 us: 1.02x slower                                        |
| scimark_fft              | 178 ms                                                      | 181 ms: 1.02x slower                                        |
| genshi_xml               | 37.3 ms                                                     | 38.0 ms: 1.02x slower                                       |
| sqlalchemy_imperative    | 10.2 ms                                                     | 10.4 ms: 1.02x slower                                       |
| unpickle_list            | 2.55 us                                                     | 2.60 us: 1.02x slower                                       |
| sqlite_synth             | 1.68 us                                                     | 1.72 us: 1.02x slower                                       |
| create_gc_cycles         | 693 us                                                      | 709 us: 1.02x slower                                        |
| mako                     | 7.26 ms                                                     | 7.44 ms: 1.02x slower                                       |
| meteor_contest           | 74.7 ms                                                     | 76.8 ms: 1.03x slower                                       |
| pickle_list              | 2.68 us                                                     | 2.75 us: 1.03x slower                                       |
| sqlalchemy_declarative   | 81.5 ms                                                     | 83.8 ms: 1.03x slower                                       |
| chameleon                | 5.11 ms                                                     | 5.27 ms: 1.03x slower                                       |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 516 ms: 1.03x slower                                        |
| genshi_text              | 17.0 ms                                                     | 17.5 ms: 1.03x slower                                       |
| html5lib                 | 37.5 ms                                                     | 38.8 ms: 1.03x slower                                       |
| pickle                   | 6.61 us                                                     | 6.86 us: 1.04x slower                                       |
| python_startup_no_site   | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                       |
| python_startup           | 18.7 ms                                                     | 19.4 ms: 1.04x slower                                       |
| scimark_monte_carlo      | 44.6 ms                                                     | 46.5 ms: 1.04x slower                                       |
| chaos                    | 47.1 ms                                                     | 49.5 ms: 1.05x slower                                       |
| fannkuch                 | 252 ms                                                      | 268 ms: 1.06x slower                                        |
| mypy2                    | 229 ms                                                      | 275 ms: 1.20x slower                                        |
| Geometric mean           | (ref)                                                       | 1.00x slower                                                |

Benchmark hidden because not significant (27): json, asyncio_tcp_ssl, unpack_sequence, asyncio_tcp, deepcopy_reduce, unpickle_pure_python, xml_etree_process, sympy_integrate, pidigits, 2to3, sqlglot_normalize, hexiom, pickle_dict, deltablue, comprehensions, generators, nbody, docutils, async_tree_io, scimark_sparse_mat_mult, dask, pprint_safe_repr, logging_silent, sympy_sum, pycparser, async_tree_memoization, bench_thread_pool


# HPT report

- Reliability score: 65.49% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
