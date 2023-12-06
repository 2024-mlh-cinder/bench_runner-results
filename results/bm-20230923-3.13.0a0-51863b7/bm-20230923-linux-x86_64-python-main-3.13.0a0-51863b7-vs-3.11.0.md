
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.05x faster
- HPT reliability: 96.52%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.60 sec: 1.01x faster                                |
| tornado_http   | 96.3 ms                                                | 94.9 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                  |
| nbody          | 93.1 ms                                                | 90.9 ms: 1.02x faster                                 |
| float          | 77.2 ms                                                | 78.8 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.36 ms: 1.19x faster                                 |
| regex_compile  | 138 ms                                                 | 134 ms: 1.03x faster                                  |
| regex_dna      | 204 ms                                                 | 202 ms: 1.01x faster                                  |
| regex_v8       | 22.0 ms                                                | 24.0 ms: 1.09x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.77 ms: 1.29x faster                                 |
| tomli_loads          | 2.22 sec                                               | 2.06 sec: 1.08x faster                                |
| unpickle_pure_python | 228 us                                                 | 215 us: 1.06x faster                                  |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                 |
| xml_etree_parse      | 158 ms                                                 | 153 ms: 1.04x faster                                  |
| pickle_pure_python   | 306 us                                                 | 296 us: 1.03x faster                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| pickle_dict          | 31.1 us                                                | 31.6 us: 1.01x slower                                 |
| pickle               | 10.1 us                                                | 10.2 us: 1.02x slower                                 |
| unpickle_list        | 4.91 us                                                | 5.03 us: 1.03x slower                                 |
| xml_etree_process    | 53.9 ms                                                | 56.5 ms: 1.05x slower                                 |
| xml_etree_generate   | 76.2 ms                                                | 81.5 ms: 1.07x slower                                 |
| unpickle             | 13.7 us                                                | 14.6 us: 1.07x slower                                 |
| pickle_list          | 4.11 us                                                | 4.75 us: 1.16x slower                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.86 ms: 1.14x slower                                 |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                 |
| Geometric mean         | (ref)                                                  | 1.16x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.9 ms: 1.08x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-python-main-3.13.0a0-51863b7 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 140 us: 3.48x faster                                  |
| generators               | 73.5 ms                                                | 29.5 ms: 2.49x faster                                 |
| asyncio_tcp              | 922 ms                                                 | 504 ms: 1.83x faster                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                |
| json_dumps               | 12.6 ms                                                | 9.77 ms: 1.29x faster                                 |
| mypy2                    | 420 ms                                                 | 338 ms: 1.24x faster                                  |
| async_tree_none          | 526 ms                                                 | 436 ms: 1.21x faster                                  |
| regex_effbot             | 3.99 ms                                                | 3.36 ms: 1.19x faster                                 |
| chaos                    | 69.2 ms                                                | 60.2 ms: 1.15x faster                                 |
| coroutines               | 25.5 ms                                                | 22.3 ms: 1.14x faster                                 |
| coverage                 | 100 ms                                                 | 87.8 ms: 1.14x faster                                 |
| async_tree_memoization   | 627 ms                                                 | 561 ms: 1.12x faster                                  |
| comprehensions           | 22.4 us                                                | 20.3 us: 1.11x faster                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.27 ms: 1.10x faster                                 |
| async_tree_io            | 1.30 sec                                               | 1.18 sec: 1.10x faster                                |
| deltablue                | 3.67 ms                                                | 3.34 ms: 1.10x faster                                 |
| raytrace                 | 297 ms                                                 | 271 ms: 1.10x faster                                  |
| sqlglot_transpile        | 1.70 ms                                                | 1.57 ms: 1.08x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.06 sec: 1.08x faster                                |
| crypto_pyaes             | 74.7 ms                                                | 69.8 ms: 1.07x faster                                 |
| hexiom                   | 6.37 ms                                                | 5.99 ms: 1.06x faster                                 |
| unpickle_pure_python     | 228 us                                                 | 215 us: 1.06x faster                                  |
| nqueens                  | 83.4 ms                                                | 78.7 ms: 1.06x faster                                 |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                  |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 699 ms: 1.06x faster                                  |
| richards_super           | 56.8 ms                                                | 54.2 ms: 1.05x faster                                 |
| mdp                      | 2.62 sec                                               | 2.50 sec: 1.04x faster                                |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                 |
| gc_traversal             | 4.02 ms                                                | 3.85 ms: 1.04x faster                                 |
| xml_etree_parse          | 158 ms                                                 | 153 ms: 1.04x faster                                  |
| json                     | 4.94 ms                                                | 4.78 ms: 1.03x faster                                 |
| pickle_pure_python       | 306 us                                                 | 296 us: 1.03x faster                                  |
| regex_compile            | 138 ms                                                 | 134 ms: 1.03x faster                                  |
| sqlglot_normalize        | 108 ms                                                 | 105 ms: 1.03x faster                                  |
| nbody                    | 93.1 ms                                                | 90.9 ms: 1.02x faster                                 |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                |
| logging_simple           | 6.03 us                                                | 5.92 us: 1.02x faster                                 |
| logging_format           | 6.68 us                                                | 6.57 us: 1.02x faster                                 |
| bench_thread_pool        | 819 us                                                 | 805 us: 1.02x faster                                  |
| tornado_http             | 96.3 ms                                                | 94.9 ms: 1.01x faster                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 67.2 ms: 1.01x faster                                 |
| docutils                 | 2.63 sec                                               | 2.60 sec: 1.01x faster                                |
| deepcopy_memo            | 37.0 us                                                | 36.6 us: 1.01x faster                                 |
| sqlglot_optimize         | 53.1 ms                                                | 52.6 ms: 1.01x faster                                 |
| regex_dna                | 204 ms                                                 | 202 ms: 1.01x faster                                  |
| logging_silent           | 101 ns                                                 | 100 ns: 1.01x faster                                  |
| deepcopy                 | 342 us                                                 | 344 us: 1.01x slower                                  |
| scimark_lu               | 110 ms                                                 | 111 ms: 1.01x slower                                  |
| pickle_dict              | 31.1 us                                                | 31.6 us: 1.01x slower                                 |
| fannkuch                 | 388 ms                                                 | 393 ms: 1.01x slower                                  |
| pickle                   | 10.1 us                                                | 10.2 us: 1.02x slower                                 |
| pprint_safe_repr         | 701 ms                                                 | 713 ms: 1.02x slower                                  |
| float                    | 77.2 ms                                                | 78.8 ms: 1.02x slower                                 |
| go                       | 140 ms                                                 | 143 ms: 1.02x slower                                  |
| unpickle_list            | 4.91 us                                                | 5.03 us: 1.03x slower                                 |
| create_gc_cycles         | 1.49 ms                                                | 1.54 ms: 1.03x slower                                 |
| dulwich_log              | 63.7 ms                                                | 65.9 ms: 1.03x slower                                 |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                 |
| xml_etree_process        | 53.9 ms                                                | 56.5 ms: 1.05x slower                                 |
| richards                 | 45.7 ms                                                | 48.0 ms: 1.05x slower                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.09 us: 1.05x slower                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.74 ms: 1.05x slower                                 |
| spectral_norm            | 100 ms                                                 | 106 ms: 1.06x slower                                  |
| xml_etree_generate       | 76.2 ms                                                | 81.5 ms: 1.07x slower                                 |
| unpickle                 | 13.7 us                                                | 14.6 us: 1.07x slower                                 |
| scimark_fft              | 328 ms                                                 | 353 ms: 1.08x slower                                  |
| mako                     | 10.1 ms                                                | 10.9 ms: 1.08x slower                                 |
| regex_v8                 | 22.0 ms                                                | 24.0 ms: 1.09x slower                                 |
| sqlite_synth             | 2.52 us                                                | 2.76 us: 1.09x slower                                 |
| scimark_sor              | 118 ms                                                 | 130 ms: 1.10x slower                                  |
| pyflate                  | 418 ms                                                 | 462 ms: 1.10x slower                                  |
| unpack_sequence          | 43.1 ns                                                | 48.0 ns: 1.11x slower                                 |
| python_startup_no_site   | 6.01 ms                                                | 6.86 ms: 1.14x slower                                 |
| pickle_list              | 4.11 us                                                | 4.75 us: 1.16x slower                                 |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                 |
| async_generators         | 368 ms                                                 | 443 ms: 1.20x slower                                  |
| telco                    | 6.58 ms                                                | 7.97 ms: 1.21x slower                                 |
| dask                     | 360 ms                                                 | 526 ms: 1.46x slower                                  |
| Geometric mean           | (ref)                                                  | 1.05x faster                                          |

Benchmark hidden because not significant (3): meteor_contest, bench_mp_pool, pprint_pformat
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 96.52% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
