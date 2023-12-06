
# Results vs. 3.10.4

- fork: python
- ref: 19b7ead5eb2fd1a0d194
- machine: linux-x86_64
- commit hash: 19b7ead
- commit date: 2023-10-12
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                                      |
| tornado_http   | 152 ms                                                       | 120 ms: 1.27x faster                                                        |
| Geometric mean | (ref)                                                        | 1.23x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 88.5 ms: 1.55x faster                                                       |
| float          | 110 ms                                                       | 80.3 ms: 1.37x faster                                                       |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                                        |
| Geometric mean | (ref)                                                        | 1.30x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 149 ms: 1.30x faster                                                        |
| regex_dna      | 259 ms                                                       | 238 ms: 1.09x faster                                                        |
| regex_v8       | 26.6 ms                                                      | 24.9 ms: 1.07x faster                                                       |
| regex_effbot   | 2.99 ms                                                      | 3.46 ms: 1.16x slower                                                       |
| Geometric mean | (ref)                                                        | 1.07x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 312 us: 1.47x faster                                                        |
| unpickle_pure_python | 321 us                                                       | 227 us: 1.41x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                                       |
| xml_etree_process    | 76.0 ms                                                      | 58.0 ms: 1.31x faster                                                       |
| tomli_loads          | 2.97 sec                                                     | 2.36 sec: 1.26x faster                                                      |
| json_loads           | 30.0 us                                                      | 24.2 us: 1.24x faster                                                       |
| xml_etree_generate   | 94.6 ms                                                      | 84.8 ms: 1.12x faster                                                       |
| xml_etree_parse      | 162 ms                                                       | 149 ms: 1.08x faster                                                        |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.03x faster                                                        |
| pickle               | 9.94 us                                                      | 10.2 us: 1.03x slower                                                       |
| unpickle_list        | 4.49 us                                                      | 4.73 us: 1.05x slower                                                       |
| pickle_dict          | 30.0 us                                                      | 32.5 us: 1.08x slower                                                       |
| pickle_list          | 4.11 us                                                      | 4.45 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                                |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.47x faster                                                        |
| asyncio_tcp              | 782 ms                                                       | 366 ms: 2.14x faster                                                        |
| deltablue                | 7.47 ms                                                      | 3.66 ms: 2.04x faster                                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                                      |
| chaos                    | 107 ms                                                       | 61.2 ms: 1.75x faster                                                       |
| raytrace                 | 488 ms                                                       | 279 ms: 1.75x faster                                                        |
| logging_silent           | 166 ns                                                       | 97.3 ns: 1.70x faster                                                       |
| generators               | 58.0 ms                                                      | 35.2 ms: 1.65x faster                                                       |
| crypto_pyaes             | 118 ms                                                       | 72.1 ms: 1.64x faster                                                       |
| scimark_lu               | 164 ms                                                       | 102 ms: 1.61x faster                                                        |
| async_tree_none          | 700 ms                                                       | 437 ms: 1.60x faster                                                        |
| sqlglot_parse            | 2.26 ms                                                      | 1.41 ms: 1.60x faster                                                       |
| scimark_monte_carlo      | 109 ms                                                       | 69.8 ms: 1.57x faster                                                       |
| nbody                    | 137 ms                                                       | 88.5 ms: 1.55x faster                                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.67 ms: 1.54x faster                                                       |
| go                       | 259 ms                                                       | 170 ms: 1.53x faster                                                        |
| richards_super           | 90.8 ms                                                      | 60.2 ms: 1.51x faster                                                       |
| async_tree_memoization   | 824 ms                                                       | 552 ms: 1.49x faster                                                        |
| hexiom                   | 9.52 ms                                                      | 6.39 ms: 1.49x faster                                                       |
| sqlglot_transpile        | 2.71 ms                                                      | 1.82 ms: 1.49x faster                                                       |
| spectral_norm            | 136 ms                                                       | 91.7 ms: 1.49x faster                                                       |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                                      |
| pickle_pure_python       | 457 us                                                       | 312 us: 1.47x faster                                                        |
| mako                     | 14.7 ms                                                      | 10.3 ms: 1.43x faster                                                       |
| unpickle_pure_python     | 321 us                                                       | 227 us: 1.41x faster                                                        |
| float                    | 110 ms                                                       | 80.3 ms: 1.37x faster                                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 699 ms: 1.36x faster                                                        |
| pyflate                  | 697 ms                                                       | 514 ms: 1.36x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.5 ms: 1.35x faster                                                       |
| richards                 | 74.1 ms                                                      | 54.9 ms: 1.35x faster                                                       |
| deepcopy_memo            | 48.9 us                                                      | 37.0 us: 1.32x faster                                                       |
| xml_etree_process        | 76.0 ms                                                      | 58.0 ms: 1.31x faster                                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.65 sec: 1.30x faster                                                      |
| regex_compile            | 194 ms                                                       | 149 ms: 1.30x faster                                                        |
| pprint_safe_repr         | 1.05 sec                                                     | 809 ms: 1.30x faster                                                        |
| coroutines               | 30.4 ms                                                      | 23.5 ms: 1.30x faster                                                       |
| logging_simple           | 8.90 us                                                      | 6.88 us: 1.29x faster                                                       |
| pycparser                | 1.66 sec                                                     | 1.29 sec: 1.29x faster                                                      |
| nqueens                  | 112 ms                                                       | 88.1 ms: 1.28x faster                                                       |
| logging_format           | 9.57 us                                                      | 7.50 us: 1.28x faster                                                       |
| tornado_http             | 152 ms                                                       | 120 ms: 1.27x faster                                                        |
| fannkuch                 | 496 ms                                                       | 392 ms: 1.27x faster                                                        |
| tomli_loads              | 2.97 sec                                                     | 2.36 sec: 1.26x faster                                                      |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.12 ms: 1.26x faster                                                       |
| mypy2                    | 466 ms                                                       | 371 ms: 1.26x faster                                                        |
| sqlglot_normalize        | 144 ms                                                       | 116 ms: 1.24x faster                                                        |
| json_loads               | 30.0 us                                                      | 24.2 us: 1.24x faster                                                       |
| comprehensions           | 26.9 us                                                      | 22.0 us: 1.22x faster                                                       |
| deepcopy                 | 454 us                                                       | 375 us: 1.21x faster                                                        |
| scimark_fft              | 359 ms                                                       | 298 ms: 1.21x faster                                                        |
| sqlglot_optimize         | 70.3 ms                                                      | 58.4 ms: 1.20x faster                                                       |
| mdp                      | 3.03 sec                                                     | 2.52 sec: 1.20x faster                                                      |
| deepcopy_reduce          | 4.03 us                                                      | 3.37 us: 1.20x faster                                                       |
| scimark_sor              | 177 ms                                                       | 149 ms: 1.19x faster                                                        |
| docutils                 | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                                      |
| bench_thread_pool        | 1.14 ms                                                      | 962 us: 1.18x faster                                                        |
| json                     | 5.96 ms                                                      | 5.12 ms: 1.16x faster                                                       |
| dulwich_log              | 80.1 ms                                                      | 70.0 ms: 1.14x faster                                                       |
| xml_etree_generate       | 94.6 ms                                                      | 84.8 ms: 1.12x faster                                                       |
| pathlib                  | 21.7 ms                                                      | 19.5 ms: 1.11x faster                                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.64 ms: 1.11x faster                                                       |
| unpack_sequence          | 59.5 ns                                                      | 54.1 ns: 1.10x faster                                                       |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.10x faster                                                       |
| async_generators         | 422 ms                                                       | 386 ms: 1.09x faster                                                        |
| regex_dna                | 259 ms                                                       | 238 ms: 1.09x faster                                                        |
| xml_etree_parse          | 162 ms                                                       | 149 ms: 1.08x faster                                                        |
| regex_v8                 | 26.6 ms                                                      | 24.9 ms: 1.07x faster                                                       |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.03x faster                                                        |
| meteor_contest           | 137 ms                                                       | 133 ms: 1.03x faster                                                        |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                                        |
| pickle                   | 9.94 us                                                      | 10.2 us: 1.03x slower                                                       |
| unpickle_list            | 4.49 us                                                      | 4.73 us: 1.05x slower                                                       |
| gc_traversal             | 3.45 ms                                                      | 3.71 ms: 1.07x slower                                                       |
| pickle_dict              | 30.0 us                                                      | 32.5 us: 1.08x slower                                                       |
| pickle_list              | 4.11 us                                                      | 4.45 us: 1.08x slower                                                       |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                       |
| telco                    | 7.14 ms                                                      | 8.20 ms: 1.15x slower                                                       |
| regex_effbot             | 2.99 ms                                                      | 3.46 ms: 1.16x slower                                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.69 ms: 1.19x slower                                                       |
| coverage                 | 64.0 ms                                                      | 82.5 ms: 1.29x slower                                                       |
| Geometric mean           | (ref)                                                        | 1.28x faster                                                                |

Benchmark hidden because not significant (1): unpickle
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
