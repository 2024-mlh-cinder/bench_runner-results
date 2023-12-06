
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.08x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                              |
| tornado_http   | 109 ms                                                      | 91.1 ms: 1.20x faster                                               |
| Geometric mean | (ref)                                                       | 1.15x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 52.0 ms: 1.16x faster                                               |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                                |
| nbody          | 69.3 ms                                                     | 81.7 ms: 1.18x slower                                               |
| Geometric mean | (ref)                                                       | 1.02x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 119 ms: 1.11x faster                                                |
| regex_compile  | 103 ms                                                      | 95.7 ms: 1.08x faster                                               |
| regex_effbot   | 1.66 ms                                                     | 1.61 ms: 1.04x faster                                               |
| regex_v8       | 15.0 ms                                                     | 21.4 ms: 1.42x slower                                               |
| Geometric mean | (ref)                                                       | 1.03x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|---------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps          | 8.50 ms                                                     | 5.98 ms: 1.42x faster                                               |
| tomli_loads         | 1.62 sec                                                    | 1.38 sec: 1.18x faster                                              |
| pickle_pure_python  | 257 us                                                      | 227 us: 1.13x faster                                                |
| unpickle            | 9.17 us                                                     | 8.16 us: 1.12x faster                                               |
| xml_etree_parse     | 102 ms                                                      | 92.5 ms: 1.10x faster                                               |
| unpickle_list       | 2.81 us                                                     | 2.71 us: 1.04x faster                                               |
| json_loads          | 14.2 us                                                     | 13.7 us: 1.04x faster                                               |
| xml_etree_process   | 43.4 ms                                                     | 44.8 ms: 1.03x slower                                               |
| pickle              | 6.80 us                                                     | 7.04 us: 1.03x slower                                               |
| xml_etree_iterparse | 63.5 ms                                                     | 68.1 ms: 1.07x slower                                               |
| pickle_list         | 2.59 us                                                     | 2.86 us: 1.10x slower                                               |
| pickle_dict         | 16.9 us                                                     | 18.7 us: 1.10x slower                                               |
| xml_etree_generate  | 54.5 ms                                                     | 62.2 ms: 1.14x slower                                               |
| Geometric mean      | (ref)                                                       | 1.03x faster                                                        |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.6 ms: 1.02x faster                                               |
| python_startup_no_site | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                               |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.39 ms: 1.38x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 107 us: 3.02x faster                                                |
| deltablue                | 4.17 ms                                                     | 2.34 ms: 1.79x faster                                               |
| mypy2                    | 352 ms                                                      | 230 ms: 1.53x faster                                                |
| asyncio_tcp              | 712 ms                                                      | 478 ms: 1.49x faster                                                |
| async_tree_none          | 420 ms                                                      | 290 ms: 1.45x faster                                                |
| json_dumps               | 8.50 ms                                                     | 5.98 ms: 1.42x faster                                               |
| async_tree_io            | 1.07 sec                                                    | 767 ms: 1.39x faster                                                |
| mako                     | 8.80 ms                                                     | 6.39 ms: 1.38x faster                                               |
| async_tree_memoization   | 497 ms                                                      | 368 ms: 1.35x faster                                                |
| richards_super           | 51.7 ms                                                     | 38.4 ms: 1.35x faster                                               |
| crypto_pyaes             | 62.3 ms                                                     | 46.6 ms: 1.34x faster                                               |
| raytrace                 | 271 ms                                                      | 209 ms: 1.30x faster                                                |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 476 ms: 1.28x faster                                                |
| go                       | 136 ms                                                      | 109 ms: 1.25x faster                                                |
| sqlglot_parse            | 1.22 ms                                                     | 979 us: 1.24x faster                                                |
| chaos                    | 58.9 ms                                                     | 48.6 ms: 1.21x faster                                               |
| hexiom                   | 5.52 ms                                                     | 4.58 ms: 1.21x faster                                               |
| tornado_http             | 109 ms                                                      | 91.1 ms: 1.20x faster                                               |
| sqlglot_transpile        | 1.46 ms                                                     | 1.22 ms: 1.20x faster                                               |
| richards                 | 41.2 ms                                                     | 34.5 ms: 1.19x faster                                               |
| mdp                      | 1.71 sec                                                    | 1.44 sec: 1.19x faster                                              |
| tomli_loads              | 1.62 sec                                                    | 1.38 sec: 1.18x faster                                              |
| pyflate                  | 387 ms                                                      | 331 ms: 1.17x faster                                                |
| float                    | 60.2 ms                                                     | 52.0 ms: 1.16x faster                                               |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.34 ms: 1.14x faster                                               |
| scimark_lu               | 85.4 ms                                                     | 75.3 ms: 1.13x faster                                               |
| pickle_pure_python       | 257 us                                                      | 227 us: 1.13x faster                                                |
| unpickle                 | 9.17 us                                                     | 8.16 us: 1.12x faster                                               |
| scimark_monte_carlo      | 55.9 ms                                                     | 50.1 ms: 1.12x faster                                               |
| regex_dna                | 132 ms                                                      | 119 ms: 1.11x faster                                                |
| docutils                 | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                              |
| sqlite_synth             | 1.84 us                                                     | 1.66 us: 1.11x faster                                               |
| xml_etree_parse          | 102 ms                                                      | 92.5 ms: 1.10x faster                                               |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.87 sec: 1.09x faster                                              |
| regex_compile            | 103 ms                                                      | 95.7 ms: 1.08x faster                                               |
| bench_thread_pool        | 946 us                                                      | 877 us: 1.08x faster                                                |
| pycparser                | 868 ms                                                      | 808 ms: 1.07x faster                                                |
| create_gc_cycles         | 782 us                                                      | 730 us: 1.07x faster                                                |
| logging_silent           | 96.4 ns                                                     | 92.1 ns: 1.05x faster                                               |
| comprehensions           | 16.0 us                                                     | 15.3 us: 1.04x faster                                               |
| unpickle_list            | 2.81 us                                                     | 2.71 us: 1.04x faster                                               |
| json_loads               | 14.2 us                                                     | 13.7 us: 1.04x faster                                               |
| regex_effbot             | 1.66 ms                                                     | 1.61 ms: 1.04x faster                                               |
| fannkuch                 | 258 ms                                                      | 249 ms: 1.04x faster                                                |
| pprint_pformat           | 1.21 sec                                                    | 1.17 sec: 1.03x faster                                              |
| dulwich_log              | 47.6 ms                                                     | 46.3 ms: 1.03x faster                                               |
| nqueens                  | 67.0 ms                                                     | 65.4 ms: 1.03x faster                                               |
| python_startup           | 20.0 ms                                                     | 19.6 ms: 1.02x faster                                               |
| pprint_safe_repr         | 589 ms                                                      | 577 ms: 1.02x faster                                                |
| scimark_fft              | 193 ms                                                      | 192 ms: 1.01x faster                                                |
| sqlglot_normalize        | 202 ms                                                      | 207 ms: 1.02x slower                                                |
| spectral_norm            | 78.0 ms                                                     | 80.1 ms: 1.03x slower                                               |
| xml_etree_process        | 43.4 ms                                                     | 44.8 ms: 1.03x slower                                               |
| pathlib                  | 77.4 ms                                                     | 79.8 ms: 1.03x slower                                               |
| pickle                   | 6.80 us                                                     | 7.04 us: 1.03x slower                                               |
| python_startup_no_site   | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                               |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                                |
| deepcopy_memo            | 28.5 us                                                     | 30.2 us: 1.06x slower                                               |
| generators               | 31.6 ms                                                     | 33.5 ms: 1.06x slower                                               |
| meteor_contest           | 72.5 ms                                                     | 77.6 ms: 1.07x slower                                               |
| xml_etree_iterparse      | 63.5 ms                                                     | 68.1 ms: 1.07x slower                                               |
| deepcopy                 | 255 us                                                      | 277 us: 1.08x slower                                                |
| bench_mp_pool            | 60.7 ms                                                     | 66.3 ms: 1.09x slower                                               |
| pickle_list              | 2.59 us                                                     | 2.86 us: 1.10x slower                                               |
| pickle_dict              | 16.9 us                                                     | 18.7 us: 1.10x slower                                               |
| logging_format           | 6.66 us                                                     | 7.41 us: 1.11x slower                                               |
| deepcopy_reduce          | 2.16 us                                                     | 2.41 us: 1.12x slower                                               |
| logging_simple           | 6.20 us                                                     | 6.95 us: 1.12x slower                                               |
| gc_traversal             | 1.34 ms                                                     | 1.51 ms: 1.12x slower                                               |
| xml_etree_generate       | 54.5 ms                                                     | 62.2 ms: 1.14x slower                                               |
| coverage                 | 40.0 ms                                                     | 45.8 ms: 1.14x slower                                               |
| nbody                    | 69.3 ms                                                     | 81.7 ms: 1.18x slower                                               |
| coroutines               | 15.9 ms                                                     | 19.4 ms: 1.22x slower                                               |
| async_generators         | 224 ms                                                      | 274 ms: 1.22x slower                                                |
| telco                    | 3.78 ms                                                     | 4.69 ms: 1.24x slower                                               |
| unpack_sequence          | 37.8 ns                                                     | 48.4 ns: 1.28x slower                                               |
| regex_v8                 | 15.0 ms                                                     | 21.4 ms: 1.42x slower                                               |
| Geometric mean           | (ref)                                                       | 1.08x faster                                                        |

Benchmark hidden because not significant (4): json, unpickle_pure_python, scimark_sor, sqlglot_optimize
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
