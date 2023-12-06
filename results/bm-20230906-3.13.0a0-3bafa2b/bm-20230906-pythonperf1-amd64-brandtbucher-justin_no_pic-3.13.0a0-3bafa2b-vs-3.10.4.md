
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_pic
- machine: windows-amd64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.12x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.67 sec: 1.13x faster                                                    |
| tornado_http   | 109 ms                                                      | 89.3 ms: 1.22x faster                                                     |
| Geometric mean | (ref)                                                       | 1.18x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 56.2 ms: 1.07x faster                                                     |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                                      |
| nbody          | 69.3 ms                                                     | 77.1 ms: 1.11x slower                                                     |
| Geometric mean | (ref)                                                       | 1.03x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 94.7 ms: 1.09x faster                                                     |
| regex_dna      | 132 ms                                                      | 123 ms: 1.07x faster                                                      |
| regex_effbot   | 1.66 ms                                                     | 1.64 ms: 1.01x faster                                                     |
| regex_v8       | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                                     |
| Geometric mean | (ref)                                                       | 1.04x faster                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.82 ms: 1.46x faster                                                     |
| pickle_pure_python   | 257 us                                                      | 203 us: 1.26x faster                                                      |
| unpickle_pure_python | 171 us                                                      | 152 us: 1.13x faster                                                      |
| xml_etree_parse      | 102 ms                                                      | 91.4 ms: 1.11x faster                                                     |
| tomli_loads          | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                                    |
| xml_etree_process    | 43.4 ms                                                     | 39.9 ms: 1.09x faster                                                     |
| unpickle             | 9.17 us                                                     | 8.46 us: 1.09x faster                                                     |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                                     |
| unpickle_list        | 2.81 us                                                     | 2.70 us: 1.04x faster                                                     |
| xml_etree_iterparse  | 63.5 ms                                                     | 65.3 ms: 1.03x slower                                                     |
| xml_etree_generate   | 54.5 ms                                                     | 58.2 ms: 1.07x slower                                                     |
| pickle               | 6.80 us                                                     | 7.38 us: 1.08x slower                                                     |
| pickle_dict          | 16.9 us                                                     | 18.9 us: 1.11x slower                                                     |
| pickle_list          | 2.59 us                                                     | 2.93 us: 1.13x slower                                                     |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                              |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.1 ms: 1.05x faster                                                     |
| python_startup_no_site | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                                     |
| Geometric mean         | (ref)                                                       | 1.01x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.74 ms: 1.30x faster                                                     |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 98.9 us: 3.28x faster                                                     |
| deltablue                | 4.17 ms                                                     | 2.31 ms: 1.81x faster                                                     |
| mypy2                    | 352 ms                                                      | 222 ms: 1.58x faster                                                      |
| async_tree_none          | 420 ms                                                      | 273 ms: 1.54x faster                                                      |
| logging_silent           | 96.4 ns                                                     | 64.4 ns: 1.50x faster                                                     |
| asyncio_tcp              | 712 ms                                                      | 479 ms: 1.49x faster                                                      |
| raytrace                 | 271 ms                                                      | 183 ms: 1.48x faster                                                      |
| richards_super           | 51.7 ms                                                     | 34.9 ms: 1.48x faster                                                     |
| json_dumps               | 8.50 ms                                                     | 5.82 ms: 1.46x faster                                                     |
| async_tree_io            | 1.07 sec                                                    | 731 ms: 1.46x faster                                                      |
| sqlglot_parse            | 1.22 ms                                                     | 856 us: 1.42x faster                                                      |
| async_tree_memoization   | 497 ms                                                      | 353 ms: 1.41x faster                                                      |
| richards                 | 41.2 ms                                                     | 30.3 ms: 1.36x faster                                                     |
| sqlglot_transpile        | 1.46 ms                                                     | 1.08 ms: 1.35x faster                                                     |
| scimark_lu               | 85.4 ms                                                     | 64.5 ms: 1.32x faster                                                     |
| generators               | 31.6 ms                                                     | 24.1 ms: 1.31x faster                                                     |
| chaos                    | 58.9 ms                                                     | 45.1 ms: 1.31x faster                                                     |
| mako                     | 8.80 ms                                                     | 6.74 ms: 1.30x faster                                                     |
| go                       | 136 ms                                                      | 105 ms: 1.30x faster                                                      |
| crypto_pyaes             | 62.3 ms                                                     | 48.0 ms: 1.30x faster                                                     |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 478 ms: 1.27x faster                                                      |
| pickle_pure_python       | 257 us                                                      | 203 us: 1.26x faster                                                      |
| pyflate                  | 387 ms                                                      | 316 ms: 1.22x faster                                                      |
| tornado_http             | 109 ms                                                      | 89.3 ms: 1.22x faster                                                     |
| scimark_monte_carlo      | 55.9 ms                                                     | 46.5 ms: 1.20x faster                                                     |
| pycparser                | 868 ms                                                      | 726 ms: 1.20x faster                                                      |
| scimark_sor              | 105 ms                                                      | 90.4 ms: 1.16x faster                                                     |
| hexiom                   | 5.52 ms                                                     | 4.80 ms: 1.15x faster                                                     |
| spectral_norm            | 78.0 ms                                                     | 68.7 ms: 1.14x faster                                                     |
| docutils                 | 1.89 sec                                                    | 1.67 sec: 1.13x faster                                                    |
| mdp                      | 1.71 sec                                                    | 1.51 sec: 1.13x faster                                                    |
| unpickle_pure_python     | 171 us                                                      | 152 us: 1.13x faster                                                      |
| xml_etree_parse          | 102 ms                                                      | 91.4 ms: 1.11x faster                                                     |
| regex_compile            | 103 ms                                                      | 94.7 ms: 1.09x faster                                                     |
| tomli_loads              | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                                    |
| xml_etree_process        | 43.4 ms                                                     | 39.9 ms: 1.09x faster                                                     |
| bench_thread_pool        | 946 us                                                      | 869 us: 1.09x faster                                                      |
| create_gc_cycles         | 782 us                                                      | 720 us: 1.09x faster                                                      |
| unpickle                 | 9.17 us                                                     | 8.46 us: 1.09x faster                                                     |
| deepcopy_memo            | 28.5 us                                                     | 26.5 us: 1.08x faster                                                     |
| float                    | 60.2 ms                                                     | 56.2 ms: 1.07x faster                                                     |
| regex_dna                | 132 ms                                                      | 123 ms: 1.07x faster                                                      |
| pprint_pformat           | 1.21 sec                                                    | 1.13 sec: 1.06x faster                                                    |
| sqlglot_optimize         | 39.0 ms                                                     | 36.7 ms: 1.06x faster                                                     |
| pprint_safe_repr         | 589 ms                                                      | 555 ms: 1.06x faster                                                      |
| python_startup           | 20.0 ms                                                     | 19.1 ms: 1.05x faster                                                     |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                                     |
| json                     | 3.05 ms                                                     | 2.92 ms: 1.05x faster                                                     |
| unpickle_list            | 2.81 us                                                     | 2.70 us: 1.04x faster                                                     |
| sqlite_synth             | 1.84 us                                                     | 1.77 us: 1.04x faster                                                     |
| dulwich_log              | 47.6 ms                                                     | 45.7 ms: 1.04x faster                                                     |
| coroutines               | 15.9 ms                                                     | 15.3 ms: 1.04x faster                                                     |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.96 sec: 1.04x faster                                                    |
| nqueens                  | 67.0 ms                                                     | 65.3 ms: 1.03x faster                                                     |
| sqlglot_normalize        | 202 ms                                                      | 197 ms: 1.03x faster                                                      |
| comprehensions           | 16.0 us                                                     | 15.6 us: 1.02x faster                                                     |
| regex_effbot             | 1.66 ms                                                     | 1.64 ms: 1.01x faster                                                     |
| fannkuch                 | 258 ms                                                      | 255 ms: 1.01x faster                                                      |
| regex_v8                 | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                                     |
| scimark_fft              | 193 ms                                                      | 196 ms: 1.02x slower                                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.70 ms: 1.02x slower                                                     |
| logging_format           | 6.66 us                                                     | 6.80 us: 1.02x slower                                                     |
| pathlib                  | 77.4 ms                                                     | 79.2 ms: 1.02x slower                                                     |
| logging_simple           | 6.20 us                                                     | 6.37 us: 1.03x slower                                                     |
| xml_etree_iterparse      | 63.5 ms                                                     | 65.3 ms: 1.03x slower                                                     |
| python_startup_no_site   | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                                     |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                                      |
| deepcopy_reduce          | 2.16 us                                                     | 2.25 us: 1.04x slower                                                     |
| xml_etree_generate       | 54.5 ms                                                     | 58.2 ms: 1.07x slower                                                     |
| pickle                   | 6.80 us                                                     | 7.38 us: 1.08x slower                                                     |
| meteor_contest           | 72.5 ms                                                     | 78.7 ms: 1.08x slower                                                     |
| nbody                    | 69.3 ms                                                     | 77.1 ms: 1.11x slower                                                     |
| pickle_dict              | 16.9 us                                                     | 18.9 us: 1.11x slower                                                     |
| gc_traversal             | 1.34 ms                                                     | 1.51 ms: 1.12x slower                                                     |
| async_generators         | 224 ms                                                      | 252 ms: 1.13x slower                                                      |
| pickle_list              | 2.59 us                                                     | 2.93 us: 1.13x slower                                                     |
| bench_mp_pool            | 60.7 ms                                                     | 69.6 ms: 1.15x slower                                                     |
| coverage                 | 40.0 ms                                                     | 46.6 ms: 1.16x slower                                                     |
| unpack_sequence          | 37.8 ns                                                     | 45.2 ns: 1.19x slower                                                     |
| telco                    | 3.78 ms                                                     | 4.76 ms: 1.26x slower                                                     |
| dask                     | 305 ms                                                      | 391 ms: 1.28x slower                                                      |
| Geometric mean           | (ref)                                                       | 1.12x faster                                                              |

Benchmark hidden because not significant (1): deepcopy
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.06x
- 95% likely to have a speedup of 1.06x
- 99% likely to have a speedup of 1.04x
