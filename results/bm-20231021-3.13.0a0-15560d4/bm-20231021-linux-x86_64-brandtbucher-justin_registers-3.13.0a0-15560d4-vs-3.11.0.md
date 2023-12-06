
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 15560d4
- commit date: 2023-10-21
- overall geometric mean: 1.01x slower
- HPT reliability: 99.97%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.74 sec: 1.04x slower                                                  |
| tornado_http   | 96.3 ms                                                | 99.7 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.05x faster                                                    |
| nbody          | 93.1 ms                                                | 100.0 ms: 1.07x slower                                                  |
| float          | 77.2 ms                                                | 86.8 ms: 1.12x slower                                                   |
| Geometric mean | (ref)                                                  | 1.05x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.65 ms: 1.09x faster                                                   |
| regex_dna      | 204 ms                                                 | 217 ms: 1.07x slower                                                    |
| regex_compile  | 138 ms                                                 | 151 ms: 1.09x slower                                                    |
| regex_v8       | 22.0 ms                                                | 25.8 ms: 1.17x slower                                                   |
| Geometric mean | (ref)                                                  | 1.06x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 10.6 ms: 1.19x faster                                                   |
| tomli_loads          | 2.22 sec                                               | 2.14 sec: 1.04x faster                                                  |
| pickle_pure_python   | 306 us                                                 | 308 us: 1.01x slower                                                    |
| unpickle_list        | 4.91 us                                                | 5.00 us: 1.02x slower                                                   |
| unpickle_pure_python | 228 us                                                 | 234 us: 1.02x slower                                                    |
| xml_etree_iterparse  | 104 ms                                                 | 109 ms: 1.05x slower                                                    |
| json_loads           | 26.5 us                                                | 28.3 us: 1.07x slower                                                   |
| pickle_dict          | 31.1 us                                                | 34.5 us: 1.11x slower                                                   |
| xml_etree_process    | 53.9 ms                                                | 60.2 ms: 1.12x slower                                                   |
| unpickle             | 13.7 us                                                | 15.4 us: 1.12x slower                                                   |
| xml_etree_generate   | 76.2 ms                                                | 87.0 ms: 1.14x slower                                                   |
| pickle               | 10.1 us                                                | 11.6 us: 1.15x slower                                                   |
| pickle_list          | 4.11 us                                                | 5.02 us: 1.22x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.06x slower                                                            |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.93 ms: 1.15x slower                                                   |
| python_startup         | 8.52 ms                                                | 10.2 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.17x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 12.1 ms: 1.20x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 158 us: 3.08x faster                                                    |
| generators               | 73.5 ms                                                | 29.4 ms: 2.50x faster                                                   |
| asyncio_tcp              | 922 ms                                                 | 490 ms: 1.88x faster                                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.80 sec: 1.74x faster                                                  |
| json_dumps               | 12.6 ms                                                | 10.6 ms: 1.19x faster                                                   |
| async_tree_none          | 526 ms                                                 | 450 ms: 1.17x faster                                                    |
| mypy2                    | 420 ms                                                 | 361 ms: 1.16x faster                                                    |
| coroutines               | 25.5 ms                                                | 22.5 ms: 1.13x faster                                                   |
| coverage                 | 100 ms                                                 | 91.2 ms: 1.10x faster                                                   |
| regex_effbot             | 3.99 ms                                                | 3.65 ms: 1.09x faster                                                   |
| async_tree_memoization   | 627 ms                                                 | 579 ms: 1.08x faster                                                    |
| async_tree_io            | 1.30 sec                                               | 1.21 sec: 1.08x faster                                                  |
| sqlglot_parse            | 1.40 ms                                                | 1.32 ms: 1.06x faster                                                   |
| pidigits                 | 198 ms                                                 | 188 ms: 1.05x faster                                                    |
| gc_traversal             | 4.02 ms                                                | 3.82 ms: 1.05x faster                                                   |
| richards_super           | 56.8 ms                                                | 54.5 ms: 1.04x faster                                                   |
| sqlglot_transpile        | 1.70 ms                                                | 1.64 ms: 1.04x faster                                                   |
| tomli_loads              | 2.22 sec                                               | 2.14 sec: 1.04x faster                                                  |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 724 ms: 1.02x faster                                                    |
| create_gc_cycles         | 1.49 ms                                                | 1.46 ms: 1.02x faster                                                   |
| pickle_pure_python       | 306 us                                                 | 308 us: 1.01x slower                                                    |
| raytrace                 | 297 ms                                                 | 301 ms: 1.01x slower                                                    |
| unpickle_list            | 4.91 us                                                | 5.00 us: 1.02x slower                                                   |
| crypto_pyaes             | 74.7 ms                                                | 76.2 ms: 1.02x slower                                                   |
| logging_simple           | 6.03 us                                                | 6.17 us: 1.02x slower                                                   |
| unpickle_pure_python     | 228 us                                                 | 234 us: 1.02x slower                                                    |
| logging_format           | 6.68 us                                                | 6.86 us: 1.03x slower                                                   |
| bench_thread_pool        | 819 us                                                 | 843 us: 1.03x slower                                                    |
| sqlglot_optimize         | 53.1 ms                                                | 54.7 ms: 1.03x slower                                                   |
| pycparser                | 1.18 sec                                               | 1.22 sec: 1.03x slower                                                  |
| tornado_http             | 96.3 ms                                                | 99.7 ms: 1.04x slower                                                   |
| deltablue                | 3.67 ms                                                | 3.81 ms: 1.04x slower                                                   |
| pathlib                  | 18.2 ms                                                | 19.0 ms: 1.04x slower                                                   |
| docutils                 | 2.63 sec                                               | 2.74 sec: 1.04x slower                                                  |
| richards                 | 45.7 ms                                                | 47.9 ms: 1.05x slower                                                   |
| meteor_contest           | 107 ms                                                 | 112 ms: 1.05x slower                                                    |
| json                     | 4.94 ms                                                | 5.20 ms: 1.05x slower                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 109 ms: 1.05x slower                                                    |
| deepcopy                 | 342 us                                                 | 362 us: 1.06x slower                                                    |
| logging_silent           | 101 ns                                                 | 107 ns: 1.06x slower                                                    |
| chaos                    | 69.2 ms                                                | 73.7 ms: 1.07x slower                                                   |
| regex_dna                | 204 ms                                                 | 217 ms: 1.07x slower                                                    |
| json_loads               | 26.5 us                                                | 28.3 us: 1.07x slower                                                   |
| mdp                      | 2.62 sec                                               | 2.81 sec: 1.07x slower                                                  |
| nbody                    | 93.1 ms                                                | 100.0 ms: 1.07x slower                                                  |
| scimark_sor              | 118 ms                                                 | 127 ms: 1.07x slower                                                    |
| scimark_lu               | 110 ms                                                 | 118 ms: 1.08x slower                                                    |
| deepcopy_reduce          | 2.94 us                                                | 3.19 us: 1.09x slower                                                   |
| scimark_monte_carlo      | 68.1 ms                                                | 74.1 ms: 1.09x slower                                                   |
| fannkuch                 | 388 ms                                                 | 423 ms: 1.09x slower                                                    |
| regex_compile            | 138 ms                                                 | 151 ms: 1.09x slower                                                    |
| go                       | 140 ms                                                 | 153 ms: 1.09x slower                                                    |
| dulwich_log              | 63.7 ms                                                | 69.8 ms: 1.10x slower                                                   |
| scimark_fft              | 328 ms                                                 | 360 ms: 1.10x slower                                                    |
| deepcopy_memo            | 37.0 us                                                | 40.8 us: 1.10x slower                                                   |
| pickle_dict              | 31.1 us                                                | 34.5 us: 1.11x slower                                                   |
| nqueens                  | 83.4 ms                                                | 92.6 ms: 1.11x slower                                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.00 ms: 1.11x slower                                                   |
| xml_etree_process        | 53.9 ms                                                | 60.2 ms: 1.12x slower                                                   |
| sqlite_synth             | 2.52 us                                                | 2.83 us: 1.12x slower                                                   |
| float                    | 77.2 ms                                                | 86.8 ms: 1.12x slower                                                   |
| unpickle                 | 13.7 us                                                | 15.4 us: 1.12x slower                                                   |
| xml_etree_generate       | 76.2 ms                                                | 87.0 ms: 1.14x slower                                                   |
| pickle                   | 10.1 us                                                | 11.6 us: 1.15x slower                                                   |
| comprehensions           | 22.4 us                                                | 25.9 us: 1.15x slower                                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.93 ms: 1.15x slower                                                   |
| regex_v8                 | 22.0 ms                                                | 25.8 ms: 1.17x slower                                                   |
| spectral_norm            | 100 ms                                                 | 118 ms: 1.18x slower                                                    |
| pprint_pformat           | 1.46 sec                                               | 1.73 sec: 1.19x slower                                                  |
| pprint_safe_repr         | 701 ms                                                 | 835 ms: 1.19x slower                                                    |
| python_startup           | 8.52 ms                                                | 10.2 ms: 1.19x slower                                                   |
| mako                     | 10.1 ms                                                | 12.1 ms: 1.20x slower                                                   |
| pickle_list              | 4.11 us                                                | 5.02 us: 1.22x slower                                                   |
| pyflate                  | 418 ms                                                 | 517 ms: 1.24x slower                                                    |
| unpack_sequence          | 43.1 ns                                                | 53.6 ns: 1.24x slower                                                   |
| async_generators         | 368 ms                                                 | 476 ms: 1.29x slower                                                    |
| telco                    | 6.58 ms                                                | 8.52 ms: 1.29x slower                                                   |
| hexiom                   | 6.37 ms                                                | 8.25 ms: 1.30x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (3): xml_etree_parse, bench_mp_pool, sqlglot_normalize
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.97% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.01x
