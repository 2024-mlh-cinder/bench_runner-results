
# Results vs. 3.10.4

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 8794817
- commit date: 2023-11-02
- overall geometric mean: 1.28x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 279 ms: 1.24x faster                                                  |
| chameleon      | 9.84 ms                                                | 7.09 ms: 1.39x faster                                                 |
| docutils       | 3.26 sec                                               | 2.70 sec: 1.21x faster                                                |
| tornado_http   | 131 ms                                                 | 98.4 ms: 1.33x faster                                                 |
| Geometric mean | (ref)                                                  | 1.29x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 452 ms: 1.62x faster                                                  |
| async_tree_memoization  | 867 ms                                                 | 576 ms: 1.50x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.21 sec: 1.48x faster                                                |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 730 ms: 1.38x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.49x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 111 ms: 1.34x faster                                                  |
| float          | 116 ms                                                 | 94.7 ms: 1.23x faster                                                 |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                  | 1.17x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 156 ms: 1.19x faster                                                  |
| regex_v8       | 26.2 ms                                                | 25.9 ms: 1.01x faster                                                 |
| regex_dna      | 215 ms                                                 | 218 ms: 1.02x slower                                                  |
| regex_effbot   | 3.41 ms                                                | 3.68 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 301 us: 1.60x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 235 us: 1.39x faster                                                  |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.37x faster                                                 |
| xml_etree_process    | 79.8 ms                                                | 59.2 ms: 1.35x faster                                                 |
| tomli_loads          | 3.06 sec                                               | 2.38 sec: 1.29x faster                                                |
| xml_etree_generate   | 100.0 ms                                               | 86.9 ms: 1.15x faster                                                 |
| json_loads           | 31.4 us                                                | 27.5 us: 1.14x faster                                                 |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.07x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 110 ms: 1.05x faster                                                  |
| pickle_list          | 5.05 us                                                | 4.91 us: 1.03x faster                                                 |
| unpickle_list        | 5.10 us                                                | 5.02 us: 1.02x faster                                                 |
| unpickle             | 14.9 us                                                | 15.4 us: 1.04x slower                                                 |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                                 |
| pickle_dict          | 30.0 us                                                | 33.4 us: 1.12x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                 |
| python_startup_no_site | 5.87 ms                                                | 8.99 ms: 1.53x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 13.6 ms: 1.20x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 123 us: 4.55x faster                                                  |
| generators               | 78.9 ms                                                | 30.3 ms: 2.61x faster                                                 |
| asyncio_tcp              | 918 ms                                                 | 490 ms: 1.87x faster                                                  |
| logging_silent           | 189 ns                                                 | 106 ns: 1.78x faster                                                  |
| raytrace                 | 498 ms                                                 | 290 ms: 1.72x faster                                                  |
| deltablue                | 7.81 ms                                                | 4.62 ms: 1.69x faster                                                 |
| richards_super           | 95.6 ms                                                | 56.7 ms: 1.69x faster                                                 |
| chaos                    | 114 ms                                                 | 68.6 ms: 1.67x faster                                                 |
| crypto_pyaes             | 127 ms                                                 | 76.7 ms: 1.65x faster                                                 |
| scimark_sor              | 214 ms                                                 | 130 ms: 1.65x faster                                                  |
| async_tree_none          | 732 ms                                                 | 452 ms: 1.62x faster                                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.33 ms: 1.61x faster                                                 |
| scimark_monte_carlo      | 118 ms                                                 | 73.4 ms: 1.61x faster                                                 |
| pickle_pure_python       | 482 us                                                 | 301 us: 1.60x faster                                                  |
| richards                 | 79.4 ms                                                | 50.2 ms: 1.58x faster                                                 |
| coroutines               | 34.5 ms                                                | 22.2 ms: 1.55x faster                                                 |
| sqlglot_transpile        | 2.55 ms                                                | 1.65 ms: 1.54x faster                                                 |
| async_tree_memoization   | 867 ms                                                 | 576 ms: 1.50x faster                                                  |
| go                       | 238 ms                                                 | 159 ms: 1.50x faster                                                  |
| async_tree_io            | 1.79 sec                                               | 1.21 sec: 1.48x faster                                                |
| scimark_lu               | 175 ms                                                 | 121 ms: 1.45x faster                                                  |
| deepcopy_memo            | 58.8 us                                                | 40.9 us: 1.44x faster                                                 |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                                |
| spectral_norm            | 163 ms                                                 | 115 ms: 1.42x faster                                                  |
| logging_simple           | 8.27 us                                                | 5.84 us: 1.42x faster                                                 |
| logging_format           | 9.07 us                                                | 6.44 us: 1.41x faster                                                 |
| pyflate                  | 708 ms                                                 | 507 ms: 1.40x faster                                                  |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                 |
| unpickle_pure_python     | 327 us                                                 | 235 us: 1.39x faster                                                  |
| chameleon                | 9.84 ms                                                | 7.09 ms: 1.39x faster                                                 |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 730 ms: 1.38x faster                                                  |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.37x faster                                                 |
| deepcopy                 | 481 us                                                 | 356 us: 1.35x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 59.2 ms: 1.35x faster                                                 |
| deepcopy_reduce          | 4.17 us                                                | 3.10 us: 1.35x faster                                                 |
| nbody                    | 148 ms                                                 | 111 ms: 1.34x faster                                                  |
| tornado_http             | 131 ms                                                 | 98.4 ms: 1.33x faster                                                 |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                                  |
| comprehensions           | 28.5 us                                                | 21.9 us: 1.30x faster                                                 |
| unpack_sequence          | 65.7 ns                                                | 50.6 ns: 1.30x faster                                                 |
| tomli_loads              | 3.06 sec                                               | 2.38 sec: 1.29x faster                                                |
| pprint_pformat           | 2.10 sec                                               | 1.66 sec: 1.26x faster                                                |
| pycparser                | 1.57 sec                                               | 1.25 sec: 1.26x faster                                                |
| pprint_safe_repr         | 1.01 sec                                               | 808 ms: 1.26x faster                                                  |
| mypy2                    | 442 ms                                                 | 353 ms: 1.25x faster                                                  |
| fannkuch                 | 527 ms                                                 | 422 ms: 1.25x faster                                                  |
| sqlglot_optimize         | 68.7 ms                                                | 55.1 ms: 1.25x faster                                                 |
| 2to3                     | 346 ms                                                 | 279 ms: 1.24x faster                                                  |
| sympy_sum                | 190 ms                                                 | 154 ms: 1.23x faster                                                  |
| float                    | 116 ms                                                 | 94.7 ms: 1.23x faster                                                 |
| sympy_integrate          | 25.4 ms                                                | 20.9 ms: 1.21x faster                                                 |
| docutils                 | 3.26 sec                                               | 2.70 sec: 1.21x faster                                                |
| hexiom                   | 10.3 ms                                                | 8.58 ms: 1.20x faster                                                 |
| mako                     | 16.3 ms                                                | 13.6 ms: 1.20x faster                                                 |
| sympy_str                | 337 ms                                                 | 282 ms: 1.19x faster                                                  |
| regex_compile            | 186 ms                                                 | 156 ms: 1.19x faster                                                  |
| sympy_expand             | 558 ms                                                 | 476 ms: 1.17x faster                                                  |
| bench_thread_pool        | 966 us                                                 | 837 us: 1.15x faster                                                  |
| dulwich_log              | 77.0 ms                                                | 66.9 ms: 1.15x faster                                                 |
| xml_etree_generate       | 100.0 ms                                               | 86.9 ms: 1.15x faster                                                 |
| json_loads               | 31.4 us                                                | 27.5 us: 1.14x faster                                                 |
| scimark_fft              | 454 ms                                                 | 402 ms: 1.13x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.63 sec: 1.11x faster                                                |
| nqueens                  | 107 ms                                                 | 96.2 ms: 1.11x faster                                                 |
| create_gc_cycles         | 1.61 ms                                                | 1.45 ms: 1.11x faster                                                 |
| json                     | 5.67 ms                                                | 5.13 ms: 1.10x faster                                                 |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.07x faster                                                  |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.69 ms: 1.07x faster                                                 |
| sqlite_synth             | 3.02 us                                                | 2.85 us: 1.06x faster                                                 |
| xml_etree_iterparse      | 116 ms                                                 | 110 ms: 1.05x faster                                                  |
| pathlib                  | 20.3 ms                                                | 19.7 ms: 1.03x faster                                                 |
| pickle_list              | 5.05 us                                                | 4.91 us: 1.03x faster                                                 |
| meteor_contest           | 119 ms                                                 | 116 ms: 1.03x faster                                                  |
| unpickle_list            | 5.10 us                                                | 5.02 us: 1.02x faster                                                 |
| regex_v8                 | 26.2 ms                                                | 25.9 ms: 1.01x faster                                                 |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                  |
| regex_dna                | 215 ms                                                 | 218 ms: 1.02x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 3.51 ms: 1.02x slower                                                 |
| async_generators         | 442 ms                                                 | 453 ms: 1.03x slower                                                  |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                                  |
| unpickle                 | 14.9 us                                                | 15.4 us: 1.04x slower                                                 |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                                 |
| regex_effbot             | 3.41 ms                                                | 3.68 ms: 1.08x slower                                                 |
| pickle_dict              | 30.0 us                                                | 33.4 us: 1.12x slower                                                 |
| coverage                 | 82.0 ms                                                | 95.3 ms: 1.16x slower                                                 |
| telco                    | 7.01 ms                                                | 8.57 ms: 1.22x slower                                                 |
| python_startup_no_site   | 5.87 ms                                                | 8.99 ms: 1.53x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.28x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231102-3.13.0a1+-8794817/bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1+-8794817.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.20x
