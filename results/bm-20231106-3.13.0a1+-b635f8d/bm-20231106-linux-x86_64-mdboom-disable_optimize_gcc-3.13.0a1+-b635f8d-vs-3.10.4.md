
# Results vs. 3.10.4

- fork: mdboom
- ref: disable_optimize_gcc
- machine: linux-x86_64
- commit hash: b635f8d
- commit date: 2023-11-06
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 289 ms: 1.19x faster                                                   |
| chameleon      | 9.84 ms                                                | 8.49 ms: 1.16x faster                                                  |
| docutils       | 3.26 sec                                               | 2.72 sec: 1.20x faster                                                 |
| tornado_http   | 131 ms                                                 | 98.9 ms: 1.32x faster                                                  |
| Geometric mean | (ref)                                                  | 1.22x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 464 ms: 1.58x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 597 ms: 1.45x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.24 sec: 1.44x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 742 ms: 1.36x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.45x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 116 ms                                                 | 89.5 ms: 1.30x faster                                                  |
| nbody          | 148 ms                                                 | 125 ms: 1.18x faster                                                   |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| Geometric mean | (ref)                                                  | 1.16x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 150 ms: 1.24x faster                                                   |
| regex_v8       | 26.2 ms                                                | 24.5 ms: 1.07x faster                                                  |
| regex_dna      | 215 ms                                                 | 217 ms: 1.01x slower                                                   |
| regex_effbot   | 3.41 ms                                                | 3.50 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                  | 1.06x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 357 us: 1.35x faster                                                   |
| json_dumps           | 14.3 ms                                                | 10.9 ms: 1.31x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 258 us: 1.27x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.46 sec: 1.24x faster                                                 |
| xml_etree_process    | 79.8 ms                                                | 68.9 ms: 1.16x faster                                                  |
| json_loads           | 31.4 us                                                | 28.0 us: 1.12x faster                                                  |
| xml_etree_parse      | 171 ms                                                 | 163 ms: 1.05x faster                                                   |
| xml_etree_generate   | 100.0 ms                                               | 96.0 ms: 1.04x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 113 ms: 1.03x faster                                                   |
| pickle_list          | 5.05 us                                                | 4.92 us: 1.03x faster                                                  |
| unpickle             | 14.9 us                                                | 14.6 us: 1.02x faster                                                  |
| unpickle_list        | 5.10 us                                                | 5.31 us: 1.04x slower                                                  |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                                  |
| pickle_dict          | 30.0 us                                                | 33.5 us: 1.12x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.09x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 9.06 ms: 1.54x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 13.4 ms: 1.21x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 130 us: 4.31x faster                                                   |
| generators               | 78.9 ms                                                | 37.8 ms: 2.08x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 490 ms: 1.87x faster                                                   |
| deltablue                | 7.81 ms                                                | 4.32 ms: 1.81x faster                                                  |
| crypto_pyaes             | 127 ms                                                 | 78.2 ms: 1.62x faster                                                  |
| chaos                    | 114 ms                                                 | 72.2 ms: 1.58x faster                                                  |
| async_tree_none          | 732 ms                                                 | 464 ms: 1.58x faster                                                   |
| raytrace                 | 498 ms                                                 | 324 ms: 1.54x faster                                                   |
| scimark_monte_carlo      | 118 ms                                                 | 77.8 ms: 1.52x faster                                                  |
| logging_silent           | 189 ns                                                 | 126 ns: 1.50x faster                                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.46 ms: 1.47x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 597 ms: 1.45x faster                                                   |
| richards_super           | 95.6 ms                                                | 66.0 ms: 1.45x faster                                                  |
| go                       | 238 ms                                                 | 165 ms: 1.44x faster                                                   |
| async_tree_io            | 1.79 sec                                               | 1.24 sec: 1.44x faster                                                 |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                                 |
| comprehensions           | 28.5 us                                                | 19.9 us: 1.43x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.79 ms: 1.42x faster                                                  |
| scimark_lu               | 175 ms                                                 | 127 ms: 1.38x faster                                                   |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 742 ms: 1.36x faster                                                   |
| richards                 | 79.4 ms                                                | 58.8 ms: 1.35x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 357 us: 1.35x faster                                                   |
| hexiom                   | 10.3 ms                                                | 7.66 ms: 1.34x faster                                                  |
| pyflate                  | 708 ms                                                 | 528 ms: 1.34x faster                                                   |
| spectral_norm            | 163 ms                                                 | 123 ms: 1.32x faster                                                   |
| tornado_http             | 131 ms                                                 | 98.9 ms: 1.32x faster                                                  |
| json_dumps               | 14.3 ms                                                | 10.9 ms: 1.31x faster                                                  |
| float                    | 116 ms                                                 | 89.5 ms: 1.30x faster                                                  |
| pycparser                | 1.57 sec                                               | 1.22 sec: 1.29x faster                                                 |
| scimark_sor              | 214 ms                                                 | 169 ms: 1.27x faster                                                   |
| unpickle_pure_python     | 327 us                                                 | 258 us: 1.27x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 47.0 us: 1.25x faster                                                  |
| mypy2                    | 442 ms                                                 | 354 ms: 1.25x faster                                                   |
| tomli_loads              | 3.06 sec                                               | 2.46 sec: 1.24x faster                                                 |
| sympy_sum                | 190 ms                                                 | 154 ms: 1.24x faster                                                   |
| regex_compile            | 186 ms                                                 | 150 ms: 1.24x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 20.6 ms: 1.23x faster                                                  |
| mako                     | 16.3 ms                                                | 13.4 ms: 1.21x faster                                                  |
| coroutines               | 34.5 ms                                                | 28.5 ms: 1.21x faster                                                  |
| docutils                 | 3.26 sec                                               | 2.72 sec: 1.20x faster                                                 |
| 2to3                     | 346 ms                                                 | 289 ms: 1.19x faster                                                   |
| nbody                    | 148 ms                                                 | 125 ms: 1.18x faster                                                   |
| pprint_pformat           | 2.10 sec                                               | 1.78 sec: 1.18x faster                                                 |
| sqlglot_normalize        | 141 ms                                                 | 121 ms: 1.17x faster                                                   |
| sympy_str                | 337 ms                                                 | 290 ms: 1.16x faster                                                   |
| chameleon                | 9.84 ms                                                | 8.49 ms: 1.16x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 68.9 ms: 1.16x faster                                                  |
| sqlglot_optimize         | 68.7 ms                                                | 59.4 ms: 1.16x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 878 ms: 1.16x faster                                                   |
| logging_format           | 9.07 us                                                | 7.92 us: 1.15x faster                                                  |
| deepcopy                 | 481 us                                                 | 420 us: 1.14x faster                                                   |
| sympy_expand             | 558 ms                                                 | 489 ms: 1.14x faster                                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.66 us: 1.14x faster                                                  |
| logging_simple           | 8.27 us                                                | 7.30 us: 1.13x faster                                                  |
| dulwich_log              | 77.0 ms                                                | 68.0 ms: 1.13x faster                                                  |
| json_loads               | 31.4 us                                                | 28.0 us: 1.12x faster                                                  |
| nqueens                  | 107 ms                                                 | 95.1 ms: 1.12x faster                                                  |
| fannkuch                 | 527 ms                                                 | 474 ms: 1.11x faster                                                   |
| bench_thread_pool        | 966 us                                                 | 878 us: 1.10x faster                                                   |
| scimark_fft              | 454 ms                                                 | 414 ms: 1.10x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.09x faster                                                  |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.60 ms: 1.09x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.72 sec: 1.08x faster                                                 |
| json                     | 5.67 ms                                                | 5.27 ms: 1.08x faster                                                  |
| regex_v8                 | 26.2 ms                                                | 24.5 ms: 1.07x faster                                                  |
| sqlite_synth             | 3.02 us                                                | 2.86 us: 1.06x faster                                                  |
| meteor_contest           | 119 ms                                                 | 114 ms: 1.05x faster                                                   |
| xml_etree_parse          | 171 ms                                                 | 163 ms: 1.05x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 96.0 ms: 1.04x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 113 ms: 1.03x faster                                                   |
| pickle_list              | 5.05 us                                                | 4.92 us: 1.03x faster                                                  |
| unpickle                 | 14.9 us                                                | 14.6 us: 1.02x faster                                                  |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                   |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| regex_dna                | 215 ms                                                 | 217 ms: 1.01x slower                                                   |
| regex_effbot             | 3.41 ms                                                | 3.50 ms: 1.03x slower                                                  |
| unpickle_list            | 5.10 us                                                | 5.31 us: 1.04x slower                                                  |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                                  |
| async_generators         | 442 ms                                                 | 473 ms: 1.07x slower                                                   |
| pickle_dict              | 30.0 us                                                | 33.5 us: 1.12x slower                                                  |
| unpack_sequence          | 65.7 ns                                                | 75.8 ns: 1.15x slower                                                  |
| coverage                 | 82.0 ms                                                | 101 ms: 1.23x slower                                                   |
| telco                    | 7.01 ms                                                | 8.64 ms: 1.23x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 4.30 ms: 1.25x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 9.06 ms: 1.54x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.21x faster                                                           |

Benchmark hidden because not significant (2): pathlib, bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231106-3.13.0a1+-b635f8d/bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
