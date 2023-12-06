
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b3
- machine: linux-x86_64
- commit hash: f992a60
- commit date: 2023-06-19
- overall geometric mean: 1.02x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 267 ms: 1.03x faster                                       |
| docutils       | 2.75 sec                                               | 2.72 sec: 1.01x faster                                     |
| tornado_http   | 101 ms                                                 | 99.3 ms: 1.01x faster                                      |
| Geometric mean | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 713 ms: 1.02x faster                                       |
| async_tree_none         | 475 ms                                                 | 469 ms: 1.01x faster                                       |
| async_tree_io           | 1.16 sec                                               | 1.16 sec: 1.00x faster                                     |
| Geometric mean          | (ref)                                                  | 1.01x faster                                               |

Benchmark hidden because not significant (1): async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 83.3 ms                                                | 80.4 ms: 1.04x faster                                      |
| nbody          | 92.2 ms                                                | 94.3 ms: 1.02x slower                                      |
| pidigits       | 187 ms                                                 | 197 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 200 ms: 1.04x faster                                       |
| regex_compile  | 148 ms                                                 | 144 ms: 1.03x faster                                       |
| regex_effbot   | 3.57 ms                                                | 3.56 ms: 1.00x faster                                      |
| regex_v8       | 22.7 ms                                                | 22.9 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                  | 1.01x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| json_loads           | 28.4 us                                                | 25.0 us: 1.13x faster                                      |
| json_dumps           | 10.6 ms                                                | 9.79 ms: 1.08x faster                                      |
| unpickle_pure_python | 230 us                                                 | 215 us: 1.07x faster                                       |
| tomli_loads          | 2.30 sec                                               | 2.17 sec: 1.06x faster                                     |
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                      |
| pickle_dict          | 33.5 us                                                | 31.8 us: 1.05x faster                                      |
| xml_etree_parse      | 159 ms                                                 | 152 ms: 1.05x faster                                       |
| pickle_pure_python   | 326 us                                                 | 312 us: 1.05x faster                                       |
| pickle_list          | 4.67 us                                                | 4.49 us: 1.04x faster                                      |
| xml_etree_generate   | 88.7 ms                                                | 85.4 ms: 1.04x faster                                      |
| xml_etree_process    | 61.2 ms                                                | 59.2 ms: 1.04x faster                                      |
| xml_etree_iterparse  | 106 ms                                                 | 103 ms: 1.03x faster                                       |
| pickle               | 11.2 us                                                | 11.0 us: 1.02x faster                                      |
| unpickle_list        | 5.04 us                                                | 4.96 us: 1.02x faster                                      |
| Geometric mean       | (ref)                                                  | 1.05x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 9.28 ms: 1.03x faster                                      |
| python_startup_no_site | 6.92 ms                                                | 6.74 ms: 1.03x faster                                      |
| Geometric mean         | (ref)                                                  | 1.03x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 11.5 ms                                                | 10.6 ms: 1.08x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230619-linux-x86_64-python-v3.12.0b3-3.12.0b3-f992a60 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| unpack_sequence          | 54.2 ns                                                | 47.4 ns: 1.14x faster                                      |
| json_loads               | 28.4 us                                                | 25.0 us: 1.13x faster                                      |
| json                     | 5.22 ms                                                | 4.74 ms: 1.10x faster                                      |
| scimark_sparse_mat_mult  | 5.33 ms                                                | 4.88 ms: 1.09x faster                                      |
| mako                     | 11.5 ms                                                | 10.6 ms: 1.08x faster                                      |
| spectral_norm            | 115 ms                                                 | 106 ms: 1.08x faster                                       |
| json_dumps               | 10.6 ms                                                | 9.79 ms: 1.08x faster                                      |
| logging_silent           | 108 ns                                                 | 99.7 ns: 1.08x faster                                      |
| scimark_lu               | 120 ms                                                 | 112 ms: 1.07x faster                                       |
| nqueens                  | 86.2 ms                                                | 80.5 ms: 1.07x faster                                      |
| crypto_pyaes             | 83.6 ms                                                | 78.1 ms: 1.07x faster                                      |
| generators               | 32.5 ms                                                | 30.3 ms: 1.07x faster                                      |
| hexiom                   | 6.54 ms                                                | 6.13 ms: 1.07x faster                                      |
| unpickle_pure_python     | 230 us                                                 | 215 us: 1.07x faster                                       |
| scimark_fft              | 381 ms                                                 | 358 ms: 1.06x faster                                       |
| tomli_loads              | 2.30 sec                                               | 2.17 sec: 1.06x faster                                     |
| deltablue                | 3.71 ms                                                | 3.50 ms: 1.06x faster                                      |
| unpickle                 | 15.8 us                                                | 14.9 us: 1.06x faster                                      |
| coroutines               | 23.5 ms                                                | 22.2 ms: 1.06x faster                                      |
| fannkuch                 | 410 ms                                                 | 387 ms: 1.06x faster                                       |
| chaos                    | 67.5 ms                                                | 63.8 ms: 1.06x faster                                      |
| richards_super           | 51.9 ms                                                | 49.2 ms: 1.06x faster                                      |
| pickle_dict              | 33.5 us                                                | 31.8 us: 1.05x faster                                      |
| richards                 | 46.0 ms                                                | 43.8 ms: 1.05x faster                                      |
| telco                    | 7.18 ms                                                | 6.82 ms: 1.05x faster                                      |
| gc_traversal             | 4.28 ms                                                | 4.07 ms: 1.05x faster                                      |
| typing_runtime_protocols | 153 us                                                 | 146 us: 1.05x faster                                       |
| xml_etree_parse          | 159 ms                                                 | 152 ms: 1.05x faster                                       |
| scimark_monte_carlo      | 74.6 ms                                                | 71.2 ms: 1.05x faster                                      |
| pickle_pure_python       | 326 us                                                 | 312 us: 1.05x faster                                       |
| scimark_sor              | 129 ms                                                 | 124 ms: 1.04x faster                                       |
| pprint_safe_repr         | 765 ms                                                 | 734 ms: 1.04x faster                                       |
| regex_dna                | 209 ms                                                 | 200 ms: 1.04x faster                                       |
| pickle_list              | 4.67 us                                                | 4.49 us: 1.04x faster                                      |
| meteor_contest           | 110 ms                                                 | 106 ms: 1.04x faster                                       |
| pyflate                  | 471 ms                                                 | 453 ms: 1.04x faster                                       |
| xml_etree_generate       | 88.7 ms                                                | 85.4 ms: 1.04x faster                                      |
| deepcopy_memo            | 39.7 us                                                | 38.3 us: 1.04x faster                                      |
| pathlib                  | 18.9 ms                                                | 18.2 ms: 1.04x faster                                      |
| float                    | 83.3 ms                                                | 80.4 ms: 1.04x faster                                      |
| async_generators         | 459 ms                                                 | 444 ms: 1.04x faster                                       |
| xml_etree_process        | 61.2 ms                                                | 59.2 ms: 1.04x faster                                      |
| deepcopy_reduce          | 3.23 us                                                | 3.12 us: 1.03x faster                                      |
| pprint_pformat           | 1.55 sec                                               | 1.50 sec: 1.03x faster                                     |
| raytrace                 | 308 ms                                                 | 298 ms: 1.03x faster                                       |
| sqlite_synth             | 2.83 us                                                | 2.75 us: 1.03x faster                                      |
| sqlglot_normalize        | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| python_startup           | 9.53 ms                                                | 9.28 ms: 1.03x faster                                      |
| go                       | 140 ms                                                 | 137 ms: 1.03x faster                                       |
| regex_compile            | 148 ms                                                 | 144 ms: 1.03x faster                                       |
| 2to3                     | 274 ms                                                 | 267 ms: 1.03x faster                                       |
| python_startup_no_site   | 6.92 ms                                                | 6.74 ms: 1.03x faster                                      |
| xml_etree_iterparse      | 106 ms                                                 | 103 ms: 1.03x faster                                       |
| sqlglot_optimize         | 54.8 ms                                                | 53.5 ms: 1.02x faster                                      |
| pickle                   | 11.2 us                                                | 11.0 us: 1.02x faster                                      |
| bench_thread_pool        | 845 us                                                 | 827 us: 1.02x faster                                       |
| logging_simple           | 6.38 us                                                | 6.25 us: 1.02x faster                                      |
| sqlglot_transpile        | 1.68 ms                                                | 1.64 ms: 1.02x faster                                      |
| sqlglot_parse            | 1.35 ms                                                | 1.33 ms: 1.02x faster                                      |
| unpickle_list            | 5.04 us                                                | 4.96 us: 1.02x faster                                      |
| async_tree_cpu_io_mixed  | 724 ms                                                 | 713 ms: 1.02x faster                                       |
| logging_format           | 7.10 us                                                | 6.99 us: 1.02x faster                                      |
| sqlalchemy_declarative   | 147 ms                                                 | 145 ms: 1.01x faster                                       |
| async_tree_none          | 475 ms                                                 | 469 ms: 1.01x faster                                       |
| tornado_http             | 101 ms                                                 | 99.3 ms: 1.01x faster                                      |
| docutils                 | 2.75 sec                                               | 2.72 sec: 1.01x faster                                     |
| dulwich_log              | 68.7 ms                                                | 67.9 ms: 1.01x faster                                      |
| deepcopy                 | 363 us                                                 | 359 us: 1.01x faster                                       |
| pycparser                | 1.17 sec                                               | 1.16 sec: 1.01x faster                                     |
| comprehensions           | 20.9 us                                                | 20.7 us: 1.01x faster                                      |
| async_tree_io            | 1.16 sec                                               | 1.16 sec: 1.00x faster                                     |
| regex_effbot             | 3.57 ms                                                | 3.56 ms: 1.00x faster                                      |
| asyncio_tcp_ssl          | 1.78 sec                                               | 1.79 sec: 1.01x slower                                     |
| regex_v8                 | 22.7 ms                                                | 22.9 ms: 1.01x slower                                      |
| asyncio_tcp              | 506 ms                                                 | 513 ms: 1.01x slower                                       |
| nbody                    | 92.2 ms                                                | 94.3 ms: 1.02x slower                                      |
| mdp                      | 2.57 sec                                               | 2.64 sec: 1.03x slower                                     |
| create_gc_cycles         | 1.45 ms                                                | 1.50 ms: 1.03x slower                                      |
| pidigits                 | 187 ms                                                 | 197 ms: 1.05x slower                                       |
| coverage                 | 75.1 ms                                                | 95.0 ms: 1.26x slower                                      |
| mypy2                    | 351 ms                                                 | 458 ms: 1.30x slower                                       |
| dask                     | 369 ms                                                 | 536 ms: 1.45x slower                                       |
| Geometric mean           | (ref)                                                  | 1.02x faster                                               |

Benchmark hidden because not significant (3): async_tree_memoization, sqlalchemy_imperative, bench_mp_pool
Ignored benchmarks (13) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
