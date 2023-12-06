
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.01x slower
- HPT reliability: 99.84%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 268 ms                                                 | 268 ms: 1.00x slower                                    |
| tornado_http   | 99.6 ms                                                | 102 ms: 1.02x slower                                    |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| float          | 80.7 ms                                                | 81.2 ms: 1.01x slower                                   |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                    |
| nbody          | 88.8 ms                                                | 90.3 ms: 1.02x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_v8       | 22.3 ms                                                | 22.4 ms: 1.00x slower                                   |
| regex_effbot   | 3.55 ms                                                | 3.56 ms: 1.00x slower                                   |
| regex_dna      | 209 ms                                                 | 210 ms: 1.01x slower                                    |
| Geometric mean | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|---------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps          | 9.85 ms                                                | 9.64 ms: 1.02x faster                                   |
| unpickle            | 15.0 us                                                | 14.7 us: 1.02x faster                                   |
| json_loads          | 25.2 us                                                | 24.9 us: 1.01x faster                                   |
| xml_etree_iterparse | 104 ms                                                 | 103 ms: 1.01x faster                                    |
| xml_etree_generate  | 84.8 ms                                                | 85.2 ms: 1.00x slower                                   |
| xml_etree_process   | 58.6 ms                                                | 58.9 ms: 1.01x slower                                   |
| pickle_pure_python  | 309 us                                                 | 311 us: 1.01x slower                                    |
| pickle_list         | 4.62 us                                                | 4.66 us: 1.01x slower                                   |
| pickle              | 10.6 us                                                | 10.7 us: 1.01x slower                                   |
| unpickle_list       | 4.95 us                                                | 5.00 us: 1.01x slower                                   |
| tomli_loads         | 2.22 sec                                               | 2.25 sec: 1.01x slower                                  |
| pickle_dict         | 31.6 us                                                | 32.8 us: 1.04x slower                                   |
| Geometric mean      | (ref)                                                  | 1.00x slower                                            |

Benchmark hidden because not significant (2): unpickle_pure_python, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.77 ms: 1.02x faster                                   |
| python_startup         | 9.47 ms                                                | 9.31 ms: 1.02x faster                                   |
| Geometric mean         | (ref)                                                  | 1.02x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 504 ms: 1.04x faster                                    |
| generators               | 31.1 ms                                                | 30.3 ms: 1.03x faster                                   |
| json_dumps               | 9.85 ms                                                | 9.64 ms: 1.02x faster                                   |
| coroutines               | 22.4 ms                                                | 22.0 ms: 1.02x faster                                   |
| python_startup_no_site   | 6.90 ms                                                | 6.77 ms: 1.02x faster                                   |
| sqlite_synth             | 2.76 us                                                | 2.71 us: 1.02x faster                                   |
| unpickle                 | 15.0 us                                                | 14.7 us: 1.02x faster                                   |
| python_startup           | 9.47 ms                                                | 9.31 ms: 1.02x faster                                   |
| typing_runtime_protocols | 146 us                                                 | 144 us: 1.02x faster                                    |
| pathlib                  | 18.5 ms                                                | 18.2 ms: 1.01x faster                                   |
| spectral_norm            | 106 ms                                                 | 105 ms: 1.01x faster                                    |
| telco                    | 6.87 ms                                                | 6.79 ms: 1.01x faster                                   |
| json_loads               | 25.2 us                                                | 24.9 us: 1.01x faster                                   |
| scimark_lu               | 114 ms                                                 | 113 ms: 1.01x faster                                    |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                    |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                   |
| pprint_pformat           | 1.50 sec                                               | 1.49 sec: 1.00x faster                                  |
| dulwich_log              | 67.9 ms                                                | 67.6 ms: 1.00x faster                                   |
| 2to3                     | 268 ms                                                 | 268 ms: 1.00x slower                                    |
| regex_v8                 | 22.3 ms                                                | 22.4 ms: 1.00x slower                                   |
| nqueens                  | 81.1 ms                                                | 81.5 ms: 1.00x slower                                   |
| xml_etree_generate       | 84.8 ms                                                | 85.2 ms: 1.00x slower                                   |
| deepcopy                 | 355 us                                                 | 357 us: 1.00x slower                                    |
| regex_effbot             | 3.55 ms                                                | 3.56 ms: 1.00x slower                                   |
| float                    | 80.7 ms                                                | 81.2 ms: 1.01x slower                                   |
| bench_thread_pool        | 827 us                                                 | 832 us: 1.01x slower                                    |
| xml_etree_process        | 58.6 ms                                                | 58.9 ms: 1.01x slower                                   |
| pickle_pure_python       | 309 us                                                 | 311 us: 1.01x slower                                    |
| sqlglot_transpile        | 1.64 ms                                                | 1.65 ms: 1.01x slower                                   |
| scimark_monte_carlo      | 71.0 ms                                                | 71.5 ms: 1.01x slower                                   |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                   |
| sqlglot_parse            | 1.32 ms                                                | 1.33 ms: 1.01x slower                                   |
| regex_dna                | 209 ms                                                 | 210 ms: 1.01x slower                                    |
| deltablue                | 3.52 ms                                                | 3.55 ms: 1.01x slower                                   |
| go                       | 136 ms                                                 | 137 ms: 1.01x slower                                    |
| async_tree_none          | 469 ms                                                 | 473 ms: 1.01x slower                                    |
| pickle_list              | 4.62 us                                                | 4.66 us: 1.01x slower                                   |
| comprehensions           | 20.4 us                                                | 20.6 us: 1.01x slower                                   |
| pickle                   | 10.6 us                                                | 10.7 us: 1.01x slower                                   |
| async_tree_io            | 1.16 sec                                               | 1.17 sec: 1.01x slower                                  |
| crypto_pyaes             | 77.2 ms                                                | 78.0 ms: 1.01x slower                                   |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                    |
| sqlglot_optimize         | 53.3 ms                                                | 53.9 ms: 1.01x slower                                   |
| logging_simple           | 6.18 us                                                | 6.25 us: 1.01x slower                                   |
| unpickle_list            | 4.95 us                                                | 5.00 us: 1.01x slower                                   |
| richards                 | 43.2 ms                                                | 43.7 ms: 1.01x slower                                   |
| tomli_loads              | 2.22 sec                                               | 2.25 sec: 1.01x slower                                  |
| deepcopy_memo            | 37.4 us                                                | 37.9 us: 1.01x slower                                   |
| logging_format           | 6.90 us                                                | 7.00 us: 1.01x slower                                   |
| richards_super           | 49.0 ms                                                | 49.7 ms: 1.02x slower                                   |
| fannkuch                 | 387 ms                                                 | 394 ms: 1.02x slower                                    |
| gc_traversal             | 3.84 ms                                                | 3.91 ms: 1.02x slower                                   |
| nbody                    | 88.8 ms                                                | 90.3 ms: 1.02x slower                                   |
| sqlglot_normalize        | 107 ms                                                 | 109 ms: 1.02x slower                                    |
| deepcopy_reduce          | 3.14 us                                                | 3.19 us: 1.02x slower                                   |
| hexiom                   | 6.12 ms                                                | 6.23 ms: 1.02x slower                                   |
| tornado_http             | 99.6 ms                                                | 102 ms: 1.02x slower                                    |
| async_generators         | 440 ms                                                 | 449 ms: 1.02x slower                                    |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.93 ms: 1.04x slower                                   |
| pickle_dict              | 31.6 us                                                | 32.8 us: 1.04x slower                                   |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.04x slower                                    |
| mdp                      | 2.57 sec                                               | 2.70 sec: 1.05x slower                                  |
| unpack_sequence          | 44.8 ns                                                | 52.9 ns: 1.18x slower                                   |
| dask                     | 365 ms                                                 | 537 ms: 1.47x slower                                    |
| Geometric mean           | (ref)                                                  | 1.01x slower                                            |

Benchmark hidden because not significant (21): json, scimark_sor, chaos, async_tree_cpu_io_mixed, scimark_fft, sqlalchemy_imperative, unpickle_pure_python, meteor_contest, bench_mp_pool, pyflate, asyncio_tcp_ssl, regex_compile, pprint_safe_repr, xml_etree_parse, mypy2, docutils, pycparser, sqlalchemy_declarative, raytrace, coverage, async_tree_memoization


# HPT report

- Reliability score: 99.84% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
