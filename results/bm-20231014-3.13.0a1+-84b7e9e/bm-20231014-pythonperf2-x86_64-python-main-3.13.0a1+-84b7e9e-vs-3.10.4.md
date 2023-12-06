
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.87 sec: 1.18x faster                                       |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                         |
| Geometric mean | (ref)                                                        | 1.22x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 86.0 ms: 1.60x faster                                        |
| float          | 110 ms                                                       | 81.4 ms: 1.36x faster                                        |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                        | 1.30x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 148 ms: 1.31x faster                                         |
| regex_dna      | 259 ms                                                       | 240 ms: 1.08x faster                                         |
| regex_v8       | 26.6 ms                                                      | 25.3 ms: 1.05x faster                                        |
| regex_effbot   | 2.99 ms                                                      | 3.56 ms: 1.19x slower                                        |
| Geometric mean | (ref)                                                        | 1.06x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 219 us: 1.46x faster                                         |
| pickle_pure_python   | 457 us                                                       | 320 us: 1.43x faster                                         |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                        |
| xml_etree_process    | 76.0 ms                                                      | 58.4 ms: 1.30x faster                                        |
| tomli_loads          | 2.97 sec                                                     | 2.32 sec: 1.28x faster                                       |
| json_loads           | 30.0 us                                                      | 24.3 us: 1.23x faster                                        |
| xml_etree_generate   | 94.6 ms                                                      | 85.3 ms: 1.11x faster                                        |
| xml_etree_parse      | 162 ms                                                       | 147 ms: 1.10x faster                                         |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.05x faster                                         |
| pickle_list          | 4.11 us                                                      | 4.15 us: 1.01x slower                                        |
| pickle               | 9.94 us                                                      | 10.2 us: 1.02x slower                                        |
| unpickle             | 14.2 us                                                      | 14.6 us: 1.03x slower                                        |
| pickle_dict          | 30.0 us                                                      | 31.9 us: 1.06x slower                                        |
| unpickle_list        | 4.49 us                                                      | 4.82 us: 1.07x slower                                        |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.09x slower                                        |
| python_startup_no_site | 7.32 ms                                                      | 8.66 ms: 1.18x slower                                        |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.5 ms: 1.40x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf2-x86_64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.46x faster                                         |
| asyncio_tcp              | 782 ms                                                       | 368 ms: 2.13x faster                                         |
| deltablue                | 7.47 ms                                                      | 3.62 ms: 2.06x faster                                        |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.61 sec: 1.92x faster                                       |
| raytrace                 | 488 ms                                                       | 275 ms: 1.78x faster                                         |
| logging_silent           | 166 ns                                                       | 96.9 ns: 1.71x faster                                        |
| chaos                    | 107 ms                                                       | 62.7 ms: 1.71x faster                                        |
| scimark_monte_carlo      | 109 ms                                                       | 66.5 ms: 1.65x faster                                        |
| generators               | 58.0 ms                                                      | 35.5 ms: 1.63x faster                                        |
| crypto_pyaes             | 118 ms                                                       | 73.1 ms: 1.62x faster                                        |
| async_tree_none          | 700 ms                                                       | 434 ms: 1.61x faster                                         |
| scimark_lu               | 164 ms                                                       | 102 ms: 1.61x faster                                         |
| sqlglot_parse            | 2.26 ms                                                      | 1.40 ms: 1.61x faster                                        |
| nbody                    | 137 ms                                                       | 86.0 ms: 1.60x faster                                        |
| bench_mp_pool            | 7.18 ms                                                      | 4.69 ms: 1.53x faster                                        |
| go                       | 259 ms                                                       | 171 ms: 1.51x faster                                         |
| async_tree_memoization   | 824 ms                                                       | 548 ms: 1.50x faster                                         |
| sqlglot_transpile        | 2.71 ms                                                      | 1.81 ms: 1.50x faster                                        |
| richards_super           | 90.8 ms                                                      | 60.8 ms: 1.49x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                       |
| hexiom                   | 9.52 ms                                                      | 6.39 ms: 1.49x faster                                        |
| unpickle_pure_python     | 321 us                                                       | 219 us: 1.46x faster                                         |
| spectral_norm            | 136 ms                                                       | 93.6 ms: 1.46x faster                                        |
| pickle_pure_python       | 457 us                                                       | 320 us: 1.43x faster                                         |
| mako                     | 14.7 ms                                                      | 10.5 ms: 1.40x faster                                        |
| pyflate                  | 697 ms                                                       | 510 ms: 1.37x faster                                         |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 701 ms: 1.36x faster                                         |
| float                    | 110 ms                                                       | 81.4 ms: 1.36x faster                                        |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                        |
| richards                 | 74.1 ms                                                      | 55.4 ms: 1.34x faster                                        |
| regex_compile            | 194 ms                                                       | 148 ms: 1.31x faster                                         |
| coroutines               | 30.4 ms                                                      | 23.3 ms: 1.30x faster                                        |
| xml_etree_process        | 76.0 ms                                                      | 58.4 ms: 1.30x faster                                        |
| deepcopy_memo            | 48.9 us                                                      | 37.7 us: 1.30x faster                                        |
| pycparser                | 1.66 sec                                                     | 1.28 sec: 1.30x faster                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.67 sec: 1.29x faster                                       |
| pprint_safe_repr         | 1.05 sec                                                     | 815 ms: 1.29x faster                                         |
| logging_simple           | 8.90 us                                                      | 6.93 us: 1.28x faster                                        |
| tomli_loads              | 2.97 sec                                                     | 2.32 sec: 1.28x faster                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.06 ms: 1.28x faster                                        |
| nqueens                  | 112 ms                                                       | 88.6 ms: 1.27x faster                                        |
| mypy2                    | 466 ms                                                       | 370 ms: 1.26x faster                                         |
| logging_format           | 9.57 us                                                      | 7.59 us: 1.26x faster                                        |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                         |
| fannkuch                 | 496 ms                                                       | 399 ms: 1.24x faster                                         |
| sqlglot_normalize        | 144 ms                                                       | 117 ms: 1.24x faster                                         |
| comprehensions           | 26.9 us                                                      | 21.8 us: 1.23x faster                                        |
| json_loads               | 30.0 us                                                      | 24.3 us: 1.23x faster                                        |
| scimark_sor              | 177 ms                                                       | 145 ms: 1.22x faster                                         |
| deepcopy_reduce          | 4.03 us                                                      | 3.32 us: 1.21x faster                                        |
| deepcopy                 | 454 us                                                       | 375 us: 1.21x faster                                         |
| mdp                      | 3.03 sec                                                     | 2.54 sec: 1.19x faster                                       |
| sqlglot_optimize         | 70.3 ms                                                      | 59.2 ms: 1.19x faster                                        |
| docutils                 | 3.40 sec                                                     | 2.87 sec: 1.18x faster                                       |
| scimark_fft              | 359 ms                                                       | 307 ms: 1.17x faster                                         |
| json                     | 5.96 ms                                                      | 5.11 ms: 1.17x faster                                        |
| dulwich_log              | 80.1 ms                                                      | 69.1 ms: 1.16x faster                                        |
| bench_thread_pool        | 1.14 ms                                                      | 986 us: 1.15x faster                                         |
| pathlib                  | 21.7 ms                                                      | 19.6 ms: 1.11x faster                                        |
| xml_etree_generate       | 94.6 ms                                                      | 85.3 ms: 1.11x faster                                        |
| xml_etree_parse          | 162 ms                                                       | 147 ms: 1.10x faster                                         |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                        |
| create_gc_cycles         | 1.82 ms                                                      | 1.67 ms: 1.09x faster                                        |
| unpack_sequence          | 59.5 ns                                                      | 55.1 ns: 1.08x faster                                        |
| regex_dna                | 259 ms                                                       | 240 ms: 1.08x faster                                         |
| async_generators         | 422 ms                                                       | 392 ms: 1.08x faster                                         |
| regex_v8                 | 26.6 ms                                                      | 25.3 ms: 1.05x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.05x faster                                         |
| meteor_contest           | 137 ms                                                       | 131 ms: 1.04x faster                                         |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                         |
| pickle_list              | 4.11 us                                                      | 4.15 us: 1.01x slower                                        |
| pickle                   | 9.94 us                                                      | 10.2 us: 1.02x slower                                        |
| gc_traversal             | 3.45 ms                                                      | 3.54 ms: 1.03x slower                                        |
| unpickle                 | 14.2 us                                                      | 14.6 us: 1.03x slower                                        |
| pickle_dict              | 30.0 us                                                      | 31.9 us: 1.06x slower                                        |
| unpickle_list            | 4.49 us                                                      | 4.82 us: 1.07x slower                                        |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.09x slower                                        |
| telco                    | 7.14 ms                                                      | 8.11 ms: 1.14x slower                                        |
| python_startup_no_site   | 7.32 ms                                                      | 8.66 ms: 1.18x slower                                        |
| regex_effbot             | 2.99 ms                                                      | 3.56 ms: 1.19x slower                                        |
| coverage                 | 64.0 ms                                                      | 85.7 ms: 1.34x slower                                        |
| Geometric mean           | (ref)                                                        | 1.28x faster                                                 |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
