
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b2
- machine: linux-x86_64
- commit hash: e6c0efa
- commit date: 2023-06-06
- overall geometric mean: 1.05x faster \*
- HPT reliability: 98.12%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 269 ms: 1.01x slower                                       |
| docutils       | 2.69 sec                                               | 2.72 sec: 1.01x slower                                     |
| tornado_http   | 97.7 ms                                                | 99.3 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 532 ms                                                 | 468 ms: 1.14x faster                                       |
| async_tree_io           | 1.31 sec                                               | 1.15 sec: 1.13x faster                                     |
| async_tree_memoization  | 640 ms                                                 | 570 ms: 1.12x faster                                       |
| async_tree_cpu_io_mixed | 750 ms                                                 | 708 ms: 1.06x faster                                       |
| Geometric mean          | (ref)                                                  | 1.11x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 91.6 ms                                                | 89.7 ms: 1.02x faster                                      |
| float          | 78.9 ms                                                | 80.3 ms: 1.02x slower                                      |
| pidigits       | 190 ms                                                 | 197 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 204 ms                                                 | 202 ms: 1.01x faster                                       |
| regex_compile  | 141 ms                                                 | 145 ms: 1.02x slower                                       |
| regex_effbot   | 3.45 ms                                                | 3.83 ms: 1.11x slower                                      |
| Geometric mean | (ref)                                                  | 1.03x slower                                               |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 9.69 ms: 1.39x faster                                      |
| json_loads           | 29.4 us                                                | 25.1 us: 1.17x faster                                      |
| unpickle_pure_python | 241 us                                                 | 217 us: 1.11x faster                                       |
| pickle_dict          | 34.8 us                                                | 31.3 us: 1.11x faster                                      |
| unpickle_list        | 5.22 us                                                | 4.90 us: 1.06x faster                                      |
| xml_etree_iterparse  | 109 ms                                                 | 104 ms: 1.04x faster                                       |
| xml_etree_parse      | 163 ms                                                 | 156 ms: 1.04x faster                                       |
| tomli_loads          | 2.31 sec                                               | 2.24 sec: 1.03x faster                                     |
| pickle               | 11.1 us                                                | 10.9 us: 1.02x faster                                      |
| pickle_pure_python   | 319 us                                                 | 314 us: 1.01x faster                                       |
| pickle_list          | 4.65 us                                                | 4.75 us: 1.02x slower                                      |
| xml_etree_process    | 56.5 ms                                                | 59.1 ms: 1.05x slower                                      |
| xml_etree_generate   | 80.4 ms                                                | 85.6 ms: 1.06x slower                                      |
| unpickle             | 13.9 us                                                | 15.0 us: 1.08x slower                                      |
| Geometric mean       | (ref)                                                  | 1.05x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 9.30 ms: 1.07x slower                                      |
| python_startup_no_site | 6.09 ms                                                | 6.76 ms: 1.11x slower                                      |
| Geometric mean         | (ref)                                                  | 1.09x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 10.8 ms                                                | 10.6 ms: 1.02x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 521 us                                                 | 148 us: 3.52x faster                                       |
| generators               | 76.5 ms                                                | 31.6 ms: 2.42x faster                                      |
| asyncio_tcp_ssl          | 3.13 sec                                               | 1.80 sec: 1.74x faster                                     |
| asyncio_tcp              | 887 ms                                                 | 511 ms: 1.74x faster                                       |
| json_dumps               | 13.5 ms                                                | 9.69 ms: 1.39x faster                                      |
| richards_super           | 61.2 ms                                                | 48.9 ms: 1.25x faster                                      |
| coroutines               | 26.1 ms                                                | 22.1 ms: 1.19x faster                                      |
| json_loads               | 29.4 us                                                | 25.1 us: 1.17x faster                                      |
| async_tree_none          | 532 ms                                                 | 468 ms: 1.14x faster                                       |
| richards                 | 48.9 ms                                                | 43.1 ms: 1.14x faster                                      |
| async_tree_io            | 1.31 sec                                               | 1.15 sec: 1.13x faster                                     |
| comprehensions           | 23.6 us                                                | 20.9 us: 1.13x faster                                      |
| async_tree_memoization   | 640 ms                                                 | 570 ms: 1.12x faster                                       |
| chaos                    | 71.4 ms                                                | 63.6 ms: 1.12x faster                                      |
| unpickle_pure_python     | 241 us                                                 | 217 us: 1.11x faster                                       |
| pickle_dict              | 34.8 us                                                | 31.3 us: 1.11x faster                                      |
| deltablue                | 3.80 ms                                                | 3.46 ms: 1.10x faster                                      |
| json                     | 5.24 ms                                                | 4.76 ms: 1.10x faster                                      |
| mdp                      | 2.79 sec                                               | 2.55 sec: 1.09x faster                                     |
| hexiom                   | 6.74 ms                                                | 6.19 ms: 1.09x faster                                      |
| unpickle_list            | 5.22 us                                                | 4.90 us: 1.06x faster                                      |
| sqlglot_parse            | 1.43 ms                                                | 1.35 ms: 1.06x faster                                      |
| async_tree_cpu_io_mixed  | 750 ms                                                 | 708 ms: 1.06x faster                                       |
| logging_silent           | 108 ns                                                 | 103 ns: 1.06x faster                                       |
| go                       | 143 ms                                                 | 136 ms: 1.05x faster                                       |
| nqueens                  | 86.8 ms                                                | 82.6 ms: 1.05x faster                                      |
| sqlglot_transpile        | 1.75 ms                                                | 1.67 ms: 1.05x faster                                      |
| xml_etree_iterparse      | 109 ms                                                 | 104 ms: 1.04x faster                                       |
| xml_etree_parse          | 163 ms                                                 | 156 ms: 1.04x faster                                       |
| raytrace                 | 306 ms                                                 | 296 ms: 1.04x faster                                       |
| tomli_loads              | 2.31 sec                                               | 2.24 sec: 1.03x faster                                     |
| sqlglot_normalize        | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| fannkuch                 | 410 ms                                                 | 398 ms: 1.03x faster                                       |
| meteor_contest           | 109 ms                                                 | 106 ms: 1.03x faster                                       |
| mako                     | 10.8 ms                                                | 10.6 ms: 1.02x faster                                      |
| deepcopy_memo            | 38.9 us                                                | 38.1 us: 1.02x faster                                      |
| nbody                    | 91.6 ms                                                | 89.7 ms: 1.02x faster                                      |
| pycparser                | 1.20 sec                                               | 1.17 sec: 1.02x faster                                     |
| sqlglot_optimize         | 55.2 ms                                                | 54.2 ms: 1.02x faster                                      |
| pickle                   | 11.1 us                                                | 10.9 us: 1.02x faster                                      |
| pickle_pure_python       | 319 us                                                 | 314 us: 1.01x faster                                       |
| pprint_pformat           | 1.53 sec                                               | 1.51 sec: 1.01x faster                                     |
| pprint_safe_repr         | 743 ms                                                 | 735 ms: 1.01x faster                                       |
| scimark_sor              | 121 ms                                                 | 120 ms: 1.01x faster                                       |
| regex_dna                | 204 ms                                                 | 202 ms: 1.01x faster                                       |
| spectral_norm            | 105 ms                                                 | 104 ms: 1.01x faster                                       |
| scimark_monte_carlo      | 71.8 ms                                                | 71.3 ms: 1.01x faster                                      |
| bench_thread_pool        | 833 us                                                 | 829 us: 1.01x faster                                       |
| deepcopy                 | 360 us                                                 | 359 us: 1.00x faster                                       |
| crypto_pyaes             | 77.5 ms                                                | 78.0 ms: 1.01x slower                                      |
| scimark_lu               | 112 ms                                                 | 113 ms: 1.01x slower                                       |
| 2to3                     | 266 ms                                                 | 269 ms: 1.01x slower                                       |
| docutils                 | 2.69 sec                                               | 2.72 sec: 1.01x slower                                     |
| tornado_http             | 97.7 ms                                                | 99.3 ms: 1.02x slower                                      |
| deepcopy_reduce          | 3.14 us                                                | 3.19 us: 1.02x slower                                      |
| scimark_sparse_mat_mult  | 4.80 ms                                                | 4.89 ms: 1.02x slower                                      |
| telco                    | 6.72 ms                                                | 6.83 ms: 1.02x slower                                      |
| float                    | 78.9 ms                                                | 80.3 ms: 1.02x slower                                      |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.02x slower                                      |
| logging_format           | 6.83 us                                                | 6.96 us: 1.02x slower                                      |
| pickle_list              | 4.65 us                                                | 4.75 us: 1.02x slower                                      |
| regex_compile            | 141 ms                                                 | 145 ms: 1.02x slower                                       |
| create_gc_cycles         | 1.48 ms                                                | 1.52 ms: 1.03x slower                                      |
| sqlalchemy_declarative   | 141 ms                                                 | 145 ms: 1.03x slower                                       |
| sqlalchemy_imperative    | 18.2 ms                                                | 18.8 ms: 1.03x slower                                      |
| pidigits                 | 190 ms                                                 | 197 ms: 1.04x slower                                       |
| xml_etree_process        | 56.5 ms                                                | 59.1 ms: 1.05x slower                                      |
| scimark_fft              | 342 ms                                                 | 358 ms: 1.05x slower                                       |
| pyflate                  | 426 ms                                                 | 448 ms: 1.05x slower                                       |
| dulwich_log              | 64.9 ms                                                | 68.4 ms: 1.05x slower                                      |
| sqlite_synth             | 2.58 us                                                | 2.73 us: 1.06x slower                                      |
| xml_etree_generate       | 80.4 ms                                                | 85.6 ms: 1.06x slower                                      |
| python_startup           | 8.69 ms                                                | 9.30 ms: 1.07x slower                                      |
| unpack_sequence          | 43.3 ns                                                | 46.7 ns: 1.08x slower                                      |
| unpickle                 | 13.9 us                                                | 15.0 us: 1.08x slower                                      |
| gc_traversal             | 3.90 ms                                                | 4.25 ms: 1.09x slower                                      |
| python_startup_no_site   | 6.09 ms                                                | 6.76 ms: 1.11x slower                                      |
| regex_effbot             | 3.45 ms                                                | 3.83 ms: 1.11x slower                                      |
| coverage                 | 81.2 ms                                                | 93.8 ms: 1.16x slower                                      |
| async_generators         | 375 ms                                                 | 450 ms: 1.20x slower                                       |
| dask                     | 365 ms                                                 | 536 ms: 1.47x slower                                       |
| Geometric mean           | (ref)                                                  | 1.05x faster                                               |

Benchmark hidden because not significant (4): bench_mp_pool, logging_simple, regex_v8, mypy2
Ignored benchmarks (20) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 98.12% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
