
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b3
- machine: linux-x86_64
- commit hash: f992a60
- commit date: 2023-06-19
- overall geometric mean: 1.06x faster \*
- HPT reliability: 97.95%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 267 ms: 1.00x slower                                       |
| docutils       | 2.69 sec                                               | 2.72 sec: 1.01x slower                                     |
| tornado_http   | 97.7 ms                                                | 99.3 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 532 ms                                                 | 469 ms: 1.13x faster                                       |
| async_tree_io           | 1.31 sec                                               | 1.16 sec: 1.13x faster                                     |
| async_tree_memoization  | 640 ms                                                 | 575 ms: 1.11x faster                                       |
| async_tree_cpu_io_mixed | 750 ms                                                 | 713 ms: 1.05x faster                                       |
| Geometric mean          | (ref)                                                  | 1.11x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 78.9 ms                                                | 80.4 ms: 1.02x slower                                      |
| nbody          | 91.6 ms                                                | 94.3 ms: 1.03x slower                                      |
| pidigits       | 190 ms                                                 | 197 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                  | 1.03x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 204 ms                                                 | 200 ms: 1.02x faster                                       |
| regex_compile  | 141 ms                                                 | 144 ms: 1.02x slower                                       |
| regex_effbot   | 3.45 ms                                                | 3.56 ms: 1.03x slower                                      |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 9.79 ms: 1.37x faster                                      |
| json_loads           | 29.4 us                                                | 25.0 us: 1.18x faster                                      |
| unpickle_pure_python | 241 us                                                 | 215 us: 1.12x faster                                       |
| pickle_dict          | 34.8 us                                                | 31.8 us: 1.10x faster                                      |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                       |
| tomli_loads          | 2.31 sec                                               | 2.17 sec: 1.07x faster                                     |
| xml_etree_iterparse  | 109 ms                                                 | 103 ms: 1.05x faster                                       |
| unpickle_list        | 5.22 us                                                | 4.96 us: 1.05x faster                                      |
| pickle_list          | 4.65 us                                                | 4.49 us: 1.03x faster                                      |
| pickle_pure_python   | 319 us                                                 | 312 us: 1.02x faster                                       |
| pickle               | 11.1 us                                                | 11.0 us: 1.01x faster                                      |
| xml_etree_process    | 56.5 ms                                                | 59.2 ms: 1.05x slower                                      |
| xml_etree_generate   | 80.4 ms                                                | 85.4 ms: 1.06x slower                                      |
| unpickle             | 13.9 us                                                | 14.9 us: 1.07x slower                                      |
| Geometric mean       | (ref)                                                  | 1.06x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 9.28 ms: 1.07x slower                                      |
| python_startup_no_site | 6.09 ms                                                | 6.74 ms: 1.11x slower                                      |
| Geometric mean         | (ref)                                                  | 1.09x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 10.8 ms                                                | 10.6 ms: 1.02x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 521 us                                                 | 146 us: 3.57x faster                                       |
| generators               | 76.5 ms                                                | 30.3 ms: 2.52x faster                                      |
| asyncio_tcp_ssl          | 3.13 sec                                               | 1.79 sec: 1.74x faster                                     |
| asyncio_tcp              | 887 ms                                                 | 513 ms: 1.73x faster                                       |
| json_dumps               | 13.5 ms                                                | 9.79 ms: 1.37x faster                                      |
| richards_super           | 61.2 ms                                                | 49.2 ms: 1.25x faster                                      |
| coroutines               | 26.1 ms                                                | 22.2 ms: 1.18x faster                                      |
| json_loads               | 29.4 us                                                | 25.0 us: 1.18x faster                                      |
| comprehensions           | 23.6 us                                                | 20.7 us: 1.14x faster                                      |
| async_tree_none          | 532 ms                                                 | 469 ms: 1.13x faster                                       |
| async_tree_io            | 1.31 sec                                               | 1.16 sec: 1.13x faster                                     |
| unpickle_pure_python     | 241 us                                                 | 215 us: 1.12x faster                                       |
| chaos                    | 71.4 ms                                                | 63.8 ms: 1.12x faster                                      |
| richards                 | 48.9 ms                                                | 43.8 ms: 1.12x faster                                      |
| async_tree_memoization   | 640 ms                                                 | 575 ms: 1.11x faster                                       |
| json                     | 5.24 ms                                                | 4.74 ms: 1.10x faster                                      |
| hexiom                   | 6.74 ms                                                | 6.13 ms: 1.10x faster                                      |
| pickle_dict              | 34.8 us                                                | 31.8 us: 1.10x faster                                      |
| logging_silent           | 108 ns                                                 | 99.7 ns: 1.09x faster                                      |
| deltablue                | 3.80 ms                                                | 3.50 ms: 1.09x faster                                      |
| sqlglot_parse            | 1.43 ms                                                | 1.33 ms: 1.08x faster                                      |
| nqueens                  | 86.8 ms                                                | 80.5 ms: 1.08x faster                                      |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                       |
| sqlglot_transpile        | 1.75 ms                                                | 1.64 ms: 1.07x faster                                      |
| tomli_loads              | 2.31 sec                                               | 2.17 sec: 1.07x faster                                     |
| fannkuch                 | 410 ms                                                 | 387 ms: 1.06x faster                                       |
| mdp                      | 2.79 sec                                               | 2.64 sec: 1.05x faster                                     |
| xml_etree_iterparse      | 109 ms                                                 | 103 ms: 1.05x faster                                       |
| unpickle_list            | 5.22 us                                                | 4.96 us: 1.05x faster                                      |
| async_tree_cpu_io_mixed  | 750 ms                                                 | 713 ms: 1.05x faster                                       |
| go                       | 143 ms                                                 | 137 ms: 1.05x faster                                       |
| pickle_list              | 4.65 us                                                | 4.49 us: 1.03x faster                                      |
| sqlglot_normalize        | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| meteor_contest           | 109 ms                                                 | 106 ms: 1.03x faster                                       |
| sqlglot_optimize         | 55.2 ms                                                | 53.5 ms: 1.03x faster                                      |
| pycparser                | 1.20 sec                                               | 1.16 sec: 1.03x faster                                     |
| raytrace                 | 306 ms                                                 | 298 ms: 1.03x faster                                       |
| pickle_pure_python       | 319 us                                                 | 312 us: 1.02x faster                                       |
| mako                     | 10.8 ms                                                | 10.6 ms: 1.02x faster                                      |
| regex_dna                | 204 ms                                                 | 200 ms: 1.02x faster                                       |
| deepcopy_memo            | 38.9 us                                                | 38.3 us: 1.02x faster                                      |
| pprint_pformat           | 1.53 sec                                               | 1.50 sec: 1.02x faster                                     |
| pathlib                  | 18.5 ms                                                | 18.2 ms: 1.01x faster                                      |
| pprint_safe_repr         | 743 ms                                                 | 734 ms: 1.01x faster                                       |
| pickle                   | 11.1 us                                                | 11.0 us: 1.01x faster                                      |
| bench_thread_pool        | 833 us                                                 | 827 us: 1.01x faster                                       |
| scimark_monte_carlo      | 71.8 ms                                                | 71.2 ms: 1.01x faster                                      |
| deepcopy                 | 360 us                                                 | 359 us: 1.00x faster                                       |
| 2to3                     | 266 ms                                                 | 267 ms: 1.00x slower                                       |
| crypto_pyaes             | 77.5 ms                                                | 78.1 ms: 1.01x slower                                      |
| sqlalchemy_imperative    | 18.2 ms                                                | 18.4 ms: 1.01x slower                                      |
| docutils                 | 2.69 sec                                               | 2.72 sec: 1.01x slower                                     |
| scimark_sparse_mat_mult  | 4.80 ms                                                | 4.88 ms: 1.01x slower                                      |
| create_gc_cycles         | 1.48 ms                                                | 1.50 ms: 1.01x slower                                      |
| telco                    | 6.72 ms                                                | 6.82 ms: 1.02x slower                                      |
| tornado_http             | 97.7 ms                                                | 99.3 ms: 1.02x slower                                      |
| float                    | 78.9 ms                                                | 80.4 ms: 1.02x slower                                      |
| scimark_sor              | 121 ms                                                 | 124 ms: 1.02x slower                                       |
| regex_compile            | 141 ms                                                 | 144 ms: 1.02x slower                                       |
| logging_format           | 6.83 us                                                | 6.99 us: 1.02x slower                                      |
| sqlalchemy_declarative   | 141 ms                                                 | 145 ms: 1.03x slower                                       |
| nbody                    | 91.6 ms                                                | 94.3 ms: 1.03x slower                                      |
| regex_effbot             | 3.45 ms                                                | 3.56 ms: 1.03x slower                                      |
| pidigits                 | 190 ms                                                 | 197 ms: 1.03x slower                                       |
| gc_traversal             | 3.90 ms                                                | 4.07 ms: 1.04x slower                                      |
| dulwich_log              | 64.9 ms                                                | 67.9 ms: 1.05x slower                                      |
| scimark_fft              | 342 ms                                                 | 358 ms: 1.05x slower                                       |
| xml_etree_process        | 56.5 ms                                                | 59.2 ms: 1.05x slower                                      |
| xml_etree_generate       | 80.4 ms                                                | 85.4 ms: 1.06x slower                                      |
| pyflate                  | 426 ms                                                 | 453 ms: 1.06x slower                                       |
| sqlite_synth             | 2.58 us                                                | 2.75 us: 1.07x slower                                      |
| python_startup           | 8.69 ms                                                | 9.28 ms: 1.07x slower                                      |
| unpickle                 | 13.9 us                                                | 14.9 us: 1.07x slower                                      |
| unpack_sequence          | 43.3 ns                                                | 47.4 ns: 1.09x slower                                      |
| python_startup_no_site   | 6.09 ms                                                | 6.74 ms: 1.11x slower                                      |
| coverage                 | 81.2 ms                                                | 95.0 ms: 1.17x slower                                      |
| async_generators         | 375 ms                                                 | 444 ms: 1.18x slower                                       |
| dask                     | 365 ms                                                 | 536 ms: 1.47x slower                                       |
| Geometric mean           | (ref)                                                  | 1.06x faster                                               |

Benchmark hidden because not significant (7): deepcopy_reduce, scimark_lu, bench_mp_pool, logging_simple, regex_v8, spectral_norm, mypy2
Ignored benchmarks (20) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.95% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
