
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 4cb7a87
- commit date: 2023-11-21
- overall geometric mean: 1.23x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 291 ms: 1.19x faster                                           |
| chameleon      | 9.84 ms                                                | 7.48 ms: 1.32x faster                                          |
| docutils       | 3.26 sec                                               | 2.73 sec: 1.19x faster                                         |
| tornado_http   | 131 ms                                                 | 99.8 ms: 1.31x faster                                          |
| Geometric mean | (ref)                                                  | 1.25x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 459 ms: 1.59x faster                                           |
| async_tree_memoization  | 867 ms                                                 | 585 ms: 1.48x faster                                           |
| async_tree_io           | 1.79 sec                                               | 1.23 sec: 1.46x faster                                         |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 737 ms: 1.37x faster                                           |
| Geometric mean          | (ref)                                                  | 1.47x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 116 ms                                                 | 98.5 ms: 1.18x faster                                          |
| nbody          | 148 ms                                                 | 128 ms: 1.16x faster                                           |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                           |
| Geometric mean | (ref)                                                  | 1.11x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 162 ms: 1.15x faster                                           |
| regex_v8       | 26.2 ms                                                | 25.6 ms: 1.02x faster                                          |
| regex_dna      | 215 ms                                                 | 217 ms: 1.01x slower                                           |
| regex_effbot   | 3.41 ms                                                | 3.72 ms: 1.09x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 308 us: 1.56x faster                                           |
| unpickle_pure_python | 327 us                                                 | 242 us: 1.35x faster                                           |
| json_dumps           | 14.3 ms                                                | 10.8 ms: 1.33x faster                                          |
| xml_etree_process    | 79.8 ms                                                | 63.0 ms: 1.27x faster                                          |
| tomli_loads          | 3.06 sec                                               | 2.73 sec: 1.12x faster                                         |
| json_loads           | 31.4 us                                                | 28.2 us: 1.11x faster                                          |
| xml_etree_generate   | 100.0 ms                                               | 92.3 ms: 1.08x faster                                          |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                           |
| xml_etree_iterparse  | 116 ms                                                 | 115 ms: 1.01x faster                                           |
| pickle_list          | 5.05 us                                                | 5.10 us: 1.01x slower                                          |
| unpickle_list        | 5.10 us                                                | 5.20 us: 1.02x slower                                          |
| pickle               | 10.7 us                                                | 11.6 us: 1.09x slower                                          |
| pickle_dict          | 30.0 us                                                | 34.9 us: 1.16x slower                                          |
| Geometric mean       | (ref)                                                  | 1.10x faster                                                   |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                          |
| python_startup_no_site | 5.87 ms                                                | 9.03 ms: 1.54x slower                                          |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 15.2 ms: 1.07x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 123 us: 4.54x faster                                           |
| generators               | 78.9 ms                                                | 29.7 ms: 2.66x faster                                          |
| asyncio_tcp              | 918 ms                                                 | 494 ms: 1.86x faster                                           |
| logging_silent           | 189 ns                                                 | 109 ns: 1.74x faster                                           |
| richards_super           | 95.6 ms                                                | 55.3 ms: 1.73x faster                                          |
| scimark_sor              | 214 ms                                                 | 127 ms: 1.69x faster                                           |
| async_tree_none          | 732 ms                                                 | 459 ms: 1.59x faster                                           |
| richards                 | 79.4 ms                                                | 50.1 ms: 1.59x faster                                          |
| raytrace                 | 498 ms                                                 | 318 ms: 1.57x faster                                           |
| unpack_sequence          | 65.7 ns                                                | 42.0 ns: 1.56x faster                                          |
| pickle_pure_python       | 482 us                                                 | 308 us: 1.56x faster                                           |
| sqlglot_parse            | 2.15 ms                                                | 1.39 ms: 1.54x faster                                          |
| coroutines               | 34.5 ms                                                | 22.4 ms: 1.54x faster                                          |
| deltablue                | 7.81 ms                                                | 5.12 ms: 1.53x faster                                          |
| sqlglot_transpile        | 2.55 ms                                                | 1.71 ms: 1.49x faster                                          |
| async_tree_memoization   | 867 ms                                                 | 585 ms: 1.48x faster                                           |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.47x faster                                           |
| chaos                    | 114 ms                                                 | 78.0 ms: 1.46x faster                                          |
| async_tree_io            | 1.79 sec                                               | 1.23 sec: 1.46x faster                                         |
| go                       | 238 ms                                                 | 165 ms: 1.44x faster                                           |
| crypto_pyaes             | 127 ms                                                 | 88.4 ms: 1.43x faster                                          |
| deepcopy_memo            | 58.8 us                                                | 41.1 us: 1.43x faster                                          |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.43x faster                                         |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                          |
| scimark_monte_carlo      | 118 ms                                                 | 86.1 ms: 1.37x faster                                          |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 737 ms: 1.37x faster                                           |
| logging_simple           | 8.27 us                                                | 6.09 us: 1.36x faster                                          |
| unpickle_pure_python     | 327 us                                                 | 242 us: 1.35x faster                                           |
| deepcopy                 | 481 us                                                 | 361 us: 1.33x faster                                           |
| json_dumps               | 14.3 ms                                                | 10.8 ms: 1.33x faster                                          |
| logging_format           | 9.07 us                                                | 6.83 us: 1.33x faster                                          |
| chameleon                | 9.84 ms                                                | 7.48 ms: 1.32x faster                                          |
| deepcopy_reduce          | 4.17 us                                                | 3.18 us: 1.31x faster                                          |
| tornado_http             | 131 ms                                                 | 99.8 ms: 1.31x faster                                          |
| pyflate                  | 708 ms                                                 | 547 ms: 1.29x faster                                           |
| pycparser                | 1.57 sec                                               | 1.22 sec: 1.28x faster                                         |
| xml_etree_process        | 79.8 ms                                                | 63.0 ms: 1.27x faster                                          |
| mypy2                    | 442 ms                                                 | 356 ms: 1.24x faster                                           |
| comprehensions           | 28.5 us                                                | 23.1 us: 1.24x faster                                          |
| sqlglot_normalize        | 141 ms                                                 | 115 ms: 1.23x faster                                           |
| pprint_safe_repr         | 1.01 sec                                               | 824 ms: 1.23x faster                                           |
| pprint_pformat           | 2.10 sec                                               | 1.72 sec: 1.22x faster                                         |
| docutils                 | 3.26 sec                                               | 2.73 sec: 1.19x faster                                         |
| 2to3                     | 346 ms                                                 | 291 ms: 1.19x faster                                           |
| float                    | 116 ms                                                 | 98.5 ms: 1.18x faster                                          |
| sympy_integrate          | 25.4 ms                                                | 21.6 ms: 1.18x faster                                          |
| sympy_sum                | 190 ms                                                 | 162 ms: 1.17x faster                                           |
| sqlglot_optimize         | 68.7 ms                                                | 58.5 ms: 1.17x faster                                          |
| dask                     | 432 ms                                                 | 371 ms: 1.16x faster                                           |
| nbody                    | 148 ms                                                 | 128 ms: 1.16x faster                                           |
| regex_compile            | 186 ms                                                 | 162 ms: 1.15x faster                                           |
| sympy_expand             | 558 ms                                                 | 492 ms: 1.14x faster                                           |
| sympy_str                | 337 ms                                                 | 297 ms: 1.13x faster                                           |
| bench_thread_pool        | 966 us                                                 | 860 us: 1.12x faster                                           |
| hexiom                   | 10.3 ms                                                | 9.17 ms: 1.12x faster                                          |
| tomli_loads              | 3.06 sec                                               | 2.73 sec: 1.12x faster                                         |
| fannkuch                 | 527 ms                                                 | 471 ms: 1.12x faster                                           |
| dulwich_log              | 77.0 ms                                                | 69.1 ms: 1.11x faster                                          |
| json_loads               | 31.4 us                                                | 28.2 us: 1.11x faster                                          |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.09x faster                                          |
| xml_etree_generate       | 100.0 ms                                               | 92.3 ms: 1.08x faster                                          |
| json                     | 5.67 ms                                                | 5.25 ms: 1.08x faster                                          |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                           |
| mako                     | 16.3 ms                                                | 15.2 ms: 1.07x faster                                          |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                          |
| nqueens                  | 107 ms                                                 | 100 ms: 1.06x faster                                           |
| sqlite_synth             | 3.02 us                                                | 2.89 us: 1.04x faster                                          |
| regex_v8                 | 26.2 ms                                                | 25.6 ms: 1.02x faster                                          |
| mdp                      | 2.93 sec                                               | 2.88 sec: 1.02x faster                                         |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                           |
| xml_etree_iterparse      | 116 ms                                                 | 115 ms: 1.01x faster                                           |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                           |
| meteor_contest           | 119 ms                                                 | 118 ms: 1.01x faster                                           |
| pickle_list              | 5.05 us                                                | 5.10 us: 1.01x slower                                          |
| regex_dna                | 215 ms                                                 | 217 ms: 1.01x slower                                           |
| unpickle_list            | 5.10 us                                                | 5.20 us: 1.02x slower                                          |
| async_generators         | 442 ms                                                 | 457 ms: 1.03x slower                                           |
| scimark_fft              | 454 ms                                                 | 475 ms: 1.05x slower                                           |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.55 ms: 1.07x slower                                          |
| pickle                   | 10.7 us                                                | 11.6 us: 1.09x slower                                          |
| regex_effbot             | 3.41 ms                                                | 3.72 ms: 1.09x slower                                          |
| gc_traversal             | 3.43 ms                                                | 3.87 ms: 1.13x slower                                          |
| coverage                 | 82.0 ms                                                | 95.2 ms: 1.16x slower                                          |
| pickle_dict              | 30.0 us                                                | 34.9 us: 1.16x slower                                          |
| telco                    | 7.01 ms                                                | 8.66 ms: 1.23x slower                                          |
| python_startup_no_site   | 5.87 ms                                                | 9.03 ms: 1.54x slower                                          |
| Geometric mean           | (ref)                                                  | 1.23x faster                                                   |

Benchmark hidden because not significant (3): spectral_norm, bench_mp_pool, unpickle
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231121-3.13.0a1+-4cb7a87/bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1+-4cb7a87.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.14x
