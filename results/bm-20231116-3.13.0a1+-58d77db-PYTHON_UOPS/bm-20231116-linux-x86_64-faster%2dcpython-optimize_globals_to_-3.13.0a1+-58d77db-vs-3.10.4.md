
# Results vs. 3.10.4

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 58d77db
- commit date: 2023-11-16
- overall geometric mean: 1.24x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 285 ms: 1.21x faster                                                             |
| chameleon      | 9.84 ms                                                | 7.40 ms: 1.33x faster                                                            |
| docutils       | 3.26 sec                                               | 2.70 sec: 1.21x faster                                                           |
| tornado_http   | 131 ms                                                 | 99.9 ms: 1.31x faster                                                            |
| Geometric mean | (ref)                                                  | 1.26x faster                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 460 ms: 1.59x faster                                                             |
| async_tree_memoization  | 867 ms                                                 | 588 ms: 1.48x faster                                                             |
| async_tree_io           | 1.79 sec                                               | 1.23 sec: 1.46x faster                                                           |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 734 ms: 1.37x faster                                                             |
| Geometric mean          | (ref)                                                  | 1.47x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 114 ms: 1.30x faster                                                             |
| float          | 116 ms                                                 | 101 ms: 1.15x faster                                                             |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| Geometric mean | (ref)                                                  | 1.15x faster                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 162 ms: 1.15x faster                                                             |
| regex_v8       | 26.2 ms                                                | 24.8 ms: 1.06x faster                                                            |
| regex_dna      | 215 ms                                                 | 217 ms: 1.01x slower                                                             |
| regex_effbot   | 3.41 ms                                                | 3.62 ms: 1.06x slower                                                            |
| Geometric mean | (ref)                                                  | 1.03x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 308 us: 1.57x faster                                                             |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                            |
| xml_etree_process    | 79.8 ms                                                | 59.4 ms: 1.34x faster                                                            |
| unpickle_pure_python | 327 us                                                 | 248 us: 1.32x faster                                                             |
| xml_etree_generate   | 100.0 ms                                               | 87.7 ms: 1.14x faster                                                            |
| json_loads           | 31.4 us                                                | 28.2 us: 1.12x faster                                                            |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                             |
| tomli_loads          | 3.06 sec                                               | 2.86 sec: 1.07x faster                                                           |
| xml_etree_iterparse  | 116 ms                                                 | 112 ms: 1.04x faster                                                             |
| unpickle_list        | 5.10 us                                                | 5.06 us: 1.01x faster                                                            |
| pickle_list          | 5.05 us                                                | 5.08 us: 1.01x slower                                                            |
| pickle               | 10.7 us                                                | 11.7 us: 1.10x slower                                                            |
| pickle_dict          | 30.0 us                                                | 36.3 us: 1.21x slower                                                            |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                                     |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                            |
| python_startup_no_site | 5.87 ms                                                | 9.08 ms: 1.55x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 14.7 ms: 1.11x faster                                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 123 us: 4.57x faster                                                             |
| generators               | 78.9 ms                                                | 30.2 ms: 2.62x faster                                                            |
| asyncio_tcp              | 918 ms                                                 | 496 ms: 1.85x faster                                                             |
| logging_silent           | 189 ns                                                 | 107 ns: 1.76x faster                                                             |
| richards_super           | 95.6 ms                                                | 57.4 ms: 1.67x faster                                                            |
| scimark_sor              | 214 ms                                                 | 129 ms: 1.67x faster                                                             |
| raytrace                 | 498 ms                                                 | 305 ms: 1.63x faster                                                             |
| sqlglot_parse            | 2.15 ms                                                | 1.34 ms: 1.60x faster                                                            |
| async_tree_none          | 732 ms                                                 | 460 ms: 1.59x faster                                                             |
| richards                 | 79.4 ms                                                | 50.5 ms: 1.57x faster                                                            |
| deltablue                | 7.81 ms                                                | 4.98 ms: 1.57x faster                                                            |
| pickle_pure_python       | 482 us                                                 | 308 us: 1.57x faster                                                             |
| chaos                    | 114 ms                                                 | 73.2 ms: 1.56x faster                                                            |
| coroutines               | 34.5 ms                                                | 22.3 ms: 1.55x faster                                                            |
| sqlglot_transpile        | 2.55 ms                                                | 1.67 ms: 1.53x faster                                                            |
| crypto_pyaes             | 127 ms                                                 | 84.9 ms: 1.49x faster                                                            |
| async_tree_memoization   | 867 ms                                                 | 588 ms: 1.48x faster                                                             |
| async_tree_io            | 1.79 sec                                               | 1.23 sec: 1.46x faster                                                           |
| spectral_norm            | 163 ms                                                 | 113 ms: 1.44x faster                                                             |
| scimark_monte_carlo      | 118 ms                                                 | 82.2 ms: 1.43x faster                                                            |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                                           |
| scimark_lu               | 175 ms                                                 | 123 ms: 1.43x faster                                                             |
| unpack_sequence          | 65.7 ns                                                | 47.3 ns: 1.39x faster                                                            |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                            |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 734 ms: 1.37x faster                                                             |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                            |
| deepcopy_memo            | 58.8 us                                                | 43.1 us: 1.36x faster                                                            |
| deepcopy                 | 481 us                                                 | 355 us: 1.36x faster                                                             |
| xml_etree_process        | 79.8 ms                                                | 59.4 ms: 1.34x faster                                                            |
| logging_simple           | 8.27 us                                                | 6.22 us: 1.33x faster                                                            |
| chameleon                | 9.84 ms                                                | 7.40 ms: 1.33x faster                                                            |
| pyflate                  | 708 ms                                                 | 535 ms: 1.32x faster                                                             |
| deepcopy_reduce          | 4.17 us                                                | 3.16 us: 1.32x faster                                                            |
| unpickle_pure_python     | 327 us                                                 | 248 us: 1.32x faster                                                             |
| tornado_http             | 131 ms                                                 | 99.9 ms: 1.31x faster                                                            |
| logging_format           | 9.07 us                                                | 6.96 us: 1.30x faster                                                            |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                                             |
| nbody                    | 148 ms                                                 | 114 ms: 1.30x faster                                                             |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.29x faster                                                           |
| go                       | 238 ms                                                 | 186 ms: 1.28x faster                                                             |
| sqlglot_optimize         | 68.7 ms                                                | 54.7 ms: 1.25x faster                                                            |
| pprint_pformat           | 2.10 sec                                               | 1.68 sec: 1.25x faster                                                           |
| mypy2                    | 442 ms                                                 | 355 ms: 1.25x faster                                                             |
| pprint_safe_repr         | 1.01 sec                                               | 822 ms: 1.23x faster                                                             |
| sympy_sum                | 190 ms                                                 | 154 ms: 1.23x faster                                                             |
| 2to3                     | 346 ms                                                 | 285 ms: 1.21x faster                                                             |
| docutils                 | 3.26 sec                                               | 2.70 sec: 1.21x faster                                                           |
| sympy_str                | 337 ms                                                 | 284 ms: 1.19x faster                                                             |
| sympy_integrate          | 25.4 ms                                                | 21.5 ms: 1.18x faster                                                            |
| dask                     | 432 ms                                                 | 367 ms: 1.18x faster                                                             |
| comprehensions           | 28.5 us                                                | 24.3 us: 1.17x faster                                                            |
| sympy_expand             | 558 ms                                                 | 480 ms: 1.16x faster                                                             |
| float                    | 116 ms                                                 | 101 ms: 1.15x faster                                                             |
| regex_compile            | 186 ms                                                 | 162 ms: 1.15x faster                                                             |
| xml_etree_generate       | 100.0 ms                                               | 87.7 ms: 1.14x faster                                                            |
| bench_thread_pool        | 966 us                                                 | 856 us: 1.13x faster                                                             |
| json_loads               | 31.4 us                                                | 28.2 us: 1.12x faster                                                            |
| dulwich_log              | 77.0 ms                                                | 69.2 ms: 1.11x faster                                                            |
| mako                     | 16.3 ms                                                | 14.7 ms: 1.11x faster                                                            |
| json                     | 5.67 ms                                                | 5.15 ms: 1.10x faster                                                            |
| pathlib                  | 20.3 ms                                                | 18.5 ms: 1.10x faster                                                            |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.09x faster                                                            |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                             |
| fannkuch                 | 527 ms                                                 | 492 ms: 1.07x faster                                                             |
| tomli_loads              | 3.06 sec                                               | 2.86 sec: 1.07x faster                                                           |
| scimark_fft              | 454 ms                                                 | 427 ms: 1.06x faster                                                             |
| mdp                      | 2.93 sec                                               | 2.76 sec: 1.06x faster                                                           |
| regex_v8                 | 26.2 ms                                                | 24.8 ms: 1.06x faster                                                            |
| hexiom                   | 10.3 ms                                                | 9.84 ms: 1.05x faster                                                            |
| sqlite_synth             | 3.02 us                                                | 2.91 us: 1.04x faster                                                            |
| xml_etree_iterparse      | 116 ms                                                 | 112 ms: 1.04x faster                                                             |
| nqueens                  | 107 ms                                                 | 103 ms: 1.03x faster                                                             |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                                             |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| meteor_contest           | 119 ms                                                 | 118 ms: 1.01x faster                                                             |
| unpickle_list            | 5.10 us                                                | 5.06 us: 1.01x faster                                                            |
| pickle_list              | 5.05 us                                                | 5.08 us: 1.01x slower                                                            |
| regex_dna                | 215 ms                                                 | 217 ms: 1.01x slower                                                             |
| async_generators         | 442 ms                                                 | 464 ms: 1.05x slower                                                             |
| regex_effbot             | 3.41 ms                                                | 3.62 ms: 1.06x slower                                                            |
| pickle                   | 10.7 us                                                | 11.7 us: 1.10x slower                                                            |
| gc_traversal             | 3.43 ms                                                | 3.82 ms: 1.11x slower                                                            |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.94 ms: 1.14x slower                                                            |
| coverage                 | 82.0 ms                                                | 96.8 ms: 1.18x slower                                                            |
| pickle_dict              | 30.0 us                                                | 36.3 us: 1.21x slower                                                            |
| telco                    | 7.01 ms                                                | 8.79 ms: 1.25x slower                                                            |
| python_startup_no_site   | 5.87 ms                                                | 9.08 ms: 1.55x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                                     |

Benchmark hidden because not significant (2): unpickle, bench_mp_pool
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231116-3.13.0a1+-58d77db-PYTHON_UOPS/bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
