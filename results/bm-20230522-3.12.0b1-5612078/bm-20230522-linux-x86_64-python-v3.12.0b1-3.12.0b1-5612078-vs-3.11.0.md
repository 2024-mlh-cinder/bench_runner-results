
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b1
- machine: linux-x86_64
- commit hash: 5612078
- commit date: 2023-05-22
- overall geometric mean: 1.06x faster \*
- HPT reliability: 91.79%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 268 ms: 1.01x slower                                       |
| docutils       | 2.69 sec                                               | 2.71 sec: 1.01x slower                                     |
| tornado_http   | 97.7 ms                                                | 99.2 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 532 ms                                                 | 469 ms: 1.13x faster                                       |
| async_tree_io           | 1.31 sec                                               | 1.16 sec: 1.13x faster                                     |
| async_tree_memoization  | 640 ms                                                 | 572 ms: 1.12x faster                                       |
| async_tree_cpu_io_mixed | 750 ms                                                 | 708 ms: 1.06x faster                                       |
| Geometric mean          | (ref)                                                  | 1.11x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 91.6 ms                                                | 88.9 ms: 1.03x faster                                      |
| float          | 78.9 ms                                                | 80.7 ms: 1.02x slower                                      |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_v8       | 22.9 ms                                                | 21.8 ms: 1.05x faster                                      |
| regex_compile  | 141 ms                                                 | 144 ms: 1.02x slower                                       |
| regex_dna      | 204 ms                                                 | 208 ms: 1.02x slower                                       |
| regex_effbot   | 3.45 ms                                                | 3.54 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                  | 1.00x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 9.76 ms: 1.38x faster                                      |
| json_loads           | 29.4 us                                                | 25.1 us: 1.17x faster                                      |
| unpickle_pure_python | 241 us                                                 | 216 us: 1.12x faster                                       |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.06x faster                                       |
| tomli_loads          | 2.31 sec                                               | 2.18 sec: 1.06x faster                                     |
| xml_etree_iterparse  | 109 ms                                                 | 103 ms: 1.05x faster                                       |
| pickle               | 11.1 us                                                | 10.6 us: 1.05x faster                                      |
| pickle_dict          | 34.8 us                                                | 33.3 us: 1.05x faster                                      |
| pickle_pure_python   | 319 us                                                 | 312 us: 1.02x faster                                       |
| unpickle_list        | 5.22 us                                                | 5.17 us: 1.01x faster                                      |
| pickle_list          | 4.65 us                                                | 4.73 us: 1.02x slower                                      |
| xml_etree_process    | 56.5 ms                                                | 59.0 ms: 1.04x slower                                      |
| xml_etree_generate   | 80.4 ms                                                | 85.6 ms: 1.06x slower                                      |
| unpickle             | 13.9 us                                                | 14.9 us: 1.07x slower                                      |
| Geometric mean       | (ref)                                                  | 1.05x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 9.34 ms: 1.07x slower                                      |
| python_startup_no_site | 6.09 ms                                                | 6.78 ms: 1.11x slower                                      |
| Geometric mean         | (ref)                                                  | 1.09x slower                                               |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 521 us                                                 | 140 us: 3.72x faster                                       |
| generators               | 76.5 ms                                                | 31.4 ms: 2.43x faster                                      |
| asyncio_tcp_ssl          | 3.13 sec                                               | 1.80 sec: 1.74x faster                                     |
| asyncio_tcp              | 887 ms                                                 | 513 ms: 1.73x faster                                       |
| json_dumps               | 13.5 ms                                                | 9.76 ms: 1.38x faster                                      |
| richards_super           | 61.2 ms                                                | 49.8 ms: 1.23x faster                                      |
| coroutines               | 26.1 ms                                                | 21.9 ms: 1.20x faster                                      |
| json_loads               | 29.4 us                                                | 25.1 us: 1.17x faster                                      |
| comprehensions           | 23.6 us                                                | 20.6 us: 1.15x faster                                      |
| async_tree_none          | 532 ms                                                 | 469 ms: 1.13x faster                                       |
| async_tree_io            | 1.31 sec                                               | 1.16 sec: 1.13x faster                                     |
| richards                 | 48.9 ms                                                | 43.6 ms: 1.12x faster                                      |
| async_tree_memoization   | 640 ms                                                 | 572 ms: 1.12x faster                                       |
| unpickle_pure_python     | 241 us                                                 | 216 us: 1.12x faster                                       |
| deltablue                | 3.80 ms                                                | 3.44 ms: 1.11x faster                                      |
| chaos                    | 71.4 ms                                                | 64.6 ms: 1.11x faster                                      |
| hexiom                   | 6.74 ms                                                | 6.12 ms: 1.10x faster                                      |
| json                     | 5.24 ms                                                | 4.77 ms: 1.10x faster                                      |
| logging_silent           | 108 ns                                                 | 100 ns: 1.08x faster                                       |
| sqlglot_parse            | 1.43 ms                                                | 1.33 ms: 1.08x faster                                      |
| fannkuch                 | 410 ms                                                 | 382 ms: 1.07x faster                                       |
| sqlglot_transpile        | 1.75 ms                                                | 1.64 ms: 1.07x faster                                      |
| nqueens                  | 86.8 ms                                                | 81.4 ms: 1.07x faster                                      |
| gc_traversal             | 3.90 ms                                                | 3.67 ms: 1.06x faster                                      |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.06x faster                                       |
| tomli_loads              | 2.31 sec                                               | 2.18 sec: 1.06x faster                                     |
| async_tree_cpu_io_mixed  | 750 ms                                                 | 708 ms: 1.06x faster                                       |
| go                       | 143 ms                                                 | 136 ms: 1.05x faster                                       |
| xml_etree_iterparse      | 109 ms                                                 | 103 ms: 1.05x faster                                       |
| pickle                   | 11.1 us                                                | 10.6 us: 1.05x faster                                      |
| regex_v8                 | 22.9 ms                                                | 21.8 ms: 1.05x faster                                      |
| pickle_dict              | 34.8 us                                                | 33.3 us: 1.05x faster                                      |
| mdp                      | 2.79 sec                                               | 2.68 sec: 1.04x faster                                     |
| meteor_contest           | 109 ms                                                 | 105 ms: 1.03x faster                                       |
| sqlglot_normalize        | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| deepcopy_memo            | 38.9 us                                                | 37.6 us: 1.03x faster                                      |
| nbody                    | 91.6 ms                                                | 88.9 ms: 1.03x faster                                      |
| raytrace                 | 306 ms                                                 | 298 ms: 1.03x faster                                       |
| pickle_pure_python       | 319 us                                                 | 312 us: 1.02x faster                                       |
| pprint_pformat           | 1.53 sec                                               | 1.50 sec: 1.02x faster                                     |
| sqlglot_optimize         | 55.2 ms                                                | 54.1 ms: 1.02x faster                                      |
| pprint_safe_repr         | 743 ms                                                 | 733 ms: 1.01x faster                                       |
| unpickle_list            | 5.22 us                                                | 5.17 us: 1.01x faster                                      |
| pathlib                  | 18.5 ms                                                | 18.3 ms: 1.01x faster                                      |
| bench_thread_pool        | 833 us                                                 | 827 us: 1.01x faster                                       |
| crypto_pyaes             | 77.5 ms                                                | 77.9 ms: 1.01x slower                                      |
| scimark_lu               | 112 ms                                                 | 113 ms: 1.01x slower                                       |
| 2to3                     | 266 ms                                                 | 268 ms: 1.01x slower                                       |
| docutils                 | 2.69 sec                                               | 2.71 sec: 1.01x slower                                     |
| scimark_sor              | 121 ms                                                 | 123 ms: 1.01x slower                                       |
| create_gc_cycles         | 1.48 ms                                                | 1.50 ms: 1.01x slower                                      |
| logging_simple           | 6.24 us                                                | 6.33 us: 1.01x slower                                      |
| scimark_monte_carlo      | 71.8 ms                                                | 72.7 ms: 1.01x slower                                      |
| deepcopy_reduce          | 3.14 us                                                | 3.18 us: 1.01x slower                                      |
| regex_compile            | 141 ms                                                 | 144 ms: 1.02x slower                                       |
| tornado_http             | 97.7 ms                                                | 99.2 ms: 1.02x slower                                      |
| pickle_list              | 4.65 us                                                | 4.73 us: 1.02x slower                                      |
| telco                    | 6.72 ms                                                | 6.84 ms: 1.02x slower                                      |
| regex_dna                | 204 ms                                                 | 208 ms: 1.02x slower                                       |
| sqlalchemy_imperative    | 18.2 ms                                                | 18.6 ms: 1.02x slower                                      |
| float                    | 78.9 ms                                                | 80.7 ms: 1.02x slower                                      |
| regex_effbot             | 3.45 ms                                                | 3.54 ms: 1.02x slower                                      |
| spectral_norm            | 105 ms                                                 | 108 ms: 1.03x slower                                       |
| sqlalchemy_declarative   | 141 ms                                                 | 145 ms: 1.03x slower                                       |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                       |
| scimark_fft              | 342 ms                                                 | 356 ms: 1.04x slower                                       |
| logging_format           | 6.83 us                                                | 7.09 us: 1.04x slower                                      |
| pyflate                  | 426 ms                                                 | 443 ms: 1.04x slower                                       |
| dulwich_log              | 64.9 ms                                                | 67.7 ms: 1.04x slower                                      |
| xml_etree_process        | 56.5 ms                                                | 59.0 ms: 1.04x slower                                      |
| scimark_sparse_mat_mult  | 4.80 ms                                                | 5.05 ms: 1.05x slower                                      |
| sqlite_synth             | 2.58 us                                                | 2.72 us: 1.06x slower                                      |
| xml_etree_generate       | 80.4 ms                                                | 85.6 ms: 1.06x slower                                      |
| unpickle                 | 13.9 us                                                | 14.9 us: 1.07x slower                                      |
| python_startup           | 8.69 ms                                                | 9.34 ms: 1.07x slower                                      |
| unpack_sequence          | 43.3 ns                                                | 47.3 ns: 1.09x slower                                      |
| python_startup_no_site   | 6.09 ms                                                | 6.78 ms: 1.11x slower                                      |
| coverage                 | 81.2 ms                                                | 96.8 ms: 1.19x slower                                      |
| async_generators         | 375 ms                                                 | 449 ms: 1.20x slower                                       |
| dask                     | 365 ms                                                 | 535 ms: 1.47x slower                                       |
| Geometric mean           | (ref)                                                  | 1.06x faster                                               |

Benchmark hidden because not significant (5): pycparser, bench_mp_pool, mako, deepcopy, mypy2
Ignored benchmarks (20) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 91.79% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
