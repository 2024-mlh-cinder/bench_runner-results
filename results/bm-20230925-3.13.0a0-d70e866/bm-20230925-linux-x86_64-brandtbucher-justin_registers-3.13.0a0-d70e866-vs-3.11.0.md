
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: d70e866
- commit date: 2023-09-25
- overall geometric mean: 1.03x faster
- HPT reliability: 82.18%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.66 sec: 1.01x slower                                                  |
| tornado_http   | 96.3 ms                                                | 96.9 ms: 1.01x slower                                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                    |
| nbody          | 93.1 ms                                                | 95.9 ms: 1.03x slower                                                   |
| float          | 77.2 ms                                                | 82.3 ms: 1.07x slower                                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.45 ms: 1.16x faster                                                   |
| regex_dna      | 204 ms                                                 | 201 ms: 1.01x faster                                                    |
| regex_compile  | 138 ms                                                 | 144 ms: 1.04x slower                                                    |
| regex_v8       | 22.0 ms                                                | 23.2 ms: 1.05x slower                                                   |
| Geometric mean | (ref)                                                  | 1.02x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.91 ms: 1.27x faster                                                   |
| tomli_loads          | 2.22 sec                                               | 2.02 sec: 1.10x faster                                                  |
| json_loads           | 26.5 us                                                | 25.1 us: 1.05x faster                                                   |
| xml_etree_parse      | 158 ms                                                 | 153 ms: 1.04x faster                                                    |
| pickle_pure_python   | 306 us                                                 | 297 us: 1.03x faster                                                    |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                    |
| unpickle_list        | 4.91 us                                                | 4.88 us: 1.01x faster                                                   |
| unpickle_pure_python | 228 us                                                 | 227 us: 1.00x faster                                                    |
| pickle_dict          | 31.1 us                                                | 31.2 us: 1.00x slower                                                   |
| pickle               | 10.1 us                                                | 10.2 us: 1.01x slower                                                   |
| xml_etree_process    | 53.9 ms                                                | 57.3 ms: 1.06x slower                                                   |
| xml_etree_generate   | 76.2 ms                                                | 83.3 ms: 1.09x slower                                                   |
| unpickle             | 13.7 us                                                | 15.0 us: 1.10x slower                                                   |
| pickle_list          | 4.11 us                                                | 4.66 us: 1.13x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.90 ms: 1.15x slower                                                   |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.17x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.5 ms: 1.14x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 151 us: 3.21x faster                                                    |
| generators               | 73.5 ms                                                | 28.2 ms: 2.60x faster                                                   |
| asyncio_tcp              | 922 ms                                                 | 498 ms: 1.85x faster                                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.81 sec: 1.74x faster                                                  |
| json_dumps               | 12.6 ms                                                | 9.91 ms: 1.27x faster                                                   |
| mypy2                    | 420 ms                                                 | 352 ms: 1.19x faster                                                    |
| async_tree_none          | 526 ms                                                 | 448 ms: 1.18x faster                                                    |
| coverage                 | 100 ms                                                 | 86.3 ms: 1.16x faster                                                   |
| regex_effbot             | 3.99 ms                                                | 3.45 ms: 1.16x faster                                                   |
| coroutines               | 25.5 ms                                                | 22.2 ms: 1.15x faster                                                   |
| async_tree_memoization   | 627 ms                                                 | 569 ms: 1.10x faster                                                    |
| tomli_loads              | 2.22 sec                                               | 2.02 sec: 1.10x faster                                                  |
| raytrace                 | 297 ms                                                 | 272 ms: 1.09x faster                                                    |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                  |
| deltablue                | 3.67 ms                                                | 3.41 ms: 1.08x faster                                                   |
| sqlglot_parse            | 1.40 ms                                                | 1.30 ms: 1.07x faster                                                   |
| chaos                    | 69.2 ms                                                | 65.3 ms: 1.06x faster                                                   |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                    |
| json_loads               | 26.5 us                                                | 25.1 us: 1.05x faster                                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.63 ms: 1.05x faster                                                   |
| crypto_pyaes             | 74.7 ms                                                | 71.5 ms: 1.04x faster                                                   |
| richards_super           | 56.8 ms                                                | 54.4 ms: 1.04x faster                                                   |
| xml_etree_parse          | 158 ms                                                 | 153 ms: 1.04x faster                                                    |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 715 ms: 1.03x faster                                                    |
| pickle_pure_python       | 306 us                                                 | 297 us: 1.03x faster                                                    |
| mdp                      | 2.62 sec                                               | 2.57 sec: 1.02x faster                                                  |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                                    |
| scimark_monte_carlo      | 68.1 ms                                                | 67.0 ms: 1.02x faster                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                    |
| regex_dna                | 204 ms                                                 | 201 ms: 1.01x faster                                                    |
| unpickle_list            | 4.91 us                                                | 4.88 us: 1.01x faster                                                   |
| unpickle_pure_python     | 228 us                                                 | 227 us: 1.00x faster                                                    |
| pickle_dict              | 31.1 us                                                | 31.2 us: 1.00x slower                                                   |
| sqlglot_optimize         | 53.1 ms                                                | 53.4 ms: 1.01x slower                                                   |
| tornado_http             | 96.3 ms                                                | 96.9 ms: 1.01x slower                                                   |
| logging_format           | 6.68 us                                                | 6.73 us: 1.01x slower                                                   |
| logging_simple           | 6.03 us                                                | 6.08 us: 1.01x slower                                                   |
| docutils                 | 2.63 sec                                               | 2.66 sec: 1.01x slower                                                  |
| pickle                   | 10.1 us                                                | 10.2 us: 1.01x slower                                                   |
| pycparser                | 1.18 sec                                               | 1.20 sec: 1.01x slower                                                  |
| meteor_contest           | 107 ms                                                 | 108 ms: 1.02x slower                                                    |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                                   |
| scimark_fft              | 328 ms                                                 | 334 ms: 1.02x slower                                                    |
| fannkuch                 | 388 ms                                                 | 396 ms: 1.02x slower                                                    |
| gc_traversal             | 4.02 ms                                                | 4.11 ms: 1.02x slower                                                   |
| bench_thread_pool        | 819 us                                                 | 838 us: 1.02x slower                                                    |
| nbody                    | 93.1 ms                                                | 95.9 ms: 1.03x slower                                                   |
| logging_silent           | 101 ns                                                 | 104 ns: 1.03x slower                                                    |
| scimark_sor              | 118 ms                                                 | 122 ms: 1.03x slower                                                    |
| pathlib                  | 18.2 ms                                                | 18.8 ms: 1.03x slower                                                   |
| pprint_pformat           | 1.46 sec                                               | 1.51 sec: 1.04x slower                                                  |
| deepcopy                 | 342 us                                                 | 355 us: 1.04x slower                                                    |
| scimark_lu               | 110 ms                                                 | 114 ms: 1.04x slower                                                    |
| regex_compile            | 138 ms                                                 | 144 ms: 1.04x slower                                                    |
| richards                 | 45.7 ms                                                | 48.0 ms: 1.05x slower                                                   |
| regex_v8                 | 22.0 ms                                                | 23.2 ms: 1.05x slower                                                   |
| go                       | 140 ms                                                 | 147 ms: 1.05x slower                                                    |
| pprint_safe_repr         | 701 ms                                                 | 740 ms: 1.05x slower                                                    |
| comprehensions           | 22.4 us                                                | 23.8 us: 1.06x slower                                                   |
| xml_etree_process        | 53.9 ms                                                | 57.3 ms: 1.06x slower                                                   |
| float                    | 77.2 ms                                                | 82.3 ms: 1.07x slower                                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.79 ms: 1.07x slower                                                   |
| deepcopy_memo            | 37.0 us                                                | 39.5 us: 1.07x slower                                                   |
| nqueens                  | 83.4 ms                                                | 89.6 ms: 1.08x slower                                                   |
| spectral_norm            | 100 ms                                                 | 108 ms: 1.08x slower                                                    |
| dulwich_log              | 63.7 ms                                                | 68.6 ms: 1.08x slower                                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.17 us: 1.08x slower                                                   |
| sqlite_synth             | 2.52 us                                                | 2.73 us: 1.08x slower                                                   |
| pyflate                  | 418 ms                                                 | 453 ms: 1.08x slower                                                    |
| hexiom                   | 6.37 ms                                                | 6.95 ms: 1.09x slower                                                   |
| xml_etree_generate       | 76.2 ms                                                | 83.3 ms: 1.09x slower                                                   |
| unpack_sequence          | 43.1 ns                                                | 47.2 ns: 1.10x slower                                                   |
| unpickle                 | 13.7 us                                                | 15.0 us: 1.10x slower                                                   |
| pickle_list              | 4.11 us                                                | 4.66 us: 1.13x slower                                                   |
| mako                     | 10.1 ms                                                | 11.5 ms: 1.14x slower                                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.90 ms: 1.15x slower                                                   |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                   |
| telco                    | 6.58 ms                                                | 8.08 ms: 1.23x slower                                                   |
| async_generators         | 368 ms                                                 | 460 ms: 1.25x slower                                                    |
| dask                     | 360 ms                                                 | 534 ms: 1.48x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.03x faster                                                            |

Benchmark hidden because not significant (2): json, bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 82.18% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
