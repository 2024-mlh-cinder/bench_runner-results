
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 853b4b5
- commit date: 2023-11-04
- overall geometric mean: 1.35x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.27x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 262 ms: 1.32x faster                                   |
| chameleon      | 9.84 ms                                                | 6.84 ms: 1.44x faster                                  |
| docutils       | 3.26 sec                                               | 2.59 sec: 1.26x faster                                 |
| tornado_http   | 131 ms                                                 | 95.2 ms: 1.37x faster                                  |
| Geometric mean | (ref)                                                  | 1.35x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 439 ms: 1.67x faster                                   |
| async_tree_memoization  | 867 ms                                                 | 565 ms: 1.53x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.50x faster                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 711 ms: 1.42x faster                                   |
| Geometric mean          | (ref)                                                  | 1.53x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 148 ms                                                 | 90.5 ms: 1.64x faster                                  |
| float          | 116 ms                                                 | 81.5 ms: 1.43x faster                                  |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                   |
| Geometric mean | (ref)                                                  | 1.32x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 134 ms: 1.38x faster                                   |
| regex_v8       | 26.2 ms                                                | 24.3 ms: 1.08x faster                                  |
| regex_dna      | 215 ms                                                 | 222 ms: 1.03x slower                                   |
| regex_effbot   | 3.41 ms                                                | 3.53 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.09x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 295 us: 1.63x faster                                   |
| unpickle_pure_python | 327 us                                                 | 218 us: 1.50x faster                                   |
| tomli_loads          | 3.06 sec                                               | 2.12 sec: 1.44x faster                                 |
| json_dumps           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                  |
| xml_etree_process    | 79.8 ms                                                | 59.1 ms: 1.35x faster                                  |
| xml_etree_generate   | 100.0 ms                                               | 86.6 ms: 1.15x faster                                  |
| json_loads           | 31.4 us                                                | 27.5 us: 1.14x faster                                  |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.11x faster                                   |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                   |
| unpickle_list        | 5.10 us                                                | 5.19 us: 1.02x slower                                  |
| unpickle             | 14.9 us                                                | 15.3 us: 1.03x slower                                  |
| pickle_list          | 5.05 us                                                | 5.24 us: 1.04x slower                                  |
| pickle               | 10.7 us                                                | 11.5 us: 1.08x slower                                  |
| pickle_dict          | 30.0 us                                                | 36.1 us: 1.20x slower                                  |
| Geometric mean       | (ref)                                                  | 1.15x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                  |
| python_startup_no_site | 5.87 ms                                                | 8.97 ms: 1.53x slower                                  |
| Geometric mean         | (ref)                                                  | 1.05x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.1 ms: 1.47x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 115 us: 4.88x faster                                   |
| generators               | 78.9 ms                                                | 29.5 ms: 2.67x faster                                  |
| deltablue                | 7.81 ms                                                | 3.25 ms: 2.41x faster                                  |
| chaos                    | 114 ms                                                 | 59.8 ms: 1.91x faster                                  |
| asyncio_tcp              | 918 ms                                                 | 484 ms: 1.89x faster                                   |
| raytrace                 | 498 ms                                                 | 268 ms: 1.86x faster                                   |
| logging_silent           | 189 ns                                                 | 105 ns: 1.80x faster                                   |
| crypto_pyaes             | 127 ms                                                 | 70.3 ms: 1.80x faster                                  |
| comprehensions           | 28.5 us                                                | 15.9 us: 1.79x faster                                  |
| scimark_sor              | 214 ms                                                 | 121 ms: 1.77x faster                                   |
| scimark_monte_carlo      | 118 ms                                                 | 67.5 ms: 1.75x faster                                  |
| richards_super           | 95.6 ms                                                | 55.0 ms: 1.74x faster                                  |
| hexiom                   | 10.3 ms                                                | 6.03 ms: 1.71x faster                                  |
| go                       | 238 ms                                                 | 139 ms: 1.71x faster                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.26 ms: 1.70x faster                                  |
| async_tree_none          | 732 ms                                                 | 439 ms: 1.67x faster                                   |
| richards                 | 79.4 ms                                                | 48.4 ms: 1.64x faster                                  |
| nbody                    | 148 ms                                                 | 90.5 ms: 1.64x faster                                  |
| pickle_pure_python       | 482 us                                                 | 295 us: 1.63x faster                                   |
| sqlglot_transpile        | 2.55 ms                                                | 1.58 ms: 1.62x faster                                  |
| pyflate                  | 708 ms                                                 | 451 ms: 1.57x faster                                   |
| unpack_sequence          | 65.7 ns                                                | 41.9 ns: 1.57x faster                                  |
| coroutines               | 34.5 ms                                                | 22.0 ms: 1.56x faster                                  |
| deepcopy_memo            | 58.8 us                                                | 37.6 us: 1.56x faster                                  |
| spectral_norm            | 163 ms                                                 | 105 ms: 1.55x faster                                   |
| scimark_lu               | 175 ms                                                 | 114 ms: 1.54x faster                                   |
| async_tree_memoization   | 867 ms                                                 | 565 ms: 1.53x faster                                   |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.50x faster                                 |
| unpickle_pure_python     | 327 us                                                 | 218 us: 1.50x faster                                   |
| mako                     | 16.3 ms                                                | 11.1 ms: 1.47x faster                                  |
| logging_simple           | 8.27 us                                                | 5.72 us: 1.45x faster                                  |
| tomli_loads              | 3.06 sec                                               | 2.12 sec: 1.44x faster                                 |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                 |
| logging_format           | 9.07 us                                                | 6.30 us: 1.44x faster                                  |
| chameleon                | 9.84 ms                                                | 6.84 ms: 1.44x faster                                  |
| float                    | 116 ms                                                 | 81.5 ms: 1.43x faster                                  |
| pprint_pformat           | 2.10 sec                                               | 1.48 sec: 1.42x faster                                 |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 711 ms: 1.42x faster                                   |
| pprint_safe_repr         | 1.01 sec                                               | 724 ms: 1.40x faster                                   |
| deepcopy                 | 481 us                                                 | 344 us: 1.40x faster                                   |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                  |
| regex_compile            | 186 ms                                                 | 134 ms: 1.38x faster                                   |
| json_dumps               | 14.3 ms                                                | 10.4 ms: 1.38x faster                                  |
| tornado_http             | 131 ms                                                 | 95.2 ms: 1.37x faster                                  |
| nqueens                  | 107 ms                                                 | 77.7 ms: 1.37x faster                                  |
| sqlglot_normalize        | 141 ms                                                 | 104 ms: 1.35x faster                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.08 us: 1.35x faster                                  |
| xml_etree_process        | 79.8 ms                                                | 59.1 ms: 1.35x faster                                  |
| fannkuch                 | 527 ms                                                 | 396 ms: 1.33x faster                                   |
| 2to3                     | 346 ms                                                 | 262 ms: 1.32x faster                                   |
| sympy_integrate          | 25.4 ms                                                | 19.3 ms: 1.32x faster                                  |
| pycparser                | 1.57 sec                                               | 1.20 sec: 1.30x faster                                 |
| mypy2                    | 442 ms                                                 | 340 ms: 1.30x faster                                   |
| sympy_sum                | 190 ms                                                 | 146 ms: 1.30x faster                                   |
| sqlglot_optimize         | 68.7 ms                                                | 53.1 ms: 1.29x faster                                  |
| sympy_str                | 337 ms                                                 | 265 ms: 1.27x faster                                   |
| docutils                 | 3.26 sec                                               | 2.59 sec: 1.26x faster                                 |
| scimark_fft              | 454 ms                                                 | 361 ms: 1.26x faster                                   |
| sympy_expand             | 558 ms                                                 | 447 ms: 1.25x faster                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.92 ms: 1.24x faster                                  |
| dulwich_log              | 77.0 ms                                                | 65.6 ms: 1.17x faster                                  |
| bench_thread_pool        | 966 us                                                 | 826 us: 1.17x faster                                   |
| xml_etree_generate       | 100.0 ms                                               | 86.6 ms: 1.15x faster                                  |
| json_loads               | 31.4 us                                                | 27.5 us: 1.14x faster                                  |
| mdp                      | 2.93 sec                                               | 2.59 sec: 1.13x faster                                 |
| meteor_contest           | 119 ms                                                 | 107 ms: 1.11x faster                                   |
| xml_etree_iterparse      | 116 ms                                                 | 105 ms: 1.11x faster                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.45 ms: 1.11x faster                                  |
| json                     | 5.67 ms                                                | 5.12 ms: 1.11x faster                                  |
| regex_v8                 | 26.2 ms                                                | 24.3 ms: 1.08x faster                                  |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                   |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                  |
| sqlite_synth             | 3.02 us                                                | 2.82 us: 1.07x faster                                  |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                   |
| async_generators         | 442 ms                                                 | 447 ms: 1.01x slower                                   |
| unpickle_list            | 5.10 us                                                | 5.19 us: 1.02x slower                                  |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                   |
| unpickle                 | 14.9 us                                                | 15.3 us: 1.03x slower                                  |
| regex_dna                | 215 ms                                                 | 222 ms: 1.03x slower                                   |
| regex_effbot             | 3.41 ms                                                | 3.53 ms: 1.03x slower                                  |
| pickle_list              | 5.05 us                                                | 5.24 us: 1.04x slower                                  |
| gc_traversal             | 3.43 ms                                                | 3.67 ms: 1.07x slower                                  |
| pickle                   | 10.7 us                                                | 11.5 us: 1.08x slower                                  |
| coverage                 | 82.0 ms                                                | 95.7 ms: 1.17x slower                                  |
| telco                    | 7.01 ms                                                | 8.31 ms: 1.18x slower                                  |
| pickle_dict              | 30.0 us                                                | 36.1 us: 1.20x slower                                  |
| python_startup_no_site   | 5.87 ms                                                | 8.97 ms: 1.53x slower                                  |
| Geometric mean           | (ref)                                                  | 1.35x faster                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231104-3.13.0a1+-853b4b5/bm-20231104-linux-x86_64-python-main-3.13.0a1+-853b4b5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.31x
- 95% likely to have a speedup of 1.29x
- 99% likely to have a speedup of 1.27x
