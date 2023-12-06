
# Results vs. 3.10.4

- fork: python
- ref: v3.11.0
- machine: linux-x86_64
- commit hash: deaf509
- commit date: 2022-10-24
- overall geometric mean: 1.21x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 349 ms                                                       | 286 ms: 1.22x faster                                         |
| chameleon      | 9.88 ms                                                      | 7.42 ms: 1.33x faster                                        |
| docutils       | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                       |
| html5lib       | 94.7 ms                                                      | 70.7 ms: 1.34x faster                                        |
| tornado_http   | 157 ms                                                       | 125 ms: 1.25x faster                                         |
| Geometric mean | (ref)                                                        | 1.27x faster                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_io           | 1.61 sec                                                     | 1.19 sec: 1.35x faster                                       |
| async_tree_none         | 700 ms                                                       | 529 ms: 1.32x faster                                         |
| async_tree_memoization  | 827 ms                                                       | 648 ms: 1.28x faster                                         |
| async_tree_cpu_io_mixed | 946 ms                                                       | 762 ms: 1.24x faster                                         |
| Geometric mean          | (ref)                                                        | 1.30x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 109 ms                                                       | 76.0 ms: 1.43x faster                                        |
| nbody          | 134 ms                                                       | 95.8 ms: 1.40x faster                                        |
| pidigits       | 270 ms                                                       | 251 ms: 1.08x faster                                         |
| Geometric mean | (ref)                                                        | 1.29x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 192 ms                                                       | 157 ms: 1.23x faster                                         |
| regex_dna      | 260 ms                                                       | 226 ms: 1.15x faster                                         |
| regex_v8       | 27.1 ms                                                      | 23.7 ms: 1.14x faster                                        |
| regex_effbot   | 3.10 ms                                                      | 3.42 ms: 1.10x slower                                        |
| Geometric mean | (ref)                                                        | 1.10x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_pure_python   | 453 us                                                       | 318 us: 1.42x faster                                         |
| xml_etree_process    | 76.4 ms                                                      | 56.1 ms: 1.36x faster                                        |
| unpickle_pure_python | 315 us                                                       | 236 us: 1.33x faster                                         |
| tomli_loads          | 2.96 sec                                                     | 2.27 sec: 1.30x faster                                       |
| xml_etree_generate   | 93.1 ms                                                      | 80.5 ms: 1.16x faster                                        |
| pickle_list          | 4.23 us                                                      | 3.89 us: 1.09x faster                                        |
| json_dumps           | 14.2 ms                                                      | 13.5 ms: 1.06x faster                                        |
| unpickle             | 13.9 us                                                      | 13.2 us: 1.06x faster                                        |
| json_loads           | 30.0 us                                                      | 29.0 us: 1.04x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.03x faster                                         |
| pickle               | 10.1 us                                                      | 9.77 us: 1.03x faster                                        |
| unpickle_list        | 4.45 us                                                      | 4.47 us: 1.01x slower                                        |
| pickle_dict          | 30.4 us                                                      | 31.8 us: 1.04x slower                                        |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.8 ms: 1.07x faster                                        |
| python_startup_no_site | 7.35 ms                                                      | 7.78 ms: 1.06x slower                                        |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 11.0 ms: 1.34x faster                                        |
| django_template | 51.8 ms                                                      | 40.4 ms: 1.28x faster                                        |
| genshi_text     | 32.3 ms                                                      | 26.1 ms: 1.24x faster                                        |
| genshi_xml      | 64.1 ms                                                      | 57.2 ms: 1.12x faster                                        |
| Geometric mean  | (ref)                                                        | 1.24x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| deltablue                | 7.43 ms                                                      | 4.03 ms: 1.84x faster                                        |
| scimark_sor              | 183 ms                                                       | 109 ms: 1.67x faster                                         |
| logging_silent           | 168 ns                                                       | 102 ns: 1.65x faster                                         |
| raytrace                 | 497 ms                                                       | 308 ms: 1.62x faster                                         |
| go                       | 258 ms                                                       | 166 ms: 1.56x faster                                         |
| scimark_monte_carlo      | 109 ms                                                       | 70.6 ms: 1.55x faster                                        |
| pyflate                  | 698 ms                                                       | 453 ms: 1.54x faster                                         |
| richards                 | 76.3 ms                                                      | 49.9 ms: 1.53x faster                                        |
| spectral_norm            | 141 ms                                                       | 94.0 ms: 1.50x faster                                        |
| chaos                    | 106 ms                                                       | 71.6 ms: 1.48x faster                                        |
| bench_mp_pool            | 6.82 ms                                                      | 4.63 ms: 1.47x faster                                        |
| sqlglot_parse            | 2.27 ms                                                      | 1.55 ms: 1.46x faster                                        |
| crypto_pyaes             | 118 ms                                                       | 81.8 ms: 1.44x faster                                        |
| float                    | 109 ms                                                       | 76.0 ms: 1.43x faster                                        |
| scimark_lu               | 165 ms                                                       | 115 ms: 1.43x faster                                         |
| richards_super           | 93.0 ms                                                      | 65.2 ms: 1.43x faster                                        |
| pickle_pure_python       | 453 us                                                       | 318 us: 1.42x faster                                         |
| sqlglot_transpile        | 2.73 ms                                                      | 1.94 ms: 1.41x faster                                        |
| nbody                    | 134 ms                                                       | 95.8 ms: 1.40x faster                                        |
| xml_etree_process        | 76.4 ms                                                      | 56.1 ms: 1.36x faster                                        |
| hexiom                   | 9.46 ms                                                      | 6.97 ms: 1.36x faster                                        |
| deepcopy_memo            | 50.5 us                                                      | 37.3 us: 1.35x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.19 sec: 1.35x faster                                       |
| unpack_sequence          | 60.3 ns                                                      | 44.9 ns: 1.34x faster                                        |
| html5lib                 | 94.7 ms                                                      | 70.7 ms: 1.34x faster                                        |
| mako                     | 14.7 ms                                                      | 11.0 ms: 1.34x faster                                        |
| unpickle_pure_python     | 315 us                                                       | 236 us: 1.33x faster                                         |
| pprint_safe_repr         | 1.04 sec                                                     | 780 ms: 1.33x faster                                         |
| chameleon                | 9.88 ms                                                      | 7.42 ms: 1.33x faster                                        |
| async_tree_none          | 700 ms                                                       | 529 ms: 1.32x faster                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.63 sec: 1.32x faster                                       |
| tomli_loads              | 2.96 sec                                                     | 2.27 sec: 1.30x faster                                       |
| async_generators         | 418 ms                                                       | 322 ms: 1.30x faster                                         |
| scimark_sparse_mat_mult  | 5.21 ms                                                      | 4.04 ms: 1.29x faster                                        |
| scimark_fft              | 363 ms                                                       | 281 ms: 1.29x faster                                         |
| pycparser                | 1.65 sec                                                     | 1.28 sec: 1.28x faster                                       |
| django_template          | 51.8 ms                                                      | 40.4 ms: 1.28x faster                                        |
| async_tree_memoization   | 827 ms                                                       | 648 ms: 1.28x faster                                         |
| thrift                   | 1.20 ms                                                      | 941 us: 1.27x faster                                         |
| logging_simple           | 9.06 us                                                      | 7.21 us: 1.26x faster                                        |
| logging_format           | 9.82 us                                                      | 7.83 us: 1.25x faster                                        |
| tornado_http             | 157 ms                                                       | 125 ms: 1.25x faster                                         |
| async_tree_cpu_io_mixed  | 946 ms                                                       | 762 ms: 1.24x faster                                         |
| genshi_text              | 32.3 ms                                                      | 26.1 ms: 1.24x faster                                        |
| aiohttp                  | 1.21 ms                                                      | 984 us: 1.23x faster                                         |
| regex_compile            | 192 ms                                                       | 157 ms: 1.23x faster                                         |
| 2to3                     | 349 ms                                                       | 286 ms: 1.22x faster                                         |
| sqlalchemy_declarative   | 189 ms                                                       | 155 ms: 1.22x faster                                         |
| gunicorn                 | 1.20 ms                                                      | 986 us: 1.22x faster                                         |
| sqlglot_normalize        | 146 ms                                                       | 122 ms: 1.20x faster                                         |
| sqlite_synth             | 2.97 us                                                      | 2.49 us: 1.19x faster                                        |
| docutils                 | 3.42 sec                                                     | 2.87 sec: 1.19x faster                                       |
| deepcopy_reduce          | 4.00 us                                                      | 3.37 us: 1.19x faster                                        |
| deepcopy                 | 459 us                                                       | 389 us: 1.18x faster                                         |
| sqlglot_optimize         | 69.9 ms                                                      | 59.2 ms: 1.18x faster                                        |
| dulwich_log              | 80.0 ms                                                      | 68.3 ms: 1.17x faster                                        |
| xml_etree_generate       | 93.1 ms                                                      | 80.5 ms: 1.16x faster                                        |
| sqlalchemy_imperative    | 23.0 ms                                                      | 19.9 ms: 1.15x faster                                        |
| regex_dna                | 260 ms                                                       | 226 ms: 1.15x faster                                         |
| regex_v8                 | 27.1 ms                                                      | 23.7 ms: 1.14x faster                                        |
| flaskblogging            | 4.44 ms                                                      | 3.92 ms: 1.13x faster                                        |
| nqueens                  | 112 ms                                                       | 99.2 ms: 1.13x faster                                        |
| dask                     | 469 ms                                                       | 417 ms: 1.13x faster                                         |
| create_gc_cycles         | 1.79 ms                                                      | 1.59 ms: 1.12x faster                                        |
| genshi_xml               | 64.1 ms                                                      | 57.2 ms: 1.12x faster                                        |
| bench_thread_pool        | 1.13 ms                                                      | 1.02 ms: 1.11x faster                                        |
| coroutines               | 30.9 ms                                                      | 27.9 ms: 1.11x faster                                        |
| sympy_integrate          | 28.3 ms                                                      | 25.6 ms: 1.11x faster                                        |
| pathlib                  | 21.2 ms                                                      | 19.1 ms: 1.11x faster                                        |
| comprehensions           | 27.0 us                                                      | 24.8 us: 1.09x faster                                        |
| sympy_expand             | 599 ms                                                       | 550 ms: 1.09x faster                                         |
| pickle_list              | 4.23 us                                                      | 3.89 us: 1.09x faster                                        |
| pylint                   | 564 ms                                                       | 521 ms: 1.08x faster                                         |
| mdp                      | 2.94 sec                                                     | 2.72 sec: 1.08x faster                                       |
| pidigits                 | 270 ms                                                       | 251 ms: 1.08x faster                                         |
| sympy_str                | 359 ms                                                       | 336 ms: 1.07x faster                                         |
| fannkuch                 | 488 ms                                                       | 457 ms: 1.07x faster                                         |
| python_startup           | 11.5 ms                                                      | 10.8 ms: 1.07x faster                                        |
| json_dumps               | 14.2 ms                                                      | 13.5 ms: 1.06x faster                                        |
| json                     | 5.91 ms                                                      | 5.59 ms: 1.06x faster                                        |
| unpickle                 | 13.9 us                                                      | 13.2 us: 1.06x faster                                        |
| meteor_contest           | 138 ms                                                       | 130 ms: 1.06x faster                                         |
| sympy_sum                | 194 ms                                                       | 184 ms: 1.05x faster                                         |
| telco                    | 7.21 ms                                                      | 6.91 ms: 1.04x faster                                        |
| asyncio_tcp              | 785 ms                                                       | 752 ms: 1.04x faster                                         |
| json_loads               | 30.0 us                                                      | 29.0 us: 1.04x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.03x faster                                         |
| pickle                   | 10.1 us                                                      | 9.77 us: 1.03x faster                                        |
| generators               | 57.7 ms                                                      | 56.4 ms: 1.02x faster                                        |
| asyncio_websockets       | 394 ms                                                       | 388 ms: 1.01x faster                                         |
| typing_runtime_protocols | 533 us                                                       | 527 us: 1.01x faster                                         |
| asyncio_tcp_ssl          | 3.13 sec                                                     | 3.09 sec: 1.01x faster                                       |
| unpickle_list            | 4.45 us                                                      | 4.47 us: 1.01x slower                                        |
| coverage                 | 65.9 ms                                                      | 66.6 ms: 1.01x slower                                        |
| pickle_dict              | 30.4 us                                                      | 31.8 us: 1.04x slower                                        |
| python_startup_no_site   | 7.35 ms                                                      | 7.78 ms: 1.06x slower                                        |
| regex_effbot             | 3.10 ms                                                      | 3.42 ms: 1.10x slower                                        |
| gc_traversal             | 3.63 ms                                                      | 4.06 ms: 1.12x slower                                        |
| Geometric mean           | (ref)                                                        | 1.21x faster                                                 |

Benchmark hidden because not significant (2): mypy2, xml_etree_parse
Ignored benchmarks (4) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
