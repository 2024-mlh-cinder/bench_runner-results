
# Results vs. 3.11.0

- fork: python
- ref: de5f8f7d13c0bbc723ea
- machine: linux-x86_64
- commit hash: de5f8f7
- commit date: 2023-09-11
- overall geometric mean: 1.05x faster
- HPT reliability: 97.40%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.62 sec: 1.00x faster                                                |
| tornado_http   | 96.3 ms                                                | 95.5 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                  |
| nbody          | 93.1 ms                                                | 89.2 ms: 1.04x faster                                                 |
| float          | 77.2 ms                                                | 79.9 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.39 ms: 1.18x faster                                                 |
| regex_compile  | 138 ms                                                 | 133 ms: 1.04x faster                                                  |
| regex_dna      | 204 ms                                                 | 205 ms: 1.00x slower                                                  |
| regex_v8       | 22.0 ms                                                | 23.7 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.92 ms: 1.27x faster                                                 |
| tomli_loads          | 2.22 sec                                               | 2.02 sec: 1.10x faster                                                |
| unpickle_pure_python | 228 us                                                 | 214 us: 1.07x faster                                                  |
| xml_etree_parse      | 158 ms                                                 | 151 ms: 1.05x faster                                                  |
| json_loads           | 26.5 us                                                | 25.3 us: 1.04x faster                                                 |
| pickle_pure_python   | 306 us                                                 | 297 us: 1.03x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                                  |
| pickle_dict          | 31.1 us                                                | 31.9 us: 1.03x slower                                                 |
| unpickle_list        | 4.91 us                                                | 5.05 us: 1.03x slower                                                 |
| pickle               | 10.1 us                                                | 10.5 us: 1.05x slower                                                 |
| unpickle             | 13.7 us                                                | 14.5 us: 1.06x slower                                                 |
| xml_etree_process    | 53.9 ms                                                | 57.1 ms: 1.06x slower                                                 |
| xml_etree_generate   | 76.2 ms                                                | 82.3 ms: 1.08x slower                                                 |
| pickle_list          | 4.11 us                                                | 4.63 us: 1.13x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.81 ms: 1.13x slower                                                 |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.7 ms: 1.06x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 142 us: 3.42x faster                                                  |
| generators               | 73.5 ms                                                | 28.6 ms: 2.57x faster                                                 |
| asyncio_tcp              | 922 ms                                                 | 486 ms: 1.89x faster                                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                                |
| json_dumps               | 12.6 ms                                                | 9.92 ms: 1.27x faster                                                 |
| mypy2                    | 420 ms                                                 | 337 ms: 1.25x faster                                                  |
| async_tree_none          | 526 ms                                                 | 437 ms: 1.21x faster                                                  |
| coroutines               | 25.5 ms                                                | 21.5 ms: 1.19x faster                                                 |
| regex_effbot             | 3.99 ms                                                | 3.39 ms: 1.18x faster                                                 |
| chaos                    | 69.2 ms                                                | 59.8 ms: 1.16x faster                                                 |
| coverage                 | 100 ms                                                 | 88.4 ms: 1.13x faster                                                 |
| deltablue                | 3.67 ms                                                | 3.25 ms: 1.13x faster                                                 |
| async_tree_memoization   | 627 ms                                                 | 564 ms: 1.11x faster                                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.26 ms: 1.11x faster                                                 |
| raytrace                 | 297 ms                                                 | 268 ms: 1.11x faster                                                  |
| comprehensions           | 22.4 us                                                | 20.5 us: 1.10x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 2.02 sec: 1.10x faster                                                |
| hexiom                   | 6.37 ms                                                | 5.82 ms: 1.09x faster                                                 |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                |
| crypto_pyaes             | 74.7 ms                                                | 68.7 ms: 1.09x faster                                                 |
| sqlglot_transpile        | 1.70 ms                                                | 1.57 ms: 1.09x faster                                                 |
| richards_super           | 56.8 ms                                                | 53.1 ms: 1.07x faster                                                 |
| unpickle_pure_python     | 228 us                                                 | 214 us: 1.07x faster                                                  |
| nqueens                  | 83.4 ms                                                | 78.4 ms: 1.06x faster                                                 |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                  |
| scimark_monte_carlo      | 68.1 ms                                                | 64.6 ms: 1.05x faster                                                 |
| xml_etree_parse          | 158 ms                                                 | 151 ms: 1.05x faster                                                  |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 705 ms: 1.05x faster                                                  |
| json_loads               | 26.5 us                                                | 25.3 us: 1.04x faster                                                 |
| nbody                    | 93.1 ms                                                | 89.2 ms: 1.04x faster                                                 |
| json                     | 4.94 ms                                                | 4.74 ms: 1.04x faster                                                 |
| logging_simple           | 6.03 us                                                | 5.80 us: 1.04x faster                                                 |
| fannkuch                 | 388 ms                                                 | 373 ms: 1.04x faster                                                  |
| sqlglot_normalize        | 108 ms                                                 | 104 ms: 1.04x faster                                                  |
| logging_format           | 6.68 us                                                | 6.45 us: 1.04x faster                                                 |
| regex_compile            | 138 ms                                                 | 133 ms: 1.04x faster                                                  |
| pycparser                | 1.18 sec                                               | 1.14 sec: 1.03x faster                                                |
| pickle_pure_python       | 306 us                                                 | 297 us: 1.03x faster                                                  |
| logging_silent           | 101 ns                                                 | 98.9 ns: 1.02x faster                                                 |
| go                       | 140 ms                                                 | 138 ms: 1.02x faster                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                                  |
| deepcopy_memo            | 37.0 us                                                | 36.4 us: 1.02x faster                                                 |
| sqlglot_optimize         | 53.1 ms                                                | 52.3 ms: 1.01x faster                                                 |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.01x faster                                                  |
| bench_thread_pool        | 819 us                                                 | 809 us: 1.01x faster                                                  |
| gc_traversal             | 4.02 ms                                                | 3.98 ms: 1.01x faster                                                 |
| tornado_http             | 96.3 ms                                                | 95.5 ms: 1.01x faster                                                 |
| docutils                 | 2.63 sec                                               | 2.62 sec: 1.00x faster                                                |
| regex_dna                | 204 ms                                                 | 205 ms: 1.00x slower                                                  |
| deepcopy                 | 342 us                                                 | 349 us: 1.02x slower                                                  |
| pickle_dict              | 31.1 us                                                | 31.9 us: 1.03x slower                                                 |
| richards                 | 45.7 ms                                                | 47.0 ms: 1.03x slower                                                 |
| unpickle_list            | 4.91 us                                                | 5.05 us: 1.03x slower                                                 |
| unpack_sequence          | 43.1 ns                                                | 44.4 ns: 1.03x slower                                                 |
| mdp                      | 2.62 sec                                               | 2.69 sec: 1.03x slower                                                |
| create_gc_cycles         | 1.49 ms                                                | 1.53 ms: 1.03x slower                                                 |
| spectral_norm            | 100 ms                                                 | 103 ms: 1.03x slower                                                  |
| float                    | 77.2 ms                                                | 79.9 ms: 1.03x slower                                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.67 ms: 1.04x slower                                                 |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.04x slower                                                |
| dulwich_log              | 63.7 ms                                                | 66.5 ms: 1.04x slower                                                 |
| pickle                   | 10.1 us                                                | 10.5 us: 1.05x slower                                                 |
| pprint_safe_repr         | 701 ms                                                 | 736 ms: 1.05x slower                                                  |
| pyflate                  | 418 ms                                                 | 443 ms: 1.06x slower                                                  |
| unpickle                 | 13.7 us                                                | 14.5 us: 1.06x slower                                                 |
| xml_etree_process        | 53.9 ms                                                | 57.1 ms: 1.06x slower                                                 |
| mako                     | 10.1 ms                                                | 10.7 ms: 1.06x slower                                                 |
| scimark_fft              | 328 ms                                                 | 350 ms: 1.07x slower                                                  |
| regex_v8                 | 22.0 ms                                                | 23.7 ms: 1.08x slower                                                 |
| xml_etree_generate       | 76.2 ms                                                | 82.3 ms: 1.08x slower                                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.18 us: 1.08x slower                                                 |
| sqlite_synth             | 2.52 us                                                | 2.80 us: 1.11x slower                                                 |
| pickle_list              | 4.11 us                                                | 4.63 us: 1.13x slower                                                 |
| python_startup_no_site   | 6.01 ms                                                | 6.81 ms: 1.13x slower                                                 |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                 |
| async_generators         | 368 ms                                                 | 447 ms: 1.21x slower                                                  |
| telco                    | 6.58 ms                                                | 8.04 ms: 1.22x slower                                                 |
| dask                     | 360 ms                                                 | 522 ms: 1.45x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.05x faster                                                          |

Benchmark hidden because not significant (4): scimark_lu, bench_mp_pool, pathlib, scimark_sor
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.40% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
