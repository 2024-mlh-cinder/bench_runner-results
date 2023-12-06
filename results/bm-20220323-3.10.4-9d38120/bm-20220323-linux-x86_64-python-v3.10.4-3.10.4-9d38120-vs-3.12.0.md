
# Results vs. 3.12.0

- fork: python
- ref: v3.10.4
- machine: linux-x86_64
- commit hash: 9d38120
- commit date: 2022-03-23
- overall geometric mean: 1.29x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 346 ms: 1.26x slower                                   |
| chameleon      | 7.41 ms                                                | 9.84 ms: 1.33x slower                                  |
| docutils       | 2.75 sec                                               | 3.26 sec: 1.19x slower                                 |
| tornado_http   | 101 ms                                                 | 131 ms: 1.30x slower                                   |
| Geometric mean | (ref)                                                  | 1.27x slower                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 1.01 sec: 1.39x slower                                 |
| async_tree_memoization  | 580 ms                                                 | 867 ms: 1.50x slower                                   |
| async_tree_io           | 1.16 sec                                               | 1.79 sec: 1.54x slower                                 |
| async_tree_none         | 475 ms                                                 | 732 ms: 1.54x slower                                   |
| Geometric mean          | (ref)                                                  | 1.49x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 190 ms: 1.02x slower                                   |
| float          | 83.3 ms                                                | 116 ms: 1.40x slower                                   |
| nbody          | 92.2 ms                                                | 148 ms: 1.61x slower                                   |
| Geometric mean | (ref)                                                  | 1.32x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.41 ms: 1.05x faster                                  |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                   |
| regex_v8       | 22.7 ms                                                | 26.2 ms: 1.16x slower                                  |
| regex_compile  | 148 ms                                                 | 186 ms: 1.25x slower                                   |
| Geometric mean | (ref)                                                  | 1.09x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 30.0 us: 1.12x faster                                  |
| unpickle             | 15.8 us                                                | 14.9 us: 1.06x faster                                  |
| pickle               | 11.2 us                                                | 10.7 us: 1.05x faster                                  |
| unpickle_list        | 5.04 us                                                | 5.10 us: 1.01x slower                                  |
| xml_etree_parse      | 159 ms                                                 | 171 ms: 1.07x slower                                   |
| pickle_list          | 4.67 us                                                | 5.05 us: 1.08x slower                                  |
| xml_etree_iterparse  | 106 ms                                                 | 116 ms: 1.10x slower                                   |
| json_loads           | 28.4 us                                                | 31.4 us: 1.11x slower                                  |
| xml_etree_generate   | 88.7 ms                                                | 100.0 ms: 1.13x slower                                 |
| xml_etree_process    | 61.2 ms                                                | 79.8 ms: 1.30x slower                                  |
| tomli_loads          | 2.30 sec                                               | 3.06 sec: 1.33x slower                                 |
| json_dumps           | 10.6 ms                                                | 14.3 ms: 1.35x slower                                  |
| unpickle_pure_python | 230 us                                                 | 327 us: 1.42x slower                                   |
| pickle_pure_python   | 326 us                                                 | 482 us: 1.48x slower                                   |
| Geometric mean       | (ref)                                                  | 1.14x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 5.87 ms: 1.18x faster                                  |
| python_startup         | 9.53 ms                                                | 14.3 ms: 1.50x slower                                  |
| Geometric mean         | (ref)                                                  | 1.13x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| django_template | 35.0 ms                                                | 47.6 ms: 1.36x slower                                  |
| mako            | 11.5 ms                                                | 16.3 ms: 1.42x slower                                  |
| Geometric mean  | (ref)                                                  | 1.39x slower                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| gc_traversal             | 4.28 ms                                                | 3.43 ms: 1.25x faster                                  |
| python_startup_no_site   | 6.92 ms                                                | 5.87 ms: 1.18x faster                                  |
| pickle_dict              | 33.5 us                                                | 30.0 us: 1.12x faster                                  |
| unpickle                 | 15.8 us                                                | 14.9 us: 1.06x faster                                  |
| pickle                   | 11.2 us                                                | 10.7 us: 1.05x faster                                  |
| regex_effbot             | 3.57 ms                                                | 3.41 ms: 1.05x faster                                  |
| async_generators         | 459 ms                                                 | 442 ms: 1.04x faster                                   |
| telco                    | 7.18 ms                                                | 7.01 ms: 1.02x faster                                  |
| unpickle_list            | 5.04 us                                                | 5.10 us: 1.01x slower                                  |
| asyncio_websockets       | 552 ms                                                 | 558 ms: 1.01x slower                                   |
| pidigits                 | 187 ms                                                 | 190 ms: 1.02x slower                                   |
| regex_dna                | 209 ms                                                 | 215 ms: 1.03x slower                                   |
| sqlite_synth             | 2.83 us                                                | 3.02 us: 1.07x slower                                  |
| xml_etree_parse          | 159 ms                                                 | 171 ms: 1.07x slower                                   |
| pathlib                  | 18.9 ms                                                | 20.3 ms: 1.07x slower                                  |
| pickle_list              | 4.67 us                                                | 5.05 us: 1.08x slower                                  |
| json                     | 5.22 ms                                                | 5.67 ms: 1.09x slower                                  |
| meteor_contest           | 110 ms                                                 | 119 ms: 1.09x slower                                   |
| coverage                 | 75.1 ms                                                | 82.0 ms: 1.09x slower                                  |
| xml_etree_iterparse      | 106 ms                                                 | 116 ms: 1.10x slower                                   |
| json_loads               | 28.4 us                                                | 31.4 us: 1.11x slower                                  |
| create_gc_cycles         | 1.45 ms                                                | 1.61 ms: 1.11x slower                                  |
| dulwich_log              | 68.7 ms                                                | 77.0 ms: 1.12x slower                                  |
| xml_etree_generate       | 88.7 ms                                                | 100.0 ms: 1.13x slower                                 |
| sympy_sum                | 167 ms                                                 | 190 ms: 1.14x slower                                   |
| sympy_str                | 296 ms                                                 | 337 ms: 1.14x slower                                   |
| mdp                      | 2.57 sec                                               | 2.93 sec: 1.14x slower                                 |
| scimark_sparse_mat_mult  | 5.33 ms                                                | 6.10 ms: 1.14x slower                                  |
| bench_thread_pool        | 845 us                                                 | 966 us: 1.14x slower                                   |
| regex_v8                 | 22.7 ms                                                | 26.2 ms: 1.16x slower                                  |
| sqlalchemy_declarative   | 147 ms                                                 | 170 ms: 1.16x slower                                   |
| dask                     | 369 ms                                                 | 432 ms: 1.17x slower                                   |
| sympy_expand             | 476 ms                                                 | 558 ms: 1.17x slower                                   |
| sqlalchemy_imperative    | 18.5 ms                                                | 21.9 ms: 1.18x slower                                  |
| docutils                 | 2.75 sec                                               | 3.26 sec: 1.19x slower                                 |
| gunicorn                 | 1.24 ms                                                | 1.48 ms: 1.19x slower                                  |
| scimark_fft              | 381 ms                                                 | 454 ms: 1.19x slower                                   |
| sympy_integrate          | 21.2 ms                                                | 25.4 ms: 1.20x slower                                  |
| unpack_sequence          | 54.2 ns                                                | 65.7 ns: 1.21x slower                                  |
| aiohttp                  | 1.15 ms                                                | 1.41 ms: 1.23x slower                                  |
| nqueens                  | 86.2 ms                                                | 107 ms: 1.24x slower                                   |
| regex_compile            | 148 ms                                                 | 186 ms: 1.25x slower                                   |
| sqlglot_optimize         | 54.8 ms                                                | 68.7 ms: 1.25x slower                                  |
| 2to3                     | 274 ms                                                 | 346 ms: 1.26x slower                                   |
| mypy2                    | 351 ms                                                 | 442 ms: 1.26x slower                                   |
| sqlglot_normalize        | 112 ms                                                 | 141 ms: 1.27x slower                                   |
| logging_format           | 7.10 us                                                | 9.07 us: 1.28x slower                                  |
| fannkuch                 | 410 ms                                                 | 527 ms: 1.29x slower                                   |
| deepcopy_reduce          | 3.23 us                                                | 4.17 us: 1.29x slower                                  |
| logging_simple           | 6.38 us                                                | 8.27 us: 1.30x slower                                  |
| tornado_http             | 101 ms                                                 | 131 ms: 1.30x slower                                   |
| xml_etree_process        | 61.2 ms                                                | 79.8 ms: 1.30x slower                                  |
| pprint_safe_repr         | 765 ms                                                 | 1.01 sec: 1.33x slower                                 |
| deepcopy                 | 363 us                                                 | 481 us: 1.33x slower                                   |
| chameleon                | 7.41 ms                                                | 9.84 ms: 1.33x slower                                  |
| tomli_loads              | 2.30 sec                                               | 3.06 sec: 1.33x slower                                 |
| pycparser                | 1.17 sec                                               | 1.57 sec: 1.34x slower                                 |
| pprint_pformat           | 1.55 sec                                               | 2.10 sec: 1.35x slower                                 |
| json_dumps               | 10.6 ms                                                | 14.3 ms: 1.35x slower                                  |
| django_template          | 35.0 ms                                                | 47.6 ms: 1.36x slower                                  |
| comprehensions           | 20.9 us                                                | 28.5 us: 1.36x slower                                  |
| async_tree_cpu_io_mixed  | 724 ms                                                 | 1.01 sec: 1.39x slower                                 |
| float                    | 83.3 ms                                                | 116 ms: 1.40x slower                                   |
| mako                     | 11.5 ms                                                | 16.3 ms: 1.42x slower                                  |
| spectral_norm            | 115 ms                                                 | 163 ms: 1.42x slower                                   |
| unpickle_pure_python     | 230 us                                                 | 327 us: 1.42x slower                                   |
| asyncio_tcp_ssl          | 1.78 sec                                               | 2.58 sec: 1.45x slower                                 |
| scimark_lu               | 120 ms                                                 | 175 ms: 1.46x slower                                   |
| coroutines               | 23.5 ms                                                | 34.5 ms: 1.47x slower                                  |
| pickle_pure_python       | 326 us                                                 | 482 us: 1.48x slower                                   |
| deepcopy_memo            | 39.7 us                                                | 58.8 us: 1.48x slower                                  |
| async_tree_memoization   | 580 ms                                                 | 867 ms: 1.50x slower                                   |
| python_startup           | 9.53 ms                                                | 14.3 ms: 1.50x slower                                  |
| pyflate                  | 471 ms                                                 | 708 ms: 1.50x slower                                   |
| crypto_pyaes             | 83.6 ms                                                | 127 ms: 1.52x slower                                   |
| sqlglot_transpile        | 1.68 ms                                                | 2.55 ms: 1.52x slower                                  |
| async_tree_io            | 1.16 sec                                               | 1.79 sec: 1.54x slower                                 |
| async_tree_none          | 475 ms                                                 | 732 ms: 1.54x slower                                   |
| hexiom                   | 6.54 ms                                                | 10.3 ms: 1.57x slower                                  |
| scimark_monte_carlo      | 74.6 ms                                                | 118 ms: 1.58x slower                                   |
| sqlglot_parse            | 1.35 ms                                                | 2.15 ms: 1.59x slower                                  |
| nbody                    | 92.2 ms                                                | 148 ms: 1.61x slower                                   |
| raytrace                 | 308 ms                                                 | 498 ms: 1.62x slower                                   |
| scimark_sor              | 129 ms                                                 | 214 ms: 1.66x slower                                   |
| go                       | 140 ms                                                 | 238 ms: 1.69x slower                                   |
| chaos                    | 67.5 ms                                                | 114 ms: 1.69x slower                                   |
| richards                 | 46.0 ms                                                | 79.4 ms: 1.73x slower                                  |
| logging_silent           | 108 ns                                                 | 189 ns: 1.76x slower                                   |
| asyncio_tcp              | 506 ms                                                 | 918 ms: 1.82x slower                                   |
| richards_super           | 51.9 ms                                                | 95.6 ms: 1.84x slower                                  |
| deltablue                | 3.71 ms                                                | 7.81 ms: 2.11x slower                                  |
| generators               | 32.5 ms                                                | 78.9 ms: 2.43x slower                                  |
| typing_runtime_protocols | 153 us                                                 | 560 us: 3.65x slower                                   |
| Geometric mean           | (ref)                                                  | 1.29x slower                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
Ignored benchmarks (7) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.25x
- 95% likely to have a slowdown of 1.24x
- 99% likely to have a slowdown of 1.20x
