
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 07fb485
- commit date: 2023-10-11
- overall geometric mean: 1.06x faster
- HPT reliability: 98.12%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.71 sec: 1.11x faster                                             |
| tornado_http   | 109 ms                                                      | 91.9 ms: 1.19x faster                                              |
| Geometric mean | (ref)                                                       | 1.15x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.7 ms: 1.10x faster                                              |
| pidigits       | 145 ms                                                      | 150 ms: 1.04x slower                                               |
| nbody          | 69.3 ms                                                     | 86.4 ms: 1.25x slower                                              |
| Geometric mean | (ref)                                                       | 1.05x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 121 ms: 1.09x faster                                               |
| regex_compile  | 103 ms                                                      | 99.0 ms: 1.05x faster                                              |
| regex_effbot   | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                              |
| regex_v8       | 15.0 ms                                                     | 16.9 ms: 1.12x slower                                              |
| Geometric mean | (ref)                                                       | 1.01x faster                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|---------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps          | 8.50 ms                                                     | 6.00 ms: 1.42x faster                                              |
| pickle_pure_python  | 257 us                                                      | 227 us: 1.13x faster                                               |
| unpickle            | 9.17 us                                                     | 8.23 us: 1.12x faster                                              |
| xml_etree_parse     | 102 ms                                                      | 92.9 ms: 1.10x faster                                              |
| tomli_loads         | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                             |
| unpickle_list       | 2.81 us                                                     | 2.71 us: 1.04x faster                                              |
| json_loads          | 14.2 us                                                     | 13.9 us: 1.02x faster                                              |
| xml_etree_process   | 43.4 ms                                                     | 45.2 ms: 1.04x slower                                              |
| xml_etree_iterparse | 63.5 ms                                                     | 67.4 ms: 1.06x slower                                              |
| pickle              | 6.80 us                                                     | 7.34 us: 1.08x slower                                              |
| pickle_list         | 2.59 us                                                     | 2.82 us: 1.09x slower                                              |
| pickle_dict         | 16.9 us                                                     | 18.9 us: 1.12x slower                                              |
| xml_etree_generate  | 54.5 ms                                                     | 62.8 ms: 1.15x slower                                              |
| Geometric mean      | (ref)                                                       | 1.02x faster                                                       |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.4 ms: 1.03x faster                                              |
| python_startup_no_site | 15.5 ms                                                     | 15.9 ms: 1.03x slower                                              |
| Geometric mean         | (ref)                                                       | 1.00x faster                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.91 ms: 1.27x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 101 us: 3.20x faster                                               |
| mypy2                    | 352 ms                                                      | 230 ms: 1.53x faster                                               |
| asyncio_tcp              | 712 ms                                                      | 488 ms: 1.46x faster                                               |
| deltablue                | 4.17 ms                                                     | 2.87 ms: 1.45x faster                                              |
| async_tree_none          | 420 ms                                                      | 289 ms: 1.45x faster                                               |
| json_dumps               | 8.50 ms                                                     | 6.00 ms: 1.42x faster                                              |
| async_tree_io            | 1.07 sec                                                    | 773 ms: 1.38x faster                                               |
| async_tree_memoization   | 497 ms                                                      | 368 ms: 1.35x faster                                               |
| richards_super           | 51.7 ms                                                     | 38.6 ms: 1.34x faster                                              |
| raytrace                 | 271 ms                                                      | 211 ms: 1.29x faster                                               |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 477 ms: 1.28x faster                                               |
| mako                     | 8.80 ms                                                     | 6.91 ms: 1.27x faster                                              |
| sqlglot_parse            | 1.22 ms                                                     | 984 us: 1.24x faster                                               |
| crypto_pyaes             | 62.3 ms                                                     | 50.9 ms: 1.22x faster                                              |
| go                       | 136 ms                                                      | 113 ms: 1.21x faster                                               |
| sqlglot_transpile        | 1.46 ms                                                     | 1.23 ms: 1.19x faster                                              |
| tornado_http             | 109 ms                                                      | 91.9 ms: 1.19x faster                                              |
| richards                 | 41.2 ms                                                     | 35.0 ms: 1.18x faster                                              |
| chaos                    | 58.9 ms                                                     | 50.4 ms: 1.17x faster                                              |
| pickle_pure_python       | 257 us                                                      | 227 us: 1.13x faster                                               |
| pycparser                | 868 ms                                                      | 771 ms: 1.13x faster                                               |
| mdp                      | 1.71 sec                                                    | 1.53 sec: 1.12x faster                                             |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.82 sec: 1.12x faster                                             |
| unpickle                 | 9.17 us                                                     | 8.23 us: 1.12x faster                                              |
| scimark_lu               | 85.4 ms                                                     | 76.7 ms: 1.11x faster                                              |
| docutils                 | 1.89 sec                                                    | 1.71 sec: 1.11x faster                                             |
| float                    | 60.2 ms                                                     | 54.7 ms: 1.10x faster                                              |
| pyflate                  | 387 ms                                                      | 352 ms: 1.10x faster                                               |
| xml_etree_parse          | 102 ms                                                      | 92.9 ms: 1.10x faster                                              |
| regex_dna                | 132 ms                                                      | 121 ms: 1.09x faster                                               |
| tomli_loads              | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                             |
| scimark_monte_carlo      | 55.9 ms                                                     | 51.5 ms: 1.09x faster                                              |
| create_gc_cycles         | 782 us                                                      | 722 us: 1.08x faster                                               |
| bench_thread_pool        | 946 us                                                      | 881 us: 1.07x faster                                               |
| sqlite_synth             | 1.84 us                                                     | 1.73 us: 1.07x faster                                              |
| hexiom                   | 5.52 ms                                                     | 5.21 ms: 1.06x faster                                              |
| logging_silent           | 96.4 ns                                                     | 91.1 ns: 1.06x faster                                              |
| regex_compile            | 103 ms                                                      | 99.0 ms: 1.05x faster                                              |
| unpickle_list            | 2.81 us                                                     | 2.71 us: 1.04x faster                                              |
| json                     | 3.05 ms                                                     | 2.94 ms: 1.04x faster                                              |
| regex_effbot             | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                              |
| dulwich_log              | 47.6 ms                                                     | 46.1 ms: 1.03x faster                                              |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.58 ms: 1.03x faster                                              |
| python_startup           | 20.0 ms                                                     | 19.4 ms: 1.03x faster                                              |
| json_loads               | 14.2 us                                                     | 13.9 us: 1.02x faster                                              |
| nqueens                  | 67.0 ms                                                     | 67.8 ms: 1.01x slower                                              |
| pprint_pformat           | 1.21 sec                                                    | 1.22 sec: 1.01x slower                                             |
| pprint_safe_repr         | 589 ms                                                      | 599 ms: 1.02x slower                                               |
| pathlib                  | 77.4 ms                                                     | 78.9 ms: 1.02x slower                                              |
| python_startup_no_site   | 15.5 ms                                                     | 15.9 ms: 1.03x slower                                              |
| pidigits                 | 145 ms                                                      | 150 ms: 1.04x slower                                               |
| spectral_norm            | 78.0 ms                                                     | 80.9 ms: 1.04x slower                                              |
| sqlglot_normalize        | 202 ms                                                      | 210 ms: 1.04x slower                                               |
| xml_etree_process        | 43.4 ms                                                     | 45.2 ms: 1.04x slower                                              |
| fannkuch                 | 258 ms                                                      | 269 ms: 1.04x slower                                               |
| comprehensions           | 16.0 us                                                     | 16.8 us: 1.05x slower                                              |
| xml_etree_iterparse      | 63.5 ms                                                     | 67.4 ms: 1.06x slower                                              |
| scimark_fft              | 193 ms                                                      | 205 ms: 1.06x slower                                               |
| pickle                   | 6.80 us                                                     | 7.34 us: 1.08x slower                                              |
| deepcopy                 | 255 us                                                      | 276 us: 1.08x slower                                               |
| bench_mp_pool            | 60.7 ms                                                     | 65.8 ms: 1.08x slower                                              |
| generators               | 31.6 ms                                                     | 34.2 ms: 1.08x slower                                              |
| pickle_list              | 2.59 us                                                     | 2.82 us: 1.09x slower                                              |
| meteor_contest           | 72.5 ms                                                     | 80.1 ms: 1.10x slower                                              |
| deepcopy_reduce          | 2.16 us                                                     | 2.39 us: 1.11x slower                                              |
| pickle_dict              | 16.9 us                                                     | 18.9 us: 1.12x slower                                              |
| gc_traversal             | 1.34 ms                                                     | 1.50 ms: 1.12x slower                                              |
| deepcopy_memo            | 28.5 us                                                     | 31.9 us: 1.12x slower                                              |
| regex_v8                 | 15.0 ms                                                     | 16.9 ms: 1.12x slower                                              |
| logging_format           | 6.66 us                                                     | 7.55 us: 1.13x slower                                              |
| logging_simple           | 6.20 us                                                     | 7.09 us: 1.14x slower                                              |
| xml_etree_generate       | 54.5 ms                                                     | 62.8 ms: 1.15x slower                                              |
| coverage                 | 40.0 ms                                                     | 47.7 ms: 1.19x slower                                              |
| coroutines               | 15.9 ms                                                     | 19.1 ms: 1.20x slower                                              |
| async_generators         | 224 ms                                                      | 269 ms: 1.20x slower                                               |
| nbody                    | 69.3 ms                                                     | 86.4 ms: 1.25x slower                                              |
| telco                    | 3.78 ms                                                     | 4.83 ms: 1.28x slower                                              |
| unpack_sequence          | 37.8 ns                                                     | 48.6 ns: 1.29x slower                                              |
| Geometric mean           | (ref)                                                       | 1.06x faster                                                       |

Benchmark hidden because not significant (3): scimark_sor, sqlglot_optimize, unpickle_pure_python
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 98.12% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
