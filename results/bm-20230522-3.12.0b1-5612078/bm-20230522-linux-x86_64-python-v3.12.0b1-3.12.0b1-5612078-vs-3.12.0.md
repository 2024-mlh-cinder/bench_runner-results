
# Results vs. 3.12.0

- fork: python
- ref: v3.12.0b1
- machine: linux-x86_64
- commit hash: 5612078
- commit date: 2023-05-22
- overall geometric mean: 1.02x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 268 ms: 1.02x faster                                       |
| docutils       | 2.75 sec                                               | 2.71 sec: 1.02x faster                                     |
| tornado_http   | 101 ms                                                 | 99.2 ms: 1.01x faster                                      |
| Geometric mean | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 708 ms: 1.02x faster                                       |
| async_tree_none         | 475 ms                                                 | 469 ms: 1.01x faster                                       |
| async_tree_memoization  | 580 ms                                                 | 572 ms: 1.01x faster                                       |
| Geometric mean          | (ref)                                                  | 1.01x faster                                               |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 92.2 ms                                                | 88.9 ms: 1.04x faster                                      |
| float          | 83.3 ms                                                | 80.7 ms: 1.03x faster                                      |
| pidigits       | 187 ms                                                 | 196 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                  | 1.01x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_v8       | 22.7 ms                                                | 21.8 ms: 1.04x faster                                      |
| regex_compile  | 148 ms                                                 | 144 ms: 1.03x faster                                       |
| regex_effbot   | 3.57 ms                                                | 3.54 ms: 1.01x faster                                      |
| Geometric mean | (ref)                                                  | 1.02x faster                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| json_loads           | 28.4 us                                                | 25.1 us: 1.13x faster                                      |
| json_dumps           | 10.6 ms                                                | 9.76 ms: 1.08x faster                                      |
| unpickle_pure_python | 230 us                                                 | 216 us: 1.06x faster                                       |
| pickle               | 11.2 us                                                | 10.6 us: 1.06x faster                                      |
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                      |
| tomli_loads          | 2.30 sec                                               | 2.18 sec: 1.05x faster                                     |
| pickle_pure_python   | 326 us                                                 | 312 us: 1.05x faster                                       |
| xml_etree_parse      | 159 ms                                                 | 153 ms: 1.04x faster                                       |
| xml_etree_process    | 61.2 ms                                                | 59.0 ms: 1.04x faster                                      |
| xml_etree_generate   | 88.7 ms                                                | 85.6 ms: 1.04x faster                                      |
| xml_etree_iterparse  | 106 ms                                                 | 103 ms: 1.02x faster                                       |
| pickle_dict          | 33.5 us                                                | 33.3 us: 1.01x faster                                      |
| pickle_list          | 4.67 us                                                | 4.73 us: 1.01x slower                                      |
| unpickle_list        | 5.04 us                                                | 5.17 us: 1.02x slower                                      |
| Geometric mean       | (ref)                                                  | 1.04x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 9.34 ms: 1.02x faster                                      |
| python_startup_no_site | 6.92 ms                                                | 6.78 ms: 1.02x faster                                      |
| Geometric mean         | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 11.5 ms                                                | 10.8 ms: 1.06x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| gc_traversal             | 4.28 ms                                                | 3.67 ms: 1.17x faster                                      |
| unpack_sequence          | 54.2 ns                                                | 47.3 ns: 1.14x faster                                      |
| json_loads               | 28.4 us                                                | 25.1 us: 1.13x faster                                      |
| typing_runtime_protocols | 153 us                                                 | 140 us: 1.09x faster                                       |
| json                     | 5.22 ms                                                | 4.77 ms: 1.09x faster                                      |
| json_dumps               | 10.6 ms                                                | 9.76 ms: 1.08x faster                                      |
| deltablue                | 3.71 ms                                                | 3.44 ms: 1.08x faster                                      |
| fannkuch                 | 410 ms                                                 | 382 ms: 1.07x faster                                       |
| logging_silent           | 108 ns                                                 | 100 ns: 1.07x faster                                       |
| crypto_pyaes             | 83.6 ms                                                | 77.9 ms: 1.07x faster                                      |
| coroutines               | 23.5 ms                                                | 21.9 ms: 1.07x faster                                      |
| scimark_fft              | 381 ms                                                 | 356 ms: 1.07x faster                                       |
| hexiom                   | 6.54 ms                                                | 6.12 ms: 1.07x faster                                      |
| scimark_lu               | 120 ms                                                 | 113 ms: 1.06x faster                                       |
| unpickle_pure_python     | 230 us                                                 | 216 us: 1.06x faster                                       |
| pyflate                  | 471 ms                                                 | 443 ms: 1.06x faster                                       |
| pickle                   | 11.2 us                                                | 10.6 us: 1.06x faster                                      |
| spectral_norm            | 115 ms                                                 | 108 ms: 1.06x faster                                       |
| mako                     | 11.5 ms                                                | 10.8 ms: 1.06x faster                                      |
| nqueens                  | 86.2 ms                                                | 81.4 ms: 1.06x faster                                      |
| unpickle                 | 15.8 us                                                | 14.9 us: 1.06x faster                                      |
| deepcopy_memo            | 39.7 us                                                | 37.6 us: 1.06x faster                                      |
| richards                 | 46.0 ms                                                | 43.6 ms: 1.06x faster                                      |
| scimark_sparse_mat_mult  | 5.33 ms                                                | 5.05 ms: 1.06x faster                                      |
| tomli_loads              | 2.30 sec                                               | 2.18 sec: 1.05x faster                                     |
| scimark_sor              | 129 ms                                                 | 123 ms: 1.05x faster                                       |
| telco                    | 7.18 ms                                                | 6.84 ms: 1.05x faster                                      |
| pickle_pure_python       | 326 us                                                 | 312 us: 1.05x faster                                       |
| chaos                    | 67.5 ms                                                | 64.6 ms: 1.05x faster                                      |
| pprint_safe_repr         | 765 ms                                                 | 733 ms: 1.04x faster                                       |
| richards_super           | 51.9 ms                                                | 49.8 ms: 1.04x faster                                      |
| xml_etree_parse          | 159 ms                                                 | 153 ms: 1.04x faster                                       |
| meteor_contest           | 110 ms                                                 | 105 ms: 1.04x faster                                       |
| sqlite_synth             | 2.83 us                                                | 2.72 us: 1.04x faster                                      |
| xml_etree_process        | 61.2 ms                                                | 59.0 ms: 1.04x faster                                      |
| regex_v8                 | 22.7 ms                                                | 21.8 ms: 1.04x faster                                      |
| pprint_pformat           | 1.55 sec                                               | 1.50 sec: 1.04x faster                                     |
| nbody                    | 92.2 ms                                                | 88.9 ms: 1.04x faster                                      |
| xml_etree_generate       | 88.7 ms                                                | 85.6 ms: 1.04x faster                                      |
| go                       | 140 ms                                                 | 136 ms: 1.03x faster                                       |
| generators               | 32.5 ms                                                | 31.4 ms: 1.03x faster                                      |
| float                    | 83.3 ms                                                | 80.7 ms: 1.03x faster                                      |
| raytrace                 | 308 ms                                                 | 298 ms: 1.03x faster                                       |
| regex_compile            | 148 ms                                                 | 144 ms: 1.03x faster                                       |
| pathlib                  | 18.9 ms                                                | 18.3 ms: 1.03x faster                                      |
| sqlglot_normalize        | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| scimark_monte_carlo      | 74.6 ms                                                | 72.7 ms: 1.03x faster                                      |
| 2to3                     | 274 ms                                                 | 268 ms: 1.02x faster                                       |
| xml_etree_iterparse      | 106 ms                                                 | 103 ms: 1.02x faster                                       |
| async_generators         | 459 ms                                                 | 449 ms: 1.02x faster                                       |
| async_tree_cpu_io_mixed  | 724 ms                                                 | 708 ms: 1.02x faster                                       |
| bench_thread_pool        | 845 us                                                 | 827 us: 1.02x faster                                       |
| python_startup           | 9.53 ms                                                | 9.34 ms: 1.02x faster                                      |
| sqlglot_transpile        | 1.68 ms                                                | 1.64 ms: 1.02x faster                                      |
| python_startup_no_site   | 6.92 ms                                                | 6.78 ms: 1.02x faster                                      |
| comprehensions           | 20.9 us                                                | 20.6 us: 1.02x faster                                      |
| sqlglot_parse            | 1.35 ms                                                | 1.33 ms: 1.02x faster                                      |
| docutils                 | 2.75 sec                                               | 2.71 sec: 1.02x faster                                     |
| dulwich_log              | 68.7 ms                                                | 67.7 ms: 1.02x faster                                      |
| deepcopy_reduce          | 3.23 us                                                | 3.18 us: 1.01x faster                                      |
| tornado_http             | 101 ms                                                 | 99.2 ms: 1.01x faster                                      |
| async_tree_none          | 475 ms                                                 | 469 ms: 1.01x faster                                       |
| sqlglot_optimize         | 54.8 ms                                                | 54.1 ms: 1.01x faster                                      |
| async_tree_memoization   | 580 ms                                                 | 572 ms: 1.01x faster                                       |
| sqlalchemy_declarative   | 147 ms                                                 | 145 ms: 1.01x faster                                       |
| regex_effbot             | 3.57 ms                                                | 3.54 ms: 1.01x faster                                      |
| logging_simple           | 6.38 us                                                | 6.33 us: 1.01x faster                                      |
| pickle_dict              | 33.5 us                                                | 33.3 us: 1.01x faster                                      |
| asyncio_tcp_ssl          | 1.78 sec                                               | 1.80 sec: 1.01x slower                                     |
| pickle_list              | 4.67 us                                                | 4.73 us: 1.01x slower                                      |
| asyncio_tcp              | 506 ms                                                 | 513 ms: 1.01x slower                                       |
| pycparser                | 1.17 sec                                               | 1.19 sec: 1.02x slower                                     |
| unpickle_list            | 5.04 us                                                | 5.17 us: 1.02x slower                                      |
| create_gc_cycles         | 1.45 ms                                                | 1.50 ms: 1.03x slower                                      |
| mdp                      | 2.57 sec                                               | 2.68 sec: 1.04x slower                                     |
| pidigits                 | 187 ms                                                 | 196 ms: 1.05x slower                                       |
| coverage                 | 75.1 ms                                                | 96.8 ms: 1.29x slower                                      |
| mypy2                    | 351 ms                                                 | 458 ms: 1.31x slower                                       |
| dask                     | 369 ms                                                 | 535 ms: 1.45x slower                                       |
| Geometric mean           | (ref)                                                  | 1.02x faster                                               |

Benchmark hidden because not significant (6): deepcopy, regex_dna, async_tree_io, logging_format, bench_mp_pool, sqlalchemy_imperative
Ignored benchmarks (13) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sympy_expand, sympy_integrate, sympy_str, sympy_sum


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
