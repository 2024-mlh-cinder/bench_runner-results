
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3473315
- commit date: 2023-09-15
- overall geometric mean: 1.04x faster
- HPT reliability: 73.45%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.67 sec: 1.02x slower                                               |
| Geometric mean | (ref)                                                  | 1.01x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 93.1 ms                                                | 87.9 ms: 1.06x faster                                                |
| pidigits       | 198 ms                                                 | 188 ms: 1.05x faster                                                 |
| float          | 77.2 ms                                                | 81.5 ms: 1.06x slower                                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.40 ms: 1.18x faster                                                |
| regex_dna      | 204 ms                                                 | 204 ms: 1.00x slower                                                 |
| regex_compile  | 138 ms                                                 | 142 ms: 1.03x slower                                                 |
| regex_v8       | 22.0 ms                                                | 23.4 ms: 1.06x slower                                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.77 ms: 1.29x faster                                                |
| tomli_loads          | 2.22 sec                                               | 2.06 sec: 1.08x faster                                               |
| json_loads           | 26.5 us                                                | 25.3 us: 1.05x faster                                                |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                                 |
| pickle_pure_python   | 306 us                                                 | 300 us: 1.02x faster                                                 |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                 |
| unpickle_pure_python | 228 us                                                 | 225 us: 1.01x faster                                                 |
| unpickle_list        | 4.91 us                                                | 4.87 us: 1.01x faster                                                |
| pickle_dict          | 31.1 us                                                | 31.2 us: 1.00x slower                                                |
| pickle               | 10.1 us                                                | 10.3 us: 1.03x slower                                                |
| unpickle             | 13.7 us                                                | 14.1 us: 1.03x slower                                                |
| xml_etree_process    | 53.9 ms                                                | 57.4 ms: 1.07x slower                                                |
| xml_etree_generate   | 76.2 ms                                                | 83.4 ms: 1.09x slower                                                |
| pickle_list          | 4.11 us                                                | 4.64 us: 1.13x slower                                                |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.82 ms: 1.14x slower                                                |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.9 ms: 1.09x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 147 us: 3.30x faster                                                 |
| generators               | 73.5 ms                                                | 28.5 ms: 2.58x faster                                                |
| asyncio_tcp              | 922 ms                                                 | 487 ms: 1.89x faster                                                 |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.81 sec: 1.74x faster                                               |
| json_dumps               | 12.6 ms                                                | 9.77 ms: 1.29x faster                                                |
| async_tree_none          | 526 ms                                                 | 438 ms: 1.20x faster                                                 |
| mypy2                    | 420 ms                                                 | 350 ms: 1.20x faster                                                 |
| coverage                 | 100 ms                                                 | 84.5 ms: 1.18x faster                                                |
| regex_effbot             | 3.99 ms                                                | 3.40 ms: 1.18x faster                                                |
| coroutines               | 25.5 ms                                                | 21.8 ms: 1.17x faster                                                |
| async_tree_memoization   | 627 ms                                                 | 567 ms: 1.11x faster                                                 |
| raytrace                 | 297 ms                                                 | 270 ms: 1.10x faster                                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.10x faster                                                |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                               |
| deltablue                | 3.67 ms                                                | 3.38 ms: 1.09x faster                                                |
| tomli_loads              | 2.22 sec                                               | 2.06 sec: 1.08x faster                                               |
| chaos                    | 69.2 ms                                                | 64.3 ms: 1.08x faster                                                |
| sqlglot_transpile        | 1.70 ms                                                | 1.59 ms: 1.07x faster                                                |
| nbody                    | 93.1 ms                                                | 87.9 ms: 1.06x faster                                                |
| richards_super           | 56.8 ms                                                | 53.7 ms: 1.06x faster                                                |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 701 ms: 1.05x faster                                                 |
| pidigits                 | 198 ms                                                 | 188 ms: 1.05x faster                                                 |
| gc_traversal             | 4.02 ms                                                | 3.84 ms: 1.05x faster                                                |
| json_loads               | 26.5 us                                                | 25.3 us: 1.05x faster                                                |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                 |
| crypto_pyaes             | 74.7 ms                                                | 71.6 ms: 1.04x faster                                                |
| pycparser                | 1.18 sec                                               | 1.15 sec: 1.03x faster                                               |
| scimark_monte_carlo      | 68.1 ms                                                | 66.5 ms: 1.02x faster                                                |
| pickle_pure_python       | 306 us                                                 | 300 us: 1.02x faster                                                 |
| logging_simple           | 6.03 us                                                | 5.94 us: 1.02x faster                                                |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                 |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.01x faster                                                 |
| unpickle_pure_python     | 228 us                                                 | 225 us: 1.01x faster                                                 |
| unpickle_list            | 4.91 us                                                | 4.87 us: 1.01x faster                                                |
| pickle_dict              | 31.1 us                                                | 31.2 us: 1.00x slower                                                |
| regex_dna                | 204 ms                                                 | 204 ms: 1.00x slower                                                 |
| comprehensions           | 22.4 us                                                | 22.5 us: 1.00x slower                                                |
| sqlglot_optimize         | 53.1 ms                                                | 53.4 ms: 1.00x slower                                                |
| create_gc_cycles         | 1.49 ms                                                | 1.50 ms: 1.01x slower                                                |
| pprint_pformat           | 1.46 sec                                               | 1.48 sec: 1.01x slower                                               |
| json                     | 4.94 ms                                                | 5.02 ms: 1.02x slower                                                |
| docutils                 | 2.63 sec                                               | 2.67 sec: 1.02x slower                                               |
| bench_thread_pool        | 819 us                                                 | 834 us: 1.02x slower                                                 |
| logging_silent           | 101 ns                                                 | 103 ns: 1.02x slower                                                 |
| pprint_safe_repr         | 701 ms                                                 | 717 ms: 1.02x slower                                                 |
| meteor_contest           | 107 ms                                                 | 109 ms: 1.02x slower                                                 |
| scimark_lu               | 110 ms                                                 | 112 ms: 1.02x slower                                                 |
| regex_compile            | 138 ms                                                 | 142 ms: 1.03x slower                                                 |
| pickle                   | 10.1 us                                                | 10.3 us: 1.03x slower                                                |
| deepcopy                 | 342 us                                                 | 351 us: 1.03x slower                                                 |
| pathlib                  | 18.2 ms                                                | 18.7 ms: 1.03x slower                                                |
| go                       | 140 ms                                                 | 144 ms: 1.03x slower                                                 |
| unpickle                 | 13.7 us                                                | 14.1 us: 1.03x slower                                                |
| scimark_fft              | 328 ms                                                 | 340 ms: 1.04x slower                                                 |
| richards                 | 45.7 ms                                                | 47.6 ms: 1.04x slower                                                |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.69 ms: 1.04x slower                                                |
| mdp                      | 2.62 sec                                               | 2.73 sec: 1.04x slower                                               |
| deepcopy_reduce          | 2.94 us                                                | 3.10 us: 1.05x slower                                                |
| nqueens                  | 83.4 ms                                                | 87.8 ms: 1.05x slower                                                |
| fannkuch                 | 388 ms                                                 | 409 ms: 1.05x slower                                                 |
| float                    | 77.2 ms                                                | 81.5 ms: 1.06x slower                                                |
| regex_v8                 | 22.0 ms                                                | 23.4 ms: 1.06x slower                                                |
| xml_etree_process        | 53.9 ms                                                | 57.4 ms: 1.07x slower                                                |
| hexiom                   | 6.37 ms                                                | 6.80 ms: 1.07x slower                                                |
| dulwich_log              | 63.7 ms                                                | 68.7 ms: 1.08x slower                                                |
| spectral_norm            | 100 ms                                                 | 108 ms: 1.08x slower                                                 |
| mako                     | 10.1 ms                                                | 10.9 ms: 1.09x slower                                                |
| unpack_sequence          | 43.1 ns                                                | 46.9 ns: 1.09x slower                                                |
| sqlite_synth             | 2.52 us                                                | 2.75 us: 1.09x slower                                                |
| pyflate                  | 418 ms                                                 | 456 ms: 1.09x slower                                                 |
| xml_etree_generate       | 76.2 ms                                                | 83.4 ms: 1.09x slower                                                |
| pickle_list              | 4.11 us                                                | 4.64 us: 1.13x slower                                                |
| python_startup_no_site   | 6.01 ms                                                | 6.82 ms: 1.14x slower                                                |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                |
| telco                    | 6.58 ms                                                | 7.92 ms: 1.20x slower                                                |
| async_generators         | 368 ms                                                 | 458 ms: 1.24x slower                                                 |
| dask                     | 360 ms                                                 | 529 ms: 1.47x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.04x faster                                                         |

Benchmark hidden because not significant (5): logging_format, deepcopy_memo, bench_mp_pool, tornado_http, scimark_sor
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 73.45% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
