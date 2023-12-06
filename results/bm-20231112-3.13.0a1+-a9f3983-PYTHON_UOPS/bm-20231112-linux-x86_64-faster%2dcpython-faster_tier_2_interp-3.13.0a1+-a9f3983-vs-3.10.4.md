
# Results vs. 3.10.4

- fork: faster-cpython
- ref: faster_tier_2_interp
- machine: linux-x86_64
- commit hash: a9f3983
- commit date: 2023-11-12
- overall geometric mean: 1.23x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 293 ms: 1.18x faster                                                             |
| chameleon      | 9.84 ms                                                | 7.56 ms: 1.30x faster                                                            |
| docutils       | 3.26 sec                                               | 2.72 sec: 1.20x faster                                                           |
| tornado_http   | 131 ms                                                 | 102 ms: 1.28x faster                                                             |
| Geometric mean | (ref)                                                  | 1.24x faster                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 462 ms: 1.58x faster                                                             |
| async_tree_memoization  | 867 ms                                                 | 592 ms: 1.46x faster                                                             |
| async_tree_io           | 1.79 sec                                               | 1.23 sec: 1.46x faster                                                           |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 736 ms: 1.37x faster                                                             |
| Geometric mean          | (ref)                                                  | 1.47x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 124 ms: 1.19x faster                                                             |
| float          | 116 ms                                                 | 109 ms: 1.07x faster                                                             |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                                             |
| Geometric mean | (ref)                                                  | 1.07x faster                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 161 ms: 1.15x faster                                                             |
| regex_v8       | 26.2 ms                                                | 24.7 ms: 1.06x faster                                                            |
| regex_dna      | 215 ms                                                 | 214 ms: 1.00x faster                                                             |
| regex_effbot   | 3.41 ms                                                | 3.49 ms: 1.02x slower                                                            |
| Geometric mean | (ref)                                                  | 1.05x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 309 us: 1.56x faster                                                             |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.36x faster                                                            |
| xml_etree_process    | 79.8 ms                                                | 59.2 ms: 1.35x faster                                                            |
| unpickle_pure_python | 327 us                                                 | 249 us: 1.31x faster                                                             |
| xml_etree_generate   | 100.0 ms                                               | 87.0 ms: 1.15x faster                                                            |
| json_loads           | 31.4 us                                                | 28.2 us: 1.12x faster                                                            |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                             |
| xml_etree_iterparse  | 116 ms                                                 | 113 ms: 1.02x faster                                                             |
| tomli_loads          | 3.06 sec                                               | 2.99 sec: 1.02x faster                                                           |
| pickle_list          | 5.05 us                                                | 4.95 us: 1.02x faster                                                            |
| unpickle             | 14.9 us                                                | 14.6 us: 1.02x faster                                                            |
| pickle               | 10.7 us                                                | 11.4 us: 1.07x slower                                                            |
| pickle_dict          | 30.0 us                                                | 33.6 us: 1.12x slower                                                            |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                                     |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                            |
| python_startup_no_site | 5.87 ms                                                | 9.03 ms: 1.54x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 15.2 ms: 1.07x faster                                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 124 us: 4.52x faster                                                             |
| generators               | 78.9 ms                                                | 29.9 ms: 2.64x faster                                                            |
| asyncio_tcp              | 918 ms                                                 | 502 ms: 1.83x faster                                                             |
| logging_silent           | 189 ns                                                 | 107 ns: 1.76x faster                                                             |
| scimark_sor              | 214 ms                                                 | 126 ms: 1.70x faster                                                             |
| richards_super           | 95.6 ms                                                | 59.2 ms: 1.61x faster                                                            |
| sqlglot_parse            | 2.15 ms                                                | 1.34 ms: 1.60x faster                                                            |
| async_tree_none          | 732 ms                                                 | 462 ms: 1.58x faster                                                             |
| raytrace                 | 498 ms                                                 | 316 ms: 1.57x faster                                                             |
| pickle_pure_python       | 482 us                                                 | 309 us: 1.56x faster                                                             |
| coroutines               | 34.5 ms                                                | 22.3 ms: 1.54x faster                                                            |
| sqlglot_transpile        | 2.55 ms                                                | 1.67 ms: 1.53x faster                                                            |
| chaos                    | 114 ms                                                 | 75.7 ms: 1.51x faster                                                            |
| richards                 | 79.4 ms                                                | 52.7 ms: 1.51x faster                                                            |
| spectral_norm            | 163 ms                                                 | 111 ms: 1.48x faster                                                             |
| deltablue                | 7.81 ms                                                | 5.32 ms: 1.47x faster                                                            |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.47x faster                                                             |
| async_tree_memoization   | 867 ms                                                 | 592 ms: 1.46x faster                                                             |
| async_tree_io            | 1.79 sec                                               | 1.23 sec: 1.46x faster                                                           |
| scimark_monte_carlo      | 118 ms                                                 | 81.6 ms: 1.45x faster                                                            |
| crypto_pyaes             | 127 ms                                                 | 88.5 ms: 1.43x faster                                                            |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                                           |
| unpack_sequence          | 65.7 ns                                                | 46.6 ns: 1.41x faster                                                            |
| go                       | 238 ms                                                 | 170 ms: 1.40x faster                                                             |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                            |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 736 ms: 1.37x faster                                                             |
| deepcopy_memo            | 58.8 us                                                | 43.3 us: 1.36x faster                                                            |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.36x faster                                                            |
| xml_etree_process        | 79.8 ms                                                | 59.2 ms: 1.35x faster                                                            |
| deepcopy                 | 481 us                                                 | 359 us: 1.34x faster                                                             |
| logging_simple           | 8.27 us                                                | 6.28 us: 1.32x faster                                                            |
| unpickle_pure_python     | 327 us                                                 | 249 us: 1.31x faster                                                             |
| sqlglot_normalize        | 141 ms                                                 | 108 ms: 1.31x faster                                                             |
| chameleon                | 9.84 ms                                                | 7.56 ms: 1.30x faster                                                            |
| deepcopy_reduce          | 4.17 us                                                | 3.21 us: 1.30x faster                                                            |
| tornado_http             | 131 ms                                                 | 102 ms: 1.28x faster                                                             |
| logging_format           | 9.07 us                                                | 7.18 us: 1.26x faster                                                            |
| sqlglot_optimize         | 68.7 ms                                                | 54.9 ms: 1.25x faster                                                            |
| mypy2                    | 442 ms                                                 | 355 ms: 1.25x faster                                                             |
| pycparser                | 1.57 sec                                               | 1.26 sec: 1.24x faster                                                           |
| sympy_sum                | 190 ms                                                 | 154 ms: 1.24x faster                                                             |
| pyflate                  | 708 ms                                                 | 573 ms: 1.24x faster                                                             |
| pprint_pformat           | 2.10 sec                                               | 1.71 sec: 1.23x faster                                                           |
| pprint_safe_repr         | 1.01 sec                                               | 833 ms: 1.22x faster                                                             |
| docutils                 | 3.26 sec                                               | 2.72 sec: 1.20x faster                                                           |
| nbody                    | 148 ms                                                 | 124 ms: 1.19x faster                                                             |
| 2to3                     | 346 ms                                                 | 293 ms: 1.18x faster                                                             |
| sympy_integrate          | 25.4 ms                                                | 21.5 ms: 1.18x faster                                                            |
| sympy_str                | 337 ms                                                 | 287 ms: 1.17x faster                                                             |
| sympy_expand             | 558 ms                                                 | 483 ms: 1.15x faster                                                             |
| regex_compile            | 186 ms                                                 | 161 ms: 1.15x faster                                                             |
| xml_etree_generate       | 100.0 ms                                               | 87.0 ms: 1.15x faster                                                            |
| bench_thread_pool        | 966 us                                                 | 860 us: 1.12x faster                                                             |
| json_loads               | 31.4 us                                                | 28.2 us: 1.12x faster                                                            |
| dulwich_log              | 77.0 ms                                                | 69.2 ms: 1.11x faster                                                            |
| json                     | 5.67 ms                                                | 5.12 ms: 1.11x faster                                                            |
| create_gc_cycles         | 1.61 ms                                                | 1.49 ms: 1.08x faster                                                            |
| pathlib                  | 20.3 ms                                                | 18.8 ms: 1.08x faster                                                            |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                             |
| comprehensions           | 28.5 us                                                | 26.5 us: 1.08x faster                                                            |
| mako                     | 16.3 ms                                                | 15.2 ms: 1.07x faster                                                            |
| float                    | 116 ms                                                 | 109 ms: 1.07x faster                                                             |
| regex_v8                 | 26.2 ms                                                | 24.7 ms: 1.06x faster                                                            |
| mdp                      | 2.93 sec                                               | 2.78 sec: 1.06x faster                                                           |
| sqlite_synth             | 3.02 us                                                | 2.91 us: 1.04x faster                                                            |
| scimark_fft              | 454 ms                                                 | 440 ms: 1.03x faster                                                             |
| fannkuch                 | 527 ms                                                 | 512 ms: 1.03x faster                                                             |
| xml_etree_iterparse      | 116 ms                                                 | 113 ms: 1.02x faster                                                             |
| tomli_loads              | 3.06 sec                                               | 2.99 sec: 1.02x faster                                                           |
| pickle_list              | 5.05 us                                                | 4.95 us: 1.02x faster                                                            |
| unpickle                 | 14.9 us                                                | 14.6 us: 1.02x faster                                                            |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                                             |
| regex_dna                | 215 ms                                                 | 214 ms: 1.00x faster                                                             |
| meteor_contest           | 119 ms                                                 | 120 ms: 1.01x slower                                                             |
| regex_effbot             | 3.41 ms                                                | 3.49 ms: 1.02x slower                                                            |
| hexiom                   | 10.3 ms                                                | 10.6 ms: 1.03x slower                                                            |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                                             |
| nqueens                  | 107 ms                                                 | 113 ms: 1.06x slower                                                             |
| async_generators         | 442 ms                                                 | 468 ms: 1.06x slower                                                             |
| pickle                   | 10.7 us                                                | 11.4 us: 1.07x slower                                                            |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.66 ms: 1.09x slower                                                            |
| gc_traversal             | 3.43 ms                                                | 3.82 ms: 1.11x slower                                                            |
| pickle_dict              | 30.0 us                                                | 33.6 us: 1.12x slower                                                            |
| coverage                 | 82.0 ms                                                | 95.3 ms: 1.16x slower                                                            |
| telco                    | 7.01 ms                                                | 8.98 ms: 1.28x slower                                                            |
| python_startup_no_site   | 5.87 ms                                                | 9.03 ms: 1.54x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.23x faster                                                                     |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle_list
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231112-3.13.0a1+-a9f3983-PYTHON_UOPS/bm-20231112-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-a9f3983.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.14x
