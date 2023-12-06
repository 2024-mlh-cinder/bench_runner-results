
# Results vs. 3.10.4

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 237c561
- commit date: 2023-10-09
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.77 sec: 1.15x faster                                               |
| tornado_http   | 127 ms                                                 | 102 ms: 1.25x faster                                                 |
| Geometric mean | (ref)                                                  | 1.19x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 114 ms: 1.24x faster                                                 |
| float          | 111 ms                                                 | 95.1 ms: 1.16x faster                                                |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                  | 1.13x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 162 ms: 1.09x faster                                                 |
| regex_dna      | 222 ms                                                 | 208 ms: 1.06x faster                                                 |
| regex_v8       | 25.0 ms                                                | 24.9 ms: 1.01x faster                                                |
| regex_effbot   | 3.23 ms                                                | 3.58 ms: 1.11x slower                                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 310 us: 1.47x faster                                                 |
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.29x faster                                                |
| unpickle_pure_python | 300 us                                                 | 240 us: 1.25x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 60.6 ms: 1.24x faster                                                |
| tomli_loads          | 2.92 sec                                               | 2.41 sec: 1.21x faster                                               |
| xml_etree_generate   | 94.2 ms                                                | 88.6 ms: 1.06x faster                                                |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                                 |
| json_loads           | 28.8 us                                                | 28.2 us: 1.02x faster                                                |
| xml_etree_iterparse  | 111 ms                                                 | 110 ms: 1.01x faster                                                 |
| pickle               | 10.3 us                                                | 10.9 us: 1.06x slower                                                |
| unpickle             | 14.1 us                                                | 15.2 us: 1.07x slower                                                |
| unpickle_list        | 4.82 us                                                | 5.21 us: 1.08x slower                                                |
| pickle_list          | 4.56 us                                                | 4.97 us: 1.09x slower                                                |
| pickle_dict          | 27.3 us                                                | 34.4 us: 1.26x slower                                                |
| Geometric mean       | (ref)                                                  | 1.06x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                |
| python_startup_no_site | 5.82 ms                                                | 6.84 ms: 1.18x slower                                                |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 13.4 ms: 1.10x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 159 us: 3.21x faster                                                 |
| generators               | 76.8 ms                                                | 30.7 ms: 2.50x faster                                                |
| asyncio_tcp              | 925 ms                                                 | 472 ms: 1.96x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                               |
| logging_silent           | 175 ns                                                 | 109 ns: 1.60x faster                                                 |
| richards_super           | 90.7 ms                                                | 56.7 ms: 1.60x faster                                                |
| async_tree_none          | 717 ms                                                 | 451 ms: 1.59x faster                                                 |
| deltablue                | 7.42 ms                                                | 4.80 ms: 1.55x faster                                                |
| sqlglot_parse            | 2.06 ms                                                | 1.35 ms: 1.53x faster                                                |
| scimark_sor              | 197 ms                                                 | 129 ms: 1.52x faster                                                 |
| richards                 | 74.9 ms                                                | 49.9 ms: 1.50x faster                                                |
| raytrace                 | 464 ms                                                 | 310 ms: 1.50x faster                                                 |
| async_tree_io            | 1.77 sec                                               | 1.20 sec: 1.48x faster                                               |
| async_tree_memoization   | 854 ms                                                 | 580 ms: 1.47x faster                                                 |
| pickle_pure_python       | 455 us                                                 | 310 us: 1.47x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.67 ms: 1.47x faster                                                |
| chaos                    | 106 ms                                                 | 74.2 ms: 1.43x faster                                                |
| scimark_monte_carlo      | 108 ms                                                 | 76.7 ms: 1.41x faster                                                |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                |
| crypto_pyaes             | 118 ms                                                 | 84.0 ms: 1.41x faster                                                |
| go                       | 229 ms                                                 | 169 ms: 1.36x faster                                                 |
| coroutines               | 31.8 ms                                                | 23.4 ms: 1.36x faster                                                |
| scimark_lu               | 163 ms                                                 | 122 ms: 1.34x faster                                                 |
| spectral_norm            | 150 ms                                                 | 115 ms: 1.31x faster                                                 |
| json_dumps               | 13.5 ms                                                | 10.5 ms: 1.29x faster                                                |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 737 ms: 1.29x faster                                                 |
| pyflate                  | 673 ms                                                 | 526 ms: 1.28x faster                                                 |
| unpack_sequence          | 64.7 ns                                                | 50.6 ns: 1.28x faster                                                |
| logging_simple           | 8.07 us                                                | 6.45 us: 1.25x faster                                                |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.25x faster                                                 |
| unpickle_pure_python     | 300 us                                                 | 240 us: 1.25x faster                                                 |
| pycparser                | 1.50 sec                                               | 1.20 sec: 1.25x faster                                               |
| tornado_http             | 127 ms                                                 | 102 ms: 1.25x faster                                                 |
| nbody                    | 142 ms                                                 | 114 ms: 1.24x faster                                                 |
| deepcopy_memo            | 52.3 us                                                | 42.2 us: 1.24x faster                                                |
| xml_etree_process        | 74.9 ms                                                | 60.6 ms: 1.24x faster                                                |
| deepcopy                 | 442 us                                                 | 361 us: 1.22x faster                                                 |
| logging_format           | 8.91 us                                                | 7.33 us: 1.22x faster                                                |
| tomli_loads              | 2.92 sec                                               | 2.41 sec: 1.21x faster                                               |
| deepcopy_reduce          | 3.82 us                                                | 3.19 us: 1.20x faster                                                |
| mypy2                    | 428 ms                                                 | 358 ms: 1.20x faster                                                 |
| pprint_pformat           | 1.99 sec                                               | 1.67 sec: 1.19x faster                                               |
| sqlglot_optimize         | 65.3 ms                                                | 55.1 ms: 1.19x faster                                                |
| pprint_safe_repr         | 955 ms                                                 | 809 ms: 1.18x faster                                                 |
| float                    | 111 ms                                                 | 95.1 ms: 1.16x faster                                                |
| docutils                 | 3.17 sec                                               | 2.77 sec: 1.15x faster                                               |
| bench_thread_pool        | 947 us                                                 | 845 us: 1.12x faster                                                 |
| mako                     | 14.8 ms                                                | 13.4 ms: 1.10x faster                                                |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                                |
| regex_compile            | 177 ms                                                 | 162 ms: 1.09x faster                                                 |
| fannkuch                 | 486 ms                                                 | 449 ms: 1.08x faster                                                 |
| dulwich_log              | 75.9 ms                                                | 70.3 ms: 1.08x faster                                                |
| regex_dna                | 222 ms                                                 | 208 ms: 1.06x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 88.6 ms: 1.06x faster                                                |
| hexiom                   | 9.53 ms                                                | 9.04 ms: 1.05x faster                                                |
| json                     | 5.42 ms                                                | 5.14 ms: 1.05x faster                                                |
| sqlite_synth             | 2.93 us                                                | 2.83 us: 1.04x faster                                                |
| mdp                      | 2.82 sec                                               | 2.74 sec: 1.03x faster                                               |
| xml_etree_parse          | 163 ms                                                 | 159 ms: 1.03x faster                                                 |
| json_loads               | 28.8 us                                                | 28.2 us: 1.02x faster                                                |
| pathlib                  | 20.0 ms                                                | 19.8 ms: 1.01x faster                                                |
| xml_etree_iterparse      | 111 ms                                                 | 110 ms: 1.01x faster                                                 |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                 |
| regex_v8                 | 25.0 ms                                                | 24.9 ms: 1.01x faster                                                |
| scimark_fft              | 424 ms                                                 | 427 ms: 1.01x slower                                                 |
| meteor_contest           | 115 ms                                                 | 116 ms: 1.01x slower                                                 |
| pickle                   | 10.3 us                                                | 10.9 us: 1.06x slower                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.81 ms: 1.07x slower                                                |
| unpickle                 | 14.1 us                                                | 15.2 us: 1.07x slower                                                |
| unpickle_list            | 4.82 us                                                | 5.21 us: 1.08x slower                                                |
| pickle_list              | 4.56 us                                                | 4.97 us: 1.09x slower                                                |
| regex_effbot             | 3.23 ms                                                | 3.58 ms: 1.11x slower                                                |
| gc_traversal             | 3.84 ms                                                | 4.35 ms: 1.13x slower                                                |
| async_generators         | 425 ms                                                 | 484 ms: 1.14x slower                                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.84 ms: 1.18x slower                                                |
| coverage                 | 72.8 ms                                                | 90.8 ms: 1.25x slower                                                |
| pickle_dict              | 27.3 us                                                | 34.4 us: 1.26x slower                                                |
| telco                    | 6.54 ms                                                | 8.69 ms: 1.33x slower                                                |
| Geometric mean           | (ref)                                                  | 1.20x faster                                                         |

Benchmark hidden because not significant (3): nqueens, bench_mp_pool, comprehensions
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.12x
