
# Results vs. 3.10.4

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 01e464a
- commit date: 2023-11-04
- overall geometric mean: 1.22x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 292 ms: 1.18x faster                                                             |
| chameleon      | 9.84 ms                                                | 7.59 ms: 1.30x faster                                                            |
| docutils       | 3.26 sec                                               | 2.73 sec: 1.20x faster                                                           |
| tornado_http   | 131 ms                                                 | 99.7 ms: 1.31x faster                                                            |
| Geometric mean | (ref)                                                  | 1.25x faster                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 459 ms: 1.59x faster                                                             |
| async_tree_io           | 1.79 sec                                               | 1.21 sec: 1.48x faster                                                           |
| async_tree_memoization  | 867 ms                                                 | 588 ms: 1.47x faster                                                             |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 732 ms: 1.38x faster                                                             |
| Geometric mean          | (ref)                                                  | 1.48x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 122 ms: 1.21x faster                                                             |
| float          | 116 ms                                                 | 104 ms: 1.12x faster                                                             |
| pidigits       | 190 ms                                                 | 197 ms: 1.03x slower                                                             |
| Geometric mean | (ref)                                                  | 1.09x faster                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 164 ms: 1.13x faster                                                             |
| regex_v8       | 26.2 ms                                                | 25.8 ms: 1.02x faster                                                            |
| regex_dna      | 215 ms                                                 | 218 ms: 1.01x slower                                                             |
| regex_effbot   | 3.41 ms                                                | 3.72 ms: 1.09x slower                                                            |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 303 us: 1.59x faster                                                             |
| unpickle_pure_python | 327 us                                                 | 243 us: 1.35x faster                                                             |
| xml_etree_process    | 79.8 ms                                                | 59.5 ms: 1.34x faster                                                            |
| json_dumps           | 14.3 ms                                                | 10.7 ms: 1.34x faster                                                            |
| xml_etree_generate   | 100.0 ms                                               | 87.6 ms: 1.14x faster                                                            |
| json_loads           | 31.4 us                                                | 27.7 us: 1.13x faster                                                            |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.07x faster                                                             |
| xml_etree_iterparse  | 116 ms                                                 | 112 ms: 1.03x faster                                                             |
| tomli_loads          | 3.06 sec                                               | 2.99 sec: 1.02x faster                                                           |
| pickle_list          | 5.05 us                                                | 5.11 us: 1.01x slower                                                            |
| unpickle             | 14.9 us                                                | 15.5 us: 1.04x slower                                                            |
| unpickle_list        | 5.10 us                                                | 5.40 us: 1.06x slower                                                            |
| pickle               | 10.7 us                                                | 11.6 us: 1.09x slower                                                            |
| pickle_dict          | 30.0 us                                                | 35.6 us: 1.19x slower                                                            |
| Geometric mean       | (ref)                                                  | 1.10x faster                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                            |
| python_startup_no_site | 5.87 ms                                                | 9.00 ms: 1.53x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 15.3 ms: 1.07x faster                                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 124 us: 4.52x faster                                                             |
| generators               | 78.9 ms                                                | 30.0 ms: 2.63x faster                                                            |
| asyncio_tcp              | 918 ms                                                 | 495 ms: 1.85x faster                                                             |
| logging_silent           | 189 ns                                                 | 105 ns: 1.80x faster                                                             |
| scimark_sor              | 214 ms                                                 | 125 ms: 1.71x faster                                                             |
| richards_super           | 95.6 ms                                                | 57.8 ms: 1.65x faster                                                            |
| raytrace                 | 498 ms                                                 | 309 ms: 1.61x faster                                                             |
| async_tree_none          | 732 ms                                                 | 459 ms: 1.59x faster                                                             |
| pickle_pure_python       | 482 us                                                 | 303 us: 1.59x faster                                                             |
| sqlglot_parse            | 2.15 ms                                                | 1.36 ms: 1.58x faster                                                            |
| richards                 | 79.4 ms                                                | 50.7 ms: 1.57x faster                                                            |
| coroutines               | 34.5 ms                                                | 22.1 ms: 1.56x faster                                                            |
| chaos                    | 114 ms                                                 | 75.4 ms: 1.52x faster                                                            |
| sqlglot_transpile        | 2.55 ms                                                | 1.69 ms: 1.51x faster                                                            |
| spectral_norm            | 163 ms                                                 | 109 ms: 1.50x faster                                                             |
| deltablue                | 7.81 ms                                                | 5.25 ms: 1.49x faster                                                            |
| async_tree_io            | 1.79 sec                                               | 1.21 sec: 1.48x faster                                                           |
| scimark_monte_carlo      | 118 ms                                                 | 79.9 ms: 1.48x faster                                                            |
| async_tree_memoization   | 867 ms                                                 | 588 ms: 1.47x faster                                                             |
| scimark_lu               | 175 ms                                                 | 122 ms: 1.44x faster                                                             |
| crypto_pyaes             | 127 ms                                                 | 88.4 ms: 1.43x faster                                                            |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                                           |
| go                       | 238 ms                                                 | 170 ms: 1.40x faster                                                             |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                            |
| deepcopy_memo            | 58.8 us                                                | 42.6 us: 1.38x faster                                                            |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 732 ms: 1.38x faster                                                             |
| deepcopy                 | 481 us                                                 | 358 us: 1.35x faster                                                             |
| unpickle_pure_python     | 327 us                                                 | 243 us: 1.35x faster                                                             |
| xml_etree_process        | 79.8 ms                                                | 59.5 ms: 1.34x faster                                                            |
| json_dumps               | 14.3 ms                                                | 10.7 ms: 1.34x faster                                                            |
| deepcopy_reduce          | 4.17 us                                                | 3.15 us: 1.32x faster                                                            |
| sqlglot_normalize        | 141 ms                                                 | 107 ms: 1.32x faster                                                             |
| tornado_http             | 131 ms                                                 | 99.7 ms: 1.31x faster                                                            |
| logging_simple           | 8.27 us                                                | 6.32 us: 1.31x faster                                                            |
| chameleon                | 9.84 ms                                                | 7.59 ms: 1.30x faster                                                            |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.29x faster                                                           |
| logging_format           | 9.07 us                                                | 7.12 us: 1.28x faster                                                            |
| pprint_safe_repr         | 1.01 sec                                               | 807 ms: 1.26x faster                                                             |
| pprint_pformat           | 2.10 sec                                               | 1.67 sec: 1.26x faster                                                           |
| sqlglot_optimize         | 68.7 ms                                                | 55.1 ms: 1.25x faster                                                            |
| mypy2                    | 442 ms                                                 | 358 ms: 1.24x faster                                                             |
| pyflate                  | 708 ms                                                 | 579 ms: 1.22x faster                                                             |
| sympy_sum                | 190 ms                                                 | 157 ms: 1.21x faster                                                             |
| nbody                    | 148 ms                                                 | 122 ms: 1.21x faster                                                             |
| docutils                 | 3.26 sec                                               | 2.73 sec: 1.20x faster                                                           |
| 2to3                     | 346 ms                                                 | 292 ms: 1.18x faster                                                             |
| sympy_integrate          | 25.4 ms                                                | 21.6 ms: 1.18x faster                                                            |
| sympy_str                | 337 ms                                                 | 288 ms: 1.17x faster                                                             |
| sympy_expand             | 558 ms                                                 | 488 ms: 1.14x faster                                                             |
| xml_etree_generate       | 100.0 ms                                               | 87.6 ms: 1.14x faster                                                            |
| json_loads               | 31.4 us                                                | 27.7 us: 1.13x faster                                                            |
| regex_compile            | 186 ms                                                 | 164 ms: 1.13x faster                                                             |
| bench_thread_pool        | 966 us                                                 | 860 us: 1.12x faster                                                             |
| float                    | 116 ms                                                 | 104 ms: 1.12x faster                                                             |
| dulwich_log              | 77.0 ms                                                | 69.4 ms: 1.11x faster                                                            |
| create_gc_cycles         | 1.61 ms                                                | 1.45 ms: 1.11x faster                                                            |
| unpack_sequence          | 65.7 ns                                                | 59.4 ns: 1.11x faster                                                            |
| json                     | 5.67 ms                                                | 5.14 ms: 1.10x faster                                                            |
| comprehensions           | 28.5 us                                                | 26.2 us: 1.09x faster                                                            |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.07x faster                                                             |
| mako                     | 16.3 ms                                                | 15.3 ms: 1.07x faster                                                            |
| sqlite_synth             | 3.02 us                                                | 2.87 us: 1.05x faster                                                            |
| scimark_fft              | 454 ms                                                 | 437 ms: 1.04x faster                                                             |
| xml_etree_iterparse      | 116 ms                                                 | 112 ms: 1.03x faster                                                             |
| fannkuch                 | 527 ms                                                 | 510 ms: 1.03x faster                                                             |
| pathlib                  | 20.3 ms                                                | 19.7 ms: 1.03x faster                                                            |
| tomli_loads              | 3.06 sec                                               | 2.99 sec: 1.02x faster                                                           |
| regex_v8                 | 26.2 ms                                                | 25.8 ms: 1.02x faster                                                            |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                             |
| hexiom                   | 10.3 ms                                                | 10.3 ms: 1.00x faster                                                            |
| mdp                      | 2.93 sec                                               | 2.94 sec: 1.00x slower                                                           |
| meteor_contest           | 119 ms                                                 | 121 ms: 1.01x slower                                                             |
| pickle_list              | 5.05 us                                                | 5.11 us: 1.01x slower                                                            |
| regex_dna                | 215 ms                                                 | 218 ms: 1.01x slower                                                             |
| nqueens                  | 107 ms                                                 | 108 ms: 1.01x slower                                                             |
| pidigits                 | 190 ms                                                 | 197 ms: 1.03x slower                                                             |
| unpickle                 | 14.9 us                                                | 15.5 us: 1.04x slower                                                            |
| async_generators         | 442 ms                                                 | 467 ms: 1.06x slower                                                             |
| unpickle_list            | 5.10 us                                                | 5.40 us: 1.06x slower                                                            |
| pickle                   | 10.7 us                                                | 11.6 us: 1.09x slower                                                            |
| regex_effbot             | 3.41 ms                                                | 3.72 ms: 1.09x slower                                                            |
| gc_traversal             | 3.43 ms                                                | 3.80 ms: 1.11x slower                                                            |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.87 ms: 1.13x slower                                                            |
| coverage                 | 82.0 ms                                                | 96.0 ms: 1.17x slower                                                            |
| pickle_dict              | 30.0 us                                                | 35.6 us: 1.19x slower                                                            |
| telco                    | 7.01 ms                                                | 8.71 ms: 1.24x slower                                                            |
| python_startup_no_site   | 5.87 ms                                                | 9.00 ms: 1.53x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.22x faster                                                                     |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231104-3.13.0a1+-01e464a/bm-20231104-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-01e464a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.13x
