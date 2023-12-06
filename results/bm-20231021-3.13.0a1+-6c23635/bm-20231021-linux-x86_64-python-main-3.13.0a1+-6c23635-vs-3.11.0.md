
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.03x faster
- HPT reliability: 61.93%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.65 sec: 1.01x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.06x faster                                   |
| nbody          | 93.1 ms                                                | 89.5 ms: 1.04x faster                                  |
| float          | 77.2 ms                                                | 80.9 ms: 1.05x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.60 ms: 1.11x faster                                  |
| regex_dna      | 204 ms                                                 | 216 ms: 1.06x slower                                   |
| regex_v8       | 22.0 ms                                                | 24.1 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.6 ms: 1.19x faster                                  |
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                 |
| unpickle_pure_python | 228 us                                                 | 226 us: 1.01x faster                                   |
| pickle_pure_python   | 306 us                                                 | 308 us: 1.01x slower                                   |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                   |
| unpickle_list        | 4.91 us                                                | 5.05 us: 1.03x slower                                  |
| json_loads           | 26.5 us                                                | 27.7 us: 1.05x slower                                  |
| unpickle             | 13.7 us                                                | 14.5 us: 1.06x slower                                  |
| pickle_dict          | 31.1 us                                                | 33.9 us: 1.09x slower                                  |
| pickle               | 10.1 us                                                | 11.1 us: 1.10x slower                                  |
| xml_etree_process    | 53.9 ms                                                | 59.3 ms: 1.10x slower                                  |
| xml_etree_generate   | 76.2 ms                                                | 86.3 ms: 1.13x slower                                  |
| pickle_list          | 4.11 us                                                | 4.96 us: 1.21x slower                                  |
| Geometric mean       | (ref)                                                  | 1.04x slower                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.84 ms: 1.14x slower                                  |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                  |
| Geometric mean         | (ref)                                                  | 1.16x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.5 ms: 1.14x slower                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 151 us: 3.23x faster                                   |
| generators               | 73.5 ms                                                | 29.9 ms: 2.46x faster                                  |
| asyncio_tcp              | 922 ms                                                 | 485 ms: 1.90x faster                                   |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.78 sec: 1.77x faster                                 |
| mypy2                    | 420 ms                                                 | 343 ms: 1.22x faster                                   |
| async_tree_none          | 526 ms                                                 | 436 ms: 1.21x faster                                   |
| json_dumps               | 12.6 ms                                                | 10.6 ms: 1.19x faster                                  |
| gc_traversal             | 4.02 ms                                                | 3.52 ms: 1.14x faster                                  |
| async_tree_memoization   | 627 ms                                                 | 563 ms: 1.11x faster                                   |
| regex_effbot             | 3.99 ms                                                | 3.60 ms: 1.11x faster                                  |
| coroutines               | 25.5 ms                                                | 23.0 ms: 1.11x faster                                  |
| coverage                 | 100 ms                                                 | 90.4 ms: 1.11x faster                                  |
| chaos                    | 69.2 ms                                                | 62.6 ms: 1.11x faster                                  |
| deltablue                | 3.67 ms                                                | 3.32 ms: 1.10x faster                                  |
| async_tree_io            | 1.30 sec                                               | 1.18 sec: 1.09x faster                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.09x faster                                  |
| comprehensions           | 22.4 us                                                | 20.7 us: 1.08x faster                                  |
| raytrace                 | 297 ms                                                 | 275 ms: 1.08x faster                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.61 ms: 1.06x faster                                  |
| pidigits                 | 198 ms                                                 | 188 ms: 1.06x faster                                   |
| richards_super           | 56.8 ms                                                | 54.3 ms: 1.04x faster                                  |
| nbody                    | 93.1 ms                                                | 89.5 ms: 1.04x faster                                  |
| nqueens                  | 83.4 ms                                                | 80.5 ms: 1.04x faster                                  |
| mdp                      | 2.62 sec                                               | 2.53 sec: 1.03x faster                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 718 ms: 1.03x faster                                   |
| hexiom                   | 6.37 ms                                                | 6.21 ms: 1.03x faster                                  |
| logging_format           | 6.68 us                                                | 6.54 us: 1.02x faster                                  |
| crypto_pyaes             | 74.7 ms                                                | 73.2 ms: 1.02x faster                                  |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                   |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                 |
| create_gc_cycles         | 1.49 ms                                                | 1.46 ms: 1.02x faster                                  |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                 |
| unpickle_pure_python     | 228 us                                                 | 226 us: 1.01x faster                                   |
| logging_simple           | 6.03 us                                                | 5.98 us: 1.01x faster                                  |
| bench_thread_pool        | 819 us                                                 | 814 us: 1.01x faster                                   |
| sqlglot_optimize         | 53.1 ms                                                | 53.4 ms: 1.00x slower                                  |
| pickle_pure_python       | 306 us                                                 | 308 us: 1.01x slower                                   |
| docutils                 | 2.63 sec                                               | 2.65 sec: 1.01x slower                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 68.7 ms: 1.01x slower                                  |
| meteor_contest           | 107 ms                                                 | 108 ms: 1.02x slower                                   |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                   |
| go                       | 140 ms                                                 | 143 ms: 1.02x slower                                   |
| unpickle_list            | 4.91 us                                                | 5.05 us: 1.03x slower                                  |
| deepcopy                 | 342 us                                                 | 352 us: 1.03x slower                                   |
| pprint_pformat           | 1.46 sec                                               | 1.50 sec: 1.03x slower                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.67 ms: 1.04x slower                                  |
| json                     | 4.94 ms                                                | 5.14 ms: 1.04x slower                                  |
| deepcopy_memo            | 37.0 us                                                | 38.5 us: 1.04x slower                                  |
| dulwich_log              | 63.7 ms                                                | 66.6 ms: 1.05x slower                                  |
| json_loads               | 26.5 us                                                | 27.7 us: 1.05x slower                                  |
| float                    | 77.2 ms                                                | 80.9 ms: 1.05x slower                                  |
| pathlib                  | 18.2 ms                                                | 19.1 ms: 1.05x slower                                  |
| richards                 | 45.7 ms                                                | 47.9 ms: 1.05x slower                                  |
| logging_silent           | 101 ns                                                 | 106 ns: 1.05x slower                                   |
| pprint_safe_repr         | 701 ms                                                 | 739 ms: 1.05x slower                                   |
| unpack_sequence          | 43.1 ns                                                | 45.4 ns: 1.05x slower                                  |
| scimark_lu               | 110 ms                                                 | 116 ms: 1.06x slower                                   |
| regex_dna                | 204 ms                                                 | 216 ms: 1.06x slower                                   |
| fannkuch                 | 388 ms                                                 | 412 ms: 1.06x slower                                   |
| unpickle                 | 13.7 us                                                | 14.5 us: 1.06x slower                                  |
| deepcopy_reduce          | 2.94 us                                                | 3.15 us: 1.07x slower                                  |
| scimark_sor              | 118 ms                                                 | 127 ms: 1.08x slower                                   |
| pickle_dict              | 31.1 us                                                | 33.9 us: 1.09x slower                                  |
| regex_v8                 | 22.0 ms                                                | 24.1 ms: 1.09x slower                                  |
| pickle                   | 10.1 us                                                | 11.1 us: 1.10x slower                                  |
| xml_etree_process        | 53.9 ms                                                | 59.3 ms: 1.10x slower                                  |
| sqlite_synth             | 2.52 us                                                | 2.82 us: 1.12x slower                                  |
| xml_etree_generate       | 76.2 ms                                                | 86.3 ms: 1.13x slower                                  |
| scimark_fft              | 328 ms                                                 | 373 ms: 1.14x slower                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.84 ms: 1.14x slower                                  |
| mako                     | 10.1 ms                                                | 11.5 ms: 1.14x slower                                  |
| pyflate                  | 418 ms                                                 | 480 ms: 1.15x slower                                   |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                  |
| spectral_norm            | 100 ms                                                 | 119 ms: 1.18x slower                                   |
| pickle_list              | 4.11 us                                                | 4.96 us: 1.21x slower                                  |
| async_generators         | 368 ms                                                 | 460 ms: 1.25x slower                                   |
| telco                    | 6.58 ms                                                | 8.31 ms: 1.26x slower                                  |
| Geometric mean           | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (4): tornado_http, regex_compile, bench_mp_pool, xml_etree_parse
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 61.93% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
