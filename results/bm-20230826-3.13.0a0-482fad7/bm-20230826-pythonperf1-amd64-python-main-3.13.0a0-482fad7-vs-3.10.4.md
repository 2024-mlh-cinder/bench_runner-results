
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 482fad7
- commit date: 2023-08-26
- overall geometric mean: 1.15x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                     |
| tornado_http   | 109 ms                                                      | 87.6 ms: 1.25x faster                                      |
| Geometric mean | (ref)                                                       | 1.21x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.3 ms: 1.09x faster                                      |
| pidigits       | 145 ms                                                      | 147 ms: 1.02x slower                                       |
| nbody          | 69.3 ms                                                     | 75.4 ms: 1.09x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 90.7 ms: 1.14x faster                                      |
| regex_dna      | 132 ms                                                      | 120 ms: 1.10x faster                                       |
| regex_effbot   | 1.66 ms                                                     | 1.60 ms: 1.04x faster                                      |
| regex_v8       | 15.0 ms                                                     | 14.7 ms: 1.03x faster                                      |
| Geometric mean | (ref)                                                       | 1.08x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.71 ms: 1.49x faster                                      |
| pickle_pure_python   | 257 us                                                      | 197 us: 1.31x faster                                       |
| unpickle_pure_python | 171 us                                                      | 144 us: 1.19x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 39.0 ms: 1.11x faster                                      |
| tomli_loads          | 1.62 sec                                                    | 1.48 sec: 1.10x faster                                     |
| xml_etree_parse      | 102 ms                                                      | 93.4 ms: 1.09x faster                                      |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                      |
| unpickle_list        | 2.81 us                                                     | 2.92 us: 1.04x slower                                      |
| xml_etree_generate   | 54.5 ms                                                     | 57.0 ms: 1.05x slower                                      |
| pickle               | 6.80 us                                                     | 7.13 us: 1.05x slower                                      |
| pickle_dict          | 16.9 us                                                     | 18.4 us: 1.09x slower                                      |
| pickle_list          | 2.59 us                                                     | 2.86 us: 1.11x slower                                      |
| Geometric mean       | (ref)                                                       | 1.06x faster                                               |

Benchmark hidden because not significant (2): unpickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.0 ms: 1.05x faster                                      |
| python_startup_no_site | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                      |
| Geometric mean         | (ref)                                                       | 1.00x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.47 ms: 1.18x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf1-amd64-python-main-3.13.0a0-482fad7 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 94.5 us: 3.43x faster                                      |
| deltablue                | 4.17 ms                                                     | 2.23 ms: 1.87x faster                                      |
| mypy2                    | 352 ms                                                      | 213 ms: 1.65x faster                                       |
| async_tree_none          | 420 ms                                                      | 268 ms: 1.57x faster                                       |
| richards_super           | 51.7 ms                                                     | 33.3 ms: 1.56x faster                                      |
| raytrace                 | 271 ms                                                      | 175 ms: 1.55x faster                                       |
| asyncio_tcp              | 712 ms                                                      | 468 ms: 1.52x faster                                       |
| logging_silent           | 96.4 ns                                                     | 64.0 ns: 1.51x faster                                      |
| json_dumps               | 8.50 ms                                                     | 5.71 ms: 1.49x faster                                      |
| async_tree_io            | 1.07 sec                                                    | 723 ms: 1.47x faster                                       |
| sqlglot_parse            | 1.22 ms                                                     | 831 us: 1.47x faster                                       |
| go                       | 136 ms                                                      | 93.7 ms: 1.45x faster                                      |
| async_tree_memoization   | 497 ms                                                      | 344 ms: 1.45x faster                                       |
| richards                 | 41.2 ms                                                     | 29.4 ms: 1.40x faster                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.05 ms: 1.39x faster                                      |
| scimark_lu               | 85.4 ms                                                     | 61.4 ms: 1.39x faster                                      |
| crypto_pyaes             | 62.3 ms                                                     | 45.3 ms: 1.38x faster                                      |
| chaos                    | 58.9 ms                                                     | 42.9 ms: 1.37x faster                                      |
| generators               | 31.6 ms                                                     | 24.1 ms: 1.31x faster                                      |
| pickle_pure_python       | 257 us                                                      | 197 us: 1.31x faster                                       |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 470 ms: 1.30x faster                                       |
| hexiom                   | 5.52 ms                                                     | 4.32 ms: 1.28x faster                                      |
| pyflate                  | 387 ms                                                      | 309 ms: 1.25x faster                                       |
| tornado_http             | 109 ms                                                      | 87.6 ms: 1.25x faster                                      |
| mdp                      | 1.71 sec                                                    | 1.40 sec: 1.23x faster                                     |
| scimark_monte_carlo      | 55.9 ms                                                     | 46.0 ms: 1.21x faster                                      |
| pycparser                | 868 ms                                                      | 716 ms: 1.21x faster                                       |
| spectral_norm            | 78.0 ms                                                     | 65.4 ms: 1.19x faster                                      |
| scimark_sor              | 105 ms                                                      | 87.9 ms: 1.19x faster                                      |
| unpickle_pure_python     | 171 us                                                      | 144 us: 1.19x faster                                       |
| mako                     | 8.80 ms                                                     | 7.47 ms: 1.18x faster                                      |
| deepcopy_memo            | 28.5 us                                                     | 24.3 us: 1.17x faster                                      |
| docutils                 | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                     |
| regex_compile            | 103 ms                                                      | 90.7 ms: 1.14x faster                                      |
| sqlglot_optimize         | 39.0 ms                                                     | 34.9 ms: 1.12x faster                                      |
| xml_etree_process        | 43.4 ms                                                     | 39.0 ms: 1.11x faster                                      |
| pprint_safe_repr         | 589 ms                                                      | 531 ms: 1.11x faster                                       |
| bench_thread_pool        | 946 us                                                      | 855 us: 1.11x faster                                       |
| pprint_pformat           | 1.21 sec                                                    | 1.09 sec: 1.11x faster                                     |
| regex_dna                | 132 ms                                                      | 120 ms: 1.10x faster                                       |
| nqueens                  | 67.0 ms                                                     | 61.2 ms: 1.10x faster                                      |
| tomli_loads              | 1.62 sec                                                    | 1.48 sec: 1.10x faster                                     |
| xml_etree_parse          | 102 ms                                                      | 93.4 ms: 1.09x faster                                      |
| float                    | 60.2 ms                                                     | 55.3 ms: 1.09x faster                                      |
| create_gc_cycles         | 782 us                                                      | 723 us: 1.08x faster                                       |
| sqlglot_normalize        | 202 ms                                                      | 187 ms: 1.08x faster                                       |
| comprehensions           | 16.0 us                                                     | 14.8 us: 1.08x faster                                      |
| json                     | 3.05 ms                                                     | 2.85 ms: 1.07x faster                                      |
| deepcopy                 | 255 us                                                      | 239 us: 1.07x faster                                       |
| dulwich_log              | 47.6 ms                                                     | 44.6 ms: 1.07x faster                                      |
| sqlite_synth             | 1.84 us                                                     | 1.74 us: 1.06x faster                                      |
| coroutines               | 15.9 ms                                                     | 15.1 ms: 1.05x faster                                      |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                      |
| python_startup           | 20.0 ms                                                     | 19.0 ms: 1.05x faster                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.54 ms: 1.05x faster                                      |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.95 sec: 1.04x faster                                     |
| regex_effbot             | 1.66 ms                                                     | 1.60 ms: 1.04x faster                                      |
| scimark_fft              | 193 ms                                                      | 186 ms: 1.04x faster                                       |
| regex_v8                 | 15.0 ms                                                     | 14.7 ms: 1.03x faster                                      |
| pathlib                  | 77.4 ms                                                     | 78.4 ms: 1.01x slower                                      |
| pidigits                 | 145 ms                                                      | 147 ms: 1.02x slower                                       |
| meteor_contest           | 72.5 ms                                                     | 74.9 ms: 1.03x slower                                      |
| logging_format           | 6.66 us                                                     | 6.89 us: 1.03x slower                                      |
| unpickle_list            | 2.81 us                                                     | 2.92 us: 1.04x slower                                      |
| python_startup_no_site   | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                      |
| logging_simple           | 6.20 us                                                     | 6.48 us: 1.04x slower                                      |
| xml_etree_generate       | 54.5 ms                                                     | 57.0 ms: 1.05x slower                                      |
| pickle                   | 6.80 us                                                     | 7.13 us: 1.05x slower                                      |
| unpack_sequence          | 37.8 ns                                                     | 39.7 ns: 1.05x slower                                      |
| fannkuch                 | 258 ms                                                      | 272 ms: 1.06x slower                                       |
| async_generators         | 224 ms                                                      | 241 ms: 1.08x slower                                       |
| pickle_dict              | 16.9 us                                                     | 18.4 us: 1.09x slower                                      |
| nbody                    | 69.3 ms                                                     | 75.4 ms: 1.09x slower                                      |
| bench_mp_pool            | 60.7 ms                                                     | 66.3 ms: 1.09x slower                                      |
| pickle_list              | 2.59 us                                                     | 2.86 us: 1.11x slower                                      |
| gc_traversal             | 1.34 ms                                                     | 1.49 ms: 1.11x slower                                      |
| coverage                 | 40.0 ms                                                     | 46.9 ms: 1.17x slower                                      |
| dask                     | 305 ms                                                      | 373 ms: 1.22x slower                                       |
| telco                    | 3.78 ms                                                     | 4.67 ms: 1.23x slower                                      |
| Geometric mean           | (ref)                                                       | 1.15x faster                                               |

Benchmark hidden because not significant (3): unpickle, deepcopy_reduce, xml_etree_iterparse
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
