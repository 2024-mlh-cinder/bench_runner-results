
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.04x faster
- HPT reliability: 82.78%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.62 sec: 1.00x faster                                |
| tornado_http   | 96.3 ms                                                | 95.0 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 93.1 ms                                                | 89.3 ms: 1.04x faster                                 |
| float          | 77.2 ms                                                | 78.7 ms: 1.02x slower                                 |
| pidigits       | 198 ms                                                 | 203 ms: 1.02x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.68 ms: 1.09x faster                                 |
| regex_compile  | 138 ms                                                 | 135 ms: 1.02x faster                                  |
| regex_dna      | 204 ms                                                 | 221 ms: 1.08x slower                                  |
| regex_v8       | 22.0 ms                                                | 24.6 ms: 1.11x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.91 ms: 1.27x faster                                 |
| unpickle_pure_python | 228 us                                                 | 213 us: 1.07x faster                                  |
| xml_etree_parse      | 158 ms                                                 | 150 ms: 1.06x faster                                  |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                 |
| pickle_pure_python   | 306 us                                                 | 297 us: 1.03x faster                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| unpickle_list        | 4.91 us                                                | 4.84 us: 1.01x faster                                 |
| pickle               | 10.1 us                                                | 10.5 us: 1.04x slower                                 |
| pickle_dict          | 31.1 us                                                | 32.6 us: 1.05x slower                                 |
| xml_etree_process    | 53.9 ms                                                | 56.6 ms: 1.05x slower                                 |
| xml_etree_generate   | 76.2 ms                                                | 82.0 ms: 1.08x slower                                 |
| pickle_list          | 4.11 us                                                | 4.74 us: 1.15x slower                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.43 ms: 1.11x slower                                 |
| python_startup_no_site | 6.01 ms                                                | 6.93 ms: 1.15x slower                                 |
| Geometric mean         | (ref)                                                  | 1.13x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.0 ms: 1.09x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 146 us: 3.33x faster                                  |
| generators               | 73.5 ms                                                | 28.9 ms: 2.55x faster                                 |
| asyncio_tcp              | 922 ms                                                 | 485 ms: 1.90x faster                                  |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                |
| json_dumps               | 12.6 ms                                                | 9.91 ms: 1.27x faster                                 |
| mypy2                    | 420 ms                                                 | 339 ms: 1.24x faster                                  |
| async_tree_none          | 526 ms                                                 | 438 ms: 1.20x faster                                  |
| chaos                    | 69.2 ms                                                | 59.7 ms: 1.16x faster                                 |
| coverage                 | 100 ms                                                 | 86.9 ms: 1.15x faster                                 |
| coroutines               | 25.5 ms                                                | 22.2 ms: 1.15x faster                                 |
| deltablue                | 3.67 ms                                                | 3.25 ms: 1.13x faster                                 |
| sqlglot_parse            | 1.40 ms                                                | 1.27 ms: 1.11x faster                                 |
| async_tree_memoization   | 627 ms                                                 | 567 ms: 1.11x faster                                  |
| comprehensions           | 22.4 us                                                | 20.7 us: 1.09x faster                                 |
| regex_effbot             | 3.99 ms                                                | 3.68 ms: 1.09x faster                                 |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                |
| sqlglot_transpile        | 1.70 ms                                                | 1.57 ms: 1.08x faster                                 |
| raytrace                 | 297 ms                                                 | 276 ms: 1.07x faster                                  |
| unpickle_pure_python     | 228 us                                                 | 213 us: 1.07x faster                                  |
| richards_super           | 56.8 ms                                                | 53.3 ms: 1.07x faster                                 |
| crypto_pyaes             | 74.7 ms                                                | 70.3 ms: 1.06x faster                                 |
| hexiom                   | 6.37 ms                                                | 6.01 ms: 1.06x faster                                 |
| xml_etree_parse          | 158 ms                                                 | 150 ms: 1.06x faster                                  |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 705 ms: 1.05x faster                                  |
| nqueens                  | 83.4 ms                                                | 79.6 ms: 1.05x faster                                 |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                 |
| nbody                    | 93.1 ms                                                | 89.3 ms: 1.04x faster                                 |
| sqlglot_normalize        | 108 ms                                                 | 104 ms: 1.04x faster                                  |
| logging_format           | 6.68 us                                                | 6.48 us: 1.03x faster                                 |
| pickle_pure_python       | 306 us                                                 | 297 us: 1.03x faster                                  |
| logging_simple           | 6.03 us                                                | 5.87 us: 1.03x faster                                 |
| scimark_monte_carlo      | 68.1 ms                                                | 66.4 ms: 1.03x faster                                 |
| regex_compile            | 138 ms                                                 | 135 ms: 1.02x faster                                  |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| fannkuch                 | 388 ms                                                 | 382 ms: 1.01x faster                                  |
| tornado_http             | 96.3 ms                                                | 95.0 ms: 1.01x faster                                 |
| unpickle_list            | 4.91 us                                                | 4.84 us: 1.01x faster                                 |
| sqlglot_optimize         | 53.1 ms                                                | 52.4 ms: 1.01x faster                                 |
| scimark_lu               | 110 ms                                                 | 109 ms: 1.01x faster                                  |
| go                       | 140 ms                                                 | 138 ms: 1.01x faster                                  |
| docutils                 | 2.63 sec                                               | 2.62 sec: 1.00x faster                                |
| deepcopy                 | 342 us                                                 | 345 us: 1.01x slower                                  |
| pycparser                | 1.18 sec                                               | 1.20 sec: 1.01x slower                                |
| float                    | 77.2 ms                                                | 78.7 ms: 1.02x slower                                 |
| pprint_pformat           | 1.46 sec                                               | 1.49 sec: 1.02x slower                                |
| logging_silent           | 101 ns                                                 | 103 ns: 1.02x slower                                  |
| pidigits                 | 198 ms                                                 | 203 ms: 1.02x slower                                  |
| richards                 | 45.7 ms                                                | 47.0 ms: 1.03x slower                                 |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.64 ms: 1.03x slower                                 |
| pathlib                  | 18.2 ms                                                | 18.8 ms: 1.03x slower                                 |
| gc_traversal             | 4.02 ms                                                | 4.18 ms: 1.04x slower                                 |
| pprint_safe_repr         | 701 ms                                                 | 730 ms: 1.04x slower                                  |
| pickle                   | 10.1 us                                                | 10.5 us: 1.04x slower                                 |
| mdp                      | 2.62 sec                                               | 2.73 sec: 1.04x slower                                |
| pickle_dict              | 31.1 us                                                | 32.6 us: 1.05x slower                                 |
| dulwich_log              | 63.7 ms                                                | 66.7 ms: 1.05x slower                                 |
| xml_etree_process        | 53.9 ms                                                | 56.6 ms: 1.05x slower                                 |
| deepcopy_reduce          | 2.94 us                                                | 3.09 us: 1.05x slower                                 |
| pyflate                  | 418 ms                                                 | 442 ms: 1.06x slower                                  |
| unpack_sequence          | 43.1 ns                                                | 45.7 ns: 1.06x slower                                 |
| xml_etree_generate       | 76.2 ms                                                | 82.0 ms: 1.08x slower                                 |
| scimark_fft              | 328 ms                                                 | 355 ms: 1.08x slower                                  |
| regex_dna                | 204 ms                                                 | 221 ms: 1.08x slower                                  |
| spectral_norm            | 100 ms                                                 | 108 ms: 1.08x slower                                  |
| mako                     | 10.1 ms                                                | 11.0 ms: 1.09x slower                                 |
| sqlite_synth             | 2.52 us                                                | 2.77 us: 1.10x slower                                 |
| python_startup           | 8.52 ms                                                | 9.43 ms: 1.11x slower                                 |
| regex_v8                 | 22.0 ms                                                | 24.6 ms: 1.11x slower                                 |
| python_startup_no_site   | 6.01 ms                                                | 6.93 ms: 1.15x slower                                 |
| pickle_list              | 4.11 us                                                | 4.74 us: 1.15x slower                                 |
| telco                    | 6.58 ms                                                | 8.00 ms: 1.22x slower                                 |
| async_generators         | 368 ms                                                 | 448 ms: 1.22x slower                                  |
| dask                     | 360 ms                                                 | 523 ms: 1.45x slower                                  |
| Geometric mean           | (ref)                                                  | 1.04x faster                                          |

Benchmark hidden because not significant (8): meteor_contest, deepcopy_memo, json, bench_thread_pool, bench_mp_pool, scimark_sor, create_gc_cycles, unpickle
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 82.78% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
