
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 1778268
- commit date: 2023-09-25
- overall geometric mean: 1.01x faster
- HPT reliability: 96.56%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.68 sec: 1.02x slower                                                  |
| tornado_http   | 96.3 ms                                                | 99.1 ms: 1.03x slower                                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 195 ms: 1.01x faster                                                    |
| nbody          | 93.1 ms                                                | 103 ms: 1.10x slower                                                    |
| float          | 77.2 ms                                                | 86.8 ms: 1.12x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.40 ms: 1.18x faster                                                   |
| regex_dna      | 204 ms                                                 | 205 ms: 1.00x slower                                                    |
| regex_v8       | 22.0 ms                                                | 23.4 ms: 1.06x slower                                                   |
| regex_compile  | 138 ms                                                 | 149 ms: 1.08x slower                                                    |
| Geometric mean | (ref)                                                  | 1.01x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.87 ms: 1.27x faster                                                   |
| json_loads           | 26.5 us                                                | 25.0 us: 1.06x faster                                                   |
| xml_etree_parse      | 158 ms                                                 | 151 ms: 1.05x faster                                                    |
| tomli_loads          | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                  |
| unpickle_list        | 4.91 us                                                | 4.80 us: 1.02x faster                                                   |
| pickle_pure_python   | 306 us                                                 | 303 us: 1.01x faster                                                    |
| unpickle_pure_python | 228 us                                                 | 233 us: 1.02x slower                                                    |
| xml_etree_iterparse  | 104 ms                                                 | 107 ms: 1.03x slower                                                    |
| pickle               | 10.1 us                                                | 10.6 us: 1.06x slower                                                   |
| xml_etree_process    | 53.9 ms                                                | 57.4 ms: 1.07x slower                                                   |
| xml_etree_generate   | 76.2 ms                                                | 83.2 ms: 1.09x slower                                                   |
| unpickle             | 13.7 us                                                | 15.1 us: 1.10x slower                                                   |
| pickle_list          | 4.11 us                                                | 4.72 us: 1.15x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.88 ms: 1.15x slower                                                   |
| python_startup         | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.5 ms: 1.14x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 153 us: 3.17x faster                                                    |
| generators               | 73.5 ms                                                | 28.9 ms: 2.54x faster                                                   |
| asyncio_tcp              | 922 ms                                                 | 502 ms: 1.84x faster                                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.81 sec: 1.73x faster                                                  |
| json_dumps               | 12.6 ms                                                | 9.87 ms: 1.27x faster                                                   |
| regex_effbot             | 3.99 ms                                                | 3.40 ms: 1.18x faster                                                   |
| mypy2                    | 420 ms                                                 | 358 ms: 1.17x faster                                                    |
| async_tree_none          | 526 ms                                                 | 451 ms: 1.17x faster                                                    |
| coverage                 | 100 ms                                                 | 86.2 ms: 1.16x faster                                                   |
| coroutines               | 25.5 ms                                                | 22.0 ms: 1.16x faster                                                   |
| async_tree_memoization   | 627 ms                                                 | 573 ms: 1.09x faster                                                    |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                  |
| richards_super           | 56.8 ms                                                | 52.7 ms: 1.08x faster                                                   |
| sqlglot_parse            | 1.40 ms                                                | 1.31 ms: 1.07x faster                                                   |
| json_loads               | 26.5 us                                                | 25.0 us: 1.06x faster                                                   |
| xml_etree_parse          | 158 ms                                                 | 151 ms: 1.05x faster                                                    |
| sqlglot_transpile        | 1.70 ms                                                | 1.63 ms: 1.05x faster                                                   |
| gc_traversal             | 4.02 ms                                                | 3.86 ms: 1.04x faster                                                   |
| json                     | 4.94 ms                                                | 4.78 ms: 1.03x faster                                                   |
| tomli_loads              | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                  |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 718 ms: 1.03x faster                                                    |
| unpickle_list            | 4.91 us                                                | 4.80 us: 1.02x faster                                                   |
| crypto_pyaes             | 74.7 ms                                                | 73.0 ms: 1.02x faster                                                   |
| pycparser                | 1.18 sec                                               | 1.16 sec: 1.02x faster                                                  |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                                    |
| pidigits                 | 198 ms                                                 | 195 ms: 1.01x faster                                                    |
| pickle_pure_python       | 306 us                                                 | 303 us: 1.01x faster                                                    |
| raytrace                 | 297 ms                                                 | 295 ms: 1.01x faster                                                    |
| mdp                      | 2.62 sec                                               | 2.62 sec: 1.00x slower                                                  |
| regex_dna                | 204 ms                                                 | 205 ms: 1.00x slower                                                    |
| create_gc_cycles         | 1.49 ms                                                | 1.50 ms: 1.01x slower                                                   |
| sqlglot_optimize         | 53.1 ms                                                | 53.7 ms: 1.01x slower                                                   |
| richards                 | 45.7 ms                                                | 46.3 ms: 1.01x slower                                                   |
| docutils                 | 2.63 sec                                               | 2.68 sec: 1.02x slower                                                  |
| unpickle_pure_python     | 228 us                                                 | 233 us: 1.02x slower                                                    |
| bench_thread_pool        | 819 us                                                 | 838 us: 1.02x slower                                                    |
| deltablue                | 3.67 ms                                                | 3.76 ms: 1.02x slower                                                   |
| pathlib                  | 18.2 ms                                                | 18.7 ms: 1.02x slower                                                   |
| deepcopy                 | 342 us                                                 | 351 us: 1.03x slower                                                    |
| xml_etree_iterparse      | 104 ms                                                 | 107 ms: 1.03x slower                                                    |
| tornado_http             | 96.3 ms                                                | 99.1 ms: 1.03x slower                                                   |
| meteor_contest           | 107 ms                                                 | 110 ms: 1.03x slower                                                    |
| scimark_lu               | 110 ms                                                 | 113 ms: 1.03x slower                                                    |
| scimark_sor              | 118 ms                                                 | 123 ms: 1.04x slower                                                    |
| scimark_monte_carlo      | 68.1 ms                                                | 71.0 ms: 1.04x slower                                                   |
| deepcopy_memo            | 37.0 us                                                | 38.7 us: 1.04x slower                                                   |
| logging_silent           | 101 ns                                                 | 106 ns: 1.05x slower                                                    |
| pickle                   | 10.1 us                                                | 10.6 us: 1.06x slower                                                   |
| fannkuch                 | 388 ms                                                 | 410 ms: 1.06x slower                                                    |
| regex_v8                 | 22.0 ms                                                | 23.4 ms: 1.06x slower                                                   |
| chaos                    | 69.2 ms                                                | 73.5 ms: 1.06x slower                                                   |
| xml_etree_process        | 53.9 ms                                                | 57.4 ms: 1.07x slower                                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.15 us: 1.07x slower                                                   |
| go                       | 140 ms                                                 | 150 ms: 1.07x slower                                                    |
| regex_compile            | 138 ms                                                 | 149 ms: 1.08x slower                                                    |
| dulwich_log              | 63.7 ms                                                | 69.3 ms: 1.09x slower                                                   |
| xml_etree_generate       | 76.2 ms                                                | 83.2 ms: 1.09x slower                                                   |
| scimark_fft              | 328 ms                                                 | 359 ms: 1.09x slower                                                    |
| spectral_norm            | 100 ms                                                 | 109 ms: 1.09x slower                                                    |
| sqlite_synth             | 2.52 us                                                | 2.77 us: 1.10x slower                                                   |
| nbody                    | 93.1 ms                                                | 103 ms: 1.10x slower                                                    |
| unpickle                 | 13.7 us                                                | 15.1 us: 1.10x slower                                                   |
| nqueens                  | 83.4 ms                                                | 92.4 ms: 1.11x slower                                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.02 ms: 1.12x slower                                                   |
| float                    | 77.2 ms                                                | 86.8 ms: 1.12x slower                                                   |
| unpack_sequence          | 43.1 ns                                                | 49.0 ns: 1.14x slower                                                   |
| mako                     | 10.1 ms                                                | 11.5 ms: 1.14x slower                                                   |
| python_startup_no_site   | 6.01 ms                                                | 6.88 ms: 1.15x slower                                                   |
| pickle_list              | 4.11 us                                                | 4.72 us: 1.15x slower                                                   |
| comprehensions           | 22.4 us                                                | 25.9 us: 1.16x slower                                                   |
| python_startup           | 8.52 ms                                                | 10.0 ms: 1.18x slower                                                   |
| pprint_safe_repr         | 701 ms                                                 | 834 ms: 1.19x slower                                                    |
| pyflate                  | 418 ms                                                 | 498 ms: 1.19x slower                                                    |
| pprint_pformat           | 1.46 sec                                               | 1.75 sec: 1.20x slower                                                  |
| telco                    | 6.58 ms                                                | 8.03 ms: 1.22x slower                                                   |
| async_generators         | 368 ms                                                 | 458 ms: 1.24x slower                                                    |
| hexiom                   | 6.37 ms                                                | 8.53 ms: 1.34x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                            |

Benchmark hidden because not significant (4): logging_simple, pickle_dict, logging_format, bench_mp_pool
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 96.56% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
