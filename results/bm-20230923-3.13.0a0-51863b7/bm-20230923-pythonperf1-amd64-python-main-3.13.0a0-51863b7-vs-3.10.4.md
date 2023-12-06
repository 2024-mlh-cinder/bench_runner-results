
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.16x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                     |
| tornado_http   | 109 ms                                                      | 88.1 ms: 1.24x faster                                      |
| Geometric mean | (ref)                                                       | 1.21x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.8 ms: 1.10x faster                                      |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                       |
| nbody          | 69.3 ms                                                     | 76.0 ms: 1.10x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 90.1 ms: 1.15x faster                                      |
| regex_dna      | 132 ms                                                      | 122 ms: 1.08x faster                                       |
| regex_effbot   | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                      |
| regex_v8       | 15.0 ms                                                     | 14.8 ms: 1.01x faster                                      |
| Geometric mean | (ref)                                                       | 1.07x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.74 ms: 1.48x faster                                      |
| pickle_pure_python   | 257 us                                                      | 192 us: 1.33x faster                                       |
| unpickle_pure_python | 171 us                                                      | 136 us: 1.26x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 38.5 ms: 1.13x faster                                      |
| unpickle             | 9.17 us                                                     | 8.29 us: 1.11x faster                                      |
| xml_etree_parse      | 102 ms                                                      | 93.1 ms: 1.09x faster                                      |
| tomli_loads          | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                     |
| unpickle_list        | 2.81 us                                                     | 2.65 us: 1.06x faster                                      |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.05x faster                                      |
| xml_etree_generate   | 54.5 ms                                                     | 56.7 ms: 1.04x slower                                      |
| pickle               | 6.80 us                                                     | 7.13 us: 1.05x slower                                      |
| pickle_dict          | 16.9 us                                                     | 18.7 us: 1.10x slower                                      |
| pickle_list          | 2.59 us                                                     | 3.38 us: 1.31x slower                                      |
| Geometric mean       | (ref)                                                       | 1.07x faster                                               |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                      |
| Geometric mean         | (ref)                                                       | 1.02x slower                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.39 ms: 1.19x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 96.0 us: 3.38x faster                                      |
| deltablue                | 4.17 ms                                                     | 2.18 ms: 1.91x faster                                      |
| mypy2                    | 352 ms                                                      | 214 ms: 1.65x faster                                       |
| richards_super           | 51.7 ms                                                     | 32.0 ms: 1.62x faster                                      |
| async_tree_none          | 420 ms                                                      | 262 ms: 1.60x faster                                       |
| raytrace                 | 271 ms                                                      | 177 ms: 1.53x faster                                       |
| sqlglot_parse            | 1.22 ms                                                     | 805 us: 1.51x faster                                       |
| logging_silent           | 96.4 ns                                                     | 63.7 ns: 1.51x faster                                      |
| go                       | 136 ms                                                      | 91.6 ms: 1.49x faster                                      |
| json_dumps               | 8.50 ms                                                     | 5.74 ms: 1.48x faster                                      |
| asyncio_tcp              | 712 ms                                                      | 482 ms: 1.48x faster                                       |
| async_tree_io            | 1.07 sec                                                    | 722 ms: 1.48x faster                                       |
| async_tree_memoization   | 497 ms                                                      | 344 ms: 1.45x faster                                       |
| sqlglot_transpile        | 1.46 ms                                                     | 1.02 ms: 1.43x faster                                      |
| richards                 | 41.2 ms                                                     | 28.8 ms: 1.43x faster                                      |
| scimark_lu               | 85.4 ms                                                     | 59.8 ms: 1.43x faster                                      |
| chaos                    | 58.9 ms                                                     | 41.4 ms: 1.42x faster                                      |
| generators               | 31.6 ms                                                     | 22.9 ms: 1.38x faster                                      |
| crypto_pyaes             | 62.3 ms                                                     | 45.7 ms: 1.36x faster                                      |
| scimark_monte_carlo      | 55.9 ms                                                     | 41.7 ms: 1.34x faster                                      |
| pickle_pure_python       | 257 us                                                      | 192 us: 1.33x faster                                       |
| hexiom                   | 5.52 ms                                                     | 4.21 ms: 1.31x faster                                      |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 466 ms: 1.31x faster                                       |
| scimark_sor              | 105 ms                                                      | 80.8 ms: 1.30x faster                                      |
| pyflate                  | 387 ms                                                      | 300 ms: 1.29x faster                                       |
| unpickle_pure_python     | 171 us                                                      | 136 us: 1.26x faster                                       |
| tornado_http             | 109 ms                                                      | 88.1 ms: 1.24x faster                                      |
| spectral_norm            | 78.0 ms                                                     | 63.0 ms: 1.24x faster                                      |
| mako                     | 8.80 ms                                                     | 7.39 ms: 1.19x faster                                      |
| deepcopy_memo            | 28.5 us                                                     | 24.1 us: 1.18x faster                                      |
| docutils                 | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                     |
| mdp                      | 1.71 sec                                                    | 1.47 sec: 1.17x faster                                     |
| regex_compile            | 103 ms                                                      | 90.1 ms: 1.15x faster                                      |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.79 sec: 1.14x faster                                     |
| bench_thread_pool        | 946 us                                                      | 834 us: 1.14x faster                                       |
| pprint_pformat           | 1.21 sec                                                    | 1.07 sec: 1.13x faster                                     |
| pprint_safe_repr         | 589 ms                                                      | 521 ms: 1.13x faster                                       |
| xml_etree_process        | 43.4 ms                                                     | 38.5 ms: 1.13x faster                                      |
| sqlglot_optimize         | 39.0 ms                                                     | 34.7 ms: 1.12x faster                                      |
| comprehensions           | 16.0 us                                                     | 14.3 us: 1.12x faster                                      |
| unpickle                 | 9.17 us                                                     | 8.29 us: 1.11x faster                                      |
| nqueens                  | 67.0 ms                                                     | 60.8 ms: 1.10x faster                                      |
| sqlglot_normalize        | 202 ms                                                      | 184 ms: 1.10x faster                                       |
| float                    | 60.2 ms                                                     | 54.8 ms: 1.10x faster                                      |
| xml_etree_parse          | 102 ms                                                      | 93.1 ms: 1.09x faster                                      |
| coroutines               | 15.9 ms                                                     | 14.6 ms: 1.09x faster                                      |
| pycparser                | 868 ms                                                      | 796 ms: 1.09x faster                                       |
| deepcopy                 | 255 us                                                      | 234 us: 1.09x faster                                       |
| tomli_loads              | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                     |
| regex_dna                | 132 ms                                                      | 122 ms: 1.08x faster                                       |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.48 ms: 1.07x faster                                      |
| unpickle_list            | 2.81 us                                                     | 2.65 us: 1.06x faster                                      |
| create_gc_cycles         | 782 us                                                      | 739 us: 1.06x faster                                       |
| scimark_fft              | 193 ms                                                      | 183 ms: 1.06x faster                                       |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.05x faster                                      |
| dulwich_log              | 47.6 ms                                                     | 45.2 ms: 1.05x faster                                      |
| regex_effbot             | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                      |
| sqlite_synth             | 1.84 us                                                     | 1.79 us: 1.03x faster                                      |
| deepcopy_reduce          | 2.16 us                                                     | 2.11 us: 1.02x faster                                      |
| regex_v8                 | 15.0 ms                                                     | 14.8 ms: 1.01x faster                                      |
| meteor_contest           | 72.5 ms                                                     | 72.8 ms: 1.00x slower                                      |
| logging_format           | 6.66 us                                                     | 6.73 us: 1.01x slower                                      |
| logging_simple           | 6.20 us                                                     | 6.28 us: 1.01x slower                                      |
| pathlib                  | 77.4 ms                                                     | 78.7 ms: 1.02x slower                                      |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                       |
| unpack_sequence          | 37.8 ns                                                     | 39.2 ns: 1.04x slower                                      |
| xml_etree_generate       | 54.5 ms                                                     | 56.7 ms: 1.04x slower                                      |
| pickle                   | 6.80 us                                                     | 7.13 us: 1.05x slower                                      |
| python_startup_no_site   | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                      |
| async_generators         | 224 ms                                                      | 240 ms: 1.07x slower                                       |
| nbody                    | 69.3 ms                                                     | 76.0 ms: 1.10x slower                                      |
| pickle_dict              | 16.9 us                                                     | 18.7 us: 1.10x slower                                      |
| gc_traversal             | 1.34 ms                                                     | 1.50 ms: 1.11x slower                                      |
| coverage                 | 40.0 ms                                                     | 45.9 ms: 1.15x slower                                      |
| bench_mp_pool            | 60.7 ms                                                     | 70.6 ms: 1.16x slower                                      |
| dask                     | 305 ms                                                      | 368 ms: 1.21x slower                                       |
| telco                    | 3.78 ms                                                     | 4.77 ms: 1.26x slower                                      |
| pickle_list              | 2.59 us                                                     | 3.38 us: 1.31x slower                                      |
| Geometric mean           | (ref)                                                       | 1.16x faster                                               |

Benchmark hidden because not significant (4): json, python_startup, fannkuch, xml_etree_iterparse
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.09x
