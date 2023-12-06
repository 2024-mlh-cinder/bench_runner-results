
# Results vs. 3.10.4

- fork: colesbury
- ref: biased_reference_cou
- machine: linux-x86_64
- commit hash: 2144e0e
- commit date: 2023-10-12
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.87 sec: 1.18x faster                                                         |
| tornado_http   | 152 ms                                                       | 119 ms: 1.28x faster                                                           |
| Geometric mean | (ref)                                                        | 1.23x faster                                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 90.5 ms: 1.52x faster                                                          |
| float          | 110 ms                                                       | 81.8 ms: 1.35x faster                                                          |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                                           |
| Geometric mean | (ref)                                                        | 1.28x faster                                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 147 ms: 1.31x faster                                                           |
| regex_v8       | 26.6 ms                                                      | 24.6 ms: 1.08x faster                                                          |
| regex_dna      | 259 ms                                                       | 245 ms: 1.06x faster                                                           |
| regex_effbot   | 2.99 ms                                                      | 3.36 ms: 1.12x slower                                                          |
| Geometric mean | (ref)                                                        | 1.08x faster                                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 316 us: 1.45x faster                                                           |
| unpickle_pure_python | 321 us                                                       | 230 us: 1.39x faster                                                           |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                                          |
| tomli_loads          | 2.97 sec                                                     | 2.22 sec: 1.34x faster                                                         |
| xml_etree_process    | 76.0 ms                                                      | 60.0 ms: 1.27x faster                                                          |
| json_loads           | 30.0 us                                                      | 24.2 us: 1.24x faster                                                          |
| xml_etree_generate   | 94.6 ms                                                      | 86.5 ms: 1.09x faster                                                          |
| xml_etree_parse      | 162 ms                                                       | 148 ms: 1.09x faster                                                           |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                                           |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                                          |
| unpickle             | 14.2 us                                                      | 14.4 us: 1.02x slower                                                          |
| unpickle_list        | 4.49 us                                                      | 4.63 us: 1.03x slower                                                          |
| pickle_dict          | 30.0 us                                                      | 31.9 us: 1.06x slower                                                          |
| pickle_list          | 4.11 us                                                      | 4.43 us: 1.08x slower                                                          |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                          |
| python_startup_no_site | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                                          |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.46x faster                                                           |
| asyncio_tcp              | 782 ms                                                       | 369 ms: 2.12x faster                                                           |
| deltablue                | 7.47 ms                                                      | 3.71 ms: 2.02x faster                                                          |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                                         |
| chaos                    | 107 ms                                                       | 61.0 ms: 1.76x faster                                                          |
| raytrace                 | 488 ms                                                       | 282 ms: 1.73x faster                                                           |
| logging_silent           | 166 ns                                                       | 98.1 ns: 1.69x faster                                                          |
| crypto_pyaes             | 118 ms                                                       | 72.0 ms: 1.64x faster                                                          |
| generators               | 58.0 ms                                                      | 35.6 ms: 1.63x faster                                                          |
| scimark_lu               | 164 ms                                                       | 101 ms: 1.62x faster                                                           |
| async_tree_none          | 700 ms                                                       | 437 ms: 1.60x faster                                                           |
| sqlglot_parse            | 2.26 ms                                                      | 1.43 ms: 1.58x faster                                                          |
| bench_mp_pool            | 7.18 ms                                                      | 4.58 ms: 1.57x faster                                                          |
| richards_super           | 90.8 ms                                                      | 59.6 ms: 1.52x faster                                                          |
| scimark_monte_carlo      | 109 ms                                                       | 72.1 ms: 1.52x faster                                                          |
| nbody                    | 137 ms                                                       | 90.5 ms: 1.52x faster                                                          |
| spectral_norm            | 136 ms                                                       | 91.1 ms: 1.50x faster                                                          |
| go                       | 259 ms                                                       | 173 ms: 1.49x faster                                                           |
| async_tree_memoization   | 824 ms                                                       | 553 ms: 1.49x faster                                                           |
| hexiom                   | 9.52 ms                                                      | 6.42 ms: 1.48x faster                                                          |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.48x faster                                                         |
| sqlglot_transpile        | 2.71 ms                                                      | 1.83 ms: 1.48x faster                                                          |
| pickle_pure_python       | 457 us                                                       | 316 us: 1.45x faster                                                           |
| mako                     | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                                          |
| unpickle_pure_python     | 321 us                                                       | 230 us: 1.39x faster                                                           |
| richards                 | 74.1 ms                                                      | 54.0 ms: 1.37x faster                                                          |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                                          |
| pyflate                  | 697 ms                                                       | 511 ms: 1.36x faster                                                           |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 704 ms: 1.35x faster                                                           |
| float                    | 110 ms                                                       | 81.8 ms: 1.35x faster                                                          |
| tomli_loads              | 2.97 sec                                                     | 2.22 sec: 1.34x faster                                                         |
| regex_compile            | 194 ms                                                       | 147 ms: 1.31x faster                                                           |
| logging_simple           | 8.90 us                                                      | 6.78 us: 1.31x faster                                                          |
| logging_format           | 9.57 us                                                      | 7.33 us: 1.31x faster                                                          |
| coroutines               | 30.4 ms                                                      | 23.3 ms: 1.30x faster                                                          |
| deepcopy_memo            | 48.9 us                                                      | 37.5 us: 1.30x faster                                                          |
| nqueens                  | 112 ms                                                       | 87.2 ms: 1.29x faster                                                          |
| tornado_http             | 152 ms                                                       | 119 ms: 1.28x faster                                                           |
| pprint_pformat           | 2.15 sec                                                     | 1.69 sec: 1.27x faster                                                         |
| pycparser                | 1.66 sec                                                     | 1.31 sec: 1.27x faster                                                         |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.09 ms: 1.27x faster                                                          |
| xml_etree_process        | 76.0 ms                                                      | 60.0 ms: 1.27x faster                                                          |
| pprint_safe_repr         | 1.05 sec                                                     | 834 ms: 1.26x faster                                                           |
| fannkuch                 | 496 ms                                                       | 396 ms: 1.25x faster                                                           |
| sqlglot_normalize        | 144 ms                                                       | 116 ms: 1.25x faster                                                           |
| mypy2                    | 466 ms                                                       | 374 ms: 1.25x faster                                                           |
| json_loads               | 30.0 us                                                      | 24.2 us: 1.24x faster                                                          |
| scimark_fft              | 359 ms                                                       | 294 ms: 1.22x faster                                                           |
| comprehensions           | 26.9 us                                                      | 22.1 us: 1.22x faster                                                          |
| deepcopy                 | 454 us                                                       | 374 us: 1.21x faster                                                           |
| deepcopy_reduce          | 4.03 us                                                      | 3.34 us: 1.21x faster                                                          |
| unpack_sequence          | 59.5 ns                                                      | 49.6 ns: 1.20x faster                                                          |
| sqlglot_optimize         | 70.3 ms                                                      | 58.7 ms: 1.20x faster                                                          |
| scimark_sor              | 177 ms                                                       | 148 ms: 1.20x faster                                                           |
| docutils                 | 3.40 sec                                                     | 2.87 sec: 1.18x faster                                                         |
| mdp                      | 3.03 sec                                                     | 2.57 sec: 1.18x faster                                                         |
| bench_thread_pool        | 1.14 ms                                                      | 964 us: 1.18x faster                                                           |
| json                     | 5.96 ms                                                      | 5.12 ms: 1.16x faster                                                          |
| dulwich_log              | 80.1 ms                                                      | 69.7 ms: 1.15x faster                                                          |
| pathlib                  | 21.7 ms                                                      | 19.4 ms: 1.12x faster                                                          |
| sqlite_synth             | 2.97 us                                                      | 2.67 us: 1.11x faster                                                          |
| xml_etree_generate       | 94.6 ms                                                      | 86.5 ms: 1.09x faster                                                          |
| xml_etree_parse          | 162 ms                                                       | 148 ms: 1.09x faster                                                           |
| regex_v8                 | 26.6 ms                                                      | 24.6 ms: 1.08x faster                                                          |
| create_gc_cycles         | 1.82 ms                                                      | 1.68 ms: 1.08x faster                                                          |
| async_generators         | 422 ms                                                       | 392 ms: 1.08x faster                                                           |
| regex_dna                | 259 ms                                                       | 245 ms: 1.06x faster                                                           |
| meteor_contest           | 137 ms                                                       | 129 ms: 1.06x faster                                                           |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                                           |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                                           |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                                          |
| unpickle                 | 14.2 us                                                      | 14.4 us: 1.02x slower                                                          |
| unpickle_list            | 4.49 us                                                      | 4.63 us: 1.03x slower                                                          |
| pickle_dict              | 30.0 us                                                      | 31.9 us: 1.06x slower                                                          |
| pickle_list              | 4.11 us                                                      | 4.43 us: 1.08x slower                                                          |
| gc_traversal             | 3.45 ms                                                      | 3.76 ms: 1.09x slower                                                          |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                          |
| regex_effbot             | 2.99 ms                                                      | 3.36 ms: 1.12x slower                                                          |
| telco                    | 7.14 ms                                                      | 8.07 ms: 1.13x slower                                                          |
| python_startup_no_site   | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                                          |
| coverage                 | 64.0 ms                                                      | 82.2 ms: 1.29x slower                                                          |
| Geometric mean           | (ref)                                                        | 1.28x faster                                                                   |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
