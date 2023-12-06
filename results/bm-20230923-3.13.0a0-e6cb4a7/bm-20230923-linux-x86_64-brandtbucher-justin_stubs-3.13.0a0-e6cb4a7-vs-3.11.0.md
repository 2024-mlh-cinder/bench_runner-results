
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_stubs
- machine: linux-x86_64
- commit hash: e6cb4a7
- commit date: 2023-09-23
- overall geometric mean: 1.02x faster
- HPT reliability: 85.03%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.69 sec: 1.02x slower                                              |
| tornado_http   | 96.3 ms                                                | 97.0 ms: 1.01x slower                                               |
| Geometric mean | (ref)                                                  | 1.02x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.05x faster                                                |
| nbody          | 93.1 ms                                                | 90.9 ms: 1.02x faster                                               |
| float          | 77.2 ms                                                | 82.5 ms: 1.07x slower                                               |
| Geometric mean | (ref)                                                  | 1.00x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.65 ms: 1.09x faster                                               |
| regex_dna      | 204 ms                                                 | 210 ms: 1.03x slower                                                |
| regex_compile  | 138 ms                                                 | 143 ms: 1.04x slower                                                |
| regex_v8       | 22.0 ms                                                | 23.3 ms: 1.06x slower                                               |
| Geometric mean | (ref)                                                  | 1.01x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.86 ms: 1.28x faster                                               |
| tomli_loads          | 2.22 sec                                               | 2.07 sec: 1.07x faster                                              |
| json_loads           | 26.5 us                                                | 25.2 us: 1.05x faster                                               |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                                |
| pickle_pure_python   | 306 us                                                 | 296 us: 1.03x faster                                                |
| unpickle_pure_python | 228 us                                                 | 223 us: 1.02x faster                                                |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                |
| pickle_dict          | 31.1 us                                                | 31.6 us: 1.02x slower                                               |
| unpickle_list        | 4.91 us                                                | 5.02 us: 1.02x slower                                               |
| pickle               | 10.1 us                                                | 10.3 us: 1.03x slower                                               |
| xml_etree_process    | 53.9 ms                                                | 58.1 ms: 1.08x slower                                               |
| unpickle             | 13.7 us                                                | 14.9 us: 1.09x slower                                               |
| xml_etree_generate   | 76.2 ms                                                | 84.6 ms: 1.11x slower                                               |
| pickle_list          | 4.11 us                                                | 4.58 us: 1.11x slower                                               |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.88 ms: 1.15x slower                                               |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                               |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.0 ms: 1.09x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 148 us: 3.28x faster                                                |
| generators               | 73.5 ms                                                | 28.4 ms: 2.59x faster                                               |
| asyncio_tcp              | 922 ms                                                 | 503 ms: 1.83x faster                                                |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                              |
| json_dumps               | 12.6 ms                                                | 9.86 ms: 1.28x faster                                               |
| mypy2                    | 420 ms                                                 | 350 ms: 1.20x faster                                                |
| async_tree_none          | 526 ms                                                 | 444 ms: 1.18x faster                                                |
| coroutines               | 25.5 ms                                                | 21.9 ms: 1.17x faster                                               |
| coverage                 | 100 ms                                                 | 86.7 ms: 1.15x faster                                               |
| async_tree_memoization   | 627 ms                                                 | 571 ms: 1.10x faster                                                |
| raytrace                 | 297 ms                                                 | 271 ms: 1.09x faster                                                |
| regex_effbot             | 3.99 ms                                                | 3.65 ms: 1.09x faster                                               |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.09x faster                                               |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                              |
| deltablue                | 3.67 ms                                                | 3.38 ms: 1.09x faster                                               |
| tomli_loads              | 2.22 sec                                               | 2.07 sec: 1.07x faster                                              |
| chaos                    | 69.2 ms                                                | 64.8 ms: 1.07x faster                                               |
| sqlglot_transpile        | 1.70 ms                                                | 1.61 ms: 1.06x faster                                               |
| pidigits                 | 198 ms                                                 | 188 ms: 1.05x faster                                                |
| json_loads               | 26.5 us                                                | 25.2 us: 1.05x faster                                               |
| richards_super           | 56.8 ms                                                | 54.1 ms: 1.05x faster                                               |
| crypto_pyaes             | 74.7 ms                                                | 71.3 ms: 1.05x faster                                               |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 706 ms: 1.05x faster                                                |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                |
| pickle_pure_python       | 306 us                                                 | 296 us: 1.03x faster                                                |
| scimark_monte_carlo      | 68.1 ms                                                | 66.2 ms: 1.03x faster                                               |
| unpickle_pure_python     | 228 us                                                 | 223 us: 1.02x faster                                                |
| nbody                    | 93.1 ms                                                | 90.9 ms: 1.02x faster                                               |
| json                     | 4.94 ms                                                | 4.86 ms: 1.02x faster                                               |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.01x faster                                                |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                |
| tornado_http             | 96.3 ms                                                | 97.0 ms: 1.01x slower                                               |
| pycparser                | 1.18 sec                                               | 1.19 sec: 1.01x slower                                              |
| sqlglot_optimize         | 53.1 ms                                                | 53.6 ms: 1.01x slower                                               |
| scimark_sor              | 118 ms                                                 | 120 ms: 1.01x slower                                                |
| pickle_dict              | 31.1 us                                                | 31.6 us: 1.02x slower                                               |
| bench_thread_pool        | 819 us                                                 | 832 us: 1.02x slower                                                |
| scimark_lu               | 110 ms                                                 | 112 ms: 1.02x slower                                                |
| unpickle_list            | 4.91 us                                                | 5.02 us: 1.02x slower                                               |
| comprehensions           | 22.4 us                                                | 23.0 us: 1.02x slower                                               |
| pathlib                  | 18.2 ms                                                | 18.7 ms: 1.02x slower                                               |
| docutils                 | 2.63 sec                                               | 2.69 sec: 1.02x slower                                              |
| pickle                   | 10.1 us                                                | 10.3 us: 1.03x slower                                               |
| create_gc_cycles         | 1.49 ms                                                | 1.53 ms: 1.03x slower                                               |
| regex_dna                | 204 ms                                                 | 210 ms: 1.03x slower                                                |
| meteor_contest           | 107 ms                                                 | 110 ms: 1.03x slower                                                |
| go                       | 140 ms                                                 | 145 ms: 1.03x slower                                                |
| fannkuch                 | 388 ms                                                 | 401 ms: 1.03x slower                                                |
| logging_simple           | 6.03 us                                                | 6.24 us: 1.03x slower                                               |
| logging_format           | 6.68 us                                                | 6.92 us: 1.04x slower                                               |
| regex_compile            | 138 ms                                                 | 143 ms: 1.04x slower                                                |
| scimark_fft              | 328 ms                                                 | 341 ms: 1.04x slower                                                |
| deepcopy                 | 342 us                                                 | 357 us: 1.04x slower                                                |
| logging_silent           | 101 ns                                                 | 105 ns: 1.04x slower                                                |
| nqueens                  | 83.4 ms                                                | 87.1 ms: 1.04x slower                                               |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.05x slower                                              |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.74 ms: 1.05x slower                                               |
| richards                 | 45.7 ms                                                | 48.2 ms: 1.05x slower                                               |
| regex_v8                 | 22.0 ms                                                | 23.3 ms: 1.06x slower                                               |
| deepcopy_memo            | 37.0 us                                                | 39.1 us: 1.06x slower                                               |
| pprint_safe_repr         | 701 ms                                                 | 748 ms: 1.07x slower                                                |
| float                    | 77.2 ms                                                | 82.5 ms: 1.07x slower                                               |
| dulwich_log              | 63.7 ms                                                | 68.3 ms: 1.07x slower                                               |
| hexiom                   | 6.37 ms                                                | 6.86 ms: 1.08x slower                                               |
| deepcopy_reduce          | 2.94 us                                                | 3.17 us: 1.08x slower                                               |
| xml_etree_process        | 53.9 ms                                                | 58.1 ms: 1.08x slower                                               |
| gc_traversal             | 4.02 ms                                                | 4.37 ms: 1.09x slower                                               |
| unpickle                 | 13.7 us                                                | 14.9 us: 1.09x slower                                               |
| mako                     | 10.1 ms                                                | 11.0 ms: 1.09x slower                                               |
| spectral_norm            | 100 ms                                                 | 109 ms: 1.09x slower                                                |
| pyflate                  | 418 ms                                                 | 459 ms: 1.10x slower                                                |
| sqlite_synth             | 2.52 us                                                | 2.76 us: 1.10x slower                                               |
| xml_etree_generate       | 76.2 ms                                                | 84.6 ms: 1.11x slower                                               |
| pickle_list              | 4.11 us                                                | 4.58 us: 1.11x slower                                               |
| python_startup_no_site   | 6.01 ms                                                | 6.88 ms: 1.15x slower                                               |
| unpack_sequence          | 43.1 ns                                                | 49.9 ns: 1.16x slower                                               |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                               |
| telco                    | 6.58 ms                                                | 8.07 ms: 1.23x slower                                               |
| async_generators         | 368 ms                                                 | 464 ms: 1.26x slower                                                |
| dask                     | 360 ms                                                 | 529 ms: 1.47x slower                                                |
| Geometric mean           | (ref)                                                  | 1.02x faster                                                        |

Benchmark hidden because not significant (2): bench_mp_pool, mdp
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 85.03% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
