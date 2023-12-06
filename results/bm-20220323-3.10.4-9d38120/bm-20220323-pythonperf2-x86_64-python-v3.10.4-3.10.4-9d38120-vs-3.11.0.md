
# Results vs. 3.11.0

- fork: python
- ref: v3.10.4
- machine: linux-x86_64
- commit hash: 9d38120
- commit date: 2022-03-23
- overall geometric mean: 1.21x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 349 ms: 1.22x slower                                         |
| chameleon      | 7.42 ms                                                      | 9.88 ms: 1.33x slower                                        |
| docutils       | 2.87 sec                                                     | 3.42 sec: 1.19x slower                                       |
| html5lib       | 70.7 ms                                                      | 94.7 ms: 1.34x slower                                        |
| tornado_http   | 125 ms                                                       | 157 ms: 1.25x slower                                         |
| Geometric mean | (ref)                                                        | 1.27x slower                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 762 ms                                                       | 946 ms: 1.24x slower                                         |
| async_tree_memoization  | 648 ms                                                       | 827 ms: 1.28x slower                                         |
| async_tree_none         | 529 ms                                                       | 700 ms: 1.32x slower                                         |
| async_tree_io           | 1.19 sec                                                     | 1.61 sec: 1.35x slower                                       |
| Geometric mean          | (ref)                                                        | 1.30x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 270 ms: 1.08x slower                                         |
| nbody          | 95.8 ms                                                      | 134 ms: 1.40x slower                                         |
| float          | 76.0 ms                                                      | 109 ms: 1.43x slower                                         |
| Geometric mean | (ref)                                                        | 1.29x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.10 ms: 1.10x faster                                        |
| regex_v8       | 23.7 ms                                                      | 27.1 ms: 1.14x slower                                        |
| regex_dna      | 226 ms                                                       | 260 ms: 1.15x slower                                         |
| regex_compile  | 157 ms                                                       | 192 ms: 1.23x slower                                         |
| Geometric mean | (ref)                                                        | 1.10x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_dict          | 31.8 us                                                      | 30.4 us: 1.04x faster                                        |
| unpickle_list        | 4.47 us                                                      | 4.45 us: 1.01x faster                                        |
| pickle               | 9.77 us                                                      | 10.1 us: 1.03x slower                                        |
| xml_etree_iterparse  | 106 ms                                                       | 110 ms: 1.03x slower                                         |
| json_loads           | 29.0 us                                                      | 30.0 us: 1.04x slower                                        |
| unpickle             | 13.2 us                                                      | 13.9 us: 1.06x slower                                        |
| json_dumps           | 13.5 ms                                                      | 14.2 ms: 1.06x slower                                        |
| pickle_list          | 3.89 us                                                      | 4.23 us: 1.09x slower                                        |
| xml_etree_generate   | 80.5 ms                                                      | 93.1 ms: 1.16x slower                                        |
| tomli_loads          | 2.27 sec                                                     | 2.96 sec: 1.30x slower                                       |
| unpickle_pure_python | 236 us                                                       | 315 us: 1.33x slower                                         |
| xml_etree_process    | 56.1 ms                                                      | 76.4 ms: 1.36x slower                                        |
| pickle_pure_python   | 318 us                                                       | 453 us: 1.42x slower                                         |
| Geometric mean       | (ref)                                                        | 1.12x slower                                                 |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 7.78 ms                                                      | 7.35 ms: 1.06x faster                                        |
| python_startup         | 10.8 ms                                                      | 11.5 ms: 1.07x slower                                        |
| Geometric mean         | (ref)                                                        | 1.00x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| genshi_xml      | 57.2 ms                                                      | 64.1 ms: 1.12x slower                                        |
| genshi_text     | 26.1 ms                                                      | 32.3 ms: 1.24x slower                                        |
| django_template | 40.4 ms                                                      | 51.8 ms: 1.28x slower                                        |
| mako            | 11.0 ms                                                      | 14.7 ms: 1.34x slower                                        |
| Geometric mean  | (ref)                                                        | 1.24x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| gc_traversal             | 4.06 ms                                                      | 3.63 ms: 1.12x faster                                        |
| regex_effbot             | 3.42 ms                                                      | 3.10 ms: 1.10x faster                                        |
| python_startup_no_site   | 7.78 ms                                                      | 7.35 ms: 1.06x faster                                        |
| pickle_dict              | 31.8 us                                                      | 30.4 us: 1.04x faster                                        |
| coverage                 | 66.6 ms                                                      | 65.9 ms: 1.01x faster                                        |
| unpickle_list            | 4.47 us                                                      | 4.45 us: 1.01x faster                                        |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 3.13 sec: 1.01x slower                                       |
| typing_runtime_protocols | 527 us                                                       | 533 us: 1.01x slower                                         |
| asyncio_websockets       | 388 ms                                                       | 394 ms: 1.01x slower                                         |
| generators               | 56.4 ms                                                      | 57.7 ms: 1.02x slower                                        |
| pickle                   | 9.77 us                                                      | 10.1 us: 1.03x slower                                        |
| xml_etree_iterparse      | 106 ms                                                       | 110 ms: 1.03x slower                                         |
| json_loads               | 29.0 us                                                      | 30.0 us: 1.04x slower                                        |
| asyncio_tcp              | 752 ms                                                       | 785 ms: 1.04x slower                                         |
| telco                    | 6.91 ms                                                      | 7.21 ms: 1.04x slower                                        |
| sympy_sum                | 184 ms                                                       | 194 ms: 1.05x slower                                         |
| meteor_contest           | 130 ms                                                       | 138 ms: 1.06x slower                                         |
| unpickle                 | 13.2 us                                                      | 13.9 us: 1.06x slower                                        |
| json                     | 5.59 ms                                                      | 5.91 ms: 1.06x slower                                        |
| json_dumps               | 13.5 ms                                                      | 14.2 ms: 1.06x slower                                        |
| python_startup           | 10.8 ms                                                      | 11.5 ms: 1.07x slower                                        |
| fannkuch                 | 457 ms                                                       | 488 ms: 1.07x slower                                         |
| sympy_str                | 336 ms                                                       | 359 ms: 1.07x slower                                         |
| pidigits                 | 251 ms                                                       | 270 ms: 1.08x slower                                         |
| mdp                      | 2.72 sec                                                     | 2.94 sec: 1.08x slower                                       |
| pylint                   | 521 ms                                                       | 564 ms: 1.08x slower                                         |
| pickle_list              | 3.89 us                                                      | 4.23 us: 1.09x slower                                        |
| sympy_expand             | 550 ms                                                       | 599 ms: 1.09x slower                                         |
| comprehensions           | 24.8 us                                                      | 27.0 us: 1.09x slower                                        |
| pathlib                  | 19.1 ms                                                      | 21.2 ms: 1.11x slower                                        |
| sympy_integrate          | 25.6 ms                                                      | 28.3 ms: 1.11x slower                                        |
| coroutines               | 27.9 ms                                                      | 30.9 ms: 1.11x slower                                        |
| bench_thread_pool        | 1.02 ms                                                      | 1.13 ms: 1.11x slower                                        |
| genshi_xml               | 57.2 ms                                                      | 64.1 ms: 1.12x slower                                        |
| create_gc_cycles         | 1.59 ms                                                      | 1.79 ms: 1.12x slower                                        |
| dask                     | 417 ms                                                       | 469 ms: 1.13x slower                                         |
| nqueens                  | 99.2 ms                                                      | 112 ms: 1.13x slower                                         |
| flaskblogging            | 3.92 ms                                                      | 4.44 ms: 1.13x slower                                        |
| regex_v8                 | 23.7 ms                                                      | 27.1 ms: 1.14x slower                                        |
| regex_dna                | 226 ms                                                       | 260 ms: 1.15x slower                                         |
| sqlalchemy_imperative    | 19.9 ms                                                      | 23.0 ms: 1.15x slower                                        |
| xml_etree_generate       | 80.5 ms                                                      | 93.1 ms: 1.16x slower                                        |
| dulwich_log              | 68.3 ms                                                      | 80.0 ms: 1.17x slower                                        |
| sqlglot_optimize         | 59.2 ms                                                      | 69.9 ms: 1.18x slower                                        |
| deepcopy                 | 389 us                                                       | 459 us: 1.18x slower                                         |
| deepcopy_reduce          | 3.37 us                                                      | 4.00 us: 1.19x slower                                        |
| docutils                 | 2.87 sec                                                     | 3.42 sec: 1.19x slower                                       |
| sqlite_synth             | 2.49 us                                                      | 2.97 us: 1.19x slower                                        |
| sqlglot_normalize        | 122 ms                                                       | 146 ms: 1.20x slower                                         |
| gunicorn                 | 986 us                                                       | 1.20 ms: 1.22x slower                                        |
| sqlalchemy_declarative   | 155 ms                                                       | 189 ms: 1.22x slower                                         |
| 2to3                     | 286 ms                                                       | 349 ms: 1.22x slower                                         |
| regex_compile            | 157 ms                                                       | 192 ms: 1.23x slower                                         |
| aiohttp                  | 984 us                                                       | 1.21 ms: 1.23x slower                                        |
| genshi_text              | 26.1 ms                                                      | 32.3 ms: 1.24x slower                                        |
| async_tree_cpu_io_mixed  | 762 ms                                                       | 946 ms: 1.24x slower                                         |
| tornado_http             | 125 ms                                                       | 157 ms: 1.25x slower                                         |
| logging_format           | 7.83 us                                                      | 9.82 us: 1.25x slower                                        |
| logging_simple           | 7.21 us                                                      | 9.06 us: 1.26x slower                                        |
| thrift                   | 941 us                                                       | 1.20 ms: 1.27x slower                                        |
| async_tree_memoization   | 648 ms                                                       | 827 ms: 1.28x slower                                         |
| django_template          | 40.4 ms                                                      | 51.8 ms: 1.28x slower                                        |
| pycparser                | 1.28 sec                                                     | 1.65 sec: 1.28x slower                                       |
| scimark_fft              | 281 ms                                                       | 363 ms: 1.29x slower                                         |
| scimark_sparse_mat_mult  | 4.04 ms                                                      | 5.21 ms: 1.29x slower                                        |
| async_generators         | 322 ms                                                       | 418 ms: 1.30x slower                                         |
| tomli_loads              | 2.27 sec                                                     | 2.96 sec: 1.30x slower                                       |
| pprint_pformat           | 1.63 sec                                                     | 2.15 sec: 1.32x slower                                       |
| async_tree_none          | 529 ms                                                       | 700 ms: 1.32x slower                                         |
| chameleon                | 7.42 ms                                                      | 9.88 ms: 1.33x slower                                        |
| pprint_safe_repr         | 780 ms                                                       | 1.04 sec: 1.33x slower                                       |
| unpickle_pure_python     | 236 us                                                       | 315 us: 1.33x slower                                         |
| mako                     | 11.0 ms                                                      | 14.7 ms: 1.34x slower                                        |
| html5lib                 | 70.7 ms                                                      | 94.7 ms: 1.34x slower                                        |
| unpack_sequence          | 44.9 ns                                                      | 60.3 ns: 1.34x slower                                        |
| async_tree_io            | 1.19 sec                                                     | 1.61 sec: 1.35x slower                                       |
| deepcopy_memo            | 37.3 us                                                      | 50.5 us: 1.35x slower                                        |
| hexiom                   | 6.97 ms                                                      | 9.46 ms: 1.36x slower                                        |
| xml_etree_process        | 56.1 ms                                                      | 76.4 ms: 1.36x slower                                        |
| nbody                    | 95.8 ms                                                      | 134 ms: 1.40x slower                                         |
| sqlglot_transpile        | 1.94 ms                                                      | 2.73 ms: 1.41x slower                                        |
| pickle_pure_python       | 318 us                                                       | 453 us: 1.42x slower                                         |
| richards_super           | 65.2 ms                                                      | 93.0 ms: 1.43x slower                                        |
| scimark_lu               | 115 ms                                                       | 165 ms: 1.43x slower                                         |
| float                    | 76.0 ms                                                      | 109 ms: 1.43x slower                                         |
| crypto_pyaes             | 81.8 ms                                                      | 118 ms: 1.44x slower                                         |
| sqlglot_parse            | 1.55 ms                                                      | 2.27 ms: 1.46x slower                                        |
| bench_mp_pool            | 4.63 ms                                                      | 6.82 ms: 1.47x slower                                        |
| chaos                    | 71.6 ms                                                      | 106 ms: 1.48x slower                                         |
| spectral_norm            | 94.0 ms                                                      | 141 ms: 1.50x slower                                         |
| richards                 | 49.9 ms                                                      | 76.3 ms: 1.53x slower                                        |
| pyflate                  | 453 ms                                                       | 698 ms: 1.54x slower                                         |
| scimark_monte_carlo      | 70.6 ms                                                      | 109 ms: 1.55x slower                                         |
| go                       | 166 ms                                                       | 258 ms: 1.56x slower                                         |
| raytrace                 | 308 ms                                                       | 497 ms: 1.62x slower                                         |
| logging_silent           | 102 ns                                                       | 168 ns: 1.65x slower                                         |
| scimark_sor              | 109 ms                                                       | 183 ms: 1.67x slower                                         |
| deltablue                | 4.03 ms                                                      | 7.43 ms: 1.84x slower                                        |
| Geometric mean           | (ref)                                                        | 1.21x slower                                                 |

Benchmark hidden because not significant (2): xml_etree_parse, mypy2
Ignored benchmarks (4) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.18x
- 95% likely to have a slowdown of 1.17x
- 99% likely to have a slowdown of 1.15x
