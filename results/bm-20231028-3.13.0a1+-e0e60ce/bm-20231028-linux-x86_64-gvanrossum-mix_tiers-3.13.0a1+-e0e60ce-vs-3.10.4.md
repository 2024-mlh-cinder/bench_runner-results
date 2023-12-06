
# Results vs. 3.10.4

- fork: gvanrossum
- ref: mix_tiers
- machine: linux-x86_64
- commit hash: e0e60ce
- commit date: 2023-10-28
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 290 ms: 1.19x faster                                            |
| chameleon      | 9.84 ms                                                | 7.56 ms: 1.30x faster                                           |
| docutils       | 3.26 sec                                               | 2.76 sec: 1.18x faster                                          |
| tornado_http   | 131 ms                                                 | 102 ms: 1.28x faster                                            |
| Geometric mean | (ref)                                                  | 1.24x faster                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 448 ms: 1.63x faster                                            |
| async_tree_memoization  | 867 ms                                                 | 577 ms: 1.50x faster                                            |
| async_tree_io           | 1.79 sec                                               | 1.20 sec: 1.48x faster                                          |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 718 ms: 1.40x faster                                            |
| Geometric mean          | (ref)                                                  | 1.50x faster                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 118 ms: 1.26x faster                                            |
| float          | 116 ms                                                 | 95.1 ms: 1.22x faster                                           |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                            |
| Geometric mean | (ref)                                                  | 1.16x faster                                                    |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 165 ms: 1.13x faster                                            |
| regex_v8       | 26.2 ms                                                | 24.6 ms: 1.07x faster                                           |
| regex_dna      | 215 ms                                                 | 222 ms: 1.03x slower                                            |
| regex_effbot   | 3.41 ms                                                | 3.58 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                  | 1.03x faster                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 311 us: 1.55x faster                                            |
| unpickle_pure_python | 327 us                                                 | 239 us: 1.36x faster                                            |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                           |
| xml_etree_process    | 79.8 ms                                                | 60.2 ms: 1.33x faster                                           |
| tomli_loads          | 3.06 sec                                               | 2.48 sec: 1.23x faster                                          |
| json_loads           | 31.4 us                                                | 27.7 us: 1.13x faster                                           |
| xml_etree_generate   | 100.0 ms                                               | 88.3 ms: 1.13x faster                                           |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                            |
| xml_etree_iterparse  | 116 ms                                                 | 111 ms: 1.05x faster                                            |
| pickle_list          | 5.05 us                                                | 4.87 us: 1.04x faster                                           |
| unpickle             | 14.9 us                                                | 15.0 us: 1.01x slower                                           |
| pickle               | 10.7 us                                                | 11.0 us: 1.03x slower                                           |
| unpickle_list        | 5.10 us                                                | 5.34 us: 1.05x slower                                           |
| pickle_dict          | 30.0 us                                                | 32.6 us: 1.09x slower                                           |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                           |
| python_startup_no_site | 5.87 ms                                                | 9.01 ms: 1.53x slower                                           |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 13.8 ms: 1.18x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 161 us: 3.48x faster                                            |
| generators               | 78.9 ms                                                | 32.8 ms: 2.41x faster                                           |
| asyncio_tcp              | 918 ms                                                 | 482 ms: 1.90x faster                                            |
| logging_silent           | 189 ns                                                 | 110 ns: 1.72x faster                                            |
| richards_super           | 95.6 ms                                                | 57.5 ms: 1.66x faster                                           |
| scimark_sor              | 214 ms                                                 | 129 ms: 1.66x faster                                            |
| deltablue                | 7.81 ms                                                | 4.73 ms: 1.65x faster                                           |
| async_tree_none          | 732 ms                                                 | 448 ms: 1.63x faster                                            |
| sqlglot_parse            | 2.15 ms                                                | 1.34 ms: 1.60x faster                                           |
| raytrace                 | 498 ms                                                 | 313 ms: 1.59x faster                                            |
| richards                 | 79.4 ms                                                | 50.6 ms: 1.57x faster                                           |
| pickle_pure_python       | 482 us                                                 | 311 us: 1.55x faster                                            |
| scimark_monte_carlo      | 118 ms                                                 | 76.2 ms: 1.55x faster                                           |
| sqlglot_transpile        | 2.55 ms                                                | 1.67 ms: 1.53x faster                                           |
| chaos                    | 114 ms                                                 | 75.7 ms: 1.51x faster                                           |
| async_tree_memoization   | 867 ms                                                 | 577 ms: 1.50x faster                                            |
| coroutines               | 34.5 ms                                                | 23.0 ms: 1.50x faster                                           |
| crypto_pyaes             | 127 ms                                                 | 84.9 ms: 1.49x faster                                           |
| async_tree_io            | 1.79 sec                                               | 1.20 sec: 1.48x faster                                          |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.46x faster                                            |
| go                       | 238 ms                                                 | 165 ms: 1.44x faster                                            |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                          |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 718 ms: 1.40x faster                                            |
| spectral_norm            | 163 ms                                                 | 117 ms: 1.40x faster                                            |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                           |
| deepcopy_memo            | 58.8 us                                                | 42.6 us: 1.38x faster                                           |
| unpickle_pure_python     | 327 us                                                 | 239 us: 1.36x faster                                            |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                           |
| pyflate                  | 708 ms                                                 | 520 ms: 1.36x faster                                            |
| xml_etree_process        | 79.8 ms                                                | 60.2 ms: 1.33x faster                                           |
| deepcopy                 | 481 us                                                 | 363 us: 1.33x faster                                            |
| unpack_sequence          | 65.7 ns                                                | 49.6 ns: 1.32x faster                                           |
| deepcopy_reduce          | 4.17 us                                                | 3.17 us: 1.31x faster                                           |
| sqlglot_normalize        | 141 ms                                                 | 108 ms: 1.30x faster                                            |
| chameleon                | 9.84 ms                                                | 7.56 ms: 1.30x faster                                           |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.30x faster                                          |
| comprehensions           | 28.5 us                                                | 22.1 us: 1.29x faster                                           |
| logging_simple           | 8.27 us                                                | 6.44 us: 1.29x faster                                           |
| tornado_http             | 131 ms                                                 | 102 ms: 1.28x faster                                            |
| nbody                    | 148 ms                                                 | 118 ms: 1.26x faster                                            |
| logging_format           | 9.07 us                                                | 7.25 us: 1.25x faster                                           |
| sqlglot_optimize         | 68.7 ms                                                | 55.3 ms: 1.24x faster                                           |
| pprint_pformat           | 2.10 sec                                               | 1.69 sec: 1.24x faster                                          |
| pprint_safe_repr         | 1.01 sec                                               | 820 ms: 1.24x faster                                            |
| mypy2                    | 442 ms                                                 | 358 ms: 1.24x faster                                            |
| tomli_loads              | 3.06 sec                                               | 2.48 sec: 1.23x faster                                          |
| float                    | 116 ms                                                 | 95.1 ms: 1.22x faster                                           |
| sympy_sum                | 190 ms                                                 | 157 ms: 1.21x faster                                            |
| 2to3                     | 346 ms                                                 | 290 ms: 1.19x faster                                            |
| docutils                 | 3.26 sec                                               | 2.76 sec: 1.18x faster                                          |
| mako                     | 16.3 ms                                                | 13.8 ms: 1.18x faster                                           |
| sympy_integrate          | 25.4 ms                                                | 21.6 ms: 1.17x faster                                           |
| sympy_str                | 337 ms                                                 | 289 ms: 1.16x faster                                            |
| fannkuch                 | 527 ms                                                 | 453 ms: 1.16x faster                                            |
| hexiom                   | 10.3 ms                                                | 8.96 ms: 1.15x faster                                           |
| sympy_expand             | 558 ms                                                 | 486 ms: 1.15x faster                                            |
| bench_thread_pool        | 966 us                                                 | 850 us: 1.14x faster                                            |
| json_loads               | 31.4 us                                                | 27.7 us: 1.13x faster                                           |
| xml_etree_generate       | 100.0 ms                                               | 88.3 ms: 1.13x faster                                           |
| regex_compile            | 186 ms                                                 | 165 ms: 1.13x faster                                            |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                           |
| dulwich_log              | 77.0 ms                                                | 69.8 ms: 1.10x faster                                           |
| mdp                      | 2.93 sec                                               | 2.68 sec: 1.09x faster                                          |
| json                     | 5.67 ms                                                | 5.21 ms: 1.09x faster                                           |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                            |
| nqueens                  | 107 ms                                                 | 99.1 ms: 1.08x faster                                           |
| scimark_fft              | 454 ms                                                 | 424 ms: 1.07x faster                                            |
| regex_v8                 | 26.2 ms                                                | 24.6 ms: 1.07x faster                                           |
| sqlite_synth             | 3.02 us                                                | 2.83 us: 1.07x faster                                           |
| xml_etree_iterparse      | 116 ms                                                 | 111 ms: 1.05x faster                                            |
| pickle_list              | 5.05 us                                                | 4.87 us: 1.04x faster                                           |
| meteor_contest           | 119 ms                                                 | 116 ms: 1.03x faster                                            |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.92 ms: 1.03x faster                                           |
| pathlib                  | 20.3 ms                                                | 20.0 ms: 1.01x faster                                           |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                            |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                            |
| unpickle                 | 14.9 us                                                | 15.0 us: 1.01x slower                                           |
| regex_dna                | 215 ms                                                 | 222 ms: 1.03x slower                                            |
| pickle                   | 10.7 us                                                | 11.0 us: 1.03x slower                                           |
| unpickle_list            | 5.10 us                                                | 5.34 us: 1.05x slower                                           |
| regex_effbot             | 3.41 ms                                                | 3.58 ms: 1.05x slower                                           |
| async_generators         | 442 ms                                                 | 472 ms: 1.07x slower                                            |
| pickle_dict              | 30.0 us                                                | 32.6 us: 1.09x slower                                           |
| coverage                 | 82.0 ms                                                | 94.3 ms: 1.15x slower                                           |
| gc_traversal             | 3.43 ms                                                | 4.07 ms: 1.19x slower                                           |
| telco                    | 7.01 ms                                                | 8.65 ms: 1.23x slower                                           |
| python_startup_no_site   | 5.87 ms                                                | 9.01 ms: 1.53x slower                                           |
| Geometric mean           | (ref)                                                  | 1.25x faster                                                    |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231028-3.13.0a1+-e0e60ce/bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1+-e0e60ce.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.17x
