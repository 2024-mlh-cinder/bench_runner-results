
# Results vs. 3.10.4

- fork: gvanrossum
- ref: mix_tiers
- machine: linux-x86_64
- commit hash: d805312
- commit date: 2023-10-28
- overall geometric mean: 1.32x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 267 ms: 1.29x faster                                            |
| chameleon      | 9.84 ms                                                | 7.00 ms: 1.41x faster                                           |
| docutils       | 3.26 sec                                               | 2.66 sec: 1.23x faster                                          |
| tornado_http   | 131 ms                                                 | 95.8 ms: 1.36x faster                                           |
| Geometric mean | (ref)                                                  | 1.32x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 439 ms: 1.67x faster                                            |
| async_tree_memoization  | 867 ms                                                 | 565 ms: 1.53x faster                                            |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.51x faster                                          |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 710 ms: 1.42x faster                                            |
| Geometric mean          | (ref)                                                  | 1.53x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 92.8 ms: 1.60x faster                                           |
| float          | 116 ms                                                 | 82.0 ms: 1.42x faster                                           |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                            |
| Geometric mean | (ref)                                                  | 1.30x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 139 ms: 1.34x faster                                            |
| regex_v8       | 26.2 ms                                                | 25.4 ms: 1.03x faster                                           |
| regex_dna      | 215 ms                                                 | 217 ms: 1.01x slower                                            |
| regex_effbot   | 3.41 ms                                                | 3.76 ms: 1.10x slower                                           |
| Geometric mean | (ref)                                                  | 1.06x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 305 us: 1.58x faster                                            |
| unpickle_pure_python | 327 us                                                 | 221 us: 1.47x faster                                            |
| tomli_loads          | 3.06 sec                                               | 2.15 sec: 1.42x faster                                          |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                           |
| xml_etree_process    | 79.8 ms                                                | 59.6 ms: 1.34x faster                                           |
| xml_etree_generate   | 100.0 ms                                               | 86.7 ms: 1.15x faster                                           |
| json_loads           | 31.4 us                                                | 27.7 us: 1.13x faster                                           |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.09x faster                                            |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                            |
| unpickle             | 14.9 us                                                | 14.5 us: 1.02x faster                                           |
| pickle_list          | 5.05 us                                                | 4.99 us: 1.01x faster                                           |
| pickle               | 10.7 us                                                | 11.3 us: 1.06x slower                                           |
| pickle_dict          | 30.0 us                                                | 33.4 us: 1.12x slower                                           |
| Geometric mean       | (ref)                                                  | 1.16x faster                                                    |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                           |
| python_startup_no_site | 5.87 ms                                                | 8.96 ms: 1.53x slower                                           |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.4 ms: 1.43x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 156 us: 3.60x faster                                            |
| generators               | 78.9 ms                                                | 29.7 ms: 2.66x faster                                           |
| deltablue                | 7.81 ms                                                | 3.36 ms: 2.33x faster                                           |
| asyncio_tcp              | 918 ms                                                 | 477 ms: 1.92x faster                                            |
| chaos                    | 114 ms                                                 | 61.9 ms: 1.85x faster                                           |
| raytrace                 | 498 ms                                                 | 275 ms: 1.81x faster                                            |
| logging_silent           | 189 ns                                                 | 107 ns: 1.77x faster                                            |
| richards_super           | 95.6 ms                                                | 55.2 ms: 1.73x faster                                           |
| crypto_pyaes             | 127 ms                                                 | 73.3 ms: 1.73x faster                                           |
| scimark_monte_carlo      | 118 ms                                                 | 68.9 ms: 1.71x faster                                           |
| comprehensions           | 28.5 us                                                | 16.8 us: 1.70x faster                                           |
| sqlglot_parse            | 2.15 ms                                                | 1.28 ms: 1.68x faster                                           |
| async_tree_none          | 732 ms                                                 | 439 ms: 1.67x faster                                            |
| go                       | 238 ms                                                 | 145 ms: 1.64x faster                                            |
| hexiom                   | 10.3 ms                                                | 6.28 ms: 1.64x faster                                           |
| richards                 | 79.4 ms                                                | 49.4 ms: 1.61x faster                                           |
| scimark_sor              | 214 ms                                                 | 134 ms: 1.60x faster                                            |
| nbody                    | 148 ms                                                 | 92.8 ms: 1.60x faster                                           |
| sqlglot_transpile        | 2.55 ms                                                | 1.60 ms: 1.59x faster                                           |
| pickle_pure_python       | 482 us                                                 | 305 us: 1.58x faster                                            |
| unpack_sequence          | 65.7 ns                                                | 42.6 ns: 1.54x faster                                           |
| async_tree_memoization   | 867 ms                                                 | 565 ms: 1.53x faster                                            |
| coroutines               | 34.5 ms                                                | 22.5 ms: 1.53x faster                                           |
| scimark_lu               | 175 ms                                                 | 116 ms: 1.51x faster                                            |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.51x faster                                          |
| pyflate                  | 708 ms                                                 | 480 ms: 1.48x faster                                            |
| deepcopy_memo            | 58.8 us                                                | 39.8 us: 1.48x faster                                           |
| unpickle_pure_python     | 327 us                                                 | 221 us: 1.47x faster                                            |
| spectral_norm            | 163 ms                                                 | 113 ms: 1.45x faster                                            |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.78 sec: 1.44x faster                                          |
| mako                     | 16.3 ms                                                | 11.4 ms: 1.43x faster                                           |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 710 ms: 1.42x faster                                            |
| tomli_loads              | 3.06 sec                                               | 2.15 sec: 1.42x faster                                          |
| float                    | 116 ms                                                 | 82.0 ms: 1.42x faster                                           |
| chameleon                | 9.84 ms                                                | 7.00 ms: 1.41x faster                                           |
| logging_format           | 9.07 us                                                | 6.52 us: 1.39x faster                                           |
| logging_simple           | 8.27 us                                                | 5.95 us: 1.39x faster                                           |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                           |
| tornado_http             | 131 ms                                                 | 95.8 ms: 1.36x faster                                           |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                           |
| pprint_pformat           | 2.10 sec                                               | 1.54 sec: 1.36x faster                                          |
| deepcopy                 | 481 us                                                 | 357 us: 1.35x faster                                            |
| pprint_safe_repr         | 1.01 sec                                               | 757 ms: 1.34x faster                                            |
| regex_compile            | 186 ms                                                 | 139 ms: 1.34x faster                                            |
| xml_etree_process        | 79.8 ms                                                | 59.6 ms: 1.34x faster                                           |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.34x faster                                            |
| pycparser                | 1.57 sec                                               | 1.17 sec: 1.34x faster                                          |
| nqueens                  | 107 ms                                                 | 81.3 ms: 1.31x faster                                           |
| deepcopy_reduce          | 4.17 us                                                | 3.18 us: 1.31x faster                                           |
| mypy2                    | 442 ms                                                 | 341 ms: 1.30x faster                                            |
| fannkuch                 | 527 ms                                                 | 407 ms: 1.30x faster                                            |
| 2to3                     | 346 ms                                                 | 267 ms: 1.29x faster                                            |
| sqlglot_optimize         | 68.7 ms                                                | 53.5 ms: 1.28x faster                                           |
| sympy_sum                | 190 ms                                                 | 148 ms: 1.28x faster                                            |
| sympy_integrate          | 25.4 ms                                                | 19.9 ms: 1.28x faster                                           |
| sympy_str                | 337 ms                                                 | 267 ms: 1.26x faster                                            |
| sympy_expand             | 558 ms                                                 | 453 ms: 1.23x faster                                            |
| docutils                 | 3.26 sec                                               | 2.66 sec: 1.23x faster                                          |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.03 ms: 1.21x faster                                           |
| scimark_fft              | 454 ms                                                 | 377 ms: 1.20x faster                                            |
| bench_thread_pool        | 966 us                                                 | 815 us: 1.19x faster                                            |
| mdp                      | 2.93 sec                                               | 2.53 sec: 1.16x faster                                          |
| dulwich_log              | 77.0 ms                                                | 66.7 ms: 1.15x faster                                           |
| xml_etree_generate       | 100.0 ms                                               | 86.7 ms: 1.15x faster                                           |
| json_loads               | 31.4 us                                                | 27.7 us: 1.13x faster                                           |
| json                     | 5.67 ms                                                | 5.12 ms: 1.11x faster                                           |
| meteor_contest           | 119 ms                                                 | 109 ms: 1.09x faster                                            |
| xml_etree_iterparse      | 116 ms                                                 | 106 ms: 1.09x faster                                            |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.09x faster                                           |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                            |
| pathlib                  | 20.3 ms                                                | 19.0 ms: 1.07x faster                                           |
| sqlite_synth             | 3.02 us                                                | 2.84 us: 1.06x faster                                           |
| regex_v8                 | 26.2 ms                                                | 25.4 ms: 1.03x faster                                           |
| unpickle                 | 14.9 us                                                | 14.5 us: 1.02x faster                                           |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                            |
| pickle_list              | 5.05 us                                                | 4.99 us: 1.01x faster                                           |
| regex_dna                | 215 ms                                                 | 217 ms: 1.01x slower                                            |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                            |
| async_generators         | 442 ms                                                 | 460 ms: 1.04x slower                                            |
| pickle                   | 10.7 us                                                | 11.3 us: 1.06x slower                                           |
| regex_effbot             | 3.41 ms                                                | 3.76 ms: 1.10x slower                                           |
| pickle_dict              | 30.0 us                                                | 33.4 us: 1.12x slower                                           |
| gc_traversal             | 3.43 ms                                                | 3.94 ms: 1.15x slower                                           |
| coverage                 | 82.0 ms                                                | 94.9 ms: 1.16x slower                                           |
| telco                    | 7.01 ms                                                | 8.40 ms: 1.20x slower                                           |
| python_startup_no_site   | 5.87 ms                                                | 8.96 ms: 1.53x slower                                           |
| Geometric mean           | (ref)                                                  | 1.32x faster                                                    |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle_list
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231028-3.13.0a1+-d805312/bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-d805312.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.26x
