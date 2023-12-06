
# Results vs. 3.10.4

- fork: python
- ref: v3.11.0
- machine: linux-x86_64
- commit hash: deaf509
- commit date: 2022-10-24
- overall geometric mean: 1.26x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 266 ms: 1.30x faster                                   |
| chameleon      | 9.84 ms                                                | 6.86 ms: 1.43x faster                                  |
| docutils       | 3.26 sec                                               | 2.69 sec: 1.21x faster                                 |
| html5lib       | 88.1 ms                                                | 65.0 ms: 1.35x faster                                  |
| tornado_http   | 131 ms                                                 | 97.7 ms: 1.34x faster                                  |
| Geometric mean | (ref)                                                  | 1.33x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 532 ms: 1.38x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.31 sec: 1.37x faster                                 |
| async_tree_memoization  | 867 ms                                                 | 640 ms: 1.35x faster                                   |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 750 ms: 1.34x faster                                   |
| Geometric mean          | (ref)                                                  | 1.36x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 148 ms                                                 | 91.6 ms: 1.62x faster                                  |
| float          | 116 ms                                                 | 78.9 ms: 1.48x faster                                  |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.34x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 141 ms: 1.31x faster                                   |
| regex_v8       | 26.2 ms                                                | 22.9 ms: 1.15x faster                                  |
| regex_dna      | 215 ms                                                 | 204 ms: 1.05x faster                                   |
| regex_effbot   | 3.41 ms                                                | 3.45 ms: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.12x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 319 us: 1.51x faster                                   |
| xml_etree_process    | 79.8 ms                                                | 56.5 ms: 1.41x faster                                  |
| unpickle_pure_python | 327 us                                                 | 241 us: 1.36x faster                                   |
| tomli_loads          | 3.06 sec                                               | 2.31 sec: 1.32x faster                                 |
| xml_etree_generate   | 100.0 ms                                               | 80.4 ms: 1.24x faster                                  |
| pickle_list          | 5.05 us                                                | 4.65 us: 1.09x faster                                  |
| unpickle             | 14.9 us                                                | 13.9 us: 1.07x faster                                  |
| xml_etree_iterparse  | 116 ms                                                 | 109 ms: 1.07x faster                                   |
| json_loads           | 31.4 us                                                | 29.4 us: 1.07x faster                                  |
| json_dumps           | 14.3 ms                                                | 13.5 ms: 1.06x faster                                  |
| xml_etree_parse      | 171 ms                                                 | 163 ms: 1.05x faster                                   |
| unpickle_list        | 5.10 us                                                | 5.22 us: 1.02x slower                                  |
| pickle               | 10.7 us                                                | 11.1 us: 1.04x slower                                  |
| pickle_dict          | 30.0 us                                                | 34.8 us: 1.16x slower                                  |
| Geometric mean       | (ref)                                                  | 1.13x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.69 ms: 1.65x faster                                  |
| python_startup_no_site | 5.87 ms                                                | 6.09 ms: 1.04x slower                                  |
| Geometric mean         | (ref)                                                  | 1.26x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 16.3 ms                                                | 10.8 ms: 1.50x faster                                  |
| django_template | 47.6 ms                                                | 33.8 ms: 1.41x faster                                  |
| genshi_text     | 31.7 ms                                                | 22.8 ms: 1.39x faster                                  |
| genshi_xml      | 66.0 ms                                                | 54.1 ms: 1.22x faster                                  |
| Geometric mean  | (ref)                                                  | 1.38x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| deltablue                | 7.81 ms                                                | 3.80 ms: 2.05x faster                                  |
| scimark_sor              | 214 ms                                                 | 121 ms: 1.77x faster                                   |
| logging_silent           | 189 ns                                                 | 108 ns: 1.74x faster                                   |
| pyflate                  | 708 ms                                                 | 426 ms: 1.66x faster                                   |
| go                       | 238 ms                                                 | 143 ms: 1.66x faster                                   |
| python_startup           | 14.3 ms                                                | 8.69 ms: 1.65x faster                                  |
| scimark_monte_carlo      | 118 ms                                                 | 71.8 ms: 1.64x faster                                  |
| crypto_pyaes             | 127 ms                                                 | 77.5 ms: 1.64x faster                                  |
| richards                 | 79.4 ms                                                | 48.9 ms: 1.63x faster                                  |
| raytrace                 | 498 ms                                                 | 306 ms: 1.62x faster                                   |
| nbody                    | 148 ms                                                 | 91.6 ms: 1.62x faster                                  |
| chaos                    | 114 ms                                                 | 71.4 ms: 1.60x faster                                  |
| richards_super           | 95.6 ms                                                | 61.2 ms: 1.56x faster                                  |
| scimark_lu               | 175 ms                                                 | 112 ms: 1.56x faster                                   |
| spectral_norm            | 163 ms                                                 | 105 ms: 1.55x faster                                   |
| hexiom                   | 10.3 ms                                                | 6.74 ms: 1.53x faster                                  |
| unpack_sequence          | 65.7 ns                                                | 43.3 ns: 1.52x faster                                  |
| deepcopy_memo            | 58.8 us                                                | 38.9 us: 1.51x faster                                  |
| pickle_pure_python       | 482 us                                                 | 319 us: 1.51x faster                                   |
| mako                     | 16.3 ms                                                | 10.8 ms: 1.50x faster                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.43 ms: 1.50x faster                                  |
| float                    | 116 ms                                                 | 78.9 ms: 1.48x faster                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.75 ms: 1.45x faster                                  |
| chameleon                | 9.84 ms                                                | 6.86 ms: 1.43x faster                                  |
| xml_etree_process        | 79.8 ms                                                | 56.5 ms: 1.41x faster                                  |
| django_template          | 47.6 ms                                                | 33.8 ms: 1.41x faster                                  |
| genshi_text              | 31.7 ms                                                | 22.8 ms: 1.39x faster                                  |
| thrift                   | 1.06 ms                                                | 772 us: 1.38x faster                                   |
| async_tree_none          | 732 ms                                                 | 532 ms: 1.38x faster                                   |
| pprint_pformat           | 2.10 sec                                               | 1.53 sec: 1.37x faster                                 |
| async_tree_io            | 1.79 sec                                               | 1.31 sec: 1.37x faster                                 |
| pprint_safe_repr         | 1.01 sec                                               | 743 ms: 1.37x faster                                   |
| unpickle_pure_python     | 327 us                                                 | 241 us: 1.36x faster                                   |
| async_tree_memoization   | 867 ms                                                 | 640 ms: 1.35x faster                                   |
| html5lib                 | 88.1 ms                                                | 65.0 ms: 1.35x faster                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 750 ms: 1.34x faster                                   |
| tornado_http             | 131 ms                                                 | 97.7 ms: 1.34x faster                                  |
| deepcopy                 | 481 us                                                 | 360 us: 1.34x faster                                   |
| logging_format           | 9.07 us                                                | 6.83 us: 1.33x faster                                  |
| deepcopy_reduce          | 4.17 us                                                | 3.14 us: 1.33x faster                                  |
| scimark_fft              | 454 ms                                                 | 342 ms: 1.33x faster                                   |
| logging_simple           | 8.27 us                                                | 6.24 us: 1.33x faster                                  |
| tomli_loads              | 3.06 sec                                               | 2.31 sec: 1.32x faster                                 |
| coroutines               | 34.5 ms                                                | 26.1 ms: 1.32x faster                                  |
| regex_compile            | 186 ms                                                 | 141 ms: 1.31x faster                                   |
| pycparser                | 1.57 sec                                               | 1.20 sec: 1.31x faster                                 |
| 2to3                     | 346 ms                                                 | 266 ms: 1.30x faster                                   |
| fannkuch                 | 527 ms                                                 | 410 ms: 1.29x faster                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.80 ms: 1.27x faster                                  |
| aiohttp                  | 1.41 ms                                                | 1.12 ms: 1.27x faster                                  |
| sqlglot_normalize        | 141 ms                                                 | 112 ms: 1.26x faster                                   |
| sqlglot_optimize         | 68.7 ms                                                | 55.2 ms: 1.25x faster                                  |
| xml_etree_generate       | 100.0 ms                                               | 80.4 ms: 1.24x faster                                  |
| gunicorn                 | 1.48 ms                                                | 1.20 ms: 1.24x faster                                  |
| nqueens                  | 107 ms                                                 | 86.8 ms: 1.23x faster                                  |
| genshi_xml               | 66.0 ms                                                | 54.1 ms: 1.22x faster                                  |
| docutils                 | 3.26 sec                                               | 2.69 sec: 1.21x faster                                 |
| comprehensions           | 28.5 us                                                | 23.6 us: 1.21x faster                                  |
| sqlalchemy_declarative   | 170 ms                                                 | 141 ms: 1.21x faster                                   |
| sqlalchemy_imperative    | 21.9 ms                                                | 18.2 ms: 1.20x faster                                  |
| sympy_integrate          | 25.4 ms                                                | 21.4 ms: 1.19x faster                                  |
| dulwich_log              | 77.0 ms                                                | 64.9 ms: 1.19x faster                                  |
| dask                     | 432 ms                                                 | 365 ms: 1.18x faster                                   |
| async_generators         | 442 ms                                                 | 375 ms: 1.18x faster                                   |
| sqlite_synth             | 3.02 us                                                | 2.58 us: 1.17x faster                                  |
| flaskblogging            | 8.42 ms                                                | 7.20 ms: 1.17x faster                                  |
| bench_thread_pool        | 966 us                                                 | 833 us: 1.16x faster                                   |
| regex_v8                 | 26.2 ms                                                | 22.9 ms: 1.15x faster                                  |
| sympy_expand             | 558 ms                                                 | 490 ms: 1.14x faster                                   |
| sympy_str                | 337 ms                                                 | 299 ms: 1.13x faster                                   |
| djangocms                | 37.2 us                                                | 33.1 us: 1.12x faster                                  |
| sympy_sum                | 190 ms                                                 | 170 ms: 1.12x faster                                   |
| pylint                   | 534 ms                                                 | 478 ms: 1.12x faster                                   |
| pathlib                  | 20.3 ms                                                | 18.5 ms: 1.10x faster                                  |
| meteor_contest           | 119 ms                                                 | 109 ms: 1.09x faster                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.09x faster                                  |
| pickle_list              | 5.05 us                                                | 4.65 us: 1.09x faster                                  |
| json                     | 5.67 ms                                                | 5.24 ms: 1.08x faster                                  |
| typing_runtime_protocols | 560 us                                                 | 521 us: 1.07x faster                                   |
| unpickle                 | 14.9 us                                                | 13.9 us: 1.07x faster                                  |
| xml_etree_iterparse      | 116 ms                                                 | 109 ms: 1.07x faster                                   |
| json_loads               | 31.4 us                                                | 29.4 us: 1.07x faster                                  |
| json_dumps               | 14.3 ms                                                | 13.5 ms: 1.06x faster                                  |
| regex_dna                | 215 ms                                                 | 204 ms: 1.05x faster                                   |
| mdp                      | 2.93 sec                                               | 2.79 sec: 1.05x faster                                 |
| xml_etree_parse          | 171 ms                                                 | 163 ms: 1.05x faster                                   |
| telco                    | 7.01 ms                                                | 6.72 ms: 1.04x faster                                  |
| asyncio_tcp              | 918 ms                                                 | 887 ms: 1.03x faster                                   |
| generators               | 78.9 ms                                                | 76.5 ms: 1.03x faster                                  |
| coverage                 | 82.0 ms                                                | 81.2 ms: 1.01x faster                                  |
| asyncio_websockets       | 558 ms                                                 | 556 ms: 1.00x faster                                   |
| pidigits                 | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| regex_effbot             | 3.41 ms                                                | 3.45 ms: 1.01x slower                                  |
| unpickle_list            | 5.10 us                                                | 5.22 us: 1.02x slower                                  |
| python_startup_no_site   | 5.87 ms                                                | 6.09 ms: 1.04x slower                                  |
| pickle                   | 10.7 us                                                | 11.1 us: 1.04x slower                                  |
| gc_traversal             | 3.43 ms                                                | 3.90 ms: 1.14x slower                                  |
| pickle_dict              | 30.0 us                                                | 34.8 us: 1.16x slower                                  |
| asyncio_tcp_ssl          | 2.58 sec                                               | 3.13 sec: 1.21x slower                                 |
| Geometric mean           | (ref)                                                  | 1.26x faster                                           |

Benchmark hidden because not significant (2): mypy2, bench_mp_pool
Ignored benchmarks (4) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.20x
