
# Results vs. 3.11.0

- fork: gvanrossum
- ref: load_attr_uops
- machine: linux-x86_64
- commit hash: b54eee3
- commit date: 2023-09-26
- overall geometric mean: 1.05x faster
- HPT reliability: 93.26%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| tornado_http   | 96.3 ms                                                | 95.1 ms: 1.01x faster                                               |
| Geometric mean | (ref)                                                  | 1.01x faster                                                        |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.06x faster                                                |
| nbody          | 93.1 ms                                                | 90.9 ms: 1.02x faster                                               |
| float          | 77.2 ms                                                | 78.4 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                  | 1.02x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.52 ms: 1.13x faster                                               |
| regex_compile  | 138 ms                                                 | 133 ms: 1.04x faster                                                |
| regex_dna      | 204 ms                                                 | 212 ms: 1.04x slower                                                |
| regex_v8       | 22.0 ms                                                | 24.0 ms: 1.09x slower                                               |
| Geometric mean | (ref)                                                  | 1.01x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.76 ms: 1.29x faster                                               |
| unpickle_pure_python | 228 us                                                 | 211 us: 1.08x faster                                                |
| tomli_loads          | 2.22 sec                                               | 2.09 sec: 1.06x faster                                              |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                               |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                                |
| pickle_pure_python   | 306 us                                                 | 296 us: 1.03x faster                                                |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                |
| unpickle_list        | 4.91 us                                                | 4.96 us: 1.01x slower                                               |
| pickle_dict          | 31.1 us                                                | 31.9 us: 1.03x slower                                               |
| unpickle             | 13.7 us                                                | 14.3 us: 1.05x slower                                               |
| pickle               | 10.1 us                                                | 10.6 us: 1.05x slower                                               |
| xml_etree_process    | 53.9 ms                                                | 57.7 ms: 1.07x slower                                               |
| xml_etree_generate   | 76.2 ms                                                | 84.3 ms: 1.11x slower                                               |
| pickle_list          | 4.11 us                                                | 4.78 us: 1.16x slower                                               |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.86 ms: 1.14x slower                                               |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.19x slower                                               |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.6 ms: 1.05x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 142 us: 3.43x faster                                                |
| generators               | 73.5 ms                                                | 28.8 ms: 2.55x faster                                               |
| asyncio_tcp              | 922 ms                                                 | 505 ms: 1.83x faster                                                |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                              |
| json_dumps               | 12.6 ms                                                | 9.76 ms: 1.29x faster                                               |
| mypy2                    | 420 ms                                                 | 336 ms: 1.25x faster                                                |
| async_tree_none          | 526 ms                                                 | 440 ms: 1.20x faster                                                |
| coverage                 | 100 ms                                                 | 84.8 ms: 1.18x faster                                               |
| coroutines               | 25.5 ms                                                | 22.0 ms: 1.16x faster                                               |
| chaos                    | 69.2 ms                                                | 60.6 ms: 1.14x faster                                               |
| regex_effbot             | 3.99 ms                                                | 3.52 ms: 1.13x faster                                               |
| gc_traversal             | 4.02 ms                                                | 3.56 ms: 1.13x faster                                               |
| deltablue                | 3.67 ms                                                | 3.29 ms: 1.11x faster                                               |
| async_tree_memoization   | 627 ms                                                 | 565 ms: 1.11x faster                                                |
| sqlglot_parse            | 1.40 ms                                                | 1.26 ms: 1.11x faster                                               |
| raytrace                 | 297 ms                                                 | 268 ms: 1.11x faster                                                |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                              |
| crypto_pyaes             | 74.7 ms                                                | 68.6 ms: 1.09x faster                                               |
| comprehensions           | 22.4 us                                                | 20.7 us: 1.09x faster                                               |
| unpickle_pure_python     | 228 us                                                 | 211 us: 1.08x faster                                                |
| sqlglot_transpile        | 1.70 ms                                                | 1.58 ms: 1.08x faster                                               |
| tomli_loads              | 2.22 sec                                               | 2.09 sec: 1.06x faster                                              |
| hexiom                   | 6.37 ms                                                | 6.02 ms: 1.06x faster                                               |
| nqueens                  | 83.4 ms                                                | 78.9 ms: 1.06x faster                                               |
| pidigits                 | 198 ms                                                 | 188 ms: 1.06x faster                                                |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 703 ms: 1.05x faster                                                |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                               |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                |
| regex_compile            | 138 ms                                                 | 133 ms: 1.04x faster                                                |
| pickle_pure_python       | 306 us                                                 | 296 us: 1.03x faster                                                |
| sqlglot_normalize        | 108 ms                                                 | 105 ms: 1.03x faster                                                |
| scimark_monte_carlo      | 68.1 ms                                                | 66.2 ms: 1.03x faster                                               |
| pycparser                | 1.18 sec                                               | 1.15 sec: 1.03x faster                                              |
| logging_format           | 6.68 us                                                | 6.52 us: 1.03x faster                                               |
| nbody                    | 93.1 ms                                                | 90.9 ms: 1.02x faster                                               |
| richards_super           | 56.8 ms                                                | 55.4 ms: 1.02x faster                                               |
| json                     | 4.94 ms                                                | 4.85 ms: 1.02x faster                                               |
| deepcopy_memo            | 37.0 us                                                | 36.4 us: 1.02x faster                                               |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                |
| tornado_http             | 96.3 ms                                                | 95.1 ms: 1.01x faster                                               |
| logging_simple           | 6.03 us                                                | 5.96 us: 1.01x faster                                               |
| bench_thread_pool        | 819 us                                                 | 810 us: 1.01x faster                                                |
| sqlglot_optimize         | 53.1 ms                                                | 52.6 ms: 1.01x faster                                               |
| scimark_lu               | 110 ms                                                 | 109 ms: 1.01x faster                                                |
| go                       | 140 ms                                                 | 141 ms: 1.01x slower                                                |
| unpickle_list            | 4.91 us                                                | 4.96 us: 1.01x slower                                               |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.01x slower                                               |
| float                    | 77.2 ms                                                | 78.4 ms: 1.02x slower                                               |
| pprint_pformat           | 1.46 sec                                               | 1.48 sec: 1.02x slower                                              |
| mdp                      | 2.62 sec                                               | 2.67 sec: 1.02x slower                                              |
| pathlib                  | 18.2 ms                                                | 18.6 ms: 1.02x slower                                               |
| pickle_dict              | 31.1 us                                                | 31.9 us: 1.03x slower                                               |
| deepcopy                 | 342 us                                                 | 351 us: 1.03x slower                                                |
| pprint_safe_repr         | 701 ms                                                 | 727 ms: 1.04x slower                                                |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.67 ms: 1.04x slower                                               |
| regex_dna                | 204 ms                                                 | 212 ms: 1.04x slower                                                |
| dulwich_log              | 63.7 ms                                                | 66.2 ms: 1.04x slower                                               |
| unpickle                 | 13.7 us                                                | 14.3 us: 1.05x slower                                               |
| pickle                   | 10.1 us                                                | 10.6 us: 1.05x slower                                               |
| spectral_norm            | 100 ms                                                 | 105 ms: 1.05x slower                                                |
| mako                     | 10.1 ms                                                | 10.6 ms: 1.05x slower                                               |
| richards                 | 45.7 ms                                                | 48.6 ms: 1.06x slower                                               |
| xml_etree_process        | 53.9 ms                                                | 57.7 ms: 1.07x slower                                               |
| deepcopy_reduce          | 2.94 us                                                | 3.17 us: 1.08x slower                                               |
| regex_v8                 | 22.0 ms                                                | 24.0 ms: 1.09x slower                                               |
| scimark_fft              | 328 ms                                                 | 359 ms: 1.09x slower                                                |
| sqlite_synth             | 2.52 us                                                | 2.75 us: 1.09x slower                                               |
| scimark_sor              | 118 ms                                                 | 129 ms: 1.09x slower                                                |
| pyflate                  | 418 ms                                                 | 457 ms: 1.09x slower                                                |
| xml_etree_generate       | 76.2 ms                                                | 84.3 ms: 1.11x slower                                               |
| unpack_sequence          | 43.1 ns                                                | 48.2 ns: 1.12x slower                                               |
| python_startup_no_site   | 6.01 ms                                                | 6.86 ms: 1.14x slower                                               |
| pickle_list              | 4.11 us                                                | 4.78 us: 1.16x slower                                               |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.19x slower                                               |
| async_generators         | 368 ms                                                 | 444 ms: 1.21x slower                                                |
| telco                    | 6.58 ms                                                | 8.06 ms: 1.22x slower                                               |
| dask                     | 360 ms                                                 | 524 ms: 1.46x slower                                                |
| Geometric mean           | (ref)                                                  | 1.05x faster                                                        |

Benchmark hidden because not significant (5): meteor_contest, docutils, fannkuch, logging_silent, bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 93.26% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
