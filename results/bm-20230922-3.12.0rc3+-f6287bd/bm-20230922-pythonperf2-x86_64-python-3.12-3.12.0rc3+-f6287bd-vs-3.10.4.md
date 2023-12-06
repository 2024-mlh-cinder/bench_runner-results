
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 286 ms: 1.22x faster                                          |
| docutils       | 3.40 sec                                                     | 2.89 sec: 1.18x faster                                        |
| tornado_http   | 152 ms                                                       | 120 ms: 1.27x faster                                          |
| Geometric mean | (ref)                                                        | 1.22x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 91.0 ms: 1.51x faster                                         |
| float          | 110 ms                                                       | 79.0 ms: 1.40x faster                                         |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                        | 1.29x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 145 ms: 1.34x faster                                          |
| regex_v8       | 26.6 ms                                                      | 25.2 ms: 1.06x faster                                         |
| regex_dna      | 259 ms                                                       | 246 ms: 1.05x faster                                          |
| regex_effbot   | 2.99 ms                                                      | 3.47 ms: 1.16x slower                                         |
| Geometric mean | (ref)                                                        | 1.06x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 207 us: 1.55x faster                                          |
| pickle_pure_python   | 457 us                                                       | 324 us: 1.41x faster                                          |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                         |
| tomli_loads          | 2.97 sec                                                     | 2.17 sec: 1.37x faster                                        |
| xml_etree_process    | 76.0 ms                                                      | 59.1 ms: 1.29x faster                                         |
| json_loads           | 30.0 us                                                      | 24.6 us: 1.22x faster                                         |
| xml_etree_generate   | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                         |
| xml_etree_parse      | 162 ms                                                       | 148 ms: 1.09x faster                                          |
| xml_etree_iterparse  | 110 ms                                                       | 104 ms: 1.07x faster                                          |
| pickle               | 9.94 us                                                      | 10.2 us: 1.02x slower                                         |
| unpickle             | 14.2 us                                                      | 14.8 us: 1.04x slower                                         |
| unpickle_list        | 4.49 us                                                      | 4.74 us: 1.05x slower                                         |
| pickle_list          | 4.11 us                                                      | 4.39 us: 1.07x slower                                         |
| pickle_dict          | 30.0 us                                                      | 32.3 us: 1.08x slower                                         |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| python_startup_no_site | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                         |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-pythonperf2-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.47x faster                                          |
| deltablue                | 7.47 ms                                                      | 3.32 ms: 2.25x faster                                         |
| asyncio_tcp              | 782 ms                                                       | 379 ms: 2.07x faster                                          |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.96x faster                                        |
| logging_silent           | 166 ns                                                       | 94.6 ns: 1.75x faster                                         |
| richards_super           | 90.8 ms                                                      | 52.5 ms: 1.73x faster                                         |
| chaos                    | 107 ms                                                       | 63.3 ms: 1.69x faster                                         |
| go                       | 259 ms                                                       | 154 ms: 1.68x faster                                          |
| scimark_lu               | 164 ms                                                       | 102 ms: 1.61x faster                                          |
| sqlglot_parse            | 2.26 ms                                                      | 1.41 ms: 1.60x faster                                         |
| richards                 | 74.1 ms                                                      | 46.3 ms: 1.60x faster                                         |
| hexiom                   | 9.52 ms                                                      | 5.98 ms: 1.59x faster                                         |
| raytrace                 | 488 ms                                                       | 308 ms: 1.59x faster                                          |
| scimark_sor              | 177 ms                                                       | 112 ms: 1.58x faster                                          |
| generators               | 58.0 ms                                                      | 36.8 ms: 1.58x faster                                         |
| unpickle_pure_python     | 321 us                                                       | 207 us: 1.55x faster                                          |
| scimark_monte_carlo      | 109 ms                                                       | 70.8 ms: 1.55x faster                                         |
| async_tree_none          | 700 ms                                                       | 460 ms: 1.52x faster                                          |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                        |
| nbody                    | 137 ms                                                       | 91.0 ms: 1.51x faster                                         |
| spectral_norm            | 136 ms                                                       | 91.0 ms: 1.50x faster                                         |
| pyflate                  | 697 ms                                                       | 466 ms: 1.50x faster                                          |
| sqlglot_transpile        | 2.71 ms                                                      | 1.82 ms: 1.49x faster                                         |
| async_tree_memoization   | 824 ms                                                       | 556 ms: 1.48x faster                                          |
| mako                     | 14.7 ms                                                      | 10.1 ms: 1.46x faster                                         |
| crypto_pyaes             | 118 ms                                                       | 81.1 ms: 1.46x faster                                         |
| bench_mp_pool            | 7.18 ms                                                      | 5.08 ms: 1.41x faster                                         |
| fannkuch                 | 496 ms                                                       | 351 ms: 1.41x faster                                          |
| pickle_pure_python       | 457 us                                                       | 324 us: 1.41x faster                                          |
| json_dumps               | 14.2 ms                                                      | 10.2 ms: 1.40x faster                                         |
| float                    | 110 ms                                                       | 79.0 ms: 1.40x faster                                         |
| tomli_loads              | 2.97 sec                                                     | 2.17 sec: 1.37x faster                                        |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 706 ms: 1.35x faster                                          |
| regex_compile            | 194 ms                                                       | 145 ms: 1.34x faster                                          |
| logging_simple           | 8.90 us                                                      | 6.74 us: 1.32x faster                                         |
| coroutines               | 30.4 ms                                                      | 23.1 ms: 1.32x faster                                         |
| deepcopy_memo            | 48.9 us                                                      | 37.7 us: 1.30x faster                                         |
| pycparser                | 1.66 sec                                                     | 1.29 sec: 1.29x faster                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.67 sec: 1.29x faster                                        |
| xml_etree_process        | 76.0 ms                                                      | 59.1 ms: 1.29x faster                                         |
| pprint_safe_repr         | 1.05 sec                                                     | 817 ms: 1.28x faster                                          |
| tornado_http             | 152 ms                                                       | 120 ms: 1.27x faster                                          |
| mypy2                    | 466 ms                                                       | 368 ms: 1.27x faster                                          |
| logging_format           | 9.57 us                                                      | 7.58 us: 1.26x faster                                         |
| comprehensions           | 26.9 us                                                      | 21.6 us: 1.25x faster                                         |
| sqlglot_normalize        | 144 ms                                                       | 118 ms: 1.23x faster                                          |
| unpack_sequence          | 59.5 ns                                                      | 48.6 ns: 1.22x faster                                         |
| 2to3                     | 350 ms                                                       | 286 ms: 1.22x faster                                          |
| nqueens                  | 112 ms                                                       | 92.1 ms: 1.22x faster                                         |
| dulwich_log              | 80.1 ms                                                      | 65.7 ms: 1.22x faster                                         |
| json_loads               | 30.0 us                                                      | 24.6 us: 1.22x faster                                         |
| sqlglot_optimize         | 70.3 ms                                                      | 58.0 ms: 1.21x faster                                         |
| mdp                      | 3.03 sec                                                     | 2.54 sec: 1.20x faster                                        |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.36 ms: 1.19x faster                                         |
| bench_thread_pool        | 1.14 ms                                                      | 960 us: 1.18x faster                                          |
| deepcopy                 | 454 us                                                       | 384 us: 1.18x faster                                          |
| docutils                 | 3.40 sec                                                     | 2.89 sec: 1.18x faster                                        |
| scimark_fft              | 359 ms                                                       | 306 ms: 1.17x faster                                          |
| dask                     | 463 ms                                                       | 397 ms: 1.17x faster                                          |
| deepcopy_reduce          | 4.03 us                                                      | 3.47 us: 1.16x faster                                         |
| json                     | 5.96 ms                                                      | 5.19 ms: 1.15x faster                                         |
| pathlib                  | 21.7 ms                                                      | 19.5 ms: 1.11x faster                                         |
| xml_etree_generate       | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                         |
| create_gc_cycles         | 1.82 ms                                                      | 1.66 ms: 1.09x faster                                         |
| xml_etree_parse          | 162 ms                                                       | 148 ms: 1.09x faster                                          |
| meteor_contest           | 137 ms                                                       | 125 ms: 1.09x faster                                          |
| sqlite_synth             | 2.97 us                                                      | 2.75 us: 1.08x faster                                         |
| async_generators         | 422 ms                                                       | 391 ms: 1.08x faster                                          |
| xml_etree_iterparse      | 110 ms                                                       | 104 ms: 1.07x faster                                          |
| regex_v8                 | 26.6 ms                                                      | 25.2 ms: 1.06x faster                                         |
| regex_dna                | 259 ms                                                       | 246 ms: 1.05x faster                                          |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                          |
| telco                    | 7.14 ms                                                      | 6.98 ms: 1.02x faster                                         |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                         |
| pickle                   | 9.94 us                                                      | 10.2 us: 1.02x slower                                         |
| gc_traversal             | 3.45 ms                                                      | 3.55 ms: 1.03x slower                                         |
| unpickle                 | 14.2 us                                                      | 14.8 us: 1.04x slower                                         |
| unpickle_list            | 4.49 us                                                      | 4.74 us: 1.05x slower                                         |
| pickle_list              | 4.11 us                                                      | 4.39 us: 1.07x slower                                         |
| pickle_dict              | 30.0 us                                                      | 32.3 us: 1.08x slower                                         |
| regex_effbot             | 2.99 ms                                                      | 3.47 ms: 1.16x slower                                         |
| python_startup_no_site   | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                         |
| coverage                 | 64.0 ms                                                      | 90.5 ms: 1.41x slower                                         |
| Geometric mean           | (ref)                                                        | 1.29x faster                                                  |
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.22x
