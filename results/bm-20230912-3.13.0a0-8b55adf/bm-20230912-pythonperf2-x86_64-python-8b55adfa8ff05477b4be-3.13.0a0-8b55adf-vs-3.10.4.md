
# Results vs. 3.10.4

- fork: python
- ref: 8b55adfa8ff05477b4be
- machine: linux-x86_64
- commit hash: 8b55adf
- commit date: 2023-09-12
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                                      |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                                        |
| Geometric mean | (ref)                                                        | 1.22x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 85.9 ms: 1.60x faster                                                       |
| float          | 110 ms                                                       | 80.9 ms: 1.36x faster                                                       |
| pidigits       | 271 ms                                                       | 263 ms: 1.03x faster                                                        |
| Geometric mean | (ref)                                                        | 1.31x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 149 ms: 1.30x faster                                                        |
| regex_v8       | 26.6 ms                                                      | 24.6 ms: 1.08x faster                                                       |
| regex_dna      | 259 ms                                                       | 240 ms: 1.08x faster                                                        |
| regex_effbot   | 2.99 ms                                                      | 3.66 ms: 1.22x slower                                                       |
| Geometric mean | (ref)                                                        | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 314 us: 1.45x faster                                                        |
| unpickle_pure_python | 321 us                                                       | 228 us: 1.41x faster                                                        |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                                       |
| tomli_loads          | 2.97 sec                                                     | 2.19 sec: 1.35x faster                                                      |
| xml_etree_process    | 76.0 ms                                                      | 58.3 ms: 1.30x faster                                                       |
| json_loads           | 30.0 us                                                      | 25.2 us: 1.19x faster                                                       |
| xml_etree_generate   | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                                       |
| xml_etree_parse      | 162 ms                                                       | 148 ms: 1.09x faster                                                        |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                                        |
| unpickle_list        | 4.49 us                                                      | 4.54 us: 1.01x slower                                                       |
| pickle               | 9.94 us                                                      | 10.1 us: 1.01x slower                                                       |
| unpickle             | 14.2 us                                                      | 14.5 us: 1.03x slower                                                       |
| pickle_list          | 4.11 us                                                      | 4.37 us: 1.06x slower                                                       |
| pickle_dict          | 30.0 us                                                      | 32.9 us: 1.10x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.4 ms: 1.41x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 153 us: 3.41x faster                                                        |
| asyncio_tcp              | 782 ms                                                       | 372 ms: 2.10x faster                                                        |
| deltablue                | 7.47 ms                                                      | 3.67 ms: 2.04x faster                                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                                      |
| raytrace                 | 488 ms                                                       | 279 ms: 1.75x faster                                                        |
| logging_silent           | 166 ns                                                       | 97.7 ns: 1.70x faster                                                       |
| chaos                    | 107 ms                                                       | 63.6 ms: 1.68x faster                                                       |
| generators               | 58.0 ms                                                      | 34.5 ms: 1.68x faster                                                       |
| scimark_monte_carlo      | 109 ms                                                       | 65.4 ms: 1.67x faster                                                       |
| crypto_pyaes             | 118 ms                                                       | 72.4 ms: 1.63x faster                                                       |
| async_tree_none          | 700 ms                                                       | 433 ms: 1.62x faster                                                        |
| sqlglot_parse            | 2.26 ms                                                      | 1.40 ms: 1.61x faster                                                       |
| nbody                    | 137 ms                                                       | 85.9 ms: 1.60x faster                                                       |
| scimark_lu               | 164 ms                                                       | 103 ms: 1.59x faster                                                        |
| bench_mp_pool            | 7.18 ms                                                      | 4.60 ms: 1.56x faster                                                       |
| richards_super           | 90.8 ms                                                      | 59.0 ms: 1.54x faster                                                       |
| go                       | 259 ms                                                       | 171 ms: 1.52x faster                                                        |
| async_tree_memoization   | 824 ms                                                       | 546 ms: 1.51x faster                                                        |
| spectral_norm            | 136 ms                                                       | 90.4 ms: 1.51x faster                                                       |
| sqlglot_transpile        | 2.71 ms                                                      | 1.81 ms: 1.50x faster                                                       |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                                      |
| hexiom                   | 9.52 ms                                                      | 6.48 ms: 1.47x faster                                                       |
| pickle_pure_python       | 457 us                                                       | 314 us: 1.45x faster                                                        |
| richards                 | 74.1 ms                                                      | 52.2 ms: 1.42x faster                                                       |
| mako                     | 14.7 ms                                                      | 10.4 ms: 1.41x faster                                                       |
| unpickle_pure_python     | 321 us                                                       | 228 us: 1.41x faster                                                        |
| pyflate                  | 697 ms                                                       | 509 ms: 1.37x faster                                                        |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 696 ms: 1.37x faster                                                        |
| float                    | 110 ms                                                       | 80.9 ms: 1.36x faster                                                       |
| tomli_loads              | 2.97 sec                                                     | 2.19 sec: 1.35x faster                                                      |
| logging_simple           | 8.90 us                                                      | 6.62 us: 1.34x faster                                                       |
| coroutines               | 30.4 ms                                                      | 23.0 ms: 1.32x faster                                                       |
| logging_format           | 9.57 us                                                      | 7.30 us: 1.31x faster                                                       |
| deepcopy_memo            | 48.9 us                                                      | 37.3 us: 1.31x faster                                                       |
| xml_etree_process        | 76.0 ms                                                      | 58.3 ms: 1.30x faster                                                       |
| regex_compile            | 194 ms                                                       | 149 ms: 1.30x faster                                                        |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.30x faster                                                      |
| pycparser                | 1.66 sec                                                     | 1.29 sec: 1.29x faster                                                      |
| pprint_safe_repr         | 1.05 sec                                                     | 816 ms: 1.29x faster                                                        |
| fannkuch                 | 496 ms                                                       | 390 ms: 1.27x faster                                                        |
| nqueens                  | 112 ms                                                       | 88.4 ms: 1.27x faster                                                       |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                                        |
| mypy2                    | 466 ms                                                       | 372 ms: 1.25x faster                                                        |
| unpack_sequence          | 59.5 ns                                                      | 47.9 ns: 1.24x faster                                                       |
| comprehensions           | 26.9 us                                                      | 21.7 us: 1.24x faster                                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.19 ms: 1.24x faster                                                       |
| sqlglot_normalize        | 144 ms                                                       | 118 ms: 1.23x faster                                                        |
| mdp                      | 3.03 sec                                                     | 2.51 sec: 1.21x faster                                                      |
| scimark_fft              | 359 ms                                                       | 298 ms: 1.21x faster                                                        |
| bench_thread_pool        | 1.14 ms                                                      | 949 us: 1.20x faster                                                        |
| scimark_sor              | 177 ms                                                       | 148 ms: 1.20x faster                                                        |
| sqlglot_optimize         | 70.3 ms                                                      | 58.9 ms: 1.19x faster                                                       |
| json_loads               | 30.0 us                                                      | 25.2 us: 1.19x faster                                                       |
| deepcopy                 | 454 us                                                       | 382 us: 1.19x faster                                                        |
| docutils                 | 3.40 sec                                                     | 2.88 sec: 1.18x faster                                                      |
| deepcopy_reduce          | 4.03 us                                                      | 3.43 us: 1.17x faster                                                       |
| json                     | 5.96 ms                                                      | 5.15 ms: 1.16x faster                                                       |
| dulwich_log              | 80.1 ms                                                      | 69.3 ms: 1.16x faster                                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.64 ms: 1.11x faster                                                       |
| sqlite_synth             | 2.97 us                                                      | 2.69 us: 1.10x faster                                                       |
| xml_etree_generate       | 94.6 ms                                                      | 85.9 ms: 1.10x faster                                                       |
| pathlib                  | 21.7 ms                                                      | 19.8 ms: 1.10x faster                                                       |
| async_generators         | 422 ms                                                       | 386 ms: 1.09x faster                                                        |
| xml_etree_parse          | 162 ms                                                       | 148 ms: 1.09x faster                                                        |
| regex_v8                 | 26.6 ms                                                      | 24.6 ms: 1.08x faster                                                       |
| regex_dna                | 259 ms                                                       | 240 ms: 1.08x faster                                                        |
| meteor_contest           | 137 ms                                                       | 130 ms: 1.05x faster                                                        |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                                        |
| pidigits                 | 271 ms                                                       | 263 ms: 1.03x faster                                                        |
| unpickle_list            | 4.49 us                                                      | 4.54 us: 1.01x slower                                                       |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.01x slower                                                       |
| unpickle                 | 14.2 us                                                      | 14.5 us: 1.03x slower                                                       |
| gc_traversal             | 3.45 ms                                                      | 3.60 ms: 1.04x slower                                                       |
| pickle_list              | 4.11 us                                                      | 4.37 us: 1.06x slower                                                       |
| pickle_dict              | 30.0 us                                                      | 32.9 us: 1.10x slower                                                       |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                       |
| telco                    | 7.14 ms                                                      | 7.97 ms: 1.12x slower                                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                                       |
| regex_effbot             | 2.99 ms                                                      | 3.66 ms: 1.22x slower                                                       |
| dask                     | 463 ms                                                       | 589 ms: 1.27x slower                                                        |
| coverage                 | 64.0 ms                                                      | 84.0 ms: 1.31x slower                                                       |
| Geometric mean           | (ref)                                                        | 1.28x faster                                                                |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
