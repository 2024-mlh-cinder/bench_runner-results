
# Results vs. 3.10.4

- fork: python
- ref: v3.11.6
- machine: linux-x86_64
- commit hash: 8b6ee5b
- commit date: 2023-10-02
- overall geometric mean: 1.22x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 285 ms: 1.22x faster                                         |
| chameleon      | 9.72 ms                                                      | 7.64 ms: 1.27x faster                                        |
| docutils       | 3.40 sec                                                     | 2.83 sec: 1.20x faster                                       |
| html5lib       | 94.6 ms                                                      | 71.9 ms: 1.32x faster                                        |
| tornado_http   | 152 ms                                                       | 123 ms: 1.24x faster                                         |
| Geometric mean | (ref)                                                        | 1.25x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 110 ms                                                       | 76.4 ms: 1.44x faster                                        |
| nbody          | 137 ms                                                       | 96.9 ms: 1.42x faster                                        |
| pidigits       | 271 ms                                                       | 268 ms: 1.01x faster                                         |
| Geometric mean | (ref)                                                        | 1.27x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 157 ms: 1.24x faster                                         |
| regex_dna      | 259 ms                                                       | 220 ms: 1.18x faster                                         |
| regex_v8       | 26.6 ms                                                      | 23.2 ms: 1.15x faster                                        |
| regex_effbot   | 2.99 ms                                                      | 3.29 ms: 1.10x slower                                        |
| Geometric mean | (ref)                                                        | 1.11x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 315 us: 1.45x faster                                         |
| xml_etree_process    | 76.0 ms                                                      | 55.8 ms: 1.36x faster                                        |
| unpickle_pure_python | 321 us                                                       | 239 us: 1.34x faster                                         |
| tomli_loads          | 2.97 sec                                                     | 2.28 sec: 1.30x faster                                       |
| json_loads           | 30.0 us                                                      | 24.6 us: 1.22x faster                                        |
| xml_etree_generate   | 94.6 ms                                                      | 79.8 ms: 1.19x faster                                        |
| pickle_list          | 4.11 us                                                      | 3.77 us: 1.09x faster                                        |
| json_dumps           | 14.2 ms                                                      | 13.3 ms: 1.07x faster                                        |
| unpickle             | 14.2 us                                                      | 13.3 us: 1.07x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.05x faster                                         |
| xml_etree_parse      | 162 ms                                                       | 159 ms: 1.01x faster                                         |
| pickle               | 9.94 us                                                      | 9.99 us: 1.01x slower                                        |
| unpickle_list        | 4.49 us                                                      | 4.69 us: 1.04x slower                                        |
| pickle_dict          | 30.0 us                                                      | 32.1 us: 1.07x slower                                        |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.8 ms: 1.06x faster                                        |
| python_startup_no_site | 7.32 ms                                                      | 7.81 ms: 1.07x slower                                        |
| Geometric mean         | (ref)                                                        | 1.00x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.8 ms: 1.36x faster                                        |
| django_template | 51.5 ms                                                      | 40.5 ms: 1.27x faster                                        |
| genshi_text     | 31.5 ms                                                      | 25.4 ms: 1.24x faster                                        |
| genshi_xml      | 64.7 ms                                                      | 56.3 ms: 1.15x faster                                        |
| Geometric mean  | (ref)                                                        | 1.25x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| deltablue                | 7.47 ms                                                      | 3.97 ms: 1.88x faster                                        |
| logging_silent           | 166 ns                                                       | 101 ns: 1.64x faster                                         |
| raytrace                 | 488 ms                                                       | 301 ms: 1.62x faster                                         |
| scimark_monte_carlo      | 109 ms                                                       | 68.3 ms: 1.60x faster                                        |
| go                       | 259 ms                                                       | 162 ms: 1.60x faster                                         |
| scimark_sor              | 177 ms                                                       | 112 ms: 1.58x faster                                         |
| pyflate                  | 697 ms                                                       | 442 ms: 1.58x faster                                         |
| richards                 | 74.1 ms                                                      | 49.6 ms: 1.49x faster                                        |
| bench_mp_pool            | 7.18 ms                                                      | 4.82 ms: 1.49x faster                                        |
| sqlglot_parse            | 2.26 ms                                                      | 1.53 ms: 1.47x faster                                        |
| chaos                    | 107 ms                                                       | 73.4 ms: 1.46x faster                                        |
| pickle_pure_python       | 457 us                                                       | 315 us: 1.45x faster                                         |
| float                    | 110 ms                                                       | 76.4 ms: 1.44x faster                                        |
| scimark_lu               | 164 ms                                                       | 114 ms: 1.44x faster                                         |
| crypto_pyaes             | 118 ms                                                       | 82.4 ms: 1.44x faster                                        |
| richards_super           | 90.8 ms                                                      | 63.6 ms: 1.43x faster                                        |
| sqlglot_transpile        | 2.71 ms                                                      | 1.91 ms: 1.42x faster                                        |
| nbody                    | 137 ms                                                       | 96.9 ms: 1.42x faster                                        |
| spectral_norm            | 136 ms                                                       | 97.3 ms: 1.40x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.17 sec: 1.37x faster                                       |
| hexiom                   | 9.52 ms                                                      | 6.97 ms: 1.37x faster                                        |
| xml_etree_process        | 76.0 ms                                                      | 55.8 ms: 1.36x faster                                        |
| mako                     | 14.7 ms                                                      | 10.8 ms: 1.36x faster                                        |
| pprint_safe_repr         | 1.05 sec                                                     | 775 ms: 1.35x faster                                         |
| async_tree_none          | 700 ms                                                       | 519 ms: 1.35x faster                                         |
| unpickle_pure_python     | 321 us                                                       | 239 us: 1.34x faster                                         |
| async_generators         | 422 ms                                                       | 316 ms: 1.34x faster                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.61 sec: 1.34x faster                                       |
| async_tree_memoization   | 824 ms                                                       | 622 ms: 1.33x faster                                         |
| html5lib                 | 94.6 ms                                                      | 71.9 ms: 1.32x faster                                        |
| unpack_sequence          | 59.5 ns                                                      | 45.6 ns: 1.31x faster                                        |
| deepcopy_memo            | 48.9 us                                                      | 37.5 us: 1.30x faster                                        |
| pycparser                | 1.66 sec                                                     | 1.28 sec: 1.30x faster                                       |
| tomli_loads              | 2.97 sec                                                     | 2.28 sec: 1.30x faster                                       |
| logging_simple           | 8.90 us                                                      | 6.96 us: 1.28x faster                                        |
| django_template          | 51.5 ms                                                      | 40.5 ms: 1.27x faster                                        |
| chameleon                | 9.72 ms                                                      | 7.64 ms: 1.27x faster                                        |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 751 ms: 1.27x faster                                         |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.11 ms: 1.26x faster                                        |
| scimark_fft              | 359 ms                                                       | 286 ms: 1.26x faster                                         |
| logging_format           | 9.57 us                                                      | 7.66 us: 1.25x faster                                        |
| genshi_text              | 31.5 ms                                                      | 25.4 ms: 1.24x faster                                        |
| tornado_http             | 152 ms                                                       | 123 ms: 1.24x faster                                         |
| regex_compile            | 194 ms                                                       | 157 ms: 1.24x faster                                         |
| aiohttp                  | 1.21 ms                                                      | 984 us: 1.23x faster                                         |
| dulwich_log              | 80.1 ms                                                      | 65.3 ms: 1.23x faster                                        |
| 2to3                     | 350 ms                                                       | 285 ms: 1.22x faster                                         |
| json_loads               | 30.0 us                                                      | 24.6 us: 1.22x faster                                        |
| thrift                   | 1.16 ms                                                      | 958 us: 1.22x faster                                         |
| sqlalchemy_declarative   | 187 ms                                                       | 155 ms: 1.21x faster                                         |
| docutils                 | 3.40 sec                                                     | 2.83 sec: 1.20x faster                                       |
| gunicorn                 | 1.17 ms                                                      | 977 us: 1.20x faster                                         |
| sqlglot_optimize         | 70.3 ms                                                      | 58.6 ms: 1.20x faster                                        |
| sqlglot_normalize        | 144 ms                                                       | 121 ms: 1.19x faster                                         |
| sqlite_synth             | 2.97 us                                                      | 2.50 us: 1.19x faster                                        |
| deepcopy_reduce          | 4.03 us                                                      | 3.39 us: 1.19x faster                                        |
| xml_etree_generate       | 94.6 ms                                                      | 79.8 ms: 1.19x faster                                        |
| deepcopy                 | 454 us                                                       | 383 us: 1.19x faster                                         |
| regex_dna                | 259 ms                                                       | 220 ms: 1.18x faster                                         |
| genshi_xml               | 64.7 ms                                                      | 56.3 ms: 1.15x faster                                        |
| regex_v8                 | 26.6 ms                                                      | 23.2 ms: 1.15x faster                                        |
| sqlalchemy_imperative    | 22.6 ms                                                      | 19.7 ms: 1.15x faster                                        |
| json                     | 5.96 ms                                                      | 5.23 ms: 1.14x faster                                        |
| dask                     | 463 ms                                                       | 407 ms: 1.14x faster                                         |
| bench_thread_pool        | 1.14 ms                                                      | 1.00 ms: 1.13x faster                                        |
| fannkuch                 | 496 ms                                                       | 437 ms: 1.13x faster                                         |
| pathlib                  | 21.7 ms                                                      | 19.2 ms: 1.13x faster                                        |
| create_gc_cycles         | 1.82 ms                                                      | 1.61 ms: 1.13x faster                                        |
| flaskblogging            | 4.39 ms                                                      | 3.89 ms: 1.13x faster                                        |
| nqueens                  | 112 ms                                                       | 101 ms: 1.11x faster                                         |
| pylint                   | 562 ms                                                       | 514 ms: 1.09x faster                                         |
| coroutines               | 30.4 ms                                                      | 27.9 ms: 1.09x faster                                        |
| pickle_list              | 4.11 us                                                      | 3.77 us: 1.09x faster                                        |
| sympy_expand             | 599 ms                                                       | 550 ms: 1.09x faster                                         |
| comprehensions           | 26.9 us                                                      | 24.8 us: 1.08x faster                                        |
| sympy_integrate          | 28.1 ms                                                      | 25.9 ms: 1.08x faster                                        |
| sympy_str                | 358 ms                                                       | 335 ms: 1.07x faster                                         |
| generators               | 58.0 ms                                                      | 54.3 ms: 1.07x faster                                        |
| meteor_contest           | 137 ms                                                       | 128 ms: 1.07x faster                                         |
| json_dumps               | 14.2 ms                                                      | 13.3 ms: 1.07x faster                                        |
| unpickle                 | 14.2 us                                                      | 13.3 us: 1.07x faster                                        |
| python_startup           | 11.5 ms                                                      | 10.8 ms: 1.06x faster                                        |
| mdp                      | 3.03 sec                                                     | 2.86 sec: 1.06x faster                                       |
| telco                    | 7.14 ms                                                      | 6.80 ms: 1.05x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.05x faster                                         |
| asyncio_tcp              | 782 ms                                                       | 747 ms: 1.05x faster                                         |
| sympy_sum                | 193 ms                                                       | 184 ms: 1.05x faster                                         |
| xml_etree_parse          | 162 ms                                                       | 159 ms: 1.01x faster                                         |
| pidigits                 | 271 ms                                                       | 268 ms: 1.01x faster                                         |
| typing_runtime_protocols | 523 us                                                       | 519 us: 1.01x faster                                         |
| pickle                   | 9.94 us                                                      | 9.99 us: 1.01x slower                                        |
| unpickle_list            | 4.49 us                                                      | 4.69 us: 1.04x slower                                        |
| python_startup_no_site   | 7.32 ms                                                      | 7.81 ms: 1.07x slower                                        |
| pickle_dict              | 30.0 us                                                      | 32.1 us: 1.07x slower                                        |
| regex_effbot             | 2.99 ms                                                      | 3.29 ms: 1.10x slower                                        |
| mypy2                    | 466 ms                                                       | 534 ms: 1.14x slower                                         |
| gc_traversal             | 3.45 ms                                                      | 3.97 ms: 1.15x slower                                        |
| Geometric mean           | (ref)                                                        | 1.22x faster                                                 |

Benchmark hidden because not significant (1): asyncio_tcp_ssl
Ignored benchmarks (1) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: coverage


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
