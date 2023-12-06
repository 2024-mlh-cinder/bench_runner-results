
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 8e56d55
- commit date: 2023-10-07
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.86 sec: 1.19x faster                                      |
| tornado_http   | 152 ms                                                       | 122 ms: 1.25x faster                                        |
| Geometric mean | (ref)                                                        | 1.22x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 85.1 ms: 1.61x faster                                       |
| float          | 110 ms                                                       | 80.7 ms: 1.37x faster                                       |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                        | 1.31x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 148 ms: 1.30x faster                                        |
| regex_dna      | 259 ms                                                       | 235 ms: 1.10x faster                                        |
| regex_v8       | 26.6 ms                                                      | 25.1 ms: 1.06x faster                                       |
| regex_effbot   | 2.99 ms                                                      | 3.44 ms: 1.15x slower                                       |
| Geometric mean | (ref)                                                        | 1.07x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 311 us: 1.47x faster                                        |
| unpickle_pure_python | 321 us                                                       | 226 us: 1.42x faster                                        |
| json_dumps           | 14.2 ms                                                      | 10.5 ms: 1.36x faster                                       |
| xml_etree_process    | 76.0 ms                                                      | 59.1 ms: 1.29x faster                                       |
| tomli_loads          | 2.97 sec                                                     | 2.32 sec: 1.28x faster                                      |
| json_loads           | 30.0 us                                                      | 25.0 us: 1.20x faster                                       |
| xml_etree_generate   | 94.6 ms                                                      | 86.3 ms: 1.10x faster                                       |
| xml_etree_parse      | 162 ms                                                       | 149 ms: 1.09x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.03x faster                                        |
| unpickle             | 14.2 us                                                      | 14.3 us: 1.01x slower                                       |
| pickle               | 9.94 us                                                      | 10.3 us: 1.04x slower                                       |
| unpickle_list        | 4.49 us                                                      | 4.68 us: 1.04x slower                                       |
| pickle_dict          | 30.0 us                                                      | 31.6 us: 1.05x slower                                       |
| pickle_list          | 4.11 us                                                      | 4.39 us: 1.07x slower                                       |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                       |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.4 ms: 1.41x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.49x faster                                        |
| asyncio_tcp              | 782 ms                                                       | 366 ms: 2.14x faster                                        |
| deltablue                | 7.47 ms                                                      | 3.61 ms: 2.07x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                      |
| raytrace                 | 488 ms                                                       | 268 ms: 1.82x faster                                        |
| chaos                    | 107 ms                                                       | 61.1 ms: 1.75x faster                                       |
| logging_silent           | 166 ns                                                       | 96.9 ns: 1.71x faster                                       |
| generators               | 58.0 ms                                                      | 34.8 ms: 1.67x faster                                       |
| scimark_monte_carlo      | 109 ms                                                       | 66.8 ms: 1.64x faster                                       |
| scimark_lu               | 164 ms                                                       | 101 ms: 1.63x faster                                        |
| crypto_pyaes             | 118 ms                                                       | 72.9 ms: 1.62x faster                                       |
| nbody                    | 137 ms                                                       | 85.1 ms: 1.61x faster                                       |
| async_tree_none          | 700 ms                                                       | 435 ms: 1.61x faster                                        |
| sqlglot_parse            | 2.26 ms                                                      | 1.42 ms: 1.58x faster                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.57 ms: 1.57x faster                                       |
| go                       | 259 ms                                                       | 171 ms: 1.51x faster                                        |
| richards_super           | 90.8 ms                                                      | 60.2 ms: 1.51x faster                                       |
| async_tree_memoization   | 824 ms                                                       | 549 ms: 1.50x faster                                        |
| spectral_norm            | 136 ms                                                       | 91.0 ms: 1.50x faster                                       |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.48x faster                                      |
| sqlglot_transpile        | 2.71 ms                                                      | 1.83 ms: 1.48x faster                                       |
| pickle_pure_python       | 457 us                                                       | 311 us: 1.47x faster                                        |
| hexiom                   | 9.52 ms                                                      | 6.50 ms: 1.46x faster                                       |
| unpickle_pure_python     | 321 us                                                       | 226 us: 1.42x faster                                        |
| mako                     | 14.7 ms                                                      | 10.4 ms: 1.41x faster                                       |
| richards                 | 74.1 ms                                                      | 54.0 ms: 1.37x faster                                       |
| float                    | 110 ms                                                       | 80.7 ms: 1.37x faster                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 700 ms: 1.36x faster                                        |
| json_dumps               | 14.2 ms                                                      | 10.5 ms: 1.36x faster                                       |
| pyflate                  | 697 ms                                                       | 514 ms: 1.35x faster                                        |
| unpack_sequence          | 59.5 ns                                                      | 44.8 ns: 1.33x faster                                       |
| deepcopy_memo            | 48.9 us                                                      | 36.9 us: 1.32x faster                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.65 sec: 1.31x faster                                      |
| coroutines               | 30.4 ms                                                      | 23.3 ms: 1.31x faster                                       |
| regex_compile            | 194 ms                                                       | 148 ms: 1.30x faster                                        |
| pycparser                | 1.66 sec                                                     | 1.28 sec: 1.30x faster                                      |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.00 ms: 1.30x faster                                       |
| pprint_safe_repr         | 1.05 sec                                                     | 808 ms: 1.30x faster                                        |
| logging_simple           | 8.90 us                                                      | 6.88 us: 1.29x faster                                       |
| fannkuch                 | 496 ms                                                       | 385 ms: 1.29x faster                                        |
| xml_etree_process        | 76.0 ms                                                      | 59.1 ms: 1.29x faster                                       |
| nqueens                  | 112 ms                                                       | 87.9 ms: 1.28x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.32 sec: 1.28x faster                                      |
| logging_format           | 9.57 us                                                      | 7.56 us: 1.27x faster                                       |
| mypy2                    | 466 ms                                                       | 370 ms: 1.26x faster                                        |
| sqlglot_normalize        | 144 ms                                                       | 115 ms: 1.26x faster                                        |
| tornado_http             | 152 ms                                                       | 122 ms: 1.25x faster                                        |
| deepcopy                 | 454 us                                                       | 368 us: 1.23x faster                                        |
| comprehensions           | 26.9 us                                                      | 22.1 us: 1.22x faster                                       |
| scimark_sor              | 177 ms                                                       | 146 ms: 1.22x faster                                        |
| scimark_fft              | 359 ms                                                       | 296 ms: 1.22x faster                                        |
| mdp                      | 3.03 sec                                                     | 2.51 sec: 1.21x faster                                      |
| sqlglot_optimize         | 70.3 ms                                                      | 58.2 ms: 1.21x faster                                       |
| deepcopy_reduce          | 4.03 us                                                      | 3.34 us: 1.21x faster                                       |
| json_loads               | 30.0 us                                                      | 25.0 us: 1.20x faster                                       |
| docutils                 | 3.40 sec                                                     | 2.86 sec: 1.19x faster                                      |
| bench_thread_pool        | 1.14 ms                                                      | 962 us: 1.18x faster                                        |
| json                     | 5.96 ms                                                      | 5.14 ms: 1.16x faster                                       |
| dulwich_log              | 80.1 ms                                                      | 69.4 ms: 1.15x faster                                       |
| pathlib                  | 21.7 ms                                                      | 19.6 ms: 1.10x faster                                       |
| regex_dna                | 259 ms                                                       | 235 ms: 1.10x faster                                        |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                       |
| xml_etree_generate       | 94.6 ms                                                      | 86.3 ms: 1.10x faster                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.67 ms: 1.09x faster                                       |
| xml_etree_parse          | 162 ms                                                       | 149 ms: 1.09x faster                                        |
| regex_v8                 | 26.6 ms                                                      | 25.1 ms: 1.06x faster                                       |
| async_generators         | 422 ms                                                       | 404 ms: 1.05x faster                                        |
| meteor_contest           | 137 ms                                                       | 132 ms: 1.04x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.03x faster                                        |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                        |
| unpickle                 | 14.2 us                                                      | 14.3 us: 1.01x slower                                       |
| pickle                   | 9.94 us                                                      | 10.3 us: 1.04x slower                                       |
| unpickle_list            | 4.49 us                                                      | 4.68 us: 1.04x slower                                       |
| pickle_dict              | 30.0 us                                                      | 31.6 us: 1.05x slower                                       |
| pickle_list              | 4.11 us                                                      | 4.39 us: 1.07x slower                                       |
| gc_traversal             | 3.45 ms                                                      | 3.74 ms: 1.08x slower                                       |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                       |
| telco                    | 7.14 ms                                                      | 8.08 ms: 1.13x slower                                       |
| regex_effbot             | 2.99 ms                                                      | 3.44 ms: 1.15x slower                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                       |
| coverage                 | 64.0 ms                                                      | 82.8 ms: 1.29x slower                                       |
| Geometric mean           | (ref)                                                        | 1.29x faster                                                |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
