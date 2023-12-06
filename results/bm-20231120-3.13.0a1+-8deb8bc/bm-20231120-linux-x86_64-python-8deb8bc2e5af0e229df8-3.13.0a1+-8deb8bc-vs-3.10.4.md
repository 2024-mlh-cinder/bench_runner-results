
# Results vs. 3.10.4

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: linux-x86_64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.34x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| chameleon      | 9.84 ms                                                | 7.02 ms: 1.40x faster                                                  |
| docutils       | 3.26 sec                                               | 2.61 sec: 1.25x faster                                                 |
| tornado_http   | 131 ms                                                 | 94.8 ms: 1.38x faster                                                  |
| Geometric mean | (ref)                                                  | 1.33x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 439 ms: 1.67x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 565 ms: 1.53x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.20 sec: 1.50x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 710 ms: 1.42x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.53x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 90.8 ms: 1.63x faster                                                  |
| float          | 116 ms                                                 | 82.1 ms: 1.42x faster                                                  |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                  | 1.31x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 135 ms: 1.37x faster                                                   |
| regex_v8       | 26.2 ms                                                | 25.5 ms: 1.03x faster                                                  |
| regex_dna      | 215 ms                                                 | 217 ms: 1.01x slower                                                   |
| regex_effbot   | 3.41 ms                                                | 3.72 ms: 1.09x slower                                                  |
| Geometric mean | (ref)                                                  | 1.06x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 304 us: 1.58x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 220 us: 1.49x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.17 sec: 1.41x faster                                                 |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.37x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 59.5 ms: 1.34x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 86.7 ms: 1.15x faster                                                  |
| json_loads           | 31.4 us                                                | 28.2 us: 1.11x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.10x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                   |
| unpickle             | 14.9 us                                                | 14.3 us: 1.04x faster                                                  |
| pickle_list          | 5.05 us                                                | 4.92 us: 1.03x faster                                                  |
| pickle               | 10.7 us                                                | 11.0 us: 1.03x slower                                                  |
| pickle_dict          | 30.0 us                                                | 32.4 us: 1.08x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.17x faster                                                           |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 8.97 ms: 1.53x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.6 ms: 1.40x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 119 us: 4.72x faster                                                   |
| generators               | 78.9 ms                                                | 29.7 ms: 2.65x faster                                                  |
| deltablue                | 7.81 ms                                                | 3.33 ms: 2.35x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 488 ms: 1.88x faster                                                   |
| chaos                    | 114 ms                                                 | 60.9 ms: 1.88x faster                                                  |
| raytrace                 | 498 ms                                                 | 275 ms: 1.81x faster                                                   |
| crypto_pyaes             | 127 ms                                                 | 72.3 ms: 1.75x faster                                                  |
| richards_super           | 95.6 ms                                                | 54.6 ms: 1.75x faster                                                  |
| scimark_sor              | 214 ms                                                 | 123 ms: 1.74x faster                                                   |
| scimark_monte_carlo      | 118 ms                                                 | 67.9 ms: 1.74x faster                                                  |
| logging_silent           | 189 ns                                                 | 110 ns: 1.72x faster                                                   |
| comprehensions           | 28.5 us                                                | 16.7 us: 1.71x faster                                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.28 ms: 1.68x faster                                                  |
| go                       | 238 ms                                                 | 142 ms: 1.67x faster                                                   |
| async_tree_none          | 732 ms                                                 | 439 ms: 1.67x faster                                                   |
| hexiom                   | 10.3 ms                                                | 6.23 ms: 1.65x faster                                                  |
| richards                 | 79.4 ms                                                | 48.5 ms: 1.64x faster                                                  |
| nbody                    | 148 ms                                                 | 90.8 ms: 1.63x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.59 ms: 1.60x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 304 us: 1.58x faster                                                   |
| coroutines               | 34.5 ms                                                | 22.0 ms: 1.57x faster                                                  |
| scimark_lu               | 175 ms                                                 | 114 ms: 1.54x faster                                                   |
| async_tree_memoization   | 867 ms                                                 | 565 ms: 1.53x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 38.5 us: 1.53x faster                                                  |
| pyflate                  | 708 ms                                                 | 469 ms: 1.51x faster                                                   |
| async_tree_io            | 1.79 sec                                               | 1.20 sec: 1.50x faster                                                 |
| unpickle_pure_python     | 327 us                                                 | 220 us: 1.49x faster                                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                                 |
| logging_format           | 9.07 us                                                | 6.31 us: 1.44x faster                                                  |
| logging_simple           | 8.27 us                                                | 5.77 us: 1.44x faster                                                  |
| spectral_norm            | 163 ms                                                 | 115 ms: 1.42x faster                                                   |
| unpack_sequence          | 65.7 ns                                                | 46.3 ns: 1.42x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 710 ms: 1.42x faster                                                   |
| float                    | 116 ms                                                 | 82.1 ms: 1.42x faster                                                  |
| tomli_loads              | 3.06 sec                                               | 2.17 sec: 1.41x faster                                                 |
| mako                     | 16.3 ms                                                | 11.6 ms: 1.40x faster                                                  |
| chameleon                | 9.84 ms                                                | 7.02 ms: 1.40x faster                                                  |
| pprint_pformat           | 2.10 sec                                               | 1.51 sec: 1.39x faster                                                 |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| deepcopy                 | 481 us                                                 | 349 us: 1.38x faster                                                   |
| tornado_http             | 131 ms                                                 | 94.8 ms: 1.38x faster                                                  |
| regex_compile            | 186 ms                                                 | 135 ms: 1.37x faster                                                   |
| pprint_safe_repr         | 1.01 sec                                               | 740 ms: 1.37x faster                                                   |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.37x faster                                                  |
| deepcopy_reduce          | 4.17 us                                                | 3.05 us: 1.36x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 59.5 ms: 1.34x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.34x faster                                                   |
| pycparser                | 1.57 sec                                               | 1.17 sec: 1.33x faster                                                 |
| fannkuch                 | 527 ms                                                 | 398 ms: 1.33x faster                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.63 ms: 1.32x faster                                                  |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 19.5 ms: 1.30x faster                                                  |
| nqueens                  | 107 ms                                                 | 82.1 ms: 1.30x faster                                                  |
| mypy2                    | 442 ms                                                 | 343 ms: 1.29x faster                                                   |
| sympy_sum                | 190 ms                                                 | 148 ms: 1.29x faster                                                   |
| sqlglot_optimize         | 68.7 ms                                                | 53.7 ms: 1.28x faster                                                  |
| sympy_str                | 337 ms                                                 | 268 ms: 1.26x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.61 sec: 1.25x faster                                                 |
| scimark_fft              | 454 ms                                                 | 364 ms: 1.25x faster                                                   |
| sympy_expand             | 558 ms                                                 | 455 ms: 1.23x faster                                                   |
| dask                     | 432 ms                                                 | 360 ms: 1.20x faster                                                   |
| dulwich_log              | 77.0 ms                                                | 66.0 ms: 1.17x faster                                                  |
| bench_thread_pool        | 966 us                                                 | 834 us: 1.16x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 86.7 ms: 1.15x faster                                                  |
| json_loads               | 31.4 us                                                | 28.2 us: 1.11x faster                                                  |
| pathlib                  | 20.3 ms                                                | 18.3 ms: 1.11x faster                                                  |
| json                     | 5.67 ms                                                | 5.12 ms: 1.11x faster                                                  |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 105 ms: 1.10x faster                                                   |
| meteor_contest           | 119 ms                                                 | 109 ms: 1.09x faster                                                   |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                   |
| mdp                      | 2.93 sec                                               | 2.74 sec: 1.07x faster                                                 |
| sqlite_synth             | 3.02 us                                                | 2.84 us: 1.06x faster                                                  |
| unpickle                 | 14.9 us                                                | 14.3 us: 1.04x faster                                                  |
| regex_v8                 | 26.2 ms                                                | 25.5 ms: 1.03x faster                                                  |
| pickle_list              | 5.05 us                                                | 4.92 us: 1.03x faster                                                  |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                                   |
| regex_dna                | 215 ms                                                 | 217 ms: 1.01x slower                                                   |
| async_generators         | 442 ms                                                 | 448 ms: 1.02x slower                                                   |
| gc_traversal             | 3.43 ms                                                | 3.51 ms: 1.02x slower                                                  |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| pickle                   | 10.7 us                                                | 11.0 us: 1.03x slower                                                  |
| pickle_dict              | 30.0 us                                                | 32.4 us: 1.08x slower                                                  |
| regex_effbot             | 3.41 ms                                                | 3.72 ms: 1.09x slower                                                  |
| coverage                 | 82.0 ms                                                | 94.8 ms: 1.16x slower                                                  |
| telco                    | 7.01 ms                                                | 8.32 ms: 1.19x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 8.97 ms: 1.53x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.34x faster                                                           |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle_list
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-8deb8bc/bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.30x
- 95% likely to have a speedup of 1.29x
- 99% likely to have a speedup of 1.26x
