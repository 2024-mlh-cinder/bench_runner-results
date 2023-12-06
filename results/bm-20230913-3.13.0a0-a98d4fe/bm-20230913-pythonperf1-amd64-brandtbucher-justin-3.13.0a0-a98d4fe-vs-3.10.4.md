
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.06x faster
- HPT reliability: 99.07%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                             |
| tornado_http   | 109 ms                                                      | 91.7 ms: 1.19x faster                                              |
| Geometric mean | (ref)                                                       | 1.15x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 59.1 ms: 1.17x faster                                              |
| pidigits       | 145 ms                                                      | 152 ms: 1.05x slower                                               |
| float          | 60.2 ms                                                     | 65.9 ms: 1.09x slower                                              |
| Geometric mean | (ref)                                                       | 1.01x faster                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 118 ms: 1.12x faster                                               |
| regex_effbot   | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                              |
| regex_compile  | 103 ms                                                      | 102 ms: 1.02x faster                                               |
| Geometric mean | (ref)                                                       | 1.05x faster                                                       |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|---------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps          | 8.50 ms                                                     | 6.06 ms: 1.40x faster                                              |
| pickle_pure_python  | 257 us                                                      | 223 us: 1.15x faster                                               |
| tomli_loads         | 1.62 sec                                                    | 1.42 sec: 1.14x faster                                             |
| unpickle            | 9.17 us                                                     | 8.33 us: 1.10x faster                                              |
| xml_etree_parse     | 102 ms                                                      | 93.6 ms: 1.09x faster                                              |
| json_loads          | 14.2 us                                                     | 13.8 us: 1.03x faster                                              |
| xml_etree_process   | 43.4 ms                                                     | 44.8 ms: 1.03x slower                                              |
| pickle              | 6.80 us                                                     | 7.16 us: 1.05x slower                                              |
| pickle_dict         | 16.9 us                                                     | 18.2 us: 1.08x slower                                              |
| xml_etree_iterparse | 63.5 ms                                                     | 72.0 ms: 1.13x slower                                              |
| xml_etree_generate  | 54.5 ms                                                     | 62.1 ms: 1.14x slower                                              |
| pickle_list         | 2.59 us                                                     | 3.40 us: 1.31x slower                                              |
| Geometric mean      | (ref)                                                       | 1.01x faster                                                       |

Benchmark hidden because not significant (2): unpickle_list, unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                              |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                       |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.80 ms: 1.13x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 104 us: 3.13x faster                                               |
| mypy2                    | 352 ms                                                      | 233 ms: 1.51x faster                                               |
| asyncio_tcp              | 712 ms                                                      | 483 ms: 1.47x faster                                               |
| async_tree_none          | 420 ms                                                      | 294 ms: 1.43x faster                                               |
| deltablue                | 4.17 ms                                                     | 2.92 ms: 1.43x faster                                              |
| json_dumps               | 8.50 ms                                                     | 6.06 ms: 1.40x faster                                              |
| async_tree_io            | 1.07 sec                                                    | 778 ms: 1.37x faster                                               |
| async_tree_memoization   | 497 ms                                                      | 371 ms: 1.34x faster                                               |
| richards_super           | 51.7 ms                                                     | 40.1 ms: 1.29x faster                                              |
| crypto_pyaes             | 62.3 ms                                                     | 49.6 ms: 1.26x faster                                              |
| raytrace                 | 271 ms                                                      | 216 ms: 1.26x faster                                               |
| sqlglot_parse            | 1.22 ms                                                     | 996 us: 1.22x faster                                               |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 498 ms: 1.22x faster                                               |
| go                       | 136 ms                                                      | 113 ms: 1.21x faster                                               |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.70 sec: 1.20x faster                                             |
| chaos                    | 58.9 ms                                                     | 49.3 ms: 1.19x faster                                              |
| tornado_http             | 109 ms                                                      | 91.7 ms: 1.19x faster                                              |
| mdp                      | 1.71 sec                                                    | 1.45 sec: 1.18x faster                                             |
| sqlglot_transpile        | 1.46 ms                                                     | 1.24 ms: 1.18x faster                                              |
| nbody                    | 69.3 ms                                                     | 59.1 ms: 1.17x faster                                              |
| pickle_pure_python       | 257 us                                                      | 223 us: 1.15x faster                                               |
| richards                 | 41.2 ms                                                     | 35.9 ms: 1.15x faster                                              |
| tomli_loads              | 1.62 sec                                                    | 1.42 sec: 1.14x faster                                             |
| mako                     | 8.80 ms                                                     | 7.80 ms: 1.13x faster                                              |
| regex_dna                | 132 ms                                                      | 118 ms: 1.12x faster                                               |
| pyflate                  | 387 ms                                                      | 347 ms: 1.12x faster                                               |
| docutils                 | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                             |
| scimark_lu               | 85.4 ms                                                     | 76.9 ms: 1.11x faster                                              |
| unpickle                 | 9.17 us                                                     | 8.33 us: 1.10x faster                                              |
| xml_etree_parse          | 102 ms                                                      | 93.6 ms: 1.09x faster                                              |
| create_gc_cycles         | 782 us                                                      | 725 us: 1.08x faster                                               |
| bench_thread_pool        | 946 us                                                      | 886 us: 1.07x faster                                               |
| scimark_monte_carlo      | 55.9 ms                                                     | 52.5 ms: 1.06x faster                                              |
| hexiom                   | 5.52 ms                                                     | 5.18 ms: 1.06x faster                                              |
| regex_effbot             | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                              |
| pycparser                | 868 ms                                                      | 825 ms: 1.05x faster                                               |
| logging_silent           | 96.4 ns                                                     | 91.9 ns: 1.05x faster                                              |
| scimark_fft              | 193 ms                                                      | 186 ms: 1.04x faster                                               |
| sqlite_synth             | 1.84 us                                                     | 1.78 us: 1.03x faster                                              |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.58 ms: 1.03x faster                                              |
| json                     | 3.05 ms                                                     | 2.96 ms: 1.03x faster                                              |
| dulwich_log              | 47.6 ms                                                     | 46.2 ms: 1.03x faster                                              |
| json_loads               | 14.2 us                                                     | 13.8 us: 1.03x faster                                              |
| regex_compile            | 103 ms                                                      | 102 ms: 1.02x faster                                               |
| scimark_sor              | 105 ms                                                      | 103 ms: 1.02x faster                                               |
| nqueens                  | 67.0 ms                                                     | 66.4 ms: 1.01x faster                                              |
| pprint_safe_repr         | 589 ms                                                      | 597 ms: 1.01x slower                                               |
| pprint_pformat           | 1.21 sec                                                    | 1.23 sec: 1.02x slower                                             |
| fannkuch                 | 258 ms                                                      | 264 ms: 1.02x slower                                               |
| pathlib                  | 77.4 ms                                                     | 79.5 ms: 1.03x slower                                              |
| spectral_norm            | 78.0 ms                                                     | 80.3 ms: 1.03x slower                                              |
| xml_etree_process        | 43.4 ms                                                     | 44.8 ms: 1.03x slower                                              |
| sqlglot_normalize        | 202 ms                                                      | 210 ms: 1.04x slower                                               |
| comprehensions           | 16.0 us                                                     | 16.6 us: 1.04x slower                                              |
| pidigits                 | 145 ms                                                      | 152 ms: 1.05x slower                                               |
| pickle                   | 6.80 us                                                     | 7.16 us: 1.05x slower                                              |
| generators               | 31.6 ms                                                     | 33.3 ms: 1.05x slower                                              |
| python_startup_no_site   | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                              |
| deepcopy_memo            | 28.5 us                                                     | 30.4 us: 1.07x slower                                              |
| deepcopy                 | 255 us                                                      | 273 us: 1.07x slower                                               |
| pickle_dict              | 16.9 us                                                     | 18.2 us: 1.08x slower                                              |
| meteor_contest           | 72.5 ms                                                     | 78.2 ms: 1.08x slower                                              |
| float                    | 60.2 ms                                                     | 65.9 ms: 1.09x slower                                              |
| deepcopy_reduce          | 2.16 us                                                     | 2.39 us: 1.11x slower                                              |
| gc_traversal             | 1.34 ms                                                     | 1.51 ms: 1.12x slower                                              |
| xml_etree_iterparse      | 63.5 ms                                                     | 72.0 ms: 1.13x slower                                              |
| logging_format           | 6.66 us                                                     | 7.59 us: 1.14x slower                                              |
| xml_etree_generate       | 54.5 ms                                                     | 62.1 ms: 1.14x slower                                              |
| logging_simple           | 6.20 us                                                     | 7.10 us: 1.15x slower                                              |
| bench_mp_pool            | 60.7 ms                                                     | 70.6 ms: 1.16x slower                                              |
| coroutines               | 15.9 ms                                                     | 18.8 ms: 1.18x slower                                              |
| coverage                 | 40.0 ms                                                     | 48.9 ms: 1.22x slower                                              |
| async_generators         | 224 ms                                                      | 274 ms: 1.22x slower                                               |
| unpack_sequence          | 37.8 ns                                                     | 47.9 ns: 1.27x slower                                              |
| pickle_list              | 2.59 us                                                     | 3.40 us: 1.31x slower                                              |
| telco                    | 3.78 ms                                                     | 4.98 ms: 1.32x slower                                              |
| dask                     | 305 ms                                                      | 409 ms: 1.34x slower                                               |
| Geometric mean           | (ref)                                                       | 1.06x faster                                                       |

Benchmark hidden because not significant (5): unpickle_list, unpickle_pure_python, regex_v8, sqlglot_optimize, python_startup
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.07% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
