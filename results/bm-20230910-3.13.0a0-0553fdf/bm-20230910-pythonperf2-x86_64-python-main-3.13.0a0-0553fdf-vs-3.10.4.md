
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.90 sec: 1.17x faster                                      |
| tornado_http   | 152 ms                                                       | 120 ms: 1.27x faster                                        |
| Geometric mean | (ref)                                                        | 1.22x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 87.7 ms: 1.57x faster                                       |
| float          | 110 ms                                                       | 81.1 ms: 1.36x faster                                       |
| pidigits       | 271 ms                                                       | 264 ms: 1.03x faster                                        |
| Geometric mean | (ref)                                                        | 1.30x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 148 ms: 1.31x faster                                        |
| regex_dna      | 259 ms                                                       | 242 ms: 1.07x faster                                        |
| regex_v8       | 26.6 ms                                                      | 25.6 ms: 1.04x faster                                       |
| regex_effbot   | 2.99 ms                                                      | 3.61 ms: 1.20x slower                                       |
| Geometric mean | (ref)                                                        | 1.05x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 312 us: 1.47x faster                                        |
| unpickle_pure_python | 321 us                                                       | 227 us: 1.41x faster                                        |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                       |
| tomli_loads          | 2.97 sec                                                     | 2.18 sec: 1.36x faster                                      |
| xml_etree_process    | 76.0 ms                                                      | 58.9 ms: 1.29x faster                                       |
| json_loads           | 30.0 us                                                      | 24.8 us: 1.21x faster                                       |
| xml_etree_generate   | 94.6 ms                                                      | 86.1 ms: 1.10x faster                                       |
| xml_etree_parse      | 162 ms                                                       | 148 ms: 1.09x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                        |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                       |
| unpickle_list        | 4.49 us                                                      | 4.65 us: 1.03x slower                                       |
| unpickle             | 14.2 us                                                      | 14.9 us: 1.05x slower                                       |
| pickle_dict          | 30.0 us                                                      | 32.3 us: 1.08x slower                                       |
| pickle_list          | 4.11 us                                                      | 4.58 us: 1.11x slower                                       |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.3 ms: 1.42x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf2-x86_64-python-main-3.13.0a0-0553fdf |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 151 us: 3.47x faster                                        |
| asyncio_tcp              | 782 ms                                                       | 370 ms: 2.12x faster                                        |
| deltablue                | 7.47 ms                                                      | 3.70 ms: 2.02x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                      |
| raytrace                 | 488 ms                                                       | 271 ms: 1.80x faster                                        |
| chaos                    | 107 ms                                                       | 62.0 ms: 1.73x faster                                       |
| generators               | 58.0 ms                                                      | 35.4 ms: 1.64x faster                                       |
| logging_silent           | 166 ns                                                       | 102 ns: 1.63x faster                                        |
| crypto_pyaes             | 118 ms                                                       | 72.8 ms: 1.62x faster                                       |
| sqlglot_parse            | 2.26 ms                                                      | 1.40 ms: 1.61x faster                                       |
| async_tree_none          | 700 ms                                                       | 439 ms: 1.60x faster                                        |
| scimark_lu               | 164 ms                                                       | 103 ms: 1.59x faster                                        |
| scimark_monte_carlo      | 109 ms                                                       | 69.3 ms: 1.58x faster                                       |
| nbody                    | 137 ms                                                       | 87.7 ms: 1.57x faster                                       |
| richards_super           | 90.8 ms                                                      | 60.5 ms: 1.50x faster                                       |
| async_tree_memoization   | 824 ms                                                       | 552 ms: 1.49x faster                                        |
| sqlglot_transpile        | 2.71 ms                                                      | 1.82 ms: 1.49x faster                                       |
| go                       | 259 ms                                                       | 174 ms: 1.49x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                      |
| hexiom                   | 9.52 ms                                                      | 6.46 ms: 1.47x faster                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.89 ms: 1.47x faster                                       |
| pickle_pure_python       | 457 us                                                       | 312 us: 1.47x faster                                        |
| spectral_norm            | 136 ms                                                       | 94.6 ms: 1.44x faster                                       |
| mako                     | 14.7 ms                                                      | 10.3 ms: 1.42x faster                                       |
| unpickle_pure_python     | 321 us                                                       | 227 us: 1.41x faster                                        |
| richards                 | 74.1 ms                                                      | 53.5 ms: 1.38x faster                                       |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.37x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.18 sec: 1.36x faster                                      |
| float                    | 110 ms                                                       | 81.1 ms: 1.36x faster                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 701 ms: 1.36x faster                                        |
| pyflate                  | 697 ms                                                       | 515 ms: 1.35x faster                                        |
| coroutines               | 30.4 ms                                                      | 23.0 ms: 1.32x faster                                       |
| regex_compile            | 194 ms                                                       | 148 ms: 1.31x faster                                        |
| logging_simple           | 8.90 us                                                      | 6.81 us: 1.31x faster                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.29x faster                                      |
| xml_etree_process        | 76.0 ms                                                      | 58.9 ms: 1.29x faster                                       |
| deepcopy_memo            | 48.9 us                                                      | 38.1 us: 1.28x faster                                       |
| pprint_safe_repr         | 1.05 sec                                                     | 819 ms: 1.28x faster                                        |
| logging_format           | 9.57 us                                                      | 7.51 us: 1.27x faster                                       |
| tornado_http             | 152 ms                                                       | 120 ms: 1.27x faster                                        |
| nqueens                  | 112 ms                                                       | 88.9 ms: 1.27x faster                                       |
| mypy2                    | 466 ms                                                       | 372 ms: 1.25x faster                                        |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.16 ms: 1.25x faster                                       |
| pycparser                | 1.66 sec                                                     | 1.34 sec: 1.25x faster                                      |
| sqlglot_normalize        | 144 ms                                                       | 116 ms: 1.24x faster                                        |
| fannkuch                 | 496 ms                                                       | 400 ms: 1.24x faster                                        |
| scimark_sor              | 177 ms                                                       | 146 ms: 1.21x faster                                        |
| comprehensions           | 26.9 us                                                      | 22.3 us: 1.21x faster                                       |
| json_loads               | 30.0 us                                                      | 24.8 us: 1.21x faster                                       |
| deepcopy                 | 454 us                                                       | 376 us: 1.21x faster                                        |
| sqlglot_optimize         | 70.3 ms                                                      | 58.4 ms: 1.20x faster                                       |
| deepcopy_reduce          | 4.03 us                                                      | 3.37 us: 1.19x faster                                       |
| mdp                      | 3.03 sec                                                     | 2.57 sec: 1.18x faster                                      |
| docutils                 | 3.40 sec                                                     | 2.90 sec: 1.17x faster                                      |
| json                     | 5.96 ms                                                      | 5.11 ms: 1.17x faster                                       |
| scimark_fft              | 359 ms                                                       | 308 ms: 1.17x faster                                        |
| bench_thread_pool        | 1.14 ms                                                      | 976 us: 1.16x faster                                        |
| dulwich_log              | 80.1 ms                                                      | 69.0 ms: 1.16x faster                                       |
| pathlib                  | 21.7 ms                                                      | 19.7 ms: 1.10x faster                                       |
| xml_etree_generate       | 94.6 ms                                                      | 86.1 ms: 1.10x faster                                       |
| xml_etree_parse          | 162 ms                                                       | 148 ms: 1.09x faster                                        |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.68 ms: 1.08x faster                                       |
| unpack_sequence          | 59.5 ns                                                      | 55.4 ns: 1.07x faster                                       |
| regex_dna                | 259 ms                                                       | 242 ms: 1.07x faster                                        |
| async_generators         | 422 ms                                                       | 393 ms: 1.07x faster                                        |
| meteor_contest           | 137 ms                                                       | 129 ms: 1.06x faster                                        |
| regex_v8                 | 26.6 ms                                                      | 25.6 ms: 1.04x faster                                       |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                        |
| pidigits                 | 271 ms                                                       | 264 ms: 1.03x faster                                        |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                       |
| unpickle_list            | 4.49 us                                                      | 4.65 us: 1.03x slower                                       |
| unpickle                 | 14.2 us                                                      | 14.9 us: 1.05x slower                                       |
| pickle_dict              | 30.0 us                                                      | 32.3 us: 1.08x slower                                       |
| gc_traversal             | 3.45 ms                                                      | 3.79 ms: 1.10x slower                                       |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                       |
| pickle_list              | 4.11 us                                                      | 4.58 us: 1.11x slower                                       |
| telco                    | 7.14 ms                                                      | 8.15 ms: 1.14x slower                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                       |
| regex_effbot             | 2.99 ms                                                      | 3.61 ms: 1.20x slower                                       |
| coverage                 | 64.0 ms                                                      | 79.8 ms: 1.25x slower                                       |
| dask                     | 463 ms                                                       | 588 ms: 1.27x slower                                        |
| Geometric mean           | (ref)                                                        | 1.27x faster                                                |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.20x
