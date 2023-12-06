
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 0441b8d
- commit date: 2023-09-15
- overall geometric mean: 1.01x faster
- HPT reliability: 98.07%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.70 sec: 1.03x slower                                                  |
| tornado_http   | 96.3 ms                                                | 97.9 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 189 ms: 1.04x faster                                                    |
| float          | 77.2 ms                                                | 83.6 ms: 1.08x slower                                                   |
| nbody          | 93.1 ms                                                | 122 ms: 1.31x slower                                                    |
| Geometric mean | (ref)                                                  | 1.11x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.58 ms: 1.12x faster                                                   |
| regex_dna      | 204 ms                                                 | 213 ms: 1.05x slower                                                    |
| regex_compile  | 138 ms                                                 | 148 ms: 1.07x slower                                                    |
| regex_v8       | 22.0 ms                                                | 24.1 ms: 1.09x slower                                                   |
| Geometric mean | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.83 ms: 1.28x faster                                                   |
| json_loads           | 26.5 us                                                | 25.4 us: 1.04x faster                                                   |
| xml_etree_parse      | 158 ms                                                 | 154 ms: 1.03x faster                                                    |
| tomli_loads          | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                  |
| pickle_pure_python   | 306 us                                                 | 301 us: 1.02x faster                                                    |
| unpickle_list        | 4.91 us                                                | 5.01 us: 1.02x slower                                                   |
| pickle_dict          | 31.1 us                                                | 31.9 us: 1.02x slower                                                   |
| unpickle_pure_python | 228 us                                                 | 236 us: 1.04x slower                                                    |
| pickle               | 10.1 us                                                | 10.5 us: 1.04x slower                                                   |
| unpickle             | 13.7 us                                                | 14.7 us: 1.07x slower                                                   |
| xml_etree_process    | 53.9 ms                                                | 57.9 ms: 1.08x slower                                                   |
| xml_etree_generate   | 76.2 ms                                                | 84.8 ms: 1.11x slower                                                   |
| pickle_list          | 4.11 us                                                | 4.59 us: 1.12x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.92 ms: 1.15x slower                                                   |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.17x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.7 ms: 1.16x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 156 us: 3.13x faster                                                    |
| generators               | 73.5 ms                                                | 28.2 ms: 2.61x faster                                                   |
| asyncio_tcp              | 922 ms                                                 | 488 ms: 1.89x faster                                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                                  |
| json_dumps               | 12.6 ms                                                | 9.83 ms: 1.28x faster                                                   |
| mypy2                    | 420 ms                                                 | 355 ms: 1.18x faster                                                    |
| async_tree_none          | 526 ms                                                 | 451 ms: 1.17x faster                                                    |
| coroutines               | 25.5 ms                                                | 22.0 ms: 1.16x faster                                                   |
| coverage                 | 100 ms                                                 | 87.3 ms: 1.15x faster                                                   |
| regex_effbot             | 3.99 ms                                                | 3.58 ms: 1.12x faster                                                   |
| async_tree_memoization   | 627 ms                                                 | 578 ms: 1.08x faster                                                    |
| sqlglot_parse            | 1.40 ms                                                | 1.30 ms: 1.08x faster                                                   |
| raytrace                 | 297 ms                                                 | 276 ms: 1.08x faster                                                    |
| async_tree_io            | 1.30 sec                                               | 1.21 sec: 1.07x faster                                                  |
| deltablue                | 3.67 ms                                                | 3.46 ms: 1.06x faster                                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.62 ms: 1.05x faster                                                   |
| pidigits                 | 198 ms                                                 | 189 ms: 1.04x faster                                                    |
| json_loads               | 26.5 us                                                | 25.4 us: 1.04x faster                                                   |
| gc_traversal             | 4.02 ms                                                | 3.86 ms: 1.04x faster                                                   |
| richards_super           | 56.8 ms                                                | 54.8 ms: 1.04x faster                                                   |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 716 ms: 1.03x faster                                                    |
| xml_etree_parse          | 158 ms                                                 | 154 ms: 1.03x faster                                                    |
| tomli_loads              | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                  |
| pickle_pure_python       | 306 us                                                 | 301 us: 1.02x faster                                                    |
| crypto_pyaes             | 74.7 ms                                                | 74.3 ms: 1.00x faster                                                   |
| logging_simple           | 6.03 us                                                | 6.09 us: 1.01x slower                                                   |
| logging_format           | 6.68 us                                                | 6.75 us: 1.01x slower                                                   |
| logging_silent           | 101 ns                                                 | 102 ns: 1.01x slower                                                    |
| sqlglot_optimize         | 53.1 ms                                                | 53.9 ms: 1.01x slower                                                   |
| tornado_http             | 96.3 ms                                                | 97.9 ms: 1.02x slower                                                   |
| bench_thread_pool        | 819 us                                                 | 833 us: 1.02x slower                                                    |
| unpickle_list            | 4.91 us                                                | 5.01 us: 1.02x slower                                                   |
| pathlib                  | 18.2 ms                                                | 18.7 ms: 1.02x slower                                                   |
| pickle_dict              | 31.1 us                                                | 31.9 us: 1.02x slower                                                   |
| create_gc_cycles         | 1.49 ms                                                | 1.52 ms: 1.02x slower                                                   |
| docutils                 | 2.63 sec                                               | 2.70 sec: 1.03x slower                                                  |
| unpickle_pure_python     | 228 us                                                 | 236 us: 1.04x slower                                                    |
| scimark_lu               | 110 ms                                                 | 114 ms: 1.04x slower                                                    |
| deepcopy                 | 342 us                                                 | 355 us: 1.04x slower                                                    |
| pprint_pformat           | 1.46 sec                                               | 1.51 sec: 1.04x slower                                                  |
| chaos                    | 69.2 ms                                                | 72.0 ms: 1.04x slower                                                   |
| meteor_contest           | 107 ms                                                 | 111 ms: 1.04x slower                                                    |
| pickle                   | 10.1 us                                                | 10.5 us: 1.04x slower                                                   |
| regex_dna                | 204 ms                                                 | 213 ms: 1.05x slower                                                    |
| scimark_sor              | 118 ms                                                 | 123 ms: 1.05x slower                                                    |
| pprint_safe_repr         | 701 ms                                                 | 734 ms: 1.05x slower                                                    |
| richards                 | 45.7 ms                                                | 48.4 ms: 1.06x slower                                                   |
| go                       | 140 ms                                                 | 149 ms: 1.07x slower                                                    |
| mdp                      | 2.62 sec                                               | 2.79 sec: 1.07x slower                                                  |
| regex_compile            | 138 ms                                                 | 148 ms: 1.07x slower                                                    |
| unpickle                 | 13.7 us                                                | 14.7 us: 1.07x slower                                                   |
| xml_etree_process        | 53.9 ms                                                | 57.9 ms: 1.08x slower                                                   |
| deepcopy_memo            | 37.0 us                                                | 39.9 us: 1.08x slower                                                   |
| float                    | 77.2 ms                                                | 83.6 ms: 1.08x slower                                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.18 us: 1.08x slower                                                   |
| dulwich_log              | 63.7 ms                                                | 69.5 ms: 1.09x slower                                                   |
| regex_v8                 | 22.0 ms                                                | 24.1 ms: 1.09x slower                                                   |
| fannkuch                 | 388 ms                                                 | 427 ms: 1.10x slower                                                    |
| spectral_norm            | 100 ms                                                 | 111 ms: 1.11x slower                                                    |
| comprehensions           | 22.4 us                                                | 24.9 us: 1.11x slower                                                   |
| sqlite_synth             | 2.52 us                                                | 2.80 us: 1.11x slower                                                   |
| xml_etree_generate       | 76.2 ms                                                | 84.8 ms: 1.11x slower                                                   |
| pickle_list              | 4.11 us                                                | 4.59 us: 1.12x slower                                                   |
| pyflate                  | 418 ms                                                 | 475 ms: 1.14x slower                                                    |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.16 ms: 1.15x slower                                                   |
| unpack_sequence          | 43.1 ns                                                | 49.6 ns: 1.15x slower                                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.92 ms: 1.15x slower                                                   |
| hexiom                   | 6.37 ms                                                | 7.34 ms: 1.15x slower                                                   |
| mako                     | 10.1 ms                                                | 11.7 ms: 1.16x slower                                                   |
| scimark_fft              | 328 ms                                                 | 381 ms: 1.16x slower                                                    |
| nqueens                  | 83.4 ms                                                | 98.4 ms: 1.18x slower                                                   |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                   |
| telco                    | 6.58 ms                                                | 8.15 ms: 1.24x slower                                                   |
| async_generators         | 368 ms                                                 | 465 ms: 1.26x slower                                                    |
| nbody                    | 93.1 ms                                                | 122 ms: 1.31x slower                                                    |
| dask                     | 360 ms                                                 | 536 ms: 1.49x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                            |

Benchmark hidden because not significant (6): scimark_monte_carlo, json, sqlglot_normalize, xml_etree_iterparse, bench_mp_pool, pycparser
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 98.07% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
