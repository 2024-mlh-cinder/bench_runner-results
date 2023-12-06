
# Results vs. 3.10.4

- fork: mdboom
- ref: count_tier2_miss_opc
- machine: linux-x86_64
- commit hash: 22212fb
- commit date: 2023-10-09
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.65 sec: 1.20x faster                                                |
| tornado_http   | 127 ms                                                 | 96.0 ms: 1.33x faster                                                 |
| Geometric mean | (ref)                                                  | 1.26x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 95.8 ms: 1.48x faster                                                 |
| float          | 111 ms                                                 | 82.8 ms: 1.33x faster                                                 |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.26x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 138 ms: 1.28x faster                                                  |
| regex_dna      | 222 ms                                                 | 208 ms: 1.07x faster                                                  |
| regex_v8       | 25.0 ms                                                | 25.5 ms: 1.02x slower                                                 |
| regex_effbot   | 3.23 ms                                                | 3.58 ms: 1.11x slower                                                 |
| Geometric mean | (ref)                                                  | 1.05x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 307 us: 1.48x faster                                                  |
| tomli_loads          | 2.92 sec                                               | 2.16 sec: 1.35x faster                                                |
| unpickle_pure_python | 300 us                                                 | 223 us: 1.34x faster                                                  |
| json_dumps           | 13.5 ms                                                | 10.4 ms: 1.31x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 60.1 ms: 1.25x faster                                                 |
| xml_etree_generate   | 94.2 ms                                                | 88.1 ms: 1.07x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.06x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.02x faster                                                  |
| json_loads           | 28.8 us                                                | 28.4 us: 1.01x faster                                                 |
| unpickle             | 14.1 us                                                | 15.1 us: 1.07x slower                                                 |
| pickle_list          | 4.56 us                                                | 4.96 us: 1.09x slower                                                 |
| pickle               | 10.3 us                                                | 11.3 us: 1.10x slower                                                 |
| unpickle_list        | 4.82 us                                                | 5.30 us: 1.10x slower                                                 |
| pickle_dict          | 27.3 us                                                | 34.8 us: 1.28x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.08x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                 |
| python_startup_no_site | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.3 ms: 1.30x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-22212fb |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 152 us: 3.35x faster                                                  |
| generators               | 76.8 ms                                                | 29.3 ms: 2.62x faster                                                 |
| deltablue                | 7.42 ms                                                | 3.36 ms: 2.21x faster                                                 |
| asyncio_tcp              | 925 ms                                                 | 468 ms: 1.98x faster                                                  |
| chaos                    | 106 ms                                                 | 61.7 ms: 1.72x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.78 sec: 1.69x faster                                                |
| raytrace                 | 464 ms                                                 | 277 ms: 1.68x faster                                                  |
| richards_super           | 90.7 ms                                                | 54.9 ms: 1.65x faster                                                 |
| crypto_pyaes             | 118 ms                                                 | 71.8 ms: 1.65x faster                                                 |
| logging_silent           | 175 ns                                                 | 107 ns: 1.64x faster                                                  |
| async_tree_none          | 717 ms                                                 | 442 ms: 1.62x faster                                                  |
| sqlglot_parse            | 2.06 ms                                                | 1.29 ms: 1.59x faster                                                 |
| go                       | 229 ms                                                 | 145 ms: 1.58x faster                                                  |
| scimark_sor              | 197 ms                                                 | 125 ms: 1.57x faster                                                  |
| richards                 | 74.9 ms                                                | 47.7 ms: 1.57x faster                                                 |
| scimark_monte_carlo      | 108 ms                                                 | 69.8 ms: 1.55x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.61 ms: 1.52x faster                                                 |
| unpack_sequence          | 64.7 ns                                                | 42.5 ns: 1.52x faster                                                 |
| hexiom                   | 9.53 ms                                                | 6.27 ms: 1.52x faster                                                 |
| async_tree_memoization   | 854 ms                                                 | 572 ms: 1.49x faster                                                  |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                |
| pickle_pure_python       | 455 us                                                 | 307 us: 1.48x faster                                                  |
| nbody                    | 142 ms                                                 | 95.8 ms: 1.48x faster                                                 |
| pyflate                  | 673 ms                                                 | 472 ms: 1.43x faster                                                  |
| coroutines               | 31.8 ms                                                | 22.4 ms: 1.42x faster                                                 |
| scimark_lu               | 163 ms                                                 | 115 ms: 1.42x faster                                                  |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                 |
| logging_format           | 8.91 us                                                | 6.55 us: 1.36x faster                                                 |
| tomli_loads              | 2.92 sec                                               | 2.16 sec: 1.35x faster                                                |
| unpickle_pure_python     | 300 us                                                 | 223 us: 1.34x faster                                                  |
| logging_simple           | 8.07 us                                                | 6.05 us: 1.33x faster                                                 |
| float                    | 111 ms                                                 | 82.8 ms: 1.33x faster                                                 |
| tornado_http             | 127 ms                                                 | 96.0 ms: 1.33x faster                                                 |
| deepcopy_memo            | 52.3 us                                                | 39.5 us: 1.33x faster                                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 717 ms: 1.33x faster                                                  |
| spectral_norm            | 150 ms                                                 | 114 ms: 1.31x faster                                                  |
| json_dumps               | 13.5 ms                                                | 10.4 ms: 1.31x faster                                                 |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                                |
| mako                     | 14.8 ms                                                | 11.3 ms: 1.30x faster                                                 |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.30x faster                                                |
| sqlglot_normalize        | 135 ms                                                 | 105 ms: 1.28x faster                                                  |
| regex_compile            | 177 ms                                                 | 138 ms: 1.28x faster                                                  |
| pprint_safe_repr         | 955 ms                                                 | 748 ms: 1.28x faster                                                  |
| comprehensions           | 26.8 us                                                | 21.4 us: 1.25x faster                                                 |
| xml_etree_process        | 74.9 ms                                                | 60.1 ms: 1.25x faster                                                 |
| mypy2                    | 428 ms                                                 | 345 ms: 1.24x faster                                                  |
| deepcopy                 | 442 us                                                 | 358 us: 1.23x faster                                                  |
| sqlglot_optimize         | 65.3 ms                                                | 53.5 ms: 1.22x faster                                                 |
| nqueens                  | 100 ms                                                 | 82.4 ms: 1.21x faster                                                 |
| deepcopy_reduce          | 3.82 us                                                | 3.17 us: 1.21x faster                                                 |
| fannkuch                 | 486 ms                                                 | 406 ms: 1.20x faster                                                  |
| docutils                 | 3.17 sec                                               | 2.65 sec: 1.20x faster                                                |
| bench_thread_pool        | 947 us                                                 | 818 us: 1.16x faster                                                  |
| scimark_fft              | 424 ms                                                 | 373 ms: 1.14x faster                                                  |
| dulwich_log              | 75.9 ms                                                | 67.5 ms: 1.13x faster                                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.96 ms: 1.10x faster                                                 |
| create_gc_cycles         | 1.67 ms                                                | 1.55 ms: 1.08x faster                                                 |
| mdp                      | 2.82 sec                                               | 2.62 sec: 1.08x faster                                                |
| xml_etree_generate       | 94.2 ms                                                | 88.1 ms: 1.07x faster                                                 |
| regex_dna                | 222 ms                                                 | 208 ms: 1.07x faster                                                  |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.06x faster                                                  |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.06x faster                                                 |
| json                     | 5.42 ms                                                | 5.14 ms: 1.05x faster                                                 |
| meteor_contest           | 115 ms                                                 | 110 ms: 1.05x faster                                                  |
| sqlite_synth             | 2.93 us                                                | 2.84 us: 1.03x faster                                                 |
| xml_etree_parse          | 163 ms                                                 | 160 ms: 1.02x faster                                                  |
| json_loads               | 28.8 us                                                | 28.4 us: 1.01x faster                                                 |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                  |
| regex_v8                 | 25.0 ms                                                | 25.5 ms: 1.02x slower                                                 |
| unpickle                 | 14.1 us                                                | 15.1 us: 1.07x slower                                                 |
| async_generators         | 425 ms                                                 | 459 ms: 1.08x slower                                                  |
| pickle_list              | 4.56 us                                                | 4.96 us: 1.09x slower                                                 |
| pickle                   | 10.3 us                                                | 11.3 us: 1.10x slower                                                 |
| unpickle_list            | 4.82 us                                                | 5.30 us: 1.10x slower                                                 |
| regex_effbot             | 3.23 ms                                                | 3.58 ms: 1.11x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 4.36 ms: 1.13x slower                                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                 |
| coverage                 | 72.8 ms                                                | 90.3 ms: 1.24x slower                                                 |
| telco                    | 6.54 ms                                                | 8.33 ms: 1.27x slower                                                 |
| pickle_dict              | 27.3 us                                                | 34.8 us: 1.28x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
