
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_o2
- machine: linux-x86_64
- commit hash: 2a353e9
- commit date: 2023-10-13
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.94 sec: 1.16x faster                                                 |
| tornado_http   | 152 ms                                                       | 124 ms: 1.22x faster                                                   |
| Geometric mean | (ref)                                                        | 1.19x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 102 ms: 1.35x faster                                                   |
| float          | 110 ms                                                       | 89.3 ms: 1.24x faster                                                  |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                        | 1.19x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 160 ms: 1.21x faster                                                   |
| regex_dna      | 259 ms                                                       | 245 ms: 1.06x faster                                                   |
| regex_v8       | 26.6 ms                                                      | 25.2 ms: 1.06x faster                                                  |
| regex_effbot   | 2.99 ms                                                      | 3.57 ms: 1.19x slower                                                  |
| Geometric mean | (ref)                                                        | 1.03x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 319 us: 1.43x faster                                                   |
| unpickle_pure_python | 321 us                                                       | 229 us: 1.40x faster                                                   |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                  |
| xml_etree_process    | 76.0 ms                                                      | 59.3 ms: 1.28x faster                                                  |
| json_loads           | 30.0 us                                                      | 24.5 us: 1.22x faster                                                  |
| tomli_loads          | 2.97 sec                                                     | 2.46 sec: 1.21x faster                                                 |
| xml_etree_generate   | 94.6 ms                                                      | 87.4 ms: 1.08x faster                                                  |
| xml_etree_parse      | 162 ms                                                       | 152 ms: 1.06x faster                                                   |
| xml_etree_iterparse  | 110 ms                                                       | 108 ms: 1.02x faster                                                   |
| pickle               | 9.94 us                                                      | 10.2 us: 1.02x slower                                                  |
| unpickle             | 14.2 us                                                      | 14.7 us: 1.04x slower                                                  |
| pickle_list          | 4.11 us                                                      | 4.30 us: 1.05x slower                                                  |
| unpickle_list        | 4.49 us                                                      | 4.75 us: 1.06x slower                                                  |
| pickle_dict          | 30.0 us                                                      | 33.0 us: 1.10x slower                                                  |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                                  |
| python_startup_no_site | 7.32 ms                                                      | 8.72 ms: 1.19x slower                                                  |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 12.1 ms: 1.22x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf2-x86_64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 155 us: 3.38x faster                                                   |
| asyncio_tcp              | 782 ms                                                       | 370 ms: 2.12x faster                                                   |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                                 |
| raytrace                 | 488 ms                                                       | 292 ms: 1.67x faster                                                   |
| logging_silent           | 166 ns                                                       | 99.9 ns: 1.66x faster                                                  |
| generators               | 58.0 ms                                                      | 36.4 ms: 1.59x faster                                                  |
| bench_mp_pool            | 7.18 ms                                                      | 4.55 ms: 1.58x faster                                                  |
| sqlglot_parse            | 2.26 ms                                                      | 1.43 ms: 1.58x faster                                                  |
| scimark_lu               | 164 ms                                                       | 105 ms: 1.57x faster                                                   |
| async_tree_none          | 700 ms                                                       | 449 ms: 1.56x faster                                                   |
| richards_super           | 90.8 ms                                                      | 58.4 ms: 1.55x faster                                                  |
| deltablue                | 7.47 ms                                                      | 4.89 ms: 1.53x faster                                                  |
| chaos                    | 107 ms                                                       | 70.3 ms: 1.52x faster                                                  |
| go                       | 259 ms                                                       | 176 ms: 1.47x faster                                                   |
| sqlglot_transpile        | 2.71 ms                                                      | 1.85 ms: 1.47x faster                                                  |
| async_tree_memoization   | 824 ms                                                       | 563 ms: 1.46x faster                                                   |
| scimark_monte_carlo      | 109 ms                                                       | 74.9 ms: 1.46x faster                                                  |
| async_tree_io            | 1.61 sec                                                     | 1.10 sec: 1.46x faster                                                 |
| spectral_norm            | 136 ms                                                       | 94.0 ms: 1.45x faster                                                  |
| pickle_pure_python       | 457 us                                                       | 319 us: 1.43x faster                                                   |
| richards                 | 74.1 ms                                                      | 52.3 ms: 1.42x faster                                                  |
| crypto_pyaes             | 118 ms                                                       | 83.6 ms: 1.41x faster                                                  |
| unpickle_pure_python     | 321 us                                                       | 229 us: 1.40x faster                                                   |
| nbody                    | 137 ms                                                       | 102 ms: 1.35x faster                                                   |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                  |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 716 ms: 1.33x faster                                                   |
| pyflate                  | 697 ms                                                       | 530 ms: 1.31x faster                                                   |
| coroutines               | 30.4 ms                                                      | 23.3 ms: 1.30x faster                                                  |
| logging_simple           | 8.90 us                                                      | 6.93 us: 1.28x faster                                                  |
| xml_etree_process        | 76.0 ms                                                      | 59.3 ms: 1.28x faster                                                  |
| logging_format           | 9.57 us                                                      | 7.64 us: 1.25x faster                                                  |
| pycparser                | 1.66 sec                                                     | 1.34 sec: 1.24x faster                                                 |
| float                    | 110 ms                                                       | 89.3 ms: 1.24x faster                                                  |
| unpack_sequence          | 59.5 ns                                                      | 48.3 ns: 1.23x faster                                                  |
| tornado_http             | 152 ms                                                       | 124 ms: 1.22x faster                                                   |
| json_loads               | 30.0 us                                                      | 24.5 us: 1.22x faster                                                  |
| mako                     | 14.7 ms                                                      | 12.1 ms: 1.22x faster                                                  |
| deepcopy_memo            | 48.9 us                                                      | 40.2 us: 1.22x faster                                                  |
| sqlglot_normalize        | 144 ms                                                       | 119 ms: 1.21x faster                                                   |
| deepcopy                 | 454 us                                                       | 374 us: 1.21x faster                                                   |
| mypy2                    | 466 ms                                                       | 384 ms: 1.21x faster                                                   |
| regex_compile            | 194 ms                                                       | 160 ms: 1.21x faster                                                   |
| deepcopy_reduce          | 4.03 us                                                      | 3.33 us: 1.21x faster                                                  |
| tomli_loads              | 2.97 sec                                                     | 2.46 sec: 1.21x faster                                                 |
| pprint_pformat           | 2.15 sec                                                     | 1.79 sec: 1.20x faster                                                 |
| pprint_safe_repr         | 1.05 sec                                                     | 878 ms: 1.20x faster                                                   |
| scimark_sor              | 177 ms                                                       | 151 ms: 1.17x faster                                                   |
| sqlglot_optimize         | 70.3 ms                                                      | 60.2 ms: 1.17x faster                                                  |
| mdp                      | 3.03 sec                                                     | 2.61 sec: 1.16x faster                                                 |
| docutils                 | 3.40 sec                                                     | 2.94 sec: 1.16x faster                                                 |
| json                     | 5.96 ms                                                      | 5.18 ms: 1.15x faster                                                  |
| dulwich_log              | 80.1 ms                                                      | 69.9 ms: 1.15x faster                                                  |
| bench_thread_pool        | 1.14 ms                                                      | 992 us: 1.15x faster                                                   |
| create_gc_cycles         | 1.82 ms                                                      | 1.61 ms: 1.13x faster                                                  |
| fannkuch                 | 496 ms                                                       | 440 ms: 1.13x faster                                                   |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.10x faster                                                  |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.75 ms: 1.09x faster                                                  |
| nqueens                  | 112 ms                                                       | 103 ms: 1.09x faster                                                   |
| xml_etree_generate       | 94.6 ms                                                      | 87.4 ms: 1.08x faster                                                  |
| pathlib                  | 21.7 ms                                                      | 20.2 ms: 1.07x faster                                                  |
| hexiom                   | 9.52 ms                                                      | 8.97 ms: 1.06x faster                                                  |
| xml_etree_parse          | 162 ms                                                       | 152 ms: 1.06x faster                                                   |
| regex_dna                | 259 ms                                                       | 245 ms: 1.06x faster                                                   |
| regex_v8                 | 26.6 ms                                                      | 25.2 ms: 1.06x faster                                                  |
| xml_etree_iterparse      | 110 ms                                                       | 108 ms: 1.02x faster                                                   |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                                   |
| scimark_fft              | 359 ms                                                       | 356 ms: 1.01x faster                                                   |
| async_generators         | 422 ms                                                       | 418 ms: 1.01x faster                                                   |
| meteor_contest           | 137 ms                                                       | 139 ms: 1.02x slower                                                   |
| pickle                   | 9.94 us                                                      | 10.2 us: 1.02x slower                                                  |
| unpickle                 | 14.2 us                                                      | 14.7 us: 1.04x slower                                                  |
| pickle_list              | 4.11 us                                                      | 4.30 us: 1.05x slower                                                  |
| unpickle_list            | 4.49 us                                                      | 4.75 us: 1.06x slower                                                  |
| comprehensions           | 26.9 us                                                      | 28.7 us: 1.07x slower                                                  |
| pickle_dict              | 30.0 us                                                      | 33.0 us: 1.10x slower                                                  |
| python_startup           | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                                  |
| gc_traversal             | 3.45 ms                                                      | 3.95 ms: 1.14x slower                                                  |
| telco                    | 7.14 ms                                                      | 8.30 ms: 1.16x slower                                                  |
| python_startup_no_site   | 7.32 ms                                                      | 8.72 ms: 1.19x slower                                                  |
| regex_effbot             | 2.99 ms                                                      | 3.57 ms: 1.19x slower                                                  |
| coverage                 | 64.0 ms                                                      | 86.1 ms: 1.35x slower                                                  |
| Geometric mean           | (ref)                                                        | 1.23x faster                                                           |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
