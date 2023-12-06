
# Results vs. 3.10.4

- fork: python
- ref: 05a370abd6cdfe4b54be
- machine: linux-x86_64
- commit hash: 05a370a
- commit date: 2023-12-01
- overall geometric mean: 1.32x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| chameleon      | 9.84 ms                                                | 6.88 ms: 1.43x faster                                                  |
| docutils       | 3.26 sec                                               | 2.61 sec: 1.25x faster                                                 |
| tornado_http   | 131 ms                                                 | 96.0 ms: 1.36x faster                                                  |
| Geometric mean | (ref)                                                  | 1.34x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 437 ms: 1.67x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 566 ms: 1.53x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.18 sec: 1.51x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 714 ms: 1.41x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.53x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 92.3 ms: 1.60x faster                                                  |
| float          | 116 ms                                                 | 82.3 ms: 1.41x faster                                                  |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                  | 1.32x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 133 ms: 1.40x faster                                                   |
| regex_v8       | 26.2 ms                                                | 26.1 ms: 1.01x faster                                                  |
| regex_dna      | 215 ms                                                 | 214 ms: 1.00x faster                                                   |
| regex_effbot   | 3.41 ms                                                | 3.59 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 305 us: 1.58x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 217 us: 1.51x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.19 sec: 1.39x faster                                                 |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 59.5 ms: 1.34x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 87.0 ms: 1.15x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.11x faster                                                   |
| json_loads           | 31.4 us                                                | 28.3 us: 1.11x faster                                                  |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.09x faster                                                   |
| pickle_list          | 5.05 us                                                | 4.91 us: 1.03x faster                                                  |
| unpickle_list        | 5.10 us                                                | 5.23 us: 1.03x slower                                                  |
| unpickle             | 14.9 us                                                | 15.3 us: 1.03x slower                                                  |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                                  |
| pickle_dict          | 30.0 us                                                | 33.0 us: 1.10x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.16x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 8.95 ms: 1.53x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.1 ms: 1.47x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 115 us: 4.88x faster                                                   |
| generators               | 78.9 ms                                                | 28.3 ms: 2.78x faster                                                  |
| deltablue                | 7.81 ms                                                | 3.28 ms: 2.38x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 488 ms: 1.88x faster                                                   |
| chaos                    | 114 ms                                                 | 61.9 ms: 1.85x faster                                                  |
| raytrace                 | 498 ms                                                 | 275 ms: 1.81x faster                                                   |
| comprehensions           | 28.5 us                                                | 16.0 us: 1.78x faster                                                  |
| richards_super           | 95.6 ms                                                | 53.8 ms: 1.78x faster                                                  |
| crypto_pyaes             | 127 ms                                                 | 71.8 ms: 1.77x faster                                                  |
| logging_silent           | 189 ns                                                 | 108 ns: 1.75x faster                                                   |
| scimark_sor              | 214 ms                                                 | 124 ms: 1.73x faster                                                   |
| scimark_monte_carlo      | 118 ms                                                 | 68.5 ms: 1.72x faster                                                  |
| go                       | 238 ms                                                 | 140 ms: 1.70x faster                                                   |
| async_tree_none          | 732 ms                                                 | 437 ms: 1.67x faster                                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.28 ms: 1.67x faster                                                  |
| hexiom                   | 10.3 ms                                                | 6.19 ms: 1.66x faster                                                  |
| richards                 | 79.4 ms                                                | 48.0 ms: 1.66x faster                                                  |
| nbody                    | 148 ms                                                 | 92.3 ms: 1.60x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.60 ms: 1.60x faster                                                  |
| coroutines               | 34.5 ms                                                | 21.7 ms: 1.59x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 305 us: 1.58x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 38.2 us: 1.54x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 566 ms: 1.53x faster                                                   |
| pyflate                  | 708 ms                                                 | 467 ms: 1.52x faster                                                   |
| scimark_lu               | 175 ms                                                 | 116 ms: 1.52x faster                                                   |
| async_tree_io            | 1.79 sec                                               | 1.18 sec: 1.51x faster                                                 |
| unpickle_pure_python     | 327 us                                                 | 217 us: 1.51x faster                                                   |
| mako                     | 16.3 ms                                                | 11.1 ms: 1.47x faster                                                  |
| logging_simple           | 8.27 us                                                | 5.68 us: 1.46x faster                                                  |
| logging_format           | 9.07 us                                                | 6.26 us: 1.45x faster                                                  |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                                 |
| spectral_norm            | 163 ms                                                 | 114 ms: 1.43x faster                                                   |
| chameleon                | 9.84 ms                                                | 6.88 ms: 1.43x faster                                                  |
| float                    | 116 ms                                                 | 82.3 ms: 1.41x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 714 ms: 1.41x faster                                                   |
| regex_compile            | 186 ms                                                 | 133 ms: 1.40x faster                                                   |
| tomli_loads              | 3.06 sec                                               | 2.19 sec: 1.39x faster                                                 |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| pprint_pformat           | 2.10 sec                                               | 1.52 sec: 1.38x faster                                                 |
| deepcopy                 | 481 us                                                 | 349 us: 1.38x faster                                                   |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| tornado_http             | 131 ms                                                 | 96.0 ms: 1.36x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 748 ms: 1.36x faster                                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.10 us: 1.34x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 59.5 ms: 1.34x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.33x faster                                                   |
| fannkuch                 | 527 ms                                                 | 398 ms: 1.32x faster                                                   |
| nqueens                  | 107 ms                                                 | 80.7 ms: 1.32x faster                                                  |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 19.6 ms: 1.30x faster                                                  |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.29x faster                                                 |
| sqlglot_optimize         | 68.7 ms                                                | 53.4 ms: 1.29x faster                                                  |
| sympy_sum                | 190 ms                                                 | 148 ms: 1.28x faster                                                   |
| unpack_sequence          | 65.7 ns                                                | 51.6 ns: 1.27x faster                                                  |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.81 ms: 1.27x faster                                                  |
| sympy_str                | 337 ms                                                 | 267 ms: 1.26x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.61 sec: 1.25x faster                                                 |
| scimark_fft              | 454 ms                                                 | 365 ms: 1.24x faster                                                   |
| sympy_expand             | 558 ms                                                 | 453 ms: 1.23x faster                                                   |
| dask                     | 432 ms                                                 | 361 ms: 1.20x faster                                                   |
| dulwich_log              | 77.0 ms                                                | 65.9 ms: 1.17x faster                                                  |
| bench_thread_pool        | 966 us                                                 | 829 us: 1.17x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 87.0 ms: 1.15x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.56 sec: 1.15x faster                                                 |
| pathlib                  | 20.3 ms                                                | 18.2 ms: 1.12x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 105 ms: 1.11x faster                                                   |
| json_loads               | 31.4 us                                                | 28.3 us: 1.11x faster                                                  |
| meteor_contest           | 119 ms                                                 | 108 ms: 1.11x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                                  |
| json                     | 5.67 ms                                                | 5.18 ms: 1.10x faster                                                  |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.09x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.82 us: 1.07x faster                                                  |
| pickle_list              | 5.05 us                                                | 4.91 us: 1.03x faster                                                  |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                                   |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                   |
| regex_v8                 | 26.2 ms                                                | 26.1 ms: 1.01x faster                                                  |
| regex_dna                | 215 ms                                                 | 214 ms: 1.00x faster                                                   |
| async_generators         | 442 ms                                                 | 445 ms: 1.01x slower                                                   |
| unpickle_list            | 5.10 us                                                | 5.23 us: 1.03x slower                                                  |
| unpickle                 | 14.9 us                                                | 15.3 us: 1.03x slower                                                  |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                                  |
| regex_effbot             | 3.41 ms                                                | 3.59 ms: 1.05x slower                                                  |
| pickle_dict              | 30.0 us                                                | 33.0 us: 1.10x slower                                                  |
| coverage                 | 82.0 ms                                                | 94.4 ms: 1.15x slower                                                  |
| telco                    | 7.01 ms                                                | 8.28 ms: 1.18x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 4.29 ms: 1.25x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 8.95 ms: 1.53x slower                                                  |
| mypy2                    | 442 ms                                                 | 838 ms: 1.90x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.32x faster                                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231201-3.13.0a2+-05a370a/bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.25x
