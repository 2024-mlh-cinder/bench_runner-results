
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b1
- machine: linux-x86_64
- commit hash: 5612078
- commit date: 2023-05-22
- overall geometric mean: 1.33x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 268 ms: 1.29x faster                                       |
| docutils       | 3.26 sec                                               | 2.71 sec: 1.20x faster                                     |
| tornado_http   | 131 ms                                                 | 99.2 ms: 1.32x faster                                      |
| Geometric mean | (ref)                                                  | 1.27x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 469 ms: 1.56x faster                                       |
| async_tree_io           | 1.79 sec                                               | 1.16 sec: 1.54x faster                                     |
| async_tree_memoization  | 867 ms                                                 | 572 ms: 1.51x faster                                       |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 708 ms: 1.42x faster                                       |
| Geometric mean          | (ref)                                                  | 1.51x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 148 ms                                                 | 88.9 ms: 1.67x faster                                      |
| float          | 116 ms                                                 | 80.7 ms: 1.44x faster                                      |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                  | 1.33x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 144 ms: 1.29x faster                                       |
| regex_v8       | 26.2 ms                                                | 21.8 ms: 1.20x faster                                      |
| regex_dna      | 215 ms                                                 | 208 ms: 1.03x faster                                       |
| regex_effbot   | 3.41 ms                                                | 3.54 ms: 1.04x slower                                      |
| Geometric mean | (ref)                                                  | 1.12x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 312 us: 1.55x faster                                       |
| unpickle_pure_python | 327 us                                                 | 216 us: 1.51x faster                                       |
| json_dumps           | 14.3 ms                                                | 9.76 ms: 1.47x faster                                      |
| tomli_loads          | 3.06 sec                                               | 2.18 sec: 1.40x faster                                     |
| xml_etree_process    | 79.8 ms                                                | 59.0 ms: 1.35x faster                                      |
| json_loads           | 31.4 us                                                | 25.1 us: 1.25x faster                                      |
| xml_etree_generate   | 100.0 ms                                               | 85.6 ms: 1.17x faster                                      |
| xml_etree_iterparse  | 116 ms                                                 | 103 ms: 1.12x faster                                       |
| xml_etree_parse      | 171 ms                                                 | 153 ms: 1.12x faster                                       |
| pickle_list          | 5.05 us                                                | 4.73 us: 1.07x faster                                      |
| pickle               | 10.7 us                                                | 10.6 us: 1.01x faster                                      |
| unpickle_list        | 5.10 us                                                | 5.17 us: 1.01x slower                                      |
| pickle_dict          | 30.0 us                                                | 33.3 us: 1.11x slower                                      |
| Geometric mean       | (ref)                                                  | 1.19x faster                                               |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 9.34 ms: 1.53x faster                                      |
| python_startup_no_site | 5.87 ms                                                | 6.78 ms: 1.16x slower                                      |
| Geometric mean         | (ref)                                                  | 1.15x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 16.3 ms                                                | 10.8 ms: 1.50x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230522-linux-x86_64-python-v3.12.0b1-3.12.0b1-5612078 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 140 us: 4.00x faster                                       |
| generators               | 78.9 ms                                                | 31.4 ms: 2.51x faster                                      |
| deltablue                | 7.81 ms                                                | 3.44 ms: 2.27x faster                                      |
| richards_super           | 95.6 ms                                                | 49.8 ms: 1.92x faster                                      |
| logging_silent           | 189 ns                                                 | 100 ns: 1.89x faster                                       |
| richards                 | 79.4 ms                                                | 43.6 ms: 1.82x faster                                      |
| asyncio_tcp              | 918 ms                                                 | 513 ms: 1.79x faster                                       |
| chaos                    | 114 ms                                                 | 64.6 ms: 1.77x faster                                      |
| go                       | 238 ms                                                 | 136 ms: 1.75x faster                                       |
| scimark_sor              | 214 ms                                                 | 123 ms: 1.75x faster                                       |
| hexiom                   | 10.3 ms                                                | 6.12 ms: 1.68x faster                                      |
| raytrace                 | 498 ms                                                 | 298 ms: 1.67x faster                                       |
| nbody                    | 148 ms                                                 | 88.9 ms: 1.67x faster                                      |
| crypto_pyaes             | 127 ms                                                 | 77.9 ms: 1.63x faster                                      |
| scimark_monte_carlo      | 118 ms                                                 | 72.7 ms: 1.62x faster                                      |
| sqlglot_parse            | 2.15 ms                                                | 1.33 ms: 1.61x faster                                      |
| pyflate                  | 708 ms                                                 | 443 ms: 1.60x faster                                       |
| coroutines               | 34.5 ms                                                | 21.9 ms: 1.57x faster                                      |
| deepcopy_memo            | 58.8 us                                                | 37.6 us: 1.56x faster                                      |
| async_tree_none          | 732 ms                                                 | 469 ms: 1.56x faster                                       |
| sqlglot_transpile        | 2.55 ms                                                | 1.64 ms: 1.55x faster                                      |
| scimark_lu               | 175 ms                                                 | 113 ms: 1.55x faster                                       |
| pickle_pure_python       | 482 us                                                 | 312 us: 1.55x faster                                       |
| async_tree_io            | 1.79 sec                                               | 1.16 sec: 1.54x faster                                     |
| python_startup           | 14.3 ms                                                | 9.34 ms: 1.53x faster                                      |
| async_tree_memoization   | 867 ms                                                 | 572 ms: 1.51x faster                                       |
| unpickle_pure_python     | 327 us                                                 | 216 us: 1.51x faster                                       |
| spectral_norm            | 163 ms                                                 | 108 ms: 1.51x faster                                       |
| mako                     | 16.3 ms                                                | 10.8 ms: 1.50x faster                                      |
| json_dumps               | 14.3 ms                                                | 9.76 ms: 1.47x faster                                      |
| float                    | 116 ms                                                 | 80.7 ms: 1.44x faster                                      |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                     |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 708 ms: 1.42x faster                                       |
| pprint_pformat           | 2.10 sec                                               | 1.50 sec: 1.40x faster                                     |
| tomli_loads              | 3.06 sec                                               | 2.18 sec: 1.40x faster                                     |
| unpack_sequence          | 65.7 ns                                                | 47.3 ns: 1.39x faster                                      |
| comprehensions           | 28.5 us                                                | 20.6 us: 1.39x faster                                      |
| pprint_safe_repr         | 1.01 sec                                               | 733 ms: 1.38x faster                                       |
| fannkuch                 | 527 ms                                                 | 382 ms: 1.38x faster                                       |
| xml_etree_process        | 79.8 ms                                                | 59.0 ms: 1.35x faster                                      |
| deepcopy                 | 481 us                                                 | 361 us: 1.33x faster                                       |
| tornado_http             | 131 ms                                                 | 99.2 ms: 1.32x faster                                      |
| pycparser                | 1.57 sec                                               | 1.19 sec: 1.32x faster                                     |
| nqueens                  | 107 ms                                                 | 81.4 ms: 1.31x faster                                      |
| deepcopy_reduce          | 4.17 us                                                | 3.18 us: 1.31x faster                                      |
| logging_simple           | 8.27 us                                                | 6.33 us: 1.31x faster                                      |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                       |
| regex_compile            | 186 ms                                                 | 144 ms: 1.29x faster                                       |
| 2to3                     | 346 ms                                                 | 268 ms: 1.29x faster                                       |
| logging_format           | 9.07 us                                                | 7.09 us: 1.28x faster                                      |
| scimark_fft              | 454 ms                                                 | 356 ms: 1.28x faster                                       |
| sqlglot_optimize         | 68.7 ms                                                | 54.1 ms: 1.27x faster                                      |
| json_loads               | 31.4 us                                                | 25.1 us: 1.25x faster                                      |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.05 ms: 1.21x faster                                      |
| docutils                 | 3.26 sec                                               | 2.71 sec: 1.20x faster                                     |
| regex_v8                 | 26.2 ms                                                | 21.8 ms: 1.20x faster                                      |
| json                     | 5.67 ms                                                | 4.77 ms: 1.19x faster                                      |
| sqlalchemy_imperative    | 21.9 ms                                                | 18.6 ms: 1.18x faster                                      |
| sqlalchemy_declarative   | 170 ms                                                 | 145 ms: 1.17x faster                                       |
| bench_thread_pool        | 966 us                                                 | 827 us: 1.17x faster                                       |
| xml_etree_generate       | 100.0 ms                                               | 85.6 ms: 1.17x faster                                      |
| dulwich_log              | 77.0 ms                                                | 67.7 ms: 1.14x faster                                      |
| meteor_contest           | 119 ms                                                 | 105 ms: 1.13x faster                                       |
| xml_etree_iterparse      | 116 ms                                                 | 103 ms: 1.12x faster                                       |
| xml_etree_parse          | 171 ms                                                 | 153 ms: 1.12x faster                                       |
| sqlite_synth             | 3.02 us                                                | 2.72 us: 1.11x faster                                      |
| pathlib                  | 20.3 ms                                                | 18.3 ms: 1.11x faster                                      |
| mdp                      | 2.93 sec                                               | 2.68 sec: 1.10x faster                                     |
| create_gc_cycles         | 1.61 ms                                                | 1.50 ms: 1.08x faster                                      |
| pickle_list              | 5.05 us                                                | 4.73 us: 1.07x faster                                      |
| regex_dna                | 215 ms                                                 | 208 ms: 1.03x faster                                       |
| telco                    | 7.01 ms                                                | 6.84 ms: 1.03x faster                                      |
| pickle                   | 10.7 us                                                | 10.6 us: 1.01x faster                                      |
| unpickle_list            | 5.10 us                                                | 5.17 us: 1.01x slower                                      |
| async_generators         | 442 ms                                                 | 449 ms: 1.02x slower                                       |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                       |
| regex_effbot             | 3.41 ms                                                | 3.54 ms: 1.04x slower                                      |
| gc_traversal             | 3.43 ms                                                | 3.67 ms: 1.07x slower                                      |
| pickle_dict              | 30.0 us                                                | 33.3 us: 1.11x slower                                      |
| python_startup_no_site   | 5.87 ms                                                | 6.78 ms: 1.16x slower                                      |
| coverage                 | 82.0 ms                                                | 96.8 ms: 1.18x slower                                      |
| dask                     | 432 ms                                                 | 535 ms: 1.24x slower                                       |
| Geometric mean           | (ref)                                                  | 1.33x faster                                               |

Benchmark hidden because not significant (3): bench_mp_pool, unpickle, mypy2
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.26x
