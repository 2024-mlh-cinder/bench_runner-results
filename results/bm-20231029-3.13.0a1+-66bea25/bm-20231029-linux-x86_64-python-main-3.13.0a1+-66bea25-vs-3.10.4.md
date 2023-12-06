
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.33x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 265 ms: 1.31x faster                                   |
| chameleon      | 9.84 ms                                                | 6.93 ms: 1.42x faster                                  |
| docutils       | 3.26 sec                                               | 2.64 sec: 1.23x faster                                 |
| tornado_http   | 131 ms                                                 | 95.6 ms: 1.37x faster                                  |
| Geometric mean | (ref)                                                  | 1.33x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 439 ms: 1.67x faster                                   |
| async_tree_memoization  | 867 ms                                                 | 563 ms: 1.54x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.51x faster                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 709 ms: 1.42x faster                                   |
| Geometric mean          | (ref)                                                  | 1.53x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 148 ms                                                 | 94.5 ms: 1.57x faster                                  |
| float          | 116 ms                                                 | 81.0 ms: 1.44x faster                                  |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                   |
| Geometric mean | (ref)                                                  | 1.32x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 136 ms: 1.36x faster                                   |
| regex_v8       | 26.2 ms                                                | 25.0 ms: 1.05x faster                                  |
| regex_dna      | 215 ms                                                 | 219 ms: 1.02x slower                                   |
| regex_effbot   | 3.41 ms                                                | 3.63 ms: 1.06x slower                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 302 us: 1.60x faster                                   |
| unpickle_pure_python | 327 us                                                 | 220 us: 1.49x faster                                   |
| tomli_loads          | 3.06 sec                                               | 2.15 sec: 1.42x faster                                 |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.37x faster                                  |
| xml_etree_process    | 79.8 ms                                                | 59.2 ms: 1.35x faster                                  |
| xml_etree_generate   | 100.0 ms                                               | 86.2 ms: 1.16x faster                                  |
| json_loads           | 31.4 us                                                | 27.8 us: 1.13x faster                                  |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.09x faster                                   |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                   |
| pickle_list          | 5.05 us                                                | 4.81 us: 1.05x faster                                  |
| unpickle             | 14.9 us                                                | 14.6 us: 1.02x faster                                  |
| unpickle_list        | 5.10 us                                                | 5.15 us: 1.01x slower                                  |
| pickle               | 10.7 us                                                | 11.3 us: 1.05x slower                                  |
| pickle_dict          | 30.0 us                                                | 33.2 us: 1.11x slower                                  |
| Geometric mean       | (ref)                                                  | 1.17x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                  |
| python_startup_no_site | 5.87 ms                                                | 8.97 ms: 1.53x slower                                  |
| Geometric mean         | (ref)                                                  | 1.05x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.5 ms: 1.42x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 152 us: 3.69x faster                                   |
| generators               | 78.9 ms                                                | 29.5 ms: 2.68x faster                                  |
| deltablue                | 7.81 ms                                                | 3.40 ms: 2.30x faster                                  |
| asyncio_tcp              | 918 ms                                                 | 474 ms: 1.94x faster                                   |
| chaos                    | 114 ms                                                 | 62.0 ms: 1.84x faster                                  |
| logging_silent           | 189 ns                                                 | 105 ns: 1.80x faster                                   |
| raytrace                 | 498 ms                                                 | 276 ms: 1.80x faster                                   |
| crypto_pyaes             | 127 ms                                                 | 72.2 ms: 1.75x faster                                  |
| comprehensions           | 28.5 us                                                | 16.5 us: 1.72x faster                                  |
| richards_super           | 95.6 ms                                                | 55.5 ms: 1.72x faster                                  |
| scimark_monte_carlo      | 118 ms                                                 | 68.8 ms: 1.71x faster                                  |
| scimark_sor              | 214 ms                                                 | 127 ms: 1.68x faster                                   |
| async_tree_none          | 732 ms                                                 | 439 ms: 1.67x faster                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.29 ms: 1.66x faster                                  |
| go                       | 238 ms                                                 | 145 ms: 1.64x faster                                   |
| hexiom                   | 10.3 ms                                                | 6.29 ms: 1.64x faster                                  |
| richards                 | 79.4 ms                                                | 49.6 ms: 1.60x faster                                  |
| pickle_pure_python       | 482 us                                                 | 302 us: 1.60x faster                                   |
| sqlglot_transpile        | 2.55 ms                                                | 1.61 ms: 1.58x faster                                  |
| nbody                    | 148 ms                                                 | 94.5 ms: 1.57x faster                                  |
| async_tree_memoization   | 867 ms                                                 | 563 ms: 1.54x faster                                   |
| pyflate                  | 708 ms                                                 | 462 ms: 1.53x faster                                   |
| coroutines               | 34.5 ms                                                | 22.5 ms: 1.53x faster                                  |
| scimark_lu               | 175 ms                                                 | 115 ms: 1.52x faster                                   |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.51x faster                                 |
| deepcopy_memo            | 58.8 us                                                | 39.1 us: 1.50x faster                                  |
| unpickle_pure_python     | 327 us                                                 | 220 us: 1.49x faster                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                 |
| float                    | 116 ms                                                 | 81.0 ms: 1.44x faster                                  |
| spectral_norm            | 163 ms                                                 | 114 ms: 1.43x faster                                   |
| tomli_loads              | 3.06 sec                                               | 2.15 sec: 1.42x faster                                 |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 709 ms: 1.42x faster                                   |
| chameleon                | 9.84 ms                                                | 6.93 ms: 1.42x faster                                  |
| mako                     | 16.3 ms                                                | 11.5 ms: 1.42x faster                                  |
| pprint_pformat           | 2.10 sec                                               | 1.50 sec: 1.40x faster                                 |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                  |
| logging_simple           | 8.27 us                                                | 5.95 us: 1.39x faster                                  |
| unpack_sequence          | 65.7 ns                                                | 47.3 ns: 1.39x faster                                  |
| logging_format           | 9.07 us                                                | 6.54 us: 1.39x faster                                  |
| pprint_safe_repr         | 1.01 sec                                               | 738 ms: 1.37x faster                                   |
| deepcopy                 | 481 us                                                 | 351 us: 1.37x faster                                   |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.37x faster                                  |
| tornado_http             | 131 ms                                                 | 95.6 ms: 1.37x faster                                  |
| regex_compile            | 186 ms                                                 | 136 ms: 1.36x faster                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.07 us: 1.36x faster                                  |
| xml_etree_process        | 79.8 ms                                                | 59.2 ms: 1.35x faster                                  |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.34x faster                                   |
| nqueens                  | 107 ms                                                 | 80.2 ms: 1.33x faster                                  |
| pycparser                | 1.57 sec                                               | 1.19 sec: 1.31x faster                                 |
| 2to3                     | 346 ms                                                 | 265 ms: 1.31x faster                                   |
| mypy2                    | 442 ms                                                 | 342 ms: 1.29x faster                                   |
| fannkuch                 | 527 ms                                                 | 408 ms: 1.29x faster                                   |
| sqlglot_optimize         | 68.7 ms                                                | 53.3 ms: 1.29x faster                                  |
| sympy_sum                | 190 ms                                                 | 148 ms: 1.29x faster                                   |
| sympy_integrate          | 25.4 ms                                                | 19.9 ms: 1.28x faster                                  |
| sympy_str                | 337 ms                                                 | 268 ms: 1.26x faster                                   |
| docutils                 | 3.26 sec                                               | 2.64 sec: 1.23x faster                                 |
| sympy_expand             | 558 ms                                                 | 452 ms: 1.23x faster                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.95 ms: 1.23x faster                                  |
| scimark_fft              | 454 ms                                                 | 369 ms: 1.23x faster                                   |
| bench_thread_pool        | 966 us                                                 | 815 us: 1.19x faster                                   |
| xml_etree_generate       | 100.0 ms                                               | 86.2 ms: 1.16x faster                                  |
| mdp                      | 2.93 sec                                               | 2.54 sec: 1.16x faster                                 |
| dulwich_log              | 77.0 ms                                                | 67.0 ms: 1.15x faster                                  |
| json_loads               | 31.4 us                                                | 27.8 us: 1.13x faster                                  |
| json                     | 5.67 ms                                                | 5.09 ms: 1.11x faster                                  |
| meteor_contest           | 119 ms                                                 | 108 ms: 1.11x faster                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.10x faster                                  |
| xml_etree_iterparse      | 116 ms                                                 | 106 ms: 1.09x faster                                   |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                   |
| sqlite_synth             | 3.02 us                                                | 2.81 us: 1.08x faster                                  |
| pathlib                  | 20.3 ms                                                | 19.2 ms: 1.06x faster                                  |
| regex_v8                 | 26.2 ms                                                | 25.0 ms: 1.05x faster                                  |
| pickle_list              | 5.05 us                                                | 4.81 us: 1.05x faster                                  |
| unpickle                 | 14.9 us                                                | 14.6 us: 1.02x faster                                  |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                   |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                   |
| unpickle_list            | 5.10 us                                                | 5.15 us: 1.01x slower                                  |
| regex_dna                | 215 ms                                                 | 219 ms: 1.02x slower                                   |
| async_generators         | 442 ms                                                 | 454 ms: 1.03x slower                                   |
| pickle                   | 10.7 us                                                | 11.3 us: 1.05x slower                                  |
| regex_effbot             | 3.41 ms                                                | 3.63 ms: 1.06x slower                                  |
| gc_traversal             | 3.43 ms                                                | 3.79 ms: 1.11x slower                                  |
| pickle_dict              | 30.0 us                                                | 33.2 us: 1.11x slower                                  |
| coverage                 | 82.0 ms                                                | 93.2 ms: 1.14x slower                                  |
| telco                    | 7.01 ms                                                | 8.29 ms: 1.18x slower                                  |
| python_startup_no_site   | 5.87 ms                                                | 8.97 ms: 1.53x slower                                  |
| Geometric mean           | (ref)                                                  | 1.33x faster                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231029-3.13.0a1+-66bea25/bm-20231029-linux-x86_64-python-main-3.13.0a1+-66bea25.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.26x
