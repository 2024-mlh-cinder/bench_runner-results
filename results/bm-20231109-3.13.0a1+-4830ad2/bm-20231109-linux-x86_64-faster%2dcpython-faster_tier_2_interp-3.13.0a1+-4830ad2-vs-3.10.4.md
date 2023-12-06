
# Results vs. 3.10.4

- fork: faster-cpython
- ref: faster_tier_2_interp
- machine: linux-x86_64
- commit hash: 4830ad2
- commit date: 2023-11-09
- overall geometric mean: 1.24x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 287 ms: 1.20x faster                                                             |
| chameleon      | 9.84 ms                                                | 7.53 ms: 1.31x faster                                                            |
| docutils       | 3.26 sec                                               | 2.71 sec: 1.21x faster                                                           |
| tornado_http   | 131 ms                                                 | 99.3 ms: 1.32x faster                                                            |
| Geometric mean | (ref)                                                  | 1.26x faster                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 454 ms: 1.61x faster                                                             |
| async_tree_memoization  | 867 ms                                                 | 581 ms: 1.49x faster                                                             |
| async_tree_io           | 1.79 sec                                               | 1.20 sec: 1.49x faster                                                           |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 733 ms: 1.38x faster                                                             |
| Geometric mean          | (ref)                                                  | 1.49x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 127 ms: 1.16x faster                                                             |
| float          | 116 ms                                                 | 101 ms: 1.15x faster                                                             |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| Geometric mean | (ref)                                                  | 1.11x faster                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 158 ms: 1.17x faster                                                             |
| regex_v8       | 26.2 ms                                                | 24.2 ms: 1.09x faster                                                            |
| regex_dna      | 215 ms                                                 | 219 ms: 1.02x slower                                                             |
| regex_effbot   | 3.41 ms                                                | 3.59 ms: 1.05x slower                                                            |
| Geometric mean | (ref)                                                  | 1.04x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 310 us: 1.55x faster                                                             |
| unpickle_pure_python | 327 us                                                 | 242 us: 1.35x faster                                                             |
| xml_etree_process    | 79.8 ms                                                | 60.2 ms: 1.33x faster                                                            |
| json_dumps           | 14.3 ms                                                | 10.8 ms: 1.32x faster                                                            |
| tomli_loads          | 3.06 sec                                               | 2.66 sec: 1.15x faster                                                           |
| xml_etree_generate   | 100.0 ms                                               | 87.9 ms: 1.14x faster                                                            |
| json_loads           | 31.4 us                                                | 27.6 us: 1.14x faster                                                            |
| xml_etree_parse      | 171 ms                                                 | 157 ms: 1.09x faster                                                             |
| xml_etree_iterparse  | 116 ms                                                 | 110 ms: 1.05x faster                                                             |
| unpickle_list        | 5.10 us                                                | 5.34 us: 1.05x slower                                                            |
| pickle               | 10.7 us                                                | 11.7 us: 1.10x slower                                                            |
| pickle_dict          | 30.0 us                                                | 34.5 us: 1.15x slower                                                            |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                                     |

Benchmark hidden because not significant (2): pickle_list, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                            |
| python_startup_no_site | 5.87 ms                                                | 9.03 ms: 1.54x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 14.2 ms: 1.15x faster                                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 126 us: 4.45x faster                                                             |
| generators               | 78.9 ms                                                | 30.9 ms: 2.55x faster                                                            |
| asyncio_tcp              | 918 ms                                                 | 494 ms: 1.86x faster                                                             |
| logging_silent           | 189 ns                                                 | 109 ns: 1.74x faster                                                             |
| scimark_sor              | 214 ms                                                 | 128 ms: 1.68x faster                                                             |
| richards_super           | 95.6 ms                                                | 58.2 ms: 1.64x faster                                                            |
| raytrace                 | 498 ms                                                 | 304 ms: 1.64x faster                                                             |
| deltablue                | 7.81 ms                                                | 4.83 ms: 1.62x faster                                                            |
| async_tree_none          | 732 ms                                                 | 454 ms: 1.61x faster                                                             |
| sqlglot_parse            | 2.15 ms                                                | 1.35 ms: 1.59x faster                                                            |
| coroutines               | 34.5 ms                                                | 22.1 ms: 1.56x faster                                                            |
| pickle_pure_python       | 482 us                                                 | 310 us: 1.55x faster                                                             |
| chaos                    | 114 ms                                                 | 74.0 ms: 1.54x faster                                                            |
| richards                 | 79.4 ms                                                | 51.5 ms: 1.54x faster                                                            |
| sqlglot_transpile        | 2.55 ms                                                | 1.67 ms: 1.52x faster                                                            |
| async_tree_memoization   | 867 ms                                                 | 581 ms: 1.49x faster                                                             |
| async_tree_io            | 1.79 sec                                               | 1.20 sec: 1.49x faster                                                           |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.47x faster                                                             |
| scimark_monte_carlo      | 118 ms                                                 | 80.6 ms: 1.46x faster                                                            |
| go                       | 238 ms                                                 | 163 ms: 1.46x faster                                                             |
| unpack_sequence          | 65.7 ns                                                | 45.0 ns: 1.46x faster                                                            |
| crypto_pyaes             | 127 ms                                                 | 87.1 ms: 1.45x faster                                                            |
| spectral_norm            | 163 ms                                                 | 114 ms: 1.42x faster                                                             |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                                           |
| deepcopy_memo            | 58.8 us                                                | 42.3 us: 1.39x faster                                                            |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                            |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 733 ms: 1.38x faster                                                             |
| unpickle_pure_python     | 327 us                                                 | 242 us: 1.35x faster                                                             |
| deepcopy                 | 481 us                                                 | 360 us: 1.34x faster                                                             |
| xml_etree_process        | 79.8 ms                                                | 60.2 ms: 1.33x faster                                                            |
| json_dumps               | 14.3 ms                                                | 10.8 ms: 1.32x faster                                                            |
| logging_simple           | 8.27 us                                                | 6.28 us: 1.32x faster                                                            |
| tornado_http             | 131 ms                                                 | 99.3 ms: 1.32x faster                                                            |
| logging_format           | 9.07 us                                                | 6.94 us: 1.31x faster                                                            |
| chameleon                | 9.84 ms                                                | 7.53 ms: 1.31x faster                                                            |
| deepcopy_reduce          | 4.17 us                                                | 3.20 us: 1.30x faster                                                            |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                                             |
| pyflate                  | 708 ms                                                 | 549 ms: 1.29x faster                                                             |
| comprehensions           | 28.5 us                                                | 22.6 us: 1.26x faster                                                            |
| pycparser                | 1.57 sec                                               | 1.25 sec: 1.26x faster                                                           |
| sqlglot_optimize         | 68.7 ms                                                | 55.2 ms: 1.24x faster                                                            |
| mypy2                    | 442 ms                                                 | 356 ms: 1.24x faster                                                             |
| pprint_pformat           | 2.10 sec                                               | 1.70 sec: 1.23x faster                                                           |
| sympy_sum                | 190 ms                                                 | 155 ms: 1.23x faster                                                             |
| pprint_safe_repr         | 1.01 sec                                               | 826 ms: 1.23x faster                                                             |
| docutils                 | 3.26 sec                                               | 2.71 sec: 1.21x faster                                                           |
| 2to3                     | 346 ms                                                 | 287 ms: 1.20x faster                                                             |
| sympy_integrate          | 25.4 ms                                                | 21.2 ms: 1.20x faster                                                            |
| sympy_str                | 337 ms                                                 | 283 ms: 1.19x faster                                                             |
| regex_compile            | 186 ms                                                 | 158 ms: 1.17x faster                                                             |
| nbody                    | 148 ms                                                 | 127 ms: 1.16x faster                                                             |
| sympy_expand             | 558 ms                                                 | 480 ms: 1.16x faster                                                             |
| float                    | 116 ms                                                 | 101 ms: 1.15x faster                                                             |
| tomli_loads              | 3.06 sec                                               | 2.66 sec: 1.15x faster                                                           |
| mako                     | 16.3 ms                                                | 14.2 ms: 1.15x faster                                                            |
| xml_etree_generate       | 100.0 ms                                               | 87.9 ms: 1.14x faster                                                            |
| json_loads               | 31.4 us                                                | 27.6 us: 1.14x faster                                                            |
| bench_thread_pool        | 966 us                                                 | 859 us: 1.12x faster                                                             |
| hexiom                   | 10.3 ms                                                | 9.19 ms: 1.12x faster                                                            |
| dulwich_log              | 77.0 ms                                                | 68.8 ms: 1.12x faster                                                            |
| fannkuch                 | 527 ms                                                 | 477 ms: 1.11x faster                                                             |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                                            |
| xml_etree_parse          | 171 ms                                                 | 157 ms: 1.09x faster                                                             |
| regex_v8                 | 26.2 ms                                                | 24.2 ms: 1.09x faster                                                            |
| json                     | 5.67 ms                                                | 5.22 ms: 1.09x faster                                                            |
| xml_etree_iterparse      | 116 ms                                                 | 110 ms: 1.05x faster                                                             |
| nqueens                  | 107 ms                                                 | 102 ms: 1.05x faster                                                             |
| sqlite_synth             | 3.02 us                                                | 2.93 us: 1.03x faster                                                            |
| pathlib                  | 20.3 ms                                                | 19.7 ms: 1.03x faster                                                            |
| mdp                      | 2.93 sec                                               | 2.87 sec: 1.02x faster                                                           |
| meteor_contest           | 119 ms                                                 | 117 ms: 1.02x faster                                                             |
| scimark_fft              | 454 ms                                                 | 447 ms: 1.02x faster                                                             |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                             |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.03 ms: 1.01x faster                                                            |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                             |
| regex_dna                | 215 ms                                                 | 219 ms: 1.02x slower                                                             |
| async_generators         | 442 ms                                                 | 456 ms: 1.03x slower                                                             |
| unpickle_list            | 5.10 us                                                | 5.34 us: 1.05x slower                                                            |
| regex_effbot             | 3.41 ms                                                | 3.59 ms: 1.05x slower                                                            |
| gc_traversal             | 3.43 ms                                                | 3.77 ms: 1.10x slower                                                            |
| pickle                   | 10.7 us                                                | 11.7 us: 1.10x slower                                                            |
| coverage                 | 82.0 ms                                                | 93.7 ms: 1.14x slower                                                            |
| pickle_dict              | 30.0 us                                                | 34.5 us: 1.15x slower                                                            |
| telco                    | 7.01 ms                                                | 8.73 ms: 1.25x slower                                                            |
| python_startup_no_site   | 5.87 ms                                                | 9.03 ms: 1.54x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                                     |

Benchmark hidden because not significant (3): pickle_list, unpickle, bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231109-3.13.0a1+-4830ad2/bm-20231109-linux-x86_64-faster%2dcpython-faster_tier_2_interp-3.13.0a1+-4830ad2.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.16x
