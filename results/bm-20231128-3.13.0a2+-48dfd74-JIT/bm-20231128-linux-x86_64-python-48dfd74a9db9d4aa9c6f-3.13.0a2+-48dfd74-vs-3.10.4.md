
# Results vs. 3.10.4

- fork: python
- ref: 48dfd74a9db9d4aa9c6f
- machine: linux-x86_64
- commit hash: 48dfd74
- commit date: 2023-11-28
- overall geometric mean: 1.32x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| chameleon      | 9.84 ms                                                | 7.06 ms: 1.39x faster                                                  |
| docutils       | 3.26 sec                                               | 2.60 sec: 1.26x faster                                                 |
| tornado_http   | 131 ms                                                 | 94.9 ms: 1.38x faster                                                  |
| Geometric mean | (ref)                                                  | 1.33x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 436 ms: 1.68x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 558 ms: 1.55x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.51x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 706 ms: 1.43x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.54x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 91.8 ms: 1.61x faster                                                  |
| float          | 116 ms                                                 | 81.5 ms: 1.43x faster                                                  |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                  | 1.33x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 135 ms: 1.38x faster                                                   |
| regex_v8       | 26.2 ms                                                | 25.7 ms: 1.02x faster                                                  |
| regex_effbot   | 3.41 ms                                                | 3.62 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                                           |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 302 us: 1.59x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 216 us: 1.51x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.15 sec: 1.42x faster                                                 |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 59.7 ms: 1.34x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 87.6 ms: 1.14x faster                                                  |
| json_loads           | 31.4 us                                                | 28.5 us: 1.10x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.10x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                                   |
| pickle_list          | 5.05 us                                                | 5.10 us: 1.01x slower                                                  |
| unpickle_list        | 5.10 us                                                | 5.25 us: 1.03x slower                                                  |
| unpickle             | 14.9 us                                                | 15.4 us: 1.04x slower                                                  |
| pickle               | 10.7 us                                                | 11.1 us: 1.04x slower                                                  |
| pickle_dict          | 30.0 us                                                | 33.4 us: 1.11x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 8.98 ms: 1.53x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.6 ms: 1.41x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 119 us: 4.70x faster                                                   |
| generators               | 78.9 ms                                                | 29.8 ms: 2.65x faster                                                  |
| deltablue                | 7.81 ms                                                | 3.29 ms: 2.38x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 486 ms: 1.89x faster                                                   |
| chaos                    | 114 ms                                                 | 61.8 ms: 1.85x faster                                                  |
| logging_silent           | 189 ns                                                 | 105 ns: 1.80x faster                                                   |
| raytrace                 | 498 ms                                                 | 279 ms: 1.78x faster                                                   |
| crypto_pyaes             | 127 ms                                                 | 71.4 ms: 1.77x faster                                                  |
| richards_super           | 95.6 ms                                                | 54.1 ms: 1.77x faster                                                  |
| comprehensions           | 28.5 us                                                | 16.4 us: 1.74x faster                                                  |
| scimark_sor              | 214 ms                                                 | 124 ms: 1.73x faster                                                   |
| scimark_monte_carlo      | 118 ms                                                 | 68.6 ms: 1.72x faster                                                  |
| hexiom                   | 10.3 ms                                                | 6.02 ms: 1.71x faster                                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.28 ms: 1.68x faster                                                  |
| async_tree_none          | 732 ms                                                 | 436 ms: 1.68x faster                                                   |
| go                       | 238 ms                                                 | 142 ms: 1.68x faster                                                   |
| richards                 | 79.4 ms                                                | 47.4 ms: 1.67x faster                                                  |
| nbody                    | 148 ms                                                 | 91.8 ms: 1.61x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.59 ms: 1.60x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 302 us: 1.59x faster                                                   |
| coroutines               | 34.5 ms                                                | 22.1 ms: 1.56x faster                                                  |
| pyflate                  | 708 ms                                                 | 456 ms: 1.55x faster                                                   |
| async_tree_memoization   | 867 ms                                                 | 558 ms: 1.55x faster                                                   |
| scimark_lu               | 175 ms                                                 | 115 ms: 1.52x faster                                                   |
| unpickle_pure_python     | 327 us                                                 | 216 us: 1.51x faster                                                   |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.51x faster                                                 |
| deepcopy_memo            | 58.8 us                                                | 39.3 us: 1.50x faster                                                  |
| spectral_norm            | 163 ms                                                 | 111 ms: 1.47x faster                                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.78 sec: 1.44x faster                                                 |
| logging_format           | 9.07 us                                                | 6.32 us: 1.44x faster                                                  |
| unpack_sequence          | 65.7 ns                                                | 45.9 ns: 1.43x faster                                                  |
| float                    | 116 ms                                                 | 81.5 ms: 1.43x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 706 ms: 1.43x faster                                                   |
| logging_simple           | 8.27 us                                                | 5.80 us: 1.43x faster                                                  |
| tomli_loads              | 3.06 sec                                               | 2.15 sec: 1.42x faster                                                 |
| mako                     | 16.3 ms                                                | 11.6 ms: 1.41x faster                                                  |
| chameleon                | 9.84 ms                                                | 7.06 ms: 1.39x faster                                                  |
| pprint_pformat           | 2.10 sec                                               | 1.50 sec: 1.39x faster                                                 |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| deepcopy                 | 481 us                                                 | 349 us: 1.38x faster                                                   |
| tornado_http             | 131 ms                                                 | 94.9 ms: 1.38x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 737 ms: 1.38x faster                                                   |
| regex_compile            | 186 ms                                                 | 135 ms: 1.38x faster                                                   |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| deepcopy_reduce          | 4.17 us                                                | 3.12 us: 1.34x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 59.7 ms: 1.34x faster                                                  |
| nqueens                  | 107 ms                                                 | 80.1 ms: 1.33x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 107 ms: 1.32x faster                                                   |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| fannkuch                 | 527 ms                                                 | 404 ms: 1.31x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 19.5 ms: 1.30x faster                                                  |
| sympy_sum                | 190 ms                                                 | 147 ms: 1.30x faster                                                   |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.29x faster                                                 |
| sqlglot_optimize         | 68.7 ms                                                | 53.9 ms: 1.27x faster                                                  |
| sympy_str                | 337 ms                                                 | 268 ms: 1.26x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.60 sec: 1.26x faster                                                 |
| scimark_fft              | 454 ms                                                 | 369 ms: 1.23x faster                                                   |
| sympy_expand             | 558 ms                                                 | 457 ms: 1.22x faster                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.00 ms: 1.22x faster                                                  |
| dask                     | 432 ms                                                 | 360 ms: 1.20x faster                                                   |
| dulwich_log              | 77.0 ms                                                | 65.5 ms: 1.18x faster                                                  |
| bench_thread_pool        | 966 us                                                 | 832 us: 1.16x faster                                                   |
| mdp                      | 2.93 sec                                               | 2.54 sec: 1.15x faster                                                 |
| xml_etree_generate       | 100.0 ms                                               | 87.6 ms: 1.14x faster                                                  |
| pathlib                  | 20.3 ms                                                | 18.0 ms: 1.12x faster                                                  |
| json_loads               | 31.4 us                                                | 28.5 us: 1.10x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 105 ms: 1.10x faster                                                   |
| meteor_contest           | 119 ms                                                 | 108 ms: 1.10x faster                                                   |
| json                     | 5.67 ms                                                | 5.16 ms: 1.10x faster                                                  |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                                  |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.84 us: 1.07x faster                                                  |
| regex_v8                 | 26.2 ms                                                | 25.7 ms: 1.02x faster                                                  |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| asyncio_websockets       | 558 ms                                                 | 554 ms: 1.01x faster                                                   |
| async_generators         | 442 ms                                                 | 445 ms: 1.01x slower                                                   |
| pickle_list              | 5.05 us                                                | 5.10 us: 1.01x slower                                                  |
| unpickle_list            | 5.10 us                                                | 5.25 us: 1.03x slower                                                  |
| unpickle                 | 14.9 us                                                | 15.4 us: 1.04x slower                                                  |
| pickle                   | 10.7 us                                                | 11.1 us: 1.04x slower                                                  |
| regex_effbot             | 3.41 ms                                                | 3.62 ms: 1.06x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 3.64 ms: 1.06x slower                                                  |
| pickle_dict              | 30.0 us                                                | 33.4 us: 1.11x slower                                                  |
| coverage                 | 82.0 ms                                                | 95.5 ms: 1.16x slower                                                  |
| telco                    | 7.01 ms                                                | 8.42 ms: 1.20x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 8.98 ms: 1.53x slower                                                  |
| mypy2                    | 442 ms                                                 | 842 ms: 1.90x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.32x faster                                                           |

Benchmark hidden because not significant (2): bench_mp_pool, regex_dna
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231128-3.13.0a2+-48dfd74-JIT/bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2+-48dfd74.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.25x
