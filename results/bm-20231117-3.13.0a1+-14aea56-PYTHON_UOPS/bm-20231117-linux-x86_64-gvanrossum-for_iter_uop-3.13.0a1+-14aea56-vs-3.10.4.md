
# Results vs. 3.10.4

- fork: gvanrossum
- ref: for_iter_uop
- machine: linux-x86_64
- commit hash: 14aea56
- commit date: 2023-11-17
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 301 ms: 1.15x faster                                               |
| chameleon      | 9.84 ms                                                | 7.84 ms: 1.25x faster                                              |
| docutils       | 3.26 sec                                               | 2.79 sec: 1.17x faster                                             |
| tornado_http   | 131 ms                                                 | 104 ms: 1.26x faster                                               |
| Geometric mean | (ref)                                                  | 1.21x faster                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 468 ms: 1.56x faster                                               |
| async_tree_memoization  | 867 ms                                                 | 596 ms: 1.46x faster                                               |
| async_tree_io           | 1.79 sec                                               | 1.24 sec: 1.45x faster                                             |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 742 ms: 1.36x faster                                               |
| Geometric mean          | (ref)                                                  | 1.45x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 199 ms: 1.04x slower                                               |
| float          | 116 ms                                                 | 123 ms: 1.06x slower                                               |
| nbody          | 148 ms                                                 | 159 ms: 1.07x slower                                               |
| Geometric mean | (ref)                                                  | 1.06x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 176 ms: 1.05x faster                                               |
| regex_v8       | 26.2 ms                                                | 26.1 ms: 1.01x faster                                              |
| regex_dna      | 215 ms                                                 | 220 ms: 1.02x slower                                               |
| regex_effbot   | 3.41 ms                                                | 3.63 ms: 1.06x slower                                              |
| Geometric mean | (ref)                                                  | 1.01x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 315 us: 1.53x faster                                               |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                              |
| unpickle_pure_python | 327 us                                                 | 262 us: 1.25x faster                                               |
| xml_etree_process    | 79.8 ms                                                | 67.0 ms: 1.19x faster                                              |
| json_loads           | 31.4 us                                                | 28.2 us: 1.11x faster                                              |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                               |
| xml_etree_generate   | 100.0 ms                                               | 98.2 ms: 1.02x faster                                              |
| unpickle             | 14.9 us                                                | 15.1 us: 1.01x slower                                              |
| xml_etree_iterparse  | 116 ms                                                 | 122 ms: 1.05x slower                                               |
| pickle               | 10.7 us                                                | 11.3 us: 1.06x slower                                              |
| unpickle_list        | 5.10 us                                                | 5.40 us: 1.06x slower                                              |
| tomli_loads          | 3.06 sec                                               | 3.30 sec: 1.08x slower                                             |
| pickle_dict          | 30.0 us                                                | 33.2 us: 1.11x slower                                              |
| Geometric mean       | (ref)                                                  | 1.07x faster                                                       |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.37x faster                                              |
| python_startup_no_site | 5.87 ms                                                | 9.07 ms: 1.55x slower                                              |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 19.1 ms: 1.17x slower                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 130 us: 4.32x faster                                               |
| generators               | 78.9 ms                                                | 29.7 ms: 2.65x faster                                              |
| asyncio_tcp              | 918 ms                                                 | 493 ms: 1.86x faster                                               |
| logging_silent           | 189 ns                                                 | 113 ns: 1.68x faster                                               |
| richards_super           | 95.6 ms                                                | 60.6 ms: 1.58x faster                                              |
| async_tree_none          | 732 ms                                                 | 468 ms: 1.56x faster                                               |
| coroutines               | 34.5 ms                                                | 22.0 ms: 1.56x faster                                              |
| scimark_sor              | 214 ms                                                 | 138 ms: 1.55x faster                                               |
| pickle_pure_python       | 482 us                                                 | 315 us: 1.53x faster                                               |
| richards                 | 79.4 ms                                                | 53.2 ms: 1.49x faster                                              |
| sqlglot_parse            | 2.15 ms                                                | 1.44 ms: 1.49x faster                                              |
| raytrace                 | 498 ms                                                 | 339 ms: 1.47x faster                                               |
| async_tree_memoization   | 867 ms                                                 | 596 ms: 1.46x faster                                               |
| async_tree_io            | 1.79 sec                                               | 1.24 sec: 1.45x faster                                             |
| sqlglot_transpile        | 2.55 ms                                                | 1.77 ms: 1.44x faster                                              |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                             |
| scimark_lu               | 175 ms                                                 | 124 ms: 1.42x faster                                               |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                              |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                              |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 742 ms: 1.36x faster                                               |
| deepcopy_memo            | 58.8 us                                                | 44.7 us: 1.31x faster                                              |
| go                       | 238 ms                                                 | 181 ms: 1.31x faster                                               |
| logging_simple           | 8.27 us                                                | 6.31 us: 1.31x faster                                              |
| deepcopy_reduce          | 4.17 us                                                | 3.18 us: 1.31x faster                                              |
| deepcopy                 | 481 us                                                 | 372 us: 1.29x faster                                               |
| unpack_sequence          | 65.7 ns                                                | 50.9 ns: 1.29x faster                                              |
| logging_format           | 9.07 us                                                | 7.11 us: 1.28x faster                                              |
| chaos                    | 114 ms                                                 | 89.5 ms: 1.28x faster                                              |
| tornado_http             | 131 ms                                                 | 104 ms: 1.26x faster                                               |
| chameleon                | 9.84 ms                                                | 7.84 ms: 1.25x faster                                              |
| unpickle_pure_python     | 327 us                                                 | 262 us: 1.25x faster                                               |
| pycparser                | 1.57 sec                                               | 1.27 sec: 1.23x faster                                             |
| mypy2                    | 442 ms                                                 | 360 ms: 1.23x faster                                               |
| deltablue                | 7.81 ms                                                | 6.38 ms: 1.23x faster                                              |
| scimark_monte_carlo      | 118 ms                                                 | 97.1 ms: 1.21x faster                                              |
| crypto_pyaes             | 127 ms                                                 | 105 ms: 1.20x faster                                               |
| xml_etree_process        | 79.8 ms                                                | 67.0 ms: 1.19x faster                                              |
| docutils                 | 3.26 sec                                               | 2.79 sec: 1.17x faster                                             |
| sqlglot_normalize        | 141 ms                                                 | 121 ms: 1.17x faster                                               |
| dask                     | 432 ms                                                 | 373 ms: 1.16x faster                                               |
| 2to3                     | 346 ms                                                 | 301 ms: 1.15x faster                                               |
| pprint_safe_repr         | 1.01 sec                                               | 905 ms: 1.12x faster                                               |
| sympy_sum                | 190 ms                                                 | 171 ms: 1.11x faster                                               |
| json_loads               | 31.4 us                                                | 28.2 us: 1.11x faster                                              |
| sympy_integrate          | 25.4 ms                                                | 22.9 ms: 1.11x faster                                              |
| sqlglot_optimize         | 68.7 ms                                                | 62.1 ms: 1.11x faster                                              |
| pprint_pformat           | 2.10 sec                                               | 1.90 sec: 1.11x faster                                             |
| bench_thread_pool        | 966 us                                                 | 877 us: 1.10x faster                                               |
| pyflate                  | 708 ms                                                 | 645 ms: 1.10x faster                                               |
| json                     | 5.67 ms                                                | 5.18 ms: 1.09x faster                                              |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.09x faster                                              |
| dulwich_log              | 77.0 ms                                                | 70.6 ms: 1.09x faster                                              |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                               |
| pathlib                  | 20.3 ms                                                | 19.1 ms: 1.06x faster                                              |
| sympy_expand             | 558 ms                                                 | 528 ms: 1.06x faster                                               |
| sympy_str                | 337 ms                                                 | 319 ms: 1.06x faster                                               |
| regex_compile            | 186 ms                                                 | 176 ms: 1.05x faster                                               |
| mdp                      | 2.93 sec                                               | 2.80 sec: 1.05x faster                                             |
| xml_etree_generate       | 100.0 ms                                               | 98.2 ms: 1.02x faster                                              |
| asyncio_websockets       | 558 ms                                                 | 553 ms: 1.01x faster                                               |
| sqlite_synth             | 3.02 us                                                | 3.00 us: 1.01x faster                                              |
| regex_v8                 | 26.2 ms                                                | 26.1 ms: 1.01x faster                                              |
| unpickle                 | 14.9 us                                                | 15.1 us: 1.01x slower                                              |
| regex_dna                | 215 ms                                                 | 220 ms: 1.02x slower                                               |
| pidigits                 | 190 ms                                                 | 199 ms: 1.04x slower                                               |
| xml_etree_iterparse      | 116 ms                                                 | 122 ms: 1.05x slower                                               |
| pickle                   | 10.7 us                                                | 11.3 us: 1.06x slower                                              |
| float                    | 116 ms                                                 | 123 ms: 1.06x slower                                               |
| unpickle_list            | 5.10 us                                                | 5.40 us: 1.06x slower                                              |
| regex_effbot             | 3.41 ms                                                | 3.63 ms: 1.06x slower                                              |
| async_generators         | 442 ms                                                 | 472 ms: 1.07x slower                                               |
| fannkuch                 | 527 ms                                                 | 566 ms: 1.07x slower                                               |
| nbody                    | 148 ms                                                 | 159 ms: 1.07x slower                                               |
| tomli_loads              | 3.06 sec                                               | 3.30 sec: 1.08x slower                                             |
| meteor_contest           | 119 ms                                                 | 129 ms: 1.08x slower                                               |
| pickle_dict              | 30.0 us                                                | 33.2 us: 1.11x slower                                              |
| nqueens                  | 107 ms                                                 | 120 ms: 1.12x slower                                               |
| hexiom                   | 10.3 ms                                                | 11.6 ms: 1.13x slower                                              |
| coverage                 | 82.0 ms                                                | 95.8 ms: 1.17x slower                                              |
| mako                     | 16.3 ms                                                | 19.1 ms: 1.17x slower                                              |
| gc_traversal             | 3.43 ms                                                | 4.09 ms: 1.19x slower                                              |
| spectral_norm            | 163 ms                                                 | 209 ms: 1.28x slower                                               |
| scimark_fft              | 454 ms                                                 | 581 ms: 1.28x slower                                               |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 7.92 ms: 1.30x slower                                              |
| telco                    | 7.01 ms                                                | 9.30 ms: 1.33x slower                                              |
| python_startup_no_site   | 5.87 ms                                                | 9.07 ms: 1.55x slower                                              |
| Geometric mean           | (ref)                                                  | 1.15x faster                                                       |

Benchmark hidden because not significant (3): pickle_list, bench_mp_pool, comprehensions
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-14aea56-PYTHON_UOPS/bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.06x
