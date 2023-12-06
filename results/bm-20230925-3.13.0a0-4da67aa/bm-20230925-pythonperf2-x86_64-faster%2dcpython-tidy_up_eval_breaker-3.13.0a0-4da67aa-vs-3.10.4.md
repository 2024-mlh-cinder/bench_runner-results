
# Results vs. 3.10.4

- fork: faster-cpython
- ref: tidy_up_eval_breaker
- machine: linux-x86_64
- commit hash: 4da67aa
- commit date: 2023-09-25
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.87 sec: 1.19x faster                                                                |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                                                  |
| Geometric mean | (ref)                                                        | 1.22x faster                                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 86.7 ms: 1.58x faster                                                                 |
| float          | 110 ms                                                       | 81.2 ms: 1.36x faster                                                                 |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                                                  |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 149 ms: 1.30x faster                                                                  |
| regex_dna      | 259 ms                                                       | 250 ms: 1.04x faster                                                                  |
| regex_v8       | 26.6 ms                                                      | 26.0 ms: 1.03x faster                                                                 |
| regex_effbot   | 2.99 ms                                                      | 3.62 ms: 1.21x slower                                                                 |
| Geometric mean | (ref)                                                        | 1.03x faster                                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 318 us: 1.44x faster                                                                  |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                                                 |
| tomli_loads          | 2.97 sec                                                     | 2.21 sec: 1.35x faster                                                                |
| unpickle_pure_python | 321 us                                                       | 238 us: 1.35x faster                                                                  |
| xml_etree_process    | 76.0 ms                                                      | 58.5 ms: 1.30x faster                                                                 |
| json_loads           | 30.0 us                                                      | 24.7 us: 1.21x faster                                                                 |
| xml_etree_generate   | 94.6 ms                                                      | 86.0 ms: 1.10x faster                                                                 |
| xml_etree_parse      | 162 ms                                                       | 153 ms: 1.05x faster                                                                  |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.03x faster                                                                  |
| pickle               | 9.94 us                                                      | 10.0 us: 1.01x slower                                                                 |
| unpickle             | 14.2 us                                                      | 15.0 us: 1.06x slower                                                                 |
| pickle_list          | 4.11 us                                                      | 4.36 us: 1.06x slower                                                                 |
| pickle_dict          | 30.0 us                                                      | 32.0 us: 1.07x slower                                                                 |
| unpickle_list        | 4.49 us                                                      | 4.84 us: 1.08x slower                                                                 |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                                                 |
| python_startup_no_site | 7.32 ms                                                      | 8.68 ms: 1.19x slower                                                                 |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230925-pythonperf2-x86_64-faster%2dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.48x faster                                                                  |
| asyncio_tcp              | 782 ms                                                       | 368 ms: 2.13x faster                                                                  |
| deltablue                | 7.47 ms                                                      | 3.64 ms: 2.05x faster                                                                 |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                                                |
| raytrace                 | 488 ms                                                       | 281 ms: 1.74x faster                                                                  |
| chaos                    | 107 ms                                                       | 63.0 ms: 1.70x faster                                                                 |
| logging_silent           | 166 ns                                                       | 97.6 ns: 1.70x faster                                                                 |
| generators               | 58.0 ms                                                      | 35.3 ms: 1.64x faster                                                                 |
| scimark_monte_carlo      | 109 ms                                                       | 66.9 ms: 1.64x faster                                                                 |
| sqlglot_parse            | 2.26 ms                                                      | 1.39 ms: 1.62x faster                                                                 |
| scimark_lu               | 164 ms                                                       | 101 ms: 1.62x faster                                                                  |
| crypto_pyaes             | 118 ms                                                       | 73.4 ms: 1.61x faster                                                                 |
| async_tree_none          | 700 ms                                                       | 436 ms: 1.60x faster                                                                  |
| nbody                    | 137 ms                                                       | 86.7 ms: 1.58x faster                                                                 |
| sqlglot_transpile        | 2.71 ms                                                      | 1.79 ms: 1.51x faster                                                                 |
| go                       | 259 ms                                                       | 171 ms: 1.51x faster                                                                  |
| async_tree_memoization   | 824 ms                                                       | 549 ms: 1.50x faster                                                                  |
| spectral_norm            | 136 ms                                                       | 90.9 ms: 1.50x faster                                                                 |
| richards_super           | 90.8 ms                                                      | 60.9 ms: 1.49x faster                                                                 |
| hexiom                   | 9.52 ms                                                      | 6.39 ms: 1.49x faster                                                                 |
| bench_mp_pool            | 7.18 ms                                                      | 4.83 ms: 1.49x faster                                                                 |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                                                |
| pickle_pure_python       | 457 us                                                       | 318 us: 1.44x faster                                                                  |
| mako                     | 14.7 ms                                                      | 10.4 ms: 1.42x faster                                                                 |
| pyflate                  | 697 ms                                                       | 508 ms: 1.37x faster                                                                  |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                                                 |
| float                    | 110 ms                                                       | 81.2 ms: 1.36x faster                                                                 |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 701 ms: 1.36x faster                                                                  |
| richards                 | 74.1 ms                                                      | 54.8 ms: 1.35x faster                                                                 |
| tomli_loads              | 2.97 sec                                                     | 2.21 sec: 1.35x faster                                                                |
| unpickle_pure_python     | 321 us                                                       | 238 us: 1.35x faster                                                                  |
| unpack_sequence          | 59.5 ns                                                      | 44.5 ns: 1.34x faster                                                                 |
| coroutines               | 30.4 ms                                                      | 22.9 ms: 1.33x faster                                                                 |
| logging_simple           | 8.90 us                                                      | 6.71 us: 1.33x faster                                                                 |
| deepcopy_memo            | 48.9 us                                                      | 37.0 us: 1.32x faster                                                                 |
| logging_format           | 9.57 us                                                      | 7.36 us: 1.30x faster                                                                 |
| regex_compile            | 194 ms                                                       | 149 ms: 1.30x faster                                                                  |
| xml_etree_process        | 76.0 ms                                                      | 58.5 ms: 1.30x faster                                                                 |
| pprint_pformat           | 2.15 sec                                                     | 1.68 sec: 1.28x faster                                                                |
| pprint_safe_repr         | 1.05 sec                                                     | 821 ms: 1.28x faster                                                                  |
| nqueens                  | 112 ms                                                       | 88.0 ms: 1.28x faster                                                                 |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.06 ms: 1.28x faster                                                                 |
| fannkuch                 | 496 ms                                                       | 393 ms: 1.26x faster                                                                  |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                                                  |
| mypy2                    | 466 ms                                                       | 372 ms: 1.26x faster                                                                  |
| pycparser                | 1.66 sec                                                     | 1.34 sec: 1.24x faster                                                                |
| sqlglot_normalize        | 144 ms                                                       | 116 ms: 1.24x faster                                                                  |
| comprehensions           | 26.9 us                                                      | 22.1 us: 1.22x faster                                                                 |
| json_loads               | 30.0 us                                                      | 24.7 us: 1.21x faster                                                                 |
| mdp                      | 3.03 sec                                                     | 2.52 sec: 1.21x faster                                                                |
| deepcopy                 | 454 us                                                       | 379 us: 1.20x faster                                                                  |
| scimark_sor              | 177 ms                                                       | 148 ms: 1.20x faster                                                                  |
| sqlglot_optimize         | 70.3 ms                                                      | 58.7 ms: 1.20x faster                                                                 |
| docutils                 | 3.40 sec                                                     | 2.87 sec: 1.19x faster                                                                |
| bench_thread_pool        | 1.14 ms                                                      | 963 us: 1.18x faster                                                                  |
| deepcopy_reduce          | 4.03 us                                                      | 3.42 us: 1.18x faster                                                                 |
| json                     | 5.96 ms                                                      | 5.10 ms: 1.17x faster                                                                 |
| scimark_fft              | 359 ms                                                       | 310 ms: 1.16x faster                                                                  |
| dulwich_log              | 80.1 ms                                                      | 69.6 ms: 1.15x faster                                                                 |
| pathlib                  | 21.7 ms                                                      | 19.3 ms: 1.12x faster                                                                 |
| sqlite_synth             | 2.97 us                                                      | 2.66 us: 1.11x faster                                                                 |
| xml_etree_generate       | 94.6 ms                                                      | 86.0 ms: 1.10x faster                                                                 |
| create_gc_cycles         | 1.82 ms                                                      | 1.68 ms: 1.08x faster                                                                 |
| async_generators         | 422 ms                                                       | 395 ms: 1.07x faster                                                                  |
| xml_etree_parse          | 162 ms                                                       | 153 ms: 1.05x faster                                                                  |
| meteor_contest           | 137 ms                                                       | 131 ms: 1.04x faster                                                                  |
| regex_dna                | 259 ms                                                       | 250 ms: 1.04x faster                                                                  |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.03x faster                                                                  |
| regex_v8                 | 26.6 ms                                                      | 26.0 ms: 1.03x faster                                                                 |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                                                  |
| pickle                   | 9.94 us                                                      | 10.0 us: 1.01x slower                                                                 |
| gc_traversal             | 3.45 ms                                                      | 3.58 ms: 1.04x slower                                                                 |
| unpickle                 | 14.2 us                                                      | 15.0 us: 1.06x slower                                                                 |
| pickle_list              | 4.11 us                                                      | 4.36 us: 1.06x slower                                                                 |
| pickle_dict              | 30.0 us                                                      | 32.0 us: 1.07x slower                                                                 |
| unpickle_list            | 4.49 us                                                      | 4.84 us: 1.08x slower                                                                 |
| python_startup           | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                                                 |
| telco                    | 7.14 ms                                                      | 7.99 ms: 1.12x slower                                                                 |
| python_startup_no_site   | 7.32 ms                                                      | 8.68 ms: 1.19x slower                                                                 |
| regex_effbot             | 2.99 ms                                                      | 3.62 ms: 1.21x slower                                                                 |
| coverage                 | 64.0 ms                                                      | 78.4 ms: 1.23x slower                                                                 |
| dask                     | 463 ms                                                       | 587 ms: 1.27x slower                                                                  |
| Geometric mean           | (ref)                                                        | 1.27x faster                                                                          |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
