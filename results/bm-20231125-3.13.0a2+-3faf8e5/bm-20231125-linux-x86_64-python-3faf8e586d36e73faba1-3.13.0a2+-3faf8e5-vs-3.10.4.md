
# Results vs. 3.10.4

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: linux-x86_64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.34x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| chameleon      | 9.84 ms                                                | 6.90 ms: 1.43x faster                                                  |
| docutils       | 3.26 sec                                               | 2.60 sec: 1.26x faster                                                 |
| tornado_http   | 131 ms                                                 | 95.4 ms: 1.37x faster                                                  |
| Geometric mean | (ref)                                                  | 1.34x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 438 ms: 1.67x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 566 ms: 1.53x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.51x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 709 ms: 1.42x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.53x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 97.7 ms: 1.52x faster                                                  |
| float          | 116 ms                                                 | 82.5 ms: 1.41x faster                                                  |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                  | 1.28x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 133 ms: 1.39x faster                                                   |
| regex_v8       | 26.2 ms                                                | 25.5 ms: 1.03x faster                                                  |
| regex_dna      | 215 ms                                                 | 221 ms: 1.03x slower                                                   |
| regex_effbot   | 3.41 ms                                                | 3.62 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 305 us: 1.58x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 221 us: 1.48x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.16 sec: 1.42x faster                                                 |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 59.4 ms: 1.34x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 87.1 ms: 1.15x faster                                                  |
| json_loads           | 31.4 us                                                | 28.4 us: 1.11x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.10x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                   |
| pickle_list          | 5.05 us                                                | 4.88 us: 1.03x faster                                                  |
| unpickle             | 14.9 us                                                | 15.0 us: 1.01x slower                                                  |
| unpickle_list        | 5.10 us                                                | 5.24 us: 1.03x slower                                                  |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                                  |
| pickle_dict          | 30.0 us                                                | 32.5 us: 1.09x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.16x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 9.04 ms: 1.54x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.0 ms: 1.48x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 115 us: 4.87x faster                                                   |
| generators               | 78.9 ms                                                | 29.8 ms: 2.64x faster                                                  |
| deltablue                | 7.81 ms                                                | 3.28 ms: 2.38x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 481 ms: 1.91x faster                                                   |
| chaos                    | 114 ms                                                 | 61.4 ms: 1.86x faster                                                  |
| raytrace                 | 498 ms                                                 | 277 ms: 1.80x faster                                                   |
| richards_super           | 95.6 ms                                                | 53.7 ms: 1.78x faster                                                  |
| comprehensions           | 28.5 us                                                | 16.4 us: 1.74x faster                                                  |
| scimark_sor              | 214 ms                                                 | 124 ms: 1.74x faster                                                   |
| logging_silent           | 189 ns                                                 | 109 ns: 1.73x faster                                                   |
| crypto_pyaes             | 127 ms                                                 | 73.6 ms: 1.72x faster                                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.28 ms: 1.68x faster                                                  |
| scimark_monte_carlo      | 118 ms                                                 | 70.2 ms: 1.68x faster                                                  |
| go                       | 238 ms                                                 | 141 ms: 1.68x faster                                                   |
| async_tree_none          | 732 ms                                                 | 438 ms: 1.67x faster                                                   |
| hexiom                   | 10.3 ms                                                | 6.20 ms: 1.66x faster                                                  |
| richards                 | 79.4 ms                                                | 47.9 ms: 1.66x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.59 ms: 1.60x faster                                                  |
| coroutines               | 34.5 ms                                                | 21.6 ms: 1.60x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 305 us: 1.58x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 38.3 us: 1.53x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 566 ms: 1.53x faster                                                   |
| pyflate                  | 708 ms                                                 | 465 ms: 1.52x faster                                                   |
| nbody                    | 148 ms                                                 | 97.7 ms: 1.52x faster                                                  |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.51x faster                                                 |
| scimark_lu               | 175 ms                                                 | 117 ms: 1.50x faster                                                   |
| unpickle_pure_python     | 327 us                                                 | 221 us: 1.48x faster                                                   |
| mako                     | 16.3 ms                                                | 11.0 ms: 1.48x faster                                                  |
| spectral_norm            | 163 ms                                                 | 111 ms: 1.46x faster                                                   |
| logging_simple           | 8.27 us                                                | 5.72 us: 1.45x faster                                                  |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.78 sec: 1.44x faster                                                 |
| logging_format           | 9.07 us                                                | 6.30 us: 1.44x faster                                                  |
| unpack_sequence          | 65.7 ns                                                | 46.1 ns: 1.43x faster                                                  |
| chameleon                | 9.84 ms                                                | 6.90 ms: 1.43x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 709 ms: 1.42x faster                                                   |
| tomli_loads              | 3.06 sec                                               | 2.16 sec: 1.42x faster                                                 |
| float                    | 116 ms                                                 | 82.5 ms: 1.41x faster                                                  |
| deepcopy                 | 481 us                                                 | 346 us: 1.39x faster                                                   |
| regex_compile            | 186 ms                                                 | 133 ms: 1.39x faster                                                   |
| pprint_pformat           | 2.10 sec                                               | 1.52 sec: 1.38x faster                                                 |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| tornado_http             | 131 ms                                                 | 95.4 ms: 1.37x faster                                                  |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 744 ms: 1.36x faster                                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.09 us: 1.35x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 59.4 ms: 1.34x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.34x faster                                                   |
| nqueens                  | 107 ms                                                 | 80.9 ms: 1.32x faster                                                  |
| fannkuch                 | 527 ms                                                 | 402 ms: 1.31x faster                                                   |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 19.4 ms: 1.31x faster                                                  |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.30x faster                                                 |
| mypy2                    | 442 ms                                                 | 342 ms: 1.29x faster                                                   |
| sympy_sum                | 190 ms                                                 | 147 ms: 1.29x faster                                                   |
| sqlglot_optimize         | 68.7 ms                                                | 53.5 ms: 1.29x faster                                                  |
| sympy_str                | 337 ms                                                 | 266 ms: 1.26x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.60 sec: 1.26x faster                                                 |
| sympy_expand             | 558 ms                                                 | 450 ms: 1.24x faster                                                   |
| scimark_fft              | 454 ms                                                 | 369 ms: 1.23x faster                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.98 ms: 1.22x faster                                                  |
| dask                     | 432 ms                                                 | 359 ms: 1.20x faster                                                   |
| dulwich_log              | 77.0 ms                                                | 65.9 ms: 1.17x faster                                                  |
| bench_thread_pool        | 966 us                                                 | 835 us: 1.16x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 87.1 ms: 1.15x faster                                                  |
| meteor_contest           | 119 ms                                                 | 107 ms: 1.11x faster                                                   |
| json_loads               | 31.4 us                                                | 28.4 us: 1.11x faster                                                  |
| pathlib                  | 20.3 ms                                                | 18.4 ms: 1.10x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 106 ms: 1.10x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.09x faster                                                  |
| json                     | 5.67 ms                                                | 5.19 ms: 1.09x faster                                                  |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.81 us: 1.08x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.76 sec: 1.06x faster                                                 |
| pickle_list              | 5.05 us                                                | 4.88 us: 1.03x faster                                                  |
| regex_v8                 | 26.2 ms                                                | 25.5 ms: 1.03x faster                                                  |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                   |
| async_generators         | 442 ms                                                 | 444 ms: 1.01x slower                                                   |
| unpickle                 | 14.9 us                                                | 15.0 us: 1.01x slower                                                  |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| regex_dna                | 215 ms                                                 | 221 ms: 1.03x slower                                                   |
| unpickle_list            | 5.10 us                                                | 5.24 us: 1.03x slower                                                  |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                                  |
| regex_effbot             | 3.41 ms                                                | 3.62 ms: 1.06x slower                                                  |
| pickle_dict              | 30.0 us                                                | 32.5 us: 1.09x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 3.85 ms: 1.12x slower                                                  |
| coverage                 | 82.0 ms                                                | 94.3 ms: 1.15x slower                                                  |
| telco                    | 7.01 ms                                                | 8.27 ms: 1.18x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 9.04 ms: 1.54x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.34x faster                                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.26x
