
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_elf
- machine: linux-x86_64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.92 sec: 1.16x faster                                                  |
| tornado_http   | 152 ms                                                       | 121 ms: 1.26x faster                                                    |
| Geometric mean | (ref)                                                        | 1.21x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| float          | 110 ms                                                       | 82.3 ms: 1.34x faster                                                   |
| nbody          | 137 ms                                                       | 110 ms: 1.24x faster                                                    |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                                    |
| Geometric mean | (ref)                                                        | 1.19x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 155 ms: 1.25x faster                                                    |
| regex_dna      | 259 ms                                                       | 244 ms: 1.06x faster                                                    |
| regex_v8       | 26.6 ms                                                      | 25.8 ms: 1.03x faster                                                   |
| regex_effbot   | 2.99 ms                                                      | 3.56 ms: 1.19x slower                                                   |
| Geometric mean | (ref)                                                        | 1.04x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 315 us: 1.45x faster                                                    |
| unpickle_pure_python | 321 us                                                       | 226 us: 1.42x faster                                                    |
| json_dumps           | 14.2 ms                                                      | 10.5 ms: 1.36x faster                                                   |
| tomli_loads          | 2.97 sec                                                     | 2.27 sec: 1.31x faster                                                  |
| xml_etree_process    | 76.0 ms                                                      | 59.1 ms: 1.29x faster                                                   |
| json_loads           | 30.0 us                                                      | 24.7 us: 1.21x faster                                                   |
| xml_etree_generate   | 94.6 ms                                                      | 86.1 ms: 1.10x faster                                                   |
| xml_etree_parse      | 162 ms                                                       | 149 ms: 1.08x faster                                                    |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.05x faster                                                    |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                                   |
| unpickle             | 14.2 us                                                      | 14.5 us: 1.02x slower                                                   |
| unpickle_list        | 4.49 us                                                      | 4.62 us: 1.03x slower                                                   |
| pickle_list          | 4.11 us                                                      | 4.45 us: 1.08x slower                                                   |
| pickle_dict          | 30.0 us                                                      | 33.3 us: 1.11x slower                                                   |
| Geometric mean       | (ref)                                                        | 1.13x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                                   |
| python_startup_no_site | 7.32 ms                                                      | 8.72 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.3 ms: 1.42x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 158 us: 3.30x faster                                                    |
| asyncio_tcp              | 782 ms                                                       | 370 ms: 2.11x faster                                                    |
| deltablue                | 7.47 ms                                                      | 3.82 ms: 1.96x faster                                                   |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.59 sec: 1.95x faster                                                  |
| raytrace                 | 488 ms                                                       | 286 ms: 1.70x faster                                                    |
| logging_silent           | 166 ns                                                       | 97.8 ns: 1.69x faster                                                   |
| generators               | 58.0 ms                                                      | 36.1 ms: 1.61x faster                                                   |
| sqlglot_parse            | 2.26 ms                                                      | 1.43 ms: 1.58x faster                                                   |
| async_tree_none          | 700 ms                                                       | 445 ms: 1.57x faster                                                    |
| richards_super           | 90.8 ms                                                      | 58.4 ms: 1.55x faster                                                   |
| crypto_pyaes             | 118 ms                                                       | 76.4 ms: 1.55x faster                                                   |
| scimark_lu               | 164 ms                                                       | 107 ms: 1.53x faster                                                    |
| async_tree_memoization   | 824 ms                                                       | 558 ms: 1.48x faster                                                    |
| bench_mp_pool            | 7.18 ms                                                      | 4.88 ms: 1.47x faster                                                   |
| spectral_norm            | 136 ms                                                       | 92.7 ms: 1.47x faster                                                   |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.47x faster                                                  |
| sqlglot_transpile        | 2.71 ms                                                      | 1.84 ms: 1.47x faster                                                   |
| go                       | 259 ms                                                       | 177 ms: 1.46x faster                                                    |
| chaos                    | 107 ms                                                       | 73.5 ms: 1.46x faster                                                   |
| pickle_pure_python       | 457 us                                                       | 315 us: 1.45x faster                                                    |
| scimark_monte_carlo      | 109 ms                                                       | 75.5 ms: 1.45x faster                                                   |
| richards                 | 74.1 ms                                                      | 52.1 ms: 1.42x faster                                                   |
| mako                     | 14.7 ms                                                      | 10.3 ms: 1.42x faster                                                   |
| unpickle_pure_python     | 321 us                                                       | 226 us: 1.42x faster                                                    |
| json_dumps               | 14.2 ms                                                      | 10.5 ms: 1.36x faster                                                   |
| float                    | 110 ms                                                       | 82.3 ms: 1.34x faster                                                   |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 711 ms: 1.34x faster                                                    |
| pyflate                  | 697 ms                                                       | 532 ms: 1.31x faster                                                    |
| tomli_loads              | 2.97 sec                                                     | 2.27 sec: 1.31x faster                                                  |
| logging_simple           | 8.90 us                                                      | 6.80 us: 1.31x faster                                                   |
| coroutines               | 30.4 ms                                                      | 23.6 ms: 1.29x faster                                                   |
| xml_etree_process        | 76.0 ms                                                      | 59.1 ms: 1.29x faster                                                   |
| logging_format           | 9.57 us                                                      | 7.53 us: 1.27x faster                                                   |
| deepcopy_memo            | 48.9 us                                                      | 38.8 us: 1.26x faster                                                   |
| tornado_http             | 152 ms                                                       | 121 ms: 1.26x faster                                                    |
| regex_compile            | 194 ms                                                       | 155 ms: 1.25x faster                                                    |
| nbody                    | 137 ms                                                       | 110 ms: 1.24x faster                                                    |
| pycparser                | 1.66 sec                                                     | 1.35 sec: 1.24x faster                                                  |
| mypy2                    | 466 ms                                                       | 383 ms: 1.22x faster                                                    |
| scimark_sor              | 177 ms                                                       | 146 ms: 1.21x faster                                                    |
| json_loads               | 30.0 us                                                      | 24.7 us: 1.21x faster                                                   |
| fannkuch                 | 496 ms                                                       | 410 ms: 1.21x faster                                                    |
| deepcopy_reduce          | 4.03 us                                                      | 3.33 us: 1.21x faster                                                   |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.31 ms: 1.20x faster                                                   |
| pprint_pformat           | 2.15 sec                                                     | 1.79 sec: 1.20x faster                                                  |
| hexiom                   | 9.52 ms                                                      | 7.93 ms: 1.20x faster                                                   |
| pprint_safe_repr         | 1.05 sec                                                     | 875 ms: 1.20x faster                                                    |
| sqlglot_normalize        | 144 ms                                                       | 121 ms: 1.20x faster                                                    |
| deepcopy                 | 454 us                                                       | 380 us: 1.19x faster                                                    |
| docutils                 | 3.40 sec                                                     | 2.92 sec: 1.16x faster                                                  |
| mdp                      | 3.03 sec                                                     | 2.61 sec: 1.16x faster                                                  |
| json                     | 5.96 ms                                                      | 5.14 ms: 1.16x faster                                                   |
| sqlglot_optimize         | 70.3 ms                                                      | 60.9 ms: 1.15x faster                                                   |
| dulwich_log              | 80.1 ms                                                      | 69.4 ms: 1.15x faster                                                   |
| unpack_sequence          | 59.5 ns                                                      | 52.0 ns: 1.15x faster                                                   |
| bench_thread_pool        | 1.14 ms                                                      | 1.01 ms: 1.13x faster                                                   |
| create_gc_cycles         | 1.82 ms                                                      | 1.63 ms: 1.11x faster                                                   |
| pathlib                  | 21.7 ms                                                      | 19.7 ms: 1.10x faster                                                   |
| xml_etree_generate       | 94.6 ms                                                      | 86.1 ms: 1.10x faster                                                   |
| nqueens                  | 112 ms                                                       | 102 ms: 1.10x faster                                                    |
| sqlite_synth             | 2.97 us                                                      | 2.71 us: 1.09x faster                                                   |
| xml_etree_parse          | 162 ms                                                       | 149 ms: 1.08x faster                                                    |
| regex_dna                | 259 ms                                                       | 244 ms: 1.06x faster                                                    |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.05x faster                                                    |
| regex_v8                 | 26.6 ms                                                      | 25.8 ms: 1.03x faster                                                   |
| async_generators         | 422 ms                                                       | 410 ms: 1.03x faster                                                    |
| comprehensions           | 26.9 us                                                      | 26.2 us: 1.03x faster                                                   |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                                    |
| meteor_contest           | 137 ms                                                       | 134 ms: 1.02x faster                                                    |
| scimark_fft              | 359 ms                                                       | 358 ms: 1.00x faster                                                    |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                                   |
| unpickle                 | 14.2 us                                                      | 14.5 us: 1.02x slower                                                   |
| unpickle_list            | 4.49 us                                                      | 4.62 us: 1.03x slower                                                   |
| pickle_list              | 4.11 us                                                      | 4.45 us: 1.08x slower                                                   |
| python_startup           | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                                   |
| pickle_dict              | 30.0 us                                                      | 33.3 us: 1.11x slower                                                   |
| gc_traversal             | 3.45 ms                                                      | 3.94 ms: 1.14x slower                                                   |
| telco                    | 7.14 ms                                                      | 8.26 ms: 1.16x slower                                                   |
| regex_effbot             | 2.99 ms                                                      | 3.56 ms: 1.19x slower                                                   |
| python_startup_no_site   | 7.32 ms                                                      | 8.72 ms: 1.19x slower                                                   |
| coverage                 | 64.0 ms                                                      | 79.2 ms: 1.24x slower                                                   |
| Geometric mean           | (ref)                                                        | 1.24x faster                                                            |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.18x
