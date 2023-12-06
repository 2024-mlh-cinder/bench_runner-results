
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0b4
- machine: linux-x86_64
- commit hash: 97a6a41
- commit date: 2023-07-11
- overall geometric mean: 1.06x faster \*
- HPT reliability: 99.24%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 267 ms: 1.00x slower                                       |
| docutils       | 2.69 sec                                               | 2.70 sec: 1.00x slower                                     |
| tornado_http   | 97.7 ms                                                | 99.1 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_io           | 1.31 sec                                               | 1.16 sec: 1.13x faster                                     |
| async_tree_none         | 532 ms                                                 | 472 ms: 1.13x faster                                       |
| async_tree_memoization  | 640 ms                                                 | 573 ms: 1.12x faster                                       |
| async_tree_cpu_io_mixed | 750 ms                                                 | 715 ms: 1.05x faster                                       |
| Geometric mean          | (ref)                                                  | 1.11x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 91.6 ms                                                | 89.2 ms: 1.03x faster                                      |
| pidigits       | 190 ms                                                 | 192 ms: 1.01x slower                                       |
| float          | 78.9 ms                                                | 80.7 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                  | 1.00x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_v8       | 22.9 ms                                                | 23.0 ms: 1.00x slower                                      |
| regex_compile  | 141 ms                                                 | 142 ms: 1.01x slower                                       |
| regex_dna      | 204 ms                                                 | 207 ms: 1.01x slower                                       |
| regex_effbot   | 3.45 ms                                                | 3.57 ms: 1.03x slower                                      |
| Geometric mean | (ref)                                                  | 1.01x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 9.66 ms: 1.39x faster                                      |
| json_loads           | 29.4 us                                                | 25.7 us: 1.15x faster                                      |
| unpickle_pure_python | 241 us                                                 | 217 us: 1.11x faster                                       |
| pickle_dict          | 34.8 us                                                | 31.6 us: 1.10x faster                                      |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                       |
| xml_etree_iterparse  | 109 ms                                                 | 102 ms: 1.06x faster                                       |
| unpickle_list        | 5.22 us                                                | 4.95 us: 1.06x faster                                      |
| pickle_pure_python   | 319 us                                                 | 306 us: 1.04x faster                                       |
| pickle               | 11.1 us                                                | 10.6 us: 1.04x faster                                      |
| tomli_loads          | 2.31 sec                                               | 2.23 sec: 1.04x faster                                     |
| pickle_list          | 4.65 us                                                | 4.59 us: 1.01x faster                                      |
| xml_etree_process    | 56.5 ms                                                | 59.4 ms: 1.05x slower                                      |
| xml_etree_generate   | 80.4 ms                                                | 85.0 ms: 1.06x slower                                      |
| unpickle             | 13.9 us                                                | 15.1 us: 1.09x slower                                      |
| Geometric mean       | (ref)                                                  | 1.06x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 9.35 ms: 1.08x slower                                      |
| python_startup_no_site | 6.09 ms                                                | 6.79 ms: 1.11x slower                                      |
| Geometric mean         | (ref)                                                  | 1.10x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 10.8 ms                                                | 10.9 ms: 1.00x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 521 us                                                 | 145 us: 3.60x faster                                       |
| generators               | 76.5 ms                                                | 30.5 ms: 2.50x faster                                      |
| asyncio_tcp_ssl          | 3.13 sec                                               | 1.80 sec: 1.74x faster                                     |
| asyncio_tcp              | 887 ms                                                 | 517 ms: 1.72x faster                                       |
| json_dumps               | 13.5 ms                                                | 9.66 ms: 1.39x faster                                      |
| mypy2                    | 427 ms                                                 | 343 ms: 1.25x faster                                       |
| richards_super           | 61.2 ms                                                | 49.2 ms: 1.25x faster                                      |
| coroutines               | 26.1 ms                                                | 22.5 ms: 1.16x faster                                      |
| json_loads               | 29.4 us                                                | 25.7 us: 1.15x faster                                      |
| comprehensions           | 23.6 us                                                | 20.7 us: 1.14x faster                                      |
| chaos                    | 71.4 ms                                                | 62.7 ms: 1.14x faster                                      |
| richards                 | 48.9 ms                                                | 43.3 ms: 1.13x faster                                      |
| async_tree_io            | 1.31 sec                                               | 1.16 sec: 1.13x faster                                     |
| async_tree_none          | 532 ms                                                 | 472 ms: 1.13x faster                                       |
| async_tree_memoization   | 640 ms                                                 | 573 ms: 1.12x faster                                       |
| hexiom                   | 6.74 ms                                                | 6.05 ms: 1.11x faster                                      |
| unpickle_pure_python     | 241 us                                                 | 217 us: 1.11x faster                                       |
| logging_silent           | 108 ns                                                 | 97.8 ns: 1.11x faster                                      |
| pickle_dict              | 34.8 us                                                | 31.6 us: 1.10x faster                                      |
| deltablue                | 3.80 ms                                                | 3.49 ms: 1.09x faster                                      |
| sqlglot_parse            | 1.43 ms                                                | 1.33 ms: 1.08x faster                                      |
| nqueens                  | 86.8 ms                                                | 80.9 ms: 1.07x faster                                      |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                       |
| sqlglot_transpile        | 1.75 ms                                                | 1.64 ms: 1.07x faster                                      |
| fannkuch                 | 410 ms                                                 | 385 ms: 1.06x faster                                       |
| xml_etree_iterparse      | 109 ms                                                 | 102 ms: 1.06x faster                                       |
| go                       | 143 ms                                                 | 135 ms: 1.06x faster                                       |
| json                     | 5.24 ms                                                | 4.95 ms: 1.06x faster                                      |
| unpickle_list            | 5.22 us                                                | 4.95 us: 1.06x faster                                      |
| async_tree_cpu_io_mixed  | 750 ms                                                 | 715 ms: 1.05x faster                                       |
| raytrace                 | 306 ms                                                 | 293 ms: 1.04x faster                                       |
| pickle_pure_python       | 319 us                                                 | 306 us: 1.04x faster                                       |
| meteor_contest           | 109 ms                                                 | 104 ms: 1.04x faster                                       |
| pickle                   | 11.1 us                                                | 10.6 us: 1.04x faster                                      |
| tomli_loads              | 2.31 sec                                               | 2.23 sec: 1.04x faster                                     |
| sqlglot_normalize        | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| spectral_norm            | 105 ms                                                 | 102 ms: 1.03x faster                                       |
| deepcopy_memo            | 38.9 us                                                | 37.9 us: 1.03x faster                                      |
| nbody                    | 91.6 ms                                                | 89.2 ms: 1.03x faster                                      |
| pycparser                | 1.20 sec                                               | 1.17 sec: 1.03x faster                                     |
| pprint_pformat           | 1.53 sec                                               | 1.49 sec: 1.03x faster                                     |
| sqlglot_optimize         | 55.2 ms                                                | 53.9 ms: 1.02x faster                                      |
| mdp                      | 2.79 sec                                               | 2.73 sec: 1.02x faster                                     |
| scimark_sor              | 121 ms                                                 | 119 ms: 1.02x faster                                       |
| pprint_safe_repr         | 743 ms                                                 | 731 ms: 1.02x faster                                       |
| deepcopy                 | 360 us                                                 | 355 us: 1.01x faster                                       |
| pickle_list              | 4.65 us                                                | 4.59 us: 1.01x faster                                      |
| deepcopy_reduce          | 3.14 us                                                | 3.11 us: 1.01x faster                                      |
| bench_thread_pool        | 833 us                                                 | 827 us: 1.01x faster                                       |
| logging_simple           | 6.24 us                                                | 6.21 us: 1.01x faster                                      |
| crypto_pyaes             | 77.5 ms                                                | 77.2 ms: 1.00x faster                                      |
| mako                     | 10.8 ms                                                | 10.9 ms: 1.00x slower                                      |
| docutils                 | 2.69 sec                                               | 2.70 sec: 1.00x slower                                     |
| 2to3                     | 266 ms                                                 | 267 ms: 1.00x slower                                       |
| regex_v8                 | 22.9 ms                                                | 23.0 ms: 1.00x slower                                      |
| regex_compile            | 141 ms                                                 | 142 ms: 1.01x slower                                       |
| pidigits                 | 190 ms                                                 | 192 ms: 1.01x slower                                       |
| scimark_monte_carlo      | 71.8 ms                                                | 72.4 ms: 1.01x slower                                      |
| regex_dna                | 204 ms                                                 | 207 ms: 1.01x slower                                       |
| sqlalchemy_imperative    | 18.2 ms                                                | 18.5 ms: 1.01x slower                                      |
| tornado_http             | 97.7 ms                                                | 99.1 ms: 1.01x slower                                      |
| logging_format           | 6.83 us                                                | 6.93 us: 1.02x slower                                      |
| telco                    | 6.72 ms                                                | 6.83 ms: 1.02x slower                                      |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.02x slower                                      |
| pyflate                  | 426 ms                                                 | 434 ms: 1.02x slower                                       |
| scimark_sparse_mat_mult  | 4.80 ms                                                | 4.91 ms: 1.02x slower                                      |
| float                    | 78.9 ms                                                | 80.7 ms: 1.02x slower                                      |
| sqlalchemy_declarative   | 141 ms                                                 | 144 ms: 1.02x slower                                       |
| create_gc_cycles         | 1.48 ms                                                | 1.51 ms: 1.03x slower                                      |
| regex_effbot             | 3.45 ms                                                | 3.57 ms: 1.03x slower                                      |
| scimark_fft              | 342 ms                                                 | 358 ms: 1.05x slower                                       |
| dulwich_log              | 64.9 ms                                                | 67.9 ms: 1.05x slower                                      |
| xml_etree_process        | 56.5 ms                                                | 59.4 ms: 1.05x slower                                      |
| xml_etree_generate       | 80.4 ms                                                | 85.0 ms: 1.06x slower                                      |
| sqlite_synth             | 2.58 us                                                | 2.74 us: 1.06x slower                                      |
| python_startup           | 8.69 ms                                                | 9.35 ms: 1.08x slower                                      |
| unpickle                 | 13.9 us                                                | 15.1 us: 1.09x slower                                      |
| python_startup_no_site   | 6.09 ms                                                | 6.79 ms: 1.11x slower                                      |
| unpack_sequence          | 43.3 ns                                                | 48.9 ns: 1.13x slower                                      |
| coverage                 | 81.2 ms                                                | 93.5 ms: 1.15x slower                                      |
| async_generators         | 375 ms                                                 | 448 ms: 1.19x slower                                       |
| dask                     | 365 ms                                                 | 535 ms: 1.47x slower                                       |
| Geometric mean           | (ref)                                                  | 1.06x faster                                               |

Benchmark hidden because not significant (3): bench_mp_pool, scimark_lu, gc_traversal
Ignored benchmarks (20) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.24% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
