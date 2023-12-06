
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.00x faster \*
- HPT reliability: 84.07%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 274 ms                                                 | 273 ms: 1.01x faster                                 |
| chameleon      | 7.41 ms                                                | 7.27 ms: 1.02x faster                                |
| docutils       | 2.75 sec                                               | 2.71 sec: 1.02x faster                               |
| tornado_http   | 101 ms                                                 | 99.2 ms: 1.01x faster                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|--------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_io_tg   | 1.19 sec                                               | 1.20 sec: 1.01x slower                               |
| async_tree_io      | 1.16 sec                                               | 1.17 sec: 1.01x slower                               |
| async_tree_none_tg | 447 ms                                                 | 451 ms: 1.01x slower                                 |
| Geometric mean     | (ref)                                                  | 1.00x slower                                         |

Benchmark hidden because not significant (5): async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| nbody          | 92.2 ms                                                | 90.3 ms: 1.02x faster                                |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x faster                                 |
| float          | 83.3 ms                                                | 84.1 ms: 1.01x slower                                |
| Geometric mean | (ref)                                                  | 1.00x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 146 ms: 1.01x faster                                 |
| regex_v8       | 22.7 ms                                                | 22.9 ms: 1.01x slower                                |
| regex_dna      | 209 ms                                                 | 213 ms: 1.02x slower                                 |
| regex_effbot   | 3.57 ms                                                | 3.87 ms: 1.08x slower                                |
| Geometric mean | (ref)                                                  | 1.03x slower                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 31.9 us: 1.05x faster                                |
| unpickle_pure_python | 230 us                                                 | 226 us: 1.01x faster                                 |
| pickle               | 11.2 us                                                | 11.1 us: 1.01x faster                                |
| pickle_pure_python   | 326 us                                                 | 323 us: 1.01x faster                                 |
| tomli_loads          | 2.30 sec                                               | 2.28 sec: 1.01x faster                               |
| xml_etree_generate   | 88.7 ms                                                | 89.6 ms: 1.01x slower                                |
| xml_etree_process    | 61.2 ms                                                | 61.9 ms: 1.01x slower                                |
| unpickle             | 15.8 us                                                | 16.1 us: 1.02x slower                                |
| unpickle_list        | 5.04 us                                                | 5.36 us: 1.06x slower                                |
| pickle_list          | 4.67 us                                                | 5.01 us: 1.07x slower                                |
| Geometric mean       | (ref)                                                  | 1.01x slower                                         |

Benchmark hidden because not significant (4): json_loads, xml_etree_iterparse, xml_etree_parse, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.88 ms: 1.01x faster                                |
| python_startup         | 9.53 ms                                                | 9.49 ms: 1.00x faster                                |
| Geometric mean         | (ref)                                                  | 1.01x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| django_template | 35.0 ms                                                | 34.5 ms: 1.02x faster                                |
| mako            | 11.5 ms                                                | 11.5 ms: 1.00x slower                                |
| Geometric mean  | (ref)                                                  | 1.01x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 153 us                                                 | 121 us: 1.27x faster                                 |
| gc_traversal             | 4.28 ms                                                | 3.78 ms: 1.13x faster                                |
| scimark_sparse_mat_mult  | 5.33 ms                                                | 5.04 ms: 1.06x faster                                |
| pickle_dict              | 33.5 us                                                | 31.9 us: 1.05x faster                                |
| nqueens                  | 86.2 ms                                                | 83.5 ms: 1.03x faster                                |
| scimark_fft              | 381 ms                                                 | 371 ms: 1.03x faster                                 |
| hexiom                   | 6.54 ms                                                | 6.38 ms: 1.03x faster                                |
| sympy_integrate          | 21.2 ms                                                | 20.7 ms: 1.02x faster                                |
| nbody                    | 92.2 ms                                                | 90.3 ms: 1.02x faster                                |
| chaos                    | 67.5 ms                                                | 66.2 ms: 1.02x faster                                |
| chameleon                | 7.41 ms                                                | 7.27 ms: 1.02x faster                                |
| comprehensions           | 20.9 us                                                | 20.6 us: 1.02x faster                                |
| docutils                 | 2.75 sec                                               | 2.71 sec: 1.02x faster                               |
| coroutines               | 23.5 ms                                                | 23.1 ms: 1.02x faster                                |
| async_generators         | 459 ms                                                 | 452 ms: 1.02x faster                                 |
| richards_super           | 51.9 ms                                                | 51.1 ms: 1.02x faster                                |
| django_template          | 35.0 ms                                                | 34.5 ms: 1.02x faster                                |
| sympy_sum                | 167 ms                                                 | 165 ms: 1.02x faster                                 |
| spectral_norm            | 115 ms                                                 | 113 ms: 1.02x faster                                 |
| richards                 | 46.0 ms                                                | 45.3 ms: 1.02x faster                                |
| unpickle_pure_python     | 230 us                                                 | 226 us: 1.01x faster                                 |
| tornado_http             | 101 ms                                                 | 99.2 ms: 1.01x faster                                |
| unpack_sequence          | 54.2 ns                                                | 53.4 ns: 1.01x faster                                |
| logging_silent           | 108 ns                                                 | 106 ns: 1.01x faster                                 |
| sqlglot_normalize        | 112 ms                                                 | 110 ms: 1.01x faster                                 |
| scimark_lu               | 120 ms                                                 | 119 ms: 1.01x faster                                 |
| dulwich_log              | 68.7 ms                                                | 67.9 ms: 1.01x faster                                |
| regex_compile            | 148 ms                                                 | 146 ms: 1.01x faster                                 |
| deltablue                | 3.71 ms                                                | 3.67 ms: 1.01x faster                                |
| pickle                   | 11.2 us                                                | 11.1 us: 1.01x faster                                |
| aiohttp                  | 1.15 ms                                                | 1.14 ms: 1.01x faster                                |
| pprint_safe_repr         | 765 ms                                                 | 757 ms: 1.01x faster                                 |
| pickle_pure_python       | 326 us                                                 | 323 us: 1.01x faster                                 |
| pprint_pformat           | 1.55 sec                                               | 1.54 sec: 1.01x faster                               |
| scimark_monte_carlo      | 74.6 ms                                                | 74.0 ms: 1.01x faster                                |
| tomli_loads              | 2.30 sec                                               | 2.28 sec: 1.01x faster                               |
| meteor_contest           | 110 ms                                                 | 109 ms: 1.01x faster                                 |
| raytrace                 | 308 ms                                                 | 306 ms: 1.01x faster                                 |
| python_startup_no_site   | 6.92 ms                                                | 6.88 ms: 1.01x faster                                |
| 2to3                     | 274 ms                                                 | 273 ms: 1.01x faster                                 |
| bench_thread_pool        | 845 us                                                 | 841 us: 1.01x faster                                 |
| python_startup           | 9.53 ms                                                | 9.49 ms: 1.00x faster                                |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x faster                                 |
| create_gc_cycles         | 1.45 ms                                                | 1.45 ms: 1.00x slower                                |
| mako                     | 11.5 ms                                                | 11.5 ms: 1.00x slower                                |
| asyncio_tcp              | 506 ms                                                 | 509 ms: 1.01x slower                                 |
| deepcopy                 | 363 us                                                 | 365 us: 1.01x slower                                 |
| async_tree_io_tg         | 1.19 sec                                               | 1.20 sec: 1.01x slower                               |
| json                     | 5.22 ms                                                | 5.26 ms: 1.01x slower                                |
| async_tree_io            | 1.16 sec                                               | 1.17 sec: 1.01x slower                               |
| mdp                      | 2.57 sec                                               | 2.59 sec: 1.01x slower                               |
| async_tree_none_tg       | 447 ms                                                 | 451 ms: 1.01x slower                                 |
| sqlglot_transpile        | 1.68 ms                                                | 1.69 ms: 1.01x slower                                |
| float                    | 83.3 ms                                                | 84.1 ms: 1.01x slower                                |
| xml_etree_generate       | 88.7 ms                                                | 89.6 ms: 1.01x slower                                |
| xml_etree_process        | 61.2 ms                                                | 61.9 ms: 1.01x slower                                |
| deepcopy_memo            | 39.7 us                                                | 40.2 us: 1.01x slower                                |
| generators               | 32.5 ms                                                | 32.8 ms: 1.01x slower                                |
| deepcopy_reduce          | 3.23 us                                                | 3.26 us: 1.01x slower                                |
| asyncio_tcp_ssl          | 1.78 sec                                               | 1.80 sec: 1.01x slower                               |
| regex_v8                 | 22.7 ms                                                | 22.9 ms: 1.01x slower                                |
| fannkuch                 | 410 ms                                                 | 416 ms: 1.01x slower                                 |
| sqlite_synth             | 2.83 us                                                | 2.87 us: 1.01x slower                                |
| sqlglot_parse            | 1.35 ms                                                | 1.37 ms: 1.02x slower                                |
| unpickle                 | 15.8 us                                                | 16.1 us: 1.02x slower                                |
| logging_format           | 7.10 us                                                | 7.26 us: 1.02x slower                                |
| regex_dna                | 209 ms                                                 | 213 ms: 1.02x slower                                 |
| logging_simple           | 6.38 us                                                | 6.56 us: 1.03x slower                                |
| pycparser                | 1.17 sec                                               | 1.21 sec: 1.03x slower                               |
| unpickle_list            | 5.04 us                                                | 5.36 us: 1.06x slower                                |
| pickle_list              | 4.67 us                                                | 5.01 us: 1.07x slower                                |
| regex_effbot             | 3.57 ms                                                | 3.87 ms: 1.08x slower                                |
| mypy2                    | 351 ms                                                 | 465 ms: 1.33x slower                                 |
| Geometric mean           | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (25): gunicorn, pyflate, asyncio_websockets, scimark_sor, pathlib, dask, telco, sqlalchemy_declarative, bench_mp_pool, sqlglot_optimize, go, json_loads, async_tree_memoization_tg, xml_etree_iterparse, async_tree_cpu_io_mixed_tg, async_tree_memoization, xml_etree_parse, sympy_str, crypto_pyaes, async_tree_cpu_io_mixed, async_tree_none, coverage, json_dumps, sympy_expand, sqlalchemy_imperative


# HPT report

- Reliability score: 84.07% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
