
# Results vs. 3.11.0

- fork: mdboom
- ref: disable_optimize_gcc
- machine: linux-x86_64
- commit hash: b635f8d
- commit date: 2023-11-06
- overall geometric mean: 1.04x slower \*
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 289 ms: 1.09x slower                                                   |
| chameleon      | 6.86 ms                                                | 8.49 ms: 1.24x slower                                                  |
| docutils       | 2.69 sec                                               | 2.72 sec: 1.01x slower                                                 |
| tornado_http   | 97.7 ms                                                | 98.9 ms: 1.01x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x slower                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 532 ms                                                 | 464 ms: 1.15x faster                                                   |
| async_tree_memoization  | 640 ms                                                 | 597 ms: 1.07x faster                                                   |
| async_tree_io           | 1.31 sec                                               | 1.24 sec: 1.05x faster                                                 |
| async_tree_none_tg      | 490 ms                                                 | 480 ms: 1.02x faster                                                   |
| async_tree_io_tg        | 1.30 sec                                               | 1.28 sec: 1.02x faster                                                 |
| async_tree_cpu_io_mixed | 750 ms                                                 | 742 ms: 1.01x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.04x faster                                                           |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| float          | 78.9 ms                                                | 89.5 ms: 1.13x slower                                                  |
| nbody          | 91.6 ms                                                | 125 ms: 1.37x slower                                                   |
| Geometric mean | (ref)                                                  | 1.15x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.50 ms: 1.01x slower                                                  |
| regex_compile  | 141 ms                                                 | 150 ms: 1.06x slower                                                   |
| regex_dna      | 204 ms                                                 | 217 ms: 1.06x slower                                                   |
| regex_v8       | 22.9 ms                                                | 24.5 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 10.9 ms: 1.23x faster                                                  |
| json_loads           | 29.4 us                                                | 28.0 us: 1.05x faster                                                  |
| pickle_dict          | 34.8 us                                                | 33.5 us: 1.04x faster                                                  |
| pickle               | 11.1 us                                                | 11.2 us: 1.01x slower                                                  |
| unpickle_list        | 5.22 us                                                | 5.31 us: 1.02x slower                                                  |
| xml_etree_iterparse  | 109 ms                                                 | 113 ms: 1.04x slower                                                   |
| unpickle             | 13.9 us                                                | 14.6 us: 1.06x slower                                                  |
| pickle_list          | 4.65 us                                                | 4.92 us: 1.06x slower                                                  |
| tomli_loads          | 2.31 sec                                               | 2.46 sec: 1.06x slower                                                 |
| unpickle_pure_python | 241 us                                                 | 258 us: 1.07x slower                                                   |
| pickle_pure_python   | 319 us                                                 | 357 us: 1.12x slower                                                   |
| xml_etree_generate   | 80.4 ms                                                | 96.0 ms: 1.19x slower                                                  |
| xml_etree_process    | 56.5 ms                                                | 68.9 ms: 1.22x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                  |
| python_startup_no_site | 6.09 ms                                                | 9.06 ms: 1.49x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.34x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.8 ms                                                | 13.4 ms: 1.24x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1+-b635f8d |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 521 us                                                 | 130 us: 4.01x faster                                                   |
| generators               | 76.5 ms                                                | 37.8 ms: 2.02x faster                                                  |
| asyncio_tcp              | 887 ms                                                 | 490 ms: 1.81x faster                                                   |
| asyncio_tcp_ssl          | 3.13 sec                                               | 1.80 sec: 1.74x faster                                                 |
| json_dumps               | 13.5 ms                                                | 10.9 ms: 1.23x faster                                                  |
| mypy2                    | 427 ms                                                 | 354 ms: 1.21x faster                                                   |
| comprehensions           | 23.6 us                                                | 19.9 us: 1.18x faster                                                  |
| async_tree_none          | 532 ms                                                 | 464 ms: 1.15x faster                                                   |
| sympy_sum                | 170 ms                                                 | 154 ms: 1.11x faster                                                   |
| async_tree_memoization   | 640 ms                                                 | 597 ms: 1.07x faster                                                   |
| async_tree_io            | 1.31 sec                                               | 1.24 sec: 1.05x faster                                                 |
| json_loads               | 29.4 us                                                | 28.0 us: 1.05x faster                                                  |
| pickle_dict              | 34.8 us                                                | 33.5 us: 1.04x faster                                                  |
| sympy_integrate          | 21.4 ms                                                | 20.6 ms: 1.04x faster                                                  |
| sympy_str                | 299 ms                                                 | 290 ms: 1.03x faster                                                   |
| mdp                      | 2.79 sec                                               | 2.72 sec: 1.03x faster                                                 |
| async_tree_none_tg       | 490 ms                                                 | 480 ms: 1.02x faster                                                   |
| async_tree_io_tg         | 1.30 sec                                               | 1.28 sec: 1.02x faster                                                 |
| async_tree_cpu_io_mixed  | 750 ms                                                 | 742 ms: 1.01x faster                                                   |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| asyncio_websockets       | 556 ms                                                 | 552 ms: 1.01x faster                                                   |
| create_gc_cycles         | 1.48 ms                                                | 1.47 ms: 1.00x faster                                                  |
| crypto_pyaes             | 77.5 ms                                                | 78.2 ms: 1.01x slower                                                  |
| pickle                   | 11.1 us                                                | 11.2 us: 1.01x slower                                                  |
| docutils                 | 2.69 sec                                               | 2.72 sec: 1.01x slower                                                 |
| chaos                    | 71.4 ms                                                | 72.2 ms: 1.01x slower                                                  |
| tornado_http             | 97.7 ms                                                | 98.9 ms: 1.01x slower                                                  |
| regex_effbot             | 3.45 ms                                                | 3.50 ms: 1.01x slower                                                  |
| sqlglot_parse            | 1.43 ms                                                | 1.46 ms: 1.02x slower                                                  |
| pycparser                | 1.20 sec                                               | 1.22 sec: 1.02x slower                                                 |
| unpickle_list            | 5.22 us                                                | 5.31 us: 1.02x slower                                                  |
| sqlglot_transpile        | 1.75 ms                                                | 1.79 ms: 1.02x slower                                                  |
| xml_etree_iterparse      | 109 ms                                                 | 113 ms: 1.04x slower                                                   |
| meteor_contest           | 109 ms                                                 | 114 ms: 1.04x slower                                                   |
| dulwich_log              | 64.9 ms                                                | 68.0 ms: 1.05x slower                                                  |
| bench_thread_pool        | 833 us                                                 | 878 us: 1.05x slower                                                   |
| unpickle                 | 13.9 us                                                | 14.6 us: 1.06x slower                                                  |
| raytrace                 | 306 ms                                                 | 324 ms: 1.06x slower                                                   |
| pickle_list              | 4.65 us                                                | 4.92 us: 1.06x slower                                                  |
| regex_compile            | 141 ms                                                 | 150 ms: 1.06x slower                                                   |
| regex_dna                | 204 ms                                                 | 217 ms: 1.06x slower                                                   |
| tomli_loads              | 2.31 sec                                               | 2.46 sec: 1.06x slower                                                 |
| regex_v8                 | 22.9 ms                                                | 24.5 ms: 1.07x slower                                                  |
| unpickle_pure_python     | 241 us                                                 | 258 us: 1.07x slower                                                   |
| sqlglot_normalize        | 112 ms                                                 | 121 ms: 1.07x slower                                                   |
| sqlglot_optimize         | 55.2 ms                                                | 59.4 ms: 1.08x slower                                                  |
| richards_super           | 61.2 ms                                                | 66.0 ms: 1.08x slower                                                  |
| scimark_monte_carlo      | 71.8 ms                                                | 77.8 ms: 1.08x slower                                                  |
| 2to3                     | 266 ms                                                 | 289 ms: 1.09x slower                                                   |
| coroutines               | 26.1 ms                                                | 28.5 ms: 1.09x slower                                                  |
| nqueens                  | 86.8 ms                                                | 95.1 ms: 1.10x slower                                                  |
| pathlib                  | 18.5 ms                                                | 20.2 ms: 1.10x slower                                                  |
| gc_traversal             | 3.90 ms                                                | 4.30 ms: 1.10x slower                                                  |
| sqlite_synth             | 2.58 us                                                | 2.86 us: 1.11x slower                                                  |
| pickle_pure_python       | 319 us                                                 | 357 us: 1.12x slower                                                   |
| scimark_lu               | 112 ms                                                 | 127 ms: 1.13x slower                                                   |
| float                    | 78.9 ms                                                | 89.5 ms: 1.13x slower                                                  |
| deltablue                | 3.80 ms                                                | 4.32 ms: 1.14x slower                                                  |
| hexiom                   | 6.74 ms                                                | 7.66 ms: 1.14x slower                                                  |
| go                       | 143 ms                                                 | 165 ms: 1.15x slower                                                   |
| fannkuch                 | 410 ms                                                 | 474 ms: 1.16x slower                                                   |
| logging_silent           | 108 ns                                                 | 126 ns: 1.16x slower                                                   |
| logging_format           | 6.83 us                                                | 7.92 us: 1.16x slower                                                  |
| scimark_sparse_mat_mult  | 4.80 ms                                                | 5.60 ms: 1.17x slower                                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.66 us: 1.17x slower                                                  |
| deepcopy                 | 360 us                                                 | 420 us: 1.17x slower                                                   |
| pprint_pformat           | 1.53 sec                                               | 1.78 sec: 1.17x slower                                                 |
| logging_simple           | 6.24 us                                                | 7.30 us: 1.17x slower                                                  |
| spectral_norm            | 105 ms                                                 | 123 ms: 1.17x slower                                                   |
| pprint_safe_repr         | 743 ms                                                 | 878 ms: 1.18x slower                                                   |
| xml_etree_generate       | 80.4 ms                                                | 96.0 ms: 1.19x slower                                                  |
| python_startup           | 8.69 ms                                                | 10.4 ms: 1.20x slower                                                  |
| richards                 | 48.9 ms                                                | 58.8 ms: 1.20x slower                                                  |
| deepcopy_memo            | 38.9 us                                                | 47.0 us: 1.21x slower                                                  |
| scimark_fft              | 342 ms                                                 | 414 ms: 1.21x slower                                                   |
| xml_etree_process        | 56.5 ms                                                | 68.9 ms: 1.22x slower                                                  |
| chameleon                | 6.86 ms                                                | 8.49 ms: 1.24x slower                                                  |
| mako                     | 10.8 ms                                                | 13.4 ms: 1.24x slower                                                  |
| coverage                 | 81.2 ms                                                | 101 ms: 1.24x slower                                                   |
| pyflate                  | 426 ms                                                 | 528 ms: 1.24x slower                                                   |
| async_generators         | 375 ms                                                 | 473 ms: 1.26x slower                                                   |
| telco                    | 6.72 ms                                                | 8.64 ms: 1.29x slower                                                  |
| nbody                    | 91.6 ms                                                | 125 ms: 1.37x slower                                                   |
| scimark_sor              | 121 ms                                                 | 169 ms: 1.39x slower                                                   |
| python_startup_no_site   | 6.09 ms                                                | 9.06 ms: 1.49x slower                                                  |
| unpack_sequence          | 43.3 ns                                                | 75.8 ns: 1.75x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                           |

Benchmark hidden because not significant (6): async_tree_memoization_tg, sympy_expand, bench_mp_pool, xml_etree_parse, json, async_tree_cpu_io_mixed_tg
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
