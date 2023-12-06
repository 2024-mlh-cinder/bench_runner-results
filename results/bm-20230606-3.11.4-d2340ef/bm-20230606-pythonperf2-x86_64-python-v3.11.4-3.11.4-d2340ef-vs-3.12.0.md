
# Results vs. 3.12.0

- fork: python
- ref: v3.11.4
- machine: linux-x86_64
- commit hash: d2340ef
- commit date: 2023-06-06
- overall geometric mean: 1.07x slower \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 285 ms: 1.00x slower                                         |
| chameleon      | 7.27 ms                                                      | 7.63 ms: 1.05x slower                                        |
| docutils       | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                       |
| Geometric mean | (ref)                                                        | 1.00x slower                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 704 ms                                                       | 758 ms: 1.08x slower                                         |
| async_tree_io           | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                       |
| async_tree_none         | 459 ms                                                       | 522 ms: 1.14x slower                                         |
| async_tree_memoization  | 554 ms                                                       | 630 ms: 1.14x slower                                         |
| Geometric mean          | (ref)                                                        | 1.12x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 73.8 ms: 1.11x faster                                        |
| pidigits       | 264 ms                                                       | 252 ms: 1.05x faster                                         |
| nbody          | 88.2 ms                                                      | 95.6 ms: 1.08x slower                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.61 ms                                                      | 3.46 ms: 1.04x faster                                        |
| regex_dna      | 240 ms                                                       | 231 ms: 1.04x faster                                         |
| regex_v8       | 24.4 ms                                                      | 24.5 ms: 1.00x slower                                        |
| regex_compile  | 145 ms                                                       | 155 ms: 1.07x slower                                         |
| Geometric mean | (ref)                                                        | 1.00x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.0 us: 1.18x faster                                        |
| pickle_list          | 4.22 us                                                      | 3.70 us: 1.14x faster                                        |
| pickle_dict          | 32.0 us                                                      | 29.7 us: 1.08x faster                                        |
| xml_etree_generate   | 85.3 ms                                                      | 81.0 ms: 1.05x faster                                        |
| xml_etree_process    | 58.3 ms                                                      | 56.3 ms: 1.04x faster                                        |
| pickle_pure_python   | 319 us                                                       | 321 us: 1.00x slower                                         |
| unpickle_list        | 4.65 us                                                      | 4.69 us: 1.01x slower                                        |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                         |
| tomli_loads          | 2.17 sec                                                     | 2.27 sec: 1.05x slower                                       |
| xml_etree_parse      | 147 ms                                                       | 159 ms: 1.08x slower                                         |
| unpickle_pure_python | 210 us                                                       | 243 us: 1.16x slower                                         |
| json_loads           | 24.3 us                                                      | 28.4 us: 1.17x slower                                        |
| json_dumps           | 10.3 ms                                                      | 13.4 ms: 1.31x slower                                        |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                 |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.72 ms: 1.12x faster                                        |
| python_startup         | 11.7 ms                                                      | 10.7 ms: 1.10x faster                                        |
| Geometric mean         | (ref)                                                        | 1.11x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 39.7 ms: 1.03x slower                                        |
| mako            | 10.1 ms                                                      | 10.8 ms: 1.07x slower                                        |
| Geometric mean  | (ref)                                                        | 1.05x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpack_sequence          | 54.5 ns                                                      | 45.6 ns: 1.20x faster                                        |
| async_generators         | 385 ms                                                       | 322 ms: 1.20x faster                                         |
| unpickle                 | 15.3 us                                                      | 13.0 us: 1.18x faster                                        |
| pickle_list              | 4.22 us                                                      | 3.70 us: 1.14x faster                                        |
| python_startup_no_site   | 8.67 ms                                                      | 7.72 ms: 1.12x faster                                        |
| scimark_sparse_mat_mult  | 4.49 ms                                                      | 4.01 ms: 1.12x faster                                        |
| float                    | 81.6 ms                                                      | 73.8 ms: 1.11x faster                                        |
| sqlite_synth             | 2.72 us                                                      | 2.48 us: 1.10x faster                                        |
| python_startup           | 11.7 ms                                                      | 10.7 ms: 1.10x faster                                        |
| bench_mp_pool            | 4.96 ms                                                      | 4.58 ms: 1.08x faster                                        |
| scimark_fft              | 303 ms                                                       | 281 ms: 1.08x faster                                         |
| pickle_dict              | 32.0 us                                                      | 29.7 us: 1.08x faster                                        |
| telco                    | 7.16 ms                                                      | 6.75 ms: 1.06x faster                                        |
| xml_etree_generate       | 85.3 ms                                                      | 81.0 ms: 1.05x faster                                        |
| pidigits                 | 264 ms                                                       | 252 ms: 1.05x faster                                         |
| regex_effbot             | 3.61 ms                                                      | 3.46 ms: 1.04x faster                                        |
| regex_dna                | 240 ms                                                       | 231 ms: 1.04x faster                                         |
| sqlalchemy_declarative   | 161 ms                                                       | 154 ms: 1.04x faster                                         |
| aiohttp                  | 1.02 ms                                                      | 980 us: 1.04x faster                                         |
| xml_etree_process        | 58.3 ms                                                      | 56.3 ms: 1.04x faster                                        |
| pprint_safe_repr         | 808 ms                                                       | 784 ms: 1.03x faster                                         |
| gunicorn                 | 1.01 ms                                                      | 981 us: 1.03x faster                                         |
| docutils                 | 2.89 sec                                                     | 2.83 sec: 1.02x faster                                       |
| pprint_pformat           | 1.64 sec                                                     | 1.62 sec: 1.02x faster                                       |
| pycparser                | 1.29 sec                                                     | 1.28 sec: 1.01x faster                                       |
| deepcopy_reduce          | 3.41 us                                                      | 3.39 us: 1.01x faster                                        |
| 2to3                     | 285 ms                                                       | 285 ms: 1.00x slower                                         |
| regex_v8                 | 24.4 ms                                                      | 24.5 ms: 1.00x slower                                        |
| pickle_pure_python       | 319 us                                                       | 321 us: 1.00x slower                                         |
| sqlglot_optimize         | 58.4 ms                                                      | 58.7 ms: 1.01x slower                                        |
| crypto_pyaes             | 82.4 ms                                                      | 83.1 ms: 1.01x slower                                        |
| unpickle_list            | 4.65 us                                                      | 4.69 us: 1.01x slower                                        |
| pathlib                  | 18.7 ms                                                      | 18.9 ms: 1.01x slower                                        |
| xml_etree_iterparse      | 104 ms                                                       | 105 ms: 1.01x slower                                         |
| sqlglot_normalize        | 119 ms                                                       | 122 ms: 1.02x slower                                         |
| dask                     | 394 ms                                                       | 402 ms: 1.02x slower                                         |
| django_template          | 38.7 ms                                                      | 39.7 ms: 1.03x slower                                        |
| meteor_contest           | 126 ms                                                       | 130 ms: 1.03x slower                                         |
| create_gc_cycles         | 1.58 ms                                                      | 1.63 ms: 1.03x slower                                        |
| raytrace                 | 301 ms                                                       | 311 ms: 1.03x slower                                         |
| pyflate                  | 442 ms                                                       | 458 ms: 1.04x slower                                         |
| logging_format           | 7.29 us                                                      | 7.58 us: 1.04x slower                                        |
| bench_thread_pool        | 956 us                                                       | 995 us: 1.04x slower                                         |
| deepcopy_memo            | 36.6 us                                                      | 38.1 us: 1.04x slower                                        |
| dulwich_log              | 64.9 ms                                                      | 67.6 ms: 1.04x slower                                        |
| deepcopy                 | 371 us                                                       | 387 us: 1.04x slower                                         |
| tomli_loads              | 2.17 sec                                                     | 2.27 sec: 1.05x slower                                       |
| chameleon                | 7.27 ms                                                      | 7.63 ms: 1.05x slower                                        |
| sqlalchemy_imperative    | 18.6 ms                                                      | 19.6 ms: 1.06x slower                                        |
| sqlglot_transpile        | 1.80 ms                                                      | 1.91 ms: 1.06x slower                                        |
| json                     | 5.17 ms                                                      | 5.48 ms: 1.06x slower                                        |
| logging_simple           | 6.64 us                                                      | 7.05 us: 1.06x slower                                        |
| sympy_integrate          | 24.0 ms                                                      | 25.6 ms: 1.07x slower                                        |
| mako                     | 10.1 ms                                                      | 10.8 ms: 1.07x slower                                        |
| regex_compile            | 145 ms                                                       | 155 ms: 1.07x slower                                         |
| scimark_sor              | 107 ms                                                       | 115 ms: 1.07x slower                                         |
| async_tree_cpu_io_mixed  | 704 ms                                                       | 758 ms: 1.08x slower                                         |
| xml_etree_parse          | 147 ms                                                       | 159 ms: 1.08x slower                                         |
| logging_silent           | 93.3 ns                                                      | 101 ns: 1.08x slower                                         |
| nbody                    | 88.2 ms                                                      | 95.6 ms: 1.08x slower                                        |
| nqueens                  | 90.1 ms                                                      | 98.5 ms: 1.09x slower                                        |
| sympy_str                | 305 ms                                                       | 334 ms: 1.09x slower                                         |
| sqlglot_parse            | 1.41 ms                                                      | 1.55 ms: 1.10x slower                                        |
| async_tree_io            | 1.06 sec                                                     | 1.17 sec: 1.11x slower                                       |
| sympy_expand             | 492 ms                                                       | 550 ms: 1.12x slower                                         |
| mdp                      | 2.56 sec                                                     | 2.86 sec: 1.12x slower                                       |
| sympy_sum                | 163 ms                                                       | 183 ms: 1.13x slower                                         |
| async_tree_none          | 459 ms                                                       | 522 ms: 1.14x slower                                         |
| async_tree_memoization   | 554 ms                                                       | 630 ms: 1.14x slower                                         |
| go                       | 149 ms                                                       | 170 ms: 1.14x slower                                         |
| comprehensions           | 21.8 us                                                      | 24.9 us: 1.14x slower                                        |
| scimark_lu               | 98.6 ms                                                      | 113 ms: 1.15x slower                                         |
| richards                 | 45.1 ms                                                      | 52.2 ms: 1.16x slower                                        |
| unpickle_pure_python     | 210 us                                                       | 243 us: 1.16x slower                                         |
| chaos                    | 64.1 ms                                                      | 75.0 ms: 1.17x slower                                        |
| json_loads               | 24.3 us                                                      | 28.4 us: 1.17x slower                                        |
| hexiom                   | 5.97 ms                                                      | 7.06 ms: 1.18x slower                                        |
| coroutines               | 23.1 ms                                                      | 27.8 ms: 1.21x slower                                        |
| fannkuch                 | 362 ms                                                       | 441 ms: 1.22x slower                                         |
| deltablue                | 3.24 ms                                                      | 4.06 ms: 1.25x slower                                        |
| richards_super           | 50.8 ms                                                      | 65.2 ms: 1.28x slower                                        |
| json_dumps               | 10.3 ms                                                      | 13.4 ms: 1.31x slower                                        |
| mypy2                    | 365 ms                                                       | 535 ms: 1.47x slower                                         |
| generators               | 37.3 ms                                                      | 54.7 ms: 1.47x slower                                        |
| asyncio_tcp_ssl          | 1.57 sec                                                     | 3.07 sec: 1.95x slower                                       |
| asyncio_tcp              | 380 ms                                                       | 751 ms: 1.98x slower                                         |
| typing_runtime_protocols | 150 us                                                       | 525 us: 3.50x slower                                         |
| Geometric mean           | (ref)                                                        | 1.07x slower                                                 |

Benchmark hidden because not significant (5): tornado_http, pickle, gc_traversal, scimark_monte_carlo, spectral_norm
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
Ignored benchmarks (6) of results/bm-20230606-3.11.4-d2340ef/bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
