
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.28x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 273 ms: 1.26x faster                                           |
| chameleon      | 9.84 ms                                                | 7.19 ms: 1.37x faster                                          |
| docutils       | 3.26 sec                                               | 2.67 sec: 1.22x faster                                         |
| tornado_http   | 131 ms                                                 | 97.0 ms: 1.35x faster                                          |
| Geometric mean | (ref)                                                  | 1.30x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 443 ms: 1.65x faster                                           |
| async_tree_memoization  | 867 ms                                                 | 568 ms: 1.53x faster                                           |
| async_tree_io           | 1.79 sec                                               | 1.20 sec: 1.49x faster                                         |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 714 ms: 1.41x faster                                           |
| Geometric mean          | (ref)                                                  | 1.52x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 98.4 ms: 1.51x faster                                          |
| float          | 116 ms                                                 | 84.9 ms: 1.37x faster                                          |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                  | 1.26x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 143 ms: 1.30x faster                                           |
| regex_v8       | 26.2 ms                                                | 26.0 ms: 1.01x faster                                          |
| regex_dna      | 215 ms                                                 | 222 ms: 1.03x slower                                           |
| regex_effbot   | 3.41 ms                                                | 3.71 ms: 1.09x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 305 us: 1.58x faster                                           |
| tomli_loads          | 3.06 sec                                               | 2.15 sec: 1.42x faster                                         |
| unpickle_pure_python | 327 us                                                 | 231 us: 1.42x faster                                           |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                          |
| xml_etree_process    | 79.8 ms                                                | 61.1 ms: 1.31x faster                                          |
| xml_etree_generate   | 100.0 ms                                               | 88.6 ms: 1.13x faster                                          |
| json_loads           | 31.4 us                                                | 28.1 us: 1.12x faster                                          |
| xml_etree_parse      | 171 ms                                                 | 161 ms: 1.06x faster                                           |
| xml_etree_iterparse  | 116 ms                                                 | 110 ms: 1.05x faster                                           |
| unpickle_list        | 5.10 us                                                | 4.96 us: 1.03x faster                                          |
| unpickle             | 14.9 us                                                | 15.7 us: 1.05x slower                                          |
| pickle               | 10.7 us                                                | 11.6 us: 1.09x slower                                          |
| pickle_dict          | 30.0 us                                                | 36.4 us: 1.22x slower                                          |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                   |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.37x faster                                          |
| python_startup_no_site | 5.87 ms                                                | 9.11 ms: 1.55x slower                                          |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.2 ms: 1.33x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 119 us: 4.69x faster                                           |
| generators               | 78.9 ms                                                | 28.7 ms: 2.75x faster                                          |
| deltablue                | 7.81 ms                                                | 4.07 ms: 1.92x faster                                          |
| asyncio_tcp              | 918 ms                                                 | 494 ms: 1.86x faster                                           |
| richards_super           | 95.6 ms                                                | 52.3 ms: 1.83x faster                                          |
| logging_silent           | 189 ns                                                 | 108 ns: 1.75x faster                                           |
| raytrace                 | 498 ms                                                 | 285 ms: 1.75x faster                                           |
| scimark_sor              | 214 ms                                                 | 123 ms: 1.75x faster                                           |
| chaos                    | 114 ms                                                 | 66.4 ms: 1.72x faster                                          |
| richards                 | 79.4 ms                                                | 47.3 ms: 1.68x faster                                          |
| async_tree_none          | 732 ms                                                 | 443 ms: 1.65x faster                                           |
| sqlglot_parse            | 2.15 ms                                                | 1.30 ms: 1.65x faster                                          |
| crypto_pyaes             | 127 ms                                                 | 78.0 ms: 1.62x faster                                          |
| go                       | 238 ms                                                 | 150 ms: 1.58x faster                                           |
| pickle_pure_python       | 482 us                                                 | 305 us: 1.58x faster                                           |
| sqlglot_transpile        | 2.55 ms                                                | 1.63 ms: 1.57x faster                                          |
| scimark_monte_carlo      | 118 ms                                                 | 76.4 ms: 1.54x faster                                          |
| async_tree_memoization   | 867 ms                                                 | 568 ms: 1.53x faster                                           |
| coroutines               | 34.5 ms                                                | 22.7 ms: 1.52x faster                                          |
| nbody                    | 148 ms                                                 | 98.4 ms: 1.51x faster                                          |
| scimark_lu               | 175 ms                                                 | 116 ms: 1.51x faster                                           |
| async_tree_io            | 1.79 sec                                               | 1.20 sec: 1.49x faster                                         |
| deepcopy_memo            | 58.8 us                                                | 39.6 us: 1.49x faster                                          |
| comprehensions           | 28.5 us                                                | 19.3 us: 1.48x faster                                          |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                         |
| pyflate                  | 708 ms                                                 | 493 ms: 1.44x faster                                           |
| tomli_loads              | 3.06 sec                                               | 2.15 sec: 1.42x faster                                         |
| logging_simple           | 8.27 us                                                | 5.84 us: 1.42x faster                                          |
| unpickle_pure_python     | 327 us                                                 | 231 us: 1.42x faster                                           |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 714 ms: 1.41x faster                                           |
| logging_format           | 9.07 us                                                | 6.45 us: 1.41x faster                                          |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                          |
| float                    | 116 ms                                                 | 84.9 ms: 1.37x faster                                          |
| hexiom                   | 10.3 ms                                                | 7.52 ms: 1.37x faster                                          |
| chameleon                | 9.84 ms                                                | 7.19 ms: 1.37x faster                                          |
| deepcopy                 | 481 us                                                 | 355 us: 1.36x faster                                           |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                          |
| tornado_http             | 131 ms                                                 | 97.0 ms: 1.35x faster                                          |
| deepcopy_reduce          | 4.17 us                                                | 3.11 us: 1.34x faster                                          |
| mako                     | 16.3 ms                                                | 12.2 ms: 1.33x faster                                          |
| pprint_pformat           | 2.10 sec                                               | 1.59 sec: 1.32x faster                                         |
| pprint_safe_repr         | 1.01 sec                                               | 775 ms: 1.31x faster                                           |
| xml_etree_process        | 79.8 ms                                                | 61.1 ms: 1.31x faster                                          |
| regex_compile            | 186 ms                                                 | 143 ms: 1.30x faster                                           |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.30x faster                                         |
| sqlglot_normalize        | 141 ms                                                 | 110 ms: 1.29x faster                                           |
| 2to3                     | 346 ms                                                 | 273 ms: 1.26x faster                                           |
| sqlglot_optimize         | 68.7 ms                                                | 55.8 ms: 1.23x faster                                          |
| fannkuch                 | 527 ms                                                 | 429 ms: 1.23x faster                                           |
| sympy_integrate          | 25.4 ms                                                | 20.7 ms: 1.22x faster                                          |
| scimark_fft              | 454 ms                                                 | 371 ms: 1.22x faster                                           |
| docutils                 | 3.26 sec                                               | 2.67 sec: 1.22x faster                                         |
| sympy_sum                | 190 ms                                                 | 157 ms: 1.21x faster                                           |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.06 ms: 1.21x faster                                          |
| sympy_str                | 337 ms                                                 | 280 ms: 1.20x faster                                           |
| sympy_expand             | 558 ms                                                 | 470 ms: 1.19x faster                                           |
| dask                     | 432 ms                                                 | 365 ms: 1.19x faster                                           |
| spectral_norm            | 163 ms                                                 | 138 ms: 1.18x faster                                           |
| unpack_sequence          | 65.7 ns                                                | 55.9 ns: 1.17x faster                                          |
| nqueens                  | 107 ms                                                 | 91.8 ms: 1.16x faster                                          |
| dulwich_log              | 77.0 ms                                                | 66.5 ms: 1.16x faster                                          |
| bench_thread_pool        | 966 us                                                 | 848 us: 1.14x faster                                           |
| xml_etree_generate       | 100.0 ms                                               | 88.6 ms: 1.13x faster                                          |
| json_loads               | 31.4 us                                                | 28.1 us: 1.12x faster                                          |
| pathlib                  | 20.3 ms                                                | 18.3 ms: 1.11x faster                                          |
| json                     | 5.67 ms                                                | 5.12 ms: 1.11x faster                                          |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.10x faster                                          |
| sqlite_synth             | 3.02 us                                                | 2.80 us: 1.08x faster                                          |
| xml_etree_parse          | 171 ms                                                 | 161 ms: 1.06x faster                                           |
| meteor_contest           | 119 ms                                                 | 112 ms: 1.06x faster                                           |
| xml_etree_iterparse      | 116 ms                                                 | 110 ms: 1.05x faster                                           |
| mdp                      | 2.93 sec                                               | 2.80 sec: 1.05x faster                                         |
| unpickle_list            | 5.10 us                                                | 4.96 us: 1.03x faster                                          |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                           |
| regex_v8                 | 26.2 ms                                                | 26.0 ms: 1.01x faster                                          |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                           |
| regex_dna                | 215 ms                                                 | 222 ms: 1.03x slower                                           |
| async_generators         | 442 ms                                                 | 465 ms: 1.05x slower                                           |
| unpickle                 | 14.9 us                                                | 15.7 us: 1.05x slower                                          |
| pickle                   | 10.7 us                                                | 11.6 us: 1.09x slower                                          |
| regex_effbot             | 3.41 ms                                                | 3.71 ms: 1.09x slower                                          |
| gc_traversal             | 3.43 ms                                                | 3.85 ms: 1.12x slower                                          |
| coverage                 | 82.0 ms                                                | 93.9 ms: 1.15x slower                                          |
| telco                    | 7.01 ms                                                | 8.29 ms: 1.18x slower                                          |
| pickle_dict              | 30.0 us                                                | 36.4 us: 1.22x slower                                          |
| python_startup_no_site   | 5.87 ms                                                | 9.11 ms: 1.55x slower                                          |
| mypy2                    | 442 ms                                                 | 861 ms: 1.95x slower                                           |
| Geometric mean           | (ref)                                                  | 1.28x faster                                                   |

Benchmark hidden because not significant (2): bench_mp_pool, pickle_list
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231128-3.13.0a2+-dfface9-JIT/bm-20231128-linux-x86_64-brandtbucher-justin-3.13.0a2+-dfface9.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.21x
