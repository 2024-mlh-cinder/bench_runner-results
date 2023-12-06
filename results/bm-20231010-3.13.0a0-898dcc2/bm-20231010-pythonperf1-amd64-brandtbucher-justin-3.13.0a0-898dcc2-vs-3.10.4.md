
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 898dcc2
- commit date: 2023-10-10
- overall geometric mean: 1.07x faster
- HPT reliability: 99.84%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                             |
| tornado_http   | 109 ms                                                      | 91.2 ms: 1.20x faster                                              |
| Geometric mean | (ref)                                                       | 1.15x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.6 ms: 1.10x faster                                              |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                               |
| nbody          | 69.3 ms                                                     | 84.9 ms: 1.22x slower                                              |
| Geometric mean | (ref)                                                       | 1.05x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 119 ms: 1.11x faster                                               |
| regex_compile  | 103 ms                                                      | 98.1 ms: 1.05x faster                                              |
| regex_effbot   | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                              |
| regex_v8       | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                              |
| Geometric mean | (ref)                                                       | 1.05x faster                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 6.06 ms: 1.40x faster                                              |
| tomli_loads          | 1.62 sec                                                    | 1.40 sec: 1.16x faster                                             |
| pickle_pure_python   | 257 us                                                      | 225 us: 1.14x faster                                               |
| unpickle             | 9.17 us                                                     | 8.17 us: 1.12x faster                                              |
| xml_etree_parse      | 102 ms                                                      | 93.2 ms: 1.09x faster                                              |
| unpickle_list        | 2.81 us                                                     | 2.69 us: 1.05x faster                                              |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                              |
| unpickle_pure_python | 171 us                                                      | 175 us: 1.02x slower                                               |
| pickle               | 6.80 us                                                     | 7.11 us: 1.05x slower                                              |
| xml_etree_process    | 43.4 ms                                                     | 45.9 ms: 1.06x slower                                              |
| pickle_dict          | 16.9 us                                                     | 18.3 us: 1.08x slower                                              |
| xml_etree_iterparse  | 63.5 ms                                                     | 70.2 ms: 1.11x slower                                              |
| pickle_list          | 2.59 us                                                     | 2.94 us: 1.13x slower                                              |
| xml_etree_generate   | 54.5 ms                                                     | 64.1 ms: 1.18x slower                                              |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 16.6 ms: 1.07x slower                                              |
| Geometric mean         | (ref)                                                       | 1.04x slower                                                       |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.72 ms: 1.31x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 101 us: 3.20x faster                                               |
| deltablue                | 4.17 ms                                                     | 2.47 ms: 1.69x faster                                              |
| mypy2                    | 352 ms                                                      | 229 ms: 1.54x faster                                               |
| asyncio_tcp              | 712 ms                                                      | 471 ms: 1.51x faster                                               |
| async_tree_none          | 420 ms                                                      | 288 ms: 1.46x faster                                               |
| json_dumps               | 8.50 ms                                                     | 6.06 ms: 1.40x faster                                              |
| async_tree_io            | 1.07 sec                                                    | 771 ms: 1.38x faster                                               |
| async_tree_memoization   | 497 ms                                                      | 368 ms: 1.35x faster                                               |
| richards_super           | 51.7 ms                                                     | 38.6 ms: 1.34x faster                                              |
| mako                     | 8.80 ms                                                     | 6.72 ms: 1.31x faster                                              |
| crypto_pyaes             | 62.3 ms                                                     | 48.3 ms: 1.29x faster                                              |
| raytrace                 | 271 ms                                                      | 211 ms: 1.29x faster                                               |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 477 ms: 1.28x faster                                               |
| sqlglot_parse            | 1.22 ms                                                     | 976 us: 1.25x faster                                               |
| go                       | 136 ms                                                      | 110 ms: 1.24x faster                                               |
| chaos                    | 58.9 ms                                                     | 48.9 ms: 1.20x faster                                              |
| sqlglot_transpile        | 1.46 ms                                                     | 1.22 ms: 1.20x faster                                              |
| tornado_http             | 109 ms                                                      | 91.2 ms: 1.20x faster                                              |
| mdp                      | 1.71 sec                                                    | 1.44 sec: 1.19x faster                                             |
| richards                 | 41.2 ms                                                     | 34.8 ms: 1.18x faster                                              |
| tomli_loads              | 1.62 sec                                                    | 1.40 sec: 1.16x faster                                             |
| hexiom                   | 5.52 ms                                                     | 4.83 ms: 1.14x faster                                              |
| pickle_pure_python       | 257 us                                                      | 225 us: 1.14x faster                                               |
| scimark_lu               | 85.4 ms                                                     | 75.0 ms: 1.14x faster                                              |
| pyflate                  | 387 ms                                                      | 342 ms: 1.13x faster                                               |
| unpickle                 | 9.17 us                                                     | 8.17 us: 1.12x faster                                              |
| pycparser                | 868 ms                                                      | 776 ms: 1.12x faster                                               |
| docutils                 | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                             |
| regex_dna                | 132 ms                                                      | 119 ms: 1.11x faster                                               |
| scimark_monte_carlo      | 55.9 ms                                                     | 50.4 ms: 1.11x faster                                              |
| float                    | 60.2 ms                                                     | 54.6 ms: 1.10x faster                                              |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.42 ms: 1.10x faster                                              |
| xml_etree_parse          | 102 ms                                                      | 93.2 ms: 1.09x faster                                              |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.88 sec: 1.08x faster                                             |
| sqlite_synth             | 1.84 us                                                     | 1.70 us: 1.08x faster                                              |
| bench_thread_pool        | 946 us                                                      | 880 us: 1.08x faster                                               |
| create_gc_cycles         | 782 us                                                      | 729 us: 1.07x faster                                               |
| logging_silent           | 96.4 ns                                                     | 90.9 ns: 1.06x faster                                              |
| regex_compile            | 103 ms                                                      | 98.1 ms: 1.05x faster                                              |
| regex_effbot             | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                              |
| unpickle_list            | 2.81 us                                                     | 2.69 us: 1.05x faster                                              |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                              |
| dulwich_log              | 47.6 ms                                                     | 45.7 ms: 1.04x faster                                              |
| scimark_sor              | 105 ms                                                      | 103 ms: 1.02x faster                                               |
| comprehensions           | 16.0 us                                                     | 15.8 us: 1.01x faster                                              |
| pprint_safe_repr         | 589 ms                                                      | 582 ms: 1.01x faster                                               |
| nqueens                  | 67.0 ms                                                     | 66.4 ms: 1.01x faster                                              |
| pprint_pformat           | 1.21 sec                                                    | 1.20 sec: 1.01x faster                                             |
| sqlglot_optimize         | 39.0 ms                                                     | 38.7 ms: 1.01x faster                                              |
| regex_v8                 | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                              |
| fannkuch                 | 258 ms                                                      | 261 ms: 1.01x slower                                               |
| pathlib                  | 77.4 ms                                                     | 78.4 ms: 1.01x slower                                              |
| unpickle_pure_python     | 171 us                                                      | 175 us: 1.02x slower                                               |
| sqlglot_normalize        | 202 ms                                                      | 208 ms: 1.03x slower                                               |
| scimark_fft              | 193 ms                                                      | 200 ms: 1.04x slower                                               |
| spectral_norm            | 78.0 ms                                                     | 80.9 ms: 1.04x slower                                              |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                               |
| pickle                   | 6.80 us                                                     | 7.11 us: 1.05x slower                                              |
| xml_etree_process        | 43.4 ms                                                     | 45.9 ms: 1.06x slower                                              |
| python_startup_no_site   | 15.5 ms                                                     | 16.6 ms: 1.07x slower                                              |
| generators               | 31.6 ms                                                     | 34.0 ms: 1.08x slower                                              |
| pickle_dict              | 16.9 us                                                     | 18.3 us: 1.08x slower                                              |
| meteor_contest           | 72.5 ms                                                     | 79.3 ms: 1.09x slower                                              |
| deepcopy                 | 255 us                                                      | 279 us: 1.09x slower                                               |
| xml_etree_iterparse      | 63.5 ms                                                     | 70.2 ms: 1.11x slower                                              |
| gc_traversal             | 1.34 ms                                                     | 1.49 ms: 1.11x slower                                              |
| deepcopy_reduce          | 2.16 us                                                     | 2.39 us: 1.11x slower                                              |
| logging_format           | 6.66 us                                                     | 7.42 us: 1.11x slower                                              |
| deepcopy_memo            | 28.5 us                                                     | 31.8 us: 1.12x slower                                              |
| logging_simple           | 6.20 us                                                     | 6.98 us: 1.13x slower                                              |
| pickle_list              | 2.59 us                                                     | 2.94 us: 1.13x slower                                              |
| bench_mp_pool            | 60.7 ms                                                     | 69.3 ms: 1.14x slower                                              |
| coverage                 | 40.0 ms                                                     | 46.3 ms: 1.16x slower                                              |
| xml_etree_generate       | 54.5 ms                                                     | 64.1 ms: 1.18x slower                                              |
| coroutines               | 15.9 ms                                                     | 18.9 ms: 1.19x slower                                              |
| async_generators         | 224 ms                                                      | 269 ms: 1.20x slower                                               |
| nbody                    | 69.3 ms                                                     | 84.9 ms: 1.22x slower                                              |
| telco                    | 3.78 ms                                                     | 4.77 ms: 1.26x slower                                              |
| unpack_sequence          | 37.8 ns                                                     | 48.4 ns: 1.28x slower                                              |
| Geometric mean           | (ref)                                                       | 1.07x faster                                                       |

Benchmark hidden because not significant (2): json, python_startup
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.84% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.00x
