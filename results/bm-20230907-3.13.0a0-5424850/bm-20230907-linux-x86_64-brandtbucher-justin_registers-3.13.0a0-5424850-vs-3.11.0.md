
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 5424850
- commit date: 2023-09-07
- overall geometric mean: 1.00x faster
- HPT reliability: 99.15%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.72 sec: 1.04x slower                                                  |
| tornado_http   | 96.3 ms                                                | 98.0 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                    |
| float          | 77.2 ms                                                | 82.9 ms: 1.07x slower                                                   |
| nbody          | 93.1 ms                                                | 103 ms: 1.10x slower                                                    |
| Geometric mean | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.63 ms: 1.10x faster                                                   |
| regex_compile  | 138 ms                                                 | 147 ms: 1.07x slower                                                    |
| regex_dna      | 204 ms                                                 | 226 ms: 1.11x slower                                                    |
| regex_v8       | 22.0 ms                                                | 25.2 ms: 1.14x slower                                                   |
| Geometric mean | (ref)                                                  | 1.05x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.91 ms: 1.27x faster                                                   |
| json_loads           | 26.5 us                                                | 25.3 us: 1.05x faster                                                   |
| xml_etree_parse      | 158 ms                                                 | 152 ms: 1.04x faster                                                    |
| pickle_pure_python   | 306 us                                                 | 303 us: 1.01x faster                                                    |
| unpickle_list        | 4.91 us                                                | 4.93 us: 1.01x slower                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                    |
| tomli_loads          | 2.22 sec                                               | 2.26 sec: 1.02x slower                                                  |
| pickle_dict          | 31.1 us                                                | 32.2 us: 1.03x slower                                                   |
| unpickle_pure_python | 228 us                                                 | 237 us: 1.04x slower                                                    |
| pickle               | 10.1 us                                                | 10.8 us: 1.08x slower                                                   |
| unpickle             | 13.7 us                                                | 14.8 us: 1.08x slower                                                   |
| xml_etree_process    | 53.9 ms                                                | 58.3 ms: 1.08x slower                                                   |
| xml_etree_generate   | 76.2 ms                                                | 84.5 ms: 1.11x slower                                                   |
| pickle_list          | 4.11 us                                                | 4.83 us: 1.17x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 8.52 ms                                                | 9.59 ms: 1.13x slower                                                   |
| python_startup_no_site | 6.01 ms                                                | 7.06 ms: 1.17x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.6 ms: 1.15x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 158 us: 3.07x faster                                                    |
| generators               | 73.5 ms                                                | 30.0 ms: 2.45x faster                                                   |
| asyncio_tcp              | 922 ms                                                 | 492 ms: 1.88x faster                                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.81 sec: 1.74x faster                                                  |
| json_dumps               | 12.6 ms                                                | 9.91 ms: 1.27x faster                                                   |
| async_tree_none          | 526 ms                                                 | 445 ms: 1.18x faster                                                    |
| mypy2                    | 420 ms                                                 | 357 ms: 1.18x faster                                                    |
| coroutines               | 25.5 ms                                                | 22.1 ms: 1.16x faster                                                   |
| coverage                 | 100 ms                                                 | 88.9 ms: 1.12x faster                                                   |
| regex_effbot             | 3.99 ms                                                | 3.63 ms: 1.10x faster                                                   |
| async_tree_memoization   | 627 ms                                                 | 573 ms: 1.10x faster                                                    |
| gc_traversal             | 4.02 ms                                                | 3.67 ms: 1.09x faster                                                   |
| async_tree_io            | 1.30 sec                                               | 1.20 sec: 1.08x faster                                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.30 ms: 1.07x faster                                                   |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                    |
| deltablue                | 3.67 ms                                                | 3.49 ms: 1.05x faster                                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.62 ms: 1.05x faster                                                   |
| raytrace                 | 297 ms                                                 | 283 ms: 1.05x faster                                                    |
| json_loads               | 26.5 us                                                | 25.3 us: 1.05x faster                                                   |
| xml_etree_parse          | 158 ms                                                 | 152 ms: 1.04x faster                                                    |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 709 ms: 1.04x faster                                                    |
| crypto_pyaes             | 74.7 ms                                                | 72.7 ms: 1.03x faster                                                   |
| richards_super           | 56.8 ms                                                | 55.3 ms: 1.03x faster                                                   |
| chaos                    | 69.2 ms                                                | 67.5 ms: 1.03x faster                                                   |
| json                     | 4.94 ms                                                | 4.86 ms: 1.02x faster                                                   |
| pickle_pure_python       | 306 us                                                 | 303 us: 1.01x faster                                                    |
| logging_format           | 6.68 us                                                | 6.62 us: 1.01x faster                                                   |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.01x faster                                                    |
| create_gc_cycles         | 1.49 ms                                                | 1.49 ms: 1.00x slower                                                   |
| unpickle_list            | 4.91 us                                                | 4.93 us: 1.01x slower                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                    |
| scimark_monte_carlo      | 68.1 ms                                                | 68.7 ms: 1.01x slower                                                   |
| tomli_loads              | 2.22 sec                                               | 2.26 sec: 1.02x slower                                                  |
| tornado_http             | 96.3 ms                                                | 98.0 ms: 1.02x slower                                                   |
| sqlglot_optimize         | 53.1 ms                                                | 54.2 ms: 1.02x slower                                                   |
| bench_thread_pool        | 819 us                                                 | 844 us: 1.03x slower                                                    |
| pickle_dict              | 31.1 us                                                | 32.2 us: 1.03x slower                                                   |
| docutils                 | 2.63 sec                                               | 2.72 sec: 1.04x slower                                                  |
| pathlib                  | 18.2 ms                                                | 18.9 ms: 1.04x slower                                                   |
| unpickle_pure_python     | 228 us                                                 | 237 us: 1.04x slower                                                    |
| deepcopy                 | 342 us                                                 | 358 us: 1.05x slower                                                    |
| pycparser                | 1.18 sec                                               | 1.24 sec: 1.05x slower                                                  |
| mdp                      | 2.62 sec                                               | 2.76 sec: 1.06x slower                                                  |
| scimark_sor              | 118 ms                                                 | 125 ms: 1.06x slower                                                    |
| meteor_contest           | 107 ms                                                 | 113 ms: 1.06x slower                                                    |
| scimark_lu               | 110 ms                                                 | 117 ms: 1.06x slower                                                    |
| pprint_pformat           | 1.46 sec                                               | 1.55 sec: 1.06x slower                                                  |
| regex_compile            | 138 ms                                                 | 147 ms: 1.07x slower                                                    |
| float                    | 77.2 ms                                                | 82.9 ms: 1.07x slower                                                   |
| pickle                   | 10.1 us                                                | 10.8 us: 1.08x slower                                                   |
| pprint_safe_repr         | 701 ms                                                 | 756 ms: 1.08x slower                                                    |
| deepcopy_reduce          | 2.94 us                                                | 3.18 us: 1.08x slower                                                   |
| unpickle                 | 13.7 us                                                | 14.8 us: 1.08x slower                                                   |
| xml_etree_process        | 53.9 ms                                                | 58.3 ms: 1.08x slower                                                   |
| dulwich_log              | 63.7 ms                                                | 69.0 ms: 1.08x slower                                                   |
| richards                 | 45.7 ms                                                | 49.6 ms: 1.09x slower                                                   |
| logging_silent           | 101 ns                                                 | 110 ns: 1.09x slower                                                    |
| go                       | 140 ms                                                 | 152 ms: 1.09x slower                                                    |
| sqlite_synth             | 2.52 us                                                | 2.76 us: 1.10x slower                                                   |
| spectral_norm            | 100 ms                                                 | 110 ms: 1.10x slower                                                    |
| fannkuch                 | 388 ms                                                 | 426 ms: 1.10x slower                                                    |
| deepcopy_memo            | 37.0 us                                                | 40.7 us: 1.10x slower                                                   |
| nbody                    | 93.1 ms                                                | 103 ms: 1.10x slower                                                    |
| xml_etree_generate       | 76.2 ms                                                | 84.5 ms: 1.11x slower                                                   |
| regex_dna                | 204 ms                                                 | 226 ms: 1.11x slower                                                    |
| comprehensions           | 22.4 us                                                | 25.1 us: 1.12x slower                                                   |
| python_startup           | 8.52 ms                                                | 9.59 ms: 1.13x slower                                                   |
| scimark_fft              | 328 ms                                                 | 374 ms: 1.14x slower                                                    |
| nqueens                  | 83.4 ms                                                | 94.9 ms: 1.14x slower                                                   |
| regex_v8                 | 22.0 ms                                                | 25.2 ms: 1.14x slower                                                   |
| hexiom                   | 6.37 ms                                                | 7.29 ms: 1.14x slower                                                   |
| mako                     | 10.1 ms                                                | 11.6 ms: 1.15x slower                                                   |
| pyflate                  | 418 ms                                                 | 482 ms: 1.15x slower                                                    |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.25 ms: 1.17x slower                                                   |
| pickle_list              | 4.11 us                                                | 4.83 us: 1.17x slower                                                   |
| python_startup_no_site   | 6.01 ms                                                | 7.06 ms: 1.17x slower                                                   |
| unpack_sequence          | 43.1 ns                                                | 51.5 ns: 1.19x slower                                                   |
| telco                    | 6.58 ms                                                | 8.35 ms: 1.27x slower                                                   |
| async_generators         | 368 ms                                                 | 471 ms: 1.28x slower                                                    |
| dask                     | 360 ms                                                 | 535 ms: 1.49x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                            |

Benchmark hidden because not significant (2): logging_simple, bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.15% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
