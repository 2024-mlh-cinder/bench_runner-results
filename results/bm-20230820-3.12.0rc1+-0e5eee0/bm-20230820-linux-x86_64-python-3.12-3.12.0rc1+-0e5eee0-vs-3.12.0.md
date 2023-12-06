
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 0e5eee0
- commit date: 2023-08-20
- overall geometric mean: 1.01x slower
- HPT reliability: 99.97%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-linux-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 269 ms: 1.00x slower                                    |
| docutils       | 2.70 sec                                               | 2.73 sec: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-linux-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| nbody          | 88.8 ms                                                | 88.0 ms: 1.01x faster                                   |
| pidigits       | 187 ms                                                 | 200 ms: 1.07x slower                                    |
| Geometric mean | (ref)                                                  | 1.02x slower                                            |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-linux-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 203 ms: 1.03x faster                                    |
| regex_compile  | 144 ms                                                 | 146 ms: 1.02x slower                                    |
| regex_v8       | 22.3 ms                                                | 22.8 ms: 1.02x slower                                   |
| regex_effbot   | 3.55 ms                                                | 3.70 ms: 1.04x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-linux-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|---------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_dict         | 31.6 us                                                | 30.2 us: 1.05x faster                                   |
| pickle              | 10.6 us                                                | 10.3 us: 1.03x faster                                   |
| json_dumps          | 9.85 ms                                                | 9.66 ms: 1.02x faster                                   |
| xml_etree_iterparse | 104 ms                                                 | 103 ms: 1.01x faster                                    |
| xml_etree_generate  | 84.8 ms                                                | 85.1 ms: 1.00x slower                                   |
| pickle_pure_python  | 309 us                                                 | 312 us: 1.01x slower                                    |
| xml_etree_process   | 58.6 ms                                                | 59.2 ms: 1.01x slower                                   |
| unpickle_list       | 4.95 us                                                | 5.05 us: 1.02x slower                                   |
| Geometric mean      | (ref)                                                  | 1.00x faster                                            |

Benchmark hidden because not significant (6): json_loads, pickle_list, tomli_loads, xml_etree_parse, unpickle_pure_python, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-linux-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.77 ms: 1.02x faster                                   |
| python_startup         | 9.47 ms                                                | 9.31 ms: 1.02x faster                                   |
| Geometric mean         | (ref)                                                  | 1.02x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-linux-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230820-linux-x86_64-python-3.12-3.12.0rc1+-0e5eee0 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_dict              | 31.6 us                                                | 30.2 us: 1.05x faster                                   |
| pickle                   | 10.6 us                                                | 10.3 us: 1.03x faster                                   |
| generators               | 31.1 ms                                                | 30.2 ms: 1.03x faster                                   |
| scimark_lu               | 114 ms                                                 | 111 ms: 1.03x faster                                    |
| regex_dna                | 209 ms                                                 | 203 ms: 1.03x faster                                    |
| python_startup_no_site   | 6.90 ms                                                | 6.77 ms: 1.02x faster                                   |
| json_dumps               | 9.85 ms                                                | 9.66 ms: 1.02x faster                                   |
| asyncio_tcp              | 526 ms                                                 | 516 ms: 1.02x faster                                    |
| python_startup           | 9.47 ms                                                | 9.31 ms: 1.02x faster                                   |
| deepcopy_reduce          | 3.14 us                                                | 3.09 us: 1.02x faster                                   |
| pathlib                  | 18.5 ms                                                | 18.2 ms: 1.02x faster                                   |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                   |
| nbody                    | 88.8 ms                                                | 88.0 ms: 1.01x faster                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                   |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                    |
| typing_runtime_protocols | 146 us                                                 | 145 us: 1.01x faster                                    |
| telco                    | 6.87 ms                                                | 6.84 ms: 1.00x faster                                   |
| deepcopy                 | 355 us                                                 | 354 us: 1.00x faster                                    |
| deepcopy_memo            | 37.4 us                                                | 37.5 us: 1.00x slower                                   |
| xml_etree_generate       | 84.8 ms                                                | 85.1 ms: 1.00x slower                                   |
| 2to3                     | 268 ms                                                 | 269 ms: 1.00x slower                                    |
| pprint_safe_repr         | 735 ms                                                 | 738 ms: 1.00x slower                                    |
| go                       | 136 ms                                                 | 136 ms: 1.00x slower                                    |
| bench_thread_pool        | 827 us                                                 | 832 us: 1.01x slower                                    |
| dulwich_log              | 67.9 ms                                                | 68.3 ms: 1.01x slower                                   |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                  |
| async_tree_io            | 1.16 sec                                               | 1.17 sec: 1.01x slower                                  |
| coverage                 | 94.2 ms                                                | 94.9 ms: 1.01x slower                                   |
| logging_format           | 6.90 us                                                | 6.96 us: 1.01x slower                                   |
| pickle_pure_python       | 309 us                                                 | 312 us: 1.01x slower                                    |
| sqlglot_parse            | 1.32 ms                                                | 1.33 ms: 1.01x slower                                   |
| docutils                 | 2.70 sec                                               | 2.73 sec: 1.01x slower                                  |
| spectral_norm            | 106 ms                                                 | 107 ms: 1.01x slower                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 71.8 ms: 1.01x slower                                   |
| chaos                    | 63.5 ms                                                | 64.3 ms: 1.01x slower                                   |
| xml_etree_process        | 58.6 ms                                                | 59.2 ms: 1.01x slower                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.66 ms: 1.01x slower                                   |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                   |
| comprehensions           | 20.4 us                                                | 20.7 us: 1.01x slower                                   |
| deltablue                | 3.52 ms                                                | 3.56 ms: 1.01x slower                                   |
| logging_simple           | 6.18 us                                                | 6.26 us: 1.01x slower                                   |
| sqlglot_optimize         | 53.3 ms                                                | 54.0 ms: 1.01x slower                                   |
| crypto_pyaes             | 77.2 ms                                                | 78.5 ms: 1.02x slower                                   |
| regex_compile            | 144 ms                                                 | 146 ms: 1.02x slower                                    |
| fannkuch                 | 387 ms                                                 | 395 ms: 1.02x slower                                    |
| unpickle_list            | 4.95 us                                                | 5.05 us: 1.02x slower                                   |
| regex_v8                 | 22.3 ms                                                | 22.8 ms: 1.02x slower                                   |
| richards                 | 43.2 ms                                                | 44.1 ms: 1.02x slower                                   |
| hexiom                   | 6.12 ms                                                | 6.28 ms: 1.03x slower                                   |
| async_generators         | 440 ms                                                 | 452 ms: 1.03x slower                                    |
| sqlglot_normalize        | 107 ms                                                 | 110 ms: 1.03x slower                                    |
| raytrace                 | 294 ms                                                 | 302 ms: 1.03x slower                                    |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.90 ms: 1.03x slower                                   |
| mdp                      | 2.57 sec                                               | 2.66 sec: 1.03x slower                                  |
| richards_super           | 49.0 ms                                                | 50.8 ms: 1.04x slower                                   |
| regex_effbot             | 3.55 ms                                                | 3.70 ms: 1.04x slower                                   |
| logging_silent           | 99.1 ns                                                | 104 ns: 1.05x slower                                    |
| pidigits                 | 187 ms                                                 | 200 ms: 1.07x slower                                    |
| gc_traversal             | 3.84 ms                                                | 4.46 ms: 1.16x slower                                   |
| unpack_sequence          | 44.8 ns                                                | 53.7 ns: 1.20x slower                                   |
| dask                     | 365 ms                                                 | 538 ms: 1.48x slower                                    |
| Geometric mean           | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (24): coroutines, sqlalchemy_imperative, json_loads, scimark_fft, pyflate, async_tree_cpu_io_mixed, tornado_http, meteor_contest, pickle_list, tomli_loads, bench_mp_pool, asyncio_tcp_ssl, float, pprint_pformat, xml_etree_parse, async_tree_memoization, mypy2, nqueens, unpickle_pure_python, sqlalchemy_declarative, async_tree_none, json, scimark_sor, unpickle


# HPT report

- Reliability score: 99.97% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
