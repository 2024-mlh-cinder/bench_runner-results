
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_os
- machine: linux-x86_64
- commit hash: 24495fb
- commit date: 2023-10-13
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.94 sec: 1.16x faster                                                 |
| tornado_http   | 152 ms                                                       | 123 ms: 1.23x faster                                                   |
| Geometric mean | (ref)                                                        | 1.20x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 100 ms: 1.37x faster                                                   |
| float          | 110 ms                                                       | 88.0 ms: 1.25x faster                                                  |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                        | 1.20x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 159 ms: 1.22x faster                                                   |
| regex_v8       | 26.6 ms                                                      | 24.9 ms: 1.07x faster                                                  |
| regex_dna      | 259 ms                                                       | 248 ms: 1.05x faster                                                   |
| regex_effbot   | 2.99 ms                                                      | 3.59 ms: 1.20x slower                                                  |
| Geometric mean | (ref)                                                        | 1.03x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 322 us: 1.42x faster                                                   |
| unpickle_pure_python | 321 us                                                       | 241 us: 1.33x faster                                                   |
| json_dumps           | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                                  |
| xml_etree_process    | 76.0 ms                                                      | 59.6 ms: 1.28x faster                                                  |
| json_loads           | 30.0 us                                                      | 25.0 us: 1.20x faster                                                  |
| tomli_loads          | 2.97 sec                                                     | 2.49 sec: 1.19x faster                                                 |
| xml_etree_parse      | 162 ms                                                       | 147 ms: 1.10x faster                                                   |
| xml_etree_generate   | 94.6 ms                                                      | 86.2 ms: 1.10x faster                                                  |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                                   |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                                  |
| unpickle             | 14.2 us                                                      | 14.7 us: 1.04x slower                                                  |
| unpickle_list        | 4.49 us                                                      | 4.79 us: 1.07x slower                                                  |
| pickle_list          | 4.11 us                                                      | 4.40 us: 1.07x slower                                                  |
| pickle_dict          | 30.0 us                                                      | 32.2 us: 1.07x slower                                                  |
| Geometric mean       | (ref)                                                        | 1.11x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                  |
| python_startup_no_site | 7.32 ms                                                      | 8.71 ms: 1.19x slower                                                  |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 12.0 ms: 1.23x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_os-3.13.0a0-24495fb |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 158 us: 3.31x faster                                                   |
| asyncio_tcp              | 782 ms                                                       | 374 ms: 2.09x faster                                                   |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.59 sec: 1.95x faster                                                 |
| raytrace                 | 488 ms                                                       | 285 ms: 1.71x faster                                                   |
| logging_silent           | 166 ns                                                       | 100 ns: 1.66x faster                                                   |
| generators               | 58.0 ms                                                      | 36.7 ms: 1.58x faster                                                  |
| sqlglot_parse            | 2.26 ms                                                      | 1.44 ms: 1.57x faster                                                  |
| scimark_lu               | 164 ms                                                       | 105 ms: 1.56x faster                                                   |
| async_tree_none          | 700 ms                                                       | 448 ms: 1.56x faster                                                   |
| deltablue                | 7.47 ms                                                      | 4.81 ms: 1.55x faster                                                  |
| richards_super           | 90.8 ms                                                      | 58.8 ms: 1.55x faster                                                  |
| chaos                    | 107 ms                                                       | 70.2 ms: 1.53x faster                                                  |
| scimark_monte_carlo      | 109 ms                                                       | 73.5 ms: 1.49x faster                                                  |
| bench_mp_pool            | 7.18 ms                                                      | 4.83 ms: 1.49x faster                                                  |
| sqlglot_transpile        | 2.71 ms                                                      | 1.85 ms: 1.46x faster                                                  |
| async_tree_memoization   | 824 ms                                                       | 563 ms: 1.46x faster                                                   |
| async_tree_io            | 1.61 sec                                                     | 1.10 sec: 1.46x faster                                                 |
| spectral_norm            | 136 ms                                                       | 94.1 ms: 1.45x faster                                                  |
| go                       | 259 ms                                                       | 179 ms: 1.45x faster                                                   |
| pickle_pure_python       | 457 us                                                       | 322 us: 1.42x faster                                                   |
| crypto_pyaes             | 118 ms                                                       | 83.6 ms: 1.41x faster                                                  |
| richards                 | 74.1 ms                                                      | 52.6 ms: 1.41x faster                                                  |
| nbody                    | 137 ms                                                       | 100 ms: 1.37x faster                                                   |
| unpickle_pure_python     | 321 us                                                       | 241 us: 1.33x faster                                                   |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 716 ms: 1.33x faster                                                   |
| json_dumps               | 14.2 ms                                                      | 10.7 ms: 1.33x faster                                                  |
| pyflate                  | 697 ms                                                       | 528 ms: 1.32x faster                                                   |
| coroutines               | 30.4 ms                                                      | 23.4 ms: 1.30x faster                                                  |
| xml_etree_process        | 76.0 ms                                                      | 59.6 ms: 1.28x faster                                                  |
| unpack_sequence          | 59.5 ns                                                      | 47.1 ns: 1.26x faster                                                  |
| logging_simple           | 8.90 us                                                      | 7.09 us: 1.26x faster                                                  |
| float                    | 110 ms                                                       | 88.0 ms: 1.25x faster                                                  |
| pycparser                | 1.66 sec                                                     | 1.35 sec: 1.24x faster                                                 |
| logging_format           | 9.57 us                                                      | 7.75 us: 1.23x faster                                                  |
| tornado_http             | 152 ms                                                       | 123 ms: 1.23x faster                                                   |
| deepcopy_memo            | 48.9 us                                                      | 39.8 us: 1.23x faster                                                  |
| mako                     | 14.7 ms                                                      | 12.0 ms: 1.23x faster                                                  |
| regex_compile            | 194 ms                                                       | 159 ms: 1.22x faster                                                   |
| mypy2                    | 466 ms                                                       | 385 ms: 1.21x faster                                                   |
| scimark_sor              | 177 ms                                                       | 147 ms: 1.21x faster                                                   |
| json_loads               | 30.0 us                                                      | 25.0 us: 1.20x faster                                                  |
| pprint_pformat           | 2.15 sec                                                     | 1.80 sec: 1.20x faster                                                 |
| tomli_loads              | 2.97 sec                                                     | 2.49 sec: 1.19x faster                                                 |
| sqlglot_normalize        | 144 ms                                                       | 121 ms: 1.19x faster                                                   |
| pprint_safe_repr         | 1.05 sec                                                     | 882 ms: 1.19x faster                                                   |
| deepcopy_reduce          | 4.03 us                                                      | 3.43 us: 1.17x faster                                                  |
| deepcopy                 | 454 us                                                       | 388 us: 1.17x faster                                                   |
| json                     | 5.96 ms                                                      | 5.13 ms: 1.16x faster                                                  |
| bench_thread_pool        | 1.14 ms                                                      | 978 us: 1.16x faster                                                   |
| docutils                 | 3.40 sec                                                     | 2.94 sec: 1.16x faster                                                 |
| dulwich_log              | 80.1 ms                                                      | 69.5 ms: 1.15x faster                                                  |
| sqlglot_optimize         | 70.3 ms                                                      | 61.2 ms: 1.15x faster                                                  |
| create_gc_cycles         | 1.82 ms                                                      | 1.60 ms: 1.14x faster                                                  |
| fannkuch                 | 496 ms                                                       | 437 ms: 1.13x faster                                                   |
| mdp                      | 3.03 sec                                                     | 2.68 sec: 1.13x faster                                                 |
| sqlite_synth             | 2.97 us                                                      | 2.67 us: 1.11x faster                                                  |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.71 ms: 1.10x faster                                                  |
| xml_etree_parse          | 162 ms                                                       | 147 ms: 1.10x faster                                                   |
| nqueens                  | 112 ms                                                       | 102 ms: 1.10x faster                                                   |
| xml_etree_generate       | 94.6 ms                                                      | 86.2 ms: 1.10x faster                                                  |
| pathlib                  | 21.7 ms                                                      | 20.0 ms: 1.09x faster                                                  |
| hexiom                   | 9.52 ms                                                      | 8.90 ms: 1.07x faster                                                  |
| regex_v8                 | 26.6 ms                                                      | 24.9 ms: 1.07x faster                                                  |
| regex_dna                | 259 ms                                                       | 248 ms: 1.05x faster                                                   |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                                   |
| async_generators         | 422 ms                                                       | 410 ms: 1.03x faster                                                   |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                                   |
| meteor_contest           | 137 ms                                                       | 137 ms: 1.00x faster                                                   |
| scimark_fft              | 359 ms                                                       | 362 ms: 1.01x slower                                                   |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                                  |
| unpickle                 | 14.2 us                                                      | 14.7 us: 1.04x slower                                                  |
| comprehensions           | 26.9 us                                                      | 28.4 us: 1.06x slower                                                  |
| unpickle_list            | 4.49 us                                                      | 4.79 us: 1.07x slower                                                  |
| pickle_list              | 4.11 us                                                      | 4.40 us: 1.07x slower                                                  |
| pickle_dict              | 30.0 us                                                      | 32.2 us: 1.07x slower                                                  |
| python_startup           | 11.5 ms                                                      | 12.8 ms: 1.11x slower                                                  |
| gc_traversal             | 3.45 ms                                                      | 3.97 ms: 1.15x slower                                                  |
| telco                    | 7.14 ms                                                      | 8.34 ms: 1.17x slower                                                  |
| python_startup_no_site   | 7.32 ms                                                      | 8.71 ms: 1.19x slower                                                  |
| regex_effbot             | 2.99 ms                                                      | 3.59 ms: 1.20x slower                                                  |
| coverage                 | 64.0 ms                                                      | 82.4 ms: 1.29x slower                                                  |
| Geometric mean           | (ref)                                                        | 1.23x faster                                                           |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
