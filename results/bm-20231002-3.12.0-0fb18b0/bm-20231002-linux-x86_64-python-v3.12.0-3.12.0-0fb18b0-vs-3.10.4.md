
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0
- machine: linux-x86_64
- commit hash: 0fb18b0
- commit date: 2023-10-02
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 274 ms: 1.26x faster                                   |
| chameleon      | 9.84 ms                                                | 7.41 ms: 1.33x faster                                  |
| docutils       | 3.26 sec                                               | 2.75 sec: 1.19x faster                                 |
| tornado_http   | 131 ms                                                 | 101 ms: 1.30x faster                                   |
| Geometric mean | (ref)                                                  | 1.27x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 475 ms: 1.54x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.16 sec: 1.54x faster                                 |
| async_tree_memoization  | 867 ms                                                 | 580 ms: 1.50x faster                                   |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 724 ms: 1.39x faster                                   |
| Geometric mean          | (ref)                                                  | 1.49x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 148 ms                                                 | 92.2 ms: 1.61x faster                                  |
| float          | 116 ms                                                 | 83.3 ms: 1.40x faster                                  |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                   |
| Geometric mean | (ref)                                                  | 1.32x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 148 ms: 1.25x faster                                   |
| regex_v8       | 26.2 ms                                                | 22.7 ms: 1.16x faster                                  |
| regex_dna      | 215 ms                                                 | 209 ms: 1.03x faster                                   |
| regex_effbot   | 3.41 ms                                                | 3.57 ms: 1.05x slower                                  |
| Geometric mean | (ref)                                                  | 1.09x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 326 us: 1.48x faster                                   |
| unpickle_pure_python | 327 us                                                 | 230 us: 1.42x faster                                   |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                  |
| tomli_loads          | 3.06 sec                                               | 2.30 sec: 1.33x faster                                 |
| xml_etree_process    | 79.8 ms                                                | 61.2 ms: 1.30x faster                                  |
| xml_etree_generate   | 100.0 ms                                               | 88.7 ms: 1.13x faster                                  |
| json_loads           | 31.4 us                                                | 28.4 us: 1.11x faster                                  |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.10x faster                                   |
| pickle_list          | 5.05 us                                                | 4.67 us: 1.08x faster                                  |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.07x faster                                   |
| unpickle_list        | 5.10 us                                                | 5.04 us: 1.01x faster                                  |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                  |
| unpickle             | 14.9 us                                                | 15.8 us: 1.06x slower                                  |
| pickle_dict          | 30.0 us                                                | 33.5 us: 1.12x slower                                  |
| Geometric mean       | (ref)                                                  | 1.14x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 9.53 ms: 1.50x faster                                  |
| python_startup_no_site | 5.87 ms                                                | 6.92 ms: 1.18x slower                                  |
| Geometric mean         | (ref)                                                  | 1.13x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 16.3 ms                                                | 11.5 ms: 1.42x faster                                  |
| django_template | 47.6 ms                                                | 35.0 ms: 1.36x faster                                  |
| Geometric mean  | (ref)                                                  | 1.39x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 153 us: 3.65x faster                                   |
| generators               | 78.9 ms                                                | 32.5 ms: 2.43x faster                                  |
| deltablue                | 7.81 ms                                                | 3.71 ms: 2.11x faster                                  |
| richards_super           | 95.6 ms                                                | 51.9 ms: 1.84x faster                                  |
| asyncio_tcp              | 918 ms                                                 | 506 ms: 1.82x faster                                   |
| logging_silent           | 189 ns                                                 | 108 ns: 1.76x faster                                   |
| richards                 | 79.4 ms                                                | 46.0 ms: 1.73x faster                                  |
| chaos                    | 114 ms                                                 | 67.5 ms: 1.69x faster                                  |
| go                       | 238 ms                                                 | 140 ms: 1.69x faster                                   |
| scimark_sor              | 214 ms                                                 | 129 ms: 1.66x faster                                   |
| raytrace                 | 498 ms                                                 | 308 ms: 1.62x faster                                   |
| nbody                    | 148 ms                                                 | 92.2 ms: 1.61x faster                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.35 ms: 1.59x faster                                  |
| scimark_monte_carlo      | 118 ms                                                 | 74.6 ms: 1.58x faster                                  |
| hexiom                   | 10.3 ms                                                | 6.54 ms: 1.57x faster                                  |
| async_tree_none          | 732 ms                                                 | 475 ms: 1.54x faster                                   |
| async_tree_io            | 1.79 sec                                               | 1.16 sec: 1.54x faster                                 |
| sqlglot_transpile        | 2.55 ms                                                | 1.68 ms: 1.52x faster                                  |
| crypto_pyaes             | 127 ms                                                 | 83.6 ms: 1.52x faster                                  |
| pyflate                  | 708 ms                                                 | 471 ms: 1.50x faster                                   |
| python_startup           | 14.3 ms                                                | 9.53 ms: 1.50x faster                                  |
| async_tree_memoization   | 867 ms                                                 | 580 ms: 1.50x faster                                   |
| deepcopy_memo            | 58.8 us                                                | 39.7 us: 1.48x faster                                  |
| pickle_pure_python       | 482 us                                                 | 326 us: 1.48x faster                                   |
| coroutines               | 34.5 ms                                                | 23.5 ms: 1.47x faster                                  |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.46x faster                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.78 sec: 1.45x faster                                 |
| unpickle_pure_python     | 327 us                                                 | 230 us: 1.42x faster                                   |
| spectral_norm            | 163 ms                                                 | 115 ms: 1.42x faster                                   |
| mako                     | 16.3 ms                                                | 11.5 ms: 1.42x faster                                  |
| float                    | 116 ms                                                 | 83.3 ms: 1.40x faster                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 724 ms: 1.39x faster                                   |
| comprehensions           | 28.5 us                                                | 20.9 us: 1.36x faster                                  |
| django_template          | 47.6 ms                                                | 35.0 ms: 1.36x faster                                  |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                  |
| pprint_pformat           | 2.10 sec                                               | 1.55 sec: 1.35x faster                                 |
| pycparser                | 1.57 sec                                               | 1.17 sec: 1.34x faster                                 |
| tomli_loads              | 3.06 sec                                               | 2.30 sec: 1.33x faster                                 |
| chameleon                | 9.84 ms                                                | 7.41 ms: 1.33x faster                                  |
| deepcopy                 | 481 us                                                 | 363 us: 1.33x faster                                   |
| pprint_safe_repr         | 1.01 sec                                               | 765 ms: 1.33x faster                                   |
| xml_etree_process        | 79.8 ms                                                | 61.2 ms: 1.30x faster                                  |
| tornado_http             | 131 ms                                                 | 101 ms: 1.30x faster                                   |
| logging_simple           | 8.27 us                                                | 6.38 us: 1.30x faster                                  |
| deepcopy_reduce          | 4.17 us                                                | 3.23 us: 1.29x faster                                  |
| fannkuch                 | 527 ms                                                 | 410 ms: 1.29x faster                                   |
| logging_format           | 9.07 us                                                | 7.10 us: 1.28x faster                                  |
| sqlglot_normalize        | 141 ms                                                 | 112 ms: 1.27x faster                                   |
| mypy2                    | 442 ms                                                 | 351 ms: 1.26x faster                                   |
| 2to3                     | 346 ms                                                 | 274 ms: 1.26x faster                                   |
| sqlglot_optimize         | 68.7 ms                                                | 54.8 ms: 1.25x faster                                  |
| regex_compile            | 186 ms                                                 | 148 ms: 1.25x faster                                   |
| nqueens                  | 107 ms                                                 | 86.2 ms: 1.24x faster                                  |
| aiohttp                  | 1.41 ms                                                | 1.15 ms: 1.23x faster                                  |
| unpack_sequence          | 65.7 ns                                                | 54.2 ns: 1.21x faster                                  |
| sympy_integrate          | 25.4 ms                                                | 21.2 ms: 1.20x faster                                  |
| scimark_fft              | 454 ms                                                 | 381 ms: 1.19x faster                                   |
| gunicorn                 | 1.48 ms                                                | 1.24 ms: 1.19x faster                                  |
| docutils                 | 3.26 sec                                               | 2.75 sec: 1.19x faster                                 |
| sqlalchemy_imperative    | 21.9 ms                                                | 18.5 ms: 1.18x faster                                  |
| sympy_expand             | 558 ms                                                 | 476 ms: 1.17x faster                                   |
| dask                     | 432 ms                                                 | 369 ms: 1.17x faster                                   |
| sqlalchemy_declarative   | 170 ms                                                 | 147 ms: 1.16x faster                                   |
| regex_v8                 | 26.2 ms                                                | 22.7 ms: 1.16x faster                                  |
| bench_thread_pool        | 966 us                                                 | 845 us: 1.14x faster                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.33 ms: 1.14x faster                                  |
| mdp                      | 2.93 sec                                               | 2.57 sec: 1.14x faster                                 |
| sympy_str                | 337 ms                                                 | 296 ms: 1.14x faster                                   |
| sympy_sum                | 190 ms                                                 | 167 ms: 1.14x faster                                   |
| xml_etree_generate       | 100.0 ms                                               | 88.7 ms: 1.13x faster                                  |
| dulwich_log              | 77.0 ms                                                | 68.7 ms: 1.12x faster                                  |
| create_gc_cycles         | 1.61 ms                                                | 1.45 ms: 1.11x faster                                  |
| json_loads               | 31.4 us                                                | 28.4 us: 1.11x faster                                  |
| xml_etree_iterparse      | 116 ms                                                 | 106 ms: 1.10x faster                                   |
| coverage                 | 82.0 ms                                                | 75.1 ms: 1.09x faster                                  |
| meteor_contest           | 119 ms                                                 | 110 ms: 1.09x faster                                   |
| json                     | 5.67 ms                                                | 5.22 ms: 1.09x faster                                  |
| pickle_list              | 5.05 us                                                | 4.67 us: 1.08x faster                                  |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                  |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.07x faster                                   |
| sqlite_synth             | 3.02 us                                                | 2.83 us: 1.07x faster                                  |
| regex_dna                | 215 ms                                                 | 209 ms: 1.03x faster                                   |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                   |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                   |
| unpickle_list            | 5.10 us                                                | 5.04 us: 1.01x faster                                  |
| telco                    | 7.01 ms                                                | 7.18 ms: 1.02x slower                                  |
| async_generators         | 442 ms                                                 | 459 ms: 1.04x slower                                   |
| regex_effbot             | 3.41 ms                                                | 3.57 ms: 1.05x slower                                  |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                  |
| unpickle                 | 14.9 us                                                | 15.8 us: 1.06x slower                                  |
| pickle_dict              | 30.0 us                                                | 33.5 us: 1.12x slower                                  |
| python_startup_no_site   | 5.87 ms                                                | 6.92 ms: 1.18x slower                                  |
| gc_traversal             | 3.43 ms                                                | 4.28 ms: 1.25x slower                                  |
| Geometric mean           | (ref)                                                  | 1.29x faster                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (7) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.20x
