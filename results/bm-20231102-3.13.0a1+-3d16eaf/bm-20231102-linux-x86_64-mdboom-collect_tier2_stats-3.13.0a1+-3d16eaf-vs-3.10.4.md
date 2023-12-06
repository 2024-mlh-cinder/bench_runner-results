
# Results vs. 3.10.4

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 3d16eaf
- commit date: 2023-11-02
- overall geometric mean: 1.27x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 282 ms: 1.23x faster                                                  |
| chameleon      | 9.84 ms                                                | 7.14 ms: 1.38x faster                                                 |
| docutils       | 3.26 sec                                               | 2.71 sec: 1.21x faster                                                |
| tornado_http   | 131 ms                                                 | 98.2 ms: 1.33x faster                                                 |
| Geometric mean | (ref)                                                  | 1.28x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 454 ms: 1.61x faster                                                  |
| async_tree_memoization  | 867 ms                                                 | 582 ms: 1.49x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.21 sec: 1.48x faster                                                |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 727 ms: 1.39x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.49x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 113 ms: 1.31x faster                                                  |
| float          | 116 ms                                                 | 97.0 ms: 1.20x faster                                                 |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                  | 1.15x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 158 ms: 1.18x faster                                                  |
| regex_v8       | 26.2 ms                                                | 24.9 ms: 1.06x faster                                                 |
| regex_dna      | 215 ms                                                 | 212 ms: 1.01x faster                                                  |
| regex_effbot   | 3.41 ms                                                | 3.44 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                  | 1.06x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 303 us: 1.59x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 237 us: 1.38x faster                                                  |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.34x faster                                                 |
| xml_etree_process    | 79.8 ms                                                | 59.9 ms: 1.33x faster                                                 |
| tomli_loads          | 3.06 sec                                               | 2.47 sec: 1.24x faster                                                |
| xml_etree_generate   | 100.0 ms                                               | 88.0 ms: 1.14x faster                                                 |
| json_loads           | 31.4 us                                                | 27.9 us: 1.13x faster                                                 |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 111 ms: 1.05x faster                                                  |
| unpickle_list        | 5.10 us                                                | 5.02 us: 1.02x faster                                                 |
| pickle_list          | 5.05 us                                                | 5.07 us: 1.00x slower                                                 |
| unpickle             | 14.9 us                                                | 15.0 us: 1.01x slower                                                 |
| pickle               | 10.7 us                                                | 11.6 us: 1.08x slower                                                 |
| pickle_dict          | 30.0 us                                                | 34.4 us: 1.15x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                 |
| python_startup_no_site | 5.87 ms                                                | 9.00 ms: 1.53x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 13.7 ms: 1.19x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 128 us: 4.37x faster                                                  |
| generators               | 78.9 ms                                                | 29.7 ms: 2.65x faster                                                 |
| asyncio_tcp              | 918 ms                                                 | 490 ms: 1.87x faster                                                  |
| logging_silent           | 189 ns                                                 | 107 ns: 1.76x faster                                                  |
| raytrace                 | 498 ms                                                 | 293 ms: 1.70x faster                                                  |
| scimark_sor              | 214 ms                                                 | 130 ms: 1.66x faster                                                  |
| richards_super           | 95.6 ms                                                | 57.7 ms: 1.66x faster                                                 |
| chaos                    | 114 ms                                                 | 69.2 ms: 1.65x faster                                                 |
| crypto_pyaes             | 127 ms                                                 | 77.0 ms: 1.65x faster                                                 |
| async_tree_none          | 732 ms                                                 | 454 ms: 1.61x faster                                                  |
| deltablue                | 7.81 ms                                                | 4.85 ms: 1.61x faster                                                 |
| pickle_pure_python       | 482 us                                                 | 303 us: 1.59x faster                                                  |
| scimark_monte_carlo      | 118 ms                                                 | 74.4 ms: 1.59x faster                                                 |
| sqlglot_parse            | 2.15 ms                                                | 1.36 ms: 1.58x faster                                                 |
| richards                 | 79.4 ms                                                | 51.7 ms: 1.54x faster                                                 |
| coroutines               | 34.5 ms                                                | 22.5 ms: 1.53x faster                                                 |
| sqlglot_transpile        | 2.55 ms                                                | 1.69 ms: 1.51x faster                                                 |
| async_tree_memoization   | 867 ms                                                 | 582 ms: 1.49x faster                                                  |
| go                       | 238 ms                                                 | 160 ms: 1.49x faster                                                  |
| async_tree_io            | 1.79 sec                                               | 1.21 sec: 1.48x faster                                                |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.46x faster                                                  |
| spectral_norm            | 163 ms                                                 | 114 ms: 1.44x faster                                                  |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                                |
| deepcopy_memo            | 58.8 us                                                | 41.6 us: 1.41x faster                                                 |
| pyflate                  | 708 ms                                                 | 506 ms: 1.40x faster                                                  |
| logging_format           | 9.07 us                                                | 6.49 us: 1.40x faster                                                 |
| logging_simple           | 8.27 us                                                | 5.95 us: 1.39x faster                                                 |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                 |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 727 ms: 1.39x faster                                                  |
| unpickle_pure_python     | 327 us                                                 | 237 us: 1.38x faster                                                  |
| chameleon                | 9.84 ms                                                | 7.14 ms: 1.38x faster                                                 |
| deepcopy                 | 481 us                                                 | 356 us: 1.35x faster                                                  |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.34x faster                                                 |
| deepcopy_reduce          | 4.17 us                                                | 3.13 us: 1.33x faster                                                 |
| xml_etree_process        | 79.8 ms                                                | 59.9 ms: 1.33x faster                                                 |
| tornado_http             | 131 ms                                                 | 98.2 ms: 1.33x faster                                                 |
| nbody                    | 148 ms                                                 | 113 ms: 1.31x faster                                                  |
| pycparser                | 1.57 sec                                               | 1.20 sec: 1.30x faster                                                |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 794 ms: 1.28x faster                                                  |
| pprint_pformat           | 2.10 sec                                               | 1.65 sec: 1.27x faster                                                |
| comprehensions           | 28.5 us                                                | 22.5 us: 1.27x faster                                                 |
| mypy2                    | 442 ms                                                 | 356 ms: 1.24x faster                                                  |
| tomli_loads              | 3.06 sec                                               | 2.47 sec: 1.24x faster                                                |
| fannkuch                 | 527 ms                                                 | 427 ms: 1.23x faster                                                  |
| sqlglot_optimize         | 68.7 ms                                                | 55.7 ms: 1.23x faster                                                 |
| sympy_sum                | 190 ms                                                 | 155 ms: 1.23x faster                                                  |
| 2to3                     | 346 ms                                                 | 282 ms: 1.23x faster                                                  |
| sympy_integrate          | 25.4 ms                                                | 21.0 ms: 1.21x faster                                                 |
| docutils                 | 3.26 sec                                               | 2.71 sec: 1.21x faster                                                |
| float                    | 116 ms                                                 | 97.0 ms: 1.20x faster                                                 |
| mako                     | 16.3 ms                                                | 13.7 ms: 1.19x faster                                                 |
| sympy_str                | 337 ms                                                 | 284 ms: 1.19x faster                                                  |
| regex_compile            | 186 ms                                                 | 158 ms: 1.18x faster                                                  |
| sympy_expand             | 558 ms                                                 | 479 ms: 1.17x faster                                                  |
| hexiom                   | 10.3 ms                                                | 8.94 ms: 1.15x faster                                                 |
| bench_thread_pool        | 966 us                                                 | 841 us: 1.15x faster                                                  |
| scimark_fft              | 454 ms                                                 | 395 ms: 1.15x faster                                                  |
| dulwich_log              | 77.0 ms                                                | 67.3 ms: 1.14x faster                                                 |
| xml_etree_generate       | 100.0 ms                                               | 88.0 ms: 1.14x faster                                                 |
| json_loads               | 31.4 us                                                | 27.9 us: 1.13x faster                                                 |
| json                     | 5.67 ms                                                | 5.12 ms: 1.11x faster                                                 |
| nqueens                  | 107 ms                                                 | 96.5 ms: 1.10x faster                                                 |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.10x faster                                                 |
| unpack_sequence          | 65.7 ns                                                | 59.9 ns: 1.10x faster                                                 |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.60 ms: 1.09x faster                                                 |
| mdp                      | 2.93 sec                                               | 2.71 sec: 1.08x faster                                                |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                  |
| sqlite_synth             | 3.02 us                                                | 2.85 us: 1.06x faster                                                 |
| regex_v8                 | 26.2 ms                                                | 24.9 ms: 1.06x faster                                                 |
| xml_etree_iterparse      | 116 ms                                                 | 111 ms: 1.05x faster                                                  |
| meteor_contest           | 119 ms                                                 | 114 ms: 1.04x faster                                                  |
| pathlib                  | 20.3 ms                                                | 19.5 ms: 1.04x faster                                                 |
| unpickle_list            | 5.10 us                                                | 5.02 us: 1.02x faster                                                 |
| regex_dna                | 215 ms                                                 | 212 ms: 1.01x faster                                                  |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                  |
| pickle_list              | 5.05 us                                                | 5.07 us: 1.00x slower                                                 |
| regex_effbot             | 3.41 ms                                                | 3.44 ms: 1.01x slower                                                 |
| unpickle                 | 14.9 us                                                | 15.0 us: 1.01x slower                                                 |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                                  |
| async_generators         | 442 ms                                                 | 456 ms: 1.03x slower                                                  |
| pickle                   | 10.7 us                                                | 11.6 us: 1.08x slower                                                 |
| gc_traversal             | 3.43 ms                                                | 3.91 ms: 1.14x slower                                                 |
| pickle_dict              | 30.0 us                                                | 34.4 us: 1.15x slower                                                 |
| coverage                 | 82.0 ms                                                | 94.8 ms: 1.16x slower                                                 |
| telco                    | 7.01 ms                                                | 8.37 ms: 1.19x slower                                                 |
| python_startup_no_site   | 5.87 ms                                                | 9.00 ms: 1.53x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231102-3.13.0a1+-3d16eaf/bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-3d16eaf.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.22x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.19x
