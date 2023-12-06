
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.03x faster
- HPT reliability: 89.21%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 259 ms                                                 | 268 ms: 1.03x slower                                    |
| docutils       | 2.63 sec                                               | 2.71 sec: 1.03x slower                                  |
| tornado_http   | 96.3 ms                                                | 102 ms: 1.05x slower                                    |
| Geometric mean | (ref)                                                  | 1.04x slower                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 189 ms: 1.05x faster                                    |
| nbody          | 93.1 ms                                                | 90.3 ms: 1.03x faster                                   |
| float          | 77.2 ms                                                | 81.2 ms: 1.05x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.56 ms: 1.12x faster                                   |
| regex_v8       | 22.0 ms                                                | 22.4 ms: 1.02x slower                                   |
| regex_dna      | 204 ms                                                 | 210 ms: 1.03x slower                                    |
| regex_compile  | 138 ms                                                 | 144 ms: 1.04x slower                                    |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.64 ms: 1.31x faster                                   |
| json_loads           | 26.5 us                                                | 24.9 us: 1.06x faster                                   |
| unpickle_pure_python | 228 us                                                 | 218 us: 1.05x faster                                    |
| xml_etree_parse      | 158 ms                                                 | 154 ms: 1.03x faster                                    |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                    |
| tomli_loads          | 2.22 sec                                               | 2.25 sec: 1.01x slower                                  |
| pickle_pure_python   | 306 us                                                 | 311 us: 1.02x slower                                    |
| unpickle_list        | 4.91 us                                                | 5.00 us: 1.02x slower                                   |
| pickle_dict          | 31.1 us                                                | 32.8 us: 1.06x slower                                   |
| pickle               | 10.1 us                                                | 10.7 us: 1.06x slower                                   |
| unpickle             | 13.7 us                                                | 14.7 us: 1.08x slower                                   |
| xml_etree_process    | 53.9 ms                                                | 58.9 ms: 1.09x slower                                   |
| xml_etree_generate   | 76.2 ms                                                | 85.2 ms: 1.12x slower                                   |
| pickle_list          | 4.11 us                                                | 4.66 us: 1.13x slower                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.31 ms: 1.09x slower                                   |
| python_startup_no_site | 6.01 ms                                                | 6.77 ms: 1.13x slower                                   |
| Geometric mean         | (ref)                                                  | 1.11x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.8 ms: 1.07x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 144 us: 3.39x faster                                    |
| generators               | 73.5 ms                                                | 30.3 ms: 2.43x faster                                   |
| asyncio_tcp              | 922 ms                                                 | 504 ms: 1.83x faster                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.75x faster                                  |
| json_dumps               | 12.6 ms                                                | 9.64 ms: 1.31x faster                                   |
| mypy2                    | 420 ms                                                 | 344 ms: 1.22x faster                                    |
| coroutines               | 25.5 ms                                                | 22.0 ms: 1.16x faster                                   |
| richards_super           | 56.8 ms                                                | 49.7 ms: 1.14x faster                                   |
| regex_effbot             | 3.99 ms                                                | 3.56 ms: 1.12x faster                                   |
| async_tree_none          | 526 ms                                                 | 473 ms: 1.11x faster                                    |
| async_tree_io            | 1.30 sec                                               | 1.17 sec: 1.11x faster                                  |
| chaos                    | 69.2 ms                                                | 63.3 ms: 1.09x faster                                   |
| comprehensions           | 22.4 us                                                | 20.6 us: 1.09x faster                                   |
| async_tree_memoization   | 627 ms                                                 | 577 ms: 1.09x faster                                    |
| json_loads               | 26.5 us                                                | 24.9 us: 1.06x faster                                   |
| coverage                 | 100 ms                                                 | 94.6 ms: 1.06x faster                                   |
| sqlglot_parse            | 1.40 ms                                                | 1.33 ms: 1.05x faster                                   |
| pidigits                 | 198 ms                                                 | 189 ms: 1.05x faster                                    |
| unpickle_pure_python     | 228 us                                                 | 218 us: 1.05x faster                                    |
| richards                 | 45.7 ms                                                | 43.7 ms: 1.05x faster                                   |
| json                     | 4.94 ms                                                | 4.74 ms: 1.04x faster                                   |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 712 ms: 1.04x faster                                    |
| deltablue                | 3.67 ms                                                | 3.55 ms: 1.04x faster                                   |
| nbody                    | 93.1 ms                                                | 90.3 ms: 1.03x faster                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.65 ms: 1.03x faster                                   |
| xml_etree_parse          | 158 ms                                                 | 154 ms: 1.03x faster                                    |
| gc_traversal             | 4.02 ms                                                | 3.91 ms: 1.03x faster                                   |
| pycparser                | 1.18 sec                                               | 1.15 sec: 1.03x faster                                  |
| go                       | 140 ms                                                 | 137 ms: 1.02x faster                                    |
| nqueens                  | 83.4 ms                                                | 81.5 ms: 1.02x faster                                   |
| hexiom                   | 6.37 ms                                                | 6.23 ms: 1.02x faster                                   |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.02x faster                                    |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                    |
| sqlglot_normalize        | 108 ms                                                 | 109 ms: 1.01x slower                                    |
| tomli_loads              | 2.22 sec                                               | 2.25 sec: 1.01x slower                                  |
| sqlglot_optimize         | 53.1 ms                                                | 53.9 ms: 1.02x slower                                   |
| fannkuch                 | 388 ms                                                 | 394 ms: 1.02x slower                                    |
| bench_thread_pool        | 819 us                                                 | 832 us: 1.02x slower                                    |
| regex_v8                 | 22.0 ms                                                | 22.4 ms: 1.02x slower                                   |
| pickle_pure_python       | 306 us                                                 | 311 us: 1.02x slower                                    |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                   |
| unpickle_list            | 4.91 us                                                | 5.00 us: 1.02x slower                                   |
| logging_silent           | 101 ns                                                 | 103 ns: 1.02x slower                                    |
| pprint_pformat           | 1.46 sec                                               | 1.49 sec: 1.03x slower                                  |
| deepcopy_memo            | 37.0 us                                                | 37.9 us: 1.03x slower                                   |
| sqlalchemy_imperative    | 17.9 ms                                                | 18.4 ms: 1.03x slower                                   |
| scimark_lu               | 110 ms                                                 | 113 ms: 1.03x slower                                    |
| mdp                      | 2.62 sec                                               | 2.70 sec: 1.03x slower                                  |
| docutils                 | 2.63 sec                                               | 2.71 sec: 1.03x slower                                  |
| regex_dna                | 204 ms                                                 | 210 ms: 1.03x slower                                    |
| telco                    | 6.58 ms                                                | 6.79 ms: 1.03x slower                                   |
| 2to3                     | 259 ms                                                 | 268 ms: 1.03x slower                                    |
| logging_simple           | 6.03 us                                                | 6.25 us: 1.04x slower                                   |
| regex_compile            | 138 ms                                                 | 144 ms: 1.04x slower                                    |
| deepcopy                 | 342 us                                                 | 357 us: 1.04x slower                                    |
| crypto_pyaes             | 74.7 ms                                                | 78.0 ms: 1.04x slower                                   |
| sqlalchemy_declarative   | 138 ms                                                 | 144 ms: 1.05x slower                                    |
| logging_format           | 6.68 us                                                | 7.00 us: 1.05x slower                                   |
| spectral_norm            | 100 ms                                                 | 105 ms: 1.05x slower                                    |
| pprint_safe_repr         | 701 ms                                                 | 736 ms: 1.05x slower                                    |
| scimark_sor              | 118 ms                                                 | 124 ms: 1.05x slower                                    |
| float                    | 77.2 ms                                                | 81.2 ms: 1.05x slower                                   |
| scimark_monte_carlo      | 68.1 ms                                                | 71.5 ms: 1.05x slower                                   |
| tornado_http             | 96.3 ms                                                | 102 ms: 1.05x slower                                    |
| pickle_dict              | 31.1 us                                                | 32.8 us: 1.06x slower                                   |
| dulwich_log              | 63.7 ms                                                | 67.6 ms: 1.06x slower                                   |
| pickle                   | 10.1 us                                                | 10.7 us: 1.06x slower                                   |
| mako                     | 10.1 ms                                                | 10.8 ms: 1.07x slower                                   |
| sqlite_synth             | 2.52 us                                                | 2.71 us: 1.07x slower                                   |
| unpickle                 | 13.7 us                                                | 14.7 us: 1.08x slower                                   |
| pyflate                  | 418 ms                                                 | 450 ms: 1.08x slower                                    |
| deepcopy_reduce          | 2.94 us                                                | 3.19 us: 1.09x slower                                   |
| scimark_fft              | 328 ms                                                 | 358 ms: 1.09x slower                                    |
| python_startup           | 8.52 ms                                                | 9.31 ms: 1.09x slower                                   |
| xml_etree_process        | 53.9 ms                                                | 58.9 ms: 1.09x slower                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.93 ms: 1.10x slower                                   |
| xml_etree_generate       | 76.2 ms                                                | 85.2 ms: 1.12x slower                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.77 ms: 1.13x slower                                   |
| pickle_list              | 4.11 us                                                | 4.66 us: 1.13x slower                                   |
| async_generators         | 368 ms                                                 | 449 ms: 1.22x slower                                    |
| unpack_sequence          | 43.1 ns                                                | 52.9 ns: 1.23x slower                                   |
| dask                     | 360 ms                                                 | 537 ms: 1.49x slower                                    |
| Geometric mean           | (ref)                                                  | 1.03x faster                                            |

Benchmark hidden because not significant (3): raytrace, bench_mp_pool, pathlib
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 89.21% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
