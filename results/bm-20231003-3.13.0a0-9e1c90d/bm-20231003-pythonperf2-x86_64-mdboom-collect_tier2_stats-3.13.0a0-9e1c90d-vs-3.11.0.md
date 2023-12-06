
# Results vs. 3.11.0

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 9e1c90d
- commit date: 2023-10-03
- overall geometric mean: 1.01x faster
- HPT reliability: 91.21%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.99 sec: 1.05x slower                                                     |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                        | 1.03x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                       |
| float          | 74.2 ms                                                      | 83.3 ms: 1.12x slower                                                      |
| nbody          | 90.7 ms                                                      | 102 ms: 1.12x slower                                                       |
| Geometric mean | (ref)                                                        | 1.10x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.50 ms                                                      | 3.61 ms: 1.03x slower                                                      |
| regex_dna      | 227 ms                                                       | 242 ms: 1.07x slower                                                       |
| regex_v8       | 23.9 ms                                                      | 25.6 ms: 1.07x slower                                                      |
| regex_compile  | 158 ms                                                       | 172 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                        | 1.06x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|---------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps          | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                                      |
| json_loads          | 28.7 us                                                      | 24.6 us: 1.16x faster                                                      |
| xml_etree_parse     | 158 ms                                                       | 153 ms: 1.03x faster                                                       |
| pickle_pure_python  | 319 us                                                       | 323 us: 1.01x slower                                                       |
| unpickle_list       | 4.53 us                                                      | 4.70 us: 1.04x slower                                                      |
| xml_etree_iterparse | 104 ms                                                       | 109 ms: 1.04x slower                                                       |
| pickle_dict         | 30.8 us                                                      | 32.2 us: 1.05x slower                                                      |
| xml_etree_process   | 56.5 ms                                                      | 59.8 ms: 1.06x slower                                                      |
| pickle              | 9.64 us                                                      | 10.2 us: 1.06x slower                                                      |
| unpickle            | 13.4 us                                                      | 14.5 us: 1.08x slower                                                      |
| xml_etree_generate  | 80.5 ms                                                      | 87.7 ms: 1.09x slower                                                      |
| pickle_list         | 3.83 us                                                      | 4.32 us: 1.13x slower                                                      |
| tomli_loads         | 2.26 sec                                                     | 2.71 sec: 1.20x slower                                                     |
| Geometric mean      | (ref)                                                        | 1.02x slower                                                               |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.65 ms: 1.11x slower                                                      |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 11.5 ms: 1.05x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 162 us: 3.22x faster                                                       |
| asyncio_tcp              | 753 ms                                                       | 373 ms: 2.02x faster                                                       |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.59 sec: 1.94x faster                                                     |
| generators               | 56.0 ms                                                      | 36.0 ms: 1.56x faster                                                      |
| json_dumps               | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                                      |
| coroutines               | 27.6 ms                                                      | 23.1 ms: 1.19x faster                                                      |
| chaos                    | 80.9 ms                                                      | 68.1 ms: 1.19x faster                                                      |
| async_tree_none          | 519 ms                                                       | 444 ms: 1.17x faster                                                       |
| mypy2                    | 451 ms                                                       | 387 ms: 1.17x faster                                                       |
| json_loads               | 28.7 us                                                      | 24.6 us: 1.16x faster                                                      |
| raytrace                 | 317 ms                                                       | 280 ms: 1.13x faster                                                       |
| async_tree_memoization   | 630 ms                                                       | 557 ms: 1.13x faster                                                       |
| crypto_pyaes             | 83.4 ms                                                      | 75.8 ms: 1.10x faster                                                      |
| json                     | 5.65 ms                                                      | 5.17 ms: 1.09x faster                                                      |
| gc_traversal             | 3.85 ms                                                      | 3.58 ms: 1.08x faster                                                      |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                                     |
| sqlglot_parse            | 1.53 ms                                                      | 1.43 ms: 1.07x faster                                                      |
| sqlglot_normalize        | 126 ms                                                       | 118 ms: 1.07x faster                                                       |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 708 ms: 1.06x faster                                                       |
| logging_format           | 8.11 us                                                      | 7.68 us: 1.06x faster                                                      |
| sqlglot_transpile        | 1.92 ms                                                      | 1.85 ms: 1.04x faster                                                      |
| xml_etree_parse          | 158 ms                                                       | 153 ms: 1.03x faster                                                       |
| scimark_lu               | 115 ms                                                       | 111 ms: 1.03x faster                                                       |
| coverage                 | 84.8 ms                                                      | 82.5 ms: 1.03x faster                                                      |
| mdp                      | 2.75 sec                                                     | 2.68 sec: 1.03x faster                                                     |
| deltablue                | 4.00 ms                                                      | 3.91 ms: 1.02x faster                                                      |
| logging_simple           | 7.19 us                                                      | 7.05 us: 1.02x faster                                                      |
| spectral_norm            | 93.3 ms                                                      | 91.6 ms: 1.02x faster                                                      |
| deepcopy                 | 399 us                                                       | 393 us: 1.02x faster                                                       |
| deepcopy_reduce          | 3.51 us                                                      | 3.47 us: 1.01x faster                                                      |
| logging_silent           | 101 ns                                                       | 99.8 ns: 1.01x faster                                                      |
| pickle_pure_python       | 319 us                                                       | 323 us: 1.01x slower                                                       |
| tornado_http             | 122 ms                                                       | 124 ms: 1.02x slower                                                       |
| regex_effbot             | 3.50 ms                                                      | 3.61 ms: 1.03x slower                                                      |
| pycparser                | 1.32 sec                                                     | 1.37 sec: 1.03x slower                                                     |
| unpickle_list            | 4.53 us                                                      | 4.70 us: 1.04x slower                                                      |
| xml_etree_iterparse      | 104 ms                                                       | 109 ms: 1.04x slower                                                       |
| richards_super           | 61.0 ms                                                      | 63.6 ms: 1.04x slower                                                      |
| create_gc_cycles         | 1.61 ms                                                      | 1.68 ms: 1.04x slower                                                      |
| dulwich_log              | 68.4 ms                                                      | 71.5 ms: 1.04x slower                                                      |
| docutils                 | 2.86 sec                                                     | 2.99 sec: 1.05x slower                                                     |
| pickle_dict              | 30.8 us                                                      | 32.2 us: 1.05x slower                                                      |
| nqueens                  | 103 ms                                                       | 108 ms: 1.05x slower                                                       |
| mako                     | 11.0 ms                                                      | 11.5 ms: 1.05x slower                                                      |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                                       |
| pprint_pformat           | 1.63 sec                                                     | 1.72 sec: 1.05x slower                                                     |
| meteor_contest           | 131 ms                                                       | 138 ms: 1.06x slower                                                       |
| xml_etree_process        | 56.5 ms                                                      | 59.8 ms: 1.06x slower                                                      |
| pickle                   | 9.64 us                                                      | 10.2 us: 1.06x slower                                                      |
| pathlib                  | 19.1 ms                                                      | 20.2 ms: 1.06x slower                                                      |
| regex_dna                | 227 ms                                                       | 242 ms: 1.07x slower                                                       |
| regex_v8                 | 23.9 ms                                                      | 25.6 ms: 1.07x slower                                                      |
| pprint_safe_repr         | 784 ms                                                       | 840 ms: 1.07x slower                                                       |
| sqlite_synth             | 2.50 us                                                      | 2.68 us: 1.07x slower                                                      |
| unpickle                 | 13.4 us                                                      | 14.5 us: 1.08x slower                                                      |
| fannkuch                 | 429 ms                                                       | 465 ms: 1.08x slower                                                       |
| xml_etree_generate       | 80.5 ms                                                      | 87.7 ms: 1.09x slower                                                      |
| regex_compile            | 158 ms                                                       | 172 ms: 1.09x slower                                                       |
| deepcopy_memo            | 38.8 us                                                      | 42.6 us: 1.10x slower                                                      |
| comprehensions           | 24.6 us                                                      | 27.3 us: 1.11x slower                                                      |
| go                       | 164 ms                                                       | 182 ms: 1.11x slower                                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.65 ms: 1.11x slower                                                      |
| float                    | 74.2 ms                                                      | 83.3 ms: 1.12x slower                                                      |
| nbody                    | 90.7 ms                                                      | 102 ms: 1.12x slower                                                       |
| pickle_list              | 3.83 us                                                      | 4.32 us: 1.13x slower                                                      |
| unpack_sequence          | 45.6 ns                                                      | 52.5 ns: 1.15x slower                                                      |
| hexiom                   | 7.13 ms                                                      | 8.29 ms: 1.16x slower                                                      |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                                      |
| telco                    | 6.86 ms                                                      | 8.16 ms: 1.19x slower                                                      |
| richards                 | 48.3 ms                                                      | 57.6 ms: 1.19x slower                                                      |
| pyflate                  | 449 ms                                                       | 536 ms: 1.19x slower                                                       |
| tomli_loads              | 2.26 sec                                                     | 2.71 sec: 1.20x slower                                                     |
| scimark_fft              | 285 ms                                                       | 347 ms: 1.22x slower                                                       |
| async_generators         | 316 ms                                                       | 402 ms: 1.28x slower                                                       |
| scimark_sor              | 111 ms                                                       | 149 ms: 1.34x slower                                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 5.84 ms: 1.44x slower                                                      |
| Geometric mean           | (ref)                                                        | 1.01x faster                                                               |

Benchmark hidden because not significant (5): bench_thread_pool, unpickle_pure_python, scimark_monte_carlo, sqlglot_optimize, bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 91.21% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
