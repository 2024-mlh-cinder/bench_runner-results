
# Results vs. 3.11.0

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: linux-x86_64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.05x faster
- HPT reliability: 97.14%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.60 sec: 1.01x faster                                                |
| tornado_http   | 96.3 ms                                                | 95.2 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 93.1 ms                                                | 88.1 ms: 1.06x faster                                                 |
| float          | 77.2 ms                                                | 79.5 ms: 1.03x slower                                                 |
| pidigits       | 198 ms                                                 | 212 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.42 ms: 1.17x faster                                                 |
| regex_compile  | 138 ms                                                 | 134 ms: 1.03x faster                                                  |
| regex_dna      | 204 ms                                                 | 205 ms: 1.01x slower                                                  |
| regex_v8       | 22.0 ms                                                | 23.6 ms: 1.07x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.85 ms: 1.28x faster                                                 |
| tomli_loads          | 2.22 sec                                               | 1.99 sec: 1.11x faster                                                |
| unpickle_pure_python | 228 us                                                 | 212 us: 1.07x faster                                                  |
| json_loads           | 26.5 us                                                | 25.1 us: 1.06x faster                                                 |
| xml_etree_parse      | 158 ms                                                 | 154 ms: 1.03x faster                                                  |
| pickle_pure_python   | 306 us                                                 | 297 us: 1.03x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 101 ms: 1.03x faster                                                  |
| pickle_dict          | 31.1 us                                                | 32.7 us: 1.05x slower                                                 |
| xml_etree_process    | 53.9 ms                                                | 57.7 ms: 1.07x slower                                                 |
| pickle               | 10.1 us                                                | 10.9 us: 1.08x slower                                                 |
| unpickle             | 13.7 us                                                | 15.0 us: 1.10x slower                                                 |
| xml_etree_generate   | 76.2 ms                                                | 83.8 ms: 1.10x slower                                                 |
| pickle_list          | 4.11 us                                                | 4.74 us: 1.15x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                          |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.87 ms: 1.14x slower                                                 |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.6 ms: 1.05x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 144 us: 3.39x faster                                                  |
| generators               | 73.5 ms                                                | 28.0 ms: 2.62x faster                                                 |
| asyncio_tcp              | 922 ms                                                 | 488 ms: 1.89x faster                                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                                |
| json_dumps               | 12.6 ms                                                | 9.85 ms: 1.28x faster                                                 |
| mypy2                    | 420 ms                                                 | 337 ms: 1.25x faster                                                  |
| async_tree_none          | 526 ms                                                 | 439 ms: 1.20x faster                                                  |
| regex_effbot             | 3.99 ms                                                | 3.42 ms: 1.17x faster                                                 |
| coroutines               | 25.5 ms                                                | 21.9 ms: 1.16x faster                                                 |
| chaos                    | 69.2 ms                                                | 59.9 ms: 1.16x faster                                                 |
| coverage                 | 100 ms                                                 | 86.7 ms: 1.15x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 1.99 sec: 1.11x faster                                                |
| comprehensions           | 22.4 us                                                | 20.2 us: 1.11x faster                                                 |
| raytrace                 | 297 ms                                                 | 268 ms: 1.11x faster                                                  |
| deltablue                | 3.67 ms                                                | 3.32 ms: 1.11x faster                                                 |
| async_tree_memoization   | 627 ms                                                 | 568 ms: 1.10x faster                                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.28 ms: 1.10x faster                                                 |
| crypto_pyaes             | 74.7 ms                                                | 68.5 ms: 1.09x faster                                                 |
| async_tree_io            | 1.30 sec                                               | 1.20 sec: 1.08x faster                                                |
| hexiom                   | 6.37 ms                                                | 5.91 ms: 1.08x faster                                                 |
| sqlglot_transpile        | 1.70 ms                                                | 1.58 ms: 1.08x faster                                                 |
| unpickle_pure_python     | 228 us                                                 | 212 us: 1.07x faster                                                  |
| nqueens                  | 83.4 ms                                                | 78.3 ms: 1.06x faster                                                 |
| richards_super           | 56.8 ms                                                | 53.5 ms: 1.06x faster                                                 |
| nbody                    | 93.1 ms                                                | 88.1 ms: 1.06x faster                                                 |
| json_loads               | 26.5 us                                                | 25.1 us: 1.06x faster                                                 |
| unpack_sequence          | 43.1 ns                                                | 41.1 ns: 1.05x faster                                                 |
| gc_traversal             | 4.02 ms                                                | 3.86 ms: 1.04x faster                                                 |
| logging_format           | 6.68 us                                                | 6.42 us: 1.04x faster                                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 710 ms: 1.04x faster                                                  |
| deepcopy_memo            | 37.0 us                                                | 35.6 us: 1.04x faster                                                 |
| sqlglot_normalize        | 108 ms                                                 | 104 ms: 1.04x faster                                                  |
| json                     | 4.94 ms                                                | 4.77 ms: 1.04x faster                                                 |
| mdp                      | 2.62 sec                                               | 2.53 sec: 1.03x faster                                                |
| logging_simple           | 6.03 us                                                | 5.83 us: 1.03x faster                                                 |
| regex_compile            | 138 ms                                                 | 134 ms: 1.03x faster                                                  |
| xml_etree_parse          | 158 ms                                                 | 154 ms: 1.03x faster                                                  |
| pickle_pure_python       | 306 us                                                 | 297 us: 1.03x faster                                                  |
| scimark_monte_carlo      | 68.1 ms                                                | 66.4 ms: 1.03x faster                                                 |
| xml_etree_iterparse      | 104 ms                                                 | 101 ms: 1.03x faster                                                  |
| pycparser                | 1.18 sec                                               | 1.15 sec: 1.03x faster                                                |
| logging_silent           | 101 ns                                                 | 98.7 ns: 1.02x faster                                                 |
| sqlglot_optimize         | 53.1 ms                                                | 52.2 ms: 1.02x faster                                                 |
| bench_thread_pool        | 819 us                                                 | 807 us: 1.01x faster                                                  |
| docutils                 | 2.63 sec                                               | 2.60 sec: 1.01x faster                                                |
| fannkuch                 | 388 ms                                                 | 383 ms: 1.01x faster                                                  |
| tornado_http             | 96.3 ms                                                | 95.2 ms: 1.01x faster                                                 |
| pprint_pformat           | 1.46 sec                                               | 1.45 sec: 1.00x faster                                                |
| go                       | 140 ms                                                 | 141 ms: 1.00x slower                                                  |
| regex_dna                | 204 ms                                                 | 205 ms: 1.01x slower                                                  |
| pathlib                  | 18.2 ms                                                | 18.4 ms: 1.01x slower                                                 |
| scimark_lu               | 110 ms                                                 | 111 ms: 1.01x slower                                                  |
| deepcopy                 | 342 us                                                 | 348 us: 1.02x slower                                                  |
| pprint_safe_repr         | 701 ms                                                 | 715 ms: 1.02x slower                                                  |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.62 ms: 1.03x slower                                                 |
| float                    | 77.2 ms                                                | 79.5 ms: 1.03x slower                                                 |
| create_gc_cycles         | 1.49 ms                                                | 1.54 ms: 1.04x slower                                                 |
| spectral_norm            | 100 ms                                                 | 104 ms: 1.04x slower                                                  |
| dulwich_log              | 63.7 ms                                                | 66.2 ms: 1.04x slower                                                 |
| richards                 | 45.7 ms                                                | 47.7 ms: 1.04x slower                                                 |
| pickle_dict              | 31.1 us                                                | 32.7 us: 1.05x slower                                                 |
| mako                     | 10.1 ms                                                | 10.6 ms: 1.05x slower                                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.13 us: 1.06x slower                                                 |
| regex_v8                 | 22.0 ms                                                | 23.6 ms: 1.07x slower                                                 |
| pidigits                 | 198 ms                                                 | 212 ms: 1.07x slower                                                  |
| xml_etree_process        | 53.9 ms                                                | 57.7 ms: 1.07x slower                                                 |
| pickle                   | 10.1 us                                                | 10.9 us: 1.08x slower                                                 |
| pyflate                  | 418 ms                                                 | 456 ms: 1.09x slower                                                  |
| sqlite_synth             | 2.52 us                                                | 2.75 us: 1.09x slower                                                 |
| unpickle                 | 13.7 us                                                | 15.0 us: 1.10x slower                                                 |
| xml_etree_generate       | 76.2 ms                                                | 83.8 ms: 1.10x slower                                                 |
| scimark_fft              | 328 ms                                                 | 361 ms: 1.10x slower                                                  |
| scimark_sor              | 118 ms                                                 | 130 ms: 1.10x slower                                                  |
| python_startup_no_site   | 6.01 ms                                                | 6.87 ms: 1.14x slower                                                 |
| pickle_list              | 4.11 us                                                | 4.74 us: 1.15x slower                                                 |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                 |
| async_generators         | 368 ms                                                 | 444 ms: 1.21x slower                                                  |
| telco                    | 6.58 ms                                                | 8.03 ms: 1.22x slower                                                 |
| dask                     | 360 ms                                                 | 529 ms: 1.47x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.05x faster                                                          |

Benchmark hidden because not significant (3): meteor_contest, unpickle_list, bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.14% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
