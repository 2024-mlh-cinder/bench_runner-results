
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: dcaacd9
- commit date: 2023-09-03
- overall geometric mean: 1.03x faster
- HPT reliability: 58.24%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 259 ms                                                 | 268 ms: 1.03x slower                                    |
| docutils       | 2.63 sec                                               | 2.72 sec: 1.03x slower                                  |
| tornado_http   | 96.3 ms                                                | 99.5 ms: 1.03x slower                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                    |
| nbody          | 93.1 ms                                                | 89.5 ms: 1.04x faster                                   |
| float          | 77.2 ms                                                | 78.6 ms: 1.02x slower                                   |
| Geometric mean | (ref)                                                  | 1.03x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.61 ms: 1.11x faster                                   |
| regex_dna      | 204 ms                                                 | 210 ms: 1.03x slower                                    |
| regex_compile  | 138 ms                                                 | 142 ms: 1.03x slower                                    |
| regex_v8       | 22.0 ms                                                | 22.7 ms: 1.03x slower                                   |
| Geometric mean | (ref)                                                  | 1.00x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.85 ms: 1.28x faster                                   |
| unpickle_pure_python | 228 us                                                 | 216 us: 1.05x faster                                    |
| json_loads           | 26.5 us                                                | 25.2 us: 1.05x faster                                   |
| xml_etree_parse      | 158 ms                                                 | 154 ms: 1.03x faster                                    |
| tomli_loads          | 2.22 sec                                               | 2.17 sec: 1.02x faster                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                    |
| pickle_pure_python   | 306 us                                                 | 307 us: 1.01x slower                                    |
| pickle_dict          | 31.1 us                                                | 32.7 us: 1.05x slower                                   |
| unpickle_list        | 4.91 us                                                | 5.18 us: 1.06x slower                                   |
| unpickle             | 13.7 us                                                | 14.8 us: 1.09x slower                                   |
| pickle               | 10.1 us                                                | 11.0 us: 1.09x slower                                   |
| xml_etree_process    | 53.9 ms                                                | 58.6 ms: 1.09x slower                                   |
| xml_etree_generate   | 76.2 ms                                                | 84.4 ms: 1.11x slower                                   |
| pickle_list          | 4.11 us                                                | 4.74 us: 1.15x slower                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.44 ms: 1.11x slower                                   |
| python_startup_no_site | 6.01 ms                                                | 6.86 ms: 1.14x slower                                   |
| Geometric mean         | (ref)                                                  | 1.12x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.7 ms: 1.06x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 144 us: 3.38x faster                                    |
| generators               | 73.5 ms                                                | 32.0 ms: 2.29x faster                                   |
| asyncio_tcp              | 922 ms                                                 | 516 ms: 1.79x faster                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                  |
| json_dumps               | 12.6 ms                                                | 9.85 ms: 1.28x faster                                   |
| mypy2                    | 420 ms                                                 | 343 ms: 1.22x faster                                    |
| coroutines               | 25.5 ms                                                | 22.1 ms: 1.15x faster                                   |
| richards_super           | 56.8 ms                                                | 50.1 ms: 1.13x faster                                   |
| async_tree_none          | 526 ms                                                 | 468 ms: 1.12x faster                                    |
| async_tree_io            | 1.30 sec                                               | 1.16 sec: 1.12x faster                                  |
| regex_effbot             | 3.99 ms                                                | 3.61 ms: 1.11x faster                                   |
| chaos                    | 69.2 ms                                                | 63.1 ms: 1.10x faster                                   |
| async_tree_memoization   | 627 ms                                                 | 573 ms: 1.10x faster                                    |
| comprehensions           | 22.4 us                                                | 20.5 us: 1.09x faster                                   |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                    |
| sqlglot_parse            | 1.40 ms                                                | 1.32 ms: 1.06x faster                                   |
| coverage                 | 100 ms                                                 | 94.8 ms: 1.05x faster                                   |
| unpickle_pure_python     | 228 us                                                 | 216 us: 1.05x faster                                    |
| json_loads               | 26.5 us                                                | 25.2 us: 1.05x faster                                   |
| deltablue                | 3.67 ms                                                | 3.49 ms: 1.05x faster                                   |
| gc_traversal             | 4.02 ms                                                | 3.85 ms: 1.05x faster                                   |
| hexiom                   | 6.37 ms                                                | 6.10 ms: 1.04x faster                                   |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 708 ms: 1.04x faster                                    |
| sqlglot_transpile        | 1.70 ms                                                | 1.64 ms: 1.04x faster                                   |
| nbody                    | 93.1 ms                                                | 89.5 ms: 1.04x faster                                   |
| richards                 | 45.7 ms                                                | 44.0 ms: 1.04x faster                                   |
| xml_etree_parse          | 158 ms                                                 | 154 ms: 1.03x faster                                    |
| go                       | 140 ms                                                 | 136 ms: 1.03x faster                                    |
| json                     | 4.94 ms                                                | 4.83 ms: 1.02x faster                                   |
| tomli_loads              | 2.22 sec                                               | 2.17 sec: 1.02x faster                                  |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                  |
| mdp                      | 2.62 sec                                               | 2.56 sec: 1.02x faster                                  |
| raytrace                 | 297 ms                                                 | 291 ms: 1.02x faster                                    |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                    |
| logging_silent           | 101 ns                                                 | 100 ns: 1.01x faster                                    |
| nqueens                  | 83.4 ms                                                | 82.7 ms: 1.01x faster                                   |
| pathlib                  | 18.2 ms                                                | 18.1 ms: 1.01x faster                                   |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.00x faster                                    |
| sqlglot_optimize         | 53.1 ms                                                | 53.3 ms: 1.00x slower                                   |
| pickle_pure_python       | 306 us                                                 | 307 us: 1.01x slower                                    |
| bench_thread_pool        | 819 us                                                 | 829 us: 1.01x slower                                    |
| fannkuch                 | 388 ms                                                 | 393 ms: 1.01x slower                                    |
| float                    | 77.2 ms                                                | 78.6 ms: 1.02x slower                                   |
| deepcopy                 | 342 us                                                 | 348 us: 1.02x slower                                    |
| scimark_lu               | 110 ms                                                 | 112 ms: 1.02x slower                                    |
| pprint_pformat           | 1.46 sec                                               | 1.49 sec: 1.02x slower                                  |
| logging_simple           | 6.03 us                                                | 6.17 us: 1.02x slower                                   |
| sqlalchemy_imperative    | 17.9 ms                                                | 18.3 ms: 1.03x slower                                   |
| regex_dna                | 204 ms                                                 | 210 ms: 1.03x slower                                    |
| logging_format           | 6.68 us                                                | 6.88 us: 1.03x slower                                   |
| regex_compile            | 138 ms                                                 | 142 ms: 1.03x slower                                    |
| regex_v8                 | 22.0 ms                                                | 22.7 ms: 1.03x slower                                   |
| tornado_http             | 96.3 ms                                                | 99.5 ms: 1.03x slower                                   |
| 2to3                     | 259 ms                                                 | 268 ms: 1.03x slower                                    |
| docutils                 | 2.63 sec                                               | 2.72 sec: 1.03x slower                                  |
| scimark_sor              | 118 ms                                                 | 122 ms: 1.04x slower                                    |
| pprint_safe_repr         | 701 ms                                                 | 730 ms: 1.04x slower                                    |
| scimark_monte_carlo      | 68.1 ms                                                | 70.9 ms: 1.04x slower                                   |
| sqlalchemy_declarative   | 138 ms                                                 | 144 ms: 1.04x slower                                    |
| telco                    | 6.58 ms                                                | 6.91 ms: 1.05x slower                                   |
| pickle_dict              | 31.1 us                                                | 32.7 us: 1.05x slower                                   |
| crypto_pyaes             | 74.7 ms                                                | 78.6 ms: 1.05x slower                                   |
| unpickle_list            | 4.91 us                                                | 5.18 us: 1.06x slower                                   |
| mako                     | 10.1 ms                                                | 10.7 ms: 1.06x slower                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.11 us: 1.06x slower                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.77 ms: 1.06x slower                                   |
| dulwich_log              | 63.7 ms                                                | 68.1 ms: 1.07x slower                                   |
| spectral_norm            | 100 ms                                                 | 107 ms: 1.07x slower                                    |
| unpickle                 | 13.7 us                                                | 14.8 us: 1.09x slower                                   |
| pickle                   | 10.1 us                                                | 11.0 us: 1.09x slower                                   |
| xml_etree_process        | 53.9 ms                                                | 58.6 ms: 1.09x slower                                   |
| sqlite_synth             | 2.52 us                                                | 2.77 us: 1.10x slower                                   |
| python_startup           | 8.52 ms                                                | 9.44 ms: 1.11x slower                                   |
| xml_etree_generate       | 76.2 ms                                                | 84.4 ms: 1.11x slower                                   |
| pyflate                  | 418 ms                                                 | 464 ms: 1.11x slower                                    |
| scimark_fft              | 328 ms                                                 | 372 ms: 1.13x slower                                    |
| python_startup_no_site   | 6.01 ms                                                | 6.86 ms: 1.14x slower                                   |
| pickle_list              | 4.11 us                                                | 4.74 us: 1.15x slower                                   |
| unpack_sequence          | 43.1 ns                                                | 49.7 ns: 1.15x slower                                   |
| async_generators         | 368 ms                                                 | 450 ms: 1.22x slower                                    |
| dask                     | 360 ms                                                 | 533 ms: 1.48x slower                                    |
| Geometric mean           | (ref)                                                  | 1.03x faster                                            |

Benchmark hidden because not significant (4): create_gc_cycles, bench_mp_pool, meteor_contest, deepcopy_memo
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 58.24% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
