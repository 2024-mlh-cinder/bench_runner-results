
# Results vs. 3.10.4

- fork: python
- ref: 9da98c0d9a7cc55c67fb
- machine: linux-x86_64
- commit hash: 9da98c0
- commit date: 2023-10-25
- overall geometric mean: 1.33x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 268 ms: 1.29x faster                                                   |
| chameleon      | 9.84 ms                                                | 6.91 ms: 1.42x faster                                                  |
| docutils       | 3.26 sec                                               | 2.65 sec: 1.23x faster                                                 |
| tornado_http   | 131 ms                                                 | 95.2 ms: 1.37x faster                                                  |
| Geometric mean | (ref)                                                  | 1.33x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 440 ms: 1.66x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 567 ms: 1.53x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.50x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 718 ms: 1.40x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.52x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 98.1 ms: 1.51x faster                                                  |
| float          | 116 ms                                                 | 81.8 ms: 1.42x faster                                                  |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                  | 1.30x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 138 ms: 1.35x faster                                                   |
| regex_v8       | 26.2 ms                                                | 25.4 ms: 1.03x faster                                                  |
| regex_dna      | 215 ms                                                 | 218 ms: 1.02x slower                                                   |
| regex_effbot   | 3.41 ms                                                | 3.84 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 308 us: 1.57x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 221 us: 1.48x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.15 sec: 1.42x faster                                                 |
| json_dumps           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 59.4 ms: 1.34x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 86.5 ms: 1.16x faster                                                  |
| json_loads           | 31.4 us                                                | 27.8 us: 1.13x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.09x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 160 ms: 1.07x faster                                                   |
| pickle_list          | 5.05 us                                                | 4.99 us: 1.01x faster                                                  |
| unpickle_list        | 5.10 us                                                | 5.17 us: 1.01x slower                                                  |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                                  |
| pickle_dict          | 30.0 us                                                | 33.5 us: 1.12x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.16x faster                                                           |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.1 ms: 1.42x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 6.88 ms: 1.17x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.10x faster                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.2 ms: 1.45x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 151 us: 3.70x faster                                                   |
| generators               | 78.9 ms                                                | 29.6 ms: 2.67x faster                                                  |
| deltablue                | 7.81 ms                                                | 3.29 ms: 2.38x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 484 ms: 1.90x faster                                                   |
| chaos                    | 114 ms                                                 | 62.2 ms: 1.84x faster                                                  |
| raytrace                 | 498 ms                                                 | 273 ms: 1.83x faster                                                   |
| logging_silent           | 189 ns                                                 | 107 ns: 1.77x faster                                                   |
| richards_super           | 95.6 ms                                                | 54.6 ms: 1.75x faster                                                  |
| crypto_pyaes             | 127 ms                                                 | 72.5 ms: 1.75x faster                                                  |
| scimark_monte_carlo      | 118 ms                                                 | 69.2 ms: 1.70x faster                                                  |
| scimark_sor              | 214 ms                                                 | 126 ms: 1.70x faster                                                   |
| go                       | 238 ms                                                 | 140 ms: 1.69x faster                                                   |
| hexiom                   | 10.3 ms                                                | 6.15 ms: 1.67x faster                                                  |
| async_tree_none          | 732 ms                                                 | 440 ms: 1.66x faster                                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.29 ms: 1.66x faster                                                  |
| richards                 | 79.4 ms                                                | 48.9 ms: 1.62x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.61 ms: 1.58x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 308 us: 1.57x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 38.3 us: 1.54x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 567 ms: 1.53x faster                                                   |
| scimark_lu               | 175 ms                                                 | 115 ms: 1.53x faster                                                   |
| coroutines               | 34.5 ms                                                | 22.7 ms: 1.52x faster                                                  |
| nbody                    | 148 ms                                                 | 98.1 ms: 1.51x faster                                                  |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.50x faster                                                 |
| pyflate                  | 708 ms                                                 | 471 ms: 1.50x faster                                                   |
| unpickle_pure_python     | 327 us                                                 | 221 us: 1.48x faster                                                   |
| unpack_sequence          | 65.7 ns                                                | 44.8 ns: 1.47x faster                                                  |
| spectral_norm            | 163 ms                                                 | 112 ms: 1.46x faster                                                   |
| mako                     | 16.3 ms                                                | 11.2 ms: 1.45x faster                                                  |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.77 sec: 1.45x faster                                                 |
| chameleon                | 9.84 ms                                                | 6.91 ms: 1.42x faster                                                  |
| float                    | 116 ms                                                 | 81.8 ms: 1.42x faster                                                  |
| tomli_loads              | 3.06 sec                                               | 2.15 sec: 1.42x faster                                                 |
| python_startup           | 14.3 ms                                                | 10.1 ms: 1.42x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 718 ms: 1.40x faster                                                   |
| logging_simple           | 8.27 us                                                | 5.89 us: 1.40x faster                                                  |
| logging_format           | 9.07 us                                                | 6.47 us: 1.40x faster                                                  |
| pprint_pformat           | 2.10 sec                                               | 1.52 sec: 1.38x faster                                                 |
| json_dumps               | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                  |
| comprehensions           | 28.5 us                                                | 20.8 us: 1.37x faster                                                  |
| tornado_http             | 131 ms                                                 | 95.2 ms: 1.37x faster                                                  |
| deepcopy                 | 481 us                                                 | 354 us: 1.36x faster                                                   |
| pprint_safe_repr         | 1.01 sec                                               | 751 ms: 1.35x faster                                                   |
| regex_compile            | 186 ms                                                 | 138 ms: 1.35x faster                                                   |
| xml_etree_process        | 79.8 ms                                                | 59.4 ms: 1.34x faster                                                  |
| pycparser                | 1.57 sec                                               | 1.17 sec: 1.34x faster                                                 |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.34x faster                                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.12 us: 1.34x faster                                                  |
| nqueens                  | 107 ms                                                 | 81.3 ms: 1.31x faster                                                  |
| mypy2                    | 442 ms                                                 | 343 ms: 1.29x faster                                                   |
| 2to3                     | 346 ms                                                 | 268 ms: 1.29x faster                                                   |
| sqlglot_optimize         | 68.7 ms                                                | 53.5 ms: 1.28x faster                                                  |
| fannkuch                 | 527 ms                                                 | 412 ms: 1.28x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 20.3 ms: 1.25x faster                                                  |
| sympy_expand             | 558 ms                                                 | 453 ms: 1.23x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.65 sec: 1.23x faster                                                 |
| sympy_sum                | 190 ms                                                 | 156 ms: 1.22x faster                                                   |
| sympy_str                | 337 ms                                                 | 279 ms: 1.21x faster                                                   |
| bench_thread_pool        | 966 us                                                 | 812 us: 1.19x faster                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.13 ms: 1.19x faster                                                  |
| scimark_fft              | 454 ms                                                 | 384 ms: 1.18x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 86.5 ms: 1.16x faster                                                  |
| dulwich_log              | 77.0 ms                                                | 66.9 ms: 1.15x faster                                                  |
| json_loads               | 31.4 us                                                | 27.8 us: 1.13x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.61 sec: 1.12x faster                                                 |
| json                     | 5.67 ms                                                | 5.09 ms: 1.11x faster                                                  |
| meteor_contest           | 119 ms                                                 | 108 ms: 1.10x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.10x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 106 ms: 1.09x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.81 us: 1.08x faster                                                  |
| xml_etree_parse          | 171 ms                                                 | 160 ms: 1.07x faster                                                   |
| pathlib                  | 20.3 ms                                                | 19.0 ms: 1.07x faster                                                  |
| regex_v8                 | 26.2 ms                                                | 25.4 ms: 1.03x faster                                                  |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                                   |
| pickle_list              | 5.05 us                                                | 4.99 us: 1.01x faster                                                  |
| unpickle_list            | 5.10 us                                                | 5.17 us: 1.01x slower                                                  |
| regex_dna                | 215 ms                                                 | 218 ms: 1.02x slower                                                   |
| async_generators         | 442 ms                                                 | 456 ms: 1.03x slower                                                   |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 3.79 ms: 1.10x slower                                                  |
| pickle_dict              | 30.0 us                                                | 33.5 us: 1.12x slower                                                  |
| regex_effbot             | 3.41 ms                                                | 3.84 ms: 1.13x slower                                                  |
| coverage                 | 82.0 ms                                                | 94.9 ms: 1.16x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 6.88 ms: 1.17x slower                                                  |
| telco                    | 7.01 ms                                                | 8.28 ms: 1.18x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.33x faster                                                           |

Benchmark hidden because not significant (2): unpickle, bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231025-3.13.0a1+-9da98c0/bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1+-9da98c0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.25x
