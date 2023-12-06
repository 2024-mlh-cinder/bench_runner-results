
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b2
- machine: linux-x86_64
- commit hash: e6c0efa
- commit date: 2023-06-06
- overall geometric mean: 1.02x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 269 ms: 1.02x faster                                       |
| docutils       | 2.75 sec                                               | 2.72 sec: 1.01x faster                                     |
| tornado_http   | 101 ms                                                 | 99.3 ms: 1.01x faster                                      |
| Geometric mean | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 708 ms: 1.02x faster                                       |
| async_tree_memoization  | 580 ms                                                 | 570 ms: 1.02x faster                                       |
| async_tree_none         | 475 ms                                                 | 468 ms: 1.02x faster                                       |
| async_tree_io           | 1.16 sec                                               | 1.15 sec: 1.01x faster                                     |
| Geometric mean          | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 83.3 ms                                                | 80.3 ms: 1.04x faster                                      |
| nbody          | 92.2 ms                                                | 89.7 ms: 1.03x faster                                      |
| pidigits       | 187 ms                                                 | 197 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                  | 1.00x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 202 ms: 1.03x faster                                       |
| regex_compile  | 148 ms                                                 | 145 ms: 1.02x faster                                       |
| regex_v8       | 22.7 ms                                                | 22.9 ms: 1.01x slower                                      |
| regex_effbot   | 3.57 ms                                                | 3.83 ms: 1.07x slower                                      |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| json_loads           | 28.4 us                                                | 25.1 us: 1.13x faster                                      |
| json_dumps           | 10.6 ms                                                | 9.69 ms: 1.09x faster                                      |
| pickle_dict          | 33.5 us                                                | 31.3 us: 1.07x faster                                      |
| unpickle_pure_python | 230 us                                                 | 217 us: 1.06x faster                                       |
| unpickle             | 15.8 us                                                | 15.0 us: 1.05x faster                                      |
| pickle_pure_python   | 326 us                                                 | 314 us: 1.04x faster                                       |
| xml_etree_process    | 61.2 ms                                                | 59.1 ms: 1.04x faster                                      |
| xml_etree_generate   | 88.7 ms                                                | 85.6 ms: 1.04x faster                                      |
| unpickle_list        | 5.04 us                                                | 4.90 us: 1.03x faster                                      |
| pickle               | 11.2 us                                                | 10.9 us: 1.03x faster                                      |
| tomli_loads          | 2.30 sec                                               | 2.24 sec: 1.03x faster                                     |
| xml_etree_parse      | 159 ms                                                 | 156 ms: 1.02x faster                                       |
| xml_etree_iterparse  | 106 ms                                                 | 104 ms: 1.01x faster                                       |
| pickle_list          | 4.67 us                                                | 4.75 us: 1.02x slower                                      |
| Geometric mean       | (ref)                                                  | 1.04x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 9.30 ms: 1.03x faster                                      |
| python_startup_no_site | 6.92 ms                                                | 6.76 ms: 1.02x faster                                      |
| Geometric mean         | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 11.5 ms                                                | 10.6 ms: 1.09x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| unpack_sequence          | 54.2 ns                                                | 46.7 ns: 1.16x faster                                      |
| json_loads               | 28.4 us                                                | 25.1 us: 1.13x faster                                      |
| spectral_norm            | 115 ms                                                 | 104 ms: 1.10x faster                                       |
| json                     | 5.22 ms                                                | 4.76 ms: 1.10x faster                                      |
| scimark_sparse_mat_mult  | 5.33 ms                                                | 4.89 ms: 1.09x faster                                      |
| json_dumps               | 10.6 ms                                                | 9.69 ms: 1.09x faster                                      |
| mako                     | 11.5 ms                                                | 10.6 ms: 1.09x faster                                      |
| scimark_sor              | 129 ms                                                 | 120 ms: 1.07x faster                                       |
| deltablue                | 3.71 ms                                                | 3.46 ms: 1.07x faster                                      |
| crypto_pyaes             | 83.6 ms                                                | 78.0 ms: 1.07x faster                                      |
| pickle_dict              | 33.5 us                                                | 31.3 us: 1.07x faster                                      |
| richards                 | 46.0 ms                                                | 43.1 ms: 1.07x faster                                      |
| scimark_lu               | 120 ms                                                 | 113 ms: 1.06x faster                                       |
| scimark_fft              | 381 ms                                                 | 358 ms: 1.06x faster                                       |
| coroutines               | 23.5 ms                                                | 22.1 ms: 1.06x faster                                      |
| chaos                    | 67.5 ms                                                | 63.6 ms: 1.06x faster                                      |
| richards_super           | 51.9 ms                                                | 48.9 ms: 1.06x faster                                      |
| unpickle_pure_python     | 230 us                                                 | 217 us: 1.06x faster                                       |
| hexiom                   | 6.54 ms                                                | 6.19 ms: 1.06x faster                                      |
| unpickle                 | 15.8 us                                                | 15.0 us: 1.05x faster                                      |
| pyflate                  | 471 ms                                                 | 448 ms: 1.05x faster                                       |
| telco                    | 7.18 ms                                                | 6.83 ms: 1.05x faster                                      |
| logging_silent           | 108 ns                                                 | 103 ns: 1.05x faster                                       |
| scimark_monte_carlo      | 74.6 ms                                                | 71.3 ms: 1.05x faster                                      |
| nqueens                  | 86.2 ms                                                | 82.6 ms: 1.04x faster                                      |
| deepcopy_memo            | 39.7 us                                                | 38.1 us: 1.04x faster                                      |
| raytrace                 | 308 ms                                                 | 296 ms: 1.04x faster                                       |
| pprint_safe_repr         | 765 ms                                                 | 735 ms: 1.04x faster                                       |
| sqlite_synth             | 2.83 us                                                | 2.73 us: 1.04x faster                                      |
| pickle_pure_python       | 326 us                                                 | 314 us: 1.04x faster                                       |
| float                    | 83.3 ms                                                | 80.3 ms: 1.04x faster                                      |
| xml_etree_process        | 61.2 ms                                                | 59.1 ms: 1.04x faster                                      |
| meteor_contest           | 110 ms                                                 | 106 ms: 1.04x faster                                       |
| typing_runtime_protocols | 153 us                                                 | 148 us: 1.04x faster                                       |
| xml_etree_generate       | 88.7 ms                                                | 85.6 ms: 1.04x faster                                      |
| go                       | 140 ms                                                 | 136 ms: 1.03x faster                                       |
| regex_dna                | 209 ms                                                 | 202 ms: 1.03x faster                                       |
| fannkuch                 | 410 ms                                                 | 398 ms: 1.03x faster                                       |
| unpickle_list            | 5.04 us                                                | 4.90 us: 1.03x faster                                      |
| pprint_pformat           | 1.55 sec                                               | 1.51 sec: 1.03x faster                                     |
| pickle                   | 11.2 us                                                | 10.9 us: 1.03x faster                                      |
| nbody                    | 92.2 ms                                                | 89.7 ms: 1.03x faster                                      |
| generators               | 32.5 ms                                                | 31.6 ms: 1.03x faster                                      |
| sqlglot_normalize        | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| tomli_loads              | 2.30 sec                                               | 2.24 sec: 1.03x faster                                     |
| python_startup           | 9.53 ms                                                | 9.30 ms: 1.03x faster                                      |
| regex_compile            | 148 ms                                                 | 145 ms: 1.02x faster                                       |
| logging_simple           | 6.38 us                                                | 6.24 us: 1.02x faster                                      |
| python_startup_no_site   | 6.92 ms                                                | 6.76 ms: 1.02x faster                                      |
| async_tree_cpu_io_mixed  | 724 ms                                                 | 708 ms: 1.02x faster                                       |
| async_generators         | 459 ms                                                 | 450 ms: 1.02x faster                                       |
| 2to3                     | 274 ms                                                 | 269 ms: 1.02x faster                                       |
| logging_format           | 7.10 us                                                | 6.96 us: 1.02x faster                                      |
| xml_etree_parse          | 159 ms                                                 | 156 ms: 1.02x faster                                       |
| bench_thread_pool        | 845 us                                                 | 829 us: 1.02x faster                                       |
| async_tree_memoization   | 580 ms                                                 | 570 ms: 1.02x faster                                       |
| async_tree_none          | 475 ms                                                 | 468 ms: 1.02x faster                                       |
| xml_etree_iterparse      | 106 ms                                                 | 104 ms: 1.01x faster                                       |
| tornado_http             | 101 ms                                                 | 99.3 ms: 1.01x faster                                      |
| deepcopy_reduce          | 3.23 us                                                | 3.19 us: 1.01x faster                                      |
| sqlglot_optimize         | 54.8 ms                                                | 54.2 ms: 1.01x faster                                      |
| docutils                 | 2.75 sec                                               | 2.72 sec: 1.01x faster                                     |
| sqlalchemy_declarative   | 147 ms                                                 | 145 ms: 1.01x faster                                       |
| deepcopy                 | 363 us                                                 | 359 us: 1.01x faster                                       |
| async_tree_io            | 1.16 sec                                               | 1.15 sec: 1.01x faster                                     |
| gc_traversal             | 4.28 ms                                                | 4.25 ms: 1.01x faster                                      |
| mdp                      | 2.57 sec                                               | 2.55 sec: 1.01x faster                                     |
| dulwich_log              | 68.7 ms                                                | 68.4 ms: 1.00x faster                                      |
| asyncio_tcp_ssl          | 1.78 sec                                               | 1.80 sec: 1.01x slower                                     |
| asyncio_tcp              | 506 ms                                                 | 511 ms: 1.01x slower                                       |
| regex_v8                 | 22.7 ms                                                | 22.9 ms: 1.01x slower                                      |
| pickle_list              | 4.67 us                                                | 4.75 us: 1.02x slower                                      |
| create_gc_cycles         | 1.45 ms                                                | 1.52 ms: 1.05x slower                                      |
| pidigits                 | 187 ms                                                 | 197 ms: 1.05x slower                                       |
| regex_effbot             | 3.57 ms                                                | 3.83 ms: 1.07x slower                                      |
| coverage                 | 75.1 ms                                                | 93.8 ms: 1.25x slower                                      |
| mypy2                    | 351 ms                                                 | 459 ms: 1.31x slower                                       |
| dask                     | 369 ms                                                 | 536 ms: 1.45x slower                                       |
| Geometric mean           | (ref)                                                  | 1.02x faster                                               |

Benchmark hidden because not significant (7): pathlib, sqlglot_transpile, comprehensions, bench_mp_pool, sqlglot_parse, pycparser, sqlalchemy_imperative
Ignored benchmarks (13) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
