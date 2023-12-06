
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 2b170f6
- commit date: 2023-09-13
- overall geometric mean: 1.00x faster
- HPT reliability: 97.70%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.69 sec: 1.02x slower                                                  |
| tornado_http   | 96.3 ms                                                | 97.4 ms: 1.01x slower                                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 189 ms: 1.05x faster                                                    |
| float          | 77.2 ms                                                | 84.3 ms: 1.09x slower                                                   |
| nbody          | 93.1 ms                                                | 127 ms: 1.36x slower                                                    |
| Geometric mean | (ref)                                                  | 1.12x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.57 ms: 1.12x faster                                                   |
| regex_dna      | 204 ms                                                 | 209 ms: 1.03x slower                                                    |
| regex_compile  | 138 ms                                                 | 148 ms: 1.08x slower                                                    |
| regex_v8       | 22.0 ms                                                | 24.1 ms: 1.09x slower                                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.96 ms: 1.26x faster                                                   |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                                    |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                                   |
| pickle_pure_python   | 306 us                                                 | 298 us: 1.03x faster                                                    |
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                    |
| unpickle_list        | 4.91 us                                                | 4.94 us: 1.01x slower                                                   |
| pickle_dict          | 31.1 us                                                | 31.7 us: 1.02x slower                                                   |
| unpickle_pure_python | 228 us                                                 | 234 us: 1.03x slower                                                    |
| xml_etree_process    | 53.9 ms                                                | 57.8 ms: 1.07x slower                                                   |
| pickle               | 10.1 us                                                | 10.8 us: 1.08x slower                                                   |
| xml_etree_generate   | 76.2 ms                                                | 83.7 ms: 1.10x slower                                                   |
| unpickle             | 13.7 us                                                | 15.5 us: 1.13x slower                                                   |
| pickle_list          | 4.11 us                                                | 4.67 us: 1.13x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.89 ms: 1.15x slower                                                   |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.17x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.7 ms: 1.16x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 155 us: 3.14x faster                                                    |
| generators               | 73.5 ms                                                | 27.8 ms: 2.64x faster                                                   |
| asyncio_tcp              | 922 ms                                                 | 490 ms: 1.88x faster                                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                                  |
| json_dumps               | 12.6 ms                                                | 9.96 ms: 1.26x faster                                                   |
| mypy2                    | 420 ms                                                 | 358 ms: 1.17x faster                                                    |
| async_tree_none          | 526 ms                                                 | 450 ms: 1.17x faster                                                    |
| coroutines               | 25.5 ms                                                | 22.1 ms: 1.15x faster                                                   |
| coverage                 | 100 ms                                                 | 86.8 ms: 1.15x faster                                                   |
| regex_effbot             | 3.99 ms                                                | 3.57 ms: 1.12x faster                                                   |
| async_tree_memoization   | 627 ms                                                 | 572 ms: 1.10x faster                                                    |
| gc_traversal             | 4.02 ms                                                | 3.69 ms: 1.09x faster                                                   |
| async_tree_io            | 1.30 sec                                               | 1.21 sec: 1.07x faster                                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.31 ms: 1.07x faster                                                   |
| raytrace                 | 297 ms                                                 | 277 ms: 1.07x faster                                                    |
| deltablue                | 3.67 ms                                                | 3.48 ms: 1.06x faster                                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.63 ms: 1.05x faster                                                   |
| pidigits                 | 198 ms                                                 | 189 ms: 1.05x faster                                                    |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                    |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                                   |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 713 ms: 1.04x faster                                                    |
| json                     | 4.94 ms                                                | 4.82 ms: 1.03x faster                                                   |
| pickle_pure_python       | 306 us                                                 | 298 us: 1.03x faster                                                    |
| richards_super           | 56.8 ms                                                | 55.4 ms: 1.02x faster                                                   |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                    |
| scimark_monte_carlo      | 68.1 ms                                                | 67.5 ms: 1.01x faster                                                   |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.01x faster                                                    |
| mdp                      | 2.62 sec                                               | 2.63 sec: 1.01x slower                                                  |
| unpickle_list            | 4.91 us                                                | 4.94 us: 1.01x slower                                                   |
| create_gc_cycles         | 1.49 ms                                                | 1.50 ms: 1.01x slower                                                   |
| tornado_http             | 96.3 ms                                                | 97.4 ms: 1.01x slower                                                   |
| sqlglot_optimize         | 53.1 ms                                                | 53.8 ms: 1.01x slower                                                   |
| pickle_dict              | 31.1 us                                                | 31.7 us: 1.02x slower                                                   |
| bench_thread_pool        | 819 us                                                 | 838 us: 1.02x slower                                                    |
| docutils                 | 2.63 sec                                               | 2.69 sec: 1.02x slower                                                  |
| unpickle_pure_python     | 228 us                                                 | 234 us: 1.03x slower                                                    |
| pycparser                | 1.18 sec                                               | 1.21 sec: 1.03x slower                                                  |
| regex_dna                | 204 ms                                                 | 209 ms: 1.03x slower                                                    |
| scimark_lu               | 110 ms                                                 | 113 ms: 1.03x slower                                                    |
| logging_silent           | 101 ns                                                 | 105 ns: 1.04x slower                                                    |
| pprint_pformat           | 1.46 sec                                               | 1.51 sec: 1.04x slower                                                  |
| meteor_contest           | 107 ms                                                 | 111 ms: 1.04x slower                                                    |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                                   |
| chaos                    | 69.2 ms                                                | 72.7 ms: 1.05x slower                                                   |
| scimark_sor              | 118 ms                                                 | 124 ms: 1.05x slower                                                    |
| pprint_safe_repr         | 701 ms                                                 | 741 ms: 1.06x slower                                                    |
| deepcopy                 | 342 us                                                 | 362 us: 1.06x slower                                                    |
| richards                 | 45.7 ms                                                | 48.4 ms: 1.06x slower                                                   |
| xml_etree_process        | 53.9 ms                                                | 57.8 ms: 1.07x slower                                                   |
| regex_compile            | 138 ms                                                 | 148 ms: 1.08x slower                                                    |
| pickle                   | 10.1 us                                                | 10.8 us: 1.08x slower                                                   |
| go                       | 140 ms                                                 | 151 ms: 1.08x slower                                                    |
| deepcopy_memo            | 37.0 us                                                | 40.1 us: 1.08x slower                                                   |
| dulwich_log              | 63.7 ms                                                | 69.0 ms: 1.08x slower                                                   |
| float                    | 77.2 ms                                                | 84.3 ms: 1.09x slower                                                   |
| regex_v8                 | 22.0 ms                                                | 24.1 ms: 1.09x slower                                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.22 us: 1.10x slower                                                   |
| xml_etree_generate       | 76.2 ms                                                | 83.7 ms: 1.10x slower                                                   |
| sqlite_synth             | 2.52 us                                                | 2.81 us: 1.11x slower                                                   |
| spectral_norm            | 100 ms                                                 | 112 ms: 1.12x slower                                                    |
| fannkuch                 | 388 ms                                                 | 435 ms: 1.12x slower                                                    |
| comprehensions           | 22.4 us                                                | 25.4 us: 1.13x slower                                                   |
| unpickle                 | 13.7 us                                                | 15.5 us: 1.13x slower                                                   |
| pickle_list              | 4.11 us                                                | 4.67 us: 1.13x slower                                                   |
| pyflate                  | 418 ms                                                 | 477 ms: 1.14x slower                                                    |
| hexiom                   | 6.37 ms                                                | 7.28 ms: 1.14x slower                                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.89 ms: 1.15x slower                                                   |
| nqueens                  | 83.4 ms                                                | 95.7 ms: 1.15x slower                                                   |
| mako                     | 10.1 ms                                                | 11.7 ms: 1.16x slower                                                   |
| scimark_fft              | 328 ms                                                 | 386 ms: 1.17x slower                                                    |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.38 ms: 1.20x slower                                                   |
| telco                    | 6.58 ms                                                | 8.13 ms: 1.23x slower                                                   |
| async_generators         | 368 ms                                                 | 470 ms: 1.28x slower                                                    |
| unpack_sequence          | 43.1 ns                                                | 55.2 ns: 1.28x slower                                                   |
| nbody                    | 93.1 ms                                                | 127 ms: 1.36x slower                                                    |
| dask                     | 360 ms                                                 | 535 ms: 1.49x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                            |

Benchmark hidden because not significant (4): bench_mp_pool, logging_simple, crypto_pyaes, logging_format
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.70% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
