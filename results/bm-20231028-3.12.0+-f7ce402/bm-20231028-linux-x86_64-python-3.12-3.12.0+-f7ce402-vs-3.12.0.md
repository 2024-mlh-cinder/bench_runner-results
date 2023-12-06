
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.00x slower
- HPT reliability: 86.28%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 274 ms                                                 | 275 ms: 1.00x slower                                 |
| chameleon      | 7.41 ms                                                | 7.47 ms: 1.01x slower                                |
| docutils       | 2.75 sec                                               | 2.73 sec: 1.01x faster                               |
| Geometric mean | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_io    | 1.16 sec                                               | 1.17 sec: 1.00x slower                               |
| async_tree_io_tg | 1.19 sec                                               | 1.19 sec: 1.00x slower                               |
| Geometric mean   | (ref)                                                  | 1.00x slower                                         |

Benchmark hidden because not significant (6): async_tree_none, async_tree_memoization_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg, async_tree_none_tg, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                 |
| float          | 83.3 ms                                                | 84.6 ms: 1.02x slower                                |
| nbody          | 92.2 ms                                                | 97.8 ms: 1.06x slower                                |
| Geometric mean | (ref)                                                  | 1.03x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 147 ms: 1.01x faster                                 |
| regex_dna      | 209 ms                                                 | 209 ms: 1.00x slower                                 |
| regex_effbot   | 3.57 ms                                                | 3.58 ms: 1.00x slower                                |
| regex_v8       | 22.7 ms                                                | 23.2 ms: 1.02x slower                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_pure_python   | 326 us                                                 | 323 us: 1.01x faster                                 |
| json_loads           | 28.4 us                                                | 28.2 us: 1.01x faster                                |
| unpickle_pure_python | 230 us                                                 | 229 us: 1.00x faster                                 |
| xml_etree_process    | 61.2 ms                                                | 61.0 ms: 1.00x faster                                |
| xml_etree_generate   | 88.7 ms                                                | 88.5 ms: 1.00x faster                                |
| xml_etree_iterparse  | 106 ms                                                 | 106 ms: 1.01x slower                                 |
| pickle               | 11.2 us                                                | 11.4 us: 1.01x slower                                |
| unpickle_list        | 5.04 us                                                | 5.12 us: 1.01x slower                                |
| xml_etree_parse      | 159 ms                                                 | 162 ms: 1.02x slower                                 |
| tomli_loads          | 2.30 sec                                               | 2.35 sec: 1.02x slower                               |
| unpickle             | 15.8 us                                                | 16.3 us: 1.04x slower                                |
| pickle_list          | 4.67 us                                                | 4.94 us: 1.06x slower                                |
| Geometric mean       | (ref)                                                  | 1.01x slower                                         |

Benchmark hidden because not significant (2): json_dumps, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.97 ms: 1.01x slower                                |
| python_startup         | 9.53 ms                                                | 9.62 ms: 1.01x slower                                |
| Geometric mean         | (ref)                                                  | 1.01x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| django_template | 35.0 ms                                                | 34.7 ms: 1.01x faster                                |
| mako            | 11.5 ms                                                | 11.4 ms: 1.01x faster                                |
| Geometric mean  | (ref)                                                  | 1.01x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| unpack_sequence          | 54.2 ns                                                | 48.5 ns: 1.12x faster                                |
| generators               | 32.5 ms                                                | 31.1 ms: 1.04x faster                                |
| pyflate                  | 471 ms                                                 | 453 ms: 1.04x faster                                 |
| nqueens                  | 86.2 ms                                                | 83.8 ms: 1.03x faster                                |
| coverage                 | 75.1 ms                                                | 73.3 ms: 1.03x faster                                |
| crypto_pyaes             | 83.6 ms                                                | 81.7 ms: 1.02x faster                                |
| deltablue                | 3.71 ms                                                | 3.64 ms: 1.02x faster                                |
| richards                 | 46.0 ms                                                | 45.4 ms: 1.01x faster                                |
| hexiom                   | 6.54 ms                                                | 6.46 ms: 1.01x faster                                |
| richards_super           | 51.9 ms                                                | 51.3 ms: 1.01x faster                                |
| scimark_sparse_mat_mult  | 5.33 ms                                                | 5.27 ms: 1.01x faster                                |
| chaos                    | 67.5 ms                                                | 66.8 ms: 1.01x faster                                |
| logging_silent           | 108 ns                                                 | 106 ns: 1.01x faster                                 |
| sqlglot_normalize        | 112 ms                                                 | 110 ms: 1.01x faster                                 |
| django_template          | 35.0 ms                                                | 34.7 ms: 1.01x faster                                |
| docutils                 | 2.75 sec                                               | 2.73 sec: 1.01x faster                               |
| regex_compile            | 148 ms                                                 | 147 ms: 1.01x faster                                 |
| pickle_pure_python       | 326 us                                                 | 323 us: 1.01x faster                                 |
| meteor_contest           | 110 ms                                                 | 109 ms: 1.01x faster                                 |
| mako                     | 11.5 ms                                                | 11.4 ms: 1.01x faster                                |
| scimark_monte_carlo      | 74.6 ms                                                | 74.1 ms: 1.01x faster                                |
| asyncio_tcp              | 506 ms                                                 | 503 ms: 1.01x faster                                 |
| json_loads               | 28.4 us                                                | 28.2 us: 1.01x faster                                |
| dulwich_log              | 68.7 ms                                                | 68.4 ms: 1.01x faster                                |
| bench_thread_pool        | 845 us                                                 | 841 us: 1.00x faster                                 |
| aiohttp                  | 1.15 ms                                                | 1.15 ms: 1.00x faster                                |
| unpickle_pure_python     | 230 us                                                 | 229 us: 1.00x faster                                 |
| xml_etree_process        | 61.2 ms                                                | 61.0 ms: 1.00x faster                                |
| xml_etree_generate       | 88.7 ms                                                | 88.5 ms: 1.00x faster                                |
| fannkuch                 | 410 ms                                                 | 409 ms: 1.00x faster                                 |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                 |
| gc_traversal             | 4.28 ms                                                | 4.28 ms: 1.00x slower                                |
| regex_dna                | 209 ms                                                 | 209 ms: 1.00x slower                                 |
| 2to3                     | 274 ms                                                 | 275 ms: 1.00x slower                                 |
| regex_effbot             | 3.57 ms                                                | 3.58 ms: 1.00x slower                                |
| async_tree_io            | 1.16 sec                                               | 1.17 sec: 1.00x slower                               |
| pprint_pformat           | 1.55 sec                                               | 1.56 sec: 1.00x slower                               |
| async_tree_io_tg         | 1.19 sec                                               | 1.19 sec: 1.00x slower                               |
| async_generators         | 459 ms                                                 | 461 ms: 1.00x slower                                 |
| pprint_safe_repr         | 765 ms                                                 | 769 ms: 1.01x slower                                 |
| asyncio_tcp_ssl          | 1.78 sec                                               | 1.79 sec: 1.01x slower                               |
| xml_etree_iterparse      | 106 ms                                                 | 106 ms: 1.01x slower                                 |
| python_startup_no_site   | 6.92 ms                                                | 6.97 ms: 1.01x slower                                |
| create_gc_cycles         | 1.45 ms                                                | 1.46 ms: 1.01x slower                                |
| scimark_fft              | 381 ms                                                 | 384 ms: 1.01x slower                                 |
| chameleon                | 7.41 ms                                                | 7.47 ms: 1.01x slower                                |
| python_startup           | 9.53 ms                                                | 9.62 ms: 1.01x slower                                |
| deepcopy_reduce          | 3.23 us                                                | 3.26 us: 1.01x slower                                |
| sympy_expand             | 476 ms                                                 | 481 ms: 1.01x slower                                 |
| sqlite_synth             | 2.83 us                                                | 2.86 us: 1.01x slower                                |
| sympy_str                | 296 ms                                                 | 299 ms: 1.01x slower                                 |
| pycparser                | 1.17 sec                                               | 1.18 sec: 1.01x slower                               |
| deepcopy_memo            | 39.7 us                                                | 40.2 us: 1.01x slower                                |
| scimark_sor              | 129 ms                                                 | 131 ms: 1.01x slower                                 |
| sqlglot_parse            | 1.35 ms                                                | 1.37 ms: 1.01x slower                                |
| sqlglot_transpile        | 1.68 ms                                                | 1.70 ms: 1.01x slower                                |
| pickle                   | 11.2 us                                                | 11.4 us: 1.01x slower                                |
| sqlalchemy_imperative    | 18.5 ms                                                | 18.8 ms: 1.01x slower                                |
| unpickle_list            | 5.04 us                                                | 5.12 us: 1.01x slower                                |
| xml_etree_parse          | 159 ms                                                 | 162 ms: 1.02x slower                                 |
| scimark_lu               | 120 ms                                                 | 122 ms: 1.02x slower                                 |
| float                    | 83.3 ms                                                | 84.6 ms: 1.02x slower                                |
| logging_simple           | 6.38 us                                                | 6.49 us: 1.02x slower                                |
| logging_format           | 7.10 us                                                | 7.21 us: 1.02x slower                                |
| typing_runtime_protocols | 153 us                                                 | 156 us: 1.02x slower                                 |
| deepcopy                 | 363 us                                                 | 370 us: 1.02x slower                                 |
| regex_v8                 | 22.7 ms                                                | 23.2 ms: 1.02x slower                                |
| spectral_norm            | 115 ms                                                 | 117 ms: 1.02x slower                                 |
| tomli_loads              | 2.30 sec                                               | 2.35 sec: 1.02x slower                               |
| comprehensions           | 20.9 us                                                | 21.6 us: 1.03x slower                                |
| unpickle                 | 15.8 us                                                | 16.3 us: 1.04x slower                                |
| pickle_list              | 4.67 us                                                | 4.94 us: 1.06x slower                                |
| mdp                      | 2.57 sec                                               | 2.72 sec: 1.06x slower                               |
| nbody                    | 92.2 ms                                                | 97.8 ms: 1.06x slower                                |
| mypy2                    | 351 ms                                                 | 467 ms: 1.33x slower                                 |
| Geometric mean           | (ref)                                                  | 1.00x slower                                         |

Benchmark hidden because not significant (23): tornado_http, json_dumps, gunicorn, pathlib, async_tree_none, go, sqlglot_optimize, asyncio_websockets, dask, raytrace, async_tree_memoization_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg, pickle_dict, sympy_sum, async_tree_none_tg, bench_mp_pool, telco, sympy_integrate, async_tree_cpu_io_mixed, coroutines, json, sqlalchemy_declarative


# HPT report

- Reliability score: 86.28% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
