
# Results vs. 3.10.4

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: linux-x86_64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.33x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| chameleon      | 9.84 ms                                                | 6.98 ms: 1.41x faster                                                  |
| docutils       | 3.26 sec                                               | 2.61 sec: 1.25x faster                                                 |
| tornado_http   | 131 ms                                                 | 96.1 ms: 1.36x faster                                                  |
| Geometric mean | (ref)                                                  | 1.33x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 434 ms: 1.69x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 563 ms: 1.54x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.50x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 713 ms: 1.41x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.53x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 94.0 ms: 1.58x faster                                                  |
| float          | 116 ms                                                 | 81.8 ms: 1.42x faster                                                  |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                  | 1.30x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 135 ms: 1.37x faster                                                   |
| regex_v8       | 26.2 ms                                                | 24.5 ms: 1.07x faster                                                  |
| regex_dna      | 215 ms                                                 | 217 ms: 1.01x slower                                                   |
| regex_effbot   | 3.41 ms                                                | 3.57 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 303 us: 1.59x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 219 us: 1.49x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.13 sec: 1.44x faster                                                 |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 59.4 ms: 1.34x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 86.4 ms: 1.16x faster                                                  |
| json_loads           | 31.4 us                                                | 27.8 us: 1.13x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.10x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 157 ms: 1.09x faster                                                   |
| unpickle_list        | 5.10 us                                                | 5.06 us: 1.01x faster                                                  |
| pickle_list          | 5.05 us                                                | 5.09 us: 1.01x slower                                                  |
| pickle               | 10.7 us                                                | 11.7 us: 1.10x slower                                                  |
| pickle_dict          | 30.0 us                                                | 34.2 us: 1.14x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.16x faster                                                           |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 9.02 ms: 1.54x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.5 ms: 1.42x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 116 us: 4.83x faster                                                   |
| generators               | 78.9 ms                                                | 29.7 ms: 2.66x faster                                                  |
| deltablue                | 7.81 ms                                                | 3.33 ms: 2.35x faster                                                  |
| chaos                    | 114 ms                                                 | 61.0 ms: 1.87x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 497 ms: 1.85x faster                                                   |
| raytrace                 | 498 ms                                                 | 277 ms: 1.80x faster                                                   |
| crypto_pyaes             | 127 ms                                                 | 71.6 ms: 1.77x faster                                                  |
| richards_super           | 95.6 ms                                                | 54.1 ms: 1.77x faster                                                  |
| logging_silent           | 189 ns                                                 | 108 ns: 1.76x faster                                                   |
| scimark_sor              | 214 ms                                                 | 124 ms: 1.73x faster                                                   |
| scimark_monte_carlo      | 118 ms                                                 | 68.6 ms: 1.72x faster                                                  |
| comprehensions           | 28.5 us                                                | 16.8 us: 1.69x faster                                                  |
| async_tree_none          | 732 ms                                                 | 434 ms: 1.69x faster                                                   |
| go                       | 238 ms                                                 | 141 ms: 1.69x faster                                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.28 ms: 1.68x faster                                                  |
| richards                 | 79.4 ms                                                | 47.4 ms: 1.68x faster                                                  |
| hexiom                   | 10.3 ms                                                | 6.19 ms: 1.66x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.59 ms: 1.60x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 303 us: 1.59x faster                                                   |
| nbody                    | 148 ms                                                 | 94.0 ms: 1.58x faster                                                  |
| coroutines               | 34.5 ms                                                | 21.9 ms: 1.57x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 563 ms: 1.54x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 38.5 us: 1.53x faster                                                  |
| pyflate                  | 708 ms                                                 | 466 ms: 1.52x faster                                                   |
| scimark_lu               | 175 ms                                                 | 116 ms: 1.51x faster                                                   |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.50x faster                                                 |
| unpickle_pure_python     | 327 us                                                 | 219 us: 1.49x faster                                                   |
| logging_simple           | 8.27 us                                                | 5.68 us: 1.46x faster                                                  |
| logging_format           | 9.07 us                                                | 6.24 us: 1.45x faster                                                  |
| tomli_loads              | 3.06 sec                                               | 2.13 sec: 1.44x faster                                                 |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                                 |
| spectral_norm            | 163 ms                                                 | 114 ms: 1.43x faster                                                   |
| float                    | 116 ms                                                 | 81.8 ms: 1.42x faster                                                  |
| mako                     | 16.3 ms                                                | 11.5 ms: 1.42x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 713 ms: 1.41x faster                                                   |
| chameleon                | 9.84 ms                                                | 6.98 ms: 1.41x faster                                                  |
| pprint_pformat           | 2.10 sec                                               | 1.51 sec: 1.39x faster                                                 |
| deepcopy                 | 481 us                                                 | 348 us: 1.38x faster                                                   |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 738 ms: 1.38x faster                                                   |
| regex_compile            | 186 ms                                                 | 135 ms: 1.37x faster                                                   |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| tornado_http             | 131 ms                                                 | 96.1 ms: 1.36x faster                                                  |
| fannkuch                 | 527 ms                                                 | 393 ms: 1.34x faster                                                   |
| xml_etree_process        | 79.8 ms                                                | 59.4 ms: 1.34x faster                                                  |
| deepcopy_reduce          | 4.17 us                                                | 3.11 us: 1.34x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.33x faster                                                   |
| unpack_sequence          | 65.7 ns                                                | 49.4 ns: 1.33x faster                                                  |
| nqueens                  | 107 ms                                                 | 81.4 ms: 1.31x faster                                                  |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| pycparser                | 1.57 sec                                               | 1.20 sec: 1.31x faster                                                 |
| sympy_integrate          | 25.4 ms                                                | 19.5 ms: 1.30x faster                                                  |
| mypy2                    | 442 ms                                                 | 342 ms: 1.29x faster                                                   |
| sympy_sum                | 190 ms                                                 | 148 ms: 1.29x faster                                                   |
| sqlglot_optimize         | 68.7 ms                                                | 53.5 ms: 1.28x faster                                                  |
| sympy_str                | 337 ms                                                 | 267 ms: 1.26x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.61 sec: 1.25x faster                                                 |
| sympy_expand             | 558 ms                                                 | 454 ms: 1.23x faster                                                   |
| scimark_fft              | 454 ms                                                 | 372 ms: 1.22x faster                                                   |
| dask                     | 432 ms                                                 | 363 ms: 1.19x faster                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.21 ms: 1.17x faster                                                  |
| dulwich_log              | 77.0 ms                                                | 65.9 ms: 1.17x faster                                                  |
| bench_thread_pool        | 966 us                                                 | 834 us: 1.16x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 86.4 ms: 1.16x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.54 sec: 1.16x faster                                                 |
| json_loads               | 31.4 us                                                | 27.8 us: 1.13x faster                                                  |
| pathlib                  | 20.3 ms                                                | 18.2 ms: 1.11x faster                                                  |
| json                     | 5.67 ms                                                | 5.12 ms: 1.11x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 105 ms: 1.10x faster                                                   |
| meteor_contest           | 119 ms                                                 | 108 ms: 1.10x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.09x faster                                                  |
| xml_etree_parse          | 171 ms                                                 | 157 ms: 1.09x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.81 us: 1.08x faster                                                  |
| regex_v8                 | 26.2 ms                                                | 24.5 ms: 1.07x faster                                                  |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                                   |
| unpickle_list            | 5.10 us                                                | 5.06 us: 1.01x faster                                                  |
| pickle_list              | 5.05 us                                                | 5.09 us: 1.01x slower                                                  |
| regex_dna                | 215 ms                                                 | 217 ms: 1.01x slower                                                   |
| async_generators         | 442 ms                                                 | 447 ms: 1.01x slower                                                   |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| regex_effbot             | 3.41 ms                                                | 3.57 ms: 1.05x slower                                                  |
| pickle                   | 10.7 us                                                | 11.7 us: 1.10x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 3.87 ms: 1.13x slower                                                  |
| pickle_dict              | 30.0 us                                                | 34.2 us: 1.14x slower                                                  |
| coverage                 | 82.0 ms                                                | 95.0 ms: 1.16x slower                                                  |
| telco                    | 7.01 ms                                                | 8.41 ms: 1.20x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 9.02 ms: 1.54x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.33x faster                                                           |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231115-3.13.0a1+-7e2308a/bm-20231115-linux-x86_64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.26x
