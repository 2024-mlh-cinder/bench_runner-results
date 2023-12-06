
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.17x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                     |
| tornado_http   | 109 ms                                                      | 88.4 ms: 1.23x faster                                      |
| Geometric mean | (ref)                                                       | 1.21x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.4 ms: 1.11x faster                                      |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                       |
| nbody          | 69.3 ms                                                     | 72.5 ms: 1.05x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 89.1 ms: 1.16x faster                                      |
| regex_dna      | 132 ms                                                      | 120 ms: 1.10x faster                                       |
| regex_effbot   | 1.66 ms                                                     | 1.60 ms: 1.04x faster                                      |
| Geometric mean | (ref)                                                       | 1.06x faster                                               |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.76 ms: 1.48x faster                                      |
| pickle_pure_python   | 257 us                                                      | 190 us: 1.35x faster                                       |
| unpickle_pure_python | 171 us                                                      | 134 us: 1.28x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 38.2 ms: 1.14x faster                                      |
| xml_etree_parse      | 102 ms                                                      | 91.8 ms: 1.11x faster                                      |
| tomli_loads          | 1.62 sec                                                    | 1.48 sec: 1.10x faster                                     |
| unpickle             | 9.17 us                                                     | 8.40 us: 1.09x faster                                      |
| unpickle_list        | 2.81 us                                                     | 2.63 us: 1.07x faster                                      |
| json_loads           | 14.2 us                                                     | 13.7 us: 1.04x faster                                      |
| xml_etree_generate   | 54.5 ms                                                     | 55.5 ms: 1.02x slower                                      |
| pickle               | 6.80 us                                                     | 7.10 us: 1.04x slower                                      |
| pickle_dict          | 16.9 us                                                     | 18.4 us: 1.09x slower                                      |
| pickle_list          | 2.59 us                                                     | 3.21 us: 1.24x slower                                      |
| Geometric mean       | (ref)                                                       | 1.08x faster                                               |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.6 ms: 1.02x faster                                      |
| python_startup_no_site | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                      |
| Geometric mean         | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.33 ms: 1.20x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 93.7 us: 3.46x faster                                      |
| deltablue                | 4.17 ms                                                     | 2.19 ms: 1.91x faster                                      |
| mypy2                    | 352 ms                                                      | 213 ms: 1.65x faster                                       |
| richards_super           | 51.7 ms                                                     | 31.7 ms: 1.63x faster                                      |
| raytrace                 | 271 ms                                                      | 174 ms: 1.56x faster                                       |
| async_tree_none          | 420 ms                                                      | 269 ms: 1.56x faster                                       |
| go                       | 136 ms                                                      | 89.5 ms: 1.52x faster                                      |
| logging_silent           | 96.4 ns                                                     | 63.5 ns: 1.52x faster                                      |
| asyncio_tcp              | 712 ms                                                      | 470 ms: 1.51x faster                                       |
| sqlglot_parse            | 1.22 ms                                                     | 810 us: 1.50x faster                                       |
| json_dumps               | 8.50 ms                                                     | 5.76 ms: 1.48x faster                                      |
| scimark_lu               | 85.4 ms                                                     | 58.0 ms: 1.47x faster                                      |
| async_tree_io            | 1.07 sec                                                    | 723 ms: 1.47x faster                                       |
| chaos                    | 58.9 ms                                                     | 40.4 ms: 1.46x faster                                      |
| richards                 | 41.2 ms                                                     | 28.4 ms: 1.45x faster                                      |
| async_tree_memoization   | 497 ms                                                      | 344 ms: 1.45x faster                                       |
| sqlglot_transpile        | 1.46 ms                                                     | 1.03 ms: 1.42x faster                                      |
| crypto_pyaes             | 62.3 ms                                                     | 45.0 ms: 1.39x faster                                      |
| scimark_monte_carlo      | 55.9 ms                                                     | 40.6 ms: 1.38x faster                                      |
| scimark_sor              | 105 ms                                                      | 76.8 ms: 1.36x faster                                      |
| generators               | 31.6 ms                                                     | 23.2 ms: 1.36x faster                                      |
| pickle_pure_python       | 257 us                                                      | 190 us: 1.35x faster                                       |
| hexiom                   | 5.52 ms                                                     | 4.13 ms: 1.33x faster                                      |
| pyflate                  | 387 ms                                                      | 299 ms: 1.29x faster                                       |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 471 ms: 1.29x faster                                       |
| unpickle_pure_python     | 171 us                                                      | 134 us: 1.28x faster                                       |
| tornado_http             | 109 ms                                                      | 88.4 ms: 1.23x faster                                      |
| spectral_norm            | 78.0 ms                                                     | 63.3 ms: 1.23x faster                                      |
| mako                     | 8.80 ms                                                     | 7.33 ms: 1.20x faster                                      |
| deepcopy_memo            | 28.5 us                                                     | 23.9 us: 1.19x faster                                      |
| docutils                 | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                     |
| mdp                      | 1.71 sec                                                    | 1.46 sec: 1.18x faster                                     |
| regex_compile            | 103 ms                                                      | 89.1 ms: 1.16x faster                                      |
| pprint_pformat           | 1.21 sec                                                    | 1.06 sec: 1.14x faster                                     |
| xml_etree_process        | 43.4 ms                                                     | 38.2 ms: 1.14x faster                                      |
| pprint_safe_repr         | 589 ms                                                      | 519 ms: 1.14x faster                                       |
| comprehensions           | 16.0 us                                                     | 14.1 us: 1.13x faster                                      |
| sqlglot_optimize         | 39.0 ms                                                     | 34.7 ms: 1.12x faster                                      |
| bench_thread_pool        | 946 us                                                      | 844 us: 1.12x faster                                       |
| pycparser                | 868 ms                                                      | 775 ms: 1.12x faster                                       |
| nqueens                  | 67.0 ms                                                     | 60.2 ms: 1.11x faster                                      |
| xml_etree_parse          | 102 ms                                                      | 91.8 ms: 1.11x faster                                      |
| float                    | 60.2 ms                                                     | 54.4 ms: 1.11x faster                                      |
| sqlglot_normalize        | 202 ms                                                      | 183 ms: 1.10x faster                                       |
| deepcopy                 | 255 us                                                      | 231 us: 1.10x faster                                       |
| scimark_fft              | 193 ms                                                      | 175 ms: 1.10x faster                                       |
| tomli_loads              | 1.62 sec                                                    | 1.48 sec: 1.10x faster                                     |
| regex_dna                | 132 ms                                                      | 120 ms: 1.10x faster                                       |
| unpickle                 | 9.17 us                                                     | 8.40 us: 1.09x faster                                      |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.86 sec: 1.09x faster                                     |
| coroutines               | 15.9 ms                                                     | 14.6 ms: 1.09x faster                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.45 ms: 1.09x faster                                      |
| unpickle_list            | 2.81 us                                                     | 2.63 us: 1.07x faster                                      |
| create_gc_cycles         | 782 us                                                      | 734 us: 1.06x faster                                       |
| dulwich_log              | 47.6 ms                                                     | 44.9 ms: 1.06x faster                                      |
| sqlite_synth             | 1.84 us                                                     | 1.75 us: 1.05x faster                                      |
| json                     | 3.05 ms                                                     | 2.90 ms: 1.05x faster                                      |
| fannkuch                 | 258 ms                                                      | 246 ms: 1.05x faster                                       |
| deepcopy_reduce          | 2.16 us                                                     | 2.06 us: 1.04x faster                                      |
| regex_effbot             | 1.66 ms                                                     | 1.60 ms: 1.04x faster                                      |
| json_loads               | 14.2 us                                                     | 13.7 us: 1.04x faster                                      |
| python_startup           | 20.0 ms                                                     | 19.6 ms: 1.02x faster                                      |
| meteor_contest           | 72.5 ms                                                     | 73.4 ms: 1.01x slower                                      |
| pathlib                  | 77.4 ms                                                     | 78.7 ms: 1.02x slower                                      |
| xml_etree_generate       | 54.5 ms                                                     | 55.5 ms: 1.02x slower                                      |
| unpack_sequence          | 37.8 ns                                                     | 38.6 ns: 1.02x slower                                      |
| logging_format           | 6.66 us                                                     | 6.85 us: 1.03x slower                                      |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                       |
| logging_simple           | 6.20 us                                                     | 6.44 us: 1.04x slower                                      |
| pickle                   | 6.80 us                                                     | 7.10 us: 1.04x slower                                      |
| nbody                    | 69.3 ms                                                     | 72.5 ms: 1.05x slower                                      |
| python_startup_no_site   | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                      |
| async_generators         | 224 ms                                                      | 236 ms: 1.06x slower                                       |
| pickle_dict              | 16.9 us                                                     | 18.4 us: 1.09x slower                                      |
| gc_traversal             | 1.34 ms                                                     | 1.51 ms: 1.13x slower                                      |
| bench_mp_pool            | 60.7 ms                                                     | 68.6 ms: 1.13x slower                                      |
| coverage                 | 40.0 ms                                                     | 46.9 ms: 1.17x slower                                      |
| pickle_list              | 2.59 us                                                     | 3.21 us: 1.24x slower                                      |
| telco                    | 3.78 ms                                                     | 4.91 ms: 1.30x slower                                      |
| Geometric mean           | (ref)                                                       | 1.17x faster                                               |

Benchmark hidden because not significant (2): xml_etree_iterparse, regex_v8
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.10x
