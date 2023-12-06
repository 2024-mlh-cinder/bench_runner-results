
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: f1573ca
- commit date: 2023-09-25
- overall geometric mean: 1.01x slower
- HPT reliability: 99.88%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.70 sec: 1.03x slower                                                  |
| tornado_http   | 96.3 ms                                                | 99.6 ms: 1.03x slower                                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 188 ms: 1.05x faster                                                    |
| nbody          | 93.1 ms                                                | 111 ms: 1.19x slower                                                    |
| float          | 77.2 ms                                                | 96.1 ms: 1.24x slower                                                   |
| Geometric mean | (ref)                                                  | 1.12x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.45 ms: 1.16x faster                                                   |
| regex_dna      | 204 ms                                                 | 206 ms: 1.01x slower                                                    |
| regex_v8       | 22.0 ms                                                | 23.5 ms: 1.07x slower                                                   |
| regex_compile  | 138 ms                                                 | 154 ms: 1.11x slower                                                    |
| Geometric mean | (ref)                                                  | 1.01x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 12.6 ms                                                | 9.84 ms: 1.28x faster                                                   |
| json_loads           | 26.5 us                                                | 24.8 us: 1.07x faster                                                   |
| xml_etree_parse      | 158 ms                                                 | 154 ms: 1.03x faster                                                    |
| pickle_pure_python   | 306 us                                                 | 301 us: 1.02x faster                                                    |
| unpickle_list        | 4.91 us                                                | 4.87 us: 1.01x faster                                                   |
| pickle_dict          | 31.1 us                                                | 31.5 us: 1.01x slower                                                   |
| tomli_loads          | 2.22 sec                                               | 2.27 sec: 1.02x slower                                                  |
| unpickle_pure_python | 228 us                                                 | 238 us: 1.04x slower                                                    |
| pickle               | 10.1 us                                                | 10.5 us: 1.05x slower                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 109 ms: 1.05x slower                                                    |
| xml_etree_process    | 53.9 ms                                                | 58.2 ms: 1.08x slower                                                   |
| xml_etree_generate   | 76.2 ms                                                | 83.6 ms: 1.10x slower                                                   |
| unpickle             | 13.7 us                                                | 15.2 us: 1.11x slower                                                   |
| pickle_list          | 4.11 us                                                | 4.80 us: 1.17x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.92 ms: 1.15x slower                                                   |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.17x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 11.8 ms: 1.17x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-f1573ca |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 152 us: 3.20x faster                                                    |
| generators               | 73.5 ms                                                | 28.6 ms: 2.57x faster                                                   |
| asyncio_tcp              | 922 ms                                                 | 511 ms: 1.80x faster                                                    |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.82 sec: 1.72x faster                                                  |
| json_dumps               | 12.6 ms                                                | 9.84 ms: 1.28x faster                                                   |
| mypy2                    | 420 ms                                                 | 358 ms: 1.17x faster                                                    |
| async_tree_none          | 526 ms                                                 | 451 ms: 1.17x faster                                                    |
| regex_effbot             | 3.99 ms                                                | 3.45 ms: 1.16x faster                                                   |
| coroutines               | 25.5 ms                                                | 22.3 ms: 1.15x faster                                                   |
| coverage                 | 100 ms                                                 | 87.6 ms: 1.14x faster                                                   |
| async_tree_io            | 1.30 sec                                               | 1.20 sec: 1.08x faster                                                  |
| async_tree_memoization   | 627 ms                                                 | 584 ms: 1.07x faster                                                    |
| json_loads               | 26.5 us                                                | 24.8 us: 1.07x faster                                                   |
| sqlglot_parse            | 1.40 ms                                                | 1.32 ms: 1.06x faster                                                   |
| pidigits                 | 198 ms                                                 | 188 ms: 1.05x faster                                                    |
| sqlglot_transpile        | 1.70 ms                                                | 1.64 ms: 1.04x faster                                                   |
| xml_etree_parse          | 158 ms                                                 | 154 ms: 1.03x faster                                                    |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 717 ms: 1.03x faster                                                    |
| json                     | 4.94 ms                                                | 4.80 ms: 1.03x faster                                                   |
| richards_super           | 56.8 ms                                                | 55.3 ms: 1.03x faster                                                   |
| crypto_pyaes             | 74.7 ms                                                | 72.9 ms: 1.02x faster                                                   |
| sqlglot_normalize        | 108 ms                                                 | 106 ms: 1.02x faster                                                    |
| pickle_pure_python       | 306 us                                                 | 301 us: 1.02x faster                                                    |
| pycparser                | 1.18 sec                                               | 1.17 sec: 1.01x faster                                                  |
| unpickle_list            | 4.91 us                                                | 4.87 us: 1.01x faster                                                   |
| logging_simple           | 6.03 us                                                | 6.09 us: 1.01x slower                                                   |
| regex_dna                | 204 ms                                                 | 206 ms: 1.01x slower                                                    |
| pickle_dict              | 31.1 us                                                | 31.5 us: 1.01x slower                                                   |
| logging_format           | 6.68 us                                                | 6.77 us: 1.01x slower                                                   |
| sqlglot_optimize         | 53.1 ms                                                | 53.8 ms: 1.01x slower                                                   |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.02x slower                                                   |
| gc_traversal             | 4.02 ms                                                | 4.11 ms: 1.02x slower                                                   |
| tomli_loads              | 2.22 sec                                               | 2.27 sec: 1.02x slower                                                  |
| pathlib                  | 18.2 ms                                                | 18.7 ms: 1.03x slower                                                   |
| bench_thread_pool        | 819 us                                                 | 840 us: 1.03x slower                                                    |
| raytrace                 | 297 ms                                                 | 305 ms: 1.03x slower                                                    |
| docutils                 | 2.63 sec                                               | 2.70 sec: 1.03x slower                                                  |
| tornado_http             | 96.3 ms                                                | 99.6 ms: 1.03x slower                                                   |
| logging_silent           | 101 ns                                                 | 105 ns: 1.04x slower                                                    |
| deepcopy                 | 342 us                                                 | 355 us: 1.04x slower                                                    |
| scimark_lu               | 110 ms                                                 | 114 ms: 1.04x slower                                                    |
| unpickle_pure_python     | 228 us                                                 | 238 us: 1.04x slower                                                    |
| meteor_contest           | 107 ms                                                 | 111 ms: 1.04x slower                                                    |
| scimark_sor              | 118 ms                                                 | 123 ms: 1.05x slower                                                    |
| pickle                   | 10.1 us                                                | 10.5 us: 1.05x slower                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 109 ms: 1.05x slower                                                    |
| richards                 | 45.7 ms                                                | 48.5 ms: 1.06x slower                                                   |
| mdp                      | 2.62 sec                                               | 2.78 sec: 1.06x slower                                                  |
| regex_v8                 | 22.0 ms                                                | 23.5 ms: 1.07x slower                                                   |
| deepcopy_reduce          | 2.94 us                                                | 3.16 us: 1.07x slower                                                   |
| dulwich_log              | 63.7 ms                                                | 68.5 ms: 1.08x slower                                                   |
| spectral_norm            | 100 ms                                                 | 108 ms: 1.08x slower                                                    |
| deepcopy_memo            | 37.0 us                                                | 40.0 us: 1.08x slower                                                   |
| xml_etree_process        | 53.9 ms                                                | 58.2 ms: 1.08x slower                                                   |
| sqlite_synth             | 2.52 us                                                | 2.74 us: 1.09x slower                                                   |
| scimark_monte_carlo      | 68.1 ms                                                | 74.1 ms: 1.09x slower                                                   |
| go                       | 140 ms                                                 | 153 ms: 1.10x slower                                                    |
| xml_etree_generate       | 76.2 ms                                                | 83.6 ms: 1.10x slower                                                   |
| chaos                    | 69.2 ms                                                | 76.5 ms: 1.11x slower                                                   |
| unpickle                 | 13.7 us                                                | 15.2 us: 1.11x slower                                                   |
| regex_compile            | 138 ms                                                 | 154 ms: 1.11x slower                                                    |
| unpack_sequence          | 43.1 ns                                                | 48.6 ns: 1.13x slower                                                   |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 5.09 ms: 1.13x slower                                                   |
| scimark_fft              | 328 ms                                                 | 373 ms: 1.13x slower                                                    |
| fannkuch                 | 388 ms                                                 | 442 ms: 1.14x slower                                                    |
| python_startup_no_site   | 6.01 ms                                                | 6.92 ms: 1.15x slower                                                   |
| deltablue                | 3.67 ms                                                | 4.26 ms: 1.16x slower                                                   |
| nqueens                  | 83.4 ms                                                | 97.2 ms: 1.17x slower                                                   |
| pickle_list              | 4.11 us                                                | 4.80 us: 1.17x slower                                                   |
| mako                     | 10.1 ms                                                | 11.8 ms: 1.17x slower                                                   |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.19x slower                                                   |
| nbody                    | 93.1 ms                                                | 111 ms: 1.19x slower                                                    |
| comprehensions           | 22.4 us                                                | 26.8 us: 1.19x slower                                                   |
| telco                    | 6.58 ms                                                | 8.08 ms: 1.23x slower                                                   |
| pprint_safe_repr         | 701 ms                                                 | 865 ms: 1.23x slower                                                    |
| float                    | 77.2 ms                                                | 96.1 ms: 1.24x slower                                                   |
| pprint_pformat           | 1.46 sec                                               | 1.82 sec: 1.25x slower                                                  |
| async_generators         | 368 ms                                                 | 463 ms: 1.26x slower                                                    |
| pyflate                  | 418 ms                                                 | 533 ms: 1.27x slower                                                    |
| hexiom                   | 6.37 ms                                                | 9.45 ms: 1.48x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (19) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.88% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
