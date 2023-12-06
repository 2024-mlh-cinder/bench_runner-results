
# Results vs. 3.11.0

- fork: python
- ref: v3.10.4
- machine: linux-x86_64
- commit hash: 9d38120
- commit date: 2022-03-23
- overall geometric mean: 1.26x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 346 ms: 1.30x slower                                   |
| chameleon      | 6.86 ms                                                | 9.84 ms: 1.43x slower                                  |
| docutils       | 2.69 sec                                               | 3.26 sec: 1.21x slower                                 |
| html5lib       | 65.0 ms                                                | 88.1 ms: 1.35x slower                                  |
| tornado_http   | 97.7 ms                                                | 131 ms: 1.34x slower                                   |
| Geometric mean | (ref)                                                  | 1.33x slower                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_cpu_io_mixed | 750 ms                                                 | 1.01 sec: 1.34x slower                                 |
| async_tree_memoization  | 640 ms                                                 | 867 ms: 1.35x slower                                   |
| async_tree_io           | 1.31 sec                                               | 1.79 sec: 1.37x slower                                 |
| async_tree_none         | 532 ms                                                 | 732 ms: 1.38x slower                                   |
| Geometric mean          | (ref)                                                  | 1.36x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 190 ms: 1.00x slower                                   |
| float          | 78.9 ms                                                | 116 ms: 1.48x slower                                   |
| nbody          | 91.6 ms                                                | 148 ms: 1.62x slower                                   |
| Geometric mean | (ref)                                                  | 1.34x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.41 ms: 1.01x faster                                  |
| regex_dna      | 204 ms                                                 | 215 ms: 1.05x slower                                   |
| regex_v8       | 22.9 ms                                                | 26.2 ms: 1.15x slower                                  |
| regex_compile  | 141 ms                                                 | 186 ms: 1.31x slower                                   |
| Geometric mean | (ref)                                                  | 1.12x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_dict          | 34.8 us                                                | 30.0 us: 1.16x faster                                  |
| pickle               | 11.1 us                                                | 10.7 us: 1.04x faster                                  |
| unpickle_list        | 5.22 us                                                | 5.10 us: 1.02x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 171 ms: 1.05x slower                                   |
| json_dumps           | 13.5 ms                                                | 14.3 ms: 1.06x slower                                  |
| json_loads           | 29.4 us                                                | 31.4 us: 1.07x slower                                  |
| xml_etree_iterparse  | 109 ms                                                 | 116 ms: 1.07x slower                                   |
| unpickle             | 13.9 us                                                | 14.9 us: 1.07x slower                                  |
| pickle_list          | 4.65 us                                                | 5.05 us: 1.09x slower                                  |
| xml_etree_generate   | 80.4 ms                                                | 100.0 ms: 1.24x slower                                 |
| tomli_loads          | 2.31 sec                                               | 3.06 sec: 1.32x slower                                 |
| unpickle_pure_python | 241 us                                                 | 327 us: 1.36x slower                                   |
| xml_etree_process    | 56.5 ms                                                | 79.8 ms: 1.41x slower                                  |
| pickle_pure_python   | 319 us                                                 | 482 us: 1.51x slower                                   |
| Geometric mean       | (ref)                                                  | 1.13x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.09 ms                                                | 5.87 ms: 1.04x faster                                  |
| python_startup         | 8.69 ms                                                | 14.3 ms: 1.65x slower                                  |
| Geometric mean         | (ref)                                                  | 1.26x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| genshi_xml      | 54.1 ms                                                | 66.0 ms: 1.22x slower                                  |
| genshi_text     | 22.8 ms                                                | 31.7 ms: 1.39x slower                                  |
| django_template | 33.8 ms                                                | 47.6 ms: 1.41x slower                                  |
| mako            | 10.8 ms                                                | 16.3 ms: 1.50x slower                                  |
| Geometric mean  | (ref)                                                  | 1.38x slower                                           |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| asyncio_tcp_ssl          | 3.13 sec                                               | 2.58 sec: 1.21x faster                                 |
| pickle_dict              | 34.8 us                                                | 30.0 us: 1.16x faster                                  |
| gc_traversal             | 3.90 ms                                                | 3.43 ms: 1.14x faster                                  |
| pickle                   | 11.1 us                                                | 10.7 us: 1.04x faster                                  |
| python_startup_no_site   | 6.09 ms                                                | 5.87 ms: 1.04x faster                                  |
| unpickle_list            | 5.22 us                                                | 5.10 us: 1.02x faster                                  |
| regex_effbot             | 3.45 ms                                                | 3.41 ms: 1.01x faster                                  |
| pidigits                 | 190 ms                                                 | 190 ms: 1.00x slower                                   |
| asyncio_websockets       | 556 ms                                                 | 558 ms: 1.00x slower                                   |
| coverage                 | 81.2 ms                                                | 82.0 ms: 1.01x slower                                  |
| generators               | 76.5 ms                                                | 78.9 ms: 1.03x slower                                  |
| asyncio_tcp              | 887 ms                                                 | 918 ms: 1.03x slower                                   |
| telco                    | 6.72 ms                                                | 7.01 ms: 1.04x slower                                  |
| xml_etree_parse          | 163 ms                                                 | 171 ms: 1.05x slower                                   |
| mdp                      | 2.79 sec                                               | 2.93 sec: 1.05x slower                                 |
| regex_dna                | 204 ms                                                 | 215 ms: 1.05x slower                                   |
| json_dumps               | 13.5 ms                                                | 14.3 ms: 1.06x slower                                  |
| json_loads               | 29.4 us                                                | 31.4 us: 1.07x slower                                  |
| xml_etree_iterparse      | 109 ms                                                 | 116 ms: 1.07x slower                                   |
| unpickle                 | 13.9 us                                                | 14.9 us: 1.07x slower                                  |
| typing_runtime_protocols | 521 us                                                 | 560 us: 1.07x slower                                   |
| json                     | 5.24 ms                                                | 5.67 ms: 1.08x slower                                  |
| pickle_list              | 4.65 us                                                | 5.05 us: 1.09x slower                                  |
| create_gc_cycles         | 1.48 ms                                                | 1.61 ms: 1.09x slower                                  |
| meteor_contest           | 109 ms                                                 | 119 ms: 1.09x slower                                   |
| pathlib                  | 18.5 ms                                                | 20.3 ms: 1.10x slower                                  |
| pylint                   | 478 ms                                                 | 534 ms: 1.12x slower                                   |
| sympy_sum                | 170 ms                                                 | 190 ms: 1.12x slower                                   |
| djangocms                | 33.1 us                                                | 37.2 us: 1.12x slower                                  |
| sympy_str                | 299 ms                                                 | 337 ms: 1.13x slower                                   |
| sympy_expand             | 490 ms                                                 | 558 ms: 1.14x slower                                   |
| regex_v8                 | 22.9 ms                                                | 26.2 ms: 1.15x slower                                  |
| bench_thread_pool        | 833 us                                                 | 966 us: 1.16x slower                                   |
| flaskblogging            | 7.20 ms                                                | 8.42 ms: 1.17x slower                                  |
| sqlite_synth             | 2.58 us                                                | 3.02 us: 1.17x slower                                  |
| async_generators         | 375 ms                                                 | 442 ms: 1.18x slower                                   |
| dask                     | 365 ms                                                 | 432 ms: 1.18x slower                                   |
| dulwich_log              | 64.9 ms                                                | 77.0 ms: 1.19x slower                                  |
| sympy_integrate          | 21.4 ms                                                | 25.4 ms: 1.19x slower                                  |
| sqlalchemy_imperative    | 18.2 ms                                                | 21.9 ms: 1.20x slower                                  |
| sqlalchemy_declarative   | 141 ms                                                 | 170 ms: 1.21x slower                                   |
| comprehensions           | 23.6 us                                                | 28.5 us: 1.21x slower                                  |
| docutils                 | 2.69 sec                                               | 3.26 sec: 1.21x slower                                 |
| genshi_xml               | 54.1 ms                                                | 66.0 ms: 1.22x slower                                  |
| nqueens                  | 86.8 ms                                                | 107 ms: 1.23x slower                                   |
| gunicorn                 | 1.20 ms                                                | 1.48 ms: 1.24x slower                                  |
| xml_etree_generate       | 80.4 ms                                                | 100.0 ms: 1.24x slower                                 |
| sqlglot_optimize         | 55.2 ms                                                | 68.7 ms: 1.25x slower                                  |
| sqlglot_normalize        | 112 ms                                                 | 141 ms: 1.26x slower                                   |
| aiohttp                  | 1.12 ms                                                | 1.41 ms: 1.27x slower                                  |
| scimark_sparse_mat_mult  | 4.80 ms                                                | 6.10 ms: 1.27x slower                                  |
| fannkuch                 | 410 ms                                                 | 527 ms: 1.29x slower                                   |
| 2to3                     | 266 ms                                                 | 346 ms: 1.30x slower                                   |
| pycparser                | 1.20 sec                                               | 1.57 sec: 1.31x slower                                 |
| regex_compile            | 141 ms                                                 | 186 ms: 1.31x slower                                   |
| coroutines               | 26.1 ms                                                | 34.5 ms: 1.32x slower                                  |
| tomli_loads              | 2.31 sec                                               | 3.06 sec: 1.32x slower                                 |
| logging_simple           | 6.24 us                                                | 8.27 us: 1.33x slower                                  |
| scimark_fft              | 342 ms                                                 | 454 ms: 1.33x slower                                   |
| deepcopy_reduce          | 3.14 us                                                | 4.17 us: 1.33x slower                                  |
| logging_format           | 6.83 us                                                | 9.07 us: 1.33x slower                                  |
| deepcopy                 | 360 us                                                 | 481 us: 1.34x slower                                   |
| tornado_http             | 97.7 ms                                                | 131 ms: 1.34x slower                                   |
| async_tree_cpu_io_mixed  | 750 ms                                                 | 1.01 sec: 1.34x slower                                 |
| html5lib                 | 65.0 ms                                                | 88.1 ms: 1.35x slower                                  |
| async_tree_memoization   | 640 ms                                                 | 867 ms: 1.35x slower                                   |
| unpickle_pure_python     | 241 us                                                 | 327 us: 1.36x slower                                   |
| pprint_safe_repr         | 743 ms                                                 | 1.01 sec: 1.37x slower                                 |
| async_tree_io            | 1.31 sec                                               | 1.79 sec: 1.37x slower                                 |
| pprint_pformat           | 1.53 sec                                               | 2.10 sec: 1.37x slower                                 |
| async_tree_none          | 532 ms                                                 | 732 ms: 1.38x slower                                   |
| thrift                   | 772 us                                                 | 1.06 ms: 1.38x slower                                  |
| genshi_text              | 22.8 ms                                                | 31.7 ms: 1.39x slower                                  |
| django_template          | 33.8 ms                                                | 47.6 ms: 1.41x slower                                  |
| xml_etree_process        | 56.5 ms                                                | 79.8 ms: 1.41x slower                                  |
| chameleon                | 6.86 ms                                                | 9.84 ms: 1.43x slower                                  |
| sqlglot_transpile        | 1.75 ms                                                | 2.55 ms: 1.45x slower                                  |
| float                    | 78.9 ms                                                | 116 ms: 1.48x slower                                   |
| sqlglot_parse            | 1.43 ms                                                | 2.15 ms: 1.50x slower                                  |
| mako                     | 10.8 ms                                                | 16.3 ms: 1.50x slower                                  |
| pickle_pure_python       | 319 us                                                 | 482 us: 1.51x slower                                   |
| deepcopy_memo            | 38.9 us                                                | 58.8 us: 1.51x slower                                  |
| unpack_sequence          | 43.3 ns                                                | 65.7 ns: 1.52x slower                                  |
| hexiom                   | 6.74 ms                                                | 10.3 ms: 1.53x slower                                  |
| spectral_norm            | 105 ms                                                 | 163 ms: 1.55x slower                                   |
| scimark_lu               | 112 ms                                                 | 175 ms: 1.56x slower                                   |
| richards_super           | 61.2 ms                                                | 95.6 ms: 1.56x slower                                  |
| chaos                    | 71.4 ms                                                | 114 ms: 1.60x slower                                   |
| nbody                    | 91.6 ms                                                | 148 ms: 1.62x slower                                   |
| raytrace                 | 306 ms                                                 | 498 ms: 1.62x slower                                   |
| richards                 | 48.9 ms                                                | 79.4 ms: 1.63x slower                                  |
| crypto_pyaes             | 77.5 ms                                                | 127 ms: 1.64x slower                                   |
| scimark_monte_carlo      | 71.8 ms                                                | 118 ms: 1.64x slower                                   |
| python_startup           | 8.69 ms                                                | 14.3 ms: 1.65x slower                                  |
| go                       | 143 ms                                                 | 238 ms: 1.66x slower                                   |
| pyflate                  | 426 ms                                                 | 708 ms: 1.66x slower                                   |
| logging_silent           | 108 ns                                                 | 189 ns: 1.74x slower                                   |
| scimark_sor              | 121 ms                                                 | 214 ms: 1.77x slower                                   |
| deltablue                | 3.80 ms                                                | 7.81 ms: 2.05x slower                                  |
| Geometric mean           | (ref)                                                  | 1.26x slower                                           |

Benchmark hidden because not significant (2): bench_mp_pool, mypy2
Ignored benchmarks (4) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.23x
- 95% likely to have a slowdown of 1.22x
- 99% likely to have a slowdown of 1.20x
