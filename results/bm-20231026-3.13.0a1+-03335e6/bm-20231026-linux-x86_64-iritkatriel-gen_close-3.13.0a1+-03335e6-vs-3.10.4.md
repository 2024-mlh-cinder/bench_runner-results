
# Results vs. 3.10.4

- fork: iritkatriel
- ref: gen_close
- machine: linux-x86_64
- commit hash: 03335e6
- commit date: 2023-10-26
- overall geometric mean: 1.33x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                             |
| chameleon      | 9.84 ms                                                | 6.97 ms: 1.41x faster                                            |
| docutils       | 3.26 sec                                               | 2.65 sec: 1.23x faster                                           |
| tornado_http   | 131 ms                                                 | 95.7 ms: 1.36x faster                                            |
| Geometric mean | (ref)                                                  | 1.33x faster                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 437 ms: 1.68x faster                                             |
| async_tree_memoization  | 867 ms                                                 | 563 ms: 1.54x faster                                             |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.51x faster                                           |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 712 ms: 1.42x faster                                             |
| Geometric mean          | (ref)                                                  | 1.53x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 91.3 ms: 1.62x faster                                            |
| float          | 116 ms                                                 | 81.4 ms: 1.43x faster                                            |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                             |
| Geometric mean | (ref)                                                  | 1.33x faster                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 138 ms: 1.35x faster                                             |
| regex_v8       | 26.2 ms                                                | 25.5 ms: 1.03x faster                                            |
| regex_dna      | 215 ms                                                 | 212 ms: 1.01x faster                                             |
| regex_effbot   | 3.41 ms                                                | 3.65 ms: 1.07x slower                                            |
| Geometric mean | (ref)                                                  | 1.07x faster                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 300 us: 1.60x faster                                             |
| unpickle_pure_python | 327 us                                                 | 220 us: 1.48x faster                                             |
| tomli_loads          | 3.06 sec                                               | 2.14 sec: 1.43x faster                                           |
| json_dumps           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                            |
| xml_etree_process    | 79.8 ms                                                | 58.8 ms: 1.36x faster                                            |
| xml_etree_generate   | 100.0 ms                                               | 86.1 ms: 1.16x faster                                            |
| json_loads           | 31.4 us                                                | 28.0 us: 1.12x faster                                            |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.10x faster                                             |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                             |
| pickle_list          | 5.05 us                                                | 4.95 us: 1.02x faster                                            |
| pickle               | 10.7 us                                                | 11.1 us: 1.04x slower                                            |
| pickle_dict          | 30.0 us                                                | 32.8 us: 1.09x slower                                            |
| Geometric mean       | (ref)                                                  | 1.17x faster                                                     |

Benchmark hidden because not significant (2): unpickle, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.40x faster                                            |
| python_startup_no_site | 5.87 ms                                                | 8.94 ms: 1.52x slower                                            |
| Geometric mean         | (ref)                                                  | 1.04x slower                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.5 ms: 1.42x faster                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 152 us: 3.70x faster                                             |
| generators               | 78.9 ms                                                | 29.6 ms: 2.66x faster                                            |
| deltablue                | 7.81 ms                                                | 3.38 ms: 2.31x faster                                            |
| asyncio_tcp              | 918 ms                                                 | 479 ms: 1.91x faster                                             |
| chaos                    | 114 ms                                                 | 61.4 ms: 1.86x faster                                            |
| logging_silent           | 189 ns                                                 | 105 ns: 1.81x faster                                             |
| raytrace                 | 498 ms                                                 | 276 ms: 1.80x faster                                             |
| crypto_pyaes             | 127 ms                                                 | 71.5 ms: 1.77x faster                                            |
| richards_super           | 95.6 ms                                                | 55.0 ms: 1.74x faster                                            |
| scimark_sor              | 214 ms                                                 | 125 ms: 1.71x faster                                             |
| scimark_monte_carlo      | 118 ms                                                 | 69.1 ms: 1.71x faster                                            |
| comprehensions           | 28.5 us                                                | 16.7 us: 1.71x faster                                            |
| async_tree_none          | 732 ms                                                 | 437 ms: 1.68x faster                                             |
| hexiom                   | 10.3 ms                                                | 6.20 ms: 1.66x faster                                            |
| go                       | 238 ms                                                 | 145 ms: 1.64x faster                                             |
| sqlglot_parse            | 2.15 ms                                                | 1.31 ms: 1.64x faster                                            |
| richards                 | 79.4 ms                                                | 48.8 ms: 1.63x faster                                            |
| nbody                    | 148 ms                                                 | 91.3 ms: 1.62x faster                                            |
| pickle_pure_python       | 482 us                                                 | 300 us: 1.60x faster                                             |
| sqlglot_transpile        | 2.55 ms                                                | 1.62 ms: 1.58x faster                                            |
| async_tree_memoization   | 867 ms                                                 | 563 ms: 1.54x faster                                             |
| coroutines               | 34.5 ms                                                | 22.5 ms: 1.53x faster                                            |
| deepcopy_memo            | 58.8 us                                                | 38.5 us: 1.53x faster                                            |
| scimark_lu               | 175 ms                                                 | 116 ms: 1.52x faster                                             |
| pyflate                  | 708 ms                                                 | 470 ms: 1.51x faster                                             |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.51x faster                                           |
| unpickle_pure_python     | 327 us                                                 | 220 us: 1.48x faster                                             |
| spectral_norm            | 163 ms                                                 | 110 ms: 1.48x faster                                             |
| unpack_sequence          | 65.7 ns                                                | 44.7 ns: 1.47x faster                                            |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.78 sec: 1.45x faster                                           |
| float                    | 116 ms                                                 | 81.4 ms: 1.43x faster                                            |
| tomli_loads              | 3.06 sec                                               | 2.14 sec: 1.43x faster                                           |
| mako                     | 16.3 ms                                                | 11.5 ms: 1.42x faster                                            |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 712 ms: 1.42x faster                                             |
| chameleon                | 9.84 ms                                                | 6.97 ms: 1.41x faster                                            |
| logging_format           | 9.07 us                                                | 6.43 us: 1.41x faster                                            |
| logging_simple           | 8.27 us                                                | 5.91 us: 1.40x faster                                            |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.40x faster                                            |
| pprint_pformat           | 2.10 sec                                               | 1.50 sec: 1.39x faster                                           |
| pprint_safe_repr         | 1.01 sec                                               | 737 ms: 1.38x faster                                             |
| deepcopy                 | 481 us                                                 | 350 us: 1.37x faster                                             |
| json_dumps               | 14.3 ms                                                | 10.4 ms: 1.37x faster                                            |
| tornado_http             | 131 ms                                                 | 95.7 ms: 1.36x faster                                            |
| xml_etree_process        | 79.8 ms                                                | 58.8 ms: 1.36x faster                                            |
| pycparser                | 1.57 sec                                               | 1.16 sec: 1.35x faster                                           |
| sqlglot_normalize        | 141 ms                                                 | 105 ms: 1.35x faster                                             |
| regex_compile            | 186 ms                                                 | 138 ms: 1.35x faster                                             |
| deepcopy_reduce          | 4.17 us                                                | 3.13 us: 1.33x faster                                            |
| nqueens                  | 107 ms                                                 | 80.4 ms: 1.33x faster                                            |
| fannkuch                 | 527 ms                                                 | 401 ms: 1.32x faster                                             |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                             |
| sympy_integrate          | 25.4 ms                                                | 19.7 ms: 1.29x faster                                            |
| sqlglot_optimize         | 68.7 ms                                                | 53.2 ms: 1.29x faster                                            |
| sympy_sum                | 190 ms                                                 | 148 ms: 1.29x faster                                             |
| mypy2                    | 442 ms                                                 | 343 ms: 1.29x faster                                             |
| sympy_str                | 337 ms                                                 | 266 ms: 1.26x faster                                             |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.90 ms: 1.25x faster                                            |
| sympy_expand             | 558 ms                                                 | 452 ms: 1.23x faster                                             |
| docutils                 | 3.26 sec                                               | 2.65 sec: 1.23x faster                                           |
| scimark_fft              | 454 ms                                                 | 377 ms: 1.21x faster                                             |
| bench_thread_pool        | 966 us                                                 | 815 us: 1.19x faster                                             |
| xml_etree_generate       | 100.0 ms                                               | 86.1 ms: 1.16x faster                                            |
| dulwich_log              | 77.0 ms                                                | 66.4 ms: 1.16x faster                                            |
| mdp                      | 2.93 sec                                               | 2.54 sec: 1.16x faster                                           |
| json_loads               | 31.4 us                                                | 28.0 us: 1.12x faster                                            |
| meteor_contest           | 119 ms                                                 | 107 ms: 1.11x faster                                             |
| create_gc_cycles         | 1.61 ms                                                | 1.45 ms: 1.11x faster                                            |
| xml_etree_iterparse      | 116 ms                                                 | 105 ms: 1.10x faster                                             |
| json                     | 5.67 ms                                                | 5.17 ms: 1.10x faster                                            |
| sqlite_synth             | 3.02 us                                                | 2.78 us: 1.09x faster                                            |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                             |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                            |
| regex_v8                 | 26.2 ms                                                | 25.5 ms: 1.03x faster                                            |
| pickle_list              | 5.05 us                                                | 4.95 us: 1.02x faster                                            |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                             |
| regex_dna                | 215 ms                                                 | 212 ms: 1.01x faster                                             |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                             |
| async_generators         | 442 ms                                                 | 458 ms: 1.04x slower                                             |
| pickle                   | 10.7 us                                                | 11.1 us: 1.04x slower                                            |
| regex_effbot             | 3.41 ms                                                | 3.65 ms: 1.07x slower                                            |
| pickle_dict              | 30.0 us                                                | 32.8 us: 1.09x slower                                            |
| coverage                 | 82.0 ms                                                | 94.3 ms: 1.15x slower                                            |
| telco                    | 7.01 ms                                                | 8.32 ms: 1.19x slower                                            |
| gc_traversal             | 3.43 ms                                                | 4.08 ms: 1.19x slower                                            |
| python_startup_no_site   | 5.87 ms                                                | 8.94 ms: 1.52x slower                                            |
| Geometric mean           | (ref)                                                  | 1.33x faster                                                     |

Benchmark hidden because not significant (3): unpickle, unpickle_list, bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231026-3.13.0a1+-03335e6/bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1+-03335e6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.30x
- 95% likely to have a speedup of 1.29x
- 99% likely to have a speedup of 1.26x
