
# Results vs. 3.10.4

- fork: mdboom
- ref: count_tier2_miss_opc
- machine: linux-x86_64
- commit hash: 8ce6535
- commit date: 2023-10-09
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.65 sec: 1.19x faster                                                |
| tornado_http   | 127 ms                                                 | 96.2 ms: 1.32x faster                                                 |
| Geometric mean | (ref)                                                  | 1.26x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 95.9 ms: 1.48x faster                                                 |
| float          | 111 ms                                                 | 80.7 ms: 1.37x faster                                                 |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.27x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 139 ms: 1.27x faster                                                  |
| regex_dna      | 222 ms                                                 | 207 ms: 1.07x faster                                                  |
| regex_v8       | 25.0 ms                                                | 25.6 ms: 1.02x slower                                                 |
| regex_effbot   | 3.23 ms                                                | 3.57 ms: 1.10x slower                                                 |
| Geometric mean | (ref)                                                  | 1.05x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 305 us: 1.49x faster                                                  |
| tomli_loads          | 2.92 sec                                               | 2.15 sec: 1.36x faster                                                |
| unpickle_pure_python | 300 us                                                 | 222 us: 1.35x faster                                                  |
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.30x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 59.2 ms: 1.27x faster                                                 |
| xml_etree_generate   | 94.2 ms                                                | 86.5 ms: 1.09x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.06x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                                  |
| unpickle             | 14.1 us                                                | 14.9 us: 1.05x slower                                                 |
| pickle               | 10.3 us                                                | 11.1 us: 1.08x slower                                                 |
| unpickle_list        | 4.82 us                                                | 5.31 us: 1.10x slower                                                 |
| pickle_list          | 4.56 us                                                | 5.18 us: 1.14x slower                                                 |
| pickle_dict          | 27.3 us                                                | 33.1 us: 1.22x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.09x faster                                                          |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                 |
| python_startup_no_site | 5.82 ms                                                | 6.85 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.5 ms: 1.29x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 153 us: 3.34x faster                                                  |
| generators               | 76.8 ms                                                | 29.2 ms: 2.63x faster                                                 |
| deltablue                | 7.42 ms                                                | 3.37 ms: 2.20x faster                                                 |
| asyncio_tcp              | 925 ms                                                 | 466 ms: 1.99x faster                                                  |
| chaos                    | 106 ms                                                 | 62.4 ms: 1.70x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.77 sec: 1.69x faster                                                |
| raytrace                 | 464 ms                                                 | 281 ms: 1.65x faster                                                  |
| crypto_pyaes             | 118 ms                                                 | 71.8 ms: 1.65x faster                                                 |
| async_tree_none          | 717 ms                                                 | 437 ms: 1.64x faster                                                  |
| logging_silent           | 175 ns                                                 | 107 ns: 1.63x faster                                                  |
| richards_super           | 90.7 ms                                                | 55.6 ms: 1.63x faster                                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                                 |
| go                       | 229 ms                                                 | 144 ms: 1.59x faster                                                  |
| scimark_sor              | 197 ms                                                 | 125 ms: 1.58x faster                                                  |
| scimark_monte_carlo      | 108 ms                                                 | 69.4 ms: 1.56x faster                                                 |
| richards                 | 74.9 ms                                                | 48.7 ms: 1.54x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                                 |
| hexiom                   | 9.53 ms                                                | 6.22 ms: 1.53x faster                                                 |
| async_tree_memoization   | 854 ms                                                 | 566 ms: 1.51x faster                                                  |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.50x faster                                                |
| pickle_pure_python       | 455 us                                                 | 305 us: 1.49x faster                                                  |
| nbody                    | 142 ms                                                 | 95.9 ms: 1.48x faster                                                 |
| coroutines               | 31.8 ms                                                | 22.0 ms: 1.45x faster                                                 |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.44x faster                                                  |
| pyflate                  | 673 ms                                                 | 471 ms: 1.43x faster                                                  |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                 |
| float                    | 111 ms                                                 | 80.7 ms: 1.37x faster                                                 |
| logging_format           | 8.91 us                                                | 6.53 us: 1.36x faster                                                 |
| tomli_loads              | 2.92 sec                                               | 2.15 sec: 1.36x faster                                                |
| logging_simple           | 8.07 us                                                | 5.95 us: 1.36x faster                                                 |
| unpickle_pure_python     | 300 us                                                 | 222 us: 1.35x faster                                                  |
| spectral_norm            | 150 ms                                                 | 112 ms: 1.34x faster                                                  |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 711 ms: 1.34x faster                                                  |
| tornado_http             | 127 ms                                                 | 96.2 ms: 1.32x faster                                                 |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.31x faster                                                |
| deepcopy_memo            | 52.3 us                                                | 39.9 us: 1.31x faster                                                 |
| json_dumps               | 13.5 ms                                                | 10.4 ms: 1.30x faster                                                 |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.29x faster                                                |
| mako                     | 14.8 ms                                                | 11.5 ms: 1.29x faster                                                 |
| pprint_safe_repr         | 955 ms                                                 | 743 ms: 1.28x faster                                                  |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.28x faster                                                  |
| regex_compile            | 177 ms                                                 | 139 ms: 1.27x faster                                                  |
| xml_etree_process        | 74.9 ms                                                | 59.2 ms: 1.27x faster                                                 |
| comprehensions           | 26.8 us                                                | 21.3 us: 1.26x faster                                                 |
| nqueens                  | 100 ms                                                 | 80.1 ms: 1.25x faster                                                 |
| mypy2                    | 428 ms                                                 | 344 ms: 1.24x faster                                                  |
| unpack_sequence          | 64.7 ns                                                | 52.0 ns: 1.24x faster                                                 |
| deepcopy                 | 442 us                                                 | 358 us: 1.24x faster                                                  |
| sqlglot_optimize         | 65.3 ms                                                | 53.3 ms: 1.23x faster                                                 |
| fannkuch                 | 486 ms                                                 | 397 ms: 1.23x faster                                                  |
| deepcopy_reduce          | 3.82 us                                                | 3.19 us: 1.20x faster                                                 |
| docutils                 | 3.17 sec                                               | 2.65 sec: 1.19x faster                                                |
| bench_thread_pool        | 947 us                                                 | 816 us: 1.16x faster                                                  |
| scimark_fft              | 424 ms                                                 | 375 ms: 1.13x faster                                                  |
| dulwich_log              | 75.9 ms                                                | 67.5 ms: 1.12x faster                                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 86.5 ms: 1.09x faster                                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.02 ms: 1.09x faster                                                 |
| regex_dna                | 222 ms                                                 | 207 ms: 1.07x faster                                                  |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.06x faster                                                  |
| meteor_contest           | 115 ms                                                 | 109 ms: 1.05x faster                                                  |
| mdp                      | 2.82 sec                                               | 2.69 sec: 1.05x faster                                                |
| pathlib                  | 20.0 ms                                                | 19.1 ms: 1.05x faster                                                 |
| json                     | 5.42 ms                                                | 5.17 ms: 1.05x faster                                                 |
| xml_etree_parse          | 163 ms                                                 | 158 ms: 1.03x faster                                                  |
| sqlite_synth             | 2.93 us                                                | 2.85 us: 1.03x faster                                                 |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                                  |
| regex_v8                 | 25.0 ms                                                | 25.6 ms: 1.02x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 3.97 ms: 1.03x slower                                                 |
| unpickle                 | 14.1 us                                                | 14.9 us: 1.05x slower                                                 |
| pickle                   | 10.3 us                                                | 11.1 us: 1.08x slower                                                 |
| async_generators         | 425 ms                                                 | 461 ms: 1.08x slower                                                  |
| unpickle_list            | 4.82 us                                                | 5.31 us: 1.10x slower                                                 |
| regex_effbot             | 3.23 ms                                                | 3.57 ms: 1.10x slower                                                 |
| pickle_list              | 4.56 us                                                | 5.18 us: 1.14x slower                                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.85 ms: 1.18x slower                                                 |
| pickle_dict              | 27.3 us                                                | 33.1 us: 1.22x slower                                                 |
| coverage                 | 72.8 ms                                                | 91.6 ms: 1.26x slower                                                 |
| telco                    | 6.54 ms                                                | 8.51 ms: 1.30x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                          |

Benchmark hidden because not significant (2): json_loads, bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.22x
