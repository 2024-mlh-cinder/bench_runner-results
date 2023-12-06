
# Results vs. 3.11.0

- fork: brandtbucher
- ref: kwnames_tstate
- machine: linux-x86_64
- commit hash: 70d0242
- commit date: 2023-08-11
- overall geometric mean: 1.03x faster
- HPT reliability: 52.67%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 189 ms: 1.05x faster                                                  |
| nbody          | 93.1 ms                                                | 96.1 ms: 1.03x slower                                                 |
| float          | 77.2 ms                                                | 81.4 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.76 ms: 1.06x faster                                                 |
| regex_compile  | 138 ms                                                 | 137 ms: 1.01x faster                                                  |
| regex_dna      | 204 ms                                                 | 219 ms: 1.08x slower                                                  |
| regex_v8       | 22.0 ms                                                | 25.9 ms: 1.18x slower                                                 |
| Geometric mean | (ref)                                                  | 1.04x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.90 ms: 1.27x faster                                                 |
| unpickle_pure_python | 228 us                                                 | 218 us: 1.05x faster                                                  |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                                 |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                                  |
| tomli_loads          | 2.22 sec                                               | 2.19 sec: 1.01x faster                                                |
| pickle_pure_python   | 306 us                                                 | 303 us: 1.01x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                  |
| unpickle_list        | 4.91 us                                                | 4.98 us: 1.01x slower                                                 |
| pickle_dict          | 31.1 us                                                | 31.9 us: 1.03x slower                                                 |
| unpickle             | 13.7 us                                                | 14.4 us: 1.05x slower                                                 |
| xml_etree_process    | 53.9 ms                                                | 57.7 ms: 1.07x slower                                                 |
| pickle               | 10.1 us                                                | 10.9 us: 1.08x slower                                                 |
| xml_etree_generate   | 76.2 ms                                                | 83.7 ms: 1.10x slower                                                 |
| pickle_list          | 4.11 us                                                | 4.54 us: 1.11x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.41 ms: 1.10x slower                                                 |
| python_startup_no_site | 6.01 ms                                                | 6.88 ms: 1.15x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.12x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.2 ms: 1.11x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 147 us: 3.30x faster                                                  |
| generators               | 73.5 ms                                                | 30.2 ms: 2.44x faster                                                 |
| asyncio_tcp              | 922 ms                                                 | 499 ms: 1.85x faster                                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.75x faster                                                |
| json_dumps               | 12.6 ms                                                | 9.90 ms: 1.27x faster                                                 |
| mypy2                    | 420 ms                                                 | 339 ms: 1.24x faster                                                  |
| async_tree_none          | 526 ms                                                 | 442 ms: 1.19x faster                                                  |
| coverage                 | 100 ms                                                 | 85.7 ms: 1.17x faster                                                 |
| chaos                    | 69.2 ms                                                | 60.5 ms: 1.14x faster                                                 |
| coroutines               | 25.5 ms                                                | 22.6 ms: 1.13x faster                                                 |
| deltablue                | 3.67 ms                                                | 3.32 ms: 1.11x faster                                                 |
| async_tree_memoization   | 627 ms                                                 | 570 ms: 1.10x faster                                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.10x faster                                                 |
| async_tree_io            | 1.30 sec                                               | 1.20 sec: 1.08x faster                                                |
| comprehensions           | 22.4 us                                                | 20.9 us: 1.08x faster                                                 |
| crypto_pyaes             | 74.7 ms                                                | 69.5 ms: 1.08x faster                                                 |
| raytrace                 | 297 ms                                                 | 277 ms: 1.07x faster                                                  |
| sqlglot_transpile        | 1.70 ms                                                | 1.60 ms: 1.07x faster                                                 |
| regex_effbot             | 3.99 ms                                                | 3.76 ms: 1.06x faster                                                 |
| richards_super           | 56.8 ms                                                | 53.7 ms: 1.06x faster                                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 704 ms: 1.05x faster                                                  |
| pidigits                 | 198 ms                                                 | 189 ms: 1.05x faster                                                  |
| unpickle_pure_python     | 228 us                                                 | 218 us: 1.05x faster                                                  |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                                 |
| hexiom                   | 6.37 ms                                                | 6.12 ms: 1.04x faster                                                 |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                  |
| nqueens                  | 83.4 ms                                                | 80.5 ms: 1.04x faster                                                 |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                                  |
| tomli_loads              | 2.22 sec                                               | 2.19 sec: 1.01x faster                                                |
| regex_compile            | 138 ms                                                 | 137 ms: 1.01x faster                                                  |
| pickle_pure_python       | 306 us                                                 | 303 us: 1.01x faster                                                  |
| logging_format           | 6.68 us                                                | 6.62 us: 1.01x faster                                                 |
| logging_simple           | 6.03 us                                                | 5.98 us: 1.01x faster                                                 |
| mdp                      | 2.62 sec                                               | 2.59 sec: 1.01x faster                                                |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                  |
| scimark_monte_carlo      | 68.1 ms                                                | 67.5 ms: 1.01x faster                                                 |
| bench_thread_pool        | 819 us                                                 | 822 us: 1.00x slower                                                  |
| go                       | 140 ms                                                 | 141 ms: 1.01x slower                                                  |
| pprint_pformat           | 1.46 sec                                               | 1.47 sec: 1.01x slower                                                |
| unpickle_list            | 4.91 us                                                | 4.98 us: 1.01x slower                                                 |
| deepcopy_memo            | 37.0 us                                                | 37.5 us: 1.01x slower                                                 |
| fannkuch                 | 388 ms                                                 | 394 ms: 1.02x slower                                                  |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                                 |
| pathlib                  | 18.2 ms                                                | 18.6 ms: 1.02x slower                                                 |
| richards                 | 45.7 ms                                                | 46.7 ms: 1.02x slower                                                 |
| pickle_dict              | 31.1 us                                                | 31.9 us: 1.03x slower                                                 |
| pprint_safe_repr         | 701 ms                                                 | 722 ms: 1.03x slower                                                  |
| nbody                    | 93.1 ms                                                | 96.1 ms: 1.03x slower                                                 |
| deepcopy                 | 342 us                                                 | 354 us: 1.03x slower                                                  |
| logging_silent           | 101 ns                                                 | 105 ns: 1.04x slower                                                  |
| dulwich_log              | 63.7 ms                                                | 66.9 ms: 1.05x slower                                                 |
| scimark_sor              | 118 ms                                                 | 124 ms: 1.05x slower                                                  |
| float                    | 77.2 ms                                                | 81.4 ms: 1.05x slower                                                 |
| unpickle                 | 13.7 us                                                | 14.4 us: 1.05x slower                                                 |
| unpack_sequence          | 43.1 ns                                                | 45.5 ns: 1.06x slower                                                 |
| gc_traversal             | 4.02 ms                                                | 4.25 ms: 1.06x slower                                                 |
| xml_etree_process        | 53.9 ms                                                | 57.7 ms: 1.07x slower                                                 |
| sqlite_synth             | 2.52 us                                                | 2.71 us: 1.07x slower                                                 |
| regex_dna                | 204 ms                                                 | 219 ms: 1.08x slower                                                  |
| pickle                   | 10.1 us                                                | 10.9 us: 1.08x slower                                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.18 us: 1.08x slower                                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.88 ms: 1.09x slower                                                 |
| pyflate                  | 418 ms                                                 | 458 ms: 1.10x slower                                                  |
| xml_etree_generate       | 76.2 ms                                                | 83.7 ms: 1.10x slower                                                 |
| spectral_norm            | 100 ms                                                 | 110 ms: 1.10x slower                                                  |
| python_startup           | 8.52 ms                                                | 9.41 ms: 1.10x slower                                                 |
| scimark_fft              | 328 ms                                                 | 363 ms: 1.10x slower                                                  |
| pickle_list              | 4.11 us                                                | 4.54 us: 1.11x slower                                                 |
| mako                     | 10.1 ms                                                | 11.2 ms: 1.11x slower                                                 |
| python_startup_no_site   | 6.01 ms                                                | 6.88 ms: 1.15x slower                                                 |
| regex_v8                 | 22.0 ms                                                | 25.9 ms: 1.18x slower                                                 |
| async_generators         | 368 ms                                                 | 453 ms: 1.23x slower                                                  |
| telco                    | 6.58 ms                                                | 8.15 ms: 1.24x slower                                                 |
| dask                     | 360 ms                                                 | 526 ms: 1.46x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.03x faster                                                          |

Benchmark hidden because not significant (8): json, meteor_contest, scimark_lu, pycparser, bench_mp_pool, docutils, sqlglot_optimize, tornado_http
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 52.67% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
