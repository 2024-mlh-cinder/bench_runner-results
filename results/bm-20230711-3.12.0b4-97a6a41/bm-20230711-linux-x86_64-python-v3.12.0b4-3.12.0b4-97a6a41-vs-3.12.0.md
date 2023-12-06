
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b4
- machine: linux-x86_64
- commit hash: 97a6a41
- commit date: 2023-07-11
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 267 ms: 1.03x faster                                       |
| docutils       | 2.75 sec                                               | 2.70 sec: 1.02x faster                                     |
| tornado_http   | 101 ms                                                 | 99.1 ms: 1.02x faster                                      |
| Geometric mean | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 715 ms: 1.01x faster                                       |
| async_tree_memoization  | 580 ms                                                 | 573 ms: 1.01x faster                                       |
| async_tree_none         | 475 ms                                                 | 472 ms: 1.01x faster                                       |
| async_tree_io           | 1.16 sec                                               | 1.16 sec: 1.00x faster                                     |
| Geometric mean          | (ref)                                                  | 1.01x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 92.2 ms                                                | 89.2 ms: 1.03x faster                                      |
| float          | 83.3 ms                                                | 80.7 ms: 1.03x faster                                      |
| pidigits       | 187 ms                                                 | 192 ms: 1.02x slower                                       |
| Geometric mean | (ref)                                                  | 1.01x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 142 ms: 1.04x faster                                       |
| regex_dna      | 209 ms                                                 | 207 ms: 1.01x faster                                       |
| regex_v8       | 22.7 ms                                                | 23.0 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                  | 1.01x faster                                               |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| json_loads           | 28.4 us                                                | 25.7 us: 1.11x faster                                      |
| json_dumps           | 10.6 ms                                                | 9.66 ms: 1.09x faster                                      |
| pickle_pure_python   | 326 us                                                 | 306 us: 1.07x faster                                       |
| pickle_dict          | 33.5 us                                                | 31.6 us: 1.06x faster                                      |
| unpickle_pure_python | 230 us                                                 | 217 us: 1.06x faster                                       |
| pickle               | 11.2 us                                                | 10.6 us: 1.05x faster                                      |
| xml_etree_parse      | 159 ms                                                 | 152 ms: 1.05x faster                                       |
| unpickle             | 15.8 us                                                | 15.1 us: 1.05x faster                                      |
| xml_etree_generate   | 88.7 ms                                                | 85.0 ms: 1.04x faster                                      |
| xml_etree_iterparse  | 106 ms                                                 | 102 ms: 1.04x faster                                       |
| tomli_loads          | 2.30 sec                                               | 2.23 sec: 1.03x faster                                     |
| xml_etree_process    | 61.2 ms                                                | 59.4 ms: 1.03x faster                                      |
| unpickle_list        | 5.04 us                                                | 4.95 us: 1.02x faster                                      |
| pickle_list          | 4.67 us                                                | 4.59 us: 1.02x faster                                      |
| Geometric mean       | (ref)                                                  | 1.05x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 9.35 ms: 1.02x faster                                      |
| python_startup_no_site | 6.92 ms                                                | 6.79 ms: 1.02x faster                                      |
| Geometric mean         | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 11.5 ms                                                | 10.9 ms: 1.06x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| spectral_norm            | 115 ms                                                 | 102 ms: 1.13x faster                                       |
| unpack_sequence          | 54.2 ns                                                | 48.9 ns: 1.11x faster                                      |
| json_loads               | 28.4 us                                                | 25.7 us: 1.11x faster                                      |
| logging_silent           | 108 ns                                                 | 97.8 ns: 1.10x faster                                      |
| gc_traversal             | 4.28 ms                                                | 3.91 ms: 1.10x faster                                      |
| json_dumps               | 10.6 ms                                                | 9.66 ms: 1.09x faster                                      |
| scimark_sparse_mat_mult  | 5.33 ms                                                | 4.91 ms: 1.09x faster                                      |
| scimark_sor              | 129 ms                                                 | 119 ms: 1.08x faster                                       |
| pyflate                  | 471 ms                                                 | 434 ms: 1.08x faster                                       |
| crypto_pyaes             | 83.6 ms                                                | 77.2 ms: 1.08x faster                                      |
| hexiom                   | 6.54 ms                                                | 6.05 ms: 1.08x faster                                      |
| chaos                    | 67.5 ms                                                | 62.7 ms: 1.08x faster                                      |
| scimark_lu               | 120 ms                                                 | 112 ms: 1.07x faster                                       |
| pickle_pure_python       | 326 us                                                 | 306 us: 1.07x faster                                       |
| fannkuch                 | 410 ms                                                 | 385 ms: 1.07x faster                                       |
| nqueens                  | 86.2 ms                                                | 80.9 ms: 1.07x faster                                      |
| scimark_fft              | 381 ms                                                 | 358 ms: 1.06x faster                                       |
| richards                 | 46.0 ms                                                | 43.3 ms: 1.06x faster                                      |
| generators               | 32.5 ms                                                | 30.5 ms: 1.06x faster                                      |
| deltablue                | 3.71 ms                                                | 3.49 ms: 1.06x faster                                      |
| pickle_dict              | 33.5 us                                                | 31.6 us: 1.06x faster                                      |
| unpickle_pure_python     | 230 us                                                 | 217 us: 1.06x faster                                       |
| typing_runtime_protocols | 153 us                                                 | 145 us: 1.06x faster                                       |
| mako                     | 11.5 ms                                                | 10.9 ms: 1.06x faster                                      |
| richards_super           | 51.9 ms                                                | 49.2 ms: 1.06x faster                                      |
| json                     | 5.22 ms                                                | 4.95 ms: 1.06x faster                                      |
| pickle                   | 11.2 us                                                | 10.6 us: 1.05x faster                                      |
| meteor_contest           | 110 ms                                                 | 104 ms: 1.05x faster                                       |
| telco                    | 7.18 ms                                                | 6.83 ms: 1.05x faster                                      |
| raytrace                 | 308 ms                                                 | 293 ms: 1.05x faster                                       |
| deepcopy_memo            | 39.7 us                                                | 37.9 us: 1.05x faster                                      |
| xml_etree_parse          | 159 ms                                                 | 152 ms: 1.05x faster                                       |
| pprint_safe_repr         | 765 ms                                                 | 731 ms: 1.05x faster                                       |
| unpickle                 | 15.8 us                                                | 15.1 us: 1.05x faster                                      |
| xml_etree_generate       | 88.7 ms                                                | 85.0 ms: 1.04x faster                                      |
| coroutines               | 23.5 ms                                                | 22.5 ms: 1.04x faster                                      |
| pprint_pformat           | 1.55 sec                                               | 1.49 sec: 1.04x faster                                     |
| regex_compile            | 148 ms                                                 | 142 ms: 1.04x faster                                       |
| deepcopy_reduce          | 3.23 us                                                | 3.11 us: 1.04x faster                                      |
| go                       | 140 ms                                                 | 135 ms: 1.04x faster                                       |
| sqlite_synth             | 2.83 us                                                | 2.74 us: 1.04x faster                                      |
| xml_etree_iterparse      | 106 ms                                                 | 102 ms: 1.04x faster                                       |
| nbody                    | 92.2 ms                                                | 89.2 ms: 1.03x faster                                      |
| float                    | 83.3 ms                                                | 80.7 ms: 1.03x faster                                      |
| tomli_loads              | 2.30 sec                                               | 2.23 sec: 1.03x faster                                     |
| xml_etree_process        | 61.2 ms                                                | 59.4 ms: 1.03x faster                                      |
| scimark_monte_carlo      | 74.6 ms                                                | 72.4 ms: 1.03x faster                                      |
| sqlglot_normalize        | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| logging_simple           | 6.38 us                                                | 6.21 us: 1.03x faster                                      |
| 2to3                     | 274 ms                                                 | 267 ms: 1.03x faster                                       |
| async_generators         | 459 ms                                                 | 448 ms: 1.03x faster                                       |
| mypy2                    | 351 ms                                                 | 343 ms: 1.02x faster                                       |
| logging_format           | 7.10 us                                                | 6.93 us: 1.02x faster                                      |
| bench_thread_pool        | 845 us                                                 | 827 us: 1.02x faster                                       |
| deepcopy                 | 363 us                                                 | 355 us: 1.02x faster                                       |
| sqlglot_transpile        | 1.68 ms                                                | 1.64 ms: 1.02x faster                                      |
| unpickle_list            | 5.04 us                                                | 4.95 us: 1.02x faster                                      |
| python_startup           | 9.53 ms                                                | 9.35 ms: 1.02x faster                                      |
| sqlalchemy_declarative   | 147 ms                                                 | 144 ms: 1.02x faster                                       |
| python_startup_no_site   | 6.92 ms                                                | 6.79 ms: 1.02x faster                                      |
| docutils                 | 2.75 sec                                               | 2.70 sec: 1.02x faster                                     |
| pickle_list              | 4.67 us                                                | 4.59 us: 1.02x faster                                      |
| sqlglot_parse            | 1.35 ms                                                | 1.33 ms: 1.02x faster                                      |
| sqlglot_optimize         | 54.8 ms                                                | 53.9 ms: 1.02x faster                                      |
| tornado_http             | 101 ms                                                 | 99.1 ms: 1.02x faster                                      |
| comprehensions           | 20.9 us                                                | 20.7 us: 1.01x faster                                      |
| async_tree_cpu_io_mixed  | 724 ms                                                 | 715 ms: 1.01x faster                                       |
| async_tree_memoization   | 580 ms                                                 | 573 ms: 1.01x faster                                       |
| dulwich_log              | 68.7 ms                                                | 67.9 ms: 1.01x faster                                      |
| regex_dna                | 209 ms                                                 | 207 ms: 1.01x faster                                       |
| async_tree_none          | 475 ms                                                 | 472 ms: 1.01x faster                                       |
| async_tree_io            | 1.16 sec                                               | 1.16 sec: 1.00x faster                                     |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                      |
| asyncio_tcp_ssl          | 1.78 sec                                               | 1.80 sec: 1.01x slower                                     |
| regex_v8                 | 22.7 ms                                                | 23.0 ms: 1.02x slower                                      |
| asyncio_tcp              | 506 ms                                                 | 517 ms: 1.02x slower                                       |
| pidigits                 | 187 ms                                                 | 192 ms: 1.02x slower                                       |
| create_gc_cycles         | 1.45 ms                                                | 1.51 ms: 1.04x slower                                      |
| mdp                      | 2.57 sec                                               | 2.73 sec: 1.06x slower                                     |
| coverage                 | 75.1 ms                                                | 93.5 ms: 1.24x slower                                      |
| dask                     | 369 ms                                                 | 535 ms: 1.45x slower                                       |
| Geometric mean           | (ref)                                                  | 1.03x faster                                               |

Benchmark hidden because not significant (4): pathlib, pycparser, sqlalchemy_imperative, regex_effbot
Ignored benchmarks (13) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
