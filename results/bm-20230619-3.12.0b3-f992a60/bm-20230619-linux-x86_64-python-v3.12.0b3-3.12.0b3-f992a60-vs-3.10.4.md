
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b3
- machine: linux-x86_64
- commit hash: f992a60
- commit date: 2023-06-19
- overall geometric mean: 1.34x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 267 ms: 1.29x faster                                       |
| docutils       | 3.26 sec                                               | 2.72 sec: 1.20x faster                                     |
| tornado_http   | 131 ms                                                 | 99.3 ms: 1.32x faster                                      |
| Geometric mean | (ref)                                                  | 1.27x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 469 ms: 1.56x faster                                       |
| async_tree_io           | 1.79 sec                                               | 1.16 sec: 1.54x faster                                     |
| async_tree_memoization  | 867 ms                                                 | 575 ms: 1.51x faster                                       |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 713 ms: 1.41x faster                                       |
| Geometric mean          | (ref)                                                  | 1.51x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 148 ms                                                 | 94.3 ms: 1.57x faster                                      |
| float          | 116 ms                                                 | 80.4 ms: 1.45x faster                                      |
| pidigits       | 190 ms                                                 | 197 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                  | 1.30x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 144 ms: 1.29x faster                                       |
| regex_v8       | 26.2 ms                                                | 22.9 ms: 1.14x faster                                      |
| regex_dna      | 215 ms                                                 | 200 ms: 1.07x faster                                       |
| regex_effbot   | 3.41 ms                                                | 3.56 ms: 1.04x slower                                      |
| Geometric mean | (ref)                                                  | 1.11x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 312 us: 1.55x faster                                       |
| unpickle_pure_python | 327 us                                                 | 215 us: 1.52x faster                                       |
| json_dumps           | 14.3 ms                                                | 9.79 ms: 1.46x faster                                      |
| tomli_loads          | 3.06 sec                                               | 2.17 sec: 1.41x faster                                     |
| xml_etree_process    | 79.8 ms                                                | 59.2 ms: 1.35x faster                                      |
| json_loads           | 31.4 us                                                | 25.0 us: 1.25x faster                                      |
| xml_etree_generate   | 100.0 ms                                               | 85.4 ms: 1.17x faster                                      |
| xml_etree_parse      | 171 ms                                                 | 152 ms: 1.13x faster                                       |
| xml_etree_iterparse  | 116 ms                                                 | 103 ms: 1.13x faster                                       |
| pickle_list          | 5.05 us                                                | 4.49 us: 1.12x faster                                      |
| unpickle_list        | 5.10 us                                                | 4.96 us: 1.03x faster                                      |
| pickle               | 10.7 us                                                | 11.0 us: 1.03x slower                                      |
| pickle_dict          | 30.0 us                                                | 31.8 us: 1.06x slower                                      |
| Geometric mean       | (ref)                                                  | 1.20x faster                                               |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 9.28 ms: 1.54x faster                                      |
| python_startup_no_site | 5.87 ms                                                | 6.74 ms: 1.15x slower                                      |
| Geometric mean         | (ref)                                                  | 1.16x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 16.3 ms                                                | 10.6 ms: 1.53x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 146 us: 3.84x faster                                       |
| generators               | 78.9 ms                                                | 30.3 ms: 2.60x faster                                      |
| deltablue                | 7.81 ms                                                | 3.50 ms: 2.23x faster                                      |
| richards_super           | 95.6 ms                                                | 49.2 ms: 1.94x faster                                      |
| logging_silent           | 189 ns                                                 | 99.7 ns: 1.90x faster                                      |
| richards                 | 79.4 ms                                                | 43.8 ms: 1.82x faster                                      |
| chaos                    | 114 ms                                                 | 63.8 ms: 1.79x faster                                      |
| asyncio_tcp              | 918 ms                                                 | 513 ms: 1.79x faster                                       |
| go                       | 238 ms                                                 | 137 ms: 1.74x faster                                       |
| scimark_sor              | 214 ms                                                 | 124 ms: 1.73x faster                                       |
| hexiom                   | 10.3 ms                                                | 6.13 ms: 1.68x faster                                      |
| raytrace                 | 498 ms                                                 | 298 ms: 1.67x faster                                       |
| scimark_monte_carlo      | 118 ms                                                 | 71.2 ms: 1.66x faster                                      |
| crypto_pyaes             | 127 ms                                                 | 78.1 ms: 1.62x faster                                      |
| sqlglot_parse            | 2.15 ms                                                | 1.33 ms: 1.62x faster                                      |
| nbody                    | 148 ms                                                 | 94.3 ms: 1.57x faster                                      |
| pyflate                  | 708 ms                                                 | 453 ms: 1.56x faster                                       |
| scimark_lu               | 175 ms                                                 | 112 ms: 1.56x faster                                       |
| async_tree_none          | 732 ms                                                 | 469 ms: 1.56x faster                                       |
| coroutines               | 34.5 ms                                                | 22.2 ms: 1.56x faster                                      |
| sqlglot_transpile        | 2.55 ms                                                | 1.64 ms: 1.55x faster                                      |
| pickle_pure_python       | 482 us                                                 | 312 us: 1.55x faster                                       |
| python_startup           | 14.3 ms                                                | 9.28 ms: 1.54x faster                                      |
| async_tree_io            | 1.79 sec                                               | 1.16 sec: 1.54x faster                                     |
| spectral_norm            | 163 ms                                                 | 106 ms: 1.54x faster                                       |
| deepcopy_memo            | 58.8 us                                                | 38.3 us: 1.54x faster                                      |
| mako                     | 16.3 ms                                                | 10.6 ms: 1.53x faster                                      |
| unpickle_pure_python     | 327 us                                                 | 215 us: 1.52x faster                                       |
| async_tree_memoization   | 867 ms                                                 | 575 ms: 1.51x faster                                       |
| json_dumps               | 14.3 ms                                                | 9.79 ms: 1.46x faster                                      |
| float                    | 116 ms                                                 | 80.4 ms: 1.45x faster                                      |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                     |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 713 ms: 1.41x faster                                       |
| tomli_loads              | 3.06 sec                                               | 2.17 sec: 1.41x faster                                     |
| pprint_pformat           | 2.10 sec                                               | 1.50 sec: 1.40x faster                                     |
| unpack_sequence          | 65.7 ns                                                | 47.4 ns: 1.39x faster                                      |
| pprint_safe_repr         | 1.01 sec                                               | 734 ms: 1.38x faster                                       |
| comprehensions           | 28.5 us                                                | 20.7 us: 1.38x faster                                      |
| fannkuch                 | 527 ms                                                 | 387 ms: 1.36x faster                                       |
| pycparser                | 1.57 sec                                               | 1.16 sec: 1.35x faster                                     |
| xml_etree_process        | 79.8 ms                                                | 59.2 ms: 1.35x faster                                      |
| deepcopy                 | 481 us                                                 | 359 us: 1.34x faster                                       |
| deepcopy_reduce          | 4.17 us                                                | 3.12 us: 1.33x faster                                      |
| logging_simple           | 8.27 us                                                | 6.25 us: 1.32x faster                                      |
| nqueens                  | 107 ms                                                 | 80.5 ms: 1.32x faster                                      |
| tornado_http             | 131 ms                                                 | 99.3 ms: 1.32x faster                                      |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                       |
| logging_format           | 9.07 us                                                | 6.99 us: 1.30x faster                                      |
| 2to3                     | 346 ms                                                 | 267 ms: 1.29x faster                                       |
| regex_compile            | 186 ms                                                 | 144 ms: 1.29x faster                                       |
| sqlglot_optimize         | 68.7 ms                                                | 53.5 ms: 1.28x faster                                      |
| scimark_fft              | 454 ms                                                 | 358 ms: 1.27x faster                                       |
| json_loads               | 31.4 us                                                | 25.0 us: 1.25x faster                                      |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.88 ms: 1.25x faster                                      |
| docutils                 | 3.26 sec                                               | 2.72 sec: 1.20x faster                                     |
| json                     | 5.67 ms                                                | 4.74 ms: 1.19x faster                                      |
| sqlalchemy_imperative    | 21.9 ms                                                | 18.4 ms: 1.19x faster                                      |
| sqlalchemy_declarative   | 170 ms                                                 | 145 ms: 1.17x faster                                       |
| xml_etree_generate       | 100.0 ms                                               | 85.4 ms: 1.17x faster                                      |
| bench_thread_pool        | 966 us                                                 | 827 us: 1.17x faster                                       |
| regex_v8                 | 26.2 ms                                                | 22.9 ms: 1.14x faster                                      |
| dulwich_log              | 77.0 ms                                                | 67.9 ms: 1.13x faster                                      |
| meteor_contest           | 119 ms                                                 | 106 ms: 1.13x faster                                       |
| xml_etree_parse          | 171 ms                                                 | 152 ms: 1.13x faster                                       |
| xml_etree_iterparse      | 116 ms                                                 | 103 ms: 1.13x faster                                       |
| pickle_list              | 5.05 us                                                | 4.49 us: 1.12x faster                                      |
| pathlib                  | 20.3 ms                                                | 18.2 ms: 1.11x faster                                      |
| mdp                      | 2.93 sec                                               | 2.64 sec: 1.11x faster                                     |
| sqlite_synth             | 3.02 us                                                | 2.75 us: 1.10x faster                                      |
| create_gc_cycles         | 1.61 ms                                                | 1.50 ms: 1.07x faster                                      |
| regex_dna                | 215 ms                                                 | 200 ms: 1.07x faster                                       |
| telco                    | 7.01 ms                                                | 6.82 ms: 1.03x faster                                      |
| unpickle_list            | 5.10 us                                                | 4.96 us: 1.03x faster                                      |
| async_generators         | 442 ms                                                 | 444 ms: 1.00x slower                                       |
| pickle                   | 10.7 us                                                | 11.0 us: 1.03x slower                                      |
| pidigits                 | 190 ms                                                 | 197 ms: 1.03x slower                                       |
| regex_effbot             | 3.41 ms                                                | 3.56 ms: 1.04x slower                                      |
| pickle_dict              | 30.0 us                                                | 31.8 us: 1.06x slower                                      |
| python_startup_no_site   | 5.87 ms                                                | 6.74 ms: 1.15x slower                                      |
| coverage                 | 82.0 ms                                                | 95.0 ms: 1.16x slower                                      |
| gc_traversal             | 3.43 ms                                                | 4.07 ms: 1.19x slower                                      |
| dask                     | 432 ms                                                 | 536 ms: 1.24x slower                                       |
| Geometric mean           | (ref)                                                  | 1.34x faster                                               |

Benchmark hidden because not significant (3): bench_mp_pool, unpickle, mypy2
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.26x
