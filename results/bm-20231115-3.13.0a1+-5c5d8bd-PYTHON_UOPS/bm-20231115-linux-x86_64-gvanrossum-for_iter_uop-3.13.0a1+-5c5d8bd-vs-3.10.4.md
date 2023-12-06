
# Results vs. 3.10.4

- fork: gvanrossum
- ref: for_iter_uop
- machine: linux-x86_64
- commit hash: 5c5d8bd
- commit date: 2023-11-15
- overall geometric mean: 1.20x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 291 ms: 1.19x faster                                               |
| chameleon      | 9.84 ms                                                | 7.65 ms: 1.29x faster                                              |
| docutils       | 3.26 sec                                               | 2.75 sec: 1.19x faster                                             |
| tornado_http   | 131 ms                                                 | 100 ms: 1.31x faster                                               |
| Geometric mean | (ref)                                                  | 1.24x faster                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 465 ms: 1.58x faster                                               |
| async_tree_memoization  | 867 ms                                                 | 596 ms: 1.46x faster                                               |
| async_tree_io           | 1.79 sec                                               | 1.24 sec: 1.45x faster                                             |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 742 ms: 1.36x faster                                               |
| Geometric mean          | (ref)                                                  | 1.46x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 121 ms: 1.22x faster                                               |
| float          | 116 ms                                                 | 109 ms: 1.07x faster                                               |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                               |
| Geometric mean | (ref)                                                  | 1.10x faster                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 167 ms: 1.11x faster                                               |
| regex_dna      | 215 ms                                                 | 219 ms: 1.02x slower                                               |
| regex_effbot   | 3.41 ms                                                | 3.65 ms: 1.07x slower                                              |
| Geometric mean | (ref)                                                  | 1.01x faster                                                       |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 307 us: 1.57x faster                                               |
| json_dumps           | 14.3 ms                                                | 10.7 ms: 1.34x faster                                              |
| unpickle_pure_python | 327 us                                                 | 255 us: 1.28x faster                                               |
| xml_etree_process    | 79.8 ms                                                | 65.6 ms: 1.22x faster                                              |
| json_loads           | 31.4 us                                                | 28.8 us: 1.09x faster                                              |
| xml_etree_parse      | 171 ms                                                 | 160 ms: 1.07x faster                                               |
| xml_etree_generate   | 100.0 ms                                               | 96.8 ms: 1.03x faster                                              |
| tomli_loads          | 3.06 sec                                               | 2.99 sec: 1.02x faster                                             |
| unpickle             | 14.9 us                                                | 14.7 us: 1.01x faster                                              |
| pickle_list          | 5.05 us                                                | 5.01 us: 1.01x faster                                              |
| unpickle_list        | 5.10 us                                                | 5.22 us: 1.03x slower                                              |
| xml_etree_iterparse  | 116 ms                                                 | 120 ms: 1.04x slower                                               |
| pickle               | 10.7 us                                                | 11.8 us: 1.10x slower                                              |
| pickle_dict          | 30.0 us                                                | 33.2 us: 1.11x slower                                              |
| Geometric mean       | (ref)                                                  | 1.09x faster                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                              |
| python_startup_no_site | 5.87 ms                                                | 9.07 ms: 1.54x slower                                              |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 16.2 ms: 1.01x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 127 us: 4.42x faster                                               |
| generators               | 78.9 ms                                                | 29.2 ms: 2.71x faster                                              |
| asyncio_tcp              | 918 ms                                                 | 501 ms: 1.83x faster                                               |
| logging_silent           | 189 ns                                                 | 112 ns: 1.68x faster                                               |
| scimark_sor              | 214 ms                                                 | 129 ms: 1.66x faster                                               |
| richards_super           | 95.6 ms                                                | 59.9 ms: 1.60x faster                                              |
| raytrace                 | 498 ms                                                 | 312 ms: 1.59x faster                                               |
| async_tree_none          | 732 ms                                                 | 465 ms: 1.58x faster                                               |
| pickle_pure_python       | 482 us                                                 | 307 us: 1.57x faster                                               |
| coroutines               | 34.5 ms                                                | 22.4 ms: 1.54x faster                                              |
| sqlglot_parse            | 2.15 ms                                                | 1.42 ms: 1.51x faster                                              |
| richards                 | 79.4 ms                                                | 52.6 ms: 1.51x faster                                              |
| chaos                    | 114 ms                                                 | 77.2 ms: 1.48x faster                                              |
| sqlglot_transpile        | 2.55 ms                                                | 1.74 ms: 1.46x faster                                              |
| async_tree_memoization   | 867 ms                                                 | 596 ms: 1.46x faster                                               |
| async_tree_io            | 1.79 sec                                               | 1.24 sec: 1.45x faster                                             |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                             |
| unpack_sequence          | 65.7 ns                                                | 46.0 ns: 1.43x faster                                              |
| crypto_pyaes             | 127 ms                                                 | 90.8 ms: 1.39x faster                                              |
| scimark_lu               | 175 ms                                                 | 126 ms: 1.39x faster                                               |
| deltablue                | 7.81 ms                                                | 5.64 ms: 1.39x faster                                              |
| go                       | 238 ms                                                 | 172 ms: 1.38x faster                                               |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                              |
| scimark_monte_carlo      | 118 ms                                                 | 86.4 ms: 1.36x faster                                              |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 742 ms: 1.36x faster                                               |
| deepcopy_memo            | 58.8 us                                                | 43.4 us: 1.36x faster                                              |
| json_dumps               | 14.3 ms                                                | 10.7 ms: 1.34x faster                                              |
| deepcopy_reduce          | 4.17 us                                                | 3.12 us: 1.33x faster                                              |
| deepcopy                 | 481 us                                                 | 365 us: 1.32x faster                                               |
| logging_simple           | 8.27 us                                                | 6.28 us: 1.32x faster                                              |
| tornado_http             | 131 ms                                                 | 100 ms: 1.31x faster                                               |
| logging_format           | 9.07 us                                                | 7.02 us: 1.29x faster                                              |
| chameleon                | 9.84 ms                                                | 7.65 ms: 1.29x faster                                              |
| unpickle_pure_python     | 327 us                                                 | 255 us: 1.28x faster                                               |
| mypy2                    | 442 ms                                                 | 358 ms: 1.24x faster                                               |
| pycparser                | 1.57 sec                                               | 1.27 sec: 1.23x faster                                             |
| nbody                    | 148 ms                                                 | 121 ms: 1.22x faster                                               |
| xml_etree_process        | 79.8 ms                                                | 65.6 ms: 1.22x faster                                              |
| pprint_safe_repr         | 1.01 sec                                               | 841 ms: 1.21x faster                                               |
| pprint_pformat           | 2.10 sec                                               | 1.74 sec: 1.21x faster                                             |
| sqlglot_normalize        | 141 ms                                                 | 119 ms: 1.19x faster                                               |
| docutils                 | 3.26 sec                                               | 2.75 sec: 1.19x faster                                             |
| 2to3                     | 346 ms                                                 | 291 ms: 1.19x faster                                               |
| pyflate                  | 708 ms                                                 | 599 ms: 1.18x faster                                               |
| dask                     | 432 ms                                                 | 372 ms: 1.16x faster                                               |
| sympy_sum                | 190 ms                                                 | 166 ms: 1.14x faster                                               |
| sympy_integrate          | 25.4 ms                                                | 22.3 ms: 1.14x faster                                              |
| sqlglot_optimize         | 68.7 ms                                                | 60.9 ms: 1.13x faster                                              |
| sympy_expand             | 558 ms                                                 | 497 ms: 1.12x faster                                               |
| regex_compile            | 186 ms                                                 | 167 ms: 1.11x faster                                               |
| bench_thread_pool        | 966 us                                                 | 873 us: 1.11x faster                                               |
| sympy_str                | 337 ms                                                 | 306 ms: 1.10x faster                                               |
| dulwich_log              | 77.0 ms                                                | 69.9 ms: 1.10x faster                                              |
| json_loads               | 31.4 us                                                | 28.8 us: 1.09x faster                                              |
| create_gc_cycles         | 1.61 ms                                                | 1.49 ms: 1.08x faster                                              |
| pathlib                  | 20.3 ms                                                | 18.8 ms: 1.08x faster                                              |
| float                    | 116 ms                                                 | 109 ms: 1.07x faster                                               |
| xml_etree_parse          | 171 ms                                                 | 160 ms: 1.07x faster                                               |
| json                     | 5.67 ms                                                | 5.30 ms: 1.07x faster                                              |
| mdp                      | 2.93 sec                                               | 2.79 sec: 1.05x faster                                             |
| comprehensions           | 28.5 us                                                | 27.2 us: 1.05x faster                                              |
| xml_etree_generate       | 100.0 ms                                               | 96.8 ms: 1.03x faster                                              |
| sqlite_synth             | 3.02 us                                                | 2.96 us: 1.02x faster                                              |
| tomli_loads              | 3.06 sec                                               | 2.99 sec: 1.02x faster                                             |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                               |
| fannkuch                 | 527 ms                                                 | 522 ms: 1.01x faster                                               |
| unpickle                 | 14.9 us                                                | 14.7 us: 1.01x faster                                              |
| pickle_list              | 5.05 us                                                | 5.01 us: 1.01x faster                                              |
| mako                     | 16.3 ms                                                | 16.2 ms: 1.01x faster                                              |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                               |
| regex_dna                | 215 ms                                                 | 219 ms: 1.02x slower                                               |
| unpickle_list            | 5.10 us                                                | 5.22 us: 1.03x slower                                              |
| xml_etree_iterparse      | 116 ms                                                 | 120 ms: 1.04x slower                                               |
| meteor_contest           | 119 ms                                                 | 124 ms: 1.04x slower                                               |
| async_generators         | 442 ms                                                 | 460 ms: 1.04x slower                                               |
| nqueens                  | 107 ms                                                 | 113 ms: 1.06x slower                                               |
| hexiom                   | 10.3 ms                                                | 10.9 ms: 1.06x slower                                              |
| regex_effbot             | 3.41 ms                                                | 3.65 ms: 1.07x slower                                              |
| pickle                   | 10.7 us                                                | 11.8 us: 1.10x slower                                              |
| gc_traversal             | 3.43 ms                                                | 3.80 ms: 1.11x slower                                              |
| pickle_dict              | 30.0 us                                                | 33.2 us: 1.11x slower                                              |
| spectral_norm            | 163 ms                                                 | 186 ms: 1.14x slower                                               |
| coverage                 | 82.0 ms                                                | 94.4 ms: 1.15x slower                                              |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 7.36 ms: 1.21x slower                                              |
| telco                    | 7.01 ms                                                | 8.86 ms: 1.26x slower                                              |
| python_startup_no_site   | 5.87 ms                                                | 9.07 ms: 1.54x slower                                              |
| Geometric mean           | (ref)                                                  | 1.20x faster                                                       |

Benchmark hidden because not significant (3): scimark_fft, bench_mp_pool, regex_v8
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231115-3.13.0a1+-5c5d8bd-PYTHON_UOPS/bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-5c5d8bd.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.13x
- 95% likely to have a speedup of 1.12x
- 99% likely to have a speedup of 1.10x
