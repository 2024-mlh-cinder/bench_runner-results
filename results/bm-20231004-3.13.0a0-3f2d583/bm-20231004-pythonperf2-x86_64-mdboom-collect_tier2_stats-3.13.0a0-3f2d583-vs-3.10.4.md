
# Results vs. 3.10.4

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 3f2d583
- commit date: 2023-10-04
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 3.01 sec: 1.13x faster                                                     |
| tornado_http   | 152 ms                                                       | 125 ms: 1.21x faster                                                       |
| Geometric mean | (ref)                                                        | 1.17x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 114 ms: 1.20x faster                                                       |
| float          | 110 ms                                                       | 104 ms: 1.06x faster                                                       |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                        | 1.09x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 259 ms                                                       | 234 ms: 1.11x faster                                                       |
| regex_compile  | 194 ms                                                       | 178 ms: 1.09x faster                                                       |
| regex_v8       | 26.6 ms                                                      | 25.1 ms: 1.06x faster                                                      |
| regex_effbot   | 2.99 ms                                                      | 3.35 ms: 1.12x slower                                                      |
| Geometric mean | (ref)                                                        | 1.03x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 321 us: 1.42x faster                                                       |
| unpickle_pure_python | 321 us                                                       | 239 us: 1.34x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                      |
| xml_etree_process    | 76.0 ms                                                      | 59.2 ms: 1.28x faster                                                      |
| json_loads           | 30.0 us                                                      | 24.9 us: 1.21x faster                                                      |
| tomli_loads          | 2.97 sec                                                     | 2.65 sec: 1.12x faster                                                     |
| xml_etree_generate   | 94.6 ms                                                      | 87.0 ms: 1.09x faster                                                      |
| xml_etree_parse      | 162 ms                                                       | 149 ms: 1.08x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 112 ms: 1.01x slower                                                       |
| pickle               | 9.94 us                                                      | 10.1 us: 1.02x slower                                                      |
| unpickle             | 14.2 us                                                      | 14.6 us: 1.03x slower                                                      |
| pickle_list          | 4.11 us                                                      | 4.27 us: 1.04x slower                                                      |
| unpickle_list        | 4.49 us                                                      | 4.73 us: 1.05x slower                                                      |
| pickle_dict          | 30.0 us                                                      | 32.0 us: 1.07x slower                                                      |
| Geometric mean       | (ref)                                                        | 1.11x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                      |
| python_startup_no_site | 7.32 ms                                                      | 8.68 ms: 1.18x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 13.7 ms: 1.07x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 162 us: 3.22x faster                                                       |
| asyncio_tcp              | 782 ms                                                       | 374 ms: 2.09x faster                                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.60 sec: 1.93x faster                                                     |
| raytrace                 | 488 ms                                                       | 297 ms: 1.64x faster                                                       |
| logging_silent           | 166 ns                                                       | 101 ns: 1.64x faster                                                       |
| generators               | 58.0 ms                                                      | 36.6 ms: 1.59x faster                                                      |
| sqlglot_parse            | 2.26 ms                                                      | 1.46 ms: 1.54x faster                                                      |
| async_tree_none          | 700 ms                                                       | 456 ms: 1.54x faster                                                       |
| scimark_lu               | 164 ms                                                       | 108 ms: 1.52x faster                                                       |
| bench_mp_pool            | 7.18 ms                                                      | 4.80 ms: 1.50x faster                                                      |
| spectral_norm            | 136 ms                                                       | 92.2 ms: 1.48x faster                                                      |
| chaos                    | 107 ms                                                       | 73.2 ms: 1.46x faster                                                      |
| richards_super           | 90.8 ms                                                      | 62.1 ms: 1.46x faster                                                      |
| unpack_sequence          | 59.5 ns                                                      | 41.0 ns: 1.45x faster                                                      |
| deltablue                | 7.47 ms                                                      | 5.15 ms: 1.45x faster                                                      |
| async_tree_memoization   | 824 ms                                                       | 570 ms: 1.45x faster                                                       |
| sqlglot_transpile        | 2.71 ms                                                      | 1.88 ms: 1.44x faster                                                      |
| async_tree_io            | 1.61 sec                                                     | 1.12 sec: 1.44x faster                                                     |
| scimark_monte_carlo      | 109 ms                                                       | 76.9 ms: 1.42x faster                                                      |
| pickle_pure_python       | 457 us                                                       | 321 us: 1.42x faster                                                       |
| crypto_pyaes             | 118 ms                                                       | 84.0 ms: 1.41x faster                                                      |
| go                       | 259 ms                                                       | 186 ms: 1.39x faster                                                       |
| unpickle_pure_python     | 321 us                                                       | 239 us: 1.34x faster                                                       |
| richards                 | 74.1 ms                                                      | 55.3 ms: 1.34x faster                                                      |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                      |
| coroutines               | 30.4 ms                                                      | 23.1 ms: 1.32x faster                                                      |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 726 ms: 1.31x faster                                                       |
| xml_etree_process        | 76.0 ms                                                      | 59.2 ms: 1.28x faster                                                      |
| logging_simple           | 8.90 us                                                      | 7.07 us: 1.26x faster                                                      |
| pycparser                | 1.66 sec                                                     | 1.33 sec: 1.25x faster                                                     |
| logging_format           | 9.57 us                                                      | 7.67 us: 1.25x faster                                                      |
| pyflate                  | 697 ms                                                       | 567 ms: 1.23x faster                                                       |
| sqlglot_normalize        | 144 ms                                                       | 119 ms: 1.22x faster                                                       |
| tornado_http             | 152 ms                                                       | 125 ms: 1.21x faster                                                       |
| json_loads               | 30.0 us                                                      | 24.9 us: 1.21x faster                                                      |
| mypy2                    | 466 ms                                                       | 388 ms: 1.20x faster                                                       |
| nbody                    | 137 ms                                                       | 114 ms: 1.20x faster                                                       |
| deepcopy_reduce          | 4.03 us                                                      | 3.37 us: 1.20x faster                                                      |
| scimark_sor              | 177 ms                                                       | 148 ms: 1.20x faster                                                       |
| pprint_pformat           | 2.15 sec                                                     | 1.80 sec: 1.19x faster                                                     |
| pprint_safe_repr         | 1.05 sec                                                     | 883 ms: 1.19x faster                                                       |
| deepcopy                 | 454 us                                                       | 385 us: 1.18x faster                                                       |
| sqlglot_optimize         | 70.3 ms                                                      | 60.3 ms: 1.17x faster                                                      |
| bench_thread_pool        | 1.14 ms                                                      | 983 us: 1.16x faster                                                       |
| json                     | 5.96 ms                                                      | 5.17 ms: 1.15x faster                                                      |
| docutils                 | 3.40 sec                                                     | 3.01 sec: 1.13x faster                                                     |
| deepcopy_memo            | 48.9 us                                                      | 43.6 us: 1.12x faster                                                      |
| mdp                      | 3.03 sec                                                     | 2.71 sec: 1.12x faster                                                     |
| tomli_loads              | 2.97 sec                                                     | 2.65 sec: 1.12x faster                                                     |
| regex_dna                | 259 ms                                                       | 234 ms: 1.11x faster                                                       |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                                      |
| regex_compile            | 194 ms                                                       | 178 ms: 1.09x faster                                                       |
| dulwich_log              | 80.1 ms                                                      | 73.4 ms: 1.09x faster                                                      |
| xml_etree_generate       | 94.6 ms                                                      | 87.0 ms: 1.09x faster                                                      |
| xml_etree_parse          | 162 ms                                                       | 149 ms: 1.08x faster                                                       |
| mako                     | 14.7 ms                                                      | 13.7 ms: 1.07x faster                                                      |
| create_gc_cycles         | 1.82 ms                                                      | 1.70 ms: 1.07x faster                                                      |
| async_generators         | 422 ms                                                       | 395 ms: 1.07x faster                                                       |
| regex_v8                 | 26.6 ms                                                      | 25.1 ms: 1.06x faster                                                      |
| float                    | 110 ms                                                       | 104 ms: 1.06x faster                                                       |
| pathlib                  | 21.7 ms                                                      | 20.6 ms: 1.05x faster                                                      |
| fannkuch                 | 496 ms                                                       | 473 ms: 1.05x faster                                                       |
| nqueens                  | 112 ms                                                       | 110 ms: 1.02x faster                                                       |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                                       |
| meteor_contest           | 137 ms                                                       | 138 ms: 1.01x slower                                                       |
| xml_etree_iterparse      | 110 ms                                                       | 112 ms: 1.01x slower                                                       |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.02x slower                                                      |
| hexiom                   | 9.52 ms                                                      | 9.72 ms: 1.02x slower                                                      |
| unpickle                 | 14.2 us                                                      | 14.6 us: 1.03x slower                                                      |
| pickle_list              | 4.11 us                                                      | 4.27 us: 1.04x slower                                                      |
| unpickle_list            | 4.49 us                                                      | 4.73 us: 1.05x slower                                                      |
| scimark_fft              | 359 ms                                                       | 382 ms: 1.06x slower                                                       |
| pickle_dict              | 30.0 us                                                      | 32.0 us: 1.07x slower                                                      |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                      |
| regex_effbot             | 2.99 ms                                                      | 3.35 ms: 1.12x slower                                                      |
| comprehensions           | 26.9 us                                                      | 30.4 us: 1.13x slower                                                      |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 5.95 ms: 1.15x slower                                                      |
| telco                    | 7.14 ms                                                      | 8.36 ms: 1.17x slower                                                      |
| gc_traversal             | 3.45 ms                                                      | 4.04 ms: 1.17x slower                                                      |
| python_startup_no_site   | 7.32 ms                                                      | 8.68 ms: 1.18x slower                                                      |
| coverage                 | 64.0 ms                                                      | 80.6 ms: 1.26x slower                                                      |
| Geometric mean           | (ref)                                                        | 1.20x faster                                                               |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.11x
