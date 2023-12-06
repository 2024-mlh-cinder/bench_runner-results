
# Results vs. 3.11.0

- fork: brandtbucher
- ref: kwnames_again
- machine: linux-x86_64
- commit hash: 3276185
- commit date: 2023-08-10
- overall geometric mean: 1.02x faster
- HPT reliability: 80.32%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.66 sec: 1.01x slower                                               |
| tornado_http   | 96.3 ms                                                | 97.7 ms: 1.01x slower                                                |
| Geometric mean | (ref)                                                  | 1.01x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 93.1 ms                                                | 92.5 ms: 1.01x faster                                                |
| pidigits       | 198 ms                                                 | 201 ms: 1.01x slower                                                 |
| float          | 77.2 ms                                                | 79.3 ms: 1.03x slower                                                |
| Geometric mean | (ref)                                                  | 1.01x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.76 ms: 1.06x faster                                                |
| regex_compile  | 138 ms                                                 | 140 ms: 1.01x slower                                                 |
| regex_dna      | 204 ms                                                 | 224 ms: 1.10x slower                                                 |
| regex_v8       | 22.0 ms                                                | 29.2 ms: 1.33x slower                                                |
| Geometric mean | (ref)                                                  | 1.09x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.84 ms: 1.28x faster                                                |
| json_loads           | 26.5 us                                                | 25.3 us: 1.05x faster                                                |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.05x faster                                                 |
| unpickle_pure_python | 228 us                                                 | 220 us: 1.03x faster                                                 |
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                               |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                 |
| pickle_pure_python   | 306 us                                                 | 308 us: 1.01x slower                                                 |
| pickle_dict          | 31.1 us                                                | 32.1 us: 1.03x slower                                                |
| unpickle_list        | 4.91 us                                                | 5.13 us: 1.05x slower                                                |
| pickle               | 10.1 us                                                | 10.6 us: 1.06x slower                                                |
| xml_etree_process    | 53.9 ms                                                | 57.9 ms: 1.08x slower                                                |
| xml_etree_generate   | 76.2 ms                                                | 83.4 ms: 1.09x slower                                                |
| unpickle             | 13.7 us                                                | 15.1 us: 1.11x slower                                                |
| pickle_list          | 4.11 us                                                | 4.64 us: 1.13x slower                                                |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.38 ms: 1.10x slower                                                |
| python_startup_no_site | 6.01 ms                                                | 6.86 ms: 1.14x slower                                                |
| Geometric mean         | (ref)                                                  | 1.12x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.3 ms: 1.12x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 151 us: 3.22x faster                                                 |
| generators               | 73.5 ms                                                | 29.9 ms: 2.45x faster                                                |
| asyncio_tcp              | 922 ms                                                 | 484 ms: 1.90x faster                                                 |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                               |
| json_dumps               | 12.6 ms                                                | 9.84 ms: 1.28x faster                                                |
| mypy2                    | 420 ms                                                 | 344 ms: 1.22x faster                                                 |
| async_tree_none          | 526 ms                                                 | 446 ms: 1.18x faster                                                 |
| coverage                 | 100 ms                                                 | 87.5 ms: 1.14x faster                                                |
| coroutines               | 25.5 ms                                                | 22.7 ms: 1.12x faster                                                |
| chaos                    | 69.2 ms                                                | 61.6 ms: 1.12x faster                                                |
| async_tree_memoization   | 627 ms                                                 | 572 ms: 1.10x faster                                                 |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                               |
| deltablue                | 3.67 ms                                                | 3.38 ms: 1.09x faster                                                |
| sqlglot_parse            | 1.40 ms                                                | 1.30 ms: 1.07x faster                                                |
| raytrace                 | 297 ms                                                 | 279 ms: 1.06x faster                                                 |
| crypto_pyaes             | 74.7 ms                                                | 70.2 ms: 1.06x faster                                                |
| regex_effbot             | 3.99 ms                                                | 3.76 ms: 1.06x faster                                                |
| sqlglot_transpile        | 1.70 ms                                                | 1.62 ms: 1.05x faster                                                |
| json_loads               | 26.5 us                                                | 25.3 us: 1.05x faster                                                |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.05x faster                                                 |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 709 ms: 1.04x faster                                                 |
| comprehensions           | 22.4 us                                                | 21.5 us: 1.04x faster                                                |
| unpickle_pure_python     | 228 us                                                 | 220 us: 1.03x faster                                                 |
| richards_super           | 56.8 ms                                                | 55.1 ms: 1.03x faster                                                |
| mdp                      | 2.62 sec                                               | 2.56 sec: 1.02x faster                                               |
| json                     | 4.94 ms                                                | 4.83 ms: 1.02x faster                                                |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                               |
| create_gc_cycles         | 1.49 ms                                                | 1.46 ms: 1.02x faster                                                |
| nqueens                  | 83.4 ms                                                | 82.3 ms: 1.01x faster                                                |
| meteor_contest           | 107 ms                                                 | 105 ms: 1.01x faster                                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 67.3 ms: 1.01x faster                                                |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                 |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.01x faster                                                 |
| nbody                    | 93.1 ms                                                | 92.5 ms: 1.01x faster                                                |
| fannkuch                 | 388 ms                                                 | 391 ms: 1.01x slower                                                 |
| bench_thread_pool        | 819 us                                                 | 825 us: 1.01x slower                                                 |
| pickle_pure_python       | 306 us                                                 | 308 us: 1.01x slower                                                 |
| sqlglot_optimize         | 53.1 ms                                                | 53.7 ms: 1.01x slower                                                |
| regex_compile            | 138 ms                                                 | 140 ms: 1.01x slower                                                 |
| docutils                 | 2.63 sec                                               | 2.66 sec: 1.01x slower                                               |
| pidigits                 | 198 ms                                                 | 201 ms: 1.01x slower                                                 |
| tornado_http             | 96.3 ms                                                | 97.7 ms: 1.01x slower                                                |
| scimark_lu               | 110 ms                                                 | 112 ms: 1.02x slower                                                 |
| go                       | 140 ms                                                 | 143 ms: 1.02x slower                                                 |
| float                    | 77.2 ms                                                | 79.3 ms: 1.03x slower                                                |
| gc_traversal             | 4.02 ms                                                | 4.14 ms: 1.03x slower                                                |
| pickle_dict              | 31.1 us                                                | 32.1 us: 1.03x slower                                                |
| logging_silent           | 101 ns                                                 | 104 ns: 1.03x slower                                                 |
| pycparser                | 1.18 sec                                               | 1.22 sec: 1.04x slower                                               |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                                |
| logging_simple           | 6.03 us                                                | 6.29 us: 1.04x slower                                                |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.04x slower                                               |
| scimark_sor              | 118 ms                                                 | 123 ms: 1.04x slower                                                 |
| unpickle_list            | 4.91 us                                                | 5.13 us: 1.05x slower                                                |
| deepcopy_memo            | 37.0 us                                                | 38.7 us: 1.05x slower                                                |
| logging_format           | 6.68 us                                                | 7.02 us: 1.05x slower                                                |
| deepcopy                 | 342 us                                                 | 361 us: 1.06x slower                                                 |
| pickle                   | 10.1 us                                                | 10.6 us: 1.06x slower                                                |
| pprint_safe_repr         | 701 ms                                                 | 745 ms: 1.06x slower                                                 |
| dulwich_log              | 63.7 ms                                                | 68.1 ms: 1.07x slower                                                |
| richards                 | 45.7 ms                                                | 49.0 ms: 1.07x slower                                                |
| xml_etree_process        | 53.9 ms                                                | 57.9 ms: 1.08x slower                                                |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.87 ms: 1.08x slower                                                |
| sqlite_synth             | 2.52 us                                                | 2.73 us: 1.08x slower                                                |
| deepcopy_reduce          | 2.94 us                                                | 3.19 us: 1.08x slower                                                |
| spectral_norm            | 100 ms                                                 | 109 ms: 1.09x slower                                                 |
| scimark_fft              | 328 ms                                                 | 359 ms: 1.09x slower                                                 |
| pyflate                  | 418 ms                                                 | 457 ms: 1.09x slower                                                 |
| xml_etree_generate       | 76.2 ms                                                | 83.4 ms: 1.09x slower                                                |
| regex_dna                | 204 ms                                                 | 224 ms: 1.10x slower                                                 |
| python_startup           | 8.52 ms                                                | 9.38 ms: 1.10x slower                                                |
| unpickle                 | 13.7 us                                                | 15.1 us: 1.11x slower                                                |
| mako                     | 10.1 ms                                                | 11.3 ms: 1.12x slower                                                |
| pickle_list              | 4.11 us                                                | 4.64 us: 1.13x slower                                                |
| python_startup_no_site   | 6.01 ms                                                | 6.86 ms: 1.14x slower                                                |
| telco                    | 6.58 ms                                                | 7.95 ms: 1.21x slower                                                |
| async_generators         | 368 ms                                                 | 448 ms: 1.22x slower                                                 |
| unpack_sequence          | 43.1 ns                                                | 53.6 ns: 1.24x slower                                                |
| regex_v8                 | 22.0 ms                                                | 29.2 ms: 1.33x slower                                                |
| dask                     | 360 ms                                                 | 535 ms: 1.49x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.02x faster                                                         |

Benchmark hidden because not significant (2): bench_mp_pool, hexiom
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 80.32% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
