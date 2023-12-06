
# Results vs. 3.10.4

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: bff925c
- commit date: 2023-11-05
- overall geometric mean: 1.25x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 283 ms: 1.22x faster                                                             |
| chameleon      | 9.84 ms                                                | 7.52 ms: 1.31x faster                                                            |
| docutils       | 3.26 sec                                               | 2.70 sec: 1.21x faster                                                           |
| tornado_http   | 131 ms                                                 | 99.2 ms: 1.32x faster                                                            |
| Geometric mean | (ref)                                                  | 1.26x faster                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 452 ms: 1.62x faster                                                             |
| async_tree_memoization  | 867 ms                                                 | 577 ms: 1.50x faster                                                             |
| async_tree_io           | 1.79 sec                                               | 1.20 sec: 1.49x faster                                                           |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 730 ms: 1.38x faster                                                             |
| Geometric mean          | (ref)                                                  | 1.50x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 126 ms: 1.18x faster                                                             |
| float          | 116 ms                                                 | 105 ms: 1.11x faster                                                             |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| Geometric mean | (ref)                                                  | 1.10x faster                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 158 ms: 1.17x faster                                                             |
| regex_v8       | 26.2 ms                                                | 25.9 ms: 1.01x faster                                                            |
| regex_effbot   | 3.41 ms                                                | 3.61 ms: 1.06x slower                                                            |
| Geometric mean | (ref)                                                  | 1.03x faster                                                                     |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 314 us: 1.54x faster                                                             |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                            |
| unpickle_pure_python | 327 us                                                 | 241 us: 1.36x faster                                                             |
| xml_etree_process    | 79.8 ms                                                | 59.2 ms: 1.35x faster                                                            |
| tomli_loads          | 3.06 sec                                               | 2.57 sec: 1.19x faster                                                           |
| xml_etree_generate   | 100.0 ms                                               | 86.4 ms: 1.16x faster                                                            |
| json_loads           | 31.4 us                                                | 27.8 us: 1.13x faster                                                            |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.09x faster                                                             |
| xml_etree_iterparse  | 116 ms                                                 | 111 ms: 1.05x faster                                                             |
| pickle_list          | 5.05 us                                                | 4.87 us: 1.04x faster                                                            |
| unpickle             | 14.9 us                                                | 14.7 us: 1.01x faster                                                            |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                                            |
| unpickle_list        | 5.10 us                                                | 5.53 us: 1.08x slower                                                            |
| pickle_dict          | 30.0 us                                                | 33.1 us: 1.11x slower                                                            |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                                     |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.40x faster                                                            |
| python_startup_no_site | 5.87 ms                                                | 8.96 ms: 1.53x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 14.4 ms: 1.13x faster                                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 124 us: 4.50x faster                                                             |
| generators               | 78.9 ms                                                | 29.6 ms: 2.67x faster                                                            |
| asyncio_tcp              | 918 ms                                                 | 490 ms: 1.87x faster                                                             |
| logging_silent           | 189 ns                                                 | 109 ns: 1.74x faster                                                             |
| richards_super           | 95.6 ms                                                | 56.3 ms: 1.70x faster                                                            |
| raytrace                 | 498 ms                                                 | 304 ms: 1.63x faster                                                             |
| sqlglot_parse            | 2.15 ms                                                | 1.31 ms: 1.63x faster                                                            |
| scimark_sor              | 214 ms                                                 | 132 ms: 1.62x faster                                                             |
| async_tree_none          | 732 ms                                                 | 452 ms: 1.62x faster                                                             |
| richards                 | 79.4 ms                                                | 49.6 ms: 1.60x faster                                                            |
| deltablue                | 7.81 ms                                                | 4.90 ms: 1.59x faster                                                            |
| sqlglot_transpile        | 2.55 ms                                                | 1.64 ms: 1.55x faster                                                            |
| coroutines               | 34.5 ms                                                | 22.2 ms: 1.55x faster                                                            |
| pickle_pure_python       | 482 us                                                 | 314 us: 1.54x faster                                                             |
| chaos                    | 114 ms                                                 | 74.8 ms: 1.53x faster                                                            |
| async_tree_memoization   | 867 ms                                                 | 577 ms: 1.50x faster                                                             |
| async_tree_io            | 1.79 sec                                               | 1.20 sec: 1.49x faster                                                           |
| scimark_monte_carlo      | 118 ms                                                 | 80.3 ms: 1.47x faster                                                            |
| crypto_pyaes             | 127 ms                                                 | 86.3 ms: 1.47x faster                                                            |
| spectral_norm            | 163 ms                                                 | 112 ms: 1.46x faster                                                             |
| scimark_lu               | 175 ms                                                 | 121 ms: 1.45x faster                                                             |
| go                       | 238 ms                                                 | 164 ms: 1.45x faster                                                             |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.43x faster                                                           |
| deepcopy_memo            | 58.8 us                                                | 42.0 us: 1.40x faster                                                            |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.40x faster                                                            |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 730 ms: 1.38x faster                                                             |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                            |
| deepcopy                 | 481 us                                                 | 355 us: 1.36x faster                                                             |
| unpickle_pure_python     | 327 us                                                 | 241 us: 1.36x faster                                                             |
| xml_etree_process        | 79.8 ms                                                | 59.2 ms: 1.35x faster                                                            |
| unpack_sequence          | 65.7 ns                                                | 49.0 ns: 1.34x faster                                                            |
| logging_simple           | 8.27 us                                                | 6.20 us: 1.33x faster                                                            |
| deepcopy_reduce          | 4.17 us                                                | 3.13 us: 1.33x faster                                                            |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.33x faster                                                             |
| tornado_http             | 131 ms                                                 | 99.2 ms: 1.32x faster                                                            |
| chameleon                | 9.84 ms                                                | 7.52 ms: 1.31x faster                                                            |
| pyflate                  | 708 ms                                                 | 543 ms: 1.30x faster                                                             |
| logging_format           | 9.07 us                                                | 6.97 us: 1.30x faster                                                            |
| pprint_pformat           | 2.10 sec                                               | 1.65 sec: 1.27x faster                                                           |
| pprint_safe_repr         | 1.01 sec                                               | 801 ms: 1.27x faster                                                             |
| sqlglot_optimize         | 68.7 ms                                                | 54.3 ms: 1.27x faster                                                            |
| pycparser                | 1.57 sec                                               | 1.24 sec: 1.26x faster                                                           |
| mypy2                    | 442 ms                                                 | 354 ms: 1.25x faster                                                             |
| sympy_sum                | 190 ms                                                 | 153 ms: 1.24x faster                                                             |
| comprehensions           | 28.5 us                                                | 23.3 us: 1.22x faster                                                            |
| 2to3                     | 346 ms                                                 | 283 ms: 1.22x faster                                                             |
| docutils                 | 3.26 sec                                               | 2.70 sec: 1.21x faster                                                           |
| sympy_integrate          | 25.4 ms                                                | 21.1 ms: 1.20x faster                                                            |
| sympy_str                | 337 ms                                                 | 282 ms: 1.19x faster                                                             |
| tomli_loads              | 3.06 sec                                               | 2.57 sec: 1.19x faster                                                           |
| nbody                    | 148 ms                                                 | 126 ms: 1.18x faster                                                             |
| regex_compile            | 186 ms                                                 | 158 ms: 1.17x faster                                                             |
| sympy_expand             | 558 ms                                                 | 479 ms: 1.16x faster                                                             |
| xml_etree_generate       | 100.0 ms                                               | 86.4 ms: 1.16x faster                                                            |
| mako                     | 16.3 ms                                                | 14.4 ms: 1.13x faster                                                            |
| bench_thread_pool        | 966 us                                                 | 854 us: 1.13x faster                                                             |
| json_loads               | 31.4 us                                                | 27.8 us: 1.13x faster                                                            |
| fannkuch                 | 527 ms                                                 | 468 ms: 1.13x faster                                                             |
| hexiom                   | 10.3 ms                                                | 9.19 ms: 1.12x faster                                                            |
| dulwich_log              | 77.0 ms                                                | 69.0 ms: 1.12x faster                                                            |
| float                    | 116 ms                                                 | 105 ms: 1.11x faster                                                             |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                                            |
| json                     | 5.67 ms                                                | 5.19 ms: 1.09x faster                                                            |
| nqueens                  | 107 ms                                                 | 97.9 ms: 1.09x faster                                                            |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.09x faster                                                             |
| sqlite_synth             | 3.02 us                                                | 2.83 us: 1.07x faster                                                            |
| mdp                      | 2.93 sec                                               | 2.79 sec: 1.05x faster                                                           |
| xml_etree_iterparse      | 116 ms                                                 | 111 ms: 1.05x faster                                                             |
| pickle_list              | 5.05 us                                                | 4.87 us: 1.04x faster                                                            |
| pathlib                  | 20.3 ms                                                | 19.7 ms: 1.03x faster                                                            |
| scimark_fft              | 454 ms                                                 | 442 ms: 1.03x faster                                                             |
| meteor_contest           | 119 ms                                                 | 116 ms: 1.02x faster                                                             |
| regex_v8                 | 26.2 ms                                                | 25.9 ms: 1.01x faster                                                            |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                                             |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| unpickle                 | 14.9 us                                                | 14.7 us: 1.01x faster                                                            |
| async_generators         | 442 ms                                                 | 454 ms: 1.03x slower                                                             |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.31 ms: 1.03x slower                                                            |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                                            |
| regex_effbot             | 3.41 ms                                                | 3.61 ms: 1.06x slower                                                            |
| gc_traversal             | 3.43 ms                                                | 3.64 ms: 1.06x slower                                                            |
| unpickle_list            | 5.10 us                                                | 5.53 us: 1.08x slower                                                            |
| pickle_dict              | 30.0 us                                                | 33.1 us: 1.11x slower                                                            |
| coverage                 | 82.0 ms                                                | 94.7 ms: 1.15x slower                                                            |
| telco                    | 7.01 ms                                                | 8.73 ms: 1.24x slower                                                            |
| python_startup_no_site   | 5.87 ms                                                | 8.96 ms: 1.53x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.25x faster                                                                     |

Benchmark hidden because not significant (2): bench_mp_pool, regex_dna
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231105-3.13.0a1+-bff925c/bm-20231105-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bff925c.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.17x
