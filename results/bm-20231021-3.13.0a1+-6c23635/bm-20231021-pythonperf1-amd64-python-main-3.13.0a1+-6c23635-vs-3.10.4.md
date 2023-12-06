
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.14x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.66 sec: 1.14x faster                                      |
| tornado_http   | 109 ms                                                      | 90.6 ms: 1.20x faster                                       |
| Geometric mean | (ref)                                                       | 1.17x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 58.0 ms: 1.04x faster                                       |
| pidigits       | 145 ms                                                      | 147 ms: 1.01x slower                                        |
| nbody          | 69.3 ms                                                     | 83.3 ms: 1.20x slower                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 93.6 ms: 1.11x faster                                       |
| regex_dna      | 132 ms                                                      | 121 ms: 1.09x faster                                        |
| regex_effbot   | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.70 ms: 1.49x faster                                       |
| pickle_pure_python   | 257 us                                                      | 193 us: 1.33x faster                                        |
| unpickle_pure_python | 171 us                                                      | 141 us: 1.22x faster                                        |
| unpickle             | 9.17 us                                                     | 8.05 us: 1.14x faster                                       |
| xml_etree_parse      | 102 ms                                                      | 92.7 ms: 1.10x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 39.8 ms: 1.09x faster                                       |
| unpickle_list        | 2.81 us                                                     | 2.60 us: 1.08x faster                                       |
| tomli_loads          | 1.62 sec                                                    | 1.56 sec: 1.04x faster                                      |
| json_loads           | 14.2 us                                                     | 13.9 us: 1.02x faster                                       |
| pickle               | 6.80 us                                                     | 6.92 us: 1.02x slower                                       |
| xml_etree_generate   | 54.5 ms                                                     | 56.3 ms: 1.03x slower                                       |
| xml_etree_iterparse  | 63.5 ms                                                     | 65.7 ms: 1.03x slower                                       |
| pickle_dict          | 16.9 us                                                     | 18.1 us: 1.07x slower                                       |
| pickle_list          | 2.59 us                                                     | 2.80 us: 1.08x slower                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.6 ms: 1.02x faster                                       |
| python_startup_no_site | 15.5 ms                                                     | 16.2 ms: 1.04x slower                                       |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.69 ms: 1.14x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 96.8 us: 3.35x faster                                       |
| deltablue                | 4.17 ms                                                     | 2.37 ms: 1.76x faster                                       |
| mypy2                    | 352 ms                                                      | 221 ms: 1.59x faster                                        |
| richards_super           | 51.7 ms                                                     | 33.8 ms: 1.53x faster                                       |
| async_tree_none          | 420 ms                                                      | 281 ms: 1.49x faster                                        |
| json_dumps               | 8.50 ms                                                     | 5.70 ms: 1.49x faster                                       |
| asyncio_tcp              | 712 ms                                                      | 490 ms: 1.45x faster                                        |
| raytrace                 | 271 ms                                                      | 188 ms: 1.44x faster                                        |
| scimark_lu               | 85.4 ms                                                     | 60.3 ms: 1.42x faster                                       |
| sqlglot_parse            | 1.22 ms                                                     | 863 us: 1.41x faster                                        |
| go                       | 136 ms                                                      | 96.8 ms: 1.41x faster                                       |
| async_tree_io            | 1.07 sec                                                    | 759 ms: 1.40x faster                                        |
| async_tree_memoization   | 497 ms                                                      | 357 ms: 1.39x faster                                        |
| crypto_pyaes             | 62.3 ms                                                     | 44.7 ms: 1.39x faster                                       |
| logging_silent           | 96.4 ns                                                     | 69.4 ns: 1.39x faster                                       |
| richards                 | 41.2 ms                                                     | 30.2 ms: 1.36x faster                                       |
| chaos                    | 58.9 ms                                                     | 43.6 ms: 1.35x faster                                       |
| sqlglot_transpile        | 1.46 ms                                                     | 1.09 ms: 1.34x faster                                       |
| pickle_pure_python       | 257 us                                                      | 193 us: 1.33x faster                                        |
| scimark_monte_carlo      | 55.9 ms                                                     | 42.9 ms: 1.30x faster                                       |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 468 ms: 1.30x faster                                        |
| scimark_sor              | 105 ms                                                      | 82.9 ms: 1.26x faster                                       |
| hexiom                   | 5.52 ms                                                     | 4.42 ms: 1.25x faster                                       |
| generators               | 31.6 ms                                                     | 25.4 ms: 1.25x faster                                       |
| pyflate                  | 387 ms                                                      | 312 ms: 1.24x faster                                        |
| unpickle_pure_python     | 171 us                                                      | 141 us: 1.22x faster                                        |
| tornado_http             | 109 ms                                                      | 90.6 ms: 1.20x faster                                       |
| spectral_norm            | 78.0 ms                                                     | 65.1 ms: 1.20x faster                                       |
| sqlite_synth             | 1.84 us                                                     | 1.58 us: 1.17x faster                                       |
| mdp                      | 1.71 sec                                                    | 1.48 sec: 1.15x faster                                      |
| mako                     | 8.80 ms                                                     | 7.69 ms: 1.14x faster                                       |
| docutils                 | 1.89 sec                                                    | 1.66 sec: 1.14x faster                                      |
| pprint_safe_repr         | 589 ms                                                      | 517 ms: 1.14x faster                                        |
| unpickle                 | 9.17 us                                                     | 8.05 us: 1.14x faster                                       |
| pprint_pformat           | 1.21 sec                                                    | 1.06 sec: 1.14x faster                                      |
| bench_thread_pool        | 946 us                                                      | 849 us: 1.11x faster                                        |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.84 sec: 1.11x faster                                      |
| regex_compile            | 103 ms                                                      | 93.6 ms: 1.11x faster                                       |
| xml_etree_parse          | 102 ms                                                      | 92.7 ms: 1.10x faster                                       |
| regex_dna                | 132 ms                                                      | 121 ms: 1.09x faster                                        |
| xml_etree_process        | 43.4 ms                                                     | 39.8 ms: 1.09x faster                                       |
| create_gc_cycles         | 782 us                                                      | 721 us: 1.08x faster                                        |
| deepcopy_memo            | 28.5 us                                                     | 26.3 us: 1.08x faster                                       |
| unpickle_list            | 2.81 us                                                     | 2.60 us: 1.08x faster                                       |
| sqlglot_optimize         | 39.0 ms                                                     | 36.5 ms: 1.07x faster                                       |
| scimark_fft              | 193 ms                                                      | 183 ms: 1.05x faster                                        |
| comprehensions           | 16.0 us                                                     | 15.1 us: 1.05x faster                                       |
| nqueens                  | 67.0 ms                                                     | 63.8 ms: 1.05x faster                                       |
| sqlglot_normalize        | 202 ms                                                      | 192 ms: 1.05x faster                                        |
| regex_effbot             | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                       |
| tomli_loads              | 1.62 sec                                                    | 1.56 sec: 1.04x faster                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.55 ms: 1.04x faster                                       |
| json                     | 3.05 ms                                                     | 2.94 ms: 1.04x faster                                       |
| float                    | 60.2 ms                                                     | 58.0 ms: 1.04x faster                                       |
| dulwich_log              | 47.6 ms                                                     | 46.0 ms: 1.04x faster                                       |
| unpack_sequence          | 37.8 ns                                                     | 36.7 ns: 1.03x faster                                       |
| coroutines               | 15.9 ms                                                     | 15.6 ms: 1.02x faster                                       |
| python_startup           | 20.0 ms                                                     | 19.6 ms: 1.02x faster                                       |
| fannkuch                 | 258 ms                                                      | 253 ms: 1.02x faster                                        |
| json_loads               | 14.2 us                                                     | 13.9 us: 1.02x faster                                       |
| deepcopy                 | 255 us                                                      | 251 us: 1.02x faster                                        |
| pidigits                 | 145 ms                                                      | 147 ms: 1.01x slower                                        |
| pickle                   | 6.80 us                                                     | 6.92 us: 1.02x slower                                       |
| meteor_contest           | 72.5 ms                                                     | 74.2 ms: 1.02x slower                                       |
| pathlib                  | 77.4 ms                                                     | 79.6 ms: 1.03x slower                                       |
| xml_etree_generate       | 54.5 ms                                                     | 56.3 ms: 1.03x slower                                       |
| xml_etree_iterparse      | 63.5 ms                                                     | 65.7 ms: 1.03x slower                                       |
| deepcopy_reduce          | 2.16 us                                                     | 2.24 us: 1.04x slower                                       |
| python_startup_no_site   | 15.5 ms                                                     | 16.2 ms: 1.04x slower                                       |
| bench_mp_pool            | 60.7 ms                                                     | 64.3 ms: 1.06x slower                                       |
| logging_format           | 6.66 us                                                     | 7.10 us: 1.07x slower                                       |
| logging_simple           | 6.20 us                                                     | 6.63 us: 1.07x slower                                       |
| pickle_dict              | 16.9 us                                                     | 18.1 us: 1.07x slower                                       |
| pickle_list              | 2.59 us                                                     | 2.80 us: 1.08x slower                                       |
| async_generators         | 224 ms                                                      | 248 ms: 1.11x slower                                        |
| coverage                 | 40.0 ms                                                     | 44.6 ms: 1.11x slower                                       |
| gc_traversal             | 1.34 ms                                                     | 1.51 ms: 1.13x slower                                       |
| nbody                    | 69.3 ms                                                     | 83.3 ms: 1.20x slower                                       |
| telco                    | 3.78 ms                                                     | 4.84 ms: 1.28x slower                                       |
| Geometric mean           | (ref)                                                       | 1.14x faster                                                |

Benchmark hidden because not significant (2): pycparser, regex_v8
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.06x
