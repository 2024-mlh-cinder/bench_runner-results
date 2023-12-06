
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 482fad7
- commit date: 2023-08-26
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.90 sec: 1.17x faster                                      |
| tornado_http   | 152 ms                                                       | 122 ms: 1.25x faster                                        |
| Geometric mean | (ref)                                                        | 1.21x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 137 ms                                                       | 85.1 ms: 1.61x faster                                       |
| float          | 110 ms                                                       | 81.0 ms: 1.36x faster                                       |
| pidigits       | 271 ms                                                       | 259 ms: 1.04x faster                                        |
| Geometric mean | (ref)                                                        | 1.32x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 151 ms: 1.28x faster                                        |
| regex_dna      | 259 ms                                                       | 249 ms: 1.04x faster                                        |
| regex_v8       | 26.6 ms                                                      | 26.8 ms: 1.00x slower                                       |
| regex_effbot   | 2.99 ms                                                      | 3.64 ms: 1.21x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 318 us: 1.44x faster                                        |
| unpickle_pure_python | 321 us                                                       | 225 us: 1.42x faster                                        |
| json_dumps           | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                       |
| tomli_loads          | 2.97 sec                                                     | 2.26 sec: 1.31x faster                                      |
| xml_etree_process    | 76.0 ms                                                      | 59.6 ms: 1.28x faster                                       |
| json_loads           | 30.0 us                                                      | 25.1 us: 1.19x faster                                       |
| xml_etree_generate   | 94.6 ms                                                      | 87.1 ms: 1.09x faster                                       |
| xml_etree_parse      | 162 ms                                                       | 149 ms: 1.08x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 107 ms: 1.03x faster                                        |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                       |
| unpickle             | 14.2 us                                                      | 14.4 us: 1.02x slower                                       |
| unpickle_list        | 4.49 us                                                      | 4.63 us: 1.03x slower                                       |
| pickle_dict          | 30.0 us                                                      | 32.1 us: 1.07x slower                                       |
| pickle_list          | 4.11 us                                                      | 4.42 us: 1.07x slower                                       |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.6 ms: 1.01x slower                                       |
| python_startup_no_site | 7.32 ms                                                      | 8.66 ms: 1.18x slower                                       |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.3 ms: 1.42x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.48x faster                                        |
| asyncio_tcp              | 782 ms                                                       | 369 ms: 2.12x faster                                        |
| deltablue                | 7.47 ms                                                      | 3.68 ms: 2.03x faster                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                      |
| chaos                    | 107 ms                                                       | 61.9 ms: 1.73x faster                                       |
| raytrace                 | 488 ms                                                       | 287 ms: 1.70x faster                                        |
| scimark_monte_carlo      | 109 ms                                                       | 65.1 ms: 1.68x faster                                       |
| logging_silent           | 166 ns                                                       | 98.7 ns: 1.68x faster                                       |
| scimark_lu               | 164 ms                                                       | 99.9 ms: 1.64x faster                                       |
| crypto_pyaes             | 118 ms                                                       | 72.5 ms: 1.63x faster                                       |
| nbody                    | 137 ms                                                       | 85.1 ms: 1.61x faster                                       |
| async_tree_none          | 700 ms                                                       | 440 ms: 1.59x faster                                        |
| sqlglot_parse            | 2.26 ms                                                      | 1.42 ms: 1.59x faster                                       |
| generators               | 58.0 ms                                                      | 36.6 ms: 1.59x faster                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.66 ms: 1.54x faster                                       |
| go                       | 259 ms                                                       | 170 ms: 1.52x faster                                        |
| richards_super           | 90.8 ms                                                      | 60.3 ms: 1.51x faster                                       |
| async_tree_memoization   | 824 ms                                                       | 554 ms: 1.49x faster                                        |
| spectral_norm            | 136 ms                                                       | 91.7 ms: 1.49x faster                                       |
| sqlglot_transpile        | 2.71 ms                                                      | 1.83 ms: 1.48x faster                                       |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.47x faster                                      |
| hexiom                   | 9.52 ms                                                      | 6.53 ms: 1.46x faster                                       |
| pickle_pure_python       | 457 us                                                       | 318 us: 1.44x faster                                        |
| unpickle_pure_python     | 321 us                                                       | 225 us: 1.42x faster                                        |
| mako                     | 14.7 ms                                                      | 10.3 ms: 1.42x faster                                       |
| json_dumps               | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                       |
| pyflate                  | 697 ms                                                       | 510 ms: 1.37x faster                                        |
| float                    | 110 ms                                                       | 81.0 ms: 1.36x faster                                       |
| richards                 | 74.1 ms                                                      | 54.6 ms: 1.36x faster                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 706 ms: 1.35x faster                                        |
| coroutines               | 30.4 ms                                                      | 22.8 ms: 1.34x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.26 sec: 1.31x faster                                      |
| logging_simple           | 8.90 us                                                      | 6.85 us: 1.30x faster                                       |
| deepcopy_memo            | 48.9 us                                                      | 37.8 us: 1.29x faster                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.67 sec: 1.29x faster                                      |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.05 ms: 1.28x faster                                       |
| fannkuch                 | 496 ms                                                       | 387 ms: 1.28x faster                                        |
| regex_compile            | 194 ms                                                       | 151 ms: 1.28x faster                                        |
| logging_format           | 9.57 us                                                      | 7.50 us: 1.28x faster                                       |
| xml_etree_process        | 76.0 ms                                                      | 59.6 ms: 1.28x faster                                       |
| pprint_safe_repr         | 1.05 sec                                                     | 824 ms: 1.27x faster                                        |
| tornado_http             | 152 ms                                                       | 122 ms: 1.25x faster                                        |
| mypy2                    | 466 ms                                                       | 374 ms: 1.25x faster                                        |
| sqlglot_normalize        | 144 ms                                                       | 116 ms: 1.24x faster                                        |
| nqueens                  | 112 ms                                                       | 90.6 ms: 1.24x faster                                       |
| pycparser                | 1.66 sec                                                     | 1.34 sec: 1.24x faster                                      |
| scimark_sor              | 177 ms                                                       | 147 ms: 1.20x faster                                        |
| sqlglot_optimize         | 70.3 ms                                                      | 58.5 ms: 1.20x faster                                       |
| scimark_fft              | 359 ms                                                       | 299 ms: 1.20x faster                                        |
| json_loads               | 30.0 us                                                      | 25.1 us: 1.19x faster                                       |
| mdp                      | 3.03 sec                                                     | 2.54 sec: 1.19x faster                                      |
| unpack_sequence          | 59.5 ns                                                      | 49.9 ns: 1.19x faster                                       |
| comprehensions           | 26.9 us                                                      | 22.7 us: 1.19x faster                                       |
| deepcopy                 | 454 us                                                       | 386 us: 1.18x faster                                        |
| docutils                 | 3.40 sec                                                     | 2.90 sec: 1.17x faster                                      |
| deepcopy_reduce          | 4.03 us                                                      | 3.44 us: 1.17x faster                                       |
| json                     | 5.96 ms                                                      | 5.13 ms: 1.16x faster                                       |
| bench_thread_pool        | 1.14 ms                                                      | 989 us: 1.15x faster                                        |
| dulwich_log              | 80.1 ms                                                      | 69.9 ms: 1.15x faster                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.63 ms: 1.11x faster                                       |
| pathlib                  | 21.7 ms                                                      | 19.6 ms: 1.11x faster                                       |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.10x faster                                       |
| xml_etree_generate       | 94.6 ms                                                      | 87.1 ms: 1.09x faster                                       |
| xml_etree_parse          | 162 ms                                                       | 149 ms: 1.08x faster                                        |
| async_generators         | 422 ms                                                       | 395 ms: 1.07x faster                                        |
| pidigits                 | 271 ms                                                       | 259 ms: 1.04x faster                                        |
| meteor_contest           | 137 ms                                                       | 131 ms: 1.04x faster                                        |
| regex_dna                | 259 ms                                                       | 249 ms: 1.04x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 107 ms: 1.03x faster                                        |
| regex_v8                 | 26.6 ms                                                      | 26.8 ms: 1.00x slower                                       |
| python_startup           | 11.5 ms                                                      | 11.6 ms: 1.01x slower                                       |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                       |
| unpickle                 | 14.2 us                                                      | 14.4 us: 1.02x slower                                       |
| gc_traversal             | 3.45 ms                                                      | 3.54 ms: 1.03x slower                                       |
| unpickle_list            | 4.49 us                                                      | 4.63 us: 1.03x slower                                       |
| pickle_dict              | 30.0 us                                                      | 32.1 us: 1.07x slower                                       |
| pickle_list              | 4.11 us                                                      | 4.42 us: 1.07x slower                                       |
| telco                    | 7.14 ms                                                      | 8.12 ms: 1.14x slower                                       |
| python_startup_no_site   | 7.32 ms                                                      | 8.66 ms: 1.18x slower                                       |
| regex_effbot             | 2.99 ms                                                      | 3.64 ms: 1.21x slower                                       |
| dask                     | 463 ms                                                       | 591 ms: 1.28x slower                                        |
| coverage                 | 64.0 ms                                                      | 83.5 ms: 1.31x slower                                       |
| Geometric mean           | (ref)                                                        | 1.27x faster                                                |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.20x
